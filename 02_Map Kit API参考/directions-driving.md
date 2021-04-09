# 规划驾车路径<a name="ZH-CN_TOPIC_0000001145541119"></a>

-   [功能介绍](#section8455201431219)
-   [场景描述](#section733593991210)
-   [使用约束](#section5561220132)
-   [接口原型](#section12176172981317)
-   [请求参数](#section1044255015145)
-   [请求示例](#section19799143115168)
-   [响应参数](#section193511835151612)
-   [响应示例](#section095094211614)
-   [调用示例](#section284195414164)

## 功能介绍<a name="section8455201431219"></a>

提供两点之间驾车路径规划能力。

## 场景描述<a name="section733593991210"></a>

无

## 使用约束<a name="section5561220132"></a>

-   支持一次请求返回多条路线，最多支持3条路线。
-   最多支持5个途经点。
-   服务调用量的限制请查看[服务定价](zh-cn_topic_0000001145860925.md)。

## 接口原型<a name="section12176172981317"></a>

<a name="table11154520143815"></a>
<table><tbody><tr id="row18154202003811"><th class="firstcol" valign="top" width="20%" id="mcps1.1.3.1.1"><p id="p101546202386"><a name="p101546202386"></a><a name="p101546202386"></a>承载协议</p>
</th>
<td class="cellrowborder" valign="top" width="80%" headers="mcps1.1.3.1.1 "><p id="p81541720123818"><a name="p81541720123818"></a><a name="p81541720123818"></a>HTTPS POST</p>
</td>
</tr>
<tr id="row1115462019387"><th class="firstcol" valign="top" width="20%" id="mcps1.1.3.2.1"><p id="p12756174203813"><a name="p12756174203813"></a><a name="p12756174203813"></a>接口方向</p>
</th>
<td class="cellrowborder" valign="top" width="80%" headers="mcps1.1.3.2.1 "><p id="p16154112093811"><a name="p16154112093811"></a><a name="p16154112093811"></a>开发者-&gt;华为地图服务器</p>
</td>
</tr>
<tr id="row215413208388"><th class="firstcol" valign="top" width="20%" id="mcps1.1.3.3.1"><p id="p19782114513386"><a name="p19782114513386"></a><a name="p19782114513386"></a>接口URL</p>
</th>
<td class="cellrowborder" valign="top" width="80%" headers="mcps1.1.3.3.1 "><p id="p9827850185319"><a name="p9827850185319"></a><a name="p9827850185319"></a>https://mapapi.cloud.huawei.com/mapApi/v1/routeService/driving?key=<i><span class="varname" id="varname168423113295"><a name="varname168423113295"></a><a name="varname168423113295"></a>API KEY</span></i></p>
<div class="note" id="note65176364306"><a name="note65176364306"></a><a name="note65176364306"></a><span class="notetitle"> 说明： </span><div class="notebody"><a name="zh-cn_topic_0000001099181294_ol42140252365"></a><a name="zh-cn_topic_0000001099181294_ol42140252365"></a><ol id="zh-cn_topic_0000001099181294_ol42140252365"><li>获取<i><span class="varname" id="zh-cn_topic_0000001099181294_varname6145746111817"><a name="zh-cn_topic_0000001099181294_varname6145746111817"></a><a name="zh-cn_topic_0000001099181294_varname6145746111817"></a>API KEY</span></i>的方式请参见<a href="zh-cn_topic_0000001099501072.md#section169441820428">获取API Key</a>。</li><li>使用API Key时需要调用URLEncoder.encode("Your apiKey", "UTF-8")方法对API Key进行encodeURI编码。例如：原始API Key：ABC/DFG+ ，转换结果：ABC%2FDFG%2B。</li></ol>
</div></div>
</td>
</tr>
<tr id="row39361834214"><th class="firstcol" valign="top" width="20%" id="mcps1.1.3.4.1"><p id="p59410184422"><a name="p59410184422"></a><a name="p59410184422"></a>数据格式</p>
</th>
<td class="cellrowborder" valign="top" width="80%" headers="mcps1.1.3.4.1 "><p id="p171991908351"><a name="p171991908351"></a><a name="p171991908351"></a>请求消息：Content-Type: application/json</p>
<p id="p919916013510"><a name="p919916013510"></a><a name="p919916013510"></a>响应消息：Content-Type: application/json</p>
</td>
</tr>
</tbody>
</table>

## 请求参数<a name="section1044255015145"></a>

**Request Header**

<a name="table1845425124915"></a>
<table><thead align="left"><tr id="zh-cn_topic_0000001050161916_row445417514491"><th class="cellrowborder" valign="top" width="20%" id="mcps1.1.5.1.1"><p id="zh-cn_topic_0000001050161916_p15454956493"><a name="zh-cn_topic_0000001050161916_p15454956493"></a><a name="zh-cn_topic_0000001050161916_p15454956493"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="14.000000000000002%" id="mcps1.1.5.1.2"><p id="zh-cn_topic_0000001050161916_p7454159496"><a name="zh-cn_topic_0000001050161916_p7454159496"></a><a name="zh-cn_topic_0000001050161916_p7454159496"></a>是否必选</p>
</th>
<th class="cellrowborder" valign="top" width="16%" id="mcps1.1.5.1.3"><p id="zh-cn_topic_0000001050161916_p24541659497"><a name="zh-cn_topic_0000001050161916_p24541659497"></a><a name="zh-cn_topic_0000001050161916_p24541659497"></a>参数类型</p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.1.5.1.4"><p id="zh-cn_topic_0000001050161916_p34549513499"><a name="zh-cn_topic_0000001050161916_p34549513499"></a><a name="zh-cn_topic_0000001050161916_p34549513499"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="zh-cn_topic_0000001050161916_row84546564911"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.1.5.1.1 "><p id="zh-cn_topic_0000001050161916_p16591286492"><a name="zh-cn_topic_0000001050161916_p16591286492"></a><a name="zh-cn_topic_0000001050161916_p16591286492"></a>Content-Type</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="zh-cn_topic_0000001050161916_p2058087492"><a name="zh-cn_topic_0000001050161916_p2058087492"></a><a name="zh-cn_topic_0000001050161916_p2058087492"></a>是</p>
</td>
<td class="cellrowborder" valign="top" width="16%" headers="mcps1.1.5.1.3 "><p id="zh-cn_topic_0000001050161916_p85718154918"><a name="zh-cn_topic_0000001050161916_p85718154918"></a><a name="zh-cn_topic_0000001050161916_p85718154918"></a>application/json</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="zh-cn_topic_0000001050161916_p35512818497"><a name="zh-cn_topic_0000001050161916_p35512818497"></a><a name="zh-cn_topic_0000001050161916_p35512818497"></a>请求消息的数据格式。</p>
</td>
</tr>
</tbody>
</table>

**Request Body**

<a name="table15122457103219"></a>
<table><thead align="left"><tr id="row13123205753213"><th class="cellrowborder" valign="top" width="18%" id="mcps1.1.5.1.1"><p id="p91231578321"><a name="p91231578321"></a><a name="p91231578321"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="14.000000000000002%" id="mcps1.1.5.1.2"><p id="p129581029151016"><a name="p129581029151016"></a><a name="p129581029151016"></a>是否必选</p>
</th>
<th class="cellrowborder" valign="top" width="18%" id="mcps1.1.5.1.3"><p id="p201231157173218"><a name="p201231157173218"></a><a name="p201231157173218"></a>参数类型</p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.1.5.1.4"><p id="p1123057123216"><a name="p1123057123216"></a><a name="p1123057123216"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="row9123157173217"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="p6274235149"><a name="p6274235149"></a><a name="p6274235149"></a>origin</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="p1295852931019"><a name="p1295852931019"></a><a name="p1295852931019"></a>是</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.3 "><p id="p122741935644"><a name="p122741935644"></a><a name="p122741935644"></a><a href="input-params.md#section1256775182913">Coordinate</a></p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="p112741435141"><a name="p112741435141"></a><a name="p112741435141"></a>起点的经纬度。</p>
</td>
</tr>
<tr id="row1312355763212"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="p127414351843"><a name="p127414351843"></a><a name="p127414351843"></a>destination</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="p995892921018"><a name="p995892921018"></a><a name="p995892921018"></a>是</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.3 "><p id="p13274183514419"><a name="p13274183514419"></a><a name="p13274183514419"></a><a href="input-params.md#section1256775182913">Coordinate</a></p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="p32748351849"><a name="p32748351849"></a><a name="p32748351849"></a>终点的经纬度。</p>
</td>
</tr>
<tr id="row1412316579327"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="p127413514420"><a name="p127413514420"></a><a name="p127413514420"></a>waypoints</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="p19581029131019"><a name="p19581029131019"></a><a name="p19581029131019"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.3 "><p id="p327483510411"><a name="p327483510411"></a><a name="p327483510411"></a><a href="input-params.md#section1256775182913">Coordinate</a>[]</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="p62741135148"><a name="p62741135148"></a><a name="p62741135148"></a>途经点。最多可以输入5个途经点。</p>
</td>
</tr>
<tr id="row8578311103312"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="p1571298183411"><a name="p1571298183411"></a><a name="p1571298183411"></a>viaType</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="p457915118334"><a name="p457915118334"></a><a name="p457915118334"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.3 "><p id="p118281191341"><a name="p118281191341"></a><a name="p118281191341"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="p151802314346"><a name="p151802314346"></a><a name="p151802314346"></a>途径点类型，是via类型还是stopover类型。</p>
<a name="ul48071538372"></a><a name="ul48071538372"></a><ul id="ul48071538372"><li>false：stopover类型（默认）</li><li>true：via类型</li></ul>
</td>
</tr>
<tr id="row17974121119338"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="p1471220812346"><a name="p1471220812346"></a><a name="p1471220812346"></a>optimize</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="p49740119338"><a name="p49740119338"></a><a name="p49740119338"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.3 "><p id="p1782811913410"><a name="p1782811913410"></a><a name="p1782811913410"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="p518013117342"><a name="p518013117342"></a><a name="p518013117342"></a>是否对途径点进行优化。</p>
<a name="ul1917165911376"></a><a name="ul1917165911376"></a><ul id="ul1917165911376"><li>false：不进行途径点优化（默认）</li><li>true：进行途径点优化</li></ul>
</td>
</tr>
<tr id="row8342512203311"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="p15712188173411"><a name="p15712188173411"></a><a name="p15712188173411"></a>alternatives</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="p13342101233310"><a name="p13342101233310"></a><a name="p13342101233310"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.3 "><p id="p10828419143417"><a name="p10828419143417"></a><a name="p10828419143417"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="p171801312347"><a name="p171801312347"></a><a name="p171801312347"></a>如果设置为true，可以返回多条规划路线结果。</p>
<p id="p12181173193419"><a name="p12181173193419"></a><a name="p12181173193419"></a>取值包括：</p>
<a name="ul3378046384"></a><a name="ul3378046384"></a><ul id="ul3378046384"><li>true</li><li>false（默认）</li></ul>
<div class="caution" id="note14922719189"><a name="note14922719189"></a><a name="note14922719189"></a><span class="cautiontitle"> 注意： </span><div class="cautionbody"><p id="p2091627201811"><a name="p2091627201811"></a><a name="p2091627201811"></a>如果设置了途经点时，不能使用多路线功能。</p>
</div></div>
</td>
</tr>
<tr id="row187131312163314"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="p87127812342"><a name="p87127812342"></a><a name="p87127812342"></a>avoid</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="p5713191293314"><a name="p5713191293314"></a><a name="p5713191293314"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.3 "><p id="p1582851911344"><a name="p1582851911344"></a><a name="p1582851911344"></a>int[]</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="p518116319340"><a name="p518116319340"></a><a name="p518116319340"></a>表示计算出的路径应避免所指示的特性，取值包括：</p>
<a name="ul13587194673714"></a><a name="ul13587194673714"></a><ul id="ul13587194673714"><li>0：时间最短</li><li>1：避免经过收费的公路</li><li>2：避开高速公路</li><li>4：距离优先</li><li>8：避免轮渡</li></ul>
<p id="p2181183118347"><a name="p2181183118347"></a><a name="p2181183118347"></a>默认按时间最短返回。</p>
</td>
</tr>
<tr id="row11911513193316"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="p9712118103410"><a name="p9712118103410"></a><a name="p9712118103410"></a>departAt</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="p1591171314339"><a name="p1591171314339"></a><a name="p1591171314339"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.3 "><p id="p58281197341"><a name="p58281197341"></a><a name="p58281197341"></a>long</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="p1618183163413"><a name="p1618183163413"></a><a name="p1618183163413"></a>预计出发时间。以自UTC 1970年1月1日午夜以来的秒数为单位。</p>
<p id="p121811331183413"><a name="p121811331183413"></a><a name="p121811331183413"></a>必须是当前或者未来时间，不能是过去时间。</p>
</td>
</tr>
<tr id="row1742031311339"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="p13712128103410"><a name="p13712128103410"></a><a name="p13712128103410"></a>trafficMode</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="p12420613193311"><a name="p12420613193311"></a><a name="p12420613193311"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.3 "><p id="p1082881953417"><a name="p1082881953417"></a><a name="p1082881953417"></a>int</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="p21811317348"><a name="p21811317348"></a><a name="p21811317348"></a>时间预估模型。取值包括：</p>
<a name="ul334515319378"></a><a name="ul334515319378"></a><ul id="ul334515319378"><li>0：best guess（默认）</li><li>1：路况差于历史平均水平</li><li>2：路况优于历史平均水平</li></ul>
</td>
</tr>
<tr id="row16840101363311"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="p971215863416"><a name="p971215863416"></a><a name="p971215863416"></a>language</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="p984061319338"><a name="p984061319338"></a><a name="p984061319338"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.3 "><p id="p17828191917345"><a name="p17828191917345"></a><a name="p17828191917345"></a>String(&lt;=6)</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="p12181143116345"><a name="p12181143116345"></a><a name="p12181143116345"></a>文字指引/描述的语种。目前只支持zh_CN和en。</p>
</td>
</tr>
</tbody>
</table>

## 请求示例<a name="section19799143115168"></a>

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

## 响应参数<a name="section193511835151612"></a>

**状态码为200时：**

**Response Header**

<a name="table06641185395"></a>
<table><thead align="left"><tr id="zh-cn_topic_0000001050161916_row1150982918214"><th class="cellrowborder" valign="top" width="20%" id="mcps1.1.5.1.1"><p id="zh-cn_topic_0000001050161916_p10509329102114"><a name="zh-cn_topic_0000001050161916_p10509329102114"></a><a name="zh-cn_topic_0000001050161916_p10509329102114"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="14.000000000000002%" id="mcps1.1.5.1.2"><p id="zh-cn_topic_0000001050161916_p16509129132117"><a name="zh-cn_topic_0000001050161916_p16509129132117"></a><a name="zh-cn_topic_0000001050161916_p16509129132117"></a>是否必选</p>
</th>
<th class="cellrowborder" valign="top" width="16%" id="mcps1.1.5.1.3"><p id="zh-cn_topic_0000001050161916_p12509132915214"><a name="zh-cn_topic_0000001050161916_p12509132915214"></a><a name="zh-cn_topic_0000001050161916_p12509132915214"></a>参数类型</p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.1.5.1.4"><p id="zh-cn_topic_0000001050161916_p1650992972118"><a name="zh-cn_topic_0000001050161916_p1650992972118"></a><a name="zh-cn_topic_0000001050161916_p1650992972118"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="zh-cn_topic_0000001050161916_row18510102912216"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.1.5.1.1 "><p id="zh-cn_topic_0000001050161916_p15510162932115"><a name="zh-cn_topic_0000001050161916_p15510162932115"></a><a name="zh-cn_topic_0000001050161916_p15510162932115"></a>Content-Type</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="zh-cn_topic_0000001050161916_p19510112919214"><a name="zh-cn_topic_0000001050161916_p19510112919214"></a><a name="zh-cn_topic_0000001050161916_p19510112919214"></a>是</p>
</td>
<td class="cellrowborder" valign="top" width="16%" headers="mcps1.1.5.1.3 "><p id="zh-cn_topic_0000001050161916_p205101929182117"><a name="zh-cn_topic_0000001050161916_p205101929182117"></a><a name="zh-cn_topic_0000001050161916_p205101929182117"></a>application/json</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="zh-cn_topic_0000001050161916_p1951092919216"><a name="zh-cn_topic_0000001050161916_p1951092919216"></a><a name="zh-cn_topic_0000001050161916_p1951092919216"></a>响应消息的数据格式。</p>
</td>
</tr>
</tbody>
</table>

**Response Body**

<a name="table1566715241678"></a>
<table><thead align="left"><tr id="row766718241178"><th class="cellrowborder" valign="top" width="20%" id="mcps1.1.4.1.1"><p id="p16671824079"><a name="p16671824079"></a><a name="p16671824079"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="20%" id="mcps1.1.4.1.2"><p id="p1166710247717"><a name="p1166710247717"></a><a name="p1166710247717"></a>参数类型</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.1.4.1.3"><p id="p866716241572"><a name="p866716241572"></a><a name="p866716241572"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="row12668924572"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.1.4.1.1 "><p id="p389092417820"><a name="p389092417820"></a><a name="p389092417820"></a>returnCode</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.1.4.1.2 "><p id="p16890112419815"><a name="p16890112419815"></a><a name="p16890112419815"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.4.1.3 "><p id="p188901124285"><a name="p188901124285"></a><a name="p188901124285"></a>返回码，具体请参见<a href="error-code.md">错误码</a>。</p>
</td>
</tr>
<tr id="row196681524377"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.1.4.1.1 "><p id="p689022419817"><a name="p689022419817"></a><a name="p689022419817"></a>returnDesc</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.1.4.1.2 "><p id="p6890524280"><a name="p6890524280"></a><a name="p6890524280"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.4.1.3 "><p id="p4891424681"><a name="p4891424681"></a><a name="p4891424681"></a>返回值描述。</p>
</td>
</tr>
<tr id="row1668924973"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.1.4.1.1 "><p id="p1489113247811"><a name="p1489113247811"></a><a name="p1489113247811"></a>routes</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.1.4.1.2 "><p id="p1889142416816"><a name="p1889142416816"></a><a name="p1889142416816"></a><a href="output-params.md#section05097566301">Route</a>[]</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.4.1.3 "><p id="p14891172416812"><a name="p14891172416812"></a><a name="p14891172416812"></a>从起点到目的地的规划路径。如果没有结果，返回空数组。</p>
</td>
</tr>
</tbody>
</table>

## 响应示例<a name="section095094211614"></a>

**状态码为200时：**

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

## 调用示例<a name="section284195414164"></a>

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

