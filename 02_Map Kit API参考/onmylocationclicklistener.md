# HuaweiMap.OnMyLocationClickListener<a name="ZH-CN_TOPIC_0000001099661072"></a>

-   [Public Method Summary](#section17148141117332)
-   [Public Methods](#section5401614125211)
-   [onMyLocationClick](#section97121240135217)


<a name="table4450mcpsimp"></a>
<table><thead align="left"><tr id="row4454mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p4456mcpsimp"><a name="p4456mcpsimp"></a><a name="p4456mcpsimp"></a>Interface Info</p>
</th>
</tr>
</thead>
<tbody><tr id="row4457mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p383915122264"><a name="p383915122264"></a><a name="p383915122264"></a>public interface HuaweiMap.OnMyLocationClickListener</p>
<p id="p4459mcpsimp"><a name="p4459mcpsimp"></a><a name="p4459mcpsimp"></a>是<a href="huaweimap.md">HuaweiMap</a>类的一个内部接口，表示我的位置点击事件的侦听器，包含一个抽象函数<a href="#section97121240135217">onMyLocationClick</a>(Location)。</p>
</td>
</tr>
</tbody>
</table>

## Public Method Summary<a name="section17148141117332"></a>

<a name="table4465mcpsimp"></a>
<table><thead align="left"><tr id="row4470mcpsimp"><th class="cellrowborder" valign="top" width="40%" id="mcps1.1.3.1.1"><p id="p4472mcpsimp"><a name="p4472mcpsimp"></a><a name="p4472mcpsimp"></a>Qualifier and Type</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.1.3.1.2"><p id="p4474mcpsimp"><a name="p4474mcpsimp"></a><a name="p4474mcpsimp"></a>Method Name and Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row4475mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p4477mcpsimp"><a name="p4477mcpsimp"></a><a name="p4477mcpsimp"></a>abstract void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p4479mcpsimp"><a name="p4479mcpsimp"></a><a name="p4479mcpsimp"></a><a href="#section97121240135217">onMyLocationClick</a>(Location location)</p>
<p id="p2062215310418"><a name="p2062215310418"></a><a name="p2062215310418"></a>点击我的位置点时的回调方法。</p>
</td>
</tr>
</tbody>
</table>

## Public Methods<a name="section5401614125211"></a>

## onMyLocationClick<a name="section97121240135217"></a>

<a name="table4482mcpsimp"></a>
<table><thead align="left"><tr id="row4486mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p4488mcpsimp"><a name="p4488mcpsimp"></a><a name="p4488mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row4489mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p4491mcpsimp"><a name="p4491mcpsimp"></a><a name="p4491mcpsimp"></a>public abstract void onMyLocationClick(Location location)</p>
<p id="p1086125315528"><a name="p1086125315528"></a><a name="p1086125315528"></a>点击我的位置点时的回调方法。必须在主线程中执行。</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table4497mcpsimp"></a>
<table><thead align="left"><tr id="row4502mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p4504mcpsimp"><a name="p4504mcpsimp"></a><a name="p4504mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p4506mcpsimp"><a name="p4506mcpsimp"></a><a name="p4506mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row4507mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p4509mcpsimp"><a name="p4509mcpsimp"></a><a name="p4509mcpsimp"></a>location</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p4511mcpsimp"><a name="p4511mcpsimp"></a><a name="p4511mcpsimp"></a>用户当前位置信息。</p>
</td>
</tr>
</tbody>
</table>

