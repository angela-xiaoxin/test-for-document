# UrlTileProvider<a name="EN-US_TOPIC_0000001145541093"></a>

-   [Public Constructor Summary](#section1332411442318)
-   [Public Method Summary](#section20527104442413)
-   [Public Constructors](#section042681119126)
-   [UrlTileProvider](#section147561345184912)
-   [Public Methods](#section145661338151517)
-   [getTile](#section12624550181514)
-   [getTileUrl](#section473164110165)


<a name="table23871mcpsimp"></a>
<table><thead align="left"><tr id="row23875mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p23877mcpsimp"><a name="p23877mcpsimp"></a><a name="p23877mcpsimp"></a>Class Info</p>
</th>
</tr>
</thead>
<tbody><tr id="row23878mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p520151915459"><a name="p520151915459"></a><a name="p520151915459"></a>public abstract class UrlTileProvider</p>
<p id="p192920519317"><a name="p192920519317"></a><a name="p192920519317"></a>Defines the provider of <a href="tileoverlay.md">TileOverlay</a> that requires a URL pointing to an image.</p>
<div class="caution" id="note87101434411"><a name="note87101434411"></a><a name="note87101434411"></a><span class="cautiontitle"> CAUTION: </span><div class="cautionbody"><p id="p671011314415"><a name="p671011314415"></a><a name="p671011314415"></a>When using this class, ensure that all images have the same dimensions.</p>
</div></div>
</td>
</tr>
</tbody>
</table>

## Public Constructor Summary<a name="section1332411442318"></a>

<a name="table23884mcpsimp"></a>
<table><thead align="left"><tr id="row23888mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p145mcpsimp"><a name="p145mcpsimp"></a><a name="p145mcpsimp"></a>Constructor Name</p>
</th>
</tr>
</thead>
<tbody><tr id="row23891mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p23893mcpsimp"><a name="p23893mcpsimp"></a><a name="p23893mcpsimp"></a><a href="#section147561345184912">UrlTileProvider</a>(int width, int height)</p>
<p id="p49020187144"><a name="p49020187144"></a><a name="p49020187144"></a>Creates a <a href="urltileprovider.md">UrlTileProvider</a> object based on specified parameters.</p>
</td>
</tr>
</tbody>
</table>

## Public Method Summary<a name="section20527104442413"></a>

<a name="table23895mcpsimp"></a>
<table><thead align="left"><tr id="row23900mcpsimp"><th class="cellrowborder" valign="top" width="40%" id="mcps1.1.3.1.1"><p id="p770950204210"><a name="p770950204210"></a><a name="p770950204210"></a>Qualifier and Type</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.1.3.1.2"><p id="p270650134216"><a name="p270650134216"></a><a name="p270650134216"></a>Method Name and Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row23905mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p23907mcpsimp"><a name="p23907mcpsimp"></a><a name="p23907mcpsimp"></a>final <a href="tile.md">Tile</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p23909mcpsimp"><a name="p23909mcpsimp"></a><a name="p23909mcpsimp"></a><a href="#section12624550181514">getTile</a>(int x, int y, int zoom)</p>
<p id="p8798192544010"><a name="p8798192544010"></a><a name="p8798192544010"></a>Obtains a <strong id="b129711343400"><a name="b129711343400"></a><a name="b129711343400"></a>Tile</strong> object with the specified coordinates and zoom level.</p>
</td>
</tr>
<tr id="row23910mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p23912mcpsimp"><a name="p23912mcpsimp"></a><a name="p23912mcpsimp"></a>abstract URL</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p23914mcpsimp"><a name="p23914mcpsimp"></a><a name="p23914mcpsimp"></a><a href="#section473164110165">getTileUrl</a>(int x, int y, int zoom)</p>
<p id="p685742617403"><a name="p685742617403"></a><a name="p685742617403"></a>Obtains the URL of an image to be used at the specified tile coordinates.</p>
</td>
</tr>
</tbody>
</table>

## Public Constructors<a name="section042681119126"></a>

## UrlTileProvider<a name="section147561345184912"></a>

<a name="table227mcpsimp"></a>
<table><thead align="left"><tr id="row231mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p233mcpsimp"><a name="p233mcpsimp"></a><a name="p233mcpsimp"></a>Constructor</p>
</th>
</tr>
</thead>
<tbody><tr id="row235mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p208421950803"><a name="p208421950803"></a><a name="p208421950803"></a>public <a href="urltileprovider.md">UrlTileProvider</a>(int width, int height)</p>
<p id="p12842185017015"><a name="p12842185017015"></a><a name="p12842185017015"></a>Creates a <a href="urltileprovider.md">UrlTileProvider</a> object based on specified parameters.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table243mcpsimp"></a>
<table><thead align="left"><tr id="row248mcpsimp"><th class="cellrowborder" valign="top" width="43%" id="mcps1.1.3.1.1"><p id="p250mcpsimp"><a name="p250mcpsimp"></a><a name="p250mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="56.99999999999999%" id="mcps1.1.3.1.2"><p id="p253mcpsimp"><a name="p253mcpsimp"></a><a name="p253mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row255mcpsimp"><td class="cellrowborder" valign="top" width="43%" headers="mcps1.1.3.1.1 "><p id="p6815182565014"><a name="p6815182565014"></a><a name="p6815182565014"></a>width</p>
</td>
<td class="cellrowborder" valign="top" width="56.99999999999999%" headers="mcps1.1.3.1.2 "><p id="p181418256500"><a name="p181418256500"></a><a name="p181418256500"></a>Image width.</p>
</td>
</tr>
<tr id="row05001713362"><td class="cellrowborder" valign="top" width="43%" headers="mcps1.1.3.1.1 "><p id="p18813925125011"><a name="p18813925125011"></a><a name="p18813925125011"></a>height</p>
</td>
<td class="cellrowborder" valign="top" width="56.99999999999999%" headers="mcps1.1.3.1.2 "><p id="p1179492535016"><a name="p1179492535016"></a><a name="p1179492535016"></a>Image height.</p>
</td>
</tr>
</tbody>
</table>

## Public Methods<a name="section145661338151517"></a>

## getTile<a name="section12624550181514"></a>

<a name="table23917mcpsimp"></a>
<table><thead align="left"><tr id="row23921mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p23923mcpsimp"><a name="p23923mcpsimp"></a><a name="p23923mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row23924mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p23926mcpsimp"><a name="p23926mcpsimp"></a><a name="p23926mcpsimp"></a>public final Tile getTile(int x, int y, int zoom)</p>
<p id="p23929mcpsimp"><a name="p23929mcpsimp"></a><a name="p23929mcpsimp"></a>Obtains a <strong id="b79891341522"><a name="b79891341522"></a><a name="b79891341522"></a>Tile</strong> object with the specified coordinates and zoom level.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table23932mcpsimp"></a>
<table><thead align="left"><tr id="row23937mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p23939mcpsimp"><a name="p23939mcpsimp"></a><a name="p23939mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p23941mcpsimp"><a name="p23941mcpsimp"></a><a name="p23941mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row23942mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p23944mcpsimp"><a name="p23944mcpsimp"></a><a name="p23944mcpsimp"></a>x</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p23946mcpsimp"><a name="p23946mcpsimp"></a><a name="p23946mcpsimp"></a>X coordinate of a tile. The value ranges from 0 to 2<sup id="sup23947mcpsimp"><a name="sup23947mcpsimp"></a><a name="sup23947mcpsimp"></a>zoom</sup> minus 1.</p>
</td>
</tr>
<tr id="row23948mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p23950mcpsimp"><a name="p23950mcpsimp"></a><a name="p23950mcpsimp"></a>y</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p23952mcpsimp"><a name="p23952mcpsimp"></a><a name="p23952mcpsimp"></a>Y coordinate of a tile. The value ranges from 0 to 2<sup id="sup23953mcpsimp"><a name="sup23953mcpsimp"></a><a name="sup23953mcpsimp"></a>zoom</sup> minus 1.</p>
</td>
</tr>
<tr id="row23954mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p23956mcpsimp"><a name="p23956mcpsimp"></a><a name="p23956mcpsimp"></a>zoom</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p23958mcpsimp"><a name="p23958mcpsimp"></a><a name="p23958mcpsimp"></a>Zoom level of a tile. To obtain the value range, call the <a href="huaweimap.md#section15491181135412">getMinZoomLevel</a><strong id="b1947236175314"><a name="b1947236175314"></a><a name="b1947236175314"></a>()</strong> and <a href="huaweimap.md#section10176115075312">getMaxZoomLevel</a><strong id="b64771561534"><a name="b64771561534"></a><a name="b64771561534"></a>()</strong> methods in the <a href="huaweimap.md">HuaweiMap</a> class.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table23961mcpsimp"></a>
<table><thead align="left"><tr id="row23966mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p23968mcpsimp"><a name="p23968mcpsimp"></a><a name="p23968mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p23970mcpsimp"><a name="p23970mcpsimp"></a><a name="p23970mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row23971mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p23973mcpsimp"><a name="p23973mcpsimp"></a><a name="p23973mcpsimp"></a>Tile</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p23975mcpsimp"><a name="p23975mcpsimp"></a><a name="p23975mcpsimp"></a><a href="tile.md">Tile</a> object with the specified coordinates and zoom level.</p>
</td>
</tr>
</tbody>
</table>

## getTileUrl<a name="section473164110165"></a>

<a name="table23977mcpsimp"></a>
<table><thead align="left"><tr id="row23981mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p23983mcpsimp"><a name="p23983mcpsimp"></a><a name="p23983mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row23984mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p23986mcpsimp"><a name="p23986mcpsimp"></a><a name="p23986mcpsimp"></a>public abstract URL getTileUrl(int x, int y, int zoom)</p>
<p id="p1234154161619"><a name="p1234154161619"></a><a name="p1234154161619"></a>Obtains the URL of an image to be used at the specified tile coordinates.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table23992mcpsimp"></a>
<table><thead align="left"><tr id="row23997mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p23999mcpsimp"><a name="p23999mcpsimp"></a><a name="p23999mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p24001mcpsimp"><a name="p24001mcpsimp"></a><a name="p24001mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row24002mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p24004mcpsimp"><a name="p24004mcpsimp"></a><a name="p24004mcpsimp"></a>x</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p24006mcpsimp"><a name="p24006mcpsimp"></a><a name="p24006mcpsimp"></a>X coordinate of a tile. The value ranges from 0 to 2<sup id="sup24007mcpsimp"><a name="sup24007mcpsimp"></a><a name="sup24007mcpsimp"></a>zoom</sup> minus 1.</p>
</td>
</tr>
<tr id="row24008mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p24010mcpsimp"><a name="p24010mcpsimp"></a><a name="p24010mcpsimp"></a>y</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p24012mcpsimp"><a name="p24012mcpsimp"></a><a name="p24012mcpsimp"></a>Y coordinate of a tile. The value ranges from 0 to 2<sup id="sup24013mcpsimp"><a name="sup24013mcpsimp"></a><a name="sup24013mcpsimp"></a>zoom</sup> minus 1.</p>
</td>
</tr>
<tr id="row24014mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p24016mcpsimp"><a name="p24016mcpsimp"></a><a name="p24016mcpsimp"></a>zoom</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p24018mcpsimp"><a name="p24018mcpsimp"></a><a name="p24018mcpsimp"></a>Zoom level of a tile. To obtain the value range, call the <a href="huaweimap.md#section15491181135412">getMinZoomLevel</a><strong id="b1262111491472"><a name="b1262111491472"></a><a name="b1262111491472"></a>()</strong> and <a href="huaweimap.md#section10176115075312">getMaxZoomLevel</a><strong id="b1225823725316"><a name="b1225823725316"></a><a name="b1225823725316"></a>()</strong> methods in the <a href="huaweimap.md">HuaweiMap</a> class.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table24021mcpsimp"></a>
<table><thead align="left"><tr id="row24026mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p24028mcpsimp"><a name="p24028mcpsimp"></a><a name="p24028mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p24030mcpsimp"><a name="p24030mcpsimp"></a><a name="p24030mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row24031mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p24033mcpsimp"><a name="p24033mcpsimp"></a><a name="p24033mcpsimp"></a>URL</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p24035mcpsimp"><a name="p24035mcpsimp"></a><a name="p24035mcpsimp"></a>URL of the image to be used at the specified tile coordinates.</p>
</td>
</tr>
</tbody>
</table>

