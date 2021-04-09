# PointOfInterest<a name="EN-US_TOPIC_0000001099181236"></a>

-   [Public Field Summary](#section1538112031519)
-   [Public Constructor Summary](#section44411353156)
-   [Public Method Summary](#section433765510157)
-   [Public Constructors](#section042681119126)
-   [PointOfInterest](#section147561345184912)


<a name="table17243mcpsimp"></a>
<table><thead align="left"><tr id="row17247mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p17249mcpsimp"><a name="p17249mcpsimp"></a><a name="p17249mcpsimp"></a>Class Info</p>
</th>
</tr>
</thead>
<tbody><tr id="row17250mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p48511453114112"><a name="p48511453114112"></a><a name="p48511453114112"></a>public class PointOfInterest</p>
<p id="p17252mcpsimp"><a name="p17252mcpsimp"></a><a name="p17252mcpsimp"></a>An object that contains attributes about a tapped POI.</p>
</td>
</tr>
</tbody>
</table>

## Public Field Summary<a name="section1538112031519"></a>

<a name="table51207528357"></a>
<table><thead align="left"><tr id="row6121185283516"><th class="cellrowborder" valign="top" width="32.21%" id="mcps1.1.3.1.1"><p id="p1528164471414"><a name="p1528164471414"></a><a name="p1528164471414"></a>Qualifier and Type</p>
</th>
<th class="cellrowborder" valign="top" width="67.78999999999999%" id="mcps1.1.3.1.2"><p id="p1554614158108"><a name="p1554614158108"></a><a name="p1554614158108"></a>Field and Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row2012119527357"><td class="cellrowborder" valign="top" width="32.21%" headers="mcps1.1.3.1.1 "><p id="p18686543867"><a name="p18686543867"></a><a name="p18686543867"></a><a href="latlng.md">LatLng</a></p>
</td>
<td class="cellrowborder" valign="top" width="67.78999999999999%" headers="mcps1.1.3.1.2 "><p id="p16640164617617"><a name="p16640164617617"></a><a name="p16640164617617"></a>latLng</p>
<p id="p176459391764"><a name="p176459391764"></a><a name="p176459391764"></a>Position of a POI.</p>
</td>
</tr>
<tr id="row1082618212224"><td class="cellrowborder" valign="top" width="32.21%" headers="mcps1.1.3.1.1 "><p id="p196861343061"><a name="p196861343061"></a><a name="p196861343061"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="67.78999999999999%" headers="mcps1.1.3.1.2 "><p id="p132889521612"><a name="p132889521612"></a><a name="p132889521612"></a>name</p>
<p id="p1364673914613"><a name="p1364673914613"></a><a name="p1364673914613"></a>Name of a POI.</p>
</td>
</tr>
<tr id="row8965818847"><td class="cellrowborder" valign="top" width="32.21%" headers="mcps1.1.3.1.1 "><p id="p9686243869"><a name="p9686243869"></a><a name="p9686243869"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="67.78999999999999%" headers="mcps1.1.3.1.2 "><p id="p745815491263"><a name="p745815491263"></a><a name="p745815491263"></a>placeId</p>
<p id="p6645439969"><a name="p6645439969"></a><a name="p6645439969"></a>ID of a POI.</p>
</td>
</tr>
</tbody>
</table>

## Public Constructor Summary<a name="section44411353156"></a>

<a name="table17289mcpsimp"></a>
<table><thead align="left"><tr id="row17293mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p145mcpsimp"><a name="p145mcpsimp"></a><a name="p145mcpsimp"></a>Constructor Name</p>
</th>
</tr>
</thead>
<tbody><tr id="row17296mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p17298mcpsimp"><a name="p17298mcpsimp"></a><a name="p17298mcpsimp"></a><a href="#section147561345184912">PointOfInterest</a>(<a href="latlng.md">LatLng</a> latLng, String placeId, String name)</p>
<p id="p18641919141213"><a name="p18641919141213"></a><a name="p18641919141213"></a>Creates a <a href="pointofinterest.md">PointOfInterest</a> object based on specified parameters.</p>
</td>
</tr>
</tbody>
</table>

## Public Method Summary<a name="section433765510157"></a>

<a name="table17300mcpsimp"></a>
<table><thead align="left"><tr id="row17305mcpsimp"><th class="cellrowborder" valign="top" width="40%" id="mcps1.1.3.1.1"><p id="p081120285386"><a name="p081120285386"></a><a name="p081120285386"></a>Qualifier and Type</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.1.3.1.2"><p id="p681112883813"><a name="p681112883813"></a><a name="p681112883813"></a>Method Name and Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row17310mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p17312mcpsimp"><a name="p17312mcpsimp"></a><a name="p17312mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p17314mcpsimp"><a name="p17314mcpsimp"></a><a name="p17314mcpsimp"></a>writeToParcel(Parcel out, int flags)</p>
<p id="p21145318207"><a name="p21145318207"></a><a name="p21145318207"></a>Serializes data.</p>
</td>
</tr>
</tbody>
</table>

## Public Constructors<a name="section042681119126"></a>

## PointOfInterest<a name="section147561345184912"></a>

<a name="table227mcpsimp"></a>
<table><thead align="left"><tr id="row231mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p233mcpsimp"><a name="p233mcpsimp"></a><a name="p233mcpsimp"></a>Constructor</p>
</th>
</tr>
</thead>
<tbody><tr id="row235mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p98575855418"><a name="p98575855418"></a><a name="p98575855418"></a>public <a href="pointofinterest.md">PointOfInterest</a>(<a href="latlng.md">LatLng</a> latLng, String placeId, String name)</p>
<p id="p985714811543"><a name="p985714811543"></a><a name="p985714811543"></a>Creates a <a href="pointofinterest.md">PointOfInterest</a> object based on specified parameters.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table243mcpsimp"></a>
<table><thead align="left"><tr id="row248mcpsimp"><th class="cellrowborder" valign="top" width="43%" id="mcps1.1.3.1.1"><p id="p250mcpsimp"><a name="p250mcpsimp"></a><a name="p250mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="56.99999999999999%" id="mcps1.1.3.1.2"><p id="p253mcpsimp"><a name="p253mcpsimp"></a><a name="p253mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row255mcpsimp"><td class="cellrowborder" valign="top" width="43%" headers="mcps1.1.3.1.1 "><p id="p6815182565014"><a name="p6815182565014"></a><a name="p6815182565014"></a>latLng</p>
</td>
<td class="cellrowborder" valign="top" width="56.99999999999999%" headers="mcps1.1.3.1.2 "><p id="p181418256500"><a name="p181418256500"></a><a name="p181418256500"></a>Position of a POI.</p>
</td>
</tr>
<tr id="row05001713362"><td class="cellrowborder" valign="top" width="43%" headers="mcps1.1.3.1.1 "><p id="p18813925125011"><a name="p18813925125011"></a><a name="p18813925125011"></a>placeId</p>
</td>
<td class="cellrowborder" valign="top" width="56.99999999999999%" headers="mcps1.1.3.1.2 "><p id="p1179492535016"><a name="p1179492535016"></a><a name="p1179492535016"></a>ID of a POI.</p>
</td>
</tr>
<tr id="row145614418544"><td class="cellrowborder" valign="top" width="43%" headers="mcps1.1.3.1.1 "><p id="p1557541135414"><a name="p1557541135414"></a><a name="p1557541135414"></a>name</p>
</td>
<td class="cellrowborder" valign="top" width="56.99999999999999%" headers="mcps1.1.3.1.2 "><p id="p3571341175417"><a name="p3571341175417"></a><a name="p3571341175417"></a>Name of a POI.</p>
</td>
</tr>
</tbody>
</table>

