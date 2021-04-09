# HWDistanceCalculator<a name="ZH-CN_TOPIC_0000001099341122"></a>

-   [概览](#section194833517270)
-   [构造方法](#section59204122287)
-   [公共方法](#section12524111762818)

## 概览<a name="section194833517270"></a>

根据经纬度计算两点之间的直线距离。

## 构造方法<a name="section59204122287"></a>

<a name="table392918596288"></a>
<table><thead align="left"><tr id="row1292995915281"><th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.1"><p id="p1392925918289"><a name="p1392925918289"></a><a name="p1392925918289"></a>构造方法</p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.2"><p id="p39295591284"><a name="p39295591284"></a><a name="p39295591284"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="row13929659162819"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p1992945913282"><a name="p1992945913282"></a><a name="p1992945913282"></a>HWMapJsSDK.HWDistanceCalculator()</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p18929359102815"><a name="p18929359102815"></a><a name="p18929359102815"></a>-</p>
</td>
</tr>
</tbody>
</table>

## 公共方法<a name="section12524111762818"></a>

<a name="t127419a48d134b34b18afb99ab071e76"></a>
<table><thead align="left"><tr id="r500feb32cc984b97a9d96cbd6ca562be"><th class="cellrowborder" valign="top" width="26.43%" id="mcps1.1.5.1.1"><p id="a5eb811748e2340f5b64e2dd8580bb92e"><a name="a5eb811748e2340f5b64e2dd8580bb92e"></a><a name="a5eb811748e2340f5b64e2dd8580bb92e"></a><strong id="ad1e2401e28fb4089b0f49e57dd306342"><a name="ad1e2401e28fb4089b0f49e57dd306342"></a><a name="ad1e2401e28fb4089b0f49e57dd306342"></a>方法</strong></p>
</th>
<th class="cellrowborder" valign="top" width="21.57%" id="mcps1.1.5.1.2"><p id="a85e9b8b51c524eb6811492a8034e00b4"><a name="a85e9b8b51c524eb6811492a8034e00b4"></a><a name="a85e9b8b51c524eb6811492a8034e00b4"></a><strong id="abd5f55b3f59547e6b175e39164ebfc72"><a name="abd5f55b3f59547e6b175e39164ebfc72"></a><a name="abd5f55b3f59547e6b175e39164ebfc72"></a>描述</strong></p>
</th>
<th class="cellrowborder" valign="top" width="32.67%" id="mcps1.1.5.1.3"><p id="a6c225265d07c407e803118de8eb553ce"><a name="a6c225265d07c407e803118de8eb553ce"></a><a name="a6c225265d07c407e803118de8eb553ce"></a><strong id="aabb132627de84a6794aced37108ed22a"><a name="aabb132627de84a6794aced37108ed22a"></a><a name="aabb132627de84a6794aced37108ed22a"></a>参数类型</strong></p>
</th>
<th class="cellrowborder" valign="top" width="19.33%" id="mcps1.1.5.1.4"><p id="a0f353fe9c5604307bb1d8a10d49116c3"><a name="a0f353fe9c5604307bb1d8a10d49116c3"></a><a name="a0f353fe9c5604307bb1d8a10d49116c3"></a><strong id="ac4de4943f69542c2b36581438b4d81a4"><a name="ac4de4943f69542c2b36581438b4d81a4"></a><a name="ac4de4943f69542c2b36581438b4d81a4"></a>返回值</strong></p>
</th>
</tr>
</thead>
<tbody><tr id="rea2004a8bf6c4cb1b3b9e8c38fbf6129"><td class="cellrowborder" valign="top" width="26.43%" headers="mcps1.1.5.1.1 "><p id="p188301112123010"><a name="p188301112123010"></a><a name="p188301112123010"></a>computeDistanceBetween(fromPostion, toPosition, opt_radius)</p>
</td>
<td class="cellrowborder" valign="top" width="21.57%" headers="mcps1.1.5.1.2 "><p id="p382981263019"><a name="p382981263019"></a><a name="p382981263019"></a>计算两点之间的直线距离。</p>
</td>
<td class="cellrowborder" valign="top" width="32.67%" headers="mcps1.1.5.1.3 "><a name="ul4554133683110"></a><a name="ul4554133683110"></a><ul id="ul4554133683110"><li>fromPostion：<a href="js-params.md#s45373a8938e040ca9f46c78f4283b385">LatLng</a>，一个点的经纬度。</li><li>toPosition：<a href="js-params.md#s45373a8938e040ca9f46c78f4283b385">LatLng</a>，另一个点的经纬度。</li><li>opt_radius：Number，球体半径，可选参数，默认为6378137.0米。</li></ul>
</td>
<td class="cellrowborder" valign="top" width="19.33%" headers="mcps1.1.5.1.4 "><p id="p10826191218305"><a name="p10826191218305"></a><a name="p10826191218305"></a>两点之间的直线距离，单位：米。</p>
</td>
</tr>
</tbody>
</table>

