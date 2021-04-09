# Camera Control<a name="EN-US_TOPIC_0000001145923545"></a>

-   [Map Moving](#section1448615217619)
-   [Map Shift](#section1566791015715)
-   [Zoom Control](#section7466441173)
-   [Area Control](#section29934131184)

## Map Moving<a name="section1448615217619"></a>

You can call the  **map.panTo\(latLng\)**  method to move the map center to a specified coordinate point.

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

## Map Shift<a name="section1566791015715"></a>

You can call the  **map.panBy\(x, y\)**  method to shift the map center by the specified  **x**  and  **y**  values \(in pixels\). 

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

## Zoom Control<a name="section7466441173"></a>

You can use the  **map.setZoom\(zoom\)**  method to set the zoom level of a map. You can also use the  **map.zoomIn\(\)**  or  **map.zoomOut\(\)**  method to increase or decrease the zoom level by one each time.

```
<tr>
     <td>Super Input:</td>
     <td><input id="superInput" type="text" value=""/></td>
</tr>

<script>
    var zoom = Number(document.getElementById("superInput").value);
    // Set the map zoom coefficient.
    map.setZoom(zoom);
    // Zoom in on the map by one level.
    map.zoomIn();
    // Zoom out on the map by one level.
    map.zoomOut();
</script>
```

## Area Control<a name="section29934131184"></a>

You can use  **map.fitBounds\(bounds\)**  to set the map display scope.

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

