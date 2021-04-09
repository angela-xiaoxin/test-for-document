# HuaweiMap.OnMyLocationButtonClickListener<a name="ZH-CN_TOPIC_0000001099181254"></a>

-   [Public Method Summary](#section1174114417322)
-   [Public Methods](#section1861245405019)
-   [onMyLocationButtonClick](#section2082520410519)


<a name="table4384mcpsimp"></a>
<table><thead align="left"><tr id="row4388mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p4390mcpsimp"><a name="p4390mcpsimp"></a><a name="p4390mcpsimp"></a>Interface Info</p>
</th>
</tr>
</thead>
<tbody><tr id="row4391mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p1892791218257"><a name="p1892791218257"></a><a name="p1892791218257"></a>public interface HuaweiMap.OnMyLocationButtonClickListener</p>
<p id="p4393mcpsimp"><a name="p4393mcpsimp"></a><a name="p4393mcpsimp"></a>是<a href="huaweimap.md">HuaweiMap</a>类的一个内部接口，表示<span class="uicontrol" id="uicontrol1178518619613"><a name="uicontrol1178518619613"></a><a name="uicontrol1178518619613"></a>“我的位置”</span>按钮事件点击的侦听器，包含一个抽象函数<a href="#section2082520410519">onMyLocationButtonClick</a>()。</p>
</td>
</tr>
</tbody>
</table>

## Public Method Summary<a name="section1174114417322"></a>

<a name="table4399mcpsimp"></a>
<table><thead align="left"><tr id="row4404mcpsimp"><th class="cellrowborder" valign="top" width="40%" id="mcps1.1.3.1.1"><p id="p4406mcpsimp"><a name="p4406mcpsimp"></a><a name="p4406mcpsimp"></a>Qualifier and Type</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.1.3.1.2"><p id="p4408mcpsimp"><a name="p4408mcpsimp"></a><a name="p4408mcpsimp"></a>Method Name and Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row4409mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p4411mcpsimp"><a name="p4411mcpsimp"></a><a name="p4411mcpsimp"></a>abstract boolean</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p4413mcpsimp"><a name="p4413mcpsimp"></a><a name="p4413mcpsimp"></a><a href="#section2082520410519">onMyLocationButtonClick</a>()</p>
<p id="p22374401442"><a name="p22374401442"></a><a name="p22374401442"></a>点击我的位置按钮时的回调方法。</p>
</td>
</tr>
</tbody>
</table>

## Public Methods<a name="section1861245405019"></a>

## onMyLocationButtonClick<a name="section2082520410519"></a>

<a name="table4416mcpsimp"></a>
<table><thead align="left"><tr id="row4420mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p4422mcpsimp"><a name="p4422mcpsimp"></a><a name="p4422mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row4423mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p4425mcpsimp"><a name="p4425mcpsimp"></a><a name="p4425mcpsimp"></a>public abstract boolean onMyLocationButtonClick()</p>
<p id="p7337832115116"><a name="p7337832115116"></a><a name="p7337832115116"></a>点击我的位置按钮时的回调方法。必须在主线程中调用。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table4434mcpsimp"></a>
<table><thead align="left"><tr id="row4439mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p4441mcpsimp"><a name="p4441mcpsimp"></a><a name="p4441mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p4443mcpsimp"><a name="p4443mcpsimp"></a><a name="p4443mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row4444mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p4446mcpsimp"><a name="p4446mcpsimp"></a><a name="p4446mcpsimp"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p4448mcpsimp"><a name="p4448mcpsimp"></a><a name="p4448mcpsimp"></a>如果侦听器已经消耗了该事件（即不发生默认行为），返回true，否则（即发生默认行为），返回false。默认行为是相机移动，使其以用户位置为中心。</p>
</td>
</tr>
</tbody>
</table>

