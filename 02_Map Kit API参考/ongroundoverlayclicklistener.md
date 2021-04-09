# HuaweiMap.OnGroundOverlayClickListener<a name="ZH-CN_TOPIC_0000001145541105"></a>

-   [Public Method Summary](#section1783473562712)
-   [Public Methods](#section1940832415371)
-   [onGroundOverlayClick](#section1448704115373)


<a name="table3712mcpsimp"></a>
<table><thead align="left"><tr id="row3716mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p3718mcpsimp"><a name="p3718mcpsimp"></a><a name="p3718mcpsimp"></a>Interface Info</p>
</th>
</tr>
</thead>
<tbody><tr id="row3719mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p1933164692315"><a name="p1933164692315"></a><a name="p1933164692315"></a>public interface HuaweiMap.OnGroundOverlayClickListener</p>
<p id="p3721mcpsimp"><a name="p3721mcpsimp"></a><a name="p3721mcpsimp"></a>是<a href="huaweimap.md">HuaweiMap</a>类的一个内部接口，表示覆盖物点击事件的侦听器，包含一个抽象函数<a href="#section1448704115373">onGroundOverlayClick</a>(<a href="groundoverlay.md">GroundOverlay</a>)。</p>
</td>
</tr>
</tbody>
</table>

## Public Method Summary<a name="section1783473562712"></a>

<a name="table3727mcpsimp"></a>
<table><thead align="left"><tr id="row3732mcpsimp"><th class="cellrowborder" valign="top" width="40%" id="mcps1.1.3.1.1"><p id="p081120285386"><a name="p081120285386"></a><a name="p081120285386"></a>Qualifier and Type</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.1.3.1.2"><p id="p681112883813"><a name="p681112883813"></a><a name="p681112883813"></a>Method Name and Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row3737mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p3739mcpsimp"><a name="p3739mcpsimp"></a><a name="p3739mcpsimp"></a>abstract void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p3741mcpsimp"><a name="p3741mcpsimp"></a><a name="p3741mcpsimp"></a><a href="#section1448704115373">onGroundOverlayClick</a>(<a href="groundoverlay.md">GroundOverlay</a> groundOverlay)</p>
<p id="p3895133916115"><a name="p3895133916115"></a><a name="p3895133916115"></a>点击覆盖物时回调此方法。</p>
</td>
</tr>
</tbody>
</table>

## Public Methods<a name="section1940832415371"></a>

## onGroundOverlayClick<a name="section1448704115373"></a>

<a name="table3744mcpsimp"></a>
<table><thead align="left"><tr id="row3748mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p3750mcpsimp"><a name="p3750mcpsimp"></a><a name="p3750mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row3751mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p3753mcpsimp"><a name="p3753mcpsimp"></a><a name="p3753mcpsimp"></a>public abstract void onGroundOverlayClick(<a href="groundoverlay.md">GroundOverlay</a> groundOverlay)</p>
<p id="p3756mcpsimp"><a name="p3756mcpsimp"></a><a name="p3756mcpsimp"></a>点击覆盖物时回调此方法。必须在主线程中执行。</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table3759mcpsimp"></a>
<table><thead align="left"><tr id="row3764mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p3766mcpsimp"><a name="p3766mcpsimp"></a><a name="p3766mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p3768mcpsimp"><a name="p3768mcpsimp"></a><a name="p3768mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row3769mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p3771mcpsimp"><a name="p3771mcpsimp"></a><a name="p3771mcpsimp"></a>groundOverlay</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p3773mcpsimp"><a name="p3773mcpsimp"></a><a name="p3773mcpsimp"></a>被点击的覆盖物。</p>
</td>
</tr>
</tbody>
</table>

