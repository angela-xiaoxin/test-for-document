# Walking Route Planning<a name="EN-US_TOPIC_0000001099181256"></a>

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

Plans walking routes between multiple places. 

## Scenario<a name="section733593991210"></a>

None.

## Restrictions<a name="section5561220132"></a>

-   A route can only be planned within a distance of 150 kilometers.
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
<td class="cellrowborder" valign="top" width="80%" headers="mcps1.1.3.3.1 "><p id="p9827850185319"><a name="p9827850185319"></a><a name="p9827850185319"></a>https://mapapi.cloud.huawei.com/mapApi/v1/routeService/walkingMatrix?key=<i><span class="varname" id="varname168423113295"><a name="varname168423113295"></a><a name="varname168423113295"></a>API KEY</span></i></p>
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
<tbody><tr id="row1872122203212"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="p6274235149"><a name="p6274235149"></a><a name="p6274235149"></a>origin</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="p1295852931019"><a name="p1295852931019"></a><a name="p1295852931019"></a>Mandatory</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.3 "><p id="p95731160406"><a name="p95731160406"></a><a name="p95731160406"></a><a href="input-params.md#section1256775182913">Coordinate</a>[]</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="p13388122364019"><a name="p13388122364019"></a><a name="p13388122364019"></a>Longitudes and latitudes of the departure places. A maximum of 5 departure places are allowed.</p>
</td>
</tr>
<tr id="row1772422133216"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="p127414351843"><a name="p127414351843"></a><a name="p127414351843"></a>destination</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="p995892921018"><a name="p995892921018"></a><a name="p995892921018"></a>Mandatory</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.3 "><p id="p55731816194019"><a name="p55731816194019"></a><a name="p55731816194019"></a><a href="input-params.md#section1256775182913">Coordinate</a>[]</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="p123881323134015"><a name="p123881323134015"></a><a name="p123881323134015"></a>Longitudes and latitudes of the destinations. A maximum of 5 destinations are allowed. The linear distance between the departure place and destination cannot exceed 150 km.</p>
</td>
</tr>
<tr id="row1872722153217"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="p127413514420"><a name="p127413514420"></a><a name="p127413514420"></a>language</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="p19581029131019"><a name="p19581029131019"></a><a name="p19581029131019"></a>Optional</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.3 "><p id="p327483510411"><a name="p327483510411"></a><a name="p327483510411"></a>String(&lt;=6)</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="p62741135148"><a name="p62741135148"></a><a name="p62741135148"></a>Language of the distance and journey time descriptions in the returned result. Currently, only <strong id="b1344862443815"><a name="b1344862443815"></a><a name="b1344862443815"></a>zh_CN</strong> (Chinese) and <strong id="b1945362414384"><a name="b1945362414384"></a><a name="b1945362414384"></a>en</strong> (English) are supported.</p>
</td>
</tr>
</tbody>
</table>

## Request Example<a name="section19799143115168"></a>

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

<a name="table157795718811"></a>
<table><thead align="left"><tr id="row277457982"><th class="cellrowborder" valign="top" width="20%" id="mcps1.1.4.1.1"><p id="p27785719818"><a name="p27785719818"></a><a name="p27785719818"></a>Parameter</p>
</th>
<th class="cellrowborder" valign="top" width="20%" id="mcps1.1.4.1.2"><p id="p16771157882"><a name="p16771157882"></a><a name="p16771157882"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.1.4.1.3"><p id="p47712576815"><a name="p47712576815"></a><a name="p47712576815"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row20774571781"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.1.4.1.1 "><p id="p112811901011"><a name="p112811901011"></a><a name="p112811901011"></a>returnCode</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.1.4.1.2 "><p id="p1028139181014"><a name="p1028139181014"></a><a name="p1028139181014"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.4.1.3 "><p id="p201582019431"><a name="p201582019431"></a><a name="p201582019431"></a>Result code. For details, please refer to <a href="error-code.md">Result Codes</a>.</p>
</td>
</tr>
<tr id="row167717571887"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.1.4.1.1 "><p id="p42916991013"><a name="p42916991013"></a><a name="p42916991013"></a>returnDesc</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.1.4.1.2 "><p id="p2029299107"><a name="p2029299107"></a><a name="p2029299107"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.4.1.3 "><p id="p112918911013"><a name="p112918911013"></a><a name="p112918911013"></a>Result description.</p>
</td>
</tr>
<tr id="row878145712815"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.1.4.1.1 "><p id="p929994103"><a name="p929994103"></a><a name="p929994103"></a>originAddresses</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.1.4.1.2 "><p id="p229597102"><a name="p229597102"></a><a name="p229597102"></a>String[]</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.4.1.3 "><p id="p1293910103"><a name="p1293910103"></a><a name="p1293910103"></a>Departure place details.</p>
</td>
</tr>
<tr id="row637214311109"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.1.4.1.1 "><p id="p42949111013"><a name="p42949111013"></a><a name="p42949111013"></a>destinationAddresses</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.1.4.1.2 "><p id="p6291696102"><a name="p6291696102"></a><a name="p6291696102"></a>String[]</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.4.1.3 "><p id="p029894102"><a name="p029894102"></a><a name="p029894102"></a>Destination details.</p>
</td>
</tr>
<tr id="row165894311108"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.1.4.1.1 "><p id="p202919918102"><a name="p202919918102"></a><a name="p202919918102"></a>rows</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.1.4.1.2 "><p id="p729199171019"><a name="p729199171019"></a><a name="p729199171019"></a><a href="output-params.md#section98851198326">Row</a>[]</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.4.1.3 "><p id="p172918911018"><a name="p172918911018"></a><a name="p172918911018"></a>Distances and journey time of routes between departure places and destinations. </p>
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
        "76, Rue des Archives, 75003, Le Marais, 3e Arrondissement, Paris, ??le-de-France, France",
        "62, Rue des Archives, 75003, 3e Arrondissement, Paris, ??le-de-France, France"
    ],
    "returnCode": "0",
    "destinationAddresses": [
        "101 T, Rue Des Coutures Saint-Gervais, 75003, 3e Arrondissement, Paris, ??le-de-France, France"
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

## Call Example<a name="section284195414164"></a>

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

