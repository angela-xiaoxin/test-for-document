# HuaweiMap.OnPolygonClickListener<a name="EN-US_TOPIC_0000001145860947"></a>

-   [Public Method Summary](#section460124143318)
-   [Public Methods](#section165316915556)
-   [onPolygonClick](#section101721911558)


<a name="table4582mcpsimp"></a>
<table><thead align="left"><tr id="row4586mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p4588mcpsimp"><a name="p4588mcpsimp"></a><a name="p4588mcpsimp"></a>Interface Info</p>
</th>
</tr>
</thead>
<tbody><tr id="row4589mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p132691818142613"><a name="p132691818142613"></a><a name="p132691818142613"></a>public interface HuaweiMap.OnPolygonClickListener</p>
<p id="p4591mcpsimp"><a name="p4591mcpsimp"></a><a name="p4591mcpsimp"></a>An internal API of the <a href="huaweimap.md">HuaweiMap</a> class, which is used to listen for the polygon tap event. It contains the abstract method <a href="#section101721911558">onPolygonClick</a>(<a href="polygon.md">Polygon</a>).</p>
</td>
</tr>
</tbody>
</table>

## Public Method Summary<a name="section460124143318"></a>

<a name="table4597mcpsimp"></a>
<table><thead align="left"><tr id="row4602mcpsimp"><th class="cellrowborder" valign="top" width="40%" id="mcps1.1.3.1.1"><p id="p4604mcpsimp"><a name="p4604mcpsimp"></a><a name="p4604mcpsimp"></a>Qualifier and Type</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.1.3.1.2"><p id="p4606mcpsimp"><a name="p4606mcpsimp"></a><a name="p4606mcpsimp"></a>Method Name and Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row4607mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p4609mcpsimp"><a name="p4609mcpsimp"></a><a name="p4609mcpsimp"></a>abstract void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p4611mcpsimp"><a name="p4611mcpsimp"></a><a name="p4611mcpsimp"></a><a href="#section101721911558">onPolygonClick</a>(<a href="polygon.md">Polygon</a> polygon)</p>
<p id="p194027211167"><a name="p194027211167"></a><a name="p194027211167"></a>Called when a polygon is tapped.</p>
</td>
</tr>
</tbody>
</table>

## Public Methods<a name="section165316915556"></a>

## onPolygonClick<a name="section101721911558"></a>

<a name="table4614mcpsimp"></a>
<table><thead align="left"><tr id="row4618mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p4620mcpsimp"><a name="p4620mcpsimp"></a><a name="p4620mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row4621mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p4623mcpsimp"><a name="p4623mcpsimp"></a><a name="p4623mcpsimp"></a>public abstract void onPolygonClick(<a href="polygon.md">Polygon</a> polygon)</p>
<p id="p4626mcpsimp"><a name="p4626mcpsimp"></a><a name="p4626mcpsimp"></a>Called when a polygon is tapped. This method must be called in the main thread.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table4629mcpsimp"></a>
<table><thead align="left"><tr id="row4634mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p4636mcpsimp"><a name="p4636mcpsimp"></a><a name="p4636mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p4638mcpsimp"><a name="p4638mcpsimp"></a><a name="p4638mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row4639mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p4641mcpsimp"><a name="p4641mcpsimp"></a><a name="p4641mcpsimp"></a>polygon</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p4643mcpsimp"><a name="p4643mcpsimp"></a><a name="p4643mcpsimp"></a>Polygon that is tapped.</p>
</td>
</tr>
</tbody>
</table>

