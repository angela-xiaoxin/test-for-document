# UI Controls and Gestures<a name="EN-US_TOPIC_0000001145523575"></a>

-   [Zoom Control](#section0205198489)
-   [Compass](#section58813314489)
-   [My-Location Icon](#section15524453134819)
-   [Map Gestures](#section166327340494)

You can call the  [HuaweiMap.getUiSettings](en-us_topic_0000001098683684.md#section86721421145920)**\(\)**  method to obtain a  [UiSettings](en-us_topic_0000001098843536.md)  object that controls the visibility of UI controls. UI controls include the zoom controls, compass, my-location icon, and map gestures.

## Zoom Control<a name="section0205198489"></a>

The HMS Core Map SDK provides built-in zoom controls, which are enabled by default.

The sample code is as follows:

```
Java
// Set whether to enable the zoom controls.
hMap.getUiSettings().setZoomControlsEnabled(false);
```

```
Kotlin
// Set whether to enable the zoom controls.
hMap.uiSettings.isZoomControlsEnabled = false
```

## Compass<a name="section58813314489"></a>

The HMS Core Map SDK provides the compass function. By default, a compass is displayed in the upper right corner of the map. If the compass is enabled and the map is not oriented to the due north, a compass icon will be displayed in the upper right corner of the map. A user can tap the compass icon to rotate the map to be oriented to the due north. If the compass is enabled and the map is oriented to the due north, the compass icon will be hidden. If the compass is disabled, the compass icon will never be displayed.

The sample code is as follows:

```
Java
// Set whether to enable the compass.
hMap.getUiSettings().setCompassEnabled(false);
```

```
Kotlin
// Set whether to enable the compass.
hMap.uiSettings.isCompassEnabled = false
```

## My-Location Icon<a name="section15524453134819"></a>

Before enabling the my-location icon, ensure that your app has the  **android.permission.ACCESS\_FINE\_LOCATION**  and  **android.permission.ACCESS\_COARSE\_LOCATION**  permissions and the my-location layer has been enabled. The my-location icon is displayed on a map only after being enabled. 

The sample code is as follows:

```
Java
// Enable the my-location layer.
hMap.setMyLocationEnabled(true);
// Enable the function of displaying the my-location icon.
hMap.getUiSettings().setMyLocationButtonEnabled(true);
```

```
Kotlin
// Enable the my-location layer.
hMap.isMyLocationEnabled = true
// Enable the function of displaying the my-location icon.
hMap.uiSettings.isMyLocationButtonEnabled = true
```

## Map Gestures<a name="section166327340494"></a>

You can use a  [UiSettings](en-us_topic_0000001098843536.md)  object to enable or disable relevant map gestures.

-   Zoom gestures:

    1.  A user can double-tap the map to increase the zoom level by 1 \(zoom-in\), or tap the map with two fingers to decrease the zoom level by 1 \(zoom-out\).
    2.  A user can stretch or pinch the map with two fingers to increase or decrease the zoom level.
    3.  A user can double-tap the map, long press the map upon the second tap, and slide up to zoom in on the map or down to zoom out on the map. 

    The sample code is as follows:

    ```
    Java
    // Set whether to enable the zoom gestures.
    hMap.getUiSettings().setZoomGesturesEnabled(true);
    ```

    ```
    Kotlin
    // Set whether to enable the zoom gestures.
    hMap.uiSettings.isZoomGesturesEnabled = true
    ```


-   Scroll gestures: A user can drag the map to move it.

    The sample code is as follows:

    ```
    Java
    // Set whether to enable the scroll gestures.
    hMap.getUiSettings().setScrollGesturesEnabled(true);
    ```

    ```
    Kotlin
    // Set whether to enable the scroll gestures.
    hMap.uiSettings.isScrollGesturesEnabled = true
    ```


-   Tilt gestures: A user can move two fingers up or down on a map to change the tilt angle.

    The sample code is as follows:

    ```
    Java
    // Set whether to enable the tilt gestures.
    hMap.getUiSettings().setTiltGesturesEnabled(true);
    ```

    ```
    Kotlin
    // Set whether to enable the tilt gestures.
    hMap.uiSettings.isTiltGesturesEnabled = true
    ```


-   Rotate gestures: A user can rotate a map with two fingers.

    The sample code is as follows:

    ```
    Java
    // Set whether to enable the rotate gestures.
    hMap.getUiSettings().setRotateGesturesEnabled(true);
    ```

    ```
    Kotlin
    // Set whether to enable the rotate gestures.
    hMap.uiSettings.isRotateGesturesEnabled = true
    ```


