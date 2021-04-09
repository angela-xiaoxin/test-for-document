# Driving Route Planning<a name="EN-US_TOPIC_0000001145541119"></a>

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

Plans driving routes between two places. 

## Scenario<a name="section733593991210"></a>

None.

## Restrictions<a name="section5561220132"></a>

-   Up to 3 routes can be returned for each request.
-   Up to 5 waypoints can be specified. 
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
<td class="cellrowborder" valign="top" width="80%" headers="mcps1.1.3.3.1 "><p id="p9827850185319"><a name="p9827850185319"></a><a name="p9827850185319"></a>https://mapapi.cloud.huawei.com/mapApi/v1/routeService/driving?key=<i><span class="varname" id="varname168423113295"><a name="varname168423113295"></a><a name="varname168423113295"></a>API KEY</span></i></p>
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

<a name="table15122457103219"></a>
<table><thead align="left"><tr id="row13123205753213"><th class="cellrowborder" valign="top" width="18%" id="mcps1.1.5.1.1"><p id="p91231578321"><a name="p91231578321"></a><a name="p91231578321"></a>Parameter</p>
</th>
<th class="cellrowborder" valign="top" width="14.000000000000002%" id="mcps1.1.5.1.2"><p id="p129581029151016"><a name="p129581029151016"></a><a name="p129581029151016"></a>Mandatory/Optional</p>
</th>
<th class="cellrowborder" valign="top" width="18%" id="mcps1.1.5.1.3"><p id="p201231157173218"><a name="p201231157173218"></a><a name="p201231157173218"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.1.5.1.4"><p id="p1123057123216"><a name="p1123057123216"></a><a name="p1123057123216"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row9123157173217"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="p6274235149"><a name="p6274235149"></a><a name="p6274235149"></a>origin</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="p1295852931019"><a name="p1295852931019"></a><a name="p1295852931019"></a>Mandatory</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.3 "><p id="p122741935644"><a name="p122741935644"></a><a name="p122741935644"></a><a href="input-params.md#section1256775182913">Coordinate</a></p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="p112741435141"><a name="p112741435141"></a><a name="p112741435141"></a>Longitude and latitude of the departure place.</p>
</td>
</tr>
<tr id="row1312355763212"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="p127414351843"><a name="p127414351843"></a><a name="p127414351843"></a>destination</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="p995892921018"><a name="p995892921018"></a><a name="p995892921018"></a>Mandatory</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.3 "><p id="p13274183514419"><a name="p13274183514419"></a><a name="p13274183514419"></a><a href="input-params.md#section1256775182913">Coordinate</a></p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="p32748351849"><a name="p32748351849"></a><a name="p32748351849"></a>Longitude and latitude of the destination.</p>
</td>
</tr>
<tr id="row1412316579327"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="p127413514420"><a name="p127413514420"></a><a name="p127413514420"></a>waypoints</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="p19581029131019"><a name="p19581029131019"></a><a name="p19581029131019"></a>Optional</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.3 "><p id="p327483510411"><a name="p327483510411"></a><a name="p327483510411"></a><a href="input-params.md#section1256775182913">Coordinate</a>[]</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="p62741135148"><a name="p62741135148"></a><a name="p62741135148"></a>Waypoints. You can specify up to 5 waypoints.</p>
</td>
</tr>
<tr id="row8578311103312"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="p1571298183411"><a name="p1571298183411"></a><a name="p1571298183411"></a>viaType</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="p457915118334"><a name="p457915118334"></a><a name="p457915118334"></a>Optional</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.3 "><p id="p118281191341"><a name="p118281191341"></a><a name="p118281191341"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="p151802314346"><a name="p151802314346"></a><a name="p151802314346"></a>Waypoint type. The options are as follows:</p>
<a name="ul48071538372"></a><a name="ul48071538372"></a><ul id="ul48071538372"><li><strong id="b651324432518"><a name="b651324432518"></a><a name="b651324432518"></a>false</strong> (default): stopover</li><li><strong id="b456634832518"><a name="b456634832518"></a><a name="b456634832518"></a>true</strong>: via (pass-by)</li></ul>
</td>
</tr>
<tr id="row17974121119338"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="p1471220812346"><a name="p1471220812346"></a><a name="p1471220812346"></a>optimize</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="p49740119338"><a name="p49740119338"></a><a name="p49740119338"></a>Optional</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.3 "><p id="p1782811913410"><a name="p1782811913410"></a><a name="p1782811913410"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="p518013117342"><a name="p518013117342"></a><a name="p518013117342"></a>Indicates whether to optimize the waypoint.</p>
<a name="ul1917165911376"></a><a name="ul1917165911376"></a><ul id="ul1917165911376"><li><strong id="b43791414266"><a name="b43791414266"></a><a name="b43791414266"></a>false</strong> (default): no</li><li><strong id="b158981426265"><a name="b158981426265"></a><a name="b158981426265"></a>true</strong>: yes</li></ul>
</td>
</tr>
<tr id="row8342512203311"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="p15712188173411"><a name="p15712188173411"></a><a name="p15712188173411"></a>alternatives</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="p13342101233310"><a name="p13342101233310"></a><a name="p13342101233310"></a>Optional</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.3 "><p id="p10828419143417"><a name="p10828419143417"></a><a name="p10828419143417"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="p171801312347"><a name="p171801312347"></a><a name="p171801312347"></a>Indicates whether to return multiple planned routes. </p>
<p id="p12181173193419"><a name="p12181173193419"></a><a name="p12181173193419"></a>The options are as follows:</p>
<a name="ul3378046384"></a><a name="ul3378046384"></a><ul id="ul3378046384"><li><strong id="b199441040152616"><a name="b199441040152616"></a><a name="b199441040152616"></a>true</strong>: yes</li><li><strong id="b13158171412615"><a name="b13158171412615"></a><a name="b13158171412615"></a>false</strong> (default): no</li></ul>
<div class="caution" id="note14922719189"><a name="note14922719189"></a><a name="note14922719189"></a><span class="cautiontitle"> CAUTION: </span><div class="cautionbody"><p id="p2091627201811"><a name="p2091627201811"></a><a name="p2091627201811"></a>This parameter is unavailable when waypoints are set.</p>
</div></div>
</td>
</tr>
<tr id="row187131312163314"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="p87127812342"><a name="p87127812342"></a><a name="p87127812342"></a>avoid</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="p5713191293314"><a name="p5713191293314"></a><a name="p5713191293314"></a>Optional</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.3 "><p id="p1582851911344"><a name="p1582851911344"></a><a name="p1582851911344"></a>int[]</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="p518116319340"><a name="p518116319340"></a><a name="p518116319340"></a>Indicates the specified type of roads to be avoided. The options are as follows:</p>
<a name="ul13587194673714"></a><a name="ul13587194673714"></a><ul id="ul13587194673714"><li><strong id="b6369248312"><a name="b6369248312"></a><a name="b6369248312"></a>0</strong>: Take least time.</li><li><strong id="b619412215315"><a name="b619412215315"></a><a name="b619412215315"></a>1</strong>: Avoid toll roads.</li><li><strong id="b1862916612311"><a name="b1862916612311"></a><a name="b1862916612311"></a>2</strong>: Avoid expressways.</li></ul>
<p id="p2181183118347"><a name="p2181183118347"></a><a name="p2181183118347"></a>If this parameter is not included in the request, the route taking the least time will be returned by default.</p>
</td>
</tr>
<tr id="row11911513193316"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="p9712118103410"><a name="p9712118103410"></a><a name="p9712118103410"></a>departAt</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="p1591171314339"><a name="p1591171314339"></a><a name="p1591171314339"></a>Optional</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.3 "><p id="p58281197341"><a name="p58281197341"></a><a name="p58281197341"></a>long</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="p1618183163413"><a name="p1618183163413"></a><a name="p1618183163413"></a>Estimated departure time, in seconds since 00:00 on January 1, 1970 (UTC).</p>
<p id="p121811331183413"><a name="p121811331183413"></a><a name="p121811331183413"></a>The value must be the current time or a future time.</p>
</td>
</tr>
<tr id="row1742031311339"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="p13712128103410"><a name="p13712128103410"></a><a name="p13712128103410"></a>trafficMode</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="p12420613193311"><a name="p12420613193311"></a><a name="p12420613193311"></a>Optional</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.3 "><p id="p1082881953417"><a name="p1082881953417"></a><a name="p1082881953417"></a>int</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="p21811317348"><a name="p21811317348"></a><a name="p21811317348"></a>Time estimation mode. The options are as follows:</p>
<a name="ul334515319378"></a><a name="ul334515319378"></a><ul id="ul334515319378"><li><strong id="b203901941202719"><a name="b203901941202719"></a><a name="b203901941202719"></a>0</strong> (default): best guess</li><li><strong id="b991844332713"><a name="b991844332713"></a><a name="b991844332713"></a>1</strong>: The traffic condition is worse than the historical average.</li><li><strong id="b285494918278"><a name="b285494918278"></a><a name="b285494918278"></a>2</strong>: The traffic condition is better than the historical average.</li></ul>
</td>
</tr>
<tr id="row16840101363311"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="p971215863416"><a name="p971215863416"></a><a name="p971215863416"></a>language</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="p984061319338"><a name="p984061319338"></a><a name="p984061319338"></a>Optional</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.3 "><p id="p17828191917345"><a name="p17828191917345"></a><a name="p17828191917345"></a>String(&lt;=6)</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="p12181143116345"><a name="p12181143116345"></a><a name="p12181143116345"></a>Language of the distance and journey time descriptions in the returned result. Currently, only <strong id="b1635201242814"><a name="b1635201242814"></a><a name="b1635201242814"></a>zh_CN</strong> (Chinese) and <strong id="b163521712142811"><a name="b163521712142811"></a><a name="b163521712142811"></a>en</strong> (English) are supported.</p>
</td>
</tr>
</tbody>
</table>

