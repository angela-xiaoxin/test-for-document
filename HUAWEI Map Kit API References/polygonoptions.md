# PolygonOptions<a name="EN-US_TOPIC_0000001145860951"></a>

-   [Public Constructor Summary](#section146951214172)
-   [Public Method Summary](#section1974715513179)
-   [Public Methods](#section201110194516)
-   [add\(LatLng... points\)](#section16654164445112)
-   [add\(LatLng point\)](#section1019721914520)
-   [addAll](#section11151141725712)
-   [addHole](#section874319100586)
-   [clickable](#section12764124915819)
-   [fillColor](#section129413288114)
-   [geodesic](#section01622087214)
-   [getFillColor](#section411713436217)
-   [getHoles](#section1110712151531)
-   [getPoints](#section915202713413)
-   [getStrokeColor](#section13591484311)
-   [getStrokeJointType](#section143841310959)
-   [getStrokePattern](#section1473217443519)
-   [getStrokeWidth](#section1163341714618)
-   [getZIndex](#section1562365314616)
-   [isClickable](#section1550811171973)
-   [isGeodesic](#section79861851571)
-   [isVisible](#section161543191689)
-   [strokeColor](#section147551851285)
-   [strokeJointType](#section590852719910)
-   [strokePattern](#section55016211102)
-   [strokeWidth](#section208221238141011)
-   [visible](#section128711841191217)
-   [zIndex](#section98173041518)


<a name="table18446mcpsimp"></a>
<table><thead align="left"><tr id="row18450mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p18452mcpsimp"><a name="p18452mcpsimp"></a><a name="p18452mcpsimp"></a>Class Info</p>
</th>
</tr>
</thead>
<tbody><tr id="row18453mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p952424517424"><a name="p952424517424"></a><a name="p952424517424"></a>public class PolygonOptions</p>
<p id="p18455mcpsimp"><a name="p18455mcpsimp"></a><a name="p18455mcpsimp"></a>Defines attributes for a <a href="polygon.md">Polygon</a> object.</p>
</td>
</tr>
</tbody>
</table>

## Public Constructor Summary<a name="section146951214172"></a>

<a name="table18459mcpsimp"></a>
<table><thead align="left"><tr id="row18463mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p145mcpsimp"><a name="p145mcpsimp"></a><a name="p145mcpsimp"></a>Constructor Name</p>
</th>
</tr>
</thead>
<tbody><tr id="row18466mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p18468mcpsimp"><a name="p18468mcpsimp"></a><a name="p18468mcpsimp"></a><a href="polygonoptions.md">PolygonOptions</a>()</p>
<p id="p171173313512"><a name="p171173313512"></a><a name="p171173313512"></a>Default constructor of the <strong id="b178061139689"><a name="b178061139689"></a><a name="b178061139689"></a>PolygonOptions</strong> class.</p>
</td>
</tr>
</tbody>
</table>

## Public Method Summary<a name="section1974715513179"></a>

<a name="table18470mcpsimp"></a>
<table><thead align="left"><tr id="row18475mcpsimp"><th class="cellrowborder" valign="top" width="40%" id="mcps1.1.3.1.1"><p id="p081120285386"><a name="p081120285386"></a><a name="p081120285386"></a>Qualifier and Type</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.1.3.1.2"><p id="p681112883813"><a name="p681112883813"></a><a name="p681112883813"></a>Method Name and Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row18480mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p18482mcpsimp"><a name="p18482mcpsimp"></a><a name="p18482mcpsimp"></a><a href="polygonoptions.md">PolygonOptions</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p18484mcpsimp"><a name="p18484mcpsimp"></a><a name="p18484mcpsimp"></a><a href="#section16654164445112">add</a>(<a href="latlng.md">LatLng</a>... points)</p>
<p id="p77612511209"><a name="p77612511209"></a><a name="p77612511209"></a>Sets multiple vertices of a polygon.</p>
</td>
</tr>
<tr id="row18485mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p18487mcpsimp"><a name="p18487mcpsimp"></a><a name="p18487mcpsimp"></a><a href="polygonoptions.md">PolygonOptions</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p18489mcpsimp"><a name="p18489mcpsimp"></a><a name="p18489mcpsimp"></a><a href="#section1019721914520">add</a>(<a href="latlng.md">LatLng</a> point)</p>
<p id="p636413524016"><a name="p636413524016"></a><a name="p636413524016"></a>Adds a vertex to a polygon.</p>
</td>
</tr>
<tr id="row18490mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p18492mcpsimp"><a name="p18492mcpsimp"></a><a name="p18492mcpsimp"></a><a href="polygonoptions.md">PolygonOptions</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p18494mcpsimp"><a name="p18494mcpsimp"></a><a name="p18494mcpsimp"></a><a href="#section11151141725712">addAll</a>(Iterable&lt;<a href="latlng.md">LatLng</a>&gt; points)</p>
<p id="p7310185312012"><a name="p7310185312012"></a><a name="p7310185312012"></a>Adds multiple vertices to a polygon.</p>
</td>
</tr>
<tr id="row18495mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p18497mcpsimp"><a name="p18497mcpsimp"></a><a name="p18497mcpsimp"></a><a href="polygonoptions.md">PolygonOptions</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p18499mcpsimp"><a name="p18499mcpsimp"></a><a name="p18499mcpsimp"></a><a href="#section874319100586">addHole</a>(Iterable&lt;<a href="latlng.md">LatLng</a>&gt; points)</p>
<p id="p182853541012"><a name="p182853541012"></a><a name="p182853541012"></a>Adds multiple holes to a polygon.</p>
</td>
</tr>
<tr id="row18500mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p18502mcpsimp"><a name="p18502mcpsimp"></a><a name="p18502mcpsimp"></a><a href="polygonoptions.md">PolygonOptions</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p18504mcpsimp"><a name="p18504mcpsimp"></a><a name="p18504mcpsimp"></a><a href="#section12764124915819">clickable</a>(boolean clickable)</p>
<p id="p1465655705"><a name="p1465655705"></a><a name="p1465655705"></a>Sets whether a polygon is tappable.</p>
</td>
</tr>
<tr id="row18505mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p18507mcpsimp"><a name="p18507mcpsimp"></a><a name="p18507mcpsimp"></a><a href="polygonoptions.md">PolygonOptions</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p18509mcpsimp"><a name="p18509mcpsimp"></a><a name="p18509mcpsimp"></a><a href="#section129413288114">fillColor</a>(int color)</p>
<p id="p821714571409"><a name="p821714571409"></a><a name="p821714571409"></a>Sets the fill color of a polygon.</p>
</td>
</tr>
<tr id="row18510mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p18512mcpsimp"><a name="p18512mcpsimp"></a><a name="p18512mcpsimp"></a><a href="polygonoptions.md">PolygonOptions</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p18514mcpsimp"><a name="p18514mcpsimp"></a><a name="p18514mcpsimp"></a><a href="#section01622087214">geodesic</a>(boolean geodesic)</p>
<p id="p352115817010"><a name="p352115817010"></a><a name="p352115817010"></a>Sets whether to draw each segment of a polygon as a geodesic.</p>
</td>
</tr>
<tr id="row18515mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p18517mcpsimp"><a name="p18517mcpsimp"></a><a name="p18517mcpsimp"></a>int</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p18519mcpsimp"><a name="p18519mcpsimp"></a><a name="p18519mcpsimp"></a><a href="#section411713436217">getFillColor</a>()</p>
<p id="p1888119591503"><a name="p1888119591503"></a><a name="p1888119591503"></a>Obtains the fill color of a polygon.</p>
</td>
</tr>
<tr id="row18520mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p18522mcpsimp"><a name="p18522mcpsimp"></a><a name="p18522mcpsimp"></a>List&lt;List&lt;<a href="latlng.md">LatLng</a>&gt;&gt;</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p18524mcpsimp"><a name="p18524mcpsimp"></a><a name="p18524mcpsimp"></a><a href="#section1110712151531">getHoles</a>()</p>
<p id="p9275152315"><a name="p9275152315"></a><a name="p9275152315"></a>Obtains holes in a polygon on a map.</p>
</td>
</tr>
<tr id="row18525mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p18527mcpsimp"><a name="p18527mcpsimp"></a><a name="p18527mcpsimp"></a>List&lt;<a href="latlng.md">LatLng</a>&gt;</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p18529mcpsimp"><a name="p18529mcpsimp"></a><a name="p18529mcpsimp"></a><a href="#section915202713413">getPoints</a>()</p>
<p id="p1429231617"><a name="p1429231617"></a><a name="p1429231617"></a>Obtains all vertices of a polygon.</p>
</td>
</tr>
<tr id="row18530mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p18532mcpsimp"><a name="p18532mcpsimp"></a><a name="p18532mcpsimp"></a>int</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p18534mcpsimp"><a name="p18534mcpsimp"></a><a name="p18534mcpsimp"></a><a href="#section13591484311">getStrokeColor</a>()</p>
<p id="p15617249115"><a name="p15617249115"></a><a name="p15617249115"></a>Obtains the stroke color of a polygon's outline, in ARGB format.</p>
</td>
</tr>
<tr id="row18535mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p18537mcpsimp"><a name="p18537mcpsimp"></a><a name="p18537mcpsimp"></a>int</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p18539mcpsimp"><a name="p18539mcpsimp"></a><a name="p18539mcpsimp"></a><a href="#section143841310959">getStrokeJointType</a>()</p>
<p id="p134661451811"><a name="p134661451811"></a><a name="p134661451811"></a>Obtains the joint type of a polygon.</p>
</td>
</tr>
<tr id="row18540mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p18542mcpsimp"><a name="p18542mcpsimp"></a><a name="p18542mcpsimp"></a>List&lt;<a href="patternitem.md">PatternItem</a>&gt;</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p18544mcpsimp"><a name="p18544mcpsimp"></a><a name="p18544mcpsimp"></a><a href="#section1473217443519">getStrokePattern</a>()</p>
<p id="p2293061918"><a name="p2293061918"></a><a name="p2293061918"></a>Obtains the stroke pattern of a polygon's outline.</p>
</td>
</tr>
<tr id="row18545mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p18547mcpsimp"><a name="p18547mcpsimp"></a><a name="p18547mcpsimp"></a>float</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p18549mcpsimp"><a name="p18549mcpsimp"></a><a name="p18549mcpsimp"></a><a href="#section1163341714618">getStrokeWidth</a>()</p>
<p id="p1631507810"><a name="p1631507810"></a><a name="p1631507810"></a>Obtains the stroke width of a polygon's outline.</p>
</td>
</tr>
<tr id="row18550mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p18552mcpsimp"><a name="p18552mcpsimp"></a><a name="p18552mcpsimp"></a>float</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p18554mcpsimp"><a name="p18554mcpsimp"></a><a name="p18554mcpsimp"></a><a href="#section1562365314616">getZIndex</a>()</p>
<p id="p135632811119"><a name="p135632811119"></a><a name="p135632811119"></a>Obtains the z-index of a polygon.</p>
</td>
</tr>
<tr id="row18555mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p18557mcpsimp"><a name="p18557mcpsimp"></a><a name="p18557mcpsimp"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p18559mcpsimp"><a name="p18559mcpsimp"></a><a name="p18559mcpsimp"></a><a href="#section1550811171973">isClickable</a>()</p>
<p id="p5650893119"><a name="p5650893119"></a><a name="p5650893119"></a>Checks whether a polygon is tappable.</p>
</td>
</tr>
<tr id="row18560mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p18562mcpsimp"><a name="p18562mcpsimp"></a><a name="p18562mcpsimp"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p18564mcpsimp"><a name="p18564mcpsimp"></a><a name="p18564mcpsimp"></a><a href="#section79861851571">isGeodesic</a>()</p>
<p id="p842981118112"><a name="p842981118112"></a><a name="p842981118112"></a>Checks whether each segment of a polygon is drawn as a geodesic.</p>
</td>
</tr>
<tr id="row18565mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p18567mcpsimp"><a name="p18567mcpsimp"></a><a name="p18567mcpsimp"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p18569mcpsimp"><a name="p18569mcpsimp"></a><a name="p18569mcpsimp"></a><a href="#section161543191689">isVisible</a>()</p>
<p id="p134317121811"><a name="p134317121811"></a><a name="p134317121811"></a>Checks whether a polygon is visible.</p>
</td>
</tr>
<tr id="row18570mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p18572mcpsimp"><a name="p18572mcpsimp"></a><a name="p18572mcpsimp"></a><a href="polygonoptions.md">PolygonOptions</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p18574mcpsimp"><a name="p18574mcpsimp"></a><a name="p18574mcpsimp"></a><a href="#section147551851285">strokeColor</a>(int color)</p>
<p id="p93660131511"><a name="p93660131511"></a><a name="p93660131511"></a>Sets the stroke color of a polygon's outline.</p>
</td>
</tr>
<tr id="row18575mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p18577mcpsimp"><a name="p18577mcpsimp"></a><a name="p18577mcpsimp"></a><a href="polygonoptions.md">PolygonOptions</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p18579mcpsimp"><a name="p18579mcpsimp"></a><a name="p18579mcpsimp"></a><a href="#section590852719910">strokeJointType</a>(int jointType)</p>
<p id="p8350111418114"><a name="p8350111418114"></a><a name="p8350111418114"></a>Sets the joint type of a polygon.</p>
</td>
</tr>
<tr id="row18580mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p18582mcpsimp"><a name="p18582mcpsimp"></a><a name="p18582mcpsimp"></a><a href="polygonoptions.md">PolygonOptions</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p18584mcpsimp"><a name="p18584mcpsimp"></a><a name="p18584mcpsimp"></a><a href="#section55016211102">strokePattern</a>(List&lt;<a href="patternitem.md">PatternItem</a>&gt; pattern)</p>
<p id="p77424151113"><a name="p77424151113"></a><a name="p77424151113"></a>Sets the stroke pattern of a polygon's outline.</p>
</td>
</tr>
<tr id="row18585mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p18587mcpsimp"><a name="p18587mcpsimp"></a><a name="p18587mcpsimp"></a><a href="polygonoptions.md">PolygonOptions</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p18589mcpsimp"><a name="p18589mcpsimp"></a><a name="p18589mcpsimp"></a><a href="#section208221238141011">strokeWidth</a>(float width)</p>
<p id="p122781117111"><a name="p122781117111"></a><a name="p122781117111"></a>Sets the stroke width of a polygon's outline.</p>
</td>
</tr>
<tr id="row18590mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p18592mcpsimp"><a name="p18592mcpsimp"></a><a name="p18592mcpsimp"></a><a href="polygonoptions.md">PolygonOptions</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p18594mcpsimp"><a name="p18594mcpsimp"></a><a name="p18594mcpsimp"></a><a href="#section128711841191217">visible</a>(boolean visible)</p>
<p id="p133636186119"><a name="p133636186119"></a><a name="p133636186119"></a>Sets whether a polygon is visible.</p>
</td>
</tr>
<tr id="row18595mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p18597mcpsimp"><a name="p18597mcpsimp"></a><a name="p18597mcpsimp"></a><a href="polygonoptions.md">PolygonOptions</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p18599mcpsimp"><a name="p18599mcpsimp"></a><a name="p18599mcpsimp"></a><a href="#section98173041518">zIndex</a>(float zIndex)</p>
<p id="p108731919413"><a name="p108731919413"></a><a name="p108731919413"></a>Sets the z-index of a polygon.</p>
</td>
</tr>
</tbody>
</table>

## Public Methods<a name="section201110194516"></a>

## add\(LatLng... points\)<a name="section16654164445112"></a>

<a name="table18602mcpsimp"></a>
<table><thead align="left"><tr id="row18606mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p18608mcpsimp"><a name="p18608mcpsimp"></a><a name="p18608mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row18609mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p18611mcpsimp"><a name="p18611mcpsimp"></a><a name="p18611mcpsimp"></a>public <a href="polygonoptions.md">PolygonOptions</a> add(<a href="latlng.md">LatLng</a>... points)</p>
<p id="p1914012579520"><a name="p1914012579520"></a><a name="p1914012579520"></a>Sets multiple vertices of a polygon.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table18617mcpsimp"></a>
<table><thead align="left"><tr id="row18622mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p18624mcpsimp"><a name="p18624mcpsimp"></a><a name="p18624mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p18626mcpsimp"><a name="p18626mcpsimp"></a><a name="p18626mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row18627mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p18629mcpsimp"><a name="p18629mcpsimp"></a><a name="p18629mcpsimp"></a>points</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p18631mcpsimp"><a name="p18631mcpsimp"></a><a name="p18631mcpsimp"></a>Coordinates of multiple vertices.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table18634mcpsimp"></a>
<table><thead align="left"><tr id="row18639mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p18641mcpsimp"><a name="p18641mcpsimp"></a><a name="p18641mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p18643mcpsimp"><a name="p18643mcpsimp"></a><a name="p18643mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row18644mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p18646mcpsimp"><a name="p18646mcpsimp"></a><a name="p18646mcpsimp"></a>PolygonOptions</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p18648mcpsimp"><a name="p18648mcpsimp"></a><a name="p18648mcpsimp"></a><a href="polygonoptions.md">PolygonOptions</a> object containing the specified vertices.</p>
</td>
</tr>
</tbody>
</table>

## add\(LatLng point\)<a name="section1019721914520"></a>

<a name="table18650mcpsimp"></a>
<table><thead align="left"><tr id="row18654mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p18656mcpsimp"><a name="p18656mcpsimp"></a><a name="p18656mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row18657mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p18659mcpsimp"><a name="p18659mcpsimp"></a><a name="p18659mcpsimp"></a>public <a href="polygonoptions.md">PolygonOptions</a> add(<a href="latlng.md">LatLng</a> point)</p>
<p id="p1025467525"><a name="p1025467525"></a><a name="p1025467525"></a>Adds a vertex to a polygon.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table18665mcpsimp"></a>
<table><thead align="left"><tr id="row18670mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p18672mcpsimp"><a name="p18672mcpsimp"></a><a name="p18672mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p18674mcpsimp"><a name="p18674mcpsimp"></a><a name="p18674mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row18675mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p18677mcpsimp"><a name="p18677mcpsimp"></a><a name="p18677mcpsimp"></a>point</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p18679mcpsimp"><a name="p18679mcpsimp"></a><a name="p18679mcpsimp"></a>Coordinates of a vertex.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table18682mcpsimp"></a>
<table><thead align="left"><tr id="row18687mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p18689mcpsimp"><a name="p18689mcpsimp"></a><a name="p18689mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p18691mcpsimp"><a name="p18691mcpsimp"></a><a name="p18691mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row18692mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p18694mcpsimp"><a name="p18694mcpsimp"></a><a name="p18694mcpsimp"></a>PolygonOptions</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p18696mcpsimp"><a name="p18696mcpsimp"></a><a name="p18696mcpsimp"></a><a href="polygonoptions.md">PolygonOptions</a> object containing the specified vertex.</p>
</td>
</tr>
</tbody>
</table>

## addAll<a name="section11151141725712"></a>

<a name="table18698mcpsimp"></a>
<table><thead align="left"><tr id="row18702mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p18704mcpsimp"><a name="p18704mcpsimp"></a><a name="p18704mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row18705mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p18707mcpsimp"><a name="p18707mcpsimp"></a><a name="p18707mcpsimp"></a>public <a href="polygonoptions.md">PolygonOptions</a> addAll(Iterable&lt;<a href="latlng.md">LatLng</a>&gt; points)</p>
<p id="p18710mcpsimp"><a name="p18710mcpsimp"></a><a name="p18710mcpsimp"></a>Adds multiple vertices to a polygon.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table18713mcpsimp"></a>
<table><thead align="left"><tr id="row18718mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p18720mcpsimp"><a name="p18720mcpsimp"></a><a name="p18720mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p18722mcpsimp"><a name="p18722mcpsimp"></a><a name="p18722mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row18723mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p18725mcpsimp"><a name="p18725mcpsimp"></a><a name="p18725mcpsimp"></a>points</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p18727mcpsimp"><a name="p18727mcpsimp"></a><a name="p18727mcpsimp"></a>Multiple vertices.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table18730mcpsimp"></a>
<table><thead align="left"><tr id="row18735mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p18737mcpsimp"><a name="p18737mcpsimp"></a><a name="p18737mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p18739mcpsimp"><a name="p18739mcpsimp"></a><a name="p18739mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row18740mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p18742mcpsimp"><a name="p18742mcpsimp"></a><a name="p18742mcpsimp"></a>PolygonOptions</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p18744mcpsimp"><a name="p18744mcpsimp"></a><a name="p18744mcpsimp"></a><a href="polygonoptions.md">PolygonOptions</a> object containing the specified vertices.</p>
</td>
</tr>
</tbody>
</table>

## addHole<a name="section874319100586"></a>

<a name="table18746mcpsimp"></a>
<table><thead align="left"><tr id="row18750mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p18752mcpsimp"><a name="p18752mcpsimp"></a><a name="p18752mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row18753mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p18755mcpsimp"><a name="p18755mcpsimp"></a><a name="p18755mcpsimp"></a>public <a href="polygonoptions.md">PolygonOptions</a> addHole(Iterable&lt;<a href="latlng.md">LatLng</a>&gt; points)</p>
<p id="p071842514588"><a name="p071842514588"></a><a name="p071842514588"></a>Adds multiple holes to a polygon.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table18761mcpsimp"></a>
<table><thead align="left"><tr id="row18766mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p18768mcpsimp"><a name="p18768mcpsimp"></a><a name="p18768mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p18770mcpsimp"><a name="p18770mcpsimp"></a><a name="p18770mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row18771mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p18773mcpsimp"><a name="p18773mcpsimp"></a><a name="p18773mcpsimp"></a>points</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p18775mcpsimp"><a name="p18775mcpsimp"></a><a name="p18775mcpsimp"></a>Multiple holes.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table18778mcpsimp"></a>
<table><thead align="left"><tr id="row18783mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p18785mcpsimp"><a name="p18785mcpsimp"></a><a name="p18785mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p18787mcpsimp"><a name="p18787mcpsimp"></a><a name="p18787mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row18788mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p18790mcpsimp"><a name="p18790mcpsimp"></a><a name="p18790mcpsimp"></a>PolygonOptions</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p18792mcpsimp"><a name="p18792mcpsimp"></a><a name="p18792mcpsimp"></a><a href="polygonoptions.md">PolygonOptions</a> object containing multiple specified holes.</p>
</td>
</tr>
</tbody>
</table>

## clickable<a name="section12764124915819"></a>

<a name="table18794mcpsimp"></a>
<table><thead align="left"><tr id="row18798mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p18800mcpsimp"><a name="p18800mcpsimp"></a><a name="p18800mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row18801mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p18803mcpsimp"><a name="p18803mcpsimp"></a><a name="p18803mcpsimp"></a>public <a href="polygonoptions.md">PolygonOptions</a> clickable(boolean clickable)</p>
<p id="p18806mcpsimp"><a name="p18806mcpsimp"></a><a name="p18806mcpsimp"></a>Sets whether a polygon is tappable.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table18809mcpsimp"></a>
<table><thead align="left"><tr id="row18814mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p18816mcpsimp"><a name="p18816mcpsimp"></a><a name="p18816mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p18818mcpsimp"><a name="p18818mcpsimp"></a><a name="p18818mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row18819mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p18821mcpsimp"><a name="p18821mcpsimp"></a><a name="p18821mcpsimp"></a>clickable</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p18823mcpsimp"><a name="p18823mcpsimp"></a><a name="p18823mcpsimp"></a>Indicates whether a polygon is tappable. <strong id="b65234144215"><a name="b65234144215"></a><a name="b65234144215"></a>true</strong>: yes; <strong id="b135241146212"><a name="b135241146212"></a><a name="b135241146212"></a>false</strong> (default): no. </p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table18826mcpsimp"></a>
<table><thead align="left"><tr id="row18831mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p18833mcpsimp"><a name="p18833mcpsimp"></a><a name="p18833mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p18835mcpsimp"><a name="p18835mcpsimp"></a><a name="p18835mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row18836mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p18838mcpsimp"><a name="p18838mcpsimp"></a><a name="p18838mcpsimp"></a>PolygonOptions</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p18840mcpsimp"><a name="p18840mcpsimp"></a><a name="p18840mcpsimp"></a><a href="polygonoptions.md">PolygonOptions</a> object with the new tappability setting.</p>
</td>
</tr>
</tbody>
</table>

## fillColor<a name="section129413288114"></a>

<a name="table18842mcpsimp"></a>
<table><thead align="left"><tr id="row18846mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p18848mcpsimp"><a name="p18848mcpsimp"></a><a name="p18848mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row18849mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p18851mcpsimp"><a name="p18851mcpsimp"></a><a name="p18851mcpsimp"></a>public <a href="polygonoptions.md">PolygonOptions</a> fillColor(int color)</p>
<p id="p18854mcpsimp"><a name="p18854mcpsimp"></a><a name="p18854mcpsimp"></a>Sets the fill color of a polygon.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table18857mcpsimp"></a>
<table><thead align="left"><tr id="row18862mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p18864mcpsimp"><a name="p18864mcpsimp"></a><a name="p18864mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p18866mcpsimp"><a name="p18866mcpsimp"></a><a name="p18866mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row18867mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p18869mcpsimp"><a name="p18869mcpsimp"></a><a name="p18869mcpsimp"></a>color</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p18871mcpsimp"><a name="p18871mcpsimp"></a><a name="p18871mcpsimp"></a>Color in ARGB format. By default, the fill color is transparent (0x00000000).</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table18874mcpsimp"></a>
<table><thead align="left"><tr id="row18879mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p18881mcpsimp"><a name="p18881mcpsimp"></a><a name="p18881mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p18883mcpsimp"><a name="p18883mcpsimp"></a><a name="p18883mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row18884mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p18886mcpsimp"><a name="p18886mcpsimp"></a><a name="p18886mcpsimp"></a>PolygonOptions</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p18888mcpsimp"><a name="p18888mcpsimp"></a><a name="p18888mcpsimp"></a><a href="polygonoptions.md">PolygonOptions</a> object with the new fill color.</p>
</td>
</tr>
</tbody>
</table>

## geodesic<a name="section01622087214"></a>

<a name="table18890mcpsimp"></a>
<table><thead align="left"><tr id="row18894mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p18896mcpsimp"><a name="p18896mcpsimp"></a><a name="p18896mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row18897mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p18899mcpsimp"><a name="p18899mcpsimp"></a><a name="p18899mcpsimp"></a>public <a href="polygonoptions.md">PolygonOptions</a> geodesic(boolean geodesic)</p>
<p id="p11149628427"><a name="p11149628427"></a><a name="p11149628427"></a>Sets whether to draw each segment of a polygon as a geodesic.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table18905mcpsimp"></a>
<table><thead align="left"><tr id="row18910mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p18912mcpsimp"><a name="p18912mcpsimp"></a><a name="p18912mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p18914mcpsimp"><a name="p18914mcpsimp"></a><a name="p18914mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row18915mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p18917mcpsimp"><a name="p18917mcpsimp"></a><a name="p18917mcpsimp"></a>geodesic</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p18919mcpsimp"><a name="p18919mcpsimp"></a><a name="p18919mcpsimp"></a>Indicates whether to draw each segment of a polygon as a geodesic. <strong id="b5698105812124"><a name="b5698105812124"></a><a name="b5698105812124"></a>true</strong>: yes; <strong id="b1670812583127"><a name="b1670812583127"></a><a name="b1670812583127"></a>false</strong>: no. The default value is <strong id="b20720115018112"><a name="b20720115018112"></a><a name="b20720115018112"></a>false</strong>.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table18922mcpsimp"></a>
<table><thead align="left"><tr id="row18927mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p18929mcpsimp"><a name="p18929mcpsimp"></a><a name="p18929mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p18931mcpsimp"><a name="p18931mcpsimp"></a><a name="p18931mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row18932mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p18934mcpsimp"><a name="p18934mcpsimp"></a><a name="p18934mcpsimp"></a>PolygonOptions</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p18936mcpsimp"><a name="p18936mcpsimp"></a><a name="p18936mcpsimp"></a><a href="polygonoptions.md">PolygonOptions</a> object with the new <strong id="b1561710721310"><a name="b1561710721310"></a><a name="b1561710721310"></a>geodesic</strong> attribute setting.</p>
</td>
</tr>
</tbody>
</table>

## getFillColor<a name="section411713436217"></a>

<a name="table18938mcpsimp"></a>
<table><thead align="left"><tr id="row18942mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p18944mcpsimp"><a name="p18944mcpsimp"></a><a name="p18944mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row18945mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p18947mcpsimp"><a name="p18947mcpsimp"></a><a name="p18947mcpsimp"></a>public int getFillColor()</p>
<p id="p1774216551927"><a name="p1774216551927"></a><a name="p1774216551927"></a>Obtains the fill color of a polygon.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table18956mcpsimp"></a>
<table><thead align="left"><tr id="row18961mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p18963mcpsimp"><a name="p18963mcpsimp"></a><a name="p18963mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p18965mcpsimp"><a name="p18965mcpsimp"></a><a name="p18965mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row18966mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p18968mcpsimp"><a name="p18968mcpsimp"></a><a name="p18968mcpsimp"></a>int</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p18970mcpsimp"><a name="p18970mcpsimp"></a><a name="p18970mcpsimp"></a>Color in ARGB format.</p>
</td>
</tr>
</tbody>
</table>

## getHoles<a name="section1110712151531"></a>

<a name="table18972mcpsimp"></a>
<table><thead align="left"><tr id="row18976mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p18978mcpsimp"><a name="p18978mcpsimp"></a><a name="p18978mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row18979mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p18981mcpsimp"><a name="p18981mcpsimp"></a><a name="p18981mcpsimp"></a>public List&lt;List&lt;<a href="latlng.md">LatLng</a>&gt;&gt; getHoles()</p>
<p id="p18984mcpsimp"><a name="p18984mcpsimp"></a><a name="p18984mcpsimp"></a>Obtains holes in a polygon on a map.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table18990mcpsimp"></a>
<table><thead align="left"><tr id="row18995mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p18997mcpsimp"><a name="p18997mcpsimp"></a><a name="p18997mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p18999mcpsimp"><a name="p18999mcpsimp"></a><a name="p18999mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row19000mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p19002mcpsimp"><a name="p19002mcpsimp"></a><a name="p19002mcpsimp"></a>List&lt;List&lt;<a href="latlng.md">LatLng</a>&gt;&gt;</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p19004mcpsimp"><a name="p19004mcpsimp"></a><a name="p19004mcpsimp"></a>Holes in a polygon.</p>
</td>
</tr>
</tbody>
</table>

## getPoints<a name="section915202713413"></a>

<a name="table19006mcpsimp"></a>
<table><thead align="left"><tr id="row19010mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p19012mcpsimp"><a name="p19012mcpsimp"></a><a name="p19012mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row19013mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p19015mcpsimp"><a name="p19015mcpsimp"></a><a name="p19015mcpsimp"></a>public List&lt;<a href="latlng.md">LatLng</a>&gt; getPoints()</p>
<p id="p19781164614415"><a name="p19781164614415"></a><a name="p19781164614415"></a>Obtains all vertices of a polygon.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table19024mcpsimp"></a>
<table><thead align="left"><tr id="row19029mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p19031mcpsimp"><a name="p19031mcpsimp"></a><a name="p19031mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p19033mcpsimp"><a name="p19033mcpsimp"></a><a name="p19033mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row19034mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p19036mcpsimp"><a name="p19036mcpsimp"></a><a name="p19036mcpsimp"></a>List&lt;<a href="latlng.md">LatLng</a>&gt;</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p19038mcpsimp"><a name="p19038mcpsimp"></a><a name="p19038mcpsimp"></a>All vertices of a polygon.</p>
</td>
</tr>
</tbody>
</table>

## getStrokeColor<a name="section13591484311"></a>

<a name="table19040mcpsimp"></a>
<table><thead align="left"><tr id="row19044mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p19046mcpsimp"><a name="p19046mcpsimp"></a><a name="p19046mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row19047mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p19049mcpsimp"><a name="p19049mcpsimp"></a><a name="p19049mcpsimp"></a>public int getStrokeColor()</p>
<p id="p1812616218412"><a name="p1812616218412"></a><a name="p1812616218412"></a>Obtains the stroke color of a polygon's outline, in ARGB format.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table19058mcpsimp"></a>
<table><thead align="left"><tr id="row19063mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p19065mcpsimp"><a name="p19065mcpsimp"></a><a name="p19065mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p19067mcpsimp"><a name="p19067mcpsimp"></a><a name="p19067mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row19068mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p19070mcpsimp"><a name="p19070mcpsimp"></a><a name="p19070mcpsimp"></a>int</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p19072mcpsimp"><a name="p19072mcpsimp"></a><a name="p19072mcpsimp"></a>Color in ARGB format.</p>
</td>
</tr>
</tbody>
</table>

## getStrokeJointType<a name="section143841310959"></a>

<a name="table19074mcpsimp"></a>
<table><thead align="left"><tr id="row19078mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p19080mcpsimp"><a name="p19080mcpsimp"></a><a name="p19080mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row19081mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p19083mcpsimp"><a name="p19083mcpsimp"></a><a name="p19083mcpsimp"></a>public int getStrokeJointType()</p>
<p id="p935192416519"><a name="p935192416519"></a><a name="p935192416519"></a>Obtains the joint type of a polygon.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table19094mcpsimp"></a>
<table><thead align="left"><tr id="row19099mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p19101mcpsimp"><a name="p19101mcpsimp"></a><a name="p19101mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p19103mcpsimp"><a name="p19103mcpsimp"></a><a name="p19103mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row19104mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p19106mcpsimp"><a name="p19106mcpsimp"></a><a name="p19106mcpsimp"></a>int</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p19108mcpsimp"><a name="p19108mcpsimp"></a><a name="p19108mcpsimp"></a>Joint type of a polygon.</p>
</td>
</tr>
</tbody>
</table>

## getStrokePattern<a name="section1473217443519"></a>

<a name="table19110mcpsimp"></a>
<table><thead align="left"><tr id="row19114mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p19116mcpsimp"><a name="p19116mcpsimp"></a><a name="p19116mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row19117mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p19119mcpsimp"><a name="p19119mcpsimp"></a><a name="p19119mcpsimp"></a>public List&lt;<a href="patternitem.md">PatternItem</a>&gt; getStrokePattern()</p>
<p id="p1754691668"><a name="p1754691668"></a><a name="p1754691668"></a>Obtains the stroke pattern of a polygon's outline.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table19128mcpsimp"></a>
<table><thead align="left"><tr id="row19133mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p19135mcpsimp"><a name="p19135mcpsimp"></a><a name="p19135mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p19137mcpsimp"><a name="p19137mcpsimp"></a><a name="p19137mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row19138mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p19140mcpsimp"><a name="p19140mcpsimp"></a><a name="p19140mcpsimp"></a>List&lt;<a href="patternitem.md">PatternItem</a>&gt;</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p19142mcpsimp"><a name="p19142mcpsimp"></a><a name="p19142mcpsimp"></a>Stroke pattern of a polygon's outline.</p>
</td>
</tr>
</tbody>
</table>

## getStrokeWidth<a name="section1163341714618"></a>

<a name="table19144mcpsimp"></a>
<table><thead align="left"><tr id="row19148mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p19150mcpsimp"><a name="p19150mcpsimp"></a><a name="p19150mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row19151mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p19153mcpsimp"><a name="p19153mcpsimp"></a><a name="p19153mcpsimp"></a>public float getStrokeWidth()</p>
<p id="p19156mcpsimp"><a name="p19156mcpsimp"></a><a name="p19156mcpsimp"></a>Obtains the stroke width of a polygon's outline.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table19162mcpsimp"></a>
<table><thead align="left"><tr id="row19167mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p19169mcpsimp"><a name="p19169mcpsimp"></a><a name="p19169mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p19171mcpsimp"><a name="p19171mcpsimp"></a><a name="p19171mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row19172mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p19174mcpsimp"><a name="p19174mcpsimp"></a><a name="p19174mcpsimp"></a>float</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p19176mcpsimp"><a name="p19176mcpsimp"></a><a name="p19176mcpsimp"></a>Stroke width of a polygon's outline, in pixels.</p>
</td>
</tr>
</tbody>
</table>

## getZIndex<a name="section1562365314616"></a>

<a name="table19178mcpsimp"></a>
<table><thead align="left"><tr id="row19182mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p19184mcpsimp"><a name="p19184mcpsimp"></a><a name="p19184mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row19185mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p19187mcpsimp"><a name="p19187mcpsimp"></a><a name="p19187mcpsimp"></a>public float getZIndex()</p>
<p id="p20610141477"><a name="p20610141477"></a><a name="p20610141477"></a>Obtains the z-index of a polygon.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table19196mcpsimp"></a>
<table><thead align="left"><tr id="row19201mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p19203mcpsimp"><a name="p19203mcpsimp"></a><a name="p19203mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p19205mcpsimp"><a name="p19205mcpsimp"></a><a name="p19205mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row19206mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p19208mcpsimp"><a name="p19208mcpsimp"></a><a name="p19208mcpsimp"></a>float</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p19210mcpsimp"><a name="p19210mcpsimp"></a><a name="p19210mcpsimp"></a>Z-index, which indicates the overlapping order of a polygon.</p>
</td>
</tr>
</tbody>
</table>

## isClickable<a name="section1550811171973"></a>

<a name="table19212mcpsimp"></a>
<table><thead align="left"><tr id="row19216mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p19218mcpsimp"><a name="p19218mcpsimp"></a><a name="p19218mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row19219mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p19221mcpsimp"><a name="p19221mcpsimp"></a><a name="p19221mcpsimp"></a>public boolean isClickable()</p>
<p id="p19224mcpsimp"><a name="p19224mcpsimp"></a><a name="p19224mcpsimp"></a>Checks whether a polygon is tappable.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table19230mcpsimp"></a>
<table><thead align="left"><tr id="row19235mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p19237mcpsimp"><a name="p19237mcpsimp"></a><a name="p19237mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p19239mcpsimp"><a name="p19239mcpsimp"></a><a name="p19239mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row19240mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p19242mcpsimp"><a name="p19242mcpsimp"></a><a name="p19242mcpsimp"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p19244mcpsimp"><a name="p19244mcpsimp"></a><a name="p19244mcpsimp"></a><strong id="b169292712153"><a name="b169292712153"></a><a name="b169292712153"></a>true</strong> if a polygon is tappable; <strong id="b1692121961519"><a name="b1692121961519"></a><a name="b1692121961519"></a>false</strong> otherwise.</p>
</td>
</tr>
</tbody>
</table>

## isGeodesic<a name="section79861851571"></a>

<a name="table19246mcpsimp"></a>
<table><thead align="left"><tr id="row19250mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p19252mcpsimp"><a name="p19252mcpsimp"></a><a name="p19252mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row19253mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p19255mcpsimp"><a name="p19255mcpsimp"></a><a name="p19255mcpsimp"></a>public boolean isGeodesic()</p>
<p id="p19258mcpsimp"><a name="p19258mcpsimp"></a><a name="p19258mcpsimp"></a>Checks whether each segment of a polygon is drawn as a geodesic.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table19264mcpsimp"></a>
<table><thead align="left"><tr id="row19269mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p19271mcpsimp"><a name="p19271mcpsimp"></a><a name="p19271mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p19273mcpsimp"><a name="p19273mcpsimp"></a><a name="p19273mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row19274mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p19276mcpsimp"><a name="p19276mcpsimp"></a><a name="p19276mcpsimp"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p19278mcpsimp"><a name="p19278mcpsimp"></a><a name="p19278mcpsimp"></a><strong id="b1850065613158"><a name="b1850065613158"></a><a name="b1850065613158"></a>true</strong> if each segment is drawn as a geodesic; <strong id="b1551465614158"><a name="b1551465614158"></a><a name="b1551465614158"></a>false</strong> otherwise.</p>
</td>
</tr>
</tbody>
</table>

## isVisible<a name="section161543191689"></a>

<a name="table19280mcpsimp"></a>
<table><thead align="left"><tr id="row19284mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p19286mcpsimp"><a name="p19286mcpsimp"></a><a name="p19286mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row19287mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p19289mcpsimp"><a name="p19289mcpsimp"></a><a name="p19289mcpsimp"></a>public boolean isVisible()</p>
<p id="p1218311346813"><a name="p1218311346813"></a><a name="p1218311346813"></a>Checks whether a polygon is visible.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table19298mcpsimp"></a>
<table><thead align="left"><tr id="row19303mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p19305mcpsimp"><a name="p19305mcpsimp"></a><a name="p19305mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p19307mcpsimp"><a name="p19307mcpsimp"></a><a name="p19307mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row19308mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p19310mcpsimp"><a name="p19310mcpsimp"></a><a name="p19310mcpsimp"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p19312mcpsimp"><a name="p19312mcpsimp"></a><a name="p19312mcpsimp"></a><strong id="b75491104169"><a name="b75491104169"></a><a name="b75491104169"></a>true</strong> if the polygon is visible; <strong id="b1356381081617"><a name="b1356381081617"></a><a name="b1356381081617"></a>false</strong> otherwise.</p>
</td>
</tr>
</tbody>
</table>

## strokeColor<a name="section147551851285"></a>

<a name="table19314mcpsimp"></a>
<table><thead align="left"><tr id="row19318mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p19320mcpsimp"><a name="p19320mcpsimp"></a><a name="p19320mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row19321mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p19323mcpsimp"><a name="p19323mcpsimp"></a><a name="p19323mcpsimp"></a>public <a href="polygonoptions.md">PolygonOptions</a> strokeColor(int color)</p>
<p id="p19533819917"><a name="p19533819917"></a><a name="p19533819917"></a>Sets the stroke color of a polygon's outline.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table19329mcpsimp"></a>
<table><thead align="left"><tr id="row19334mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p19336mcpsimp"><a name="p19336mcpsimp"></a><a name="p19336mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p19338mcpsimp"><a name="p19338mcpsimp"></a><a name="p19338mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row19339mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p19341mcpsimp"><a name="p19341mcpsimp"></a><a name="p19341mcpsimp"></a>color</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p19343mcpsimp"><a name="p19343mcpsimp"></a><a name="p19343mcpsimp"></a>Color in ARGB format. By default, the stroke color is black (0xff000000).</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table19346mcpsimp"></a>
<table><thead align="left"><tr id="row19351mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p19353mcpsimp"><a name="p19353mcpsimp"></a><a name="p19353mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p19355mcpsimp"><a name="p19355mcpsimp"></a><a name="p19355mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row19356mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p19358mcpsimp"><a name="p19358mcpsimp"></a><a name="p19358mcpsimp"></a>PolygonOptions</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p19360mcpsimp"><a name="p19360mcpsimp"></a><a name="p19360mcpsimp"></a><a href="polygonoptions.md">PolygonOptions</a> object with the new outline stroke color.</p>
</td>
</tr>
</tbody>
</table>

## strokeJointType<a name="section590852719910"></a>

<a name="table19362mcpsimp"></a>
<table><thead align="left"><tr id="row19366mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p19368mcpsimp"><a name="p19368mcpsimp"></a><a name="p19368mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row19369mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p19371mcpsimp"><a name="p19371mcpsimp"></a><a name="p19371mcpsimp"></a>public <a href="polygonoptions.md">PolygonOptions</a> strokeJointType(int jointType)</p>
<p id="p112444218913"><a name="p112444218913"></a><a name="p112444218913"></a>Sets the joint type of a polygon.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table19377mcpsimp"></a>
<table><thead align="left"><tr id="row19382mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p19384mcpsimp"><a name="p19384mcpsimp"></a><a name="p19384mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p19386mcpsimp"><a name="p19386mcpsimp"></a><a name="p19386mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row19387mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p19389mcpsimp"><a name="p19389mcpsimp"></a><a name="p19389mcpsimp"></a>jointType</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p19391mcpsimp"><a name="p19391mcpsimp"></a><a name="p19391mcpsimp"></a>Joint type. The default value is <a href="jointtype.md#section103572813326">DEFAULT</a>.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table19394mcpsimp"></a>
<table><thead align="left"><tr id="row19399mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p19401mcpsimp"><a name="p19401mcpsimp"></a><a name="p19401mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p19403mcpsimp"><a name="p19403mcpsimp"></a><a name="p19403mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row19404mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p19406mcpsimp"><a name="p19406mcpsimp"></a><a name="p19406mcpsimp"></a>PolygonOptions</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p19408mcpsimp"><a name="p19408mcpsimp"></a><a name="p19408mcpsimp"></a><a href="polygonoptions.md">PolygonOptions</a> object with the new joint type.</p>
</td>
</tr>
</tbody>
</table>

## strokePattern<a name="section55016211102"></a>

<a name="table19410mcpsimp"></a>
<table><thead align="left"><tr id="row19414mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p19416mcpsimp"><a name="p19416mcpsimp"></a><a name="p19416mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row19417mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p19419mcpsimp"><a name="p19419mcpsimp"></a><a name="p19419mcpsimp"></a>public <a href="polygonoptions.md">PolygonOptions</a> strokePattern(List&lt;<a href="patternitem.md">PatternItem</a>&gt; pattern)</p>
<p id="p4459181711103"><a name="p4459181711103"></a><a name="p4459181711103"></a>Sets the stroke pattern of a polygon's outline.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table19425mcpsimp"></a>
<table><thead align="left"><tr id="row19430mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p19432mcpsimp"><a name="p19432mcpsimp"></a><a name="p19432mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p19434mcpsimp"><a name="p19434mcpsimp"></a><a name="p19434mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row19435mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p19437mcpsimp"><a name="p19437mcpsimp"></a><a name="p19437mcpsimp"></a>pattern</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p19439mcpsimp"><a name="p19439mcpsimp"></a><a name="p19439mcpsimp"></a><a href="patternitem.md">PatternItem</a> object set. The default value is <strong id="b31534364414"><a name="b31534364414"></a><a name="b31534364414"></a>null</strong>, indicating that the stroke is in the solid pattern. </p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table19442mcpsimp"></a>
<table><thead align="left"><tr id="row19447mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p19449mcpsimp"><a name="p19449mcpsimp"></a><a name="p19449mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p19451mcpsimp"><a name="p19451mcpsimp"></a><a name="p19451mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row19452mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p19454mcpsimp"><a name="p19454mcpsimp"></a><a name="p19454mcpsimp"></a>PolygonOptions</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p19456mcpsimp"><a name="p19456mcpsimp"></a><a name="p19456mcpsimp"></a><a href="polygonoptions.md">PolygonOptions</a> object with the new outline pattern.</p>
</td>
</tr>
</tbody>
</table>

## strokeWidth<a name="section208221238141011"></a>

<a name="table19458mcpsimp"></a>
<table><thead align="left"><tr id="row19462mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p19464mcpsimp"><a name="p19464mcpsimp"></a><a name="p19464mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row19465mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p19467mcpsimp"><a name="p19467mcpsimp"></a><a name="p19467mcpsimp"></a>public <a href="polygonoptions.md">PolygonOptions</a> strokeWidth(float width)</p>
<p id="p18788255141013"><a name="p18788255141013"></a><a name="p18788255141013"></a>Sets the stroke width of a polygon's outline.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table19473mcpsimp"></a>
<table><thead align="left"><tr id="row19478mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p19480mcpsimp"><a name="p19480mcpsimp"></a><a name="p19480mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p19482mcpsimp"><a name="p19482mcpsimp"></a><a name="p19482mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row19483mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p19485mcpsimp"><a name="p19485mcpsimp"></a><a name="p19485mcpsimp"></a>width</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p19487mcpsimp"><a name="p19487mcpsimp"></a><a name="p19487mcpsimp"></a>Stroke width of a polygon's outline, in pixels. The default value is <strong id="b10227123131819"><a name="b10227123131819"></a><a name="b10227123131819"></a>10</strong>.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table19490mcpsimp"></a>
<table><thead align="left"><tr id="row19495mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p19497mcpsimp"><a name="p19497mcpsimp"></a><a name="p19497mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p19499mcpsimp"><a name="p19499mcpsimp"></a><a name="p19499mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row19500mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p19502mcpsimp"><a name="p19502mcpsimp"></a><a name="p19502mcpsimp"></a>PolygonOptions</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p19504mcpsimp"><a name="p19504mcpsimp"></a><a name="p19504mcpsimp"></a><a href="polygonoptions.md">PolygonOptions</a> object with the new outline stroke width.</p>
</td>
</tr>
</tbody>
</table>

## visible<a name="section128711841191217"></a>

<a name="table19506mcpsimp"></a>
<table><thead align="left"><tr id="row19510mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p19512mcpsimp"><a name="p19512mcpsimp"></a><a name="p19512mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row19513mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p19515mcpsimp"><a name="p19515mcpsimp"></a><a name="p19515mcpsimp"></a>public <a href="polygonoptions.md">PolygonOptions</a> visible(boolean visible)</p>
<p id="p19518mcpsimp"><a name="p19518mcpsimp"></a><a name="p19518mcpsimp"></a>Sets whether a polygon is visible. If the polygon is invisible, it will not be drawn but all other states will be preserved.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table19521mcpsimp"></a>
<table><thead align="left"><tr id="row19526mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p19528mcpsimp"><a name="p19528mcpsimp"></a><a name="p19528mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p19530mcpsimp"><a name="p19530mcpsimp"></a><a name="p19530mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row19531mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p19533mcpsimp"><a name="p19533mcpsimp"></a><a name="p19533mcpsimp"></a>visible</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p19535mcpsimp"><a name="p19535mcpsimp"></a><a name="p19535mcpsimp"></a>Indicates whether a polygon is visible. By default, a polygon is visible.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table19538mcpsimp"></a>
<table><thead align="left"><tr id="row19543mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p19545mcpsimp"><a name="p19545mcpsimp"></a><a name="p19545mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p19547mcpsimp"><a name="p19547mcpsimp"></a><a name="p19547mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row19548mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p19550mcpsimp"><a name="p19550mcpsimp"></a><a name="p19550mcpsimp"></a>PolygonOptions</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p19552mcpsimp"><a name="p19552mcpsimp"></a><a name="p19552mcpsimp"></a><a href="polygonoptions.md">PolygonOptions</a> object with the new visibility setting.</p>
</td>
</tr>
</tbody>
</table>

## zIndex<a name="section98173041518"></a>

<a name="table19554mcpsimp"></a>
<table><thead align="left"><tr id="row19558mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p19560mcpsimp"><a name="p19560mcpsimp"></a><a name="p19560mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row19561mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p19563mcpsimp"><a name="p19563mcpsimp"></a><a name="p19563mcpsimp"></a>public <a href="polygonoptions.md">PolygonOptions</a> zIndex(float zIndex)</p>
<p id="p19566mcpsimp"><a name="p19566mcpsimp"></a><a name="p19566mcpsimp"></a>Sets the z-index of a polygon. The z-index indicates the overlapping order of a polygon. A polygon with a larger z-index overlaps that with a smaller z-index. Polygons with the same z-index overlap each other by the order in which they are added.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table19569mcpsimp"></a>
<table><thead align="left"><tr id="row19574mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p19576mcpsimp"><a name="p19576mcpsimp"></a><a name="p19576mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p19578mcpsimp"><a name="p19578mcpsimp"></a><a name="p19578mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row19579mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p19581mcpsimp"><a name="p19581mcpsimp"></a><a name="p19581mcpsimp"></a>zIndex</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p19583mcpsimp"><a name="p19583mcpsimp"></a><a name="p19583mcpsimp"></a>Z-index, which indicates the overlapping order of a polygon. By default, the z-index is 0.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table19586mcpsimp"></a>
<table><thead align="left"><tr id="row19591mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p19593mcpsimp"><a name="p19593mcpsimp"></a><a name="p19593mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p19595mcpsimp"><a name="p19595mcpsimp"></a><a name="p19595mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row19596mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p19598mcpsimp"><a name="p19598mcpsimp"></a><a name="p19598mcpsimp"></a>PolygonOptions</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p19600mcpsimp"><a name="p19600mcpsimp"></a><a name="p19600mcpsimp"></a><a href="polygonoptions.md">PolygonOptions</a> object with the new z-index.</p>
</td>
</tr>
</tbody>
</table>

