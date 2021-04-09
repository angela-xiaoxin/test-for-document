# Place Search Suggestion<a name="EN-US_TOPIC_0000001099003572"></a>

-   [Procedure](#section05671521114112)
-   [Sample Code](#section1715816329413)

This section describes how to display suggested search places in real time during user input. 

## Procedure<a name="section05671521114112"></a>

1.  Initialize the  [HWSiteService](en-us_topic_0000001098843524.md)  object through  **HWMapJsSDK**.
2.  Construct a place search suggestion request. In the request, the  **query**  parameter is mandatory and other parameters are optional. The  **politicalView**  parameter has been deprecated.
    -   **query**: search keyword.
    -   **location**: longitude and latitude to which search results need to be biased.
    -   **radius**: search radius, in meters. The value ranges from 1 to 50000. The default value is  **50000**.
    -   **bounds**: coordinate bounds to which search results need to be biased.
    -   **poiType**: type of the POI to be returned.
    -   **countryCode**: code of the country where places are searched. The country code must comply with the ISO 3166-1 alpha-2 standard. 
    -   **language**: language in which the search results are displayed. If no language is specified, the local language will be used.
    -   **politicalView**: political view. The value is a two-letter country or region code complying with the ISO 3166-1 alpha-2 standard. This parameter has been deprecated.

3.  Call the  **querySuggestion**  API through the initialized  [HWSiteService](en-us_topic_0000001098843524.md)  object, and pass the created request. 
4.  Obtain the search result. You can obtain the search result \(**result**\) and search status \(**status**\) through the callback functions of the  **querySuggestion**  API. For details about status, please refer to  [Result Codes](en-us_topic_0000001099163496.md). The result contains the following field:

    **sites**: search result, which is a  [Site](en-us_topic_0000001145523549.md#sea6a597b34a74d6aa464f0ce92e35c48)**\[\]**  array of up to 5 records. For details about the array, please refer to  [Parameters](en-us_topic_0000001145523549.md).


## Sample Code<a name="section1715816329413"></a>

```
var map;
var mapOptions = {};
mapOptions.center = {lat: 48.856613, lng: 2.352222};
mapOptions.zoom = 15;
map = new HWMapJsSDK.HWMap(document.getElementById('map'), mapOptions);
var siteService
// Initialize the HWSiteService object.
siteService = new HWMapJsSDK.HWSiteService();
// Construct a request.
var request = {
    query: "coffee"
};

siteService.querySuggestion(request, function (result, status) {
    if (status == '0') {
        for (var i = 0; i < result.sites.length; i++) {
			// Add a marker on the map.
            var marker = new HWMapJsSDK.HWMarker({
                map: map,
                position: {lat: result.sites[i].location.lat, lng: result.sites[i].location.lng},
                label: result.sites[i].name
            });
            // Set the map center.
            map.setCenter({lat: result.sites[0].location.lat, lng: result.sites[0].location.lng})
        }
    }
});
```

