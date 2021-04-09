# HuaweiMap.OnMapLongClickListener<a name="ZH-CN_TOPIC_0000001099341126"></a>

-   [Public Method Summary](#section4591457193110)
-   [Public Methods](#section15643125574511)
-   [onMapLongClick](#section821945114617)


<a name="table4094mcpsimp"></a>
<table><thead align="left"><tr id="row4098mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p4100mcpsimp"><a name="p4100mcpsimp"></a><a name="p4100mcpsimp"></a>Interface Info</p>
</th>
</tr>
</thead>
<tbody><tr id="row4101mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p1887214511243"><a name="p1887214511243"></a><a name="p1887214511243"></a>public interface HuaweiMap.OnMapLongClickListener</p>
<p id="p4103mcpsimp"><a name="p4103mcpsimp"></a><a name="p4103mcpsimp"></a>是<a href="huaweimap.md">HuaweiMap</a>类的一个内部接口，表示地图长按事件的侦听器，包含一个抽象函数<a href="#section821945114617">onMapLongClick</a>(<a href="latlng.md">LatLng</a>)。</p>
</td>
</tr>
</tbody>
</table>

## Public Method Summary<a name="section4591457193110"></a>

<a name="table4109mcpsimp"></a>
<table><thead align="left"><tr id="row4114mcpsimp"><th class="cellrowborder" valign="top" width="40%" id="mcps1.1.3.1.1"><p id="p4116mcpsimp"><a name="p4116mcpsimp"></a><a name="p4116mcpsimp"></a>Qualifier and Type</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.1.3.1.2"><p id="p4118mcpsimp"><a name="p4118mcpsimp"></a><a name="p4118mcpsimp"></a>Method Name and Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row4119mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p4121mcpsimp"><a name="p4121mcpsimp"></a><a name="p4121mcpsimp"></a>abstract void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p4123mcpsimp"><a name="p4123mcpsimp"></a><a name="p4123mcpsimp"></a><a href="#section821945114617">onMapLongClick</a>(<a href="latlng.md">LatLng</a> latLng)</p>
<p id="p18458411038"><a name="p18458411038"></a><a name="p18458411038"></a>长按地图时回调此方法，仅当地图的覆盖层均未处理该手势的时候才会调用。</p>
</td>
</tr>
</tbody>
</table>

## Public Methods<a name="section15643125574511"></a>

## onMapLongClick<a name="section821945114617"></a>

<a name="table4126mcpsimp"></a>
<table><thead align="left"><tr id="row4130mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p4132mcpsimp"><a name="p4132mcpsimp"></a><a name="p4132mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row4133mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p4135mcpsimp"><a name="p4135mcpsimp"></a><a name="p4135mcpsimp"></a>public abstract void onMapLongClick(<a href="latlng.md">LatLng</a> latLng)</p>
<p id="p181281167463"><a name="p181281167463"></a><a name="p181281167463"></a>长按地图时回调此方法，仅当地图的覆盖层均未处理该手势的时候才会调用。必须在主线程中执行。</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table4141mcpsimp"></a>
<table><thead align="left"><tr id="row4146mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p4148mcpsimp"><a name="p4148mcpsimp"></a><a name="p4148mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p4150mcpsimp"><a name="p4150mcpsimp"></a><a name="p4150mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row4151mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p4153mcpsimp"><a name="p4153mcpsimp"></a><a name="p4153mcpsimp"></a>latLng</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p4155mcpsimp"><a name="p4155mcpsimp"></a><a name="p4155mcpsimp"></a>长按的点。</p>
</td>
</tr>
</tbody>
</table>

