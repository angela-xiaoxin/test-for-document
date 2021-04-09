# HuaweiMap.OnCameraMoveListener<a name="EN-US_TOPIC_0000001099341066"></a>

-   [Public Method Summary](#section193131669256)
-   [Public Methods](#section13957489326)
-   [onCameraMove](#section113245916324)


<a name="table3495mcpsimp"></a>
<table><thead align="left"><tr id="row3499mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p3501mcpsimp"><a name="p3501mcpsimp"></a><a name="p3501mcpsimp"></a>Interface Info</p>
</th>
</tr>
</thead>
<tbody><tr id="row3502mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p5314631182020"><a name="p5314631182020"></a><a name="p5314631182020"></a>public interface HuaweiMap.OnCameraMoveListener</p>
<p id="p3504mcpsimp"><a name="p3504mcpsimp"></a><a name="p3504mcpsimp"></a>An internal API of the <a href="huaweimap.md">HuaweiMap</a> class, which is used to listen for the camera movement event. It contains the abstract method <a href="#section113245916324">onCameraMove</a><strong id="b10194362595"><a name="b10194362595"></a><a name="b10194362595"></a>()</strong>.</p>
</td>
</tr>
</tbody>
</table>

## Public Method Summary<a name="section193131669256"></a>

<a name="table3510mcpsimp"></a>
<table><thead align="left"><tr id="row3515mcpsimp"><th class="cellrowborder" valign="top" width="40%" id="mcps1.1.3.1.1"><p id="p3517mcpsimp"><a name="p3517mcpsimp"></a><a name="p3517mcpsimp"></a>Qualifier and Type</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.1.3.1.2"><p id="p3519mcpsimp"><a name="p3519mcpsimp"></a><a name="p3519mcpsimp"></a>Method Name and Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row3520mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p3522mcpsimp"><a name="p3522mcpsimp"></a><a name="p3522mcpsimp"></a>abstract void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p3524mcpsimp"><a name="p3524mcpsimp"></a><a name="p3524mcpsimp"></a><a href="#section113245916324">onCameraMove</a>()</p>
<p id="p46171545909"><a name="p46171545909"></a><a name="p46171545909"></a>Called repeatedly when the camera moves after the <a href="oncameramovestartedlistener.md#section15331349172613">onCameraMoveStarted</a> method is called.</p>
</td>
</tr>
</tbody>
</table>

## Public Methods<a name="section13957489326"></a>

## onCameraMove<a name="section113245916324"></a>

<a name="table3527mcpsimp"></a>
<table><thead align="left"><tr id="row3531mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p3533mcpsimp"><a name="p3533mcpsimp"></a><a name="p3533mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row3534mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p3536mcpsimp"><a name="p3536mcpsimp"></a><a name="p3536mcpsimp"></a>public abstract void onCameraMove()</p>
<p id="p3539mcpsimp"><a name="p3539mcpsimp"></a><a name="p3539mcpsimp"></a>Called repeatedly when the camera moves after the <a href="oncameramovestartedlistener.md#section15331349172613">onCameraMoveStarted</a> method is called. This method may be called once per frame. Therefore, do not perform high-consumption operations. This method must be called in the main thread.</p>
</td>
</tr>
</tbody>
</table>

