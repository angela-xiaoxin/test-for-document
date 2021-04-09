# Reverse Geocoding<a name="EN-US_TOPIC_0000001145523591"></a>

-   [Procedure](#section524014583501)
-   [Sample Code](#section686017745117)

This section describes how to obtain places corresponding to the specified longitudes and latitudes. A maximum of 11 records can be returned.

## Procedure<a name="section524014583501"></a>

1.  Initialize the  [HWSiteService](en-us_topic_0000001098843524.md)  object through  **HWMapJsSDK**.
2.  Construct a request. In the request, the  **location**  parameter is mandatory and other parameters are optional. The  **politicalView**  parameter has been deprecated.
    -   **location**: longitude and latitude of a place.
    -   **language**: language in which the search results are displayed. If no language is specified, the local language will be used. For details, please refer to  [Supported Languages](en-us_topic_0000001050162856.md).
    -   **politicalView**: political view. The value is a two-letter country or region code complying with the ISO 3166-1 alpha-2 standard. This parameter has been deprecated.
    -   **returnPoi**: Indicates whether to return the place name of a POI. The default value is  **true**.

3.  Call the  **reverseGeocode**  API through the initialized  [HWSiteService](en-us_topic_0000001098843524.md)  object, and pass the created request. 
4.  Obtain the search result. You can obtain the search result \(**result**\) and search status \(**status**\) through the callback functions of the  **reverseGeocode**  API. For details about status, please refer to  [Result Codes](en-us_topic_0000001099163496.md). The result contains the following field:

    **sites**: search result, which is a  [Site](en-us_topic_0000001145523549.md#sea6a597b34a74d6aa464f0ce92e35c48)**\[\]**  array of up to 11 records. For details about the array, please refer to  [Parameters](en-us_topic_0000001145523549.md). Note that the  **Site**  array does not contain the POI information. 


## Sample Code<a name="section686017745117"></a>

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
                location: {
                    lat: 18.0527,
                    lng: 77.2155
                }
            };
            // Call the reverse geocoding API. In the API, result indicates the search result and status indicates the search status. 
            siteService.reverseGeocode(request, function (result, status) {
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

