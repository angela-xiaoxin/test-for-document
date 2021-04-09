# HWDirectionsService<a name="ZH-CN_TOPIC_0000001145941053"></a>

-   [概览](#scb7bb019553e4de58a54a07667892299)
-   [构造方法](#s943511137def418895576b646155729f)
-   [公共方法](#sb704fcc4000f444d89c3f53fd1e4813f)
-   [DirectionsRequest](#s3deb591b65dc43e4b4c40f10afa4a71d)
-   [DirectionsResult](#s70691a88ea7b4be2aec22deb6a3f18e8)
-   [DrivingDirectionsRequest](#sa55b3a04190c47e7b236494902a06d4b)

## 概览<a name="scb7bb019553e4de58a54a07667892299"></a>

该类提供路径规划服务，支持步行路径规划、骑行路径规划和驾车路径规划。

## 构造方法<a name="s943511137def418895576b646155729f"></a>

<a name="tecf548e3bc414c75abe7b3de508ff529"></a>
<table><thead align="left"><tr id="re7e012cb030c4a2696c9442361ccbfa6"><th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.1"><p id="a160c8ab883bd4e809ef7e79c1d9e9fa6"><a name="a160c8ab883bd4e809ef7e79c1d9e9fa6"></a><a name="a160c8ab883bd4e809ef7e79c1d9e9fa6"></a><strong id="a21fec2d2e25e40319fc778b3b6b8f1a7"><a name="a21fec2d2e25e40319fc778b3b6b8f1a7"></a><a name="a21fec2d2e25e40319fc778b3b6b8f1a7"></a>构造方法</strong></p>
</th>
<th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.2"><p id="a98c043b91770434abd8bf34b4f57b6d5"><a name="a98c043b91770434abd8bf34b4f57b6d5"></a><a name="a98c043b91770434abd8bf34b4f57b6d5"></a><strong id="af958fa1052da445a835aa9c68044e9be"><a name="af958fa1052da445a835aa9c68044e9be"></a><a name="af958fa1052da445a835aa9c68044e9be"></a>描述</strong></p>
</th>
</tr>
</thead>
<tbody><tr id="reeca93482b414a08870474ec6dd2a604"><td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.1 "><p id="a9d37182d572040b9a59c4f3242e3fdd2"><a name="a9d37182d572040b9a59c4f3242e3fdd2"></a><a name="a9d37182d572040b9a59c4f3242e3fdd2"></a>HWMapJsSDK.HWDirectionsService()</p>
</td>
<td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.2 "><p id="ae78e24209ce14f2687a6b097527556be"><a name="ae78e24209ce14f2687a6b097527556be"></a><a name="ae78e24209ce14f2687a6b097527556be"></a>-</p>
</td>
</tr>
</tbody>
</table>

## 公共方法<a name="sb704fcc4000f444d89c3f53fd1e4813f"></a>

<a name="tdaa9599253254ce7abfa087fcadf387d"></a>
<table><thead align="left"><tr id="rd5ab5ff38de0435da51d451b4994da1d"><th class="cellrowborder" valign="top" width="28.000000000000004%" id="mcps1.1.5.1.1"><p id="a265806dae4b84a45a0f06f41642cceca"><a name="a265806dae4b84a45a0f06f41642cceca"></a><a name="a265806dae4b84a45a0f06f41642cceca"></a><strong id="a9d60ba8826d34daf9f6932d5220d925f"><a name="a9d60ba8826d34daf9f6932d5220d925f"></a><a name="a9d60ba8826d34daf9f6932d5220d925f"></a>方法</strong></p>
</th>
<th class="cellrowborder" valign="top" width="18%" id="mcps1.1.5.1.2"><p id="a47a9d0752ac4470697932140d73c73aa"><a name="a47a9d0752ac4470697932140d73c73aa"></a><a name="a47a9d0752ac4470697932140d73c73aa"></a><strong id="aae7060e8fe294cfeac6b48c43f6eb7a7"><a name="aae7060e8fe294cfeac6b48c43f6eb7a7"></a><a name="aae7060e8fe294cfeac6b48c43f6eb7a7"></a>描述</strong></p>
</th>
<th class="cellrowborder" valign="top" width="41%" id="mcps1.1.5.1.3"><p id="ae8def4881c094944845bfe91ca7fc8f3"><a name="ae8def4881c094944845bfe91ca7fc8f3"></a><a name="ae8def4881c094944845bfe91ca7fc8f3"></a><strong id="a33dfeb9da74f42439acf66dd712516eb"><a name="a33dfeb9da74f42439acf66dd712516eb"></a><a name="a33dfeb9da74f42439acf66dd712516eb"></a>参数类型</strong></p>
</th>
<th class="cellrowborder" valign="top" width="13%" id="mcps1.1.5.1.4"><p id="ad763c53f63594eb4ae27a927fa977304"><a name="ad763c53f63594eb4ae27a927fa977304"></a><a name="ad763c53f63594eb4ae27a927fa977304"></a><strong id="a01b8040412574c139a4d30aaf22d9a36"><a name="a01b8040412574c139a4d30aaf22d9a36"></a><a name="a01b8040412574c139a4d30aaf22d9a36"></a>返回值</strong></p>
</th>
</tr>
</thead>
<tbody><tr id="r98c3021052404af88fd980f1c3098a83"><td class="cellrowborder" valign="top" width="28.000000000000004%" headers="mcps1.1.5.1.1 "><p id="a7e09a80f0f504dffaacbc6943b643d75"><a name="a7e09a80f0f504dffaacbc6943b643d75"></a><a name="a7e09a80f0f504dffaacbc6943b643d75"></a>routeWalking(request, callback)</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.2 "><p id="ac34c47747b1a49709e488b12a3146f6c"><a name="ac34c47747b1a49709e488b12a3146f6c"></a><a name="ac34c47747b1a49709e488b12a3146f6c"></a>步行路径规划。</p>
</td>
<td class="cellrowborder" valign="top" width="41%" headers="mcps1.1.5.1.3 "><a name="uc38d2dd4791148328915475e0aa12598"></a><a name="uc38d2dd4791148328915475e0aa12598"></a><ul id="uc38d2dd4791148328915475e0aa12598"><li>request: <a href="#s3deb591b65dc43e4b4c40f10afa4a71d">DirectionsRequest</a>，路线规划的请求体。</li><li>callback： Function(<a href="#s70691a88ea7b4be2aec22deb6a3f18e8">DirectionsResult</a>, StatusCode)，路径规划的回调函数。</li></ul>
</td>
<td class="cellrowborder" valign="top" width="13%" headers="mcps1.1.5.1.4 "><p id="a5d33f5c4e6dc4cbea4e28cdaff663e3a"><a name="a5d33f5c4e6dc4cbea4e28cdaff663e3a"></a><a name="a5d33f5c4e6dc4cbea4e28cdaff663e3a"></a>-</p>
</td>
</tr>
<tr id="r3c48611395514c69b48da237a0e73fb0"><td class="cellrowborder" valign="top" width="28.000000000000004%" headers="mcps1.1.5.1.1 "><p id="a8a53a1fde8944206b641921ff351bff2"><a name="a8a53a1fde8944206b641921ff351bff2"></a><a name="a8a53a1fde8944206b641921ff351bff2"></a>routeBicycling(request, callback)</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.2 "><p id="ae52838b9c6e74c68a0babf8549c6da3f"><a name="ae52838b9c6e74c68a0babf8549c6da3f"></a><a name="ae52838b9c6e74c68a0babf8549c6da3f"></a>骑行路径规划。</p>
</td>
<td class="cellrowborder" valign="top" width="41%" headers="mcps1.1.5.1.3 "><a name="u6344bbabee6a48849b7f7a17999015b5"></a><a name="u6344bbabee6a48849b7f7a17999015b5"></a><ul id="u6344bbabee6a48849b7f7a17999015b5"><li>request：<a href="#s3deb591b65dc43e4b4c40f10afa4a71d">DirectionsRequest</a>，路线规划的请求体。</li><li>callback： Function(<a href="#s70691a88ea7b4be2aec22deb6a3f18e8">DirectionsResult</a>, StatusCode)，路径规划的回调函数。</li></ul>
</td>
<td class="cellrowborder" valign="top" width="13%" headers="mcps1.1.5.1.4 "><p id="abb314a38ed5f4e00b66bdfee3326dfc3"><a name="abb314a38ed5f4e00b66bdfee3326dfc3"></a><a name="abb314a38ed5f4e00b66bdfee3326dfc3"></a>-</p>
</td>
</tr>
<tr id="r0945856b60b5453982d10c15f1484049"><td class="cellrowborder" valign="top" width="28.000000000000004%" headers="mcps1.1.5.1.1 "><p id="a382b7e9355a048888063066bdb5f3400"><a name="a382b7e9355a048888063066bdb5f3400"></a><a name="a382b7e9355a048888063066bdb5f3400"></a>routeDriving(request, callback)</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.2 "><p id="a62345dad7b2349d59f8b169e5a4652d2"><a name="a62345dad7b2349d59f8b169e5a4652d2"></a><a name="a62345dad7b2349d59f8b169e5a4652d2"></a>驾车路径规划。</p>
</td>
<td class="cellrowborder" valign="top" width="41%" headers="mcps1.1.5.1.3 "><a name="u5f07eacb40c14b7581ef4492526a42ef"></a><a name="u5f07eacb40c14b7581ef4492526a42ef"></a><ul id="u5f07eacb40c14b7581ef4492526a42ef"><li>request：<a href="#sa55b3a04190c47e7b236494902a06d4b">DrivingDirectionsRequest</a>，驾车路径规划的请求体。</li><li>callback： Function(<a href="#s70691a88ea7b4be2aec22deb6a3f18e8">DirectionsResult</a>, StatusCode)，驾车路径规划的回调函数。</li></ul>
</td>
<td class="cellrowborder" valign="top" width="13%" headers="mcps1.1.5.1.4 "><p id="af2e20282193f4cb99d8f7dea4149854f"><a name="af2e20282193f4cb99d8f7dea4149854f"></a><a name="af2e20282193f4cb99d8f7dea4149854f"></a>-</p>
</td>
</tr>
</tbody>
</table>

>![](public_sys-resources/icon-note.gif) **说明：** 
>StatusCode是接口调用状态的返回码，具体请参见[错误码](error-code.md)。

## DirectionsRequest<a name="s3deb591b65dc43e4b4c40f10afa4a71d"></a>

<a name="ta054afa991384be297ce40ceae786c50"></a>
<table><thead align="left"><tr id="r3e3808026909442f85d27d9b8675dc37"><th class="cellrowborder" valign="top" width="22.8%" id="mcps1.1.5.1.1"><p id="a8372c72a85284997b36a48ea2fdfa63a"><a name="a8372c72a85284997b36a48ea2fdfa63a"></a><a name="a8372c72a85284997b36a48ea2fdfa63a"></a><strong id="a0023226066194cba87bc469cbb0ba9e7"><a name="a0023226066194cba87bc469cbb0ba9e7"></a><a name="a0023226066194cba87bc469cbb0ba9e7"></a>名称</strong></p>
</th>
<th class="cellrowborder" valign="top" width="14.000000000000002%" id="mcps1.1.5.1.2"><p id="a455bd40a2e3745eab474fb824217ad60"><a name="a455bd40a2e3745eab474fb824217ad60"></a><a name="a455bd40a2e3745eab474fb824217ad60"></a><strong id="a2bddffc71ee541509c4e33e6a5181dc7"><a name="a2bddffc71ee541509c4e33e6a5181dc7"></a><a name="a2bddffc71ee541509c4e33e6a5181dc7"></a>是否必选</strong></p>
</th>
<th class="cellrowborder" valign="top" width="25.900000000000002%" id="mcps1.1.5.1.3"><p id="aeccdd653b0c146e68a1d07e30a177d6c"><a name="aeccdd653b0c146e68a1d07e30a177d6c"></a><a name="aeccdd653b0c146e68a1d07e30a177d6c"></a><strong id="ab1669b3eaa544af7ba524c6ca25d7ec6"><a name="ab1669b3eaa544af7ba524c6ca25d7ec6"></a><a name="ab1669b3eaa544af7ba524c6ca25d7ec6"></a>类型</strong></p>
</th>
<th class="cellrowborder" valign="top" width="37.3%" id="mcps1.1.5.1.4"><p id="a144d4e65b38a418989e73e9173fee0a3"><a name="a144d4e65b38a418989e73e9173fee0a3"></a><a name="a144d4e65b38a418989e73e9173fee0a3"></a><strong id="a34637f70904c463e8e33a3081841c513"><a name="a34637f70904c463e8e33a3081841c513"></a><a name="a34637f70904c463e8e33a3081841c513"></a>描述</strong></p>
</th>
</tr>
</thead>
<tbody><tr id="r443ccabfc03c460a9371c5026e3ff646"><td class="cellrowborder" valign="top" width="22.8%" headers="mcps1.1.5.1.1 "><p id="a48314294f5114bb981b491a93d2f0ea5"><a name="a48314294f5114bb981b491a93d2f0ea5"></a><a name="a48314294f5114bb981b491a93d2f0ea5"></a>origin</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="aeb2f99ca9bf24c14afd7409574e912e3"><a name="aeb2f99ca9bf24c14afd7409574e912e3"></a><a name="aeb2f99ca9bf24c14afd7409574e912e3"></a>是</p>
</td>
<td class="cellrowborder" valign="top" width="25.900000000000002%" headers="mcps1.1.5.1.3 "><p id="a913483427ffa45a881b9efe78a5f8539"><a name="a913483427ffa45a881b9efe78a5f8539"></a><a name="a913483427ffa45a881b9efe78a5f8539"></a><a href="js-params.md#s45373a8938e040ca9f46c78f4283b385">LatLng</a></p>
</td>
<td class="cellrowborder" valign="top" width="37.3%" headers="mcps1.1.5.1.4 "><p id="aa1151d3d92dd4b2dab3c0bca554d7ebc"><a name="aa1151d3d92dd4b2dab3c0bca554d7ebc"></a><a name="aa1151d3d92dd4b2dab3c0bca554d7ebc"></a>起点的经纬度。</p>
</td>
</tr>
<tr id="rea0e5dc1abec4370bd73c68273b98439"><td class="cellrowborder" valign="top" width="22.8%" headers="mcps1.1.5.1.1 "><p id="adce074c7aab94914852bb6f1364f9fc8"><a name="adce074c7aab94914852bb6f1364f9fc8"></a><a name="adce074c7aab94914852bb6f1364f9fc8"></a>destination</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="a2315543ba3974f69b7f68fb81f6ebe47"><a name="a2315543ba3974f69b7f68fb81f6ebe47"></a><a name="a2315543ba3974f69b7f68fb81f6ebe47"></a>是</p>
</td>
<td class="cellrowborder" valign="top" width="25.900000000000002%" headers="mcps1.1.5.1.3 "><p id="a22c1ad76ac104685a25b548af458ec4f"><a name="a22c1ad76ac104685a25b548af458ec4f"></a><a name="a22c1ad76ac104685a25b548af458ec4f"></a><a href="js-params.md#s45373a8938e040ca9f46c78f4283b385">LatLng</a></p>
</td>
<td class="cellrowborder" valign="top" width="37.3%" headers="mcps1.1.5.1.4 "><p id="adfe46ff9730d4ebd887188f6c3634390"><a name="adfe46ff9730d4ebd887188f6c3634390"></a><a name="adfe46ff9730d4ebd887188f6c3634390"></a>终点的经纬度。</p>
</td>
</tr>
</tbody>
</table>

## DirectionsResult<a name="s70691a88ea7b4be2aec22deb6a3f18e8"></a>

<a name="td7a77014da6c4c35899958fa3a537c37"></a>
<table><thead align="left"><tr id="rd84d308a95f54b5caaf48acfabc6deab"><th class="cellrowborder" valign="top" width="26.51%" id="mcps1.1.4.1.1"><p id="a88c59bab815245aab2546175b30b4000"><a name="a88c59bab815245aab2546175b30b4000"></a><a name="a88c59bab815245aab2546175b30b4000"></a><strong id="a29e68a583377467ca52b1c7b0936236c"><a name="a29e68a583377467ca52b1c7b0936236c"></a><a name="a29e68a583377467ca52b1c7b0936236c"></a>名称</strong></p>
</th>
<th class="cellrowborder" valign="top" width="30.12%" id="mcps1.1.4.1.2"><p id="a5984941fb76b4cc2a4dd34fde6bedda6"><a name="a5984941fb76b4cc2a4dd34fde6bedda6"></a><a name="a5984941fb76b4cc2a4dd34fde6bedda6"></a><strong id="a1407ed5639c34daeabf48f1caf78427b"><a name="a1407ed5639c34daeabf48f1caf78427b"></a><a name="a1407ed5639c34daeabf48f1caf78427b"></a>类型</strong></p>
</th>
<th class="cellrowborder" valign="top" width="43.37%" id="mcps1.1.4.1.3"><p id="a3d97840b19b94a5cb08a7e30fefa648d"><a name="a3d97840b19b94a5cb08a7e30fefa648d"></a><a name="a3d97840b19b94a5cb08a7e30fefa648d"></a><strong id="ad0f726e30839477ab7eafe49875ba23b"><a name="ad0f726e30839477ab7eafe49875ba23b"></a><a name="ad0f726e30839477ab7eafe49875ba23b"></a>描述</strong></p>
</th>
</tr>
</thead>
<tbody><tr id="rf11cd887cb394dbe8bb7f5b51cccc332"><td class="cellrowborder" valign="top" width="26.51%" headers="mcps1.1.4.1.1 "><p id="a6ac78864d9f7407cb4409824931c4982"><a name="a6ac78864d9f7407cb4409824931c4982"></a><a name="a6ac78864d9f7407cb4409824931c4982"></a>routes</p>
</td>
<td class="cellrowborder" valign="top" width="30.12%" headers="mcps1.1.4.1.2 "><p id="a5a3db39b6f214451a94c779b314bd0bc"><a name="a5a3db39b6f214451a94c779b314bd0bc"></a><a name="a5a3db39b6f214451a94c779b314bd0bc"></a>Array&lt;<a href="js-params.md#scff6465e40704ddf9d95d3572e9e61bc">Route</a>&gt;</p>
</td>
<td class="cellrowborder" valign="top" width="43.37%" headers="mcps1.1.4.1.3 "><p id="a4dde09a5cc9e499faea9c519736982de"><a name="a4dde09a5cc9e499faea9c519736982de"></a><a name="a4dde09a5cc9e499faea9c519736982de"></a>从起点到目的地的规划路径。</p>
</td>
</tr>
</tbody>
</table>

## DrivingDirectionsRequest<a name="sa55b3a04190c47e7b236494902a06d4b"></a>

<a name="t739b75d041364b75843d3333f23a30b0"></a>
<table><thead align="left"><tr id="r0d499a0c808349e69ad2e0d69dce6a51"><th class="cellrowborder" valign="top" width="18.05%" id="mcps1.1.5.1.1"><p id="a07ced4e2c6d840ba848aa8d60f7b9376"><a name="a07ced4e2c6d840ba848aa8d60f7b9376"></a><a name="a07ced4e2c6d840ba848aa8d60f7b9376"></a><strong id="a927cf5847d7e47709f5b3df91236fe8f"><a name="a927cf5847d7e47709f5b3df91236fe8f"></a><a name="a927cf5847d7e47709f5b3df91236fe8f"></a>名称</strong></p>
</th>
<th class="cellrowborder" valign="top" width="14.000000000000002%" id="mcps1.1.5.1.2"><p id="ac3142c3086e040c2883a874554a907b0"><a name="ac3142c3086e040c2883a874554a907b0"></a><a name="ac3142c3086e040c2883a874554a907b0"></a><strong id="afb9e1463b5bc452a8bafb3b35ee2aa5c"><a name="afb9e1463b5bc452a8bafb3b35ee2aa5c"></a><a name="afb9e1463b5bc452a8bafb3b35ee2aa5c"></a>是否必选</strong></p>
</th>
<th class="cellrowborder" valign="top" width="22.3%" id="mcps1.1.5.1.3"><p id="aeca1cd13861d4032bfef6033daa64657"><a name="aeca1cd13861d4032bfef6033daa64657"></a><a name="aeca1cd13861d4032bfef6033daa64657"></a><strong id="a2ae6a665a94b42e3acc55a807d757440"><a name="a2ae6a665a94b42e3acc55a807d757440"></a><a name="a2ae6a665a94b42e3acc55a807d757440"></a>类型</strong></p>
</th>
<th class="cellrowborder" valign="top" width="45.65%" id="mcps1.1.5.1.4"><p id="acb613b1f4d6d4ac4b94d6acb7c459a14"><a name="acb613b1f4d6d4ac4b94d6acb7c459a14"></a><a name="acb613b1f4d6d4ac4b94d6acb7c459a14"></a><strong id="ab83cf3d57d7b40d8b6af2699d1d0d8d3"><a name="ab83cf3d57d7b40d8b6af2699d1d0d8d3"></a><a name="ab83cf3d57d7b40d8b6af2699d1d0d8d3"></a>描述</strong></p>
</th>
</tr>
</thead>
<tbody><tr id="rc5324ad13ada401d92c225dac174aea9"><td class="cellrowborder" valign="top" width="18.05%" headers="mcps1.1.5.1.1 "><p id="aec218958aeae43ef8e4bf7e3ad78f3d4"><a name="aec218958aeae43ef8e4bf7e3ad78f3d4"></a><a name="aec218958aeae43ef8e4bf7e3ad78f3d4"></a>origin</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="a83b166275ab441e78a0b8529eb03dce3"><a name="a83b166275ab441e78a0b8529eb03dce3"></a><a name="a83b166275ab441e78a0b8529eb03dce3"></a>是</p>
</td>
<td class="cellrowborder" valign="top" width="22.3%" headers="mcps1.1.5.1.3 "><p id="a723c4a0795124209ace4435b5218feba"><a name="a723c4a0795124209ace4435b5218feba"></a><a name="a723c4a0795124209ace4435b5218feba"></a><a href="js-params.md#s45373a8938e040ca9f46c78f4283b385">LatLng</a></p>
</td>
<td class="cellrowborder" valign="top" width="45.65%" headers="mcps1.1.5.1.4 "><p id="a3ac46e56b887409cbb8600650c86b7bd"><a name="a3ac46e56b887409cbb8600650c86b7bd"></a><a name="a3ac46e56b887409cbb8600650c86b7bd"></a>起点的经纬度。</p>
</td>
</tr>
<tr id="r82ec83b8da604541923977df6c39c679"><td class="cellrowborder" valign="top" width="18.05%" headers="mcps1.1.5.1.1 "><p id="aec44af2fc32d488c9629db9168a28cba"><a name="aec44af2fc32d488c9629db9168a28cba"></a><a name="aec44af2fc32d488c9629db9168a28cba"></a>destination</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="a1a00b50602a945f7892e4e8d39ae003f"><a name="a1a00b50602a945f7892e4e8d39ae003f"></a><a name="a1a00b50602a945f7892e4e8d39ae003f"></a>是</p>
</td>
<td class="cellrowborder" valign="top" width="22.3%" headers="mcps1.1.5.1.3 "><p id="a28752558c86c4fa4beaefb90887c7264"><a name="a28752558c86c4fa4beaefb90887c7264"></a><a name="a28752558c86c4fa4beaefb90887c7264"></a><a href="js-params.md#s45373a8938e040ca9f46c78f4283b385">LatLng</a></p>
</td>
<td class="cellrowborder" valign="top" width="45.65%" headers="mcps1.1.5.1.4 "><p id="a8e15485259dd45a78e59f675f3caf4d4"><a name="a8e15485259dd45a78e59f675f3caf4d4"></a><a name="a8e15485259dd45a78e59f675f3caf4d4"></a>终点的经纬度。</p>
</td>
</tr>
<tr id="r5b7f472da03b425788fed3de89520223"><td class="cellrowborder" valign="top" width="18.05%" headers="mcps1.1.5.1.1 "><p id="aca44850560954c8490f3b3d125495450"><a name="aca44850560954c8490f3b3d125495450"></a><a name="aca44850560954c8490f3b3d125495450"></a>waypoints</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="a677a9fbf136e4ff98353801f67f10b3a"><a name="a677a9fbf136e4ff98353801f67f10b3a"></a><a name="a677a9fbf136e4ff98353801f67f10b3a"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="22.3%" headers="mcps1.1.5.1.3 "><p id="a26b3403b515b49f68e7869b01f5057ba"><a name="a26b3403b515b49f68e7869b01f5057ba"></a><a name="a26b3403b515b49f68e7869b01f5057ba"></a>Array&lt;<a href="js-params.md#s45373a8938e040ca9f46c78f4283b385">LatLng</a>&gt;</p>
</td>
<td class="cellrowborder" valign="top" width="45.65%" headers="mcps1.1.5.1.4 "><p id="a049e660af40445b0ad92ca9ff15b962a"><a name="a049e660af40445b0ad92ca9ff15b962a"></a><a name="a049e660af40445b0ad92ca9ff15b962a"></a>途经点。最多可以输入5个途经点。</p>
</td>
</tr>
<tr id="r79042f518f134f6cbc439a407554be2f"><td class="cellrowborder" valign="top" width="18.05%" headers="mcps1.1.5.1.1 "><p id="a76b729dbeb3e42d9a6b3151774a8112a"><a name="a76b729dbeb3e42d9a6b3151774a8112a"></a><a name="a76b729dbeb3e42d9a6b3151774a8112a"></a>viaType</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="abe282aa8b0b04673b656fc6f98c17256"><a name="abe282aa8b0b04673b656fc6f98c17256"></a><a name="abe282aa8b0b04673b656fc6f98c17256"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="22.3%" headers="mcps1.1.5.1.3 "><p id="a26c089ca64f64a3e8b0436f998206d0b"><a name="a26c089ca64f64a3e8b0436f998206d0b"></a><a name="a26c089ca64f64a3e8b0436f998206d0b"></a>Boolean</p>
</td>
<td class="cellrowborder" valign="top" width="45.65%" headers="mcps1.1.5.1.4 "><p id="af4d7bcedc14e49adab476cd3a0e24676"><a name="af4d7bcedc14e49adab476cd3a0e24676"></a><a name="af4d7bcedc14e49adab476cd3a0e24676"></a>途径点类型，是via类型还是stopover类型。</p>
<a name="u8616997e100b48d29e5eeff3eae85ed1"></a><a name="u8616997e100b48d29e5eeff3eae85ed1"></a><ul id="u8616997e100b48d29e5eeff3eae85ed1"><li>false：stopover类型（默认）</li><li>true：via类型</li></ul>
</td>
</tr>
<tr id="re34959b1c74a4e02a237aea968a01343"><td class="cellrowborder" valign="top" width="18.05%" headers="mcps1.1.5.1.1 "><p id="a0fc922e5cbee4374933fae9d0664d1bc"><a name="a0fc922e5cbee4374933fae9d0664d1bc"></a><a name="a0fc922e5cbee4374933fae9d0664d1bc"></a>optimize</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="a7da0d2f454f947d3be9d40b481d7b40f"><a name="a7da0d2f454f947d3be9d40b481d7b40f"></a><a name="a7da0d2f454f947d3be9d40b481d7b40f"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="22.3%" headers="mcps1.1.5.1.3 "><p id="a58759d285fe34c60b4fd4c42ca1b391c"><a name="a58759d285fe34c60b4fd4c42ca1b391c"></a><a name="a58759d285fe34c60b4fd4c42ca1b391c"></a>Boolean</p>
</td>
<td class="cellrowborder" valign="top" width="45.65%" headers="mcps1.1.5.1.4 "><p id="a679b22cbeeab4a3ba7bdd645d74041a8"><a name="a679b22cbeeab4a3ba7bdd645d74041a8"></a><a name="a679b22cbeeab4a3ba7bdd645d74041a8"></a>是否对途径点进行优化。</p>
<a name="u18c5526e1bdb4b7f81de43192263ad37"></a><a name="u18c5526e1bdb4b7f81de43192263ad37"></a><ul id="u18c5526e1bdb4b7f81de43192263ad37"><li>false：不进行途径点优化（默认）</li><li>true：进行途径点优化</li></ul>
</td>
</tr>
<tr id="ra47ef3f6ebc846019fb04082bd8c7dfd"><td class="cellrowborder" valign="top" width="18.05%" headers="mcps1.1.5.1.1 "><p id="a73c8e2e930d74058be33bcf87302e901"><a name="a73c8e2e930d74058be33bcf87302e901"></a><a name="a73c8e2e930d74058be33bcf87302e901"></a>alternatives</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="adc5ee01939b049a98d90c71b56c54c1d"><a name="adc5ee01939b049a98d90c71b56c54c1d"></a><a name="adc5ee01939b049a98d90c71b56c54c1d"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="22.3%" headers="mcps1.1.5.1.3 "><p id="a8003176f8c0c4195a2e3a54115fc5a31"><a name="a8003176f8c0c4195a2e3a54115fc5a31"></a><a name="a8003176f8c0c4195a2e3a54115fc5a31"></a>Boolean</p>
</td>
<td class="cellrowborder" valign="top" width="45.65%" headers="mcps1.1.5.1.4 "><p id="a15d5064c8c7346b38787c85303bf6e48"><a name="a15d5064c8c7346b38787c85303bf6e48"></a><a name="a15d5064c8c7346b38787c85303bf6e48"></a>如果设置为true，可以返回多条规划路线结果。</p>
<p id="a72dd12b4368648ffa8a29f6978cd0b23"><a name="a72dd12b4368648ffa8a29f6978cd0b23"></a><a name="a72dd12b4368648ffa8a29f6978cd0b23"></a>取值包括：</p>
<a name="u11a744c6f9f74f5dabcd70da93650370"></a><a name="u11a744c6f9f74f5dabcd70da93650370"></a><ul id="u11a744c6f9f74f5dabcd70da93650370"><li>true</li><li>false（默认）</li></ul>
<div class="note" id="note0698503125"><a name="note0698503125"></a><a name="note0698503125"></a><span class="notetitle"> 说明： </span><div class="notebody"><p id="p126911501122"><a name="p126911501122"></a><a name="p126911501122"></a>如果设置了途经点时，不能使用多路线功能。</p>
</div></div>
</td>
</tr>
<tr id="rd60e91c91f9e459480f51ada6580c431"><td class="cellrowborder" valign="top" width="18.05%" headers="mcps1.1.5.1.1 "><p id="a9ec33c02950e4dd88b36f686b49ad458"><a name="a9ec33c02950e4dd88b36f686b49ad458"></a><a name="a9ec33c02950e4dd88b36f686b49ad458"></a>avoid</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="af0214bdac4744a198db588e54aeac570"><a name="af0214bdac4744a198db588e54aeac570"></a><a name="af0214bdac4744a198db588e54aeac570"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="22.3%" headers="mcps1.1.5.1.3 "><p id="a52b0c4f328c04adc8d6aa387bf55e05a"><a name="a52b0c4f328c04adc8d6aa387bf55e05a"></a><a name="a52b0c4f328c04adc8d6aa387bf55e05a"></a>Array&lt;Number&gt;</p>
</td>
<td class="cellrowborder" valign="top" width="45.65%" headers="mcps1.1.5.1.4 "><p id="a7ff40ea5b9b94afea776b876c9c12932"><a name="a7ff40ea5b9b94afea776b876c9c12932"></a><a name="a7ff40ea5b9b94afea776b876c9c12932"></a>表示计算出的路径应避免所指示的特性，取值包括：</p>
<a name="ue9eadc15f9d440469332344d5aabe912"></a><a name="ue9eadc15f9d440469332344d5aabe912"></a><ul id="ue9eadc15f9d440469332344d5aabe912"><li>1：避免经过收费的公路</li><li>2：避开高速公路</li></ul>
<p id="aad7bea8cdf3d4313a1127331268394bb"><a name="aad7bea8cdf3d4313a1127331268394bb"></a><a name="aad7bea8cdf3d4313a1127331268394bb"></a>默认按时间最短返回。</p>
</td>
</tr>
<tr id="rbe5b9afa0ea44ac6893a624dda847738"><td class="cellrowborder" valign="top" width="18.05%" headers="mcps1.1.5.1.1 "><p id="acff5682170d24c29bd76db11986f312f"><a name="acff5682170d24c29bd76db11986f312f"></a><a name="acff5682170d24c29bd76db11986f312f"></a>departAt</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="a1ff48b2453df47d98bfbee8808dd07fd"><a name="a1ff48b2453df47d98bfbee8808dd07fd"></a><a name="a1ff48b2453df47d98bfbee8808dd07fd"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="22.3%" headers="mcps1.1.5.1.3 "><p id="aab135bb0d6714c1d8a54c9108c795a49"><a name="aab135bb0d6714c1d8a54c9108c795a49"></a><a name="aab135bb0d6714c1d8a54c9108c795a49"></a>Number</p>
</td>
<td class="cellrowborder" valign="top" width="45.65%" headers="mcps1.1.5.1.4 "><p id="a1f8a9b4c560a4fd2b9cf6257a0368dc4"><a name="a1f8a9b4c560a4fd2b9cf6257a0368dc4"></a><a name="a1f8a9b4c560a4fd2b9cf6257a0368dc4"></a>预计出发时间。以自UTC 1970年1月1日午夜以来的秒数为单位。</p>
<p id="a8d7419c810e64ea5a1bb171a4c527a16"><a name="a8d7419c810e64ea5a1bb171a4c527a16"></a><a name="a8d7419c810e64ea5a1bb171a4c527a16"></a>必须是当前或者未来时间，不能是过去时间。</p>
</td>
</tr>
<tr id="r9e98a91dda1d4f64984f684e05a30746"><td class="cellrowborder" valign="top" width="18.05%" headers="mcps1.1.5.1.1 "><p id="a7ac8a49433c34a61a2de7681127122e4"><a name="a7ac8a49433c34a61a2de7681127122e4"></a><a name="a7ac8a49433c34a61a2de7681127122e4"></a>trafficMode</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="aa07bb3473d9b49f88a10a7390444be4c"><a name="aa07bb3473d9b49f88a10a7390444be4c"></a><a name="aa07bb3473d9b49f88a10a7390444be4c"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="22.3%" headers="mcps1.1.5.1.3 "><p id="a4b8fe7cde2b548b29fa4042caed387e1"><a name="a4b8fe7cde2b548b29fa4042caed387e1"></a><a name="a4b8fe7cde2b548b29fa4042caed387e1"></a>Number</p>
</td>
<td class="cellrowborder" valign="top" width="45.65%" headers="mcps1.1.5.1.4 "><p id="a98483799de4a45ecbc463c382088b828"><a name="a98483799de4a45ecbc463c382088b828"></a><a name="a98483799de4a45ecbc463c382088b828"></a>时间预估模型。取值包括：</p>
<a name="u2d088249955843f998921ac7f2464b62"></a><a name="u2d088249955843f998921ac7f2464b62"></a><ul id="u2d088249955843f998921ac7f2464b62"><li>0：best guess（默认）</li><li>1：路况差于历史平均水平</li><li>2：路况优于历史平均水平</li></ul>
</td>
</tr>
</tbody>
</table>

