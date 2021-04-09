# 路线规划<a name="ZH-CN_TOPIC_0000001099661036"></a>

提供驾车路线规划功能。

-   Deeplink样例：

    ```
    mapapp://route?saddr=25.102916,55.165363&daddr=25.164610000000,55.228869000000&type=drive
    mapapp://route?saddr=home&daddr=company&type=drive
    petalmaps:route?saddr=home&daddr=company&type=drive
    ```


-   Applink样例

    ```
    https://www.petalmaps.com/routes/?saddr=25.102916,55.165363&daddr=25.164610000000,55.228869000000&type=drive&utm_source=fb
    ```

-   参数列表：

    <a name="table1090724503720"></a>
    <table><thead align="left"><tr id="row1490734519378"><th class="cellrowborder" valign="top" width="20%" id="mcps1.1.5.1.1"><p id="p2090744523719"><a name="p2090744523719"></a><a name="p2090744523719"></a>参数</p>
    </th>
    <th class="cellrowborder" valign="top" width="15%" id="mcps1.1.5.1.2"><p id="p15907144593713"><a name="p15907144593713"></a><a name="p15907144593713"></a>是否必选</p>
    </th>
    <th class="cellrowborder" valign="top" width="15%" id="mcps1.1.5.1.3"><p id="p18907164553714"><a name="p18907164553714"></a><a name="p18907164553714"></a>参数类型</p>
    </th>
    <th class="cellrowborder" valign="top" width="50%" id="mcps1.1.5.1.4"><p id="p14907114553715"><a name="p14907114553715"></a><a name="p14907114553715"></a>描述</p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="row139081145183718"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.1.5.1.1 "><p id="p125mcpsimp"><a name="p125mcpsimp"></a><a name="p125mcpsimp"></a>saddr</p>
    </td>
    <td class="cellrowborder" valign="top" width="15%" headers="mcps1.1.5.1.2 "><p id="p1134241864114"><a name="p1134241864114"></a><a name="p1134241864114"></a>否</p>
    </td>
    <td class="cellrowborder" valign="top" width="15%" headers="mcps1.1.5.1.3 "><p id="p127mcpsimp"><a name="p127mcpsimp"></a><a name="p127mcpsimp"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="p17293175516553"><a name="p17293175516553"></a><a name="p17293175516553"></a>路线规划的起点。支持设置为经纬度、花瓣地图的家庭地址“home”或公司地址“company”。如果不设置，默认取当前位置。</p>
    </td>
    </tr>
    <tr id="row152521016155515"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.1.5.1.1 "><p id="p1253121610559"><a name="p1253121610559"></a><a name="p1253121610559"></a>daddr</p>
    </td>
    <td class="cellrowborder" valign="top" width="15%" headers="mcps1.1.5.1.2 "><p id="p1925321615553"><a name="p1925321615553"></a><a name="p1925321615553"></a>是</p>
    </td>
    <td class="cellrowborder" valign="top" width="15%" headers="mcps1.1.5.1.3 "><p id="p1253111618557"><a name="p1253111618557"></a><a name="p1253111618557"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="p122531416155516"><a name="p122531416155516"></a><a name="p122531416155516"></a>路线规划的终点。支持设置为经纬度、花瓣地图的家庭地址“home”或公司地址“company”。</p>
    </td>
    </tr>
    <tr id="row2836418105512"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.1.5.1.1 "><p id="p1583731875514"><a name="p1583731875514"></a><a name="p1583731875514"></a>type</p>
    </td>
    <td class="cellrowborder" valign="top" width="15%" headers="mcps1.1.5.1.2 "><p id="p158376184552"><a name="p158376184552"></a><a name="p158376184552"></a>否</p>
    </td>
    <td class="cellrowborder" valign="top" width="15%" headers="mcps1.1.5.1.3 "><p id="p1183716180558"><a name="p1183716180558"></a><a name="p1183716180558"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="p446614371014"><a name="p446614371014"></a><a name="p446614371014"></a>drive：驾车路径规划。</p>
    </td>
    </tr>
    <tr id="row939955112178"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.1.5.1.1 "><p id="p5416152215172"><a name="p5416152215172"></a><a name="p5416152215172"></a>utm_source</p>
    </td>
    <td class="cellrowborder" valign="top" width="15%" headers="mcps1.1.5.1.2 "><p id="p11416112217171"><a name="p11416112217171"></a><a name="p11416112217171"></a>否</p>
    </td>
    <td class="cellrowborder" valign="top" width="15%" headers="mcps1.1.5.1.3 "><p id="p174161322131710"><a name="p174161322131710"></a><a name="p174161322131710"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="p1884707181818"><a name="p1884707181818"></a><a name="p1884707181818"></a>渠道来源（应用可以传入App包名或者应用名）。</p>
    </td>
    </tr>
    <tr id="row11630165615178"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.1.5.1.1 "><p id="p1079613193187"><a name="p1079613193187"></a><a name="p1079613193187"></a>utm_medium</p>
    </td>
    <td class="cellrowborder" valign="top" width="15%" headers="mcps1.1.5.1.2 "><p id="p295410466206"><a name="p295410466206"></a><a name="p295410466206"></a>否</p>
    </td>
    <td class="cellrowborder" valign="top" width="15%" headers="mcps1.1.5.1.3 "><p id="p87968195185"><a name="p87968195185"></a><a name="p87968195185"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="p179641917180"><a name="p179641917180"></a><a name="p179641917180"></a>媒介。</p>
    </td>
    </tr>
    <tr id="row10774111101813"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.1.5.1.1 "><p id="p3790421101819"><a name="p3790421101819"></a><a name="p3790421101819"></a>utm_campaign</p>
    </td>
    <td class="cellrowborder" valign="top" width="15%" headers="mcps1.1.5.1.2 "><p id="p199621547172016"><a name="p199621547172016"></a><a name="p199621547172016"></a>否</p>
    </td>
    <td class="cellrowborder" valign="top" width="15%" headers="mcps1.1.5.1.3 "><p id="p12791021131813"><a name="p12791021131813"></a><a name="p12791021131813"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="p197917216189"><a name="p197917216189"></a><a name="p197917216189"></a>运营活动名称。</p>
    </td>
    </tr>
    <tr id="row82081548185"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.1.5.1.1 "><p id="p12143122415186"><a name="p12143122415186"></a><a name="p12143122415186"></a>utm_term</p>
    </td>
    <td class="cellrowborder" valign="top" width="15%" headers="mcps1.1.5.1.2 "><p id="p162581249122012"><a name="p162581249122012"></a><a name="p162581249122012"></a>否</p>
    </td>
    <td class="cellrowborder" valign="top" width="15%" headers="mcps1.1.5.1.3 "><p id="p171439243189"><a name="p171439243189"></a><a name="p171439243189"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="p214362491810"><a name="p214362491810"></a><a name="p214362491810"></a>运营活动关键词。</p>
    </td>
    </tr>
    <tr id="row71295593174"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.1.5.1.1 "><p id="p923533412020"><a name="p923533412020"></a><a name="p923533412020"></a>utm_content</p>
    </td>
    <td class="cellrowborder" valign="top" width="15%" headers="mcps1.1.5.1.2 "><p id="p20306050102018"><a name="p20306050102018"></a><a name="p20306050102018"></a>否</p>
    </td>
    <td class="cellrowborder" valign="top" width="15%" headers="mcps1.1.5.1.3 "><p id="p13235123419206"><a name="p13235123419206"></a><a name="p13235123419206"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="p16235143419201"><a name="p16235143419201"></a><a name="p16235143419201"></a>运营活动内容。</p>
    </td>
    </tr>
    </tbody>
    </table>


-   代码样例

    Intent方式：

    ```
    Uri content_url = Uri.parse("petalmaps://route?saddr=25.102916,55.165363&daddr=25.164610000000,55.228869000000&type=drive&utm_source=fb"); 
    String uriString = "mapapp://route?saddr=25.102916,55.165363&daddr=25.164610000000,55.228869000000&type=drive"; 
    Uri content_url = Uri.parse(uriString);
    Intent intent = new Intent(Intent.ACTION_VIEW, content_url); 
    if (intent.resolveActivity(getPackageManager()) != null) {
         startActivity(intent); 
    }
    ```

    直接点击链接方式：

    ```
    https://www.petalmaps.com/routes/?saddr=home&daddr=company&type=drive&utm_source=fb
    ```

    运行后的效果如下图所示：

    ![](figures/zh-cn_image_0000001099661096.jpg)


