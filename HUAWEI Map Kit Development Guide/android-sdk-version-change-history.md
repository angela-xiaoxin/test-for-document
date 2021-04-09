# Version Change History<a name="EN-US_TOPIC_0000001145923557"></a>

-   [5.2.0.302 \(2021-03-17\)](#section11607284219)
-   [About SDK Dependencies](#section11913115191910)
-   [Earlier Versions](#section1267344102016)
    -   [5.2.0.301 \(2021-03-09\)](#section1820411114398)
    -   [5.1.0.300 \(2020-12-31\)](#section96211418127)
    -   [5.0.5.301 \(2020-11-27\)](#section141211186522)
    -   [5.0.3.302 \(2020-11-06\)](#section3356334135813)
    -   [5.0.3.301 \(2020-10-27\)](#section675083119719)
    -   [5.0.2.300 \(2020-09-18\)](#section16177174912154)
    -   [5.0.1.301 \(2020-08-14\)](#section11355836172019)
    -   [5.0.1.300 \(2020-07-27\)](#section81811356164617)
    -   [5.0.0.300 \(2020-06-15\)](#section3713742164119)
    -   [4.0.1.302 \(2020-04-30\)](#section1443220818111)
    -   [4.0.0.302 \(2020-02-14\)](#section12975152821114)
    -   [3.0.2.302 \(2019-10-08\)](#section138571251410)
    -   [Documents of Earlier Versions](#section1460132252113)


## 5.2.0.302 \(2021-03-17\)<a name="section11607284219"></a>

<a name="simpletable220481173919"></a>
<table id="simpletable220481173919"><tr id="strow1204121153911"><td valign="top" id="stentry4204131203911"><p id="p5160102810215"><a name="p5160102810215"></a><a name="p5160102810215"></a>SDK version for Android: com.huawei.hms:maps:5.2.0.302</p>
<p id="p8160122819218"><a name="p8160122819218"></a><a name="p8160122819218"></a><strong id="b572217516241"><a name="b572217516241"></a><a name="b572217516241"></a>New Features</strong></p>
<p id="p16469114544011"><a name="p16469114544011"></a><a name="p16469114544011"></a>Fixed the issue that the fallback-version SDK prompts users to update HMS Core (APK).</p>
</td>
</tr>
</table>

## About SDK Dependencies<a name="section11913115191910"></a>

-   The SDK of the latest version can be used only on devices running HMS Core \(APK\) 5.1.0 or later. If HMS Core \(APK\) is not installed or its version is earlier than 5.1.0, Map Kit functions can be normally used but the Map SDK version cannot be automatically updated.
-   Basic features of this Kit are available on most Huawei devices, whereas some advanced features are available only on Huawei devices running specific EMUI versions. For details, please refer to  [EMUI Version-Dependent Features](en-us_topic_0000001050042515.md).

Tips: If you have any questions about integrating the HMS Core SDK or releasing your app on HUAWEI AppGallery,  [submit a ticket online](https://developer.huawei.com/consumer/en/support/feedback/#/).

## Earlier Versions<a name="section1267344102016"></a>

### 5.2.0.301 \(2021-03-09\)<a name="section1820411114398"></a>

<a name="simpletable216013281224"></a>
<table id="simpletable216013281224"><tr id="strow116010281323"><td valign="top" id="stentry416022814210"><p id="p720420116395"><a name="p720420116395"></a><a name="p720420116395"></a>SDK version for Android: com.huawei.hms:maps:5.2.0.301</p>
<p id="p12204101183914"><a name="p12204101183914"></a><a name="p12204101183914"></a><strong id="b1720133669"><a name="b1720133669"></a><a name="b1720133669"></a>New Features</strong></p>
<a name="ul32859291243"></a><a name="ul32859291243"></a><ul id="ul32859291243"><li>Added the <a href="en-us_topic_0000001098843536.md#section11137745113915">setMarkerClusterColor</a> method to the <a href="en-us_topic_0000001098843536.md">UiSettings</a> class. This method is used to set the color of the default cluster marker.</li><li>Added the <a href="en-us_topic_0000001098843536.md#section72972050124113">setMarkerClusterIcon</a> and <a href="en-us_topic_0000001098843536.md#section3137125684216">setMarkerClusterTextColor</a> methods to the <a href="en-us_topic_0000001098843536.md">UiSettings</a> class. The methods are used to set the icon and text color of the custom cluster marker. </li><li>Added the API key protection measures in <a href="faq.md">FAQs</a>.</li></ul>
</td>
</tr>
</table>

### 5.1.0.300 \(2020-12-31\)<a name="section96211418127"></a>

<a name="simpletable7621241131211"></a>
<table id="simpletable7621241131211"><tr id="strow263141191212"><td valign="top" id="stentry136394117124"><p id="p663741171218"><a name="p663741171218"></a><a name="p663741171218"></a>SDK version for Android: com.huawei.hms:maps:5.1.0.300</p>
<p id="p8631441131217"><a name="p8631441131217"></a><a name="p8631441131217"></a><strong id="b2324815817"><a name="b2324815817"></a><a name="b2324815817"></a>New Features</strong></p>
<p id="p596402611720"><a name="p596402611720"></a><a name="p596402611720"></a>Added the guide for adding dependencies on two fallbacks, so that Map Kit can be used on non-Huawei Android phones and in other scenarios where HMS Core (APK) is not required.</p>
</td>
</tr>
</table>

### 5.0.5.301 \(2020-11-27\)<a name="section141211186522"></a>

<a name="simpletable13121181816520"></a>
<table id="simpletable13121181816520"><tr id="strow1112131811528"><td valign="top" id="stentry111211118165211"><p id="p151217184528"><a name="p151217184528"></a><a name="p151217184528"></a>SDK version for Android: com.huawei.hms:maps:5.0.5.301</p>
<p id="p31219180525"><a name="p31219180525"></a><a name="p31219180525"></a><strong id="b1789417902312"><a name="b1789417902312"></a><a name="b1789417902312"></a>New Features</strong></p>
<a name="ul14121201885213"></a><a name="ul14121201885213"></a><ul id="ul14121201885213"><li>Added the Kotlin sample code.</li><li>Added the <a href="en-us_topic_0000001098683684.md#section63930559559">setPointToCenter</a> method to the <a href="en-us_topic_0000001098683684.md">HuaweiMap</a> class, which is used to set a fixed screen center for zooming. </li><li>Added the <a href="en-us_topic_0000001098843536.md#section8176121651612">setGestureScaleByMapCenter</a> method to the <a href="en-us_topic_0000001098843536.md">UiSettings</a> class, which is used to specify whether a fixed screen center can be set for zooming. </li></ul>
</td>
</tr>
</table>

### 5.0.3.302 \(2020-11-06\)<a name="section3356334135813"></a>

<a name="simpletable12947466182"></a>
<table id="simpletable12947466182"><tr id="strow14294646101814"><td valign="top" id="stentry62941146161819"><p id="p1635643435816"><a name="p1635643435816"></a><a name="p1635643435816"></a>SDK version for Android: com.huawei.hms:maps:5.0.3.302</p>
<p id="p1835618342589"><a name="p1835618342589"></a><a name="p1835618342589"></a><strong id="b19609193151012"><a name="b19609193151012"></a><a name="b19609193151012"></a>Modified Features</strong></p>
<p id="p8356534115812"><a name="p8356534115812"></a><a name="p8356534115812"></a>Fixed the issue that the obfuscation configuration conflicts with that of other kits.</p>
</td>
</tr>
</table>

### 5.0.3.301 \(2020-10-27\)<a name="section675083119719"></a>

<a name="simpletable13750143118711"></a>
<table id="simpletable13750143118711"><tr id="strow175063116710"><td valign="top" id="stentry1175193117719"><p id="p875117318711"><a name="p875117318711"></a><a name="p875117318711"></a>SDK version for Android: com.huawei.hms:maps:5.0.3.301</p>
<p id="p1881854132117"><a name="p1881854132117"></a><a name="p1881854132117"></a><strong id="b1908515960"><a name="b1908515960"></a><a name="b1908515960"></a>Modified Features</strong></p>
<a name="ul168917549211"></a><a name="ul168917549211"></a><ul id="ul168917549211"><li>Optimized the log information.</li><li>Optimized the marker clustering performance in the marker deletion/hiding scenarios.</li><li>Fixed the multi-language issue that occurs when an app is released to an app store other than AppGallery.</li></ul>
</td>
</tr>
</table>

### 5.0.2.300 \(2020-09-18\)<a name="section16177174912154"></a>

<a name="simpletable11177174941513"></a>
<table id="simpletable11177174941513"><tr id="strow317734981518"><td valign="top" id="stentry1117734961515"><p id="p1717744917159"><a name="p1717744917159"></a><a name="p1717744917159"></a>SDK version for Android: com.huawei.hms:maps:5.0.2.300</p>
<p id="p15177204951517"><a name="p15177204951517"></a><a name="p15177204951517"></a><strong id="b18990132511812"><a name="b18990132511812"></a><a name="b18990132511812"></a>New Features</strong></p>
<p id="p11177124914151"><a name="p11177124914151"></a><a name="p11177124914151"></a>Optimized the marker clustering performance.</p>
</td>
</tr>
</table>

### 5.0.1.301 \(2020-08-14\)<a name="section11355836172019"></a>

<a name="simpletable1935593610206"></a>
<table id="simpletable1935593610206"><tr id="strow1235563612015"><td valign="top" id="stentry1035510361201"><p id="p36473593207"><a name="p36473593207"></a><a name="p36473593207"></a>SDK version for Android: com.huawei.hms:maps:5.0.1.301</p>
<p id="p964755912206"><a name="p964755912206"></a><a name="p964755912206"></a><strong id="b1333409506"><a name="b1333409506"></a><a name="b1333409506"></a>New Features</strong></p>
<p id="p764714593206"><a name="p764714593206"></a><a name="p764714593206"></a>Optimized the <a href="en-us_topic_0000001098683684.md#section105931534124619">animateCamera(CameraUpdate update, HuaweiMap.CancelableCallback callback)</a> method in the <a href="en-us_topic_0000001098683684.md">HuaweiMap</a> class to fix the issue that the callback cannot be performed.</p>
</td>
</tr>
</table>

### 5.0.1.300 \(2020-07-27\)<a name="section81811356164617"></a>

<a name="simpletable118145624611"></a>
<table id="simpletable118145624611"><tr id="strow118114565468"><td valign="top" id="stentry318111568464"><p id="p10181135611468"><a name="p10181135611468"></a><a name="p10181135611468"></a>SDK version for Android: com.huawei.hms:maps:5.0.1.300</p>
<p id="p14181115674615"><a name="p14181115674615"></a><a name="p14181115674615"></a><strong id="b1830211360118"><a name="b1830211360118"></a><a name="b1830211360118"></a>Modified Features</strong></p>
<a name="ul8271318164811"></a><a name="ul8271318164811"></a><ul id="ul8271318164811"><li>Added definitions for the <a href="en-us_topic_0000001145923481.md">TextureMapFragment</a>, <a href="en-us_topic_0000001145843387.md">TextureMapView</a>, and <a href="en-us_topic_0000001098843532.md">TextureSupportMapFragment</a> classes. Black screen will not appear when multiple fragments are supported.</li><li>Added <a href="en-us_topic_0000001145523533.md#section138322612114">setAnimation</a>(<a href="en-us_topic_0000001145723449.md">Animation</a><strong id="b1251013816443"><a name="b1251013816443"></a><a name="b1251013816443"></a> animation</strong>) for setting animation for a marker and <a href="en-us_topic_0000001145523533.md#section13557451287">startAnimation</a><strong id="b12510488447"><a name="b12510488447"></a><a name="b12510488447"></a>()</strong> for starting animation for a marker, and added definitions for the <a href="en-us_topic_0000001145723449.md">Animation</a>, <a href="en-us_topic_0000001145843371.md">AlphaAnimation</a>, <a href="en-us_topic_0000001145723453.md">RotateAnimation</a>, <a href="en-us_topic_0000001145923491.md">ScaleAnimation</a>, <a href="en-us_topic_0000001098843526.md">TranslateAnimation</a>, and <a href="en-us_topic_0000001145723441.md">AnimationSet</a> classes.</li></ul>
</td>
</tr>
</table>

### 5.0.0.300 \(2020-06-15\)<a name="section3713742164119"></a>

<a name="simpletable246102117221"></a>
<table id="simpletable246102117221"><tr id="strow14461021102210"><td valign="top" id="stentry19461172114222"><p id="p97721543122218"><a name="p97721543122218"></a><a name="p97721543122218"></a>SDK version for Android: com.huawei.hms:maps:5.0.0.300</p>
<p id="p141870834211"><a name="p141870834211"></a><a name="p141870834211"></a><strong id="b8742530182413"><a name="b8742530182413"></a><a name="b8742530182413"></a>Modified Features</strong></p>
<p id="p4187887429"><a name="p4187887429"></a><a name="p4187887429"></a>Added API key authentication. You can set an API key in either of the following ways:</p>
<a name="ul5187382422"></a><a name="ul5187382422"></a><ul id="ul5187382422"><li>Set the <strong id="b545131532620"><a name="b545131532620"></a><a name="b545131532620"></a>api_key</strong> field in the <strong id="b198391924132611"><a name="b198391924132611"></a><a name="b198391924132611"></a>agconnect-services.json</strong> file.</li><li>Call the <strong id="b10556723123014"><a name="b10556723123014"></a><a name="b10556723123014"></a>MapsInitializer.setApiKey(String)</strong> method.</li></ul>
</td>
</tr>
</table>

### 4.0.1.302 \(2020-04-30\)<a name="section1443220818111"></a>

<a name="simpletable2714928102314"></a>
<table id="simpletable2714928102314"><tr id="strow2715528192314"><td valign="top" id="stentry12715162862320"><p id="p11414441151515"><a name="p11414441151515"></a><a name="p11414441151515"></a>SDK version for Android: com.huawei.hms:maps:4.0.1.302</p>
<p id="p54141841121515"><a name="p54141841121515"></a><a name="p54141841121515"></a><strong id="b158541533199"><a name="b158541533199"></a><a name="b158541533199"></a>New Features</strong></p>
<a name="ul1160132110117"></a><a name="ul1160132110117"></a><ul id="ul1160132110117"><li>Added the <a href="en-us_topic_0000001098683684.md#section10782142412914">setPadding</a>, <a href="en-us_topic_0000001098683684.md#section123781718617">setContentDescription</a>, <a href="en-us_topic_0000001098683684.md#section34348380817">setOnPoiClickListener</a>, and <a href="en-us_topic_0000001098683684.md#section48222916516">setOnGroundOverlayClickListener</a> methods to the <a href="en-us_topic_0000001098683684.md">HuaweiMap</a> class.</li><li>Supported the anchor point attribute setting for markers, ground overlays, and information windows. </li><li>Supported settings of attributes such as visibility, z-index, and outline style for polylines, polygons, and circles.</li><li>Supported APIs related to <a href="en-us_topic_0000001145723445.md">TileOverlay</a>.</li><li>Added the function of accessing <strong id="b113021333103"><a name="b113021333103"></a><a name="b113021333103"></a>MapService</strong> to obtain the earliest HMS Core (APK) version that is required for using the SDK.</li></ul>
</td>
</tr>
</table>

### 4.0.0.302 \(2020-02-14\)<a name="section12975152821114"></a>

<a name="simpletable81211259182512"></a>
<table id="simpletable81211259182512"><tr id="strow512245914259"><td valign="top" id="stentry012265982515"><p id="p917212510264"><a name="p917212510264"></a><a name="p917212510264"></a>SDK version for Android: com.huawei.hms:maps:4.0.0.302</p>
<p id="p663515953520"><a name="p663515953520"></a><a name="p663515953520"></a><strong id="b266642051616"><a name="b266642051616"></a><a name="b266642051616"></a>New Features</strong></p>
<p id="p645019461531"><a name="p645019461531"></a><a name="p645019461531"></a>Added the real-time traffic status function. You can call <a href="en-us_topic_0000001098683684.md">HuaweiMap</a>.<a href="en-us_topic_0000001098683684.md#section14752131510581">setTrafficEnabled(boolean enabled)</a> to enable or disable this function.</p>
</td>
</tr>
</table>

### 3.0.2.302 \(2019-10-08\)<a name="section138571251410"></a>

<a name="simpletable111388367263"></a>
<table id="simpletable111388367263"><tr id="strow16138193612619"><td valign="top" id="stentry1013823682618"><p id="p013823620266"><a name="p013823620266"></a><a name="p013823620266"></a>SDK version for Android: com.huawei.hms:maps:3.0.2.302</p>
<p id="p1939063562912"><a name="p1939063562912"></a><a name="p1939063562912"></a><strong id="b16722522181819"><a name="b16722522181819"></a><a name="b16722522181819"></a>New Features</strong></p>
<a name="ul1732912804118"></a><a name="ul1732912804118"></a><ul id="ul1732912804118"><li>Map display: Displays buildings, roads, water systems, and Points of Interest (POIs).</li><li>Map interaction: Controls the interaction gestures and buttons on the map.</li><li>Map drawing: Adds location markers, map layers, overlays, and various shapes.</li></ul>
</td>
</tr>
</table>

### Documents of Earlier Versions<a name="section1460132252113"></a>

[Map Kit 4.0](https://developer.huawei.com/consumer/en/doc/development/HMS-Guides/hms-map-v4-abouttheservice)

