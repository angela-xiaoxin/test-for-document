# Animation<a name="ZH-CN_TOPIC_0000001099341100"></a>

-   [Nested Class Summary](#section20712438152910)
-   [Public Field Summary](#section1022812963413)
-   [Public Constructor Summary](#section87392536379)
-   [Public Method Summary](#section1312413410395)
-   [Public Fields](#section10626215124512)
-   [FILL\_MODE\_BACKWARDS](#section7850163275012)
-   [FILL\_MODE\_FORWARDS](#section14921853122216)
-   [INFINITE](#section1568118167524)
-   [RESTART](#section115903104535)
-   [REVERSE](#section1079711311546)
-   [Public Methods](#section13599345115811)
-   [getFillMode](#section145631818720)
-   [getInterpolator](#section139481721171313)
-   [getListener](#section6685353131413)
-   [getRepeatCount](#section10950544171116)
-   [getRepeatMode](#section9833545181010)
-   [getDuration](#section523712743417)
-   [setAnimationListener](#section11704105017376)
-   [setDuration](#section397015215117)
-   [setFillMode](#section983111569412)
-   [setInterpolator](#section92301125931)
-   [setRepeatCount](#section8288571985)
-   [setRepeatMode](#section715014351193)


<a name="table22004mcpsimp"></a>
<table><thead align="left"><tr id="row22008mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p22010mcpsimp"><a name="p22010mcpsimp"></a><a name="p22010mcpsimp"></a>Class Info</p>
</th>
</tr>
</thead>
<tbody><tr id="row22011mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p041043220271"><a name="p041043220271"></a><a name="p041043220271"></a>public abstract class Animation</p>
<p id="p1087721214612"><a name="p1087721214612"></a><a name="p1087721214612"></a>用于支持标记动画。</p>
</td>
</tr>
</tbody>
</table>

## Nested Class Summary<a name="section20712438152910"></a>

<a name="table1110mcpsimp"></a>
<table><thead align="left"><tr id="row1115mcpsimp"><th class="cellrowborder" valign="top" width="39.290000000000006%" id="mcps1.1.3.1.1"><p id="p7543132495318"><a name="p7543132495318"></a><a name="p7543132495318"></a>Qualifier and Type</p>
</th>
<th class="cellrowborder" valign="top" width="60.709999999999994%" id="mcps1.1.3.1.2"><p id="p1554319242536"><a name="p1554319242536"></a><a name="p1554319242536"></a>Class Name and Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row1120mcpsimp"><td class="cellrowborder" valign="top" width="39.290000000000006%" headers="mcps1.1.3.1.1 "><p id="p1456135211228"><a name="p1456135211228"></a><a name="p1456135211228"></a>public interface</p>
</td>
<td class="cellrowborder" valign="top" width="60.709999999999994%" headers="mcps1.1.3.1.2 "><p id="p1122mcpsimp"><a name="p1122mcpsimp"></a><a name="p1122mcpsimp"></a><a href="animationlistener.md">Animation.AnimationListener</a></p>
<p id="p758915615218"><a name="p758915615218"></a><a name="p758915615218"></a>动画移动的侦听器。</p>
</td>
</tr>
</tbody>
</table>

## Public Field Summary<a name="section1022812963413"></a>

<a name="table51207528357"></a>
<table><thead align="left"><tr id="row6121185283516"><th class="cellrowborder" valign="top" width="32.21%" id="mcps1.1.3.1.1"><p id="p1528164471414"><a name="p1528164471414"></a><a name="p1528164471414"></a>Qualifier and Type</p>
</th>
<th class="cellrowborder" valign="top" width="67.78999999999999%" id="mcps1.1.3.1.2"><p id="p1554614158108"><a name="p1554614158108"></a><a name="p1554614158108"></a>Field and Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row2012119527357"><td class="cellrowborder" valign="top" width="32.21%" headers="mcps1.1.3.1.1 "><p id="p18435813153514"><a name="p18435813153514"></a><a name="p18435813153514"></a>static final int</p>
</td>
<td class="cellrowborder" valign="top" width="67.78999999999999%" headers="mcps1.1.3.1.2 "><p id="p53826412545"><a name="p53826412545"></a><a name="p53826412545"></a><a href="#section7850163275012">FILL_MODE_BACKWARDS</a></p>
<p id="p237715783516"><a name="p237715783516"></a><a name="p237715783516"></a>动画执行后保持在第一帧。</p>
</td>
</tr>
<tr id="row13442716354"><td class="cellrowborder" valign="top" width="32.21%" headers="mcps1.1.3.1.1 "><p id="p1577170102915"><a name="p1577170102915"></a><a name="p1577170102915"></a>static final int</p>
</td>
<td class="cellrowborder" valign="top" width="67.78999999999999%" headers="mcps1.1.3.1.2 "><p id="p151731339143618"><a name="p151731339143618"></a><a name="p151731339143618"></a><a href="#section14921853122216">FILL_MODE_FORWARDS</a></p>
<p id="p171731339163620"><a name="p171731339163620"></a><a name="p171731339163620"></a>动画执行后保持在最后一帧。</p>
</td>
</tr>
<tr id="row1336562919353"><td class="cellrowborder" valign="top" width="32.21%" headers="mcps1.1.3.1.1 "><p id="p7112007295"><a name="p7112007295"></a><a name="p7112007295"></a>static final int</p>
</td>
<td class="cellrowborder" valign="top" width="67.78999999999999%" headers="mcps1.1.3.1.2 "><p id="p6602046193613"><a name="p6602046193613"></a><a name="p6602046193613"></a><a href="#section1568118167524">INFINITE</a></p>
<p id="p15604461360"><a name="p15604461360"></a><a name="p15604461360"></a>无限期地重复动画。</p>
</td>
</tr>
<tr id="row144371826193513"><td class="cellrowborder" valign="top" width="32.21%" headers="mcps1.1.3.1.1 "><p id="p8144204293"><a name="p8144204293"></a><a name="p8144204293"></a>static final int</p>
</td>
<td class="cellrowborder" valign="top" width="67.78999999999999%" headers="mcps1.1.3.1.2 "><p id="p9381105220363"><a name="p9381105220363"></a><a name="p9381105220363"></a><a href="#section115903104535">RESTART</a></p>
<p id="p1938214528363"><a name="p1938214528363"></a><a name="p1938214528363"></a>动画结束后从头播放，最大重复次数受<a href="#section8288571985">Animation.setRepeatCount</a>(int) 限制。</p>
</td>
</tr>
<tr id="row12311410355"><td class="cellrowborder" valign="top" width="32.21%" headers="mcps1.1.3.1.1 "><p id="p516319052918"><a name="p516319052918"></a><a name="p516319052918"></a>static final int</p>
</td>
<td class="cellrowborder" valign="top" width="67.78999999999999%" headers="mcps1.1.3.1.2 "><p id="p18614145743612"><a name="p18614145743612"></a><a name="p18614145743612"></a><a href="#section1079711311546">REVERSE</a></p>
<p id="p1961410571360"><a name="p1961410571360"></a><a name="p1961410571360"></a>动画结束后从尾倒放，最大重复次数受<a href="#section8288571985">Animation.setRepeatCount</a>(int) 限制。</p>
</td>
</tr>
</tbody>
</table>

## Public Constructor Summary<a name="section87392536379"></a>

<a name="table6451mcpsimp"></a>
<table><thead align="left"><tr id="row6455mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p6457mcpsimp"><a name="p6457mcpsimp"></a><a name="p6457mcpsimp"></a>Constructor Name</p>
</th>
</tr>
</thead>
<tbody><tr id="row6458mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p16203348113812"><a name="p16203348113812"></a><a name="p16203348113812"></a><a href="animation.md">Animation</a>()</p>
<p id="p884315329362"><a name="p884315329362"></a><a name="p884315329362"></a>Animation类的默认构造方法。</p>
</td>
</tr>
</tbody>
</table>

## Public Method Summary<a name="section1312413410395"></a>

<a name="table5738155010595"></a>
<table><thead align="left"><tr id="row9739145005913"><th class="cellrowborder" valign="top" width="37.36%" id="mcps1.1.3.1.1"><p id="p6469mcpsimp"><a name="p6469mcpsimp"></a><a name="p6469mcpsimp"></a>Qualifier and Type</p>
</th>
<th class="cellrowborder" valign="top" width="62.63999999999999%" id="mcps1.1.3.1.2"><p id="p6471mcpsimp"><a name="p6471mcpsimp"></a><a name="p6471mcpsimp"></a>Method Name and Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row7740350105918"><td class="cellrowborder" valign="top" width="37.36%" headers="mcps1.1.3.1.1 "><p id="p1719412447402"><a name="p1719412447402"></a><a name="p1719412447402"></a>int</p>
</td>
<td class="cellrowborder" valign="top" width="62.63999999999999%" headers="mcps1.1.3.1.2 "><p id="p219334484019"><a name="p219334484019"></a><a name="p219334484019"></a><a href="#section145631818720">getFillMode</a>()</p>
<p id="p7408113994615"><a name="p7408113994615"></a><a name="p7408113994615"></a>获取动画执行完成后的状态。</p>
</td>
</tr>
<tr id="row0740185015916"><td class="cellrowborder" valign="top" width="37.36%" headers="mcps1.1.3.1.1 "><p id="p8192104444020"><a name="p8192104444020"></a><a name="p8192104444020"></a>Interpolator</p>
</td>
<td class="cellrowborder" valign="top" width="62.63999999999999%" headers="mcps1.1.3.1.2 "><p id="p8192144411408"><a name="p8192144411408"></a><a name="p8192144411408"></a><a href="#section139481721171313">getInterpolator</a>()</p>
<p id="p039054044612"><a name="p039054044612"></a><a name="p039054044612"></a>获取插值器。</p>
</td>
</tr>
<tr id="row0143457184013"><td class="cellrowborder" valign="top" width="37.36%" headers="mcps1.1.3.1.1 "><p id="p101431857114019"><a name="p101431857114019"></a><a name="p101431857114019"></a><a href="animationlistener.md">Animation.AnimationListener</a></p>
</td>
<td class="cellrowborder" valign="top" width="62.63999999999999%" headers="mcps1.1.3.1.2 "><p id="p10143557154017"><a name="p10143557154017"></a><a name="p10143557154017"></a><a href="#section6685353131413">getListener</a>()</p>
<p id="p10252447164711"><a name="p10252447164711"></a><a name="p10252447164711"></a>获取动画侦听器。</p>
</td>
</tr>
<tr id="row11218209411"><td class="cellrowborder" valign="top" width="37.36%" headers="mcps1.1.3.1.1 "><p id="p1439203416"><a name="p1439203416"></a><a name="p1439203416"></a>int</p>
</td>
<td class="cellrowborder" valign="top" width="62.63999999999999%" headers="mcps1.1.3.1.2 "><p id="p731620194118"><a name="p731620194118"></a><a name="p731620194118"></a><a href="#section10950544171116">getRepeatCount</a>()</p>
<p id="p1468516572474"><a name="p1468516572474"></a><a name="p1468516572474"></a>获取动画重复次数。</p>
</td>
</tr>
<tr id="row1367311794110"><td class="cellrowborder" valign="top" width="37.36%" headers="mcps1.1.3.1.1 "><p id="p76731117124113"><a name="p76731117124113"></a><a name="p76731117124113"></a>int</p>
</td>
<td class="cellrowborder" valign="top" width="62.63999999999999%" headers="mcps1.1.3.1.2 "><p id="p1767481710418"><a name="p1767481710418"></a><a name="p1767481710418"></a><a href="#section9833545181010">getRepeatMode</a>()</p>
<p id="p7630107134817"><a name="p7630107134817"></a><a name="p7630107134817"></a>获取动画重复模式。</p>
</td>
</tr>
<tr id="row821994410324"><td class="cellrowborder" valign="top" width="37.36%" headers="mcps1.1.3.1.1 "><p id="p22201144153219"><a name="p22201144153219"></a><a name="p22201144153219"></a>long</p>
</td>
<td class="cellrowborder" valign="top" width="62.63999999999999%" headers="mcps1.1.3.1.2 "><p id="p22201644193215"><a name="p22201644193215"></a><a name="p22201644193215"></a><a href="#section523712743417">getDuration</a>()</p>
<p id="p115071917114812"><a name="p115071917114812"></a><a name="p115071917114812"></a>获取动画持续时间。</p>
</td>
</tr>
<tr id="row11349170134119"><td class="cellrowborder" valign="top" width="37.36%" headers="mcps1.1.3.1.1 "><p id="p193506014110"><a name="p193506014110"></a><a name="p193506014110"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="62.63999999999999%" headers="mcps1.1.3.1.2 "><p id="p435016010413"><a name="p435016010413"></a><a name="p435016010413"></a><a href="#section11704105017376">setAnimationListener</a>(<a href="animationlistener.md">Animation.AnimationListener</a> listener)</p>
<p id="p7996142614484"><a name="p7996142614484"></a><a name="p7996142614484"></a>设置侦听器。</p>
</td>
</tr>
<tr id="row117824284120"><td class="cellrowborder" valign="top" width="37.36%" headers="mcps1.1.3.1.1 "><p id="p1778214218414"><a name="p1778214218414"></a><a name="p1778214218414"></a>abstract void</p>
</td>
<td class="cellrowborder" valign="top" width="62.63999999999999%" headers="mcps1.1.3.1.2 "><p id="p1878312194117"><a name="p1878312194117"></a><a name="p1878312194117"></a><a href="#section397015215117">setDuration</a>(long duration)</p>
<p id="p17429936104810"><a name="p17429936104810"></a><a name="p17429936104810"></a>设置动画持续时间。</p>
</td>
</tr>
<tr id="row1740918154415"><td class="cellrowborder" valign="top" width="37.36%" headers="mcps1.1.3.1.1 "><p id="p640919150411"><a name="p640919150411"></a><a name="p640919150411"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="62.63999999999999%" headers="mcps1.1.3.1.2 "><p id="p14409121564110"><a name="p14409121564110"></a><a name="p14409121564110"></a><a href="#section983111569412">setFillMode</a>(int fillMode)</p>
<p id="p16926146144817"><a name="p16926146144817"></a><a name="p16926146144817"></a>设置动画执行完成后的状态。</p>
</td>
</tr>
<tr id="row616113508409"><td class="cellrowborder" valign="top" width="37.36%" headers="mcps1.1.3.1.1 "><p id="p1162145034018"><a name="p1162145034018"></a><a name="p1162145034018"></a>abstract void</p>
</td>
<td class="cellrowborder" valign="top" width="62.63999999999999%" headers="mcps1.1.3.1.2 "><p id="p111621850114012"><a name="p111621850114012"></a><a name="p111621850114012"></a><a href="#section92301125931">setInterpolator</a>(Interpolator interpolator)</p>
<p id="p13521058174815"><a name="p13521058174815"></a><a name="p13521058174815"></a>设置动画插值器。</p>
</td>
</tr>
<tr id="row1425110541405"><td class="cellrowborder" valign="top" width="37.36%" headers="mcps1.1.3.1.1 "><p id="p1025175411407"><a name="p1025175411407"></a><a name="p1025175411407"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="62.63999999999999%" headers="mcps1.1.3.1.2 "><p id="p325112549401"><a name="p325112549401"></a><a name="p325112549401"></a><a href="#section8288571985">setRepeatCount</a>(int repeatCount)</p>
<p id="p188233324919"><a name="p188233324919"></a><a name="p188233324919"></a>设置动画重复执行的次数。</p>
</td>
</tr>
<tr id="row1726016515178"><td class="cellrowborder" valign="top" width="37.36%" headers="mcps1.1.3.1.1 "><p id="p1319184464015"><a name="p1319184464015"></a><a name="p1319184464015"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="62.63999999999999%" headers="mcps1.1.3.1.2 "><p id="p1018974484014"><a name="p1018974484014"></a><a name="p1018974484014"></a><a href="#section715014351193">setRepeatMode</a>(int repeatMode)</p>
<p id="p6687245124910"><a name="p6687245124910"></a><a name="p6687245124910"></a>设置重复执行的模式，默认从前往后执行。</p>
</td>
</tr>
</tbody>
</table>

## Public Fields<a name="section10626215124512"></a>

## FILL\_MODE\_BACKWARDS<a name="section7850163275012"></a>

<a name="table3850173211507"></a>
<table><thead align="left"><tr id="row985019327502"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p178516322508"><a name="p178516322508"></a><a name="p178516322508"></a>Fields</p>
</th>
</tr>
</thead>
<tbody><tr id="row8851193225014"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p598115303513"><a name="p598115303513"></a><a name="p598115303513"></a>public static final int FILL_MODE_BACKWARDS</p>
<p id="p12851232105015"><a name="p12851232105015"></a><a name="p12851232105015"></a>动画执行后保持在第一帧。</p>
<p id="p17851732115011"><a name="p17851732115011"></a><a name="p17851732115011"></a>FILL_MODE_BACKWARDS：1，其余常量值参阅：<a href="constant-values.md#section152341354115215">Constant-values</a></p>
</td>
</tr>
</tbody>
</table>

## FILL\_MODE\_FORWARDS<a name="section14921853122216"></a>

<a name="table21921426102319"></a>
<table><thead align="left"><tr id="row3192726182318"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p18192826122310"><a name="p18192826122310"></a><a name="p18192826122310"></a>Fields</p>
</th>
</tr>
</thead>
<tbody><tr id="row9192626172316"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p16731422184812"><a name="p16731422184812"></a><a name="p16731422184812"></a>public static final int FILL_MODE_FORWARDS</p>
<p id="p81921026192319"><a name="p81921026192319"></a><a name="p81921026192319"></a>动画执行后保持在最后一帧。</p>
<p id="p127751542165617"><a name="p127751542165617"></a><a name="p127751542165617"></a>FILL_MODE_FORWARDS：0，其余常量值参阅：<a href="constant-values.md#section152341354115215">Constant-values</a></p>
</td>
</tr>
</tbody>
</table>

## INFINITE<a name="section1568118167524"></a>

<a name="table6681516115210"></a>
<table><thead align="left"><tr id="row136811516195212"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p468118165521"><a name="p468118165521"></a><a name="p468118165521"></a>Fields</p>
</th>
</tr>
</thead>
<tbody><tr id="row2681116195211"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p1268119161523"><a name="p1268119161523"></a><a name="p1268119161523"></a>public static final int INFINITE</p>
<p id="p0681121615527"><a name="p0681121615527"></a><a name="p0681121615527"></a>无限期地重复动画。</p>
<p id="p10681171695220"><a name="p10681171695220"></a><a name="p10681171695220"></a>INFINITE：-1，其余常量值参阅：<a href="constant-values.md#section152341354115215">Constant-values</a></p>
</td>
</tr>
</tbody>
</table>

## RESTART<a name="section115903104535"></a>

<a name="table1259151019532"></a>
<table><thead align="left"><tr id="row659161035311"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p259115102532"><a name="p259115102532"></a><a name="p259115102532"></a>Fields</p>
</th>
</tr>
</thead>
<tbody><tr id="row159121010531"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p1188835175315"><a name="p1188835175315"></a><a name="p1188835175315"></a>public static final int RESTART</p>
<p id="p459120104538"><a name="p459120104538"></a><a name="p459120104538"></a>动画结束后从头播放，最大重复次数受<a href="#section8288571985">Animation.setRepeatCount</a>(int)限制。</p>
<p id="p195915107538"><a name="p195915107538"></a><a name="p195915107538"></a>RESTART：1，其余常量值参阅：<a href="constant-values.md#section152341354115215">Constant-values</a></p>
</td>
</tr>
</tbody>
</table>

## REVERSE<a name="section1079711311546"></a>

<a name="table6798513125410"></a>
<table><thead align="left"><tr id="row1798213165416"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p13798151318547"><a name="p13798151318547"></a><a name="p13798151318547"></a>Fields</p>
</th>
</tr>
</thead>
<tbody><tr id="row197981013185416"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p15798181345416"><a name="p15798181345416"></a><a name="p15798181345416"></a>public static final int REVERSE</p>
<p id="p1979817133542"><a name="p1979817133542"></a><a name="p1979817133542"></a>动画结束后从尾倒放，最大重复次数受<a href="#section8288571985">Animation.setRepeatCount</a>(int)限制。</p>
<p id="p18798111325411"><a name="p18798111325411"></a><a name="p18798111325411"></a>REVERSE：2，其余常量值参阅：<a href="constant-values.md#section152341354115215">Constant-values</a></p>
</td>
</tr>
</tbody>
</table>

## Public Methods<a name="section13599345115811"></a>

## getFillMode<a name="section145631818720"></a>

<a name="table18563198577"></a>
<table><thead align="left"><tr id="row6563138674"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p95631981574"><a name="p95631981574"></a><a name="p95631981574"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row175638810713"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p65637819711"><a name="p65637819711"></a><a name="p65637819711"></a>public int getFillMode()</p>
<p id="p105632086719"><a name="p105632086719"></a><a name="p105632086719"></a>获取动画执行完成后的状态。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table897131717617"></a>
<table><thead align="left"><tr id="row1397617168"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p11976171066"><a name="p11976171066"></a><a name="p11976171066"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p59814174612"><a name="p59814174612"></a><a name="p59814174612"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row4981217565"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p14980173616"><a name="p14980173616"></a><a name="p14980173616"></a>int</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p1867714268615"><a name="p1867714268615"></a><a name="p1867714268615"></a>动画执行完成后的状态。</p>
</td>
</tr>
</tbody>
</table>

## getInterpolator<a name="section139481721171313"></a>

<a name="table19948182120136"></a>
<table><thead align="left"><tr id="row094872121313"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p15949112115137"><a name="p15949112115137"></a><a name="p15949112115137"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row1949122112139"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p1087810559134"><a name="p1087810559134"></a><a name="p1087810559134"></a>public Interpolator getInterpolator()</p>
<p id="p3949921111314"><a name="p3949921111314"></a><a name="p3949921111314"></a>获取插值器。</p>
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

## getListener<a name="section6685353131413"></a>

<a name="table12685155391411"></a>
<table><thead align="left"><tr id="row0685115316149"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p668575361414"><a name="p668575361414"></a><a name="p668575361414"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row168545351411"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p46855538147"><a name="p46855538147"></a><a name="p46855538147"></a>public <a href="animationlistener.md">Animation.AnimationListener</a> getListener()</p>
<p id="p136854539141"><a name="p136854539141"></a><a name="p136854539141"></a>获取动画侦听器。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table141293149810"></a>
<table><thead align="left"><tr id="row1712915141387"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p171291914086"><a name="p171291914086"></a><a name="p171291914086"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p3129714383"><a name="p3129714383"></a><a name="p3129714383"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row513011142089"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p41301914081"><a name="p41301914081"></a><a name="p41301914081"></a><a href="animationlistener.md">Animation.AnimationListener</a></p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p5130714187"><a name="p5130714187"></a><a name="p5130714187"></a>动画侦听器。</p>
</td>
</tr>
</tbody>
</table>

## getRepeatCount<a name="section10950544171116"></a>

<a name="table495084416116"></a>
<table><thead align="left"><tr id="row795014411116"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p20950134419118"><a name="p20950134419118"></a><a name="p20950134419118"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row0950044161115"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p99505444118"><a name="p99505444118"></a><a name="p99505444118"></a>public int getRepeatCount()</p>
<p id="p195015448119"><a name="p195015448119"></a><a name="p195015448119"></a>获取动画重复次数。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table11488856574"></a>
<table><thead align="left"><tr id="row1448955610718"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p104891756778"><a name="p104891756778"></a><a name="p104891756778"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p248914567713"><a name="p248914567713"></a><a name="p248914567713"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row18489125611711"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p44895567718"><a name="p44895567718"></a><a name="p44895567718"></a>int</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p1848918567716"><a name="p1848918567716"></a><a name="p1848918567716"></a>动画重复次数。</p>
</td>
</tr>
</tbody>
</table>

## getRepeatMode<a name="section9833545181010"></a>

<a name="table7833134513100"></a>
<table><thead align="left"><tr id="row2833945131010"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p88334453108"><a name="p88334453108"></a><a name="p88334453108"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row1583454551016"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p283444518101"><a name="p283444518101"></a><a name="p283444518101"></a>public int getRepeatMode()</p>
<p id="p1783454511102"><a name="p1783454511102"></a><a name="p1783454511102"></a>获取动画重复模式。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table16171961718"></a>
<table><thead align="left"><tr id="row1861986878"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p1461911619716"><a name="p1461911619716"></a><a name="p1461911619716"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p156191169717"><a name="p156191169717"></a><a name="p156191169717"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row361915617712"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p116191661872"><a name="p116191661872"></a><a name="p116191661872"></a>int</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p16619106171"><a name="p16619106171"></a><a name="p16619106171"></a>动画重复模式。</p>
</td>
</tr>
</tbody>
</table>

## getDuration<a name="section523712743417"></a>

<a name="table852519913410"></a>
<table><thead align="left"><tr id="row165258911346"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p8525795341"><a name="p8525795341"></a><a name="p8525795341"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row2052579193415"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p1252599163418"><a name="p1252599163418"></a><a name="p1252599163418"></a>public long getDuration()</p>
<p id="p15525197342"><a name="p15525197342"></a><a name="p15525197342"></a>获取动画持续时间。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table14525691349"></a>
<table><thead align="left"><tr id="row10525297341"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p752512917340"><a name="p752512917340"></a><a name="p752512917340"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p105250913414"><a name="p105250913414"></a><a name="p105250913414"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row552549183416"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p1952510917344"><a name="p1952510917344"></a><a name="p1952510917344"></a>long</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p6525992342"><a name="p6525992342"></a><a name="p6525992342"></a>动画持续时间。</p>
</td>
</tr>
</tbody>
</table>

## setAnimationListener<a name="section11704105017376"></a>

<a name="table6569mcpsimp"></a>
<table><thead align="left"><tr id="row6573mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p6575mcpsimp"><a name="p6575mcpsimp"></a><a name="p6575mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row6576mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p17430221107"><a name="p17430221107"></a><a name="p17430221107"></a>public void setAnimationListener(<a href="animationlistener.md">Animation.AnimationListener</a> listener)</p>
<p id="p17377650124613"><a name="p17377650124613"></a><a name="p17377650124613"></a>设置侦听器。</p>
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
<tbody><tr id="row22876mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p22878mcpsimp"><a name="p22878mcpsimp"></a><a name="p22878mcpsimp"></a>listener</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p22880mcpsimp"><a name="p22880mcpsimp"></a><a name="p22880mcpsimp"></a>动画侦听器。</p>
</td>
</tr>
</tbody>
</table>

## setDuration<a name="section397015215117"></a>

<a name="table16161430729"></a>
<table><thead align="left"><tr id="row1173301123"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p117113010210"><a name="p117113010210"></a><a name="p117113010210"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row131763017210"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p12174301322"><a name="p12174301322"></a><a name="p12174301322"></a>public abstract void setDuration(long duration)</p>
<p id="p14172030124"><a name="p14172030124"></a><a name="p14172030124"></a>设置动画持续时间。</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table317330922"></a>
<table><thead align="left"><tr id="row1817030428"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p20176301029"><a name="p20176301029"></a><a name="p20176301029"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p121717301022"><a name="p121717301022"></a><a name="p121717301022"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row1178300212"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p15176301027"><a name="p15176301027"></a><a name="p15176301027"></a>duration</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p14174301828"><a name="p14174301828"></a><a name="p14174301828"></a>动画持续时间，单位：毫秒，默认为250毫秒。</p>
</td>
</tr>
</tbody>
</table>

## setFillMode<a name="section983111569412"></a>

<a name="table38314561943"></a>
<table><thead align="left"><tr id="row7831105610413"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p19831256046"><a name="p19831256046"></a><a name="p19831256046"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row168310564417"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p98317568410"><a name="p98317568410"></a><a name="p98317568410"></a>public void setFillMode(int fillMode)</p>
<p id="p11831105614416"><a name="p11831105614416"></a><a name="p11831105614416"></a>设置动画执行完成后的状态。</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table148311656346"></a>
<table><thead align="left"><tr id="row18321556141"><th class="cellrowborder" valign="top" width="40.28%" id="mcps1.1.3.1.1"><p id="p16832105613411"><a name="p16832105613411"></a><a name="p16832105613411"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="59.72%" id="mcps1.1.3.1.2"><p id="p1883210561342"><a name="p1883210561342"></a><a name="p1883210561342"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row168320560416"><td class="cellrowborder" valign="top" width="40.28%" headers="mcps1.1.3.1.1 "><p id="p48329563416"><a name="p48329563416"></a><a name="p48329563416"></a>fillMode</p>
</td>
<td class="cellrowborder" valign="top" width="59.72%" headers="mcps1.1.3.1.2 "><p id="p88321056442"><a name="p88321056442"></a><a name="p88321056442"></a>动画执行完成后的状态，默认为保持最后一帧（<a href="#section14921853122216">FILL_MODE_FORWARDS</a>），缩放动画默认保持第一帧（<a href="#section7850163275012">FILL_MODE_BACKWARDS</a>）。</p>
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
<tbody><tr id="row1223172513310"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p424145612310"><a name="p424145612310"></a><a name="p424145612310"></a>public abstract void setInterpolator(Interpolator interpolator)</p>
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

## setRepeatCount<a name="section8288571985"></a>

<a name="table122881175819"></a>
<table><thead align="left"><tr id="row728818711817"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p228815715814"><a name="p228815715814"></a><a name="p228815715814"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row10288187184"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p10136371888"><a name="p10136371888"></a><a name="p10136371888"></a>public void setRepeatCount(int repeatCount)</p>
<p id="p989414410813"><a name="p989414410813"></a><a name="p989414410813"></a>设置动画重复执行的次数。</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table22881716813"></a>
<table><thead align="left"><tr id="row62891677816"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p1128977485"><a name="p1128977485"></a><a name="p1128977485"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p42892715810"><a name="p42892715810"></a><a name="p42892715810"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row15289197387"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p9289473819"><a name="p9289473819"></a><a name="p9289473819"></a>repeatCount</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p15289071483"><a name="p15289071483"></a><a name="p15289071483"></a>动画重复执行的次数，默认为0。</p>
</td>
</tr>
</tbody>
</table>

## setRepeatMode<a name="section715014351193"></a>

<a name="table815003510914"></a>
<table><thead align="left"><tr id="row131505351993"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p181506352911"><a name="p181506352911"></a><a name="p181506352911"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row1915011352096"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p61406614109"><a name="p61406614109"></a><a name="p61406614109"></a>public void setRepeatMode(int repeatMode)</p>
<p id="p41511935597"><a name="p41511935597"></a><a name="p41511935597"></a>设置重复执行的模式，默认从前往后执行。</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table915113359914"></a>
<table><thead align="left"><tr id="row1115116351912"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p6151153513911"><a name="p6151153513911"></a><a name="p6151153513911"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p1315117351092"><a name="p1315117351092"></a><a name="p1315117351092"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row1315111357917"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p1921312631013"><a name="p1921312631013"></a><a name="p1921312631013"></a>repeatMode</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p1315111357919"><a name="p1315111357919"></a><a name="p1315111357919"></a>重复执行的模式，默认为1。取值包括：</p>
<a name="ul1625635072419"></a><a name="ul1625635072419"></a><ul id="ul1625635072419"><li><a href="#section115903104535">RESTART</a>：动画结束后从头播放。</li><li><a href="#section1079711311546">REVERSE</a>：动画结束后从尾倒放。</li></ul>
</td>
</tr>
</tbody>
</table>

