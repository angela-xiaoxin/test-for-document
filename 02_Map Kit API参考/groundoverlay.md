# GroundOverlay<a name="ZH-CN_TOPIC_0000001145780995"></a>

-   [Public Method Summary](#section41831615985)
-   [Public Methods](#section11583621172616)
-   [equals](#section1631196204012)
-   [getBearing](#section47162554391)
-   [getBounds](#section1437364753911)
-   [getHeight](#section1786016343394)
-   [getId](#section5514162863912)
-   [getPosition](#section1422515195398)
-   [getTag](#section182571159123818)
-   [getTransparency](#section176028810392)
-   [getWidth](#section10294105218386)
-   [getZIndex](#section1132764615389)
-   [hashCode](#section10415133293811)
-   [isClickable](#section4812182453810)
-   [isVisible](#section1931111673818)
-   [remove](#section137601858123719)
-   [setBearing](#section1239854733712)
-   [setClickable](#section45409352378)
-   [setDimensions\(float width, float height\)](#section6919112773713)
-   [setDimensions\(float width\)](#section0141102153714)
-   [setImage](#section1281711313376)
-   [setPosition](#section141766412377)
-   [setPositionFromBounds](#section977685511362)
-   [setTag](#section85441446203618)
-   [setTransparency](#section497274010365)
-   [setVisible](#section312643417368)
-   [setZIndex](#section61641226133617)


<a name="table11740mcpsimp"></a>
<table><thead align="left"><tr id="row11744mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p11746mcpsimp"><a name="p11746mcpsimp"></a><a name="p11746mcpsimp"></a>Class Info</p>
</th>
</tr>
</thead>
<tbody><tr id="row11747mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p15912948153911"><a name="p15912948153911"></a><a name="p15912948153911"></a>public final class GroundOverlay</p>
<p id="p11749mcpsimp"><a name="p11749mcpsimp"></a><a name="p11749mcpsimp"></a>叠加在地图上的图像类，在调用<a href="huaweimap.md">HuaweiMap</a>类的<a href="huaweimap.md#section374112486409">addGroundOverlay</a>方法时会返回该类型的实例。</p>
</td>
</tr>
</tbody>
</table>

## Public Method Summary<a name="section41831615985"></a>

<a name="table11755mcpsimp"></a>
<table><thead align="left"><tr id="row11760mcpsimp"><th class="cellrowborder" valign="top" width="40%" id="mcps1.1.3.1.1"><p id="p081120285386"><a name="p081120285386"></a><a name="p081120285386"></a>Qualifier and Type</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.1.3.1.2"><p id="p681112883813"><a name="p681112883813"></a><a name="p681112883813"></a>Method Name and Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row11765mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p11767mcpsimp"><a name="p11767mcpsimp"></a><a name="p11767mcpsimp"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p11769mcpsimp"><a name="p11769mcpsimp"></a><a name="p11769mcpsimp"></a><a href="#section1631196204012">equals</a>(Object other)</p>
<p id="p1374464764613"><a name="p1374464764613"></a><a name="p1374464764613"></a>判断两个覆盖物对象是否相等。</p>
</td>
</tr>
<tr id="row11770mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p11772mcpsimp"><a name="p11772mcpsimp"></a><a name="p11772mcpsimp"></a>float</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p11774mcpsimp"><a name="p11774mcpsimp"></a><a name="p11774mcpsimp"></a><a href="#section47162554391">getBearing</a>()</p>
<p id="p49174483462"><a name="p49174483462"></a><a name="p49174483462"></a>获取覆盖物的角度。</p>
</td>
</tr>
<tr id="row11775mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p11777mcpsimp"><a name="p11777mcpsimp"></a><a name="p11777mcpsimp"></a><a href="latlngbounds.md">LatLngBounds</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p11779mcpsimp"><a name="p11779mcpsimp"></a><a name="p11779mcpsimp"></a><a href="#section1437364753911">getBounds</a>()</p>
<p id="p186015495462"><a name="p186015495462"></a><a name="p186015495462"></a>获取覆盖物的矩形区域。</p>
</td>
</tr>
<tr id="row11780mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p11782mcpsimp"><a name="p11782mcpsimp"></a><a name="p11782mcpsimp"></a>float</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p11784mcpsimp"><a name="p11784mcpsimp"></a><a name="p11784mcpsimp"></a><a href="#section1786016343394">getHeight</a>()</p>
<p id="p284555094611"><a name="p284555094611"></a><a name="p284555094611"></a>获取覆盖物的高。</p>
</td>
</tr>
<tr id="row11785mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p11787mcpsimp"><a name="p11787mcpsimp"></a><a name="p11787mcpsimp"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p11789mcpsimp"><a name="p11789mcpsimp"></a><a name="p11789mcpsimp"></a><a href="#section5514162863912">getId</a>()</p>
<p id="p9181952144615"><a name="p9181952144615"></a><a name="p9181952144615"></a>获取覆盖物的ID属性。</p>
</td>
</tr>
<tr id="row11790mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p11792mcpsimp"><a name="p11792mcpsimp"></a><a name="p11792mcpsimp"></a><a href="latlng.md">LatLng</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p11794mcpsimp"><a name="p11794mcpsimp"></a><a name="p11794mcpsimp"></a><a href="#section1422515195398">getPosition</a>()</p>
<p id="p177481253144612"><a name="p177481253144612"></a><a name="p177481253144612"></a>获取覆盖物的位置信息。</p>
</td>
</tr>
<tr id="row11795mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p11797mcpsimp"><a name="p11797mcpsimp"></a><a name="p11797mcpsimp"></a>Object</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p11799mcpsimp"><a name="p11799mcpsimp"></a><a name="p11799mcpsimp"></a><a href="#section182571159123818">getTag</a>()</p>
<p id="p3845185413465"><a name="p3845185413465"></a><a name="p3845185413465"></a>获取tag属性。</p>
</td>
</tr>
<tr id="row11800mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p11802mcpsimp"><a name="p11802mcpsimp"></a><a name="p11802mcpsimp"></a>float</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p11804mcpsimp"><a name="p11804mcpsimp"></a><a name="p11804mcpsimp"></a><a href="#section176028810392">getTransparency</a>()</p>
<p id="p124210563464"><a name="p124210563464"></a><a name="p124210563464"></a>获取覆盖物的透明度。</p>
</td>
</tr>
<tr id="row11805mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p11807mcpsimp"><a name="p11807mcpsimp"></a><a name="p11807mcpsimp"></a>float</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p11809mcpsimp"><a name="p11809mcpsimp"></a><a name="p11809mcpsimp"></a><a href="#section10294105218386">getWidth</a>()</p>
<p id="p17939185674611"><a name="p17939185674611"></a><a name="p17939185674611"></a>获取覆盖物的宽度。</p>
</td>
</tr>
<tr id="row11810mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p11812mcpsimp"><a name="p11812mcpsimp"></a><a name="p11812mcpsimp"></a>float</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p11814mcpsimp"><a name="p11814mcpsimp"></a><a name="p11814mcpsimp"></a><a href="#section1132764615389">getZIndex</a>()</p>
<p id="p17892125715468"><a name="p17892125715468"></a><a name="p17892125715468"></a>获取覆盖物的z指数。</p>
</td>
</tr>
<tr id="row11815mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p11817mcpsimp"><a name="p11817mcpsimp"></a><a name="p11817mcpsimp"></a>int</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p11819mcpsimp"><a name="p11819mcpsimp"></a><a name="p11819mcpsimp"></a><a href="#section10415133293811">hashCode</a>()</p>
<p id="p1970319589461"><a name="p1970319589461"></a><a name="p1970319589461"></a>获取覆盖物的哈希值。</p>
</td>
</tr>
<tr id="row11820mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p11822mcpsimp"><a name="p11822mcpsimp"></a><a name="p11822mcpsimp"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p11824mcpsimp"><a name="p11824mcpsimp"></a><a name="p11824mcpsimp"></a><a href="#section4812182453810">isClickable</a>()</p>
<p id="p3582305473"><a name="p3582305473"></a><a name="p3582305473"></a>获取覆盖物的可点击性。</p>
</td>
</tr>
<tr id="row11825mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p11827mcpsimp"><a name="p11827mcpsimp"></a><a name="p11827mcpsimp"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p11829mcpsimp"><a name="p11829mcpsimp"></a><a name="p11829mcpsimp"></a><a href="#section1931111673818">isVisible</a>()</p>
<p id="p46331211471"><a name="p46331211471"></a><a name="p46331211471"></a>获取覆盖物的可见性。</p>
</td>
</tr>
<tr id="row11830mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p11832mcpsimp"><a name="p11832mcpsimp"></a><a name="p11832mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p11834mcpsimp"><a name="p11834mcpsimp"></a><a name="p11834mcpsimp"></a><a href="#section137601858123719">remove</a>()</p>
<p id="p1544414284715"><a name="p1544414284715"></a><a name="p1544414284715"></a>将覆盖物从地图上移除。</p>
</td>
</tr>
<tr id="row11835mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p11837mcpsimp"><a name="p11837mcpsimp"></a><a name="p11837mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p11839mcpsimp"><a name="p11839mcpsimp"></a><a name="p11839mcpsimp"></a><a href="#section1239854733712">setBearing</a>(float bearing)</p>
<p id="p56324412472"><a name="p56324412472"></a><a name="p56324412472"></a>设置覆盖物从正北顺时针的角度。</p>
</td>
</tr>
<tr id="row11840mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p11842mcpsimp"><a name="p11842mcpsimp"></a><a name="p11842mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p11844mcpsimp"><a name="p11844mcpsimp"></a><a name="p11844mcpsimp"></a><a href="#section45409352378">setClickable</a>(boolean clickable)</p>
<p id="p136176534714"><a name="p136176534714"></a><a name="p136176534714"></a>设置覆盖物的可点击性。</p>
</td>
</tr>
<tr id="row11845mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p11847mcpsimp"><a name="p11847mcpsimp"></a><a name="p11847mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p11849mcpsimp"><a name="p11849mcpsimp"></a><a name="p11849mcpsimp"></a><a href="#section6919112773713">setDimensions</a>(float width, float height)</p>
<p id="p1157815614715"><a name="p1157815614715"></a><a name="p1157815614715"></a>设置覆盖物的宽高。</p>
</td>
</tr>
<tr id="row11850mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p11852mcpsimp"><a name="p11852mcpsimp"></a><a name="p11852mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p11854mcpsimp"><a name="p11854mcpsimp"></a><a name="p11854mcpsimp"></a><a href="#section0141102153714">setDimensions</a>(float width)</p>
<p id="p1058515714476"><a name="p1058515714476"></a><a name="p1058515714476"></a>设置覆盖物的宽度。</p>
</td>
</tr>
<tr id="row11855mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p11857mcpsimp"><a name="p11857mcpsimp"></a><a name="p11857mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p11859mcpsimp"><a name="p11859mcpsimp"></a><a name="p11859mcpsimp"></a><a href="#section1281711313376">setImage</a>(<a href="bitmapdescriptor.md">BitmapDescriptor</a> imageDescriptor)</p>
<p id="p1657578164718"><a name="p1657578164718"></a><a name="p1657578164718"></a>置覆盖物的图片信息，新图片会使用老图片的矩形区域。</p>
</td>
</tr>
<tr id="row11860mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p11862mcpsimp"><a name="p11862mcpsimp"></a><a name="p11862mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p11864mcpsimp"><a name="p11864mcpsimp"></a><a name="p11864mcpsimp"></a><a href="#section141766412377">setPosition</a>(<a href="latlng.md">LatLng</a> latLng)</p>
<p id="p8389161094710"><a name="p8389161094710"></a><a name="p8389161094710"></a>设置覆盖物的位置，覆盖物的其他属性不变。</p>
</td>
</tr>
<tr id="row11865mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p11867mcpsimp"><a name="p11867mcpsimp"></a><a name="p11867mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p11869mcpsimp"><a name="p11869mcpsimp"></a><a name="p11869mcpsimp"></a><a href="#section977685511362">setPositionFromBounds</a>(<a href="latlngbounds.md">LatLngBounds</a> bounds)</p>
<p id="p18406911164719"><a name="p18406911164719"></a><a name="p18406911164719"></a>根据矩形区域设置覆盖物的位置。</p>
</td>
</tr>
<tr id="row11870mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p11872mcpsimp"><a name="p11872mcpsimp"></a><a name="p11872mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p11874mcpsimp"><a name="p11874mcpsimp"></a><a name="p11874mcpsimp"></a><a href="#section85441446203618">setTag</a>(Object tag)</p>
<p id="p10420412194712"><a name="p10420412194712"></a><a name="p10420412194712"></a>设置覆盖物的tag属性。</p>
</td>
</tr>
<tr id="row11875mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p11877mcpsimp"><a name="p11877mcpsimp"></a><a name="p11877mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p11879mcpsimp"><a name="p11879mcpsimp"></a><a name="p11879mcpsimp"></a><a href="#section497274010365">setTransparency</a>(float transparency)</p>
<p id="p944771311474"><a name="p944771311474"></a><a name="p944771311474"></a>设置覆盖物的透明度。</p>
</td>
</tr>
<tr id="row11880mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p11882mcpsimp"><a name="p11882mcpsimp"></a><a name="p11882mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p11884mcpsimp"><a name="p11884mcpsimp"></a><a name="p11884mcpsimp"></a><a href="#section312643417368">setVisible</a>(boolean visible)</p>
<p id="p11619131444716"><a name="p11619131444716"></a><a name="p11619131444716"></a>设置覆盖物的可见性。</p>
</td>
</tr>
<tr id="row11885mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p11887mcpsimp"><a name="p11887mcpsimp"></a><a name="p11887mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p11889mcpsimp"><a name="p11889mcpsimp"></a><a name="p11889mcpsimp"></a><a href="#section61641226133617">setZIndex</a>(float zIndex)</p>
<p id="p13281516104714"><a name="p13281516104714"></a><a name="p13281516104714"></a>设置覆盖物的z指数。</p>
</td>
</tr>
</tbody>
</table>

## Public Methods<a name="section11583621172616"></a>

## equals<a name="section1631196204012"></a>

<a name="table11892mcpsimp"></a>
<table><thead align="left"><tr id="row11896mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p11898mcpsimp"><a name="p11898mcpsimp"></a><a name="p11898mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row11899mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p11901mcpsimp"><a name="p11901mcpsimp"></a><a name="p11901mcpsimp"></a>public boolean equals(Object other)</p>
<p id="p11904mcpsimp"><a name="p11904mcpsimp"></a><a name="p11904mcpsimp"></a>判断两个覆盖物对象是否相等。</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table11907mcpsimp"></a>
<table><thead align="left"><tr id="row11912mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p11914mcpsimp"><a name="p11914mcpsimp"></a><a name="p11914mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p11916mcpsimp"><a name="p11916mcpsimp"></a><a name="p11916mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row11917mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p11919mcpsimp"><a name="p11919mcpsimp"></a><a name="p11919mcpsimp"></a>other</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p11921mcpsimp"><a name="p11921mcpsimp"></a><a name="p11921mcpsimp"></a>另一对象。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table11924mcpsimp"></a>
<table><thead align="left"><tr id="row11929mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p11931mcpsimp"><a name="p11931mcpsimp"></a><a name="p11931mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p11933mcpsimp"><a name="p11933mcpsimp"></a><a name="p11933mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row11934mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p11936mcpsimp"><a name="p11936mcpsimp"></a><a name="p11936mcpsimp"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p11938mcpsimp"><a name="p11938mcpsimp"></a><a name="p11938mcpsimp"></a>覆盖物对象是否相等。true为相等，false为不相等。</p>
</td>
</tr>
</tbody>
</table>

## getBearing<a name="section47162554391"></a>

<a name="table11940mcpsimp"></a>
<table><thead align="left"><tr id="row11944mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p11946mcpsimp"><a name="p11946mcpsimp"></a><a name="p11946mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row11947mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p11949mcpsimp"><a name="p11949mcpsimp"></a><a name="p11949mcpsimp"></a>public float getBearing()</p>
<p id="p1068609350"><a name="p1068609350"></a><a name="p1068609350"></a>您调用此API可以获取覆盖物的角度。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table11958mcpsimp"></a>
<table><thead align="left"><tr id="row11963mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p11965mcpsimp"><a name="p11965mcpsimp"></a><a name="p11965mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p11967mcpsimp"><a name="p11967mcpsimp"></a><a name="p11967mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row11968mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p11970mcpsimp"><a name="p11970mcpsimp"></a><a name="p11970mcpsimp"></a>float</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p11972mcpsimp"><a name="p11972mcpsimp"></a><a name="p11972mcpsimp"></a>覆盖物的角度。</p>
</td>
</tr>
</tbody>
</table>

## getBounds<a name="section1437364753911"></a>

<a name="table11974mcpsimp"></a>
<table><thead align="left"><tr id="row11978mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p11980mcpsimp"><a name="p11980mcpsimp"></a><a name="p11980mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row11981mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p11983mcpsimp"><a name="p11983mcpsimp"></a><a name="p11983mcpsimp"></a>public <a href="latlngbounds.md">LatLngBounds</a> getBounds()</p>
<p id="p48351717157"><a name="p48351717157"></a><a name="p48351717157"></a>您调用此API可以获取覆盖物的矩形区域。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table11992mcpsimp"></a>
<table><thead align="left"><tr id="row11997mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p11999mcpsimp"><a name="p11999mcpsimp"></a><a name="p11999mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p12001mcpsimp"><a name="p12001mcpsimp"></a><a name="p12001mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row12002mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p12004mcpsimp"><a name="p12004mcpsimp"></a><a name="p12004mcpsimp"></a><a href="latlngbounds.md">LatLngBounds</a></p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p12006mcpsimp"><a name="p12006mcpsimp"></a><a name="p12006mcpsimp"></a>覆盖物的矩形区域。</p>
</td>
</tr>
</tbody>
</table>

## getHeight<a name="section1786016343394"></a>

<a name="table12008mcpsimp"></a>
<table><thead align="left"><tr id="row12012mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p12014mcpsimp"><a name="p12014mcpsimp"></a><a name="p12014mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row12015mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p12017mcpsimp"><a name="p12017mcpsimp"></a><a name="p12017mcpsimp"></a>public float getHeight()</p>
<p id="p67815273510"><a name="p67815273510"></a><a name="p67815273510"></a>您调用此API可以获取覆盖物的高。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table12026mcpsimp"></a>
<table><thead align="left"><tr id="row12031mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p12033mcpsimp"><a name="p12033mcpsimp"></a><a name="p12033mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p12035mcpsimp"><a name="p12035mcpsimp"></a><a name="p12035mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row12036mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p12038mcpsimp"><a name="p12038mcpsimp"></a><a name="p12038mcpsimp"></a>float</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p12040mcpsimp"><a name="p12040mcpsimp"></a><a name="p12040mcpsimp"></a>覆盖物的高度，单位：米。</p>
</td>
</tr>
</tbody>
</table>

## getId<a name="section5514162863912"></a>

<a name="table12042mcpsimp"></a>
<table><thead align="left"><tr id="row12046mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p12048mcpsimp"><a name="p12048mcpsimp"></a><a name="p12048mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row12049mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p12051mcpsimp"><a name="p12051mcpsimp"></a><a name="p12051mcpsimp"></a>public String getId()</p>
<p id="p183732379519"><a name="p183732379519"></a><a name="p183732379519"></a>您调用此API可以获取覆盖物的ID属性，该ID在地图上的所有覆盖物中都是唯一的。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table12060mcpsimp"></a>
<table><thead align="left"><tr id="row12065mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p12067mcpsimp"><a name="p12067mcpsimp"></a><a name="p12067mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p12069mcpsimp"><a name="p12069mcpsimp"></a><a name="p12069mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row12070mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p12072mcpsimp"><a name="p12072mcpsimp"></a><a name="p12072mcpsimp"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p12074mcpsimp"><a name="p12074mcpsimp"></a><a name="p12074mcpsimp"></a>覆盖物的ID。</p>
</td>
</tr>
</tbody>
</table>

## getPosition<a name="section1422515195398"></a>

<a name="table12076mcpsimp"></a>
<table><thead align="left"><tr id="row12080mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p12082mcpsimp"><a name="p12082mcpsimp"></a><a name="p12082mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row12083mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p12085mcpsimp"><a name="p12085mcpsimp"></a><a name="p12085mcpsimp"></a>public <a href="latlng.md">LatLng</a> getPosition()</p>
<p id="p293219461559"><a name="p293219461559"></a><a name="p293219461559"></a>您调用此API可以获取覆盖物的位置信息。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table12094mcpsimp"></a>
<table><thead align="left"><tr id="row12099mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p12101mcpsimp"><a name="p12101mcpsimp"></a><a name="p12101mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p12103mcpsimp"><a name="p12103mcpsimp"></a><a name="p12103mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row12104mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p12106mcpsimp"><a name="p12106mcpsimp"></a><a name="p12106mcpsimp"></a><a href="latlng.md">LatLng</a></p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p12108mcpsimp"><a name="p12108mcpsimp"></a><a name="p12108mcpsimp"></a>覆盖物的经纬度。</p>
</td>
</tr>
</tbody>
</table>

## getTag<a name="section182571159123818"></a>

<a name="table12144mcpsimp"></a>
<table><thead align="left"><tr id="row12148mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p12150mcpsimp"><a name="p12150mcpsimp"></a><a name="p12150mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row12151mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p12153mcpsimp"><a name="p12153mcpsimp"></a><a name="p12153mcpsimp"></a>public Object getTag()</p>
<p id="p67231961262"><a name="p67231961262"></a><a name="p67231961262"></a>当您已给覆盖物设置tag属性，调用此API将获取该tag属性。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table12162mcpsimp"></a>
<table><thead align="left"><tr id="row12167mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p12169mcpsimp"><a name="p12169mcpsimp"></a><a name="p12169mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p12171mcpsimp"><a name="p12171mcpsimp"></a><a name="p12171mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row12172mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p12174mcpsimp"><a name="p12174mcpsimp"></a><a name="p12174mcpsimp"></a>Object</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p12176mcpsimp"><a name="p12176mcpsimp"></a><a name="p12176mcpsimp"></a>如果已设置tag，则返回Object；如果未设置，则返回null。</p>
</td>
</tr>
</tbody>
</table>

## getTransparency<a name="section176028810392"></a>

<a name="table12110mcpsimp"></a>
<table><thead align="left"><tr id="row12114mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p12116mcpsimp"><a name="p12116mcpsimp"></a><a name="p12116mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row12117mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p12119mcpsimp"><a name="p12119mcpsimp"></a><a name="p12119mcpsimp"></a>public float getTransparency()</p>
<p id="p762035815510"><a name="p762035815510"></a><a name="p762035815510"></a>您调用此API可以获取覆盖物的透明度。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table12128mcpsimp"></a>
<table><thead align="left"><tr id="row12133mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p12135mcpsimp"><a name="p12135mcpsimp"></a><a name="p12135mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p12137mcpsimp"><a name="p12137mcpsimp"></a><a name="p12137mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row12138mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p12140mcpsimp"><a name="p12140mcpsimp"></a><a name="p12140mcpsimp"></a>float</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p12142mcpsimp"><a name="p12142mcpsimp"></a><a name="p12142mcpsimp"></a>覆盖物的透明度，取值范围：[0, 1]，0为不透明，1为全透明。</p>
</td>
</tr>
</tbody>
</table>

## getWidth<a name="section10294105218386"></a>

<a name="table12178mcpsimp"></a>
<table><thead align="left"><tr id="row12182mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p12184mcpsimp"><a name="p12184mcpsimp"></a><a name="p12184mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row12185mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p12187mcpsimp"><a name="p12187mcpsimp"></a><a name="p12187mcpsimp"></a>public float getWidth()</p>
<p id="p91011132565"><a name="p91011132565"></a><a name="p91011132565"></a>您调用此API可以获取覆盖物的宽度。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table12196mcpsimp"></a>
<table><thead align="left"><tr id="row12201mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p12203mcpsimp"><a name="p12203mcpsimp"></a><a name="p12203mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p12205mcpsimp"><a name="p12205mcpsimp"></a><a name="p12205mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row12206mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p12208mcpsimp"><a name="p12208mcpsimp"></a><a name="p12208mcpsimp"></a>float</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p12210mcpsimp"><a name="p12210mcpsimp"></a><a name="p12210mcpsimp"></a>覆盖物的宽度，单位：米。</p>
</td>
</tr>
</tbody>
</table>

## getZIndex<a name="section1132764615389"></a>

<a name="table12212mcpsimp"></a>
<table><thead align="left"><tr id="row12216mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p12218mcpsimp"><a name="p12218mcpsimp"></a><a name="p12218mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row12219mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p12221mcpsimp"><a name="p12221mcpsimp"></a><a name="p12221mcpsimp"></a>public float getZIndex()</p>
<p id="p569719461161"><a name="p569719461161"></a><a name="p569719461161"></a>您调用此API可以获取覆盖物的z指数。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table12230mcpsimp"></a>
<table><thead align="left"><tr id="row12235mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p12237mcpsimp"><a name="p12237mcpsimp"></a><a name="p12237mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p12239mcpsimp"><a name="p12239mcpsimp"></a><a name="p12239mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row12240mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p12242mcpsimp"><a name="p12242mcpsimp"></a><a name="p12242mcpsimp"></a>float</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p12244mcpsimp"><a name="p12244mcpsimp"></a><a name="p12244mcpsimp"></a>z指数，即覆盖物的叠加顺序。</p>
</td>
</tr>
</tbody>
</table>

## hashCode<a name="section10415133293811"></a>

<a name="table12246mcpsimp"></a>
<table><thead align="left"><tr id="row12250mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p12252mcpsimp"><a name="p12252mcpsimp"></a><a name="p12252mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row12253mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p12255mcpsimp"><a name="p12255mcpsimp"></a><a name="p12255mcpsimp"></a>public int hashCode()</p>
<p id="p12258mcpsimp"><a name="p12258mcpsimp"></a><a name="p12258mcpsimp"></a>您调用此API可以获取覆盖物的哈希值。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table12264mcpsimp"></a>
<table><thead align="left"><tr id="row12269mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p12271mcpsimp"><a name="p12271mcpsimp"></a><a name="p12271mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p12273mcpsimp"><a name="p12273mcpsimp"></a><a name="p12273mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row12274mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p12276mcpsimp"><a name="p12276mcpsimp"></a><a name="p12276mcpsimp"></a>int</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p12278mcpsimp"><a name="p12278mcpsimp"></a><a name="p12278mcpsimp"></a>表示覆盖物的哈希值。</p>
</td>
</tr>
</tbody>
</table>

## isClickable<a name="section4812182453810"></a>

<a name="table12280mcpsimp"></a>
<table><thead align="left"><tr id="row12284mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p12286mcpsimp"><a name="p12286mcpsimp"></a><a name="p12286mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row12287mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p12289mcpsimp"><a name="p12289mcpsimp"></a><a name="p12289mcpsimp"></a>public boolean isClickable()</p>
<p id="p1623619253716"><a name="p1623619253716"></a><a name="p1623619253716"></a>您调用此API可以获取覆盖物的可点击性。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table12298mcpsimp"></a>
<table><thead align="left"><tr id="row12303mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p12305mcpsimp"><a name="p12305mcpsimp"></a><a name="p12305mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p12307mcpsimp"><a name="p12307mcpsimp"></a><a name="p12307mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row12308mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p12310mcpsimp"><a name="p12310mcpsimp"></a><a name="p12310mcpsimp"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p12312mcpsimp"><a name="p12312mcpsimp"></a><a name="p12312mcpsimp"></a>覆盖物的可点击性，true为可点击，false为不可点击。</p>
</td>
</tr>
</tbody>
</table>

## isVisible<a name="section1931111673818"></a>

<a name="table12314mcpsimp"></a>
<table><thead align="left"><tr id="row12318mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p12320mcpsimp"><a name="p12320mcpsimp"></a><a name="p12320mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row12321mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p12323mcpsimp"><a name="p12323mcpsimp"></a><a name="p12323mcpsimp"></a>public boolean isVisible()</p>
<p id="p12326mcpsimp"><a name="p12326mcpsimp"></a><a name="p12326mcpsimp"></a>您调用此API可以获取覆盖物的可见性。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table12332mcpsimp"></a>
<table><thead align="left"><tr id="row12337mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p12339mcpsimp"><a name="p12339mcpsimp"></a><a name="p12339mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p12341mcpsimp"><a name="p12341mcpsimp"></a><a name="p12341mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row12342mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p12344mcpsimp"><a name="p12344mcpsimp"></a><a name="p12344mcpsimp"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p12346mcpsimp"><a name="p12346mcpsimp"></a><a name="p12346mcpsimp"></a>覆盖物的可见性，true为可见，false为不可见。</p>
</td>
</tr>
</tbody>
</table>

## remove<a name="section137601858123719"></a>

<a name="table12348mcpsimp"></a>
<table><thead align="left"><tr id="row12352mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p12354mcpsimp"><a name="p12354mcpsimp"></a><a name="p12354mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row12355mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p12357mcpsimp"><a name="p12357mcpsimp"></a><a name="p12357mcpsimp"></a>public void remove()</p>
<p id="p1912214141412"><a name="p1912214141412"></a><a name="p1912214141412"></a>您调用此API可以将覆盖物从地图上移除。</p>
</td>
</tr>
</tbody>
</table>

## setBearing<a name="section1239854733712"></a>

<a name="table12368mcpsimp"></a>
<table><thead align="left"><tr id="row12372mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p12374mcpsimp"><a name="p12374mcpsimp"></a><a name="p12374mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row12375mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="_ZH-CN_TOPIC_0204692055-chtext"><a name="_ZH-CN_TOPIC_0204692055-chtext"></a><a name="_ZH-CN_TOPIC_0204692055-chtext"></a>public void setBearing(float bearing)</p>
<p id="p9318422134116"><a name="p9318422134116"></a><a name="p9318422134116"></a>您调用此API可以设置覆盖物从正北顺时针的角度。</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table12382mcpsimp"></a>
<table><thead align="left"><tr id="row12387mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p12389mcpsimp"><a name="p12389mcpsimp"></a><a name="p12389mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p12391mcpsimp"><a name="p12391mcpsimp"></a><a name="p12391mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row12392mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p12394mcpsimp"><a name="p12394mcpsimp"></a><a name="p12394mcpsimp"></a>bearing</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p12396mcpsimp"><a name="p12396mcpsimp"></a><a name="p12396mcpsimp"></a>覆盖物从正北顺时针的角度，正北方向为0度，顺时针增加。取值范围：[0, 360]，默认为0。</p>
</td>
</tr>
</tbody>
</table>

## setClickable<a name="section45409352378"></a>

<a name="table12401mcpsimp"></a>
<table><thead align="left"><tr id="row12405mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p12407mcpsimp"><a name="p12407mcpsimp"></a><a name="p12407mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row12408mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p12410mcpsimp"><a name="p12410mcpsimp"></a><a name="p12410mcpsimp"></a>public void setClickable(boolean clickable)</p>
<p id="p169469321414"><a name="p169469321414"></a><a name="p169469321414"></a>您调用此API可以设置覆盖物的可点击性。</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table12416mcpsimp"></a>
<table><thead align="left"><tr id="row12421mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p12423mcpsimp"><a name="p12423mcpsimp"></a><a name="p12423mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p12425mcpsimp"><a name="p12425mcpsimp"></a><a name="p12425mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row12426mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p12428mcpsimp"><a name="p12428mcpsimp"></a><a name="p12428mcpsimp"></a>clickable</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p12430mcpsimp"><a name="p12430mcpsimp"></a><a name="p12430mcpsimp"></a>可点击性。默认为不可点击。</p>
</td>
</tr>
</tbody>
</table>

## setDimensions\(float width, float height\)<a name="section6919112773713"></a>

<a name="table12435mcpsimp"></a>
<table><thead align="left"><tr id="row12439mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p12441mcpsimp"><a name="p12441mcpsimp"></a><a name="p12441mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row12442mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p12444mcpsimp"><a name="p12444mcpsimp"></a><a name="p12444mcpsimp"></a>public void setDimensions(float width, float height)</p>
<p id="p1840440114119"><a name="p1840440114119"></a><a name="p1840440114119"></a>您调用此API可以设置覆盖物的宽高，图片会被拉伸，可能不会保留之前的图片比例。</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table12450mcpsimp"></a>
<table><thead align="left"><tr id="row12455mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p12457mcpsimp"><a name="p12457mcpsimp"></a><a name="p12457mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p12459mcpsimp"><a name="p12459mcpsimp"></a><a name="p12459mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row12460mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p12462mcpsimp"><a name="p12462mcpsimp"></a><a name="p12462mcpsimp"></a>width</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p12464mcpsimp"><a name="p12464mcpsimp"></a><a name="p12464mcpsimp"></a>覆盖物的宽度，单位：米。</p>
</td>
</tr>
<tr id="row12465mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p12467mcpsimp"><a name="p12467mcpsimp"></a><a name="p12467mcpsimp"></a>height</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p12469mcpsimp"><a name="p12469mcpsimp"></a><a name="p12469mcpsimp"></a>覆盖物的高度，单位：米。</p>
</td>
</tr>
</tbody>
</table>

## setDimensions\(float width\)<a name="section0141102153714"></a>

<a name="table12474mcpsimp"></a>
<table><thead align="left"><tr id="row12478mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p12480mcpsimp"><a name="p12480mcpsimp"></a><a name="p12480mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row12481mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p12483mcpsimp"><a name="p12483mcpsimp"></a><a name="p12483mcpsimp"></a>public void setDimensions(float width)</p>
<p id="p12486mcpsimp"><a name="p12486mcpsimp"></a><a name="p12486mcpsimp"></a>您调用此API可以设置覆盖物的宽度，覆盖物的高度根据图片的比例自动变化。</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table12489mcpsimp"></a>
<table><thead align="left"><tr id="row12494mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p12496mcpsimp"><a name="p12496mcpsimp"></a><a name="p12496mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p12498mcpsimp"><a name="p12498mcpsimp"></a><a name="p12498mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row12499mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p12501mcpsimp"><a name="p12501mcpsimp"></a><a name="p12501mcpsimp"></a>width</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p12503mcpsimp"><a name="p12503mcpsimp"></a><a name="p12503mcpsimp"></a>覆盖物的宽度，单位：米。</p>
</td>
</tr>
</tbody>
</table>

## setImage<a name="section1281711313376"></a>

<a name="table12508mcpsimp"></a>
<table><thead align="left"><tr id="row12512mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p12514mcpsimp"><a name="p12514mcpsimp"></a><a name="p12514mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row12515mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p12517mcpsimp"><a name="p12517mcpsimp"></a><a name="p12517mcpsimp"></a>public void setImage(<a href="bitmapdescriptor.md">BitmapDescriptor </a>imageDescriptor)</p>
<p id="p9484135134114"><a name="p9484135134114"></a><a name="p9484135134114"></a>您调用此API可以置覆盖物的图片信息，新图片会使用老图片的矩形区域。</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table12523mcpsimp"></a>
<table><thead align="left"><tr id="row12528mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p12530mcpsimp"><a name="p12530mcpsimp"></a><a name="p12530mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p12532mcpsimp"><a name="p12532mcpsimp"></a><a name="p12532mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row12533mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p12535mcpsimp"><a name="p12535mcpsimp"></a><a name="p12535mcpsimp"></a>imageDescriptor</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p12537mcpsimp"><a name="p12537mcpsimp"></a><a name="p12537mcpsimp"></a>图片对象。</p>
</td>
</tr>
</tbody>
</table>

## setPosition<a name="section141766412377"></a>

<a name="table12542mcpsimp"></a>
<table><thead align="left"><tr id="row12546mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p12548mcpsimp"><a name="p12548mcpsimp"></a><a name="p12548mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row12549mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p12551mcpsimp"><a name="p12551mcpsimp"></a><a name="p12551mcpsimp"></a>public setPosition(<a href="latlng.md">LatLng</a> latLng)</p>
<p id="p1257735818418"><a name="p1257735818418"></a><a name="p1257735818418"></a>您调用此API可以设置覆盖物的位置，覆盖物的其他属性不变。</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table12557mcpsimp"></a>
<table><thead align="left"><tr id="row12562mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p12564mcpsimp"><a name="p12564mcpsimp"></a><a name="p12564mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p12566mcpsimp"><a name="p12566mcpsimp"></a><a name="p12566mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row12567mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p12569mcpsimp"><a name="p12569mcpsimp"></a><a name="p12569mcpsimp"></a>latLng</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p12571mcpsimp"><a name="p12571mcpsimp"></a><a name="p12571mcpsimp"></a>覆盖物的位置。默认情况下，锚点在距离图像顶部和图像左侧一半的位置。</p>
</td>
</tr>
</tbody>
</table>

## setPositionFromBounds<a name="section977685511362"></a>

<a name="table12576mcpsimp"></a>
<table><thead align="left"><tr id="row12580mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p12582mcpsimp"><a name="p12582mcpsimp"></a><a name="p12582mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row12583mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p12585mcpsimp"><a name="p12585mcpsimp"></a><a name="p12585mcpsimp"></a>public void setPositionFromBounds(<a href="latlngbounds.md">LatLngBounds</a> bounds)</p>
<p id="p1383815212920"><a name="p1383815212920"></a><a name="p1383815212920"></a>根据矩形区域设置覆盖物的位置。当定位时忽略旋转的角度，但绘制覆盖物时仍会使用它。</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table12591mcpsimp"></a>
<table><thead align="left"><tr id="row12596mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p12598mcpsimp"><a name="p12598mcpsimp"></a><a name="p12598mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p12600mcpsimp"><a name="p12600mcpsimp"></a><a name="p12600mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row12601mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p12603mcpsimp"><a name="p12603mcpsimp"></a><a name="p12603mcpsimp"></a>bounds</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p12605mcpsimp"><a name="p12605mcpsimp"></a><a name="p12605mcpsimp"></a>覆盖物位置的矩形区域。</p>
</td>
</tr>
</tbody>
</table>

## setTag<a name="section85441446203618"></a>

<a name="table12610mcpsimp"></a>
<table><thead align="left"><tr id="row12614mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p12616mcpsimp"><a name="p12616mcpsimp"></a><a name="p12616mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row12617mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p12619mcpsimp"><a name="p12619mcpsimp"></a><a name="p12619mcpsimp"></a>public void setTag(Object tag)</p>
<p id="p8917150243"><a name="p8917150243"></a><a name="p8917150243"></a>您调用此API可以设置覆盖物的tag属性，tag属性可以是任意对象，如果设置为空，则清除tag。当您不再需要使用tag时，您可以调用setTag(null)清除tag，以防止应用程序发生内存泄漏。</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table12625mcpsimp"></a>
<table><thead align="left"><tr id="row12630mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p12632mcpsimp"><a name="p12632mcpsimp"></a><a name="p12632mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p12634mcpsimp"><a name="p12634mcpsimp"></a><a name="p12634mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row12635mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p12637mcpsimp"><a name="p12637mcpsimp"></a><a name="p12637mcpsimp"></a>tag</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p12639mcpsimp"><a name="p12639mcpsimp"></a><a name="p12639mcpsimp"></a>覆盖物的tag属性。</p>
</td>
</tr>
</tbody>
</table>

## setTransparency<a name="section497274010365"></a>

<a name="table12644mcpsimp"></a>
<table><thead align="left"><tr id="row12648mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p12650mcpsimp"><a name="p12650mcpsimp"></a><a name="p12650mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row12651mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p12653mcpsimp"><a name="p12653mcpsimp"></a><a name="p12653mcpsimp"></a>public void setTransparency(float transparency)</p>
<p id="p1614813571994"><a name="p1614813571994"></a><a name="p1614813571994"></a>设置覆盖物的透明度。</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table12659mcpsimp"></a>
<table><thead align="left"><tr id="row12664mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p12666mcpsimp"><a name="p12666mcpsimp"></a><a name="p12666mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p12668mcpsimp"><a name="p12668mcpsimp"></a><a name="p12668mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row12669mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p12671mcpsimp"><a name="p12671mcpsimp"></a><a name="p12671mcpsimp"></a>transparency</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p12673mcpsimp"><a name="p12673mcpsimp"></a><a name="p12673mcpsimp"></a>覆盖物的透明度，取值范围：[0, 1]，0为不透明，1为全透明，默认为0。</p>
</td>
</tr>
</tbody>
</table>

## setVisible<a name="section312643417368"></a>

<a name="table12678mcpsimp"></a>
<table><thead align="left"><tr id="row12682mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p12684mcpsimp"><a name="p12684mcpsimp"></a><a name="p12684mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row12685mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p12687mcpsimp"><a name="p12687mcpsimp"></a><a name="p12687mcpsimp"></a>public void setVisible(boolean visible)</p>
<p id="p12690mcpsimp"><a name="p12690mcpsimp"></a><a name="p12690mcpsimp"></a>您调用此方法来设置覆盖物的可见性，如果覆盖物不可见，则不会绘制，其他所有状态均保留。</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table12693mcpsimp"></a>
<table><thead align="left"><tr id="row12698mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p12700mcpsimp"><a name="p12700mcpsimp"></a><a name="p12700mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p12702mcpsimp"><a name="p12702mcpsimp"></a><a name="p12702mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row12703mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p12705mcpsimp"><a name="p12705mcpsimp"></a><a name="p12705mcpsimp"></a>visible</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p12707mcpsimp"><a name="p12707mcpsimp"></a><a name="p12707mcpsimp"></a>可见性。默认为可见。</p>
</td>
</tr>
</tbody>
</table>

## setZIndex<a name="section61641226133617"></a>

<a name="table12712mcpsimp"></a>
<table><thead align="left"><tr id="row12716mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p12718mcpsimp"><a name="p12718mcpsimp"></a><a name="p12718mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row12719mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p12721mcpsimp"><a name="p12721mcpsimp"></a><a name="p12721mcpsimp"></a>public void setZIndex(float zIndex)</p>
<p id="p12724mcpsimp"><a name="p12724mcpsimp"></a><a name="p12724mcpsimp"></a>用于设置覆盖物的z指数。z指数指的是覆盖物的叠加顺序，具有较大z指数的覆盖物会绘制在具有较小z指数的覆盖物上，具有相同z指数的叠加顺序为元素添加的先后顺序。</p>
<div class="note" id="note6936411216"><a name="note6936411216"></a><a name="note6936411216"></a><span class="notetitle"> 说明： </span><div class="notebody"><p id="p209367111517"><a name="p209367111517"></a><a name="p209367111517"></a>数量限制：添加Circle和Polygon的总数乘以2加上添加Polyline和GroundOverlay的总数不超过1450，否则会出现图形叠加错误。</p>
</div></div>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table12727mcpsimp"></a>
<table><thead align="left"><tr id="row12732mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p12734mcpsimp"><a name="p12734mcpsimp"></a><a name="p12734mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p12736mcpsimp"><a name="p12736mcpsimp"></a><a name="p12736mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row12737mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p12739mcpsimp"><a name="p12739mcpsimp"></a><a name="p12739mcpsimp"></a>zIndex</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p12741mcpsimp"><a name="p12741mcpsimp"></a><a name="p12741mcpsimp"></a>z指数，即覆盖物的叠加顺序。默认的z指数是0。</p>
</td>
</tr>
</tbody>
</table>

