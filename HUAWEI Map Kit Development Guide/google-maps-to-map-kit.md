# Migration From Google Maps to HUAWEI Map Kit<a name="EN-US_TOPIC_0000001099163558"></a>

-   [Overview](#section14565114715461)
-   [Preparations](#section831111183470)
-   [Creating a Map](#section8128184194818)
    -   [Google Maps SDK](#section1937014121494)
    -   [Map Kit](#section1090724194914)

-   [Adding a Marker](#section79311456184914)
    -   [Google Maps SDK](#section5442173845020)
    -   [Map Kit](#section1367459145020)

-   [Precaution](#section102770202518)
-   [Summary](#section64502410516)

## Overview<a name="section14565114715461"></a>

This tutorial helps you migrate the Google Maps SDK for Android to the HMS Core Map SDK for Android in your Android app. It starts with basic environment settings, and covers some basic use cases, such as creating a map and adding a marker. At the bottom of the page is a summary in which we provide links to an automated tool that helps you finish the migration. 

## Preparations<a name="section831111183470"></a>

Before integrating HUAWEI Map Kit, complete the following preparations:

-   Create an app in  [AppGallery Connect](https://developer.huawei.com/consumer/en/service/josp/agc/index.html).
-   Create an Android Studio project.
-   Generate a signing certificate and a signing certificate fingerprint. 
-   Configure the signing certificate fingerprint in  [AppGallery Connect](https://developer.huawei.com/consumer/en/service/josp/agc/index.html). 
-   Integrate the HMS Core SDK.
-   Configure a project signature.

For details, please refer to  [Preparations for Integrating HUAWEI HMS Core](https://developer.huawei.com/consumer/en/codelab/HMSPreparation/index.html#0).

## Creating a Map<a name="section8128184194818"></a>

This part describes how to create a map using Google Maps SDK and HUAWEI Map Kit. 

### Google Maps SDK<a name="section1937014121494"></a>

1.  Add build dependencies to the  **build.gradle**  file of your app. 

    ```
    implementation 'com.google.android.gms:play-services-maps:15.0.0'  
    ```

2.  Add a fragment to the activity layout file.

    ```
    <fragment   
        android:id="@+id/mapFragment"   
        android:name="com.google.android.gms.maps.SupportMapFragment"
        android:layout_width="match_parent"
        android:layout_height="match_parent"/>  
    ```

3.  Add a Google Android API key in the  **application**  block in the  **AndroidManifest.xml**  file.

    ```
    <meta-data 
    android:name="com.google.android.geo.API_KEY"
    android:value="YOUR_GOOGLE_KEY_GOES_HERE"/>
    ```


### Map Kit<a name="section1090724194914"></a>

1.  Add build dependencies to the  **build.gradle**  file of your app. 

    ```
    implementation 'com.huawei.hms:maps:5.2.0.302'
    ```

2.  Add a fragment to the activity layout file.

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


## Adding a Marker<a name="section79311456184914"></a>

This part describes how to add a marker using Google Maps SDK and HUAWEI Map Kit. 

### Google Maps SDK<a name="section5442173845020"></a>

1.  Define a  **GoogleMap**  object and a  **MapFragment**  object.

    The sample code is as follows:

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

2.  Implement the  **OnMapReadyCallback**  API and override the  **onMapReady**  method.

    The sample code is as follows:

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

3.  Load  **MapFragment**  in the  **onCreate**  method of  **Activity**  and call  **getMapAsync\(\)**.

    The sample code is as follows:

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

1.  Define a  [HuaweiMap](en-us_topic_0000001098683684.md)  object and a  [MapFragment](en-us_topic_0000001099163506.md)  object.

    The sample code is as follows:

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

2.  Implement the  [OnMapReadyCallback](en-us_topic_0000001098843540.md)  API and override the  [onMapReady](en-us_topic_0000001098843540.md#section74342919481)  method.

    The sample code is as follows:

    ```
    Java
    @Override  
    public void onMapReady(HuaweiMap map) {
        // After calling the getMapAsync() method, you can obtain a HuaweiMap object through this callback method. 
        hMap = map;  
        mMarker = hMap.addMarker(new MarkerOptions().position(new LatLng(31.2304, 121.4737)).icon(BitmapDescriptorFactory.fromResource(R.drawable.ic_launcher_background)));  
        hMap.moveCamera(CameraUpdateFactory.newLatLngZoom(new LatLng(31.2304, 121.4737), 10));  
    }
    ```

    ```
    Kotlin
    override fun onMapReady(map: HuaweiMap) {
        // After calling the getMapAsync() method, you can obtain a HuaweiMap object through this callback method. 
        hMap = map
        mMarker = hMap.addMarker(MarkerOptions().position(LatLng(31.2304, 121.4737)).icon(BitmapDescriptorFactory.fromResource(R.drawable.ic_launcher_background)))
        hMap.moveCamera(CameraUpdateFactory.newLatLngZoom(LatLng(31.2304, 121.4737), 10f))
    }
    ```

3.  Load  [MapFragment](en-us_topic_0000001099163506.md)  in the  **onCreate**  method of the activity and call  [getMapAsync](en-us_topic_0000001099163506.md#section11704105017376)\(\).

    The sample code is as follows:

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


## Precaution<a name="section102770202518"></a>

To replace the V2-version Google Maps SDK for Android with the HUAWEI Map SDK, you need to replace the package name  **com.google.android.gms.maps**  with  **com.huawei.hms.maps**. To replace the V3-version Google Maps SDK for Android with the HUAWEI Map SDK, you need to replace the package name  **com.google.android.libraries.maps**  with  **com.huawei.hms.maps**. \(To replace the package name, you can go to  **Edit**  \>  **Find**  \>  **Replace in Path**  in Android Studio.\)

## Summary<a name="section64502410516"></a>

This tutorial has covered the differences between the Google Maps SDK and HUAWEI Map Kit. HMS Toolkit, an automated tool, is also provided to help you migrate from the Google Maps SDK to HUAWEI Map Kit or add HUAWEI Map Kit to your app efficiently. For details, visit the following links:

[HMS Toolkit Development Guide](https://developer.huawei.com/consumer/en/doc/development/Tools-Guides/overview-0000001050060881)

[Map Kit Manual Conversion Guide](https://developer.huawei.com/consumer/en/doc/development/Tools-Guides/map-conversion-0000001050062227)

