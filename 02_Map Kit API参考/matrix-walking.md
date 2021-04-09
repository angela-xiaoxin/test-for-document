# 规划步行路径<a name="ZH-CN_TOPIC_0000001099181256"></a>

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

提供多点之间步行路径规划功能。

## 场景描述<a name="section733593991210"></a>

无

## 使用约束<a name="section5561220132"></a>

-   仅提供150km以内的路径规划能力。
-   起点或终点数不能超过5个。
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
<td class="cellrowborder" valign="top" width="80%" headers="mcps1.1.3.3.1 "><p id="p9827850185319"><a name="p9827850185319"></a><a name="p9827850185319"></a>https://mapapi.cloud.huawei.com/mapApi/v1/routeService/walkingMatrix?key=<i><span class="varname" id="varname168423113295"><a name="varname168423113295"></a><a name="varname168423113295"></a>API KEY</span></i></p>
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

**Rquest Body**

<a name="table77202273214"></a>
<table><thead align="left"><tr id="row11729225326"><th class="cellrowborder" valign="top" width="18%" id="mcps1.1.5.1.1"><p id="p87210228329"><a name="p87210228329"></a><a name="p87210228329"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="14.000000000000002%" id="mcps1.1.5.1.2"><p id="p129581029151016"><a name="p129581029151016"></a><a name="p129581029151016"></a>是否必选</p>
</th>
<th class="cellrowborder" valign="top" width="18%" id="mcps1.1.5.1.3"><p id="p18726222329"><a name="p18726222329"></a><a name="p18726222329"></a>参数类型</p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.1.5.1.4"><p id="p67242210323"><a name="p67242210323"></a><a name="p67242210323"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="row1872122203212"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="p6274235149"><a name="p6274235149"></a><a name="p6274235149"></a>origin</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="p1295852931019"><a name="p1295852931019"></a><a name="p1295852931019"></a>是</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.3 "><p id="p95731160406"><a name="p95731160406"></a><a name="p95731160406"></a><a href="input-params.md#section1256775182913">Coordinate</a>[]</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="p13388122364019"><a name="p13388122364019"></a><a name="p13388122364019"></a>起点的经纬度，不能超过5个。</p>
</td>
</tr>
<tr id="row1772422133216"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="p127414351843"><a name="p127414351843"></a><a name="p127414351843"></a>destination</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="p995892921018"><a name="p995892921018"></a><a name="p995892921018"></a>是</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.3 "><p id="p55731816194019"><a name="p55731816194019"></a><a name="p55731816194019"></a><a href="input-params.md#section1256775182913">Coordinate</a>[]</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="p123881323134015"><a name="p123881323134015"></a><a name="p123881323134015"></a>终点的经纬度，不能超过5个。起点和终点的直线距离不能超过150km。</p>
</td>
</tr>
<tr id="row1872722153217"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="p127413514420"><a name="p127413514420"></a><a name="p127413514420"></a>language</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="p19581029131019"><a name="p19581029131019"></a><a name="p19581029131019"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.3 "><p id="p327483510411"><a name="p327483510411"></a><a name="p327483510411"></a>String(&lt;=6)</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="p62741135148"><a name="p62741135148"></a><a name="p62741135148"></a>文字指引/描述的语种。目前只支持zh_CN和en。</p>
</td>
</tr>
</tbody>
</table>

## 请求示例<a name="section19799143115168"></a>

