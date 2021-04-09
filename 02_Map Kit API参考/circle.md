# Circle<a name="ZH-CN_TOPIC_0000001099661042"></a>

-   [Public Method Summary](#section9411729111518)
-   [Public Methods](#section789195017342)
-   [getCenter](#section16256105614214)
-   [getFillColor](#section1516912544315)
-   [getId](#section1467151415439)
-   [getRadius](#section1012192474315)
-   [getStrokeColor](#section8908143514318)
-   [getStrokePattern](#section11775179124510)
-   [getStrokeWidth](#section8731144613433)
-   [getTag](#section02230313440)
-   [getZIndex](#section9103171318446)
-   [isClickable](#section18436131814454)
-   [isVisible](#section569152794512)
-   [remove](#section16940241144514)
-   [setCenter](#section1187515316454)
-   [setClickable](#section066010611466)
-   [setFillColor](#section109011517154616)
-   [setRadius](#section1594183211467)
-   [setStrokeColor](#section411010496468)
-   [setStrokePattern](#section19343302476)
-   [setStrokeWidth](#section55401426164811)
-   [setTag](#section136481518164819)
-   [setVisible](#section932681194811)
-   [setZIndex](#section1027016353395)


<a name="table9707mcpsimp"></a>
<table><thead align="left"><tr id="row9711mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p9713mcpsimp"><a name="p9713mcpsimp"></a><a name="p9713mcpsimp"></a>Class Info</p>
</th>
</tr>
</thead>
<tbody><tr id="row9714mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p1198793718385"><a name="p1198793718385"></a><a name="p1198793718385"></a>public final class Circle</p>
<p id="p1088365121517"><a name="p1088365121517"></a><a name="p1088365121517"></a>地图上的圆形对象，包括实心圆和空心圆两种。在调用<a href="huaweimap.md">HuaweiMap</a>类的<a href="huaweimap.md#section7603022114010">addCircle</a>方法时会返回该类型的实例。</p>
</td>
</tr>
</tbody>
</table>

## Public Method Summary<a name="section9411729111518"></a>

<a name="table9722mcpsimp"></a>
<table><thead align="left"><tr id="row9727mcpsimp"><th class="cellrowborder" valign="top" width="40%" id="mcps1.1.3.1.1"><p id="p081120285386"><a name="p081120285386"></a><a name="p081120285386"></a>Qualifier and Type</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.1.3.1.2"><p id="p681112883813"><a name="p681112883813"></a><a name="p681112883813"></a>Method Name and Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row9732mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p9734mcpsimp"><a name="p9734mcpsimp"></a><a name="p9734mcpsimp"></a><a href="latlng.md">LatLng</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p9736mcpsimp"><a name="p9736mcpsimp"></a><a name="p9736mcpsimp"></a><a href="#section16256105614214">getCenter</a>()</p>
<p id="p145464820342"><a name="p145464820342"></a><a name="p145464820342"></a>获取圆心经纬度。</p>
</td>
</tr>
<tr id="row9737mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p9739mcpsimp"><a name="p9739mcpsimp"></a><a name="p9739mcpsimp"></a>int</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p9741mcpsimp"><a name="p9741mcpsimp"></a><a name="p9741mcpsimp"></a><a href="#section1516912544315">getFillColor</a>()</p>
<p id="p14951848193410"><a name="p14951848193410"></a><a name="p14951848193410"></a>获取圆的填充色。</p>
</td>
</tr>
<tr id="row9742mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p9744mcpsimp"><a name="p9744mcpsimp"></a><a name="p9744mcpsimp"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p9746mcpsimp"><a name="p9746mcpsimp"></a><a name="p9746mcpsimp"></a><a href="#section1467151415439">getId</a>()</p>
<p id="p54571850193418"><a name="p54571850193418"></a><a name="p54571850193418"></a>获取圆的id属性。</p>
</td>
</tr>
<tr id="row9747mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p9749mcpsimp"><a name="p9749mcpsimp"></a><a name="p9749mcpsimp"></a>double</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p9751mcpsimp"><a name="p9751mcpsimp"></a><a name="p9751mcpsimp"></a><a href="#section1012192474315">getRadius</a>()</p>
<p id="p1167111517347"><a name="p1167111517347"></a><a name="p1167111517347"></a>获取圆的半径。</p>
</td>
</tr>
<tr id="row9752mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p9754mcpsimp"><a name="p9754mcpsimp"></a><a name="p9754mcpsimp"></a>int</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p9756mcpsimp"><a name="p9756mcpsimp"></a><a name="p9756mcpsimp"></a><a href="#section8908143514318">getStrokeColor</a>()</p>
<p id="p975605273413"><a name="p975605273413"></a><a name="p975605273413"></a>获取圆的边框颜色值。</p>
</td>
</tr>
<tr id="row209711240185615"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p15877114815569"><a name="p15877114815569"></a><a name="p15877114815569"></a>List&lt;<a href="patternitem.md">PatternItem</a>&gt;</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p3878164816565"><a name="p3878164816565"></a><a name="p3878164816565"></a><a href="#section11775179124510">getStrokePattern</a>()</p>
<p id="p5121854193418"><a name="p5121854193418"></a><a name="p5121854193418"></a>获取圆的边框样式。</p>
</td>
</tr>
<tr id="row9757mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p9759mcpsimp"><a name="p9759mcpsimp"></a><a name="p9759mcpsimp"></a>float</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p9761mcpsimp"><a name="p9761mcpsimp"></a><a name="p9761mcpsimp"></a><a href="#section8731144613433">getStrokeWidth</a>()</p>
<p id="p526435517346"><a name="p526435517346"></a><a name="p526435517346"></a>获取圆的边框宽度。</p>
</td>
</tr>
<tr id="row9762mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p9764mcpsimp"><a name="p9764mcpsimp"></a><a name="p9764mcpsimp"></a>Object</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p9766mcpsimp"><a name="p9766mcpsimp"></a><a name="p9766mcpsimp"></a><a href="#section02230313440">getTag</a>()</p>
<p id="p9782165619344"><a name="p9782165619344"></a><a name="p9782165619344"></a>获取圆的tag属性</p>
</td>
</tr>
<tr id="row9767mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p9769mcpsimp"><a name="p9769mcpsimp"></a><a name="p9769mcpsimp"></a>float</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p9771mcpsimp"><a name="p9771mcpsimp"></a><a name="p9771mcpsimp"></a><a href="#section9103171318446">getZIndex</a>()</p>
<p id="p17281758103416"><a name="p17281758103416"></a><a name="p17281758103416"></a>获取圆的z指数。</p>
</td>
</tr>
<tr id="row9777mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p9779mcpsimp"><a name="p9779mcpsimp"></a><a name="p9779mcpsimp"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p9781mcpsimp"><a name="p9781mcpsimp"></a><a name="p9781mcpsimp"></a><a href="#section18436131814454">isClickable</a>()</p>
<p id="p15979165963411"><a name="p15979165963411"></a><a name="p15979165963411"></a>获取圆的可点击性。</p>
</td>
</tr>
<tr id="row9782mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p9784mcpsimp"><a name="p9784mcpsimp"></a><a name="p9784mcpsimp"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p9786mcpsimp"><a name="p9786mcpsimp"></a><a name="p9786mcpsimp"></a><a href="#section569152794512">isVisible</a>()</p>
<p id="p7775171143512"><a name="p7775171143512"></a><a name="p7775171143512"></a>获取圆的可见性。</p>
</td>
</tr>
<tr id="row9787mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p9789mcpsimp"><a name="p9789mcpsimp"></a><a name="p9789mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p9791mcpsimp"><a name="p9791mcpsimp"></a><a name="p9791mcpsimp"></a><a href="#section16940241144514">remove</a>()</p>
<p id="p177121128351"><a name="p177121128351"></a><a name="p177121128351"></a>从地图上移除该圆，移除后，该圆的所有方法行为都将无效。</p>
</td>
</tr>
<tr id="row9792mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p9794mcpsimp"><a name="p9794mcpsimp"></a><a name="p9794mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p9796mcpsimp"><a name="p9796mcpsimp"></a><a name="p9796mcpsimp"></a><a href="#section1187515316454">setCenter</a>(<a href="latlng.md">LatLng</a> center)</p>
<p id="p129343320354"><a name="p129343320354"></a><a name="p129343320354"></a>给圆心设置经纬度坐标。</p>
</td>
</tr>
<tr id="row9797mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p9799mcpsimp"><a name="p9799mcpsimp"></a><a name="p9799mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p9801mcpsimp"><a name="p9801mcpsimp"></a><a name="p9801mcpsimp"></a><a href="#section066010611466">setClickable</a>(boolean clickable)</p>
<p id="p12635103519"><a name="p12635103519"></a><a name="p12635103519"></a>设置圆的可点击性。</p>
</td>
</tr>
<tr id="row9802mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p9804mcpsimp"><a name="p9804mcpsimp"></a><a name="p9804mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p9806mcpsimp"><a name="p9806mcpsimp"></a><a name="p9806mcpsimp"></a><a href="#section109011517154616">setFillColor</a>(int color)</p>
<p id="p1230376113516"><a name="p1230376113516"></a><a name="p1230376113516"></a>设置圆的填充色。</p>
</td>
</tr>
<tr id="row9807mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p9809mcpsimp"><a name="p9809mcpsimp"></a><a name="p9809mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p9811mcpsimp"><a name="p9811mcpsimp"></a><a name="p9811mcpsimp"></a><a href="#section1594183211467">setRadius</a>(double radius)</p>
<p id="p183604883517"><a name="p183604883517"></a><a name="p183604883517"></a>设置圆的半径。</p>
</td>
</tr>
<tr id="row9812mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p9814mcpsimp"><a name="p9814mcpsimp"></a><a name="p9814mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p9816mcpsimp"><a name="p9816mcpsimp"></a><a name="p9816mcpsimp"></a><a href="#section411010496468">setStrokeColor</a>(int color)</p>
<p id="p1436309113516"><a name="p1436309113516"></a><a name="p1436309113516"></a>设置圆的边框颜色。</p>
</td>
</tr>
<tr id="row9817mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p9819mcpsimp"><a name="p9819mcpsimp"></a><a name="p9819mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p9821mcpsimp"><a name="p9821mcpsimp"></a><a name="p9821mcpsimp"></a><a href="#section19343302476">setStrokePattern</a>(List&lt;<a href="patternitem.md">PatternItem</a>&gt; pattern)</p>
<p id="p94391310153512"><a name="p94391310153512"></a><a name="p94391310153512"></a>设置圆的边框样式。</p>
</td>
</tr>
<tr id="row9822mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p9824mcpsimp"><a name="p9824mcpsimp"></a><a name="p9824mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p9826mcpsimp"><a name="p9826mcpsimp"></a><a name="p9826mcpsimp"></a><a href="#section55401426164811">setStrokeWidth</a>(float width)</p>
<p id="p35031611143519"><a name="p35031611143519"></a><a name="p35031611143519"></a>设置圆的边框宽度。</p>
</td>
</tr>
<tr id="row9827mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p9829mcpsimp"><a name="p9829mcpsimp"></a><a name="p9829mcpsimp"></a>&lt;T&gt; void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p9831mcpsimp"><a name="p9831mcpsimp"></a><a name="p9831mcpsimp"></a><a href="#section136481518164819">setTag</a>(T tag)</p>
<p id="p9699171216354"><a name="p9699171216354"></a><a name="p9699171216354"></a>设置圆的tag属性。</p>
</td>
</tr>
<tr id="row9832mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p9834mcpsimp"><a name="p9834mcpsimp"></a><a name="p9834mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p9836mcpsimp"><a name="p9836mcpsimp"></a><a name="p9836mcpsimp"></a><a href="#section932681194811">setVisible</a>(boolean visible)</p>
<p id="p87861513123514"><a name="p87861513123514"></a><a name="p87861513123514"></a>设置圆的可见性。</p>
</td>
</tr>
<tr id="row9837mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p9839mcpsimp"><a name="p9839mcpsimp"></a><a name="p9839mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p9841mcpsimp"><a name="p9841mcpsimp"></a><a name="p9841mcpsimp"></a><a href="#section1027016353395">setZIndex</a>(float zIndex)</p>
<p id="p563761523520"><a name="p563761523520"></a><a name="p563761523520"></a>设置圆的z指数。</p>
</td>
</tr>
</tbody>
</table>

## Public Methods<a name="section789195017342"></a>

## getCenter<a name="section16256105614214"></a>

<a name="table9844mcpsimp"></a>
<table><thead align="left"><tr id="row9848mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p9850mcpsimp"><a name="p9850mcpsimp"></a><a name="p9850mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row9851mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p9853mcpsimp"><a name="p9853mcpsimp"></a><a name="p9853mcpsimp"></a>public <a href="latlng.md">LatLng</a> getCenter()</p>
<p id="p951374785214"><a name="p951374785214"></a><a name="p951374785214"></a>您调用此API可以获取圆心经纬度。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table9862mcpsimp"></a>
<table><thead align="left"><tr id="row9867mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p9869mcpsimp"><a name="p9869mcpsimp"></a><a name="p9869mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p9871mcpsimp"><a name="p9871mcpsimp"></a><a name="p9871mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row9872mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p9874mcpsimp"><a name="p9874mcpsimp"></a><a name="p9874mcpsimp"></a><a href="latlng.md">LatLng</a></p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p9876mcpsimp"><a name="p9876mcpsimp"></a><a name="p9876mcpsimp"></a>圆心的经纬度。</p>
</td>
</tr>
</tbody>
</table>

## getFillColor<a name="section1516912544315"></a>

<a name="table9878mcpsimp"></a>
<table><thead align="left"><tr id="row9882mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p9884mcpsimp"><a name="p9884mcpsimp"></a><a name="p9884mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row9885mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p9887mcpsimp"><a name="p9887mcpsimp"></a><a name="p9887mcpsimp"></a>public int getFillColor()</p>
<p id="p1341315718523"><a name="p1341315718523"></a><a name="p1341315718523"></a>您调用此API可以获取圆的填充色。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table9896mcpsimp"></a>
<table><thead align="left"><tr id="row9901mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p9903mcpsimp"><a name="p9903mcpsimp"></a><a name="p9903mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p9905mcpsimp"><a name="p9905mcpsimp"></a><a name="p9905mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row9906mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p9908mcpsimp"><a name="p9908mcpsimp"></a><a name="p9908mcpsimp"></a>int</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p9910mcpsimp"><a name="p9910mcpsimp"></a><a name="p9910mcpsimp"></a>ARGB格式的颜色值。</p>
</td>
</tr>
</tbody>
</table>

## getId<a name="section1467151415439"></a>

<a name="table9912mcpsimp"></a>
<table><thead align="left"><tr id="row9916mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p9918mcpsimp"><a name="p9918mcpsimp"></a><a name="p9918mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row9919mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p9921mcpsimp"><a name="p9921mcpsimp"></a><a name="p9921mcpsimp"></a>public String getId()</p>
<p id="p628916205314"><a name="p628916205314"></a><a name="p628916205314"></a>您调用此API可以获取圆的id属性，该id在地图上的所有圆中都是唯一的。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table9930mcpsimp"></a>
<table><thead align="left"><tr id="row9935mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p9937mcpsimp"><a name="p9937mcpsimp"></a><a name="p9937mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p9939mcpsimp"><a name="p9939mcpsimp"></a><a name="p9939mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row9940mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p9942mcpsimp"><a name="p9942mcpsimp"></a><a name="p9942mcpsimp"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p9944mcpsimp"><a name="p9944mcpsimp"></a><a name="p9944mcpsimp"></a>圆的ID属性。</p>
</td>
</tr>
</tbody>
</table>

## getRadius<a name="section1012192474315"></a>

<a name="table9946mcpsimp"></a>
<table><thead align="left"><tr id="row9950mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p9952mcpsimp"><a name="p9952mcpsimp"></a><a name="p9952mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row9953mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p9955mcpsimp"><a name="p9955mcpsimp"></a><a name="p9955mcpsimp"></a>public double getRadius()</p>
<p id="p168281520195319"><a name="p168281520195319"></a><a name="p168281520195319"></a>您调用此API可以获取圆的半径。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table9964mcpsimp"></a>
<table><thead align="left"><tr id="row9969mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p9971mcpsimp"><a name="p9971mcpsimp"></a><a name="p9971mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p9973mcpsimp"><a name="p9973mcpsimp"></a><a name="p9973mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row9974mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p9976mcpsimp"><a name="p9976mcpsimp"></a><a name="p9976mcpsimp"></a>double</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p9978mcpsimp"><a name="p9978mcpsimp"></a><a name="p9978mcpsimp"></a>圆的半径，单位：米。</p>
</td>
</tr>
</tbody>
</table>

## getStrokeColor<a name="section8908143514318"></a>

<a name="table9980mcpsimp"></a>
<table><thead align="left"><tr id="row9984mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p9986mcpsimp"><a name="p9986mcpsimp"></a><a name="p9986mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row9987mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p9989mcpsimp"><a name="p9989mcpsimp"></a><a name="p9989mcpsimp"></a>public int getStrokeColor()</p>
<p id="p4286102975311"><a name="p4286102975311"></a><a name="p4286102975311"></a>您调用此API可以获取圆的边框颜色值。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table9998mcpsimp"></a>
<table><thead align="left"><tr id="row10003mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p10005mcpsimp"><a name="p10005mcpsimp"></a><a name="p10005mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p10007mcpsimp"><a name="p10007mcpsimp"></a><a name="p10007mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row10008mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p10010mcpsimp"><a name="p10010mcpsimp"></a><a name="p10010mcpsimp"></a>int</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p10012mcpsimp"><a name="p10012mcpsimp"></a><a name="p10012mcpsimp"></a>ARGB格式的颜色值。</p>
</td>
</tr>
</tbody>
</table>

## getStrokePattern<a name="section11775179124510"></a>

<a name="table10116mcpsimp"></a>
<table><thead align="left"><tr id="row10120mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p10122mcpsimp"><a name="p10122mcpsimp"></a><a name="p10122mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row10123mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p10125mcpsimp"><a name="p10125mcpsimp"></a><a name="p10125mcpsimp"></a>public List&lt;<a href="patternitem.md">PatternItem</a>&gt; getStrokePattern()</p>
<p id="p19127351205518"><a name="p19127351205518"></a><a name="p19127351205518"></a>您调用此API可以获取圆的边框样式。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table10134mcpsimp"></a>
<table><thead align="left"><tr id="row10139mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p10141mcpsimp"><a name="p10141mcpsimp"></a><a name="p10141mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p10143mcpsimp"><a name="p10143mcpsimp"></a><a name="p10143mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row10144mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p10146mcpsimp"><a name="p10146mcpsimp"></a><a name="p10146mcpsimp"></a>List&lt;<a href="patternitem.md">PatternItem</a>&gt;</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p10148mcpsimp"><a name="p10148mcpsimp"></a><a name="p10148mcpsimp"></a>圆的边框样式。</p>
</td>
</tr>
</tbody>
</table>

## getStrokeWidth<a name="section8731144613433"></a>

<a name="table10014mcpsimp"></a>
<table><thead align="left"><tr id="row10018mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p10020mcpsimp"><a name="p10020mcpsimp"></a><a name="p10020mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row10021mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p10023mcpsimp"><a name="p10023mcpsimp"></a><a name="p10023mcpsimp"></a>public float getStrokeWidth()</p>
<p id="p324684085311"><a name="p324684085311"></a><a name="p324684085311"></a>您调用此API可以获取圆的边框宽度。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table10032mcpsimp"></a>
<table><thead align="left"><tr id="row10037mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p10039mcpsimp"><a name="p10039mcpsimp"></a><a name="p10039mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p10041mcpsimp"><a name="p10041mcpsimp"></a><a name="p10041mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row10042mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p10044mcpsimp"><a name="p10044mcpsimp"></a><a name="p10044mcpsimp"></a>float</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p10046mcpsimp"><a name="p10046mcpsimp"></a><a name="p10046mcpsimp"></a>圆的边框宽度，单位：像素。</p>
</td>
</tr>
</tbody>
</table>

## getTag<a name="section02230313440"></a>

<a name="table10048mcpsimp"></a>
<table><thead align="left"><tr id="row10052mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p10054mcpsimp"><a name="p10054mcpsimp"></a><a name="p10054mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row10055mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p10057mcpsimp"><a name="p10057mcpsimp"></a><a name="p10057mcpsimp"></a>public Object getTag()</p>
<p id="p72721333175514"><a name="p72721333175514"></a><a name="p72721333175514"></a>您调用此API将获取圆的tag属性。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table10066mcpsimp"></a>
<table><thead align="left"><tr id="row10071mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p10073mcpsimp"><a name="p10073mcpsimp"></a><a name="p10073mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p10075mcpsimp"><a name="p10075mcpsimp"></a><a name="p10075mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row10076mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p10078mcpsimp"><a name="p10078mcpsimp"></a><a name="p10078mcpsimp"></a>Object</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p10080mcpsimp"><a name="p10080mcpsimp"></a><a name="p10080mcpsimp"></a>圆的tag属性。如果已设置tag，则返回Object；如果未设置，则返回null。</p>
</td>
</tr>
</tbody>
</table>

## getZIndex<a name="section9103171318446"></a>

<a name="table10082mcpsimp"></a>
<table><thead align="left"><tr id="row10086mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p10088mcpsimp"><a name="p10088mcpsimp"></a><a name="p10088mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row10089mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p10091mcpsimp"><a name="p10091mcpsimp"></a><a name="p10091mcpsimp"></a>public float getZIndex()</p>
<p id="p14654942205514"><a name="p14654942205514"></a><a name="p14654942205514"></a>您调用此API可以获取圆的z指数。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table10100mcpsimp"></a>
<table><thead align="left"><tr id="row10105mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p10107mcpsimp"><a name="p10107mcpsimp"></a><a name="p10107mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p10109mcpsimp"><a name="p10109mcpsimp"></a><a name="p10109mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row10110mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p10112mcpsimp"><a name="p10112mcpsimp"></a><a name="p10112mcpsimp"></a>float</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p10114mcpsimp"><a name="p10114mcpsimp"></a><a name="p10114mcpsimp"></a>z指数，即圆的叠加顺序。</p>
</td>
</tr>
</tbody>
</table>

## isClickable<a name="section18436131814454"></a>

<a name="table10150mcpsimp"></a>
<table><thead align="left"><tr id="row10154mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p10156mcpsimp"><a name="p10156mcpsimp"></a><a name="p10156mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row10157mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p10159mcpsimp"><a name="p10159mcpsimp"></a><a name="p10159mcpsimp"></a>public boolean isClickable()</p>
<p id="p1554125945512"><a name="p1554125945512"></a><a name="p1554125945512"></a>您调用此API可以获取圆的可点击性。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table10168mcpsimp"></a>
<table><thead align="left"><tr id="row10173mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p10175mcpsimp"><a name="p10175mcpsimp"></a><a name="p10175mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p10177mcpsimp"><a name="p10177mcpsimp"></a><a name="p10177mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row10178mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p10180mcpsimp"><a name="p10180mcpsimp"></a><a name="p10180mcpsimp"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p10182mcpsimp"><a name="p10182mcpsimp"></a><a name="p10182mcpsimp"></a>圆的可点击性。true为可点击，false为不可点击。</p>
</td>
</tr>
</tbody>
</table>

## isVisible<a name="section569152794512"></a>

<a name="table10184mcpsimp"></a>
<table><thead align="left"><tr id="row10188mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p10190mcpsimp"><a name="p10190mcpsimp"></a><a name="p10190mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row10191mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p10193mcpsimp"><a name="p10193mcpsimp"></a><a name="p10193mcpsimp"></a>public boolean isVisible()</p>
<p id="p132208814566"><a name="p132208814566"></a><a name="p132208814566"></a>您调用此API可以获取圆的可见性。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table10202mcpsimp"></a>
<table><thead align="left"><tr id="row10207mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p10209mcpsimp"><a name="p10209mcpsimp"></a><a name="p10209mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p10211mcpsimp"><a name="p10211mcpsimp"></a><a name="p10211mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row10212mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p10214mcpsimp"><a name="p10214mcpsimp"></a><a name="p10214mcpsimp"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p10216mcpsimp"><a name="p10216mcpsimp"></a><a name="p10216mcpsimp"></a>圆的可见性。true为可见，false为不可见。</p>
</td>
</tr>
</tbody>
</table>

## remove<a name="section16940241144514"></a>

<a name="table10218mcpsimp"></a>
<table><thead align="left"><tr id="row10222mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p10224mcpsimp"><a name="p10224mcpsimp"></a><a name="p10224mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row10225mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p10227mcpsimp"><a name="p10227mcpsimp"></a><a name="p10227mcpsimp"></a>public void remove()</p>
<p id="p57541516195615"><a name="p57541516195615"></a><a name="p57541516195615"></a>您调用此API可以从地图上移除该圆，移除后，该圆的所有方法行为都将无效。</p>
</td>
</tr>
</tbody>
</table>

## setCenter<a name="section1187515316454"></a>

<a name="table10238mcpsimp"></a>
<table><thead align="left"><tr id="row10242mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p10244mcpsimp"><a name="p10244mcpsimp"></a><a name="p10244mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row10245mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p10247mcpsimp"><a name="p10247mcpsimp"></a><a name="p10247mcpsimp"></a>public void setCenter(<a href="latlng.md">LatLng</a> center)</p>
<p id="p10756152413566"><a name="p10756152413566"></a><a name="p10756152413566"></a>您调用此API可以给圆心设置经纬度坐标，该圆心不能为空，因为圆没有默认的圆心。</p>
<div class="note" id="note113441497335"><a name="note113441497335"></a><a name="note113441497335"></a><span class="notetitle"> 说明： </span><div class="notebody"><p id="p18344199143318"><a name="p18344199143318"></a><a name="p18344199143318"></a>圆的中心点纬度在[-85.051128, 85.051128]范围内才能画出圆。若圆中心点纬度正好为-85.051128或85.051128时，能画出半径为1.006270米的圆。</p>
</div></div>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table10253mcpsimp"></a>
<table><thead align="left"><tr id="row10258mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p10260mcpsimp"><a name="p10260mcpsimp"></a><a name="p10260mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p10262mcpsimp"><a name="p10262mcpsimp"></a><a name="p10262mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row10263mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p10265mcpsimp"><a name="p10265mcpsimp"></a><a name="p10265mcpsimp"></a>center</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p10267mcpsimp"><a name="p10267mcpsimp"></a><a name="p10267mcpsimp"></a>圆心对象。</p>
</td>
</tr>
</tbody>
</table>

**Throws**

<a name="table10273mcpsimp"></a>
<table><thead align="left"><tr id="row10278mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p10280mcpsimp"><a name="p10280mcpsimp"></a><a name="p10280mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p10282mcpsimp"><a name="p10282mcpsimp"></a><a name="p10282mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row10283mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p10285mcpsimp"><a name="p10285mcpsimp"></a><a name="p10285mcpsimp"></a>NullPointerException</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p10287mcpsimp"><a name="p10287mcpsimp"></a><a name="p10287mcpsimp"></a>当传入的center为空时，抛出异常。</p>
</td>
</tr>
</tbody>
</table>

## setClickable<a name="section066010611466"></a>

<a name="table10289mcpsimp"></a>
<table><thead align="left"><tr id="row10293mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p10295mcpsimp"><a name="p10295mcpsimp"></a><a name="p10295mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row10296mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p10298mcpsimp"><a name="p10298mcpsimp"></a><a name="p10298mcpsimp"></a>public void setClickable(boolean clickable)</p>
<p id="p212017398566"><a name="p212017398566"></a><a name="p212017398566"></a>您调用此API可以设置圆的可点击性。</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table10304mcpsimp"></a>
<table><thead align="left"><tr id="row10309mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p10311mcpsimp"><a name="p10311mcpsimp"></a><a name="p10311mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p10313mcpsimp"><a name="p10313mcpsimp"></a><a name="p10313mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row10314mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p10316mcpsimp"><a name="p10316mcpsimp"></a><a name="p10316mcpsimp"></a>clickable</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p10318mcpsimp"><a name="p10318mcpsimp"></a><a name="p10318mcpsimp"></a>圆的可点击性，true为可点击，false为不可点击。</p>
</td>
</tr>
</tbody>
</table>

## setFillColor<a name="section109011517154616"></a>

<a name="table10323mcpsimp"></a>
<table><thead align="left"><tr id="row10327mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p10329mcpsimp"><a name="p10329mcpsimp"></a><a name="p10329mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row10330mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p10332mcpsimp"><a name="p10332mcpsimp"></a><a name="p10332mcpsimp"></a>public void setFillColor(int color)</p>
<p id="p655205018562"><a name="p655205018562"></a><a name="p655205018562"></a>您调用此API可以设置圆的填充色，如果使用Color.TRANSPARENT，则不会绘制填充。</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table10338mcpsimp"></a>
<table><thead align="left"><tr id="row10343mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p10345mcpsimp"><a name="p10345mcpsimp"></a><a name="p10345mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p10347mcpsimp"><a name="p10347mcpsimp"></a><a name="p10347mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row10348mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p10350mcpsimp"><a name="p10350mcpsimp"></a><a name="p10350mcpsimp"></a>color</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p10352mcpsimp"><a name="p10352mcpsimp"></a><a name="p10352mcpsimp"></a>ARGB格式颜色值，默认填充色为透明色（0x00000000）。</p>
</td>
</tr>
</tbody>
</table>

## setRadius<a name="section1594183211467"></a>

<a name="table10357mcpsimp"></a>
<table><thead align="left"><tr id="row10361mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p10363mcpsimp"><a name="p10363mcpsimp"></a><a name="p10363mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row10364mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p10366mcpsimp"><a name="p10366mcpsimp"></a><a name="p10366mcpsimp"></a>public void setRadius(double radius)</p>
<p id="p964955912560"><a name="p964955912560"></a><a name="p964955912560"></a>您调用此API可以设置圆的半径。</p>
<div class="note" id="note1319510218346"><a name="note1319510218346"></a><a name="note1319510218346"></a><span class="notetitle"> 说明： </span><div class="notebody"><p id="p85321016121611"><a name="p85321016121611"></a><a name="p85321016121611"></a>圆的中心点纬度在[-85.051128, 85.051128]范围内才能画出圆。若圆中心点纬度正好为-85.051128或85.051128时，能画出半径为1.006270米的圆。</p>
</div></div>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table10372mcpsimp"></a>
<table><thead align="left"><tr id="row10377mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p10379mcpsimp"><a name="p10379mcpsimp"></a><a name="p10379mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p10381mcpsimp"><a name="p10381mcpsimp"></a><a name="p10381mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row10382mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p10384mcpsimp"><a name="p10384mcpsimp"></a><a name="p10384mcpsimp"></a>radius</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p10386mcpsimp"><a name="p10386mcpsimp"></a><a name="p10386mcpsimp"></a>圆的半径，单位：米。取值范围：大于等于0，默认为0。</p>
</td>
</tr>
</tbody>
</table>

## setStrokeColor<a name="section411010496468"></a>

<a name="table10391mcpsimp"></a>
<table><thead align="left"><tr id="row10395mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p10397mcpsimp"><a name="p10397mcpsimp"></a><a name="p10397mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row10398mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p10400mcpsimp"><a name="p10400mcpsimp"></a><a name="p10400mcpsimp"></a>public void setStrokeColor(int color)</p>
<p id="p285620813576"><a name="p285620813576"></a><a name="p285620813576"></a>您调用此API可以设置圆的边框颜色，如果使用TRANSPARENT，则不会绘制边框。</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table10406mcpsimp"></a>
<table><thead align="left"><tr id="row10411mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p10413mcpsimp"><a name="p10413mcpsimp"></a><a name="p10413mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p10415mcpsimp"><a name="p10415mcpsimp"></a><a name="p10415mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row10416mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p10418mcpsimp"><a name="p10418mcpsimp"></a><a name="p10418mcpsimp"></a>color</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p10420mcpsimp"><a name="p10420mcpsimp"></a><a name="p10420mcpsimp"></a>ARGB格式的颜色值，默认为黑色（0xff000000）。</p>
</td>
</tr>
</tbody>
</table>

## setStrokePattern<a name="section19343302476"></a>

<a name="table10425mcpsimp"></a>
<table><thead align="left"><tr id="row10429mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p10431mcpsimp"><a name="p10431mcpsimp"></a><a name="p10431mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row10432mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p10434mcpsimp"><a name="p10434mcpsimp"></a><a name="p10434mcpsimp"></a>public void setStrokePattern(List&lt;<a href="patternitem.md">PatternItem</a>&gt; pattern)</p>
<p id="p8442420175710"><a name="p8442420175710"></a><a name="p8442420175710"></a>您调用此API可以设置圆的边框样式。</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table10440mcpsimp"></a>
<table><thead align="left"><tr id="row10445mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p10447mcpsimp"><a name="p10447mcpsimp"></a><a name="p10447mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p10449mcpsimp"><a name="p10449mcpsimp"></a><a name="p10449mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row10450mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p10452mcpsimp"><a name="p10452mcpsimp"></a><a name="p10452mcpsimp"></a>pattern</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p10454mcpsimp"><a name="p10454mcpsimp"></a><a name="p10454mcpsimp"></a><a href="patternitem.md">PatternItem</a>对象的集合。默认的边框样式为实心，用null表示。</p>
</td>
</tr>
</tbody>
</table>

## setStrokeWidth<a name="section55401426164811"></a>

<a name="table10459mcpsimp"></a>
<table><thead align="left"><tr id="row10463mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p10465mcpsimp"><a name="p10465mcpsimp"></a><a name="p10465mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row10466mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p10468mcpsimp"><a name="p10468mcpsimp"></a><a name="p10468mcpsimp"></a>public void setStrokeWidth(float width)</p>
<p id="p1493412294579"><a name="p1493412294579"></a><a name="p1493412294579"></a>您调用此API可以设置圆的边框宽度。</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table10474mcpsimp"></a>
<table><thead align="left"><tr id="row10479mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p10481mcpsimp"><a name="p10481mcpsimp"></a><a name="p10481mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p10483mcpsimp"><a name="p10483mcpsimp"></a><a name="p10483mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row10484mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p10486mcpsimp"><a name="p10486mcpsimp"></a><a name="p10486mcpsimp"></a>width</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p10488mcpsimp"><a name="p10488mcpsimp"></a><a name="p10488mcpsimp"></a>边框的宽度，单位：像素。取值范围：大于等于0，默认为10。</p>
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
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p10508mcpsimp"><a name="p10508mcpsimp"></a><a name="p10508mcpsimp"></a>当传入的宽度width是负数时，抛出异常。</p>
</td>
</tr>
</tbody>
</table>

## setTag<a name="section136481518164819"></a>

<a name="table10510mcpsimp"></a>
<table><thead align="left"><tr id="row10514mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p10516mcpsimp"><a name="p10516mcpsimp"></a><a name="p10516mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row10517mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p10519mcpsimp"><a name="p10519mcpsimp"></a><a name="p10519mcpsimp"></a>public &lt;T&gt; void setTag(T tag)</p>
<p id="p8917150243"><a name="p8917150243"></a><a name="p8917150243"></a>您调用此API可以设置圆的tag属性，tag属性可以是任意对象，如果设置为空，则清除tag。当您不再需要使用tag时，您可以调用setTag(null)清除tag，以防止应用程序发生内存泄漏。</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table10525mcpsimp"></a>
<table><thead align="left"><tr id="row10530mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p10532mcpsimp"><a name="p10532mcpsimp"></a><a name="p10532mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p10534mcpsimp"><a name="p10534mcpsimp"></a><a name="p10534mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row10535mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p10537mcpsimp"><a name="p10537mcpsimp"></a><a name="p10537mcpsimp"></a>tag</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p10539mcpsimp"><a name="p10539mcpsimp"></a><a name="p10539mcpsimp"></a>圆的tag属性。</p>
</td>
</tr>
</tbody>
</table>

## setVisible<a name="section932681194811"></a>

<a name="table10544mcpsimp"></a>
<table><thead align="left"><tr id="row10548mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p10550mcpsimp"><a name="p10550mcpsimp"></a><a name="p10550mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row10551mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p10553mcpsimp"><a name="p10553mcpsimp"></a><a name="p10553mcpsimp"></a>public void setVisible(boolean visible)</p>
<p id="p94679465910"><a name="p94679465910"></a><a name="p94679465910"></a>您调用此API可以设置圆的可见性，如果圆不可见，则不会绘制，其他所有状态均保留，圆默认是可见的。</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table10559mcpsimp"></a>
<table><thead align="left"><tr id="row10564mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p10566mcpsimp"><a name="p10566mcpsimp"></a><a name="p10566mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p10568mcpsimp"><a name="p10568mcpsimp"></a><a name="p10568mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row10569mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p10571mcpsimp"><a name="p10571mcpsimp"></a><a name="p10571mcpsimp"></a>visible</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p10573mcpsimp"><a name="p10573mcpsimp"></a><a name="p10573mcpsimp"></a>圆的可见性。true表示可见，false表示不可见，默认值为true。</p>
</td>
</tr>
</tbody>
</table>

## setZIndex<a name="section1027016353395"></a>

<a name="table10578mcpsimp"></a>
<table><thead align="left"><tr id="row10582mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p10584mcpsimp"><a name="p10584mcpsimp"></a><a name="p10584mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row10585mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p10587mcpsimp"><a name="p10587mcpsimp"></a><a name="p10587mcpsimp"></a>public void setZIndex(float zIndex)</p>
<p id="p2075952618598"><a name="p2075952618598"></a><a name="p2075952618598"></a>设置圆的z指数。z指数指的是圆的叠加顺序，具有较大z指数的圆会绘制在具有较小z指数的圆上，具有相同z指数的叠加顺序为元素添加的先后顺序。默认的z指数是0。</p>
<div class="note" id="note113078372471"><a name="note113078372471"></a><a name="note113078372471"></a><span class="notetitle"> 说明： </span><div class="notebody"><p id="p113065581532"><a name="p113065581532"></a><a name="p113065581532"></a>数量限制：添加Circle和Polygon的总数乘以2加上添加Polyline和GroundOverlay的总数不超过1450，否则会出现图形叠加错误。</p>
</div></div>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table10593mcpsimp"></a>
<table><thead align="left"><tr id="row10598mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p10600mcpsimp"><a name="p10600mcpsimp"></a><a name="p10600mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p10602mcpsimp"><a name="p10602mcpsimp"></a><a name="p10602mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row10603mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p10605mcpsimp"><a name="p10605mcpsimp"></a><a name="p10605mcpsimp"></a>zIndex</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p10607mcpsimp"><a name="p10607mcpsimp"></a><a name="p10607mcpsimp"></a>z指数，即圆的叠加顺序。默认值为0。</p>
</td>
</tr>
</tbody>
</table>

