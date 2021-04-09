# Polygon<a name="EN-US_TOPIC_0000001145941057"></a>

-   [Public Method Summary](#section13652164911616)
-   [Public Methods](#section097019101110)
-   [equals](#section5705142315118)
-   [getFillColor](#section3159212171217)
-   [getHoles](#section103112038131311)
-   [getId](#section13702171911411)
-   [getPoints](#section1876512539146)
-   [getStrokeColor](#section1874123281519)
-   [getStrokeJointType](#section65261817181613)
-   [getStrokePattern](#section2866846121612)
-   [getStrokeWidth](#section850172711172)
-   [getTag](#section2054262111817)
-   [getZIndex](#section15792359171818)
-   [hashCode](#section6648437191917)
-   [isClickable](#section163616732011)
-   [isGeodesic](#section94211744162019)
-   [isVisible](#section2092752502116)
-   [remove](#section81662315221)
-   [setClickable](#section151966234239)
-   [setFillColor](#section10729185902319)
-   [setGeodesic](#section655394202410)
-   [setHoles](#section2803142417253)
-   [setPoints](#section1826199122616)
-   [setStrokeColor](#section14513438269)
-   [setStrokeJointType](#section283222602715)
-   [setStrokePattern](#section1218011417281)
-   [setStrokeWidth](#section11113144212284)
-   [setTag](#section72874203297)
-   [setVisible](#section15486012306)
-   [setZIndex](#section1650733317309)


<a name="table17316mcpsimp"></a>
<table><thead align="left"><tr id="row17320mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p17322mcpsimp"><a name="p17322mcpsimp"></a><a name="p17322mcpsimp"></a>Class Info</p>
</th>
</tr>
</thead>
<tbody><tr id="row17323mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p18562191834216"><a name="p18562191834216"></a><a name="p18562191834216"></a>public final class Polygon</p>
<p id="p17325mcpsimp"><a name="p17325mcpsimp"></a><a name="p17325mcpsimp"></a>Defines a polygon on the surface of the Earth. A polygon can be convex or concave. It can span the 180 meridian and have holes that are not filled in. An instance of this type will be returned when the <a href="huaweimap.md#section342720397412">addPolygon</a> method in the <a href="huaweimap.md">HuaweiMap</a> class is called.</p>
</td>
</tr>
</tbody>
</table>

## Public Method Summary<a name="section13652164911616"></a>

<a name="table17340mcpsimp"></a>
<table><thead align="left"><tr id="row17345mcpsimp"><th class="cellrowborder" valign="top" width="40%" id="mcps1.1.3.1.1"><p id="p081120285386"><a name="p081120285386"></a><a name="p081120285386"></a>Qualifier and Type</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.1.3.1.2"><p id="p681112883813"><a name="p681112883813"></a><a name="p681112883813"></a>Method Name and Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row17350mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p17352mcpsimp"><a name="p17352mcpsimp"></a><a name="p17352mcpsimp"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p17354mcpsimp"><a name="p17354mcpsimp"></a><a name="p17354mcpsimp"></a><a href="#section5705142315118">equals</a>(Object other)</p>
<p id="p9104145919288"><a name="p9104145919288"></a><a name="p9104145919288"></a>Checks whether a polygon object equals another.</p>
</td>
</tr>
<tr id="row17355mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p17357mcpsimp"><a name="p17357mcpsimp"></a><a name="p17357mcpsimp"></a>int</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p17359mcpsimp"><a name="p17359mcpsimp"></a><a name="p17359mcpsimp"></a><a href="#section3159212171217">getFillColor</a>()</p>
<p id="p101894042915"><a name="p101894042915"></a><a name="p101894042915"></a>Obtains the fill color of a polygon, in ARGB format.</p>
</td>
</tr>
<tr id="row17360mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p17362mcpsimp"><a name="p17362mcpsimp"></a><a name="p17362mcpsimp"></a>List&lt;List&lt;<a href="latlng.md">LatLng</a>&gt;&gt;</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p17364mcpsimp"><a name="p17364mcpsimp"></a><a name="p17364mcpsimp"></a><a href="#section103112038131311">getHoles</a>()</p>
<p id="p9313219291"><a name="p9313219291"></a><a name="p9313219291"></a>Obtains holes in a polygon on a map.</p>
</td>
</tr>
<tr id="row17365mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p17367mcpsimp"><a name="p17367mcpsimp"></a><a name="p17367mcpsimp"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p17369mcpsimp"><a name="p17369mcpsimp"></a><a name="p17369mcpsimp"></a><a href="#section13702171911411">getId</a>()</p>
<p id="p15757352917"><a name="p15757352917"></a><a name="p15757352917"></a>Obtains the ID of a polygon on a map.</p>
</td>
</tr>
<tr id="row17370mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p17372mcpsimp"><a name="p17372mcpsimp"></a><a name="p17372mcpsimp"></a>List&lt;<a href="latlng.md">LatLng</a>&gt;</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p17374mcpsimp"><a name="p17374mcpsimp"></a><a name="p17374mcpsimp"></a><a href="#section1876512539146">getPoints</a>()</p>
<p id="p1186117392912"><a name="p1186117392912"></a><a name="p1186117392912"></a>Obtains the vertex set of a polygon.</p>
</td>
</tr>
<tr id="row17375mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p17377mcpsimp"><a name="p17377mcpsimp"></a><a name="p17377mcpsimp"></a>int</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p17379mcpsimp"><a name="p17379mcpsimp"></a><a name="p17379mcpsimp"></a><a href="#section1874123281519">getStrokeColor</a>()</p>
<p id="p268819412299"><a name="p268819412299"></a><a name="p268819412299"></a>Obtains the stroke color of a polygon's outline, in ARGB format.</p>
</td>
</tr>
<tr id="row17380mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p17382mcpsimp"><a name="p17382mcpsimp"></a><a name="p17382mcpsimp"></a>int</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p17384mcpsimp"><a name="p17384mcpsimp"></a><a name="p17384mcpsimp"></a><a href="#section65261817181613">getStrokeJointType</a>()</p>
<p id="p44834572912"><a name="p44834572912"></a><a name="p44834572912"></a>Obtains the joint type of a polygon.</p>
</td>
</tr>
<tr id="row17385mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p17387mcpsimp"><a name="p17387mcpsimp"></a><a name="p17387mcpsimp"></a>List&lt;<a href="patternitem.md">PatternItem</a>&gt;</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p17389mcpsimp"><a name="p17389mcpsimp"></a><a name="p17389mcpsimp"></a><a href="#section2866846121612">getStrokePattern</a>()</p>
<p id="p83281682913"><a name="p83281682913"></a><a name="p83281682913"></a>Obtains the stroke pattern of a polygon's outline.</p>
</td>
</tr>
<tr id="row17390mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p17392mcpsimp"><a name="p17392mcpsimp"></a><a name="p17392mcpsimp"></a>float</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p17394mcpsimp"><a name="p17394mcpsimp"></a><a name="p17394mcpsimp"></a><a href="#section850172711172">getStrokeWidth</a>()</p>
<p id="p139957719295"><a name="p139957719295"></a><a name="p139957719295"></a>Obtains the stroke width of a polygon's outline, in pixels.</p>
</td>
</tr>
<tr id="row17395mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p17397mcpsimp"><a name="p17397mcpsimp"></a><a name="p17397mcpsimp"></a>Object</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p17399mcpsimp"><a name="p17399mcpsimp"></a><a name="p17399mcpsimp"></a><a href="#section2054262111817">getTag</a>()</p>
<p id="p39112922912"><a name="p39112922912"></a><a name="p39112922912"></a>Obtains the <strong id="b86701615342"><a name="b86701615342"></a><a name="b86701615342"></a>tag</strong> attribute of a polygon.</p>
</td>
</tr>
<tr id="row17400mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p17402mcpsimp"><a name="p17402mcpsimp"></a><a name="p17402mcpsimp"></a>float</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p17404mcpsimp"><a name="p17404mcpsimp"></a><a name="p17404mcpsimp"></a><a href="#section15792359171818">getZIndex</a>()</p>
<p id="p17965199142910"><a name="p17965199142910"></a><a name="p17965199142910"></a>Obtains the z-index of a polygon.</p>
</td>
</tr>
<tr id="row17405mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p17407mcpsimp"><a name="p17407mcpsimp"></a><a name="p17407mcpsimp"></a>int</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p17409mcpsimp"><a name="p17409mcpsimp"></a><a name="p17409mcpsimp"></a><a href="#section6648437191917">hashCode</a>()</p>
<p id="p17826151014296"><a name="p17826151014296"></a><a name="p17826151014296"></a>Obtains the hash code of a polygon.</p>
</td>
</tr>
<tr id="row17410mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p17412mcpsimp"><a name="p17412mcpsimp"></a><a name="p17412mcpsimp"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p17414mcpsimp"><a name="p17414mcpsimp"></a><a name="p17414mcpsimp"></a><a href="#section163616732011">isClickable</a>()</p>
<p id="p11737611192918"><a name="p11737611192918"></a><a name="p11737611192918"></a>Checks whether a polygon is tappable.</p>
</td>
</tr>
<tr id="row17415mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p17417mcpsimp"><a name="p17417mcpsimp"></a><a name="p17417mcpsimp"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p17419mcpsimp"><a name="p17419mcpsimp"></a><a name="p17419mcpsimp"></a><a href="#section94211744162019">isGeodesic</a>()</p>
<p id="p115494121299"><a name="p115494121299"></a><a name="p115494121299"></a>Checks whether each segment of a polygon is drawn as a geodesic.</p>
</td>
</tr>
<tr id="row17420mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p17422mcpsimp"><a name="p17422mcpsimp"></a><a name="p17422mcpsimp"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p17424mcpsimp"><a name="p17424mcpsimp"></a><a name="p17424mcpsimp"></a><a href="#section2092752502116">isVisible</a>()</p>
<p id="p6371314192914"><a name="p6371314192914"></a><a name="p6371314192914"></a>Checks whether a polygon is visible.</p>
</td>
</tr>
<tr id="row17425mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p17427mcpsimp"><a name="p17427mcpsimp"></a><a name="p17427mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p17429mcpsimp"><a name="p17429mcpsimp"></a><a name="p17429mcpsimp"></a><a href="#section81662315221">remove</a>()</p>
<p id="p14284121514299"><a name="p14284121514299"></a><a name="p14284121514299"></a>Removes a polygon from a map.</p>
</td>
</tr>
<tr id="row17430mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p17432mcpsimp"><a name="p17432mcpsimp"></a><a name="p17432mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p17434mcpsimp"><a name="p17434mcpsimp"></a><a name="p17434mcpsimp"></a><a href="#section151966234239">setClickable</a>(boolean clickable)</p>
<p id="p312441610297"><a name="p312441610297"></a><a name="p312441610297"></a>Sets whether a polygon is tappable.</p>
</td>
</tr>
<tr id="row17435mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p17437mcpsimp"><a name="p17437mcpsimp"></a><a name="p17437mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p17439mcpsimp"><a name="p17439mcpsimp"></a><a name="p17439mcpsimp"></a><a href="#section10729185902319">setFillColor</a>(int color)</p>
<p id="p732712173298"><a name="p732712173298"></a><a name="p732712173298"></a>Sets the fill color of a polygon.</p>
</td>
</tr>
<tr id="row17440mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p17442mcpsimp"><a name="p17442mcpsimp"></a><a name="p17442mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p17444mcpsimp"><a name="p17444mcpsimp"></a><a name="p17444mcpsimp"></a><a href="#section655394202410">setGeodesic</a>(boolean geodesic)</p>
<p id="p1728331810299"><a name="p1728331810299"></a><a name="p1728331810299"></a>Sets whether to draw each segment of a polygon as a geodesic.</p>
</td>
</tr>
<tr id="row17445mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p17447mcpsimp"><a name="p17447mcpsimp"></a><a name="p17447mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p17449mcpsimp"><a name="p17449mcpsimp"></a><a name="p17449mcpsimp"></a><a href="#section2803142417253">setHoles</a>(List&lt;? extends List&lt;<a href="latlng.md">LatLng</a>&gt;&gt; holes)</p>
<p id="p75526193291"><a name="p75526193291"></a><a name="p75526193291"></a>Sets holes in a polygon.</p>
</td>
</tr>
<tr id="row17450mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p17452mcpsimp"><a name="p17452mcpsimp"></a><a name="p17452mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p17454mcpsimp"><a name="p17454mcpsimp"></a><a name="p17454mcpsimp"></a><a href="#section1826199122616">setPoints</a>(List&lt;<a href="latlng.md">LatLng</a>&gt; points)</p>
<p id="p143485209294"><a name="p143485209294"></a><a name="p143485209294"></a>Sets vertex coordinates of a polygon.</p>
</td>
</tr>
<tr id="row17455mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p17457mcpsimp"><a name="p17457mcpsimp"></a><a name="p17457mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p17459mcpsimp"><a name="p17459mcpsimp"></a><a name="p17459mcpsimp"></a><a href="#section14513438269">setStrokeColor</a>(int color)</p>
<p id="p18922117295"><a name="p18922117295"></a><a name="p18922117295"></a>Sets the stroke color of a polygon's outline.</p>
</td>
</tr>
<tr id="row17460mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p17462mcpsimp"><a name="p17462mcpsimp"></a><a name="p17462mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p17464mcpsimp"><a name="p17464mcpsimp"></a><a name="p17464mcpsimp"></a><a href="#section283222602715">setStrokeJointType</a>(int jointType)</p>
<p id="p10880112219298"><a name="p10880112219298"></a><a name="p10880112219298"></a>Sets the joint type of a polygon.</p>
</td>
</tr>
<tr id="row17465mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p17467mcpsimp"><a name="p17467mcpsimp"></a><a name="p17467mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p17469mcpsimp"><a name="p17469mcpsimp"></a><a name="p17469mcpsimp"></a><a href="#section1218011417281">setStrokePattern</a>(List&lt;<a href="patternitem.md">PatternItem</a>&gt; pattern)</p>
<p id="p169010231297"><a name="p169010231297"></a><a name="p169010231297"></a>Sets the stroke pattern of a polygon's outline.</p>
</td>
</tr>
<tr id="row17470mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p17472mcpsimp"><a name="p17472mcpsimp"></a><a name="p17472mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p17474mcpsimp"><a name="p17474mcpsimp"></a><a name="p17474mcpsimp"></a><a href="#section11113144212284">setStrokeWidth</a>(float width)</p>
<p id="p570622417299"><a name="p570622417299"></a><a name="p570622417299"></a>Sets the stroke width of a polygon's outline.</p>
</td>
</tr>
<tr id="row17475mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p17477mcpsimp"><a name="p17477mcpsimp"></a><a name="p17477mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p17479mcpsimp"><a name="p17479mcpsimp"></a><a name="p17479mcpsimp"></a><a href="#section72874203297">setTag</a>(Object tag)</p>
<p id="p1481442514297"><a name="p1481442514297"></a><a name="p1481442514297"></a>Sets the <strong id="b15809172515812"><a name="b15809172515812"></a><a name="b15809172515812"></a>tag</strong> attribute of a polygon.</p>
</td>
</tr>
<tr id="row17480mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p17482mcpsimp"><a name="p17482mcpsimp"></a><a name="p17482mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p17484mcpsimp"><a name="p17484mcpsimp"></a><a name="p17484mcpsimp"></a><a href="#section15486012306">setVisible</a>(boolean visible)</p>
<p id="p2612182610295"><a name="p2612182610295"></a><a name="p2612182610295"></a>Sets whether a polygon is visible.</p>
</td>
</tr>
<tr id="row17485mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p17487mcpsimp"><a name="p17487mcpsimp"></a><a name="p17487mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p17489mcpsimp"><a name="p17489mcpsimp"></a><a name="p17489mcpsimp"></a><a href="#section1650733317309">setZIndex</a>(float zIndex)</p>
<p id="p043114272293"><a name="p043114272293"></a><a name="p043114272293"></a>Sets the z-index of a polygon.</p>
</td>
</tr>
</tbody>
</table>

## Public Methods<a name="section097019101110"></a>

## equals<a name="section5705142315118"></a>

<a name="table17492mcpsimp"></a>
<table><thead align="left"><tr id="row17496mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p17498mcpsimp"><a name="p17498mcpsimp"></a><a name="p17498mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row17499mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p17501mcpsimp"><a name="p17501mcpsimp"></a><a name="p17501mcpsimp"></a>public boolean equals(Object other)</p>
<p id="p17504mcpsimp"><a name="p17504mcpsimp"></a><a name="p17504mcpsimp"></a>Checks whether a polygon object equals another.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table17507mcpsimp"></a>
<table><thead align="left"><tr id="row17512mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p17514mcpsimp"><a name="p17514mcpsimp"></a><a name="p17514mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p17516mcpsimp"><a name="p17516mcpsimp"></a><a name="p17516mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row17517mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p17519mcpsimp"><a name="p17519mcpsimp"></a><a name="p17519mcpsimp"></a>other</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p17521mcpsimp"><a name="p17521mcpsimp"></a><a name="p17521mcpsimp"></a>Another object to be compared.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table17524mcpsimp"></a>
<table><thead align="left"><tr id="row17529mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p17531mcpsimp"><a name="p17531mcpsimp"></a><a name="p17531mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p17533mcpsimp"><a name="p17533mcpsimp"></a><a name="p17533mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row17534mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p17536mcpsimp"><a name="p17536mcpsimp"></a><a name="p17536mcpsimp"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p17538mcpsimp"><a name="p17538mcpsimp"></a><a name="p17538mcpsimp"></a><strong id="b2145744195619"><a name="b2145744195619"></a><a name="b2145744195619"></a>true</strong> if the polygon objects are equal; <strong id="b141521744155618"><a name="b141521744155618"></a><a name="b141521744155618"></a>false</strong> otherwise.</p>
</td>
</tr>
</tbody>
</table>

## getFillColor<a name="section3159212171217"></a>

<a name="table17540mcpsimp"></a>
<table><thead align="left"><tr id="row17544mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p17546mcpsimp"><a name="p17546mcpsimp"></a><a name="p17546mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row17547mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p17549mcpsimp"><a name="p17549mcpsimp"></a><a name="p17549mcpsimp"></a>public int getFillColor()</p>
<p id="p17552mcpsimp"><a name="p17552mcpsimp"></a><a name="p17552mcpsimp"></a>Obtains the fill color of a polygon, in ARGB format.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table17558mcpsimp"></a>
<table><thead align="left"><tr id="row17563mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p17565mcpsimp"><a name="p17565mcpsimp"></a><a name="p17565mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p17567mcpsimp"><a name="p17567mcpsimp"></a><a name="p17567mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row17568mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p17570mcpsimp"><a name="p17570mcpsimp"></a><a name="p17570mcpsimp"></a>int</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p17572mcpsimp"><a name="p17572mcpsimp"></a><a name="p17572mcpsimp"></a>Color in ARGB format.</p>
</td>
</tr>
</tbody>
</table>

## getHoles<a name="section103112038131311"></a>

<a name="table17574mcpsimp"></a>
<table><thead align="left"><tr id="row17578mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p17580mcpsimp"><a name="p17580mcpsimp"></a><a name="p17580mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row17581mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p17583mcpsimp"><a name="p17583mcpsimp"></a><a name="p17583mcpsimp"></a>public List&lt;List&lt;<a href="latlng.md">LatLng</a>&gt;&gt; getHoles()</p>
<p id="p17586mcpsimp"><a name="p17586mcpsimp"></a><a name="p17586mcpsimp"></a>Obtains holes in a polygon on a map.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table17592mcpsimp"></a>
<table><thead align="left"><tr id="row17597mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p17599mcpsimp"><a name="p17599mcpsimp"></a><a name="p17599mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p17601mcpsimp"><a name="p17601mcpsimp"></a><a name="p17601mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row17602mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p17604mcpsimp"><a name="p17604mcpsimp"></a><a name="p17604mcpsimp"></a>List&lt;List&lt;<a href="latlng.md">LatLng</a>&gt;&gt;</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p17606mcpsimp"><a name="p17606mcpsimp"></a><a name="p17606mcpsimp"></a>Holes in a polygon.</p>
</td>
</tr>
</tbody>
</table>

## getId<a name="section13702171911411"></a>

<a name="table17608mcpsimp"></a>
<table><thead align="left"><tr id="row17612mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p17614mcpsimp"><a name="p17614mcpsimp"></a><a name="p17614mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row17615mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p17617mcpsimp"><a name="p17617mcpsimp"></a><a name="p17617mcpsimp"></a>public String getId()</p>
<p id="p17620mcpsimp"><a name="p17620mcpsimp"></a><a name="p17620mcpsimp"></a>Obtains the ID of a polygon on a map. The ID will be unique among all polygons on the map.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table17626mcpsimp"></a>
<table><thead align="left"><tr id="row17631mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p17633mcpsimp"><a name="p17633mcpsimp"></a><a name="p17633mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p17635mcpsimp"><a name="p17635mcpsimp"></a><a name="p17635mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row17636mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p17638mcpsimp"><a name="p17638mcpsimp"></a><a name="p17638mcpsimp"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p17640mcpsimp"><a name="p17640mcpsimp"></a><a name="p17640mcpsimp"></a>ID of a polygon.</p>
</td>
</tr>
</tbody>
</table>

## getPoints<a name="section1876512539146"></a>

<a name="table17642mcpsimp"></a>
<table><thead align="left"><tr id="row17646mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p17648mcpsimp"><a name="p17648mcpsimp"></a><a name="p17648mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row17649mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p17651mcpsimp"><a name="p17651mcpsimp"></a><a name="p17651mcpsimp"></a>public List&lt;<a href="latlng.md">LatLng</a>&gt; getPoints()</p>
<p id="p17654mcpsimp"><a name="p17654mcpsimp"></a><a name="p17654mcpsimp"></a>Obtains the vertex set of a polygon.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table17660mcpsimp"></a>
<table><thead align="left"><tr id="row17665mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p17667mcpsimp"><a name="p17667mcpsimp"></a><a name="p17667mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p17669mcpsimp"><a name="p17669mcpsimp"></a><a name="p17669mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row17670mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p17672mcpsimp"><a name="p17672mcpsimp"></a><a name="p17672mcpsimp"></a>List&lt;<a href="latlng.md">LatLng</a>&gt;</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p17674mcpsimp"><a name="p17674mcpsimp"></a><a name="p17674mcpsimp"></a>Vertex set of a polygon.</p>
</td>
</tr>
</tbody>
</table>

## getStrokeColor<a name="section1874123281519"></a>

<a name="table17676mcpsimp"></a>
<table><thead align="left"><tr id="row17680mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p17682mcpsimp"><a name="p17682mcpsimp"></a><a name="p17682mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row17683mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p17685mcpsimp"><a name="p17685mcpsimp"></a><a name="p17685mcpsimp"></a>public int getStrokeColor()</p>
<p id="p17688mcpsimp"><a name="p17688mcpsimp"></a><a name="p17688mcpsimp"></a>Obtains the stroke color of a polygon's outline, in ARGB format.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table17694mcpsimp"></a>
<table><thead align="left"><tr id="row17699mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p17701mcpsimp"><a name="p17701mcpsimp"></a><a name="p17701mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p17703mcpsimp"><a name="p17703mcpsimp"></a><a name="p17703mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row17704mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p17706mcpsimp"><a name="p17706mcpsimp"></a><a name="p17706mcpsimp"></a>int</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p17708mcpsimp"><a name="p17708mcpsimp"></a><a name="p17708mcpsimp"></a>Color in ARGB format.</p>
</td>
</tr>
</tbody>
</table>

## getStrokeJointType<a name="section65261817181613"></a>

<a name="table17710mcpsimp"></a>
<table><thead align="left"><tr id="row17714mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p17716mcpsimp"><a name="p17716mcpsimp"></a><a name="p17716mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row17717mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p17719mcpsimp"><a name="p17719mcpsimp"></a><a name="p17719mcpsimp"></a>public int getStrokeJointType()</p>
<p id="p17722mcpsimp"><a name="p17722mcpsimp"></a><a name="p17722mcpsimp"></a>Obtains the joint type of a polygon.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table17728mcpsimp"></a>
<table><thead align="left"><tr id="row17733mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p17735mcpsimp"><a name="p17735mcpsimp"></a><a name="p17735mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p17737mcpsimp"><a name="p17737mcpsimp"></a><a name="p17737mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row17738mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p17740mcpsimp"><a name="p17740mcpsimp"></a><a name="p17740mcpsimp"></a>int</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p17742mcpsimp"><a name="p17742mcpsimp"></a><a name="p17742mcpsimp"></a>Joint type of a polygon.</p>
</td>
</tr>
</tbody>
</table>

## getStrokePattern<a name="section2866846121612"></a>

<a name="table17744mcpsimp"></a>
<table><thead align="left"><tr id="row17748mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p17750mcpsimp"><a name="p17750mcpsimp"></a><a name="p17750mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row17751mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p17753mcpsimp"><a name="p17753mcpsimp"></a><a name="p17753mcpsimp"></a>public List&lt;<a href="patternitem.md">PatternItem</a>&gt; getStrokePattern()</p>
<p id="p17756mcpsimp"><a name="p17756mcpsimp"></a><a name="p17756mcpsimp"></a>Obtains the stroke pattern of a polygon's outline.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table17762mcpsimp"></a>
<table><thead align="left"><tr id="row17767mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p17769mcpsimp"><a name="p17769mcpsimp"></a><a name="p17769mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p17771mcpsimp"><a name="p17771mcpsimp"></a><a name="p17771mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row17772mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p17774mcpsimp"><a name="p17774mcpsimp"></a><a name="p17774mcpsimp"></a>List&lt;<a href="patternitem.md">PatternItem</a>&gt;</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p17776mcpsimp"><a name="p17776mcpsimp"></a><a name="p17776mcpsimp"></a>Stroke pattern of a polygon's outline.</p>
</td>
</tr>
</tbody>
</table>

## getStrokeWidth<a name="section850172711172"></a>

<a name="table17778mcpsimp"></a>
<table><thead align="left"><tr id="row17782mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p17784mcpsimp"><a name="p17784mcpsimp"></a><a name="p17784mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row17785mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p17787mcpsimp"><a name="p17787mcpsimp"></a><a name="p17787mcpsimp"></a>public float getStrokeWidth()</p>
<p id="p744214113176"><a name="p744214113176"></a><a name="p744214113176"></a>Obtains the stroke width of a polygon's outline, in pixels.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table17796mcpsimp"></a>
<table><thead align="left"><tr id="row17801mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p17803mcpsimp"><a name="p17803mcpsimp"></a><a name="p17803mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p17805mcpsimp"><a name="p17805mcpsimp"></a><a name="p17805mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row17806mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p17808mcpsimp"><a name="p17808mcpsimp"></a><a name="p17808mcpsimp"></a>float</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p17810mcpsimp"><a name="p17810mcpsimp"></a><a name="p17810mcpsimp"></a>Stroke width of a polygon's outline, in pixels.</p>
</td>
</tr>
</tbody>
</table>

## getTag<a name="section2054262111817"></a>

<a name="table17812mcpsimp"></a>
<table><thead align="left"><tr id="row17816mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p17818mcpsimp"><a name="p17818mcpsimp"></a><a name="p17818mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row17819mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p17821mcpsimp"><a name="p17821mcpsimp"></a><a name="p17821mcpsimp"></a>public Object getTag()</p>
<p id="p3681102413187"><a name="p3681102413187"></a><a name="p3681102413187"></a>Obtains the <strong id="b2083554163517"><a name="b2083554163517"></a><a name="b2083554163517"></a>tag</strong> attribute (if it has been set) of a polygon. </p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table17830mcpsimp"></a>
<table><thead align="left"><tr id="row17835mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p17837mcpsimp"><a name="p17837mcpsimp"></a><a name="p17837mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p17839mcpsimp"><a name="p17839mcpsimp"></a><a name="p17839mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row17840mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p17842mcpsimp"><a name="p17842mcpsimp"></a><a name="p17842mcpsimp"></a>Object</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p17844mcpsimp"><a name="p17844mcpsimp"></a><a name="p17844mcpsimp"></a><strong id="b101294549019"><a name="b101294549019"></a><a name="b101294549019"></a>Object</strong> if a tag has been set; <strong id="b932914565019"><a name="b932914565019"></a><a name="b932914565019"></a>null</strong> otherwise.</p>
</td>
</tr>
</tbody>
</table>

## getZIndex<a name="section15792359171818"></a>

<a name="table17846mcpsimp"></a>
<table><thead align="left"><tr id="row17850mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p17852mcpsimp"><a name="p17852mcpsimp"></a><a name="p17852mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row17853mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p17855mcpsimp"><a name="p17855mcpsimp"></a><a name="p17855mcpsimp"></a>public float getZIndex()</p>
<p id="p17858mcpsimp"><a name="p17858mcpsimp"></a><a name="p17858mcpsimp"></a>Obtains the z-index of a polygon.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table17864mcpsimp"></a>
<table><thead align="left"><tr id="row17869mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p17871mcpsimp"><a name="p17871mcpsimp"></a><a name="p17871mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p17873mcpsimp"><a name="p17873mcpsimp"></a><a name="p17873mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row17874mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p17876mcpsimp"><a name="p17876mcpsimp"></a><a name="p17876mcpsimp"></a>float</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p17878mcpsimp"><a name="p17878mcpsimp"></a><a name="p17878mcpsimp"></a>Z-index, which indicates the overlapping order of a polygon.</p>
</td>
</tr>
</tbody>
</table>

## hashCode<a name="section6648437191917"></a>

<a name="table17880mcpsimp"></a>
<table><thead align="left"><tr id="row17884mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p17886mcpsimp"><a name="p17886mcpsimp"></a><a name="p17886mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row17887mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p17889mcpsimp"><a name="p17889mcpsimp"></a><a name="p17889mcpsimp"></a>public int hashCode()</p>
<p id="p17892mcpsimp"><a name="p17892mcpsimp"></a><a name="p17892mcpsimp"></a>Obtains the hash code of a polygon.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table17898mcpsimp"></a>
<table><thead align="left"><tr id="row17903mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p17905mcpsimp"><a name="p17905mcpsimp"></a><a name="p17905mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p17907mcpsimp"><a name="p17907mcpsimp"></a><a name="p17907mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row17908mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p17910mcpsimp"><a name="p17910mcpsimp"></a><a name="p17910mcpsimp"></a>int</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p17912mcpsimp"><a name="p17912mcpsimp"></a><a name="p17912mcpsimp"></a>Hash code of a polygon.</p>
</td>
</tr>
</tbody>
</table>

## isClickable<a name="section163616732011"></a>

<a name="table17914mcpsimp"></a>
<table><thead align="left"><tr id="row17918mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p17920mcpsimp"><a name="p17920mcpsimp"></a><a name="p17920mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row17921mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p17923mcpsimp"><a name="p17923mcpsimp"></a><a name="p17923mcpsimp"></a>public boolean isClickable()</p>
<p id="p17926mcpsimp"><a name="p17926mcpsimp"></a><a name="p17926mcpsimp"></a>Checks whether a polygon is tappable.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table17932mcpsimp"></a>
<table><thead align="left"><tr id="row17937mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p17939mcpsimp"><a name="p17939mcpsimp"></a><a name="p17939mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p17941mcpsimp"><a name="p17941mcpsimp"></a><a name="p17941mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row17942mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p17944mcpsimp"><a name="p17944mcpsimp"></a><a name="p17944mcpsimp"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p17946mcpsimp"><a name="p17946mcpsimp"></a><a name="p17946mcpsimp"></a><strong id="b131455392118"><a name="b131455392118"></a><a name="b131455392118"></a>true</strong> if a polygon is tappable; <strong id="b1313912283113"><a name="b1313912283113"></a><a name="b1313912283113"></a>false</strong> otherwise.</p>
</td>
</tr>
</tbody>
</table>

## isGeodesic<a name="section94211744162019"></a>

<a name="table17948mcpsimp"></a>
<table><thead align="left"><tr id="row17952mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p17954mcpsimp"><a name="p17954mcpsimp"></a><a name="p17954mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row17955mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p17957mcpsimp"><a name="p17957mcpsimp"></a><a name="p17957mcpsimp"></a>public boolean isGeodesic()</p>
<p id="p46821557212"><a name="p46821557212"></a><a name="p46821557212"></a>Checks whether each segment of a polygon is drawn as a geodesic.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table17966mcpsimp"></a>
<table><thead align="left"><tr id="row17971mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p17973mcpsimp"><a name="p17973mcpsimp"></a><a name="p17973mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p17975mcpsimp"><a name="p17975mcpsimp"></a><a name="p17975mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row17976mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p17978mcpsimp"><a name="p17978mcpsimp"></a><a name="p17978mcpsimp"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p17980mcpsimp"><a name="p17980mcpsimp"></a><a name="p17980mcpsimp"></a><strong id="b6536523415"><a name="b6536523415"></a><a name="b6536523415"></a>true</strong> if each segment is drawn as a geodesic; <strong id="b82770551336"><a name="b82770551336"></a><a name="b82770551336"></a>false</strong> otherwise.</p>
</td>
</tr>
</tbody>
</table>

## isVisible<a name="section2092752502116"></a>

<a name="table17982mcpsimp"></a>
<table><thead align="left"><tr id="row17986mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p17988mcpsimp"><a name="p17988mcpsimp"></a><a name="p17988mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row17989mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p17991mcpsimp"><a name="p17991mcpsimp"></a><a name="p17991mcpsimp"></a>public boolean isVisible()</p>
<p id="p17994mcpsimp"><a name="p17994mcpsimp"></a><a name="p17994mcpsimp"></a>Checks whether a polygon is visible.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table18000mcpsimp"></a>
<table><thead align="left"><tr id="row18005mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p18007mcpsimp"><a name="p18007mcpsimp"></a><a name="p18007mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p18009mcpsimp"><a name="p18009mcpsimp"></a><a name="p18009mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row18010mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p18012mcpsimp"><a name="p18012mcpsimp"></a><a name="p18012mcpsimp"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p18014mcpsimp"><a name="p18014mcpsimp"></a><a name="p18014mcpsimp"></a><strong id="b172212280415"><a name="b172212280415"></a><a name="b172212280415"></a>true</strong> if the polyline is visible; <strong id="b1584912171448"><a name="b1584912171448"></a><a name="b1584912171448"></a>false</strong> otherwise.</p>
</td>
</tr>
</tbody>
</table>

## remove<a name="section81662315221"></a>

<a name="table18016mcpsimp"></a>
<table><thead align="left"><tr id="row18020mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p18022mcpsimp"><a name="p18022mcpsimp"></a><a name="p18022mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row18023mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p18025mcpsimp"><a name="p18025mcpsimp"></a><a name="p18025mcpsimp"></a>public void remove()</p>
<p id="p56801826132218"><a name="p56801826132218"></a><a name="p56801826132218"></a>Removes a polygon from a map.</p>
</td>
</tr>
</tbody>
</table>

## setClickable<a name="section151966234239"></a>

<a name="table18036mcpsimp"></a>
<table><thead align="left"><tr id="row18040mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p18042mcpsimp"><a name="p18042mcpsimp"></a><a name="p18042mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row18043mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p18045mcpsimp"><a name="p18045mcpsimp"></a><a name="p18045mcpsimp"></a>public void setClickable(boolean clickable)</p>
<p id="p192380375233"><a name="p192380375233"></a><a name="p192380375233"></a>Sets whether a polygon is tappable.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table18051mcpsimp"></a>
<table><thead align="left"><tr id="row18056mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p18058mcpsimp"><a name="p18058mcpsimp"></a><a name="p18058mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p18060mcpsimp"><a name="p18060mcpsimp"></a><a name="p18060mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row18061mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p18063mcpsimp"><a name="p18063mcpsimp"></a><a name="p18063mcpsimp"></a>clickable</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p18065mcpsimp"><a name="p18065mcpsimp"></a><a name="p18065mcpsimp"></a>Indicates whether a polygon is tappable. <strong id="b175807541440"><a name="b175807541440"></a><a name="b175807541440"></a>true</strong>: yes; <strong id="b1158935416414"><a name="b1158935416414"></a><a name="b1158935416414"></a>false</strong>: no. The default value is <strong id="b23318161439"><a name="b23318161439"></a><a name="b23318161439"></a>false</strong>.</p>
</td>
</tr>
</tbody>
</table>

## setFillColor<a name="section10729185902319"></a>

<a name="table18070mcpsimp"></a>
<table><thead align="left"><tr id="row18074mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p18076mcpsimp"><a name="p18076mcpsimp"></a><a name="p18076mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row18077mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p18079mcpsimp"><a name="p18079mcpsimp"></a><a name="p18079mcpsimp"></a>public void setFillColor(int color)</p>
<p id="p18082mcpsimp"><a name="p18082mcpsimp"></a><a name="p18082mcpsimp"></a>Sets the fill color of a polygon.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table18085mcpsimp"></a>
<table><thead align="left"><tr id="row18090mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p18092mcpsimp"><a name="p18092mcpsimp"></a><a name="p18092mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p18094mcpsimp"><a name="p18094mcpsimp"></a><a name="p18094mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row18095mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p18097mcpsimp"><a name="p18097mcpsimp"></a><a name="p18097mcpsimp"></a>color</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p18099mcpsimp"><a name="p18099mcpsimp"></a><a name="p18099mcpsimp"></a>Color in ARGB format. By default, the fill color is transparent (0x00000000).</p>
</td>
</tr>
</tbody>
</table>

## setGeodesic<a name="section655394202410"></a>

<a name="table18104mcpsimp"></a>
<table><thead align="left"><tr id="row18108mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p18110mcpsimp"><a name="p18110mcpsimp"></a><a name="p18110mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row18111mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p18113mcpsimp"><a name="p18113mcpsimp"></a><a name="p18113mcpsimp"></a>public void setGeodesic(boolean geodesic)</p>
<p id="p18116mcpsimp"><a name="p18116mcpsimp"></a><a name="p18116mcpsimp"></a>Sets whether to draw each segment of a polygon as a geodesic.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table18119mcpsimp"></a>
<table><thead align="left"><tr id="row18124mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p18126mcpsimp"><a name="p18126mcpsimp"></a><a name="p18126mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p18128mcpsimp"><a name="p18128mcpsimp"></a><a name="p18128mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row18129mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p18131mcpsimp"><a name="p18131mcpsimp"></a><a name="p18131mcpsimp"></a>geodesic</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p18133mcpsimp"><a name="p18133mcpsimp"></a><a name="p18133mcpsimp"></a>Indicates whether to draw each segment of a polygon as a geodesic. <strong id="b457619534619"><a name="b457619534619"></a><a name="b457619534619"></a>true</strong>: yes; <strong id="b758735315610"><a name="b758735315610"></a><a name="b758735315610"></a>false</strong>: no. The default value is <strong id="b113160125616"><a name="b113160125616"></a><a name="b113160125616"></a>false</strong>.</p>
</td>
</tr>
</tbody>
</table>

## setHoles<a name="section2803142417253"></a>

<a name="table18138mcpsimp"></a>
<table><thead align="left"><tr id="row18142mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p18144mcpsimp"><a name="p18144mcpsimp"></a><a name="p18144mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row18145mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p18147mcpsimp"><a name="p18147mcpsimp"></a><a name="p18147mcpsimp"></a>public void setHoles(List&lt;? extends List&lt;<a href="latlng.md">LatLng</a>&gt;&gt; holes)</p>
<p id="p3418194222516"><a name="p3418194222516"></a><a name="p3418194222516"></a>Sets holes in a polygon.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table18153mcpsimp"></a>
<table><thead align="left"><tr id="row18158mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p18160mcpsimp"><a name="p18160mcpsimp"></a><a name="p18160mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p18162mcpsimp"><a name="p18162mcpsimp"></a><a name="p18162mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row18163mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p18165mcpsimp"><a name="p18165mcpsimp"></a><a name="p18165mcpsimp"></a>holes</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p18167mcpsimp"><a name="p18167mcpsimp"></a><a name="p18167mcpsimp"></a>Hole list. Each hole is a <a href="latlng.md">LatLng</a> list.</p>
</td>
</tr>
</tbody>
</table>

## setPoints<a name="section1826199122616"></a>

<a name="table18172mcpsimp"></a>
<table><thead align="left"><tr id="row18176mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p18178mcpsimp"><a name="p18178mcpsimp"></a><a name="p18178mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row18179mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p18181mcpsimp"><a name="p18181mcpsimp"></a><a name="p18181mcpsimp"></a>public void setPoints(List&lt;<a href="latlng.md">LatLng</a>&gt; points)</p>
<p id="p13262172332617"><a name="p13262172332617"></a><a name="p13262172332617"></a>Sets vertex coordinates of a polygon.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table18187mcpsimp"></a>
<table><thead align="left"><tr id="row18192mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p18194mcpsimp"><a name="p18194mcpsimp"></a><a name="p18194mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p18196mcpsimp"><a name="p18196mcpsimp"></a><a name="p18196mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row18197mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p18199mcpsimp"><a name="p18199mcpsimp"></a><a name="p18199mcpsimp"></a>points</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p18201mcpsimp"><a name="p18201mcpsimp"></a><a name="p18201mcpsimp"></a>Vertex coordinate set.</p>
</td>
</tr>
</tbody>
</table>

## setStrokeColor<a name="section14513438269"></a>

<a name="table18206mcpsimp"></a>
<table><thead align="left"><tr id="row18210mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p18212mcpsimp"><a name="p18212mcpsimp"></a><a name="p18212mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row18213mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p18215mcpsimp"><a name="p18215mcpsimp"></a><a name="p18215mcpsimp"></a>public void setStrokeColor(int color)</p>
<p id="p87419414274"><a name="p87419414274"></a><a name="p87419414274"></a>Sets the stroke color of a polygon's outline.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table18221mcpsimp"></a>
<table><thead align="left"><tr id="row18226mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p18228mcpsimp"><a name="p18228mcpsimp"></a><a name="p18228mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p18230mcpsimp"><a name="p18230mcpsimp"></a><a name="p18230mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row18231mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p18233mcpsimp"><a name="p18233mcpsimp"></a><a name="p18233mcpsimp"></a>color</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p18235mcpsimp"><a name="p18235mcpsimp"></a><a name="p18235mcpsimp"></a>Color in ARGB format. By default, the stroke color is black (0xff000000).</p>
</td>
</tr>
</tbody>
</table>

## setStrokeJointType<a name="section283222602715"></a>

<a name="table18240mcpsimp"></a>
<table><thead align="left"><tr id="row18244mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p18246mcpsimp"><a name="p18246mcpsimp"></a><a name="p18246mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row18247mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p18249mcpsimp"><a name="p18249mcpsimp"></a><a name="p18249mcpsimp"></a>public void setStrokeJointType(int jointType)</p>
<p id="p18252mcpsimp"><a name="p18252mcpsimp"></a><a name="p18252mcpsimp"></a>Sets the joint type of a polygon.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table18255mcpsimp"></a>
<table><thead align="left"><tr id="row18260mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p18262mcpsimp"><a name="p18262mcpsimp"></a><a name="p18262mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p18264mcpsimp"><a name="p18264mcpsimp"></a><a name="p18264mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row18265mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p18267mcpsimp"><a name="p18267mcpsimp"></a><a name="p18267mcpsimp"></a>jointType</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p18269mcpsimp"><a name="p18269mcpsimp"></a><a name="p18269mcpsimp"></a>Joint type. The default value is <a href="jointtype.md#section103572813326">DEFAULT</a>.</p>
</td>
</tr>
</tbody>
</table>

## setStrokePattern<a name="section1218011417281"></a>

<a name="table18274mcpsimp"></a>
<table><thead align="left"><tr id="row18278mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p18280mcpsimp"><a name="p18280mcpsimp"></a><a name="p18280mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row18281mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p18283mcpsimp"><a name="p18283mcpsimp"></a><a name="p18283mcpsimp"></a>public void setStrokePattern(List&lt;<a href="patternitem.md">PatternItem</a>&gt; pattern)</p>
<p id="p18286mcpsimp"><a name="p18286mcpsimp"></a><a name="p18286mcpsimp"></a>Sets the stroke pattern of a polygon's outline.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table18289mcpsimp"></a>
<table><thead align="left"><tr id="row18294mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p18296mcpsimp"><a name="p18296mcpsimp"></a><a name="p18296mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p18298mcpsimp"><a name="p18298mcpsimp"></a><a name="p18298mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row18299mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p18301mcpsimp"><a name="p18301mcpsimp"></a><a name="p18301mcpsimp"></a>pattern</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p18303mcpsimp"><a name="p18303mcpsimp"></a><a name="p18303mcpsimp"></a><a href="patternitem.md">PatternItem</a> object set. The default value is <strong id="b159471639939"><a name="b159471639939"></a><a name="b159471639939"></a>null</strong>, indicating that the stroke is in the solid pattern. </p>
</td>
</tr>
</tbody>
</table>

## setStrokeWidth<a name="section11113144212284"></a>

<a name="table18308mcpsimp"></a>
<table><thead align="left"><tr id="row18312mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p18314mcpsimp"><a name="p18314mcpsimp"></a><a name="p18314mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row18315mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p18317mcpsimp"><a name="p18317mcpsimp"></a><a name="p18317mcpsimp"></a>public void setStrokeWidth(float width)</p>
<p id="p18320mcpsimp"><a name="p18320mcpsimp"></a><a name="p18320mcpsimp"></a>Sets the stroke width of a polygon's outline.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table18325mcpsimp"></a>
<table><thead align="left"><tr id="row18330mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p18332mcpsimp"><a name="p18332mcpsimp"></a><a name="p18332mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p18334mcpsimp"><a name="p18334mcpsimp"></a><a name="p18334mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row18335mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p18337mcpsimp"><a name="p18337mcpsimp"></a><a name="p18337mcpsimp"></a>width</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p18339mcpsimp"><a name="p18339mcpsimp"></a><a name="p18339mcpsimp"></a>Stroke width, in pixels. The default value is <strong id="b1842419371180"><a name="b1842419371180"></a><a name="b1842419371180"></a>10</strong>.</p>
</td>
</tr>
</tbody>
</table>

## setTag<a name="section72874203297"></a>

<a name="table18344mcpsimp"></a>
<table><thead align="left"><tr id="row18348mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p18350mcpsimp"><a name="p18350mcpsimp"></a><a name="p18350mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row18351mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p18353mcpsimp"><a name="p18353mcpsimp"></a><a name="p18353mcpsimp"></a>public void setTag(Object tag)</p>
<p id="p18356mcpsimp"><a name="p18356mcpsimp"></a><a name="p18356mcpsimp"></a>Sets the <strong id="b158811249135916"><a name="b158811249135916"></a><a name="b158811249135916"></a>tag</strong> attribute of a polygon. If <strong id="b1262012423819"><a name="b1262012423819"></a><a name="b1262012423819"></a>null</strong> is passed, the <strong id="b1494816312019"><a name="b1494816312019"></a><a name="b1494816312019"></a>tag</strong> attribute will be cleared.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table18359mcpsimp"></a>
<table><thead align="left"><tr id="row18364mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p18366mcpsimp"><a name="p18366mcpsimp"></a><a name="p18366mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p18368mcpsimp"><a name="p18368mcpsimp"></a><a name="p18368mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row18369mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p18371mcpsimp"><a name="p18371mcpsimp"></a><a name="p18371mcpsimp"></a>tag</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p18373mcpsimp"><a name="p18373mcpsimp"></a><a name="p18373mcpsimp"></a>Tag of a polygon.</p>
</td>
</tr>
</tbody>
</table>

## setVisible<a name="section15486012306"></a>

<a name="table18378mcpsimp"></a>
<table><thead align="left"><tr id="row18382mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p18384mcpsimp"><a name="p18384mcpsimp"></a><a name="p18384mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row18385mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p18387mcpsimp"><a name="p18387mcpsimp"></a><a name="p18387mcpsimp"></a>public void setVisible(boolean visible)</p>
<p id="p1685611293012"><a name="p1685611293012"></a><a name="p1685611293012"></a>Sets whether a polygon is visible. If the polygon is invisible, it will not be drawn but all other states will be preserved.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table18393mcpsimp"></a>
<table><thead align="left"><tr id="row18398mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p18400mcpsimp"><a name="p18400mcpsimp"></a><a name="p18400mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p18402mcpsimp"><a name="p18402mcpsimp"></a><a name="p18402mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row18403mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p18405mcpsimp"><a name="p18405mcpsimp"></a><a name="p18405mcpsimp"></a>visible</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p18407mcpsimp"><a name="p18407mcpsimp"></a><a name="p18407mcpsimp"></a>Indicates whether a polygon is visible. By default, a polygon is visible.</p>
</td>
</tr>
</tbody>
</table>

## setZIndex<a name="section1650733317309"></a>

<a name="table18412mcpsimp"></a>
<table><thead align="left"><tr id="row18416mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p18418mcpsimp"><a name="p18418mcpsimp"></a><a name="p18418mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row18419mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p18421mcpsimp"><a name="p18421mcpsimp"></a><a name="p18421mcpsimp"></a>public void setZIndex(float zIndex)</p>
<p id="p18424mcpsimp"><a name="p18424mcpsimp"></a><a name="p18424mcpsimp"></a>Sets the z-index of a polygon. The z-index indicates the overlapping order of a polygon. A polygon with a larger z-index overlaps that with a smaller z-index. Polygons with the same z-index overlap each other by the order in which they are added.</p>
<div class="note" id="note1361582435918"><a name="note1361582435918"></a><a name="note1361582435918"></a><span class="notetitle"> NOTE: </span><div class="notebody"><p id="p1615024165911"><a name="p1615024165911"></a><a name="p1615024165911"></a>The following formula must be met: Number of circles and polygons x 2 + Number of polylines and ground overlays ≤ 1450. If the formula is not met, overlapping errors may occur. </p>
</div></div>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table18427mcpsimp"></a>
<table><thead align="left"><tr id="row18432mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p18434mcpsimp"><a name="p18434mcpsimp"></a><a name="p18434mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p18436mcpsimp"><a name="p18436mcpsimp"></a><a name="p18436mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row18437mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p18439mcpsimp"><a name="p18439mcpsimp"></a><a name="p18439mcpsimp"></a>zIndex</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p18441mcpsimp"><a name="p18441mcpsimp"></a><a name="p18441mcpsimp"></a>Z-index, which indicates the overlapping order of a polygon. By default, the z-index is 0.</p>
</td>
</tr>
</tbody>
</table>

