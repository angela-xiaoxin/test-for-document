# Tile<a name="EN-US_TOPIC_0000001145941043"></a>

-   [Public Field Summary](#section107794408208)
-   [Public Constructor Summary](#section149241752192016)
-   [Public Method Summary](#section4648166112114)
-   [Public Constructors](#section042681119126)
-   [Tile](#section147561345184912)


<a name="table22666mcpsimp"></a>
<table><thead align="left"><tr id="row22670mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p22672mcpsimp"><a name="p22672mcpsimp"></a><a name="p22672mcpsimp"></a>Class Info</p>
</th>
</tr>
</thead>
<tbody><tr id="row22673mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p142272720449"><a name="p142272720449"></a><a name="p142272720449"></a>public class Tile</p>
<p id="p22675mcpsimp"><a name="p22675mcpsimp"></a><a name="p22675mcpsimp"></a>Defines the minimum unit of a <a href="tileoverlay.md">TileOverlay</a> object. To create a <a href="tile.md">Tile</a> object, call the <a href="tileprovider.md#section44133551418">getTile</a> method of <a href="tileprovider.md">TileProvider</a>.</p>
</td>
</tr>
</tbody>
</table>

## Public Field Summary<a name="section107794408208"></a>

<a name="table51207528357"></a>
<table><thead align="left"><tr id="row6121185283516"><th class="cellrowborder" valign="top" width="32.21%" id="mcps1.1.3.1.1"><p id="p1528164471414"><a name="p1528164471414"></a><a name="p1528164471414"></a>Qualifier and Type</p>
</th>
<th class="cellrowborder" valign="top" width="67.78999999999999%" id="mcps1.1.3.1.2"><p id="p1554614158108"><a name="p1554614158108"></a><a name="p1554614158108"></a>Field and Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row2012119527357"><td class="cellrowborder" valign="top" width="32.21%" headers="mcps1.1.3.1.1 "><p id="p5688125314712"><a name="p5688125314712"></a><a name="p5688125314712"></a>byte[]</p>
</td>
<td class="cellrowborder" valign="top" width="67.78999999999999%" headers="mcps1.1.3.1.2 "><p id="p104318562711"><a name="p104318562711"></a><a name="p104318562711"></a>data</p>
<p id="p717374811714"><a name="p717374811714"></a><a name="p717374811714"></a>A byte array containing image data. To create the image, call the <strong id="b8183134016418"><a name="b8183134016418"></a><a name="b8183134016418"></a>decodeByteArray(byte[], int, int)</strong> method in the <strong id="b91891440134110"><a name="b91891440134110"></a><a name="b91891440134110"></a>BitmapFactory</strong> class.</p>
</td>
</tr>
<tr id="row8965818847"><td class="cellrowborder" valign="top" width="32.21%" headers="mcps1.1.3.1.1 "><p id="p136889531076"><a name="p136889531076"></a><a name="p136889531076"></a>int</p>
</td>
<td class="cellrowborder" valign="top" width="67.78999999999999%" headers="mcps1.1.3.1.2 "><p id="p6268591778"><a name="p6268591778"></a><a name="p6268591778"></a>height</p>
<p id="p151732485712"><a name="p151732485712"></a><a name="p151732485712"></a>Height of a tile, in pixels.</p>
</td>
</tr>
<tr id="row07121437164"><td class="cellrowborder" valign="top" width="32.21%" headers="mcps1.1.3.1.1 "><p id="p7688105310711"><a name="p7688105310711"></a><a name="p7688105310711"></a>int</p>
</td>
<td class="cellrowborder" valign="top" width="67.78999999999999%" headers="mcps1.1.3.1.2 "><p id="p9686151787"><a name="p9686151787"></a><a name="p9686151787"></a>width</p>
<p id="p191735481775"><a name="p191735481775"></a><a name="p191735481775"></a>Width of a tile, in pixels.</p>
</td>
</tr>
</tbody>
</table>

## Public Constructor Summary<a name="section149241752192016"></a>

<a name="table22712mcpsimp"></a>
<table><thead align="left"><tr id="row22716mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p145mcpsimp"><a name="p145mcpsimp"></a><a name="p145mcpsimp"></a>Constructor Name</p>
</th>
</tr>
</thead>
<tbody><tr id="row22719mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p22721mcpsimp"><a name="p22721mcpsimp"></a><a name="p22721mcpsimp"></a><a href="#section147561345184912">Tile</a>(int width, int height, byte[] data)</p>
<p id="p175481651151310"><a name="p175481651151310"></a><a name="p175481651151310"></a>Creates a <a href="tile.md">Tile</a> object based on specified parameters.</p>
</td>
</tr>
</tbody>
</table>

## Public Method Summary<a name="section4648166112114"></a>

<a name="table22723mcpsimp"></a>
<table><thead align="left"><tr id="row22728mcpsimp"><th class="cellrowborder" valign="top" width="40%" id="mcps1.1.3.1.1"><p id="p081120285386"><a name="p081120285386"></a><a name="p081120285386"></a>Qualifier and Type</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.1.3.1.2"><p id="p681112883813"><a name="p681112883813"></a><a name="p681112883813"></a>Method Name and Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row9127105811466"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p14897161311392"><a name="p14897161311392"></a><a name="p14897161311392"></a>int</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p1926711416459"><a name="p1926711416459"></a><a name="p1926711416459"></a>describeContents()</p>
<p id="p73411918172310"><a name="p73411918172310"></a><a name="p73411918172310"></a>Returns the description of the current object. By default, <strong id="b1720882763013"><a name="b1720882763013"></a><a name="b1720882763013"></a>0</strong> is returned.</p>
</td>
</tr>
<tr id="row22733mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p22735mcpsimp"><a name="p22735mcpsimp"></a><a name="p22735mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p22737mcpsimp"><a name="p22737mcpsimp"></a><a name="p22737mcpsimp"></a>writeToParcel(Parcel out, int flags)</p>
<p id="p17304151014217"><a name="p17304151014217"></a><a name="p17304151014217"></a>Serializes data.</p>
</td>
</tr>
</tbody>
</table>

## Public Constructors<a name="section042681119126"></a>

## Tile<a name="section147561345184912"></a>

<a name="table227mcpsimp"></a>
<table><thead align="left"><tr id="row231mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p233mcpsimp"><a name="p233mcpsimp"></a><a name="p233mcpsimp"></a>Constructor</p>
</th>
</tr>
</thead>
<tbody><tr id="row235mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p18724346195710"><a name="p18724346195710"></a><a name="p18724346195710"></a>public <a href="tile.md">Tile</a>(int width, int height, byte[] data)</p>
<p id="p127243462579"><a name="p127243462579"></a><a name="p127243462579"></a>Creates a <a href="tile.md">Tile</a> object based on specified parameters.</p>
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
<td class="cellrowborder" valign="top" width="56.99999999999999%" headers="mcps1.1.3.1.2 "><p id="p181418256500"><a name="p181418256500"></a><a name="p181418256500"></a>Width of a tile, in pixels.</p>
</td>
</tr>
<tr id="row05001713362"><td class="cellrowborder" valign="top" width="43%" headers="mcps1.1.3.1.1 "><p id="p18813925125011"><a name="p18813925125011"></a><a name="p18813925125011"></a>height</p>
</td>
<td class="cellrowborder" valign="top" width="56.99999999999999%" headers="mcps1.1.3.1.2 "><p id="p1179492535016"><a name="p1179492535016"></a><a name="p1179492535016"></a>Height of a tile, in pixels.</p>
</td>
</tr>
<tr id="row145614418544"><td class="cellrowborder" valign="top" width="43%" headers="mcps1.1.3.1.1 "><p id="p1557541135414"><a name="p1557541135414"></a><a name="p1557541135414"></a>data</p>
</td>
<td class="cellrowborder" valign="top" width="56.99999999999999%" headers="mcps1.1.3.1.2 "><p id="p3571341175417"><a name="p3571341175417"></a><a name="p3571341175417"></a>A byte array containing image data. To create the image, call the <strong id="b7366034193115"><a name="b7366034193115"></a><a name="b7366034193115"></a>decodeByteArray(byte[], int, int)</strong> method in the <strong id="b837233463120"><a name="b837233463120"></a><a name="b837233463120"></a>BitmapFactory</strong> class.</p>
</td>
</tr>
</tbody>
</table>

