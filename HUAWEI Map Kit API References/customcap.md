# CustomCap<a name="EN-US_TOPIC_0000001145541115"></a>

-   [Public Field Summary](#section103050454)
-   [Public Constructor Summary](#section1291413119511)
-   [Public Method Summary](#section323882511516)
-   [Public Constructors](#section19848311202)
-   [CustomCap\(@NonNull BitmapDescriptor bitmap, float bitmapRefWidth\)](#section114762417137)
-   [CustomCap\(@NonNull BitmapDescriptor bitmap\)](#section10621772371)


<a name="table11497mcpsimp"></a>
<table><thead align="left"><tr id="row11501mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p11503mcpsimp"><a name="p11503mcpsimp"></a><a name="p11503mcpsimp"></a>Class Info</p>
</th>
</tr>
</thead>
<tbody><tr id="row11504mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p5598958193815"><a name="p5598958193815"></a><a name="p5598958193815"></a>public final class CustomCap extends Cap</p>
<p id="p18566968303"><a name="p18566968303"></a><a name="p18566968303"></a>Extends the <a href="cap.md">Cap</a> class to customize the cap style for a polyline.</p>
</td>
</tr>
</tbody>
</table>

## Public Field Summary<a name="section103050454"></a>

<a name="table51207528357"></a>
<table><thead align="left"><tr id="row6121185283516"><th class="cellrowborder" valign="top" width="32.33%" id="mcps1.1.3.1.1"><p id="p1528164471414"><a name="p1528164471414"></a><a name="p1528164471414"></a>Qualifier and Type</p>
</th>
<th class="cellrowborder" valign="top" width="67.67%" id="mcps1.1.3.1.2"><p id="p1554614158108"><a name="p1554614158108"></a><a name="p1554614158108"></a>Field and Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row2012119527357"><td class="cellrowborder" valign="top" width="32.33%" headers="mcps1.1.3.1.1 "><p id="p7541349220"><a name="p7541349220"></a><a name="p7541349220"></a>public final <a href="bitmapdescriptor.md">BitmapDescriptor</a></p>
</td>
<td class="cellrowborder" valign="top" width="67.67%" headers="mcps1.1.3.1.2 "><p id="p592329921"><a name="p592329921"></a><a name="p592329921"></a>bitmapDescriptor</p>
<p id="p1475114581810"><a name="p1475114581810"></a><a name="p1475114581810"></a>Definition of a Bitmap to be overlaid at the start or end vertex of a polyline.</p>
</td>
</tr>
<tr id="row8121145210353"><td class="cellrowborder" valign="top" width="32.33%" headers="mcps1.1.3.1.1 "><p id="p12557419214"><a name="p12557419214"></a><a name="p12557419214"></a>public final float</p>
</td>
<td class="cellrowborder" valign="top" width="67.67%" headers="mcps1.1.3.1.2 "><p id="p17422151212214"><a name="p17422151212214"></a><a name="p17422151212214"></a>refWidth</p>
<p id="p1475115581016"><a name="p1475115581016"></a><a name="p1475115581016"></a>Reference stroke width, in pixels.</p>
</td>
</tr>
</tbody>
</table>

## Public Constructor Summary<a name="section1291413119511"></a>

<a name="table11536mcpsimp"></a>
<table><thead align="left"><tr id="row11540mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p145mcpsimp"><a name="p145mcpsimp"></a><a name="p145mcpsimp"></a>Constructor Name</p>
</th>
</tr>
</thead>
<tbody><tr id="row11543mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p11545mcpsimp"><a name="p11545mcpsimp"></a><a name="p11545mcpsimp"></a><a href="#section114762417137">CustomCap</a>(@NonNull <a href="bitmapdescriptor.md">BitmapDescriptor</a> bitmap, float bitmapRefWidth)</p>
<p id="p58111739879"><a name="p58111739879"></a><a name="p58111739879"></a>Creates a <a href="customcap.md">CustomCap</a> object based on specified parameters.</p>
</td>
</tr>
<tr id="row11546mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p11548mcpsimp"><a name="p11548mcpsimp"></a><a name="p11548mcpsimp"></a><a href="#section10621772371">CustomCap</a>(@NonNull <a href="bitmapdescriptor.md">BitmapDescriptor</a> bitmap)</p>
<p id="p260119482719"><a name="p260119482719"></a><a name="p260119482719"></a>Creates a <a href="customcap.md">CustomCap</a> object based on specified parameters.</p>
</td>
</tr>
</tbody>
</table>

## Public Method Summary<a name="section323882511516"></a>

<a name="table11550mcpsimp"></a>
<table><thead align="left"><tr id="row11555mcpsimp"><th class="cellrowborder" valign="top" width="40%" id="mcps1.1.3.1.1"><p id="p081120285386"><a name="p081120285386"></a><a name="p081120285386"></a>Qualifier and Type</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.1.3.1.2"><p id="p681112883813"><a name="p681112883813"></a><a name="p681112883813"></a>Method Name and Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row11560mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p11562mcpsimp"><a name="p11562mcpsimp"></a><a name="p11562mcpsimp"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p11564mcpsimp"><a name="p11564mcpsimp"></a><a name="p11564mcpsimp"></a>toString()</p>
<p id="p15595355549"><a name="p15595355549"></a><a name="p15595355549"></a>Returns the object as a string.</p>
</td>
</tr>
</tbody>
</table>

## Public Constructors<a name="section19848311202"></a>

## CustomCap\(@NonNull BitmapDescriptor bitmap, float bitmapRefWidth\)<a name="section114762417137"></a>

<a name="table227mcpsimp"></a>
<table><thead align="left"><tr id="row231mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p233mcpsimp"><a name="p233mcpsimp"></a><a name="p233mcpsimp"></a>Constructor</p>
</th>
</tr>
</thead>
<tbody><tr id="row235mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p1136373442317"><a name="p1136373442317"></a><a name="p1136373442317"></a>public <a href="customcap.md">CustomCap</a>(@NonNull <a href="bitmapdescriptor.md">BitmapDescriptor</a> bitmap, float bitmapRefWidth)</p>
<p id="p536313432314"><a name="p536313432314"></a><a name="p536313432314"></a>Creates a <a href="customcap.md">CustomCap</a> object based on specified parameters.</p>
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
<tbody><tr id="row255mcpsimp"><td class="cellrowborder" valign="top" width="43%" headers="mcps1.1.3.1.1 "><p id="p1275719175136"><a name="p1275719175136"></a><a name="p1275719175136"></a>bitmap</p>
</td>
<td class="cellrowborder" valign="top" width="56.99999999999999%" headers="mcps1.1.3.1.2 "><p id="p69541622141317"><a name="p69541622141317"></a><a name="p69541622141317"></a>Definition of a Bitmap to be overlaid at the start or end vertex of a polyline.</p>
</td>
</tr>
<tr id="row11970191342516"><td class="cellrowborder" valign="top" width="43%" headers="mcps1.1.3.1.1 "><p id="p397111312516"><a name="p397111312516"></a><a name="p397111312516"></a>bitmapRefWidth</p>
</td>
<td class="cellrowborder" valign="top" width="56.99999999999999%" headers="mcps1.1.3.1.2 "><p id="p097110132256"><a name="p097110132256"></a><a name="p097110132256"></a>Reference stroke width, in pixels.</p>
</td>
</tr>
</tbody>
</table>

## CustomCap\(@NonNull BitmapDescriptor bitmap\)<a name="section10621772371"></a>

<a name="table462177203713"></a>
<table><thead align="left"><tr id="row1962197133720"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p186214743712"><a name="p186214743712"></a><a name="p186214743712"></a>Constructor</p>
</th>
</tr>
</thead>
<tbody><tr id="row16210783720"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p1463177153719"><a name="p1463177153719"></a><a name="p1463177153719"></a>public <a href="customcap.md">CustomCap</a>(@NonNull <a href="bitmapdescriptor.md">BitmapDescriptor</a> bitmap)</p>
<p id="p0631076370"><a name="p0631076370"></a><a name="p0631076370"></a>Creates a <a href="customcap.md">CustomCap</a> object based on specified parameters.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table46327113710"></a>
<table><thead align="left"><tr id="row7638743717"><th class="cellrowborder" valign="top" width="43%" id="mcps1.1.3.1.1"><p id="p1863117173710"><a name="p1863117173710"></a><a name="p1863117173710"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="56.99999999999999%" id="mcps1.1.3.1.2"><p id="p176317743714"><a name="p176317743714"></a><a name="p176317743714"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row176377153713"><td class="cellrowborder" valign="top" width="43%" headers="mcps1.1.3.1.1 "><p id="p1563147133714"><a name="p1563147133714"></a><a name="p1563147133714"></a>bitmap</p>
</td>
<td class="cellrowborder" valign="top" width="56.99999999999999%" headers="mcps1.1.3.1.2 "><p id="p56397173710"><a name="p56397173710"></a><a name="p56397173710"></a>Definition of a Bitmap to be overlaid at the start or end vertex of a polyline.</p>
</td>
</tr>
</tbody>
</table>

