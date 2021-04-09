# UI控件和手势<a name="ZH-CN_TOPIC_0000001145860917"></a>

-   [缩放控件](#section0205198489)
-   [指南针](#section58813314489)
-   [我的位置按钮](#section15524453134819)
-   [地图手势控制](#section166327340494)

您可以通过调用[HuaweiMap.getUiSettings](zh-cn_topic_0000001145941019.md#section86721421145920)\(\)方法获取到[UiSettings](zh-cn_topic_0000001099181290.md)对象，该类支持控制UI控件的可见性。UI控件主要包括：缩放控件、指南针、“我的位置”按钮、“地图手势”。

## 缩放控件<a name="section0205198489"></a>

华为地图SDK提供了内置的缩放控件，默认情况下是开启的。

示例代码如下：

```
Java
// 缩放控件控制开关
hMap.getUiSettings().setZoomControlsEnabled(false);
```

```
Kotlin
// 缩放控件控制开关
hMap.uiSettings.isZoomControlsEnabled = false
```

## 指南针<a name="section58813314489"></a>

华为地图SDK提供了指南针功能，默认显示在地图的右上角。如果启用，当地图不是指向正北方向时，地图右上角会显示一个指南针图标，点击指南针可使地图旋转为正北方向；当地图为正北方向时，指南针图标隐藏。如果禁用，将永远不会显示指南针图标。

示例代码如下：

```
Java
// 指南针控制开关
hMap.getUiSettings().setCompassEnabled(false);
```

```
Kotlin
// 指南针控制开关
hMap.uiSettings.isCompassEnabled = false
```

## “我的位置“按钮<a name="section15524453134819"></a>

启用我的位置按钮之前，您需要确保已经开启了android.permission.ACCESS\_FINE\_LOCATION和android.permission.ACCESS\_COARSE\_LOCATION权限，以及开启了“我的位置”图层。当启用了“我的位置“按钮功能时，该按钮才会显示在地图上。

示例代码如下：

```
Java
// "我的位置"图层开关
hMap.setMyLocationEnabled(true);
// "我的位置"按钮显示开关
hMap.getUiSettings().setMyLocationButtonEnabled(true);
```

```
Kotlin
// "我的位置"图层开关 
hMap.isMyLocationEnabled = true
// "我的位置"按钮显示开关
hMap.uiSettings.isMyLocationButtonEnabled = true
```

## 地图手势控制<a name="section166327340494"></a>

您可以通过[UiSettings](zh-cn_topic_0000001099181290.md)对象来启用或禁止相关的地图手势。

-   缩放手势：

    1.  双击可将缩放级别提高1（放大），用两根手指点击可将缩放级别降低1（缩小）。
    2.  双指张合，实现放大缩小。
    3.  双击实现单指缩放，第二次点时按住，然后上划缩小，或下划放大。

    示例代码如下：

    ```
    Java
    // 缩放手势控制开关
    hMap.getUiSettings().setZoomGesturesEnabled(true);
    ```

    ```
    Kotlin
    // 缩放手势控制开关
    hMap.uiSettings.isZoomGesturesEnabled = true
    ```


-   滚动平移手势：用户可以通过用手指拖动地图来进行移动。

    示例代码如下：

    ```
    Java
    // 移动手势控制开关
    hMap.getUiSettings().setScrollGesturesEnabled(true);
    ```

    ```
    Kotlin
    // 移动手势控制开关
    hMap.uiSettings.isScrollGesturesEnabled = true
    ```


-   倾斜手势：用户可以将两个手指在地图上进行向下或向上移动来改变地图的倾斜度。

    示例代码如下：

    ```
    Java
    // 倾斜手势控制开关
    hMap.getUiSettings().setTiltGesturesEnabled(true);
    ```

    ```
    Kotlin
    // 倾斜手势控制开关
    hMap.uiSettings.isTiltGesturesEnabled = true
    ```


-   旋转手势：用户可以通过将两个手指放在地图上旋转来旋转地图。

    示例代码如下：

    ```
    Java
    // 旋转手势控制开关
    hMap.getUiSettings().setRotateGesturesEnabled(true);
    ```

    ```
    Kotlin
    // 旋转手势控制开关
    hMap.uiSettings.isRotateGesturesEnabled = true
    ```


