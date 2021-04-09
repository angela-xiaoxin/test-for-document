# HuaweiMap.OnInfoWindowCloseListener<a name="ZH-CN_TOPIC_0000001099501114"></a>

-   [Public Method Summary](#section229661142817)
-   [Public Methods](#section2191944204019)
-   [onInfoWindowClose](#section1065513577408)


<a name="table3844mcpsimp"></a>
<table><thead align="left"><tr id="row3848mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p3850mcpsimp"><a name="p3850mcpsimp"></a><a name="p3850mcpsimp"></a>Interface Info</p>
</th>
</tr>
</thead>
<tbody><tr id="row3851mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p0269001248"><a name="p0269001248"></a><a name="p0269001248"></a>public interface HuaweiMap.OnInfoWindowCloseListener</p>
<p id="p3853mcpsimp"><a name="p3853mcpsimp"></a><a name="p3853mcpsimp"></a>是<a href="huaweimap.md">HuaweiMap</a>类的一个内部接口，表示信息窗口关闭事件的侦听器，包含一个抽象函数<a href="#section1065513577408">onInfoWindowClose</a>(<a href="marker.md">Marker</a>)。</p>
</td>
</tr>
</tbody>
</table>

## Public Method Summary<a name="section229661142817"></a>

<a name="table3859mcpsimp"></a>
<table><thead align="left"><tr id="row3864mcpsimp"><th class="cellrowborder" valign="top" width="40%" id="mcps1.1.3.1.1"><p id="p081120285386"><a name="p081120285386"></a><a name="p081120285386"></a>Qualifier and Type</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.1.3.1.2"><p id="p681112883813"><a name="p681112883813"></a><a name="p681112883813"></a>Method Name and Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row3869mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p3871mcpsimp"><a name="p3871mcpsimp"></a><a name="p3871mcpsimp"></a>abstract void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p3873mcpsimp"><a name="p3873mcpsimp"></a><a name="p3873mcpsimp"></a><a href="#section1065513577408">onInfoWindowClose</a>(<a href="marker.md">Marker</a> marker)</p>
<p id="p1524213817215"><a name="p1524213817215"></a><a name="p1524213817215"></a>标记信息窗口关闭时的回调方法。</p>
</td>
</tr>
</tbody>
</table>

## Public Methods<a name="section2191944204019"></a>

## onInfoWindowClose<a name="section1065513577408"></a>

<a name="table3876mcpsimp"></a>
<table><thead align="left"><tr id="row3880mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p3882mcpsimp"><a name="p3882mcpsimp"></a><a name="p3882mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row3883mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p3885mcpsimp"><a name="p3885mcpsimp"></a><a name="p3885mcpsimp"></a>public abstract void onInfoWindowClose(<a href="marker.md">Marker</a> marker)</p>
<p id="p3888mcpsimp"><a name="p3888mcpsimp"></a><a name="p3888mcpsimp"></a>标记信息窗口关闭时的回调方法。必须在主线程中执行。</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table3891mcpsimp"></a>
<table><thead align="left"><tr id="row3896mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p3898mcpsimp"><a name="p3898mcpsimp"></a><a name="p3898mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p3900mcpsimp"><a name="p3900mcpsimp"></a><a name="p3900mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row3901mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p3903mcpsimp"><a name="p3903mcpsimp"></a><a name="p3903mcpsimp"></a>marker</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p3905mcpsimp"><a name="p3905mcpsimp"></a><a name="p3905mcpsimp"></a>关闭的标记。</p>
</td>
</tr>
</tbody>
</table>

