# Walking Route Planning<a name="EN-US_TOPIC_0000001099181294"></a>

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

Plans walking routes between two places.

## Scenario<a name="section733593991210"></a>

None.

## Restrictions<a name="section5561220132"></a>

-   A route can only be planned within a distance of 150 kilometers. 
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
<td class="cellrowborder" valign="top" width="80%" headers="mcps1.1.3.3.1 "><p id="p9827850185319"><a name="p9827850185319"></a><a name="p9827850185319"></a>https://mapapi.cloud.huawei.com/mapApi/v1/routeService/walking?key=<i><span class="varname" id="varname168423113295"><a name="varname168423113295"></a><a name="varname168423113295"></a>API KEY</span></i></p>
<div class="note" id="note151551941102710"><a name="note151551941102710"></a><a name="note151551941102710"></a><span class="notetitle"> NOTE: </span><div class="notebody"><a name="ol42140252365"></a><a name="ol42140252365"></a><ol id="ol42140252365"><li>For details about how to obtain an API key, please refer to <a href="en-us_topic_0000001099501072.md#section169441820428">Obtaining the API Key</a>.</li><li>You need to call the <strong id="b144635512110"><a name="b144635512110"></a><a name="b144635512110"></a>URLEncoder.encode("Your apiKey", "UTF-8")</strong> method to encode the API key using <strong id="b646418511120"><a name="b646418511120"></a><a name="b646418511120"></a>encodeURI</strong>. For example, if the original API key is <strong id="b14422031224"><a name="b14422031224"></a><a name="b14422031224"></a>ABC/DFG+</strong>, the conversion result is <strong id="b2431137214"><a name="b2431137214"></a><a name="b2431137214"></a>ABC%2FDFG%2B</strong>.</li></ol>
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

<a name="requestParameter"></a>
<table><thead align="left"><tr id="row970062619437"><th class="cellrowborder" valign="top" width="18%" id="mcps1.1.5.1.1"><p id="p97014263437"><a name="p97014263437"></a><a name="p97014263437"></a>Parameter</p>
</th>
<th class="cellrowborder" valign="top" width="14.000000000000002%" id="mcps1.1.5.1.2"><p id="p129581029151016"><a name="p129581029151016"></a><a name="p129581029151016"></a>Mandatory/Optional</p>
</th>
<th class="cellrowborder" valign="top" width="18%" id="mcps1.1.5.1.3"><p id="p10701142610436"><a name="p10701142610436"></a><a name="p10701142610436"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.1.5.1.4"><p id="p37011926194315"><a name="p37011926194315"></a><a name="p37011926194315"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row1170072610438"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="p6274235149"><a name="p6274235149"></a><a name="p6274235149"></a>origin</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="p1295852931019"><a name="p1295852931019"></a><a name="p1295852931019"></a>Mandatory</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.3 "><p id="p122741935644"><a name="p122741935644"></a><a name="p122741935644"></a><a href="input-params.md#section1256775182913">Coordinate</a></p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="p112741435141"><a name="p112741435141"></a><a name="p112741435141"></a>Longitude and latitude of the departure place.</p>
</td>
</tr>
<tr id="row14571142419526"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="p127414351843"><a name="p127414351843"></a><a name="p127414351843"></a>destination</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="p995892921018"><a name="p995892921018"></a><a name="p995892921018"></a>Mandatory</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.3 "><p id="p13274183514419"><a name="p13274183514419"></a><a name="p13274183514419"></a><a href="input-params.md#section1256775182913">Coordinate</a></p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="p32748351849"><a name="p32748351849"></a><a name="p32748351849"></a>Longitude and latitude of the destination.</p>
</td>
</tr>
<tr id="row13103125125214"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="p127413514420"><a name="p127413514420"></a><a name="p127413514420"></a>language</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="p19581029131019"><a name="p19581029131019"></a><a name="p19581029131019"></a>Optional</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.3 "><p id="p327483510411"><a name="p327483510411"></a><a name="p327483510411"></a>String(&lt;=6)</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="p62741135148"><a name="p62741135148"></a><a name="p62741135148"></a>Language of the distance and journey time descriptions in the returned result. Currently, only <strong id="b7291142141116"><a name="b7291142141116"></a><a name="b7291142141116"></a>zh_CN</strong> (Chinese) and <strong id="b929762161117"><a name="b929762161117"></a><a name="b929762161117"></a>en</strong> (English) are supported.</p>
</td>
</tr>
</tbody>
</table>

## Request Example<a name="section19799143115168"></a>

```
POST https://mapapi.cloud.huawei.com/mapApi/v1/routeService/walking?key=API KEY   HTTP/1.1 
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

<a name="responseParameter"></a>
<table><thead align="left"><tr id="row2706122611434"><th class="cellrowborder" valign="top" width="20%" id="mcps1.1.4.1.1"><p id="p3706026184313"><a name="p3706026184313"></a><a name="p3706026184313"></a>Parameter</p>
</th>
<th class="cellrowborder" valign="top" width="20%" id="mcps1.1.4.1.2"><p id="p6707172611434"><a name="p6707172611434"></a><a name="p6707172611434"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.1.4.1.3"><p id="p17707326104319"><a name="p17707326104319"></a><a name="p17707326104319"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row1770622618437"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.1.4.1.1 "><p id="p34611221056"><a name="p34611221056"></a><a name="p34611221056"></a>returnCode</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.1.4.1.2 "><p id="p94613228514"><a name="p94613228514"></a><a name="p94613228514"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.4.1.3 "><p id="p25641012103820"><a name="p25641012103820"></a><a name="p25641012103820"></a>Result code. For details, please refer to <a href="error-code.md">Result Codes</a>.</p>
</td>
</tr>
<tr id="row2070692604311"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.1.4.1.1 "><p id="p1346112211518"><a name="p1346112211518"></a><a name="p1346112211518"></a>returnDesc</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.1.4.1.2 "><p id="p7461322754"><a name="p7461322754"></a><a name="p7461322754"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.4.1.3 "><p id="p1046622055"><a name="p1046622055"></a><a name="p1046622055"></a>Result description.</p>
</td>
</tr>
<tr id="row965493485314"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.1.4.1.1 "><p id="p24620221951"><a name="p24620221951"></a><a name="p24620221951"></a>routes</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.1.4.1.2 "><p id="p0469223518"><a name="p0469223518"></a><a name="p0469223518"></a><a href="output-params.md#section05097566301">Route</a>[]</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.4.1.3 "><p id="p14615221854"><a name="p14615221854"></a><a name="p14615221854"></a>Planned routes from the departure place to the destination. If no routes are available, an empty array will be returned.</p>
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
                    "duration": 12.926,
                    "durationText": "1min",
                    "durationInTraffic": 0,
                    "distance": 12.023,
                    "startLocation": {
                        "lng": -4.6652902,
                        "lat": 54.21660782
                    },
                    "startAddress": "German, Isle of Man, United Kingdom",
                    "distanceText": "12m",
                    "steps": [
                        {
                            "duration": 12.926,
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

    public static void Walking(String serviceName, String apiKey) throws UnsupportedEncodingException {
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
                Log.e("Walking", e.toString());
            }

            @Override
            public void onResponse(Call call, Response response) throws IOException {
                Log.d("Walking", response.body().string());
            }
        });
    }
}
```

