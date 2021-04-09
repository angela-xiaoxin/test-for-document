# Navigation<a name="EN-US_TOPIC_0000001099003570"></a>

This function allows users to plan driving routes for navigation. 

-   Deep link example

    ```
    mapapp://navigation?saddr=25.102916,55.165363&daddr=25.164610000000,55.228869000000&language=en&type=drive
    mapapp://navigation?saddr=home&daddr=company&language=en&type=drive
    mapapp://navigation?type=exit
    petalmaps:navigation?type=exit
    ```


-   App link example

    ```
    https://www.petalmaps.com/navigate/?saddr=25.102916,55.165363&daddr=25.164610000000,55.228869000000&type=drive&utm_source=fb
    ```

-   Parameters

    <a name="table1090724503720"></a>
    <table><thead align="left"><tr id="row1490734519378"><th class="cellrowborder" valign="top" width="20%" id="mcps1.1.5.1.1"><p id="p2090744523719"><a name="p2090744523719"></a><a name="p2090744523719"></a>Parameter</p>
    </th>
    <th class="cellrowborder" valign="top" width="15%" id="mcps1.1.5.1.2"><p id="p15907144593713"><a name="p15907144593713"></a><a name="p15907144593713"></a>Mandatory</p>
    </th>
    <th class="cellrowborder" valign="top" width="15%" id="mcps1.1.5.1.3"><p id="p18907164553714"><a name="p18907164553714"></a><a name="p18907164553714"></a>Type</p>
    </th>
    <th class="cellrowborder" valign="top" width="50%" id="mcps1.1.5.1.4"><p id="p14907114553715"><a name="p14907114553715"></a><a name="p14907114553715"></a>Description</p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="row139081145183718"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.1.5.1.1 "><p id="p125mcpsimp"><a name="p125mcpsimp"></a><a name="p125mcpsimp"></a>saddr</p>
    </td>
    <td class="cellrowborder" valign="top" width="15%" headers="mcps1.1.5.1.2 "><p id="p1134241864114"><a name="p1134241864114"></a><a name="p1134241864114"></a>No</p>
    </td>
    <td class="cellrowborder" valign="top" width="15%" headers="mcps1.1.5.1.3 "><p id="p127mcpsimp"><a name="p127mcpsimp"></a><a name="p127mcpsimp"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="p17293175516553"><a name="p17293175516553"></a><a name="p17293175516553"></a>Start point of navigation. You can set this parameter to a longitude-latitude place, or the home address (<strong id="b486331912577"><a name="b486331912577"></a><a name="b486331912577"></a>home</strong>) or company address (<strong id="b386914191579"><a name="b386914191579"></a><a name="b386914191579"></a>company</strong>) in Petal Maps. If this parameter is not set, the current location is used by default.</p>
    </td>
    </tr>
    <tr id="row152521016155515"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.1.5.1.1 "><p id="p1253121610559"><a name="p1253121610559"></a><a name="p1253121610559"></a>daddr</p>
    </td>
    <td class="cellrowborder" valign="top" width="15%" headers="mcps1.1.5.1.2 "><p id="p1925321615553"><a name="p1925321615553"></a><a name="p1925321615553"></a>Yes</p>
    </td>
    <td class="cellrowborder" valign="top" width="15%" headers="mcps1.1.5.1.3 "><p id="p1253111618557"><a name="p1253111618557"></a><a name="p1253111618557"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="p23338189307"><a name="p23338189307"></a><a name="p23338189307"></a>End point of navigation. You can set this parameter to a longitude-latitude place, or the home address (<strong id="b109892033155720"><a name="b109892033155720"></a><a name="b109892033155720"></a>home</strong>) or company address (<strong id="b799510336572"><a name="b799510336572"></a><a name="b799510336572"></a>company</strong>) in Petal Maps.</p>
    </td>
    </tr>
    <tr id="row2836418105512"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.1.5.1.1 "><p id="p1583731875514"><a name="p1583731875514"></a><a name="p1583731875514"></a>type</p>
    </td>
    <td class="cellrowborder" valign="top" width="15%" headers="mcps1.1.5.1.2 "><p id="p158376184552"><a name="p158376184552"></a><a name="p158376184552"></a>No</p>
    </td>
    <td class="cellrowborder" valign="top" width="15%" headers="mcps1.1.5.1.3 "><p id="p1183716180558"><a name="p1183716180558"></a><a name="p1183716180558"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="p201974431616"><a name="p201974431616"></a><a name="p201974431616"></a>Route planning type.</p>
    <a name="ul73435234217"></a><a name="ul73435234217"></a><ul id="ul73435234217"><li><strong id="b1576311211406"><a name="b1576311211406"></a><a name="b1576311211406"></a>drive</strong>: Plan the driving route.</li><li><strong id="b20795739309"><a name="b20795739309"></a><a name="b20795739309"></a>exit</strong>: Exit the navigation.</li></ul>
    <p id="p6333141843018"><a name="p6333141843018"></a><a name="p6333141843018"></a>The default value is <strong id="b1969513110118"><a name="b1969513110118"></a><a name="b1969513110118"></a>drive</strong>.</p>
    </td>
    </tr>
    <tr id="row990101825818"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.1.5.1.1 "><p id="p991018205810"><a name="p991018205810"></a><a name="p991018205810"></a>language</p>
    </td>
    <td class="cellrowborder" valign="top" width="15%" headers="mcps1.1.5.1.2 "><p id="p09121818588"><a name="p09121818588"></a><a name="p09121818588"></a>No</p>
    </td>
    <td class="cellrowborder" valign="top" width="15%" headers="mcps1.1.5.1.3 "><p id="p129120182587"><a name="p129120182587"></a><a name="p129120182587"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="p11809721621"><a name="p11809721621"></a><a name="p11809721621"></a>Navigation language.</p>
    <a name="ul1234422312214"></a><a name="ul1234422312214"></a><ul id="ul1234422312214"><li><strong id="b153345141918"><a name="b153345141918"></a><a name="b153345141918"></a>zh_CN</strong>: Chinese</li><li><strong id="b1530619167110"><a name="b1530619167110"></a><a name="b1530619167110"></a>en</strong>: English</li></ul>
    <p id="p1133491815304"><a name="p1133491815304"></a><a name="p1133491815304"></a>By default, the language set for the Petal Maps app is used for navigation.</p>
    </td>
    </tr>
    <tr id="row1376010542261"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.1.5.1.1 "><p id="p5416152215172"><a name="p5416152215172"></a><a name="p5416152215172"></a>utm_source</p>
    </td>
    <td class="cellrowborder" valign="top" width="15%" headers="mcps1.1.5.1.2 "><p id="p11416112217171"><a name="p11416112217171"></a><a name="p11416112217171"></a>No</p>
    </td>
    <td class="cellrowborder" valign="top" width="15%" headers="mcps1.1.5.1.3 "><p id="p174161322131710"><a name="p174161322131710"></a><a name="p174161322131710"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="p1884707181818"><a name="p1884707181818"></a><a name="p1884707181818"></a>Channel source. (For an app, the app package name or app name can be passed.)</p>
    </td>
    </tr>
    <tr id="row674113578268"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.1.5.1.1 "><p id="p1079613193187"><a name="p1079613193187"></a><a name="p1079613193187"></a>utm_medium</p>
    </td>
    <td class="cellrowborder" valign="top" width="15%" headers="mcps1.1.5.1.2 "><p id="p295410466206"><a name="p295410466206"></a><a name="p295410466206"></a>No</p>
    </td>
    <td class="cellrowborder" valign="top" width="15%" headers="mcps1.1.5.1.3 "><p id="p87968195185"><a name="p87968195185"></a><a name="p87968195185"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="p179641917180"><a name="p179641917180"></a><a name="p179641917180"></a>Media.</p>
    </td>
    </tr>
    <tr id="row69410022717"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.1.5.1.1 "><p id="p3790421101819"><a name="p3790421101819"></a><a name="p3790421101819"></a>utm_campaign</p>
    </td>
    <td class="cellrowborder" valign="top" width="15%" headers="mcps1.1.5.1.2 "><p id="p199621547172016"><a name="p199621547172016"></a><a name="p199621547172016"></a>No</p>
    </td>
    <td class="cellrowborder" valign="top" width="15%" headers="mcps1.1.5.1.3 "><p id="p12791021131813"><a name="p12791021131813"></a><a name="p12791021131813"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="p197917216189"><a name="p197917216189"></a><a name="p197917216189"></a>Campaign name.</p>
    </td>
    </tr>
    <tr id="row111090819271"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.1.5.1.1 "><p id="p12143122415186"><a name="p12143122415186"></a><a name="p12143122415186"></a>utm_term</p>
    </td>
    <td class="cellrowborder" valign="top" width="15%" headers="mcps1.1.5.1.2 "><p id="p162581249122012"><a name="p162581249122012"></a><a name="p162581249122012"></a>No</p>
    </td>
    <td class="cellrowborder" valign="top" width="15%" headers="mcps1.1.5.1.3 "><p id="p171439243189"><a name="p171439243189"></a><a name="p171439243189"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="p214362491810"><a name="p214362491810"></a><a name="p214362491810"></a>Campaign keyword.</p>
    </td>
    </tr>
    <tr id="row127010419275"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.1.5.1.1 "><p id="p923533412020"><a name="p923533412020"></a><a name="p923533412020"></a>utm_content</p>
    </td>
    <td class="cellrowborder" valign="top" width="15%" headers="mcps1.1.5.1.2 "><p id="p20306050102018"><a name="p20306050102018"></a><a name="p20306050102018"></a>No</p>
    </td>
    <td class="cellrowborder" valign="top" width="15%" headers="mcps1.1.5.1.3 "><p id="p13235123419206"><a name="p13235123419206"></a><a name="p13235123419206"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="p16235143419201"><a name="p16235143419201"></a><a name="p16235143419201"></a>Campaign content.</p>
    </td>
    </tr>
    </tbody>
    </table>


-   Sample code

    Intent mode:

    ```
    Uri content_url = Uri.parse(petalmaps: //navigation?saddr=25.102916,55.165363&daddr=25.164610000000,55.228869000000&type=drive &utm_source=fb);
    String uriString = "mapapp://navigation?saddr=25.102916,55.165363&daddr=25.164610000000,55.228869000000&language=en&type=drive"; 
    Uri content_url = Uri.parse(uriString);
    Intent intent = new Intent(Intent.ACTION_VIEW, content_url); 
    if (intent.resolveActivity(getPackageManager()) != null) {
         startActivity(intent); 
    }
    ```

    Link mode:

    ```
    https://www.petalmaps.com/ navigate/?saddr=25.102916,55.165363&daddr=25.164610000000,55.228869000000&type=drive&utm_source=fb
    ```

    The following figure shows the route planning result.

    ![](figures/en-us_image_0000001099163576.jpg)


