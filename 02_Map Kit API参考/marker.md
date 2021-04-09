# Marker<a name="ZH-CN_TOPIC_0000001145860955"></a>

-   [Public Method Summary](#section198571651191315)
-   [Public Methods](#section166797915511)
-   [equals](#section9995901416)
-   [getAlpha](#section19252111810145)
-   [getId](#section105771527101411)
-   [getPosition](#section49343761418)
-   [getRotation](#section26741745121414)
-   [getSnippet](#section7851155271416)
-   [getTag](#section1625517241520)
-   [getTitle](#section15178141116154)
-   [getZIndex](#section381418141514)
-   [hashCode](#section075815268151)
-   [hideInfoWindow](#section352393481515)
-   [isClusterable](#section12103164219159)
-   [isDraggable](#section1947358193318)
-   [isFlat](#section16358133310341)
-   [isInfoWindowShown](#section643110419342)
-   [isVisible](#section2207551183412)
-   [remove](#section6594131123511)
-   [setAlpha](#section1776118819353)
-   [setAnchor](#section14156191615354)
-   [setAnimation](#section138322612114)
-   [setDraggable](#section58671625103515)
-   [setFlat](#section1797433173511)
-   [setIcon](#section1680710531355)
-   [setInfoWindowAnchor](#section1858016183620)
-   [setMarkerAnchor](#section992613197119)
-   [setPosition](#section13917151362)
-   [h2setRotation](#section1989919222361)
-   [setSnippet](#section165927340363)
-   [setTag](#section893234843611)
-   [setTitle](#section13963185519361)
-   [setVisible](#section1775916212376)
-   [setZIndex](#section952413920376)
-   [showInfoWindow](#section13223817123711)
-   [startAnimation](#section13557451287)


<a name="table14555mcpsimp"></a>
<table><thead align="left"><tr id="row14559mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p14561mcpsimp"><a name="p14561mcpsimp"></a><a name="p14561mcpsimp"></a>Class Info</p>
</th>
</tr>
</thead>
<tbody><tr id="row14562mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p182061719416"><a name="p182061719416"></a><a name="p182061719416"></a>public class Marker</p>
<p id="p14564mcpsimp"><a name="p14564mcpsimp"></a><a name="p14564mcpsimp"></a>放在地图指定位置的图标，在调用<a href="huaweimap.md">HuaweiMap</a>类的<a href="huaweimap.md#section84151866413">addMarker</a>方法时会返回该类型的实例。</p>
</td>
</tr>
</tbody>
</table>

## Public Method Summary<a name="section198571651191315"></a>

<a name="table14579mcpsimp"></a>
<table><thead align="left"><tr id="row14584mcpsimp"><th class="cellrowborder" valign="top" width="40%" id="mcps1.1.3.1.1"><p id="p081120285386"><a name="p081120285386"></a><a name="p081120285386"></a>Qualifier and Type</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.1.3.1.2"><p id="p681112883813"><a name="p681112883813"></a><a name="p681112883813"></a>Method Name and Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row14589mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p14591mcpsimp"><a name="p14591mcpsimp"></a><a name="p14591mcpsimp"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p14593mcpsimp"><a name="p14593mcpsimp"></a><a name="p14593mcpsimp"></a><a href="#section9995901416">equals</a>(Object other)</p>
<p id="p66142485254"><a name="p66142485254"></a><a name="p66142485254"></a>判断两个标记对象是否相等。</p>
</td>
</tr>
<tr id="row14594mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p14596mcpsimp"><a name="p14596mcpsimp"></a><a name="p14596mcpsimp"></a>float</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p14598mcpsimp"><a name="p14598mcpsimp"></a><a name="p14598mcpsimp"></a><a href="#section19252111810145">getAlpha</a>()</p>
<p id="p1656154918258"><a name="p1656154918258"></a><a name="p1656154918258"></a>获取标记的透明度。</p>
</td>
</tr>
<tr id="row14599mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p14601mcpsimp"><a name="p14601mcpsimp"></a><a name="p14601mcpsimp"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p14603mcpsimp"><a name="p14603mcpsimp"></a><a name="p14603mcpsimp"></a><a href="#section105771527101411">getId</a>()</p>
<p id="p105901850152516"><a name="p105901850152516"></a><a name="p105901850152516"></a>获取标记的ID属性。</p>
</td>
</tr>
<tr id="row14604mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p14606mcpsimp"><a name="p14606mcpsimp"></a><a name="p14606mcpsimp"></a>LatLng</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p14608mcpsimp"><a name="p14608mcpsimp"></a><a name="p14608mcpsimp"></a><a href="#section49343761418">getPosition</a>()</p>
<p id="p20457195112258"><a name="p20457195112258"></a><a name="p20457195112258"></a>获取标记的位置。</p>
</td>
</tr>
<tr id="row14609mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p14611mcpsimp"><a name="p14611mcpsimp"></a><a name="p14611mcpsimp"></a>float</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p14613mcpsimp"><a name="p14613mcpsimp"></a><a name="p14613mcpsimp"></a><a href="#section26741745121414">getRotation</a>()</p>
<p id="p1693045262519"><a name="p1693045262519"></a><a name="p1693045262519"></a>获取标记的旋转角度。</p>
</td>
</tr>
<tr id="row14614mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p14616mcpsimp"><a name="p14616mcpsimp"></a><a name="p14616mcpsimp"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p14618mcpsimp"><a name="p14618mcpsimp"></a><a name="p14618mcpsimp"></a><a href="#section7851155271416">getSnippet</a>()</p>
<p id="p12778195310257"><a name="p12778195310257"></a><a name="p12778195310257"></a>获取标记的文字片段。</p>
</td>
</tr>
<tr id="row14619mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p14621mcpsimp"><a name="p14621mcpsimp"></a><a name="p14621mcpsimp"></a>Object</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p14623mcpsimp"><a name="p14623mcpsimp"></a><a name="p14623mcpsimp"></a><a href="#section1625517241520">getTag</a>()</p>
<p id="p1467505414255"><a name="p1467505414255"></a><a name="p1467505414255"></a>获取标记的tag属性。</p>
</td>
</tr>
<tr id="row14624mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p14626mcpsimp"><a name="p14626mcpsimp"></a><a name="p14626mcpsimp"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p14628mcpsimp"><a name="p14628mcpsimp"></a><a name="p14628mcpsimp"></a><a href="#section15178141116154">getTitle</a>()</p>
<p id="p16472155517259"><a name="p16472155517259"></a><a name="p16472155517259"></a>获取标记的标题。</p>
</td>
</tr>
<tr id="row14629mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p14631mcpsimp"><a name="p14631mcpsimp"></a><a name="p14631mcpsimp"></a>float</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p14633mcpsimp"><a name="p14633mcpsimp"></a><a name="p14633mcpsimp"></a><a href="#section381418141514">getZIndex</a>()</p>
<p id="p6893185682517"><a name="p6893185682517"></a><a name="p6893185682517"></a>获取标记的z指数。</p>
</td>
</tr>
<tr id="row14634mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p14636mcpsimp"><a name="p14636mcpsimp"></a><a name="p14636mcpsimp"></a>int</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p14638mcpsimp"><a name="p14638mcpsimp"></a><a name="p14638mcpsimp"></a><a href="#section075815268151">hashCode</a>()</p>
<p id="p1476605762511"><a name="p1476605762511"></a><a name="p1476605762511"></a>获取标记的哈希值。</p>
</td>
</tr>
<tr id="row14639mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p14641mcpsimp"><a name="p14641mcpsimp"></a><a name="p14641mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p14643mcpsimp"><a name="p14643mcpsimp"></a><a name="p14643mcpsimp"></a><a href="#section352393481515">hideInfoWindow</a>()</p>
<p id="p1736105815257"><a name="p1736105815257"></a><a name="p1736105815257"></a>隐藏标记的标记信息窗口。</p>
</td>
</tr>
<tr id="row14644mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p14646mcpsimp"><a name="p14646mcpsimp"></a><a name="p14646mcpsimp"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p14648mcpsimp"><a name="p14648mcpsimp"></a><a name="p14648mcpsimp"></a><a href="#section12103164219159">isClusterable</a>()</p>
<p id="p14582205952519"><a name="p14582205952519"></a><a name="p14582205952519"></a>获取标记的聚合属性。</p>
</td>
</tr>
<tr id="row14649mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p14651mcpsimp"><a name="p14651mcpsimp"></a><a name="p14651mcpsimp"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p14653mcpsimp"><a name="p14653mcpsimp"></a><a name="p14653mcpsimp"></a><a href="#section1947358193318">isDraggable</a>()</p>
<p id="p7617100142616"><a name="p7617100142616"></a><a name="p7617100142616"></a>获取标记是否可以长按拖拽。</p>
</td>
</tr>
<tr id="row14654mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p14656mcpsimp"><a name="p14656mcpsimp"></a><a name="p14656mcpsimp"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p14658mcpsimp"><a name="p14658mcpsimp"></a><a name="p14658mcpsimp"></a><a href="#section16358133310341">isFlat</a>()</p>
<p id="p11274727264"><a name="p11274727264"></a><a name="p11274727264"></a>获取标记是否平贴地图。</p>
</td>
</tr>
<tr id="row14659mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p14661mcpsimp"><a name="p14661mcpsimp"></a><a name="p14661mcpsimp"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p14663mcpsimp"><a name="p14663mcpsimp"></a><a name="p14663mcpsimp"></a><a href="#section643110419342">isInfoWindowShown</a>()</p>
<p id="p120312362618"><a name="p120312362618"></a><a name="p120312362618"></a>获取标记的标记信息窗口是否在展示状态。</p>
</td>
</tr>
<tr id="row14664mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p14666mcpsimp"><a name="p14666mcpsimp"></a><a name="p14666mcpsimp"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p14668mcpsimp"><a name="p14668mcpsimp"></a><a name="p14668mcpsimp"></a><a href="#section2207551183412">isVisible</a>()</p>
<p id="p186510410268"><a name="p186510410268"></a><a name="p186510410268"></a>获取标记的可见性。</p>
</td>
</tr>
<tr id="row14669mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p14671mcpsimp"><a name="p14671mcpsimp"></a><a name="p14671mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p14673mcpsimp"><a name="p14673mcpsimp"></a><a name="p14673mcpsimp"></a><a href="#section6594131123511">remove</a>()</p>
<p id="p20782115202614"><a name="p20782115202614"></a><a name="p20782115202614"></a>从地图移除标记。</p>
</td>
</tr>
<tr id="row14674mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p14676mcpsimp"><a name="p14676mcpsimp"></a><a name="p14676mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p14678mcpsimp"><a name="p14678mcpsimp"></a><a name="p14678mcpsimp"></a><a href="#section1776118819353">setAlpha</a>(float alpha)</p>
<p id="p1675236152611"><a name="p1675236152611"></a><a name="p1675236152611"></a>设置标记的透明度属性。</p>
</td>
</tr>
<tr id="row14679mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p14681mcpsimp"><a name="p14681mcpsimp"></a><a name="p14681mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p14683mcpsimp"><a name="p14683mcpsimp"></a><a name="p14683mcpsimp"></a><a href="#section14156191615354">setAnchor</a>(float anchorU, float anchorV)</p>
<p id="p971615711269"><a name="p971615711269"></a><a name="p971615711269"></a>设置标记的锚点位置。</p>
<div class="caution" id="note09921736125511"><a name="note09921736125511"></a><a name="note09921736125511"></a><span class="cautiontitle"> 注意： </span><div class="cautionbody"><p id="p899283611556"><a name="p899283611556"></a><a name="p899283611556"></a>该接口已弃用，设置锚点位置请使用<a href="#section992613197119">setMarkerAnchor</a>。</p>
</div></div>
</td>
</tr>
<tr id="row123527111969"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p5353161116615"><a name="p5353161116615"></a><a name="p5353161116615"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p43531411566"><a name="p43531411566"></a><a name="p43531411566"></a><a href="#section138322612114">setAnimation</a>(<a href="animation.md">Animation</a> animation)</p>
<p id="p888716872612"><a name="p888716872612"></a><a name="p888716872612"></a>设置标记的动画。</p>
</td>
</tr>
<tr id="row14684mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p14686mcpsimp"><a name="p14686mcpsimp"></a><a name="p14686mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p14688mcpsimp"><a name="p14688mcpsimp"></a><a name="p14688mcpsimp"></a><a href="#section58671625103515">setDraggable</a>(boolean draggable)</p>
<p id="p10760139162615"><a name="p10760139162615"></a><a name="p10760139162615"></a>设置标记是否可以长按拖拽。</p>
</td>
</tr>
<tr id="row14689mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p14691mcpsimp"><a name="p14691mcpsimp"></a><a name="p14691mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p14693mcpsimp"><a name="p14693mcpsimp"></a><a name="p14693mcpsimp"></a><a href="#section1797433173511">setFlat</a>(boolean flat)</p>
<p id="p1769719100267"><a name="p1769719100267"></a><a name="p1769719100267"></a>设置标记是否平贴地图。</p>
</td>
</tr>
<tr id="row14694mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p14696mcpsimp"><a name="p14696mcpsimp"></a><a name="p14696mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p14698mcpsimp"><a name="p14698mcpsimp"></a><a name="p14698mcpsimp"></a><a href="#section1680710531355">setIcon</a>(<a href="bitmapdescriptor.md">BitmapDescriptor </a>iconDescriptor)</p>
<p id="p0196101216263"><a name="p0196101216263"></a><a name="p0196101216263"></a>设置标记的图标。</p>
</td>
</tr>
<tr id="row14699mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p14701mcpsimp"><a name="p14701mcpsimp"></a><a name="p14701mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p14703mcpsimp"><a name="p14703mcpsimp"></a><a name="p14703mcpsimp"></a><a href="#section1858016183620">setInfoWindowAnchor</a>(float anchorU, float anchorV)</p>
<p id="p14385111313268"><a name="p14385111313268"></a><a name="p14385111313268"></a>设置标记的标记信息窗口的锚点坐标， 这是在与锚点相同的坐标系中指定的， 默认值为标记图像的顶部中间。</p>
</td>
</tr>
<tr id="row1810414251193"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p954343512229"><a name="p954343512229"></a><a name="p954343512229"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p1054453516229"><a name="p1054453516229"></a><a name="p1054453516229"></a><a href="#section992613197119">setMarkerAnchor</a>(float anchorU, float anchorV)</p>
<p id="p20386111452613"><a name="p20386111452613"></a><a name="p20386111452613"></a>设置标记的锚点位置。</p>
</td>
</tr>
<tr id="row14704mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p14706mcpsimp"><a name="p14706mcpsimp"></a><a name="p14706mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p14708mcpsimp"><a name="p14708mcpsimp"></a><a name="p14708mcpsimp"></a><a href="#section13917151362">setPosition</a>(<a href="latlng.md">LatLng</a> latLng)</p>
<p id="p1751471572611"><a name="p1751471572611"></a><a name="p1751471572611"></a>设置标记的位置坐标。</p>
</td>
</tr>
<tr id="row14709mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p14711mcpsimp"><a name="p14711mcpsimp"></a><a name="p14711mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p14713mcpsimp"><a name="p14713mcpsimp"></a><a name="p14713mcpsimp"></a><a href="#section1989919222361">setRotation</a>(float rotation)</p>
<p id="p85211916152619"><a name="p85211916152619"></a><a name="p85211916152619"></a>设置标记的旋转角度，即标记围绕标记锚点顺时针旋转的角度，旋转轴垂直于标记。</p>
</td>
</tr>
<tr id="row14714mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p14716mcpsimp"><a name="p14716mcpsimp"></a><a name="p14716mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p14718mcpsimp"><a name="p14718mcpsimp"></a><a name="p14718mcpsimp"></a><a href="#section165927340363">setSnippet</a>(String snippet)</p>
<p id="p1886851792615"><a name="p1886851792615"></a><a name="p1886851792615"></a>设置标记的文字片段，如果为空，则不显示文字片段。</p>
</td>
</tr>
<tr id="row14719mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p14721mcpsimp"><a name="p14721mcpsimp"></a><a name="p14721mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p14723mcpsimp"><a name="p14723mcpsimp"></a><a name="p14723mcpsimp"></a><a href="#section893234843611">setTag</a>(Object tag)</p>
<p id="p9926718172611"><a name="p9926718172611"></a><a name="p9926718172611"></a>设置标记的tag属性，如果为空，则清除tag。</p>
</td>
</tr>
<tr id="row14724mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p14726mcpsimp"><a name="p14726mcpsimp"></a><a name="p14726mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p14728mcpsimp"><a name="p14728mcpsimp"></a><a name="p14728mcpsimp"></a><a href="#section13963185519361">setTitle</a>(String title)</p>
<p id="p1690921922613"><a name="p1690921922613"></a><a name="p1690921922613"></a>设置标记的标题，默认为空。</p>
</td>
</tr>
<tr id="row14729mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p14731mcpsimp"><a name="p14731mcpsimp"></a><a name="p14731mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p14733mcpsimp"><a name="p14733mcpsimp"></a><a name="p14733mcpsimp"></a><a href="#section1775916212376">setVisible</a>(boolean visible)</p>
<p id="p1871216205268"><a name="p1871216205268"></a><a name="p1871216205268"></a>设置标记的可见性。</p>
</td>
</tr>
<tr id="row14734mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p14736mcpsimp"><a name="p14736mcpsimp"></a><a name="p14736mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p14738mcpsimp"><a name="p14738mcpsimp"></a><a name="p14738mcpsimp"></a><a href="#section952413920376">setZIndex</a>(float zIndex)</p>
<p id="p1266310217269"><a name="p1266310217269"></a><a name="p1266310217269"></a>设置标记的z指数。</p>
</td>
</tr>
<tr id="row14739mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p14741mcpsimp"><a name="p14741mcpsimp"></a><a name="p14741mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p14743mcpsimp"><a name="p14743mcpsimp"></a><a name="p14743mcpsimp"></a><a href="#section13223817123711">showInfoWindow</a>()</p>
<p id="p6674112213261"><a name="p6674112213261"></a><a name="p6674112213261"></a>展示标记的标记信息窗口。</p>
</td>
</tr>
<tr id="row19417124219719"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p174190197816"><a name="p174190197816"></a><a name="p174190197816"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p1441818421379"><a name="p1441818421379"></a><a name="p1441818421379"></a><a href="#section13557451287">startAnimation</a>()</p>
<p id="p137221523202615"><a name="p137221523202615"></a><a name="p137221523202615"></a>使标记开始动画。</p>
</td>
</tr>
</tbody>
</table>

## Public Methods<a name="section166797915511"></a>

## equals<a name="section9995901416"></a>

<a name="table14746mcpsimp"></a>
<table><thead align="left"><tr id="row14750mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p14752mcpsimp"><a name="p14752mcpsimp"></a><a name="p14752mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row14753mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p14755mcpsimp"><a name="p14755mcpsimp"></a><a name="p14755mcpsimp"></a>public boolean equals(Object other)</p>
<p id="p1599420174915"><a name="p1599420174915"></a><a name="p1599420174915"></a>判断两个标记对象是否相等。</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table14761mcpsimp"></a>
<table><thead align="left"><tr id="row14766mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p14768mcpsimp"><a name="p14768mcpsimp"></a><a name="p14768mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p14770mcpsimp"><a name="p14770mcpsimp"></a><a name="p14770mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row14771mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p14773mcpsimp"><a name="p14773mcpsimp"></a><a name="p14773mcpsimp"></a>other</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p14775mcpsimp"><a name="p14775mcpsimp"></a><a name="p14775mcpsimp"></a>另一对象。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table14778mcpsimp"></a>
<table><thead align="left"><tr id="row14783mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p14785mcpsimp"><a name="p14785mcpsimp"></a><a name="p14785mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p14787mcpsimp"><a name="p14787mcpsimp"></a><a name="p14787mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row14788mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p14790mcpsimp"><a name="p14790mcpsimp"></a><a name="p14790mcpsimp"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p14792mcpsimp"><a name="p14792mcpsimp"></a><a name="p14792mcpsimp"></a>标记对象是否相等。true为相等，false为不相等。</p>
</td>
</tr>
</tbody>
</table>

## getAlpha<a name="section19252111810145"></a>

<a name="table14794mcpsimp"></a>
<table><thead align="left"><tr id="row14798mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p14800mcpsimp"><a name="p14800mcpsimp"></a><a name="p14800mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row14801mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p14803mcpsimp"><a name="p14803mcpsimp"></a><a name="p14803mcpsimp"></a>public float getAlpha()</p>
<p id="p57331210154914"><a name="p57331210154914"></a><a name="p57331210154914"></a>您调用此API可以获取标记的透明度。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table14812mcpsimp"></a>
<table><thead align="left"><tr id="row14817mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p14819mcpsimp"><a name="p14819mcpsimp"></a><a name="p14819mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p14821mcpsimp"><a name="p14821mcpsimp"></a><a name="p14821mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row14822mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p14824mcpsimp"><a name="p14824mcpsimp"></a><a name="p14824mcpsimp"></a>float</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p14826mcpsimp"><a name="p14826mcpsimp"></a><a name="p14826mcpsimp"></a>标记的透明度，取值范围：[0, 1]。</p>
</td>
</tr>
</tbody>
</table>

## getId<a name="section105771527101411"></a>

<a name="table14828mcpsimp"></a>
<table><thead align="left"><tr id="row14832mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p14834mcpsimp"><a name="p14834mcpsimp"></a><a name="p14834mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row14835mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p14837mcpsimp"><a name="p14837mcpsimp"></a><a name="p14837mcpsimp"></a>public final String getId()</p>
<p id="p14840mcpsimp"><a name="p14840mcpsimp"></a><a name="p14840mcpsimp"></a>您调用此API可以获取标记的ID属性，该ID在地图上的所有标记中都是唯一的。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table14846mcpsimp"></a>
<table><thead align="left"><tr id="row14851mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p14853mcpsimp"><a name="p14853mcpsimp"></a><a name="p14853mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p14855mcpsimp"><a name="p14855mcpsimp"></a><a name="p14855mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row14856mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p14858mcpsimp"><a name="p14858mcpsimp"></a><a name="p14858mcpsimp"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p14860mcpsimp"><a name="p14860mcpsimp"></a><a name="p14860mcpsimp"></a>标记的ID属性。</p>
</td>
</tr>
</tbody>
</table>

## getPosition<a name="section49343761418"></a>

<a name="table14862mcpsimp"></a>
<table><thead align="left"><tr id="row14866mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p14868mcpsimp"><a name="p14868mcpsimp"></a><a name="p14868mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row14869mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p14871mcpsimp"><a name="p14871mcpsimp"></a><a name="p14871mcpsimp"></a>public final <a href="latlng.md">LatLng</a> getPosition()</p>
<p id="p1538316283490"><a name="p1538316283490"></a><a name="p1538316283490"></a>您调用此API可以获取标记的位置。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table14880mcpsimp"></a>
<table><thead align="left"><tr id="row14885mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p14887mcpsimp"><a name="p14887mcpsimp"></a><a name="p14887mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p14889mcpsimp"><a name="p14889mcpsimp"></a><a name="p14889mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row14890mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p14892mcpsimp"><a name="p14892mcpsimp"></a><a name="p14892mcpsimp"></a><a href="latlng.md">LatLng</a></p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p14894mcpsimp"><a name="p14894mcpsimp"></a><a name="p14894mcpsimp"></a>标记的位置。</p>
</td>
</tr>
</tbody>
</table>

## getRotation<a name="section26741745121414"></a>

<a name="table14896mcpsimp"></a>
<table><thead align="left"><tr id="row14900mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p14902mcpsimp"><a name="p14902mcpsimp"></a><a name="p14902mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row14903mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p14905mcpsimp"><a name="p14905mcpsimp"></a><a name="p14905mcpsimp"></a>public final float getRotation()</p>
<p id="p31331635134914"><a name="p31331635134914"></a><a name="p31331635134914"></a>您调用此API可以获取标记的旋转角度。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table14914mcpsimp"></a>
<table><thead align="left"><tr id="row14919mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p14921mcpsimp"><a name="p14921mcpsimp"></a><a name="p14921mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p14923mcpsimp"><a name="p14923mcpsimp"></a><a name="p14923mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row14924mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p14926mcpsimp"><a name="p14926mcpsimp"></a><a name="p14926mcpsimp"></a>float</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p14928mcpsimp"><a name="p14928mcpsimp"></a><a name="p14928mcpsimp"></a>标记的旋转角度。</p>
</td>
</tr>
</tbody>
</table>

## getSnippet<a name="section7851155271416"></a>

<a name="table14930mcpsimp"></a>
<table><thead align="left"><tr id="row14934mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p14936mcpsimp"><a name="p14936mcpsimp"></a><a name="p14936mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row14937mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p14939mcpsimp"><a name="p14939mcpsimp"></a><a name="p14939mcpsimp"></a>public final String getSnippet()</p>
<p id="p14942mcpsimp"><a name="p14942mcpsimp"></a><a name="p14942mcpsimp"></a>您调用此API可以获取标记的文字片段。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table14948mcpsimp"></a>
<table><thead align="left"><tr id="row14953mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p14955mcpsimp"><a name="p14955mcpsimp"></a><a name="p14955mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p14957mcpsimp"><a name="p14957mcpsimp"></a><a name="p14957mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row14958mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p14960mcpsimp"><a name="p14960mcpsimp"></a><a name="p14960mcpsimp"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p14962mcpsimp"><a name="p14962mcpsimp"></a><a name="p14962mcpsimp"></a>标记的文字片段。</p>
</td>
</tr>
</tbody>
</table>

## getTag<a name="section1625517241520"></a>

<a name="table14964mcpsimp"></a>
<table><thead align="left"><tr id="row14968mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p14970mcpsimp"><a name="p14970mcpsimp"></a><a name="p14970mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row14971mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p14973mcpsimp"><a name="p14973mcpsimp"></a><a name="p14973mcpsimp"></a>public Object getTag()</p>
<p id="p3192144910492"><a name="p3192144910492"></a><a name="p3192144910492"></a>您调用此API将获取标记的tag属性（如果标记的tag属性已被设置）。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table14982mcpsimp"></a>
<table><thead align="left"><tr id="row14987mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p14989mcpsimp"><a name="p14989mcpsimp"></a><a name="p14989mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p14991mcpsimp"><a name="p14991mcpsimp"></a><a name="p14991mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row14992mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p14994mcpsimp"><a name="p14994mcpsimp"></a><a name="p14994mcpsimp"></a>Object</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p14996mcpsimp"><a name="p14996mcpsimp"></a><a name="p14996mcpsimp"></a>标记的tag属性。如果已设置tag，则返回Object；如果未设置，则返回null。</p>
</td>
</tr>
</tbody>
</table>

## getTitle<a name="section15178141116154"></a>

<a name="table14998mcpsimp"></a>
<table><thead align="left"><tr id="row15002mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p15004mcpsimp"><a name="p15004mcpsimp"></a><a name="p15004mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row15005mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p15007mcpsimp"><a name="p15007mcpsimp"></a><a name="p15007mcpsimp"></a>public final String getTitle()</p>
<p id="p6458141045014"><a name="p6458141045014"></a><a name="p6458141045014"></a>您调用此API可以获取标记的标题。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table15016mcpsimp"></a>
<table><thead align="left"><tr id="row15021mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p15023mcpsimp"><a name="p15023mcpsimp"></a><a name="p15023mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p15025mcpsimp"><a name="p15025mcpsimp"></a><a name="p15025mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row15026mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p15028mcpsimp"><a name="p15028mcpsimp"></a><a name="p15028mcpsimp"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p15030mcpsimp"><a name="p15030mcpsimp"></a><a name="p15030mcpsimp"></a>标记的标题，字符串对象。</p>
</td>
</tr>
</tbody>
</table>

## getZIndex<a name="section381418141514"></a>

<a name="table15032mcpsimp"></a>
<table><thead align="left"><tr id="row15036mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p15038mcpsimp"><a name="p15038mcpsimp"></a><a name="p15038mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row15039mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p15041mcpsimp"><a name="p15041mcpsimp"></a><a name="p15041mcpsimp"></a>public float getZIndex()</p>
<p id="p516541812508"><a name="p516541812508"></a><a name="p516541812508"></a>您调用此API可以获取标记的z指数。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table15050mcpsimp"></a>
<table><thead align="left"><tr id="row15055mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p15057mcpsimp"><a name="p15057mcpsimp"></a><a name="p15057mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p15059mcpsimp"><a name="p15059mcpsimp"></a><a name="p15059mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row15060mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p15062mcpsimp"><a name="p15062mcpsimp"></a><a name="p15062mcpsimp"></a>float</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p15064mcpsimp"><a name="p15064mcpsimp"></a><a name="p15064mcpsimp"></a>z指数，即标记的叠加顺序。</p>
</td>
</tr>
</tbody>
</table>

## hashCode<a name="section075815268151"></a>

<a name="table15066mcpsimp"></a>
<table><thead align="left"><tr id="row15070mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p15072mcpsimp"><a name="p15072mcpsimp"></a><a name="p15072mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row15073mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p15075mcpsimp"><a name="p15075mcpsimp"></a><a name="p15075mcpsimp"></a>public int hashCode()</p>
<p id="p159418102437"><a name="p159418102437"></a><a name="p159418102437"></a>您调用此API可以获取标记的哈希值。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table15084mcpsimp"></a>
<table><thead align="left"><tr id="row15089mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p15091mcpsimp"><a name="p15091mcpsimp"></a><a name="p15091mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p15093mcpsimp"><a name="p15093mcpsimp"></a><a name="p15093mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row15094mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p15096mcpsimp"><a name="p15096mcpsimp"></a><a name="p15096mcpsimp"></a>int</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p15098mcpsimp"><a name="p15098mcpsimp"></a><a name="p15098mcpsimp"></a>标记的哈希值。</p>
</td>
</tr>
</tbody>
</table>

## hideInfoWindow<a name="section352393481515"></a>

<a name="table15100mcpsimp"></a>
<table><thead align="left"><tr id="row15104mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p15106mcpsimp"><a name="p15106mcpsimp"></a><a name="p15106mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row15107mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p15109mcpsimp"><a name="p15109mcpsimp"></a><a name="p15109mcpsimp"></a>public final void hideInfoWindow()</p>
<p id="p198009220432"><a name="p198009220432"></a><a name="p198009220432"></a>您调用此API时可以隐藏标记的标记信息窗口，如果标记显示了信息窗口，则将其隐藏。如果标记不可见，则此方法无效。</p>
</td>
</tr>
</tbody>
</table>

## isClusterable<a name="section12103164219159"></a>

<a name="table15120mcpsimp"></a>
<table><thead align="left"><tr id="row15124mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p15126mcpsimp"><a name="p15126mcpsimp"></a><a name="p15126mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row15127mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p15129mcpsimp"><a name="p15129mcpsimp"></a><a name="p15129mcpsimp"></a>public boolean isClusterable()</p>
<p id="p674523116438"><a name="p674523116438"></a><a name="p674523116438"></a>您调用此API可以获取标记的聚合属性。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table15138mcpsimp"></a>
<table><thead align="left"><tr id="row15143mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p15145mcpsimp"><a name="p15145mcpsimp"></a><a name="p15145mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p15147mcpsimp"><a name="p15147mcpsimp"></a><a name="p15147mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row15148mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p15150mcpsimp"><a name="p15150mcpsimp"></a><a name="p15150mcpsimp"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p15152mcpsimp"><a name="p15152mcpsimp"></a><a name="p15152mcpsimp"></a>表示该标记是否可聚合，true表示可聚合，false表示不可聚合。</p>
</td>
</tr>
</tbody>
</table>

## isDraggable<a name="section1947358193318"></a>

<a name="table15154mcpsimp"></a>
<table><thead align="left"><tr id="row15158mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p15160mcpsimp"><a name="p15160mcpsimp"></a><a name="p15160mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row15161mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p15163mcpsimp"><a name="p15163mcpsimp"></a><a name="p15163mcpsimp"></a>public final boolean isDraggable()</p>
<p id="p1830744914435"><a name="p1830744914435"></a><a name="p1830744914435"></a>您调用此API可以获取标记是否可以长按拖拽。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table15172mcpsimp"></a>
<table><thead align="left"><tr id="row15177mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p15179mcpsimp"><a name="p15179mcpsimp"></a><a name="p15179mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p15181mcpsimp"><a name="p15181mcpsimp"></a><a name="p15181mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row15182mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p15184mcpsimp"><a name="p15184mcpsimp"></a><a name="p15184mcpsimp"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p15186mcpsimp"><a name="p15186mcpsimp"></a><a name="p15186mcpsimp"></a>表示是否可以长按拖拽，true为可以，false为不可以。</p>
</td>
</tr>
</tbody>
</table>

## isFlat<a name="section16358133310341"></a>

<a name="table15188mcpsimp"></a>
<table><thead align="left"><tr id="row15192mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p15194mcpsimp"><a name="p15194mcpsimp"></a><a name="p15194mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row15195mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p15197mcpsimp"><a name="p15197mcpsimp"></a><a name="p15197mcpsimp"></a>public final boolean isFlat()</p>
<p id="p167018724417"><a name="p167018724417"></a><a name="p167018724417"></a>您调用此API可以获取标记是否平贴地图。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table15206mcpsimp"></a>
<table><thead align="left"><tr id="row15211mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p15213mcpsimp"><a name="p15213mcpsimp"></a><a name="p15213mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p15215mcpsimp"><a name="p15215mcpsimp"></a><a name="p15215mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row15216mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p15218mcpsimp"><a name="p15218mcpsimp"></a><a name="p15218mcpsimp"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p15220mcpsimp"><a name="p15220mcpsimp"></a><a name="p15220mcpsimp"></a>表示是否平贴地图，true为平贴地图，false为面对相机。</p>
</td>
</tr>
</tbody>
</table>

## isInfoWindowShown<a name="section643110419342"></a>

<a name="table15222mcpsimp"></a>
<table><thead align="left"><tr id="row15226mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p15228mcpsimp"><a name="p15228mcpsimp"></a><a name="p15228mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row15229mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p15231mcpsimp"><a name="p15231mcpsimp"></a><a name="p15231mcpsimp"></a>public final boolean isInfoWindowShown()</p>
<p id="p2140182544411"><a name="p2140182544411"></a><a name="p2140182544411"></a>您调用此API可以获取标记的标记信息窗口是否在展示状态，这不会考虑标记信息窗口在屏幕上是否实际可见。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table15240mcpsimp"></a>
<table><thead align="left"><tr id="row15245mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p15247mcpsimp"><a name="p15247mcpsimp"></a><a name="p15247mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p15249mcpsimp"><a name="p15249mcpsimp"></a><a name="p15249mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row15250mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p15252mcpsimp"><a name="p15252mcpsimp"></a><a name="p15252mcpsimp"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p15254mcpsimp"><a name="p15254mcpsimp"></a><a name="p15254mcpsimp"></a>表示标记信息窗口是否可见，true为可见，false为不可见。</p>
</td>
</tr>
</tbody>
</table>

## isVisible<a name="section2207551183412"></a>

<a name="table15256mcpsimp"></a>
<table><thead align="left"><tr id="row15260mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p15262mcpsimp"><a name="p15262mcpsimp"></a><a name="p15262mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row15263mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p15265mcpsimp"><a name="p15265mcpsimp"></a><a name="p15265mcpsimp"></a>public final boolean isVisible()</p>
<p id="p1018544317447"><a name="p1018544317447"></a><a name="p1018544317447"></a>您调用此API可以获取标记的可见性。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table15274mcpsimp"></a>
<table><thead align="left"><tr id="row15279mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p15281mcpsimp"><a name="p15281mcpsimp"></a><a name="p15281mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p15283mcpsimp"><a name="p15283mcpsimp"></a><a name="p15283mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row15284mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p15286mcpsimp"><a name="p15286mcpsimp"></a><a name="p15286mcpsimp"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p15288mcpsimp"><a name="p15288mcpsimp"></a><a name="p15288mcpsimp"></a>标记的可见性，true为可见，false为不可见。</p>
</td>
</tr>
</tbody>
</table>

## remove<a name="section6594131123511"></a>

<a name="table15290mcpsimp"></a>
<table><thead align="left"><tr id="row15294mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p15296mcpsimp"><a name="p15296mcpsimp"></a><a name="p15296mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row15297mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p15299mcpsimp"><a name="p15299mcpsimp"></a><a name="p15299mcpsimp"></a>public final void remove()</p>
<p id="p13301784457"><a name="p13301784457"></a><a name="p13301784457"></a>您调用此API可以从地图移除标记。</p>
</td>
</tr>
</tbody>
</table>

## setAlpha<a name="section1776118819353"></a>

<a name="table15310mcpsimp"></a>
<table><thead align="left"><tr id="row15314mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p15316mcpsimp"><a name="p15316mcpsimp"></a><a name="p15316mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row15317mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p15319mcpsimp"><a name="p15319mcpsimp"></a><a name="p15319mcpsimp"></a>public final void setAlpha(float alpha)</p>
<p id="p2225231450"><a name="p2225231450"></a><a name="p2225231450"></a>您调用此API可以设置标记的透明度属性。</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table15325mcpsimp"></a>
<table><thead align="left"><tr id="row15330mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p15332mcpsimp"><a name="p15332mcpsimp"></a><a name="p15332mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p15334mcpsimp"><a name="p15334mcpsimp"></a><a name="p15334mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row15335mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p15337mcpsimp"><a name="p15337mcpsimp"></a><a name="p15337mcpsimp"></a>alpha</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p15339mcpsimp"><a name="p15339mcpsimp"></a><a name="p15339mcpsimp"></a>透明度，取值范围：[0, 1]，0表示完全透明的，1表示完全不透明，默认为1。</p>
</td>
</tr>
</tbody>
</table>

## setAnchor<a name="section14156191615354"></a>

>![](public_sys-resources/icon-caution.gif) **注意：** 
>该接口已弃用，设置锚点位置请使用[setMarkerAnchor](#section992613197119)。

<a name="table15344mcpsimp"></a>
<table><thead align="left"><tr id="row15348mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p15350mcpsimp"><a name="p15350mcpsimp"></a><a name="p15350mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row15351mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p15353mcpsimp"><a name="p15353mcpsimp"></a><a name="p15353mcpsimp"></a>public final void setAnchor(float anchorU, float anchorV)</p>
<p id="p15356mcpsimp"><a name="p15356mcpsimp"></a><a name="p15356mcpsimp"></a>您调用此API可以设置标记的锚点位置。当前已设置u，v固定值，所以该接口固定锚点位置为标记图标的底部。</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table15360mcpsimp"></a>
<table><thead align="left"><tr id="row15365mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p15367mcpsimp"><a name="p15367mcpsimp"></a><a name="p15367mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p15369mcpsimp"><a name="p15369mcpsimp"></a><a name="p15369mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row15370mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p15372mcpsimp"><a name="p15372mcpsimp"></a><a name="p15372mcpsimp"></a>anchorU</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p15374mcpsimp"><a name="p15374mcpsimp"></a><a name="p15374mcpsimp"></a>锚点的水平坐标，以图像宽度的比例，在[0, 1]范围内。默认值为0.5。</p>
</td>
</tr>
<tr id="row15375mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p15377mcpsimp"><a name="p15377mcpsimp"></a><a name="p15377mcpsimp"></a>anchorV</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p15379mcpsimp"><a name="p15379mcpsimp"></a><a name="p15379mcpsimp"></a>锚点的垂直坐标，以图像高度的比例，在[0, 1]范围内。默认值为0.5。</p>
</td>
</tr>
</tbody>
</table>

## setAnimation<a name="section138322612114"></a>

<a name="table4841526121111"></a>
<table><thead align="left"><tr id="row198442631112"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p16841262115"><a name="p16841262115"></a><a name="p16841262115"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row884172671117"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p126501344141118"><a name="p126501344141118"></a><a name="p126501344141118"></a>public void setAnimation(Animation animation)</p>
<p id="p78422691117"><a name="p78422691117"></a><a name="p78422691117"></a>您调用此API可以设置标记的动画。</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table18412611117"></a>
<table><thead align="left"><tr id="row1985126101115"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p16850264112"><a name="p16850264112"></a><a name="p16850264112"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p1285162661113"><a name="p1285162661113"></a><a name="p1285162661113"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row385182661117"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p17854266114"><a name="p17854266114"></a><a name="p17854266114"></a>animation</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p1385826141119"><a name="p1385826141119"></a><a name="p1385826141119"></a>动画。</p>
</td>
</tr>
</tbody>
</table>

## setDraggable<a name="section58671625103515"></a>

<a name="table15384mcpsimp"></a>
<table><thead align="left"><tr id="row15388mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p15390mcpsimp"><a name="p15390mcpsimp"></a><a name="p15390mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row15391mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p15393mcpsimp"><a name="p15393mcpsimp"></a><a name="p15393mcpsimp"></a>public final void setDraggable(boolean draggable)</p>
<p id="p2082495395019"><a name="p2082495395019"></a><a name="p2082495395019"></a>您调用此API可以设置标记是否可以长按拖拽。</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table15399mcpsimp"></a>
<table><thead align="left"><tr id="row15404mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p15406mcpsimp"><a name="p15406mcpsimp"></a><a name="p15406mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p15408mcpsimp"><a name="p15408mcpsimp"></a><a name="p15408mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row15409mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p15411mcpsimp"><a name="p15411mcpsimp"></a><a name="p15411mcpsimp"></a>draggable</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p15413mcpsimp"><a name="p15413mcpsimp"></a><a name="p15413mcpsimp"></a>是否可以长按拖拽，true为可以，false为不可以。默认值为false。</p>
</td>
</tr>
</tbody>
</table>

## setFlat<a name="section1797433173511"></a>

<a name="table15418mcpsimp"></a>
<table><thead align="left"><tr id="row15422mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p15424mcpsimp"><a name="p15424mcpsimp"></a><a name="p15424mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row15425mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p15427mcpsimp"><a name="p15427mcpsimp"></a><a name="p15427mcpsimp"></a>public final void setFlat(boolean flat)</p>
<p id="p795411064615"><a name="p795411064615"></a><a name="p795411064615"></a>您调用此API可以设置标记是否平贴地图。如果标记平贴地图，则在相机旋转和倾斜时，标记仍将停留在地图上，但与<a href="groundoverlay.md">GroundOverlay</a>不同，它将保持与照相机缩放时相同的大小。 如果标记面对相机，它将始终面向相机绘制，并随相机旋转和倾斜。</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table15433mcpsimp"></a>
<table><thead align="left"><tr id="row15438mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p15440mcpsimp"><a name="p15440mcpsimp"></a><a name="p15440mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p15442mcpsimp"><a name="p15442mcpsimp"></a><a name="p15442mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row15443mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p15445mcpsimp"><a name="p15445mcpsimp"></a><a name="p15445mcpsimp"></a>flat</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p15447mcpsimp"><a name="p15447mcpsimp"></a><a name="p15447mcpsimp"></a>平贴地图设置为true，面对相机设置为false，默认值为false。</p>
</td>
</tr>
</tbody>
</table>

## setIcon<a name="section1680710531355"></a>

<a name="table15452mcpsimp"></a>
<table><thead align="left"><tr id="row15456mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p15458mcpsimp"><a name="p15458mcpsimp"></a><a name="p15458mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row15459mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p15461mcpsimp"><a name="p15461mcpsimp"></a><a name="p15461mcpsimp"></a>public final void setIcon(<a href="bitmapdescriptor.md">BitmapDescriptor</a> iconDescriptor)</p>
<p id="p136547280466"><a name="p136547280466"></a><a name="p136547280466"></a>您调用此API可以设置标记的图标，如果为空，则使用默认标记。</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table15467mcpsimp"></a>
<table><thead align="left"><tr id="row15472mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p15474mcpsimp"><a name="p15474mcpsimp"></a><a name="p15474mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p15476mcpsimp"><a name="p15476mcpsimp"></a><a name="p15476mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row15477mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p15479mcpsimp"><a name="p15479mcpsimp"></a><a name="p15479mcpsimp"></a>iconDescriptor</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p15481mcpsimp"><a name="p15481mcpsimp"></a><a name="p15481mcpsimp"></a>包含图标的对象。</p>
</td>
</tr>
</tbody>
</table>

## setInfoWindowAnchor<a name="section1858016183620"></a>

<a name="table15486mcpsimp"></a>
<table><thead align="left"><tr id="row15490mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p15492mcpsimp"><a name="p15492mcpsimp"></a><a name="p15492mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row15493mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p15495mcpsimp"><a name="p15495mcpsimp"></a><a name="p15495mcpsimp"></a>public final void setInfoWindowAnchor(float anchorU, float anchorV)</p>
<p id="p15498mcpsimp"><a name="p15498mcpsimp"></a><a name="p15498mcpsimp"></a>您调用此API可以设置标记的标记信息窗口的锚点坐标， 这是在与锚点相同的坐标系中指定的， 默认值为标记图像的顶部中间。 有关更多详细信息，请参见<a href="#section992613197119">setMarkerAnchor</a>(float anchorU, float anchorV)。</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table15501mcpsimp"></a>
<table><thead align="left"><tr id="row15506mcpsimp"><th class="cellrowborder" valign="top" width="34.46%" id="mcps1.1.3.1.1"><p id="p15508mcpsimp"><a name="p15508mcpsimp"></a><a name="p15508mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="65.53999999999999%" id="mcps1.1.3.1.2"><p id="p15510mcpsimp"><a name="p15510mcpsimp"></a><a name="p15510mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row15511mcpsimp"><td class="cellrowborder" valign="top" width="34.46%" headers="mcps1.1.3.1.1 "><p id="p15513mcpsimp"><a name="p15513mcpsimp"></a><a name="p15513mcpsimp"></a>anchorU</p>
</td>
<td class="cellrowborder" valign="top" width="65.53999999999999%" headers="mcps1.1.3.1.2 "><p id="p15515mcpsimp"><a name="p15515mcpsimp"></a><a name="p15515mcpsimp"></a>标记信息窗口锚点的水平坐标，以图像宽度的比例，建议取值[0, 1]。</p>
</td>
</tr>
<tr id="row15516mcpsimp"><td class="cellrowborder" valign="top" width="34.46%" headers="mcps1.1.3.1.1 "><p id="p15518mcpsimp"><a name="p15518mcpsimp"></a><a name="p15518mcpsimp"></a>anchorV</p>
</td>
<td class="cellrowborder" valign="top" width="65.53999999999999%" headers="mcps1.1.3.1.2 "><p id="p15520mcpsimp"><a name="p15520mcpsimp"></a><a name="p15520mcpsimp"></a>标记信息窗口锚点的垂直坐标，以图像高度的比例，建议取值[0, 1]。</p>
</td>
</tr>
</tbody>
</table>

## setMarkerAnchor<a name="section992613197119"></a>

<a name="table1477485210247"></a>
<table><thead align="left"><tr id="row1677485213249"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p177475262414"><a name="p177475262414"></a><a name="p177475262414"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row1877455212247"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p86881529102512"><a name="p86881529102512"></a><a name="p86881529102512"></a>public final void setMarkerAnchor(float anchorU, float anchorV)</p>
<p id="p10775155232417"><a name="p10775155232417"></a><a name="p10775155232417"></a>您调用此API可以设置标记的锚点位置。锚点是标记图标接触地图平面的点，图标的左顶点为（0, 0）点，右顶点为（1, 0）点，左底点为（0, 1）点，右底点为（1, 1）点。例如，在标记X（0.5, 0.3）处的锚点坐标如下：</p>
<p id="p17999174213388"><a name="p17999174213388"></a><a name="p17999174213388"></a><a name="image1999042173816"></a><a name="image1999042173816"></a><span><img id="image1999042173816" src="figures/anchor.png" height="278.160057" width="399"></span></p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table11775152152412"></a>
<table><thead align="left"><tr id="row16775155212247"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p1177575219249"><a name="p1177575219249"></a><a name="p1177575219249"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p077585292415"><a name="p077585292415"></a><a name="p077585292415"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row1577605282418"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p1776195222411"><a name="p1776195222411"></a><a name="p1776195222411"></a>anchorU</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p177619521245"><a name="p177619521245"></a><a name="p177619521245"></a>锚点的水平坐标，以图像宽度的比例，建议取值[0, 1]，默认值为0.5。</p>
</td>
</tr>
<tr id="row1177665210241"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p57766529244"><a name="p57766529244"></a><a name="p57766529244"></a>anchorV</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p0776165272414"><a name="p0776165272414"></a><a name="p0776165272414"></a>锚点的垂直坐标，以图像高度的比例，建议取值[0, 1]，默认值为1。</p>
</td>
</tr>
</tbody>
</table>

## setPosition<a name="section13917151362"></a>

<a name="table15525mcpsimp"></a>
<table><thead align="left"><tr id="row15529mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p15531mcpsimp"><a name="p15531mcpsimp"></a><a name="p15531mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row15532mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p15534mcpsimp"><a name="p15534mcpsimp"></a><a name="p15534mcpsimp"></a>public final void setPosition(<a href="latlng.md">LatLng</a> latLng)</p>
<p id="p186741514"><a name="p186741514"></a><a name="p186741514"></a>您调用此API可以设置标记的位置坐标。</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table15540mcpsimp"></a>
<table><thead align="left"><tr id="row15545mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p15547mcpsimp"><a name="p15547mcpsimp"></a><a name="p15547mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p15549mcpsimp"><a name="p15549mcpsimp"></a><a name="p15549mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row15550mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p15552mcpsimp"><a name="p15552mcpsimp"></a><a name="p15552mcpsimp"></a>latLng</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p15554mcpsimp"><a name="p15554mcpsimp"></a><a name="p15554mcpsimp"></a>标记的位置坐标。</p>
</td>
</tr>
</tbody>
</table>

**Throws**

<a name="table14799844195319"></a>
<table><thead align="left"><tr id="row1799124416534"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p979964418530"><a name="p979964418530"></a><a name="p979964418530"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p147991444155318"><a name="p147991444155318"></a><a name="p147991444155318"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row1880024412533"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p28001844115317"><a name="p28001844115317"></a><a name="p28001844115317"></a>IllegalArgumentException</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p1980010447535"><a name="p1980010447535"></a><a name="p1980010447535"></a>当latlng为空时，抛出异常。</p>
</td>
</tr>
</tbody>
</table>

## h2setRotation<a name="section1989919222361"></a>

<a name="table15559mcpsimp"></a>
<table><thead align="left"><tr id="row15563mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p15565mcpsimp"><a name="p15565mcpsimp"></a><a name="p15565mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row15566mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p15568mcpsimp"><a name="p15568mcpsimp"></a><a name="p15568mcpsimp"></a>public final void setRotation(float rotation)</p>
<p id="p15571mcpsimp"><a name="p15571mcpsimp"></a><a name="p15571mcpsimp"></a>您调用此API可以设置标记的旋转角度，即标记围绕标记锚点顺时针旋转的角度，旋转轴垂直于标记。默认旋转角度为0，默认位置为北对齐。</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table15574mcpsimp"></a>
<table><thead align="left"><tr id="row15579mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p15581mcpsimp"><a name="p15581mcpsimp"></a><a name="p15581mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p15583mcpsimp"><a name="p15583mcpsimp"></a><a name="p15583mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row15584mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p15586mcpsimp"><a name="p15586mcpsimp"></a><a name="p15586mcpsimp"></a>rotation</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p15588mcpsimp"><a name="p15588mcpsimp"></a><a name="p15588mcpsimp"></a>标记的旋转角度，默认值为0。</p>
</td>
</tr>
</tbody>
</table>

## setSnippet<a name="section165927340363"></a>

<a name="table15593mcpsimp"></a>
<table><thead align="left"><tr id="row15597mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p15599mcpsimp"><a name="p15599mcpsimp"></a><a name="p15599mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row15600mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p15602mcpsimp"><a name="p15602mcpsimp"></a><a name="p15602mcpsimp"></a>public final void setSnippet(String snippet)</p>
<p id="p10655632194716"><a name="p10655632194716"></a><a name="p10655632194716"></a>您调用此API可以设置标记的文字片段，如果为空，则不显示文字片段。</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table15608mcpsimp"></a>
<table><thead align="left"><tr id="row15613mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p15615mcpsimp"><a name="p15615mcpsimp"></a><a name="p15615mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p15617mcpsimp"><a name="p15617mcpsimp"></a><a name="p15617mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row15618mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p15620mcpsimp"><a name="p15620mcpsimp"></a><a name="p15620mcpsimp"></a>snippet</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p15622mcpsimp"><a name="p15622mcpsimp"></a><a name="p15622mcpsimp"></a>文字片段。</p>
</td>
</tr>
</tbody>
</table>

## setTag<a name="section893234843611"></a>

<a name="table15627mcpsimp"></a>
<table><thead align="left"><tr id="row15631mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p15633mcpsimp"><a name="p15633mcpsimp"></a><a name="p15633mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row15634mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p15636mcpsimp"><a name="p15636mcpsimp"></a><a name="p15636mcpsimp"></a>public final void setTag(Object tag)</p>
<p id="p136210119279"><a name="p136210119279"></a><a name="p136210119279"></a>您调用此API可以设置标记的tag属性，tag属性可以是任意对象，如果设置为空，则清除tag。当您不再需要使用tag时，您可以调用setTag(null)清除tag，以防止应用程序发生内存泄漏。</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table15642mcpsimp"></a>
<table><thead align="left"><tr id="row15647mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p15649mcpsimp"><a name="p15649mcpsimp"></a><a name="p15649mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p15651mcpsimp"><a name="p15651mcpsimp"></a><a name="p15651mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row15652mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p15654mcpsimp"><a name="p15654mcpsimp"></a><a name="p15654mcpsimp"></a>tag</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p15656mcpsimp"><a name="p15656mcpsimp"></a><a name="p15656mcpsimp"></a>标记的tag属性。</p>
</td>
</tr>
</tbody>
</table>

## setTitle<a name="section13963185519361"></a>

<a name="table15661mcpsimp"></a>
<table><thead align="left"><tr id="row15665mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p15667mcpsimp"><a name="p15667mcpsimp"></a><a name="p15667mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row15668mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p15670mcpsimp"><a name="p15670mcpsimp"></a><a name="p15670mcpsimp"></a>public final void setTitle(String title)</p>
<p id="p15673mcpsimp"><a name="p15673mcpsimp"></a><a name="p15673mcpsimp"></a>您调用此API可以设置标记的标题，默认为空。</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table15676mcpsimp"></a>
<table><thead align="left"><tr id="row15681mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p15683mcpsimp"><a name="p15683mcpsimp"></a><a name="p15683mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p15685mcpsimp"><a name="p15685mcpsimp"></a><a name="p15685mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row15686mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p15688mcpsimp"><a name="p15688mcpsimp"></a><a name="p15688mcpsimp"></a>title</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p15690mcpsimp"><a name="p15690mcpsimp"></a><a name="p15690mcpsimp"></a>标题，字符串对象，如果为空，则清除标题。</p>
</td>
</tr>
</tbody>
</table>

## setVisible<a name="section1775916212376"></a>

<a name="table15695mcpsimp"></a>
<table><thead align="left"><tr id="row15699mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p15701mcpsimp"><a name="p15701mcpsimp"></a><a name="p15701mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row15702mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p15704mcpsimp"><a name="p15704mcpsimp"></a><a name="p15704mcpsimp"></a>public final void setVisible(boolean visible)</p>
<p id="p146329854811"><a name="p146329854811"></a><a name="p146329854811"></a>您调用此API可以设置标记的可见性。</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table15710mcpsimp"></a>
<table><thead align="left"><tr id="row15715mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p15717mcpsimp"><a name="p15717mcpsimp"></a><a name="p15717mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p15719mcpsimp"><a name="p15719mcpsimp"></a><a name="p15719mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row15720mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p15722mcpsimp"><a name="p15722mcpsimp"></a><a name="p15722mcpsimp"></a>visible</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p15724mcpsimp"><a name="p15724mcpsimp"></a><a name="p15724mcpsimp"></a>标记的可见性，true为可见，false为不可见。默认值为true。</p>
</td>
</tr>
</tbody>
</table>

## setZIndex<a name="section952413920376"></a>

<a name="table15729mcpsimp"></a>
<table><thead align="left"><tr id="row15733mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p15735mcpsimp"><a name="p15735mcpsimp"></a><a name="p15735mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row15736mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p15738mcpsimp"><a name="p15738mcpsimp"></a><a name="p15738mcpsimp"></a>public final void setZIndex(float zIndex)</p>
<p id="p315311339485"><a name="p315311339485"></a><a name="p315311339485"></a>用于设置标记的z指数。z指数指的是标记的叠加顺序，具有较大z指数的标记会绘制在具有较小z指数的标记上，具有相同z指数的叠加顺序为元素添加的先后顺序。</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table15744mcpsimp"></a>
<table><thead align="left"><tr id="row15749mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p15751mcpsimp"><a name="p15751mcpsimp"></a><a name="p15751mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p15753mcpsimp"><a name="p15753mcpsimp"></a><a name="p15753mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row15754mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p15756mcpsimp"><a name="p15756mcpsimp"></a><a name="p15756mcpsimp"></a>zIndex</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p15758mcpsimp"><a name="p15758mcpsimp"></a><a name="p15758mcpsimp"></a>z指数，即标记的叠加顺序。默认的z指数是0。</p>
<div class="caution" id="note2857645191713"><a name="note2857645191713"></a><a name="note2857645191713"></a><span class="cautiontitle"> 注意： </span><div class="cautionbody"><p id="p9331114715176"><a name="p9331114715176"></a><a name="p9331114715176"></a>当点击Marker时其层级将会被置顶，标记的z指数值被置为3.4028235E38。</p>
</div></div>
</td>
</tr>
</tbody>
</table>

## showInfoWindow<a name="section13223817123711"></a>

<a name="table15763mcpsimp"></a>
<table><thead align="left"><tr id="row15767mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p15769mcpsimp"><a name="p15769mcpsimp"></a><a name="p15769mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row15770mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p15772mcpsimp"><a name="p15772mcpsimp"></a><a name="p15772mcpsimp"></a>public final void showInfoWindow()</p>
<p id="p162808499481"><a name="p162808499481"></a><a name="p162808499481"></a>您调用此API可以展示标记的标记信息窗口。</p>
</td>
</tr>
</tbody>
</table>

## startAnimation<a name="section13557451287"></a>

<a name="table13355184518818"></a>
<table><thead align="left"><tr id="row123550450818"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p635614455811"><a name="p635614455811"></a><a name="p635614455811"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row10356154518818"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p103561545289"><a name="p103561545289"></a><a name="p103561545289"></a>public void startAnimation()</p>
<p id="p12356194512817"><a name="p12356194512817"></a><a name="p12356194512817"></a>您调用此API可以使标记开始动画。</p>
</td>
</tr>
</tbody>
</table>

