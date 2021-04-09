# HuaweiMap.OnMarkerClickListener<a name="EN-US_TOPIC_0000001145941023"></a>

-   [Public Method Summary](#section1475712193210)
-   [Public Methods](#section1723715494611)
-   [onMarkerClick](#section165540817477)


<a name="table4160mcpsimp"></a>
<table><thead align="left"><tr id="row4164mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p4166mcpsimp"><a name="p4166mcpsimp"></a><a name="p4166mcpsimp"></a>Interface Info</p>
</th>
</tr>
</thead>
<tbody><tr id="row4167mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p418985852414"><a name="p418985852414"></a><a name="p418985852414"></a>public interface HuaweiMap.OnMarkerClickListener</p>
<p id="p4169mcpsimp"><a name="p4169mcpsimp"></a><a name="p4169mcpsimp"></a>An internal API of the <a href="huaweimap.md">HuaweiMap</a> class, which is used to listen for the marker tap event. It contains the abstract method <a href="#section165540817477">onMarkerClick</a>(<a href="marker.md">Marker</a>).</p>
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
<p id="p48476117313"><a name="p48476117313"></a><a name="p48476117313"></a>Called when a marker is tapped.</p>
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
<p id="p2845943194714"><a name="p2845943194714"></a><a name="p2845943194714"></a>Called when a marker is tapped. Note that when a marker is tapped, all currently displayed information windows are closed and <a href="oninfowindowcloselistener.md">HuaweiMap.OnInfoWindowCloseListener</a> is triggered. Then <a href="onmarkerclicklistener.md">OnMarkerClickListener</a> is triggered. Therefore, <strong id="b189213082914"><a name="b189213082914"></a><a name="b189213082914"></a>false</strong> will always be returned if <a href="marker.md#section643110419342">isInfoWindowShown</a><strong id="b86312019152917"><a name="b86312019152917"></a><a name="b86312019152917"></a>()</strong> is called in <a href="onmarkerclicklistener.md">OnMarkerClickListener</a> for any marker.</p>
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
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p4221mcpsimp"><a name="p4221mcpsimp"></a><a name="p4221mcpsimp"></a>Marker.</p>
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
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p4238mcpsimp"><a name="p4238mcpsimp"></a><a name="p4238mcpsimp"></a><strong id="b8723174416299"><a name="b8723174416299"></a><a name="b8723174416299"></a>true</strong> if the listener does not perform the default operation; <strong id="b971815611296"><a name="b971815611296"></a><a name="b971815611296"></a>false</strong> otherwise.</p>
</td>
</tr>
</tbody>
</table>

