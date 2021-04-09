# Driving Route Planning<a name="EN-US_TOPIC_0000001145941049"></a>

-   [Function](#section8455201431219)
-   [Scenario](#section733593991210)
-   [Restrictions](#section5561220132)
-   [Prototype](#section12176172981317)
-   [Request Parameters](#section1044255015145)
-   [Request Example](#section19799143115168)
-   [Response Parameters](#section193511835151612)
-   [Response Example](#section095094211614)
-   [Call Example](#section284195414164)

## Function<a name="section8455201431219"></a>

Plans driving routes between multiple places. 

## Scenario<a name="section733593991210"></a>

None.

## Restrictions<a name="section5561220132"></a>

-   The number of departure places or destinations cannot exceed 5. 
-   For details about service call quota, please refer to  [Service Pricing](en-us_topic_0000001145860925.md).

## Prototype<a name="section12176172981317"></a>

<a name="table11154520143815"></a>
<table><tbody><tr id="row18154202003811"><th class="firstcol" valign="top" width="20%" id="mcps1.1.3.1.1"><p id="p101546202386"><a name="p101546202386"></a><a name="p101546202386"></a>Protocol</p>
</th>
<td class="cellrowborder" valign="top" width="80%" headers="mcps1.1.3.1.1 "><p id="p81541720123818"><a name="p81541720123818"></a><a name="p81541720123818"></a>HTTPS POST</p>
</td>
</tr>
<tr id="row1115462019387"><th class="firstcol" valign="top" width="20%" id="mcps1.1.3.2.1"><p id="p12756174203813"><a name="p12756174203813"></a><a name="p12756174203813"></a>Direction</p>
</th>
<td class="cellrowborder" valign="top" width="80%" headers="mcps1.1.3.2.1 "><p id="p16154112093811"><a name="p16154112093811"></a><a name="p16154112093811"></a>Your server -&gt; HUAWEI Map Kit server</p>
</td>
</tr>
<tr id="row215413208388"><th class="firstcol" valign="top" width="20%" id="mcps1.1.3.3.1"><p id="p19782114513386"><a name="p19782114513386"></a><a name="p19782114513386"></a>URL</p>
</th>
<td class="cellrowborder" valign="top" width="80%" headers="mcps1.1.3.3.1 "><p id="p9827850185319"><a name="p9827850185319"></a><a name="p9827850185319"></a>https://mapapi.cloud.huawei.com/mapApi/v1/routeService/drivingMatrix?key=<i><span class="varname" id="varname168423113295"><a name="varname168423113295"></a><a name="varname168423113295"></a>API KEY</span></i></p>
<div class="note" id="note65176364306"><a name="note65176364306"></a><a name="note65176364306"></a><span class="notetitle"> NOTE: </span><div class="notebody"><a name="en-us_topic_0000001099181294_ol42140252365"></a><a name="en-us_topic_0000001099181294_ol42140252365"></a><ol id="en-us_topic_0000001099181294_ol42140252365"><li>For details about how to obtain an API key, please refer to <a href="en-us_topic_0000001099501072.md#section169441820428">Obtaining the API Key</a>.</li><li>You need to call the <strong id="en-us_topic_0000001099181294_b144635512110"><a name="en-us_topic_0000001099181294_b144635512110"></a><a name="en-us_topic_0000001099181294_b144635512110"></a>URLEncoder.encode("Your apiKey", "UTF-8")</strong> method to encode the API key using <strong id="en-us_topic_0000001099181294_b646418511120"><a name="en-us_topic_0000001099181294_b646418511120"></a><a name="en-us_topic_0000001099181294_b646418511120"></a>encodeURI</strong>. For example, if the original API key is <strong id="en-us_topic_0000001099181294_b14422031224"><a name="en-us_topic_0000001099181294_b14422031224"></a><a name="en-us_topic_0000001099181294_b14422031224"></a>ABC/DFG+</strong>, the conversion result is <strong id="en-us_topic_0000001099181294_b2431137214"><a name="en-us_topic_0000001099181294_b2431137214"></a><a name="en-us_topic_0000001099181294_b2431137214"></a>ABC%2FDFG%2B</strong>.</li></ol>
</div></div>
</td>
</tr>
<tr id="row39361834214"><th class="firstcol" valign="top" width="20%" id="mcps1.1.3.4.1"><p id="p59410184422"><a name="p59410184422"></a><a name="p59410184422"></a>Data Format</p>
</th>
<td class="cellrowborder" valign="top" width="80%" headers="mcps1.1.3.4.1 "><p id="p171991908351"><a name="p171991908351"></a><a name="p171991908351"></a>Request: Content-Type: application/json</p>
<p id="p919916013510"><a name="p919916013510"></a><a name="p919916013510"></a>Response: Content-Type: application/json</p>
</td>
</tr>
</tbody>
</table>

## Request Parameters<a name="section1044255015145"></a>

**Request Header**

<a name="table1845425124915"></a>
<table><thead align="left"><tr id="en-us_topic_0000001050161916_row445417514491"><th class="cellrowborder" valign="top" width="20%" id="mcps1.1.5.1.1"><p id="en-us_topic_0000001050161916_p15454956493"><a name="en-us_topic_0000001050161916_p15454956493"></a><a name="en-us_topic_0000001050161916_p15454956493"></a>Parameter</p>
</th>
<th class="cellrowborder" valign="top" width="14.000000000000002%" id="mcps1.1.5.1.2"><p id="en-us_topic_0000001050161916_p7454159496"><a name="en-us_topic_0000001050161916_p7454159496"></a><a name="en-us_topic_0000001050161916_p7454159496"></a>Mandatory/Optional</p>
</th>
<th class="cellrowborder" valign="top" width="16%" id="mcps1.1.5.1.3"><p id="en-us_topic_0000001050161916_p24541659497"><a name="en-us_topic_0000001050161916_p24541659497"></a><a name="en-us_topic_0000001050161916_p24541659497"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.1.5.1.4"><p id="en-us_topic_0000001050161916_p34549513499"><a name="en-us_topic_0000001050161916_p34549513499"></a><a name="en-us_topic_0000001050161916_p34549513499"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="en-us_topic_0000001050161916_row84546564911"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.1.5.1.1 "><p id="en-us_topic_0000001050161916_p16591286492"><a name="en-us_topic_0000001050161916_p16591286492"></a><a name="en-us_topic_0000001050161916_p16591286492"></a>Content-Type</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="en-us_topic_0000001050161916_p2058087492"><a name="en-us_topic_0000001050161916_p2058087492"></a><a name="en-us_topic_0000001050161916_p2058087492"></a>Mandatory</p>
</td>
<td class="cellrowborder" valign="top" width="16%" headers="mcps1.1.5.1.3 "><p id="en-us_topic_0000001050161916_p85718154918"><a name="en-us_topic_0000001050161916_p85718154918"></a><a name="en-us_topic_0000001050161916_p85718154918"></a>application/json</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="en-us_topic_0000001050161916_p35512818497"><a name="en-us_topic_0000001050161916_p35512818497"></a><a name="en-us_topic_0000001050161916_p35512818497"></a>Data format of a request.</p>
</td>
</tr>
</tbody>
</table>

**Request Body**

<a name="table77202273214"></a>
<table><thead align="left"><tr id="row11729225326"><th class="cellrowborder" valign="top" width="18%" id="mcps1.1.5.1.1"><p id="p87210228329"><a name="p87210228329"></a><a name="p87210228329"></a>Parameter</p>
</th>
<th class="cellrowborder" valign="top" width="14.000000000000002%" id="mcps1.1.5.1.2"><p id="p129581029151016"><a name="p129581029151016"></a><a name="p129581029151016"></a>Mandatory/Optional</p>
</th>
<th class="cellrowborder" valign="top" width="18%" id="mcps1.1.5.1.3"><p id="p18726222329"><a name="p18726222329"></a><a name="p18726222329"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.1.5.1.4"><p id="p67242210323"><a name="p67242210323"></a><a name="p67242210323"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row1872122203212"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="p3776433144119"><a name="p3776433144119"></a><a name="p3776433144119"></a>origins</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="p1295852931019"><a name="p1295852931019"></a><a name="p1295852931019"></a>Mandatory</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.3 "><p id="p95731160406"><a name="p95731160406"></a><a name="p95731160406"></a><a href="input-params.md#section1256775182913">Coordinate</a>[]</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="p18868315144210"><a name="p18868315144210"></a><a name="p18868315144210"></a>Longitudes and latitudes of the departure places. A maximum of 5 departure places are allowed.</p>
</td>
</tr>
<tr id="row1772422133216"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="p6776133313414"><a name="p6776133313414"></a><a name="p6776133313414"></a>destinations</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="p995892921018"><a name="p995892921018"></a><a name="p995892921018"></a>Mandatory</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.3 "><p id="p55731816194019"><a name="p55731816194019"></a><a name="p55731816194019"></a><a href="input-params.md#section1256775182913">Coordinate</a>[]</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="p0868181544213"><a name="p0868181544213"></a><a name="p0868181544213"></a>Longitudes and latitudes of the destinations. A maximum of 5 destinations are allowed.</p>
</td>
</tr>
<tr id="row1872722153217"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="p1277616331419"><a name="p1277616331419"></a><a name="p1277616331419"></a>avoid</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="p19581029131019"><a name="p19581029131019"></a><a name="p19581029131019"></a>Optional</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.3 "><p id="p1931845919411"><a name="p1931845919411"></a><a name="p1931845919411"></a>int[]</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="p15868181511428"><a name="p15868181511428"></a><a name="p15868181511428"></a>Indicates the specified type of roads to be avoided. The options are as follows:</p>
<a name="ul0608125516381"></a><a name="ul0608125516381"></a><ul id="ul0608125516381"><li><strong id="b1021193916332"><a name="b1021193916332"></a><a name="b1021193916332"></a>0</strong>: Take least time.</li><li><strong id="b0271115617435"><a name="b0271115617435"></a><a name="b0271115617435"></a>1</strong>: Avoid toll roads.</li><li><strong id="b446813014447"><a name="b446813014447"></a><a name="b446813014447"></a>2</strong>: Avoid expressways.</li></ul>
<p id="p28683152424"><a name="p28683152424"></a><a name="p28683152424"></a>If this parameter is not included in the request, the route taking the least time will be returned by default.</p>
</td>
</tr>
<tr id="row1320722154116"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="p1577753319415"><a name="p1577753319415"></a><a name="p1577753319415"></a>departAt</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="p23201222411"><a name="p23201222411"></a><a name="p23201222411"></a>Optional</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.3 "><p id="p731825910416"><a name="p731825910416"></a><a name="p731825910416"></a>long</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="p19868181504214"><a name="p19868181504214"></a><a name="p19868181504214"></a>Estimated departure time, in seconds since 00:00 on January 1, 1970 (UTC).</p>
<p id="p1868181524214"><a name="p1868181524214"></a><a name="p1868181524214"></a>The value must be the current time or a future time.</p>
</td>
</tr>
<tr id="row65429222418"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="p207770335413"><a name="p207770335413"></a><a name="p207770335413"></a>trafficMode</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="p3542112216416"><a name="p3542112216416"></a><a name="p3542112216416"></a>Optional</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.3 "><p id="p731895944118"><a name="p731895944118"></a><a name="p731895944118"></a>int</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="p208697152421"><a name="p208697152421"></a><a name="p208697152421"></a>Time estimation mode. The options are as follows:</p>
<a name="ul1552382323916"></a><a name="ul1552382323916"></a><ul id="ul1552382323916"><li><strong id="b209891921184418"><a name="b209891921184418"></a><a name="b209891921184418"></a>0</strong> (default): best guess</li><li><strong id="b202131324184420"><a name="b202131324184420"></a><a name="b202131324184420"></a>1</strong>: The traffic condition is worse than the historical average.</li><li><strong id="b104822724416"><a name="b104822724416"></a><a name="b104822724416"></a>2</strong>: The traffic condition is better than the historical average.</li></ul>
</td>
</tr>
<tr id="row878132264119"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="p67771433114115"><a name="p67771433114115"></a><a name="p67771433114115"></a>language</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="p7781152211413"><a name="p7781152211413"></a><a name="p7781152211413"></a>Optional</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.3 "><p id="p1318185910416"><a name="p1318185910416"></a><a name="p1318185910416"></a>String(&lt;=6)</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="p1086917159422"><a name="p1086917159422"></a><a name="p1086917159422"></a>Language of the distance and journey time descriptions in the returned result. Currently, only <strong id="b7871114574415"><a name="b7871114574415"></a><a name="b7871114574415"></a>zh_CN</strong> (Chinese) and <strong id="b1887124516447"><a name="b1887124516447"></a><a name="b1887124516447"></a>en</strong> (English) are supported.</p>
</td>
</tr>
</tbody>
</table>

## Request Example<a name="section19799143115168"></a>

```
POST https://mapapi.cloud.huawei.com/mapApi/v1/routeService/drivingMatrix?key=API KEY HTTP/1.1 
Content-Type: application/json 
Accept: application/json 
{ 
    "origins": [ 
            {"lng": -1.894679, "lat": 54.974887}, 
            {"lng": -2.882682, "lat": 54.857616} 
    ], 
    "destinations": [ 
            {"lng": -1.744955, "lat": 54.775040} 
    ], 
    "avoid": [1,2], 
    "departAt":1678435530, 
    "trafficMode":2, 
    "language": "en" 
}
```

## Response Parameters<a name="section193511835151612"></a>

**When the status code is 200:**

**Response Header**

<a name="table06641185395"></a>
<table><thead align="left"><tr id="en-us_topic_0000001050161916_row1150982918214"><th class="cellrowborder" valign="top" width="20%" id="mcps1.1.5.1.1"><p id="en-us_topic_0000001050161916_p10509329102114"><a name="en-us_topic_0000001050161916_p10509329102114"></a><a name="en-us_topic_0000001050161916_p10509329102114"></a>Parameter</p>
</th>
<th class="cellrowborder" valign="top" width="14.000000000000002%" id="mcps1.1.5.1.2"><p id="en-us_topic_0000001050161916_p16509129132117"><a name="en-us_topic_0000001050161916_p16509129132117"></a><a name="en-us_topic_0000001050161916_p16509129132117"></a>Mandatory/Optional</p>
</th>
<th class="cellrowborder" valign="top" width="16%" id="mcps1.1.5.1.3"><p id="en-us_topic_0000001050161916_p12509132915214"><a name="en-us_topic_0000001050161916_p12509132915214"></a><a name="en-us_topic_0000001050161916_p12509132915214"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.1.5.1.4"><p id="en-us_topic_0000001050161916_p1650992972118"><a name="en-us_topic_0000001050161916_p1650992972118"></a><a name="en-us_topic_0000001050161916_p1650992972118"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="en-us_topic_0000001050161916_row18510102912216"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.1.5.1.1 "><p id="en-us_topic_0000001050161916_p15510162932115"><a name="en-us_topic_0000001050161916_p15510162932115"></a><a name="en-us_topic_0000001050161916_p15510162932115"></a>Content-Type</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="en-us_topic_0000001050161916_p19510112919214"><a name="en-us_topic_0000001050161916_p19510112919214"></a><a name="en-us_topic_0000001050161916_p19510112919214"></a>Mandatory</p>
</td>
<td class="cellrowborder" valign="top" width="16%" headers="mcps1.1.5.1.3 "><p id="en-us_topic_0000001050161916_p205101929182117"><a name="en-us_topic_0000001050161916_p205101929182117"></a><a name="en-us_topic_0000001050161916_p205101929182117"></a>application/json</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="en-us_topic_0000001050161916_p1951092919216"><a name="en-us_topic_0000001050161916_p1951092919216"></a><a name="en-us_topic_0000001050161916_p1951092919216"></a>Data format of a response.</p>
</td>
</tr>
</tbody>
</table>

**Response Body**

<a name="table161133108917"></a>
<table><thead align="left"><tr id="row1711313101916"><th class="cellrowborder" valign="top" width="20%" id="mcps1.1.4.1.1"><p id="p19113121010916"><a name="p19113121010916"></a><a name="p19113121010916"></a>Parameter</p>
</th>
<th class="cellrowborder" valign="top" width="20%" id="mcps1.1.4.1.2"><p id="p411391011910"><a name="p411391011910"></a><a name="p411391011910"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.1.4.1.3"><p id="p141131710591"><a name="p141131710591"></a><a name="p141131710591"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row611317101395"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.1.4.1.1 "><p id="p1667103310116"><a name="p1667103310116"></a><a name="p1667103310116"></a>returnCode</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.1.4.1.2 "><p id="p06716339113"><a name="p06716339113"></a><a name="p06716339113"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.4.1.3 "><p id="p86721033141114"><a name="p86721033141114"></a><a name="p86721033141114"></a>Result code. For details, please refer to <a href="error-code.md">Result Codes</a>.</p>
</td>
</tr>
<tr id="row131136101792"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.1.4.1.1 "><p id="p206722330110"><a name="p206722330110"></a><a name="p206722330110"></a>returnDesc</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.1.4.1.2 "><p id="p067215334117"><a name="p067215334117"></a><a name="p067215334117"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.4.1.3 "><p id="p2672103314119"><a name="p2672103314119"></a><a name="p2672103314119"></a>Result description.</p>
</td>
</tr>
<tr id="row13113171012911"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.1.4.1.1 "><p id="p10672123341117"><a name="p10672123341117"></a><a name="p10672123341117"></a>originAddresses</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.1.4.1.2 "><p id="p1672183381113"><a name="p1672183381113"></a><a name="p1672183381113"></a>String[]</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.4.1.3 "><p id="p1567212339113"><a name="p1567212339113"></a><a name="p1567212339113"></a>Departure place details.</p>
</td>
</tr>
<tr id="row1826615319118"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.1.4.1.1 "><p id="p16672633151115"><a name="p16672633151115"></a><a name="p16672633151115"></a>destinationAddresses</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.1.4.1.2 "><p id="p17672143351118"><a name="p17672143351118"></a><a name="p17672143351118"></a>String[]</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.4.1.3 "><p id="p1567293313118"><a name="p1567293313118"></a><a name="p1567293313118"></a>Destination details.</p>
</td>
</tr>
<tr id="row1341823112118"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.1.4.1.1 "><p id="p867293313110"><a name="p867293313110"></a><a name="p867293313110"></a>rows</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.1.4.1.2 "><p id="p4672433111117"><a name="p4672433111117"></a><a name="p4672433111117"></a><a href="output-params.md#section98851198326">Row</a>[]</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.4.1.3 "><p id="p1067214330117"><a name="p1067214330117"></a><a name="p1067214330117"></a>Distances and journey time of routes between departure places and destinations. </p>
</td>
</tr>
</tbody>
</table>

## Response Example<a name="section095094211614"></a>

**When the status code is 200:**

```
HTTP/1.1 200 OK
Content-type: application/json
{
    "originAddresses": [
        "12, Springfield, Prudhoe, Ovington, Northumberland, England, NE42 6EH, the United Kingdom",
        "Saint Cuthbert Without, Carlisle, Cumbria, England, the United Kingdom"
    ],
    "returnCode": "0",
    "destinationAddresses": [
        "Hedleyhope, Durham, England, DH7 9EY, the United Kingdom"
    ],
    "rows": [
        {
            "cells": [
                {
                    "duration": 2158.559,
                    "durationText": "35min",
                    "distance": 36129.102,
                    "distanceText": "36.1km",
                    "status": 0
                }
            ]
        },
        {
            "cells": [
                {
                    "duration": 4856.301,
                    "durationText": "1h20min",
                    "distance": 104685.306,
                    "distanceText": "104.7km",
                    "status": 0
                }
            ]
        }
    ],
    "returnDesc": "OK"
}
```

## Call Example<a name="section284195414164"></a>

```
public class DirectionsService {
    public static final String ROOT_URL = "https://mapapi.cloud.huawei.com/mapApi/v1/routeService/";

    public static final String connection = "?key=";

    public static final MediaType JSON = MediaType.parse("application/json; charset=utf-8");

    public static void matrixDriving(String serviceName, String apiKey) throws UnsupportedEncodingException {
        JSONObject json = new JSONObject();
        JSONArray origin = new JSONArray();
        JSONObject startingPoint_1 = new JSONObject();
        JSONObject startingPoint_2 = new JSONObject();
        JSONArray destination = new JSONArray();
        JSONObject endPoint = new JSONObject();

        try {
            startingPoint_1.put("lng", -1.894679);
            startingPoint_1.put("lat", 54.974887);

            startingPoint_2.put("lng", -2.882682);
            startingPoint_2.put("lat", 54.857616);

            origin.put(0, startingPoint_1);
            origin.put(1, startingPoint_2);

            endPoint.put("lng", -1.744955);
            endPoint.put("lat", 54.775040);

            destination.put(0, endPoint);

            json.put("origins", origin);
            json.put("destinations", destination);
            json.put("language", "en");

        } catch (JSONException e) {
            Log.e("error", e.getMessage());
        }
        RequestBody body = RequestBody.create(JSON, String.valueOf(json));

        OkHttpClient client = new OkHttpClient();
        Request request =
            new Request.Builder().url(ROOT_URL + serviceName + connection + URLEncoder.encode(apiKey, "UTF-8"))
                .post(body)
                .build();

        client.newCall(request).enqueue(new Callback() {
            @Override
            public void onFailure(Call call, IOException e) {
                Log.e("MatrixDriving", e.toString());
            }

            @Override
            public void onResponse(Call call, Response response) throws IOException {
                Log.d("MatrixDriving", response.body().string());
            }
        });
    }
}
```

