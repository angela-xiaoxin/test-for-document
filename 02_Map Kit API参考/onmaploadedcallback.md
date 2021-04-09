# HuaweiMap.OnMapLoadedCallback<a name="ZH-CN_TOPIC_0000001099661092"></a>

-   [Public Method Summary](#section6170945133115)
-   [Public Methods](#section1671994894415)
-   [onMapLoaded](#section25781857124418)


<a name="table4042mcpsimp"></a>
<table><thead align="left"><tr id="row4046mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p4048mcpsimp"><a name="p4048mcpsimp"></a><a name="p4048mcpsimp"></a>Interface Info</p>
</th>
</tr>
</thead>
<tbody><tr id="row4049mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p017421210249"><a name="p017421210249"></a><a name="p017421210249"></a>public interface HuaweiMap.OnMapLoadedListener</p>
<p id="p108146337358"><a name="p108146337358"></a><a name="p108146337358"></a>是<a href="huaweimap.md">HuaweiMap</a>类的一个内部接口，地图加载完成时的回调接口，包含一个抽象函数<a href="#section25781857124418">onMapLoaded</a>()。当地图上所有的图层元素都渲染完成时会回调该接口。如果地图处于不可用状态，或者因为用户不停地与地图交互而导致地图不断变化且未完成加载，则此接口将不会触发回调。</p>
</td>
</tr>
</tbody>
</table>

## Public Method Summary<a name="section6170945133115"></a>

<a name="table4057mcpsimp"></a>
<table><thead align="left"><tr id="row4062mcpsimp"><th class="cellrowborder" valign="top" width="40%" id="mcps1.1.3.1.1"><p id="p4064mcpsimp"><a name="p4064mcpsimp"></a><a name="p4064mcpsimp"></a>Qualifier and Type</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.1.3.1.2"><p id="p4066mcpsimp"><a name="p4066mcpsimp"></a><a name="p4066mcpsimp"></a>Method Name and Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row4067mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p4069mcpsimp"><a name="p4069mcpsimp"></a><a name="p4069mcpsimp"></a>abstract void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p4071mcpsimp"><a name="p4071mcpsimp"></a><a name="p4071mcpsimp"></a><a href="#section25781857124418">onMapLoaded</a>()</p>
<p id="p16954456217"><a name="p16954456217"></a><a name="p16954456217"></a>地图加载完成时回调此方法。</p>
</td>
</tr>
</tbody>
</table>

## Public Methods<a name="section1671994894415"></a>

## onMapLoaded<a name="section25781857124418"></a>

<a name="table4074mcpsimp"></a>
<table><thead align="left"><tr id="row4078mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p4080mcpsimp"><a name="p4080mcpsimp"></a><a name="p4080mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row4081mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p4083mcpsimp"><a name="p4083mcpsimp"></a><a name="p4083mcpsimp"></a>public abstract void onMapLoaded()</p>
<p id="p206361191640"><a name="p206361191640"></a><a name="p206361191640"></a>地图加载完成时回调此方法。此方法只会被回调一次，如果要再次收到回调，则必须重新调用<a href="huaweimap.md">HuaweiMap</a>.<a href="huaweimap.md#section61080560616">setOnMapLoadedCallback</a>(<a href="onmaploadedcallback.md">HuaweiMap.OnMapLoadedCallback</a>)接口再次触发方法回调。</p>
<p id="p3636149244"><a name="p3636149244"></a><a name="p3636149244"></a>回调方法将在主线程中执行。</p>
</td>
</tr>
</tbody>
</table>

