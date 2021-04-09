# Lite Mode \(Unavailable Now\)<a name="EN-US_TOPIC_0000001145523597"></a>

-   [Overview](#section15436144003417)
-   [Usage](#section94301959183415)

## Overview<a name="section15436144003417"></a>

In the lite mode, the HMS Core Map SDK allows your app to show the static map image of a specified location at a specified zoom level to a user. The lite mode supports only static image–based functions. It is useful when the user wants to show multiple maps on one screen, or share their location using WeChat Moments.

The following table lists the functions supported by the HMS Core Map SDK in lite mode.

<a name="table22986234"></a>
<table><thead align="left"><tr id="row7378017"><th class="cellrowborder" valign="top" width="45%" id="mcps1.1.3.1.1"><p id="p11543491"><a name="p11543491"></a><a name="p11543491"></a><strong id="b1780581112399"><a name="b1780581112399"></a><a name="b1780581112399"></a>Function</strong></p>
</th>
<th class="cellrowborder" valign="top" width="55.00000000000001%" id="mcps1.1.3.1.2"><p id="p62607578"><a name="p62607578"></a><a name="p62607578"></a><strong id="b48347143391"><a name="b48347143391"></a><a name="b48347143391"></a>Support</strong></p>
</th>
</tr>
</thead>
<tbody><tr id="row26597293"><td class="cellrowborder" valign="top" width="45%" headers="mcps1.1.3.1.1 "><p id="p11106624102114"><a name="p11106624102114"></a><a name="p11106624102114"></a><a href="en-us_topic_0000001099163506.md">MapFragment</a> and <a href="en-us_topic_0000001098843522.md">MapView</a></p>
</td>
<td class="cellrowborder" valign="top" width="55.00000000000001%" headers="mcps1.1.3.1.2 "><p id="p108109574397"><a name="p108109574397"></a><a name="p108109574397"></a>Completely supported</p>
</td>
</tr>
<tr id="row22451943113914"><td class="cellrowborder" valign="top" width="45%" headers="mcps1.1.3.1.1 "><p id="p1832044011215"><a name="p1832044011215"></a><a name="p1832044011215"></a>My location</p>
</td>
<td class="cellrowborder" valign="top" width="55.00000000000001%" headers="mcps1.1.3.1.2 "><p id="p198101157153918"><a name="p198101157153918"></a><a name="p198101157153918"></a>Completely supported</p>
</td>
</tr>
<tr id="row04022517392"><td class="cellrowborder" valign="top" width="45%" headers="mcps1.1.3.1.1 "><p id="p95516356200"><a name="p95516356200"></a><a name="p95516356200"></a>Interaction gesture</p>
</td>
<td class="cellrowborder" valign="top" width="55.00000000000001%" headers="mcps1.1.3.1.2 "><p id="p06431458152110"><a name="p06431458152110"></a><a name="p06431458152110"></a>Not supported</p>
</td>
</tr>
<tr id="row195231149183918"><td class="cellrowborder" valign="top" width="45%" headers="mcps1.1.3.1.1 "><p id="p72912782212"><a name="p72912782212"></a><a name="p72912782212"></a>Map camera</p>
</td>
<td class="cellrowborder" valign="top" width="55.00000000000001%" headers="mcps1.1.3.1.2 "><p id="p138511714112219"><a name="p138511714112219"></a><a name="p138511714112219"></a>Partially supported (Tilt and bearing cannot be set and animation is not supported.)</p>
</td>
</tr>
<tr id="row15270134610399"><td class="cellrowborder" valign="top" width="45%" headers="mcps1.1.3.1.1 "><p id="p207811291229"><a name="p207811291229"></a><a name="p207811291229"></a>Map event</p>
</td>
<td class="cellrowborder" valign="top" width="55.00000000000001%" headers="mcps1.1.3.1.2 "><p id="p920312506222"><a name="p920312506222"></a><a name="p920312506222"></a>Only tap and long press events are supported.</p>
</td>
</tr>
<tr id="row1275384713392"><td class="cellrowborder" valign="top" width="45%" headers="mcps1.1.3.1.1 "><p id="p982319579224"><a name="p982319579224"></a><a name="p982319579224"></a>Map type</p>
</td>
<td class="cellrowborder" valign="top" width="55.00000000000001%" headers="mcps1.1.3.1.2 "><p id="p280705202312"><a name="p280705202312"></a><a name="p280705202312"></a>Only standard maps and empty maps are supported.</p>
</td>
</tr>
<tr id="row1176511445396"><td class="cellrowborder" valign="top" width="45%" headers="mcps1.1.3.1.1 "><p id="p1064201311232"><a name="p1064201311232"></a><a name="p1064201311232"></a><a href="en-us_topic_0000001145523533.md">Marker</a></p>
</td>
<td class="cellrowborder" valign="top" width="55.00000000000001%" headers="mcps1.1.3.1.2 "><p id="p97820294234"><a name="p97820294234"></a><a name="p97820294234"></a>Only dragging and rotation are not supported.</p>
</td>
</tr>
<tr id="row156601041183912"><td class="cellrowborder" valign="top" width="45%" headers="mcps1.1.3.1.1 "><p id="p455193515256"><a name="p455193515256"></a><a name="p455193515256"></a>Marker information window</p>
</td>
<td class="cellrowborder" valign="top" width="55.00000000000001%" headers="mcps1.1.3.1.2 "><p id="p136601541163912"><a name="p136601541163912"></a><a name="p136601541163912"></a>Completely supported</p>
</td>
</tr>
<tr id="row310715322396"><td class="cellrowborder" valign="top" width="45%" headers="mcps1.1.3.1.1 "><p id="p759215012252"><a name="p759215012252"></a><a name="p759215012252"></a>Overlay (<a href="en-us_topic_0000001099163498.md">GroundOverlay</a>/<a href="en-us_topic_0000001145723445.md">TileOverlay</a>)</p>
</td>
<td class="cellrowborder" valign="top" width="55.00000000000001%" headers="mcps1.1.3.1.2 "><p id="p17428757202511"><a name="p17428757202511"></a><a name="p17428757202511"></a>Not supported</p>
</td>
</tr>
<tr id="row19969639113918"><td class="cellrowborder" valign="top" width="45%" headers="mcps1.1.3.1.1 "><p id="p207359552617"><a name="p207359552617"></a><a name="p207359552617"></a>Shape (<a href="en-us_topic_0000001099003514.md">Circle</a>/<a href="en-us_topic_0000001145843377.md">Polyline</a>/<a href="en-us_topic_0000001098683698.md">Polygon</a>)</p>
</td>
<td class="cellrowborder" valign="top" width="55.00000000000001%" headers="mcps1.1.3.1.2 "><p id="p1941017913266"><a name="p1941017913266"></a><a name="p1941017913266"></a>Completely supported</p>
</td>
</tr>
<tr id="row11467145344015"><td class="cellrowborder" valign="top" width="45%" headers="mcps1.1.3.1.1 "><p id="p746815324016"><a name="p746815324016"></a><a name="p746815324016"></a>Custom map style</p>
</td>
<td class="cellrowborder" valign="top" width="55.00000000000001%" headers="mcps1.1.3.1.2 "><p id="p146845314408"><a name="p146845314408"></a><a name="p146845314408"></a>Not supported</p>
</td>
</tr>
</tbody>
</table>

## Usage<a name="section94301959183415"></a>

You can enable the lite mode in either of the following ways:

-   Configure the layout file as follows:

    ```
    <com.huawei.hms.maps.MapView xmlns:android="http://schemas.android.com/apk/res/android"
       xmlns:map="http://schemas.android.com/apk/res-auto"
       android:id="@+id/mapView"
       android:layout_width="match_parent"
       android:layout_height="match_parent"
       map:mapType="normal"        
       map:liteMode="true"        
       map:uiCompass="true"
       map:uiZoomControls="true"
       map:cameraTargetLat="51"
       map:cameraTargetLng="10"
       map:cameraZoom="8.5"/>
    ```

-   Add the following code to the code file:

    The sample code is as follows:

    ```
    Java
    // Declare a MapView object.
    private MapView mMapView; 
    
    @Override        
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_map_lite_mode);
        // Declare and initialize a HuaweiMapOptions instance.
        HuaweiMapOptions huaweiMapOptions = new HuaweiMapOptions();
        // Enable the lite mode for the map.
        huaweiMapOptions.liteMode(true);
        // Initialize the MapView object. 
        mMapView = new MapView(this, huaweiMapOptions);
        Bundle mapViewBundle = null;
        if (savedInstanceState != null) {
            mapViewBundle = savedInstanceState.getBundle("MapViewBundleKey");
        }
        mMapView.onCreate(mapViewBundle);
        // Register the OnMapReadyCallback listener.
        mMapView.getMapAsync(this);
        // Add mMapView to the page.
       ((LinearLayout)findViewById(R.id.view_main)).addView(mMapView, 0);
    }
    ```

    ```
    Kotlin
    // Declare a MapView object.
    private var mMapView: MapView? = null
    
    override fun onCreate(savedInstanceState: Bundle?) {
        super.onCreate(savedInstanceState)
        setContentView(R.layout.activity_map_lite_mode)
        // Declare and initialize a HuaweiMapOptions instance.
        val huaweiMapOptions = HuaweiMapOptions()
        // Enable the lite mode for the map.
        huaweiMapOptions.liteMode(true) 
        // Initialize the MapView object. 
        mMapView = MapView(this, huaweiMapOptions)
        var mapViewBundle: Bundle? = null
        if (savedInstanceState != null) {
            mapViewBundle = savedInstanceState.getBundle("MapViewBundleKey")
        }
        mMapView?.onCreate(mapViewBundle)
        // Register the OnMapReadyCallback listener.
        mMapView?.getMapAsync(this)
        // Add mMapView to the page.
        (findViewById<LinearLayout>(R.id.view_main)).addView(mMapView, 0)
    }
    ```


