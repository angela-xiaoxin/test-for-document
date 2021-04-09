# CameraPosition<a name="EN-US_TOPIC_0000001099501048"></a>

-   [Nested Class Summary](#section33493356534)
-   [Public Field Summary](#section103771421175218)
-   [Public Constructor Summary](#section144632714529)
-   [Public Method Summary](#section1664184214583)
-   [Public Constructors](#section186512179184)
-   [CameraPosition](#section168973357123)
-   [Public Methods](#section36701606189)
-   [builder\(\)](#section895818127119)
-   [builder\(CameraPosition camera\)](#section127922417)
-   [createFromAttributes](#section17985297319)
-   [fromLatLngZoom](#section1216101916211)


<a name="table8986mcpsimp"></a>
<table><thead align="left"><tr id="row8990mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p8992mcpsimp"><a name="p8992mcpsimp"></a><a name="p8992mcpsimp"></a>Class Info</p>
</th>
</tr>
</thead>
<tbody><tr id="row8993mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p208163490511"><a name="p208163490511"></a><a name="p208163490511"></a>public class CameraPosition</p>
<p id="p8995mcpsimp"><a name="p8995mcpsimp"></a><a name="p8995mcpsimp"></a>An immutable class that encapsulates all camera attributes. </p>
</td>
</tr>
</tbody>
</table>

## Nested Class Summary<a name="section33493356534"></a>

<a name="table9122mcpsimp"></a>
<table><thead align="left"><tr id="row9127mcpsimp"><th class="cellrowborder" valign="top" width="38.62%" id="mcps1.1.3.1.1"><p id="p7543132495318"><a name="p7543132495318"></a><a name="p7543132495318"></a>Qualifier and Type</p>
</th>
<th class="cellrowborder" valign="top" width="61.38%" id="mcps1.1.3.1.2"><p id="p1554319242536"><a name="p1554319242536"></a><a name="p1554319242536"></a>Class Name and Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row9132mcpsimp"><td class="cellrowborder" valign="top" width="38.62%" headers="mcps1.1.3.1.1 "><p id="p128853843613"><a name="p128853843613"></a><a name="p128853843613"></a>public interface</p>
</td>
<td class="cellrowborder" valign="top" width="61.38%" headers="mcps1.1.3.1.2 "><p id="p9134mcpsimp"><a name="p9134mcpsimp"></a><a name="p9134mcpsimp"></a><a href="cameraposition-builder.md">CameraPosition.Builder</a></p>
<p id="p9136mcpsimp"><a name="p9136mcpsimp"></a><a name="p9136mcpsimp"></a>Creates a <a href="cameraposition.md">CameraPosition</a> object.</p>
</td>
</tr>
</tbody>
</table>

## Public Field Summary<a name="section103771421175218"></a>

<a name="table51207528357"></a>
<table><thead align="left"><tr id="row6121185283516"><th class="cellrowborder" valign="top" width="32.33%" id="mcps1.1.3.1.1"><p id="p1528164471414"><a name="p1528164471414"></a><a name="p1528164471414"></a>Qualifier and Type</p>
</th>
<th class="cellrowborder" valign="top" width="67.67%" id="mcps1.1.3.1.2"><p id="p1554614158108"><a name="p1554614158108"></a><a name="p1554614158108"></a>Field and Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row2012119527357"><td class="cellrowborder" valign="top" width="32.33%" headers="mcps1.1.3.1.1 "><p id="p524820675210"><a name="p524820675210"></a><a name="p524820675210"></a>public final float</p>
</td>
<td class="cellrowborder" valign="top" width="67.67%" headers="mcps1.1.3.1.2 "><p id="p178414885211"><a name="p178414885211"></a><a name="p178414885211"></a>bearing</p>
<p id="p196220185216"><a name="p196220185216"></a><a name="p196220185216"></a>Direction that the camera is pointing at.</p>
</td>
</tr>
<tr id="row8121145210353"><td class="cellrowborder" valign="top" width="32.33%" headers="mcps1.1.3.1.1 "><p id="p15248669524"><a name="p15248669524"></a><a name="p15248669524"></a>public final <a href="latlng.md">LatLng</a></p>
</td>
<td class="cellrowborder" valign="top" width="67.67%" headers="mcps1.1.3.1.2 "><p id="p1346001114521"><a name="p1346001114521"></a><a name="p1346001114521"></a>target</p>
<p id="p129629015217"><a name="p129629015217"></a><a name="p129629015217"></a>Longitude and latitude of the location that the camera is pointing at.</p>
</td>
</tr>
<tr id="row11169719154710"><td class="cellrowborder" valign="top" width="32.33%" headers="mcps1.1.3.1.1 "><p id="p1524813625212"><a name="p1524813625212"></a><a name="p1524813625212"></a>public final float</p>
</td>
<td class="cellrowborder" valign="top" width="67.67%" headers="mcps1.1.3.1.2 "><p id="p438331455219"><a name="p438331455219"></a><a name="p438331455219"></a>tilt</p>
<p id="p1296340195211"><a name="p1296340195211"></a><a name="p1296340195211"></a>Angle of the camera from the nadir (directly facing the Earth).</p>
</td>
</tr>
<tr id="row91071248204916"><td class="cellrowborder" valign="top" width="32.33%" headers="mcps1.1.3.1.1 "><p id="p1624846155219"><a name="p1624846155219"></a><a name="p1624846155219"></a>public final float</p>
</td>
<td class="cellrowborder" valign="top" width="67.67%" headers="mcps1.1.3.1.2 "><p id="p19953716185213"><a name="p19953716185213"></a><a name="p19953716185213"></a>zoom</p>
<p id="p1963405526"><a name="p1963405526"></a><a name="p1963405526"></a>Zoom level near the center of the screen.</p>
</td>
</tr>
</tbody>
</table>

## Public Constructor Summary<a name="section144632714529"></a>

<a name="table9039mcpsimp"></a>
<table><thead align="left"><tr id="row9043mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p145mcpsimp"><a name="p145mcpsimp"></a><a name="p145mcpsimp"></a>Constructor Name</p>
</th>
</tr>
</thead>
<tbody><tr id="row9046mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p9048mcpsimp"><a name="p9048mcpsimp"></a><a name="p9048mcpsimp"></a><a href="#section168973357123">CameraPosition</a>(<a href="latlng.md">LatLng</a> target, float zoom, float tilt, float bearing)</p>
<p id="p1182415110413"><a name="p1182415110413"></a><a name="p1182415110413"></a>Creates a <a href="cameraposition.md">CameraPosition</a> object based on specified parameters.</p>
</td>
</tr>
</tbody>
</table>

## Public Method Summary<a name="section1664184214583"></a>

<a name="table1359341712586"></a>
<table><thead align="left"><tr id="row1269861710583"><th class="cellrowborder" valign="top" width="43.63%" id="mcps1.1.3.1.1"><p id="p770950204210"><a name="p770950204210"></a><a name="p770950204210"></a>Qualifier and Type</p>
</th>
<th class="cellrowborder" valign="top" width="56.37%" id="mcps1.1.3.1.2"><p id="p12123115418111"><a name="p12123115418111"></a><a name="p12123115418111"></a>Method Name and Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row1569981715810"><td class="cellrowborder" valign="top" width="43.63%" headers="mcps1.1.3.1.1 "><p id="p2699141795811"><a name="p2699141795811"></a><a name="p2699141795811"></a>static <a href="cameraposition-builder.md">CameraPosition.Builder</a></p>
</td>
<td class="cellrowborder" valign="top" width="56.37%" headers="mcps1.1.3.1.2 "><p id="p14699141715819"><a name="p14699141715819"></a><a name="p14699141715819"></a><a href="#section895818127119">builder</a>()</p>
<p id="p378874220301"><a name="p378874220301"></a><a name="p378874220301"></a>Creates a <a href="cameraposition-builder.md">CameraPosition.Builder</a> object.</p>
</td>
</tr>
<tr id="row16699131711589"><td class="cellrowborder" valign="top" width="43.63%" headers="mcps1.1.3.1.1 "><p id="p106991017115811"><a name="p106991017115811"></a><a name="p106991017115811"></a>static <a href="cameraposition-builder.md">CameraPosition.Builder</a></p>
</td>
<td class="cellrowborder" valign="top" width="56.37%" headers="mcps1.1.3.1.2 "><p id="p1569915177582"><a name="p1569915177582"></a><a name="p1569915177582"></a><a href="#section127922417">builder</a>(<a href="cameraposition.md">CameraPosition</a> camera)</p>
<p id="p48931944123010"><a name="p48931944123010"></a><a name="p48931944123010"></a>Creates a <a href="cameraposition-builder.md">CameraPosition.Builder</a> object using the specified <a href="cameraposition.md">CameraPosition</a>.</p>
</td>
</tr>
<tr id="row0699121713587"><td class="cellrowborder" valign="top" width="43.63%" headers="mcps1.1.3.1.1 "><p id="p14699141725818"><a name="p14699141725818"></a><a name="p14699141725818"></a>static <a href="cameraposition.md">CameraPosition</a></p>
</td>
<td class="cellrowborder" valign="top" width="56.37%" headers="mcps1.1.3.1.2 "><p id="p1369931785813"><a name="p1369931785813"></a><a name="p1369931785813"></a><a href="#section17985297319">createFromAttributes</a>(Context context, AttributeSet attrs)</p>
<p id="p2254204618302"><a name="p2254204618302"></a><a name="p2254204618302"></a>Customizes attributes of a <a href="cameraposition.md">CameraPosition</a> object.</p>
</td>
</tr>
<tr id="row116999177584"><td class="cellrowborder" valign="top" width="43.63%" headers="mcps1.1.3.1.1 "><p id="p10699161765815"><a name="p10699161765815"></a><a name="p10699161765815"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="56.37%" headers="mcps1.1.3.1.2 "><p id="p670018175587"><a name="p670018175587"></a><a name="p670018175587"></a>equals(Object o)</p>
<p id="p1803742191511"><a name="p1803742191511"></a><a name="p1803742191511"></a>Checks whether a <a href="cameraposition.md">CameraPosition</a> object equals another.</p>
</td>
</tr>
<tr id="row2070061711588"><td class="cellrowborder" valign="top" width="43.63%" headers="mcps1.1.3.1.1 "><p id="p87001017155816"><a name="p87001017155816"></a><a name="p87001017155816"></a>static <a href="cameraposition.md">CameraPosition</a></p>
</td>
<td class="cellrowborder" valign="top" width="56.37%" headers="mcps1.1.3.1.2 "><p id="p4700101712580"><a name="p4700101712580"></a><a name="p4700101712580"></a><a href="#section1216101916211">fromLatLngZoom</a>(<a href="latlng.md">LatLng</a> target, float zoom)</p>
<p id="p1728174893016"><a name="p1728174893016"></a><a name="p1728174893016"></a>Creates a <a href="cameraposition.md">CameraPosition</a> object pointed for a specific target (longitude and latitude) and zoom level.</p>
</td>
</tr>
<tr id="row15700191715812"><td class="cellrowborder" valign="top" width="43.63%" headers="mcps1.1.3.1.1 "><p id="p147001917195818"><a name="p147001917195818"></a><a name="p147001917195818"></a>int</p>
</td>
<td class="cellrowborder" valign="top" width="56.37%" headers="mcps1.1.3.1.2 "><p id="p6700171705815"><a name="p6700171705815"></a><a name="p6700171705815"></a>hashCode()</p>
<p id="p1638394641010"><a name="p1638394641010"></a><a name="p1638394641010"></a>Returns the hash code of an object.</p>
</td>
</tr>
<tr id="row5700417125812"><td class="cellrowborder" valign="top" width="43.63%" headers="mcps1.1.3.1.1 "><p id="p1770017174585"><a name="p1770017174585"></a><a name="p1770017174585"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="56.37%" headers="mcps1.1.3.1.2 "><p id="p11700191718587"><a name="p11700191718587"></a><a name="p11700191718587"></a>toString()</p>
<p id="p772114921015"><a name="p772114921015"></a><a name="p772114921015"></a>Returns the object as a string.</p>
</td>
</tr>
<tr id="row470031717582"><td class="cellrowborder" valign="top" width="43.63%" headers="mcps1.1.3.1.1 "><p id="p870061716580"><a name="p870061716580"></a><a name="p870061716580"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="56.37%" headers="mcps1.1.3.1.2 "><p id="p970001714585"><a name="p970001714585"></a><a name="p970001714585"></a>writeToParcel(Parcel out, int flags)</p>
<p id="p142370615206"><a name="p142370615206"></a><a name="p142370615206"></a>Serializes data.</p>
</td>
</tr>
</tbody>
</table>

## Public Constructors<a name="section186512179184"></a>

## CameraPosition<a name="section168973357123"></a>

<a name="table227mcpsimp"></a>
<table><thead align="left"><tr id="row231mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p233mcpsimp"><a name="p233mcpsimp"></a><a name="p233mcpsimp"></a>Constructor</p>
</th>
</tr>
</thead>
<tbody><tr id="row235mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p1884817142017"><a name="p1884817142017"></a><a name="p1884817142017"></a>public <a href="cameraposition.md">CameraPosition</a>(<a href="latlng.md">LatLng</a> target, float zoom, float tilt, float bearing)</p>
<p id="p78641135445"><a name="p78641135445"></a><a name="p78641135445"></a>Constructs a <a href="cameraposition.md">CameraPosition</a> object.</p>
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
<tbody><tr id="row255mcpsimp"><td class="cellrowborder" valign="top" width="43%" headers="mcps1.1.3.1.1 "><p id="p1275719175136"><a name="p1275719175136"></a><a name="p1275719175136"></a>target</p>
</td>
<td class="cellrowborder" valign="top" width="56.99999999999999%" headers="mcps1.1.3.1.2 "><p id="p69541622141317"><a name="p69541622141317"></a><a name="p69541622141317"></a>Longitude and latitude of the location that the camera is pointing at.</p>
</td>
</tr>
<tr id="row1241952481220"><td class="cellrowborder" valign="top" width="43%" headers="mcps1.1.3.1.1 "><p id="p17420924131217"><a name="p17420924131217"></a><a name="p17420924131217"></a>zoom</p>
</td>
<td class="cellrowborder" valign="top" width="56.99999999999999%" headers="mcps1.1.3.1.2 "><p id="p142013243124"><a name="p142013243124"></a><a name="p142013243124"></a>Zoom level near the center of the screen.</p>
</td>
</tr>
<tr id="row6948828191213"><td class="cellrowborder" valign="top" width="43%" headers="mcps1.1.3.1.1 "><p id="p179482028181215"><a name="p179482028181215"></a><a name="p179482028181215"></a>tilt</p>
</td>
<td class="cellrowborder" valign="top" width="56.99999999999999%" headers="mcps1.1.3.1.2 "><p id="p8948192871217"><a name="p8948192871217"></a><a name="p8948192871217"></a>Angle of the camera from the nadir (directly facing the Earth).</p>
</td>
</tr>
<tr id="row33281532171220"><td class="cellrowborder" valign="top" width="43%" headers="mcps1.1.3.1.1 "><p id="p7328133261219"><a name="p7328133261219"></a><a name="p7328133261219"></a>bearing</p>
</td>
<td class="cellrowborder" valign="top" width="56.99999999999999%" headers="mcps1.1.3.1.2 "><p id="p123292032161210"><a name="p123292032161210"></a><a name="p123292032161210"></a>Direction that the camera is pointing at.</p>
</td>
</tr>
</tbody>
</table>

**Throws**

<a name="table9101mcpsimp"></a>
<table><thead align="left"><tr id="row9106mcpsimp"><th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.1"><p id="p310mcpsimp"><a name="p310mcpsimp"></a><a name="p310mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.2"><p id="p313mcpsimp"><a name="p313mcpsimp"></a><a name="p313mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row9111mcpsimp"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p9113mcpsimp"><a name="p9113mcpsimp"></a><a name="p9113mcpsimp"></a>NullPointerException</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p9115mcpsimp"><a name="p9115mcpsimp"></a><a name="p9115mcpsimp"></a>If the passed <strong id="b18754744915"><a name="b18754744915"></a><a name="b18754744915"></a>target</strong> is <strong id="b0268349194915"><a name="b0268349194915"></a><a name="b0268349194915"></a>null</strong>.</p>
</td>
</tr>
<tr id="row9116mcpsimp"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p9118mcpsimp"><a name="p9118mcpsimp"></a><a name="p9118mcpsimp"></a>IllegalArgumentException</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p9120mcpsimp"><a name="p9120mcpsimp"></a><a name="p9120mcpsimp"></a>If the passed <strong id="b3555156154910"><a name="b3555156154910"></a><a name="b3555156154910"></a>tilt</strong> is out of the range from 0 to 90 degrees.</p>
</td>
</tr>
</tbody>
</table>

## Public Methods<a name="section36701606189"></a>

## builder\(\)<a name="section895818127119"></a>

<a name="table11641597014"></a>
<table><thead align="left"><tr id="row528485916018"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p1028512591402"><a name="p1028512591402"></a><a name="p1028512591402"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row428519597013"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p6285159809"><a name="p6285159809"></a><a name="p6285159809"></a>public static <a href="cameraposition-builder.md">CameraPosition.Builder</a> builder()</p>
<p id="p12285259905"><a name="p12285259905"></a><a name="p12285259905"></a>Creates a <a href="cameraposition-builder.md">CameraPosition.Builder</a> object.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table19765593019"></a>
<table><thead align="left"><tr id="row6285859901"><th class="cellrowborder" valign="top" width="49.01%" id="mcps1.1.3.1.1"><p id="p374mcpsimp"><a name="p374mcpsimp"></a><a name="p374mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="50.99%" id="mcps1.1.3.1.2"><p id="p377mcpsimp"><a name="p377mcpsimp"></a><a name="p377mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row4285105910012"><td class="cellrowborder" valign="top" width="49.01%" headers="mcps1.1.3.1.1 "><p id="p228616591605"><a name="p228616591605"></a><a name="p228616591605"></a>CameraPosition.Builder</p>
</td>
<td class="cellrowborder" valign="top" width="50.99%" headers="mcps1.1.3.1.2 "><p id="p128612591203"><a name="p128612591203"></a><a name="p128612591203"></a><a href="cameraposition-builder.md">CameraPosition.Builder</a> object.</p>
</td>
</tr>
</tbody>
</table>

## builder\(CameraPosition camera\)<a name="section127922417"></a>

<a name="table78017593010"></a>
<table><thead align="left"><tr id="row928611591019"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p8286559603"><a name="p8286559603"></a><a name="p8286559603"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row18286125918014"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p142869591201"><a name="p142869591201"></a><a name="p142869591201"></a>public static <a href="cameraposition-builder.md">CameraPosition.Builder</a> builder(<a href="cameraposition.md">CameraPosition</a> camera)</p>
<p id="p5241103424216"><a name="p5241103424216"></a><a name="p5241103424216"></a>Creates a <a href="cameraposition-builder.md">CameraPosition.Builder</a> object using the specified <a href="cameraposition.md">CameraPosition</a>.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table1784135913016"></a>
<table><thead align="left"><tr id="row12871595020"><th class="cellrowborder" valign="top" width="45.33%" id="mcps1.1.3.1.1"><p id="p1428710592014"><a name="p1428710592014"></a><a name="p1428710592014"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="54.669999999999995%" id="mcps1.1.3.1.2"><p id="p1088035202613"><a name="p1088035202613"></a><a name="p1088035202613"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row82887593016"><td class="cellrowborder" valign="top" width="45.33%" headers="mcps1.1.3.1.1 "><p id="p11288175911014"><a name="p11288175911014"></a><a name="p11288175911014"></a>camera</p>
</td>
<td class="cellrowborder" valign="top" width="54.669999999999995%" headers="mcps1.1.3.1.2 "><p id="p1828816591018"><a name="p1828816591018"></a><a name="p1828816591018"></a><a href="cameraposition.md">CameraPosition</a> object used to create a <a href="cameraposition-builder.md">CameraPosition.Builder</a> object.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table888359700"></a>
<table><thead align="left"><tr id="row122897594016"><th class="cellrowborder" valign="top" width="49.01%" id="mcps1.1.3.1.1"><p id="p528395918268"><a name="p528395918268"></a><a name="p528395918268"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="50.99%" id="mcps1.1.3.1.2"><p id="p52836593267"><a name="p52836593267"></a><a name="p52836593267"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row1428919591007"><td class="cellrowborder" valign="top" width="49.01%" headers="mcps1.1.3.1.1 "><p id="p1628945911016"><a name="p1628945911016"></a><a name="p1628945911016"></a>CameraPosition.Builder</p>
</td>
<td class="cellrowborder" valign="top" width="50.99%" headers="mcps1.1.3.1.2 "><p id="p14289459802"><a name="p14289459802"></a><a name="p14289459802"></a><a href="cameraposition-builder.md">CameraPosition.Builder</a> object.</p>
</td>
</tr>
</tbody>
</table>

## createFromAttributes<a name="section17985297319"></a>

<a name="table8911359409"></a>
<table><thead align="left"><tr id="row122902591404"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p82906590015"><a name="p82906590015"></a><a name="p82906590015"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row1129016591403"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p17290165919013"><a name="p17290165919013"></a><a name="p17290165919013"></a>public static <a href="cameraposition.md">CameraPosition</a> createFromAttributes(Context context, AttributeSet attrs)</p>
<p id="p174861458425"><a name="p174861458425"></a><a name="p174861458425"></a>Customizes attributes of a <a href="cameraposition.md">CameraPosition</a> object.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table595205911019"></a>
<table><thead align="left"><tr id="row329111599013"><th class="cellrowborder" valign="top" width="45.33%" id="mcps1.1.3.1.1"><p id="p06911116132711"><a name="p06911116132711"></a><a name="p06911116132711"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="54.669999999999995%" id="mcps1.1.3.1.2"><p id="p2069112162272"><a name="p2069112162272"></a><a name="p2069112162272"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row1629217591008"><td class="cellrowborder" valign="top" width="45.33%" headers="mcps1.1.3.1.1 "><p id="p1429213593010"><a name="p1429213593010"></a><a name="p1429213593010"></a>context</p>
</td>
<td class="cellrowborder" valign="top" width="54.669999999999995%" headers="mcps1.1.3.1.2 "><p id="p1329212599010"><a name="p1329212599010"></a><a name="p1329212599010"></a>Context.</p>
</td>
</tr>
<tr id="row18292759004"><td class="cellrowborder" valign="top" width="45.33%" headers="mcps1.1.3.1.1 "><p id="p429310591608"><a name="p429310591608"></a><a name="p429310591608"></a>attrs</p>
</td>
<td class="cellrowborder" valign="top" width="54.669999999999995%" headers="mcps1.1.3.1.2 "><p id="p10293155910012"><a name="p10293155910012"></a><a name="p10293155910012"></a>Attributes of <a href="cameraposition.md">CameraPosition</a>.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table9996591004"></a>
<table><thead align="left"><tr id="row182937599013"><th class="cellrowborder" valign="top" width="48.02%" id="mcps1.1.3.1.1"><p id="p121723412272"><a name="p121723412272"></a><a name="p121723412272"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="51.980000000000004%" id="mcps1.1.3.1.2"><p id="p11721944271"><a name="p11721944271"></a><a name="p11721944271"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row1229414591207"><td class="cellrowborder" valign="top" width="48.02%" headers="mcps1.1.3.1.1 "><p id="p20294115913010"><a name="p20294115913010"></a><a name="p20294115913010"></a><a href="cameraposition.md">CameraPosition</a></p>
</td>
<td class="cellrowborder" valign="top" width="51.980000000000004%" headers="mcps1.1.3.1.2 "><p id="p1629435916012"><a name="p1629435916012"></a><a name="p1629435916012"></a><strong id="b186529241963"><a name="b186529241963"></a><a name="b186529241963"></a>CameraPosition</strong> object.</p>
</td>
</tr>
</tbody>
</table>

## fromLatLngZoom<a name="section1216101916211"></a>

<a name="table11026595010"></a>
<table><thead align="left"><tr id="row19294559602"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p182941959805"><a name="p182941959805"></a><a name="p182941959805"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row929585918013"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p1129520592012"><a name="p1129520592012"></a><a name="p1129520592012"></a>public static <a href="cameraposition.md">CameraPosition</a> fromLatLngZoom(<a href="latlng.md">LatLng</a> target, float zoom)</p>
<p id="p1329517595013"><a name="p1329517595013"></a><a name="p1329517595013"></a>Creates a <a href="cameraposition.md">CameraPosition</a> object pointed for a specific target (longitude and latitude) and zoom level.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table1310514594010"></a>
<table><thead align="left"><tr id="row62957591204"><th class="cellrowborder" valign="top" width="47.589999999999996%" id="mcps1.1.3.1.1"><p id="p53518216279"><a name="p53518216279"></a><a name="p53518216279"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="52.410000000000004%" id="mcps1.1.3.1.2"><p id="p23562113274"><a name="p23562113274"></a><a name="p23562113274"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row7296205913014"><td class="cellrowborder" valign="top" width="47.589999999999996%" headers="mcps1.1.3.1.1 "><p id="p152964597010"><a name="p152964597010"></a><a name="p152964597010"></a>target</p>
</td>
<td class="cellrowborder" valign="top" width="52.410000000000004%" headers="mcps1.1.3.1.2 "><p id="p182964596018"><a name="p182964596018"></a><a name="p182964596018"></a>Longitude and latitude.</p>
</td>
</tr>
<tr id="row1329620591803"><td class="cellrowborder" valign="top" width="47.589999999999996%" headers="mcps1.1.3.1.1 "><p id="p1829610591606"><a name="p1829610591606"></a><a name="p1829610591606"></a>zoom</p>
</td>
<td class="cellrowborder" valign="top" width="52.410000000000004%" headers="mcps1.1.3.1.2 "><p id="p429645910010"><a name="p429645910010"></a><a name="p429645910010"></a>Zoom level of the map camera. The value range is [3, 20].</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table16109105915018"></a>
<table><thead align="left"><tr id="row8297259205"><th class="cellrowborder" valign="top" width="48.02%" id="mcps1.1.3.1.1"><p id="p1743712610278"><a name="p1743712610278"></a><a name="p1743712610278"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="51.980000000000004%" id="mcps1.1.3.1.2"><p id="p13437142612274"><a name="p13437142612274"></a><a name="p13437142612274"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row1229719591005"><td class="cellrowborder" valign="top" width="48.02%" headers="mcps1.1.3.1.1 "><p id="p3297115918010"><a name="p3297115918010"></a><a name="p3297115918010"></a>CameraPosition</p>
</td>
<td class="cellrowborder" valign="top" width="51.980000000000004%" headers="mcps1.1.3.1.2 "><p id="p4297359803"><a name="p4297359803"></a><a name="p4297359803"></a><a href="cameraposition.md">CameraPosition</a> object.</p>
</td>
</tr>
</tbody>
</table>

