# AnimationSet<a name="ZH-CN_TOPIC_0000001099341084"></a>

-   [Public Constructor Summary](#section186641616203)
-   [Public Method Summary](#section1230414213220)
-   [Public Constructors](#section042681119126)
-   [AnimationSet](#section147561345184912)
-   [Public Methods](#section178075662915)
-   [addAnimation](#section139034209334)
-   [cleanAnimation](#section1026262293513)
-   [getInterpolator](#section185831855102315)
-   [getDuration](#section5722115214474)
-   [setDuration](#section11704105017376)
-   [setInterpolator](#section92301125931)


<a name="table22004mcpsimp"></a>
<table><thead align="left"><tr id="row22008mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p22010mcpsimp"><a name="p22010mcpsimp"></a><a name="p22010mcpsimp"></a>Class Info</p>
</th>
</tr>
</thead>
<tbody><tr id="row22011mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p51280417178"><a name="p51280417178"></a><a name="p51280417178"></a>public class AnimationSet extends Animation</p>
<p id="p1097894811125"><a name="p1097894811125"></a><a name="p1097894811125"></a>动画集合。</p>
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
<tbody><tr id="row6458mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p789204619202"><a name="p789204619202"></a><a name="p789204619202"></a><a href="#section147561345184912">AnimationSet</a>(boolean shareInterpolator)</p>
<p id="p11471244141518"><a name="p11471244141518"></a><a name="p11471244141518"></a>使用是否共享插值器参数创建<a href="animationset.md">AnimationSet</a>对象。</p>
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
<tbody><tr id="row7740350105918"><td class="cellrowborder" valign="top" width="35.77%" headers="mcps1.1.3.1.1 "><p id="p1719412447402"><a name="p1719412447402"></a><a name="p1719412447402"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="64.23%" headers="mcps1.1.3.1.2 "><p id="p13390132122310"><a name="p13390132122310"></a><a name="p13390132122310"></a><a href="#section139034209334">addAnimation</a>(<a href="animation.md">Animation</a> animation)</p>
<p id="p21451132125017"><a name="p21451132125017"></a><a name="p21451132125017"></a>添加动画。</p>
</td>
</tr>
<tr id="row0740185015916"><td class="cellrowborder" valign="top" width="35.77%" headers="mcps1.1.3.1.1 "><p id="p1366863112215"><a name="p1366863112215"></a><a name="p1366863112215"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="64.23%" headers="mcps1.1.3.1.2 "><p id="p0980154113239"><a name="p0980154113239"></a><a name="p0980154113239"></a><a href="#section1026262293513">cleanAnimation</a>()</p>
<p id="p1251164175011"><a name="p1251164175011"></a><a name="p1251164175011"></a>清除动画。</p>
</td>
</tr>
<tr id="row0143457184013"><td class="cellrowborder" valign="top" width="35.77%" headers="mcps1.1.3.1.1 "><p id="p115835542218"><a name="p115835542218"></a><a name="p115835542218"></a>Interpolator</p>
</td>
<td class="cellrowborder" valign="top" width="64.23%" headers="mcps1.1.3.1.2 "><p id="p468510462232"><a name="p468510462232"></a><a name="p468510462232"></a><a href="#section185831855102315">getInterpolator</a>()</p>
<p id="p0206018175016"><a name="p0206018175016"></a><a name="p0206018175016"></a>获取动画插值器。</p>
</td>
</tr>
<tr id="row9376103110238"><td class="cellrowborder" valign="top" width="35.77%" headers="mcps1.1.3.1.1 "><p id="p1961372311399"><a name="p1961372311399"></a><a name="p1961372311399"></a>long</p>
</td>
<td class="cellrowborder" valign="top" width="64.23%" headers="mcps1.1.3.1.2 "><p id="p2028716810404"><a name="p2028716810404"></a><a name="p2028716810404"></a><a href="#section5722115214474">getDuration</a>()</p>
<p id="p9450123110512"><a name="p9450123110512"></a><a name="p9450123110512"></a>获取动画持续时间。</p>
</td>
</tr>
<tr id="row11218209411"><td class="cellrowborder" valign="top" width="35.77%" headers="mcps1.1.3.1.1 "><p id="p3106933172211"><a name="p3106933172211"></a><a name="p3106933172211"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="64.23%" headers="mcps1.1.3.1.2 "><p id="p10622195113231"><a name="p10622195113231"></a><a name="p10622195113231"></a><a href="#section11704105017376">setDuration</a>(long duration)</p>
<p id="p99465775016"><a name="p99465775016"></a><a name="p99465775016"></a>设置动画持续时间。</p>
</td>
</tr>
<tr id="row1367311794110"><td class="cellrowborder" valign="top" width="35.77%" headers="mcps1.1.3.1.1 "><p id="p141212331220"><a name="p141212331220"></a><a name="p141212331220"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="64.23%" headers="mcps1.1.3.1.2 "><p id="p14891115612231"><a name="p14891115612231"></a><a name="p14891115612231"></a><a href="#section92301125931">setInterpolator</a>(Interpolator interpolator)</p>
<p id="p89460595118"><a name="p89460595118"></a><a name="p89460595118"></a>设置动画插值器。</p>
</td>
</tr>
</tbody>
</table>

## Public Constructors<a name="section042681119126"></a>

## AnimationSet<a name="section147561345184912"></a>

<a name="table227mcpsimp"></a>
<table><thead align="left"><tr id="row231mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p233mcpsimp"><a name="p233mcpsimp"></a><a name="p233mcpsimp"></a>Constructor</p>
</th>
</tr>
</thead>
<tbody><tr id="row235mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p148525013163"><a name="p148525013163"></a><a name="p148525013163"></a>public <a href="animationset.md">AnimationSet</a>(boolean shareInterpolator)</p>
<p id="p168565015168"><a name="p168565015168"></a><a name="p168565015168"></a>使用是否共享插值器参数创建<a href="animationset.md">AnimationSet</a>对象。</p>
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
<tbody><tr id="row255mcpsimp"><td class="cellrowborder" valign="top" width="43%" headers="mcps1.1.3.1.1 "><p id="p16831145118919"><a name="p16831145118919"></a><a name="p16831145118919"></a>shareInterpolator</p>
</td>
<td class="cellrowborder" valign="top" width="56.99999999999999%" headers="mcps1.1.3.1.2 "><p id="p20707102717141"><a name="p20707102717141"></a><a name="p20707102717141"></a>是否共享插值器。</p>
</td>
</tr>
</tbody>
</table>

## Public Methods<a name="section178075662915"></a>

## addAnimation<a name="section139034209334"></a>

<a name="table10903192019338"></a>
<table><thead align="left"><tr id="row6904182014332"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p179041820183316"><a name="p179041820183316"></a><a name="p179041820183316"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row129041220123310"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p16904820163315"><a name="p16904820163315"></a><a name="p16904820163315"></a>public void addAnimation(<a href="animation.md">Animation</a> animation)</p>
<p id="p199048208333"><a name="p199048208333"></a><a name="p199048208333"></a>添加动画。</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table1590442063319"></a>
<table><thead align="left"><tr id="row17904182017334"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p190402010333"><a name="p190402010333"></a><a name="p190402010333"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p1690472010336"><a name="p1690472010336"></a><a name="p1690472010336"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row15904820183317"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p1790419208337"><a name="p1790419208337"></a><a name="p1790419208337"></a>animation</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p109047208337"><a name="p109047208337"></a><a name="p109047208337"></a>动画。</p>
</td>
</tr>
</tbody>
</table>

## cleanAnimation<a name="section1026262293513"></a>

<a name="table1026212219351"></a>
<table><thead align="left"><tr id="row16262822103510"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p0262192220356"><a name="p0262192220356"></a><a name="p0262192220356"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row16262102233510"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p72623229359"><a name="p72623229359"></a><a name="p72623229359"></a>public void cleanAnimation()</p>
<p id="p626216223355"><a name="p626216223355"></a><a name="p626216223355"></a>清除动画。</p>
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
<tbody><tr id="row16583115514231"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p94511958203415"><a name="p94511958203415"></a><a name="p94511958203415"></a>public Interpolator getInterpolator()</p>
<p id="p5584155514238"><a name="p5584155514238"></a><a name="p5584155514238"></a>获取动画插值器。</p>
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

