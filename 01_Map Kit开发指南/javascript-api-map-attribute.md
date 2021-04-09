# 地图属性<a name="ZH-CN_TOPIC_0000001099661074"></a>

地图支持属性自定义修改，如地图的中心点、缩放系数以及地图朝向等。以下代码示例为修改地图中心点：

```
<tr>
    <td>Latitude:</td>
    <td><input id="latInput" type="text" value="48.95"/></td>
</tr>
<tr>
    <td>Longitude:</td>
    <td><input id="lngInput" type="text" value="2.35"/></td>
</tr>

var lat = Number(document.getElementById("latInput").value);
var lng = Number(document.getElementById("lngInput").value);
map.setCenter({lat: lat, lng: lng});
```

地图的以下属性支持自定义，具体请参见[HWMap](zh-cn_topic_0000001145860979.md)。

<a name="table59581866"></a>
<table><thead align="left"><tr id="row65358770"><th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.1"><p id="p59569016"><a name="p59569016"></a><a name="p59569016"></a><strong id="b4818011573"><a name="b4818011573"></a><a name="b4818011573"></a>属性</strong></p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.2"><p id="p60360962"><a name="p60360962"></a><a name="p60360962"></a><strong id="b181061804575"><a name="b181061804575"></a><a name="b181061804575"></a>含义</strong></p>
</th>
</tr>
</thead>
<tbody><tr id="row6377748"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p46835584"><a name="p46835584"></a><a name="p46835584"></a>setCenter(latlng)</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p35585956"><a name="p35585956"></a><a name="p35585956"></a>设置地图中心点坐标。</p>
</td>
</tr>
<tr id="row51838155"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p38141047"><a name="p38141047"></a><a name="p38141047"></a>setHeading(heading)</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p2417136"><a name="p2417136"></a><a name="p2417136"></a>设置地图朝向，即地图与正北方向的夹角。</p>
</td>
</tr>
<tr id="row34707125"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p59813744"><a name="p59813744"></a><a name="p59813744"></a>setOpacity(opacity)</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p13075071"><a name="p13075071"></a><a name="p13075071"></a>设置地图透明度。</p>
</td>
</tr>
<tr id="row50566778"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p2268323"><a name="p2268323"></a><a name="p2268323"></a>setTitle(title)</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p49516436"><a name="p49516436"></a><a name="p49516436"></a>设置地图所在容器的提示信息。</p>
</td>
</tr>
<tr id="row42994743"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p60022184"><a name="p60022184"></a><a name="p60022184"></a>setZoom(zoom)</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p29958774"><a name="p29958774"></a><a name="p29958774"></a>设置地图缩放级别。</p>
</td>
</tr>
<tr id="row1193515"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p29565903"><a name="p29565903"></a><a name="p29565903"></a>zoomOut()</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p46027906"><a name="p46027906"></a><a name="p46027906"></a>地图缩小一个级别。</p>
</td>
</tr>
<tr id="row11597978"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p67021034"><a name="p67021034"></a><a name="p67021034"></a>zoomIn()</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p59994654"><a name="p59994654"></a><a name="p59994654"></a>地图放大一个级别。</p>
</td>
</tr>
</tbody>
</table>

