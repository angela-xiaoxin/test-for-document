# TextureMapView<a name="ZH-CN_TOPIC_0000001099501102"></a>

-   [Public Constructor Summary](#section23359442310)
-   [Public Method Summary](#section3737622154813)
-   [Public Constructors](#section19848311202)
-   [TextureMapView\(Context context\)](#section114762417137)
-   [TextureMapView\(Context context, AttributeSet attrs\)](#section13649203318293)
-   [TextureMapView\(Context context, AttributeSet attrs, int defStyle\)](#section2355113832917)
-   [TextureMapView\(Context context, HuaweiMapOptions options\)](#section10808241152917)
-   [Public Methods](#section1354587509)
-   [getMapAsync](#section18155143712405)
-   [onCreate](#section5701320154117)
-   [onDestroy](#section1991150164217)
-   [onLowMemory](#section1298412345428)
-   [onPause](#section119871413124319)
-   [onResume](#section127594720434)
-   [onSaveInstanceState](#section17492429104415)
-   [onStart](#section1929311316455)
-   [onStop](#section1185125812451)


<a name="table22004mcpsimp"></a>
<table><thead align="left"><tr id="row22008mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p22010mcpsimp"><a name="p22010mcpsimp"></a><a name="p22010mcpsimp"></a>Class Info</p>
</th>
</tr>
</thead>
<tbody><tr id="row22011mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p1480874182718"><a name="p1480874182718"></a><a name="p1480874182718"></a>public class TextureMapView extends MapView</p>
<p id="p16569131570"><a name="p16569131570"></a><a name="p16569131570"></a>继承自<a href="mapview.md">MapView</a>，地图容器。</p>
<div class="caution" id="note10641157171710"><a name="note10641157171710"></a><a name="note10641157171710"></a><span class="cautiontitle"> 注意： </span><div class="cautionbody"><p id="p10641057101717"><a name="p10641057101717"></a><a name="p10641057101717"></a>TextureMapView不能与<a href="mapfragment.md">MapFragment</a>、<a href="mapview.md">MapView</a>、<a href="supportmapfragment.md">SupportMapFragment</a>混用。</p>
</div></div>
</td>
</tr>
</tbody>
</table>

## Public Constructor Summary<a name="section23359442310"></a>

<a name="table7113mcpsimp"></a>
<table><thead align="left"><tr id="row7117mcpsimp"><th class="cellrowborder" valign="top" width="54.87%" id="mcps1.1.3.1.1"><p id="p7119mcpsimp"><a name="p7119mcpsimp"></a><a name="p7119mcpsimp"></a>Constructor Name</p>
</th>
<th class="cellrowborder" valign="top" width="45.129999999999995%" id="mcps1.1.3.1.2">&nbsp;&nbsp;</th>
</tr>
</thead>
<tbody><tr id="row7120mcpsimp"><td class="cellrowborder" valign="top" width="54.87%" headers="mcps1.1.3.1.1 "><p id="p1887735216515"><a name="p1887735216515"></a><a name="p1887735216515"></a><a href="#section114762417137">TextureMapView</a>(Context context)</p>
<p id="p19849132411818"><a name="p19849132411818"></a><a name="p19849132411818"></a>使用给定参数创建<a href="texturemapview.md">TextureMapView</a>对象。</p>
</td>
<td class="cellrowborder" rowspan="4" valign="top" width="45.129999999999995%" headers="mcps1.1.3.1.2 "><div class="note" id="note333614134318"><a name="note333614134318"></a><a name="note333614134318"></a><span class="notetitle"> 说明： </span><div class="notebody"><p id="p9336741194316"><a name="p9336741194316"></a><a name="p9336741194316"></a>当传入参数为非Activity类型时，如果触发HMS Core（APK）升级，此时不会弹出UI交互界面提示用户处理，只会返回错误信息：Hms is not available26，此时需要手动升级HMS Core。如果需要拉起升级引导界面，建议传入Activity类型参数替代Context类型，创建<a href="texturemapview.md">TextureMapView</a>实例。</p>
</div></div>
</td>
</tr>
<tr id="row7123mcpsimp"><td class="cellrowborder" valign="top" headers="mcps1.1.3.1.1 "><p id="p4355198262"><a name="p4355198262"></a><a name="p4355198262"></a><a href="#section13649203318293">TextureMapView</a>(Context context, AttributeSet attrs)</p>
<p id="p5569531594"><a name="p5569531594"></a><a name="p5569531594"></a>使用给定参数创建<a href="texturemapview.md">TextureMapView</a>对象。</p>
</td>
</tr>
<tr id="row7126mcpsimp"><td class="cellrowborder" valign="top" headers="mcps1.1.3.1.1 "><p id="p9108102814617"><a name="p9108102814617"></a><a name="p9108102814617"></a><a href="#section2355113832917">TextureMapView</a>(Context context, AttributeSet attrs, int defStyle)</p>
<p id="p22178108917"><a name="p22178108917"></a><a name="p22178108917"></a>使用给定参数创建<a href="texturemapview.md">TextureMapView</a>对象。</p>
</td>
</tr>
<tr id="row7129mcpsimp"><td class="cellrowborder" valign="top" headers="mcps1.1.3.1.1 "><p id="p7131mcpsimp"><a name="p7131mcpsimp"></a><a name="p7131mcpsimp"></a><a href="#section10808241152917">TextureMapView</a>(Context context, <a href="huaweimapooptions.md">HuaweiMapOptions</a> options)</p>
<p id="p1456151210918"><a name="p1456151210918"></a><a name="p1456151210918"></a>使用给定参数创建<a href="texturemapview.md">TextureMapView</a>对象。</p>
</td>
</tr>
</tbody>
</table>

## Public Method Summary<a name="section3737622154813"></a>

<a name="table951071264911"></a>
<table><thead align="left"><tr id="row1151017123496"><th class="cellrowborder" valign="top" width="36.199999999999996%" id="mcps1.1.3.1.1"><p id="p751191234917"><a name="p751191234917"></a><a name="p751191234917"></a>Qualifier and Type</p>
</th>
<th class="cellrowborder" valign="top" width="63.800000000000004%" id="mcps1.1.3.1.2"><p id="p12511201211490"><a name="p12511201211490"></a><a name="p12511201211490"></a>Method Name and Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row1951171244917"><td class="cellrowborder" valign="top" width="36.199999999999996%" headers="mcps1.1.3.1.1 "><p id="p1951171213494"><a name="p1951171213494"></a><a name="p1951171213494"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="63.800000000000004%" headers="mcps1.1.3.1.2 "><p id="p19511121216491"><a name="p19511121216491"></a><a name="p19511121216491"></a><a href="#section18155143712405">getMapAsync</a>(<a href="onmapreadycallback.md">OnMapReadyCallback</a> callback)</p>
<p id="p4371443141310"><a name="p4371443141310"></a><a name="p4371443141310"></a>当地图对象准备就绪时，就会触发此接口回调，获取<a href="huaweimap.md">HuaweiMap</a>对象。</p>
</td>
</tr>
<tr id="row7148mcpsimp"><td class="cellrowborder" valign="top" width="36.199999999999996%" headers="mcps1.1.3.1.1 "><p id="p7150mcpsimp"><a name="p7150mcpsimp"></a><a name="p7150mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="63.800000000000004%" headers="mcps1.1.3.1.2 "><p id="p7152mcpsimp"><a name="p7152mcpsimp"></a><a name="p7152mcpsimp"></a><a href="#section5701320154117">onCreate</a>(Bundle savedInstanceState)</p>
<p id="p680411258127"><a name="p680411258127"></a><a name="p680411258127"></a>地图创建时的生命周期函数。</p>
</td>
</tr>
<tr id="row7153mcpsimp"><td class="cellrowborder" valign="top" width="36.199999999999996%" headers="mcps1.1.3.1.1 "><p id="p7155mcpsimp"><a name="p7155mcpsimp"></a><a name="p7155mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="63.800000000000004%" headers="mcps1.1.3.1.2 "><p id="p7157mcpsimp"><a name="p7157mcpsimp"></a><a name="p7157mcpsimp"></a><a href="#section1991150164217">onDestroy</a>()</p>
<p id="p97559262125"><a name="p97559262125"></a><a name="p97559262125"></a>地图销毁时的生命周期函数。</p>
</td>
</tr>
<tr id="row7168mcpsimp"><td class="cellrowborder" valign="top" width="36.199999999999996%" headers="mcps1.1.3.1.1 "><p id="p7170mcpsimp"><a name="p7170mcpsimp"></a><a name="p7170mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="63.800000000000004%" headers="mcps1.1.3.1.2 "><p id="p7172mcpsimp"><a name="p7172mcpsimp"></a><a name="p7172mcpsimp"></a><a href="#section1298412345428">onLowMemory</a>()</p>
<p id="p56736326121"><a name="p56736326121"></a><a name="p56736326121"></a>内存不足时调用此方法。</p>
</td>
</tr>
<tr id="row7173mcpsimp"><td class="cellrowborder" valign="top" width="36.199999999999996%" headers="mcps1.1.3.1.1 "><p id="p7175mcpsimp"><a name="p7175mcpsimp"></a><a name="p7175mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="63.800000000000004%" headers="mcps1.1.3.1.2 "><p id="p7177mcpsimp"><a name="p7177mcpsimp"></a><a name="p7177mcpsimp"></a><a href="#section119871413124319">onPause</a>()</p>
<p id="p1157103381213"><a name="p1157103381213"></a><a name="p1157103381213"></a>活动暂停时调用此方法。</p>
</td>
</tr>
<tr id="row7178mcpsimp"><td class="cellrowborder" valign="top" width="36.199999999999996%" headers="mcps1.1.3.1.1 "><p id="p7180mcpsimp"><a name="p7180mcpsimp"></a><a name="p7180mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="63.800000000000004%" headers="mcps1.1.3.1.2 "><p id="p7182mcpsimp"><a name="p7182mcpsimp"></a><a name="p7182mcpsimp"></a><a href="#section127594720434">onResume</a>()</p>
<p id="p17434834121219"><a name="p17434834121219"></a><a name="p17434834121219"></a>活动准备就绪时调用此方法。</p>
</td>
</tr>
<tr id="row7183mcpsimp"><td class="cellrowborder" valign="top" width="36.199999999999996%" headers="mcps1.1.3.1.1 "><p id="p7185mcpsimp"><a name="p7185mcpsimp"></a><a name="p7185mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="63.800000000000004%" headers="mcps1.1.3.1.2 "><p id="p7187mcpsimp"><a name="p7187mcpsimp"></a><a name="p7187mcpsimp"></a><a href="#section17492429104415">onSaveInstanceState</a>(Bundle outState)</p>
<p id="p137783571218"><a name="p137783571218"></a><a name="p137783571218"></a>意外退出时调用此方法保存当前地图状态信息。</p>
</td>
</tr>
<tr id="row7188mcpsimp"><td class="cellrowborder" valign="top" width="36.199999999999996%" headers="mcps1.1.3.1.1 "><p id="p7190mcpsimp"><a name="p7190mcpsimp"></a><a name="p7190mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="63.800000000000004%" headers="mcps1.1.3.1.2 "><p id="p7192mcpsimp"><a name="p7192mcpsimp"></a><a name="p7192mcpsimp"></a><a href="#section1929311316455">onStart</a>()</p>
<p id="p13210153661219"><a name="p13210153661219"></a><a name="p13210153661219"></a>活动创建成功后调用此方法，地图可见。</p>
</td>
</tr>
<tr id="row7193mcpsimp"><td class="cellrowborder" valign="top" width="36.199999999999996%" headers="mcps1.1.3.1.1 "><p id="p7195mcpsimp"><a name="p7195mcpsimp"></a><a name="p7195mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="63.800000000000004%" headers="mcps1.1.3.1.2 "><p id="p7197mcpsimp"><a name="p7197mcpsimp"></a><a name="p7197mcpsimp"></a><a href="#section1185125812451">onStop</a>()</p>
<p id="p19247637161214"><a name="p19247637161214"></a><a name="p19247637161214"></a>活动退出时调用此方法，界面不可见。</p>
</td>
</tr>
</tbody>
</table>

## Public Constructors<a name="section19848311202"></a>

## TextureMapView\(Context context\)<a name="section114762417137"></a>

<a name="table227mcpsimp"></a>
<table><thead align="left"><tr id="row231mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p233mcpsimp"><a name="p233mcpsimp"></a><a name="p233mcpsimp"></a>Constructor</p>
</th>
</tr>
</thead>
<tbody><tr id="row235mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p17568645115116"><a name="p17568645115116"></a><a name="p17568645115116"></a>public <a href="texturemapview.md">TextureMapView</a>(Context context)</p>
<p id="p11568945165115"><a name="p11568945165115"></a><a name="p11568945165115"></a>使用给定参数创建<a href="texturemapview.md">TextureMapView</a>对象。</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table243mcpsimp"></a>
<table><thead align="left"><tr id="row248mcpsimp"><th class="cellrowborder" valign="top" width="43%" id="mcps1.1.3.1.1"><p id="p250mcpsimp"><a name="p250mcpsimp"></a><a name="p250mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="56.99999999999999%" id="mcps1.1.3.1.2"><p id="p253mcpsimp"><a name="p253mcpsimp"></a><a name="p253mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row255mcpsimp"><td class="cellrowborder" valign="top" width="43%" headers="mcps1.1.3.1.1 "><p id="p1275719175136"><a name="p1275719175136"></a><a name="p1275719175136"></a>context</p>
</td>
<td class="cellrowborder" valign="top" width="56.99999999999999%" headers="mcps1.1.3.1.2 "><p id="p69541622141317"><a name="p69541622141317"></a><a name="p69541622141317"></a>上下文。</p>
</td>
</tr>
</tbody>
</table>

## TextureMapView\(Context context, AttributeSet attrs\)<a name="section13649203318293"></a>

<a name="table364912332291"></a>
<table><thead align="left"><tr id="row1064993310297"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p1964910337291"><a name="p1964910337291"></a><a name="p1964910337291"></a>Constructor</p>
</th>
</tr>
</thead>
<tbody><tr id="row17649173382914"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p16491133182916"><a name="p16491133182916"></a><a name="p16491133182916"></a>public <a href="texturemapview.md">TextureMapView</a>(Context context, AttributeSet attrs)</p>
<p id="p19649183342916"><a name="p19649183342916"></a><a name="p19649183342916"></a>使用给定参数创建<a href="texturemapview.md">TextureMapView</a>对象。</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table13650163313297"></a>
<table><thead align="left"><tr id="row86501433172910"><th class="cellrowborder" valign="top" width="43%" id="mcps1.1.3.1.1"><p id="p1065033372910"><a name="p1065033372910"></a><a name="p1065033372910"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="56.99999999999999%" id="mcps1.1.3.1.2"><p id="p17650203314293"><a name="p17650203314293"></a><a name="p17650203314293"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row86504335296"><td class="cellrowborder" valign="top" width="43%" headers="mcps1.1.3.1.1 "><p id="p665018335299"><a name="p665018335299"></a><a name="p665018335299"></a>context</p>
</td>
<td class="cellrowborder" valign="top" width="56.99999999999999%" headers="mcps1.1.3.1.2 "><p id="p12650123352913"><a name="p12650123352913"></a><a name="p12650123352913"></a>上下文。</p>
</td>
</tr>
<tr id="row10650153392912"><td class="cellrowborder" valign="top" width="43%" headers="mcps1.1.3.1.1 "><p id="p665012332299"><a name="p665012332299"></a><a name="p665012332299"></a>attrs</p>
</td>
<td class="cellrowborder" valign="top" width="56.99999999999999%" headers="mcps1.1.3.1.2 "><p id="p176501233102912"><a name="p176501233102912"></a><a name="p176501233102912"></a>XML文件中MapView属性的集合。</p>
</td>
</tr>
</tbody>
</table>

## TextureMapView\(Context context, AttributeSet attrs, int defStyle\)<a name="section2355113832917"></a>

<a name="table1435511387293"></a>
<table><thead align="left"><tr id="row235543813290"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p1355638112915"><a name="p1355638112915"></a><a name="p1355638112915"></a>Constructor</p>
</th>
</tr>
</thead>
<tbody><tr id="row835612384291"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p13561238142918"><a name="p13561238142918"></a><a name="p13561238142918"></a>public <a href="texturemapview.md">TextureMapView</a>(Context context, AttributeSet attrs, int defStyle)</p>
<p id="p535663822910"><a name="p535663822910"></a><a name="p535663822910"></a>使用给定参数创建<a href="texturemapview.md">TextureMapView</a>对象。</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table3356338192912"></a>
<table><thead align="left"><tr id="row135611381295"><th class="cellrowborder" valign="top" width="43%" id="mcps1.1.3.1.1"><p id="p1356638182915"><a name="p1356638182915"></a><a name="p1356638182915"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="56.99999999999999%" id="mcps1.1.3.1.2"><p id="p153561738162913"><a name="p153561738162913"></a><a name="p153561738162913"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row1335603882910"><td class="cellrowborder" valign="top" width="43%" headers="mcps1.1.3.1.1 "><p id="p13356738192910"><a name="p13356738192910"></a><a name="p13356738192910"></a>context</p>
</td>
<td class="cellrowborder" valign="top" width="56.99999999999999%" headers="mcps1.1.3.1.2 "><p id="p10357038202916"><a name="p10357038202916"></a><a name="p10357038202916"></a>上下文。</p>
</td>
</tr>
<tr id="row193571380296"><td class="cellrowborder" valign="top" width="43%" headers="mcps1.1.3.1.1 "><p id="p19357938192915"><a name="p19357938192915"></a><a name="p19357938192915"></a>attrs</p>
</td>
<td class="cellrowborder" valign="top" width="56.99999999999999%" headers="mcps1.1.3.1.2 "><p id="p1135743813293"><a name="p1135743813293"></a><a name="p1135743813293"></a>XML文件中MapView属性的集合。</p>
</td>
</tr>
<tr id="row8357163812915"><td class="cellrowborder" valign="top" width="43%" headers="mcps1.1.3.1.1 "><p id="p1357203842911"><a name="p1357203842911"></a><a name="p1357203842911"></a>defStyle</p>
</td>
<td class="cellrowborder" valign="top" width="56.99999999999999%" headers="mcps1.1.3.1.2 "><p id="p18357163810299"><a name="p18357163810299"></a><a name="p18357163810299"></a>当前主题中的属性，它包含对样式资源的引用，该资源为视图提供默认值，可以为0不查找默认值。</p>
</td>
</tr>
</tbody>
</table>

## TextureMapView\(Context context, HuaweiMapOptions options\)<a name="section10808241152917"></a>

<a name="table1680814172916"></a>
<table><thead align="left"><tr id="row19808104117293"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p1880864142914"><a name="p1880864142914"></a><a name="p1880864142914"></a>Constructor</p>
</th>
</tr>
</thead>
<tbody><tr id="row1380864152920"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p11809841142911"><a name="p11809841142911"></a><a name="p11809841142911"></a>public <a href="texturemapview.md">TextureMapView</a>(Context context, <a href="huaweimapooptions.md">HuaweiMapOptions</a> options)</p>
<p id="p48099415293"><a name="p48099415293"></a><a name="p48099415293"></a>使用给定参数创建<a href="texturemapview.md">TextureMapView</a>对象。</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table13809941122917"></a>
<table><thead align="left"><tr id="row380994172919"><th class="cellrowborder" valign="top" width="43%" id="mcps1.1.3.1.1"><p id="p1480974118298"><a name="p1480974118298"></a><a name="p1480974118298"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="56.99999999999999%" id="mcps1.1.3.1.2"><p id="p11809141192919"><a name="p11809141192919"></a><a name="p11809141192919"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row18091641192914"><td class="cellrowborder" valign="top" width="43%" headers="mcps1.1.3.1.1 "><p id="p14809141132913"><a name="p14809141132913"></a><a name="p14809141132913"></a>context</p>
</td>
<td class="cellrowborder" valign="top" width="56.99999999999999%" headers="mcps1.1.3.1.2 "><p id="p580911418299"><a name="p580911418299"></a><a name="p580911418299"></a>上下文。</p>
</td>
</tr>
<tr id="row1680914410290"><td class="cellrowborder" valign="top" width="43%" headers="mcps1.1.3.1.1 "><p id="p10809144117290"><a name="p10809144117290"></a><a name="p10809144117290"></a>options</p>
</td>
<td class="cellrowborder" valign="top" width="56.99999999999999%" headers="mcps1.1.3.1.2 "><p id="p8809184182919"><a name="p8809184182919"></a><a name="p8809184182919"></a>包含了华为地图配置信息的<a href="huaweimapooptions.md">HuaweiMapOptions</a>实例。</p>
</td>
</tr>
</tbody>
</table>

## Public Methods<a name="section1354587509"></a>

## getMapAsync<a name="section18155143712405"></a>

<a name="table7200mcpsimp"></a>
<table><thead align="left"><tr id="row7204mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p7206mcpsimp"><a name="p7206mcpsimp"></a><a name="p7206mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row7207mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p7209mcpsimp"><a name="p7209mcpsimp"></a><a name="p7209mcpsimp"></a>public void getMapAsync(<a href="onmapreadycallback.md">OnMapReadyCallback</a> callback)</p>
<p id="p7212mcpsimp"><a name="p7212mcpsimp"></a><a name="p7212mcpsimp"></a>当地图对象准备就绪时，就会触发此接口回调，获取<a href="huaweimap.md">HuaweiMap</a>对象。</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table7215mcpsimp"></a>
<table><thead align="left"><tr id="row7220mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p7222mcpsimp"><a name="p7222mcpsimp"></a><a name="p7222mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p7224mcpsimp"><a name="p7224mcpsimp"></a><a name="p7224mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row7225mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p7227mcpsimp"><a name="p7227mcpsimp"></a><a name="p7227mcpsimp"></a>callback</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p7229mcpsimp"><a name="p7229mcpsimp"></a><a name="p7229mcpsimp"></a>当<a href="huaweimap.md">HuaweiMap</a>准备就绪时回调。</p>
</td>
</tr>
</tbody>
</table>

## onCreate<a name="section5701320154117"></a>

<a name="table7234mcpsimp"></a>
<table><thead align="left"><tr id="row7238mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p7240mcpsimp"><a name="p7240mcpsimp"></a><a name="p7240mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row7241mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p7243mcpsimp"><a name="p7243mcpsimp"></a><a name="p7243mcpsimp"></a>public void onCreate(Bundle savedInstanceState)</p>
<p id="p18361240144113"><a name="p18361240144113"></a><a name="p18361240144113"></a>地图创建时的生命周期函数，用户重载该方法时必须调用父类的这个方法。</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table7249mcpsimp"></a>
<table><thead align="left"><tr id="row7254mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p7256mcpsimp"><a name="p7256mcpsimp"></a><a name="p7256mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p7258mcpsimp"><a name="p7258mcpsimp"></a><a name="p7258mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row7259mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p7261mcpsimp"><a name="p7261mcpsimp"></a><a name="p7261mcpsimp"></a>savedInstanceState</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p7263mcpsimp"><a name="p7263mcpsimp"></a><a name="p7263mcpsimp"></a>保存的地图状态。</p>
</td>
</tr>
</tbody>
</table>

## onDestroy<a name="section1991150164217"></a>

<a name="table7268mcpsimp"></a>
<table><thead align="left"><tr id="row7272mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p7274mcpsimp"><a name="p7274mcpsimp"></a><a name="p7274mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row7275mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p7277mcpsimp"><a name="p7277mcpsimp"></a><a name="p7277mcpsimp"></a>public void onDestroy()</p>
<p id="p7280mcpsimp"><a name="p7280mcpsimp"></a><a name="p7280mcpsimp"></a>地图销毁时的生命周期函数，用户重载该方法时必须调用父类的这个方法。</p>
</td>
</tr>
</tbody>
</table>

## onLowMemory<a name="section1298412345428"></a>

<a name="table7288mcpsimp"></a>
<table><thead align="left"><tr id="row7292mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p7294mcpsimp"><a name="p7294mcpsimp"></a><a name="p7294mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row7295mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p7297mcpsimp"><a name="p7297mcpsimp"></a><a name="p7297mcpsimp"></a>public void onLowMemory()</p>
<p id="p7300mcpsimp"><a name="p7300mcpsimp"></a><a name="p7300mcpsimp"></a>内存不足时调用此方法，用户重载该方法时必须调用父类的这个方法。</p>
</td>
</tr>
</tbody>
</table>

## onPause<a name="section119871413124319"></a>

<a name="table7308mcpsimp"></a>
<table><thead align="left"><tr id="row7312mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p7314mcpsimp"><a name="p7314mcpsimp"></a><a name="p7314mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row7315mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p7317mcpsimp"><a name="p7317mcpsimp"></a><a name="p7317mcpsimp"></a>public void onPause()</p>
<p id="p6656183015434"><a name="p6656183015434"></a><a name="p6656183015434"></a>活动暂停时调用此方法，用户重载该方法时必须调用父类的这个方法。</p>
</td>
</tr>
</tbody>
</table>

## onResume<a name="section127594720434"></a>

<a name="table7328mcpsimp"></a>
<table><thead align="left"><tr id="row7332mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p7334mcpsimp"><a name="p7334mcpsimp"></a><a name="p7334mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row7335mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p7337mcpsimp"><a name="p7337mcpsimp"></a><a name="p7337mcpsimp"></a>public void onResume()</p>
<p id="p7340mcpsimp"><a name="p7340mcpsimp"></a><a name="p7340mcpsimp"></a>活动准备就绪时调用此方法，用户重载该方法时必须调用父类的这个方法。</p>
</td>
</tr>
</tbody>
</table>

## onSaveInstanceState<a name="section17492429104415"></a>

<a name="table7348mcpsimp"></a>
<table><thead align="left"><tr id="row7352mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p7354mcpsimp"><a name="p7354mcpsimp"></a><a name="p7354mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row7355mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p7357mcpsimp"><a name="p7357mcpsimp"></a><a name="p7357mcpsimp"></a>public void onSaveInstanceState(Bundle outState)</p>
<p id="p7360mcpsimp"><a name="p7360mcpsimp"></a><a name="p7360mcpsimp"></a>意外退出，保存数据。</p>
<p id="p7363mcpsimp"><a name="p7363mcpsimp"></a><a name="p7363mcpsimp"></a>意外退出时调用此方法保存当前地图状态信息，用户重载这个方法时必须调用父类的这个方法。</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table7366mcpsimp"></a>
<table><thead align="left"><tr id="row7371mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p7373mcpsimp"><a name="p7373mcpsimp"></a><a name="p7373mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p7375mcpsimp"><a name="p7375mcpsimp"></a><a name="p7375mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row7376mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p7378mcpsimp"><a name="p7378mcpsimp"></a><a name="p7378mcpsimp"></a>outState</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p7380mcpsimp"><a name="p7380mcpsimp"></a><a name="p7380mcpsimp"></a>保存地图状态信息。</p>
</td>
</tr>
</tbody>
</table>

## onStart<a name="section1929311316455"></a>

<a name="table7385mcpsimp"></a>
<table><thead align="left"><tr id="row7389mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p7391mcpsimp"><a name="p7391mcpsimp"></a><a name="p7391mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row7392mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p7394mcpsimp"><a name="p7394mcpsimp"></a><a name="p7394mcpsimp"></a>public void onStart()</p>
<p id="p7397mcpsimp"><a name="p7397mcpsimp"></a><a name="p7397mcpsimp"></a>活动创建成功后调用此方法，地图可见。用户重载该方法时必须调用父类的这个方法。</p>
</td>
</tr>
</tbody>
</table>

## onStop<a name="section1185125812451"></a>

<a name="table7405mcpsimp"></a>
<table><thead align="left"><tr id="row7409mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p7411mcpsimp"><a name="p7411mcpsimp"></a><a name="p7411mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row7412mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p7414mcpsimp"><a name="p7414mcpsimp"></a><a name="p7414mcpsimp"></a>public void onStop()</p>
<p id="p7417mcpsimp"><a name="p7417mcpsimp"></a><a name="p7417mcpsimp"></a>活动退出时调用此方法，界面不可见。用户重载该方法时必须调用父类的这个方法。</p>
</td>
</tr>
</tbody>
</table>

