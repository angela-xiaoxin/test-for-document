# HuaweiMap.OnMapClickListener<a name="ZH-CN_TOPIC_0000001145541089"></a>

-   [Public Method Summary](#section768803719289)
-   [Public Methods](#section1899113612436)
-   [onMapClick](#section2046695034315)


<a name="table3976mcpsimp"></a>
<table><thead align="left"><tr id="row3980mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p3982mcpsimp"><a name="p3982mcpsimp"></a><a name="p3982mcpsimp"></a>Interface Info</p>
</th>
</tr>
</thead>
<tbody><tr id="row3983mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p7545386244"><a name="p7545386244"></a><a name="p7545386244"></a>public interface HuaweiMap.OnMapClickListener</p>
<p id="p3985mcpsimp"><a name="p3985mcpsimp"></a><a name="p3985mcpsimp"></a>是<a href="huaweimap.md">HuaweiMap</a>类的一个内部接口，表示地图点击事件的侦听器，包含一个抽象函数<a href="#section2046695034315">onMapClick</a>(<a href="latlng.md">LatLng</a>)。</p>
</td>
</tr>
</tbody>
</table>

## Public Method Summary<a name="section768803719289"></a>

<a name="table3991mcpsimp"></a>
<table><thead align="left"><tr id="row3996mcpsimp"><th class="cellrowborder" valign="top" width="40%" id="mcps1.1.3.1.1"><p id="p081120285386"><a name="p081120285386"></a><a name="p081120285386"></a>Qualifier and Type</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.1.3.1.2"><p id="p681112883813"><a name="p681112883813"></a><a name="p681112883813"></a>Method Name and Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row4001mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p4003mcpsimp"><a name="p4003mcpsimp"></a><a name="p4003mcpsimp"></a>abstract void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p4005mcpsimp"><a name="p4005mcpsimp"></a><a name="p4005mcpsimp"></a><a href="#section2046695034315">onMapClick</a>(<a href="latlng.md">LatLng</a> latLng)</p>
<p id="p05220291128"><a name="p05220291128"></a><a name="p05220291128"></a>点击地图时回调此方法，但前提是地图上的所有覆盖层均未处理手势。</p>
</td>
</tr>
</tbody>
</table>

## Public Methods<a name="section1899113612436"></a>

## onMapClick<a name="section2046695034315"></a>

<a name="table4008mcpsimp"></a>
<table><thead align="left"><tr id="row4012mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p4014mcpsimp"><a name="p4014mcpsimp"></a><a name="p4014mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row4015mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p4017mcpsimp"><a name="p4017mcpsimp"></a><a name="p4017mcpsimp"></a>public abstract void onMapClick(<a href="latlng.md">LatLng</a> latLng)</p>
<p id="p4020mcpsimp"><a name="p4020mcpsimp"></a><a name="p4020mcpsimp"></a>点击地图时回调此方法，但前提是地图上的所有覆盖层均未处理手势。必须在主线程中执行。</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table4023mcpsimp"></a>
<table><thead align="left"><tr id="row4028mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p4030mcpsimp"><a name="p4030mcpsimp"></a><a name="p4030mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p4032mcpsimp"><a name="p4032mcpsimp"></a><a name="p4032mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row4033mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p4035mcpsimp"><a name="p4035mcpsimp"></a><a name="p4035mcpsimp"></a>latLng</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p4037mcpsimp"><a name="p4037mcpsimp"></a><a name="p4037mcpsimp"></a>点击的点。</p>
</td>
</tr>
</tbody>
</table>

