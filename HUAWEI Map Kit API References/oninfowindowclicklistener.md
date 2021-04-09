# HuaweiMap.OnInfoWindowClickListener<a name="EN-US_TOPIC_0000001145780987"></a>

-   [Public Method Summary](#section986625372714)
-   [Public Methods](#section7401191143913)
-   [onInfoWindowClick](#section42521813113917)


<a name="table3778mcpsimp"></a>
<table><thead align="left"><tr id="row3782mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p3784mcpsimp"><a name="p3784mcpsimp"></a><a name="p3784mcpsimp"></a>Interface Info</p>
</th>
</tr>
</thead>
<tbody><tr id="row3785mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p2752145382310"><a name="p2752145382310"></a><a name="p2752145382310"></a>public interface HuaweiMap.OnInfoWindowClick</p>
<p id="p3787mcpsimp"><a name="p3787mcpsimp"></a><a name="p3787mcpsimp"></a>An internal API of the <a href="huaweimap.md">HuaweiMap</a> class, which is used to listen for the information window tap event. It contains the abstract method <a href="#section42521813113917">onInfoWindowClick</a>(<a href="marker.md">Marker</a>). You can register this API and implement its abstract method to listen for the tap event of the information window of a marker.</p>
</td>
</tr>
</tbody>
</table>

## Public Method Summary<a name="section986625372714"></a>

<a name="table3793mcpsimp"></a>
<table><thead align="left"><tr id="row3798mcpsimp"><th class="cellrowborder" valign="top" width="40%" id="mcps1.1.3.1.1"><p id="p081120285386"><a name="p081120285386"></a><a name="p081120285386"></a>Qualifier and Type</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.1.3.1.2"><p id="p681112883813"><a name="p681112883813"></a><a name="p681112883813"></a>Method Name and Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row3803mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p3805mcpsimp"><a name="p3805mcpsimp"></a><a name="p3805mcpsimp"></a>abstract void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p3807mcpsimp"><a name="p3807mcpsimp"></a><a name="p3807mcpsimp"></a><a href="#section42521813113917">onInfoWindowClick</a>(<a href="marker.md">Marker</a> marker)</p>
<p id="p115821053017"><a name="p115821053017"></a><a name="p115821053017"></a>Called when the information window of a marker is tapped.</p>
</td>
</tr>
</tbody>
</table>

## Public Methods<a name="section7401191143913"></a>

## onInfoWindowClick<a name="section42521813113917"></a>

<a name="table3810mcpsimp"></a>
<table><thead align="left"><tr id="row3814mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p3816mcpsimp"><a name="p3816mcpsimp"></a><a name="p3816mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row3817mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p3819mcpsimp"><a name="p3819mcpsimp"></a><a name="p3819mcpsimp"></a>public abstract void onInfoWindowClick(<a href="marker.md">Marker</a> marker)</p>
<p id="p3822mcpsimp"><a name="p3822mcpsimp"></a><a name="p3822mcpsimp"></a>Called when the information window of a marker is tapped. This method must be called in the main thread.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table3825mcpsimp"></a>
<table><thead align="left"><tr id="row3830mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p3832mcpsimp"><a name="p3832mcpsimp"></a><a name="p3832mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p3834mcpsimp"><a name="p3834mcpsimp"></a><a name="p3834mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row3835mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p3837mcpsimp"><a name="p3837mcpsimp"></a><a name="p3837mcpsimp"></a>marker</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p3839mcpsimp"><a name="p3839mcpsimp"></a><a name="p3839mcpsimp"></a>Marker whose information window is tapped.</p>
</td>
</tr>
</tbody>
</table>

