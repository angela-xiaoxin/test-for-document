# PolylineOptions<a name="EN-US_TOPIC_0000001145860943"></a>

-   [Public Constructor Summary](#section965544116189)
-   [Public Method Summary](#section1051111881915)
-   [Public Methods](#section141301440151013)
-   [add\(LatLng... points\)](#section2746155511011)
-   [add\(LatLng point\)](#section16827203311118)
-   [addAll](#section06718233127)
-   [clickable](#section4718269130)
-   [color](#section2144201310144)
-   [endCap](#section114046504142)
-   [geodesic](#section2811192141518)
-   [getColor](#section101181153181517)
-   [getEndCap](#section4466324111619)
-   [getJointType](#section13384105915161)
-   [getPattern](#section5504927141716)
-   [getPoints](#section352743417182)
-   [getStartCap](#section1553061115191)
-   [getWidth](#section16511554181916)
-   [getZIndex](#section342518338214)
-   [isClickable](#section167712742311)
-   [isGeodesic](#section71902235251)
-   [isVisible](#section15985923102612)
-   [jointType](#section54645418262)
-   [pattern](#section17745728122713)
-   [startCap](#section14983632112810)
-   [visible](#section5185611122910)
-   [width](#section4343845172911)
-   [zIndex](#section1536018521142)


<a name="table20725mcpsimp"></a>
<table><thead align="left"><tr id="row20729mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p20731mcpsimp"><a name="p20731mcpsimp"></a><a name="p20731mcpsimp"></a>Class Info</p>
</th>
</tr>
</thead>
<tbody><tr id="row20732mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p1572182264312"><a name="p1572182264312"></a><a name="p1572182264312"></a>public class PolylineOptions</p>
<p id="p20734mcpsimp"><a name="p20734mcpsimp"></a><a name="p20734mcpsimp"></a>Implements the <strong id="b1260336153019"><a name="b1260336153019"></a><a name="b1260336153019"></a>Parcelable</strong> API and defines attributes for a polyline.</p>
</td>
</tr>
</tbody>
</table>

## Public Constructor Summary<a name="section965544116189"></a>

<a name="table20738mcpsimp"></a>
<table><thead align="left"><tr id="row20742mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p145mcpsimp"><a name="p145mcpsimp"></a><a name="p145mcpsimp"></a>Constructor Name</p>
</th>
</tr>
</thead>
<tbody><tr id="row20745mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p20747mcpsimp"><a name="p20747mcpsimp"></a><a name="p20747mcpsimp"></a><a href="polylineoptions.md">PolylineOptions</a>()</p>
<p id="p986414389358"><a name="p986414389358"></a><a name="p986414389358"></a>Default constructor of the <strong id="b15291596815"><a name="b15291596815"></a><a name="b15291596815"></a>PolylineOptions</strong> class.</p>
</td>
</tr>
</tbody>
</table>

## Public Method Summary<a name="section1051111881915"></a>

<a name="table20749mcpsimp"></a>
<table><thead align="left"><tr id="row20754mcpsimp"><th class="cellrowborder" valign="top" width="40%" id="mcps1.1.3.1.1"><p id="p081120285386"><a name="p081120285386"></a><a name="p081120285386"></a>Qualifier and Type</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.1.3.1.2"><p id="p681112883813"><a name="p681112883813"></a><a name="p681112883813"></a>Method Name and Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row20774mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p20776mcpsimp"><a name="p20776mcpsimp"></a><a name="p20776mcpsimp"></a><a href="polylineoptions.md">PolylineOptions</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p20778mcpsimp"><a name="p20778mcpsimp"></a><a name="p20778mcpsimp"></a><a href="#section2746155511011">add</a>(<a href="latlng.md">LatLng</a>... points)</p>
<p id="p1335313115173"><a name="p1335313115173"></a><a name="p1335313115173"></a>Adds multiple vertices to a polyline.</p>
</td>
</tr>
<tr id="row20779mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p20781mcpsimp"><a name="p20781mcpsimp"></a><a name="p20781mcpsimp"></a><a href="polylineoptions.md">PolylineOptions</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p20783mcpsimp"><a name="p20783mcpsimp"></a><a name="p20783mcpsimp"></a><a href="#section16827203311118">add</a>(<a href="latlng.md">LatLng</a> point)</p>
<p id="p7189102201714"><a name="p7189102201714"></a><a name="p7189102201714"></a>Adds a vertex to a polyline.</p>
</td>
</tr>
<tr id="row20784mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p20786mcpsimp"><a name="p20786mcpsimp"></a><a name="p20786mcpsimp"></a><a href="polylineoptions.md">PolylineOptions</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p20788mcpsimp"><a name="p20788mcpsimp"></a><a name="p20788mcpsimp"></a><a href="#section06718233127">addAll</a>(Iterable&lt;<a href="latlng.md">LatLng</a>&gt; points)</p>
<p id="p898622181717"><a name="p898622181717"></a><a name="p898622181717"></a>Adds a group of vertices to a polyline.</p>
</td>
</tr>
<tr id="row20789mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p20791mcpsimp"><a name="p20791mcpsimp"></a><a name="p20791mcpsimp"></a><a href="polylineoptions.md">PolylineOptions</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p20793mcpsimp"><a name="p20793mcpsimp"></a><a name="p20793mcpsimp"></a><a href="#section4718269130">clickable</a>(boolean clickable)</p>
<p id="p75821647175"><a name="p75821647175"></a><a name="p75821647175"></a>Sets whether a polyline is tappable.</p>
</td>
</tr>
<tr id="row20794mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p20796mcpsimp"><a name="p20796mcpsimp"></a><a name="p20796mcpsimp"></a><a href="polylineoptions.md">PolylineOptions</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p20798mcpsimp"><a name="p20798mcpsimp"></a><a name="p20798mcpsimp"></a><a href="#section2144201310144">color</a>(int color)</p>
<p id="p9543165151714"><a name="p9543165151714"></a><a name="p9543165151714"></a>Sets the stroke color of a polyline.</p>
</td>
</tr>
<tr id="row20799mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p20801mcpsimp"><a name="p20801mcpsimp"></a><a name="p20801mcpsimp"></a><a href="polylineoptions.md">PolylineOptions</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p20803mcpsimp"><a name="p20803mcpsimp"></a><a name="p20803mcpsimp"></a><a href="#section114046504142">endCap</a>(<a href="cap.md">Cap</a> endCap)</p>
<p id="p12315161221712"><a name="p12315161221712"></a><a name="p12315161221712"></a>Sets the end vertex cap of a polyline.</p>
</td>
</tr>
<tr id="row20804mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p20806mcpsimp"><a name="p20806mcpsimp"></a><a name="p20806mcpsimp"></a><a href="polylineoptions.md">PolylineOptions</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p20808mcpsimp"><a name="p20808mcpsimp"></a><a name="p20808mcpsimp"></a><a href="#section2811192141518">geodesic</a>(boolean geodesic)</p>
<p id="p15420141173"><a name="p15420141173"></a><a name="p15420141173"></a>Sets whether to draw each segment of a polyline as a geodesic.</p>
</td>
</tr>
<tr id="row20809mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p20811mcpsimp"><a name="p20811mcpsimp"></a><a name="p20811mcpsimp"></a>int</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p20813mcpsimp"><a name="p20813mcpsimp"></a><a name="p20813mcpsimp"></a><a href="#section101181153181517">getColor</a>()</p>
<p id="p285411150174"><a name="p285411150174"></a><a name="p285411150174"></a>Obtains the stroke color of a polyline.</p>
</td>
</tr>
<tr id="row20814mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p20816mcpsimp"><a name="p20816mcpsimp"></a><a name="p20816mcpsimp"></a><a href="cap.md">Cap</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p20818mcpsimp"><a name="p20818mcpsimp"></a><a name="p20818mcpsimp"></a><a href="#section4466324111619">getEndCap</a>()</p>
<p id="p1673071612177"><a name="p1673071612177"></a><a name="p1673071612177"></a>Obtains the end vertex cap of a polyline.</p>
</td>
</tr>
<tr id="row20819mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p20821mcpsimp"><a name="p20821mcpsimp"></a><a name="p20821mcpsimp"></a>int</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p20823mcpsimp"><a name="p20823mcpsimp"></a><a name="p20823mcpsimp"></a><a href="#section13384105915161">getJointType</a>()</p>
<p id="p156901417181717"><a name="p156901417181717"></a><a name="p156901417181717"></a>Obtains the joint type of all vertices of a polyline, except the start and end vertices.</p>
</td>
</tr>
<tr id="row20824mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p20826mcpsimp"><a name="p20826mcpsimp"></a><a name="p20826mcpsimp"></a>List&lt;<a href="patternitem.md">PatternItem</a>&gt;</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p20828mcpsimp"><a name="p20828mcpsimp"></a><a name="p20828mcpsimp"></a><a href="#section5504927141716">getPattern</a>()</p>
<p id="p136911818111719"><a name="p136911818111719"></a><a name="p136911818111719"></a>Obtains the stroke pattern of a polyline.</p>
</td>
</tr>
<tr id="row20829mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p20831mcpsimp"><a name="p20831mcpsimp"></a><a name="p20831mcpsimp"></a>List&lt;<a href="latlng.md">LatLng</a>&gt;</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p20833mcpsimp"><a name="p20833mcpsimp"></a><a name="p20833mcpsimp"></a><a href="#section352743417182">getPoints</a>()</p>
<p id="p8955161971710"><a name="p8955161971710"></a><a name="p8955161971710"></a>Obtains all vertices of a polyline.</p>
</td>
</tr>
<tr id="row20834mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p20836mcpsimp"><a name="p20836mcpsimp"></a><a name="p20836mcpsimp"></a><a href="cap.md">Cap</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p20838mcpsimp"><a name="p20838mcpsimp"></a><a name="p20838mcpsimp"></a><a href="#section1553061115191">getStartCap</a>()</p>
<p id="p711192212175"><a name="p711192212175"></a><a name="p711192212175"></a>Obtains the start vertex cap of a polyline.</p>
</td>
</tr>
<tr id="row20839mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p20841mcpsimp"><a name="p20841mcpsimp"></a><a name="p20841mcpsimp"></a>float</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p20843mcpsimp"><a name="p20843mcpsimp"></a><a name="p20843mcpsimp"></a><a href="#section16511554181916">getWidth</a>()</p>
<p id="p28110229179"><a name="p28110229179"></a><a name="p28110229179"></a>Obtains the stroke width of a polyline.</p>
</td>
</tr>
<tr id="row20844mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p20846mcpsimp"><a name="p20846mcpsimp"></a><a name="p20846mcpsimp"></a>float</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p20848mcpsimp"><a name="p20848mcpsimp"></a><a name="p20848mcpsimp"></a><a href="#section342518338214">getZIndex</a>()</p>
<p id="p1760712239179"><a name="p1760712239179"></a><a name="p1760712239179"></a>Obtains the z-index of a polyline.</p>
</td>
</tr>
<tr id="row20849mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p20851mcpsimp"><a name="p20851mcpsimp"></a><a name="p20851mcpsimp"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p20853mcpsimp"><a name="p20853mcpsimp"></a><a name="p20853mcpsimp"></a><a href="#section167712742311">isClickable</a>()</p>
<p id="p1980172518174"><a name="p1980172518174"></a><a name="p1980172518174"></a>Checks whether a polyline is tappable.</p>
</td>
</tr>
<tr id="row20854mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p20856mcpsimp"><a name="p20856mcpsimp"></a><a name="p20856mcpsimp"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p20858mcpsimp"><a name="p20858mcpsimp"></a><a name="p20858mcpsimp"></a><a href="#section71902235251">isGeodesic</a>()</p>
<p id="p1710802715170"><a name="p1710802715170"></a><a name="p1710802715170"></a>Checks whether each segment of a polyline is drawn as a geodesic.</p>
</td>
</tr>
<tr id="row20859mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p20861mcpsimp"><a name="p20861mcpsimp"></a><a name="p20861mcpsimp"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p20863mcpsimp"><a name="p20863mcpsimp"></a><a name="p20863mcpsimp"></a><a href="#section15985923102612">isVisible</a>()</p>
<p id="p494919279174"><a name="p494919279174"></a><a name="p494919279174"></a>Checks whether a polyline is visible.</p>
</td>
</tr>
<tr id="row20864mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p20866mcpsimp"><a name="p20866mcpsimp"></a><a name="p20866mcpsimp"></a><a href="polylineoptions.md">PolylineOptions</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p20868mcpsimp"><a name="p20868mcpsimp"></a><a name="p20868mcpsimp"></a><a href="#section54645418262">jointType</a>(int jointType)</p>
<p id="p8797152817175"><a name="p8797152817175"></a><a name="p8797152817175"></a>Sets the joint type of all vertices of a polyline, except the start and end vertices. For details about the allowed joint types, please refer to <a href="jointtype.md">JointType</a>.</p>
</td>
</tr>
<tr id="row20869mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p20871mcpsimp"><a name="p20871mcpsimp"></a><a name="p20871mcpsimp"></a><a href="polylineoptions.md">PolylineOptions</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p20873mcpsimp"><a name="p20873mcpsimp"></a><a name="p20873mcpsimp"></a><a href="#section17745728122713">pattern</a>(List&lt;<a href="patternitem.md">PatternItem</a>&gt; pattern)</p>
<p id="p5976163114174"><a name="p5976163114174"></a><a name="p5976163114174"></a>Sets the stroke pattern of a polyline.</p>
</td>
</tr>
<tr id="row20874mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p20876mcpsimp"><a name="p20876mcpsimp"></a><a name="p20876mcpsimp"></a><a href="polylineoptions.md">PolylineOptions</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p20878mcpsimp"><a name="p20878mcpsimp"></a><a name="p20878mcpsimp"></a><a href="#section14983632112810">startCap</a>(<a href="cap.md">Cap</a> startCap)</p>
<p id="p10243133161718"><a name="p10243133161718"></a><a name="p10243133161718"></a>Sets the start vertex cap of a polyline.</p>
</td>
</tr>
<tr id="row20879mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p20881mcpsimp"><a name="p20881mcpsimp"></a><a name="p20881mcpsimp"></a><a href="polylineoptions.md">PolylineOptions</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p20883mcpsimp"><a name="p20883mcpsimp"></a><a name="p20883mcpsimp"></a><a href="#section5185611122910">visible</a>(boolean visible)</p>
<p id="p252163411178"><a name="p252163411178"></a><a name="p252163411178"></a>Sets whether a polyline is visible.</p>
</td>
</tr>
<tr id="row20884mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p20886mcpsimp"><a name="p20886mcpsimp"></a><a name="p20886mcpsimp"></a><a href="polylineoptions.md">PolylineOptions</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p20888mcpsimp"><a name="p20888mcpsimp"></a><a name="p20888mcpsimp"></a><a href="#section4343845172911">width</a>(float width)</p>
<p id="p15317133551714"><a name="p15317133551714"></a><a name="p15317133551714"></a>Sets the stroke width of a polyline.</p>
</td>
</tr>
<tr id="row20889mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p20891mcpsimp"><a name="p20891mcpsimp"></a><a name="p20891mcpsimp"></a><a href="polylineoptions.md">PolylineOptions</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p20893mcpsimp"><a name="p20893mcpsimp"></a><a name="p20893mcpsimp"></a><a href="#section1536018521142">zIndex</a>(float zIndex)</p>
<p id="p674733617175"><a name="p674733617175"></a><a name="p674733617175"></a>Sets the z-index of a polyline.</p>
</td>
</tr>
</tbody>
</table>

## Public Methods<a name="section141301440151013"></a>

## add\(LatLng... points\)<a name="section2746155511011"></a>

<a name="table20896mcpsimp"></a>
<table><thead align="left"><tr id="row20900mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p20902mcpsimp"><a name="p20902mcpsimp"></a><a name="p20902mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row20903mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p20905mcpsimp"><a name="p20905mcpsimp"></a><a name="p20905mcpsimp"></a>public <a href="polylineoptions.md">PolylineOptions</a> add(<a href="latlng.md">LatLng</a>... points)</p>
<p id="p1921219146117"><a name="p1921219146117"></a><a name="p1921219146117"></a>Adds multiple vertices to a polyline.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table20911mcpsimp"></a>
<table><thead align="left"><tr id="row20916mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p20918mcpsimp"><a name="p20918mcpsimp"></a><a name="p20918mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p20920mcpsimp"><a name="p20920mcpsimp"></a><a name="p20920mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row20921mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p20923mcpsimp"><a name="p20923mcpsimp"></a><a name="p20923mcpsimp"></a>points</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p20925mcpsimp"><a name="p20925mcpsimp"></a><a name="p20925mcpsimp"></a>Coordinates of multiple vertices.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table20928mcpsimp"></a>
<table><thead align="left"><tr id="row20933mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p20935mcpsimp"><a name="p20935mcpsimp"></a><a name="p20935mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p20937mcpsimp"><a name="p20937mcpsimp"></a><a name="p20937mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row20938mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p20940mcpsimp"><a name="p20940mcpsimp"></a><a name="p20940mcpsimp"></a>PolylineOptions</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p20942mcpsimp"><a name="p20942mcpsimp"></a><a name="p20942mcpsimp"></a><a href="polylineoptions.md">PolylineOptions</a> object containing the specified vertices.</p>
</td>
</tr>
</tbody>
</table>

## add\(LatLng point\)<a name="section16827203311118"></a>

<a name="table20944mcpsimp"></a>
<table><thead align="left"><tr id="row20948mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p20950mcpsimp"><a name="p20950mcpsimp"></a><a name="p20950mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row20951mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p20953mcpsimp"><a name="p20953mcpsimp"></a><a name="p20953mcpsimp"></a>public <a href="polylineoptions.md">PolylineOptions</a> add(<a href="latlng.md">LatLng</a> point)</p>
<p id="p246514213120"><a name="p246514213120"></a><a name="p246514213120"></a>Adds a vertex to a polyline.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table20959mcpsimp"></a>
<table><thead align="left"><tr id="row20964mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p20966mcpsimp"><a name="p20966mcpsimp"></a><a name="p20966mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p20968mcpsimp"><a name="p20968mcpsimp"></a><a name="p20968mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row20969mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p20971mcpsimp"><a name="p20971mcpsimp"></a><a name="p20971mcpsimp"></a>point</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p20973mcpsimp"><a name="p20973mcpsimp"></a><a name="p20973mcpsimp"></a>Coordinates of a vertex.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table20976mcpsimp"></a>
<table><thead align="left"><tr id="row20981mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p20983mcpsimp"><a name="p20983mcpsimp"></a><a name="p20983mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p20985mcpsimp"><a name="p20985mcpsimp"></a><a name="p20985mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row20986mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p20988mcpsimp"><a name="p20988mcpsimp"></a><a name="p20988mcpsimp"></a>PolylineOptions</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p20990mcpsimp"><a name="p20990mcpsimp"></a><a name="p20990mcpsimp"></a><a href="polylineoptions.md">PolylineOptions</a> object with the new vertex setting.</p>
</td>
</tr>
</tbody>
</table>

## addAll<a name="section06718233127"></a>

<a name="table20992mcpsimp"></a>
<table><thead align="left"><tr id="row20996mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p20998mcpsimp"><a name="p20998mcpsimp"></a><a name="p20998mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row20999mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p21001mcpsimp"><a name="p21001mcpsimp"></a><a name="p21001mcpsimp"></a>public <a href="polylineoptions.md">PolylineOptions</a> addAll(Iterable&lt;<a href="latlng.md">LatLng</a>&gt; points)</p>
<p id="p53111040131217"><a name="p53111040131217"></a><a name="p53111040131217"></a>Adds a group of vertices to a polyline.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table21007mcpsimp"></a>
<table><thead align="left"><tr id="row21012mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p21014mcpsimp"><a name="p21014mcpsimp"></a><a name="p21014mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p21016mcpsimp"><a name="p21016mcpsimp"></a><a name="p21016mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row21017mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p21019mcpsimp"><a name="p21019mcpsimp"></a><a name="p21019mcpsimp"></a>points</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p21021mcpsimp"><a name="p21021mcpsimp"></a><a name="p21021mcpsimp"></a>Multiple vertices.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table21024mcpsimp"></a>
<table><thead align="left"><tr id="row21029mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p21031mcpsimp"><a name="p21031mcpsimp"></a><a name="p21031mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p21033mcpsimp"><a name="p21033mcpsimp"></a><a name="p21033mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row21034mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p21036mcpsimp"><a name="p21036mcpsimp"></a><a name="p21036mcpsimp"></a>PolylineOptions</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p21038mcpsimp"><a name="p21038mcpsimp"></a><a name="p21038mcpsimp"></a><a href="polylineoptions.md">PolylineOptions</a> object containing the specified vertices.</p>
</td>
</tr>
</tbody>
</table>

## clickable<a name="section4718269130"></a>

<a name="table21040mcpsimp"></a>
<table><thead align="left"><tr id="row21044mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p21046mcpsimp"><a name="p21046mcpsimp"></a><a name="p21046mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row21047mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p21049mcpsimp"><a name="p21049mcpsimp"></a><a name="p21049mcpsimp"></a>public <a href="polylineoptions.md">PolylineOptions</a> clickable(boolean clickable)</p>
<p id="p21052mcpsimp"><a name="p21052mcpsimp"></a><a name="p21052mcpsimp"></a>Sets whether a polyline is tappable.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table21055mcpsimp"></a>
<table><thead align="left"><tr id="row21060mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p21062mcpsimp"><a name="p21062mcpsimp"></a><a name="p21062mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p21064mcpsimp"><a name="p21064mcpsimp"></a><a name="p21064mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row21065mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p21067mcpsimp"><a name="p21067mcpsimp"></a><a name="p21067mcpsimp"></a>clickable</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p21069mcpsimp"><a name="p21069mcpsimp"></a><a name="p21069mcpsimp"></a>Indicates whether a polyline is tappable. <strong id="b7920334123213"><a name="b7920334123213"></a><a name="b7920334123213"></a>true</strong>: yes; <strong id="b59251734203220"><a name="b59251734203220"></a><a name="b59251734203220"></a>false</strong> (default): no. </p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table21072mcpsimp"></a>
<table><thead align="left"><tr id="row21077mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p21079mcpsimp"><a name="p21079mcpsimp"></a><a name="p21079mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p21081mcpsimp"><a name="p21081mcpsimp"></a><a name="p21081mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row21082mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p21084mcpsimp"><a name="p21084mcpsimp"></a><a name="p21084mcpsimp"></a>PolylineOptions</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p21086mcpsimp"><a name="p21086mcpsimp"></a><a name="p21086mcpsimp"></a><a href="polylineoptions.md">PolylineOptions</a> object with the new tappability setting.</p>
</td>
</tr>
</tbody>
</table>

## color<a name="section2144201310144"></a>

<a name="table21088mcpsimp"></a>
<table><thead align="left"><tr id="row21092mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p21094mcpsimp"><a name="p21094mcpsimp"></a><a name="p21094mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row21095mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p21097mcpsimp"><a name="p21097mcpsimp"></a><a name="p21097mcpsimp"></a>public <a href="polylineoptions.md">PolylineOptions</a> color(int color)</p>
<p id="p21100mcpsimp"><a name="p21100mcpsimp"></a><a name="p21100mcpsimp"></a>Sets the stroke color of a polyline.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table21103mcpsimp"></a>
<table><thead align="left"><tr id="row21108mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p21110mcpsimp"><a name="p21110mcpsimp"></a><a name="p21110mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p21112mcpsimp"><a name="p21112mcpsimp"></a><a name="p21112mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row21113mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p21115mcpsimp"><a name="p21115mcpsimp"></a><a name="p21115mcpsimp"></a>color</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p21117mcpsimp"><a name="p21117mcpsimp"></a><a name="p21117mcpsimp"></a>Color in ARGB format. By default, the stroke color is black (0xff000000).</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table21120mcpsimp"></a>
<table><thead align="left"><tr id="row21125mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p21127mcpsimp"><a name="p21127mcpsimp"></a><a name="p21127mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p21129mcpsimp"><a name="p21129mcpsimp"></a><a name="p21129mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row21130mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p21132mcpsimp"><a name="p21132mcpsimp"></a><a name="p21132mcpsimp"></a>PolylineOptions</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p21134mcpsimp"><a name="p21134mcpsimp"></a><a name="p21134mcpsimp"></a><a href="polylineoptions.md">PolylineOptions</a> object with the new polyline stroke color.</p>
</td>
</tr>
</tbody>
</table>

## endCap<a name="section114046504142"></a>

<a name="table21136mcpsimp"></a>
<table><thead align="left"><tr id="row21140mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p21142mcpsimp"><a name="p21142mcpsimp"></a><a name="p21142mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row21143mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p21145mcpsimp"><a name="p21145mcpsimp"></a><a name="p21145mcpsimp"></a>public <a href="polylineoptions.md">PolylineOptions</a> endCap(<a href="cap.md">Cap</a> endCap)</p>
<p id="p21148mcpsimp"><a name="p21148mcpsimp"></a><a name="p21148mcpsimp"></a>Sets the end vertex cap of a polyline.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table21151mcpsimp"></a>
<table><thead align="left"><tr id="row21156mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p21158mcpsimp"><a name="p21158mcpsimp"></a><a name="p21158mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p21160mcpsimp"><a name="p21160mcpsimp"></a><a name="p21160mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row21161mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p21163mcpsimp"><a name="p21163mcpsimp"></a><a name="p21163mcpsimp"></a>endCap</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p21165mcpsimp"><a name="p21165mcpsimp"></a><a name="p21165mcpsimp"></a>End vertex cap of a polyline. The default value is <a href="buttcap.md">ButtCap</a>.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table21168mcpsimp"></a>
<table><thead align="left"><tr id="row21173mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p21175mcpsimp"><a name="p21175mcpsimp"></a><a name="p21175mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p21177mcpsimp"><a name="p21177mcpsimp"></a><a name="p21177mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row21178mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p21180mcpsimp"><a name="p21180mcpsimp"></a><a name="p21180mcpsimp"></a>PolylineOptions</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p21182mcpsimp"><a name="p21182mcpsimp"></a><a name="p21182mcpsimp"></a><a href="polylineoptions.md">PolylineOptions</a> object with the new end vertex cap setting.</p>
</td>
</tr>
</tbody>
</table>

## geodesic<a name="section2811192141518"></a>

<a name="table21184mcpsimp"></a>
<table><thead align="left"><tr id="row21188mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p21190mcpsimp"><a name="p21190mcpsimp"></a><a name="p21190mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row21191mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p21193mcpsimp"><a name="p21193mcpsimp"></a><a name="p21193mcpsimp"></a>public <a href="polylineoptions.md">PolylineOptions</a> geodesic(boolean geodesic)</p>
<p id="p21196mcpsimp"><a name="p21196mcpsimp"></a><a name="p21196mcpsimp"></a>Sets whether to draw each segment of a polyline as a geodesic. If the parameter is not set, the default value <strong id="b16461182345413"><a name="b16461182345413"></a><a name="b16461182345413"></a>false</strong> will be used.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table21199mcpsimp"></a>
<table><thead align="left"><tr id="row21204mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p21206mcpsimp"><a name="p21206mcpsimp"></a><a name="p21206mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p21208mcpsimp"><a name="p21208mcpsimp"></a><a name="p21208mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row21209mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p21211mcpsimp"><a name="p21211mcpsimp"></a><a name="p21211mcpsimp"></a>geodesic</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p21213mcpsimp"><a name="p21213mcpsimp"></a><a name="p21213mcpsimp"></a>Indicates whether to draw each segment of a polyline as a geodesic. <strong id="b948662716343"><a name="b948662716343"></a><a name="b948662716343"></a>true</strong>: yes; <strong id="b10492162703418"><a name="b10492162703418"></a><a name="b10492162703418"></a>false</strong>: no.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table21216mcpsimp"></a>
<table><thead align="left"><tr id="row21221mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p21223mcpsimp"><a name="p21223mcpsimp"></a><a name="p21223mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p21225mcpsimp"><a name="p21225mcpsimp"></a><a name="p21225mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row21226mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p21228mcpsimp"><a name="p21228mcpsimp"></a><a name="p21228mcpsimp"></a>PolylineOptions</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p21230mcpsimp"><a name="p21230mcpsimp"></a><a name="p21230mcpsimp"></a><a href="polylineoptions.md">PolylineOptions</a> object with the new <strong id="b749973319345"><a name="b749973319345"></a><a name="b749973319345"></a>geodesic</strong> attribute setting.</p>
</td>
</tr>
</tbody>
</table>

## getColor<a name="section101181153181517"></a>

<a name="table21232mcpsimp"></a>
<table><thead align="left"><tr id="row21236mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p21238mcpsimp"><a name="p21238mcpsimp"></a><a name="p21238mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row21239mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p21241mcpsimp"><a name="p21241mcpsimp"></a><a name="p21241mcpsimp"></a>public int getColor()</p>
<p id="p21244mcpsimp"><a name="p21244mcpsimp"></a><a name="p21244mcpsimp"></a>Obtains the stroke color of a polyline.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table21250mcpsimp"></a>
<table><thead align="left"><tr id="row21255mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p21257mcpsimp"><a name="p21257mcpsimp"></a><a name="p21257mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p21259mcpsimp"><a name="p21259mcpsimp"></a><a name="p21259mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row21260mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p21262mcpsimp"><a name="p21262mcpsimp"></a><a name="p21262mcpsimp"></a>int</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p21264mcpsimp"><a name="p21264mcpsimp"></a><a name="p21264mcpsimp"></a>Color in ARGB format. By default, the stroke color is black (0xff000000).</p>
</td>
</tr>
</tbody>
</table>

## getEndCap<a name="section4466324111619"></a>

<a name="table21266mcpsimp"></a>
<table><thead align="left"><tr id="row21270mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p21272mcpsimp"><a name="p21272mcpsimp"></a><a name="p21272mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row21273mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p21275mcpsimp"><a name="p21275mcpsimp"></a><a name="p21275mcpsimp"></a>public <a href="cap.md">Cap</a> getEndCap()</p>
<p id="p21278mcpsimp"><a name="p21278mcpsimp"></a><a name="p21278mcpsimp"></a>Obtains the end vertex cap of a polyline.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table21284mcpsimp"></a>
<table><thead align="left"><tr id="row21289mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p21291mcpsimp"><a name="p21291mcpsimp"></a><a name="p21291mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p21293mcpsimp"><a name="p21293mcpsimp"></a><a name="p21293mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row21294mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p21296mcpsimp"><a name="p21296mcpsimp"></a><a name="p21296mcpsimp"></a><a href="cap.md">Cap</a></p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p21298mcpsimp"><a name="p21298mcpsimp"></a><a name="p21298mcpsimp"></a>End vertex cap of a polyline. If no vertex cap is set, the default value <a href="buttcap.md">ButtCap</a> will be returned.</p>
</td>
</tr>
</tbody>
</table>

## getJointType<a name="section13384105915161"></a>

<a name="table21300mcpsimp"></a>
<table><thead align="left"><tr id="row21304mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p21306mcpsimp"><a name="p21306mcpsimp"></a><a name="p21306mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row21307mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p21309mcpsimp"><a name="p21309mcpsimp"></a><a name="p21309mcpsimp"></a>public int getJointType()</p>
<p id="p21312mcpsimp"><a name="p21312mcpsimp"></a><a name="p21312mcpsimp"></a>Obtains the joint type of all vertices of a polyline, except the start and end vertices.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table21318mcpsimp"></a>
<table><thead align="left"><tr id="row21323mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p21325mcpsimp"><a name="p21325mcpsimp"></a><a name="p21325mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p21327mcpsimp"><a name="p21327mcpsimp"></a><a name="p21327mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row21328mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p21330mcpsimp"><a name="p21330mcpsimp"></a><a name="p21330mcpsimp"></a>int</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p21332mcpsimp"><a name="p21332mcpsimp"></a><a name="p21332mcpsimp"></a>Joint type of a polyline. The default value is <a href="jointtype.md#section103572813326">DEFAULT</a>.</p>
</td>
</tr>
</tbody>
</table>

## getPattern<a name="section5504927141716"></a>

<a name="table21334mcpsimp"></a>
<table><thead align="left"><tr id="row21338mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p21340mcpsimp"><a name="p21340mcpsimp"></a><a name="p21340mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row21341mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p21343mcpsimp"><a name="p21343mcpsimp"></a><a name="p21343mcpsimp"></a>public List&lt;<a href="patternitem.md">PatternItem</a>&gt; getPattern()</p>
<p id="p21346mcpsimp"><a name="p21346mcpsimp"></a><a name="p21346mcpsimp"></a>Obtains the stroke pattern of a polyline.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table21352mcpsimp"></a>
<table><thead align="left"><tr id="row21357mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p21359mcpsimp"><a name="p21359mcpsimp"></a><a name="p21359mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p21361mcpsimp"><a name="p21361mcpsimp"></a><a name="p21361mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row21362mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p21364mcpsimp"><a name="p21364mcpsimp"></a><a name="p21364mcpsimp"></a>List&lt;<a href="patternitem.md">PatternItem</a>&gt;</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p21366mcpsimp"><a name="p21366mcpsimp"></a><a name="p21366mcpsimp"></a>Stroke pattern of a polyline.</p>
</td>
</tr>
</tbody>
</table>

## getPoints<a name="section352743417182"></a>

<a name="table21368mcpsimp"></a>
<table><thead align="left"><tr id="row21372mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p21374mcpsimp"><a name="p21374mcpsimp"></a><a name="p21374mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row21375mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p21377mcpsimp"><a name="p21377mcpsimp"></a><a name="p21377mcpsimp"></a>public List&lt;<a href="latlng.md">LatLng</a>&gt; getPoints()</p>
<p id="p21380mcpsimp"><a name="p21380mcpsimp"></a><a name="p21380mcpsimp"></a>Obtains all vertices of a polyline.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table21386mcpsimp"></a>
<table><thead align="left"><tr id="row21391mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p21393mcpsimp"><a name="p21393mcpsimp"></a><a name="p21393mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p21395mcpsimp"><a name="p21395mcpsimp"></a><a name="p21395mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row21396mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p21398mcpsimp"><a name="p21398mcpsimp"></a><a name="p21398mcpsimp"></a>List&lt;<a href="latlng.md">LatLng</a>&gt;</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p21400mcpsimp"><a name="p21400mcpsimp"></a><a name="p21400mcpsimp"></a>All vertices of a polyline.</p>
</td>
</tr>
</tbody>
</table>

## getStartCap<a name="section1553061115191"></a>

<a name="table21402mcpsimp"></a>
<table><thead align="left"><tr id="row21406mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p21408mcpsimp"><a name="p21408mcpsimp"></a><a name="p21408mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row21409mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p21411mcpsimp"><a name="p21411mcpsimp"></a><a name="p21411mcpsimp"></a>public <a href="cap.md">Cap</a> getStartCap()</p>
<p id="p293952641920"><a name="p293952641920"></a><a name="p293952641920"></a>Obtains the start vertex cap of a polyline.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table21420mcpsimp"></a>
<table><thead align="left"><tr id="row21425mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p21427mcpsimp"><a name="p21427mcpsimp"></a><a name="p21427mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p21429mcpsimp"><a name="p21429mcpsimp"></a><a name="p21429mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row21430mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p21432mcpsimp"><a name="p21432mcpsimp"></a><a name="p21432mcpsimp"></a><a href="cap.md">Cap</a></p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p21434mcpsimp"><a name="p21434mcpsimp"></a><a name="p21434mcpsimp"></a>Start vertex cap of a polyline. If no vertex cap is set, the default value <a href="buttcap.md">ButtCap</a> will be returned.</p>
</td>
</tr>
</tbody>
</table>

## getWidth<a name="section16511554181916"></a>

<a name="table21436mcpsimp"></a>
<table><thead align="left"><tr id="row21440mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p21442mcpsimp"><a name="p21442mcpsimp"></a><a name="p21442mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row21443mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p21445mcpsimp"><a name="p21445mcpsimp"></a><a name="p21445mcpsimp"></a>public float getWidth()</p>
<p id="p21448mcpsimp"><a name="p21448mcpsimp"></a><a name="p21448mcpsimp"></a>Obtains the stroke width of a polyline.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table21456mcpsimp"></a>
<table><thead align="left"><tr id="row21461mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p21463mcpsimp"><a name="p21463mcpsimp"></a><a name="p21463mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p21465mcpsimp"><a name="p21465mcpsimp"></a><a name="p21465mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row21466mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p21468mcpsimp"><a name="p21468mcpsimp"></a><a name="p21468mcpsimp"></a>float</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p21470mcpsimp"><a name="p21470mcpsimp"></a><a name="p21470mcpsimp"></a>Stroke width of a polyline, in pixels.</p>
<div class="note" id="note17515153182119"><a name="note17515153182119"></a><a name="note17515153182119"></a><span class="notetitle"> NOTE: </span><div class="notebody"><p id="p651514342111"><a name="p651514342111"></a><a name="p651514342111"></a>The stroke width returned by this API is one third of the actual width.</p>
</div></div>
</td>
</tr>
</tbody>
</table>

## getZIndex<a name="section342518338214"></a>

<a name="table21472mcpsimp"></a>
<table><thead align="left"><tr id="row21476mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p21478mcpsimp"><a name="p21478mcpsimp"></a><a name="p21478mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row21479mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p21481mcpsimp"><a name="p21481mcpsimp"></a><a name="p21481mcpsimp"></a>public float getZIndex()</p>
<p id="p17745144272216"><a name="p17745144272216"></a><a name="p17745144272216"></a>Obtains the z-index of a polyline.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table21490mcpsimp"></a>
<table><thead align="left"><tr id="row21495mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p21497mcpsimp"><a name="p21497mcpsimp"></a><a name="p21497mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p21499mcpsimp"><a name="p21499mcpsimp"></a><a name="p21499mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row21500mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p21502mcpsimp"><a name="p21502mcpsimp"></a><a name="p21502mcpsimp"></a>float</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p21504mcpsimp"><a name="p21504mcpsimp"></a><a name="p21504mcpsimp"></a>Z-index, which indicates the overlapping order of a polyline.</p>
</td>
</tr>
</tbody>
</table>

## isClickable<a name="section167712742311"></a>

<a name="table21506mcpsimp"></a>
<table><thead align="left"><tr id="row21510mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p21512mcpsimp"><a name="p21512mcpsimp"></a><a name="p21512mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row21513mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p21515mcpsimp"><a name="p21515mcpsimp"></a><a name="p21515mcpsimp"></a>public boolean isClickable()</p>
<p id="p21518mcpsimp"><a name="p21518mcpsimp"></a><a name="p21518mcpsimp"></a>Checks whether a polyline is tappable.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table21524mcpsimp"></a>
<table><thead align="left"><tr id="row21529mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p21531mcpsimp"><a name="p21531mcpsimp"></a><a name="p21531mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p21533mcpsimp"><a name="p21533mcpsimp"></a><a name="p21533mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row21534mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p21536mcpsimp"><a name="p21536mcpsimp"></a><a name="p21536mcpsimp"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p21538mcpsimp"><a name="p21538mcpsimp"></a><a name="p21538mcpsimp"></a><strong id="b122981047143512"><a name="b122981047143512"></a><a name="b122981047143512"></a>true</strong> if the polyline is tappable; <strong id="b72980479355"><a name="b72980479355"></a><a name="b72980479355"></a>false</strong> otherwise. The default value is <strong id="b16859193612315"><a name="b16859193612315"></a><a name="b16859193612315"></a>false</strong>.</p>
</td>
</tr>
</tbody>
</table>

## isGeodesic<a name="section71902235251"></a>

<a name="table21540mcpsimp"></a>
<table><thead align="left"><tr id="row21544mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p21546mcpsimp"><a name="p21546mcpsimp"></a><a name="p21546mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row21550mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p045334182511"><a name="p045334182511"></a><a name="p045334182511"></a>public boolean isGeodesic()</p>
<p id="p21552mcpsimp"><a name="p21552mcpsimp"></a><a name="p21552mcpsimp"></a>Checks whether each segment of a polyline is drawn as a geodesic.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table21558mcpsimp"></a>
<table><thead align="left"><tr id="row21563mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p21565mcpsimp"><a name="p21565mcpsimp"></a><a name="p21565mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p21567mcpsimp"><a name="p21567mcpsimp"></a><a name="p21567mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row21568mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p21570mcpsimp"><a name="p21570mcpsimp"></a><a name="p21570mcpsimp"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p21572mcpsimp"><a name="p21572mcpsimp"></a><a name="p21572mcpsimp"></a><strong id="b7423125618351"><a name="b7423125618351"></a><a name="b7423125618351"></a>true</strong> if each segment is drawn as a geodesic; <strong id="b10423155663512"><a name="b10423155663512"></a><a name="b10423155663512"></a>false</strong> otherwise.</p>
</td>
</tr>
</tbody>
</table>

## isVisible<a name="section15985923102612"></a>

<a name="table21574mcpsimp"></a>
<table><thead align="left"><tr id="row21578mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p21580mcpsimp"><a name="p21580mcpsimp"></a><a name="p21580mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row21581mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p21583mcpsimp"><a name="p21583mcpsimp"></a><a name="p21583mcpsimp"></a>public boolean isVisible()</p>
<p id="p21586mcpsimp"><a name="p21586mcpsimp"></a><a name="p21586mcpsimp"></a>Checks whether a polyline is visible.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table21592mcpsimp"></a>
<table><thead align="left"><tr id="row21597mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p21599mcpsimp"><a name="p21599mcpsimp"></a><a name="p21599mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p21601mcpsimp"><a name="p21601mcpsimp"></a><a name="p21601mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row21602mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p21604mcpsimp"><a name="p21604mcpsimp"></a><a name="p21604mcpsimp"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p21606mcpsimp"><a name="p21606mcpsimp"></a><a name="p21606mcpsimp"></a><strong id="b1589091093616"><a name="b1589091093616"></a><a name="b1589091093616"></a>true</strong> if the polyline is visible; <strong id="b1289531011366"><a name="b1289531011366"></a><a name="b1289531011366"></a>false</strong> otherwise.</p>
</td>
</tr>
</tbody>
</table>

## jointType<a name="section54645418262"></a>

<a name="table21608mcpsimp"></a>
<table><thead align="left"><tr id="row21612mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p21614mcpsimp"><a name="p21614mcpsimp"></a><a name="p21614mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row21615mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p21617mcpsimp"><a name="p21617mcpsimp"></a><a name="p21617mcpsimp"></a>public <a href="polylineoptions.md">PolylineOptions</a> jointType(int jointType)</p>
<p id="p21620mcpsimp"><a name="p21620mcpsimp"></a><a name="p21620mcpsimp"></a>Sets the joint type of all vertices of a polyline, except the start and end vertices. For details about the allowed joint types, please refer to <a href="jointtype.md">JointType</a>. If the joint type is not set or not an allowed one, the default value <a href="jointtype.md#section103572813326">DEFAULT</a> will be used.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table21623mcpsimp"></a>
<table><thead align="left"><tr id="row21628mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p21630mcpsimp"><a name="p21630mcpsimp"></a><a name="p21630mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p21632mcpsimp"><a name="p21632mcpsimp"></a><a name="p21632mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row21633mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p21635mcpsimp"><a name="p21635mcpsimp"></a><a name="p21635mcpsimp"></a>jointType</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p21637mcpsimp"><a name="p21637mcpsimp"></a><a name="p21637mcpsimp"></a>Joint type. The default value is <a href="jointtype.md#section103572813326">DEFAULT</a>.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table21640mcpsimp"></a>
<table><thead align="left"><tr id="row21645mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p21647mcpsimp"><a name="p21647mcpsimp"></a><a name="p21647mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p21649mcpsimp"><a name="p21649mcpsimp"></a><a name="p21649mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row21650mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p21652mcpsimp"><a name="p21652mcpsimp"></a><a name="p21652mcpsimp"></a>PolylineOptions</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p21654mcpsimp"><a name="p21654mcpsimp"></a><a name="p21654mcpsimp"></a><a href="polylineoptions.md">PolylineOptions</a> object with the new joint type.</p>
</td>
</tr>
</tbody>
</table>

## pattern<a name="section17745728122713"></a>

<a name="table21656mcpsimp"></a>
<table><thead align="left"><tr id="row21660mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p21662mcpsimp"><a name="p21662mcpsimp"></a><a name="p21662mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row21663mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p21665mcpsimp"><a name="p21665mcpsimp"></a><a name="p21665mcpsimp"></a>public <a href="polylineoptions.md">PolylineOptions</a> pattern(List&lt;<a href="patternitem.md">PatternItem</a>&gt; pattern)</p>
<p id="p21668mcpsimp"><a name="p21668mcpsimp"></a><a name="p21668mcpsimp"></a>Sets the stroke pattern of a polyline.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table21671mcpsimp"></a>
<table><thead align="left"><tr id="row21676mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p21678mcpsimp"><a name="p21678mcpsimp"></a><a name="p21678mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p21680mcpsimp"><a name="p21680mcpsimp"></a><a name="p21680mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row21681mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p21683mcpsimp"><a name="p21683mcpsimp"></a><a name="p21683mcpsimp"></a>pattern</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p21685mcpsimp"><a name="p21685mcpsimp"></a><a name="p21685mcpsimp"></a><a href="patternitem.md">PatternItem</a> object set. The default value is <strong id="b6495254776"><a name="b6495254776"></a><a name="b6495254776"></a>null</strong>, indicating that the stroke is in the solid pattern. </p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table21688mcpsimp"></a>
<table><thead align="left"><tr id="row21693mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p21695mcpsimp"><a name="p21695mcpsimp"></a><a name="p21695mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p21697mcpsimp"><a name="p21697mcpsimp"></a><a name="p21697mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row21698mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p21700mcpsimp"><a name="p21700mcpsimp"></a><a name="p21700mcpsimp"></a>PolylineOptions</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p21702mcpsimp"><a name="p21702mcpsimp"></a><a name="p21702mcpsimp"></a><a href="polylineoptions.md">PolylineOptions</a> object with the new pattern setting.</p>
</td>
</tr>
</tbody>
</table>

## startCap<a name="section14983632112810"></a>

<a name="table21704mcpsimp"></a>
<table><thead align="left"><tr id="row21708mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p21710mcpsimp"><a name="p21710mcpsimp"></a><a name="p21710mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row21711mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p21713mcpsimp"><a name="p21713mcpsimp"></a><a name="p21713mcpsimp"></a>public <a href="polylineoptions.md">PolylineOptions</a> startCap(<a href="cap.md">Cap</a> startCap)</p>
<p id="p035819451287"><a name="p035819451287"></a><a name="p035819451287"></a>Sets the start vertex cap of a polyline.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table21721mcpsimp"></a>
<table><thead align="left"><tr id="row21726mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p21728mcpsimp"><a name="p21728mcpsimp"></a><a name="p21728mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p21730mcpsimp"><a name="p21730mcpsimp"></a><a name="p21730mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row21731mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p21733mcpsimp"><a name="p21733mcpsimp"></a><a name="p21733mcpsimp"></a>startCap</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p21735mcpsimp"><a name="p21735mcpsimp"></a><a name="p21735mcpsimp"></a>Start vertex cap. The default value is <a href="buttcap.md">ButtCap</a>.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table21738mcpsimp"></a>
<table><thead align="left"><tr id="row21743mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p21745mcpsimp"><a name="p21745mcpsimp"></a><a name="p21745mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p21747mcpsimp"><a name="p21747mcpsimp"></a><a name="p21747mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row21748mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p21750mcpsimp"><a name="p21750mcpsimp"></a><a name="p21750mcpsimp"></a>PolylineOptions</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p21752mcpsimp"><a name="p21752mcpsimp"></a><a name="p21752mcpsimp"></a><a href="polylineoptions.md">PolylineOptions</a> object with the new start vertex cap setting.</p>
</td>
</tr>
</tbody>
</table>

## visible<a name="section5185611122910"></a>

<a name="table21754mcpsimp"></a>
<table><thead align="left"><tr id="row21758mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p21760mcpsimp"><a name="p21760mcpsimp"></a><a name="p21760mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row21761mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p21763mcpsimp"><a name="p21763mcpsimp"></a><a name="p21763mcpsimp"></a>public <a href="polylineoptions.md">PolylineOptions</a> visible(boolean visible)</p>
<p id="p21766mcpsimp"><a name="p21766mcpsimp"></a><a name="p21766mcpsimp"></a>Sets whether a polyline is visible. If the polyline is invisible, it will not be drawn but all other states will be preserved.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table21769mcpsimp"></a>
<table><thead align="left"><tr id="row21774mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p21776mcpsimp"><a name="p21776mcpsimp"></a><a name="p21776mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p21778mcpsimp"><a name="p21778mcpsimp"></a><a name="p21778mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row21779mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p21781mcpsimp"><a name="p21781mcpsimp"></a><a name="p21781mcpsimp"></a>visible</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p21783mcpsimp"><a name="p21783mcpsimp"></a><a name="p21783mcpsimp"></a>Indicates whether a polyline is visible. The default value is <strong id="b272146105618"><a name="b272146105618"></a><a name="b272146105618"></a>true</strong>, indicating that the polyline is visible.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table21786mcpsimp"></a>
<table><thead align="left"><tr id="row21791mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p21793mcpsimp"><a name="p21793mcpsimp"></a><a name="p21793mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p21795mcpsimp"><a name="p21795mcpsimp"></a><a name="p21795mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row21796mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p21798mcpsimp"><a name="p21798mcpsimp"></a><a name="p21798mcpsimp"></a>PolylineOptions</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p21800mcpsimp"><a name="p21800mcpsimp"></a><a name="p21800mcpsimp"></a><a href="polylineoptions.md">PolylineOptions</a> object with the new visibility setting.</p>
</td>
</tr>
</tbody>
</table>

## width<a name="section4343845172911"></a>

<a name="table21802mcpsimp"></a>
<table><thead align="left"><tr id="row21806mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p21808mcpsimp"><a name="p21808mcpsimp"></a><a name="p21808mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row21809mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p21811mcpsimp"><a name="p21811mcpsimp"></a><a name="p21811mcpsimp"></a>public <a href="polylineoptions.md">PolylineOptions</a> width(float width)</p>
<p id="p21814mcpsimp"><a name="p21814mcpsimp"></a><a name="p21814mcpsimp"></a>Sets the stroke width of a polyline.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table21817mcpsimp"></a>
<table><thead align="left"><tr id="row21822mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p21824mcpsimp"><a name="p21824mcpsimp"></a><a name="p21824mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p21826mcpsimp"><a name="p21826mcpsimp"></a><a name="p21826mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row21827mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p21829mcpsimp"><a name="p21829mcpsimp"></a><a name="p21829mcpsimp"></a>width</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p21831mcpsimp"><a name="p21831mcpsimp"></a><a name="p21831mcpsimp"></a>Stroke width of a polyline, in pixels. The default value is <strong id="b8592114843813"><a name="b8592114843813"></a><a name="b8592114843813"></a>10</strong>.</p>
<div class="note" id="note722162122010"><a name="note722162122010"></a><a name="note722162122010"></a><span class="notetitle"> NOTE: </span><div class="notebody"><p id="p122142192012"><a name="p122142192012"></a><a name="p122142192012"></a>To ensure compatibility, the actual stroke width triples the passed parameter value.</p>
</div></div>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table21834mcpsimp"></a>
<table><thead align="left"><tr id="row21839mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p21841mcpsimp"><a name="p21841mcpsimp"></a><a name="p21841mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p21843mcpsimp"><a name="p21843mcpsimp"></a><a name="p21843mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row21844mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p21846mcpsimp"><a name="p21846mcpsimp"></a><a name="p21846mcpsimp"></a>PolylineOptions</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p21848mcpsimp"><a name="p21848mcpsimp"></a><a name="p21848mcpsimp"></a><a href="polylineoptions.md">PolylineOptions</a> object with the new polyline stroke width.</p>
</td>
</tr>
</tbody>
</table>

**Throws**

<a name="table10494mcpsimp"></a>
<table><thead align="left"><tr id="row10499mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p10501mcpsimp"><a name="p10501mcpsimp"></a><a name="p10501mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p10503mcpsimp"><a name="p10503mcpsimp"></a><a name="p10503mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row10504mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p10506mcpsimp"><a name="p10506mcpsimp"></a><a name="p10506mcpsimp"></a>IllegalArgumentException</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p10508mcpsimp"><a name="p10508mcpsimp"></a><a name="p10508mcpsimp"></a>If the passed stroke width is a negative number.</p>
</td>
</tr>
</tbody>
</table>

## zIndex<a name="section1536018521142"></a>

<a name="table9565548111415"></a>
<table><thead align="left"><tr id="row2620194811145"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p3620154851418"><a name="p3620154851418"></a><a name="p3620154851418"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row462084820149"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p20620154811419"><a name="p20620154811419"></a><a name="p20620154811419"></a>public <a href="polylineoptions.md">PolylineOptions</a> zIndex(float zIndex)</p>
<p id="p8620848131414"><a name="p8620848131414"></a><a name="p8620848131414"></a>Sets the z-index of a polyline. The z-index indicates the overlapping order of a polyline. A polyline with a larger z-index overlaps that with a smaller z-index. Polylines with the same z-index overlap each other by the order in which they are added.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table25720484144"></a>
<table><thead align="left"><tr id="row146205484143"><th class="cellrowborder" valign="top" width="47.02%" id="mcps1.1.3.1.1"><p id="p250mcpsimp"><a name="p250mcpsimp"></a><a name="p250mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="52.980000000000004%" id="mcps1.1.3.1.2"><p id="p253mcpsimp"><a name="p253mcpsimp"></a><a name="p253mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row162010486146"><td class="cellrowborder" valign="top" width="47.02%" headers="mcps1.1.3.1.1 "><p id="p1620194881417"><a name="p1620194881417"></a><a name="p1620194881417"></a>zIndex</p>
</td>
<td class="cellrowborder" valign="top" width="52.980000000000004%" headers="mcps1.1.3.1.2 "><p id="p10620154861417"><a name="p10620154861417"></a><a name="p10620154861417"></a>Z-index, which indicates the overlapping order of a polyline. By default, the z-index is 0.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table25751048111417"></a>
<table><thead align="left"><tr id="row262014815145"><th class="cellrowborder" valign="top" width="47.02%" id="mcps1.1.3.1.1"><p id="p374mcpsimp"><a name="p374mcpsimp"></a><a name="p374mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="52.980000000000004%" id="mcps1.1.3.1.2"><p id="p377mcpsimp"><a name="p377mcpsimp"></a><a name="p377mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row1762054816146"><td class="cellrowborder" valign="top" width="47.02%" headers="mcps1.1.3.1.1 "><p id="p12620948141412"><a name="p12620948141412"></a><a name="p12620948141412"></a>PolylineOptions</p>
</td>
<td class="cellrowborder" valign="top" width="52.980000000000004%" headers="mcps1.1.3.1.2 "><p id="p136214481146"><a name="p136214481146"></a><a name="p136214481146"></a><a href="polylineoptions.md">PolylineOptions</a> object with the new z-index.</p>
</td>
</tr>
</tbody>
</table>

