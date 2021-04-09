# CameraUpdate<a name="EN-US_TOPIC_0000001145781029"></a>

-   [Public Method Summary](#section196311271188)
-   [Public Methods](#section5258112311597)
-   [getCameraUpdate](#section12885172015592)
-   [getCameraUpdateParam](#section177569525173)


<a name="table103mcpsimp"></a>
<table><thead align="left"><tr id="row107mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p25980mcpsimp"><a name="p25980mcpsimp"></a><a name="p25980mcpsimp"></a>Class Info</p>
</th>
</tr>
</thead>
<tbody><tr id="row110mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p963912113816"><a name="p963912113816"></a><a name="p963912113816"></a>public final class CameraUpdate</p>
<p id="p112mcpsimp"><a name="p112mcpsimp"></a><a name="p112mcpsimp"></a>Defines camera movement parameters. You can call <a href="huaweimap.md#section13382161444614">animateCamera</a>(<a href="cameraupdate.md">CameraUpdate</a>) or <a href="huaweimap.md#section168451531308">moveCamera</a>(<a href="cameraupdate.md">CameraUpdate</a>) to move the camera of a map. To obtain a <a href="cameraupdate.md">CameraUpdate</a> object, use the <a href="cameraupdatefactory.md">CameraUpdateFactory</a> class by referring to the class description.</p>
</td>
</tr>
</tbody>
</table>

## Public Method Summary<a name="section196311271188"></a>

<a name="table1890314411112"></a>
<table><thead align="left"><tr id="row0903241131117"><th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.1"><p id="p18903184141115"><a name="p18903184141115"></a><a name="p18903184141115"></a>Qualifier and Type</p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.2"><p id="p590315416114"><a name="p590315416114"></a><a name="p590315416114"></a>Method Name and Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row4903154118118"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p8903141171117"><a name="p8903141171117"></a><a name="p8903141171117"></a>CameraUpdateParam</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p181085137157"><a name="p181085137157"></a><a name="p181085137157"></a><a href="#section12885172015592">getCameraUpdate</a>()</p>
<p id="p72634715506"><a name="p72634715506"></a><a name="p72634715506"></a>Obtains a <a href="cameraupdate.md">CameraUpdate</a> object for updating camera parameters.</p>
<div class="caution" id="note7119174217541"><a name="note7119174217541"></a><a name="note7119174217541"></a><span class="cautiontitle"> CAUTION: </span><div class="cautionbody"><p id="p1119114245418"><a name="p1119114245418"></a><a name="p1119114245418"></a>This method has been deprecated. To obtain a <a href="cameraupdate.md">CameraUpdate</a> object for updating camera parameters, call <a href="#section177569525173">getCameraUpdateParam</a>().</p>
</div></div>
</td>
</tr>
<tr id="row2813161341416"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p198146135143"><a name="p198146135143"></a><a name="p198146135143"></a>CameraUpdateParam</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p1481421391414"><a name="p1481421391414"></a><a name="p1481421391414"></a><a href="#section177569525173">getCameraUpdateParam</a>()</p>
<p id="p4704438141615"><a name="p4704438141615"></a><a name="p4704438141615"></a>Obtains a <a href="cameraupdate.md">CameraUpdate</a> object for updating camera parameters.</p>
</td>
</tr>
</tbody>
</table>

## Public Methods<a name="section5258112311597"></a>

## getCameraUpdate<a name="section12885172015592"></a>

>![](public_sys-resources/icon-caution.gif) **CAUTION:** 
>This method has been deprecated. To obtain a  [CameraUpdate](cameraupdate.md)  object for updating camera parameters, call  [getCameraUpdateParam](#section177569525173)\(\).

<a name="table1773216367199"></a>
<table><thead align="left"><tr id="row137321436181911"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p177321036101910"><a name="p177321036101910"></a><a name="p177321036101910"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row197321036131914"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p97321036141919"><a name="p97321036141919"></a><a name="p97321036141919"></a>public CameraUpdateParam getCameraUpdate()</p>
<p id="p162914176548"><a name="p162914176548"></a><a name="p162914176548"></a>Obtains a <a href="cameraupdate.md">CameraUpdate</a> object for updating camera parameters.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table647317194239"></a>
<table><thead align="left"><tr id="row847361919238"><th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.1"><p id="p1473519182315"><a name="p1473519182315"></a><a name="p1473519182315"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.2"><p id="p347315193233"><a name="p347315193233"></a><a name="p347315193233"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row34730199230"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p54733192234"><a name="p54733192234"></a><a name="p54733192234"></a>CameraUpdateParam</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p13473171902317"><a name="p13473171902317"></a><a name="p13473171902317"></a><strong id="b77113574598"><a name="b77113574598"></a><a name="b77113574598"></a>CameraUpdateParam</strong> object for updating camera parameters.</p>
</td>
</tr>
</tbody>
</table>

## getCameraUpdateParam<a name="section177569525173"></a>

<a name="table12757185210176"></a>
<table><thead align="left"><tr id="row4757125241710"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p1775713522178"><a name="p1775713522178"></a><a name="p1775713522178"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row18757552151710"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p2757115241711"><a name="p2757115241711"></a><a name="p2757115241711"></a>public final CameraUpdateParam getCameraUpdateParam()</p>
<p id="p575735211173"><a name="p575735211173"></a><a name="p575735211173"></a>Obtains a <a href="cameraupdate.md">CameraUpdate</a> object for updating camera parameters.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table167574526172"></a>
<table><thead align="left"><tr id="row207571452111711"><th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.1"><p id="p575765217179"><a name="p575765217179"></a><a name="p575765217179"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.2"><p id="p2075716529178"><a name="p2075716529178"></a><a name="p2075716529178"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row27571852131710"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p575725218170"><a name="p575725218170"></a><a name="p575725218170"></a>CameraUpdateParam</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p275719523173"><a name="p275719523173"></a><a name="p275719523173"></a><strong id="b246981691"><a name="b246981691"></a><a name="b246981691"></a>CameraUpdateParam</strong> object for updating camera parameters.</p>
</td>
</tr>
</tbody>
</table>

