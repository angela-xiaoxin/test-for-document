# HWMarker<a name="EN-US_TOPIC_0000001099501040"></a>

-   [Overview](#se418145f214342159181f6aac75b1f4c)
-   [Build Method](#sf911422ee5b949dbb4181dfb7aeee73e)
-   [Public Methods](#s30dc7757feac40e38b61b95d237b6365)
-   [Events](#s96ebb83d37c2423aa1aa9f6caa44bf11)
-   [MarkerOptions](#s049098dea90d4152ad819e2e16099e38)
-   [MarkerIconOption](#sfbc5428e87a44deb9010cc2f3a589894)
-   [MarkerLabelOption](#sddf63bee876d44188dec2b7ccdfcaeb8)

## Overview<a name="se418145f214342159181f6aac75b1f4c"></a>

Adds markers to present elements loaded on a map layer on the map based on the preset rules. 

## Build Method<a name="sf911422ee5b949dbb4181dfb7aeee73e"></a>

<a name="t5e96ad3c40024296adec49eaa4288111"></a>
<table><thead align="left"><tr id="re8a132edb57c483e9126acba0c6a4a6a"><th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.1"><p id="ad9f715269cb14f4f9592061d5271c2d9"><a name="ad9f715269cb14f4f9592061d5271c2d9"></a><a name="ad9f715269cb14f4f9592061d5271c2d9"></a><strong id="aad932a3846e04d3a9b2441fd69465718"><a name="aad932a3846e04d3a9b2441fd69465718"></a><a name="aad932a3846e04d3a9b2441fd69465718"></a>Build Method</strong></p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.2"><p id="ac272b5922cf94072894ff461e8ba8bd5"><a name="ac272b5922cf94072894ff461e8ba8bd5"></a><a name="ac272b5922cf94072894ff461e8ba8bd5"></a><strong id="b19598912102215"><a name="b19598912102215"></a><a name="b19598912102215"></a>Description</strong></p>
</th>
</tr>
</thead>
<tbody><tr id="r5a85d5789a374dc980ab8465dd077c59"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="aef8804720265418f855605a671d50ae3"><a name="aef8804720265418f855605a671d50ae3"></a><a name="aef8804720265418f855605a671d50ae3"></a>HWMapJsSDK.HWMarker(markerOptions)</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="aeef4c39e04444ffb937267f71bec807c"><a name="aeef4c39e04444ffb937267f71bec807c"></a><a name="aeef4c39e04444ffb937267f71bec807c"></a>The <strong id="b15804213182214"><a name="b15804213182214"></a><a name="b15804213182214"></a>markerOptions</strong> parameter is used to set the marker attributes. For details, please refer to <a href="#s049098dea90d4152ad819e2e16099e38">MarkerOptions</a>.</p>
</td>
</tr>
</tbody>
</table>

## Public Methods<a name="s30dc7757feac40e38b61b95d237b6365"></a>

<a name="t9a3ca766234640619bf9acc4893efdbf"></a>
<table><thead align="left"><tr id="re2c904dc3ff3473aaf28f4644abc9628"><th class="cellrowborder" valign="top" width="32.01%" id="mcps1.1.5.1.1"><p id="a72bacd1ec5d34d68b0690a026b1f3ad5"><a name="a72bacd1ec5d34d68b0690a026b1f3ad5"></a><a name="a72bacd1ec5d34d68b0690a026b1f3ad5"></a><strong id="b6489826112218"><a name="b6489826112218"></a><a name="b6489826112218"></a>Method</strong></p>
</th>
<th class="cellrowborder" valign="top" width="26.99%" id="mcps1.1.5.1.2"><p id="a629d9640db254907a671998434eeae2f"><a name="a629d9640db254907a671998434eeae2f"></a><a name="a629d9640db254907a671998434eeae2f"></a><strong id="b3474428162212"><a name="b3474428162212"></a><a name="b3474428162212"></a>Description</strong></p>
</th>
<th class="cellrowborder" valign="top" width="27.82%" id="mcps1.1.5.1.3"><p id="a017f198a6de043c2951cda2f3bc2de1f"><a name="a017f198a6de043c2951cda2f3bc2de1f"></a><a name="a017f198a6de043c2951cda2f3bc2de1f"></a><strong id="a6949408f1852407fb31624cc35b7e0e2"><a name="a6949408f1852407fb31624cc35b7e0e2"></a><a name="a6949408f1852407fb31624cc35b7e0e2"></a>Type</strong></p>
</th>
<th class="cellrowborder" valign="top" width="13.18%" id="mcps1.1.5.1.4"><p id="ae4e4791471ce4b1c9a8eb2e3793e8009"><a name="ae4e4791471ce4b1c9a8eb2e3793e8009"></a><a name="ae4e4791471ce4b1c9a8eb2e3793e8009"></a><strong id="af96796e73b9547a59644d842001d738e"><a name="af96796e73b9547a59644d842001d738e"></a><a name="af96796e73b9547a59644d842001d738e"></a>Return Value</strong></p>
</th>
</tr>
</thead>
<tbody><tr id="r17d9cfc55e6946269f7fcf388efe0271"><td class="cellrowborder" valign="top" width="32.01%" headers="mcps1.1.5.1.1 "><p id="a8895f2dadaef427c8c50bb4bb2f11e02"><a name="a8895f2dadaef427c8c50bb4bb2f11e02"></a><a name="a8895f2dadaef427c8c50bb4bb2f11e02"></a>getIcon()</p>
</td>
<td class="cellrowborder" valign="top" width="26.99%" headers="mcps1.1.5.1.2 "><p id="a74973e9e2e814a7dbfe0925342fd9db9"><a name="a74973e9e2e814a7dbfe0925342fd9db9"></a><a name="a74973e9e2e814a7dbfe0925342fd9db9"></a>Obtains the marker icon.</p>
</td>
<td class="cellrowborder" valign="top" width="27.82%" headers="mcps1.1.5.1.3 "><p id="a7b06b74290954fd486680c60905e3ce9"><a name="a7b06b74290954fd486680c60905e3ce9"></a><a name="a7b06b74290954fd486680c60905e3ce9"></a>-</p>
</td>
<td class="cellrowborder" valign="top" width="13.18%" headers="mcps1.1.5.1.4 "><p id="a8571982996dc4e6ea23d84d16b431bed"><a name="a8571982996dc4e6ea23d84d16b431bed"></a><a name="a8571982996dc4e6ea23d84d16b431bed"></a>Object</p>
</td>
</tr>
<tr id="rd5abf9d205134633b24e94640875c447"><td class="cellrowborder" valign="top" width="32.01%" headers="mcps1.1.5.1.1 "><p id="ade23864887ac4d87854faf1e4ee83793"><a name="ade23864887ac4d87854faf1e4ee83793"></a><a name="ade23864887ac4d87854faf1e4ee83793"></a>getLabel()</p>
</td>
<td class="cellrowborder" valign="top" width="26.99%" headers="mcps1.1.5.1.2 "><p id="a49b0923f55a847aca9d83c7faf9ad8c2"><a name="a49b0923f55a847aca9d83c7faf9ad8c2"></a><a name="a49b0923f55a847aca9d83c7faf9ad8c2"></a>Obtains the marker label.</p>
</td>
<td class="cellrowborder" valign="top" width="27.82%" headers="mcps1.1.5.1.3 "><p id="a95cdb3d2070e4a62977e90237c89ca45"><a name="a95cdb3d2070e4a62977e90237c89ca45"></a><a name="a95cdb3d2070e4a62977e90237c89ca45"></a>-</p>
</td>
<td class="cellrowborder" valign="top" width="13.18%" headers="mcps1.1.5.1.4 "><p id="a204faca44e264bbfbf73ef708aa3c9e0"><a name="a204faca44e264bbfbf73ef708aa3c9e0"></a><a name="a204faca44e264bbfbf73ef708aa3c9e0"></a>String</p>
</td>
</tr>
<tr id="rf21a844c002746789b26ab4510710065"><td class="cellrowborder" valign="top" width="32.01%" headers="mcps1.1.5.1.1 "><p id="a429d36de04cc41f9b4f6a020cf621cbc"><a name="a429d36de04cc41f9b4f6a020cf621cbc"></a><a name="a429d36de04cc41f9b4f6a020cf621cbc"></a>getMap()</p>
</td>
<td class="cellrowborder" valign="top" width="26.99%" headers="mcps1.1.5.1.2 "><p id="aabe1aa653a244c519ee8ffaaeda236e4"><a name="aabe1aa653a244c519ee8ffaaeda236e4"></a><a name="aabe1aa653a244c519ee8ffaaeda236e4"></a>Obtains the map instance to which a marker is bound.</p>
</td>
<td class="cellrowborder" valign="top" width="27.82%" headers="mcps1.1.5.1.3 "><p id="a12677295c3774181b768b5a873d877b9"><a name="a12677295c3774181b768b5a873d877b9"></a><a name="a12677295c3774181b768b5a873d877b9"></a>-</p>
</td>
<td class="cellrowborder" valign="top" width="13.18%" headers="mcps1.1.5.1.4 "><p id="aaeb6d251b6e24f4da097e00083620b0c"><a name="aaeb6d251b6e24f4da097e00083620b0c"></a><a name="aaeb6d251b6e24f4da097e00083620b0c"></a><a href="js-hwmap.md">HWMap</a></p>
</td>
</tr>
<tr id="r2148e4f3b0294bf4804187ad7ea71e57"><td class="cellrowborder" valign="top" width="32.01%" headers="mcps1.1.5.1.1 "><p id="a7dc8ba56c3d94b929f950629fe69d395"><a name="a7dc8ba56c3d94b929f950629fe69d395"></a><a name="a7dc8ba56c3d94b929f950629fe69d395"></a>getPosition()</p>
</td>
<td class="cellrowborder" valign="top" width="26.99%" headers="mcps1.1.5.1.2 "><p id="a854b488acff24c84b160d9d1cb86ee86"><a name="a854b488acff24c84b160d9d1cb86ee86"></a><a name="a854b488acff24c84b160d9d1cb86ee86"></a>Obtains the position of a <a href="js-hwmarker.md">HWMarker</a> object.</p>
</td>
<td class="cellrowborder" valign="top" width="27.82%" headers="mcps1.1.5.1.3 "><p id="a04004970747c46beb7cbc90170fdaea3"><a name="a04004970747c46beb7cbc90170fdaea3"></a><a name="a04004970747c46beb7cbc90170fdaea3"></a>-</p>
</td>
<td class="cellrowborder" valign="top" width="13.18%" headers="mcps1.1.5.1.4 "><p id="a8193fa4d3d264c3d9c7c7c9903c8fd35"><a name="a8193fa4d3d264c3d9c7c7c9903c8fd35"></a><a name="a8193fa4d3d264c3d9c7c7c9903c8fd35"></a><a href="js-params.md#s1f33822192a04bbe9bd9de86a17460b1">LatLng</a></p>
</td>
</tr>
<tr id="re4a84f0231174052ba9d8709d3108ce9"><td class="cellrowborder" valign="top" width="32.01%" headers="mcps1.1.5.1.1 "><p id="ab297eedb3ac74eeba172a192a42d402c"><a name="ab297eedb3ac74eeba172a192a42d402c"></a><a name="ab297eedb3ac74eeba172a192a42d402c"></a>getZIndex()</p>
</td>
<td class="cellrowborder" valign="top" width="26.99%" headers="mcps1.1.5.1.2 "><p id="a0f27e2c6bdbb410a9640609d9049d473"><a name="a0f27e2c6bdbb410a9640609d9049d473"></a><a name="a0f27e2c6bdbb410a9640609d9049d473"></a>Obtains the z-index of a <a href="js-hwmarker.md">HWMarker</a> object.</p>
</td>
<td class="cellrowborder" valign="top" width="27.82%" headers="mcps1.1.5.1.3 "><p id="aa359213fb94545e9b1807664352e4d03"><a name="aa359213fb94545e9b1807664352e4d03"></a><a name="aa359213fb94545e9b1807664352e4d03"></a>-</p>
</td>
<td class="cellrowborder" valign="top" width="13.18%" headers="mcps1.1.5.1.4 "><p id="accee5572c5fb4b3bbc8cb1348a7a96bd"><a name="accee5572c5fb4b3bbc8cb1348a7a96bd"></a><a name="accee5572c5fb4b3bbc8cb1348a7a96bd"></a>Number</p>
</td>
</tr>
<tr id="r7287ca333bdb4af3b08b15d99840e5c9"><td class="cellrowborder" valign="top" width="32.01%" headers="mcps1.1.5.1.1 "><p id="a26d004f2276e446086833baf825dbef1"><a name="a26d004f2276e446086833baf825dbef1"></a><a name="a26d004f2276e446086833baf825dbef1"></a>setIcon(icon)</p>
</td>
<td class="cellrowborder" valign="top" width="26.99%" headers="mcps1.1.5.1.2 "><p id="a7c7b5fcf988649ecaffbb4b9a07a40e8"><a name="a7c7b5fcf988649ecaffbb4b9a07a40e8"></a><a name="a7c7b5fcf988649ecaffbb4b9a07a40e8"></a>Sets the marker icon.</p>
</td>
<td class="cellrowborder" valign="top" width="27.82%" headers="mcps1.1.5.1.3 "><p id="a2eaf8de7a3b14842bedbde7b4c9aee11"><a name="a2eaf8de7a3b14842bedbde7b4c9aee11"></a><a name="a2eaf8de7a3b14842bedbde7b4c9aee11"></a>Object</p>
</td>
<td class="cellrowborder" valign="top" width="13.18%" headers="mcps1.1.5.1.4 "><p id="a0da8f938e18346bf9c07a1448f8ad679"><a name="a0da8f938e18346bf9c07a1448f8ad679"></a><a name="a0da8f938e18346bf9c07a1448f8ad679"></a>-</p>
</td>
</tr>
<tr id="r820267bbf53140d88b46e8b56fcbb0b0"><td class="cellrowborder" valign="top" width="32.01%" headers="mcps1.1.5.1.1 "><p id="a4e4b4117b47249f48012a95e50e17802"><a name="a4e4b4117b47249f48012a95e50e17802"></a><a name="a4e4b4117b47249f48012a95e50e17802"></a>setLabel(label)</p>
</td>
<td class="cellrowborder" valign="top" width="26.99%" headers="mcps1.1.5.1.2 "><p id="ac1cf5773c7784b67897d83ba3ccf1c59"><a name="ac1cf5773c7784b67897d83ba3ccf1c59"></a><a name="ac1cf5773c7784b67897d83ba3ccf1c59"></a>Sets the marker label.</p>
</td>
<td class="cellrowborder" valign="top" width="27.82%" headers="mcps1.1.5.1.3 "><p id="a321d0cf57017457b957f620f2b6afdec"><a name="a321d0cf57017457b957f620f2b6afdec"></a><a name="a321d0cf57017457b957f620f2b6afdec"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="13.18%" headers="mcps1.1.5.1.4 "><p id="ad62e695e7cc642769f6c9ad26e563b59"><a name="ad62e695e7cc642769f6c9ad26e563b59"></a><a name="ad62e695e7cc642769f6c9ad26e563b59"></a>-</p>
</td>
</tr>
<tr id="r9e1fffabeb68475283cde9d499e7fcca"><td class="cellrowborder" valign="top" width="32.01%" headers="mcps1.1.5.1.1 "><p id="ada5f444a342b47be8ec8f3959a3ea5ec"><a name="ada5f444a342b47be8ec8f3959a3ea5ec"></a><a name="ada5f444a342b47be8ec8f3959a3ea5ec"></a>setMap(map)</p>
</td>
<td class="cellrowborder" valign="top" width="26.99%" headers="mcps1.1.5.1.2 "><p id="a79c3434b529442cea75024cb27f99a14"><a name="a79c3434b529442cea75024cb27f99a14"></a><a name="a79c3434b529442cea75024cb27f99a14"></a>Binds a marker to a map. </p>
</td>
<td class="cellrowborder" valign="top" width="27.82%" headers="mcps1.1.5.1.3 "><p id="a2b5bef14f90844e58aa0c7c005db8e8b"><a name="a2b5bef14f90844e58aa0c7c005db8e8b"></a><a name="a2b5bef14f90844e58aa0c7c005db8e8b"></a><a href="js-hwmap.md">HWMap</a></p>
</td>
<td class="cellrowborder" valign="top" width="13.18%" headers="mcps1.1.5.1.4 "><p id="a7eb156dd8a8845229cec40a9328b579e"><a name="a7eb156dd8a8845229cec40a9328b579e"></a><a name="a7eb156dd8a8845229cec40a9328b579e"></a>-</p>
</td>
</tr>
<tr id="r32f4acb0d3bb4be9ae11b84592f14cd6"><td class="cellrowborder" valign="top" width="32.01%" headers="mcps1.1.5.1.1 "><p id="a54d6da2378434eec9bd56eead86d5afc"><a name="a54d6da2378434eec9bd56eead86d5afc"></a><a name="a54d6da2378434eec9bd56eead86d5afc"></a>setPosition(position)</p>
</td>
<td class="cellrowborder" valign="top" width="26.99%" headers="mcps1.1.5.1.2 "><p id="a23e37406aea541379ebc23a8c61bed75"><a name="a23e37406aea541379ebc23a8c61bed75"></a><a name="a23e37406aea541379ebc23a8c61bed75"></a>Sets the position of a <a href="js-hwmarker.md">HWMarker</a> object.</p>
</td>
<td class="cellrowborder" valign="top" width="27.82%" headers="mcps1.1.5.1.3 "><p id="ae318d581d7ea4bbe8127ec67d95351fa"><a name="ae318d581d7ea4bbe8127ec67d95351fa"></a><a name="ae318d581d7ea4bbe8127ec67d95351fa"></a><a href="js-params.md#s1f33822192a04bbe9bd9de86a17460b1">LatLng</a></p>
</td>
<td class="cellrowborder" valign="top" width="13.18%" headers="mcps1.1.5.1.4 "><p id="a83534ff535ae4e65821dda398b13f372"><a name="a83534ff535ae4e65821dda398b13f372"></a><a name="a83534ff535ae4e65821dda398b13f372"></a>-</p>
</td>
</tr>
<tr id="rccf26fa78f094cca99421f14e384bb0a"><td class="cellrowborder" valign="top" width="32.01%" headers="mcps1.1.5.1.1 "><p id="a09fb32d425dd42cf8b0a491ff800145a"><a name="a09fb32d425dd42cf8b0a491ff800145a"></a><a name="a09fb32d425dd42cf8b0a491ff800145a"></a>setZIndex(zIndex)</p>
</td>
<td class="cellrowborder" valign="top" width="26.99%" headers="mcps1.1.5.1.2 "><p id="ad270f52fc4ff4536841b7a9d28709d08"><a name="ad270f52fc4ff4536841b7a9d28709d08"></a><a name="ad270f52fc4ff4536841b7a9d28709d08"></a>Sets the z-index of a <a href="js-hwmarker.md">HWMarker</a> object, that is, the overlay relationship on the Z axis.</p>
</td>
<td class="cellrowborder" valign="top" width="27.82%" headers="mcps1.1.5.1.3 "><p id="a2f42cc64674f437888aaa131c7f52c8c"><a name="a2f42cc64674f437888aaa131c7f52c8c"></a><a name="a2f42cc64674f437888aaa131c7f52c8c"></a>Number</p>
</td>
<td class="cellrowborder" valign="top" width="13.18%" headers="mcps1.1.5.1.4 "><p id="a6b005bcfe67c47f1ab6190c01a207753"><a name="a6b005bcfe67c47f1ab6190c01a207753"></a><a name="a6b005bcfe67c47f1ab6190c01a207753"></a>-</p>
</td>
</tr>
<tr id="r3478e0631895402a945376880ab04eb6"><td class="cellrowborder" valign="top" width="32.01%" headers="mcps1.1.5.1.1 "><p id="ae4a493da40064ad6a325b76508eb63b7"><a name="ae4a493da40064ad6a325b76508eb63b7"></a><a name="ae4a493da40064ad6a325b76508eb63b7"></a>addListener(event, callback)</p>
</td>
<td class="cellrowborder" valign="top" width="26.99%" headers="mcps1.1.5.1.2 "><p id="aab4411d4fd614a0ebbda0d3000e4b07d"><a name="aab4411d4fd614a0ebbda0d3000e4b07d"></a><a name="aab4411d4fd614a0ebbda0d3000e4b07d"></a>Adds an event listener. </p>
</td>
<td class="cellrowborder" valign="top" width="27.82%" headers="mcps1.1.5.1.3 "><a name="ua321e5032e344920a321838bf57cf5f6"></a><a name="ua321e5032e344920a321838bf57cf5f6"></a><ul id="ua321e5032e344920a321838bf57cf5f6"><li><strong id="b82975558231"><a name="b82975558231"></a><a name="b82975558231"></a>event</strong>: event, which is of the <strong id="b71954214249"><a name="b71954214249"></a><a name="b71954214249"></a>String</strong> type. For details, please refer to <a href="#s96ebb83d37c2423aa1aa9f6caa44bf11">Events</a>.</li><li><strong id="b1953458192415"><a name="b1953458192415"></a><a name="b1953458192415"></a>callback</strong>: callback function triggered by the event.</li></ul>
</td>
<td class="cellrowborder" valign="top" width="13.18%" headers="mcps1.1.5.1.4 "><p id="a8b057780777d4885a97b29f277e2522a"><a name="a8b057780777d4885a97b29f277e2522a"></a><a name="a8b057780777d4885a97b29f277e2522a"></a>-</p>
</td>
</tr>
<tr id="rb14e17a8d7f94de788a79193abeda67e"><td class="cellrowborder" valign="top" width="32.01%" headers="mcps1.1.5.1.1 "><p id="a7831857108094c73a29a4527b40e7796"><a name="a7831857108094c73a29a4527b40e7796"></a><a name="a7831857108094c73a29a4527b40e7796"></a>removeListener(event, callback)</p>
</td>
<td class="cellrowborder" valign="top" width="26.99%" headers="mcps1.1.5.1.2 "><p id="adacb94816928407eab7ed89491bad013"><a name="adacb94816928407eab7ed89491bad013"></a><a name="adacb94816928407eab7ed89491bad013"></a>Deletes an event listener.</p>
</td>
<td class="cellrowborder" valign="top" width="27.82%" headers="mcps1.1.5.1.3 "><a name="u36fbe705cac646899cd69d1b3cc56430"></a><a name="u36fbe705cac646899cd69d1b3cc56430"></a><ul id="u36fbe705cac646899cd69d1b3cc56430"><li><strong id="b81541219192418"><a name="b81541219192418"></a><a name="b81541219192418"></a>event</strong>: event, which is of the <strong id="b1416017196241"><a name="b1416017196241"></a><a name="b1416017196241"></a>String</strong> type. For details, please refer to <a href="#s96ebb83d37c2423aa1aa9f6caa44bf11">Events</a>.</li><li><strong id="b12299192462414"><a name="b12299192462414"></a><a name="b12299192462414"></a>callback</strong>: callback function triggered by the event.</li></ul>
</td>
<td class="cellrowborder" valign="top" width="13.18%" headers="mcps1.1.5.1.4 "><p id="af2cc8f1e83094e76b1d53b809e248d72"><a name="af2cc8f1e83094e76b1d53b809e248d72"></a><a name="af2cc8f1e83094e76b1d53b809e248d72"></a>-</p>
</td>
</tr>
</tbody>
</table>

## Events<a name="s96ebb83d37c2423aa1aa9f6caa44bf11"></a>

<a name="t0a52df0f796c4f05bedecfdc6787e352"></a>
<table><thead align="left"><tr id="rf7f4b73c431246c198b7d547c036798d"><th class="cellrowborder" valign="top" width="30.303030303030305%" id="mcps1.1.4.1.1"><p id="a8bc6b6a12dad48f38729037eecb782d8"><a name="a8bc6b6a12dad48f38729037eecb782d8"></a><a name="a8bc6b6a12dad48f38729037eecb782d8"></a><strong id="a271ebc565aa84f62a6742a2ea9f6032c"><a name="a271ebc565aa84f62a6742a2ea9f6032c"></a><a name="a271ebc565aa84f62a6742a2ea9f6032c"></a>Event</strong></p>
</th>
<th class="cellrowborder" valign="top" width="26.26262626262626%" id="mcps1.1.4.1.2"><p id="aca9ecc339f514b34abb13d9007e0b35c"><a name="aca9ecc339f514b34abb13d9007e0b35c"></a><a name="aca9ecc339f514b34abb13d9007e0b35c"></a><strong id="b97179348241"><a name="b97179348241"></a><a name="b97179348241"></a>Description</strong></p>
</th>
<th class="cellrowborder" valign="top" width="43.43434343434344%" id="mcps1.1.4.1.3"><p id="afac0099d2ea6487981870b2cedb4c9b5"><a name="afac0099d2ea6487981870b2cedb4c9b5"></a><a name="afac0099d2ea6487981870b2cedb4c9b5"></a><strong id="a93f18e137daf4a4f96ed37ba4e91a24a"><a name="a93f18e137daf4a4f96ed37ba4e91a24a"></a><a name="a93f18e137daf4a4f96ed37ba4e91a24a"></a>Usage</strong></p>
</th>
</tr>
</thead>
<tbody><tr id="rd205460143bd4f0f9af02038c5da6ba7"><td class="cellrowborder" valign="top" width="30.303030303030305%" headers="mcps1.1.4.1.1 "><p id="a2a313d02b3c041f1857dffd64a401f43"><a name="a2a313d02b3c041f1857dffd64a401f43"></a><a name="a2a313d02b3c041f1857dffd64a401f43"></a>click</p>
</td>
<td class="cellrowborder" valign="top" width="26.26262626262626%" headers="mcps1.1.4.1.2 "><p id="a8367941478aa4581b1ec36fa5ba8a1dc"><a name="a8367941478aa4581b1ec36fa5ba8a1dc"></a><a name="a8367941478aa4581b1ec36fa5ba8a1dc"></a>Click on a marker.</p>
</td>
<td class="cellrowborder" valign="top" width="43.43434343434344%" headers="mcps1.1.4.1.3 "><p id="aacf3138be4ef4a38a3e99eb292c0d0a0"><a name="aacf3138be4ef4a38a3e99eb292c0d0a0"></a><a name="aacf3138be4ef4a38a3e99eb292c0d0a0"></a><strong id="b3716133619244"><a name="b3716133619244"></a><a name="b3716133619244"></a>marker.addListener('click', callback)</strong>: The <strong id="b107221136202416"><a name="b107221136202416"></a><a name="b107221136202416"></a>callback</strong> parameter indicates a custom callback function.</p>
</td>
</tr>
<tr id="rfeb788cbfa324ef0a41f99c65192731e"><td class="cellrowborder" valign="top" width="30.303030303030305%" headers="mcps1.1.4.1.1 "><p id="a2125fe4759b0468f9e187c807c913b9b"><a name="a2125fe4759b0468f9e187c807c913b9b"></a><a name="a2125fe4759b0468f9e187c807c913b9b"></a>dbclick</p>
</td>
<td class="cellrowborder" valign="top" width="26.26262626262626%" headers="mcps1.1.4.1.2 "><p id="a6b07e20d8917444c90987200ead43f82"><a name="a6b07e20d8917444c90987200ead43f82"></a><a name="a6b07e20d8917444c90987200ead43f82"></a>Double-click on a marker. </p>
</td>
<td class="cellrowborder" valign="top" width="43.43434343434344%" headers="mcps1.1.4.1.3 "><p id="a2a27f2550dcd4247bbdc952c3df0a0ec"><a name="a2a27f2550dcd4247bbdc952c3df0a0ec"></a><a name="a2a27f2550dcd4247bbdc952c3df0a0ec"></a><strong id="b254164412244"><a name="b254164412244"></a><a name="b254164412244"></a>marker.addListener('dbclick', callback)</strong>: The <strong id="b060154442412"><a name="b060154442412"></a><a name="b060154442412"></a>callback</strong> parameter indicates a custom callback function.</p>
</td>
</tr>
<tr id="r11e78895839844e894824527269a997f"><td class="cellrowborder" valign="top" width="30.303030303030305%" headers="mcps1.1.4.1.1 "><p id="ae45a7795e53a456bb25761958dd1f358"><a name="ae45a7795e53a456bb25761958dd1f358"></a><a name="ae45a7795e53a456bb25761958dd1f358"></a>icon_changed</p>
</td>
<td class="cellrowborder" valign="top" width="26.26262626262626%" headers="mcps1.1.4.1.2 "><p id="a4afbfe6b5803456fbccf7f97d7c625e6"><a name="a4afbfe6b5803456fbccf7f97d7c625e6"></a><a name="a4afbfe6b5803456fbccf7f97d7c625e6"></a>Marker icon change.</p>
</td>
<td class="cellrowborder" valign="top" width="43.43434343434344%" headers="mcps1.1.4.1.3 "><p id="a83673924f23e4a079e5fa686f98c86cf"><a name="a83673924f23e4a079e5fa686f98c86cf"></a><a name="a83673924f23e4a079e5fa686f98c86cf"></a><strong id="b18515175212248"><a name="b18515175212248"></a><a name="b18515175212248"></a>marker.addListener('icon_changed', callback)</strong>: The <strong id="b152195213240"><a name="b152195213240"></a><a name="b152195213240"></a>callback</strong> parameter indicates a custom callback function.</p>
</td>
</tr>
<tr id="r1d012053fa9842ffb8c47572837a36ea"><td class="cellrowborder" valign="top" width="30.303030303030305%" headers="mcps1.1.4.1.1 "><p id="aa0e337d6fe184660846ef92c57a1a632"><a name="aa0e337d6fe184660846ef92c57a1a632"></a><a name="aa0e337d6fe184660846ef92c57a1a632"></a>mousedown</p>
</td>
<td class="cellrowborder" valign="top" width="26.26262626262626%" headers="mcps1.1.4.1.2 "><p id="a4fac14f00aaf447d9e4c16f67927280b"><a name="a4fac14f00aaf447d9e4c16f67927280b"></a><a name="a4fac14f00aaf447d9e4c16f67927280b"></a>Mouse button press.</p>
</td>
<td class="cellrowborder" valign="top" width="43.43434343434344%" headers="mcps1.1.4.1.3 "><p id="a2038457271674e248ca7b7af1f739b03"><a name="a2038457271674e248ca7b7af1f739b03"></a><a name="a2038457271674e248ca7b7af1f739b03"></a><strong id="b95812619255"><a name="b95812619255"></a><a name="b95812619255"></a>marker.addListener('mousedown', callback)</strong>: The <strong id="b1164667254"><a name="b1164667254"></a><a name="b1164667254"></a>callback</strong> parameter indicates a custom callback function.</p>
</td>
</tr>
<tr id="r87a75b1dbd6e414191c26a8ac6dd74c2"><td class="cellrowborder" valign="top" width="30.303030303030305%" headers="mcps1.1.4.1.1 "><p id="a7edabdf05a5f402db9cf184459b9786e"><a name="a7edabdf05a5f402db9cf184459b9786e"></a><a name="a7edabdf05a5f402db9cf184459b9786e"></a>mouseup</p>
</td>
<td class="cellrowborder" valign="top" width="26.26262626262626%" headers="mcps1.1.4.1.2 "><p id="a9eb2cb90099f4102b0a9bbce7fc9e704"><a name="a9eb2cb90099f4102b0a9bbce7fc9e704"></a><a name="a9eb2cb90099f4102b0a9bbce7fc9e704"></a>Mouse button release.</p>
</td>
<td class="cellrowborder" valign="top" width="43.43434343434344%" headers="mcps1.1.4.1.3 "><p id="aaed1748c8cf64895acfa29e36bd591d4"><a name="aaed1748c8cf64895acfa29e36bd591d4"></a><a name="aaed1748c8cf64895acfa29e36bd591d4"></a><strong id="b1376120126259"><a name="b1376120126259"></a><a name="b1376120126259"></a>marker.addListener('mouseup', callback)</strong>: The <strong id="b13767412162511"><a name="b13767412162511"></a><a name="b13767412162511"></a>callback</strong> parameter indicates a custom callback function.</p>
</td>
</tr>
<tr id="rbef8e98b00e64ad29e72987b2ef00d19"><td class="cellrowborder" valign="top" width="30.303030303030305%" headers="mcps1.1.4.1.1 "><p id="ab4f5e68254d942278b4ee8c1ce9a4f25"><a name="ab4f5e68254d942278b4ee8c1ce9a4f25"></a><a name="ab4f5e68254d942278b4ee8c1ce9a4f25"></a>position_changed</p>
</td>
<td class="cellrowborder" valign="top" width="26.26262626262626%" headers="mcps1.1.4.1.2 "><p id="a7c1bcf9bfd604d1e95bace10253ef664"><a name="a7c1bcf9bfd604d1e95bace10253ef664"></a><a name="a7c1bcf9bfd604d1e95bace10253ef664"></a>Marker position change.</p>
</td>
<td class="cellrowborder" valign="top" width="43.43434343434344%" headers="mcps1.1.4.1.3 "><p id="a667aa931b50b484d9d463f462d1afec7"><a name="a667aa931b50b484d9d463f462d1afec7"></a><a name="a667aa931b50b484d9d463f462d1afec7"></a><strong id="b04181962510"><a name="b04181962510"></a><a name="b04181962510"></a>marker.addListener('position_changed', callback)</strong>: The <strong id="b61017193259"><a name="b61017193259"></a><a name="b61017193259"></a>callback</strong> parameter indicates a custom callback function.</p>
</td>
</tr>
</tbody>
</table>

## MarkerOptions<a name="s049098dea90d4152ad819e2e16099e38"></a>

<a name="t151fa03e654a4c6898bfe1e23624c4af"></a>
<table><thead align="left"><tr id="rf772fc6deb0d4ee186b46f68cb2d9ff6"><th class="cellrowborder" valign="top" width="18.5%" id="mcps1.1.5.1.1"><p id="af464dfa4eee6473e952657216ae391f7"><a name="af464dfa4eee6473e952657216ae391f7"></a><a name="af464dfa4eee6473e952657216ae391f7"></a><strong id="a6ad24109403549b88cf0a44db097fe16"><a name="a6ad24109403549b88cf0a44db097fe16"></a><a name="a6ad24109403549b88cf0a44db097fe16"></a>Parameter</strong></p>
</th>
<th class="cellrowborder" valign="top" width="14.000000000000002%" id="mcps1.1.5.1.2"><p id="a2da396b142954a5db222bc194b7fd472"><a name="a2da396b142954a5db222bc194b7fd472"></a><a name="a2da396b142954a5db222bc194b7fd472"></a><strong id="adda77d155fe4477b8a5bba6bb9797338"><a name="adda77d155fe4477b8a5bba6bb9797338"></a><a name="adda77d155fe4477b8a5bba6bb9797338"></a>Mandatory/Optional</strong></p>
</th>
<th class="cellrowborder" valign="top" width="22.86%" id="mcps1.1.5.1.3"><p id="a035856c28b2d4d80b9a05c1dfb48d14c"><a name="a035856c28b2d4d80b9a05c1dfb48d14c"></a><a name="a035856c28b2d4d80b9a05c1dfb48d14c"></a><strong id="a1d83694689214a069babfb39df72b3e6"><a name="a1d83694689214a069babfb39df72b3e6"></a><a name="a1d83694689214a069babfb39df72b3e6"></a>Type</strong></p>
</th>
<th class="cellrowborder" valign="top" width="44.64%" id="mcps1.1.5.1.4"><p id="a13fcd85d8b7340229832eb2404d02800"><a name="a13fcd85d8b7340229832eb2404d02800"></a><a name="a13fcd85d8b7340229832eb2404d02800"></a><strong id="b747542992511"><a name="b747542992511"></a><a name="b747542992511"></a>Description</strong></p>
</th>
</tr>
</thead>
<tbody><tr id="r22c63c8e68e5428bacdadcbc80016001"><td class="cellrowborder" valign="top" width="18.5%" headers="mcps1.1.5.1.1 "><p id="ace54fbfe3d554a2eb141b2282e03e925"><a name="ace54fbfe3d554a2eb141b2282e03e925"></a><a name="ace54fbfe3d554a2eb141b2282e03e925"></a>map</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="a666701b93a394ce3b9887d1762313730"><a name="a666701b93a394ce3b9887d1762313730"></a><a name="a666701b93a394ce3b9887d1762313730"></a>Mandatory</p>
</td>
<td class="cellrowborder" valign="top" width="22.86%" headers="mcps1.1.5.1.3 "><p id="a8534d1391d0343b5a0f4ec06d412c845"><a name="a8534d1391d0343b5a0f4ec06d412c845"></a><a name="a8534d1391d0343b5a0f4ec06d412c845"></a><a href="js-hwmap.md">HWMap</a></p>
</td>
<td class="cellrowborder" valign="top" width="44.64%" headers="mcps1.1.5.1.4 "><p id="aead8332cf81146ba8562405c20ef386e"><a name="aead8332cf81146ba8562405c20ef386e"></a><a name="aead8332cf81146ba8562405c20ef386e"></a>Map instance.</p>
</td>
</tr>
<tr id="r9d1b310b87624bdba1181d036778c2f0"><td class="cellrowborder" valign="top" width="18.5%" headers="mcps1.1.5.1.1 "><p id="a5ce39f20df334fd0a1147fc515ff1fa5"><a name="a5ce39f20df334fd0a1147fc515ff1fa5"></a><a name="a5ce39f20df334fd0a1147fc515ff1fa5"></a>icon</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="a7a021fc5940d4390b5778350c56e01a6"><a name="a7a021fc5940d4390b5778350c56e01a6"></a><a name="a7a021fc5940d4390b5778350c56e01a6"></a>Optional</p>
</td>
<td class="cellrowborder" valign="top" width="22.86%" headers="mcps1.1.5.1.3 "><p id="aee68aedef810468d9ec724a496e6adda"><a name="aee68aedef810468d9ec724a496e6adda"></a><a name="aee68aedef810468d9ec724a496e6adda"></a>String | <a href="#sfbc5428e87a44deb9010cc2f3a589894">MarkerIconOption</a></p>
</td>
<td class="cellrowborder" valign="top" width="44.64%" headers="mcps1.1.5.1.4 "><p id="affb7ede478054750bf146828352cb03b"><a name="affb7ede478054750bf146828352cb03b"></a><a name="affb7ede478054750bf146828352cb03b"></a>Icon of a marker, which can be the URL of an image or a file path.</p>
</td>
</tr>
<tr id="re3648790d4d14573baaca44615c8053c"><td class="cellrowborder" valign="top" width="18.5%" headers="mcps1.1.5.1.1 "><p id="a0f7e031181ac406bb5841d87a797b5fb"><a name="a0f7e031181ac406bb5841d87a797b5fb"></a><a name="a0f7e031181ac406bb5841d87a797b5fb"></a>label</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="p39220316367"><a name="p39220316367"></a><a name="p39220316367"></a>Optional</p>
</td>
<td class="cellrowborder" valign="top" width="22.86%" headers="mcps1.1.5.1.3 "><p id="a936798278ce14e60ac85749cdad3f7a4"><a name="a936798278ce14e60ac85749cdad3f7a4"></a><a name="a936798278ce14e60ac85749cdad3f7a4"></a>String | <a href="#sddf63bee876d44188dec2b7ccdfcaeb8">MarkerLabelOption</a></p>
</td>
<td class="cellrowborder" valign="top" width="44.64%" headers="mcps1.1.5.1.4 "><p id="a4f8b4ec394e34f29a979782321bd378b"><a name="a4f8b4ec394e34f29a979782321bd378b"></a><a name="a4f8b4ec394e34f29a979782321bd378b"></a>Marker label, which can be text or detailed information.</p>
</td>
</tr>
<tr id="rccc6e97e252a45ebbad443b0050060ca"><td class="cellrowborder" valign="top" width="18.5%" headers="mcps1.1.5.1.1 "><p id="aad7d420edd2442808ae70a4fdeadb44c"><a name="aad7d420edd2442808ae70a4fdeadb44c"></a><a name="aad7d420edd2442808ae70a4fdeadb44c"></a>position</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="a37454c891a5c42c3a76f8ad85f1aeae0"><a name="a37454c891a5c42c3a76f8ad85f1aeae0"></a><a name="a37454c891a5c42c3a76f8ad85f1aeae0"></a>Mandatory</p>
</td>
<td class="cellrowborder" valign="top" width="22.86%" headers="mcps1.1.5.1.3 "><p id="aac01430ffe36463b9a0db97cd330ec8b"><a name="aac01430ffe36463b9a0db97cd330ec8b"></a><a name="aac01430ffe36463b9a0db97cd330ec8b"></a><a href="js-params.md#s1f33822192a04bbe9bd9de86a17460b1">LatLng</a></p>
</td>
<td class="cellrowborder" valign="top" width="44.64%" headers="mcps1.1.5.1.4 "><p id="aa9979ec3cfd64956a09a87063869eb8c"><a name="aa9979ec3cfd64956a09a87063869eb8c"></a><a name="aa9979ec3cfd64956a09a87063869eb8c"></a>Marker position.</p>
</td>
</tr>
<tr id="r49e6edd1cdf64aaa84a8a2148dff2785"><td class="cellrowborder" valign="top" width="18.5%" headers="mcps1.1.5.1.1 "><p id="a471abbe917f943ac8f6f24d1466172c1"><a name="a471abbe917f943ac8f6f24d1466172c1"></a><a name="a471abbe917f943ac8f6f24d1466172c1"></a>zIndex</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="p1977116321367"><a name="p1977116321367"></a><a name="p1977116321367"></a>Optional</p>
</td>
<td class="cellrowborder" valign="top" width="22.86%" headers="mcps1.1.5.1.3 "><p id="a7244296a042340158ac5d06ec78e65e9"><a name="a7244296a042340158ac5d06ec78e65e9"></a><a name="a7244296a042340158ac5d06ec78e65e9"></a>Number</p>
</td>
<td class="cellrowborder" valign="top" width="44.64%" headers="mcps1.1.5.1.4 "><p id="ab516cd6e59f74c7db50aac02309154d5"><a name="ab516cd6e59f74c7db50aac02309154d5"></a><a name="ab516cd6e59f74c7db50aac02309154d5"></a>Z-index of a <a href="js-hwmarker.md">HWMarker</a> object, that is, the overlay relationship on the Z axis (relative to <a href="js-hwmarker.md">HWMarker</a>, <a href="js-hwcircle.md">HWCircle</a>, <a href="js-hwpolygon.md">HWPolygon</a>, and <a href="js-hwpolyline.md">HWPolyline</a>).</p>
</td>
</tr>
</tbody>
</table>

## MarkerIconOption<a name="sfbc5428e87a44deb9010cc2f3a589894"></a>

<a name="t67e6a47db8244410914a6bc63804fe9d"></a>
<table><thead align="left"><tr id="ra38f3062ec914c5a920cc9557b7d78eb"><th class="cellrowborder" valign="top" width="20.237976202379762%" id="mcps1.1.5.1.1"><p id="a8f310bc95cc042ab9ff2a0536cb882b3"><a name="a8f310bc95cc042ab9ff2a0536cb882b3"></a><a name="a8f310bc95cc042ab9ff2a0536cb882b3"></a><strong id="a019815a27fc8468e940b01dc82162146"><a name="a019815a27fc8468e940b01dc82162146"></a><a name="a019815a27fc8468e940b01dc82162146"></a>Parameter</strong></p>
</th>
<th class="cellrowborder" valign="top" width="13.998600139986003%" id="mcps1.1.5.1.2"><p id="acd211f90510d44c99a1c5a5d64ae7c3c"><a name="acd211f90510d44c99a1c5a5d64ae7c3c"></a><a name="acd211f90510d44c99a1c5a5d64ae7c3c"></a><strong id="aa363acf72a3646a681b692137820f659"><a name="aa363acf72a3646a681b692137820f659"></a><a name="aa363acf72a3646a681b692137820f659"></a>Mandatory/Optional</strong></p>
</th>
<th class="cellrowborder" valign="top" width="15.17848215178482%" id="mcps1.1.5.1.3"><p id="ae24b8652cb334831aaba58bcc492e9f3"><a name="ae24b8652cb334831aaba58bcc492e9f3"></a><a name="ae24b8652cb334831aaba58bcc492e9f3"></a><strong id="ace180424fed046ffb35887912d775c1f"><a name="ace180424fed046ffb35887912d775c1f"></a><a name="ace180424fed046ffb35887912d775c1f"></a>Type</strong></p>
</th>
<th class="cellrowborder" valign="top" width="50.584941505849415%" id="mcps1.1.5.1.4"><p id="a2c8dcf1d25e540c598574e8cd9e33335"><a name="a2c8dcf1d25e540c598574e8cd9e33335"></a><a name="a2c8dcf1d25e540c598574e8cd9e33335"></a><strong id="b07475211275"><a name="b07475211275"></a><a name="b07475211275"></a>Description</strong></p>
</th>
</tr>
</thead>
<tbody><tr id="r73f90d79355d4c51b904517d8dc32aa3"><td class="cellrowborder" valign="top" width="20.237976202379762%" headers="mcps1.1.5.1.1 "><p id="ac72784d3f51c4d709fccb965e3b39e67"><a name="ac72784d3f51c4d709fccb965e3b39e67"></a><a name="ac72784d3f51c4d709fccb965e3b39e67"></a>anchor</p>
</td>
<td class="cellrowborder" valign="top" width="13.998600139986003%" headers="mcps1.1.5.1.2 "><p id="a2191e3a50dc045d398ebf699b8a81629"><a name="a2191e3a50dc045d398ebf699b8a81629"></a><a name="a2191e3a50dc045d398ebf699b8a81629"></a>Optional</p>
</td>
<td class="cellrowborder" valign="top" width="15.17848215178482%" headers="mcps1.1.5.1.3 "><p id="a77495e3c7ff5431e9b1fd6f2ddfe9411"><a name="a77495e3c7ff5431e9b1fd6f2ddfe9411"></a><a name="a77495e3c7ff5431e9b1fd6f2ddfe9411"></a>Array&lt;Number&gt;</p>
</td>
<td class="cellrowborder" valign="top" width="50.584941505849415%" headers="mcps1.1.5.1.4 "><p id="aaf49dcf64dc94044880f3d84ccf1ca6e"><a name="aaf49dcf64dc94044880f3d84ccf1ca6e"></a><a name="aaf49dcf64dc94044880f3d84ccf1ca6e"></a>Image anchor point. The value is an array in <em id="i2018215410276"><a name="i2018215410276"></a><a name="i2018215410276"></a>[x, y]</em> format. The default value is <strong id="b1318765462710"><a name="b1318765462710"></a><a name="b1318765462710"></a>[0.5, 1]</strong>, indicating that the anchor point is in the middle of the bottom side of the image.</p>
</td>
</tr>
<tr id="r74d6c5d4936a4485b528247960e0ade4"><td class="cellrowborder" valign="top" width="20.237976202379762%" headers="mcps1.1.5.1.1 "><p id="a2f5ebad1d1a14dd7ad14c5e345bf0c2f"><a name="a2f5ebad1d1a14dd7ad14c5e345bf0c2f"></a><a name="a2f5ebad1d1a14dd7ad14c5e345bf0c2f"></a>scale</p>
</td>
<td class="cellrowborder" valign="top" width="13.998600139986003%" headers="mcps1.1.5.1.2 "><p id="a2ed6166411cc4f7bbe084f4b77523fed"><a name="a2ed6166411cc4f7bbe084f4b77523fed"></a><a name="a2ed6166411cc4f7bbe084f4b77523fed"></a>Optional</p>
</td>
<td class="cellrowborder" valign="top" width="15.17848215178482%" headers="mcps1.1.5.1.3 "><p id="a7491e4ee7ea64eba932f6bf784e5373f"><a name="a7491e4ee7ea64eba932f6bf784e5373f"></a><a name="a7491e4ee7ea64eba932f6bf784e5373f"></a>Number</p>
</td>
<td class="cellrowborder" valign="top" width="50.584941505849415%" headers="mcps1.1.5.1.4 "><p id="a6497d4636fef4cc38df73a384d1f2b06"><a name="a6497d4636fef4cc38df73a384d1f2b06"></a><a name="a6497d4636fef4cc38df73a384d1f2b06"></a>Map zoom level, which is used to control image zooming. The value must be greater than 0. The default value is <strong id="b2692111019287"><a name="b2692111019287"></a><a name="b2692111019287"></a>1</strong>. </p>
</td>
</tr>
<tr id="r523d448b633c4edf90f99afbdb13f4a7"><td class="cellrowborder" valign="top" width="20.237976202379762%" headers="mcps1.1.5.1.1 "><p id="a73d521bdb47845a1b69721394193f32a"><a name="a73d521bdb47845a1b69721394193f32a"></a><a name="a73d521bdb47845a1b69721394193f32a"></a>opacity</p>
</td>
<td class="cellrowborder" valign="top" width="13.998600139986003%" headers="mcps1.1.5.1.2 "><p id="a902be5a1054d4a13ad5df673ddb9bf92"><a name="a902be5a1054d4a13ad5df673ddb9bf92"></a><a name="a902be5a1054d4a13ad5df673ddb9bf92"></a>Optional</p>
</td>
<td class="cellrowborder" valign="top" width="15.17848215178482%" headers="mcps1.1.5.1.3 "><p id="a785ec51d05cf4d0e835d68c22066cdb6"><a name="a785ec51d05cf4d0e835d68c22066cdb6"></a><a name="a785ec51d05cf4d0e835d68c22066cdb6"></a>Number</p>
</td>
<td class="cellrowborder" valign="top" width="50.584941505849415%" headers="mcps1.1.5.1.4 "><p id="a2e8a335bdde5432eb3aa47957846cf59"><a name="a2e8a335bdde5432eb3aa47957846cf59"></a><a name="a2e8a335bdde5432eb3aa47957846cf59"></a>Opacity. The value range is [0,1]. The value <strong id="b16521182472818"><a name="b16521182472818"></a><a name="b16521182472818"></a>1</strong> indicates that the overlay is opaque. The value <strong id="b105282242285"><a name="b105282242285"></a><a name="b105282242285"></a>0</strong> indicates that the overlay is completely transparent. The default value is <strong id="b85301924112817"><a name="b85301924112817"></a><a name="b85301924112817"></a>1</strong>. </p>
</td>
</tr>
<tr id="r8b40ad72649740fb80afd9f90a4bafc2"><td class="cellrowborder" valign="top" width="20.237976202379762%" headers="mcps1.1.5.1.1 "><p id="a3f0c9c3ab0aa48798c67e102cad65044"><a name="a3f0c9c3ab0aa48798c67e102cad65044"></a><a name="a3f0c9c3ab0aa48798c67e102cad65044"></a>url</p>
</td>
<td class="cellrowborder" valign="top" width="13.998600139986003%" headers="mcps1.1.5.1.2 "><p id="a47e3960d9d824af5ad2c80c7d5ecb79b"><a name="a47e3960d9d824af5ad2c80c7d5ecb79b"></a><a name="a47e3960d9d824af5ad2c80c7d5ecb79b"></a>Optional</p>
</td>
<td class="cellrowborder" valign="top" width="15.17848215178482%" headers="mcps1.1.5.1.3 "><p id="a6514ce83f05a41cbacb8f25a63fbecab"><a name="a6514ce83f05a41cbacb8f25a63fbecab"></a><a name="a6514ce83f05a41cbacb8f25a63fbecab"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="50.584941505849415%" headers="mcps1.1.5.1.4 "><p id="a6b03e40b4d4a48009aff439a811cf58e"><a name="a6b03e40b4d4a48009aff439a811cf58e"></a><a name="a6b03e40b4d4a48009aff439a811cf58e"></a>Image address, which can be the image URL or file path. By default, a built-in image is provided.</p>
</td>
</tr>
</tbody>
</table>

## MarkerLabelOption<a name="sddf63bee876d44188dec2b7ccdfcaeb8"></a>

<a name="table1576923818243"></a>
<table><thead align="left"><tr id="row11769183814242"><th class="cellrowborder" valign="top" width="20.237976202379762%" id="mcps1.1.5.1.1"><p id="p107695383248"><a name="p107695383248"></a><a name="p107695383248"></a><strong id="b2011566744"><a name="b2011566744"></a><a name="b2011566744"></a>Parameter</strong></p>
</th>
<th class="cellrowborder" valign="top" width="13.998600139986003%" id="mcps1.1.5.1.2"><p id="p37697388240"><a name="p37697388240"></a><a name="p37697388240"></a><strong id="b127672399"><a name="b127672399"></a><a name="b127672399"></a>Mandatory/Optional</strong></p>
</th>
<th class="cellrowborder" valign="top" width="15.17848215178482%" id="mcps1.1.5.1.3"><p id="p1976973819244"><a name="p1976973819244"></a><a name="p1976973819244"></a><strong id="b1876399565"><a name="b1876399565"></a><a name="b1876399565"></a>Type</strong></p>
</th>
<th class="cellrowborder" valign="top" width="50.584941505849415%" id="mcps1.1.5.1.4"><p id="p1276914389242"><a name="p1276914389242"></a><a name="p1276914389242"></a><strong id="b1040120278268"><a name="b1040120278268"></a><a name="b1040120278268"></a>Description</strong></p>
</th>
</tr>
</thead>
<tbody><tr id="row14769163812418"><td class="cellrowborder" valign="top" width="20.237976202379762%" headers="mcps1.1.5.1.1 "><p id="p67691138122418"><a name="p67691138122418"></a><a name="p67691138122418"></a>color</p>
</td>
<td class="cellrowborder" valign="top" width="13.998600139986003%" headers="mcps1.1.5.1.2 "><p id="p1777043882417"><a name="p1777043882417"></a><a name="p1777043882417"></a>Optional</p>
</td>
<td class="cellrowborder" valign="top" width="15.17848215178482%" headers="mcps1.1.5.1.3 "><p id="p127701538132420"><a name="p127701538132420"></a><a name="p127701538132420"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="50.584941505849415%" headers="mcps1.1.5.1.4 "><p id="p167701738132415"><a name="p167701738132415"></a><a name="p167701738132415"></a>Font color. The default value is <strong id="b182593289263"><a name="b182593289263"></a><a name="b182593289263"></a>#333</strong>.</p>
<p id="p67703385246"><a name="p67703385246"></a><a name="p67703385246"></a>The color can be set in the following ways:</p>
<a name="ul7770143818246"></a><a name="ul7770143818246"></a><ul id="ul7770143818246"><li>Color name: green</li><li>Hexadecimal value: #ff0000</li><li>RGB: rgb(0,0,0)</li><li>RGBA: rgba(0,0,0,0.5)</li><li>HSL: hsl(120,65%,75%)</li></ul>
</td>
</tr>
<tr id="row97701238112411"><td class="cellrowborder" valign="top" width="20.237976202379762%" headers="mcps1.1.5.1.1 "><p id="p777023812248"><a name="p777023812248"></a><a name="p777023812248"></a>fontSize</p>
</td>
<td class="cellrowborder" valign="top" width="13.998600139986003%" headers="mcps1.1.5.1.2 "><p id="p9770203810246"><a name="p9770203810246"></a><a name="p9770203810246"></a>Optional</p>
</td>
<td class="cellrowborder" valign="top" width="15.17848215178482%" headers="mcps1.1.5.1.3 "><p id="p8770938142412"><a name="p8770938142412"></a><a name="p8770938142412"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="50.584941505849415%" headers="mcps1.1.5.1.4 "><p id="p5770938112410"><a name="p5770938112410"></a><a name="p5770938112410"></a>Text size. The default value is <strong id="b112951915152716"><a name="b112951915152716"></a><a name="b112951915152716"></a>14</strong> pixels.</p>
</td>
</tr>
<tr id="row577043892411"><td class="cellrowborder" valign="top" width="20.237976202379762%" headers="mcps1.1.5.1.1 "><p id="p137701238192412"><a name="p137701238192412"></a><a name="p137701238192412"></a>fontFamily</p>
</td>
<td class="cellrowborder" valign="top" width="13.998600139986003%" headers="mcps1.1.5.1.2 "><p id="p87701838122417"><a name="p87701838122417"></a><a name="p87701838122417"></a>Optional</p>
</td>
<td class="cellrowborder" valign="top" width="15.17848215178482%" headers="mcps1.1.5.1.3 "><p id="p6770113811242"><a name="p6770113811242"></a><a name="p6770113811242"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="50.584941505849415%" headers="mcps1.1.5.1.4 "><p id="p077063810247"><a name="p077063810247"></a><a name="p077063810247"></a>Font. The default value is <strong id="b177515184273"><a name="b177515184273"></a><a name="b177515184273"></a>sans-serif</strong>.</p>
</td>
</tr>
<tr id="row7770838182414"><td class="cellrowborder" valign="top" width="20.237976202379762%" headers="mcps1.1.5.1.1 "><p id="p1777011383244"><a name="p1777011383244"></a><a name="p1777011383244"></a>text</p>
</td>
<td class="cellrowborder" valign="top" width="13.998600139986003%" headers="mcps1.1.5.1.2 "><p id="p207709387242"><a name="p207709387242"></a><a name="p207709387242"></a>Optional</p>
</td>
<td class="cellrowborder" valign="top" width="15.17848215178482%" headers="mcps1.1.5.1.3 "><p id="p97711038172415"><a name="p97711038172415"></a><a name="p97711038172415"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="50.584941505849415%" headers="mcps1.1.5.1.4 "><p id="p15771938172412"><a name="p15771938172412"></a><a name="p15771938172412"></a>Text content.</p>
</td>
</tr>
<tr id="row97714387246"><td class="cellrowborder" valign="top" width="20.237976202379762%" headers="mcps1.1.5.1.1 "><p id="p187711438172417"><a name="p187711438172417"></a><a name="p187711438172417"></a>offsetX</p>
</td>
<td class="cellrowborder" valign="top" width="13.998600139986003%" headers="mcps1.1.5.1.2 "><p id="p6771938202415"><a name="p6771938202415"></a><a name="p6771938202415"></a>Optional</p>
</td>
<td class="cellrowborder" valign="top" width="15.17848215178482%" headers="mcps1.1.5.1.3 "><p id="p877113872419"><a name="p877113872419"></a><a name="p877113872419"></a>Number</p>
</td>
<td class="cellrowborder" valign="top" width="50.584941505849415%" headers="mcps1.1.5.1.4 "><p id="p11771183882416"><a name="p11771183882416"></a><a name="p11771183882416"></a>Offset on the X axis, in pixels. The default value is <strong id="b182539244272"><a name="b182539244272"></a><a name="b182539244272"></a>0</strong>, indicating that the marker overlaps with the coordinate point.</p>
</td>
</tr>
<tr id="row1477113382244"><td class="cellrowborder" valign="top" width="20.237976202379762%" headers="mcps1.1.5.1.1 "><p id="p157711638162410"><a name="p157711638162410"></a><a name="p157711638162410"></a>offsetY</p>
</td>
<td class="cellrowborder" valign="top" width="13.998600139986003%" headers="mcps1.1.5.1.2 "><p id="p167712386241"><a name="p167712386241"></a><a name="p167712386241"></a>Optional</p>
</td>
<td class="cellrowborder" valign="top" width="15.17848215178482%" headers="mcps1.1.5.1.3 "><p id="p077143882413"><a name="p077143882413"></a><a name="p077143882413"></a>Number</p>
</td>
<td class="cellrowborder" valign="top" width="50.584941505849415%" headers="mcps1.1.5.1.4 "><p id="p12771103820246"><a name="p12771103820246"></a><a name="p12771103820246"></a>Offset on the Y axis, in pixels. The default value is <strong id="b491692341911"><a name="b491692341911"></a><a name="b491692341911"></a>0</strong>, indicating that the marker overlaps with the coordinate point.</p>
</td>
</tr>
</tbody>
</table>

