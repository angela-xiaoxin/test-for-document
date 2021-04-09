# Map Attribute<a name="EN-US_TOPIC_0000001098683760"></a>

You can modify the attributes of a map, such as the map center, zoom level, and map heading. The following sample code is to modify the map center:

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

The following table describes map attributes that can be customized. For details, please refer to  [HWMap](en-us_topic_0000001145523545.md). 

<a name="table59581866"></a>
<table><thead align="left"><tr id="row65358770"><th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.1"><p id="p59569016"><a name="p59569016"></a><a name="p59569016"></a><strong id="b4818011573"><a name="b4818011573"></a><a name="b4818011573"></a>Attribute</strong></p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.2"><p id="p60360962"><a name="p60360962"></a><a name="p60360962"></a><strong id="b181061804575"><a name="b181061804575"></a><a name="b181061804575"></a>Description</strong></p>
</th>
</tr>
</thead>
<tbody><tr id="row6377748"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p46835584"><a name="p46835584"></a><a name="p46835584"></a>setCenter(latlng)</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p35585956"><a name="p35585956"></a><a name="p35585956"></a>Sets the coordinates of the map center point.</p>
</td>
</tr>
<tr id="row51838155"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p38141047"><a name="p38141047"></a><a name="p38141047"></a>setHeading(heading)</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p2417136"><a name="p2417136"></a><a name="p2417136"></a>Sets the map heading, that is, the angle between the map and the north direction.</p>
</td>
</tr>
<tr id="row34707125"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p59813744"><a name="p59813744"></a><a name="p59813744"></a>setOpacity(opacity)</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p13075071"><a name="p13075071"></a><a name="p13075071"></a>Sets map transparency.</p>
</td>
</tr>
<tr id="row50566778"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p2268323"><a name="p2268323"></a><a name="p2268323"></a>setTitle(title)</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p49516436"><a name="p49516436"></a><a name="p49516436"></a>Sets the prompt information for the container where the map is located.</p>
</td>
</tr>
<tr id="row42994743"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p60022184"><a name="p60022184"></a><a name="p60022184"></a>setZoom(zoom)</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p29958774"><a name="p29958774"></a><a name="p29958774"></a>Sets the zoom level of a map.</p>
</td>
</tr>
<tr id="row1193515"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p29565903"><a name="p29565903"></a><a name="p29565903"></a>zoomOut()</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p46027906"><a name="p46027906"></a><a name="p46027906"></a>Zooms out on the map by one level.</p>
</td>
</tr>
<tr id="row11597978"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p67021034"><a name="p67021034"></a><a name="p67021034"></a>zoomIn()</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p59994654"><a name="p59994654"></a><a name="p59994654"></a>Zooms in on the map by one level.</p>
</td>
</tr>
</tbody>
</table>

