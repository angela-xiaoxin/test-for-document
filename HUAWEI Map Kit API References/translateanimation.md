# TranslateAnimation<a name="EN-US_TOPIC_0000001099181274"></a>

-   [Public Constructor Summary](#section186641616203)
-   [Public Method Summary](#section1230414213220)
-   [Public Constructors](#section042681119126)
-   [TranslateAnimation](#section147561345184912)
-   [Public Methods](#section178075662915)
-   [getDuration](#section7666825286)
-   [getInterpolator](#section185831855102315)
-   [getTarget](#section177511713191)
-   [setDuration](#section11704105017376)
-   [setInterpolator](#section92301125931)


<a name="table22004mcpsimp"></a>
<table><thead align="left"><tr id="row22008mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p22010mcpsimp"><a name="p22010mcpsimp"></a><a name="p22010mcpsimp"></a>Class Info</p>
</th>
</tr>
</thead>
<tbody><tr id="row22011mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p1290783718377"><a name="p1290783718377"></a><a name="p1290783718377"></a>public class TranslateAnimation extends Animation</p>
<p id="p1097894811125"><a name="p1097894811125"></a><a name="p1097894811125"></a>A class that controls the animation movement.</p>
</td>
</tr>
</tbody>
</table>

## Public Constructor Summary<a name="section186641616203"></a>

<a name="table6451mcpsimp"></a>
<table><thead align="left"><tr id="row6455mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p6457mcpsimp"><a name="p6457mcpsimp"></a><a name="p6457mcpsimp"></a>Constructor Name</p>
</th>
</tr>
</thead>
<tbody><tr id="row6458mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p143196311741"><a name="p143196311741"></a><a name="p143196311741"></a><a href="#section147561345184912">TranslateAnimation</a>(<a href="latlng.md">LatLng</a> target)</p>
<p id="p10224559131613"><a name="p10224559131613"></a><a name="p10224559131613"></a>Creates a <a href="translateanimation.md">TranslateAnimation</a> object using the target latitude and longitude. </p>
</td>
</tr>
</tbody>
</table>

## Public Method Summary<a name="section1230414213220"></a>

<a name="table5738155010595"></a>
<table><thead align="left"><tr id="row9739145005913"><th class="cellrowborder" valign="top" width="35.77%" id="mcps1.1.3.1.1"><p id="p6469mcpsimp"><a name="p6469mcpsimp"></a><a name="p6469mcpsimp"></a>Qualifier and Type</p>
</th>
<th class="cellrowborder" valign="top" width="64.23%" id="mcps1.1.3.1.2"><p id="p6471mcpsimp"><a name="p6471mcpsimp"></a><a name="p6471mcpsimp"></a>Method Name and Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row7740350105918"><td class="cellrowborder" valign="top" width="35.77%" headers="mcps1.1.3.1.1 "><p id="p1961372311399"><a name="p1961372311399"></a><a name="p1961372311399"></a>long</p>
</td>
<td class="cellrowborder" valign="top" width="64.23%" headers="mcps1.1.3.1.2 "><p id="p2028716810404"><a name="p2028716810404"></a><a name="p2028716810404"></a><a href="#section7666825286">getDuration</a>()</p>
<p id="p19881195835412"><a name="p19881195835412"></a><a name="p19881195835412"></a>Obtains the animation duration.</p>
</td>
</tr>
<tr id="row0143457184013"><td class="cellrowborder" valign="top" width="35.77%" headers="mcps1.1.3.1.1 "><p id="p1460722303910"><a name="p1460722303910"></a><a name="p1460722303910"></a>Interpolator</p>
</td>
<td class="cellrowborder" valign="top" width="64.23%" headers="mcps1.1.3.1.2 "><p id="p9778576544"><a name="p9778576544"></a><a name="p9778576544"></a><a href="#section185831855102315">getInterpolator</a>()</p>
<p id="p58836710557"><a name="p58836710557"></a><a name="p58836710557"></a>Obtains an interpolator.</p>
</td>
</tr>
<tr id="row11218209411"><td class="cellrowborder" valign="top" width="35.77%" headers="mcps1.1.3.1.1 "><p id="p132201347519"><a name="p132201347519"></a><a name="p132201347519"></a><a href="latlng.md">LatLng</a></p>
</td>
<td class="cellrowborder" valign="top" width="64.23%" headers="mcps1.1.3.1.2 "><p id="p129691501956"><a name="p129691501956"></a><a name="p129691501956"></a><a href="#section177511713191">getTarget</a>()</p>
<p id="p1164161913555"><a name="p1164161913555"></a><a name="p1164161913555"></a>Obtains the movement target position.</p>
</td>
</tr>
<tr id="row1367311794110"><td class="cellrowborder" valign="top" width="35.77%" headers="mcps1.1.3.1.1 "><p id="p106015232395"><a name="p106015232395"></a><a name="p106015232395"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="64.23%" headers="mcps1.1.3.1.2 "><p id="p1782916310541"><a name="p1782916310541"></a><a name="p1782916310541"></a><a href="#section11704105017376">setDuration</a>(long duration)</p>
<p id="p1696152811551"><a name="p1696152811551"></a><a name="p1696152811551"></a>Sets the animation duration.</p>
</td>
</tr>
<tr id="row15766112116392"><td class="cellrowborder" valign="top" width="35.77%" headers="mcps1.1.3.1.1 "><p id="p5766172114391"><a name="p5766172114391"></a><a name="p5766172114391"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="64.23%" headers="mcps1.1.3.1.2 "><p id="p9478183695414"><a name="p9478183695414"></a><a name="p9478183695414"></a><a href="#section92301125931">setInterpolator</a>(Interpolator interpolator)</p>
<p id="p1839943965518"><a name="p1839943965518"></a><a name="p1839943965518"></a>Sets an animation interpolator.</p>
</td>
</tr>
</tbody>
</table>

## Public Constructors<a name="section042681119126"></a>

## TranslateAnimation<a name="section147561345184912"></a>

<a name="table227mcpsimp"></a>
<table><thead align="left"><tr id="row231mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p233mcpsimp"><a name="p233mcpsimp"></a><a name="p233mcpsimp"></a>Constructor</p>
</th>
</tr>
</thead>
<tbody><tr id="row235mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p11878931172514"><a name="p11878931172514"></a><a name="p11878931172514"></a>public <a href="#section147561345184912">TranslateAnimation</a>(<a href="latlng.md">LatLng</a> target)</p>
<p id="p7878173172511"><a name="p7878173172511"></a><a name="p7878173172511"></a>Creates a <a href="translateanimation.md">TranslateAnimation</a> object using the target latitude and longitude. </p>
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
<tbody><tr id="row255mcpsimp"><td class="cellrowborder" valign="top" width="43%" headers="mcps1.1.3.1.1 "><p id="p103021647181817"><a name="p103021647181817"></a><a name="p103021647181817"></a>target</p>
</td>
<td class="cellrowborder" valign="top" width="56.99999999999999%" headers="mcps1.1.3.1.2 "><p id="p20707102717141"><a name="p20707102717141"></a><a name="p20707102717141"></a>Latitude and longitude of the movement target position.</p>
</td>
</tr>
</tbody>
</table>

## Public Methods<a name="section178075662915"></a>

## getDuration<a name="section7666825286"></a>

<a name="table16669251683"></a>
<table><thead align="left"><tr id="row1666122520816"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p7666225187"><a name="p7666225187"></a><a name="p7666225187"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row1466616251782"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p1245820271142"><a name="p1245820271142"></a><a name="p1245820271142"></a>public long getDuration()</p>
<p id="p7667132513813"><a name="p7667132513813"></a><a name="p7667132513813"></a>Obtains the animation duration.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table1564520134204"></a>
<table><thead align="left"><tr id="row1564581312017"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p15645181318206"><a name="p15645181318206"></a><a name="p15645181318206"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p18645201352018"><a name="p18645201352018"></a><a name="p18645201352018"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row13646201352010"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p16463137207"><a name="p16463137207"></a><a name="p16463137207"></a>long</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p1664681392012"><a name="p1664681392012"></a><a name="p1664681392012"></a>Animation duration, in milliseconds.</p>
</td>
</tr>
</tbody>
</table>

## getInterpolator<a name="section185831855102315"></a>

<a name="table1658316559235"></a>
<table><thead align="left"><tr id="row19583185516236"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p658385517239"><a name="p658385517239"></a><a name="p658385517239"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row16583115514231"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p1258305592319"><a name="p1258305592319"></a><a name="p1258305592319"></a>public Interpolator getInterpolator()</p>
<p id="p5584155514238"><a name="p5584155514238"></a><a name="p5584155514238"></a>Obtains an interpolator.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table22204mcpsimp"></a>
<table><thead align="left"><tr id="row22209mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p22211mcpsimp"><a name="p22211mcpsimp"></a><a name="p22211mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p22213mcpsimp"><a name="p22213mcpsimp"></a><a name="p22213mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row22214mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p22216mcpsimp"><a name="p22216mcpsimp"></a><a name="p22216mcpsimp"></a>Interpolator</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p22218mcpsimp"><a name="p22218mcpsimp"></a><a name="p22218mcpsimp"></a>Interpolator.</p>
</td>
</tr>
</tbody>
</table>

## getTarget<a name="section177511713191"></a>

<a name="table1475113131397"></a>
<table><thead align="left"><tr id="row1675181318911"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p97517134914"><a name="p97517134914"></a><a name="p97517134914"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row475212131992"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p94981726899"><a name="p94981726899"></a><a name="p94981726899"></a>public <a href="latlng.md">LatLng</a> getTarget()</p>
<p id="p975218139914"><a name="p975218139914"></a><a name="p975218139914"></a>Obtains the movement target position.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table1617018121222"></a>
<table><thead align="left"><tr id="row13170121272220"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p14170191214227"><a name="p14170191214227"></a><a name="p14170191214227"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p1917091282220"><a name="p1917091282220"></a><a name="p1917091282220"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row817031222218"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p176150201222"><a name="p176150201222"></a><a name="p176150201222"></a><a href="latlng.md">LatLng</a></p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p1717017122223"><a name="p1717017122223"></a><a name="p1717017122223"></a>Movement target position.</p>
</td>
</tr>
</tbody>
</table>

## setDuration<a name="section11704105017376"></a>

<a name="table6569mcpsimp"></a>
<table><thead align="left"><tr id="row6573mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p6575mcpsimp"><a name="p6575mcpsimp"></a><a name="p6575mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row6576mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p12627338312"><a name="p12627338312"></a><a name="p12627338312"></a>public void setDuration(long duration)</p>
<p id="p17377650124613"><a name="p17377650124613"></a><a name="p17377650124613"></a>Sets the animation duration.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table22866mcpsimp"></a>
<table><thead align="left"><tr id="row22871mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p22873mcpsimp"><a name="p22873mcpsimp"></a><a name="p22873mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p22875mcpsimp"><a name="p22875mcpsimp"></a><a name="p22875mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row22876mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p22878mcpsimp"><a name="p22878mcpsimp"></a><a name="p22878mcpsimp"></a>duration</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p22880mcpsimp"><a name="p22880mcpsimp"></a><a name="p22880mcpsimp"></a>Animation duration, in milliseconds. The default value is <strong id="b196204479425"><a name="b196204479425"></a><a name="b196204479425"></a>250</strong>.</p>
</td>
</tr>
</tbody>
</table>

## setInterpolator<a name="section92301125931"></a>

<a name="table17230625435"></a>
<table><thead align="left"><tr id="row13231142518318"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p13231725636"><a name="p13231725636"></a><a name="p13231725636"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row1223172513310"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p424145612310"><a name="p424145612310"></a><a name="p424145612310"></a>public void setInterpolator(Interpolator interpolator)</p>
<p id="p62314251636"><a name="p62314251636"></a><a name="p62314251636"></a>Sets an animation interpolator.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table1223111251838"></a>
<table><thead align="left"><tr id="row1023117251335"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p13231825230"><a name="p13231825230"></a><a name="p13231825230"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p17231102511316"><a name="p17231102511316"></a><a name="p17231102511316"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row172311725631"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p123113252314"><a name="p123113252314"></a><a name="p123113252314"></a>interpolator</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p152313251938"><a name="p152313251938"></a><a name="p152313251938"></a>Interpolator.</p>
</td>
</tr>
</tbody>
</table>

