# TileOverlay<a name="ZH-CN_TOPIC_0000001099341092"></a>

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
<p id="p22748mcpsimp"><a name="p22748mcpsimp"></a><a name="p22748mcpsimp"></a><a href="tileoverlay.md">TileOverlay</a>是瓦片图层的相关类。瓦片图层是显示在地图上的一组图像。这些瓦片可以是透明的，允许您增加一些新的功能到现有的地图上。在调用<a href="huaweimap.md">HuaweiMap</a>类的<a href="huaweimap.md#section12241957204519">addTileOverlay</a>方法时会返回该类型的实例。</p>
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
<p id="p152726863413"><a name="p152726863413"></a><a name="p152726863413"></a>清空瓦片图层的缓存。</p>
</td>
</tr>
<tr id="row22769mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p22771mcpsimp"><a name="p22771mcpsimp"></a><a name="p22771mcpsimp"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p22773mcpsimp"><a name="p22773mcpsimp"></a><a name="p22773mcpsimp"></a><a href="#section15108202995916">equals</a>(Object other)</p>
<p id="p1051579193413"><a name="p1051579193413"></a><a name="p1051579193413"></a>判断两个瓦片图层对象是否相等。</p>
</td>
</tr>
<tr id="row22774mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p22776mcpsimp"><a name="p22776mcpsimp"></a><a name="p22776mcpsimp"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p22778mcpsimp"><a name="p22778mcpsimp"></a><a name="p22778mcpsimp"></a><a href="#section1795437900">getFadeIn</a>()</p>
<p id="p166533107344"><a name="p166533107344"></a><a name="p166533107344"></a>获取瓦片图层是否是淡入。</p>
</td>
</tr>
<tr id="row22779mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p22781mcpsimp"><a name="p22781mcpsimp"></a><a name="p22781mcpsimp"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p22783mcpsimp"><a name="p22783mcpsimp"></a><a name="p22783mcpsimp"></a><a href="#section42720526014">getId</a>()</p>
<p id="p2078161193416"><a name="p2078161193416"></a><a name="p2078161193416"></a>获取瓦片图层的id属性。</p>
</td>
</tr>
<tr id="row22784mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p22786mcpsimp"><a name="p22786mcpsimp"></a><a name="p22786mcpsimp"></a>float</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p22788mcpsimp"><a name="p22788mcpsimp"></a><a name="p22788mcpsimp"></a><a href="#section382417241813">getTransparency</a>()</p>
<p id="p107865126346"><a name="p107865126346"></a><a name="p107865126346"></a>获取瓦片图层的透明度。</p>
</td>
</tr>
<tr id="row22789mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p22791mcpsimp"><a name="p22791mcpsimp"></a><a name="p22791mcpsimp"></a>float</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p22793mcpsimp"><a name="p22793mcpsimp"></a><a name="p22793mcpsimp"></a><a href="#section1740420531818">getZIndex</a>()</p>
<p id="p9819161313417"><a name="p9819161313417"></a><a name="p9819161313417"></a>获取瓦片图层的z指数。</p>
</td>
</tr>
<tr id="row22794mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p22796mcpsimp"><a name="p22796mcpsimp"></a><a name="p22796mcpsimp"></a>int</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p22798mcpsimp"><a name="p22798mcpsimp"></a><a name="p22798mcpsimp"></a><a href="#section1079617226216">hashCode</a>()</p>
<p id="p13791191411342"><a name="p13791191411342"></a><a name="p13791191411342"></a>获取瓦片图层的哈希值。</p>
</td>
</tr>
<tr id="row22799mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p22801mcpsimp"><a name="p22801mcpsimp"></a><a name="p22801mcpsimp"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p22803mcpsimp"><a name="p22803mcpsimp"></a><a name="p22803mcpsimp"></a><a href="#section1718157628">isVisible</a>()</p>
<p id="p10703181533418"><a name="p10703181533418"></a><a name="p10703181533418"></a>获取瓦片图层的可见性。</p>
</td>
</tr>
<tr id="row22804mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p22806mcpsimp"><a name="p22806mcpsimp"></a><a name="p22806mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p22808mcpsimp"><a name="p22808mcpsimp"></a><a name="p22808mcpsimp"></a><a href="#section354412291830">remove</a>()</p>
<p id="p14524121719344"><a name="p14524121719344"></a><a name="p14524121719344"></a>将瓦片图层从地图上移除。</p>
</td>
</tr>
<tr id="row22809mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p22811mcpsimp"><a name="p22811mcpsimp"></a><a name="p22811mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p22813mcpsimp"><a name="p22813mcpsimp"></a><a name="p22813mcpsimp"></a><a href="#section9414160649">setFadeIn</a>(boolean fadeIn)</p>
<p id="p16774218203419"><a name="p16774218203419"></a><a name="p16774218203419"></a>设置瓦片图层是否是淡入。</p>
</td>
</tr>
<tr id="row22814mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p22816mcpsimp"><a name="p22816mcpsimp"></a><a name="p22816mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p22818mcpsimp"><a name="p22818mcpsimp"></a><a name="p22818mcpsimp"></a><a href="#section10412133211419">setTransparency</a>(float transparency)</p>
<p id="p12920131915347"><a name="p12920131915347"></a><a name="p12920131915347"></a>设置瓦片图层的透明度。</p>
</td>
</tr>
<tr id="row22819mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p22821mcpsimp"><a name="p22821mcpsimp"></a><a name="p22821mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p22823mcpsimp"><a name="p22823mcpsimp"></a><a name="p22823mcpsimp"></a><a href="#section933417218519">setVisible</a>(boolean visible)</p>
<p id="p69911820133415"><a name="p69911820133415"></a><a name="p69911820133415"></a>设置瓦片图层的可见性。</p>
</td>
</tr>
<tr id="row22824mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p22826mcpsimp"><a name="p22826mcpsimp"></a><a name="p22826mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p22828mcpsimp"><a name="p22828mcpsimp"></a><a name="p22828mcpsimp"></a><a href="#section182617531253">setZIndex</a>(float zIndex)</p>
<p id="p32172233412"><a name="p32172233412"></a><a name="p32172233412"></a>设置瓦片图层的z指数。</p>
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
<p id="p18424975913"><a name="p18424975913"></a><a name="p18424975913"></a>您调用此API可以清空瓦片图层的缓存。</p>
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
<p id="p22863mcpsimp"><a name="p22863mcpsimp"></a><a name="p22863mcpsimp"></a>您调用此API可以判断两个瓦片图层对象是否相等。</p>
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
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p22880mcpsimp"><a name="p22880mcpsimp"></a><a name="p22880mcpsimp"></a>另一对象名称。</p>
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
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p22897mcpsimp"><a name="p22897mcpsimp"></a><a name="p22897mcpsimp"></a>瓦片图层对象是否相等。true为相等，false为不相等。</p>
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
<p id="p186425241603"><a name="p186425241603"></a><a name="p186425241603"></a>您调用此API可以获取瓦片图层是否是淡入。</p>
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
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p22931mcpsimp"><a name="p22931mcpsimp"></a><a name="p22931mcpsimp"></a>是否是淡入。</p>
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
<p id="p22945mcpsimp"><a name="p22945mcpsimp"></a><a name="p22945mcpsimp"></a>您调用此API可以获取瓦片图层的id属性，该id在地图上的所有标记中都是唯一的。</p>
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
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p22965mcpsimp"><a name="p22965mcpsimp"></a><a name="p22965mcpsimp"></a>瓦片图层的id属性。</p>
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
<p id="p0410113714118"><a name="p0410113714118"></a><a name="p0410113714118"></a>您调用此API可以获取瓦片图层的透明度。</p>
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
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p22999mcpsimp"><a name="p22999mcpsimp"></a><a name="p22999mcpsimp"></a>瓦片图层的透明度，取值范围：[0, 1]，0为不透明，1为全透明。</p>
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
<p id="p19556166224"><a name="p19556166224"></a><a name="p19556166224"></a>您调用此API可以获取瓦片图层的z指数。</p>
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
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p23033mcpsimp"><a name="p23033mcpsimp"></a><a name="p23033mcpsimp"></a>z指数，即瓦片图层的叠加顺序。</p>
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
<p id="p6884740326"><a name="p6884740326"></a><a name="p6884740326"></a>您调用此API可以获取瓦片图层的哈希值。</p>
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
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p23067mcpsimp"><a name="p23067mcpsimp"></a><a name="p23067mcpsimp"></a>表示瓦片图层的哈希值。</p>
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
<p id="p23081mcpsimp"><a name="p23081mcpsimp"></a><a name="p23081mcpsimp"></a>您调用此API可以获取瓦片图层的可见性。</p>
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
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p23101mcpsimp"><a name="p23101mcpsimp"></a><a name="p23101mcpsimp"></a>瓦片图层的可见性，true为可见，false为不可见。</p>
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
<p id="p23115mcpsimp"><a name="p23115mcpsimp"></a><a name="p23115mcpsimp"></a>您调用此API可以将瓦片图层从地图上移除。</p>
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
<p id="p23135mcpsimp"><a name="p23135mcpsimp"></a><a name="p23135mcpsimp"></a>您调用此API可以设置瓦片图层是否是淡入。</p>
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
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p9682161852011"><a name="p9682161852011"></a><a name="p9682161852011"></a>是否是淡入，true为淡入，false为不淡入。默认值为true。</p>
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
<p id="p23169mcpsimp"><a name="p23169mcpsimp"></a><a name="p23169mcpsimp"></a>您调用此API可以设置瓦片图层的透明度。</p>
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
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p23186mcpsimp"><a name="p23186mcpsimp"></a><a name="p23186mcpsimp"></a>瓦片图层的透明度，取值范围：[0, 1]，0为不透明，1为全透明，默认为0。</p>
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
<p id="p23203mcpsimp"><a name="p23203mcpsimp"></a><a name="p23203mcpsimp"></a>您调用此方法来设置瓦片图层的可见性，如果瓦片图层不可见，则不会绘制，其他所有状态均保留，瓦片图层默认是可见的。</p>
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
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p23220mcpsimp"><a name="p23220mcpsimp"></a><a name="p23220mcpsimp"></a>可见性，true为可见，false为不可见。默认值为true。</p>
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
<p id="p14391845756"><a name="p14391845756"></a><a name="p14391845756"></a>用于设置瓦片图层的z指数。z指数指的是瓦片图层的叠加顺序，具有较大z指数的瓦片图层会绘制在具有较小z指数的瓦片图层上，具有相同z指数的叠加顺序为元素添加的先后顺序。</p>
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
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p23254mcpsimp"><a name="p23254mcpsimp"></a><a name="p23254mcpsimp"></a>z指数，即瓦片图层的叠加顺序。默认的z指数是0。</p>
</td>
</tr>
</tbody>
</table>

