# GroundOverlayOptions<a name="ZH-CN_TOPIC_0000001145860919"></a>

-   [Public Constructor Summary](#section795412714816)
-   [Public Method Summary](#section15311281918)
-   [Public Methods](#section14621195651919)
-   [anchor](#section25201542411)
-   [bearing](#section611612432290)
-   [clickable](#section6602193363017)
-   [getAnchorU](#section1325535053013)
-   [getAnchorV](#section8421423113110)
-   [getBearing](#section1457714507314)
-   [getBounds](#section18230114483216)
-   [getHeight](#section15528168103313)
-   [getImage](#section116509346333)
-   [getLocation](#section1664721283414)
-   [getTransparency](#section0265153112343)
-   [getWidth](#section7391091354)
-   [getZIndex](#section19884132218368)
-   [image](#section19876145116369)
-   [isClickable](#section1559761915375)
-   [isVisible](#section183891514193816)
-   [position\(LatLng location, float width\)](#section18441164103913)
-   [position\(LatLng location, float width, float height\)](#section1263995883915)
-   [positionFromBounds](#section1971542716405)
-   [transparency](#section146372104217)
-   [visible](#section1986154284211)
-   [zIndex](#section109261034311)


<a name="table12748mcpsimp"></a>
<table><thead align="left"><tr id="row12752mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p12754mcpsimp"><a name="p12754mcpsimp"></a><a name="p12754mcpsimp"></a>Class Info</p>
</th>
</tr>
</thead>
<tbody><tr id="row12755mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p1498055843915"><a name="p1498055843915"></a><a name="p1498055843915"></a>public class GroundOverlayOptions</p>
<p id="p12757mcpsimp"><a name="p12757mcpsimp"></a><a name="p12757mcpsimp"></a>用于设置<a href="groundoverlay.md">GroundOverlay</a>属性的类。</p>
</td>
</tr>
</tbody>
</table>

## Public Constructor Summary<a name="section795412714816"></a>

<a name="table12759mcpsimp"></a>
<table><thead align="left"><tr id="row12763mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p145mcpsimp"><a name="p145mcpsimp"></a><a name="p145mcpsimp"></a>Constructor Name</p>
</th>
</tr>
</thead>
<tbody><tr id="row12766mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p12768mcpsimp"><a name="p12768mcpsimp"></a><a name="p12768mcpsimp"></a><a href="groundoverlayoptions.md">GroundOverlayOptions</a>()</p>
<p id="p753943511"><a name="p753943511"></a><a name="p753943511"></a>GroundOverlayOptions类的默认构造方法。</p>
</td>
</tr>
</tbody>
</table>

## Public Method Summary<a name="section15311281918"></a>

<a name="table12770mcpsimp"></a>
<table><thead align="left"><tr id="row12775mcpsimp"><th class="cellrowborder" valign="top" width="40%" id="mcps1.1.3.1.1"><p id="p081120285386"><a name="p081120285386"></a><a name="p081120285386"></a>Qualifier and Type</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.1.3.1.2"><p id="p681112883813"><a name="p681112883813"></a><a name="p681112883813"></a>Method Name and Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row12780mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p12782mcpsimp"><a name="p12782mcpsimp"></a><a name="p12782mcpsimp"></a><a href="groundoverlayoptions.md">GroundOverlayOptions</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p12784mcpsimp"><a name="p12784mcpsimp"></a><a name="p12784mcpsimp"></a><a href="#section25201542411">anchor</a>(float u, float v)</p>
<p id="p747616398232"><a name="p747616398232"></a><a name="p747616398232"></a>设置覆盖物图片的对齐方式，即指定锚点的位置。</p>
</td>
</tr>
<tr id="row12785mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p12787mcpsimp"><a name="p12787mcpsimp"></a><a name="p12787mcpsimp"></a><a href="groundoverlayoptions.md">GroundOverlayOptions</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p12789mcpsimp"><a name="p12789mcpsimp"></a><a name="p12789mcpsimp"></a><a href="#section611612432290">bearing</a>(float bearing)</p>
<p id="p2051894002312"><a name="p2051894002312"></a><a name="p2051894002312"></a>设置覆盖物从正北顺时针的角度。</p>
</td>
</tr>
<tr id="row12790mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p12792mcpsimp"><a name="p12792mcpsimp"></a><a name="p12792mcpsimp"></a><a href="groundoverlayoptions.md">GroundOverlayOptions</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p12794mcpsimp"><a name="p12794mcpsimp"></a><a name="p12794mcpsimp"></a><a href="#section6602193363017">clickable</a>(boolean clickable)</p>
<p id="p1131844119236"><a name="p1131844119236"></a><a name="p1131844119236"></a>设置覆盖物的可点击性。</p>
</td>
</tr>
<tr id="row12795mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p12797mcpsimp"><a name="p12797mcpsimp"></a><a name="p12797mcpsimp"></a>float</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p12799mcpsimp"><a name="p12799mcpsimp"></a><a name="p12799mcpsimp"></a><a href="#section1325535053013">getAnchorU</a>()</p>
<p id="p51831442162316"><a name="p51831442162316"></a><a name="p51831442162316"></a>获取覆盖物锚点的水平位置的值。</p>
</td>
</tr>
<tr id="row12800mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p12802mcpsimp"><a name="p12802mcpsimp"></a><a name="p12802mcpsimp"></a>float</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p12804mcpsimp"><a name="p12804mcpsimp"></a><a name="p12804mcpsimp"></a><a href="#section8421423113110">getAnchorV</a>()</p>
<p id="p1318284311237"><a name="p1318284311237"></a><a name="p1318284311237"></a>获取覆盖物锚点的垂直位置的值。</p>
</td>
</tr>
<tr id="row12805mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p12807mcpsimp"><a name="p12807mcpsimp"></a><a name="p12807mcpsimp"></a>float</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p12809mcpsimp"><a name="p12809mcpsimp"></a><a name="p12809mcpsimp"></a><a href="#section1457714507314">getBearing</a>()</p>
<p id="p29521943202313"><a name="p29521943202313"></a><a name="p29521943202313"></a>获取覆盖物的角度。</p>
</td>
</tr>
<tr id="row12810mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p12812mcpsimp"><a name="p12812mcpsimp"></a><a name="p12812mcpsimp"></a><a href="latlngbounds.md">LatLngBounds</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p12814mcpsimp"><a name="p12814mcpsimp"></a><a name="p12814mcpsimp"></a><a href="#section18230114483216">getBounds</a>()</p>
<p id="p168962442235"><a name="p168962442235"></a><a name="p168962442235"></a>获取覆盖物的矩形区域。</p>
</td>
</tr>
<tr id="row12815mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p12817mcpsimp"><a name="p12817mcpsimp"></a><a name="p12817mcpsimp"></a>float</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p12819mcpsimp"><a name="p12819mcpsimp"></a><a name="p12819mcpsimp"></a><a href="#section15528168103313">getHeight</a>()</p>
<p id="p1722474652315"><a name="p1722474652315"></a><a name="p1722474652315"></a>获取覆盖物的高度。</p>
</td>
</tr>
<tr id="row12820mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p12822mcpsimp"><a name="p12822mcpsimp"></a><a name="p12822mcpsimp"></a><a href="bitmapdescriptor.md">BitmapDescriptor</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p12824mcpsimp"><a name="p12824mcpsimp"></a><a name="p12824mcpsimp"></a><a href="#section116509346333">getImage</a>()</p>
<p id="p179034713238"><a name="p179034713238"></a><a name="p179034713238"></a>获取覆盖物的图片信息。</p>
</td>
</tr>
<tr id="row12825mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p12827mcpsimp"><a name="p12827mcpsimp"></a><a name="p12827mcpsimp"></a>LatLng</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p12829mcpsimp"><a name="p12829mcpsimp"></a><a name="p12829mcpsimp"></a><a href="#section1664721283414">getLocation</a>()</p>
<p id="p1967412483238"><a name="p1967412483238"></a><a name="p1967412483238"></a>获取覆盖物的位置。</p>
</td>
</tr>
<tr id="row12830mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p12832mcpsimp"><a name="p12832mcpsimp"></a><a name="p12832mcpsimp"></a>float</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p12834mcpsimp"><a name="p12834mcpsimp"></a><a name="p12834mcpsimp"></a><a href="#section0265153112343">getTransparency</a>()</p>
<p id="p1518184992316"><a name="p1518184992316"></a><a name="p1518184992316"></a>获取覆盖物的透明度。</p>
</td>
</tr>
<tr id="row12835mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p12837mcpsimp"><a name="p12837mcpsimp"></a><a name="p12837mcpsimp"></a>float</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p12839mcpsimp"><a name="p12839mcpsimp"></a><a name="p12839mcpsimp"></a><a href="#section7391091354">getWidth</a>()</p>
<p id="p1374675082313"><a name="p1374675082313"></a><a name="p1374675082313"></a>获取覆盖物的宽度。</p>
</td>
</tr>
<tr id="row12840mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p12842mcpsimp"><a name="p12842mcpsimp"></a><a name="p12842mcpsimp"></a>float</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p12844mcpsimp"><a name="p12844mcpsimp"></a><a name="p12844mcpsimp"></a><a href="#section19884132218368">getZIndex</a>()</p>
<p id="p1259012516239"><a name="p1259012516239"></a><a name="p1259012516239"></a>获取覆盖物的z指数。</p>
</td>
</tr>
<tr id="row12845mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p12847mcpsimp"><a name="p12847mcpsimp"></a><a name="p12847mcpsimp"></a><a href="groundoverlayoptions.md">GroundOverlayOptions</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p12849mcpsimp"><a name="p12849mcpsimp"></a><a name="p12849mcpsimp"></a><a href="#section19876145116369">image</a>(<a href="bitmapdescriptor.md">BitmapDescriptor</a> imageDescriptor)</p>
<p id="p13423353182319"><a name="p13423353182319"></a><a name="p13423353182319"></a>设置覆盖物的图片信息。</p>
</td>
</tr>
<tr id="row12850mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p12852mcpsimp"><a name="p12852mcpsimp"></a><a name="p12852mcpsimp"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p12854mcpsimp"><a name="p12854mcpsimp"></a><a name="p12854mcpsimp"></a><a href="#section1559761915375">isClickable</a>()</p>
<p id="p1388311548237"><a name="p1388311548237"></a><a name="p1388311548237"></a>获取覆盖物的可点击性。</p>
</td>
</tr>
<tr id="row12855mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p12857mcpsimp"><a name="p12857mcpsimp"></a><a name="p12857mcpsimp"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p12859mcpsimp"><a name="p12859mcpsimp"></a><a name="p12859mcpsimp"></a><a href="#section183891514193816">isVisible</a>()</p>
<p id="p4746165516231"><a name="p4746165516231"></a><a name="p4746165516231"></a>获取覆盖物的可见性。</p>
</td>
</tr>
<tr id="row12860mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p12862mcpsimp"><a name="p12862mcpsimp"></a><a name="p12862mcpsimp"></a><a href="groundoverlayoptions.md">GroundOverlayOptions</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p12864mcpsimp"><a name="p12864mcpsimp"></a><a name="p12864mcpsimp"></a><a href="#section18441164103913">position</a>(<a href="latlng.md">LatLng</a> location, float width)</p>
<p id="p8809155613232"><a name="p8809155613232"></a><a name="p8809155613232"></a>根据位置和宽设置覆盖物。</p>
</td>
</tr>
<tr id="row12865mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p12867mcpsimp"><a name="p12867mcpsimp"></a><a name="p12867mcpsimp"></a><a href="groundoverlayoptions.md">GroundOverlayOptions</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p12869mcpsimp"><a name="p12869mcpsimp"></a><a name="p12869mcpsimp"></a><a href="#section1263995883915">position</a>(<a href="latlng.md">LatLng</a> location, float width, float height)</p>
<p id="p1970945752311"><a name="p1970945752311"></a><a name="p1970945752311"></a>根据位置和宽高设置覆盖物。</p>
</td>
</tr>
<tr id="row12870mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p12872mcpsimp"><a name="p12872mcpsimp"></a><a name="p12872mcpsimp"></a><a href="groundoverlayoptions.md">GroundOverlayOptions</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p12874mcpsimp"><a name="p12874mcpsimp"></a><a name="p12874mcpsimp"></a><a href="#section1971542716405">positionFromBounds</a>(<a href="latlngbounds.md">LatLngBounds</a> bounds)</p>
<p id="p20713185852313"><a name="p20713185852313"></a><a name="p20713185852313"></a>根据矩形区域设置覆盖物的位置。</p>
</td>
</tr>
<tr id="row12875mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p12877mcpsimp"><a name="p12877mcpsimp"></a><a name="p12877mcpsimp"></a><a href="groundoverlayoptions.md">GroundOverlayOptions</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p12879mcpsimp"><a name="p12879mcpsimp"></a><a name="p12879mcpsimp"></a><a href="#section146372104217">transparency</a>(float transparency)</p>
<p id="p126881759142315"><a name="p126881759142315"></a><a name="p126881759142315"></a>设置覆盖物的透明度。</p>
</td>
</tr>
<tr id="row12880mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p12882mcpsimp"><a name="p12882mcpsimp"></a><a name="p12882mcpsimp"></a><a href="groundoverlayoptions.md">GroundOverlayOptions</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p12884mcpsimp"><a name="p12884mcpsimp"></a><a name="p12884mcpsimp"></a><a href="#section1986154284211">visible</a>(boolean visible)</p>
<p id="p1871380162411"><a name="p1871380162411"></a><a name="p1871380162411"></a>设置覆盖物的可见性。</p>
</td>
</tr>
<tr id="row12885mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p12887mcpsimp"><a name="p12887mcpsimp"></a><a name="p12887mcpsimp"></a><a href="groundoverlayoptions.md">GroundOverlayOptions</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p12889mcpsimp"><a name="p12889mcpsimp"></a><a name="p12889mcpsimp"></a><a href="#section109261034311">zIndex</a>(float zIndex)</p>
<p id="p1381625249"><a name="p1381625249"></a><a name="p1381625249"></a>设置覆盖物的z指数。</p>
</td>
</tr>
</tbody>
</table>

## Public Methods<a name="section14621195651919"></a>

## anchor<a name="section25201542411"></a>

<a name="table1494933314235"></a>
<table><thead align="left"><tr id="row399413352314"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p12994133312235"><a name="p12994133312235"></a><a name="p12994133312235"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row129941433132310"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p10994733102319"><a name="p10994733102319"></a><a name="p10994733102319"></a>public <a href="groundoverlayoptions.md">GroundOverlayOptions</a> anchor(float u, float v)</p>
<p id="p1099423352317"><a name="p1099423352317"></a><a name="p1099423352317"></a>您调用此API可以设置覆盖物图片的对齐方式，即指定锚点的位置。（0, 0）是左上角，（1, 0）是右上角，（0, 1）是左下角，（1, 1）是右下角 。如果不设置，默认为（0.5, 0.5）图片的中心点。例如，在覆盖物X（0.5, 0.3）处的锚点坐标如下：</p>
<p id="p59941733152315"><a name="p59941733152315"></a><a name="p59941733152315"></a><a name="image7903341202517"></a><a name="image7903341202517"></a><span><img id="image7903341202517" src="figures/zh-cn_image_0000001145781059.png"></span></p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table169571433152316"></a>
<table><thead align="left"><tr id="row1599473314239"><th class="cellrowborder" valign="top" width="47.02%" id="mcps1.1.3.1.1"><p id="p250mcpsimp"><a name="p250mcpsimp"></a><a name="p250mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="52.980000000000004%" id="mcps1.1.3.1.2"><p id="p253mcpsimp"><a name="p253mcpsimp"></a><a name="p253mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row1995163311234"><td class="cellrowborder" valign="top" width="47.02%" headers="mcps1.1.3.1.1 "><p id="p17995833162318"><a name="p17995833162318"></a><a name="p17995833162318"></a>u</p>
</td>
<td class="cellrowborder" valign="top" width="52.980000000000004%" headers="mcps1.1.3.1.2 "><p id="p119954332237"><a name="p119954332237"></a><a name="p119954332237"></a>锚点的水平坐标，以图像宽度的比例，建议取值[0, 1]。默认值为0.5。</p>
</td>
</tr>
<tr id="row17995633162311"><td class="cellrowborder" valign="top" width="47.02%" headers="mcps1.1.3.1.1 "><p id="p1399553318236"><a name="p1399553318236"></a><a name="p1399553318236"></a>v</p>
</td>
<td class="cellrowborder" valign="top" width="52.980000000000004%" headers="mcps1.1.3.1.2 "><p id="p1799513335233"><a name="p1799513335233"></a><a name="p1799513335233"></a>锚点的垂直坐标，以图像高度的比例，建议取值[0, 1]。默认值为0.5。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table39611433192320"></a>
<table><thead align="left"><tr id="row4995133315234"><th class="cellrowborder" valign="top" width="47.02%" id="mcps1.1.3.1.1"><p id="p374mcpsimp"><a name="p374mcpsimp"></a><a name="p374mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="52.980000000000004%" id="mcps1.1.3.1.2"><p id="p377mcpsimp"><a name="p377mcpsimp"></a><a name="p377mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row19995153314231"><td class="cellrowborder" valign="top" width="47.02%" headers="mcps1.1.3.1.1 "><p id="p10995123312314"><a name="p10995123312314"></a><a name="p10995123312314"></a>GroundOverlayOptions</p>
</td>
<td class="cellrowborder" valign="top" width="52.980000000000004%" headers="mcps1.1.3.1.2 "><p id="p1995203316232"><a name="p1995203316232"></a><a name="p1995203316232"></a>设置新的对齐方式后的<a href="groundoverlayoptions.md">GroundOverlayOptions</a>对象。</p>
</td>
</tr>
</tbody>
</table>

## bearing<a name="section611612432290"></a>

<a name="table17901521122511"></a>
<table><thead align="left"><tr id="row1641892112254"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p3419172117255"><a name="p3419172117255"></a><a name="p3419172117255"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row12419132119258"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p9419021162518"><a name="p9419021162518"></a><a name="p9419021162518"></a>public <a href="groundoverlayoptions.md">GroundOverlayOptions</a> bearing(float bearing)</p>
<p id="p174191821172512"><a name="p174191821172512"></a><a name="p174191821172512"></a>您调用此API可以设置覆盖物从正北顺时针的角度。</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table2951821182517"></a>
<table><thead align="left"><tr id="row1941942117251"><th class="cellrowborder" valign="top" width="47.02%" id="mcps1.1.3.1.1"><p id="p183733772816"><a name="p183733772816"></a><a name="p183733772816"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="52.980000000000004%" id="mcps1.1.3.1.2"><p id="p1837311772810"><a name="p1837311772810"></a><a name="p1837311772810"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row1341962118252"><td class="cellrowborder" valign="top" width="47.02%" headers="mcps1.1.3.1.1 "><p id="p941952114252"><a name="p941952114252"></a><a name="p941952114252"></a>bearing</p>
</td>
<td class="cellrowborder" valign="top" width="52.980000000000004%" headers="mcps1.1.3.1.2 "><p id="p541922119256"><a name="p541922119256"></a><a name="p541922119256"></a>覆盖物从正北顺时针的角度，取值范围：[0, 360)<span>。默认值为0。</span></p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table3159221162519"></a>
<table><thead align="left"><tr id="row941916218254"><th class="cellrowborder" valign="top" width="47.02%" id="mcps1.1.3.1.1"><p id="p135533252813"><a name="p135533252813"></a><a name="p135533252813"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="52.980000000000004%" id="mcps1.1.3.1.2"><p id="p35532212284"><a name="p35532212284"></a><a name="p35532212284"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row1841912113256"><td class="cellrowborder" valign="top" width="47.02%" headers="mcps1.1.3.1.1 "><p id="p5419112192520"><a name="p5419112192520"></a><a name="p5419112192520"></a>GroundOverlayOptions</p>
</td>
<td class="cellrowborder" valign="top" width="52.980000000000004%" headers="mcps1.1.3.1.2 "><p id="p341914218257"><a name="p341914218257"></a><a name="p341914218257"></a>设置新的角度后的<a href="groundoverlayoptions.md">GroundOverlayOptions</a>对象。</p>
</td>
</tr>
</tbody>
</table>

## clickable<a name="section6602193363017"></a>

<a name="table14161421122514"></a>
<table><thead align="left"><tr id="row12419142132518"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p10419192172510"><a name="p10419192172510"></a><a name="p10419192172510"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row1741919219259"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p14419192112257"><a name="p14419192112257"></a><a name="p14419192112257"></a>public <a href="groundoverlayoptions.md">GroundOverlayOptions</a> clickable(boolean clickable)</p>
<p id="p97058219486"><a name="p97058219486"></a><a name="p97058219486"></a>您调用此API可以设置覆盖物的可点击性。</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table616232182518"></a>
<table><thead align="left"><tr id="row1142022117257"><th class="cellrowborder" valign="top" width="47.02%" id="mcps1.1.3.1.1"><p id="p269110334284"><a name="p269110334284"></a><a name="p269110334284"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="52.980000000000004%" id="mcps1.1.3.1.2"><p id="p86919332288"><a name="p86919332288"></a><a name="p86919332288"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row1420021172517"><td class="cellrowborder" valign="top" width="47.02%" headers="mcps1.1.3.1.1 "><p id="p442012213257"><a name="p442012213257"></a><a name="p442012213257"></a>clickable</p>
</td>
<td class="cellrowborder" valign="top" width="52.980000000000004%" headers="mcps1.1.3.1.2 "><p id="p19420182172511"><a name="p19420182172511"></a><a name="p19420182172511"></a>可点击性，默认为不可点击<span>。</span></p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table3164421182512"></a>
<table><thead align="left"><tr id="row14420521182517"><th class="cellrowborder" valign="top" width="47.02%" id="mcps1.1.3.1.1"><p id="p9929124213119"><a name="p9929124213119"></a><a name="p9929124213119"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="52.980000000000004%" id="mcps1.1.3.1.2"><p id="p159299427316"><a name="p159299427316"></a><a name="p159299427316"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row1342022182519"><td class="cellrowborder" valign="top" width="47.02%" headers="mcps1.1.3.1.1 "><p id="p18420132142510"><a name="p18420132142510"></a><a name="p18420132142510"></a>GroundOverlayOptions</p>
</td>
<td class="cellrowborder" valign="top" width="52.980000000000004%" headers="mcps1.1.3.1.2 "><p id="p1542012102519"><a name="p1542012102519"></a><a name="p1542012102519"></a>设置新的可点击性后的<a href="groundoverlayoptions.md">GroundOverlayOptions</a>对象。</p>
</td>
</tr>
</tbody>
</table>

## getAnchorU<a name="section1325535053013"></a>

<a name="table016682152513"></a>
<table><thead align="left"><tr id="row1142019211257"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p34201921162519"><a name="p34201921162519"></a><a name="p34201921162519"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row4420192112258"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p15420192114257"><a name="p15420192114257"></a><a name="p15420192114257"></a>public float getAnchorU()</p>
<p id="p11420152152520"><a name="p11420152152520"></a><a name="p11420152152520"></a>您调用此API可以获取覆盖物锚点的水平位置的值。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table0168182182520"></a>
<table><thead align="left"><tr id="row1542110212253"><th class="cellrowborder" valign="top" width="47.02%" id="mcps1.1.3.1.1"><p id="p18417184612312"><a name="p18417184612312"></a><a name="p18417184612312"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="52.980000000000004%" id="mcps1.1.3.1.2"><p id="p44173461319"><a name="p44173461319"></a><a name="p44173461319"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row642115219252"><td class="cellrowborder" valign="top" width="47.02%" headers="mcps1.1.3.1.1 "><p id="p1642122122510"><a name="p1642122122510"></a><a name="p1642122122510"></a>float</p>
</td>
<td class="cellrowborder" valign="top" width="52.980000000000004%" headers="mcps1.1.3.1.2 "><p id="p15421621132518"><a name="p15421621132518"></a><a name="p15421621132518"></a>锚点水平方向的值，取值范围：[0, 1]。</p>
</td>
</tr>
</tbody>
</table>

## getAnchorV<a name="section8421423113110"></a>

<a name="table916982117257"></a>
<table><thead align="left"><tr id="row1942182152518"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p16421182115259"><a name="p16421182115259"></a><a name="p16421182115259"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row1842122113259"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p13421122119253"><a name="p13421122119253"></a><a name="p13421122119253"></a>public float getAnchorV()</p>
<p id="p1787763414312"><a name="p1787763414312"></a><a name="p1787763414312"></a>您调用此API可以获取覆盖物锚点的垂直位置的值。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table3170821192518"></a>
<table><thead align="left"><tr id="row742114215255"><th class="cellrowborder" valign="top" width="47.02%" id="mcps1.1.3.1.1"><p id="p182761649153117"><a name="p182761649153117"></a><a name="p182761649153117"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="52.980000000000004%" id="mcps1.1.3.1.2"><p id="p12767496311"><a name="p12767496311"></a><a name="p12767496311"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row842115218255"><td class="cellrowborder" valign="top" width="47.02%" headers="mcps1.1.3.1.1 "><p id="p94211213251"><a name="p94211213251"></a><a name="p94211213251"></a>float</p>
</td>
<td class="cellrowborder" valign="top" width="52.980000000000004%" headers="mcps1.1.3.1.2 "><p id="p7421182162512"><a name="p7421182162512"></a><a name="p7421182162512"></a>锚点垂直方向的值，取值范围：[0, 1]。</p>
</td>
</tr>
</tbody>
</table>

## getBearing<a name="section1457714507314"></a>

<a name="table1517218213256"></a>
<table><thead align="left"><tr id="row14216217258"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p14421121192511"><a name="p14421121192511"></a><a name="p14421121192511"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row144211321142511"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p3422192112256"><a name="p3422192112256"></a><a name="p3422192112256"></a>public float getBearing()</p>
<p id="p54221211257"><a name="p54221211257"></a><a name="p54221211257"></a>您调用此API可以获取覆盖物的角度。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table1617318217254"></a>
<table><thead align="left"><tr id="row1442232172519"><th class="cellrowborder" valign="top" width="47.02%" id="mcps1.1.3.1.1"><p id="p891213513316"><a name="p891213513316"></a><a name="p891213513316"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="52.980000000000004%" id="mcps1.1.3.1.2"><p id="p13912165111312"><a name="p13912165111312"></a><a name="p13912165111312"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row2422821192519"><td class="cellrowborder" valign="top" width="47.02%" headers="mcps1.1.3.1.1 "><p id="p16422182113258"><a name="p16422182113258"></a><a name="p16422182113258"></a>float</p>
</td>
<td class="cellrowborder" valign="top" width="52.980000000000004%" headers="mcps1.1.3.1.2 "><p id="p542262122519"><a name="p542262122519"></a><a name="p542262122519"></a>覆盖物的角度，取值范围：[0, 360)。</p>
</td>
</tr>
</tbody>
</table>

## getBounds<a name="section18230114483216"></a>

<a name="table617432162516"></a>
<table><thead align="left"><tr id="row94223214252"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p94221219257"><a name="p94221219257"></a><a name="p94221219257"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row1842219217254"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p1042282118257"><a name="p1042282118257"></a><a name="p1042282118257"></a>public <a href="latlngbounds.md">LatLngBounds</a> getBounds()</p>
<p id="p5422921102517"><a name="p5422921102517"></a><a name="p5422921102517"></a>您调用此API可以获取覆盖物的矩形区域。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table3175162162515"></a>
<table><thead align="left"><tr id="row124227215258"><th class="cellrowborder" valign="top" width="47.02%" id="mcps1.1.3.1.1"><p id="p3745125519311"><a name="p3745125519311"></a><a name="p3745125519311"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="52.980000000000004%" id="mcps1.1.3.1.2"><p id="p774545515316"><a name="p774545515316"></a><a name="p774545515316"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row15422122102516"><td class="cellrowborder" valign="top" width="47.02%" headers="mcps1.1.3.1.1 "><p id="p34221214251"><a name="p34221214251"></a><a name="p34221214251"></a><a href="latlngbounds.md">LatLngBounds</a></p>
</td>
<td class="cellrowborder" valign="top" width="52.980000000000004%" headers="mcps1.1.3.1.2 "><p id="p7423132112519"><a name="p7423132112519"></a><a name="p7423132112519"></a>覆盖物的矩形区域。</p>
</td>
</tr>
</tbody>
</table>

## getHeight<a name="section15528168103313"></a>

<a name="table717611215251"></a>
<table><thead align="left"><tr id="row842310214256"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p114235218254"><a name="p114235218254"></a><a name="p114235218254"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row154239217259"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p144231421132520"><a name="p144231421132520"></a><a name="p144231421132520"></a>public float getHeight()</p>
<p id="p94231021162514"><a name="p94231021162514"></a><a name="p94231021162514"></a>您调用此API可以获取覆盖物的高度。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table017852152516"></a>
<table><thead align="left"><tr id="row194236216256"><th class="cellrowborder" valign="top" width="47.02%" id="mcps1.1.3.1.1"><p id="p14503205818311"><a name="p14503205818311"></a><a name="p14503205818311"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="52.980000000000004%" id="mcps1.1.3.1.2"><p id="p11503155873118"><a name="p11503155873118"></a><a name="p11503155873118"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row242310216251"><td class="cellrowborder" valign="top" width="47.02%" headers="mcps1.1.3.1.1 "><p id="p94231221112511"><a name="p94231221112511"></a><a name="p94231221112511"></a>float</p>
</td>
<td class="cellrowborder" valign="top" width="52.980000000000004%" headers="mcps1.1.3.1.2 "><p id="p8423202119253"><a name="p8423202119253"></a><a name="p8423202119253"></a>覆盖物的高度，单位：米。</p>
</td>
</tr>
</tbody>
</table>

## getImage<a name="section116509346333"></a>

<a name="table2179172112520"></a>
<table><thead align="left"><tr id="row8423152152517"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p742315215259"><a name="p742315215259"></a><a name="p742315215259"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row1042372132511"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p20423162117250"><a name="p20423162117250"></a><a name="p20423162117250"></a>public <a href="bitmapdescriptor.md">BitmapDescriptor</a> getImage()</p>
<p id="p13423521112516"><a name="p13423521112516"></a><a name="p13423521112516"></a>您调用此API可以获取覆盖物的图片信息。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table1318010214253"></a>
<table><thead align="left"><tr id="row5423142112516"><th class="cellrowborder" valign="top" width="47.02%" id="mcps1.1.3.1.1"><p id="p0656161153216"><a name="p0656161153216"></a><a name="p0656161153216"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="52.980000000000004%" id="mcps1.1.3.1.2"><p id="p11656151173213"><a name="p11656151173213"></a><a name="p11656151173213"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row7424132162517"><td class="cellrowborder" valign="top" width="47.02%" headers="mcps1.1.3.1.1 "><p id="p1424021182512"><a name="p1424021182512"></a><a name="p1424021182512"></a><a href="bitmapdescriptor.md">BitmapDescriptor</a></p>
</td>
<td class="cellrowborder" valign="top" width="52.980000000000004%" headers="mcps1.1.3.1.2 "><p id="p1642420219252"><a name="p1642420219252"></a><a name="p1642420219252"></a>覆盖物图片。</p>
</td>
</tr>
</tbody>
</table>

## getLocation<a name="section1664721283414"></a>

<a name="table918122172520"></a>
<table><thead align="left"><tr id="row942452142519"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p342442112512"><a name="p342442112512"></a><a name="p342442112512"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row1342442120252"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p1742492172514"><a name="p1742492172514"></a><a name="p1742492172514"></a>public <a href="latlng.md">LatLng</a> getLocation()</p>
<p id="p442419216256"><a name="p442419216256"></a><a name="p442419216256"></a>您调用此API可以获取覆盖物的位置。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table1518314213255"></a>
<table><thead align="left"><tr id="row24241121142514"><th class="cellrowborder" valign="top" width="47.02%" id="mcps1.1.3.1.1"><p id="p1048113411323"><a name="p1048113411323"></a><a name="p1048113411323"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="52.980000000000004%" id="mcps1.1.3.1.2"><p id="p13481446322"><a name="p13481446322"></a><a name="p13481446322"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row17424182117250"><td class="cellrowborder" valign="top" width="47.02%" headers="mcps1.1.3.1.1 "><p id="p1142414215251"><a name="p1142414215251"></a><a name="p1142414215251"></a><a href="latlng.md">LatLng</a></p>
</td>
<td class="cellrowborder" valign="top" width="52.980000000000004%" headers="mcps1.1.3.1.2 "><p id="p1842442182511"><a name="p1842442182511"></a><a name="p1842442182511"></a>覆盖物的经纬度。</p>
</td>
</tr>
</tbody>
</table>

## getTransparency<a name="section0265153112343"></a>

<a name="table718402113253"></a>
<table><thead align="left"><tr id="row7424182172519"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p342410211251"><a name="p342410211251"></a><a name="p342410211251"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row842402192516"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p14424182192514"><a name="p14424182192514"></a><a name="p14424182192514"></a>public float getTransparency()</p>
<p id="p82010550344"><a name="p82010550344"></a><a name="p82010550344"></a>您调用此API可以获取覆盖物的透明度。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table018512218257"></a>
<table><thead align="left"><tr id="row124250212259"><th class="cellrowborder" valign="top" width="47.02%" id="mcps1.1.3.1.1"><p id="p18389653210"><a name="p18389653210"></a><a name="p18389653210"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="52.980000000000004%" id="mcps1.1.3.1.2"><p id="p1283819611328"><a name="p1283819611328"></a><a name="p1283819611328"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row13425142118257"><td class="cellrowborder" valign="top" width="47.02%" headers="mcps1.1.3.1.1 "><p id="p6425152120258"><a name="p6425152120258"></a><a name="p6425152120258"></a>float</p>
</td>
<td class="cellrowborder" valign="top" width="52.980000000000004%" headers="mcps1.1.3.1.2 "><p id="p542510214256"><a name="p542510214256"></a><a name="p542510214256"></a>覆盖物的透明度，取值范围：[0, 1]，0为不透明，1为全透明。</p>
</td>
</tr>
</tbody>
</table>

## getWidth<a name="section7391091354"></a>

<a name="table618632115254"></a>
<table><thead align="left"><tr id="row11425221102510"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p1442552172520"><a name="p1442552172520"></a><a name="p1442552172520"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row12425142122515"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p1242512217259"><a name="p1242512217259"></a><a name="p1242512217259"></a>public float getWidth()</p>
<p id="p0425821202513"><a name="p0425821202513"></a><a name="p0425821202513"></a>您调用此API可以获取覆盖物的宽度。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table15188102182514"></a>
<table><thead align="left"><tr id="row2425112119258"><th class="cellrowborder" valign="top" width="47.02%" id="mcps1.1.3.1.1"><p id="p10339101017323"><a name="p10339101017323"></a><a name="p10339101017323"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="52.980000000000004%" id="mcps1.1.3.1.2"><p id="p1633931073219"><a name="p1633931073219"></a><a name="p1633931073219"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row942515215256"><td class="cellrowborder" valign="top" width="47.02%" headers="mcps1.1.3.1.1 "><p id="p16425192113257"><a name="p16425192113257"></a><a name="p16425192113257"></a>float</p>
</td>
<td class="cellrowborder" valign="top" width="52.980000000000004%" headers="mcps1.1.3.1.2 "><p id="p144251521102511"><a name="p144251521102511"></a><a name="p144251521102511"></a>覆盖物的宽度。</p>
</td>
</tr>
</tbody>
</table>

## getZIndex<a name="section19884132218368"></a>

<a name="table181891121112519"></a>
<table><thead align="left"><tr id="row6425621202518"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p8425421112519"><a name="p8425421112519"></a><a name="p8425421112519"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row842619211251"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p642610212252"><a name="p642610212252"></a><a name="p642610212252"></a>public float getZIndex()</p>
<p id="p44268211255"><a name="p44268211255"></a><a name="p44268211255"></a>您调用此API可以获取覆盖物的z指数。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table121911621122517"></a>
<table><thead align="left"><tr id="row164264216252"><th class="cellrowborder" valign="top" width="47.02%" id="mcps1.1.3.1.1"><p id="p9773111383216"><a name="p9773111383216"></a><a name="p9773111383216"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="52.980000000000004%" id="mcps1.1.3.1.2"><p id="p47744138325"><a name="p47744138325"></a><a name="p47744138325"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row1742672110258"><td class="cellrowborder" valign="top" width="47.02%" headers="mcps1.1.3.1.1 "><p id="p8426182117252"><a name="p8426182117252"></a><a name="p8426182117252"></a>float</p>
</td>
<td class="cellrowborder" valign="top" width="52.980000000000004%" headers="mcps1.1.3.1.2 "><p id="p16426621162517"><a name="p16426621162517"></a><a name="p16426621162517"></a>z指数，即覆盖物的叠加顺序。</p>
</td>
</tr>
</tbody>
</table>

## image<a name="section19876145116369"></a>

<a name="table319292120256"></a>
<table><thead align="left"><tr id="row19426112115251"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p2042662122510"><a name="p2042662122510"></a><a name="p2042662122510"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row144261421142518"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p14261121132516"><a name="p14261121132516"></a><a name="p14261121132516"></a>public <a href="groundoverlayoptions.md">GroundOverlayOptions</a> image(<a href="bitmapdescriptor.md">BitmapDescriptor</a> imageDescriptor)</p>
<p id="p1242642116252"><a name="p1242642116252"></a><a name="p1242642116252"></a>您调用此API可以设置覆盖物的图片信息。</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table18229897123"></a>
<table><thead align="left"><tr id="row142292097120"><th class="cellrowborder" valign="top" width="47.02%" id="mcps1.1.3.1.1"><p id="p72298918125"><a name="p72298918125"></a><a name="p72298918125"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="52.980000000000004%" id="mcps1.1.3.1.2"><p id="p10229179191210"><a name="p10229179191210"></a><a name="p10229179191210"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row222919181219"><td class="cellrowborder" valign="top" width="47.02%" headers="mcps1.1.3.1.1 "><p id="p192292991214"><a name="p192292991214"></a><a name="p192292991214"></a>imageDescriptor</p>
</td>
<td class="cellrowborder" valign="top" width="52.980000000000004%" headers="mcps1.1.3.1.2 "><p id="p16229196129"><a name="p16229196129"></a><a name="p16229196129"></a>图片对象。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table01931621122519"></a>
<table><thead align="left"><tr id="row44261921142512"><th class="cellrowborder" valign="top" width="47.02%" id="mcps1.1.3.1.1"><p id="p3875319123217"><a name="p3875319123217"></a><a name="p3875319123217"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="52.980000000000004%" id="mcps1.1.3.1.2"><p id="p787531911322"><a name="p787531911322"></a><a name="p787531911322"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row104261621162510"><td class="cellrowborder" valign="top" width="47.02%" headers="mcps1.1.3.1.1 "><p id="p1742612114253"><a name="p1742612114253"></a><a name="p1742612114253"></a>GroundOverlayOptions</p>
</td>
<td class="cellrowborder" valign="top" width="52.980000000000004%" headers="mcps1.1.3.1.2 "><p id="p19427121182516"><a name="p19427121182516"></a><a name="p19427121182516"></a>设置新的图片信息后的<a href="groundoverlayoptions.md">GroundOverlayOptions</a>对象。</p>
</td>
</tr>
</tbody>
</table>

## isClickable<a name="section1559761915375"></a>

<a name="table5194152112516"></a>
<table><thead align="left"><tr id="row7428122112511"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p1842822112518"><a name="p1842822112518"></a><a name="p1842822112518"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row3428921172515"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p442812116250"><a name="p442812116250"></a><a name="p442812116250"></a>public boolean isClickable()</p>
<p id="p1542872118256"><a name="p1542872118256"></a><a name="p1542872118256"></a>您调用此API可以获取覆盖物的可点击性。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table61965212252"></a>
<table><thead align="left"><tr id="row14428132172517"><th class="cellrowborder" valign="top" width="47.02%" id="mcps1.1.3.1.1"><p id="p2068592219327"><a name="p2068592219327"></a><a name="p2068592219327"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="52.980000000000004%" id="mcps1.1.3.1.2"><p id="p968592217325"><a name="p968592217325"></a><a name="p968592217325"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row74287217255"><td class="cellrowborder" valign="top" width="47.02%" headers="mcps1.1.3.1.1 "><p id="p64281621182514"><a name="p64281621182514"></a><a name="p64281621182514"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="52.980000000000004%" headers="mcps1.1.3.1.2 "><p id="p1042862122514"><a name="p1042862122514"></a><a name="p1042862122514"></a>覆盖物的可点击性，true为可点击，false为不可点击。</p>
</td>
</tr>
</tbody>
</table>

## isVisible<a name="section183891514193816"></a>

<a name="table5197421112513"></a>
<table><thead align="left"><tr id="row14282021182519"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p204291221162513"><a name="p204291221162513"></a><a name="p204291221162513"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row4429192122510"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p164291621132510"><a name="p164291621132510"></a><a name="p164291621132510"></a>public boolean isVisible()</p>
<p id="p1442982182516"><a name="p1442982182516"></a><a name="p1442982182516"></a>您调用此API可以获取覆盖物的可见性。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table201989218258"></a>
<table><thead align="left"><tr id="row1442912192518"><th class="cellrowborder" valign="top" width="47.02%" id="mcps1.1.3.1.1"><p id="p116756250322"><a name="p116756250322"></a><a name="p116756250322"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="52.980000000000004%" id="mcps1.1.3.1.2"><p id="p196758251328"><a name="p196758251328"></a><a name="p196758251328"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row16429821132519"><td class="cellrowborder" valign="top" width="47.02%" headers="mcps1.1.3.1.1 "><p id="p9429182120257"><a name="p9429182120257"></a><a name="p9429182120257"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="52.980000000000004%" headers="mcps1.1.3.1.2 "><p id="p542914212259"><a name="p542914212259"></a><a name="p542914212259"></a>覆盖物的可见性，true为可见，false为不可见。</p>
</td>
</tr>
</tbody>
</table>

## position\(LatLng location, float width\)<a name="section18441164103913"></a>

<a name="table819912116254"></a>
<table><thead align="left"><tr id="row12429421122515"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p18429621192510"><a name="p18429621192510"></a><a name="p18429621192510"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row18429321142514"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p842942111257"><a name="p842942111257"></a><a name="p842942111257"></a>public <a href="groundoverlayoptions.md">GroundOverlayOptions</a> position(<a href="latlng.md">LatLng</a> location, float width)</p>
<p id="p154291821162520"><a name="p154291821162520"></a><a name="p154291821162520"></a>根据位置和宽设置覆盖物。在显示时，图片高度根据图片的比例自动匹配。</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table1920022115254"></a>
<table><thead align="left"><tr id="row64298215253"><th class="cellrowborder" valign="top" width="47.02%" id="mcps1.1.3.1.1"><p id="p18376253122814"><a name="p18376253122814"></a><a name="p18376253122814"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="52.980000000000004%" id="mcps1.1.3.1.2"><p id="p103762535281"><a name="p103762535281"></a><a name="p103762535281"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row1242916211250"><td class="cellrowborder" valign="top" width="47.02%" headers="mcps1.1.3.1.1 "><p id="p742972119259"><a name="p742972119259"></a><a name="p742972119259"></a>location</p>
</td>
<td class="cellrowborder" valign="top" width="52.980000000000004%" headers="mcps1.1.3.1.2 "><p id="p16430122115254"><a name="p16430122115254"></a><a name="p16430122115254"></a>锚点的位置。默认情况下，锚点在距离图像顶部和图像左侧一半的位置。</p>
</td>
</tr>
<tr id="row11430182142515"><td class="cellrowborder" valign="top" width="47.02%" headers="mcps1.1.3.1.1 "><p id="p1743022115255"><a name="p1743022115255"></a><a name="p1743022115255"></a>width</p>
</td>
<td class="cellrowborder" valign="top" width="52.980000000000004%" headers="mcps1.1.3.1.2 "><p id="p94301421192518"><a name="p94301421192518"></a><a name="p94301421192518"></a>覆盖物的宽，单位：米。</p>
</td>
</tr>
</tbody>
</table>

**Throws**

<a name="table16203142115255"></a>
<table><thead align="left"><tr id="row18430721142511"><th class="cellrowborder" valign="top" width="47.02%" id="mcps1.1.3.1.1"><p id="p1430152118251"><a name="p1430152118251"></a><a name="p1430152118251"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="52.980000000000004%" id="mcps1.1.3.1.2"><p id="p143012218255"><a name="p143012218255"></a><a name="p143012218255"></a><span>Description</span></p>
</th>
</tr>
</thead>
<tbody><tr id="row7430321102514"><td class="cellrowborder" valign="top" width="47.02%" headers="mcps1.1.3.1.1 "><p id="p743017211250"><a name="p743017211250"></a><a name="p743017211250"></a>IllegalArgumentException</p>
</td>
<td class="cellrowborder" valign="top" width="52.980000000000004%" headers="mcps1.1.3.1.2 "><p id="p17430121122515"><a name="p17430121122515"></a><a name="p17430121122515"></a>锚点的位置为空或者传入的width为负数时，抛出异常。</p>
</td>
</tr>
<tr id="row2430121142520"><td class="cellrowborder" valign="top" width="47.02%" headers="mcps1.1.3.1.1 "><p id="p94301213257"><a name="p94301213257"></a><a name="p94301213257"></a>IllegalStateException</p>
</td>
<td class="cellrowborder" valign="top" width="52.980000000000004%" headers="mcps1.1.3.1.2 "><p id="p164301221202514"><a name="p164301221202514"></a><a name="p164301221202514"></a>如果已使用<a href="#section1971542716405">positionFromBounds</a>(<a href="latlngbounds.md">LatLngBounds</a>)设置了位置，抛出异常。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table182021721202514"></a>
<table><thead align="left"><tr id="row843092132514"><th class="cellrowborder" valign="top" width="47.02%" id="mcps1.1.3.1.1"><p id="p199081327183213"><a name="p199081327183213"></a><a name="p199081327183213"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="52.980000000000004%" id="mcps1.1.3.1.2"><p id="p190852718323"><a name="p190852718323"></a><a name="p190852718323"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row11430182118252"><td class="cellrowborder" valign="top" width="47.02%" headers="mcps1.1.3.1.1 "><p id="p18430122119258"><a name="p18430122119258"></a><a name="p18430122119258"></a>GroundOverlayOptions</p>
</td>
<td class="cellrowborder" valign="top" width="52.980000000000004%" headers="mcps1.1.3.1.2 "><p id="p043013215250"><a name="p043013215250"></a><a name="p043013215250"></a>设置新的位置和宽度后的<a href="groundoverlayoptions.md">GroundOverlayOptions</a>对象。</p>
</td>
</tr>
</tbody>
</table>

## position\(LatLng location, float width, float height\)<a name="section1263995883915"></a>

<a name="table17205321102514"></a>
<table><thead align="left"><tr id="row443062113250"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p1543002114252"><a name="p1543002114252"></a><a name="p1543002114252"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row1743162192519"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p20431421192510"><a name="p20431421192510"></a><a name="p20431421192510"></a>public <a href="groundoverlayoptions.md">GroundOverlayOptions</a> position(<a href="latlng.md">LatLng</a> location, float width, float height)</p>
<p id="p15431921122517"><a name="p15431921122517"></a><a name="p15431921122517"></a>根据位置和宽高设置覆盖物。在显示时，图片会被缩放来适应指定的尺寸。</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table162061821132510"></a>
<table><thead align="left"><tr id="row94312021132514"><th class="cellrowborder" valign="top" width="47.02%" id="mcps1.1.3.1.1"><p id="p162004117307"><a name="p162004117307"></a><a name="p162004117307"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="52.980000000000004%" id="mcps1.1.3.1.2"><p id="p1120017112307"><a name="p1120017112307"></a><a name="p1120017112307"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row1343212120252"><td class="cellrowborder" valign="top" width="47.02%" headers="mcps1.1.3.1.1 "><p id="p1543232118250"><a name="p1543232118250"></a><a name="p1543232118250"></a>location</p>
</td>
<td class="cellrowborder" valign="top" width="52.980000000000004%" headers="mcps1.1.3.1.2 "><p id="p543211219252"><a name="p543211219252"></a><a name="p543211219252"></a>锚点的位置。默认情况下，锚点在距离图像顶部和图像左侧一半的位置。</p>
</td>
</tr>
<tr id="row12432162172514"><td class="cellrowborder" valign="top" width="47.02%" headers="mcps1.1.3.1.1 "><p id="p204323215259"><a name="p204323215259"></a><a name="p204323215259"></a>width</p>
</td>
<td class="cellrowborder" valign="top" width="52.980000000000004%" headers="mcps1.1.3.1.2 "><p id="p043210216257"><a name="p043210216257"></a><a name="p043210216257"></a>覆盖物的宽，单位：米。</p>
</td>
</tr>
<tr id="row114321821162510"><td class="cellrowborder" valign="top" width="47.02%" headers="mcps1.1.3.1.1 "><p id="p443252112250"><a name="p443252112250"></a><a name="p443252112250"></a>height</p>
</td>
<td class="cellrowborder" valign="top" width="52.980000000000004%" headers="mcps1.1.3.1.2 "><p id="p7432142102518"><a name="p7432142102518"></a><a name="p7432142102518"></a>覆盖物的高，单位：米。</p>
</td>
</tr>
</tbody>
</table>

**Throws**

<a name="table8210921102510"></a>
<table><thead align="left"><tr id="row114332021122512"><th class="cellrowborder" valign="top" width="47.02%" id="mcps1.1.3.1.1"><p id="p20433921182512"><a name="p20433921182512"></a><a name="p20433921182512"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="52.980000000000004%" id="mcps1.1.3.1.2"><p id="p204331621132518"><a name="p204331621132518"></a><a name="p204331621132518"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row18433162116252"><td class="cellrowborder" valign="top" width="47.02%" headers="mcps1.1.3.1.1 "><p id="p1433142112251"><a name="p1433142112251"></a><a name="p1433142112251"></a>IllegalArgumentException</p>
</td>
<td class="cellrowborder" valign="top" width="52.980000000000004%" headers="mcps1.1.3.1.2 "><p id="p20433132116258"><a name="p20433132116258"></a><a name="p20433132116258"></a>锚点的位置为空或者传入的width/height为负数时，抛出异常。</p>
</td>
</tr>
<tr id="row10433142142516"><td class="cellrowborder" valign="top" width="47.02%" headers="mcps1.1.3.1.1 "><p id="p943352162516"><a name="p943352162516"></a><a name="p943352162516"></a>IllegalStateException</p>
</td>
<td class="cellrowborder" valign="top" width="52.980000000000004%" headers="mcps1.1.3.1.2 "><p id="p7433132119255"><a name="p7433132119255"></a><a name="p7433132119255"></a>如果已使用<a href="#section1971542716405">positionFromBounds</a>(<a href="latlngbounds.md">LatLngBounds</a>)设置了位置，抛出异常。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table220842119250"></a>
<table><thead align="left"><tr id="row19432121152516"><th class="cellrowborder" valign="top" width="47.02%" id="mcps1.1.3.1.1"><p id="p12735143073219"><a name="p12735143073219"></a><a name="p12735143073219"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="52.980000000000004%" id="mcps1.1.3.1.2"><p id="p67354304322"><a name="p67354304322"></a><a name="p67354304322"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row543215212258"><td class="cellrowborder" valign="top" width="47.02%" headers="mcps1.1.3.1.1 "><p id="p18432142162511"><a name="p18432142162511"></a><a name="p18432142162511"></a>GroundOverlayOptions</p>
</td>
<td class="cellrowborder" valign="top" width="52.980000000000004%" headers="mcps1.1.3.1.2 "><p id="p1843242162518"><a name="p1843242162518"></a><a name="p1843242162518"></a>设置新的位置和宽高后的<a href="groundoverlayoptions.md">GroundOverlayOptions</a>对象。</p>
</td>
</tr>
</tbody>
</table>

## positionFromBounds<a name="section1971542716405"></a>

<a name="table82129218255"></a>
<table><thead align="left"><tr id="row743342110255"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p114332217251"><a name="p114332217251"></a><a name="p114332217251"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row16433102162517"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p17433921142510"><a name="p17433921142510"></a><a name="p17433921142510"></a>public <a href="groundoverlayoptions.md">GroundOverlayOptions</a> positionFromBounds(<a href="latlngbounds.md">LatLngBounds</a> bounds)</p>
<p id="p643312132515"><a name="p643312132515"></a><a name="p643312132515"></a>您调用此API可以根据矩形区域设置覆盖物的位置。</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table10213132115259"></a>
<table><thead align="left"><tr id="row10433121172512"><th class="cellrowborder" valign="top" width="47.02%" id="mcps1.1.3.1.1"><p id="p8649129192913"><a name="p8649129192913"></a><a name="p8649129192913"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="52.980000000000004%" id="mcps1.1.3.1.2"><p id="p10649112916299"><a name="p10649112916299"></a><a name="p10649112916299"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row18433162112515"><td class="cellrowborder" valign="top" width="47.02%" headers="mcps1.1.3.1.1 "><p id="p343422116254"><a name="p343422116254"></a><a name="p343422116254"></a>bounds</p>
</td>
<td class="cellrowborder" valign="top" width="52.980000000000004%" headers="mcps1.1.3.1.2 "><p id="p1434121202519"><a name="p1434121202519"></a><a name="p1434121202519"></a>矩形区域。</p>
</td>
</tr>
</tbody>
</table>

**Throws**

<a name="table192151521122512"></a>
<table><thead align="left"><tr id="row1434152192516"><th class="cellrowborder" valign="top" width="47.02%" id="mcps1.1.3.1.1"><p id="p043417217259"><a name="p043417217259"></a><a name="p043417217259"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="52.980000000000004%" id="mcps1.1.3.1.2"><p id="p18434142192512"><a name="p18434142192512"></a><a name="p18434142192512"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row14434142182510"><td class="cellrowborder" valign="top" width="47.02%" headers="mcps1.1.3.1.1 "><p id="p1543452172510"><a name="p1543452172510"></a><a name="p1543452172510"></a>IllegalStateException</p>
</td>
<td class="cellrowborder" valign="top" width="52.980000000000004%" headers="mcps1.1.3.1.2 "><p id="p114341221102515"><a name="p114341221102515"></a><a name="p114341221102515"></a>如果已使用<a href="#section18441164103913">position</a>(<a href="latlng.md">LatLng</a>, float)或者<a href="#section1263995883915">position</a>(<a href="latlng.md">LatLng</a>, float, float)设置了位置，抛出异常。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table13214192114259"></a>
<table><thead align="left"><tr id="row15434112162510"><th class="cellrowborder" valign="top" width="47.02%" id="mcps1.1.3.1.1"><p id="p15246733153210"><a name="p15246733153210"></a><a name="p15246733153210"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="52.980000000000004%" id="mcps1.1.3.1.2"><p id="p624612333322"><a name="p624612333322"></a><a name="p624612333322"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row343420215259"><td class="cellrowborder" valign="top" width="47.02%" headers="mcps1.1.3.1.1 "><p id="p843416212259"><a name="p843416212259"></a><a name="p843416212259"></a>GroundOverlayOptions</p>
</td>
<td class="cellrowborder" valign="top" width="52.980000000000004%" headers="mcps1.1.3.1.2 "><p id="p1443422116258"><a name="p1443422116258"></a><a name="p1443422116258"></a>设置新的矩形区域位置后的<a href="groundoverlayoptions.md">GroundOverlayOptions</a>对象。</p>
</td>
</tr>
</tbody>
</table>

## transparency<a name="section146372104217"></a>

<a name="table5217162114254"></a>
<table><thead align="left"><tr id="row64341021152520"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p14341721142515"><a name="p14341721142515"></a><a name="p14341721142515"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row4434321182514"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p15434121172514"><a name="p15434121172514"></a><a name="p15434121172514"></a>public <a href="groundoverlayoptions.md">GroundOverlayOptions</a> transparency(float transparency)</p>
<p id="p1911721344218"><a name="p1911721344218"></a><a name="p1911721344218"></a>设置覆盖物的透明度，取值范围：[0, 1]，0为不透明，1为全透明。</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table6218112112510"></a>
<table><thead align="left"><tr id="row13434102114254"><th class="cellrowborder" valign="top" width="47.02%" id="mcps1.1.3.1.1"><p id="p66797360295"><a name="p66797360295"></a><a name="p66797360295"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="52.980000000000004%" id="mcps1.1.3.1.2"><p id="p15679203614291"><a name="p15679203614291"></a><a name="p15679203614291"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row1543582115252"><td class="cellrowborder" valign="top" width="47.02%" headers="mcps1.1.3.1.1 "><p id="p243562115251"><a name="p243562115251"></a><a name="p243562115251"></a>transparency</p>
</td>
<td class="cellrowborder" valign="top" width="52.980000000000004%" headers="mcps1.1.3.1.2 "><p id="p44351214252"><a name="p44351214252"></a><a name="p44351214252"></a>覆盖物的透明度，默认值为0。</p>
</td>
</tr>
</tbody>
</table>

**Throws**

<a name="table77591127154018"></a>
<table><thead align="left"><tr id="row167591827164013"><th class="cellrowborder" valign="top" width="47.02%" id="mcps1.1.3.1.1"><p id="p775912714404"><a name="p775912714404"></a><a name="p775912714404"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="52.980000000000004%" id="mcps1.1.3.1.2"><p id="p075942774010"><a name="p075942774010"></a><a name="p075942774010"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row12760327154011"><td class="cellrowborder" valign="top" width="47.02%" headers="mcps1.1.3.1.1 "><p id="p7760172715408"><a name="p7760172715408"></a><a name="p7760172715408"></a>IllegalArgumentException</p>
</td>
<td class="cellrowborder" valign="top" width="52.980000000000004%" headers="mcps1.1.3.1.2 "><p id="p18760227164010"><a name="p18760227164010"></a><a name="p18760227164010"></a>透明度范围超过[0, 1]抛出异常。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table1722014213256"></a>
<table><thead align="left"><tr id="row104353210256"><th class="cellrowborder" valign="top" width="47.02%" id="mcps1.1.3.1.1"><p id="p182193683213"><a name="p182193683213"></a><a name="p182193683213"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="52.980000000000004%" id="mcps1.1.3.1.2"><p id="p17233616325"><a name="p17233616325"></a><a name="p17233616325"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row114355217250"><td class="cellrowborder" valign="top" width="47.02%" headers="mcps1.1.3.1.1 "><p id="p1843518215255"><a name="p1843518215255"></a><a name="p1843518215255"></a>GroundOverlayOptions</p>
</td>
<td class="cellrowborder" valign="top" width="52.980000000000004%" headers="mcps1.1.3.1.2 "><p id="p04351521122514"><a name="p04351521122514"></a><a name="p04351521122514"></a>设置新的透明度后的<a href="groundoverlayoptions.md">GroundOverlayOptions</a>对象。</p>
</td>
</tr>
</tbody>
</table>

## visible<a name="section1986154284211"></a>

<a name="table162211021102514"></a>
<table><thead align="left"><tr id="row20435421172514"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p6435102117252"><a name="p6435102117252"></a><a name="p6435102117252"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row104357216255"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p2435152118251"><a name="p2435152118251"></a><a name="p2435152118251"></a>public <a href="groundoverlayoptions.md">GroundOverlayOptions</a> visible(boolean visible)</p>
<p id="p84351221192510"><a name="p84351221192510"></a><a name="p84351221192510"></a>您调用此API可以设置覆盖物的可见性，如果覆盖物不可见，则不会绘制，其他所有状态均保留。</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table182221821112513"></a>
<table><thead align="left"><tr id="row194358212257"><th class="cellrowborder" valign="top" width="47.02%" id="mcps1.1.3.1.1"><p id="p4373174422912"><a name="p4373174422912"></a><a name="p4373174422912"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="52.980000000000004%" id="mcps1.1.3.1.2"><p id="p133731244172914"><a name="p133731244172914"></a><a name="p133731244172914"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row15435102117258"><td class="cellrowborder" valign="top" width="47.02%" headers="mcps1.1.3.1.1 "><p id="p3436112111258"><a name="p3436112111258"></a><a name="p3436112111258"></a>visible</p>
</td>
<td class="cellrowborder" valign="top" width="52.980000000000004%" headers="mcps1.1.3.1.2 "><p id="p12436162112253"><a name="p12436162112253"></a><a name="p12436162112253"></a>覆盖物的可见性<span>，</span>默认为可见。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table1422410218254"></a>
<table><thead align="left"><tr id="row15436202102520"><th class="cellrowborder" valign="top" width="47.02%" id="mcps1.1.3.1.1"><p id="p1161353863216"><a name="p1161353863216"></a><a name="p1161353863216"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="52.980000000000004%" id="mcps1.1.3.1.2"><p id="p361323873215"><a name="p361323873215"></a><a name="p361323873215"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row15436162120254"><td class="cellrowborder" valign="top" width="47.02%" headers="mcps1.1.3.1.1 "><p id="p114364211254"><a name="p114364211254"></a><a name="p114364211254"></a>GroundOverlayOptions</p>
</td>
<td class="cellrowborder" valign="top" width="52.980000000000004%" headers="mcps1.1.3.1.2 "><p id="p443652111257"><a name="p443652111257"></a><a name="p443652111257"></a>设置新的可见性后的<a href="groundoverlayoptions.md">GroundOverlayOptions</a>对象。</p>
</td>
</tr>
</tbody>
</table>

## zIndex<a name="section109261034311"></a>

<a name="table112254215259"></a>
<table><thead align="left"><tr id="row5436521192511"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p184363214252"><a name="p184363214252"></a><a name="p184363214252"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row1743620216253"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p943682152513"><a name="p943682152513"></a><a name="p943682152513"></a>public <a href="groundoverlayoptions.md">GroundOverlayOptions</a> zIndex(float zIndex)</p>
<p id="p3436162118251"><a name="p3436162118251"></a><a name="p3436162118251"></a>用于设置覆盖物的z指数。z指数指的是覆盖物的叠加顺序，具有较大z指数的覆盖物会绘制在具有较小z指数的覆盖物上，具有相同z指数的叠加顺序为元素添加的先后顺序。</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table1022762113250"></a>
<table><thead align="left"><tr id="row64362021172515"><th class="cellrowborder" valign="top" width="47.02%" id="mcps1.1.3.1.1"><p id="p54721649122920"><a name="p54721649122920"></a><a name="p54721649122920"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="52.980000000000004%" id="mcps1.1.3.1.2"><p id="p747244915297"><a name="p747244915297"></a><a name="p747244915297"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row164361121172515"><td class="cellrowborder" valign="top" width="47.02%" headers="mcps1.1.3.1.1 "><p id="p12436202142514"><a name="p12436202142514"></a><a name="p12436202142514"></a>zIndex</p>
</td>
<td class="cellrowborder" valign="top" width="52.980000000000004%" headers="mcps1.1.3.1.2 "><p id="p843652132513"><a name="p843652132513"></a><a name="p843652132513"></a>z指数，即覆盖物的叠加顺序。默认的z指数是0。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table9228122182510"></a>
<table><thead align="left"><tr id="row1143722132514"><th class="cellrowborder" valign="top" width="47.05%" id="mcps1.1.3.1.1"><p id="p3550142163214"><a name="p3550142163214"></a><a name="p3550142163214"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="52.949999999999996%" id="mcps1.1.3.1.2"><p id="p10550204218326"><a name="p10550204218326"></a><a name="p10550204218326"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row7437021152515"><td class="cellrowborder" valign="top" width="47.05%" headers="mcps1.1.3.1.1 "><p id="p154371021152513"><a name="p154371021152513"></a><a name="p154371021152513"></a>GroundOverlayOptions</p>
</td>
<td class="cellrowborder" valign="top" width="52.949999999999996%" headers="mcps1.1.3.1.2 "><p id="p943722117252"><a name="p943722117252"></a><a name="p943722117252"></a>设置新的z指数后的<a href="groundoverlayoptions.md">GroundOverlayOptions</a>对象。</p>
</td>
</tr>
</tbody>
</table>

