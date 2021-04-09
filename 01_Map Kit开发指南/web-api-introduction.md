# 业务简介<a name="ZH-CN_TOPIC_0000001145541087"></a>

-   [Directions API](#section160152955116)
-   [Matrix API](#section61061048195215)
-   [Maps Static API](#section193266447536)
-   [Tile API](#section13215144920533)
-   [场景介绍](#section2827122911617)
-   [功能使用限制](#section1425318477373)

地图服务以HTTP/HTTPS形式为第三方开发者提供了API，您可以通过这些接口使用地图数据服务，用于开发路径规划、静态图、栅格图等相关功能。在API被调用时，相关数据通过JSON格式返回。

服务使用前，需要您先[获取API Key](web-api-preparations.md#section169441820428)。

使用路径规划服务时，请确保您规划的路径所在国家均在路径规划所支持的国家/地区内，请参见[支持的国家/地区（路径规划）](supported-countries-and-regions-route-planning.md)。

## Directions API<a name="section160152955116"></a>

路径规划API是一套以HTTPS形式提供的步行、骑行、驾车路径规划以及行驶距离计算接口，通过JSON格式返回路径查询数据，提供路径规划能力。

路径规划具体提供如下功能：

-   **步行路径规划**

    步行路径规划API提供150km以内的步行路径规划能力。


-   **骑行路径规划**

    骑行路径规划API提供100km以内的骑行路径规划能力。


-   **驾车路径规划**

    驾车路径规划API提供驾车路径规划能力，支持以下功能：

    -   支持一次请求返回多条路线，最多支持3条路线。
    -   最多支持5个途经点。
    -   支持未来出行规划。
    -   支持根据实时路况进行合理路线规划。


## Matrix API<a name="section61061048195215"></a>

提供一次计算多组起点和目的地的路线距离和时间计算功能，包括步行，骑行及驾车三种模式。

-   **步行路径规划**

    提供150km以内的步行路径规划能力。

-   **骑行路径规划**

    提供100km以内的骑行路径规划能力。

-   **驾车路径规划**

    提供驾车路径规划能力。


## Maps Static API<a name="section193266447536"></a>

Maps Static API服务通过HTTP请求发送的URL参数创建地图，并将地图作为可以在网页上显示的图像返回。

本服务具有支持您自定义生成指定区域、附加指定信息的单一成品渲染图的能力。接口返回一张实时渲染的图片，您可以指定请求的地图位置、图片大小、以及在地图上添加覆盖物，如标签、折线、多边形。

## Tile API<a name="section13215144920533"></a>

Tile API服务通过HTTP请求发送的URL参数允许您直接访问华为地图瓦片数据。通过请求独立的地图瓦片，构建一个地图图层，使得地图可以方便的加载到已有的地图平台中。例如在PC端将瓦片加载到QGIS，Arcgis上；在移动应用中以tile overlay形式加载到已有的地图上。

## 场景介绍<a name="section2827122911617"></a>

<a name="table8957161316424"></a>
<table><thead align="left"><tr id="row895791316422"><th class="cellrowborder" valign="top" width="25%" id="mcps1.1.3.1.1"><p id="p17957913154219"><a name="p17957913154219"></a><a name="p17957913154219"></a>场景分类</p>
</th>
<th class="cellrowborder" valign="top" width="75%" id="mcps1.1.3.1.2"><p id="p29571913134212"><a name="p29571913134212"></a><a name="p29571913134212"></a>场景说明</p>
</th>
</tr>
</thead>
<tbody><tr id="row731914131394"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.3.1.1 "><p id="p1231915131591"><a name="p1231915131591"></a><a name="p1231915131591"></a>Directions API</p>
</td>
<td class="cellrowborder" valign="top" width="75%" headers="mcps1.1.3.1.2 "><p id="p1831911314917"><a name="p1831911314917"></a><a name="p1831911314917"></a>提供步行、骑行、驾车三种交通方式的两点之间路径规划能力。计算路线时，API返回最有效路线。</p>
</td>
</tr>
<tr id="row3903113199"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.3.1.1 "><p id="p1290341312914"><a name="p1290341312914"></a><a name="p1290341312914"></a>Matrix API</p>
</td>
<td class="cellrowborder" valign="top" width="75%" headers="mcps1.1.3.1.2 "><p id="p990313132914"><a name="p990313132914"></a><a name="p990313132914"></a>提供步行、骑行、驾车三种交通方式的多点之间路径规划能力。计算多个点之间的路线距离和时间。</p>
</td>
</tr>
<tr id="row1979814161093"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.3.1.1 "><p id="p779812164915"><a name="p779812164915"></a><a name="p779812164915"></a>Maps Static API</p>
</td>
<td class="cellrowborder" valign="top" width="75%" headers="mcps1.1.3.1.2 "><p id="p67983161598"><a name="p67983161598"></a><a name="p67983161598"></a>通过HTTP请求发送的URL参数创建地图图片并直接嵌入到网页中，而无需通过JavaScript或动态页面加载。</p>
</td>
</tr>
<tr id="row52161317299"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.3.1.1 "><p id="p1821651712914"><a name="p1821651712914"></a><a name="p1821651712914"></a>Tile API</p>
</td>
<td class="cellrowborder" valign="top" width="75%" headers="mcps1.1.3.1.2 "><a name="ul5360115911015"></a><a name="ul5360115911015"></a><ul id="ul5360115911015"><li>在PC端将瓦片加载到QGIS，Arcgis上。</li><li>在移动应用中以tile overlay形式加载到已有的地图上。</li></ul>
</td>
</tr>
</tbody>
</table>

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
<tbody><tr id="row1939723514219"><td class="cellrowborder" valign="top" width="30%" headers="mcps1.1.4.1.1 "><p id="p1059713475444"><a name="p1059713475444"></a><a name="p1059713475444"></a>地图加载等涉及数据的功能</p>
</td>
<td class="cellrowborder" valign="top" width="30%" headers="mcps1.1.4.1.2 "><p id="p92541438185311"><a name="p92541438185311"></a><a name="p92541438185311"></a>不支持中国大陆</p>
</td>
<td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.4.1.3 "><p id="p0397123584215"><a name="p0397123584215"></a><a name="p0397123584215"></a>无中国大陆数据，例如地图加载，路径规划等</p>
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

