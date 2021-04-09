# SupportMapFragment<a name="EN-US_TOPIC_0000001145541123"></a>

-   [Public Constructor Summary](#section123311785567)
-   [Public Method Summary](#section47328285717)
-   [Public Methods](#section9438103916458)
-   [getMapAsync](#section1874811557456)
-   [newInstance\(HuaweiMapOptions options\)](#section72194211462)
-   [newInstance\(\)](#section13140131974714)
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
<tbody><tr id="row22011mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p1480874182718"><a name="p1480874182718"></a><a name="p1480874182718"></a>public class SupportMapFragment</p>
<p id="p22013mcpsimp"><a name="p22013mcpsimp"></a><a name="p22013mcpsimp"></a>Map component in an app, which can be used to add a map to the app in the simplest way. To obtain the map manager, call <a href="#section1874811557456">getMapAsync</a>.</p>
</td>
</tr>
</tbody>
</table>

## Public Constructor Summary<a name="section123311785567"></a>

<a name="table22017mcpsimp"></a>
<table><thead align="left"><tr id="row22021mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p145mcpsimp"><a name="p145mcpsimp"></a><a name="p145mcpsimp"></a>Constructor Name</p>
</th>
</tr>
</thead>
<tbody><tr id="row22024mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p22026mcpsimp"><a name="p22026mcpsimp"></a><a name="p22026mcpsimp"></a><a href="supportmapfragment.md">SupportMapFragment</a>()</p>
<p id="p141584544335"><a name="p141584544335"></a><a name="p141584544335"></a>Default constructor of the <strong id="b68123111127"><a name="b68123111127"></a><a name="b68123111127"></a>SupportMapFragment</strong> class.</p>
</td>
</tr>
</tbody>
</table>

## Public Method Summary<a name="section47328285717"></a>

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
<p id="p1642716101643"><a name="p1642716101643"></a><a name="p1642716101643"></a>Obtains a <a href="huaweimap.md">HuaweiMap</a> object when the object is ready. </p>
</td>
</tr>
<tr id="row22043mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p22045mcpsimp"><a name="p22045mcpsimp"></a><a name="p22045mcpsimp"></a>static <a href="supportmapfragment.md">SupportMapFragment</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p22047mcpsimp"><a name="p22047mcpsimp"></a><a name="p22047mcpsimp"></a><a href="#section72194211462">newInstance</a>(<a href="huaweimapooptions.md">HuaweiMapOptions</a> options)</p>
<p id="p135437309310"><a name="p135437309310"></a><a name="p135437309310"></a>Creates a <a href="supportmapfragment.md">SupportMapFragment</a> object with specified attributes.</p>
</td>
</tr>
<tr id="row22048mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p22050mcpsimp"><a name="p22050mcpsimp"></a><a name="p22050mcpsimp"></a>static <a href="supportmapfragment.md">SupportMapFragment</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p22052mcpsimp"><a name="p22052mcpsimp"></a><a name="p22052mcpsimp"></a><a href="#section13140131974714">newInstance()</a></p>
<p id="p9768361132"><a name="p9768361132"></a><a name="p9768361132"></a>Creates a <a href="supportmapfragment.md">SupportMapFragment</a> object with default attributes.</p>
</td>
</tr>
<tr id="row22053mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p22055mcpsimp"><a name="p22055mcpsimp"></a><a name="p22055mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p22057mcpsimp"><a name="p22057mcpsimp"></a><a name="p22057mcpsimp"></a><a href="#section00182374920">onActivityCreated</a>(Bundle savedInstanceState)</p>
<p id="p172126371735"><a name="p172126371735"></a><a name="p172126371735"></a>Lifecycle method inherited from <strong id="b15446458155017"><a name="b15446458155017"></a><a name="b15446458155017"></a>Fragment</strong>.</p>
</td>
</tr>
<tr id="row22058mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p22060mcpsimp"><a name="p22060mcpsimp"></a><a name="p22060mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p22062mcpsimp"><a name="p22062mcpsimp"></a><a name="p22062mcpsimp"></a><a href="#section10531135894915">onAttach</a>(Activity activity)</p>
<p id="p13252163811317"><a name="p13252163811317"></a><a name="p13252163811317"></a>Lifecycle method inherited from <strong id="b1810172125114"><a name="b1810172125114"></a><a name="b1810172125114"></a>Fragment</strong>.</p>
</td>
</tr>
<tr id="row22063mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p22065mcpsimp"><a name="p22065mcpsimp"></a><a name="p22065mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p22067mcpsimp"><a name="p22067mcpsimp"></a><a name="p22067mcpsimp"></a><a href="#section19132104012509">onCreate</a>(Bundle savedInstanceState)</p>
<p id="p4714393313"><a name="p4714393313"></a><a name="p4714393313"></a>Lifecycle method inherited from <strong id="b1168019335116"><a name="b1168019335116"></a><a name="b1168019335116"></a>Fragment</strong>.</p>
</td>
</tr>
<tr id="row22068mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p22070mcpsimp"><a name="p22070mcpsimp"></a><a name="p22070mcpsimp"></a>View</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p22072mcpsimp"><a name="p22072mcpsimp"></a><a name="p22072mcpsimp"></a><a href="#section648115222519">onCreateView</a>(LayoutInflater inflater, ViewGroup container, Bundle savedInstanceState)</p>
<p id="p122924401736"><a name="p122924401736"></a><a name="p122924401736"></a>Lifecycle method inherited from <strong id="b11677465110"><a name="b11677465110"></a><a name="b11677465110"></a>Fragment</strong>.</p>
</td>
</tr>
<tr id="row22073mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p22075mcpsimp"><a name="p22075mcpsimp"></a><a name="p22075mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p22077mcpsimp"><a name="p22077mcpsimp"></a><a name="p22077mcpsimp"></a><a href="#section11273709522">onDestroy</a>()</p>
<p id="p1021912411137"><a name="p1021912411137"></a><a name="p1021912411137"></a>Lifecycle method inherited from <strong id="b182671495111"><a name="b182671495111"></a><a name="b182671495111"></a>Fragment</strong>.</p>
</td>
</tr>
<tr id="row22078mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p22080mcpsimp"><a name="p22080mcpsimp"></a><a name="p22080mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p22082mcpsimp"><a name="p22082mcpsimp"></a><a name="p22082mcpsimp"></a><a href="#section032617282527">onDestroyView</a>()</p>
<p id="p19240154217317"><a name="p19240154217317"></a><a name="p19240154217317"></a>Lifecycle method inherited from <strong id="b543419410515"><a name="b543419410515"></a><a name="b543419410515"></a>Fragment</strong>.</p>
</td>
</tr>
<tr id="row22093mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p22095mcpsimp"><a name="p22095mcpsimp"></a><a name="p22095mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p22097mcpsimp"><a name="p22097mcpsimp"></a><a name="p22097mcpsimp"></a><a href="#section1229121125312">onInflate</a>(Activity activity, AttributeSet attrs, Bundle savedInstanceState)</p>
<p id="p988719441834"><a name="p988719441834"></a><a name="p988719441834"></a>Lifecycle method inherited from <strong id="b2087311405115"><a name="b2087311405115"></a><a name="b2087311405115"></a>Fragment</strong>. This method is called when <a href="supportmapfragment.md">SupportMapFragment</a> is statically loaded in XML mode. </p>
</td>
</tr>
<tr id="row22098mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p22100mcpsimp"><a name="p22100mcpsimp"></a><a name="p22100mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p22102mcpsimp"><a name="p22102mcpsimp"></a><a name="p22102mcpsimp"></a><a href="#section29326333532">onLowMemory</a>()</p>
<p id="p197853659"><a name="p197853659"></a><a name="p197853659"></a>Lifecycle method inherited from <strong id="b13920918125118"><a name="b13920918125118"></a><a name="b13920918125118"></a>Fragment</strong>.</p>
</td>
</tr>
<tr id="row22103mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p22105mcpsimp"><a name="p22105mcpsimp"></a><a name="p22105mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p22107mcpsimp"><a name="p22107mcpsimp"></a><a name="p22107mcpsimp"></a><a href="#section14721458546">onPause</a>()</p>
<p id="p17471472030"><a name="p17471472030"></a><a name="p17471472030"></a>Lifecycle method inherited from <strong id="b1269542175117"><a name="b1269542175117"></a><a name="b1269542175117"></a>Fragment</strong>.</p>
</td>
</tr>
<tr id="row22108mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p22110mcpsimp"><a name="p22110mcpsimp"></a><a name="p22110mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p22112mcpsimp"><a name="p22112mcpsimp"></a><a name="p22112mcpsimp"></a><a href="#section983593585415">onResume</a>()</p>
<p id="p1294811471438"><a name="p1294811471438"></a><a name="p1294811471438"></a>Lifecycle method inherited from <strong id="b159351121165118"><a name="b159351121165118"></a><a name="b159351121165118"></a>Fragment</strong>.</p>
</td>
</tr>
<tr id="row22113mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p22115mcpsimp"><a name="p22115mcpsimp"></a><a name="p22115mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p22117mcpsimp"><a name="p22117mcpsimp"></a><a name="p22117mcpsimp"></a><a href="#section957915755513">onSaveInstanceState</a>(Bundle outState)</p>
<p id="p199128481032"><a name="p199128481032"></a><a name="p199128481032"></a>Lifecycle method inherited from <strong id="b99403224510"><a name="b99403224510"></a><a name="b99403224510"></a>Fragment</strong> and called when <strong id="b194062295116"><a name="b194062295116"></a><a name="b194062295116"></a>Fragment</strong> is destroyed unexpectedly. It is used to save the status of a <a href="supportmapfragment.md">SupportMapFragment</a> object before it is destroyed. Then, the status can be retrieved when <strong id="b294112205114"><a name="b294112205114"></a><a name="b294112205114"></a>onCreate(Bundle)</strong> is called again.</p>
</td>
</tr>
<tr id="row22118mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p22120mcpsimp"><a name="p22120mcpsimp"></a><a name="p22120mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p22122mcpsimp"><a name="p22122mcpsimp"></a><a name="p22122mcpsimp"></a><a href="#section1792804625518">onStart</a>()</p>
<p id="p3909124915311"><a name="p3909124915311"></a><a name="p3909124915311"></a>Lifecycle method inherited from <strong id="b196729645217"><a name="b196729645217"></a><a name="b196729645217"></a>Fragment</strong>.</p>
</td>
</tr>
<tr id="row22123mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p22125mcpsimp"><a name="p22125mcpsimp"></a><a name="p22125mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p22127mcpsimp"><a name="p22127mcpsimp"></a><a name="p22127mcpsimp"></a><a href="#section51391716135616">onStop</a>()</p>
<p id="p1274216501332"><a name="p1274216501332"></a><a name="p1274216501332"></a>Lifecycle method inherited from <strong id="b656111010522"><a name="b656111010522"></a><a name="b656111010522"></a>Fragment</strong>.</p>
</td>
</tr>
<tr id="row22128mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p22130mcpsimp"><a name="p22130mcpsimp"></a><a name="p22130mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p22132mcpsimp"><a name="p22132mcpsimp"></a><a name="p22132mcpsimp"></a><a href="#section17257548135617">setArguments</a>(Bundle args)</p>
<p id="p166521252931"><a name="p166521252931"></a><a name="p166521252931"></a>Lifecycle method inherited from <strong id="b1524561312522"><a name="b1524561312522"></a><a name="b1524561312522"></a>Fragment</strong> and called when data needs to be passed to <strong id="b7251101335220"><a name="b7251101335220"></a><a name="b7251101335220"></a>Fragment</strong>.</p>
</td>
</tr>
</tbody>
</table>

## Public Methods<a name="section9438103916458"></a>

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
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p22167mcpsimp"><a name="p22167mcpsimp"></a><a name="p22167mcpsimp"></a>Callback to be triggered when a map is ready for use.</p>
</td>
</tr>
</tbody>
</table>

## newInstance\(HuaweiMapOptions options\)<a name="section72194211462"></a>

<a name="table22172mcpsimp"></a>
<table><thead align="left"><tr id="row22176mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p22178mcpsimp"><a name="p22178mcpsimp"></a><a name="p22178mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row22179mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p22181mcpsimp"><a name="p22181mcpsimp"></a><a name="p22181mcpsimp"></a>public static <a href="supportmapfragment.md">SupportMapFragment</a> newInstance(<a href="huaweimapooptions.md">HuaweiMapOptions</a> options)</p>
<p id="p1280111194718"><a name="p1280111194718"></a><a name="p1280111194718"></a>Creates a <a href="supportmapfragment.md">SupportMapFragment</a> object with specified attributes.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table22187mcpsimp"></a>
<table><thead align="left"><tr id="row22192mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p22194mcpsimp"><a name="p22194mcpsimp"></a><a name="p22194mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p22196mcpsimp"><a name="p22196mcpsimp"></a><a name="p22196mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row22197mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p22199mcpsimp"><a name="p22199mcpsimp"></a><a name="p22199mcpsimp"></a>options</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p22201mcpsimp"><a name="p22201mcpsimp"></a><a name="p22201mcpsimp"></a>Attributes required for creating a <a href="supportmapfragment.md">SupportMapFragment</a> object.</p>
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
<tbody><tr id="row22214mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p22216mcpsimp"><a name="p22216mcpsimp"></a><a name="p22216mcpsimp"></a>SupportMapFragment</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p22218mcpsimp"><a name="p22218mcpsimp"></a><a name="p22218mcpsimp"></a><a href="supportmapfragment.md">SupportMapFragment</a> object.</p>
</td>
</tr>
</tbody>
</table>

## newInstance\(\)<a name="section13140131974714"></a>

<a name="table22220mcpsimp"></a>
<table><thead align="left"><tr id="row22224mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p22226mcpsimp"><a name="p22226mcpsimp"></a><a name="p22226mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row22227mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p22229mcpsimp"><a name="p22229mcpsimp"></a><a name="p22229mcpsimp"></a>public static <a href="supportmapfragment.md">SupportMapFragment</a> newInstance()</p>
<p id="p6977121311483"><a name="p6977121311483"></a><a name="p6977121311483"></a>Creates a <a href="supportmapfragment.md">SupportMapFragment</a> object with default attributes.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table22238mcpsimp"></a>
<table><thead align="left"><tr id="row22243mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p22245mcpsimp"><a name="p22245mcpsimp"></a><a name="p22245mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p22247mcpsimp"><a name="p22247mcpsimp"></a><a name="p22247mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row22248mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p22250mcpsimp"><a name="p22250mcpsimp"></a><a name="p22250mcpsimp"></a>SupportMapFragment</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p22252mcpsimp"><a name="p22252mcpsimp"></a><a name="p22252mcpsimp"></a><a href="supportmapfragment.md">SupportMapFragment</a> object.</p>
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
<p id="p163342396498"><a name="p163342396498"></a><a name="p163342396498"></a>Lifecycle method inherited from <strong id="b1081419571410"><a name="b1081419571410"></a><a name="b1081419571410"></a>Fragment</strong>.</p>
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
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p22283mcpsimp"><a name="p22283mcpsimp"></a><a name="p22283mcpsimp"></a>Status to be saved for a <a href="supportmapfragment.md">SupportMapFragment</a> object.</p>
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
<p id="p22300mcpsimp"><a name="p22300mcpsimp"></a><a name="p22300mcpsimp"></a>Lifecycle method inherited from <strong id="b9666115191515"><a name="b9666115191515"></a><a name="b9666115191515"></a>Fragment</strong>.</p>
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
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p22317mcpsimp"><a name="p22317mcpsimp"></a><a name="p22317mcpsimp"></a>Activity object bound to <a href="supportmapfragment.md">SupportMapFragment</a>.</p>
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
<p id="p22334mcpsimp"><a name="p22334mcpsimp"></a><a name="p22334mcpsimp"></a>Lifecycle method inherited from <strong id="b2030612239157"><a name="b2030612239157"></a><a name="b2030612239157"></a>Fragment</strong>.</p>
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
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p22351mcpsimp"><a name="p22351mcpsimp"></a><a name="p22351mcpsimp"></a>Status to be saved for a <a href="supportmapfragment.md">SupportMapFragment</a> object.</p>
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
<p id="p22368mcpsimp"><a name="p22368mcpsimp"></a><a name="p22368mcpsimp"></a>Lifecycle method inherited from <strong id="b148681523171615"><a name="b148681523171615"></a><a name="b148681523171615"></a>Fragment</strong>.</p>
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
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p22385mcpsimp"><a name="p22385mcpsimp"></a><a name="p22385mcpsimp"></a><strong id="b1718262721618"><a name="b1718262721618"></a><a name="b1718262721618"></a>LayoutInflater</strong> object, which is used to search for controls in a layout.</p>
</td>
</tr>
<tr id="row22386mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p22388mcpsimp"><a name="p22388mcpsimp"></a><a name="p22388mcpsimp"></a>container</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p22390mcpsimp"><a name="p22390mcpsimp"></a><a name="p22390mcpsimp"></a>Layout container.</p>
</td>
</tr>
<tr id="row22391mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p22393mcpsimp"><a name="p22393mcpsimp"></a><a name="p22393mcpsimp"></a>savedInstanceState</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p22395mcpsimp"><a name="p22395mcpsimp"></a><a name="p22395mcpsimp"></a>Status to be saved for a <a href="supportmapfragment.md">SupportMapFragment</a> object.</p>
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
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p22412mcpsimp"><a name="p22412mcpsimp"></a><a name="p22412mcpsimp"></a><strong id="b18361173971618"><a name="b18361173971618"></a><a name="b18361173971618"></a>View</strong> object.</p>
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
<p id="p22426mcpsimp"><a name="p22426mcpsimp"></a><a name="p22426mcpsimp"></a>Lifecycle method inherited from <strong id="b16402144571617"><a name="b16402144571617"></a><a name="b16402144571617"></a>Fragment</strong>.</p>
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
<p id="p22446mcpsimp"><a name="p22446mcpsimp"></a><a name="p22446mcpsimp"></a>Lifecycle method inherited from <strong id="b464065015162"><a name="b464065015162"></a><a name="b464065015162"></a>Fragment</strong>.</p>
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
<p id="p22466mcpsimp"><a name="p22466mcpsimp"></a><a name="p22466mcpsimp"></a>Lifecycle method inherited from <strong id="b1340717413514"><a name="b1340717413514"></a><a name="b1340717413514"></a>Fragment</strong>. This method is called when <a href="supportmapfragment.md">SupportMapFragment</a> is statically loaded in XML mode. </p>
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
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p22483mcpsimp"><a name="p22483mcpsimp"></a><a name="p22483mcpsimp"></a>Activity object bound to <a href="supportmapfragment.md">SupportMapFragment</a>.</p>
</td>
</tr>
<tr id="row22484mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p22486mcpsimp"><a name="p22486mcpsimp"></a><a name="p22486mcpsimp"></a>attrs</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p22488mcpsimp"><a name="p22488mcpsimp"></a><a name="p22488mcpsimp"></a>Attributes used to create a <a href="supportmapfragment.md">SupportMapFragment</a> object.</p>
</td>
</tr>
<tr id="row22489mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p22491mcpsimp"><a name="p22491mcpsimp"></a><a name="p22491mcpsimp"></a>savedInstanceState</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p22493mcpsimp"><a name="p22493mcpsimp"></a><a name="p22493mcpsimp"></a>Status to be saved for a <a href="supportmapfragment.md">SupportMapFragment</a> object.</p>
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
<p id="p22510mcpsimp"><a name="p22510mcpsimp"></a><a name="p22510mcpsimp"></a>Lifecycle method inherited from <strong id="b558544016173"><a name="b558544016173"></a><a name="b558544016173"></a>Fragment</strong>.</p>
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
<p id="p22530mcpsimp"><a name="p22530mcpsimp"></a><a name="p22530mcpsimp"></a>Lifecycle method inherited from <strong id="b81631846131715"><a name="b81631846131715"></a><a name="b81631846131715"></a>Fragment</strong>.</p>
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
<p id="p22550mcpsimp"><a name="p22550mcpsimp"></a><a name="p22550mcpsimp"></a>Lifecycle method inherited from <strong id="b133071510174"><a name="b133071510174"></a><a name="b133071510174"></a>Fragment</strong>.</p>
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
<p id="p437732455515"><a name="p437732455515"></a><a name="p437732455515"></a>Method inherited from <strong id="b1281035515174"><a name="b1281035515174"></a><a name="b1281035515174"></a>Fragment</strong> and called when <strong id="b7815195551713"><a name="b7815195551713"></a><a name="b7815195551713"></a>Fragment</strong> is destroyed unexpectedly. It is used to save the status of a <a href="supportmapfragment.md">SupportMapFragment</a> object before it is destroyed. Then, the status can be retrieved when <strong id="b198161355111716"><a name="b198161355111716"></a><a name="b198161355111716"></a>onCreate(Bundle)</strong> is called again.</p>
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
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p22587mcpsimp"><a name="p22587mcpsimp"></a><a name="p22587mcpsimp"></a>Status to be saved for a <a href="supportmapfragment.md">SupportMapFragment</a> object.</p>
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
<p id="p22604mcpsimp"><a name="p22604mcpsimp"></a><a name="p22604mcpsimp"></a>Lifecycle method inherited from <strong id="b421827112819"><a name="b421827112819"></a><a name="b421827112819"></a>Fragment</strong>.</p>
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
<p id="p22624mcpsimp"><a name="p22624mcpsimp"></a><a name="p22624mcpsimp"></a>Lifecycle method inherited from <strong id="b18231836202813"><a name="b18231836202813"></a><a name="b18231836202813"></a>Fragment</strong>.</p>
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
<p id="p22644mcpsimp"><a name="p22644mcpsimp"></a><a name="p22644mcpsimp"></a>Method inherited from <strong id="b669311502915"><a name="b669311502915"></a><a name="b669311502915"></a>Fragment</strong> and called when data needs to be passed to <strong id="b5794329192920"><a name="b5794329192920"></a><a name="b5794329192920"></a>Fragment</strong>.</p>
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
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p22661mcpsimp"><a name="p22661mcpsimp"></a><a name="p22661mcpsimp"></a>Data to be passed to <a href="supportmapfragment.md">SupportMapFragment</a>.</p>
</td>
</tr>
</tbody>
</table>

