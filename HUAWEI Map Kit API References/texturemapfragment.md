# TextureMapFragment<a name="EN-US_TOPIC_0000001145541051"></a>

-   [Public Constructor Summary](#section176234589542)
-   [Public Method Summary](#section1674217711594)
-   [Public Methods](#section184932710111)
-   [getMapAsync](#section1352948173510)
-   [newInstance\(\)](#section11704105017376)
-   [newInstance\(HuaweiMapOptions options\)](#section8621523165811)
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


<a name="table22004mcpsimp"></a>
<table><thead align="left"><tr id="row22008mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p22010mcpsimp"><a name="p22010mcpsimp"></a><a name="p22010mcpsimp"></a>Class Info</p>
</th>
</tr>
</thead>
<tbody><tr id="row22011mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p1480874182718"><a name="p1480874182718"></a><a name="p1480874182718"></a>public class TextureMapFragment extends MapFragment</p>
<p id="p25492491243"><a name="p25492491243"></a><a name="p25492491243"></a>Map component inherited from <a href="mapfragment.md">MapFragment</a>, which is the simplest way for placing a map in an app. It provides a view of a map to manage the map lifecycle, and can be loaded to the layout file of <strong id="b1689717371660"><a name="b1689717371660"></a><a name="b1689717371660"></a>Activity</strong> for use. To obtain the map manager, call <a href="#section1352948173510">getMapAsync</a>.</p>
<div class="caution" id="note13075318915"><a name="note13075318915"></a><a name="note13075318915"></a><span class="cautiontitle"> CAUTION: </span><div class="cautionbody"><p id="p5010538912"><a name="p5010538912"></a><a name="p5010538912"></a>This class cannot be used with <a href="mapfragment.md">MapFragment</a>, <a href="mapview.md">MapView</a>, and <a href="supportmapfragment.md">SupportMapFragment</a>.</p>
</div></div>
</td>
</tr>
</tbody>
</table>

## Public Constructor Summary<a name="section176234589542"></a>

<a name="table6451mcpsimp"></a>
<table><thead align="left"><tr id="row6455mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p6457mcpsimp"><a name="p6457mcpsimp"></a><a name="p6457mcpsimp"></a>Constructor Name</p>
</th>
</tr>
</thead>
<tbody><tr id="row6458mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p6460mcpsimp"><a name="p6460mcpsimp"></a><a name="p6460mcpsimp"></a><a href="texturemapfragment.md">TextureMapFragment</a>()</p>
<p id="p10534155923318"><a name="p10534155923318"></a><a name="p10534155923318"></a>Default constructor of the <strong id="b9490724224"><a name="b9490724224"></a><a name="b9490724224"></a>TextureMapFragment</strong> class.</p>
</td>
</tr>
</tbody>
</table>

## Public Method Summary<a name="section1674217711594"></a>

<a name="table5738155010595"></a>
<table><thead align="left"><tr id="row9739145005913"><th class="cellrowborder" valign="top" width="37.36%" id="mcps1.1.3.1.1"><p id="p6469mcpsimp"><a name="p6469mcpsimp"></a><a name="p6469mcpsimp"></a>Qualifier and Type</p>
</th>
<th class="cellrowborder" valign="top" width="62.63999999999999%" id="mcps1.1.3.1.2"><p id="p6471mcpsimp"><a name="p6471mcpsimp"></a><a name="p6471mcpsimp"></a>Method Name and Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row551319529357"><td class="cellrowborder" valign="top" width="37.36%" headers="mcps1.1.3.1.1 "><p id="p6474mcpsimp"><a name="p6474mcpsimp"></a><a name="p6474mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="62.63999999999999%" headers="mcps1.1.3.1.2 "><p id="p6476mcpsimp"><a name="p6476mcpsimp"></a><a name="p6476mcpsimp"></a><a href="#section1352948173510">getMapAsync</a>(<a href="onmapreadycallback.md">OnMapReadyCallback</a> callback)</p>
<p id="p10775543817"><a name="p10775543817"></a><a name="p10775543817"></a>Obtains a <a href="huaweimap.md">HuaweiMap</a> object when the object is ready. </p>
</td>
</tr>
<tr id="row7740350105918"><td class="cellrowborder" valign="top" width="37.36%" headers="mcps1.1.3.1.1 "><p id="p1174025025918"><a name="p1174025025918"></a><a name="p1174025025918"></a>static <a href="texturemapfragment.md">TextureMapFragment</a></p>
</td>
<td class="cellrowborder" valign="top" width="62.63999999999999%" headers="mcps1.1.3.1.2 "><p id="p8352122417355"><a name="p8352122417355"></a><a name="p8352122417355"></a><a href="#section11704105017376">newInstance</a>()</p>
<p id="p91711254914"><a name="p91711254914"></a><a name="p91711254914"></a>Creates a <a href="texturemapfragment.md">TextureMapFragment</a> object with default attributes.</p>
</td>
</tr>
<tr id="row77400503598"><td class="cellrowborder" valign="top" width="37.36%" headers="mcps1.1.3.1.1 "><p id="p473915923516"><a name="p473915923516"></a><a name="p473915923516"></a>static <a href="texturemapfragment.md">TextureMapFragment</a></p>
</td>
<td class="cellrowborder" valign="top" width="62.63999999999999%" headers="mcps1.1.3.1.2 "><p id="p15740750125915"><a name="p15740750125915"></a><a name="p15740750125915"></a><a href="#section8621523165811">newInstance</a>(<a href="huaweimapooptions.md">HuaweiMapOptions</a> options)</p>
<p id="p1098832495"><a name="p1098832495"></a><a name="p1098832495"></a>Creates a <a href="texturemapfragment.md">TextureMapFragment</a> object based on the specified options.</p>
</td>
</tr>
<tr id="row3701113283613"><td class="cellrowborder" valign="top" width="37.36%" headers="mcps1.1.3.1.1 "><p id="p6489mcpsimp"><a name="p6489mcpsimp"></a><a name="p6489mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="62.63999999999999%" headers="mcps1.1.3.1.2 "><p id="p6491mcpsimp"><a name="p6491mcpsimp"></a><a name="p6491mcpsimp"></a><a href="#section98871329193810">onActivityCreated</a>(Bundle savedInstanceState)</p>
<p id="p860615213918"><a name="p860615213918"></a><a name="p860615213918"></a>Lifecycle method inherited from <a href="mapfragment.md">MapFragment</a>.</p>
</td>
</tr>
<tr id="row18700659123618"><td class="cellrowborder" valign="top" width="37.36%" headers="mcps1.1.3.1.1 "><p id="p6494mcpsimp"><a name="p6494mcpsimp"></a><a name="p6494mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="62.63999999999999%" headers="mcps1.1.3.1.2 "><p id="p6496mcpsimp"><a name="p6496mcpsimp"></a><a name="p6496mcpsimp"></a><a href="#section15213513515">onAttach</a>(Activity activity)</p>
<p id="p112617315102"><a name="p112617315102"></a><a name="p112617315102"></a>Lifecycle method inherited from <a href="mapfragment.md">MapFragment</a>.</p>
</td>
</tr>
<tr id="row103697486364"><td class="cellrowborder" valign="top" width="37.36%" headers="mcps1.1.3.1.1 "><p id="p6499mcpsimp"><a name="p6499mcpsimp"></a><a name="p6499mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="62.63999999999999%" headers="mcps1.1.3.1.2 "><p id="p6501mcpsimp"><a name="p6501mcpsimp"></a><a name="p6501mcpsimp"></a><a href="#section137918240516">onCreate</a>(Bundle savedInstanceState)</p>
<p id="p245771491012"><a name="p245771491012"></a><a name="p245771491012"></a>Lifecycle method inherited from <a href="mapfragment.md">MapFragment</a>.</p>
</td>
</tr>
<tr id="row828685614363"><td class="cellrowborder" valign="top" width="37.36%" headers="mcps1.1.3.1.1 "><p id="p6504mcpsimp"><a name="p6504mcpsimp"></a><a name="p6504mcpsimp"></a>View</p>
</td>
<td class="cellrowborder" valign="top" width="62.63999999999999%" headers="mcps1.1.3.1.2 "><p id="p6506mcpsimp"><a name="p6506mcpsimp"></a><a name="p6506mcpsimp"></a><a href="#section113001834165120">onCreateView</a>(LayoutInflater inflater, ViewGroup container, Bundle savedInstanceState)</p>
<p id="p142252441013"><a name="p142252441013"></a><a name="p142252441013"></a>Lifecycle method inherited from <a href="mapfragment.md">MapFragment</a>.</p>
</td>
</tr>
<tr id="row1560604516366"><td class="cellrowborder" valign="top" width="37.36%" headers="mcps1.1.3.1.1 "><p id="p6509mcpsimp"><a name="p6509mcpsimp"></a><a name="p6509mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="62.63999999999999%" headers="mcps1.1.3.1.2 "><p id="p6511mcpsimp"><a name="p6511mcpsimp"></a><a name="p6511mcpsimp"></a><a href="#section387435115512">onDestroy</a>()</p>
<p id="p6413123521010"><a name="p6413123521010"></a><a name="p6413123521010"></a>Lifecycle method inherited from <a href="mapfragment.md">MapFragment</a>.</p>
</td>
</tr>
<tr id="row185150411362"><td class="cellrowborder" valign="top" width="37.36%" headers="mcps1.1.3.1.1 "><p id="p6514mcpsimp"><a name="p6514mcpsimp"></a><a name="p6514mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="62.63999999999999%" headers="mcps1.1.3.1.2 "><p id="p6516mcpsimp"><a name="p6516mcpsimp"></a><a name="p6516mcpsimp"></a><a href="#section12346216526">onDestroyView</a>()</p>
<p id="p20993134421016"><a name="p20993134421016"></a><a name="p20993134421016"></a>Lifecycle method inherited from <a href="mapfragment.md">MapFragment</a>.</p>
</td>
</tr>
<tr id="row1748419203392"><td class="cellrowborder" valign="top" width="37.36%" headers="mcps1.1.3.1.1 "><p id="p7800193016408"><a name="p7800193016408"></a><a name="p7800193016408"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="62.63999999999999%" headers="mcps1.1.3.1.2 "><p id="p15800193094018"><a name="p15800193094018"></a><a name="p15800193094018"></a><a href="#section18462711115217">onInflate</a>(Activity activity, AttributeSet attrs, Bundle savedInstanceState)</p>
<p id="p19383195613108"><a name="p19383195613108"></a><a name="p19383195613108"></a>Lifecycle method inherited from <a href="mapfragment.md">MapFragment</a>. This method is called when <strong id="b7909184311567"><a name="b7909184311567"></a><a name="b7909184311567"></a>Fragment</strong> is statically loaded in XML mode. </p>
</td>
</tr>
<tr id="row10303131814397"><td class="cellrowborder" valign="top" width="37.36%" headers="mcps1.1.3.1.1 "><p id="p138008307406"><a name="p138008307406"></a><a name="p138008307406"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="62.63999999999999%" headers="mcps1.1.3.1.2 "><p id="p1380063014403"><a name="p1380063014403"></a><a name="p1380063014403"></a><a href="#section8571102125210">onLowMemory</a>()</p>
<p id="p35501621117"><a name="p35501621117"></a><a name="p35501621117"></a>Lifecycle method inherited from <a href="mapfragment.md">MapFragment</a>. This method is called when the memory is insufficient. </p>
</td>
</tr>
<tr id="row1789033510392"><td class="cellrowborder" valign="top" width="37.36%" headers="mcps1.1.3.1.1 "><p id="p380073012408"><a name="p380073012408"></a><a name="p380073012408"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="62.63999999999999%" headers="mcps1.1.3.1.2 "><p id="p9800143014403"><a name="p9800143014403"></a><a name="p9800143014403"></a><a href="#section162873275220">onPause</a>()</p>
<p id="p11243181721112"><a name="p11243181721112"></a><a name="p11243181721112"></a>Lifecycle method inherited from <a href="mapfragment.md">MapFragment</a>.</p>
</td>
</tr>
<tr id="row2801416203918"><td class="cellrowborder" valign="top" width="37.36%" headers="mcps1.1.3.1.1 "><p id="p28003302403"><a name="p28003302403"></a><a name="p28003302403"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="62.63999999999999%" headers="mcps1.1.3.1.2 "><p id="p88012300404"><a name="p88012300404"></a><a name="p88012300404"></a><a href="#section324514414524">onResume</a>()</p>
<p id="p16818122671115"><a name="p16818122671115"></a><a name="p16818122671115"></a>Lifecycle method inherited from <a href="mapfragment.md">MapFragment</a>.</p>
</td>
</tr>
<tr id="row9242549133910"><td class="cellrowborder" valign="top" width="37.36%" headers="mcps1.1.3.1.1 "><p id="p8801330144017"><a name="p8801330144017"></a><a name="p8801330144017"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="62.63999999999999%" headers="mcps1.1.3.1.2 "><p id="p1880119309402"><a name="p1880119309402"></a><a name="p1880119309402"></a><a href="#section1892975212522">onSaveInstanceState</a>(Bundle outState)</p>
<p id="p333593891110"><a name="p333593891110"></a><a name="p333593891110"></a>Lifecycle method inherited from <a href="mapfragment.md">MapFragment</a> and called when <a href="texturemapfragment.md">TextureMapFragment</a> is destroyed unexpectedly. It is used to save the status of a <a href="texturemapfragment.md">TextureMapFragment</a> object before it is destroyed.</p>
</td>
</tr>
<tr id="row9461714113916"><td class="cellrowborder" valign="top" width="37.36%" headers="mcps1.1.3.1.1 "><p id="p6801123014011"><a name="p6801123014011"></a><a name="p6801123014011"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="62.63999999999999%" headers="mcps1.1.3.1.2 "><p id="p6801183013404"><a name="p6801183013404"></a><a name="p6801183013404"></a><a href="#section56688365318">onStart</a>()</p>
<p id="p41531949171118"><a name="p41531949171118"></a><a name="p41531949171118"></a>Lifecycle method inherited from <a href="mapfragment.md">MapFragment</a>.</p>
</td>
</tr>
<tr id="row1268061143911"><td class="cellrowborder" valign="top" width="37.36%" headers="mcps1.1.3.1.1 "><p id="p780153010409"><a name="p780153010409"></a><a name="p780153010409"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="62.63999999999999%" headers="mcps1.1.3.1.2 "><p id="p1880143011403"><a name="p1880143011403"></a><a name="p1880143011403"></a><a href="#section4940112185318">onStop</a>()</p>
<p id="p1671125912111"><a name="p1671125912111"></a><a name="p1671125912111"></a>Lifecycle method inherited from <a href="mapfragment.md">MapFragment</a>.</p>
</td>
</tr>
<tr id="row13971963912"><td class="cellrowborder" valign="top" width="37.36%" headers="mcps1.1.3.1.1 "><p id="p168011830144011"><a name="p168011830144011"></a><a name="p168011830144011"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="62.63999999999999%" headers="mcps1.1.3.1.2 "><p id="p380253084020"><a name="p380253084020"></a><a name="p380253084020"></a><a href="#section1188015215533">setArguments</a>(Bundle args)</p>
<p id="p9984121015129"><a name="p9984121015129"></a><a name="p9984121015129"></a>Lifecycle method inherited from <a href="mapfragment.md">MapFragment</a> and called when data needs to be passed to <a href="texturemapfragment.md">TextureMapFragment</a>.</p>
</td>
</tr>
</tbody>
</table>

## Public Methods<a name="section184932710111"></a>

## getMapAsync<a name="section1352948173510"></a>

<a name="table19352174813518"></a>
<table><thead align="left"><tr id="row183522488358"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p1435284810355"><a name="p1435284810355"></a><a name="p1435284810355"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row6352114893516"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p14729143318334"><a name="p14729143318334"></a><a name="p14729143318334"></a>public void getMapAsync(<a href="onmapreadycallback.md">OnMapReadyCallback</a> callback)</p>
<p id="p2352174843518"><a name="p2352174843518"></a><a name="p2352174843518"></a>Obtains a <a href="huaweimap.md">HuaweiMap</a> object when the object is ready. </p>
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

## newInstance\(\)<a name="section11704105017376"></a>

<a name="table6569mcpsimp"></a>
<table><thead align="left"><tr id="row6573mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p6575mcpsimp"><a name="p6575mcpsimp"></a><a name="p6575mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row6576mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p074126114516"><a name="p074126114516"></a><a name="p074126114516"></a>public static <a href="texturemapfragment.md">TextureMapFragment</a> newInstance()</p>
<p id="p17377650124613"><a name="p17377650124613"></a><a name="p17377650124613"></a>Creates a <a href="texturemapfragment.md">TextureMapFragment</a> object with default attributes.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table98601644163618"></a>
<table><thead align="left"><tr id="row16886544183618"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p4886204412367"><a name="p4886204412367"></a><a name="p4886204412367"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p11886544183614"><a name="p11886544183614"></a><a name="p11886544183614"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row3886544123620"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p9250800378"><a name="p9250800378"></a><a name="p9250800378"></a>TextureMapFragment</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p1488604463616"><a name="p1488604463616"></a><a name="p1488604463616"></a><a href="texturemapfragment.md">TextureMapFragment</a> object.</p>
</td>
</tr>
</tbody>
</table>

## newInstance\(HuaweiMapOptions options\)<a name="section8621523165811"></a>

<a name="table105691449115814"></a>
<table><thead align="left"><tr id="row11569449175811"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p1656912492582"><a name="p1656912492582"></a><a name="p1656912492582"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row0569144918588"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p6462171019599"><a name="p6462171019599"></a><a name="p6462171019599"></a>public static <a href="texturemapfragment.md">TextureMapFragment</a> newInstance(<a href="huaweimapooptions.md">HuaweiMapOptions</a> options)</p>
<p id="p25785151309"><a name="p25785151309"></a><a name="p25785151309"></a>Creates a <a href="texturemapfragment.md">TextureMapFragment</a> object based on the specified options.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table13569049175814"></a>
<table><thead align="left"><tr id="row1357094985811"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p175707497588"><a name="p175707497588"></a><a name="p175707497588"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p20570949105818"><a name="p20570949105818"></a><a name="p20570949105818"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row79270398011"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p16518553803"><a name="p16518553803"></a><a name="p16518553803"></a>options</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p1751816531019"><a name="p1751816531019"></a><a name="p1751816531019"></a>Attributes required for creating a <a href="huaweimapooptions.md">HuaweiMapOptions</a> object.</p>
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
<tbody><tr id="row6648mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p11296746153610"><a name="p11296746153610"></a><a name="p11296746153610"></a>TextureMapFragment</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p6652mcpsimp"><a name="p6652mcpsimp"></a><a name="p6652mcpsimp"></a><a href="texturemapfragment.md">TextureMapFragment</a> object.</p>
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
<p id="p6700mcpsimp"><a name="p6700mcpsimp"></a><a name="p6700mcpsimp"></a>Lifecycle method inherited from <a href="mapfragment.md">MapFragment</a>.</p>
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
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p6717mcpsimp"><a name="p6717mcpsimp"></a><a name="p6717mcpsimp"></a>Status to be saved for a <a href="texturemapfragment.md">TextureMapFragment</a> object.</p>
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
<p id="p1418631193120"><a name="p1418631193120"></a><a name="p1418631193120"></a>Lifecycle method inherited from <a href="mapfragment.md">MapFragment</a>.</p>
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
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p6751mcpsimp"><a name="p6751mcpsimp"></a><a name="p6751mcpsimp"></a>Activity object bound to <a href="texturemapfragment.md">TextureMapFragment</a>.</p>
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
<p id="p5116134218316"><a name="p5116134218316"></a><a name="p5116134218316"></a>Lifecycle method inherited from <a href="mapfragment.md">MapFragment</a>.</p>
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
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p6785mcpsimp"><a name="p6785mcpsimp"></a><a name="p6785mcpsimp"></a>Status to be saved for a <a href="texturemapfragment.md">TextureMapFragment</a> object.</p>
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
<p id="p6802mcpsimp"><a name="p6802mcpsimp"></a><a name="p6802mcpsimp"></a>Lifecycle method inherited from <a href="mapfragment.md">MapFragment</a>.</p>
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
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p6819mcpsimp"><a name="p6819mcpsimp"></a><a name="p6819mcpsimp"></a><strong id="b515875371012"><a name="b515875371012"></a><a name="b515875371012"></a>LayoutInflater</strong> object, which is used to search for controls in a layout.</p>
</td>
</tr>
<tr id="row6820mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p6822mcpsimp"><a name="p6822mcpsimp"></a><a name="p6822mcpsimp"></a>container</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p6824mcpsimp"><a name="p6824mcpsimp"></a><a name="p6824mcpsimp"></a>Layout container.</p>
</td>
</tr>
<tr id="row6825mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p6827mcpsimp"><a name="p6827mcpsimp"></a><a name="p6827mcpsimp"></a>savedInstanceState</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p6829mcpsimp"><a name="p6829mcpsimp"></a><a name="p6829mcpsimp"></a>Status to be saved for a <a href="texturemapfragment.md">TextureMapFragment</a> object.</p>
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
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p6846mcpsimp"><a name="p6846mcpsimp"></a><a name="p6846mcpsimp"></a><strong id="b151662831110"><a name="b151662831110"></a><a name="b151662831110"></a>View</strong> object.</p>
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
<p id="p6860mcpsimp"><a name="p6860mcpsimp"></a><a name="p6860mcpsimp"></a>Lifecycle method inherited from <a href="mapfragment.md">MapFragment</a>.</p>
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
<p id="p32031940173316"><a name="p32031940173316"></a><a name="p32031940173316"></a>Lifecycle method inherited from <a href="mapfragment.md">MapFragment</a>.</p>
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
<p id="p6900mcpsimp"><a name="p6900mcpsimp"></a><a name="p6900mcpsimp"></a>Lifecycle method inherited from <a href="mapfragment.md">MapFragment</a>. This method is called when <strong id="b1889615190112"><a name="b1889615190112"></a><a name="b1889615190112"></a>Fragment</strong> is statically loaded in XML mode. </p>
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
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p6917mcpsimp"><a name="p6917mcpsimp"></a><a name="p6917mcpsimp"></a>Activity object bound to <a href="texturemapfragment.md">TextureMapFragment</a>.</p>
</td>
</tr>
<tr id="row6918mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p6920mcpsimp"><a name="p6920mcpsimp"></a><a name="p6920mcpsimp"></a>attrs</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p6922mcpsimp"><a name="p6922mcpsimp"></a><a name="p6922mcpsimp"></a>Attributes used to create a <a href="texturemapfragment.md">TextureMapFragment</a> object.</p>
</td>
</tr>
<tr id="row6923mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p6925mcpsimp"><a name="p6925mcpsimp"></a><a name="p6925mcpsimp"></a>savedInstanceState</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p6927mcpsimp"><a name="p6927mcpsimp"></a><a name="p6927mcpsimp"></a>Status to be saved for a <a href="texturemapfragment.md">TextureMapFragment</a> object.</p>
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
<p id="p1934183453515"><a name="p1934183453515"></a><a name="p1934183453515"></a>Lifecycle method inherited from <a href="mapfragment.md">MapFragment</a>. This method is called when the memory is insufficient. </p>
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
<p id="p676018153365"><a name="p676018153365"></a><a name="p676018153365"></a>Lifecycle method inherited from <a href="mapfragment.md">MapFragment</a>.</p>
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
<p id="p16612752183617"><a name="p16612752183617"></a><a name="p16612752183617"></a>Lifecycle method inherited from <a href="mapfragment.md">MapFragment</a>.</p>
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
<p id="p33091121123"><a name="p33091121123"></a><a name="p33091121123"></a>Method inherited from <a href="mapfragment.md">MapFragment</a> and called when <a href="texturemapfragment.md">TextureMapFragment</a> is destroyed unexpectedly. It is used to save the status of a <a href="texturemapfragment.md">TextureMapFragment</a> object before it is destroyed.</p>
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
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p7021mcpsimp"><a name="p7021mcpsimp"></a><a name="p7021mcpsimp"></a>Status to be saved for a <a href="texturemapfragment.md">TextureMapFragment</a> object.</p>
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
<p id="p368297103818"><a name="p368297103818"></a><a name="p368297103818"></a>Lifecycle method inherited from <a href="mapfragment.md">MapFragment</a>.</p>
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
<p id="p7058mcpsimp"><a name="p7058mcpsimp"></a><a name="p7058mcpsimp"></a>Lifecycle method inherited from <a href="mapfragment.md">MapFragment</a>.</p>
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
<p id="p669910533915"><a name="p669910533915"></a><a name="p669910533915"></a>Lifecycle method inherited from <a href="mapfragment.md">MapFragment</a> and called when data needs to be passed to <a href="texturemapfragment.md">TextureMapFragment</a>.</p>
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
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p7095mcpsimp"><a name="p7095mcpsimp"></a><a name="p7095mcpsimp"></a>Data to be passed to <a href="texturemapfragment.md">TextureMapFragment</a>.</p>
</td>
</tr>
</tbody>
</table>

