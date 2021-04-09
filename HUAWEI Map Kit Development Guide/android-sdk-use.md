# Getting Started<a name="EN-US_TOPIC_0000001145843441"></a>

-   [Quick Tutorial](#section8992121481312)
-   [Development Environment](#sc50cac42cc41439fbe42214051156d67)
-   [Development Process](#section18946774278)

## Quick Tutorial<a name="section8992121481312"></a>

Before developing your app, you can follow instructions in the  [codelab](https://developer.huawei.com/consumer/en/codelab/HMSMapKit/index.html#0)  to experience how to quickly integrate Map Kit into an app. Through the codelab, you will learn how to:

-   Configure app information in AppGallery Connect.
-   Obtain the sample code demo app of Map Kit on HUAWEI Developers.
-   Use Android Studio to integrate the Map SDK into the app and develop map-related functions.
-   Build and demonstrate a demo map.

## Development Environment<a name="sc50cac42cc41439fbe42214051156d67"></a>

-   Android Studio version: 3.3 or later

-   JDK version: 1.8 or later
-   SDK and Gradle:

    -   minSdkVersion: 19
    -   targetSdkVersion: 29
    -   compileSdkVersion: 29
    -   Gradle version: 3.5.3 or later

-   Test device: a Huawei phone running EMUI 5.0 or later, or a non-Huawei phone running Android 7.0 or later


## Development Process<a name="section18946774278"></a>

Follow the steps in the following process when you develop an app.

<a name="table4122153120269"></a>
<table><thead align="left"><tr id="row15305163112618"><th class="cellrowborder" align="center" valign="top" width="6.28062806280628%" id="mcps1.1.4.1.1"><p id="p19280142664212"><a name="p19280142664212"></a><a name="p19280142664212"></a>No.</p>
</th>
<th class="cellrowborder" valign="top" width="22.302230223022303%" id="mcps1.1.4.1.2"><p id="p830511312266"><a name="p830511312266"></a><a name="p830511312266"></a>Step</p>
</th>
<th class="cellrowborder" valign="top" width="71.41714171417142%" id="mcps1.1.4.1.3"><p id="p103051631192618"><a name="p103051631192618"></a><a name="p103051631192618"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row103051431182612"><td class="cellrowborder" align="center" valign="top" width="6.28062806280628%" headers="mcps1.1.4.1.1 "><p id="p1483673810243"><a name="p1483673810243"></a><a name="p1483673810243"></a>1</p>
</td>
<td class="cellrowborder" valign="top" width="22.302230223022303%" headers="mcps1.1.4.1.2 "><p id="p27011313104416"><a name="p27011313104416"></a><a name="p27011313104416"></a><a href="android-sdk-config-agc.md">Configuring App Information in AppGallery Connect</a></p>
</td>
<td class="cellrowborder" valign="top" width="71.41714171417142%" headers="mcps1.1.4.1.3 "><p id="p1483220153314"><a name="p1483220153314"></a><a name="p1483220153314"></a>Configure app information in <a href="https://developer.huawei.com/consumer/en/service/josp/agc/index.html" target="_blank" rel="noopener noreferrer">AppGallery Connect</a>, including <a href="android-sdk-config-agc.md#section47264296">Registering as a Developer</a>, <a href="android-sdk-config-agc.md#section83893131911">Creating a Project</a>, <a href="android-sdk-config-agc.md#section0592162815915">Creating an App</a>, <a href="android-sdk-config-agc.md#section147011294331">Generating a Signing Certificate Fingerprint</a>, <a href="android-sdk-config-agc.md#section4972271336">Configuring the Signing Certificate Fingerprint</a>, and <a href="android-sdk-config-agc.md#section58097464">Enabling Required Services</a>.</p>
</td>
</tr>
<tr id="row1730663162618"><td class="cellrowborder" align="center" valign="top" width="6.28062806280628%" headers="mcps1.1.4.1.1 "><p id="p683543822413"><a name="p683543822413"></a><a name="p683543822413"></a>2</p>
</td>
<td class="cellrowborder" valign="top" width="22.302230223022303%" headers="mcps1.1.4.1.2 "><p id="p530693118266"><a name="p530693118266"></a><a name="p530693118266"></a><a href="android-sdk-integrating-sdk.md">Integrating the HMS Core SDK</a></p>
</td>
<td class="cellrowborder" valign="top" width="71.41714171417142%" headers="mcps1.1.4.1.3 "><p id="p17184513165"><a name="p17184513165"></a><a name="p17184513165"></a>Integrate the HMS Core SDK into your app.</p>
</td>
</tr>
<tr id="row215818418196"><td class="cellrowborder" align="center" valign="top" width="6.28062806280628%" headers="mcps1.1.4.1.1 "><p id="p13834938192418"><a name="p13834938192418"></a><a name="p13834938192418"></a>3</p>
</td>
<td class="cellrowborder" valign="top" width="22.302230223022303%" headers="mcps1.1.4.1.2 "><p id="p161581145192"><a name="p161581145192"></a><a name="p161581145192"></a><a href="android-sdk-config-obfuscation-scripts.md">Configuring Obfuscation Scripts</a></p>
</td>
<td class="cellrowborder" valign="top" width="71.41714171417142%" headers="mcps1.1.4.1.3 "><p id="p415816401912"><a name="p415816401912"></a><a name="p415816401912"></a>Before building the APK, configure the obfuscation configuration file to prevent the HMS Core SDK from being obfuscated.</p>
</td>
</tr>
<tr id="row14808202071911"><td class="cellrowborder" rowspan="4" align="center" valign="top" width="6.28062806280628%" headers="mcps1.1.4.1.1 "><p id="p1315711211110"><a name="p1315711211110"></a><a name="p1315711211110"></a>4</p>
</td>
<td class="cellrowborder" valign="top" width="22.302230223022303%" headers="mcps1.1.4.1.2 "><p id="p149471455191912"><a name="p149471455191912"></a><a name="p149471455191912"></a><a href="android-sdk-map-creation-overview.md">Map Creation</a></p>
</td>
<td class="cellrowborder" valign="top" width="71.41714171417142%" headers="mcps1.1.4.1.3 "><p id="p133911750181919"><a name="p133911750181919"></a><a name="p133911750181919"></a>Use a map container to quickly obtain a map object, change the map type, display the my-location icon on the map, and enable the map's lite mode.</p>
</td>
</tr>
<tr id="row734019881617"><td class="cellrowborder" valign="top" headers="mcps1.1.4.1.1 "><p id="p1534116891612"><a name="p1534116891612"></a><a name="p1534116891612"></a><a href="android-sdk-map-interaction-overview.md">Map Interaction</a></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.4.1.2 "><p id="p19341280165"><a name="p19341280165"></a><a name="p19341280165"></a>Control the built-in UI control display and allowable gestures to customize modes for users to interact with the map.</p>
</td>
</tr>
<tr id="row13302593166"><td class="cellrowborder" valign="top" headers="mcps1.1.4.1.1 "><p id="p16302794162"><a name="p16302794162"></a><a name="p16302794162"></a><a href="android-sdk-drawing-map-overview.md">Drawing on a Map</a></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.4.1.2 "><p id="p230209131615"><a name="p230209131615"></a><a name="p230209131615"></a>Draw markers, overlays, and shapes on the map.</p>
</td>
</tr>
<tr id="row17240217151612"><td class="cellrowborder" valign="top" headers="mcps1.1.4.1.1 "><p id="p15241717191617"><a name="p15241717191617"></a><a name="p15241717191617"></a><a href="android-sdk-map-style-customization-overview.md">Map Style Customization</a></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.4.1.2 "><p id="p42411117141614"><a name="p42411117141614"></a><a name="p42411117141614"></a>Add a custom map to your app.</p>
</td>
</tr>
<tr id="row067021715166"><td class="cellrowborder" align="center" valign="top" width="6.28062806280628%" headers="mcps1.1.4.1.1 "><p id="p1670717111616"><a name="p1670717111616"></a><a name="p1670717111616"></a>5</p>
</td>
<td class="cellrowborder" valign="top" width="22.302230223022303%" headers="mcps1.1.4.1.2 "><p id="p146701617101612"><a name="p146701617101612"></a><a name="p146701617101612"></a><a href="google-maps-to-map-kit.md">Migration From Google Maps to HUAWEI Map Kit</a></p>
</td>
<td class="cellrowborder" valign="top" width="71.41714171417142%" headers="mcps1.1.4.1.3 "><p id="p1167015173169"><a name="p1167015173169"></a><a name="p1167015173169"></a>Migrate the Google Maps SDK for Android to the HMS Core Map SDK for Android in your Android app, starting with basic environment settings.</p>
</td>
</tr>
<tr id="row14390150111916"><td class="cellrowborder" align="center" valign="top" width="6.28062806280628%" headers="mcps1.1.4.1.1 "><p id="p1983273816248"><a name="p1983273816248"></a><a name="p1983273816248"></a>6</p>
</td>
<td class="cellrowborder" valign="top" width="22.302230223022303%" headers="mcps1.1.4.1.2 "><p id="p2306133132615"><a name="p2306133132615"></a><a name="p2306133132615"></a><a href="pre-release-check.md">Pre-release Check</a></p>
</td>
<td class="cellrowborder" valign="top" width="71.41714171417142%" headers="mcps1.1.4.1.3 "><p id="p1130619315263"><a name="p1130619315263"></a><a name="p1130619315263"></a>Use the tool offered by Huawei to automatically check your app before release.</p>
</td>
</tr>
<tr id="row930610316269"><td class="cellrowborder" align="center" valign="top" width="6.28062806280628%" headers="mcps1.1.4.1.1 "><p id="p1831133882417"><a name="p1831133882417"></a><a name="p1831133882417"></a>7</p>
</td>
<td class="cellrowborder" valign="top" width="22.302230223022303%" headers="mcps1.1.4.1.2 "><p id="p5306123192610"><a name="p5306123192610"></a><a name="p5306123192610"></a><a href="app-release.md">App Release</a></p>
</td>
<td class="cellrowborder" valign="top" width="71.41714171417142%" headers="mcps1.1.4.1.3 "><p id="p0306123115265"><a name="p0306123115265"></a><a name="p0306123115265"></a>Complete your app information in <a href="https://developer.huawei.com/consumer/en/service/josp/agc/index.html" target="_blank" rel="noopener noreferrer">AppGallery Connect</a>, and submit your app for release.</p>
</td>
</tr>
</tbody>
</table>

If your app has integrated third-party mobile services, you can use Convertor in  [HMS Toolkit](https://developer.huawei.com/consumer/en/huawei-toolkit/)  to convert their APIs into HMS APIs so that you can quickly access the HMS Core capabilities. 

