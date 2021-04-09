# Function Experience<a name="EN-US_TOPIC_0000001099163554"></a>

-   [Map Display](#section13111635736)
-   [Map Interaction](#section75605732419)
-   [Marker Addition](#section28601833112416)
-   [Polygon](#section186815162418)
-   [Map Style Customization](#section1431610152518)

## Map Display<a name="section13111635736"></a>

<a name="table738320224018"></a>
<table><tbody><tr id="row1338342212015"><td class="row-nocellborder" style="border:none" valign="top" width="61.78%"><pre class="screen" id="screen127045596016"><a name="screen127045596016"></a><a name="screen127045596016"></a>// Create a <strong id="b034010221555"><a name="b034010221555"></a><a name="b034010221555"></a>MapView</strong> object.
public class MapViewDemoActivity extends BaseActivity implements OnMapReadyCallback {
    private static final String TAG = "MapViewDemoActivity";
    private MapView mMapView;
    private HuaweiMap hMap;
    @Override
    protected void onCreate(Bundle savedInstanceState) {
        Log.i(TAG, "onCreate: ");
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_map_view_demo);
        mMapView = findViewById(R.id.mapview_mapviewdemo);
        mMapView.onCreate(null);
        mMapView.getMapAsync(this);
    }
    @RequiresPermission(allOf = {ACCESS_FINE_LOCATION, ACCESS_WIFI_STATE})
    @Override
    public void onMapReady(HuaweiMap map) {
        Log.i(TAG, "onMapReady: ");
        hMap = map;
        hMap.setMyLocationEnabled(true);
        hMap.moveCamera(CameraUpdateFactory.newLatLngZoom(new LatLng(48.893478, 2.334595), 10));
    }
    @Override
    protected void onStart() {
        super.onStart();
        mMapView.onStart();
    }
    @Override
    protected void onStop() {
        super.onStop();
        mMapView.onStop();
    }
    @Override
    protected void onPause() {
        mMapView.onPause();
        super.onPause();
    }
    @Override
    protected void onResume() {
        super.onResume();
        mMapView.onResume();
    }
}
  </pre>
</td>
<td class="cellrowborder" style="border:none" valign="top" width="38.22%"><p id="p173838221201"><a name="p173838221201"></a><a name="p173838221201"></a><object id="object126117414426" height="717.4805333333334" data="en-us_media_0000001145923569.mp4" width="322.9882666666666"><param name="movie" id="param112937594958" value="en-us_media_0000001145923569.mp4"><param name="play" id="param143638513258" value="true"><param name="loop" id="param148413229258" value="false"><param name="wmode" id="param35753485558" value="transparent"></object></p>
</td>
</tr>
</tbody>
</table>

## Map Interaction<a name="section75605732419"></a>

<a name="table256017122419"></a>
<table><tbody><tr id="row35605722414"><td class="row-nocellborder" style="border:none" valign="top" width="62.35000000000001%"><pre class="screen" id="screen256077182412"><a name="screen256077182412"></a><a name="screen256077182412"></a>// Gesture-related code.
public class GestureDemoActivity extends BaseActivity implements OnMapReadyCallback {
    private static final String TAG = "GestureDemoActivity";
    private SupportMapFragment mSupportMapFragment;
    private HuaweiMap hMap;
    private UiSettings mUiSettings;
    @Override
    protected void onCreate(@Nullable Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_gesture_demo);
        mSupportMapFragment =
                (SupportMapFragment) getSupportFragmentManager().findFragmentById(R.id.mapfragment_gesturedemo);
        mSupportMapFragment.getMapAsync(this);
    }
    @RequiresPermission(allOf = {ACCESS_FINE_LOCATION, ACCESS_WIFI_STATE})
    @Override
    public void onMapReady(HuaweiMap paramHuaweiMap) {
        hMap = paramHuaweiMap;
        hMap.moveCamera(CameraUpdateFactory.newLatLngZoom(new LatLng(48.893478, 2.334595), 10));
        hMap.setMyLocationEnabled(false);
        hMap.getUiSettings().setCompassEnabled(false);
        hMap.getUiSettings().setZoomControlsEnabled(false);
        hMap.getUiSettings().setMyLocationButtonEnabled(false);
        mUiSettings = hMap.getUiSettings();
    }
    // Enable or disable zoom controls.
    public void setZoomButtonsEnabled(View v) {
        mUiSettings.setZoomControlsEnabled(((CheckBox) v).isChecked());
    }
    // Enable or disable the my-location layer.
    public void setMyLocationLayerEnabled(View v) {
        if (PermissionChecker.checkSelfPermission(this,
                Manifest.permission.ACCESS_FINE_LOCATION) == PackageManager.PERMISSION_GRANTED) {
            hMap.setMyLocationEnabled(((CheckBox) v).isChecked());
        }
    }
    // Enable or disable zoom gestures.
    public void setZoomGesturesEnabled(View v) {
        mUiSettings.setZoomGesturesEnabled(((CheckBox) v).isChecked());
    }
    // Enable or disable rotate gestures.
    public void setRotateGesturesEnabled(View v) {
        mUiSettings.setRotateGesturesEnabled(((CheckBox) v).isChecked());
    }
}</pre>
</td>
<td class="cellrowborder" style="border:none" valign="top" width="37.65%"><p id="p1183614232712"><a name="p1183614232712"></a><a name="p1183614232712"></a><object id="object17658204012915" height="717.4805333333334" data="en-us_media_0000001145723517.mp4" width="322.9882666666666"><param name="movie" id="param47106494258" value="en-us_media_0000001145723517.mp4"><param name="play" id="param154430545658" value="true"><param name="loop" id="param39695048458" value="false"><param name="wmode" id="param47085118158" value="transparent"></object></p>
</td>
</tr>
</tbody>
</table>

## Marker Addition<a name="section28601833112416"></a>

<a name="table13860163392414"></a>
<table><tbody><tr id="row086113382420"><td class="row-nocellborder" style="border:none" valign="top" width="62.33%"><pre class="screen" id="screen08611233182416"><a name="screen08611233182416"></a><a name="screen08611233182416"></a>// Marker-related code.
public class MarkerDemoActivity extends BaseActivity implements OnMapReadyCallback {
    private static final String TAG = "MarkerDemoActivity";
    private static final LatLng PARIS = new LatLng(48.893478, 2.334595);
    private SupportMapFragment mSupportMapFragment;
    private HuaweiMap hMap;
    private Marker mParis;
    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_marker_demo);
        Fragment fragment = getSupportFragmentManager().findFragmentById(R.id.mapfragment_markerdemo);
        if (fragment instanceof SupportMapFragment) {
            mSupportMapFragment = (SupportMapFragment) fragment;
            mSupportMapFragment.getMapAsync(this);
        }
    }
    @SuppressLint("MissingPermission")
    @Override
    public void onMapReady(HuaweiMap paramHuaweiMap) {
        hMap = paramHuaweiMap;
        hMap.moveCamera(CameraUpdateFactory.newLatLngZoom(new LatLng(48.893478, 2.334595), 14));
    }
    // Add a marker to the map.
    public void addMarker(View view) {
        if (mParis == null) {
            mParis =
                    hMap.addMarker(new MarkerOptions().position(PARIS).title("paris").snippet("hello").clusterable(true));
        }
    }
    // Remove the marker from the map.
    public void deleteMarker(View view) {
        if (null != mParis) {
            mParis.remove();
            mParis = null;
        }
    }
}</pre>
</td>
<td class="cellrowborder" style="border:none" valign="top" width="37.669999999999995%"><p id="p161811337522"><a name="p161811337522"></a><a name="p161811337522"></a><object id="object1017410441526" height="717.4805333333334" data="en-us_media_0000001099163578.mp4" width="322.9882666666666"><param name="movie" id="param147564540358" value="en-us_media_0000001099163578.mp4"><param name="play" id="param16202141158" value="true"><param name="loop" id="param48036454658" value="false"><param name="wmode" id="param179226338058" value="transparent"></object></p>
</td>
</tr>
</tbody>
</table>

## Polygon<a name="section186815162418"></a>

<a name="table188681551192415"></a>
<table><tbody><tr id="row13868105192415"><td class="row-nocellborder" style="border:none" valign="top" width="62.29%"><pre class="screen" id="screen13868351102419"><a name="screen13868351102419"></a><a name="screen13868351102419"></a>// Polygon-related code.
public class PolygonDemoActivity extends BaseActivity implements OnMapReadyCallback {
    private static final String TAG = "PolygonDemoActivity";
    private SupportMapFragment mSupportMapFragment;
    private HuaweiMap hMap;
    private Polygon mPolygon;
    @Override
    protected void onCreate(@Nullable Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_polygon_demo);
        Fragment fragment = getSupportFragmentManager().findFragmentById(R.id.mapfragment_polygondemo);
        if (fragment instanceof SupportMapFragment) {
            mSupportMapFragment = (SupportMapFragment) fragment;
            mSupportMapFragment.getMapAsync(this);
        }
    }
    @RequiresPermission(allOf = {ACCESS_FINE_LOCATION, ACCESS_WIFI_STATE})
    @Override
    public void onMapReady(HuaweiMap paramHuaweiMap) {
        Log.i(TAG, "onMapReady: ");
        hMap = paramHuaweiMap;
        hMap.moveCamera(CameraUpdateFactory.newLatLngZoom(new LatLng(48.893478, 2.334595), 10));
    }
    // Add a polygon to the map.
    public void addPolygon(View view) {
        List&lt;PatternItem&gt; gonPattern = new ArrayList&lt;&gt;();

        PatternItem patternItemDash = new PatternItem(0, 200);
        gonPattern.add(patternItemDash);
        PatternItem patternItemDot = new PatternItem(1, 10);
        gonPattern.add(patternItemDot);
        PatternItem patternItemGap = new PatternItem(2, 10);
        gonPattern.add(patternItemGap);
        mPolygon = hMap
                .addPolygon(new PolygonOptions().addAll(MapUtils.createRectangle(new LatLng(48.893478, 2.334595), 0.1, 0.1))
                        .fillColor(Color.GREEN)
                        .strokeColor(Color.RED)
                        .strokeWidth(20)
                        .visible(true)
                        .zIndex(10L)
                        .geodesic(true)
                        .clickable(true)
                        .strokePattern(gonPattern)
                        .strokeJointType(ROUND));
    }
    // Remove the polygon from the map.
    public void removePolygon(View view) {
        if (null != mPolygon) {
            mPolygon.remove();
        }
    }
}</pre>
</td>
<td class="cellrowborder" style="border:none" valign="top" width="37.71%"><p id="p1286935132416"><a name="p1286935132416"></a><a name="p1286935132416"></a><object id="object17414141920533" height="717.4805333333334" data="en-us_media_0000001098843596.mp4" width="322.9882666666666"><param name="movie" id="param83573846958" value="en-us_media_0000001098843596.mp4"><param name="play" id="param117186727658" value="true"><param name="loop" id="param122712880358" value="false"><param name="wmode" id="param75857868258" value="transparent"></object></p>
</td>
</tr>
</tbody>
</table>

