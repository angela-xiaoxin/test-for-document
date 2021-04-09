# HuaweiMap.OnCameraMoveStartedListener<a name="EN-US_TOPIC_0000001099661062"></a>

-   [Public Field Summary](#section67961113265)
-   [Public Method Summary](#section12405411262)
-   [Public Fields](#section1046222462120)
-   [REASON\_API\_ANIMATION](#section14921853122216)
-   [REASON\_DEVELOPER\_ANIMATION](#section1531873214235)
-   [REASON\_GESTURE](#section198092040202118)
-   [Public Methods](#section18578154422615)
-   [onCameraMoveStarted](#section15331349172613)


<a name="table3547mcpsimp"></a>
<table><thead align="left"><tr id="row3551mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p3553mcpsimp"><a name="p3553mcpsimp"></a><a name="p3553mcpsimp"></a>Interface Info</p>
</th>
</tr>
</thead>
<tbody><tr id="row3554mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p16456152572019"><a name="p16456152572019"></a><a name="p16456152572019"></a>public interface HuaweiMap.OnCameraMoveStartedListener</p>
<p id="p3556mcpsimp"><a name="p3556mcpsimp"></a><a name="p3556mcpsimp"></a>An internal API of the <a href="huaweimap.md">HuaweiMap</a> class, which is used to listen for the camera movement start event. It contains three public fields and the abstract method <a href="#section15331349172613">onCameraMoveStarted</a><strong id="b1746510253319"><a name="b1746510253319"></a><a name="b1746510253319"></a>(int reason)</strong>.</p>
</td>
</tr>
</tbody>
</table>

## Public Field Summary<a name="section67961113265"></a>

<a name="table51207528357"></a>
<table><thead align="left"><tr id="row6121185283516"><th class="cellrowborder" valign="top" width="32.33%" id="mcps1.1.3.1.1"><p id="p1528164471414"><a name="p1528164471414"></a><a name="p1528164471414"></a>Qualifier and Type</p>
</th>
<th class="cellrowborder" valign="top" width="67.67%" id="mcps1.1.3.1.2"><p id="p1554614158108"><a name="p1554614158108"></a><a name="p1554614158108"></a>Field and Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row2012119527357"><td class="cellrowborder" valign="top" width="32.33%" headers="mcps1.1.3.1.1 "><p id="p7975539193810"><a name="p7975539193810"></a><a name="p7975539193810"></a>public static final int</p>
</td>
<td class="cellrowborder" valign="top" width="67.67%" headers="mcps1.1.3.1.2 "><p id="p1335742919474"><a name="p1335742919474"></a><a name="p1335742919474"></a><a href="#section14921853122216">REASON_API_ANIMATION</a></p>
<p id="p18158142110474"><a name="p18158142110474"></a><a name="p18158142110474"></a>Non-gesture animation started in response to a user operation.</p>
</td>
</tr>
<tr id="row8121145210353"><td class="cellrowborder" valign="top" width="32.33%" headers="mcps1.1.3.1.1 "><p id="p1866134223816"><a name="p1866134223816"></a><a name="p1866134223816"></a>public static final int</p>
</td>
<td class="cellrowborder" valign="top" width="67.67%" headers="mcps1.1.3.1.2 "><p id="p14846193219474"><a name="p14846193219474"></a><a name="p14846193219474"></a><a href="#section1531873214235">REASON_DEVELOPER_ANIMATION</a></p>
<p id="p1215810218478"><a name="p1215810218478"></a><a name="p1215810218478"></a>Animation that you started.</p>
</td>
</tr>
<tr id="row118511853616"><td class="cellrowborder" valign="top" width="32.33%" headers="mcps1.1.3.1.1 "><p id="p166538177384"><a name="p166538177384"></a><a name="p166538177384"></a>public static final int</p>
</td>
<td class="cellrowborder" valign="top" width="67.67%" headers="mcps1.1.3.1.2 "><p id="p7468935194712"><a name="p7468935194712"></a><a name="p7468935194712"></a><a href="#section198092040202118">REASON_GESTURE</a></p>
<p id="p201580212479"><a name="p201580212479"></a><a name="p201580212479"></a>Animation started in response to user gestures on a map.</p>
</td>
</tr>
</tbody>
</table>

## Public Method Summary<a name="section12405411262"></a>

<a name="table3595mcpsimp"></a>
<table><thead align="left"><tr id="row3600mcpsimp"><th class="cellrowborder" valign="top" width="40%" id="mcps1.1.3.1.1"><p id="p3602mcpsimp"><a name="p3602mcpsimp"></a><a name="p3602mcpsimp"></a>Qualifier and Type</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.1.3.1.2"><p id="p3604mcpsimp"><a name="p3604mcpsimp"></a><a name="p3604mcpsimp"></a>Method Name and Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row3605mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p3607mcpsimp"><a name="p3607mcpsimp"></a><a name="p3607mcpsimp"></a>abstract void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p3609mcpsimp"><a name="p3609mcpsimp"></a><a name="p3609mcpsimp"></a><a href="#section15331349172613">onCameraMoveStarted</a>(int reason)</p>
<p id="p7709131415"><a name="p7709131415"></a><a name="p7709131415"></a>Called when the idle camera starts moving or the camera movement reason changes.</p>
</td>
</tr>
</tbody>
</table>

## Public Fields<a name="section1046222462120"></a>

## REASON\_API\_ANIMATION<a name="section14921853122216"></a>

<a name="table21921426102319"></a>
<table><thead align="left"><tr id="row3192726182318"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p18192826122310"><a name="p18192826122310"></a><a name="p18192826122310"></a>Fields</p>
</th>
</tr>
</thead>
<tbody><tr id="row9192626172316"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p13165165533813"><a name="p13165165533813"></a><a name="p13165165533813"></a>public static final int REASON_API_ANIMATION</p>
<p id="p81921026192319"><a name="p81921026192319"></a><a name="p81921026192319"></a>Non-gesture animation started in response to a user operation.</p>
<p id="p49022293529"><a name="p49022293529"></a><a name="p49022293529"></a><strong id="b3902192945216"><a name="b3902192945216"></a><a name="b3902192945216"></a>REASON_API_ANIMATION</strong>: 2</p>
<p id="p127751542165617"><a name="p127751542165617"></a><a name="p127751542165617"></a>For other constant values, please refer to <a href="constant-values.md#section12896623165220">Constant-values</a>.</p>
</td>
</tr>
</tbody>
</table>

## REASON\_DEVELOPER\_ANIMATION<a name="section1531873214235"></a>

<a name="table196510409232"></a>
<table><thead align="left"><tr id="row10966940202319"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p1296634072314"><a name="p1296634072314"></a><a name="p1296634072314"></a>Fields</p>
</th>
</tr>
</thead>
<tbody><tr id="row696644016234"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p103811158143814"><a name="p103811158143814"></a><a name="p103811158143814"></a>public static final int REASON_DEVELOPER_ANIMATION</p>
<p id="p596644072319"><a name="p596644072319"></a><a name="p596644072319"></a>Animation that you started.</p>
<p id="p12583918145215"><a name="p12583918145215"></a><a name="p12583918145215"></a><strong id="b11583141855216"><a name="b11583141855216"></a><a name="b11583141855216"></a>REASON_DEVELOPER_ANIMATION</strong>: 3</p>
<p id="p1032914472508"><a name="p1032914472508"></a><a name="p1032914472508"></a>For other constant values, please refer to <a href="constant-values.md#section12896623165220">Constant-values</a>.</p>
</td>
</tr>
</tbody>
</table>

## REASON\_GESTURE<a name="section198092040202118"></a>

<a name="table1255354452212"></a>
<table><thead align="left"><tr id="row65541441229"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p10554944132214"><a name="p10554944132214"></a><a name="p10554944132214"></a>Fields</p>
</th>
</tr>
</thead>
<tbody><tr id="row125541144132214"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p14825519385"><a name="p14825519385"></a><a name="p14825519385"></a>public static final int REASON_GESTURE</p>
<p id="p1255410440225"><a name="p1255410440225"></a><a name="p1255410440225"></a>Animation started in response to user gestures on a map.</p>
<p id="p1550011785213"><a name="p1550011785213"></a><a name="p1550011785213"></a><strong id="b3500372526"><a name="b3500372526"></a><a name="b3500372526"></a>REASON_GESTURE</strong>: 1</p>
<p id="p1539313196564"><a name="p1539313196564"></a><a name="p1539313196564"></a>For other constant values, please refer to <a href="constant-values.md#section12896623165220">Constant-values</a>.</p>
</td>
</tr>
</tbody>
</table>

## Public Methods<a name="section18578154422615"></a>

## onCameraMoveStarted<a name="section15331349172613"></a>

<a name="table3612mcpsimp"></a>
<table><thead align="left"><tr id="row3616mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p3618mcpsimp"><a name="p3618mcpsimp"></a><a name="p3618mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row3619mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p3621mcpsimp"><a name="p3621mcpsimp"></a><a name="p3621mcpsimp"></a>public abstract void onCameraMoveStarted(int reason)</p>
<p id="p3624mcpsimp"><a name="p3624mcpsimp"></a><a name="p3624mcpsimp"></a>Called when the idle camera starts moving or the camera movement reason changes. Do not update the camera in this method. This method must be called in the main thread.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table3627mcpsimp"></a>
<table><thead align="left"><tr id="row3632mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p3634mcpsimp"><a name="p3634mcpsimp"></a><a name="p3634mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p3636mcpsimp"><a name="p3636mcpsimp"></a><a name="p3636mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row3637mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p3639mcpsimp"><a name="p3639mcpsimp"></a><a name="p3639mcpsimp"></a>reason</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p3641mcpsimp"><a name="p3641mcpsimp"></a><a name="p3641mcpsimp"></a>Camera movement reason. The options are as follows:</p>
<a name="ul96521655163514"></a><a name="ul96521655163514"></a><ul id="ul96521655163514"><li><a href="#section198092040202118">REASON_GESTURE</a>: A user makes a gesture on the map.</li><li><a href="#section14921853122216">REASON_API_ANIMATION</a>: The default animation is triggered during user interaction.</li><li><a href="#section1531873214235">REASON_DEVELOPER_ANIMATION</a>: You start the animation.</li></ul>
</td>
</tr>
</tbody>
</table>

