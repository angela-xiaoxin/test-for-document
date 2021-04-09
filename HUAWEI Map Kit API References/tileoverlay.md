# TileOverlay<a name="EN-US_TOPIC_0000001099341092"></a>

-   [Public Method Summary](#section10604204117213)
-   [Public Methods](#section138021539145820)
-   [clearTileCache](#section1976495145817)
-   [equals](#section15108202995916)
-   [getFadeIn](#section1795437900)
-   [getId](#section42720526014)
-   [getTransparency](#section382417241813)
-   [getZIndex](#section1740420531818)
-   [hashCode](#section1079617226216)
-   [isVisible](#section1718157628)
-   [remove](#section354412291830)
-   [setFadeIn](#section9414160649)
-   [setTransparency](#section10412133211419)
-   [setVisible](#section933417218519)
-   [setZIndex](#section182617531253)


<a name="table22739mcpsimp"></a>
<table><thead align="left"><tr id="row22743mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p22745mcpsimp"><a name="p22745mcpsimp"></a><a name="p22745mcpsimp"></a>Class Info</p>
</th>
</tr>
</thead>
<tbody><tr id="row22746mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p1295534024415"><a name="p1295534024415"></a><a name="p1295534024415"></a>public final class TileOverlay</p>
<p id="p22748mcpsimp"><a name="p22748mcpsimp"></a><a name="p22748mcpsimp"></a>Represents a tile overlay. A tile overlay is a set of images to be displayed on a map. It can be transparent and enable you to add new functions to an existing map. An instance of this type will be returned when the <a href="huaweimap.md#section12241957204519">addTileOverlay</a> method in the <a href="huaweimap.md">HuaweiMap</a> class is called.</p>
</td>
</tr>
</tbody>
</table>

## Public Method Summary<a name="section10604204117213"></a>

<a name="table22754mcpsimp"></a>
<table><thead align="left"><tr id="row22759mcpsimp"><th class="cellrowborder" valign="top" width="40%" id="mcps1.1.3.1.1"><p id="p081120285386"><a name="p081120285386"></a><a name="p081120285386"></a>Qualifier and Type</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.1.3.1.2"><p id="p681112883813"><a name="p681112883813"></a><a name="p681112883813"></a>Method Name and Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row22764mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p22766mcpsimp"><a name="p22766mcpsimp"></a><a name="p22766mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p22768mcpsimp"><a name="p22768mcpsimp"></a><a name="p22768mcpsimp"></a><a href="#section1976495145817">clearTileCache</a>()</p>
<p id="p152726863413"><a name="p152726863413"></a><a name="p152726863413"></a>Clears the cache of a tile overlay.</p>
</td>
</tr>
<tr id="row22769mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p22771mcpsimp"><a name="p22771mcpsimp"></a><a name="p22771mcpsimp"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p22773mcpsimp"><a name="p22773mcpsimp"></a><a name="p22773mcpsimp"></a><a href="#section15108202995916">equals</a>(Object other)</p>
<p id="p1051579193413"><a name="p1051579193413"></a><a name="p1051579193413"></a>Checks whether a tile overlay object equals another.</p>
</td>
</tr>
<tr id="row22774mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p22776mcpsimp"><a name="p22776mcpsimp"></a><a name="p22776mcpsimp"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p22778mcpsimp"><a name="p22778mcpsimp"></a><a name="p22778mcpsimp"></a><a href="#section1795437900">getFadeIn</a>()</p>
<p id="p166533107344"><a name="p166533107344"></a><a name="p166533107344"></a>Checks whether a tile overlay fades in.</p>
</td>
</tr>
<tr id="row22779mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p22781mcpsimp"><a name="p22781mcpsimp"></a><a name="p22781mcpsimp"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p22783mcpsimp"><a name="p22783mcpsimp"></a><a name="p22783mcpsimp"></a><a href="#section42720526014">getId</a>()</p>
<p id="p2078161193416"><a name="p2078161193416"></a><a name="p2078161193416"></a>Obtains the ID of a tile overlay on a map. </p>
</td>
</tr>
<tr id="row22784mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p22786mcpsimp"><a name="p22786mcpsimp"></a><a name="p22786mcpsimp"></a>float</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p22788mcpsimp"><a name="p22788mcpsimp"></a><a name="p22788mcpsimp"></a><a href="#section382417241813">getTransparency</a>()</p>
<p id="p107865126346"><a name="p107865126346"></a><a name="p107865126346"></a>Obtains the transparency of a tile overlay.</p>
</td>
</tr>
<tr id="row22789mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p22791mcpsimp"><a name="p22791mcpsimp"></a><a name="p22791mcpsimp"></a>float</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p22793mcpsimp"><a name="p22793mcpsimp"></a><a name="p22793mcpsimp"></a><a href="#section1740420531818">getZIndex</a>()</p>
<p id="p9819161313417"><a name="p9819161313417"></a><a name="p9819161313417"></a>Obtains the z-index of a tile overlay.</p>
</td>
</tr>
<tr id="row22794mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p22796mcpsimp"><a name="p22796mcpsimp"></a><a name="p22796mcpsimp"></a>int</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p22798mcpsimp"><a name="p22798mcpsimp"></a><a name="p22798mcpsimp"></a><a href="#section1079617226216">hashCode</a>()</p>
<p id="p13791191411342"><a name="p13791191411342"></a><a name="p13791191411342"></a>Obtains the hash code of a tile overlay.</p>
</td>
</tr>
<tr id="row22799mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p22801mcpsimp"><a name="p22801mcpsimp"></a><a name="p22801mcpsimp"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p22803mcpsimp"><a name="p22803mcpsimp"></a><a name="p22803mcpsimp"></a><a href="#section1718157628">isVisible</a>()</p>
<p id="p10703181533418"><a name="p10703181533418"></a><a name="p10703181533418"></a>Checks whether a tile overlay is visible.</p>
</td>
</tr>
<tr id="row22804mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p22806mcpsimp"><a name="p22806mcpsimp"></a><a name="p22806mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p22808mcpsimp"><a name="p22808mcpsimp"></a><a name="p22808mcpsimp"></a><a href="#section354412291830">remove</a>()</p>
<p id="p14524121719344"><a name="p14524121719344"></a><a name="p14524121719344"></a>Removes a tile overlay from a map.</p>
</td>
</tr>
<tr id="row22809mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p22811mcpsimp"><a name="p22811mcpsimp"></a><a name="p22811mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p22813mcpsimp"><a name="p22813mcpsimp"></a><a name="p22813mcpsimp"></a><a href="#section9414160649">setFadeIn</a>(boolean fadeIn)</p>
<p id="p16774218203419"><a name="p16774218203419"></a><a name="p16774218203419"></a>Sets whether a tile overlay fades in.</p>
</td>
</tr>
<tr id="row22814mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p22816mcpsimp"><a name="p22816mcpsimp"></a><a name="p22816mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p22818mcpsimp"><a name="p22818mcpsimp"></a><a name="p22818mcpsimp"></a><a href="#section10412133211419">setTransparency</a>(float transparency)</p>
<p id="p12920131915347"><a name="p12920131915347"></a><a name="p12920131915347"></a>Sets the transparency of a tile overlay.</p>
</td>
</tr>
<tr id="row22819mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p22821mcpsimp"><a name="p22821mcpsimp"></a><a name="p22821mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p22823mcpsimp"><a name="p22823mcpsimp"></a><a name="p22823mcpsimp"></a><a href="#section933417218519">setVisible</a>(boolean visible)</p>
<p id="p69911820133415"><a name="p69911820133415"></a><a name="p69911820133415"></a>Sets whether a tile overlay is visible.</p>
</td>
</tr>
<tr id="row22824mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p22826mcpsimp"><a name="p22826mcpsimp"></a><a name="p22826mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p22828mcpsimp"><a name="p22828mcpsimp"></a><a name="p22828mcpsimp"></a><a href="#section182617531253">setZIndex</a>(float zIndex)</p>
<p id="p32172233412"><a name="p32172233412"></a><a name="p32172233412"></a>Sets the z-index of a tile overlay.</p>
</td>
</tr>
</tbody>
</table>

## Public Methods<a name="section138021539145820"></a>

## clearTileCache<a name="section1976495145817"></a>

<a name="table22831mcpsimp"></a>
<table><thead align="left"><tr id="row22835mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p22837mcpsimp"><a name="p22837mcpsimp"></a><a name="p22837mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row22838mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p22840mcpsimp"><a name="p22840mcpsimp"></a><a name="p22840mcpsimp"></a>public void clearTileCache()</p>
<p id="p18424975913"><a name="p18424975913"></a><a name="p18424975913"></a>Clears the cache of a tile overlay.</p>
</td>
</tr>
</tbody>
</table>

## equals<a name="section15108202995916"></a>

<a name="table22851mcpsimp"></a>
<table><thead align="left"><tr id="row22855mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p22857mcpsimp"><a name="p22857mcpsimp"></a><a name="p22857mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row22858mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p22860mcpsimp"><a name="p22860mcpsimp"></a><a name="p22860mcpsimp"></a>public boolean equals(Object other)</p>
<p id="p22863mcpsimp"><a name="p22863mcpsimp"></a><a name="p22863mcpsimp"></a>Checks whether a tile overlay object equals another.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table22866mcpsimp"></a>
<table><thead align="left"><tr id="row22871mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p22873mcpsimp"><a name="p22873mcpsimp"></a><a name="p22873mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p22875mcpsimp"><a name="p22875mcpsimp"></a><a name="p22875mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row22876mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p22878mcpsimp"><a name="p22878mcpsimp"></a><a name="p22878mcpsimp"></a>other</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p22880mcpsimp"><a name="p22880mcpsimp"></a><a name="p22880mcpsimp"></a>Name of another object.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table22883mcpsimp"></a>
<table><thead align="left"><tr id="row22888mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p22890mcpsimp"><a name="p22890mcpsimp"></a><a name="p22890mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p22892mcpsimp"><a name="p22892mcpsimp"></a><a name="p22892mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row22893mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p22895mcpsimp"><a name="p22895mcpsimp"></a><a name="p22895mcpsimp"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p22897mcpsimp"><a name="p22897mcpsimp"></a><a name="p22897mcpsimp"></a><strong id="b717413169432"><a name="b717413169432"></a><a name="b717413169432"></a>true</strong> if the tile overlay objects are equal; <strong id="b20174101614311"><a name="b20174101614311"></a><a name="b20174101614311"></a>false</strong> otherwise.</p>
</td>
</tr>
</tbody>
</table>

## getFadeIn<a name="section1795437900"></a>

<a name="table22899mcpsimp"></a>
<table><thead align="left"><tr id="row22903mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p22905mcpsimp"><a name="p22905mcpsimp"></a><a name="p22905mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row22906mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p22908mcpsimp"><a name="p22908mcpsimp"></a><a name="p22908mcpsimp"></a>public boolean getFadeIn()</p>
<p id="p186425241603"><a name="p186425241603"></a><a name="p186425241603"></a>Checks whether a tile overlay fades in.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table22917mcpsimp"></a>
<table><thead align="left"><tr id="row22922mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p22924mcpsimp"><a name="p22924mcpsimp"></a><a name="p22924mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p22926mcpsimp"><a name="p22926mcpsimp"></a><a name="p22926mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row22927mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p22929mcpsimp"><a name="p22929mcpsimp"></a><a name="p22929mcpsimp"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p22931mcpsimp"><a name="p22931mcpsimp"></a><a name="p22931mcpsimp"></a><strong id="b141948558287"><a name="b141948558287"></a><a name="b141948558287"></a>true</strong> if the tile overlay fades in; <strong id="b66771012299"><a name="b66771012299"></a><a name="b66771012299"></a>false</strong> otherwise.</p>
</td>
</tr>
</tbody>
</table>

## getId<a name="section42720526014"></a>

<a name="table22933mcpsimp"></a>
<table><thead align="left"><tr id="row22937mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p22939mcpsimp"><a name="p22939mcpsimp"></a><a name="p22939mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row22940mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p22942mcpsimp"><a name="p22942mcpsimp"></a><a name="p22942mcpsimp"></a>public String getId()</p>
<p id="p22945mcpsimp"><a name="p22945mcpsimp"></a><a name="p22945mcpsimp"></a>Obtains the ID of a tile overlay on a map. The ID will be unique among all tile overlays on the map.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table22951mcpsimp"></a>
<table><thead align="left"><tr id="row22956mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p22958mcpsimp"><a name="p22958mcpsimp"></a><a name="p22958mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p22960mcpsimp"><a name="p22960mcpsimp"></a><a name="p22960mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row22961mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p22963mcpsimp"><a name="p22963mcpsimp"></a><a name="p22963mcpsimp"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p22965mcpsimp"><a name="p22965mcpsimp"></a><a name="p22965mcpsimp"></a>ID of a tile overlay.</p>
</td>
</tr>
</tbody>
</table>

## getTransparency<a name="section382417241813"></a>

<a name="table22967mcpsimp"></a>
<table><thead align="left"><tr id="row22971mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p22973mcpsimp"><a name="p22973mcpsimp"></a><a name="p22973mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row22974mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p22976mcpsimp"><a name="p22976mcpsimp"></a><a name="p22976mcpsimp"></a>public float getTransparency()</p>
<p id="p0410113714118"><a name="p0410113714118"></a><a name="p0410113714118"></a>Obtains the transparency of a tile overlay.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table22985mcpsimp"></a>
<table><thead align="left"><tr id="row22990mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p22992mcpsimp"><a name="p22992mcpsimp"></a><a name="p22992mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p22994mcpsimp"><a name="p22994mcpsimp"></a><a name="p22994mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row22995mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p22997mcpsimp"><a name="p22997mcpsimp"></a><a name="p22997mcpsimp"></a>float</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p22999mcpsimp"><a name="p22999mcpsimp"></a><a name="p22999mcpsimp"></a>Transparency of a tile overlay. The value ranges from 0 (completely opaque) to 1 (completely transparent). </p>
</td>
</tr>
</tbody>
</table>

## getZIndex<a name="section1740420531818"></a>

<a name="table23001mcpsimp"></a>
<table><thead align="left"><tr id="row23005mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p23007mcpsimp"><a name="p23007mcpsimp"></a><a name="p23007mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row23008mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p23010mcpsimp"><a name="p23010mcpsimp"></a><a name="p23010mcpsimp"></a>public float getZIndex()</p>
<p id="p19556166224"><a name="p19556166224"></a><a name="p19556166224"></a>Obtains the z-index of a tile overlay.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table23019mcpsimp"></a>
<table><thead align="left"><tr id="row23024mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p23026mcpsimp"><a name="p23026mcpsimp"></a><a name="p23026mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p23028mcpsimp"><a name="p23028mcpsimp"></a><a name="p23028mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row23029mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p23031mcpsimp"><a name="p23031mcpsimp"></a><a name="p23031mcpsimp"></a>float</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p23033mcpsimp"><a name="p23033mcpsimp"></a><a name="p23033mcpsimp"></a>Z-index, which indicates the overlapping order of a tile overlay.</p>
</td>
</tr>
</tbody>
</table>

## hashCode<a name="section1079617226216"></a>

<a name="table23035mcpsimp"></a>
<table><thead align="left"><tr id="row23039mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p23041mcpsimp"><a name="p23041mcpsimp"></a><a name="p23041mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row23042mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p23044mcpsimp"><a name="p23044mcpsimp"></a><a name="p23044mcpsimp"></a>public int hashCode()</p>
<p id="p6884740326"><a name="p6884740326"></a><a name="p6884740326"></a>Obtains the hash code of a tile overlay.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table23053mcpsimp"></a>
<table><thead align="left"><tr id="row23058mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p23060mcpsimp"><a name="p23060mcpsimp"></a><a name="p23060mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p23062mcpsimp"><a name="p23062mcpsimp"></a><a name="p23062mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row23063mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p23065mcpsimp"><a name="p23065mcpsimp"></a><a name="p23065mcpsimp"></a>int</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p23067mcpsimp"><a name="p23067mcpsimp"></a><a name="p23067mcpsimp"></a>Hash code of a tile overlay.</p>
</td>
</tr>
</tbody>
</table>

## isVisible<a name="section1718157628"></a>

<a name="table23069mcpsimp"></a>
<table><thead align="left"><tr id="row23073mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p23075mcpsimp"><a name="p23075mcpsimp"></a><a name="p23075mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row23076mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p23078mcpsimp"><a name="p23078mcpsimp"></a><a name="p23078mcpsimp"></a>public boolean isVisible()</p>
<p id="p23081mcpsimp"><a name="p23081mcpsimp"></a><a name="p23081mcpsimp"></a>Checks whether a tile overlay is visible.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table23087mcpsimp"></a>
<table><thead align="left"><tr id="row23092mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p23094mcpsimp"><a name="p23094mcpsimp"></a><a name="p23094mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p23096mcpsimp"><a name="p23096mcpsimp"></a><a name="p23096mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row23097mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p23099mcpsimp"><a name="p23099mcpsimp"></a><a name="p23099mcpsimp"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p23101mcpsimp"><a name="p23101mcpsimp"></a><a name="p23101mcpsimp"></a><strong id="b188623411451"><a name="b188623411451"></a><a name="b188623411451"></a>true</strong> if the tile overlay is visible; <strong id="b086214464510"><a name="b086214464510"></a><a name="b086214464510"></a>false</strong> otherwise.</p>
</td>
</tr>
</tbody>
</table>

## remove<a name="section354412291830"></a>

<a name="table23103mcpsimp"></a>
<table><thead align="left"><tr id="row23107mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p23109mcpsimp"><a name="p23109mcpsimp"></a><a name="p23109mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row23110mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p23112mcpsimp"><a name="p23112mcpsimp"></a><a name="p23112mcpsimp"></a>public void remove()</p>
<p id="p23115mcpsimp"><a name="p23115mcpsimp"></a><a name="p23115mcpsimp"></a>Removes a tile overlay from a map.</p>
</td>
</tr>
</tbody>
</table>

## setFadeIn<a name="section9414160649"></a>

<a name="table23123mcpsimp"></a>
<table><thead align="left"><tr id="row23127mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p23129mcpsimp"><a name="p23129mcpsimp"></a><a name="p23129mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row23130mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p23132mcpsimp"><a name="p23132mcpsimp"></a><a name="p23132mcpsimp"></a>public void setFadeIn(boolean fadeIn)</p>
<p id="p23135mcpsimp"><a name="p23135mcpsimp"></a><a name="p23135mcpsimp"></a>Sets whether a tile overlay fades in.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table23138mcpsimp"></a>
<table><thead align="left"><tr id="row23143mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p23145mcpsimp"><a name="p23145mcpsimp"></a><a name="p23145mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p23147mcpsimp"><a name="p23147mcpsimp"></a><a name="p23147mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row23148mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p23150mcpsimp"><a name="p23150mcpsimp"></a><a name="p23150mcpsimp"></a>fadeIn</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p9682161852011"><a name="p9682161852011"></a><a name="p9682161852011"></a>Indicates whether a tile overlay fades in. The options are <strong id="b179411257131714"><a name="b179411257131714"></a><a name="b179411257131714"></a>true</strong> (yes) and <strong id="b875818017184"><a name="b875818017184"></a><a name="b875818017184"></a>false</strong> (no). The default value is <strong id="b136167261814"><a name="b136167261814"></a><a name="b136167261814"></a>true</strong>.</p>
</td>
</tr>
</tbody>
</table>

## setTransparency<a name="section10412133211419"></a>

<a name="table23157mcpsimp"></a>
<table><thead align="left"><tr id="row23161mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p23163mcpsimp"><a name="p23163mcpsimp"></a><a name="p23163mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row23164mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p23166mcpsimp"><a name="p23166mcpsimp"></a><a name="p23166mcpsimp"></a>public void setTransparency(float transparency)</p>
<p id="p23169mcpsimp"><a name="p23169mcpsimp"></a><a name="p23169mcpsimp"></a>Sets the transparency of a tile overlay.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table23172mcpsimp"></a>
<table><thead align="left"><tr id="row23177mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p23179mcpsimp"><a name="p23179mcpsimp"></a><a name="p23179mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p23181mcpsimp"><a name="p23181mcpsimp"></a><a name="p23181mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row23182mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p23184mcpsimp"><a name="p23184mcpsimp"></a><a name="p23184mcpsimp"></a>transparency</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p23186mcpsimp"><a name="p23186mcpsimp"></a><a name="p23186mcpsimp"></a>Transparency of a tile overlay. The value ranges from 0 (completely opaque) to 1 (completely transparent). The default value is <strong id="b93671135982"><a name="b93671135982"></a><a name="b93671135982"></a>0</strong>.</p>
</td>
</tr>
</tbody>
</table>

## setVisible<a name="section933417218519"></a>

<a name="table23191mcpsimp"></a>
<table><thead align="left"><tr id="row23195mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p23197mcpsimp"><a name="p23197mcpsimp"></a><a name="p23197mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row23198mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p23200mcpsimp"><a name="p23200mcpsimp"></a><a name="p23200mcpsimp"></a>public void setVisible(boolean visible)</p>
<p id="p23203mcpsimp"><a name="p23203mcpsimp"></a><a name="p23203mcpsimp"></a>Sets whether a tile overlay is visible. If the tile overlay is invisible, it will not be drawn but all other states will be preserved. By default, a tile overlay is visible.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table23206mcpsimp"></a>
<table><thead align="left"><tr id="row23211mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p23213mcpsimp"><a name="p23213mcpsimp"></a><a name="p23213mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p23215mcpsimp"><a name="p23215mcpsimp"></a><a name="p23215mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row23216mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p23218mcpsimp"><a name="p23218mcpsimp"></a><a name="p23218mcpsimp"></a>visible</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p23220mcpsimp"><a name="p23220mcpsimp"></a><a name="p23220mcpsimp"></a>Indicates whether a tile overlay is visible. <strong id="b225032612469"><a name="b225032612469"></a><a name="b225032612469"></a>true</strong>: yes; <strong id="b125619268467"><a name="b125619268467"></a><a name="b125619268467"></a>false</strong>: no. The default value is <strong id="b148491933989"><a name="b148491933989"></a><a name="b148491933989"></a>true</strong>.</p>
</td>
</tr>
</tbody>
</table>

## setZIndex<a name="section182617531253"></a>

<a name="table23225mcpsimp"></a>
<table><thead align="left"><tr id="row23229mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p23231mcpsimp"><a name="p23231mcpsimp"></a><a name="p23231mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row23232mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p23234mcpsimp"><a name="p23234mcpsimp"></a><a name="p23234mcpsimp"></a>public void setZIndex(float zIndex)</p>
<p id="p14391845756"><a name="p14391845756"></a><a name="p14391845756"></a>Sets the z-index of a tile overlay. The z-index indicates the overlapping order of a tile overlay. A tile overlay with a larger z-index overlaps that with a smaller z-index. Tile overlays with the same z-index overlap each other by the order in which they are added.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table23240mcpsimp"></a>
<table><thead align="left"><tr id="row23245mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p23247mcpsimp"><a name="p23247mcpsimp"></a><a name="p23247mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p23249mcpsimp"><a name="p23249mcpsimp"></a><a name="p23249mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row23250mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p23252mcpsimp"><a name="p23252mcpsimp"></a><a name="p23252mcpsimp"></a>zIndex</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p23254mcpsimp"><a name="p23254mcpsimp"></a><a name="p23254mcpsimp"></a>Z-index, which indicates the overlapping order of a tile overlay. By default, the z-index is 0.</p>
</td>
</tr>
</tbody>
</table>

