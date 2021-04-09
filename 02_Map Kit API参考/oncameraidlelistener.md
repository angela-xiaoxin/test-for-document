# HuaweiMap.OnCameraIdleListener<a name="ZH-CN_TOPIC_0000001099661034"></a>

-   [Public Method Summary](#section12344172511249)
-   [Public Methods](#section127571147291)
-   [onCameraIdle](#section495822616298)


<a name="table3391mcpsimp"></a>
<table><thead align="left"><tr id="row3395mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p3397mcpsimp"><a name="p3397mcpsimp"></a><a name="p3397mcpsimp"></a>Interface Info</p>
</th>
</tr>
</thead>
<tbody><tr id="row3398mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p1052083832110"><a name="p1052083832110"></a><a name="p1052083832110"></a>public interface HuaweiMap.OnCameraIdleListener</p>
<p id="p3400mcpsimp"><a name="p3400mcpsimp"></a><a name="p3400mcpsimp"></a>是<a href="huaweimap.md">HuaweiMap</a>类的一个内部接口，表示相机移动结束事件的侦听器，包含一个抽象函数<a href="#section495822616298">onCameraIdle</a>()。</p>
</td>
</tr>
</tbody>
</table>

## Public Method Summary<a name="section12344172511249"></a>

<a name="table3406mcpsimp"></a>
<table><thead align="left"><tr id="row3411mcpsimp"><th class="cellrowborder" valign="top" width="40%" id="mcps1.1.3.1.1"><p id="p3413mcpsimp"><a name="p3413mcpsimp"></a><a name="p3413mcpsimp"></a>Qualifier and Type</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.1.3.1.2"><p id="p3415mcpsimp"><a name="p3415mcpsimp"></a><a name="p3415mcpsimp"></a>Method Name and Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row3416mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p3418mcpsimp"><a name="p3418mcpsimp"></a><a name="p3418mcpsimp"></a>abstract void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p3420mcpsimp"><a name="p3420mcpsimp"></a><a name="p3420mcpsimp"></a><a href="#section495822616298">onCameraIdle</a>()</p>
<p id="p737425745915"><a name="p737425745915"></a><a name="p737425745915"></a>当相机移动结束时回调此方法，没有待处理动画，并且用户已停止与地图进行交互。必须在主线程中调用。</p>
</td>
</tr>
</tbody>
</table>

## Public Methods<a name="section127571147291"></a>

## onCameraIdle<a name="section495822616298"></a>

<a name="table3423mcpsimp"></a>
<table><thead align="left"><tr id="row3427mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p3429mcpsimp"><a name="p3429mcpsimp"></a><a name="p3429mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row3430mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p3432mcpsimp"><a name="p3432mcpsimp"></a><a name="p3432mcpsimp"></a>public abstract void onCameraIdle()</p>
<p id="p3435mcpsimp"><a name="p3435mcpsimp"></a><a name="p3435mcpsimp"></a>当相机移动结束时回调此方法，没有待处理动画，并且用户已停止与地图进行交互。必须在主线程中调用。</p>
</td>
</tr>
</tbody>
</table>

