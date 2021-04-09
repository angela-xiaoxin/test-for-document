# MapView<a name="EN-US_TOPIC_0000001099181264"></a>

-   [Public Constructor Summary](#section16131398535)
-   [Public Method Summary](#section15678173605416)
-   [Public Constructors](#section19848311202)
-   [MapView\(Context context\)](#section114762417137)
-   [MapView\(Context context, AttributeSet attrs\)](#section11481108176)
-   [MapView\(Context context, AttributeSet attrs, int defStyle\)](#section817711579171)
-   [MapView\(Context context, HuaweiMapOptions options\)](#section03591042182)
-   [Public Methods](#section35314160400)
-   [getMapAsync](#section18155143712405)
-   [onCreate](#section5701320154117)
-   [onDestroy](#section1991150164217)
-   [onLowMemory](#section1298412345428)
-   [onPause](#section119871413124319)
-   [onResume](#section127594720434)
-   [onSaveInstanceState](#section17492429104415)
-   [onStart](#section1929311316455)
-   [onStop](#section1185125812451)


<a name="table7100mcpsimp"></a>
<table><thead align="left"><tr id="row7104mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p7106mcpsimp"><a name="p7106mcpsimp"></a><a name="p7106mcpsimp"></a>Class Info</p>
</th>
</tr>
</thead>
<tbody><tr id="row7107mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p3343155117353"><a name="p3343155117353"></a><a name="p3343155117353"></a>public class MapView</p>
<p id="p7109mcpsimp"><a name="p7109mcpsimp"></a><a name="p7109mcpsimp"></a>Class inherited from <strong id="b890911235912"><a name="b890911235912"></a><a name="b890911235912"></a>FrameLayout</strong> and representing a map view. (The view data is obtained from HUAWEI Map Kit.)</p>
</td>
</tr>
</tbody>
</table>

## Public Constructor Summary<a name="section16131398535"></a>

>![](public_sys-resources/icon-note.gif) **NOTE:** 
>If the input parameter is not of the  **Activity**  type, no update wizard will be displayed to a user when HMS Core \(APK\) needs to be updated. Instead, the error information "Hms is not available26" is displayed. In such case, HMS Core \(APK\) needs to be manually updated. To show the update wizard, you are advised to pass a parameter of the  **Activity**  type instead of the  **Context**  type to create a  [MapView](mapview.md)  instance.

<a name="table7113mcpsimp"></a>
<table><thead align="left"><tr id="row7117mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p7119mcpsimp"><a name="p7119mcpsimp"></a><a name="p7119mcpsimp"></a>Constructor Name</p>
</th>
</tr>
</thead>
<tbody><tr id="row7120mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p7122mcpsimp"><a name="p7122mcpsimp"></a><a name="p7122mcpsimp"></a><a href="#section114762417137">MapView</a>(Context context)</p>
<p id="p1764722632"><a name="p1764722632"></a><a name="p1764722632"></a>Creates a <a href="mapview.md">MapView</a> object using the context.</p>
</td>
</tr>
<tr id="row7123mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p7125mcpsimp"><a name="p7125mcpsimp"></a><a name="p7125mcpsimp"></a><a href="#section11481108176">MapView</a>(Context context, AttributeSet attrs)</p>
<p id="p8617195618718"><a name="p8617195618718"></a><a name="p8617195618718"></a>Creates a <a href="mapview.md">MapView</a> object based on specified parameters.</p>
</td>
</tr>
<tr id="row7126mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p7128mcpsimp"><a name="p7128mcpsimp"></a><a name="p7128mcpsimp"></a><a href="#section817711579171">MapView</a>(Context context, AttributeSet attrs, int defStyle)</p>
<p id="p3485858978"><a name="p3485858978"></a><a name="p3485858978"></a>Creates a <a href="mapview.md">MapView</a> object based on specified parameters.</p>
</td>
</tr>
<tr id="row7129mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p7131mcpsimp"><a name="p7131mcpsimp"></a><a name="p7131mcpsimp"></a><a href="#section03591042182">MapView</a>(Context context, <a href="huaweimapooptions.md">HuaweiMapOptions</a> options)</p>
<p id="p1342641282"><a name="p1342641282"></a><a name="p1342641282"></a>Creates a <a href="mapview.md">MapView</a> object based on specified parameters.</p>
</td>
</tr>
</tbody>
</table>

## Public Method Summary<a name="section15678173605416"></a>

<a name="table7133mcpsimp"></a>
<table><thead align="left"><tr id="row7138mcpsimp"><th class="cellrowborder" valign="top" width="40%" id="mcps1.1.3.1.1"><p id="p7140mcpsimp"><a name="p7140mcpsimp"></a><a name="p7140mcpsimp"></a>Qualifier and Type</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.1.3.1.2"><p id="p7142mcpsimp"><a name="p7142mcpsimp"></a><a name="p7142mcpsimp"></a>Method Name and Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row7143mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p7145mcpsimp"><a name="p7145mcpsimp"></a><a name="p7145mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p7147mcpsimp"><a name="p7147mcpsimp"></a><a name="p7147mcpsimp"></a><a href="#section18155143712405">getMapAsync</a>(<a href="onmapreadycallback.md">OnMapReadyCallback</a> callback)</p>
<p id="p182634514816"><a name="p182634514816"></a><a name="p182634514816"></a>Obtains a <a href="huaweimap.md">HuaweiMap</a> object when the object is ready. </p>
</td>
</tr>
<tr id="row7148mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p7150mcpsimp"><a name="p7150mcpsimp"></a><a name="p7150mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p7152mcpsimp"><a name="p7152mcpsimp"></a><a name="p7152mcpsimp"></a><a href="#section5701320154117">onCreate</a>(Bundle savedInstanceState)</p>
<p id="p533312612483"><a name="p533312612483"></a><a name="p533312612483"></a>Called when a map is created.</p>
</td>
</tr>
<tr id="row7153mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p7155mcpsimp"><a name="p7155mcpsimp"></a><a name="p7155mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p7157mcpsimp"><a name="p7157mcpsimp"></a><a name="p7157mcpsimp"></a><a href="#section1991150164217">onDestroy</a>()</p>
<p id="p1934110784817"><a name="p1934110784817"></a><a name="p1934110784817"></a>Called when a map is destroyed.</p>
</td>
</tr>
<tr id="row7168mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p7170mcpsimp"><a name="p7170mcpsimp"></a><a name="p7170mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p7172mcpsimp"><a name="p7172mcpsimp"></a><a name="p7172mcpsimp"></a><a href="#section1298412345428">onLowMemory</a>()</p>
<p id="p72772984810"><a name="p72772984810"></a><a name="p72772984810"></a>Called when the memory is insufficient.</p>
</td>
</tr>
<tr id="row7173mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p7175mcpsimp"><a name="p7175mcpsimp"></a><a name="p7175mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p7177mcpsimp"><a name="p7177mcpsimp"></a><a name="p7177mcpsimp"></a><a href="#section119871413124319">onPause</a>()</p>
<p id="p1234251084816"><a name="p1234251084816"></a><a name="p1234251084816"></a>Called when an activity is paused.</p>
</td>
</tr>
<tr id="row7178mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p7180mcpsimp"><a name="p7180mcpsimp"></a><a name="p7180mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p7182mcpsimp"><a name="p7182mcpsimp"></a><a name="p7182mcpsimp"></a><a href="#section127594720434">onResume</a>()</p>
<p id="p3109141144810"><a name="p3109141144810"></a><a name="p3109141144810"></a>Called when an activity is ready.</p>
</td>
</tr>
<tr id="row7183mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p7185mcpsimp"><a name="p7185mcpsimp"></a><a name="p7185mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p7187mcpsimp"><a name="p7187mcpsimp"></a><a name="p7187mcpsimp"></a><a href="#section17492429104415">onSaveInstanceState</a>(Bundle outState)</p>
<p id="p14183612114811"><a name="p14183612114811"></a><a name="p14183612114811"></a>Called to save the current map status upon unexpected exit.</p>
</td>
</tr>
<tr id="row7188mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p7190mcpsimp"><a name="p7190mcpsimp"></a><a name="p7190mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p7192mcpsimp"><a name="p7192mcpsimp"></a><a name="p7192mcpsimp"></a><a href="#section1929311316455">onStart</a>()</p>
<p id="p10147181312488"><a name="p10147181312488"></a><a name="p10147181312488"></a>Called when an activity is created successfully. Then the map is visible.</p>
</td>
</tr>
<tr id="row7193mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p7195mcpsimp"><a name="p7195mcpsimp"></a><a name="p7195mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p7197mcpsimp"><a name="p7197mcpsimp"></a><a name="p7197mcpsimp"></a><a href="#section1185125812451">onStop</a>()</p>
<p id="p14801814164813"><a name="p14801814164813"></a><a name="p14801814164813"></a>Called when an activity exits. Then the map is invisible.</p>
</td>
</tr>
</tbody>
</table>

## Public Constructors<a name="section19848311202"></a>

## MapView\(Context context\)<a name="section114762417137"></a>

<a name="table227mcpsimp"></a>
<table><thead align="left"><tr id="row231mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p233mcpsimp"><a name="p233mcpsimp"></a><a name="p233mcpsimp"></a>Constructor</p>
</th>
</tr>
</thead>
<tbody><tr id="row235mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p17568645115116"><a name="p17568645115116"></a><a name="p17568645115116"></a>public <a href="mapview.md">MapView</a>(Context context)</p>
<p id="p11568945165115"><a name="p11568945165115"></a><a name="p11568945165115"></a>Creates a <a href="mapview.md">MapView</a> object using the context.</p>
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
<td class="cellrowborder" valign="top" width="56.99999999999999%" headers="mcps1.1.3.1.2 "><p id="p69541622141317"><a name="p69541622141317"></a><a name="p69541622141317"></a>Context.</p>
</td>
</tr>
</tbody>
</table>

## MapView\(Context context, AttributeSet attrs\)<a name="section11481108176"></a>

<a name="table13559181541919"></a>
<table><thead align="left"><tr id="row5559191531917"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p185592015191911"><a name="p185592015191911"></a><a name="p185592015191911"></a>Constructor</p>
</th>
</tr>
</thead>
<tbody><tr id="row356013155191"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p45601152191"><a name="p45601152191"></a><a name="p45601152191"></a>public <a href="mapview.md">MapView</a>(Context context, AttributeSet attrs)</p>
<p id="p18560131571916"><a name="p18560131571916"></a><a name="p18560131571916"></a>Creates a <a href="mapview.md">MapView</a> object based on specified parameters.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table14560815171915"></a>
<table><thead align="left"><tr id="row15601415191910"><th class="cellrowborder" valign="top" width="43%" id="mcps1.1.3.1.1"><p id="p1456020150196"><a name="p1456020150196"></a><a name="p1456020150196"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="56.99999999999999%" id="mcps1.1.3.1.2"><p id="p1356041515199"><a name="p1356041515199"></a><a name="p1356041515199"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row8560121571913"><td class="cellrowborder" valign="top" width="43%" headers="mcps1.1.3.1.1 "><p id="p17560215151918"><a name="p17560215151918"></a><a name="p17560215151918"></a>context</p>
</td>
<td class="cellrowborder" valign="top" width="56.99999999999999%" headers="mcps1.1.3.1.2 "><p id="p1560121519192"><a name="p1560121519192"></a><a name="p1560121519192"></a>Context.</p>
</td>
</tr>
<tr id="row9560151581910"><td class="cellrowborder" valign="top" width="43%" headers="mcps1.1.3.1.1 "><p id="p195619153199"><a name="p195619153199"></a><a name="p195619153199"></a>attrs</p>
</td>
<td class="cellrowborder" valign="top" width="56.99999999999999%" headers="mcps1.1.3.1.2 "><p id="p456111154190"><a name="p456111154190"></a><a name="p456111154190"></a>Collection of <strong id="b5551163982916"><a name="b5551163982916"></a><a name="b5551163982916"></a>MapView</strong> attributes in the XML file. </p>
</td>
</tr>
</tbody>
</table>

## MapView\(Context context, AttributeSet attrs, int defStyle\)<a name="section817711579171"></a>

<a name="table674118239196"></a>
<table><thead align="left"><tr id="row13741132319194"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p13741112315191"><a name="p13741112315191"></a><a name="p13741112315191"></a>Constructor</p>
</th>
</tr>
</thead>
<tbody><tr id="row274292311910"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p474219239191"><a name="p474219239191"></a><a name="p474219239191"></a>public <a href="mapview.md">MapView</a>(Context context, AttributeSet attrs, int defStyle)</p>
<p id="p107421323191911"><a name="p107421323191911"></a><a name="p107421323191911"></a>Creates a <a href="mapview.md">MapView</a> object based on specified parameters.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table20742142319197"></a>
<table><thead align="left"><tr id="row1174262317194"><th class="cellrowborder" valign="top" width="43%" id="mcps1.1.3.1.1"><p id="p574216236192"><a name="p574216236192"></a><a name="p574216236192"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="56.99999999999999%" id="mcps1.1.3.1.2"><p id="p57421523201914"><a name="p57421523201914"></a><a name="p57421523201914"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row774211232196"><td class="cellrowborder" valign="top" width="43%" headers="mcps1.1.3.1.1 "><p id="p4742323161914"><a name="p4742323161914"></a><a name="p4742323161914"></a>context</p>
</td>
<td class="cellrowborder" valign="top" width="56.99999999999999%" headers="mcps1.1.3.1.2 "><p id="p87426232193"><a name="p87426232193"></a><a name="p87426232193"></a>Context.</p>
</td>
</tr>
<tr id="row14742723191915"><td class="cellrowborder" valign="top" width="43%" headers="mcps1.1.3.1.1 "><p id="p1574218234194"><a name="p1574218234194"></a><a name="p1574218234194"></a>attrs</p>
</td>
<td class="cellrowborder" valign="top" width="56.99999999999999%" headers="mcps1.1.3.1.2 "><p id="p1174219238194"><a name="p1174219238194"></a><a name="p1174219238194"></a>Collection of <strong id="b461745784113"><a name="b461745784113"></a><a name="b461745784113"></a>MapView</strong> attributes in the XML file. </p>
</td>
</tr>
<tr id="row20742112341918"><td class="cellrowborder" valign="top" width="43%" headers="mcps1.1.3.1.1 "><p id="p6742172310199"><a name="p6742172310199"></a><a name="p6742172310199"></a>defStyle</p>
</td>
<td class="cellrowborder" valign="top" width="56.99999999999999%" headers="mcps1.1.3.1.2 "><p id="p11742523171913"><a name="p11742523171913"></a><a name="p11742523171913"></a>Attributes of the current theme, including reference to the style resource. The resource provides default values for the map view. The value <strong id="b4991121193015"><a name="b4991121193015"></a><a name="b4991121193015"></a>0</strong> indicates that default values are not used.</p>
</td>
</tr>
</tbody>
</table>

## MapView\(Context context, HuaweiMapOptions options\)<a name="section03591042182"></a>

<a name="table6694274197"></a>
<table><thead align="left"><tr id="row1969027161912"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p12707270198"><a name="p12707270198"></a><a name="p12707270198"></a>Constructor</p>
</th>
</tr>
</thead>
<tbody><tr id="row07092717193"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p4704279190"><a name="p4704279190"></a><a name="p4704279190"></a>public <a href="mapview.md">MapView</a>(Context context, <a href="huaweimapooptions.md">HuaweiMapOptions</a> options)</p>
<p id="p15701276196"><a name="p15701276196"></a><a name="p15701276196"></a>Creates a <a href="mapview.md">MapView</a> object based on specified parameters.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table1570102710198"></a>
<table><thead align="left"><tr id="row270192751915"><th class="cellrowborder" valign="top" width="43%" id="mcps1.1.3.1.1"><p id="p3701427151911"><a name="p3701427151911"></a><a name="p3701427151911"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="56.99999999999999%" id="mcps1.1.3.1.2"><p id="p1070122714196"><a name="p1070122714196"></a><a name="p1070122714196"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row1570527171911"><td class="cellrowborder" valign="top" width="43%" headers="mcps1.1.3.1.1 "><p id="p4701227131913"><a name="p4701227131913"></a><a name="p4701227131913"></a>context</p>
</td>
<td class="cellrowborder" valign="top" width="56.99999999999999%" headers="mcps1.1.3.1.2 "><p id="p770112712191"><a name="p770112712191"></a><a name="p770112712191"></a>Context.</p>
</td>
</tr>
<tr id="row17711927121918"><td class="cellrowborder" valign="top" width="43%" headers="mcps1.1.3.1.1 "><p id="p6711127181919"><a name="p6711127181919"></a><a name="p6711127181919"></a>options</p>
</td>
<td class="cellrowborder" valign="top" width="56.99999999999999%" headers="mcps1.1.3.1.2 "><p id="p97152741912"><a name="p97152741912"></a><a name="p97152741912"></a><a href="huaweimapooptions.md">HuaweiMapOptions</a> instance that contains configurations about the Huawei map. </p>
</td>
</tr>
</tbody>
</table>

## Public Methods<a name="section35314160400"></a>

## getMapAsync<a name="section18155143712405"></a>

<a name="table7200mcpsimp"></a>
<table><thead align="left"><tr id="row7204mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p7206mcpsimp"><a name="p7206mcpsimp"></a><a name="p7206mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row7207mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p7209mcpsimp"><a name="p7209mcpsimp"></a><a name="p7209mcpsimp"></a>public void getMapAsync(<a href="onmapreadycallback.md">OnMapReadyCallback</a> callback)</p>
<p id="p1059013587146"><a name="p1059013587146"></a><a name="p1059013587146"></a>Obtains a <a href="huaweimap.md">HuaweiMap</a> object when the object is ready. </p>
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
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p7229mcpsimp"><a name="p7229mcpsimp"></a><a name="p7229mcpsimp"></a>Callback to be executed when a <a href="huaweimap.md">HuaweiMap</a> object is ready for use.</p>
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
<p id="p18361240144113"><a name="p18361240144113"></a><a name="p18361240144113"></a>Called when a map is created. If this method needs to be reloaded, call it from the parent class.</p>
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
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p7263mcpsimp"><a name="p7263mcpsimp"></a><a name="p7263mcpsimp"></a>Map status to be saved.</p>
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
<p id="p7280mcpsimp"><a name="p7280mcpsimp"></a><a name="p7280mcpsimp"></a>Called when a map is destroyed. If this method needs to be reloaded, call it from the parent class.</p>
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
<p id="p7300mcpsimp"><a name="p7300mcpsimp"></a><a name="p7300mcpsimp"></a>Called when the memory is insufficient. If this method needs to be reloaded, call it from the parent class.</p>
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
<p id="p6656183015434"><a name="p6656183015434"></a><a name="p6656183015434"></a>Called when an activity is paused. If this method needs to be reloaded, call it from the parent class.</p>
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
<p id="p7340mcpsimp"><a name="p7340mcpsimp"></a><a name="p7340mcpsimp"></a>Called when an activity is ready. If this method needs to be reloaded, call it from the parent class.</p>
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
<p id="p7360mcpsimp"><a name="p7360mcpsimp"></a><a name="p7360mcpsimp"></a>Called to save the current map status upon unexpected app exit.</p>
<p id="p7363mcpsimp"><a name="p7363mcpsimp"></a><a name="p7363mcpsimp"></a>If this method needs to be reloaded, call it from the parent class.</p>
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
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p7380mcpsimp"><a name="p7380mcpsimp"></a><a name="p7380mcpsimp"></a>Map status to be saved.</p>
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
<p id="p7397mcpsimp"><a name="p7397mcpsimp"></a><a name="p7397mcpsimp"></a>Called when an activity is created successfully. Then the map is visible. If this method needs to be reloaded, call it from the parent class.</p>
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
<p id="p7417mcpsimp"><a name="p7417mcpsimp"></a><a name="p7417mcpsimp"></a>Called when an activity exits. Then the map is invisible. If this method needs to be reloaded, call it from the parent class.</p>
</td>
</tr>
</tbody>
</table>