```
POST https://mapapi.cloud.huawei.com/mapApi/v1/routeService/walkingMatrix?key=API KEY HTTP/1.1 
Content-Type: application/json 
Accept: application/json 
{
    "origins": [
        {
            "lng": 2.359782,
            "lat": 48.862544
        },
        {
            "lng": 2.358537,
            "lat": 48.861443
        }
    ],
    "destinations": [
        {
            "lng": 2.361702,
            "lat": 48.86042
        }
    ],
    "language": "en"
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

<a name="table157795718811"></a>
<table><thead align="left"><tr id="row277457982"><th class="cellrowborder" valign="top" width="20%" id="mcps1.1.4.1.1"><p id="p27785719818"><a name="p27785719818"></a><a name="p27785719818"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="20%" id="mcps1.1.4.1.2"><p id="p16771157882"><a name="p16771157882"></a><a name="p16771157882"></a>参数类型</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.1.4.1.3"><p id="p47712576815"><a name="p47712576815"></a><a name="p47712576815"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="row20774571781"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.1.4.1.1 "><p id="p112811901011"><a name="p112811901011"></a><a name="p112811901011"></a>returnCode</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.1.4.1.2 "><p id="p1028139181014"><a name="p1028139181014"></a><a name="p1028139181014"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.4.1.3 "><p id="p201582019431"><a name="p201582019431"></a><a name="p201582019431"></a>返回码，具体请参见<a href="error-code.md">错误码</a>。</p>
</td>
</tr>
<tr id="row167717571887"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.1.4.1.1 "><p id="p42916991013"><a name="p42916991013"></a><a name="p42916991013"></a>returnDesc</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.1.4.1.2 "><p id="p2029299107"><a name="p2029299107"></a><a name="p2029299107"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.4.1.3 "><p id="p112918911013"><a name="p112918911013"></a><a name="p112918911013"></a>返回值描述。</p>
</td>
</tr>
<tr id="row878145712815"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.1.4.1.1 "><p id="p929994103"><a name="p929994103"></a><a name="p929994103"></a>originAddresses</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.1.4.1.2 "><p id="p229597102"><a name="p229597102"></a><a name="p229597102"></a>String[]</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.4.1.3 "><p id="p1293910103"><a name="p1293910103"></a><a name="p1293910103"></a>Origins的地址详情。</p>
</td>
</tr>
<tr id="row637214311109"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.1.4.1.1 "><p id="p42949111013"><a name="p42949111013"></a><a name="p42949111013"></a>destinationAddresses</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.1.4.1.2 "><p id="p6291696102"><a name="p6291696102"></a><a name="p6291696102"></a>String[]</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.4.1.3 "><p id="p029894102"><a name="p029894102"></a><a name="p029894102"></a>Destinations的地址详情。</p>
</td>
</tr>
<tr id="row165894311108"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.1.4.1.1 "><p id="p202919918102"><a name="p202919918102"></a><a name="p202919918102"></a>rows</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.1.4.1.2 "><p id="p729199171019"><a name="p729199171019"></a><a name="p729199171019"></a><a href="output-params.md#section98851198326">Row</a>[]</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.4.1.3 "><p id="p172918911018"><a name="p172918911018"></a><a name="p172918911018"></a>Origins和Destinations两两进行路径规划后的计算出来的时长和距离。</p>
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
    "originAddresses": [
        "76, Rue des Archives, 75003, Le Marais, 3e Arrondissement, Paris, Île-de-France, France",
        "62, Rue des Archives, 75003, 3e Arrondissement, Paris, Île-de-France, France"
    ],
    "returnCode": "0",
    "destinationAddresses": [
        "101 T, Rue Des Coutures Saint-Gervais, 75003, 3e Arrondissement, Paris, Île-de-France, France"
    ],
    "rows": [
        {
            "cells": [
                {
                    "duration": 268.684,
                    "durationText": "4min",
                    "distance": 353.573,
                    "distanceText": "354m",
                    "status": 0
                }
            ]
        },
        {
            "cells": [
                {
                    "duration": 256.39,
                    "durationText": "4min",
                    "distance": 352.386,
                    "distanceText": "352m",
                    "status": 0
                }
            ]
        }
    ],
    "returnDesc": "OK"
}
```

## 调用示例<a name="section284195414164"></a>

```
public class DirectionsService {
    public static final String ROOT_URL = "https://mapapi.cloud.huawei.com/mapApi/v1/routeService/";

    public static final String connection = "?key=";

    public static final MediaType JSON = MediaType.parse("application/json; charset=utf-8");

    public static void matrixWalking(String serviceName, String apiKey) throws UnsupportedEncodingException {
        JSONObject json = new JSONObject();
        JSONArray origin = new JSONArray();
        JSONObject startingPoint_1 = new JSONObject();
        JSONObject startingPoint_2 = new JSONObject();
        JSONArray destination = new JSONArray();
        JSONObject endPoint = new JSONObject();

        try {
            startingPoint_1.put("lng", 2.359782);
            startingPoint_1.put("lat", 48.862544);

            startingPoint_2.put("lng", 2.358537);
            startingPoint_2.put("lat", 48.861443);

            origin.put(0, startingPoint_1);
            origin.put(1, startingPoint_2);

            endPoint.put("lng", 2.361702);
            endPoint.put("lat", 48.860420);

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
                Log.e("MatrixWalking", e.toString());
            }

            @Override
            public void onResponse(Call call, Response response) throws IOException {
                Log.d("MatrixWalking", response.body().string());
            }
        });
    }
}

```

