# HuaweiMap.OnCameraIdleListener<a name="EN-US_TOPIC_0000001099661034"></a>

-   [Public Method Summary](#section12344172511249)
-   [Public Methods](#section127571147291)
-   [onCameraIdle](#section495822616298)


<a name="table3391mcpsimp"></a>
<table><thead align="left"><tr id="row3395mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p3397mcpsimp"><a name="p3397mcpsimp"></a><a name="p3397mcpsimp"></a>Interface Info</p>
</th>
</tr>
</thead>
<tbody><tr id="row3398mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p1052083832110"><a name="p1052083832110"></a><a name="p1052083832110"></a>public interface HuaweiMap.OnCameraIdleListener</p>
<p id="p3400mcpsimp"><a name="p3400mcpsimp"></a><a name="p3400mcpsimp"></a>An internal API of the <a href="huaweimap.md">HuaweiMap</a> class, which is used to listen for the camera movement end event. It contains the abstract method <a href="#section495822616298">onCameraIdle</a><strong id="b9696153155319"><a name="b9696153155319"></a><a name="b9696153155319"></a>()</strong>.</p>
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
<p id="p737425745915"><a name="p737425745915"></a><a name="p737425745915"></a>Called when the camera stops moving, no animation needs to be performed, and the user has stopped interacting with the map. This method must be called in the main thread.</p>
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
<p id="p3435mcpsimp"><a name="p3435mcpsimp"></a><a name="p3435mcpsimp"></a>Called when the camera stops moving, no animation needs to be performed, and the user has stopped interacting with the map. This method must be called in the main thread.</p>
</td>
</tr>
</tbody>
</table>

