# Overview<a name="EN-US_TOPIC_0000001099181288"></a>

-   [Interface Summary](#section59921344152916)
-   [Class Summary](#section193323021919)

Model classes of the Map SDK.

## Interface Summary<a name="section59921344152916"></a>

<a name="table1776018683019"></a>
<table><thead align="left"><tr id="row6760186203020"><th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.1"><p id="p476046133019"><a name="p476046133019"></a><a name="p476046133019"></a>Interface</p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.2"><p id="p8760156103016"><a name="p8760156103016"></a><a name="p8760156103016"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row1276017683010"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p3430544103118"><a name="p3430544103118"></a><a name="p3430544103118"></a><a href="tileprovider.md">TileProvider</a></p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p581517133212"><a name="p581517133212"></a><a name="p581517133212"></a>Provides tile images for <a href="tileoverlay.md">TileOverlay</a>. The method in this API may be called from multiple threads. Therefore, you must ensure the thread safety when implementing this API.</p>
</td>
</tr>
</tbody>
</table>

## Class Summary<a name="section193323021919"></a>

<a name="table6777536175"></a>
<table><thead align="left"><tr id="row9778536177"><th class="cellrowborder" valign="top" width="29.29%" id="mcps1.1.3.1.1"><p id="p87765381718"><a name="p87765381718"></a><a name="p87765381718"></a>Class</p>
</th>
<th class="cellrowborder" valign="top" width="70.71%" id="mcps1.1.3.1.2"><p id="p178185316174"><a name="p178185316174"></a><a name="p178185316174"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row8781953191714"><td class="cellrowborder" valign="top" width="29.29%" headers="mcps1.1.3.1.1 "><p id="p117865311178"><a name="p117865311178"></a><a name="p117865311178"></a><a href="bitmapdescriptor.md">BitmapDescriptor</a></p>
</td>
<td class="cellrowborder" valign="top" width="70.71%" headers="mcps1.1.3.1.2 "><p id="p478145391713"><a name="p478145391713"></a><a name="p478145391713"></a>Defines a Bitmap image. You can obtain a <strong id="b1873629144513"><a name="b1873629144513"></a><a name="b1873629144513"></a>BitmapDescriptor</strong> using <a href="bitmapdescriptorfactory.md">BitmapDescriptorFactory</a>.</p>
</td>
</tr>
<tr id="row77815317175"><td class="cellrowborder" valign="top" width="29.29%" headers="mcps1.1.3.1.1 "><p id="p167865318172"><a name="p167865318172"></a><a name="p167865318172"></a><a href="bitmapdescriptorfactory.md">BitmapDescriptorFactory</a></p>
</td>
<td class="cellrowborder" valign="top" width="70.71%" headers="mcps1.1.3.1.2 "><p id="p197845321711"><a name="p197845321711"></a><a name="p197845321711"></a>Creates the definition of a Bitmap image.</p>
</td>
</tr>
<tr id="row97845371717"><td class="cellrowborder" valign="top" width="29.29%" headers="mcps1.1.3.1.1 "><p id="p57995351711"><a name="p57995351711"></a><a name="p57995351711"></a><a href="buttcap.md">ButtCap</a></p>
</td>
<td class="cellrowborder" valign="top" width="70.71%" headers="mcps1.1.3.1.2 "><p id="p8955mcpsimp"><a name="p8955mcpsimp"></a><a name="p8955mcpsimp"></a>Extends the <a href="cap.md">Cap</a> class and defines a cap that is squared off exactly at the start or end vertex of a polyline.</p>
</td>
</tr>
<tr id="row1679253151716"><td class="cellrowborder" valign="top" width="29.29%" headers="mcps1.1.3.1.1 "><p id="p127985381714"><a name="p127985381714"></a><a name="p127985381714"></a><a href="cameraposition.md">CameraPosition</a></p>
</td>
<td class="cellrowborder" valign="top" width="70.71%" headers="mcps1.1.3.1.2 "><p id="p127919533174"><a name="p127919533174"></a><a name="p127919533174"></a>An immutable class that encapsulates all camera attributes.</p>
</td>
</tr>
<tr id="row2702165583210"><td class="cellrowborder" valign="top" width="29.29%" headers="mcps1.1.3.1.1 "><p id="p177031755133214"><a name="p177031755133214"></a><a name="p177031755133214"></a><a href="cameraposition-builder.md">CameraPosition.Builder</a></p>
</td>
<td class="cellrowborder" valign="top" width="70.71%" headers="mcps1.1.3.1.2 "><p id="p17039559329"><a name="p17039559329"></a><a name="p17039559329"></a>An internal API of the <a href="cameraposition.md">CameraPosition</a> class.</p>
</td>
</tr>
<tr id="row187919535177"><td class="cellrowborder" valign="top" width="29.29%" headers="mcps1.1.3.1.1 "><p id="p1879353161720"><a name="p1879353161720"></a><a name="p1879353161720"></a><a href="cap.md">Cap</a></p>
</td>
<td class="cellrowborder" valign="top" width="70.71%" headers="mcps1.1.3.1.2 "><p id="p1679453151711"><a name="p1679453151711"></a><a name="p1679453151711"></a>Defines a cap that is applied at the start or end vertex of a polyline.</p>
</td>
</tr>
<tr id="row7808533179"><td class="cellrowborder" valign="top" width="29.29%" headers="mcps1.1.3.1.1 "><p id="p1680135391718"><a name="p1680135391718"></a><a name="p1680135391718"></a><a href="circle.md">Circle</a></p>
</td>
<td class="cellrowborder" valign="top" width="70.71%" headers="mcps1.1.3.1.2 "><p id="p38015532178"><a name="p38015532178"></a><a name="p38015532178"></a>Defines a circle on a map.</p>
</td>
</tr>
<tr id="row680115331714"><td class="cellrowborder" valign="top" width="29.29%" headers="mcps1.1.3.1.1 "><p id="p78011534177"><a name="p78011534177"></a><a name="p78011534177"></a><a href="circleoptions.md">CircleOptions</a></p>
</td>
<td class="cellrowborder" valign="top" width="70.71%" headers="mcps1.1.3.1.2 "><p id="p7801253111719"><a name="p7801253111719"></a><a name="p7801253111719"></a>Defines attributes for a <a href="circle.md">Circle</a> object.</p>
</td>
</tr>
<tr id="row138962053102014"><td class="cellrowborder" valign="top" width="29.29%" headers="mcps1.1.3.1.1 "><p id="p20896153182014"><a name="p20896153182014"></a><a name="p20896153182014"></a><a href="customcap.md">CustomCap</a></p>
</td>
<td class="cellrowborder" valign="top" width="70.71%" headers="mcps1.1.3.1.2 "><p id="p11506mcpsimp"><a name="p11506mcpsimp"></a><a name="p11506mcpsimp"></a>Extends the <a href="cap.md">Cap</a> class to customize the cap style for a polyline.</p>
</td>
</tr>
<tr id="row17180114816206"><td class="cellrowborder" valign="top" width="29.29%" headers="mcps1.1.3.1.1 "><p id="p41801482203"><a name="p41801482203"></a><a name="p41801482203"></a><a href="dash.md">Dash</a></p>
</td>
<td class="cellrowborder" valign="top" width="70.71%" headers="mcps1.1.3.1.2 "><p id="p6180348112011"><a name="p6180348112011"></a><a name="p6180348112011"></a>Extends <a href="patternitem.md">PatternItem</a> and represents a dash used in the stroke pattern for a polyline or the outline of a polygon or circle.</p>
</td>
</tr>
<tr id="row791052152018"><td class="cellrowborder" valign="top" width="29.29%" headers="mcps1.1.3.1.1 "><p id="p199052172016"><a name="p199052172016"></a><a name="p199052172016"></a><a href="dot.md">Dot</a></p>
</td>
<td class="cellrowborder" valign="top" width="70.71%" headers="mcps1.1.3.1.2 "><p id="p11650mcpsimp"><a name="p11650mcpsimp"></a><a name="p11650mcpsimp"></a>Extends <a href="patternitem.md">PatternItem</a> and represents a dot used in the stroke pattern for a polyline or the outline of a polygon or circle.</p>
</td>
</tr>
<tr id="row514845052016"><td class="cellrowborder" valign="top" width="29.29%" headers="mcps1.1.3.1.1 "><p id="p2148155013202"><a name="p2148155013202"></a><a name="p2148155013202"></a><a href="gap.md">Gap</a></p>
</td>
<td class="cellrowborder" valign="top" width="70.71%" headers="mcps1.1.3.1.2 "><p id="p181481850162012"><a name="p181481850162012"></a><a name="p181481850162012"></a>Extends <a href="patternitem.md">PatternItem</a> and represents a gap used in the stroke pattern for a polyline or the outline of a polygon or circle.</p>
</td>
</tr>
<tr id="row108063457203"><td class="cellrowborder" valign="top" width="29.29%" headers="mcps1.1.3.1.1 "><p id="p1780611451204"><a name="p1780611451204"></a><a name="p1780611451204"></a><a href="groundoverlay.md">GroundOverlay</a></p>
</td>
<td class="cellrowborder" valign="top" width="70.71%" headers="mcps1.1.3.1.2 "><p id="p14806124515207"><a name="p14806124515207"></a><a name="p14806124515207"></a>Defines an image that is fixed to a map.</p>
</td>
</tr>
<tr id="row97301943102015"><td class="cellrowborder" valign="top" width="29.29%" headers="mcps1.1.3.1.1 "><p id="p1731154322018"><a name="p1731154322018"></a><a name="p1731154322018"></a><a href="groundoverlayoptions.md">GroundOverlayOptions</a></p>
</td>
<td class="cellrowborder" valign="top" width="70.71%" headers="mcps1.1.3.1.2 "><p id="p19731124342017"><a name="p19731124342017"></a><a name="p19731124342017"></a>Defines attributes for a <a href="groundoverlay.md">GroundOverlay</a> object.</p>
</td>
</tr>
<tr id="row11850154062018"><td class="cellrowborder" valign="top" width="29.29%" headers="mcps1.1.3.1.1 "><p id="p19850114011201"><a name="p19850114011201"></a><a name="p19850114011201"></a><a href="jointtype.md">JointType</a></p>
</td>
<td class="cellrowborder" valign="top" width="70.71%" headers="mcps1.1.3.1.2 "><p id="p1185194014208"><a name="p1185194014208"></a><a name="p1185194014208"></a>Defines the joint type for a polyline or the outline of a polygon.</p>
</td>
</tr>
<tr id="row1638153518200"><td class="cellrowborder" valign="top" width="29.29%" headers="mcps1.1.3.1.1 "><p id="p463863513206"><a name="p463863513206"></a><a name="p463863513206"></a><a href="latlng.md">LatLng</a></p>
</td>
<td class="cellrowborder" valign="top" width="70.71%" headers="mcps1.1.3.1.2 "><p id="p9638193517207"><a name="p9638193517207"></a><a name="p9638193517207"></a>Defines the longitude and latitude, in degrees. This class is immutable.</p>
</td>
</tr>
<tr id="row78992862014"><td class="cellrowborder" valign="top" width="29.29%" headers="mcps1.1.3.1.1 "><p id="p1390428122013"><a name="p1390428122013"></a><a name="p1390428122013"></a><a href="latlngbounds.md">LatLngBounds</a></p>
</td>
<td class="cellrowborder" valign="top" width="70.71%" headers="mcps1.1.3.1.2 "><p id="p79052802013"><a name="p79052802013"></a><a name="p79052802013"></a>Defines a rectangular area using a pair of longitude and latitude.</p>
</td>
</tr>
<tr id="row8703839103318"><td class="cellrowborder" valign="top" width="29.29%" headers="mcps1.1.3.1.1 "><p id="p187046397336"><a name="p187046397336"></a><a name="p187046397336"></a><a href="latlngbounds-builder.md">LatLngBounds.Builder</a></p>
</td>
<td class="cellrowborder" valign="top" width="70.71%" headers="mcps1.1.3.1.2 "><p id="p18704113919335"><a name="p18704113919335"></a><a name="p18704113919335"></a>Builds a <a href="latlngbounds.md">LatLngBounds</a> object. <a href="latlngbounds-builder.md">LatLngBounds.Builder</a> is an internal method of <a href="latlngbounds.md">LatLngBounds</a>.</p>
</td>
</tr>
<tr id="row3983832102017"><td class="cellrowborder" valign="top" width="29.29%" headers="mcps1.1.3.1.1 "><p id="p15983113242010"><a name="p15983113242010"></a><a name="p15983113242010"></a><a href="mapstyleoptions.md">MapStyleOptions</a></p>
</td>
<td class="cellrowborder" valign="top" width="70.71%" headers="mcps1.1.3.1.2 "><p id="p798443219206"><a name="p798443219206"></a><a name="p798443219206"></a>Customizes style attributes for a <a href="huaweimap.md">HuaweiMap</a> object.</p>
</td>
</tr>
<tr id="row789131515248"><td class="cellrowborder" valign="top" width="29.29%" headers="mcps1.1.3.1.1 "><p id="p1589151512415"><a name="p1589151512415"></a><a name="p1589151512415"></a><a href="marker.md">Marker</a></p>
</td>
<td class="cellrowborder" valign="top" width="70.71%" headers="mcps1.1.3.1.2 "><p id="p18911562417"><a name="p18911562417"></a><a name="p18911562417"></a>Defines a marker placed at a specified position on a map.</p>
</td>
</tr>
<tr id="row1942817112412"><td class="cellrowborder" valign="top" width="29.29%" headers="mcps1.1.3.1.1 "><p id="p1842917713248"><a name="p1842917713248"></a><a name="p1842917713248"></a><a href="markeroptions.md">MarkerOptions</a></p>
</td>
<td class="cellrowborder" valign="top" width="70.71%" headers="mcps1.1.3.1.2 "><p id="p184290762411"><a name="p184290762411"></a><a name="p184290762411"></a>Defines attributes for a <a href="marker.md">Marker</a> object.</p>
</td>
</tr>
<tr id="row21281012416"><td class="cellrowborder" valign="top" width="29.29%" headers="mcps1.1.3.1.1 "><p id="p81316100247"><a name="p81316100247"></a><a name="p81316100247"></a>OnStreetViewPanoramaReadyCallback</p>
</td>
<td class="cellrowborder" valign="top" width="70.71%" headers="mcps1.1.3.1.2 "><p id="p713161012247"><a name="p713161012247"></a><a name="p713161012247"></a>Called when the street view panorama is ready for use. (Currently, APIs related to street view are not supported.)</p>
</td>
</tr>
<tr id="row1375681252413"><td class="cellrowborder" valign="top" width="29.29%" headers="mcps1.1.3.1.1 "><p id="p4756712152420"><a name="p4756712152420"></a><a name="p4756712152420"></a><a href="patternitem.md">PatternItem</a></p>
</td>
<td class="cellrowborder" valign="top" width="70.71%" headers="mcps1.1.3.1.2 "><p id="p15756181213247"><a name="p15756181213247"></a><a name="p15756181213247"></a>Defines the stroke pattern of a polyline or the outline of a polygon or circle.</p>
</td>
</tr>
<tr id="row193991857132512"><td class="cellrowborder" valign="top" width="29.29%" headers="mcps1.1.3.1.1 "><p id="p184001757202520"><a name="p184001757202520"></a><a name="p184001757202520"></a><a href="pointofinterest.md">PointOfInterest</a></p>
</td>
<td class="cellrowborder" valign="top" width="70.71%" headers="mcps1.1.3.1.2 "><p id="p19400205716250"><a name="p19400205716250"></a><a name="p19400205716250"></a>Defines a POI on a map.</p>
</td>
</tr>
<tr id="row94015919251"><td class="cellrowborder" valign="top" width="29.29%" headers="mcps1.1.3.1.1 "><p id="p54065910255"><a name="p54065910255"></a><a name="p54065910255"></a><a href="polygon.md">Polygon</a></p>
</td>
<td class="cellrowborder" valign="top" width="70.71%" headers="mcps1.1.3.1.2 "><p id="p241155922515"><a name="p241155922515"></a><a name="p241155922515"></a>Defines a polygon on a map.</p>
</td>
</tr>
<tr id="row14377247112516"><td class="cellrowborder" valign="top" width="29.29%" headers="mcps1.1.3.1.1 "><p id="p637894714257"><a name="p637894714257"></a><a name="p637894714257"></a><a href="polygonoptions.md">PolygonOptions</a></p>
</td>
<td class="cellrowborder" valign="top" width="70.71%" headers="mcps1.1.3.1.2 "><p id="p13378134712250"><a name="p13378134712250"></a><a name="p13378134712250"></a>Defines attributes for a <a href="polygon.md">Polygon</a> object.</p>
</td>
</tr>
<tr id="row157881055192511"><td class="cellrowborder" valign="top" width="29.29%" headers="mcps1.1.3.1.1 "><p id="p18788115522518"><a name="p18788115522518"></a><a name="p18788115522518"></a><a href="polyline.md">Polyline</a></p>
</td>
<td class="cellrowborder" valign="top" width="70.71%" headers="mcps1.1.3.1.2 "><p id="p67891355152514"><a name="p67891355152514"></a><a name="p67891355152514"></a>Defines a polyline on a map.</p>
</td>
</tr>
<tr id="row57335532256"><td class="cellrowborder" valign="top" width="29.29%" headers="mcps1.1.3.1.1 "><p id="p117341653152514"><a name="p117341653152514"></a><a name="p117341653152514"></a><a href="polylineoptions.md">PolylineOptions</a></p>
</td>
<td class="cellrowborder" valign="top" width="70.71%" headers="mcps1.1.3.1.2 "><p id="p679217441153"><a name="p679217441153"></a><a name="p679217441153"></a>Defines attributes for a <a href="polyline.md">Polyline</a> object.</p>
</td>
</tr>
<tr id="row13853155152519"><td class="cellrowborder" valign="top" width="29.29%" headers="mcps1.1.3.1.1 "><p id="p1485355182516"><a name="p1485355182516"></a><a name="p1485355182516"></a><a href="roundcap.md">RoundCap</a></p>
</td>
<td class="cellrowborder" valign="top" width="70.71%" headers="mcps1.1.3.1.2 "><p id="p21907mcpsimp"><a name="p21907mcpsimp"></a><a name="p21907mcpsimp"></a>Extends the <a href="cap.md">Cap</a> class and represents a semicircle with a radius equal to a half of the stroke width. The semicircle will be centered at the start or end vertex of a polyline.</p>
</td>
</tr>
<tr id="row3776349142510"><td class="cellrowborder" valign="top" width="29.29%" headers="mcps1.1.3.1.1 "><p id="p277644911255"><a name="p277644911255"></a><a name="p277644911255"></a><a href="runtimeremote.md">RuntimeRemoteException</a></p>
</td>
<td class="cellrowborder" valign="top" width="70.71%" headers="mcps1.1.3.1.2 "><p id="p21947mcpsimp"><a name="p21947mcpsimp"></a><a name="p21947mcpsimp"></a>Extends <strong id="b3731195393811"><a name="b3731195393811"></a><a name="b3731195393811"></a>RuntimeException</strong>. The exception is thrown to indicate a major exception when the map server fails to be accessed and cannot be recovered.</p>
</td>
</tr>
<tr id="row7903194619288"><td class="cellrowborder" valign="top" width="29.29%" headers="mcps1.1.3.1.1 "><p id="p1790419465285"><a name="p1790419465285"></a><a name="p1790419465285"></a><a href="squarecap.md">SquareCap</a></p>
</td>
<td class="cellrowborder" valign="top" width="70.71%" headers="mcps1.1.3.1.2 "><p id="p21973mcpsimp"><a name="p21973mcpsimp"></a><a name="p21973mcpsimp"></a>Extends <a href="cap.md">Cap</a> and sets the start or end vertex of a polyline to the square type.</p>
</td>
</tr>
<tr id="row082016480288"><td class="cellrowborder" valign="top" width="29.29%" headers="mcps1.1.3.1.1 "><p id="p38201248142814"><a name="p38201248142814"></a><a name="p38201248142814"></a><a href="tile.md">Tile</a></p>
</td>
<td class="cellrowborder" valign="top" width="70.71%" headers="mcps1.1.3.1.2 "><p id="p22675mcpsimp"><a name="p22675mcpsimp"></a><a name="p22675mcpsimp"></a>Defines the minimum unit of <a href="tileoverlay.md">TileOverlay</a>. </p>
</td>
</tr>
<tr id="row9811256102817"><td class="cellrowborder" valign="top" width="29.29%" headers="mcps1.1.3.1.1 "><p id="p16811185616285"><a name="p16811185616285"></a><a name="p16811185616285"></a><a href="tileoverlay.md">TileOverlay</a></p>
</td>
<td class="cellrowborder" valign="top" width="70.71%" headers="mcps1.1.3.1.2 "><p id="p18811105618285"><a name="p18811105618285"></a><a name="p18811105618285"></a>Defines a tile overlay on a map. </p>
</td>
</tr>
<tr id="row89025546283"><td class="cellrowborder" valign="top" width="29.29%" headers="mcps1.1.3.1.1 "><p id="p169031054122811"><a name="p169031054122811"></a><a name="p169031054122811"></a><a href="tileoverlayoptions.md">TileOverlayOptions</a></p>
</td>
<td class="cellrowborder" valign="top" width="70.71%" headers="mcps1.1.3.1.2 "><p id="p15255242498"><a name="p15255242498"></a><a name="p15255242498"></a>Defines attributes for a <a href="tileoverlay.md">TileOverlay</a> object.</p>
</td>
</tr>
<tr id="row31771151102820"><td class="cellrowborder" valign="top" width="29.29%" headers="mcps1.1.3.1.1 "><p id="p161782518287"><a name="p161782518287"></a><a name="p161782518287"></a><a href="urltileprovider.md">UrlTileProvider</a></p>
</td>
<td class="cellrowborder" valign="top" width="70.71%" headers="mcps1.1.3.1.2 "><p id="p9178751152818"><a name="p9178751152818"></a><a name="p9178751152818"></a>Defines the provider of <a href="tileoverlay.md">TileOverlay</a> that requires a URL pointing to an image.</p>
</td>
</tr>
<tr id="row19950104492810"><td class="cellrowborder" valign="top" width="29.29%" headers="mcps1.1.3.1.1 "><p id="p295113446284"><a name="p295113446284"></a><a name="p295113446284"></a><a href="visibleregion.md">VisibleRegion</a></p>
</td>
<td class="cellrowborder" valign="top" width="70.71%" headers="mcps1.1.3.1.2 "><p id="p1995154442820"><a name="p1995154442820"></a><a name="p1995154442820"></a>Implements the <strong id="b48216113415"><a name="b48216113415"></a><a name="b48216113415"></a>Parcelable</strong> API. It contains four points that define a tetragon visible in the camera of a map.</p>
</td>
</tr>
</tbody>
</table>

