# Event Listening<a name="EN-US_TOPIC_0000001145523587"></a>

-   [Map Event Listening](#section7462182685011)
    -   [Tap Event](#section353913449253)
    -   [Long Press Event](#section5376192112619)

-   [Camera Moving Event Listening](#section15747650125016)
-   [Other Event Listening](#section1033618213514)
    -   [Marker Tap Event](#section106081014162813)
    -   [Information Window Tap Event](#section2415115316297)
    -   [My-location Icon Tap Event](#section485211519309)


This section describes how to set listeners for map tap and long press events, camera moving events, and other events such as my-location icon tap events.

## Map Event Listening<a name="section7462182685011"></a>

### Tap Event<a name="section353913449253"></a>

The sample code is as follows:

```
Java
hMap.setOnMapClickListener(new HuaweiMap.OnMapClickListener() {
    @Override
    public void onMapClick(LatLng latLng) {
        Toast.makeText(getApplicationContext(), "onMapClick:" + latLng.toString(), Toast.LENGTH_SHORT).show();
    }
});
```

```
Kotlin
hMap.setOnMapClickListener { latLng -> Toast.makeText(applicationContext, "onMapClick:$latLng", Toast.LENGTH_SHORT).show() }
```

### Long Press Event<a name="section5376192112619"></a>

The sample code is as follows:

```
Java
hMap.setOnMapLongClickListener(new HuaweiMap.OnMapLongClickListener() {
    @Override
    public void onMapLongClick(LatLng latLng) {
        Toast.makeText(getApplicationContext(), "onMapLongClick:" + latLng.toString(), Toast.LENGTH_SHORT).show();
    }
});
```

```
Kotlin
hMap.setOnMapLongClickListener { latLng -> Toast.makeText(applicationContext, "onMapLongClick:$latLng", Toast.LENGTH_SHORT).show() }
```

## Camera Moving Event Listening<a name="section15747650125016"></a>

After a listener is set for camera moving events, the application layer can listen on the camera moving status.

-   When the camera starts to move, the  [onCameraMoveStarted](en-us_topic_0000001099003520.md#section15331349172613)**\(\)**  method of  [HuaweiMap.OnCameraMoveStartedListener](en-us_topic_0000001099003520.md)  will be called.
-   When the camera moves or a user interacts with the map, the  [onCameraMove](en-us_topic_0000001145723437.md#section113245916324)**\(\)**  method of  [HuaweiMap.OnCameraMoveListener](en-us_topic_0000001145723437.md)  will be called for multiple times.
-   When the camera stops moving, the  [onCameraIdle](en-us_topic_0000001099003510.md#section495822616298)**\(\)**  method of  [HuaweiMap.OnCameraIdleListener](en-us_topic_0000001099003510.md)  will be called.

    The sample code is as follows:

    ```
    Java
    @Override
    public void onMapReady(HuaweiMap huaweiMap) {
        Log.i(TAG, "onMapReady: ");
        hMap = huaweiMap;
        hMap.setMyLocationEnabled(true);
        hMap.setOnCameraMoveStartedListener(this);
        hMap.setOnCameraIdleListener(this);
        hMap.setOnCameraMoveListener(this);
        hMap.setOnMapLoadedCallback(new HuaweiMap.OnMapLoadedCallback() {
            @Override
            public void onMapLoaded() {
                Log.i(TAG, "onMapLoaded: successful");
            }
        });
    }
    
    // Callback when the camera starts moving.
    @Override
    public void onCameraMoveStarted(int reason) {
        Log.i(TAG, "onCameraMoveStarted: successful");
    }
    
    // Callback when the camera stops moving.
    @Override
    public void onCameraIdle() {
        Log.i(TAG, "onCameraIdle: successful");
     }
    
    // Callback during camera moving.
    @Override
    public void onCameraMove() {
        Log.i(TAG, "onCameraMove: successful");
    }
    ```

    ```
    Kotlin
    override fun onMapReady(huaweiMap: HuaweiMap) {
        Log.i(TAG, "onMapReady: ")
        hMap = huaweiMap
        hMap.isMyLocationEnabled = true
        hMap.setOnCameraMoveStartedListener(this)
        hMap.setOnCameraIdleListener(this)
        hMap.setOnCameraMoveListener(this)
        hMap.setOnMapLoadedCallback { Log.i(TAG, "onMapLoaded: successful") }
    }
    
    // Callback when the camera starts moving.
    override fun onCameraMoveStarted(reason: Int) {
        Log.i(TAG, "onCameraMoveStarted: successful")
    }
    
    // Callback when the camera stops moving.
    override fun onCameraIdle() {
        Log.i(TAG, "onCameraIdle: successful")
    }
    
    // Callback during camera moving.
    override fun onCameraMove() {
        Log.i(TAG, "onCameraMove: successful")
    }
    ```


## Other Event Listening<a name="section1033618213514"></a>

### Marker Tap Event<a name="section106081014162813"></a>

The sample code is as follows:

```
Java
hMap.setOnMarkerClickListener(new HuaweiMap.OnMarkerClickListener() {
    @Override
    public boolean onMarkerClick(Marker marker) {
        Toast.makeText(getApplicationContext(), "onMarkerClick:" + marker.getTitle(), Toast.LENGTH_SHORT).show();
        return false;
    }
});
```

```
Kotlin
hMap.setOnMarkerClickListener { marker ->
    Toast.makeText(applicationContext, "onMarkerClick:${marker.title}", Toast.LENGTH_SHORT).show()
    false
}
```

### Information Window Tap Event<a name="section2415115316297"></a>

The sample code is as follows:

```
Java
hMap.setOnInfoWindowClickListener(new HuaweiMap.OnInfoWindowClickListener() {
    @Override
    public void onInfoWindowClick(Marker marker) {
        Toast.makeText(getApplicationContext(), "onInfoWindowClick:" + marker.getTitle(), Toast.LENGTH_SHORT).show();
    }
});
```

```
Kotlin
hMap.setOnInfoWindowClickListener { marker -> Toast.makeText(applicationContext, "onInfoWindowClick:${marker.title}", Toast.LENGTH_SHORT).show() }
```

### My-location Icon Tap Event<a name="section485211519309"></a>

The sample code is as follows:

```
Java
hMap.setOnMyLocationButtonClickListener(new HuaweiMap.OnMyLocationButtonClickListener() {
    @Override
    public boolean onMyLocationButtonClick() {
        Toast.makeText(getApplicationContext(), "MyLocation button clicked", Toast.LENGTH_SHORT).show();
        return false;
    }
});
```

```
Kotlin
hMap.setOnMyLocationButtonClickListener {
    Toast.makeText(applicationContext, "MyLocation button clicked", Toast.LENGTH_SHORT).show()
    false
}
```

