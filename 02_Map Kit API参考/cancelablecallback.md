# HuaweiMap.CancelableCallback<a name="ZH-CN_TOPIC_0000001099181228"></a>

-   [Public Method Summary](#section5256441191014)
-   [Public Methods](#section1938934116158)
-   [onCancel](#section1867917349161)
-   [onFinish](#section153541721172312)


<a name="table3181mcpsimp"></a>
<table><thead align="left"><tr id="row3185mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p3187mcpsimp"><a name="p3187mcpsimp"></a><a name="p3187mcpsimp"></a>Interface Info</p>
</th>
</tr>
</thead>
<tbody><tr id="row3188mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p172631917230"><a name="p172631917230"></a><a name="p172631917230"></a>public interface HuaweiMap.CancelableCallback</p>
<p id="p3190mcpsimp"><a name="p3190mcpsimp"></a><a name="p3190mcpsimp"></a>是<a href="huaweimap.md">HuaweiMap</a>类的一个内部接口，任务完成或关闭时的回调接口，包含两个抽象函数<a href="#section1867917349161">onCancel</a>()和<a href="#section153541721172312">onFinish</a>()。</p>
</td>
</tr>
</tbody>
</table>

## Public Method Summary<a name="section5256441191014"></a>

<a name="table3196mcpsimp"></a>
<table><thead align="left"><tr id="row3201mcpsimp"><th class="cellrowborder" valign="top" width="40%" id="mcps1.1.3.1.1"><p id="p3203mcpsimp"><a name="p3203mcpsimp"></a><a name="p3203mcpsimp"></a>Qualifier and Type</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.1.3.1.2"><p id="p3205mcpsimp"><a name="p3205mcpsimp"></a><a name="p3205mcpsimp"></a>Method Name and Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row3206mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p3208mcpsimp"><a name="p3208mcpsimp"></a><a name="p3208mcpsimp"></a>abstract void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p3210mcpsimp"><a name="p3210mcpsimp"></a><a name="p3210mcpsimp"></a><a href="#section1867917349161">onCancel</a>()</p>
<p id="p14848192814456"><a name="p14848192814456"></a><a name="p14848192814456"></a>当<a href="cameraupdate.md">CameraUpdate</a>任务取消时回调此方法。</p>
</td>
</tr>
<tr id="row3211mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p3213mcpsimp"><a name="p3213mcpsimp"></a><a name="p3213mcpsimp"></a>abstract void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p3215mcpsimp"><a name="p3215mcpsimp"></a><a name="p3215mcpsimp"></a><a href="#section153541721172312">onFinish</a>()</p>
<p id="p17679182944520"><a name="p17679182944520"></a><a name="p17679182944520"></a>当<a href="cameraupdate.md">CameraUpdate</a>任务完成时回调此方法。</p>
</td>
</tr>
</tbody>
</table>

## Public Methods<a name="section1938934116158"></a>

## onCancel<a name="section1867917349161"></a>

<a name="table3218mcpsimp"></a>
<table><thead align="left"><tr id="row3222mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p3224mcpsimp"><a name="p3224mcpsimp"></a><a name="p3224mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row3225mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p3227mcpsimp"><a name="p3227mcpsimp"></a><a name="p3227mcpsimp"></a>public abstract void onCancel()</p>
<p id="p05471530235"><a name="p05471530235"></a><a name="p05471530235"></a>当<a href="cameraupdate.md">CameraUpdate</a>任务取消时回调此方法。</p>
</td>
</tr>
</tbody>
</table>

## onFinish<a name="section153541721172312"></a>

<a name="table3238mcpsimp"></a>
<table><thead align="left"><tr id="row3242mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p3244mcpsimp"><a name="p3244mcpsimp"></a><a name="p3244mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row3245mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p3247mcpsimp"><a name="p3247mcpsimp"></a><a name="p3247mcpsimp"></a>public abstract void onFinish()</p>
<p id="p9447040132315"><a name="p9447040132315"></a><a name="p9447040132315"></a>当<a href="cameraupdate.md">CameraUpdate</a>任务完成时回调此方法。</p>
</td>
</tr>
</tbody>
</table>

