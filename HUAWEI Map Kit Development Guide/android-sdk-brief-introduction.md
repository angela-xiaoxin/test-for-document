# Service Introduction<a name="EN-US_TOPIC_0000001099003588"></a>

-   [Supported Devices](#section1261123620147)
-   [Use Cases](#section2827122911617)
-   [Function Restrictions](#section1425318477373)

<a name="table89171544191517"></a>
<table><tbody><tr id="row991874471518"><td class="row-nocellborder" style="border:none" valign="top" width="50%"><p id="p94161111201616"><a name="p94161111201616"></a><a name="p94161111201616"></a>Map Kit is an SDK for map development. It covers map data of more than 200 countries and regions, and supports over one hundred of languages. With this SDK, you can easily integrate map-based functions into your apps.</p>
<p id="p23501621184414"><a name="p23501621184414"></a><a name="p23501621184414"></a>The demo video introduces functions, service scenarios, and advantages of Map Kit. Through this video, you will learn how to use Map Kit to realize personalized map display and interaction in your app.</p>
<p id="p59361023111612"><a name="p59361023111612"></a><a name="p59361023111612"></a>You can click <a href="https://developer.huawei.com/consumer/en/training/detail/201575277450653242" target="_blank" rel="noopener noreferrer">here</a> to watch the MOOC video about Map Kit.</p>
</td>
<td class="cellrowborder" style="border:none" valign="top" width="50%"><p id="p5936152381613"><a name="p5936152381613"></a><a name="p5936152381613"></a></p>
<p id="p351513112164"><a name="p351513112164"></a><a name="p351513112164"></a><a href="https://mos-vod-drcn.dbankcdn.cn/P_VT/video_cutover/14/v3/4F68F2AE351767327559169024/276718473.mp4">https://mos-vod-drcn.dbankcdn.cn/P_VT/video_cutover/14/v3/4F68F2AE351767327559169024/276718473.mp4</a></p>
</td>
</tr>
</tbody>
</table>

In addition, Map Kit continuously optimizes and enriches the map detail display capability. For example, Map Kit can clearly show green fields and vegetation information in a small scale. It can also display most suitable POIs and road network information in different scales based on the POI attributes and regional road network differences. Map Kit supports gestures including zoom, rotation, moving, and tilt gestures to ensure smooth interaction experience.

## Supported Devices<a name="section1261123620147"></a>

<a name="table12611103641414"></a>
<table><thead align="left"><tr id="row2061163618149"><th class="cellrowborder" valign="top" width="33.33333333333333%" id="mcps1.1.4.1.1"><p id="p5611636161410"><a name="p5611636161410"></a><a name="p5611636161410"></a>Device Type</p>
</th>
<th class="cellrowborder" valign="top" width="33.33333333333333%" id="mcps1.1.4.1.2"><p id="p14611936201414"><a name="p14611936201414"></a><a name="p14611936201414"></a>OS Version</p>
</th>
<th class="cellrowborder" valign="top" width="33.33333333333333%" id="mcps1.1.4.1.3"><p id="p16611136191416"><a name="p16611136191416"></a><a name="p16611136191416"></a>HMS Core (APK) Version</p>
</th>
</tr>
</thead>
<tbody><tr id="row206118362142"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p3611163621413"><a name="p3611163621413"></a><a name="p3611163621413"></a>Huawei phone and tablet</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p3612103621415"><a name="p3612103621415"></a><a name="p3612103621415"></a>EMUI 5.0 or later</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p8612036131410"><a name="p8612036131410"></a><a name="p8612036131410"></a>4.0.0 or later</p>
</td>
</tr>
<tr id="row961263611412"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p13612153651412"><a name="p13612153651412"></a><a name="p13612153651412"></a>Non-Huawei Android phone</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p1661283691412"><a name="p1661283691412"></a><a name="p1661283691412"></a>Android 7.0 or later</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p66127366140"><a name="p66127366140"></a><a name="p66127366140"></a>5.1.0 or later</p>
</td>
</tr>
</tbody>
</table>

>![](public_sys-resources/icon-note.gif) **NOTE:** 
>To use Map Kit independent of HMS Core \(APK\), you need to  [add dependencies on fallbacks](android-sdk-integrating-sdk.md#section926020288361).

## Use Cases<a name="section2827122911617"></a>

Map Kit uses the WGS 84 GPS coordinate system, which meets most map development requirements outside the Chinese mainland, including:

-   Map display: Displays buildings, roads, water systems, and Points of Interest \(POIs\).
-   Map interaction: Controls the interaction gestures and buttons on the map.
-   Map drawing: Adds location markers, map layers, overlays, and various shapes.

## Function Restrictions<a name="section1425318477373"></a>

<a name="table13395173564216"></a>
<table><thead align="left"><tr id="row839618353424"><th class="cellrowborder" valign="top" width="30%" id="mcps1.1.4.1.1"><p id="p1439623512424"><a name="p1439623512424"></a><a name="p1439623512424"></a>Function</p>
</th>
<th class="cellrowborder" valign="top" width="30%" id="mcps1.1.4.1.2"><p id="p152545386535"><a name="p152545386535"></a><a name="p152545386535"></a>Location Restriction</p>
</th>
<th class="cellrowborder" valign="top" width="40%" id="mcps1.1.4.1.3"><p id="p1739610359423"><a name="p1739610359423"></a><a name="p1739610359423"></a>Remarks</p>
</th>
</tr>
</thead>
<tbody><tr id="row1939723514219"><td class="cellrowborder" valign="top" width="30%" headers="mcps1.1.4.1.1 "><p id="p1059713475444"><a name="p1059713475444"></a><a name="p1059713475444"></a>Functions relevant to map data, such as map data loading</p>
</td>
<td class="cellrowborder" valign="top" width="30%" headers="mcps1.1.4.1.2 "><p id="p92541438185311"><a name="p92541438185311"></a><a name="p92541438185311"></a>Not supported in the Chinese mainland</p>
</td>
<td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.4.1.3 "><p id="p0397123584215"><a name="p0397123584215"></a><a name="p0397123584215"></a>No data of the Chinese mainland is available for these functions, such as map data loading and route planning.</p>
</td>
</tr>
<tr id="row439713350421"><td class="cellrowborder" valign="top" width="30%" headers="mcps1.1.4.1.1 "><p id="p115983477444"><a name="p115983477444"></a><a name="p115983477444"></a>Functions irrelevant to map data</p>
</td>
<td class="cellrowborder" valign="top" width="30%" headers="mcps1.1.4.1.2 "><p id="p1125463845319"><a name="p1125463845319"></a><a name="p1125463845319"></a>None</p>
</td>
<td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.4.1.3 "><p id="p93981435174218"><a name="p93981435174218"></a><a name="p93981435174218"></a>All functions irrelevant to map data are available, such as the functions of adding markers and polygons.</p>
</td>
</tr>
</tbody>
</table>

