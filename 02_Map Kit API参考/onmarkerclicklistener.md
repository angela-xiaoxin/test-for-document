# HuaweiMap.OnMarkerClickListener<a name="ZH-CN_TOPIC_0000001145941023"></a>

-   [Public Method Summary](#section1475712193210)
-   [Public Methods](#section1723715494611)
-   [onMarkerClick](#section165540817477)


<a name="table4160mcpsimp"></a>
<table><thead align="left"><tr id="row4164mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p4166mcpsimp"><a name="p4166mcpsimp"></a><a name="p4166mcpsimp"></a>Interface Info</p>
</th>
</tr>
</thead>
<tbody><tr id="row4167mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p418985852414"><a name="p418985852414"></a><a name="p418985852414"></a>public interface HuaweiMap.OnMarkerClickListener</p>
<p id="p4169mcpsimp"><a name="p4169mcpsimp"></a><a name="p4169mcpsimp"></a>是<a href="huaweimap.md">HuaweiMap</a>类的一个内部接口，表示标记点击事件的侦听器，包含一个抽象函数<a href="#section165540817477">onMarkerClick</a>(<a href="marker.md">Marker</a>)。</p>
</td>
</tr>
</tbody>
</table>

## Public Method Summary<a name="section1475712193210"></a>

<a name="table4175mcpsimp"></a>
<table><thead align="left"><tr id="row4180mcpsimp"><th class="cellrowborder" valign="top" width="40%" id="mcps1.1.3.1.1"><p id="p4182mcpsimp"><a name="p4182mcpsimp"></a><a name="p4182mcpsimp"></a>Qualifier and Type</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.1.3.1.2"><p id="p4184mcpsimp"><a name="p4184mcpsimp"></a><a name="p4184mcpsimp"></a>Method Name and Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row4185mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p4187mcpsimp"><a name="p4187mcpsimp"></a><a name="p4187mcpsimp"></a>abstract boolean</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p4189mcpsimp"><a name="p4189mcpsimp"></a><a name="p4189mcpsimp"></a><a href="#section165540817477">onMarkerClick</a>(<a href="marker.md">Marker</a> marker)</p>
<p id="p48476117313"><a name="p48476117313"></a><a name="p48476117313"></a>点击标记时回调此方法。</p>
</td>
</tr>
</tbody>
</table>

## Public Methods<a name="section1723715494611"></a>

## onMarkerClick<a name="section165540817477"></a>

<a name="table4192mcpsimp"></a>
<table><thead align="left"><tr id="row4196mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p4198mcpsimp"><a name="p4198mcpsimp"></a><a name="p4198mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row4199mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p4201mcpsimp"><a name="p4201mcpsimp"></a><a name="p4201mcpsimp"></a>public abstract boolean onMarkerClick(<a href="marker.md">Marker</a> marker)</p>
<p id="p2845943194714"><a name="p2845943194714"></a><a name="p2845943194714"></a>点击标记时回调此方法。注意，点击标记时发生的第一件事是关闭当前显示的所有信息窗口并触发<a href="oninfowindowcloselistener.md">HuaweiMap.OnInfoWindowCloseListener</a>，然后再触发<a href="onmarkerclicklistener.md">OnMarkerClickListener</a>。因此，从任何标记的<a href="onmarkerclicklistener.md">OnMarkerClickListener</a>中调用<a href="marker.md#section643110419342">isInfoWindowShown</a>()都将返回false。</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table4207mcpsimp"></a>
<table><thead align="left"><tr id="row4212mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p4214mcpsimp"><a name="p4214mcpsimp"></a><a name="p4214mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p4216mcpsimp"><a name="p4216mcpsimp"></a><a name="p4216mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row4217mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p4219mcpsimp"><a name="p4219mcpsimp"></a><a name="p4219mcpsimp"></a>marker</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p4221mcpsimp"><a name="p4221mcpsimp"></a><a name="p4221mcpsimp"></a>标记。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table4224mcpsimp"></a>
<table><thead align="left"><tr id="row4229mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p4231mcpsimp"><a name="p4231mcpsimp"></a><a name="p4231mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p4233mcpsimp"><a name="p4233mcpsimp"></a><a name="p4233mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row4234mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p4236mcpsimp"><a name="p4236mcpsimp"></a><a name="p4236mcpsimp"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p4238mcpsimp"><a name="p4238mcpsimp"></a><a name="p4238mcpsimp"></a>当侦听器没有执行默认行为则返回true，否则返回false。</p>
</td>
</tr>
</tbody>
</table>

