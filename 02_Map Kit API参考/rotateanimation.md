# RotateAnimation<a name="ZH-CN_TOPIC_0000001099341108"></a>

-   [Public Constructor Summary](#section186641616203)
-   [Public Method Summary](#section1230414213220)
-   [Public Constructors](#section042681119126)
-   [RotateAnimation](#section147561345184912)
-   [Public Methods](#section178075662915)
-   [getDuration](#section5722115214474)
-   [getFromDegree](#section81081648464)
-   [getInterpolator](#section185831855102315)
-   [getToDegree](#section6217142515477)
-   [setDuration](#section11704105017376)
-   [setInterpolator](#section92301125931)


<a name="table22004mcpsimp"></a>
<table><thead align="left"><tr id="row22008mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p22010mcpsimp"><a name="p22010mcpsimp"></a><a name="p22010mcpsimp"></a>Class Info</p>
</th>
</tr>
</thead>
<tbody><tr id="row22011mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p1290783718377"><a name="p1290783718377"></a><a name="p1290783718377"></a>public class RotateAnimation extends Animation</p>
<p id="p1097894811125"><a name="p1097894811125"></a><a name="p1097894811125"></a>控制旋转的动画类。</p>
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
<tbody><tr id="row6458mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p15447233113815"><a name="p15447233113815"></a><a name="p15447233113815"></a><a href="#section147561345184912">RotateAnimation</a>(float fromDegree, float toDegree)</p>
<p id="p134811294168"><a name="p134811294168"></a><a name="p134811294168"></a>使用起始角度和目标角度创建<a href="rotateanimation.md">RotateAnimation</a>对象。</p>
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
<td class="cellrowborder" valign="top" width="64.23%" headers="mcps1.1.3.1.2 "><p id="p2028716810404"><a name="p2028716810404"></a><a name="p2028716810404"></a><a href="#section5722115214474">getDuration</a>()</p>
<p id="p9450123110512"><a name="p9450123110512"></a><a name="p9450123110512"></a>获取动画持续时间。</p>
</td>
</tr>
<tr id="row0740185015916"><td class="cellrowborder" valign="top" width="35.77%" headers="mcps1.1.3.1.1 "><p id="p11610162311392"><a name="p11610162311392"></a><a name="p11610162311392"></a>float</p>
</td>
<td class="cellrowborder" valign="top" width="64.23%" headers="mcps1.1.3.1.2 "><p id="p121911112204015"><a name="p121911112204015"></a><a name="p121911112204015"></a><a href="#section81081648464">getFromDegree</a>()</p>
<p id="p1033334013511"><a name="p1033334013511"></a><a name="p1033334013511"></a>获取起始角度。</p>
</td>
</tr>
<tr id="row0143457184013"><td class="cellrowborder" valign="top" width="35.77%" headers="mcps1.1.3.1.1 "><p id="p1460722303910"><a name="p1460722303910"></a><a name="p1460722303910"></a>Interpolator</p>
</td>
<td class="cellrowborder" valign="top" width="64.23%" headers="mcps1.1.3.1.2 "><p id="p967513156407"><a name="p967513156407"></a><a name="p967513156407"></a><a href="#section185831855102315">getInterpolator</a>()</p>
<p id="p44861748145110"><a name="p44861748145110"></a><a name="p44861748145110"></a>获取插值器。</p>
</td>
</tr>
<tr id="row11218209411"><td class="cellrowborder" valign="top" width="35.77%" headers="mcps1.1.3.1.1 "><p id="p160412333914"><a name="p160412333914"></a><a name="p160412333914"></a>float</p>
</td>
<td class="cellrowborder" valign="top" width="64.23%" headers="mcps1.1.3.1.2 "><p id="p2393161918407"><a name="p2393161918407"></a><a name="p2393161918407"></a><a href="#section6217142515477">getToDegree</a>()</p>
<p id="p13145795119"><a name="p13145795119"></a><a name="p13145795119"></a>获取目标角度。</p>
</td>
</tr>
<tr id="row1367311794110"><td class="cellrowborder" valign="top" width="35.77%" headers="mcps1.1.3.1.1 "><p id="p106015232395"><a name="p106015232395"></a><a name="p106015232395"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="64.23%" headers="mcps1.1.3.1.2 "><p id="p19136122394012"><a name="p19136122394012"></a><a name="p19136122394012"></a><a href="#section11704105017376">setDuration</a>(long duration)</p>
<p id="p46559518525"><a name="p46559518525"></a><a name="p46559518525"></a>设置动画持续时间。</p>
</td>
</tr>
<tr id="row15766112116392"><td class="cellrowborder" valign="top" width="35.77%" headers="mcps1.1.3.1.1 "><p id="p5766172114391"><a name="p5766172114391"></a><a name="p5766172114391"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="64.23%" headers="mcps1.1.3.1.2 "><p id="p57541726104016"><a name="p57541726104016"></a><a name="p57541726104016"></a><a href="#section92301125931">setInterpolator</a>(Interpolator interpolator)</p>
<p id="p7249214145218"><a name="p7249214145218"></a><a name="p7249214145218"></a>设置动画插值器。</p>
</td>
</tr>
</tbody>
</table>

## Public Constructors<a name="section042681119126"></a>

## RotateAnimation<a name="section147561345184912"></a>

<a name="table227mcpsimp"></a>
<table><thead align="left"><tr id="row231mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p233mcpsimp"><a name="p233mcpsimp"></a><a name="p233mcpsimp"></a>Constructor</p>
</th>
</tr>
</thead>
<tbody><tr id="row235mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p149162041171816"><a name="p149162041171816"></a><a name="p149162041171816"></a>public <a href="#section147561345184912">RotateAnimation</a>(float fromDegree, float toDegree)</p>
<p id="p1191615418189"><a name="p1191615418189"></a><a name="p1191615418189"></a>使用起始角度和目标角度创建<a href="rotateanimation.md">RotateAnimation</a>对象。</p>
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
<tbody><tr id="row255mcpsimp"><td class="cellrowborder" valign="top" width="43%" headers="mcps1.1.3.1.1 "><p id="p103021647181817"><a name="p103021647181817"></a><a name="p103021647181817"></a>fromDegree</p>
</td>
<td class="cellrowborder" valign="top" width="56.99999999999999%" headers="mcps1.1.3.1.2 "><p id="p20707102717141"><a name="p20707102717141"></a><a name="p20707102717141"></a>起始角度。</p>
</td>
</tr>
<tr id="row18244506183"><td class="cellrowborder" valign="top" width="43%" headers="mcps1.1.3.1.1 "><p id="p98251950181820"><a name="p98251950181820"></a><a name="p98251950181820"></a>toDegree</p>
</td>
<td class="cellrowborder" valign="top" width="56.99999999999999%" headers="mcps1.1.3.1.2 "><p id="p148251750191813"><a name="p148251750191813"></a><a name="p148251750191813"></a>目标角度。</p>
</td>
</tr>
</tbody>
</table>

## Public Methods<a name="section178075662915"></a>

## getDuration<a name="section5722115214474"></a>

<a name="table3722552194717"></a>
<table><thead align="left"><tr id="row14722135264717"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p1972385264715"><a name="p1972385264715"></a><a name="p1972385264715"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row4723185211477"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p4766152474812"><a name="p4766152474812"></a><a name="p4766152474812"></a>public long getDuration()</p>
<p id="p1723105220475"><a name="p1723105220475"></a><a name="p1723105220475"></a>获取动画持续时间。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table162617553176"></a>
<table><thead align="left"><tr id="row726185516174"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p1226135517179"><a name="p1226135517179"></a><a name="p1226135517179"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p20261135521720"><a name="p20261135521720"></a><a name="p20261135521720"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row42624552175"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p14262055101715"><a name="p14262055101715"></a><a name="p14262055101715"></a>long</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p126213556177"><a name="p126213556177"></a><a name="p126213556177"></a>动画持续时间，单位：毫秒。</p>
</td>
</tr>
</tbody>
</table>

## getFromDegree<a name="section81081648464"></a>

<a name="table12108134154615"></a>
<table><thead align="left"><tr id="row13108164104610"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p1910818404612"><a name="p1910818404612"></a><a name="p1910818404612"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row2108749464"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p1636535874617"><a name="p1636535874617"></a><a name="p1636535874617"></a>public float getFromDegree()</p>
<p id="p15108194124612"><a name="p15108194124612"></a><a name="p15108194124612"></a>获取起始角度。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table3489356201013"></a>
<table><thead align="left"><tr id="row7489105620106"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p11489356191018"><a name="p11489356191018"></a><a name="p11489356191018"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p049014563108"><a name="p049014563108"></a><a name="p049014563108"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row174901356141016"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p1549018567108"><a name="p1549018567108"></a><a name="p1549018567108"></a>float</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p490619813111"><a name="p490619813111"></a><a name="p490619813111"></a>起始角度。</p>
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
<p id="p5584155514238"><a name="p5584155514238"></a><a name="p5584155514238"></a>获取插值器。</p>
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
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p22218mcpsimp"><a name="p22218mcpsimp"></a><a name="p22218mcpsimp"></a>插值器。</p>
</td>
</tr>
</tbody>
</table>

## getToDegree<a name="section6217142515477"></a>

<a name="table821792513478"></a>
<table><thead align="left"><tr id="row1021714255478"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p4217142524720"><a name="p4217142524720"></a><a name="p4217142524720"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row1217225194711"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p1021714251474"><a name="p1021714251474"></a><a name="p1021714251474"></a>public float getToDegree()</p>
<p id="p12217182534710"><a name="p12217182534710"></a><a name="p12217182534710"></a>获取目标角度。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table1270201731111"></a>
<table><thead align="left"><tr id="row270317173114"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p1070321761114"><a name="p1070321761114"></a><a name="p1070321761114"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p1870321712116"><a name="p1870321712116"></a><a name="p1870321712116"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row18703191717114"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p1970315177110"><a name="p1970315177110"></a><a name="p1970315177110"></a>float</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p6703131781117"><a name="p6703131781117"></a><a name="p6703131781117"></a>目标角度。</p>
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
<p id="p17377650124613"><a name="p17377650124613"></a><a name="p17377650124613"></a>设置动画持续时间。</p>
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
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p22880mcpsimp"><a name="p22880mcpsimp"></a><a name="p22880mcpsimp"></a>动画持续时间，单位：毫秒，默认为250毫秒。</p>
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
<p id="p62314251636"><a name="p62314251636"></a><a name="p62314251636"></a>设置动画插值器。</p>
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
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p152313251938"><a name="p152313251938"></a><a name="p152313251938"></a>插值器。</p>
</td>
</tr>
</tbody>
</table>

