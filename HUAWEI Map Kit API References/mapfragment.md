# MapFragment<a name="EN-US_TOPIC_0000001145781021"></a>

-   [Public Constructor Summary](#section72451811103710)
-   [Public Method Summary](#section125626395378)
-   [Public Methods](#section45609464375)
-   [getMapAsync](#section11704105017376)
-   [newInstance\(\)](#section85072163815)
-   [newInstance\(HuaweiMapOptions options\)](#section2225611183820)
-   [onActivityCreated](#section98871329193810)
-   [onAttach](#section15213513515)
-   [onCreate](#section137918240516)
-   [onCreateView](#section113001834165120)
-   [onDestroy](#section387435115512)
-   [onDestroyView](#section12346216526)
-   [onInflate](#section18462711115217)
-   [onLowMemory](#section8571102125210)
-   [onPause](#section162873275220)
-   [onResume](#section324514414524)
-   [onSaveInstanceState](#section1892975212522)
-   [onStart](#section56688365318)
-   [onStop](#section4940112185318)
-   [setArguments](#section1188015215533)


<a name="table6438mcpsimp"></a>
<table><thead align="left"><tr id="row6442mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p6444mcpsimp"><a name="p6444mcpsimp"></a><a name="p6444mcpsimp"></a>Class Info</p>
</th>
</tr>
</thead>
<tbody><tr id="row6445mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p9350141214263"><a name="p9350141214263"></a><a name="p9350141214263"></a>public class MapFragment</p>
<p id="p211764432715"><a name="p211764432715"></a><a name="p211764432715"></a>Map component that extends the native <strong id="b2048918513414"><a name="b2048918513414"></a><a name="b2048918513414"></a>Fragment</strong> component of Android and can be used to add a map to an app in the simplest way. It provides a view of a map to automatically process the necessary lifecycle functions, and can be loaded to the layout file of <strong id="b837088163711"><a name="b837088163711"></a><a name="b837088163711"></a>Activity</strong> for use. To automatically initialize the map system and view, call <a href="#section11704105017376">getMapAsync</a>.</p>
</td>
</tr>
</tbody>
</table>

## Public Constructor Summary<a name="section72451811103710"></a>

<a name="table6451mcpsimp"></a>
<table><thead align="left"><tr id="row6455mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p6457mcpsimp"><a name="p6457mcpsimp"></a><a name="p6457mcpsimp"></a>Constructor Name</p>
</th>
</tr>
</thead>
<tbody><tr id="row6458mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p6460mcpsimp"><a name="p6460mcpsimp"></a><a name="p6460mcpsimp"></a><a href="mapfragment.md">MapFragment</a>()</p>
<p id="p5909323113313"><a name="p5909323113313"></a><a name="p5909323113313"></a>Default constructor of <strong id="b143444141105"><a name="b143444141105"></a><a name="b143444141105"></a>MapFragment</strong>.</p>
</td>
</tr>
</tbody>
</table>

## Public Method Summary<a name="section125626395378"></a>

<a name="table6462mcpsimp"></a>
<table><thead align="left"><tr id="row6467mcpsimp"><th class="cellrowborder" valign="top" width="40%" id="mcps1.1.3.1.1"><p id="p6469mcpsimp"><a name="p6469mcpsimp"></a><a name="p6469mcpsimp"></a>Qualifier and Type</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.1.3.1.2"><p id="p6471mcpsimp"><a name="p6471mcpsimp"></a><a name="p6471mcpsimp"></a>Method Name and Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row6472mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p6474mcpsimp"><a name="p6474mcpsimp"></a><a name="p6474mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p6476mcpsimp"><a name="p6476mcpsimp"></a><a name="p6476mcpsimp"></a><a href="#section11704105017376">getMapAsync</a>(<a href="onmapreadycallback.md">OnMapReadyCallback</a> callback)</p>
<p id="p182621015204320"><a name="p182621015204320"></a><a name="p182621015204320"></a>Obtains a <a href="huaweimap.md">HuaweiMap</a> object when the object is ready. </p>
</td>
</tr>
<tr id="row1557917311359"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p6484mcpsimp"><a name="p6484mcpsimp"></a><a name="p6484mcpsimp"></a>static <a href="mapfragment.md">MapFragment</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p6486mcpsimp"><a name="p6486mcpsimp"></a><a name="p6486mcpsimp"></a><a href="#section85072163815">newInstance</a>()</p>
<p id="p844291604316"><a name="p844291604316"></a><a name="p844291604316"></a>Creates a <a href="mapfragment.md">MapFragment</a> object with default attributes.</p>
</td>
</tr>
<tr id="row6477mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p6479mcpsimp"><a name="p6479mcpsimp"></a><a name="p6479mcpsimp"></a>static <a href="mapfragment.md">MapFragment</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p6481mcpsimp"><a name="p6481mcpsimp"></a><a name="p6481mcpsimp"></a><a href="#section2225611183820">newInstance</a>(<a href="huaweimapooptions.md">HuaweiMapOptions</a> options)</p>
<p id="p198591817104311"><a name="p198591817104311"></a><a name="p198591817104311"></a>Creates a <a href="mapfragment.md">MapFragment</a> object based on the specified <strong id="b25385455281"><a name="b25385455281"></a><a name="b25385455281"></a>options</strong> parameter.</p>
</td>
</tr>
<tr id="row6487mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p6489mcpsimp"><a name="p6489mcpsimp"></a><a name="p6489mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p6491mcpsimp"><a name="p6491mcpsimp"></a><a name="p6491mcpsimp"></a><a href="#section98871329193810">onActivityCreated</a>(Bundle savedInstanceState)</p>
<p id="p1710861912439"><a name="p1710861912439"></a><a name="p1710861912439"></a>Lifecycle method inherited from <strong id="b77267312911"><a name="b77267312911"></a><a name="b77267312911"></a>Fragment</strong>.</p>
</td>
</tr>
<tr id="row6492mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p6494mcpsimp"><a name="p6494mcpsimp"></a><a name="p6494mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p6496mcpsimp"><a name="p6496mcpsimp"></a><a name="p6496mcpsimp"></a><a href="#section15213513515">onAttach</a>(Activity activity)</p>
<p id="p97316209437"><a name="p97316209437"></a><a name="p97316209437"></a>Lifecycle method inherited from <strong id="b61921131122918"><a name="b61921131122918"></a><a name="b61921131122918"></a>Fragment</strong>.</p>
</td>
</tr>
<tr id="row6497mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p6499mcpsimp"><a name="p6499mcpsimp"></a><a name="p6499mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p6501mcpsimp"><a name="p6501mcpsimp"></a><a name="p6501mcpsimp"></a><a href="#section137918240516">onCreate</a>(Bundle savedInstanceState)</p>
<p id="p1025312215434"><a name="p1025312215434"></a><a name="p1025312215434"></a>Lifecycle method inherited from <strong id="b116011637122918"><a name="b116011637122918"></a><a name="b116011637122918"></a>Fragment</strong>.</p>
</td>
</tr>
<tr id="row6502mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p6504mcpsimp"><a name="p6504mcpsimp"></a><a name="p6504mcpsimp"></a>View</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p6506mcpsimp"><a name="p6506mcpsimp"></a><a name="p6506mcpsimp"></a><a href="#section113001834165120">onCreateView</a>(LayoutInflater inflater, ViewGroup container, Bundle savedInstanceState)</p>
<p id="p673512394319"><a name="p673512394319"></a><a name="p673512394319"></a>Lifecycle method inherited from <strong id="b106664016297"><a name="b106664016297"></a><a name="b106664016297"></a>Fragment</strong>.</p>
</td>
</tr>
<tr id="row6507mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p6509mcpsimp"><a name="p6509mcpsimp"></a><a name="p6509mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p6511mcpsimp"><a name="p6511mcpsimp"></a><a name="p6511mcpsimp"></a><a href="#section387435115512">onDestroy</a>()</p>
<p id="p11891112410435"><a name="p11891112410435"></a><a name="p11891112410435"></a>Lifecycle method inherited from <strong id="b18731242172911"><a name="b18731242172911"></a><a name="b18731242172911"></a>Fragment</strong>.</p>
</td>
</tr>
<tr id="row6512mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p6514mcpsimp"><a name="p6514mcpsimp"></a><a name="p6514mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p6516mcpsimp"><a name="p6516mcpsimp"></a><a name="p6516mcpsimp"></a><a href="#section12346216526">onDestroyView</a>()</p>
<p id="p11212112654316"><a name="p11212112654316"></a><a name="p11212112654316"></a>Lifecycle method inherited from <strong id="b75721644162919"><a name="b75721644162919"></a><a name="b75721644162919"></a>Fragment</strong>.</p>
</td>
</tr>
<tr id="row6527mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p6529mcpsimp"><a name="p6529mcpsimp"></a><a name="p6529mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p6531mcpsimp"><a name="p6531mcpsimp"></a><a name="p6531mcpsimp"></a><a href="#section18462711115217">onInflate</a>(Activity activity, AttributeSet attrs, Bundle savedInstanceState)</p>
<p id="p3623928134318"><a name="p3623928134318"></a><a name="p3623928134318"></a>Lifecycle method inherited from <strong id="b4848146142911"><a name="b4848146142911"></a><a name="b4848146142911"></a>Fragment</strong>. This method is called when <strong id="b168481846122919"><a name="b168481846122919"></a><a name="b168481846122919"></a>Fragment</strong> is statically loaded in XML mode. </p>
</td>
</tr>
<tr id="row6532mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p6534mcpsimp"><a name="p6534mcpsimp"></a><a name="p6534mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p6536mcpsimp"><a name="p6536mcpsimp"></a><a name="p6536mcpsimp"></a><a href="#section8571102125210">onLowMemory</a>()</p>
<p id="p1674262904316"><a name="p1674262904316"></a><a name="p1674262904316"></a>Lifecycle method inherited from <strong id="b1451983153015"><a name="b1451983153015"></a><a name="b1451983153015"></a>Fragment</strong>. This method is called when the memory is insufficient. </p>
</td>
</tr>
<tr id="row6537mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p6539mcpsimp"><a name="p6539mcpsimp"></a><a name="p6539mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p6541mcpsimp"><a name="p6541mcpsimp"></a><a name="p6541mcpsimp"></a><a href="#section162873275220">onPause</a>()</p>
<p id="p367163094315"><a name="p367163094315"></a><a name="p367163094315"></a>Lifecycle method inherited from <strong id="b20741620173020"><a name="b20741620173020"></a><a name="b20741620173020"></a>Fragment</strong>.</p>
</td>
</tr>
<tr id="row6542mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p6544mcpsimp"><a name="p6544mcpsimp"></a><a name="p6544mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p6546mcpsimp"><a name="p6546mcpsimp"></a><a name="p6546mcpsimp"></a><a href="#section324514414524">onResume</a>()</p>
<p id="p1874731184317"><a name="p1874731184317"></a><a name="p1874731184317"></a>Lifecycle method inherited from <strong id="b9306192623012"><a name="b9306192623012"></a><a name="b9306192623012"></a>Fragment</strong>.</p>
</td>
</tr>
<tr id="row6547mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p6549mcpsimp"><a name="p6549mcpsimp"></a><a name="p6549mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p6551mcpsimp"><a name="p6551mcpsimp"></a><a name="p6551mcpsimp"></a><a href="#section1892975212522">onSaveInstanceState</a>(Bundle outState)</p>
<p id="p620423319439"><a name="p620423319439"></a><a name="p620423319439"></a>Lifecycle method inherited from <strong id="b1789132914304"><a name="b1789132914304"></a><a name="b1789132914304"></a>Fragment</strong> and called when <a href="mapfragment.md">MapFragment</a> is destroyed unexpectedly. It is used to save the status of a <a href="mapfragment.md">MapFragment</a> object before it is destroyed.</p>
</td>
</tr>
<tr id="row6552mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p6554mcpsimp"><a name="p6554mcpsimp"></a><a name="p6554mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p6556mcpsimp"><a name="p6556mcpsimp"></a><a name="p6556mcpsimp"></a><a href="#section56688365318">onStart</a>()</p>
<p id="p25255346433"><a name="p25255346433"></a><a name="p25255346433"></a>Lifecycle method inherited from <strong id="b394111612316"><a name="b394111612316"></a><a name="b394111612316"></a>Fragment</strong>.</p>
</td>
</tr>
<tr id="row6557mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p6559mcpsimp"><a name="p6559mcpsimp"></a><a name="p6559mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p6561mcpsimp"><a name="p6561mcpsimp"></a><a name="p6561mcpsimp"></a><a href="#section4940112185318">onStop</a>()</p>
<p id="p962443512435"><a name="p962443512435"></a><a name="p962443512435"></a>Lifecycle method inherited from <strong id="b18955718123113"><a name="b18955718123113"></a><a name="b18955718123113"></a>Fragment</strong>.</p>
</td>
</tr>
<tr id="row6562mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p6564mcpsimp"><a name="p6564mcpsimp"></a><a name="p6564mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p6566mcpsimp"><a name="p6566mcpsimp"></a><a name="p6566mcpsimp"></a><a href="#section1188015215533">setArguments</a>(Bundle args)</p>
<p id="p1184816360435"><a name="p1184816360435"></a><a name="p1184816360435"></a>Lifecycle method inherited from <strong id="b18820172119317"><a name="b18820172119317"></a><a name="b18820172119317"></a>Fragment</strong> and called when data needs to be passed to <a href="mapfragment.md">MapFragment</a>.</p>
</td>
</tr>
</tbody>
</table>

## Public Methods<a name="section45609464375"></a>

## getMapAsync<a name="section11704105017376"></a>

<a name="table6569mcpsimp"></a>
<table><thead align="left"><tr id="row6573mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p6575mcpsimp"><a name="p6575mcpsimp"></a><a name="p6575mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row6576mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p6578mcpsimp"><a name="p6578mcpsimp"></a><a name="p6578mcpsimp"></a>public void getMapAsync(<a href="onmapreadycallback.md">OnMapReadyCallback</a> callback)</p>
<p id="p6584mcpsimp"><a name="p6584mcpsimp"></a><a name="p6584mcpsimp"></a>Obtains a <a href="huaweimap.md">HuaweiMap</a> object when the object is ready. </p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table6587mcpsimp"></a>
<table><thead align="left"><tr id="row6592mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p6594mcpsimp"><a name="p6594mcpsimp"></a><a name="p6594mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p6596mcpsimp"><a name="p6596mcpsimp"></a><a name="p6596mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row6597mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p6599mcpsimp"><a name="p6599mcpsimp"></a><a name="p6599mcpsimp"></a>callback</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p6601mcpsimp"><a name="p6601mcpsimp"></a><a name="p6601mcpsimp"></a>Callback to be executed when a <a href="huaweimap.md">HuaweiMap</a> object is ready for use.</p>
</td>
</tr>
</tbody>
</table>

## newInstance\(\)<a name="section85072163815"></a>

<a name="table6654mcpsimp"></a>
<table><thead align="left"><tr id="row6658mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p6660mcpsimp"><a name="p6660mcpsimp"></a><a name="p6660mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row6661mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p6663mcpsimp"><a name="p6663mcpsimp"></a><a name="p6663mcpsimp"></a>public static <a href="mapfragment.md">MapFragment</a> newInstance()</p>
<p id="p6666mcpsimp"><a name="p6666mcpsimp"></a><a name="p6666mcpsimp"></a>Creates a <a href="mapfragment.md">MapFragment</a> object with default attributes.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table6672mcpsimp"></a>
<table><thead align="left"><tr id="row6677mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p6679mcpsimp"><a name="p6679mcpsimp"></a><a name="p6679mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p6681mcpsimp"><a name="p6681mcpsimp"></a><a name="p6681mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row6682mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p1757411580207"><a name="p1757411580207"></a><a name="p1757411580207"></a>MapFragment</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p6686mcpsimp"><a name="p6686mcpsimp"></a><a name="p6686mcpsimp"></a><a href="mapfragment.md">MapFragment</a> object.</p>
</td>
</tr>
</tbody>
</table>

## newInstance\(HuaweiMapOptions options\)<a name="section2225611183820"></a>

<a name="table6606mcpsimp"></a>
<table><thead align="left"><tr id="row6610mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p6612mcpsimp"><a name="p6612mcpsimp"></a><a name="p6612mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row6613mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p6615mcpsimp"><a name="p6615mcpsimp"></a><a name="p6615mcpsimp"></a>public static <a href="mapfragment.md">MapFragment</a> newInstance(<a href="huaweimapooptions.md">HuaweiMapOptions</a> options)</p>
<p id="p6618mcpsimp"><a name="p6618mcpsimp"></a><a name="p6618mcpsimp"></a>Creates a <a href="mapfragment.md">MapFragment</a> object based on the specified <strong id="b847113167015"><a name="b847113167015"></a><a name="b847113167015"></a>options</strong> parameter.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table6621mcpsimp"></a>
<table><thead align="left"><tr id="row6626mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p6628mcpsimp"><a name="p6628mcpsimp"></a><a name="p6628mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p6630mcpsimp"><a name="p6630mcpsimp"></a><a name="p6630mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row6631mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p6633mcpsimp"><a name="p6633mcpsimp"></a><a name="p6633mcpsimp"></a>options</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p6635mcpsimp"><a name="p6635mcpsimp"></a><a name="p6635mcpsimp"></a>Attributes required for creating a <a href="mapfragment.md">MapFragment</a> object.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table6638mcpsimp"></a>
<table><thead align="left"><tr id="row6643mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p6645mcpsimp"><a name="p6645mcpsimp"></a><a name="p6645mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p6647mcpsimp"><a name="p6647mcpsimp"></a><a name="p6647mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row6648mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p6650mcpsimp"><a name="p6650mcpsimp"></a><a name="p6650mcpsimp"></a>MapFragment</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p6652mcpsimp"><a name="p6652mcpsimp"></a><a name="p6652mcpsimp"></a><a href="mapfragment.md">MapFragment</a> object.</p>
</td>
</tr>
</tbody>
</table>

## onActivityCreated<a name="section98871329193810"></a>

<a name="table6688mcpsimp"></a>
<table><thead align="left"><tr id="row6692mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p6694mcpsimp"><a name="p6694mcpsimp"></a><a name="p6694mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row6695mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p6697mcpsimp"><a name="p6697mcpsimp"></a><a name="p6697mcpsimp"></a>public void onActivityCreated(Bundle savedInstanceState)</p>
<p id="p6700mcpsimp"><a name="p6700mcpsimp"></a><a name="p6700mcpsimp"></a>Lifecycle method inherited from <strong id="b5327314918"><a name="b5327314918"></a><a name="b5327314918"></a>Fragment</strong>.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table6703mcpsimp"></a>
<table><thead align="left"><tr id="row6708mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p6710mcpsimp"><a name="p6710mcpsimp"></a><a name="p6710mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p6712mcpsimp"><a name="p6712mcpsimp"></a><a name="p6712mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row6713mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p6715mcpsimp"><a name="p6715mcpsimp"></a><a name="p6715mcpsimp"></a>savedInstanceState</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p6717mcpsimp"><a name="p6717mcpsimp"></a><a name="p6717mcpsimp"></a>Status to be saved for a <a href="mapfragment.md">MapFragment</a> object.</p>
</td>
</tr>
</tbody>
</table>

## onAttach<a name="section15213513515"></a>

<a name="table6722mcpsimp"></a>
<table><thead align="left"><tr id="row6726mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p6728mcpsimp"><a name="p6728mcpsimp"></a><a name="p6728mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row6729mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p6731mcpsimp"><a name="p6731mcpsimp"></a><a name="p6731mcpsimp"></a>public void onAttach(Activity activity)</p>
<p id="p1418631193120"><a name="p1418631193120"></a><a name="p1418631193120"></a>Lifecycle method inherited from <strong id="b658315491523"><a name="b658315491523"></a><a name="b658315491523"></a>Fragment</strong>.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table6737mcpsimp"></a>
<table><thead align="left"><tr id="row6742mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p6744mcpsimp"><a name="p6744mcpsimp"></a><a name="p6744mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p6746mcpsimp"><a name="p6746mcpsimp"></a><a name="p6746mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row6747mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p6749mcpsimp"><a name="p6749mcpsimp"></a><a name="p6749mcpsimp"></a>activity</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p6751mcpsimp"><a name="p6751mcpsimp"></a><a name="p6751mcpsimp"></a>Activity object bound to <a href="mapfragment.md">MapFragment</a>.</p>
</td>
</tr>
</tbody>
</table>

## onCreate<a name="section137918240516"></a>

<a name="table6756mcpsimp"></a>
<table><thead align="left"><tr id="row6760mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p6762mcpsimp"><a name="p6762mcpsimp"></a><a name="p6762mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row6763mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p6765mcpsimp"><a name="p6765mcpsimp"></a><a name="p6765mcpsimp"></a>public void onCreate(Bundle savedInstanceState)</p>
<p id="p5116134218316"><a name="p5116134218316"></a><a name="p5116134218316"></a>Lifecycle method inherited from <strong id="b10826611849"><a name="b10826611849"></a><a name="b10826611849"></a>Fragment</strong>.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table6771mcpsimp"></a>
<table><thead align="left"><tr id="row6776mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p6778mcpsimp"><a name="p6778mcpsimp"></a><a name="p6778mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p6780mcpsimp"><a name="p6780mcpsimp"></a><a name="p6780mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row6781mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p6783mcpsimp"><a name="p6783mcpsimp"></a><a name="p6783mcpsimp"></a>savedInstanceState</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p6785mcpsimp"><a name="p6785mcpsimp"></a><a name="p6785mcpsimp"></a>Status to be saved for a <a href="mapfragment.md">MapFragment</a> object.</p>
</td>
</tr>
</tbody>
</table>

## onCreateView<a name="section113001834165120"></a>

<a name="table6790mcpsimp"></a>
<table><thead align="left"><tr id="row6794mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p6796mcpsimp"><a name="p6796mcpsimp"></a><a name="p6796mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row6797mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p6799mcpsimp"><a name="p6799mcpsimp"></a><a name="p6799mcpsimp"></a>public View onCreateView(LayoutInflater inflater, ViewGroup container, Bundle savedInstanceState)</p>
<p id="p6802mcpsimp"><a name="p6802mcpsimp"></a><a name="p6802mcpsimp"></a>Lifecycle method inherited from <strong id="b14782121345"><a name="b14782121345"></a><a name="b14782121345"></a>Fragment</strong>.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table6805mcpsimp"></a>
<table><thead align="left"><tr id="row6810mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p6812mcpsimp"><a name="p6812mcpsimp"></a><a name="p6812mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p6814mcpsimp"><a name="p6814mcpsimp"></a><a name="p6814mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row6815mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p6817mcpsimp"><a name="p6817mcpsimp"></a><a name="p6817mcpsimp"></a>inflater</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p6819mcpsimp"><a name="p6819mcpsimp"></a><a name="p6819mcpsimp"></a><strong id="b18922172519412"><a name="b18922172519412"></a><a name="b18922172519412"></a>LayoutInflater</strong> object, which is used to search for controls in a layout.</p>
</td>
</tr>
<tr id="row6820mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p6822mcpsimp"><a name="p6822mcpsimp"></a><a name="p6822mcpsimp"></a>container</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p6824mcpsimp"><a name="p6824mcpsimp"></a><a name="p6824mcpsimp"></a>Layout container.</p>
</td>
</tr>
<tr id="row6825mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p6827mcpsimp"><a name="p6827mcpsimp"></a><a name="p6827mcpsimp"></a>savedInstanceState</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p6829mcpsimp"><a name="p6829mcpsimp"></a><a name="p6829mcpsimp"></a>Status to be saved for a <a href="mapfragment.md">MapFragment</a> object.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table6832mcpsimp"></a>
<table><thead align="left"><tr id="row6837mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p6839mcpsimp"><a name="p6839mcpsimp"></a><a name="p6839mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p6841mcpsimp"><a name="p6841mcpsimp"></a><a name="p6841mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row6842mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p6844mcpsimp"><a name="p6844mcpsimp"></a><a name="p6844mcpsimp"></a>View</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p6846mcpsimp"><a name="p6846mcpsimp"></a><a name="p6846mcpsimp"></a><strong id="b461934314412"><a name="b461934314412"></a><a name="b461934314412"></a>View</strong> object.</p>
</td>
</tr>
</tbody>
</table>

## onDestroy<a name="section387435115512"></a>

<a name="table6848mcpsimp"></a>
<table><thead align="left"><tr id="row6852mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p6854mcpsimp"><a name="p6854mcpsimp"></a><a name="p6854mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row6855mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p6857mcpsimp"><a name="p6857mcpsimp"></a><a name="p6857mcpsimp"></a>public void onDestroy()</p>
<p id="p6860mcpsimp"><a name="p6860mcpsimp"></a><a name="p6860mcpsimp"></a>Lifecycle method inherited from <strong id="b359519481442"><a name="b359519481442"></a><a name="b359519481442"></a>Fragment</strong>.</p>
</td>
</tr>
</tbody>
</table>

## onDestroyView<a name="section12346216526"></a>

<a name="table6868mcpsimp"></a>
<table><thead align="left"><tr id="row6872mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p6874mcpsimp"><a name="p6874mcpsimp"></a><a name="p6874mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row6875mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p6877mcpsimp"><a name="p6877mcpsimp"></a><a name="p6877mcpsimp"></a>public void onDestroyView()</p>
<p id="p32031940173316"><a name="p32031940173316"></a><a name="p32031940173316"></a>Lifecycle method inherited from <strong id="b12151158542"><a name="b12151158542"></a><a name="b12151158542"></a>Fragment</strong>.</p>
</td>
</tr>
</tbody>
</table>

## onInflate<a name="section18462711115217"></a>

<a name="table6888mcpsimp"></a>
<table><thead align="left"><tr id="row6892mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p6894mcpsimp"><a name="p6894mcpsimp"></a><a name="p6894mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row6895mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p6897mcpsimp"><a name="p6897mcpsimp"></a><a name="p6897mcpsimp"></a>public void onInflate(Activity activity, AttributeSet attrs, Bundle savedInstanceState)</p>
<p id="p6900mcpsimp"><a name="p6900mcpsimp"></a><a name="p6900mcpsimp"></a>Lifecycle method inherited from <strong id="b8603133417585"><a name="b8603133417585"></a><a name="b8603133417585"></a>Fragment</strong>. This method is called when <strong id="b1221115133591"><a name="b1221115133591"></a><a name="b1221115133591"></a>Fragment</strong> is statically loaded in XML mode. </p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table6903mcpsimp"></a>
<table><thead align="left"><tr id="row6908mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p6910mcpsimp"><a name="p6910mcpsimp"></a><a name="p6910mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p6912mcpsimp"><a name="p6912mcpsimp"></a><a name="p6912mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row6913mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p6915mcpsimp"><a name="p6915mcpsimp"></a><a name="p6915mcpsimp"></a>activity</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p6917mcpsimp"><a name="p6917mcpsimp"></a><a name="p6917mcpsimp"></a>Activity object bound to <a href="mapfragment.md">MapFragment</a>.</p>
</td>
</tr>
<tr id="row6918mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p6920mcpsimp"><a name="p6920mcpsimp"></a><a name="p6920mcpsimp"></a>attrs</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p6922mcpsimp"><a name="p6922mcpsimp"></a><a name="p6922mcpsimp"></a>Attributes used to create a <a href="mapfragment.md">MapFragment</a> object.</p>
</td>
</tr>
<tr id="row6923mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p6925mcpsimp"><a name="p6925mcpsimp"></a><a name="p6925mcpsimp"></a>savedInstanceState</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p6927mcpsimp"><a name="p6927mcpsimp"></a><a name="p6927mcpsimp"></a>Status to be saved for a <a href="mapfragment.md">MapFragment</a> object.</p>
</td>
</tr>
</tbody>
</table>

## onLowMemory<a name="section8571102125210"></a>

<a name="table6932mcpsimp"></a>
<table><thead align="left"><tr id="row6936mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p6938mcpsimp"><a name="p6938mcpsimp"></a><a name="p6938mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row6939mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p6941mcpsimp"><a name="p6941mcpsimp"></a><a name="p6941mcpsimp"></a>public void onLowMemory()</p>
<p id="p1934183453515"><a name="p1934183453515"></a><a name="p1934183453515"></a>Lifecycle method inherited from <strong id="b0380153045916"><a name="b0380153045916"></a><a name="b0380153045916"></a>Fragment</strong>. This method is called when the memory is insufficient. </p>
</td>
</tr>
</tbody>
</table>

## onPause<a name="section162873275220"></a>

<a name="table6952mcpsimp"></a>
<table><thead align="left"><tr id="row6956mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p6958mcpsimp"><a name="p6958mcpsimp"></a><a name="p6958mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row6959mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p6961mcpsimp"><a name="p6961mcpsimp"></a><a name="p6961mcpsimp"></a>public void onPause()</p>
<p id="p676018153365"><a name="p676018153365"></a><a name="p676018153365"></a>Lifecycle method inherited from <strong id="b54713419620"><a name="b54713419620"></a><a name="b54713419620"></a>Fragment</strong>.</p>
</td>
</tr>
</tbody>
</table>

## onResume<a name="section324514414524"></a>

<a name="table6972mcpsimp"></a>
<table><thead align="left"><tr id="row6976mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p6978mcpsimp"><a name="p6978mcpsimp"></a><a name="p6978mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row6979mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p6981mcpsimp"><a name="p6981mcpsimp"></a><a name="p6981mcpsimp"></a>public void onResume()</p>
<p id="p16612752183617"><a name="p16612752183617"></a><a name="p16612752183617"></a>Lifecycle method inherited from <strong id="b562268665"><a name="b562268665"></a><a name="b562268665"></a>Fragment</strong>.</p>
</td>
</tr>
</tbody>
</table>

## onSaveInstanceState<a name="section1892975212522"></a>

<a name="table6992mcpsimp"></a>
<table><thead align="left"><tr id="row6996mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p6998mcpsimp"><a name="p6998mcpsimp"></a><a name="p6998mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row6999mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p7001mcpsimp"><a name="p7001mcpsimp"></a><a name="p7001mcpsimp"></a>public void onSaveInstanceState(Bundle outState)</p>
<p id="p1339922819371"><a name="p1339922819371"></a><a name="p1339922819371"></a>Method inherited from <strong id="b198311919466"><a name="b198311919466"></a><a name="b198311919466"></a>Fragment</strong> and called when <a href="mapfragment.md">MapFragment</a> is destroyed unexpectedly. It is used to save the status of a <a href="mapfragment.md">MapFragment</a> object before it is destroyed.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table7007mcpsimp"></a>
<table><thead align="left"><tr id="row7012mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p7014mcpsimp"><a name="p7014mcpsimp"></a><a name="p7014mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p7016mcpsimp"><a name="p7016mcpsimp"></a><a name="p7016mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row7017mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p7019mcpsimp"><a name="p7019mcpsimp"></a><a name="p7019mcpsimp"></a>outState</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p7021mcpsimp"><a name="p7021mcpsimp"></a><a name="p7021mcpsimp"></a>Status to be saved for a <a href="mapfragment.md">MapFragment</a> object.</p>
</td>
</tr>
</tbody>
</table>

## onStart<a name="section56688365318"></a>

<a name="table7026mcpsimp"></a>
<table><thead align="left"><tr id="row7030mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p7032mcpsimp"><a name="p7032mcpsimp"></a><a name="p7032mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row7033mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p7035mcpsimp"><a name="p7035mcpsimp"></a><a name="p7035mcpsimp"></a>public void onStart()</p>
<p id="p368297103818"><a name="p368297103818"></a><a name="p368297103818"></a>Lifecycle method inherited from <strong id="b65926913716"><a name="b65926913716"></a><a name="b65926913716"></a>Fragment</strong>.</p>
</td>
</tr>
</tbody>
</table>

## onStop<a name="section4940112185318"></a>

<a name="table7046mcpsimp"></a>
<table><thead align="left"><tr id="row7050mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p7052mcpsimp"><a name="p7052mcpsimp"></a><a name="p7052mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row7053mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p7055mcpsimp"><a name="p7055mcpsimp"></a><a name="p7055mcpsimp"></a>public void onStop()</p>
<p id="p7058mcpsimp"><a name="p7058mcpsimp"></a><a name="p7058mcpsimp"></a>Lifecycle method inherited from <strong id="b15301134915714"><a name="b15301134915714"></a><a name="b15301134915714"></a>Fragment</strong>.</p>
</td>
</tr>
</tbody>
</table>

## setArguments<a name="section1188015215533"></a>

<a name="table7066mcpsimp"></a>
<table><thead align="left"><tr id="row7070mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p7072mcpsimp"><a name="p7072mcpsimp"></a><a name="p7072mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row7073mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p7075mcpsimp"><a name="p7075mcpsimp"></a><a name="p7075mcpsimp"></a>public void setArguments(Bundle args)</p>
<p id="p669910533915"><a name="p669910533915"></a><a name="p669910533915"></a>Method inherited from <strong id="b1081619239119"><a name="b1081619239119"></a><a name="b1081619239119"></a>Fragment</strong> and called when data needs to be passed to <a href="mapfragment.md">MapFragment</a>.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table7081mcpsimp"></a>
<table><thead align="left"><tr id="row7086mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p7088mcpsimp"><a name="p7088mcpsimp"></a><a name="p7088mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p7090mcpsimp"><a name="p7090mcpsimp"></a><a name="p7090mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row7091mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p7093mcpsimp"><a name="p7093mcpsimp"></a><a name="p7093mcpsimp"></a>args</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p7095mcpsimp"><a name="p7095mcpsimp"></a><a name="p7095mcpsimp"></a>Data to be passed to <a href="mapfragment.md">MapFragment</a>.</p>
</td>
</tr>
</tbody>
</table>

