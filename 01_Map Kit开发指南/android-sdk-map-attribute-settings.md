# 设置地图属性<a name="ZH-CN_TOPIC_0000001099661068"></a>

-   [XML方式设置](#section10810213187)
-   [代码方式设置](#section55412018141915)

您可以通过XML来配置地图的初始属性，也可以在代码中设置地图的初始属性并在之后动态更新其属性。

## XML方式设置<a name="section10810213187"></a>

华为地图SDK为[SupportMapFragment](zh-cn_topic_0000001145541123.md)和[MapView](zh-cn_topic_0000001099181264.md)定义了一组自定义XML属性，您可以直接在布局文件中使用这些属性来配置地图的初始属性。

在使用这些属性之前，请确保您已经申明了下面的命名空间：

```
xmlns:map="http://schemas.android.com/apk/res-auto"
```

接下来，您就可以使用以下属性来配置地图的初始属性了：

-   mapType：设置地图类型，有效值包括none和normal。
-   cameraTargetLat，cameraTargetLng：设置地图中心位置的经纬度。
-   cameraZoom：设置屏幕中心附近的缩放级别。
-   cameraBearing：设置地图的旋转角度，以正北方向为0度，顺时针旋转。
-   cameraTilt：设置相机的倾斜角度，即相机角度与垂直于地球表面直线的夹角。
-   uiZoomControls：设置缩放功能是否可用，默认可用。
-   uiCompass：设置指南针是否可用，默认可用。
-   uiZoomGestures，uiScrollGestures，uiRotateGestures，uiTiltGestures：设置缩放手势、滚动手势、旋转手势、倾斜手势是否可用，默认均可用。
-   zOrderOnTop：设置地图视图的表面是否放置在地图窗口的顶部，默认放置在地图窗口的顶部。
-   useViewLifecycle：仅对[SupportMapFragment](zh-cn_topic_0000001145541123.md)有效，设置是否将地图的生命周期绑定到[SupportMapFragment](zh-cn_topic_0000001145541123.md)的视图上或[SupportMapFragment](zh-cn_topic_0000001145541123.md)本身。默认将地图的生命周期与[SupportMapFragment](zh-cn_topic_0000001145541123.md)绑定在一起。
-   liteMode：设置地图是否为精简模式。默认为否。
-   cameraMinZoomPreference，cameraMaxZoomPreference：设置偏好最小/最大缩放级别。
-   latLngBoundsSouthWestLatitude，latLngBoundsSouthWestLongitude，latLngBoundsNorthEastLatitude，latLngBoundsNorthEastLongitude：设置一个LatLngBounds来约束相机目标，使用户移动相机时，相机目标不会移出此边界范围。需要注意的是，latLngBoundsNorthEastLatitude不能小于latLngBoundsSouthWestLatitude。

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

## 代码方式设置<a name="section55412018141915"></a>

您也可以通过代码方式设置地图的初始属性，并在需要更新相机状态时重新设置这些属性。所以在XML中设置的属性都可以在代码中设置。

示例代码如下：

```
Java
// 声明SupportMapFragment
SupportMapFragment mSupportMapFragment;
// 初始化相机属性
CameraPosition cameraPosition =
    CameraPosition.builder().target(new LatLng(48.893478, 2.334595)).zoom(10).bearing(45).tilt(20).build();
// 构造相机目标区域
LatLng southwest = new LatLng(47.893478, 3.334595);
LatLng northeast = new LatLng(49.893478, 1.334595);
LatLngBounds latLngBounds = new LatLngBounds(southwest, northeast);

HuaweiMapOptions options = new HuaweiMapOptions();

options
        // 设置地图类型，有效值包括none和normal
        .mapType(HuaweiMap.MAP_TYPE_NORMAL)
        // 设置相机属性
        .camera(cameraPosition)
        // 设置缩放功能是否可用，默认可用
        .zoomControlsEnabled(false)
        // 设置指南针是否可用，默认可用
        .compassEnabled(true)
        // 设置缩放手势是否可用，默认可用
        .zoomGesturesEnabled(true)
        // 设置滚动手势是否可用，默认可用
        .scrollGesturesEnabled(true)
        // 设置旋转手势是否可用，默认可用
        .rotateGesturesEnabled(false)
        // 设置倾斜手势是否可用，默认可用
        .tiltGesturesEnabled(true)
        // 设置地图视图的表面是否放置在地图窗口的顶部，默认放置在地图窗口的顶部
        .zOrderOnTop(true)
        // 设置是否将地图的生命周期绑定到SupportMapFragment的视图上或SupportMapFragment本身，默认为true
        .useViewLifecycleInFragment(true)
        // 设置地图是否为精简模式。默认为否
        .liteMode(false)
        // 设置偏好最小缩放级别
        .minZoomPreference(3)
        // 设置偏好最大缩放级别
        .maxZoomPreference(13)
        // 设置区域约束相机目标，使用户移动相机时，相机目标不会移出此边界范围
        .latLngBoundsForCameraTarget(latLngBounds);
        
mSupportMapFragment = SupportMapFragment.newInstance(options);
```

```
Kotlin
// 声明SupportMapFragment
val mSupportMapFragment: SupportMapFragment
// 初始化相机属性
val cameraPosition = CameraPosition.builder().target(LatLng(48.893478, 2.334595)).zoom(10f).bearing(45f).tilt(20f).build()
 
// 构造相机目标区域
val southwest = LatLng(47.893478, 3.334595)
val northeast = LatLng(49.893478, 1.334595)
val latLngBounds = LatLngBounds(southwest, northeast)
 
val options = HuaweiMapOptions()
 
options
        // 设置地图类型，有效值包括none和normal
        .mapType(HuaweiMap.MAP_TYPE_NORMAL)
        // 设置相机属性
        .camera(cameraPosition)
        // 设置缩放功能是否可用，默认可用
        .zoomControlsEnabled(false)
        // 设置指南针是否可用，默认可用
        .compassEnabled(true)
        // 设置缩放手势是否可用，默认可用
        .zoomGesturesEnabled(true)
        // 设置滚动手势是否可用，默认可用
        .scrollGesturesEnabled(true)
        // 设置旋转手势是否可用，默认可用
        .rotateGesturesEnabled(false)
        // 设置倾斜手势是否可用，默认可用
        .tiltGesturesEnabled(true)
        // 设置地图视图的表面是否放置在地图窗口的顶部，默认放置在地图窗口的顶部
        .zOrderOnTop(true)
        // 设置是否将地图的生命周期绑定到SupportMapFragment的视图上或SupportMapFragment本身，默认为true
        .useViewLifecycleInFragment(true)
        // 设置地图是否为精简模式。默认为否
        .liteMode(false)
        // 设置偏好最小缩放级别
        .minZoomPreference(3f)
        // 设置偏好最大缩放级别
        .maxZoomPreference(13f)
        // 设置区域约束相机目标，使用户移动相机时，相机目标不会移出此边界范围
        .latLngBoundsForCameraTarget(latLngBounds)
        
mSupportMapFragment = SupportMapFragment.newInstance(options)
```

>![](public_sys-resources/icon-note.gif) **说明：** 
>[SupportMapFragment](zh-cn_topic_0000001145541123.md)创建的时候，需要将其与Fragment的生命周期进行关联，即创建的时候需要使[HuaweiMapOptions.useViewLifecycleInFragment](zh-cn_topic_0000001099661076.md#section14526745191913)\(boolean isUseViewLifecycleInFragment\)方法参数为true。

