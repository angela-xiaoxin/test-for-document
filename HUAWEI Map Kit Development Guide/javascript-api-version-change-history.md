# Version Change History<a name="EN-US_TOPIC_0000001145723509"></a>

-   [5.2.0.300 \(2021-03-09\)](#section1975882984511)
-   [Earlier Versions](#section185731027105216)
    -   [5.1.1.300 \(2021-01-29\)](#section197526615243)
    -   [5.1.0.300 \(2020-12-31\)](#section41141212193417)
    -   [5.0.5.300 \(2020-11-27\)](#section137948182311)
    -   [5.0.2.300 \(2020-09-18\)](#section1293013818228)
    -   [5.0.1.300 \(2020-07-13\)](#section1230951612514)
    -   [4.0.4.300 \(2020-05-25\)](#section177811737194015)
    -   [4.0.3.300 \(2020-03-27\)](#section3117143172416)
    -   [4.0.2.300 \(2020-03-12\)](#section4293173412246)
    -   [4.0.1.300 \(2020-01-21\)](#section10201151052417)
    -   [4.0.0.300 \(2019-12-30\)](#section27214573129)


## 5.2.0.300 \(2021-03-09\)<a name="section1975882984511"></a>

<a name="simpletable975892984513"></a>
<table id="simpletable975892984513"><tr id="strow1775982915454"><td valign="top" id="stentry107591529194518"><p id="p17759162914514"><a name="p17759162914514"></a><a name="p17759162914514"></a>The feature updates for JavaScript API are as follows:</p>
<p id="p10759152904514"><a name="p10759152904514"></a><a name="p10759152904514"></a><strong id="b5847165417580"><a name="b5847165417580"></a><a name="b5847165417580"></a>New Features</strong></p>
<a name="ul3659163317411"></a><a name="ul3659163317411"></a>
<p id="p124651633468"><a name="p124651633468"></a><a name="p124651633468"></a>Added the <strong id="b35341120915"><a name="b35341120915"></a><a name="b35341120915"></a>hasRestrictedRoad</strong>, <strong id="b1181419245118"><a name="b1181419245118"></a><a name="b1181419245118"></a>dstInRestrictedArea</strong>, <strong id="b1615230719"><a name="b1615230719"></a><a name="b1615230719"></a>crossCountry</strong>, <strong id="b63531635715"><a name="b63531635715"></a><a name="b63531635715"></a>crossMultiCountries</strong>, <strong id="b275143914116"><a name="b275143914116"></a><a name="b275143914116"></a>hasRoughRoad</strong>, <strong id="b527116451415"><a name="b527116451415"></a><a name="b527116451415"></a>dstInDiffTimeZone</strong>, <strong id="b0177125011119"><a name="b0177125011119"></a><a name="b0177125011119"></a>hasFerry</strong>, <strong id="b92558541818"><a name="b92558541818"></a><a name="b92558541818"></a>hasTrafficLight</strong>, <strong id="b1969385818116"><a name="b1969385818116"></a><a name="b1969385818116"></a>hasTolls</strong>, and <strong id="b3960941821"><a name="b3960941821"></a><a name="b3960941821"></a>trafficLightNum</strong> attributes to the <a href="en-us_topic_0000001145523549.md#s3f077a58ddb84eb49ab91635b0663f35">Route</a> object.</p>
</td>
</tr>
</table>

## Earlier Versions<a name="section185731027105216"></a>

### 5.1.1.300 \(2021-01-29\)<a name="section197526615243"></a>

<a name="simpletable87520622417"></a>
<table id="simpletable87520622417"><tr id="strow157521863241"><td valign="top" id="stentry975218682417"><p id="p1998473919119"><a name="p1998473919119"></a><a name="p1998473919119"></a>The feature updates for JavaScript API are as follows:</p>
<p id="p1575213622414"><a name="p1575213622414"></a><a name="p1575213622414"></a><strong id="b131068396598"><a name="b131068396598"></a><a name="b131068396598"></a>New Features</strong></p>
<p id="p16190193172414"><a name="p16190193172414"></a><a name="p16190193172414"></a>Added the <strong id="b4300910904"><a name="b4300910904"></a><a name="b4300910904"></a>sourceType</strong> parameter to <a href="en-us_topic_0000001145523545.md#s3c1e160316e8483783f2cd525f0c9c8e">MapOptions</a>, which is used to set the type of tiles loaded for the map. The options include <strong id="b82426132117"><a name="b82426132117"></a><a name="b82426132117"></a>vector</strong> and <strong id="b1566621517115"><a name="b1566621517115"></a><a name="b1566621517115"></a>raster</strong>.</p>
</td>
</tr>
</table>

### 5.1.0.300 \(2020-12-31\)<a name="section41141212193417"></a>

<a name="simpletable254010319355"></a>
<table id="simpletable254010319355"><tr id="strow7541103153518"><td valign="top" id="stentry135414383517"><p id="p2234162415110"><a name="p2234162415110"></a><a name="p2234162415110"></a>The feature updates for JavaScript API are as follows:</p>
<p id="p0664105543510"><a name="p0664105543510"></a><a name="p0664105543510"></a><strong id="b694915131616"><a name="b694915131616"></a><a name="b694915131616"></a>Modified Features</strong></p>
<p id="p20421443292"><a name="p20421443292"></a><a name="p20421443292"></a>Deprecated the <strong id="b970381710610"><a name="b970381710610"></a><a name="b970381710610"></a>politicalView</strong> parameter for <a href="en-us_topic_0000001098843524.md#s26c1dc4610cb42acbcc751478d3aea1d">Keyword Search</a>, <a href="en-us_topic_0000001098843524.md#sbfcaae7fd8e1436ab372b7ddd607ad84">Nearby Place Search</a>, <a href="en-us_topic_0000001098843524.md#sd8f8a5d5af4f41da93e178a4d7c5e3dc">Place Detail Search</a>, <a href="en-us_topic_0000001098843524.md#sce21dc95c5794bf6b17974848278c241">Place Search Suggestion</a>, <a href="en-us_topic_0000001098843510.md#saa4fb00052304977abb1e612fe52f664">Autocomplete</a>, <a href="en-us_topic_0000001098843524.md#s5127fd0562ca431b9b6204822619f6e0">Forward Geocoding</a>, and <a href="en-us_topic_0000001098843524.md#sdfae3d7270c041798e27911450c27d65">Reverse Geocoding</a>.</p>
</td>
</tr>
</table>

### 5.0.5.300 \(2020-11-27\)<a name="section137948182311"></a>

<a name="simpletable20376489231"></a>
<table id="simpletable20376489231"><tr id="strow938134852319"><td valign="top" id="stentry13815486239"><p id="p3490161618"><a name="p3490161618"></a><a name="p3490161618"></a>The feature updates for JavaScript API are as follows:</p>
<p id="p2381848132319"><a name="p2381848132319"></a><a name="p2381848132319"></a><strong id="b1571193713313"><a name="b1571193713313"></a><a name="b1571193713313"></a>New Features</strong></p>
<a name="ul138174810231"></a><a name="ul138174810231"></a><ul id="ul138174810231"><li>Added the legal copyright logo in the lower left corner of the sample image.</li><li>Modified the pricing policy to charge for the JavaScript APIs from January 1, 2021. For details, please refer to <a href="about-charging.md">Service Pricing</a>.</li></ul>
</td>
</tr>
</table>

### 5.0.2.300 \(2020-09-18\)<a name="section1293013818228"></a>

<a name="simpletable8930103842216"></a>
<table id="simpletable8930103842216"><tr id="strow17930138112215"><td valign="top" id="stentry6930183816222"><p id="p1766825320014"><a name="p1766825320014"></a><a name="p1766825320014"></a>The feature updates for JavaScript API are as follows:</p>
<p id="p49301338172218"><a name="p49301338172218"></a><a name="p49301338172218"></a><strong id="b14578322151113"><a name="b14578322151113"></a><a name="b14578322151113"></a>New Features</strong></p>
<a name="ul993073811226"></a><a name="ul993073811226"></a><ul id="ul993073811226"><li>Added the <a href="en-us_topic_0000001145723461.md">HWDistanceCalculator</a> API for calculating distance. </li><li>Added the <strong id="b198691062024"><a name="b198691062024"></a><a name="b198691062024"></a>maxHeight</strong>, <strong id="b129129228"><a name="b129129228"></a><a name="b129129228"></a>data</strong>, and <strong id="b2066731113218"><a name="b2066731113218"></a><a name="b2066731113218"></a>customHandler</strong> parameters to the <a href="en-us_topic_0000001098843510.md#saa4fb00052304977abb1e612fe52f664">AutocompleteOptions</a> object, which are used to customize the style.</li></ul>
</td>
</tr>
</table>

### 5.0.1.300 \(2020-07-13\)<a name="section1230951612514"></a>

<a name="simpletable33091516152518"></a>
<table id="simpletable33091516152518"><tr id="strow53091016112512"><td valign="top" id="stentry8309416152514"><p id="p205114423010"><a name="p205114423010"></a><a name="p205114423010"></a>The feature updates for JavaScript API are as follows:</p>
<p id="p103091616192517"><a name="p103091616192517"></a><a name="p103091616192517"></a><strong id="b10982152712206"><a name="b10982152712206"></a><a name="b10982152712206"></a>New Features</strong></p>
<p id="p16309181617256"><a name="p16309181617256"></a><a name="p16309181617256"></a>Added the function of seamlessly adjusting the map scale through gestures on Web JavaScript clients.</p>
</td>
</tr>
</table>

### 4.0.4.300 \(2020-05-25\)<a name="section177811737194015"></a>

<a name="simpletable152451705119"></a>
<table id="simpletable152451705119"><tr id="strow132459014110"><td valign="top" id="stentry6245301112"><p id="p93097321806"><a name="p93097321806"></a><a name="p93097321806"></a>The feature updates for JavaScript API are as follows:</p>
<p id="p520613684119"><a name="p520613684119"></a><a name="p520613684119"></a><strong id="b1513013558224"><a name="b1513013558224"></a><a name="b1513013558224"></a>New Features</strong></p>
<a name="ul20146255113"></a><a name="ul20146255113"></a><ul id="ul20146255113"><li>Added the <strong id="b87322014142310"><a name="b87322014142310"></a><a name="b87322014142310"></a>strokeLineDash</strong> attribute for <a href="en-us_topic_0000001145723431.md">HWCircle</a>, <a href="en-us_topic_0000001099163514.md">HWPolyline</a>, and <a href="en-us_topic_0000001145723447.md">HWPolygon</a>.</li><li>Added the location button as a map control.</li><li>Added the function to customize the map style.</li></ul>
</td>
</tr>
</table>

### 4.0.3.300 \(2020-03-27\)<a name="section3117143172416"></a>

<a name="simpletable181171743132413"></a>
<table id="simpletable181171743132413"><tr id="strow181172431243"><td valign="top" id="stentry16117943192411"><p id="p2051110171209"><a name="p2051110171209"></a><a name="p2051110171209"></a>The feature updates for JavaScript API are as follows:</p>
<p id="p179061430182418"><a name="p179061430182418"></a><a name="p179061430182418"></a><strong id="b1255582915120"><a name="b1255582915120"></a><a name="b1255582915120"></a>New Features</strong></p>
<a name="ul090617300240"></a><a name="ul090617300240"></a><ul id="ul090617300240"><li>Added Distance Matrix to calculate route distances between multiple departure places and destinations and traveling duration required for each route.</li><li>Added the current location control, and supported display of the current location.</li><li>Added the <strong id="b19235125518"><a name="b19235125518"></a><a name="b19235125518"></a>distanceText</strong> and <strong id="b125021741757"><a name="b125021741757"></a><a name="b125021741757"></a>durationText</strong> attributes for the <a href="en-us_topic_0000001145523549.md#s8f3c15d7935d43cba758ef721d678cef">Path</a> and <a href="en-us_topic_0000001145523549.md#sb52779383eab45b990b2ec23c9541eb5">Step</a> objects to provide tips on traveling distance and duration. </li><li>Added the <strong id="b1121717132064"><a name="b1121717132064"></a><a name="b1121717132064"></a>durationInTrafficText</strong> attribute for the <a href="en-us_topic_0000001145523549.md#s8f3c15d7935d43cba758ef721d678cef">Path</a> object to provide tips on traveling duration calculated based on real-time traffic status.</li><li>Added the <strong id="b18036301178"><a name="b18036301178"></a><a name="b18036301178"></a>instruction</strong> attribute for the <a href="en-us_topic_0000001145523549.md#sb52779383eab45b990b2ec23c9541eb5">Step</a> object to provide tips on steps.</li></ul>
</td>
</tr>
</table>

### 4.0.2.300 \(2020-03-12\)<a name="section4293173412246"></a>

<a name="simpletable829483410245"></a>
<table id="simpletable829483410245"><tr id="strow4294183482411"><td valign="top" id="stentry132941934152410"><p id="p1599233818598"><a name="p1599233818598"></a><a name="p1599233818598"></a>The feature updates for JavaScript API are as follows:</p>
<p id="p4665144213539"><a name="p4665144213539"></a><a name="p4665144213539"></a><strong id="b196141251674"><a name="b196141251674"></a><a name="b196141251674"></a>New Features</strong></p>
<a name="ul1166534215533"></a><a name="ul1166534215533"></a><ul id="ul1166534215533"><li>Added the <strong id="b16493143414814"><a name="b16493143414814"></a><a name="b16493143414814"></a>searchByText</strong> method in the <a href="en-us_topic_0000001098843524.md">HWSiteService</a> class to search for places by keyword.</li><li>Added the <strong id="b14458041783"><a name="b14458041783"></a><a name="b14458041783"></a>nearbySearch</strong> method in the <a href="en-us_topic_0000001098843524.md">HWSiteService</a> class to search for nearby places.</li><li>Added the <strong id="b57201071596"><a name="b57201071596"></a><a name="b57201071596"></a>searchById</strong> method in the <a href="en-us_topic_0000001098843524.md">HWSiteService</a> class to query address of a place based on the place ID.</li><li>Added the <strong id="b13567191671012"><a name="b13567191671012"></a><a name="b13567191671012"></a>querySuggestion</strong> method in the <a href="en-us_topic_0000001098843524.md">HWSiteService</a> class to provide place search suggestions.</li><li>Supported preset standard map styles.</li></ul>
</td>
</tr>
</table>

### 4.0.1.300 \(2020-01-21\)<a name="section10201151052417"></a>

<a name="simpletable5201171072417"></a>
<table id="simpletable5201171072417"><tr id="strow12201131018249"><td valign="top" id="stentry192011910112414"><p id="p14506410171314"><a name="p14506410171314"></a><a name="p14506410171314"></a>The feature updates for JavaScript API are as follows:</p>
<p id="p196631337173914"><a name="p196631337173914"></a><a name="p196631337173914"></a><strong id="b1820313618217"><a name="b1820313618217"></a><a name="b1820313618217"></a>New Features</strong></p>
<a name="ul3663133713912"></a><a name="ul3663133713912"></a><ul id="ul3663133713912"><li>Supported authentication based on the API key and service account, and changed the authentication credential from the access token to the API key for the Web APIs.</li><li>Supported mouse and gesture actions. </li><li>Added the <a href="en-us_topic_0000001145523533.md">Marker</a> class to allow you to add markers on the map.</li><li>Added the <a href="en-us_topic_0000001099163498.md">GroundOverlay</a> class to display images based on Bbox and automatically pad the overlay.</li><li>Added the function to plan (walking, cycling, and driving) routes. Before using route planning capabilities of JavaScript APIs in your project, you need to enable Directions APIs for the project. </li></ul>
</td>
</tr>
</table>

### 4.0.0.300 \(2019-12-30\)<a name="section27214573129"></a>

<a name="simpletable472114571122"></a>
<table id="simpletable472114571122"><tr id="strow117217576128"><td valign="top" id="stentry17211573122"><p id="p1624581311315"><a name="p1624581311315"></a><a name="p1624581311315"></a>The feature updates for JavaScript API are as follows:</p>
<p id="p2394357193"><a name="p2394357193"></a><a name="p2394357193"></a><strong id="b186982195228"><a name="b186982195228"></a><a name="b186982195228"></a>New Features</strong></p>
<p id="p106535772118"><a name="p106535772118"></a><a name="p106535772118"></a>Provided JavaScript APIs for you to easily build map apps applicable to browsers. Supported basic map display, map drawing, and map interaction.</p>
</td>
</tr>
</table>

