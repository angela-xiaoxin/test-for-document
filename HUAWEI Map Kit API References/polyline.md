# Polyline<a name="EN-US_TOPIC_0000001099501082"></a>

-   [Public Method Summary](#section3455192841814)
-   [Public Methods](#section749713214179)
-   [equals](#section853911341716)
-   [getColor](#section311205513172)
-   [getEndCap](#section1474953331814)
-   [getId](#section339905181913)
-   [getJointType](#section6767342135410)
-   [getPattern](#section1131102385516)
-   [getPoints](#section166671316563)
-   [getStartCap](#section174211035165617)
-   [getTag](#section1297371116575)
-   [getWidth](#section142291349125716)
-   [getZIndex](#section5767142015588)
-   [hashCode](#section142719578585)
-   [isClickable](#section1121182819597)
-   [isGeodesic](#section1785131609)
-   [isVisible](#section243117361704)
-   [remove](#section193591012413)
-   [setClickable](#section114084419112)
-   [setColor](#section1215112270216)
-   [setEndCap](#section8261559324)
-   [setGeodesic](#section582118411634)
-   [setJointType](#section7764119142)
-   [setPattern](#section16311361458)
-   [setPoints](#section1721284615510)
-   [setStartCap](#section1902102711613)
-   [setTag](#section26811611775)
-   [setVisible](#section2681104718714)
-   [setWidth](#section146861631180)
-   [setZIndex](#section16726451291)


<a name="table19602mcpsimp"></a>
<table><thead align="left"><tr id="row19606mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p19608mcpsimp"><a name="p19608mcpsimp"></a><a name="p19608mcpsimp"></a>Class Info</p>
</th>
</tr>
</thead>
<tbody><tr id="row19609mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p74371454134214"><a name="p74371454134214"></a><a name="p74371454134214"></a>public final class Polyline</p>
<p id="p19611mcpsimp"><a name="p19611mcpsimp"></a><a name="p19611mcpsimp"></a>Defines a polyline, which is a list of vertices, where line segments are drawn between consecutive vertices. An instance of this type will be returned when the <a href="huaweimap.md#section527091714515">addPolyline</a> method in the <a href="huaweimap.md">HuaweiMap</a> class is called.</p>
</td>
</tr>
</tbody>
</table>

## Public Method Summary<a name="section3455192841814"></a>

<a name="table19617mcpsimp"></a>
<table><thead align="left"><tr id="row19622mcpsimp"><th class="cellrowborder" valign="top" width="40%" id="mcps1.1.3.1.1"><p id="p081120285386"><a name="p081120285386"></a><a name="p081120285386"></a>Qualifier and Type</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.1.3.1.2"><p id="p681112883813"><a name="p681112883813"></a><a name="p681112883813"></a>Method Name and Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row19627mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p19629mcpsimp"><a name="p19629mcpsimp"></a><a name="p19629mcpsimp"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p19631mcpsimp"><a name="p19631mcpsimp"></a><a name="p19631mcpsimp"></a><a href="#section853911341716">equals</a>(Object other)</p>
<p id="p1116917330615"><a name="p1116917330615"></a><a name="p1116917330615"></a>Checks whether a polyline object equals another.</p>
</td>
</tr>
<tr id="row19632mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p19634mcpsimp"><a name="p19634mcpsimp"></a><a name="p19634mcpsimp"></a>int</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p19636mcpsimp"><a name="p19636mcpsimp"></a><a name="p19636mcpsimp"></a><a href="#section311205513172">getColor</a>()</p>
<p id="p132721334966"><a name="p132721334966"></a><a name="p132721334966"></a>Obtains the stroke color of a polyline.</p>
</td>
</tr>
<tr id="row19637mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p19639mcpsimp"><a name="p19639mcpsimp"></a><a name="p19639mcpsimp"></a><a href="cap.md">Cap</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p19641mcpsimp"><a name="p19641mcpsimp"></a><a name="p19641mcpsimp"></a><a href="#section1474953331814">getEndCap</a>()</p>
<p id="p192235566"><a name="p192235566"></a><a name="p192235566"></a>Obtains the end vertex cap of a polyline.</p>
</td>
</tr>
<tr id="row19642mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p19644mcpsimp"><a name="p19644mcpsimp"></a><a name="p19644mcpsimp"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p19646mcpsimp"><a name="p19646mcpsimp"></a><a name="p19646mcpsimp"></a><a href="#section339905181913">getId</a>()</p>
<p id="p61973617615"><a name="p61973617615"></a><a name="p61973617615"></a>Obtains the ID of a polyline on a map. </p>
</td>
</tr>
<tr id="row19647mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p19649mcpsimp"><a name="p19649mcpsimp"></a><a name="p19649mcpsimp"></a>int</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p19651mcpsimp"><a name="p19651mcpsimp"></a><a name="p19651mcpsimp"></a><a href="#section6767342135410">getJointType</a>()</p>
<p id="p167913374612"><a name="p167913374612"></a><a name="p167913374612"></a>Obtains the joint type of all vertices of a polyline, except the start and end vertices.</p>
</td>
</tr>
<tr id="row19652mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p19654mcpsimp"><a name="p19654mcpsimp"></a><a name="p19654mcpsimp"></a>List&lt;<a href="patternitem.md">PatternItem</a>&gt;</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p19656mcpsimp"><a name="p19656mcpsimp"></a><a name="p19656mcpsimp"></a><a href="#section1131102385516">getPattern</a>()</p>
<p id="p787816377612"><a name="p787816377612"></a><a name="p787816377612"></a>Obtains the stroke pattern of a polyline.</p>
</td>
</tr>
<tr id="row19657mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p19659mcpsimp"><a name="p19659mcpsimp"></a><a name="p19659mcpsimp"></a>List&lt;<a href="latlng.md">LatLng</a>&gt;</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p19661mcpsimp"><a name="p19661mcpsimp"></a><a name="p19661mcpsimp"></a><a href="#section166671316563">getPoints</a>()</p>
<p id="p17862382616"><a name="p17862382616"></a><a name="p17862382616"></a>Obtains the vertex set of a polyline.</p>
</td>
</tr>
<tr id="row19662mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p19664mcpsimp"><a name="p19664mcpsimp"></a><a name="p19664mcpsimp"></a><a href="cap.md">Cap</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p19666mcpsimp"><a name="p19666mcpsimp"></a><a name="p19666mcpsimp"></a><a href="#section174211035165617">getStartCap</a>()</p>
<p id="p77801839965"><a name="p77801839965"></a><a name="p77801839965"></a>Obtains the start vertex cap of a polyline.</p>
</td>
</tr>
<tr id="row19667mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p19669mcpsimp"><a name="p19669mcpsimp"></a><a name="p19669mcpsimp"></a>Object</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p19671mcpsimp"><a name="p19671mcpsimp"></a><a name="p19671mcpsimp"></a><a href="#section1297371116575">getTag</a>()</p>
<p id="p209111540967"><a name="p209111540967"></a><a name="p209111540967"></a>Obtains the <strong id="b1942416344215"><a name="b1942416344215"></a><a name="b1942416344215"></a>tag</strong> attribute of a polyline.</p>
</td>
</tr>
<tr id="row19672mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p19674mcpsimp"><a name="p19674mcpsimp"></a><a name="p19674mcpsimp"></a>float</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p19676mcpsimp"><a name="p19676mcpsimp"></a><a name="p19676mcpsimp"></a><a href="#section142291349125716">getWidth</a>()</p>
<p id="p208071421618"><a name="p208071421618"></a><a name="p208071421618"></a>Obtains the stroke width of a polyline.</p>
</td>
</tr>
<tr id="row19677mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p19679mcpsimp"><a name="p19679mcpsimp"></a><a name="p19679mcpsimp"></a>float</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p19681mcpsimp"><a name="p19681mcpsimp"></a><a name="p19681mcpsimp"></a><a href="#section5767142015588">getZIndex</a>()</p>
<p id="p11718174317614"><a name="p11718174317614"></a><a name="p11718174317614"></a>Obtains the z-index of a polyline.</p>
</td>
</tr>
<tr id="row19682mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p19684mcpsimp"><a name="p19684mcpsimp"></a><a name="p19684mcpsimp"></a>int</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p19686mcpsimp"><a name="p19686mcpsimp"></a><a name="p19686mcpsimp"></a><a href="#section142719578585">hashCode</a>()</p>
<p id="p155612441667"><a name="p155612441667"></a><a name="p155612441667"></a>Obtains the hash code of a polyline.</p>
</td>
</tr>
<tr id="row19687mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p19689mcpsimp"><a name="p19689mcpsimp"></a><a name="p19689mcpsimp"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p19691mcpsimp"><a name="p19691mcpsimp"></a><a name="p19691mcpsimp"></a><a href="#section1121182819597">isClickable</a>()</p>
<p id="p128136452064"><a name="p128136452064"></a><a name="p128136452064"></a>Checks whether a polyline is tappable.</p>
</td>
</tr>
<tr id="row19692mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p19694mcpsimp"><a name="p19694mcpsimp"></a><a name="p19694mcpsimp"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p19696mcpsimp"><a name="p19696mcpsimp"></a><a name="p19696mcpsimp"></a><a href="#section1785131609">isGeodesic</a>()</p>
<p id="p183574619611"><a name="p183574619611"></a><a name="p183574619611"></a>Checks whether each segment of a polyline is drawn as a geodesic.</p>
</td>
</tr>
<tr id="row19697mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p19699mcpsimp"><a name="p19699mcpsimp"></a><a name="p19699mcpsimp"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p19701mcpsimp"><a name="p19701mcpsimp"></a><a name="p19701mcpsimp"></a><a href="#section243117361704">isVisible</a>()</p>
<p id="p1577734718612"><a name="p1577734718612"></a><a name="p1577734718612"></a>Checks whether a polyline is visible.</p>
</td>
</tr>
<tr id="row19702mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p19704mcpsimp"><a name="p19704mcpsimp"></a><a name="p19704mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p19706mcpsimp"><a name="p19706mcpsimp"></a><a name="p19706mcpsimp"></a><a href="#section193591012413">remove</a>()</p>
<p id="p676819481614"><a name="p676819481614"></a><a name="p676819481614"></a>Removes a polyline from a map. </p>
</td>
</tr>
<tr id="row19707mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p19709mcpsimp"><a name="p19709mcpsimp"></a><a name="p19709mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p19711mcpsimp"><a name="p19711mcpsimp"></a><a name="p19711mcpsimp"></a><a href="#section114084419112">setClickable</a>(boolean clickable)</p>
<p id="p14221550562"><a name="p14221550562"></a><a name="p14221550562"></a>Sets whether a polyline is tappable.</p>
</td>
</tr>
<tr id="row19712mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p19714mcpsimp"><a name="p19714mcpsimp"></a><a name="p19714mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p19716mcpsimp"><a name="p19716mcpsimp"></a><a name="p19716mcpsimp"></a><a href="#section1215112270216">setColor</a>(int color)</p>
<p id="p1138510511368"><a name="p1138510511368"></a><a name="p1138510511368"></a>Sets the stroke color of a polyline.</p>
</td>
</tr>
<tr id="row19717mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p19719mcpsimp"><a name="p19719mcpsimp"></a><a name="p19719mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p19721mcpsimp"><a name="p19721mcpsimp"></a><a name="p19721mcpsimp"></a><a href="#section8261559324">setEndCap</a>(<a href="cap.md">Cap</a> endCap)</p>
<p id="p845645218611"><a name="p845645218611"></a><a name="p845645218611"></a>Sets the end vertex cap of a polyline.</p>
</td>
</tr>
<tr id="row19722mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p19724mcpsimp"><a name="p19724mcpsimp"></a><a name="p19724mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p19726mcpsimp"><a name="p19726mcpsimp"></a><a name="p19726mcpsimp"></a><a href="#section582118411634">setGeodesic</a>(boolean geodesic)</p>
<p id="p42943539614"><a name="p42943539614"></a><a name="p42943539614"></a>Sets whether to draw each segment of a polyline as a geodesic.</p>
</td>
</tr>
<tr id="row19727mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p19729mcpsimp"><a name="p19729mcpsimp"></a><a name="p19729mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p19731mcpsimp"><a name="p19731mcpsimp"></a><a name="p19731mcpsimp"></a><a href="#section7764119142">setJointType</a>(int jointType)</p>
<p id="p1666616541067"><a name="p1666616541067"></a><a name="p1666616541067"></a>Sets the joint type of all vertices of a polyline, except the start and end vertices. For details about the allowed joint types, please refer to <a href="jointtype.md">JointType</a>.</p>
</td>
</tr>
<tr id="row19732mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p19734mcpsimp"><a name="p19734mcpsimp"></a><a name="p19734mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p19736mcpsimp"><a name="p19736mcpsimp"></a><a name="p19736mcpsimp"></a><a href="#section16311361458">setPattern</a>(List&lt;<a href="patternitem.md">PatternItem</a>&gt; pattern)</p>
<p id="p185260554615"><a name="p185260554615"></a><a name="p185260554615"></a>Sets the stroke pattern of a polyline.</p>
</td>
</tr>
<tr id="row19737mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p19739mcpsimp"><a name="p19739mcpsimp"></a><a name="p19739mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p19741mcpsimp"><a name="p19741mcpsimp"></a><a name="p19741mcpsimp"></a><a href="#section1721284615510">setPoints</a>(List&lt;<a href="latlng.md">LatLng</a>&gt; points)</p>
<p id="p6406165617613"><a name="p6406165617613"></a><a name="p6406165617613"></a>Sets the vertex coordinates of a polyline.</p>
</td>
</tr>
<tr id="row19742mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p19744mcpsimp"><a name="p19744mcpsimp"></a><a name="p19744mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p19746mcpsimp"><a name="p19746mcpsimp"></a><a name="p19746mcpsimp"></a><a href="#section1902102711613">setStartCap</a>(<a href="cap.md">Cap</a> startCap)</p>
<p id="p8462457467"><a name="p8462457467"></a><a name="p8462457467"></a>Sets the start vertex cap of a polyline.</p>
</td>
</tr>
<tr id="row19747mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p19749mcpsimp"><a name="p19749mcpsimp"></a><a name="p19749mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p19751mcpsimp"><a name="p19751mcpsimp"></a><a name="p19751mcpsimp"></a><a href="#section26811611775">setTag</a>(Object tag)</p>
<p id="p04551658662"><a name="p04551658662"></a><a name="p04551658662"></a>Sets the <strong id="b188321050112610"><a name="b188321050112610"></a><a name="b188321050112610"></a>tag</strong> attribute of a polyline.</p>
</td>
</tr>
<tr id="row19752mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p19754mcpsimp"><a name="p19754mcpsimp"></a><a name="p19754mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p19756mcpsimp"><a name="p19756mcpsimp"></a><a name="p19756mcpsimp"></a><a href="#section2681104718714">setVisible</a>(boolean visible)</p>
<p id="p522817597613"><a name="p522817597613"></a><a name="p522817597613"></a>Sets whether a polyline is visible.</p>
</td>
</tr>
<tr id="row19757mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p19759mcpsimp"><a name="p19759mcpsimp"></a><a name="p19759mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p19761mcpsimp"><a name="p19761mcpsimp"></a><a name="p19761mcpsimp"></a><a href="#section146861631180">setWidth</a>(float width)</p>
<p id="p18322200570"><a name="p18322200570"></a><a name="p18322200570"></a>Sets the stroke width of a polyline.</p>
</td>
</tr>
<tr id="row19762mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p19764mcpsimp"><a name="p19764mcpsimp"></a><a name="p19764mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p19766mcpsimp"><a name="p19766mcpsimp"></a><a name="p19766mcpsimp"></a><a href="#section16726451291">setZIndex</a>(float zIndex)</p>
<p id="p2379411075"><a name="p2379411075"></a><a name="p2379411075"></a>Sets the z-index of a polyline.</p>
</td>
</tr>
</tbody>
</table>

## Public Methods<a name="section749713214179"></a>

## equals<a name="section853911341716"></a>

<a name="table19769mcpsimp"></a>
<table><thead align="left"><tr id="row19773mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p19775mcpsimp"><a name="p19775mcpsimp"></a><a name="p19775mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row19776mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p19778mcpsimp"><a name="p19778mcpsimp"></a><a name="p19778mcpsimp"></a>public boolean equals(Object other)</p>
<p id="p57325289173"><a name="p57325289173"></a><a name="p57325289173"></a>Checks whether a polyline object equals another.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table19784mcpsimp"></a>
<table><thead align="left"><tr id="row19789mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p19791mcpsimp"><a name="p19791mcpsimp"></a><a name="p19791mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p19793mcpsimp"><a name="p19793mcpsimp"></a><a name="p19793mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row19794mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p19796mcpsimp"><a name="p19796mcpsimp"></a><a name="p19796mcpsimp"></a>other</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p19798mcpsimp"><a name="p19798mcpsimp"></a><a name="p19798mcpsimp"></a>Name of another object.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table19801mcpsimp"></a>
<table><thead align="left"><tr id="row19806mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p19808mcpsimp"><a name="p19808mcpsimp"></a><a name="p19808mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p19810mcpsimp"><a name="p19810mcpsimp"></a><a name="p19810mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row19811mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p19813mcpsimp"><a name="p19813mcpsimp"></a><a name="p19813mcpsimp"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p19815mcpsimp"><a name="p19815mcpsimp"></a><a name="p19815mcpsimp"></a><strong id="b752225612217"><a name="b752225612217"></a><a name="b752225612217"></a>true</strong> if the polyline objects are equal; <strong id="b16523125692215"><a name="b16523125692215"></a><a name="b16523125692215"></a>false</strong> otherwise.</p>
</td>
</tr>
</tbody>
</table>

## getColor<a name="section311205513172"></a>

<a name="table19817mcpsimp"></a>
<table><thead align="left"><tr id="row19821mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p19823mcpsimp"><a name="p19823mcpsimp"></a><a name="p19823mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row19824mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p19826mcpsimp"><a name="p19826mcpsimp"></a><a name="p19826mcpsimp"></a>public int getColor()</p>
<p id="p19829mcpsimp"><a name="p19829mcpsimp"></a><a name="p19829mcpsimp"></a>Obtains the stroke color of a polyline.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table19835mcpsimp"></a>
<table><thead align="left"><tr id="row19840mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p19842mcpsimp"><a name="p19842mcpsimp"></a><a name="p19842mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p19844mcpsimp"><a name="p19844mcpsimp"></a><a name="p19844mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row19845mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p19847mcpsimp"><a name="p19847mcpsimp"></a><a name="p19847mcpsimp"></a>int</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p19849mcpsimp"><a name="p19849mcpsimp"></a><a name="p19849mcpsimp"></a>Color in ARGB format.</p>
</td>
</tr>
</tbody>
</table>

## getEndCap<a name="section1474953331814"></a>

<a name="table19851mcpsimp"></a>
<table><thead align="left"><tr id="row19855mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p19857mcpsimp"><a name="p19857mcpsimp"></a><a name="p19857mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row19858mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p19860mcpsimp"><a name="p19860mcpsimp"></a><a name="p19860mcpsimp"></a>public <a href="cap.md">Cap</a> getEndCap()</p>
<p id="p1816494913186"><a name="p1816494913186"></a><a name="p1816494913186"></a>Obtains the end vertex cap of a polyline.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table19869mcpsimp"></a>
<table><thead align="left"><tr id="row19874mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p19876mcpsimp"><a name="p19876mcpsimp"></a><a name="p19876mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p19878mcpsimp"><a name="p19878mcpsimp"></a><a name="p19878mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row19879mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p19881mcpsimp"><a name="p19881mcpsimp"></a><a name="p19881mcpsimp"></a><a href="cap.md">Cap</a></p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p19883mcpsimp"><a name="p19883mcpsimp"></a><a name="p19883mcpsimp"></a>End vertex cap of a polyline. If no vertex cap is set, the default value <a href="buttcap.md">ButtCap</a> will be returned.</p>
</td>
</tr>
</tbody>
</table>

## getId<a name="section339905181913"></a>

<a name="table19885mcpsimp"></a>
<table><thead align="left"><tr id="row19889mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p19891mcpsimp"><a name="p19891mcpsimp"></a><a name="p19891mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row19892mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p19894mcpsimp"><a name="p19894mcpsimp"></a><a name="p19894mcpsimp"></a>public String getId()</p>
<p id="p19897mcpsimp"><a name="p19897mcpsimp"></a><a name="p19897mcpsimp"></a>Obtains the ID of a polyline on a map. The ID will be unique among all polylines on the map.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table19903mcpsimp"></a>
<table><thead align="left"><tr id="row19908mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p19910mcpsimp"><a name="p19910mcpsimp"></a><a name="p19910mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p19912mcpsimp"><a name="p19912mcpsimp"></a><a name="p19912mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row19913mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p19915mcpsimp"><a name="p19915mcpsimp"></a><a name="p19915mcpsimp"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p19917mcpsimp"><a name="p19917mcpsimp"></a><a name="p19917mcpsimp"></a>ID of a polyline.</p>
</td>
</tr>
</tbody>
</table>

## getJointType<a name="section6767342135410"></a>

<a name="table19919mcpsimp"></a>
<table><thead align="left"><tr id="row19923mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p19925mcpsimp"><a name="p19925mcpsimp"></a><a name="p19925mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row19926mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p19928mcpsimp"><a name="p19928mcpsimp"></a><a name="p19928mcpsimp"></a>public int getJointType()</p>
<p id="p19931mcpsimp"><a name="p19931mcpsimp"></a><a name="p19931mcpsimp"></a>Obtains the joint type of all vertices of a polyline, except the start and end vertices.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table19937mcpsimp"></a>
<table><thead align="left"><tr id="row19942mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p19944mcpsimp"><a name="p19944mcpsimp"></a><a name="p19944mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p19946mcpsimp"><a name="p19946mcpsimp"></a><a name="p19946mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row19947mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p19949mcpsimp"><a name="p19949mcpsimp"></a><a name="p19949mcpsimp"></a>int</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p19951mcpsimp"><a name="p19951mcpsimp"></a><a name="p19951mcpsimp"></a>Joint type of a polyline. The default value is <a href="jointtype.md#section103572813326">DEFAULT</a>.</p>
</td>
</tr>
</tbody>
</table>

## getPattern<a name="section1131102385516"></a>

<a name="table19953mcpsimp"></a>
<table><thead align="left"><tr id="row19957mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p19959mcpsimp"><a name="p19959mcpsimp"></a><a name="p19959mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row19960mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p19962mcpsimp"><a name="p19962mcpsimp"></a><a name="p19962mcpsimp"></a>public List&lt;<a href="patternitem.md">PatternItem</a>&gt; getPattern()</p>
<p id="p19965mcpsimp"><a name="p19965mcpsimp"></a><a name="p19965mcpsimp"></a>Obtains the stroke pattern of a polyline.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table19971mcpsimp"></a>
<table><thead align="left"><tr id="row19976mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p19978mcpsimp"><a name="p19978mcpsimp"></a><a name="p19978mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p19980mcpsimp"><a name="p19980mcpsimp"></a><a name="p19980mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row19981mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p19983mcpsimp"><a name="p19983mcpsimp"></a><a name="p19983mcpsimp"></a>List&lt;<a href="patternitem.md">PatternItem</a>&gt;</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p19985mcpsimp"><a name="p19985mcpsimp"></a><a name="p19985mcpsimp"></a>Stroke pattern of a polyline.</p>
</td>
</tr>
</tbody>
</table>

## getPoints<a name="section166671316563"></a>

<a name="table19987mcpsimp"></a>
<table><thead align="left"><tr id="row19991mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p19993mcpsimp"><a name="p19993mcpsimp"></a><a name="p19993mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row19994mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p19996mcpsimp"><a name="p19996mcpsimp"></a><a name="p19996mcpsimp"></a>public List&lt;<a href="latlng.md">LatLng</a>&gt; getPoints()</p>
<p id="p19999mcpsimp"><a name="p19999mcpsimp"></a><a name="p19999mcpsimp"></a>Obtains the vertex set of a polyline.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table20005mcpsimp"></a>
<table><thead align="left"><tr id="row20010mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p20012mcpsimp"><a name="p20012mcpsimp"></a><a name="p20012mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p20014mcpsimp"><a name="p20014mcpsimp"></a><a name="p20014mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row20015mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p20017mcpsimp"><a name="p20017mcpsimp"></a><a name="p20017mcpsimp"></a>List&lt;<a href="latlng.md">LatLng</a>&gt;</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p20019mcpsimp"><a name="p20019mcpsimp"></a><a name="p20019mcpsimp"></a>Vertex set of a polyline.</p>
</td>
</tr>
</tbody>
</table>

## getStartCap<a name="section174211035165617"></a>

<a name="table20021mcpsimp"></a>
<table><thead align="left"><tr id="row20025mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p20027mcpsimp"><a name="p20027mcpsimp"></a><a name="p20027mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row20028mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p20030mcpsimp"><a name="p20030mcpsimp"></a><a name="p20030mcpsimp"></a>public <a href="cap.md">Cap</a> getStartCap()</p>
<p id="p6458194965617"><a name="p6458194965617"></a><a name="p6458194965617"></a>Obtains the start vertex cap of a polyline.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table20039mcpsimp"></a>
<table><thead align="left"><tr id="row20044mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p20046mcpsimp"><a name="p20046mcpsimp"></a><a name="p20046mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p20048mcpsimp"><a name="p20048mcpsimp"></a><a name="p20048mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row20049mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p1099418571545"><a name="p1099418571545"></a><a name="p1099418571545"></a><a href="cap.md">Cap</a></p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p20053mcpsimp"><a name="p20053mcpsimp"></a><a name="p20053mcpsimp"></a>Start vertex cap of a polyline. If no vertex cap is set, the default value <a href="buttcap.md">ButtCap</a> will be returned.</p>
</td>
</tr>
</tbody>
</table>

## getTag<a name="section1297371116575"></a>

<a name="table20055mcpsimp"></a>
<table><thead align="left"><tr id="row20059mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p20061mcpsimp"><a name="p20061mcpsimp"></a><a name="p20061mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row20062mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p20064mcpsimp"><a name="p20064mcpsimp"></a><a name="p20064mcpsimp"></a>public Object getTag()</p>
<p id="p20067mcpsimp"><a name="p20067mcpsimp"></a><a name="p20067mcpsimp"></a>Obtains the <strong id="b155673643816"><a name="b155673643816"></a><a name="b155673643816"></a>tag</strong> attribute (if it has been set) of a polyline. </p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table20073mcpsimp"></a>
<table><thead align="left"><tr id="row20078mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p20080mcpsimp"><a name="p20080mcpsimp"></a><a name="p20080mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p20082mcpsimp"><a name="p20082mcpsimp"></a><a name="p20082mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row20083mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p20085mcpsimp"><a name="p20085mcpsimp"></a><a name="p20085mcpsimp"></a>Object</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p20087mcpsimp"><a name="p20087mcpsimp"></a><a name="p20087mcpsimp"></a><strong id="b7862251161914"><a name="b7862251161914"></a><a name="b7862251161914"></a>Object</strong> if a tag has been set; <strong id="b15863105115196"><a name="b15863105115196"></a><a name="b15863105115196"></a>null</strong> otherwise.</p>
</td>
</tr>
</tbody>
</table>

## getWidth<a name="section142291349125716"></a>

<a name="table20089mcpsimp"></a>
<table><thead align="left"><tr id="row20093mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p20095mcpsimp"><a name="p20095mcpsimp"></a><a name="p20095mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row20096mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p20098mcpsimp"><a name="p20098mcpsimp"></a><a name="p20098mcpsimp"></a>public float getWidth()</p>
<p id="p20101mcpsimp"><a name="p20101mcpsimp"></a><a name="p20101mcpsimp"></a>Obtains the stroke width of a polyline. The default width is 10 pixels. </p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table20109mcpsimp"></a>
<table><thead align="left"><tr id="row20114mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p20116mcpsimp"><a name="p20116mcpsimp"></a><a name="p20116mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p20118mcpsimp"><a name="p20118mcpsimp"></a><a name="p20118mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row20119mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p20121mcpsimp"><a name="p20121mcpsimp"></a><a name="p20121mcpsimp"></a>float</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p20123mcpsimp"><a name="p20123mcpsimp"></a><a name="p20123mcpsimp"></a>Stroke width of a polyline, in pixels.</p>
<div class="note" id="note4300125611715"><a name="note4300125611715"></a><a name="note4300125611715"></a><span class="notetitle"> NOTE: </span><div class="notebody"><p id="p1430065601711"><a name="p1430065601711"></a><a name="p1430065601711"></a>The stroke width returned by this API is one third of the actual width.</p>
</div></div>
</td>
</tr>
</tbody>
</table>

## getZIndex<a name="section5767142015588"></a>

<a name="table20125mcpsimp"></a>
<table><thead align="left"><tr id="row20129mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p20131mcpsimp"><a name="p20131mcpsimp"></a><a name="p20131mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row20132mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p20134mcpsimp"><a name="p20134mcpsimp"></a><a name="p20134mcpsimp"></a>public float getZIndex()</p>
<p id="p20137mcpsimp"><a name="p20137mcpsimp"></a><a name="p20137mcpsimp"></a>Obtains the z-index of a polyline.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table20143mcpsimp"></a>
<table><thead align="left"><tr id="row20148mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p20150mcpsimp"><a name="p20150mcpsimp"></a><a name="p20150mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p20152mcpsimp"><a name="p20152mcpsimp"></a><a name="p20152mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row20153mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p20155mcpsimp"><a name="p20155mcpsimp"></a><a name="p20155mcpsimp"></a>float</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p20157mcpsimp"><a name="p20157mcpsimp"></a><a name="p20157mcpsimp"></a>Z-index, which indicates the overlapping order of a polyline.</p>
</td>
</tr>
</tbody>
</table>

## hashCode<a name="section142719578585"></a>

<a name="table20159mcpsimp"></a>
<table><thead align="left"><tr id="row20163mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p20165mcpsimp"><a name="p20165mcpsimp"></a><a name="p20165mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row20166mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p20168mcpsimp"><a name="p20168mcpsimp"></a><a name="p20168mcpsimp"></a>public int hashCode()</p>
<p id="p20171mcpsimp"><a name="p20171mcpsimp"></a><a name="p20171mcpsimp"></a>Obtains the hash code of a polyline.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table20177mcpsimp"></a>
<table><thead align="left"><tr id="row20182mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p20184mcpsimp"><a name="p20184mcpsimp"></a><a name="p20184mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p20186mcpsimp"><a name="p20186mcpsimp"></a><a name="p20186mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row20187mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p20189mcpsimp"><a name="p20189mcpsimp"></a><a name="p20189mcpsimp"></a>int</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p20191mcpsimp"><a name="p20191mcpsimp"></a><a name="p20191mcpsimp"></a>Hash code of a polyline.</p>
</td>
</tr>
</tbody>
</table>

## isClickable<a name="section1121182819597"></a>

<a name="table20193mcpsimp"></a>
<table><thead align="left"><tr id="row20197mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p20199mcpsimp"><a name="p20199mcpsimp"></a><a name="p20199mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row20200mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p20202mcpsimp"><a name="p20202mcpsimp"></a><a name="p20202mcpsimp"></a>public boolean isClickable()</p>
<p id="p20205mcpsimp"><a name="p20205mcpsimp"></a><a name="p20205mcpsimp"></a>Checks whether a polyline is tappable.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table20211mcpsimp"></a>
<table><thead align="left"><tr id="row20216mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p20218mcpsimp"><a name="p20218mcpsimp"></a><a name="p20218mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p20220mcpsimp"><a name="p20220mcpsimp"></a><a name="p20220mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row20221mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p20223mcpsimp"><a name="p20223mcpsimp"></a><a name="p20223mcpsimp"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p20225mcpsimp"><a name="p20225mcpsimp"></a><a name="p20225mcpsimp"></a><strong id="b1925035372414"><a name="b1925035372414"></a><a name="b1925035372414"></a>true</strong> if the polyline is tappable; <strong id="b158534515242"><a name="b158534515242"></a><a name="b158534515242"></a>false</strong> otherwise.</p>
</td>
</tr>
</tbody>
</table>

## isGeodesic<a name="section1785131609"></a>

<a name="table20227mcpsimp"></a>
<table><thead align="left"><tr id="row20231mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p20233mcpsimp"><a name="p20233mcpsimp"></a><a name="p20233mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row20234mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p20236mcpsimp"><a name="p20236mcpsimp"></a><a name="p20236mcpsimp"></a>public boolean isGeodesic()</p>
<p id="p20239mcpsimp"><a name="p20239mcpsimp"></a><a name="p20239mcpsimp"></a>Checks whether each segment of a polyline is drawn as a geodesic.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table20245mcpsimp"></a>
<table><thead align="left"><tr id="row20250mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p20252mcpsimp"><a name="p20252mcpsimp"></a><a name="p20252mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p20254mcpsimp"><a name="p20254mcpsimp"></a><a name="p20254mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row20255mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p20257mcpsimp"><a name="p20257mcpsimp"></a><a name="p20257mcpsimp"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p20259mcpsimp"><a name="p20259mcpsimp"></a><a name="p20259mcpsimp"></a><strong id="b8186191412255"><a name="b8186191412255"></a><a name="b8186191412255"></a>true</strong> if each segment is drawn as a geodesic; <strong id="b8186201410253"><a name="b8186201410253"></a><a name="b8186201410253"></a>false</strong> otherwise.</p>
</td>
</tr>
</tbody>
</table>

## isVisible<a name="section243117361704"></a>

<a name="table20261mcpsimp"></a>
<table><thead align="left"><tr id="row20265mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p20267mcpsimp"><a name="p20267mcpsimp"></a><a name="p20267mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row20268mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p20270mcpsimp"><a name="p20270mcpsimp"></a><a name="p20270mcpsimp"></a>public boolean isVisible()</p>
<p id="p20273mcpsimp"><a name="p20273mcpsimp"></a><a name="p20273mcpsimp"></a>Checks whether a polyline is visible.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table20279mcpsimp"></a>
<table><thead align="left"><tr id="row20284mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p20286mcpsimp"><a name="p20286mcpsimp"></a><a name="p20286mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p20288mcpsimp"><a name="p20288mcpsimp"></a><a name="p20288mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row20289mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p20291mcpsimp"><a name="p20291mcpsimp"></a><a name="p20291mcpsimp"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p20293mcpsimp"><a name="p20293mcpsimp"></a><a name="p20293mcpsimp"></a><strong id="b19874431122512"><a name="b19874431122512"></a><a name="b19874431122512"></a>true</strong> if the polyline is visible; <strong id="b487973111254"><a name="b487973111254"></a><a name="b487973111254"></a>false</strong> otherwise.</p>
</td>
</tr>
</tbody>
</table>

## remove<a name="section193591012413"></a>

<a name="table20295mcpsimp"></a>
<table><thead align="left"><tr id="row20299mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p20301mcpsimp"><a name="p20301mcpsimp"></a><a name="p20301mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row20302mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p20304mcpsimp"><a name="p20304mcpsimp"></a><a name="p20304mcpsimp"></a>public void remove()</p>
<p id="p20307mcpsimp"><a name="p20307mcpsimp"></a><a name="p20307mcpsimp"></a>Removes a polyline from a map. After the polyline is removed, the operations of all its methods will be undefined.</p>
</td>
</tr>
</tbody>
</table>

## setClickable<a name="section114084419112"></a>

<a name="table20315mcpsimp"></a>
<table><thead align="left"><tr id="row20319mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p20321mcpsimp"><a name="p20321mcpsimp"></a><a name="p20321mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row20322mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p20324mcpsimp"><a name="p20324mcpsimp"></a><a name="p20324mcpsimp"></a>public void setClickable(boolean clickable)</p>
<p id="p20327mcpsimp"><a name="p20327mcpsimp"></a><a name="p20327mcpsimp"></a>Sets whether a polyline is tappable.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table20330mcpsimp"></a>
<table><thead align="left"><tr id="row20335mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p20337mcpsimp"><a name="p20337mcpsimp"></a><a name="p20337mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p20339mcpsimp"><a name="p20339mcpsimp"></a><a name="p20339mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row20340mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p20342mcpsimp"><a name="p20342mcpsimp"></a><a name="p20342mcpsimp"></a>clickable</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p20344mcpsimp"><a name="p20344mcpsimp"></a><a name="p20344mcpsimp"></a>Indicates whether a polyline is tappable. <strong id="b8885144514215"><a name="b8885144514215"></a><a name="b8885144514215"></a>true</strong>: yes; <strong id="b1489013452212"><a name="b1489013452212"></a><a name="b1489013452212"></a>false</strong> (default): no. </p>
</td>
</tr>
</tbody>
</table>

## setColor<a name="section1215112270216"></a>

<a name="table20349mcpsimp"></a>
<table><thead align="left"><tr id="row20353mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p20355mcpsimp"><a name="p20355mcpsimp"></a><a name="p20355mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row20356mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p20358mcpsimp"><a name="p20358mcpsimp"></a><a name="p20358mcpsimp"></a>public void setColor(int color)</p>
<p id="p20361mcpsimp"><a name="p20361mcpsimp"></a><a name="p20361mcpsimp"></a>Sets the stroke color of a polyline.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table20364mcpsimp"></a>
<table><thead align="left"><tr id="row20369mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p20371mcpsimp"><a name="p20371mcpsimp"></a><a name="p20371mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p20373mcpsimp"><a name="p20373mcpsimp"></a><a name="p20373mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row20374mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p20376mcpsimp"><a name="p20376mcpsimp"></a><a name="p20376mcpsimp"></a>color</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p20378mcpsimp"><a name="p20378mcpsimp"></a><a name="p20378mcpsimp"></a>Color in ARGB format. By default, the stroke color is black (0xff000000).</p>
</td>
</tr>
</tbody>
</table>

## setEndCap<a name="section8261559324"></a>

<a name="table20383mcpsimp"></a>
<table><thead align="left"><tr id="row20387mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p20389mcpsimp"><a name="p20389mcpsimp"></a><a name="p20389mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row20390mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p20392mcpsimp"><a name="p20392mcpsimp"></a><a name="p20392mcpsimp"></a>public void setEndCap(<a href="cap.md">Cap</a> endCap)</p>
<p id="p20395mcpsimp"><a name="p20395mcpsimp"></a><a name="p20395mcpsimp"></a>Sets the end vertex cap of a polyline.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table20398mcpsimp"></a>
<table><thead align="left"><tr id="row20403mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p20405mcpsimp"><a name="p20405mcpsimp"></a><a name="p20405mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p20407mcpsimp"><a name="p20407mcpsimp"></a><a name="p20407mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row20408mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p20410mcpsimp"><a name="p20410mcpsimp"></a><a name="p20410mcpsimp"></a>endCap</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p20412mcpsimp"><a name="p20412mcpsimp"></a><a name="p20412mcpsimp"></a>End vertex cap. The default value is <a href="buttcap.md">ButtCap</a>.</p>
</td>
</tr>
</tbody>
</table>

## setGeodesic<a name="section582118411634"></a>

<a name="table20417mcpsimp"></a>
<table><thead align="left"><tr id="row20421mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p20423mcpsimp"><a name="p20423mcpsimp"></a><a name="p20423mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row20424mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p20426mcpsimp"><a name="p20426mcpsimp"></a><a name="p20426mcpsimp"></a>public void setGeodesic(boolean geodesic)</p>
<p id="p20429mcpsimp"><a name="p20429mcpsimp"></a><a name="p20429mcpsimp"></a>Sets whether to draw each segment of a polyline as a geodesic. If this parameter is not set, the default value <strong id="b20925940195319"><a name="b20925940195319"></a><a name="b20925940195319"></a>false</strong> will be returned.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table20432mcpsimp"></a>
<table><thead align="left"><tr id="row20437mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p20439mcpsimp"><a name="p20439mcpsimp"></a><a name="p20439mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p20441mcpsimp"><a name="p20441mcpsimp"></a><a name="p20441mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row20442mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p20444mcpsimp"><a name="p20444mcpsimp"></a><a name="p20444mcpsimp"></a>geodesic</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p20446mcpsimp"><a name="p20446mcpsimp"></a><a name="p20446mcpsimp"></a>Indicates whether to draw each segment of a polyline as a geodesic. <strong id="b473991514274"><a name="b473991514274"></a><a name="b473991514274"></a>true</strong>: yes; <strong id="b7740191519271"><a name="b7740191519271"></a><a name="b7740191519271"></a>false</strong>: no.</p>
</td>
</tr>
</tbody>
</table>

## setJointType<a name="section7764119142"></a>

<a name="table20451mcpsimp"></a>
<table><thead align="left"><tr id="row20455mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p20457mcpsimp"><a name="p20457mcpsimp"></a><a name="p20457mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row20458mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p20460mcpsimp"><a name="p20460mcpsimp"></a><a name="p20460mcpsimp"></a>public void setJointType(int jointType)</p>
<p id="p20463mcpsimp"><a name="p20463mcpsimp"></a><a name="p20463mcpsimp"></a>Sets the joint type of all vertices of a polyline, except the start and end vertices. For details about the allowed joint types, please refer to <a href="jointtype.md">JointType</a>. If the joint type is not set or not an allowed one, the default value <a href="jointtype.md#section103572813326">DEFAULT</a> will be used.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table20466mcpsimp"></a>
<table><thead align="left"><tr id="row20471mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p20473mcpsimp"><a name="p20473mcpsimp"></a><a name="p20473mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p20475mcpsimp"><a name="p20475mcpsimp"></a><a name="p20475mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row20476mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p20478mcpsimp"><a name="p20478mcpsimp"></a><a name="p20478mcpsimp"></a>jointType</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p20480mcpsimp"><a name="p20480mcpsimp"></a><a name="p20480mcpsimp"></a>Joint type. The default value is <a href="jointtype.md#section103572813326">DEFAULT</a>.</p>
</td>
</tr>
</tbody>
</table>

## setPattern<a name="section16311361458"></a>

<a name="table20485mcpsimp"></a>
<table><thead align="left"><tr id="row20489mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p20491mcpsimp"><a name="p20491mcpsimp"></a><a name="p20491mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row20492mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p20494mcpsimp"><a name="p20494mcpsimp"></a><a name="p20494mcpsimp"></a>public void setPattern(List&lt;<a href="patternitem.md">PatternItem</a>&gt; pattern)</p>
<p id="p462211191518"><a name="p462211191518"></a><a name="p462211191518"></a>Sets the stroke pattern of a polyline.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table20500mcpsimp"></a>
<table><thead align="left"><tr id="row20505mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p20507mcpsimp"><a name="p20507mcpsimp"></a><a name="p20507mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p20509mcpsimp"><a name="p20509mcpsimp"></a><a name="p20509mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row20510mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p20512mcpsimp"><a name="p20512mcpsimp"></a><a name="p20512mcpsimp"></a>pattern</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p20514mcpsimp"><a name="p20514mcpsimp"></a><a name="p20514mcpsimp"></a><a href="patternitem.md">PatternItem</a> object set. The default value is <strong id="b13161111510612"><a name="b13161111510612"></a><a name="b13161111510612"></a>null</strong>, indicating that the stroke is in the solid pattern. </p>
</td>
</tr>
</tbody>
</table>

## setPoints<a name="section1721284615510"></a>

<a name="table20519mcpsimp"></a>
<table><thead align="left"><tr id="row20523mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p20525mcpsimp"><a name="p20525mcpsimp"></a><a name="p20525mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row20526mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p20528mcpsimp"><a name="p20528mcpsimp"></a><a name="p20528mcpsimp"></a>public void setPoints(List&lt;<a href="latlng.md">LatLng</a>&gt; points)</p>
<p id="p18583401667"><a name="p18583401667"></a><a name="p18583401667"></a>Sets the vertex coordinates of a polyline. By default, a straight line is drawn between the end vertex of the polyline and the set vertex coordinate point. </p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table20536mcpsimp"></a>
<table><thead align="left"><tr id="row20541mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p20543mcpsimp"><a name="p20543mcpsimp"></a><a name="p20543mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p20545mcpsimp"><a name="p20545mcpsimp"></a><a name="p20545mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row20546mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p20548mcpsimp"><a name="p20548mcpsimp"></a><a name="p20548mcpsimp"></a>points</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p20550mcpsimp"><a name="p20550mcpsimp"></a><a name="p20550mcpsimp"></a>Vertex set of a polyline. By default, a polyline is not a closed area. To form a closed area, the start and end points of the polyline must be the same.</p>
</td>
</tr>
</tbody>
</table>

## setStartCap<a name="section1902102711613"></a>

<a name="table20555mcpsimp"></a>
<table><thead align="left"><tr id="row20559mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p20561mcpsimp"><a name="p20561mcpsimp"></a><a name="p20561mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row20562mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p20564mcpsimp"><a name="p20564mcpsimp"></a><a name="p20564mcpsimp"></a>public void setStartCap(<a href="cap.md">Cap</a> startCap)</p>
<p id="p20567mcpsimp"><a name="p20567mcpsimp"></a><a name="p20567mcpsimp"></a>Sets the start vertex cap of a polyline.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table20570mcpsimp"></a>
<table><thead align="left"><tr id="row20575mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p20577mcpsimp"><a name="p20577mcpsimp"></a><a name="p20577mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p20579mcpsimp"><a name="p20579mcpsimp"></a><a name="p20579mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row20580mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p20582mcpsimp"><a name="p20582mcpsimp"></a><a name="p20582mcpsimp"></a>startCap</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p20584mcpsimp"><a name="p20584mcpsimp"></a><a name="p20584mcpsimp"></a>Start vertex cap. The default value is <a href="buttcap.md">ButtCap</a>.</p>
</td>
</tr>
</tbody>
</table>

## setTag<a name="section26811611775"></a>

<a name="table20589mcpsimp"></a>
<table><thead align="left"><tr id="row20593mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p20595mcpsimp"><a name="p20595mcpsimp"></a><a name="p20595mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row20596mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p20598mcpsimp"><a name="p20598mcpsimp"></a><a name="p20598mcpsimp"></a>public void setTag(Object tag)</p>
<p id="p20601mcpsimp"><a name="p20601mcpsimp"></a><a name="p20601mcpsimp"></a>Sets the <strong id="b1419016504120"><a name="b1419016504120"></a><a name="b1419016504120"></a>tag</strong> attribute of a polyline. If <strong id="b09541610192910"><a name="b09541610192910"></a><a name="b09541610192910"></a>null</strong> is passed, the <strong id="b116026381320"><a name="b116026381320"></a><a name="b116026381320"></a>tag</strong> attribute will be cleared.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table20604mcpsimp"></a>
<table><thead align="left"><tr id="row20609mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p20611mcpsimp"><a name="p20611mcpsimp"></a><a name="p20611mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p20613mcpsimp"><a name="p20613mcpsimp"></a><a name="p20613mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row20614mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p20616mcpsimp"><a name="p20616mcpsimp"></a><a name="p20616mcpsimp"></a>tag</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p20618mcpsimp"><a name="p20618mcpsimp"></a><a name="p20618mcpsimp"></a>Tag of a polyline.</p>
</td>
</tr>
</tbody>
</table>

## setVisible<a name="section2681104718714"></a>

<a name="table20623mcpsimp"></a>
<table><thead align="left"><tr id="row20627mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p20629mcpsimp"><a name="p20629mcpsimp"></a><a name="p20629mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row20630mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p20632mcpsimp"><a name="p20632mcpsimp"></a><a name="p20632mcpsimp"></a>public void setVisible(boolean visible)</p>
<p id="p20635mcpsimp"><a name="p20635mcpsimp"></a><a name="p20635mcpsimp"></a>Sets whether a polyline is visible. If the polyline is invisible, it will not be drawn but all other states will be preserved.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table20638mcpsimp"></a>
<table><thead align="left"><tr id="row20643mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p20645mcpsimp"><a name="p20645mcpsimp"></a><a name="p20645mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p20647mcpsimp"><a name="p20647mcpsimp"></a><a name="p20647mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row20648mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p20650mcpsimp"><a name="p20650mcpsimp"></a><a name="p20650mcpsimp"></a>visible</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p20652mcpsimp"><a name="p20652mcpsimp"></a><a name="p20652mcpsimp"></a>Indicates whether a polyline is visible. The default value is <strong id="b211114018299"><a name="b211114018299"></a><a name="b211114018299"></a>true</strong>.</p>
</td>
</tr>
</tbody>
</table>

## setWidth<a name="section146861631180"></a>

<a name="table20657mcpsimp"></a>
<table><thead align="left"><tr id="row20661mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p20663mcpsimp"><a name="p20663mcpsimp"></a><a name="p20663mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row20664mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p20666mcpsimp"><a name="p20666mcpsimp"></a><a name="p20666mcpsimp"></a>public void setWidth(float width)</p>
<p id="p20669mcpsimp"><a name="p20669mcpsimp"></a><a name="p20669mcpsimp"></a>Sets the stroke width of a polyline.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table20672mcpsimp"></a>
<table><thead align="left"><tr id="row20677mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p20679mcpsimp"><a name="p20679mcpsimp"></a><a name="p20679mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p20681mcpsimp"><a name="p20681mcpsimp"></a><a name="p20681mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row20682mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p20684mcpsimp"><a name="p20684mcpsimp"></a><a name="p20684mcpsimp"></a>width</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p20686mcpsimp"><a name="p20686mcpsimp"></a><a name="p20686mcpsimp"></a>Stroke width of a polyline, in pixels. The value must be greater than or equal to 0. The default value is <strong id="b1044461431214"><a name="b1044461431214"></a><a name="b1044461431214"></a>10</strong>.</p>
<div class="note" id="note206465511998"><a name="note206465511998"></a><a name="note206465511998"></a><span class="notetitle"> NOTE: </span><div class="notebody"><p id="p1564615117915"><a name="p1564615117915"></a><a name="p1564615117915"></a>To ensure compatibility, it is recommended that the actual stroke width triples the passed parameter value.</p>
</div></div>
</td>
</tr>
</tbody>
</table>

**Throws**

<a name="table10494mcpsimp"></a>
<table><thead align="left"><tr id="row10499mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p10501mcpsimp"><a name="p10501mcpsimp"></a><a name="p10501mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p10503mcpsimp"><a name="p10503mcpsimp"></a><a name="p10503mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row10504mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p10506mcpsimp"><a name="p10506mcpsimp"></a><a name="p10506mcpsimp"></a>IllegalArgumentException</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p10508mcpsimp"><a name="p10508mcpsimp"></a><a name="p10508mcpsimp"></a>If the passed stroke width is negative.</p>
</td>
</tr>
</tbody>
</table>

## setZIndex<a name="section16726451291"></a>

<a name="table20691mcpsimp"></a>
<table><thead align="left"><tr id="row20695mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p20697mcpsimp"><a name="p20697mcpsimp"></a><a name="p20697mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row20698mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p20700mcpsimp"><a name="p20700mcpsimp"></a><a name="p20700mcpsimp"></a>public void setZIndex(float zIndex)</p>
<p id="p20703mcpsimp"><a name="p20703mcpsimp"></a><a name="p20703mcpsimp"></a>Sets the z-index of a polyline. The z-index indicates the overlapping order of a polyline. A polyline with a larger z-index overlaps that with a smaller z-index. Polylines with the same z-index overlap each other by the order in which they are added.</p>
<div class="note" id="note29874189587"><a name="note29874189587"></a><a name="note29874189587"></a><span class="notetitle"> NOTE: </span><div class="notebody"><p id="p99871718105811"><a name="p99871718105811"></a><a name="p99871718105811"></a>The following formula must be met: Number of circles and polygons x 2 + Number of polylines and ground overlays ≤ 1450. If the formula is not met, overlapping errors may occur. </p>
</div></div>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table20706mcpsimp"></a>
<table><thead align="left"><tr id="row20711mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p20713mcpsimp"><a name="p20713mcpsimp"></a><a name="p20713mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p20715mcpsimp"><a name="p20715mcpsimp"></a><a name="p20715mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row20716mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p20718mcpsimp"><a name="p20718mcpsimp"></a><a name="p20718mcpsimp"></a>zIndex</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p20720mcpsimp"><a name="p20720mcpsimp"></a><a name="p20720mcpsimp"></a>Z-index, which indicates the overlapping order of a polyline. By default, the z-index is 0.</p>
</td>
</tr>
</tbody>
</table>

