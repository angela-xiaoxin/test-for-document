# HuaweiMap.InfoWindowAdapter<a name="EN-US_TOPIC_0000001145860931"></a>

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
<p id="p3267mcpsimp"><a name="p3267mcpsimp"></a><a name="p3267mcpsimp"></a>An internal API of the <a href="huaweimap.md">HuaweiMap</a> class. It provides an adapter for the custom information window view of a marker and contains two abstract methods: <a href="#section1665805611258">getInfoContents</a>(<a href="marker.md">Marker</a>) and <a href="#section1927115112273">getInfoWindow</a>(<a href="marker.md">Marker</a>). When an information window needs to be displayed for a marker, methods provided by this adapter are called regardless of the reason (either a user gesture or a call to the <a href="marker.md#section13223817123711">showInfoWindow</a><strong id="b2037794518459"><a name="b2037794518459"></a><a name="b2037794518459"></a>()</strong> method). Only one information window is displayed at any time. Therefore, the adapter can choose to reuse or create a view each time the methods are called.</p>
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
<p id="p4406185810458"><a name="p4406185810458"></a><a name="p4406185810458"></a>Provides custom content for the default information window of a marker. This method is called only when <a href="#section1927115112273">getInfoWindow</a>(<a href="marker.md">Marker</a>) returns <strong id="b436419204011"><a name="b436419204011"></a><a name="b436419204011"></a>null</strong> for the first time.</p>
</td>
</tr>
<tr id="row3288mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p3290mcpsimp"><a name="p3290mcpsimp"></a><a name="p3290mcpsimp"></a>abstract View</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p3292mcpsimp"><a name="p3292mcpsimp"></a><a name="p3292mcpsimp"></a><a href="#section1927115112273">getInfoWindow</a>(<a href="marker.md">Marker</a> marker)</p>
<p id="p105250194620"><a name="p105250194620"></a><a name="p105250194620"></a>Provides a custom information window for a marker.</p>
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
<p id="p1686993015263"><a name="p1686993015263"></a><a name="p1686993015263"></a>Provides custom content for the default information window of a marker. This method is called only when <a href="#section1927115112273">getInfoWindow</a>(<a href="marker.md">Marker</a>) returns <strong id="b8288133513463"><a name="b8288133513463"></a><a name="b8288133513463"></a>null</strong> for the first time. If this method returns a view, the view will be placed in the default information window. If you change the view after this method is called, the changes may not be presented in the displayed information window. If this method returns <strong id="b19518135219479"><a name="b19518135219479"></a><a name="b19518135219479"></a>null</strong>, the default information window will be displayed.</p>
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
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p3324mcpsimp"><a name="p3324mcpsimp"></a><a name="p3324mcpsimp"></a>Marker for which an information window needs to be displayed.</p>
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
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p3341mcpsimp"><a name="p3341mcpsimp"></a><a name="p3341mcpsimp"></a><strong id="b383510164812"><a name="b383510164812"></a><a name="b383510164812"></a>View</strong> object, which will be used as the custom content of an information window. If <strong id="b290121024818"><a name="b290121024818"></a><a name="b290121024818"></a>null</strong> is returned, the default information window will be used.</p>
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
<p id="p895512812710"><a name="p895512812710"></a><a name="p895512812710"></a>Provides a custom information window view for a marker. If this method returns a view, the view will be used for the entire information window. If you change the view after this method is called, the changes may not be presented in the displayed information window. If this method returns <strong id="b69871914144916"><a name="b69871914144916"></a><a name="b69871914144916"></a>null</strong>, the default information window will be displayed, and its content is provided by <a href="#section1665805611258">getInfoContents</a>(<a href="marker.md">Marker</a>).</p>
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
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p3372mcpsimp"><a name="p3372mcpsimp"></a><a name="p3372mcpsimp"></a>Marker for which an information window needs to be displayed.</p>
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
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p3389mcpsimp"><a name="p3389mcpsimp"></a><a name="p3389mcpsimp"></a><strong id="b12466520508"><a name="b12466520508"></a><a name="b12466520508"></a>View</strong> object, which will be used as a custom information window. If <strong id="b92552575014"><a name="b92552575014"></a><a name="b92552575014"></a>null</strong> is returned, the default information window will be used.</p>
</td>
</tr>
</tbody>
</table>

