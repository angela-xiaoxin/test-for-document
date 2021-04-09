# HuaweiMap.OnMarkerDragListener<a name="ZH-CN_TOPIC_0000001145860963"></a>

-   [Public Method Summary](#section13590428113210)
-   [Public Methods](#section6873112314814)
-   [onMarkerDrag](#section41919381488)
-   [onMarkerDragEnd](#section17191517124913)
-   [onMarkerDragStart](#section15750115717498)


<a name="table4240mcpsimp"></a>
<table><thead align="left"><tr id="row4244mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p4246mcpsimp"><a name="p4246mcpsimp"></a><a name="p4246mcpsimp"></a>Interface Info</p>
</th>
</tr>
</thead>
<tbody><tr id="row4247mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p1813162272417"><a name="p1813162272417"></a><a name="p1813162272417"></a>public interface HuaweiMap.OnMarkerDragListener</p>
<p id="p4249mcpsimp"><a name="p4249mcpsimp"></a><a name="p4249mcpsimp"></a>是<a href="huaweimap.md">HuaweiMap</a>类的一个内部接口，表示标记拖拽事件进行侦听器，包含三个抽象函数<a href="#section41919381488">onMarkerDrag</a>(<a href="marker.md">Marker</a>)、<a href="#section17191517124913">onMarkerDragEnd</a>(<a href="marker.md">Marker</a>)、<a href="#section15750115717498">onMarkerDragStart</a>(<a href="marker.md">Marker</a>)。用户实现此接口可以对标记拖拽事件进行侦听。</p>
</td>
</tr>
</tbody>
</table>

## Public Method Summary<a name="section13590428113210"></a>

<a name="table4255mcpsimp"></a>
<table><thead align="left"><tr id="row4260mcpsimp"><th class="cellrowborder" valign="top" width="40%" id="mcps1.1.3.1.1"><p id="p4262mcpsimp"><a name="p4262mcpsimp"></a><a name="p4262mcpsimp"></a>Qualifier and Type</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.1.3.1.2"><p id="p4264mcpsimp"><a name="p4264mcpsimp"></a><a name="p4264mcpsimp"></a>Method Name and Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row4265mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p4267mcpsimp"><a name="p4267mcpsimp"></a><a name="p4267mcpsimp"></a>abstract void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p4269mcpsimp"><a name="p4269mcpsimp"></a><a name="p4269mcpsimp"></a><a href="#section41919381488">onMarkerDrag</a>(<a href="marker.md">Marker</a> marker)</p>
<p id="p827610523319"><a name="p827610523319"></a><a name="p827610523319"></a>标记拖动过程中反复回调此方法，标记的位置可通过<a href="marker.md#section49343761418">getPosition</a>()获取。</p>
</td>
</tr>
<tr id="row4270mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p4272mcpsimp"><a name="p4272mcpsimp"></a><a name="p4272mcpsimp"></a>abstract void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p4274mcpsimp"><a name="p4274mcpsimp"></a><a name="p4274mcpsimp"></a><a href="#section17191517124913">onMarkerDragEnd</a>(<a href="marker.md">Marker</a> marker)</p>
<p id="p1351411531338"><a name="p1351411531338"></a><a name="p1351411531338"></a>标记拖动完成时回调此方法，标记的位置可通过<a href="marker.md#section49343761418">getPosition</a>()获取。</p>
</td>
</tr>
<tr id="row4275mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p4277mcpsimp"><a name="p4277mcpsimp"></a><a name="p4277mcpsimp"></a>abstract void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p4279mcpsimp"><a name="p4279mcpsimp"></a><a name="p4279mcpsimp"></a><a href="#section15750115717498">onMarkerDragStart</a>(<a href="marker.md">Marker</a> marker)</p>
<p id="p9484154638"><a name="p9484154638"></a><a name="p9484154638"></a>标记拖动开始时回调此方法，标记的位置可通过<a href="marker.md#section49343761418">getPosition</a>()获取。</p>
</td>
</tr>
</tbody>
</table>

## Public Methods<a name="section6873112314814"></a>

## onMarkerDrag<a name="section41919381488"></a>

<a name="table4282mcpsimp"></a>
<table><thead align="left"><tr id="row4286mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p4288mcpsimp"><a name="p4288mcpsimp"></a><a name="p4288mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row4289mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p4291mcpsimp"><a name="p4291mcpsimp"></a><a name="p4291mcpsimp"></a>public abstract void onMarkerDrag(<a href="marker.md">Marker</a> marker)</p>
<p id="p4294mcpsimp"><a name="p4294mcpsimp"></a><a name="p4294mcpsimp"></a>标记拖动过程中反复回调此方法，标记的位置可通过<a href="marker.md#section49343761418">getPosition</a>()获取。</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table4297mcpsimp"></a>
<table><thead align="left"><tr id="row4302mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p4304mcpsimp"><a name="p4304mcpsimp"></a><a name="p4304mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p4306mcpsimp"><a name="p4306mcpsimp"></a><a name="p4306mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row4307mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p4309mcpsimp"><a name="p4309mcpsimp"></a><a name="p4309mcpsimp"></a>marker</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p4311mcpsimp"><a name="p4311mcpsimp"></a><a name="p4311mcpsimp"></a>拖动的标记。</p>
</td>
</tr>
</tbody>
</table>

## onMarkerDragEnd<a name="section17191517124913"></a>

<a name="table4316mcpsimp"></a>
<table><thead align="left"><tr id="row4320mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p4322mcpsimp"><a name="p4322mcpsimp"></a><a name="p4322mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row4323mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p4325mcpsimp"><a name="p4325mcpsimp"></a><a name="p4325mcpsimp"></a>public abstract void onMarkerDragEnd(<a href="marker.md">Marker</a> marker)</p>
<p id="p4328mcpsimp"><a name="p4328mcpsimp"></a><a name="p4328mcpsimp"></a>标记拖动完成时回调此方法，标记的位置可通过<a href="marker.md#section49343761418">getPosition</a>()获取。</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table4331mcpsimp"></a>
<table><thead align="left"><tr id="row4336mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p4338mcpsimp"><a name="p4338mcpsimp"></a><a name="p4338mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p4340mcpsimp"><a name="p4340mcpsimp"></a><a name="p4340mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row4341mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p4343mcpsimp"><a name="p4343mcpsimp"></a><a name="p4343mcpsimp"></a>marker</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p4345mcpsimp"><a name="p4345mcpsimp"></a><a name="p4345mcpsimp"></a>拖动的标记。</p>
</td>
</tr>
</tbody>
</table>

## onMarkerDragStart<a name="section15750115717498"></a>

<a name="table4350mcpsimp"></a>
<table><thead align="left"><tr id="row4354mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p4356mcpsimp"><a name="p4356mcpsimp"></a><a name="p4356mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row4357mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p4359mcpsimp"><a name="p4359mcpsimp"></a><a name="p4359mcpsimp"></a>public abstract void onMarkerDragStart(<a href="marker.md">Marker</a> marker)</p>
<p id="p4362mcpsimp"><a name="p4362mcpsimp"></a><a name="p4362mcpsimp"></a>标记拖动开始时回调此方法，标记的位置可通过<a href="marker.md#section49343761418">getPosition</a>()获取。此位置可能与拖动开始之前的位置不同，因为标记在接触到上方弹出。</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table4365mcpsimp"></a>
<table><thead align="left"><tr id="row4370mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p4372mcpsimp"><a name="p4372mcpsimp"></a><a name="p4372mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p4374mcpsimp"><a name="p4374mcpsimp"></a><a name="p4374mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row4375mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p4377mcpsimp"><a name="p4377mcpsimp"></a><a name="p4377mcpsimp"></a>marker</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p4379mcpsimp"><a name="p4379mcpsimp"></a><a name="p4379mcpsimp"></a>拖动的标记。</p>
</td>
</tr>
</tbody>
</table>

