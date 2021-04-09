# HuaweiMap.OnCircleClickListener<a name="EN-US_TOPIC_0000001099661084"></a>

-   [Public Method Summary](#section677532217276)
-   [Public Methods](#section2984195303520)
-   [onCircleClick](#section07842151362)


<a name="table3646mcpsimp"></a>
<table><thead align="left"><tr id="row3650mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p3652mcpsimp"><a name="p3652mcpsimp"></a><a name="p3652mcpsimp"></a>Interface Info</p>
</th>
</tr>
</thead>
<tbody><tr id="row3653mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p208951321142116"><a name="p208951321142116"></a><a name="p208951321142116"></a>public interface HuaweiMap.OnCircleClickListener</p>
<p id="p3655mcpsimp"><a name="p3655mcpsimp"></a><a name="p3655mcpsimp"></a>An internal API of the <a href="huaweimap.md">HuaweiMap</a> class, which is used to listen for the circle tap event. It contains the abstract method <a href="#section07842151362">onCircleClick</a><strong id="b184191722115510"><a name="b184191722115510"></a><a name="b184191722115510"></a>(</strong><a href="circle.md">Circle</a><strong id="b1143562465517"><a name="b1143562465517"></a><a name="b1143562465517"></a>)</strong>.</p>
</td>
</tr>
</tbody>
</table>

## Public Method Summary<a name="section677532217276"></a>

<a name="table3661mcpsimp"></a>
<table><thead align="left"><tr id="row3666mcpsimp"><th class="cellrowborder" valign="top" width="40%" id="mcps1.1.3.1.1"><p id="p3668mcpsimp"><a name="p3668mcpsimp"></a><a name="p3668mcpsimp"></a>Qualifier and Type</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.1.3.1.2"><p id="p3670mcpsimp"><a name="p3670mcpsimp"></a><a name="p3670mcpsimp"></a>Method Name and Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row3671mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p3673mcpsimp"><a name="p3673mcpsimp"></a><a name="p3673mcpsimp"></a>abstract void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p3675mcpsimp"><a name="p3675mcpsimp"></a><a name="p3675mcpsimp"></a><a href="#section07842151362">onCircleClick</a>(<a href="circle.md">Circle</a> circle)</p>
<p id="p194011249113"><a name="p194011249113"></a><a name="p194011249113"></a>Called when a circle is tapped.</p>
</td>
</tr>
</tbody>
</table>

## Public Methods<a name="section2984195303520"></a>

## onCircleClick<a name="section07842151362"></a>

<a name="table3678mcpsimp"></a>
<table><thead align="left"><tr id="row3682mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p3684mcpsimp"><a name="p3684mcpsimp"></a><a name="p3684mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row3685mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p3687mcpsimp"><a name="p3687mcpsimp"></a><a name="p3687mcpsimp"></a>public abstract void onCircleClick(<a href="circle.md">Circle</a> circle)</p>
<p id="p9553124013612"><a name="p9553124013612"></a><a name="p9553124013612"></a>Called when a circle is tapped. This method must be called in the main thread.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table3693mcpsimp"></a>
<table><thead align="left"><tr id="row3698mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p3700mcpsimp"><a name="p3700mcpsimp"></a><a name="p3700mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p3702mcpsimp"><a name="p3702mcpsimp"></a><a name="p3702mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row3703mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p3705mcpsimp"><a name="p3705mcpsimp"></a><a name="p3705mcpsimp"></a>circle</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p3707mcpsimp"><a name="p3707mcpsimp"></a><a name="p3707mcpsimp"></a>Circle that is tapped.</p>
</td>
</tr>
</tbody>
</table>

