# CircleOptions<a name="ZH-CN_TOPIC_0000001145781041"></a>

-   [Public Constructor Summary](#section439314447312)
-   [Public Method Summary](#section2039212283411)
-   [Public Methods](#section670716341500)
-   [center](#section365865121019)
-   [clickable](#section4279958496)
-   [fillColor](#section57648507918)
-   [getCenter](#section159296438915)
-   [getFillColor](#section945603716910)
-   [getRadius](#section493520281194)
-   [getStrokeColor](#section1356318220911)
-   [getStrokePattern](#section38629151594)
-   [getStrokeWidth](#section18790176590)
-   [getZIndex](#section74931561814)
-   [isClickable](#section6518124913811)
-   [isVisible](#section1446212412818)
-   [radius](#section186231533383)
-   [strokeColor](#section3282620188)
-   [strokePattern](#section2156117585)
-   [strokeWidth](#section114061759477)
-   [visible](#section6360151777)
-   [zIndex](#section527510401471)


<a name="table10612mcpsimp"></a>
<table><thead align="left"><tr id="row10616mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p10618mcpsimp"><a name="p10618mcpsimp"></a><a name="p10618mcpsimp"></a>Class Info</p>
</th>
</tr>
</thead>
<tbody><tr id="row10619mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p143657505381"><a name="p143657505381"></a><a name="p143657505381"></a>public class CircleOptions</p>
<p id="p10621mcpsimp"><a name="p10621mcpsimp"></a><a name="p10621mcpsimp"></a>用于设置<a href="circle.md">Circle</a>对象的属性的类。</p>
</td>
</tr>
</tbody>
</table>

## Public Constructor Summary<a name="section439314447312"></a>

<a name="table10625mcpsimp"></a>
<table><thead align="left"><tr id="row10629mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p145mcpsimp"><a name="p145mcpsimp"></a><a name="p145mcpsimp"></a>Constructor Name</p>
</th>
</tr>
</thead>
<tbody><tr id="row10632mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p10634mcpsimp"><a name="p10634mcpsimp"></a><a name="p10634mcpsimp"></a><a href="circleoptions.md">CircleOptions</a>()</p>
<p id="p15887848143417"><a name="p15887848143417"></a><a name="p15887848143417"></a>CircleOptions类的默认构造方法。</p>
</td>
</tr>
</tbody>
</table>

## Public Method Summary<a name="section2039212283411"></a>

<a name="table10636mcpsimp"></a>
<table><thead align="left"><tr id="row10641mcpsimp"><th class="cellrowborder" valign="top" width="40%" id="mcps1.1.3.1.1"><p id="p081120285386"><a name="p081120285386"></a><a name="p081120285386"></a>Qualifier and Type</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.1.3.1.2"><p id="p681112883813"><a name="p681112883813"></a><a name="p681112883813"></a>Method Name and Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row10646mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p10648mcpsimp"><a name="p10648mcpsimp"></a><a name="p10648mcpsimp"></a><a href="circleoptions.md">CircleOptions</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p10650mcpsimp"><a name="p10650mcpsimp"></a><a name="p10650mcpsimp"></a><a href="#section365865121019">center</a>(<a href="latlng.md">LatLng </a>center)</p>
<p id="p8275121511410"><a name="p8275121511410"></a><a name="p8275121511410"></a>设置圆的圆心并获取一个<a href="circleoptions.md">CircleOptions</a>对象。</p>
</td>
</tr>
<tr id="row10651mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p10653mcpsimp"><a name="p10653mcpsimp"></a><a name="p10653mcpsimp"></a><a href="circleoptions.md">CircleOptions</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p10655mcpsimp"><a name="p10655mcpsimp"></a><a name="p10655mcpsimp"></a><a href="#section4279958496">clickable</a>(boolean clickable)</p>
<p id="p191761168416"><a name="p191761168416"></a><a name="p191761168416"></a>修改圆的点击属性，默认不可点击。</p>
</td>
</tr>
<tr id="row10656mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p10658mcpsimp"><a name="p10658mcpsimp"></a><a name="p10658mcpsimp"></a><a href="circleoptions.md">CircleOptions</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p10660mcpsimp"><a name="p10660mcpsimp"></a><a name="p10660mcpsimp"></a><a href="#section57648507918">fillColor</a>(int color)</p>
<p id="p1315814175419"><a name="p1315814175419"></a><a name="p1315814175419"></a>修改圆的填充色。</p>
</td>
</tr>
<tr id="row10661mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p10663mcpsimp"><a name="p10663mcpsimp"></a><a name="p10663mcpsimp"></a><a href="latlng.md">LatLng</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p10665mcpsimp"><a name="p10665mcpsimp"></a><a name="p10665mcpsimp"></a><a href="#section159296438915">getCenter</a>()</p>
<p id="p106441819411"><a name="p106441819411"></a><a name="p106441819411"></a>获取圆心的经纬度。</p>
</td>
</tr>
<tr id="row10666mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p10668mcpsimp"><a name="p10668mcpsimp"></a><a name="p10668mcpsimp"></a>int</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p10670mcpsimp"><a name="p10670mcpsimp"></a><a name="p10670mcpsimp"></a><a href="#section945603716910">getFillColor</a>()</p>
<p id="p127111916412"><a name="p127111916412"></a><a name="p127111916412"></a>获取圆的填充色值。</p>
</td>
</tr>
<tr id="row10671mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p10673mcpsimp"><a name="p10673mcpsimp"></a><a name="p10673mcpsimp"></a>double</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p10675mcpsimp"><a name="p10675mcpsimp"></a><a name="p10675mcpsimp"></a><a href="#section493520281194">getRadius</a>()</p>
<p id="p129271192416"><a name="p129271192416"></a><a name="p129271192416"></a>获取以米为单位的圆的半径。</p>
</td>
</tr>
<tr id="row10676mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p10678mcpsimp"><a name="p10678mcpsimp"></a><a name="p10678mcpsimp"></a>int</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p10680mcpsimp"><a name="p10680mcpsimp"></a><a name="p10680mcpsimp"></a><a href="#section1356318220911">getStrokeColor</a>()</p>
<p id="p1234821194117"><a name="p1234821194117"></a><a name="p1234821194117"></a>获取圆的边框颜色值。</p>
</td>
</tr>
<tr id="row10681mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p10683mcpsimp"><a name="p10683mcpsimp"></a><a name="p10683mcpsimp"></a>List&lt;<a href="patternitem.md">PatternItem</a>&gt;</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p10685mcpsimp"><a name="p10685mcpsimp"></a><a name="p10685mcpsimp"></a><a href="#section38629151594">getStrokePattern</a>()</p>
<p id="p4697182210416"><a name="p4697182210416"></a><a name="p4697182210416"></a>获取圆的边框样式。</p>
</td>
</tr>
<tr id="row10686mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p10688mcpsimp"><a name="p10688mcpsimp"></a><a name="p10688mcpsimp"></a>float</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p10690mcpsimp"><a name="p10690mcpsimp"></a><a name="p10690mcpsimp"></a><a href="#section18790176590">getStrokeWidth</a>()</p>
<p id="p1952315230419"><a name="p1952315230419"></a><a name="p1952315230419"></a>获取圆的边框宽度。</p>
</td>
</tr>
<tr id="row10691mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p10693mcpsimp"><a name="p10693mcpsimp"></a><a name="p10693mcpsimp"></a>float</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p10695mcpsimp"><a name="p10695mcpsimp"></a><a name="p10695mcpsimp"></a><a href="#section74931561814">getZIndex</a>()</p>
<p id="p5396624174112"><a name="p5396624174112"></a><a name="p5396624174112"></a>获取圆的Z指数。</p>
</td>
</tr>
<tr id="row10696mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p10698mcpsimp"><a name="p10698mcpsimp"></a><a name="p10698mcpsimp"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p10700mcpsimp"><a name="p10700mcpsimp"></a><a name="p10700mcpsimp"></a><a href="#section6518124913811">isClickable</a>()</p>
<p id="p517802694119"><a name="p517802694119"></a><a name="p517802694119"></a>获取圆的可点击属性。</p>
</td>
</tr>
<tr id="row10701mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p10703mcpsimp"><a name="p10703mcpsimp"></a><a name="p10703mcpsimp"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p10705mcpsimp"><a name="p10705mcpsimp"></a><a name="p10705mcpsimp"></a><a href="#section1446212412818">isVisible</a>()</p>
<p id="p12283192724110"><a name="p12283192724110"></a><a name="p12283192724110"></a>获取圆的可见属性。</p>
</td>
</tr>
<tr id="row10706mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p10708mcpsimp"><a name="p10708mcpsimp"></a><a name="p10708mcpsimp"></a><a href="circleoptions.md">CircleOptions</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p10710mcpsimp"><a name="p10710mcpsimp"></a><a name="p10710mcpsimp"></a><a href="#section186231533383">radius</a>(double radius)</p>
<p id="p4199162984119"><a name="p4199162984119"></a><a name="p4199162984119"></a>传入一个&gt;=0的值来设置圆的半径。</p>
</td>
</tr>
<tr id="row10711mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p10713mcpsimp"><a name="p10713mcpsimp"></a><a name="p10713mcpsimp"></a><a href="circleoptions.md">CircleOptions</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p10715mcpsimp"><a name="p10715mcpsimp"></a><a name="p10715mcpsimp"></a><a href="#section3282620188">strokeColor</a>(int color)</p>
<p id="p6469430144115"><a name="p6469430144115"></a><a name="p6469430144115"></a>改变圆的边框颜色。</p>
</td>
</tr>
<tr id="row10716mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p10718mcpsimp"><a name="p10718mcpsimp"></a><a name="p10718mcpsimp"></a><a href="circleoptions.md">CircleOptions</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p10720mcpsimp"><a name="p10720mcpsimp"></a><a name="p10720mcpsimp"></a><a href="#section2156117585">strokePattern</a>(List&lt;<a href="patternitem.md">PatternItem</a>&gt; pattern)</p>
<p id="p1381443117411"><a name="p1381443117411"></a><a name="p1381443117411"></a>改变圆的边框样式。</p>
</td>
</tr>
<tr id="row10721mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p10723mcpsimp"><a name="p10723mcpsimp"></a><a name="p10723mcpsimp"></a><a href="circleoptions.md">CircleOptions</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p10725mcpsimp"><a name="p10725mcpsimp"></a><a name="p10725mcpsimp"></a><a href="#section114061759477">strokeWidth</a>(float width)</p>
<p id="p1211993334118"><a name="p1211993334118"></a><a name="p1211993334118"></a>设置圆边框的宽度。</p>
</td>
</tr>
<tr id="row10726mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p10728mcpsimp"><a name="p10728mcpsimp"></a><a name="p10728mcpsimp"></a><a href="circleoptions.md">CircleOptions</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p10730mcpsimp"><a name="p10730mcpsimp"></a><a name="p10730mcpsimp"></a><a href="#section6360151777">visible</a>(boolean visible)</p>
<p id="p93838342415"><a name="p93838342415"></a><a name="p93838342415"></a>设置圆的可见性。</p>
</td>
</tr>
<tr id="row10731mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p10733mcpsimp"><a name="p10733mcpsimp"></a><a name="p10733mcpsimp"></a><a href="circleoptions.md">CircleOptions</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p10735mcpsimp"><a name="p10735mcpsimp"></a><a name="p10735mcpsimp"></a><a href="#section527510401471">zIndex</a>(float zIndex)</p>
<p id="p134633517411"><a name="p134633517411"></a><a name="p134633517411"></a>设置圆的z指数。</p>
</td>
</tr>
</tbody>
</table>

## Public Methods<a name="section670716341500"></a>

## center<a name="section365865121019"></a>

<a name="table10759mcpsimp"></a>
<table><thead align="left"><tr id="row10763mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p10765mcpsimp"><a name="p10765mcpsimp"></a><a name="p10765mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row10766mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p10768mcpsimp"><a name="p10768mcpsimp"></a><a name="p10768mcpsimp"></a>public <a href="circleoptions.md">CircleOptions</a> center(<a href="latlng.md">LatLng</a> center)</p>
<p id="p364715186011"><a name="p364715186011"></a><a name="p364715186011"></a>您必须调用此API来设置圆的圆心并获取一个<a href="circleoptions.md">CircleOptions</a>对象。此方法是强制性的，因为没有默认的圆心。</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table10774mcpsimp"></a>
<table><thead align="left"><tr id="row10779mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p10781mcpsimp"><a name="p10781mcpsimp"></a><a name="p10781mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p10783mcpsimp"><a name="p10783mcpsimp"></a><a name="p10783mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row10784mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p10786mcpsimp"><a name="p10786mcpsimp"></a><a name="p10786mcpsimp"></a>center</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p10788mcpsimp"><a name="p10788mcpsimp"></a><a name="p10788mcpsimp"></a>圆的圆心，不能为空。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table10791mcpsimp"></a>
<table><thead align="left"><tr id="row10796mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p10798mcpsimp"><a name="p10798mcpsimp"></a><a name="p10798mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p10800mcpsimp"><a name="p10800mcpsimp"></a><a name="p10800mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row10801mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p1555317211417"><a name="p1555317211417"></a><a name="p1555317211417"></a>CircleOptions</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p10803mcpsimp"><a name="p10803mcpsimp"></a><a name="p10803mcpsimp"></a><a href="circleoptions.md">CircleOptions</a>对象。</p>
</td>
</tr>
</tbody>
</table>

## clickable<a name="section4279958496"></a>

<a name="table10807mcpsimp"></a>
<table><thead align="left"><tr id="row10811mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p10813mcpsimp"><a name="p10813mcpsimp"></a><a name="p10813mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row10814mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p10816mcpsimp"><a name="p10816mcpsimp"></a><a name="p10816mcpsimp"></a>public <a href="circleoptions.md">CircleOptions</a> clickable(boolean clickable)</p>
<p id="p1365132718020"><a name="p1365132718020"></a><a name="p1365132718020"></a>您调用此API可以修改圆的点击属性，默认不可点击。</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table10822mcpsimp"></a>
<table><thead align="left"><tr id="row10827mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p10829mcpsimp"><a name="p10829mcpsimp"></a><a name="p10829mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p10831mcpsimp"><a name="p10831mcpsimp"></a><a name="p10831mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row10832mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p10834mcpsimp"><a name="p10834mcpsimp"></a><a name="p10834mcpsimp"></a>clickable</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p10836mcpsimp"><a name="p10836mcpsimp"></a><a name="p10836mcpsimp"></a>true表示可点击，false表示不可点击。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table10839mcpsimp"></a>
<table><thead align="left"><tr id="row10844mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p10846mcpsimp"><a name="p10846mcpsimp"></a><a name="p10846mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p10848mcpsimp"><a name="p10848mcpsimp"></a><a name="p10848mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row10849mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p10851mcpsimp"><a name="p10851mcpsimp"></a><a name="p10851mcpsimp"></a>CircleOptions</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p10853mcpsimp"><a name="p10853mcpsimp"></a><a name="p10853mcpsimp"></a><a href="circleoptions.md">CircleOptions</a>对象。</p>
</td>
</tr>
</tbody>
</table>

## fillColor<a name="section57648507918"></a>

<a name="table10855mcpsimp"></a>
<table><thead align="left"><tr id="row10859mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p10861mcpsimp"><a name="p10861mcpsimp"></a><a name="p10861mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row10862mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p10864mcpsimp"><a name="p10864mcpsimp"></a><a name="p10864mcpsimp"></a>public <a href="circleoptions.md">CircleOptions</a> fillColor(int color)</p>
<p id="p455019371404"><a name="p455019371404"></a><a name="p455019371404"></a>您调用此API可以修改圆的填充色。</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table10870mcpsimp"></a>
<table><thead align="left"><tr id="row10875mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p10877mcpsimp"><a name="p10877mcpsimp"></a><a name="p10877mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p10879mcpsimp"><a name="p10879mcpsimp"></a><a name="p10879mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row10880mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p10882mcpsimp"><a name="p10882mcpsimp"></a><a name="p10882mcpsimp"></a>color</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p10884mcpsimp"><a name="p10884mcpsimp"></a><a name="p10884mcpsimp"></a>圆的填充色值。ARGB格式颜色值，默认填充色为透明色（0x00000000）。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table10887mcpsimp"></a>
<table><thead align="left"><tr id="row10892mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p10894mcpsimp"><a name="p10894mcpsimp"></a><a name="p10894mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p10896mcpsimp"><a name="p10896mcpsimp"></a><a name="p10896mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row10897mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p10899mcpsimp"><a name="p10899mcpsimp"></a><a name="p10899mcpsimp"></a>CircleOptions</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p10901mcpsimp"><a name="p10901mcpsimp"></a><a name="p10901mcpsimp"></a><a href="circleoptions.md">CircleOptions</a>对象。</p>
</td>
</tr>
</tbody>
</table>

## getCenter<a name="section159296438915"></a>

<a name="table10903mcpsimp"></a>
<table><thead align="left"><tr id="row10907mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p10909mcpsimp"><a name="p10909mcpsimp"></a><a name="p10909mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row10910mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p10912mcpsimp"><a name="p10912mcpsimp"></a><a name="p10912mcpsimp"></a>public <a href="latlng.md">LatLng</a> getCenter()</p>
<p id="p88825471701"><a name="p88825471701"></a><a name="p88825471701"></a>您调用此API可以获取圆心的经纬度。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table10921mcpsimp"></a>
<table><thead align="left"><tr id="row10926mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p10928mcpsimp"><a name="p10928mcpsimp"></a><a name="p10928mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p10930mcpsimp"><a name="p10930mcpsimp"></a><a name="p10930mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row10931mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p10933mcpsimp"><a name="p10933mcpsimp"></a><a name="p10933mcpsimp"></a>LatLng</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p10935mcpsimp"><a name="p10935mcpsimp"></a><a name="p10935mcpsimp"></a><a href="latlng.md">LatLng</a>对象。</p>
</td>
</tr>
</tbody>
</table>

## getFillColor<a name="section945603716910"></a>

<a name="table10937mcpsimp"></a>
<table><thead align="left"><tr id="row10941mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p10943mcpsimp"><a name="p10943mcpsimp"></a><a name="p10943mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row10944mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p10946mcpsimp"><a name="p10946mcpsimp"></a><a name="p10946mcpsimp"></a>public int getFillColor()</p>
<p id="p1047613571808"><a name="p1047613571808"></a><a name="p1047613571808"></a>您调用此API可以获取圆的填充色值。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table10955mcpsimp"></a>
<table><thead align="left"><tr id="row10960mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p10962mcpsimp"><a name="p10962mcpsimp"></a><a name="p10962mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p10964mcpsimp"><a name="p10964mcpsimp"></a><a name="p10964mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row10965mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p10967mcpsimp"><a name="p10967mcpsimp"></a><a name="p10967mcpsimp"></a>int</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p10969mcpsimp"><a name="p10969mcpsimp"></a><a name="p10969mcpsimp"></a>圆的填充颜色。</p>
</td>
</tr>
</tbody>
</table>

## getRadius<a name="section493520281194"></a>

<a name="table10971mcpsimp"></a>
<table><thead align="left"><tr id="row10975mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p10977mcpsimp"><a name="p10977mcpsimp"></a><a name="p10977mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row10978mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p10980mcpsimp"><a name="p10980mcpsimp"></a><a name="p10980mcpsimp"></a>public double getRadius()</p>
<p id="p10657671413"><a name="p10657671413"></a><a name="p10657671413"></a>您调用此API可以获取以米为单位的圆的半径。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table10989mcpsimp"></a>
<table><thead align="left"><tr id="row10994mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p10996mcpsimp"><a name="p10996mcpsimp"></a><a name="p10996mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p10998mcpsimp"><a name="p10998mcpsimp"></a><a name="p10998mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row10999mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p11001mcpsimp"><a name="p11001mcpsimp"></a><a name="p11001mcpsimp"></a>double</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p11003mcpsimp"><a name="p11003mcpsimp"></a><a name="p11003mcpsimp"></a>圆的半径，单位：米。</p>
</td>
</tr>
</tbody>
</table>

## getStrokeColor<a name="section1356318220911"></a>

<a name="table11005mcpsimp"></a>
<table><thead align="left"><tr id="row11009mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p11011mcpsimp"><a name="p11011mcpsimp"></a><a name="p11011mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row11012mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p11014mcpsimp"><a name="p11014mcpsimp"></a><a name="p11014mcpsimp"></a>public int getStrokeColor()</p>
<p id="p17546167110"><a name="p17546167110"></a><a name="p17546167110"></a>您调用此API可以获取圆的边框颜色值。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table11023mcpsimp"></a>
<table><thead align="left"><tr id="row11028mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p11030mcpsimp"><a name="p11030mcpsimp"></a><a name="p11030mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p11032mcpsimp"><a name="p11032mcpsimp"></a><a name="p11032mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row11033mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p11035mcpsimp"><a name="p11035mcpsimp"></a><a name="p11035mcpsimp"></a>int</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p11037mcpsimp"><a name="p11037mcpsimp"></a><a name="p11037mcpsimp"></a>圆的边框颜色。</p>
</td>
</tr>
</tbody>
</table>

## getStrokePattern<a name="section38629151594"></a>

<a name="table11039mcpsimp"></a>
<table><thead align="left"><tr id="row11043mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p11045mcpsimp"><a name="p11045mcpsimp"></a><a name="p11045mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row11046mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p11048mcpsimp"><a name="p11048mcpsimp"></a><a name="p11048mcpsimp"></a>public List&lt;<a href="patternitem.md">PatternItem</a>&gt; getStrokePattern()</p>
<p id="p650117251013"><a name="p650117251013"></a><a name="p650117251013"></a>您调用此API可以获取圆的边框样式。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table11057mcpsimp"></a>
<table><thead align="left"><tr id="row11062mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p11064mcpsimp"><a name="p11064mcpsimp"></a><a name="p11064mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p11066mcpsimp"><a name="p11066mcpsimp"></a><a name="p11066mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row11067mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p11069mcpsimp"><a name="p11069mcpsimp"></a><a name="p11069mcpsimp"></a>List&lt;<a href="patternitem.md">PatternItem</a>&gt;</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p11071mcpsimp"><a name="p11071mcpsimp"></a><a name="p11071mcpsimp"></a>圆的边框样式。</p>
</td>
</tr>
</tbody>
</table>

## getStrokeWidth<a name="section18790176590"></a>

<a name="table11073mcpsimp"></a>
<table><thead align="left"><tr id="row11077mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p11079mcpsimp"><a name="p11079mcpsimp"></a><a name="p11079mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row11080mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p11082mcpsimp"><a name="p11082mcpsimp"></a><a name="p11082mcpsimp"></a>public float getStrokeWidth()</p>
<p id="p632518388114"><a name="p632518388114"></a><a name="p632518388114"></a>您调用此API可以获取圆的边框宽度。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table11091mcpsimp"></a>
<table><thead align="left"><tr id="row11096mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p11098mcpsimp"><a name="p11098mcpsimp"></a><a name="p11098mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p11100mcpsimp"><a name="p11100mcpsimp"></a><a name="p11100mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row11101mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p11103mcpsimp"><a name="p11103mcpsimp"></a><a name="p11103mcpsimp"></a>float</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p11105mcpsimp"><a name="p11105mcpsimp"></a><a name="p11105mcpsimp"></a>圆的边框宽度，单位：像素。</p>
</td>
</tr>
</tbody>
</table>

## getZIndex<a name="section74931561814"></a>

<a name="table11107mcpsimp"></a>
<table><thead align="left"><tr id="row11111mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p11113mcpsimp"><a name="p11113mcpsimp"></a><a name="p11113mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row11114mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p11116mcpsimp"><a name="p11116mcpsimp"></a><a name="p11116mcpsimp"></a>public float getZIndex()</p>
<p id="p2066934612118"><a name="p2066934612118"></a><a name="p2066934612118"></a>您调用此API可以获取圆的Z指数。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table11125mcpsimp"></a>
<table><thead align="left"><tr id="row11130mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p11132mcpsimp"><a name="p11132mcpsimp"></a><a name="p11132mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p11134mcpsimp"><a name="p11134mcpsimp"></a><a name="p11134mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row11135mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p11137mcpsimp"><a name="p11137mcpsimp"></a><a name="p11137mcpsimp"></a>float</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p11139mcpsimp"><a name="p11139mcpsimp"></a><a name="p11139mcpsimp"></a>z指数，即圆的叠加顺序。</p>
</td>
</tr>
</tbody>
</table>

## isClickable<a name="section6518124913811"></a>

<a name="table11141mcpsimp"></a>
<table><thead align="left"><tr id="row11145mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p11147mcpsimp"><a name="p11147mcpsimp"></a><a name="p11147mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row11148mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p11150mcpsimp"><a name="p11150mcpsimp"></a><a name="p11150mcpsimp"></a>public boolean isClickable()</p>
<p id="p81515813114"><a name="p81515813114"></a><a name="p81515813114"></a>您调用此API可以获取圆的可点击属性。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table11159mcpsimp"></a>
<table><thead align="left"><tr id="row11164mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p11166mcpsimp"><a name="p11166mcpsimp"></a><a name="p11166mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p11168mcpsimp"><a name="p11168mcpsimp"></a><a name="p11168mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row11169mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p11171mcpsimp"><a name="p11171mcpsimp"></a><a name="p11171mcpsimp"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p11173mcpsimp"><a name="p11173mcpsimp"></a><a name="p11173mcpsimp"></a>true表示可点击，false表示不可点击，默认值为false。</p>
</td>
</tr>
</tbody>
</table>

## isVisible<a name="section1446212412818"></a>

<a name="table11175mcpsimp"></a>
<table><thead align="left"><tr id="row11179mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p11181mcpsimp"><a name="p11181mcpsimp"></a><a name="p11181mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row11182mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p11184mcpsimp"><a name="p11184mcpsimp"></a><a name="p11184mcpsimp"></a>public boolean isVisible()</p>
<p id="p145188326"><a name="p145188326"></a><a name="p145188326"></a>您调用此API可以获取圆的可见属性。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table11193mcpsimp"></a>
<table><thead align="left"><tr id="row11198mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p11200mcpsimp"><a name="p11200mcpsimp"></a><a name="p11200mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p11202mcpsimp"><a name="p11202mcpsimp"></a><a name="p11202mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row11203mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p11205mcpsimp"><a name="p11205mcpsimp"></a><a name="p11205mcpsimp"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p11207mcpsimp"><a name="p11207mcpsimp"></a><a name="p11207mcpsimp"></a>true表示可见，false表示不可见。</p>
</td>
</tr>
</tbody>
</table>

## radius<a name="section186231533383"></a>

<a name="table11209mcpsimp"></a>
<table><thead align="left"><tr id="row11213mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p11215mcpsimp"><a name="p11215mcpsimp"></a><a name="p11215mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row11216mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p11218mcpsimp"><a name="p11218mcpsimp"></a><a name="p11218mcpsimp"></a>public <a href="circleoptions.md">CircleOptions</a> radius(double radius)</p>
<p id="p11221mcpsimp"><a name="p11221mcpsimp"></a><a name="p11221mcpsimp"></a>您调用此API可以传入一个&gt;=0的值来设置圆的半径。当radius值为负数时，调用<a href="huaweimap.md">HuaweiMap</a>.<a href="huaweimap.md#section7603022114010">addCircle</a>(<a href="circleoptions.md">CircleOptions</a> options)方法会抛出IllegalArgumentException异常。</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table11224mcpsimp"></a>
<table><thead align="left"><tr id="row11229mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p11231mcpsimp"><a name="p11231mcpsimp"></a><a name="p11231mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p11233mcpsimp"><a name="p11233mcpsimp"></a><a name="p11233mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row11234mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p11236mcpsimp"><a name="p11236mcpsimp"></a><a name="p11236mcpsimp"></a>radius</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p11238mcpsimp"><a name="p11238mcpsimp"></a><a name="p11238mcpsimp"></a>圆的半径，单位：米。圆的半径默认为0。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table11241mcpsimp"></a>
<table><thead align="left"><tr id="row11246mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p11248mcpsimp"><a name="p11248mcpsimp"></a><a name="p11248mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p11250mcpsimp"><a name="p11250mcpsimp"></a><a name="p11250mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row11251mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p11253mcpsimp"><a name="p11253mcpsimp"></a><a name="p11253mcpsimp"></a>CircleOptions</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p11255mcpsimp"><a name="p11255mcpsimp"></a><a name="p11255mcpsimp"></a><a href="circleoptions.md">CircleOptions</a>对象。</p>
</td>
</tr>
</tbody>
</table>

## strokeColor<a name="section3282620188"></a>

<a name="table11257mcpsimp"></a>
<table><thead align="left"><tr id="row11261mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p11263mcpsimp"><a name="p11263mcpsimp"></a><a name="p11263mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row11264mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p11266mcpsimp"><a name="p11266mcpsimp"></a><a name="p11266mcpsimp"></a>public <a href="circleoptions.md">CircleOptions</a> strokeColor(int color)</p>
<p id="p11269mcpsimp"><a name="p11269mcpsimp"></a><a name="p11269mcpsimp"></a>您调用此API可以改变圆的边框颜色。</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table11272mcpsimp"></a>
<table><thead align="left"><tr id="row11277mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p11279mcpsimp"><a name="p11279mcpsimp"></a><a name="p11279mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p11281mcpsimp"><a name="p11281mcpsimp"></a><a name="p11281mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row11282mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p11284mcpsimp"><a name="p11284mcpsimp"></a><a name="p11284mcpsimp"></a>color</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p11286mcpsimp"><a name="p11286mcpsimp"></a><a name="p11286mcpsimp"></a>边框颜色。ARGB格式颜色值，默认为黑色（0xff000000）。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table11289mcpsimp"></a>
<table><thead align="left"><tr id="row11294mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p11296mcpsimp"><a name="p11296mcpsimp"></a><a name="p11296mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p11298mcpsimp"><a name="p11298mcpsimp"></a><a name="p11298mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row11299mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p11301mcpsimp"><a name="p11301mcpsimp"></a><a name="p11301mcpsimp"></a>CircleOptions</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p11303mcpsimp"><a name="p11303mcpsimp"></a><a name="p11303mcpsimp"></a><a href="circleoptions.md">CircleOptions</a>对象。</p>
</td>
</tr>
</tbody>
</table>

## strokePattern<a name="section2156117585"></a>

<a name="table11305mcpsimp"></a>
<table><thead align="left"><tr id="row11309mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p11311mcpsimp"><a name="p11311mcpsimp"></a><a name="p11311mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row11312mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p11314mcpsimp"><a name="p11314mcpsimp"></a><a name="p11314mcpsimp"></a>public <a href="circleoptions.md">CircleOptions</a> strokePattern(List&lt;<a href="patternitem.md">PatternItem</a>&gt; pattern)</p>
<p id="p122511451129"><a name="p122511451129"></a><a name="p122511451129"></a>您调用此API可以改变圆的边框样式。</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table11320mcpsimp"></a>
<table><thead align="left"><tr id="row11325mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p11327mcpsimp"><a name="p11327mcpsimp"></a><a name="p11327mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p11329mcpsimp"><a name="p11329mcpsimp"></a><a name="p11329mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row11330mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p11332mcpsimp"><a name="p11332mcpsimp"></a><a name="p11332mcpsimp"></a>pattern</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p11334mcpsimp"><a name="p11334mcpsimp"></a><a name="p11334mcpsimp"></a>边框样式。默认的边框样式为实心，用null表示。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table11337mcpsimp"></a>
<table><thead align="left"><tr id="row11342mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p11344mcpsimp"><a name="p11344mcpsimp"></a><a name="p11344mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p11346mcpsimp"><a name="p11346mcpsimp"></a><a name="p11346mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row11347mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p11349mcpsimp"><a name="p11349mcpsimp"></a><a name="p11349mcpsimp"></a>CircleOptions</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p11351mcpsimp"><a name="p11351mcpsimp"></a><a name="p11351mcpsimp"></a><a href="circleoptions.md">CircleOptions</a>对象。</p>
</td>
</tr>
</tbody>
</table>

## strokeWidth<a name="section114061759477"></a>

<a name="table11353mcpsimp"></a>
<table><thead align="left"><tr id="row11357mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p11359mcpsimp"><a name="p11359mcpsimp"></a><a name="p11359mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row11360mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p11362mcpsimp"><a name="p11362mcpsimp"></a><a name="p11362mcpsimp"></a>public <a href="circleoptions.md">CircleOptions</a> strokeWidth(float width)</p>
<p id="p8558955522"><a name="p8558955522"></a><a name="p8558955522"></a>您调用此API可以设置圆边框的宽度。当width值为负数时，调用<a href="huaweimap.md">HuaweiMap</a>.<a href="huaweimap.md#section7603022114010">addCircle</a>(<a href="circleoptions.md">CircleOptions</a> options)方法会抛出IllegalArgumentException异常。</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table11368mcpsimp"></a>
<table><thead align="left"><tr id="row11373mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p11375mcpsimp"><a name="p11375mcpsimp"></a><a name="p11375mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p11377mcpsimp"><a name="p11377mcpsimp"></a><a name="p11377mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row11378mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p11380mcpsimp"><a name="p11380mcpsimp"></a><a name="p11380mcpsimp"></a>width</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p11382mcpsimp"><a name="p11382mcpsimp"></a><a name="p11382mcpsimp"></a>边框的宽度，以像素为单位。取值范围：大于等于0，默认为10。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table11385mcpsimp"></a>
<table><thead align="left"><tr id="row11390mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p11392mcpsimp"><a name="p11392mcpsimp"></a><a name="p11392mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p11394mcpsimp"><a name="p11394mcpsimp"></a><a name="p11394mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row11395mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p11397mcpsimp"><a name="p11397mcpsimp"></a><a name="p11397mcpsimp"></a>CircleOptions</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p11399mcpsimp"><a name="p11399mcpsimp"></a><a name="p11399mcpsimp"></a><a href="circleoptions.md">CircleOptions</a>对象。</p>
</td>
</tr>
</tbody>
</table>

## visible<a name="section6360151777"></a>

<a name="table11401mcpsimp"></a>
<table><thead align="left"><tr id="row11405mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p11407mcpsimp"><a name="p11407mcpsimp"></a><a name="p11407mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row11408mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p11410mcpsimp"><a name="p11410mcpsimp"></a><a name="p11410mcpsimp"></a>public <a href="circleoptions.md">CircleOptions</a> visible(boolean visible)</p>
<p id="p137091751439"><a name="p137091751439"></a><a name="p137091751439"></a>您调用此API可以设置圆的可见性。如果圆不可见，则不会绘制它，但保留其所有其他状态。</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table11416mcpsimp"></a>
<table><thead align="left"><tr id="row11421mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p11423mcpsimp"><a name="p11423mcpsimp"></a><a name="p11423mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p11425mcpsimp"><a name="p11425mcpsimp"></a><a name="p11425mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row11426mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p11428mcpsimp"><a name="p11428mcpsimp"></a><a name="p11428mcpsimp"></a>visible</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p11430mcpsimp"><a name="p11430mcpsimp"></a><a name="p11430mcpsimp"></a>true表示可见，false表示不可见。默认值为true。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table11433mcpsimp"></a>
<table><thead align="left"><tr id="row11438mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p11440mcpsimp"><a name="p11440mcpsimp"></a><a name="p11440mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p11442mcpsimp"><a name="p11442mcpsimp"></a><a name="p11442mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row11443mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p11445mcpsimp"><a name="p11445mcpsimp"></a><a name="p11445mcpsimp"></a>CircleOptions</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p11447mcpsimp"><a name="p11447mcpsimp"></a><a name="p11447mcpsimp"></a><a href="circleoptions.md">CircleOptions</a>对象。</p>
</td>
</tr>
</tbody>
</table>

## zIndex<a name="section527510401471"></a>

<a name="table11449mcpsimp"></a>
<table><thead align="left"><tr id="row11453mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p11455mcpsimp"><a name="p11455mcpsimp"></a><a name="p11455mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row11456mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p11458mcpsimp"><a name="p11458mcpsimp"></a><a name="p11458mcpsimp"></a>public <a href="circleoptions.md">CircleOptions</a> zIndex(float zIndex)</p>
<p id="p896713173317"><a name="p896713173317"></a><a name="p896713173317"></a>设置圆的z指数。z指数指的是圆的叠加顺序，具有较大z指数的圆会绘制在具有较小z指数的圆上，具有相同z指数的叠加顺序为元素添加的先后顺序。</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table11464mcpsimp"></a>
<table><thead align="left"><tr id="row11469mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p11471mcpsimp"><a name="p11471mcpsimp"></a><a name="p11471mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p11473mcpsimp"><a name="p11473mcpsimp"></a><a name="p11473mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row11474mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p11476mcpsimp"><a name="p11476mcpsimp"></a><a name="p11476mcpsimp"></a>zIndex</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p11478mcpsimp"><a name="p11478mcpsimp"></a><a name="p11478mcpsimp"></a>z指数，即圆的叠加顺序。默认的z指数是0。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table11481mcpsimp"></a>
<table><thead align="left"><tr id="row11486mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p11488mcpsimp"><a name="p11488mcpsimp"></a><a name="p11488mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p11490mcpsimp"><a name="p11490mcpsimp"></a><a name="p11490mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row11491mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p11493mcpsimp"><a name="p11493mcpsimp"></a><a name="p11493mcpsimp"></a>CircleOptions</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p11495mcpsimp"><a name="p11495mcpsimp"></a><a name="p11495mcpsimp"></a><a href="circleoptions.md">CircleOptions</a>对象。</p>
</td>
</tr>
</tbody>
</table>

