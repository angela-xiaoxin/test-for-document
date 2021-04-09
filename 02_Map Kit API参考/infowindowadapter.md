# HuaweiMap.InfoWindowAdapter<a name="ZH-CN_TOPIC_0000001145860931"></a>

-   [Public Method Summary](#section18689195552318)
-   [Public Methods](#section141641934152511)
-   [getInfoContents](#section1665805611258)
-   [getInfoWindow](#section1927115112273)


<a name="table3258mcpsimp"></a>
<table><thead align="left"><tr id="row3262mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p3264mcpsimp"><a name="p3264mcpsimp"></a><a name="p3264mcpsimp"></a>Interface Info</p>
</th>
</tr>
</thead>
<tbody><tr id="row3265mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p1088861532318"><a name="p1088861532318"></a><a name="p1088861532318"></a>public interface HuaweiMap.InfoWindowAdapter</p>
<p id="p3267mcpsimp"><a name="p3267mcpsimp"></a><a name="p3267mcpsimp"></a>是<a href="huaweimap.md">HuaweiMap</a>类的一个内部接口，提供自定义标记信息窗口视图的适配器，包含两个抽象函数<a href="#section1665805611258">getInfoContents</a>(<a href="marker.md">Marker</a>)和<a href="#section1927115112273">getInfoWindow</a>(<a href="marker.md">Marker</a>)。当需要显示标记信息窗口时，无论是出于何种原因（不管是因为用户手势还是调用了<a href="marker.md#section13223817123711">showInfoWindow</a>()方法），都会调用适配器提供的方法。由于任何时候都只显示一个标记信息窗口，因此适配器可以选择重用视图，也可以选择在每次调用方法时创建新视图。</p>
</td>
</tr>
</tbody>
</table>

## Public Method Summary<a name="section18689195552318"></a>

<a name="table3273mcpsimp"></a>
<table><thead align="left"><tr id="row3278mcpsimp"><th class="cellrowborder" valign="top" width="40%" id="mcps1.1.3.1.1"><p id="p3280mcpsimp"><a name="p3280mcpsimp"></a><a name="p3280mcpsimp"></a>Qualifier and Type</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.1.3.1.2"><p id="p3282mcpsimp"><a name="p3282mcpsimp"></a><a name="p3282mcpsimp"></a>Method Name and Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row3283mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p3285mcpsimp"><a name="p3285mcpsimp"></a><a name="p3285mcpsimp"></a>abstract View</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p3287mcpsimp"><a name="p3287mcpsimp"></a><a name="p3287mcpsimp"></a><a href="#section1665805611258">getInfoContents</a>(<a href="marker.md">Marker</a> marker)</p>
<p id="p4406185810458"><a name="p4406185810458"></a><a name="p4406185810458"></a>为标记的默认信息窗口提供自定义内容，仅当<a href="#section1927115112273">getInfoWindow</a>(<a href="marker.md">Marker</a>)首次返回null时才会被调用。</p>
</td>
</tr>
<tr id="row3288mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p3290mcpsimp"><a name="p3290mcpsimp"></a><a name="p3290mcpsimp"></a>abstract View</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p3292mcpsimp"><a name="p3292mcpsimp"></a><a name="p3292mcpsimp"></a><a href="#section1927115112273">getInfoWindow</a>(<a href="marker.md">Marker</a> marker)</p>
<p id="p105250194620"><a name="p105250194620"></a><a name="p105250194620"></a>为标记提供自定义信息窗口。</p>
</td>
</tr>
</tbody>
</table>

## Public Methods<a name="section141641934152511"></a>

## getInfoContents<a name="section1665805611258"></a>

<a name="table3295mcpsimp"></a>
<table><thead align="left"><tr id="row3299mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p3301mcpsimp"><a name="p3301mcpsimp"></a><a name="p3301mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row3302mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p3304mcpsimp"><a name="p3304mcpsimp"></a><a name="p3304mcpsimp"></a>public abstract View getInfoContents(<a href="marker.md">Marker</a> marker)</p>
<p id="p1686993015263"><a name="p1686993015263"></a><a name="p1686993015263"></a>此方法为标记的默认信息窗口提供自定义内容，仅当<a href="#section1927115112273">getInfoWindow</a>(<a href="marker.md">Marker</a>)首次返回null时才会被调用。如果此方法返回一个视图，它将被放置在默认信息窗口里。如果您在此方法被调用之后更改视图，则这些更改不一定会反映在展示的信息窗口中。如果此方法返回null，则将展示默认信息窗口。</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table3310mcpsimp"></a>
<table><thead align="left"><tr id="row3315mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p3317mcpsimp"><a name="p3317mcpsimp"></a><a name="p3317mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p3319mcpsimp"><a name="p3319mcpsimp"></a><a name="p3319mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row3320mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p3322mcpsimp"><a name="p3322mcpsimp"></a><a name="p3322mcpsimp"></a>marker</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p3324mcpsimp"><a name="p3324mcpsimp"></a><a name="p3324mcpsimp"></a>待填充的标记。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table3327mcpsimp"></a>
<table><thead align="left"><tr id="row3332mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p3334mcpsimp"><a name="p3334mcpsimp"></a><a name="p3334mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p3336mcpsimp"><a name="p3336mcpsimp"></a><a name="p3336mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row3337mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p3339mcpsimp"><a name="p3339mcpsimp"></a><a name="p3339mcpsimp"></a>View</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p3341mcpsimp"><a name="p3341mcpsimp"></a><a name="p3341mcpsimp"></a>View对象，返回一个内容自定义的标记信息窗口，如果返回为null，将使用默认标记信息窗口。</p>
</td>
</tr>
</tbody>
</table>

## getInfoWindow<a name="section1927115112273"></a>

<a name="table3343mcpsimp"></a>
<table><thead align="left"><tr id="row3347mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p3349mcpsimp"><a name="p3349mcpsimp"></a><a name="p3349mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row3350mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p3352mcpsimp"><a name="p3352mcpsimp"></a><a name="p3352mcpsimp"></a>public abstract View getInfoWindow(<a href="marker.md">Marker</a> marker)</p>
<p id="p895512812710"><a name="p895512812710"></a><a name="p895512812710"></a>为标记提供自定义信息窗口。如果此方法返回一个视图，则它将用于整个信息窗口。如果您在此方法被调用之后更改此视图，则这些更改不一定会反映在展示的信息窗口中。如果此方法返回null，则将展示默认信息窗口，其内容由<a href="#section1665805611258">getInfoContents</a>(<a href="marker.md">Marker</a>)提供。</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table3358mcpsimp"></a>
<table><thead align="left"><tr id="row3363mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p3365mcpsimp"><a name="p3365mcpsimp"></a><a name="p3365mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p3367mcpsimp"><a name="p3367mcpsimp"></a><a name="p3367mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row3368mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p3370mcpsimp"><a name="p3370mcpsimp"></a><a name="p3370mcpsimp"></a>marker</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p3372mcpsimp"><a name="p3372mcpsimp"></a><a name="p3372mcpsimp"></a>待填充的标记。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table3375mcpsimp"></a>
<table><thead align="left"><tr id="row3380mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p3382mcpsimp"><a name="p3382mcpsimp"></a><a name="p3382mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p3384mcpsimp"><a name="p3384mcpsimp"></a><a name="p3384mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row3385mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p3387mcpsimp"><a name="p3387mcpsimp"></a><a name="p3387mcpsimp"></a>View</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p3389mcpsimp"><a name="p3389mcpsimp"></a><a name="p3389mcpsimp"></a>View对象，返回一个自定义的标记信息窗口，如果返回为null，将使用默认的标记信息窗口。</p>
</td>
</tr>
</tbody>
</table>

