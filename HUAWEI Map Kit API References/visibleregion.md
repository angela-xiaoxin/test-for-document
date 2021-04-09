# VisibleRegion<a name="EN-US_TOPIC_0000001099501058"></a>

-   [Public Field Summary](#section796155782411)
-   [Public Constructor Summary](#section1564131472510)
-   [Public Method Summary](#section14065270489)
-   [Public Constructors](#section042681119126)
-   [VisibleRegion](#section147561345184912)
-   [Public Methods](#section5134184312616)
-   [equals](#section148091116191319)


<a name="table24037mcpsimp"></a>
<table><thead align="left"><tr id="row24041mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p24043mcpsimp"><a name="p24043mcpsimp"></a><a name="p24043mcpsimp"></a>Class Info</p>
</th>
</tr>
</thead>
<tbody><tr id="row24044mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p1256413024511"><a name="p1256413024511"></a><a name="p1256413024511"></a>public class VisibleRegion</p>
<p id="p24046mcpsimp"><a name="p24046mcpsimp"></a><a name="p24046mcpsimp"></a>Implements the <strong id="b360305410531"><a name="b360305410531"></a><a name="b360305410531"></a>Parcelable</strong> API. It contains four points that define a tetragon visible in the camera of a map. The tetragon may be a trapezoid instead of rectangle because the camera may tilt. If the camera is directly over the center of the visible region, the shape is rectangular. If the camera tilts, the shape will be a trapezoid whose smallest side is closest to the point of view.</p>
</td>
</tr>
</tbody>
</table>

## Public Field Summary<a name="section796155782411"></a>

<a name="table51207528357"></a>
<table><thead align="left"><tr id="row6121185283516"><th class="cellrowborder" valign="top" width="32.21%" id="mcps1.1.3.1.1"><p id="p1528164471414"><a name="p1528164471414"></a><a name="p1528164471414"></a>Qualifier and Type</p>
</th>
<th class="cellrowborder" valign="top" width="67.78999999999999%" id="mcps1.1.3.1.2"><p id="p1554614158108"><a name="p1554614158108"></a><a name="p1554614158108"></a>Field and Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row2012119527357"><td class="cellrowborder" valign="top" width="32.21%" headers="mcps1.1.3.1.1 "><p id="p1375101715918"><a name="p1375101715918"></a><a name="p1375101715918"></a>public final <a href="latlng.md">LatLng</a></p>
</td>
<td class="cellrowborder" valign="top" width="67.78999999999999%" headers="mcps1.1.3.1.2 "><p id="p473614244916"><a name="p473614244916"></a><a name="p473614244916"></a>farLeft</p>
<p id="p58851812799"><a name="p58851812799"></a><a name="p58851812799"></a>Upper left corner of the camera.</p>
</td>
</tr>
<tr id="row8446859589"><td class="cellrowborder" valign="top" width="32.21%" headers="mcps1.1.3.1.1 "><p id="p137513171597"><a name="p137513171597"></a><a name="p137513171597"></a>public final <a href="latlng.md">LatLng</a></p>
</td>
<td class="cellrowborder" valign="top" width="67.78999999999999%" headers="mcps1.1.3.1.2 "><p id="p085919271994"><a name="p085919271994"></a><a name="p085919271994"></a>farRight</p>
<p id="p38851112595"><a name="p38851112595"></a><a name="p38851112595"></a>Upper right corner of the camera.</p>
</td>
</tr>
<tr id="row1386317591082"><td class="cellrowborder" valign="top" width="32.21%" headers="mcps1.1.3.1.1 "><p id="p1837519172910"><a name="p1837519172910"></a><a name="p1837519172910"></a>public final <a href="latlngbounds.md">LatLngBounds</a></p>
</td>
<td class="cellrowborder" valign="top" width="67.78999999999999%" headers="mcps1.1.3.1.2 "><p id="p730019321594"><a name="p730019321594"></a><a name="p730019321594"></a>latLngBounds</p>
<p id="p1588519121099"><a name="p1588519121099"></a><a name="p1588519121099"></a>Smallest bounding box that includes the visible region.</p>
</td>
</tr>
<tr id="row5283140394"><td class="cellrowborder" valign="top" width="32.21%" headers="mcps1.1.3.1.1 "><p id="p537511171591"><a name="p537511171591"></a><a name="p537511171591"></a>public final <a href="latlng.md">LatLng</a></p>
</td>
<td class="cellrowborder" valign="top" width="67.78999999999999%" headers="mcps1.1.3.1.2 "><p id="p7676133515918"><a name="p7676133515918"></a><a name="p7676133515918"></a>nearLeft</p>
<p id="p14885191218919"><a name="p14885191218919"></a><a name="p14885191218919"></a>Lower left corner of the camera.</p>
</td>
</tr>
<tr id="row87229014917"><td class="cellrowborder" valign="top" width="32.21%" headers="mcps1.1.3.1.1 "><p id="p93754177911"><a name="p93754177911"></a><a name="p93754177911"></a>public final <a href="latlng.md">LatLng</a></p>
</td>
<td class="cellrowborder" valign="top" width="67.78999999999999%" headers="mcps1.1.3.1.2 "><p id="p1972953810915"><a name="p1972953810915"></a><a name="p1972953810915"></a>nearRight</p>
<p id="p488561212916"><a name="p488561212916"></a><a name="p488561212916"></a>Lower right corner of the camera.</p>
</td>
</tr>
</tbody>
</table>

## Public Constructor Summary<a name="section1564131472510"></a>

<a name="table24097mcpsimp"></a>
<table><thead align="left"><tr id="row24101mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p145mcpsimp"><a name="p145mcpsimp"></a><a name="p145mcpsimp"></a>Constructor Name</p>
</th>
</tr>
</thead>
<tbody><tr id="row24104mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p24106mcpsimp"><a name="p24106mcpsimp"></a><a name="p24106mcpsimp"></a><a href="#section147561345184912">VisibleRegion</a>(<a href="latlng.md">LatLng</a> nearLeft, <a href="latlng.md">LatLng</a> nearRight, <a href="latlng.md">LatLng</a> farLeft, <a href="latlng.md">LatLng</a> farRight, <a href="latlngbounds.md">LatLngBounds</a> latLngBounds)</p>
<p id="p84081638151418"><a name="p84081638151418"></a><a name="p84081638151418"></a>Creates a <a href="visibleregion.md">VisibleRegion</a> object based on specified parameters.</p>
</td>
</tr>
</tbody>
</table>

## Public Method Summary<a name="section14065270489"></a>

<a name="table9676mcpsimp"></a>
<table><thead align="left"><tr id="row9681mcpsimp"><th class="cellrowborder" valign="top" width="40%" id="mcps1.1.3.1.1"><p id="p770950204210"><a name="p770950204210"></a><a name="p770950204210"></a>Qualifier and Type</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.1.3.1.2"><p id="p270650134216"><a name="p270650134216"></a><a name="p270650134216"></a>Method Name and Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row16557430214"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p920917448213"><a name="p920917448213"></a><a name="p920917448213"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p1521018441625"><a name="p1521018441625"></a><a name="p1521018441625"></a><a href="#section148091116191319">equals</a>()</p>
<p id="p208171418417"><a name="p208171418417"></a><a name="p208171418417"></a>Checks whether a <a href="visibleregion.md">VisibleRegion</a> object equals another.</p>
</td>
</tr>
<tr id="row9691mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p9693mcpsimp"><a name="p9693mcpsimp"></a><a name="p9693mcpsimp"></a>int</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p9695mcpsimp"><a name="p9695mcpsimp"></a><a name="p9695mcpsimp"></a>hashCode()</p>
<p id="p136495017414"><a name="p136495017414"></a><a name="p136495017414"></a>Returns the hash code of an object.</p>
</td>
</tr>
<tr id="row9701mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p9703mcpsimp"><a name="p9703mcpsimp"></a><a name="p9703mcpsimp"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p9705mcpsimp"><a name="p9705mcpsimp"></a><a name="p9705mcpsimp"></a>toString()</p>
<p id="p108842553"><a name="p108842553"></a><a name="p108842553"></a>Returns the object as a string.</p>
</td>
</tr>
<tr id="row24641859621"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p1444313017316"><a name="p1444313017316"></a><a name="p1444313017316"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p18443407311"><a name="p18443407311"></a><a name="p18443407311"></a>writeToParcel(Parcel out, int flags)</p>
<p id="p327772682115"><a name="p327772682115"></a><a name="p327772682115"></a>Serializes data.</p>
</td>
</tr>
</tbody>
</table>

## Public Constructors<a name="section042681119126"></a>

## VisibleRegion<a name="section147561345184912"></a>

<a name="table227mcpsimp"></a>
<table><thead align="left"><tr id="row231mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p233mcpsimp"><a name="p233mcpsimp"></a><a name="p233mcpsimp"></a>Constructor</p>
</th>
</tr>
</thead>
<tbody><tr id="row235mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p114231510376"><a name="p114231510376"></a><a name="p114231510376"></a>public <a href="visibleregion.md">VisibleRegion</a>(<a href="latlng.md">LatLng</a> nearLeft, <a href="latlng.md">LatLng</a> nearRight, <a href="latlng.md">LatLng</a> farLeft, <a href="latlng.md">LatLng</a> farRight, <a href="latlngbounds.md">LatLngBounds</a> latLngBounds)</p>
<p id="p1142316101175"><a name="p1142316101175"></a><a name="p1142316101175"></a>Creates a <a href="visibleregion.md">VisibleRegion</a> object based on specified parameters.</p>
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
<tbody><tr id="row255mcpsimp"><td class="cellrowborder" valign="top" width="43%" headers="mcps1.1.3.1.1 "><p id="p16831145118919"><a name="p16831145118919"></a><a name="p16831145118919"></a>nearLeft</p>
</td>
<td class="cellrowborder" valign="top" width="56.99999999999999%" headers="mcps1.1.3.1.2 "><p id="p108301951798"><a name="p108301951798"></a><a name="p108301951798"></a>Lower-left corner of the camera.</p>
</td>
</tr>
<tr id="row05001713362"><td class="cellrowborder" valign="top" width="43%" headers="mcps1.1.3.1.1 "><p id="p382915511795"><a name="p382915511795"></a><a name="p382915511795"></a>nearRight</p>
</td>
<td class="cellrowborder" valign="top" width="56.99999999999999%" headers="mcps1.1.3.1.2 "><p id="p16827185110912"><a name="p16827185110912"></a><a name="p16827185110912"></a>Lower-right corner of the camera.</p>
</td>
</tr>
<tr id="row19226195171011"><td class="cellrowborder" valign="top" width="43%" headers="mcps1.1.3.1.1 "><p id="p52261450101"><a name="p52261450101"></a><a name="p52261450101"></a>farLeft</p>
</td>
<td class="cellrowborder" valign="top" width="56.99999999999999%" headers="mcps1.1.3.1.2 "><p id="p162264515103"><a name="p162264515103"></a><a name="p162264515103"></a>Upper-left corner of the camera.</p>
</td>
</tr>
<tr id="row5877412201014"><td class="cellrowborder" valign="top" width="43%" headers="mcps1.1.3.1.1 "><p id="p1387710126102"><a name="p1387710126102"></a><a name="p1387710126102"></a>farRight</p>
</td>
<td class="cellrowborder" valign="top" width="56.99999999999999%" headers="mcps1.1.3.1.2 "><p id="p9877512121019"><a name="p9877512121019"></a><a name="p9877512121019"></a>Upper-right corner of the camera.</p>
</td>
</tr>
<tr id="row20982151571011"><td class="cellrowborder" valign="top" width="43%" headers="mcps1.1.3.1.1 "><p id="p199821015151020"><a name="p199821015151020"></a><a name="p199821015151020"></a>latLngBounds</p>
</td>
<td class="cellrowborder" valign="top" width="56.99999999999999%" headers="mcps1.1.3.1.2 "><p id="p15982515201011"><a name="p15982515201011"></a><a name="p15982515201011"></a>Smallest bounding box that includes the visible region.</p>
</td>
</tr>
</tbody>
</table>

## Public Methods<a name="section5134184312616"></a>

## equals<a name="section148091116191319"></a>

<a name="table202mcpsimp"></a>
<table><thead align="left"><tr id="row206mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p208mcpsimp"><a name="p208mcpsimp"></a><a name="p208mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row209mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p310314754612"><a name="p310314754612"></a><a name="p310314754612"></a>public boolean equals(Object object)</p>
<p id="p12974181661612"><a name="p12974181661612"></a><a name="p12974181661612"></a>Checks whether a <a href="visibleregion.md">VisibleRegion</a> object equals another.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table217mcpsimp"></a>
<table><thead align="left"><tr id="row222mcpsimp"><th class="cellrowborder" valign="top" width="46.19%" id="mcps1.1.3.1.1"><p id="p224mcpsimp"><a name="p224mcpsimp"></a><a name="p224mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53.81%" id="mcps1.1.3.1.2"><p id="p226mcpsimp"><a name="p226mcpsimp"></a><a name="p226mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row227mcpsimp"><td class="cellrowborder" valign="top" width="46.19%" headers="mcps1.1.3.1.1 "><p id="p1424314316119"><a name="p1424314316119"></a><a name="p1424314316119"></a>object</p>
</td>
<td class="cellrowborder" valign="top" width="53.81%" headers="mcps1.1.3.1.2 "><p id="p122431631515"><a name="p122431631515"></a><a name="p122431631515"></a>Another object to be compared.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table234mcpsimp"></a>
<table><thead align="left"><tr id="row239mcpsimp"><th class="cellrowborder" valign="top" width="46.37%" id="mcps1.1.3.1.1"><p id="p241mcpsimp"><a name="p241mcpsimp"></a><a name="p241mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53.63%" id="mcps1.1.3.1.2"><p id="p243mcpsimp"><a name="p243mcpsimp"></a><a name="p243mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row244mcpsimp"><td class="cellrowborder" valign="top" width="46.37%" headers="mcps1.1.3.1.1 "><p id="p910812116"><a name="p910812116"></a><a name="p910812116"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="53.63%" headers="mcps1.1.3.1.2 "><p id="p171021212115"><a name="p171021212115"></a><a name="p171021212115"></a><strong id="b134118428487"><a name="b134118428487"></a><a name="b134118428487"></a>true</strong> if the two objects are equal; <strong id="b1534711423481"><a name="b1534711423481"></a><a name="b1534711423481"></a>false</strong> otherwise.</p>
</td>
</tr>
</tbody>
</table>

