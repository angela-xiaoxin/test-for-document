# BitmapDescriptorFactory<a name="ZH-CN_TOPIC_0000001145860975"></a>

-   [Public Field Summary](#section7765355142012)
-   [Public Method Summary](#section038814485226)
-   [Public Fields](#section1046222462120)
-   [HUE\_AZURE](#section198092040202118)
-   [HUE\_BLUE](#section61791812163718)
-   [HUE\_CYAN](#section6702101633716)
-   [h2HUE\_GREEN](#section13469917203715)
-   [HUE\_MAGENTA](#section6304318143719)
-   [HUE\_ORANGE](#section123055192378)
-   [HUE\_RED](#section41171120193718)
-   [HUE\_ROSE](#section3946102023711)
-   [HUE\_VIOLET](#section98344219370)
-   [HUE\_YELLOW](#section37551522143720)
-   [Public Methods](#section14924141264412)
-   [defaultMarker\(float hue\)](#section13757171244714)
-   [defaultMarker\(\)](#section192932119515)
-   [fromAsset](#section177751156105216)
-   [fromBitmap](#section375416351533)
-   [fromFile](#section338617415546)
-   [fromPath](#section1762285545410)
-   [fromResource](#section11216192714558)


<a name="table8477mcpsimp"></a>
<table><thead align="left"><tr id="row8481mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p8483mcpsimp"><a name="p8483mcpsimp"></a><a name="p8483mcpsimp"></a>Class Info</p>
</th>
</tr>
</thead>
<tbody><tr id="row8484mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p95216561821"><a name="p95216561821"></a><a name="p95216561821"></a>public final class BitmapDescriptorFactory</p>
<p id="p8486mcpsimp"><a name="p8486mcpsimp"></a><a name="p8486mcpsimp"></a>用于创建Bitmap图像的定义。</p>
<p id="p38801857141015"><a name="p38801857141015"></a><a name="p38801857141015"></a>在使用此类中的任何方法之前，必须执行以下操作之一以确保初始化此类：</p>
<a name="ul88801957191015"></a><a name="ul88801957191015"></a><ul id="ul88801957191015"><li>等待<a href="huaweimap.md">HuaweiMap</a>从<a href="mapfragment.md">MapFragment</a>或<a href="mapview.md">MapView</a>中可用。您可以通过调用getMapAsync()并等待onMapReady(HuaweiMap huaweiMap)回调来获取<a href="huaweimap.md">HuaweiMap</a>实例。</li><li>调用<a href="mapsinitializer.md">MapsInitializer</a>.<a href="mapsinitializer.md#section1516212511479">initialize</a>(Context context)接口，完成初始化。</li></ul>
</td>
</tr>
</tbody>
</table>

## Public Field Summary<a name="section7765355142012"></a>

<a name="table51207528357"></a>
<table><thead align="left"><tr id="row6121185283516"><th class="cellrowborder" valign="top" width="32.33%" id="mcps1.1.3.1.1"><p id="p1528164471414"><a name="p1528164471414"></a><a name="p1528164471414"></a>Qualifier and Type</p>
</th>
<th class="cellrowborder" valign="top" width="67.67%" id="mcps1.1.3.1.2"><p id="p1554614158108"><a name="p1554614158108"></a><a name="p1554614158108"></a>Field and Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row2012119527357"><td class="cellrowborder" valign="top" width="32.33%" headers="mcps1.1.3.1.1 "><p id="p04140318506"><a name="p04140318506"></a><a name="p04140318506"></a>public static final float</p>
</td>
<td class="cellrowborder" valign="top" width="67.67%" headers="mcps1.1.3.1.2 "><p id="p14308171501"><a name="p14308171501"></a><a name="p14308171501"></a><a href="#section198092040202118">HUE_AZURE</a></p>
<p id="p953110563497"><a name="p953110563497"></a><a name="p953110563497"></a>天蓝色。</p>
</td>
</tr>
<tr id="row8121145210353"><td class="cellrowborder" valign="top" width="32.33%" headers="mcps1.1.3.1.1 "><p id="p1941423175019"><a name="p1941423175019"></a><a name="p1941423175019"></a>public static final float</p>
</td>
<td class="cellrowborder" valign="top" width="67.67%" headers="mcps1.1.3.1.2 "><p id="p18186165515016"><a name="p18186165515016"></a><a name="p18186165515016"></a><a href="#section61791812163718">HUE_BLUE</a></p>
<p id="p55311556114915"><a name="p55311556114915"></a><a name="p55311556114915"></a>蓝色。</p>
</td>
</tr>
<tr id="row11169719154710"><td class="cellrowborder" valign="top" width="32.33%" headers="mcps1.1.3.1.1 "><p id="p134141036506"><a name="p134141036506"></a><a name="p134141036506"></a>public static final float</p>
</td>
<td class="cellrowborder" valign="top" width="67.67%" headers="mcps1.1.3.1.2 "><p id="p201507011510"><a name="p201507011510"></a><a name="p201507011510"></a><a href="#section6702101633716">HUE_CYAN</a></p>
<p id="p10531105618498"><a name="p10531105618498"></a><a name="p10531105618498"></a>青色。</p>
</td>
</tr>
<tr id="row91071248204916"><td class="cellrowborder" valign="top" width="32.33%" headers="mcps1.1.3.1.1 "><p id="p194141432503"><a name="p194141432503"></a><a name="p194141432503"></a>public static final float</p>
</td>
<td class="cellrowborder" valign="top" width="67.67%" headers="mcps1.1.3.1.2 "><p id="p1989123175117"><a name="p1989123175117"></a><a name="p1989123175117"></a><a href="#section13469917203715">HUE_GREEN</a></p>
<p id="p653117562495"><a name="p653117562495"></a><a name="p653117562495"></a>绿色。</p>
</td>
</tr>
<tr id="row184047485497"><td class="cellrowborder" valign="top" width="32.33%" headers="mcps1.1.3.1.1 "><p id="p194143305013"><a name="p194143305013"></a><a name="p194143305013"></a>public static final float</p>
</td>
<td class="cellrowborder" valign="top" width="67.67%" headers="mcps1.1.3.1.2 "><p id="p199716195111"><a name="p199716195111"></a><a name="p199716195111"></a><a href="#section6304318143719">HUE_MAGENTA</a></p>
<p id="p12531195644912"><a name="p12531195644912"></a><a name="p12531195644912"></a>酒红色。</p>
</td>
</tr>
<tr id="row1171414480497"><td class="cellrowborder" valign="top" width="32.33%" headers="mcps1.1.3.1.1 "><p id="p1741412310500"><a name="p1741412310500"></a><a name="p1741412310500"></a>public static final float</p>
</td>
<td class="cellrowborder" valign="top" width="67.67%" headers="mcps1.1.3.1.2 "><p id="p14221191020511"><a name="p14221191020511"></a><a name="p14221191020511"></a><a href="#section123055192378">HUE_ORANGE</a></p>
<p id="p8531165614499"><a name="p8531165614499"></a><a name="p8531165614499"></a>橙色。</p>
</td>
</tr>
<tr id="row255849114910"><td class="cellrowborder" valign="top" width="32.33%" headers="mcps1.1.3.1.1 "><p id="p1141410325016"><a name="p1141410325016"></a><a name="p1141410325016"></a>public static final float</p>
</td>
<td class="cellrowborder" valign="top" width="67.67%" headers="mcps1.1.3.1.2 "><p id="p11349913115114"><a name="p11349913115114"></a><a name="p11349913115114"></a><a href="#section41171120193718">HUE_RED</a></p>
<p id="p17531156174917"><a name="p17531156174917"></a><a name="p17531156174917"></a>红色。</p>
</td>
</tr>
<tr id="row85591750154918"><td class="cellrowborder" valign="top" width="32.33%" headers="mcps1.1.3.1.1 "><p id="p1541414316507"><a name="p1541414316507"></a><a name="p1541414316507"></a>public static final float</p>
</td>
<td class="cellrowborder" valign="top" width="67.67%" headers="mcps1.1.3.1.2 "><p id="p549281675114"><a name="p549281675114"></a><a name="p549281675114"></a><a href="#section3946102023711">HUE_ROSE</a></p>
<p id="p1453112563499"><a name="p1453112563499"></a><a name="p1453112563499"></a>玫瑰红。</p>
</td>
</tr>
<tr id="row13832550164916"><td class="cellrowborder" valign="top" width="32.33%" headers="mcps1.1.3.1.1 "><p id="p54148311509"><a name="p54148311509"></a><a name="p54148311509"></a>public static final float</p>
</td>
<td class="cellrowborder" valign="top" width="67.67%" headers="mcps1.1.3.1.2 "><p id="p66792065114"><a name="p66792065114"></a><a name="p66792065114"></a><a href="#section98344219370">HUE_VIOLET</a></p>
<p id="p1053110563499"><a name="p1053110563499"></a><a name="p1053110563499"></a>紫色。</p>
</td>
</tr>
<tr id="row158815515496"><td class="cellrowborder" valign="top" width="32.33%" headers="mcps1.1.3.1.1 "><p id="p1541513305018"><a name="p1541513305018"></a><a name="p1541513305018"></a>public static final float</p>
</td>
<td class="cellrowborder" valign="top" width="67.67%" headers="mcps1.1.3.1.2 "><p id="p11169182311518"><a name="p11169182311518"></a><a name="p11169182311518"></a><a href="#section37551522143720">HUE_YELLOW</a></p>
<p id="p153145620496"><a name="p153145620496"></a><a name="p153145620496"></a>黄色。</p>
</td>
</tr>
</tbody>
</table>

## Public Method Summary<a name="section038814485226"></a>

<a name="table8574mcpsimp"></a>
<table><thead align="left"><tr id="row8579mcpsimp"><th class="cellrowborder" valign="top" width="40%" id="mcps1.1.3.1.1"><p id="p770950204210"><a name="p770950204210"></a><a name="p770950204210"></a>Qualifier and Type</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.1.3.1.2"><p id="p8583mcpsimp"><a name="p8583mcpsimp"></a><a name="p8583mcpsimp"></a>Method Name and Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row8584mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p8586mcpsimp"><a name="p8586mcpsimp"></a><a name="p8586mcpsimp"></a>static <a href="bitmapdescriptor.md">BitmapDescriptor</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p8588mcpsimp"><a name="p8588mcpsimp"></a><a name="p8588mcpsimp"></a><a href="#section13757171244714">defaultMarker</a>(float hue)</p>
<p id="p55298720286"><a name="p55298720286"></a><a name="p55298720286"></a>根据不同的色值来创建不同颜色的默认标记图标的<a href="bitmapdescriptor.md">BitmapDescriptor</a>对象。</p>
</td>
</tr>
<tr id="row8589mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p8591mcpsimp"><a name="p8591mcpsimp"></a><a name="p8591mcpsimp"></a>static <a href="bitmapdescriptor.md">BitmapDescriptor</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p8593mcpsimp"><a name="p8593mcpsimp"></a><a name="p8593mcpsimp"></a><a href="#section192932119515">defaultMarker</a>()</p>
<p id="p66421832812"><a name="p66421832812"></a><a name="p66421832812"></a>创建默认标记图标的<a href="bitmapdescriptor.md">BitmapDescriptor</a>对象。</p>
</td>
</tr>
<tr id="row8594mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p8596mcpsimp"><a name="p8596mcpsimp"></a><a name="p8596mcpsimp"></a>static <a href="bitmapdescriptor.md">BitmapDescriptor</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p8598mcpsimp"><a name="p8598mcpsimp"></a><a name="p8598mcpsimp"></a><a href="#section177751156105216">fromAsset</a>(String assetName)</p>
<p id="p856717919283"><a name="p856717919283"></a><a name="p856717919283"></a>使用asset目录中的图片资源创建<a href="bitmapdescriptor.md">BitmapDescriptor</a>对象。</p>
</td>
</tr>
<tr id="row8599mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p8601mcpsimp"><a name="p8601mcpsimp"></a><a name="p8601mcpsimp"></a>static <a href="bitmapdescriptor.md">BitmapDescriptor</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p8603mcpsimp"><a name="p8603mcpsimp"></a><a name="p8603mcpsimp"></a><a href="#section375416351533">fromBitmap</a>(Bitmap image)</p>
<p id="p114007107287"><a name="p114007107287"></a><a name="p114007107287"></a>通过Bitmap类型图片创建<a href="bitmapdescriptor.md">BitmapDescriptor</a>对象。</p>
</td>
</tr>
<tr id="row8604mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p8606mcpsimp"><a name="p8606mcpsimp"></a><a name="p8606mcpsimp"></a>static <a href="bitmapdescriptor.md">BitmapDescriptor</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p8608mcpsimp"><a name="p8608mcpsimp"></a><a name="p8608mcpsimp"></a><a href="#section338617415546">fromFile</a>(String fileName)</p>
<p id="p18186201112819"><a name="p18186201112819"></a><a name="p18186201112819"></a>通过内部存储中的图片文件名创建一个<a href="bitmapdescriptor.md">BitmapDescriptor</a>对象。</p>
</td>
</tr>
<tr id="row8609mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p8611mcpsimp"><a name="p8611mcpsimp"></a><a name="p8611mcpsimp"></a>static <a href="bitmapdescriptor.md">BitmapDescriptor</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p8613mcpsimp"><a name="p8613mcpsimp"></a><a name="p8613mcpsimp"></a><a href="#section1762285545410">fromPath</a>(String absolutePath)</p>
<p id="p20968611182815"><a name="p20968611182815"></a><a name="p20968611182815"></a>通过图片资源的绝对路径创建一个<a href="bitmapdescriptor.md">BitmapDescriptor</a>对象。</p>
</td>
</tr>
<tr id="row8614mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p8616mcpsimp"><a name="p8616mcpsimp"></a><a name="p8616mcpsimp"></a>static <a href="bitmapdescriptor.md">BitmapDescriptor</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p8618mcpsimp"><a name="p8618mcpsimp"></a><a name="p8618mcpsimp"></a><a href="#section11216192714558">fromResource</a>(int resourceId)</p>
<p id="p1778321292819"><a name="p1778321292819"></a><a name="p1778321292819"></a>通过图片的资源ID创建一个<a href="bitmapdescriptor.md">BitmapDescriptor</a>对象。</p>
</td>
</tr>
</tbody>
</table>

## Public Fields<a name="section1046222462120"></a>

## HUE\_AZURE<a name="section198092040202118"></a>

<a name="table1255354452212"></a>
<table><thead align="left"><tr id="row65541441229"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p10554944132214"><a name="p10554944132214"></a><a name="p10554944132214"></a>Fields</p>
</th>
</tr>
</thead>
<tbody><tr id="row125541144132214"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p14825519385"><a name="p14825519385"></a><a name="p14825519385"></a>public static final float HUE_AZURE</p>
<p id="p4634253113616"><a name="p4634253113616"></a><a name="p4634253113616"></a>天蓝色。</p>
<p id="p1539313196564"><a name="p1539313196564"></a><a name="p1539313196564"></a>HUE_AZURE：210.0，其余常量值参阅：<a href="constant-values.md#section185601344164319">Constant-values</a></p>
</td>
</tr>
</tbody>
</table>

## HUE\_BLUE<a name="section61791812163718"></a>

<a name="table117921211370"></a>
<table><thead align="left"><tr id="row218061218378"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p1180161273716"><a name="p1180161273716"></a><a name="p1180161273716"></a>Fields</p>
</th>
</tr>
</thead>
<tbody><tr id="row1618031233712"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p8180131233711"><a name="p8180131233711"></a><a name="p8180131233711"></a>public static final float HUE_BLUE</p>
<p id="p418001213376"><a name="p418001213376"></a><a name="p418001213376"></a>蓝色。</p>
<p id="p11180111215370"><a name="p11180111215370"></a><a name="p11180111215370"></a>HUE_BLUE：240.0，其余常量值参阅：<a href="constant-values.md#section185601344164319">Constant-values</a></p>
</td>
</tr>
</tbody>
</table>

## HUE\_CYAN<a name="section6702101633716"></a>

<a name="table127025161376"></a>
<table><thead align="left"><tr id="row470351619373"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p170391610376"><a name="p170391610376"></a><a name="p170391610376"></a>Fields</p>
</th>
</tr>
</thead>
<tbody><tr id="row19703201617377"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p1703161633718"><a name="p1703161633718"></a><a name="p1703161633718"></a>public static final float HUE_CYAN</p>
<p id="p9703116143715"><a name="p9703116143715"></a><a name="p9703116143715"></a>青色。</p>
<p id="p7703191619379"><a name="p7703191619379"></a><a name="p7703191619379"></a>HUE_CYAN：180.0，其余常量值参阅：<a href="constant-values.md#section185601344164319">Constant-values</a></p>
</td>
</tr>
</tbody>
</table>

## h2HUE\_GREEN<a name="section13469917203715"></a>

<a name="table134691617113717"></a>
<table><thead align="left"><tr id="row7470171710378"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p647051743718"><a name="p647051743718"></a><a name="p647051743718"></a>Fields</p>
</th>
</tr>
</thead>
<tbody><tr id="row13470817113710"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p11470917113711"><a name="p11470917113711"></a><a name="p11470917113711"></a>public static final float  HUE_GREEN</p>
<p id="p1470517103715"><a name="p1470517103715"></a><a name="p1470517103715"></a>绿色。</p>
<p id="p11470917153715"><a name="p11470917153715"></a><a name="p11470917153715"></a>HUE_GREEN：120.0，其余常量值参阅：<a href="constant-values.md#section185601344164319">Constant-values</a></p>
</td>
</tr>
</tbody>
</table>

## HUE\_MAGENTA<a name="section6304318143719"></a>

<a name="table1930501815379"></a>
<table><thead align="left"><tr id="row5305161833714"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p930591843717"><a name="p930591843717"></a><a name="p930591843717"></a>Fields</p>
</th>
</tr>
</thead>
<tbody><tr id="row830514182375"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p1830561814377"><a name="p1830561814377"></a><a name="p1830561814377"></a>public static final float HUE_MAGENTA</p>
<p id="p183051718143714"><a name="p183051718143714"></a><a name="p183051718143714"></a>酒红色。</p>
<p id="p630591833715"><a name="p630591833715"></a><a name="p630591833715"></a>HUE_MAGENTA：300.0，其余常量值参阅：<a href="constant-values.md#section185601344164319">Constant-values</a></p>
</td>
</tr>
</tbody>
</table>

## HUE\_ORANGE<a name="section123055192378"></a>

<a name="table173051119183715"></a>
<table><thead align="left"><tr id="row1730511983712"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p183051419183717"><a name="p183051419183717"></a><a name="p183051419183717"></a>Fields</p>
</th>
</tr>
</thead>
<tbody><tr id="row1030551993714"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p10305111983713"><a name="p10305111983713"></a><a name="p10305111983713"></a>public static final float HUE_ORANGE</p>
<p id="p5305619133712"><a name="p5305619133712"></a><a name="p5305619133712"></a>橙色。</p>
<p id="p23053198375"><a name="p23053198375"></a><a name="p23053198375"></a>HUE_ORANGE：30.0，其余常量值参阅：<a href="constant-values.md#section185601344164319">Constant-values</a></p>
</td>
</tr>
</tbody>
</table>

## HUE\_RED<a name="section41171120193718"></a>

<a name="table1411718208370"></a>
<table><thead align="left"><tr id="row111171209379"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p9117920153719"><a name="p9117920153719"></a><a name="p9117920153719"></a>Fields</p>
</th>
</tr>
</thead>
<tbody><tr id="row31171820193715"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p5117112014373"><a name="p5117112014373"></a><a name="p5117112014373"></a>public static final float HUE_RED</p>
<p id="p171171820133717"><a name="p171171820133717"></a><a name="p171171820133717"></a>红色。</p>
<p id="p1411792010370"><a name="p1411792010370"></a><a name="p1411792010370"></a>HUE_RED：0.0，其余常量值参阅：<a href="constant-values.md#section185601344164319">Constant-values</a></p>
</td>
</tr>
</tbody>
</table>

## HUE\_ROSE<a name="section3946102023711"></a>

<a name="table2946620133716"></a>
<table><thead align="left"><tr id="row1194622063715"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p11946102003717"><a name="p11946102003717"></a><a name="p11946102003717"></a>Fields</p>
</th>
</tr>
</thead>
<tbody><tr id="row994642043716"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p1594612093710"><a name="p1594612093710"></a><a name="p1594612093710"></a>public static final float HUE_ROSE</p>
<p id="p5946182011378"><a name="p5946182011378"></a><a name="p5946182011378"></a>玫瑰红。</p>
<p id="p3946152015370"><a name="p3946152015370"></a><a name="p3946152015370"></a>HUE_ROSE：330.0，其余常量值参阅：<a href="constant-values.md#section185601344164319">Constant-values</a></p>
</td>
</tr>
</tbody>
</table>

## HUE\_VIOLET<a name="section98344219370"></a>

<a name="table58341221113713"></a>
<table><thead align="left"><tr id="row188341621153713"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p4835152114372"><a name="p4835152114372"></a><a name="p4835152114372"></a>Fields</p>
</th>
</tr>
</thead>
<tbody><tr id="row183513214378"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p13835921153710"><a name="p13835921153710"></a><a name="p13835921153710"></a>public static final float HUE_VIOLET</p>
<p id="p1583572173715"><a name="p1583572173715"></a><a name="p1583572173715"></a>紫色。</p>
<p id="p1083592112373"><a name="p1083592112373"></a><a name="p1083592112373"></a>HUE_VIOLET：270.0，其余常量值参阅：<a href="constant-values.md#section185601344164319">Constant-values</a></p>
</td>
</tr>
</tbody>
</table>

## HUE\_YELLOW<a name="section37551522143720"></a>

<a name="table375512273714"></a>
<table><thead align="left"><tr id="row475613225378"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p275642214378"><a name="p275642214378"></a><a name="p275642214378"></a>Fields</p>
</th>
</tr>
</thead>
<tbody><tr id="row1175662215379"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p14756822123719"><a name="p14756822123719"></a><a name="p14756822123719"></a>public static final float HUE_YELLOW</p>
<p id="p4756322103712"><a name="p4756322103712"></a><a name="p4756322103712"></a>黄色。</p>
<p id="p1575615221374"><a name="p1575615221374"></a><a name="p1575615221374"></a>HUE_YELLOW：60.0，其余常量值参阅：<a href="constant-values.md#section185601344164319">Constant-values</a></p>
</td>
</tr>
</tbody>
</table>

## Public Methods<a name="section14924141264412"></a>

## defaultMarker\(float hue\)<a name="section13757171244714"></a>

<a name="table8621mcpsimp"></a>
<table><thead align="left"><tr id="row8625mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p8627mcpsimp"><a name="p8627mcpsimp"></a><a name="p8627mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row8628mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p8630mcpsimp"><a name="p8630mcpsimp"></a><a name="p8630mcpsimp"></a>public static <a href="bitmapdescriptor.md">BitmapDescriptor</a> defaultMarker(float hue)</p>
<p id="p164021954144819"><a name="p164021954144819"></a><a name="p164021954144819"></a>根据不同的色值来创建不同颜色的默认标记图标的<a href="bitmapdescriptor.md">BitmapDescriptor</a>对象。本类提供了10个颜色的标记图标，您可以通过传入本类的字段来调用，请参见本类的<a href="#section1046222462120">Public Fields</a>。</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table8639mcpsimp"></a>
<table><thead align="left"><tr id="row8644mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p8646mcpsimp"><a name="p8646mcpsimp"></a><a name="p8646mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p8648mcpsimp"><a name="p8648mcpsimp"></a><a name="p8648mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row8649mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p8651mcpsimp"><a name="p8651mcpsimp"></a><a name="p8651mcpsimp"></a>hue</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p8653mcpsimp"><a name="p8653mcpsimp"></a><a name="p8653mcpsimp"></a>颜色常量。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table8656mcpsimp"></a>
<table><thead align="left"><tr id="row8661mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p8663mcpsimp"><a name="p8663mcpsimp"></a><a name="p8663mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p8665mcpsimp"><a name="p8665mcpsimp"></a><a name="p8665mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row8666mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p8668mcpsimp"><a name="p8668mcpsimp"></a><a name="p8668mcpsimp"></a>BitmapDescriptor</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p8670mcpsimp"><a name="p8670mcpsimp"></a><a name="p8670mcpsimp"></a><a href="bitmapdescriptor.md">BitmapDescriptor</a>对象。</p>
</td>
</tr>
</tbody>
</table>

## defaultMarker\(\)<a name="section192932119515"></a>

<a name="table8672mcpsimp"></a>
<table><thead align="left"><tr id="row8676mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p8678mcpsimp"><a name="p8678mcpsimp"></a><a name="p8678mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row8679mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p8681mcpsimp"><a name="p8681mcpsimp"></a><a name="p8681mcpsimp"></a>public static <a href="bitmapdescriptor.md">BitmapDescriptor</a> defaultMarker()</p>
<p id="p19933158471"><a name="p19933158471"></a><a name="p19933158471"></a>您调用此API可以创建默认标记图标的<a href="bitmapdescriptor.md">BitmapDescriptor</a>对象。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table8690mcpsimp"></a>
<table><thead align="left"><tr id="row8695mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p8697mcpsimp"><a name="p8697mcpsimp"></a><a name="p8697mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p8699mcpsimp"><a name="p8699mcpsimp"></a><a name="p8699mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row8700mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p8702mcpsimp"><a name="p8702mcpsimp"></a><a name="p8702mcpsimp"></a>BitmapDescriptor</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p8704mcpsimp"><a name="p8704mcpsimp"></a><a name="p8704mcpsimp"></a><a href="bitmapdescriptor.md">BitmapDescriptor</a>对象。</p>
</td>
</tr>
</tbody>
</table>

## fromAsset<a name="section177751156105216"></a>

<a name="table8706mcpsimp"></a>
<table><thead align="left"><tr id="row8710mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p8712mcpsimp"><a name="p8712mcpsimp"></a><a name="p8712mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row8713mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p8715mcpsimp"><a name="p8715mcpsimp"></a><a name="p8715mcpsimp"></a>public static <a href="bitmapdescriptor.md">BitmapDescriptor</a> fromAsset(String assetName)</p>
<p id="p895113307472"><a name="p895113307472"></a><a name="p895113307472"></a>您调用此API可以使用asset目录中的图片资源创建<a href="bitmapdescriptor.md">BitmapDescriptor</a>对象。</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table8721mcpsimp"></a>
<table><thead align="left"><tr id="row8726mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p8728mcpsimp"><a name="p8728mcpsimp"></a><a name="p8728mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p8730mcpsimp"><a name="p8730mcpsimp"></a><a name="p8730mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row8731mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p8733mcpsimp"><a name="p8733mcpsimp"></a><a name="p8733mcpsimp"></a>assetName</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p8735mcpsimp"><a name="p8735mcpsimp"></a><a name="p8735mcpsimp"></a>图片在asset目录下的路径，包含图片名称。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table8738mcpsimp"></a>
<table><thead align="left"><tr id="row8743mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p8745mcpsimp"><a name="p8745mcpsimp"></a><a name="p8745mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p8747mcpsimp"><a name="p8747mcpsimp"></a><a name="p8747mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row8748mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p8750mcpsimp"><a name="p8750mcpsimp"></a><a name="p8750mcpsimp"></a>BitmapDescriptor</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p8752mcpsimp"><a name="p8752mcpsimp"></a><a name="p8752mcpsimp"></a>返回<a href="bitmapdescriptor.md">BitmapDescriptor</a>对象，用于定义Bitmap图像。</p>
</td>
</tr>
</tbody>
</table>

## fromBitmap<a name="section375416351533"></a>

<a name="table8754mcpsimp"></a>
<table><thead align="left"><tr id="row8758mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p8760mcpsimp"><a name="p8760mcpsimp"></a><a name="p8760mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row8761mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p8763mcpsimp"><a name="p8763mcpsimp"></a><a name="p8763mcpsimp"></a>public static <a href="bitmapdescriptor.md">BitmapDescriptor</a> fromBitmap(Bitmap image)</p>
<p id="p1520714214712"><a name="p1520714214712"></a><a name="p1520714214712"></a>您调用此API通过Bitmap类型图片创建<a href="bitmapdescriptor.md">BitmapDescriptor</a>对象。</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table8769mcpsimp"></a>
<table><thead align="left"><tr id="row8774mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p8776mcpsimp"><a name="p8776mcpsimp"></a><a name="p8776mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p8778mcpsimp"><a name="p8778mcpsimp"></a><a name="p8778mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row8779mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p8781mcpsimp"><a name="p8781mcpsimp"></a><a name="p8781mcpsimp"></a>image</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p8783mcpsimp"><a name="p8783mcpsimp"></a><a name="p8783mcpsimp"></a>Bitmap图像。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table8786mcpsimp"></a>
<table><thead align="left"><tr id="row8791mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p8793mcpsimp"><a name="p8793mcpsimp"></a><a name="p8793mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p8795mcpsimp"><a name="p8795mcpsimp"></a><a name="p8795mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row8796mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p8798mcpsimp"><a name="p8798mcpsimp"></a><a name="p8798mcpsimp"></a>BitmapDescriptor</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p8800mcpsimp"><a name="p8800mcpsimp"></a><a name="p8800mcpsimp"></a>返回<a href="bitmapdescriptor.md">BitmapDescriptor</a>对象，用于定义Bitmap图像。</p>
</td>
</tr>
</tbody>
</table>

## fromFile<a name="section338617415546"></a>

<a name="table8802mcpsimp"></a>
<table><thead align="left"><tr id="row8806mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p8808mcpsimp"><a name="p8808mcpsimp"></a><a name="p8808mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row8809mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p8811mcpsimp"><a name="p8811mcpsimp"></a><a name="p8811mcpsimp"></a>public static <a href="bitmapdescriptor.md">BitmapDescriptor</a> fromFile(String fileName)</p>
<p id="p21080564477"><a name="p21080564477"></a><a name="p21080564477"></a>您调用此API可以通过内部存储中的图片文件名创建一个<a href="bitmapdescriptor.md">BitmapDescriptor</a>对象。</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table8817mcpsimp"></a>
<table><thead align="left"><tr id="row8822mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p8824mcpsimp"><a name="p8824mcpsimp"></a><a name="p8824mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p8826mcpsimp"><a name="p8826mcpsimp"></a><a name="p8826mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row8827mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p8829mcpsimp"><a name="p8829mcpsimp"></a><a name="p8829mcpsimp"></a>fileName</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p8831mcpsimp"><a name="p8831mcpsimp"></a><a name="p8831mcpsimp"></a>图片的本地文件名。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table8834mcpsimp"></a>
<table><thead align="left"><tr id="row8839mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p8841mcpsimp"><a name="p8841mcpsimp"></a><a name="p8841mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p8843mcpsimp"><a name="p8843mcpsimp"></a><a name="p8843mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row8844mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p8846mcpsimp"><a name="p8846mcpsimp"></a><a name="p8846mcpsimp"></a>BitmapDescriptor</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p8848mcpsimp"><a name="p8848mcpsimp"></a><a name="p8848mcpsimp"></a>返回<a href="bitmapdescriptor.md">BitmapDescriptor</a>对象，用于定义Bitmap图像。</p>
</td>
</tr>
</tbody>
</table>

## fromPath<a name="section1762285545410"></a>

<a name="table8850mcpsimp"></a>
<table><thead align="left"><tr id="row8854mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p8856mcpsimp"><a name="p8856mcpsimp"></a><a name="p8856mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row8857mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p8859mcpsimp"><a name="p8859mcpsimp"></a><a name="p8859mcpsimp"></a>public static <a href="bitmapdescriptor.md">BitmapDescriptor</a> fromPath(String absolutePath)</p>
<p id="p1486710664820"><a name="p1486710664820"></a><a name="p1486710664820"></a>您调用此API可以通过图片资源的绝对路径创建一个<a href="bitmapdescriptor.md">BitmapDescriptor</a>对象。</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table8865mcpsimp"></a>
<table><thead align="left"><tr id="row8870mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p8872mcpsimp"><a name="p8872mcpsimp"></a><a name="p8872mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p8874mcpsimp"><a name="p8874mcpsimp"></a><a name="p8874mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row8875mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p8877mcpsimp"><a name="p8877mcpsimp"></a><a name="p8877mcpsimp"></a>absolutePath</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p8879mcpsimp"><a name="p8879mcpsimp"></a><a name="p8879mcpsimp"></a>图片的绝对路径名。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table8882mcpsimp"></a>
<table><thead align="left"><tr id="row8887mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p8889mcpsimp"><a name="p8889mcpsimp"></a><a name="p8889mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p8891mcpsimp"><a name="p8891mcpsimp"></a><a name="p8891mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row8892mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p8894mcpsimp"><a name="p8894mcpsimp"></a><a name="p8894mcpsimp"></a>BitmapDescriptor</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p8896mcpsimp"><a name="p8896mcpsimp"></a><a name="p8896mcpsimp"></a>返回<a href="bitmapdescriptor.md">BitmapDescriptor</a>对象，用于定义Bitmap图像。</p>
</td>
</tr>
</tbody>
</table>

## fromResource<a name="section11216192714558"></a>

<a name="table8898mcpsimp"></a>
<table><thead align="left"><tr id="row8902mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p8904mcpsimp"><a name="p8904mcpsimp"></a><a name="p8904mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row8905mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p8907mcpsimp"><a name="p8907mcpsimp"></a><a name="p8907mcpsimp"></a>public static <a href="bitmapdescriptor.md">BitmapDescriptor</a> fromResource(int resourceId)</p>
<p id="p2291319164813"><a name="p2291319164813"></a><a name="p2291319164813"></a>您调用此API可以通过图片的资源ID创建一个<a href="bitmapdescriptor.md">BitmapDescriptor</a>对象。</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table8913mcpsimp"></a>
<table><thead align="left"><tr id="row8918mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p8920mcpsimp"><a name="p8920mcpsimp"></a><a name="p8920mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p8922mcpsimp"><a name="p8922mcpsimp"></a><a name="p8922mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row8923mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p8925mcpsimp"><a name="p8925mcpsimp"></a><a name="p8925mcpsimp"></a>resourceId</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p8927mcpsimp"><a name="p8927mcpsimp"></a><a name="p8927mcpsimp"></a>图片的资源ID。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table8930mcpsimp"></a>
<table><thead align="left"><tr id="row8935mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p8937mcpsimp"><a name="p8937mcpsimp"></a><a name="p8937mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p8939mcpsimp"><a name="p8939mcpsimp"></a><a name="p8939mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row8940mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p8942mcpsimp"><a name="p8942mcpsimp"></a><a name="p8942mcpsimp"></a>BitmapDescriptor</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p12927642113212"><a name="p12927642113212"></a><a name="p12927642113212"></a>返回<a href="bitmapdescriptor.md">BitmapDescriptor</a>对象，用于定义Bitmap图像。</p>
</td>
</tr>
</tbody>
</table>