## Map Style Customization<a name="section1431610152518"></a>

<a name="table6317170112514"></a>
<table><tbody><tr id="row133171011254"><td class="row-nocellborder" style="border:none" valign="top" width="62.29%"><pre class="screen" id="screen1631719018254"><a name="screen1631719018254"></a><a name="screen1631719018254"></a>// StyleMap-related code.
public class StyleMapDemoActivity extends BaseActivity implements OnMapReadyCallback {
    private SupportMapFragment mSupportMapFragment;
    private HuaweiMap hMap;

    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_style_map_demo);
        Fragment fragment = getSupportFragmentManager().findFragmentById(R.id.mapfragment_stylemapdemo);
        if (fragment instanceof SupportMapFragment) {
            mSupportMapFragment = (SupportMapFragment) fragment;
            mSupportMapFragment.getMapAsync(this);
        }
    }

    @RequiresPermission(allOf = {ACCESS_FINE_LOCATION, ACCESS_WIFI_STATE})
    @Override
    public void onMapReady(HuaweiMap huaweiMap) {
        hMap = huaweiMap;
        hMap.moveCamera(CameraUpdateFactory.newLatLngZoom(new LatLng(48.893478, 2.334595), 10));
    }

    public void simple(View view) {
        hMap.setMapStyle(MapStyleOptions.loadRawResourceStyle(this, R.raw.mapstyle_simple));
    }
    public void night(View view) {
        hMap.setMapStyle(MapStyleOptions.loadRawResourceStyle(this, R.raw.mapstyle_night));
    }
    public void grayScale(View view) {
        hMap.setMapStyle(MapStyleOptions.loadRawResourceStyle(this, R.raw.mapstyle_grayscale));
    }
    public void defaultStyle(View view) {
        hMap.setMapStyle(null);
    }
}</pre>
</td>
<td class="cellrowborder" style="border:none" valign="top" width="37.71%"><p id="p1231713013254"><a name="p1231713013254"></a><a name="p1231713013254"></a><object id="object15232185910539" height="717.4805333333334" data="en-us_media_0000001145843447.mp4" width="322.9882666666666"><param name="movie" id="param68951670858" value="en-us_media_0000001145843447.mp4"><param name="play" id="param106913288458" value="true"><param name="loop" id="param19021637958" value="false"><param name="wmode" id="param105470071858" value="transparent"></object></p>
</td>
</tr>
</tbody>
</table>

