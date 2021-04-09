# 相机控制<a name="ZH-CN_TOPIC_0000001145941021"></a>

-   [地图移动](#section1448615217619)
-   [地图偏移](#section1566791015715)
-   [缩放控制](#section7466441173)
-   [区域控制](#section29934131184)

## 地图移动<a name="section1448615217619"></a>

地图移动，可以调用map.panTo\(latLng\)方法，地图中心会移动到指定坐标点。

```
<tr>
    <td>X/Latitude:</td>
    <td><input id="xLatInput" type="text" value="48.8"/></td>
</tr>
<tr>
    <td>Y/Longitude:</td>
    <td><input id="yLngInput" type="text" value="2.3"/></td>
</tr>

var lat = Number(document.getElementById("xLatInput").value);
var lng = Number(document.getElementById("yLngInput").value);
map.panTo({lat: lat, lng: lng});
```

## 地图偏移<a name="section1566791015715"></a>

地图偏移，可以调用map.panBy\(x, y\)方法，地图中心会根据x和y值进行偏移，其中x和y单位为像素。

```
<tr>
    <td>X/Latitude:</td>
    <td><input id="xLatInput" type="text" value="100"/></td>
</tr>
<tr>
    <td>Y/Longitude:</td>
    <td><input id="yLngInput" type="text" value="100"/></td>
</tr>

var x = Number(document.getElementById("xLatInput").value);
var y = Number(document.getElementById("yLngInput").value);
map.panBy(x, y);
```

## 缩放控制<a name="section7466441173"></a>

缩放控制，可以使用map.setZoom\(zoom\)方法对地图缩放级别进行指定设置，也可以使用map.zoomIn\(\)和map.zoomOut\(\)对地图缩放级别进行修改，每次增加或缩小一个级别。

```
<tr>
     <td>Super Input:</td>
     <td><input id="superInput" type="text" value=""/></td>
</tr>

<script>
    var zoom = Number(document.getElementById("superInput").value);
    // 设置地图缩放系数
    map.setZoom(zoom);
    // 地图放大一个级别
    map.zoomIn();
    // 地图缩小一个级别
    map.zoomOut();
</script>
```

## 区域控制<a name="section29934131184"></a>

区域控制，可以使用map.fitBounds\(bounds\)设置地图显示区域的范围。

```
<tr>
    <td>SouthWestLat:</td>
    <td><input id="swLatInput" type="text" value="39.82"/></td>
</tr>
<tr>
    <td>SouthWestLng:</td>
    <td><input id="swLngInput" type="text" value="116.3"/></td>
</tr>
<tr>
    <td>NorthEastLat:</td>
    <td><input id="neLatInput" type="text" value="40.0"/></td>
</tr>
<tr>
    <td>NorthEastLng:</td>
    <td><input id="neLngInput" type="text" value="116.5"/></td>
</tr>


var swLat = Number(document.getElementById("swLatInput").value);
var swLng = Number(document.getElementById("swLngInput").value);
var neLat = Number(document.getElementById("neLatInput").value);
var neLng = Number(document.getElementById("neLngInput").value);
map.fitBounds({
    sw: {lng: swLng, lat: swLat},
    ne: {lng: neLng, lat: neLat},
});
```

