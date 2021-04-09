# Nearby Place Search<a name="EN-US_TOPIC_0000001099163568"></a>

-   [Procedure](#section1562015393314)
-   [Sample Code](#section28803277330)

With this function, your app can return a list of nearby places based on the current location of a user. When the user selects a place, the app obtains the place ID and searches for details about the place.

## Procedure<a name="section1562015393314"></a>

1.  Initialize the  [HWSiteService](en-us_topic_0000001098843524.md)  object through  **HWMapJsSDK**.
2.  Construct a nearby place search request. In the request, the  **location**  parameter is mandatory and other parameters are optional. The  **politicalView**  parameter has been deprecated.
    -   **location**: current location of a user.
    -   **radius**: search radius, in meters. The value ranges from 1 to 50000. The default value is  **1000**.
    -   **query**: search keyword.
    -   **poiType**: type of the POI to be returned.
    -   **language**: language in which the search results are displayed. If no language is specified, the local language will be used.
    -   **pageSize**: number of records on each page. The value ranges from 1 to 20. The default value is  **20**.
    -   **pageIndex**: current page number. The value ranges from 1 to 60. The default value is  **1**.
    -   **politicalView**: political view. The value is a two-letter country or region code complying with the ISO 3166-1 alpha-2 standard. This parameter has been deprecated.

3.  Call the  **nearbySearch**  API through the initialized  [HWSiteService](en-us_topic_0000001098843524.md)  object, and pass the created request. 
4.  Obtain the search result. You can obtain the search result \(**result**\) and search status \(**status**\) through the callback functions of the  **nearbySearch**  API. For details about status, please refer to  [Result Codes](en-us_topic_0000001099163496.md). The result contains the following fields:
    -   **sites**: search result, which is a  [Site](en-us_topic_0000001145523549.md#sea6a597b34a74d6aa464f0ce92e35c48)**\[\]**  array. For details about the array, please refer to  [Parameters](en-us_topic_0000001145523549.md).
    -   **totalCount**: total number of search result records.


## Sample Code<a name="section28803277330"></a>

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
	location: {
		lat: 48.893478,
		lng: 2.334595
	}
};
// Call the search API. In the API, result indicates the search result and status indicates the search status. 
siteService.nearbySearch(request, function (result, status) {
	if (status == '0') {
		for (var i = 0; i < result.sites.length; i++) {
			// Add a marker on the map.
			var marker = new HWMapJsSDK.HWMarker({
				map: map,
				position: {lat: result.sites[i].location.lat, lng: result.sites[i].location.lng},
				label: result.sites[i].name
			});
		}
		// Set the map center.
		map.setCenter({lat: result.sites[0].location.lat, lng: result.sites[0].location.lng})
	}
});
```

