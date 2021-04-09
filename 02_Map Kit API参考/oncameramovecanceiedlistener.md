# HuaweiMap.OnCameraMoveCanceledListener<a name="ZH-CN_TOPIC_0000001145541063"></a>

-   [Public Method Summary](#section13285446152413)
-   [Public Methods](#section37891926193119)
-   [onCameraMoveCanceled](#section161773399315)


<a name="table3443mcpsimp"></a>
<table><thead align="left"><tr id="row3447mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p3449mcpsimp"><a name="p3449mcpsimp"></a><a name="p3449mcpsimp"></a>Interface Info</p>
</th>
</tr>
</thead>
<tbody><tr id="row3450mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p5673335212"><a name="p5673335212"></a><a name="p5673335212"></a>public interface HuaweiMap.OnCameraMoveCanceledListener</p>
<p id="p3452mcpsimp"><a name="p3452mcpsimp"></a><a name="p3452mcpsimp"></a>是<a href="huaweimap.md">HuaweiMap</a>类的一个内部接口，表示相机移动被取消事件的侦听器，包含一个抽象函数<a href="#section161773399315">onCameraMoveCanceled</a>()。</p>
</td>
</tr>
</tbody>
</table>

## Public Method Summary<a name="section13285446152413"></a>

<a name="table3458mcpsimp"></a>
<table><thead align="left"><tr id="row3463mcpsimp"><th class="cellrowborder" valign="top" width="40%" id="mcps1.1.3.1.1"><p id="p3465mcpsimp"><a name="p3465mcpsimp"></a><a name="p3465mcpsimp"></a>Qualifier and Type</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.1.3.1.2"><p id="p3467mcpsimp"><a name="p3467mcpsimp"></a><a name="p3467mcpsimp"></a>Method Name and Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row3468mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p3470mcpsimp"><a name="p3470mcpsimp"></a><a name="p3470mcpsimp"></a>abstract void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p3472mcpsimp"><a name="p3472mcpsimp"></a><a name="p3472mcpsimp"></a><a href="#section161773399315">onCameraMoveCanceled</a>()</p>
<p id="p1874411191903"><a name="p1874411191903"></a><a name="p1874411191903"></a>当您显式调用<a href="huaweimap.md#section4909811181019">stopAnimation</a>()方法或者触发相机移动的原因发生变化时调用此方法。</p>
</td>
</tr>
</tbody>
</table>

## Public Methods<a name="section37891926193119"></a>

## onCameraMoveCanceled<a name="section161773399315"></a>

<a name="table3475mcpsimp"></a>
<table><thead align="left"><tr id="row3479mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p3481mcpsimp"><a name="p3481mcpsimp"></a><a name="p3481mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row3482mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p3484mcpsimp"><a name="p3484mcpsimp"></a><a name="p3484mcpsimp"></a>public abstract void onCameraMoveCanceled()</p>
<p id="p3487mcpsimp"><a name="p3487mcpsimp"></a><a name="p3487mcpsimp"></a>当您显式调用<a href="huaweimap.md#section4909811181019">stopAnimation</a>()方法或者触发相机移动的原因发生变化时调用此方法。不要在此方法中更新相机状态。必须在主线程中调用。</p>
</td>
</tr>
</tbody>
</table>

