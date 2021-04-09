# MarkerOptions<a name="ZH-CN_TOPIC_0000001145941087"></a>

-   [Public Constructor Summary](#section555713615148)
-   [Public Method Summary](#section4327440131410)
-   [Public Methods](#section1411112224221)
-   [alpha](#section34311726293)
-   [anchor](#section1326516357302)
-   [anchorMarker](#section95121330125810)
-   [clusterable](#section99273302577)
-   [draggable](#section0702145819302)
-   [flat](#section2727192393111)
-   [getAlpha](#section1832455019318)
-   [getAnchorU](#section155871213163216)
-   [getMarkerAnchorU](#section1930718125268)
-   [getAnchorV](#section42741744163220)
-   [getMarkerAnchorV](#section3991833123317)
-   [getIcon](#section168698343319)
-   [getInfoWindowAnchorU](#section155505241338)
-   [getInfoWindowAnchorV](#section133371542203315)
-   [getPosition](#section4923215113418)
-   [getRotation](#section7334736113412)
-   [getSnippet](#section1305114363414)
-   [getTitle](#section109271048183419)
-   [getZIndex](#section1060212123512)
-   [icon](#section4119596355)
-   [infoWindowAnchor](#section114908172352)
-   [isDraggable](#section8566122333511)
-   [isFlat](#section7919729183512)
-   [ismClusterable](#section147631875440)
-   [isVisible](#section1952123613518)
-   [position](#section339524313354)
-   [rotation](#section1986735018353)
-   [snippet](#section1266276203610)
-   [title](#section144310304569)
-   [visible](#section47301652195614)
-   [zIndex](#section551291175715)


<a name="table15800mcpsimp"></a>
<table><thead align="left"><tr id="row15804mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p15806mcpsimp"><a name="p15806mcpsimp"></a><a name="p15806mcpsimp"></a>Class Info</p>
</th>
</tr>
</thead>
<tbody><tr id="row15807mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p767873684110"><a name="p767873684110"></a><a name="p767873684110"></a>public class MarkerOptions</p>
<p id="p15809mcpsimp"><a name="p15809mcpsimp"></a><a name="p15809mcpsimp"></a>用于定义标记属性的类。</p>
</td>
</tr>
</tbody>
</table>

## Public Constructor Summary<a name="section555713615148"></a>

<a name="table15813mcpsimp"></a>
<table><thead align="left"><tr id="row15817mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p145mcpsimp"><a name="p145mcpsimp"></a><a name="p145mcpsimp"></a>Constructor Name</p>
</th>
</tr>
</thead>
<tbody><tr id="row15820mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p15822mcpsimp"><a name="p15822mcpsimp"></a><a name="p15822mcpsimp"></a><a href="markeroptions.md">MarkerOptions</a>()</p>
<p id="p19669102553514"><a name="p19669102553514"></a><a name="p19669102553514"></a>MarkerOptions类的默认构造方法。</p>
</td>
</tr>
</tbody>
</table>

## Public Method Summary<a name="section4327440131410"></a>

<a name="table15824mcpsimp"></a>
<table><thead align="left"><tr id="row15829mcpsimp"><th class="cellrowborder" valign="top" width="40%" id="mcps1.1.3.1.1"><p id="p081120285386"><a name="p081120285386"></a><a name="p081120285386"></a>Qualifier and Type</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.1.3.1.2"><p id="p681112883813"><a name="p681112883813"></a><a name="p681112883813"></a>Method Name and Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row15834mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p15836mcpsimp"><a name="p15836mcpsimp"></a><a name="p15836mcpsimp"></a><a href="markeroptions.md">MarkerOptions</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p15838mcpsimp"><a name="p15838mcpsimp"></a><a name="p15838mcpsimp"></a><a href="#section34311726293">alpha</a>(float alpha)</p>
<p id="p175951340102617"><a name="p175951340102617"></a><a name="p175951340102617"></a>设置标记的透明度。</p>
</td>
</tr>
<tr id="row15839mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p15841mcpsimp"><a name="p15841mcpsimp"></a><a name="p15841mcpsimp"></a><a href="markeroptions.md">MarkerOptions</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p15843mcpsimp"><a name="p15843mcpsimp"></a><a name="p15843mcpsimp"></a><a href="#section1326516357302">anchor</a>(float u, float v)</p>
<p id="p951513412262"><a name="p951513412262"></a><a name="p951513412262"></a>设置标记的锚点位置。</p>
<div class="caution" id="note594614537569"><a name="note594614537569"></a><a name="note594614537569"></a><span class="cautiontitle"> 注意： </span><div class="cautionbody"><p id="p1294635315617"><a name="p1294635315617"></a><a name="p1294635315617"></a>该接口已弃用，设置锚点位置请使用<a href="#section95121330125810">anchorMarker</a>。</p>
</div></div>
</td>
</tr>
<tr id="row956244355712"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p185632435579"><a name="p185632435579"></a><a name="p185632435579"></a><a href="markeroptions.md">MarkerOptions</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p95631743145712"><a name="p95631743145712"></a><a name="p95631743145712"></a><a href="#section95121330125810">anchorMarker</a>(float anchorU, float anchorV)</p>
<p id="p93811642192617"><a name="p93811642192617"></a><a name="p93811642192617"></a>设置标记的锚点位置。</p>
</td>
</tr>
<tr id="row71930274218"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p15966mcpsimp"><a name="p15966mcpsimp"></a><a name="p15966mcpsimp"></a><a href="markeroptions.md">MarkerOptions</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p15968mcpsimp"><a name="p15968mcpsimp"></a><a name="p15968mcpsimp"></a><a href="#section99273302577">clusterable</a>(boolean clusterable)</p>
<p id="p1962834312611"><a name="p1962834312611"></a><a name="p1962834312611"></a>设置标记的聚合属性。</p>
</td>
</tr>
<tr id="row15844mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p15846mcpsimp"><a name="p15846mcpsimp"></a><a name="p15846mcpsimp"></a><a href="markeroptions.md">MarkerOptions</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p15848mcpsimp"><a name="p15848mcpsimp"></a><a name="p15848mcpsimp"></a><a href="#section0702145819302">draggable</a>(boolean draggable)</p>
<p id="p686213441267"><a name="p686213441267"></a><a name="p686213441267"></a>设置标记是否可以通过长按来拖拽。</p>
</td>
</tr>
<tr id="row15849mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p15851mcpsimp"><a name="p15851mcpsimp"></a><a name="p15851mcpsimp"></a><a href="markeroptions.md">MarkerOptions</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p15853mcpsimp"><a name="p15853mcpsimp"></a><a name="p15853mcpsimp"></a><a href="#section2727192393111">flat</a>(boolean flat)</p>
<p id="p18859545152616"><a name="p18859545152616"></a><a name="p18859545152616"></a>设置标记是否平贴地图。</p>
</td>
</tr>
<tr id="row15854mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p15856mcpsimp"><a name="p15856mcpsimp"></a><a name="p15856mcpsimp"></a>float</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p15858mcpsimp"><a name="p15858mcpsimp"></a><a name="p15858mcpsimp"></a><a href="#section1832455019318">getAlpha</a>()</p>
<p id="p01734714263"><a name="p01734714263"></a><a name="p01734714263"></a>获取标记的透明度。</p>
</td>
</tr>
<tr id="row15859mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p15861mcpsimp"><a name="p15861mcpsimp"></a><a name="p15861mcpsimp"></a>float</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p15863mcpsimp"><a name="p15863mcpsimp"></a><a name="p15863mcpsimp"></a><a href="#section155871213163216">getAnchorU</a>()</p>
<p id="p095624722615"><a name="p095624722615"></a><a name="p095624722615"></a>获取标记锚点在水平范围的比例。</p>
<div class="caution" id="note5109355185719"><a name="note5109355185719"></a><a name="note5109355185719"></a><span class="cautiontitle"> 注意： </span><div class="cautionbody"><p id="p2109155595720"><a name="p2109155595720"></a><a name="p2109155595720"></a>该接口已弃用，获取标记锚点在水平范围的比例请使用<a href="#section1930718125268">getMarkerAnchorU</a>。</p>
</div></div>
</td>
</tr>
<tr id="row19254554203116"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p725425433115"><a name="p725425433115"></a><a name="p725425433115"></a>float</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p1525411544310"><a name="p1525411544310"></a><a name="p1525411544310"></a><a href="#section1930718125268">getMarkerAnchorU</a>()</p>
<p id="p1054015490266"><a name="p1054015490266"></a><a name="p1054015490266"></a>获取标记锚点在水平范围的比例。</p>
</td>
</tr>
<tr id="row15864mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p15866mcpsimp"><a name="p15866mcpsimp"></a><a name="p15866mcpsimp"></a>float</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p15868mcpsimp"><a name="p15868mcpsimp"></a><a name="p15868mcpsimp"></a><a href="#section42741744163220">getAnchorV</a>()</p>
<p id="p462125032616"><a name="p462125032616"></a><a name="p462125032616"></a>获取标记锚点在垂直范围的比例。</p>
<div class="caution" id="note14582023105915"><a name="note14582023105915"></a><a name="note14582023105915"></a><span class="cautiontitle"> 注意： </span><div class="cautionbody"><p id="p18458132316590"><a name="p18458132316590"></a><a name="p18458132316590"></a>该接口已弃用，获取标记锚点在垂直范围的比例请使用<a href="#section3991833123317">getMarkerAnchorV</a>。</p>
</div></div>
</td>
</tr>
<tr id="row03412571358"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p63411957123511"><a name="p63411957123511"></a><a name="p63411957123511"></a>float</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p034215711357"><a name="p034215711357"></a><a name="p034215711357"></a><a href="#section3991833123317">getMarkerAnchorV</a>()</p>
<p id="p13494751132617"><a name="p13494751132617"></a><a name="p13494751132617"></a>获取标记锚点在垂直范围的比例。</p>
</td>
</tr>
<tr id="row15869mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p15871mcpsimp"><a name="p15871mcpsimp"></a><a name="p15871mcpsimp"></a><a href="bitmapdescriptor.md">BitmapDescriptor</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p15873mcpsimp"><a name="p15873mcpsimp"></a><a name="p15873mcpsimp"></a><a href="#section168698343319">getIcon</a>()</p>
<p id="p153317524263"><a name="p153317524263"></a><a name="p153317524263"></a>获取到标记的图标。</p>
</td>
</tr>
<tr id="row15874mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p15876mcpsimp"><a name="p15876mcpsimp"></a><a name="p15876mcpsimp"></a>float</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p15878mcpsimp"><a name="p15878mcpsimp"></a><a name="p15878mcpsimp"></a><a href="#section155505241338">getInfoWindowAnchorU</a>()</p>
<p id="p194320535266"><a name="p194320535266"></a><a name="p194320535266"></a>获取标记的标记信息窗口锚点在水平范围的比例。</p>
</td>
</tr>
<tr id="row15879mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p15881mcpsimp"><a name="p15881mcpsimp"></a><a name="p15881mcpsimp"></a>float</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p15883mcpsimp"><a name="p15883mcpsimp"></a><a name="p15883mcpsimp"></a><a href="#section133371542203315">getInfoWindowAnchorV</a>()</p>
<p id="p1814616550267"><a name="p1814616550267"></a><a name="p1814616550267"></a>获取标记的标记信息窗口锚点在垂直范围的比例。</p>
</td>
</tr>
<tr id="row15884mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p15886mcpsimp"><a name="p15886mcpsimp"></a><a name="p15886mcpsimp"></a>LatLng</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p15888mcpsimp"><a name="p15888mcpsimp"></a><a name="p15888mcpsimp"></a><a href="#section4923215113418">getPosition</a>()</p>
<p id="p8135256142614"><a name="p8135256142614"></a><a name="p8135256142614"></a>获取标记的位置。</p>
</td>
</tr>
<tr id="row15889mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p15891mcpsimp"><a name="p15891mcpsimp"></a><a name="p15891mcpsimp"></a>float</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p15893mcpsimp"><a name="p15893mcpsimp"></a><a name="p15893mcpsimp"></a><a href="#section7334736113412">getRotation</a>()</p>
<p id="p121197575267"><a name="p121197575267"></a><a name="p121197575267"></a>获取标记的旋转角度。</p>
</td>
</tr>
<tr id="row15894mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p15896mcpsimp"><a name="p15896mcpsimp"></a><a name="p15896mcpsimp"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p15898mcpsimp"><a name="p15898mcpsimp"></a><a name="p15898mcpsimp"></a><a href="#section1305114363414">getSnippet</a>()</p>
<p id="p157715814260"><a name="p157715814260"></a><a name="p157715814260"></a>获取标记的文字片段。</p>
</td>
</tr>
<tr id="row15899mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p15901mcpsimp"><a name="p15901mcpsimp"></a><a name="p15901mcpsimp"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p15903mcpsimp"><a name="p15903mcpsimp"></a><a name="p15903mcpsimp"></a><a href="#section109271048183419">getTitle</a>()</p>
<p id="p3127115910263"><a name="p3127115910263"></a><a name="p3127115910263"></a>获取标记的标题。</p>
</td>
</tr>
<tr id="row15904mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p15906mcpsimp"><a name="p15906mcpsimp"></a><a name="p15906mcpsimp"></a>float</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p15908mcpsimp"><a name="p15908mcpsimp"></a><a name="p15908mcpsimp"></a><a href="#section1060212123512">getZIndex</a>()</p>
<p id="p75614014276"><a name="p75614014276"></a><a name="p75614014276"></a>获取标记的z指数。</p>
</td>
</tr>
<tr id="row15909mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p15911mcpsimp"><a name="p15911mcpsimp"></a><a name="p15911mcpsimp"></a><a href="markeroptions.md">MarkerOptions</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p15913mcpsimp"><a name="p15913mcpsimp"></a><a name="p15913mcpsimp"></a><a href="#section4119596355">icon</a>(<a href="bitmapdescriptor.md">BitmapDescriptor</a> iconDescriptor)</p>
<p id="p7166013270"><a name="p7166013270"></a><a name="p7166013270"></a>设置标记的图标。</p>
</td>
</tr>
<tr id="row15914mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p15916mcpsimp"><a name="p15916mcpsimp"></a><a name="p15916mcpsimp"></a><a href="markeroptions.md">MarkerOptions</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p15918mcpsimp"><a name="p15918mcpsimp"></a><a name="p15918mcpsimp"></a><a href="#section114908172352">infoWindowAnchor</a>(float u, float v)</p>
<p id="p1097418217278"><a name="p1097418217278"></a><a name="p1097418217278"></a>设置标记的标记信息窗口的锚点坐标。</p>
</td>
</tr>
<tr id="row15919mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p15921mcpsimp"><a name="p15921mcpsimp"></a><a name="p15921mcpsimp"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p15923mcpsimp"><a name="p15923mcpsimp"></a><a name="p15923mcpsimp"></a><a href="#section8566122333511">isDraggable</a>()</p>
<p id="p1082417442719"><a name="p1082417442719"></a><a name="p1082417442719"></a>获取标记是否可以通过长按来拖拽。</p>
</td>
</tr>
<tr id="row15924mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p15926mcpsimp"><a name="p15926mcpsimp"></a><a name="p15926mcpsimp"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p15928mcpsimp"><a name="p15928mcpsimp"></a><a name="p15928mcpsimp"></a><a href="#section7919729183512">isFlat</a>()</p>
<p id="p269619512274"><a name="p269619512274"></a><a name="p269619512274"></a>获取标记是否平贴地图。</p>
</td>
</tr>
<tr id="row201112717432"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p1824262918427"><a name="p1824262918427"></a><a name="p1824262918427"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p1724216299422"><a name="p1724216299422"></a><a name="p1724216299422"></a><a href="#section147631875440">ismClusterable</a>()</p>
<p id="p77091168278"><a name="p77091168278"></a><a name="p77091168278"></a>获取标记的聚合属性。</p>
</td>
</tr>
<tr id="row15929mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p15931mcpsimp"><a name="p15931mcpsimp"></a><a name="p15931mcpsimp"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p15933mcpsimp"><a name="p15933mcpsimp"></a><a name="p15933mcpsimp"></a><a href="#section1952123613518">isVisible</a>()</p>
<p id="p663620742712"><a name="p663620742712"></a><a name="p663620742712"></a>获取标记的可见性。</p>
</td>
</tr>
<tr id="row15934mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p15936mcpsimp"><a name="p15936mcpsimp"></a><a name="p15936mcpsimp"></a><a href="markeroptions.md">MarkerOptions</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p15938mcpsimp"><a name="p15938mcpsimp"></a><a name="p15938mcpsimp"></a><a href="#section339524313354">position</a>(LatLng latLng)</p>
<p id="p58155872718"><a name="p58155872718"></a><a name="p58155872718"></a>设置标记的位置坐标。</p>
</td>
</tr>
<tr id="row15939mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p15941mcpsimp"><a name="p15941mcpsimp"></a><a name="p15941mcpsimp"></a><a href="markeroptions.md">MarkerOptions</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p15943mcpsimp"><a name="p15943mcpsimp"></a><a name="p15943mcpsimp"></a><a href="#section1986735018353">rotation</a>(float rotation)</p>
<p id="p45941410202711"><a name="p45941410202711"></a><a name="p45941410202711"></a>设置标记的旋转角度，即标记围绕标记锚点顺时针旋转的角度，旋转轴垂直于标记。</p>
</td>
</tr>
<tr id="row15944mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p15946mcpsimp"><a name="p15946mcpsimp"></a><a name="p15946mcpsimp"></a><a href="markeroptions.md">MarkerOptions</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p15948mcpsimp"><a name="p15948mcpsimp"></a><a name="p15948mcpsimp"></a><a href="#section1266276203610">snippet</a>(String snippet)</p>
<p id="p19232112277"><a name="p19232112277"></a><a name="p19232112277"></a>设置标记的文字片段。</p>
</td>
</tr>
<tr id="row15949mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p15951mcpsimp"><a name="p15951mcpsimp"></a><a name="p15951mcpsimp"></a><a href="markeroptions.md">MarkerOptions</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p15953mcpsimp"><a name="p15953mcpsimp"></a><a name="p15953mcpsimp"></a><a href="#section144310304569">title</a>(String title)</p>
<p id="p1415861318270"><a name="p1415861318270"></a><a name="p1415861318270"></a>设置标记的标题。</p>
</td>
</tr>
<tr id="row15954mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p15956mcpsimp"><a name="p15956mcpsimp"></a><a name="p15956mcpsimp"></a><a href="markeroptions.md">MarkerOptions</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p15958mcpsimp"><a name="p15958mcpsimp"></a><a name="p15958mcpsimp"></a><a href="#section47301652195614">visible</a>(boolean visible)</p>
<p id="p418401482712"><a name="p418401482712"></a><a name="p418401482712"></a>设置标记的可见性。</p>
</td>
</tr>
<tr id="row15959mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p15961mcpsimp"><a name="p15961mcpsimp"></a><a name="p15961mcpsimp"></a><a href="markeroptions.md">MarkerOptions</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p15963mcpsimp"><a name="p15963mcpsimp"></a><a name="p15963mcpsimp"></a><a href="#section551291175715">zIndex</a>(float zIndex)</p>
<p id="p64969159273"><a name="p64969159273"></a><a name="p64969159273"></a>设置标记的z指数。</p>
</td>
</tr>
</tbody>
</table>

## Public Methods<a name="section1411112224221"></a>

## alpha<a name="section34311726293"></a>

<a name="table15971mcpsimp"></a>
<table><thead align="left"><tr id="row15975mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p15977mcpsimp"><a name="p15977mcpsimp"></a><a name="p15977mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row15978mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p15980mcpsimp"><a name="p15980mcpsimp"></a><a name="p15980mcpsimp"></a>public <a href="markeroptions.md">MarkerOptions</a> alpha(float alpha)</p>
<p id="p15983mcpsimp"><a name="p15983mcpsimp"></a><a name="p15983mcpsimp"></a>您调用此API可以设置标记的透明度。</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table15986mcpsimp"></a>
<table><thead align="left"><tr id="row15991mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p15993mcpsimp"><a name="p15993mcpsimp"></a><a name="p15993mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p15995mcpsimp"><a name="p15995mcpsimp"></a><a name="p15995mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row15996mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p15998mcpsimp"><a name="p15998mcpsimp"></a><a name="p15998mcpsimp"></a>alpha</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p16000mcpsimp"><a name="p16000mcpsimp"></a><a name="p16000mcpsimp"></a>透明度，取值范围：[0, 1]，0表示完全透明的，1表示完全不透明，默认为1。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table16003mcpsimp"></a>
<table><thead align="left"><tr id="row16008mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p16010mcpsimp"><a name="p16010mcpsimp"></a><a name="p16010mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p16012mcpsimp"><a name="p16012mcpsimp"></a><a name="p16012mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row16013mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p16015mcpsimp"><a name="p16015mcpsimp"></a><a name="p16015mcpsimp"></a>MarkerOptions</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p16017mcpsimp"><a name="p16017mcpsimp"></a><a name="p16017mcpsimp"></a>设置新的透明度后的<a href="markeroptions.md">MarkerOptions</a>对象。</p>
</td>
</tr>
</tbody>
</table>

## anchor<a name="section1326516357302"></a>

>![](public_sys-resources/icon-caution.gif) **注意：** 
>该接口已弃用，设置锚点位置请使用[anchorMarker](#section95121330125810)。

<a name="table16019mcpsimp"></a>
<table><thead align="left"><tr id="row16023mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p16025mcpsimp"><a name="p16025mcpsimp"></a><a name="p16025mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row16026mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p16028mcpsimp"><a name="p16028mcpsimp"></a><a name="p16028mcpsimp"></a>public <a href="markeroptions.md">MarkerOptions</a> anchor(float u, float v)</p>
<p id="p19982044518"><a name="p19982044518"></a><a name="p19982044518"></a>您调用此API可以设置标记的锚点位置。当前u，v已设置固定值，所以该接口固定锚点位置为标记图标的中部。</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table16035mcpsimp"></a>
<table><thead align="left"><tr id="row16040mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p16042mcpsimp"><a name="p16042mcpsimp"></a><a name="p16042mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p16044mcpsimp"><a name="p16044mcpsimp"></a><a name="p16044mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row16045mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p16047mcpsimp"><a name="p16047mcpsimp"></a><a name="p16047mcpsimp"></a>u</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p16049mcpsimp"><a name="p16049mcpsimp"></a><a name="p16049mcpsimp"></a>锚点的水平坐标，以图像宽度的比例，在[0, 1]范围内。</p>
</td>
</tr>
<tr id="row16050mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p16052mcpsimp"><a name="p16052mcpsimp"></a><a name="p16052mcpsimp"></a>v</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p16054mcpsimp"><a name="p16054mcpsimp"></a><a name="p16054mcpsimp"></a>锚点的垂直坐标，以图像高度的比例，在[0, 1]范围内。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table16057mcpsimp"></a>
<table><thead align="left"><tr id="row16062mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p16064mcpsimp"><a name="p16064mcpsimp"></a><a name="p16064mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p16066mcpsimp"><a name="p16066mcpsimp"></a><a name="p16066mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row16067mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p16069mcpsimp"><a name="p16069mcpsimp"></a><a name="p16069mcpsimp"></a>MarkerOptions</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p16071mcpsimp"><a name="p16071mcpsimp"></a><a name="p16071mcpsimp"></a>设置新的锚点位置后的<a href="markeroptions.md">MarkerOptions</a>对象。</p>
</td>
</tr>
</tbody>
</table>

## anchorMarker<a name="section95121330125810"></a>

<a name="table8199503582"></a>
<table><thead align="left"><tr id="row1320185012589"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p020125045811"><a name="p020125045811"></a><a name="p020125045811"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row1820550175813"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p18201150185814"><a name="p18201150185814"></a><a name="p18201150185814"></a>public <a href="markeroptions.md">MarkerOptions</a> anchorMarker(float anchorU, float anchorV)</p>
<p id="p02015016581"><a name="p02015016581"></a><a name="p02015016581"></a>您调用此API可以设置标记的锚点位置。锚点是标记图标接触地图平面的点，图标的左顶点为（0, 0）点，右顶点为（1, 0）点，左底点为（0, 1）点，右底点为（1, 1）点。例如，在标记X（0.5, 0.3）处的锚点坐标如下：</p>
<p id="p1729085314409"><a name="p1729085314409"></a><a name="p1729085314409"></a><a name="image19290165314015"></a><a name="image19290165314015"></a><span><img id="image19290165314015" src="figures/anchor-0.png" height="278.160057" width="399"></span></p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table20201501581"></a>
<table><thead align="left"><tr id="row220145085813"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p520185025813"><a name="p520185025813"></a><a name="p520185025813"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p1020850125817"><a name="p1020850125817"></a><a name="p1020850125817"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row520205010583"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p849625075911"><a name="p849625075911"></a><a name="p849625075911"></a>u</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p1149625085915"><a name="p1149625085915"></a><a name="p1149625085915"></a>锚点的水平坐标，以图像宽度的比例，建议取值[0, 1]，默认值为0.5。</p>
</td>
</tr>
<tr id="row2510340195914"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p10497050105917"><a name="p10497050105917"></a><a name="p10497050105917"></a>v</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p17497450135915"><a name="p17497450135915"></a><a name="p17497450135915"></a>锚点的垂直坐标，以图像高度的比例，建议取值[0, 1]，默认值为1。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table102119502585"></a>
<table><thead align="left"><tr id="row6211850135811"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p82119500582"><a name="p82119500582"></a><a name="p82119500582"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p162116506581"><a name="p162116506581"></a><a name="p162116506581"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row1221175017587"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p62118508588"><a name="p62118508588"></a><a name="p62118508588"></a>MarkerOptions</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p686912121408"><a name="p686912121408"></a><a name="p686912121408"></a>设置新的锚点位置后的<a href="markeroptions.md">MarkerOptions</a>对象。</p>
</td>
</tr>
</tbody>
</table>

## clusterable<a name="section99273302577"></a>

<a name="table1755442216577"></a>
<table><thead align="left"><tr id="row16653122255717"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p1065312255717"><a name="p1065312255717"></a><a name="p1065312255717"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row26537224574"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p1665362235715"><a name="p1665362235715"></a><a name="p1665362235715"></a>public <a href="markeroptions.md">MarkerOptions</a> clusterable(boolean clusterable)</p>
<p id="p265318225571"><a name="p265318225571"></a><a name="p265318225571"></a>用于设置标记的聚合属性。</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table25581922185714"></a>
<table><thead align="left"><tr id="row965432219571"><th class="cellrowborder" valign="top" width="47.88%" id="mcps1.1.3.1.1"><p id="p996635593019"><a name="p996635593019"></a><a name="p996635593019"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="52.12%" id="mcps1.1.3.1.2"><p id="p796617557301"><a name="p796617557301"></a><a name="p796617557301"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row126544227571"><td class="cellrowborder" valign="top" width="47.88%" headers="mcps1.1.3.1.1 "><p id="p1565411221573"><a name="p1565411221573"></a><a name="p1565411221573"></a>clusterable</p>
</td>
<td class="cellrowborder" valign="top" width="52.12%" headers="mcps1.1.3.1.2 "><p id="p156541022205718"><a name="p156541022205718"></a><a name="p156541022205718"></a><a href="markeroptions.md">MarkerOptions</a>的聚合属性，true表示可聚合，false表示不可聚合，默认为false。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table8561162255716"></a>
<table><thead align="left"><tr id="row8654172216574"><th class="cellrowborder" valign="top" width="48.02%" id="mcps1.1.3.1.1"><p id="p1687914917335"><a name="p1687914917335"></a><a name="p1687914917335"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="51.980000000000004%" id="mcps1.1.3.1.2"><p id="p08797491337"><a name="p08797491337"></a><a name="p08797491337"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row4654132215715"><td class="cellrowborder" valign="top" width="48.02%" headers="mcps1.1.3.1.1 "><p id="p86541022105713"><a name="p86541022105713"></a><a name="p86541022105713"></a>MarkerOptions</p>
</td>
<td class="cellrowborder" valign="top" width="51.980000000000004%" headers="mcps1.1.3.1.2 "><p id="p665432275711"><a name="p665432275711"></a><a name="p665432275711"></a>设置聚合属性后的<a href="markeroptions.md">MarkerOptions</a>对象。</p>
</td>
</tr>
</tbody>
</table>

## draggable<a name="section0702145819302"></a>

<a name="table16073mcpsimp"></a>
<table><thead align="left"><tr id="row16077mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p16079mcpsimp"><a name="p16079mcpsimp"></a><a name="p16079mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row16080mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p16082mcpsimp"><a name="p16082mcpsimp"></a><a name="p16082mcpsimp"></a>public <a href="markeroptions.md">MarkerOptions</a> draggable(boolean draggable)</p>
<p id="p446491174715"><a name="p446491174715"></a><a name="p446491174715"></a>您调用此API可以设置标记是否可以通过长按来拖拽。</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table16088mcpsimp"></a>
<table><thead align="left"><tr id="row16093mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p16095mcpsimp"><a name="p16095mcpsimp"></a><a name="p16095mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p16097mcpsimp"><a name="p16097mcpsimp"></a><a name="p16097mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row16098mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p16100mcpsimp"><a name="p16100mcpsimp"></a><a name="p16100mcpsimp"></a>draggable</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p16102mcpsimp"><a name="p16102mcpsimp"></a><a name="p16102mcpsimp"></a>是否可以长按拖拽，true为可以，false为不可以。默认值为false。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table16105mcpsimp"></a>
<table><thead align="left"><tr id="row16110mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p16112mcpsimp"><a name="p16112mcpsimp"></a><a name="p16112mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p16114mcpsimp"><a name="p16114mcpsimp"></a><a name="p16114mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row16115mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p16117mcpsimp"><a name="p16117mcpsimp"></a><a name="p16117mcpsimp"></a>MarkerOptions</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p16119mcpsimp"><a name="p16119mcpsimp"></a><a name="p16119mcpsimp"></a>设置新的draggable属性后的<a href="markeroptions.md">MarkerOptions</a>对象。</p>
</td>
</tr>
</tbody>
</table>

## flat<a name="section2727192393111"></a>

<a name="table16121mcpsimp"></a>
<table><thead align="left"><tr id="row16125mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p16127mcpsimp"><a name="p16127mcpsimp"></a><a name="p16127mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row16128mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p16130mcpsimp"><a name="p16130mcpsimp"></a><a name="p16130mcpsimp"></a>public <a href="markeroptions.md">MarkerOptions</a> flat(boolean flat)</p>
<p id="p166512019408"><a name="p166512019408"></a><a name="p166512019408"></a>您调用此API可以设置标记是否平贴地图。如果标记平贴地图，则在相机旋转和倾斜时，标记仍将停留在地图上，但与<a href="groundoverlay.md">GroundOverlay</a>不同，它将保持与照相机缩放时相同的大小。如果标记面对相机，它将始终面向相机绘制，并随相机旋转和倾斜。</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table16136mcpsimp"></a>
<table><thead align="left"><tr id="row16141mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p16143mcpsimp"><a name="p16143mcpsimp"></a><a name="p16143mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p16145mcpsimp"><a name="p16145mcpsimp"></a><a name="p16145mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row16146mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p16148mcpsimp"><a name="p16148mcpsimp"></a><a name="p16148mcpsimp"></a>flat</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p16150mcpsimp"><a name="p16150mcpsimp"></a><a name="p16150mcpsimp"></a>平贴地图设置为true，面对相机设置为false。默认值为false。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table16153mcpsimp"></a>
<table><thead align="left"><tr id="row16158mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p16160mcpsimp"><a name="p16160mcpsimp"></a><a name="p16160mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p16162mcpsimp"><a name="p16162mcpsimp"></a><a name="p16162mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row16163mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p16165mcpsimp"><a name="p16165mcpsimp"></a><a name="p16165mcpsimp"></a>MarkerOptions</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p16167mcpsimp"><a name="p16167mcpsimp"></a><a name="p16167mcpsimp"></a>设置新的flat属性后的<a href="markeroptions.md">MarkerOptions</a>对象。</p>
</td>
</tr>
</tbody>
</table>

## getAlpha<a name="section1832455019318"></a>

<a name="table16169mcpsimp"></a>
<table><thead align="left"><tr id="row16173mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p16175mcpsimp"><a name="p16175mcpsimp"></a><a name="p16175mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row16176mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p16178mcpsimp"><a name="p16178mcpsimp"></a><a name="p16178mcpsimp"></a>public float getAlpha()</p>
<p id="p1246194419401"><a name="p1246194419401"></a><a name="p1246194419401"></a>您调用此API可以获取标记的透明度。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table16187mcpsimp"></a>
<table><thead align="left"><tr id="row16192mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p16194mcpsimp"><a name="p16194mcpsimp"></a><a name="p16194mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p16196mcpsimp"><a name="p16196mcpsimp"></a><a name="p16196mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row16197mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p16199mcpsimp"><a name="p16199mcpsimp"></a><a name="p16199mcpsimp"></a>float</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p16201mcpsimp"><a name="p16201mcpsimp"></a><a name="p16201mcpsimp"></a>标记的透明度。</p>
</td>
</tr>
</tbody>
</table>

## getAnchorU<a name="section155871213163216"></a>

>![](public_sys-resources/icon-caution.gif) **注意：** 
>该接口已弃用，获取标记锚点在水平范围的比例请使用[getMarkerAnchorU](#section1930718125268)。

<a name="table16203mcpsimp"></a>
<table><thead align="left"><tr id="row16207mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p16209mcpsimp"><a name="p16209mcpsimp"></a><a name="p16209mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row16210mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p16212mcpsimp"><a name="p16212mcpsimp"></a><a name="p16212mcpsimp"></a>public float getAnchorU()</p>
<p id="p1843918592408"><a name="p1843918592408"></a><a name="p1843918592408"></a>您调用此API可以获取标记锚点在水平范围的比例，这个比例值从图标的左边开始计算，在[0, 1]范围内。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table16221mcpsimp"></a>
<table><thead align="left"><tr id="row16226mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p16228mcpsimp"><a name="p16228mcpsimp"></a><a name="p16228mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p16230mcpsimp"><a name="p16230mcpsimp"></a><a name="p16230mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row16231mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p16233mcpsimp"><a name="p16233mcpsimp"></a><a name="p16233mcpsimp"></a>float</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p16235mcpsimp"><a name="p16235mcpsimp"></a><a name="p16235mcpsimp"></a>标记锚点在水平范围的比例。</p>
</td>
</tr>
</tbody>
</table>

## getMarkerAnchorU<a name="section1930718125268"></a>

<a name="table430716123260"></a>
<table><thead align="left"><tr id="row030791219265"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p203071212142612"><a name="p203071212142612"></a><a name="p203071212142612"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row1230711125263"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p33075124268"><a name="p33075124268"></a><a name="p33075124268"></a>public float getMarkerAnchorU()</p>
<p id="p183071112102614"><a name="p183071112102614"></a><a name="p183071112102614"></a>您调用此API可以获取标记锚点在水平范围的比例，这个比例值从图标的左边开始计算，在[0, 1]范围内。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table15308212132612"></a>
<table><thead align="left"><tr id="row2308111292610"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p16308191222619"><a name="p16308191222619"></a><a name="p16308191222619"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p1330817129265"><a name="p1330817129265"></a><a name="p1330817129265"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row1130871262614"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p4308191216267"><a name="p4308191216267"></a><a name="p4308191216267"></a>float</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p3308171232620"><a name="p3308171232620"></a><a name="p3308171232620"></a>标记锚点在水平范围的比例。</p>
</td>
</tr>
</tbody>
</table>

## getAnchorV<a name="section42741744163220"></a>

>![](public_sys-resources/icon-caution.gif) **注意：** 
>该接口已弃用，获取标记锚点在垂直范围的比例请使用[getMarkerAnchorV](#section3991833123317)。

<a name="table16237mcpsimp"></a>
<table><thead align="left"><tr id="row16241mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p16243mcpsimp"><a name="p16243mcpsimp"></a><a name="p16243mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row16244mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p16246mcpsimp"><a name="p16246mcpsimp"></a><a name="p16246mcpsimp"></a>public float getAnchorV()</p>
<p id="p063224854619"><a name="p063224854619"></a><a name="p063224854619"></a>您调用此API可以获取标记锚点在垂直范围的比例，这个比例值从图标的顶端开始计算，在[0, 1]范围内。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table16255mcpsimp"></a>
<table><thead align="left"><tr id="row16260mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p16262mcpsimp"><a name="p16262mcpsimp"></a><a name="p16262mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p16264mcpsimp"><a name="p16264mcpsimp"></a><a name="p16264mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row16265mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p16267mcpsimp"><a name="p16267mcpsimp"></a><a name="p16267mcpsimp"></a>float</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p16269mcpsimp"><a name="p16269mcpsimp"></a><a name="p16269mcpsimp"></a>标记锚点在垂直范围的比例。</p>
</td>
</tr>
</tbody>
</table>

## getMarkerAnchorV<a name="section3991833123317"></a>

<a name="table1399143310332"></a>
<table><thead align="left"><tr id="row1999173311332"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p1899123363312"><a name="p1899123363312"></a><a name="p1899123363312"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row69953333317"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p299933123316"><a name="p299933123316"></a><a name="p299933123316"></a>public float getMarkerAnchorV()</p>
<p id="p29963315337"><a name="p29963315337"></a><a name="p29963315337"></a>您调用此API可以获取标记锚点在垂直范围的比例，这个比例值从图标的顶端开始计算，在[0, 1]范围内。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table410073383312"></a>
<table><thead align="left"><tr id="row9100153314330"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p6100103315332"><a name="p6100103315332"></a><a name="p6100103315332"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p16100733133312"><a name="p16100733133312"></a><a name="p16100733133312"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row191005336331"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p201021833163318"><a name="p201021833163318"></a><a name="p201021833163318"></a>float</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p71021233123315"><a name="p71021233123315"></a><a name="p71021233123315"></a>标记锚点在垂直范围的比例。</p>
</td>
</tr>
</tbody>
</table>

## getIcon<a name="section168698343319"></a>

<a name="table16271mcpsimp"></a>
<table><thead align="left"><tr id="row16275mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p16277mcpsimp"><a name="p16277mcpsimp"></a><a name="p16277mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row16278mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p16280mcpsimp"><a name="p16280mcpsimp"></a><a name="p16280mcpsimp"></a>public <a href="bitmapdescriptor.md">BitmapDescriptor</a> getIcon()</p>
<p id="p1818715399460"><a name="p1818715399460"></a><a name="p1818715399460"></a>您调用此API可以获取到标记的图标。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table16289mcpsimp"></a>
<table><thead align="left"><tr id="row16294mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p16296mcpsimp"><a name="p16296mcpsimp"></a><a name="p16296mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p16298mcpsimp"><a name="p16298mcpsimp"></a><a name="p16298mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row16299mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p16301mcpsimp"><a name="p16301mcpsimp"></a><a name="p16301mcpsimp"></a>BitmapDescriptor</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p16303mcpsimp"><a name="p16303mcpsimp"></a><a name="p16303mcpsimp"></a>图标的<a href="bitmapdescriptor.md">BitmapDescriptor</a>对象。</p>
</td>
</tr>
</tbody>
</table>

## getInfoWindowAnchorU<a name="section155505241338"></a>

<a name="table16305mcpsimp"></a>
<table><thead align="left"><tr id="row16309mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p16311mcpsimp"><a name="p16311mcpsimp"></a><a name="p16311mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row16312mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p16314mcpsimp"><a name="p16314mcpsimp"></a><a name="p16314mcpsimp"></a>public float getInfoWindowAnchorU()</p>
<p id="p278123984119"><a name="p278123984119"></a><a name="p278123984119"></a>您调用此API可以获取标记的标记信息窗口锚点在水平范围的比例，这个比例值从标记图标的左边开始计算，在[0, 1]范围内。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table16323mcpsimp"></a>
<table><thead align="left"><tr id="row16328mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p16330mcpsimp"><a name="p16330mcpsimp"></a><a name="p16330mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p16332mcpsimp"><a name="p16332mcpsimp"></a><a name="p16332mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row16333mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p16335mcpsimp"><a name="p16335mcpsimp"></a><a name="p16335mcpsimp"></a>float</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p16337mcpsimp"><a name="p16337mcpsimp"></a><a name="p16337mcpsimp"></a>标记信息窗口锚点在水平范围的比例。</p>
</td>
</tr>
</tbody>
</table>

## getInfoWindowAnchorV<a name="section133371542203315"></a>

<a name="table16339mcpsimp"></a>
<table><thead align="left"><tr id="row16343mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p16345mcpsimp"><a name="p16345mcpsimp"></a><a name="p16345mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row16346mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p16348mcpsimp"><a name="p16348mcpsimp"></a><a name="p16348mcpsimp"></a>public float getInfoWindowAnchorV()</p>
<p id="p1473492684612"><a name="p1473492684612"></a><a name="p1473492684612"></a>您调用此API可以获取标记的标记信息窗口锚点在垂直范围的比例，这个比例值从标记图标的顶端开始计算，在[0, 1]范围内。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table16357mcpsimp"></a>
<table><thead align="left"><tr id="row16362mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p16364mcpsimp"><a name="p16364mcpsimp"></a><a name="p16364mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p16366mcpsimp"><a name="p16366mcpsimp"></a><a name="p16366mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row16367mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p16369mcpsimp"><a name="p16369mcpsimp"></a><a name="p16369mcpsimp"></a>float</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p16371mcpsimp"><a name="p16371mcpsimp"></a><a name="p16371mcpsimp"></a>标记信息窗口锚点在垂直范围的比例。</p>
</td>
</tr>
</tbody>
</table>

## getPosition<a name="section4923215113418"></a>

<a name="table16373mcpsimp"></a>
<table><thead align="left"><tr id="row16377mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p16379mcpsimp"><a name="p16379mcpsimp"></a><a name="p16379mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row16380mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p16382mcpsimp"><a name="p16382mcpsimp"></a><a name="p16382mcpsimp"></a>public <a href="latlng.md">LatLng</a> getPosition()</p>
<p id="p128461416104620"><a name="p128461416104620"></a><a name="p128461416104620"></a>您调用此API可以获取标记的位置。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table16391mcpsimp"></a>
<table><thead align="left"><tr id="row16396mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p16398mcpsimp"><a name="p16398mcpsimp"></a><a name="p16398mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p16400mcpsimp"><a name="p16400mcpsimp"></a><a name="p16400mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row16401mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p16403mcpsimp"><a name="p16403mcpsimp"></a><a name="p16403mcpsimp"></a><a href="latlng.md">LatLng</a></p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p16405mcpsimp"><a name="p16405mcpsimp"></a><a name="p16405mcpsimp"></a>标记的位置。</p>
</td>
</tr>
</tbody>
</table>

## getRotation<a name="section7334736113412"></a>

<a name="table16407mcpsimp"></a>
<table><thead align="left"><tr id="row16411mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p16413mcpsimp"><a name="p16413mcpsimp"></a><a name="p16413mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row16414mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p16416mcpsimp"><a name="p16416mcpsimp"></a><a name="p16416mcpsimp"></a>public float getRotation()</p>
<p id="p16419mcpsimp"><a name="p16419mcpsimp"></a><a name="p16419mcpsimp"></a>您调用此API可以获取标记的旋转角度。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table16425mcpsimp"></a>
<table><thead align="left"><tr id="row16430mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p16432mcpsimp"><a name="p16432mcpsimp"></a><a name="p16432mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p16434mcpsimp"><a name="p16434mcpsimp"></a><a name="p16434mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row16435mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p16437mcpsimp"><a name="p16437mcpsimp"></a><a name="p16437mcpsimp"></a>float</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p16439mcpsimp"><a name="p16439mcpsimp"></a><a name="p16439mcpsimp"></a>标记的旋转角度。</p>
</td>
</tr>
</tbody>
</table>

## getSnippet<a name="section1305114363414"></a>

<a name="table16441mcpsimp"></a>
<table><thead align="left"><tr id="row16445mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p16447mcpsimp"><a name="p16447mcpsimp"></a><a name="p16447mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row16448mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p16450mcpsimp"><a name="p16450mcpsimp"></a><a name="p16450mcpsimp"></a>public String getSnippet()</p>
<p id="p16453mcpsimp"><a name="p16453mcpsimp"></a><a name="p16453mcpsimp"></a>您调用此API可以获取标记的文字片段。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table16459mcpsimp"></a>
<table><thead align="left"><tr id="row16464mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p16466mcpsimp"><a name="p16466mcpsimp"></a><a name="p16466mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p16468mcpsimp"><a name="p16468mcpsimp"></a><a name="p16468mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row16469mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p16471mcpsimp"><a name="p16471mcpsimp"></a><a name="p16471mcpsimp"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p16473mcpsimp"><a name="p16473mcpsimp"></a><a name="p16473mcpsimp"></a>标记的文字片段。</p>
</td>
</tr>
</tbody>
</table>

## getTitle<a name="section109271048183419"></a>

<a name="table16475mcpsimp"></a>
<table><thead align="left"><tr id="row16479mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p16481mcpsimp"><a name="p16481mcpsimp"></a><a name="p16481mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row16482mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p16484mcpsimp"><a name="p16484mcpsimp"></a><a name="p16484mcpsimp"></a>public String getTitle()</p>
<p id="p42941257114510"><a name="p42941257114510"></a><a name="p42941257114510"></a>您调用此API可以获取标记的标题。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table16493mcpsimp"></a>
<table><thead align="left"><tr id="row16498mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p16500mcpsimp"><a name="p16500mcpsimp"></a><a name="p16500mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p16502mcpsimp"><a name="p16502mcpsimp"></a><a name="p16502mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row16503mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p16505mcpsimp"><a name="p16505mcpsimp"></a><a name="p16505mcpsimp"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p16507mcpsimp"><a name="p16507mcpsimp"></a><a name="p16507mcpsimp"></a>标记的标题。</p>
</td>
</tr>
</tbody>
</table>

## getZIndex<a name="section1060212123512"></a>

<a name="table16509mcpsimp"></a>
<table><thead align="left"><tr id="row16513mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p16515mcpsimp"><a name="p16515mcpsimp"></a><a name="p16515mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row16516mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p16518mcpsimp"><a name="p16518mcpsimp"></a><a name="p16518mcpsimp"></a>public float getZIndex()</p>
<p id="p662517482458"><a name="p662517482458"></a><a name="p662517482458"></a>您调用此API可以获取标记的z指数。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table16527mcpsimp"></a>
<table><thead align="left"><tr id="row16532mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p16534mcpsimp"><a name="p16534mcpsimp"></a><a name="p16534mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p16536mcpsimp"><a name="p16536mcpsimp"></a><a name="p16536mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row16537mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p16539mcpsimp"><a name="p16539mcpsimp"></a><a name="p16539mcpsimp"></a>float</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p16541mcpsimp"><a name="p16541mcpsimp"></a><a name="p16541mcpsimp"></a>z指数，即标记的叠加顺序。</p>
</td>
</tr>
</tbody>
</table>

## icon<a name="section4119596355"></a>

<a name="table16543mcpsimp"></a>
<table><thead align="left"><tr id="row16547mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p16549mcpsimp"><a name="p16549mcpsimp"></a><a name="p16549mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row16550mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p16552mcpsimp"><a name="p16552mcpsimp"></a><a name="p16552mcpsimp"></a>public <a href="markeroptions.md">MarkerOptions</a> icon(<a href="bitmapdescriptor.md">BitmapDescriptor </a>iconDescriptor)</p>
<p id="p7800156124212"><a name="p7800156124212"></a><a name="p7800156124212"></a>您调用此API可以设置标记的图标，如果为空，则使用默认标记图标。</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table16558mcpsimp"></a>
<table><thead align="left"><tr id="row16563mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p16565mcpsimp"><a name="p16565mcpsimp"></a><a name="p16565mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p16567mcpsimp"><a name="p16567mcpsimp"></a><a name="p16567mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row16568mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p16570mcpsimp"><a name="p16570mcpsimp"></a><a name="p16570mcpsimp"></a>iconDescriptor</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p16572mcpsimp"><a name="p16572mcpsimp"></a><a name="p16572mcpsimp"></a>含有新icon图标对象。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table16575mcpsimp"></a>
<table><thead align="left"><tr id="row16580mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p16582mcpsimp"><a name="p16582mcpsimp"></a><a name="p16582mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p16584mcpsimp"><a name="p16584mcpsimp"></a><a name="p16584mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row16585mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p16587mcpsimp"><a name="p16587mcpsimp"></a><a name="p16587mcpsimp"></a>MarkerOptions</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p16589mcpsimp"><a name="p16589mcpsimp"></a><a name="p16589mcpsimp"></a>设置新的图标后的<a href="markeroptions.md">MarkerOptions</a>对象。</p>
</td>
</tr>
</tbody>
</table>

## infoWindowAnchor<a name="section114908172352"></a>

<a name="table16591mcpsimp"></a>
<table><thead align="left"><tr id="row16595mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p16597mcpsimp"><a name="p16597mcpsimp"></a><a name="p16597mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row16598mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p16600mcpsimp"><a name="p16600mcpsimp"></a><a name="p16600mcpsimp"></a>public <a href="markeroptions.md">MarkerOptions</a> infoWindowAnchor(float u, float v)</p>
<p id="p536021744313"><a name="p536021744313"></a><a name="p536021744313"></a>您调用此API可以设置标记的标记信息窗口的锚点坐标， 这是在与锚点相同的坐标系中指定的， 默认值为图像的顶部中间。 有关更多详细信息，请参见<a href="#section95121330125810">anchorMarker</a>(float anchorU, float anchorV)。</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table16606mcpsimp"></a>
<table><thead align="left"><tr id="row16611mcpsimp"><th class="cellrowborder" valign="top" width="35.82%" id="mcps1.1.3.1.1"><p id="p16613mcpsimp"><a name="p16613mcpsimp"></a><a name="p16613mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="64.18%" id="mcps1.1.3.1.2"><p id="p16615mcpsimp"><a name="p16615mcpsimp"></a><a name="p16615mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row16616mcpsimp"><td class="cellrowborder" valign="top" width="35.82%" headers="mcps1.1.3.1.1 "><p id="p16618mcpsimp"><a name="p16618mcpsimp"></a><a name="p16618mcpsimp"></a>u</p>
</td>
<td class="cellrowborder" valign="top" width="64.18%" headers="mcps1.1.3.1.2 "><p id="p16620mcpsimp"><a name="p16620mcpsimp"></a><a name="p16620mcpsimp"></a>标记信息窗口锚点的水平坐标，以图像宽度的比例，建议取值[0, 1]，默认值为0.5。</p>
</td>
</tr>
<tr id="row16621mcpsimp"><td class="cellrowborder" valign="top" width="35.82%" headers="mcps1.1.3.1.1 "><p id="p16623mcpsimp"><a name="p16623mcpsimp"></a><a name="p16623mcpsimp"></a>v</p>
</td>
<td class="cellrowborder" valign="top" width="64.18%" headers="mcps1.1.3.1.2 "><p id="p16625mcpsimp"><a name="p16625mcpsimp"></a><a name="p16625mcpsimp"></a>标记信息窗口锚点的垂直坐标，以图像高度的比例，建议取值[0, 1]，默认值为1。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table16628mcpsimp"></a>
<table><thead align="left"><tr id="row16633mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p16635mcpsimp"><a name="p16635mcpsimp"></a><a name="p16635mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p16637mcpsimp"><a name="p16637mcpsimp"></a><a name="p16637mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row16638mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p16640mcpsimp"><a name="p16640mcpsimp"></a><a name="p16640mcpsimp"></a>MarkerOptions</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p16642mcpsimp"><a name="p16642mcpsimp"></a><a name="p16642mcpsimp"></a>设置新的标记信息窗口锚点坐标后的<a href="markeroptions.md">MarkerOptions</a>对象。</p>
</td>
</tr>
</tbody>
</table>

## isDraggable<a name="section8566122333511"></a>

<a name="table16644mcpsimp"></a>
<table><thead align="left"><tr id="row16648mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p16650mcpsimp"><a name="p16650mcpsimp"></a><a name="p16650mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row16651mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p16653mcpsimp"><a name="p16653mcpsimp"></a><a name="p16653mcpsimp"></a>public boolean isDraggable()</p>
<p id="p02024349454"><a name="p02024349454"></a><a name="p02024349454"></a>您调用此API可以获取标记是否可以通过长按来拖拽。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table16662mcpsimp"></a>
<table><thead align="left"><tr id="row16667mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p16669mcpsimp"><a name="p16669mcpsimp"></a><a name="p16669mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p16671mcpsimp"><a name="p16671mcpsimp"></a><a name="p16671mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row16672mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p16674mcpsimp"><a name="p16674mcpsimp"></a><a name="p16674mcpsimp"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p16676mcpsimp"><a name="p16676mcpsimp"></a><a name="p16676mcpsimp"></a>表示是否可以拖拽，true为可以，false为不可以。</p>
</td>
</tr>
</tbody>
</table>

## isFlat<a name="section7919729183512"></a>

<a name="table16678mcpsimp"></a>
<table><thead align="left"><tr id="row16682mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p16684mcpsimp"><a name="p16684mcpsimp"></a><a name="p16684mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row16685mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p16687mcpsimp"><a name="p16687mcpsimp"></a><a name="p16687mcpsimp"></a>public boolean isFlat()</p>
<p id="p1591732312454"><a name="p1591732312454"></a><a name="p1591732312454"></a>您调用此API可以获取标记是否平贴地图。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table16696mcpsimp"></a>
<table><thead align="left"><tr id="row16701mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p16703mcpsimp"><a name="p16703mcpsimp"></a><a name="p16703mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p16705mcpsimp"><a name="p16705mcpsimp"></a><a name="p16705mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row16706mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p16708mcpsimp"><a name="p16708mcpsimp"></a><a name="p16708mcpsimp"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p16710mcpsimp"><a name="p16710mcpsimp"></a><a name="p16710mcpsimp"></a>表示是否平贴地图，true为平贴地图，false为面对相机。</p>
</td>
</tr>
</tbody>
</table>

## ismClusterable<a name="section147631875440"></a>

<a name="table177647716449"></a>
<table><thead align="left"><tr id="row15765157184411"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p47655710447"><a name="p47655710447"></a><a name="p47655710447"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row127654784414"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p11766167104414"><a name="p11766167104414"></a><a name="p11766167104414"></a>public boolean ismClusterable()</p>
<p id="p618242185210"><a name="p618242185210"></a><a name="p618242185210"></a>获取标记的聚合属性。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table77696754420"></a>
<table><thead align="left"><tr id="row16769778441"><th class="cellrowborder" valign="top" width="48.02%" id="mcps1.1.3.1.1"><p id="p15201353193314"><a name="p15201353193314"></a><a name="p15201353193314"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="51.980000000000004%" id="mcps1.1.3.1.2"><p id="p7201853163312"><a name="p7201853163312"></a><a name="p7201853163312"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row12770127144419"><td class="cellrowborder" valign="top" width="48.02%" headers="mcps1.1.3.1.1 "><p id="p47701275440"><a name="p47701275440"></a><a name="p47701275440"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="51.980000000000004%" headers="mcps1.1.3.1.2 "><p id="p577010724411"><a name="p577010724411"></a><a name="p577010724411"></a>true表示可聚合，false表示不可聚合。</p>
</td>
</tr>
</tbody>
</table>

## isVisible<a name="section1952123613518"></a>

<a name="table16712mcpsimp"></a>
<table><thead align="left"><tr id="row16716mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p16718mcpsimp"><a name="p16718mcpsimp"></a><a name="p16718mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row16719mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p16721mcpsimp"><a name="p16721mcpsimp"></a><a name="p16721mcpsimp"></a>public boolean isVisible()</p>
<p id="p1170719161457"><a name="p1170719161457"></a><a name="p1170719161457"></a>您调用此API可以获取标记的可见性。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table16730mcpsimp"></a>
<table><thead align="left"><tr id="row16735mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p16737mcpsimp"><a name="p16737mcpsimp"></a><a name="p16737mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p16739mcpsimp"><a name="p16739mcpsimp"></a><a name="p16739mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row16740mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p16742mcpsimp"><a name="p16742mcpsimp"></a><a name="p16742mcpsimp"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p16744mcpsimp"><a name="p16744mcpsimp"></a><a name="p16744mcpsimp"></a>标记的可见性 ，true为可见，false为不可见。</p>
</td>
</tr>
</tbody>
</table>

## position<a name="section339524313354"></a>

<a name="table16746mcpsimp"></a>
<table><thead align="left"><tr id="row16750mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p16752mcpsimp"><a name="p16752mcpsimp"></a><a name="p16752mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row16753mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p16755mcpsimp"><a name="p16755mcpsimp"></a><a name="p16755mcpsimp"></a>public <a href="markeroptions.md">MarkerOptions</a> position(<a href="latlng.md">LatLng</a> latLng)</p>
<p id="p123101334456"><a name="p123101334456"></a><a name="p123101334456"></a>您调用此API可以设置标记的位置坐标。</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table16761mcpsimp"></a>
<table><thead align="left"><tr id="row16766mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p16768mcpsimp"><a name="p16768mcpsimp"></a><a name="p16768mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p16770mcpsimp"><a name="p16770mcpsimp"></a><a name="p16770mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row16771mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p16773mcpsimp"><a name="p16773mcpsimp"></a><a name="p16773mcpsimp"></a>latLng</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p16775mcpsimp"><a name="p16775mcpsimp"></a><a name="p16775mcpsimp"></a>标记的位置坐标。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table16778mcpsimp"></a>
<table><thead align="left"><tr id="row16783mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p16785mcpsimp"><a name="p16785mcpsimp"></a><a name="p16785mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p16787mcpsimp"><a name="p16787mcpsimp"></a><a name="p16787mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row16788mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p16790mcpsimp"><a name="p16790mcpsimp"></a><a name="p16790mcpsimp"></a>MarkerOptions</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p16792mcpsimp"><a name="p16792mcpsimp"></a><a name="p16792mcpsimp"></a>设置新的位置坐标后的<a href="markeroptions.md">MarkerOptions</a>对象。</p>
</td>
</tr>
</tbody>
</table>

## rotation<a name="section1986735018353"></a>

<a name="table16794mcpsimp"></a>
<table><thead align="left"><tr id="row16798mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p16800mcpsimp"><a name="p16800mcpsimp"></a><a name="p16800mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row16801mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p16803mcpsimp"><a name="p16803mcpsimp"></a><a name="p16803mcpsimp"></a>public <a href="markeroptions.md">MarkerOptions</a> rotation(float rotation)</p>
<p id="p15131654114417"><a name="p15131654114417"></a><a name="p15131654114417"></a>您调用此API可以设置标记的旋转角度，即标记围绕标记锚点顺时针旋转的角度，旋转轴垂直于标记。默认旋转角度为0，默认位置为北对齐。</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table16809mcpsimp"></a>
<table><thead align="left"><tr id="row16814mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p16816mcpsimp"><a name="p16816mcpsimp"></a><a name="p16816mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p16818mcpsimp"><a name="p16818mcpsimp"></a><a name="p16818mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row16819mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p16821mcpsimp"><a name="p16821mcpsimp"></a><a name="p16821mcpsimp"></a>rotation</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p16823mcpsimp"><a name="p16823mcpsimp"></a><a name="p16823mcpsimp"></a>标记的旋转角度，默认值为0。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table16826mcpsimp"></a>
<table><thead align="left"><tr id="row16831mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p16833mcpsimp"><a name="p16833mcpsimp"></a><a name="p16833mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p16835mcpsimp"><a name="p16835mcpsimp"></a><a name="p16835mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row16836mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p16838mcpsimp"><a name="p16838mcpsimp"></a><a name="p16838mcpsimp"></a>MarkerOptions</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p16840mcpsimp"><a name="p16840mcpsimp"></a><a name="p16840mcpsimp"></a>设置新的旋转角度后的<a href="markeroptions.md">MarkerOptions</a>对象。</p>
</td>
</tr>
</tbody>
</table>

## snippet<a name="section1266276203610"></a>

<a name="table16842mcpsimp"></a>
<table><thead align="left"><tr id="row16846mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p16848mcpsimp"><a name="p16848mcpsimp"></a><a name="p16848mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row16849mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p16851mcpsimp"><a name="p16851mcpsimp"></a><a name="p16851mcpsimp"></a>public <a href="markeroptions.md">MarkerOptions</a> snippet(String snippet)</p>
<p id="p16854mcpsimp"><a name="p16854mcpsimp"></a><a name="p16854mcpsimp"></a>您调用此API可以设置标记的文字片段。</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table16857mcpsimp"></a>
<table><thead align="left"><tr id="row16862mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p16864mcpsimp"><a name="p16864mcpsimp"></a><a name="p16864mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p16866mcpsimp"><a name="p16866mcpsimp"></a><a name="p16866mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row16867mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p16869mcpsimp"><a name="p16869mcpsimp"></a><a name="p16869mcpsimp"></a>snippet</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p16871mcpsimp"><a name="p16871mcpsimp"></a><a name="p16871mcpsimp"></a>文字片段。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table16874mcpsimp"></a>
<table><thead align="left"><tr id="row16879mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p16881mcpsimp"><a name="p16881mcpsimp"></a><a name="p16881mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p16883mcpsimp"><a name="p16883mcpsimp"></a><a name="p16883mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row16884mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p16886mcpsimp"><a name="p16886mcpsimp"></a><a name="p16886mcpsimp"></a>MarkerOptions</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p16888mcpsimp"><a name="p16888mcpsimp"></a><a name="p16888mcpsimp"></a>设置新的文字片段后的<a href="markeroptions.md">MarkerOptions</a>对象。</p>
</td>
</tr>
</tbody>
</table>

## title<a name="section144310304569"></a>

<a name="table108031919125615"></a>
<table><thead align="left"><tr id="row16915319185615"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p69151619185613"><a name="p69151619185613"></a><a name="p69151619185613"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row1291581917565"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p7915111917564"><a name="p7915111917564"></a><a name="p7915111917564"></a>public <a href="markeroptions.md">MarkerOptions</a> title(String title)</p>
<p id="p7962145512514"><a name="p7962145512514"></a><a name="p7962145512514"></a>您调用此API可以设置标记的标题。</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table78111919175616"></a>
<table><thead align="left"><tr id="row0916171985616"><th class="cellrowborder" valign="top" width="47.589999999999996%" id="mcps1.1.3.1.1"><p id="p250mcpsimp"><a name="p250mcpsimp"></a><a name="p250mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="52.410000000000004%" id="mcps1.1.3.1.2"><p id="p253mcpsimp"><a name="p253mcpsimp"></a><a name="p253mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row19916191975610"><td class="cellrowborder" valign="top" width="47.589999999999996%" headers="mcps1.1.3.1.1 "><p id="p18916191912569"><a name="p18916191912569"></a><a name="p18916191912569"></a>title</p>
</td>
<td class="cellrowborder" valign="top" width="52.410000000000004%" headers="mcps1.1.3.1.2 "><p id="p1491701955612"><a name="p1491701955612"></a><a name="p1491701955612"></a>标题。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table1781410191560"></a>
<table><thead align="left"><tr id="row1991721918563"><th class="cellrowborder" valign="top" width="48.02%" id="mcps1.1.3.1.1"><p id="p374mcpsimp"><a name="p374mcpsimp"></a><a name="p374mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="51.980000000000004%" id="mcps1.1.3.1.2"><p id="p377mcpsimp"><a name="p377mcpsimp"></a><a name="p377mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row19173197565"><td class="cellrowborder" valign="top" width="48.02%" headers="mcps1.1.3.1.1 "><p id="p1691713193566"><a name="p1691713193566"></a><a name="p1691713193566"></a>MarkerOptions</p>
</td>
<td class="cellrowborder" valign="top" width="51.980000000000004%" headers="mcps1.1.3.1.2 "><p id="p139171619195619"><a name="p139171619195619"></a><a name="p139171619195619"></a>设置新的标题后的<a href="markeroptions.md">MarkerOptions</a>对象。</p>
</td>
</tr>
</tbody>
</table>

## visible<a name="section47301652195614"></a>

<a name="table1254711442561"></a>
<table><thead align="left"><tr id="row14669174425614"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p20669544135620"><a name="p20669544135620"></a><a name="p20669544135620"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row106694445560"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p86705442562"><a name="p86705442562"></a><a name="p86705442562"></a>public <a href="markeroptions.md">MarkerOptions</a> visible(boolean visible)</p>
<p id="p6670154435619"><a name="p6670154435619"></a><a name="p6670154435619"></a>您调用此API可以设置标记的可见性。</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table9552104416564"></a>
<table><thead align="left"><tr id="row867018443566"><th class="cellrowborder" valign="top" width="47.589999999999996%" id="mcps1.1.3.1.1"><p id="p1069111142332"><a name="p1069111142332"></a><a name="p1069111142332"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="52.410000000000004%" id="mcps1.1.3.1.2"><p id="p10691514153314"><a name="p10691514153314"></a><a name="p10691514153314"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row767004445611"><td class="cellrowborder" valign="top" width="47.589999999999996%" headers="mcps1.1.3.1.1 "><p id="p166701644175611"><a name="p166701644175611"></a><a name="p166701644175611"></a>visible</p>
</td>
<td class="cellrowborder" valign="top" width="52.410000000000004%" headers="mcps1.1.3.1.2 "><p id="p96704448564"><a name="p96704448564"></a><a name="p96704448564"></a>标记的可见性，true为可见，false为不可见。默认值为true。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table18559194411569"></a>
<table><thead align="left"><tr id="row3671184410567"><th class="cellrowborder" valign="top" width="48.02%" id="mcps1.1.3.1.1"><p id="p13175205114327"><a name="p13175205114327"></a><a name="p13175205114327"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="51.980000000000004%" id="mcps1.1.3.1.2"><p id="p18175135113329"><a name="p18175135113329"></a><a name="p18175135113329"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row156711344165618"><td class="cellrowborder" valign="top" width="48.02%" headers="mcps1.1.3.1.1 "><p id="p1567174410562"><a name="p1567174410562"></a><a name="p1567174410562"></a>MarkerOptions</p>
</td>
<td class="cellrowborder" valign="top" width="51.980000000000004%" headers="mcps1.1.3.1.2 "><p id="p5671344115617"><a name="p5671344115617"></a><a name="p5671344115617"></a>设置新的可见性后的<a href="markeroptions.md">MarkerOptions</a>对象。</p>
</td>
</tr>
</tbody>
</table>

## zIndex<a name="section551291175715"></a>

<a name="table741011419574"></a>
<table><thead align="left"><tr id="row145151541572"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p1351610415717"><a name="p1351610415717"></a><a name="p1351610415717"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row1551610485713"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p125161475710"><a name="p125161475710"></a><a name="p125161475710"></a>public <a href="markeroptions.md">MarkerOptions</a> zIndex(float zIndex)</p>
<p id="p1551694195720"><a name="p1551694195720"></a><a name="p1551694195720"></a>用于设置标记的z指数。z指数指的是标记的叠加顺序，具有较大z指数的标记会绘制在具有较小z指数的标记上，具有相同z指数的叠加顺序为元素添加的先后顺序。</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table641610415715"></a>
<table><thead align="left"><tr id="row105168445718"><th class="cellrowborder" valign="top" width="47.589999999999996%" id="mcps1.1.3.1.1"><p id="p12659122893310"><a name="p12659122893310"></a><a name="p12659122893310"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="52.410000000000004%" id="mcps1.1.3.1.2"><p id="p965942819339"><a name="p965942819339"></a><a name="p965942819339"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row105161142577"><td class="cellrowborder" valign="top" width="47.589999999999996%" headers="mcps1.1.3.1.1 "><p id="p151618411572"><a name="p151618411572"></a><a name="p151618411572"></a>zIndex</p>
</td>
<td class="cellrowborder" valign="top" width="52.410000000000004%" headers="mcps1.1.3.1.2 "><p id="p1516194195715"><a name="p1516194195715"></a><a name="p1516194195715"></a>z指数，即标记的叠加顺序。默认的z指数是0。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table541918413577"></a>
<table><thead align="left"><tr id="row10516144165712"><th class="cellrowborder" valign="top" width="48.02%" id="mcps1.1.3.1.1"><p id="p2219744183310"><a name="p2219744183310"></a><a name="p2219744183310"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="51.980000000000004%" id="mcps1.1.3.1.2"><p id="p15220164403312"><a name="p15220164403312"></a><a name="p15220164403312"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row1551754115718"><td class="cellrowborder" valign="top" width="48.02%" headers="mcps1.1.3.1.1 "><p id="p17517540573"><a name="p17517540573"></a><a name="p17517540573"></a>MarkerOptions</p>
</td>
<td class="cellrowborder" valign="top" width="51.980000000000004%" headers="mcps1.1.3.1.2 "><p id="p1351717495717"><a name="p1351717495717"></a><a name="p1351717495717"></a>设置新的z指数后的<a href="markeroptions.md">MarkerOptions</a>对象。</p>
</td>
</tr>
</tbody>
</table>

