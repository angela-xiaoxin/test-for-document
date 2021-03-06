# HuaweiMap<a name="EN-US_TOPIC_0000001145941019"></a>

-   [Nested Class Summary](#section6557355113015)
-   [Public Field Summary](#section181450139302)
-   [Public Method Summary](#section1955212430398)
-   [Public Fields](#section14918414815)
-   [MAP\_TYPE\_NONE](#section19250192319483)
-   [MAP\_TYPE\_NORMAL](#section1020623124910)
-   [Public Methods](#section6735192113919)
-   [addCircle](#section7603022114010)
-   [addGroundOverlay](#section374112486409)
-   [addMarker](#section84151866413)
-   [addPolygon](#section342720397412)
-   [addPolyline](#section527091714515)
-   [addTileOverlay](#section12241957204519)
-   [animateCamera\(CameraUpdate update\)](#section13382161444614)
-   [animateCamera\(CameraUpdate update, HuaweiMap.CancelableCallback callback\)](#section105931534124619)
-   [animateCamera\(CameraUpdate update, int durationMs, HuaweiMap.CancelableCallback callback\)](#section10235112164715)
-   [clear](#section192781734134710)
-   [getCameraPosition](#section6273104784712)
-   [getMapType](#section182805611495)
-   [getMaxZoomLevel](#section10176115075312)
-   [getMinZoomLevel](#section15491181135412)
-   [getProjection](#section10118629175416)
-   [getUiSettings](#section86721421145920)
-   [isBuildingsEnabled](#section12710113985913)
-   [isMyLocationEnabled](#section1749445113591)
-   [isTrafficEnabled](#section4431113205518)
-   [moveCamera](#section168451531308)
-   [resetMinMaxZoomPreference](#section430911571905)
-   [setBuildingsEnabled](#section1956116323019)
-   [setContentDescription](#section123781718617)
-   [setInfoWindowAdapter](#section696710332112)
-   [setLatLngBoundsForCameraTarget](#section11439194715114)
-   [setLocationSource](#section1664916820220)
-   [setMapStyle](#section172547271522)
-   [setMapType](#section3746134811217)
-   [setMarkersClustering](#section02341839699)
-   [setMaxZoomPreference](#section793718196316)
-   [setMinZoomPreference](#section21610342315)
-   [setMyLocationEnabled](#section672514559310)
-   [setOnCameraIdleListener](#section77951391549)
-   [setOnCameraMoveCanceledListener](#section5860828845)
-   [setOnCameraMoveListener](#section166063431548)
-   [setOnCameraMoveStartedListener](#section1555059847)
-   [setOnCircleClickListener](#section185329145511)
-   [setOnGroundOverlayClickListener](#section48222916516)
-   [setOnInfoWindowClickListener](#section14758114215513)
-   [setOnInfoWindowCloseListener](#section1096718581452)
-   [setOnInfoWindowLongClickListener](#section17625311668)
-   [setOnMapClickListener](#section52313331461)
-   [setOnMapLoadedCallback](#section61080560616)
-   [setOnMapLongClickListener](#section7571104711)
-   [setOnMarkerClickListener](#section6157172618712)
-   [setOnMarkerDragListener](#section183907434711)
-   [setOnMyLocationButtonClickListener](#section260912591070)
-   [setOnMyLocationClickListener](#section438716120819)
-   [setOnPoiClickListener](#section34348380817)
-   [setOnPolygonClickListener](#section1893435314811)
-   [setOnPolylineClickListener](#section15655107591)
-   [setPadding](#section10782142412914)
-   [setPointToCenter](#section63930559559)
-   [setTrafficEnabled](#section14752131510581)
-   [snapshot\(HuaweiMap.SnapshotReadyCallback callback\)](#section2497204917913)
-   [snapshot\(HuaweiMap.SnapshotReadyCallback callback, Bitmap bitmap\)](#section208491759897)
-   [stopAnimation](#section4909811181019)


<a name="table737mcpsimp"></a>
<table><thead align="left"><tr id="row741mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p743mcpsimp"><a name="p743mcpsimp"></a><a name="p743mcpsimp"></a>Class Info</p>
</th>
</tr>
</thead>
<tbody><tr id="row744mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p13592412497"><a name="p13592412497"></a><a name="p13592412497"></a>public class HuaweiMap</p>
<p id="p746mcpsimp"><a name="p746mcpsimp"></a><a name="p746mcpsimp"></a>A main class of the HUAWEI Map SDK. The <a href="huaweimap.md">HuaweiMap</a> class is the entry point for all map-related methods. You cannot instantiate a <a href="huaweimap.md">HuaweiMap</a> object directly. Instead, you must obtain an object using the <strong id="b1932474095414"><a name="b1932474095414"></a><a name="b1932474095414"></a>getMapAsync()</strong> method in <a href="mapfragment.md">MapFragment</a> or <a href="mapview.md">MapView</a>.</p>
<div class="note" id="note084818148423"><a name="note084818148423"></a><a name="note084818148423"></a><span class="notetitle"> NOTE: </span><div class="notebody"><p id="p1784831412428"><a name="p1784831412428"></a><a name="p1784831412428"></a>Similar to a <strong id="b1978417532171"><a name="b1978417532171"></a><a name="b1978417532171"></a>View</strong> object, <strong id="b1178765311714"><a name="b1178765311714"></a><a name="b1178765311714"></a>HuaweiMap</strong> can only be read and modified from the Android UI thread. An exception may be thrown if <strong id="b2052465341814"><a name="b2052465341814"></a><a name="b2052465341814"></a>HuaweiMap</strong> is called from other threads.</p>
</div></div>
</td>
</tr>
</tbody>
</table>

## Nested Class Summary<a name="section6557355113015"></a>

<a name="table1110mcpsimp"></a>
<table><thead align="left"><tr id="row1115mcpsimp"><th class="cellrowborder" valign="top" width="56.99999999999999%" id="mcps1.1.3.1.1"><p id="p7543132495318"><a name="p7543132495318"></a><a name="p7543132495318"></a>Qualifier and Type</p>
</th>
<th class="cellrowborder" valign="top" width="43%" id="mcps1.1.3.1.2"><p id="p1554319242536"><a name="p1554319242536"></a><a name="p1554319242536"></a>Class Name and Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row1120mcpsimp"><td class="cellrowborder" valign="top" width="56.99999999999999%" headers="mcps1.1.3.1.1 "><p id="p1456135211228"><a name="p1456135211228"></a><a name="p1456135211228"></a>public interface</p>
</td>
<td class="cellrowborder" valign="top" width="43%" headers="mcps1.1.3.1.2 "><p id="p1122mcpsimp"><a name="p1122mcpsimp"></a><a name="p1122mcpsimp"></a><a href="cancelablecallback.md">HuaweiMap.CancelableCallback</a></p>
<p id="p1124mcpsimp"><a name="p1124mcpsimp"></a><a name="p1124mcpsimp"></a>Provides callbacks executed when a task is finished or closed.</p>
</td>
</tr>
<tr id="row1125mcpsimp"><td class="cellrowborder" valign="top" width="56.99999999999999%" headers="mcps1.1.3.1.1 "><p id="p1127mcpsimp"><a name="p1127mcpsimp"></a><a name="p1127mcpsimp"></a>public interface</p>
</td>
<td class="cellrowborder" valign="top" width="43%" headers="mcps1.1.3.1.2 "><p id="p753176112520"><a name="p753176112520"></a><a name="p753176112520"></a><a href="infowindowadapter.md">HuaweiMap.InfoWindowAdapter</a></p>
<p id="p1129mcpsimp"><a name="p1129mcpsimp"></a><a name="p1129mcpsimp"></a>Provides an adapter for the custom information window view of a marker.</p>
</td>
</tr>
<tr id="row1130mcpsimp"><td class="cellrowborder" valign="top" width="56.99999999999999%" headers="mcps1.1.3.1.1 "><p id="p1132mcpsimp"><a name="p1132mcpsimp"></a><a name="p1132mcpsimp"></a>public interface</p>
</td>
<td class="cellrowborder" valign="top" width="43%" headers="mcps1.1.3.1.2 "><p id="p14404141262513"><a name="p14404141262513"></a><a name="p14404141262513"></a><a href="oncameraidlelistener.md">HuaweiMap.OnCameraIdleListener</a></p>
<p id="p1134mcpsimp"><a name="p1134mcpsimp"></a><a name="p1134mcpsimp"></a>Listens for the end of camera movement.</p>
</td>
</tr>
<tr id="row1135mcpsimp"><td class="cellrowborder" valign="top" width="56.99999999999999%" headers="mcps1.1.3.1.1 "><p id="p1137mcpsimp"><a name="p1137mcpsimp"></a><a name="p1137mcpsimp"></a>public interface</p>
</td>
<td class="cellrowborder" valign="top" width="43%" headers="mcps1.1.3.1.2 "><p id="p74741862519"><a name="p74741862519"></a><a name="p74741862519"></a><a href="oncameramovecanceiedlistener.md">HuaweiMap.OnCameraMoveCanceledListener</a></p>
<p id="p1139mcpsimp"><a name="p1139mcpsimp"></a><a name="p1139mcpsimp"></a>Listens for the stop of camera movement or the beginning of camera movement due to a new reason.</p>
</td>
</tr>
<tr id="row1140mcpsimp"><td class="cellrowborder" valign="top" width="56.99999999999999%" headers="mcps1.1.3.1.1 "><p id="p1142mcpsimp"><a name="p1142mcpsimp"></a><a name="p1142mcpsimp"></a>public interface</p>
</td>
<td class="cellrowborder" valign="top" width="43%" headers="mcps1.1.3.1.2 "><p id="p545919235257"><a name="p545919235257"></a><a name="p545919235257"></a><a href="oncameramovelistener.md">HuaweiMap.OnCameraMoveListener</a></p>
<p id="p1144mcpsimp"><a name="p1144mcpsimp"></a><a name="p1144mcpsimp"></a>Listens for camera movement.</p>
</td>
</tr>
<tr id="row1145mcpsimp"><td class="cellrowborder" valign="top" width="56.99999999999999%" headers="mcps1.1.3.1.1 "><p id="p1147mcpsimp"><a name="p1147mcpsimp"></a><a name="p1147mcpsimp"></a>public interface</p>
</td>
<td class="cellrowborder" valign="top" width="43%" headers="mcps1.1.3.1.2 "><p id="p138115527259"><a name="p138115527259"></a><a name="p138115527259"></a><a href="oncameramovestartedlistener.md">HuaweiMap.OnCameraMoveStartedListener</a></p>
<p id="p1149mcpsimp"><a name="p1149mcpsimp"></a><a name="p1149mcpsimp"></a>Listens for the beginning of camera movement.</p>
</td>
</tr>
<tr id="row1150mcpsimp"><td class="cellrowborder" valign="top" width="56.99999999999999%" headers="mcps1.1.3.1.1 "><p id="p1152mcpsimp"><a name="p1152mcpsimp"></a><a name="p1152mcpsimp"></a>public interface</p>
</td>
<td class="cellrowborder" valign="top" width="43%" headers="mcps1.1.3.1.2 "><p id="p6365757162511"><a name="p6365757162511"></a><a name="p6365757162511"></a><a href="oncircleclicklistener.md">HuaweiMap.OnCircleClickListener</a></p>
<p id="p1154mcpsimp"><a name="p1154mcpsimp"></a><a name="p1154mcpsimp"></a>Listens for the circle tap event.</p>
</td>
</tr>
<tr id="row1155mcpsimp"><td class="cellrowborder" valign="top" width="56.99999999999999%" headers="mcps1.1.3.1.1 "><p id="p1157mcpsimp"><a name="p1157mcpsimp"></a><a name="p1157mcpsimp"></a>public interface</p>
</td>
<td class="cellrowborder" valign="top" width="43%" headers="mcps1.1.3.1.2 "><p id="p136988182615"><a name="p136988182615"></a><a name="p136988182615"></a><a href="ongroundoverlayclicklistener.md">HuaweiMap.OnGroundOverlayClickListener</a></p>
<p id="p1159mcpsimp"><a name="p1159mcpsimp"></a><a name="p1159mcpsimp"></a>Listens for the ground overlay tap event.</p>
</td>
</tr>
<tr id="row1165mcpsimp"><td class="cellrowborder" valign="top" width="56.99999999999999%" headers="mcps1.1.3.1.1 "><p id="p1167mcpsimp"><a name="p1167mcpsimp"></a><a name="p1167mcpsimp"></a>public interface</p>
</td>
<td class="cellrowborder" valign="top" width="43%" headers="mcps1.1.3.1.2 "><p id="p82991512182614"><a name="p82991512182614"></a><a name="p82991512182614"></a><a href="oninfowindowclicklistener.md">HuaweiMap.OnInfoWindowClickListener</a></p>
<p id="p1169mcpsimp"><a name="p1169mcpsimp"></a><a name="p1169mcpsimp"></a>Listens for the information window tap event.</p>
</td>
</tr>
<tr id="row1170mcpsimp"><td class="cellrowborder" valign="top" width="56.99999999999999%" headers="mcps1.1.3.1.1 "><p id="p6691818182618"><a name="p6691818182618"></a><a name="p6691818182618"></a>public interface</p>
</td>
<td class="cellrowborder" valign="top" width="43%" headers="mcps1.1.3.1.2 "><p id="p1664617137514"><a name="p1664617137514"></a><a name="p1664617137514"></a><a href="oninfowindowcloselistener.md">HuaweiMap.OnInfoWindowCloseListener</a></p>
<p id="p1172mcpsimp"><a name="p1172mcpsimp"></a><a name="p1172mcpsimp"></a>Listens for the information window closure event.</p>
</td>
</tr>
<tr id="row1175mcpsimp"><td class="cellrowborder" valign="top" width="56.99999999999999%" headers="mcps1.1.3.1.1 "><p id="p12456644192613"><a name="p12456644192613"></a><a name="p12456644192613"></a>public interface</p>
</td>
<td class="cellrowborder" valign="top" width="43%" headers="mcps1.1.3.1.2 "><p id="p3474113092615"><a name="p3474113092615"></a><a name="p3474113092615"></a><a href="oninfowindowlongclicklistener.md">HuaweiMap.OnInfoWindowLongClickListener</a></p>
<p id="p1179mcpsimp"><a name="p1179mcpsimp"></a><a name="p1179mcpsimp"></a>Listens for the long press event of an information window.</p>
</td>
</tr>
<tr id="row1180mcpsimp"><td class="cellrowborder" valign="top" width="56.99999999999999%" headers="mcps1.1.3.1.1 "><p id="p525719374263"><a name="p525719374263"></a><a name="p525719374263"></a>public interface</p>
</td>
<td class="cellrowborder" valign="top" width="43%" headers="mcps1.1.3.1.2 "><p id="p1182mcpsimp"><a name="p1182mcpsimp"></a><a name="p1182mcpsimp"></a><a href="onmapclicklistener.md">HuaweiMap.OnMapClickListener</a></p>
<p id="p1184mcpsimp"><a name="p1184mcpsimp"></a><a name="p1184mcpsimp"></a>Listens for the map tap event.</p>
</td>
</tr>
<tr id="row1185mcpsimp"><td class="cellrowborder" valign="top" width="56.99999999999999%" headers="mcps1.1.3.1.1 "><p id="p1187mcpsimp"><a name="p1187mcpsimp"></a><a name="p1187mcpsimp"></a>public interface</p>
</td>
<td class="cellrowborder" valign="top" width="43%" headers="mcps1.1.3.1.2 "><p id="p20433452122612"><a name="p20433452122612"></a><a name="p20433452122612"></a><a href="onmaploadedcallback.md">HuaweiMap.OnMapLoadedCallback</a></p>
<p id="p1189mcpsimp"><a name="p1189mcpsimp"></a><a name="p1189mcpsimp"></a>Provides callbacks executed when the map loading is completed.</p>
</td>
</tr>
<tr id="row1190mcpsimp"><td class="cellrowborder" valign="top" width="56.99999999999999%" headers="mcps1.1.3.1.1 "><p id="p9971155911262"><a name="p9971155911262"></a><a name="p9971155911262"></a>public interface</p>
</td>
<td class="cellrowborder" valign="top" width="43%" headers="mcps1.1.3.1.2 "><p id="p1192mcpsimp"><a name="p1192mcpsimp"></a><a name="p1192mcpsimp"></a><a href="onmaplongclicklistener.md">HuaweiMap.OnMapLongClickListener</a></p>
<p id="p1194mcpsimp"><a name="p1194mcpsimp"></a><a name="p1194mcpsimp"></a>Listens for the long press event of a map.</p>
</td>
</tr>
<tr id="row1195mcpsimp"><td class="cellrowborder" valign="top" width="56.99999999999999%" headers="mcps1.1.3.1.1 "><p id="p2705859272"><a name="p2705859272"></a><a name="p2705859272"></a>public interface</p>
</td>
<td class="cellrowborder" valign="top" width="43%" headers="mcps1.1.3.1.2 "><p id="p1197mcpsimp"><a name="p1197mcpsimp"></a><a name="p1197mcpsimp"></a><a href="onmarkerclicklistener.md">HuaweiMap.OnMarkerClickListener</a></p>
<p id="p1199mcpsimp"><a name="p1199mcpsimp"></a><a name="p1199mcpsimp"></a>Listens for the marker tap event.</p>
</td>
</tr>
<tr id="row1200mcpsimp"><td class="cellrowborder" valign="top" width="56.99999999999999%" headers="mcps1.1.3.1.1 "><p id="p123611262710"><a name="p123611262710"></a><a name="p123611262710"></a>public interface</p>
</td>
<td class="cellrowborder" valign="top" width="43%" headers="mcps1.1.3.1.2 "><p id="p1202mcpsimp"><a name="p1202mcpsimp"></a><a name="p1202mcpsimp"></a><a href="onmarkerdraglistener.md">HuaweiMap.OnMarkerDragListener</a></p>
<p id="p1204mcpsimp"><a name="p1204mcpsimp"></a><a name="p1204mcpsimp"></a>Listens for the marker drag event.</p>
</td>
</tr>
<tr id="row1205mcpsimp"><td class="cellrowborder" valign="top" width="56.99999999999999%" headers="mcps1.1.3.1.1 "><p id="p8793104281"><a name="p8793104281"></a><a name="p8793104281"></a>public interface</p>
</td>
<td class="cellrowborder" valign="top" width="43%" headers="mcps1.1.3.1.2 "><p id="p1207mcpsimp"><a name="p1207mcpsimp"></a><a name="p1207mcpsimp"></a><a href="onmylocationbuttonclicklistener.md">HuaweiMap.OnMyLocationButtonClickListener</a></p>
<p id="p1209mcpsimp"><a name="p1209mcpsimp"></a><a name="p1209mcpsimp"></a>Listens for the my-location icon tap event.</p>
</td>
</tr>
<tr id="row1210mcpsimp"><td class="cellrowborder" valign="top" width="56.99999999999999%" headers="mcps1.1.3.1.1 "><p id="p62631111172816"><a name="p62631111172816"></a><a name="p62631111172816"></a>public interface</p>
</td>
<td class="cellrowborder" valign="top" width="43%" headers="mcps1.1.3.1.2 "><p id="p1212mcpsimp"><a name="p1212mcpsimp"></a><a name="p1212mcpsimp"></a><a href="onmylocationclicklistener.md">HuaweiMap.OnMyLocationClickListener</a></p>
<p id="p1214mcpsimp"><a name="p1214mcpsimp"></a><a name="p1214mcpsimp"></a>Listens for my-location dot tap event.</p>
</td>
</tr>
<tr id="row1215mcpsimp"><td class="cellrowborder" valign="top" width="56.99999999999999%" headers="mcps1.1.3.1.1 "><p id="p1964714153285"><a name="p1964714153285"></a><a name="p1964714153285"></a>public interface</p>
</td>
<td class="cellrowborder" valign="top" width="43%" headers="mcps1.1.3.1.2 "><p id="p1217mcpsimp"><a name="p1217mcpsimp"></a><a name="p1217mcpsimp"></a><a href="onpoiclicklistener.md">HuaweiMap.OnPoiClickListener</a></p>
<p id="p1219mcpsimp"><a name="p1219mcpsimp"></a><a name="p1219mcpsimp"></a>Listens for the POI tap event.</p>
</td>
</tr>
<tr id="row1220mcpsimp"><td class="cellrowborder" valign="top" width="56.99999999999999%" headers="mcps1.1.3.1.1 "><p id="p368622019289"><a name="p368622019289"></a><a name="p368622019289"></a>public interface</p>
</td>
<td class="cellrowborder" valign="top" width="43%" headers="mcps1.1.3.1.2 "><p id="p1222mcpsimp"><a name="p1222mcpsimp"></a><a name="p1222mcpsimp"></a><a href="onpolygonclicklistener.md">HuaweiMap.OnPolygonClickListener</a></p>
<p id="p1224mcpsimp"><a name="p1224mcpsimp"></a><a name="p1224mcpsimp"></a>Listens for the polygon tap event.</p>
</td>
</tr>
<tr id="row1225mcpsimp"><td class="cellrowborder" valign="top" width="56.99999999999999%" headers="mcps1.1.3.1.1 "><p id="p1227mcpsimp"><a name="p1227mcpsimp"></a><a name="p1227mcpsimp"></a>public interface</p>
</td>
<td class="cellrowborder" valign="top" width="43%" headers="mcps1.1.3.1.2 "><p id="p15236132962814"><a name="p15236132962814"></a><a name="p15236132962814"></a><a href="onpolylineclicklistener.md">HuaweiMap.OnPolylineClickListener</a></p>
<p id="p1229mcpsimp"><a name="p1229mcpsimp"></a><a name="p1229mcpsimp"></a>Listens for the polyline tap event.</p>
</td>
</tr>
<tr id="row1230mcpsimp"><td class="cellrowborder" valign="top" width="56.99999999999999%" headers="mcps1.1.3.1.1 "><p id="p1396903122817"><a name="p1396903122817"></a><a name="p1396903122817"></a>public interface</p>
</td>
<td class="cellrowborder" valign="top" width="43%" headers="mcps1.1.3.1.2 "><p id="p1232mcpsimp"><a name="p1232mcpsimp"></a><a name="p1232mcpsimp"></a><a href="snapshotreadycallback.md">HuaweiMap.SnapshotReadyCallback</a></p>
<p id="p1234mcpsimp"><a name="p1234mcpsimp"></a><a name="p1234mcpsimp"></a>Executes a callback when a snapshot is generated.</p>
</td>
</tr>
</tbody>
</table>

## Public Field Summary<a name="section181450139302"></a>

<a name="table51207528357"></a>
<table><thead align="left"><tr id="row6121185283516"><th class="cellrowborder" valign="top" width="32.33%" id="mcps1.1.3.1.1"><p id="p1528164471414"><a name="p1528164471414"></a><a name="p1528164471414"></a>Qualifier and Type</p>
</th>
<th class="cellrowborder" valign="top" width="67.67%" id="mcps1.1.3.1.2"><p id="p1554614158108"><a name="p1554614158108"></a><a name="p1554614158108"></a>Field and Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row5517135425419"><td class="cellrowborder" valign="top" width="32.33%" headers="mcps1.1.3.1.1 "><p id="p102751911144219"><a name="p102751911144219"></a><a name="p102751911144219"></a>public static final int</p>
</td>
<td class="cellrowborder" valign="top" width="67.67%" headers="mcps1.1.3.1.2 "><p id="p1176522611422"><a name="p1176522611422"></a><a name="p1176522611422"></a>MAP_TYPE_HYBRID</p>
<p id="p8316624219"><a name="p8316624219"></a><a name="p8316624219"></a>Satellite map with a transparent layer of main streets. (Currently not supported for the Map SDK)</p>
</td>
</tr>
<tr id="row2012119527357"><td class="cellrowborder" valign="top" width="32.33%" headers="mcps1.1.3.1.1 "><p id="p2275411194217"><a name="p2275411194217"></a><a name="p2275411194217"></a>public static final int</p>
</td>
<td class="cellrowborder" valign="top" width="67.67%" headers="mcps1.1.3.1.2 "><p id="p1299317198423"><a name="p1299317198423"></a><a name="p1299317198423"></a><a href="#section19250192319483">MAP_TYPE_NONE</a></p>
<p id="p10312674216"><a name="p10312674216"></a><a name="p10312674216"></a>Empty map.</p>
</td>
</tr>
<tr id="row8121145210353"><td class="cellrowborder" valign="top" width="32.33%" headers="mcps1.1.3.1.1 "><p id="p627521114428"><a name="p627521114428"></a><a name="p627521114428"></a>public static final int</p>
</td>
<td class="cellrowborder" valign="top" width="67.67%" headers="mcps1.1.3.1.2 "><p id="p207092023144218"><a name="p207092023144218"></a><a name="p207092023144218"></a><a href="#section1020623124910">MAP_TYPE_NORMAL</a></p>
<p id="p7311066428"><a name="p7311066428"></a><a name="p7311066428"></a>Basic map.</p>
</td>
</tr>
<tr id="row1362714013429"><td class="cellrowborder" valign="top" width="32.33%" headers="mcps1.1.3.1.1 "><p id="p16276111111429"><a name="p16276111111429"></a><a name="p16276111111429"></a>public static final int</p>
</td>
<td class="cellrowborder" valign="top" width="67.67%" headers="mcps1.1.3.1.2 "><p id="p1476103004218"><a name="p1476103004218"></a><a name="p1476103004218"></a>MAP_TYPE_SATELLITE</p>
<p id="p9311461421"><a name="p9311461421"></a><a name="p9311461421"></a>Satellite map without markers. (Currently not supported for the Map SDK)</p>
</td>
</tr>
<tr id="row1284717016424"><td class="cellrowborder" valign="top" width="32.33%" headers="mcps1.1.3.1.1 "><p id="p72761211134212"><a name="p72761211134212"></a><a name="p72761211134212"></a>public static final int</p>
</td>
<td class="cellrowborder" valign="top" width="67.67%" headers="mcps1.1.3.1.2 "><p id="p195896333425"><a name="p195896333425"></a><a name="p195896333425"></a>MAP_TYPE_TERRAIN</p>
<p id="p143116104213"><a name="p143116104213"></a><a name="p143116104213"></a>Terrain map. (Currently not supported for the Map SDK)</p>
</td>
</tr>
</tbody>
</table>

## Public Method Summary<a name="section1955212430398"></a>

<a name="table1695814271385"></a>
<table><thead align="left"><tr id="row1811628193815"><th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.1"><p id="p081120285386"><a name="p081120285386"></a><a name="p081120285386"></a>Qualifier and Type</p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.2"><p id="p681112883813"><a name="p681112883813"></a><a name="p681112883813"></a>Method Name and Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row78115283381"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p1081114288383"><a name="p1081114288383"></a><a name="p1081114288383"></a><a href="circle.md">Circle</a></p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p18811192820388"><a name="p18811192820388"></a><a name="p18811192820388"></a><a href="#section7603022114010">addCircle</a>(<a href="circleoptions.md">CircleOptions</a> options)</p>
<p id="p9711114213414"><a name="p9711114213414"></a><a name="p9711114213414"></a>Adds a circle to a map. </p>
</td>
</tr>
<tr id="row1811728113818"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p7812182863811"><a name="p7812182863811"></a><a name="p7812182863811"></a><a href="groundoverlay.md">GroundOverlay</a></p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p1581218282381"><a name="p1581218282381"></a><a name="p1581218282381"></a><a href="#section374112486409">addGroundOverlay</a>(<a href="groundoverlayoptions.md">GroundOverlayOptions</a> options)</p>
<p id="p173762441414"><a name="p173762441414"></a><a name="p173762441414"></a>Adds an image to a map.</p>
</td>
</tr>
<tr id="row178121528183820"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p1381282817387"><a name="p1381282817387"></a><a name="p1381282817387"></a><a href="marker.md">Marker</a></p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p2081222815387"><a name="p2081222815387"></a><a name="p2081222815387"></a><a href="#section84151866413">addMarker</a>(<a href="markeroptions.md">MarkerOptions</a> options)</p>
<p id="p1324717453411"><a name="p1324717453411"></a><a name="p1324717453411"></a>Adds a marker to a map. </p>
</td>
</tr>
<tr id="row12812192893816"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p188164287389"><a name="p188164287389"></a><a name="p188164287389"></a><a href="polygon.md">Polygon</a></p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p12816172893812"><a name="p12816172893812"></a><a name="p12816172893812"></a><a href="#section342720397412">addPolygon</a>(<a href="polygonoptions.md">PolygonOptions</a> options)</p>
<p id="p13307346746"><a name="p13307346746"></a><a name="p13307346746"></a>Adds a polygon to a map.</p>
</td>
</tr>
<tr id="row7816102823816"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p381672873813"><a name="p381672873813"></a><a name="p381672873813"></a><a href="polyline.md">Polyline</a></p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p2816128143812"><a name="p2816128143812"></a><a name="p2816128143812"></a><a href="#section527091714515">addPolyline</a>(<a href="polylineoptions.md">PolylineOptions</a> options)</p>
<p id="p12280471840"><a name="p12280471840"></a><a name="p12280471840"></a>Adds a polyline to a map.</p>
</td>
</tr>
<tr id="row208161428203816"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p881672812387"><a name="p881672812387"></a><a name="p881672812387"></a><a href="tileoverlay.md">TileOverlay</a></p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p20816152814387"><a name="p20816152814387"></a><a name="p20816152814387"></a><a href="#section12241957204519">addTileOverlay</a>(<a href="tileoverlayoptions.md">TileOverlayOptions</a> options)</p>
<p id="p173967481542"><a name="p173967481542"></a><a name="p173967481542"></a>Adds a tile overlay to a map.</p>
</td>
</tr>
<tr id="row2817928193813"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p28171328193820"><a name="p28171328193820"></a><a name="p28171328193820"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p2817122863812"><a name="p2817122863812"></a><a name="p2817122863812"></a><a href="#section13382161444614">animateCamera</a>(<a href="cameraupdate.md">CameraUpdate</a> update)</p>
<p id="p1174315502415"><a name="p1174315502415"></a><a name="p1174315502415"></a>Updates the camera position in animation mode.</p>
</td>
</tr>
<tr id="row16817192814387"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p17817192833816"><a name="p17817192833816"></a><a name="p17817192833816"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p14817152820386"><a name="p14817152820386"></a><a name="p14817152820386"></a><a href="#section105931534124619">animateCamera</a>(<a href="cameraupdate.md">CameraUpdate</a> update, <a href="cancelablecallback.md">HuaweiMap.CancelableCallback</a> callback)</p>
<p id="p4914851243"><a name="p4914851243"></a><a name="p4914851243"></a>Updates the camera position in animation mode and calls an optional callback upon animation completion.</p>
</td>
</tr>
<tr id="row1746435646"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p1681762873812"><a name="p1681762873812"></a><a name="p1681762873812"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p58171128153817"><a name="p58171128153817"></a><a name="p58171128153817"></a><a href="#section10235112164715">animateCamera</a>(<a href="cameraupdate.md">CameraUpdate</a> update, int durationMs, <a href="cancelablecallback.md">HuaweiMap.CancelableCallback</a> callback)</p>
<p id="p957213531448"><a name="p957213531448"></a><a name="p957213531448"></a>Updates the camera position in animation mode within a specified period and calls an optional callback upon animation completion.</p>
</td>
</tr>
<tr id="row481802812386"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p158181281386"><a name="p158181281386"></a><a name="p158181281386"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p68181228193813"><a name="p68181228193813"></a><a name="p68181228193813"></a><a href="#section192781734134710">clear</a>()</p>
<p id="p19952055443"><a name="p19952055443"></a><a name="p19952055443"></a>Removes all circles, markers, polylines, ground overlays, and other shapes from a map.</p>
</td>
</tr>
<tr id="row14818528203817"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p9818102873819"><a name="p9818102873819"></a><a name="p9818102873819"></a><a href="cameraposition.md">CameraPosition</a></p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p6818112843814"><a name="p6818112843814"></a><a name="p6818112843814"></a><a href="#section6273104784712">getCameraPosition</a>()</p>
<p id="p93061356443"><a name="p93061356443"></a><a name="p93061356443"></a>Obtains the current position of the camera.</p>
</td>
</tr>
<tr id="row178181228193812"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p12818132883810"><a name="p12818132883810"></a><a name="p12818132883810"></a>int</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p4818102883815"><a name="p4818102883815"></a><a name="p4818102883815"></a><a href="#section182805611495">getMapType</a>()</p>
<p id="p787610157"><a name="p787610157"></a><a name="p787610157"></a>Obtains the current map type.</p>
</td>
</tr>
<tr id="row58181287381"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p168189283385"><a name="p168189283385"></a><a name="p168189283385"></a>float</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p118181028143820"><a name="p118181028143820"></a><a name="p118181028143820"></a><a href="#section10176115075312">getMaxZoomLevel</a>()</p>
<p id="p11484124517"><a name="p11484124517"></a><a name="p11484124517"></a>Obtains the maximum zoom level of the map camera.</p>
</td>
</tr>
<tr id="row681862843816"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p198188286388"><a name="p198188286388"></a><a name="p198188286388"></a>float</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p7818728173810"><a name="p7818728173810"></a><a name="p7818728173810"></a><a href="#section15491181135412">getMinZoomLevel</a>()</p>
<p id="p868018319516"><a name="p868018319516"></a><a name="p868018319516"></a>Obtains the minimum zoom level of the map camera.</p>
</td>
</tr>
<tr id="row581852873818"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p15819132813815"><a name="p15819132813815"></a><a name="p15819132813815"></a><a href="projection.md">Projection</a></p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p7819182893811"><a name="p7819182893811"></a><a name="p7819182893811"></a><a href="#section10118629175416">getProjection</a>()</p>
<p id="p15756741051"><a name="p15756741051"></a><a name="p15756741051"></a>Obtains a <a href="projection.md">Projection</a> object that can be used to convert between the pixel coordinates on the screen and the longitude/latitude coordinates on the map.</p>
</td>
</tr>
<tr id="row1281932853812"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p4819182873820"><a name="p4819182873820"></a><a name="p4819182873820"></a><a href="uisettings.md">UiSettings</a></p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p10819728113815"><a name="p10819728113815"></a><a name="p10819728113815"></a><a href="#section86721421145920">getUiSettings</a>()</p>
<p id="p822116254"><a name="p822116254"></a><a name="p822116254"></a>Obtains the UI and gesture controls of a map, which can determine whether to display the built-in UI (such as zoom buttons and compass) and whether to enable certain gestures such as scroll and zoom gestures.</p>
</td>
</tr>
<tr id="row11819152843814"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p1581942811389"><a name="p1581942811389"></a><a name="p1581942811389"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p3819028203819"><a name="p3819028203819"></a><a name="p3819028203819"></a><a href="#section12710113985913">isBuildingsEnabled</a>()</p>
<p id="p1730628750"><a name="p1730628750"></a><a name="p1730628750"></a>Checks whether the 3D building layer is enabled for a map.</p>
</td>
</tr>
<tr id="row168198280385"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p5819162843816"><a name="p5819162843816"></a><a name="p5819162843816"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p1381992811387"><a name="p1381992811387"></a><a name="p1381992811387"></a><a href="#section1749445113591">isMyLocationEnabled</a>()</p>
<p id="p26741916518"><a name="p26741916518"></a><a name="p26741916518"></a>Checks whether the my-location layer is enabled for a map.</p>
</td>
</tr>
<tr id="row1481982863817"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p6819728203815"><a name="p6819728203815"></a><a name="p6819728203815"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p68191628113812"><a name="p68191628113812"></a><a name="p68191628113812"></a><a href="#section4431113205518">isTrafficEnabled</a>()</p>
<p id="p114331111152"><a name="p114331111152"></a><a name="p114331111152"></a>Checks whether the traffic status layer is enabled.</p>
</td>
</tr>
<tr id="row1819128203819"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p781972819386"><a name="p781972819386"></a><a name="p781972819386"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p482019287382"><a name="p482019287382"></a><a name="p482019287382"></a><a href="#section168451531308">moveCamera</a>(<a href="cameraupdate.md">CameraUpdate</a> update)</p>
<p id="p15996123511"><a name="p15996123511"></a><a name="p15996123511"></a>Updates the camera position. The movement is instantaneous. If <a href="#section6273104784712">getCameraPosition</a><strong id="b16211127115917"><a name="b16211127115917"></a><a name="b16211127115917"></a>()</strong> is called later, the camera will be moved to the new position.</p>
</td>
</tr>
<tr id="row198205283384"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p582062812381"><a name="p582062812381"></a><a name="p582062812381"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p2082032803811"><a name="p2082032803811"></a><a name="p2082032803811"></a><a href="#section430911571905">resetMinMaxZoomPreference</a>()</p>
<p id="p137303132054"><a name="p137303132054"></a><a name="p137303132054"></a>Deletes all maximum and minimum zoom levels set previously.</p>
</td>
</tr>
<tr id="row3820192843815"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p582062893814"><a name="p582062893814"></a><a name="p582062893814"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p3820112843811"><a name="p3820112843811"></a><a name="p3820112843811"></a><a href="#section1956116323019">setBuildingsEnabled</a>(boolean enabled)</p>
<p id="p855811520512"><a name="p855811520512"></a><a name="p855811520512"></a>Sets whether to enable the 3D building layer.</p>
</td>
</tr>
<tr id="row78205282381"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p148201286381"><a name="p148201286381"></a><a name="p148201286381"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p4820112817383"><a name="p4820112817383"></a><a name="p4820112817383"></a><a href="#section123781718617">setContentDescription</a>(String description)</p>
<p id="p772817163513"><a name="p772817163513"></a><a name="p772817163513"></a>Adds content description to a map. If the auxiliary mode is enabled, voice description about the map will be provided. </p>
</td>
</tr>
<tr id="row582032817385"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p382092883811"><a name="p382092883811"></a><a name="p382092883811"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p982002819381"><a name="p982002819381"></a><a name="p982002819381"></a><a href="#section696710332112">setInfoWindowAdapter</a>(<a href="infowindowadapter.md">HuaweiMap.InfoWindowAdapter</a> adapter)</p>
<p id="p46718186519"><a name="p46718186519"></a><a name="p46718186519"></a>Sets a custom adapter for the content of an information window.</p>
</td>
</tr>
<tr id="row38214282380"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p1482172863812"><a name="p1482172863812"></a><a name="p1482172863812"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p15821128183816"><a name="p15821128183816"></a><a name="p15821128183816"></a><a href="#section11439194715114">setLatLngBoundsForCameraTarget</a>(<a href="latlngbounds.md">LatLngBounds</a> bounds)</p>
<p id="p49045191653"><a name="p49045191653"></a><a name="p49045191653"></a>Sets a <a href="latlngbounds.md">LatLngBounds</a> object to constrain the camera target so that the camera target does not move outside the bounds when a user scrolls the map.</p>
</td>
</tr>
<tr id="row1682182810381"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p182132873818"><a name="p182132873818"></a><a name="p182132873818"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p4821152813812"><a name="p4821152813812"></a><a name="p4821152813812"></a><a href="#section1664916820220">setLocationSource</a>(<a href="locationsource.md">LocationSource</a> locationSource)</p>
<p id="p29664228512"><a name="p29664228512"></a><a name="p29664228512"></a>Sets the location source for the my-location layer.</p>
</td>
</tr>
<tr id="row138211928103814"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p1882118280384"><a name="p1882118280384"></a><a name="p1882118280384"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p14821112873813"><a name="p14821112873813"></a><a name="p14821112873813"></a><a href="#section172547271522">setMapStyle</a>(<a href="mapstyleoptions.md">MapStyleOptions</a> option)</p>
<p id="p118714241518"><a name="p118714241518"></a><a name="p118714241518"></a>Sets the map style.</p>
</td>
</tr>
<tr id="row1821172818381"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p198211228203815"><a name="p198211228203815"></a><a name="p198211228203815"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p19821728153819"><a name="p19821728153819"></a><a name="p19821728153819"></a><a href="#section3746134811217">setMapType</a>(int mapType)</p>
<p id="p138679301511"><a name="p138679301511"></a><a name="p138679301511"></a>Sets the map type.</p>
</td>
</tr>
<tr id="row1530095317568"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p1982712893818"><a name="p1982712893818"></a><a name="p1982712893818"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p582712893812"><a name="p582712893812"></a><a name="p582712893812"></a><a href="#section02341839699">setMarkersClustering</a>(boolean isMarkersClustering)</p>
<p id="p18160153214514"><a name="p18160153214514"></a><a name="p18160153214514"></a>Sets whether to cluster markers.</p>
</td>
</tr>
<tr id="row4821328163814"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p1582152813386"><a name="p1582152813386"></a><a name="p1582152813386"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p16821152816388"><a name="p16821152816388"></a><a name="p16821152816388"></a><a href="#section793718196316">setMaxZoomPreference</a>(float maxZoom)</p>
<p id="p126713314517"><a name="p126713314517"></a><a name="p126713314517"></a>Sets the preferred maximum zoom level of the camera.</p>
</td>
</tr>
<tr id="row1082232843814"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p682222817388"><a name="p682222817388"></a><a name="p682222817388"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p11822628173813"><a name="p11822628173813"></a><a name="p11822628173813"></a><a href="#section21610342315">setMinZoomPreference</a>(float minZoom)</p>
<p id="p112891134656"><a name="p112891134656"></a><a name="p112891134656"></a>Sets the preferred minimum zoom level of the camera.</p>
</td>
</tr>
<tr id="row188221928193817"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p13822142883812"><a name="p13822142883812"></a><a name="p13822142883812"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p682215284385"><a name="p682215284385"></a><a name="p682215284385"></a><a href="#section672514559310">setMyLocationEnabled</a>(boolean myLocationEnabled)</p>
<p id="p1513518361510"><a name="p1513518361510"></a><a name="p1513518361510"></a>Sets whether to enable the my-location layer.</p>
</td>
</tr>
<tr id="row482211286383"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p18221128103819"><a name="p18221128103819"></a><a name="p18221128103819"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p15822122817389"><a name="p15822122817389"></a><a name="p15822122817389"></a><a href="#section77951391549">setOnCameraIdleListener</a>(<a href="oncameraidlelistener.md">HuaweiMap.OnCameraIdleListener</a> listener)</p>
<p id="p1035318371050"><a name="p1035318371050"></a><a name="p1035318371050"></a>Sets a listener to listen for the end of camera movement.</p>
</td>
</tr>
<tr id="row58221728143816"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p118223281388"><a name="p118223281388"></a><a name="p118223281388"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p2082292813812"><a name="p2082292813812"></a><a name="p2082292813812"></a><a href="#section5860828845">setOnCameraMoveCanceledListener</a>(<a href="oncameramovecanceiedlistener.md">HuaweiMap.OnCameraMoveCanceledListener</a> listener)</p>
<p id="p16766173814511"><a name="p16766173814511"></a><a name="p16766173814511"></a>Sets a listener to listen for the stop of camera movement or the interruption of camera movement due to a new animation.</p>
</td>
</tr>
<tr id="row2822132883810"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p2082262812380"><a name="p2082262812380"></a><a name="p2082262812380"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p782242814389"><a name="p782242814389"></a><a name="p782242814389"></a><a href="#section166063431548">setOnCameraMoveListener</a>(<a href="oncameramovelistener.md">HuaweiMap.OnCameraMoveListener</a> listener)</p>
<p id="p16657140059"><a name="p16657140059"></a><a name="p16657140059"></a>Sets a listener that is repeatedly called when the camera moves. </p>
</td>
</tr>
<tr id="row08232284381"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p108231528163816"><a name="p108231528163816"></a><a name="p108231528163816"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p168231228133810"><a name="p168231228133810"></a><a name="p168231228133810"></a><a href="#section1555059847">setOnCameraMoveStartedListener</a>(<a href="oncameramovestartedlistener.md">HuaweiMap.OnCameraMoveStartedListener</a> listener)</p>
<p id="p79547417517"><a name="p79547417517"></a><a name="p79547417517"></a>Sets a listener to listen for the beginning of camera movement or changes of the camera movement reason.</p>
</td>
</tr>
<tr id="row68231328133818"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p6823192819388"><a name="p6823192819388"></a><a name="p6823192819388"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p1282332810389"><a name="p1282332810389"></a><a name="p1282332810389"></a><a href="#section185329145511">setOnCircleClickListener</a>(<a href="oncircleclicklistener.md">HuaweiMap.OnCircleClickListener</a> listener)</p>
<p id="p332220431516"><a name="p332220431516"></a><a name="p332220431516"></a>Sets a listener to listen for tap events of a circle.</p>
</td>
</tr>
<tr id="row4823028113811"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p6823162893812"><a name="p6823162893812"></a><a name="p6823162893812"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p582392819382"><a name="p582392819382"></a><a name="p582392819382"></a><a href="#section48222916516">setOnGroundOverlayClickListener</a>(<a href="ongroundoverlayclicklistener.md">HuaweiMap.OnGroundOverlayClickListener</a> listener)</p>
<p id="p1287413442510"><a name="p1287413442510"></a><a name="p1287413442510"></a>Sets a listener to listen for tap events of a ground overlay.</p>
</td>
</tr>
<tr id="row18823152813817"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p138230280388"><a name="p138230280388"></a><a name="p138230280388"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p482342810381"><a name="p482342810381"></a><a name="p482342810381"></a><a href="#section14758114215513">setOnInfoWindowClickListener</a>(<a href="oninfowindowclicklistener.md">HuaweiMap.OnInfoWindowClickListener</a> listener)</p>
<p id="p114678481551"><a name="p114678481551"></a><a name="p114678481551"></a>Sets a listener to listen for tap events of an information window.</p>
</td>
</tr>
<tr id="row1182411283384"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p1382482814383"><a name="p1382482814383"></a><a name="p1382482814383"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p208248283381"><a name="p208248283381"></a><a name="p208248283381"></a><a href="#section1096718581452">setOnInfoWindowCloseListener</a>(<a href="oninfowindowcloselistener.md">HuaweiMap.OnInfoWindowCloseListener</a> listener)</p>
<p id="p153751591266"><a name="p153751591266"></a><a name="p153751591266"></a>Sets a listener to listen for closure events of an information window.</p>
</td>
</tr>
<tr id="row182418285389"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p182492893819"><a name="p182492893819"></a><a name="p182492893819"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p10824628123816"><a name="p10824628123816"></a><a name="p10824628123816"></a><a href="#section17625311668">setOnInfoWindowLongClickListener</a>(<a href="oninfowindowlongclicklistener.md">HuaweiMap.OnInfoWindowLongClickListener</a> listener)</p>
<p id="p1430571017616"><a name="p1430571017616"></a><a name="p1430571017616"></a>Sets a listener to listen for long press events of an information window.</p>
</td>
</tr>
<tr id="row38242028183819"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p178246286389"><a name="p178246286389"></a><a name="p178246286389"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p182418283389"><a name="p182418283389"></a><a name="p182418283389"></a><a href="#section52313331461">setOnMapClickListener</a>(<a href="onmapclicklistener.md">HuaweiMap.OnMapClickListener</a> listener)</p>
<p id="p10440141118611"><a name="p10440141118611"></a><a name="p10440141118611"></a>Sets a listener to listen for tap events of a map.</p>
</td>
</tr>
<tr id="row18824028183813"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p8824152893817"><a name="p8824152893817"></a><a name="p8824152893817"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p11824328193814"><a name="p11824328193814"></a><a name="p11824328193814"></a><a href="#section61080560616">setOnMapLoadedCallback</a>(<a href="onmaploadedcallback.md">HuaweiMap.OnMapLoadedCallback</a> callback)</p>
<p id="p0312112562"><a name="p0312112562"></a><a name="p0312112562"></a>Sets a callback executed when the map loading is completed.</p>
</td>
</tr>
<tr id="row582520285389"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p12825928133812"><a name="p12825928133812"></a><a name="p12825928133812"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p1482532815383"><a name="p1482532815383"></a><a name="p1482532815383"></a><a href="#section7571104711">setOnMapLongClickListener</a>(<a href="onmaplongclicklistener.md">HuaweiMap.OnMapLongClickListener</a> listener)</p>
<p id="p1717001317616"><a name="p1717001317616"></a><a name="p1717001317616"></a>Sets a listener to listen for long press events of a map.</p>
</td>
</tr>
<tr id="row3825628153815"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p4825228103811"><a name="p4825228103811"></a><a name="p4825228103811"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p118252284380"><a name="p118252284380"></a><a name="p118252284380"></a><a href="#section6157172618712">setOnMarkerClickListener</a>(<a href="onmarkerclicklistener.md">HuaweiMap.OnMarkerClickListener</a> listener)</p>
<p id="p11576141412614"><a name="p11576141412614"></a><a name="p11576141412614"></a>Sets a listener to listen for tap events of a marker.</p>
</td>
</tr>
<tr id="row1282592833810"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p1082516280388"><a name="p1082516280388"></a><a name="p1082516280388"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p5825192823812"><a name="p5825192823812"></a><a name="p5825192823812"></a><a href="#section183907434711">setOnMarkerDragListener</a>(<a href="onmarkerdraglistener.md">HuaweiMap.OnMarkerDragListener</a> listener)</p>
<p id="p1567219161069"><a name="p1567219161069"></a><a name="p1567219161069"></a>Sets a listener to listen for drag events of a marker.</p>
</td>
</tr>
<tr id="row2825192883820"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p11826172813386"><a name="p11826172813386"></a><a name="p11826172813386"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p17826132812383"><a name="p17826132812383"></a><a name="p17826132812383"></a><a href="#section260912591070">setOnMyLocationButtonClickListener</a>(<a href="onmylocationbuttonclicklistener.md">HuaweiMap.OnMyLocationButtonClickListener</a> listener)</p>
<p id="p18157101817618"><a name="p18157101817618"></a><a name="p18157101817618"></a>Sets a listener to listen for tap events of the my-location icon.</p>
</td>
</tr>
<tr id="row782618288382"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p1582614280389"><a name="p1582614280389"></a><a name="p1582614280389"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p7826928123816"><a name="p7826928123816"></a><a name="p7826928123816"></a><a href="#section438716120819">setOnMyLocationClickListener</a>(<a href="onmylocationclicklistener.md">HuaweiMap.OnMyLocationClickListener</a> listener)</p>
<p id="p18155111918617"><a name="p18155111918617"></a><a name="p18155111918617"></a>Sets a listener to listen for tap events of the my-location dot.</p>
</td>
</tr>
<tr id="row198261628143814"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p582632812383"><a name="p582632812383"></a><a name="p582632812383"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p68268289385"><a name="p68268289385"></a><a name="p68268289385"></a><a href="#section34348380817">setOnPoiClickListener</a>(<a href="onpoiclicklistener.md">HuaweiMap.OnPoiClickListener</a> listener)</p>
<p id="p9145820167"><a name="p9145820167"></a><a name="p9145820167"></a>Sets a listener to listen for tap events of a POI.</p>
</td>
</tr>
<tr id="row118271028123810"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p1827928183819"><a name="p1827928183819"></a><a name="p1827928183819"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p98279283388"><a name="p98279283388"></a><a name="p98279283388"></a><a href="#section1893435314811">setOnPolygonClickListener</a>(<a href="onpolygonclicklistener.md">HuaweiMap.OnPolygonClickListener</a> listener)</p>
<p id="p828652110617"><a name="p828652110617"></a><a name="p828652110617"></a>Sets a listener to listen for tap events of a polygon.</p>
</td>
</tr>
<tr id="row1482702811383"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p1182732843818"><a name="p1182732843818"></a><a name="p1182732843818"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p118271289383"><a name="p118271289383"></a><a name="p118271289383"></a><a href="#section15655107591">setOnPolylineClickListener</a>(<a href="onpolylineclicklistener.md">HuaweiMap.OnPolylineClickListener</a> listener)</p>
<p id="p115721822268"><a name="p115721822268"></a><a name="p115721822268"></a>Sets a listener to listen for tap events of a polyline.</p>
</td>
</tr>
<tr id="row1982714285386"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p58276285388"><a name="p58276285388"></a><a name="p58276285388"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p682711281389"><a name="p682711281389"></a><a name="p682711281389"></a><a href="#section10782142412914">setPadding</a>(int left, int top, int right, int bottom)</p>
<p id="p5175123952217"><a name="p5175123952217"></a><a name="p5175123952217"></a>Sets padding on a map to define the visible region on a map. Some portions around the map edges may be obscured.</p>
</td>
</tr>
<tr id="row148013919542"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p178113985412"><a name="p178113985412"></a><a name="p178113985412"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p19811439205417"><a name="p19811439205417"></a><a name="p19811439205417"></a><a href="#section63930559559">setPointToCenter</a>(int x,int y)</p>
<p id="p1434094112558"><a name="p1434094112558"></a><a name="p1434094112558"></a>Sets a fixed screen center for zooming.</p>
</td>
</tr>
<tr id="row582792818385"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p1827112815389"><a name="p1827112815389"></a><a name="p1827112815389"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p208271028143817"><a name="p208271028143817"></a><a name="p208271028143817"></a><a href="#section14752131510581">setTrafficEnabled</a>(boolean enabled)</p>
<p id="p10540132519615"><a name="p10540132519615"></a><a name="p10540132519615"></a>Sets whether to enable the traffic status layer.</p>
</td>
</tr>
<tr id="row2827152817389"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p10827102873815"><a name="p10827102873815"></a><a name="p10827102873815"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p2828828143815"><a name="p2828828143815"></a><a name="p2828828143815"></a><a href="#section2497204917913">snapshot</a>(<a href="snapshotreadycallback.md">HuaweiMap.SnapshotReadyCallback</a> callback)</p>
<p id="p54892267613"><a name="p54892267613"></a><a name="p54892267613"></a>Takes a snapshot of a map.</p>
</td>
</tr>
<tr id="row1982822812383"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p178288282383"><a name="p178288282383"></a><a name="p178288282383"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p58281928193814"><a name="p58281928193814"></a><a name="p58281928193814"></a><a href="#section208491759897">snapshot</a>(<a href="snapshotreadycallback.md">HuaweiMap.SnapshotReadyCallback</a> callback, Bitmap bitmap)</p>
<p id="p1547172717615"><a name="p1547172717615"></a><a name="p1547172717615"></a>Takes a snapshot of a map.</p>
</td>
</tr>
<tr id="row1828172893811"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p1982817287384"><a name="p1982817287384"></a><a name="p1982817287384"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p148281428173812"><a name="p148281428173812"></a><a name="p148281428173812"></a><a href="#section4909811181019">stopAnimation</a>()</p>
<p id="p1443811291864"><a name="p1443811291864"></a><a name="p1443811291864"></a>Stops the current animation of the camera.</p>
</td>
</tr>
</tbody>
</table>

## Public Fields<a name="section14918414815"></a>

## MAP\_TYPE\_NONE<a name="section19250192319483"></a>

<a name="table1735141612498"></a>
<table><thead align="left"><tr id="row57364161492"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p3736216194918"><a name="p3736216194918"></a><a name="p3736216194918"></a>Fields</p>
</th>
</tr>
</thead>
<tbody><tr id="row16736161624920"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p8736916184914"><a name="p8736916184914"></a><a name="p8736916184914"></a>public static final int MAP_TYPE_NONE</p>
<p id="p199812131527"><a name="p199812131527"></a><a name="p199812131527"></a>Empty map.</p>
<p id="p10901845133116"><a name="p10901845133116"></a><a name="p10901845133116"></a><strong id="b11900457311"><a name="b11900457311"></a><a name="b11900457311"></a>MAP_TYPE_NONE</strong>: 0</p>
<p id="p8331851255"><a name="p8331851255"></a><a name="p8331851255"></a>For other constant values, please refer to <a href="constant-values.md#section4943154465210">Constant-values</a>.</p>
</td>
</tr>
</tbody>
</table>

## MAP\_TYPE\_NORMAL<a name="section1020623124910"></a>

<a name="table19206183110496"></a>
<table><thead align="left"><tr id="row12064310491"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p1320703144916"><a name="p1320703144916"></a><a name="p1320703144916"></a>Fields</p>
</th>
</tr>
</thead>
<tbody><tr id="row1620711317498"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p1207123118495"><a name="p1207123118495"></a><a name="p1207123118495"></a>public static final int MAP_TYPE_NORMAL</p>
<p id="p18298141611526"><a name="p18298141611526"></a><a name="p18298141611526"></a>Basic map.</p>
<p id="p148379521317"><a name="p148379521317"></a><a name="p148379521317"></a><strong id="b48371652203118"><a name="b48371652203118"></a><a name="b48371652203118"></a>MAP_TYPE_NORMAL</strong>: 1</p>
<p id="p682813112497"><a name="p682813112497"></a><a name="p682813112497"></a>For other constant values, please refer to <a href="constant-values.md#section4943154465210">Constant-values</a>.</p>
</td>
</tr>
</tbody>
</table>

## Public Methods<a name="section6735192113919"></a>

## addCircle<a name="section7603022114010"></a>

<a name="table8353134085314"></a>
<table><thead align="left"><tr id="row549344013536"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p1249418406538"><a name="p1249418406538"></a><a name="p1249418406538"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row1749434045313"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p2049424018530"><a name="p2049424018530"></a><a name="p2049424018530"></a>public <a href="circle.md">Circle</a> addCircle(<a href="circleoptions.md">CircleOptions</a> options)</p>
<p id="p14494104085318"><a name="p14494104085318"></a><a name="p14494104085318"></a>Adds a circle to a map. The longitude and latitude of the center and the radius are specified for the circle to indicate the surrounding area of a location.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table17106172813818"></a>
<table><thead align="left"><tr id="row198282288389"><th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.1"><p id="p1882872883816"><a name="p1882872883816"></a><a name="p1882872883816"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.2"><p id="p158281928123816"><a name="p158281928123816"></a><a name="p158281928123816"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row982818282380"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p482842811386"><a name="p482842811386"></a><a name="p482842811386"></a>options</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p282820288387"><a name="p282820288387"></a><a name="p282820288387"></a>Attributes of a circle.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table410992812382"></a>
<table><thead align="left"><tr id="row13828192818382"><th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.1"><p id="p4829528153818"><a name="p4829528153818"></a><a name="p4829528153818"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.2"><p id="p382942815381"><a name="p382942815381"></a><a name="p382942815381"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row19829192810381"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p2829142812386"><a name="p2829142812386"></a><a name="p2829142812386"></a>Circle</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p12829102833819"><a name="p12829102833819"></a><a name="p12829102833819"></a><a href="circle.md">Circle</a> object.</p>
</td>
</tr>
</tbody>
</table>

## addGroundOverlay<a name="section374112486409"></a>

<a name="table117513488413"></a>
<table><thead align="left"><tr id="row3325134817410"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p163251448247"><a name="p163251448247"></a><a name="p163251448247"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row103259482041"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p15325184811419"><a name="p15325184811419"></a><a name="p15325184811419"></a>public <a href="groundoverlay.md">GroundOverlay</a> addGroundOverlay(<a href="groundoverlayoptions.md">GroundOverlayOptions</a> options)</p>
<p id="p83257489413"><a name="p83257489413"></a><a name="p83257489413"></a>Adds an image to a map.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table1811215281383"></a>
<table><thead align="left"><tr id="row18295288385"><th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.1"><p id="p11829142843816"><a name="p11829142843816"></a><a name="p11829142843816"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.2"><p id="p108291228113819"><a name="p108291228113819"></a><a name="p108291228113819"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row1582942815381"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p1882952823817"><a name="p1882952823817"></a><a name="p1882952823817"></a>options</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p6829162813817"><a name="p6829162813817"></a><a name="p6829162813817"></a>Attributes of a ground overlay. An image and a position must be specified for the ground overlay.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table171141228153817"></a>
<table><thead align="left"><tr id="row14829728183818"><th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.1"><p id="p14829132811387"><a name="p14829132811387"></a><a name="p14829132811387"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.2"><p id="p28292028163813"><a name="p28292028163813"></a><a name="p28292028163813"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row19829132883819"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p8829172812384"><a name="p8829172812384"></a><a name="p8829172812384"></a>GroundOverlay</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p682942873813"><a name="p682942873813"></a><a name="p682942873813"></a><a href="groundoverlay.md">GroundOverlay</a> object.</p>
</td>
</tr>
</tbody>
</table>

**Throws**

<a name="table15117528163817"></a>
<table><thead align="left"><tr id="row19829182823817"><th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.1"><p id="p2083032843819"><a name="p2083032843819"></a><a name="p2083032843819"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.2"><p id="p168301928193811"><a name="p168301928193811"></a><a name="p168301928193811"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row1830132811387"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p683015282386"><a name="p683015282386"></a><a name="p683015282386"></a>IllegalArgumentException</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p983032813383"><a name="p983032813383"></a><a name="p983032813383"></a>If no image or location is specified in the <strong id="b372610111209"><a name="b372610111209"></a><a name="b372610111209"></a>options</strong> parameter.</p>
</td>
</tr>
</tbody>
</table>

## addMarker<a name="section84151866413"></a>

<a name="table112414217511"></a>
<table><thead align="left"><tr id="row173311028519"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p173311421252"><a name="p173311421252"></a><a name="p173311421252"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row193311322514"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p63312023511"><a name="p63312023511"></a><a name="p63312023511"></a>public <a href="marker.md">Marker</a> addMarker(<a href="markeroptions.md">MarkerOptions</a> options)</p>
<p id="p1331192758"><a name="p1331192758"></a><a name="p1331192758"></a>Adds a marker to a map. The marker icon is displayed at the specified position on the map. </p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table161191428163820"></a>
<table><thead align="left"><tr id="row13830162819388"><th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.1"><p id="p148301528113817"><a name="p148301528113817"></a><a name="p148301528113817"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.2"><p id="p19830172893818"><a name="p19830172893818"></a><a name="p19830172893818"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row4830528153814"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p148307283388"><a name="p148307283388"></a><a name="p148307283388"></a>options</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p18304284386"><a name="p18304284386"></a><a name="p18304284386"></a>Attributes of a marker.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table11211428103810"></a>
<table><thead align="left"><tr id="row783042810387"><th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.1"><p id="p18301628193814"><a name="p18301628193814"></a><a name="p18301628193814"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.2"><p id="p118301728133818"><a name="p118301728133818"></a><a name="p118301728133818"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row5830128123817"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p683072823815"><a name="p683072823815"></a><a name="p683072823815"></a>Marker</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p3830132814389"><a name="p3830132814389"></a><a name="p3830132814389"></a><a href="marker.md">Marker</a> object.</p>
</td>
</tr>
</tbody>
</table>

## addPolygon<a name="section342720397412"></a>

<a name="table14305131959"></a>
<table><thead align="left"><tr id="row1271710131958"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p1371716136519"><a name="p1371716136519"></a><a name="p1371716136519"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row167171131351"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p187176131558"><a name="p187176131558"></a><a name="p187176131558"></a>public <a href="polygon.md">Polygon</a> addPolygon(<a href="polygonoptions.md">PolygonOptions</a> options)</p>
<p id="p8717151317517"><a name="p8717151317517"></a><a name="p8717151317517"></a>Adds a polygon to a map.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table51261628103812"></a>
<table><thead align="left"><tr id="row883013289381"><th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.1"><p id="p18307285388"><a name="p18307285388"></a><a name="p18307285388"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.2"><p id="p1830142819383"><a name="p1830142819383"></a><a name="p1830142819383"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row28311328163818"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p18319284382"><a name="p18319284382"></a><a name="p18319284382"></a>options</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p183116285381"><a name="p183116285381"></a><a name="p183116285381"></a>Attributes of a polygon.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table1312817282383"></a>
<table><thead align="left"><tr id="row14831428113810"><th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.1"><p id="p1783152813810"><a name="p1783152813810"></a><a name="p1783152813810"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.2"><p id="p6831728113816"><a name="p6831728113816"></a><a name="p6831728113816"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row683113288386"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p1883120287386"><a name="p1883120287386"></a><a name="p1883120287386"></a>Polygon</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p1383114285384"><a name="p1383114285384"></a><a name="p1383114285384"></a><a href="polygon.md">Polygon</a> object.</p>
</td>
</tr>
</tbody>
</table>

## addPolyline<a name="section527091714515"></a>

<a name="table79841224953"></a>
<table><thead align="left"><tr id="row15360202512514"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p113607252516"><a name="p113607252516"></a><a name="p113607252516"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row123615251558"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p33614251052"><a name="p33614251052"></a><a name="p33614251052"></a>public <a href="polyline.md">Polyline</a> addPolyline(<a href="polylineoptions.md">PolylineOptions</a> options)</p>
<p id="p1336112251051"><a name="p1336112251051"></a><a name="p1336112251051"></a>Adds a polyline to a map.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table1131728183814"></a>
<table><thead align="left"><tr id="row983192813380"><th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.1"><p id="p1383116285381"><a name="p1383116285381"></a><a name="p1383116285381"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.2"><p id="p168317280384"><a name="p168317280384"></a><a name="p168317280384"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row17831162811389"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p1383115285387"><a name="p1383115285387"></a><a name="p1383115285387"></a>options</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p12831112853817"><a name="p12831112853817"></a><a name="p12831112853817"></a>Attributes of a polyline.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table113452817387"></a>
<table><thead align="left"><tr id="row19831112893817"><th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.1"><p id="p1583111283388"><a name="p1583111283388"></a><a name="p1583111283388"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.2"><p id="p4831112817381"><a name="p4831112817381"></a><a name="p4831112817381"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row0831172810384"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p2831828133817"><a name="p2831828133817"></a><a name="p2831828133817"></a>Polyline</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p19832528113811"><a name="p19832528113811"></a><a name="p19832528113811"></a><a href="polyline.md">Polyline</a> object.</p>
</td>
</tr>
</tbody>
</table>

## addTileOverlay<a name="section12241957204519"></a>

<a name="table18301101566"></a>
<table><thead align="left"><tr id="row20983410866"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p16983810966"><a name="p16983810966"></a><a name="p16983810966"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row598312101614"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p1898316101561"><a name="p1898316101561"></a><a name="p1898316101561"></a>public <a href="tileoverlay.md">TileOverlay</a> addTileOverlay(<a href="tileoverlayoptions.md">TileOverlayOptions</a> options)</p>
<p id="p15983131019613"><a name="p15983131019613"></a><a name="p15983131019613"></a>Adds a tile overlay to a map. Note that tile overlays are different from other overlays. If you recreate a map, tile overlays on the map will be automatically discarded and you need to manually add them again.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table2137162893816"></a>
<table><thead align="left"><tr id="row6832202873815"><th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.1"><p id="p283222816384"><a name="p283222816384"></a><a name="p283222816384"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.2"><p id="p183272823810"><a name="p183272823810"></a><a name="p183272823810"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row1683211284386"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p15832162813815"><a name="p15832162813815"></a><a name="p15832162813815"></a>options</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p1383242833812"><a name="p1383242833812"></a><a name="p1383242833812"></a>Attributes of a tile overlay. <a href="tileprovider.md">TileProvider</a> must be specified. Otherwise, <strong id="b4480356202016"><a name="b4480356202016"></a><a name="b4480356202016"></a>IllegalArgumentException</strong> will be thrown.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table413916285389"></a>
<table><thead align="left"><tr id="row1883212803812"><th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.1"><p id="p108321028133813"><a name="p108321028133813"></a><a name="p108321028133813"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.2"><p id="p3832132817380"><a name="p3832132817380"></a><a name="p3832132817380"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row88322284384"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p10832182833811"><a name="p10832182833811"></a><a name="p10832182833811"></a>TileOverlay</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p1483211282388"><a name="p1483211282388"></a><a name="p1483211282388"></a><a href="tileoverlay.md">TileOverlay</a> object.</p>
</td>
</tr>
</tbody>
</table>

**Throws**

<a name="table314292863814"></a>
<table><thead align="left"><tr id="row188321628153811"><th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.1"><p id="p1483218285389"><a name="p1483218285389"></a><a name="p1483218285389"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.2"><p id="p108323283381"><a name="p108323283381"></a><a name="p108323283381"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row8832172873814"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p128326281382"><a name="p128326281382"></a><a name="p128326281382"></a>IllegalArgumentException</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p10832172813811"><a name="p10832172813811"></a><a name="p10832172813811"></a>If <a href="tileprovider.md">TileProvider</a> is not specified in the <strong id="b13584193662418"><a name="b13584193662418"></a><a name="b13584193662418"></a>options</strong> parameter.</p>
</td>
</tr>
</tbody>
</table>

## animateCamera\(CameraUpdate update\)<a name="section13382161444614"></a>

<a name="table127587245614"></a>
<table><thead align="left"><tr id="row189013241868"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p168901241062"><a name="p168901241062"></a><a name="p168901241062"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row9890162419611"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p3890112412613"><a name="p3890112412613"></a><a name="p3890112412613"></a>public void animateCamera(<a href="cameraupdate.md">CameraUpdate</a> update)</p>
<p id="p178907247615"><a name="p178907247615"></a><a name="p178907247615"></a>Updates the camera position in animation mode. If <a href="#section6273104784712">getCameraPosition</a><strong id="b16781227132011"><a name="b16781227132011"></a><a name="b16781227132011"></a>()</strong> is called during the animation, the current position of the camera will be returned. By default, the camera animation takes 250 milliseconds.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table7144132815387"></a>
<table><thead align="left"><tr id="row18833162818386"><th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.1"><p id="p8833122816388"><a name="p8833122816388"></a><a name="p8833122816388"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.2"><p id="p383312817387"><a name="p383312817387"></a><a name="p383312817387"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row883392843818"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p1833162853817"><a name="p1833162853817"></a><a name="p1833162853817"></a>update</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p5833122833813"><a name="p5833122833813"></a><a name="p5833122833813"></a>Camera position change.</p>
</td>
</tr>
</tbody>
</table>

## animateCamera\(CameraUpdate update, HuaweiMap.CancelableCallback callback\)<a name="section105931534124619"></a>

<a name="table36853451561"></a>
<table><thead align="left"><tr id="row8889194518610"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p188901451269"><a name="p188901451269"></a><a name="p188901451269"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row2089020453613"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p1889013452618"><a name="p1889013452618"></a><a name="p1889013452618"></a>public void animateCamera(<a href="cameraupdate.md">CameraUpdate</a> update, <a href="cancelablecallback.md">HuaweiMap.CancelableCallback</a> callback)</p>
<p id="p158903451665"><a name="p158903451665"></a><a name="p158903451665"></a>Updates the camera position in animation mode and calls an optional callback upon animation completion. The default animation duration is 250 milliseconds.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table214722893818"></a>
<table><thead align="left"><tr id="row583392814382"><th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.1"><p id="p983313285381"><a name="p983313285381"></a><a name="p983313285381"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.2"><p id="p783312883816"><a name="p783312883816"></a><a name="p783312883816"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row188336283386"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p19833122823811"><a name="p19833122823811"></a><a name="p19833122823811"></a>update</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p15833112853816"><a name="p15833112853816"></a><a name="p15833112853816"></a>Camera position change.</p>
</td>
</tr>
<tr id="row4833112813381"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p1483382883811"><a name="p1483382883811"></a><a name="p1483382883811"></a>callback</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p1183319288383"><a name="p1183319288383"></a><a name="p1183319288383"></a>Callback executed when the animation stops. If the animation is completed properly, <a href="cancelablecallback.md#section153541721172312">onFinish</a><strong id="b48811856162210"><a name="b48811856162210"></a><a name="b48811856162210"></a>()</strong> will be called. Otherwise, <a href="cancelablecallback.md#section1867917349161">onCancel</a><strong id="b068791182311"><a name="b068791182311"></a><a name="b068791182311"></a>()</strong> will be called.</p>
</td>
</tr>
</tbody>
</table>

## animateCamera\(CameraUpdate update, int durationMs, HuaweiMap.CancelableCallback callback\)<a name="section10235112164715"></a>

<a name="table135041131573"></a>
<table><thead align="left"><tr id="row1465619313717"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p3657193376"><a name="p3657193376"></a><a name="p3657193376"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row56571731372"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p76571931177"><a name="p76571931177"></a><a name="p76571931177"></a>public void animateCamera(<a href="cameraupdate.md">CameraUpdate</a> update, int durationMs, <a href="cancelablecallback.md">HuaweiMap.CancelableCallback</a> callback)</p>
<p id="p156571235713"><a name="p156571235713"></a><a name="p156571235713"></a>Updates the camera position in animation mode within a specified period and calls an optional callback upon animation completion.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table2151628173818"></a>
<table><thead align="left"><tr id="row683392818383"><th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.1"><p id="p78331428173812"><a name="p78331428173812"></a><a name="p78331428173812"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.2"><p id="p12833192815381"><a name="p12833192815381"></a><a name="p12833192815381"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row1283342863810"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p683372883819"><a name="p683372883819"></a><a name="p683372883819"></a>update</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p0834202873816"><a name="p0834202873816"></a><a name="p0834202873816"></a>Camera position change.</p>
</td>
</tr>
<tr id="row178341228163814"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p14834728103810"><a name="p14834728103810"></a><a name="p14834728103810"></a>durationMs</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p7834132816382"><a name="p7834132816382"></a><a name="p7834132816382"></a>Animation duration, in milliseconds. The value must be greater than 0. Otherwise, exception <strong id="b892715213515"><a name="b892715213515"></a><a name="b892715213515"></a>IllegalArgumentException</strong> will be thrown.</p>
</td>
</tr>
<tr id="row1183402820384"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p1683413289381"><a name="p1683413289381"></a><a name="p1683413289381"></a>callback</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p122391434161711"><a name="p122391434161711"></a><a name="p122391434161711"></a>Callback executed when the animation stops. If the animation is completed properly, <a href="cancelablecallback.md#section153541721172312">onFinish</a><strong id="b512591554"><a name="b512591554"></a><a name="b512591554"></a>()</strong> will be called. Otherwise, <a href="cancelablecallback.md#section1867917349161">onCancel</a><strong id="b771784214"><a name="b771784214"></a><a name="b771784214"></a>()</strong> will be called.</p>
</td>
</tr>
</tbody>
</table>

## clear<a name="section192781734134710"></a>

<a name="table494712221672"></a>
<table><thead align="left"><tr id="row17150223377"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p915019239716"><a name="p915019239716"></a><a name="p915019239716"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row61509230714"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p915112235713"><a name="p915112235713"></a><a name="p915112235713"></a>public void clear()</p>
<p id="p615116231678"><a name="p615116231678"></a><a name="p615116231678"></a>Removes all circles, markers, polylines, ground overlays, and other shapes from a map.</p>
</td>
</tr>
</tbody>
</table>

## getCameraPosition<a name="section6273104784712"></a>

<a name="table2101114215718"></a>
<table><thead align="left"><tr id="row1445716421579"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p94574424717"><a name="p94574424717"></a><a name="p94574424717"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row15457164218719"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p945719428710"><a name="p945719428710"></a><a name="p945719428710"></a>public <a href="cameraposition.md">CameraPosition</a> getCameraPosition()</p>
<p id="p545718421777"><a name="p545718421777"></a><a name="p545718421777"></a>Obtains the current position of the camera. The <a href="cameraposition.md">CameraPosition</a> object that is returned is a snapshot of the camera's current position and will not be automatically updated when the camera moves.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table18156328183812"></a>
<table><thead align="left"><tr id="row11834182820381"><th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.1"><p id="p88341628203810"><a name="p88341628203810"></a><a name="p88341628203810"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.2"><p id="p10834152893815"><a name="p10834152893815"></a><a name="p10834152893815"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row1383482893819"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p14834202818386"><a name="p14834202818386"></a><a name="p14834202818386"></a>CameraPosition</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p158341928163814"><a name="p158341928163814"></a><a name="p158341928163814"></a><a href="cameraposition.md">CameraPosition</a> object, which returns the current position of the camera.</p>
</td>
</tr>
</tbody>
</table>

## getMapType<a name="section182805611495"></a>

<a name="table51893521679"></a>
<table><thead align="left"><tr id="row677510529712"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p27750521075"><a name="p27750521075"></a><a name="p27750521075"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row1977515521078"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p577616521375"><a name="p577616521375"></a><a name="p577616521375"></a>public int getMapType()</p>
<p id="p77761552773"><a name="p77761552773"></a><a name="p77761552773"></a>Obtains the current map type. The value <strong id="b132506262169"><a name="b132506262169"></a><a name="b132506262169"></a>-1</strong> indicates that the map type is not specified. </p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table8159192813382"></a>
<table><thead align="left"><tr id="row68344289383"><th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.1"><p id="p58342289380"><a name="p58342289380"></a><a name="p58342289380"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.2"><p id="p13834132814386"><a name="p13834132814386"></a><a name="p13834132814386"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row12835112814386"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p108358288383"><a name="p108358288383"></a><a name="p108358288383"></a>int</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><a name="ul129073425418"></a><a name="ul129073425418"></a><ul id="ul129073425418"><li><strong id="b097673021819"><a name="b097673021819"></a><a name="b097673021819"></a>-1</strong>: not specified</li><li><strong id="b1695522012254"><a name="b1695522012254"></a><a name="b1695522012254"></a>0</strong>: empty map</li><li><strong id="b159531227192518"><a name="b159531227192518"></a><a name="b159531227192518"></a>1</strong>: basic map</li><li><strong id="b167721958152513"><a name="b167721958152513"></a><a name="b167721958152513"></a>2</strong>: satellite map without markers</li><li><strong id="b107441513142616"><a name="b107441513142616"></a><a name="b107441513142616"></a>3</strong>: terrain map</li><li><strong id="b1718032317272"><a name="b1718032317272"></a><a name="b1718032317272"></a>4</strong>: satellite map with a transparent layer of main streets</li></ul>
</td>
</tr>
</tbody>
</table>

## getMaxZoomLevel<a name="section10176115075312"></a>

<a name="table48959178814"></a>
<table><thead align="left"><tr id="row62612181181"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p4262181886"><a name="p4262181886"></a><a name="p4262181886"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row5261918887"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p3262181810"><a name="p3262181810"></a><a name="p3262181810"></a>public float getMaxZoomLevel()</p>
<p id="p13271181387"><a name="p13271181387"></a><a name="p13271181387"></a>Obtains the maximum zoom level of the map camera.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table1116213285384"></a>
<table><thead align="left"><tr id="row283592843813"><th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.1"><p id="p283562853810"><a name="p283562853810"></a><a name="p283562853810"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.2"><p id="p18835122811386"><a name="p18835122811386"></a><a name="p18835122811386"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row1483532893811"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p1583502812380"><a name="p1583502812380"></a><a name="p1583502812380"></a>float</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p17835182803817"><a name="p17835182803817"></a><a name="p17835182803817"></a>Maximum zoom level of the map camera, which is constant <strong id="b113464313498"><a name="b113464313498"></a><a name="b113464313498"></a>20</strong>. </p>
</td>
</tr>
</tbody>
</table>

## getMinZoomLevel<a name="section15491181135412"></a>

<a name="table186041626981"></a>
<table><thead align="left"><tr id="row27351266813"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p97356264820"><a name="p97356264820"></a><a name="p97356264820"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row773617265818"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p157361926483"><a name="p157361926483"></a><a name="p157361926483"></a>public float getMinZoomLevel()</p>
<p id="p973632618817"><a name="p973632618817"></a><a name="p973632618817"></a>Obtains the minimum zoom level of the map camera.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table1716632843815"></a>
<table><thead align="left"><tr id="row168351128163811"><th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.1"><p id="p5835202819389"><a name="p5835202819389"></a><a name="p5835202819389"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.2"><p id="p5835142810389"><a name="p5835142810389"></a><a name="p5835142810389"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row28351228133818"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p5835192863813"><a name="p5835192863813"></a><a name="p5835192863813"></a>float</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p7835132843813"><a name="p7835132843813"></a><a name="p7835132843813"></a>Minimum zoom level of the map camera, which is constant <strong id="b1329012112501"><a name="b1329012112501"></a><a name="b1329012112501"></a>3</strong>. </p>
</td>
</tr>
</tbody>
</table>

## getProjection<a name="section10118629175416"></a>

<a name="table12622940180"></a>
<table><thead align="left"><tr id="row1077420405810"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p1774134017819"><a name="p1774134017819"></a><a name="p1774134017819"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row77745401682"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p147741240484"><a name="p147741240484"></a><a name="p147741240484"></a>public <a href="projection.md">Projection</a> getProjection()</p>
<p id="p8775840181"><a name="p8775840181"></a><a name="p8775840181"></a>Obtains a <a href="projection.md">Projection</a> object that can be used to convert between the pixel coordinates on the screen and the longitude/latitude coordinates on the map.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table11168162853812"></a>
<table><thead align="left"><tr id="row1183532813810"><th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.1"><p id="p3835132873815"><a name="p3835132873815"></a><a name="p3835132873815"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.2"><p id="p983522813812"><a name="p983522813812"></a><a name="p983522813812"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row183572833814"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p983652818389"><a name="p983652818389"></a><a name="p983652818389"></a>Projection</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p983610283385"><a name="p983610283385"></a><a name="p983610283385"></a><a href="projection.md">Projection</a> object.</p>
</td>
</tr>
</tbody>
</table>

## getUiSettings<a name="section86721421145920"></a>

<a name="table158411541884"></a>
<table><thead align="left"><tr id="row1299818544812"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p199988542815"><a name="p199988542815"></a><a name="p199988542815"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row699815413815"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p16998154283"><a name="p16998154283"></a><a name="p16998154283"></a>public <a href="uisettings.md">UiSettings</a> getUiSettings()</p>
<p id="p799885410815"><a name="p799885410815"></a><a name="p799885410815"></a>Obtains the UI and gesture controls of a map, which can determine whether to display the built-in UI (such as zoom buttons and compass) and whether to enable certain gestures such as scroll and zoom gestures.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table19171182843815"></a>
<table><thead align="left"><tr id="row138361528193818"><th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.1"><p id="p68361428173819"><a name="p68361428173819"></a><a name="p68361428173819"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.2"><p id="p9836152811387"><a name="p9836152811387"></a><a name="p9836152811387"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row9836142823815"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p183612811385"><a name="p183612811385"></a><a name="p183612811385"></a>UiSettings</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p183613289389"><a name="p183613289389"></a><a name="p183613289389"></a><a href="uisettings.md">UiSettings</a> object.</p>
</td>
</tr>
</tbody>
</table>

## isBuildingsEnabled<a name="section12710113985913"></a>

<a name="table292218117916"></a>
<table><thead align="left"><tr id="row331513121918"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p03169125910"><a name="p03169125910"></a><a name="p03169125910"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row1131615124918"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p1631712121794"><a name="p1631712121794"></a><a name="p1631712121794"></a>public boolean isBuildingsEnabled()</p>
<p id="p8317012497"><a name="p8317012497"></a><a name="p8317012497"></a>Checks whether the 3D building layer is enabled for a map.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table7174112873817"></a>
<table><thead align="left"><tr id="row198365285384"><th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.1"><p id="p1383632833814"><a name="p1383632833814"></a><a name="p1383632833814"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.2"><p id="p1683642812385"><a name="p1683642812385"></a><a name="p1683642812385"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row5836628103816"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p1583613284384"><a name="p1583613284384"></a><a name="p1583613284384"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p2836828123814"><a name="p2836828123814"></a><a name="p2836828123814"></a><strong id="b489382052813"><a name="b489382052813"></a><a name="b489382052813"></a>true</strong> if the 3D building layer is enabled; <strong id="b295535512710"><a name="b295535512710"></a><a name="b295535512710"></a>false</strong> otherwise. The default value is <strong id="b22915534423"><a name="b22915534423"></a><a name="b22915534423"></a>true</strong>.</p>
</td>
</tr>
</tbody>
</table>

## isMyLocationEnabled<a name="section1749445113591"></a>

<a name="table4346182716913"></a>
<table><thead align="left"><tr id="row196561227590"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p665772715911"><a name="p665772715911"></a><a name="p665772715911"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row8657172718912"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p1365718275913"><a name="p1365718275913"></a><a name="p1365718275913"></a>public boolean isMyLocationEnabled()</p>
<p id="p196570271691"><a name="p196570271691"></a><a name="p196570271691"></a>Checks whether the my-location layer is enabled for a map.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table141771128143815"></a>
<table><thead align="left"><tr id="row10837162819386"><th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.1"><p id="p1383742817383"><a name="p1383742817383"></a><a name="p1383742817383"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.2"><p id="p1983718289382"><a name="p1983718289382"></a><a name="p1983718289382"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row1483718286388"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p1183719284385"><a name="p1183719284385"></a><a name="p1183719284385"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p8837328183819"><a name="p8837328183819"></a><a name="p8837328183819"></a><strong id="b15561123472814"><a name="b15561123472814"></a><a name="b15561123472814"></a>true</strong> if the my-location layer is enabled; <strong id="b628042311285"><a name="b628042311285"></a><a name="b628042311285"></a>false</strong> otherwise. The default value is <strong id="b145192413432"><a name="b145192413432"></a><a name="b145192413432"></a>false</strong>.</p>
</td>
</tr>
</tbody>
</table>

## isTrafficEnabled<a name="section4431113205518"></a>

<a name="table15432141316551"></a>
<table><thead align="left"><tr id="row74321713155515"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p6432121375514"><a name="p6432121375514"></a><a name="p6432121375514"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row1243251320552"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p1432151385520"><a name="p1432151385520"></a><a name="p1432151385520"></a>public boolean isTrafficEnabled()</p>
<p id="p1432151311554"><a name="p1432151311554"></a><a name="p1432151311554"></a>Checks whether the traffic status layer is enabled. </p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table1443391345516"></a>
<table><thead align="left"><tr id="row24341413115516"><th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.1"><p id="p94341813195512"><a name="p94341813195512"></a><a name="p94341813195512"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.2"><p id="p1843415133555"><a name="p1843415133555"></a><a name="p1843415133555"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row20434121314551"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p1143411315519"><a name="p1143411315519"></a><a name="p1143411315519"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p54347132554"><a name="p54347132554"></a><a name="p54347132554"></a><strong id="b2832319411"><a name="b2832319411"></a><a name="b2832319411"></a>true</strong> if the traffic status layer is enabled; <strong id="b537442720498"><a name="b537442720498"></a><a name="b537442720498"></a>false</strong> otherwise. The default value is <strong id="b8629337174312"><a name="b8629337174312"></a><a name="b8629337174312"></a>false</strong>.</p>
</td>
</tr>
</tbody>
</table>

## moveCamera<a name="section168451531308"></a>

<a name="table1111514368918"></a>
<table><thead align="left"><tr id="row142674361392"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p1268336497"><a name="p1268336497"></a><a name="p1268336497"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row726811363913"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p1426817361698"><a name="p1426817361698"></a><a name="p1426817361698"></a>public void moveCamera(<a href="cameraupdate.md">CameraUpdate</a> update)</p>
<p id="p112681536290"><a name="p112681536290"></a><a name="p112681536290"></a>Updates the camera position. The movement is instantaneous. If <a href="#section6273104784712">getCameraPosition</a><strong id="b3726437102211"><a name="b3726437102211"></a><a name="b3726437102211"></a>()</strong> is called later, the camera will be moved to the new position. </p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table617942820383"></a>
<table><thead align="left"><tr id="row58371928183815"><th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.1"><p id="p58379286381"><a name="p58379286381"></a><a name="p58379286381"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.2"><p id="p7837172811383"><a name="p7837172811383"></a><a name="p7837172811383"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row19837142815387"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p883792833812"><a name="p883792833812"></a><a name="p883792833812"></a>update</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p1583792803820"><a name="p1583792803820"></a><a name="p1583792803820"></a>Camera position change.</p>
</td>
</tr>
</tbody>
</table>

## resetMinMaxZoomPreference<a name="section430911571905"></a>

<a name="table18978132914104"></a>
<table><thead align="left"><tr id="row115273051010"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p81525307103"><a name="p81525307103"></a><a name="p81525307103"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row7152113091013"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p215213015109"><a name="p215213015109"></a><a name="p215213015109"></a>public void resetMinMaxZoomPreference()</p>
<p id="p71531630161017"><a name="p71531630161017"></a><a name="p71531630161017"></a>Deletes all maximum and minimum zoom levels set previously.</p>
</td>
</tr>
</tbody>
</table>

## setBuildingsEnabled<a name="section1956116323019"></a>

<a name="table39710164102"></a>
<table><thead align="left"><tr id="row7265111631015"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p92651516181015"><a name="p92651516181015"></a><a name="p92651516181015"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row152657160101"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p13265101691010"><a name="p13265101691010"></a><a name="p13265101691010"></a>public void setBuildingsEnabled(boolean enabled)</p>
<p id="p32655166107"><a name="p32655166107"></a><a name="p32655166107"></a>Sets whether to enable the 3D building layer.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table9182102863812"></a>
<table><thead align="left"><tr id="row15837628103811"><th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.1"><p id="p13837428203813"><a name="p13837428203813"></a><a name="p13837428203813"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.2"><p id="p9837728183820"><a name="p9837728183820"></a><a name="p9837728183820"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row88374283380"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p108373287387"><a name="p108373287387"></a><a name="p108373287387"></a>enabled</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p2837128203814"><a name="p2837128203814"></a><a name="p2837128203814"></a>Indicates whether to enable the 3D building layer. <strong id="b206785551289"><a name="b206785551289"></a><a name="b206785551289"></a>true</strong>: yes; <strong id="b668415516281"><a name="b668415516281"></a><a name="b668415516281"></a>false</strong>: no.</p>
</td>
</tr>
</tbody>
</table>

## setContentDescription<a name="section123781718617"></a>

<a name="table82531043151011"></a>
<table><thead align="left"><tr id="row24401643111020"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p13440104313102"><a name="p13440104313102"></a><a name="p13440104313102"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row74401543161016"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p544034321011"><a name="p544034321011"></a><a name="p544034321011"></a>public void setContentDescription(String description)</p>
<p id="p1415105553912"><a name="p1415105553912"></a><a name="p1415105553912"></a>Adds content description to a map. If the auxiliary mode is enabled, voice description about the map will be provided.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table131851128203810"></a>
<table><thead align="left"><tr id="row20838122833815"><th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.1"><p id="p1883822833812"><a name="p1883822833812"></a><a name="p1883822833812"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.2"><p id="p148381288387"><a name="p148381288387"></a><a name="p148381288387"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row1483862813813"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p58381285384"><a name="p58381285384"></a><a name="p58381285384"></a>description</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p1683802812381"><a name="p1683802812381"></a><a name="p1683802812381"></a>Voice description about the map.</p>
</td>
</tr>
</tbody>
</table>

## setInfoWindowAdapter<a name="section696710332112"></a>

<a name="table1151575651013"></a>
<table><thead align="left"><tr id="row968135621011"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p11681556141013"><a name="p11681556141013"></a><a name="p11681556141013"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row2681175621010"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p1681156131015"><a name="p1681156131015"></a><a name="p1681156131015"></a>public void setInfoWindowAdapter(<a href="infowindowadapter.md">HuaweiMap.InfoWindowAdapter</a> adapter)</p>
<p id="p116811256161011"><a name="p116811256161011"></a><a name="p116811256161011"></a>Sets a custom adapter for the content of an information window. The adaptation state will not persist, similar to a state obtained by a map event listener. If a map is recreated (for example, the configuration is modified), you must call this method again to preserve the custom information window view.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table1018862883814"></a>
<table><thead align="left"><tr id="row5838132883819"><th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.1"><p id="p683816287383"><a name="p683816287383"></a><a name="p683816287383"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.2"><p id="p1383812280387"><a name="p1383812280387"></a><a name="p1383812280387"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row6838182893815"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p48381289384"><a name="p48381289384"></a><a name="p48381289384"></a>adapter</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p1583816285389"><a name="p1583816285389"></a><a name="p1583816285389"></a>Custom information window view adapter.</p>
</td>
</tr>
</tbody>
</table>

## setLatLngBoundsForCameraTarget<a name="section11439194715114"></a>

<a name="table836839171116"></a>
<table><thead align="left"><tr id="row557911911119"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p11579399113"><a name="p11579399113"></a><a name="p11579399113"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row165792951112"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p657919921110"><a name="p657919921110"></a><a name="p657919921110"></a>public void setLatLngBoundsForCameraTarget(<a href="latlngbounds.md">LatLngBounds</a> bounds)</p>
<p id="p657999101117"><a name="p657999101117"></a><a name="p657999101117"></a>Sets a <a href="latlngbounds.md">LatLngBounds</a> object to constrain the camera target so that the camera target does not move outside the bounds when a user scrolls the map. If this parameter is set to <strong id="b136731618104519"><a name="b136731618104519"></a><a name="b136731618104519"></a>null</strong>, the map camera bounds will be cleared.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table121901728113818"></a>
<table><thead align="left"><tr id="row183815282386"><th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.1"><p id="p8838122815386"><a name="p8838122815386"></a><a name="p8838122815386"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.2"><p id="p2083832893817"><a name="p2083832893817"></a><a name="p2083832893817"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row38381828123818"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p1283814280380"><a name="p1283814280380"></a><a name="p1283814280380"></a>bounds</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p5838728163810"><a name="p5838728163810"></a><a name="p5838728163810"></a>Bounds for constraining the camera target.</p>
</td>
</tr>
</tbody>
</table>

## setLocationSource<a name="section1664916820220"></a>

<a name="table17765272116"></a>
<table><thead align="left"><tr id="row1543762710117"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p54377271118"><a name="p54377271118"></a><a name="p54377271118"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row124371270118"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p1043832714119"><a name="p1043832714119"></a><a name="p1043832714119"></a>public void setLocationSource(<a href="locationsource.md">LocationSource</a> locationSource)</p>
<p id="p15438172710111"><a name="p15438172710111"></a><a name="p15438172710111"></a>Sets the location source for the my-location layer.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table171931928153811"></a>
<table><thead align="left"><tr id="row483916284383"><th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.1"><p id="p128394285389"><a name="p128394285389"></a><a name="p128394285389"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.2"><p id="p1483992823814"><a name="p1483992823814"></a><a name="p1483992823814"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row1983913285381"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p983911285381"><a name="p983911285381"></a><a name="p983911285381"></a>locationSource</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p1383912803811"><a name="p1383912803811"></a><a name="p1383912803811"></a>Location source. If this parameter is set to <strong id="b3924183552919"><a name="b3924183552919"></a><a name="b3924183552919"></a>null</strong>, the default location source will be used.</p>
</td>
</tr>
</tbody>
</table>

## setMapStyle<a name="section172547271522"></a>

<a name="table1045144010115"></a>
<table><thead align="left"><tr id="row13631134018112"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p12631640121111"><a name="p12631640121111"></a><a name="p12631640121111"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row863144017112"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p063174031119"><a name="p063174031119"></a><a name="p063174031119"></a>public boolean setMapStyle(<a href="mapstyleoptions.md">MapStyleOptions</a> option)</p>
<p id="p9631144016111"><a name="p9631144016111"></a><a name="p9631144016111"></a>Sets the map style. If <strong id="b35958273508"><a name="b35958273508"></a><a name="b35958273508"></a>null</strong> is passed, all custom map styles set previously will be cleared. </p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table15197228183816"></a>
<table><thead align="left"><tr id="row1483912283385"><th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.1"><p id="p483916289389"><a name="p483916289389"></a><a name="p483916289389"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.2"><p id="p118394283384"><a name="p118394283384"></a><a name="p118394283384"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row1183982853814"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p15839122823810"><a name="p15839122823810"></a><a name="p15839122823810"></a>option</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p1083918287381"><a name="p1083918287381"></a><a name="p1083918287381"></a>Map style attribute settings.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table111994286384"></a>
<table><thead align="left"><tr id="row68392028113813"><th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.1"><p id="p98391728133814"><a name="p98391728133814"></a><a name="p98391728133814"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.2"><p id="p1683992863815"><a name="p1683992863815"></a><a name="p1683992863815"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row4839192812383"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p16839428103814"><a name="p16839428103814"></a><a name="p16839428103814"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p108390287385"><a name="p108390287385"></a><a name="p108390287385"></a><strong id="b1756161223013"><a name="b1756161223013"></a><a name="b1756161223013"></a>true</strong> if the map style is set successfully; <strong id="b1148165862911"><a name="b1148165862911"></a><a name="b1148165862911"></a>false</strong> otherwise. For example, if the JSON string fails to be parsed, the feature or element type cannot be recognized, or the style key is invalid, the map style fails to be set, and <strong id="b171498588295"><a name="b171498588295"></a><a name="b171498588295"></a>false</strong> is returned. In this case, the current style remains unchanged.</p>
</td>
</tr>
</tbody>
</table>

## setMapType<a name="section3746134811217"></a>

<a name="table191713101210"></a>
<table><thead align="left"><tr id="row2021371101214"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p192148119124"><a name="p192148119124"></a><a name="p192148119124"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row121412110124"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p1321414112127"><a name="p1321414112127"></a><a name="p1321414112127"></a>public void setMapType(int mapType)</p>
<p id="p1421417141214"><a name="p1421417141214"></a><a name="p1421417141214"></a>Sets the map type. If the map type is not specified, the standard map type will be used by default.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table22032028203818"></a>
<table><thead align="left"><tr id="row108391528203813"><th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.1"><p id="p13839182819382"><a name="p13839182819382"></a><a name="p13839182819382"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.2"><p id="p19839728153816"><a name="p19839728153816"></a><a name="p19839728153816"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row38401228193817"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p384092813810"><a name="p384092813810"></a><a name="p384092813810"></a>mapType</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p38191719809"><a name="p38191719809"></a><a name="p38191719809"></a>Map type. The options are as follows:</p>
<a name="ul540519541400"></a><a name="ul540519541400"></a><ul id="ul540519541400"><li><strong id="b16019536502"><a name="b16019536502"></a><a name="b16019536502"></a>0</strong>: empty map</li><li><strong id="b947811569502"><a name="b947811569502"></a><a name="b947811569502"></a>1</strong>: basic map</li><li><strong id="b755210605115"><a name="b755210605115"></a><a name="b755210605115"></a>2</strong>: satellite map without markers (not supported currently)</li><li><strong id="b4249133555110"><a name="b4249133555110"></a><a name="b4249133555110"></a>3</strong>: terrain map (not supported currently)</li><li><strong id="b1173494145112"><a name="b1173494145112"></a><a name="b1173494145112"></a>4</strong>: satellite map with a transparent layer of main streets (not supported currently)</li></ul>
</td>
</tr>
</tbody>
</table>

## setMarkersClustering<a name="section02341839699"></a>

<a name="table1224110106212"></a>
<table><thead align="left"><tr id="row2456141016213"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p1445631032111"><a name="p1445631032111"></a><a name="p1445631032111"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row045717107218"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p045711042111"><a name="p045711042111"></a><a name="p045711042111"></a>public void setMarkersClustering(boolean isMarkersClustering)</p>
<p id="p7457121015215"><a name="p7457121015215"></a><a name="p7457121015215"></a>Sets whether to cluster markers.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table7264132815387"></a>
<table><thead align="left"><tr id="row085092893817"><th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.1"><p id="p12850122843819"><a name="p12850122843819"></a><a name="p12850122843819"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.2"><p id="p78501828133816"><a name="p78501828133816"></a><a name="p78501828133816"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row19850928133810"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p58501228153813"><a name="p58501228153813"></a><a name="p58501228153813"></a>isMarkersClustering</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p1385052873819"><a name="p1385052873819"></a><a name="p1385052873819"></a>Indicates whether a marker can be clustered. <strong id="b3951122654115"><a name="b3951122654115"></a><a name="b3951122654115"></a>true</strong>: yes; <strong id="b17929132911417"><a name="b17929132911417"></a><a name="b17929132911417"></a>false</strong> (default): no.</p>
</td>
</tr>
</tbody>
</table>

## setMaxZoomPreference<a name="section793718196316"></a>

<a name="table12562101912125"></a>
<table><thead align="left"><tr id="row3734131916129"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p37341319131213"><a name="p37341319131213"></a><a name="p37341319131213"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row7734131911216"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p673481941211"><a name="p673481941211"></a><a name="p673481941211"></a>public void setMaxZoomPreference(float maxZoom)</p>
<p id="p11734151921214"><a name="p11734151921214"></a><a name="p11734151921214"></a>Sets the preferred maximum zoom level of the camera. If the preferred maximum zoom level is lower than the current minimum zoom level, the SDK uses the preferred maximum zoom level as both the minimum and maximum zoom levels. Assume that the current minimum and maximum zoom levels are 6 and 15, respectively. If you set the preferred maximum zoom level to 4, the SDK uses the value <strong id="b3351164813523"><a name="b3351164813523"></a><a name="b3351164813523"></a>4</strong> as both the minimum and maximum zoom levels. That is, the zoom level of the camera is fixed at 4.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table8206112873816"></a>
<table><thead align="left"><tr id="row88401428103818"><th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.1"><p id="p6840132818388"><a name="p6840132818388"></a><a name="p6840132818388"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.2"><p id="p784010282389"><a name="p784010282389"></a><a name="p784010282389"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row188401428123814"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p158402287385"><a name="p158402287385"></a><a name="p158402287385"></a>maxZoom</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p1184012873819"><a name="p1184012873819"></a><a name="p1184012873819"></a>Preferred maximum zoom level of the camera. The value ranges from 3 to 20. </p>
</td>
</tr>
</tbody>
</table>

## setMinZoomPreference<a name="section21610342315"></a>

<a name="table1364113219128"></a>
<table><thead align="left"><tr id="row6871173221211"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p887123218126"><a name="p887123218126"></a><a name="p887123218126"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row6871432111214"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p208714327121"><a name="p208714327121"></a><a name="p208714327121"></a>public void setMinZoomPreference(float minZoom)</p>
<p id="p78711321129"><a name="p78711321129"></a><a name="p78711321129"></a>Sets the preferred minimum zoom level of the camera. The value must be greater than or equal to the minimum zoom level (3) supported by the Map SDK. If the preferred minimum zoom level is higher than the current maximum zoom level, the SDK uses the preferred minimum zoom level as both the minimum and maximum zoom levels. Assume that the current minimum and maximum zoom levels are 4 and 10, respectively. If you set the preferred minimum zoom level to 15, the SDK uses the value <strong id="b35282004412"><a name="b35282004412"></a><a name="b35282004412"></a>15</strong> as both the minimum and maximum zoom levels. That is, the zoom level of the camera is fixed at 15.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table5208122863810"></a>
<table><thead align="left"><tr id="row128401828103811"><th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.1"><p id="p38401728203814"><a name="p38401728203814"></a><a name="p38401728203814"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.2"><p id="p18403288386"><a name="p18403288386"></a><a name="p18403288386"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row7840182803816"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p38401728103818"><a name="p38401728103818"></a><a name="p38401728103818"></a>minZoom</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p178401428103814"><a name="p178401428103814"></a><a name="p178401428103814"></a>Preferred minimum zoom level of the camera. The value ranges from 3 to 20. </p>
</td>
</tr>
</tbody>
</table>

## setMyLocationEnabled<a name="section672514559310"></a>

<a name="table188820508127"></a>
<table><thead align="left"><tr id="row151382051111210"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p161382513128"><a name="p161382513128"></a><a name="p161382513128"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row1713911511126"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p913905114126"><a name="p913905114126"></a><a name="p913905114126"></a>public void setMyLocationEnabled(boolean myLocationEnabled)</p>
<p id="p31399516123"><a name="p31399516123"></a><a name="p31399516123"></a>Sets whether to enable the my-location layer. If the my-location layer is enabled and the location is available, the layer constantly draws the user's current location and bearing and displays the UI controls for the user to interact with their location (for example, to enable or disable the camera to track their location and bearing). To use the my-location layer function, you must apply for the <strong id="b4434143415520"><a name="b4434143415520"></a><a name="b4434143415520"></a>ACCESS_COARSE_LOCATION</strong> or <strong id="b244823416514"><a name="b244823416514"></a><a name="b244823416514"></a>ACCESS_FINE_LOCATION</strong> permission unless you have set a custom location source. If you have set a custom location source using <a href="#section1664916820220">setLocationSource</a><strong id="b1917544900"><a name="b1917544900"></a><a name="b1917544900"></a>(</strong><a href="locationsource.md">LocationSource</a><strong id="b1136212462001"><a name="b1136212462001"></a><a name="b1136212462001"></a>)</strong>, the Map SDK will not check whether the preceding permissions have been granted. However, you must ensure that the user has granted all permissions required for the custom location source.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table721012286388"></a>
<table><thead align="left"><tr id="row884072814385"><th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.1"><p id="p138408281382"><a name="p138408281382"></a><a name="p138408281382"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.2"><p id="p1884032813388"><a name="p1884032813388"></a><a name="p1884032813388"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row38413286389"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p2084116280381"><a name="p2084116280381"></a><a name="p2084116280381"></a>myLocationEnabled</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p884115287385"><a name="p884115287385"></a><a name="p884115287385"></a><strong id="b589210258340"><a name="b589210258340"></a><a name="b589210258340"></a>true</strong>: enable; <strong id="b148931025103412"><a name="b148931025103412"></a><a name="b148931025103412"></a>false</strong>: disable.</p>
</td>
</tr>
</tbody>
</table>

**Throws**

<a name="table9213132803812"></a>
<table><thead align="left"><tr id="row18411928153815"><th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.1"><p id="p138411128163812"><a name="p138411128163812"></a><a name="p138411128163812"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.2"><p id="p18841628163813"><a name="p18841628163813"></a><a name="p18841628163813"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row16841828113814"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p1584182853814"><a name="p1584182853814"></a><a name="p1584182853814"></a>SecurityException</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p584119286383"><a name="p584119286383"></a><a name="p584119286383"></a>If the location permission is not granted.</p>
</td>
</tr>
</tbody>
</table>

## setOnCameraIdleListener<a name="section77951391549"></a>

<a name="table932615616139"></a>
<table><thead align="left"><tr id="row1350712681310"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p175071163131"><a name="p175071163131"></a><a name="p175071163131"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row5507765131"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p1950714617133"><a name="p1950714617133"></a><a name="p1950714617133"></a>public void setOnCameraIdleListener(<a href="oncameraidlelistener.md">HuaweiMap.OnCameraIdleListener</a> listener)</p>
<p id="p11508964130"><a name="p11508964130"></a><a name="p11508964130"></a>Sets a listener to listen for the end of camera movement.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table13215328113820"></a>
<table><thead align="left"><tr id="row18841128163813"><th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.1"><p id="p15841428193810"><a name="p15841428193810"></a><a name="p15841428193810"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.2"><p id="p984117285382"><a name="p984117285382"></a><a name="p984117285382"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row68418287389"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p198411128103814"><a name="p198411128103814"></a><a name="p198411128103814"></a>listener</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p1841628113817"><a name="p1841628113817"></a><a name="p1841628113817"></a>Listener used to listen for the end of camera movement.</p>
</td>
</tr>
</tbody>
</table>

## setOnCameraMoveCanceledListener<a name="section5860828845"></a>

<a name="table12978132791313"></a>
<table><thead align="left"><tr id="row319092851315"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p1019019288131"><a name="p1019019288131"></a><a name="p1019019288131"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row20190328171311"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p6190228141316"><a name="p6190228141316"></a><a name="p6190228141316"></a>public void setOnCameraMoveCanceledListener(<a href="oncameramovecanceiedlistener.md">HuaweiMap.OnCameraMoveCanceledListener</a> listener)</p>
<p id="p161901128161316"><a name="p161901128161316"></a><a name="p161901128161316"></a>Sets a listener to listen for the stop of camera movement or the interruption of camera movement due to a new animation.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table92179283387"></a>
<table><thead align="left"><tr id="row1784112813385"><th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.1"><p id="p8841028153813"><a name="p8841028153813"></a><a name="p8841028153813"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.2"><p id="p14841182820383"><a name="p14841182820383"></a><a name="p14841182820383"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row20841142863812"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p184182853817"><a name="p184182853817"></a><a name="p184182853817"></a>listener</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p14841102813817"><a name="p14841102813817"></a><a name="p14841102813817"></a>Listener used to listen for the stop of camera movement or the interruption of camera movement due to a new animation.</p>
</td>
</tr>
</tbody>
</table>

## setOnCameraMoveListener<a name="section166063431548"></a>

<a name="table1740510441135"></a>
<table><thead align="left"><tr id="row38557446132"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p19855644141310"><a name="p19855644141310"></a><a name="p19855644141310"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row1585514442133"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p48550447132"><a name="p48550447132"></a><a name="p48550447132"></a>public void setOnCameraMoveListener(final <a href="oncameramovelistener.md">HuaweiMap.OnCameraMoveListener</a> listener)</p>
<p id="p18855444171316"><a name="p18855444171316"></a><a name="p18855444171316"></a>Sets a listener that is repeatedly called when the camera moves. The listener may be called once per frame. Therefore, do not perform high-consumption operations.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table1220112814381"></a>
<table><thead align="left"><tr id="row8842328143815"><th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.1"><p id="p16842122812383"><a name="p16842122812383"></a><a name="p16842122812383"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.2"><p id="p1484282810385"><a name="p1484282810385"></a><a name="p1484282810385"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row88421028113814"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p384217284380"><a name="p384217284380"></a><a name="p384217284380"></a>listener</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p484212817383"><a name="p484212817383"></a><a name="p484212817383"></a>Listener used to listen for camera movement.</p>
</td>
</tr>
</tbody>
</table>

## setOnCameraMoveStartedListener<a name="section1555059847"></a>

<a name="table640911014144"></a>
<table><thead align="left"><tr id="row147743018143"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p107741301144"><a name="p107741301144"></a><a name="p107741301144"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row137748013148"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p1177510141415"><a name="p1177510141415"></a><a name="p1177510141415"></a>public void setOnCameraMoveStartedListener(<a href="oncameramovestartedlistener.md">HuaweiMap.OnCameraMoveStartedListener</a> listener)</p>
<p id="p577520161412"><a name="p577520161412"></a><a name="p577520161412"></a>Sets a listener to listen for the beginning of camera movement or changes of the camera movement reason.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table17222828203816"></a>
<table><thead align="left"><tr id="row88421328113817"><th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.1"><p id="p208421428173810"><a name="p208421428173810"></a><a name="p208421428173810"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.2"><p id="p984211283385"><a name="p984211283385"></a><a name="p984211283385"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row2842132817386"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p118425286383"><a name="p118425286383"></a><a name="p118425286383"></a>listener</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p158421128193818"><a name="p158421128193818"></a><a name="p158421128193818"></a>Listener used to listen for the beginning of camera movement or changes of the camera movement reason.</p>
</td>
</tr>
</tbody>
</table>

## setOnCircleClickListener<a name="section185329145511"></a>

<a name="table11555181751417"></a>
<table><thead align="left"><tr id="row47671517181412"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p0767171718141"><a name="p0767171718141"></a><a name="p0767171718141"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row1576781791416"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p197671717101410"><a name="p197671717101410"></a><a name="p197671717101410"></a>public void setOnCircleClickListener(<a href="oncircleclicklistener.md">HuaweiMap.OnCircleClickListener</a> listener)</p>
<p id="p1976761751419"><a name="p1976761751419"></a><a name="p1976761751419"></a>Sets a listener to listen for tap events of a circle.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table92241028143819"></a>
<table><thead align="left"><tr id="row684252815384"><th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.1"><p id="p684282883816"><a name="p684282883816"></a><a name="p684282883816"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.2"><p id="p5842628193813"><a name="p5842628193813"></a><a name="p5842628193813"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row1184252893817"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p1184292833813"><a name="p1184292833813"></a><a name="p1184292833813"></a>listener</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p16842112818384"><a name="p16842112818384"></a><a name="p16842112818384"></a>Listener used to listen for the circle tap event.</p>
</td>
</tr>
</tbody>
</table>

## setOnGroundOverlayClickListener<a name="section48222916516"></a>

<a name="table1996732151420"></a>
<table><thead align="left"><tr id="row1127717320149"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p14277183211411"><a name="p14277183211411"></a><a name="p14277183211411"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row11277173217146"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p1527717326144"><a name="p1527717326144"></a><a name="p1527717326144"></a>public void setOnGroundOverlayClickListener(<a href="ongroundoverlayclicklistener.md">HuaweiMap.OnGroundOverlayClickListener</a> listener)</p>
<p id="p182771325140"><a name="p182771325140"></a><a name="p182771325140"></a>Sets a listener to listen for tap events of a ground overlay.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table16226128133813"></a>
<table><thead align="left"><tr id="row38432288389"><th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.1"><p id="p684312843814"><a name="p684312843814"></a><a name="p684312843814"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.2"><p id="p13843628143812"><a name="p13843628143812"></a><a name="p13843628143812"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row1484317289389"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p5843142823815"><a name="p5843142823815"></a><a name="p5843142823815"></a>listener</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p384382823814"><a name="p384382823814"></a><a name="p384382823814"></a>Listener used to listen for the ground overlay tap event.</p>
</td>
</tr>
</tbody>
</table>

## setOnInfoWindowClickListener<a name="section14758114215513"></a>

<a name="table1161617478146"></a>
<table><thead align="left"><tr id="row187976472143"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p679794721417"><a name="p679794721417"></a><a name="p679794721417"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row18797154771411"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p879814473146"><a name="p879814473146"></a><a name="p879814473146"></a>public void setOnInfoWindowClickListener(<a href="oninfowindowclicklistener.md">HuaweiMap.OnInfoWindowClickListener</a> listener)</p>
<p id="p1779819477141"><a name="p1779819477141"></a><a name="p1779819477141"></a>Sets a listener to listen for tap events of an information window.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table32281428123818"></a>
<table><thead align="left"><tr id="row148434283388"><th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.1"><p id="p178431028163814"><a name="p178431028163814"></a><a name="p178431028163814"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.2"><p id="p08431628143815"><a name="p08431628143815"></a><a name="p08431628143815"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row1584312819387"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p13843102843811"><a name="p13843102843811"></a><a name="p13843102843811"></a>listener</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p1984342883818"><a name="p1984342883818"></a><a name="p1984342883818"></a>Listener used to listen for the information window tap event.</p>
</td>
</tr>
</tbody>
</table>

## setOnInfoWindowCloseListener<a name="section1096718581452"></a>

<a name="table48759261519"></a>
<table><thead align="left"><tr id="row127110311156"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p172713371514"><a name="p172713371514"></a><a name="p172713371514"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row1027213101513"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p18272435158"><a name="p18272435158"></a><a name="p18272435158"></a>public void setOnInfoWindowCloseListener(<a href="oninfowindowcloselistener.md">HuaweiMap.OnInfoWindowCloseListener</a> listener)</p>
<p id="p627214312158"><a name="p627214312158"></a><a name="p627214312158"></a>Sets a listener to listen for closure events of an information window.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table162301628153817"></a>
<table><thead align="left"><tr id="row984412810386"><th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.1"><p id="p6844102810381"><a name="p6844102810381"></a><a name="p6844102810381"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.2"><p id="p15844192816385"><a name="p15844192816385"></a><a name="p15844192816385"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row284462815387"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p1684412873817"><a name="p1684412873817"></a><a name="p1684412873817"></a>listener</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p2084432833820"><a name="p2084432833820"></a><a name="p2084432833820"></a>Listener used to listen for the information window closure event.</p>
</td>
</tr>
</tbody>
</table>

## setOnInfoWindowLongClickListener<a name="section17625311668"></a>

<a name="table5596101701518"></a>
<table><thead align="left"><tr id="row1578131751518"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p1778171713155"><a name="p1778171713155"></a><a name="p1778171713155"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row10781317101519"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p1378112178157"><a name="p1378112178157"></a><a name="p1378112178157"></a>public void setOnInfoWindowLongClickListener(<a href="oninfowindowlongclicklistener.md">HuaweiMap.OnInfoWindowLongClickListener</a> listener)</p>
<p id="p15781817101510"><a name="p15781817101510"></a><a name="p15781817101510"></a>Sets a listener to listen for long press events of an information window.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table32340287388"></a>
<table><thead align="left"><tr id="row17844528183811"><th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.1"><p id="p16844182823811"><a name="p16844182823811"></a><a name="p16844182823811"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.2"><p id="p1384492818385"><a name="p1384492818385"></a><a name="p1384492818385"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row10844112812386"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p1284482810387"><a name="p1284482810387"></a><a name="p1284482810387"></a>listener</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p158441728193819"><a name="p158441728193819"></a><a name="p158441728193819"></a>Listener used to listen for the long press event of an information window.</p>
</td>
</tr>
</tbody>
</table>

## setOnMapClickListener<a name="section52313331461"></a>

<a name="table18291328141516"></a>
<table><thead align="left"><tr id="row4132929191513"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p1413242971514"><a name="p1413242971514"></a><a name="p1413242971514"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row9133122910154"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p1313382912152"><a name="p1313382912152"></a><a name="p1313382912152"></a>public void setOnMapClickListener(<a href="onmapclicklistener.md">HuaweiMap.OnMapClickListener</a> listener)</p>
<p id="p7133172961516"><a name="p7133172961516"></a><a name="p7133172961516"></a>Sets a listener to listen for tap events of a map.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table142365280385"></a>
<table><thead align="left"><tr id="row68461628153813"><th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.1"><p id="p108469284380"><a name="p108469284380"></a><a name="p108469284380"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.2"><p id="p13846172814387"><a name="p13846172814387"></a><a name="p13846172814387"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row38461028163814"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p7846132813816"><a name="p7846132813816"></a><a name="p7846132813816"></a>listener</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p11846152843811"><a name="p11846152843811"></a><a name="p11846152843811"></a>Listener used to listen for the map tap event.</p>
</td>
</tr>
</tbody>
</table>

## setOnMapLoadedCallback<a name="section61080560616"></a>

<a name="table17917125311518"></a>
<table><thead align="left"><tr id="row1812915421513"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p14129254181512"><a name="p14129254181512"></a><a name="p14129254181512"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row1112935420158"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p21293541158"><a name="p21293541158"></a><a name="p21293541158"></a>public void setOnMapLoadedCallback(<a href="onmaploadedcallback.md">HuaweiMap.OnMapLoadedCallback</a> callback)</p>
<p id="p313025491513"><a name="p313025491513"></a><a name="p313025491513"></a>Sets a callback executed when the map loading is completed. The callback will be executed once only. </p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table12239182883818"></a>
<table><thead align="left"><tr id="row1784602883820"><th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.1"><p id="p78461728123811"><a name="p78461728123811"></a><a name="p78461728123811"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.2"><p id="p4846162843816"><a name="p4846162843816"></a><a name="p4846162843816"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row16846728203817"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p14846162833816"><a name="p14846162833816"></a><a name="p14846162833816"></a>callback</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p784632883820"><a name="p784632883820"></a><a name="p784632883820"></a>Callback executed when the map loading is complete.</p>
</td>
</tr>
</tbody>
</table>

## setOnMapLongClickListener<a name="section7571104711"></a>

<a name="table767911417167"></a>
<table><thead align="left"><tr id="row1987371481614"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p38732148160"><a name="p38732148160"></a><a name="p38732148160"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row1487316140165"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p08733144163"><a name="p08733144163"></a><a name="p08733144163"></a>public void setOnMapLongClickListener(<a href="onmaplongclicklistener.md">HuaweiMap.OnMapLongClickListener</a> listener)</p>
<p id="p6873181413168"><a name="p6873181413168"></a><a name="p6873181413168"></a>Sets a listener to listen for long press events of a map.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table12241328173814"></a>
<table><thead align="left"><tr id="row178466288389"><th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.1"><p id="p884682810382"><a name="p884682810382"></a><a name="p884682810382"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.2"><p id="p18846628183820"><a name="p18846628183820"></a><a name="p18846628183820"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row12846182815381"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p138471128163811"><a name="p138471128163811"></a><a name="p138471128163811"></a>listener</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p58471028173819"><a name="p58471028173819"></a><a name="p58471028173819"></a>Listener used to listen for the map long press event.</p>
</td>
</tr>
</tbody>
</table>

## setOnMarkerClickListener<a name="section6157172618712"></a>

<a name="table14471227181614"></a>
<table><thead align="left"><tr id="row172078277162"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p1220722791616"><a name="p1220722791616"></a><a name="p1220722791616"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row4207627161611"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p120718279160"><a name="p120718279160"></a><a name="p120718279160"></a>public void setOnMarkerClickListener(<a href="onmarkerclicklistener.md">HuaweiMap.OnMarkerClickListener</a> listener)</p>
<p id="p2207142721615"><a name="p2207142721615"></a><a name="p2207142721615"></a>Sets a listener to listen for tap events of a marker.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table1624392818382"></a>
<table><thead align="left"><tr id="row48471428193810"><th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.1"><p id="p5847142810384"><a name="p5847142810384"></a><a name="p5847142810384"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.2"><p id="p1847428123813"><a name="p1847428123813"></a><a name="p1847428123813"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row138472288389"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p1484717288388"><a name="p1484717288388"></a><a name="p1484717288388"></a>listener</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p1984792817385"><a name="p1984792817385"></a><a name="p1984792817385"></a>Listener used to listen for the marker tap event.</p>
</td>
</tr>
</tbody>
</table>

## setOnMarkerDragListener<a name="section183907434711"></a>

<a name="table128215411165"></a>
<table><thead align="left"><tr id="row9236144121617"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p12236164118162"><a name="p12236164118162"></a><a name="p12236164118162"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row6236174119167"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p82366415163"><a name="p82366415163"></a><a name="p82366415163"></a>public void setOnMarkerDragListener(<a href="onmarkerdraglistener.md">HuaweiMap.OnMarkerDragListener</a> listener)</p>
<p id="p10236941161612"><a name="p10236941161612"></a><a name="p10236941161612"></a>Sets a listener to listen for drag events of a marker.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table17245142843818"></a>
<table><thead align="left"><tr id="row68476284389"><th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.1"><p id="p38471128133813"><a name="p38471128133813"></a><a name="p38471128133813"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.2"><p id="p1284710283383"><a name="p1284710283383"></a><a name="p1284710283383"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row08471128203814"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p18847122812389"><a name="p18847122812389"></a><a name="p18847122812389"></a>listener</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p17847182833820"><a name="p17847182833820"></a><a name="p17847182833820"></a>Listener used to listen for the marker drag event.</p>
</td>
</tr>
</tbody>
</table>

## setOnMyLocationButtonClickListener<a name="section260912591070"></a>

<a name="table138365238178"></a>
<table><thead align="left"><tr id="row248124121714"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p148162418173"><a name="p148162418173"></a><a name="p148162418173"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row1448162471717"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p34882481715"><a name="p34882481715"></a><a name="p34882481715"></a>public void setOnMyLocationButtonClickListener(<a href="onmylocationbuttonclicklistener.md">OnMyLocationButtonClickListener</a> listener)</p>
<p id="p19481724191716"><a name="p19481724191716"></a><a name="p19481724191716"></a>Sets a listener to listen for tap events of the my-location icon. If the listener returns <strong id="b12262114881018"><a name="b12262114881018"></a><a name="b12262114881018"></a>true</strong>, an event has been consumed and no default operation will be performed. If the listener returns <strong id="b453335719103"><a name="b453335719103"></a><a name="b453335719103"></a>false</strong>, the default operation will be performed. That is, the camera moves to center on the current location of the user.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table162481628203811"></a>
<table><thead align="left"><tr id="row1584712812382"><th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.1"><p id="p16847152817387"><a name="p16847152817387"></a><a name="p16847152817387"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.2"><p id="p38485286386"><a name="p38485286386"></a><a name="p38485286386"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row1484842843814"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p15848112883815"><a name="p15848112883815"></a><a name="p15848112883815"></a>listener</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p98481528193813"><a name="p98481528193813"></a><a name="p98481528193813"></a>Listener used to listen for the my-location icon tap event.</p>
</td>
</tr>
</tbody>
</table>

## setOnMyLocationClickListener<a name="section438716120819"></a>

<a name="table97091538101719"></a>
<table><thead align="left"><tr id="row5921173801719"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p1921103819170"><a name="p1921103819170"></a><a name="p1921103819170"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row492143891715"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p13921153891717"><a name="p13921153891717"></a><a name="p13921153891717"></a>public void setOnMyLocationClickListener(<a href="onmylocationclicklistener.md">OnMyLocationClickListener</a> listener)</p>
<p id="p1921183812173"><a name="p1921183812173"></a><a name="p1921183812173"></a>Sets a listener to listen for tap events of the my-location dot.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table32503282382"></a>
<table><thead align="left"><tr id="row16848228133811"><th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.1"><p id="p48485286383"><a name="p48485286383"></a><a name="p48485286383"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.2"><p id="p1884842811385"><a name="p1884842811385"></a><a name="p1884842811385"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row78481828173817"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p98481283382"><a name="p98481283382"></a><a name="p98481283382"></a>listener</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p1784816288386"><a name="p1784816288386"></a><a name="p1784816288386"></a>Listener used to listen for the my-location dot tap event.</p>
</td>
</tr>
</tbody>
</table>

## setOnPoiClickListener<a name="section34348380817"></a>

<a name="table87745513174"></a>
<table><thead align="left"><tr id="row18187115221713"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p91872520172"><a name="p91872520172"></a><a name="p91872520172"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row1187252111710"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p1318775251713"><a name="p1318775251713"></a><a name="p1318775251713"></a>public void setOnPoiClickListener(<a href="onpoiclicklistener.md">HuaweiMap.OnPoiClickListener</a> listener)</p>
<p id="p16187185211719"><a name="p16187185211719"></a><a name="p16187185211719"></a>Sets a listener to listen for tap events of a POI.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table4252152813817"></a>
<table><thead align="left"><tr id="row58489285383"><th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.1"><p id="p1584882843812"><a name="p1584882843812"></a><a name="p1584882843812"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.2"><p id="p198489288385"><a name="p198489288385"></a><a name="p198489288385"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row138491628193817"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p13849828143812"><a name="p13849828143812"></a><a name="p13849828143812"></a>listener</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p5849132863812"><a name="p5849132863812"></a><a name="p5849132863812"></a>Listener used to listen for the POI tap event.</p>
</td>
</tr>
</tbody>
</table>

## setOnPolygonClickListener<a name="section1893435314811"></a>

<a name="table343112321812"></a>
<table><thead align="left"><tr id="row11789223161816"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p12804123171814"><a name="p12804123171814"></a><a name="p12804123171814"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row10804112318181"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p98051123191814"><a name="p98051123191814"></a><a name="p98051123191814"></a>public void setOnPolygonClickListener(<a href="onpolygonclicklistener.md">HuaweiMap.OnPolygonClickListener</a> listener)</p>
<p id="p1480502317187"><a name="p1480502317187"></a><a name="p1480502317187"></a>Sets a listener to listen for tap events of a polygon.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table142550284388"></a>
<table><thead align="left"><tr id="row98491028163818"><th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.1"><p id="p11849172819388"><a name="p11849172819388"></a><a name="p11849172819388"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.2"><p id="p11849328123817"><a name="p11849328123817"></a><a name="p11849328123817"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row584962812388"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p184932823819"><a name="p184932823819"></a><a name="p184932823819"></a>listener</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p1084952817385"><a name="p1084952817385"></a><a name="p1084952817385"></a>Listener used to listen for the polygon tap event.</p>
</td>
</tr>
</tbody>
</table>

## setOnPolylineClickListener<a name="section15655107591"></a>

<a name="table5385237191816"></a>
<table><thead align="left"><tr id="row6543173720182"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p1654317376188"><a name="p1654317376188"></a><a name="p1654317376188"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row145431637151817"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p1154310377185"><a name="p1154310377185"></a><a name="p1154310377185"></a>public void setOnPolylineClickListener(<a href="onpolylineclicklistener.md">HuaweiMap.OnPolylineClickListener</a> listener)</p>
<p id="p5543173710188"><a name="p5543173710188"></a><a name="p5543173710188"></a>Sets a listener to listen for tap events of a polyline.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table152573289388"></a>
<table><thead align="left"><tr id="row17849142811386"><th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.1"><p id="p084914287387"><a name="p084914287387"></a><a name="p084914287387"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.2"><p id="p8849192816388"><a name="p8849192816388"></a><a name="p8849192816388"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row178491928153819"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p118491728123817"><a name="p118491728123817"></a><a name="p118491728123817"></a>listener</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p1684915282384"><a name="p1684915282384"></a><a name="p1684915282384"></a>Listener used to listen for the polyline tap event.</p>
</td>
</tr>
</tbody>
</table>

## setPadding<a name="section10782142412914"></a>

<a name="table819384910183"></a>
<table><thead align="left"><tr id="row20356134911187"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p19356154914182"><a name="p19356154914182"></a><a name="p19356154914182"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row93561549181812"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p19356124912182"><a name="p19356124912182"></a><a name="p19356124912182"></a>public void setPadding(int left, int top, int right, int bottom)</p>
<p id="p781917355178"><a name="p781917355178"></a><a name="p781917355178"></a>Sets padding on a map to define the visible region on a map. Some portions around the map edges may be obscured. Map elements will adapt to the padding. For example, icons such as the zoom controls and compass will be moved to adapt to the visible region, and the camera will move in relative to the center of the visible region.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table1525911282384"></a>
<table><thead align="left"><tr id="row18491528183818"><th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.1"><p id="p6849192815380"><a name="p6849192815380"></a><a name="p6849192815380"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.2"><p id="p38492287389"><a name="p38492287389"></a><a name="p38492287389"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row10850328113813"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p148503282387"><a name="p148503282387"></a><a name="p148503282387"></a>left</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p18850928203819"><a name="p18850928203819"></a><a name="p18850928203819"></a>Distance from the visible region to the left edge of the map, in pixels.</p>
</td>
</tr>
<tr id="row1685022819385"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p12850128153820"><a name="p12850128153820"></a><a name="p12850128153820"></a>top</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p13850228123818"><a name="p13850228123818"></a><a name="p13850228123818"></a>Distance from the visible region to the top edge of the map, in pixels.</p>
</td>
</tr>
<tr id="row1385032813813"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p5850228103812"><a name="p5850228103812"></a><a name="p5850228103812"></a>right</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p18850122863810"><a name="p18850122863810"></a><a name="p18850122863810"></a>Distance from the visible region to the right edge of the map, in pixels.</p>
</td>
</tr>
<tr id="row4850102819389"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p1185017283381"><a name="p1185017283381"></a><a name="p1185017283381"></a>bottom</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p20850202818383"><a name="p20850202818383"></a><a name="p20850202818383"></a>Distance from the visible region to the bottom edge of the map, in pixels.</p>
</td>
</tr>
</tbody>
</table>

## setPointToCenter<a name="section63930559559"></a>

<a name="table2039335545518"></a>
<table><thead align="left"><tr id="row8393145511557"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p339317558554"><a name="p339317558554"></a><a name="p339317558554"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row73931555195515"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p1039385525513"><a name="p1039385525513"></a><a name="p1039385525513"></a>public void setPointToCenter(int x, int y)</p>
<p id="p17394195545517"><a name="p17394195545517"></a><a name="p17394195545517"></a>Sets a fixed screen center for zooming. </p>
<div class="caution" id="note1357113323815"><a name="note1357113323815"></a><a name="note1357113323815"></a><span class="cautiontitle"> CAUTION: </span><div class="cautionbody"><p id="p45711237384"><a name="p45711237384"></a><a name="p45711237384"></a>The passed screen center is valid only when <strong id="b133851121185111"><a name="b133851121185111"></a><a name="b133851121185111"></a>true</strong> is passed to <a href="uisettings.md#section8176121651612">setGestureScaleByMapCenter</a><strong id="b93863218511"><a name="b93863218511"></a><a name="b93863218511"></a>(boolean enabled)</strong> in the <a href="uisettings.md">UiSettings</a> class in advance. To cancel the function of setting a fixed screen center, you only need to pass <strong id="b738682135110"><a name="b738682135110"></a><a name="b738682135110"></a>false</strong> to <a href="uisettings.md#section8176121651612">setGestureScaleByMapCenter</a><strong id="b0387162135112"><a name="b0387162135112"></a><a name="b0387162135112"></a>(boolean enabled)</strong> without calling <strong id="b15387122165115"><a name="b15387122165115"></a><a name="b15387122165115"></a>setPointToCenter</strong>. </p>
</div></div>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table5394555135512"></a>
<table><thead align="left"><tr id="row1039485585513"><th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.1"><p id="p93942550558"><a name="p93942550558"></a><a name="p93942550558"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.2"><p id="p10394205565518"><a name="p10394205565518"></a><a name="p10394205565518"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row6394655115511"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p18395655185513"><a name="p18395655185513"></a><a name="p18395655185513"></a>x</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p183951955165512"><a name="p183951955165512"></a><a name="p183951955165512"></a>X-axis coordinate on the screen.</p>
</td>
</tr>
<tr id="row10395125511556"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p12395195511550"><a name="p12395195511550"></a><a name="p12395195511550"></a>y</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p83952055155514"><a name="p83952055155514"></a><a name="p83952055155514"></a>Y-axis coordinate on the screen.</p>
</td>
</tr>
</tbody>
</table>

## setTrafficEnabled<a name="section14752131510581"></a>

<a name="table575312156587"></a>
<table><thead align="left"><tr id="row8753111595810"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p187536159589"><a name="p187536159589"></a><a name="p187536159589"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row15753151535812"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p1175316155589"><a name="p1175316155589"></a><a name="p1175316155589"></a>public void setTrafficEnabled(boolean enabled)</p>
<p id="p1575351545813"><a name="p1575351545813"></a><a name="p1575351545813"></a>Sets whether to enable the traffic status layer. </p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table12754315135815"></a>
<table><thead align="left"><tr id="row1575431518587"><th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.1"><p id="p475471565815"><a name="p475471565815"></a><a name="p475471565815"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.2"><p id="p975491565818"><a name="p975491565818"></a><a name="p975491565818"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row1275491535819"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p162510359595"><a name="p162510359595"></a><a name="p162510359595"></a>enabled</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p1275481511584"><a name="p1275481511584"></a><a name="p1275481511584"></a>Indicates whether to enable the traffic status layer. The options are <strong id="b0573158863"><a name="b0573158863"></a><a name="b0573158863"></a>true</strong> (yes) and <strong id="b3146111619"><a name="b3146111619"></a><a name="b3146111619"></a>false</strong> (no). The default value is <strong id="b988816181969"><a name="b988816181969"></a><a name="b988816181969"></a>false</strong>.</p>
</td>
</tr>
</tbody>
</table>

## snapshot\(HuaweiMap.SnapshotReadyCallback callback\)<a name="section2497204917913"></a>

<a name="table410117212192"></a>
<table><thead align="left"><tr id="row429313211197"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p102938231915"><a name="p102938231915"></a><a name="p102938231915"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row11293132171911"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p92936218195"><a name="p92936218195"></a><a name="p92936218195"></a>public void snapshot(<a href="snapshotreadycallback.md">HuaweiMap.SnapshotReadyCallback</a> callback)</p>
<p id="p32936291916"><a name="p32936291916"></a><a name="p32936291916"></a>Takes a snapshot of a map. If an interactive map is difficult or impossible to use, you can use snapshots in your app. For example, you can call the <a href="#section2497204917913">snapshot</a><strong id="b208601232161319"><a name="b208601232161319"></a><a name="b208601232161319"></a>()</strong> method to generate images and use them to display a thumbnail of the map in your app, or display a snapshot in the notification center.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table726822815382"></a>
<table><thead align="left"><tr id="row10850228193810"><th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.1"><p id="p1850142811384"><a name="p1850142811384"></a><a name="p1850142811384"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.2"><p id="p118504288388"><a name="p118504288388"></a><a name="p118504288388"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row11850128193810"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p7851202813385"><a name="p7851202813385"></a><a name="p7851202813385"></a>callback</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p13851122816386"><a name="p13851122816386"></a><a name="p13851122816386"></a>Callback method called when a map snapshot is generated.</p>
</td>
</tr>
</tbody>
</table>

## snapshot\(HuaweiMap.SnapshotReadyCallback callback, Bitmap bitmap\)<a name="section208491759897"></a>

<a name="table17682101461920"></a>
<table><thead align="left"><tr id="row108971614131916"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p7897161420199"><a name="p7897161420199"></a><a name="p7897161420199"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row18897151421918"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p789713147196"><a name="p789713147196"></a><a name="p789713147196"></a>public void snapshot(<a href="snapshotreadycallback.md">HuaweiMap.SnapshotReadyCallback</a> callback, Bitmap bitmap)</p>
<p id="p10897714121912"><a name="p10897714121912"></a><a name="p10897714121912"></a>Takes a snapshot of a map. This method is equivalent to <a href="#section2497204917913">snapshot</a>(<a href="snapshotreadycallback.md">SnapshotReadyCallback</a>), but allows you to provide a pre-allocated Bitmap image. If the Bitmap image does not match the current map size, another Bitmap image matching the size will be allocated. In most cases, the object passed by the callback method is the same as that provided in the parameter of this method. However, in some cases, the object provided in this method may not be used (for example, if the size of the view has changed at the time when the snapshot is actually taken). Therefore, you should trust only the Bitmap image passed by the callback method.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table142701328153820"></a>
<table><thead align="left"><tr id="row48518281388"><th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.1"><p id="p185111287384"><a name="p185111287384"></a><a name="p185111287384"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.2"><p id="p13851162814389"><a name="p13851162814389"></a><a name="p13851162814389"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row19851132816382"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p118511528183815"><a name="p118511528183815"></a><a name="p118511528183815"></a>callback</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p15851152873814"><a name="p15851152873814"></a><a name="p15851152873814"></a>Callback method called when a map snapshot is generated.</p>
</td>
</tr>
<tr id="row12851142815385"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p7851152812386"><a name="p7851152812386"></a><a name="p7851152812386"></a>bitmap</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p1285122823820"><a name="p1285122823820"></a><a name="p1285122823820"></a>Pre-allocated Bitmap image. If this parameter is set to <strong id="b1341125764116"><a name="b1341125764116"></a><a name="b1341125764116"></a>null</strong>, this method functions similarly to <a href="#section2497204917913">snapshot</a>(<a href="snapshotreadycallback.md">SnapshotReadyCallback</a>).</p>
</td>
</tr>
</tbody>
</table>

## stopAnimation<a name="section4909811181019"></a>

<a name="table5813132721918"></a>
<table><thead align="left"><tr id="row099013271197"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p19990427131913"><a name="p19990427131913"></a><a name="p19990427131913"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row799011277191"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p699092781918"><a name="p699092781918"></a><a name="p699092781918"></a>public void stopAnimation()</p>
<p id="p599092751916"><a name="p599092751916"></a><a name="p599092751916"></a>Stops the current animation of the camera. When this method is called, the camera stops moving immediately and remains in that position.</p>
</td>
</tr>
</tbody>
</table>

