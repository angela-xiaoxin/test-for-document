# 从Google Maps迁移到HUAWEI Map Kit<a name="ZH-CN_TOPIC_0000001099501062"></a>

-   [概览](#section14565114715461)
-   [开发准备](#section831111183470)
-   [创建地图](#section8128184194818)
    -   [Google Maps SDK](#section1937014121494)
    -   [Map Kit](#section1090724194914)

-   [添加标记](#section79311456184914)
    -   [Google Maps SDK](#section5442173845020)
    -   [Map Kit](#section1367459145020)

-   [说明](#section102770202518)
-   [总结](#section64502410516)

## 概览<a name="section14565114715461"></a>

本教程将从最基本的环境配置开始，帮助您尽快将Android应用程序从Google Maps SDK for Android切换到Map Kit提供的SDK for Android。除此之外，还提供了一些基本用例，如创建地图、添加标记等。在总结部分，我们提供了自动化工具的获取链接，该工具可以帮助您完成手动切换的工作。

## 开发准备<a name="section831111183470"></a>

集成HUAWEI Map Kit能力，需要完成以下准备工作：

-   创建[AppGallery Connect](https://developer.huawei.com/consumer/cn/service/josp/agc/index.html)应用
-   创建Android Studio工程
-   生成签名证书以及签名证书指纹
-   在[AppGallery Connect](https://developer.huawei.com/consumer/cn/service/josp/agc/index.html)上配置签名证书指纹
-   集成HMS Core SDK
-   配置项目签名

具体操作，请按照[HUAWEI HMS Core集成准备](https://developer.huawei.com/consumer/cn/codelab/HMSPreparation/index.html#0)中详细说明来完成。

## 创建地图<a name="section8128184194818"></a>

本小节内容将介绍使用Google Maps和HUAWEI Map Kit创建地图的步骤。

### Google Maps SDK<a name="section1937014121494"></a>

1.  将编译依赖添加到模块的“build.gradle“文件中：

    ```
    implementation 'com.google.android.gms:play-services-maps:15.0.0'  
    ```

2.  在Activity的布局文件中添加一个fragment：

    ```
    <fragment   
        android:id="@+id/mapFragment"   
        android:name="com.google.android.gms.maps.SupportMapFragment"
        android:layout_width="match_parent"
        android:layout_height="match_parent"/>  
    ```

3.  在AndroidManifest.xml文件的application部分内添加一个Google Android API密钥：

    ```
    <meta-data 
    android:name="com.google.android.geo.API_KEY"
    android:value="YOUR_GOOGLE_KEY_GOES_HERE"/>
    ```


### Map Kit<a name="section1090724194914"></a>

1.  将编译依赖添加到模块的“build.gradle“文件中：

    ```
    implementation 'com.huawei.hms:maps:5.2.0.302'
    ```

2.  在Activity的布局文件中添加一个fragment：

    ```
    <fragment
        xmlns:android="http://schemas.android.com/apk/res/android"  
        xmlns:map="http://schemas.android.com/apk/res-auto"  
        android:id="@+id/mapfragment_mapfragmentdemo"  
        class="com.huawei.hms.maps.SupportMapFragment"  
        android:layout_width="match_parent"  
        android:layout_height="match_parent"
        map:cameraTargetLat="48"
        map:cameraTargetLng="118"/>
    ```


## 添加标记<a name="section79311456184914"></a>

本小节内容将介绍使用Google Maps和HUAWEI Map Kit添加标记的步骤。

### Google Maps SDK<a name="section5442173845020"></a>

1.  定义一个GoogleMap对象和一个MapFragment对象：

    示例代码如下：

    ```
    Java
    private GoogleMap gMap; 
    private SupportMapFragment mSupportMapFragment;
    ```

    ```
    Kotlin
    private lateinit var gMap: GoogleMap
    private var mSupportMapFragment: SupportMapFragment? = null
    ```

2.  实现OnMapReadyCallback接口，并重写onMapReady方法：

    示例代码如下：

    ```
    Java
    @Override
    public void onMapReady(GoogleMap googleMap) {  
       gMap = googleMap;  
       LatLng amsterdam = new LatLng(52.37, 4.90);  
       gMap.addMarker(new MarkerOptions().position(amsterdam).title("Amsterdam"));
       gMap.animateCamera(CameraUpdateFactory.newLatLngZoom(amsterdam, 8));
    }  
    ```

    ```
    Kotlin
    override fun onMapReady(googleMap: GoogleMap) {
        gMap = googleMap
        val amsterdam = LatLng(52.37, 4.90)
        gMap.addMarker(MarkerOptions().position(amsterdam).title("Amsterdam"))
        gMap.animateCamera(CameraUpdateFactory.newLatLngZoom(amsterdam, 8f))
    }
    ```

3.  在Activity的onCreate方法中加载MapFragment，并调用getMapAsync\(\)：

    示例代码如下：

    ```
    Java
    MapFragment mapFragment = (MapFragment)getFragmentManager().findFragmentById(R.id.mapFragment);  
    mapFragment.getMapAsync(this);
    ```

    ```
    Kotlin
    mSupportMapFragment = supportFragmentManager.findFragmentById(R.id.mapFragment) as SupportMapFragment
    mSupportMapFragment?.getMapAsync(this)
    ```


### Map Kit<a name="section1367459145020"></a>

1.  定义一个[HuaweiMap](zh-cn_topic_0000001145941019.md)对象和一个[MapFragment](zh-cn_topic_0000001145781021.md)对象：

    示例代码如下：

    ```
    Java
    private HuaweiMap hMap;
    private SupportMapFragment mSupportMapFragment;
    ```

    ```
    Kotlin
    private lateinit var hMap: HuaweiMap
    private var mSupportMapFragment: SupportMapFragment? = null
    ```

2.  实现[OnMapReadyCallback](zh-cn_topic_0000001099181298.md)接口，并重写[onMapReady](zh-cn_topic_0000001099181298.md#section74342919481)方法：

    示例代码如下：

    ```
    Java
    @Override  
    public void onMapReady(HuaweiMap map) {
        // 调用getMapAsync()方法后，我们可以在这个回调方法得到HuaweiMap对象
        hMap = map;  
        mMarker = hMap.addMarker(new MarkerOptions().position(new LatLng(31.2304, 121.4737)).icon(BitmapDescriptorFactory.fromResource(R.drawable.ic_launcher_background)));  
        hMap.moveCamera(CameraUpdateFactory.newLatLngZoom(new LatLng(31.2304, 121.4737), 10));  
    }
    ```

    ```
    Kotlin
    override fun onMapReady(map: HuaweiMap) {
        // 调用getMapAsync()方法后，我们可以在这个回调方法得到HuaweiMap对象
        hMap = map
        mMarker = hMap.addMarker(MarkerOptions().position(LatLng(31.2304, 121.4737)).icon(BitmapDescriptorFactory.fromResource(R.drawable.ic_launcher_background)))
        hMap.moveCamera(CameraUpdateFactory.newLatLngZoom(LatLng(31.2304, 121.4737), 10f))
    }
    ```

3.  在Activity的onCreate方法中加载[MapFragment](zh-cn_topic_0000001145781021.md)，并调用[getMapAsync](zh-cn_topic_0000001145781021.md#section11704105017376)\(\)：

    示例代码如下：

    ```
    Java
    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_map_fragment_demo);
        mSupportMapFragment = (SupportMapFragment) getSupportFragmentManager().findFragmentById(R.id.mapfragment_mapfragmentdemo);
        mSupportMapFragment.getMapAsync(this);
    }
    ```

    ```
    Kotlin
    override fun onCreate(savedInstanceState: Bundle?) {
        super.onCreate(savedInstanceState)
        setContentView(R.layout.activity_map_fragment_demo)
        mSupportMapFragment = supportFragmentManager.findFragmentById(R.id.mapfragment_mapfragmentdemo) as SupportMapFragment?
        mSupportMapFragment?.getMapAsync(this)
    }
    ```


## 说明<a name="section102770202518"></a>

如果您使用V2版本的Google Maps SDK for Android，切换到Map Kit，需要将包名com.google.android.gms.maps替换成com.huawei.hms.maps；如果您使用V3版本的Google Maps SDK for Android，切换到Map Kit，需要将包名com.google.android.libraries.maps替换成com.huawei.hms.maps（替换包名可以使用Android Studio的**Edit **\>** Find **\>  **Replace in Path**…）。

## 总结<a name="section64502410516"></a>

上述内容是介绍了Google Maps与HUAWEI Map Kit的异同，我们提供了自动化工具来高效完成从Google Maps切换到Map Kit或者添加Map Kit的步骤，下面是关于工具的介绍以及使用指导：

[HMS ToolKit开发指南](https://developer.huawei.com/consumer/cn/doc/development/Tools-Guides/overview-0000001050060881)

[Map Kit手工转换指导书](https://developer.huawei.com/consumer/cn/doc/development/Tools-Guides/map-conversion-0000001050062227)

