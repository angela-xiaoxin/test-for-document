# 侦听事件<a name="ZH-CN_TOPIC_0000001145860949"></a>

-   [地图事件侦听](#section7462182685011)
    -   [点击事件侦听](#section353913449253)
    -   [长按事件侦听](#section5376192112619)

-   [相机移动侦听](#section15747650125016)
-   [其他事件侦听](#section1033618213514)
    -   [标记点击事件侦听](#section106081014162813)
    -   [窗口点击事件侦听](#section2415115316297)
    -   [按钮点击事件侦听](#section485211519309)


本章节包含地图的点击和长按、相机移动、以及“我的位置”按钮点击等事件侦听。

## 地图事件侦听<a name="section7462182685011"></a>

### 点击事件侦听<a name="section353913449253"></a>

示例代码如下：

```
Java
hMap.setOnMapClickListener(new HuaweiMap.OnMapClickListener() {
    @Override
    public void onMapClick(LatLng latLng) {
        Toast.makeText(getApplicationContext(), "onMapClick：" + latLng.toString(), Toast.LENGTH_SHORT).show();
    }
});
```

```
Kotlin
hMap.setOnMapClickListener { latLng -> Toast.makeText(applicationContext, "onMapClick：$latLng", Toast.LENGTH_SHORT).show() }
```

### 长按事件侦听<a name="section5376192112619"></a>

示例代码如下：

```
Java
hMap.setOnMapLongClickListener(new HuaweiMap.OnMapLongClickListener() {
    @Override
    public void onMapLongClick(LatLng latLng) {
        Toast.makeText(getApplicationContext(), "onMapLongClick：" + latLng.toString(), Toast.LENGTH_SHORT).show();
    }
});
```

```
Kotlin
hMap.setOnMapLongClickListener { latLng -> Toast.makeText(applicationContext, "onMapLongClick：$latLng", Toast.LENGTH_SHORT).show() }
```

## 相机移动侦听<a name="section15747650125016"></a>

相机移动时，应用层通过设置侦听器，能够对相机移动状态进行侦听。

-   当相机开始移动时，将调用[HuaweiMap.OnCameraMoveStartedListener](zh-cn_topic_0000001099661062.md)的[onCameraMoveStarted](zh-cn_topic_0000001099661062.md#section15331349172613)\(\)方法进行回调。
-   当相机移动或用户与触摸屏交互时，会多次调用[HuaweiMap.OnCameraMoveListener](zh-cn_topic_0000001099341066.md)的[onCameraMove](zh-cn_topic_0000001099341066.md#section113245916324)\(\)方法。
-   当相机停止移动时，将调用[HuaweiMap.OnCameraIdleListener](zh-cn_topic_0000001099661034.md)的[onCameraIdle](zh-cn_topic_0000001099661034.md#section495822616298)\(\)方法。

    示例代码如下：

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
    
    // 相机开始移动时回调
    @Override
    public void onCameraMoveStarted(int reason) {
        Log.i(TAG, "onCameraMoveStarted: successful");
    }
    
    // 相机移动终止时的回调
    @Override
    public void onCameraIdle() {
        Log.i(TAG, "onCameraIdle: successful");
     }
    
    // 相机移动过程中的回调
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
    
    // 相机开始移动时回调
    override fun onCameraMoveStarted(reason: Int) {
        Log.i(TAG, "onCameraMoveStarted: successful")
    }
    
    // 相机移动终止时的回调
    override fun onCameraIdle() {
        Log.i(TAG, "onCameraIdle: successful")
    }
    
    // 相机移动过程中的回调
    override fun onCameraMove() {
        Log.i(TAG, "onCameraMove: successful")
    }
    ```


## 其他事件侦听<a name="section1033618213514"></a>

### 标记点击事件侦听<a name="section106081014162813"></a>

示例代码如下：

```
Java
hMap.setOnMarkerClickListener(new HuaweiMap.OnMarkerClickListener() {
    @Override
    public boolean onMarkerClick(Marker marker) {
        Toast.makeText(getApplicationContext(), "onMarkerClick：" + marker.getTitle(), Toast.LENGTH_SHORT).show();
        return false;
    }
});
```

```
Kotlin
hMap.setOnMarkerClickListener { marker ->
    Toast.makeText(applicationContext, "onMarkerClick：${marker.title}", Toast.LENGTH_SHORT).show()
    false
}
```

### 窗口点击事件侦听<a name="section2415115316297"></a>

示例代码如下：

```
Java
hMap.setOnInfoWindowClickListener(new HuaweiMap.OnInfoWindowClickListener() {
    @Override
    public void onInfoWindowClick(Marker marker) {
        Toast.makeText(getApplicationContext(), "onInfoWindowClick：" + marker.getTitle(), Toast.LENGTH_SHORT).show();
    }
});
```

```
Kotlin
hMap.setOnInfoWindowClickListener { marker -> Toast.makeText(applicationContext, "onInfoWindowClick：${marker.title}", Toast.LENGTH_SHORT).show() }
```

### “我的位置“按钮点击事件侦听<a name="section485211519309"></a>

示例代码如下：

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

