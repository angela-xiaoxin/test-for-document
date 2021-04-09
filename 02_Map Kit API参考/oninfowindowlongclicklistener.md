# HuaweiMap.OnInfoWindowLongClickListener<a name="ZH-CN_TOPIC_0000001145780983"></a>

-   [Public Method Summary](#section05392025112817)
-   [Public Methods](#section1467515115427)
-   [onInfoWindowLongClick](#section9371202515423)


<a name="table3910mcpsimp"></a>
<table><thead align="left"><tr id="row3914mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p3916mcpsimp"><a name="p3916mcpsimp"></a><a name="p3916mcpsimp"></a>Interface Info</p>
</th>
</tr>
</thead>
<tbody><tr id="row3917mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p855454182416"><a name="p855454182416"></a><a name="p855454182416"></a>public interface HuaweiMap.OnInfoWindowLongClickListener</p>
<p id="p3919mcpsimp"><a name="p3919mcpsimp"></a><a name="p3919mcpsimp"></a>是<a href="huaweimap.md">HuaweiMap</a>类的一个内部接口，表示信息窗口长按事件的侦听器，包含一个抽象函数<a href="#section9371202515423">onInfoWindowLongClick</a>(<a href="marker.md">Marker</a>)。</p>
</td>
</tr>
</tbody>
</table>

## Public Method Summary<a name="section05392025112817"></a>

<a name="table3925mcpsimp"></a>
<table><thead align="left"><tr id="row3930mcpsimp"><th class="cellrowborder" valign="top" width="40%" id="mcps1.1.3.1.1"><p id="p081120285386"><a name="p081120285386"></a><a name="p081120285386"></a>Qualifier and Type</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.1.3.1.2"><p id="p681112883813"><a name="p681112883813"></a><a name="p681112883813"></a>Method Name and Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row3935mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p3937mcpsimp"><a name="p3937mcpsimp"></a><a name="p3937mcpsimp"></a>abstract void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p3939mcpsimp"><a name="p3939mcpsimp"></a><a name="p3939mcpsimp"></a><a href="#section9371202515423">onInfoWindowLongClick</a>(<a href="marker.md">Marker</a> marker)</p>
<p id="p9713191817217"><a name="p9713191817217"></a><a name="p9713191817217"></a>长按标记信息窗口时回调此方法。</p>
</td>
</tr>
</tbody>
</table>

## Public Methods<a name="section1467515115427"></a>

## onInfoWindowLongClick<a name="section9371202515423"></a>

<a name="table3942mcpsimp"></a>
<table><thead align="left"><tr id="row3946mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p3948mcpsimp"><a name="p3948mcpsimp"></a><a name="p3948mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row3949mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p3951mcpsimp"><a name="p3951mcpsimp"></a><a name="p3951mcpsimp"></a>public abstract void onInfoWindowLongClick(<a href="marker.md">Marker</a> marker)</p>
<p id="p188272386429"><a name="p188272386429"></a><a name="p188272386429"></a>长按标记信息窗口时回调此方法。必须在主线程中执行。</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table3957mcpsimp"></a>
<table><thead align="left"><tr id="row3962mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p3964mcpsimp"><a name="p3964mcpsimp"></a><a name="p3964mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p3966mcpsimp"><a name="p3966mcpsimp"></a><a name="p3966mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row3967mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p3969mcpsimp"><a name="p3969mcpsimp"></a><a name="p3969mcpsimp"></a>marker</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p3971mcpsimp"><a name="p3971mcpsimp"></a><a name="p3971mcpsimp"></a>长按的标记。</p>
</td>
</tr>
</tbody>
</table>

