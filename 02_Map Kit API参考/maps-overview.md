# Overview<a name="ZH-CN_TOPIC_0000001099341088"></a>

-   [Interface Summary](#section59921344152916)
-   [Class Summary](#section15910112685010)

地图服务SDK的功能类。

## Interface Summary<a name="section59921344152916"></a>

<a name="table126131618196"></a>
<table><thead align="left"><tr id="row132711611198"><th class="cellrowborder" valign="top" width="49.559999999999995%" id="mcps1.1.3.1.1"><p id="p476046133019"><a name="p476046133019"></a><a name="p476046133019"></a>Interface</p>
</th>
<th class="cellrowborder" valign="top" width="50.44%" id="mcps1.1.3.1.2"><p id="p8760156103016"><a name="p8760156103016"></a><a name="p8760156103016"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row172761613196"><td class="cellrowborder" valign="top" width="49.559999999999995%" headers="mcps1.1.3.1.1 "><p id="p181664312105"><a name="p181664312105"></a><a name="p181664312105"></a><a href="cancelablecallback.md">HuaweiMap.CancelableCallback</a></p>
</td>
<td class="cellrowborder" valign="top" width="50.44%" headers="mcps1.1.3.1.2 "><p id="p6164153171011"><a name="p6164153171011"></a><a name="p6164153171011"></a>任务完成或关闭时的回调接口。</p>
</td>
</tr>
<tr id="row82741681913"><td class="cellrowborder" valign="top" width="49.559999999999995%" headers="mcps1.1.3.1.1 "><p id="p12149153191010"><a name="p12149153191010"></a><a name="p12149153191010"></a><a href="infowindowadapter.md">HuaweiMap.InfoWindowAdapter</a></p>
</td>
<td class="cellrowborder" valign="top" width="50.44%" headers="mcps1.1.3.1.2 "><p id="p11118163191012"><a name="p11118163191012"></a><a name="p11118163191012"></a>提供自定义标记信息窗口视图的适配器。</p>
</td>
</tr>
<tr id="row927181641912"><td class="cellrowborder" valign="top" width="49.559999999999995%" headers="mcps1.1.3.1.1 "><p id="p12741614191"><a name="p12741614191"></a><a name="p12741614191"></a><a href="oncameraidlelistener.md">HuaweiMap.OnCameraIdleListener</a></p>
</td>
<td class="cellrowborder" valign="top" width="50.44%" headers="mcps1.1.3.1.2 "><p id="p1131221173012"><a name="p1131221173012"></a><a name="p1131221173012"></a>相机移动结束事件的侦听器。</p>
</td>
</tr>
<tr id="row1827131631919"><td class="cellrowborder" valign="top" width="49.559999999999995%" headers="mcps1.1.3.1.1 "><p id="p208971150161918"><a name="p208971150161918"></a><a name="p208971150161918"></a><a href="oncameramovecanceiedlistener.md">HuaweiMap.OnCameraMoveCanceledListener</a></p>
</td>
<td class="cellrowborder" valign="top" width="50.44%" headers="mcps1.1.3.1.2 "><p id="p3322111117303"><a name="p3322111117303"></a><a name="p3322111117303"></a>相机移动被取消事件的侦听器。</p>
</td>
</tr>
<tr id="row52811616193"><td class="cellrowborder" valign="top" width="49.559999999999995%" headers="mcps1.1.3.1.1 "><p id="p028191671915"><a name="p028191671915"></a><a name="p028191671915"></a><a href="oncameramovelistener.md">HuaweiMap.OnCameraMoveListener</a></p>
</td>
<td class="cellrowborder" valign="top" width="50.44%" headers="mcps1.1.3.1.2 "><p id="p1632661123013"><a name="p1632661123013"></a><a name="p1632661123013"></a>相机移动事件的侦听器。</p>
</td>
</tr>
<tr id="row328111615194"><td class="cellrowborder" valign="top" width="49.559999999999995%" headers="mcps1.1.3.1.1 "><p id="p1728216131911"><a name="p1728216131911"></a><a name="p1728216131911"></a><a href="oncameramovestartedlistener.md">HuaweiMap.OnCameraMoveStartedListener</a></p>
</td>
<td class="cellrowborder" valign="top" width="50.44%" headers="mcps1.1.3.1.2 "><p id="p172814166199"><a name="p172814166199"></a><a name="p172814166199"></a>相机移动开始事件的侦听器。</p>
</td>
</tr>
<tr id="row628616161911"><td class="cellrowborder" valign="top" width="49.559999999999995%" headers="mcps1.1.3.1.1 "><p id="p6281416181916"><a name="p6281416181916"></a><a name="p6281416181916"></a><a href="oncircleclicklistener.md">HuaweiMap.OnCircleClickListener</a></p>
</td>
<td class="cellrowborder" valign="top" width="50.44%" headers="mcps1.1.3.1.2 "><p id="p142819161191"><a name="p142819161191"></a><a name="p142819161191"></a>圆点击事件的侦听器。</p>
</td>
</tr>
<tr id="row128616111910"><td class="cellrowborder" valign="top" width="49.559999999999995%" headers="mcps1.1.3.1.1 "><p id="p182818162190"><a name="p182818162190"></a><a name="p182818162190"></a><a href="ongroundoverlayclicklistener.md">HuaweiMap.OnGroundOverlayClickListener</a></p>
</td>
<td class="cellrowborder" valign="top" width="50.44%" headers="mcps1.1.3.1.2 "><p id="p1128916191916"><a name="p1128916191916"></a><a name="p1128916191916"></a>覆盖物点击事件的侦听器。</p>
</td>
</tr>
<tr id="row828191611913"><td class="cellrowborder" valign="top" width="49.559999999999995%" headers="mcps1.1.3.1.1 "><p id="p8283164194"><a name="p8283164194"></a><a name="p8283164194"></a><a href="oninfowindowclicklistener.md">HuaweiMap.OnInfoWindowClickListener</a></p>
</td>
<td class="cellrowborder" valign="top" width="50.44%" headers="mcps1.1.3.1.2 "><p id="p12821681910"><a name="p12821681910"></a><a name="p12821681910"></a>信息窗口点击事件侦听器。</p>
</td>
</tr>
<tr id="row1128141641916"><td class="cellrowborder" valign="top" width="49.559999999999995%" headers="mcps1.1.3.1.1 "><p id="p199301112215"><a name="p199301112215"></a><a name="p199301112215"></a><a href="oninfowindowcloselistener.md">HuaweiMap.OnInfoWindowCloseListener</a></p>
</td>
<td class="cellrowborder" valign="top" width="50.44%" headers="mcps1.1.3.1.2 "><p id="p1128121651917"><a name="p1128121651917"></a><a name="p1128121651917"></a>信息窗口关闭事件的侦听器。</p>
</td>
</tr>
<tr id="row1728121611190"><td class="cellrowborder" valign="top" width="49.559999999999995%" headers="mcps1.1.3.1.1 "><p id="p1628171620198"><a name="p1628171620198"></a><a name="p1628171620198"></a><a href="oninfowindowlongclicklistener.md">HuaweiMap.OnInfoWindowLongClickListener</a></p>
</td>
<td class="cellrowborder" valign="top" width="50.44%" headers="mcps1.1.3.1.2 "><p id="p929616121911"><a name="p929616121911"></a><a name="p929616121911"></a>信息窗口长按事件的侦听器。</p>
</td>
</tr>
<tr id="row829191691911"><td class="cellrowborder" valign="top" width="49.559999999999995%" headers="mcps1.1.3.1.1 "><p id="p529141661913"><a name="p529141661913"></a><a name="p529141661913"></a><a href="onmapclicklistener.md">HuaweiMap.OnMapClickListener</a></p>
</td>
<td class="cellrowborder" valign="top" width="50.44%" headers="mcps1.1.3.1.2 "><p id="p1333519354276"><a name="p1333519354276"></a><a name="p1333519354276"></a>地图点击事件的侦听器。</p>
</td>
</tr>
<tr id="row329181612196"><td class="cellrowborder" valign="top" width="49.559999999999995%" headers="mcps1.1.3.1.1 "><p id="p1329016141919"><a name="p1329016141919"></a><a name="p1329016141919"></a><a href="onmaploadedcallback.md">HuaweiMap.OnMapLoadedCallback</a></p>
</td>
<td class="cellrowborder" valign="top" width="50.44%" headers="mcps1.1.3.1.2 "><p id="p1291716151915"><a name="p1291716151915"></a><a name="p1291716151915"></a>地图加载完成时的回调接口。</p>
</td>
</tr>
<tr id="row729151681919"><td class="cellrowborder" valign="top" width="49.559999999999995%" headers="mcps1.1.3.1.1 "><p id="p52941631919"><a name="p52941631919"></a><a name="p52941631919"></a><a href="onmaplongclicklistener.md">HuaweiMap.OnMapLongClickListener</a></p>
</td>
<td class="cellrowborder" valign="top" width="50.44%" headers="mcps1.1.3.1.2 "><p id="p16543137172714"><a name="p16543137172714"></a><a name="p16543137172714"></a>地图长按事件的侦听器。</p>
</td>
</tr>
<tr id="row172901681918"><td class="cellrowborder" valign="top" width="49.559999999999995%" headers="mcps1.1.3.1.1 "><p id="p3291416141910"><a name="p3291416141910"></a><a name="p3291416141910"></a><a href="onmarkerclicklistener.md">HuaweiMap.OnMarkerClickListener</a></p>
</td>
<td class="cellrowborder" valign="top" width="50.44%" headers="mcps1.1.3.1.2 "><p id="p1880419380271"><a name="p1880419380271"></a><a name="p1880419380271"></a>标记点击事件的侦听器。</p>
</td>
</tr>
<tr id="row202961612190"><td class="cellrowborder" valign="top" width="49.559999999999995%" headers="mcps1.1.3.1.1 "><p id="p182916162198"><a name="p182916162198"></a><a name="p182916162198"></a><a href="onmarkerdraglistener.md">HuaweiMap.OnMarkerDragListener</a></p>
</td>
<td class="cellrowborder" valign="top" width="50.44%" headers="mcps1.1.3.1.2 "><p id="p3291216121914"><a name="p3291216121914"></a><a name="p3291216121914"></a>标记拖拽事件进行侦听器。</p>
</td>
</tr>
<tr id="row1229816101919"><td class="cellrowborder" valign="top" width="49.559999999999995%" headers="mcps1.1.3.1.1 "><p id="p15291165194"><a name="p15291165194"></a><a name="p15291165194"></a><a href="onmylocationbuttonclicklistener.md">HuaweiMap.OnMyLocationButtonClickListener</a></p>
</td>
<td class="cellrowborder" valign="top" width="50.44%" headers="mcps1.1.3.1.2 "><p id="p1329191617193"><a name="p1329191617193"></a><a name="p1329191617193"></a>我的位置按钮事件点击的侦听器。</p>
</td>
</tr>
<tr id="row20296167193"><td class="cellrowborder" valign="top" width="49.559999999999995%" headers="mcps1.1.3.1.1 "><p id="p6291616131910"><a name="p6291616131910"></a><a name="p6291616131910"></a><a href="onmylocationclicklistener.md">HuaweiMap.OnMyLocationClickListener</a></p>
</td>
<td class="cellrowborder" valign="top" width="50.44%" headers="mcps1.1.3.1.2 "><p id="p52961611915"><a name="p52961611915"></a><a name="p52961611915"></a>我的位置点击事件的侦听器。</p>
</td>
</tr>
<tr id="row1229181631916"><td class="cellrowborder" valign="top" width="49.559999999999995%" headers="mcps1.1.3.1.1 "><p id="p2030181671910"><a name="p2030181671910"></a><a name="p2030181671910"></a><a href="onpoiclicklistener.md">HuaweiMap.OnPoiClickListener</a></p>
</td>
<td class="cellrowborder" valign="top" width="50.44%" headers="mcps1.1.3.1.2 "><p id="p12303162191"><a name="p12303162191"></a><a name="p12303162191"></a>POI点击事件的侦听器。</p>
</td>
</tr>
<tr id="row12387852172311"><td class="cellrowborder" valign="top" width="49.559999999999995%" headers="mcps1.1.3.1.1 "><p id="p19388135211231"><a name="p19388135211231"></a><a name="p19388135211231"></a><a href="onpolygonclicklistener.md">HuaweiMap.OnPolygonClickListener</a></p>
</td>
<td class="cellrowborder" valign="top" width="50.44%" headers="mcps1.1.3.1.2 "><p id="p53891252142311"><a name="p53891252142311"></a><a name="p53891252142311"></a>多边形点击事件的侦听器。</p>
</td>
</tr>
<tr id="row1554717162413"><td class="cellrowborder" valign="top" width="49.559999999999995%" headers="mcps1.1.3.1.1 "><p id="p931911172242"><a name="p931911172242"></a><a name="p931911172242"></a><a href="onpolylineclicklistener.md">HuaweiMap.OnPolylineClickListener</a></p>
</td>
<td class="cellrowborder" valign="top" width="50.44%" headers="mcps1.1.3.1.2 "><p id="p654819119244"><a name="p654819119244"></a><a name="p654819119244"></a>折线点击事件的侦听器。</p>
</td>
</tr>
<tr id="row1037519372412"><td class="cellrowborder" valign="top" width="49.559999999999995%" headers="mcps1.1.3.1.1 "><p id="p658022515248"><a name="p658022515248"></a><a name="p658022515248"></a><a href="snapshotreadycallback.md">HuaweiMap.SnapshotReadyCallback</a></p>
</td>
<td class="cellrowborder" valign="top" width="50.44%" headers="mcps1.1.3.1.2 "><p id="p43761235245"><a name="p43761235245"></a><a name="p43761235245"></a>截图完成时的回调接口。</p>
</td>
</tr>
<tr id="row161402464911"><td class="cellrowborder" valign="top" width="49.559999999999995%" headers="mcps1.1.3.1.1 "><p id="p415122410493"><a name="p415122410493"></a><a name="p415122410493"></a><a href="locationsource.md">LocationSource</a></p>
</td>
<td class="cellrowborder" valign="top" width="50.44%" headers="mcps1.1.3.1.2 "><p id="p6154240496"><a name="p6154240496"></a><a name="p6154240496"></a>定义了一个位置源，提供定位数据。</p>
</td>
</tr>
<tr id="row11925163124919"><td class="cellrowborder" valign="top" width="49.559999999999995%" headers="mcps1.1.3.1.1 "><p id="p8534351175111"><a name="p8534351175111"></a><a name="p8534351175111"></a><a href="onlocationchangedlistener.md">LocationSource.OnLocationChangedListener</a></p>
</td>
<td class="cellrowborder" valign="top" width="50.44%" headers="mcps1.1.3.1.2 "><p id="p13926173184913"><a name="p13926173184913"></a><a name="p13926173184913"></a>位置源改变的侦听器。</p>
</td>
</tr>
<tr id="row1464512924911"><td class="cellrowborder" valign="top" width="49.559999999999995%" headers="mcps1.1.3.1.1 "><p id="p187215975112"><a name="p187215975112"></a><a name="p187215975112"></a><a href="onmapreadycallback.md">OnMapReadyCallback</a></p>
</td>
<td class="cellrowborder" valign="top" width="50.44%" headers="mcps1.1.3.1.2 "><p id="p96450295495"><a name="p96450295495"></a><a name="p96450295495"></a><a href="huaweimap.md">HuaweiMap</a>对象就绪的回调接口。</p>
</td>
</tr>
</tbody>
</table>

## Class Summary<a name="section15910112685010"></a>

<a name="table1983435920912"></a>
<table><thead align="left"><tr id="row178341591290"><th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.1"><p id="p283418590918"><a name="p283418590918"></a><a name="p283418590918"></a>Class</p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.2"><p id="p1583518591799"><a name="p1583518591799"></a><a name="p1583518591799"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row138359591894"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p1483515911912"><a name="p1483515911912"></a><a name="p1483515911912"></a><a href="cameraupdate.md">CameraUpdate</a></p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p683512591095"><a name="p683512591095"></a><a name="p683512591095"></a>定义相机移动参数。</p>
</td>
</tr>
<tr id="row683519597920"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p10835195916915"><a name="p10835195916915"></a><a name="p10835195916915"></a><a href="cameraupdatefactory.md">CameraUpdateFactory</a></p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p148351591995"><a name="p148351591995"></a><a name="p148351591995"></a>包含用于创建<a href="cameraupdate.md">CameraUpdate</a>对象的方法。</p>
</td>
</tr>
<tr id="row883512597915"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p168351659992"><a name="p168351659992"></a><a name="p168351659992"></a><a href="huaweimap.md">HuaweiMap</a></p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p168351959592"><a name="p168351959592"></a><a name="p168351959592"></a>地图服务SDK的主要功能入口类。</p>
</td>
</tr>
<tr id="row583505911910"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p383515592915"><a name="p383515592915"></a><a name="p383515592915"></a><a href="huaweimapooptions.md">HuaweiMapOptions</a></p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p18350595920"><a name="p18350595920"></a><a name="p18350595920"></a>定义<a href="huaweimap.md">HuaweiMap</a>配置信息。</p>
</td>
</tr>
<tr id="row083595916910"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p083516597912"><a name="p083516597912"></a><a name="p083516597912"></a><a href="mapfragment.md">MapFragment</a></p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p9496226191219"><a name="p9496226191219"></a><a name="p9496226191219"></a>继承自Fragment，地图容器。</p>
</td>
</tr>
<tr id="row283619591498"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p1683625917912"><a name="p1683625917912"></a><a name="p1683625917912"></a><a href="mapview.md">MapView</a></p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p783635915919"><a name="p783635915919"></a><a name="p783635915919"></a>继承自FrameLayout，地图容器。</p>
</td>
</tr>
<tr id="row167584194136"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p1775941951318"><a name="p1775941951318"></a><a name="p1775941951318"></a><a href="mapsinitializer.md">MapsInitializer</a></p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p1175991921312"><a name="p1175991921312"></a><a name="p1175991921312"></a>继承自Object的final类，如果在获取地图之前需要使用某些功能，需要使用此类初始化地图服务SDK。</p>
</td>
</tr>
<tr id="row169181712293"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p32098294135"><a name="p32098294135"></a><a name="p32098294135"></a><a href="projection.md">Projection</a></p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p1520914292138"><a name="p1520914292138"></a><a name="p1520914292138"></a>继承自Object的final类，这个类用于在屏幕坐标和经纬度之间进行转换。</p>
</td>
</tr>
<tr id="row2298172715131"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p629952718130"><a name="p629952718130"></a><a name="p629952718130"></a><a href="supportmapfragment.md">SupportMapFragment</a></p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p22013mcpsimp"><a name="p22013mcpsimp"></a><a name="p22013mcpsimp"></a>应用中的地图组件，是应用中放置地图的最简单的方式。通过<a href="mapfragment.md#section11704105017376">getMapAsync</a>，获取地图管理器。</p>
</td>
</tr>
<tr id="row816320716493"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p516413764915"><a name="p516413764915"></a><a name="p516413764915"></a><a href="texturemapfragment.md">TextureMapFragment</a></p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p2164127134910"><a name="p2164127134910"></a><a name="p2164127134910"></a>继承自<a href="mapfragment.md">MapFragment</a>，地图容器。</p>
</td>
</tr>
<tr id="row20524103714517"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p4525137165111"><a name="p4525137165111"></a><a name="p4525137165111"></a><a href="texturemapview.md">TextureMapView</a></p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p16569131570"><a name="p16569131570"></a><a name="p16569131570"></a>继承自<a href="mapview.md">MapView</a>，地图容器。</p>
</td>
</tr>
<tr id="row139953416512"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p799510418510"><a name="p799510418510"></a><a name="p799510418510"></a><a href="texturesupportmapfragment.md">TextureSupportMapFragment</a></p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p5995174114514"><a name="p5995174114514"></a><a name="p5995174114514"></a>继承自Fragment，应用中的地图组件，管理地图生命周期。通过<a href="texturesupportmapfragment.md#section1874811557456">getMapAsync</a>，获取地图管理器。</p>
</td>
</tr>
<tr id="row101721523191318"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p617292320137"><a name="p617292320137"></a><a name="p617292320137"></a><a href="uisettings.md">UiSettings</a></p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p11172142371310"><a name="p11172142371310"></a><a name="p11172142371310"></a>地图内置UI控件及手势控制器。</p>
</td>
</tr>
</tbody>
</table>

