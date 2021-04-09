# HWMarkerCluster<a name="ZH-CN_TOPIC_0000001145860959"></a>

-   [概览](#s9ff17b3b14934e499e60389ea924156a)
-   [构造方法](#s3d61b02daf28471ebef955f06f7f52b3)
-   [公共方法](#sd4fe6740c35045b6a8c0b4f6388300c8)
-   [MarkerClusterOptions](#s82c155f3c105429ebcac6bf4c9989a5b)

## 概览<a name="s9ff17b3b14934e499e60389ea924156a"></a>

用来聚合地图上指定的Marker集合，能设定聚合距离以及聚合后显示的图片。

## 构造方法<a name="s3d61b02daf28471ebef955f06f7f52b3"></a>

<a name="tb049cbfe60a74275a5da8f19d9e67067"></a>
<table><thead align="left"><tr id="r84422b2d63e14330a488d32379d0ae2a"><th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.1"><p id="a45b4c6a78d3446bca47682b50b5bc019"><a name="a45b4c6a78d3446bca47682b50b5bc019"></a><a name="a45b4c6a78d3446bca47682b50b5bc019"></a><strong id="a8857ad37069b462a8cea4df6e8dedfa4"><a name="a8857ad37069b462a8cea4df6e8dedfa4"></a><a name="a8857ad37069b462a8cea4df6e8dedfa4"></a>构造方法</strong></p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.2"><p id="a9466768f184640bdb373ee0c458f8683"><a name="a9466768f184640bdb373ee0c458f8683"></a><a name="a9466768f184640bdb373ee0c458f8683"></a><strong id="ab1bde405cfc84c7cbf815aee50f3183e"><a name="ab1bde405cfc84c7cbf815aee50f3183e"></a><a name="ab1bde405cfc84c7cbf815aee50f3183e"></a>描述</strong></p>
</th>
</tr>
</thead>
<tbody><tr id="r3613ab88b7db402a8f69d077cd11cabe"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="a7d181b449d3144dd8e8fa0e1afb850cf"><a name="a7d181b449d3144dd8e8fa0e1afb850cf"></a><a name="a7d181b449d3144dd8e8fa0e1afb850cf"></a>HWMapJsSDK.HWMarkerCluster(map, markers, options)</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><a name="u22809d85f7044feaa216eb06fdee6987"></a><a name="u22809d85f7044feaa216eb06fdee6987"></a><ul id="u22809d85f7044feaa216eb06fdee6987"><li>map：添加的地图图层，必选项。</li><li>markers：要被聚合的<a href="js-hwmarker.md">HWMarker</a>集合，必选项。</li><li>options：<a href="js-hwmarkercluster.md">HWMarkerCluster</a>的属性，详情见<a href="#s82c155f3c105429ebcac6bf4c9989a5b">MarkerClusterOptions</a>。</li></ul>
</td>
</tr>
</tbody>
</table>

## 公共方法<a name="sd4fe6740c35045b6a8c0b4f6388300c8"></a>

<a name="t5a054a0c1a0c4d3083311b04a68e4adb"></a>
<table><thead align="left"><tr id="rdf0d42d2b6ec4372ab7a03d60ef64eae"><th class="cellrowborder" valign="top" width="33%" id="mcps1.1.5.1.1"><p id="a299e4b89174f432888c01a35a13a8ba4"><a name="a299e4b89174f432888c01a35a13a8ba4"></a><a name="a299e4b89174f432888c01a35a13a8ba4"></a><strong id="acfbc0c781f1340049b1f9cf66c12718e"><a name="acfbc0c781f1340049b1f9cf66c12718e"></a><a name="acfbc0c781f1340049b1f9cf66c12718e"></a>方法</strong></p>
</th>
<th class="cellrowborder" valign="top" width="26%" id="mcps1.1.5.1.2"><p id="afb9381d2aabf406bac8a7bda48b58b3a"><a name="afb9381d2aabf406bac8a7bda48b58b3a"></a><a name="afb9381d2aabf406bac8a7bda48b58b3a"></a><strong id="ae769cfc32a2341f2bf2460eab56dfff7"><a name="ae769cfc32a2341f2bf2460eab56dfff7"></a><a name="ae769cfc32a2341f2bf2460eab56dfff7"></a>描述</strong></p>
</th>
<th class="cellrowborder" valign="top" width="26.08%" id="mcps1.1.5.1.3"><p id="acfd17e4ee9374561b69772e6b96c22e4"><a name="acfd17e4ee9374561b69772e6b96c22e4"></a><a name="acfd17e4ee9374561b69772e6b96c22e4"></a><strong id="af4bfeba55ea24d03bd6546ae6abf7e89"><a name="af4bfeba55ea24d03bd6546ae6abf7e89"></a><a name="af4bfeba55ea24d03bd6546ae6abf7e89"></a>参数类型</strong></p>
</th>
<th class="cellrowborder" valign="top" width="14.92%" id="mcps1.1.5.1.4"><p id="a68f77259e6c244aaa33b8a55e74fda83"><a name="a68f77259e6c244aaa33b8a55e74fda83"></a><a name="a68f77259e6c244aaa33b8a55e74fda83"></a><strong id="a622adaa788d24eeca172909c02004980"><a name="a622adaa788d24eeca172909c02004980"></a><a name="a622adaa788d24eeca172909c02004980"></a>返回值</strong></p>
</th>
</tr>
</thead>
<tbody><tr id="r35dcefd4ccf6460c814195b71f88d34b"><td class="cellrowborder" valign="top" width="33%" headers="mcps1.1.5.1.1 "><p id="a8241ea21360843c690db4b2ee929e778"><a name="a8241ea21360843c690db4b2ee929e778"></a><a name="a8241ea21360843c690db4b2ee929e778"></a>addMarker(marker)</p>
</td>
<td class="cellrowborder" valign="top" width="26%" headers="mcps1.1.5.1.2 "><p id="a34708502ded541428d495c706439ab53"><a name="a34708502ded541428d495c706439ab53"></a><a name="a34708502ded541428d495c706439ab53"></a>添加<a href="js-hwmarker.md">HWMarker</a>。</p>
</td>
<td class="cellrowborder" valign="top" width="26.08%" headers="mcps1.1.5.1.3 "><p id="a24373b735bb64eeda0b58481e4856858"><a name="a24373b735bb64eeda0b58481e4856858"></a><a name="a24373b735bb64eeda0b58481e4856858"></a><a href="js-hwmarker.md">HWMarker</a></p>
</td>
<td class="cellrowborder" valign="top" width="14.92%" headers="mcps1.1.5.1.4 "><p id="ab6946ca6d2ee48cc827c74788b25a880"><a name="ab6946ca6d2ee48cc827c74788b25a880"></a><a name="ab6946ca6d2ee48cc827c74788b25a880"></a>-</p>
</td>
</tr>
<tr id="rdb47ef485f96451d9d071650480c3b9e"><td class="cellrowborder" valign="top" width="33%" headers="mcps1.1.5.1.1 "><p id="aee3d9026108347ebb63cb6d22dca4636"><a name="aee3d9026108347ebb63cb6d22dca4636"></a><a name="aee3d9026108347ebb63cb6d22dca4636"></a>addMarkers(markers)</p>
</td>
<td class="cellrowborder" valign="top" width="26%" headers="mcps1.1.5.1.2 "><p id="afa0ee6a66f0b49cc94e5fe536fad147f"><a name="afa0ee6a66f0b49cc94e5fe536fad147f"></a><a name="afa0ee6a66f0b49cc94e5fe536fad147f"></a>添加<a href="js-hwmarker.md">HWMarker</a>集合。</p>
</td>
<td class="cellrowborder" valign="top" width="26.08%" headers="mcps1.1.5.1.3 "><p id="a7c06b166469d4bd5a8ea50acbe663a92"><a name="a7c06b166469d4bd5a8ea50acbe663a92"></a><a name="a7c06b166469d4bd5a8ea50acbe663a92"></a>Array&lt;<a href="js-hwmarker.md">HWMarker</a>&gt;</p>
</td>
<td class="cellrowborder" valign="top" width="14.92%" headers="mcps1.1.5.1.4 "><p id="a2a47fd9a5d77480cb7280d8de58c407b"><a name="a2a47fd9a5d77480cb7280d8de58c407b"></a><a name="a2a47fd9a5d77480cb7280d8de58c407b"></a>-</p>
</td>
</tr>
<tr id="r187d5670dde24203bedcee9527839939"><td class="cellrowborder" valign="top" width="33%" headers="mcps1.1.5.1.1 "><p id="a7289c5f505634b8cae26606c2aff51d2"><a name="a7289c5f505634b8cae26606c2aff51d2"></a><a name="a7289c5f505634b8cae26606c2aff51d2"></a>removeMarker(marker)</p>
</td>
<td class="cellrowborder" valign="top" width="26%" headers="mcps1.1.5.1.2 "><p id="ab76906cf235646359744b0ef342d6d2b"><a name="ab76906cf235646359744b0ef342d6d2b"></a><a name="ab76906cf235646359744b0ef342d6d2b"></a>删除<a href="js-hwmarker.md">HWMarker</a>。</p>
</td>
<td class="cellrowborder" valign="top" width="26.08%" headers="mcps1.1.5.1.3 "><p id="a4baf1d4382da4da2ae9dc1da7a118551"><a name="a4baf1d4382da4da2ae9dc1da7a118551"></a><a name="a4baf1d4382da4da2ae9dc1da7a118551"></a><a href="js-hwmarker.md">HWMarker</a></p>
</td>
<td class="cellrowborder" valign="top" width="14.92%" headers="mcps1.1.5.1.4 "><p id="ac91632b74cee4ec49047fd3d4d38648a"><a name="ac91632b74cee4ec49047fd3d4d38648a"></a><a name="ac91632b74cee4ec49047fd3d4d38648a"></a>-</p>
</td>
</tr>
<tr id="r36efe689450746fe8763e04451baa6df"><td class="cellrowborder" valign="top" width="33%" headers="mcps1.1.5.1.1 "><p id="aad9cc03e8b904570b15489e4910a4767"><a name="aad9cc03e8b904570b15489e4910a4767"></a><a name="aad9cc03e8b904570b15489e4910a4767"></a>removeMarkers(markers)</p>
</td>
<td class="cellrowborder" valign="top" width="26%" headers="mcps1.1.5.1.2 "><p id="a66095244f7aa44debb9adb58b8faf212"><a name="a66095244f7aa44debb9adb58b8faf212"></a><a name="a66095244f7aa44debb9adb58b8faf212"></a>删除<a href="js-hwmarker.md">HWMarker</a>集合。</p>
</td>
<td class="cellrowborder" valign="top" width="26.08%" headers="mcps1.1.5.1.3 "><p id="ae38ba2b8dcfb4aafa887bbb2aa87fdf0"><a name="ae38ba2b8dcfb4aafa887bbb2aa87fdf0"></a><a name="ae38ba2b8dcfb4aafa887bbb2aa87fdf0"></a>Array&lt;<a href="js-hwmarker.md">HWMarker</a>&gt;</p>
</td>
<td class="cellrowborder" valign="top" width="14.92%" headers="mcps1.1.5.1.4 "><p id="a4c3faa806a1f4ffe92fc339d7ea93cc9"><a name="a4c3faa806a1f4ffe92fc339d7ea93cc9"></a><a name="a4c3faa806a1f4ffe92fc339d7ea93cc9"></a>-</p>
</td>
</tr>
<tr id="raea92d5c055e4223942d075022bf2f75"><td class="cellrowborder" valign="top" width="33%" headers="mcps1.1.5.1.1 "><p id="a460148ec7a2c41cb8473dd6a22293d34"><a name="a460148ec7a2c41cb8473dd6a22293d34"></a><a name="a460148ec7a2c41cb8473dd6a22293d34"></a>clearMarkers()</p>
</td>
<td class="cellrowborder" valign="top" width="26%" headers="mcps1.1.5.1.2 "><p id="a119dec5fb0474f089b63e5d7fc4e9ad7"><a name="a119dec5fb0474f089b63e5d7fc4e9ad7"></a><a name="a119dec5fb0474f089b63e5d7fc4e9ad7"></a>清除全部<a href="js-hwmarker.md">HWMarker</a>。</p>
</td>
<td class="cellrowborder" valign="top" width="26.08%" headers="mcps1.1.5.1.3 "><p id="a1aec91f68093449d92ff6e3a90ae5797"><a name="a1aec91f68093449d92ff6e3a90ae5797"></a><a name="a1aec91f68093449d92ff6e3a90ae5797"></a>-</p>
</td>
<td class="cellrowborder" valign="top" width="14.92%" headers="mcps1.1.5.1.4 "><p id="a975c067a801a4db8b5deb537a790f889"><a name="a975c067a801a4db8b5deb537a790f889"></a><a name="a975c067a801a4db8b5deb537a790f889"></a>-</p>
</td>
</tr>
<tr id="rd5190e6c5f714082b7ad6ac680cff346"><td class="cellrowborder" valign="top" width="33%" headers="mcps1.1.5.1.1 "><p id="a326adb109e0c492aa202d59bc798a5fe"><a name="a326adb109e0c492aa202d59bc798a5fe"></a><a name="a326adb109e0c492aa202d59bc798a5fe"></a>getMarkers()</p>
</td>
<td class="cellrowborder" valign="top" width="26%" headers="mcps1.1.5.1.2 "><p id="a229c28069b2f415eb6bd79c58aa41294"><a name="a229c28069b2f415eb6bd79c58aa41294"></a><a name="a229c28069b2f415eb6bd79c58aa41294"></a>获取所有的<a href="js-hwmarker.md">HWMarker</a>。</p>
</td>
<td class="cellrowborder" valign="top" width="26.08%" headers="mcps1.1.5.1.3 "><p id="a5fd3151b16544bbf838f5f4eed578a54"><a name="a5fd3151b16544bbf838f5f4eed578a54"></a><a name="a5fd3151b16544bbf838f5f4eed578a54"></a>-</p>
</td>
<td class="cellrowborder" valign="top" width="14.92%" headers="mcps1.1.5.1.4 "><p id="a6932779c60514ed48c137305434d212d"><a name="a6932779c60514ed48c137305434d212d"></a><a name="a6932779c60514ed48c137305434d212d"></a>Array&lt;<a href="js-hwmarker.md">HWMarker</a>&gt;</p>
</td>
</tr>
</tbody>
</table>

## MarkerClusterOptions<a name="s82c155f3c105429ebcac6bf4c9989a5b"></a>

<a name="tfb8ed312727847f0841608f4af58d88c"></a>
<table><thead align="left"><tr id="rdf91d8f6be5e4c4fb39c7422fcb5e92f"><th class="cellrowborder" valign="top" width="18.86%" id="mcps1.1.5.1.1"><p id="aaae51ff7ced9421484e531b78091eb20"><a name="aaae51ff7ced9421484e531b78091eb20"></a><a name="aaae51ff7ced9421484e531b78091eb20"></a><strong id="a3d1d76a17c7e43ef87e296accb14c2d9"><a name="a3d1d76a17c7e43ef87e296accb14c2d9"></a><a name="a3d1d76a17c7e43ef87e296accb14c2d9"></a>参数</strong></p>
</th>
<th class="cellrowborder" valign="top" width="14.000000000000002%" id="mcps1.1.5.1.2"><p id="aff159010952549068efdd2235ee7cb93"><a name="aff159010952549068efdd2235ee7cb93"></a><a name="aff159010952549068efdd2235ee7cb93"></a><strong id="a2207dc3307474368bc0c1fce28106004"><a name="a2207dc3307474368bc0c1fce28106004"></a><a name="a2207dc3307474368bc0c1fce28106004"></a>是否必选</strong></p>
</th>
<th class="cellrowborder" valign="top" width="21.54%" id="mcps1.1.5.1.3"><p id="ae81108032af04661bb00dfd781620d90"><a name="ae81108032af04661bb00dfd781620d90"></a><a name="ae81108032af04661bb00dfd781620d90"></a><strong id="a5c371f4d050c42d29a42cd7e568bbd64"><a name="a5c371f4d050c42d29a42cd7e568bbd64"></a><a name="a5c371f4d050c42d29a42cd7e568bbd64"></a>参数类型</strong></p>
</th>
<th class="cellrowborder" valign="top" width="45.6%" id="mcps1.1.5.1.4"><p id="abb51f5f31e964577b1dd669ec00f38eb"><a name="abb51f5f31e964577b1dd669ec00f38eb"></a><a name="abb51f5f31e964577b1dd669ec00f38eb"></a><strong id="a9d733c93f8e447cba36760cae5724cd2"><a name="a9d733c93f8e447cba36760cae5724cd2"></a><a name="a9d733c93f8e447cba36760cae5724cd2"></a>描述</strong></p>
</th>
</tr>
</thead>
<tbody><tr id="r47df51005fe94d3e8082b881f91f6203"><td class="cellrowborder" valign="top" width="18.86%" headers="mcps1.1.5.1.1 "><p id="ac4d2bc2f76ef4b31abd961be7491c0c9"><a name="ac4d2bc2f76ef4b31abd961be7491c0c9"></a><a name="ac4d2bc2f76ef4b31abd961be7491c0c9"></a>options.icon</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="a817f3621a2274bcc8e525174cee794fa"><a name="a817f3621a2274bcc8e525174cee794fa"></a><a name="a817f3621a2274bcc8e525174cee794fa"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="21.54%" headers="mcps1.1.5.1.3 "><p id="a2773f03004cd4075993c67ba7e028dbb"><a name="a2773f03004cd4075993c67ba7e028dbb"></a><a name="a2773f03004cd4075993c67ba7e028dbb"></a>String | <a href="js-hwmarker.md#s45d84da191d34eb09832e54692ca0908">MarkerIconOption</a></p>
</td>
<td class="cellrowborder" valign="top" width="45.6%" headers="mcps1.1.5.1.4 "><p id="a38f1646a0d0c4d25be125b25476a976c"><a name="a38f1646a0d0c4d25be125b25476a976c"></a><a name="a38f1646a0d0c4d25be125b25476a976c"></a><a href="js-hwmarker.md">HWMarker</a>聚合后显示的图标，同<a href="js-hwmarker.md">HWMarker</a>的设置。</p>
</td>
</tr>
<tr id="r709aae5be34e442cacc9c83bb23a1bc3"><td class="cellrowborder" valign="top" width="18.86%" headers="mcps1.1.5.1.1 "><p id="ac6aa0c372f7247f09ca1eb02781b1751"><a name="ac6aa0c372f7247f09ca1eb02781b1751"></a><a name="ac6aa0c372f7247f09ca1eb02781b1751"></a>options.label</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="adfe6ee126f4f49b78ad6a0bba125d001"><a name="adfe6ee126f4f49b78ad6a0bba125d001"></a><a name="adfe6ee126f4f49b78ad6a0bba125d001"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="21.54%" headers="mcps1.1.5.1.3 "><p id="ab2aa7654d5d54e0fa141c9aacb1ab946"><a name="ab2aa7654d5d54e0fa141c9aacb1ab946"></a><a name="ab2aa7654d5d54e0fa141c9aacb1ab946"></a>String | <a href="js-hwmarker.md#s68f99f7a5787475dbe502ecf9a107d48">MarkerLabelOption</a></p>
</td>
<td class="cellrowborder" valign="top" width="45.6%" headers="mcps1.1.5.1.4 "><p id="a9ee49d9391b0421a8f46c978ba4266bd"><a name="a9ee49d9391b0421a8f46c978ba4266bd"></a><a name="a9ee49d9391b0421a8f46c978ba4266bd"></a><a href="js-hwmarker.md">HWMarker</a>聚合后的文字标签，同<a href="js-hwmarker.md">HWMarker</a>的设置，默认值为聚合后的总数。</p>
</td>
</tr>
</tbody>
</table>

