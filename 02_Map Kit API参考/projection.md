# Projection<a name="ZH-CN_TOPIC_0000001099501074"></a>

-   [Public Method Summary](#section9524257145511)
-   [Public Methods](#section7776112444917)
-   [fromScreenLocation](#section10287164110496)
-   [getVisibleRegion](#section124911628145020)
-   [toScreenLocation](#section998261112518)


<a name="table7571mcpsimp"></a>
<table><thead align="left"><tr id="row7575mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p7577mcpsimp"><a name="p7577mcpsimp"></a><a name="p7577mcpsimp"></a>Class Info</p>
</th>
</tr>
</thead>
<tbody><tr id="row7578mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p1896216215276"><a name="p1896216215276"></a><a name="p1896216215276"></a>public final class Projection</p>
<p id="p1424810532119"><a name="p1424810532119"></a><a name="p1424810532119"></a>继承自Object的final类，这个类用于在屏幕坐标和经纬度之间进行转换，在调用<a href="huaweimap.md">HuaweiMap</a>类的<a href="huaweimap.md#section10118629175416">getProjection</a>方法时会返回该类型的实例。</p>
</td>
</tr>
</tbody>
</table>

## Public Method Summary<a name="section9524257145511"></a>

<a name="table7586mcpsimp"></a>
<table><thead align="left"><tr id="row7591mcpsimp"><th class="cellrowborder" valign="top" width="40%" id="mcps1.1.3.1.1"><p id="p7593mcpsimp"><a name="p7593mcpsimp"></a><a name="p7593mcpsimp"></a>Qualifier and Type</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.1.3.1.2"><p id="p7595mcpsimp"><a name="p7595mcpsimp"></a><a name="p7595mcpsimp"></a>Method Name and Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row7596mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p7598mcpsimp"><a name="p7598mcpsimp"></a><a name="p7598mcpsimp"></a><a href="latlng.md">LatLng</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p7600mcpsimp"><a name="p7600mcpsimp"></a><a name="p7600mcpsimp"></a><a href="#section10287164110496">fromScreenLocation</a>(Point point)</p>
<p id="p116251151217"><a name="p116251151217"></a><a name="p116251151217"></a>实现屏幕像素点坐标转换成经纬度。</p>
</td>
</tr>
<tr id="row7601mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p7603mcpsimp"><a name="p7603mcpsimp"></a><a name="p7603mcpsimp"></a><a href="visibleregion.md">VisibleRegion</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p7605mcpsimp"><a name="p7605mcpsimp"></a><a name="p7605mcpsimp"></a><a href="#section124911628145020">getVisibleRegion</a>()</p>
<p id="p114399161813"><a name="p114399161813"></a><a name="p114399161813"></a>获取在屏幕坐标和地理经纬度坐标之间转换之后的可见区域。</p>
</td>
</tr>
<tr id="row7606mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p7608mcpsimp"><a name="p7608mcpsimp"></a><a name="p7608mcpsimp"></a>Point</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p7610mcpsimp"><a name="p7610mcpsimp"></a><a name="p7610mcpsimp"></a><a href="#section998261112518">toScreenLocation</a>(<a href="latlng.md">LatLng</a> latLng)</p>
<p id="p102271617615"><a name="p102271617615"></a><a name="p102271617615"></a>获取与经纬度对应的屏幕上的点的位置。</p>
</td>
</tr>
</tbody>
</table>

## Public Methods<a name="section7776112444917"></a>

## fromScreenLocation<a name="section10287164110496"></a>

<a name="table7613mcpsimp"></a>
<table><thead align="left"><tr id="row7617mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p7619mcpsimp"><a name="p7619mcpsimp"></a><a name="p7619mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row7620mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p7622mcpsimp"><a name="p7622mcpsimp"></a><a name="p7622mcpsimp"></a>public <a href="latlng.md">LatLng</a> fromScreenLocation(Point point)</p>
<p id="p7628mcpsimp"><a name="p7628mcpsimp"></a><a name="p7628mcpsimp"></a>您调用此API实现屏幕像素点坐标转换成经纬度。屏幕位置是以相对于地图左上角（而不是整个屏幕的左上角）的屏幕像素（而非显示像素）指定的。</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table7631mcpsimp"></a>
<table><thead align="left"><tr id="row7636mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p7638mcpsimp"><a name="p7638mcpsimp"></a><a name="p7638mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p7640mcpsimp"><a name="p7640mcpsimp"></a><a name="p7640mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row7641mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p7643mcpsimp"><a name="p7643mcpsimp"></a><a name="p7643mcpsimp"></a>point</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p7645mcpsimp"><a name="p7645mcpsimp"></a><a name="p7645mcpsimp"></a>屏幕上的坐标点，单位：像素。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table7648mcpsimp"></a>
<table><thead align="left"><tr id="row7653mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p7655mcpsimp"><a name="p7655mcpsimp"></a><a name="p7655mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p7657mcpsimp"><a name="p7657mcpsimp"></a><a name="p7657mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row7658mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p586392532517"><a name="p586392532517"></a><a name="p586392532517"></a>LatLng</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p7662mcpsimp"><a name="p7662mcpsimp"></a><a name="p7662mcpsimp"></a><a href="latlng.md">LatLng</a>对象，表示经纬度。</p>
</td>
</tr>
</tbody>
</table>

## getVisibleRegion<a name="section124911628145020"></a>

<a name="table7664mcpsimp"></a>
<table><thead align="left"><tr id="row7668mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p7670mcpsimp"><a name="p7670mcpsimp"></a><a name="p7670mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row7671mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p7673mcpsimp"><a name="p7673mcpsimp"></a><a name="p7673mcpsimp"></a>public <a href="visibleregion.md">VisibleRegion</a> getVisibleRegion()</p>
<p id="p7676mcpsimp"><a name="p7676mcpsimp"></a><a name="p7676mcpsimp"></a>您调用此API可以获取在屏幕坐标和地理经纬度坐标之间转换之后的可见区域。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table7682mcpsimp"></a>
<table><thead align="left"><tr id="row7687mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p7689mcpsimp"><a name="p7689mcpsimp"></a><a name="p7689mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p7691mcpsimp"><a name="p7691mcpsimp"></a><a name="p7691mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row7692mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p27691234112512"><a name="p27691234112512"></a><a name="p27691234112512"></a><a href="visibleregion.md">VisibleRegion</a></p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p7696mcpsimp"><a name="p7696mcpsimp"></a><a name="p7696mcpsimp"></a>可见区域。</p>
</td>
</tr>
</tbody>
</table>

## toScreenLocation<a name="section998261112518"></a>

<a name="table7698mcpsimp"></a>
<table><thead align="left"><tr id="row7702mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p7704mcpsimp"><a name="p7704mcpsimp"></a><a name="p7704mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row7705mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p7707mcpsimp"><a name="p7707mcpsimp"></a><a name="p7707mcpsimp"></a>public Point toScreenLocation(<a href="latlng.md">LatLng</a> latLng)</p>
<p id="p7710mcpsimp"><a name="p7710mcpsimp"></a><a name="p7710mcpsimp"></a>您调用此API可获取与经纬度对应的屏幕上的点的位置。屏幕位置是以相对于地图左上角（而不是整个屏幕的左上角）的屏幕像素（而非显示像素）指定的。</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table7716mcpsimp"></a>
<table><thead align="left"><tr id="row7721mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p7723mcpsimp"><a name="p7723mcpsimp"></a><a name="p7723mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p7725mcpsimp"><a name="p7725mcpsimp"></a><a name="p7725mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row7726mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p7728mcpsimp"><a name="p7728mcpsimp"></a><a name="p7728mcpsimp"></a>latLng</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p7730mcpsimp"><a name="p7730mcpsimp"></a><a name="p7730mcpsimp"></a><a href="latlng.md">LatLng</a>对象，表示经纬度。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table7733mcpsimp"></a>
<table><thead align="left"><tr id="row7738mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p7740mcpsimp"><a name="p7740mcpsimp"></a><a name="p7740mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p7742mcpsimp"><a name="p7742mcpsimp"></a><a name="p7742mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row7743mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p7745mcpsimp"><a name="p7745mcpsimp"></a><a name="p7745mcpsimp"></a>Point</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p7747mcpsimp"><a name="p7747mcpsimp"></a><a name="p7747mcpsimp"></a>屏幕上的坐标点，单位：像素。</p>
</td>
</tr>
</tbody>
</table>

