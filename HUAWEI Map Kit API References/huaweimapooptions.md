# HuaweiMapOptions<a name="EN-US_TOPIC_0000001099661076"></a>

-   [Public Constructor Summary](#section192474225348)
-   [Public Method Summary](#section9782050163418)
-   [Public Methods](#section45771096013)
-   [camera](#section798402413010)
-   [compassEnabled](#section158911641711)
-   [createFromAttributes](#section328210591811)
-   [getCamera](#section810020521830)
-   [getCompassEnabled](#section1694714242410)
-   [getLatLngBoundsForCameraTarget](#section4666175815418)
-   [getLiteMode](#section141801147759)
-   [getMapType](#section12521027168)
-   [getMaxZoomPreference](#section78861111672)
-   [getMinZoomPreference](#section10719165715713)
-   [getRotateGesturesEnabled](#section16773144116814)
-   [getScrollGesturesEnabled](#section446415211395)
-   [getTiltGesturesEnabled](#section072675119915)
-   [getUseViewLifecycleInFragment](#section0818164121012)
-   [getZOrderOnTop](#section2011561881120)
-   [getZoomControlsEnabled](#section15687165511118)
-   [getZoomGesturesEnabled](#section202671951161310)
-   [latLngBoundsForCameraTarget](#section1394012719138)
-   [liteMode](#section29491334161413)
-   [mapType](#section2485024181514)
-   [maxZoomPreference](#section88791059160)
-   [minZoomPreference](#section1616415503161)
-   [rotateGesturesEnabled](#section65033374179)
-   [scrollGesturesEnabled](#section2094318183189)
-   [tiltGesturesEnabled](#section1469615401913)
-   [useViewLifecycleInFragment](#section14526745191913)
-   [zOrderOnTop](#section17532163552014)
-   [zoomControlsEnabled](#section937192082118)
-   [zoomGesturesEnabled](#section67067692220)


<a name="table4780mcpsimp"></a>
<table><thead align="left"><tr id="row4784mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p4786mcpsimp"><a name="p4786mcpsimp"></a><a name="p4786mcpsimp"></a>Class Info</p>
</th>
</tr>
</thead>
<tbody><tr id="row4787mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p5395143092619"><a name="p5395143092619"></a><a name="p5395143092619"></a>public final class HuaweiMapOptions</p>
<p id="p4789mcpsimp"><a name="p4789mcpsimp"></a><a name="p4789mcpsimp"></a>Final class that extends <strong id="b117519594423"><a name="b117519594423"></a><a name="b117519594423"></a>Object</strong> and implements the <strong id="b97511859144214"><a name="b97511859144214"></a><a name="b97511859144214"></a>Parcelable</strong> API. This class defines attributes for a <a href="huaweimap.md">HuaweiMap</a> object, and they can be used when you add a map to your app. If <a href="mapfragment.md">MapFragment</a> is used, you can use the static factory method <a href="mapfragment.md#section2225611183820">newInstance</a>(<a href="huaweimapooptions.md">HuaweiMapOptions</a>) to pass the attributes. If <a href="mapview.md">MapView</a> is used, you can use the constructor <a href="mapview.md">MapView</a><strong id="b13330123811179"><a name="b13330123811179"></a><a name="b13330123811179"></a>(Context, </strong><a href="huaweimapooptions.md">HuaweiMapOptions</a><strong id="b43211417172"><a name="b43211417172"></a><a name="b43211417172"></a>)</strong> to pass the attributes.</p>
</td>
</tr>
</tbody>
</table>

## Public Constructor Summary<a name="section192474225348"></a>

<a name="table4793mcpsimp"></a>
<table><thead align="left"><tr id="row4797mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p145mcpsimp"><a name="p145mcpsimp"></a><a name="p145mcpsimp"></a>Constructor Name</p>
</th>
</tr>
</thead>
<tbody><tr id="row4800mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p4802mcpsimp"><a name="p4802mcpsimp"></a><a name="p4802mcpsimp"></a><a href="huaweimapooptions.md">HuaweiMapOptions</a>()</p>
<p id="p1716911720333"><a name="p1716911720333"></a><a name="p1716911720333"></a>Default constructor of the <strong id="b2624722185615"><a name="b2624722185615"></a><a name="b2624722185615"></a>HuaweiMapOptions</strong> class.</p>
</td>
</tr>
</tbody>
</table>

## Public Method Summary<a name="section9782050163418"></a>

<a name="table4804mcpsimp"></a>
<table><thead align="left"><tr id="row4809mcpsimp"><th class="cellrowborder" valign="top" width="40%" id="mcps1.1.3.1.1"><p id="p4811mcpsimp"><a name="p4811mcpsimp"></a><a name="p4811mcpsimp"></a>Qualifier and Type</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.1.3.1.2"><p id="p4813mcpsimp"><a name="p4813mcpsimp"></a><a name="p4813mcpsimp"></a>Method Name and Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row4819mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p4821mcpsimp"><a name="p4821mcpsimp"></a><a name="p4821mcpsimp"></a><a href="huaweimapooptions.md">HuaweiMapOptions</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p4823mcpsimp"><a name="p4823mcpsimp"></a><a name="p4823mcpsimp"></a><a href="#section798402413010">camera</a>(<a href="cameraposition.md">CameraPosition</a> cameraPosition)</p>
<p id="p788422333217"><a name="p788422333217"></a><a name="p788422333217"></a>Sets the initial camera position for a map based on camera parameters.</p>
</td>
</tr>
<tr id="row4824mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p4826mcpsimp"><a name="p4826mcpsimp"></a><a name="p4826mcpsimp"></a><a href="huaweimapooptions.md">HuaweiMapOptions</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p4828mcpsimp"><a name="p4828mcpsimp"></a><a name="p4828mcpsimp"></a><a href="#section158911641711">compassEnabled</a>(boolean isCompassEnabled)</p>
<p id="p12135025103217"><a name="p12135025103217"></a><a name="p12135025103217"></a>Sets whether to enable the compass for a map based on the <strong id="b2047233912414"><a name="b2047233912414"></a><a name="b2047233912414"></a>isCompassEnabled</strong> parameter.</p>
</td>
</tr>
<tr id="row4829mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p4831mcpsimp"><a name="p4831mcpsimp"></a><a name="p4831mcpsimp"></a>static <a href="huaweimapooptions.md">HuaweiMapOptions</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p4833mcpsimp"><a name="p4833mcpsimp"></a><a name="p4833mcpsimp"></a><a href="#section328210591811">createFromAttributes</a>(Context context, AttributeSet attrs)</p>
<p id="p20425122611322"><a name="p20425122611322"></a><a name="p20425122611322"></a>Creates a <a href="huaweimapooptions.md">HuaweiMapOptions</a> object based on a custom attribute file.</p>
</td>
</tr>
<tr id="row4839mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p4841mcpsimp"><a name="p4841mcpsimp"></a><a name="p4841mcpsimp"></a><a href="cameraposition.md">CameraPosition</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p4843mcpsimp"><a name="p4843mcpsimp"></a><a name="p4843mcpsimp"></a><a href="#section810020521830">getCamera</a>()</p>
<p id="p12510203043210"><a name="p12510203043210"></a><a name="p12510203043210"></a>Obtains the current configuration of the camera.</p>
</td>
</tr>
<tr id="row4844mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p4846mcpsimp"><a name="p4846mcpsimp"></a><a name="p4846mcpsimp"></a>Boolean</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p4848mcpsimp"><a name="p4848mcpsimp"></a><a name="p4848mcpsimp"></a><a href="#section1694714242410">getCompassEnabled</a>()</p>
<p id="p7451332113211"><a name="p7451332113211"></a><a name="p7451332113211"></a>Checks whether the compass is enabled for a map.</p>
</td>
</tr>
<tr id="row4849mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p4851mcpsimp"><a name="p4851mcpsimp"></a><a name="p4851mcpsimp"></a><a href="latlngbounds.md">LatLngBounds</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p4853mcpsimp"><a name="p4853mcpsimp"></a><a name="p4853mcpsimp"></a><a href="#section4666175815418">getLatLngBoundsForCameraTarget</a>()</p>
<p id="p1995018333326"><a name="p1995018333326"></a><a name="p1995018333326"></a>Obtains the bounds for constraining the camera target. If the bounds are not specified, <strong id="b1755215424315"><a name="b1755215424315"></a><a name="b1755215424315"></a>null</strong> will be returned.</p>
</td>
</tr>
<tr id="row4854mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p4856mcpsimp"><a name="p4856mcpsimp"></a><a name="p4856mcpsimp"></a>Boolean</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p4858mcpsimp"><a name="p4858mcpsimp"></a><a name="p4858mcpsimp"></a><a href="#section141801147759">getLiteMode</a>()</p>
<p id="p169671637163216"><a name="p169671637163216"></a><a name="p169671637163216"></a>Checks whether the lite mode is enabled for a map.</p>
</td>
</tr>
<tr id="row4864mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p4866mcpsimp"><a name="p4866mcpsimp"></a><a name="p4866mcpsimp"></a>int</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p4868mcpsimp"><a name="p4868mcpsimp"></a><a name="p4868mcpsimp"></a><a href="#section12521027168">getMapType</a>()</p>
<p id="p5283841173218"><a name="p5283841173218"></a><a name="p5283841173218"></a>Obtains the current map type.</p>
</td>
</tr>
<tr id="row4869mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p4871mcpsimp"><a name="p4871mcpsimp"></a><a name="p4871mcpsimp"></a>Float</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p4873mcpsimp"><a name="p4873mcpsimp"></a><a name="p4873mcpsimp"></a><a href="#section78861111672">getMaxZoomPreference</a>()</p>
<p id="p645612428326"><a name="p645612428326"></a><a name="p645612428326"></a>Obtains the preferred maximum zoom level of a map.</p>
</td>
</tr>
<tr id="row4874mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p4876mcpsimp"><a name="p4876mcpsimp"></a><a name="p4876mcpsimp"></a>Float</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p4878mcpsimp"><a name="p4878mcpsimp"></a><a name="p4878mcpsimp"></a><a href="#section10719165715713">getMinZoomPreference</a>()</p>
<p id="p54321043203217"><a name="p54321043203217"></a><a name="p54321043203217"></a>Obtains the preferred minimum zoom level of a map. </p>
</td>
</tr>
<tr id="row4879mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p4881mcpsimp"><a name="p4881mcpsimp"></a><a name="p4881mcpsimp"></a>Boolean</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p4883mcpsimp"><a name="p4883mcpsimp"></a><a name="p4883mcpsimp"></a><a href="#section16773144116814">getRotateGesturesEnabled</a>()</p>
<p id="p2354104413218"><a name="p2354104413218"></a><a name="p2354104413218"></a>Checks whether rotation gestures are enabled for a map. </p>
</td>
</tr>
<tr id="row4884mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p4886mcpsimp"><a name="p4886mcpsimp"></a><a name="p4886mcpsimp"></a>Boolean</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p4888mcpsimp"><a name="p4888mcpsimp"></a><a name="p4888mcpsimp"></a><a href="#section446415211395">getScrollGesturesEnabled</a>()</p>
<p id="p11338645163217"><a name="p11338645163217"></a><a name="p11338645163217"></a>Checks whether scroll gestures are enabled for a map.</p>
</td>
</tr>
<tr id="row4889mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p4891mcpsimp"><a name="p4891mcpsimp"></a><a name="p4891mcpsimp"></a>Boolean</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p4893mcpsimp"><a name="p4893mcpsimp"></a><a name="p4893mcpsimp"></a><a href="#section072675119915">getTiltGesturesEnabled</a>()</p>
<p id="p9604646173216"><a name="p9604646173216"></a><a name="p9604646173216"></a>Checks whether tilt gestures are enabled for a map.</p>
</td>
</tr>
<tr id="row4894mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p4896mcpsimp"><a name="p4896mcpsimp"></a><a name="p4896mcpsimp"></a>Boolean</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p4898mcpsimp"><a name="p4898mcpsimp"></a><a name="p4898mcpsimp"></a><a href="#section0818164121012">getUseViewLifecycleInFragment</a>()</p>
<p id="p17161149113219"><a name="p17161149113219"></a><a name="p17161149113219"></a>Checks whether the lifecycle of a map is bound to the view of <a href="mapfragment.md">MapFragment</a> or to <a href="mapfragment.md">MapFragment</a> itself when <a href="mapfragment.md">MapFragment</a> is used. </p>
</td>
</tr>
<tr id="row4899mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p4901mcpsimp"><a name="p4901mcpsimp"></a><a name="p4901mcpsimp"></a>Boolean</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p4903mcpsimp"><a name="p4903mcpsimp"></a><a name="p4903mcpsimp"></a><a href="#section2011561881120">getZOrderOnTop</a>()</p>
<p id="p12233950183215"><a name="p12233950183215"></a><a name="p12233950183215"></a>Checks whether the surface of a map view is placed on top of its window.</p>
</td>
</tr>
<tr id="row4904mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p4906mcpsimp"><a name="p4906mcpsimp"></a><a name="p4906mcpsimp"></a>Boolean</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p4908mcpsimp"><a name="p4908mcpsimp"></a><a name="p4908mcpsimp"></a><a href="#section15687165511118">getZoomControlsEnabled</a>()</p>
<p id="p111172518328"><a name="p111172518328"></a><a name="p111172518328"></a>Checks whether the zoom function is enabled for a map.</p>
</td>
</tr>
<tr id="row4909mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p4911mcpsimp"><a name="p4911mcpsimp"></a><a name="p4911mcpsimp"></a>Boolean</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p4913mcpsimp"><a name="p4913mcpsimp"></a><a name="p4913mcpsimp"></a><a href="#section202671951161310">getZoomGesturesEnabled</a>()</p>
<p id="p1598395173216"><a name="p1598395173216"></a><a name="p1598395173216"></a>Checks whether zoom gestures are enabled for a map.</p>
</td>
</tr>
<tr id="row4914mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p4916mcpsimp"><a name="p4916mcpsimp"></a><a name="p4916mcpsimp"></a><a href="huaweimapooptions.md">HuaweiMapOptions</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p4918mcpsimp"><a name="p4918mcpsimp"></a><a name="p4918mcpsimp"></a><a href="#section1394012719138">latLngBoundsForCameraTarget</a>(<a href="latlngbounds.md">LatLngBounds</a> latLngBounds)</p>
<p id="p172407537326"><a name="p172407537326"></a><a name="p172407537326"></a>Sets a <a href="latlngbounds.md">LatLngBounds</a> object to constrain the camera target so that the camera target does not move outside the bounds when a user scrolls the map.</p>
</td>
</tr>
<tr id="row4919mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p4921mcpsimp"><a name="p4921mcpsimp"></a><a name="p4921mcpsimp"></a><a href="huaweimapooptions.md">HuaweiMapOptions</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p4923mcpsimp"><a name="p4923mcpsimp"></a><a name="p4923mcpsimp"></a><a href="#section29491334161413">liteMode</a>(boolean isLiteMode)</p>
<p id="p339575573214"><a name="p339575573214"></a><a name="p339575573214"></a>Sets whether to create a map in lite mode.</p>
</td>
</tr>
<tr id="row4929mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p4931mcpsimp"><a name="p4931mcpsimp"></a><a name="p4931mcpsimp"></a><a href="huaweimapooptions.md">HuaweiMapOptions</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p4933mcpsimp"><a name="p4933mcpsimp"></a><a name="p4933mcpsimp"></a><a href="#section2485024181514">mapType</a>(int mapType)</p>
<p id="p93121158123218"><a name="p93121158123218"></a><a name="p93121158123218"></a>Sets the Huawei map type.</p>
</td>
</tr>
<tr id="row4934mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p4936mcpsimp"><a name="p4936mcpsimp"></a><a name="p4936mcpsimp"></a><a href="huaweimapooptions.md">HuaweiMapOptions</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p4938mcpsimp"><a name="p4938mcpsimp"></a><a name="p4938mcpsimp"></a><a href="#section88791059160">maxZoomPreference</a>(float maxZoomLevel)</p>
<p id="p751705917324"><a name="p751705917324"></a><a name="p751705917324"></a>Sets the preferred maximum zoom level.</p>
</td>
</tr>
<tr id="row4939mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p4941mcpsimp"><a name="p4941mcpsimp"></a><a name="p4941mcpsimp"></a><a href="huaweimapooptions.md">HuaweiMapOptions</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p4943mcpsimp"><a name="p4943mcpsimp"></a><a name="p4943mcpsimp"></a><a href="#section1616415503161">minZoomPreference</a>(float minZoomLevel)</p>
<p id="p12544707330"><a name="p12544707330"></a><a name="p12544707330"></a>Sets the preferred minimum zoom level.</p>
</td>
</tr>
<tr id="row4944mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p4946mcpsimp"><a name="p4946mcpsimp"></a><a name="p4946mcpsimp"></a><a href="huaweimapooptions.md">HuaweiMapOptions</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p4948mcpsimp"><a name="p4948mcpsimp"></a><a name="p4948mcpsimp"></a><a href="#section65033374179">rotateGesturesEnabled</a>(boolean isRotateGesturesEnabled)</p>
<p id="p141720211339"><a name="p141720211339"></a><a name="p141720211339"></a>Sets whether to enable rotation gestures for a map. </p>
</td>
</tr>
<tr id="row4949mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p4951mcpsimp"><a name="p4951mcpsimp"></a><a name="p4951mcpsimp"></a><a href="huaweimapooptions.md">HuaweiMapOptions</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p4953mcpsimp"><a name="p4953mcpsimp"></a><a name="p4953mcpsimp"></a><a href="#section2094318183189">scrollGesturesEnabled</a>(boolean isScrollGesturesEnabled)</p>
<p id="p13271193143318"><a name="p13271193143318"></a><a name="p13271193143318"></a>Sets whether to enable scroll gestures for a map. </p>
</td>
</tr>
<tr id="row4954mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p4956mcpsimp"><a name="p4956mcpsimp"></a><a name="p4956mcpsimp"></a><a href="huaweimapooptions.md">HuaweiMapOptions</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p4958mcpsimp"><a name="p4958mcpsimp"></a><a name="p4958mcpsimp"></a><a href="#section1469615401913">tiltGesturesEnabled</a>(boolean isTiltGesturesEnabled)</p>
<p id="p21051441336"><a name="p21051441336"></a><a name="p21051441336"></a>Sets whether to enable rotation gestures for a map. </p>
</td>
</tr>
<tr id="row4959mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p4961mcpsimp"><a name="p4961mcpsimp"></a><a name="p4961mcpsimp"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p4963mcpsimp"><a name="p4963mcpsimp"></a><a name="p4963mcpsimp"></a>toString()</p>
<p id="p170012671313"><a name="p170012671313"></a><a name="p170012671313"></a>Returns the object as a string.</p>
</td>
</tr>
<tr id="row4964mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p4966mcpsimp"><a name="p4966mcpsimp"></a><a name="p4966mcpsimp"></a><a href="huaweimapooptions.md">HuaweiMapOptions</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p4968mcpsimp"><a name="p4968mcpsimp"></a><a name="p4968mcpsimp"></a><a href="#section14526745191913">useViewLifecycleInFragment</a>(boolean isUseViewLifecycleInFragment)</p>
<p id="p4856191216335"><a name="p4856191216335"></a><a name="p4856191216335"></a>Sets whether to bind the lifecycle of a map to the view of <a href="mapfragment.md">MapFragment</a> or to <a href="mapfragment.md">MapFragment</a> itself. </p>
</td>
</tr>
<tr id="row4969mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p4971mcpsimp"><a name="p4971mcpsimp"></a><a name="p4971mcpsimp"></a>void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p4973mcpsimp"><a name="p4973mcpsimp"></a><a name="p4973mcpsimp"></a>writeToParcel(Parcel out, int flags)</p>
<p id="p154172361913"><a name="p154172361913"></a><a name="p154172361913"></a>Serializes data.</p>
</td>
</tr>
<tr id="row4974mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p4976mcpsimp"><a name="p4976mcpsimp"></a><a name="p4976mcpsimp"></a><a href="huaweimapooptions.md">HuaweiMapOptions</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p4978mcpsimp"><a name="p4978mcpsimp"></a><a name="p4978mcpsimp"></a><a href="#section17532163552014">zOrderOnTop</a>(boolean zOrderOnTop)</p>
<p id="p186911156337"><a name="p186911156337"></a><a name="p186911156337"></a>Sets whether to place the surface of a map view on top of its window.</p>
</td>
</tr>
<tr id="row4979mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p4981mcpsimp"><a name="p4981mcpsimp"></a><a name="p4981mcpsimp"></a><a href="huaweimapooptions.md">HuaweiMapOptions</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p4983mcpsimp"><a name="p4983mcpsimp"></a><a name="p4983mcpsimp"></a><a href="#section937192082118">zoomControlsEnabled</a>(boolean isZoomControlsEnabled)</p>
<p id="p19407171783317"><a name="p19407171783317"></a><a name="p19407171783317"></a>Sets whether to enable the zoom function for the camera. </p>
</td>
</tr>
<tr id="row4984mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p4986mcpsimp"><a name="p4986mcpsimp"></a><a name="p4986mcpsimp"></a><a href="huaweimapooptions.md">HuaweiMapOptions</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p4988mcpsimp"><a name="p4988mcpsimp"></a><a name="p4988mcpsimp"></a><a href="#section67067692220">zoomGesturesEnabled</a>(boolean isZoomGesturesEnabled)</p>
<p id="p1730312443310"><a name="p1730312443310"></a><a name="p1730312443310"></a>Sets whether to enable zoom gestures for a map. </p>
</td>
</tr>
</tbody>
</table>

## Public Methods<a name="section45771096013"></a>

## camera<a name="section798402413010"></a>

<a name="table4991mcpsimp"></a>
<table><thead align="left"><tr id="row4995mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p4997mcpsimp"><a name="p4997mcpsimp"></a><a name="p4997mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row4998mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p5000mcpsimp"><a name="p5000mcpsimp"></a><a name="p5000mcpsimp"></a>public <a href="huaweimapooptions.md">HuaweiMapOptions</a> camera(<a href="cameraposition.md">CameraPosition </a>cameraPosition)</p>
<p id="p5003mcpsimp"><a name="p5003mcpsimp"></a><a name="p5003mcpsimp"></a>Sets the initial camera position for a map based on camera parameters.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table5006mcpsimp"></a>
<table><thead align="left"><tr id="row5011mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p5013mcpsimp"><a name="p5013mcpsimp"></a><a name="p5013mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p5015mcpsimp"><a name="p5015mcpsimp"></a><a name="p5015mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row5016mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p5018mcpsimp"><a name="p5018mcpsimp"></a><a name="p5018mcpsimp"></a>cameraPosition</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p5020mcpsimp"><a name="p5020mcpsimp"></a><a name="p5020mcpsimp"></a>Camera position.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table5023mcpsimp"></a>
<table><thead align="left"><tr id="row5028mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p5030mcpsimp"><a name="p5030mcpsimp"></a><a name="p5030mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p5032mcpsimp"><a name="p5032mcpsimp"></a><a name="p5032mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row5033mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p5035mcpsimp"><a name="p5035mcpsimp"></a><a name="p5035mcpsimp"></a><a href="huaweimapooptions.md">HuaweiMapOptions</a></p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p5037mcpsimp"><a name="p5037mcpsimp"></a><a name="p5037mcpsimp"></a><strong id="b5184152964517"><a name="b5184152964517"></a><a name="b5184152964517"></a>HuaweiMapOptions</strong> object.</p>
</td>
</tr>
</tbody>
</table>

## compassEnabled<a name="section158911641711"></a>

<a name="table5039mcpsimp"></a>
<table><thead align="left"><tr id="row5043mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p5045mcpsimp"><a name="p5045mcpsimp"></a><a name="p5045mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row5046mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p5048mcpsimp"><a name="p5048mcpsimp"></a><a name="p5048mcpsimp"></a>public <a href="huaweimapooptions.md">HuaweiMapOptions</a> compassEnabled(boolean isCompassEnabled)</p>
<p id="p5051mcpsimp"><a name="p5051mcpsimp"></a><a name="p5051mcpsimp"></a>Sets whether to enable the compass for a map based on the <strong id="b75172031124512"><a name="b75172031124512"></a><a name="b75172031124512"></a>isCompassEnabled</strong> parameter.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table5054mcpsimp"></a>
<table><thead align="left"><tr id="row5059mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p5061mcpsimp"><a name="p5061mcpsimp"></a><a name="p5061mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p5063mcpsimp"><a name="p5063mcpsimp"></a><a name="p5063mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row5064mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p5066mcpsimp"><a name="p5066mcpsimp"></a><a name="p5066mcpsimp"></a>isCompassEnabled</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p5068mcpsimp"><a name="p5068mcpsimp"></a><a name="p5068mcpsimp"></a>Indicates whether to enable the compass. <strong id="b1550719019468"><a name="b1550719019468"></a><a name="b1550719019468"></a>true</strong> (default): yes; <strong id="b165131208464"><a name="b165131208464"></a><a name="b165131208464"></a>false</strong>: no.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table5071mcpsimp"></a>
<table><thead align="left"><tr id="row5076mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p5078mcpsimp"><a name="p5078mcpsimp"></a><a name="p5078mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p5080mcpsimp"><a name="p5080mcpsimp"></a><a name="p5080mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row5081mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p5083mcpsimp"><a name="p5083mcpsimp"></a><a name="p5083mcpsimp"></a><a href="huaweimapooptions.md">HuaweiMapOptions</a></p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p5085mcpsimp"><a name="p5085mcpsimp"></a><a name="p5085mcpsimp"></a><strong id="b1295554284617"><a name="b1295554284617"></a><a name="b1295554284617"></a>HuaweiMapOptions</strong> object.</p>
</td>
</tr>
</tbody>
</table>

## createFromAttributes<a name="section328210591811"></a>

<a name="table5087mcpsimp"></a>
<table><thead align="left"><tr id="row5091mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p5093mcpsimp"><a name="p5093mcpsimp"></a><a name="p5093mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row5094mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p5096mcpsimp"><a name="p5096mcpsimp"></a><a name="p5096mcpsimp"></a>public static <a href="huaweimapooptions.md">HuaweiMapOptions</a> createFromAttributes(Context context, AttributeSet attrs)</p>
<p id="p11688122119212"><a name="p11688122119212"></a><a name="p11688122119212"></a>Creates a <a href="huaweimapooptions.md">HuaweiMapOptions</a> object based on a custom attribute file.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table5102mcpsimp"></a>
<table><thead align="left"><tr id="row5107mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p5109mcpsimp"><a name="p5109mcpsimp"></a><a name="p5109mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p5111mcpsimp"><a name="p5111mcpsimp"></a><a name="p5111mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row5112mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p5114mcpsimp"><a name="p5114mcpsimp"></a><a name="p5114mcpsimp"></a>context</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p5116mcpsimp"><a name="p5116mcpsimp"></a><a name="p5116mcpsimp"></a>Context.</p>
</td>
</tr>
<tr id="row5117mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p5119mcpsimp"><a name="p5119mcpsimp"></a><a name="p5119mcpsimp"></a>attrs</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p5121mcpsimp"><a name="p5121mcpsimp"></a><a name="p5121mcpsimp"></a>Attribute file directory.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table5124mcpsimp"></a>
<table><thead align="left"><tr id="row5129mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p5131mcpsimp"><a name="p5131mcpsimp"></a><a name="p5131mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p5133mcpsimp"><a name="p5133mcpsimp"></a><a name="p5133mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row5134mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p5136mcpsimp"><a name="p5136mcpsimp"></a><a name="p5136mcpsimp"></a><a href="huaweimapooptions.md">HuaweiMapOptions</a></p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p5138mcpsimp"><a name="p5138mcpsimp"></a><a name="p5138mcpsimp"></a><strong id="b071101124818"><a name="b071101124818"></a><a name="b071101124818"></a>HuaweiMapOptions</strong> object.</p>
</td>
</tr>
</tbody>
</table>

## getCamera<a name="section810020521830"></a>

<a name="table5174mcpsimp"></a>
<table><thead align="left"><tr id="row5178mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p5180mcpsimp"><a name="p5180mcpsimp"></a><a name="p5180mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row5181mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p5183mcpsimp"><a name="p5183mcpsimp"></a><a name="p5183mcpsimp"></a>public <a href="cameraposition.md">CameraPosition</a> getCamera()</p>
<p id="p6825543410"><a name="p6825543410"></a><a name="p6825543410"></a>Obtains the current configuration of the camera.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table5192mcpsimp"></a>
<table><thead align="left"><tr id="row5197mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p5199mcpsimp"><a name="p5199mcpsimp"></a><a name="p5199mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p5201mcpsimp"><a name="p5201mcpsimp"></a><a name="p5201mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row5202mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p5204mcpsimp"><a name="p5204mcpsimp"></a><a name="p5204mcpsimp"></a><a href="cameraposition.md">CameraPosition</a></p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p5206mcpsimp"><a name="p5206mcpsimp"></a><a name="p5206mcpsimp"></a>Camera configuration.</p>
</td>
</tr>
</tbody>
</table>

## getCompassEnabled<a name="section1694714242410"></a>

<a name="table5208mcpsimp"></a>
<table><thead align="left"><tr id="row5212mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p5214mcpsimp"><a name="p5214mcpsimp"></a><a name="p5214mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row5215mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p5217mcpsimp"><a name="p5217mcpsimp"></a><a name="p5217mcpsimp"></a>public Boolean getCompassEnabled()</p>
<p id="p1926211421140"><a name="p1926211421140"></a><a name="p1926211421140"></a>Checks whether the compass is enabled for a map.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table5226mcpsimp"></a>
<table><thead align="left"><tr id="row5231mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p5233mcpsimp"><a name="p5233mcpsimp"></a><a name="p5233mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p5235mcpsimp"><a name="p5235mcpsimp"></a><a name="p5235mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row5236mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p5238mcpsimp"><a name="p5238mcpsimp"></a><a name="p5238mcpsimp"></a>Boolean</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p5240mcpsimp"><a name="p5240mcpsimp"></a><a name="p5240mcpsimp"></a><strong id="b1096919122493"><a name="b1096919122493"></a><a name="b1096919122493"></a>true</strong> if the compass is enabled; <strong id="b1423520254913"><a name="b1423520254913"></a><a name="b1423520254913"></a>false</strong> otherwise. The default value is <strong id="b1482707121818"><a name="b1482707121818"></a><a name="b1482707121818"></a>true</strong>.</p>
</td>
</tr>
</tbody>
</table>

## getLatLngBoundsForCameraTarget<a name="section4666175815418"></a>

<a name="table5242mcpsimp"></a>
<table><thead align="left"><tr id="row5246mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p5248mcpsimp"><a name="p5248mcpsimp"></a><a name="p5248mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row5249mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p5251mcpsimp"><a name="p5251mcpsimp"></a><a name="p5251mcpsimp"></a>public <a href="latlngbounds.md">LatLngBounds</a> getLatLngBoundsForCameraTarget()</p>
<p id="p997214151858"><a name="p997214151858"></a><a name="p997214151858"></a>Obtains the bounds for constraining the camera target. If the bounds are not specified, <strong id="b0790155174915"><a name="b0790155174915"></a><a name="b0790155174915"></a>null</strong> will be returned.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table5260mcpsimp"></a>
<table><thead align="left"><tr id="row5265mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p5267mcpsimp"><a name="p5267mcpsimp"></a><a name="p5267mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p5269mcpsimp"><a name="p5269mcpsimp"></a><a name="p5269mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row5270mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p5272mcpsimp"><a name="p5272mcpsimp"></a><a name="p5272mcpsimp"></a><a href="latlngbounds.md">LatLngBounds</a></p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p5274mcpsimp"><a name="p5274mcpsimp"></a><a name="p5274mcpsimp"></a>Bounds for constraining the camera target.</p>
</td>
</tr>
</tbody>
</table>

## getLiteMode<a name="section141801147759"></a>

<a name="table5276mcpsimp"></a>
<table><thead align="left"><tr id="row5280mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p5282mcpsimp"><a name="p5282mcpsimp"></a><a name="p5282mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row5283mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p5285mcpsimp"><a name="p5285mcpsimp"></a><a name="p5285mcpsimp"></a>public Boolean getLiteMode()</p>
<p id="p158132062612"><a name="p158132062612"></a><a name="p158132062612"></a>Checks whether the lite mode is enabled for a map.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table5294mcpsimp"></a>
<table><thead align="left"><tr id="row5299mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p5301mcpsimp"><a name="p5301mcpsimp"></a><a name="p5301mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p5303mcpsimp"><a name="p5303mcpsimp"></a><a name="p5303mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row5304mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p5306mcpsimp"><a name="p5306mcpsimp"></a><a name="p5306mcpsimp"></a>Boolean</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p5308mcpsimp"><a name="p5308mcpsimp"></a><a name="p5308mcpsimp"></a><strong id="b0575192714501"><a name="b0575192714501"></a><a name="b0575192714501"></a>true</strong> if the lite mode is enabled; <strong id="b12580182715018"><a name="b12580182715018"></a><a name="b12580182715018"></a>false</strong> otherwise. The default value is <strong id="b823723912182"><a name="b823723912182"></a><a name="b823723912182"></a>false</strong>.</p>
</td>
</tr>
</tbody>
</table>

## getMapType<a name="section12521027168"></a>

<a name="table5310mcpsimp"></a>
<table><thead align="left"><tr id="row5314mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p5316mcpsimp"><a name="p5316mcpsimp"></a><a name="p5316mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row5317mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p5319mcpsimp"><a name="p5319mcpsimp"></a><a name="p5319mcpsimp"></a>public int getMapType()</p>
<p id="p5322mcpsimp"><a name="p5322mcpsimp"></a><a name="p5322mcpsimp"></a>Obtains the current map type.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table5328mcpsimp"></a>
<table><thead align="left"><tr id="row5333mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p5335mcpsimp"><a name="p5335mcpsimp"></a><a name="p5335mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p5337mcpsimp"><a name="p5337mcpsimp"></a><a name="p5337mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row5338mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p5340mcpsimp"><a name="p5340mcpsimp"></a><a name="p5340mcpsimp"></a>int</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p5342mcpsimp"><a name="p5342mcpsimp"></a><a name="p5342mcpsimp"></a>Map type. If the map type is not specified, <strong id="b2759162092518"><a name="b2759162092518"></a><a name="b2759162092518"></a>-1</strong> will be returned.</p>
</td>
</tr>
</tbody>
</table>

## getMaxZoomPreference<a name="section78861111672"></a>

<a name="table5344mcpsimp"></a>
<table><thead align="left"><tr id="row5348mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p5350mcpsimp"><a name="p5350mcpsimp"></a><a name="p5350mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row5351mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p5353mcpsimp"><a name="p5353mcpsimp"></a><a name="p5353mcpsimp"></a>public Float getMaxZoomPreference()</p>
<p id="p899713261371"><a name="p899713261371"></a><a name="p899713261371"></a>Obtains the preferred maximum zoom level of a map.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table5362mcpsimp"></a>
<table><thead align="left"><tr id="row5367mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p5369mcpsimp"><a name="p5369mcpsimp"></a><a name="p5369mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p5371mcpsimp"><a name="p5371mcpsimp"></a><a name="p5371mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row5372mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p5374mcpsimp"><a name="p5374mcpsimp"></a><a name="p5374mcpsimp"></a>Float</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p5376mcpsimp"><a name="p5376mcpsimp"></a><a name="p5376mcpsimp"></a>Preferred maximum zoom level. The default value is <strong id="b195671058161812"><a name="b195671058161812"></a><a name="b195671058161812"></a>20</strong>.</p>
</td>
</tr>
</tbody>
</table>

## getMinZoomPreference<a name="section10719165715713"></a>

<a name="table5378mcpsimp"></a>
<table><thead align="left"><tr id="row5382mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p5384mcpsimp"><a name="p5384mcpsimp"></a><a name="p5384mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row5385mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p5387mcpsimp"><a name="p5387mcpsimp"></a><a name="p5387mcpsimp"></a>public Float getMinZoomPreference()</p>
<p id="p7596101911813"><a name="p7596101911813"></a><a name="p7596101911813"></a>Obtains the preferred minimum zoom level of a map.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table5396mcpsimp"></a>
<table><thead align="left"><tr id="row5401mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p5403mcpsimp"><a name="p5403mcpsimp"></a><a name="p5403mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p5405mcpsimp"><a name="p5405mcpsimp"></a><a name="p5405mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row5406mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p5408mcpsimp"><a name="p5408mcpsimp"></a><a name="p5408mcpsimp"></a>Float</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p5410mcpsimp"><a name="p5410mcpsimp"></a><a name="p5410mcpsimp"></a>Minimum preferred zoom level. The default value is <strong id="b137561454198"><a name="b137561454198"></a><a name="b137561454198"></a>3</strong>.</p>
</td>
</tr>
</tbody>
</table>

## getRotateGesturesEnabled<a name="section16773144116814"></a>

<a name="table5412mcpsimp"></a>
<table><thead align="left"><tr id="row5416mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p5418mcpsimp"><a name="p5418mcpsimp"></a><a name="p5418mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row5419mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p5421mcpsimp"><a name="p5421mcpsimp"></a><a name="p5421mcpsimp"></a>public Boolean getRotateGesturesEnabled()</p>
<p id="p5424mcpsimp"><a name="p5424mcpsimp"></a><a name="p5424mcpsimp"></a>Checks whether rotation gestures are enabled for a map.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table5430mcpsimp"></a>
<table><thead align="left"><tr id="row5435mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p5437mcpsimp"><a name="p5437mcpsimp"></a><a name="p5437mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p5439mcpsimp"><a name="p5439mcpsimp"></a><a name="p5439mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row5440mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p5442mcpsimp"><a name="p5442mcpsimp"></a><a name="p5442mcpsimp"></a>Boolean</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p5444mcpsimp"><a name="p5444mcpsimp"></a><a name="p5444mcpsimp"></a><strong id="b8120155324518"><a name="b8120155324518"></a><a name="b8120155324518"></a>true</strong> if the rotation gestures are enabled for a map; <strong id="b1054215911466"><a name="b1054215911466"></a><a name="b1054215911466"></a>false</strong> otherwise.</p>
</td>
</tr>
</tbody>
</table>

## getScrollGesturesEnabled<a name="section446415211395"></a>

<a name="table5446mcpsimp"></a>
<table><thead align="left"><tr id="row5450mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p5452mcpsimp"><a name="p5452mcpsimp"></a><a name="p5452mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row5453mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p5455mcpsimp"><a name="p5455mcpsimp"></a><a name="p5455mcpsimp"></a>public Boolean getScrollGesturesEnabled()</p>
<p id="p157471734497"><a name="p157471734497"></a><a name="p157471734497"></a>Checks whether scroll gestures are enabled for a map.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table5464mcpsimp"></a>
<table><thead align="left"><tr id="row5469mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p5471mcpsimp"><a name="p5471mcpsimp"></a><a name="p5471mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p5473mcpsimp"><a name="p5473mcpsimp"></a><a name="p5473mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row5474mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p5476mcpsimp"><a name="p5476mcpsimp"></a><a name="p5476mcpsimp"></a>Boolean</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p5478mcpsimp"><a name="p5478mcpsimp"></a><a name="p5478mcpsimp"></a><strong id="b2075964794613"><a name="b2075964794613"></a><a name="b2075964794613"></a>true</strong> if the scroll gestures are enabled for a map; <strong id="b10658193154715"><a name="b10658193154715"></a><a name="b10658193154715"></a>false</strong> otherwise.</p>
</td>
</tr>
</tbody>
</table>

## getTiltGesturesEnabled<a name="section072675119915"></a>

<a name="table5480mcpsimp"></a>
<table><thead align="left"><tr id="row5484mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p5486mcpsimp"><a name="p5486mcpsimp"></a><a name="p5486mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row5487mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p5489mcpsimp"><a name="p5489mcpsimp"></a><a name="p5489mcpsimp"></a>public Boolean getTiltGesturesEnabled()</p>
<p id="p5492mcpsimp"><a name="p5492mcpsimp"></a><a name="p5492mcpsimp"></a>Checks whether tilt gestures are enabled for a map.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table5498mcpsimp"></a>
<table><thead align="left"><tr id="row5503mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p5505mcpsimp"><a name="p5505mcpsimp"></a><a name="p5505mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p5507mcpsimp"><a name="p5507mcpsimp"></a><a name="p5507mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row5508mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p5510mcpsimp"><a name="p5510mcpsimp"></a><a name="p5510mcpsimp"></a>Boolean</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p5512mcpsimp"><a name="p5512mcpsimp"></a><a name="p5512mcpsimp"></a><strong id="b1765764144818"><a name="b1765764144818"></a><a name="b1765764144818"></a>true</strong> if the tilt gestures are enabled for a map; <strong id="b1543591824811"><a name="b1543591824811"></a><a name="b1543591824811"></a>false</strong> otherwise.</p>
</td>
</tr>
</tbody>
</table>

## getUseViewLifecycleInFragment<a name="section0818164121012"></a>

<a name="table5514mcpsimp"></a>
<table><thead align="left"><tr id="row5518mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p5520mcpsimp"><a name="p5520mcpsimp"></a><a name="p5520mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row5521mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p5523mcpsimp"><a name="p5523mcpsimp"></a><a name="p5523mcpsimp"></a>public Boolean getUseViewLifecycleInFragment()</p>
<p id="p4423175781012"><a name="p4423175781012"></a><a name="p4423175781012"></a>Checks whether the lifecycle of a map is bound to the view of <a href="mapfragment.md">MapFragment</a> or to <a href="mapfragment.md">MapFragment</a> itself when <a href="mapfragment.md">MapFragment</a> is used. If the binding relationship is not specified, no value will be returned.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table5532mcpsimp"></a>
<table><thead align="left"><tr id="row5537mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p5539mcpsimp"><a name="p5539mcpsimp"></a><a name="p5539mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p5541mcpsimp"><a name="p5541mcpsimp"></a><a name="p5541mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row5542mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p5544mcpsimp"><a name="p5544mcpsimp"></a><a name="p5544mcpsimp"></a>Boolean</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p5546mcpsimp"><a name="p5546mcpsimp"></a><a name="p5546mcpsimp"></a><strong id="b291516617554"><a name="b291516617554"></a><a name="b291516617554"></a>true</strong> if the lifecycle of a map is bound to the view of <a href="mapfragment.md">MapFragment</a>; <strong id="b3736105175718"><a name="b3736105175718"></a><a name="b3736105175718"></a>false</strong> if the lifecycle of a map is bound to <a href="mapfragment.md">MapFragment</a> itself.</p>
</td>
</tr>
</tbody>
</table>

## getZOrderOnTop<a name="section2011561881120"></a>

<a name="table5548mcpsimp"></a>
<table><thead align="left"><tr id="row5552mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p5554mcpsimp"><a name="p5554mcpsimp"></a><a name="p5554mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row5555mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p5557mcpsimp"><a name="p5557mcpsimp"></a><a name="p5557mcpsimp"></a>public Boolean getZOrderOnTop()</p>
<p id="p5560mcpsimp"><a name="p5560mcpsimp"></a><a name="p5560mcpsimp"></a>Checks whether the surface of a map view is placed on top of its window. If the place order is not specified, no value will be returned.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table5566mcpsimp"></a>
<table><thead align="left"><tr id="row5571mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p5573mcpsimp"><a name="p5573mcpsimp"></a><a name="p5573mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p5575mcpsimp"><a name="p5575mcpsimp"></a><a name="p5575mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row5576mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p5578mcpsimp"><a name="p5578mcpsimp"></a><a name="p5578mcpsimp"></a>Boolean</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p5580mcpsimp"><a name="p5580mcpsimp"></a><a name="p5580mcpsimp"></a><strong id="b1292041610590"><a name="b1292041610590"></a><a name="b1292041610590"></a>true</strong> if the surface of a map view is placed on top of its window; <strong id="b119157112592"><a name="b119157112592"></a><a name="b119157112592"></a>false</strong> otherwise.</p>
</td>
</tr>
</tbody>
</table>

## getZoomControlsEnabled<a name="section15687165511118"></a>

<a name="table5582mcpsimp"></a>
<table><thead align="left"><tr id="row5586mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p5588mcpsimp"><a name="p5588mcpsimp"></a><a name="p5588mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row5589mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p5591mcpsimp"><a name="p5591mcpsimp"></a><a name="p5591mcpsimp"></a>public Boolean getZoomControlsEnabled()</p>
<p id="p935911931220"><a name="p935911931220"></a><a name="p935911931220"></a>Checks whether the zoom function is enabled for a map.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table5600mcpsimp"></a>
<table><thead align="left"><tr id="row5605mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p5607mcpsimp"><a name="p5607mcpsimp"></a><a name="p5607mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p5609mcpsimp"><a name="p5609mcpsimp"></a><a name="p5609mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row5610mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p5612mcpsimp"><a name="p5612mcpsimp"></a><a name="p5612mcpsimp"></a>Boolean</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p5614mcpsimp"><a name="p5614mcpsimp"></a><a name="p5614mcpsimp"></a><strong id="b166691991500"><a name="b166691991500"></a><a name="b166691991500"></a>true</strong> if the zoom function is enabled; <strong id="b10671145875916"><a name="b10671145875916"></a><a name="b10671145875916"></a>false</strong> otherwise.</p>
</td>
</tr>
</tbody>
</table>

## getZoomGesturesEnabled<a name="section202671951161310"></a>

<a name="table5664mcpsimp"></a>
<table><thead align="left"><tr id="row5668mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p5670mcpsimp"><a name="p5670mcpsimp"></a><a name="p5670mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row5671mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p5673mcpsimp"><a name="p5673mcpsimp"></a><a name="p5673mcpsimp"></a>public Boolean getZoomGesturesEnabled()</p>
<p id="p5676mcpsimp"><a name="p5676mcpsimp"></a><a name="p5676mcpsimp"></a>Checks whether zoom gestures are enabled for a map.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table5682mcpsimp"></a>
<table><thead align="left"><tr id="row5687mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p5689mcpsimp"><a name="p5689mcpsimp"></a><a name="p5689mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p5691mcpsimp"><a name="p5691mcpsimp"></a><a name="p5691mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row5692mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p5694mcpsimp"><a name="p5694mcpsimp"></a><a name="p5694mcpsimp"></a>Boolean</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p5696mcpsimp"><a name="p5696mcpsimp"></a><a name="p5696mcpsimp"></a><strong id="b1273320371111"><a name="b1273320371111"></a><a name="b1273320371111"></a>true</strong> if zoom gestures are enabled for a map; <strong id="b73294420120"><a name="b73294420120"></a><a name="b73294420120"></a>false</strong> otherwise. </p>
</td>
</tr>
</tbody>
</table>

## latLngBoundsForCameraTarget<a name="section1394012719138"></a>

<a name="table5616mcpsimp"></a>
<table><thead align="left"><tr id="row5620mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p5622mcpsimp"><a name="p5622mcpsimp"></a><a name="p5622mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row5623mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p5625mcpsimp"><a name="p5625mcpsimp"></a><a name="p5625mcpsimp"></a>public <a href="huaweimapooptions.md">HuaweiMapOptions</a> latLngBoundsForCameraTarget(<a href="latlngbounds.md">LatLngBounds</a> latLngBounds)</p>
<p id="p5628mcpsimp"><a name="p5628mcpsimp"></a><a name="p5628mcpsimp"></a>Sets a <a href="latlngbounds.md">LatLngBounds</a> object to constrain the camera target so that the camera target does not move outside the bounds when a user scrolls the map.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table5631mcpsimp"></a>
<table><thead align="left"><tr id="row5636mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p5638mcpsimp"><a name="p5638mcpsimp"></a><a name="p5638mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p5640mcpsimp"><a name="p5640mcpsimp"></a><a name="p5640mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row5641mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p5643mcpsimp"><a name="p5643mcpsimp"></a><a name="p5643mcpsimp"></a>latLngBounds</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p5645mcpsimp"><a name="p5645mcpsimp"></a><a name="p5645mcpsimp"></a>Bounds for constraining the camera target.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table5648mcpsimp"></a>
<table><thead align="left"><tr id="row5653mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p5655mcpsimp"><a name="p5655mcpsimp"></a><a name="p5655mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p5657mcpsimp"><a name="p5657mcpsimp"></a><a name="p5657mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row5658mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p5660mcpsimp"><a name="p5660mcpsimp"></a><a name="p5660mcpsimp"></a><a href="huaweimapooptions.md">HuaweiMapOptions</a></p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p5662mcpsimp"><a name="p5662mcpsimp"></a><a name="p5662mcpsimp"></a><strong id="b18274145913020"><a name="b18274145913020"></a><a name="b18274145913020"></a>HuaweiMapOptions</strong> object.</p>
</td>
</tr>
</tbody>
</table>

## liteMode<a name="section29491334161413"></a>

<a name="table5698mcpsimp"></a>
<table><thead align="left"><tr id="row5702mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p5704mcpsimp"><a name="p5704mcpsimp"></a><a name="p5704mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row5705mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p5707mcpsimp"><a name="p5707mcpsimp"></a><a name="p5707mcpsimp"></a>public <a href="huaweimapooptions.md">HuaweiMapOptions</a> liteMode(boolean isLiteMode)</p>
<p id="p5710mcpsimp"><a name="p5710mcpsimp"></a><a name="p5710mcpsimp"></a>Sets whether to create a map in lite mode.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table5713mcpsimp"></a>
<table><thead align="left"><tr id="row5718mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p5720mcpsimp"><a name="p5720mcpsimp"></a><a name="p5720mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p5722mcpsimp"><a name="p5722mcpsimp"></a><a name="p5722mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row5723mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p5725mcpsimp"><a name="p5725mcpsimp"></a><a name="p5725mcpsimp"></a>isLiteMode</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p5727mcpsimp"><a name="p5727mcpsimp"></a><a name="p5727mcpsimp"></a><strong id="b2591651174814"><a name="b2591651174814"></a><a name="b2591651174814"></a>true</strong> if the map is created in lite mode; <strong id="b165927514487"><a name="b165927514487"></a><a name="b165927514487"></a>false</strong> otherwise. </p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table5730mcpsimp"></a>
<table><thead align="left"><tr id="row5735mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p5737mcpsimp"><a name="p5737mcpsimp"></a><a name="p5737mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p5739mcpsimp"><a name="p5739mcpsimp"></a><a name="p5739mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row5740mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p5742mcpsimp"><a name="p5742mcpsimp"></a><a name="p5742mcpsimp"></a><a href="huaweimapooptions.md">HuaweiMapOptions</a></p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p5744mcpsimp"><a name="p5744mcpsimp"></a><a name="p5744mcpsimp"></a><strong id="b524101617211"><a name="b524101617211"></a><a name="b524101617211"></a>HuaweiMapOptions</strong> object.</p>
</td>
</tr>
</tbody>
</table>

## mapType<a name="section2485024181514"></a>

<a name="table5746mcpsimp"></a>
<table><thead align="left"><tr id="row5750mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p5752mcpsimp"><a name="p5752mcpsimp"></a><a name="p5752mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row5753mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p5755mcpsimp"><a name="p5755mcpsimp"></a><a name="p5755mcpsimp"></a>public <a href="huaweimapooptions.md">HuaweiMapOptions</a> mapType(int mapType)</p>
<p id="p1669253912154"><a name="p1669253912154"></a><a name="p1669253912154"></a>Sets the Huawei map type. The options are <a href="huaweimap.md#section1020623124910">HuaweiMap.MAP_TYPE_NORMAL</a> and <a href="huaweimap.md#section19250192319483">HuaweiMap.MAP_TYPE_NONE</a>. If the map type is not specified, the value <strong id="b149121216191820"><a name="b149121216191820"></a><a name="b149121216191820"></a>-1</strong> will be passed to this method. </p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table5761mcpsimp"></a>
<table><thead align="left"><tr id="row5766mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p5768mcpsimp"><a name="p5768mcpsimp"></a><a name="p5768mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p5770mcpsimp"><a name="p5770mcpsimp"></a><a name="p5770mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row5771mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p5773mcpsimp"><a name="p5773mcpsimp"></a><a name="p5773mcpsimp"></a>mapType</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p5775mcpsimp"><a name="p5775mcpsimp"></a><a name="p5775mcpsimp"></a>Map type.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table5778mcpsimp"></a>
<table><thead align="left"><tr id="row5783mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p5785mcpsimp"><a name="p5785mcpsimp"></a><a name="p5785mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p5787mcpsimp"><a name="p5787mcpsimp"></a><a name="p5787mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row5788mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p5790mcpsimp"><a name="p5790mcpsimp"></a><a name="p5790mcpsimp"></a><a href="huaweimapooptions.md">HuaweiMapOptions</a></p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p5792mcpsimp"><a name="p5792mcpsimp"></a><a name="p5792mcpsimp"></a><strong id="b18365741637"><a name="b18365741637"></a><a name="b18365741637"></a>HuaweiMapOptions</strong> object.</p>
</td>
</tr>
</tbody>
</table>

## maxZoomPreference<a name="section88791059160"></a>

<a name="table5794mcpsimp"></a>
<table><thead align="left"><tr id="row5798mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p5800mcpsimp"><a name="p5800mcpsimp"></a><a name="p5800mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row5801mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p5803mcpsimp"><a name="p5803mcpsimp"></a><a name="p5803mcpsimp"></a>public <a href="huaweimapooptions.md">HuaweiMapOptions</a> maxZoomPreference(float maxZoomLevel)</p>
<p id="p722482421619"><a name="p722482421619"></a><a name="p722482421619"></a>Sets the preferred maximum zoom level of the camera. </p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table5809mcpsimp"></a>
<table><thead align="left"><tr id="row5814mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p5816mcpsimp"><a name="p5816mcpsimp"></a><a name="p5816mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p5818mcpsimp"><a name="p5818mcpsimp"></a><a name="p5818mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row5819mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p5821mcpsimp"><a name="p5821mcpsimp"></a><a name="p5821mcpsimp"></a>maxZoomLevel</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p5823mcpsimp"><a name="p5823mcpsimp"></a><a name="p5823mcpsimp"></a>Preferred maximum zoom level.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table5826mcpsimp"></a>
<table><thead align="left"><tr id="row5831mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p5833mcpsimp"><a name="p5833mcpsimp"></a><a name="p5833mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p5835mcpsimp"><a name="p5835mcpsimp"></a><a name="p5835mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row5836mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p5838mcpsimp"><a name="p5838mcpsimp"></a><a name="p5838mcpsimp"></a><a href="huaweimapooptions.md">HuaweiMapOptions</a></p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p5840mcpsimp"><a name="p5840mcpsimp"></a><a name="p5840mcpsimp"></a><strong id="b199918200415"><a name="b199918200415"></a><a name="b199918200415"></a>HuaweiMapOptions</strong> object.</p>
</td>
</tr>
</tbody>
</table>

## minZoomPreference<a name="section1616415503161"></a>

<a name="table5842mcpsimp"></a>
<table><thead align="left"><tr id="row5846mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p5848mcpsimp"><a name="p5848mcpsimp"></a><a name="p5848mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row5849mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p5851mcpsimp"><a name="p5851mcpsimp"></a><a name="p5851mcpsimp"></a>public <a href="huaweimapooptions.md">HuaweiMapOptions</a> minZoomPreference(float minZoomLevel)</p>
<p id="p5854mcpsimp"><a name="p5854mcpsimp"></a><a name="p5854mcpsimp"></a>Sets the preferred minimum zoom level of the camera.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table5857mcpsimp"></a>
<table><thead align="left"><tr id="row5862mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p5864mcpsimp"><a name="p5864mcpsimp"></a><a name="p5864mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p5866mcpsimp"><a name="p5866mcpsimp"></a><a name="p5866mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row5867mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p5869mcpsimp"><a name="p5869mcpsimp"></a><a name="p5869mcpsimp"></a>minZoomLevel</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p5871mcpsimp"><a name="p5871mcpsimp"></a><a name="p5871mcpsimp"></a>Preferred minimum zoom level.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table5874mcpsimp"></a>
<table><thead align="left"><tr id="row5879mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p5881mcpsimp"><a name="p5881mcpsimp"></a><a name="p5881mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p5883mcpsimp"><a name="p5883mcpsimp"></a><a name="p5883mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row5884mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p5886mcpsimp"><a name="p5886mcpsimp"></a><a name="p5886mcpsimp"></a><a href="huaweimapooptions.md">HuaweiMapOptions</a></p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p5888mcpsimp"><a name="p5888mcpsimp"></a><a name="p5888mcpsimp"></a><strong id="b169395331041"><a name="b169395331041"></a><a name="b169395331041"></a>HuaweiMapOptions</strong> object.</p>
</td>
</tr>
</tbody>
</table>

## rotateGesturesEnabled<a name="section65033374179"></a>

<a name="table5890mcpsimp"></a>
<table><thead align="left"><tr id="row5894mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p5896mcpsimp"><a name="p5896mcpsimp"></a><a name="p5896mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row5897mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p5899mcpsimp"><a name="p5899mcpsimp"></a><a name="p5899mcpsimp"></a>public <a href="huaweimapooptions.md">HuaweiMapOptions</a> rotateGesturesEnabled(boolean isRotateGesturesEnabled)</p>
<p id="p18856448201714"><a name="p18856448201714"></a><a name="p18856448201714"></a>Sets whether to enable rotation gestures for a map. By default, rotation gestures are enabled.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table5905mcpsimp"></a>
<table><thead align="left"><tr id="row5910mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p5912mcpsimp"><a name="p5912mcpsimp"></a><a name="p5912mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p5914mcpsimp"><a name="p5914mcpsimp"></a><a name="p5914mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row5915mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p5917mcpsimp"><a name="p5917mcpsimp"></a><a name="p5917mcpsimp"></a>isRotateGesturesEnabled</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p5919mcpsimp"><a name="p5919mcpsimp"></a><a name="p5919mcpsimp"></a>Indicates whether to enable rotation gestures. <strong id="b134821441746"><a name="b134821441746"></a><a name="b134821441746"></a>true</strong> (default): yes; <strong id="b648812441417"><a name="b648812441417"></a><a name="b648812441417"></a>false</strong>: no. </p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table5922mcpsimp"></a>
<table><thead align="left"><tr id="row5927mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p5929mcpsimp"><a name="p5929mcpsimp"></a><a name="p5929mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p5931mcpsimp"><a name="p5931mcpsimp"></a><a name="p5931mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row5932mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p5934mcpsimp"><a name="p5934mcpsimp"></a><a name="p5934mcpsimp"></a>HuaweiMapOptions</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p5936mcpsimp"><a name="p5936mcpsimp"></a><a name="p5936mcpsimp"></a><strong id="b15145171612519"><a name="b15145171612519"></a><a name="b15145171612519"></a>HuaweiMapOptions</strong> object.</p>
</td>
</tr>
</tbody>
</table>

## scrollGesturesEnabled<a name="section2094318183189"></a>

<a name="table5938mcpsimp"></a>
<table><thead align="left"><tr id="row5942mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p5944mcpsimp"><a name="p5944mcpsimp"></a><a name="p5944mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row5945mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p5947mcpsimp"><a name="p5947mcpsimp"></a><a name="p5947mcpsimp"></a>public <a href="huaweimapooptions.md">HuaweiMapOptions</a> scrollGesturesEnabled(boolean isScrollGesturesEnabled)</p>
<p id="p5950mcpsimp"><a name="p5950mcpsimp"></a><a name="p5950mcpsimp"></a>Sets whether to enable scroll gestures for a map. By default, scroll gestures are enabled.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table5953mcpsimp"></a>
<table><thead align="left"><tr id="row5958mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p5960mcpsimp"><a name="p5960mcpsimp"></a><a name="p5960mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p5962mcpsimp"><a name="p5962mcpsimp"></a><a name="p5962mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row5963mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p5965mcpsimp"><a name="p5965mcpsimp"></a><a name="p5965mcpsimp"></a>isScrollGesturesEnabled</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p5967mcpsimp"><a name="p5967mcpsimp"></a><a name="p5967mcpsimp"></a>Indicates whether to enable scroll gestures. <strong id="b1757522919519"><a name="b1757522919519"></a><a name="b1757522919519"></a>true</strong> (default): yes; <strong id="b195764291552"><a name="b195764291552"></a><a name="b195764291552"></a>false</strong>: no. </p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table5970mcpsimp"></a>
<table><thead align="left"><tr id="row5975mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p5977mcpsimp"><a name="p5977mcpsimp"></a><a name="p5977mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p5979mcpsimp"><a name="p5979mcpsimp"></a><a name="p5979mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row5980mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p5982mcpsimp"><a name="p5982mcpsimp"></a><a name="p5982mcpsimp"></a><a href="huaweimapooptions.md">HuaweiMapOptions</a></p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p5984mcpsimp"><a name="p5984mcpsimp"></a><a name="p5984mcpsimp"></a><strong id="b14725634452"><a name="b14725634452"></a><a name="b14725634452"></a>HuaweiMapOptions</strong> object.</p>
</td>
</tr>
</tbody>
</table>

## tiltGesturesEnabled<a name="section1469615401913"></a>

<a name="table5986mcpsimp"></a>
<table><thead align="left"><tr id="row5990mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p5992mcpsimp"><a name="p5992mcpsimp"></a><a name="p5992mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row5993mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p5995mcpsimp"><a name="p5995mcpsimp"></a><a name="p5995mcpsimp"></a>public <a href="huaweimapooptions.md">HuaweiMapOptions</a> tiltGesturesEnabled(boolean isTiltGesturesEnabled)</p>
<p id="p5998mcpsimp"><a name="p5998mcpsimp"></a><a name="p5998mcpsimp"></a>Sets whether to enable tilt gestures for a map. By default, tilt gestures are enabled.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table6001mcpsimp"></a>
<table><thead align="left"><tr id="row6006mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p6008mcpsimp"><a name="p6008mcpsimp"></a><a name="p6008mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p6010mcpsimp"><a name="p6010mcpsimp"></a><a name="p6010mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row6011mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p6013mcpsimp"><a name="p6013mcpsimp"></a><a name="p6013mcpsimp"></a>isTiltGesturesEnabled</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p6015mcpsimp"><a name="p6015mcpsimp"></a><a name="p6015mcpsimp"></a>Indicates whether to enable tilt gestures. <strong id="b15182144619513"><a name="b15182144619513"></a><a name="b15182144619513"></a>true</strong> (default): yes; <strong id="b51821346358"><a name="b51821346358"></a><a name="b51821346358"></a>false</strong>: no. </p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table6018mcpsimp"></a>
<table><thead align="left"><tr id="row6023mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p6025mcpsimp"><a name="p6025mcpsimp"></a><a name="p6025mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p6027mcpsimp"><a name="p6027mcpsimp"></a><a name="p6027mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row6028mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p6030mcpsimp"><a name="p6030mcpsimp"></a><a name="p6030mcpsimp"></a><a href="huaweimapooptions.md">HuaweiMapOptions</a></p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p6032mcpsimp"><a name="p6032mcpsimp"></a><a name="p6032mcpsimp"></a><strong id="b776434716512"><a name="b776434716512"></a><a name="b776434716512"></a>HuaweiMapOptions</strong> object.</p>
</td>
</tr>
</tbody>
</table>

## useViewLifecycleInFragment<a name="section14526745191913"></a>

<a name="table6034mcpsimp"></a>
<table><thead align="left"><tr id="row6038mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p6040mcpsimp"><a name="p6040mcpsimp"></a><a name="p6040mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row6041mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p6043mcpsimp"><a name="p6043mcpsimp"></a><a name="p6043mcpsimp"></a>public <a href="huaweimapooptions.md">HuaweiMapOptions</a> useViewLifecycleInFragment(boolean isUseViewLifecycleInFragment)</p>
<p id="p6046mcpsimp"><a name="p6046mcpsimp"></a><a name="p6046mcpsimp"></a>Sets whether to bind the lifecycle of a map to the view of <a href="mapfragment.md">MapFragment</a> or to <a href="mapfragment.md">MapFragment</a> itself. By default, the map lifecycle is bound to <a href="mapfragment.md">MapFragment</a> itself. In this case, the map can be rendered more quickly when <a href="mapfragment.md">MapFragment</a> is detached and reattached. However, this has the cost that the memory used by the map will not be released when <a href="mapfragment.md">MapFragment</a> is detached but not destroyed. If the lifecycle of a map is bound to the view of <a href="mapfragment.md">MapFragment</a>, the map is not reused when <a href="mapfragment.md">MapFragment</a> is detached and reattached. As a result, the map needs to be re-rendered, which may take several seconds. In addition, when <a href="mapfragment.md">MapFragment</a> is detached, all methods in the <a href="huaweimap.md">HuaweiMap</a> class will throw <strong id="b24761226109"><a name="b24761226109"></a><a name="b24761226109"></a>NullPointerException</strong> because no view is available.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table6049mcpsimp"></a>
<table><thead align="left"><tr id="row6054mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p6056mcpsimp"><a name="p6056mcpsimp"></a><a name="p6056mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p6058mcpsimp"><a name="p6058mcpsimp"></a><a name="p6058mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row6059mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p6061mcpsimp"><a name="p6061mcpsimp"></a><a name="p6061mcpsimp"></a>isUseViewLifecycleInFragment</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p6063mcpsimp"><a name="p6063mcpsimp"></a><a name="p6063mcpsimp"></a>Indicates whether to bind the lifecycle of a map to the view of <a href="mapfragment.md">MapFragment</a> or to <a href="mapfragment.md">MapFragment</a> itself. <strong id="b947615711019"><a name="b947615711019"></a><a name="b947615711019"></a>true</strong>: to the view of <a href="mapfragment.md">MapFragment</a>; <strong id="b34821710107"><a name="b34821710107"></a><a name="b34821710107"></a>false</strong>: to <a href="mapfragment.md">MapFragment</a> itself.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table6066mcpsimp"></a>
<table><thead align="left"><tr id="row6071mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p6073mcpsimp"><a name="p6073mcpsimp"></a><a name="p6073mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p6075mcpsimp"><a name="p6075mcpsimp"></a><a name="p6075mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row6076mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p6078mcpsimp"><a name="p6078mcpsimp"></a><a name="p6078mcpsimp"></a><a href="huaweimapooptions.md">HuaweiMapOptions</a></p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p6080mcpsimp"><a name="p6080mcpsimp"></a><a name="p6080mcpsimp"></a><strong id="b91378128114"><a name="b91378128114"></a><a name="b91378128114"></a>HuaweiMapOptions</strong> object.</p>
</td>
</tr>
</tbody>
</table>

## zOrderOnTop<a name="section17532163552014"></a>

<a name="table6082mcpsimp"></a>
<table><thead align="left"><tr id="row6086mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p6088mcpsimp"><a name="p6088mcpsimp"></a><a name="p6088mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row6089mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p6091mcpsimp"><a name="p6091mcpsimp"></a><a name="p6091mcpsimp"></a>public <a href="huaweimapooptions.md">HuaweiMapOptions</a> zOrderOnTop(boolean zOrderOnTop)</p>
<p id="p6094mcpsimp"><a name="p6094mcpsimp"></a><a name="p6094mcpsimp"></a>Sets whether to place the surface of a map view on top of its window.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table6097mcpsimp"></a>
<table><thead align="left"><tr id="row6102mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p6104mcpsimp"><a name="p6104mcpsimp"></a><a name="p6104mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p6106mcpsimp"><a name="p6106mcpsimp"></a><a name="p6106mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row6107mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p6109mcpsimp"><a name="p6109mcpsimp"></a><a name="p6109mcpsimp"></a>zOrderOnTop</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p6111mcpsimp"><a name="p6111mcpsimp"></a><a name="p6111mcpsimp"></a>Indicates whether to place the surface of a map view on top of its window. <strong id="b134871937111119"><a name="b134871937111119"></a><a name="b134871937111119"></a>true</strong>: yes; <strong id="b10646143941112"><a name="b10646143941112"></a><a name="b10646143941112"></a>false</strong>: no. If this parameter is not set, no value is returned, and the effect is the same as that of <strong id="b1627011217597"><a name="b1627011217597"></a><a name="b1627011217597"></a>false</strong>.</p>
<div class="note" id="note8473627124019"><a name="note8473627124019"></a><a name="note8473627124019"></a><span class="notetitle"> NOTE: </span><div class="notebody"><p id="p34730277400"><a name="p34730277400"></a><a name="p34730277400"></a>This parameter cannot be set for map containers <strong id="b233031722313"><a name="b233031722313"></a><a name="b233031722313"></a>TextureMapView</strong>, <strong id="b366371814234"><a name="b366371814234"></a><a name="b366371814234"></a>TextureMapFragment</strong>, and <strong id="b13406162014237"><a name="b13406162014237"></a><a name="b13406162014237"></a>TextureSupportMapFragment</strong>.</p>
</div></div>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table6114mcpsimp"></a>
<table><thead align="left"><tr id="row6119mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p6121mcpsimp"><a name="p6121mcpsimp"></a><a name="p6121mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p6123mcpsimp"><a name="p6123mcpsimp"></a><a name="p6123mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row6124mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p6126mcpsimp"><a name="p6126mcpsimp"></a><a name="p6126mcpsimp"></a><a href="huaweimapooptions.md">HuaweiMapOptions</a></p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p6128mcpsimp"><a name="p6128mcpsimp"></a><a name="p6128mcpsimp"></a><strong id="b090524016113"><a name="b090524016113"></a><a name="b090524016113"></a>HuaweiMapOptions</strong> object.</p>
</td>
</tr>
</tbody>
</table>

## zoomControlsEnabled<a name="section937192082118"></a>

<a name="table6130mcpsimp"></a>
<table><thead align="left"><tr id="row6134mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p6136mcpsimp"><a name="p6136mcpsimp"></a><a name="p6136mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row6137mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p6139mcpsimp"><a name="p6139mcpsimp"></a><a name="p6139mcpsimp"></a>public <a href="huaweimapooptions.md">HuaweiMapOptions</a> zoomControlsEnabled(boolean isZoomControlsEnabled)</p>
<p id="p6142mcpsimp"><a name="p6142mcpsimp"></a><a name="p6142mcpsimp"></a>Sets whether to enable the zoom function for the camera. The zoom function is enabled by default.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table6145mcpsimp"></a>
<table><thead align="left"><tr id="row6150mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p6152mcpsimp"><a name="p6152mcpsimp"></a><a name="p6152mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p6154mcpsimp"><a name="p6154mcpsimp"></a><a name="p6154mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row6155mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p6157mcpsimp"><a name="p6157mcpsimp"></a><a name="p6157mcpsimp"></a>isZoomControlsEnabled</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p6159mcpsimp"><a name="p6159mcpsimp"></a><a name="p6159mcpsimp"></a>Indicates whether to enable the zoom function. <strong id="b184211811171211"><a name="b184211811171211"></a><a name="b184211811171211"></a>true</strong> (default): yes; <strong id="b44215119121"><a name="b44215119121"></a><a name="b44215119121"></a>false</strong>: no.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table6162mcpsimp"></a>
<table><thead align="left"><tr id="row6167mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p6169mcpsimp"><a name="p6169mcpsimp"></a><a name="p6169mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p6171mcpsimp"><a name="p6171mcpsimp"></a><a name="p6171mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row6172mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p6174mcpsimp"><a name="p6174mcpsimp"></a><a name="p6174mcpsimp"></a><a href="huaweimapooptions.md">HuaweiMapOptions</a></p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p6176mcpsimp"><a name="p6176mcpsimp"></a><a name="p6176mcpsimp"></a><strong id="b203761021161213"><a name="b203761021161213"></a><a name="b203761021161213"></a>HuaweiMapOptions</strong> object.</p>
</td>
</tr>
</tbody>
</table>

## zoomGesturesEnabled<a name="section67067692220"></a>

<a name="table6178mcpsimp"></a>
<table><thead align="left"><tr id="row6182mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p6184mcpsimp"><a name="p6184mcpsimp"></a><a name="p6184mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row6185mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p6187mcpsimp"><a name="p6187mcpsimp"></a><a name="p6187mcpsimp"></a>public <a href="huaweimapooptions.md">HuaweiMapOptions</a> zoomGesturesEnabled(boolean isZoomGesturesEnabled)</p>
<p id="p6190mcpsimp"><a name="p6190mcpsimp"></a><a name="p6190mcpsimp"></a>Sets whether to enable zoom gestures for a map. By default, zoom gestures are enabled.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table6193mcpsimp"></a>
<table><thead align="left"><tr id="row6198mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p6200mcpsimp"><a name="p6200mcpsimp"></a><a name="p6200mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p6202mcpsimp"><a name="p6202mcpsimp"></a><a name="p6202mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row6203mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p6205mcpsimp"><a name="p6205mcpsimp"></a><a name="p6205mcpsimp"></a>isZoomGesturesEnabled</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p6207mcpsimp"><a name="p6207mcpsimp"></a><a name="p6207mcpsimp"></a>Indicates whether to enable zoom gestures. <strong id="b12926488124"><a name="b12926488124"></a><a name="b12926488124"></a>true</strong> (default): yes; <strong id="b19292948121218"><a name="b19292948121218"></a><a name="b19292948121218"></a>false</strong>: no.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table6210mcpsimp"></a>
<table><thead align="left"><tr id="row6215mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p6217mcpsimp"><a name="p6217mcpsimp"></a><a name="p6217mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p6219mcpsimp"><a name="p6219mcpsimp"></a><a name="p6219mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row6220mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p6222mcpsimp"><a name="p6222mcpsimp"></a><a name="p6222mcpsimp"></a><a href="huaweimapooptions.md">HuaweiMapOptions</a></p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p6224mcpsimp"><a name="p6224mcpsimp"></a><a name="p6224mcpsimp"></a><strong id="b126675021210"><a name="b126675021210"></a><a name="b126675021210"></a>HuaweiMapOptions</strong> object.</p>
</td>
</tr>
</tbody>
</table>

