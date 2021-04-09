# Map Attribute Settings<a name="EN-US_TOPIC_0000001098683756"></a>

-   [Setting Attributes Using the Layout File](#section10810213187)
-   [Setting Attributes Using the Code File](#section55412018141915)

You can set initial map attributes using the layout file \(for example,  **activity\_main.xml**\) or the code file, and dynamically update them later.

## Setting Attributes Using the Layout File<a name="section10810213187"></a>

The HMS Core Map SDK defines a group of map attributes in the layout file for  [SupportMapFragment](en-us_topic_0000001145923513.md)  and  [MapView](en-us_topic_0000001098843522.md). You can directly use these attributes in the layout file to set initial map attributes.

Before using these attributes, ensure that you have declared the following namespace:

```
xmlns:map="http://schemas.android.com/apk/res-auto"
```

After declaring the namespace, you can add the following attributes as the initial attributes of a map:

-   **mapType**: map type. The options are  **none**  and  **normal**.
-   **cameraTargetLng**  and  **cameraTargetLat**: longitude and latitude of the map center.
-   **cameraZoom**: zoom level near the center of the screen.
-   **cameraBearing**: angle of a map rotated from the north in the clockwise direction. 
-   **cameraTilt**: angle of the camera from the nadir \(directly facing the Earth\), in degrees.
-   **uiZoomControls**: indicates whether the zoom function is enabled. The zoom function is enabled by default.
-   **uiCompass**: indicates whether the compass is enabled. The compass is enabled by default.
-   **uiZoomGestures**,  **uiScrollGestures**,  **uiRotateGestures**, and  **uiTiltGestures**: indicates whether the zoom gestures, scroll gestures, rotate gestures, and tilt gestures are enabled. By default, these gestures are enabled.
-   **zOrderOnTop**: indicates whether the map view is placed on the top of the map window. By default, the map view is placed on the top of the map window.
-   **useViewLifecycle**: indicates whether to bind the map lifecycle to  [SupportMapFragment](en-us_topic_0000001145923513.md)  or the view of  [SupportMapFragment](en-us_topic_0000001145923513.md). This parameter is only valid for  [SupportMapFragment](en-us_topic_0000001145923513.md). By default, the map lifecycle is bound to  [SupportMapFragment](en-us_topic_0000001145923513.md).
-   **liteMode**: indicates whether to enable the lite mode for the map. By default, the lite mode is disabled.
-   **cameraMinZoomPreference**  and  **cameraMaxZoomPreference**: preferred minimum and maximum zoom levels.
-   **latLngBoundsSouthWestLatitude**,  **latLngBoundsSouthWestLongitude**,  **latLngBoundsNorthEastLatitude**, and  **latLngBoundsNorthEastLongitude**: latitudes and longitudes of the bounds of a  **LatLngBounds**, which constrain the camera target so that the camera target does not move outside the bounds when a user scrolls the map camera. Note that the value of  **latLngBoundsNorthEastLatitude**  cannot be smaller than that of  **latLngBoundsSouthWestLatitude**.

```
<fragment xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:map="http://schemas.android.com/apk/res-auto"
    android:id="@+id/mapfragment_mapfragmentdemo"
    class="com.huawei.hms.maps.SupportMapFragment"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    map:cameraBearing="45"
    map:cameraMaxZoomPreference="13"
    map:cameraMinZoomPreference="3"
    map:cameraTargetLat="48.893478"
    map:cameraTargetLng="2.334595"
    map:cameraTilt="20"
    map:cameraZoom="10"
    map:latLngBoundsNorthEastLatitude="49.893478"
    map:latLngBoundsNorthEastLongitude="1.334595"
    map:latLngBoundsSouthWestLatitude="47.893478"
    map:latLngBoundsSouthWestLongitude="3.334595"
    map:liteMode="false"
    map:mapType="normal"
    map:uiCompass="true"
    map:uiRotateGestures="false"
    map:uiScrollGestures="true"
    map:uiTiltGestures="true"
    map:uiZoomControls="false"
    map:uiZoomGestures="true"
    map:useViewLifecycle="true"
    map:zOrderOnTop="true" />
```

## Setting Attributes Using the Code File<a name="section55412018141915"></a>

You can also set initial attributes for a map in the code file and update these attributes when the camera status needs to be updated. All map attributes in the layout file can be set in the code file.

The sample code is as follows:

```
Java
// Declare a SupportMapFragment object.
SupportMapFragment mSupportMapFragment;
// Set initial camera attributes.
CameraPosition cameraPosition =
    CameraPosition.builder().target(new LatLng(48.893478, 2.334595)).zoom(10).bearing(45).tilt(20).build();
// Construct the target area of the camera.
LatLng southwest = new LatLng(47.893478, 3.334595);
LatLng northeast = new LatLng(49.893478, 1.334595);
LatLngBounds latLngBounds = new LatLngBounds(southwest, northeast);

HuaweiMapOptions options = new HuaweiMapOptions();

options
        // Set the map type. The options are NONE and NORMAL.
        .mapType(HuaweiMap.MAP_TYPE_NORMAL)
        // Set camera attributes.
        .camera(cameraPosition)
        // Set whether the zoom function is enabled. The zoom function is enabled by default.
        .zoomControlsEnabled(false)
        // Set whether the compass is enabled. The compass is enabled by default.
        .compassEnabled(true)
        // Set whether zoom gestures are enabled. The zoom gestures are enabled by default.
        .zoomGesturesEnabled(true)
        // Set whether scroll gestures are enabled. The scroll gestures are enabled by default.
        .scrollGesturesEnabled(true)
        // Set whether rotate gestures are enabled. The rotate gestures are enabled by default.
        .rotateGesturesEnabled(false)
        // Set whether tilt gestures are enabled. The tilt gestures are enabled by default.
        .tiltGesturesEnabled(true)
        // Set whether the map view is placed on the top of the map window. By default, the map view is placed on the top of the map window.
        .zOrderOnTop(true)
        // Set whether to bind the map lifecycle to SupportMapFragment or the view of SupportMapFragment. The default value is true.
        .useViewLifecycleInFragment(true)
        // Set whether the lite mode is enabled for the map. The lite mode is disabled by default.
        .liteMode(false)
        // Set the preferred minimum zoom level.
        .minZoomPreference(3)
        // Set the preferred maximum zoom level.
        .maxZoomPreference(13)
        // Set an area to constrain the camera target so that the camera target does not move outside the bounds when a user scrolls the map camera.
        .latLngBoundsForCameraTarget(latLngBounds);
        
mSupportMapFragment = SupportMapFragment.newInstance(options);
```

```
Kotlin
// Declare a SupportMapFragment object.
val mSupportMapFragment: SupportMapFragment
// Set initial camera attributes.
val cameraPosition = CameraPosition.builder().target(LatLng(48.893478, 2.334595)).zoom(10f).bearing(45f).tilt(20f).build()
 
// Construct the target area of the camera.
val southwest = LatLng(47.893478, 3.334595)
val northeast = LatLng(49.893478, 1.334595)
val latLngBounds = LatLngBounds(southwest, northeast)
 
val options = HuaweiMapOptions()
 
options
        // Set the map type. The options are NONE and NORMAL.
        .mapType(HuaweiMap.MAP_TYPE_NORMAL)
        // Set camera attributes.
        .camera(cameraPosition)
        // Set whether the zoom function is enabled. The zoom function is enabled by default.
        .zoomControlsEnabled(false)
        // Set whether the compass is enabled. The compass is enabled by default.
        .compassEnabled(true)
        // Set whether zoom gestures are enabled. The zoom gestures are enabled by default.
        .zoomGesturesEnabled(true)
        // Set whether scroll gestures are enabled. The scroll gestures are enabled by default.
        .scrollGesturesEnabled(true)
        // Set whether rotate gestures are enabled. The rotate gestures are enabled by default.
        .rotateGesturesEnabled(false)
        // Set whether tilt gestures are enabled. The tilt gestures are enabled by default.
        .tiltGesturesEnabled(true)
        // Set whether the map view is placed on the top of the map window. By default, the map view is placed on the top of the map window.
        .zOrderOnTop(true)
        // Set whether to bind the map lifecycle to SupportMapFragment or the view of SupportMapFragment. The default value is true.
        .useViewLifecycleInFragment(true)
        // Set whether the lite mode is enabled for the map. The lite mode is disabled by default.
        .liteMode(false)
        // Set the preferred minimum zoom level.
        .minZoomPreference(3f)
        // Set the preferred maximum zoom level.
        .maxZoomPreference(13f)
        // Set an area to constrain the camera target so that the camera target does not move outside the bounds when a user scrolls the map camera.
        .latLngBoundsForCameraTarget(latLngBounds)
        
mSupportMapFragment = SupportMapFragment.newInstance(options)
```

>![](public_sys-resources/icon-note.gif) **NOTE:** 
>When creating  [SupportMapFragment](en-us_topic_0000001145923513.md), you need to associate it with the lifecycle of  **Fragment**, that is, the parameter value of the  [HuaweiMapOptions.useViewLifecycleInFragment](en-us_topic_0000001099003526.md#section14526745191913)**\(boolean isUseViewLifecycleInFragment\)**  method must be  **true**.

