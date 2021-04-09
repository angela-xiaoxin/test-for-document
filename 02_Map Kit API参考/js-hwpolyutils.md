# HWPolyUtils<a name="ZH-CN_TOPIC_0000001099661080"></a>

-   [概览](#section6750114614115)
-   [构造方法](#section637053415211)
-   [公共方法](#section2091003114512)

## 概览<a name="section6750114614115"></a>

经纬度编解码工具类。

## 构造方法<a name="section637053415211"></a>

<a name="tc9acd08816954359a7075b54b4f7740b"></a>
<table><thead align="left"><tr id="r5e8967a688c7470485275c2d8d22bd7d"><th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.1"><p id="a78127353536d48c2a5b6260c371dec91"><a name="a78127353536d48c2a5b6260c371dec91"></a><a name="a78127353536d48c2a5b6260c371dec91"></a><strong id="acde0abc58c8b45bf814cfb00ee55f29a"><a name="acde0abc58c8b45bf814cfb00ee55f29a"></a><a name="acde0abc58c8b45bf814cfb00ee55f29a"></a>构造方法</strong></p>
</th>
<th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.2"><p id="a0375d3c450364b64b34343dfe5a65638"><a name="a0375d3c450364b64b34343dfe5a65638"></a><a name="a0375d3c450364b64b34343dfe5a65638"></a><strong id="aa83e4e6f0b15428a9e9ce3efae7084e8"><a name="aa83e4e6f0b15428a9e9ce3efae7084e8"></a><a name="aa83e4e6f0b15428a9e9ce3efae7084e8"></a>描述</strong></p>
</th>
</tr>
</thead>
<tbody><tr id="r872f67c456004eb6bab21dc0cbf7bebf"><td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.1 "><p id="acb1e220c7fee454d904fc2f4410e4c2f"><a name="acb1e220c7fee454d904fc2f4410e4c2f"></a><a name="acb1e220c7fee454d904fc2f4410e4c2f"></a>HWMapJsSDK.HWPolyUtils</p>
</td>
<td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.2 "><p id="ab07db2dce3a844a1869704498d7aa33d"><a name="ab07db2dce3a844a1869704498d7aa33d"></a><a name="ab07db2dce3a844a1869704498d7aa33d"></a>overviewPolyline编解码工具类。</p>
</td>
</tr>
</tbody>
</table>

## 公共方法<a name="section2091003114512"></a>

<a name="tc20e9fc0c160468a9d3d6e3874d4ce53"></a>
<table><thead align="left"><tr id="r12f5b3de494d460c8349ac911b3494b6"><th class="cellrowborder" valign="top" width="25.26252625262526%" id="mcps1.1.5.1.1"><p id="a88f3ce071055415d82cda52e9f062230"><a name="a88f3ce071055415d82cda52e9f062230"></a><a name="a88f3ce071055415d82cda52e9f062230"></a><strong id="afcc8b8640a0d45ada42d71a8f13d9fb8"><a name="afcc8b8640a0d45ada42d71a8f13d9fb8"></a><a name="afcc8b8640a0d45ada42d71a8f13d9fb8"></a>方法</strong></p>
</th>
<th class="cellrowborder" valign="top" width="31.553155315531555%" id="mcps1.1.5.1.2"><p id="aa639dbce9a8a4632b8bdf0d701b9dfd4"><a name="aa639dbce9a8a4632b8bdf0d701b9dfd4"></a><a name="aa639dbce9a8a4632b8bdf0d701b9dfd4"></a><strong id="a4150acd03de34ba79585ab6810150280"><a name="a4150acd03de34ba79585ab6810150280"></a><a name="a4150acd03de34ba79585ab6810150280"></a>描述</strong></p>
</th>
<th class="cellrowborder" valign="top" width="21.772177217721772%" id="mcps1.1.5.1.3"><p id="a72ed2f95fa614bf5876860adb1a525bd"><a name="a72ed2f95fa614bf5876860adb1a525bd"></a><a name="a72ed2f95fa614bf5876860adb1a525bd"></a><strong id="afad06168ff39431a96621038bace9f50"><a name="afad06168ff39431a96621038bace9f50"></a><a name="afad06168ff39431a96621038bace9f50"></a>参数类型</strong></p>
</th>
<th class="cellrowborder" valign="top" width="21.412141214121412%" id="mcps1.1.5.1.4"><p id="af8aba1d4dcea4f678803ece52ca52c12"><a name="af8aba1d4dcea4f678803ece52ca52c12"></a><a name="af8aba1d4dcea4f678803ece52ca52c12"></a><strong id="a9dddec1e556c4c1093363a520daddb91"><a name="a9dddec1e556c4c1093363a520daddb91"></a><a name="a9dddec1e556c4c1093363a520daddb91"></a>返回值</strong></p>
</th>
</tr>
</thead>
<tbody><tr id="ra073ac88b90545deaf9b9a1446d38761"><td class="cellrowborder" valign="top" width="25.26252625262526%" headers="mcps1.1.5.1.1 "><p id="p6396205513512"><a name="p6396205513512"></a><a name="p6396205513512"></a>encode(latLngs)</p>
</td>
<td class="cellrowborder" valign="top" width="31.553155315531555%" headers="mcps1.1.5.1.2 "><p id="p1739518557517"><a name="p1739518557517"></a><a name="p1739518557517"></a>对每个经纬度进行编码，编码后的字串使用“；”拼接。</p>
</td>
<td class="cellrowborder" valign="top" width="21.772177217721772%" headers="mcps1.1.5.1.3 "><p id="p113942055451"><a name="p113942055451"></a><a name="p113942055451"></a>Array&lt;<a href="js-params.md#s45373a8938e040ca9f46c78f4283b385">LatLng</a>&gt;</p>
</td>
<td class="cellrowborder" valign="top" width="21.412141214121412%" headers="mcps1.1.5.1.4 "><p id="p173923551951"><a name="p173923551951"></a><a name="p173923551951"></a>String</p>
</td>
</tr>
<tr id="re0144c150a754c5e8e0865d8750bd8dc"><td class="cellrowborder" valign="top" width="25.26252625262526%" headers="mcps1.1.5.1.1 "><p id="p5392255553"><a name="p5392255553"></a><a name="p5392255553"></a>decode(encodePolyline)</p>
</td>
<td class="cellrowborder" valign="top" width="31.553155315531555%" headers="mcps1.1.5.1.2 "><p id="p13391155514518"><a name="p13391155514518"></a><a name="p13391155514518"></a>对encodePolyline使用“；”分隔后，对分隔后的字符解码得到经纬度。</p>
</td>
<td class="cellrowborder" valign="top" width="21.772177217721772%" headers="mcps1.1.5.1.3 "><p id="p183901255859"><a name="p183901255859"></a><a name="p183901255859"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="21.412141214121412%" headers="mcps1.1.5.1.4 "><p id="p937085510512"><a name="p937085510512"></a><a name="p937085510512"></a>Array&lt;<a href="js-params.md#s45373a8938e040ca9f46c78f4283b385">LatLng</a>&gt;</p>
</td>
</tr>
</tbody>
</table>

