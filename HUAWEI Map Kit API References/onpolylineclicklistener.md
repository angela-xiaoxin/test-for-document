# HuaweiMap.OnPolylineClickListener<a name="EN-US_TOPIC_0000001145781007"></a>

-   [Public Method Summary](#section15252125403319)
-   [Public Methods](#section18788949155619)
-   [onPolylineClick](#section101131459577)


<a name="table4648mcpsimp"></a>
<table><thead align="left"><tr id="row4652mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p4654mcpsimp"><a name="p4654mcpsimp"></a><a name="p4654mcpsimp"></a>Interface Info</p>
</th>
</tr>
</thead>
<tbody><tr id="row4655mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p7564621142619"><a name="p7564621142619"></a><a name="p7564621142619"></a>public interface HuaweiMap.OnPolylineClickListener</p>
<p id="p4657mcpsimp"><a name="p4657mcpsimp"></a><a name="p4657mcpsimp"></a>An internal API of the <a href="huaweimap.md">HuaweiMap</a> class, which is used to listen for the polyline tap event. It contains the abstract method <a href="#section101131459577">onPolylineClick</a>(<a href="polyline.md">Polyline</a>).</p>
</td>
</tr>
</tbody>
</table>

## Public Method Summary<a name="section15252125403319"></a>

<a name="table4663mcpsimp"></a>
<table><thead align="left"><tr id="row4668mcpsimp"><th class="cellrowborder" valign="top" width="40%" id="mcps1.1.3.1.1"><p id="p4670mcpsimp"><a name="p4670mcpsimp"></a><a name="p4670mcpsimp"></a>Qualifier and Type</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.1.3.1.2"><p id="p4672mcpsimp"><a name="p4672mcpsimp"></a><a name="p4672mcpsimp"></a>Method Name and Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row4673mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p4675mcpsimp"><a name="p4675mcpsimp"></a><a name="p4675mcpsimp"></a>abstract void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p4677mcpsimp"><a name="p4677mcpsimp"></a><a name="p4677mcpsimp"></a><a href="#section101131459577">onPolylineClick</a>(<a href="polyline.md">Polyline</a> polyline)</p>
<p id="p176047333614"><a name="p176047333614"></a><a name="p176047333614"></a>Called when a polyline is tapped.</p>
</td>
</tr>
</tbody>
</table>

## Public Methods<a name="section18788949155619"></a>

## onPolylineClick<a name="section101131459577"></a>

<a name="table4680mcpsimp"></a>
<table><thead align="left"><tr id="row4684mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p4686mcpsimp"><a name="p4686mcpsimp"></a><a name="p4686mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row4687mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p4689mcpsimp"><a name="p4689mcpsimp"></a><a name="p4689mcpsimp"></a>public abstract void onPolylineClick(<a href="polyline.md">Polyline</a> polyline)</p>
<p id="p4692mcpsimp"><a name="p4692mcpsimp"></a><a name="p4692mcpsimp"></a>Called when a polyline is tapped. This method must be called in the main thread.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table4695mcpsimp"></a>
<table><thead align="left"><tr id="row4700mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p4702mcpsimp"><a name="p4702mcpsimp"></a><a name="p4702mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p4704mcpsimp"><a name="p4704mcpsimp"></a><a name="p4704mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row4705mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p4707mcpsimp"><a name="p4707mcpsimp"></a><a name="p4707mcpsimp"></a>polyline</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p4709mcpsimp"><a name="p4709mcpsimp"></a><a name="p4709mcpsimp"></a>Polyline that is tapped.</p>
</td>
</tr>
</tbody>
</table>

