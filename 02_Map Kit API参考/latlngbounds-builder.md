# LatLngBounds.Builder<a name="ZH-CN_TOPIC_0000001145941031"></a>

-   [Public Method Summary](#section1981422101210)
-   [Public Methods](#section11922758141918)
-   [build](#section9434191512013)
-   [include](#section1837923042016)


<a name="table14325mcpsimp"></a>
<table><thead align="left"><tr id="row14329mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p14331mcpsimp"><a name="p14331mcpsimp"></a><a name="p14331mcpsimp"></a>Class Info</p>
</th>
</tr>
</thead>
<tbody><tr id="row14332mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p83598575402"><a name="p83598575402"></a><a name="p83598575402"></a>public static final class LatLngBounds.Builder</p>
<p id="p14334mcpsimp"><a name="p14334mcpsimp"></a><a name="p14334mcpsimp"></a><a href="latlngbounds-builder.md">LatLngBounds.Builder</a>是<a href="latlngbounds.md">LatLngBounds</a>的内部接口，包含了<a href="#section9434191512013">build</a>()、<a href="#section1837923042016">include</a>(<a href="latlng.md">LatLng</a> point)两个方法。您可以通过<a href="latlngbounds.md">LatLngBounds</a>类的<a href="latlngbounds.md#section1854132519124">builder</a>方法获取<a href="latlngbounds-builder.md">LatLngBounds.Builder</a>对象，具体使用方法参见<a href="latlngbounds.md">LatLngBounds</a>。</p>
</td>
</tr>
</tbody>
</table>

## Public Method Summary<a name="section1981422101210"></a>

<a name="table14340mcpsimp"></a>
<table><thead align="left"><tr id="row14345mcpsimp"><th class="cellrowborder" valign="top" width="40%" id="mcps1.1.3.1.1"><p id="p081120285386"><a name="p081120285386"></a><a name="p081120285386"></a>Qualifier and Type</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.1.3.1.2"><p id="p681112883813"><a name="p681112883813"></a><a name="p681112883813"></a>Method Name and Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row14350mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p14352mcpsimp"><a name="p14352mcpsimp"></a><a name="p14352mcpsimp"></a><a href="latlngbounds.md">LatLngBounds</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p14354mcpsimp"><a name="p14354mcpsimp"></a><a name="p14354mcpsimp"></a><a href="#section9434191512013">build</a>()</p>
<p id="p648617117256"><a name="p648617117256"></a><a name="p648617117256"></a>构建一个<a href="latlngbounds.md">LatLngBounds</a>对象。</p>
</td>
</tr>
<tr id="row14355mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p14357mcpsimp"><a name="p14357mcpsimp"></a><a name="p14357mcpsimp"></a><a href="latlngbounds-builder.md">LatLngBounds.Builder</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p14359mcpsimp"><a name="p14359mcpsimp"></a><a name="p14359mcpsimp"></a><a href="#section1837923042016">include</a>(<a href="latlng.md">LatLng</a> point)</p>
<p id="p1251211210251"><a name="p1251211210251"></a><a name="p1251211210251"></a>获得一个以最小方式扩展并包含指定位置的<a href="latlngbounds.md">LatLngBounds</a>对象。</p>
</td>
</tr>
</tbody>
</table>

## Public Methods<a name="section11922758141918"></a>

## build<a name="section9434191512013"></a>

<a name="table14362mcpsimp"></a>
<table><thead align="left"><tr id="row14366mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p14368mcpsimp"><a name="p14368mcpsimp"></a><a name="p14368mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row14369mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p14371mcpsimp"><a name="p14371mcpsimp"></a><a name="p14371mcpsimp"></a>public <a href="latlngbounds.md">LatLngBounds</a> build()</p>
<p id="p2465165512122"><a name="p2465165512122"></a><a name="p2465165512122"></a>您调用此API可以构建一个<a href="latlngbounds.md">LatLngBounds</a>对象。</p>
</td>
</tr>
</tbody>
</table>

**Throws**

<a name="table14397mcpsimp"></a>
<table><thead align="left"><tr id="row14402mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p14404mcpsimp"><a name="p14404mcpsimp"></a><a name="p14404mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p14406mcpsimp"><a name="p14406mcpsimp"></a><a name="p14406mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row14407mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p14409mcpsimp"><a name="p14409mcpsimp"></a><a name="p14409mcpsimp"></a>IllegalStateException</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p14411mcpsimp"><a name="p14411mcpsimp"></a><a name="p14411mcpsimp"></a>当<a href="latlngbounds.md">LatLngBounds</a>没有包含任何点坐标，抛出异常。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table14380mcpsimp"></a>
<table><thead align="left"><tr id="row14385mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p14387mcpsimp"><a name="p14387mcpsimp"></a><a name="p14387mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p14389mcpsimp"><a name="p14389mcpsimp"></a><a name="p14389mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row14390mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p14392mcpsimp"><a name="p14392mcpsimp"></a><a name="p14392mcpsimp"></a>LatLngBounds</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p14394mcpsimp"><a name="p14394mcpsimp"></a><a name="p14394mcpsimp"></a><a href="latlngbounds.md">LatLngBounds</a>对象。</p>
</td>
</tr>
</tbody>
</table>

## include<a name="section1837923042016"></a>

<a name="table14413mcpsimp"></a>
<table><thead align="left"><tr id="row14417mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p14419mcpsimp"><a name="p14419mcpsimp"></a><a name="p14419mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row14420mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p14422mcpsimp"><a name="p14422mcpsimp"></a><a name="p14422mcpsimp"></a>public <a href="latlngbounds-builder.md">LatLngBounds.Builder</a> include(LatLng point)</p>
<p id="p122521830182618"><a name="p122521830182618"></a><a name="p122521830182618"></a>您调用此API可以设置<a href="latlngbounds.md">LatLngBounds</a>对象包含一个指定位置，用于构建矩形区域。</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table14428mcpsimp"></a>
<table><thead align="left"><tr id="row14433mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p14435mcpsimp"><a name="p14435mcpsimp"></a><a name="p14435mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p14437mcpsimp"><a name="p14437mcpsimp"></a><a name="p14437mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row14438mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p14440mcpsimp"><a name="p14440mcpsimp"></a><a name="p14440mcpsimp"></a>point</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p14442mcpsimp"><a name="p14442mcpsimp"></a><a name="p14442mcpsimp"></a>需要被包含的位置。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table14445mcpsimp"></a>
<table><thead align="left"><tr id="row14450mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p14452mcpsimp"><a name="p14452mcpsimp"></a><a name="p14452mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p14454mcpsimp"><a name="p14454mcpsimp"></a><a name="p14454mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row14455mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p14457mcpsimp"><a name="p14457mcpsimp"></a><a name="p14457mcpsimp"></a><a href="latlngbounds-builder.md">LatLngBounds.Builder</a></p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p14459mcpsimp"><a name="p14459mcpsimp"></a><a name="p14459mcpsimp"></a>包含指定位置的<a href="latlngbounds.md">LatLngBounds</a>对象。</p>
</td>
</tr>
</tbody>
</table>

