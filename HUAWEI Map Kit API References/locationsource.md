# LocationSource<a name="EN-US_TOPIC_0000001145860923"></a>

-   [Nested Class Summary](#section18656449153516)
-   [Public Method Summary](#section849186103618)
-   [Public Methods](#section944171212368)
-   [activate](#section549262333611)
-   [deactivate](#section825742143618)


<a name="table6226mcpsimp"></a>
<table><thead align="left"><tr id="row6230mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p6232mcpsimp"><a name="p6232mcpsimp"></a><a name="p6232mcpsimp"></a>Interface Info</p>
</th>
</tr>
</thead>
<tbody><tr id="row6233mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p175181547257"><a name="p175181547257"></a><a name="p175181547257"></a>public interface LocationSource</p>
<p id="p1370184455912"><a name="p1370184455912"></a><a name="p1370184455912"></a>Defines a location source that provides location data for the map.</p>
</td>
</tr>
</tbody>
</table>

## Nested Class Summary<a name="section18656449153516"></a>

<a name="table6262mcpsimp"></a>
<table><thead align="left"><tr id="row6267mcpsimp"><th class="cellrowborder" valign="top" width="56.99999999999999%" id="mcps1.1.3.1.1"><p id="p7543132495318"><a name="p7543132495318"></a><a name="p7543132495318"></a>Qualifier and Type</p>
</th>
<th class="cellrowborder" valign="top" width="43%" id="mcps1.1.3.1.2"><p id="p1554319242536"><a name="p1554319242536"></a><a name="p1554319242536"></a>Class Name and Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row6272mcpsimp"><td class="cellrowborder" valign="top" width="56.99999999999999%" headers="mcps1.1.3.1.1 "><p id="p6274mcpsimp"><a name="p6274mcpsimp"></a><a name="p6274mcpsimp"></a>public interface</p>
</td>
<td class="cellrowborder" valign="top" width="43%" headers="mcps1.1.3.1.2 "><p id="p1339565863313"><a name="p1339565863313"></a><a name="p1339565863313"></a><a href="onlocationchangedlistener.md">LocationSource.OnLocationChangedListener</a></p>
<p id="p6276mcpsimp"><a name="p6276mcpsimp"></a><a name="p6276mcpsimp"></a>Listener used to listen for location updates.</p>
</td>
</tr>
</tbody>
</table>

## Public Method Summary<a name="section849186103618"></a>

<a name="table6241mcpsimp"></a>
<table><thead align="left"><tr id="row6246mcpsimp"><th class="cellrowborder" valign="top" width="40%" id="mcps1.1.3.1.1"><p id="p6248mcpsimp"><a name="p6248mcpsimp"></a><a name="p6248mcpsimp"></a><strong id="b23726193614"><a name="b23726193614"></a><a name="b23726193614"></a>Qualifier and Type</strong></p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.1.3.1.2"><p id="p6250mcpsimp"><a name="p6250mcpsimp"></a><a name="p6250mcpsimp"></a>Method Name and Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row6251mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p6253mcpsimp"><a name="p6253mcpsimp"></a><a name="p6253mcpsimp"></a>abstract void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p6255mcpsimp"><a name="p6255mcpsimp"></a><a name="p6255mcpsimp"></a><a href="#section549262333611">activate</a>(<a href="onlocationchangedlistener.md">LocationSource.OnLocationChangedListener</a> listener)</p>
<p id="p1242212673"><a name="p1242212673"></a><a name="p1242212673"></a>Activates a location source and listens for location updates.</p>
</td>
</tr>
<tr id="row6256mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p6258mcpsimp"><a name="p6258mcpsimp"></a><a name="p6258mcpsimp"></a>abstract void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p6260mcpsimp"><a name="p6260mcpsimp"></a><a name="p6260mcpsimp"></a><a href="#section825742143618">deactivate</a>()</p>
<p id="p443143972"><a name="p443143972"></a><a name="p443143972"></a>Deactivates a location source.</p>
</td>
</tr>
</tbody>
</table>

## Public Methods<a name="section944171212368"></a>

## activate<a name="section549262333611"></a>

<a name="table6279mcpsimp"></a>
<table><thead align="left"><tr id="row6283mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p6285mcpsimp"><a name="p6285mcpsimp"></a><a name="p6285mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row6286mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p6288mcpsimp"><a name="p6288mcpsimp"></a><a name="p6288mcpsimp"></a>public abstract void activate(<a href="onlocationchangedlistener.md">LocationSource.OnLocationChangedListener</a> listener)</p>
<p id="p680933442413"><a name="p680933442413"></a><a name="p680933442413"></a>Activates a location source and listens for location updates.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table6294mcpsimp"></a>
<table><thead align="left"><tr id="row6299mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p6301mcpsimp"><a name="p6301mcpsimp"></a><a name="p6301mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p6303mcpsimp"><a name="p6303mcpsimp"></a><a name="p6303mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row6304mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p6306mcpsimp"><a name="p6306mcpsimp"></a><a name="p6306mcpsimp"></a>listener</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p6308mcpsimp"><a name="p6308mcpsimp"></a><a name="p6308mcpsimp"></a>Listener used to listen for location updates.</p>
</td>
</tr>
</tbody>
</table>

## deactivate<a name="section825742143618"></a>

<a name="table6335mcpsimp"></a>
<table><thead align="left"><tr id="row6339mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p6341mcpsimp"><a name="p6341mcpsimp"></a><a name="p6341mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row6342mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p6344mcpsimp"><a name="p6344mcpsimp"></a><a name="p6344mcpsimp"></a>public abstract deactivate()</p>
<p id="p114221918192518"><a name="p114221918192518"></a><a name="p114221918192518"></a>Deactivates a location source.</p>
</td>
</tr>
</tbody>
</table>

