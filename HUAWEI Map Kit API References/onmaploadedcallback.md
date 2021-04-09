# HuaweiMap.OnMapLoadedCallback<a name="EN-US_TOPIC_0000001099661092"></a>

-   [Public Method Summary](#section6170945133115)
-   [Public Methods](#section1671994894415)
-   [onMapLoaded](#section25781857124418)


<a name="table4042mcpsimp"></a>
<table><thead align="left"><tr id="row4046mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p4048mcpsimp"><a name="p4048mcpsimp"></a><a name="p4048mcpsimp"></a>Interface Info</p>
</th>
</tr>
</thead>
<tbody><tr id="row4049mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p017421210249"><a name="p017421210249"></a><a name="p017421210249"></a>public interface HuaweiMap.OnMapLoadedListener</p>
<p id="p108146337358"><a name="p108146337358"></a><a name="p108146337358"></a>An internal API of the <a href="huaweimap.md">HuaweiMap</a> class, which is called when the map loading is completed. It contains the abstract method <a href="#section25781857124418">onMapLoaded</a>(). </p>
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
<p id="p16954456217"><a name="p16954456217"></a><a name="p16954456217"></a>Called when the map loading is completed.</p>
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
<p id="p206361191640"><a name="p206361191640"></a><a name="p206361191640"></a>Called when the map loading is completed. This method is called only once. If you want to receive a callback notification again, you must call <a href="huaweimap.md">HuaweiMap</a>.<a href="huaweimap.md#section61080560616">setOnMapLoadedCallback</a>(<a href="onmaploadedcallback.md">HuaweiMap.OnMapLoadedCallback</a>) again to request another callback.</p>
<p id="p3636149244"><a name="p3636149244"></a><a name="p3636149244"></a>This method will be executed in the main thread.</p>
</td>
</tr>
</tbody>
</table>

