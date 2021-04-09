# HWSiteService<a name="ZH-CN_TOPIC_0000001099181268"></a>

-   [概览](#sb838c309604d41dba207b02801a18334)
-   [构造方法](#s04722c9a59494656b3795e39f8c7e718)
-   [公共方法](#s73c542d0bd7b4ddbac83ed2f9119e07b)
-   [GeocodeRequest](#sd5e3ac239f6a48689261e9d5f38b8641)
-   [GeocodeResult](#s7adee8d76acb4b2e80bad2c9b78c99a1)
-   [NearbySearchRequest](#se147bc59b0194eda80de17c0bdaee77c)
-   [NearbySearchResult](#s76ba1898bfc5490ca57e0d3c50fee30d)
-   [QuerySuggestionRequest](#sd7916193426041b1b9579296b161bba6)
-   [QuerySuggestionResult](#s2dc38e671e904caab9d133069638a4f1)
-   [ReverseGeocodeRequest](#s871ce65677cc4e1dbfd1636c3b325d6f)
-   [ReverseGeocodeResult](#s682816b9645c4c928831c554b541e014)
-   [SearchByIdRequest](#s07869d36847f4dcd8b38d5428c2cafd4)
-   [SearchByIdResult](#sc03caf032be04183a23bfa399b25594c)
-   [SearchByTextRequest](#s0636d688325540bab4ba4311b4092d9d)
-   [SearchByTextResult](#s61d75014a6c144bbbe67f6e830579f67)

## 概览<a name="sb838c309604d41dba207b02801a18334"></a>

该类提供位置搜索和地理编码接口。

## 构造方法<a name="s04722c9a59494656b3795e39f8c7e718"></a>

<a name="t099dd3d69df94d5ebe7cb919907797a8"></a>
<table><thead align="left"><tr id="r8326de059b6e4ea49cf00d2583254da0"><th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.1"><p id="a1d4c0f538c20441ba022aaec721e1279"><a name="a1d4c0f538c20441ba022aaec721e1279"></a><a name="a1d4c0f538c20441ba022aaec721e1279"></a><strong id="a8c1fd581fa704537a9e01cb9e3828bd0"><a name="a8c1fd581fa704537a9e01cb9e3828bd0"></a><a name="a8c1fd581fa704537a9e01cb9e3828bd0"></a>构造方法</strong></p>
</th>
<th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.2"><p id="ab4f5d2ac95b84430902820acbf2f2d5f"><a name="ab4f5d2ac95b84430902820acbf2f2d5f"></a><a name="ab4f5d2ac95b84430902820acbf2f2d5f"></a><strong id="ab68c66c70ca54e3d91e5f1d1df8a1d73"><a name="ab68c66c70ca54e3d91e5f1d1df8a1d73"></a><a name="ab68c66c70ca54e3d91e5f1d1df8a1d73"></a>描述</strong></p>
</th>
</tr>
</thead>
<tbody><tr id="rdcf805d647e94e28b51bc0d103048c81"><td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.1 "><p id="a3e8375021a7e410396ca6248f0908ff3"><a name="a3e8375021a7e410396ca6248f0908ff3"></a><a name="a3e8375021a7e410396ca6248f0908ff3"></a>HWMapJsSDK.HWSiteService()</p>
</td>
<td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.2 "><p id="a8c539bc2365f42f692bf2c64706c2053"><a name="a8c539bc2365f42f692bf2c64706c2053"></a><a name="a8c539bc2365f42f692bf2c64706c2053"></a>-</p>
</td>
</tr>
</tbody>
</table>

## 公共方法<a name="s73c542d0bd7b4ddbac83ed2f9119e07b"></a>

<a name="t784b8a38bd72493bbda89318bde7139a"></a>
<table><thead align="left"><tr id="rfab01a9699314e979c0d2f677afc67bb"><th class="cellrowborder" valign="top" width="27%" id="mcps1.1.5.1.1"><p id="a4d15e727bb74423f9c6fa86b87d48be7"><a name="a4d15e727bb74423f9c6fa86b87d48be7"></a><a name="a4d15e727bb74423f9c6fa86b87d48be7"></a><strong id="aefcedc5296c34995940af50aaed9558a"><a name="aefcedc5296c34995940af50aaed9558a"></a><a name="aefcedc5296c34995940af50aaed9558a"></a>方法</strong></p>
</th>
<th class="cellrowborder" valign="top" width="14.67%" id="mcps1.1.5.1.2"><p id="a3920a3b0e99b4153b79bb0c475c8063d"><a name="a3920a3b0e99b4153b79bb0c475c8063d"></a><a name="a3920a3b0e99b4153b79bb0c475c8063d"></a><strong id="a750a5afbb6f04de0b0294a4ebf372e42"><a name="a750a5afbb6f04de0b0294a4ebf372e42"></a><a name="a750a5afbb6f04de0b0294a4ebf372e42"></a>描述</strong></p>
</th>
<th class="cellrowborder" valign="top" width="41.23%" id="mcps1.1.5.1.3"><p id="aad28acb1aac54df5be1f86ce8d14f93c"><a name="aad28acb1aac54df5be1f86ce8d14f93c"></a><a name="aad28acb1aac54df5be1f86ce8d14f93c"></a><strong id="a7a3575cc92364184a3c863a37c6e5c5f"><a name="a7a3575cc92364184a3c863a37c6e5c5f"></a><a name="a7a3575cc92364184a3c863a37c6e5c5f"></a>参数类型</strong></p>
</th>
<th class="cellrowborder" valign="top" width="17.1%" id="mcps1.1.5.1.4"><p id="a4ce36db10a4a4fecbdb8445d87d96c2d"><a name="a4ce36db10a4a4fecbdb8445d87d96c2d"></a><a name="a4ce36db10a4a4fecbdb8445d87d96c2d"></a><strong id="a146ec7e7f1534c7398a549b0d6bd5673"><a name="a146ec7e7f1534c7398a549b0d6bd5673"></a><a name="a146ec7e7f1534c7398a549b0d6bd5673"></a>返回值</strong></p>
</th>
</tr>
</thead>
<tbody><tr id="r69bafb66608747aa8c34d7e0984ce7dc"><td class="cellrowborder" valign="top" width="27%" headers="mcps1.1.5.1.1 "><p id="acffa9793b01641d0b9ad0d9fa5828021"><a name="acffa9793b01641d0b9ad0d9fa5828021"></a><a name="acffa9793b01641d0b9ad0d9fa5828021"></a>geocode(request, callback)</p>
</td>
<td class="cellrowborder" valign="top" width="14.67%" headers="mcps1.1.5.1.2 "><p id="a1427382e7cb3467983696dc0ca9ac89b"><a name="a1427382e7cb3467983696dc0ca9ac89b"></a><a name="a1427382e7cb3467983696dc0ca9ac89b"></a>正地理编码。</p>
</td>
<td class="cellrowborder" valign="top" width="41.23%" headers="mcps1.1.5.1.3 "><a name="uadaf3e4ef8f749f38b4d6535a30bce22"></a><a name="uadaf3e4ef8f749f38b4d6535a30bce22"></a><ul id="uadaf3e4ef8f749f38b4d6535a30bce22"><li>request：<a href="#sd5e3ac239f6a48689261e9d5f38b8641">GeocodeRequest</a>，正地理编码的请求体。</li><li>callback：Function(<a href="#s7adee8d76acb4b2e80bad2c9b78c99a1">GeocodeResult</a>, StatusCode)，正地理编码的回调函数。</li></ul>
</td>
<td class="cellrowborder" valign="top" width="17.1%" headers="mcps1.1.5.1.4 "><p id="a9113e1bcaa6b4560a920862e6e8cbecd"><a name="a9113e1bcaa6b4560a920862e6e8cbecd"></a><a name="a9113e1bcaa6b4560a920862e6e8cbecd"></a>-</p>
</td>
</tr>
<tr id="r4b390988cb4847f48ec6539a9bd10150"><td class="cellrowborder" valign="top" width="27%" headers="mcps1.1.5.1.1 "><p id="ac6dd83848fd74832a61829adaf98886b"><a name="ac6dd83848fd74832a61829adaf98886b"></a><a name="ac6dd83848fd74832a61829adaf98886b"></a>nearbySearch(request, callback)</p>
</td>
<td class="cellrowborder" valign="top" width="14.67%" headers="mcps1.1.5.1.2 "><p id="aa431081168f04a21820c12619321d403"><a name="aa431081168f04a21820c12619321d403"></a><a name="aa431081168f04a21820c12619321d403"></a>周边搜索。</p>
</td>
<td class="cellrowborder" valign="top" width="41.23%" headers="mcps1.1.5.1.3 "><a name="ubc520cd716fa4d8c889bf044e083cc33"></a><a name="ubc520cd716fa4d8c889bf044e083cc33"></a><ul id="ubc520cd716fa4d8c889bf044e083cc33"><li>request：<a href="#se147bc59b0194eda80de17c0bdaee77c">NearbySearchRequest</a>，周边搜索的请求体。</li><li>callback： Function(<a href="#s76ba1898bfc5490ca57e0d3c50fee30d">NearbySearchResult</a>, StatusCode)，周边搜索的回调函数。</li></ul>
</td>
<td class="cellrowborder" valign="top" width="17.1%" headers="mcps1.1.5.1.4 "><p id="ae4af997f34bd4f70936edc6d5b7cc0cd"><a name="ae4af997f34bd4f70936edc6d5b7cc0cd"></a><a name="ae4af997f34bd4f70936edc6d5b7cc0cd"></a>-</p>
</td>
</tr>
<tr id="rd9cbcd1da99048369434738a82cc3508"><td class="cellrowborder" valign="top" width="27%" headers="mcps1.1.5.1.1 "><p id="a6767ee01d61b4856850558269334a5d5"><a name="a6767ee01d61b4856850558269334a5d5"></a><a name="a6767ee01d61b4856850558269334a5d5"></a>querySuggestion(request, callback)</p>
</td>
<td class="cellrowborder" valign="top" width="14.67%" headers="mcps1.1.5.1.2 "><p id="aff6da8e84f3e4ad4a71124cf491fd3ef"><a name="aff6da8e84f3e4ad4a71124cf491fd3ef"></a><a name="aff6da8e84f3e4ad4a71124cf491fd3ef"></a>地点搜索建议。</p>
</td>
<td class="cellrowborder" valign="top" width="41.23%" headers="mcps1.1.5.1.3 "><a name="u62ee0583bf1d45689ca8f8865361cba5"></a><a name="u62ee0583bf1d45689ca8f8865361cba5"></a><ul id="u62ee0583bf1d45689ca8f8865361cba5"><li>request：<a href="#sd7916193426041b1b9579296b161bba6">QuerySuggestionRequest</a>，地点搜索建议的请求体。</li><li>callback：Function(<a href="#s2dc38e671e904caab9d133069638a4f1">QuerySuggestionResult</a>, StatusCode)，地点搜索建议的回调函数。</li></ul>
</td>
<td class="cellrowborder" valign="top" width="17.1%" headers="mcps1.1.5.1.4 "><p id="aec0eea3c63244df28f13f32b17d6acbe"><a name="aec0eea3c63244df28f13f32b17d6acbe"></a><a name="aec0eea3c63244df28f13f32b17d6acbe"></a>-</p>
</td>
</tr>
<tr id="redea6df7ea9f46ebbfb8e7658bee78fe"><td class="cellrowborder" valign="top" width="27%" headers="mcps1.1.5.1.1 "><p id="a011e47ace326468894e6dbc3e2ae726c"><a name="a011e47ace326468894e6dbc3e2ae726c"></a><a name="a011e47ace326468894e6dbc3e2ae726c"></a>reverseGeocode(request, callback)</p>
</td>
<td class="cellrowborder" valign="top" width="14.67%" headers="mcps1.1.5.1.2 "><p id="a8766f12469454e939c76d35b1e290dca"><a name="a8766f12469454e939c76d35b1e290dca"></a><a name="a8766f12469454e939c76d35b1e290dca"></a>逆地理编码。</p>
</td>
<td class="cellrowborder" valign="top" width="41.23%" headers="mcps1.1.5.1.3 "><a name="ub74b2df46d114002bb81d4295684d004"></a><a name="ub74b2df46d114002bb81d4295684d004"></a><ul id="ub74b2df46d114002bb81d4295684d004"><li>request： <a href="#s871ce65677cc4e1dbfd1636c3b325d6f">ReverseGeocodeRequest</a>，逆地理编码的请求体。</li><li>callback： Function( <a href="#s682816b9645c4c928831c554b541e014">ReverseGeocodeResult</a>, StatusCode)，逆地理编码的回调函数。</li></ul>
</td>
<td class="cellrowborder" valign="top" width="17.1%" headers="mcps1.1.5.1.4 "><p id="a3369da94a57e42cd8d06cab09e40cdd4"><a name="a3369da94a57e42cd8d06cab09e40cdd4"></a><a name="a3369da94a57e42cd8d06cab09e40cdd4"></a>-</p>
</td>
</tr>
<tr id="rb69c2259547d4817aa2a74b5705895d8"><td class="cellrowborder" valign="top" width="27%" headers="mcps1.1.5.1.1 "><p id="adc269c779f76439ea1e2e57128e6ad14"><a name="adc269c779f76439ea1e2e57128e6ad14"></a><a name="adc269c779f76439ea1e2e57128e6ad14"></a>searchById(request, callback)</p>
</td>
<td class="cellrowborder" valign="top" width="14.67%" headers="mcps1.1.5.1.2 "><p id="a4c404a7387e4492186eb1de92f498326"><a name="a4c404a7387e4492186eb1de92f498326"></a><a name="a4c404a7387e4492186eb1de92f498326"></a>地点详情。</p>
</td>
<td class="cellrowborder" valign="top" width="41.23%" headers="mcps1.1.5.1.3 "><a name="uf56223636aaf4b7fbd4b6a22d4d49160"></a><a name="uf56223636aaf4b7fbd4b6a22d4d49160"></a><ul id="uf56223636aaf4b7fbd4b6a22d4d49160"><li>request：<a href="#s07869d36847f4dcd8b38d5428c2cafd4">SearchByIdRequest</a>，地点详情的请求体。</li><li>callback： Function(<a href="#sc03caf032be04183a23bfa399b25594c">SearchByIdResult</a>, StatusCode)，地点详情的回调函数。</li></ul>
</td>
<td class="cellrowborder" valign="top" width="17.1%" headers="mcps1.1.5.1.4 "><p id="aba60ac6eb3054e6a8773de992a4c5736"><a name="aba60ac6eb3054e6a8773de992a4c5736"></a><a name="aba60ac6eb3054e6a8773de992a4c5736"></a>-</p>
</td>
</tr>
<tr id="reffdba42d3f642abafc6304b3154b295"><td class="cellrowborder" valign="top" width="27%" headers="mcps1.1.5.1.1 "><p id="a8e570e99f4a040b4bb7d5cb92c98e92b"><a name="a8e570e99f4a040b4bb7d5cb92c98e92b"></a><a name="a8e570e99f4a040b4bb7d5cb92c98e92b"></a>searchByText(request, callback)</p>
</td>
<td class="cellrowborder" valign="top" width="14.67%" headers="mcps1.1.5.1.2 "><p id="aedd66920bdba4022a9b8155c6657e37d"><a name="aedd66920bdba4022a9b8155c6657e37d"></a><a name="aedd66920bdba4022a9b8155c6657e37d"></a>关键字搜索。</p>
</td>
<td class="cellrowborder" valign="top" width="41.23%" headers="mcps1.1.5.1.3 "><a name="ub9b465d18f5c4ad58b083355f09b5954"></a><a name="ub9b465d18f5c4ad58b083355f09b5954"></a><ul id="ub9b465d18f5c4ad58b083355f09b5954"><li>request： <a href="#s0636d688325540bab4ba4311b4092d9d">SearchByTextRequest</a>，关键字搜索的请求体。</li><li>callback： Function(<a href="#s61d75014a6c144bbbe67f6e830579f67">SearchByTextResult</a>, StatusCode)，关键字搜索的回调函数。</li></ul>
</td>
<td class="cellrowborder" valign="top" width="17.1%" headers="mcps1.1.5.1.4 "><p id="a7184535638ee4eb88ad157015b6f1a3c"><a name="a7184535638ee4eb88ad157015b6f1a3c"></a><a name="a7184535638ee4eb88ad157015b6f1a3c"></a>-</p>
</td>
</tr>
</tbody>
</table>

>![](public_sys-resources/icon-note.gif) **说明：** 
>StatusCode是接口调用状态的返回码，具体请参见[错误码](error-code.md)。

## GeocodeRequest<a name="sd5e3ac239f6a48689261e9d5f38b8641"></a>

<a name="tde5e3ef190194cfdb797eda632d1de64"></a>
<table><thead align="left"><tr id="re6926db226af4ba299d755d4ab8563ae"><th class="cellrowborder" valign="top" width="16.97%" id="mcps1.1.5.1.1"><p id="a1b0b9b44adab467d91c2d03a5e304cf5"><a name="a1b0b9b44adab467d91c2d03a5e304cf5"></a><a name="a1b0b9b44adab467d91c2d03a5e304cf5"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="14.000000000000002%" id="mcps1.1.5.1.2"><p id="a7f4a4bfa3628473082f66fa7dc806a1b"><a name="a7f4a4bfa3628473082f66fa7dc806a1b"></a><a name="a7f4a4bfa3628473082f66fa7dc806a1b"></a>是否必选</p>
</th>
<th class="cellrowborder" valign="top" width="16%" id="mcps1.1.5.1.3"><p id="a3f8dd1024ccc4cf8a8d96af963502fcb"><a name="a3f8dd1024ccc4cf8a8d96af963502fcb"></a><a name="a3f8dd1024ccc4cf8a8d96af963502fcb"></a>参数类型</p>
</th>
<th class="cellrowborder" valign="top" width="53.03%" id="mcps1.1.5.1.4"><p id="a53826b2c75c24a1284f8ad83120e718b"><a name="a53826b2c75c24a1284f8ad83120e718b"></a><a name="a53826b2c75c24a1284f8ad83120e718b"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="r62ff6480e5f54a1ea857962f63533399"><td class="cellrowborder" valign="top" width="16.97%" headers="mcps1.1.5.1.1 "><p id="a39a7f8051d764974bdbf271ea8fc1fc3"><a name="a39a7f8051d764974bdbf271ea8fc1fc3"></a><a name="a39a7f8051d764974bdbf271ea8fc1fc3"></a>address</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="a095d74fde05e439faca634896359686f"><a name="a095d74fde05e439faca634896359686f"></a><a name="a095d74fde05e439faca634896359686f"></a>是</p>
</td>
<td class="cellrowborder" valign="top" width="16%" headers="mcps1.1.5.1.3 "><p id="a35aae855db6e4d08be0c2cb79cad7171"><a name="a35aae855db6e4d08be0c2cb79cad7171"></a><a name="a35aae855db6e4d08be0c2cb79cad7171"></a>String(&lt;=512)</p>
</td>
<td class="cellrowborder" valign="top" width="53.03%" headers="mcps1.1.5.1.4 "><p id="a836e12f15f2242a3b22bbde3e46b899f"><a name="a836e12f15f2242a3b22bbde3e46b899f"></a><a name="a836e12f15f2242a3b22bbde3e46b899f"></a>地点信息。</p>
</td>
</tr>
<tr id="r873cdaa7e9ac4bebb01f5ffd90df575e"><td class="cellrowborder" valign="top" width="16.97%" headers="mcps1.1.5.1.1 "><p id="aee393c9db4c242c980c605d58e8ec78f"><a name="aee393c9db4c242c980c605d58e8ec78f"></a><a name="aee393c9db4c242c980c605d58e8ec78f"></a>bounds</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="ab9941457aaf84dc0922983680a1c61b9"><a name="ab9941457aaf84dc0922983680a1c61b9"></a><a name="ab9941457aaf84dc0922983680a1c61b9"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="16%" headers="mcps1.1.5.1.3 "><p id="abb0fc49a309f4ef1969b8757bc017dcf"><a name="abb0fc49a309f4ef1969b8757bc017dcf"></a><a name="abb0fc49a309f4ef1969b8757bc017dcf"></a><a href="js-params.md#s7da68d05f25f42949a5700ac4cf28a27">LatLngBounds</a></p>
</td>
<td class="cellrowborder" valign="top" width="53.03%" headers="mcps1.1.5.1.4 "><p id="a55d257c50d104cf5af14022cfe211ad0"><a name="a55d257c50d104cf5af14022cfe211ad0"></a><a name="a55d257c50d104cf5af14022cfe211ad0"></a>查询结果偏向的搜索范围。</p>
</td>
</tr>
<tr id="r0666c2c74edb478bb1b9c235359c20aa"><td class="cellrowborder" valign="top" width="16.97%" headers="mcps1.1.5.1.1 "><p id="a7d4301692ab44992821dae1817282b8b"><a name="a7d4301692ab44992821dae1817282b8b"></a><a name="a7d4301692ab44992821dae1817282b8b"></a>language</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="a4242853d99a34a79b8b587395ce96235"><a name="a4242853d99a34a79b8b587395ce96235"></a><a name="a4242853d99a34a79b8b587395ce96235"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="16%" headers="mcps1.1.5.1.3 "><p id="abf332fa4eaeb4171b672d194ccf6bbbb"><a name="abf332fa4eaeb4171b672d194ccf6bbbb"></a><a name="abf332fa4eaeb4171b672d194ccf6bbbb"></a>String(&lt;=6)</p>
</td>
<td class="cellrowborder" valign="top" width="53.03%" headers="mcps1.1.5.1.4 "><p id="p6702102920561"><a name="p6702102920561"></a><a name="p6702102920561"></a>搜索结果的语种，语种取值请参见<a href="zh-cn_topic_0000001050162856.md">支持的语言</a>列表。如果不指定语种，返回地点的当地语言。</p>
</td>
</tr>
<tr id="r0fb056020b9343a1a85f34960646300d"><td class="cellrowborder" valign="top" width="16.97%" headers="mcps1.1.5.1.1 "><p id="a85e6f1425a7a40c8a5e38056b466965f"><a name="a85e6f1425a7a40c8a5e38056b466965f"></a><a name="a85e6f1425a7a40c8a5e38056b466965f"></a>politicalView</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="a848a441dc7314d5b85bd21f41cb45af0"><a name="a848a441dc7314d5b85bd21f41cb45af0"></a><a name="a848a441dc7314d5b85bd21f41cb45af0"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="16%" headers="mcps1.1.5.1.3 "><p id="a0954174a2c934b6a8f4d8c0b3f93f2a6"><a name="a0954174a2c934b6a8f4d8c0b3f93f2a6"></a><a name="a0954174a2c934b6a8f4d8c0b3f93f2a6"></a>String(=2)</p>
</td>
<td class="cellrowborder" valign="top" width="53.03%" headers="mcps1.1.5.1.4 "><p id="a80e98d0f8c9e4a318002b64b22d5b201"><a name="a80e98d0f8c9e4a318002b64b22d5b201"></a><a name="a80e98d0f8c9e4a318002b64b22d5b201"></a>政治观点参数，采用ISO 3166-1 alpha-2规范的2位国家码。</p>
<div class="caution" id="note1528292117492"><a name="note1528292117492"></a><a name="note1528292117492"></a><span class="cautiontitle"> 注意： </span><div class="cautionbody"><p id="p52829212494"><a name="p52829212494"></a><a name="p52829212494"></a>该参数已废弃。</p>
</div></div>
</td>
</tr>
</tbody>
</table>

## GeocodeResult<a name="s7adee8d76acb4b2e80bad2c9b78c99a1"></a>

<a name="t269a4738ed114599b37c740d8cf761ab"></a>
<table><thead align="left"><tr id="raf706496fb7a4d6b9641d9c8c2206c81"><th class="cellrowborder" valign="top" width="20%" id="mcps1.1.4.1.1"><p id="ae1801681d6e24dc5b113c3fb49ba5a0b"><a name="ae1801681d6e24dc5b113c3fb49ba5a0b"></a><a name="ae1801681d6e24dc5b113c3fb49ba5a0b"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="20%" id="mcps1.1.4.1.2"><p id="a629d722301dc4b58809792172586f949"><a name="a629d722301dc4b58809792172586f949"></a><a name="a629d722301dc4b58809792172586f949"></a>参数类型</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.1.4.1.3"><p id="af2c1634a02eb4495ac0a74b6e703869a"><a name="af2c1634a02eb4495ac0a74b6e703869a"></a><a name="af2c1634a02eb4495ac0a74b6e703869a"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="r7b111e09ef6e492693ef7c188aa69c88"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.1.4.1.1 "><p id="aee9ede07bd83422b9ee9a62129c06ed1"><a name="aee9ede07bd83422b9ee9a62129c06ed1"></a><a name="aee9ede07bd83422b9ee9a62129c06ed1"></a>sites</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.1.4.1.2 "><p id="a2915795f41f442549e0cf249f12eb8b3"><a name="a2915795f41f442549e0cf249f12eb8b3"></a><a name="a2915795f41f442549e0cf249f12eb8b3"></a>Array&lt;<a href="js-params.md#s60f796f99e2a42589d569ce7de36a113">Site</a>&gt;</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.4.1.3 "><p id="aae1929892f144c23975f655d38307015"><a name="aae1929892f144c23975f655d38307015"></a><a name="aae1929892f144c23975f655d38307015"></a>如果查询成功，返回搜索结果。如果没有结果，返回空数组。</p>
<div class="caution" id="note9272141116547"><a name="note9272141116547"></a><a name="note9272141116547"></a><span class="cautiontitle"> 注意： </span><div class="cautionbody"><p id="p152722011155413"><a name="p152722011155413"></a><a name="p152722011155413"></a>Site对象不返回POI信息。</p>
</div></div>
</td>
</tr>
</tbody>
</table>

## NearbySearchRequest<a name="se147bc59b0194eda80de17c0bdaee77c"></a>

<a name="t80aa9c47cd804d6a8d77b23c5d457290"></a>
<table><thead align="left"><tr id="r5f73faf2ae034c20806333a6052b2773"><th class="cellrowborder" valign="top" width="17.401740174017398%" id="mcps1.1.5.1.1"><p id="aa1ab9277b33840e08bf18723715b334b"><a name="aa1ab9277b33840e08bf18723715b334b"></a><a name="aa1ab9277b33840e08bf18723715b334b"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="14.001400140014002%" id="mcps1.1.5.1.2"><p id="a5e1f92b8bc2146dda733a1daeb3c1170"><a name="a5e1f92b8bc2146dda733a1daeb3c1170"></a><a name="a5e1f92b8bc2146dda733a1daeb3c1170"></a>是否必选</p>
</th>
<th class="cellrowborder" valign="top" width="16.38163816381638%" id="mcps1.1.5.1.3"><p id="afb860f5b5bb4434abf7ea34e6937039d"><a name="afb860f5b5bb4434abf7ea34e6937039d"></a><a name="afb860f5b5bb4434abf7ea34e6937039d"></a>参数类型</p>
</th>
<th class="cellrowborder" valign="top" width="52.21522152215221%" id="mcps1.1.5.1.4"><p id="ada0064b48aab47a281bddff8e7534c31"><a name="ada0064b48aab47a281bddff8e7534c31"></a><a name="ada0064b48aab47a281bddff8e7534c31"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="r3562fc6fd68644139667ff2371c65786"><td class="cellrowborder" valign="top" width="17.401740174017398%" headers="mcps1.1.5.1.1 "><p id="a252bda5e655f402faaf24265f513e2e1"><a name="a252bda5e655f402faaf24265f513e2e1"></a><a name="a252bda5e655f402faaf24265f513e2e1"></a>location</p>
</td>
<td class="cellrowborder" valign="top" width="14.001400140014002%" headers="mcps1.1.5.1.2 "><p id="a265a7187165d4506b9ee99ee2edbed8b"><a name="a265a7187165d4506b9ee99ee2edbed8b"></a><a name="a265a7187165d4506b9ee99ee2edbed8b"></a>是</p>
</td>
<td class="cellrowborder" valign="top" width="16.38163816381638%" headers="mcps1.1.5.1.3 "><p id="a5a1d5d11c63e47659b085cfefb02ae73"><a name="a5a1d5d11c63e47659b085cfefb02ae73"></a><a name="a5a1d5d11c63e47659b085cfefb02ae73"></a><a href="js-params.md#s45373a8938e040ca9f46c78f4283b385">LatLng</a></p>
</td>
<td class="cellrowborder" valign="top" width="52.21522152215221%" headers="mcps1.1.5.1.4 "><p id="a261ac9318f9245f2b2275d00e1c1f2a2"><a name="a261ac9318f9245f2b2275d00e1c1f2a2"></a><a name="a261ac9318f9245f2b2275d00e1c1f2a2"></a>当前用户的位置。</p>
</td>
</tr>
<tr id="r55d699c0f3b84831bb4bc750a4fe707b"><td class="cellrowborder" valign="top" width="17.401740174017398%" headers="mcps1.1.5.1.1 "><p id="a8c62a8bca86040bd8a0d417298915957"><a name="a8c62a8bca86040bd8a0d417298915957"></a><a name="a8c62a8bca86040bd8a0d417298915957"></a>radius</p>
</td>
<td class="cellrowborder" valign="top" width="14.001400140014002%" headers="mcps1.1.5.1.2 "><p id="a10f3b0264b5e4b8ba9f29159379d2cf5"><a name="a10f3b0264b5e4b8ba9f29159379d2cf5"></a><a name="a10f3b0264b5e4b8ba9f29159379d2cf5"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="16.38163816381638%" headers="mcps1.1.5.1.3 "><p id="ac2c26efa94f8496d8243d45d29118b1c"><a name="ac2c26efa94f8496d8243d45d29118b1c"></a><a name="ac2c26efa94f8496d8243d45d29118b1c"></a>Number</p>
</td>
<td class="cellrowborder" valign="top" width="52.21522152215221%" headers="mcps1.1.5.1.4 "><p id="p12115115171111"><a name="p12115115171111"></a><a name="p12115115171111"></a>可以指定搜索半径，单位：米。</p>
<p id="a5b2679fdc66b40efad9512ada576bbe2"><a name="a5b2679fdc66b40efad9512ada576bbe2"></a><a name="a5b2679fdc66b40efad9512ada576bbe2"></a>取值范围：[1, 50000]，默认1000米。</p>
</td>
</tr>
<tr id="r6eb140f6e5a34e17939bcfd7ee5da296"><td class="cellrowborder" valign="top" width="17.401740174017398%" headers="mcps1.1.5.1.1 "><p id="a1cf3f145ed8f40ddb6e3db42b87382b3"><a name="a1cf3f145ed8f40ddb6e3db42b87382b3"></a><a name="a1cf3f145ed8f40ddb6e3db42b87382b3"></a>query</p>
</td>
<td class="cellrowborder" valign="top" width="14.001400140014002%" headers="mcps1.1.5.1.2 "><p id="a4bd708fa40564cf39ab06dc9d845c46c"><a name="a4bd708fa40564cf39ab06dc9d845c46c"></a><a name="a4bd708fa40564cf39ab06dc9d845c46c"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="16.38163816381638%" headers="mcps1.1.5.1.3 "><p id="a8deb6431e2a1415fa2f94701cb3d3842"><a name="a8deb6431e2a1415fa2f94701cb3d3842"></a><a name="a8deb6431e2a1415fa2f94701cb3d3842"></a>String(&lt;=512)</p>
</td>
<td class="cellrowborder" valign="top" width="52.21522152215221%" headers="mcps1.1.5.1.4 "><p id="af01928369019461f8151ab95c8947f3f"><a name="af01928369019461f8151ab95c8947f3f"></a><a name="af01928369019461f8151ab95c8947f3f"></a>可以输入搜索关键字。</p>
</td>
</tr>
<tr id="r6e49d92d8c8644d18c8cb513d0685a86"><td class="cellrowborder" valign="top" width="17.401740174017398%" headers="mcps1.1.5.1.1 "><p id="a5d73b03313054a75ad09c416b5b691fc"><a name="a5d73b03313054a75ad09c416b5b691fc"></a><a name="a5d73b03313054a75ad09c416b5b691fc"></a>poiType</p>
</td>
<td class="cellrowborder" valign="top" width="14.001400140014002%" headers="mcps1.1.5.1.2 "><p id="ac32f2b8861f04daaae7314ebe724404e"><a name="ac32f2b8861f04daaae7314ebe724404e"></a><a name="ac32f2b8861f04daaae7314ebe724404e"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="16.38163816381638%" headers="mcps1.1.5.1.3 "><p id="a76f0f968934848fea6ada5d93ec1cb1c"><a name="a76f0f968934848fea6ada5d93ec1cb1c"></a><a name="a76f0f968934848fea6ada5d93ec1cb1c"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="52.21522152215221%" headers="mcps1.1.5.1.4 "><p id="acf1fc0e4acce4a8bb7fc7b8c2973d0b1"><a name="acf1fc0e4acce4a8bb7fc7b8c2973d0b1"></a><a name="acf1fc0e4acce4a8bb7fc7b8c2973d0b1"></a>返回指定POI类型的地点。</p>
</td>
</tr>
<tr id="r4fb04dbd400e477dbe579918fe8762c0"><td class="cellrowborder" valign="top" width="17.401740174017398%" headers="mcps1.1.5.1.1 "><p id="ac029f6109c3340ec8ce4f855e1debe8d"><a name="ac029f6109c3340ec8ce4f855e1debe8d"></a><a name="ac029f6109c3340ec8ce4f855e1debe8d"></a>language</p>
</td>
<td class="cellrowborder" valign="top" width="14.001400140014002%" headers="mcps1.1.5.1.2 "><p id="a0a8657c32285494495df172f3a6ce13e"><a name="a0a8657c32285494495df172f3a6ce13e"></a><a name="a0a8657c32285494495df172f3a6ce13e"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="16.38163816381638%" headers="mcps1.1.5.1.3 "><p id="adecbacd585a942259b7b5c5175cc5054"><a name="adecbacd585a942259b7b5c5175cc5054"></a><a name="adecbacd585a942259b7b5c5175cc5054"></a>String(&lt;=6)</p>
</td>
<td class="cellrowborder" valign="top" width="52.21522152215221%" headers="mcps1.1.5.1.4 "><p id="aaabe21eb9d2b4c83a872e1376fb33496"><a name="aaabe21eb9d2b4c83a872e1376fb33496"></a><a name="aaabe21eb9d2b4c83a872e1376fb33496"></a>搜索建议的语种，语种取值请参见<a href="zh-cn_topic_0000001050162856.md">支持的语言</a>列表。如果不指定语种，返回地点的当地语言。</p>
</td>
</tr>
<tr id="rbcb562474e1440278e1209d34037aaf3"><td class="cellrowborder" valign="top" width="17.401740174017398%" headers="mcps1.1.5.1.1 "><p id="af8f400841c3c46d8ac512cb896077801"><a name="af8f400841c3c46d8ac512cb896077801"></a><a name="af8f400841c3c46d8ac512cb896077801"></a>pageSize</p>
</td>
<td class="cellrowborder" valign="top" width="14.001400140014002%" headers="mcps1.1.5.1.2 "><p id="a71a0ac8855ee49afbbe955d68d9e49f6"><a name="a71a0ac8855ee49afbbe955d68d9e49f6"></a><a name="a71a0ac8855ee49afbbe955d68d9e49f6"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="16.38163816381638%" headers="mcps1.1.5.1.3 "><p id="a22dcd6cd957b48d8b621832f1e8eecbb"><a name="a22dcd6cd957b48d8b621832f1e8eecbb"></a><a name="a22dcd6cd957b48d8b621832f1e8eecbb"></a>Number</p>
</td>
<td class="cellrowborder" valign="top" width="52.21522152215221%" headers="mcps1.1.5.1.4 "><p id="ada22334b115f483fbb7d6f9d5a67fb61"><a name="ada22334b115f483fbb7d6f9d5a67fb61"></a><a name="ada22334b115f483fbb7d6f9d5a67fb61"></a>每页返回的记录数。</p>
<p id="a6e75182c0e0e47e9be12b09b84464dfc"><a name="a6e75182c0e0e47e9be12b09b84464dfc"></a><a name="a6e75182c0e0e47e9be12b09b84464dfc"></a>取值范围：[1, 20]，默认20。</p>
</td>
</tr>
<tr id="r02fab18298f04133b5ab3220e6d65b8a"><td class="cellrowborder" valign="top" width="17.401740174017398%" headers="mcps1.1.5.1.1 "><p id="a2afccd1a07d5400abf31a0f16a265c5a"><a name="a2afccd1a07d5400abf31a0f16a265c5a"></a><a name="a2afccd1a07d5400abf31a0f16a265c5a"></a>pageIndex</p>
</td>
<td class="cellrowborder" valign="top" width="14.001400140014002%" headers="mcps1.1.5.1.2 "><p id="a7d3631b3650e49dabd1cac1f678b9be3"><a name="a7d3631b3650e49dabd1cac1f678b9be3"></a><a name="a7d3631b3650e49dabd1cac1f678b9be3"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="16.38163816381638%" headers="mcps1.1.5.1.3 "><p id="ae866c30b81774dc4a9bc41246740b9ed"><a name="ae866c30b81774dc4a9bc41246740b9ed"></a><a name="ae866c30b81774dc4a9bc41246740b9ed"></a>Number</p>
</td>
<td class="cellrowborder" valign="top" width="52.21522152215221%" headers="mcps1.1.5.1.4 "><p id="abc7dbfe2d84349cba7a186f970df04fb"><a name="abc7dbfe2d84349cba7a186f970df04fb"></a><a name="abc7dbfe2d84349cba7a186f970df04fb"></a>当前页数。</p>
<p id="a991a37baad4244a48842ab139653eb34"><a name="a991a37baad4244a48842ab139653eb34"></a><a name="a991a37baad4244a48842ab139653eb34"></a>取值范围：[1, 60]，默认1。</p>
<p id="a731dc585b41c4397ac804e1ee7acd988"><a name="a731dc585b41c4397ac804e1ee7acd988"></a><a name="a731dc585b41c4397ac804e1ee7acd988"></a>约束：pageindex*pagesize &lt;= 60。</p>
</td>
</tr>
<tr id="r0642d9afc61644579f616c99b4c0e767"><td class="cellrowborder" valign="top" width="17.401740174017398%" headers="mcps1.1.5.1.1 "><p id="a178a246f9b644bcbaf6093b4fd06642e"><a name="a178a246f9b644bcbaf6093b4fd06642e"></a><a name="a178a246f9b644bcbaf6093b4fd06642e"></a>politicalView</p>
</td>
<td class="cellrowborder" valign="top" width="14.001400140014002%" headers="mcps1.1.5.1.2 "><p id="a3c1a687d729841b7af7122116a58f086"><a name="a3c1a687d729841b7af7122116a58f086"></a><a name="a3c1a687d729841b7af7122116a58f086"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="16.38163816381638%" headers="mcps1.1.5.1.3 "><p id="a0e382666d76b45e1950c8d57cb5341ab"><a name="a0e382666d76b45e1950c8d57cb5341ab"></a><a name="a0e382666d76b45e1950c8d57cb5341ab"></a>String(=2)</p>
</td>
<td class="cellrowborder" valign="top" width="52.21522152215221%" headers="mcps1.1.5.1.4 "><p id="ad2f4f9200b7c4340b0e208ec75de0af3"><a name="ad2f4f9200b7c4340b0e208ec75de0af3"></a><a name="ad2f4f9200b7c4340b0e208ec75de0af3"></a>政治观点参数，采用ISO 3166-1 alpha-2规范的2位国家码。</p>
<div class="caution" id="note105419228395"><a name="note105419228395"></a><a name="note105419228395"></a><span class="cautiontitle"> 注意： </span><div class="cautionbody"><p id="p3541422163916"><a name="p3541422163916"></a><a name="p3541422163916"></a>该参数已废弃。</p>
</div></div>
</td>
</tr>
</tbody>
</table>

## NearbySearchResult<a name="s76ba1898bfc5490ca57e0d3c50fee30d"></a>

<a name="te517018939444973a93912ccf73b6e08"></a>
<table><thead align="left"><tr id="r64e20599d06541f0add69b917ccb6fb1"><th class="cellrowborder" valign="top" width="18.18%" id="mcps1.1.4.1.1"><p id="afcb155a6006349b893122e621a3f8603"><a name="afcb155a6006349b893122e621a3f8603"></a><a name="afcb155a6006349b893122e621a3f8603"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="18.18%" id="mcps1.1.4.1.2"><p id="a18241c80563843519f808260cd824059"><a name="a18241c80563843519f808260cd824059"></a><a name="a18241c80563843519f808260cd824059"></a>参数类型</p>
</th>
<th class="cellrowborder" valign="top" width="63.63999999999999%" id="mcps1.1.4.1.3"><p id="affb7945673ab4501af049d0ef32e1d8b"><a name="affb7945673ab4501af049d0ef32e1d8b"></a><a name="affb7945673ab4501af049d0ef32e1d8b"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="rebe3c1f5a4744964b2514cc73288ebff"><td class="cellrowborder" valign="top" width="18.18%" headers="mcps1.1.4.1.1 "><p id="ace587f0b48d24b1884dc5b931ba35ede"><a name="ace587f0b48d24b1884dc5b931ba35ede"></a><a name="ace587f0b48d24b1884dc5b931ba35ede"></a>totalCount</p>
</td>
<td class="cellrowborder" valign="top" width="18.18%" headers="mcps1.1.4.1.2 "><p id="a77dd495edec0487c867b71f3a650d40c"><a name="a77dd495edec0487c867b71f3a650d40c"></a><a name="a77dd495edec0487c867b71f3a650d40c"></a>Number</p>
</td>
<td class="cellrowborder" valign="top" width="63.63999999999999%" headers="mcps1.1.4.1.3 "><p id="a450f5b9a1f174ebc9fd5c36e139043c8"><a name="a450f5b9a1f174ebc9fd5c36e139043c8"></a><a name="a450f5b9a1f174ebc9fd5c36e139043c8"></a>如果查询成功，返回记录总数。如果没有结果，返回0。</p>
</td>
</tr>
<tr id="rdc59ee878107435ab1358e18ed0d5cd6"><td class="cellrowborder" valign="top" width="18.18%" headers="mcps1.1.4.1.1 "><p id="acfaeede0b60d4feca80e3e7472f2d697"><a name="acfaeede0b60d4feca80e3e7472f2d697"></a><a name="acfaeede0b60d4feca80e3e7472f2d697"></a>sites</p>
</td>
<td class="cellrowborder" valign="top" width="18.18%" headers="mcps1.1.4.1.2 "><p id="af74f9e68dbe74f7abe4ad863e25587cf"><a name="af74f9e68dbe74f7abe4ad863e25587cf"></a><a name="af74f9e68dbe74f7abe4ad863e25587cf"></a>Array&lt;<a href="js-params.md#s60f796f99e2a42589d569ce7de36a113">Site</a>&gt;</p>
</td>
<td class="cellrowborder" valign="top" width="63.63999999999999%" headers="mcps1.1.4.1.3 "><p id="a50467eca606c41d4ad6525e8adef89b9"><a name="a50467eca606c41d4ad6525e8adef89b9"></a><a name="a50467eca606c41d4ad6525e8adef89b9"></a>如果查询成功，返回搜索结果。如果没有结果，返回空数组。</p>
</td>
</tr>
</tbody>
</table>

## QuerySuggestionRequest<a name="sd7916193426041b1b9579296b161bba6"></a>

<a name="t7edb02d90be44e8fb5ebcb3501307a31"></a>
<table><thead align="left"><tr id="rd3955541e624433693509a0e23bc24ec"><th class="cellrowborder" valign="top" width="17.401740174017398%" id="mcps1.1.5.1.1"><p id="a0d0ff58dad344af1ab2ca94e9d0a5602"><a name="a0d0ff58dad344af1ab2ca94e9d0a5602"></a><a name="a0d0ff58dad344af1ab2ca94e9d0a5602"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="14.001400140014002%" id="mcps1.1.5.1.2"><p id="a36be54aa5e0a492f8e0dcecd3e661e67"><a name="a36be54aa5e0a492f8e0dcecd3e661e67"></a><a name="a36be54aa5e0a492f8e0dcecd3e661e67"></a>是否必选</p>
</th>
<th class="cellrowborder" valign="top" width="16.38163816381638%" id="mcps1.1.5.1.3"><p id="a5d85a95327034041be0d1077b6b0dbb6"><a name="a5d85a95327034041be0d1077b6b0dbb6"></a><a name="a5d85a95327034041be0d1077b6b0dbb6"></a>参数类型</p>
</th>
<th class="cellrowborder" valign="top" width="52.21522152215221%" id="mcps1.1.5.1.4"><p id="aa4992e2c9a7e458a970ff132c2df15a2"><a name="aa4992e2c9a7e458a970ff132c2df15a2"></a><a name="aa4992e2c9a7e458a970ff132c2df15a2"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="r39cafa95da764f06b1d7b314fe7e5869"><td class="cellrowborder" valign="top" width="17.401740174017398%" headers="mcps1.1.5.1.1 "><p id="aa402e4df1e074396acfdf70bdf4f8cce"><a name="aa402e4df1e074396acfdf70bdf4f8cce"></a><a name="aa402e4df1e074396acfdf70bdf4f8cce"></a>query</p>
</td>
<td class="cellrowborder" valign="top" width="14.001400140014002%" headers="mcps1.1.5.1.2 "><p id="a3973f6c83c6441ff948cf3bb15cbacf6"><a name="a3973f6c83c6441ff948cf3bb15cbacf6"></a><a name="a3973f6c83c6441ff948cf3bb15cbacf6"></a>是</p>
</td>
<td class="cellrowborder" valign="top" width="16.38163816381638%" headers="mcps1.1.5.1.3 "><p id="ab256cb82f71a427da5a1a9ca88331bce"><a name="ab256cb82f71a427da5a1a9ca88331bce"></a><a name="ab256cb82f71a427da5a1a9ca88331bce"></a>String(&lt;=512)</p>
</td>
<td class="cellrowborder" valign="top" width="52.21522152215221%" headers="mcps1.1.5.1.4 "><p id="ab551155dc07846f99fcbc4a6f6cc75e7"><a name="ab551155dc07846f99fcbc4a6f6cc75e7"></a><a name="ab551155dc07846f99fcbc4a6f6cc75e7"></a>搜索关键字。</p>
</td>
</tr>
<tr id="r729716d710f443238da2450037e402c8"><td class="cellrowborder" valign="top" width="17.401740174017398%" headers="mcps1.1.5.1.1 "><p id="a326588f1caed43d6bb75940319f30d1f"><a name="a326588f1caed43d6bb75940319f30d1f"></a><a name="a326588f1caed43d6bb75940319f30d1f"></a>location</p>
</td>
<td class="cellrowborder" valign="top" width="14.001400140014002%" headers="mcps1.1.5.1.2 "><p id="a2bde602437b14396b205e915268aa90a"><a name="a2bde602437b14396b205e915268aa90a"></a><a name="a2bde602437b14396b205e915268aa90a"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="16.38163816381638%" headers="mcps1.1.5.1.3 "><p id="a75c4a72307ab44f781e0a75d771c7b34"><a name="a75c4a72307ab44f781e0a75d771c7b34"></a><a name="a75c4a72307ab44f781e0a75d771c7b34"></a><a href="js-params.md#s45373a8938e040ca9f46c78f4283b385">LatLng</a></p>
</td>
<td class="cellrowborder" valign="top" width="52.21522152215221%" headers="mcps1.1.5.1.4 "><p id="a90c9e307a767402e8072f4e6a7882e64"><a name="a90c9e307a767402e8072f4e6a7882e64"></a><a name="a90c9e307a767402e8072f4e6a7882e64"></a>搜索建议偏向的经纬度。</p>
</td>
</tr>
<tr id="rd2386e2a765e446fb57733b84e85ce09"><td class="cellrowborder" valign="top" width="17.401740174017398%" headers="mcps1.1.5.1.1 "><p id="a3f08406480f14a8dbe97247759117562"><a name="a3f08406480f14a8dbe97247759117562"></a><a name="a3f08406480f14a8dbe97247759117562"></a>radius</p>
</td>
<td class="cellrowborder" valign="top" width="14.001400140014002%" headers="mcps1.1.5.1.2 "><p id="af300d1fa24864d3085face9b6404dd5e"><a name="af300d1fa24864d3085face9b6404dd5e"></a><a name="af300d1fa24864d3085face9b6404dd5e"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="16.38163816381638%" headers="mcps1.1.5.1.3 "><p id="a5be7514e98e547b69df5317227bbd2b6"><a name="a5be7514e98e547b69df5317227bbd2b6"></a><a name="a5be7514e98e547b69df5317227bbd2b6"></a>Number</p>
</td>
<td class="cellrowborder" valign="top" width="52.21522152215221%" headers="mcps1.1.5.1.4 "><p id="p6519103313118"><a name="p6519103313118"></a><a name="p6519103313118"></a>Location的搜索半径，单位：米。</p>
<p id="a40344f2c87a3494c8d7b60fb5c2c5719"><a name="a40344f2c87a3494c8d7b60fb5c2c5719"></a><a name="a40344f2c87a3494c8d7b60fb5c2c5719"></a>取值范围：[1, 50000]，默认50000米。</p>
</td>
</tr>
<tr id="r983371aab1b246c68f3eb0ea563629f4"><td class="cellrowborder" valign="top" width="17.401740174017398%" headers="mcps1.1.5.1.1 "><p id="a6946b04742e840d39c24c723ab0fb816"><a name="a6946b04742e840d39c24c723ab0fb816"></a><a name="a6946b04742e840d39c24c723ab0fb816"></a>bounds</p>
</td>
<td class="cellrowborder" valign="top" width="14.001400140014002%" headers="mcps1.1.5.1.2 "><p id="a7fe631a02bcc444ba55719f29861cdc2"><a name="a7fe631a02bcc444ba55719f29861cdc2"></a><a name="a7fe631a02bcc444ba55719f29861cdc2"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="16.38163816381638%" headers="mcps1.1.5.1.3 "><p id="a9de77393ded541b5a75274de97e8eb16"><a name="a9de77393ded541b5a75274de97e8eb16"></a><a name="a9de77393ded541b5a75274de97e8eb16"></a><a href="js-params.md#s7da68d05f25f42949a5700ac4cf28a27">LatLngBounds</a></p>
</td>
<td class="cellrowborder" valign="top" width="52.21522152215221%" headers="mcps1.1.5.1.4 "><p id="a6c30fb65aede431a96398f4789586bf9"><a name="a6c30fb65aede431a96398f4789586bf9"></a><a name="a6c30fb65aede431a96398f4789586bf9"></a>搜索建议偏向的搜索范围。</p>
<div class="caution" id="note192134581559"><a name="note192134581559"></a><a name="note192134581559"></a><span class="cautiontitle"> 注意： </span><div class="cautionbody"><p id="p1621325818551"><a name="p1621325818551"></a><a name="p1621325818551"></a>如果bounds、location都传的话，那么bounds优先。</p>
</div></div>
</td>
</tr>
<tr id="r3bf70dd740eb4727bcaf6f2196e969b4"><td class="cellrowborder" valign="top" width="17.401740174017398%" headers="mcps1.1.5.1.1 "><p id="a7eb50c12bcea44958e8163e25aa66e09"><a name="a7eb50c12bcea44958e8163e25aa66e09"></a><a name="a7eb50c12bcea44958e8163e25aa66e09"></a>poiType</p>
</td>
<td class="cellrowborder" valign="top" width="14.001400140014002%" headers="mcps1.1.5.1.2 "><p id="a9afe1f132cfc4e61ba7ddb9a2d5c0434"><a name="a9afe1f132cfc4e61ba7ddb9a2d5c0434"></a><a name="a9afe1f132cfc4e61ba7ddb9a2d5c0434"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="16.38163816381638%" headers="mcps1.1.5.1.3 "><p id="ad7a40ec37c3b41bdb1e5746fda2b1f28"><a name="ad7a40ec37c3b41bdb1e5746fda2b1f28"></a><a name="ad7a40ec37c3b41bdb1e5746fda2b1f28"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="52.21522152215221%" headers="mcps1.1.5.1.4 "><p id="ad479dd39bd0242bd83bfcc81b5d441dc"><a name="ad479dd39bd0242bd83bfcc81b5d441dc"></a><a name="ad479dd39bd0242bd83bfcc81b5d441dc"></a>返回指定POI类型的地点。</p>
<p id="aa907074aabcf41c4a5113ac08dc3f7b0"><a name="aa907074aabcf41c4a5113ac08dc3f7b0"></a><a name="aa907074aabcf41c4a5113ac08dc3f7b0"></a>取值包括：</p>
<a name="u47a438e326d8442eb2fd47e9677aee35"></a><a name="u47a438e326d8442eb2fd47e9677aee35"></a><ul id="u47a438e326d8442eb2fd47e9677aee35"><li>GEOCODE ： 仅返回地理编码结果（如国家、城市、街道等），而不返回商业结果（如酒店、餐馆、火车站等）。可以使用此类型过滤掉商业数据，消除用户输入中存在的歧义。例如：用户输入中国时，返回中国，不返回中国银行等数据。</li><li>ADDRESS：GEOCODE的子集。仅返回具有精确地址的地理编码结果，不返回商业结果和粗粒度的地理编码结果（如国家、城市等），推荐在搜索完整地址时使用此类型。</li><li>ESTABLISHMENT：GEOCODE的补集。仅返回作为商业结果（如酒店、餐馆、火车站等），不返回地理编码结果（如国家、城市、街道等）。例如：用户输入中国时，返回中国银行等数据，不返回中国。</li><li>REGIONS ：GEOCODE的子集，仅返回与以下类型匹配的地点：<p id="ae6ff2e8f70d849acbced1bb99ccc6c3d"><a name="ae6ff2e8f70d849acbced1bb99ccc6c3d"></a><a name="ae6ff2e8f70d849acbced1bb99ccc6c3d"></a>LOCALITY</p>
<p id="abe60c9972cc64d5b85ab0e398edfb838"><a name="abe60c9972cc64d5b85ab0e398edfb838"></a><a name="abe60c9972cc64d5b85ab0e398edfb838"></a>SUBLOCALITY</p>
<p id="ae3c72d328144495caac69ad5c5422a31"><a name="ae3c72d328144495caac69ad5c5422a31"></a><a name="ae3c72d328144495caac69ad5c5422a31"></a>POSTAL_CODE</p>
<p id="a4b0c6e59ddb3452bada1c1b01babb262"><a name="a4b0c6e59ddb3452bada1c1b01babb262"></a><a name="a4b0c6e59ddb3452bada1c1b01babb262"></a>COUNTRY</p>
<p id="ad42a1adb732848d1b22001705e4b25ce"><a name="ad42a1adb732848d1b22001705e4b25ce"></a><a name="ad42a1adb732848d1b22001705e4b25ce"></a>ADMINISTRATIVE_AREA_LEVEL_1</p>
<p id="a0d74199a8a094325a857721998893c30"><a name="a0d74199a8a094325a857721998893c30"></a><a name="a0d74199a8a094325a857721998893c30"></a>ADMINISTRATIVE_AREA_LEVEL_2</p>
</li><li>CITIES：仅返回LOCALITY或ADMINISTRATIVE_AREA_LEVEL_3类型的地点。</li></ul>
</td>
</tr>
<tr id="r60f22b0445e040c89c7f03b335140b7b"><td class="cellrowborder" valign="top" width="17.401740174017398%" headers="mcps1.1.5.1.1 "><p id="a530d484ec3e94c51a10b51e06b4c14bf"><a name="a530d484ec3e94c51a10b51e06b4c14bf"></a><a name="a530d484ec3e94c51a10b51e06b4c14bf"></a>countryCode</p>
</td>
<td class="cellrowborder" valign="top" width="14.001400140014002%" headers="mcps1.1.5.1.2 "><p id="a9d0a9f3ba45a4245bbfe96b5f774d908"><a name="a9d0a9f3ba45a4245bbfe96b5f774d908"></a><a name="a9d0a9f3ba45a4245bbfe96b5f774d908"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="16.38163816381638%" headers="mcps1.1.5.1.3 "><p id="a6b2b79dca0a44d46bf13df6d455f03ca"><a name="a6b2b79dca0a44d46bf13df6d455f03ca"></a><a name="a6b2b79dca0a44d46bf13df6d455f03ca"></a>String(=2)</p>
</td>
<td class="cellrowborder" valign="top" width="52.21522152215221%" headers="mcps1.1.5.1.4 "><p id="a66a40dc0b62d4fafb8aeea93c788fa05"><a name="a66a40dc0b62d4fafb8aeea93c788fa05"></a><a name="a66a40dc0b62d4fafb8aeea93c788fa05"></a>在指定的国家内搜索，采用ISO 3166-1 alpha-2规范的2位国家码。</p>
</td>
</tr>
<tr id="r15ec375846a1453d927f48a576db4611"><td class="cellrowborder" valign="top" width="17.401740174017398%" headers="mcps1.1.5.1.1 "><p id="a6ba79855b6d042d0b8d0bf5b90edba5e"><a name="a6ba79855b6d042d0b8d0bf5b90edba5e"></a><a name="a6ba79855b6d042d0b8d0bf5b90edba5e"></a>language</p>
</td>
<td class="cellrowborder" valign="top" width="14.001400140014002%" headers="mcps1.1.5.1.2 "><p id="abf347cc32ad24d37aaae8305f0ce4296"><a name="abf347cc32ad24d37aaae8305f0ce4296"></a><a name="abf347cc32ad24d37aaae8305f0ce4296"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="16.38163816381638%" headers="mcps1.1.5.1.3 "><p id="a3ffba1069f8e4c7ca277c109714096fd"><a name="a3ffba1069f8e4c7ca277c109714096fd"></a><a name="a3ffba1069f8e4c7ca277c109714096fd"></a>String(&lt;=6)</p>
</td>
<td class="cellrowborder" valign="top" width="52.21522152215221%" headers="mcps1.1.5.1.4 "><p id="ac36d65d5baa047978a624e25da965dd9"><a name="ac36d65d5baa047978a624e25da965dd9"></a><a name="ac36d65d5baa047978a624e25da965dd9"></a>搜索建议的语种，语种取值请参见<a href="zh-cn_topic_0000001050162856.md">支持的语言</a>列表。如果不指定语种，返回地点的当地语言。</p>
</td>
</tr>
<tr id="row16392173101517"><td class="cellrowborder" valign="top" width="17.401740174017398%" headers="mcps1.1.5.1.1 "><p id="p121184291594"><a name="p121184291594"></a><a name="p121184291594"></a>countries</p>
</td>
<td class="cellrowborder" valign="top" width="14.001400140014002%" headers="mcps1.1.5.1.2 "><p id="p611815298918"><a name="p611815298918"></a><a name="p611815298918"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="16.38163816381638%" headers="mcps1.1.5.1.3 "><p id="p1011817291198"><a name="p1011817291198"></a><a name="p1011817291198"></a>Array&lt;String(=2)&gt;</p>
</td>
<td class="cellrowborder" valign="top" width="52.21522152215221%" headers="mcps1.1.5.1.4 "><p id="p1311822916912"><a name="p1311822916912"></a><a name="p1311822916912"></a>多个国家码，采用ISO 3166-1 alpha-2规范的2位国家码。</p>
</td>
</tr>
<tr id="rec555826152747988c9fed6b8b9c8032"><td class="cellrowborder" valign="top" width="17.401740174017398%" headers="mcps1.1.5.1.1 "><p id="a5b01312beb244bbdb574d065b0b64d38"><a name="a5b01312beb244bbdb574d065b0b64d38"></a><a name="a5b01312beb244bbdb574d065b0b64d38"></a>politicalView</p>
</td>
<td class="cellrowborder" valign="top" width="14.001400140014002%" headers="mcps1.1.5.1.2 "><p id="ac1bcffe4b5304983a6419b6ab6fbd86b"><a name="ac1bcffe4b5304983a6419b6ab6fbd86b"></a><a name="ac1bcffe4b5304983a6419b6ab6fbd86b"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="16.38163816381638%" headers="mcps1.1.5.1.3 "><p id="ae2f06619a7094aae9e9eaf1ffcbad2e1"><a name="ae2f06619a7094aae9e9eaf1ffcbad2e1"></a><a name="ae2f06619a7094aae9e9eaf1ffcbad2e1"></a>String(=2)</p>
</td>
<td class="cellrowborder" valign="top" width="52.21522152215221%" headers="mcps1.1.5.1.4 "><p id="aced333869dd84318a3dc4a237926326f"><a name="aced333869dd84318a3dc4a237926326f"></a><a name="aced333869dd84318a3dc4a237926326f"></a>政治观点参数，采用ISO 3166-1 alpha-2规范的2位国家码。</p>
<div class="caution" id="note13222123623911"><a name="note13222123623911"></a><a name="note13222123623911"></a><span class="cautiontitle"> 注意： </span><div class="cautionbody"><p id="p6222173623914"><a name="p6222173623914"></a><a name="p6222173623914"></a>该参数已废弃。</p>
</div></div>
</td>
</tr>
</tbody>
</table>

## QuerySuggestionResult<a name="s2dc38e671e904caab9d133069638a4f1"></a>

<a name="t1830be596a3c4d9dac27cee2b9307aaf"></a>
<table><thead align="left"><tr id="r158a8a83b5e4434e97bb0dac1d1a448b"><th class="cellrowborder" valign="top" width="20%" id="mcps1.1.4.1.1"><p id="a3c612ede98b74865a1ae31ab98519d89"><a name="a3c612ede98b74865a1ae31ab98519d89"></a><a name="a3c612ede98b74865a1ae31ab98519d89"></a><strong id="aaaa768f637a14037a7b1ac66aedd7646"><a name="aaaa768f637a14037a7b1ac66aedd7646"></a><a name="aaaa768f637a14037a7b1ac66aedd7646"></a>参数</strong></p>
</th>
<th class="cellrowborder" valign="top" width="22%" id="mcps1.1.4.1.2"><p id="ab8b6719690c94c41846266b8ce71ba02"><a name="ab8b6719690c94c41846266b8ce71ba02"></a><a name="ab8b6719690c94c41846266b8ce71ba02"></a><strong id="aad09f4f8fd0149f699b10ee2019b0b98"><a name="aad09f4f8fd0149f699b10ee2019b0b98"></a><a name="aad09f4f8fd0149f699b10ee2019b0b98"></a>参数类型</strong></p>
</th>
<th class="cellrowborder" valign="top" width="57.99999999999999%" id="mcps1.1.4.1.3"><p id="a2e96620ebd654dec9996bd04ca5da70e"><a name="a2e96620ebd654dec9996bd04ca5da70e"></a><a name="a2e96620ebd654dec9996bd04ca5da70e"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="r253c2e6ea8e74a60b576f9e5da8ef813"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.1.4.1.1 "><p id="accf16070e81b4bf7bdfb1fd5afaa9cb7"><a name="accf16070e81b4bf7bdfb1fd5afaa9cb7"></a><a name="accf16070e81b4bf7bdfb1fd5afaa9cb7"></a>sites</p>
</td>
<td class="cellrowborder" valign="top" width="22%" headers="mcps1.1.4.1.2 "><p id="acb618d5ca91840b9b1174c27a40d5283"><a name="acb618d5ca91840b9b1174c27a40d5283"></a><a name="acb618d5ca91840b9b1174c27a40d5283"></a>Array&lt;<a href="js-params.md#s60f796f99e2a42589d569ce7de36a113">Site</a>&gt;</p>
</td>
<td class="cellrowborder" valign="top" width="57.99999999999999%" headers="mcps1.1.4.1.3 "><p id="a504c5be904b74af4a2c98e0a9b12a99c"><a name="a504c5be904b74af4a2c98e0a9b12a99c"></a><a name="a504c5be904b74af4a2c98e0a9b12a99c"></a>如果查询成功，返回搜索结果。如果没有结果，返回空数组。</p>
<div class="caution" id="note1158215346568"><a name="note1158215346568"></a><a name="note1158215346568"></a><span class="cautiontitle"> 注意： </span><div class="cautionbody"><p id="p65821734115612"><a name="p65821734115612"></a><a name="p65821734115612"></a>Site对象不返回POI信息。</p>
</div></div>
</td>
</tr>
</tbody>
</table>

## ReverseGeocodeRequest<a name="s871ce65677cc4e1dbfd1636c3b325d6f"></a>

<a name="table813562911913"></a>
<table><thead align="left"><tr id="row11135629096"><th class="cellrowborder" valign="top" width="18%" id="mcps1.1.5.1.1"><p id="p813514299918"><a name="p813514299918"></a><a name="p813514299918"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="14.000000000000002%" id="mcps1.1.5.1.2"><p id="p813510291299"><a name="p813510291299"></a><a name="p813510291299"></a>是否必选</p>
</th>
<th class="cellrowborder" valign="top" width="16%" id="mcps1.1.5.1.3"><p id="p213517291494"><a name="p213517291494"></a><a name="p213517291494"></a>参数类型</p>
</th>
<th class="cellrowborder" valign="top" width="52%" id="mcps1.1.5.1.4"><p id="p111351292095"><a name="p111351292095"></a><a name="p111351292095"></a>参数说明</p>
</th>
</tr>
</thead>
<tbody><tr id="row11355293910"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="p8136172910919"><a name="p8136172910919"></a><a name="p8136172910919"></a>location</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="p11365291293"><a name="p11365291293"></a><a name="p11365291293"></a>是</p>
</td>
<td class="cellrowborder" valign="top" width="16%" headers="mcps1.1.5.1.3 "><p id="p191363299913"><a name="p191363299913"></a><a name="p191363299913"></a><a href="js-params.md#s45373a8938e040ca9f46c78f4283b385">LatLng</a></p>
</td>
<td class="cellrowborder" valign="top" width="52%" headers="mcps1.1.5.1.4 "><p id="p191361429593"><a name="p191361429593"></a><a name="p191361429593"></a>经纬度。</p>
</td>
</tr>
<tr id="row141361429593"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="p013632911912"><a name="p013632911912"></a><a name="p013632911912"></a>language</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="p171368291095"><a name="p171368291095"></a><a name="p171368291095"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="16%" headers="mcps1.1.5.1.3 "><p id="p61366296916"><a name="p61366296916"></a><a name="p61366296916"></a>String(&lt;=6)</p>
</td>
<td class="cellrowborder" valign="top" width="52%" headers="mcps1.1.5.1.4 "><p id="p613613293915"><a name="p613613293915"></a><a name="p613613293915"></a>搜索结果的语种，语种取值请参见<a href="zh-cn_topic_0000001050162856.md">支持的语言</a>列表。如果不指定语种，返回地点的当地语言。</p>
</td>
</tr>
<tr id="row613612916916"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="p7136172918916"><a name="p7136172918916"></a><a name="p7136172918916"></a>returnPoi</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="p9136129198"><a name="p9136129198"></a><a name="p9136129198"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="16%" headers="mcps1.1.5.1.3 "><p id="p1013615291392"><a name="p1013615291392"></a><a name="p1013615291392"></a>Boolean</p>
</td>
<td class="cellrowborder" valign="top" width="52%" headers="mcps1.1.5.1.4 "><p id="p21361329996"><a name="p21361329996"></a><a name="p21361329996"></a>是否返回POI的地点名称，默认为true。</p>
<div class="note" id="note14136729794"><a name="note14136729794"></a><a name="note14136729794"></a><span class="notetitle"> 说明： </span><div class="notebody"><p id="p713662913918"><a name="p713662913918"></a><a name="p713662913918"></a>目前逆地理接口，只能返回机场的名称，其他POI不支持返回名称。</p>
</div></div>
</td>
</tr>
<tr id="row8137229699"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="p7137172912910"><a name="p7137172912910"></a><a name="p7137172912910"></a>politicalView</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="p101372291898"><a name="p101372291898"></a><a name="p101372291898"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="16%" headers="mcps1.1.5.1.3 "><p id="p1013718292913"><a name="p1013718292913"></a><a name="p1013718292913"></a>String(=2)</p>
</td>
<td class="cellrowborder" valign="top" width="52%" headers="mcps1.1.5.1.4 "><p id="p1313711296911"><a name="p1313711296911"></a><a name="p1313711296911"></a>政治观点参数，采用ISO 3166-1 alpha-2规范的2位国家码。</p>
<div class="caution" id="note13391446193912"><a name="note13391446193912"></a><a name="note13391446193912"></a><span class="cautiontitle"> 注意： </span><div class="cautionbody"><p id="p194014623919"><a name="p194014623919"></a><a name="p194014623919"></a>该参数已废弃。</p>
</div></div>
</td>
</tr>
</tbody>
</table>

## ReverseGeocodeResult<a name="s682816b9645c4c928831c554b541e014"></a>

<a name="table17467449096"></a>
<table><thead align="left"><tr id="row14467164913915"><th class="cellrowborder" valign="top" width="20%" id="mcps1.1.4.1.1"><p id="p104671549496"><a name="p104671549496"></a><a name="p104671549496"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="20%" id="mcps1.1.4.1.2"><p id="p154672049599"><a name="p154672049599"></a><a name="p154672049599"></a>参数类型</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.1.4.1.3"><p id="p446713491196"><a name="p446713491196"></a><a name="p446713491196"></a>参数说明</p>
</th>
</tr>
</thead>
<tbody><tr id="row1946714918920"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.1.4.1.1 "><p id="p946734910918"><a name="p946734910918"></a><a name="p946734910918"></a>sites</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.1.4.1.2 "><p id="p114671491591"><a name="p114671491591"></a><a name="p114671491591"></a>Array&lt;<a href="js-params.md#s60f796f99e2a42589d569ce7de36a113">Site</a>&gt;</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.4.1.3 "><p id="p17467174911918"><a name="p17467174911918"></a><a name="p17467174911918"></a>如果查询成功，返回搜索结果。如果没有结果，返回空数组。</p>
<div class="caution" id="note546734917911"><a name="note546734917911"></a><a name="note546734917911"></a><span class="cautiontitle"> 注意： </span><div class="cautionbody"><p id="p134671949994"><a name="p134671949994"></a><a name="p134671949994"></a>Site对象不返回POI信息。</p>
</div></div>
</td>
</tr>
</tbody>
</table>

## SearchByIdRequest<a name="s07869d36847f4dcd8b38d5428c2cafd4"></a>

<a name="t407fb1fd1d674c5892fa62b9cc61166e"></a>
<table><thead align="left"><tr id="rf4409c9f969849a69642ed0d622e2431"><th class="cellrowborder" valign="top" width="20%" id="mcps1.1.5.1.1"><p id="a07ce6ef032d246bf94ebbaedc33b3b7d"><a name="a07ce6ef032d246bf94ebbaedc33b3b7d"></a><a name="a07ce6ef032d246bf94ebbaedc33b3b7d"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="14.000000000000002%" id="mcps1.1.5.1.2"><p id="a1962f903fb3e48fa92014fb8359774f6"><a name="a1962f903fb3e48fa92014fb8359774f6"></a><a name="a1962f903fb3e48fa92014fb8359774f6"></a>是否必选</p>
</th>
<th class="cellrowborder" valign="top" width="16%" id="mcps1.1.5.1.3"><p id="a9f5b3a7b6d874ef1ad45ab0897e75c10"><a name="a9f5b3a7b6d874ef1ad45ab0897e75c10"></a><a name="a9f5b3a7b6d874ef1ad45ab0897e75c10"></a>参数类型</p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.1.5.1.4"><p id="aee80743a95e84feda425e33e4186328f"><a name="aee80743a95e84feda425e33e4186328f"></a><a name="aee80743a95e84feda425e33e4186328f"></a>参数说明</p>
</th>
</tr>
</thead>
<tbody><tr id="rada343453eba41f1a9919dfe99bf964f"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.1.5.1.1 "><p id="a47a6d726d5b542229822dc6c643eb90e"><a name="a47a6d726d5b542229822dc6c643eb90e"></a><a name="a47a6d726d5b542229822dc6c643eb90e"></a>siteId</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="aedf9447eb3f34ca3876efba01562fbc5"><a name="aedf9447eb3f34ca3876efba01562fbc5"></a><a name="aedf9447eb3f34ca3876efba01562fbc5"></a>是</p>
</td>
<td class="cellrowborder" valign="top" width="16%" headers="mcps1.1.5.1.3 "><p id="acc2041c6ef77405a87fe3bce10f5fa57"><a name="acc2041c6ef77405a87fe3bce10f5fa57"></a><a name="acc2041c6ef77405a87fe3bce10f5fa57"></a>String(&lt;=256)</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="acff19594276f4bd196425f50a39928e1"><a name="acff19594276f4bd196425f50a39928e1"></a><a name="acff19594276f4bd196425f50a39928e1"></a>地点ID。</p>
</td>
</tr>
<tr id="r616adc319fb142758e7f711843afeefe"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.1.5.1.1 "><p id="a6c40df6cdcba4dbca0c97b5b00bf9289"><a name="a6c40df6cdcba4dbca0c97b5b00bf9289"></a><a name="a6c40df6cdcba4dbca0c97b5b00bf9289"></a>language</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="a1d460ca8fe1a40cba2dd64a25942c5e5"><a name="a1d460ca8fe1a40cba2dd64a25942c5e5"></a><a name="a1d460ca8fe1a40cba2dd64a25942c5e5"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="16%" headers="mcps1.1.5.1.3 "><p id="aabbe538ab7c0467fa82cce8604006332"><a name="aabbe538ab7c0467fa82cce8604006332"></a><a name="aabbe538ab7c0467fa82cce8604006332"></a>String(&lt;=6)</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="a39194c18ee5445a0b08500c79135d10f"><a name="a39194c18ee5445a0b08500c79135d10f"></a><a name="a39194c18ee5445a0b08500c79135d10f"></a>搜索结果的语种，语种取值请参见<a href="zh-cn_topic_0000001050162856.md">支持的语言</a>列表。如果不指定语种，返回地点的当地语言。</p>
</td>
</tr>
<tr id="r3deb447d974d4698a9cce72054fa7515"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.1.5.1.1 "><p id="a1457b3080d9342e1980df3fe286ed26c"><a name="a1457b3080d9342e1980df3fe286ed26c"></a><a name="a1457b3080d9342e1980df3fe286ed26c"></a>politicalView</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="af5d938a7a66a42d3a4335e82ba3b3ac4"><a name="af5d938a7a66a42d3a4335e82ba3b3ac4"></a><a name="af5d938a7a66a42d3a4335e82ba3b3ac4"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="16%" headers="mcps1.1.5.1.3 "><p id="ad8a32877f1df4f6fb489b0b51a18c0fa"><a name="ad8a32877f1df4f6fb489b0b51a18c0fa"></a><a name="ad8a32877f1df4f6fb489b0b51a18c0fa"></a>String(=2)</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="afa8b5d055cbd4a65b4f2517f0acf6481"><a name="afa8b5d055cbd4a65b4f2517f0acf6481"></a><a name="afa8b5d055cbd4a65b4f2517f0acf6481"></a>政治观点参数，采用ISO 3166-1 alpha-2规范的2位国家码。</p>
<div class="caution" id="note11401175411395"><a name="note11401175411395"></a><a name="note11401175411395"></a><span class="cautiontitle"> 注意： </span><div class="cautionbody"><p id="p44011554173911"><a name="p44011554173911"></a><a name="p44011554173911"></a>该参数已废弃。</p>
</div></div>
</td>
</tr>
</tbody>
</table>

## SearchByIdResult<a name="sc03caf032be04183a23bfa399b25594c"></a>

<a name="tba37003ca8d142b28fc80be1a7b23ab1"></a>
<table><thead align="left"><tr id="r8e2a3e9b475f4721bb2cd3219a075038"><th class="cellrowborder" valign="top" width="18%" id="mcps1.1.4.1.1"><p id="ad59bed14b2f24982b74f0a1d7c9ceae0"><a name="ad59bed14b2f24982b74f0a1d7c9ceae0"></a><a name="ad59bed14b2f24982b74f0a1d7c9ceae0"></a><strong id="a5e4136e8d3ba4fe29e8e7305681b1e5e"><a name="a5e4136e8d3ba4fe29e8e7305681b1e5e"></a><a name="a5e4136e8d3ba4fe29e8e7305681b1e5e"></a>参数</strong></p>
</th>
<th class="cellrowborder" valign="top" width="22%" id="mcps1.1.4.1.2"><p id="afe4a950a505d4046b3fe82a468eebc5b"><a name="afe4a950a505d4046b3fe82a468eebc5b"></a><a name="afe4a950a505d4046b3fe82a468eebc5b"></a><strong id="a21ddf474915d4945ac9c7178904f88dc"><a name="a21ddf474915d4945ac9c7178904f88dc"></a><a name="a21ddf474915d4945ac9c7178904f88dc"></a>参数类型</strong></p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.1.4.1.3"><p id="a1b2de141941f477db2a5c77a7ba044af"><a name="a1b2de141941f477db2a5c77a7ba044af"></a><a name="a1b2de141941f477db2a5c77a7ba044af"></a><strong id="a186e77701b674a1a98945f0c253c1738"><a name="a186e77701b674a1a98945f0c253c1738"></a><a name="a186e77701b674a1a98945f0c253c1738"></a>参数说明</strong></p>
</th>
</tr>
</thead>
<tbody><tr id="r1fccf2134b8445119590ec3a8e23d47a"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.4.1.1 "><p id="ac248e62bcd9244ed98f645aa2dede19e"><a name="ac248e62bcd9244ed98f645aa2dede19e"></a><a name="ac248e62bcd9244ed98f645aa2dede19e"></a>site</p>
</td>
<td class="cellrowborder" valign="top" width="22%" headers="mcps1.1.4.1.2 "><p id="a6219796096fd473aad8b59876a930505"><a name="a6219796096fd473aad8b59876a930505"></a><a name="a6219796096fd473aad8b59876a930505"></a><a href="js-params.md#s60f796f99e2a42589d569ce7de36a113">Site</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.4.1.3 "><p id="adadf0326dc3c4855813b878d2ad0802e"><a name="adadf0326dc3c4855813b878d2ad0802e"></a><a name="adadf0326dc3c4855813b878d2ad0802e"></a>如果查询成功，返回地点详情；如果错误，返会错误描述。</p>
</td>
</tr>
</tbody>
</table>

## SearchByTextRequest<a name="s0636d688325540bab4ba4311b4092d9d"></a>

<a name="t98796271719d44328a28f3bba4cddfb1"></a>
<table><thead align="left"><tr id="rc8972ac1f6c641a2b191d62d8a7582ab"><th class="cellrowborder" valign="top" width="17.82821717828217%" id="mcps1.1.5.1.1"><p id="a08600e12c3424065bf9e34524b59402b"><a name="a08600e12c3424065bf9e34524b59402b"></a><a name="a08600e12c3424065bf9e34524b59402b"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="13.998600139986003%" id="mcps1.1.5.1.2"><p id="a59aa30472b4144cf9eb001473e2c8a63"><a name="a59aa30472b4144cf9eb001473e2c8a63"></a><a name="a59aa30472b4144cf9eb001473e2c8a63"></a>是否必选</p>
</th>
<th class="cellrowborder" valign="top" width="20.97790220977902%" id="mcps1.1.5.1.3"><p id="a98bec22a3c024316a2eb667b2bc3dc02"><a name="a98bec22a3c024316a2eb667b2bc3dc02"></a><a name="a98bec22a3c024316a2eb667b2bc3dc02"></a>参数类型</p>
</th>
<th class="cellrowborder" valign="top" width="47.195280471952806%" id="mcps1.1.5.1.4"><p id="ae949b1d6017741a3861a36764e450029"><a name="ae949b1d6017741a3861a36764e450029"></a><a name="ae949b1d6017741a3861a36764e450029"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="ra1e4c02533c64c43a6d6636f3fe63395"><td class="cellrowborder" valign="top" width="17.82821717828217%" headers="mcps1.1.5.1.1 "><p id="aa24b10da96b24255bf45cbd10e13934c"><a name="aa24b10da96b24255bf45cbd10e13934c"></a><a name="aa24b10da96b24255bf45cbd10e13934c"></a>query</p>
</td>
<td class="cellrowborder" valign="top" width="13.998600139986003%" headers="mcps1.1.5.1.2 "><p id="a12cfea4c2ad54f569756849e8ea75557"><a name="a12cfea4c2ad54f569756849e8ea75557"></a><a name="a12cfea4c2ad54f569756849e8ea75557"></a>是</p>
</td>
<td class="cellrowborder" valign="top" width="20.97790220977902%" headers="mcps1.1.5.1.3 "><p id="a02fb646d87bf496cb5cebfe721e906e5"><a name="a02fb646d87bf496cb5cebfe721e906e5"></a><a name="a02fb646d87bf496cb5cebfe721e906e5"></a>String(&lt;=512)</p>
</td>
<td class="cellrowborder" valign="top" width="47.195280471952806%" headers="mcps1.1.5.1.4 "><p id="a718ebfc24a324b58b8205f6eb22e3f5d"><a name="a718ebfc24a324b58b8205f6eb22e3f5d"></a><a name="a718ebfc24a324b58b8205f6eb22e3f5d"></a>搜索关键字。</p>
</td>
</tr>
<tr id="rdce6f57210a9407c84b1d12ec5c3f3ad"><td class="cellrowborder" valign="top" width="17.82821717828217%" headers="mcps1.1.5.1.1 "><p id="a41257c9a3cc843c6bf31d6b1534a4d72"><a name="a41257c9a3cc843c6bf31d6b1534a4d72"></a><a name="a41257c9a3cc843c6bf31d6b1534a4d72"></a>location</p>
</td>
<td class="cellrowborder" valign="top" width="13.998600139986003%" headers="mcps1.1.5.1.2 "><p id="a0c29dc2c121040058c11ba78f4883488"><a name="a0c29dc2c121040058c11ba78f4883488"></a><a name="a0c29dc2c121040058c11ba78f4883488"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="20.97790220977902%" headers="mcps1.1.5.1.3 "><p id="aa60e5c339a314e2ba513d1e7739aba61"><a name="aa60e5c339a314e2ba513d1e7739aba61"></a><a name="aa60e5c339a314e2ba513d1e7739aba61"></a><a href="js-params.md#s45373a8938e040ca9f46c78f4283b385">LatLng</a></p>
</td>
<td class="cellrowborder" valign="top" width="47.195280471952806%" headers="mcps1.1.5.1.4 "><p id="a8a764fb3c7864aa28f15f8975da64ece"><a name="a8a764fb3c7864aa28f15f8975da64ece"></a><a name="a8a764fb3c7864aa28f15f8975da64ece"></a>搜索结果偏向的经纬度。</p>
</td>
</tr>
<tr id="r8d2c4aacc7114cf9aab7de942b1d1cb3"><td class="cellrowborder" valign="top" width="17.82821717828217%" headers="mcps1.1.5.1.1 "><p id="afe2b688286d84179b22f12efff3207bb"><a name="afe2b688286d84179b22f12efff3207bb"></a><a name="afe2b688286d84179b22f12efff3207bb"></a>radius</p>
</td>
<td class="cellrowborder" valign="top" width="13.998600139986003%" headers="mcps1.1.5.1.2 "><p id="a47756aab0e0246c39e696c8c6b538472"><a name="a47756aab0e0246c39e696c8c6b538472"></a><a name="a47756aab0e0246c39e696c8c6b538472"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="20.97790220977902%" headers="mcps1.1.5.1.3 "><p id="a3dd9c9a607764a4cb7708d7bd207409a"><a name="a3dd9c9a607764a4cb7708d7bd207409a"></a><a name="a3dd9c9a607764a4cb7708d7bd207409a"></a>Number</p>
</td>
<td class="cellrowborder" valign="top" width="47.195280471952806%" headers="mcps1.1.5.1.4 "><p id="a76daeb4d22ed460b8030cdd8beb386ca"><a name="a76daeb4d22ed460b8030cdd8beb386ca"></a><a name="a76daeb4d22ed460b8030cdd8beb386ca"></a>Location的搜索半径，单位：米。</p>
<p id="ab32416025aae488d92de8f5956c228c9"><a name="ab32416025aae488d92de8f5956c228c9"></a><a name="ab32416025aae488d92de8f5956c228c9"></a>取值范围：[1, 50000]，默认50000米。</p>
</td>
</tr>
<tr id="r8ff3664de12940f5b307a8c497824913"><td class="cellrowborder" valign="top" width="17.82821717828217%" headers="mcps1.1.5.1.1 "><p id="a99b768cf0ccc4b319d8711531c060167"><a name="a99b768cf0ccc4b319d8711531c060167"></a><a name="a99b768cf0ccc4b319d8711531c060167"></a>poiType</p>
</td>
<td class="cellrowborder" valign="top" width="13.998600139986003%" headers="mcps1.1.5.1.2 "><p id="a93413936cfc345bc8a36411e4fb6b9f6"><a name="a93413936cfc345bc8a36411e4fb6b9f6"></a><a name="a93413936cfc345bc8a36411e4fb6b9f6"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="20.97790220977902%" headers="mcps1.1.5.1.3 "><p id="a97ed90d748b5410e85662f975c54b3f7"><a name="a97ed90d748b5410e85662f975c54b3f7"></a><a name="a97ed90d748b5410e85662f975c54b3f7"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="47.195280471952806%" headers="mcps1.1.5.1.4 "><p id="aa6497a9b147848bf8612969eaf18c83c"><a name="aa6497a9b147848bf8612969eaf18c83c"></a><a name="aa6497a9b147848bf8612969eaf18c83c"></a>返回指定POI类型的地点。</p>
</td>
</tr>
<tr id="r96b6922eb3cd4bb8b4b4663d9a81db71"><td class="cellrowborder" valign="top" width="17.82821717828217%" headers="mcps1.1.5.1.1 "><p id="a4e62a8a6f64540178a2b43fe1d4af7c4"><a name="a4e62a8a6f64540178a2b43fe1d4af7c4"></a><a name="a4e62a8a6f64540178a2b43fe1d4af7c4"></a>countryCode</p>
</td>
<td class="cellrowborder" valign="top" width="13.998600139986003%" headers="mcps1.1.5.1.2 "><p id="a475d190459c945c297ce0f8d4d7ba195"><a name="a475d190459c945c297ce0f8d4d7ba195"></a><a name="a475d190459c945c297ce0f8d4d7ba195"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="20.97790220977902%" headers="mcps1.1.5.1.3 "><p id="ac8c93266ea2f41bb9861e50fa1b4c610"><a name="ac8c93266ea2f41bb9861e50fa1b4c610"></a><a name="ac8c93266ea2f41bb9861e50fa1b4c610"></a>String(=2)</p>
</td>
<td class="cellrowborder" valign="top" width="47.195280471952806%" headers="mcps1.1.5.1.4 "><p id="a0aa3540a04844985adf759ea4c976316"><a name="a0aa3540a04844985adf759ea4c976316"></a><a name="a0aa3540a04844985adf759ea4c976316"></a>在指定的国家内搜索，采用ISO 3166-1 alpha-2规范的2位国家码。</p>
</td>
</tr>
<tr id="rb80640e472954c549d672d965fa4070d"><td class="cellrowborder" valign="top" width="17.82821717828217%" headers="mcps1.1.5.1.1 "><p id="a239920a10e3d44dd84d14f59d4e3eedf"><a name="a239920a10e3d44dd84d14f59d4e3eedf"></a><a name="a239920a10e3d44dd84d14f59d4e3eedf"></a>language</p>
</td>
<td class="cellrowborder" valign="top" width="13.998600139986003%" headers="mcps1.1.5.1.2 "><p id="affba583bf5bb44a189a4617695a6ee45"><a name="affba583bf5bb44a189a4617695a6ee45"></a><a name="affba583bf5bb44a189a4617695a6ee45"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="20.97790220977902%" headers="mcps1.1.5.1.3 "><p id="a13d469cd55174fbc89b2b8f0bebf50d2"><a name="a13d469cd55174fbc89b2b8f0bebf50d2"></a><a name="a13d469cd55174fbc89b2b8f0bebf50d2"></a>String(&lt;=6)</p>
</td>
<td class="cellrowborder" valign="top" width="47.195280471952806%" headers="mcps1.1.5.1.4 "><p id="aaec9e221eda04df4b6fa2939d5158c7a"><a name="aaec9e221eda04df4b6fa2939d5158c7a"></a><a name="aaec9e221eda04df4b6fa2939d5158c7a"></a>搜索结果的语种，语种取值请参见<a href="zh-cn_topic_0000001050162856.md">支持的语言</a>列表。如果不指定语种，返回地点的当地语言。</p>
</td>
</tr>
<tr id="r4261abb6e28147a18d88cc4855835ab1"><td class="cellrowborder" valign="top" width="17.82821717828217%" headers="mcps1.1.5.1.1 "><p id="a372b370b03334eb1814cf69bd4e80d5a"><a name="a372b370b03334eb1814cf69bd4e80d5a"></a><a name="a372b370b03334eb1814cf69bd4e80d5a"></a>pageSize</p>
</td>
<td class="cellrowborder" valign="top" width="13.998600139986003%" headers="mcps1.1.5.1.2 "><p id="a58aa4067ff1f425f8a88f3828c422bd3"><a name="a58aa4067ff1f425f8a88f3828c422bd3"></a><a name="a58aa4067ff1f425f8a88f3828c422bd3"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="20.97790220977902%" headers="mcps1.1.5.1.3 "><p id="a3adde6db22c049f98841e3ded20e7399"><a name="a3adde6db22c049f98841e3ded20e7399"></a><a name="a3adde6db22c049f98841e3ded20e7399"></a>Number</p>
</td>
<td class="cellrowborder" valign="top" width="47.195280471952806%" headers="mcps1.1.5.1.4 "><p id="a90e87159757540538fcc50d72b437dc6"><a name="a90e87159757540538fcc50d72b437dc6"></a><a name="a90e87159757540538fcc50d72b437dc6"></a>每页返回的记录数。</p>
<p id="aecdbeffe12884e1cab5deafdb437047b"><a name="aecdbeffe12884e1cab5deafdb437047b"></a><a name="aecdbeffe12884e1cab5deafdb437047b"></a>取值范围：[1, 20]，默认20。</p>
</td>
</tr>
<tr id="re91198f81bb14979a64a1ec2a5cad32f"><td class="cellrowborder" valign="top" width="17.82821717828217%" headers="mcps1.1.5.1.1 "><p id="aafef4c092fc745ebb2f2b92c78c786a5"><a name="aafef4c092fc745ebb2f2b92c78c786a5"></a><a name="aafef4c092fc745ebb2f2b92c78c786a5"></a>pageIndex</p>
</td>
<td class="cellrowborder" valign="top" width="13.998600139986003%" headers="mcps1.1.5.1.2 "><p id="ad6a82d284d2a4a96b78b238245919beb"><a name="ad6a82d284d2a4a96b78b238245919beb"></a><a name="ad6a82d284d2a4a96b78b238245919beb"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="20.97790220977902%" headers="mcps1.1.5.1.3 "><p id="a25a9abd978584958bf396b1180299510"><a name="a25a9abd978584958bf396b1180299510"></a><a name="a25a9abd978584958bf396b1180299510"></a>Number</p>
</td>
<td class="cellrowborder" valign="top" width="47.195280471952806%" headers="mcps1.1.5.1.4 "><p id="ab8b27620431a4cc99bd9268063186b2e"><a name="ab8b27620431a4cc99bd9268063186b2e"></a><a name="ab8b27620431a4cc99bd9268063186b2e"></a>当前页数。</p>
<p id="a373ed009299047159c32d777736864b3"><a name="a373ed009299047159c32d777736864b3"></a><a name="a373ed009299047159c32d777736864b3"></a>取值范围：[1, 60]，默认1。</p>
<p id="a70a87ae1c71441d68b16e2683eb08caa"><a name="a70a87ae1c71441d68b16e2683eb08caa"></a><a name="a70a87ae1c71441d68b16e2683eb08caa"></a>约束：pageindex*pagesize &lt;= 60。</p>
</td>
</tr>
<tr id="row10271173610186"><td class="cellrowborder" valign="top" width="17.82821717828217%" headers="mcps1.1.5.1.1 "><p id="p1751938171811"><a name="p1751938171811"></a><a name="p1751938171811"></a>countries</p>
</td>
<td class="cellrowborder" valign="top" width="13.998600139986003%" headers="mcps1.1.5.1.2 "><p id="p57563810186"><a name="p57563810186"></a><a name="p57563810186"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="20.97790220977902%" headers="mcps1.1.5.1.3 "><p id="p9751438131818"><a name="p9751438131818"></a><a name="p9751438131818"></a>Array&lt;String(=2)&gt;</p>
</td>
<td class="cellrowborder" valign="top" width="47.195280471952806%" headers="mcps1.1.5.1.4 "><p id="p37553831814"><a name="p37553831814"></a><a name="p37553831814"></a>多个国家码，采用ISO 3166-1 alpha-2规范的2位国家码。</p>
</td>
</tr>
<tr id="rd2750a8f3e4649eda7793ada08d97f1e"><td class="cellrowborder" valign="top" width="17.82821717828217%" headers="mcps1.1.5.1.1 "><p id="a929b1819d2424de59fae0f8bec91b90e"><a name="a929b1819d2424de59fae0f8bec91b90e"></a><a name="a929b1819d2424de59fae0f8bec91b90e"></a>politicalView</p>
</td>
<td class="cellrowborder" valign="top" width="13.998600139986003%" headers="mcps1.1.5.1.2 "><p id="ab47a24ca72ed4de48d784ba44da236ec"><a name="ab47a24ca72ed4de48d784ba44da236ec"></a><a name="ab47a24ca72ed4de48d784ba44da236ec"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="20.97790220977902%" headers="mcps1.1.5.1.3 "><p id="a5badb10050b144a19058fccce791b0ad"><a name="a5badb10050b144a19058fccce791b0ad"></a><a name="a5badb10050b144a19058fccce791b0ad"></a>String(=2)</p>
</td>
<td class="cellrowborder" valign="top" width="47.195280471952806%" headers="mcps1.1.5.1.4 "><p id="a4d279c0662fa4a5cb4301f504c53e6e3"><a name="a4d279c0662fa4a5cb4301f504c53e6e3"></a><a name="a4d279c0662fa4a5cb4301f504c53e6e3"></a>政治观点参数，采用ISO 3166-1 alpha-2规范的2位国家码。</p>
<div class="caution" id="note191789616402"><a name="note191789616402"></a><a name="note191789616402"></a><span class="cautiontitle"> 注意： </span><div class="cautionbody"><p id="p11784654012"><a name="p11784654012"></a><a name="p11784654012"></a>该参数已废弃。</p>
</div></div>
</td>
</tr>
</tbody>
</table>

## SearchByTextResult<a name="s61d75014a6c144bbbe67f6e830579f67"></a>

<a name="t64a32ab7535d44dd9fccb079a2431761"></a>
<table><thead align="left"><tr id="r3fea21246d1547499389394b30656c7b"><th class="cellrowborder" valign="top" width="18.18%" id="mcps1.1.4.1.1"><p id="af6078ca9e7e549538774806084388da4"><a name="af6078ca9e7e549538774806084388da4"></a><a name="af6078ca9e7e549538774806084388da4"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="22.220000000000002%" id="mcps1.1.4.1.2"><p id="af5e96464380844b585fff70284ba7a21"><a name="af5e96464380844b585fff70284ba7a21"></a><a name="af5e96464380844b585fff70284ba7a21"></a>参数类型</p>
</th>
<th class="cellrowborder" valign="top" width="59.599999999999994%" id="mcps1.1.4.1.3"><p id="a8425d019b07c41f1aeb6ab78d3891ff3"><a name="a8425d019b07c41f1aeb6ab78d3891ff3"></a><a name="a8425d019b07c41f1aeb6ab78d3891ff3"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="r83fb28852df845e5a370a5c6e3e5ea72"><td class="cellrowborder" valign="top" width="18.18%" headers="mcps1.1.4.1.1 "><p id="aeccc75e98076494c93d5fee420e64573"><a name="aeccc75e98076494c93d5fee420e64573"></a><a name="aeccc75e98076494c93d5fee420e64573"></a>totalCount</p>
</td>
<td class="cellrowborder" valign="top" width="22.220000000000002%" headers="mcps1.1.4.1.2 "><p id="a8598286873d64f28be0f7e4d09e5e651"><a name="a8598286873d64f28be0f7e4d09e5e651"></a><a name="a8598286873d64f28be0f7e4d09e5e651"></a>int</p>
</td>
<td class="cellrowborder" valign="top" width="59.599999999999994%" headers="mcps1.1.4.1.3 "><p id="a81f5714b4592427ab7d977e71bc785a4"><a name="a81f5714b4592427ab7d977e71bc785a4"></a><a name="a81f5714b4592427ab7d977e71bc785a4"></a>如果查询成功，返回记录总数。如果没有结果，返回0。</p>
</td>
</tr>
<tr id="rb3b817e3664842618fcb083fd33c6fcb"><td class="cellrowborder" valign="top" width="18.18%" headers="mcps1.1.4.1.1 "><p id="a6a6fe963af8347eb910e1c8267a6fdf0"><a name="a6a6fe963af8347eb910e1c8267a6fdf0"></a><a name="a6a6fe963af8347eb910e1c8267a6fdf0"></a>sites</p>
</td>
<td class="cellrowborder" valign="top" width="22.220000000000002%" headers="mcps1.1.4.1.2 "><p id="ab9dfe9d34076433cbb1a63f0d6c66649"><a name="ab9dfe9d34076433cbb1a63f0d6c66649"></a><a name="ab9dfe9d34076433cbb1a63f0d6c66649"></a>Array&lt;<a href="js-params.md#s60f796f99e2a42589d569ce7de36a113">Site</a>&gt;</p>
</td>
<td class="cellrowborder" valign="top" width="59.599999999999994%" headers="mcps1.1.4.1.3 "><p id="ad08410aed7e2438f9c5ce544d1f0d3ec"><a name="ad08410aed7e2438f9c5ce544d1f0d3ec"></a><a name="ad08410aed7e2438f9c5ce544d1f0d3ec"></a>如果查询成功，返回搜索结果。如果没有结果，返回空数组。</p>
</td>
</tr>
</tbody>
</table>

