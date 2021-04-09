# TextureSupportMapFragment<a name="EN-US_TOPIC_0000001099181284"></a>

-   [Public Constructor Summary](#section176234589542)
-   [Public Method Summary](#section1674217711594)
-   [Public Methods](#section16714613113411)
-   [getMapAsync](#section1874811557456)
-   [newInstance\(\)](#section11704105017376)
-   [newInstance\(HuaweiMapOptions options\)](#section1610982254611)
-   [onActivityCreated](#section00182374920)
-   [onAttach](#section10531135894915)
-   [onCreate](#section19132104012509)
-   [onCreateView](#section648115222519)
-   [onDestroy](#section11273709522)
-   [onDestroyView](#section032617282527)
-   [onInflate](#section1229121125312)
-   [onLowMemory](#section29326333532)
-   [onPause](#section14721458546)
-   [onResume](#section983593585415)
-   [onSaveInstanceState](#section957915755513)
-   [onStart](#section1792804625518)
-   [onStop](#section51391716135616)
-   [setArguments](#section17257548135617)


<a name="table22004mcpsimp"></a>
<table><thead align="left"><tr id="row22008mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p22010mcpsimp"><a name="p22010mcpsimp"></a><a name="p22010mcpsimp"></a>Class Info</p>
</th>
</tr>
</thead>
<tbody><tr id="row22011mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p135881954162617"><a name="p135881954162617"></a><a name="p135881954162617"></a>public class TextureSupportMapFragment extends Fragment</p>
<p id="p22013mcpsimp"><a name="p22013mcpsimp"></a><a name="p22013mcpsimp"></a>Map component in the app, which is inherited from <strong id="b78811115181"><a name="b78811115181"></a><a name="b78811115181"></a>Fragment</strong> and used to manage the map lifecycle. To obtain the map manager, call <a href="#section1874811557456">getMapAsync</a>.</p>
<div class="caution" id="note99410493182"><a name="note99410493182"></a><a name="note99410493182"></a><span class="cautiontitle"> CAUTION: </span><div class="cautionbody"><p id="p1994134920188"><a name="p1994134920188"></a><a name="p1994134920188"></a>This class cannot be used with <a href="mapfragment.md">MapFragment</a>, <a href="mapview.md">MapView</a>, and <a href="supportmapfragment.md">SupportMapFragment</a>.</p>
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
<tbody><tr id="row6458mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p6460mcpsimp"><a name="p6460mcpsimp"></a><a name="p6460mcpsimp"></a><a href="texturesupportmapfragment.md">TextureSupportMapFragment</a>()</p>
<p id="p146302723410"><a name="p146302723410"></a><a name="p146302723410"></a>Default constructor of the <strong id="b17824743829"><a name="b17824743829"></a><a name="b17824743829"></a>TextureSupportMapFragment</strong> class.</p>
</td>
</tr>
</tbody>
</table>

## Public Method Summary<a name="section1674217711594"></a>

<a name="table22028mcpsimp"></a>
<table><thead align="left"><tr id="row22033mcpsimp"><th class="cellrowborder" valign="top" width="40%" id="mcps1.1.3.1.1"><p id="p081120285386"><a name="p081120285386"></a><a name="p081120285386"></a>Qualifier and Type</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.1.3.1.2"><p id="p681112883813"><a name="p681112883813"></a><a name="p681112883813"></a>Method Name and Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row22038mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p22040mcpsimp"><a name="p22040mcpsimp"></a><a name="p22040mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p22042mcpsimp"><a name="p22042mcpsimp"></a><a name="p22042mcpsimp"></a><a href="#section1874811557456">getMapAsync</a>(<a href="onmapreadycallback.md">OnMapReadyCallback</a> callback)</p>
<p id="p19159431131616"><a name="p19159431131616"></a><a name="p19159431131616"></a>Obtains a <a href="huaweimap.md">HuaweiMap</a> object when the object is ready. </p>
</td>
</tr>
<tr id="row22043mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p19922151915312"><a name="p19922151915312"></a><a name="p19922151915312"></a>static <a href="texturesupportmapfragment.md">TextureSupportMapFragment</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p179221519115317"><a name="p179221519115317"></a><a name="p179221519115317"></a><a href="#section11704105017376">newInstance</a>()</p>
<p id="p0175184131617"><a name="p0175184131617"></a><a name="p0175184131617"></a>Creates a <a href="texturesupportmapfragment.md">TextureSupportMapFragment</a> object with default attributes.</p>
</td>
</tr>
<tr id="row22048mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p102560272538"><a name="p102560272538"></a><a name="p102560272538"></a>static <a href="texturesupportmapfragment.md">TextureSupportMapFragment</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p202561027155319"><a name="p202561027155319"></a><a name="p202561027155319"></a><a href="#section1610982254611">newInstance</a>(<a href="huaweimapooptions.md">HuaweiMapOptions</a> options)</p>
<p id="p112921251131613"><a name="p112921251131613"></a><a name="p112921251131613"></a>Creates a <a href="texturesupportmapfragment.md">TextureSupportMapFragment</a> object based on the specified parameters.</p>
</td>
</tr>
<tr id="row22053mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p22055mcpsimp"><a name="p22055mcpsimp"></a><a name="p22055mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p22057mcpsimp"><a name="p22057mcpsimp"></a><a name="p22057mcpsimp"></a><a href="#section00182374920">onActivityCreated</a>(Bundle savedInstanceState)</p>
<p id="p422914161716"><a name="p422914161716"></a><a name="p422914161716"></a>Lifecycle method inherited from <strong id="b10615191120411"><a name="b10615191120411"></a><a name="b10615191120411"></a>Fragment</strong>.</p>
</td>
</tr>
<tr id="row22058mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p22060mcpsimp"><a name="p22060mcpsimp"></a><a name="p22060mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p22062mcpsimp"><a name="p22062mcpsimp"></a><a name="p22062mcpsimp"></a><a href="#section10531135894915">onAttach</a>(Activity activity)</p>
<p id="p1076312107171"><a name="p1076312107171"></a><a name="p1076312107171"></a>Lifecycle method inherited from <strong id="b04318213411"><a name="b04318213411"></a><a name="b04318213411"></a>Fragment</strong>.</p>
</td>
</tr>
<tr id="row22063mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p22065mcpsimp"><a name="p22065mcpsimp"></a><a name="p22065mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p22067mcpsimp"><a name="p22067mcpsimp"></a><a name="p22067mcpsimp"></a><a href="#section19132104012509">onCreate</a>(Bundle savedInstanceState)</p>
<p id="p1811722016173"><a name="p1811722016173"></a><a name="p1811722016173"></a>Lifecycle method inherited from <strong id="b195981923641"><a name="b195981923641"></a><a name="b195981923641"></a>Fragment</strong>.</p>
</td>
</tr>
<tr id="row22068mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p22070mcpsimp"><a name="p22070mcpsimp"></a><a name="p22070mcpsimp"></a>View</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p22072mcpsimp"><a name="p22072mcpsimp"></a><a name="p22072mcpsimp"></a><a href="#section648115222519">onCreateView</a>(LayoutInflater inflater, ViewGroup container, Bundle savedInstanceState)</p>
<p id="p9248172913176"><a name="p9248172913176"></a><a name="p9248172913176"></a>Lifecycle method inherited from <strong id="b1789172313411"><a name="b1789172313411"></a><a name="b1789172313411"></a>Fragment</strong>.</p>
</td>
</tr>
<tr id="row22073mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p22075mcpsimp"><a name="p22075mcpsimp"></a><a name="p22075mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p22077mcpsimp"><a name="p22077mcpsimp"></a><a name="p22077mcpsimp"></a><a href="#section11273709522">onDestroy</a>()</p>
<p id="p6502153713176"><a name="p6502153713176"></a><a name="p6502153713176"></a>Lifecycle method inherited from <strong id="b99642231341"><a name="b99642231341"></a><a name="b99642231341"></a>Fragment</strong>.</p>
</td>
</tr>
<tr id="row22078mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p22080mcpsimp"><a name="p22080mcpsimp"></a><a name="p22080mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p22082mcpsimp"><a name="p22082mcpsimp"></a><a name="p22082mcpsimp"></a><a href="#section032617282527">onDestroyView</a>()</p>
<p id="p1667810479176"><a name="p1667810479176"></a><a name="p1667810479176"></a>Lifecycle method inherited from <strong id="b512602417412"><a name="b512602417412"></a><a name="b512602417412"></a>Fragment</strong>.</p>
</td>
</tr>
<tr id="row22093mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p22095mcpsimp"><a name="p22095mcpsimp"></a><a name="p22095mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p22097mcpsimp"><a name="p22097mcpsimp"></a><a name="p22097mcpsimp"></a><a href="#section1229121125312">onInflate</a>(Activity activity, AttributeSet attrs, Bundle savedInstanceState)</p>
<p id="p12665347182"><a name="p12665347182"></a><a name="p12665347182"></a>Lifecycle method inherited from <strong id="b20522424641"><a name="b20522424641"></a><a name="b20522424641"></a>Fragment</strong>. This method is called when <a href="texturesupportmapfragment.md">TextureSupportMapFragment</a> is statically loaded in XML mode. </p>
</td>
</tr>
<tr id="row22098mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p22100mcpsimp"><a name="p22100mcpsimp"></a><a name="p22100mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p22102mcpsimp"><a name="p22102mcpsimp"></a><a name="p22102mcpsimp"></a><a href="#section29326333532">onLowMemory</a>()</p>
<p id="p1818810212186"><a name="p1818810212186"></a><a name="p1818810212186"></a>Lifecycle method inherited from <strong id="b135967312415"><a name="b135967312415"></a><a name="b135967312415"></a>Fragment</strong>.</p>
</td>
</tr>
<tr id="row22103mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p22105mcpsimp"><a name="p22105mcpsimp"></a><a name="p22105mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p22107mcpsimp"><a name="p22107mcpsimp"></a><a name="p22107mcpsimp"></a><a href="#section14721458546">onPause</a>()</p>
<p id="p4475143112184"><a name="p4475143112184"></a><a name="p4475143112184"></a>Lifecycle method inherited from <strong id="b1891119361745"><a name="b1891119361745"></a><a name="b1891119361745"></a>Fragment</strong>.</p>
</td>
</tr>
<tr id="row22108mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p22110mcpsimp"><a name="p22110mcpsimp"></a><a name="p22110mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p22112mcpsimp"><a name="p22112mcpsimp"></a><a name="p22112mcpsimp"></a><a href="#section983593585415">onResume</a>()</p>
<p id="p72753453181"><a name="p72753453181"></a><a name="p72753453181"></a>Lifecycle method inherited from <strong id="b198563715414"><a name="b198563715414"></a><a name="b198563715414"></a>Fragment</strong>.</p>
</td>
</tr>
<tr id="row22113mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p22115mcpsimp"><a name="p22115mcpsimp"></a><a name="p22115mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p22117mcpsimp"><a name="p22117mcpsimp"></a><a name="p22117mcpsimp"></a><a href="#section957915755513">onSaveInstanceState</a>(Bundle outState)</p>
<p id="p137399171914"><a name="p137399171914"></a><a name="p137399171914"></a>Lifecycle method inherited from <strong id="b102725381743"><a name="b102725381743"></a><a name="b102725381743"></a>Fragment</strong> and called when <strong id="b22731381643"><a name="b22731381643"></a><a name="b22731381643"></a>Fragment</strong> is destroyed unexpectedly. It is used to save the status of a <a href="texturesupportmapfragment.md">TextureSupportMapFragment</a> object before it is destroyed. Then, the status can be retrieved when <a href="#section19132104012509">onCreate</a><strong id="b18274538540"><a name="b18274538540"></a><a name="b18274538540"></a>(Bundle)</strong> is called again.</p>
</td>
</tr>
<tr id="row22118mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p22120mcpsimp"><a name="p22120mcpsimp"></a><a name="p22120mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p22122mcpsimp"><a name="p22122mcpsimp"></a><a name="p22122mcpsimp"></a><a href="#section1792804625518">onStart</a>()</p>
<p id="p7938141221919"><a name="p7938141221919"></a><a name="p7938141221919"></a>Lifecycle method inherited from <strong id="b3731224055"><a name="b3731224055"></a><a name="b3731224055"></a>Fragment</strong>.</p>
</td>
</tr>
<tr id="row22123mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p22125mcpsimp"><a name="p22125mcpsimp"></a><a name="p22125mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p22127mcpsimp"><a name="p22127mcpsimp"></a><a name="p22127mcpsimp"></a><a href="#section51391716135616">onStop</a>()</p>
<p id="p1257622314197"><a name="p1257622314197"></a><a name="p1257622314197"></a>Lifecycle method inherited from <strong id="b108942251955"><a name="b108942251955"></a><a name="b108942251955"></a>Fragment</strong>.</p>
</td>
</tr>
<tr id="row22128mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p22130mcpsimp"><a name="p22130mcpsimp"></a><a name="p22130mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p22132mcpsimp"><a name="p22132mcpsimp"></a><a name="p22132mcpsimp"></a><a href="#section17257548135617">setArguments</a>(Bundle args)</p>
<p id="p4135335181920"><a name="p4135335181920"></a><a name="p4135335181920"></a>Lifecycle method inherited from <strong id="b643017262513"><a name="b643017262513"></a><a name="b643017262513"></a>Fragment</strong> and called when data needs to be passed to <strong id="b743119262059"><a name="b743119262059"></a><a name="b743119262059"></a>Fragment</strong>.</p>
</td>
</tr>
</tbody>
</table>

## Public Methods<a name="section16714613113411"></a>

## getMapAsync<a name="section1874811557456"></a>

<a name="table22135mcpsimp"></a>
<table><thead align="left"><tr id="row22139mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p22141mcpsimp"><a name="p22141mcpsimp"></a><a name="p22141mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row22142mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p22144mcpsimp"><a name="p22144mcpsimp"></a><a name="p22144mcpsimp"></a>public void getMapAsync(<a href="onmapreadycallback.md">OnMapReadyCallback</a> callback)</p>
<p id="p206900148464"><a name="p206900148464"></a><a name="p206900148464"></a>Obtains a <a href="huaweimap.md">HuaweiMap</a> object when the object is ready. </p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table22153mcpsimp"></a>
<table><thead align="left"><tr id="row22158mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p22160mcpsimp"><a name="p22160mcpsimp"></a><a name="p22160mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p22162mcpsimp"><a name="p22162mcpsimp"></a><a name="p22162mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row22163mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p22165mcpsimp"><a name="p22165mcpsimp"></a><a name="p22165mcpsimp"></a>callback</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p22167mcpsimp"><a name="p22167mcpsimp"></a><a name="p22167mcpsimp"></a>Callback to be executed when a map is ready for use.</p>
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
<tbody><tr id="row6576mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p131378117365"><a name="p131378117365"></a><a name="p131378117365"></a>public static <a href="texturesupportmapfragment.md">TextureSupportMapFragment</a> newInstance()</p>
<p id="p17377650124613"><a name="p17377650124613"></a><a name="p17377650124613"></a>Creates a <a href="texturesupportmapfragment.md">TextureSupportMapFragment</a> object with default attributes.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table22204mcpsimp"></a>
<table><thead align="left"><tr id="row22209mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p22211mcpsimp"><a name="p22211mcpsimp"></a><a name="p22211mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p22213mcpsimp"><a name="p22213mcpsimp"></a><a name="p22213mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row22214mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p22216mcpsimp"><a name="p22216mcpsimp"></a><a name="p22216mcpsimp"></a>TextureSupportMapFragment</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p22218mcpsimp"><a name="p22218mcpsimp"></a><a name="p22218mcpsimp"></a><a href="texturesupportmapfragment.md">TextureSupportMapFragment</a> object.</p>
</td>
</tr>
</tbody>
</table>

## newInstance\(HuaweiMapOptions options\)<a name="section1610982254611"></a>

<a name="table1210918227465"></a>
<table><thead align="left"><tr id="row1010913221463"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p17109122184616"><a name="p17109122184616"></a><a name="p17109122184616"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row31093221463"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p158614560464"><a name="p158614560464"></a><a name="p158614560464"></a>public static <a href="texturesupportmapfragment.md">TextureSupportMapFragment</a> newInstance(<a href="huaweimapooptions.md">HuaweiMapOptions</a> options)</p>
<p id="p1327412915474"><a name="p1327412915474"></a><a name="p1327412915474"></a>Creates a <a href="texturesupportmapfragment.md">TextureSupportMapFragment</a> object based on the specified parameters.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table511015222469"></a>
<table><thead align="left"><tr id="row1110202294613"><th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.1"><p id="p101101322194614"><a name="p101101322194614"></a><a name="p101101322194614"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.2"><p id="p5110192216467"><a name="p5110192216467"></a><a name="p5110192216467"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row16110022194612"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p143661554154712"><a name="p143661554154712"></a><a name="p143661554154712"></a>options</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p711032212469"><a name="p711032212469"></a><a name="p711032212469"></a><a href="huaweimapooptions.md">HuaweiMapOptions</a>.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table8154155743012"></a>
<table><thead align="left"><tr id="row151541957133020"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p51546575307"><a name="p51546575307"></a><a name="p51546575307"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p11154115711307"><a name="p11154115711307"></a><a name="p11154115711307"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row131541957203019"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p41761007325"><a name="p41761007325"></a><a name="p41761007325"></a>TextureSupportMapFragment</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p415410579303"><a name="p415410579303"></a><a name="p415410579303"></a><a href="texturesupportmapfragment.md">TextureSupportMapFragment</a> object.</p>
</td>
</tr>
</tbody>
</table>

## onActivityCreated<a name="section00182374920"></a>

<a name="table22254mcpsimp"></a>
<table><thead align="left"><tr id="row22258mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p22260mcpsimp"><a name="p22260mcpsimp"></a><a name="p22260mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row22261mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p22263mcpsimp"><a name="p22263mcpsimp"></a><a name="p22263mcpsimp"></a>public void onActivityCreated(Bundle savedInstanceState)</p>
<p id="p163342396498"><a name="p163342396498"></a><a name="p163342396498"></a>Lifecycle method inherited from <strong id="b0613161942013"><a name="b0613161942013"></a><a name="b0613161942013"></a>Fragment</strong>.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table22269mcpsimp"></a>
<table><thead align="left"><tr id="row22274mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p22276mcpsimp"><a name="p22276mcpsimp"></a><a name="p22276mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p22278mcpsimp"><a name="p22278mcpsimp"></a><a name="p22278mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row22279mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p22281mcpsimp"><a name="p22281mcpsimp"></a><a name="p22281mcpsimp"></a>savedInstanceState</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p22283mcpsimp"><a name="p22283mcpsimp"></a><a name="p22283mcpsimp"></a>Status to be saved for a <a href="texturesupportmapfragment.md">TextureSupportMapFragment</a> object.</p>
</td>
</tr>
</tbody>
</table>

## onAttach<a name="section10531135894915"></a>

<a name="table22288mcpsimp"></a>
<table><thead align="left"><tr id="row22292mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p22294mcpsimp"><a name="p22294mcpsimp"></a><a name="p22294mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row22295mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p22297mcpsimp"><a name="p22297mcpsimp"></a><a name="p22297mcpsimp"></a>public void onAttach(Activity activity)</p>
<p id="p22300mcpsimp"><a name="p22300mcpsimp"></a><a name="p22300mcpsimp"></a>Lifecycle method inherited from <strong id="b9334162932016"><a name="b9334162932016"></a><a name="b9334162932016"></a>Fragment</strong>.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table22303mcpsimp"></a>
<table><thead align="left"><tr id="row22308mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p22310mcpsimp"><a name="p22310mcpsimp"></a><a name="p22310mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p22312mcpsimp"><a name="p22312mcpsimp"></a><a name="p22312mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row22313mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p22315mcpsimp"><a name="p22315mcpsimp"></a><a name="p22315mcpsimp"></a>activity</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p22317mcpsimp"><a name="p22317mcpsimp"></a><a name="p22317mcpsimp"></a>Activity object bound to <a href="texturesupportmapfragment.md">TextureSupportMapFragment</a>.</p>
</td>
</tr>
</tbody>
</table>

## onCreate<a name="section19132104012509"></a>

<a name="table22322mcpsimp"></a>
<table><thead align="left"><tr id="row22326mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p22328mcpsimp"><a name="p22328mcpsimp"></a><a name="p22328mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row22329mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p22331mcpsimp"><a name="p22331mcpsimp"></a><a name="p22331mcpsimp"></a>public void onCreate(Bundle savedInstanceState)</p>
<p id="p22334mcpsimp"><a name="p22334mcpsimp"></a><a name="p22334mcpsimp"></a>Lifecycle method inherited from <strong id="b51531038172016"><a name="b51531038172016"></a><a name="b51531038172016"></a>Fragment</strong>.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table22337mcpsimp"></a>
<table><thead align="left"><tr id="row22342mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p22344mcpsimp"><a name="p22344mcpsimp"></a><a name="p22344mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p22346mcpsimp"><a name="p22346mcpsimp"></a><a name="p22346mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row22347mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p22349mcpsimp"><a name="p22349mcpsimp"></a><a name="p22349mcpsimp"></a>savedInstanceState</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p22351mcpsimp"><a name="p22351mcpsimp"></a><a name="p22351mcpsimp"></a>Status to be saved for a <a href="texturesupportmapfragment.md">TextureSupportMapFragment</a> object.</p>
</td>
</tr>
</tbody>
</table>

## onCreateView<a name="section648115222519"></a>

<a name="table22356mcpsimp"></a>
<table><thead align="left"><tr id="row22360mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p22362mcpsimp"><a name="p22362mcpsimp"></a><a name="p22362mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row22363mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p22365mcpsimp"><a name="p22365mcpsimp"></a><a name="p22365mcpsimp"></a>public View onCreateView(LayoutInflater inflater, ViewGroup container, Bundle savedInstanceState)</p>
<p id="p22368mcpsimp"><a name="p22368mcpsimp"></a><a name="p22368mcpsimp"></a>Lifecycle method inherited from <strong id="b153735472207"><a name="b153735472207"></a><a name="b153735472207"></a>Fragment</strong>.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table22371mcpsimp"></a>
<table><thead align="left"><tr id="row22376mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p22378mcpsimp"><a name="p22378mcpsimp"></a><a name="p22378mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p22380mcpsimp"><a name="p22380mcpsimp"></a><a name="p22380mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row22381mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p22383mcpsimp"><a name="p22383mcpsimp"></a><a name="p22383mcpsimp"></a>inflater</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p22385mcpsimp"><a name="p22385mcpsimp"></a><a name="p22385mcpsimp"></a><strong id="b10690614212"><a name="b10690614212"></a><a name="b10690614212"></a>LayoutInflater</strong> object, which is used to search for controls in a layout.</p>
</td>
</tr>
<tr id="row22386mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p22388mcpsimp"><a name="p22388mcpsimp"></a><a name="p22388mcpsimp"></a>container</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p22390mcpsimp"><a name="p22390mcpsimp"></a><a name="p22390mcpsimp"></a>Layout container.</p>
</td>
</tr>
<tr id="row22391mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p22393mcpsimp"><a name="p22393mcpsimp"></a><a name="p22393mcpsimp"></a>savedInstanceState</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p22395mcpsimp"><a name="p22395mcpsimp"></a><a name="p22395mcpsimp"></a>Status to be saved for a <a href="texturesupportmapfragment.md">TextureSupportMapFragment</a> object.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table22398mcpsimp"></a>
<table><thead align="left"><tr id="row22403mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p22405mcpsimp"><a name="p22405mcpsimp"></a><a name="p22405mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p22407mcpsimp"><a name="p22407mcpsimp"></a><a name="p22407mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row22408mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p22410mcpsimp"><a name="p22410mcpsimp"></a><a name="p22410mcpsimp"></a>View</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p22412mcpsimp"><a name="p22412mcpsimp"></a><a name="p22412mcpsimp"></a><strong id="b59356161211"><a name="b59356161211"></a><a name="b59356161211"></a>View</strong> object.</p>
</td>
</tr>
</tbody>
</table>

## onDestroy<a name="section11273709522"></a>

<a name="table22414mcpsimp"></a>
<table><thead align="left"><tr id="row22418mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p22420mcpsimp"><a name="p22420mcpsimp"></a><a name="p22420mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row22421mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p22423mcpsimp"><a name="p22423mcpsimp"></a><a name="p22423mcpsimp"></a>public void onDestroy()</p>
<p id="p22426mcpsimp"><a name="p22426mcpsimp"></a><a name="p22426mcpsimp"></a>Lifecycle method inherited from <strong id="b3555837172110"><a name="b3555837172110"></a><a name="b3555837172110"></a>Fragment</strong>.</p>
</td>
</tr>
</tbody>
</table>

## onDestroyView<a name="section032617282527"></a>

<a name="table22434mcpsimp"></a>
<table><thead align="left"><tr id="row22438mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p22440mcpsimp"><a name="p22440mcpsimp"></a><a name="p22440mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row22441mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p22443mcpsimp"><a name="p22443mcpsimp"></a><a name="p22443mcpsimp"></a>public void onDestroyView()</p>
<p id="p22446mcpsimp"><a name="p22446mcpsimp"></a><a name="p22446mcpsimp"></a>Lifecycle method inherited from <strong id="b1212743932118"><a name="b1212743932118"></a><a name="b1212743932118"></a>Fragment</strong>.</p>
</td>
</tr>
</tbody>
</table>

## onInflate<a name="section1229121125312"></a>

<a name="table22454mcpsimp"></a>
<table><thead align="left"><tr id="row22458mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p22460mcpsimp"><a name="p22460mcpsimp"></a><a name="p22460mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row22461mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p22463mcpsimp"><a name="p22463mcpsimp"></a><a name="p22463mcpsimp"></a>public void onInflate(Activity activity, AttributeSet attrs, Bundle savedInstanceState)</p>
<p id="p22466mcpsimp"><a name="p22466mcpsimp"></a><a name="p22466mcpsimp"></a>Lifecycle method inherited from <strong id="b16619114092117"><a name="b16619114092117"></a><a name="b16619114092117"></a>Fragment</strong>. This method is called when <a href="texturesupportmapfragment.md">TextureSupportMapFragment</a> is statically loaded in XML mode. </p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table22469mcpsimp"></a>
<table><thead align="left"><tr id="row22474mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p22476mcpsimp"><a name="p22476mcpsimp"></a><a name="p22476mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p22478mcpsimp"><a name="p22478mcpsimp"></a><a name="p22478mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row22479mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p22481mcpsimp"><a name="p22481mcpsimp"></a><a name="p22481mcpsimp"></a>activity</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p22483mcpsimp"><a name="p22483mcpsimp"></a><a name="p22483mcpsimp"></a>Activity object bound to <a href="texturesupportmapfragment.md">TextureSupportMapFragment</a>.</p>
</td>
</tr>
<tr id="row22484mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p22486mcpsimp"><a name="p22486mcpsimp"></a><a name="p22486mcpsimp"></a>attrs</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p22488mcpsimp"><a name="p22488mcpsimp"></a><a name="p22488mcpsimp"></a>Attributes used to create a <a href="texturesupportmapfragment.md">TextureSupportMapFragment</a> object.</p>
</td>
</tr>
<tr id="row22489mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p22491mcpsimp"><a name="p22491mcpsimp"></a><a name="p22491mcpsimp"></a>savedInstanceState</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p22493mcpsimp"><a name="p22493mcpsimp"></a><a name="p22493mcpsimp"></a>Status to be saved for a <a href="texturesupportmapfragment.md">TextureSupportMapFragment</a> object.</p>
</td>
</tr>
</tbody>
</table>

## onLowMemory<a name="section29326333532"></a>

<a name="table22498mcpsimp"></a>
<table><thead align="left"><tr id="row22502mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p22504mcpsimp"><a name="p22504mcpsimp"></a><a name="p22504mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row22505mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p22507mcpsimp"><a name="p22507mcpsimp"></a><a name="p22507mcpsimp"></a>public void onLowMemory()</p>
<p id="p22510mcpsimp"><a name="p22510mcpsimp"></a><a name="p22510mcpsimp"></a>Lifecycle method inherited from <strong id="b131371810102217"><a name="b131371810102217"></a><a name="b131371810102217"></a>Fragment</strong>.</p>
</td>
</tr>
</tbody>
</table>

## onPause<a name="section14721458546"></a>

<a name="table22518mcpsimp"></a>
<table><thead align="left"><tr id="row22522mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p22524mcpsimp"><a name="p22524mcpsimp"></a><a name="p22524mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row22525mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p22527mcpsimp"><a name="p22527mcpsimp"></a><a name="p22527mcpsimp"></a>public void onPause()</p>
<p id="p22530mcpsimp"><a name="p22530mcpsimp"></a><a name="p22530mcpsimp"></a>Lifecycle method inherited from <strong id="b46021113152214"><a name="b46021113152214"></a><a name="b46021113152214"></a>Fragment</strong>.</p>
</td>
</tr>
</tbody>
</table>

## onResume<a name="section983593585415"></a>

<a name="table22538mcpsimp"></a>
<table><thead align="left"><tr id="row22542mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p22544mcpsimp"><a name="p22544mcpsimp"></a><a name="p22544mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row22545mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p22547mcpsimp"><a name="p22547mcpsimp"></a><a name="p22547mcpsimp"></a>public void onResume()</p>
<p id="p22550mcpsimp"><a name="p22550mcpsimp"></a><a name="p22550mcpsimp"></a>Lifecycle method inherited from <strong id="b1590071510229"><a name="b1590071510229"></a><a name="b1590071510229"></a>Fragment</strong>.</p>
</td>
</tr>
</tbody>
</table>

## onSaveInstanceState<a name="section957915755513"></a>

<a name="table22558mcpsimp"></a>
<table><thead align="left"><tr id="row22562mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p22564mcpsimp"><a name="p22564mcpsimp"></a><a name="p22564mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row22565mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p22567mcpsimp"><a name="p22567mcpsimp"></a><a name="p22567mcpsimp"></a>public void onSaveInstanceState(Bundle outState)</p>
<p id="p437732455515"><a name="p437732455515"></a><a name="p437732455515"></a>Method inherited from <strong id="b136741117192210"><a name="b136741117192210"></a><a name="b136741117192210"></a>Fragment</strong> and called when <strong id="b567461722212"><a name="b567461722212"></a><a name="b567461722212"></a>Fragment</strong> is destroyed unexpectedly. It is used to save the status of a <a href="texturesupportmapfragment.md">TextureSupportMapFragment</a> object before it is destroyed. Then, the status can be retrieved when <a href="#section19132104012509">onCreate</a><strong id="b7676141718227"><a name="b7676141718227"></a><a name="b7676141718227"></a>(Bundle)</strong> is called again.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table22573mcpsimp"></a>
<table><thead align="left"><tr id="row22578mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p22580mcpsimp"><a name="p22580mcpsimp"></a><a name="p22580mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p22582mcpsimp"><a name="p22582mcpsimp"></a><a name="p22582mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row22583mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p22585mcpsimp"><a name="p22585mcpsimp"></a><a name="p22585mcpsimp"></a>outState</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p22587mcpsimp"><a name="p22587mcpsimp"></a><a name="p22587mcpsimp"></a>Status to be saved for a <a href="texturesupportmapfragment.md">TextureSupportMapFragment</a> object.</p>
</td>
</tr>
</tbody>
</table>

## onStart<a name="section1792804625518"></a>

<a name="table22592mcpsimp"></a>
<table><thead align="left"><tr id="row22596mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p22598mcpsimp"><a name="p22598mcpsimp"></a><a name="p22598mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row22599mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p22601mcpsimp"><a name="p22601mcpsimp"></a><a name="p22601mcpsimp"></a>public void onStart()</p>
<p id="p22604mcpsimp"><a name="p22604mcpsimp"></a><a name="p22604mcpsimp"></a>Lifecycle method inherited from <strong id="b1426975016226"><a name="b1426975016226"></a><a name="b1426975016226"></a>Fragment</strong>.</p>
</td>
</tr>
</tbody>
</table>

## onStop<a name="section51391716135616"></a>

<a name="table22612mcpsimp"></a>
<table><thead align="left"><tr id="row22616mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p22618mcpsimp"><a name="p22618mcpsimp"></a><a name="p22618mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row22619mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p22621mcpsimp"><a name="p22621mcpsimp"></a><a name="p22621mcpsimp"></a>public void onStop()</p>
<p id="p22624mcpsimp"><a name="p22624mcpsimp"></a><a name="p22624mcpsimp"></a>Lifecycle method inherited from <strong id="b4743153142211"><a name="b4743153142211"></a><a name="b4743153142211"></a>Fragment</strong>.</p>
</td>
</tr>
</tbody>
</table>

## setArguments<a name="section17257548135617"></a>

<a name="table22632mcpsimp"></a>
<table><thead align="left"><tr id="row22636mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p22638mcpsimp"><a name="p22638mcpsimp"></a><a name="p22638mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row22639mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p22641mcpsimp"><a name="p22641mcpsimp"></a><a name="p22641mcpsimp"></a>public void setArguments(Bundle args)</p>
<p id="p22644mcpsimp"><a name="p22644mcpsimp"></a><a name="p22644mcpsimp"></a>Method inherited from <strong id="b175456162215"><a name="b175456162215"></a><a name="b175456162215"></a>Fragment</strong> and called when data needs to be passed to <strong id="b861256182213"><a name="b861256182213"></a><a name="b861256182213"></a>Fragment</strong>.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table22647mcpsimp"></a>
<table><thead align="left"><tr id="row22652mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p22654mcpsimp"><a name="p22654mcpsimp"></a><a name="p22654mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p22656mcpsimp"><a name="p22656mcpsimp"></a><a name="p22656mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row22657mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p22659mcpsimp"><a name="p22659mcpsimp"></a><a name="p22659mcpsimp"></a>args</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p22661mcpsimp"><a name="p22661mcpsimp"></a><a name="p22661mcpsimp"></a>Data to be passed to <a href="texturesupportmapfragment.md">TextureSupportMapFragment</a>.</p>
</td>
</tr>
</tbody>
</table>

