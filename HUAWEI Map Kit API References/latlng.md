# LatLng<a name="EN-US_TOPIC_0000001099661098"></a>

-   [Public Field Summary](#section1221015941019)
-   [Public Constructor Summary](#section34021619171011)
-   [Public Method Summary](#section1468943311106)
-   [Public Constructors](#section19848311202)
-   [LatLng](#section114762417137)


<a name="table13898mcpsimp"></a>
<table><thead align="left"><tr id="row13902mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p13904mcpsimp"><a name="p13904mcpsimp"></a><a name="p13904mcpsimp"></a>Class Info</p>
</th>
</tr>
</thead>
<tbody><tr id="row13905mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p5533125164010"><a name="p5533125164010"></a><a name="p5533125164010"></a>public class LatLng</p>
<p id="p13907mcpsimp"><a name="p13907mcpsimp"></a><a name="p13907mcpsimp"></a>Defines the longitude and latitude, in degrees.</p>
</td>
</tr>
</tbody>
</table>

## Public Field Summary<a name="section1221015941019"></a>

<a name="table51207528357"></a>
<table><thead align="left"><tr id="row6121185283516"><th class="cellrowborder" valign="top" width="32.190000000000005%" id="mcps1.1.3.1.1"><p id="p1528164471414"><a name="p1528164471414"></a><a name="p1528164471414"></a>Qualifier and Type</p>
</th>
<th class="cellrowborder" valign="top" width="67.81%" id="mcps1.1.3.1.2"><p id="p1554614158108"><a name="p1554614158108"></a><a name="p1554614158108"></a>Field and Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row2012119527357"><td class="cellrowborder" valign="top" width="32.190000000000005%" headers="mcps1.1.3.1.1 "><p id="p232118512510"><a name="p232118512510"></a><a name="p232118512510"></a>double</p>
</td>
<td class="cellrowborder" valign="top" width="67.81%" headers="mcps1.1.3.1.2 "><p id="p16837271350"><a name="p16837271350"></a><a name="p16837271350"></a>longitude</p>
<p id="p2064675818416"><a name="p2064675818416"></a><a name="p2064675818416"></a>Longitude. The value ranges from –180 to 180 (excluded).</p>
</td>
</tr>
<tr id="row8965818847"><td class="cellrowborder" valign="top" width="32.190000000000005%" headers="mcps1.1.3.1.1 "><p id="p19321251454"><a name="p19321251454"></a><a name="p19321251454"></a>double</p>
</td>
<td class="cellrowborder" valign="top" width="67.81%" headers="mcps1.1.3.1.2 "><p id="p06046101456"><a name="p06046101456"></a><a name="p06046101456"></a>latitude</p>
<p id="p1064611581148"><a name="p1064611581148"></a><a name="p1064611581148"></a>Latitude. The value ranges from –90 to 90.</p>
</td>
</tr>
</tbody>
</table>

## Public Constructor Summary<a name="section34021619171011"></a>

<a name="table13937mcpsimp"></a>
<table><thead align="left"><tr id="row13941mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p145mcpsimp"><a name="p145mcpsimp"></a><a name="p145mcpsimp"></a>Constructor Name</p>
</th>
</tr>
</thead>
<tbody><tr id="row13944mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p13946mcpsimp"><a name="p13946mcpsimp"></a><a name="p13946mcpsimp"></a><a href="#section114762417137">LatLng</a>(double latitude, double longitude)</p>
<p id="p1691810467910"><a name="p1691810467910"></a><a name="p1691810467910"></a>Creates a <a href="latlng.md">LatLng</a> object using the latitude and longitude. If the passed latitude and longitude are not in their value ranges, error logs will be recorded, and the passed latitude and longitude will be converted to valid values in the value ranges.</p>
</td>
</tr>
</tbody>
</table>

## Public Method Summary<a name="section1468943311106"></a>

<a name="table13948mcpsimp"></a>
<table><thead align="left"><tr id="row13953mcpsimp"><th class="cellrowborder" valign="top" width="40%" id="mcps1.1.3.1.1"><p id="p081120285386"><a name="p081120285386"></a><a name="p081120285386"></a>Qualifier and Type</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.1.3.1.2"><p id="p681112883813"><a name="p681112883813"></a><a name="p681112883813"></a>Method Name and Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row13958mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p13960mcpsimp"><a name="p13960mcpsimp"></a><a name="p13960mcpsimp"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p13962mcpsimp"><a name="p13962mcpsimp"></a><a name="p13962mcpsimp"></a>equals(Object other)</p>
<p id="p12114133813318"><a name="p12114133813318"></a><a name="p12114133813318"></a>Checks whether a <a href="latlng.md">LatLng</a> object equals another.</p>
</td>
</tr>
<tr id="row13963mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p13965mcpsimp"><a name="p13965mcpsimp"></a><a name="p13965mcpsimp"></a>int</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p13967mcpsimp"><a name="p13967mcpsimp"></a><a name="p13967mcpsimp"></a>hashCode()</p>
<p id="p11966133816311"><a name="p11966133816311"></a><a name="p11966133816311"></a>Returns the hash code of an object.</p>
</td>
</tr>
<tr id="row13968mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p13970mcpsimp"><a name="p13970mcpsimp"></a><a name="p13970mcpsimp"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p13972mcpsimp"><a name="p13972mcpsimp"></a><a name="p13972mcpsimp"></a>toString()</p>
<p id="p36933392315"><a name="p36933392315"></a><a name="p36933392315"></a>Returns the object as a string.</p>
</td>
</tr>
</tbody>
</table>

## Public Constructors<a name="section19848311202"></a>

## LatLng<a name="section114762417137"></a>

<a name="table227mcpsimp"></a>
<table><thead align="left"><tr id="row231mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p233mcpsimp"><a name="p233mcpsimp"></a><a name="p233mcpsimp"></a>Constructor</p>
</th>
</tr>
</thead>
<tbody><tr id="row235mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p2033459103610"><a name="p2033459103610"></a><a name="p2033459103610"></a>public <a href="latlng.md">LatLng</a>(double latitude, double longitude)</p>
<p id="p533499183620"><a name="p533499183620"></a><a name="p533499183620"></a>Creates a <a href="latlng.md">LatLng</a> object using the latitude and longitude. </p>
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
<tbody><tr id="row255mcpsimp"><td class="cellrowborder" valign="top" width="43%" headers="mcps1.1.3.1.1 "><p id="p2404192013619"><a name="p2404192013619"></a><a name="p2404192013619"></a>latitude</p>
</td>
<td class="cellrowborder" valign="top" width="56.99999999999999%" headers="mcps1.1.3.1.2 "><p id="p16403192012362"><a name="p16403192012362"></a><a name="p16403192012362"></a>Latitude. The value ranges from –90 to 90.</p>
</td>
</tr>
<tr id="row05001713362"><td class="cellrowborder" valign="top" width="43%" headers="mcps1.1.3.1.1 "><p id="p451517103611"><a name="p451517103611"></a><a name="p451517103611"></a>longitude</p>
</td>
<td class="cellrowborder" valign="top" width="56.99999999999999%" headers="mcps1.1.3.1.2 "><p id="p351171743616"><a name="p351171743616"></a><a name="p351171743616"></a>Longitude. The value ranges from –180 to 180 (excluded).</p>
</td>
</tr>
</tbody>
</table>

