# Forward Geocoding<a name="EN-US_TOPIC_0000001145843429"></a>

-   [Procedure](#section8420822175014)
-   [Sample Code](#section48971631185010)

This section describes how to obtain the longitudes and latitudes of places. A maximum of 10 records can be returned. 

## Procedure<a name="section8420822175014"></a>

1.  Initialize the  [HWSiteService](en-us_topic_0000001098843524.md)  object through  **HWMapJsSDK**.
2.  Construct a request. In the request, the  **address**  parameter is mandatory and other parameters are optional. The  **politicalView**  parameter has been deprecated.
    -   **address**: place information.
    -   **bounds**: coordinate bounds to which search results need to be biased.
    -   **language**: language in which the search results are displayed. If no language is specified, the local language will be used. For details, please refer to  [Supported Languages](en-us_topic_0000001050162856.md).
    -   **politicalView**: political view. The value is a two-letter country or region code complying with the ISO 3166-1 alpha-2 standard. This parameter has been deprecated.

3.  Call the  **geocode**  API through the initialized  [HWSiteService](en-us_topic_0000001098843524.md)  object, and pass the created request. 
4.  Obtain the search result. You can obtain the search result \(**result**\) and search status \(**status**\) through the callback functions of the  **geocode**  API. For details about status, please refer to  [Result Codes](en-us_topic_0000001099163496.md). The result contains the following field:

    **sites**: search result, which is a  [Site](en-us_topic_0000001145523549.md#sea6a597b34a74d6aa464f0ce92e35c48)**\[\]**  array of up to 10 records. For details about the array, please refer to  [Parameters](en-us_topic_0000001145523549.md).


## Sample Code<a name="section48971631185010"></a>

```
<body>
    <div id="map"></div>
    <script>
        var markers = [];
        var map;
        var mapOptions = {};
        function initMap() {
            mapOptions.center = {lat: 48.856613, lng: 2.352222};
            mapOptions.zoom = 8;
            map = new HWMapJsSDK.HWMap(document.getElementById('map'), mapOptions);
            var siteService
            // Initialize the HWSiteService object.
            siteService = new HWMapJsSDK.HWSiteService();
            // Construct a request.
            var request = {
                address: '57,RUE DU CAPITAINE PICAVET,LEERS,LEERS,NORD,HAUTS-DE-FRANCE,France'
            };
            // Call the forward geocoding API. In the API, result indicates the search result and status indicates the search status. 
            siteService.geocode(request, function (result, status) {
                if (status == '0') {
                    const res = result && result.sites && result.sites[0].location
                    if (res) {
                        // Add a marker.
                        var marker = new HWMapJsSDK.HWMarker({
                            map: map,
                            position: {lat: res.lat, lng: res.lng},
                            label: result.sites[0].name
                        });
                        markers.push(marker);
                        // Set the map center.
                        map.setCenter({lat: res.lat, lng: res.lng})
                    }
                }
            });
        }
    </script>
</body>
```

