# SupportMapFragment<a name="ZH-CN_TOPIC_0000001145541123"></a>

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
<p id="p22013mcpsimp"><a name="p22013mcpsimp"></a><a name="p22013mcpsimp"></a>应用中的地图组件，是应用中放置地图的最简单的方式。通过<a href="#section1874811557456">getMapAsync</a>，获取地图管理器。</p>
<p id="p188623134576"><a name="p188623134576"></a><a name="p188623134576"></a><a href="huaweimap.md">HuaweiMap</a>对象必须使用<a href="#section1874811557456">getMapAsync</a>(<a href="onmapreadycallback.md">OnMapReadyCallback</a> callback)获取，此类会自动初始化地图系统和视图。</p>
<p id="p686214130578"><a name="p686214130578"></a><a name="p686214130578"></a>从<a href="huaweimap.md">HuaweiMap</a>获取的任何对象都与视图关联，不要在视图的生命周期之外保留对象（例如：标记），否则将导致内存泄漏，因为视图无法释放。</p>
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
<p id="p141584544335"><a name="p141584544335"></a><a name="p141584544335"></a>SupportMapFragment类的默认构造方法。</p>
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
<p id="p1642716101643"><a name="p1642716101643"></a><a name="p1642716101643"></a>当地图对象准备就绪时，就会触发此接口回调，获取<a href="huaweimap.md">HuaweiMap</a>对象。</p>
</td>
</tr>
<tr id="row22043mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p22045mcpsimp"><a name="p22045mcpsimp"></a><a name="p22045mcpsimp"></a>static <a href="supportmapfragment.md">SupportMapFragment</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p22047mcpsimp"><a name="p22047mcpsimp"></a><a name="p22047mcpsimp"></a><a href="#section72194211462">newInstance</a>(<a href="huaweimapooptions.md">HuaweiMapOptions</a> options)</p>
<p id="p135437309310"><a name="p135437309310"></a><a name="p135437309310"></a>用于创建指定属性的<a href="supportmapfragment.md">SupportMapFragment</a>对象。</p>
</td>
</tr>
<tr id="row22048mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p22050mcpsimp"><a name="p22050mcpsimp"></a><a name="p22050mcpsimp"></a>static <a href="supportmapfragment.md">SupportMapFragment</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p22052mcpsimp"><a name="p22052mcpsimp"></a><a name="p22052mcpsimp"></a><a href="#section13140131974714">newInstance()</a></p>
<p id="p9768361132"><a name="p9768361132"></a><a name="p9768361132"></a>用于创建默认属性的<a href="supportmapfragment.md">SupportMapFragment</a>对象。</p>
</td>
</tr>
<tr id="row22053mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p22055mcpsimp"><a name="p22055mcpsimp"></a><a name="p22055mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p22057mcpsimp"><a name="p22057mcpsimp"></a><a name="p22057mcpsimp"></a><a href="#section00182374920">onActivityCreated</a>(Bundle savedInstanceState)</p>
<p id="p172126371735"><a name="p172126371735"></a><a name="p172126371735"></a>继承自Fragment的生命周期方法。</p>
</td>
</tr>
<tr id="row22058mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p22060mcpsimp"><a name="p22060mcpsimp"></a><a name="p22060mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p22062mcpsimp"><a name="p22062mcpsimp"></a><a name="p22062mcpsimp"></a><a href="#section10531135894915">onAttach</a>(Activity activity)</p>
<p id="p13252163811317"><a name="p13252163811317"></a><a name="p13252163811317"></a>继承自Fragment的生命周期方法。</p>
</td>
</tr>
<tr id="row22063mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p22065mcpsimp"><a name="p22065mcpsimp"></a><a name="p22065mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p22067mcpsimp"><a name="p22067mcpsimp"></a><a name="p22067mcpsimp"></a><a href="#section19132104012509">onCreate</a>(Bundle savedInstanceState)</p>
<p id="p4714393313"><a name="p4714393313"></a><a name="p4714393313"></a>继承自Fragment的生命周期方法。</p>
</td>
</tr>
<tr id="row22068mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p22070mcpsimp"><a name="p22070mcpsimp"></a><a name="p22070mcpsimp"></a>View</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p22072mcpsimp"><a name="p22072mcpsimp"></a><a name="p22072mcpsimp"></a><a href="#section648115222519">onCreateView</a>(LayoutInflater inflater, ViewGroup container, Bundle savedInstanceState)</p>
<p id="p122924401736"><a name="p122924401736"></a><a name="p122924401736"></a>继承自Fragment的生命周期方法。</p>
</td>
</tr>
<tr id="row22073mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p22075mcpsimp"><a name="p22075mcpsimp"></a><a name="p22075mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p22077mcpsimp"><a name="p22077mcpsimp"></a><a name="p22077mcpsimp"></a><a href="#section11273709522">onDestroy</a>()</p>
<p id="p1021912411137"><a name="p1021912411137"></a><a name="p1021912411137"></a>继承自Fragment的生命周期方法。</p>
</td>
</tr>
<tr id="row22078mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p22080mcpsimp"><a name="p22080mcpsimp"></a><a name="p22080mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p22082mcpsimp"><a name="p22082mcpsimp"></a><a name="p22082mcpsimp"></a><a href="#section032617282527">onDestroyView</a>()</p>
<p id="p19240154217317"><a name="p19240154217317"></a><a name="p19240154217317"></a>继承自Fragment的生命周期方法。</p>
</td>
</tr>
<tr id="row22093mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p22095mcpsimp"><a name="p22095mcpsimp"></a><a name="p22095mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p22097mcpsimp"><a name="p22097mcpsimp"></a><a name="p22097mcpsimp"></a><a href="#section1229121125312">onInflate</a>(Activity activity, AttributeSet attrs, Bundle savedInstanceState)</p>
<p id="p988719441834"><a name="p988719441834"></a><a name="p988719441834"></a>继承自Fragment的生命周期方法，<a href="supportmapfragment.md">SupportMapFragment</a>以XML方式静态加载时调用。</p>
</td>
</tr>
<tr id="row22098mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p22100mcpsimp"><a name="p22100mcpsimp"></a><a name="p22100mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p22102mcpsimp"><a name="p22102mcpsimp"></a><a name="p22102mcpsimp"></a><a href="#section29326333532">onLowMemory</a>()</p>
<p id="p197853659"><a name="p197853659"></a><a name="p197853659"></a>继承自Fragment的生命周期方法。</p>
</td>
</tr>
<tr id="row22103mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p22105mcpsimp"><a name="p22105mcpsimp"></a><a name="p22105mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p22107mcpsimp"><a name="p22107mcpsimp"></a><a name="p22107mcpsimp"></a><a href="#section14721458546">onPause</a>()</p>
<p id="p17471472030"><a name="p17471472030"></a><a name="p17471472030"></a>继承自Fragment的生命周期方法。</p>
</td>
</tr>
<tr id="row22108mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p22110mcpsimp"><a name="p22110mcpsimp"></a><a name="p22110mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p22112mcpsimp"><a name="p22112mcpsimp"></a><a name="p22112mcpsimp"></a><a href="#section983593585415">onResume</a>()</p>
<p id="p1294811471438"><a name="p1294811471438"></a><a name="p1294811471438"></a>继承自Fragment的生命周期方法。</p>
</td>
</tr>
<tr id="row22113mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p22115mcpsimp"><a name="p22115mcpsimp"></a><a name="p22115mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p22117mcpsimp"><a name="p22117mcpsimp"></a><a name="p22117mcpsimp"></a><a href="#section957915755513">onSaveInstanceState</a>(Bundle outState)</p>
<p id="p199128481032"><a name="p199128481032"></a><a name="p199128481032"></a>继承自Fragment的生命周期方法，Fragment异常销毁时调用，用来存储<a href="supportmapfragment.md">SupportMapFragment</a>在销毁之前的状态，可以在再次调用onCreate(Bundle)时检索它。</p>
</td>
</tr>
<tr id="row22118mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p22120mcpsimp"><a name="p22120mcpsimp"></a><a name="p22120mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p22122mcpsimp"><a name="p22122mcpsimp"></a><a name="p22122mcpsimp"></a><a href="#section1792804625518">onStart</a>()</p>
<p id="p3909124915311"><a name="p3909124915311"></a><a name="p3909124915311"></a>继承自Fragment的生命周期方法。</p>
</td>
</tr>
<tr id="row22123mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p22125mcpsimp"><a name="p22125mcpsimp"></a><a name="p22125mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p22127mcpsimp"><a name="p22127mcpsimp"></a><a name="p22127mcpsimp"></a><a href="#section51391716135616">onStop</a>()</p>
<p id="p1274216501332"><a name="p1274216501332"></a><a name="p1274216501332"></a>继承自Fragment的生命周期方法。</p>
</td>
</tr>
<tr id="row22128mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p22130mcpsimp"><a name="p22130mcpsimp"></a><a name="p22130mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p22132mcpsimp"><a name="p22132mcpsimp"></a><a name="p22132mcpsimp"></a><a href="#section17257548135617">setArguments</a>(Bundle args)</p>
<p id="p166521252931"><a name="p166521252931"></a><a name="p166521252931"></a>继承自Fragment的生命周期方法，当需要向Fragment传递数据时调用。</p>
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
<p id="p206900148464"><a name="p206900148464"></a><a name="p206900148464"></a>当地图对象准备就绪时，就会触发此接口回调，获取<a href="huaweimap.md">HuaweiMap</a>对象。</p>
<div class="note" id="note972011303527"><a name="note972011303527"></a><a name="note972011303527"></a><span class="notetitle"> 说明： </span><div class="notebody"><a name="ul62963817538"></a><a name="ul62963817538"></a><ul id="ul62963817538"><li>必须在主线程调用此方法。</li><li>回调将在主线程中执行。</li><li>在极少数情况下，创建后立即销毁<a href="huaweimap.md">HuaweiMap</a>时，不会触发回调。</li><li><a href="huaweimap.md">HuaweiMap</a>回调提供的对象为非null。</li></ul>
</div></div>
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
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p22167mcpsimp"><a name="p22167mcpsimp"></a><a name="p22167mcpsimp"></a>当地图准备就绪时被触发的回调对象。</p>
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
<p id="p1280111194718"><a name="p1280111194718"></a><a name="p1280111194718"></a>用于创建指定属性的<a href="supportmapfragment.md">SupportMapFragment</a>对象。</p>
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
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p22201mcpsimp"><a name="p22201mcpsimp"></a><a name="p22201mcpsimp"></a>用于创建<a href="supportmapfragment.md">SupportMapFragment</a>对象所需的属性。</p>
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
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p22218mcpsimp"><a name="p22218mcpsimp"></a><a name="p22218mcpsimp"></a><a href="supportmapfragment.md">SupportMapFragment</a>对象。</p>
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
<p id="p6977121311483"><a name="p6977121311483"></a><a name="p6977121311483"></a>用于创建默认属性的<a href="supportmapfragment.md">SupportMapFragment</a>对象。</p>
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
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p22252mcpsimp"><a name="p22252mcpsimp"></a><a name="p22252mcpsimp"></a><a href="supportmapfragment.md">SupportMapFragment</a>对象。</p>
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
<p id="p163342396498"><a name="p163342396498"></a><a name="p163342396498"></a>继承自Fragment的生命周期方法。</p>
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
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p22283mcpsimp"><a name="p22283mcpsimp"></a><a name="p22283mcpsimp"></a>保存<a href="supportmapfragment.md">SupportMapFragment</a>状态。</p>
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
<p id="p22300mcpsimp"><a name="p22300mcpsimp"></a><a name="p22300mcpsimp"></a>继承自Fragment的生命周期方法。</p>
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
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p22317mcpsimp"><a name="p22317mcpsimp"></a><a name="p22317mcpsimp"></a><a href="supportmapfragment.md">SupportMapFragment</a>绑定的Activity对象。</p>
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
<p id="p22334mcpsimp"><a name="p22334mcpsimp"></a><a name="p22334mcpsimp"></a>继承自Fragment的生命周期方法。</p>
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
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p22351mcpsimp"><a name="p22351mcpsimp"></a><a name="p22351mcpsimp"></a>保存<a href="supportmapfragment.md">SupportMapFragment</a>状态。</p>
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
<p id="p22368mcpsimp"><a name="p22368mcpsimp"></a><a name="p22368mcpsimp"></a>继承自Fragment的生命周期方法。</p>
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
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p22385mcpsimp"><a name="p22385mcpsimp"></a><a name="p22385mcpsimp"></a>LayoutInflater对象，用来寻找布局中的控件。</p>
</td>
</tr>
<tr id="row22386mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p22388mcpsimp"><a name="p22388mcpsimp"></a><a name="p22388mcpsimp"></a>container</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p22390mcpsimp"><a name="p22390mcpsimp"></a><a name="p22390mcpsimp"></a>布局容器。</p>
</td>
</tr>
<tr id="row22391mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p22393mcpsimp"><a name="p22393mcpsimp"></a><a name="p22393mcpsimp"></a>savedInstanceState</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p22395mcpsimp"><a name="p22395mcpsimp"></a><a name="p22395mcpsimp"></a>保存<a href="supportmapfragment.md">SupportMapFragment</a>状态。</p>
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
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p22412mcpsimp"><a name="p22412mcpsimp"></a><a name="p22412mcpsimp"></a>View对象。</p>
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
<p id="p22426mcpsimp"><a name="p22426mcpsimp"></a><a name="p22426mcpsimp"></a>继承自Fragment的生命周期方法。</p>
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
<p id="p22446mcpsimp"><a name="p22446mcpsimp"></a><a name="p22446mcpsimp"></a>继承自Fragment的生命周期方法。</p>
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
<p id="p22466mcpsimp"><a name="p22466mcpsimp"></a><a name="p22466mcpsimp"></a>继承自Fragment的生命周期方法，<a href="supportmapfragment.md">SupportMapFragment</a>以XML方式静态加载时调用。</p>
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
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p22483mcpsimp"><a name="p22483mcpsimp"></a><a name="p22483mcpsimp"></a><a href="supportmapfragment.md">SupportMapFragment</a>绑定的Activity对象。</p>
</td>
</tr>
<tr id="row22484mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p22486mcpsimp"><a name="p22486mcpsimp"></a><a name="p22486mcpsimp"></a>attrs</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p22488mcpsimp"><a name="p22488mcpsimp"></a><a name="p22488mcpsimp"></a>创建<a href="supportmapfragment.md">SupportMapFragment</a>时的属性。</p>
</td>
</tr>
<tr id="row22489mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p22491mcpsimp"><a name="p22491mcpsimp"></a><a name="p22491mcpsimp"></a>savedInstanceState</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p22493mcpsimp"><a name="p22493mcpsimp"></a><a name="p22493mcpsimp"></a>保存<a href="supportmapfragment.md">SupportMapFragment</a>状态。</p>
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
<p id="p22510mcpsimp"><a name="p22510mcpsimp"></a><a name="p22510mcpsimp"></a>继承自Fragment的生命周期方法。</p>
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
<p id="p22530mcpsimp"><a name="p22530mcpsimp"></a><a name="p22530mcpsimp"></a>继承自Fragment的生命周期方法。</p>
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
<p id="p22550mcpsimp"><a name="p22550mcpsimp"></a><a name="p22550mcpsimp"></a>继承自Fragment的生命周期方法。</p>
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
<p id="p437732455515"><a name="p437732455515"></a><a name="p437732455515"></a>继承自Fragment的生命周期方法，Fragment异常销毁时调用，用来存储<a href="supportmapfragment.md">SupportMapFragment</a>在销毁之前的状态，可以在再次调用onCreate(Bundle)时检索它。</p>
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
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p22587mcpsimp"><a name="p22587mcpsimp"></a><a name="p22587mcpsimp"></a>保存<a href="supportmapfragment.md">SupportMapFragment</a>状态。</p>
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
<p id="p22604mcpsimp"><a name="p22604mcpsimp"></a><a name="p22604mcpsimp"></a>继承自Fragment的生命周期方法。</p>
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
<p id="p22624mcpsimp"><a name="p22624mcpsimp"></a><a name="p22624mcpsimp"></a>继承自Fragment的生命周期方法。</p>
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
<p id="p22644mcpsimp"><a name="p22644mcpsimp"></a><a name="p22644mcpsimp"></a>继承自Fragment的生命周期方法，当需要向Fragment传递数据时调用。</p>
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
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p22661mcpsimp"><a name="p22661mcpsimp"></a><a name="p22661mcpsimp"></a>向<a href="supportmapfragment.md">SupportMapFragment</a>传递的数据。</p>
</td>
</tr>
</tbody>
</table>