## Request Example<a name="section19799143115168"></a>

```
POST https://mapapi.cloud.huawei.com/mapApi/v1/routeService/driving?key=API KEY   HTTP/1.1 
Content-Type: application/json 
Accept: application/json
{ 
    "origin": { 
        "lng": -4.66529, 
        "lat": 54.216608 
    }, 
    "destination": { 
        "lng": -4.66552, 
        "lat": 54.2166 
    } 
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

<a name="table1566715241678"></a>
<table><thead align="left"><tr id="row766718241178"><th class="cellrowborder" valign="top" width="20%" id="mcps1.1.4.1.1"><p id="p16671824079"><a name="p16671824079"></a><a name="p16671824079"></a>Parameter</p>
</th>
<th class="cellrowborder" valign="top" width="20%" id="mcps1.1.4.1.2"><p id="p1166710247717"><a name="p1166710247717"></a><a name="p1166710247717"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.1.4.1.3"><p id="p866716241572"><a name="p866716241572"></a><a name="p866716241572"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row12668924572"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.1.4.1.1 "><p id="p389092417820"><a name="p389092417820"></a><a name="p389092417820"></a>returnCode</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.1.4.1.2 "><p id="p16890112419815"><a name="p16890112419815"></a><a name="p16890112419815"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.4.1.3 "><p id="p188901124285"><a name="p188901124285"></a><a name="p188901124285"></a>Result code. For details, please refer to <a href="error-code.md">Result Codes</a>.</p>
</td>
</tr>
<tr id="row196681524377"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.1.4.1.1 "><p id="p689022419817"><a name="p689022419817"></a><a name="p689022419817"></a>returnDesc</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.1.4.1.2 "><p id="p6890524280"><a name="p6890524280"></a><a name="p6890524280"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.4.1.3 "><p id="p4891424681"><a name="p4891424681"></a><a name="p4891424681"></a>Result description.</p>
</td>
</tr>
<tr id="row1668924973"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.1.4.1.1 "><p id="p1489113247811"><a name="p1489113247811"></a><a name="p1489113247811"></a>routes</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.1.4.1.2 "><p id="p1889142416816"><a name="p1889142416816"></a><a name="p1889142416816"></a><a href="output-params.md#section05097566301">Route</a>[]</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.4.1.3 "><p id="p14891172416812"><a name="p14891172416812"></a><a name="p14891172416812"></a>Planned routes from the departure place to the destination. If no routes are available, an empty array will be returned.</p>
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
    "routes": [
        {
            "paths": [
                {
                    "duration": 0.962,
                    "durationText": "1min",
                    "durationInTrafficText": "1min",
                    "durationInTraffic": 1,
                    "distance": 12.023,
                    "startLocation": {
                        "lng": -4.6652902,
                        "lat": 54.21660782
                    },
                    "startAddress": "German, Isle of Man, United Kingdom",
                    "distanceText": "12m",
                    "steps": [
                        {
                            "duration": 0.962,
                            "orientation": 0,
                            "durationText": "1min",
                            "distance": 12.023,
                            "startLocation": {
                                "lng": -4.6652902,
                                "lat": 54.21660782
                            },
                            "instruction": "",
                            "action": "end",
                            "distanceText": "12m",
                            "endLocation": {
                                "lng": -4.66552194,
                                "lat": 54.21669556
                            },
                            "polyline": [
                                {
                                    "lng": -4.6652902,
                                    "lat": 54.21660782
                                },
                                {
                                    "lng": -4.66529083,
                                    "lat": 54.21660806
                                },
                                {
                                    "lng": -4.66529083,
                                    "lat": 54.21660806
                                },
                                {
                                    "lng": -4.66540472,
                                    "lat": 54.21665
                                },
                                {
                                    "lng": -4.66544603,
                                    "lat": 54.21666592
                                }
                            ],
                            "roadName": "Poortown Road"
                        }
                    ],
                    "endLocation": {
                        "lng": -4.66544603,
                        "lat": 54.21666592
                    },
                    "endAddress": "German, Isle of Man, United Kingdom"
                }
            ],
            "bounds": {
                "southwest": {
                    "lng": -4.66552194,
                    "lat": 54.21584278
                },
                "northeast": {
                    "lng": -4.66216583,
                    "lat": 54.21669556
                }
            }
        }
    ],
    "returnCode": "0",
    "returnDesc": "OK"
}
```

## Call Example<a name="section284195414164"></a>

```
public class DirectionsService {
    public static final String ROOT_URL = "https://mapapi.cloud.huawei.com/mapApi/v1/routeService/";

    public static final String connection = "?key=";

    public static final MediaType JSON = MediaType.parse("application/json; charset=utf-8");

    public static void driving(String serviceName, String apiKey) throws UnsupportedEncodingException {
        JSONObject json = new JSONObject();
        JSONObject origin = new JSONObject();
        JSONObject destination = new JSONObject();

        try {
            origin.put("lng", -4.66529);
            origin.put("lat", 54.216608);

            destination.put("lng", -4.66552);
            destination.put("lat", 54.2166);

            json.put("origin", origin);
            json.put("destination", destination);
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
                Log.e("driving", e.toString());
            }

            @Override
            public void onResponse(Call call, Response response) throws IOException {
                Log.d("driving", response.body().string());
            }
        });
    }
}
```

