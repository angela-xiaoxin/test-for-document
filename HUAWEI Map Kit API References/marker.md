# Marker<a name="EN-US_TOPIC_0000001145860955"></a>

-   [Public Method Summary](#section198571651191315)
-   [Public Methods](#section166797915511)
-   [equals](#section9995901416)
-   [getAlpha](#section19252111810145)
-   [getId](#section105771527101411)
-   [getPosition](#section49343761418)
-   [getRotation](#section26741745121414)
-   [getSnippet](#section7851155271416)
-   [getTag](#section1625517241520)
-   [getTitle](#section15178141116154)
-   [getZIndex](#section381418141514)
-   [hashCode](#section075815268151)
-   [hideInfoWindow](#section352393481515)
-   [isClusterable](#section12103164219159)
-   [isDraggable](#section1947358193318)
-   [isFlat](#section16358133310341)
-   [isInfoWindowShown](#section643110419342)
-   [isVisible](#section2207551183412)
-   [remove](#section6594131123511)
-   [setAlpha](#section1776118819353)
-   [setAnchor](#section14156191615354)
-   [setAnimation](#section138322612114)
-   [setDraggable](#section58671625103515)
-   [setFlat](#section1797433173511)
-   [setIcon](#section1680710531355)
-   [setInfoWindowAnchor](#section1858016183620)
-   [setMarkerAnchor](#section992613197119)
-   [setPosition](#section13917151362)
-   [h2setRotation](#section1989919222361)
-   [setSnippet](#section165927340363)
-   [setTag](#section893234843611)
-   [setTitle](#section13963185519361)
-   [setVisible](#section1775916212376)
-   [setZIndex](#section952413920376)
-   [showInfoWindow](#section13223817123711)
-   [startAnimation](#section13557451287)


<a name="table14555mcpsimp"></a>
<table><thead align="left"><tr id="row14559mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p14561mcpsimp"><a name="p14561mcpsimp"></a><a name="p14561mcpsimp"></a>Class Info</p>
</th>
</tr>
</thead>
<tbody><tr id="row14562mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p182061719416"><a name="p182061719416"></a><a name="p182061719416"></a>public class Marker</p>
<p id="p14564mcpsimp"><a name="p14564mcpsimp"></a><a name="p14564mcpsimp"></a>Icon placed at the specified position on the map. An instance of this type will be returned when the <a href="huaweimap.md#section84151866413">addMarker</a> method in the <a href="huaweimap.md">HuaweiMap</a> class is called.</p>
</td>
</tr>
</tbody>
</table>

## Public Method Summary<a name="section198571651191315"></a>

<a name="table14579mcpsimp"></a>
<table><thead align="left"><tr id="row14584mcpsimp"><th class="cellrowborder" valign="top" width="40%" id="mcps1.1.3.1.1"><p id="p081120285386"><a name="p081120285386"></a><a name="p081120285386"></a>Qualifier and Type</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.1.3.1.2"><p id="p681112883813"><a name="p681112883813"></a><a name="p681112883813"></a>Method Name and Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row14589mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p14591mcpsimp"><a name="p14591mcpsimp"></a><a name="p14591mcpsimp"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p14593mcpsimp"><a name="p14593mcpsimp"></a><a name="p14593mcpsimp"></a><a href="#section9995901416">equals</a>(Object other)</p>
<p id="p66142485254"><a name="p66142485254"></a><a name="p66142485254"></a>Checks whether a marker object equals another.</p>
</td>
</tr>
<tr id="row14594mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p14596mcpsimp"><a name="p14596mcpsimp"></a><a name="p14596mcpsimp"></a>float</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p14598mcpsimp"><a name="p14598mcpsimp"></a><a name="p14598mcpsimp"></a><a href="#section19252111810145">getAlpha</a>()</p>
<p id="p1656154918258"><a name="p1656154918258"></a><a name="p1656154918258"></a>Obtains the transparency of a marker.</p>
</td>
</tr>
<tr id="row14599mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p14601mcpsimp"><a name="p14601mcpsimp"></a><a name="p14601mcpsimp"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p14603mcpsimp"><a name="p14603mcpsimp"></a><a name="p14603mcpsimp"></a><a href="#section105771527101411">getId</a>()</p>
<p id="p105901850152516"><a name="p105901850152516"></a><a name="p105901850152516"></a>Obtains the ID of a marker on a map.</p>
</td>
</tr>
<tr id="row14604mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p14606mcpsimp"><a name="p14606mcpsimp"></a><a name="p14606mcpsimp"></a>LatLng</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p14608mcpsimp"><a name="p14608mcpsimp"></a><a name="p14608mcpsimp"></a><a href="#section49343761418">getPosition</a>()</p>
<p id="p20457195112258"><a name="p20457195112258"></a><a name="p20457195112258"></a>Obtains the position of a marker.</p>
</td>
</tr>
<tr id="row14609mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p14611mcpsimp"><a name="p14611mcpsimp"></a><a name="p14611mcpsimp"></a>float</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p14613mcpsimp"><a name="p14613mcpsimp"></a><a name="p14613mcpsimp"></a><a href="#section26741745121414">getRotation</a>()</p>
<p id="p1693045262519"><a name="p1693045262519"></a><a name="p1693045262519"></a>Obtains the rotation angle of a marker.</p>
</td>
</tr>
<tr id="row14614mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p14616mcpsimp"><a name="p14616mcpsimp"></a><a name="p14616mcpsimp"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p14618mcpsimp"><a name="p14618mcpsimp"></a><a name="p14618mcpsimp"></a><a href="#section7851155271416">getSnippet</a>()</p>
<p id="p12778195310257"><a name="p12778195310257"></a><a name="p12778195310257"></a>Obtains the text snippet of a marker.</p>
</td>
</tr>
<tr id="row14619mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p14621mcpsimp"><a name="p14621mcpsimp"></a><a name="p14621mcpsimp"></a>Object</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p14623mcpsimp"><a name="p14623mcpsimp"></a><a name="p14623mcpsimp"></a><a href="#section1625517241520">getTag</a>()</p>
<p id="p1467505414255"><a name="p1467505414255"></a><a name="p1467505414255"></a>Obtains the <strong id="b1398134161614"><a name="b1398134161614"></a><a name="b1398134161614"></a>tag</strong> attribute of a marker.</p>
</td>
</tr>
<tr id="row14624mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p14626mcpsimp"><a name="p14626mcpsimp"></a><a name="p14626mcpsimp"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p14628mcpsimp"><a name="p14628mcpsimp"></a><a name="p14628mcpsimp"></a><a href="#section15178141116154">getTitle</a>()</p>
<p id="p16472155517259"><a name="p16472155517259"></a><a name="p16472155517259"></a>Obtains the title of a marker.</p>
</td>
</tr>
<tr id="row14629mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p14631mcpsimp"><a name="p14631mcpsimp"></a><a name="p14631mcpsimp"></a>float</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p14633mcpsimp"><a name="p14633mcpsimp"></a><a name="p14633mcpsimp"></a><a href="#section381418141514">getZIndex</a>()</p>
<p id="p6893185682517"><a name="p6893185682517"></a><a name="p6893185682517"></a>Obtains the z-index of a marker.</p>
</td>
</tr>
<tr id="row14634mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p14636mcpsimp"><a name="p14636mcpsimp"></a><a name="p14636mcpsimp"></a>int</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p14638mcpsimp"><a name="p14638mcpsimp"></a><a name="p14638mcpsimp"></a><a href="#section075815268151">hashCode</a>()</p>
<p id="p1476605762511"><a name="p1476605762511"></a><a name="p1476605762511"></a>Obtains the hash value of a marker.</p>
</td>
</tr>
<tr id="row14639mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p14641mcpsimp"><a name="p14641mcpsimp"></a><a name="p14641mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p14643mcpsimp"><a name="p14643mcpsimp"></a><a name="p14643mcpsimp"></a><a href="#section352393481515">hideInfoWindow</a>()</p>
<p id="p1736105815257"><a name="p1736105815257"></a><a name="p1736105815257"></a>Hides the information window that is displayed for a marker.</p>
</td>
</tr>
<tr id="row14644mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p14646mcpsimp"><a name="p14646mcpsimp"></a><a name="p14646mcpsimp"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p14648mcpsimp"><a name="p14648mcpsimp"></a><a name="p14648mcpsimp"></a><a href="#section12103164219159">isClusterable</a>()</p>
<p id="p14582205952519"><a name="p14582205952519"></a><a name="p14582205952519"></a>Checks whether a marker can be clustered.</p>
</td>
</tr>
<tr id="row14649mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p14651mcpsimp"><a name="p14651mcpsimp"></a><a name="p14651mcpsimp"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p14653mcpsimp"><a name="p14653mcpsimp"></a><a name="p14653mcpsimp"></a><a href="#section1947358193318">isDraggable</a>()</p>
<p id="p7617100142616"><a name="p7617100142616"></a><a name="p7617100142616"></a>Checks whether users can long press a marker and drag it.</p>
</td>
</tr>
<tr id="row14654mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p14656mcpsimp"><a name="p14656mcpsimp"></a><a name="p14656mcpsimp"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p14658mcpsimp"><a name="p14658mcpsimp"></a><a name="p14658mcpsimp"></a><a href="#section16358133310341">isFlat</a>()</p>
<p id="p11274727264"><a name="p11274727264"></a><a name="p11274727264"></a>Checks whether a marker is flatly attached to the map.</p>
</td>
</tr>
<tr id="row14659mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p14661mcpsimp"><a name="p14661mcpsimp"></a><a name="p14661mcpsimp"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p14663mcpsimp"><a name="p14663mcpsimp"></a><a name="p14663mcpsimp"></a><a href="#section643110419342">isInfoWindowShown</a>()</p>
<p id="p120312362618"><a name="p120312362618"></a><a name="p120312362618"></a>Checks whether an information window is currently displayed for a marker.</p>
</td>
</tr>
<tr id="row14664mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p14666mcpsimp"><a name="p14666mcpsimp"></a><a name="p14666mcpsimp"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p14668mcpsimp"><a name="p14668mcpsimp"></a><a name="p14668mcpsimp"></a><a href="#section2207551183412">isVisible</a>()</p>
<p id="p186510410268"><a name="p186510410268"></a><a name="p186510410268"></a>Checks whether a marker is visible.</p>
</td>
</tr>
<tr id="row14669mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p14671mcpsimp"><a name="p14671mcpsimp"></a><a name="p14671mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p14673mcpsimp"><a name="p14673mcpsimp"></a><a name="p14673mcpsimp"></a><a href="#section6594131123511">remove</a>()</p>
<p id="p20782115202614"><a name="p20782115202614"></a><a name="p20782115202614"></a>Removes a marker from the map.</p>
</td>
</tr>
<tr id="row14674mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p14676mcpsimp"><a name="p14676mcpsimp"></a><a name="p14676mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p14678mcpsimp"><a name="p14678mcpsimp"></a><a name="p14678mcpsimp"></a><a href="#section1776118819353">setAlpha</a>(float alpha)</p>
<p id="p1675236152611"><a name="p1675236152611"></a><a name="p1675236152611"></a>Sets the transparency of a marker.</p>
</td>
</tr>
<tr id="row14679mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p14681mcpsimp"><a name="p14681mcpsimp"></a><a name="p14681mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p14683mcpsimp"><a name="p14683mcpsimp"></a><a name="p14683mcpsimp"></a><a href="#section14156191615354">setAnchor</a>(float anchorU, float anchorV)</p>
<p id="p971615711269"><a name="p971615711269"></a><a name="p971615711269"></a>Sets the anchor point of a marker.</p>
<div class="caution" id="note09921736125511"><a name="note09921736125511"></a><a name="note09921736125511"></a><span class="cautiontitle"> CAUTION: </span><div class="cautionbody"><p id="p899283611556"><a name="p899283611556"></a><a name="p899283611556"></a>This method has been deprecated. To set an anchor point, call <a href="#section992613197119">setMarkerAnchor</a>. </p>
</div></div>
</td>
</tr>
<tr id="row123527111969"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p5353161116615"><a name="p5353161116615"></a><a name="p5353161116615"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p43531411566"><a name="p43531411566"></a><a name="p43531411566"></a><a href="#section138322612114">setAnimation</a>(<a href="animation.md">Animation</a> animation)</p>
<p id="p888716872612"><a name="p888716872612"></a><a name="p888716872612"></a>Sets the animation of a marker.</p>
</td>
</tr>
<tr id="row14684mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p14686mcpsimp"><a name="p14686mcpsimp"></a><a name="p14686mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p14688mcpsimp"><a name="p14688mcpsimp"></a><a name="p14688mcpsimp"></a><a href="#section58671625103515">setDraggable</a>(boolean draggable)</p>
<p id="p10760139162615"><a name="p10760139162615"></a><a name="p10760139162615"></a>Sets whether users can long press a marker and drag it.</p>
</td>
</tr>
<tr id="row14689mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p14691mcpsimp"><a name="p14691mcpsimp"></a><a name="p14691mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p14693mcpsimp"><a name="p14693mcpsimp"></a><a name="p14693mcpsimp"></a><a href="#section1797433173511">setFlat</a>(boolean flat)</p>
<p id="p1769719100267"><a name="p1769719100267"></a><a name="p1769719100267"></a>Sets whether a marker is flatly attached to the map.</p>
</td>
</tr>
<tr id="row14694mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p14696mcpsimp"><a name="p14696mcpsimp"></a><a name="p14696mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p14698mcpsimp"><a name="p14698mcpsimp"></a><a name="p14698mcpsimp"></a><a href="#section1680710531355">setIcon</a>(<a href="bitmapdescriptor.md">BitmapDescriptor </a>iconDescriptor)</p>
<p id="p0196101216263"><a name="p0196101216263"></a><a name="p0196101216263"></a>Sets the icon of a marker.</p>
</td>
</tr>
<tr id="row14699mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p14701mcpsimp"><a name="p14701mcpsimp"></a><a name="p14701mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p14703mcpsimp"><a name="p14703mcpsimp"></a><a name="p14703mcpsimp"></a><a href="#section1858016183620">setInfoWindowAnchor</a>(float anchorU, float anchorV)</p>
<p id="p14385111313268"><a name="p14385111313268"></a><a name="p14385111313268"></a>Sets the anchor point of a marker's information window. The coordinate system used is the same as that of the anchor point of a marker. By default, the top-middle point of the marker image is used as the anchor point.</p>
</td>
</tr>
<tr id="row1810414251193"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p954343512229"><a name="p954343512229"></a><a name="p954343512229"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p1054453516229"><a name="p1054453516229"></a><a name="p1054453516229"></a><a href="#section992613197119">setMarkerAnchor</a>(float anchorU, float anchorV)</p>
<p id="p20386111452613"><a name="p20386111452613"></a><a name="p20386111452613"></a>Sets the anchor point of a marker.</p>
</td>
</tr>
<tr id="row14704mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p14706mcpsimp"><a name="p14706mcpsimp"></a><a name="p14706mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p14708mcpsimp"><a name="p14708mcpsimp"></a><a name="p14708mcpsimp"></a><a href="#section13917151362">setPosition</a>(<a href="latlng.md">LatLng</a> latLng)</p>
<p id="p1751471572611"><a name="p1751471572611"></a><a name="p1751471572611"></a>Sets the position coordinates of a marker.</p>
</td>
</tr>
<tr id="row14709mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p14711mcpsimp"><a name="p14711mcpsimp"></a><a name="p14711mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p14713mcpsimp"><a name="p14713mcpsimp"></a><a name="p14713mcpsimp"></a><a href="#section1989919222361">setRotation</a>(float rotation)</p>
<p id="p85211916152619"><a name="p85211916152619"></a><a name="p85211916152619"></a>Sets the rotation angle of a marker, that is, the angle in which the marker rotates around the anchor point clockwise. The rotation axis is perpendicular to the marker. </p>
</td>
</tr>
<tr id="row14714mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p14716mcpsimp"><a name="p14716mcpsimp"></a><a name="p14716mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p14718mcpsimp"><a name="p14718mcpsimp"></a><a name="p14718mcpsimp"></a><a href="#section165927340363">setSnippet</a>(String snippet)</p>
<p id="p1886851792615"><a name="p1886851792615"></a><a name="p1886851792615"></a>Sets the text snippet of a marker. If <strong id="b179141311112312"><a name="b179141311112312"></a><a name="b179141311112312"></a>null</strong> is passed, the existing text snippet will be cleared.</p>
</td>
</tr>
<tr id="row14719mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p14721mcpsimp"><a name="p14721mcpsimp"></a><a name="p14721mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p14723mcpsimp"><a name="p14723mcpsimp"></a><a name="p14723mcpsimp"></a><a href="#section893234843611">setTag</a>(Object tag)</p>
<p id="p9926718172611"><a name="p9926718172611"></a><a name="p9926718172611"></a>Sets the <strong id="b1491417451233"><a name="b1491417451233"></a><a name="b1491417451233"></a>tag</strong> attribute of a marker. If <strong id="b177513505236"><a name="b177513505236"></a><a name="b177513505236"></a>null</strong> is passed, the <strong id="b179769525232"><a name="b179769525232"></a><a name="b179769525232"></a>tag</strong> attribute will be cleared.</p>
</td>
</tr>
<tr id="row14724mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p14726mcpsimp"><a name="p14726mcpsimp"></a><a name="p14726mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p14728mcpsimp"><a name="p14728mcpsimp"></a><a name="p14728mcpsimp"></a><a href="#section13963185519361">setTitle</a>(String title)</p>
<p id="p1690921922613"><a name="p1690921922613"></a><a name="p1690921922613"></a>Sets the title of a marker. By default, the title is empty.</p>
</td>
</tr>
<tr id="row14729mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p14731mcpsimp"><a name="p14731mcpsimp"></a><a name="p14731mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p14733mcpsimp"><a name="p14733mcpsimp"></a><a name="p14733mcpsimp"></a><a href="#section1775916212376">setVisible</a>(boolean visible)</p>
<p id="p1871216205268"><a name="p1871216205268"></a><a name="p1871216205268"></a>Sets whether a marker is visible.</p>
</td>
</tr>
<tr id="row14734mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p14736mcpsimp"><a name="p14736mcpsimp"></a><a name="p14736mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p14738mcpsimp"><a name="p14738mcpsimp"></a><a name="p14738mcpsimp"></a><a href="#section952413920376">setZIndex</a>(float zIndex)</p>
<p id="p1266310217269"><a name="p1266310217269"></a><a name="p1266310217269"></a>Sets the z-index of a marker.</p>
</td>
</tr>
<tr id="row14739mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p14741mcpsimp"><a name="p14741mcpsimp"></a><a name="p14741mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p14743mcpsimp"><a name="p14743mcpsimp"></a><a name="p14743mcpsimp"></a><a href="#section13223817123711">showInfoWindow</a>()</p>
<p id="p6674112213261"><a name="p6674112213261"></a><a name="p6674112213261"></a>Displays the information window for a marker.</p>
</td>
</tr>
<tr id="row19417124219719"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p174190197816"><a name="p174190197816"></a><a name="p174190197816"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p1441818421379"><a name="p1441818421379"></a><a name="p1441818421379"></a><a href="#section13557451287">startAnimation</a>()</p>
<p id="p137221523202615"><a name="p137221523202615"></a><a name="p137221523202615"></a>Starts the animation of a marker.</p>
</td>
</tr>
</tbody>
</table>

## Public Methods<a name="section166797915511"></a>

## equals<a name="section9995901416"></a>

<a name="table14746mcpsimp"></a>
<table><thead align="left"><tr id="row14750mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p14752mcpsimp"><a name="p14752mcpsimp"></a><a name="p14752mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row14753mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p14755mcpsimp"><a name="p14755mcpsimp"></a><a name="p14755mcpsimp"></a>public boolean equals(Object other)</p>
<p id="p1599420174915"><a name="p1599420174915"></a><a name="p1599420174915"></a>Checks whether a marker object equals another.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table14761mcpsimp"></a>
<table><thead align="left"><tr id="row14766mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p14768mcpsimp"><a name="p14768mcpsimp"></a><a name="p14768mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p14770mcpsimp"><a name="p14770mcpsimp"></a><a name="p14770mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row14771mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p14773mcpsimp"><a name="p14773mcpsimp"></a><a name="p14773mcpsimp"></a>other</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p14775mcpsimp"><a name="p14775mcpsimp"></a><a name="p14775mcpsimp"></a>Another object to be compared.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table14778mcpsimp"></a>
<table><thead align="left"><tr id="row14783mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p14785mcpsimp"><a name="p14785mcpsimp"></a><a name="p14785mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p14787mcpsimp"><a name="p14787mcpsimp"></a><a name="p14787mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row14788mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p14790mcpsimp"><a name="p14790mcpsimp"></a><a name="p14790mcpsimp"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p14792mcpsimp"><a name="p14792mcpsimp"></a><a name="p14792mcpsimp"></a><strong id="b167761022145918"><a name="b167761022145918"></a><a name="b167761022145918"></a>true</strong> if the marker objects are equal; <strong id="b19313102005917"><a name="b19313102005917"></a><a name="b19313102005917"></a>false</strong> otherwise.</p>
</td>
</tr>
</tbody>
</table>

## getAlpha<a name="section19252111810145"></a>

<a name="table14794mcpsimp"></a>
<table><thead align="left"><tr id="row14798mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p14800mcpsimp"><a name="p14800mcpsimp"></a><a name="p14800mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row14801mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p14803mcpsimp"><a name="p14803mcpsimp"></a><a name="p14803mcpsimp"></a>public float getAlpha()</p>
<p id="p57331210154914"><a name="p57331210154914"></a><a name="p57331210154914"></a>Obtains the transparency of a marker.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table14812mcpsimp"></a>
<table><thead align="left"><tr id="row14817mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p14819mcpsimp"><a name="p14819mcpsimp"></a><a name="p14819mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p14821mcpsimp"><a name="p14821mcpsimp"></a><a name="p14821mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row14822mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p14824mcpsimp"><a name="p14824mcpsimp"></a><a name="p14824mcpsimp"></a>float</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p14826mcpsimp"><a name="p14826mcpsimp"></a><a name="p14826mcpsimp"></a>Transparency of a marker. The value ranges from 0 to 1.</p>
</td>
</tr>
</tbody>
</table>

## getId<a name="section105771527101411"></a>

<a name="table14828mcpsimp"></a>
<table><thead align="left"><tr id="row14832mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p14834mcpsimp"><a name="p14834mcpsimp"></a><a name="p14834mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row14835mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p14837mcpsimp"><a name="p14837mcpsimp"></a><a name="p14837mcpsimp"></a>public final String getId()</p>
<p id="p14840mcpsimp"><a name="p14840mcpsimp"></a><a name="p14840mcpsimp"></a>Obtains the ID of a marker on a map. The ID will be unique among all markers on the map.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table14846mcpsimp"></a>
<table><thead align="left"><tr id="row14851mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p14853mcpsimp"><a name="p14853mcpsimp"></a><a name="p14853mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p14855mcpsimp"><a name="p14855mcpsimp"></a><a name="p14855mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row14856mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p14858mcpsimp"><a name="p14858mcpsimp"></a><a name="p14858mcpsimp"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p14860mcpsimp"><a name="p14860mcpsimp"></a><a name="p14860mcpsimp"></a>ID of a marker.</p>
</td>
</tr>
</tbody>
</table>

## getPosition<a name="section49343761418"></a>

<a name="table14862mcpsimp"></a>
<table><thead align="left"><tr id="row14866mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p14868mcpsimp"><a name="p14868mcpsimp"></a><a name="p14868mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row14869mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p14871mcpsimp"><a name="p14871mcpsimp"></a><a name="p14871mcpsimp"></a>public final <a href="latlng.md">LatLng</a> getPosition()</p>
<p id="p1538316283490"><a name="p1538316283490"></a><a name="p1538316283490"></a>Obtains the position of a marker.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table14880mcpsimp"></a>
<table><thead align="left"><tr id="row14885mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p14887mcpsimp"><a name="p14887mcpsimp"></a><a name="p14887mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p14889mcpsimp"><a name="p14889mcpsimp"></a><a name="p14889mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row14890mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p14892mcpsimp"><a name="p14892mcpsimp"></a><a name="p14892mcpsimp"></a><a href="latlng.md">LatLng</a></p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p14894mcpsimp"><a name="p14894mcpsimp"></a><a name="p14894mcpsimp"></a>Marker position.</p>
</td>
</tr>
</tbody>
</table>

## getRotation<a name="section26741745121414"></a>

<a name="table14896mcpsimp"></a>
<table><thead align="left"><tr id="row14900mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p14902mcpsimp"><a name="p14902mcpsimp"></a><a name="p14902mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row14903mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p14905mcpsimp"><a name="p14905mcpsimp"></a><a name="p14905mcpsimp"></a>public final float getRotation()</p>
<p id="p31331635134914"><a name="p31331635134914"></a><a name="p31331635134914"></a>Obtains the rotation angle of a marker.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table14914mcpsimp"></a>
<table><thead align="left"><tr id="row14919mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p14921mcpsimp"><a name="p14921mcpsimp"></a><a name="p14921mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p14923mcpsimp"><a name="p14923mcpsimp"></a><a name="p14923mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row14924mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p14926mcpsimp"><a name="p14926mcpsimp"></a><a name="p14926mcpsimp"></a>float</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p14928mcpsimp"><a name="p14928mcpsimp"></a><a name="p14928mcpsimp"></a>Rotation angle of a marker.</p>
</td>
</tr>
</tbody>
</table>

## getSnippet<a name="section7851155271416"></a>

<a name="table14930mcpsimp"></a>
<table><thead align="left"><tr id="row14934mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p14936mcpsimp"><a name="p14936mcpsimp"></a><a name="p14936mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row14937mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p14939mcpsimp"><a name="p14939mcpsimp"></a><a name="p14939mcpsimp"></a>public final String getSnippet()</p>
<p id="p14942mcpsimp"><a name="p14942mcpsimp"></a><a name="p14942mcpsimp"></a>Obtains the text snippet of a marker.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table14948mcpsimp"></a>
<table><thead align="left"><tr id="row14953mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p14955mcpsimp"><a name="p14955mcpsimp"></a><a name="p14955mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p14957mcpsimp"><a name="p14957mcpsimp"></a><a name="p14957mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row14958mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p14960mcpsimp"><a name="p14960mcpsimp"></a><a name="p14960mcpsimp"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p14962mcpsimp"><a name="p14962mcpsimp"></a><a name="p14962mcpsimp"></a>Text snippet of a marker.</p>
</td>
</tr>
</tbody>
</table>

## getTag<a name="section1625517241520"></a>

<a name="table14964mcpsimp"></a>
<table><thead align="left"><tr id="row14968mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p14970mcpsimp"><a name="p14970mcpsimp"></a><a name="p14970mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row14971mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p14973mcpsimp"><a name="p14973mcpsimp"></a><a name="p14973mcpsimp"></a>public Object getTag()</p>
<p id="p3192144910492"><a name="p3192144910492"></a><a name="p3192144910492"></a>Obtains the <strong id="b162545214158"><a name="b162545214158"></a><a name="b162545214158"></a>tag</strong> attribute (if it has been set) of a marker. </p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table14982mcpsimp"></a>
<table><thead align="left"><tr id="row14987mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p14989mcpsimp"><a name="p14989mcpsimp"></a><a name="p14989mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p14991mcpsimp"><a name="p14991mcpsimp"></a><a name="p14991mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row14992mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p14994mcpsimp"><a name="p14994mcpsimp"></a><a name="p14994mcpsimp"></a>Object</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p14996mcpsimp"><a name="p14996mcpsimp"></a><a name="p14996mcpsimp"></a><strong id="b159116589211"><a name="b159116589211"></a><a name="b159116589211"></a>Object</strong> if a tag has been set; <strong id="b77785151313"><a name="b77785151313"></a><a name="b77785151313"></a>null</strong> otherwise.</p>
</td>
</tr>
</tbody>
</table>

## getTitle<a name="section15178141116154"></a>

<a name="table14998mcpsimp"></a>
<table><thead align="left"><tr id="row15002mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p15004mcpsimp"><a name="p15004mcpsimp"></a><a name="p15004mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row15005mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p15007mcpsimp"><a name="p15007mcpsimp"></a><a name="p15007mcpsimp"></a>public final String getTitle()</p>
<p id="p6458141045014"><a name="p6458141045014"></a><a name="p6458141045014"></a>Obtains the title of a marker.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table15016mcpsimp"></a>
<table><thead align="left"><tr id="row15021mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p15023mcpsimp"><a name="p15023mcpsimp"></a><a name="p15023mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p15025mcpsimp"><a name="p15025mcpsimp"></a><a name="p15025mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row15026mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p15028mcpsimp"><a name="p15028mcpsimp"></a><a name="p15028mcpsimp"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p15030mcpsimp"><a name="p15030mcpsimp"></a><a name="p15030mcpsimp"></a>Title string of a marker.</p>
</td>
</tr>
</tbody>
</table>

## getZIndex<a name="section381418141514"></a>

<a name="table15032mcpsimp"></a>
<table><thead align="left"><tr id="row15036mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p15038mcpsimp"><a name="p15038mcpsimp"></a><a name="p15038mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row15039mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p15041mcpsimp"><a name="p15041mcpsimp"></a><a name="p15041mcpsimp"></a>public float getZIndex()</p>
<p id="p516541812508"><a name="p516541812508"></a><a name="p516541812508"></a>Obtains the z-index of a marker.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table15050mcpsimp"></a>
<table><thead align="left"><tr id="row15055mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p15057mcpsimp"><a name="p15057mcpsimp"></a><a name="p15057mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p15059mcpsimp"><a name="p15059mcpsimp"></a><a name="p15059mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row15060mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p15062mcpsimp"><a name="p15062mcpsimp"></a><a name="p15062mcpsimp"></a>float</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p15064mcpsimp"><a name="p15064mcpsimp"></a><a name="p15064mcpsimp"></a>Z-index, which indicates the overlapping order of a marker.</p>
</td>
</tr>
</tbody>
</table>

## hashCode<a name="section075815268151"></a>

<a name="table15066mcpsimp"></a>
<table><thead align="left"><tr id="row15070mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p15072mcpsimp"><a name="p15072mcpsimp"></a><a name="p15072mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row15073mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p15075mcpsimp"><a name="p15075mcpsimp"></a><a name="p15075mcpsimp"></a>public int hashCode()</p>
<p id="p159418102437"><a name="p159418102437"></a><a name="p159418102437"></a>Obtains the hash value of a marker.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table15084mcpsimp"></a>
<table><thead align="left"><tr id="row15089mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p15091mcpsimp"><a name="p15091mcpsimp"></a><a name="p15091mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p15093mcpsimp"><a name="p15093mcpsimp"></a><a name="p15093mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row15094mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p15096mcpsimp"><a name="p15096mcpsimp"></a><a name="p15096mcpsimp"></a>int</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p15098mcpsimp"><a name="p15098mcpsimp"></a><a name="p15098mcpsimp"></a>Hash value of a marker.</p>
</td>
</tr>
</tbody>
</table>

## hideInfoWindow<a name="section352393481515"></a>

<a name="table15100mcpsimp"></a>
<table><thead align="left"><tr id="row15104mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p15106mcpsimp"><a name="p15106mcpsimp"></a><a name="p15106mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row15107mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p15109mcpsimp"><a name="p15109mcpsimp"></a><a name="p15109mcpsimp"></a>public final void hideInfoWindow()</p>
<p id="p198009220432"><a name="p198009220432"></a><a name="p198009220432"></a>Hides the information window that is displayed for a marker. This method is invalid for invisible markers.</p>
</td>
</tr>
</tbody>
</table>

## isClusterable<a name="section12103164219159"></a>

<a name="table15120mcpsimp"></a>
<table><thead align="left"><tr id="row15124mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p15126mcpsimp"><a name="p15126mcpsimp"></a><a name="p15126mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row15127mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p15129mcpsimp"><a name="p15129mcpsimp"></a><a name="p15129mcpsimp"></a>public boolean isClusterable()</p>
<p id="p674523116438"><a name="p674523116438"></a><a name="p674523116438"></a>Checks whether a marker can be clustered.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table15138mcpsimp"></a>
<table><thead align="left"><tr id="row15143mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p15145mcpsimp"><a name="p15145mcpsimp"></a><a name="p15145mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p15147mcpsimp"><a name="p15147mcpsimp"></a><a name="p15147mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row15148mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p15150mcpsimp"><a name="p15150mcpsimp"></a><a name="p15150mcpsimp"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p15152mcpsimp"><a name="p15152mcpsimp"></a><a name="p15152mcpsimp"></a><strong id="b58701741357"><a name="b58701741357"></a><a name="b58701741357"></a>true</strong> if the marker can be clustered; <strong id="b1819616915516"><a name="b1819616915516"></a><a name="b1819616915516"></a>false</strong> otherwise.</p>
</td>
</tr>
</tbody>
</table>

## isDraggable<a name="section1947358193318"></a>

<a name="table15154mcpsimp"></a>
<table><thead align="left"><tr id="row15158mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p15160mcpsimp"><a name="p15160mcpsimp"></a><a name="p15160mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row15161mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p15163mcpsimp"><a name="p15163mcpsimp"></a><a name="p15163mcpsimp"></a>public final boolean isDraggable()</p>
<p id="p1830744914435"><a name="p1830744914435"></a><a name="p1830744914435"></a>Checks whether users can long press a marker and drag it.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table15172mcpsimp"></a>
<table><thead align="left"><tr id="row15177mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p15179mcpsimp"><a name="p15179mcpsimp"></a><a name="p15179mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p15181mcpsimp"><a name="p15181mcpsimp"></a><a name="p15181mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row15182mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p15184mcpsimp"><a name="p15184mcpsimp"></a><a name="p15184mcpsimp"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p15186mcpsimp"><a name="p15186mcpsimp"></a><a name="p15186mcpsimp"></a><strong id="b20691124859"><a name="b20691124859"></a><a name="b20691124859"></a>true</strong> if users can long press a marker and drag it; <strong id="b16698124252"><a name="b16698124252"></a><a name="b16698124252"></a>false</strong> otherwise.</p>
</td>
</tr>
</tbody>
</table>

## isFlat<a name="section16358133310341"></a>

<a name="table15188mcpsimp"></a>
<table><thead align="left"><tr id="row15192mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p15194mcpsimp"><a name="p15194mcpsimp"></a><a name="p15194mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row15195mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p15197mcpsimp"><a name="p15197mcpsimp"></a><a name="p15197mcpsimp"></a>public final boolean isFlat()</p>
<p id="p167018724417"><a name="p167018724417"></a><a name="p167018724417"></a>Checks whether a marker is flatly attached to the map.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table15206mcpsimp"></a>
<table><thead align="left"><tr id="row15211mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p15213mcpsimp"><a name="p15213mcpsimp"></a><a name="p15213mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p15215mcpsimp"><a name="p15215mcpsimp"></a><a name="p15215mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row15216mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p15218mcpsimp"><a name="p15218mcpsimp"></a><a name="p15218mcpsimp"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p15220mcpsimp"><a name="p15220mcpsimp"></a><a name="p15220mcpsimp"></a><strong id="b1435753953"><a name="b1435753953"></a><a name="b1435753953"></a>true</strong> if a marker is flatly attached to the map; <strong id="b44315531652"><a name="b44315531652"></a><a name="b44315531652"></a>false</strong> otherwise.</p>
</td>
</tr>
</tbody>
</table>

## isInfoWindowShown<a name="section643110419342"></a>

<a name="table15222mcpsimp"></a>
<table><thead align="left"><tr id="row15226mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p15228mcpsimp"><a name="p15228mcpsimp"></a><a name="p15228mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row15229mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p15231mcpsimp"><a name="p15231mcpsimp"></a><a name="p15231mcpsimp"></a>public final boolean isInfoWindowShown()</p>
<p id="p2140182544411"><a name="p2140182544411"></a><a name="p2140182544411"></a>Checks whether an information window is currently displayed for a marker. This method will not consider whether the information window is actually visible on the screen.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table15240mcpsimp"></a>
<table><thead align="left"><tr id="row15245mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p15247mcpsimp"><a name="p15247mcpsimp"></a><a name="p15247mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p15249mcpsimp"><a name="p15249mcpsimp"></a><a name="p15249mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row15250mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p15252mcpsimp"><a name="p15252mcpsimp"></a><a name="p15252mcpsimp"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p15254mcpsimp"><a name="p15254mcpsimp"></a><a name="p15254mcpsimp"></a><strong id="b1999684315719"><a name="b1999684315719"></a><a name="b1999684315719"></a>true</strong> if an information window is currently displayed; <strong id="b184612027969"><a name="b184612027969"></a><a name="b184612027969"></a>false</strong> otherwise.</p>
</td>
</tr>
</tbody>
</table>

## isVisible<a name="section2207551183412"></a>

<a name="table15256mcpsimp"></a>
<table><thead align="left"><tr id="row15260mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p15262mcpsimp"><a name="p15262mcpsimp"></a><a name="p15262mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row15263mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p15265mcpsimp"><a name="p15265mcpsimp"></a><a name="p15265mcpsimp"></a>public final boolean isVisible()</p>
<p id="p1018544317447"><a name="p1018544317447"></a><a name="p1018544317447"></a>Checks whether a marker is visible.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table15274mcpsimp"></a>
<table><thead align="left"><tr id="row15279mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p15281mcpsimp"><a name="p15281mcpsimp"></a><a name="p15281mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p15283mcpsimp"><a name="p15283mcpsimp"></a><a name="p15283mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row15284mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p15286mcpsimp"><a name="p15286mcpsimp"></a><a name="p15286mcpsimp"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p15288mcpsimp"><a name="p15288mcpsimp"></a><a name="p15288mcpsimp"></a><strong id="b211715129819"><a name="b211715129819"></a><a name="b211715129819"></a>true</strong> if the marker is visible; <strong id="b5574666816"><a name="b5574666816"></a><a name="b5574666816"></a>false</strong> otherwise.</p>
</td>
</tr>
</tbody>
</table>

## remove<a name="section6594131123511"></a>

<a name="table15290mcpsimp"></a>
<table><thead align="left"><tr id="row15294mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p15296mcpsimp"><a name="p15296mcpsimp"></a><a name="p15296mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row15297mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p15299mcpsimp"><a name="p15299mcpsimp"></a><a name="p15299mcpsimp"></a>public final void remove()</p>
<p id="p13301784457"><a name="p13301784457"></a><a name="p13301784457"></a>Removes a marker from the map.</p>
</td>
</tr>
</tbody>
</table>

## setAlpha<a name="section1776118819353"></a>

<a name="table15310mcpsimp"></a>
<table><thead align="left"><tr id="row15314mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p15316mcpsimp"><a name="p15316mcpsimp"></a><a name="p15316mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row15317mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p15319mcpsimp"><a name="p15319mcpsimp"></a><a name="p15319mcpsimp"></a>public final void setAlpha(float alpha)</p>
<p id="p2225231450"><a name="p2225231450"></a><a name="p2225231450"></a>Sets the transparency of a marker.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table15325mcpsimp"></a>
<table><thead align="left"><tr id="row15330mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p15332mcpsimp"><a name="p15332mcpsimp"></a><a name="p15332mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p15334mcpsimp"><a name="p15334mcpsimp"></a><a name="p15334mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row15335mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p15337mcpsimp"><a name="p15337mcpsimp"></a><a name="p15337mcpsimp"></a>alpha</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p15339mcpsimp"><a name="p15339mcpsimp"></a><a name="p15339mcpsimp"></a>Transparency of a marker. The value ranges from 0 (completely transparent) to 1 (completely opaque). The default value is <strong id="b13342746820"><a name="b13342746820"></a><a name="b13342746820"></a>1</strong>.</p>
</td>
</tr>
</tbody>
</table>

## setAnchor<a name="section14156191615354"></a>

>![](public_sys-resources/icon-caution.gif) **CAUTION:** 
>This method has been deprecated. To set an anchor point, call  [setMarkerAnchor](#section992613197119). 

<a name="table15344mcpsimp"></a>
<table><thead align="left"><tr id="row15348mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p15350mcpsimp"><a name="p15350mcpsimp"></a><a name="p15350mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row15351mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p15353mcpsimp"><a name="p15353mcpsimp"></a><a name="p15353mcpsimp"></a>public final void setAnchor(float anchorU, float anchorV)</p>
<p id="p15356mcpsimp"><a name="p15356mcpsimp"></a><a name="p15356mcpsimp"></a>Sets the anchor point of a marker. Since of the values of <strong id="b6392122211255"><a name="b6392122211255"></a><a name="b6392122211255"></a>U</strong> and <strong id="b189211723122515"><a name="b189211723122515"></a><a name="b189211723122515"></a>V</strong> are fixed, this method always sets the anchor point to the bottom of the marker icon. </p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table15360mcpsimp"></a>
<table><thead align="left"><tr id="row15365mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p15367mcpsimp"><a name="p15367mcpsimp"></a><a name="p15367mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p15369mcpsimp"><a name="p15369mcpsimp"></a><a name="p15369mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row15370mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p15372mcpsimp"><a name="p15372mcpsimp"></a><a name="p15372mcpsimp"></a>anchorU</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p15374mcpsimp"><a name="p15374mcpsimp"></a><a name="p15374mcpsimp"></a>Horizontal coordinate of the anchor point of a marker. The value range is [0,1], expressed in a proportion of the marker image width. The default value is <strong id="b1754616481216"><a name="b1754616481216"></a><a name="b1754616481216"></a>0.5</strong>.</p>
</td>
</tr>
<tr id="row15375mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p15377mcpsimp"><a name="p15377mcpsimp"></a><a name="p15377mcpsimp"></a>anchorV</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p15379mcpsimp"><a name="p15379mcpsimp"></a><a name="p15379mcpsimp"></a>Vertical coordinate of the anchor point of a marker. The value range is [0,1], expressed in a proportion of the marker image height. The default value is <strong id="b1254524920213"><a name="b1254524920213"></a><a name="b1254524920213"></a>0.5</strong>.</p>
</td>
</tr>
</tbody>
</table>

## setAnimation<a name="section138322612114"></a>

<a name="table4841526121111"></a>
<table><thead align="left"><tr id="row198442631112"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p16841262115"><a name="p16841262115"></a><a name="p16841262115"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row884172671117"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p126501344141118"><a name="p126501344141118"></a><a name="p126501344141118"></a>public void setAnimation(Animation animation)</p>
<p id="p78422691117"><a name="p78422691117"></a><a name="p78422691117"></a>Sets the animation of a marker.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table18412611117"></a>
<table><thead align="left"><tr id="row1985126101115"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p16850264112"><a name="p16850264112"></a><a name="p16850264112"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p1285162661113"><a name="p1285162661113"></a><a name="p1285162661113"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row385182661117"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p17854266114"><a name="p17854266114"></a><a name="p17854266114"></a>animation</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p1385826141119"><a name="p1385826141119"></a><a name="p1385826141119"></a>Animation.</p>
</td>
</tr>
</tbody>
</table>

## setDraggable<a name="section58671625103515"></a>

<a name="table15384mcpsimp"></a>
<table><thead align="left"><tr id="row15388mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p15390mcpsimp"><a name="p15390mcpsimp"></a><a name="p15390mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row15391mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p15393mcpsimp"><a name="p15393mcpsimp"></a><a name="p15393mcpsimp"></a>public final void setDraggable(boolean draggable)</p>
<p id="p2082495395019"><a name="p2082495395019"></a><a name="p2082495395019"></a>Sets whether users can long press a marker and drag it.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table15399mcpsimp"></a>
<table><thead align="left"><tr id="row15404mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p15406mcpsimp"><a name="p15406mcpsimp"></a><a name="p15406mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p15408mcpsimp"><a name="p15408mcpsimp"></a><a name="p15408mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row15409mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p15411mcpsimp"><a name="p15411mcpsimp"></a><a name="p15411mcpsimp"></a>draggable</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p15413mcpsimp"><a name="p15413mcpsimp"></a><a name="p15413mcpsimp"></a>Indicates whether users can long press a marker and drag it. <strong id="b117805205175"><a name="b117805205175"></a><a name="b117805205175"></a>true</strong>: yes; <strong id="b127924204177"><a name="b127924204177"></a><a name="b127924204177"></a>false</strong>: no. The default value is <strong id="b63381750628"><a name="b63381750628"></a><a name="b63381750628"></a>false</strong>.</p>
</td>
</tr>
</tbody>
</table>

## setFlat<a name="section1797433173511"></a>

<a name="table15418mcpsimp"></a>
<table><thead align="left"><tr id="row15422mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p15424mcpsimp"><a name="p15424mcpsimp"></a><a name="p15424mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row15425mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p15427mcpsimp"><a name="p15427mcpsimp"></a><a name="p15427mcpsimp"></a>public final void setFlat(boolean flat)</p>
<p id="p795411064615"><a name="p795411064615"></a><a name="p795411064615"></a>Sets whether to flatly attach a marker to the map. If the marker is flatly attached to the map, it will stay on the map when the camera rotates or tilts. Different from a <a href="groundoverlay.md">ground overlay</a>, the marker will remain the same size when the camera zooms in or out. If the marker faces the camera, it will always be drawn facing the camera and rotates or tilts with the camera.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table15433mcpsimp"></a>
<table><thead align="left"><tr id="row15438mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p15440mcpsimp"><a name="p15440mcpsimp"></a><a name="p15440mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p15442mcpsimp"><a name="p15442mcpsimp"></a><a name="p15442mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row15443mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p15445mcpsimp"><a name="p15445mcpsimp"></a><a name="p15445mcpsimp"></a>flat</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p15447mcpsimp"><a name="p15447mcpsimp"></a><a name="p15447mcpsimp"></a>Indicates whether to flatly attach a marker to the map. <strong id="b15204955122010"><a name="b15204955122010"></a><a name="b15204955122010"></a>true</strong>: yes; <strong id="b1383819574209"><a name="b1383819574209"></a><a name="b1383819574209"></a>false</strong> (default): no.</p>
</td>
</tr>
</tbody>
</table>

## setIcon<a name="section1680710531355"></a>

<a name="table15452mcpsimp"></a>
<table><thead align="left"><tr id="row15456mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p15458mcpsimp"><a name="p15458mcpsimp"></a><a name="p15458mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row15459mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p15461mcpsimp"><a name="p15461mcpsimp"></a><a name="p15461mcpsimp"></a>public final void setIcon(<a href="bitmapdescriptor.md">BitmapDescriptor</a> iconDescriptor)</p>
<p id="p136547280466"><a name="p136547280466"></a><a name="p136547280466"></a>Sets the icon of a marker. If <strong id="b62688513211"><a name="b62688513211"></a><a name="b62688513211"></a>null</strong> is passed, the default marker will be used.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table15467mcpsimp"></a>
<table><thead align="left"><tr id="row15472mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p15474mcpsimp"><a name="p15474mcpsimp"></a><a name="p15474mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p15476mcpsimp"><a name="p15476mcpsimp"></a><a name="p15476mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row15477mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p15479mcpsimp"><a name="p15479mcpsimp"></a><a name="p15479mcpsimp"></a>iconDescriptor</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p15481mcpsimp"><a name="p15481mcpsimp"></a><a name="p15481mcpsimp"></a>Object containing an icon.</p>
</td>
</tr>
</tbody>
</table>

## setInfoWindowAnchor<a name="section1858016183620"></a>

<a name="table15486mcpsimp"></a>
<table><thead align="left"><tr id="row15490mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p15492mcpsimp"><a name="p15492mcpsimp"></a><a name="p15492mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row15493mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p15495mcpsimp"><a name="p15495mcpsimp"></a><a name="p15495mcpsimp"></a>public final void setInfoWindowAnchor(float anchorU, float anchorV)</p>
<p id="p15498mcpsimp"><a name="p15498mcpsimp"></a><a name="p15498mcpsimp"></a>Sets the anchor point of a marker's information window. The coordinate system used is the same as that of the anchor point of a marker. By default, the top-middle point of the marker image is used as the anchor point. For details, please refer to <a href="#section992613197119">setMarkerAnchor</a><strong id="b6190146122514"><a name="b6190146122514"></a><a name="b6190146122514"></a>(float anchorU, float anchorV)</strong>.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table15501mcpsimp"></a>
<table><thead align="left"><tr id="row15506mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p15508mcpsimp"><a name="p15508mcpsimp"></a><a name="p15508mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p15510mcpsimp"><a name="p15510mcpsimp"></a><a name="p15510mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row15511mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p15513mcpsimp"><a name="p15513mcpsimp"></a><a name="p15513mcpsimp"></a>anchorU</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p15515mcpsimp"><a name="p15515mcpsimp"></a><a name="p15515mcpsimp"></a>Horizontal coordinate of the anchor point of an information window. The recommended value range is [0,1], expressed in a proportion of the information window width. </p>
</td>
</tr>
<tr id="row15516mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p15518mcpsimp"><a name="p15518mcpsimp"></a><a name="p15518mcpsimp"></a>anchorV</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p15520mcpsimp"><a name="p15520mcpsimp"></a><a name="p15520mcpsimp"></a>Vertical coordinate of the anchor point of an information window. The recommended value range is [0,1], expressed in a proportion of the information window height. </p>
</td>
</tr>
</tbody>
</table>

## setMarkerAnchor<a name="section992613197119"></a>

<a name="table1477485210247"></a>
<table><thead align="left"><tr id="row1677485213249"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p177475262414"><a name="p177475262414"></a><a name="p177475262414"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row1877455212247"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p86881529102512"><a name="p86881529102512"></a><a name="p86881529102512"></a>public final void setMarkerAnchor(float anchorU, float anchorV)</p>
<p id="p10775155232417"><a name="p10775155232417"></a><a name="p10775155232417"></a>Sets the anchor point of a marker. The anchor point is used to anchor a marker image to the map. The coordinates (0, 0), (1, 0), (0, 1), and (1, 1) respectively indicate the top-left, top-right, bottom-left, and bottom-right corners of the marker image. The following figure shows a marker's anchor point X whose coordinates are (0.5, 0.3).</p>
<p id="p17999174213388"><a name="p17999174213388"></a><a name="p17999174213388"></a><a name="image1999042173816"></a><a name="image1999042173816"></a><span><img id="image1999042173816" src="figures/anchor.png" height="278.160057" width="399"></span></p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table11775152152412"></a>
<table><thead align="left"><tr id="row16775155212247"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p1177575219249"><a name="p1177575219249"></a><a name="p1177575219249"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p077585292415"><a name="p077585292415"></a><a name="p077585292415"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row1577605282418"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p1776195222411"><a name="p1776195222411"></a><a name="p1776195222411"></a>anchorU</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p177619521245"><a name="p177619521245"></a><a name="p177619521245"></a>Horizontal coordinate of the anchor point of a marker. The recommended value range is [0,1], expressed in a proportion of the marker image width. The default value is <strong id="b869453244219"><a name="b869453244219"></a><a name="b869453244219"></a>0.5</strong>.</p>
</td>
</tr>
<tr id="row1177665210241"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p57766529244"><a name="p57766529244"></a><a name="p57766529244"></a>anchorV</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p0776165272414"><a name="p0776165272414"></a><a name="p0776165272414"></a>Vertical coordinate of the anchor point of a marker. The recommended value range is [0,1], expressed in a proportion of the marker image height. The default value is <strong id="b107461744174211"><a name="b107461744174211"></a><a name="b107461744174211"></a>1</strong>.</p>
</td>
</tr>
</tbody>
</table>

## setPosition<a name="section13917151362"></a>

<a name="table15525mcpsimp"></a>
<table><thead align="left"><tr id="row15529mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p15531mcpsimp"><a name="p15531mcpsimp"></a><a name="p15531mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row15532mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p15534mcpsimp"><a name="p15534mcpsimp"></a><a name="p15534mcpsimp"></a>public final void setPosition(<a href="latlng.md">LatLng</a> latLng)</p>
<p id="p186741514"><a name="p186741514"></a><a name="p186741514"></a>Sets the position coordinates of a marker.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table15540mcpsimp"></a>
<table><thead align="left"><tr id="row15545mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p15547mcpsimp"><a name="p15547mcpsimp"></a><a name="p15547mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p15549mcpsimp"><a name="p15549mcpsimp"></a><a name="p15549mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row15550mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p15552mcpsimp"><a name="p15552mcpsimp"></a><a name="p15552mcpsimp"></a>latLng</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p15554mcpsimp"><a name="p15554mcpsimp"></a><a name="p15554mcpsimp"></a>Position coordinates of a marker.</p>
</td>
</tr>
</tbody>
</table>

**Throws**

<a name="table14799844195319"></a>
<table><thead align="left"><tr id="row1799124416534"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p979964418530"><a name="p979964418530"></a><a name="p979964418530"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p147991444155318"><a name="p147991444155318"></a><a name="p147991444155318"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row1880024412533"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p28001844115317"><a name="p28001844115317"></a><a name="p28001844115317"></a>IllegalArgumentException</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p1980010447535"><a name="p1980010447535"></a><a name="p1980010447535"></a>If the passed <strong id="b11721709415"><a name="b11721709415"></a><a name="b11721709415"></a>latlng</strong> is empty.</p>
</td>
</tr>
</tbody>
</table>

## h2setRotation<a name="section1989919222361"></a>

<a name="table15559mcpsimp"></a>
<table><thead align="left"><tr id="row15563mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p15565mcpsimp"><a name="p15565mcpsimp"></a><a name="p15565mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row15566mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p15568mcpsimp"><a name="p15568mcpsimp"></a><a name="p15568mcpsimp"></a>public final void setRotation(float rotation)</p>
<p id="p15571mcpsimp"><a name="p15571mcpsimp"></a><a name="p15571mcpsimp"></a>Sets the rotation angle of a marker, that is, the angle in which the marker rotates around the anchor point clockwise. The rotation axis is perpendicular to the marker. By default, the marker is north aligned, and the rotation angle is 0 degrees.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table15574mcpsimp"></a>
<table><thead align="left"><tr id="row15579mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p15581mcpsimp"><a name="p15581mcpsimp"></a><a name="p15581mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p15583mcpsimp"><a name="p15583mcpsimp"></a><a name="p15583mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row15584mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p15586mcpsimp"><a name="p15586mcpsimp"></a><a name="p15586mcpsimp"></a>rotation</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p15588mcpsimp"><a name="p15588mcpsimp"></a><a name="p15588mcpsimp"></a>Rotation angle of a marker. The default value is <strong id="b187761139172610"><a name="b187761139172610"></a><a name="b187761139172610"></a>0</strong>.</p>
</td>
</tr>
</tbody>
</table>

## setSnippet<a name="section165927340363"></a>

<a name="table15593mcpsimp"></a>
<table><thead align="left"><tr id="row15597mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p15599mcpsimp"><a name="p15599mcpsimp"></a><a name="p15599mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row15600mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p15602mcpsimp"><a name="p15602mcpsimp"></a><a name="p15602mcpsimp"></a>public final void setSnippet(String snippet)</p>
<p id="p10655632194716"><a name="p10655632194716"></a><a name="p10655632194716"></a>Sets the text snippet of a marker. If <strong id="b1149195252610"><a name="b1149195252610"></a><a name="b1149195252610"></a>null</strong> is passed, the existing text snippet will be cleared.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table15608mcpsimp"></a>
<table><thead align="left"><tr id="row15613mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p15615mcpsimp"><a name="p15615mcpsimp"></a><a name="p15615mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p15617mcpsimp"><a name="p15617mcpsimp"></a><a name="p15617mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row15618mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p15620mcpsimp"><a name="p15620mcpsimp"></a><a name="p15620mcpsimp"></a>snippet</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p15622mcpsimp"><a name="p15622mcpsimp"></a><a name="p15622mcpsimp"></a>Text snippet of a marker.</p>
</td>
</tr>
</tbody>
</table>

## setTag<a name="section893234843611"></a>

<a name="table15627mcpsimp"></a>
<table><thead align="left"><tr id="row15631mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p15633mcpsimp"><a name="p15633mcpsimp"></a><a name="p15633mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row15634mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p15636mcpsimp"><a name="p15636mcpsimp"></a><a name="p15636mcpsimp"></a>public final void setTag(Object tag)</p>
<p id="p14505144294711"><a name="p14505144294711"></a><a name="p14505144294711"></a>Sets the <strong id="b1037162444713"><a name="b1037162444713"></a><a name="b1037162444713"></a>tag</strong> attribute of a marker. If <strong id="b82211941192713"><a name="b82211941192713"></a><a name="b82211941192713"></a>null</strong> is passed, the <strong id="b1524552194720"><a name="b1524552194720"></a><a name="b1524552194720"></a>tag</strong> attribute will be cleared.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table15642mcpsimp"></a>
<table><thead align="left"><tr id="row15647mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p15649mcpsimp"><a name="p15649mcpsimp"></a><a name="p15649mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p15651mcpsimp"><a name="p15651mcpsimp"></a><a name="p15651mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row15652mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p15654mcpsimp"><a name="p15654mcpsimp"></a><a name="p15654mcpsimp"></a>tag</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p15656mcpsimp"><a name="p15656mcpsimp"></a><a name="p15656mcpsimp"></a>Tag of a marker.</p>
</td>
</tr>
</tbody>
</table>

## setTitle<a name="section13963185519361"></a>

<a name="table15661mcpsimp"></a>
<table><thead align="left"><tr id="row15665mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p15667mcpsimp"><a name="p15667mcpsimp"></a><a name="p15667mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row15668mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p15670mcpsimp"><a name="p15670mcpsimp"></a><a name="p15670mcpsimp"></a>public final void setTitle(String title)</p>
<p id="p15673mcpsimp"><a name="p15673mcpsimp"></a><a name="p15673mcpsimp"></a>Sets the title of a marker. By default, the title is empty.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table15676mcpsimp"></a>
<table><thead align="left"><tr id="row15681mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p15683mcpsimp"><a name="p15683mcpsimp"></a><a name="p15683mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p15685mcpsimp"><a name="p15685mcpsimp"></a><a name="p15685mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row15686mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p15688mcpsimp"><a name="p15688mcpsimp"></a><a name="p15688mcpsimp"></a>title</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p15690mcpsimp"><a name="p15690mcpsimp"></a><a name="p15690mcpsimp"></a>Title string. If this parameter is set to <strong id="b1295117762816"><a name="b1295117762816"></a><a name="b1295117762816"></a>null</strong>, the existing title will be cleared.</p>
</td>
</tr>
</tbody>
</table>

## setVisible<a name="section1775916212376"></a>

<a name="table15695mcpsimp"></a>
<table><thead align="left"><tr id="row15699mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p15701mcpsimp"><a name="p15701mcpsimp"></a><a name="p15701mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row15702mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p15704mcpsimp"><a name="p15704mcpsimp"></a><a name="p15704mcpsimp"></a>public final void setVisible(boolean visible)</p>
<p id="p146329854811"><a name="p146329854811"></a><a name="p146329854811"></a>Sets whether a marker is visible.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table15710mcpsimp"></a>
<table><thead align="left"><tr id="row15715mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p15717mcpsimp"><a name="p15717mcpsimp"></a><a name="p15717mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p15719mcpsimp"><a name="p15719mcpsimp"></a><a name="p15719mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row15720mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p15722mcpsimp"><a name="p15722mcpsimp"></a><a name="p15722mcpsimp"></a>visible</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p15724mcpsimp"><a name="p15724mcpsimp"></a><a name="p15724mcpsimp"></a>Indicates whether a marker is visible. <strong id="b8780143217282"><a name="b8780143217282"></a><a name="b8780143217282"></a>true</strong>: yes; <strong id="b979523214284"><a name="b979523214284"></a><a name="b979523214284"></a>false</strong>: no. The default value is <strong id="b141611059325"><a name="b141611059325"></a><a name="b141611059325"></a>true</strong>.</p>
</td>
</tr>
</tbody>
</table>

## setZIndex<a name="section952413920376"></a>

<a name="table15729mcpsimp"></a>
<table><thead align="left"><tr id="row15733mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p15735mcpsimp"><a name="p15735mcpsimp"></a><a name="p15735mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row15736mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p15738mcpsimp"><a name="p15738mcpsimp"></a><a name="p15738mcpsimp"></a>public final void setZIndex(float zIndex)</p>
<p id="p315311339485"><a name="p315311339485"></a><a name="p315311339485"></a>Sets the z-index of a marker. The z-index indicates the overlapping order of a marker. A marker with a larger z-index overlaps that with a smaller z-index. Markers with the same z-index overlap each other by the order in which they are added.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table15744mcpsimp"></a>
<table><thead align="left"><tr id="row15749mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p15751mcpsimp"><a name="p15751mcpsimp"></a><a name="p15751mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p15753mcpsimp"><a name="p15753mcpsimp"></a><a name="p15753mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row15754mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p15756mcpsimp"><a name="p15756mcpsimp"></a><a name="p15756mcpsimp"></a>zIndex</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p15758mcpsimp"><a name="p15758mcpsimp"></a><a name="p15758mcpsimp"></a>Z-index, which indicates the overlapping order of a marker. By default, the z-index is 0.</p>
<div class="caution" id="note2857645191713"><a name="note2857645191713"></a><a name="note2857645191713"></a><span class="cautiontitle"> CAUTION: </span><div class="cautionbody"><p id="p9331114715176"><a name="p9331114715176"></a><a name="p9331114715176"></a>If a marker is tapped, the marker will be place at the top and its z-index will be set to <strong id="b1693594318385"><a name="b1693594318385"></a><a name="b1693594318385"></a>3.4028235E38</strong>.</p>
</div></div>
</td>
</tr>
</tbody>
</table>

## showInfoWindow<a name="section13223817123711"></a>

<a name="table15763mcpsimp"></a>
<table><thead align="left"><tr id="row15767mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p15769mcpsimp"><a name="p15769mcpsimp"></a><a name="p15769mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row15770mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p15772mcpsimp"><a name="p15772mcpsimp"></a><a name="p15772mcpsimp"></a>public final void showInfoWindow()</p>
<p id="p162808499481"><a name="p162808499481"></a><a name="p162808499481"></a>Displays the information window for a marker.</p>
</td>
</tr>
</tbody>
</table>

## startAnimation<a name="section13557451287"></a>

<a name="table13355184518818"></a>
<table><thead align="left"><tr id="row123550450818"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p635614455811"><a name="p635614455811"></a><a name="p635614455811"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row10356154518818"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p103561545289"><a name="p103561545289"></a><a name="p103561545289"></a>public void startAnimation()</p>
<p id="p12356194512817"><a name="p12356194512817"></a><a name="p12356194512817"></a>Starts the animation of a marker.</p>
</td>
</tr>
</tbody>
</table>

