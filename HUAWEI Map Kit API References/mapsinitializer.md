# MapsInitializer<a name="EN-US_TOPIC_0000001145860981"></a>

-   [Public Method Summary](#section18824375557)
-   [Public Methods](#section1658818567463)
-   [initialize](#section1516212511479)
-   [setApiKey](#section1389444514617)


<a name="table7425mcpsimp"></a>
<table><thead align="left"><tr id="row7429mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p7431mcpsimp"><a name="p7431mcpsimp"></a><a name="p7431mcpsimp"></a>Class Info</p>
</th>
</tr>
</thead>
<tbody><tr id="row7432mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p795612467267"><a name="p795612467267"></a><a name="p795612467267"></a>public final class MapsInitializer</p>
<p id="p7434mcpsimp"><a name="p7434mcpsimp"></a><a name="p7434mcpsimp"></a>Final class that extends <strong id="b3925746105613"><a name="b3925746105613"></a><a name="b3925746105613"></a>Object</strong>. If certain features need to be used before a map is obtained, use this class to initialize the Map SDK.</p>
</td>
</tr>
</tbody>
</table>

## Public Method Summary<a name="section18824375557"></a>

<a name="table7440mcpsimp"></a>
<table><thead align="left"><tr id="row7445mcpsimp"><th class="cellrowborder" valign="top" width="40%" id="mcps1.1.3.1.1"><p id="p7447mcpsimp"><a name="p7447mcpsimp"></a><a name="p7447mcpsimp"></a>Qualifier and Type</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.1.3.1.2"><p id="p7449mcpsimp"><a name="p7449mcpsimp"></a><a name="p7449mcpsimp"></a>Method Name and Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row7450mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p7452mcpsimp"><a name="p7452mcpsimp"></a><a name="p7452mcpsimp"></a>static synchronized int</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p7454mcpsimp"><a name="p7454mcpsimp"></a><a name="p7454mcpsimp"></a><a href="#section1516212511479">initialize</a>(Context context)</p>
<p id="p104571411019"><a name="p104571411019"></a><a name="p104571411019"></a>Initializes the Map SDK so that its classes are ready for use.</p>
</td>
</tr>
<tr id="row076610353332"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p19767183583313"><a name="p19767183583313"></a><a name="p19767183583313"></a>static void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p1749974216372"><a name="p1749974216372"></a><a name="p1749974216372"></a><a href="#section1389444514617">setApiKey</a>(String apiKey)</p>
<p id="p21908151608"><a name="p21908151608"></a><a name="p21908151608"></a>Sets the API key of the Map SDK.</p>
</td>
</tr>
</tbody>
</table>

## Public Methods<a name="section1658818567463"></a>

## initialize<a name="section1516212511479"></a>

<a name="table7457mcpsimp"></a>
<table><thead align="left"><tr id="row7461mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p7463mcpsimp"><a name="p7463mcpsimp"></a><a name="p7463mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row7464mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p7466mcpsimp"><a name="p7466mcpsimp"></a><a name="p7466mcpsimp"></a>public static synchronized  int initialize(Context context)</p>
<p id="p1260731715477"><a name="p1260731715477"></a><a name="p1260731715477"></a>Initializes the Map SDK so that its classes are ready for use.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table7472mcpsimp"></a>
<table><thead align="left"><tr id="row7477mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p7479mcpsimp"><a name="p7479mcpsimp"></a><a name="p7479mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p7481mcpsimp"><a name="p7481mcpsimp"></a><a name="p7481mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row7482mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p7484mcpsimp"><a name="p7484mcpsimp"></a><a name="p7484mcpsimp"></a>context</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p7486mcpsimp"><a name="p7486mcpsimp"></a><a name="p7486mcpsimp"></a>Context required for obtaining necessary SDK resources. This parameter cannot be <strong id="b18201546227"><a name="b18201546227"></a><a name="b18201546227"></a>null</strong>.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table7489mcpsimp"></a>
<table><thead align="left"><tr id="row7494mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p7496mcpsimp"><a name="p7496mcpsimp"></a><a name="p7496mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p7498mcpsimp"><a name="p7498mcpsimp"></a><a name="p7498mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row7499mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p7501mcpsimp"><a name="p7501mcpsimp"></a><a name="p7501mcpsimp"></a>int</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p7503mcpsimp"><a name="p7503mcpsimp"></a><a name="p7503mcpsimp"></a>Initialization result code. The value is <strong id="b833713238115"><a name="b833713238115"></a><a name="b833713238115"></a>0</strong>.</p>
</td>
</tr>
</tbody>
</table>

## setApiKey<a name="section1389444514617"></a>

<a name="table12894144519617"></a>
<table><thead align="left"><tr id="row1289416459610"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p389510451861"><a name="p389510451861"></a><a name="p389510451861"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row78959451461"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p11895345564"><a name="p11895345564"></a><a name="p11895345564"></a>public static void setApiKey(String apiKey)</p>
<p id="p148959454615"><a name="p148959454615"></a><a name="p148959454615"></a>Sets the API key of the Map SDK.</p>
<div class="note" id="note32305265402"><a name="note32305265402"></a><a name="note32305265402"></a><span class="notetitle"> NOTE: </span><div class="notebody"><p id="p19230326104020"><a name="p19230326104020"></a><a name="p19230326104020"></a>This method does not need to be called if the <strong id="b1389388708"><a name="b1389388708"></a><a name="b1389388708"></a>api_key</strong> field in the <span class="uicontrol" id="u4485d9e19ef546819b05a2c2265148e8"><a name="u4485d9e19ef546819b05a2c2265148e8"></a><a name="u4485d9e19ef546819b05a2c2265148e8"></a><b>agconnect-services.json</b></span> file already specifies an API key.</p>
</div></div>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table1389618451966"></a>
<table><thead align="left"><tr id="row9897845769"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p15897545767"><a name="p15897545767"></a><a name="p15897545767"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p138972456613"><a name="p138972456613"></a><a name="p138972456613"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row168976455616"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p689711451868"><a name="p689711451868"></a><a name="p689711451868"></a>apiKey</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p88971645264"><a name="p88971645264"></a><a name="p88971645264"></a>API key. </p>
</td>
</tr>
</tbody>
</table>

