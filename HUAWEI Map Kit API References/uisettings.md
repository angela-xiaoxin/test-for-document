# UiSettings<a name="EN-US_TOPIC_0000001099181290"></a>

-   [Public Method Summary](#section1990193555718)
-   [Public Methods](#section1648332455214)
-   [isCompassEnabled](#section20382153735213)
-   [isMyLocationButtonEnabled](#section42821419205312)
-   [isRotateGesturesEnabled](#section2532125605311)
-   [isScrollGesturesEnabled](#section1538712317544)
-   [isScrollGesturesEnabledDuringRotateOrZoom](#section1985001713554)
-   [isTiltGesturesEnabled](#section41913572555)
-   [isZoomControlsEnabled](#section3339153125618)
-   [isZoomGesturesEnabled](#section2603185155713)
-   [setAllGesturesEnabled](#section32351948185710)
-   [setCompassEnabled](#section129811026105811)
-   [setGestureScaleByMapCenter](#section8176121651612)
-   [setMarkerClusterColor](#section11137745113915)
-   [setMarkerClusterIcon](#section72972050124113)
-   [setMarkerClusterTextColor](#section3137125684216)
-   [setMyLocationButtonEnabled](#section1530742525919)
-   [setRotateGesturesEnabled](#section6840881108)
-   [setScrollGesturesEnabled](#section1923864410016)
-   [setScrollGesturesEnabledDuringRotateOrZoom](#section169705158119)
-   [setTiltGesturesEnabled](#section11471236212)
-   [setZoomControlsEnabled](#section185278164314)
-   [setZoomGesturesEnabled](#section12131521337)


<a name="table7749mcpsimp"></a>
<table><thead align="left"><tr id="row7753mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p7755mcpsimp"><a name="p7755mcpsimp"></a><a name="p7755mcpsimp"></a>Class Info</p>
</th>
</tr>
</thead>
<tbody><tr id="row7756mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p194926182818"><a name="p194926182818"></a><a name="p194926182818"></a>public final class UiSettings</p>
<p id="p18718174720295"><a name="p18718174720295"></a><a name="p18718174720295"></a>Built-in UI and gesture controller. An instance of this type will be returned when the <a href="huaweimap.md#section86721421145920">getUiSettings</a> method in the <a href="huaweimap.md">HuaweiMap</a> class is called. </p>
</td>
</tr>
</tbody>
</table>

## Public Method Summary<a name="section1990193555718"></a>

<a name="table7764mcpsimp"></a>
<table><thead align="left"><tr id="row7769mcpsimp"><th class="cellrowborder" valign="top" width="40%" id="mcps1.1.3.1.1"><p id="p7771mcpsimp"><a name="p7771mcpsimp"></a><a name="p7771mcpsimp"></a>Qualifier and Type</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.1.3.1.2"><p id="p7773mcpsimp"><a name="p7773mcpsimp"></a><a name="p7773mcpsimp"></a>Method Name and Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row7774mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p7776mcpsimp"><a name="p7776mcpsimp"></a><a name="p7776mcpsimp"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p7778mcpsimp"><a name="p7778mcpsimp"></a><a name="p7778mcpsimp"></a><a href="#section20382153735213">isCompassEnabled</a>()</p>
<p id="p113431436112115"><a name="p113431436112115"></a><a name="p113431436112115"></a>Checks whether the compass is enabled for a map.</p>
</td>
</tr>
<tr id="row7789mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p7791mcpsimp"><a name="p7791mcpsimp"></a><a name="p7791mcpsimp"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p7793mcpsimp"><a name="p7793mcpsimp"></a><a name="p7793mcpsimp"></a><a href="#section42821419205312">isMyLocationButtonEnabled</a>()</p>
<p id="p189441373215"><a name="p189441373215"></a><a name="p189441373215"></a>Checks whether the my-location icon is enabled for a map.</p>
</td>
</tr>
<tr id="row7794mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p7796mcpsimp"><a name="p7796mcpsimp"></a><a name="p7796mcpsimp"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p7798mcpsimp"><a name="p7798mcpsimp"></a><a name="p7798mcpsimp"></a><a href="#section2532125605311">isRotateGesturesEnabled</a>()</p>
<p id="p487310381214"><a name="p487310381214"></a><a name="p487310381214"></a>Checks whether rotation gestures are enabled for a map.</p>
</td>
</tr>
<tr id="row7799mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p7801mcpsimp"><a name="p7801mcpsimp"></a><a name="p7801mcpsimp"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p7803mcpsimp"><a name="p7803mcpsimp"></a><a name="p7803mcpsimp"></a><a href="#section1538712317544">isScrollGesturesEnabled</a>()</p>
<p id="p1495813910211"><a name="p1495813910211"></a><a name="p1495813910211"></a>Checks whether scroll gestures are enabled for a map.</p>
</td>
</tr>
<tr id="row7804mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p7806mcpsimp"><a name="p7806mcpsimp"></a><a name="p7806mcpsimp"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p7808mcpsimp"><a name="p7808mcpsimp"></a><a name="p7808mcpsimp"></a><a href="#section1985001713554">isScrollGesturesEnabledDuringRotateOrZoom</a>()</p>
<p id="p92161141192114"><a name="p92161141192114"></a><a name="p92161141192114"></a>Checks whether scroll gestures are enabled during rotation or zooming.</p>
</td>
</tr>
<tr id="row7809mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p7811mcpsimp"><a name="p7811mcpsimp"></a><a name="p7811mcpsimp"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p7813mcpsimp"><a name="p7813mcpsimp"></a><a name="p7813mcpsimp"></a><a href="#section41913572555">isTiltGesturesEnabled</a>()</p>
<p id="p1292174232111"><a name="p1292174232111"></a><a name="p1292174232111"></a>Checks whether tilt gestures are enabled for a map.</p>
</td>
</tr>
<tr id="row7814mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p7816mcpsimp"><a name="p7816mcpsimp"></a><a name="p7816mcpsimp"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p7818mcpsimp"><a name="p7818mcpsimp"></a><a name="p7818mcpsimp"></a><a href="#section3339153125618">isZoomControlsEnabled</a>()</p>
<p id="p45319444211"><a name="p45319444211"></a><a name="p45319444211"></a>Checks whether zoom controls are enabled for a map.</p>
</td>
</tr>
<tr id="row7819mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p7821mcpsimp"><a name="p7821mcpsimp"></a><a name="p7821mcpsimp"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p7823mcpsimp"><a name="p7823mcpsimp"></a><a name="p7823mcpsimp"></a><a href="#section2603185155713">isZoomGesturesEnabled</a>()</p>
<p id="p112241845122114"><a name="p112241845122114"></a><a name="p112241845122114"></a>Checks whether zoom gestures are enabled for a map.</p>
</td>
</tr>
<tr id="row7824mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p7826mcpsimp"><a name="p7826mcpsimp"></a><a name="p7826mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p7828mcpsimp"><a name="p7828mcpsimp"></a><a name="p7828mcpsimp"></a><a href="#section32351948185710">setAllGesturesEnabled</a>(boolean enabled)</p>
<p id="p495814611217"><a name="p495814611217"></a><a name="p495814611217"></a>Sets whether to enable all gestures for a map.</p>
</td>
</tr>
<tr id="row7829mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p7831mcpsimp"><a name="p7831mcpsimp"></a><a name="p7831mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p7833mcpsimp"><a name="p7833mcpsimp"></a><a name="p7833mcpsimp"></a><a href="#section129811026105811">setCompassEnabled</a>(boolean enabled)</p>
<p id="p77801647152113"><a name="p77801647152113"></a><a name="p77801647152113"></a>Sets whether to enable the compass for a map.</p>
</td>
</tr>
<tr id="row1981617467149"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p981615463143"><a name="p981615463143"></a><a name="p981615463143"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p4816154616143"><a name="p4816154616143"></a><a name="p4816154616143"></a><a href="#section8176121651612">setGestureScaleByMapCenter</a>(boolean enabled)</p>
<p id="p3995253173514"><a name="p3995253173514"></a><a name="p3995253173514"></a>Specifies whether a fixed screen center can be set for zooming.</p>
</td>
</tr>
<tr id="row619913403311"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p131993346338"><a name="p131993346338"></a><a name="p131993346338"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p134078469293"><a name="p134078469293"></a><a name="p134078469293"></a><a href="#section11137745113915">setMarkerClusterColor</a>(int color)</p>
<p id="p1407204613290"><a name="p1407204613290"></a><a name="p1407204613290"></a>Sets the color of the default cluster marker.</p>
</td>
</tr>
<tr id="row1169575517356"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p12695195573519"><a name="p12695195573519"></a><a name="p12695195573519"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p48836483313"><a name="p48836483313"></a><a name="p48836483313"></a><a href="#section72972050124113">setMarkerClusterIcon</a>(<a href="bitmapdescriptor.md">BitmapDescriptor</a> iconDescriptor )</p>
<p id="p988354883118"><a name="p988354883118"></a><a name="p988354883118"></a>Sets the icon of the custom cluster marker.</p>
</td>
</tr>
<tr id="row4692185818358"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p1569275811351"><a name="p1569275811351"></a><a name="p1569275811351"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p1270724833311"><a name="p1270724833311"></a><a name="p1270724833311"></a><a href="#section3137125684216">setMarkerClusterTextColor</a>(int color)</p>
<p id="p1570764820331"><a name="p1570764820331"></a><a name="p1570764820331"></a>Sets the text color of the custom cluster marker.</p>
</td>
</tr>
<tr id="row7844mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p7846mcpsimp"><a name="p7846mcpsimp"></a><a name="p7846mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p7848mcpsimp"><a name="p7848mcpsimp"></a><a name="p7848mcpsimp"></a><a href="#section1530742525919">setMyLocationButtonEnabled</a>(boolean enabled)</p>
<p id="p7712144917214"><a name="p7712144917214"></a><a name="p7712144917214"></a>Sets whether to enable the my-location icon for a map.</p>
</td>
</tr>
<tr id="row7849mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p7851mcpsimp"><a name="p7851mcpsimp"></a><a name="p7851mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p7853mcpsimp"><a name="p7853mcpsimp"></a><a name="p7853mcpsimp"></a><a href="#section6840881108">setRotateGesturesEnabled</a>(boolean enabled)</p>
<p id="p133931151172112"><a name="p133931151172112"></a><a name="p133931151172112"></a>Sets whether to enable rotation gestures for a map.</p>
</td>
</tr>
<tr id="row7854mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p7856mcpsimp"><a name="p7856mcpsimp"></a><a name="p7856mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p7858mcpsimp"><a name="p7858mcpsimp"></a><a name="p7858mcpsimp"></a><a href="#section1923864410016">setScrollGesturesEnabled</a>(boolean enabled)</p>
<p id="p3824195214216"><a name="p3824195214216"></a><a name="p3824195214216"></a>Sets whether to enable scroll gestures for a map.</p>
</td>
</tr>
<tr id="row7859mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p7861mcpsimp"><a name="p7861mcpsimp"></a><a name="p7861mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p7863mcpsimp"><a name="p7863mcpsimp"></a><a name="p7863mcpsimp"></a><a href="#section169705158119">setScrollGesturesEnabledDuringRotateOrZoom</a>(boolean enabled)</p>
<p id="p91618541213"><a name="p91618541213"></a><a name="p91618541213"></a>Sets whether to enable scroll gestures during rotation or zooming.</p>
</td>
</tr>
<tr id="row7864mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p7866mcpsimp"><a name="p7866mcpsimp"></a><a name="p7866mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p7868mcpsimp"><a name="p7868mcpsimp"></a><a name="p7868mcpsimp"></a><a href="#section11471236212">setTiltGesturesEnabled</a>(boolean enabled)</p>
<p id="p03855152111"><a name="p03855152111"></a><a name="p03855152111"></a>Sets whether to enable tilt gestures for a map.</p>
</td>
</tr>
<tr id="row7869mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p7871mcpsimp"><a name="p7871mcpsimp"></a><a name="p7871mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p7873mcpsimp"><a name="p7873mcpsimp"></a><a name="p7873mcpsimp"></a><a href="#section185278164314">setZoomControlsEnabled</a>(boolean enabled)</p>
<p id="p78361555102117"><a name="p78361555102117"></a><a name="p78361555102117"></a>Sets whether to enable zoom controls for a map.</p>
</td>
</tr>
<tr id="row7874mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p7876mcpsimp"><a name="p7876mcpsimp"></a><a name="p7876mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p7878mcpsimp"><a name="p7878mcpsimp"></a><a name="p7878mcpsimp"></a><a href="#section12131521337">setZoomGesturesEnabled</a>(boolean enabled)</p>
<p id="p15769556192114"><a name="p15769556192114"></a><a name="p15769556192114"></a>Sets whether to enable zoom gestures for a map.</p>
</td>
</tr>
</tbody>
</table>

## Public Methods<a name="section1648332455214"></a>

## isCompassEnabled<a name="section20382153735213"></a>

<a name="table7881mcpsimp"></a>
<table><thead align="left"><tr id="row7885mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p7887mcpsimp"><a name="p7887mcpsimp"></a><a name="p7887mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row7888mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p7890mcpsimp"><a name="p7890mcpsimp"></a><a name="p7890mcpsimp"></a>public boolean isCompassEnabled()</p>
<p id="p4286125520526"><a name="p4286125520526"></a><a name="p4286125520526"></a>Checks whether the compass is enabled for a map.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table7899mcpsimp"></a>
<table><thead align="left"><tr id="row7904mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p7906mcpsimp"><a name="p7906mcpsimp"></a><a name="p7906mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p7908mcpsimp"><a name="p7908mcpsimp"></a><a name="p7908mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row7909mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p7911mcpsimp"><a name="p7911mcpsimp"></a><a name="p7911mcpsimp"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p7913mcpsimp"><a name="p7913mcpsimp"></a><a name="p7913mcpsimp"></a><strong id="b794525719302"><a name="b794525719302"></a><a name="b794525719302"></a>true</strong> if the compass is enabled; <strong id="b337913478304"><a name="b337913478304"></a><a name="b337913478304"></a>false</strong> otherwise.</p>
</td>
</tr>
</tbody>
</table>

## isMyLocationButtonEnabled<a name="section42821419205312"></a>

<a name="table7915mcpsimp"></a>
<table><thead align="left"><tr id="row7919mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p7921mcpsimp"><a name="p7921mcpsimp"></a><a name="p7921mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row7922mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p7924mcpsimp"><a name="p7924mcpsimp"></a><a name="p7924mcpsimp"></a>public boolean isMyLocationButtonEnabled()</p>
<p id="p7927mcpsimp"><a name="p7927mcpsimp"></a><a name="p7927mcpsimp"></a>Checks whether the my-location icon is enabled for a map.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table7933mcpsimp"></a>
<table><thead align="left"><tr id="row7938mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p7940mcpsimp"><a name="p7940mcpsimp"></a><a name="p7940mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p7942mcpsimp"><a name="p7942mcpsimp"></a><a name="p7942mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row7943mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p7945mcpsimp"><a name="p7945mcpsimp"></a><a name="p7945mcpsimp"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p7947mcpsimp"><a name="p7947mcpsimp"></a><a name="p7947mcpsimp"></a><strong id="b115531532183117"><a name="b115531532183117"></a><a name="b115531532183117"></a>true</strong> if the my-location icon is enabled; <strong id="b0793152016311"><a name="b0793152016311"></a><a name="b0793152016311"></a>false</strong> otherwise.</p>
</td>
</tr>
</tbody>
</table>

## isRotateGesturesEnabled<a name="section2532125605311"></a>

<a name="table7949mcpsimp"></a>
<table><thead align="left"><tr id="row7953mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p7955mcpsimp"><a name="p7955mcpsimp"></a><a name="p7955mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row7956mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p7958mcpsimp"><a name="p7958mcpsimp"></a><a name="p7958mcpsimp"></a>public boolean isRotateGesturesEnabled()</p>
<p id="p7961mcpsimp"><a name="p7961mcpsimp"></a><a name="p7961mcpsimp"></a>Checks whether rotation gestures are enabled for a map.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table7967mcpsimp"></a>
<table><thead align="left"><tr id="row7972mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p7974mcpsimp"><a name="p7974mcpsimp"></a><a name="p7974mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p7976mcpsimp"><a name="p7976mcpsimp"></a><a name="p7976mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row7977mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p7979mcpsimp"><a name="p7979mcpsimp"></a><a name="p7979mcpsimp"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p7981mcpsimp"><a name="p7981mcpsimp"></a><a name="p7981mcpsimp"></a><strong id="b195731048143113"><a name="b195731048143113"></a><a name="b195731048143113"></a>true</strong> if rotation gestures are enabled; <strong id="b55801848143115"><a name="b55801848143115"></a><a name="b55801848143115"></a>false</strong> otherwise.</p>
</td>
</tr>
</tbody>
</table>

## isScrollGesturesEnabled<a name="section1538712317544"></a>

<a name="table7983mcpsimp"></a>
<table><thead align="left"><tr id="row7987mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p7989mcpsimp"><a name="p7989mcpsimp"></a><a name="p7989mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row7990mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p7992mcpsimp"><a name="p7992mcpsimp"></a><a name="p7992mcpsimp"></a>public boolean isScrollGesturesEnabled()</p>
<p id="p7995mcpsimp"><a name="p7995mcpsimp"></a><a name="p7995mcpsimp"></a>Checks whether scroll gestures are enabled for a map.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table8001mcpsimp"></a>
<table><thead align="left"><tr id="row8006mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p8008mcpsimp"><a name="p8008mcpsimp"></a><a name="p8008mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p8010mcpsimp"><a name="p8010mcpsimp"></a><a name="p8010mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row8011mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p8013mcpsimp"><a name="p8013mcpsimp"></a><a name="p8013mcpsimp"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p8015mcpsimp"><a name="p8015mcpsimp"></a><a name="p8015mcpsimp"></a><strong id="b9557231143215"><a name="b9557231143215"></a><a name="b9557231143215"></a>true</strong> if scroll gestures are enabled; <strong id="b1795514185326"><a name="b1795514185326"></a><a name="b1795514185326"></a>false</strong> otherwise.</p>
</td>
</tr>
</tbody>
</table>

## isScrollGesturesEnabledDuringRotateOrZoom<a name="section1985001713554"></a>

<a name="table8017mcpsimp"></a>
<table><thead align="left"><tr id="row8021mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p8023mcpsimp"><a name="p8023mcpsimp"></a><a name="p8023mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row8024mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p8026mcpsimp"><a name="p8026mcpsimp"></a><a name="p8026mcpsimp"></a>public boolean isScrollGesturesEnabledDuringRotateOrZoom()</p>
<p id="p8029mcpsimp"><a name="p8029mcpsimp"></a><a name="p8029mcpsimp"></a>Checks whether scroll gestures are enabled during rotation or zooming.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table8035mcpsimp"></a>
<table><thead align="left"><tr id="row8040mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p8042mcpsimp"><a name="p8042mcpsimp"></a><a name="p8042mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p8044mcpsimp"><a name="p8044mcpsimp"></a><a name="p8044mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row8045mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p8047mcpsimp"><a name="p8047mcpsimp"></a><a name="p8047mcpsimp"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p8049mcpsimp"><a name="p8049mcpsimp"></a><a name="p8049mcpsimp"></a><strong id="b12155193312"><a name="b12155193312"></a><a name="b12155193312"></a>true</strong> if scroll gestures are enabled during rotation or zooming; <strong id="b1025814320"><a name="b1025814320"></a><a name="b1025814320"></a>false</strong> otherwise.</p>
</td>
</tr>
</tbody>
</table>

## isTiltGesturesEnabled<a name="section41913572555"></a>

<a name="table8051mcpsimp"></a>
<table><thead align="left"><tr id="row8055mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p8057mcpsimp"><a name="p8057mcpsimp"></a><a name="p8057mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row8058mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p8060mcpsimp"><a name="p8060mcpsimp"></a><a name="p8060mcpsimp"></a>public boolean isTiltGesturesEnabled()</p>
<p id="p8063mcpsimp"><a name="p8063mcpsimp"></a><a name="p8063mcpsimp"></a>Checks whether tilt gestures are enabled for a map.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table8069mcpsimp"></a>
<table><thead align="left"><tr id="row8074mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p8076mcpsimp"><a name="p8076mcpsimp"></a><a name="p8076mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p8078mcpsimp"><a name="p8078mcpsimp"></a><a name="p8078mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row8079mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p8081mcpsimp"><a name="p8081mcpsimp"></a><a name="p8081mcpsimp"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p8083mcpsimp"><a name="p8083mcpsimp"></a><a name="p8083mcpsimp"></a><strong id="b112921324163317"><a name="b112921324163317"></a><a name="b112921324163317"></a>true</strong> if tilt gestures are enabled; <strong id="b891342093312"><a name="b891342093312"></a><a name="b891342093312"></a>false</strong> otherwise.</p>
</td>
</tr>
</tbody>
</table>

## isZoomControlsEnabled<a name="section3339153125618"></a>

<a name="table8085mcpsimp"></a>
<table><thead align="left"><tr id="row8089mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p8091mcpsimp"><a name="p8091mcpsimp"></a><a name="p8091mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row8092mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p8094mcpsimp"><a name="p8094mcpsimp"></a><a name="p8094mcpsimp"></a>public boolean isZoomControlsEnabled()</p>
<p id="p982144316566"><a name="p982144316566"></a><a name="p982144316566"></a>Checks whether zoom controls are enabled.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table8103mcpsimp"></a>
<table><thead align="left"><tr id="row8108mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p8110mcpsimp"><a name="p8110mcpsimp"></a><a name="p8110mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p8112mcpsimp"><a name="p8112mcpsimp"></a><a name="p8112mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row8113mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p8115mcpsimp"><a name="p8115mcpsimp"></a><a name="p8115mcpsimp"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p8117mcpsimp"><a name="p8117mcpsimp"></a><a name="p8117mcpsimp"></a><strong id="b382705363318"><a name="b382705363318"></a><a name="b382705363318"></a>true</strong> if zoom controls are enabled; <strong id="b1858254814333"><a name="b1858254814333"></a><a name="b1858254814333"></a>false</strong> otherwise.</p>
</td>
</tr>
</tbody>
</table>

## isZoomGesturesEnabled<a name="section2603185155713"></a>

<a name="table8119mcpsimp"></a>
<table><thead align="left"><tr id="row8123mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p8125mcpsimp"><a name="p8125mcpsimp"></a><a name="p8125mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row8126mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p8128mcpsimp"><a name="p8128mcpsimp"></a><a name="p8128mcpsimp"></a>public boolean isZoomGesturesEnabled()</p>
<p id="p8131mcpsimp"><a name="p8131mcpsimp"></a><a name="p8131mcpsimp"></a>Checks whether zoom gestures are enabled for a map.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table8137mcpsimp"></a>
<table><thead align="left"><tr id="row8142mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p8144mcpsimp"><a name="p8144mcpsimp"></a><a name="p8144mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p8146mcpsimp"><a name="p8146mcpsimp"></a><a name="p8146mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row8147mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p8149mcpsimp"><a name="p8149mcpsimp"></a><a name="p8149mcpsimp"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p8151mcpsimp"><a name="p8151mcpsimp"></a><a name="p8151mcpsimp"></a><strong id="b1695312093414"><a name="b1695312093414"></a><a name="b1695312093414"></a>true</strong> if zoom gestures are enabled; <strong id="b112511716347"><a name="b112511716347"></a><a name="b112511716347"></a>false</strong> otherwise.</p>
</td>
</tr>
</tbody>
</table>

## setAllGesturesEnabled<a name="section32351948185710"></a>

<a name="table8153mcpsimp"></a>
<table><thead align="left"><tr id="row8157mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p8159mcpsimp"><a name="p8159mcpsimp"></a><a name="p8159mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row8160mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p8162mcpsimp"><a name="p8162mcpsimp"></a><a name="p8162mcpsimp"></a>public void setAllGesturesEnabled(boolean enabled)</p>
<p id="p8165mcpsimp"><a name="p8165mcpsimp"></a><a name="p8165mcpsimp"></a>Sets whether to enable all gestures for a map.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table8168mcpsimp"></a>
<table><thead align="left"><tr id="row8173mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p8175mcpsimp"><a name="p8175mcpsimp"></a><a name="p8175mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p8177mcpsimp"><a name="p8177mcpsimp"></a><a name="p8177mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row8178mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p8180mcpsimp"><a name="p8180mcpsimp"></a><a name="p8180mcpsimp"></a>enabled</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p8182mcpsimp"><a name="p8182mcpsimp"></a><a name="p8182mcpsimp"></a>Indicates whether to enable all gestures. <strong id="b17866951123415"><a name="b17866951123415"></a><a name="b17866951123415"></a>true</strong>: yes; <strong id="b587675118345"><a name="b587675118345"></a><a name="b587675118345"></a>false</strong>: no.</p>
</td>
</tr>
</tbody>
</table>

## setCompassEnabled<a name="section129811026105811"></a>

<a name="table8187mcpsimp"></a>
<table><thead align="left"><tr id="row8191mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p8193mcpsimp"><a name="p8193mcpsimp"></a><a name="p8193mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row8194mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p8196mcpsimp"><a name="p8196mcpsimp"></a><a name="p8196mcpsimp"></a>public void setCompassEnabled(boolean enabled)</p>
<p id="p8199mcpsimp"><a name="p8199mcpsimp"></a><a name="p8199mcpsimp"></a>Sets whether to enable the compass for a map. If the compass is enabled and the map is not oriented to the due north, a compass icon is displayed in the upper right corner of the map. A user can tap the compass icon to rotate the map to be oriented to the due north. If the compass is enabled and the map is oriented to the due north, the compass icon is hidden. If the compass is disabled, the compass icon will never be displayed.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table8202mcpsimp"></a>
<table><thead align="left"><tr id="row8207mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p8209mcpsimp"><a name="p8209mcpsimp"></a><a name="p8209mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p8211mcpsimp"><a name="p8211mcpsimp"></a><a name="p8211mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row8212mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p8214mcpsimp"><a name="p8214mcpsimp"></a><a name="p8214mcpsimp"></a>enabled</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p8216mcpsimp"><a name="p8216mcpsimp"></a><a name="p8216mcpsimp"></a>Indicates whether to enable the compass. <strong id="b16614831163710"><a name="b16614831163710"></a><a name="b16614831163710"></a>true</strong> (default): yes; <strong id="b76141531133715"><a name="b76141531133715"></a><a name="b76141531133715"></a>false</strong>: no.</p>
</td>
</tr>
</tbody>
</table>

## setGestureScaleByMapCenter<a name="section8176121651612"></a>

<a name="table141763163162"></a>
<table><thead align="left"><tr id="row3176416201610"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p14176141631619"><a name="p14176141631619"></a><a name="p14176141631619"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row31761216121611"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p0176171671615"><a name="p0176171671615"></a><a name="p0176171671615"></a>public void setGestureScaleByMapCenter(boolean enabled)</p>
<p id="p1477020164410"><a name="p1477020164410"></a><a name="p1477020164410"></a>Specifies whether a fixed screen center can be set for zooming. If the function is enabled, the map will be zoomed based on the passed fixed screen center. If the function is disabled, the map will be zoomed based on the tap point on the screen. You can call the <a href="huaweimap.md#section63930559559">HuaweiMap.setPointToCenter</a><strong id="b13173137184719"><a name="b13173137184719"></a><a name="b13173137184719"></a>(int x,int y)</strong> method to set the screen center coordinates.</p>
<div class="caution" id="note1654252619446"><a name="note1654252619446"></a><a name="note1654252619446"></a><span class="cautiontitle"> CAUTION: </span><div class="cautionbody"><p id="p12542426144413"><a name="p12542426144413"></a><a name="p12542426144413"></a>The passed screen center is valid only when <strong id="b223719531479"><a name="b223719531479"></a><a name="b223719531479"></a>true</strong> is passed to <a href="#section8176121651612">setGestureScaleByMapCenter</a><strong id="b3238165315471"><a name="b3238165315471"></a><a name="b3238165315471"></a>(boolean enabled)</strong> in advance. To cancel the function of setting a fixed screen center, you only need to pass <strong id="b16238175304719"><a name="b16238175304719"></a><a name="b16238175304719"></a>false</strong> to <a href="#section8176121651612">setGestureScaleByMapCenter</a><strong id="b11238653124712"><a name="b11238653124712"></a><a name="b11238653124712"></a>(boolean enabled)</strong> without calling <a href="huaweimap.md#section63930559559">HuaweiMap.setPointToCenter</a><strong id="b423965318471"><a name="b423965318471"></a><a name="b423965318471"></a>(int x,int y)</strong>. </p>
</div></div>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table41775165161"></a>
<table><thead align="left"><tr id="row131775163163"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p19177161601617"><a name="p19177161601617"></a><a name="p19177161601617"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p51773162160"><a name="p51773162160"></a><a name="p51773162160"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row111777165164"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p131778165169"><a name="p131778165169"></a><a name="p131778165169"></a>enabled</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p161772016131612"><a name="p161772016131612"></a><a name="p161772016131612"></a>The value <strong id="b1933520263115"><a name="b1933520263115"></a><a name="b1933520263115"></a>true</strong> indicates to zoom the map based on the fixed screen center. The value <strong id="b928285810319"><a name="b928285810319"></a><a name="b928285810319"></a>false</strong> indicates to zoom the map based on the tap point on the screen. The default value is <strong id="b10952155112323"><a name="b10952155112323"></a><a name="b10952155112323"></a>false</strong>.</p>
</td>
</tr>
</tbody>
</table>

## setMarkerClusterColor<a name="section11137745113915"></a>

<a name="table0137174543917"></a>
<table><thead align="left"><tr id="row1413714513396"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p19137645193912"><a name="p19137645193912"></a><a name="p19137645193912"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row51385455398"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p1513815453395"><a name="p1513815453395"></a><a name="p1513815453395"></a>public void setMarkerClusterColor(int color)</p>
<p id="p101381145183914"><a name="p101381145183914"></a><a name="p101381145183914"></a>Sets the color of the default cluster marker.</p>
<div class="note" id="note9849167192316"><a name="note9849167192316"></a><a name="note9849167192316"></a><span class="notetitle"> NOTE: </span><div class="notebody"><p id="p1284977122320"><a name="p1284977122320"></a><a name="p1284977122320"></a>The color value is in ARGB format.</p>
</div></div>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table20138114563919"></a>
<table><thead align="left"><tr id="row161391845113919"><th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.1"><p id="p1713944517397"><a name="p1713944517397"></a><a name="p1713944517397"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.2"><p id="p18139745183910"><a name="p18139745183910"></a><a name="p18139745183910"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row161391455396"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p4139184593911"><a name="p4139184593911"></a><a name="p4139184593911"></a>color</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p21392453398"><a name="p21392453398"></a><a name="p21392453398"></a>Color of the default cluster marker.</p>
</td>
</tr>
</tbody>
</table>

## setMarkerClusterIcon<a name="section72972050124113"></a>

<a name="table429811502410"></a>
<table><thead align="left"><tr id="row13298650104113"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p16298115044116"><a name="p16298115044116"></a><a name="p16298115044116"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row72981550114112"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p729875010418"><a name="p729875010418"></a><a name="p729875010418"></a>public void setMarkerClusterIcon(<a href="bitmapdescriptor.md">BitmapDescriptor</a> iconDescriptor)</p>
<p id="p10298185014414"><a name="p10298185014414"></a><a name="p10298185014414"></a>Sets the icon of the custom cluster marker.</p>
<div class="note" id="note127581416203518"><a name="note127581416203518"></a><a name="note127581416203518"></a><span class="notetitle"> NOTE: </span><div class="notebody"><p id="p87581716163516"><a name="p87581716163516"></a><a name="p87581716163516"></a>If the <strong id="b06133509244"><a name="b06133509244"></a><a name="b06133509244"></a>bitmapDescriptor</strong> parameter is empty for the <a href="#section72972050124113">setMarkerClusterIcon</a> method, the color, image, and text color of the cluster marker set using <a href="#section11137745113915">setMarkerClusterColor</a>, <a href="#section72972050124113">setMarkerClusterIcon</a>, and <a href="#section3137125684216">setMarkerClusterTextColor</a> will be cleared. In this case, the default cluster marker style will be used.</p>
</div></div>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table32992501415"></a>
<table><thead align="left"><tr id="row142991950144116"><th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.1"><p id="p18299135094118"><a name="p18299135094118"></a><a name="p18299135094118"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.2"><p id="p6299750144119"><a name="p6299750144119"></a><a name="p6299750144119"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row1729925014118"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p112995500415"><a name="p112995500415"></a><a name="p112995500415"></a>iconDescriptor</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p1129917505418"><a name="p1129917505418"></a><a name="p1129917505418"></a>Icon of the custom cluster marker.</p>
</td>
</tr>
</tbody>
</table>

## setMarkerClusterTextColor<a name="section3137125684216"></a>

<a name="table21381756124220"></a>
<table><thead align="left"><tr id="row18138456194214"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p1413811568426"><a name="p1413811568426"></a><a name="p1413811568426"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row181388563421"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p61389563421"><a name="p61389563421"></a><a name="p61389563421"></a>public void setMarkerClusterTextColor(int color)</p>
<p id="p12138125611428"><a name="p12138125611428"></a><a name="p12138125611428"></a>Sets the text color of the custom cluster marker.</p>
<div class="note" id="note999016246271"><a name="note999016246271"></a><a name="note999016246271"></a><span class="notetitle"> NOTE: </span><div class="notebody"><p id="p189913241271"><a name="p189913241271"></a><a name="p189913241271"></a>The color value is in ARGB format.</p>
</div></div>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table21381256164213"></a>
<table><thead align="left"><tr id="row113919560422"><th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.1"><p id="p18139105617425"><a name="p18139105617425"></a><a name="p18139105617425"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.2"><p id="p121392564423"><a name="p121392564423"></a><a name="p121392564423"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row31391567420"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p14139185644213"><a name="p14139185644213"></a><a name="p14139185644213"></a>color</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p16139175634220"><a name="p16139175634220"></a><a name="p16139175634220"></a>Text color of the custom cluster marker.</p>
</td>
</tr>
</tbody>
</table>

## setMyLocationButtonEnabled<a name="section1530742525919"></a>

<a name="table8221mcpsimp"></a>
<table><thead align="left"><tr id="row8225mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p8227mcpsimp"><a name="p8227mcpsimp"></a><a name="p8227mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row8228mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p8230mcpsimp"><a name="p8230mcpsimp"></a><a name="p8230mcpsimp"></a>public void setMyLocationButtonEnabled(boolean enabled)</p>
<p id="p8233mcpsimp"><a name="p8233mcpsimp"></a><a name="p8233mcpsimp"></a>Sets whether to enable the my-location icon for a map. Before calling this method, you need to call the <a href="huaweimap.md#section672514559310">setMyLocationEnabled</a> method of <a href="huaweimap.md">HuaweiMap</a> to enable the may-location layer.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table8236mcpsimp"></a>
<table><thead align="left"><tr id="row8241mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p8243mcpsimp"><a name="p8243mcpsimp"></a><a name="p8243mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p8245mcpsimp"><a name="p8245mcpsimp"></a><a name="p8245mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row8246mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p8248mcpsimp"><a name="p8248mcpsimp"></a><a name="p8248mcpsimp"></a>enabled</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p8250mcpsimp"><a name="p8250mcpsimp"></a><a name="p8250mcpsimp"></a>Indicates whether to enable the my-location icon. <strong id="b8205919173912"><a name="b8205919173912"></a><a name="b8205919173912"></a>true</strong>: yes; <strong id="b5205181911391"><a name="b5205181911391"></a><a name="b5205181911391"></a>false</strong>: no. The default value is <strong id="b962583511427"><a name="b962583511427"></a><a name="b962583511427"></a>true</strong>.</p>
</td>
</tr>
</tbody>
</table>

## setRotateGesturesEnabled<a name="section6840881108"></a>

<a name="table8255mcpsimp"></a>
<table><thead align="left"><tr id="row8259mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p8261mcpsimp"><a name="p8261mcpsimp"></a><a name="p8261mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row8262mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p8264mcpsimp"><a name="p8264mcpsimp"></a><a name="p8264mcpsimp"></a>public void setRotateGesturesEnabled(boolean enabled)</p>
<p id="p99610521908"><a name="p99610521908"></a><a name="p99610521908"></a>Sets whether to enable rotation gestures for a map.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table8270mcpsimp"></a>
<table><thead align="left"><tr id="row8275mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p8277mcpsimp"><a name="p8277mcpsimp"></a><a name="p8277mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p8279mcpsimp"><a name="p8279mcpsimp"></a><a name="p8279mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row8280mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p8282mcpsimp"><a name="p8282mcpsimp"></a><a name="p8282mcpsimp"></a>enabled</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p8284mcpsimp"><a name="p8284mcpsimp"></a><a name="p8284mcpsimp"></a>Indicates whether to enable rotation gestures. <strong id="b1149019330397"><a name="b1149019330397"></a><a name="b1149019330397"></a>true</strong>: yes; <strong id="b34901338395"><a name="b34901338395"></a><a name="b34901338395"></a>false</strong>: no.</p>
</td>
</tr>
</tbody>
</table>

## setScrollGesturesEnabled<a name="section1923864410016"></a>

<a name="table8289mcpsimp"></a>
<table><thead align="left"><tr id="row8293mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p8295mcpsimp"><a name="p8295mcpsimp"></a><a name="p8295mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row8296mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p8298mcpsimp"><a name="p8298mcpsimp"></a><a name="p8298mcpsimp"></a>public void setScrollGesturesEnabled(boolean enabled)</p>
<p id="p8301mcpsimp"><a name="p8301mcpsimp"></a><a name="p8301mcpsimp"></a>Sets whether to enable scroll gestures for a map.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table8304mcpsimp"></a>
<table><thead align="left"><tr id="row8309mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p8311mcpsimp"><a name="p8311mcpsimp"></a><a name="p8311mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p8313mcpsimp"><a name="p8313mcpsimp"></a><a name="p8313mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row8314mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p8316mcpsimp"><a name="p8316mcpsimp"></a><a name="p8316mcpsimp"></a>enabled</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p8318mcpsimp"><a name="p8318mcpsimp"></a><a name="p8318mcpsimp"></a>Indicates whether to enable scroll gestures. <strong id="b4940165012392"><a name="b4940165012392"></a><a name="b4940165012392"></a>true</strong>: yes; <strong id="b994065083919"><a name="b994065083919"></a><a name="b994065083919"></a>false</strong>: no.</p>
</td>
</tr>
</tbody>
</table>

## setScrollGesturesEnabledDuringRotateOrZoom<a name="section169705158119"></a>

<a name="table8323mcpsimp"></a>
<table><thead align="left"><tr id="row8327mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p8329mcpsimp"><a name="p8329mcpsimp"></a><a name="p8329mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row8330mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p8332mcpsimp"><a name="p8332mcpsimp"></a><a name="p8332mcpsimp"></a>public void setScrollGesturesEnabledDuringRotateOrZoom(boolean enabled)</p>
<p id="p7989113017111"><a name="p7989113017111"></a><a name="p7989113017111"></a>Sets whether to enable scroll gestures during rotation or zooming.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table8338mcpsimp"></a>
<table><thead align="left"><tr id="row8343mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p8345mcpsimp"><a name="p8345mcpsimp"></a><a name="p8345mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p8347mcpsimp"><a name="p8347mcpsimp"></a><a name="p8347mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row8348mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p8350mcpsimp"><a name="p8350mcpsimp"></a><a name="p8350mcpsimp"></a>enabled</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p8352mcpsimp"><a name="p8352mcpsimp"></a><a name="p8352mcpsimp"></a>Indicates whether to enable scroll gestures during rotation or zooming. <strong id="b1275633104019"><a name="b1275633104019"></a><a name="b1275633104019"></a>true</strong>: yes; <strong id="b6275333114020"><a name="b6275333114020"></a><a name="b6275333114020"></a>false</strong>: no.</p>
</td>
</tr>
</tbody>
</table>

## setTiltGesturesEnabled<a name="section11471236212"></a>

<a name="table8357mcpsimp"></a>
<table><thead align="left"><tr id="row8361mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p8363mcpsimp"><a name="p8363mcpsimp"></a><a name="p8363mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row8364mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p8366mcpsimp"><a name="p8366mcpsimp"></a><a name="p8366mcpsimp"></a>public void setTiltGesturesEnabled(boolean enabled)</p>
<p id="p397353619214"><a name="p397353619214"></a><a name="p397353619214"></a>Sets whether to enable tilt gestures for a map. If tilt gestures are enabled, users can use two fingers to swipe up vertically to tilt the camera. If tilt gestures are disabled, users cannot use gestures to tilt the camera.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table8372mcpsimp"></a>
<table><thead align="left"><tr id="row8377mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p8379mcpsimp"><a name="p8379mcpsimp"></a><a name="p8379mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p8381mcpsimp"><a name="p8381mcpsimp"></a><a name="p8381mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row8382mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p8384mcpsimp"><a name="p8384mcpsimp"></a><a name="p8384mcpsimp"></a>enabled</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p8386mcpsimp"><a name="p8386mcpsimp"></a><a name="p8386mcpsimp"></a>Indicates whether to enable tilt gestures. <strong id="b469519164118"><a name="b469519164118"></a><a name="b469519164118"></a>true</strong> (default): yes; <strong id="b116951918412"><a name="b116951918412"></a><a name="b116951918412"></a>false</strong>: no.</p>
</td>
</tr>
</tbody>
</table>

## setZoomControlsEnabled<a name="section185278164314"></a>

<a name="table8391mcpsimp"></a>
<table><thead align="left"><tr id="row8395mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p8397mcpsimp"><a name="p8397mcpsimp"></a><a name="p8397mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row8398mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p8400mcpsimp"><a name="p8400mcpsimp"></a><a name="p8400mcpsimp"></a>public void setZoomControlsEnabled(boolean enabled)</p>
<p id="p8403mcpsimp"><a name="p8403mcpsimp"></a><a name="p8403mcpsimp"></a>Sets whether to enable zoom controls for a map.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table8406mcpsimp"></a>
<table><thead align="left"><tr id="row8411mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p8413mcpsimp"><a name="p8413mcpsimp"></a><a name="p8413mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p8415mcpsimp"><a name="p8415mcpsimp"></a><a name="p8415mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row8416mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p8418mcpsimp"><a name="p8418mcpsimp"></a><a name="p8418mcpsimp"></a>enabled</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p8420mcpsimp"><a name="p8420mcpsimp"></a><a name="p8420mcpsimp"></a>Indicates whether to enable zoom controls. <strong id="b1098505111424"><a name="b1098505111424"></a><a name="b1098505111424"></a>true</strong>: yes; <strong id="b1998585174219"><a name="b1998585174219"></a><a name="b1998585174219"></a>false</strong>: no.</p>
</td>
</tr>
</tbody>
</table>

## setZoomGesturesEnabled<a name="section12131521337"></a>

<a name="table8425mcpsimp"></a>
<table><thead align="left"><tr id="row8429mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p8431mcpsimp"><a name="p8431mcpsimp"></a><a name="p8431mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row8432mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p8434mcpsimp"><a name="p8434mcpsimp"></a><a name="p8434mcpsimp"></a>public void setZoomGesturesEnabled(boolean enabled)</p>
<p id="p169112720412"><a name="p169112720412"></a><a name="p169112720412"></a>Sets whether to enable zoom gestures for a map.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table8440mcpsimp"></a>
<table><thead align="left"><tr id="row8445mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p8447mcpsimp"><a name="p8447mcpsimp"></a><a name="p8447mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p8449mcpsimp"><a name="p8449mcpsimp"></a><a name="p8449mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row8450mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p8452mcpsimp"><a name="p8452mcpsimp"></a><a name="p8452mcpsimp"></a>enabled</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p8454mcpsimp"><a name="p8454mcpsimp"></a><a name="p8454mcpsimp"></a>Indicates whether to enable zoom gestures. <strong id="b165822694318"><a name="b165822694318"></a><a name="b165822694318"></a>true</strong>: yes; <strong id="b758213624314"><a name="b758213624314"></a><a name="b758213624314"></a>false</strong>: no.</p>
</td>
</tr>
</tbody>
</table>

