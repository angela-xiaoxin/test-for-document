# AlphaAnimation<a name="ZH-CN_TOPIC_0000001099501068"></a>

-   [Public Constructor Summary](#section176234589542)
-   [Public Method Summary](#section1674217711594)
-   [Public Constructors](#section042681119126)
-   [AlphaAnimation](#section147561345184912)
-   [Public Methods](#section184932710111)
-   [getDuration](#section11704105017376)
-   [getFromAlpha](#section883118354238)
-   [getInterpolator](#section185831855102315)
-   [getToAlpha](#section12398182316249)
-   [setDuration](#section28931314122517)
-   [setInterpolator](#section1838734182519)


<a name="table22004mcpsimp"></a>
<table><thead align="left"><tr id="row22008mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p22010mcpsimp"><a name="p22010mcpsimp"></a><a name="p22010mcpsimp"></a>Class Info</p>
</th>
</tr>
</thead>
<tbody><tr id="row22011mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p20160143817121"><a name="p20160143817121"></a><a name="p20160143817121"></a>public class AlphaAnimation extends Animation</p>
<p id="p1097894811125"><a name="p1097894811125"></a><a name="p1097894811125"></a>控制透明度的动画类，透明度范围为[0, 1]，1为不透明，0为完全透明。</p>
</td>
</tr>
</tbody>
</table>

## Public Constructor Summary<a name="section176234589542"></a>

<a name="table6451mcpsimp"></a>
<table><thead align="left"><tr id="row6455mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p6457mcpsimp"><a name="p6457mcpsimp"></a><a name="p6457mcpsimp"></a>Constructor Name</p>
</th>
</tr>
</thead>
<tbody><tr id="row6458mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p49885444159"><a name="p49885444159"></a><a name="p49885444159"></a><a href="#section147561345184912">AlphaAnimation</a>(float fromAlpha, float toAlpha)</p>
<p id="p128414871518"><a name="p128414871518"></a><a name="p128414871518"></a>使用起始透明度和目标透明度创建<a href="alphaanimation.md">AlphaAnimation</a>对象。</p>
</td>
</tr>
</tbody>
</table>

## Public Method Summary<a name="section1674217711594"></a>

<a name="table5738155010595"></a>
<table><thead align="left"><tr id="row9739145005913"><th class="cellrowborder" valign="top" width="37.36%" id="mcps1.1.3.1.1"><p id="p6469mcpsimp"><a name="p6469mcpsimp"></a><a name="p6469mcpsimp"></a>Qualifier and Type</p>
</th>
<th class="cellrowborder" valign="top" width="62.63999999999999%" id="mcps1.1.3.1.2"><p id="p6471mcpsimp"><a name="p6471mcpsimp"></a><a name="p6471mcpsimp"></a>Method Name and Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row7740350105918"><td class="cellrowborder" valign="top" width="37.36%" headers="mcps1.1.3.1.1 "><p id="p85965714160"><a name="p85965714160"></a><a name="p85965714160"></a>long</p>
</td>
<td class="cellrowborder" valign="top" width="62.63999999999999%" headers="mcps1.1.3.1.2 "><p id="p19320182191714"><a name="p19320182191714"></a><a name="p19320182191714"></a><a href="#section11704105017376">getDuration</a>()</p>
<p id="p1743937124415"><a name="p1743937124415"></a><a name="p1743937124415"></a>获取动画持续时间。</p>
</td>
</tr>
<tr id="row0740185015916"><td class="cellrowborder" valign="top" width="37.36%" headers="mcps1.1.3.1.1 "><p id="p1701258181612"><a name="p1701258181612"></a><a name="p1701258181612"></a>float</p>
</td>
<td class="cellrowborder" valign="top" width="62.63999999999999%" headers="mcps1.1.3.1.2 "><p id="p20319220174"><a name="p20319220174"></a><a name="p20319220174"></a><a href="#section883118354238">getFromAlpha</a>()</p>
<p id="p168041438204412"><a name="p168041438204412"></a><a name="p168041438204412"></a>获取起始透明度。</p>
</td>
</tr>
<tr id="row1726016515178"><td class="cellrowborder" valign="top" width="37.36%" headers="mcps1.1.3.1.1 "><p id="p142601052177"><a name="p142601052177"></a><a name="p142601052177"></a>Interpolator</p>
</td>
<td class="cellrowborder" valign="top" width="62.63999999999999%" headers="mcps1.1.3.1.2 "><p id="p12260454176"><a name="p12260454176"></a><a name="p12260454176"></a><a href="#section185831855102315">getInterpolator</a>()</p>
<p id="p76612390449"><a name="p76612390449"></a><a name="p76612390449"></a>获取插值器。</p>
</td>
</tr>
<tr id="row15255947113410"><td class="cellrowborder" valign="top" width="37.36%" headers="mcps1.1.3.1.1 "><p id="p570095814162"><a name="p570095814162"></a><a name="p570095814162"></a>float</p>
</td>
<td class="cellrowborder" valign="top" width="62.63999999999999%" headers="mcps1.1.3.1.2 "><p id="p1031822161717"><a name="p1031822161717"></a><a name="p1031822161717"></a><a href="#section12398182316249">getToAlpha</a>()</p>
<p id="p13503840124418"><a name="p13503840124418"></a><a name="p13503840124418"></a>获取目标透明度。</p>
</td>
</tr>
<tr id="row10755828141711"><td class="cellrowborder" valign="top" width="37.36%" headers="mcps1.1.3.1.1 "><p id="p127552289176"><a name="p127552289176"></a><a name="p127552289176"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="62.63999999999999%" headers="mcps1.1.3.1.2 "><p id="p975520285173"><a name="p975520285173"></a><a name="p975520285173"></a><a href="#section28931314122517">setDuration</a>(long duration)</p>
<p id="p18342134124414"><a name="p18342134124414"></a><a name="p18342134124414"></a>设置动画持续时间。</p>
</td>
</tr>
<tr id="row77400503598"><td class="cellrowborder" valign="top" width="37.36%" headers="mcps1.1.3.1.1 "><p id="p6699175811612"><a name="p6699175811612"></a><a name="p6699175811612"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="62.63999999999999%" headers="mcps1.1.3.1.2 "><p id="p82973212172"><a name="p82973212172"></a><a name="p82973212172"></a><a href="#section1838734182519">setInterpolator</a>(Interpolator interpolator)</p>
<p id="p517411424445"><a name="p517411424445"></a><a name="p517411424445"></a>设置动画插值器。</p>
</td>
</tr>
</tbody>
</table>

## Public Constructors<a name="section042681119126"></a>

## AlphaAnimation<a name="section147561345184912"></a>

<a name="table227mcpsimp"></a>
<table><thead align="left"><tr id="row231mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p233mcpsimp"><a name="p233mcpsimp"></a><a name="p233mcpsimp"></a>Constructor</p>
</th>
</tr>
</thead>
<tbody><tr id="row235mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p9764184201411"><a name="p9764184201411"></a><a name="p9764184201411"></a>public <a href="alphaanimation.md">AlphaAnimation</a>(float fromAlpha, float toAlpha)</p>
<p id="p20764114181410"><a name="p20764114181410"></a><a name="p20764114181410"></a>使用起始透明度和目标透明度创建<a href="alphaanimation.md">AlphaAnimation</a>对象。</p>
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
<tbody><tr id="row255mcpsimp"><td class="cellrowborder" valign="top" width="43%" headers="mcps1.1.3.1.1 "><p id="p16831145118919"><a name="p16831145118919"></a><a name="p16831145118919"></a>fromAlpha</p>
</td>
<td class="cellrowborder" valign="top" width="56.99999999999999%" headers="mcps1.1.3.1.2 "><p id="p20707102717141"><a name="p20707102717141"></a><a name="p20707102717141"></a>起始透明度。</p>
</td>
</tr>
<tr id="row05001713362"><td class="cellrowborder" valign="top" width="43%" headers="mcps1.1.3.1.1 "><p id="p382915511795"><a name="p382915511795"></a><a name="p382915511795"></a>toAlpha</p>
</td>
<td class="cellrowborder" valign="top" width="56.99999999999999%" headers="mcps1.1.3.1.2 "><p id="p15706102761411"><a name="p15706102761411"></a><a name="p15706102761411"></a>目标透明度。</p>
</td>
</tr>
</tbody>
</table>

## Public Methods<a name="section184932710111"></a>

## getDuration<a name="section11704105017376"></a>

<a name="table6569mcpsimp"></a>
<table><thead align="left"><tr id="row6573mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p6575mcpsimp"><a name="p6575mcpsimp"></a><a name="p6575mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row6576mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p1245820271142"><a name="p1245820271142"></a><a name="p1245820271142"></a>public long getDuration()</p>
<p id="p17377650124613"><a name="p17377650124613"></a><a name="p17377650124613"></a>获取动画持续时间。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table10179125825118"></a>
<table><thead align="left"><tr id="row7179125855116"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p151791358125118"><a name="p151791358125118"></a><a name="p151791358125118"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p13179135825112"><a name="p13179135825112"></a><a name="p13179135825112"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row12179155816514"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p1179105815115"><a name="p1179105815115"></a><a name="p1179105815115"></a>long</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p2127982521"><a name="p2127982521"></a><a name="p2127982521"></a>动画持续时间，单位：毫秒。</p>
</td>
</tr>
</tbody>
</table>

## getFromAlpha<a name="section883118354238"></a>

<a name="table1831133511237"></a>
<table><thead align="left"><tr id="row13831193562312"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p883273592312"><a name="p883273592312"></a><a name="p883273592312"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row0832203502313"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p37443263153"><a name="p37443263153"></a><a name="p37443263153"></a>public float getFromAlpha()</p>
<p id="p983273518234"><a name="p983273518234"></a><a name="p983273518234"></a>获取起始透明度。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table8271421195210"></a>
<table><thead align="left"><tr id="row227110211520"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p1527162111528"><a name="p1527162111528"></a><a name="p1527162111528"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p1027182114521"><a name="p1027182114521"></a><a name="p1027182114521"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row8271162115211"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p102712217527"><a name="p102712217527"></a><a name="p102712217527"></a>float</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p1271122120526"><a name="p1271122120526"></a><a name="p1271122120526"></a>起始透明度，取值范围：[0, 1]，1为不透明，0为完全透明。</p>
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

## getToAlpha<a name="section12398182316249"></a>

<a name="table173981023122412"></a>
<table><thead align="left"><tr id="row1039812362411"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p1139862319248"><a name="p1139862319248"></a><a name="p1139862319248"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row1539872318243"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p13949115516224"><a name="p13949115516224"></a><a name="p13949115516224"></a>public float getToAlpha()</p>
<p id="p2039818235247"><a name="p2039818235247"></a><a name="p2039818235247"></a>获取目标透明度。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table1398155615527"></a>
<table><thead align="left"><tr id="row8983565520"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p1199165685217"><a name="p1199165685217"></a><a name="p1199165685217"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p69925619529"><a name="p69925619529"></a><a name="p69925619529"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row1999105610522"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p699185616529"><a name="p699185616529"></a><a name="p699185616529"></a>float</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p399156195215"><a name="p399156195215"></a><a name="p399156195215"></a>目标透明度，取值范围：[0, 1]，1为不透明，0为完全透明。</p>
</td>
</tr>
</tbody>
</table>

## setDuration<a name="section28931314122517"></a>

<a name="table3893814102510"></a>
<table><thead align="left"><tr id="row108931914122514"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p7893171412257"><a name="p7893171412257"></a><a name="p7893171412257"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row6893191482519"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p11140204511232"><a name="p11140204511232"></a><a name="p11140204511232"></a>public void setDuration(long duration)</p>
<p id="p989321417257"><a name="p989321417257"></a><a name="p989321417257"></a>设置动画持续时间。</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table17620131962412"></a>
<table><thead align="left"><tr id="row116205197245"><th class="cellrowborder" valign="top" width="50.06%" id="mcps1.1.3.1.1"><p id="p1562019196245"><a name="p1562019196245"></a><a name="p1562019196245"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="49.94%" id="mcps1.1.3.1.2"><p id="p76210191247"><a name="p76210191247"></a><a name="p76210191247"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row16621181914248"><td class="cellrowborder" valign="top" width="50.06%" headers="mcps1.1.3.1.1 "><p id="p762141920247"><a name="p762141920247"></a><a name="p762141920247"></a>duration</p>
</td>
<td class="cellrowborder" valign="top" width="49.94%" headers="mcps1.1.3.1.2 "><p id="p20621171962411"><a name="p20621171962411"></a><a name="p20621171962411"></a>动画持续时间，单位：毫秒，默认为250毫秒。</p>
</td>
</tr>
</tbody>
</table>

## setInterpolator<a name="section1838734182519"></a>

<a name="table1083883462514"></a>
<table><thead align="left"><tr id="row11838103442520"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p8838134122519"><a name="p8838134122519"></a><a name="p8838134122519"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row18381534142518"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p3928219122516"><a name="p3928219122516"></a><a name="p3928219122516"></a>public void setInterpolator(Interpolator interpolator)</p>
<p id="p14838234102517"><a name="p14838234102517"></a><a name="p14838234102517"></a>设置动画插值器。</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table211415539259"></a>
<table><thead align="left"><tr id="row41149533254"><th class="cellrowborder" valign="top" width="50.06%" id="mcps1.1.3.1.1"><p id="p6114953142510"><a name="p6114953142510"></a><a name="p6114953142510"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="49.94%" id="mcps1.1.3.1.2"><p id="p511445352512"><a name="p511445352512"></a><a name="p511445352512"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row211485352514"><td class="cellrowborder" valign="top" width="50.06%" headers="mcps1.1.3.1.1 "><p id="p61141353122510"><a name="p61141353122510"></a><a name="p61141353122510"></a>interpolator</p>
</td>
<td class="cellrowborder" valign="top" width="49.94%" headers="mcps1.1.3.1.2 "><p id="p5114185372518"><a name="p5114185372518"></a><a name="p5114185372518"></a>插值器。</p>
</td>
</tr>
</tbody>
</table>

