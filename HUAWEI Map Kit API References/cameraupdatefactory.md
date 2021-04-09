# CameraUpdateFactory<a name="EN-US_TOPIC_0000001145941073"></a>

-   [Public Method Summary](#section15598131011411)
-   [Public Methods](#section9773184011213)
-   [newCameraPosition](#section148091116191319)
-   [newLatLng](#section1385216498553)
-   [newLatLngBounds\(LatLngBounds bounds, int width, int height, int padding\)](#section1027264718117)
-   [newLatLngBounds\(LatLngBounds bounds, int padding\)](#section1897811111973)
-   [newLatLngZoom](#section1624513513199)
-   [scrollBy](#section109571558151910)
-   [zoomBy\(float amount\)](#section191645461201)
-   [zoomBy\(float amount, Point focus\)](#section2088862622117)
-   [zoomIn](#section127351130142220)
-   [zoomOut](#section18752216152316)
-   [zoomTo](#section195657584238)


<a name="table120mcpsimp"></a>
<table><thead align="left"><tr id="row124mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p25980mcpsimp"><a name="p25980mcpsimp"></a><a name="p25980mcpsimp"></a>Class Info</p>
</th>
</tr>
</thead>
<tbody><tr id="row127mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p132941322916"><a name="p132941322916"></a><a name="p132941322916"></a>public final class CameraUpdateFactory</p>
<p id="p144699159505"><a name="p144699159505"></a><a name="p144699159505"></a>Provides various methods for creating <a href="cameraupdate.md">CameraUpdate</a> objects that modify the camera of a map.</p>
</td>
</tr>
</tbody>
</table>

## Public Method Summary<a name="section15598131011411"></a>

<a name="table135mcpsimp"></a>
<table><thead align="left"><tr id="row140mcpsimp"><th class="cellrowborder" valign="top" width="40%" id="mcps1.1.3.1.1"><p id="p142mcpsimp"><a name="p142mcpsimp"></a><a name="p142mcpsimp"></a>Qualifier and Type</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.1.3.1.2"><p id="p144mcpsimp"><a name="p144mcpsimp"></a><a name="p144mcpsimp"></a>Method Name and Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row145mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p147mcpsimp"><a name="p147mcpsimp"></a><a name="p147mcpsimp"></a>static <a href="cameraupdate.md">CameraUpdate</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p149mcpsimp"><a name="p149mcpsimp"></a><a name="p149mcpsimp"></a><a href="#section148091116191319">newCameraPosition</a>(<a href="cameraposition.md">CameraPosition</a> cameraPosition)</p>
<p id="p1437910519516"><a name="p1437910519516"></a><a name="p1437910519516"></a>Sets a new position for the camera of a map.</p>
</td>
</tr>
<tr id="row150mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p152mcpsimp"><a name="p152mcpsimp"></a><a name="p152mcpsimp"></a>static <a href="cameraupdate.md">CameraUpdate</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p154mcpsimp"><a name="p154mcpsimp"></a><a name="p154mcpsimp"></a><a href="#section1385216498553">newLatLng</a>(<a href="latlng.md">LatLng</a> latLng)</p>
<p id="p118524725113"><a name="p118524725113"></a><a name="p118524725113"></a>Moves the camera to a desired longitude and latitude.</p>
</td>
</tr>
<tr id="row155mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p157mcpsimp"><a name="p157mcpsimp"></a><a name="p157mcpsimp"></a>static <a href="cameraupdate.md">CameraUpdate</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p159mcpsimp"><a name="p159mcpsimp"></a><a name="p159mcpsimp"></a><a href="#section1027264718117">newLatLngBounds</a>(<a href="latlngbounds.md">LatLngBounds</a> bounds, int width, int height, int padding)</p>
<p id="p7357276521"><a name="p7357276521"></a><a name="p7357276521"></a>Centers a region on the screen by setting the width and height of the region, longitude and latitude bounds, and the padding between the region edges and the longitude/latitude bounding box edges.</p>
</td>
</tr>
<tr id="row160mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p162mcpsimp"><a name="p162mcpsimp"></a><a name="p162mcpsimp"></a>static <a href="cameraupdate.md">CameraUpdate</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p164mcpsimp"><a name="p164mcpsimp"></a><a name="p164mcpsimp"></a><a href="#section1897811111973">newLatLngBounds</a>(<a href="latlngbounds.md">LatLngBounds</a> bounds, int padding)</p>
<p id="p15439163118527"><a name="p15439163118527"></a><a name="p15439163118527"></a>Centers a region on the screen by setting the longitude and latitude bounds and the padding between the region edges and the longitude/latitude bounding box edges.</p>
</td>
</tr>
<tr id="row165mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p167mcpsimp"><a name="p167mcpsimp"></a><a name="p167mcpsimp"></a>static <a href="cameraupdate.md">CameraUpdate</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p169mcpsimp"><a name="p169mcpsimp"></a><a name="p169mcpsimp"></a><a href="#section1624513513199">newLatLngZoom</a>(<a href="latlng.md">LatLng</a> latLng, float zoom)</p>
<p id="p5234647105416"><a name="p5234647105416"></a><a name="p5234647105416"></a>Sets the longitude and latitude of the center as well as the zoom level of a map's view.</p>
</td>
</tr>
<tr id="row170mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p172mcpsimp"><a name="p172mcpsimp"></a><a name="p172mcpsimp"></a>static <a href="cameraupdate.md">CameraUpdate</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p174mcpsimp"><a name="p174mcpsimp"></a><a name="p174mcpsimp"></a><a href="#section109571558151910">scrollBy</a>(float xPixel, float yPixel)</p>
<p id="p1763463055513"><a name="p1763463055513"></a><a name="p1763463055513"></a>Moves the center of a map's view by pixel on the screen.</p>
</td>
</tr>
<tr id="row175mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p177mcpsimp"><a name="p177mcpsimp"></a><a name="p177mcpsimp"></a>static <a href="cameraupdate.md">CameraUpdate</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p179mcpsimp"><a name="p179mcpsimp"></a><a name="p179mcpsimp"></a><a href="#section191645461201">zoomBy</a>(float amount)</p>
<p id="p7773113413558"><a name="p7773113413558"></a><a name="p7773113413558"></a>Changes the zoom level of the camera by a specified incremental value.</p>
</td>
</tr>
<tr id="row180mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p182mcpsimp"><a name="p182mcpsimp"></a><a name="p182mcpsimp"></a>static <a href="cameraupdate.md">CameraUpdate</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p184mcpsimp"><a name="p184mcpsimp"></a><a name="p184mcpsimp"></a><a href="#section2088862622117">zoomBy</a>(float amount, Point focus)</p>
<p id="p66641835115511"><a name="p66641835115511"></a><a name="p66641835115511"></a>Incrementally moves the map camera based on the map center's coordinates on the screen and the zoom level.</p>
</td>
</tr>
<tr id="row185mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p187mcpsimp"><a name="p187mcpsimp"></a><a name="p187mcpsimp"></a>static <a href="cameraupdate.md">CameraUpdate</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p189mcpsimp"><a name="p189mcpsimp"></a><a name="p189mcpsimp"></a><a href="#section127351130142220">zoomIn</a>()</p>
<p id="p5821153615518"><a name="p5821153615518"></a><a name="p5821153615518"></a>Increases the zoom level of the camera by 1.</p>
</td>
</tr>
<tr id="row190mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p192mcpsimp"><a name="p192mcpsimp"></a><a name="p192mcpsimp"></a>static <a href="cameraupdate.md">CameraUpdate</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p194mcpsimp"><a name="p194mcpsimp"></a><a name="p194mcpsimp"></a><a href="#section18752216152316">zoomOut</a>()</p>
<p id="p570515377552"><a name="p570515377552"></a><a name="p570515377552"></a>Decreases the zoom level of the camera by 1.</p>
</td>
</tr>
<tr id="row195mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p197mcpsimp"><a name="p197mcpsimp"></a><a name="p197mcpsimp"></a>static <a href="cameraupdate.md">CameraUpdate</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p199mcpsimp"><a name="p199mcpsimp"></a><a name="p199mcpsimp"></a><a href="#section195657584238">zoomTo</a>(float zoom)</p>
<p id="p146891838145514"><a name="p146891838145514"></a><a name="p146891838145514"></a>Sets the zoom level of the camera to a specified value.</p>
</td>
</tr>
</tbody>
</table>

## Public Methods<a name="section9773184011213"></a>

## newCameraPosition<a name="section148091116191319"></a>

<a name="table202mcpsimp"></a>
<table><thead align="left"><tr id="row206mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p208mcpsimp"><a name="p208mcpsimp"></a><a name="p208mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row209mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p211mcpsimp"><a name="p211mcpsimp"></a><a name="p211mcpsimp"></a>public static <a href="cameraupdate.md">CameraUpdate</a> newCameraPosition(<a href="cameraposition.md">CameraPosition</a> cameraPosition)</p>
<p id="p12974181661612"><a name="p12974181661612"></a><a name="p12974181661612"></a>Sets a new position for the camera of a map. Actually, this will cause a change based on the longitude, latitude, zoom level, bearing, and tilt of a <a href="cameraposition.md">CameraPosition</a> object.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table217mcpsimp"></a>
<table><thead align="left"><tr id="row222mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p224mcpsimp"><a name="p224mcpsimp"></a><a name="p224mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p226mcpsimp"><a name="p226mcpsimp"></a><a name="p226mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row227mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p229mcpsimp"><a name="p229mcpsimp"></a><a name="p229mcpsimp"></a>cameraPosition</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p231mcpsimp"><a name="p231mcpsimp"></a><a name="p231mcpsimp"></a>Camera position information.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table234mcpsimp"></a>
<table><thead align="left"><tr id="row239mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p241mcpsimp"><a name="p241mcpsimp"></a><a name="p241mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p243mcpsimp"><a name="p243mcpsimp"></a><a name="p243mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row244mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p246mcpsimp"><a name="p246mcpsimp"></a><a name="p246mcpsimp"></a>CameraUpdate</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p248mcpsimp"><a name="p248mcpsimp"></a><a name="p248mcpsimp"></a><a href="cameraupdate.md">CameraUpdate</a> object, which is used to update the camera position.</p>
</td>
</tr>
</tbody>
</table>

## newLatLng<a name="section1385216498553"></a>

<a name="table250mcpsimp"></a>
<table><thead align="left"><tr id="row254mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p256mcpsimp"><a name="p256mcpsimp"></a><a name="p256mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row257mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p259mcpsimp"><a name="p259mcpsimp"></a><a name="p259mcpsimp"></a>public static <a href="cameraupdate.md">CameraUpdate</a> newLatLng(<a href="latlng.md">LatLng</a> latLng)</p>
<p id="p262mcpsimp"><a name="p262mcpsimp"></a><a name="p262mcpsimp"></a>Moves the camera to a desired longitude and latitude.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table265mcpsimp"></a>
<table><thead align="left"><tr id="row270mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p272mcpsimp"><a name="p272mcpsimp"></a><a name="p272mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p274mcpsimp"><a name="p274mcpsimp"></a><a name="p274mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row275mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p277mcpsimp"><a name="p277mcpsimp"></a><a name="p277mcpsimp"></a>latLng</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p279mcpsimp"><a name="p279mcpsimp"></a><a name="p279mcpsimp"></a>Desired longitude and latitude.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table282mcpsimp"></a>
<table><thead align="left"><tr id="row287mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p289mcpsimp"><a name="p289mcpsimp"></a><a name="p289mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p291mcpsimp"><a name="p291mcpsimp"></a><a name="p291mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row292mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p294mcpsimp"><a name="p294mcpsimp"></a><a name="p294mcpsimp"></a>CameraUpdate</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p296mcpsimp"><a name="p296mcpsimp"></a><a name="p296mcpsimp"></a><a href="cameraupdate.md">CameraUpdate</a> object, which is used to update the camera position.</p>
</td>
</tr>
</tbody>
</table>

## newLatLngBounds\(LatLngBounds bounds, int width, int height, int padding\)<a name="section1027264718117"></a>

<a name="table298mcpsimp"></a>
<table><thead align="left"><tr id="row302mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p304mcpsimp"><a name="p304mcpsimp"></a><a name="p304mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row305mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p307mcpsimp"><a name="p307mcpsimp"></a><a name="p307mcpsimp"></a>public static <a href="cameraupdate.md">CameraUpdate</a> newLatLngBounds(<a href="latlngbounds.md">LatLngBounds</a> bounds, int width, int height, int padding)</p>
<p id="p148305243616"><a name="p148305243616"></a><a name="p148305243616"></a>Centers a region on the screen by setting the width and height of the region, longitude and latitude bounds, and the padding between the region edges and the longitude/latitude bounding box edges.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table313mcpsimp"></a>
<table><thead align="left"><tr id="row318mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p320mcpsimp"><a name="p320mcpsimp"></a><a name="p320mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p322mcpsimp"><a name="p322mcpsimp"></a><a name="p322mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row323mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p325mcpsimp"><a name="p325mcpsimp"></a><a name="p325mcpsimp"></a>bounds</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p327mcpsimp"><a name="p327mcpsimp"></a><a name="p327mcpsimp"></a>Longitude and latitude bounds to be displayed.</p>
</td>
</tr>
<tr id="row328mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p330mcpsimp"><a name="p330mcpsimp"></a><a name="p330mcpsimp"></a>width</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p332mcpsimp"><a name="p332mcpsimp"></a><a name="p332mcpsimp"></a>Bounding box width, in pixels.</p>
</td>
</tr>
<tr id="row333mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p335mcpsimp"><a name="p335mcpsimp"></a><a name="p335mcpsimp"></a>height</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p337mcpsimp"><a name="p337mcpsimp"></a><a name="p337mcpsimp"></a>Bounding box height, in pixels.</p>
</td>
</tr>
<tr id="row338mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p340mcpsimp"><a name="p340mcpsimp"></a><a name="p340mcpsimp"></a>padding</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p342mcpsimp"><a name="p342mcpsimp"></a><a name="p342mcpsimp"></a>Space between the region edges and bounding box edges, in pixels.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table345mcpsimp"></a>
<table><thead align="left"><tr id="row350mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p352mcpsimp"><a name="p352mcpsimp"></a><a name="p352mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p354mcpsimp"><a name="p354mcpsimp"></a><a name="p354mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row355mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p357mcpsimp"><a name="p357mcpsimp"></a><a name="p357mcpsimp"></a>CameraUpdate</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p359mcpsimp"><a name="p359mcpsimp"></a><a name="p359mcpsimp"></a><a href="cameraupdate.md">CameraUpdate</a> object, which is used to update the camera position.</p>
</td>
</tr>
</tbody>
</table>

## newLatLngBounds\(LatLngBounds bounds, int padding\)<a name="section1897811111973"></a>

<a name="table361mcpsimp"></a>
<table><thead align="left"><tr id="row365mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p367mcpsimp"><a name="p367mcpsimp"></a><a name="p367mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row368mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p370mcpsimp"><a name="p370mcpsimp"></a><a name="p370mcpsimp"></a>public static <a href="cameraupdate.md">CameraUpdate</a> newLatLngBounds(<a href="latlngbounds.md">LatLngBounds</a> bounds, int padding)</p>
<p id="p1455818123814"><a name="p1455818123814"></a><a name="p1455818123814"></a>Centers a region on the screen by setting the longitude and latitude bounds and the padding between the region edges and the longitude/latitude bounding box edges.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table376mcpsimp"></a>
<table><thead align="left"><tr id="row381mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p383mcpsimp"><a name="p383mcpsimp"></a><a name="p383mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p385mcpsimp"><a name="p385mcpsimp"></a><a name="p385mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row386mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p388mcpsimp"><a name="p388mcpsimp"></a><a name="p388mcpsimp"></a>bounds</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p390mcpsimp"><a name="p390mcpsimp"></a><a name="p390mcpsimp"></a>Longitude and latitude bounds to be displayed.</p>
</td>
</tr>
<tr id="row391mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p393mcpsimp"><a name="p393mcpsimp"></a><a name="p393mcpsimp"></a>padding</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p395mcpsimp"><a name="p395mcpsimp"></a><a name="p395mcpsimp"></a>Space between the region edges and bounding box edges, in pixels.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table398mcpsimp"></a>
<table><thead align="left"><tr id="row403mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p405mcpsimp"><a name="p405mcpsimp"></a><a name="p405mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p407mcpsimp"><a name="p407mcpsimp"></a><a name="p407mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row408mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p410mcpsimp"><a name="p410mcpsimp"></a><a name="p410mcpsimp"></a>CameraUpdate</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p412mcpsimp"><a name="p412mcpsimp"></a><a name="p412mcpsimp"></a><a href="cameraupdate.md">CameraUpdate</a> object, which is used to update the camera position.</p>
</td>
</tr>
</tbody>
</table>

## newLatLngZoom<a name="section1624513513199"></a>

<a name="table414mcpsimp"></a>
<table><thead align="left"><tr id="row418mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p420mcpsimp"><a name="p420mcpsimp"></a><a name="p420mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row421mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p423mcpsimp"><a name="p423mcpsimp"></a><a name="p423mcpsimp"></a>public static <a href="cameraupdate.md">CameraUpdate</a> newLatLngZoom(<a href="latlng.md">LatLng</a> latLng, float zoom)</p>
<p id="p16670530378"><a name="p16670530378"></a><a name="p16670530378"></a>Sets the longitude and latitude of the center as well as the zoom level of a map's view.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table429mcpsimp"></a>
<table><thead align="left"><tr id="row434mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p436mcpsimp"><a name="p436mcpsimp"></a><a name="p436mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p438mcpsimp"><a name="p438mcpsimp"></a><a name="p438mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row439mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p441mcpsimp"><a name="p441mcpsimp"></a><a name="p441mcpsimp"></a>latLng</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p443mcpsimp"><a name="p443mcpsimp"></a><a name="p443mcpsimp"></a>Longitude and latitude of the center of a map's view.</p>
</td>
</tr>
<tr id="row444mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p446mcpsimp"><a name="p446mcpsimp"></a><a name="p446mcpsimp"></a>zoom</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p448mcpsimp"><a name="p448mcpsimp"></a><a name="p448mcpsimp"></a>Zoom level of the map camera. The value range is [3, 20].</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table451mcpsimp"></a>
<table><thead align="left"><tr id="row456mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p458mcpsimp"><a name="p458mcpsimp"></a><a name="p458mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p460mcpsimp"><a name="p460mcpsimp"></a><a name="p460mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row461mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p463mcpsimp"><a name="p463mcpsimp"></a><a name="p463mcpsimp"></a>CameraUpdate</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p465mcpsimp"><a name="p465mcpsimp"></a><a name="p465mcpsimp"></a><a href="cameraupdate.md">CameraUpdate</a> object, which is used to update the camera position.</p>
</td>
</tr>
</tbody>
</table>

## scrollBy<a name="section109571558151910"></a>

<a name="table467mcpsimp"></a>
<table><thead align="left"><tr id="row471mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p473mcpsimp"><a name="p473mcpsimp"></a><a name="p473mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row474mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p476mcpsimp"><a name="p476mcpsimp"></a><a name="p476mcpsimp"></a>public static <a href="cameraupdate.md">CameraUpdate</a> scrollBy(float xPixel, float yPixel)</p>
<p id="p93223131371"><a name="p93223131371"></a><a name="p93223131371"></a>Moves the center of a map's view by pixel on the screen.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table482mcpsimp"></a>
<table><thead align="left"><tr id="row487mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p489mcpsimp"><a name="p489mcpsimp"></a><a name="p489mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p491mcpsimp"><a name="p491mcpsimp"></a><a name="p491mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row492mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p494mcpsimp"><a name="p494mcpsimp"></a><a name="p494mcpsimp"></a>xPixel</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p496mcpsimp"><a name="p496mcpsimp"></a><a name="p496mcpsimp"></a>Number of pixels moved horizontally. A positive value indicates to move the center to the right, while a negative value indicates to move the center to the left.</p>
</td>
</tr>
<tr id="row497mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p499mcpsimp"><a name="p499mcpsimp"></a><a name="p499mcpsimp"></a>yPixel</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p501mcpsimp"><a name="p501mcpsimp"></a><a name="p501mcpsimp"></a>Number of pixels moved vertically. A positive value indicates to move the center up, while a negative value indicates to move the center down.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table504mcpsimp"></a>
<table><thead align="left"><tr id="row509mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p511mcpsimp"><a name="p511mcpsimp"></a><a name="p511mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p513mcpsimp"><a name="p513mcpsimp"></a><a name="p513mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row514mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p516mcpsimp"><a name="p516mcpsimp"></a><a name="p516mcpsimp"></a>CameraUpdate</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p518mcpsimp"><a name="p518mcpsimp"></a><a name="p518mcpsimp"></a><a href="cameraupdate.md">CameraUpdate</a> object, which is used to update the camera position.</p>
</td>
</tr>
</tbody>
</table>

## zoomBy\(float amount\)<a name="section191645461201"></a>

<a name="table520mcpsimp"></a>
<table><thead align="left"><tr id="row524mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p526mcpsimp"><a name="p526mcpsimp"></a><a name="p526mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row527mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p529mcpsimp"><a name="p529mcpsimp"></a><a name="p529mcpsimp"></a>public static <a href="cameraupdate.md">CameraUpdate</a> zoomBy(float amount)</p>
<p id="p1276872233717"><a name="p1276872233717"></a><a name="p1276872233717"></a>Changes the zoom level of the camera by a specified incremental value.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table535mcpsimp"></a>
<table><thead align="left"><tr id="row540mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p542mcpsimp"><a name="p542mcpsimp"></a><a name="p542mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p544mcpsimp"><a name="p544mcpsimp"></a><a name="p544mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row545mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p547mcpsimp"><a name="p547mcpsimp"></a><a name="p547mcpsimp"></a>amount</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p549mcpsimp"><a name="p549mcpsimp"></a><a name="p549mcpsimp"></a>Incremental value to change the zoom level of the camera. The distance to the earth surface is shortened if <strong id="b897922316179"><a name="b897922316179"></a><a name="b897922316179"></a>amount</strong> has a positive value and prolonged if <strong id="b398962341714"><a name="b398962341714"></a><a name="b398962341714"></a>amount</strong> has a negative value.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table552mcpsimp"></a>
<table><thead align="left"><tr id="row557mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p559mcpsimp"><a name="p559mcpsimp"></a><a name="p559mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p561mcpsimp"><a name="p561mcpsimp"></a><a name="p561mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row562mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p564mcpsimp"><a name="p564mcpsimp"></a><a name="p564mcpsimp"></a>CameraUpdate</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p566mcpsimp"><a name="p566mcpsimp"></a><a name="p566mcpsimp"></a><a href="cameraupdate.md">CameraUpdate</a> object, which is used to update the camera position.</p>
</td>
</tr>
</tbody>
</table>

## zoomBy\(float amount, Point focus\)<a name="section2088862622117"></a>

<a name="table568mcpsimp"></a>
<table><thead align="left"><tr id="row572mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p574mcpsimp"><a name="p574mcpsimp"></a><a name="p574mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row575mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p577mcpsimp"><a name="p577mcpsimp"></a><a name="p577mcpsimp"></a>public static <a href="cameraupdate.md">CameraUpdate</a> zoomBy(float amount, Point focus)</p>
<p id="p169251034183713"><a name="p169251034183713"></a><a name="p169251034183713"></a>Incrementally moves the map camera based on the map center's coordinates on the screen and the zoom level.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table583mcpsimp"></a>
<table><thead align="left"><tr id="row588mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p590mcpsimp"><a name="p590mcpsimp"></a><a name="p590mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p592mcpsimp"><a name="p592mcpsimp"></a><a name="p592mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row593mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p595mcpsimp"><a name="p595mcpsimp"></a><a name="p595mcpsimp"></a>amount</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p597mcpsimp"><a name="p597mcpsimp"></a><a name="p597mcpsimp"></a>Incremental value to change the zoom level. The distance to the earth surface is shortened if <strong id="b128577373176"><a name="b128577373176"></a><a name="b128577373176"></a>amount</strong> has a positive value and prolonged if <strong id="b7857193714171"><a name="b7857193714171"></a><a name="b7857193714171"></a>amount</strong> has a negative value.</p>
</td>
</tr>
<tr id="row598mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p600mcpsimp"><a name="p600mcpsimp"></a><a name="p600mcpsimp"></a>focus</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p602mcpsimp"><a name="p602mcpsimp"></a><a name="p602mcpsimp"></a>Map center's coordinates on the screen. In the method, <strong id="b1474316491815"><a name="b1474316491815"></a><a name="b1474316491815"></a>focus</strong> is the center point for zooming in or out.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table605mcpsimp"></a>
<table><thead align="left"><tr id="row610mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p612mcpsimp"><a name="p612mcpsimp"></a><a name="p612mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p614mcpsimp"><a name="p614mcpsimp"></a><a name="p614mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row615mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p314874111368"><a name="p314874111368"></a><a name="p314874111368"></a>CameraUpdate</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p619mcpsimp"><a name="p619mcpsimp"></a><a name="p619mcpsimp"></a><a href="cameraupdate.md">CameraUpdate</a> object, which is used to update the camera position.</p>
</td>
</tr>
</tbody>
</table>

## zoomIn<a name="section127351130142220"></a>

<a name="table621mcpsimp"></a>
<table><thead align="left"><tr id="row625mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p627mcpsimp"><a name="p627mcpsimp"></a><a name="p627mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row628mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p630mcpsimp"><a name="p630mcpsimp"></a><a name="p630mcpsimp"></a>public static <a href="cameraupdate.md">CameraUpdate</a> zoomIn()</p>
<p id="p172510448372"><a name="p172510448372"></a><a name="p172510448372"></a>Increases the zoom level of the camera by 1.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table639mcpsimp"></a>
<table><thead align="left"><tr id="row644mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p646mcpsimp"><a name="p646mcpsimp"></a><a name="p646mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p648mcpsimp"><a name="p648mcpsimp"></a><a name="p648mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row649mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p149716433368"><a name="p149716433368"></a><a name="p149716433368"></a>CameraUpdate</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p653mcpsimp"><a name="p653mcpsimp"></a><a name="p653mcpsimp"></a><a href="cameraupdate.md">CameraUpdate</a> object, which is used to update the camera position.</p>
</td>
</tr>
</tbody>
</table>

## zoomOut<a name="section18752216152316"></a>

<a name="table655mcpsimp"></a>
<table><thead align="left"><tr id="row659mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p661mcpsimp"><a name="p661mcpsimp"></a><a name="p661mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row662mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p664mcpsimp"><a name="p664mcpsimp"></a><a name="p664mcpsimp"></a>public static <a href="cameraupdate.md">CameraUpdate</a> zoomOut()</p>
<p id="p154671352133715"><a name="p154671352133715"></a><a name="p154671352133715"></a>Decreases the zoom level of the camera by 1.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table673mcpsimp"></a>
<table><thead align="left"><tr id="row678mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p680mcpsimp"><a name="p680mcpsimp"></a><a name="p680mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p682mcpsimp"><a name="p682mcpsimp"></a><a name="p682mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row683mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p10978194533617"><a name="p10978194533617"></a><a name="p10978194533617"></a>CameraUpdate</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p687mcpsimp"><a name="p687mcpsimp"></a><a name="p687mcpsimp"></a><a href="cameraupdate.md">CameraUpdate</a> object, which is used to update the camera position.</p>
</td>
</tr>
</tbody>
</table>

## zoomTo<a name="section195657584238"></a>

<a name="table689mcpsimp"></a>
<table><thead align="left"><tr id="row693mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p695mcpsimp"><a name="p695mcpsimp"></a><a name="p695mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row696mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p698mcpsimp"><a name="p698mcpsimp"></a><a name="p698mcpsimp"></a>public static <a href="cameraupdate.md">CameraUpdate</a> zoomTo(float zoom)</p>
<p id="p701mcpsimp"><a name="p701mcpsimp"></a><a name="p701mcpsimp"></a>Sets the zoom level of the camera to a specified value.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table704mcpsimp"></a>
<table><thead align="left"><tr id="row709mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p711mcpsimp"><a name="p711mcpsimp"></a><a name="p711mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p713mcpsimp"><a name="p713mcpsimp"></a><a name="p713mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row714mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p716mcpsimp"><a name="p716mcpsimp"></a><a name="p716mcpsimp"></a>zoom</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p718mcpsimp"><a name="p718mcpsimp"></a><a name="p718mcpsimp"></a>Zoom level of the map camera. The value range is [3, 20].</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table721mcpsimp"></a>
<table><thead align="left"><tr id="row726mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p728mcpsimp"><a name="p728mcpsimp"></a><a name="p728mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p730mcpsimp"><a name="p730mcpsimp"></a><a name="p730mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row731mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p28651447173610"><a name="p28651447173610"></a><a name="p28651447173610"></a>CameraUpdate</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p735mcpsimp"><a name="p735mcpsimp"></a><a name="p735mcpsimp"></a><a href="cameraupdate.md">CameraUpdate</a> object, which is used to update the camera position.</p>
</td>
</tr>
</tbody>
</table>

