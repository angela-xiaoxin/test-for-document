# TileProvider<a name="EN-US_TOPIC_0000001099661066"></a>

-   [Public Field Summary](#section33714371221)
-   [Public Method Summary](#section115896593222)
-   [Public Methods](#section5558161411146)
-   [getTile](#section44133551418)


<a name="table23760mcpsimp"></a>
<table><thead align="left"><tr id="row23764mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p23766mcpsimp"><a name="p23766mcpsimp"></a><a name="p23766mcpsimp"></a>Interface Info</p>
</th>
</tr>
</thead>
<tbody><tr id="row23767mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p654515954510"><a name="p654515954510"></a><a name="p654515954510"></a>public interface TileProvider</p>
<p id="p23769mcpsimp"><a name="p23769mcpsimp"></a><a name="p23769mcpsimp"></a>Provides tile images for <a href="tileoverlay.md">TileOverlay</a>. The method in this API may be called from multiple threads. Therefore, you must ensure the thread safety when implementing this API.</p>
</td>
</tr>
</tbody>
</table>

## Public Field Summary<a name="section33714371221"></a>

<a name="table51207528357"></a>
<table><thead align="left"><tr id="row6121185283516"><th class="cellrowborder" valign="top" width="32.21%" id="mcps1.1.3.1.1"><p id="p1528164471414"><a name="p1528164471414"></a><a name="p1528164471414"></a>Qualifier and Type</p>
</th>
<th class="cellrowborder" valign="top" width="67.78999999999999%" id="mcps1.1.3.1.2"><p id="p1554614158108"><a name="p1554614158108"></a><a name="p1554614158108"></a>Field and Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row2012119527357"><td class="cellrowborder" valign="top" width="32.21%" headers="mcps1.1.3.1.1 "><p id="p5688125314712"><a name="p5688125314712"></a><a name="p5688125314712"></a>public static final <a href="tile.md">Tile</a></p>
</td>
<td class="cellrowborder" valign="top" width="67.78999999999999%" headers="mcps1.1.3.1.2 "><p id="p2012213361583"><a name="p2012213361583"></a><a name="p2012213361583"></a>NO_TILE</p>
<p id="p717374811714"><a name="p717374811714"></a><a name="p717374811714"></a>Special tile used to indicate that no tile is available at the specified coordinates.</p>
</td>
</tr>
</tbody>
</table>

## Public Method Summary<a name="section115896593222"></a>

<a name="table23794mcpsimp"></a>
<table><thead align="left"><tr id="row23799mcpsimp"><th class="cellrowborder" valign="top" width="40%" id="mcps1.1.3.1.1"><p id="p081120285386"><a name="p081120285386"></a><a name="p081120285386"></a>Qualifier and Type</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.1.3.1.2"><p id="p681112883813"><a name="p681112883813"></a><a name="p681112883813"></a>Method Name and Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row23804mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p23806mcpsimp"><a name="p23806mcpsimp"></a><a name="p23806mcpsimp"></a>abstract  <a href="tile.md">Tile</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p23808mcpsimp"><a name="p23808mcpsimp"></a><a name="p23808mcpsimp"></a><a href="#section44133551418">getTile</a>(int x, int y, int zoom)</p>
<p id="p844818274266"><a name="p844818274266"></a><a name="p844818274266"></a>Obtains a <strong id="b91343250142"><a name="b91343250142"></a><a name="b91343250142"></a>Tile</strong> object with the specified coordinates and zoom level.</p>
</td>
</tr>
</tbody>
</table>

## Public Methods<a name="section5558161411146"></a>

## getTile<a name="section44133551418"></a>

<a name="table23811mcpsimp"></a>
<table><thead align="left"><tr id="row23815mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p23817mcpsimp"><a name="p23817mcpsimp"></a><a name="p23817mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row23818mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p16563144116369"><a name="p16563144116369"></a><a name="p16563144116369"></a>public abstract Tile getTile(int x, int y, int zoom)</p>
<p id="p1816074531412"><a name="p1816074531412"></a><a name="p1816074531412"></a>Obtains a <strong id="b1940720410811"><a name="b1940720410811"></a><a name="b1940720410811"></a>Tile</strong> object with the specified coordinates and zoom level.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table23826mcpsimp"></a>
<table><thead align="left"><tr id="row23831mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p23833mcpsimp"><a name="p23833mcpsimp"></a><a name="p23833mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p23835mcpsimp"><a name="p23835mcpsimp"></a><a name="p23835mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row23836mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p23838mcpsimp"><a name="p23838mcpsimp"></a><a name="p23838mcpsimp"></a>x</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p23840mcpsimp"><a name="p23840mcpsimp"></a><a name="p23840mcpsimp"></a>X coordinate of a tile. The value ranges from 0 to 2<sup id="sup23841mcpsimp"><a name="sup23841mcpsimp"></a><a name="sup23841mcpsimp"></a>zoom</sup> minus 1.</p>
</td>
</tr>
<tr id="row23842mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p23844mcpsimp"><a name="p23844mcpsimp"></a><a name="p23844mcpsimp"></a>y</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p23846mcpsimp"><a name="p23846mcpsimp"></a><a name="p23846mcpsimp"></a>Y coordinate of a tile. The value ranges from 0 to 2<sup id="sup23847mcpsimp"><a name="sup23847mcpsimp"></a><a name="sup23847mcpsimp"></a>zoom</sup> minus 1.</p>
</td>
</tr>
<tr id="row23848mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p23850mcpsimp"><a name="p23850mcpsimp"></a><a name="p23850mcpsimp"></a>zoom</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p23852mcpsimp"><a name="p23852mcpsimp"></a><a name="p23852mcpsimp"></a>Zoom level of a tile. To obtain the value range, call the <a href="huaweimap.md#section15491181135412">getMinZoomLevel</a><strong id="b12738195911820"><a name="b12738195911820"></a><a name="b12738195911820"></a>()</strong> and <a href="huaweimap.md#section10176115075312">getMaxZoomLevel</a><strong id="b774519599820"><a name="b774519599820"></a><a name="b774519599820"></a>()</strong> methods in the <a href="huaweimap.md">HuaweiMap</a> class.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table23855mcpsimp"></a>
<table><thead align="left"><tr id="row23860mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p23862mcpsimp"><a name="p23862mcpsimp"></a><a name="p23862mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p23864mcpsimp"><a name="p23864mcpsimp"></a><a name="p23864mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row23865mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p23867mcpsimp"><a name="p23867mcpsimp"></a><a name="p23867mcpsimp"></a>Tile</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p23869mcpsimp"><a name="p23869mcpsimp"></a><a name="p23869mcpsimp"></a><a href="tile.md">Tile</a> object with the specified coordinates and zoom level.</p>
</td>
</tr>
</tbody>
</table>

