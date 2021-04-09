# Overview<a name="ZH-CN_TOPIC_0000001099181288"></a>

-   [Interface Summary](#section59921344152916)
-   [Class Summary](#section193323021919)

地图服务SDK的模型类。

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
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p581517133212"><a name="p581517133212"></a><a name="p581517133212"></a>为<a href="tileoverlay.md">TileOverlay</a>提供瓦片图像。 调用这个接口的方法可能会存在多线程，所以实现时注意线程安全。</p>
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
<td class="cellrowborder" valign="top" width="70.71%" headers="mcps1.1.3.1.2 "><p id="p478145391713"><a name="p478145391713"></a><a name="p478145391713"></a>用于定义Bitmap图像，可以通过<a href="bitmapdescriptorfactory.md">BitmapDescriptorFactory</a>类获得。</p>
</td>
</tr>
<tr id="row77815317175"><td class="cellrowborder" valign="top" width="29.29%" headers="mcps1.1.3.1.1 "><p id="p167865318172"><a name="p167865318172"></a><a name="p167865318172"></a><a href="bitmapdescriptorfactory.md">BitmapDescriptorFactory</a></p>
</td>
<td class="cellrowborder" valign="top" width="70.71%" headers="mcps1.1.3.1.2 "><p id="p197845321711"><a name="p197845321711"></a><a name="p197845321711"></a>用于创建Bitmap图像的定义。</p>
</td>
</tr>
<tr id="row97845371717"><td class="cellrowborder" valign="top" width="29.29%" headers="mcps1.1.3.1.1 "><p id="p57995351711"><a name="p57995351711"></a><a name="p57995351711"></a><a href="buttcap.md">ButtCap</a></p>
</td>
<td class="cellrowborder" valign="top" width="70.71%" headers="mcps1.1.3.1.2 "><p id="p8955mcpsimp"><a name="p8955mcpsimp"></a><a name="p8955mcpsimp"></a>继承<a href="cap.md">Cap</a>类，是一种方形的顶点，可用于设置折线起始顶点和末端顶点的样式。</p>
</td>
</tr>
<tr id="row1679253151716"><td class="cellrowborder" valign="top" width="29.29%" headers="mcps1.1.3.1.1 "><p id="p127985381714"><a name="p127985381714"></a><a name="p127985381714"></a><a href="cameraposition.md">CameraPosition</a></p>
</td>
<td class="cellrowborder" valign="top" width="70.71%" headers="mcps1.1.3.1.2 "><p id="p127919533174"><a name="p127919533174"></a><a name="p127919533174"></a>一个封装了相机所有属性的不可变类。</p>
</td>
</tr>
<tr id="row2702165583210"><td class="cellrowborder" valign="top" width="29.29%" headers="mcps1.1.3.1.1 "><p id="p177031755133214"><a name="p177031755133214"></a><a name="p177031755133214"></a><a href="cameraposition-builder.md">CameraPosition.Builder</a></p>
</td>
<td class="cellrowborder" valign="top" width="70.71%" headers="mcps1.1.3.1.2 "><p id="p17039559329"><a name="p17039559329"></a><a name="p17039559329"></a>是<a href="cameraposition.md">CameraPosition</a>的内部接口。</p>
</td>
</tr>
<tr id="row187919535177"><td class="cellrowborder" valign="top" width="29.29%" headers="mcps1.1.3.1.1 "><p id="p1879353161720"><a name="p1879353161720"></a><a name="p1879353161720"></a><a href="cap.md">Cap</a></p>
</td>
<td class="cellrowborder" valign="top" width="70.71%" headers="mcps1.1.3.1.2 "><p id="p1679453151711"><a name="p1679453151711"></a><a name="p1679453151711"></a>用于改变折线的起始顶点或末端顶点。</p>
</td>
</tr>
<tr id="row7808533179"><td class="cellrowborder" valign="top" width="29.29%" headers="mcps1.1.3.1.1 "><p id="p1680135391718"><a name="p1680135391718"></a><a name="p1680135391718"></a><a href="circle.md">Circle</a></p>
</td>
<td class="cellrowborder" valign="top" width="70.71%" headers="mcps1.1.3.1.2 "><p id="p38015532178"><a name="p38015532178"></a><a name="p38015532178"></a>地图上的圆对象。</p>
</td>
</tr>
<tr id="row680115331714"><td class="cellrowborder" valign="top" width="29.29%" headers="mcps1.1.3.1.1 "><p id="p78011534177"><a name="p78011534177"></a><a name="p78011534177"></a><a href="circleoptions.md">CircleOptions</a></p>
</td>
<td class="cellrowborder" valign="top" width="70.71%" headers="mcps1.1.3.1.2 "><p id="p7801253111719"><a name="p7801253111719"></a><a name="p7801253111719"></a>用于设置<a href="circle.md">Circle</a>属性的类。</p>
</td>
</tr>
<tr id="row138962053102014"><td class="cellrowborder" valign="top" width="29.29%" headers="mcps1.1.3.1.1 "><p id="p20896153182014"><a name="p20896153182014"></a><a name="p20896153182014"></a><a href="customcap.md">CustomCap</a></p>
</td>
<td class="cellrowborder" valign="top" width="70.71%" headers="mcps1.1.3.1.2 "><p id="p11506mcpsimp"><a name="p11506mcpsimp"></a><a name="p11506mcpsimp"></a>继承<a href="cap.md">Cap</a>类，用于自定义折线端点样式。</p>
</td>
</tr>
<tr id="row17180114816206"><td class="cellrowborder" valign="top" width="29.29%" headers="mcps1.1.3.1.1 "><p id="p41801482203"><a name="p41801482203"></a><a name="p41801482203"></a><a href="dash.md">Dash</a></p>
</td>
<td class="cellrowborder" valign="top" width="70.71%" headers="mcps1.1.3.1.2 "><p id="p6180348112011"><a name="p6180348112011"></a><a name="p6180348112011"></a>继承自<a href="patternitem.md">PatternItem</a>类，表示折线、多边形或圆的边框中的短划线。</p>
</td>
</tr>
<tr id="row791052152018"><td class="cellrowborder" valign="top" width="29.29%" headers="mcps1.1.3.1.1 "><p id="p199052172016"><a name="p199052172016"></a><a name="p199052172016"></a><a href="dot.md">Dot</a></p>
</td>
<td class="cellrowborder" valign="top" width="70.71%" headers="mcps1.1.3.1.2 "><p id="p11650mcpsimp"><a name="p11650mcpsimp"></a><a name="p11650mcpsimp"></a>继承自<a href="patternitem.md">PatternItem</a>类，表示折线、多边形或圆的边框中的点。</p>
</td>
</tr>
<tr id="row514845052016"><td class="cellrowborder" valign="top" width="29.29%" headers="mcps1.1.3.1.1 "><p id="p2148155013202"><a name="p2148155013202"></a><a name="p2148155013202"></a><a href="gap.md">Gap</a></p>
</td>
<td class="cellrowborder" valign="top" width="70.71%" headers="mcps1.1.3.1.2 "><p id="p181481850162012"><a name="p181481850162012"></a><a name="p181481850162012"></a>继承自<a href="patternitem.md">PatternItem</a>类，表示折线、多边形或圆中边框中的间隙。</p>
</td>
</tr>
<tr id="row108063457203"><td class="cellrowborder" valign="top" width="29.29%" headers="mcps1.1.3.1.1 "><p id="p1780611451204"><a name="p1780611451204"></a><a name="p1780611451204"></a><a href="groundoverlay.md">GroundOverlay</a></p>
</td>
<td class="cellrowborder" valign="top" width="70.71%" headers="mcps1.1.3.1.2 "><p id="p14806124515207"><a name="p14806124515207"></a><a name="p14806124515207"></a>叠加在地图上的图像类。</p>
</td>
</tr>
<tr id="row97301943102015"><td class="cellrowborder" valign="top" width="29.29%" headers="mcps1.1.3.1.1 "><p id="p1731154322018"><a name="p1731154322018"></a><a name="p1731154322018"></a><a href="groundoverlayoptions.md">GroundOverlayOptions</a></p>
</td>
<td class="cellrowborder" valign="top" width="70.71%" headers="mcps1.1.3.1.2 "><p id="p19731124342017"><a name="p19731124342017"></a><a name="p19731124342017"></a>用于设置<a href="groundoverlay.md">GroundOverlay</a>属性的类。</p>
</td>
</tr>
<tr id="row11850154062018"><td class="cellrowborder" valign="top" width="29.29%" headers="mcps1.1.3.1.1 "><p id="p19850114011201"><a name="p19850114011201"></a><a name="p19850114011201"></a><a href="jointtype.md">JointType</a></p>
</td>
<td class="cellrowborder" valign="top" width="70.71%" headers="mcps1.1.3.1.2 "><p id="p1185194014208"><a name="p1185194014208"></a><a name="p1185194014208"></a>折线和多边形边框的节点类型。</p>
</td>
</tr>
<tr id="row1638153518200"><td class="cellrowborder" valign="top" width="29.29%" headers="mcps1.1.3.1.1 "><p id="p463863513206"><a name="p463863513206"></a><a name="p463863513206"></a><a href="latlng.md">LatLng</a></p>
</td>
<td class="cellrowborder" valign="top" width="70.71%" headers="mcps1.1.3.1.2 "><p id="p9638193517207"><a name="p9638193517207"></a><a name="p9638193517207"></a>表示经纬度的不可变类，单位：度。</p>
</td>
</tr>
<tr id="row78992862014"><td class="cellrowborder" valign="top" width="29.29%" headers="mcps1.1.3.1.1 "><p id="p1390428122013"><a name="p1390428122013"></a><a name="p1390428122013"></a><a href="latlngbounds.md">LatLngBounds</a></p>
</td>
<td class="cellrowborder" valign="top" width="70.71%" headers="mcps1.1.3.1.2 "><p id="p79052802013"><a name="p79052802013"></a><a name="p79052802013"></a>表示由一对经纬度定义的矩形区域。</p>
</td>
</tr>
<tr id="row8703839103318"><td class="cellrowborder" valign="top" width="29.29%" headers="mcps1.1.3.1.1 "><p id="p187046397336"><a name="p187046397336"></a><a name="p187046397336"></a><a href="latlngbounds-builder.md">LatLngBounds.Builder</a></p>
</td>
<td class="cellrowborder" valign="top" width="70.71%" headers="mcps1.1.3.1.2 "><p id="p18704113919335"><a name="p18704113919335"></a><a name="p18704113919335"></a><a href="latlngbounds-builder.md">LatLngBounds.Builder</a>是<a href="latlngbounds.md">LatLngBounds</a>的内部接口。</p>
</td>
</tr>
<tr id="row3983832102017"><td class="cellrowborder" valign="top" width="29.29%" headers="mcps1.1.3.1.1 "><p id="p15983113242010"><a name="p15983113242010"></a><a name="p15983113242010"></a><a href="mapstyleoptions.md">MapStyleOptions</a></p>
</td>
<td class="cellrowborder" valign="top" width="70.71%" headers="mcps1.1.3.1.2 "><p id="p798443219206"><a name="p798443219206"></a><a name="p798443219206"></a>用于定义<a href="huaweimap.md">HuaweiMap</a>的样式属性的类，该属性用于自定义地图样式。</p>
</td>
</tr>
<tr id="row789131515248"><td class="cellrowborder" valign="top" width="29.29%" headers="mcps1.1.3.1.1 "><p id="p1589151512415"><a name="p1589151512415"></a><a name="p1589151512415"></a><a href="marker.md">Marker</a></p>
</td>
<td class="cellrowborder" valign="top" width="70.71%" headers="mcps1.1.3.1.2 "><p id="p18911562417"><a name="p18911562417"></a><a name="p18911562417"></a>地图上指定位置的标记对象。</p>
</td>
</tr>
<tr id="row1942817112412"><td class="cellrowborder" valign="top" width="29.29%" headers="mcps1.1.3.1.1 "><p id="p1842917713248"><a name="p1842917713248"></a><a name="p1842917713248"></a><a href="markeroptions.md">MarkerOptions</a></p>
</td>
<td class="cellrowborder" valign="top" width="70.71%" headers="mcps1.1.3.1.2 "><p id="p184290762411"><a name="p184290762411"></a><a name="p184290762411"></a>用于设置<a href="marker.md">Marker</a>属性的类。</p>
</td>
</tr>
<tr id="row21281012416"><td class="cellrowborder" valign="top" width="29.29%" headers="mcps1.1.3.1.1 "><p id="p81316100247"><a name="p81316100247"></a><a name="p81316100247"></a>OnStreetViewPanoramaReadyCallback</p>
</td>
<td class="cellrowborder" valign="top" width="70.71%" headers="mcps1.1.3.1.2 "><p id="p713161012247"><a name="p713161012247"></a><a name="p713161012247"></a>当街道全景地图可用时回调的接口（街景相关功能接口暂不支持）。</p>
</td>
</tr>
<tr id="row1375681252413"><td class="cellrowborder" valign="top" width="29.29%" headers="mcps1.1.3.1.1 "><p id="p4756712152420"><a name="p4756712152420"></a><a name="p4756712152420"></a><a href="patternitem.md">PatternItem</a></p>
</td>
<td class="cellrowborder" valign="top" width="70.71%" headers="mcps1.1.3.1.2 "><p id="p15756181213247"><a name="p15756181213247"></a><a name="p15756181213247"></a>用于定义折线、多边形或圆的边框样式的类。</p>
</td>
</tr>
<tr id="row193991857132512"><td class="cellrowborder" valign="top" width="29.29%" headers="mcps1.1.3.1.1 "><p id="p184001757202520"><a name="p184001757202520"></a><a name="p184001757202520"></a><a href="pointofinterest.md">PointOfInterest</a></p>
</td>
<td class="cellrowborder" valign="top" width="70.71%" headers="mcps1.1.3.1.2 "><p id="p19400205716250"><a name="p19400205716250"></a><a name="p19400205716250"></a>地图上的兴趣点对象。</p>
</td>
</tr>
<tr id="row94015919251"><td class="cellrowborder" valign="top" width="29.29%" headers="mcps1.1.3.1.1 "><p id="p54065910255"><a name="p54065910255"></a><a name="p54065910255"></a><a href="polygon.md">Polygon</a></p>
</td>
<td class="cellrowborder" valign="top" width="70.71%" headers="mcps1.1.3.1.2 "><p id="p241155922515"><a name="p241155922515"></a><a name="p241155922515"></a>地图上的多边形对象。</p>
</td>
</tr>
<tr id="row14377247112516"><td class="cellrowborder" valign="top" width="29.29%" headers="mcps1.1.3.1.1 "><p id="p637894714257"><a name="p637894714257"></a><a name="p637894714257"></a><a href="polygonoptions.md">PolygonOptions</a></p>
</td>
<td class="cellrowborder" valign="top" width="70.71%" headers="mcps1.1.3.1.2 "><p id="p13378134712250"><a name="p13378134712250"></a><a name="p13378134712250"></a>用于设置<a href="polygon.md">Polygon</a>属性的类。</p>
</td>
</tr>
<tr id="row157881055192511"><td class="cellrowborder" valign="top" width="29.29%" headers="mcps1.1.3.1.1 "><p id="p18788115522518"><a name="p18788115522518"></a><a name="p18788115522518"></a><a href="polyline.md">Polyline</a></p>
</td>
<td class="cellrowborder" valign="top" width="70.71%" headers="mcps1.1.3.1.2 "><p id="p67891355152514"><a name="p67891355152514"></a><a name="p67891355152514"></a>地图上的折线对象。</p>
</td>
</tr>
<tr id="row57335532256"><td class="cellrowborder" valign="top" width="29.29%" headers="mcps1.1.3.1.1 "><p id="p117341653152514"><a name="p117341653152514"></a><a name="p117341653152514"></a><a href="polylineoptions.md">PolylineOptions</a></p>
</td>
<td class="cellrowborder" valign="top" width="70.71%" headers="mcps1.1.3.1.2 "><p id="p679217441153"><a name="p679217441153"></a><a name="p679217441153"></a>用于设置<a href="polyline.md">Polyline</a>属性的类。</p>
</td>
</tr>
<tr id="row13853155152519"><td class="cellrowborder" valign="top" width="29.29%" headers="mcps1.1.3.1.1 "><p id="p1485355182516"><a name="p1485355182516"></a><a name="p1485355182516"></a><a href="roundcap.md">RoundCap</a></p>
</td>
<td class="cellrowborder" valign="top" width="70.71%" headers="mcps1.1.3.1.2 "><p id="p21907mcpsimp"><a name="p21907mcpsimp"></a><a name="p21907mcpsimp"></a>继承自<a href="cap.md">Cap</a>类，表示半径等于笔画宽度一半的半圆，圆心在折线的起点或终点。</p>
</td>
</tr>
<tr id="row3776349142510"><td class="cellrowborder" valign="top" width="29.29%" headers="mcps1.1.3.1.1 "><p id="p277644911255"><a name="p277644911255"></a><a name="p277644911255"></a><a href="runtimeremote.md">RuntimeRemoteException</a></p>
</td>
<td class="cellrowborder" valign="top" width="70.71%" headers="mcps1.1.3.1.2 "><p id="p21947mcpsimp"><a name="p21947mcpsimp"></a><a name="p21947mcpsimp"></a><a href="runtimeremote.md">RuntimeRemoteException</a>继承自RuntimeException，是一种运行时异常，当调用地图服务端失败时，会抛出严重异常，不可恢复。</p>
</td>
</tr>
<tr id="row7903194619288"><td class="cellrowborder" valign="top" width="29.29%" headers="mcps1.1.3.1.1 "><p id="p1790419465285"><a name="p1790419465285"></a><a name="p1790419465285"></a><a href="squarecap.md">SquareCap</a></p>
</td>
<td class="cellrowborder" valign="top" width="70.71%" headers="mcps1.1.3.1.2 "><p id="p21973mcpsimp"><a name="p21973mcpsimp"></a><a name="p21973mcpsimp"></a>继承自<a href="cap.md">Cap</a>的类，是一种“方形帽子”，用于设置折线起始顶点或者末端顶点的类型。</p>
</td>
</tr>
<tr id="row082016480288"><td class="cellrowborder" valign="top" width="29.29%" headers="mcps1.1.3.1.1 "><p id="p38201248142814"><a name="p38201248142814"></a><a name="p38201248142814"></a><a href="tile.md">Tile</a></p>
</td>
<td class="cellrowborder" valign="top" width="70.71%" headers="mcps1.1.3.1.2 "><p id="p22675mcpsimp"><a name="p22675mcpsimp"></a><a name="p22675mcpsimp"></a>瓦片，组成<a href="tileoverlay.md">TileOverlay</a>的最小单位。</p>
</td>
</tr>
<tr id="row9811256102817"><td class="cellrowborder" valign="top" width="29.29%" headers="mcps1.1.3.1.1 "><p id="p16811185616285"><a name="p16811185616285"></a><a name="p16811185616285"></a><a href="tileoverlay.md">TileOverlay</a></p>
</td>
<td class="cellrowborder" valign="top" width="70.71%" headers="mcps1.1.3.1.2 "><p id="p18811105618285"><a name="p18811105618285"></a><a name="p18811105618285"></a>地图上瓦片图层的相关类。</p>
</td>
</tr>
<tr id="row89025546283"><td class="cellrowborder" valign="top" width="29.29%" headers="mcps1.1.3.1.1 "><p id="p169031054122811"><a name="p169031054122811"></a><a name="p169031054122811"></a><a href="tileoverlayoptions.md">TileOverlayOptions</a></p>
</td>
<td class="cellrowborder" valign="top" width="70.71%" headers="mcps1.1.3.1.2 "><p id="p15255242498"><a name="p15255242498"></a><a name="p15255242498"></a>用于设置<a href="tileoverlay.md">TileOverlay</a>属性的类。</p>
</td>
</tr>
<tr id="row31771151102820"><td class="cellrowborder" valign="top" width="29.29%" headers="mcps1.1.3.1.1 "><p id="p161782518287"><a name="p161782518287"></a><a name="p161782518287"></a><a href="urltileprovider.md">UrlTileProvider</a></p>
</td>
<td class="cellrowborder" valign="top" width="70.71%" headers="mcps1.1.3.1.2 "><p id="p9178751152818"><a name="p9178751152818"></a><a name="p9178751152818"></a>瓦片图层<a href="tileoverlay.md">TileOverlay</a>的提供者，需要一个URL指向图像。</p>
</td>
</tr>
<tr id="row19950104492810"><td class="cellrowborder" valign="top" width="29.29%" headers="mcps1.1.3.1.1 "><p id="p295113446284"><a name="p295113446284"></a><a name="p295113446284"></a><a href="visibleregion.md">VisibleRegion</a></p>
</td>
<td class="cellrowborder" valign="top" width="70.71%" headers="mcps1.1.3.1.2 "><p id="p1995154442820"><a name="p1995154442820"></a><a name="p1995154442820"></a><a href="visibleregion.md">VisibleRegion</a>实现了Parcelable。它包含四个点，这四个点定义了地图相机的四边形可视区域。</p>
</td>
</tr>
</tbody>
</table>

