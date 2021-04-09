# ScaleAnimation<a name="ZH-CN_TOPIC_0000001145541081"></a>

-   [Public Constructor Summary](#section186641616203)
-   [Public Method Summary](#section1230414213220)
-   [Public Constructors](#section042681119126)
-   [ScaleAnimation](#section147561345184912)
-   [Public Methods](#section178075662915)
-   [getDuration](#section5722115214474)
-   [getFromX](#section0246205575916)
-   [getFromY](#section172381224523)
-   [getInterpolator](#section185831855102315)
-   [getToX](#section111215293016)
-   [getToY](#section12395241124)
-   [setDuration](#section11704105017376)
-   [setInterpolator](#section92301125931)


<a name="table22004mcpsimp"></a>
<table><thead align="left"><tr id="row22008mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p22010mcpsimp"><a name="p22010mcpsimp"></a><a name="p22010mcpsimp"></a>Class Info</p>
</th>
</tr>
</thead>
<tbody><tr id="row22011mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p1290783718377"><a name="p1290783718377"></a><a name="p1290783718377"></a>public class ScaleAnimation extends Animation</p>
<p id="p1097894811125"><a name="p1097894811125"></a><a name="p1097894811125"></a>控制缩放的动画类。</p>
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
<tbody><tr id="row6458mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p15447233113815"><a name="p15447233113815"></a><a name="p15447233113815"></a><a href="#section147561345184912">ScaleAnimation</a>(float fromX, float toX, float fromY, float toY)</p>
<p id="p220392119318"><a name="p220392119318"></a><a name="p220392119318"></a>使用起始坐标缩放比例与目的坐标缩放比例创建<a href="scaleanimation.md">ScaleAnimation</a>对象。0表示收缩到没有，1表示正常无伸缩，值小于1表示收缩，值大于1表示放大。图标放大的最大尺寸为（width:1080，height:1080），单位：像素。</p>
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
<p id="p1741119325539"><a name="p1741119325539"></a><a name="p1741119325539"></a>获取动画持续时间。</p>
</td>
</tr>
<tr id="row0740185015916"><td class="cellrowborder" valign="top" width="35.77%" headers="mcps1.1.3.1.1 "><p id="p11610162311392"><a name="p11610162311392"></a><a name="p11610162311392"></a>float</p>
</td>
<td class="cellrowborder" valign="top" width="64.23%" headers="mcps1.1.3.1.2 "><p id="p1783075914539"><a name="p1783075914539"></a><a name="p1783075914539"></a><a href="#section0246205575916">getFromX</a>()</p>
<p id="p147729409536"><a name="p147729409536"></a><a name="p147729409536"></a>获取动画开始时横坐标。</p>
</td>
</tr>
<tr id="row14302161916535"><td class="cellrowborder" valign="top" width="35.77%" headers="mcps1.1.3.1.1 "><p id="p17474133655318"><a name="p17474133655318"></a><a name="p17474133655318"></a>float</p>
</td>
<td class="cellrowborder" valign="top" width="64.23%" headers="mcps1.1.3.1.2 "><p id="p88968319548"><a name="p88968319548"></a><a name="p88968319548"></a><a href="#section172381224523">getFromY</a>()</p>
<p id="p18508105085310"><a name="p18508105085310"></a><a name="p18508105085310"></a>获取动画开始时纵坐标。</p>
</td>
</tr>
<tr id="row0143457184013"><td class="cellrowborder" valign="top" width="35.77%" headers="mcps1.1.3.1.1 "><p id="p1460722303910"><a name="p1460722303910"></a><a name="p1460722303910"></a>Interpolator</p>
</td>
<td class="cellrowborder" valign="top" width="64.23%" headers="mcps1.1.3.1.2 "><p id="p9778576544"><a name="p9778576544"></a><a name="p9778576544"></a><a href="#section185831855102315">getInterpolator</a>()</p>
<p id="p16309185816532"><a name="p16309185816532"></a><a name="p16309185816532"></a>获取插值器。</p>
</td>
</tr>
<tr id="row11218209411"><td class="cellrowborder" valign="top" width="35.77%" headers="mcps1.1.3.1.1 "><p id="p160412333914"><a name="p160412333914"></a><a name="p160412333914"></a>float</p>
</td>
<td class="cellrowborder" valign="top" width="64.23%" headers="mcps1.1.3.1.2 "><p id="p16465418125418"><a name="p16465418125418"></a><a name="p16465418125418"></a><a href="#section111215293016">getToX</a>()</p>
<p id="p583586195416"><a name="p583586195416"></a><a name="p583586195416"></a>获取动画结束时的横坐标。</p>
</td>
</tr>
<tr id="row135672460537"><td class="cellrowborder" valign="top" width="35.77%" headers="mcps1.1.3.1.1 "><p id="p1324654955312"><a name="p1324654955312"></a><a name="p1324654955312"></a>float</p>
</td>
<td class="cellrowborder" valign="top" width="64.23%" headers="mcps1.1.3.1.2 "><p id="p1252311273548"><a name="p1252311273548"></a><a name="p1252311273548"></a><a href="#section12395241124">getToY</a>()</p>
<p id="p1437341416545"><a name="p1437341416545"></a><a name="p1437341416545"></a>获取动画结束时的纵坐标。</p>
</td>
</tr>
<tr id="row1367311794110"><td class="cellrowborder" valign="top" width="35.77%" headers="mcps1.1.3.1.1 "><p id="p106015232395"><a name="p106015232395"></a><a name="p106015232395"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="64.23%" headers="mcps1.1.3.1.2 "><p id="p1782916310541"><a name="p1782916310541"></a><a name="p1782916310541"></a><a href="#section11704105017376">setDuration</a>(long duration)</p>
<p id="p183567229547"><a name="p183567229547"></a><a name="p183567229547"></a>设置动画持续时间。</p>
</td>
</tr>
<tr id="row15766112116392"><td class="cellrowborder" valign="top" width="35.77%" headers="mcps1.1.3.1.1 "><p id="p5766172114391"><a name="p5766172114391"></a><a name="p5766172114391"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="64.23%" headers="mcps1.1.3.1.2 "><p id="p9478183695414"><a name="p9478183695414"></a><a name="p9478183695414"></a><a href="#section92301125931">setInterpolator</a>(Interpolator interpolator)</p>
<p id="p1778003012548"><a name="p1778003012548"></a><a name="p1778003012548"></a>设置动画插值器。</p>
</td>
</tr>
</tbody>
</table>

## Public Constructors<a name="section042681119126"></a>

## ScaleAnimation<a name="section147561345184912"></a>

<a name="table227mcpsimp"></a>
<table><thead align="left"><tr id="row231mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p233mcpsimp"><a name="p233mcpsimp"></a><a name="p233mcpsimp"></a>Constructor</p>
</th>
</tr>
</thead>
<tbody><tr id="row235mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p2412340201"><a name="p2412340201"></a><a name="p2412340201"></a>public <a href="#section147561345184912">ScaleAnimation</a>(float fromX, float toX, float fromY, float toY)</p>
<p id="p741234132010"><a name="p741234132010"></a><a name="p741234132010"></a>使用起始坐标缩放比例与目的坐标缩放比例创建<a href="scaleanimation.md">ScaleAnimation</a>对象。0表示收缩到没有，1表示正常无伸缩，值小于1表示收缩，值大于1表示放大。图标放大的最大尺寸为（width:1080，height:1080），单位：像素。</p>
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
<tbody><tr id="row255mcpsimp"><td class="cellrowborder" valign="top" width="43%" headers="mcps1.1.3.1.1 "><p id="p34711540162014"><a name="p34711540162014"></a><a name="p34711540162014"></a>fromX</p>
</td>
<td class="cellrowborder" valign="top" width="56.99999999999999%" headers="mcps1.1.3.1.2 "><p id="p20707102717141"><a name="p20707102717141"></a><a name="p20707102717141"></a>指动画开始时应用的水平缩放倍数。</p>
</td>
</tr>
<tr id="row32181248172018"><td class="cellrowborder" valign="top" width="43%" headers="mcps1.1.3.1.1 "><p id="p321818484206"><a name="p321818484206"></a><a name="p321818484206"></a>toX</p>
</td>
<td class="cellrowborder" valign="top" width="56.99999999999999%" headers="mcps1.1.3.1.2 "><p id="p15218194882019"><a name="p15218194882019"></a><a name="p15218194882019"></a>指动画结束时应用的水平缩放倍数。</p>
</td>
</tr>
<tr id="row1336364515205"><td class="cellrowborder" valign="top" width="43%" headers="mcps1.1.3.1.1 "><p id="p143631345142011"><a name="p143631345142011"></a><a name="p143631345142011"></a>fromY</p>
</td>
<td class="cellrowborder" valign="top" width="56.99999999999999%" headers="mcps1.1.3.1.2 "><p id="p2036319456205"><a name="p2036319456205"></a><a name="p2036319456205"></a>指动画开始时应用的垂直缩放倍数。</p>
</td>
</tr>
<tr id="row18244506183"><td class="cellrowborder" valign="top" width="43%" headers="mcps1.1.3.1.1 "><p id="p144701440152019"><a name="p144701440152019"></a><a name="p144701440152019"></a>toY</p>
</td>
<td class="cellrowborder" valign="top" width="56.99999999999999%" headers="mcps1.1.3.1.2 "><p id="p148251750191813"><a name="p148251750191813"></a><a name="p148251750191813"></a>指动画结束时应用的垂直缩放倍数。</p>
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

<a name="table7201928131918"></a>
<table><thead align="left"><tr id="row19218283198"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p52192881913"><a name="p52192881913"></a><a name="p52192881913"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p1321172811194"><a name="p1321172811194"></a><a name="p1321172811194"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row221152861912"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p1621128131915"><a name="p1621128131915"></a><a name="p1621128131915"></a>long</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p11532153841918"><a name="p11532153841918"></a><a name="p11532153841918"></a>动画持续时间，单位：毫秒。</p>
</td>
</tr>
</tbody>
</table>

## getFromX<a name="section0246205575916"></a>

<a name="table82461555155911"></a>
<table><thead align="left"><tr id="row5246195515913"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p192461555195912"><a name="p192461555195912"></a><a name="p192461555195912"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row42461255115920"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p19473177016"><a name="p19473177016"></a><a name="p19473177016"></a>public float getFromX()</p>
<p id="p1924712557591"><a name="p1924712557591"></a><a name="p1924712557591"></a>获取动画开始时横坐标。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table3681435196"></a>
<table><thead align="left"><tr id="row1668134391916"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p176894361915"><a name="p176894361915"></a><a name="p176894361915"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p18685439192"><a name="p18685439192"></a><a name="p18685439192"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row66844351918"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p468104371919"><a name="p468104371919"></a><a name="p468104371919"></a>float</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p33264488363"><a name="p33264488363"></a><a name="p33264488363"></a>开始时横坐标。</p>
</td>
</tr>
</tbody>
</table>

## getFromY<a name="section172381224523"></a>

<a name="table1623919241326"></a>
<table><thead align="left"><tr id="row923952420217"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p22397244216"><a name="p22397244216"></a><a name="p22397244216"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row182391024029"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p2023917241128"><a name="p2023917241128"></a><a name="p2023917241128"></a>public float getFromY()</p>
<p id="p15239142415215"><a name="p15239142415215"></a><a name="p15239142415215"></a>获取动画开始时纵坐标。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table179910112014"></a>
<table><thead align="left"><tr id="row19918105203"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p39210202014"><a name="p39210202014"></a><a name="p39210202014"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p19991072018"><a name="p19991072018"></a><a name="p19991072018"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row0901017205"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p119310162013"><a name="p119310162013"></a><a name="p119310162013"></a>float</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p3991052011"><a name="p3991052011"></a><a name="p3991052011"></a>动画开始时纵坐标。</p>
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

## getToX<a name="section111215293016"></a>

<a name="table91262910012"></a>
<table><thead align="left"><tr id="row51222910014"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p6121529705"><a name="p6121529705"></a><a name="p6121529705"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row20120296010"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p12121829701"><a name="p12121829701"></a><a name="p12121829701"></a>public float getToX()</p>
<p id="p161215291609"><a name="p161215291609"></a><a name="p161215291609"></a>获取动画结束时的横坐标。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table045023102013"></a>
<table><thead align="left"><tr id="row1145003122015"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p145013132018"><a name="p145013132018"></a><a name="p145013132018"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p184502033201"><a name="p184502033201"></a><a name="p184502033201"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row10450438201"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p34508315208"><a name="p34508315208"></a><a name="p34508315208"></a>float</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p154508319206"><a name="p154508319206"></a><a name="p154508319206"></a>动画结束时的横坐标。</p>
</td>
</tr>
</tbody>
</table>

## getToY<a name="section12395241124"></a>

<a name="table923922410218"></a>
<table><thead align="left"><tr id="row16239182418217"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p19239162411215"><a name="p19239162411215"></a><a name="p19239162411215"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row1923912415216"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p152392241422"><a name="p152392241422"></a><a name="p152392241422"></a>public float getToY()</p>
<p id="p123910241820"><a name="p123910241820"></a><a name="p123910241820"></a>获取动画结束时的纵坐标。</p>
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
<tbody><tr id="row13646201352010"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p16463137207"><a name="p16463137207"></a><a name="p16463137207"></a>float</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p1664681392012"><a name="p1664681392012"></a><a name="p1664681392012"></a>动画结束时的纵坐标。</p>
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

