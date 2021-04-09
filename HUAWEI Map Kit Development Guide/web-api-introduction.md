# Service Introduction<a name="EN-US_TOPIC_0000001098843582"></a>

-   [Directions API](#section160152955116)
-   [Matrix API](#section61061048195215)
-   [Maps Static API](#section193266447536)
-   [Tile API](#section13215144920533)
-   [Use Cases](#section2827122911617)
-   [Function Restrictions](#section1425318477373)

Map Kit provides a set of HTTP/HTTPS APIs, with which you can use map data and develop functions such as route planning, static map, and raster map. When your app calls the APIs, related data will be returned in JSON format.

Before using the service, you need to obtain the API key by referring to  [Obtaining the API Key](web-api-preparations.md#section169441820428).

When using the route planning service, ensure that the planned routes are in the countries or regions that support this service. For details, please refer to  [Supported Countries/Regions \(Route Planning\)](supported-countries-and-regions-route-planning.md).

## Directions API<a name="section160152955116"></a>

Directions API is a set of HTTPS-based APIs used to plan routes for walking, cycling, and driving, and calculate route distances. The APIs return route data in JSON format and support planning of the following types of routes:

-   **Walking route**

    Plans a walking route within a distance of 150 kilometers.


-   **Cycling route**

    Plans a cycling route within a distance of 100 kilometers.


-   **Driving route**

    Plans driving routes. This function can:

    -   Return up to 3 routes for a request.
    -   Support up to 5 waypoints.
    -   Support planning for travel in the future.
    -   Plan routes based on real-time traffic conditions.


## Matrix API<a name="section61061048195215"></a>

Matrix API is a set of APIs for calculating the distances and journey time of routes between multiple departure places and destinations. The APIs also support walking, cycling, and driving routes.

-   **Walking route**

    Plans walking routes within a distance of 150 kilometers.

-   **Cycling route**

    Plans cycling routes within a distance of 100 kilometers.

-   **Driving route**

    Plans driving routes.


## Maps Static API<a name="section193266447536"></a>

Maps Static API creates a map based on the URL parameter in the HTTP request, and return the created map as an image that can be displayed on web pages.

The API allows you to develop a rendered map of a specified area and with specified additional information as needed, and returns a map image rendered in real time. You can specify the location for requesting the map and the map image size, as well as adding ground overlays such as markers, polylines, and polygons.

## Tile API<a name="section13215144920533"></a>

Tile API allows you to directly access Huawei's map tile data through the URL parameter in the HTTP request. You can request independent map tiles to build a map layer, so that the map can be easily loaded to an existing map platform. For example, you can load the tiles to the QGIS or ArcGIS platform on the PC, or to the existing map as tile overlays in mobile apps.

## Use Cases<a name="section2827122911617"></a>

<a name="table8957161316424"></a>
<table><thead align="left"><tr id="row895791316422"><th class="cellrowborder" valign="top" width="25%" id="mcps1.1.3.1.1"><p id="p17957913154219"><a name="p17957913154219"></a><a name="p17957913154219"></a>Use Case</p>
</th>
<th class="cellrowborder" valign="top" width="75%" id="mcps1.1.3.1.2"><p id="p29571913134212"><a name="p29571913134212"></a><a name="p29571913134212"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row731914131394"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.3.1.1 "><p id="p1231915131591"><a name="p1231915131591"></a><a name="p1231915131591"></a>Directions API</p>
</td>
<td class="cellrowborder" valign="top" width="75%" headers="mcps1.1.3.1.2 "><p id="p1831911314917"><a name="p1831911314917"></a><a name="p1831911314917"></a>Plans a walking, cycling, or driving route between two points. It will return the most efficient route.</p>
</td>
</tr>
<tr id="row3903113199"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.3.1.1 "><p id="p1290341312914"><a name="p1290341312914"></a><a name="p1290341312914"></a>Matrix API</p>
</td>
<td class="cellrowborder" valign="top" width="75%" headers="mcps1.1.3.1.2 "><p id="p990313132914"><a name="p990313132914"></a><a name="p990313132914"></a>Plans walking, cycling, or driving routes between multiple departure places and destinations, including calculating the distance and journey time for each route.</p>
</td>
</tr>
<tr id="row1979814161093"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.3.1.1 "><p id="p779812164915"><a name="p779812164915"></a><a name="p779812164915"></a>Maps Static API</p>
</td>
<td class="cellrowborder" valign="top" width="75%" headers="mcps1.1.3.1.2 "><p id="p67983161598"><a name="p67983161598"></a><a name="p67983161598"></a>Creates a map image based on the URL parameter in the HTTP request, and directly embeds the map image to the web page, without using the JavaScript or dynamic page loading.</p>
</td>
</tr>
<tr id="row52161317299"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.3.1.1 "><p id="p1821651712914"><a name="p1821651712914"></a><a name="p1821651712914"></a>Tile API</p>
</td>
<td class="cellrowborder" valign="top" width="75%" headers="mcps1.1.3.1.2 "><a name="ul5360115911015"></a><a name="ul5360115911015"></a><ul id="ul5360115911015"><li>Loads the tiles to the QGIS or ArcGIS platform on the PC. </li><li>Loads the tiles to the existing map as tile overlays in mobile apps. </li></ul>
</td>
</tr>
</tbody>
</table>

## Function Restrictions<a name="section1425318477373"></a>

<a name="table13395173564216"></a>
<table><thead align="left"><tr id="row839618353424"><th class="cellrowborder" valign="top" width="30%" id="mcps1.1.4.1.1"><p id="p1439623512424"><a name="p1439623512424"></a><a name="p1439623512424"></a>Function</p>
</th>
<th class="cellrowborder" valign="top" width="30%" id="mcps1.1.4.1.2"><p id="p152545386535"><a name="p152545386535"></a><a name="p152545386535"></a>Location Restriction</p>
</th>
<th class="cellrowborder" valign="top" width="40%" id="mcps1.1.4.1.3"><p id="p1739610359423"><a name="p1739610359423"></a><a name="p1739610359423"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row1939723514219"><td class="cellrowborder" valign="top" width="30%" headers="mcps1.1.4.1.1 "><p id="p1059713475444"><a name="p1059713475444"></a><a name="p1059713475444"></a>Functions relevant to map data, such as map data loading</p>
</td>
<td class="cellrowborder" valign="top" width="30%" headers="mcps1.1.4.1.2 "><p id="p92541438185311"><a name="p92541438185311"></a><a name="p92541438185311"></a>Not supported in the Chinese mainland</p>
</td>
<td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.4.1.3 "><p id="p0397123584215"><a name="p0397123584215"></a><a name="p0397123584215"></a>No data of the Chinese mainland is available for these functions, such as map data loading and route planning.</p>
</td>
</tr>
<tr id="row439713350421"><td class="cellrowborder" valign="top" width="30%" headers="mcps1.1.4.1.1 "><p id="p115983477444"><a name="p115983477444"></a><a name="p115983477444"></a>Functions irrelevant to map data</p>
</td>
<td class="cellrowborder" valign="top" width="30%" headers="mcps1.1.4.1.2 "><p id="p1125463845319"><a name="p1125463845319"></a><a name="p1125463845319"></a>None</p>
</td>
<td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.4.1.3 "><p id="p93981435174218"><a name="p93981435174218"></a><a name="p93981435174218"></a>All functions irrelevant to map data are available, such as the functions of adding markers and polygons.</p>
</td>
</tr>
</tbody>
</table>

