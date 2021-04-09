# HuaweiMap.SnapshotReadyCallback<a name="ZH-CN_TOPIC_0000001099501078"></a>

-   [Public Method Summary](#section195322812343)
-   [Public Methods](#section38319190589)
-   [onSnapshotReady](#section1613882835818)


<a name="table4714mcpsimp"></a>
<table><thead align="left"><tr id="row4718mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p3916mcpsimp"><a name="p3916mcpsimp"></a><a name="p3916mcpsimp"></a>Interface Info</p>
</th>
</tr>
</thead>
<tbody><tr id="row4721mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p13468258267"><a name="p13468258267"></a><a name="p13468258267"></a>public interface HuaweiMap.SnapshotReadyCallback</p>
<p id="p4723mcpsimp"><a name="p4723mcpsimp"></a><a name="p4723mcpsimp"></a>是<a href="huaweimap.md">HuaweiMap</a>类的一个内部接口，表示截图完成时的回调接口，包含一个抽象函数<a href="#section1613882835818">onSnapshotReady</a>(Bitmap)。</p>
</td>
</tr>
</tbody>
</table>

## Public Method Summary<a name="section195322812343"></a>

<a name="table4729mcpsimp"></a>
<table><thead align="left"><tr id="row4734mcpsimp"><th class="cellrowborder" valign="top" width="40%" id="mcps1.1.3.1.1"><p id="p4736mcpsimp"><a name="p4736mcpsimp"></a><a name="p4736mcpsimp"></a>Qualifier and Type</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.1.3.1.2"><p id="p4738mcpsimp"><a name="p4738mcpsimp"></a><a name="p4738mcpsimp"></a>Method Name and Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row4739mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p4741mcpsimp"><a name="p4741mcpsimp"></a><a name="p4741mcpsimp"></a>abstract void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p4743mcpsimp"><a name="p4743mcpsimp"></a><a name="p4743mcpsimp"></a><a href="#section1613882835818">onSnapshotReady</a>(Bitmap snapshot)</p>
<p id="p1663144510619"><a name="p1663144510619"></a><a name="p1663144510619"></a>快照生成时的回调方法。</p>
</td>
</tr>
</tbody>
</table>

## Public Methods<a name="section38319190589"></a>

## onSnapshotReady<a name="section1613882835818"></a>

<a name="table4746mcpsimp"></a>
<table><thead align="left"><tr id="row4750mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p4752mcpsimp"><a name="p4752mcpsimp"></a><a name="p4752mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row4753mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p4755mcpsimp"><a name="p4755mcpsimp"></a><a name="p4755mcpsimp"></a>public abstract void onSnapshotReady(Bitmap snapshot)</p>
<p id="p3370135215588"><a name="p3370135215588"></a><a name="p3370135215588"></a>快照生成时的回调方法。必须在主线程中执行。</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table4761mcpsimp"></a>
<table><thead align="left"><tr id="row4766mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p4768mcpsimp"><a name="p4768mcpsimp"></a><a name="p4768mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p4770mcpsimp"><a name="p4770mcpsimp"></a><a name="p4770mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row4771mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p4773mcpsimp"><a name="p4773mcpsimp"></a><a name="p4773mcpsimp"></a>snapshot</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p4775mcpsimp"><a name="p4775mcpsimp"></a><a name="p4775mcpsimp"></a>生成的快照。</p>
</td>
</tr>
</tbody>
</table>

