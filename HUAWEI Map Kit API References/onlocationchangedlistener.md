# LocationSource.OnLocationChangedListener<a name="EN-US_TOPIC_0000001145941027"></a>

-   [Public Method Summary](#section143575093710)
-   [Public Methods](#section22211569258)
-   [onLocationChanged](#section1642434142613)


<a name="table6372mcpsimp"></a>
<table><thead align="left"><tr id="row6376mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p3916mcpsimp"><a name="p3916mcpsimp"></a><a name="p3916mcpsimp"></a>Interface Info</p>
</th>
</tr>
</thead>
<tbody><tr id="row6379mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p3558710269"><a name="p3558710269"></a><a name="p3558710269"></a>public static interface LocationSource.OnLocationChangedListener</p>
<p id="p553455811144"><a name="p553455811144"></a><a name="p553455811144"></a>An internal API of the <a href="locationsource.md">LocationSource</a> class, which is used to listen for location source changes. It contains the abstract method <a href="#section1642434142613">onLocationChanged</a><strong id="b11941193692219"><a name="b11941193692219"></a><a name="b11941193692219"></a>(Location)</strong>.</p>
</td>
</tr>
</tbody>
</table>

## Public Method Summary<a name="section143575093710"></a>

<a name="table6387mcpsimp"></a>
<table><thead align="left"><tr id="row6392mcpsimp"><th class="cellrowborder" valign="top" width="40%" id="mcps1.1.3.1.1"><p id="p6394mcpsimp"><a name="p6394mcpsimp"></a><a name="p6394mcpsimp"></a>Qualifier and Type</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.1.3.1.2"><p id="p6396mcpsimp"><a name="p6396mcpsimp"></a><a name="p6396mcpsimp"></a>Method Name and Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row6397mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p6399mcpsimp"><a name="p6399mcpsimp"></a><a name="p6399mcpsimp"></a>abstract void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p6401mcpsimp"><a name="p6401mcpsimp"></a><a name="p6401mcpsimp"></a><a href="#section1642434142613">onLocationChanged</a>(Location location)</p>
<p id="p166648349713"><a name="p166648349713"></a><a name="p166648349713"></a>Called when a user's location changes.</p>
</td>
</tr>
</tbody>
</table>

## Public Methods<a name="section22211569258"></a>

## onLocationChanged<a name="section1642434142613"></a>

<a name="table6404mcpsimp"></a>
<table><thead align="left"><tr id="row6408mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p6410mcpsimp"><a name="p6410mcpsimp"></a><a name="p6410mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row6411mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p6413mcpsimp"><a name="p6413mcpsimp"></a><a name="p6413mcpsimp"></a>public abstract void onLocationChanged(Location location)</p>
<p id="p6416mcpsimp"><a name="p6416mcpsimp"></a><a name="p6416mcpsimp"></a>Called when a user's location changes.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table6419mcpsimp"></a>
<table><thead align="left"><tr id="row6424mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p6426mcpsimp"><a name="p6426mcpsimp"></a><a name="p6426mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p6428mcpsimp"><a name="p6428mcpsimp"></a><a name="p6428mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row6429mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p6431mcpsimp"><a name="p6431mcpsimp"></a><a name="p6431mcpsimp"></a>location</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p6433mcpsimp"><a name="p6433mcpsimp"></a><a name="p6433mcpsimp"></a>Location information.</p>
</td>
</tr>
</tbody>
</table>

