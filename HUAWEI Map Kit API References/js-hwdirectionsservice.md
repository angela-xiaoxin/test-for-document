# HWDirectionsService<a name="EN-US_TOPIC_0000001145941053"></a>

-   [Overview](#se65847112f2f4428b84787c1560e6fe9)
-   [Build Method](#sd235c8da5dfa44a1a26f87b4384b21c8)
-   [Public Methods](#sa8974ad3b7c244e785745427113f1233)
-   [DirectionsRequest](#sc8b104b22ee140de9fe5d33b398e435e)
-   [DirectionsResult](#s5136fc4b19984160b25e2cf8d90bf122)
-   [DrivingDirectionsRequest](#scc98f453d97a4d16885cdf2f02a705fc)

## Overview<a name="se65847112f2f4428b84787c1560e6fe9"></a>

Plans routes for walking, bicycling, and driving. 

## Build Method<a name="sd235c8da5dfa44a1a26f87b4384b21c8"></a>

<a name="t03b59690908a491fabdfa861684517ca"></a>
<table><thead align="left"><tr id="r543bd1791bdf4b9ab1efc4c8e45cab21"><th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.1"><p id="ad00e842d2709410681ceba077b0c7651"><a name="ad00e842d2709410681ceba077b0c7651"></a><a name="ad00e842d2709410681ceba077b0c7651"></a><strong id="a829699fd1a1a460387212e37c13a1f9a"><a name="a829699fd1a1a460387212e37c13a1f9a"></a><a name="a829699fd1a1a460387212e37c13a1f9a"></a>Build Method</strong></p>
</th>
<th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.2"><p id="ae087d153a1604b42a75c5a947917c0a3"><a name="ae087d153a1604b42a75c5a947917c0a3"></a><a name="ae087d153a1604b42a75c5a947917c0a3"></a><strong id="b169404325446"><a name="b169404325446"></a><a name="b169404325446"></a>Description</strong></p>
</th>
</tr>
</thead>
<tbody><tr id="rc401b64295e5459da59e9a958ed73e4c"><td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.1 "><p id="ad3086fd3bb5d48e1bff9f29b15a09fe4"><a name="ad3086fd3bb5d48e1bff9f29b15a09fe4"></a><a name="ad3086fd3bb5d48e1bff9f29b15a09fe4"></a>HWMapJsSDK.HWDirectionsService()</p>
</td>
<td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.2 "><p id="a10923d3bc31b48c6a20e069bf03026d3"><a name="a10923d3bc31b48c6a20e069bf03026d3"></a><a name="a10923d3bc31b48c6a20e069bf03026d3"></a>-</p>
</td>
</tr>
</tbody>
</table>

## Public Methods<a name="sa8974ad3b7c244e785745427113f1233"></a>

<a name="te47731b2267148db9592dd0ca60e0a78"></a>
<table><thead align="left"><tr id="rcbf82e15e60e4c8cb9e69d9fae3a3639"><th class="cellrowborder" valign="top" width="28.000000000000004%" id="mcps1.1.5.1.1"><p id="aafd4f1c2b164419b9d3d551fa022e9dc"><a name="aafd4f1c2b164419b9d3d551fa022e9dc"></a><a name="aafd4f1c2b164419b9d3d551fa022e9dc"></a><strong id="b4836153684413"><a name="b4836153684413"></a><a name="b4836153684413"></a>Method</strong></p>
</th>
<th class="cellrowborder" valign="top" width="18%" id="mcps1.1.5.1.2"><p id="a3ab0cb0aa175468fa57a78e1563f5fb2"><a name="a3ab0cb0aa175468fa57a78e1563f5fb2"></a><a name="a3ab0cb0aa175468fa57a78e1563f5fb2"></a><strong id="b8585153954412"><a name="b8585153954412"></a><a name="b8585153954412"></a>Description</strong></p>
</th>
<th class="cellrowborder" valign="top" width="41%" id="mcps1.1.5.1.3"><p id="ab0976bc5d82540ddbfe807b10ec52761"><a name="ab0976bc5d82540ddbfe807b10ec52761"></a><a name="ab0976bc5d82540ddbfe807b10ec52761"></a><strong id="afc4429f3a020409ab6032b82c0d9acb4"><a name="afc4429f3a020409ab6032b82c0d9acb4"></a><a name="afc4429f3a020409ab6032b82c0d9acb4"></a>Type</strong></p>
</th>
<th class="cellrowborder" valign="top" width="13%" id="mcps1.1.5.1.4"><p id="adbbc2f91e2454d2a9a6c9da5e3c0145b"><a name="adbbc2f91e2454d2a9a6c9da5e3c0145b"></a><a name="adbbc2f91e2454d2a9a6c9da5e3c0145b"></a><strong id="ab53d636dff6647848040d049155c7b0b"><a name="ab53d636dff6647848040d049155c7b0b"></a><a name="ab53d636dff6647848040d049155c7b0b"></a>Return Value</strong></p>
</th>
</tr>
</thead>
<tbody><tr id="re39585984cbd4cfe979e931f3cf77a77"><td class="cellrowborder" valign="top" width="28.000000000000004%" headers="mcps1.1.5.1.1 "><p id="a7bcbec87f14048cfafc8e4775078de34"><a name="a7bcbec87f14048cfafc8e4775078de34"></a><a name="a7bcbec87f14048cfafc8e4775078de34"></a>routeWalking(request, callback)</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.2 "><p id="ae01730dd71e242f685c537da1040a3d2"><a name="ae01730dd71e242f685c537da1040a3d2"></a><a name="ae01730dd71e242f685c537da1040a3d2"></a>Plans walking routes.</p>
</td>
<td class="cellrowborder" valign="top" width="41%" headers="mcps1.1.5.1.3 "><a name="u273d7f9008784be794de3157d35f1180"></a><a name="u273d7f9008784be794de3157d35f1180"></a><ul id="u273d7f9008784be794de3157d35f1180"><li><strong id="b1170772456"><a name="b1170772456"></a><a name="b1170772456"></a>request</strong>: <a href="#sc8b104b22ee140de9fe5d33b398e435e">DirectionsRequest</a>, which is the body of the walking route planning request.</li><li><strong id="b21651144194514"><a name="b21651144194514"></a><a name="b21651144194514"></a>callback</strong>: <strong id="b3410184817458"><a name="b3410184817458"></a><a name="b3410184817458"></a>Function(<a href="#s5136fc4b19984160b25e2cf8d90bf122">DirectionsResult</a>, StatusCode)</strong>, which is the callback function for walking route planning.</li></ul>
</td>
<td class="cellrowborder" valign="top" width="13%" headers="mcps1.1.5.1.4 "><p id="a85ca02a08ee1402ea719f425265ce7a5"><a name="a85ca02a08ee1402ea719f425265ce7a5"></a><a name="a85ca02a08ee1402ea719f425265ce7a5"></a>-</p>
</td>
</tr>
<tr id="r285f3bcedec942079b5d7edb2484038a"><td class="cellrowborder" valign="top" width="28.000000000000004%" headers="mcps1.1.5.1.1 "><p id="ac5365b4dc619412885f8e21d264eb3d0"><a name="ac5365b4dc619412885f8e21d264eb3d0"></a><a name="ac5365b4dc619412885f8e21d264eb3d0"></a>routeBicycling(request, callback)</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.2 "><p id="a463333610f094dbf9a41a493fc168dee"><a name="a463333610f094dbf9a41a493fc168dee"></a><a name="a463333610f094dbf9a41a493fc168dee"></a>Plans bicycling routes.</p>
</td>
<td class="cellrowborder" valign="top" width="41%" headers="mcps1.1.5.1.3 "><a name="u96e09b642b8a4e6b8d3ff615cd7425d7"></a><a name="u96e09b642b8a4e6b8d3ff615cd7425d7"></a><ul id="u96e09b642b8a4e6b8d3ff615cd7425d7"><li><strong id="b667913156465"><a name="b667913156465"></a><a name="b667913156465"></a>request</strong>: <a href="#sc8b104b22ee140de9fe5d33b398e435e">DirectionsRequest</a>, which is the body of the bicycling route planning request.</li><li><strong id="b174248252460"><a name="b174248252460"></a><a name="b174248252460"></a>callback</strong>: <strong id="b1242462554615"><a name="b1242462554615"></a><a name="b1242462554615"></a>Function(<a href="#s5136fc4b19984160b25e2cf8d90bf122">DirectionsResult</a>, StatusCode)</strong>, which is the callback function for bicycling route planning.</li></ul>
</td>
<td class="cellrowborder" valign="top" width="13%" headers="mcps1.1.5.1.4 "><p id="ad12116f7ff6a43d786182125d944158a"><a name="ad12116f7ff6a43d786182125d944158a"></a><a name="ad12116f7ff6a43d786182125d944158a"></a>-</p>
</td>
</tr>
<tr id="r1cd5d8f54f8a4663b775fd991cc37e4b"><td class="cellrowborder" valign="top" width="28.000000000000004%" headers="mcps1.1.5.1.1 "><p id="aa2df7b47484e4148bea8ab7a39072dea"><a name="aa2df7b47484e4148bea8ab7a39072dea"></a><a name="aa2df7b47484e4148bea8ab7a39072dea"></a>routeDriving(request, callback)</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.2 "><p id="af8230e657a534d12bf2861460b5bee51"><a name="af8230e657a534d12bf2861460b5bee51"></a><a name="af8230e657a534d12bf2861460b5bee51"></a>Plans driving routes.</p>
</td>
<td class="cellrowborder" valign="top" width="41%" headers="mcps1.1.5.1.3 "><a name="u6d1906c3bb12472cb4179d033d360170"></a><a name="u6d1906c3bb12472cb4179d033d360170"></a><ul id="u6d1906c3bb12472cb4179d033d360170"><li><strong id="b10662854144610"><a name="b10662854144610"></a><a name="b10662854144610"></a>request</strong>: <a href="#scc98f453d97a4d16885cdf2f02a705fc">DrivingDirectionsRequest</a>, which is the body of the driving route planning request.</li><li><strong id="b8993722184713"><a name="b8993722184713"></a><a name="b8993722184713"></a>callback</strong>: <strong id="b59251006488"><a name="b59251006488"></a><a name="b59251006488"></a>Function(<a href="#s5136fc4b19984160b25e2cf8d90bf122">DirectionsResult</a>, StatusCode)</strong>, which is the callback function for driving route planning.</li></ul>
</td>
<td class="cellrowborder" valign="top" width="13%" headers="mcps1.1.5.1.4 "><p id="a75e3f33bf72a417fb7a3dd4744ed18fd"><a name="a75e3f33bf72a417fb7a3dd4744ed18fd"></a><a name="a75e3f33bf72a417fb7a3dd4744ed18fd"></a>-</p>
</td>
</tr>
</tbody>
</table>

>![](public_sys-resources/icon-note.gif) **NOTE:** 
>In the methods,  **StatusCode**  indicates the result code returned for API call. For details, please refer to  [Result Codes](error-code.md).

## DirectionsRequest<a name="sc8b104b22ee140de9fe5d33b398e435e"></a>

<a name="t0e320bc23bb54bba8977c8971e28396a"></a>
<table><thead align="left"><tr id="r98f146ae649a4ecc846ab9202d6c9638"><th class="cellrowborder" valign="top" width="22.8%" id="mcps1.1.5.1.1"><p id="a49eb14ad68ed4c0d97402037fa4afb21"><a name="a49eb14ad68ed4c0d97402037fa4afb21"></a><a name="a49eb14ad68ed4c0d97402037fa4afb21"></a><strong id="b766915012487"><a name="b766915012487"></a><a name="b766915012487"></a>Parameter</strong></p>
</th>
<th class="cellrowborder" valign="top" width="14.000000000000002%" id="mcps1.1.5.1.2"><p id="abfc94cdc2c4244bc86852ae76ad7fbd8"><a name="abfc94cdc2c4244bc86852ae76ad7fbd8"></a><a name="abfc94cdc2c4244bc86852ae76ad7fbd8"></a><strong id="a94a207d6f3f44569aaf23f72a189a2e2"><a name="a94a207d6f3f44569aaf23f72a189a2e2"></a><a name="a94a207d6f3f44569aaf23f72a189a2e2"></a>Mandatory/Optional</strong></p>
</th>
<th class="cellrowborder" valign="top" width="25.900000000000002%" id="mcps1.1.5.1.3"><p id="a2ac6eae6099248d7ba77c5b614fc4648"><a name="a2ac6eae6099248d7ba77c5b614fc4648"></a><a name="a2ac6eae6099248d7ba77c5b614fc4648"></a><strong id="ae764f9526cb041048d8e3a0e4b2b29fc"><a name="ae764f9526cb041048d8e3a0e4b2b29fc"></a><a name="ae764f9526cb041048d8e3a0e4b2b29fc"></a>Type</strong></p>
</th>
<th class="cellrowborder" valign="top" width="37.3%" id="mcps1.1.5.1.4"><p id="ac7ed854ed13e489eb735a5efaa1cf3e8"><a name="ac7ed854ed13e489eb735a5efaa1cf3e8"></a><a name="ac7ed854ed13e489eb735a5efaa1cf3e8"></a><strong id="b13534543487"><a name="b13534543487"></a><a name="b13534543487"></a>Description</strong></p>
</th>
</tr>
</thead>
<tbody><tr id="r74a0cc02a4fe4a9598c38d3a82d320f9"><td class="cellrowborder" valign="top" width="22.8%" headers="mcps1.1.5.1.1 "><p id="a5d15896238da461cbdb0cb4c18727437"><a name="a5d15896238da461cbdb0cb4c18727437"></a><a name="a5d15896238da461cbdb0cb4c18727437"></a>origin</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="ad1d5bdaaaaa641db9a9cd2d197334bb9"><a name="ad1d5bdaaaaa641db9a9cd2d197334bb9"></a><a name="ad1d5bdaaaaa641db9a9cd2d197334bb9"></a>Mandatory</p>
</td>
<td class="cellrowborder" valign="top" width="25.900000000000002%" headers="mcps1.1.5.1.3 "><p id="a0182737dfe1a4bb2a4acfed499f252c9"><a name="a0182737dfe1a4bb2a4acfed499f252c9"></a><a name="a0182737dfe1a4bb2a4acfed499f252c9"></a><a href="js-params.md#s1f33822192a04bbe9bd9de86a17460b1">LatLng</a></p>
</td>
<td class="cellrowborder" valign="top" width="37.3%" headers="mcps1.1.5.1.4 "><p id="ac794405ab5cf4396a02b4d5bef15416f"><a name="ac794405ab5cf4396a02b4d5bef15416f"></a><a name="ac794405ab5cf4396a02b4d5bef15416f"></a>Longitude and latitude of the departure place.</p>
</td>
</tr>
<tr id="r70621240d4be45d893eb17e0366f66a8"><td class="cellrowborder" valign="top" width="22.8%" headers="mcps1.1.5.1.1 "><p id="ade307446ba7c44efa98bcc5e96649420"><a name="ade307446ba7c44efa98bcc5e96649420"></a><a name="ade307446ba7c44efa98bcc5e96649420"></a>destination</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="ac35b2892c1024300851d1dfa78affa53"><a name="ac35b2892c1024300851d1dfa78affa53"></a><a name="ac35b2892c1024300851d1dfa78affa53"></a>Mandatory</p>
</td>
<td class="cellrowborder" valign="top" width="25.900000000000002%" headers="mcps1.1.5.1.3 "><p id="aa3197c513d6d45f0ba8a1fd2221d2a29"><a name="aa3197c513d6d45f0ba8a1fd2221d2a29"></a><a name="aa3197c513d6d45f0ba8a1fd2221d2a29"></a><a href="js-params.md#s1f33822192a04bbe9bd9de86a17460b1">LatLng</a></p>
</td>
<td class="cellrowborder" valign="top" width="37.3%" headers="mcps1.1.5.1.4 "><p id="ab17dde822e994466a47edf455f824995"><a name="ab17dde822e994466a47edf455f824995"></a><a name="ab17dde822e994466a47edf455f824995"></a>Longitude and latitude of the destination.</p>
</td>
</tr>
</tbody>
</table>

## DirectionsResult<a name="s5136fc4b19984160b25e2cf8d90bf122"></a>

<a name="tb9342fc3daa4476aa3b20fc594f36ee3"></a>
<table><thead align="left"><tr id="r05ddd42314e34ff29027f603e309fddf"><th class="cellrowborder" valign="top" width="26.51%" id="mcps1.1.4.1.1"><p id="a518ced707bdc448aa94a117af0a0a506"><a name="a518ced707bdc448aa94a117af0a0a506"></a><a name="a518ced707bdc448aa94a117af0a0a506"></a><strong id="b1586565154913"><a name="b1586565154913"></a><a name="b1586565154913"></a>Parameter</strong></p>
</th>
<th class="cellrowborder" valign="top" width="30.12%" id="mcps1.1.4.1.2"><p id="aaa609eba060a44e0b89d7d09016704c0"><a name="aaa609eba060a44e0b89d7d09016704c0"></a><a name="aaa609eba060a44e0b89d7d09016704c0"></a><strong id="ac59f03f752cf4a3abe99655bc658f825"><a name="ac59f03f752cf4a3abe99655bc658f825"></a><a name="ac59f03f752cf4a3abe99655bc658f825"></a>Type</strong></p>
</th>
<th class="cellrowborder" valign="top" width="43.37%" id="mcps1.1.4.1.3"><p id="acdf9c3ba80be448a9d8b62925bd75abf"><a name="acdf9c3ba80be448a9d8b62925bd75abf"></a><a name="acdf9c3ba80be448a9d8b62925bd75abf"></a><strong id="b86549854910"><a name="b86549854910"></a><a name="b86549854910"></a>Description</strong></p>
</th>
</tr>
</thead>
<tbody><tr id="rd54315524a994da3a6301ff32de07e8b"><td class="cellrowborder" valign="top" width="26.51%" headers="mcps1.1.4.1.1 "><p id="a800000651a4d4c3a993bd57f276d9d39"><a name="a800000651a4d4c3a993bd57f276d9d39"></a><a name="a800000651a4d4c3a993bd57f276d9d39"></a>routes</p>
</td>
<td class="cellrowborder" valign="top" width="30.12%" headers="mcps1.1.4.1.2 "><p id="a308689c1d1fa4e5fa4c9e6c61e1732c6"><a name="a308689c1d1fa4e5fa4c9e6c61e1732c6"></a><a name="a308689c1d1fa4e5fa4c9e6c61e1732c6"></a>Array&lt;<a href="js-params.md#se7c75826f9604dc0b998c2b278e3647d">Route</a>&gt;</p>
</td>
<td class="cellrowborder" valign="top" width="43.37%" headers="mcps1.1.4.1.3 "><p id="a202c54248b704d438323a707b567ff94"><a name="a202c54248b704d438323a707b567ff94"></a><a name="a202c54248b704d438323a707b567ff94"></a>Planned routes from the departure place to the destination.</p>
</td>
</tr>
</tbody>
</table>

## DrivingDirectionsRequest<a name="scc98f453d97a4d16885cdf2f02a705fc"></a>

<a name="td44d755b29094369883df92ebfa8821e"></a>
<table><thead align="left"><tr id="r35237ad8b6214c909e75389d6b931c35"><th class="cellrowborder" valign="top" width="18.05%" id="mcps1.1.5.1.1"><p id="ae14b432d6b684ded9157bda5303f8c1a"><a name="ae14b432d6b684ded9157bda5303f8c1a"></a><a name="ae14b432d6b684ded9157bda5303f8c1a"></a><strong id="b177681725204919"><a name="b177681725204919"></a><a name="b177681725204919"></a>Parameter</strong></p>
</th>
<th class="cellrowborder" valign="top" width="14.000000000000002%" id="mcps1.1.5.1.2"><p id="a923358912ec242aa895af83a99f5e72e"><a name="a923358912ec242aa895af83a99f5e72e"></a><a name="a923358912ec242aa895af83a99f5e72e"></a><strong id="aa6b31e26088f49088b74ea360126098d"><a name="aa6b31e26088f49088b74ea360126098d"></a><a name="aa6b31e26088f49088b74ea360126098d"></a>Mandatory/Optional</strong></p>
</th>
<th class="cellrowborder" valign="top" width="22.3%" id="mcps1.1.5.1.3"><p id="a54a9044578c349bcba9f38df065639c9"><a name="a54a9044578c349bcba9f38df065639c9"></a><a name="a54a9044578c349bcba9f38df065639c9"></a><strong id="a5c6919b7e4c64faaa6bfe72fae3343e4"><a name="a5c6919b7e4c64faaa6bfe72fae3343e4"></a><a name="a5c6919b7e4c64faaa6bfe72fae3343e4"></a>Type</strong></p>
</th>
<th class="cellrowborder" valign="top" width="45.65%" id="mcps1.1.5.1.4"><p id="a75b0207d77924881b597b684db1a4da6"><a name="a75b0207d77924881b597b684db1a4da6"></a><a name="a75b0207d77924881b597b684db1a4da6"></a><strong id="b5127172954914"><a name="b5127172954914"></a><a name="b5127172954914"></a>Description</strong></p>
</th>
</tr>
</thead>
<tbody><tr id="rfac303b78c1941c78ddd64b0a0c0de0f"><td class="cellrowborder" valign="top" width="18.05%" headers="mcps1.1.5.1.1 "><p id="a683b15c04659413894dd35e4be150d2e"><a name="a683b15c04659413894dd35e4be150d2e"></a><a name="a683b15c04659413894dd35e4be150d2e"></a>origin</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="a83d545361bc0449fab7eb3c902075f66"><a name="a83d545361bc0449fab7eb3c902075f66"></a><a name="a83d545361bc0449fab7eb3c902075f66"></a>Mandatory</p>
</td>
<td class="cellrowborder" valign="top" width="22.3%" headers="mcps1.1.5.1.3 "><p id="a2427e59c9ca14dd7864e4b87820100ba"><a name="a2427e59c9ca14dd7864e4b87820100ba"></a><a name="a2427e59c9ca14dd7864e4b87820100ba"></a><a href="js-params.md#s1f33822192a04bbe9bd9de86a17460b1">LatLng</a></p>
</td>
<td class="cellrowborder" valign="top" width="45.65%" headers="mcps1.1.5.1.4 "><p id="a4b522768c22a43a18bb1a4d75965d731"><a name="a4b522768c22a43a18bb1a4d75965d731"></a><a name="a4b522768c22a43a18bb1a4d75965d731"></a>Longitude and latitude of the departure place.</p>
</td>
</tr>
<tr id="ra210646d7c944718ad4d1b837e1be091"><td class="cellrowborder" valign="top" width="18.05%" headers="mcps1.1.5.1.1 "><p id="a840ebaecd38648589946f15e4d42ab34"><a name="a840ebaecd38648589946f15e4d42ab34"></a><a name="a840ebaecd38648589946f15e4d42ab34"></a>destination</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="a79b945bc571f4f6d99fd1d1c9b36c2c4"><a name="a79b945bc571f4f6d99fd1d1c9b36c2c4"></a><a name="a79b945bc571f4f6d99fd1d1c9b36c2c4"></a>Mandatory</p>
</td>
<td class="cellrowborder" valign="top" width="22.3%" headers="mcps1.1.5.1.3 "><p id="a4afed108a38749b6b351eb33182242c7"><a name="a4afed108a38749b6b351eb33182242c7"></a><a name="a4afed108a38749b6b351eb33182242c7"></a><a href="js-params.md#s1f33822192a04bbe9bd9de86a17460b1">LatLng</a></p>
</td>
<td class="cellrowborder" valign="top" width="45.65%" headers="mcps1.1.5.1.4 "><p id="ad58c78fc5777454d819cd26fdd2d221a"><a name="ad58c78fc5777454d819cd26fdd2d221a"></a><a name="ad58c78fc5777454d819cd26fdd2d221a"></a>Longitude and latitude of the destination.</p>
</td>
</tr>
<tr id="rd93bca1cc48b4af5a8c5eef4010ebeb9"><td class="cellrowborder" valign="top" width="18.05%" headers="mcps1.1.5.1.1 "><p id="ae1ce6df50d72415e8f1f3a67b8594a08"><a name="ae1ce6df50d72415e8f1f3a67b8594a08"></a><a name="ae1ce6df50d72415e8f1f3a67b8594a08"></a>waypoints</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="ab21336b30afc469ca634b4d3ec783952"><a name="ab21336b30afc469ca634b4d3ec783952"></a><a name="ab21336b30afc469ca634b4d3ec783952"></a>Optional</p>
</td>
<td class="cellrowborder" valign="top" width="22.3%" headers="mcps1.1.5.1.3 "><p id="a9191761c73c34c98858f0ff6b318728a"><a name="a9191761c73c34c98858f0ff6b318728a"></a><a name="a9191761c73c34c98858f0ff6b318728a"></a>Array&lt;<a href="js-params.md#s1f33822192a04bbe9bd9de86a17460b1">LatLng</a>&gt;</p>
</td>
<td class="cellrowborder" valign="top" width="45.65%" headers="mcps1.1.5.1.4 "><p id="abcbb1bf6015f445ab46d82b243220d47"><a name="abcbb1bf6015f445ab46d82b243220d47"></a><a name="abcbb1bf6015f445ab46d82b243220d47"></a>Waypoints. You can specify up to 5 waypoints.</p>
</td>
</tr>
<tr id="rcd9a58db4c8346e598af7d3ecd326ea1"><td class="cellrowborder" valign="top" width="18.05%" headers="mcps1.1.5.1.1 "><p id="ae6d2b2e4dd52495a8bdee3b413cafceb"><a name="ae6d2b2e4dd52495a8bdee3b413cafceb"></a><a name="ae6d2b2e4dd52495a8bdee3b413cafceb"></a>viaType</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="a85f3e1dbbda24708ad1063b6020279a3"><a name="a85f3e1dbbda24708ad1063b6020279a3"></a><a name="a85f3e1dbbda24708ad1063b6020279a3"></a>Optional</p>
</td>
<td class="cellrowborder" valign="top" width="22.3%" headers="mcps1.1.5.1.3 "><p id="a74775931526c4d8f8bdcffe23e3fd599"><a name="a74775931526c4d8f8bdcffe23e3fd599"></a><a name="a74775931526c4d8f8bdcffe23e3fd599"></a>Boolean</p>
</td>
<td class="cellrowborder" valign="top" width="45.65%" headers="mcps1.1.5.1.4 "><p id="a3755426b2db94261b0711e61a475b9d5"><a name="a3755426b2db94261b0711e61a475b9d5"></a><a name="a3755426b2db94261b0711e61a475b9d5"></a>Waypoint type. The options are as follows:</p>
<a name="u1dce5f689bb542ad8553a61fa0dde6bb"></a><a name="u1dce5f689bb542ad8553a61fa0dde6bb"></a><ul id="u1dce5f689bb542ad8553a61fa0dde6bb"><li><strong id="b125821253194910"><a name="b125821253194910"></a><a name="b125821253194910"></a>false</strong> (default): stopover</li><li><strong id="b9654105564915"><a name="b9654105564915"></a><a name="b9654105564915"></a>true</strong>: via (pass-by)</li></ul>
</td>
</tr>
<tr id="rbb4ef7878cee408b9c52b8a4ae4bfa5d"><td class="cellrowborder" valign="top" width="18.05%" headers="mcps1.1.5.1.1 "><p id="ad88a4059d6664085995e1924a860060f"><a name="ad88a4059d6664085995e1924a860060f"></a><a name="ad88a4059d6664085995e1924a860060f"></a>optimize</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="aea55731e8191428192efc6d90f6869cb"><a name="aea55731e8191428192efc6d90f6869cb"></a><a name="aea55731e8191428192efc6d90f6869cb"></a>Optional</p>
</td>
<td class="cellrowborder" valign="top" width="22.3%" headers="mcps1.1.5.1.3 "><p id="aa9d94536ae0f4ef284d56d24e08d48a4"><a name="aa9d94536ae0f4ef284d56d24e08d48a4"></a><a name="aa9d94536ae0f4ef284d56d24e08d48a4"></a>Boolean</p>
</td>
<td class="cellrowborder" valign="top" width="45.65%" headers="mcps1.1.5.1.4 "><p id="aae04058e30354555962cc9d68d149976"><a name="aae04058e30354555962cc9d68d149976"></a><a name="aae04058e30354555962cc9d68d149976"></a>Indicates whether to optimize the waypoint. The options are as follows:</p>
<a name="uc269e41cd8354f4bb353b39dbcd396bb"></a><a name="uc269e41cd8354f4bb353b39dbcd396bb"></a><ul id="uc269e41cd8354f4bb353b39dbcd396bb"><li><strong id="b1689813265015"><a name="b1689813265015"></a><a name="b1689813265015"></a>false</strong> (default): no</li><li><strong id="b18131564508"><a name="b18131564508"></a><a name="b18131564508"></a>true</strong>: yes</li></ul>
</td>
</tr>
<tr id="rdaa3913f289c4dbc9631b4edfa96ed25"><td class="cellrowborder" valign="top" width="18.05%" headers="mcps1.1.5.1.1 "><p id="a45a5a0087e824b249e98ae2e4324ce35"><a name="a45a5a0087e824b249e98ae2e4324ce35"></a><a name="a45a5a0087e824b249e98ae2e4324ce35"></a>alternatives</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="a10df136101834345a537912f94298527"><a name="a10df136101834345a537912f94298527"></a><a name="a10df136101834345a537912f94298527"></a>Optional</p>
</td>
<td class="cellrowborder" valign="top" width="22.3%" headers="mcps1.1.5.1.3 "><p id="a3b69fa5fb1e84ba5a7f1f6d545ac0153"><a name="a3b69fa5fb1e84ba5a7f1f6d545ac0153"></a><a name="a3b69fa5fb1e84ba5a7f1f6d545ac0153"></a>Boolean</p>
</td>
<td class="cellrowborder" valign="top" width="45.65%" headers="mcps1.1.5.1.4 "><p id="ae545a3829da34975901876f386c99889"><a name="ae545a3829da34975901876f386c99889"></a><a name="ae545a3829da34975901876f386c99889"></a>Indicates whether to return multiple planned routes. </p>
<p id="a9ae414a15c7448709fe84e82f9b79343"><a name="a9ae414a15c7448709fe84e82f9b79343"></a><a name="a9ae414a15c7448709fe84e82f9b79343"></a>The options are as follows:</p>
<a name="u67dea903bf084336aec59d671e75d8ae"></a><a name="u67dea903bf084336aec59d671e75d8ae"></a><ul id="u67dea903bf084336aec59d671e75d8ae"><li><strong id="b167881550185020"><a name="b167881550185020"></a><a name="b167881550185020"></a>true</strong>: yes</li><li><strong id="b19737142915011"><a name="b19737142915011"></a><a name="b19737142915011"></a>false</strong> (default): no</li></ul>
<div class="caution" id="note1656219401543"><a name="note1656219401543"></a><a name="note1656219401543"></a><span class="cautiontitle"> CAUTION: </span><div class="cautionbody"><p id="p12562194005416"><a name="p12562194005416"></a><a name="p12562194005416"></a>This parameter is unavailable when waypoints are set.</p>
</div></div>
</td>
</tr>
<tr id="rc3250cf2a7194e21b932cac0ec04979b"><td class="cellrowborder" valign="top" width="18.05%" headers="mcps1.1.5.1.1 "><p id="af998bf880e874a52b9b5a0b10d5e8c37"><a name="af998bf880e874a52b9b5a0b10d5e8c37"></a><a name="af998bf880e874a52b9b5a0b10d5e8c37"></a>avoid</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="a927405f023ea44f385e3b6661839f802"><a name="a927405f023ea44f385e3b6661839f802"></a><a name="a927405f023ea44f385e3b6661839f802"></a>Optional</p>
</td>
<td class="cellrowborder" valign="top" width="22.3%" headers="mcps1.1.5.1.3 "><p id="a9c8ea7d7758246b0a78057b89d930f1f"><a name="a9c8ea7d7758246b0a78057b89d930f1f"></a><a name="a9c8ea7d7758246b0a78057b89d930f1f"></a>Array&lt;Number&gt;</p>
</td>
<td class="cellrowborder" valign="top" width="45.65%" headers="mcps1.1.5.1.4 "><p id="ac97396db2fe2472d80577df670a4728d"><a name="ac97396db2fe2472d80577df670a4728d"></a><a name="ac97396db2fe2472d80577df670a4728d"></a>Indicates the specified type of roads to be avoided. The options are as follows:</p>
<a name="ubeec8a1ba7bc4af58a1061473e9b2679"></a><a name="ubeec8a1ba7bc4af58a1061473e9b2679"></a><ul id="ubeec8a1ba7bc4af58a1061473e9b2679"><li><strong id="b1135512175511"><a name="b1135512175511"></a><a name="b1135512175511"></a>1</strong>: Avoid toll roads.</li><li><strong id="b13205171925116"><a name="b13205171925116"></a><a name="b13205171925116"></a>2</strong>: Avoid expressways.</li></ul>
<p id="a65f3a13370f24885a4afbcc9f7983573"><a name="a65f3a13370f24885a4afbcc9f7983573"></a><a name="a65f3a13370f24885a4afbcc9f7983573"></a>If this parameter is not included in the request, the route taking the least time will be returned by default.</p>
</td>
</tr>
<tr id="r3f8838cd5d454f628d930ffe5ddee5e7"><td class="cellrowborder" valign="top" width="18.05%" headers="mcps1.1.5.1.1 "><p id="a18a059b2ba8d4f248c2445702526d963"><a name="a18a059b2ba8d4f248c2445702526d963"></a><a name="a18a059b2ba8d4f248c2445702526d963"></a>departAt</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="a7b34e092dd6043608fd2c316d559f8bb"><a name="a7b34e092dd6043608fd2c316d559f8bb"></a><a name="a7b34e092dd6043608fd2c316d559f8bb"></a>Optional</p>
</td>
<td class="cellrowborder" valign="top" width="22.3%" headers="mcps1.1.5.1.3 "><p id="a1bba9f80a0fa4e82bebb90113bf17dac"><a name="a1bba9f80a0fa4e82bebb90113bf17dac"></a><a name="a1bba9f80a0fa4e82bebb90113bf17dac"></a>Number</p>
</td>
<td class="cellrowborder" valign="top" width="45.65%" headers="mcps1.1.5.1.4 "><p id="a312e796efb104bb397faba8b37eca4de"><a name="a312e796efb104bb397faba8b37eca4de"></a><a name="a312e796efb104bb397faba8b37eca4de"></a>Estimated departure time, in seconds since 00:00 on January 1, 1970 (UTC).</p>
<p id="aa075848c90f94e1dad702c9d12d3dbf5"><a name="aa075848c90f94e1dad702c9d12d3dbf5"></a><a name="aa075848c90f94e1dad702c9d12d3dbf5"></a>The value must be the current time or a future time.</p>
</td>
</tr>
<tr id="r2a7fe5b35b3f4ffd9335ee78108a4430"><td class="cellrowborder" valign="top" width="18.05%" headers="mcps1.1.5.1.1 "><p id="a8c8d4c750ab244a3a735b1a1e5313cfb"><a name="a8c8d4c750ab244a3a735b1a1e5313cfb"></a><a name="a8c8d4c750ab244a3a735b1a1e5313cfb"></a>trafficMode</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="ad3989bcf2993402e94bb59f41fc4c910"><a name="ad3989bcf2993402e94bb59f41fc4c910"></a><a name="ad3989bcf2993402e94bb59f41fc4c910"></a>Optional</p>
</td>
<td class="cellrowborder" valign="top" width="22.3%" headers="mcps1.1.5.1.3 "><p id="a7aa0a1e1ccce45fca68269c8a65b9ac6"><a name="a7aa0a1e1ccce45fca68269c8a65b9ac6"></a><a name="a7aa0a1e1ccce45fca68269c8a65b9ac6"></a>Number</p>
</td>
<td class="cellrowborder" valign="top" width="45.65%" headers="mcps1.1.5.1.4 "><p id="a076280039182484d81a8fb63925dd4db"><a name="a076280039182484d81a8fb63925dd4db"></a><a name="a076280039182484d81a8fb63925dd4db"></a>Time estimation mode. The options are as follows:</p>
<a name="u1fe9caac8e0f484aab000fb1bf91c7c8"></a><a name="u1fe9caac8e0f484aab000fb1bf91c7c8"></a><ul id="u1fe9caac8e0f484aab000fb1bf91c7c8"><li><strong id="b3834104219552"><a name="b3834104219552"></a><a name="b3834104219552"></a>0</strong> (default): best guess</li><li><strong id="b1993864316551"><a name="b1993864316551"></a><a name="b1993864316551"></a>1</strong>: The traffic condition is worse than the historical average.</li><li><strong id="b14906164555510"><a name="b14906164555510"></a><a name="b14906164555510"></a>2</strong>: The traffic condition is better than the historical average.</li></ul>
</td>
</tr>
</tbody>
</table>

