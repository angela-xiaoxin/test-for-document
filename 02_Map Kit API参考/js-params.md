# 参数说明<a name="ZH-CN_TOPIC_0000001145860985"></a>

-   [Address](#s4067c9cc248b447e83ca4d25c0add911)
-   [AddressDetail](#s6da2808de27a4fffbe26ce5f892ae08e)
-   [Coordinate](#s79a8e63ee72b4cb29e350a1fa05b52ce)
-   [CoordinateBounds](#s1b98984709334fa7a5cf8c7a04d4dba5)
-   [LatLng](#s45373a8938e040ca9f46c78f4283b385)
-   [LatLngBounds](#s7da68d05f25f42949a5700ac4cf28a27)
-   [OpeningHours](#scd3b7bb5f19b4324a1fb8c5da6cda1dc)
-   [Path](#sfb73d14e02cb4b2ebab582421fa618a7)
-   [Period](#sce7a427d5dd64ceb8f626b933444a38e)
-   [Poi](#sd921064d432d44689bea55491a6c96b8)
-   [Route](#scff6465e40704ddf9d95d3572e9e61bc)
-   [Site](#s60f796f99e2a42589d569ce7de36a113)
-   [Step](#s6220d04bd11944c184eeb757cc11c0d9)
-   [TimeOfWeek](#s8991b20f989c463097423b028a83fe10)
-   [Word](#section716102814347)

## Address<a name="s4067c9cc248b447e83ca4d25c0add911"></a>

<a name="tb8f3a45a93dd44d0bdfd479d136a84bf"></a>
<table><thead align="left"><tr id="re1f14f5689654e47bb732eaa156bfed6"><th class="cellrowborder" valign="top" width="18%" id="mcps1.1.5.1.1"><p id="zh-cn_topic_0000001050179698_p829755"><a name="zh-cn_topic_0000001050179698_p829755"></a><a name="zh-cn_topic_0000001050179698_p829755"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="14.000000000000002%" id="mcps1.1.5.1.2"><p id="ae0179f262c0c4af3bb19ad98946d8703"><a name="ae0179f262c0c4af3bb19ad98946d8703"></a><a name="ae0179f262c0c4af3bb19ad98946d8703"></a>是否必选</p>
</th>
<th class="cellrowborder" valign="top" width="18%" id="mcps1.1.5.1.3"><p id="zh-cn_topic_0000001050179698_p101341"><a name="zh-cn_topic_0000001050179698_p101341"></a><a name="zh-cn_topic_0000001050179698_p101341"></a>类型</p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.1.5.1.4"><p id="ad9e4d93a12244503b8cc2b224f4d84be"><a name="ad9e4d93a12244503b8cc2b224f4d84be"></a><a name="ad9e4d93a12244503b8cc2b224f4d84be"></a>说明</p>
</th>
</tr>
</thead>
<tbody><tr id="row85171649164811"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="aa86cdc2e973b44dd8f4c90f00f511b6f"><a name="aa86cdc2e973b44dd8f4c90f00f511b6f"></a><a name="aa86cdc2e973b44dd8f4c90f00f511b6f"></a>countryCode</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="afabf4d65f4c44275ac94f35c957870d3"><a name="afabf4d65f4c44275ac94f35c957870d3"></a><a name="afabf4d65f4c44275ac94f35c957870d3"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.3 "><p id="afce3b26370944f799e43fa9113ea48f5"><a name="afce3b26370944f799e43fa9113ea48f5"></a><a name="afce3b26370944f799e43fa9113ea48f5"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="a7196346248dd437f9e33cd20394b9b12"><a name="a7196346248dd437f9e33cd20394b9b12"></a><a name="a7196346248dd437f9e33cd20394b9b12"></a>国家码。</p>
</td>
</tr>
<tr id="r1ecfac2bc65a4be88398690559ead4db"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="a850e1e4a823d4d6a889e1529333b38ef"><a name="a850e1e4a823d4d6a889e1529333b38ef"></a><a name="a850e1e4a823d4d6a889e1529333b38ef"></a>country</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="ab3d556be51d241949bf3a4fc7178cb56"><a name="ab3d556be51d241949bf3a4fc7178cb56"></a><a name="ab3d556be51d241949bf3a4fc7178cb56"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.3 "><p id="a29b9c3a436f54acc9ec4a73afc9fc818"><a name="a29b9c3a436f54acc9ec4a73afc9fc818"></a><a name="a29b9c3a436f54acc9ec4a73afc9fc818"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="a49f7421ff1614f49bfec21b65f04fcfe"><a name="a49f7421ff1614f49bfec21b65f04fcfe"></a><a name="a49f7421ff1614f49bfec21b65f04fcfe"></a>国家名。</p>
</td>
</tr>
<tr id="row9947163613294"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="a6aa1a706c1334455851c0e1d53d4a1d2"><a name="a6aa1a706c1334455851c0e1d53d4a1d2"></a><a name="a6aa1a706c1334455851c0e1d53d4a1d2"></a>state</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="aa1f16f5b332f44a1bc23064e4a454cb6"><a name="aa1f16f5b332f44a1bc23064e4a454cb6"></a><a name="aa1f16f5b332f44a1bc23064e4a454cb6"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.3 "><p id="af7c2389a6ec34138a878a40de9fb4efd"><a name="af7c2389a6ec34138a878a40de9fb4efd"></a><a name="af7c2389a6ec34138a878a40de9fb4efd"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="ae8108947cfe14e2cb66f9f70177368b5"><a name="ae8108947cfe14e2cb66f9f70177368b5"></a><a name="ae8108947cfe14e2cb66f9f70177368b5"></a>省/州。</p>
</td>
</tr>
<tr id="row1154910283281"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="a79e8525e079d453ebaae6c62f05c39d5"><a name="a79e8525e079d453ebaae6c62f05c39d5"></a><a name="a79e8525e079d453ebaae6c62f05c39d5"></a>county</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="ab979e59faddf4138b2fbe96b43622ddc"><a name="ab979e59faddf4138b2fbe96b43622ddc"></a><a name="ab979e59faddf4138b2fbe96b43622ddc"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.3 "><p id="a1d8165914bd84db0bc80d58032ea50fa"><a name="a1d8165914bd84db0bc80d58032ea50fa"></a><a name="a1d8165914bd84db0bc80d58032ea50fa"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="a08c8c00a41cb47ef8164ff7949631526"><a name="a08c8c00a41cb47ef8164ff7949631526"></a><a name="a08c8c00a41cb47ef8164ff7949631526"></a>县/市。</p>
</td>
</tr>
<tr id="row10492101715513"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="a13033b8ce54d4bad800fa6ce9595a724"><a name="a13033b8ce54d4bad800fa6ce9595a724"></a><a name="a13033b8ce54d4bad800fa6ce9595a724"></a>town</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="a21aa754900fc45c690887eea1a80e87b"><a name="a21aa754900fc45c690887eea1a80e87b"></a><a name="a21aa754900fc45c690887eea1a80e87b"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.3 "><p id="a34e436e953674dbb8f71e95fb7790469"><a name="a34e436e953674dbb8f71e95fb7790469"></a><a name="a34e436e953674dbb8f71e95fb7790469"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="a738adeeeab714835b6f6b03046fb6560"><a name="a738adeeeab714835b6f6b03046fb6560"></a><a name="a738adeeeab714835b6f6b03046fb6560"></a>镇/区。</p>
</td>
</tr>
<tr id="r546716f234f14c6fad947fba198f3091"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="ad8e289a352674601b473a1760d91ceaf"><a name="ad8e289a352674601b473a1760d91ceaf"></a><a name="ad8e289a352674601b473a1760d91ceaf"></a>settlement</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="a9f9dd96310dc43b784f8458198a9dab1"><a name="a9f9dd96310dc43b784f8458198a9dab1"></a><a name="a9f9dd96310dc43b784f8458198a9dab1"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.3 "><p id="a2ed6a9d9cc3e42079acff36a3aa79b07"><a name="a2ed6a9d9cc3e42079acff36a3aa79b07"></a><a name="a2ed6a9d9cc3e42079acff36a3aa79b07"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="aaab31721f25f46ecbf6e73c875829eae"><a name="aaab31721f25f46ecbf6e73c875829eae"></a><a name="aaab31721f25f46ecbf6e73c875829eae"></a>定居点。</p>
</td>
</tr>
</tbody>
</table>

## AddressDetail<a name="s6da2808de27a4fffbe26ce5f892ae08e"></a>

<a name="td6cec3a579a84ec3b1ea04bcfac315ce"></a>
<table><thead align="left"><tr id="rc20a629a3bba4ba1bbf23df08cc7ab20"><th class="cellrowborder" valign="top" width="18%" id="mcps1.1.5.1.1"><p id="af38fc245d52747ed81b3ac8af8ea026f"><a name="af38fc245d52747ed81b3ac8af8ea026f"></a><a name="af38fc245d52747ed81b3ac8af8ea026f"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="14.000000000000002%" id="mcps1.1.5.1.2"><p id="a94c762e41ecb49499cfe4d1c24c2c436"><a name="a94c762e41ecb49499cfe4d1c24c2c436"></a><a name="a94c762e41ecb49499cfe4d1c24c2c436"></a>是否必选</p>
</th>
<th class="cellrowborder" valign="top" width="18%" id="mcps1.1.5.1.3"><p id="a4b633cba95a24ea4a5d6f244baf47624"><a name="a4b633cba95a24ea4a5d6f244baf47624"></a><a name="a4b633cba95a24ea4a5d6f244baf47624"></a>类型</p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.1.5.1.4"><p id="adcb147f02c2a45659bef3218eb108792"><a name="adcb147f02c2a45659bef3218eb108792"></a><a name="adcb147f02c2a45659bef3218eb108792"></a>说明</p>
</th>
</tr>
</thead>
<tbody><tr id="row850643335113"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="a107e1a8e3429497899458c0ef89671e3"><a name="a107e1a8e3429497899458c0ef89671e3"></a><a name="a107e1a8e3429497899458c0ef89671e3"></a>countryCode</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="ab37259b2decd485b92947c560a32816d"><a name="ab37259b2decd485b92947c560a32816d"></a><a name="ab37259b2decd485b92947c560a32816d"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.3 "><p id="a069a2472251c4474859d618b0b9f8bf8"><a name="a069a2472251c4474859d618b0b9f8bf8"></a><a name="a069a2472251c4474859d618b0b9f8bf8"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="a45fcc6f52c9d42859608abe77e363534"><a name="a45fcc6f52c9d42859608abe77e363534"></a><a name="a45fcc6f52c9d42859608abe77e363534"></a>国家码，采用ISO 3166-1 alpha-2。</p>
</td>
</tr>
<tr id="row11754124885113"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="a57b92c409dd44ddab035c0b88477f243"><a name="a57b92c409dd44ddab035c0b88477f243"></a><a name="a57b92c409dd44ddab035c0b88477f243"></a>country</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="afe82fd3a42f944288e6c8a74d7e51ef6"><a name="afe82fd3a42f944288e6c8a74d7e51ef6"></a><a name="afe82fd3a42f944288e6c8a74d7e51ef6"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.3 "><p id="aff192183cb3947bfb82a885d190f2bc2"><a name="aff192183cb3947bfb82a885d190f2bc2"></a><a name="aff192183cb3947bfb82a885d190f2bc2"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="a6970c22a4b7341f0b985d065057692f2"><a name="a6970c22a4b7341f0b985d065057692f2"></a><a name="a6970c22a4b7341f0b985d065057692f2"></a>国家名。</p>
</td>
</tr>
<tr id="row072612414309"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="a8557c72b434142f794235c38abcb18b5"><a name="a8557c72b434142f794235c38abcb18b5"></a><a name="a8557c72b434142f794235c38abcb18b5"></a>adminArea</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="a3243057cecb7454a9777a11d4b7f8347"><a name="a3243057cecb7454a9777a11d4b7f8347"></a><a name="a3243057cecb7454a9777a11d4b7f8347"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.3 "><p id="aec69a219d05c49d88416a99bbc5cabf8"><a name="aec69a219d05c49d88416a99bbc5cabf8"></a><a name="aec69a219d05c49d88416a99bbc5cabf8"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="adce974c857c3487cb0d567763d223074"><a name="adce974c857c3487cb0d567763d223074"></a><a name="adce974c857c3487cb0d567763d223074"></a>国家下面的一级行政区，一般是省/州。</p>
</td>
</tr>
<tr id="re128ff59f2f44ce780569afc68a1f200"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="ac063c7d1de704902a767c2dcd3b89e9b"><a name="ac063c7d1de704902a767c2dcd3b89e9b"></a><a name="ac063c7d1de704902a767c2dcd3b89e9b"></a>subAdminArea</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="a0d5105d0c5614e49ac2995e7a80c5aa8"><a name="a0d5105d0c5614e49ac2995e7a80c5aa8"></a><a name="a0d5105d0c5614e49ac2995e7a80c5aa8"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.3 "><p id="a88afd6de1a88417f935c619bac77ec49"><a name="a88afd6de1a88417f935c619bac77ec49"></a><a name="a88afd6de1a88417f935c619bac77ec49"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="a44379894a3cc49fb973db3f941a5545f"><a name="a44379894a3cc49fb973db3f941a5545f"></a><a name="a44379894a3cc49fb973db3f941a5545f"></a>国家下面的二级行政区，一般是市。</p>
</td>
</tr>
<tr id="r64230170e1624dd2a45d4e16fbdd0292"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="ae3502a261f424388b65a2c44b5d8fc25"><a name="ae3502a261f424388b65a2c44b5d8fc25"></a><a name="ae3502a261f424388b65a2c44b5d8fc25"></a>locality</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="a77ab29e646b34130a33bda8f6ca08c8c"><a name="a77ab29e646b34130a33bda8f6ca08c8c"></a><a name="a77ab29e646b34130a33bda8f6ca08c8c"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.3 "><p id="a26c331f25b1b4e10b3722266c741dd78"><a name="a26c331f25b1b4e10b3722266c741dd78"></a><a name="a26c331f25b1b4e10b3722266c741dd78"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="a47bea05923c24f9393e3454e2910f52d"><a name="a47bea05923c24f9393e3454e2910f52d"></a><a name="a47bea05923c24f9393e3454e2910f52d"></a>城市。</p>
</td>
</tr>
<tr id="row15845141965212"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="a3df6c67c5e5c43b0b0e26d9261f0186e"><a name="a3df6c67c5e5c43b0b0e26d9261f0186e"></a><a name="a3df6c67c5e5c43b0b0e26d9261f0186e"></a>subLocality</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="a97e8bf60fd3f4a638c31ff9366a0adb6"><a name="a97e8bf60fd3f4a638c31ff9366a0adb6"></a><a name="a97e8bf60fd3f4a638c31ff9366a0adb6"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.3 "><p id="a5d7a1101446c4ed6b4c6d8b26746afe3"><a name="a5d7a1101446c4ed6b4c6d8b26746afe3"></a><a name="a5d7a1101446c4ed6b4c6d8b26746afe3"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="a90442befeb994446b6f3f2bfb38c23d3"><a name="a90442befeb994446b6f3f2bfb38c23d3"></a><a name="a90442befeb994446b6f3f2bfb38c23d3"></a>国家下面的四级行政区，一般是镇。</p>
</td>
</tr>
<tr id="r1bebc830ab0a449dae9e7fa32731b2c3"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="a3b39f840960a48aa844a3077ce40d75b"><a name="a3b39f840960a48aa844a3077ce40d75b"></a><a name="a3b39f840960a48aa844a3077ce40d75b"></a>streetNumber</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="adf219fb907234505b5742d77200120f3"><a name="adf219fb907234505b5742d77200120f3"></a><a name="adf219fb907234505b5742d77200120f3"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.3 "><p id="aa1359783c8254245b6b3cbc29b7f78d4"><a name="aa1359783c8254245b6b3cbc29b7f78d4"></a><a name="aa1359783c8254245b6b3cbc29b7f78d4"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="a7c965da86df34c99b2bba2405b6c4a7b"><a name="a7c965da86df34c99b2bba2405b6c4a7b"></a><a name="a7c965da86df34c99b2bba2405b6c4a7b"></a>街道号。</p>
</td>
</tr>
<tr id="r19db53c97980465fa61e353a8d7899bf"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="a4a72d9fca5494f948434c9964738ed1d"><a name="a4a72d9fca5494f948434c9964738ed1d"></a><a name="a4a72d9fca5494f948434c9964738ed1d"></a>thoroughfare</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="af6c9f37c46bd4cb7811b78e5a7af403c"><a name="af6c9f37c46bd4cb7811b78e5a7af403c"></a><a name="af6c9f37c46bd4cb7811b78e5a7af403c"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.3 "><p id="a22fcd6e6745b4d7a8d0c78b2e5d78514"><a name="a22fcd6e6745b4d7a8d0c78b2e5d78514"></a><a name="a22fcd6e6745b4d7a8d0c78b2e5d78514"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="a94535cd7dbbb4a2c9b2942cf7011b3fd"><a name="a94535cd7dbbb4a2c9b2942cf7011b3fd"></a><a name="a94535cd7dbbb4a2c9b2942cf7011b3fd"></a>街道名。</p>
</td>
</tr>
<tr id="r5880dce275104ab2b349756490db5191"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="adaf36989167b497d89874a7dc78aeb9c"><a name="adaf36989167b497d89874a7dc78aeb9c"></a><a name="adaf36989167b497d89874a7dc78aeb9c"></a>postalCode</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="a254e8c3326664c158ee9b527b0085eec"><a name="a254e8c3326664c158ee9b527b0085eec"></a><a name="a254e8c3326664c158ee9b527b0085eec"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.3 "><p id="a483a6d7fafea4e258f3cb3c959760d2e"><a name="a483a6d7fafea4e258f3cb3c959760d2e"></a><a name="a483a6d7fafea4e258f3cb3c959760d2e"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="a13ae1d9ae3b9435e846682388df363b0"><a name="a13ae1d9ae3b9435e846682388df363b0"></a><a name="a13ae1d9ae3b9435e846682388df363b0"></a>邮政编码。</p>
</td>
</tr>
</tbody>
</table>

## Coordinate<a name="s79a8e63ee72b4cb29e350a1fa05b52ce"></a>

<a name="t58e5108254ae4aed8dde4c78845c9b0c"></a>
<table><thead align="left"><tr id="r423d00f03ed1487799942ff3f68df35a"><th class="cellrowborder" valign="top" width="18%" id="mcps1.1.5.1.1"><p id="a6740bfba9ab4446e8fc905f2781054c7"><a name="a6740bfba9ab4446e8fc905f2781054c7"></a><a name="a6740bfba9ab4446e8fc905f2781054c7"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="14.000000000000002%" id="mcps1.1.5.1.2"><p id="ab881884f9e36413884ff393d1b47668c"><a name="ab881884f9e36413884ff393d1b47668c"></a><a name="ab881884f9e36413884ff393d1b47668c"></a>是否必选</p>
</th>
<th class="cellrowborder" valign="top" width="18%" id="mcps1.1.5.1.3"><p id="af3df88afa18d4d039e87289f3cdfeb31"><a name="af3df88afa18d4d039e87289f3cdfeb31"></a><a name="af3df88afa18d4d039e87289f3cdfeb31"></a>类型</p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.1.5.1.4"><p id="af8f5b14a1b344efdb3f6a4cc7a2ae42e"><a name="af8f5b14a1b344efdb3f6a4cc7a2ae42e"></a><a name="af8f5b14a1b344efdb3f6a4cc7a2ae42e"></a>说明</p>
</th>
</tr>
</thead>
<tbody><tr id="rded3874d2cb541da9dafb08e948617a4"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="a1cc057a6943840669e7c8e063d8f39c9"><a name="a1cc057a6943840669e7c8e063d8f39c9"></a><a name="a1cc057a6943840669e7c8e063d8f39c9"></a>lat</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="a1fe3aaea4074403995b59f900f94bc48"><a name="a1fe3aaea4074403995b59f900f94bc48"></a><a name="a1fe3aaea4074403995b59f900f94bc48"></a>是</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.3 "><p id="afc55a8cbf4c74dd8b6e428b0a738de73"><a name="afc55a8cbf4c74dd8b6e428b0a738de73"></a><a name="afc55a8cbf4c74dd8b6e428b0a738de73"></a>Number</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="a6e6d70018344436cbb6951408ddffcbb"><a name="a6e6d70018344436cbb6951408ddffcbb"></a><a name="a6e6d70018344436cbb6951408ddffcbb"></a>纬度，取值范围：[-90, 90]。</p>
</td>
</tr>
<tr id="re49f2608fbfe43b29c054a1452abbe03"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="ada0f44e766d54ea0ac893683a569f284"><a name="ada0f44e766d54ea0ac893683a569f284"></a><a name="ada0f44e766d54ea0ac893683a569f284"></a>lng</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="a726486befc694a15af54232ca27f5240"><a name="a726486befc694a15af54232ca27f5240"></a><a name="a726486befc694a15af54232ca27f5240"></a>是</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.3 "><p id="ad67bc521979245c48ae7a07a0f10279a"><a name="ad67bc521979245c48ae7a07a0f10279a"></a><a name="ad67bc521979245c48ae7a07a0f10279a"></a>Number</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="ab2f8359a33184d5ea6bf45b14192ee84"><a name="ab2f8359a33184d5ea6bf45b14192ee84"></a><a name="ab2f8359a33184d5ea6bf45b14192ee84"></a>经度，取值范围：[-180, 180]。</p>
</td>
</tr>
</tbody>
</table>

## CoordinateBounds<a name="s1b98984709334fa7a5cf8c7a04d4dba5"></a>

<a name="t357aa0161e884193be6e0b295777848c"></a>
<table><thead align="left"><tr id="r4cdbf9c9b2754ed09256e6a29910ca1e"><th class="cellrowborder" valign="top" width="18%" id="mcps1.1.5.1.1"><p id="a549f1aa6aa1043258831e09a11e1600e"><a name="a549f1aa6aa1043258831e09a11e1600e"></a><a name="a549f1aa6aa1043258831e09a11e1600e"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="14.000000000000002%" id="mcps1.1.5.1.2"><p id="aff673a8f7b574c878c34bf2f81cf52dd"><a name="aff673a8f7b574c878c34bf2f81cf52dd"></a><a name="aff673a8f7b574c878c34bf2f81cf52dd"></a>是否必选</p>
</th>
<th class="cellrowborder" valign="top" width="18%" id="mcps1.1.5.1.3"><p id="a632cce0ce9d14df785761224aa5e30bf"><a name="a632cce0ce9d14df785761224aa5e30bf"></a><a name="a632cce0ce9d14df785761224aa5e30bf"></a>类型</p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.1.5.1.4"><p id="a1aca45dc3fcc4cc58b5ac05fa79ed0cd"><a name="a1aca45dc3fcc4cc58b5ac05fa79ed0cd"></a><a name="a1aca45dc3fcc4cc58b5ac05fa79ed0cd"></a>说明</p>
</th>
</tr>
</thead>
<tbody><tr id="r943ed223604a4d07a324eb61a88f7dc0"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="a6b231d63c05147229049a9bcd74e9961"><a name="a6b231d63c05147229049a9bcd74e9961"></a><a name="a6b231d63c05147229049a9bcd74e9961"></a>northeast</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="ab3e83bd0349145f4afbe686b05fbb1f9"><a name="ab3e83bd0349145f4afbe686b05fbb1f9"></a><a name="ab3e83bd0349145f4afbe686b05fbb1f9"></a>是</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.3 "><p id="ae0bc7b8fdf924963b9f2dc4e0c45cc50"><a name="ae0bc7b8fdf924963b9f2dc4e0c45cc50"></a><a name="ae0bc7b8fdf924963b9f2dc4e0c45cc50"></a><a href="#s79a8e63ee72b4cb29e350a1fa05b52ce">Coordinate</a></p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="a0a2da4545d2f453f9ef978b7a08bc6c4"><a name="a0a2da4545d2f453f9ef978b7a08bc6c4"></a><a name="a0a2da4545d2f453f9ef978b7a08bc6c4"></a>东北角的位置。</p>
</td>
</tr>
<tr id="r046e37c05d3941d5ab8403b9c2660004"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="a1ca92b3c445745a7b0898cf76dc669d0"><a name="a1ca92b3c445745a7b0898cf76dc669d0"></a><a name="a1ca92b3c445745a7b0898cf76dc669d0"></a>southwest</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="ab54d1304081344bcb547aca0fd760f14"><a name="ab54d1304081344bcb547aca0fd760f14"></a><a name="ab54d1304081344bcb547aca0fd760f14"></a>是</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.3 "><p id="a387ea735beac46249da7060b6caed108"><a name="a387ea735beac46249da7060b6caed108"></a><a name="a387ea735beac46249da7060b6caed108"></a><a href="#s79a8e63ee72b4cb29e350a1fa05b52ce">Coordinate</a></p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="a8203b24967094156b25811d5533a7b07"><a name="a8203b24967094156b25811d5533a7b07"></a><a name="a8203b24967094156b25811d5533a7b07"></a>西南角的位置。</p>
</td>
</tr>
</tbody>
</table>

## LatLng<a name="s45373a8938e040ca9f46c78f4283b385"></a>

<a name="tf827d383e126413e9ab35bcc5349adc4"></a>
<table><thead align="left"><tr id="r1a1902478ab44eddbc5bb68b3dc25c30"><th class="cellrowborder" valign="top" width="18%" id="mcps1.1.5.1.1"><p id="ac97530b986534e8c80996afbb749cefa"><a name="ac97530b986534e8c80996afbb749cefa"></a><a name="ac97530b986534e8c80996afbb749cefa"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="14.000000000000002%" id="mcps1.1.5.1.2"><p id="a6042e3ad849e4d5ba196d9fc08e29333"><a name="a6042e3ad849e4d5ba196d9fc08e29333"></a><a name="a6042e3ad849e4d5ba196d9fc08e29333"></a>是否必选</p>
</th>
<th class="cellrowborder" valign="top" width="18%" id="mcps1.1.5.1.3"><p id="acc903e7dfdc845078542959e8883a51a"><a name="acc903e7dfdc845078542959e8883a51a"></a><a name="acc903e7dfdc845078542959e8883a51a"></a>类型</p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.1.5.1.4"><p id="a5076a99ae02b490d84322e4c279e0713"><a name="a5076a99ae02b490d84322e4c279e0713"></a><a name="a5076a99ae02b490d84322e4c279e0713"></a>说明</p>
</th>
</tr>
</thead>
<tbody><tr id="rdc0cfc98777e478090be1e8e6dd249e9"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="a2cb0255c1d934182980205f4a5948d4d"><a name="a2cb0255c1d934182980205f4a5948d4d"></a><a name="a2cb0255c1d934182980205f4a5948d4d"></a>lat</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="afe89272f8b7b4fd082674fecd8b398ea"><a name="afe89272f8b7b4fd082674fecd8b398ea"></a><a name="afe89272f8b7b4fd082674fecd8b398ea"></a>是</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.3 "><p id="adb3459d9091d4072b5d3e6d98a064cea"><a name="adb3459d9091d4072b5d3e6d98a064cea"></a><a name="adb3459d9091d4072b5d3e6d98a064cea"></a>Number</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="a8f4ed4237289424199a4e95234dddd4d"><a name="a8f4ed4237289424199a4e95234dddd4d"></a><a name="a8f4ed4237289424199a4e95234dddd4d"></a>纬度，取值范围：[-90, 90]。</p>
</td>
</tr>
<tr id="rdfd65a3e453b40759b7e1028e49f1e0c"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="a7b6fd63c3b3c4bfca2b919e229685ecd"><a name="a7b6fd63c3b3c4bfca2b919e229685ecd"></a><a name="a7b6fd63c3b3c4bfca2b919e229685ecd"></a>lng</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="a84dcb1cc889e45db86f941d0a0bbba04"><a name="a84dcb1cc889e45db86f941d0a0bbba04"></a><a name="a84dcb1cc889e45db86f941d0a0bbba04"></a>是</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.3 "><p id="a1765b2a85b544f16bfaa294976e09338"><a name="a1765b2a85b544f16bfaa294976e09338"></a><a name="a1765b2a85b544f16bfaa294976e09338"></a>Number</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="ab495354fb1224ac6ad5821261a1b8870"><a name="ab495354fb1224ac6ad5821261a1b8870"></a><a name="ab495354fb1224ac6ad5821261a1b8870"></a>经度，取值范围：[-180, 180]。</p>
</td>
</tr>
</tbody>
</table>

## LatLngBounds<a name="s7da68d05f25f42949a5700ac4cf28a27"></a>

<a name="te1f13b7ef3ca43a2ae44a944809c78b4"></a>
<table><thead align="left"><tr id="r1709eb5741584b7caf97cf0d95cd5406"><th class="cellrowborder" valign="top" width="18%" id="mcps1.1.5.1.1"><p id="a627f4818313449c3bee425b6a3b53f32"><a name="a627f4818313449c3bee425b6a3b53f32"></a><a name="a627f4818313449c3bee425b6a3b53f32"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="14.000000000000002%" id="mcps1.1.5.1.2"><p id="a67e51c169c30452fa053a0d1bd0262e5"><a name="a67e51c169c30452fa053a0d1bd0262e5"></a><a name="a67e51c169c30452fa053a0d1bd0262e5"></a>是否必选</p>
</th>
<th class="cellrowborder" valign="top" width="18%" id="mcps1.1.5.1.3"><p id="a2f66307834d14252b2044aa3a8e696bf"><a name="a2f66307834d14252b2044aa3a8e696bf"></a><a name="a2f66307834d14252b2044aa3a8e696bf"></a>类型</p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.1.5.1.4"><p id="aa6a7ce363d72482090c8f301bf629658"><a name="aa6a7ce363d72482090c8f301bf629658"></a><a name="aa6a7ce363d72482090c8f301bf629658"></a>说明</p>
</th>
</tr>
</thead>
<tbody><tr id="reb9ce15528394cf78ce77f0f791be487"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="ac30a0d9d143241e997f9ba27e119a497"><a name="ac30a0d9d143241e997f9ba27e119a497"></a><a name="ac30a0d9d143241e997f9ba27e119a497"></a>northeast</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="a27397e1635cc4945828accf49a07a515"><a name="a27397e1635cc4945828accf49a07a515"></a><a name="a27397e1635cc4945828accf49a07a515"></a>是</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.3 "><p id="a81b0d8c6da5c4f1cb707384c53e68db3"><a name="a81b0d8c6da5c4f1cb707384c53e68db3"></a><a name="a81b0d8c6da5c4f1cb707384c53e68db3"></a><a href="#s79a8e63ee72b4cb29e350a1fa05b52ce">Coordinate</a></p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="ab95270b207bc47c795fc9856ce7107f7"><a name="ab95270b207bc47c795fc9856ce7107f7"></a><a name="ab95270b207bc47c795fc9856ce7107f7"></a>东北角的位置。</p>
</td>
</tr>
<tr id="ra96381f2a1c7455781fdd7f623babae6"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="a1dcc36d1734d468d85b40b13e86b4607"><a name="a1dcc36d1734d468d85b40b13e86b4607"></a><a name="a1dcc36d1734d468d85b40b13e86b4607"></a>southwest</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="a6b8484d30e9d4e5bab853a59c80835ab"><a name="a6b8484d30e9d4e5bab853a59c80835ab"></a><a name="a6b8484d30e9d4e5bab853a59c80835ab"></a>是</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.3 "><p id="adcef7c66485f489e884fd5cf8917a1bd"><a name="adcef7c66485f489e884fd5cf8917a1bd"></a><a name="adcef7c66485f489e884fd5cf8917a1bd"></a><a href="#s79a8e63ee72b4cb29e350a1fa05b52ce">Coordinate</a></p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="aebcbfa767b7142cf89c5f92953dcd8d2"><a name="aebcbfa767b7142cf89c5f92953dcd8d2"></a><a name="aebcbfa767b7142cf89c5f92953dcd8d2"></a>西南角的位置。</p>
</td>
</tr>
</tbody>
</table>

## OpeningHours<a name="scd3b7bb5f19b4324a1fb8c5da6cda1dc"></a>

<a name="t36af47645b1846c1bdde4e1d9fb28c9e"></a>
<table><thead align="left"><tr id="r653ed8b3ef61437d9f2c619d72272dff"><th class="cellrowborder" valign="top" width="18%" id="mcps1.1.5.1.1"><p id="a435f004d62c5402197e8a2e1780c7653"><a name="a435f004d62c5402197e8a2e1780c7653"></a><a name="a435f004d62c5402197e8a2e1780c7653"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="14.000000000000002%" id="mcps1.1.5.1.2"><p id="aee1cededf36a4ce5974e5f7821edb201"><a name="aee1cededf36a4ce5974e5f7821edb201"></a><a name="aee1cededf36a4ce5974e5f7821edb201"></a>是否必选</p>
</th>
<th class="cellrowborder" valign="top" width="18%" id="mcps1.1.5.1.3"><p id="a5d84673bc3164f769ee0cfbe712e2553"><a name="a5d84673bc3164f769ee0cfbe712e2553"></a><a name="a5d84673bc3164f769ee0cfbe712e2553"></a>类型</p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.1.5.1.4"><p id="aa2467cff17aa4cff8ab734423778a598"><a name="aa2467cff17aa4cff8ab734423778a598"></a><a name="aa2467cff17aa4cff8ab734423778a598"></a>说明</p>
</th>
</tr>
</thead>
<tbody><tr id="row1161194705613"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="a3753d2b42f6e4392824859571278d0ac"><a name="a3753d2b42f6e4392824859571278d0ac"></a><a name="a3753d2b42f6e4392824859571278d0ac"></a>texts</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="ad92d8730b6544a8fad02580f63bd635a"><a name="ad92d8730b6544a8fad02580f63bd635a"></a><a name="ad92d8730b6544a8fad02580f63bd635a"></a>是</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.3 "><p id="aff897fb877fb4aa784f71ca0e9fd0a29"><a name="aff897fb877fb4aa784f71ca0e9fd0a29"></a><a name="aff897fb877fb4aa784f71ca0e9fd0a29"></a>Array&lt;String&gt;</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="a27ec30e8e12f4cff86b512aabb325713"><a name="a27ec30e8e12f4cff86b512aabb325713"></a><a name="a27ec30e8e12f4cff86b512aabb325713"></a>每个星期的开放时间段的描述。</p>
</td>
</tr>
<tr id="row45359262341"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="a5dd3d82cd13a47efa0cb7148ac167ab6"><a name="a5dd3d82cd13a47efa0cb7148ac167ab6"></a><a name="a5dd3d82cd13a47efa0cb7148ac167ab6"></a>periods</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="a43b739a5068f4ef18a5a70ddb9be17dc"><a name="a43b739a5068f4ef18a5a70ddb9be17dc"></a><a name="a43b739a5068f4ef18a5a70ddb9be17dc"></a>是</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.3 "><p id="a182728a3cda34fa5a767ee2136cd7a87"><a name="a182728a3cda34fa5a767ee2136cd7a87"></a><a name="a182728a3cda34fa5a767ee2136cd7a87"></a>Array&lt;<a href="#sce7a427d5dd64ceb8f626b933444a38e">Period</a>&gt;</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="a757f872b12a94e48a41b4eb8d0342cf4"><a name="a757f872b12a94e48a41b4eb8d0342cf4"></a><a name="a757f872b12a94e48a41b4eb8d0342cf4"></a>开放时间段的详细说明。</p>
</td>
</tr>
</tbody>
</table>

## Path<a name="sfb73d14e02cb4b2ebab582421fa618a7"></a>

<a name="tef08540534074e0bb9e36dc921197ceb"></a>
<table><thead align="left"><tr id="r5a81956788f14199bda33a62a979b6b0"><th class="cellrowborder" valign="top" width="18%" id="mcps1.1.5.1.1"><p id="a3a6625096b6a46e3a535f0b8ebd90921"><a name="a3a6625096b6a46e3a535f0b8ebd90921"></a><a name="a3a6625096b6a46e3a535f0b8ebd90921"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="14.000000000000002%" id="mcps1.1.5.1.2"><p id="acdb4f63b3eac45289acbbd56ed778691"><a name="acdb4f63b3eac45289acbbd56ed778691"></a><a name="acdb4f63b3eac45289acbbd56ed778691"></a>是否必选</p>
</th>
<th class="cellrowborder" valign="top" width="18%" id="mcps1.1.5.1.3"><p id="adc210ff266ba4b3d85fca81d7bfa192d"><a name="adc210ff266ba4b3d85fca81d7bfa192d"></a><a name="adc210ff266ba4b3d85fca81d7bfa192d"></a>类型</p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.1.5.1.4"><p id="afb5ba5ede01f45ebbbbbfaf7a3d80a3d"><a name="afb5ba5ede01f45ebbbbbfaf7a3d80a3d"></a><a name="afb5ba5ede01f45ebbbbbfaf7a3d80a3d"></a>说明</p>
</th>
</tr>
</thead>
<tbody><tr id="r8539741514a649fe9b1ead3175756169"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="a1964245a92b544b0bf422ef647b7b7c3"><a name="a1964245a92b544b0bf422ef647b7b7c3"></a><a name="a1964245a92b544b0bf422ef647b7b7c3"></a>steps</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="a66e813e976b64a809a17503e57b3e24c"><a name="a66e813e976b64a809a17503e57b3e24c"></a><a name="a66e813e976b64a809a17503e57b3e24c"></a>是</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.3 "><p id="a59c71c1de03f44d6891c1d3e95d14a10"><a name="a59c71c1de03f44d6891c1d3e95d14a10"></a><a name="a59c71c1de03f44d6891c1d3e95d14a10"></a>Array&lt;<a href="#s6220d04bd11944c184eeb757cc11c0d9">Step</a>&gt;</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="af46a58c84ae643b58b09eee509e12a7d"><a name="af46a58c84ae643b58b09eee509e12a7d"></a><a name="af46a58c84ae643b58b09eee509e12a7d"></a>路线分段信息。</p>
</td>
</tr>
<tr id="r993122e66db24f58babb6120d26e7d1a"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="a9d5dd84fc881458dacebfbd56338ecb1"><a name="a9d5dd84fc881458dacebfbd56338ecb1"></a><a name="a9d5dd84fc881458dacebfbd56338ecb1"></a>distance</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="af772ae3d4a814f95bafc6720a1672854"><a name="af772ae3d4a814f95bafc6720a1672854"></a><a name="af772ae3d4a814f95bafc6720a1672854"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.3 "><p id="a7d6aaa016c5b43cbae7021d9f3a5379a"><a name="a7d6aaa016c5b43cbae7021d9f3a5379a"></a><a name="a7d6aaa016c5b43cbae7021d9f3a5379a"></a>Number</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="a1336c2cd2bcf4912b8c67fbf75e9b184"><a name="a1336c2cd2bcf4912b8c67fbf75e9b184"></a><a name="a1336c2cd2bcf4912b8c67fbf75e9b184"></a>行驶距离，单位：米。</p>
</td>
</tr>
<tr id="r2447195274d045abbb65beb12b9702cf"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="a86b2a06d3c5d4e5e938146a19f574e83"><a name="a86b2a06d3c5d4e5e938146a19f574e83"></a><a name="a86b2a06d3c5d4e5e938146a19f574e83"></a>duration</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="a5aa053274d094778bf04a49fab43ce5d"><a name="a5aa053274d094778bf04a49fab43ce5d"></a><a name="a5aa053274d094778bf04a49fab43ce5d"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.3 "><p id="ac376e9f12616487fb226507607daba3c"><a name="ac376e9f12616487fb226507607daba3c"></a><a name="ac376e9f12616487fb226507607daba3c"></a>Number</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="ab0191e8659e3444b9218a31bdb1f61b0"><a name="ab0191e8659e3444b9218a31bdb1f61b0"></a><a name="ab0191e8659e3444b9218a31bdb1f61b0"></a>行驶时长，单位：秒。</p>
</td>
</tr>
<tr id="r1de05a4f82b64108a50adfcbfc0c8c9a"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="a50c8bcdbb3134015ac84e92864ac9635"><a name="a50c8bcdbb3134015ac84e92864ac9635"></a><a name="a50c8bcdbb3134015ac84e92864ac9635"></a>distanceText</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="a3b83a674cbd54d7c9a2da09e3b06c004"><a name="a3b83a674cbd54d7c9a2da09e3b06c004"></a><a name="a3b83a674cbd54d7c9a2da09e3b06c004"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.3 "><p id="ad530012a97184e36ac9a4cfa16693c86"><a name="ad530012a97184e36ac9a4cfa16693c86"></a><a name="ad530012a97184e36ac9a4cfa16693c86"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="afb74319d1d6a4b53b8fd2c89b1253a4c"><a name="afb74319d1d6a4b53b8fd2c89b1253a4c"></a><a name="afb74319d1d6a4b53b8fd2c89b1253a4c"></a>Distance的文本描述。</p>
</td>
</tr>
<tr id="r5094beca08b1418dbe4febfee0a56c9c"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="a17d3d850682b47889b33f3a1daf30171"><a name="a17d3d850682b47889b33f3a1daf30171"></a><a name="a17d3d850682b47889b33f3a1daf30171"></a>durationInTraffic</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="ad8395ff87d61479f89455bbc62054f7f"><a name="ad8395ff87d61479f89455bbc62054f7f"></a><a name="ad8395ff87d61479f89455bbc62054f7f"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.3 "><p id="aa50ca8870aa44464a814f1297c4780cb"><a name="aa50ca8870aa44464a814f1297c4780cb"></a><a name="aa50ca8870aa44464a814f1297c4780cb"></a>Number</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="a320e2b1ed8134d80be841e53c0b4b066"><a name="a320e2b1ed8134d80be841e53c0b4b066"></a><a name="a320e2b1ed8134d80be841e53c0b4b066"></a>基于实时路况计算出来的行驶时长，单位：秒。</p>
</td>
</tr>
<tr id="r4440995437f54e41ac244ab728a1357f"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="a724ee46662964f46b4b1985494a13fe9"><a name="a724ee46662964f46b4b1985494a13fe9"></a><a name="a724ee46662964f46b4b1985494a13fe9"></a>durationText</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="a4e209997ac3748c1a635f829a0ffdcdc"><a name="a4e209997ac3748c1a635f829a0ffdcdc"></a><a name="a4e209997ac3748c1a635f829a0ffdcdc"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.3 "><p id="a8bda030b14f249d697747332b9074c29"><a name="a8bda030b14f249d697747332b9074c29"></a><a name="a8bda030b14f249d697747332b9074c29"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="acfc95c0fe9d64629ab40b5f63fdf96fe"><a name="acfc95c0fe9d64629ab40b5f63fdf96fe"></a><a name="acfc95c0fe9d64629ab40b5f63fdf96fe"></a>Duration的文本描述。</p>
</td>
</tr>
<tr id="rb002533503024033912fb37d5a2775ea"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="a118d3e41d0924205b940c0306baed998"><a name="a118d3e41d0924205b940c0306baed998"></a><a name="a118d3e41d0924205b940c0306baed998"></a>startLocation</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="a8b7d236d24ea46fb876d7e14abbef909"><a name="a8b7d236d24ea46fb876d7e14abbef909"></a><a name="a8b7d236d24ea46fb876d7e14abbef909"></a>是</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.3 "><p id="ae120cef7d3254347a5520e13518afec0"><a name="ae120cef7d3254347a5520e13518afec0"></a><a name="ae120cef7d3254347a5520e13518afec0"></a><a href="#s79a8e63ee72b4cb29e350a1fa05b52ce">Coordinate</a></p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="a1fedace5b7a140469064a6fd021c66e9"><a name="a1fedace5b7a140469064a6fd021c66e9"></a><a name="a1fedace5b7a140469064a6fd021c66e9"></a>出发地的经纬度。</p>
</td>
</tr>
<tr id="r5e2758dac91046bb8643a289a9822c42"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="a9fea68e136f94c5c946467b1be2a99e1"><a name="a9fea68e136f94c5c946467b1be2a99e1"></a><a name="a9fea68e136f94c5c946467b1be2a99e1"></a>startAddress</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="a81308f65f175445ab803d7f84e59644f"><a name="a81308f65f175445ab803d7f84e59644f"></a><a name="a81308f65f175445ab803d7f84e59644f"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.3 "><p id="a5f706ccb04024c4bbd42c4040e5646e5"><a name="a5f706ccb04024c4bbd42c4040e5646e5"></a><a name="a5f706ccb04024c4bbd42c4040e5646e5"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="a37f7749167b943f48b0da37bd68dafae"><a name="a37f7749167b943f48b0da37bd68dafae"></a><a name="a37f7749167b943f48b0da37bd68dafae"></a>startLocation对应的地址详情。</p>
</td>
</tr>
<tr id="r9b827633147a48b2b985b773e2b8d522"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="a2146804aa2a241f59d3c9883e2d2bba3"><a name="a2146804aa2a241f59d3c9883e2d2bba3"></a><a name="a2146804aa2a241f59d3c9883e2d2bba3"></a>endLocation</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="a8b6d4702ac6b49f1b56ce19dacea39e7"><a name="a8b6d4702ac6b49f1b56ce19dacea39e7"></a><a name="a8b6d4702ac6b49f1b56ce19dacea39e7"></a>是</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.3 "><p id="a0ec47a11a40948069aad6d7718afe353"><a name="a0ec47a11a40948069aad6d7718afe353"></a><a name="a0ec47a11a40948069aad6d7718afe353"></a><a href="#s79a8e63ee72b4cb29e350a1fa05b52ce">Coordinate</a></p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="aa3215b3518344a96a984d6875f0e6797"><a name="aa3215b3518344a96a984d6875f0e6797"></a><a name="aa3215b3518344a96a984d6875f0e6797"></a>目的地的经纬度。</p>
</td>
</tr>
<tr id="r764e5740527e4e208edc648b0ed70ea7"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="a3042e048a12146899b5420630f8b7317"><a name="a3042e048a12146899b5420630f8b7317"></a><a name="a3042e048a12146899b5420630f8b7317"></a>endAddress</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="aabbe0492025745ffbedea57cc0150ba5"><a name="aabbe0492025745ffbedea57cc0150ba5"></a><a name="aabbe0492025745ffbedea57cc0150ba5"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.3 "><p id="ae999206edf034d0dbd5e0bf282570476"><a name="ae999206edf034d0dbd5e0bf282570476"></a><a name="ae999206edf034d0dbd5e0bf282570476"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="a9c14ae215c1f45a4ad7b57479f86bcae"><a name="a9c14ae215c1f45a4ad7b57479f86bcae"></a><a name="a9c14ae215c1f45a4ad7b57479f86bcae"></a>endLocation对应的地址详情。</p>
</td>
</tr>
</tbody>
</table>

## Period<a name="sce7a427d5dd64ceb8f626b933444a38e"></a>

<a name="tb6069cdca0104a4ba40c7bf914ae780f"></a>
<table><thead align="left"><tr id="r366ad05233674490aaf475862a26d47c"><th class="cellrowborder" valign="top" width="18%" id="mcps1.1.5.1.1"><p id="ab625308e7da64174b8633457b9207ce7"><a name="ab625308e7da64174b8633457b9207ce7"></a><a name="ab625308e7da64174b8633457b9207ce7"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="14.000000000000002%" id="mcps1.1.5.1.2"><p id="a2fc774eaf5264a699fca989186c5ba0f"><a name="a2fc774eaf5264a699fca989186c5ba0f"></a><a name="a2fc774eaf5264a699fca989186c5ba0f"></a>是否必选</p>
</th>
<th class="cellrowborder" valign="top" width="18%" id="mcps1.1.5.1.3"><p id="a48b7c377b9c84b17b417c6c6c72d4457"><a name="a48b7c377b9c84b17b417c6c6c72d4457"></a><a name="a48b7c377b9c84b17b417c6c6c72d4457"></a>类型</p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.1.5.1.4"><p id="a45896ef17bf3478ebe0b5f6d1e55ba44"><a name="a45896ef17bf3478ebe0b5f6d1e55ba44"></a><a name="a45896ef17bf3478ebe0b5f6d1e55ba44"></a>说明</p>
</th>
</tr>
</thead>
<tbody><tr id="r5176dda9eb164f1bb873d2692ee4db37"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="a2937400f85494464894d4d8a3346d5a6"><a name="a2937400f85494464894d4d8a3346d5a6"></a><a name="a2937400f85494464894d4d8a3346d5a6"></a>open</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="adde6e28192be4eb2a6bc9db77f6f6121"><a name="adde6e28192be4eb2a6bc9db77f6f6121"></a><a name="adde6e28192be4eb2a6bc9db77f6f6121"></a>是</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.3 "><p id="a64a401df46544a85b8204f60f6361154"><a name="a64a401df46544a85b8204f60f6361154"></a><a name="a64a401df46544a85b8204f60f6361154"></a><a href="#s8991b20f989c463097423b028a83fe10">TimeOfWeek</a></p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="a3b7e4e60e82d429a9b623492ac9e5409"><a name="a3b7e4e60e82d429a9b623492ac9e5409"></a><a name="a3b7e4e60e82d429a9b623492ac9e5409"></a>开放时间。</p>
</td>
</tr>
<tr id="r373dd1caa17d43ce97baa714e98caf35"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="a2b9ed09562bf4e38b6ef8bb8277faf18"><a name="a2b9ed09562bf4e38b6ef8bb8277faf18"></a><a name="a2b9ed09562bf4e38b6ef8bb8277faf18"></a>close</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="a6060b0a0449c4c0c915cbbf1d7ee1443"><a name="a6060b0a0449c4c0c915cbbf1d7ee1443"></a><a name="a6060b0a0449c4c0c915cbbf1d7ee1443"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.3 "><p id="a0c9de282910f46a99b4e0e9975d99c7a"><a name="a0c9de282910f46a99b4e0e9975d99c7a"></a><a name="a0c9de282910f46a99b4e0e9975d99c7a"></a><a href="#s8991b20f989c463097423b028a83fe10">TimeOfWeek</a></p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="a04e5b1a7de9442f788f5b8173be3c504"><a name="a04e5b1a7de9442f788f5b8173be3c504"></a><a name="a04e5b1a7de9442f788f5b8173be3c504"></a>关闭时间。</p>
</td>
</tr>
</tbody>
</table>

## Poi<a name="sd921064d432d44689bea55491a6c96b8"></a>

<a name="tb35933d664e54c5d8791242865ac2ac6"></a>
<table><thead align="left"><tr id="r7b24b9f3d3fc42c08859561c1ba6d4ee"><th class="cellrowborder" valign="top" width="18%" id="mcps1.1.5.1.1"><p id="ae2e1008cab064112ab63c1a939832b8b"><a name="ae2e1008cab064112ab63c1a939832b8b"></a><a name="ae2e1008cab064112ab63c1a939832b8b"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="14.000000000000002%" id="mcps1.1.5.1.2"><p id="a57145ae1f28b444682e877dc42fc14b8"><a name="a57145ae1f28b444682e877dc42fc14b8"></a><a name="a57145ae1f28b444682e877dc42fc14b8"></a>是否必选</p>
</th>
<th class="cellrowborder" valign="top" width="18%" id="mcps1.1.5.1.3"><p id="a3ffc0732b951402c91886de04a0e8a7e"><a name="a3ffc0732b951402c91886de04a0e8a7e"></a><a name="a3ffc0732b951402c91886de04a0e8a7e"></a>类型</p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.1.5.1.4"><p id="acab434fbc8934a9aa2e690af38366f27"><a name="acab434fbc8934a9aa2e690af38366f27"></a><a name="acab434fbc8934a9aa2e690af38366f27"></a>说明</p>
</th>
</tr>
</thead>
<tbody><tr id="r9b80da53335a4c09a9db05dcc786481b"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="ad58b4b55f4f44de185fc150fa3fc84b6"><a name="ad58b4b55f4f44de185fc150fa3fc84b6"></a><a name="ad58b4b55f4f44de185fc150fa3fc84b6"></a>poiTypes</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="a47d58674dca14caa953b409781023cd4"><a name="a47d58674dca14caa953b409781023cd4"></a><a name="a47d58674dca14caa953b409781023cd4"></a>是</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.3 "><p id="a5e284a62bfd14bcabc46cbf8c877420a"><a name="a5e284a62bfd14bcabc46cbf8c877420a"></a><a name="a5e284a62bfd14bcabc46cbf8c877420a"></a>Array&lt;String&gt;</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="a8c78f2dc4c304a6a94deb363d7575b04"><a name="a8c78f2dc4c304a6a94deb363d7575b04"></a><a name="a8c78f2dc4c304a6a94deb363d7575b04"></a>POI类型。</p>
</td>
</tr>
<tr id="row1197712283014"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="p15327143102520"><a name="p15327143102520"></a><a name="p15327143102520"></a>hwPoiTypes</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="p1275634617252"><a name="p1275634617252"></a><a name="p1275634617252"></a>是</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.3 "><p id="p156527171915"><a name="p156527171915"></a><a name="p156527171915"></a>Array&lt;String&gt;</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="p103285436258"><a name="p103285436258"></a><a name="p103285436258"></a>华为POI分类体系。</p>
<div class="note" id="note2051491816525"><a name="note2051491816525"></a><a name="note2051491816525"></a><span class="notetitle"> 说明： </span><div class="notebody"><p id="p1151411812524"><a name="p1151411812524"></a><a name="p1151411812524"></a>推荐使用hwPoiTypes。</p>
</div></div>
</td>
</tr>
<tr id="re30be905f1504f64a9d280867c287a85"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="a71b125ee630e4490a2a153ac54f852a2"><a name="a71b125ee630e4490a2a153ac54f852a2"></a><a name="a71b125ee630e4490a2a153ac54f852a2"></a>phone</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="a5ac0cc4bedc8403d9fa89cae9ccfcc2f"><a name="a5ac0cc4bedc8403d9fa89cae9ccfcc2f"></a><a name="a5ac0cc4bedc8403d9fa89cae9ccfcc2f"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.3 "><p id="ac664127644d5443fabd668a27fb81d09"><a name="ac664127644d5443fabd668a27fb81d09"></a><a name="ac664127644d5443fabd668a27fb81d09"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="a81668343c07845acb5ffd99e9cce48f9"><a name="a81668343c07845acb5ffd99e9cce48f9"></a><a name="a81668343c07845acb5ffd99e9cce48f9"></a>电话号码。</p>
</td>
</tr>
<tr id="reffaf49b90c44f61802b55bd3922cc70"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="aec08800074454193ad18d1d67750f9f5"><a name="aec08800074454193ad18d1d67750f9f5"></a><a name="aec08800074454193ad18d1d67750f9f5"></a>internationalPhone</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="a772f1d673a254e02b32dcedf2e9e0e23"><a name="a772f1d673a254e02b32dcedf2e9e0e23"></a><a name="a772f1d673a254e02b32dcedf2e9e0e23"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.3 "><p id="ae2ba8cf6f23141359837f67b0ced5a5e"><a name="ae2ba8cf6f23141359837f67b0ced5a5e"></a><a name="ae2ba8cf6f23141359837f67b0ced5a5e"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="aebb1be9a3873444dbeeca2103e6b666c"><a name="aebb1be9a3873444dbeeca2103e6b666c"></a><a name="aebb1be9a3873444dbeeca2103e6b666c"></a>国际电话号码。</p>
</td>
</tr>
<tr id="r7145e54b075b475aa18ef548ce0d4b24"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="a90ab71d5573a4c459306717832d83ffa"><a name="a90ab71d5573a4c459306717832d83ffa"></a><a name="a90ab71d5573a4c459306717832d83ffa"></a>rating</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="a8efede544f184a259bc34a5368642772"><a name="a8efede544f184a259bc34a5368642772"></a><a name="a8efede544f184a259bc34a5368642772"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.3 "><p id="ad3ae28c05af2471d9f028066290b880b"><a name="ad3ae28c05af2471d9f028066290b880b"></a><a name="ad3ae28c05af2471d9f028066290b880b"></a>Number</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="af1e6e696feba4ebd8317bdda6a515cdc"><a name="af1e6e696feba4ebd8317bdda6a515cdc"></a><a name="af1e6e696feba4ebd8317bdda6a515cdc"></a>评分。</p>
</td>
</tr>
<tr id="r4005748856f74a97a3f5b80938e913b0"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="abffe3ac1e3bf406c8561157acd4d476f"><a name="abffe3ac1e3bf406c8561157acd4d476f"></a><a name="abffe3ac1e3bf406c8561157acd4d476f"></a>websiteUrl</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="a082ff5da69654ea0b4cd8370303a7ddf"><a name="a082ff5da69654ea0b4cd8370303a7ddf"></a><a name="a082ff5da69654ea0b4cd8370303a7ddf"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.3 "><p id="a48bf3e6e8a304c41b710652b18229bee"><a name="a48bf3e6e8a304c41b710652b18229bee"></a><a name="a48bf3e6e8a304c41b710652b18229bee"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="a252eb75edea54a7db5b4fe8628ef6b7c"><a name="a252eb75edea54a7db5b4fe8628ef6b7c"></a><a name="a252eb75edea54a7db5b4fe8628ef6b7c"></a>网址。</p>
</td>
</tr>
<tr id="r4798097cb2ff4a8aab08dc12b6bdd43c"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="a062bdc4155264b0c96d411a48fbb28ae"><a name="a062bdc4155264b0c96d411a48fbb28ae"></a><a name="a062bdc4155264b0c96d411a48fbb28ae"></a>openingHours</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="a40b79f4cadca4d6d80dac8a86e634b89"><a name="a40b79f4cadca4d6d80dac8a86e634b89"></a><a name="a40b79f4cadca4d6d80dac8a86e634b89"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.3 "><p id="abb14a1a8cfe047288ea33f5a6f5e75dc"><a name="abb14a1a8cfe047288ea33f5a6f5e75dc"></a><a name="abb14a1a8cfe047288ea33f5a6f5e75dc"></a><a href="#scd3b7bb5f19b4324a1fb8c5da6cda1dc">OpeningHours</a></p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="a2283bde8645749bcaa0c75061a1388a8"><a name="a2283bde8645749bcaa0c75061a1388a8"></a><a name="a2283bde8645749bcaa0c75061a1388a8"></a>营业时间。</p>
</td>
</tr>
<tr id="r5f8aeb98a60d406db6ab4c939c29b772"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="ac7362e0981bf448bb62bc63747881bc5"><a name="ac7362e0981bf448bb62bc63747881bc5"></a><a name="ac7362e0981bf448bb62bc63747881bc5"></a>photoUrls</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="ace5d913110b7434fbfe98bddaf28b3d9"><a name="ace5d913110b7434fbfe98bddaf28b3d9"></a><a name="ace5d913110b7434fbfe98bddaf28b3d9"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.3 "><p id="a46c48596c8314eb5ba292d1dacebadf8"><a name="a46c48596c8314eb5ba292d1dacebadf8"></a><a name="a46c48596c8314eb5ba292d1dacebadf8"></a>Array&lt;String&gt;</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="a00eddc7634ed4c14921b9b15462d9a98"><a name="a00eddc7634ed4c14921b9b15462d9a98"></a><a name="a00eddc7634ed4c14921b9b15462d9a98"></a>图片地址。</p>
</td>
</tr>
<tr id="row53241229184220"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="p1632519295428"><a name="p1632519295428"></a><a name="p1632519295428"></a>priceLevel</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="p18325182914420"><a name="p18325182914420"></a><a name="p18325182914420"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.3 "><p id="p892385118426"><a name="p892385118426"></a><a name="p892385118426"></a>Number</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="p10514201634310"><a name="p10514201634310"></a><a name="p10514201634310"></a>价格等级，取值范围：[0, 4]。</p>
<div class="note" id="note1994519321311"><a name="note1994519321311"></a><a name="note1994519321311"></a><span class="notetitle"> 说明： </span><div class="notebody"><p id="p19451332123115"><a name="p19451332123115"></a><a name="p19451332123115"></a>仅地点详情接口返回。</p>
</div></div>
</td>
</tr>
<tr id="row1660122165914"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="p121131244135612"><a name="p121131244135612"></a><a name="p121131244135612"></a>businessStatus</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="p1111416445568"><a name="p1111416445568"></a><a name="p1111416445568"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.3 "><p id="p41991118185712"><a name="p41991118185712"></a><a name="p41991118185712"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="p929215264574"><a name="p929215264574"></a><a name="p929215264574"></a>营业状态，其中包括：</p>
<a name="ul105851894582"></a><a name="ul105851894582"></a><ul id="ul105851894582"><li>OPEN_NOW：正在营业。</li><li>CLOSE_NOW：已休息。</li><li>CLOSED_TEMPORARILY：临时关闭。</li><li>CLOSED_PERMANENTLY：永久关闭。</li></ul>
<div class="note" id="note961381019294"><a name="note961381019294"></a><a name="note961381019294"></a><span class="notetitle"> 说明： </span><div class="notebody"><p id="p061311018299"><a name="p061311018299"></a><a name="p061311018299"></a>仅地点详情接口返回。</p>
</div></div>
</td>
</tr>
</tbody>
</table>

## Route<a name="scff6465e40704ddf9d95d3572e9e61bc"></a>

<a name="tad26ce28bb8844aa96314d1e83b1107d"></a>
<table><thead align="left"><tr id="rc716f289b6034561ad9a10055e292735"><th class="cellrowborder" valign="top" width="18%" id="mcps1.1.6.1.1"><p id="ae3a7291d6f1b46529c934c90441a27e2"><a name="ae3a7291d6f1b46529c934c90441a27e2"></a><a name="ae3a7291d6f1b46529c934c90441a27e2"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="14.000000000000002%" id="mcps1.1.6.1.2"><p id="a19d962b9307b43ac9c29a7f2602d7ad9"><a name="a19d962b9307b43ac9c29a7f2602d7ad9"></a><a name="a19d962b9307b43ac9c29a7f2602d7ad9"></a>是否必选</p>
</th>
<th class="cellrowborder" valign="top" width="18%" id="mcps1.1.6.1.3"><p id="a57ef6f7760294926b380d06987673563"><a name="a57ef6f7760294926b380d06987673563"></a><a name="a57ef6f7760294926b380d06987673563"></a>类型</p>
</th>
<th class="cellrowborder" valign="top" width="36.6%" id="mcps1.1.6.1.4"><p id="a51737629d77547eba72bae022d6fc391"><a name="a51737629d77547eba72bae022d6fc391"></a><a name="a51737629d77547eba72bae022d6fc391"></a>说明</p>
</th>
<th class="cellrowborder" valign="top" width="13.4%" id="mcps1.1.6.1.5"><p id="p73571743124319"><a name="p73571743124319"></a><a name="p73571743124319"></a>取值</p>
</th>
</tr>
</thead>
<tbody><tr id="r7c83234d9244461ba5151954cc6fef6e"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.6.1.1 "><p id="ad5bfb057a3694a8c9fc82c972ccee3b2"><a name="ad5bfb057a3694a8c9fc82c972ccee3b2"></a><a name="ad5bfb057a3694a8c9fc82c972ccee3b2"></a>paths</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.6.1.2 "><p id="a587210b1265f40b18bbc757f300d9e3a"><a name="a587210b1265f40b18bbc757f300d9e3a"></a><a name="a587210b1265f40b18bbc757f300d9e3a"></a>是</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.6.1.3 "><p id="a33a548340c364fbe88340eb97efd06f5"><a name="a33a548340c364fbe88340eb97efd06f5"></a><a name="a33a548340c364fbe88340eb97efd06f5"></a>Array&lt;<a href="#sfb73d14e02cb4b2ebab582421fa618a7">Path</a>&gt;</p>
</td>
<td class="cellrowborder" valign="top" width="36.6%" headers="mcps1.1.6.1.4 "><p id="a7eae10a34d794af7b29632d651b66e5a"><a name="a7eae10a34d794af7b29632d651b66e5a"></a><a name="a7eae10a34d794af7b29632d651b66e5a"></a>路线规划信息。</p>
</td>
<td class="cellrowborder" valign="top" width="13.4%" headers="mcps1.1.6.1.5 "><p id="p14358154316432"><a name="p14358154316432"></a><a name="p14358154316432"></a>-</p>
</td>
</tr>
<tr id="red4c7a52ef7e4ecaa245bfa6761bc117"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.6.1.1 "><p id="af56f8a2ef916436383e7ece9ad47deb5"><a name="af56f8a2ef916436383e7ece9ad47deb5"></a><a name="af56f8a2ef916436383e7ece9ad47deb5"></a>optimizedWaypoints</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.6.1.2 "><p id="a369f49577f304c2287dc68eb1f78b9cc"><a name="a369f49577f304c2287dc68eb1f78b9cc"></a><a name="a369f49577f304c2287dc68eb1f78b9cc"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.6.1.3 "><p id="afc0063ded7fc470f9be36a69e9dd4286"><a name="afc0063ded7fc470f9be36a69e9dd4286"></a><a name="afc0063ded7fc470f9be36a69e9dd4286"></a>Array&lt;Number&gt;</p>
</td>
<td class="cellrowborder" valign="top" width="36.6%" headers="mcps1.1.6.1.4 "><p id="a41c2ed44dc4d49f0bd618bd89a756763"><a name="a41c2ed44dc4d49f0bd618bd89a756763"></a><a name="a41c2ed44dc4d49f0bd618bd89a756763"></a>当viaType=false且optimize=true时才会有结果，表示进行路径优化之后途径点的索引。</p>
</td>
<td class="cellrowborder" valign="top" width="13.4%" headers="mcps1.1.6.1.5 "><p id="p16358104384314"><a name="p16358104384314"></a><a name="p16358104384314"></a>-</p>
</td>
</tr>
<tr id="r92b6538c58f3458db9c178ba5b22c687"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.6.1.1 "><p id="ac5485d4b673f4d7c9b4b56467976b854"><a name="ac5485d4b673f4d7c9b4b56467976b854"></a><a name="ac5485d4b673f4d7c9b4b56467976b854"></a>bounds</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.6.1.2 "><p id="a5d71d21cc5164cbbb1394d39618a394d"><a name="a5d71d21cc5164cbbb1394d39618a394d"></a><a name="a5d71d21cc5164cbbb1394d39618a394d"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.6.1.3 "><p id="a1b01102c01464396b771a0d1842a7f5c"><a name="a1b01102c01464396b771a0d1842a7f5c"></a><a name="a1b01102c01464396b771a0d1842a7f5c"></a><a href="#s1b98984709334fa7a5cf8c7a04d4dba5">CoordinateBounds</a></p>
</td>
<td class="cellrowborder" valign="top" width="36.6%" headers="mcps1.1.6.1.4 "><p id="a686f98f7ef194357a1858da934ba009d"><a name="a686f98f7ef194357a1858da934ba009d"></a><a name="a686f98f7ef194357a1858da934ba009d"></a>路线边界范围。</p>
</td>
<td class="cellrowborder" valign="top" width="13.4%" headers="mcps1.1.6.1.5 "><p id="p1435854304318"><a name="p1435854304318"></a><a name="p1435854304318"></a>-</p>
</td>
</tr>
<tr id="row15833023142810"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.6.1.1 "><p id="p1883317237289"><a name="p1883317237289"></a><a name="p1883317237289"></a>hasRestrictedRoad</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.6.1.2 "><p id="p6870102561019"><a name="p6870102561019"></a><a name="p6870102561019"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.6.1.3 "><p id="p783482314287"><a name="p783482314287"></a><a name="p783482314287"></a>Number</p>
</td>
<td class="cellrowborder" valign="top" width="36.6%" headers="mcps1.1.6.1.4 "><p id="p17834102372816"><a name="p17834102372816"></a><a name="p17834102372816"></a>此路段包含私家/限制用途。</p>
</td>
<td class="cellrowborder" rowspan="9" valign="top" width="13.4%" headers="mcps1.1.6.1.5 "><p id="p7987175010389"><a name="p7987175010389"></a><a name="p7987175010389"></a>取值包括：</p>
<a name="ul16197141823415"></a><a name="ul16197141823415"></a><ul id="ul16197141823415"><li>0：没有</li><li>1：有</li></ul>
</td>
</tr>
<tr id="row149643373287"><td class="cellrowborder" valign="top" headers="mcps1.1.6.1.1 "><p id="p119651937102819"><a name="p119651937102819"></a><a name="p119651937102819"></a>dstInRestrictedArea</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.6.1.2 "><p id="p8150102771010"><a name="p8150102771010"></a><a name="p8150102771010"></a>否</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.6.1.3 "><p id="p3752134815910"><a name="p3752134815910"></a><a name="p3752134815910"></a>Number</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.6.1.4 "><p id="p14965143712812"><a name="p14965143712812"></a><a name="p14965143712812"></a>终点在限制区域，进入前请确认。</p>
</td>
</tr>
<tr id="row193221548152818"><td class="cellrowborder" valign="top" headers="mcps1.1.6.1.1 "><p id="p1332254817283"><a name="p1332254817283"></a><a name="p1332254817283"></a>crossCountry</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.6.1.2 "><p id="p10476192851018"><a name="p10476192851018"></a><a name="p10476192851018"></a>否</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.6.1.3 "><p id="p4112651799"><a name="p4112651799"></a><a name="p4112651799"></a>Number</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.6.1.4 "><p id="p432310481281"><a name="p432310481281"></a><a name="p432310481281"></a>穿越国境线（出发前请确认COVID-19边境限制）。</p>
</td>
</tr>
<tr id="row0320195710280"><td class="cellrowborder" valign="top" headers="mcps1.1.6.1.1 "><p id="p20320125718282"><a name="p20320125718282"></a><a name="p20320125718282"></a>crossMultiCountries</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.6.1.2 "><p id="p1785123011011"><a name="p1785123011011"></a><a name="p1785123011011"></a>否</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.6.1.3 "><p id="p271895210919"><a name="p271895210919"></a><a name="p271895210919"></a>Number</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.6.1.4 "><p id="p53203575287"><a name="p53203575287"></a><a name="p53203575287"></a>穿越（多条）国境线。</p>
</td>
</tr>
<tr id="row1848312862914"><td class="cellrowborder" valign="top" headers="mcps1.1.6.1.1 "><p id="p448320852911"><a name="p448320852911"></a><a name="p448320852911"></a>hasRoughRoad</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.6.1.2 "><p id="p2066273112108"><a name="p2066273112108"></a><a name="p2066273112108"></a>否</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.6.1.3 "><p id="p191310542913"><a name="p191310542913"></a><a name="p191310542913"></a>Number</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.6.1.4 "><p id="p248348122912"><a name="p248348122912"></a><a name="p248348122912"></a>此路段经过崎岖道路。</p>
</td>
</tr>
<tr id="row918515166298"><td class="cellrowborder" valign="top" headers="mcps1.1.6.1.1 "><p id="p418615167294"><a name="p418615167294"></a><a name="p418615167294"></a>dstInDiffTimeZone</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.6.1.2 "><p id="p10310033161016"><a name="p10310033161016"></a><a name="p10310033161016"></a>否</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.6.1.3 "><p id="p152217551495"><a name="p152217551495"></a><a name="p152217551495"></a>Number</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.6.1.4 "><p id="p161861165294"><a name="p161861165294"></a><a name="p161861165294"></a>目的地在不同时区。</p>
</td>
</tr>
<tr id="row11664023132913"><td class="cellrowborder" valign="top" headers="mcps1.1.6.1.1 "><p id="p566432310295"><a name="p566432310295"></a><a name="p566432310295"></a>hasFerry</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.6.1.2 "><p id="p951010432101"><a name="p951010432101"></a><a name="p951010432101"></a>否</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.6.1.3 "><p id="p104931856398"><a name="p104931856398"></a><a name="p104931856398"></a>Number</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.6.1.4 "><p id="p196645236295"><a name="p196645236295"></a><a name="p196645236295"></a>途径轮渡。</p>
</td>
</tr>
<tr id="row20646163015296"><td class="cellrowborder" valign="top" headers="mcps1.1.6.1.1 "><p id="p1064683072914"><a name="p1064683072914"></a><a name="p1064683072914"></a>hasTrafficLight</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.6.1.2 "><p id="p2734144481018"><a name="p2734144481018"></a><a name="p2734144481018"></a>否</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.6.1.3 "><p id="p1687118571992"><a name="p1687118571992"></a><a name="p1687118571992"></a>Number</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.6.1.4 "><p id="p12646630102916"><a name="p12646630102916"></a><a name="p12646630102916"></a>红绿灯。</p>
</td>
</tr>
<tr id="row1540864282917"><td class="cellrowborder" valign="top" headers="mcps1.1.6.1.1 "><p id="p2408124242910"><a name="p2408124242910"></a><a name="p2408124242910"></a>hasTolls</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.6.1.2 "><p id="p79274613106"><a name="p79274613106"></a><a name="p79274613106"></a>否</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.6.1.3 "><p id="p758915916914"><a name="p758915916914"></a><a name="p758915916914"></a>Number</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.6.1.4 "><p id="p1840814428291"><a name="p1840814428291"></a><a name="p1840814428291"></a>此路段含收费站。</p>
</td>
</tr>
<tr id="row1435725513293"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.6.1.1 "><p id="p53574557295"><a name="p53574557295"></a><a name="p53574557295"></a>trafficLightNum</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.6.1.2 "><p id="p12572247101013"><a name="p12572247101013"></a><a name="p12572247101013"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.6.1.3 "><p id="p133571755192911"><a name="p133571755192911"></a><a name="p133571755192911"></a>Number</p>
</td>
<td class="cellrowborder" valign="top" width="36.6%" headers="mcps1.1.6.1.4 "><p id="p9357125542915"><a name="p9357125542915"></a><a name="p9357125542915"></a>红绿灯个数。</p>
</td>
<td class="cellrowborder" valign="top" width="13.4%" headers="mcps1.1.6.1.5 "><p id="p14358144312433"><a name="p14358144312433"></a><a name="p14358144312433"></a>-</p>
</td>
</tr>
<tr id="row03435320122"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.6.1.1 "><p id="p133445361213"><a name="p133445361213"></a><a name="p133445361213"></a>overviewPolyline</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.6.1.2 "><p id="p83419533126"><a name="p83419533126"></a><a name="p83419533126"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.6.1.3 "><p id="p034165311123"><a name="p034165311123"></a><a name="p034165311123"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="36.6%" headers="mcps1.1.6.1.4 "><p id="p034145318123"><a name="p034145318123"></a><a name="p034145318123"></a>该路线的编码后的折线。</p>
</td>
<td class="cellrowborder" valign="top" width="13.4%" headers="mcps1.1.6.1.5 "><p id="p234205301215"><a name="p234205301215"></a><a name="p234205301215"></a>-</p>
</td>
</tr>
</tbody>
</table>

## Site<a name="s60f796f99e2a42589d569ce7de36a113"></a>

<a name="tecd62c6957a44fd6b4c8c40e85d3d98b"></a>
<table><thead align="left"><tr id="r8a235834c47d4425867d7c17e41af419"><th class="cellrowborder" valign="top" width="18%" id="mcps1.1.5.1.1"><p id="a262d9f58acd4455ab567d323ef13d2cd"><a name="a262d9f58acd4455ab567d323ef13d2cd"></a><a name="a262d9f58acd4455ab567d323ef13d2cd"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="14.000000000000002%" id="mcps1.1.5.1.2"><p id="a39168ca926ce4cd5bc4b82de1a3fa7ef"><a name="a39168ca926ce4cd5bc4b82de1a3fa7ef"></a><a name="a39168ca926ce4cd5bc4b82de1a3fa7ef"></a>是否必选</p>
</th>
<th class="cellrowborder" valign="top" width="18%" id="mcps1.1.5.1.3"><p id="a119b6b883aa04f50bb9858cef980564a"><a name="a119b6b883aa04f50bb9858cef980564a"></a><a name="a119b6b883aa04f50bb9858cef980564a"></a>类型</p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.1.5.1.4"><p id="abccb933990a946f9a995fde26f57bd43"><a name="abccb933990a946f9a995fde26f57bd43"></a><a name="abccb933990a946f9a995fde26f57bd43"></a>说明</p>
</th>
</tr>
</thead>
<tbody><tr id="r4f222d8fa2984b42a4ce167aa75da4ba"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="a5a02a5b75fde43d5813ebdcd5d144d7a"><a name="a5a02a5b75fde43d5813ebdcd5d144d7a"></a><a name="a5a02a5b75fde43d5813ebdcd5d144d7a"></a>siteId</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="a45fe70442d844e68a5e61d53169d3799"><a name="a45fe70442d844e68a5e61d53169d3799"></a><a name="a45fe70442d844e68a5e61d53169d3799"></a>是</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.3 "><p id="aedf6a91154894e1ba6455ede16407b6f"><a name="aedf6a91154894e1ba6455ede16407b6f"></a><a name="aedf6a91154894e1ba6455ede16407b6f"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="a1d6740c1876e487eaad3f4216eeb1441"><a name="a1d6740c1876e487eaad3f4216eeb1441"></a><a name="a1d6740c1876e487eaad3f4216eeb1441"></a>地点的唯一主键。</p>
</td>
</tr>
<tr id="r4501cd2d4ee64c1d919fe7eb1f9b87e5"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="aa61809942275445f82aa558fcc62b4c4"><a name="aa61809942275445f82aa558fcc62b4c4"></a><a name="aa61809942275445f82aa558fcc62b4c4"></a>name</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="a10268784fc5844f9afad87796f6c63cd"><a name="a10268784fc5844f9afad87796f6c63cd"></a><a name="a10268784fc5844f9afad87796f6c63cd"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.3 "><p id="a772e7f70f156484891bf5d9cc669c990"><a name="a772e7f70f156484891bf5d9cc669c990"></a><a name="a772e7f70f156484891bf5d9cc669c990"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="a9094d5043e674ba19a01e2e0239295ef"><a name="a9094d5043e674ba19a01e2e0239295ef"></a><a name="a9094d5043e674ba19a01e2e0239295ef"></a>地点名称。</p>
</td>
</tr>
<tr id="r552f61fa469545d1b1c8516a0e5d24fc"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="a185f18acca874c6fa5677c903db83113"><a name="a185f18acca874c6fa5677c903db83113"></a><a name="a185f18acca874c6fa5677c903db83113"></a>formatAddress</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="a4525a238b9de4665b75ffe97f551e31b"><a name="a4525a238b9de4665b75ffe97f551e31b"></a><a name="a4525a238b9de4665b75ffe97f551e31b"></a>是</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.3 "><p id="abafb8e848c77418c9f15f7507bf6bb5c"><a name="abafb8e848c77418c9f15f7507bf6bb5c"></a><a name="abafb8e848c77418c9f15f7507bf6bb5c"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="a21e24573eb6a4716b1c1a06ba167b062"><a name="a21e24573eb6a4716b1c1a06ba167b062"></a><a name="a21e24573eb6a4716b1c1a06ba167b062"></a>格式化的地点详细地址。</p>
</td>
</tr>
<tr id="rdef931ddc8a34367b3f423baa34205d3"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="a2dc91bd936c24802b3ec6b782105b29f"><a name="a2dc91bd936c24802b3ec6b782105b29f"></a><a name="a2dc91bd936c24802b3ec6b782105b29f"></a>address</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="ad1edbcc9fa3b454d9be7cc309e1bcea3"><a name="ad1edbcc9fa3b454d9be7cc309e1bcea3"></a><a name="ad1edbcc9fa3b454d9be7cc309e1bcea3"></a>是</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.3 "><p id="a58d29ab569b9474d817960309e3adc55"><a name="a58d29ab569b9474d817960309e3adc55"></a><a name="a58d29ab569b9474d817960309e3adc55"></a><a href="#s6da2808de27a4fffbe26ce5f892ae08e">AddressDetail</a></p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="aa4732de896cd4331b1babd53dbe3c9fb"><a name="aa4732de896cd4331b1babd53dbe3c9fb"></a><a name="aa4732de896cd4331b1babd53dbe3c9fb"></a>地址详细信息。</p>
</td>
</tr>
<tr id="r80455ec5f2e248e39f7fb39add7e7a2e"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="a1d3d1907c895439189f0b013b8f93644"><a name="a1d3d1907c895439189f0b013b8f93644"></a><a name="a1d3d1907c895439189f0b013b8f93644"></a>location</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="a0f219b787fde423f9b05e97c8b1d113a"><a name="a0f219b787fde423f9b05e97c8b1d113a"></a><a name="a0f219b787fde423f9b05e97c8b1d113a"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.3 "><p id="ae87420c19fcd4425953de8551823c7cd"><a name="ae87420c19fcd4425953de8551823c7cd"></a><a name="ae87420c19fcd4425953de8551823c7cd"></a><a href="#s79a8e63ee72b4cb29e350a1fa05b52ce">Coordinate</a></p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="a176d97b335704749842e23200403b928"><a name="a176d97b335704749842e23200403b928"></a><a name="a176d97b335704749842e23200403b928"></a>地点的经纬度。</p>
</td>
</tr>
<tr id="r8c4e38d1fbf04ff99a089558bcb41055"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="a538ff80f2ce8451e9d21553422b7de84"><a name="a538ff80f2ce8451e9d21553422b7de84"></a><a name="a538ff80f2ce8451e9d21553422b7de84"></a>viewport</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="aafa35354342848c59e958d5fb201372a"><a name="aafa35354342848c59e958d5fb201372a"></a><a name="aafa35354342848c59e958d5fb201372a"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.3 "><p id="a810e0c1908e44b7ba9904f1436c33394"><a name="a810e0c1908e44b7ba9904f1436c33394"></a><a name="a810e0c1908e44b7ba9904f1436c33394"></a><a href="#s1b98984709334fa7a5cf8c7a04d4dba5">CoordinateBounds</a></p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="a3293eba1c76f4f50925c293d99c11bad"><a name="a3293eba1c76f4f50925c293d99c11bad"></a><a name="a3293eba1c76f4f50925c293d99c11bad"></a>地点的视口范围。</p>
<div class="note" id="note6646151193113"><a name="note6646151193113"></a><a name="note6646151193113"></a><span class="notetitle"> 说明： </span><div class="notebody"><p id="p5646171193117"><a name="p5646171193117"></a><a name="p5646171193117"></a>输入提示不支持返回此字段。</p>
</div></div>
</td>
</tr>
<tr id="rbdaee65cfc004d94acfb79065c1d1c37"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="a416a53dc3fde43049fba42a3c318fda3"><a name="a416a53dc3fde43049fba42a3c318fda3"></a><a name="a416a53dc3fde43049fba42a3c318fda3"></a>distance</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="a480c71fcd1b64362ae238b8950497603"><a name="a480c71fcd1b64362ae238b8950497603"></a><a name="a480c71fcd1b64362ae238b8950497603"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.3 "><p id="a3e6b7806979047b0bd400753cfa4562f"><a name="a3e6b7806979047b0bd400753cfa4562f"></a><a name="a3e6b7806979047b0bd400753cfa4562f"></a>Number</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="p1372262042216"><a name="p1372262042216"></a><a name="p1372262042216"></a>预测地点和传参location之间的直线距离，单位：米。</p>
<div class="note" id="note898013412294"><a name="note898013412294"></a><a name="note898013412294"></a><span class="notetitle"> 说明： </span><div class="notebody"><p id="a9d778d0d4b564ce6bba7fd5e0f7e0d50"><a name="a9d778d0d4b564ce6bba7fd5e0f7e0d50"></a><a name="a9d778d0d4b564ce6bba7fd5e0f7e0d50"></a>目前仅关键字搜索、周边搜索和地点搜索建议接口支持返回此字段。</p>
</div></div>
</td>
</tr>
<tr id="rbfdc1f85a22f45ecaefe1179a3cb0787"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="a075bbbdfebfd4dc2bb13e0dcdc78ecc4"><a name="a075bbbdfebfd4dc2bb13e0dcdc78ecc4"></a><a name="a075bbbdfebfd4dc2bb13e0dcdc78ecc4"></a>poi</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="a4b928c7f982c494ea74ba56eb936679b"><a name="a4b928c7f982c494ea74ba56eb936679b"></a><a name="a4b928c7f982c494ea74ba56eb936679b"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.3 "><p id="a156294c82aea429a8d02030da5006e82"><a name="a156294c82aea429a8d02030da5006e82"></a><a name="a156294c82aea429a8d02030da5006e82"></a><a href="#sd921064d432d44689bea55491a6c96b8">Poi</a></p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="ac30a2686805848db8c9525e590e475bd"><a name="ac30a2686805848db8c9525e590e475bd"></a><a name="ac30a2686805848db8c9525e590e475bd"></a>如果地点是POI，返回POI信息。</p>
</td>
</tr>
<tr id="row18559194510202"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="p1556014562014"><a name="p1556014562014"></a><a name="p1556014562014"></a>utcOffset</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="p87156817216"><a name="p87156817216"></a><a name="p87156817216"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.3 "><p id="p165841831142219"><a name="p165841831142219"></a><a name="p165841831142219"></a>Number</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="p1876352616217"><a name="p1876352616217"></a><a name="p1876352616217"></a>位置所在时区和UTC时区的差值，单位：分钟。</p>
<div class="note" id="note102312469305"><a name="note102312469305"></a><a name="note102312469305"></a><span class="notetitle"> 说明： </span><div class="notebody"><p id="p17631626162111"><a name="p17631626162111"></a><a name="p17631626162111"></a>仅地点详情接口返回。</p>
</div></div>
</td>
</tr>
<tr id="row981250102918"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="p38155082910"><a name="p38155082910"></a><a name="p38155082910"></a>prediction</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="p781350132914"><a name="p781350132914"></a><a name="p781350132914"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.3 "><p id="p148450142914"><a name="p148450142914"></a><a name="p148450142914"></a><a href="#section1925533718315">AutocompletePrediction</a></p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="p1481650122919"><a name="p1481650122919"></a><a name="p1481650122919"></a>地点搜索建议和自动补全接口，返回自动填充的描述信息。</p>
</td>
</tr>
</tbody>
</table>

## Step<a name="s6220d04bd11944c184eeb757cc11c0d9"></a>

<a name="ta056c47da62240b5a9e194f06b601af7"></a>
<table><thead align="left"><tr id="rf18f70a9332e4bdebf923631cd5a4ac9"><th class="cellrowborder" valign="top" width="18%" id="mcps1.1.5.1.1"><p id="a99fe0d7c6a8a439c8fc7387a7d0765b6"><a name="a99fe0d7c6a8a439c8fc7387a7d0765b6"></a><a name="a99fe0d7c6a8a439c8fc7387a7d0765b6"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="14.000000000000002%" id="mcps1.1.5.1.2"><p id="a80f143d86abf4669a4f7261d8c111005"><a name="a80f143d86abf4669a4f7261d8c111005"></a><a name="a80f143d86abf4669a4f7261d8c111005"></a>是否必选</p>
</th>
<th class="cellrowborder" valign="top" width="18%" id="mcps1.1.5.1.3"><p id="a4bbf4d11615e4d7eafc5bae647ff4445"><a name="a4bbf4d11615e4d7eafc5bae647ff4445"></a><a name="a4bbf4d11615e4d7eafc5bae647ff4445"></a>类型</p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.1.5.1.4"><p id="ac913e7633ddb4872ab4d00fefb4bd3df"><a name="ac913e7633ddb4872ab4d00fefb4bd3df"></a><a name="ac913e7633ddb4872ab4d00fefb4bd3df"></a>说明</p>
</th>
</tr>
</thead>
<tbody><tr id="r7999aa1ca04646eebf803d886bbecad6"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="a86f5c84a197843cf94bc43ca42b56171"><a name="a86f5c84a197843cf94bc43ca42b56171"></a><a name="a86f5c84a197843cf94bc43ca42b56171"></a>distance</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="adbf13393e1214e1bbc4e5740c7ea3352"><a name="adbf13393e1214e1bbc4e5740c7ea3352"></a><a name="adbf13393e1214e1bbc4e5740c7ea3352"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.3 "><p id="a7ebc1637d81443ec8e6171ae5806a355"><a name="a7ebc1637d81443ec8e6171ae5806a355"></a><a name="a7ebc1637d81443ec8e6171ae5806a355"></a>Number</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="a559058ebb519477dbbed4da47142e78c"><a name="a559058ebb519477dbbed4da47142e78c"></a><a name="a559058ebb519477dbbed4da47142e78c"></a>行驶距离，单位：米。</p>
</td>
</tr>
<tr id="r23d6e04ae16d4e58a17acee8cb259943"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="a715d1fb3b786487c815c3b3f95c5d707"><a name="a715d1fb3b786487c815c3b3f95c5d707"></a><a name="a715d1fb3b786487c815c3b3f95c5d707"></a>distanceText</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="ad41beae71add497e91b13b8f3c52ccf5"><a name="ad41beae71add497e91b13b8f3c52ccf5"></a><a name="ad41beae71add497e91b13b8f3c52ccf5"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.3 "><p id="a61daff2b406c44cfaece9acf8925d759"><a name="a61daff2b406c44cfaece9acf8925d759"></a><a name="a61daff2b406c44cfaece9acf8925d759"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="aaaad57d39e974c1cbb98b1adb4c4a4e6"><a name="aaaad57d39e974c1cbb98b1adb4c4a4e6"></a><a name="aaaad57d39e974c1cbb98b1adb4c4a4e6"></a>Distance的文本描述。</p>
</td>
</tr>
<tr id="r891528e29a974c3fabc514c9ee929e10"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="af419314aeb66442595ab53c5d6be16fa"><a name="af419314aeb66442595ab53c5d6be16fa"></a><a name="af419314aeb66442595ab53c5d6be16fa"></a>durationInTraffic</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="a2fd81ff61de244fda1b971e634855324"><a name="a2fd81ff61de244fda1b971e634855324"></a><a name="a2fd81ff61de244fda1b971e634855324"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.3 "><p id="ac4e7e6cdb8d543f0b9cb0961387aa848"><a name="ac4e7e6cdb8d543f0b9cb0961387aa848"></a><a name="ac4e7e6cdb8d543f0b9cb0961387aa848"></a>Number</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="abe135fe934c943588f402b34c4f5439e"><a name="abe135fe934c943588f402b34c4f5439e"></a><a name="abe135fe934c943588f402b34c4f5439e"></a>基于实时路况计算出来的行驶时长，单位：秒。</p>
</td>
</tr>
<tr id="r59a816d2cf75409a96b31c9390f41e95"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="ad9bf42ab081d4c87af94eca08d0e27c8"><a name="ad9bf42ab081d4c87af94eca08d0e27c8"></a><a name="ad9bf42ab081d4c87af94eca08d0e27c8"></a>durationText</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="aac2bff7778d84fdbbdf4d4363ffff9b5"><a name="aac2bff7778d84fdbbdf4d4363ffff9b5"></a><a name="aac2bff7778d84fdbbdf4d4363ffff9b5"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.3 "><p id="a476e2ce6c1f942498fc7770a40d0e485"><a name="a476e2ce6c1f942498fc7770a40d0e485"></a><a name="a476e2ce6c1f942498fc7770a40d0e485"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="a2e9bfe2ad1da4a3f87f366a296ac1c36"><a name="a2e9bfe2ad1da4a3f87f366a296ac1c36"></a><a name="a2e9bfe2ad1da4a3f87f366a296ac1c36"></a>Duration的文本描述。</p>
</td>
</tr>
<tr id="r10d5125420714d9d82f6f8e81906f248"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="ace3c0ba6b81c46439e6aaecb9042d9f9"><a name="ace3c0ba6b81c46439e6aaecb9042d9f9"></a><a name="ace3c0ba6b81c46439e6aaecb9042d9f9"></a>startLocation</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="a14aa3b5f071e494396cf99c94f4e70a3"><a name="a14aa3b5f071e494396cf99c94f4e70a3"></a><a name="a14aa3b5f071e494396cf99c94f4e70a3"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.3 "><p id="a9b1ca8070ea447d5a5c25a30d061f4a3"><a name="a9b1ca8070ea447d5a5c25a30d061f4a3"></a><a name="a9b1ca8070ea447d5a5c25a30d061f4a3"></a><a href="#s79a8e63ee72b4cb29e350a1fa05b52ce">Coordinate</a></p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="a92085617254a407a921ebf243aff1c27"><a name="a92085617254a407a921ebf243aff1c27"></a><a name="a92085617254a407a921ebf243aff1c27"></a>出发地的经纬度。</p>
</td>
</tr>
<tr id="r80bcf46dbe454727b1c61fa3c514142f"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="a5d3ca01721bf47038176705fad3d2e32"><a name="a5d3ca01721bf47038176705fad3d2e32"></a><a name="a5d3ca01721bf47038176705fad3d2e32"></a>startAddress</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="a057a863e39b046deb1aa95ce6d0b5ad3"><a name="a057a863e39b046deb1aa95ce6d0b5ad3"></a><a name="a057a863e39b046deb1aa95ce6d0b5ad3"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.3 "><p id="aadc0a223c072401aa6bbcd5a5e86b38c"><a name="aadc0a223c072401aa6bbcd5a5e86b38c"></a><a name="aadc0a223c072401aa6bbcd5a5e86b38c"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="ae292e4f1cf3c4488b0a580e37892f622"><a name="ae292e4f1cf3c4488b0a580e37892f622"></a><a name="ae292e4f1cf3c4488b0a580e37892f622"></a>startLocation对应的地址详情。</p>
</td>
</tr>
<tr id="r32a0c9b8172d436394146da05e611e54"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="af90bc56022824c7c879b55c7c3148095"><a name="af90bc56022824c7c879b55c7c3148095"></a><a name="af90bc56022824c7c879b55c7c3148095"></a>endLocation</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="a6fcdf7c96fcb41398b3935211311842a"><a name="a6fcdf7c96fcb41398b3935211311842a"></a><a name="a6fcdf7c96fcb41398b3935211311842a"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.3 "><p id="abdabe83eb475477cbff3c8dab1aba5b4"><a name="abdabe83eb475477cbff3c8dab1aba5b4"></a><a name="abdabe83eb475477cbff3c8dab1aba5b4"></a><a href="#s79a8e63ee72b4cb29e350a1fa05b52ce">Coordinate</a></p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="a683e4e21b37146698b5d2b474b42dad7"><a name="a683e4e21b37146698b5d2b474b42dad7"></a><a name="a683e4e21b37146698b5d2b474b42dad7"></a>目的地的经纬度。</p>
</td>
</tr>
<tr id="r3205e51a41714f28bf8e130e5c9587a6"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="a4411741f3297416d88784d28aa3f7a8e"><a name="a4411741f3297416d88784d28aa3f7a8e"></a><a name="a4411741f3297416d88784d28aa3f7a8e"></a>endAddress</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="a572e0f787e1d4ac9a1853b8c71d0d2bc"><a name="a572e0f787e1d4ac9a1853b8c71d0d2bc"></a><a name="a572e0f787e1d4ac9a1853b8c71d0d2bc"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.3 "><p id="a79ad5b3945e1472cab25c94d63777d1d"><a name="a79ad5b3945e1472cab25c94d63777d1d"></a><a name="a79ad5b3945e1472cab25c94d63777d1d"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="aa225a5f2646b4f01838d6e933b5fd95b"><a name="aa225a5f2646b4f01838d6e933b5fd95b"></a><a name="aa225a5f2646b4f01838d6e933b5fd95b"></a>endLocation对应的地址详情。</p>
</td>
</tr>
<tr id="r0732447324d44095b6a3573c25e12a87"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="a3a52209cc6d44fcb83c53a3ef19e22ec"><a name="a3a52209cc6d44fcb83c53a3ef19e22ec"></a><a name="a3a52209cc6d44fcb83c53a3ef19e22ec"></a>action</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="a0e9752f6e9644fb39386a10d1684fd77"><a name="a0e9752f6e9644fb39386a10d1684fd77"></a><a name="a0e9752f6e9644fb39386a10d1684fd77"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.3 "><p id="aac4985f6933243f89d29e6ef689abfa3"><a name="aac4985f6933243f89d29e6ef689abfa3"></a><a name="aac4985f6933243f89d29e6ef689abfa3"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="a62ca554d0b104619860ba74d13c18ab6"><a name="a62ca554d0b104619860ba74d13c18ab6"></a><a name="a62ca554d0b104619860ba74d13c18ab6"></a>当前步骤要执行的操作，取值包括：</p>
<a name="u0684d950f19f48b6bc8980e11694fc1d"></a><a name="u0684d950f19f48b6bc8980e11694fc1d"></a><ul id="u0684d950f19f48b6bc8980e11694fc1d"><li>TURN_SLIGHT_LEFT</li><li>TURN_SHARP_LEFT</li><li>UTURN_LEFT</li><li>TURN_LEFT</li><li>TURN_SLIGHT_RIGHT</li><li>TURN_SHARP_RIGHT</li><li>UTURN_RIGHT</li><li>TURN_RIGHT</li><li>STRAIGHT</li><li>RAMP_LEFT</li><li>RAMP_RIGHT</li><li>MERGE</li><li>FORK_LEFT</li><li>FORK_RIGHT</li><li>FERRY  （暂不支持）</li><li>FERRY_TRAIN  （暂不支持）</li><li>ROUNDABOUT_LEFT</li><li>ROUNDABOUT_RIGHT</li></ul>
</td>
</tr>
<tr id="rc8e04e555cac4c77b2c0d19336dd2f35"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="a7d6a22374e594cc1a13979888febf2ef"><a name="a7d6a22374e594cc1a13979888febf2ef"></a><a name="a7d6a22374e594cc1a13979888febf2ef"></a>polyline</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="a995fa72027ad479a911035f9f4d23a22"><a name="a995fa72027ad479a911035f9f4d23a22"></a><a name="a995fa72027ad479a911035f9f4d23a22"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.3 "><p id="acab276eaf56142cda182165bebe848ad"><a name="acab276eaf56142cda182165bebe848ad"></a><a name="acab276eaf56142cda182165bebe848ad"></a>Array&lt;<a href="#s79a8e63ee72b4cb29e350a1fa05b52ce">Coordinate</a>&gt;</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="a31b5b6e075c44e6f9ee3161d6a4a042f"><a name="a31b5b6e075c44e6f9ee3161d6a4a042f"></a><a name="a31b5b6e075c44e6f9ee3161d6a4a042f"></a>此路段的一系列坐标点（包含起点和终点坐标）。</p>
</td>
</tr>
<tr id="r0dffe3fee31f4c70a07a0acc4b6b1abd"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="a17d8d27f104e4feda923dcd767dbd235"><a name="a17d8d27f104e4feda923dcd767dbd235"></a><a name="a17d8d27f104e4feda923dcd767dbd235"></a>roadName</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="aa68408858c20422e8f0ce26fcb1a0640"><a name="aa68408858c20422e8f0ce26fcb1a0640"></a><a name="aa68408858c20422e8f0ce26fcb1a0640"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.3 "><p id="a7f4ba03206a246e180bf343f72aee2c5"><a name="a7f4ba03206a246e180bf343f72aee2c5"></a><a name="a7f4ba03206a246e180bf343f72aee2c5"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="aca7bfb8c623f47de8bf4ec9e20a3b29b"><a name="aca7bfb8c623f47de8bf4ec9e20a3b29b"></a><a name="aca7bfb8c623f47de8bf4ec9e20a3b29b"></a>路名。</p>
</td>
</tr>
<tr id="r4ccfc596ad7e45aabcdd91a7cdf9eb55"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="a21befa41899547098e7703239cea66e8"><a name="a21befa41899547098e7703239cea66e8"></a><a name="a21befa41899547098e7703239cea66e8"></a>orientation</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="a09f6e5f9e66e4b8b99e694da15f651c9"><a name="a09f6e5f9e66e4b8b99e694da15f651c9"></a><a name="a09f6e5f9e66e4b8b99e694da15f651c9"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.3 "><p id="a61f4650f3d004a8b9f4f5c215316e72e"><a name="a61f4650f3d004a8b9f4f5c215316e72e"></a><a name="a61f4650f3d004a8b9f4f5c215316e72e"></a>Number</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="aa5346811a44e43ad8958296a80c71312"><a name="aa5346811a44e43ad8958296a80c71312"></a><a name="aa5346811a44e43ad8958296a80c71312"></a>道路方向。取值包括：</p>
<a name="ub164c0acd8104b9cb129da28c3e7f6ac"></a><a name="ub164c0acd8104b9cb129da28c3e7f6ac"></a><ul id="ub164c0acd8104b9cb129da28c3e7f6ac"><li>0：双向</li><li>1：正向</li><li>2：反向</li></ul>
</td>
</tr>
<tr id="r3b36f47b772243039300eea77dae2b33"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="a1f6fead5454347bb96635405aeab64e2"><a name="a1f6fead5454347bb96635405aeab64e2"></a><a name="a1f6fead5454347bb96635405aeab64e2"></a>instruction</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="ab41c4f9f7e064dd4a4a9bc6f1e799525"><a name="ab41c4f9f7e064dd4a4a9bc6f1e799525"></a><a name="ab41c4f9f7e064dd4a4a9bc6f1e799525"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.3 "><p id="af33546afea2841d8ba4b01451ee994d4"><a name="af33546afea2841d8ba4b01451ee994d4"></a><a name="af33546afea2841d8ba4b01451ee994d4"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="afbe578cd019745f9a2da94e2be7466c7"><a name="afbe578cd019745f9a2da94e2be7466c7"></a><a name="afbe578cd019745f9a2da94e2be7466c7"></a>文字指引。</p>
</td>
</tr>
</tbody>
</table>

## TimeOfWeek<a name="s8991b20f989c463097423b028a83fe10"></a>

<a name="tde2e44c6755746e38ea7218f435242a8"></a>
<table><thead align="left"><tr id="r62ae882813774429a46d7c72810e26d1"><th class="cellrowborder" valign="top" width="18%" id="mcps1.1.5.1.1"><p id="a1e034372314b4d54a063ee1bdf923258"><a name="a1e034372314b4d54a063ee1bdf923258"></a><a name="a1e034372314b4d54a063ee1bdf923258"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="14.000000000000002%" id="mcps1.1.5.1.2"><p id="ad7bc0536240347af8cb264c0b4ea102a"><a name="ad7bc0536240347af8cb264c0b4ea102a"></a><a name="ad7bc0536240347af8cb264c0b4ea102a"></a>是否必选</p>
</th>
<th class="cellrowborder" valign="top" width="18%" id="mcps1.1.5.1.3"><p id="a256ff65a5d014f04b1d292c1f123629a"><a name="a256ff65a5d014f04b1d292c1f123629a"></a><a name="a256ff65a5d014f04b1d292c1f123629a"></a>类型</p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.1.5.1.4"><p id="a6c379f7792a241b9830eb74d917914e7"><a name="a6c379f7792a241b9830eb74d917914e7"></a><a name="a6c379f7792a241b9830eb74d917914e7"></a>说明</p>
</th>
</tr>
</thead>
<tbody><tr id="r06803706a08f4274b862ff3d179595a1"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="a7b28b29194f24dffad6558e937c48bf4"><a name="a7b28b29194f24dffad6558e937c48bf4"></a><a name="a7b28b29194f24dffad6558e937c48bf4"></a>week</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="a6b81339100294163baedb1d05f9b3a51"><a name="a6b81339100294163baedb1d05f9b3a51"></a><a name="a6b81339100294163baedb1d05f9b3a51"></a>是</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.3 "><p id="abc2340a634b545f3a2aec66f46cdcdb7"><a name="abc2340a634b545f3a2aec66f46cdcdb7"></a><a name="abc2340a634b545f3a2aec66f46cdcdb7"></a>Number</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><a name="udf94b7c303f24c68a213bc67be71f3a6"></a><a name="udf94b7c303f24c68a213bc67be71f3a6"></a><ul id="udf94b7c303f24c68a213bc67be71f3a6"><li>0：星期日</li><li>1：星期一</li><li>2：星期二</li><li>3：星期三</li><li>4：星期四</li><li>5：星期五</li><li>6：星期六</li></ul>
</td>
</tr>
<tr id="r06899121c143422f9ff70d54e5ff7d80"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="acfbd23fe06b54e79a898556f46545710"><a name="acfbd23fe06b54e79a898556f46545710"></a><a name="acfbd23fe06b54e79a898556f46545710"></a>time</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="aabb14c241809401095d2ac9ff802d051"><a name="aabb14c241809401095d2ac9ff802d051"></a><a name="aabb14c241809401095d2ac9ff802d051"></a>是</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.3 "><p id="a375ddd2e851045b88ad685a2a3f1c4d0"><a name="a375ddd2e851045b88ad685a2a3f1c4d0"></a><a name="a375ddd2e851045b88ad685a2a3f1c4d0"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="ac00e5e460eda48849b428ad4d8255b2e"><a name="ac00e5e460eda48849b428ad4d8255b2e"></a><a name="ac00e5e460eda48849b428ad4d8255b2e"></a>24小时制时间，hhmm格式。</p>
</td>
</tr>
</tbody>
</table>

## Word<a name="section716102814347"></a>

<a name="table01615281347"></a>
<table><thead align="left"><tr id="row516132819343"><th class="cellrowborder" valign="top" width="18%" id="mcps1.1.5.1.1"><p id="p31616281345"><a name="p31616281345"></a><a name="p31616281345"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="14.000000000000002%" id="mcps1.1.5.1.2"><p id="p14162152803417"><a name="p14162152803417"></a><a name="p14162152803417"></a>是否必选</p>
</th>
<th class="cellrowborder" valign="top" width="18%" id="mcps1.1.5.1.3"><p id="p16162102814345"><a name="p16162102814345"></a><a name="p16162102814345"></a>类型</p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.1.5.1.4"><p id="p2016222819349"><a name="p2016222819349"></a><a name="p2016222819349"></a>说明</p>
</th>
</tr>
</thead>
<tbody><tr id="row10162162833417"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="p1532312494342"><a name="p1532312494342"></a><a name="p1532312494342"></a>offset</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="p116212833418"><a name="p116212833418"></a><a name="p116212833418"></a>是</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.3 "><p id="p2061013013358"><a name="p2061013013358"></a><a name="p2061013013358"></a>Number</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="p237718619357"><a name="p237718619357"></a><a name="p237718619357"></a>单词在description里的偏移位。</p>
</td>
</tr>
<tr id="row9162828193419"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="p232318498341"><a name="p232318498341"></a><a name="p232318498341"></a>value</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="p1616272811342"><a name="p1616272811342"></a><a name="p1616272811342"></a>是</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.3 "><p id="p1234635531913"><a name="p1234635531913"></a><a name="p1234635531913"></a>Number</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="p10377265357"><a name="p10377265357"></a><a name="p10377265357"></a>单词。</p>
</td>
</tr>
</tbody>
</table>

