# 精简模式（暂不支持）<a name="ZH-CN_TOPIC_0000001145860969"></a>

-   [概览](#section15436144003417)
-   [使用](#section94301959183415)

## 概览<a name="section15436144003417"></a>

华为地图SDK的精简模式可以将某一指定缩放级别和指定位置的静态地图图像展示给用户，由于精简模式显示的是图片，部分常规地图的操作在精简模式下不支持。精简模式的应用场景有很多，例如：一个界面显示多个地图、朋友圈分享“我的位置”地图等。

下表展示了在精简模式下华为地图SDK支持的功能列表。

<a name="table22986234"></a>
<table><thead align="left"><tr id="row7378017"><th class="cellrowborder" valign="top" width="45%" id="mcps1.1.3.1.1"><p id="p11543491"><a name="p11543491"></a><a name="p11543491"></a><strong id="b1780581112399"><a name="b1780581112399"></a><a name="b1780581112399"></a>功能</strong></p>
</th>
<th class="cellrowborder" valign="top" width="55.00000000000001%" id="mcps1.1.3.1.2"><p id="p62607578"><a name="p62607578"></a><a name="p62607578"></a><strong id="b48347143391"><a name="b48347143391"></a><a name="b48347143391"></a>支持情况</strong></p>
</th>
</tr>
</thead>
<tbody><tr id="row26597293"><td class="cellrowborder" valign="top" width="45%" headers="mcps1.1.3.1.1 "><p id="p11106624102114"><a name="p11106624102114"></a><a name="p11106624102114"></a><a href="zh-cn_topic_0000001145781021.md">MapFragment</a>和<a href="zh-cn_topic_0000001099181264.md">MapView</a></p>
</td>
<td class="cellrowborder" valign="top" width="55.00000000000001%" headers="mcps1.1.3.1.2 "><p id="p108109574397"><a name="p108109574397"></a><a name="p108109574397"></a>全部支持。</p>
</td>
</tr>
<tr id="row22451943113914"><td class="cellrowborder" valign="top" width="45%" headers="mcps1.1.3.1.1 "><p id="p1832044011215"><a name="p1832044011215"></a><a name="p1832044011215"></a>我的位置</p>
</td>
<td class="cellrowborder" valign="top" width="55.00000000000001%" headers="mcps1.1.3.1.2 "><p id="p198101157153918"><a name="p198101157153918"></a><a name="p198101157153918"></a>全部支持。</p>
</td>
</tr>
<tr id="row04022517392"><td class="cellrowborder" valign="top" width="45%" headers="mcps1.1.3.1.1 "><p id="p95516356200"><a name="p95516356200"></a><a name="p95516356200"></a>交互手势</p>
</td>
<td class="cellrowborder" valign="top" width="55.00000000000001%" headers="mcps1.1.3.1.2 "><p id="p06431458152110"><a name="p06431458152110"></a><a name="p06431458152110"></a>不支持。</p>
</td>
</tr>
<tr id="row195231149183918"><td class="cellrowborder" valign="top" width="45%" headers="mcps1.1.3.1.1 "><p id="p72912782212"><a name="p72912782212"></a><a name="p72912782212"></a>地图相机</p>
</td>
<td class="cellrowborder" valign="top" width="55.00000000000001%" headers="mcps1.1.3.1.2 "><p id="p138511714112219"><a name="p138511714112219"></a><a name="p138511714112219"></a>部分支持，不支持设置tilt和bearing，不支持动画方式移动地图相机。</p>
</td>
</tr>
<tr id="row15270134610399"><td class="cellrowborder" valign="top" width="45%" headers="mcps1.1.3.1.1 "><p id="p207811291229"><a name="p207811291229"></a><a name="p207811291229"></a>地图事件</p>
</td>
<td class="cellrowborder" valign="top" width="55.00000000000001%" headers="mcps1.1.3.1.2 "><p id="p920312506222"><a name="p920312506222"></a><a name="p920312506222"></a>仅支持点击和长按事件。</p>
</td>
</tr>
<tr id="row1275384713392"><td class="cellrowborder" valign="top" width="45%" headers="mcps1.1.3.1.1 "><p id="p982319579224"><a name="p982319579224"></a><a name="p982319579224"></a>地图类型</p>
</td>
<td class="cellrowborder" valign="top" width="55.00000000000001%" headers="mcps1.1.3.1.2 "><p id="p280705202312"><a name="p280705202312"></a><a name="p280705202312"></a>仅支持标准地图类型和空地图类型。</p>
</td>
</tr>
<tr id="row1176511445396"><td class="cellrowborder" valign="top" width="45%" headers="mcps1.1.3.1.1 "><p id="p1064201311232"><a name="p1064201311232"></a><a name="p1064201311232"></a>标记（<a href="zh-cn_topic_0000001145860955.md">Marker</a>）</p>
</td>
<td class="cellrowborder" valign="top" width="55.00000000000001%" headers="mcps1.1.3.1.2 "><p id="p97820294234"><a name="p97820294234"></a><a name="p97820294234"></a>除拖拽和旋转外均支持。</p>
</td>
</tr>
<tr id="row156601041183912"><td class="cellrowborder" valign="top" width="45%" headers="mcps1.1.3.1.1 "><p id="p455193515256"><a name="p455193515256"></a><a name="p455193515256"></a>标记的信息窗</p>
</td>
<td class="cellrowborder" valign="top" width="55.00000000000001%" headers="mcps1.1.3.1.2 "><p id="p136601541163912"><a name="p136601541163912"></a><a name="p136601541163912"></a>全部支持。</p>
</td>
</tr>
<tr id="row310715322396"><td class="cellrowborder" valign="top" width="45%" headers="mcps1.1.3.1.1 "><p id="p759215012252"><a name="p759215012252"></a><a name="p759215012252"></a>覆盖物（<a href="zh-cn_topic_0000001145780995.md">GroundOverlay</a>/<a href="zh-cn_topic_0000001099341092.md">TileOverlay</a>）</p>
</td>
<td class="cellrowborder" valign="top" width="55.00000000000001%" headers="mcps1.1.3.1.2 "><p id="p17428757202511"><a name="p17428757202511"></a><a name="p17428757202511"></a>不支持。</p>
</td>
</tr>
<tr id="row19969639113918"><td class="cellrowborder" valign="top" width="45%" headers="mcps1.1.3.1.1 "><p id="p207359552617"><a name="p207359552617"></a><a name="p207359552617"></a>形状（<a href="zh-cn_topic_0000001099661042.md">Circle</a>/<a href="zh-cn_topic_0000001099501082.md">Polyline</a>/<a href="zh-cn_topic_0000001145941057.md">Polygon </a>）</p>
</td>
<td class="cellrowborder" valign="top" width="55.00000000000001%" headers="mcps1.1.3.1.2 "><p id="p1941017913266"><a name="p1941017913266"></a><a name="p1941017913266"></a>全部支持。</p>
</td>
</tr>
<tr id="row11467145344015"><td class="cellrowborder" valign="top" width="45%" headers="mcps1.1.3.1.1 "><p id="p746815324016"><a name="p746815324016"></a><a name="p746815324016"></a>自定义地图样式</p>
</td>
<td class="cellrowborder" valign="top" width="55.00000000000001%" headers="mcps1.1.3.1.2 "><p id="p146845314408"><a name="p146845314408"></a><a name="p146845314408"></a>不支持。</p>
</td>
</tr>
</tbody>
</table>

## 使用<a name="section94301959183415"></a>

您可以通过如下两种方式开启地图精简模式：

-   **在XML文件中设置**

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

-   **通过代码设置**

    示例代码如下：

    ```
    Java
    // 声明MapView对象
    private MapView mMapView; 
    
    @Override        
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_map_lite_mode);
        // 声明并初始化HuaweiMapOptions实例
        HuaweiMapOptions huaweiMapOptions = new HuaweiMapOptions();
        // 开启地图精简模式
        huaweiMapOptions.liteMode(true);
        // 初始化MapView对象
        mMapView = new MapView(this, huaweiMapOptions);
        Bundle mapViewBundle = null;
        if (savedInstanceState != null) {
            mapViewBundle = savedInstanceState.getBundle("MapViewBundleKey");
        }
        mMapView.onCreate(mapViewBundle);
        // 注册OnMapReadyCallback回调监听
        mMapView.getMapAsync(this);
        // 将mMapView添加到页面中     
       ((LinearLayout)findViewById(R.id.view_main)).addView(mMapView, 0);
    }
    ```

    ```
    Kotlin
    // 声明MapView对象
    private var mMapView: MapView? = null
    
    override fun onCreate(savedInstanceState: Bundle?) {
        super.onCreate(savedInstanceState)
        setContentView(R.layout.activity_map_lite_mode)
        // 声明并初始化HuaweiMapOptions实例
        val huaweiMapOptions = HuaweiMapOptions()
        // 开启地图精简模式
        huaweiMapOptions.liteMode(true) 
        // 初始化MapView对象
        mMapView = MapView(this, huaweiMapOptions)
        var mapViewBundle: Bundle? = null
        if (savedInstanceState != null) {
            mapViewBundle = savedInstanceState.getBundle("MapViewBundleKey")
        }
        mMapView?.onCreate(mapViewBundle)
        // 注册OnMapReadyCallback回调监听
        mMapView?.getMapAsync(this)
        // 将mMapView添加到页面中
        (findViewById<LinearLayout>(R.id.view_main)).addView(mMapView, 0)
    }
    ```


