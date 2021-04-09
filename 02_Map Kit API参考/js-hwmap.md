# HWMap<a name="ZH-CN_TOPIC_0000001145860979"></a>

-   [概览](#sc80dc6f3a62a49da9ef687a334c601c4)
-   [构造方法](#se861b2975a3c4027ab05e522f7e195e0)
-   [公共方法](#s197d6d03b9be40c1bbe1924e36b39463)
-   [事件](#s99c654995e49428e819c77d6425b9566)
-   [CopyrightControlOptions](#s54bc0d909e35446eac6552ff59fce17c)
-   [MapOptions](#s08ea7a96339f4dcf82f72b0e4bad2db5)
-   [ScaleControlOptions](#s25716cbc6ea049f89621828a4b96ffe9)
-   [LanguageCode](#s20ffeadccee7487a922e6d4a7fb49a93)

## 概览<a name="sc80dc6f3a62a49da9ef687a334c601c4"></a>

API中的核心类，用来加载一张地图。

## 构造方法<a name="se861b2975a3c4027ab05e522f7e195e0"></a>

<a name="t60cde9d3f4384ca6bc7ee501ecaff092"></a>
<table><thead align="left"><tr id="r5cd5643f1a8147acb0d414938db9bc57"><th class="cellrowborder" valign="top" width="40%" id="mcps1.1.3.1.1"><p id="ada0e31ed46d142a79cc8d7942a18ae34"><a name="ada0e31ed46d142a79cc8d7942a18ae34"></a><a name="ada0e31ed46d142a79cc8d7942a18ae34"></a><strong id="a3e4159b2f7fb4c198e8229730689c77a"><a name="a3e4159b2f7fb4c198e8229730689c77a"></a><a name="a3e4159b2f7fb4c198e8229730689c77a"></a>构造方法</strong></p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.1.3.1.2"><p id="a38d5aabdb81b40d4922dd5cb605398ae"><a name="a38d5aabdb81b40d4922dd5cb605398ae"></a><a name="a38d5aabdb81b40d4922dd5cb605398ae"></a><strong id="a1fca8c0bd306463daa5eb6826d5b3427"><a name="a1fca8c0bd306463daa5eb6826d5b3427"></a><a name="a1fca8c0bd306463daa5eb6826d5b3427"></a>描述</strong></p>
</th>
</tr>
</thead>
<tbody><tr id="r19319deb92f1424a9c757793f8448090"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="a4e41825a6e6047db9ddf33057a8d1520"><a name="a4e41825a6e6047db9ddf33057a8d1520"></a><a name="a4e41825a6e6047db9ddf33057a8d1520"></a>HWMapJsSDK.HWMap(div, mapOptions)</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><a name="ul169877483418"></a><a name="ul169877483418"></a><ul id="ul169877483418"><li>div：填充地图容器，必选项。</li><li>mapOptions：设置地图属性，详情见<a href="#s08ea7a96339f4dcf82f72b0e4bad2db5">MapOptions</a>。</li></ul>
</td>
</tr>
</tbody>
</table>

## 公共方法<a name="s197d6d03b9be40c1bbe1924e36b39463"></a>

<a name="teb71d1c816b2432496fc1b4e9ce839d9"></a>
<table><thead align="left"><tr id="r3d7e91e3b4e341a694685ae89d9fb057"><th class="cellrowborder" valign="top" width="28.752875287528752%" id="mcps1.1.5.1.1"><p id="a37b07e7d183d482083beaa69e3dc0132"><a name="a37b07e7d183d482083beaa69e3dc0132"></a><a name="a37b07e7d183d482083beaa69e3dc0132"></a>方法</p>
</th>
<th class="cellrowborder" valign="top" width="23.752375237523754%" id="mcps1.1.5.1.2"><p id="a9dbcc6836023403a83b2ff8b49ccb027"><a name="a9dbcc6836023403a83b2ff8b49ccb027"></a><a name="a9dbcc6836023403a83b2ff8b49ccb027"></a>描述</p>
</th>
<th class="cellrowborder" valign="top" width="23.402340234023406%" id="mcps1.1.5.1.3"><p id="a47af7f9f40d548b2a0367cd0060113c9"><a name="a47af7f9f40d548b2a0367cd0060113c9"></a><a name="a47af7f9f40d548b2a0367cd0060113c9"></a>参数类型</p>
</th>
<th class="cellrowborder" valign="top" width="24.092409240924095%" id="mcps1.1.5.1.4"><p id="ad1735cdbeaf4489d960cfd25fcf86bde"><a name="ad1735cdbeaf4489d960cfd25fcf86bde"></a><a name="ad1735cdbeaf4489d960cfd25fcf86bde"></a>返回值</p>
</th>
</tr>
</thead>
<tbody><tr id="r8c6a9367c37f4d4b9c4950abbef2206e"><td class="cellrowborder" valign="top" width="28.752875287528752%" headers="mcps1.1.5.1.1 "><p id="a6224c42d88604175aed46fae833f7104"><a name="a6224c42d88604175aed46fae833f7104"></a><a name="a6224c42d88604175aed46fae833f7104"></a>fitBounds(bounds)</p>
</td>
<td class="cellrowborder" valign="top" width="23.752375237523754%" headers="mcps1.1.5.1.2 "><p id="adbb9f32d90f64808b78156b66df2f96b"><a name="adbb9f32d90f64808b78156b66df2f96b"></a><a name="adbb9f32d90f64808b78156b66df2f96b"></a>设置地图显示区域范围。</p>
</td>
<td class="cellrowborder" valign="top" width="23.402340234023406%" headers="mcps1.1.5.1.3 "><p id="a4baf74ed403c4437a5478042c32eccd6"><a name="a4baf74ed403c4437a5478042c32eccd6"></a><a name="a4baf74ed403c4437a5478042c32eccd6"></a><a href="js-params.md#s7da68d05f25f42949a5700ac4cf28a27">LatLngBounds</a></p>
</td>
<td class="cellrowborder" valign="top" width="24.092409240924095%" headers="mcps1.1.5.1.4 "><p id="af191a65abe3543fd9cd1b1e17505eece"><a name="af191a65abe3543fd9cd1b1e17505eece"></a><a name="af191a65abe3543fd9cd1b1e17505eece"></a>-</p>
</td>
</tr>
<tr id="r428ddbbdcf2d4079b9a14b7df08ba423"><td class="cellrowborder" valign="top" width="28.752875287528752%" headers="mcps1.1.5.1.1 "><p id="a13da30cb62174b19b83b74e1913298a6"><a name="a13da30cb62174b19b83b74e1913298a6"></a><a name="a13da30cb62174b19b83b74e1913298a6"></a>getBounds()</p>
</td>
<td class="cellrowborder" valign="top" width="23.752375237523754%" headers="mcps1.1.5.1.2 "><p id="abe92d577edd04401838a18fa513a9760"><a name="abe92d577edd04401838a18fa513a9760"></a><a name="abe92d577edd04401838a18fa513a9760"></a>获取地图显示区域。</p>
</td>
<td class="cellrowborder" valign="top" width="23.402340234023406%" headers="mcps1.1.5.1.3 "><p id="a1c6380d08cc44e8bb88577938f0028fd"><a name="a1c6380d08cc44e8bb88577938f0028fd"></a><a name="a1c6380d08cc44e8bb88577938f0028fd"></a>-</p>
</td>
<td class="cellrowborder" valign="top" width="24.092409240924095%" headers="mcps1.1.5.1.4 "><p id="p10580103225710"><a name="p10580103225710"></a><a name="p10580103225710"></a><a href="js-params.md#s7da68d05f25f42949a5700ac4cf28a27">LatLngBounds</a></p>
<p id="a343aef7cb13d494c8d865535a535755f"><a name="a343aef7cb13d494c8d865535a535755f"></a><a name="a343aef7cb13d494c8d865535a535755f"></a>表示地图显示区域范围。</p>
</td>
</tr>
<tr id="r91780f4c56394b25b10b250f4287dc1e"><td class="cellrowborder" valign="top" width="28.752875287528752%" headers="mcps1.1.5.1.1 "><p id="a2e1830a937604a7eb8bfc918c5efdf84"><a name="a2e1830a937604a7eb8bfc918c5efdf84"></a><a name="a2e1830a937604a7eb8bfc918c5efdf84"></a>getCenter()</p>
</td>
<td class="cellrowborder" valign="top" width="23.752375237523754%" headers="mcps1.1.5.1.2 "><p id="a84a4202d3f944886860e5dd36e3ce3b3"><a name="a84a4202d3f944886860e5dd36e3ce3b3"></a><a name="a84a4202d3f944886860e5dd36e3ce3b3"></a>获取地图中心点坐标。</p>
</td>
<td class="cellrowborder" valign="top" width="23.402340234023406%" headers="mcps1.1.5.1.3 "><p id="aa8525a867cd1439a8c0eb3b70d289dd5"><a name="aa8525a867cd1439a8c0eb3b70d289dd5"></a><a name="aa8525a867cd1439a8c0eb3b70d289dd5"></a>-</p>
</td>
<td class="cellrowborder" valign="top" width="24.092409240924095%" headers="mcps1.1.5.1.4 "><p id="p1542863765711"><a name="p1542863765711"></a><a name="p1542863765711"></a><a href="js-params.md#s45373a8938e040ca9f46c78f4283b385">LatLng</a></p>
<p id="a15e8fbfdc9cc47c7adc6a8106f63efb5"><a name="a15e8fbfdc9cc47c7adc6a8106f63efb5"></a><a name="a15e8fbfdc9cc47c7adc6a8106f63efb5"></a>表示地图中心点经纬度坐标。</p>
</td>
</tr>
<tr id="rd8b97309d6214352b4de8cd9f5f8daeb"><td class="cellrowborder" valign="top" width="28.752875287528752%" headers="mcps1.1.5.1.1 "><p id="ac33f7e9f8db444d9a7e1338b8a593703"><a name="ac33f7e9f8db444d9a7e1338b8a593703"></a><a name="ac33f7e9f8db444d9a7e1338b8a593703"></a>getDiv()</p>
</td>
<td class="cellrowborder" valign="top" width="23.752375237523754%" headers="mcps1.1.5.1.2 "><p id="a67cccfe8b6f7415ead1309e791dbb862"><a name="a67cccfe8b6f7415ead1309e791dbb862"></a><a name="a67cccfe8b6f7415ead1309e791dbb862"></a>获取装载地图的容器。</p>
</td>
<td class="cellrowborder" valign="top" width="23.402340234023406%" headers="mcps1.1.5.1.3 "><p id="ad84e997f9ca44c54a7ed73da85dcd76e"><a name="ad84e997f9ca44c54a7ed73da85dcd76e"></a><a name="ad84e997f9ca44c54a7ed73da85dcd76e"></a>-</p>
</td>
<td class="cellrowborder" valign="top" width="24.092409240924095%" headers="mcps1.1.5.1.4 "><p id="a38e8d21627cf4e49bb736dbec7d429d9"><a name="a38e8d21627cf4e49bb736dbec7d429d9"></a><a name="a38e8d21627cf4e49bb736dbec7d429d9"></a>div容器。</p>
</td>
</tr>
<tr id="r521ada7024164969905ccf72360f645e"><td class="cellrowborder" valign="top" width="28.752875287528752%" headers="mcps1.1.5.1.1 "><p id="a6ae6b79eee164130979bba659c5409d8"><a name="a6ae6b79eee164130979bba659c5409d8"></a><a name="a6ae6b79eee164130979bba659c5409d8"></a>getHeading()</p>
</td>
<td class="cellrowborder" valign="top" width="23.752375237523754%" headers="mcps1.1.5.1.2 "><p id="a656bd1c9d6ad4d70bb0ddc4b320ea939"><a name="a656bd1c9d6ad4d70bb0ddc4b320ea939"></a><a name="a656bd1c9d6ad4d70bb0ddc4b320ea939"></a>获取地图朝向。</p>
</td>
<td class="cellrowborder" valign="top" width="23.402340234023406%" headers="mcps1.1.5.1.3 "><p id="a408f1a3bfe1e40e29a7dac3a228e2388"><a name="a408f1a3bfe1e40e29a7dac3a228e2388"></a><a name="a408f1a3bfe1e40e29a7dac3a228e2388"></a>-</p>
</td>
<td class="cellrowborder" valign="top" width="24.092409240924095%" headers="mcps1.1.5.1.4 "><p id="p8288194717571"><a name="p8288194717571"></a><a name="p8288194717571"></a>Number</p>
<p id="a3a1f5aeee37e4203a653f7a4f8379baa"><a name="a3a1f5aeee37e4203a653f7a4f8379baa"></a><a name="a3a1f5aeee37e4203a653f7a4f8379baa"></a>表示地图朝向与正北夹角值。</p>
</td>
</tr>
<tr id="r1d9937641eab40a383e16d06819aebbf"><td class="cellrowborder" valign="top" width="28.752875287528752%" headers="mcps1.1.5.1.1 "><p id="a14dc20f893fc4126b31049356959204f"><a name="a14dc20f893fc4126b31049356959204f"></a><a name="a14dc20f893fc4126b31049356959204f"></a>getMapType()</p>
</td>
<td class="cellrowborder" valign="top" width="23.752375237523754%" headers="mcps1.1.5.1.2 "><p id="ae0c76cc8754346eb9b473b32026bc9d1"><a name="ae0c76cc8754346eb9b473b32026bc9d1"></a><a name="ae0c76cc8754346eb9b473b32026bc9d1"></a>获取HWMap类型。</p>
</td>
<td class="cellrowborder" valign="top" width="23.402340234023406%" headers="mcps1.1.5.1.3 "><p id="a119b7f4b3c4f4601b63ad5694c6715b8"><a name="a119b7f4b3c4f4601b63ad5694c6715b8"></a><a name="a119b7f4b3c4f4601b63ad5694c6715b8"></a>-</p>
</td>
<td class="cellrowborder" valign="top" width="24.092409240924095%" headers="mcps1.1.5.1.4 "><p id="p188344589571"><a name="p188344589571"></a><a name="p188344589571"></a>String</p>
<p id="aba6ff488e6c84c68879256ff1531915f"><a name="aba6ff488e6c84c68879256ff1531915f"></a><a name="aba6ff488e6c84c68879256ff1531915f"></a>表示地图类型。</p>
</td>
</tr>
<tr id="rdb4972e729dc4a2ba2dda02c8fb1ba83"><td class="cellrowborder" valign="top" width="28.752875287528752%" headers="mcps1.1.5.1.1 "><p id="a96755d8d7c4e4c30bd7f9dc3a9b9061b"><a name="a96755d8d7c4e4c30bd7f9dc3a9b9061b"></a><a name="a96755d8d7c4e4c30bd7f9dc3a9b9061b"></a>getOpacity()</p>
</td>
<td class="cellrowborder" valign="top" width="23.752375237523754%" headers="mcps1.1.5.1.2 "><p id="ad78f535c3a6a49a6886df4e7fced31d8"><a name="ad78f535c3a6a49a6886df4e7fced31d8"></a><a name="ad78f535c3a6a49a6886df4e7fced31d8"></a>获取HWMap当前不透明度。</p>
</td>
<td class="cellrowborder" valign="top" width="23.402340234023406%" headers="mcps1.1.5.1.3 "><p id="af1909a9fc6b24da0bf385b4f95f37802"><a name="af1909a9fc6b24da0bf385b4f95f37802"></a><a name="af1909a9fc6b24da0bf385b4f95f37802"></a>-</p>
</td>
<td class="cellrowborder" valign="top" width="24.092409240924095%" headers="mcps1.1.5.1.4 "><p id="p1537118214585"><a name="p1537118214585"></a><a name="p1537118214585"></a>Number</p>
<p id="a769ab85a957e47ec84ed0490837a26a8"><a name="a769ab85a957e47ec84ed0490837a26a8"></a><a name="a769ab85a957e47ec84ed0490837a26a8"></a>表示地图的不透明度。</p>
</td>
</tr>
<tr id="rfec2d24d5db8474bab627c00af3a4487"><td class="cellrowborder" valign="top" width="28.752875287528752%" headers="mcps1.1.5.1.1 "><p id="afa21115c60e444629bc2ded35918fe64"><a name="afa21115c60e444629bc2ded35918fe64"></a><a name="afa21115c60e444629bc2ded35918fe64"></a>getPoi(pixel)</p>
</td>
<td class="cellrowborder" valign="top" width="23.752375237523754%" headers="mcps1.1.5.1.2 "><p id="a0d9dfe9eacda428aaab59f68f2839bb6"><a name="a0d9dfe9eacda428aaab59f68f2839bb6"></a><a name="a0d9dfe9eacda428aaab59f68f2839bb6"></a>获取当前位置的POI数据。</p>
</td>
<td class="cellrowborder" valign="top" width="23.402340234023406%" headers="mcps1.1.5.1.3 "><p id="p1993815741"><a name="p1993815741"></a><a name="p1993815741"></a>[Number, Number]</p>
<p id="a4e07e2b02ecc4660ab03a88e9f38f1ad"><a name="a4e07e2b02ecc4660ab03a88e9f38f1ad"></a><a name="a4e07e2b02ecc4660ab03a88e9f38f1ad"></a>表示地图上一个像素点坐标，分别表示横坐标和纵坐标。</p>
</td>
<td class="cellrowborder" valign="top" width="24.092409240924095%" headers="mcps1.1.5.1.4 "><p id="a0f4b42ca9165416b87c899e899ea81c0"><a name="a0f4b42ca9165416b87c899e899ea81c0"></a><a name="a0f4b42ca9165416b87c899e899ea81c0"></a>返回当前点击位置的POI信息，包含位置和属性。</p>
</td>
</tr>
<tr id="rdf701d4675a24367a2c2e8edf0639956"><td class="cellrowborder" valign="top" width="28.752875287528752%" headers="mcps1.1.5.1.1 "><p id="a3ab73e6f0c964e4f9aac0c0814568437"><a name="a3ab73e6f0c964e4f9aac0c0814568437"></a><a name="a3ab73e6f0c964e4f9aac0c0814568437"></a>getSize()</p>
</td>
<td class="cellrowborder" valign="top" width="23.752375237523754%" headers="mcps1.1.5.1.2 "><p id="ad30a2305bcc9443790b938fe336fbb8b"><a name="ad30a2305bcc9443790b938fe336fbb8b"></a><a name="ad30a2305bcc9443790b938fe336fbb8b"></a>获取地图大小。</p>
</td>
<td class="cellrowborder" valign="top" width="23.402340234023406%" headers="mcps1.1.5.1.3 "><p id="afe4d0151bbaa4aca8bbb1df750c981b9"><a name="afe4d0151bbaa4aca8bbb1df750c981b9"></a><a name="afe4d0151bbaa4aca8bbb1df750c981b9"></a>-</p>
</td>
<td class="cellrowborder" valign="top" width="24.092409240924095%" headers="mcps1.1.5.1.4 "><p id="acf10d31558264e2489c72a793a3db5a8"><a name="acf10d31558264e2489c72a793a3db5a8"></a><a name="acf10d31558264e2489c72a793a3db5a8"></a>返回[width, height]两个Number类型的数组。</p>
</td>
</tr>
<tr id="r9de8f3451c784968b008c4ebb074bcce"><td class="cellrowborder" valign="top" width="28.752875287528752%" headers="mcps1.1.5.1.1 "><p id="acb981bef103b4aa7b42e58d9d1dbf195"><a name="acb981bef103b4aa7b42e58d9d1dbf195"></a><a name="acb981bef103b4aa7b42e58d9d1dbf195"></a>getZoom()</p>
</td>
<td class="cellrowborder" valign="top" width="23.752375237523754%" headers="mcps1.1.5.1.2 "><p id="afac691aa62d64b53849fd0c939aa5105"><a name="afac691aa62d64b53849fd0c939aa5105"></a><a name="afac691aa62d64b53849fd0c939aa5105"></a>获取地图当前缩放级别。</p>
</td>
<td class="cellrowborder" valign="top" width="23.402340234023406%" headers="mcps1.1.5.1.3 "><p id="a62f85c7783104a169e49e978ab2a851b"><a name="a62f85c7783104a169e49e978ab2a851b"></a><a name="a62f85c7783104a169e49e978ab2a851b"></a>-</p>
</td>
<td class="cellrowborder" valign="top" width="24.092409240924095%" headers="mcps1.1.5.1.4 "><p id="p14391241155817"><a name="p14391241155817"></a><a name="p14391241155817"></a>Number</p>
<p id="aa12343ee2c42420b8f75b4ac2d7cfd8e"><a name="aa12343ee2c42420b8f75b4ac2d7cfd8e"></a><a name="aa12343ee2c42420b8f75b4ac2d7cfd8e"></a>表示地图缩放级别。</p>
</td>
</tr>
<tr id="r5f8c9f71a8354c94a02fc8beca4718a7"><td class="cellrowborder" valign="top" width="28.752875287528752%" headers="mcps1.1.5.1.1 "><p id="aeeca739d50fb49abba2f8a4317bb032d"><a name="aeeca739d50fb49abba2f8a4317bb032d"></a><a name="aeeca739d50fb49abba2f8a4317bb032d"></a>on(event, callback)</p>
</td>
<td class="cellrowborder" valign="top" width="23.752375237523754%" headers="mcps1.1.5.1.2 "><p id="ac0a9b220a5c444d0bb5ab4a9be5e187a"><a name="ac0a9b220a5c444d0bb5ab4a9be5e187a"></a><a name="ac0a9b220a5c444d0bb5ab4a9be5e187a"></a>设置事件触发时调用的自定义函数。</p>
</td>
<td class="cellrowborder" valign="top" width="23.402340234023406%" headers="mcps1.1.5.1.3 "><a name="u4efe973fd7494b829c977fc47845b768"></a><a name="u4efe973fd7494b829c977fc47845b768"></a><ul id="u4efe973fd7494b829c977fc47845b768"><li>event：String，事件类型，见<a href="#s99c654995e49428e819c77d6425b9566">事件</a>。</li><li>callback：Function，事件触发的回调函数。</li></ul>
</td>
<td class="cellrowborder" valign="top" width="24.092409240924095%" headers="mcps1.1.5.1.4 "><p id="a7f90849145684575807baf62455fdde8"><a name="a7f90849145684575807baf62455fdde8"></a><a name="a7f90849145684575807baf62455fdde8"></a>-</p>
</td>
</tr>
<tr id="r1a1e5f60c5c34de8bc0da515dca18ec5"><td class="cellrowborder" valign="top" width="28.752875287528752%" headers="mcps1.1.5.1.1 "><p id="a82e685ba9b0b40f199d1840a0a6f132d"><a name="a82e685ba9b0b40f199d1840a0a6f132d"></a><a name="a82e685ba9b0b40f199d1840a0a6f132d"></a>onCenterChanged(callback)</p>
</td>
<td class="cellrowborder" valign="top" width="23.752375237523754%" headers="mcps1.1.5.1.2 "><p id="ae1fa082a6e1b435db49677190f5d42aa"><a name="ae1fa082a6e1b435db49677190f5d42aa"></a><a name="ae1fa082a6e1b435db49677190f5d42aa"></a>地图中心点改变。</p>
</td>
<td class="cellrowborder" valign="top" width="23.402340234023406%" headers="mcps1.1.5.1.3 "><p id="p19340155983"><a name="p19340155983"></a><a name="p19340155983"></a>Function</p>
<p id="aad0cda792ac840f284cf33f5fdeefcd0"><a name="aad0cda792ac840f284cf33f5fdeefcd0"></a><a name="aad0cda792ac840f284cf33f5fdeefcd0"></a>自定义回调函数。</p>
</td>
<td class="cellrowborder" valign="top" width="24.092409240924095%" headers="mcps1.1.5.1.4 "><p id="a257a262c1e7d46859e215004cb157ba9"><a name="a257a262c1e7d46859e215004cb157ba9"></a><a name="a257a262c1e7d46859e215004cb157ba9"></a>-</p>
</td>
</tr>
<tr id="rd9bca4dc5bae4d73ad56d3739961ffd5"><td class="cellrowborder" valign="top" width="28.752875287528752%" headers="mcps1.1.5.1.1 "><p id="a04e74ef737ca46f6b3b1bf78deb13a83"><a name="a04e74ef737ca46f6b3b1bf78deb13a83"></a><a name="a04e74ef737ca46f6b3b1bf78deb13a83"></a>onHeadingChanged(callback)</p>
</td>
<td class="cellrowborder" valign="top" width="23.752375237523754%" headers="mcps1.1.5.1.2 "><p id="a886355992c9c4ffeb36794874d66f2c2"><a name="a886355992c9c4ffeb36794874d66f2c2"></a><a name="a886355992c9c4ffeb36794874d66f2c2"></a>地图方向改变。</p>
</td>
<td class="cellrowborder" valign="top" width="23.402340234023406%" headers="mcps1.1.5.1.3 "><p id="p174831614082"><a name="p174831614082"></a><a name="p174831614082"></a>Function</p>
<p id="ae78752ef52ef407bb62f73d9a3b3759d"><a name="ae78752ef52ef407bb62f73d9a3b3759d"></a><a name="ae78752ef52ef407bb62f73d9a3b3759d"></a>自定义回调函数。</p>
</td>
<td class="cellrowborder" valign="top" width="24.092409240924095%" headers="mcps1.1.5.1.4 "><p id="afab01cfddb3f4a1184e7ceb51f61d41f"><a name="afab01cfddb3f4a1184e7ceb51f61d41f"></a><a name="afab01cfddb3f4a1184e7ceb51f61d41f"></a>-</p>
</td>
</tr>
<tr id="rb6e934f372d7489c82a495311e828978"><td class="cellrowborder" valign="top" width="28.752875287528752%" headers="mcps1.1.5.1.1 "><p id="a15803bb9865344dcb98bbd153a4eba8e"><a name="a15803bb9865344dcb98bbd153a4eba8e"></a><a name="a15803bb9865344dcb98bbd153a4eba8e"></a>onZoomChanged(callback)</p>
</td>
<td class="cellrowborder" valign="top" width="23.752375237523754%" headers="mcps1.1.5.1.2 "><p id="a6c58d6816d0442f68c8c3582b0d6ef12"><a name="a6c58d6816d0442f68c8c3582b0d6ef12"></a><a name="a6c58d6816d0442f68c8c3582b0d6ef12"></a>缩放级别改变。</p>
</td>
<td class="cellrowborder" valign="top" width="23.402340234023406%" headers="mcps1.1.5.1.3 "><p id="p53661818187"><a name="p53661818187"></a><a name="p53661818187"></a>Function</p>
<p id="a92bb2bdb29d5409099d817665f99e455"><a name="a92bb2bdb29d5409099d817665f99e455"></a><a name="a92bb2bdb29d5409099d817665f99e455"></a>自定义回调函数。</p>
</td>
<td class="cellrowborder" valign="top" width="24.092409240924095%" headers="mcps1.1.5.1.4 "><p id="ae9033c74d87e46989f9cdcb8ea27e6ec"><a name="ae9033c74d87e46989f9cdcb8ea27e6ec"></a><a name="ae9033c74d87e46989f9cdcb8ea27e6ec"></a>-</p>
</td>
</tr>
<tr id="rf4702a4ef4b94c459189113b1f74eec0"><td class="cellrowborder" valign="top" width="28.752875287528752%" headers="mcps1.1.5.1.1 "><p id="a5f966110e15a400bb445ab23c3ec15d8"><a name="a5f966110e15a400bb445ab23c3ec15d8"></a><a name="a5f966110e15a400bb445ab23c3ec15d8"></a>panBy(x, y)</p>
</td>
<td class="cellrowborder" valign="top" width="23.752375237523754%" headers="mcps1.1.5.1.2 "><p id="a11520220d7174bc1899cc881440f65f3"><a name="a11520220d7174bc1899cc881440f65f3"></a><a name="a11520220d7174bc1899cc881440f65f3"></a>将地图中心点偏移(x, y)。</p>
</td>
<td class="cellrowborder" valign="top" width="23.402340234023406%" headers="mcps1.1.5.1.3 "><a name="ul6696135719578"></a><a name="ul6696135719578"></a><ul id="ul6696135719578"><li>x：Number，横坐标偏移的像素数。</li><li>y：Number，纵坐标偏移的像素数。</li></ul>
</td>
<td class="cellrowborder" valign="top" width="24.092409240924095%" headers="mcps1.1.5.1.4 "><p id="a44917686b343435680601623be1b050f"><a name="a44917686b343435680601623be1b050f"></a><a name="a44917686b343435680601623be1b050f"></a>-</p>
</td>
</tr>
<tr id="r13d7d7c34aa646a7b53f488c1cad2c53"><td class="cellrowborder" valign="top" width="28.752875287528752%" headers="mcps1.1.5.1.1 "><p id="a9b92a377030948dab572fd9e65ed5975"><a name="a9b92a377030948dab572fd9e65ed5975"></a><a name="a9b92a377030948dab572fd9e65ed5975"></a>panTo(latLng)</p>
</td>
<td class="cellrowborder" valign="top" width="23.752375237523754%" headers="mcps1.1.5.1.2 "><p id="ad414370df3e5478899c73922e503e038"><a name="ad414370df3e5478899c73922e503e038"></a><a name="ad414370df3e5478899c73922e503e038"></a>地图中心移动到指定坐标点。</p>
</td>
<td class="cellrowborder" valign="top" width="23.402340234023406%" headers="mcps1.1.5.1.3 "><p id="a0f8f751258fd496e9da866f4ae3b0c07"><a name="a0f8f751258fd496e9da866f4ae3b0c07"></a><a name="a0f8f751258fd496e9da866f4ae3b0c07"></a><a href="js-params.md#s45373a8938e040ca9f46c78f4283b385">LatLng</a></p>
</td>
<td class="cellrowborder" valign="top" width="24.092409240924095%" headers="mcps1.1.5.1.4 "><p id="a377ccceadd804737b3e4787a7965d5a1"><a name="a377ccceadd804737b3e4787a7965d5a1"></a><a name="a377ccceadd804737b3e4787a7965d5a1"></a>-</p>
</td>
</tr>
<tr id="rd6cd4156a9f54379b48bb52999792520"><td class="cellrowborder" valign="top" width="28.752875287528752%" headers="mcps1.1.5.1.1 "><p id="a7c6d000faee040d886e6f41e0b9209e8"><a name="a7c6d000faee040d886e6f41e0b9209e8"></a><a name="a7c6d000faee040d886e6f41e0b9209e8"></a>panToBounds(latLngBounds)</p>
</td>
<td class="cellrowborder" valign="top" width="23.752375237523754%" headers="mcps1.1.5.1.2 "><p id="a10861dc613054b3688291e54eac66499"><a name="a10861dc613054b3688291e54eac66499"></a><a name="a10861dc613054b3688291e54eac66499"></a>移动地图使得包含指定坐标区域。</p>
</td>
<td class="cellrowborder" valign="top" width="23.402340234023406%" headers="mcps1.1.5.1.3 "><p id="a16e7600ce26142e39e5aaea54d832cc7"><a name="a16e7600ce26142e39e5aaea54d832cc7"></a><a name="a16e7600ce26142e39e5aaea54d832cc7"></a><a href="js-params.md#s7da68d05f25f42949a5700ac4cf28a27">LatLngBounds</a></p>
</td>
<td class="cellrowborder" valign="top" width="24.092409240924095%" headers="mcps1.1.5.1.4 "><p id="add75d899bc8d457cad306483d5fbaecf"><a name="add75d899bc8d457cad306483d5fbaecf"></a><a name="add75d899bc8d457cad306483d5fbaecf"></a>-</p>
</td>
</tr>
<tr id="rba88345e3570409a9fc4c9eef6ca1741"><td class="cellrowborder" valign="top" width="28.752875287528752%" headers="mcps1.1.5.1.1 "><p id="a8b38fc3b7b95410cbdb33a29229dd6d3"><a name="a8b38fc3b7b95410cbdb33a29229dd6d3"></a><a name="a8b38fc3b7b95410cbdb33a29229dd6d3"></a>setCenter(latlng)</p>
</td>
<td class="cellrowborder" valign="top" width="23.752375237523754%" headers="mcps1.1.5.1.2 "><p id="a1b3100ba5638471e9ca7747bf6a1075f"><a name="a1b3100ba5638471e9ca7747bf6a1075f"></a><a name="a1b3100ba5638471e9ca7747bf6a1075f"></a>设置地图中心点坐标。</p>
</td>
<td class="cellrowborder" valign="top" width="23.402340234023406%" headers="mcps1.1.5.1.3 "><p id="a44ac097967be4edbb7f051fc242823b5"><a name="a44ac097967be4edbb7f051fc242823b5"></a><a name="a44ac097967be4edbb7f051fc242823b5"></a><a href="js-params.md#s45373a8938e040ca9f46c78f4283b385">LatLng</a></p>
</td>
<td class="cellrowborder" valign="top" width="24.092409240924095%" headers="mcps1.1.5.1.4 "><p id="a74afc238436e47929f7bc193aac72915"><a name="a74afc238436e47929f7bc193aac72915"></a><a name="a74afc238436e47929f7bc193aac72915"></a>-</p>
</td>
</tr>
<tr id="ra5524d38cc2747f59c9c152d1fe14fae"><td class="cellrowborder" valign="top" width="28.752875287528752%" headers="mcps1.1.5.1.1 "><p id="a828bc6b148294412930d1a30c43f8b6f"><a name="a828bc6b148294412930d1a30c43f8b6f"></a><a name="a828bc6b148294412930d1a30c43f8b6f"></a>setCopyrightControl(enabled)</p>
</td>
<td class="cellrowborder" valign="top" width="23.752375237523754%" headers="mcps1.1.5.1.2 "><p id="a3fdd6af8283a42608907bc17c890ffe9"><a name="a3fdd6af8283a42608907bc17c890ffe9"></a><a name="a3fdd6af8283a42608907bc17c890ffe9"></a>设置是否显示版权。</p>
</td>
<td class="cellrowborder" valign="top" width="23.402340234023406%" headers="mcps1.1.5.1.3 "><p id="a0a9f4e9a97814a9289756661bd916c38"><a name="a0a9f4e9a97814a9289756661bd916c38"></a><a name="a0a9f4e9a97814a9289756661bd916c38"></a>Boolean</p>
<p id="a4e9605ddc2154e3f8dc771986796b3d8"><a name="a4e9605ddc2154e3f8dc771986796b3d8"></a><a name="a4e9605ddc2154e3f8dc771986796b3d8"></a>true显示，false关闭。</p>
</td>
<td class="cellrowborder" valign="top" width="24.092409240924095%" headers="mcps1.1.5.1.4 "><p id="a4933b4dfc6e243798d561c05c841e594"><a name="a4933b4dfc6e243798d561c05c841e594"></a><a name="a4933b4dfc6e243798d561c05c841e594"></a>-</p>
</td>
</tr>
<tr id="rff3759f6fa454a6887c18aca39da3d65"><td class="cellrowborder" valign="top" width="28.752875287528752%" headers="mcps1.1.5.1.1 "><p id="a3d408dbe392c46a1b44937e9397c79b3"><a name="a3d408dbe392c46a1b44937e9397c79b3"></a><a name="a3d408dbe392c46a1b44937e9397c79b3"></a>setHeading(heading)</p>
</td>
<td class="cellrowborder" valign="top" width="23.752375237523754%" headers="mcps1.1.5.1.2 "><p id="a157ecc9a575d45a2847ff8b06d8c9e88"><a name="a157ecc9a575d45a2847ff8b06d8c9e88"></a><a name="a157ecc9a575d45a2847ff8b06d8c9e88"></a>设置地图朝向。</p>
</td>
<td class="cellrowborder" valign="top" width="23.402340234023406%" headers="mcps1.1.5.1.3 "><p id="p12735527111012"><a name="p12735527111012"></a><a name="p12735527111012"></a>Number</p>
<p id="affabdee91e5f435e8811564520c09a08"><a name="affabdee91e5f435e8811564520c09a08"></a><a name="affabdee91e5f435e8811564520c09a08"></a>值为地图朝向与实际正北的夹角，取值范围：[0, 360]。</p>
</td>
<td class="cellrowborder" valign="top" width="24.092409240924095%" headers="mcps1.1.5.1.4 "><p id="a0cc1edd855a345aeb7314a20088e20ca"><a name="a0cc1edd855a345aeb7314a20088e20ca"></a><a name="a0cc1edd855a345aeb7314a20088e20ca"></a>-</p>
</td>
</tr>
<tr id="r4c1d31e7c1e8417a9cccdaa662d8ba3f"><td class="cellrowborder" valign="top" width="28.752875287528752%" headers="mcps1.1.5.1.1 "><p id="p882775912212"><a name="p882775912212"></a><a name="p882775912212"></a>setLocationControl</p>
</td>
<td class="cellrowborder" valign="top" width="23.752375237523754%" headers="mcps1.1.5.1.2 "><p id="a276df410fa1c437f8752cdaf7f377fa9"><a name="a276df410fa1c437f8752cdaf7f377fa9"></a><a name="a276df410fa1c437f8752cdaf7f377fa9"></a>设置是否显示当前位置按钮。</p>
</td>
<td class="cellrowborder" valign="top" width="23.402340234023406%" headers="mcps1.1.5.1.3 "><p id="a9c5c64475c6640509c9891f1d0c33eb5"><a name="a9c5c64475c6640509c9891f1d0c33eb5"></a><a name="a9c5c64475c6640509c9891f1d0c33eb5"></a>Boolean</p>
<p id="a33c7afab5cb445fab5da26215e8836b3"><a name="a33c7afab5cb445fab5da26215e8836b3"></a><a name="a33c7afab5cb445fab5da26215e8836b3"></a>true表示显示，false表示关闭。</p>
</td>
<td class="cellrowborder" valign="top" width="24.092409240924095%" headers="mcps1.1.5.1.4 "><p id="ab282c458faa14d9b89c67ea39debd550"><a name="ab282c458faa14d9b89c67ea39debd550"></a><a name="ab282c458faa14d9b89c67ea39debd550"></a>-</p>
</td>
</tr>
<tr id="r52d5015e41f24297840f215aa4fe73a7"><td class="cellrowborder" valign="top" width="28.752875287528752%" headers="mcps1.1.5.1.1 "><p id="p891624212220"><a name="p891624212220"></a><a name="p891624212220"></a>setNavigationControl</p>
</td>
<td class="cellrowborder" valign="top" width="23.752375237523754%" headers="mcps1.1.5.1.2 "><p id="p9720184419222"><a name="p9720184419222"></a><a name="p9720184419222"></a>设置是否显示平移按钮。</p>
</td>
<td class="cellrowborder" valign="top" width="23.402340234023406%" headers="mcps1.1.5.1.3 "><p id="a5841142a3766495f80f1d27f7e0e757d"><a name="a5841142a3766495f80f1d27f7e0e757d"></a><a name="a5841142a3766495f80f1d27f7e0e757d"></a>Boolean</p>
<p id="a86c7728683b043efbb743eb458701148"><a name="a86c7728683b043efbb743eb458701148"></a><a name="a86c7728683b043efbb743eb458701148"></a>true表示显示，false表示关闭。</p>
</td>
<td class="cellrowborder" valign="top" width="24.092409240924095%" headers="mcps1.1.5.1.4 "><p id="ae2acb77f12cc40a0a016934452bec973"><a name="ae2acb77f12cc40a0a016934452bec973"></a><a name="ae2acb77f12cc40a0a016934452bec973"></a>-</p>
</td>
</tr>
<tr id="rdedd2fddb9794471955a931426cc3064"><td class="cellrowborder" valign="top" width="28.752875287528752%" headers="mcps1.1.5.1.1 "><p id="ac1428cdda27d4d1ea520cc66dc1f82ae"><a name="ac1428cdda27d4d1ea520cc66dc1f82ae"></a><a name="ac1428cdda27d4d1ea520cc66dc1f82ae"></a>setOpacity(opacity)</p>
</td>
<td class="cellrowborder" valign="top" width="23.752375237523754%" headers="mcps1.1.5.1.2 "><p id="a34c524d4c2a0448d81a3ea9ed4f4901f"><a name="a34c524d4c2a0448d81a3ea9ed4f4901f"></a><a name="a34c524d4c2a0448d81a3ea9ed4f4901f"></a>设置地图不透明度。</p>
</td>
<td class="cellrowborder" valign="top" width="23.402340234023406%" headers="mcps1.1.5.1.3 "><p id="p11103440191019"><a name="p11103440191019"></a><a name="p11103440191019"></a>Number</p>
<p id="a61c3b2f45e384674bd916080e672d7ea"><a name="a61c3b2f45e384674bd916080e672d7ea"></a><a name="a61c3b2f45e384674bd916080e672d7ea"></a>取值范围：[0, 1]。</p>
</td>
<td class="cellrowborder" valign="top" width="24.092409240924095%" headers="mcps1.1.5.1.4 "><p id="a546ebf52e36149cc9d6905cc578d33a3"><a name="a546ebf52e36149cc9d6905cc578d33a3"></a><a name="a546ebf52e36149cc9d6905cc578d33a3"></a>-</p>
</td>
</tr>
<tr id="row5419163712712"><td class="cellrowborder" valign="top" width="28.752875287528752%" headers="mcps1.1.5.1.1 "><p id="p6573949278"><a name="p6573949278"></a><a name="p6573949278"></a>setPinchRotate(disabled)</p>
</td>
<td class="cellrowborder" valign="top" width="23.752375237523754%" headers="mcps1.1.5.1.2 "><p id="p1042018371374"><a name="p1042018371374"></a><a name="p1042018371374"></a>设置地图双指旋转是否可用。</p>
</td>
<td class="cellrowborder" valign="top" width="23.402340234023406%" headers="mcps1.1.5.1.3 "><p id="p146897521813"><a name="p146897521813"></a><a name="p146897521813"></a>Boolean，</p>
<p id="p166897521781"><a name="p166897521781"></a><a name="p166897521781"></a>true表示可用，false表示不可用，默认为可用。</p>
</td>
<td class="cellrowborder" valign="top" width="24.092409240924095%" headers="mcps1.1.5.1.4 "><p id="p3421163715712"><a name="p3421163715712"></a><a name="p3421163715712"></a>-</p>
</td>
</tr>
<tr id="rbc181ce550434826b6c3ce29cd3f3067"><td class="cellrowborder" valign="top" width="28.752875287528752%" headers="mcps1.1.5.1.1 "><p id="a0ca80f29c39940419ba3b3aee9600fe1"><a name="a0ca80f29c39940419ba3b3aee9600fe1"></a><a name="a0ca80f29c39940419ba3b3aee9600fe1"></a>setPresetStyleId(presetStyleId)</p>
</td>
<td class="cellrowborder" valign="top" width="23.752375237523754%" headers="mcps1.1.5.1.2 "><p id="ad096321b3a54489298cafda620d664d6"><a name="ad096321b3a54489298cafda620d664d6"></a><a name="ad096321b3a54489298cafda620d664d6"></a>设置预置地图样式。</p>
</td>
<td class="cellrowborder" valign="top" width="23.402340234023406%" headers="mcps1.1.5.1.3 "><p id="p129595475106"><a name="p129595475106"></a><a name="p129595475106"></a>String</p>
<p id="a188a4b70ca024d95890cbedb81dc2fd3"><a name="a188a4b70ca024d95890cbedb81dc2fd3"></a><a name="a188a4b70ca024d95890cbedb81dc2fd3"></a>可选值为：standard、night、simple。</p>
</td>
<td class="cellrowborder" valign="top" width="24.092409240924095%" headers="mcps1.1.5.1.4 "><p id="ad9f7d2b5e1b64dad99fa4503875e4d1c"><a name="ad9f7d2b5e1b64dad99fa4503875e4d1c"></a><a name="ad9f7d2b5e1b64dad99fa4503875e4d1c"></a>-</p>
</td>
</tr>
<tr id="rfd4b45be709b40ce881aec3cc17c1104"><td class="cellrowborder" valign="top" width="28.752875287528752%" headers="mcps1.1.5.1.1 "><p id="aa74554ee590147f0aca9948475129d78"><a name="aa74554ee590147f0aca9948475129d78"></a><a name="aa74554ee590147f0aca9948475129d78"></a>setRotateControl(enabled)</p>
</td>
<td class="cellrowborder" valign="top" width="23.752375237523754%" headers="mcps1.1.5.1.2 "><p id="ab1024558c9a04178ad4f5470d676a060"><a name="ab1024558c9a04178ad4f5470d676a060"></a><a name="ab1024558c9a04178ad4f5470d676a060"></a>设置是否显示指北针。</p>
</td>
<td class="cellrowborder" valign="top" width="23.402340234023406%" headers="mcps1.1.5.1.3 "><p id="a9a075213f62840d880ac8aab817c3571"><a name="a9a075213f62840d880ac8aab817c3571"></a><a name="a9a075213f62840d880ac8aab817c3571"></a>Boolean</p>
<p id="abfca638217ba4d04bd46ab18ef71aed4"><a name="abfca638217ba4d04bd46ab18ef71aed4"></a><a name="abfca638217ba4d04bd46ab18ef71aed4"></a>true表示显示，false表示关闭。</p>
</td>
<td class="cellrowborder" valign="top" width="24.092409240924095%" headers="mcps1.1.5.1.4 "><p id="a0bcc54d8d37d4f1d90a19745ed08efae"><a name="a0bcc54d8d37d4f1d90a19745ed08efae"></a><a name="a0bcc54d8d37d4f1d90a19745ed08efae"></a>-</p>
</td>
</tr>
<tr id="rf1e237a69fc6418b9d945371b1d681c5"><td class="cellrowborder" valign="top" width="28.752875287528752%" headers="mcps1.1.5.1.1 "><p id="a944cbc916f1f4a4286b950c5409d55ac"><a name="a944cbc916f1f4a4286b950c5409d55ac"></a><a name="a944cbc916f1f4a4286b950c5409d55ac"></a>setScaleControl(enabled)</p>
</td>
<td class="cellrowborder" valign="top" width="23.752375237523754%" headers="mcps1.1.5.1.2 "><p id="a27dbef6ce88c48548473b73761becf53"><a name="a27dbef6ce88c48548473b73761becf53"></a><a name="a27dbef6ce88c48548473b73761becf53"></a>设置是否显示比例尺。</p>
</td>
<td class="cellrowborder" valign="top" width="23.402340234023406%" headers="mcps1.1.5.1.3 "><p id="aec750e4746504720b8ca1cfb3fa145f9"><a name="aec750e4746504720b8ca1cfb3fa145f9"></a><a name="aec750e4746504720b8ca1cfb3fa145f9"></a>Boolean</p>
<p id="acfec06cff7194211b6244b8c64f01953"><a name="acfec06cff7194211b6244b8c64f01953"></a><a name="acfec06cff7194211b6244b8c64f01953"></a>true表示显示，false表示关闭。</p>
</td>
<td class="cellrowborder" valign="top" width="24.092409240924095%" headers="mcps1.1.5.1.4 "><p id="a1688a7efed9f4009bef70a53056d459c"><a name="a1688a7efed9f4009bef70a53056d459c"></a><a name="a1688a7efed9f4009bef70a53056d459c"></a>-</p>
</td>
</tr>
<tr id="r11f10cb481fd4160b4a3da4c60e86891"><td class="cellrowborder" valign="top" width="28.752875287528752%" headers="mcps1.1.5.1.1 "><p id="a7b0ebfa651b047e49a4072cdead7b515"><a name="a7b0ebfa651b047e49a4072cdead7b515"></a><a name="a7b0ebfa651b047e49a4072cdead7b515"></a>setStyle(styles)</p>
</td>
<td class="cellrowborder" valign="top" width="23.752375237523754%" headers="mcps1.1.5.1.2 "><p id="a76cd185cb92f48a2980b9f3acae12168"><a name="a76cd185cb92f48a2980b9f3acae12168"></a><a name="a76cd185cb92f48a2980b9f3acae12168"></a>通过JSON文件设置自定义地图样式。</p>
</td>
<td class="cellrowborder" valign="top" width="23.402340234023406%" headers="mcps1.1.5.1.3 "><p id="a31c70067f48d4dcfad0dcc4252a9391b"><a name="a31c70067f48d4dcfad0dcc4252a9391b"></a><a name="a31c70067f48d4dcfad0dcc4252a9391b"></a>JSON数组。</p>
</td>
<td class="cellrowborder" valign="top" width="24.092409240924095%" headers="mcps1.1.5.1.4 "><p id="aeee083d5b0514c50a61822fc25db9751"><a name="aeee083d5b0514c50a61822fc25db9751"></a><a name="aeee083d5b0514c50a61822fc25db9751"></a>-</p>
</td>
</tr>
<tr id="r9e5aa301f35b4ebca5aa080fcb46321f"><td class="cellrowborder" valign="top" width="28.752875287528752%" headers="mcps1.1.5.1.1 "><p id="add84ac6108f54135bdb29f4eed28d0f8"><a name="add84ac6108f54135bdb29f4eed28d0f8"></a><a name="add84ac6108f54135bdb29f4eed28d0f8"></a>setTitle(title)</p>
</td>
<td class="cellrowborder" valign="top" width="23.752375237523754%" headers="mcps1.1.5.1.2 "><p id="a7455de206fb2406c983311c2b71f2520"><a name="a7455de206fb2406c983311c2b71f2520"></a><a name="a7455de206fb2406c983311c2b71f2520"></a>设置地图所在容器的提示信息。</p>
</td>
<td class="cellrowborder" valign="top" width="23.402340234023406%" headers="mcps1.1.5.1.3 "><p id="aa84d0736182e428b82130525fd0ebdd1"><a name="aa84d0736182e428b82130525fd0ebdd1"></a><a name="aa84d0736182e428b82130525fd0ebdd1"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="24.092409240924095%" headers="mcps1.1.5.1.4 "><p id="ae73aa563ad5a4015ba4660590a25cf73"><a name="ae73aa563ad5a4015ba4660590a25cf73"></a><a name="ae73aa563ad5a4015ba4660590a25cf73"></a>-</p>
</td>
</tr>
<tr id="r8f736f7c74c84094a0483653a88ef498"><td class="cellrowborder" valign="top" width="28.752875287528752%" headers="mcps1.1.5.1.1 "><p id="a1ec95324e621440fbb3351c69c0abf99"><a name="a1ec95324e621440fbb3351c69c0abf99"></a><a name="a1ec95324e621440fbb3351c69c0abf99"></a>setZoom(zoom)</p>
</td>
<td class="cellrowborder" valign="top" width="23.752375237523754%" headers="mcps1.1.5.1.2 "><p id="a0c27a76179ac47b1bd68221f0e5d606d"><a name="a0c27a76179ac47b1bd68221f0e5d606d"></a><a name="a0c27a76179ac47b1bd68221f0e5d606d"></a>设置地图缩放级别。</p>
</td>
<td class="cellrowborder" valign="top" width="23.402340234023406%" headers="mcps1.1.5.1.3 "><p id="p1382143782512"><a name="p1382143782512"></a><a name="p1382143782512"></a>数值类型</p>
<p id="a8b09c052f2e84d5fbc24d8f8a385b6d6"><a name="a8b09c052f2e84d5fbc24d8f8a385b6d6"></a><a name="a8b09c052f2e84d5fbc24d8f8a385b6d6"></a>取值范围：[minZoom, maxZoom]。</p>
</td>
<td class="cellrowborder" valign="top" width="24.092409240924095%" headers="mcps1.1.5.1.4 "><p id="a83ab4e363a814393a294825262037c82"><a name="a83ab4e363a814393a294825262037c82"></a><a name="a83ab4e363a814393a294825262037c82"></a>-</p>
</td>
</tr>
<tr id="r7682cbc9b7a246eb8dc133005189a4c5"><td class="cellrowborder" valign="top" width="28.752875287528752%" headers="mcps1.1.5.1.1 "><p id="a2f3d39f689ad449ba517b008267a6d16"><a name="a2f3d39f689ad449ba517b008267a6d16"></a><a name="a2f3d39f689ad449ba517b008267a6d16"></a>setZoomControl(enabled)</p>
</td>
<td class="cellrowborder" valign="top" width="23.752375237523754%" headers="mcps1.1.5.1.2 "><p id="a0735e0e1c38e4e2083be6661476d59df"><a name="a0735e0e1c38e4e2083be6661476d59df"></a><a name="a0735e0e1c38e4e2083be6661476d59df"></a>设置是否显示缩放按钮。</p>
</td>
<td class="cellrowborder" valign="top" width="23.402340234023406%" headers="mcps1.1.5.1.3 "><p id="a2e328955c83941e583e310ec274ce3fd"><a name="a2e328955c83941e583e310ec274ce3fd"></a><a name="a2e328955c83941e583e310ec274ce3fd"></a>Boolean</p>
<p id="ae54dd0305a714f4a93641ca4ffd76fe8"><a name="ae54dd0305a714f4a93641ca4ffd76fe8"></a><a name="ae54dd0305a714f4a93641ca4ffd76fe8"></a>true表示显示，false表示关闭。</p>
</td>
<td class="cellrowborder" valign="top" width="24.092409240924095%" headers="mcps1.1.5.1.4 "><p id="a2070761a1fb843a3b3a3af20c2023fa0"><a name="a2070761a1fb843a3b3a3af20c2023fa0"></a><a name="a2070761a1fb843a3b3a3af20c2023fa0"></a>-</p>
</td>
</tr>
<tr id="r799cacf6ce4446f69457d65ff8aca2ee"><td class="cellrowborder" valign="top" width="28.752875287528752%" headers="mcps1.1.5.1.1 "><p id="a23c6656b241c4d118c8e8d637feec44c"><a name="a23c6656b241c4d118c8e8d637feec44c"></a><a name="a23c6656b241c4d118c8e8d637feec44c"></a>setZoomSlider(enabled)</p>
</td>
<td class="cellrowborder" valign="top" width="23.752375237523754%" headers="mcps1.1.5.1.2 "><p id="a36cb298d3eb04ad0ace8eaf9ef557038"><a name="a36cb298d3eb04ad0ace8eaf9ef557038"></a><a name="a36cb298d3eb04ad0ace8eaf9ef557038"></a>设置是否显示缩放条。</p>
</td>
<td class="cellrowborder" valign="top" width="23.402340234023406%" headers="mcps1.1.5.1.3 "><p id="a5cf96aeb831a4c52b98ec564a3be7496"><a name="a5cf96aeb831a4c52b98ec564a3be7496"></a><a name="a5cf96aeb831a4c52b98ec564a3be7496"></a>Boolean</p>
<p id="ad8ea56cf219848be84fc3bcc098ab9cb"><a name="ad8ea56cf219848be84fc3bcc098ab9cb"></a><a name="ad8ea56cf219848be84fc3bcc098ab9cb"></a>true表示显示，false表示关闭。</p>
</td>
<td class="cellrowborder" valign="top" width="24.092409240924095%" headers="mcps1.1.5.1.4 "><p id="a54560aac8c1d433bacb7c66ba1d81d3a"><a name="a54560aac8c1d433bacb7c66ba1d81d3a"></a><a name="a54560aac8c1d433bacb7c66ba1d81d3a"></a>-</p>
</td>
</tr>
<tr id="r0d81c19651244f68965795fb28d43086"><td class="cellrowborder" valign="top" width="28.752875287528752%" headers="mcps1.1.5.1.1 "><p id="a95d625555c97424d95489d9de69a52d6"><a name="a95d625555c97424d95489d9de69a52d6"></a><a name="a95d625555c97424d95489d9de69a52d6"></a>zoomIn()</p>
</td>
<td class="cellrowborder" valign="top" width="23.752375237523754%" headers="mcps1.1.5.1.2 "><p id="ad72a4e45fc3c498ca69ead0d543e0eb2"><a name="ad72a4e45fc3c498ca69ead0d543e0eb2"></a><a name="ad72a4e45fc3c498ca69ead0d543e0eb2"></a>地图放大一个级别。</p>
</td>
<td class="cellrowborder" valign="top" width="23.402340234023406%" headers="mcps1.1.5.1.3 "><p id="ac5b49a30187d4401bec8bcabf25b51aa"><a name="ac5b49a30187d4401bec8bcabf25b51aa"></a><a name="ac5b49a30187d4401bec8bcabf25b51aa"></a>-</p>
</td>
<td class="cellrowborder" valign="top" width="24.092409240924095%" headers="mcps1.1.5.1.4 "><p id="a755bec1ff83e4e4c8b8364fe03ecb4c3"><a name="a755bec1ff83e4e4c8b8364fe03ecb4c3"></a><a name="a755bec1ff83e4e4c8b8364fe03ecb4c3"></a>-</p>
</td>
</tr>
<tr id="ra4ea932c87674d75a38d9567d13d51fe"><td class="cellrowborder" valign="top" width="28.752875287528752%" headers="mcps1.1.5.1.1 "><p id="a587fcb5563e645afbe7efe5d6c431809"><a name="a587fcb5563e645afbe7efe5d6c431809"></a><a name="a587fcb5563e645afbe7efe5d6c431809"></a>zoomOut()</p>
</td>
<td class="cellrowborder" valign="top" width="23.752375237523754%" headers="mcps1.1.5.1.2 "><p id="a797ff8ccedcf4c96976b098e57278c0c"><a name="a797ff8ccedcf4c96976b098e57278c0c"></a><a name="a797ff8ccedcf4c96976b098e57278c0c"></a>地图缩小一个级别。</p>
</td>
<td class="cellrowborder" valign="top" width="23.402340234023406%" headers="mcps1.1.5.1.3 "><p id="a1012a535116144ef81dc59a33f1391b5"><a name="a1012a535116144ef81dc59a33f1391b5"></a><a name="a1012a535116144ef81dc59a33f1391b5"></a>-</p>
</td>
<td class="cellrowborder" valign="top" width="24.092409240924095%" headers="mcps1.1.5.1.4 "><p id="a0b227379a9e94ed6aa3ca0c702edb3bd"><a name="a0b227379a9e94ed6aa3ca0c702edb3bd"></a><a name="a0b227379a9e94ed6aa3ca0c702edb3bd"></a>-</p>
</td>
</tr>
</tbody>
</table>

## 事件<a name="s99c654995e49428e819c77d6425b9566"></a>

<a name="tdffc50ce724344c787880d404b408547"></a>
<table><thead align="left"><tr id="raf45639bc8714764bc15fb338a1d20c9"><th class="cellrowborder" valign="top" width="19.908009199080094%" id="mcps1.1.5.1.1"><p id="a065e39426bab46dcaa6fe3347ad04a20"><a name="a065e39426bab46dcaa6fe3347ad04a20"></a><a name="a065e39426bab46dcaa6fe3347ad04a20"></a><strong id="ac00d3c26e98d473d85315c27f272c51a"><a name="ac00d3c26e98d473d85315c27f272c51a"></a><a name="ac00d3c26e98d473d85315c27f272c51a"></a>事件</strong></p>
</th>
<th class="cellrowborder" valign="top" width="16.878312168783122%" id="mcps1.1.5.1.2"><p id="a4ee899ee545846929d884cf44782b7c2"><a name="a4ee899ee545846929d884cf44782b7c2"></a><a name="a4ee899ee545846929d884cf44782b7c2"></a><strong id="a9fb9cefd4a4743bdbc9512b9ee3ff7b6"><a name="a9fb9cefd4a4743bdbc9512b9ee3ff7b6"></a><a name="a9fb9cefd4a4743bdbc9512b9ee3ff7b6"></a>描述</strong></p>
</th>
<th class="cellrowborder" valign="top" width="31.77682231776823%" id="mcps1.1.5.1.3"><p id="abe8e6145f5b5429faca36ade37e9bea8"><a name="abe8e6145f5b5429faca36ade37e9bea8"></a><a name="abe8e6145f5b5429faca36ade37e9bea8"></a><strong id="aadb316c246634ba49cd140a86c6d370f"><a name="aadb316c246634ba49cd140a86c6d370f"></a><a name="aadb316c246634ba49cd140a86c6d370f"></a>用法</strong></p>
</th>
<th class="cellrowborder" valign="top" width="31.436856314368566%" id="mcps1.1.5.1.4"><p id="p18129133812243"><a name="p18129133812243"></a><a name="p18129133812243"></a>说明</p>
</th>
</tr>
</thead>
<tbody><tr id="ra54b5bd79f23458aa6e9cd011f02cba3"><td class="cellrowborder" valign="top" width="19.908009199080094%" headers="mcps1.1.5.1.1 "><p id="ac5bc0586c7cc4941b5892fd672bf64af"><a name="ac5bc0586c7cc4941b5892fd672bf64af"></a><a name="ac5bc0586c7cc4941b5892fd672bf64af"></a>click</p>
</td>
<td class="cellrowborder" valign="top" width="16.878312168783122%" headers="mcps1.1.5.1.2 "><p id="af0606092d7c344978d498a8cd584cb80"><a name="af0606092d7c344978d498a8cd584cb80"></a><a name="af0606092d7c344978d498a8cd584cb80"></a>鼠标左键点击。</p>
</td>
<td class="cellrowborder" valign="top" width="31.77682231776823%" headers="mcps1.1.5.1.3 "><p id="ac37f0ccad46344649cf03c61d647a192"><a name="ac37f0ccad46344649cf03c61d647a192"></a><a name="ac37f0ccad46344649cf03c61d647a192"></a>map.on('click', callback)</p>
</td>
<td class="cellrowborder" rowspan="8" valign="top" width="31.436856314368566%" headers="mcps1.1.5.1.4 "><p id="p1691921442513"><a name="p1691921442513"></a><a name="p1691921442513"></a>callback回调函数中，参数event对象包含了两个重要的参数：</p>
<a name="ul1091911414251"></a><a name="ul1091911414251"></a><ul id="ul1091911414251"><li>coordinate：墨卡托3857投影经纬度。可以使用HWMapJsSDK.HWMapUtils.epsgToLatLng(event.coordinate)方法，将墨卡托3857投影经纬度转换成日常使用经纬度。</li><li>pixel：屏幕坐标，当前交互点与屏幕左上角的像素距离。</li></ul>
</td>
</tr>
<tr id="r479dc618c0574be5980b76af0cfa21c5"><td class="cellrowborder" valign="top" headers="mcps1.1.5.1.1 "><p id="aa066d4bf461c4db59e5a2e2530769617"><a name="aa066d4bf461c4db59e5a2e2530769617"></a><a name="aa066d4bf461c4db59e5a2e2530769617"></a>singleclick</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.5.1.2 "><p id="ada2da0a5fb2d40908d52be67e510ddb0"><a name="ada2da0a5fb2d40908d52be67e510ddb0"></a><a name="ada2da0a5fb2d40908d52be67e510ddb0"></a>鼠标左键点击。</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.5.1.3 "><p id="a151f70a04c624394a35969cee5b2142f"><a name="a151f70a04c624394a35969cee5b2142f"></a><a name="a151f70a04c624394a35969cee5b2142f"></a>map.on('singleclick', callback)</p>
</td>
</tr>
<tr id="r1610a378929d4560bb5b0d5ec7a21897"><td class="cellrowborder" valign="top" headers="mcps1.1.5.1.1 "><p id="a2f9a66255bbd41b89530d6ec8e96757c"><a name="a2f9a66255bbd41b89530d6ec8e96757c"></a><a name="a2f9a66255bbd41b89530d6ec8e96757c"></a>dblclick</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.5.1.2 "><p id="a0ebf7de4eb944acca23fc57e623eba05"><a name="a0ebf7de4eb944acca23fc57e623eba05"></a><a name="a0ebf7de4eb944acca23fc57e623eba05"></a>鼠标左键双击。</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.5.1.3 "><p id="ad4bbd482acb445b5be3611e0ce974682"><a name="ad4bbd482acb445b5be3611e0ce974682"></a><a name="ad4bbd482acb445b5be3611e0ce974682"></a>map.on('dblclick', callback)</p>
</td>
</tr>
<tr id="reda65a233a9441e481d6f68f1ed41c8e"><td class="cellrowborder" valign="top" headers="mcps1.1.5.1.1 "><p id="a24d22bde8e0c4f4dbdabbd86bb45f947"><a name="a24d22bde8e0c4f4dbdabbd86bb45f947"></a><a name="a24d22bde8e0c4f4dbdabbd86bb45f947"></a>contextmenu</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.5.1.2 "><p id="a6f93a3968fc4452f8a478c9207a81c1d"><a name="a6f93a3968fc4452f8a478c9207a81c1d"></a><a name="a6f93a3968fc4452f8a478c9207a81c1d"></a>鼠标右键点击。</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.5.1.3 "><p id="a0e6a1ca5df09450f889c98597c16ac09"><a name="a0e6a1ca5df09450f889c98597c16ac09"></a><a name="a0e6a1ca5df09450f889c98597c16ac09"></a>map.on('contextmenu', callback)</p>
</td>
</tr>
<tr id="r58ce2d9a0e274cfa9c3b854a011e4db8"><td class="cellrowborder" valign="top" headers="mcps1.1.5.1.1 "><p id="abdc4f5fbc3674e75a905430932221d7c"><a name="abdc4f5fbc3674e75a905430932221d7c"></a><a name="abdc4f5fbc3674e75a905430932221d7c"></a>pointermove</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.5.1.2 "><p id="a2c5cc8ea2cdb4a59bdfca7989329b0ad"><a name="a2c5cc8ea2cdb4a59bdfca7989329b0ad"></a><a name="a2c5cc8ea2cdb4a59bdfca7989329b0ad"></a>鼠标移动。</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.5.1.3 "><p id="ac85eda0630544104a56b085fcdf11c98"><a name="ac85eda0630544104a56b085fcdf11c98"></a><a name="ac85eda0630544104a56b085fcdf11c98"></a>map.on('pointermove', callback)</p>
</td>
</tr>
<tr id="rc4afb96f1e3343f5ad995a5b4d2f7666"><td class="cellrowborder" valign="top" headers="mcps1.1.5.1.1 "><p id="a32fe0ab7a50e4337a2ad553013d299a3"><a name="a32fe0ab7a50e4337a2ad553013d299a3"></a><a name="a32fe0ab7a50e4337a2ad553013d299a3"></a>pointerdown</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.5.1.2 "><p id="adc3f8072036c45458da66621440d92e0"><a name="adc3f8072036c45458da66621440d92e0"></a><a name="adc3f8072036c45458da66621440d92e0"></a>鼠标键按下。</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.5.1.3 "><p id="ac3d95c2beb894180860b2e55b8f0ffb6"><a name="ac3d95c2beb894180860b2e55b8f0ffb6"></a><a name="ac3d95c2beb894180860b2e55b8f0ffb6"></a>map.on('pointerdown', callback)</p>
</td>
</tr>
<tr id="rfc0f94656e7941388baa6a54ea5b56f2"><td class="cellrowborder" valign="top" headers="mcps1.1.5.1.1 "><p id="a167e1047805c48338c4fed09fdf683dd"><a name="a167e1047805c48338c4fed09fdf683dd"></a><a name="a167e1047805c48338c4fed09fdf683dd"></a>pointerup</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.5.1.2 "><p id="afcf8aea091cb46818d9dbd28f126bb01"><a name="afcf8aea091cb46818d9dbd28f126bb01"></a><a name="afcf8aea091cb46818d9dbd28f126bb01"></a>鼠标键松开。</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.5.1.3 "><p id="a66af13e63dc84cd9bc02c947b7f7d8a7"><a name="a66af13e63dc84cd9bc02c947b7f7d8a7"></a><a name="a66af13e63dc84cd9bc02c947b7f7d8a7"></a>map.on('pointerup', callback)</p>
</td>
</tr>
<tr id="row8706152613460"><td class="cellrowborder" valign="top" headers="mcps1.1.5.1.1 "><p id="acf99b50055894b3eb5984eb742d4d5d4"><a name="acf99b50055894b3eb5984eb742d4d5d4"></a><a name="acf99b50055894b3eb5984eb742d4d5d4"></a>pointerdrag</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.5.1.2 "><p id="ac73ea54768134cb59363340d3fca9c29"><a name="ac73ea54768134cb59363340d3fca9c29"></a><a name="ac73ea54768134cb59363340d3fca9c29"></a>地图拖动。</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.5.1.3 "><p id="a4aa67a91ab774d3e824c8d9047c4e680"><a name="a4aa67a91ab774d3e824c8d9047c4e680"></a><a name="a4aa67a91ab774d3e824c8d9047c4e680"></a>map.on('pointerdrag', callback)</p>
</td>
</tr>
<tr id="r47f161eae4394c94b5f96ba468ecf816"><td class="cellrowborder" valign="top" width="19.908009199080094%" headers="mcps1.1.5.1.1 "><p id="a335d315fdd3447cf87a441cebfb84440"><a name="a335d315fdd3447cf87a441cebfb84440"></a><a name="a335d315fdd3447cf87a441cebfb84440"></a>movestart</p>
</td>
<td class="cellrowborder" valign="top" width="16.878312168783122%" headers="mcps1.1.5.1.2 "><p id="a506804dc9295430fb57f69f67850aef8"><a name="a506804dc9295430fb57f69f67850aef8"></a><a name="a506804dc9295430fb57f69f67850aef8"></a>地图开始移动。</p>
</td>
<td class="cellrowborder" valign="top" width="31.77682231776823%" headers="mcps1.1.5.1.3 "><p id="aa2ded4d716be4980aa999fe4c1ff404a"><a name="aa2ded4d716be4980aa999fe4c1ff404a"></a><a name="aa2ded4d716be4980aa999fe4c1ff404a"></a>map.on('movestart', callback)</p>
</td>
<td class="cellrowborder" valign="top" width="31.436856314368566%" headers="mcps1.1.5.1.4 "><p id="p1013043872420"><a name="p1013043872420"></a><a name="p1013043872420"></a>-</p>
</td>
</tr>
<tr id="rf7660271fb744a0fa3c4825f121e5993"><td class="cellrowborder" valign="top" width="19.908009199080094%" headers="mcps1.1.5.1.1 "><p id="adff9b6666b20419cb28c7464ab854491"><a name="adff9b6666b20419cb28c7464ab854491"></a><a name="adff9b6666b20419cb28c7464ab854491"></a>moveend</p>
</td>
<td class="cellrowborder" valign="top" width="16.878312168783122%" headers="mcps1.1.5.1.2 "><p id="a8ff51883897a4624b460a33b9b220218"><a name="a8ff51883897a4624b460a33b9b220218"></a><a name="a8ff51883897a4624b460a33b9b220218"></a>地图结束移动。</p>
</td>
<td class="cellrowborder" valign="top" width="31.77682231776823%" headers="mcps1.1.5.1.3 "><p id="ad6385ef7861c4c0faabd940001a2847e"><a name="ad6385ef7861c4c0faabd940001a2847e"></a><a name="ad6385ef7861c4c0faabd940001a2847e"></a>map.on('moveend', callback)</p>
</td>
<td class="cellrowborder" valign="top" width="31.436856314368566%" headers="mcps1.1.5.1.4 "><p id="p1913063832414"><a name="p1913063832414"></a><a name="p1913063832414"></a>-</p>
</td>
</tr>
<tr id="row6785173815417"><td class="cellrowborder" valign="top" width="19.908009199080094%" headers="mcps1.1.5.1.1 "><p id="p60245124"><a name="p60245124"></a><a name="p60245124"></a>onCenterChanged</p>
</td>
<td class="cellrowborder" valign="top" width="16.878312168783122%" headers="mcps1.1.5.1.2 "><p id="p48016903"><a name="p48016903"></a><a name="p48016903"></a>地图中心点改变。</p>
</td>
<td class="cellrowborder" valign="top" width="31.77682231776823%" headers="mcps1.1.5.1.3 "><p id="p64163914"><a name="p64163914"></a><a name="p64163914"></a>map.onCenterChanged(callback)</p>
</td>
<td class="cellrowborder" valign="top" width="31.436856314368566%" headers="mcps1.1.5.1.4 "><p id="p18130438192416"><a name="p18130438192416"></a><a name="p18130438192416"></a>-</p>
</td>
</tr>
<tr id="row1722114012412"><td class="cellrowborder" valign="top" width="19.908009199080094%" headers="mcps1.1.5.1.1 "><p id="p615201"><a name="p615201"></a><a name="p615201"></a>onHeadingChanged</p>
</td>
<td class="cellrowborder" valign="top" width="16.878312168783122%" headers="mcps1.1.5.1.2 "><p id="p49831357"><a name="p49831357"></a><a name="p49831357"></a>方向改变。</p>
</td>
<td class="cellrowborder" valign="top" width="31.77682231776823%" headers="mcps1.1.5.1.3 "><p id="p9808084"><a name="p9808084"></a><a name="p9808084"></a>map.onHeadingChanged(callback)</p>
</td>
<td class="cellrowborder" valign="top" width="31.436856314368566%" headers="mcps1.1.5.1.4 "><p id="p41303381246"><a name="p41303381246"></a><a name="p41303381246"></a>-</p>
</td>
</tr>
<tr id="row241913417420"><td class="cellrowborder" valign="top" width="19.908009199080094%" headers="mcps1.1.5.1.1 "><p id="p36554200"><a name="p36554200"></a><a name="p36554200"></a>onZoomChanged</p>
</td>
<td class="cellrowborder" valign="top" width="16.878312168783122%" headers="mcps1.1.5.1.2 "><p id="p8100198"><a name="p8100198"></a><a name="p8100198"></a>缩放级别改变。</p>
</td>
<td class="cellrowborder" valign="top" width="31.77682231776823%" headers="mcps1.1.5.1.3 "><p id="p52136268"><a name="p52136268"></a><a name="p52136268"></a>map.onZoomChanged(callback)</p>
</td>
<td class="cellrowborder" valign="top" width="31.436856314368566%" headers="mcps1.1.5.1.4 "><p id="p1130113816247"><a name="p1130113816247"></a><a name="p1130113816247"></a>-</p>
</td>
</tr>
</tbody>
</table>

## CopyrightControlOptions<a name="s54bc0d909e35446eac6552ff59fce17c"></a>

<a name="t3e3e9a602665404b820843792d2320e6"></a>
<table><thead align="left"><tr id="rcad38119e79a4eaea12f88a031d6de97"><th class="cellrowborder" valign="top" width="20%" id="mcps1.1.5.1.1"><p id="a1103ea3cdc0d4e24a3244df453e8910b"><a name="a1103ea3cdc0d4e24a3244df453e8910b"></a><a name="a1103ea3cdc0d4e24a3244df453e8910b"></a><strong id="a0065c58ac3cd4b09be02a668cebf9f03"><a name="a0065c58ac3cd4b09be02a668cebf9f03"></a><a name="a0065c58ac3cd4b09be02a668cebf9f03"></a>参数</strong></p>
</th>
<th class="cellrowborder" valign="top" width="14.000000000000002%" id="mcps1.1.5.1.2"><p id="a58c8f6d6264748a88eb367352f2f4557"><a name="a58c8f6d6264748a88eb367352f2f4557"></a><a name="a58c8f6d6264748a88eb367352f2f4557"></a><strong id="a1d75aeee956b4875ac2354812cdbd107"><a name="a1d75aeee956b4875ac2354812cdbd107"></a><a name="a1d75aeee956b4875ac2354812cdbd107"></a>是否必选</strong></p>
</th>
<th class="cellrowborder" valign="top" width="16%" id="mcps1.1.5.1.3"><p id="a6e15d76768d44a0a8121adf021987cb8"><a name="a6e15d76768d44a0a8121adf021987cb8"></a><a name="a6e15d76768d44a0a8121adf021987cb8"></a><strong id="acd5db556ebcd42dbbf2d9b75d020a61d"><a name="acd5db556ebcd42dbbf2d9b75d020a61d"></a><a name="acd5db556ebcd42dbbf2d9b75d020a61d"></a>参数类型</strong></p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.1.5.1.4"><p id="a25283415d3b246f4bdab20f5d58a0b54"><a name="a25283415d3b246f4bdab20f5d58a0b54"></a><a name="a25283415d3b246f4bdab20f5d58a0b54"></a><strong id="aafe89bfa6bed4dc4b3be9e85aec92a6a"><a name="aafe89bfa6bed4dc4b3be9e85aec92a6a"></a><a name="aafe89bfa6bed4dc4b3be9e85aec92a6a"></a>描述</strong></p>
</th>
</tr>
</thead>
<tbody><tr id="ra7b070705e594740b2a694a6ebe94517"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.1.5.1.1 "><p id="af5d31ba2e90a474792ea520220dc87bd"><a name="af5d31ba2e90a474792ea520220dc87bd"></a><a name="af5d31ba2e90a474792ea520220dc87bd"></a>value</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="a6b50e86341194918a060812fc610cbe4"><a name="a6b50e86341194918a060812fc610cbe4"></a><a name="a6b50e86341194918a060812fc610cbe4"></a>是</p>
</td>
<td class="cellrowborder" valign="top" width="16%" headers="mcps1.1.5.1.3 "><p id="afd1918fbdb764893bc6859d79d5df527"><a name="afd1918fbdb764893bc6859d79d5df527"></a><a name="afd1918fbdb764893bc6859d79d5df527"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="p19855635505"><a name="p19855635505"></a><a name="p19855635505"></a>目前支持文本或HTML的dom元素，dom元素支持以下标签：</p>
<a name="ul511911895017"></a><a name="ul511911895017"></a><ul id="ul511911895017"><li>&lt;font&gt;标签</li><li>&lt;a&gt;标签</li><li>&lt;img&gt;标签</li></ul>
</td>
</tr>
</tbody>
</table>

## MapOptions<a name="s08ea7a96339f4dcf82f72b0e4bad2db5"></a>

<a name="t395b247f55b047fd813af8b18157a963"></a>
<table><thead align="left"><tr id="r87b2c20f88804130be9eede1833cbcc7"><th class="cellrowborder" valign="top" width="22%" id="mcps1.1.5.1.1"><p id="a80f84725d4324ce1aef560c3ee3bc0e8"><a name="a80f84725d4324ce1aef560c3ee3bc0e8"></a><a name="a80f84725d4324ce1aef560c3ee3bc0e8"></a><strong id="aee675e11ac0c46948be9f3003ce2f1ba"><a name="aee675e11ac0c46948be9f3003ce2f1ba"></a><a name="aee675e11ac0c46948be9f3003ce2f1ba"></a>参数</strong></p>
</th>
<th class="cellrowborder" valign="top" width="14.000000000000002%" id="mcps1.1.5.1.2"><p id="aaf5081f898784bc882bfff7ab814094e"><a name="aaf5081f898784bc882bfff7ab814094e"></a><a name="aaf5081f898784bc882bfff7ab814094e"></a><strong id="aa43b978bdc7d4a64a406d9c9764e5019"><a name="aa43b978bdc7d4a64a406d9c9764e5019"></a><a name="aa43b978bdc7d4a64a406d9c9764e5019"></a>是否必选</strong></p>
</th>
<th class="cellrowborder" valign="top" width="16%" id="mcps1.1.5.1.3"><p id="a1aaf5a5d31c343df963b1b40380f2522"><a name="a1aaf5a5d31c343df963b1b40380f2522"></a><a name="a1aaf5a5d31c343df963b1b40380f2522"></a><strong id="af2fb4bbeef2a42c09d388c2a0d47070d"><a name="af2fb4bbeef2a42c09d388c2a0d47070d"></a><a name="af2fb4bbeef2a42c09d388c2a0d47070d"></a>参数类型</strong></p>
</th>
<th class="cellrowborder" valign="top" width="48%" id="mcps1.1.5.1.4"><p id="a94ac4b351abe4d6fa3110ace87c824fc"><a name="a94ac4b351abe4d6fa3110ace87c824fc"></a><a name="a94ac4b351abe4d6fa3110ace87c824fc"></a><strong id="a9e68066ec3e14d9e94af8a2bb1ed74bb"><a name="a9e68066ec3e14d9e94af8a2bb1ed74bb"></a><a name="a9e68066ec3e14d9e94af8a2bb1ed74bb"></a>描述</strong></p>
</th>
</tr>
</thead>
<tbody><tr id="r2b909e14d14447c99a214140559fdd9e"><td class="cellrowborder" valign="top" width="22%" headers="mcps1.1.5.1.1 "><p id="a64da64957cd943b0bb869766813e8eb2"><a name="a64da64957cd943b0bb869766813e8eb2"></a><a name="a64da64957cd943b0bb869766813e8eb2"></a>center</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="a1fe6c3f3ac2049699a78175ca3afe634"><a name="a1fe6c3f3ac2049699a78175ca3afe634"></a><a name="a1fe6c3f3ac2049699a78175ca3afe634"></a>是</p>
</td>
<td class="cellrowborder" valign="top" width="16%" headers="mcps1.1.5.1.3 "><p id="ab86fed31103b42ea95c4476c9d23a1cd"><a name="ab86fed31103b42ea95c4476c9d23a1cd"></a><a name="ab86fed31103b42ea95c4476c9d23a1cd"></a><a href="js-params.md#s45373a8938e040ca9f46c78f4283b385">LatLng</a></p>
</td>
<td class="cellrowborder" valign="top" width="48%" headers="mcps1.1.5.1.4 "><p id="a6129202c5607485b8f607c27363199a9"><a name="a6129202c5607485b8f607c27363199a9"></a><a name="a6129202c5607485b8f607c27363199a9"></a>地图中心点。</p>
</td>
</tr>
<tr id="rdee6557c2f6040f8a9351c0e7c16a679"><td class="cellrowborder" valign="top" width="22%" headers="mcps1.1.5.1.1 "><p id="af57513e6cafd4252af6cd9bad7b34407"><a name="af57513e6cafd4252af6cd9bad7b34407"></a><a name="af57513e6cafd4252af6cd9bad7b34407"></a>copyrightControl</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="a9e6d5b18227941cea2c2400dcc285c65"><a name="a9e6d5b18227941cea2c2400dcc285c65"></a><a name="a9e6d5b18227941cea2c2400dcc285c65"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="16%" headers="mcps1.1.5.1.3 "><p id="a52faef6ce3554c35902f551938111d96"><a name="a52faef6ce3554c35902f551938111d96"></a><a name="a52faef6ce3554c35902f551938111d96"></a>Boolean</p>
</td>
<td class="cellrowborder" valign="top" width="48%" headers="mcps1.1.5.1.4 "><p id="ac679e3101dba46d4bca38bab9c94df64"><a name="ac679e3101dba46d4bca38bab9c94df64"></a><a name="ac679e3101dba46d4bca38bab9c94df64"></a>设置地图是否显示版权，默认false。</p>
</td>
</tr>
<tr id="r7a551a8a2dd349ada3f69b6e0365e8bd"><td class="cellrowborder" valign="top" width="22%" headers="mcps1.1.5.1.1 "><p id="a5c296389901a484b9737f2832a781e85"><a name="a5c296389901a484b9737f2832a781e85"></a><a name="a5c296389901a484b9737f2832a781e85"></a>copyrightControlOptions</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="a9697b65da6774a169eaf4dbd04d046ec"><a name="a9697b65da6774a169eaf4dbd04d046ec"></a><a name="a9697b65da6774a169eaf4dbd04d046ec"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="16%" headers="mcps1.1.5.1.3 "><p id="a0271bea5d7cb4486ac966221946d8b91"><a name="a0271bea5d7cb4486ac966221946d8b91"></a><a name="a0271bea5d7cb4486ac966221946d8b91"></a><a href="#s54bc0d909e35446eac6552ff59fce17c">CopyrightControlOptions</a></p>
</td>
<td class="cellrowborder" valign="top" width="48%" headers="mcps1.1.5.1.4 "><p id="a25aa41793f3c439f9c11e8fd6b948493"><a name="a25aa41793f3c439f9c11e8fd6b948493"></a><a name="a25aa41793f3c439f9c11e8fd6b948493"></a>设置地图的版权内容。</p>
</td>
</tr>
<tr id="re5710a6a3b8145ab842f6cb398200fde"><td class="cellrowborder" valign="top" width="22%" headers="mcps1.1.5.1.1 "><p id="a1276432b7b6748bbb2e09d4c7941bbd4"><a name="a1276432b7b6748bbb2e09d4c7941bbd4"></a><a name="a1276432b7b6748bbb2e09d4c7941bbd4"></a>language</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="a180718659a9c498daa5155aa07e35c74"><a name="a180718659a9c498daa5155aa07e35c74"></a><a name="a180718659a9c498daa5155aa07e35c74"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="16%" headers="mcps1.1.5.1.3 "><p id="af40ada1ded49463e87fd0c57224bfb06"><a name="af40ada1ded49463e87fd0c57224bfb06"></a><a name="af40ada1ded49463e87fd0c57224bfb06"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="48%" headers="mcps1.1.5.1.4 "><p id="a891327e6989c43b587e93fc17ef52617"><a name="a891327e6989c43b587e93fc17ef52617"></a><a name="a891327e6989c43b587e93fc17ef52617"></a>设置地图语言，取值范围参见<a href="#s20ffeadccee7487a922e6d4a7fb49a93">LanguageCode</a>。</p>
<div class="note" id="n94aceeb467214f75890b885fa066349e"><a name="n94aceeb467214f75890b885fa066349e"></a><a name="n94aceeb467214f75890b885fa066349e"></a><span class="notetitle"> 说明： </span><div class="notebody"><p id="af54e3b5063c946beaa03da9c66cd6ad9"><a name="af54e3b5063c946beaa03da9c66cd6ad9"></a><a name="af54e3b5063c946beaa03da9c66cd6ad9"></a>推荐使用BCP 47语言码。</p>
</div></div>
</td>
</tr>
<tr id="r09c89243fc6341d3b2844b7d17c8a59e"><td class="cellrowborder" valign="top" width="22%" headers="mcps1.1.5.1.1 "><p id="a7e5752842a064441b119f71b8aac6ef0"><a name="a7e5752842a064441b119f71b8aac6ef0"></a><a name="a7e5752842a064441b119f71b8aac6ef0"></a>locationControl</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="a005a0cbd476a4b2996c71fb44d18e561"><a name="a005a0cbd476a4b2996c71fb44d18e561"></a><a name="a005a0cbd476a4b2996c71fb44d18e561"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="16%" headers="mcps1.1.5.1.3 "><p id="a8220aa0302114e809dfde40efe5df712"><a name="a8220aa0302114e809dfde40efe5df712"></a><a name="a8220aa0302114e809dfde40efe5df712"></a>Boolean</p>
</td>
<td class="cellrowborder" valign="top" width="48%" headers="mcps1.1.5.1.4 "><p id="a60537818b0fc47b889c5a0344205de71"><a name="a60537818b0fc47b889c5a0344205de71"></a><a name="a60537818b0fc47b889c5a0344205de71"></a>设置地图是否显示当前位置按钮，默认false。</p>
</td>
</tr>
<tr id="rcf9824980c424b6e9e6676bc53580e9b"><td class="cellrowborder" valign="top" width="22%" headers="mcps1.1.5.1.1 "><p id="a78ef31c4db5b4f39af4e59d5aa1e447e"><a name="a78ef31c4db5b4f39af4e59d5aa1e447e"></a><a name="a78ef31c4db5b4f39af4e59d5aa1e447e"></a>mapType</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="a06bbd94b05f04cc5842af369b3fba90b"><a name="a06bbd94b05f04cc5842af369b3fba90b"></a><a name="a06bbd94b05f04cc5842af369b3fba90b"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="16%" headers="mcps1.1.5.1.3 "><p id="ab139011cd57c45519c19f5cedf23a8f8"><a name="ab139011cd57c45519c19f5cedf23a8f8"></a><a name="ab139011cd57c45519c19f5cedf23a8f8"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="48%" headers="mcps1.1.5.1.4 "><p id="aad60e48080274314926160ed49728f63"><a name="aad60e48080274314926160ed49728f63"></a><a name="aad60e48080274314926160ed49728f63"></a>地图类型，暂时仅支持标准地图类型“ROADMAP”。</p>
</td>
</tr>
<tr id="r8293c2a0cf9e4e41978a50e294e950be"><td class="cellrowborder" valign="top" width="22%" headers="mcps1.1.5.1.1 "><p id="ae3e5b5d268de401e91d9debf04ea0b82"><a name="ae3e5b5d268de401e91d9debf04ea0b82"></a><a name="ae3e5b5d268de401e91d9debf04ea0b82"></a>maxZoom</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="a4dc8f77303f6450bad92f27f6cca70ee"><a name="a4dc8f77303f6450bad92f27f6cca70ee"></a><a name="a4dc8f77303f6450bad92f27f6cca70ee"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="16%" headers="mcps1.1.5.1.3 "><p id="aecf4b4328e2540f192ed869fb765b989"><a name="aecf4b4328e2540f192ed869fb765b989"></a><a name="aecf4b4328e2540f192ed869fb765b989"></a>Number</p>
</td>
<td class="cellrowborder" valign="top" width="48%" headers="mcps1.1.5.1.4 "><p id="a1a0c9f475c8244b0abe4c82370c241db"><a name="a1a0c9f475c8244b0abe4c82370c241db"></a><a name="a1a0c9f475c8244b0abe4c82370c241db"></a>地图最大缩放级别，取值范围：[2, 20]，默认20。</p>
</td>
</tr>
<tr id="raaee50e5af144106bfcfc7237acdb44c"><td class="cellrowborder" valign="top" width="22%" headers="mcps1.1.5.1.1 "><p id="aadee7bf04f6b4e7593bfd81ab065a50e"><a name="aadee7bf04f6b4e7593bfd81ab065a50e"></a><a name="aadee7bf04f6b4e7593bfd81ab065a50e"></a>minZoom</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="a89cfd383727d465ab652950945e41dff"><a name="a89cfd383727d465ab652950945e41dff"></a><a name="a89cfd383727d465ab652950945e41dff"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="16%" headers="mcps1.1.5.1.3 "><p id="a9b140e99d3c6473597c54211ccd00086"><a name="a9b140e99d3c6473597c54211ccd00086"></a><a name="a9b140e99d3c6473597c54211ccd00086"></a>Number</p>
</td>
<td class="cellrowborder" valign="top" width="48%" headers="mcps1.1.5.1.4 "><p id="a8b30713e5a844a1586ed09d1a03fe91c"><a name="a8b30713e5a844a1586ed09d1a03fe91c"></a><a name="a8b30713e5a844a1586ed09d1a03fe91c"></a>地图最小缩放级别，取值范围：[2, 20]，默认2。</p>
</td>
</tr>
<tr id="ra5bb762769454d56822171e8899ad081"><td class="cellrowborder" valign="top" width="22%" headers="mcps1.1.5.1.1 "><p id="a12871b5450c646a986f46f510fff7845"><a name="a12871b5450c646a986f46f510fff7845"></a><a name="a12871b5450c646a986f46f510fff7845"></a>navigationControl</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="a72172e47066047fd978e4a5b7d8dec94"><a name="a72172e47066047fd978e4a5b7d8dec94"></a><a name="a72172e47066047fd978e4a5b7d8dec94"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="16%" headers="mcps1.1.5.1.3 "><p id="ac8bb272643584c808617ff7eefc6317b"><a name="ac8bb272643584c808617ff7eefc6317b"></a><a name="ac8bb272643584c808617ff7eefc6317b"></a>Boolean</p>
</td>
<td class="cellrowborder" valign="top" width="48%" headers="mcps1.1.5.1.4 "><p id="ad806f572d5424c2db7e3962ad00ee546"><a name="ad806f572d5424c2db7e3962ad00ee546"></a><a name="ad806f572d5424c2db7e3962ad00ee546"></a>设置地图是否显示平移按钮，默认false。</p>
</td>
</tr>
<tr id="re76bd70e6947411fa22e515c2e3978a3"><td class="cellrowborder" valign="top" width="22%" headers="mcps1.1.5.1.1 "><p id="a95812d755dfb46caab89ef26fa08d627"><a name="a95812d755dfb46caab89ef26fa08d627"></a><a name="a95812d755dfb46caab89ef26fa08d627"></a>political</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="abe4d223e1e4741ac98065a845eab2bf3"><a name="abe4d223e1e4741ac98065a845eab2bf3"></a><a name="abe4d223e1e4741ac98065a845eab2bf3"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="16%" headers="mcps1.1.5.1.3 "><p id="ab9c42995b96047748fee9a2d011a1f15"><a name="ab9c42995b96047748fee9a2d011a1f15"></a><a name="ab9c42995b96047748fee9a2d011a1f15"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="48%" headers="mcps1.1.5.1.4 "><p id="a234037c483ac4c2192da293f35c51f8f"><a name="a234037c483ac4c2192da293f35c51f8f"></a><a name="a234037c483ac4c2192da293f35c51f8f"></a>政治观点，采用ISO 3166-1 alpha-2规范的2位国家码。</p>
<div class="caution" id="note1528292117492"><a name="note1528292117492"></a><a name="note1528292117492"></a><span class="cautiontitle"> 注意： </span><div class="cautionbody"><p id="p52829212494"><a name="p52829212494"></a><a name="p52829212494"></a>该参数已废弃。</p>
</div></div>
</td>
</tr>
<tr id="rdf46b4453e664c87b1425ac92af86278"><td class="cellrowborder" valign="top" width="22%" headers="mcps1.1.5.1.1 "><p id="a92e2bf5dcbf544b59ffff937775e53db"><a name="a92e2bf5dcbf544b59ffff937775e53db"></a><a name="a92e2bf5dcbf544b59ffff937775e53db"></a>rotateControl</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="afb0082c0f9ae4c76bbc103d4bced985e"><a name="afb0082c0f9ae4c76bbc103d4bced985e"></a><a name="afb0082c0f9ae4c76bbc103d4bced985e"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="16%" headers="mcps1.1.5.1.3 "><p id="a1715a7b5136045d98ffaaabf38dff60e"><a name="a1715a7b5136045d98ffaaabf38dff60e"></a><a name="a1715a7b5136045d98ffaaabf38dff60e"></a>Boolean</p>
</td>
<td class="cellrowborder" valign="top" width="48%" headers="mcps1.1.5.1.4 "><p id="abed75e7ab0eb4e3395e1440afef9eb99"><a name="abed75e7ab0eb4e3395e1440afef9eb99"></a><a name="abed75e7ab0eb4e3395e1440afef9eb99"></a>设置地图是否显示指北针，默认false。</p>
</td>
</tr>
<tr id="r62de468a7512469096f609457efa9170"><td class="cellrowborder" valign="top" width="22%" headers="mcps1.1.5.1.1 "><p id="a36df26b98ca84eb1af84bbd264395608"><a name="a36df26b98ca84eb1af84bbd264395608"></a><a name="a36df26b98ca84eb1af84bbd264395608"></a>scaleControl</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="ac5679bb755874b6888d134b3e7b27ba5"><a name="ac5679bb755874b6888d134b3e7b27ba5"></a><a name="ac5679bb755874b6888d134b3e7b27ba5"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="16%" headers="mcps1.1.5.1.3 "><p id="ac2eb4b80c5d64834b5473fa4fe602e57"><a name="ac2eb4b80c5d64834b5473fa4fe602e57"></a><a name="ac2eb4b80c5d64834b5473fa4fe602e57"></a>Boolean</p>
</td>
<td class="cellrowborder" valign="top" width="48%" headers="mcps1.1.5.1.4 "><p id="a8904a80c0395456396143b2da556a0e8"><a name="a8904a80c0395456396143b2da556a0e8"></a><a name="a8904a80c0395456396143b2da556a0e8"></a>设置地图是否显示比例尺，默认false。</p>
</td>
</tr>
<tr id="r6d2a4537b48a434ea0883d89f54ff805"><td class="cellrowborder" valign="top" width="22%" headers="mcps1.1.5.1.1 "><p id="a2d124022e36643399f8f5f16c5b2a387"><a name="a2d124022e36643399f8f5f16c5b2a387"></a><a name="a2d124022e36643399f8f5f16c5b2a387"></a>zoom</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="afcc3d4738ce0456a85abd37b0e16fa9e"><a name="afcc3d4738ce0456a85abd37b0e16fa9e"></a><a name="afcc3d4738ce0456a85abd37b0e16fa9e"></a>是</p>
</td>
<td class="cellrowborder" valign="top" width="16%" headers="mcps1.1.5.1.3 "><p id="af7b76a1fc0984f6a8d4be6b9f7f17b35"><a name="af7b76a1fc0984f6a8d4be6b9f7f17b35"></a><a name="af7b76a1fc0984f6a8d4be6b9f7f17b35"></a>Number</p>
</td>
<td class="cellrowborder" valign="top" width="48%" headers="mcps1.1.5.1.4 "><p id="a07c7a839891f492aa2db0f39d2e9b995"><a name="a07c7a839891f492aa2db0f39d2e9b995"></a><a name="a07c7a839891f492aa2db0f39d2e9b995"></a>地图初始化时缩放级别。</p>
</td>
</tr>
<tr id="ra0135df74ef9410d84bb55b78919350e"><td class="cellrowborder" valign="top" width="22%" headers="mcps1.1.5.1.1 "><p id="a8f8fbead9b6b4e839ba0bd0ba52ea9e5"><a name="a8f8fbead9b6b4e839ba0bd0ba52ea9e5"></a><a name="a8f8fbead9b6b4e839ba0bd0ba52ea9e5"></a>zoomSlider</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="ab79aed8121ed4fe2a4521501746d3898"><a name="ab79aed8121ed4fe2a4521501746d3898"></a><a name="ab79aed8121ed4fe2a4521501746d3898"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="16%" headers="mcps1.1.5.1.3 "><p id="ac17c82a9fd6043e0a73484bf365ad6b1"><a name="ac17c82a9fd6043e0a73484bf365ad6b1"></a><a name="ac17c82a9fd6043e0a73484bf365ad6b1"></a>Boolean</p>
</td>
<td class="cellrowborder" valign="top" width="48%" headers="mcps1.1.5.1.4 "><p id="ae47ff837610b4525a188465076abcf31"><a name="ae47ff837610b4525a188465076abcf31"></a><a name="ae47ff837610b4525a188465076abcf31"></a>设置地图是否显示缩放条，默认false。</p>
</td>
</tr>
<tr id="rd41268c5951541d18b375d474c7f0198"><td class="cellrowborder" valign="top" width="22%" headers="mcps1.1.5.1.1 "><p id="aaa63641d7558437580093063682d54d8"><a name="aaa63641d7558437580093063682d54d8"></a><a name="aaa63641d7558437580093063682d54d8"></a>zoomControl</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="a2bf4c262b4094721b6f6b390b051b883"><a name="a2bf4c262b4094721b6f6b390b051b883"></a><a name="a2bf4c262b4094721b6f6b390b051b883"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="16%" headers="mcps1.1.5.1.3 "><p id="adfbaf45ad0384c579cfc59d8e197171a"><a name="adfbaf45ad0384c579cfc59d8e197171a"></a><a name="adfbaf45ad0384c579cfc59d8e197171a"></a>Boolean</p>
</td>
<td class="cellrowborder" valign="top" width="48%" headers="mcps1.1.5.1.4 "><p id="a59e3d9fed05b47368c33f3bce8afd2c3"><a name="a59e3d9fed05b47368c33f3bce8afd2c3"></a><a name="a59e3d9fed05b47368c33f3bce8afd2c3"></a>设置地图是否显示缩放按钮，默认true。</p>
</td>
</tr>
<tr id="row376413822711"><td class="cellrowborder" valign="top" width="22%" headers="mcps1.1.5.1.1 "><p id="p1776518192720"><a name="p1776518192720"></a><a name="p1776518192720"></a>sourceType</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="p1765585277"><a name="p1765585277"></a><a name="p1765585277"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="16%" headers="mcps1.1.5.1.3 "><p id="p137652812716"><a name="p137652812716"></a><a name="p137652812716"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="48%" headers="mcps1.1.5.1.4 "><p id="p576513811272"><a name="p576513811272"></a><a name="p576513811272"></a>设置地图加载时使用的瓦片类型，支持vector（矢量）或raster（栅格），默认为vector。</p>
</td>
</tr>
</tbody>
</table>

## ScaleControlOptions<a name="s25716cbc6ea049f89621828a4b96ffe9"></a>

<a name="t06354b24c05440a68f4a8f93f06986cb"></a>
<table><thead align="left"><tr id="r70e55e2baea04bd7978d043cc3582fe7"><th class="cellrowborder" valign="top" width="20%" id="mcps1.1.5.1.1"><p id="abbb4fbe1f3bf4069bdf030507dc8a079"><a name="abbb4fbe1f3bf4069bdf030507dc8a079"></a><a name="abbb4fbe1f3bf4069bdf030507dc8a079"></a><strong id="a33d5378752a8460aaa2a982c11958a97"><a name="a33d5378752a8460aaa2a982c11958a97"></a><a name="a33d5378752a8460aaa2a982c11958a97"></a>参数</strong></p>
</th>
<th class="cellrowborder" valign="top" width="14.000000000000002%" id="mcps1.1.5.1.2"><p id="ad4383451fbbc49b0ab06f7e487b39cd3"><a name="ad4383451fbbc49b0ab06f7e487b39cd3"></a><a name="ad4383451fbbc49b0ab06f7e487b39cd3"></a><strong id="a85bd5d15b2614ab799c59884fbc3bc1f"><a name="a85bd5d15b2614ab799c59884fbc3bc1f"></a><a name="a85bd5d15b2614ab799c59884fbc3bc1f"></a>是否必选</strong></p>
</th>
<th class="cellrowborder" valign="top" width="16%" id="mcps1.1.5.1.3"><p id="a13dd7be561d24c60bdb6cbdaefd59a3f"><a name="a13dd7be561d24c60bdb6cbdaefd59a3f"></a><a name="a13dd7be561d24c60bdb6cbdaefd59a3f"></a><strong id="af08d1ca3b5294e7bb103c1273e3e4893"><a name="af08d1ca3b5294e7bb103c1273e3e4893"></a><a name="af08d1ca3b5294e7bb103c1273e3e4893"></a>参数类型</strong></p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.1.5.1.4"><p id="ace1bee83f43b478793d9a4cb17bde3ec"><a name="ace1bee83f43b478793d9a4cb17bde3ec"></a><a name="ace1bee83f43b478793d9a4cb17bde3ec"></a><strong id="a4016d1516f1841e3a323563950794c7a"><a name="a4016d1516f1841e3a323563950794c7a"></a><a name="a4016d1516f1841e3a323563950794c7a"></a>描述</strong></p>
</th>
</tr>
</thead>
<tbody><tr id="rc22b20d39606448b90d6f4b26ae51e91"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.1.5.1.1 "><p id="ae9ba678b215d4156b4f871efacabe97e"><a name="ae9ba678b215d4156b4f871efacabe97e"></a><a name="ae9ba678b215d4156b4f871efacabe97e"></a>units</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="ab90f77d29e5c4aa7af0da5b8dbca2cee"><a name="ab90f77d29e5c4aa7af0da5b8dbca2cee"></a><a name="ab90f77d29e5c4aa7af0da5b8dbca2cee"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="16%" headers="mcps1.1.5.1.3 "><p id="a87edfda32f9d456895085c33b4e8c52f"><a name="a87edfda32f9d456895085c33b4e8c52f"></a><a name="a87edfda32f9d456895085c33b4e8c52f"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="a9e4cb8e31d424871b9c12c1ee938c536"><a name="a9e4cb8e31d424871b9c12c1ee938c536"></a><a name="a9e4cb8e31d424871b9c12c1ee938c536"></a>比例尺单位。取值包括：imperial（英制英寸）、nautical（海里）、metric（公制），默认为metric。</p>
</td>
</tr>
</tbody>
</table>

## LanguageCode<a name="s20ffeadccee7487a922e6d4a7fb49a93"></a>

<a name="table18568536173213"></a>
<table><thead align="left"><tr id="row2056813613210"><th class="cellrowborder" valign="top" width="33.33333333333333%" id="mcps1.1.4.1.1"><p id="p756863613216"><a name="p756863613216"></a><a name="p756863613216"></a><strong id="b10891912113310"><a name="b10891912113310"></a><a name="b10891912113310"></a>ISO-639-2</strong></p>
</th>
<th class="cellrowborder" valign="top" width="33.33333333333333%" id="mcps1.1.4.1.2"><p id="p1568636153216"><a name="p1568636153216"></a><a name="p1568636153216"></a><strong id="b6563192338"><a name="b6563192338"></a><a name="b6563192338"></a>BCP 47</strong></p>
</th>
<th class="cellrowborder" valign="top" width="33.33333333333333%" id="mcps1.1.4.1.3"><p id="p195681336163219"><a name="p195681336163219"></a><a name="p195681336163219"></a><strong id="b117991724203320"><a name="b117991724203320"></a><a name="b117991724203320"></a>中文名称</strong></p>
</th>
</tr>
</thead>
<tbody><tr id="row1956893673213"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p1166462720349"><a name="p1166462720349"></a><a name="p1166462720349"></a>AFR</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p4981161003510"><a name="p4981161003510"></a><a name="p4981161003510"></a>af</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p2071425293617"><a name="p2071425293617"></a><a name="p2071425293617"></a>南非语</p>
</td>
</tr>
<tr id="row556813368329"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p11664102783418"><a name="p11664102783418"></a><a name="p11664102783418"></a>SQI</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p1298112101359"><a name="p1298112101359"></a><a name="p1298112101359"></a>sq</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p15714135215366"><a name="p15714135215366"></a><a name="p15714135215366"></a>阿尔巴尼亚语</p>
</td>
</tr>
<tr id="row9568113633212"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p136641272343"><a name="p136641272343"></a><a name="p136641272343"></a>AMH</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p19811210193520"><a name="p19811210193520"></a><a name="p19811210193520"></a>am</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p1871415525364"><a name="p1871415525364"></a><a name="p1871415525364"></a>阿姆哈拉语</p>
</td>
</tr>
<tr id="row8569183613212"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p1266402763415"><a name="p1266402763415"></a><a name="p1266402763415"></a>AMH</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p15981310183517"><a name="p15981310183517"></a><a name="p15981310183517"></a>am-Latn</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p871445273615"><a name="p871445273615"></a><a name="p871445273615"></a>阿姆哈拉语</p>
</td>
</tr>
<tr id="row35691136193214"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p1666442743411"><a name="p1666442743411"></a><a name="p1666442743411"></a>ARA</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p17981210163516"><a name="p17981210163516"></a><a name="p17981210163516"></a>ar</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p127141152103613"><a name="p127141152103613"></a><a name="p127141152103613"></a>阿拉伯语</p>
</td>
</tr>
<tr id="row15694364329"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p96641273347"><a name="p96641273347"></a><a name="p96641273347"></a>HYE</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p17981191033516"><a name="p17981191033516"></a><a name="p17981191033516"></a>hy</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p1671455215365"><a name="p1671455215365"></a><a name="p1671455215365"></a>亚美尼亚语</p>
</td>
</tr>
<tr id="row14569836103212"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p1066432723414"><a name="p1066432723414"></a><a name="p1066432723414"></a>HYE</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p1398191013517"><a name="p1398191013517"></a><a name="p1398191013517"></a>hy-Latn</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p1671445218368"><a name="p1671445218368"></a><a name="p1671445218368"></a>亚美尼亚语</p>
</td>
</tr>
<tr id="row175691336103215"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p2664112718346"><a name="p2664112718346"></a><a name="p2664112718346"></a>ASM</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p598101033514"><a name="p598101033514"></a><a name="p598101033514"></a>as-Latn</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p1171495219368"><a name="p1171495219368"></a><a name="p1171495219368"></a>阿萨姆语</p>
</td>
</tr>
<tr id="row556993633215"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p166641427133417"><a name="p166641427133417"></a><a name="p166641427133417"></a>ASM</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p10981110103516"><a name="p10981110103516"></a><a name="p10981110103516"></a>as</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p971485283617"><a name="p971485283617"></a><a name="p971485283617"></a>阿萨姆语</p>
</td>
</tr>
<tr id="row3569036193212"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p7664122712345"><a name="p7664122712345"></a><a name="p7664122712345"></a>AYM</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p598131013352"><a name="p598131013352"></a><a name="p598131013352"></a>ay</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p17714452113617"><a name="p17714452113617"></a><a name="p17714452113617"></a>艾马拉语</p>
</td>
</tr>
<tr id="row105691936173210"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p1664527193418"><a name="p1664527193418"></a><a name="p1664527193418"></a>AZE</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p5981111093512"><a name="p5981111093512"></a><a name="p5981111093512"></a>az</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p17142525362"><a name="p17142525362"></a><a name="p17142525362"></a>阿塞拜疆语</p>
</td>
</tr>
<tr id="row16569536133211"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p136646279348"><a name="p136646279348"></a><a name="p136646279348"></a>BAQ</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p169816108356"><a name="p169816108356"></a><a name="p169816108356"></a>eu</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p12714452193617"><a name="p12714452193617"></a><a name="p12714452193617"></a>巴斯克语</p>
</td>
</tr>
<tr id="row35701436143212"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p16664162763417"><a name="p16664162763417"></a><a name="p16664162763417"></a>BEL</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p19982191053519"><a name="p19982191053519"></a><a name="p19982191053519"></a>be-Latn</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p171425211365"><a name="p171425211365"></a><a name="p171425211365"></a>白俄罗斯语</p>
</td>
</tr>
<tr id="row10570336153213"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p4664192713348"><a name="p4664192713348"></a><a name="p4664192713348"></a>BEL</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p698211003519"><a name="p698211003519"></a><a name="p698211003519"></a>be</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p67151529360"><a name="p67151529360"></a><a name="p67151529360"></a>白俄罗斯语</p>
</td>
</tr>
<tr id="row19570123619328"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p106641827173411"><a name="p106641827173411"></a><a name="p106641827173411"></a>BEN</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p11982101010356"><a name="p11982101010356"></a><a name="p11982101010356"></a>bn-Latn</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p207151527366"><a name="p207151527366"></a><a name="p207151527366"></a>孟加拉语</p>
</td>
</tr>
<tr id="row12570193619324"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p16641327123416"><a name="p16641327123416"></a><a name="p16641327123416"></a>BEN</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p1498271019358"><a name="p1498271019358"></a><a name="p1498271019358"></a>bn</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p207151852143616"><a name="p207151852143616"></a><a name="p207151852143616"></a>孟加拉语</p>
</td>
</tr>
<tr id="row65701836153216"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p26651827123418"><a name="p26651827123418"></a><a name="p26651827123418"></a>BIS</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p198221012356"><a name="p198221012356"></a><a name="p198221012356"></a>bi</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p147151652133614"><a name="p147151652133614"></a><a name="p147151652133614"></a>比斯拉马语</p>
</td>
</tr>
<tr id="row18570113619320"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p466517272348"><a name="p466517272348"></a><a name="p466517272348"></a>BOS</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p198221019356"><a name="p198221019356"></a><a name="p198221019356"></a>bs</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p20715135214369"><a name="p20715135214369"></a><a name="p20715135214369"></a>波斯尼亚语</p>
</td>
</tr>
<tr id="row9570636153210"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p156651627123412"><a name="p156651627123412"></a><a name="p156651627123412"></a>BRE</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p2098241083516"><a name="p2098241083516"></a><a name="p2098241083516"></a>br</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p2071555210366"><a name="p2071555210366"></a><a name="p2071555210366"></a>布列塔尼语</p>
</td>
</tr>
<tr id="row14570143612329"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p2665627143412"><a name="p2665627143412"></a><a name="p2665627143412"></a>BUL</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p15982310143512"><a name="p15982310143512"></a><a name="p15982310143512"></a>bg-Latn</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p871516525363"><a name="p871516525363"></a><a name="p871516525363"></a>保加利亚语</p>
</td>
</tr>
<tr id="row1157013369326"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p76651927133417"><a name="p76651927133417"></a><a name="p76651927133417"></a>BUL</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p159826100351"><a name="p159826100351"></a><a name="p159826100351"></a>bg</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p127151052163617"><a name="p127151052163617"></a><a name="p127151052163617"></a>保加利亚语</p>
</td>
</tr>
<tr id="row4571193623214"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p2066582712344"><a name="p2066582712344"></a><a name="p2066582712344"></a>BUR</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p14982310193516"><a name="p14982310193516"></a><a name="p14982310193516"></a>my</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p571585273618"><a name="p571585273618"></a><a name="p571585273618"></a>缅甸语</p>
</td>
</tr>
<tr id="row12571163618327"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p18665227103419"><a name="p18665227103419"></a><a name="p18665227103419"></a>CAT</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p189825107355"><a name="p189825107355"></a><a name="p189825107355"></a>ca</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p371505283618"><a name="p371505283618"></a><a name="p371505283618"></a>加泰罗尼亚语</p>
</td>
</tr>
<tr id="row457133623212"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p866532713415"><a name="p866532713415"></a><a name="p866532713415"></a>CHI</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p798261073519"><a name="p798261073519"></a><a name="p798261073519"></a>zh</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p1771517529364"><a name="p1771517529364"></a><a name="p1771517529364"></a>中文简体</p>
</td>
</tr>
<tr id="row10571193683218"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p1665172723413"><a name="p1665172723413"></a><a name="p1665172723413"></a>ZHO</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p1598231013514"><a name="p1598231013514"></a><a name="p1598231013514"></a>zh-Hant</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p9715155217366"><a name="p9715155217366"></a><a name="p9715155217366"></a>中文繁体</p>
</td>
</tr>
<tr id="row20571113618326"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p186651327133419"><a name="p186651327133419"></a><a name="p186651327133419"></a>CES</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p59829106352"><a name="p59829106352"></a><a name="p59829106352"></a>cs</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p6715452163613"><a name="p6715452163613"></a><a name="p6715452163613"></a>捷克语</p>
</td>
</tr>
<tr id="row19571193633216"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p766522716346"><a name="p766522716346"></a><a name="p766522716346"></a>DAN</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p19982121033510"><a name="p19982121033510"></a><a name="p19982121033510"></a>da</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p3715115243618"><a name="p3715115243618"></a><a name="p3715115243618"></a>丹麦语</p>
</td>
</tr>
<tr id="row457183616329"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p13665927103420"><a name="p13665927103420"></a><a name="p13665927103420"></a>DIV</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p209821310143513"><a name="p209821310143513"></a><a name="p209821310143513"></a>dv</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p177159522367"><a name="p177159522367"></a><a name="p177159522367"></a>迪维西语</p>
</td>
</tr>
<tr id="row14571123614327"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p36657275344"><a name="p36657275344"></a><a name="p36657275344"></a>NLD</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p189821710153520"><a name="p189821710153520"></a><a name="p189821710153520"></a>nl</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p197151052113617"><a name="p197151052113617"></a><a name="p197151052113617"></a>荷兰语</p>
</td>
</tr>
<tr id="row657243613322"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p266516275344"><a name="p266516275344"></a><a name="p266516275344"></a>DZO</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p169821110183518"><a name="p169821110183518"></a><a name="p169821110183518"></a>dz</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p8715125213367"><a name="p8715125213367"></a><a name="p8715125213367"></a>宗喀语</p>
</td>
</tr>
<tr id="row11572173643217"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p146651427163416"><a name="p146651427163416"></a><a name="p146651427163416"></a>ENG</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p11982121020358"><a name="p11982121020358"></a><a name="p11982121020358"></a>en</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p27151952183610"><a name="p27151952183610"></a><a name="p27151952183610"></a>英语</p>
</td>
</tr>
<tr id="row3572173615329"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p15665132773419"><a name="p15665132773419"></a><a name="p15665132773419"></a>EST</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p498211012357"><a name="p498211012357"></a><a name="p498211012357"></a>et</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p13715195213612"><a name="p13715195213612"></a><a name="p13715195213612"></a>爱沙尼亚语</p>
</td>
</tr>
<tr id="row14572133611327"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p206651327163416"><a name="p206651327163416"></a><a name="p206651327163416"></a>FAO</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p99831210143519"><a name="p99831210143519"></a><a name="p99831210143519"></a>fo</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p871575216361"><a name="p871575216361"></a><a name="p871575216361"></a>法罗语</p>
</td>
</tr>
<tr id="row65721936193216"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p1966512783416"><a name="p1966512783416"></a><a name="p1966512783416"></a>FIJ</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p159831107359"><a name="p159831107359"></a><a name="p159831107359"></a>fj</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p8716185233617"><a name="p8716185233617"></a><a name="p8716185233617"></a>斐济语</p>
</td>
</tr>
<tr id="row4572203618324"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p12665142753417"><a name="p12665142753417"></a><a name="p12665142753417"></a>FIL</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p298314108356"><a name="p298314108356"></a><a name="p298314108356"></a>tl</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p13716155233620"><a name="p13716155233620"></a><a name="p13716155233620"></a>菲律宾语</p>
</td>
</tr>
<tr id="row1857213617327"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p666522753414"><a name="p666522753414"></a><a name="p666522753414"></a>FIN</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p1498331019354"><a name="p1498331019354"></a><a name="p1498331019354"></a>fi</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p2716752203616"><a name="p2716752203616"></a><a name="p2716752203616"></a>芬兰语</p>
</td>
</tr>
<tr id="row457216368324"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p26661277346"><a name="p26661277346"></a><a name="p26661277346"></a>FRA</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p498318102353"><a name="p498318102353"></a><a name="p498318102353"></a>fr</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p17716175243612"><a name="p17716175243612"></a><a name="p17716175243612"></a>法语</p>
</td>
</tr>
<tr id="row115721036173214"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p466611270345"><a name="p466611270345"></a><a name="p466611270345"></a>FRY</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p11983110163518"><a name="p11983110163518"></a><a name="p11983110163518"></a>fy</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p13716185218361"><a name="p13716185218361"></a><a name="p13716185218361"></a>弗里斯兰语</p>
</td>
</tr>
<tr id="row1657323673211"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p1766642763414"><a name="p1766642763414"></a><a name="p1766642763414"></a>KAT</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p698391020354"><a name="p698391020354"></a><a name="p698391020354"></a>ka</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p13716552103617"><a name="p13716552103617"></a><a name="p13716552103617"></a>格鲁吉亚语</p>
</td>
</tr>
<tr id="row16573183663212"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p9666202716348"><a name="p9666202716348"></a><a name="p9666202716348"></a>KAT</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p7983191018359"><a name="p7983191018359"></a><a name="p7983191018359"></a>ka-Latn</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p12716125223616"><a name="p12716125223616"></a><a name="p12716125223616"></a>格鲁吉亚语</p>
</td>
</tr>
<tr id="row1957373673217"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p16666202710347"><a name="p16666202710347"></a><a name="p16666202710347"></a>DEU</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p1998371011354"><a name="p1998371011354"></a><a name="p1998371011354"></a>de</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p871625214369"><a name="p871625214369"></a><a name="p871625214369"></a>德语</p>
</td>
</tr>
<tr id="row1857323613214"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p1566612710345"><a name="p1566612710345"></a><a name="p1566612710345"></a>GLA</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p1983171043513"><a name="p1983171043513"></a><a name="p1983171043513"></a>gd</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p18716175218362"><a name="p18716175218362"></a><a name="p18716175218362"></a>苏格兰盖尔语</p>
</td>
</tr>
<tr id="row357319363322"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p176677272341"><a name="p176677272341"></a><a name="p176677272341"></a>GLE</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p8983410193517"><a name="p8983410193517"></a><a name="p8983410193517"></a>ga</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p4716175263610"><a name="p4716175263610"></a><a name="p4716175263610"></a>爱尔兰语</p>
</td>
</tr>
<tr id="row16573153633218"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p1266772711342"><a name="p1266772711342"></a><a name="p1266772711342"></a>GLG</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p498331053514"><a name="p498331053514"></a><a name="p498331053514"></a>gl</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p071614526363"><a name="p071614526363"></a><a name="p071614526363"></a>加利西亚语</p>
</td>
</tr>
<tr id="row11573203611323"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p116671227103417"><a name="p116671227103417"></a><a name="p116671227103417"></a>ELL</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p1098331013356"><a name="p1098331013356"></a><a name="p1098331013356"></a>el</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p9716195217362"><a name="p9716195217362"></a><a name="p9716195217362"></a>希腊语</p>
</td>
</tr>
<tr id="row657333611327"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p3667132715344"><a name="p3667132715344"></a><a name="p3667132715344"></a>ELL</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p149836104356"><a name="p149836104356"></a><a name="p149836104356"></a>el-Latn</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p671612527362"><a name="p671612527362"></a><a name="p671612527362"></a>希腊语</p>
</td>
</tr>
<tr id="row17574103673210"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p566717273343"><a name="p566717273343"></a><a name="p566717273343"></a>GRN</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p698311093519"><a name="p698311093519"></a><a name="p698311093519"></a>gn</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p4716115213619"><a name="p4716115213619"></a><a name="p4716115213619"></a>瓜拉尼语</p>
</td>
</tr>
<tr id="row2574136203216"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p106674275343"><a name="p106674275343"></a><a name="p106674275343"></a>GUJ</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p1198321019354"><a name="p1198321019354"></a><a name="p1198321019354"></a>gu-Latn</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p97164527367"><a name="p97164527367"></a><a name="p97164527367"></a>古吉拉特语</p>
</td>
</tr>
<tr id="row17574123616326"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p9667182723415"><a name="p9667182723415"></a><a name="p9667182723415"></a>GUJ</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p14983191063512"><a name="p14983191063512"></a><a name="p14983191063512"></a>gu</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p1571610528363"><a name="p1571610528363"></a><a name="p1571610528363"></a>古吉拉特语</p>
</td>
</tr>
<tr id="row15574836143214"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p15667112719344"><a name="p15667112719344"></a><a name="p15667112719344"></a>HAT</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p5983510143518"><a name="p5983510143518"></a><a name="p5983510143518"></a>ht</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p15716135216368"><a name="p15716135216368"></a><a name="p15716135216368"></a>海地法国克里奥尔语</p>
</td>
</tr>
<tr id="row1057483617320"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p366782715340"><a name="p366782715340"></a><a name="p366782715340"></a>HAU</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p7983101063510"><a name="p7983101063510"></a><a name="p7983101063510"></a>ha</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p071619523369"><a name="p071619523369"></a><a name="p071619523369"></a>豪萨语</p>
</td>
</tr>
<tr id="row75745364324"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p16667152712347"><a name="p16667152712347"></a><a name="p16667152712347"></a>HEB</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p6983110133519"><a name="p6983110133519"></a><a name="p6983110133519"></a>he-Latn</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p8716165210363"><a name="p8716165210363"></a><a name="p8716165210363"></a>希伯来语</p>
</td>
</tr>
<tr id="row155741036153213"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p1766712733415"><a name="p1766712733415"></a><a name="p1766712733415"></a>HEB</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p139841310203520"><a name="p139841310203520"></a><a name="p139841310203520"></a>he</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p27161523367"><a name="p27161523367"></a><a name="p27161523367"></a>希伯来语</p>
</td>
</tr>
<tr id="row857493663215"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p1766716271342"><a name="p1766716271342"></a><a name="p1766716271342"></a>HIN</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p19984191083510"><a name="p19984191083510"></a><a name="p19984191083510"></a>hi-Latn</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p1971614525367"><a name="p1971614525367"></a><a name="p1971614525367"></a>印地语</p>
</td>
</tr>
<tr id="row125751636143217"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p566722763410"><a name="p566722763410"></a><a name="p566722763410"></a>HIN</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p1998461018352"><a name="p1998461018352"></a><a name="p1998461018352"></a>hi</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p16717152183617"><a name="p16717152183617"></a><a name="p16717152183617"></a>印地语</p>
</td>
</tr>
<tr id="row16575133610323"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p666702710342"><a name="p666702710342"></a><a name="p666702710342"></a>HMO</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p1198410100358"><a name="p1198410100358"></a><a name="p1198410100358"></a>ho</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p18717145263619"><a name="p18717145263619"></a><a name="p18717145263619"></a>希里莫图语</p>
</td>
</tr>
<tr id="row557511364321"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p1966852723417"><a name="p1966852723417"></a><a name="p1966852723417"></a>HUN</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p129842108352"><a name="p129842108352"></a><a name="p129842108352"></a>hu</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p107173526365"><a name="p107173526365"></a><a name="p107173526365"></a>匈牙利语</p>
</td>
</tr>
<tr id="row18575113693210"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p10668132773420"><a name="p10668132773420"></a><a name="p10668132773420"></a>IBO</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p49851810123520"><a name="p49851810123520"></a><a name="p49851810123520"></a>ig</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p1171795223611"><a name="p1171795223611"></a><a name="p1171795223611"></a>伊博语</p>
</td>
</tr>
<tr id="row11575113616324"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p12668162723412"><a name="p12668162723412"></a><a name="p12668162723412"></a>ISL</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p109853105357"><a name="p109853105357"></a><a name="p109853105357"></a>is</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p15717125218368"><a name="p15717125218368"></a><a name="p15717125218368"></a>冰岛语</p>
</td>
</tr>
<tr id="row145751361320"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p11668152773418"><a name="p11668152773418"></a><a name="p11668152773418"></a>IKU</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p1498541053520"><a name="p1498541053520"></a><a name="p1498541053520"></a>iu</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p1471712523369"><a name="p1471712523369"></a><a name="p1471712523369"></a>因纽特语</p>
</td>
</tr>
<tr id="row19575133616321"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p1766862715341"><a name="p1766862715341"></a><a name="p1766862715341"></a>IND</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p698581013357"><a name="p698581013357"></a><a name="p698581013357"></a>id</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p1571714526364"><a name="p1571714526364"></a><a name="p1571714526364"></a>印尼语</p>
</td>
</tr>
<tr id="row175758362326"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p15668102763412"><a name="p15668102763412"></a><a name="p15668102763412"></a>ITA</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p9985110103515"><a name="p9985110103515"></a><a name="p9985110103515"></a>it</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p17172521369"><a name="p17172521369"></a><a name="p17172521369"></a>意大利语</p>
</td>
</tr>
<tr id="row145761636113219"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p12668127103417"><a name="p12668127103417"></a><a name="p12668127103417"></a>JPN</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p15985510203518"><a name="p15985510203518"></a><a name="p15985510203518"></a>ja-Latn</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p19717135213366"><a name="p19717135213366"></a><a name="p19717135213366"></a>日语</p>
</td>
</tr>
<tr id="row357617361321"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p1466818276346"><a name="p1466818276346"></a><a name="p1466818276346"></a>JPN</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p198571012353"><a name="p198571012353"></a><a name="p198571012353"></a>ja</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p171715243612"><a name="p171715243612"></a><a name="p171715243612"></a>日语</p>
</td>
</tr>
<tr id="row185761136183210"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p9668162716348"><a name="p9668162716348"></a><a name="p9668162716348"></a>KAL</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p398531003514"><a name="p398531003514"></a><a name="p398531003514"></a>kl</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p1971735211361"><a name="p1971735211361"></a><a name="p1971735211361"></a>格陵兰语</p>
</td>
</tr>
<tr id="row957623603211"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p14668192710345"><a name="p14668192710345"></a><a name="p14668192710345"></a>KAN</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p1498510101358"><a name="p1498510101358"></a><a name="p1498510101358"></a>kn-Latn</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p1771735211369"><a name="p1771735211369"></a><a name="p1771735211369"></a>卡纳达语</p>
</td>
</tr>
<tr id="row85761236113210"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p36681627183415"><a name="p36681627183415"></a><a name="p36681627183415"></a>KAN</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p12985710173515"><a name="p12985710173515"></a><a name="p12985710173515"></a>kn</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p571719526361"><a name="p571719526361"></a><a name="p571719526361"></a>卡纳达语</p>
</td>
</tr>
<tr id="row10576173633219"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p3668122715345"><a name="p3668122715345"></a><a name="p3668122715345"></a>KAS</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p4985121014356"><a name="p4985121014356"></a><a name="p4985121014356"></a>ks</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p27171452143611"><a name="p27171452143611"></a><a name="p27171452143611"></a>克什米尔语</p>
</td>
</tr>
<tr id="row45761361324"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p566862718348"><a name="p566862718348"></a><a name="p566862718348"></a>KAZ</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p1698513103358"><a name="p1698513103358"></a><a name="p1698513103358"></a>kk-Latn</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p971785253619"><a name="p971785253619"></a><a name="p971785253619"></a>哈萨克语</p>
</td>
</tr>
<tr id="row7576836163210"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p19668152753419"><a name="p19668152753419"></a><a name="p19668152753419"></a>KAZ</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p1298521019356"><a name="p1298521019356"></a><a name="p1298521019356"></a>kk</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p117171852153612"><a name="p117171852153612"></a><a name="p117171852153612"></a>哈萨克语</p>
</td>
</tr>
<tr id="row45761736173212"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p6668102713344"><a name="p6668102713344"></a><a name="p6668102713344"></a>KHM</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p5985510173514"><a name="p5985510173514"></a><a name="p5985510173514"></a>km-Latn</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p371718529369"><a name="p371718529369"></a><a name="p371718529369"></a>高棉语</p>
</td>
</tr>
<tr id="row15577143616325"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p10668027193410"><a name="p10668027193410"></a><a name="p10668027193410"></a>KHM</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p1798571013356"><a name="p1798571013356"></a><a name="p1798571013356"></a>km</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p4717952173615"><a name="p4717952173615"></a><a name="p4717952173615"></a>高棉语</p>
</td>
</tr>
<tr id="row18577173633214"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p116681527133415"><a name="p116681527133415"></a><a name="p116681527133415"></a>KIN</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p498514100358"><a name="p498514100358"></a><a name="p498514100358"></a>rw</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p67171052123612"><a name="p67171052123612"></a><a name="p67171052123612"></a>卢旺达语</p>
</td>
</tr>
<tr id="row1357720362327"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p366852718347"><a name="p366852718347"></a><a name="p366852718347"></a>KIR</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p4986710163512"><a name="p4986710163512"></a><a name="p4986710163512"></a>ky-Latn</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p571735293612"><a name="p571735293612"></a><a name="p571735293612"></a>柯尔克孜语</p>
</td>
</tr>
<tr id="row1557717366322"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p116687275344"><a name="p116687275344"></a><a name="p116687275344"></a>KIR</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p1798616102356"><a name="p1798616102356"></a><a name="p1798616102356"></a>ky</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p1571813522365"><a name="p1571813522365"></a><a name="p1571813522365"></a>柯尔克孜语</p>
</td>
</tr>
<tr id="row65771536113212"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p166817275344"><a name="p166817275344"></a><a name="p166817275344"></a>KOR</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p5986171063514"><a name="p5986171063514"></a><a name="p5986171063514"></a>ko-Latn</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p17181052173614"><a name="p17181052173614"></a><a name="p17181052173614"></a>韩语</p>
</td>
</tr>
<tr id="row1957714365323"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p8668327153410"><a name="p8668327153410"></a><a name="p8668327153410"></a>KOR</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p14986161063513"><a name="p14986161063513"></a><a name="p14986161063513"></a>ko</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p1271815526365"><a name="p1271815526365"></a><a name="p1271815526365"></a>韩语</p>
</td>
</tr>
<tr id="row757715364327"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p116691327113415"><a name="p116691327113415"></a><a name="p116691327113415"></a>KUR</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p9986510103517"><a name="p9986510103517"></a><a name="p9986510103517"></a>ku-Latn</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p471815523365"><a name="p471815523365"></a><a name="p471815523365"></a>库尔德语</p>
</td>
</tr>
<tr id="row195770365328"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p176691527193411"><a name="p176691527193411"></a><a name="p176691527193411"></a>KUR</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p7986111063514"><a name="p7986111063514"></a><a name="p7986111063514"></a>ku</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p13718205253619"><a name="p13718205253619"></a><a name="p13718205253619"></a>库尔德语</p>
</td>
</tr>
<tr id="row4578103613214"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p66694274348"><a name="p66694274348"></a><a name="p66694274348"></a>LAO</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p398616102355"><a name="p398616102355"></a><a name="p398616102355"></a>lo</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p107181852163616"><a name="p107181852163616"></a><a name="p107181852163616"></a>老挝语</p>
</td>
</tr>
<tr id="row3578036123211"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p13669927103412"><a name="p13669927103412"></a><a name="p13669927103412"></a>LAT</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p798614106355"><a name="p798614106355"></a><a name="p798614106355"></a>la</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p9718195263613"><a name="p9718195263613"></a><a name="p9718195263613"></a>拉丁语</p>
</td>
</tr>
<tr id="row45788365324"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p1366919278341"><a name="p1366919278341"></a><a name="p1366919278341"></a>LAV</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p209869104355"><a name="p209869104355"></a><a name="p209869104355"></a>lv</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p57189528363"><a name="p57189528363"></a><a name="p57189528363"></a>拉脱维亚语</p>
</td>
</tr>
<tr id="row957823663214"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p18669162719349"><a name="p18669162719349"></a><a name="p18669162719349"></a>LIT</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p14986210123520"><a name="p14986210123520"></a><a name="p14986210123520"></a>lt</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p16718135243615"><a name="p16718135243615"></a><a name="p16718135243615"></a>立陶宛语</p>
</td>
</tr>
<tr id="row11578113615320"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p566918271346"><a name="p566918271346"></a><a name="p566918271346"></a>LTZ</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p1098621018353"><a name="p1098621018353"></a><a name="p1098621018353"></a>lb</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p57181523368"><a name="p57181523368"></a><a name="p57181523368"></a>卢森堡语</p>
</td>
</tr>
<tr id="row12578103611322"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p116692027103419"><a name="p116692027103419"></a><a name="p116692027103419"></a>MKD</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p79861610173516"><a name="p79861610173516"></a><a name="p79861610173516"></a>mk-Latn</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p871815214367"><a name="p871815214367"></a><a name="p871815214367"></a>北马其顿语</p>
</td>
</tr>
<tr id="row165781636113214"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p5669202711349"><a name="p5669202711349"></a><a name="p5669202711349"></a>MKD</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p16986171013511"><a name="p16986171013511"></a><a name="p16986171013511"></a>mk</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p1171815203615"><a name="p1171815203615"></a><a name="p1171815203615"></a>北马其顿语</p>
</td>
</tr>
<tr id="row175781436113219"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p266912713416"><a name="p266912713416"></a><a name="p266912713416"></a>MAH</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p4986141014358"><a name="p4986141014358"></a><a name="p4986141014358"></a>mh</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p1471855293615"><a name="p1471855293615"></a><a name="p1471855293615"></a>马绍尔语</p>
</td>
</tr>
<tr id="row8578163612328"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p366920273341"><a name="p366920273341"></a><a name="p366920273341"></a>MAL</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p1986191013512"><a name="p1986191013512"></a><a name="p1986191013512"></a>ml</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p1671805223616"><a name="p1671805223616"></a><a name="p1671805223616"></a>马拉雅拉姆语</p>
</td>
</tr>
<tr id="row75797360322"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p196691327103410"><a name="p196691327103410"></a><a name="p196691327103410"></a>MAL</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p6986121013512"><a name="p6986121013512"></a><a name="p6986121013512"></a>ml-Latn</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p1771865203617"><a name="p1771865203617"></a><a name="p1771865203617"></a>马拉雅拉姆语</p>
</td>
</tr>
<tr id="row057911367325"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p1566982733417"><a name="p1566982733417"></a><a name="p1566982733417"></a>MRI</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p1898621019355"><a name="p1898621019355"></a><a name="p1898621019355"></a>mi</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p17189523362"><a name="p17189523362"></a><a name="p17189523362"></a>毛利语</p>
</td>
</tr>
<tr id="row17579163613215"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p1766972720341"><a name="p1766972720341"></a><a name="p1766972720341"></a>MAR</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p298610102352"><a name="p298610102352"></a><a name="p298610102352"></a>mr-Latn</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p167186529363"><a name="p167186529363"></a><a name="p167186529363"></a>马拉地语</p>
</td>
</tr>
<tr id="row357913673211"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p19669192712347"><a name="p19669192712347"></a><a name="p19669192712347"></a>MAR</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p1598621014352"><a name="p1598621014352"></a><a name="p1598621014352"></a>mr</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p147181052113610"><a name="p147181052113610"></a><a name="p147181052113610"></a>马拉地语</p>
</td>
</tr>
<tr id="row1357983653219"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p1766919274348"><a name="p1766919274348"></a><a name="p1766919274348"></a>MSA</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p998661063510"><a name="p998661063510"></a><a name="p998661063510"></a>ms</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p1771815218364"><a name="p1771815218364"></a><a name="p1771815218364"></a>马来语</p>
</td>
</tr>
<tr id="row175795367329"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p8669132713345"><a name="p8669132713345"></a><a name="p8669132713345"></a>MLG</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p1398651023517"><a name="p1398651023517"></a><a name="p1398651023517"></a>mg</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p4718115219368"><a name="p4718115219368"></a><a name="p4718115219368"></a>马拉加斯语</p>
</td>
</tr>
<tr id="row185797367322"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p56691927113410"><a name="p56691927113410"></a><a name="p56691927113410"></a>MLT</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p39878107356"><a name="p39878107356"></a><a name="p39878107356"></a>mt</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p27181552143615"><a name="p27181552143615"></a><a name="p27181552143615"></a>马耳他语</p>
</td>
</tr>
<tr id="row7579436163210"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p866972711341"><a name="p866972711341"></a><a name="p866972711341"></a>MON</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p109871310173517"><a name="p109871310173517"></a><a name="p109871310173517"></a>mn-Latn</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p871914529364"><a name="p871914529364"></a><a name="p871914529364"></a>蒙古语</p>
</td>
</tr>
<tr id="row1579133663214"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p767042713417"><a name="p767042713417"></a><a name="p767042713417"></a>MON</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p1298711107354"><a name="p1298711107354"></a><a name="p1298711107354"></a>mn</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p117195528366"><a name="p117195528366"></a><a name="p117195528366"></a>蒙古语</p>
</td>
</tr>
<tr id="row95807362327"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p1367017275344"><a name="p1367017275344"></a><a name="p1367017275344"></a>NAU</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p13987201015359"><a name="p13987201015359"></a><a name="p13987201015359"></a>na</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p871915526365"><a name="p871915526365"></a><a name="p871915526365"></a>瑙鲁语</p>
</td>
</tr>
<tr id="row1758093618326"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p12670182743416"><a name="p12670182743416"></a><a name="p12670182743416"></a>NDE</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p11987210203517"><a name="p11987210203517"></a><a name="p11987210203517"></a>nd</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p4719125233616"><a name="p4719125233616"></a><a name="p4719125233616"></a>北恩德贝莱语</p>
</td>
</tr>
<tr id="row1458053617328"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p867062733418"><a name="p867062733418"></a><a name="p867062733418"></a>NEP</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p7987141043511"><a name="p7987141043511"></a><a name="p7987141043511"></a>ne-Latn</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p67195521367"><a name="p67195521367"></a><a name="p67195521367"></a>尼泊尔语</p>
</td>
</tr>
<tr id="row195807361323"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p2670182717340"><a name="p2670182717340"></a><a name="p2670182717340"></a>NEP</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p1898771093518"><a name="p1898771093518"></a><a name="p1898771093518"></a>ne</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p5719205263619"><a name="p5719205263619"></a><a name="p5719205263619"></a>尼泊尔语</p>
</td>
</tr>
<tr id="row65807368326"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p12670192713412"><a name="p12670192713412"></a><a name="p12670192713412"></a>NOR</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p998719102352"><a name="p998719102352"></a><a name="p998719102352"></a>no</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p12719652163619"><a name="p12719652163619"></a><a name="p12719652163619"></a>挪威语</p>
</td>
</tr>
<tr id="row0580123611325"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p13670102714347"><a name="p13670102714347"></a><a name="p13670102714347"></a>NYA</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p159872106354"><a name="p159872106354"></a><a name="p159872106354"></a>ny</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p371913524367"><a name="p371913524367"></a><a name="p371913524367"></a>齐切瓦语</p>
</td>
</tr>
<tr id="row20580236163213"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p1167042712347"><a name="p1167042712347"></a><a name="p1167042712347"></a>OCI</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p1698751013359"><a name="p1698751013359"></a><a name="p1698751013359"></a>oc</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p117191152193610"><a name="p117191152193610"></a><a name="p117191152193610"></a>奥克语</p>
</td>
</tr>
<tr id="row1858043613210"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p1867082711342"><a name="p1867082711342"></a><a name="p1867082711342"></a>ORI</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p1198721073518"><a name="p1198721073518"></a><a name="p1198721073518"></a>or-Latn</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p2071913526368"><a name="p2071913526368"></a><a name="p2071913526368"></a>奥里亚语</p>
</td>
</tr>
<tr id="row1658012361323"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p13670627103410"><a name="p13670627103410"></a><a name="p13670627103410"></a>ORI</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p3987171023518"><a name="p3987171023518"></a><a name="p3987171023518"></a>or</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p13719115216364"><a name="p13719115216364"></a><a name="p13719115216364"></a>奥里亚语</p>
</td>
</tr>
<tr id="row1058113673215"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p8670127163416"><a name="p8670127163416"></a><a name="p8670127163416"></a>ORM</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p698719102355"><a name="p698719102355"></a><a name="p698719102355"></a>om</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p12719952173614"><a name="p12719952173614"></a><a name="p12719952173614"></a>奥罗莫语</p>
</td>
</tr>
<tr id="row135813366327"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p17670132783413"><a name="p17670132783413"></a><a name="p17670132783413"></a>PAN</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p18987151043513"><a name="p18987151043513"></a><a name="p18987151043513"></a>pa</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p3719135217365"><a name="p3719135217365"></a><a name="p3719135217365"></a>旁遮普语</p>
</td>
</tr>
<tr id="row75819369322"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p36701527183413"><a name="p36701527183413"></a><a name="p36701527183413"></a>PAN</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p12987101023519"><a name="p12987101023519"></a><a name="p12987101023519"></a>pa-Latn</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p15719125223617"><a name="p15719125223617"></a><a name="p15719125223617"></a>旁遮普语</p>
</td>
</tr>
<tr id="row558113633212"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p467012793412"><a name="p467012793412"></a><a name="p467012793412"></a>PAN</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p209876102355"><a name="p209876102355"></a><a name="p209876102355"></a>pa-Arab</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p771985283612"><a name="p771985283612"></a><a name="p771985283612"></a>旁遮普语</p>
</td>
</tr>
<tr id="row45811736193211"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p16709273343"><a name="p16709273343"></a><a name="p16709273343"></a>PAN</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p3987201073519"><a name="p3987201073519"></a><a name="p3987201073519"></a>pa-Guru</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p9719175212368"><a name="p9719175212368"></a><a name="p9719175212368"></a>旁遮普语</p>
</td>
</tr>
<tr id="row20581136123219"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p4670152717340"><a name="p4670152717340"></a><a name="p4670152717340"></a>FAS</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p1298731043510"><a name="p1298731043510"></a><a name="p1298731043510"></a>fa-Latn</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p17719205215369"><a name="p17719205215369"></a><a name="p17719205215369"></a>波斯语</p>
</td>
</tr>
<tr id="row115811836163212"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p116704271348"><a name="p116704271348"></a><a name="p116704271348"></a>FAS</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p1198761023519"><a name="p1198761023519"></a><a name="p1198761023519"></a>fa</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p8719135213611"><a name="p8719135213611"></a><a name="p8719135213611"></a>波斯语</p>
</td>
</tr>
<tr id="row55814362324"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p13670102753411"><a name="p13670102753411"></a><a name="p13670102753411"></a>POL</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p18988181043517"><a name="p18988181043517"></a><a name="p18988181043517"></a>pl</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p10719125263612"><a name="p10719125263612"></a><a name="p10719125263612"></a>波兰语</p>
</td>
</tr>
<tr id="row25821136123215"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p66706273348"><a name="p66706273348"></a><a name="p66706273348"></a>POR</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p0988131063517"><a name="p0988131063517"></a><a name="p0988131063517"></a>pt</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p27191525368"><a name="p27191525368"></a><a name="p27191525368"></a>葡萄牙语</p>
</td>
</tr>
<tr id="row17582183623213"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p12670192743417"><a name="p12670192743417"></a><a name="p12670192743417"></a>PUS</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p8988510163515"><a name="p8988510163515"></a><a name="p8988510163515"></a>ps</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p13720952183613"><a name="p13720952183613"></a><a name="p13720952183613"></a>普什图语</p>
</td>
</tr>
<tr id="row105821036173217"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p36711127133413"><a name="p36711127133413"></a><a name="p36711127133413"></a>QUE</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p179881610113512"><a name="p179881610113512"></a><a name="p179881610113512"></a>qu</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p15720652133610"><a name="p15720652133610"></a><a name="p15720652133610"></a>克丘亚语</p>
</td>
</tr>
<tr id="row158211367321"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p176711727113414"><a name="p176711727113414"></a><a name="p176711727113414"></a>ROH</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p129881410103514"><a name="p129881410103514"></a><a name="p129881410103514"></a>rm</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p107201052123619"><a name="p107201052123619"></a><a name="p107201052123619"></a>罗曼什语</p>
</td>
</tr>
<tr id="row758293616324"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p166711027113417"><a name="p166711027113417"></a><a name="p166711027113417"></a>RON</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p1198871093518"><a name="p1198871093518"></a><a name="p1198871093518"></a>ro</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p9720165283620"><a name="p9720165283620"></a><a name="p9720165283620"></a>罗马尼亚语</p>
</td>
</tr>
<tr id="row85821536173217"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p1067111273347"><a name="p1067111273347"></a><a name="p1067111273347"></a>RUN</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p11988191043519"><a name="p11988191043519"></a><a name="p11988191043519"></a>rn</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p20720852133614"><a name="p20720852133614"></a><a name="p20720852133614"></a>卢旺达-朗迪语</p>
</td>
</tr>
<tr id="row1158243673214"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p2067117273340"><a name="p2067117273340"></a><a name="p2067117273340"></a>RUS</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p198881093518"><a name="p198881093518"></a><a name="p198881093518"></a>ru-Latn</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p07201352203618"><a name="p07201352203618"></a><a name="p07201352203618"></a>俄语</p>
</td>
</tr>
<tr id="row105823368325"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p13671827123418"><a name="p13671827123418"></a><a name="p13671827123418"></a>RUS</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p998851053513"><a name="p998851053513"></a><a name="p998851053513"></a>ru</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p187201052113617"><a name="p187201052113617"></a><a name="p187201052113617"></a>俄语</p>
</td>
</tr>
<tr id="row8582736163219"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p167132783418"><a name="p167132783418"></a><a name="p167132783418"></a>SAG</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p1998861017359"><a name="p1998861017359"></a><a name="p1998861017359"></a>sg</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p12720105215369"><a name="p12720105215369"></a><a name="p12720105215369"></a>桑戈语</p>
</td>
</tr>
<tr id="row10583193619323"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p46711227173419"><a name="p46711227173419"></a><a name="p46711227173419"></a>SAN</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p59881510153512"><a name="p59881510153512"></a><a name="p59881510153512"></a>sa</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p8720135211364"><a name="p8720135211364"></a><a name="p8720135211364"></a>梵语</p>
</td>
</tr>
<tr id="row20583103612327"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p10671527163412"><a name="p10671527163412"></a><a name="p10671527163412"></a>HRV</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p39881103359"><a name="p39881103359"></a><a name="p39881103359"></a>hr</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p1372015216368"><a name="p1372015216368"></a><a name="p1372015216368"></a>克罗地亚语</p>
</td>
</tr>
<tr id="row658313366326"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p186711827173415"><a name="p186711827173415"></a><a name="p186711827173415"></a>SRP</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p99882102356"><a name="p99882102356"></a><a name="p99882102356"></a>sr-Latn</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p87209528369"><a name="p87209528369"></a><a name="p87209528369"></a>塞尔维亚语</p>
</td>
</tr>
<tr id="row1258333653213"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p14671132793414"><a name="p14671132793414"></a><a name="p14671132793414"></a>SRP</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p6988910103517"><a name="p6988910103517"></a><a name="p6988910103517"></a>sr</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p472005211368"><a name="p472005211368"></a><a name="p472005211368"></a>塞尔维亚语</p>
</td>
</tr>
<tr id="row25833363321"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p17671132716343"><a name="p17671132716343"></a><a name="p17671132716343"></a>SIN</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p59881010113513"><a name="p59881010113513"></a><a name="p59881010113513"></a>si-Latn</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p0720135223610"><a name="p0720135223610"></a><a name="p0720135223610"></a>僧伽罗语</p>
</td>
</tr>
<tr id="row115831436163215"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p18671527163417"><a name="p18671527163417"></a><a name="p18671527163417"></a>SIN</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p3988141043514"><a name="p3988141043514"></a><a name="p3988141043514"></a>si</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p207209526362"><a name="p207209526362"></a><a name="p207209526362"></a>僧伽罗语</p>
</td>
</tr>
<tr id="row55831936173214"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p1267112277348"><a name="p1267112277348"></a><a name="p1267112277348"></a>SLK</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p14988710123515"><a name="p14988710123515"></a><a name="p14988710123515"></a>sk</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p3720195273618"><a name="p3720195273618"></a><a name="p3720195273618"></a>斯洛伐克语</p>
</td>
</tr>
<tr id="row10583153623215"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p10671192715347"><a name="p10671192715347"></a><a name="p10671192715347"></a>SLV</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p10988111063513"><a name="p10988111063513"></a><a name="p10988111063513"></a>sl</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p47201452173615"><a name="p47201452173615"></a><a name="p47201452173615"></a>斯洛文尼亚语</p>
</td>
</tr>
<tr id="row958319369327"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p6671192716345"><a name="p6671192716345"></a><a name="p6671192716345"></a>SMO</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p898820103359"><a name="p898820103359"></a><a name="p898820103359"></a>sm</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p8720352183614"><a name="p8720352183614"></a><a name="p8720352183614"></a>萨摩亚语</p>
</td>
</tr>
<tr id="row6584136173213"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p467114279344"><a name="p467114279344"></a><a name="p467114279344"></a>SNA</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p149881110113517"><a name="p149881110113517"></a><a name="p149881110113517"></a>sn</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p147201052193612"><a name="p147201052193612"></a><a name="p147201052193612"></a>修纳语</p>
</td>
</tr>
<tr id="row858420362327"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p16711927153413"><a name="p16711927153413"></a><a name="p16711927153413"></a>SND</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p6989201011352"><a name="p6989201011352"></a><a name="p6989201011352"></a>sd-Latn</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p1072095273612"><a name="p1072095273612"></a><a name="p1072095273612"></a>信德语</p>
</td>
</tr>
<tr id="row155849361328"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p1067119274349"><a name="p1067119274349"></a><a name="p1067119274349"></a>SND</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p698911103359"><a name="p698911103359"></a><a name="p698911103359"></a>sd</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p16720105283618"><a name="p16720105283618"></a><a name="p16720105283618"></a>信德语</p>
</td>
</tr>
<tr id="row12584536153216"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p1367116275345"><a name="p1367116275345"></a><a name="p1367116275345"></a>SOM</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p99891810133517"><a name="p99891810133517"></a><a name="p99891810133517"></a>so</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p37201552103619"><a name="p37201552103619"></a><a name="p37201552103619"></a>索马里语</p>
</td>
</tr>
<tr id="row45841036173219"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p267210275346"><a name="p267210275346"></a><a name="p267210275346"></a>SOT</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p998911012357"><a name="p998911012357"></a><a name="p998911012357"></a>st</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p19721145211364"><a name="p19721145211364"></a><a name="p19721145211364"></a>塞索托语</p>
</td>
</tr>
<tr id="row3584193683216"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p6672327193411"><a name="p6672327193411"></a><a name="p6672327193411"></a>SPA</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p598914107359"><a name="p598914107359"></a><a name="p598914107359"></a>es</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p17721105220365"><a name="p17721105220365"></a><a name="p17721105220365"></a>西班牙文</p>
</td>
</tr>
<tr id="row18584193643218"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p11672112743410"><a name="p11672112743410"></a><a name="p11672112743410"></a>SRD</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p498915107354"><a name="p498915107354"></a><a name="p498915107354"></a>sc</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p15721952113617"><a name="p15721952113617"></a><a name="p15721952113617"></a>撒丁语</p>
</td>
</tr>
<tr id="row2584133693215"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p136721827113416"><a name="p136721827113416"></a><a name="p136721827113416"></a>SSW</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p498916100354"><a name="p498916100354"></a><a name="p498916100354"></a>ss</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p27216526364"><a name="p27216526364"></a><a name="p27216526364"></a>斯威士语</p>
</td>
</tr>
<tr id="row17584136123213"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p46728277343"><a name="p46728277343"></a><a name="p46728277343"></a>SWA</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p59892010193514"><a name="p59892010193514"></a><a name="p59892010193514"></a>sw</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p137211052133612"><a name="p137211052133612"></a><a name="p137211052133612"></a>斯瓦希里语</p>
</td>
</tr>
<tr id="row358515363323"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p116728276343"><a name="p116728276343"></a><a name="p116728276343"></a>SWE</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p1298941093516"><a name="p1298941093516"></a><a name="p1298941093516"></a>sv</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p177211525365"><a name="p177211525365"></a><a name="p177211525365"></a>瑞典语</p>
</td>
</tr>
<tr id="row358553643215"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p5672152723410"><a name="p5672152723410"></a><a name="p5672152723410"></a>TAH</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p15989131053515"><a name="p15989131053515"></a><a name="p15989131053515"></a>ty</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p6721952183618"><a name="p6721952183618"></a><a name="p6721952183618"></a>塔希提语</p>
</td>
</tr>
<tr id="row1058513610322"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p76721427193418"><a name="p76721427193418"></a><a name="p76721427193418"></a>TAM</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p16989181083516"><a name="p16989181083516"></a><a name="p16989181083516"></a>ta-Latn</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p372135213614"><a name="p372135213614"></a><a name="p372135213614"></a>泰米尔语</p>
</td>
</tr>
<tr id="row1585153614322"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p19672202715349"><a name="p19672202715349"></a><a name="p19672202715349"></a>TAM</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p1498991014353"><a name="p1498991014353"></a><a name="p1498991014353"></a>ta</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p272105253612"><a name="p272105253612"></a><a name="p272105253612"></a>泰米尔语</p>
</td>
</tr>
<tr id="row16585636103216"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p1567218271340"><a name="p1567218271340"></a><a name="p1567218271340"></a>TAT</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p798910105355"><a name="p798910105355"></a><a name="p798910105355"></a>tt-Latn</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p17218525368"><a name="p17218525368"></a><a name="p17218525368"></a>鞑靼语</p>
</td>
</tr>
<tr id="row458593643212"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p1867211275347"><a name="p1867211275347"></a><a name="p1867211275347"></a>TAT</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p69891110203513"><a name="p69891110203513"></a><a name="p69891110203513"></a>tt</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p67211652113614"><a name="p67211652113614"></a><a name="p67211652113614"></a>鞑靼语</p>
</td>
</tr>
<tr id="row958563610321"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p267242718349"><a name="p267242718349"></a><a name="p267242718349"></a>TEL</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p598981014354"><a name="p598981014354"></a><a name="p598981014354"></a>te-Latn</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p1721125273618"><a name="p1721125273618"></a><a name="p1721125273618"></a>泰卢固语</p>
</td>
</tr>
<tr id="row1658513613214"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p1967216273344"><a name="p1967216273344"></a><a name="p1967216273344"></a>TEL</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p119895103355"><a name="p119895103355"></a><a name="p119895103355"></a>te</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p872125263614"><a name="p872125263614"></a><a name="p872125263614"></a>泰卢固语</p>
</td>
</tr>
<tr id="row115854369325"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p14672427193410"><a name="p14672427193410"></a><a name="p14672427193410"></a>TGK</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p198915101353"><a name="p198915101353"></a><a name="p198915101353"></a>tg-Latn</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p372114528364"><a name="p372114528364"></a><a name="p372114528364"></a>塔吉克语</p>
</td>
</tr>
<tr id="row5586336133218"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p186721427103417"><a name="p186721427103417"></a><a name="p186721427103417"></a>TGK</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p7989010193514"><a name="p7989010193514"></a><a name="p7989010193514"></a>tg</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p11721115213613"><a name="p11721115213613"></a><a name="p11721115213613"></a>塔吉克语</p>
</td>
</tr>
<tr id="row25861436113217"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p17672112763415"><a name="p17672112763415"></a><a name="p17672112763415"></a>THA</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p59891610163513"><a name="p59891610163513"></a><a name="p59891610163513"></a>th-Latn</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p472110525369"><a name="p472110525369"></a><a name="p472110525369"></a>泰语</p>
</td>
</tr>
<tr id="row145861136183217"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p16672102711345"><a name="p16672102711345"></a><a name="p16672102711345"></a>THA</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p99892106354"><a name="p99892106354"></a><a name="p99892106354"></a>th</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p5721152113617"><a name="p5721152113617"></a><a name="p5721152113617"></a>泰语</p>
</td>
</tr>
<tr id="row1858615369325"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p1672027103416"><a name="p1672027103416"></a><a name="p1672027103416"></a>TIR</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p1998991083514"><a name="p1998991083514"></a><a name="p1998991083514"></a>ti-Latn</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p187211952133612"><a name="p187211952133612"></a><a name="p187211952133612"></a>提格雷尼亚语</p>
</td>
</tr>
<tr id="row1658603683217"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p867218277345"><a name="p867218277345"></a><a name="p867218277345"></a>TIR</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p499031018357"><a name="p499031018357"></a><a name="p499031018357"></a>ti</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p1472185216363"><a name="p1472185216363"></a><a name="p1472185216363"></a>提格雷尼亚语</p>
</td>
</tr>
<tr id="row95871367329"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p167213270347"><a name="p167213270347"></a><a name="p167213270347"></a>TON</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p1899001012359"><a name="p1899001012359"></a><a name="p1899001012359"></a>to</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p8721195212363"><a name="p8721195212363"></a><a name="p8721195212363"></a>汤加语</p>
</td>
</tr>
<tr id="row4587203693211"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p26731327113413"><a name="p26731327113413"></a><a name="p26731327113413"></a>TSN</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p7990121063515"><a name="p7990121063515"></a><a name="p7990121063515"></a>tn</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p7722205223612"><a name="p7722205223612"></a><a name="p7722205223612"></a>茨瓦纳语</p>
</td>
</tr>
<tr id="row458720361325"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p1673327173416"><a name="p1673327173416"></a><a name="p1673327173416"></a>TUK</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p3990910133518"><a name="p3990910133518"></a><a name="p3990910133518"></a>tk</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p12722752203610"><a name="p12722752203610"></a><a name="p12722752203610"></a>土库曼语</p>
</td>
</tr>
<tr id="row175871736143214"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p1367312719341"><a name="p1367312719341"></a><a name="p1367312719341"></a>TUR</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p1699081020359"><a name="p1699081020359"></a><a name="p1699081020359"></a>tr</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p16722145253620"><a name="p16722145253620"></a><a name="p16722145253620"></a>土耳其语</p>
</td>
</tr>
<tr id="row12587236123212"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p7673192713420"><a name="p7673192713420"></a><a name="p7673192713420"></a>UIG</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p49907102354"><a name="p49907102354"></a><a name="p49907102354"></a>ug-Latn</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p13722165203615"><a name="p13722165203615"></a><a name="p13722165203615"></a>维吾尔语</p>
</td>
</tr>
<tr id="row758713365329"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p3673122716341"><a name="p3673122716341"></a><a name="p3673122716341"></a>UIG</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p1499061017354"><a name="p1499061017354"></a><a name="p1499061017354"></a>ug</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p11722752183614"><a name="p11722752183614"></a><a name="p11722752183614"></a>维吾尔语</p>
</td>
</tr>
<tr id="row18588193616328"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p126731427183410"><a name="p126731427183410"></a><a name="p126731427183410"></a>UKR</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p14990171063519"><a name="p14990171063519"></a><a name="p14990171063519"></a>uk-Latn</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p14722135217363"><a name="p14722135217363"></a><a name="p14722135217363"></a>乌克兰语</p>
</td>
</tr>
<tr id="row55881936103214"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p167332723417"><a name="p167332723417"></a><a name="p167332723417"></a>UKR</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p2099061013351"><a name="p2099061013351"></a><a name="p2099061013351"></a>uk</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p147221852193610"><a name="p147221852193610"></a><a name="p147221852193610"></a>乌克兰语</p>
</td>
</tr>
<tr id="row11588536163218"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p11673182723413"><a name="p11673182723413"></a><a name="p11673182723413"></a>URD</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p139909105358"><a name="p139909105358"></a><a name="p139909105358"></a>ur-Latn</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p14722752183611"><a name="p14722752183611"></a><a name="p14722752183611"></a>乌尔都语</p>
</td>
</tr>
<tr id="row17588036103215"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p13673152720349"><a name="p13673152720349"></a><a name="p13673152720349"></a>URD</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p2990710103519"><a name="p2990710103519"></a><a name="p2990710103519"></a>ur</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p137221352193613"><a name="p137221352193613"></a><a name="p137221352193613"></a>乌尔都语</p>
</td>
</tr>
<tr id="row558863610321"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p136731827113413"><a name="p136731827113413"></a><a name="p136731827113413"></a>UZB</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p89907101359"><a name="p89907101359"></a><a name="p89907101359"></a>uz-Latn</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p10722105283612"><a name="p10722105283612"></a><a name="p10722105283612"></a>乌兹别克语</p>
</td>
</tr>
<tr id="row205881236193217"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p1673202711348"><a name="p1673202711348"></a><a name="p1673202711348"></a>UZB</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p129908102353"><a name="p129908102353"></a><a name="p129908102353"></a>uz</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p1972205233614"><a name="p1972205233614"></a><a name="p1972205233614"></a>乌兹别克语</p>
</td>
</tr>
<tr id="row2058963617322"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p17673227203417"><a name="p17673227203417"></a><a name="p17673227203417"></a>VIE</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p11990181011355"><a name="p11990181011355"></a><a name="p11990181011355"></a>vi</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p6722175213613"><a name="p6722175213613"></a><a name="p6722175213613"></a>越南语</p>
</td>
</tr>
<tr id="row1589836103216"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p1467352710340"><a name="p1467352710340"></a><a name="p1467352710340"></a>CYM</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p1799031053511"><a name="p1799031053511"></a><a name="p1799031053511"></a>cy</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p872225243618"><a name="p872225243618"></a><a name="p872225243618"></a>威尔士语</p>
</td>
</tr>
<tr id="row155891736143212"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p86738270343"><a name="p86738270343"></a><a name="p86738270343"></a>WOL</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p159900105358"><a name="p159900105358"></a><a name="p159900105358"></a>wo</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p872225215365"><a name="p872225215365"></a><a name="p872225215365"></a>沃洛夫语</p>
</td>
</tr>
<tr id="row2589133673210"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p4673427103415"><a name="p4673427103415"></a><a name="p4673427103415"></a>XHO</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p169901410103519"><a name="p169901410103519"></a><a name="p169901410103519"></a>xh</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p87228522368"><a name="p87228522368"></a><a name="p87228522368"></a>科萨语</p>
</td>
</tr>
<tr id="row10589136203219"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p067314276346"><a name="p067314276346"></a><a name="p067314276346"></a>YOR</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p49905108358"><a name="p49905108358"></a><a name="p49905108358"></a>yo</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p167221952173616"><a name="p167221952173616"></a><a name="p167221952173616"></a>约鲁巴语</p>
</td>
</tr>
<tr id="row1058993616322"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p12673122717346"><a name="p12673122717346"></a><a name="p12673122717346"></a>ZUL</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p8990810173519"><a name="p8990810173519"></a><a name="p8990810173519"></a>zu</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p77221652113610"><a name="p77221652113610"></a><a name="p77221652113610"></a>祖鲁语</p>
</td>
</tr>
</tbody>
</table>

