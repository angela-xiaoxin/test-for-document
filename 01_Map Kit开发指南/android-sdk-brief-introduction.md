# 业务简介<a name="ZH-CN_TOPIC_0000001099341102"></a>

-   [支持的设备](#section1261123620147)
-   [场景介绍](#section2827122911617)
-   [功能使用限制](#section1425318477373)

<a name="table89171544191517"></a>
<table><tbody><tr id="row991874471518"><td class="row-nocellborder" style="border:none" valign="top" width="50%"><p id="p94161111201616"><a name="p94161111201616"></a><a name="p94161111201616"></a>地图服务（Map Kit）给您提供一套地图开发调用的SDK，地图数据覆盖超过200个国家和地区，支持一百多种语言，方便您轻松地在应用中集成地图相关的功能，全方位提升用户体验。</p>
<p id="p23501621184414"><a name="p23501621184414"></a><a name="p23501621184414"></a>本视频课程介绍了Map Kit的功能、服务场景、优势等内容。通过学习本课程，您将了解如何使用地图服务实现个性化地图呈现和交互。</p>
<p id="p59361023111612"><a name="p59361023111612"></a><a name="p59361023111612"></a>更多视频请观看：<a href="https://developer.huawei.com/consumer/cn/training/" target="_blank" rel="noopener noreferrer">华为开发者学院</a> -&gt; <a href="https://developer.huawei.com/consumer/cn/training/detail/201575444281962387" target="_blank" rel="noopener noreferrer">HMS Core精品实战课</a>。</p>
</td>
<td class="cellrowborder" style="border:none" valign="top" width="50%"><p id="p5936152381613"><a name="p5936152381613"></a><a name="p5936152381613"></a><a href="https://mos-vod-drcn.dbankcdn.cn/P_VT/video_cutover/5B/v3/041EF521351574954996679680/276770409.mp4">https://mos-vod-drcn.dbankcdn.cn/P_VT/video_cutover/5B/v3/041EF521351574954996679680/276770409.mp4</a></p>
<p id="p351513112164"><a name="p351513112164"></a><a name="p351513112164"></a></p>
</td>
</tr>
</tbody>
</table>

Map Kit不断优化丰富地图的细节呈现能力，例如在小比例尺展示情况下，能够清晰的看到绿地和植被信息；在POI和路网信息展示方面，根据POI属性信息及区域路网差异，在不同层级比例尺条件下，为用户展示更合适的POI和路网信息。手势交互方面，提供了包括缩放、旋转、移动、倾斜等流畅的交互体验。

## 支持的设备<a name="section1261123620147"></a>

<a name="table12611103641414"></a>
<table><thead align="left"><tr id="row2061163618149"><th class="cellrowborder" valign="top" width="33.33333333333333%" id="mcps1.1.4.1.1"><p id="p5611636161410"><a name="p5611636161410"></a><a name="p5611636161410"></a>设备类型</p>
</th>
<th class="cellrowborder" valign="top" width="33.33333333333333%" id="mcps1.1.4.1.2"><p id="p14611936201414"><a name="p14611936201414"></a><a name="p14611936201414"></a>支持版本</p>
</th>
<th class="cellrowborder" valign="top" width="33.33333333333333%" id="mcps1.1.4.1.3"><p id="p16611136191416"><a name="p16611136191416"></a><a name="p16611136191416"></a>HMS Core（APK）版本</p>
</th>
</tr>
</thead>
<tbody><tr id="row206118362142"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p3611163621413"><a name="p3611163621413"></a><a name="p3611163621413"></a>华为手机，华为平板</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p3612103621415"><a name="p3612103621415"></a><a name="p3612103621415"></a>EMUI 5.0及以上</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p8612036131410"><a name="p8612036131410"></a><a name="p8612036131410"></a>4.0.0及以上</p>
</td>
</tr>
<tr id="row961263611412"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p13612153651412"><a name="p13612153651412"></a><a name="p13612153651412"></a>非华为Android手机</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p1661283691412"><a name="p1661283691412"></a><a name="p1661283691412"></a>Android 7.0及以上</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p66127366140"><a name="p66127366140"></a><a name="p66127366140"></a>5.1.0及以上</p>
</td>
</tr>
</tbody>
</table>

>![](public_sys-resources/icon-note.gif) **说明：** 
>如果您想不依赖HMS Core（APK）使用地图服务，需要[添加fallback依赖](android-sdk-integrating-sdk.md#section926020288361)。

## 场景介绍<a name="section2827122911617"></a>

地图采用WGS84 GPS坐标系，满足绝大多数海外地图开发的需求，包括：

-   地图呈现：呈现内容包括建筑，道路，水系，兴趣点等。
-   地图交互：控制地图的交互手势和交互按钮。
-   地图绘制：添加位置标记，图层，覆盖物以及各种形状等。

## 功能使用限制<a name="section1425318477373"></a>

<a name="table13395173564216"></a>
<table><thead align="left"><tr id="row839618353424"><th class="cellrowborder" valign="top" width="30%" id="mcps1.1.4.1.1"><p id="p1439623512424"><a name="p1439623512424"></a><a name="p1439623512424"></a>功能</p>
</th>
<th class="cellrowborder" valign="top" width="30%" id="mcps1.1.4.1.2"><p id="p152545386535"><a name="p152545386535"></a><a name="p152545386535"></a>地域要求</p>
</th>
<th class="cellrowborder" valign="top" width="40%" id="mcps1.1.4.1.3"><p id="p1739610359423"><a name="p1739610359423"></a><a name="p1739610359423"></a>说明</p>
</th>
</tr>
</thead>
<tbody><tr id="row1939723514219"><td class="cellrowborder" valign="top" width="30%" headers="mcps1.1.4.1.1 "><p id="p1059713475444"><a name="p1059713475444"></a><a name="p1059713475444"></a>地图数据加载等涉及数据的功能</p>
</td>
<td class="cellrowborder" valign="top" width="30%" headers="mcps1.1.4.1.2 "><p id="p92541438185311"><a name="p92541438185311"></a><a name="p92541438185311"></a>不支持中国大陆</p>
</td>
<td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.4.1.3 "><p id="p0397123584215"><a name="p0397123584215"></a><a name="p0397123584215"></a>无中国大陆数据，例如地图数据加载，路径规划等</p>
</td>
</tr>
<tr id="row439713350421"><td class="cellrowborder" valign="top" width="30%" headers="mcps1.1.4.1.1 "><p id="p115983477444"><a name="p115983477444"></a><a name="p115983477444"></a>不涉及数据的功能</p>
</td>
<td class="cellrowborder" valign="top" width="30%" headers="mcps1.1.4.1.2 "><p id="p1125463845319"><a name="p1125463845319"></a><a name="p1125463845319"></a>无</p>
</td>
<td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.4.1.3 "><p id="p93981435174218"><a name="p93981435174218"></a><a name="p93981435174218"></a>不涉及数据的功能，例如添加标记，多边形等都可以使用</p>
</td>
</tr>
</tbody>
</table>

