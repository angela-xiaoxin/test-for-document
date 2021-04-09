# Marker Clustering<a name="EN-US_TOPIC_0000001145723495"></a>

-   [Adding Markers to Cluster](#section1132145162315)

The HMS Core Map SDK allows you to cluster markers to effectively manage them on the map at different zoom levels. When a user zooms in on the map to a high level, all markers are displayed on the map. When the user zooms out, the markers are clustered on the map for orderly display.

## Adding Markers to Cluster<a name="section1132145162315"></a>

```
var map;
var markers = [];
var markerCluster;

var locations =  [
    {lat: 51.5145160, lng: -0.1270060},
    { lat : 51.5064490, lng : -0.1244260 },
    { lat : 51.5097080, lng : -0.1200450 },
    { lat : 51.5090680, lng : -0.1421420 },
    { lat : 51.4976080, lng : -0.1456320 },
    ···
    { lat : 51.5061590, lng : -0.140280 },
    { lat : 51.5047420, lng : -0.1470490 },
    { lat : 51.5126760, lng : -0.1189760 },
    { lat : 51.5108480, lng : -0.1208480 }
];

function initMap() {
    var mapOptions = {};
    mapOptions.center = {lat: 48.856613, lng: 2.352222};
    mapOptions.zoom = 3;

    map = new HWMapJsSDK.HWMap(document.getElementById('map'), mapOptions);
    generateMarkers(locations);

    // Initialize marker clustering.
    markerCluster = new HWMapJsSDK.HWMarkerCluster(map, markers);
}

// Initialize markers in batches.
function generateMarkers(locations) {
    for (let i = 0; i < locations.length; i++) {
        var opts = {
            position: locations[i]
        };

        markers.push(new HWMapJsSDK.HWMarker(opts));
    }
}
```

[Figure 1](#fig677775415239),  [Figure 2](#fig323221462419), and  [Figure 3](#fig835813719241)  show the marker clustering effect at different zoom levels. 

<a name="table82432035182312"></a>
<table><tbody><tr id="row1224423522317"><td class="row-nocellborder" style="border:none" valign="top" width="33.33333333333333%"><div class="fignone" id="fig677775415239"><a name="fig677775415239"></a><a name="fig677775415239"></a><span class="figcap"><b>Figure 1 </b>High zoom level</span></div>
<p id="p13520216123116"><a name="p13520216123116"></a><a name="p13520216123116"></a><a name="image15122171119273"></a><a name="image15122171119273"></a><span><img id="image15122171119273" src="figures/3绘制-227.png" height="376.595219" width="650.37"></span></p>
</td>
<td class="row-nocellborder" style="border:none" valign="top" width="33.33333333333333%"><div class="fignone" id="fig323221462419"><a name="fig323221462419"></a><a name="fig323221462419"></a><span class="figcap"><b>Figure 2 </b>Medium zoom level</span></div>
<p id="p9248151320322"><a name="p9248151320322"></a><a name="p9248151320322"></a><a name="image525530525"></a><a name="image525530525"></a><span><img id="image525530525" src="figures/3绘制-228.png" height="376.595219" width="650.37"></span></p>
</td>
<td class="cellrowborder" style="border:none" valign="top" width="33.33333333333333%"><div class="fignone" id="fig835813719241"><a name="fig835813719241"></a><a name="fig835813719241"></a><span class="figcap"><b>Figure 3 </b>Low zoom level</span></div>
<p id="p98515393312"><a name="p98515393312"></a><a name="p98515393312"></a><a name="image1698755051"></a><a name="image1698755051"></a><span><img id="image1698755051" src="figures/3绘制-229.png" height="376.595219" width="650.37"></span></p>
</td>
</tr>
</tbody>
</table>

