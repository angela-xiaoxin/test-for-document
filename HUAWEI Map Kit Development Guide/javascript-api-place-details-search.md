# Place Details Search<a name="EN-US_TOPIC_0000001098683750"></a>

-   [Procedure](#section188145510364)
-   [Sample Code](#section12972209377)

With this function, users can search for details about a place based on the unique ID \(**siteId**\) of the place.

## Procedure<a name="section188145510364"></a>

1.  Initialize the  [HWSiteService](en-us_topic_0000001098843524.md)  object through  **HWMapJsSDK**.
2.  Construct a place details search request, and pass the following parameters to the request. The  **politicalView**  parameter has been deprecated.
    -   **siteId**: ID of a place. This parameter is mandatory.
    -   **language**: language in which the search results are displayed. This parameter is optional. If no language is specified, the local language will be used.
    -   **politicalView**: political view. The value is a two-letter country or region code complying with the ISO 3166-1 alpha-2 standard. This parameter has been deprecated.

3.  Call the  **searchById**  API through the initialized  [HWSiteService](en-us_topic_0000001098843524.md)  object, and pass the created request. 
4.  Obtain the search result. You can obtain the search result \(**result**\) and search status \(**status**\) through the callback functions of the  **searchById**  API. For details about status, please refer to  [Result Codes](en-us_topic_0000001099163496.md). The result contains the following field:

    **site**: search result, which is a  [Site](en-us_topic_0000001145523549.md#sea6a597b34a74d6aa464f0ce92e35c48)  object. For details about the array, please refer to  [Parameters](en-us_topic_0000001145523549.md).


## Sample Code<a name="section12972209377"></a>

```
var map;
var mapOptions = {};
mapOptions.zoom = 15;
map = new HWMapJsSDK.HWMap(document.getElementById('map'), mapOptions);
var siteService
// Initialize the HWSiteService object.
siteService = new HWMapJsSDK.HWSiteService();
// Construct a request.
var request = {
    siteId: "F45411D2CC51C59156364492A8D13622"
};

siteService.searchById(request, function (result, status) {
    if (status == '0') {
        var marker = new HWMapJsSDK.HWMarker({
            map: map,
            position: {lat: result.site.location.lat, lng: result.site.location.lng},
            label: result.site.name
        });
        map.setCenter({lat: result.site.location.lat, lng: result.site.location.lng})
    }
});
```

