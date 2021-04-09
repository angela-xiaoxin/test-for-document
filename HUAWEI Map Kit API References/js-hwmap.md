# HWMap<a name="EN-US_TOPIC_0000001145860979"></a>

-   [Overview](#sbbb5523618874f0caf50b5570e302b9e)
-   [Build Method](#se09821694cc94ff8ac60fcebab8d96d2)
-   [Public Methods](#s555e95e253224826b4498eafaa0d7ada)
-   [Events](#sdd35559e11f04b6a917da42401515a0e)
-   [CopyrightControlOptions](#sdbd4312213b24f86a5ea558dcae2924e)
-   [MapOptions](#s4c4b9ba7e96445b4914a72eb8c29b4d9)
-   [ScaleControlOptions](#s08d9fe83d6b9407e8bfcd889e7af1969)
-   [LanguageCode](#sbeecdc5106da48ea8df14cd730975c40)

## Overview<a name="sbbb5523618874f0caf50b5570e302b9e"></a>

Loads a map. This class is a core class.

## Build Method<a name="se09821694cc94ff8ac60fcebab8d96d2"></a>

<a name="t14fe6dd5232b46d7890dda6e4d261335"></a>
<table><thead align="left"><tr id="r1b4c54b2a6e546128d3717fb09546500"><th class="cellrowborder" valign="top" width="40%" id="mcps1.1.3.1.1"><p id="a937f583187374bbeb26dc20768e126e4"><a name="a937f583187374bbeb26dc20768e126e4"></a><a name="a937f583187374bbeb26dc20768e126e4"></a><strong id="af0777d7b5d9643d686a9e0fed77675e3"><a name="af0777d7b5d9643d686a9e0fed77675e3"></a><a name="af0777d7b5d9643d686a9e0fed77675e3"></a>Build Method</strong></p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.1.3.1.2"><p id="a5bf06d59be8248748982de1246d26eb8"><a name="a5bf06d59be8248748982de1246d26eb8"></a><a name="a5bf06d59be8248748982de1246d26eb8"></a><strong id="b129910441115"><a name="b129910441115"></a><a name="b129910441115"></a>Description</strong></p>
</th>
</tr>
</thead>
<tbody><tr id="ra34066464362430995418cd6780b8483"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="a878d8e915dfc4b168239a1160414273a"><a name="a878d8e915dfc4b168239a1160414273a"></a><a name="a878d8e915dfc4b168239a1160414273a"></a>HWMapJsSDK.HWMap(div, mapOptions)</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="a7c564fbdabe545b08dd4a5515e226476"><a name="a7c564fbdabe545b08dd4a5515e226476"></a><a name="a7c564fbdabe545b08dd4a5515e226476"></a>In the method, <strong id="b1336215451312"><a name="b1336215451312"></a><a name="b1336215451312"></a>div</strong> indicates a map filling container and is mandatory, and <strong id="b1236274516113"><a name="b1236274516113"></a><a name="b1236274516113"></a>mapOptions</strong> specifies map attributes. For details, please refer to <a href="#s4c4b9ba7e96445b4914a72eb8c29b4d9">MapOptions</a>.</p>
</td>
</tr>
</tbody>
</table>

## Public Methods<a name="s555e95e253224826b4498eafaa0d7ada"></a>

<a name="tbc11b1ed9bcf45f8b6b25ac1a6a27406"></a>
<table><thead align="left"><tr id="rc5d62dfe43654f67b1a060b05419214a"><th class="cellrowborder" valign="top" width="28.752875287528752%" id="mcps1.1.5.1.1"><p id="a40514c6d9b254dd9a909afef33a3fc5a"><a name="a40514c6d9b254dd9a909afef33a3fc5a"></a><a name="a40514c6d9b254dd9a909afef33a3fc5a"></a>Method</p>
</th>
<th class="cellrowborder" valign="top" width="23.752375237523754%" id="mcps1.1.5.1.2"><p id="a0806806107ac4bafbe3e83621f405067"><a name="a0806806107ac4bafbe3e83621f405067"></a><a name="a0806806107ac4bafbe3e83621f405067"></a>Description</p>
</th>
<th class="cellrowborder" valign="top" width="23.402340234023406%" id="mcps1.1.5.1.3"><p id="ac7a3797a9c90469190244c49d854a597"><a name="ac7a3797a9c90469190244c49d854a597"></a><a name="ac7a3797a9c90469190244c49d854a597"></a>Parameter Type</p>
</th>
<th class="cellrowborder" valign="top" width="24.092409240924095%" id="mcps1.1.5.1.4"><p id="ac7fc2d995b384ffda0a43f7858548f5e"><a name="ac7fc2d995b384ffda0a43f7858548f5e"></a><a name="ac7fc2d995b384ffda0a43f7858548f5e"></a>Return Value</p>
</th>
</tr>
</thead>
<tbody><tr id="r86b8156b7bb74278b3bf245ca843ca21"><td class="cellrowborder" valign="top" width="28.752875287528752%" headers="mcps1.1.5.1.1 "><p id="ac1077331263249bd9f26c0ba144ae896"><a name="ac1077331263249bd9f26c0ba144ae896"></a><a name="ac1077331263249bd9f26c0ba144ae896"></a>fitBounds(bounds)</p>
</td>
<td class="cellrowborder" valign="top" width="23.752375237523754%" headers="mcps1.1.5.1.2 "><p id="a6fef66ba78c24fbd9516b0f403e06079"><a name="a6fef66ba78c24fbd9516b0f403e06079"></a><a name="a6fef66ba78c24fbd9516b0f403e06079"></a>Sets the map display area.</p>
</td>
<td class="cellrowborder" valign="top" width="23.402340234023406%" headers="mcps1.1.5.1.3 "><p id="a3eef106e2a414ff8a79560d81abcbfd9"><a name="a3eef106e2a414ff8a79560d81abcbfd9"></a><a name="a3eef106e2a414ff8a79560d81abcbfd9"></a><a href="js-params.md#sb6bca9c1a2f142d287414bceeabe54a9">LatLngBounds</a></p>
</td>
<td class="cellrowborder" valign="top" width="24.092409240924095%" headers="mcps1.1.5.1.4 "><p id="a9b0a3a10bf7b494f97df73aa4446b5a6"><a name="a9b0a3a10bf7b494f97df73aa4446b5a6"></a><a name="a9b0a3a10bf7b494f97df73aa4446b5a6"></a>-</p>
</td>
</tr>
<tr id="r706d58daadf54313a8608940c9a61cd4"><td class="cellrowborder" valign="top" width="28.752875287528752%" headers="mcps1.1.5.1.1 "><p id="a477a88fc99e7438a93fe6299277b170a"><a name="a477a88fc99e7438a93fe6299277b170a"></a><a name="a477a88fc99e7438a93fe6299277b170a"></a>getBounds()</p>
</td>
<td class="cellrowborder" valign="top" width="23.752375237523754%" headers="mcps1.1.5.1.2 "><p id="a48e71ba536f94947bb5dded498eb3360"><a name="a48e71ba536f94947bb5dded498eb3360"></a><a name="a48e71ba536f94947bb5dded498eb3360"></a>Obtains the map display area.</p>
</td>
<td class="cellrowborder" valign="top" width="23.402340234023406%" headers="mcps1.1.5.1.3 "><p id="a7ff7609b838f4393b506ddcb29126161"><a name="a7ff7609b838f4393b506ddcb29126161"></a><a name="a7ff7609b838f4393b506ddcb29126161"></a>-</p>
</td>
<td class="cellrowborder" valign="top" width="24.092409240924095%" headers="mcps1.1.5.1.4 "><p id="a9a8531b66b0e4d9dbb2e62d307bf6417"><a name="a9a8531b66b0e4d9dbb2e62d307bf6417"></a><a name="a9a8531b66b0e4d9dbb2e62d307bf6417"></a>Map display area, which is of the <a href="js-params.md#sb6bca9c1a2f142d287414bceeabe54a9">LatLngBounds</a> type.</p>
</td>
</tr>
<tr id="rb5daace0a33c499a987de0497bd9b718"><td class="cellrowborder" valign="top" width="28.752875287528752%" headers="mcps1.1.5.1.1 "><p id="a02eec8456913427faa550b17e65ccc67"><a name="a02eec8456913427faa550b17e65ccc67"></a><a name="a02eec8456913427faa550b17e65ccc67"></a>getCenter()</p>
</td>
<td class="cellrowborder" valign="top" width="23.752375237523754%" headers="mcps1.1.5.1.2 "><p id="ad115ec73d27a42e2bd8fdb802afacbbf"><a name="ad115ec73d27a42e2bd8fdb802afacbbf"></a><a name="ad115ec73d27a42e2bd8fdb802afacbbf"></a>Obtains the coordinates of the map center point.</p>
</td>
<td class="cellrowborder" valign="top" width="23.402340234023406%" headers="mcps1.1.5.1.3 "><p id="ad4dd48cbf3e947a293ffa99ef4f2cd54"><a name="ad4dd48cbf3e947a293ffa99ef4f2cd54"></a><a name="ad4dd48cbf3e947a293ffa99ef4f2cd54"></a>-</p>
</td>
<td class="cellrowborder" valign="top" width="24.092409240924095%" headers="mcps1.1.5.1.4 "><p id="a087a457a18214d518a5a3212a529b116"><a name="a087a457a18214d518a5a3212a529b116"></a><a name="a087a457a18214d518a5a3212a529b116"></a>Longitude and latitude coordinates of the map center point, which is of the <a href="js-params.md#s1f33822192a04bbe9bd9de86a17460b1">LatLng</a> type. </p>
</td>
</tr>
<tr id="r42ab5266cbdd435d9859e7354111538e"><td class="cellrowborder" valign="top" width="28.752875287528752%" headers="mcps1.1.5.1.1 "><p id="ae2d61ada1ad2441298156d90320ed277"><a name="ae2d61ada1ad2441298156d90320ed277"></a><a name="ae2d61ada1ad2441298156d90320ed277"></a>getDiv()</p>
</td>
<td class="cellrowborder" valign="top" width="23.752375237523754%" headers="mcps1.1.5.1.2 "><p id="a14557425f2da4aec86f1ea135a4caa6d"><a name="a14557425f2da4aec86f1ea135a4caa6d"></a><a name="a14557425f2da4aec86f1ea135a4caa6d"></a>Obtains the container for loading a map.</p>
</td>
<td class="cellrowborder" valign="top" width="23.402340234023406%" headers="mcps1.1.5.1.3 "><p id="aa832cd329bfa456e8bb357ad601d99c9"><a name="aa832cd329bfa456e8bb357ad601d99c9"></a><a name="aa832cd329bfa456e8bb357ad601d99c9"></a>-</p>
</td>
<td class="cellrowborder" valign="top" width="24.092409240924095%" headers="mcps1.1.5.1.4 "><p id="acd2bfb1e39c546ae8c1fda8bab1e2ffc"><a name="acd2bfb1e39c546ae8c1fda8bab1e2ffc"></a><a name="acd2bfb1e39c546ae8c1fda8bab1e2ffc"></a>Div container.</p>
</td>
</tr>
<tr id="r9d1daa88f2ae4a04bcb072116b123530"><td class="cellrowborder" valign="top" width="28.752875287528752%" headers="mcps1.1.5.1.1 "><p id="aeb04e34e9a224a809219715ad73043e1"><a name="aeb04e34e9a224a809219715ad73043e1"></a><a name="aeb04e34e9a224a809219715ad73043e1"></a>getHeading()</p>
</td>
<td class="cellrowborder" valign="top" width="23.752375237523754%" headers="mcps1.1.5.1.2 "><p id="a7bd04ff01f4a481aba16305342db1a02"><a name="a7bd04ff01f4a481aba16305342db1a02"></a><a name="a7bd04ff01f4a481aba16305342db1a02"></a>Obtains the map heading.</p>
</td>
<td class="cellrowborder" valign="top" width="23.402340234023406%" headers="mcps1.1.5.1.3 "><p id="a2b61c9658d0a495d998123f0b117a0fb"><a name="a2b61c9658d0a495d998123f0b117a0fb"></a><a name="a2b61c9658d0a495d998123f0b117a0fb"></a>-</p>
</td>
<td class="cellrowborder" valign="top" width="24.092409240924095%" headers="mcps1.1.5.1.4 "><p id="a828afcf580604af4b0e23f3e3b696485"><a name="a828afcf580604af4b0e23f3e3b696485"></a><a name="a828afcf580604af4b0e23f3e3b696485"></a>Angle between the map heading and north direction, which is of the <strong id="b2034410429513"><a name="b2034410429513"></a><a name="b2034410429513"></a>Number</strong> type.</p>
</td>
</tr>
<tr id="r9c40a44e18234c7d8072451996950cff"><td class="cellrowborder" valign="top" width="28.752875287528752%" headers="mcps1.1.5.1.1 "><p id="a0f616b82355149ffa89723c55cfdb791"><a name="a0f616b82355149ffa89723c55cfdb791"></a><a name="a0f616b82355149ffa89723c55cfdb791"></a>getMapType()</p>
</td>
<td class="cellrowborder" valign="top" width="23.752375237523754%" headers="mcps1.1.5.1.2 "><p id="a0d3e69b77eee445c9ebd9a1044b9a440"><a name="a0d3e69b77eee445c9ebd9a1044b9a440"></a><a name="a0d3e69b77eee445c9ebd9a1044b9a440"></a>Obtains the Huawei map type.</p>
</td>
<td class="cellrowborder" valign="top" width="23.402340234023406%" headers="mcps1.1.5.1.3 "><p id="a74a42197fb304aa3a695ff7220d45f15"><a name="a74a42197fb304aa3a695ff7220d45f15"></a><a name="a74a42197fb304aa3a695ff7220d45f15"></a>-</p>
</td>
<td class="cellrowborder" valign="top" width="24.092409240924095%" headers="mcps1.1.5.1.4 "><p id="a8eeac43df68e4a9b9987f8fac1d779ab"><a name="a8eeac43df68e4a9b9987f8fac1d779ab"></a><a name="a8eeac43df68e4a9b9987f8fac1d779ab"></a>Map type, which is of the <strong id="b68891527614"><a name="b68891527614"></a><a name="b68891527614"></a>String</strong> type.</p>
</td>
</tr>
<tr id="r9c56ca0276cc47c3ac6f948b1419f0e6"><td class="cellrowborder" valign="top" width="28.752875287528752%" headers="mcps1.1.5.1.1 "><p id="af08bb545c1bb43f89de31a0008c94053"><a name="af08bb545c1bb43f89de31a0008c94053"></a><a name="af08bb545c1bb43f89de31a0008c94053"></a>getOpacity()</p>
</td>
<td class="cellrowborder" valign="top" width="23.752375237523754%" headers="mcps1.1.5.1.2 "><p id="ad32b6a454893494783e18ee653632843"><a name="ad32b6a454893494783e18ee653632843"></a><a name="ad32b6a454893494783e18ee653632843"></a>Obtains the opacity of a Huawei map.</p>
</td>
<td class="cellrowborder" valign="top" width="23.402340234023406%" headers="mcps1.1.5.1.3 "><p id="a1c207a5efe65412887fbd8e26bd33f4f"><a name="a1c207a5efe65412887fbd8e26bd33f4f"></a><a name="a1c207a5efe65412887fbd8e26bd33f4f"></a>-</p>
</td>
<td class="cellrowborder" valign="top" width="24.092409240924095%" headers="mcps1.1.5.1.4 "><p id="ae3656641c33a4c3db6c80763c083b25c"><a name="ae3656641c33a4c3db6c80763c083b25c"></a><a name="ae3656641c33a4c3db6c80763c083b25c"></a>Map opacity, which is of the <strong id="b4191112289"><a name="b4191112289"></a><a name="b4191112289"></a>Number</strong> type.</p>
</td>
</tr>
<tr id="r718b279e31164a7ca896c7154060aa7a"><td class="cellrowborder" valign="top" width="28.752875287528752%" headers="mcps1.1.5.1.1 "><p id="acc8f045aa9224955908b187938c2c4f9"><a name="acc8f045aa9224955908b187938c2c4f9"></a><a name="acc8f045aa9224955908b187938c2c4f9"></a>getPoi(pixel)</p>
</td>
<td class="cellrowborder" valign="top" width="23.752375237523754%" headers="mcps1.1.5.1.2 "><p id="a14153e8bca8b4abaab0763c13147a988"><a name="a14153e8bca8b4abaab0763c13147a988"></a><a name="a14153e8bca8b4abaab0763c13147a988"></a>Obtains the POI data of the current place.</p>
</td>
<td class="cellrowborder" valign="top" width="23.402340234023406%" headers="mcps1.1.5.1.3 "><p id="p1993815741"><a name="p1993815741"></a><a name="p1993815741"></a>[Number, Number]</p>
<p id="abaeb7c0eb9434169b4d82c581c2408d0"><a name="abaeb7c0eb9434169b4d82c581c2408d0"></a><a name="abaeb7c0eb9434169b4d82c581c2408d0"></a>Pixel coordinates on a map. The first number indicates the X coordinate and the second number indicates the Y coordinate.</p>
</td>
<td class="cellrowborder" valign="top" width="24.092409240924095%" headers="mcps1.1.5.1.4 "><p id="a8f514593a53e4ca3b3de42830094bdb6"><a name="a8f514593a53e4ca3b3de42830094bdb6"></a><a name="a8f514593a53e4ca3b3de42830094bdb6"></a>POI information about the current place, including the location and attributes. </p>
</td>
</tr>
<tr id="r7bffc24a0766456dbc24bcf1575b3a6e"><td class="cellrowborder" valign="top" width="28.752875287528752%" headers="mcps1.1.5.1.1 "><p id="a6a2ba11bd1ff4ddda321e56051499964"><a name="a6a2ba11bd1ff4ddda321e56051499964"></a><a name="a6a2ba11bd1ff4ddda321e56051499964"></a>getSize()</p>
</td>
<td class="cellrowborder" valign="top" width="23.752375237523754%" headers="mcps1.1.5.1.2 "><p id="a08cc5eaccb1644e39f4c31ce2f320eb7"><a name="a08cc5eaccb1644e39f4c31ce2f320eb7"></a><a name="a08cc5eaccb1644e39f4c31ce2f320eb7"></a>Obtains the map size.</p>
</td>
<td class="cellrowborder" valign="top" width="23.402340234023406%" headers="mcps1.1.5.1.3 "><p id="ab3bdf3c3c4a54717a7b2b4340852192e"><a name="ab3bdf3c3c4a54717a7b2b4340852192e"></a><a name="ab3bdf3c3c4a54717a7b2b4340852192e"></a>-</p>
</td>
<td class="cellrowborder" valign="top" width="24.092409240924095%" headers="mcps1.1.5.1.4 "><p id="a84db7e20e895452abbce60fe00565a8c"><a name="a84db7e20e895452abbce60fe00565a8c"></a><a name="a84db7e20e895452abbce60fe00565a8c"></a>A Number-type array in <em id="i17801347191114"><a name="i17801347191114"></a><a name="i17801347191114"></a>[width, height]</em> format.</p>
</td>
</tr>
<tr id="rea883b6677fe4dc68684a81a21faf9f1"><td class="cellrowborder" valign="top" width="28.752875287528752%" headers="mcps1.1.5.1.1 "><p id="a6fc2d7041cd84d0bb7670fa0afed0753"><a name="a6fc2d7041cd84d0bb7670fa0afed0753"></a><a name="a6fc2d7041cd84d0bb7670fa0afed0753"></a>getZoom()</p>
</td>
<td class="cellrowborder" valign="top" width="23.752375237523754%" headers="mcps1.1.5.1.2 "><p id="a137843771a4e42bab2616f9a69f736b4"><a name="a137843771a4e42bab2616f9a69f736b4"></a><a name="a137843771a4e42bab2616f9a69f736b4"></a>Obtains the zoom level of a map.</p>
</td>
<td class="cellrowborder" valign="top" width="23.402340234023406%" headers="mcps1.1.5.1.3 "><p id="a522ad3101db64126bb3e46a8ba52fe76"><a name="a522ad3101db64126bb3e46a8ba52fe76"></a><a name="a522ad3101db64126bb3e46a8ba52fe76"></a>-</p>
</td>
<td class="cellrowborder" valign="top" width="24.092409240924095%" headers="mcps1.1.5.1.4 "><p id="aab39ce4e2d9b42a9937d2119bfdd9567"><a name="aab39ce4e2d9b42a9937d2119bfdd9567"></a><a name="aab39ce4e2d9b42a9937d2119bfdd9567"></a>Map zoom level, which is of the <strong id="b0131173191317"><a name="b0131173191317"></a><a name="b0131173191317"></a>Number</strong> type.</p>
</td>
</tr>
<tr id="rd84050ba030e441e824e4dd47f3b526b"><td class="cellrowborder" valign="top" width="28.752875287528752%" headers="mcps1.1.5.1.1 "><p id="aa0626250a2b14bd2807b62027ff3e7e9"><a name="aa0626250a2b14bd2807b62027ff3e7e9"></a><a name="aa0626250a2b14bd2807b62027ff3e7e9"></a>on(event, callback)</p>
</td>
<td class="cellrowborder" valign="top" width="23.752375237523754%" headers="mcps1.1.5.1.2 "><p id="ab1cdd4832c7f4a23ade1b9fce5153a41"><a name="ab1cdd4832c7f4a23ade1b9fce5153a41"></a><a name="ab1cdd4832c7f4a23ade1b9fce5153a41"></a>Sets a custom function to be called when an event is triggered.</p>
</td>
<td class="cellrowborder" valign="top" width="23.402340234023406%" headers="mcps1.1.5.1.3 "><a name="ue6c0356770274354b06d2d54076b7635"></a><a name="ue6c0356770274354b06d2d54076b7635"></a><ul id="ue6c0356770274354b06d2d54076b7635"><li><strong id="b5111154218417"><a name="b5111154218417"></a><a name="b5111154218417"></a>event</strong>: event, which is of the <strong id="b13114154217420"><a name="b13114154217420"></a><a name="b13114154217420"></a>String</strong> type. For details, please refer to <a href="#sdd35559e11f04b6a917da42401515a0e">Events</a>.</li><li><strong id="b51916548417"><a name="b51916548417"></a><a name="b51916548417"></a>callback</strong>: callback function triggered by the event.</li></ul>
</td>
<td class="cellrowborder" valign="top" width="24.092409240924095%" headers="mcps1.1.5.1.4 "><p id="a793919e367c94d2d8e835c6e30821e11"><a name="a793919e367c94d2d8e835c6e30821e11"></a><a name="a793919e367c94d2d8e835c6e30821e11"></a>-</p>
</td>
</tr>
<tr id="rcb7eb766abef4ddb959f3e0b84543235"><td class="cellrowborder" valign="top" width="28.752875287528752%" headers="mcps1.1.5.1.1 "><p id="aadbaa8d75bc546bebebc9d5706d07203"><a name="aadbaa8d75bc546bebebc9d5706d07203"></a><a name="aadbaa8d75bc546bebebc9d5706d07203"></a>onCenterChanged(callback)</p>
</td>
<td class="cellrowborder" valign="top" width="23.752375237523754%" headers="mcps1.1.5.1.2 "><p id="aff4c3c0694814b158aba7b7fb42fb2d9"><a name="aff4c3c0694814b158aba7b7fb42fb2d9"></a><a name="aff4c3c0694814b158aba7b7fb42fb2d9"></a>Sets a custom function called when the map center changes.</p>
</td>
<td class="cellrowborder" valign="top" width="23.402340234023406%" headers="mcps1.1.5.1.3 "><p id="p19340155983"><a name="p19340155983"></a><a name="p19340155983"></a>Function</p>
<p id="adc1e6485d58f4db9ba738f5a1d4f091c"><a name="adc1e6485d58f4db9ba738f5a1d4f091c"></a><a name="adc1e6485d58f4db9ba738f5a1d4f091c"></a>Custom callback function.</p>
</td>
<td class="cellrowborder" valign="top" width="24.092409240924095%" headers="mcps1.1.5.1.4 "><p id="a16be81504fc742f99d0f972917fb0fe9"><a name="a16be81504fc742f99d0f972917fb0fe9"></a><a name="a16be81504fc742f99d0f972917fb0fe9"></a>-</p>
</td>
</tr>
<tr id="r70b58cac998942ce9d96f1d044c44e9c"><td class="cellrowborder" valign="top" width="28.752875287528752%" headers="mcps1.1.5.1.1 "><p id="a6fa4d8fe6cc44daaa6925156f627cdd5"><a name="a6fa4d8fe6cc44daaa6925156f627cdd5"></a><a name="a6fa4d8fe6cc44daaa6925156f627cdd5"></a>onHeadingChanged(callback)</p>
</td>
<td class="cellrowborder" valign="top" width="23.752375237523754%" headers="mcps1.1.5.1.2 "><p id="a1013cc592e5b43b49971d9e4088ce8ad"><a name="a1013cc592e5b43b49971d9e4088ce8ad"></a><a name="a1013cc592e5b43b49971d9e4088ce8ad"></a>Sets a custom function called when the map heading changes.</p>
</td>
<td class="cellrowborder" valign="top" width="23.402340234023406%" headers="mcps1.1.5.1.3 "><p id="p174831614082"><a name="p174831614082"></a><a name="p174831614082"></a>Function</p>
<p id="a827bb434ca274deca9841623deb5b3a6"><a name="a827bb434ca274deca9841623deb5b3a6"></a><a name="a827bb434ca274deca9841623deb5b3a6"></a>Custom callback function. </p>
</td>
<td class="cellrowborder" valign="top" width="24.092409240924095%" headers="mcps1.1.5.1.4 "><p id="a83110f26ad284418ac76023bdd72bc47"><a name="a83110f26ad284418ac76023bdd72bc47"></a><a name="a83110f26ad284418ac76023bdd72bc47"></a>-</p>
</td>
</tr>
<tr id="r197f3aad82894d1e80eed99d7a8f580b"><td class="cellrowborder" valign="top" width="28.752875287528752%" headers="mcps1.1.5.1.1 "><p id="adebdd7d12c8347ce9914664ba07c91a6"><a name="adebdd7d12c8347ce9914664ba07c91a6"></a><a name="adebdd7d12c8347ce9914664ba07c91a6"></a>onZoomChanged(callback)</p>
</td>
<td class="cellrowborder" valign="top" width="23.752375237523754%" headers="mcps1.1.5.1.2 "><p id="a9548ee2fcd2d41d1b5f1026664fc8767"><a name="a9548ee2fcd2d41d1b5f1026664fc8767"></a><a name="a9548ee2fcd2d41d1b5f1026664fc8767"></a>Sets a custom function called when the map zoom level changes.</p>
</td>
<td class="cellrowborder" valign="top" width="23.402340234023406%" headers="mcps1.1.5.1.3 "><p id="p53661818187"><a name="p53661818187"></a><a name="p53661818187"></a>Function</p>
<p id="ae4801296a2f84566a1ba5acce73d63b5"><a name="ae4801296a2f84566a1ba5acce73d63b5"></a><a name="ae4801296a2f84566a1ba5acce73d63b5"></a>Custom callback function. </p>
</td>
<td class="cellrowborder" valign="top" width="24.092409240924095%" headers="mcps1.1.5.1.4 "><p id="a2e9c2a0944b747d0a3a768150892644f"><a name="a2e9c2a0944b747d0a3a768150892644f"></a><a name="a2e9c2a0944b747d0a3a768150892644f"></a>-</p>
</td>
</tr>
<tr id="r505c161eacd64e089803f8cb9184e816"><td class="cellrowborder" valign="top" width="28.752875287528752%" headers="mcps1.1.5.1.1 "><p id="a3ea243e84ede4db4aec02ddf5189eaa1"><a name="a3ea243e84ede4db4aec02ddf5189eaa1"></a><a name="a3ea243e84ede4db4aec02ddf5189eaa1"></a>panBy(x, y)</p>
</td>
<td class="cellrowborder" valign="top" width="23.752375237523754%" headers="mcps1.1.5.1.2 "><p id="aa94cffa274ff4386af055aada2da0ff5"><a name="aa94cffa274ff4386af055aada2da0ff5"></a><a name="aa94cffa274ff4386af055aada2da0ff5"></a>Pans the map center point by (x, y).</p>
</td>
<td class="cellrowborder" valign="top" width="23.402340234023406%" headers="mcps1.1.5.1.3 "><a name="ul6696135719578"></a><a name="ul6696135719578"></a><ul id="ul6696135719578"><li><strong id="b944714393510"><a name="b944714393510"></a><a name="b944714393510"></a>x</strong>: number of panned pixels on the x axis. </li><li><strong id="b5155541057"><a name="b5155541057"></a><a name="b5155541057"></a>y</strong>: number of panned pixels on the y axis. </li></ul>
</td>
<td class="cellrowborder" valign="top" width="24.092409240924095%" headers="mcps1.1.5.1.4 "><p id="acc8c910692214d059adda7381e6d018d"><a name="acc8c910692214d059adda7381e6d018d"></a><a name="acc8c910692214d059adda7381e6d018d"></a>-</p>
</td>
</tr>
<tr id="r5395e0a5972943ccbbd29cedcb07aafe"><td class="cellrowborder" valign="top" width="28.752875287528752%" headers="mcps1.1.5.1.1 "><p id="a5adf17ea84494500a76136aebe61dcc0"><a name="a5adf17ea84494500a76136aebe61dcc0"></a><a name="a5adf17ea84494500a76136aebe61dcc0"></a>panTo(latLng)</p>
</td>
<td class="cellrowborder" valign="top" width="23.752375237523754%" headers="mcps1.1.5.1.2 "><p id="ab6999fbe77ec42999e3d618c29e98609"><a name="ab6999fbe77ec42999e3d618c29e98609"></a><a name="ab6999fbe77ec42999e3d618c29e98609"></a>Moves the map center to a specified coordinate point.</p>
</td>
<td class="cellrowborder" valign="top" width="23.402340234023406%" headers="mcps1.1.5.1.3 "><p id="aa280f791fe084730a184924b5a43abf0"><a name="aa280f791fe084730a184924b5a43abf0"></a><a name="aa280f791fe084730a184924b5a43abf0"></a><a href="js-params.md#s1f33822192a04bbe9bd9de86a17460b1">LatLng</a></p>
</td>
<td class="cellrowborder" valign="top" width="24.092409240924095%" headers="mcps1.1.5.1.4 "><p id="a39ee7387a3724f079b9c82eb44cd691f"><a name="a39ee7387a3724f079b9c82eb44cd691f"></a><a name="a39ee7387a3724f079b9c82eb44cd691f"></a>-</p>
</td>
</tr>
<tr id="rce0fba841ee244958b2469f9418fb9f0"><td class="cellrowborder" valign="top" width="28.752875287528752%" headers="mcps1.1.5.1.1 "><p id="a99c2efd6a45e462396f29a70e93904c6"><a name="a99c2efd6a45e462396f29a70e93904c6"></a><a name="a99c2efd6a45e462396f29a70e93904c6"></a>panToBounds(latLngBounds)</p>
</td>
<td class="cellrowborder" valign="top" width="23.752375237523754%" headers="mcps1.1.5.1.2 "><p id="acd6f35c4db49425eb44e9708a43e98a4"><a name="acd6f35c4db49425eb44e9708a43e98a4"></a><a name="acd6f35c4db49425eb44e9708a43e98a4"></a>Moves a map so that it contains a specified coordinate area.</p>
</td>
<td class="cellrowborder" valign="top" width="23.402340234023406%" headers="mcps1.1.5.1.3 "><p id="afed8903a17ce45ddadfd65521d36236f"><a name="afed8903a17ce45ddadfd65521d36236f"></a><a name="afed8903a17ce45ddadfd65521d36236f"></a><a href="js-params.md#sb6bca9c1a2f142d287414bceeabe54a9">LatLngBounds</a></p>
</td>
<td class="cellrowborder" valign="top" width="24.092409240924095%" headers="mcps1.1.5.1.4 "><p id="a1d9c561311ec4028a095478555f3e8f7"><a name="a1d9c561311ec4028a095478555f3e8f7"></a><a name="a1d9c561311ec4028a095478555f3e8f7"></a>-</p>
</td>
</tr>
<tr id="rfdd42f38cbff49268ad81af9bd6c660c"><td class="cellrowborder" valign="top" width="28.752875287528752%" headers="mcps1.1.5.1.1 "><p id="acb36457969c14c478e9254cce8225aa4"><a name="acb36457969c14c478e9254cce8225aa4"></a><a name="acb36457969c14c478e9254cce8225aa4"></a>setCenter(latlng)</p>
</td>
<td class="cellrowborder" valign="top" width="23.752375237523754%" headers="mcps1.1.5.1.2 "><p id="a4e7b3fe50d6244ecaf3581274789580a"><a name="a4e7b3fe50d6244ecaf3581274789580a"></a><a name="a4e7b3fe50d6244ecaf3581274789580a"></a>Sets the coordinates of the map center point.</p>
</td>
<td class="cellrowborder" valign="top" width="23.402340234023406%" headers="mcps1.1.5.1.3 "><p id="a5c326811f9624156b21de40e7741aae2"><a name="a5c326811f9624156b21de40e7741aae2"></a><a name="a5c326811f9624156b21de40e7741aae2"></a><a href="js-params.md#s1f33822192a04bbe9bd9de86a17460b1">LatLng</a></p>
</td>
<td class="cellrowborder" valign="top" width="24.092409240924095%" headers="mcps1.1.5.1.4 "><p id="ab7bdd727abb5489b8134b9621f1ff1c1"><a name="ab7bdd727abb5489b8134b9621f1ff1c1"></a><a name="ab7bdd727abb5489b8134b9621f1ff1c1"></a>-</p>
</td>
</tr>
<tr id="r5c964edbedf34a498667adfe5c404d48"><td class="cellrowborder" valign="top" width="28.752875287528752%" headers="mcps1.1.5.1.1 "><p id="a2437f49bb07d4c8a88f22040911f2e04"><a name="a2437f49bb07d4c8a88f22040911f2e04"></a><a name="a2437f49bb07d4c8a88f22040911f2e04"></a>setCopyrightControl(enabled)</p>
</td>
<td class="cellrowborder" valign="top" width="23.752375237523754%" headers="mcps1.1.5.1.2 "><p id="ae79e3cc11da044f09753ea473708dc7f"><a name="ae79e3cc11da044f09753ea473708dc7f"></a><a name="ae79e3cc11da044f09753ea473708dc7f"></a>Sets whether to display the copyright information.</p>
</td>
<td class="cellrowborder" valign="top" width="23.402340234023406%" headers="mcps1.1.5.1.3 "><p id="a9fc4a17511224c18a61e5ab51dd960f8"><a name="a9fc4a17511224c18a61e5ab51dd960f8"></a><a name="a9fc4a17511224c18a61e5ab51dd960f8"></a>Boolean</p>
<p id="acf0ee192f365418986c25052368ac454"><a name="acf0ee192f365418986c25052368ac454"></a><a name="acf0ee192f365418986c25052368ac454"></a><strong id="b19931528192212"><a name="b19931528192212"></a><a name="b19931528192212"></a>true</strong>: yes; <strong id="b179981289225"><a name="b179981289225"></a><a name="b179981289225"></a>false</strong>: no.</p>
</td>
<td class="cellrowborder" valign="top" width="24.092409240924095%" headers="mcps1.1.5.1.4 "><p id="a3f8e58ec9f2b4ceb8450e3a1a241198c"><a name="a3f8e58ec9f2b4ceb8450e3a1a241198c"></a><a name="a3f8e58ec9f2b4ceb8450e3a1a241198c"></a>-</p>
</td>
</tr>
<tr id="r13b440ee12aa45a7abe7e9faef19d289"><td class="cellrowborder" valign="top" width="28.752875287528752%" headers="mcps1.1.5.1.1 "><p id="a78a6e2fc97124dd5a78ee0f5acf4eb7a"><a name="a78a6e2fc97124dd5a78ee0f5acf4eb7a"></a><a name="a78a6e2fc97124dd5a78ee0f5acf4eb7a"></a>setHeading(heading)</p>
</td>
<td class="cellrowborder" valign="top" width="23.752375237523754%" headers="mcps1.1.5.1.2 "><p id="a788cee5c9abe4f01ab9d3d12e56fd423"><a name="a788cee5c9abe4f01ab9d3d12e56fd423"></a><a name="a788cee5c9abe4f01ab9d3d12e56fd423"></a>Sets the map heading.</p>
</td>
<td class="cellrowborder" valign="top" width="23.402340234023406%" headers="mcps1.1.5.1.3 "><p id="p12735527111012"><a name="p12735527111012"></a><a name="p12735527111012"></a>Number</p>
<p id="ab2403dd094b745b89634c8808e1d1fe9"><a name="ab2403dd094b745b89634c8808e1d1fe9"></a><a name="ab2403dd094b745b89634c8808e1d1fe9"></a>Angle between the map heading and the north. The value ranges from 0 to 360.</p>
</td>
<td class="cellrowborder" valign="top" width="24.092409240924095%" headers="mcps1.1.5.1.4 "><p id="abff97a9f98df422fb833b8b14cfbbe95"><a name="abff97a9f98df422fb833b8b14cfbbe95"></a><a name="abff97a9f98df422fb833b8b14cfbbe95"></a>-</p>
</td>
</tr>
<tr id="rc689c49794ca4cefb13fa2c8637d2add"><td class="cellrowborder" valign="top" width="28.752875287528752%" headers="mcps1.1.5.1.1 "><p id="p882775912212"><a name="p882775912212"></a><a name="p882775912212"></a>setLocationControl</p>
</td>
<td class="cellrowborder" valign="top" width="23.752375237523754%" headers="mcps1.1.5.1.2 "><p id="a190c790bc3844c2eace4c4e26f76bd6b"><a name="a190c790bc3844c2eace4c4e26f76bd6b"></a><a name="a190c790bc3844c2eace4c4e26f76bd6b"></a>Sets whether to display the current-location icon.</p>
</td>
<td class="cellrowborder" valign="top" width="23.402340234023406%" headers="mcps1.1.5.1.3 "><p id="aed566797989b41a7b780e705c366b057"><a name="aed566797989b41a7b780e705c366b057"></a><a name="aed566797989b41a7b780e705c366b057"></a>Boolean</p>
<p id="a458976c1a3f84508ac2b697d94b4fe65"><a name="a458976c1a3f84508ac2b697d94b4fe65"></a><a name="a458976c1a3f84508ac2b697d94b4fe65"></a><strong id="b75991452162614"><a name="b75991452162614"></a><a name="b75991452162614"></a>true</strong>: yes; <strong id="b1959919527262"><a name="b1959919527262"></a><a name="b1959919527262"></a>false</strong>: no.</p>
</td>
<td class="cellrowborder" valign="top" width="24.092409240924095%" headers="mcps1.1.5.1.4 "><p id="a57c225334f8447958654445211c087bc"><a name="a57c225334f8447958654445211c087bc"></a><a name="a57c225334f8447958654445211c087bc"></a>-</p>
</td>
</tr>
<tr id="r47265b0bc9714caca846d9c934311837"><td class="cellrowborder" valign="top" width="28.752875287528752%" headers="mcps1.1.5.1.1 "><p id="p891624212220"><a name="p891624212220"></a><a name="p891624212220"></a>setNavigationControl</p>
</td>
<td class="cellrowborder" valign="top" width="23.752375237523754%" headers="mcps1.1.5.1.2 "><p id="p9720184419222"><a name="p9720184419222"></a><a name="p9720184419222"></a>Sets whether to display the pan button. </p>
</td>
<td class="cellrowborder" valign="top" width="23.402340234023406%" headers="mcps1.1.5.1.3 "><p id="ad8943e7b819a4c1f87a4c8ba51fcee46"><a name="ad8943e7b819a4c1f87a4c8ba51fcee46"></a><a name="ad8943e7b819a4c1f87a4c8ba51fcee46"></a>Boolean</p>
<p id="a94a0c74166fc46399e990587228dbf8b"><a name="a94a0c74166fc46399e990587228dbf8b"></a><a name="a94a0c74166fc46399e990587228dbf8b"></a><strong id="b1998572423"><a name="b1998572423"></a><a name="b1998572423"></a>true</strong>: yes; <strong id="b1113454175"><a name="b1113454175"></a><a name="b1113454175"></a>false</strong>: no.</p>
</td>
<td class="cellrowborder" valign="top" width="24.092409240924095%" headers="mcps1.1.5.1.4 "><p id="a80c8152564e4426ba775fa66eae49fad"><a name="a80c8152564e4426ba775fa66eae49fad"></a><a name="a80c8152564e4426ba775fa66eae49fad"></a>-</p>
</td>
</tr>
<tr id="rb3c0f8f9b7544919a37e5f41daae0ccc"><td class="cellrowborder" valign="top" width="28.752875287528752%" headers="mcps1.1.5.1.1 "><p id="a5017f116fc3e41939da6ffec407dcd34"><a name="a5017f116fc3e41939da6ffec407dcd34"></a><a name="a5017f116fc3e41939da6ffec407dcd34"></a>setOpacity(opacity)</p>
</td>
<td class="cellrowborder" valign="top" width="23.752375237523754%" headers="mcps1.1.5.1.2 "><p id="af9a03a4f628f47689035b72d9eb71636"><a name="af9a03a4f628f47689035b72d9eb71636"></a><a name="af9a03a4f628f47689035b72d9eb71636"></a>Sets the map opacity.</p>
</td>
<td class="cellrowborder" valign="top" width="23.402340234023406%" headers="mcps1.1.5.1.3 "><p id="p11103440191019"><a name="p11103440191019"></a><a name="p11103440191019"></a>Number</p>
<p id="ae9c8ed17c6394f69b5c0a625bca8e24f"><a name="ae9c8ed17c6394f69b5c0a625bca8e24f"></a><a name="ae9c8ed17c6394f69b5c0a625bca8e24f"></a>The value ranges from 0 to 1.</p>
</td>
<td class="cellrowborder" valign="top" width="24.092409240924095%" headers="mcps1.1.5.1.4 "><p id="a5088b2e23a444ecaa8bc7261f0149b14"><a name="a5088b2e23a444ecaa8bc7261f0149b14"></a><a name="a5088b2e23a444ecaa8bc7261f0149b14"></a>-</p>
</td>
</tr>
<tr id="row5419163712712"><td class="cellrowborder" valign="top" width="28.752875287528752%" headers="mcps1.1.5.1.1 "><p id="p6573949278"><a name="p6573949278"></a><a name="p6573949278"></a>setPinchRotate(disabled)</p>
</td>
<td class="cellrowborder" valign="top" width="23.752375237523754%" headers="mcps1.1.5.1.2 "><p id="p1042018371374"><a name="p1042018371374"></a><a name="p1042018371374"></a>Sets whether the map can be rotated with two fingers. </p>
</td>
<td class="cellrowborder" valign="top" width="23.402340234023406%" headers="mcps1.1.5.1.3 "><p id="p146897521813"><a name="p146897521813"></a><a name="p146897521813"></a>Boolean</p>
<p id="p166897521781"><a name="p166897521781"></a><a name="p166897521781"></a><strong id="b1910185284710"><a name="b1910185284710"></a><a name="b1910185284710"></a>true</strong>: yes; <strong id="b992112530474"><a name="b992112530474"></a><a name="b992112530474"></a>false</strong>: no.</p>
</td>
<td class="cellrowborder" valign="top" width="24.092409240924095%" headers="mcps1.1.5.1.4 "><p id="p3421163715712"><a name="p3421163715712"></a><a name="p3421163715712"></a>-</p>
</td>
</tr>
<tr id="re9f9683f0efc4a9ab83bc5bd805e351c"><td class="cellrowborder" valign="top" width="28.752875287528752%" headers="mcps1.1.5.1.1 "><p id="aeffd0e81b386454a987855d65dff3e77"><a name="aeffd0e81b386454a987855d65dff3e77"></a><a name="aeffd0e81b386454a987855d65dff3e77"></a>setPresetStyleId(presetStyleId)</p>
</td>
<td class="cellrowborder" valign="top" width="23.752375237523754%" headers="mcps1.1.5.1.2 "><p id="aee14db6a0b374ded9affdd14817b04d3"><a name="aee14db6a0b374ded9affdd14817b04d3"></a><a name="aee14db6a0b374ded9affdd14817b04d3"></a>Sets the preset map style.</p>
</td>
<td class="cellrowborder" valign="top" width="23.402340234023406%" headers="mcps1.1.5.1.3 "><p id="p129595475106"><a name="p129595475106"></a><a name="p129595475106"></a>String</p>
<p id="a8ac251e4d97547beacba5c9f867de2d1"><a name="a8ac251e4d97547beacba5c9f867de2d1"></a><a name="a8ac251e4d97547beacba5c9f867de2d1"></a>The options include <strong id="b1577923312618"><a name="b1577923312618"></a><a name="b1577923312618"></a>standard</strong>, <strong id="b45451236192620"><a name="b45451236192620"></a><a name="b45451236192620"></a>night</strong>, and <strong id="b3842538102616"><a name="b3842538102616"></a><a name="b3842538102616"></a>simple</strong>.</p>
</td>
<td class="cellrowborder" valign="top" width="24.092409240924095%" headers="mcps1.1.5.1.4 "><p id="a1fc2e42eda8c4959abebc52523dc3eaf"><a name="a1fc2e42eda8c4959abebc52523dc3eaf"></a><a name="a1fc2e42eda8c4959abebc52523dc3eaf"></a>-</p>
</td>
</tr>
<tr id="rc3a5189ee42c40f98651ec3628b8c3dc"><td class="cellrowborder" valign="top" width="28.752875287528752%" headers="mcps1.1.5.1.1 "><p id="a972395d66dab47f89ba25c9b2a582a24"><a name="a972395d66dab47f89ba25c9b2a582a24"></a><a name="a972395d66dab47f89ba25c9b2a582a24"></a>setRotateControl(enabled)</p>
</td>
<td class="cellrowborder" valign="top" width="23.752375237523754%" headers="mcps1.1.5.1.2 "><p id="afefe6f423cf8409bbceac18e51cf1451"><a name="afefe6f423cf8409bbceac18e51cf1451"></a><a name="afefe6f423cf8409bbceac18e51cf1451"></a>Sets whether to display the compass.</p>
</td>
<td class="cellrowborder" valign="top" width="23.402340234023406%" headers="mcps1.1.5.1.3 "><p id="ae9e9fd9780d7476c9c95a74391e5cd6d"><a name="ae9e9fd9780d7476c9c95a74391e5cd6d"></a><a name="ae9e9fd9780d7476c9c95a74391e5cd6d"></a>Boolean</p>
<p id="acf953279b8644407a1ddc8789c7c323f"><a name="acf953279b8644407a1ddc8789c7c323f"></a><a name="acf953279b8644407a1ddc8789c7c323f"></a><strong id="b757757343"><a name="b757757343"></a><a name="b757757343"></a>true</strong>: yes; <strong id="b1097070322"><a name="b1097070322"></a><a name="b1097070322"></a>false</strong>: no.</p>
</td>
<td class="cellrowborder" valign="top" width="24.092409240924095%" headers="mcps1.1.5.1.4 "><p id="ab9afa189f4384a779032a691dce8e7e9"><a name="ab9afa189f4384a779032a691dce8e7e9"></a><a name="ab9afa189f4384a779032a691dce8e7e9"></a>-</p>
</td>
</tr>
<tr id="rf77572ba04c145f5b75d90a255095622"><td class="cellrowborder" valign="top" width="28.752875287528752%" headers="mcps1.1.5.1.1 "><p id="aac937f3393764daeb54176d55b00e8e3"><a name="aac937f3393764daeb54176d55b00e8e3"></a><a name="aac937f3393764daeb54176d55b00e8e3"></a>setScaleControl(enabled)</p>
</td>
<td class="cellrowborder" valign="top" width="23.752375237523754%" headers="mcps1.1.5.1.2 "><p id="a9b460a6647f1453e858ff76c81aec042"><a name="a9b460a6647f1453e858ff76c81aec042"></a><a name="a9b460a6647f1453e858ff76c81aec042"></a>Sets whether to display the scale. </p>
</td>
<td class="cellrowborder" valign="top" width="23.402340234023406%" headers="mcps1.1.5.1.3 "><p id="a3fa79c69fe5640ca823a966b42d8a5cf"><a name="a3fa79c69fe5640ca823a966b42d8a5cf"></a><a name="a3fa79c69fe5640ca823a966b42d8a5cf"></a>Boolean</p>
<p id="aa147bad74c7c4cb5aa8682ff1efcd53a"><a name="aa147bad74c7c4cb5aa8682ff1efcd53a"></a><a name="aa147bad74c7c4cb5aa8682ff1efcd53a"></a><strong id="b42711417122811"><a name="b42711417122811"></a><a name="b42711417122811"></a>true</strong>: yes; <strong id="b112777172281"><a name="b112777172281"></a><a name="b112777172281"></a>false</strong>: no.</p>
</td>
<td class="cellrowborder" valign="top" width="24.092409240924095%" headers="mcps1.1.5.1.4 "><p id="a070033282c3845b6ac31a5a74363a6d7"><a name="a070033282c3845b6ac31a5a74363a6d7"></a><a name="a070033282c3845b6ac31a5a74363a6d7"></a>-</p>
</td>
</tr>
<tr id="r19a07517ee9742d4b97505d55f5c64a1"><td class="cellrowborder" valign="top" width="28.752875287528752%" headers="mcps1.1.5.1.1 "><p id="af287e5e936114be8b8642572db86b5ba"><a name="af287e5e936114be8b8642572db86b5ba"></a><a name="af287e5e936114be8b8642572db86b5ba"></a>setStyle(styles)</p>
</td>
<td class="cellrowborder" valign="top" width="23.752375237523754%" headers="mcps1.1.5.1.2 "><p id="a9ba2621d01914c72adfa9963ef1ee7ba"><a name="a9ba2621d01914c72adfa9963ef1ee7ba"></a><a name="a9ba2621d01914c72adfa9963ef1ee7ba"></a>Sets a custom map style using the JSON file.</p>
</td>
<td class="cellrowborder" valign="top" width="23.402340234023406%" headers="mcps1.1.5.1.3 "><p id="a6a3b31cbc03d47008522ad7cca1a69e5"><a name="a6a3b31cbc03d47008522ad7cca1a69e5"></a><a name="a6a3b31cbc03d47008522ad7cca1a69e5"></a>JSON array</p>
</td>
<td class="cellrowborder" valign="top" width="24.092409240924095%" headers="mcps1.1.5.1.4 "><p id="aa15450c96fb044498631a30b21a23275"><a name="aa15450c96fb044498631a30b21a23275"></a><a name="aa15450c96fb044498631a30b21a23275"></a>-</p>
</td>
</tr>
<tr id="r8da55598a6bf45df878a6b7e5a252adb"><td class="cellrowborder" valign="top" width="28.752875287528752%" headers="mcps1.1.5.1.1 "><p id="ae9942cf4fc744d2c98be9a07e6cf10f4"><a name="ae9942cf4fc744d2c98be9a07e6cf10f4"></a><a name="ae9942cf4fc744d2c98be9a07e6cf10f4"></a>setTitle(title)</p>
</td>
<td class="cellrowborder" valign="top" width="23.752375237523754%" headers="mcps1.1.5.1.2 "><p id="ab578ad56471a4bbeb2a36b0eda4e9935"><a name="ab578ad56471a4bbeb2a36b0eda4e9935"></a><a name="ab578ad56471a4bbeb2a36b0eda4e9935"></a>Sets the prompt information for the container where the map is located.</p>
</td>
<td class="cellrowborder" valign="top" width="23.402340234023406%" headers="mcps1.1.5.1.3 "><p id="a724a7e99242f471a848923e1498ce2f7"><a name="a724a7e99242f471a848923e1498ce2f7"></a><a name="a724a7e99242f471a848923e1498ce2f7"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="24.092409240924095%" headers="mcps1.1.5.1.4 "><p id="af4fef9a58b754f3d9373f9011a75388f"><a name="af4fef9a58b754f3d9373f9011a75388f"></a><a name="af4fef9a58b754f3d9373f9011a75388f"></a>-</p>
</td>
</tr>
<tr id="r6ad1e43e93bb49ee96a4569bc342fa0f"><td class="cellrowborder" valign="top" width="28.752875287528752%" headers="mcps1.1.5.1.1 "><p id="a7063b05b8a7241fbb166202329928d81"><a name="a7063b05b8a7241fbb166202329928d81"></a><a name="a7063b05b8a7241fbb166202329928d81"></a>setZoom(zoom)</p>
</td>
<td class="cellrowborder" valign="top" width="23.752375237523754%" headers="mcps1.1.5.1.2 "><p id="ab819292f64fd45289022ab03d42e25c3"><a name="ab819292f64fd45289022ab03d42e25c3"></a><a name="ab819292f64fd45289022ab03d42e25c3"></a>Sets the zoom level of a map.</p>
</td>
<td class="cellrowborder" valign="top" width="23.402340234023406%" headers="mcps1.1.5.1.3 "><p id="p1382143782512"><a name="p1382143782512"></a><a name="p1382143782512"></a>Number</p>
<p id="aaf93cad68e7545b8a8006ccacf71baee"><a name="aaf93cad68e7545b8a8006ccacf71baee"></a><a name="aaf93cad68e7545b8a8006ccacf71baee"></a>The value is between <strong id="b694613311086"><a name="b694613311086"></a><a name="b694613311086"></a>minZoom</strong> to <strong id="b51621634688"><a name="b51621634688"></a><a name="b51621634688"></a>maxZoom</strong>.</p>
</td>
<td class="cellrowborder" valign="top" width="24.092409240924095%" headers="mcps1.1.5.1.4 "><p id="ac363ac044bf541b4aad043c68b9ef637"><a name="ac363ac044bf541b4aad043c68b9ef637"></a><a name="ac363ac044bf541b4aad043c68b9ef637"></a>-</p>
</td>
</tr>
<tr id="r215adba1522d42b988d54e202d061046"><td class="cellrowborder" valign="top" width="28.752875287528752%" headers="mcps1.1.5.1.1 "><p id="ab2295607970a45afaaeb903d130513f5"><a name="ab2295607970a45afaaeb903d130513f5"></a><a name="ab2295607970a45afaaeb903d130513f5"></a>setZoomControl(enabled)</p>
</td>
<td class="cellrowborder" valign="top" width="23.752375237523754%" headers="mcps1.1.5.1.2 "><p id="a26c90571bd0840639acc7b16cfd885cf"><a name="a26c90571bd0840639acc7b16cfd885cf"></a><a name="a26c90571bd0840639acc7b16cfd885cf"></a>Sets whether to display the zoom button. </p>
</td>
<td class="cellrowborder" valign="top" width="23.402340234023406%" headers="mcps1.1.5.1.3 "><p id="ad6a7eee2def44c378e5a33790c6c806c"><a name="ad6a7eee2def44c378e5a33790c6c806c"></a><a name="ad6a7eee2def44c378e5a33790c6c806c"></a>Boolean</p>
<p id="a2da9e7b035ed41c98de559d66d04aa67"><a name="a2da9e7b035ed41c98de559d66d04aa67"></a><a name="a2da9e7b035ed41c98de559d66d04aa67"></a><strong id="b16617131422918"><a name="b16617131422918"></a><a name="b16617131422918"></a>true</strong>: yes; <strong id="b2623171414297"><a name="b2623171414297"></a><a name="b2623171414297"></a>false</strong>: no.</p>
</td>
<td class="cellrowborder" valign="top" width="24.092409240924095%" headers="mcps1.1.5.1.4 "><p id="aa5e806b966954bddb7b34df4604b55db"><a name="aa5e806b966954bddb7b34df4604b55db"></a><a name="aa5e806b966954bddb7b34df4604b55db"></a>-</p>
</td>
</tr>
<tr id="rd98b48b42b52433e8ee21f749360b148"><td class="cellrowborder" valign="top" width="28.752875287528752%" headers="mcps1.1.5.1.1 "><p id="a7943094dc8d5400386540cbb3c8bad81"><a name="a7943094dc8d5400386540cbb3c8bad81"></a><a name="a7943094dc8d5400386540cbb3c8bad81"></a>setZoomSlider(enabled)</p>
</td>
<td class="cellrowborder" valign="top" width="23.752375237523754%" headers="mcps1.1.5.1.2 "><p id="a3006354242df4093acc3b163e234fd67"><a name="a3006354242df4093acc3b163e234fd67"></a><a name="a3006354242df4093acc3b163e234fd67"></a>Sets whether to display the zoom slider.</p>
</td>
<td class="cellrowborder" valign="top" width="23.402340234023406%" headers="mcps1.1.5.1.3 "><p id="a491f0a7354b14608aa411f50e30f4cd9"><a name="a491f0a7354b14608aa411f50e30f4cd9"></a><a name="a491f0a7354b14608aa411f50e30f4cd9"></a>Boolean</p>
<p id="a6cb3f6a6e7ab4b55b4cdbd5311b97725"><a name="a6cb3f6a6e7ab4b55b4cdbd5311b97725"></a><a name="a6cb3f6a6e7ab4b55b4cdbd5311b97725"></a><strong id="b13947183911292"><a name="b13947183911292"></a><a name="b13947183911292"></a>true</strong>: yes; <strong id="b1295219399299"><a name="b1295219399299"></a><a name="b1295219399299"></a>false</strong>: no.</p>
</td>
<td class="cellrowborder" valign="top" width="24.092409240924095%" headers="mcps1.1.5.1.4 "><p id="a8b17cd115d27436bb36d078f632bb9e4"><a name="a8b17cd115d27436bb36d078f632bb9e4"></a><a name="a8b17cd115d27436bb36d078f632bb9e4"></a>-</p>
</td>
</tr>
<tr id="rbc657a9a17b94a128eb2ce00c96909ff"><td class="cellrowborder" valign="top" width="28.752875287528752%" headers="mcps1.1.5.1.1 "><p id="a594947d8add443f99234f52eaf036dac"><a name="a594947d8add443f99234f52eaf036dac"></a><a name="a594947d8add443f99234f52eaf036dac"></a>zoomIn()</p>
</td>
<td class="cellrowborder" valign="top" width="23.752375237523754%" headers="mcps1.1.5.1.2 "><p id="a1920e1df76414b1c944ff60c8fed3871"><a name="a1920e1df76414b1c944ff60c8fed3871"></a><a name="a1920e1df76414b1c944ff60c8fed3871"></a>Zooms in on the map by one level.</p>
</td>
<td class="cellrowborder" valign="top" width="23.402340234023406%" headers="mcps1.1.5.1.3 "><p id="aa440088d5ec140469f8996c0ec264e2d"><a name="aa440088d5ec140469f8996c0ec264e2d"></a><a name="aa440088d5ec140469f8996c0ec264e2d"></a>-</p>
</td>
<td class="cellrowborder" valign="top" width="24.092409240924095%" headers="mcps1.1.5.1.4 "><p id="a4874f5086acc489580eb18cb31a10608"><a name="a4874f5086acc489580eb18cb31a10608"></a><a name="a4874f5086acc489580eb18cb31a10608"></a>-</p>
</td>
</tr>
<tr id="rd691082165744360950c00c5648744ae"><td class="cellrowborder" valign="top" width="28.752875287528752%" headers="mcps1.1.5.1.1 "><p id="a8786ba9010e74403874d2b914821b56b"><a name="a8786ba9010e74403874d2b914821b56b"></a><a name="a8786ba9010e74403874d2b914821b56b"></a>zoomOut()</p>
</td>
<td class="cellrowborder" valign="top" width="23.752375237523754%" headers="mcps1.1.5.1.2 "><p id="a0c011fe5b2244c71840022ca024bba44"><a name="a0c011fe5b2244c71840022ca024bba44"></a><a name="a0c011fe5b2244c71840022ca024bba44"></a>Zooms out on the map by one level.</p>
</td>
<td class="cellrowborder" valign="top" width="23.402340234023406%" headers="mcps1.1.5.1.3 "><p id="a4c04c4738d2e41e9bd7d8b85cae499cf"><a name="a4c04c4738d2e41e9bd7d8b85cae499cf"></a><a name="a4c04c4738d2e41e9bd7d8b85cae499cf"></a>-</p>
</td>
<td class="cellrowborder" valign="top" width="24.092409240924095%" headers="mcps1.1.5.1.4 "><p id="a657b0038e0494b6c91efd98169842b58"><a name="a657b0038e0494b6c91efd98169842b58"></a><a name="a657b0038e0494b6c91efd98169842b58"></a>-</p>
</td>
</tr>
</tbody>
</table>

## Events<a name="sdd35559e11f04b6a917da42401515a0e"></a>

<a name="tbc680383012d4f0898be7be90180f192"></a>
<table><thead align="left"><tr id="rc2feb99f13b445a7811e398a7907f594"><th class="cellrowborder" valign="top" width="19.908009199080094%" id="mcps1.1.5.1.1"><p id="a2303c63b1bd34f3fbff3583fc061fa44"><a name="a2303c63b1bd34f3fbff3583fc061fa44"></a><a name="a2303c63b1bd34f3fbff3583fc061fa44"></a><strong id="ac69c86b3a33346e5a2b9748195c03806"><a name="ac69c86b3a33346e5a2b9748195c03806"></a><a name="ac69c86b3a33346e5a2b9748195c03806"></a>Event</strong></p>
</th>
<th class="cellrowborder" valign="top" width="16.878312168783122%" id="mcps1.1.5.1.2"><p id="a444590ca70e946b1bb40527cc2805c39"><a name="a444590ca70e946b1bb40527cc2805c39"></a><a name="a444590ca70e946b1bb40527cc2805c39"></a><strong id="b63101042114612"><a name="b63101042114612"></a><a name="b63101042114612"></a>Description</strong></p>
</th>
<th class="cellrowborder" valign="top" width="31.77682231776823%" id="mcps1.1.5.1.3"><p id="aca0301e2f5c047ba983141a0e5d20b75"><a name="aca0301e2f5c047ba983141a0e5d20b75"></a><a name="aca0301e2f5c047ba983141a0e5d20b75"></a><strong id="aedf9c4d1f4b34b20886b5592cdd8b318"><a name="aedf9c4d1f4b34b20886b5592cdd8b318"></a><a name="aedf9c4d1f4b34b20886b5592cdd8b318"></a>Usage</strong></p>
</th>
<th class="cellrowborder" valign="top" width="31.436856314368566%" id="mcps1.1.5.1.4"><p id="p18129133812243"><a name="p18129133812243"></a><a name="p18129133812243"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="r91817b028e92413bac0c0abddad88b03"><td class="cellrowborder" valign="top" width="19.908009199080094%" headers="mcps1.1.5.1.1 "><p id="ad686d06f36064076bd8c0312c9733d36"><a name="ad686d06f36064076bd8c0312c9733d36"></a><a name="ad686d06f36064076bd8c0312c9733d36"></a>click</p>
</td>
<td class="cellrowborder" valign="top" width="16.878312168783122%" headers="mcps1.1.5.1.2 "><p id="a8417ba13c3e34efb9b91e21c1815ec33"><a name="a8417ba13c3e34efb9b91e21c1815ec33"></a><a name="a8417ba13c3e34efb9b91e21c1815ec33"></a>Click on the left button of the mouse once or more.</p>
</td>
<td class="cellrowborder" valign="top" width="31.77682231776823%" headers="mcps1.1.5.1.3 "><p id="a29f46443596c4429813e3e610061af27"><a name="a29f46443596c4429813e3e610061af27"></a><a name="a29f46443596c4429813e3e610061af27"></a>map.on('click', callback)</p>
</td>
<td class="cellrowborder" rowspan="8" valign="top" width="31.436856314368566%" headers="mcps1.1.5.1.4 "><p id="p1691921442513"><a name="p1691921442513"></a><a name="p1691921442513"></a>In the callback function, the <strong id="b028113272116"><a name="b028113272116"></a><a name="b028113272116"></a>event</strong> object includes two important parameters:</p>
<a name="ul1091911414251"></a><a name="ul1091911414251"></a><ul id="ul1091911414251"><li><strong id="b108479305151"><a name="b108479305151"></a><a name="b108479305151"></a>coordinate</strong>: projection longitude-latitude coordinates in the Mercator 3857 coordinate system. You can use the <strong id="b1342711532136"><a name="b1342711532136"></a><a name="b1342711532136"></a>HWMapJsSDK.HWMapUtils.epsgToLatLng(event.coordinate)</strong> method to convert the projection longitude-latitude coordinates in the Mercator 3857 coordinate system to daily used longitude-latitude coordinates.</li><li><strong id="b117971544111516"><a name="b117971544111516"></a><a name="b117971544111516"></a>pixel</strong>: screen coordinate, which indicates the number of pixels between the current interaction point and the upper left corner of the screen. </li></ul>
</td>
</tr>
<tr id="rf6e8daa2dfd942788d0725fed241a5de"><td class="cellrowborder" valign="top" headers="mcps1.1.5.1.1 "><p id="a32a5036cd73647928737acd3c0dba5d7"><a name="a32a5036cd73647928737acd3c0dba5d7"></a><a name="a32a5036cd73647928737acd3c0dba5d7"></a>singleclick</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.5.1.2 "><p id="aa1f601ea0ff24b18bc476a83f918051c"><a name="aa1f601ea0ff24b18bc476a83f918051c"></a><a name="aa1f601ea0ff24b18bc476a83f918051c"></a>Click on the left button of the mouse once.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.5.1.3 "><p id="acbd1bc18d63c493d960dd8e7fbef6106"><a name="acbd1bc18d63c493d960dd8e7fbef6106"></a><a name="acbd1bc18d63c493d960dd8e7fbef6106"></a>map.on('singleclick', callback)</p>
</td>
</tr>
<tr id="rcb5dcdfed07d490c8ffe43f87b12764e"><td class="cellrowborder" valign="top" headers="mcps1.1.5.1.1 "><p id="a7a462834c0af4b6287724f1bc7921425"><a name="a7a462834c0af4b6287724f1bc7921425"></a><a name="a7a462834c0af4b6287724f1bc7921425"></a>dblclick</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.5.1.2 "><p id="a7229aad67f2541c98290ae0e478ec288"><a name="a7229aad67f2541c98290ae0e478ec288"></a><a name="a7229aad67f2541c98290ae0e478ec288"></a>Double-click on the left button of the mouse.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.5.1.3 "><p id="a19df2861a43942928ce59b00554cf474"><a name="a19df2861a43942928ce59b00554cf474"></a><a name="a19df2861a43942928ce59b00554cf474"></a>map.on('dblclick', callback)</p>
</td>
</tr>
<tr id="rdd88e5dc1c3a481a8633055e57e3ec9b"><td class="cellrowborder" valign="top" headers="mcps1.1.5.1.1 "><p id="a8b08c13f13c54058abfc615d4c4fb49d"><a name="a8b08c13f13c54058abfc615d4c4fb49d"></a><a name="a8b08c13f13c54058abfc615d4c4fb49d"></a>contextmenu</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.5.1.2 "><p id="ae2c567705d2b4b5d9020279690f49f86"><a name="ae2c567705d2b4b5d9020279690f49f86"></a><a name="ae2c567705d2b4b5d9020279690f49f86"></a>Click on the right button of the mouse.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.5.1.3 "><p id="a43832857a3e249749d4230cf346c2a5a"><a name="a43832857a3e249749d4230cf346c2a5a"></a><a name="a43832857a3e249749d4230cf346c2a5a"></a>map.on('contextmenu', callback)</p>
</td>
</tr>
<tr id="r3aa3f6aad3b446cc9cb61669a66f8aa4"><td class="cellrowborder" valign="top" headers="mcps1.1.5.1.1 "><p id="aadd7858963454d6e94f896cd66167e1e"><a name="aadd7858963454d6e94f896cd66167e1e"></a><a name="aadd7858963454d6e94f896cd66167e1e"></a>pointermove</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.5.1.2 "><p id="a5bd44193a8b34a86863bfec79d698426"><a name="a5bd44193a8b34a86863bfec79d698426"></a><a name="a5bd44193a8b34a86863bfec79d698426"></a>Moving of the mouse pointer.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.5.1.3 "><p id="a5df07ef599e045488abd6c011c396b48"><a name="a5df07ef599e045488abd6c011c396b48"></a><a name="a5df07ef599e045488abd6c011c396b48"></a>map.on('pointermove', callback)</p>
</td>
</tr>
<tr id="r903a54d9e82d49e181a54f8aa94feb4e"><td class="cellrowborder" valign="top" headers="mcps1.1.5.1.1 "><p id="a563d12970aeb44afbafcb2c8d94d2adc"><a name="a563d12970aeb44afbafcb2c8d94d2adc"></a><a name="a563d12970aeb44afbafcb2c8d94d2adc"></a>pointerdown</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.5.1.2 "><p id="af256905c9ef649ac8f98e26a83730e5b"><a name="af256905c9ef649ac8f98e26a83730e5b"></a><a name="af256905c9ef649ac8f98e26a83730e5b"></a>Mouse button press.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.5.1.3 "><p id="a7ac42a77b38f4fa98e069c650c5866b2"><a name="a7ac42a77b38f4fa98e069c650c5866b2"></a><a name="a7ac42a77b38f4fa98e069c650c5866b2"></a>map.on('pointerdown', callback)</p>
</td>
</tr>
<tr id="ra5e1899cc1ea4ff7be1c476ccfc83319"><td class="cellrowborder" valign="top" headers="mcps1.1.5.1.1 "><p id="a513cf72c3ed541dbb289f09327f7f8b5"><a name="a513cf72c3ed541dbb289f09327f7f8b5"></a><a name="a513cf72c3ed541dbb289f09327f7f8b5"></a>pointerup</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.5.1.2 "><p id="a383fcd8e8f904b3b87649ba605a98b8b"><a name="a383fcd8e8f904b3b87649ba605a98b8b"></a><a name="a383fcd8e8f904b3b87649ba605a98b8b"></a>Mouse button release.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.5.1.3 "><p id="ab57d5fa2800a4f86a66edbeb69d7aeb8"><a name="ab57d5fa2800a4f86a66edbeb69d7aeb8"></a><a name="ab57d5fa2800a4f86a66edbeb69d7aeb8"></a>map.on('pointerup', callback)</p>
</td>
</tr>
<tr id="row8706152613460"><td class="cellrowborder" valign="top" headers="mcps1.1.5.1.1 "><p id="ab0bb5892c5b142c0abe696279d335b35"><a name="ab0bb5892c5b142c0abe696279d335b35"></a><a name="ab0bb5892c5b142c0abe696279d335b35"></a>pointerdrag</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.5.1.2 "><p id="a776429f2c9ca4780acad7f1935f4064b"><a name="a776429f2c9ca4780acad7f1935f4064b"></a><a name="a776429f2c9ca4780acad7f1935f4064b"></a>Map dragging.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.5.1.3 "><p id="a04259891435140b5b12a698c2510c7fe"><a name="a04259891435140b5b12a698c2510c7fe"></a><a name="a04259891435140b5b12a698c2510c7fe"></a>map.on('pointerdrag', callback)</p>
</td>
</tr>
<tr id="r496a31bc7ccd4150be787deae67f9bab"><td class="cellrowborder" valign="top" width="19.908009199080094%" headers="mcps1.1.5.1.1 "><p id="ad07c339921cd4173adc6e841ca17f3a1"><a name="ad07c339921cd4173adc6e841ca17f3a1"></a><a name="ad07c339921cd4173adc6e841ca17f3a1"></a>movestart</p>
</td>
<td class="cellrowborder" valign="top" width="16.878312168783122%" headers="mcps1.1.5.1.2 "><p id="a4e4cb161b016427a825e6614cd0d5851"><a name="a4e4cb161b016427a825e6614cd0d5851"></a><a name="a4e4cb161b016427a825e6614cd0d5851"></a>Map moving start.</p>
</td>
<td class="cellrowborder" valign="top" width="31.77682231776823%" headers="mcps1.1.5.1.3 "><p id="a0288d79c07c94b1cae6f5c62849056e1"><a name="a0288d79c07c94b1cae6f5c62849056e1"></a><a name="a0288d79c07c94b1cae6f5c62849056e1"></a>map.on('movestart', callback)</p>
</td>
<td class="cellrowborder" valign="top" width="31.436856314368566%" headers="mcps1.1.5.1.4 "><p id="p1013043872420"><a name="p1013043872420"></a><a name="p1013043872420"></a>-</p>
</td>
</tr>
<tr id="r5dfa8b70215543519fb2708ac4c1d991"><td class="cellrowborder" valign="top" width="19.908009199080094%" headers="mcps1.1.5.1.1 "><p id="a4bde54c1988a40da9e15ba9fa438edfc"><a name="a4bde54c1988a40da9e15ba9fa438edfc"></a><a name="a4bde54c1988a40da9e15ba9fa438edfc"></a>moveend</p>
</td>
<td class="cellrowborder" valign="top" width="16.878312168783122%" headers="mcps1.1.5.1.2 "><p id="ac59561979fd0457aa3efba92ca13ade8"><a name="ac59561979fd0457aa3efba92ca13ade8"></a><a name="ac59561979fd0457aa3efba92ca13ade8"></a>Map moving stop.</p>
</td>
<td class="cellrowborder" valign="top" width="31.77682231776823%" headers="mcps1.1.5.1.3 "><p id="aa6375ec4d168471f84157732f167c56a"><a name="aa6375ec4d168471f84157732f167c56a"></a><a name="aa6375ec4d168471f84157732f167c56a"></a>map.on('moveend', callback)</p>
</td>
<td class="cellrowborder" valign="top" width="31.436856314368566%" headers="mcps1.1.5.1.4 "><p id="p1913063832414"><a name="p1913063832414"></a><a name="p1913063832414"></a>-</p>
</td>
</tr>
<tr id="row6785173815417"><td class="cellrowborder" valign="top" width="19.908009199080094%" headers="mcps1.1.5.1.1 "><p id="p60245124"><a name="p60245124"></a><a name="p60245124"></a>onCenterChanged</p>
</td>
<td class="cellrowborder" valign="top" width="16.878312168783122%" headers="mcps1.1.5.1.2 "><p id="p48016903"><a name="p48016903"></a><a name="p48016903"></a>Map center change.</p>
</td>
<td class="cellrowborder" valign="top" width="31.77682231776823%" headers="mcps1.1.5.1.3 "><p id="p64163914"><a name="p64163914"></a><a name="p64163914"></a>map.onCenterChanged(callback)</p>
</td>
<td class="cellrowborder" valign="top" width="31.436856314368566%" headers="mcps1.1.5.1.4 "><p id="p18130438192416"><a name="p18130438192416"></a><a name="p18130438192416"></a>-</p>
</td>
</tr>
<tr id="row1722114012412"><td class="cellrowborder" valign="top" width="19.908009199080094%" headers="mcps1.1.5.1.1 "><p id="p615201"><a name="p615201"></a><a name="p615201"></a>onHeadingChanged</p>
</td>
<td class="cellrowborder" valign="top" width="16.878312168783122%" headers="mcps1.1.5.1.2 "><p id="p49831357"><a name="p49831357"></a><a name="p49831357"></a>Map heading change.</p>
</td>
<td class="cellrowborder" valign="top" width="31.77682231776823%" headers="mcps1.1.5.1.3 "><p id="p9808084"><a name="p9808084"></a><a name="p9808084"></a>map.onHeadingChanged(callback)</p>
</td>
<td class="cellrowborder" valign="top" width="31.436856314368566%" headers="mcps1.1.5.1.4 "><p id="p41303381246"><a name="p41303381246"></a><a name="p41303381246"></a>-</p>
</td>
</tr>
<tr id="row241913417420"><td class="cellrowborder" valign="top" width="19.908009199080094%" headers="mcps1.1.5.1.1 "><p id="p36554200"><a name="p36554200"></a><a name="p36554200"></a>onZoomChanged</p>
</td>
<td class="cellrowborder" valign="top" width="16.878312168783122%" headers="mcps1.1.5.1.2 "><p id="p8100198"><a name="p8100198"></a><a name="p8100198"></a>Map zoom level change.</p>
</td>
<td class="cellrowborder" valign="top" width="31.77682231776823%" headers="mcps1.1.5.1.3 "><p id="p52136268"><a name="p52136268"></a><a name="p52136268"></a>map.onZoomChanged(callback)</p>
</td>
<td class="cellrowborder" valign="top" width="31.436856314368566%" headers="mcps1.1.5.1.4 "><p id="p1130113816247"><a name="p1130113816247"></a><a name="p1130113816247"></a>-</p>
</td>
</tr>
</tbody>
</table>

## CopyrightControlOptions<a name="sdbd4312213b24f86a5ea558dcae2924e"></a>

<a name="t90457f703fc74455ba9db1da5a11b412"></a>
<table><thead align="left"><tr id="rc29ba69401ed4c549c7c4a5fe7037491"><th class="cellrowborder" valign="top" width="20%" id="mcps1.1.5.1.1"><p id="a6fb23bf379144af7941a0606620be9b4"><a name="a6fb23bf379144af7941a0606620be9b4"></a><a name="a6fb23bf379144af7941a0606620be9b4"></a><strong id="a86c315be0ada468db52e03e0afd56f10"><a name="a86c315be0ada468db52e03e0afd56f10"></a><a name="a86c315be0ada468db52e03e0afd56f10"></a>Parameter</strong></p>
</th>
<th class="cellrowborder" valign="top" width="14.000000000000002%" id="mcps1.1.5.1.2"><p id="aa9ef137ab48a4f1e980c6aa197d5c1f3"><a name="aa9ef137ab48a4f1e980c6aa197d5c1f3"></a><a name="aa9ef137ab48a4f1e980c6aa197d5c1f3"></a><strong id="a4625f4f28a0b45e78456c6c42b468dcf"><a name="a4625f4f28a0b45e78456c6c42b468dcf"></a><a name="a4625f4f28a0b45e78456c6c42b468dcf"></a>Mandatory/Optional</strong></p>
</th>
<th class="cellrowborder" valign="top" width="16%" id="mcps1.1.5.1.3"><p id="abf847ac1bbb84866b1c78b2c0a278a4d"><a name="abf847ac1bbb84866b1c78b2c0a278a4d"></a><a name="abf847ac1bbb84866b1c78b2c0a278a4d"></a><strong id="ad4611c2962ad4165acd05dcbfc082a69"><a name="ad4611c2962ad4165acd05dcbfc082a69"></a><a name="ad4611c2962ad4165acd05dcbfc082a69"></a>Type</strong></p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.1.5.1.4"><p id="af9e9462d210347e4a40ef63e6e5553af"><a name="af9e9462d210347e4a40ef63e6e5553af"></a><a name="af9e9462d210347e4a40ef63e6e5553af"></a><strong id="b67353216493"><a name="b67353216493"></a><a name="b67353216493"></a>Description</strong></p>
</th>
</tr>
</thead>
<tbody><tr id="rabf1f0fa30174f39b1bd4d9498c39db5"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.1.5.1.1 "><p id="ac58094208aba4187a502f04820abe31f"><a name="ac58094208aba4187a502f04820abe31f"></a><a name="ac58094208aba4187a502f04820abe31f"></a>value</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="ab045b17e70a44e978d8f9cdf42920196"><a name="ab045b17e70a44e978d8f9cdf42920196"></a><a name="ab045b17e70a44e978d8f9cdf42920196"></a>Mandatory</p>
</td>
<td class="cellrowborder" valign="top" width="16%" headers="mcps1.1.5.1.3 "><p id="a8b90b80f579d4e50a09198260e3a2f1e"><a name="a8b90b80f579d4e50a09198260e3a2f1e"></a><a name="a8b90b80f579d4e50a09198260e3a2f1e"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="p19855635505"><a name="p19855635505"></a><a name="p19855635505"></a>Currently, DOM elements of the text or HTML format are supported. The DOM elements support the following tags:</p>
<a name="ul511911895017"></a><a name="ul511911895017"></a><ul id="ul511911895017"><li>&lt;font&gt;</li><li>&lt;a&gt;</li><li>&lt;img&gt;</li></ul>
</td>
</tr>
</tbody>
</table>

## MapOptions<a name="s4c4b9ba7e96445b4914a72eb8c29b4d9"></a>

<a name="t7e2afaebba20401a875ab9c5f122e6f8"></a>
<table><thead align="left"><tr id="re716410016d54bf6a26b85356b30ad3f"><th class="cellrowborder" valign="top" width="22%" id="mcps1.1.5.1.1"><p id="ac14a4b6e9adf48ae8682744bad07005c"><a name="ac14a4b6e9adf48ae8682744bad07005c"></a><a name="ac14a4b6e9adf48ae8682744bad07005c"></a><strong id="a5b542fb33d9248a389ed7e6763cd3b81"><a name="a5b542fb33d9248a389ed7e6763cd3b81"></a><a name="a5b542fb33d9248a389ed7e6763cd3b81"></a>Parameter</strong></p>
</th>
<th class="cellrowborder" valign="top" width="14.000000000000002%" id="mcps1.1.5.1.2"><p id="a80cf8059e12f4785b0f5dbe567dbeada"><a name="a80cf8059e12f4785b0f5dbe567dbeada"></a><a name="a80cf8059e12f4785b0f5dbe567dbeada"></a><strong id="ae5dcbce21b904764b9d37cbaa2abe91e"><a name="ae5dcbce21b904764b9d37cbaa2abe91e"></a><a name="ae5dcbce21b904764b9d37cbaa2abe91e"></a>Mandatory/Optional</strong></p>
</th>
<th class="cellrowborder" valign="top" width="16%" id="mcps1.1.5.1.3"><p id="a61bee701c52e4671b354bb1f010074b6"><a name="a61bee701c52e4671b354bb1f010074b6"></a><a name="a61bee701c52e4671b354bb1f010074b6"></a><strong id="a5d9d1a8676704108a94948c6e1d8c9fc"><a name="a5d9d1a8676704108a94948c6e1d8c9fc"></a><a name="a5d9d1a8676704108a94948c6e1d8c9fc"></a>Type</strong></p>
</th>
<th class="cellrowborder" valign="top" width="48%" id="mcps1.1.5.1.4"><p id="a26fd45847be1454ba9272255ea45698a"><a name="a26fd45847be1454ba9272255ea45698a"></a><a name="a26fd45847be1454ba9272255ea45698a"></a><strong id="b16116655114915"><a name="b16116655114915"></a><a name="b16116655114915"></a>Description</strong></p>
</th>
</tr>
</thead>
<tbody><tr id="r59c3337036934af5ab8079f5bbabff3e"><td class="cellrowborder" valign="top" width="22%" headers="mcps1.1.5.1.1 "><p id="a7df3154634f24d898bd3bc84e7e0ed91"><a name="a7df3154634f24d898bd3bc84e7e0ed91"></a><a name="a7df3154634f24d898bd3bc84e7e0ed91"></a>center</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="a75a8171e25ae425798ef7bb94a580e15"><a name="a75a8171e25ae425798ef7bb94a580e15"></a><a name="a75a8171e25ae425798ef7bb94a580e15"></a>Mandatory</p>
</td>
<td class="cellrowborder" valign="top" width="16%" headers="mcps1.1.5.1.3 "><p id="a0c3b4fd1556f418890f5674c3a349907"><a name="a0c3b4fd1556f418890f5674c3a349907"></a><a name="a0c3b4fd1556f418890f5674c3a349907"></a><a href="js-params.md#s1f33822192a04bbe9bd9de86a17460b1">LatLng</a></p>
</td>
<td class="cellrowborder" valign="top" width="48%" headers="mcps1.1.5.1.4 "><p id="a4dd93e8200ae43e7893344f82455c1ca"><a name="a4dd93e8200ae43e7893344f82455c1ca"></a><a name="a4dd93e8200ae43e7893344f82455c1ca"></a>Central point of a map.</p>
</td>
</tr>
<tr id="rba50669aae904e08b1ffddc2009a704a"><td class="cellrowborder" valign="top" width="22%" headers="mcps1.1.5.1.1 "><p id="a2e34c0ad166b4cd78e322eedabd0613f"><a name="a2e34c0ad166b4cd78e322eedabd0613f"></a><a name="a2e34c0ad166b4cd78e322eedabd0613f"></a>copyrightControl</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="a3c563ff60aee444fb01c6f8dee34b80d"><a name="a3c563ff60aee444fb01c6f8dee34b80d"></a><a name="a3c563ff60aee444fb01c6f8dee34b80d"></a>Optional</p>
</td>
<td class="cellrowborder" valign="top" width="16%" headers="mcps1.1.5.1.3 "><p id="a915c715a71f1494aa40c86b4f5946999"><a name="a915c715a71f1494aa40c86b4f5946999"></a><a name="a915c715a71f1494aa40c86b4f5946999"></a>Boolean</p>
</td>
<td class="cellrowborder" valign="top" width="48%" headers="mcps1.1.5.1.4 "><p id="a8656e95bf99c4bff8fe69cfdc7777882"><a name="a8656e95bf99c4bff8fe69cfdc7777882"></a><a name="a8656e95bf99c4bff8fe69cfdc7777882"></a>Indicates whether to display the zoom slider on a map. The default value is <strong id="b159643015015"><a name="b159643015015"></a><a name="b159643015015"></a>false</strong>.</p>
</td>
</tr>
<tr id="rd9c7f53dc579447b93c8352bec384a1b"><td class="cellrowborder" valign="top" width="22%" headers="mcps1.1.5.1.1 "><p id="a8be7350955b242d28080f5114bc1b576"><a name="a8be7350955b242d28080f5114bc1b576"></a><a name="a8be7350955b242d28080f5114bc1b576"></a>copyrightControlOptions</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="a6f9c4146a19141ea89534390397c9548"><a name="a6f9c4146a19141ea89534390397c9548"></a><a name="a6f9c4146a19141ea89534390397c9548"></a>Optional</p>
</td>
<td class="cellrowborder" valign="top" width="16%" headers="mcps1.1.5.1.3 "><p id="aa2b5978455284882a13ac61fa5c8a737"><a name="aa2b5978455284882a13ac61fa5c8a737"></a><a name="aa2b5978455284882a13ac61fa5c8a737"></a><a href="#sdbd4312213b24f86a5ea558dcae2924e">CopyrightControlOptions</a></p>
</td>
<td class="cellrowborder" valign="top" width="48%" headers="mcps1.1.5.1.4 "><p id="a990f22b319bb497ba4396730136a2b98"><a name="a990f22b319bb497ba4396730136a2b98"></a><a name="a990f22b319bb497ba4396730136a2b98"></a>Map copyright information.</p>
</td>
</tr>
<tr id="r84716925a5fd40f388b151fd4ba13d0f"><td class="cellrowborder" valign="top" width="22%" headers="mcps1.1.5.1.1 "><p id="aaf1aa1f78c244f20bc41938c55642c36"><a name="aaf1aa1f78c244f20bc41938c55642c36"></a><a name="aaf1aa1f78c244f20bc41938c55642c36"></a>language</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="a44f731d5db3d4895b829a50eb90baefe"><a name="a44f731d5db3d4895b829a50eb90baefe"></a><a name="a44f731d5db3d4895b829a50eb90baefe"></a>Optional</p>
</td>
<td class="cellrowborder" valign="top" width="16%" headers="mcps1.1.5.1.3 "><p id="a03e6a9a676dd48c6b44918a76e1809ef"><a name="a03e6a9a676dd48c6b44918a76e1809ef"></a><a name="a03e6a9a676dd48c6b44918a76e1809ef"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="48%" headers="mcps1.1.5.1.4 "><p id="aa81e4b0577ad44b6affed83ec449b5d9"><a name="aa81e4b0577ad44b6affed83ec449b5d9"></a><a name="aa81e4b0577ad44b6affed83ec449b5d9"></a>Map language. For details about the value range, please refer to <a href="#sbeecdc5106da48ea8df14cd730975c40">LanguageCode</a>.</p>
<div class="note" id="nb3b5b7a5141f42768f2f52f3034a5399"><a name="nb3b5b7a5141f42768f2f52f3034a5399"></a><a name="nb3b5b7a5141f42768f2f52f3034a5399"></a><span class="notetitle"> NOTE: </span><div class="notebody"><p id="a025d6f103c5e4c7ea06c161a5af7cdcb"><a name="a025d6f103c5e4c7ea06c161a5af7cdcb"></a><a name="a025d6f103c5e4c7ea06c161a5af7cdcb"></a>BCP 47 language codes are recommended. </p>
</div></div>
</td>
</tr>
<tr id="r4b623decf02f48c28c086a0294383fc6"><td class="cellrowborder" valign="top" width="22%" headers="mcps1.1.5.1.1 "><p id="a0ad6a1c767b04e4ea15cc29818fad925"><a name="a0ad6a1c767b04e4ea15cc29818fad925"></a><a name="a0ad6a1c767b04e4ea15cc29818fad925"></a>locationControl</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="a6894f7d3a02a44bc9fd3a8ba98533a5e"><a name="a6894f7d3a02a44bc9fd3a8ba98533a5e"></a><a name="a6894f7d3a02a44bc9fd3a8ba98533a5e"></a>Optional</p>
</td>
<td class="cellrowborder" valign="top" width="16%" headers="mcps1.1.5.1.3 "><p id="ae11706e7cc5d4c6c82cbf9175328ab83"><a name="ae11706e7cc5d4c6c82cbf9175328ab83"></a><a name="ae11706e7cc5d4c6c82cbf9175328ab83"></a>Boolean</p>
</td>
<td class="cellrowborder" valign="top" width="48%" headers="mcps1.1.5.1.4 "><p id="ab8b4b8f8d261457db27f2bf385de128f"><a name="ab8b4b8f8d261457db27f2bf385de128f"></a><a name="ab8b4b8f8d261457db27f2bf385de128f"></a>Indicates whether to display the current-location icon on the map. The default value is <strong id="b20400102110518"><a name="b20400102110518"></a><a name="b20400102110518"></a>false</strong>.</p>
</td>
</tr>
<tr id="re75f5e65260140af8a5eec788634b934"><td class="cellrowborder" valign="top" width="22%" headers="mcps1.1.5.1.1 "><p id="ad8099b059d5f40a48b8a684b7fd1e625"><a name="ad8099b059d5f40a48b8a684b7fd1e625"></a><a name="ad8099b059d5f40a48b8a684b7fd1e625"></a>mapType</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="a8a09c2d6d79d4b61868134c1baa90cb8"><a name="a8a09c2d6d79d4b61868134c1baa90cb8"></a><a name="a8a09c2d6d79d4b61868134c1baa90cb8"></a>Optional</p>
</td>
<td class="cellrowborder" valign="top" width="16%" headers="mcps1.1.5.1.3 "><p id="ab8ba8c64cec94e1488aab59a175cf88e"><a name="ab8ba8c64cec94e1488aab59a175cf88e"></a><a name="ab8ba8c64cec94e1488aab59a175cf88e"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="48%" headers="mcps1.1.5.1.4 "><p id="ae6eadd5d130d41678b0daa751fe9a3ea"><a name="ae6eadd5d130d41678b0daa751fe9a3ea"></a><a name="ae6eadd5d130d41678b0daa751fe9a3ea"></a>Map type. Currently, only the standard map type <strong id="b291273016518"><a name="b291273016518"></a><a name="b291273016518"></a>ROADMAP</strong> is supported.</p>
</td>
</tr>
<tr id="r3c34263304f444fba20b4ca88edd07bf"><td class="cellrowborder" valign="top" width="22%" headers="mcps1.1.5.1.1 "><p id="af477e7a0389c417dab1ee140fdcd5b01"><a name="af477e7a0389c417dab1ee140fdcd5b01"></a><a name="af477e7a0389c417dab1ee140fdcd5b01"></a>maxZoom</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="a60a0cc6d38194c53af429b6ec5982541"><a name="a60a0cc6d38194c53af429b6ec5982541"></a><a name="a60a0cc6d38194c53af429b6ec5982541"></a>Optional</p>
</td>
<td class="cellrowborder" valign="top" width="16%" headers="mcps1.1.5.1.3 "><p id="a2f6aca41eae34ac89fbcb4a875ab8a4f"><a name="a2f6aca41eae34ac89fbcb4a875ab8a4f"></a><a name="a2f6aca41eae34ac89fbcb4a875ab8a4f"></a>Number</p>
</td>
<td class="cellrowborder" valign="top" width="48%" headers="mcps1.1.5.1.4 "><p id="a2b0a36042ad3401687c82a9e7c1b660c"><a name="a2b0a36042ad3401687c82a9e7c1b660c"></a><a name="a2b0a36042ad3401687c82a9e7c1b660c"></a>Maximum zoom level of a map. The value ranges from 2 to 20. The default value is <strong id="b19647114195114"><a name="b19647114195114"></a><a name="b19647114195114"></a>20</strong>.</p>
</td>
</tr>
<tr id="r1e8d6f92e60a49079e1fef8866ab5d59"><td class="cellrowborder" valign="top" width="22%" headers="mcps1.1.5.1.1 "><p id="a01f98f3b345746a08285c9aaf4d8fad6"><a name="a01f98f3b345746a08285c9aaf4d8fad6"></a><a name="a01f98f3b345746a08285c9aaf4d8fad6"></a>minZoom</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="a0813c4565250492399d9c27b6a88d177"><a name="a0813c4565250492399d9c27b6a88d177"></a><a name="a0813c4565250492399d9c27b6a88d177"></a>Optional</p>
</td>
<td class="cellrowborder" valign="top" width="16%" headers="mcps1.1.5.1.3 "><p id="acd1f3dbdf8af471fbf727fd800b59b14"><a name="acd1f3dbdf8af471fbf727fd800b59b14"></a><a name="acd1f3dbdf8af471fbf727fd800b59b14"></a>Number</p>
</td>
<td class="cellrowborder" valign="top" width="48%" headers="mcps1.1.5.1.4 "><p id="ab6438798f91a46e0a27c26b00c661ae5"><a name="ab6438798f91a46e0a27c26b00c661ae5"></a><a name="ab6438798f91a46e0a27c26b00c661ae5"></a>Maximum zoom level of a map. The value ranges from 2 to 20. The default value is <strong id="b176576463510"><a name="b176576463510"></a><a name="b176576463510"></a>2</strong>.</p>
</td>
</tr>
<tr id="r52f74e4f9284488e90f4c84e54e9298f"><td class="cellrowborder" valign="top" width="22%" headers="mcps1.1.5.1.1 "><p id="ab5434f7472754c79afa664f7672fe18c"><a name="ab5434f7472754c79afa664f7672fe18c"></a><a name="ab5434f7472754c79afa664f7672fe18c"></a>navigationControl</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="a665c042602f54198a95f2a87eddeeef9"><a name="a665c042602f54198a95f2a87eddeeef9"></a><a name="a665c042602f54198a95f2a87eddeeef9"></a>Optional</p>
</td>
<td class="cellrowborder" valign="top" width="16%" headers="mcps1.1.5.1.3 "><p id="a19181188a3a84a7bb92a3e70703f3cb8"><a name="a19181188a3a84a7bb92a3e70703f3cb8"></a><a name="a19181188a3a84a7bb92a3e70703f3cb8"></a>Boolean</p>
</td>
<td class="cellrowborder" valign="top" width="48%" headers="mcps1.1.5.1.4 "><p id="ae44a21cdf65d48aa83b3663e935d0d8d"><a name="ae44a21cdf65d48aa83b3663e935d0d8d"></a><a name="ae44a21cdf65d48aa83b3663e935d0d8d"></a>Indicates whether to display the pan button on the map. The default value is <strong id="b117216765215"><a name="b117216765215"></a><a name="b117216765215"></a>false</strong>.</p>
</td>
</tr>
<tr id="r2d43d783338b416a91e0ad76322e6094"><td class="cellrowborder" valign="top" width="22%" headers="mcps1.1.5.1.1 "><p id="a34c6f88560794c7983dda7353028b6c2"><a name="a34c6f88560794c7983dda7353028b6c2"></a><a name="a34c6f88560794c7983dda7353028b6c2"></a>political</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="a2ba66bb75c2446c6b9993a059fdb4217"><a name="a2ba66bb75c2446c6b9993a059fdb4217"></a><a name="a2ba66bb75c2446c6b9993a059fdb4217"></a>Optional</p>
</td>
<td class="cellrowborder" valign="top" width="16%" headers="mcps1.1.5.1.3 "><p id="a45f65020f03a426eb57b85b538a6266d"><a name="a45f65020f03a426eb57b85b538a6266d"></a><a name="a45f65020f03a426eb57b85b538a6266d"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="48%" headers="mcps1.1.5.1.4 "><p id="a1d2388a023924d1a8262844a5087bdac"><a name="a1d2388a023924d1a8262844a5087bdac"></a><a name="a1d2388a023924d1a8262844a5087bdac"></a>Political view. The value is a two-letter country or region code complying with ISO 3166-1 alpha-2.</p>
<div class="caution" id="note1528292117492"><a name="note1528292117492"></a><a name="note1528292117492"></a><span class="cautiontitle"> CAUTION: </span><div class="cautionbody"><p id="p52829212494"><a name="p52829212494"></a><a name="p52829212494"></a>This parameter has been deprecated.</p>
</div></div>
</td>
</tr>
<tr id="r27b2cf8aadc24082b6cc8832081d38d8"><td class="cellrowborder" valign="top" width="22%" headers="mcps1.1.5.1.1 "><p id="af31b3c14a62c43999c334c2c8c981fbb"><a name="af31b3c14a62c43999c334c2c8c981fbb"></a><a name="af31b3c14a62c43999c334c2c8c981fbb"></a>rotateControl</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="acdc8640200d84086ac158338bf666ed5"><a name="acdc8640200d84086ac158338bf666ed5"></a><a name="acdc8640200d84086ac158338bf666ed5"></a>Optional</p>
</td>
<td class="cellrowborder" valign="top" width="16%" headers="mcps1.1.5.1.3 "><p id="aeaab73f054d44f9ba48eddf50cd92056"><a name="aeaab73f054d44f9ba48eddf50cd92056"></a><a name="aeaab73f054d44f9ba48eddf50cd92056"></a>Boolean</p>
</td>
<td class="cellrowborder" valign="top" width="48%" headers="mcps1.1.5.1.4 "><p id="a217542baa4d54fa9afb4be0c49ceaa5d"><a name="a217542baa4d54fa9afb4be0c49ceaa5d"></a><a name="a217542baa4d54fa9afb4be0c49ceaa5d"></a>Indicates whether to display the compass on a map. The default value is <strong id="b2428321105213"><a name="b2428321105213"></a><a name="b2428321105213"></a>false</strong>.</p>
</td>
</tr>
<tr id="ra9ad513d765e4f2cb5c3fe0a6b23a9b0"><td class="cellrowborder" valign="top" width="22%" headers="mcps1.1.5.1.1 "><p id="a346a9e751ffc4e7abdf0830ca890054d"><a name="a346a9e751ffc4e7abdf0830ca890054d"></a><a name="a346a9e751ffc4e7abdf0830ca890054d"></a>scaleControl</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="a6a7843289b30462fb645a6f944c20291"><a name="a6a7843289b30462fb645a6f944c20291"></a><a name="a6a7843289b30462fb645a6f944c20291"></a>Optional</p>
</td>
<td class="cellrowborder" valign="top" width="16%" headers="mcps1.1.5.1.3 "><p id="a6b84bf29cab1453bad0cfc60cc107c78"><a name="a6b84bf29cab1453bad0cfc60cc107c78"></a><a name="a6b84bf29cab1453bad0cfc60cc107c78"></a>Boolean</p>
</td>
<td class="cellrowborder" valign="top" width="48%" headers="mcps1.1.5.1.4 "><p id="aa5dbbb4226b04482bb0bdd560d0d058d"><a name="aa5dbbb4226b04482bb0bdd560d0d058d"></a><a name="aa5dbbb4226b04482bb0bdd560d0d058d"></a>Indicates whether to display the scale on a map. The default value is <strong id="b49168344525"><a name="b49168344525"></a><a name="b49168344525"></a>false</strong>.</p>
</td>
</tr>
<tr id="r1a13a3a77f1f4193bd2cd6ce4db3fa7e"><td class="cellrowborder" valign="top" width="22%" headers="mcps1.1.5.1.1 "><p id="a53831f7fc37f4abf995cceac9600827e"><a name="a53831f7fc37f4abf995cceac9600827e"></a><a name="a53831f7fc37f4abf995cceac9600827e"></a>zoom</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="aec0243bd6d0149d6918d220be39f5327"><a name="aec0243bd6d0149d6918d220be39f5327"></a><a name="aec0243bd6d0149d6918d220be39f5327"></a>Mandatory</p>
</td>
<td class="cellrowborder" valign="top" width="16%" headers="mcps1.1.5.1.3 "><p id="a50b0adfe7e67458aabe64be0eecd6d5c"><a name="a50b0adfe7e67458aabe64be0eecd6d5c"></a><a name="a50b0adfe7e67458aabe64be0eecd6d5c"></a>Number</p>
</td>
<td class="cellrowborder" valign="top" width="48%" headers="mcps1.1.5.1.4 "><p id="a4729599017ba4bd7935354b8e7572f37"><a name="a4729599017ba4bd7935354b8e7572f37"></a><a name="a4729599017ba4bd7935354b8e7572f37"></a>Zoom level during map initialization.</p>
</td>
</tr>
<tr id="r9270c1a739df4bb2aafd9d5bcd9415b4"><td class="cellrowborder" valign="top" width="22%" headers="mcps1.1.5.1.1 "><p id="af37315075e414481b22324150d3170f3"><a name="af37315075e414481b22324150d3170f3"></a><a name="af37315075e414481b22324150d3170f3"></a>zoomSlider</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="ab6963709d8704036bd28ed912353a4b7"><a name="ab6963709d8704036bd28ed912353a4b7"></a><a name="ab6963709d8704036bd28ed912353a4b7"></a>Optional</p>
</td>
<td class="cellrowborder" valign="top" width="16%" headers="mcps1.1.5.1.3 "><p id="ab1d66bdcfc0e4cdcaaeeb845ce020b54"><a name="ab1d66bdcfc0e4cdcaaeeb845ce020b54"></a><a name="ab1d66bdcfc0e4cdcaaeeb845ce020b54"></a>Boolean</p>
</td>
<td class="cellrowborder" valign="top" width="48%" headers="mcps1.1.5.1.4 "><p id="a76fa3a586437420aa52d3a8416639c16"><a name="a76fa3a586437420aa52d3a8416639c16"></a><a name="a76fa3a586437420aa52d3a8416639c16"></a>Indicates whether to display the zoom slider on a map. The default value is <strong id="b117613271418"><a name="b117613271418"></a><a name="b117613271418"></a>false</strong>.</p>
</td>
</tr>
<tr id="r24cbd88c9d8a42af82a812c47a8754fe"><td class="cellrowborder" valign="top" width="22%" headers="mcps1.1.5.1.1 "><p id="a436fe664d56f46b686c4f80dba76b2d6"><a name="a436fe664d56f46b686c4f80dba76b2d6"></a><a name="a436fe664d56f46b686c4f80dba76b2d6"></a>zoomControl</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="ab87a179cb82a4e5687f7b9a7835dad06"><a name="ab87a179cb82a4e5687f7b9a7835dad06"></a><a name="ab87a179cb82a4e5687f7b9a7835dad06"></a>Optional</p>
</td>
<td class="cellrowborder" valign="top" width="16%" headers="mcps1.1.5.1.3 "><p id="a5ad2fa101998456d805f9b9041fefff9"><a name="a5ad2fa101998456d805f9b9041fefff9"></a><a name="a5ad2fa101998456d805f9b9041fefff9"></a>Boolean</p>
</td>
<td class="cellrowborder" valign="top" width="48%" headers="mcps1.1.5.1.4 "><p id="a5b238077570a4053a545cb35e6f85181"><a name="a5b238077570a4053a545cb35e6f85181"></a><a name="a5b238077570a4053a545cb35e6f85181"></a>Indicates whether to display the zoom slider on a map. The default value is <strong id="b1815583415111"><a name="b1815583415111"></a><a name="b1815583415111"></a>true</strong>.</p>
</td>
</tr>
<tr id="row376413822711"><td class="cellrowborder" valign="top" width="22%" headers="mcps1.1.5.1.1 "><p id="p1776518192720"><a name="p1776518192720"></a><a name="p1776518192720"></a>sourceType</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="p1765585277"><a name="p1765585277"></a><a name="p1765585277"></a>Optional</p>
</td>
<td class="cellrowborder" valign="top" width="16%" headers="mcps1.1.5.1.3 "><p id="p137652812716"><a name="p137652812716"></a><a name="p137652812716"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="48%" headers="mcps1.1.5.1.4 "><p id="p576513811272"><a name="p576513811272"></a><a name="p576513811272"></a>Tile type used for map loading. The value can be <strong id="b779412219406"><a name="b779412219406"></a><a name="b779412219406"></a>vector</strong> or <strong id="b15693192515402"><a name="b15693192515402"></a><a name="b15693192515402"></a>raster</strong>. The default value is <strong id="b1412092924011"><a name="b1412092924011"></a><a name="b1412092924011"></a>vector</strong>.</p>
</td>
</tr>
</tbody>
</table>

## ScaleControlOptions<a name="s08d9fe83d6b9407e8bfcd889e7af1969"></a>

<a name="te950fbf54bfd48fd988a07ad93e809dd"></a>
<table><thead align="left"><tr id="r72936b4a2c574b83a846247dd71da542"><th class="cellrowborder" valign="top" width="20%" id="mcps1.1.5.1.1"><p id="a7156a415ef174241b73167d4702c3939"><a name="a7156a415ef174241b73167d4702c3939"></a><a name="a7156a415ef174241b73167d4702c3939"></a><strong id="af5528a1ea39449f8b489a4e9281089d5"><a name="af5528a1ea39449f8b489a4e9281089d5"></a><a name="af5528a1ea39449f8b489a4e9281089d5"></a>Parameter</strong></p>
</th>
<th class="cellrowborder" valign="top" width="14.000000000000002%" id="mcps1.1.5.1.2"><p id="a7f01811c828b40a1aff2c2964971caa8"><a name="a7f01811c828b40a1aff2c2964971caa8"></a><a name="a7f01811c828b40a1aff2c2964971caa8"></a><strong id="a7369f48d4ca64f50a946bec70759f1b2"><a name="a7369f48d4ca64f50a946bec70759f1b2"></a><a name="a7369f48d4ca64f50a946bec70759f1b2"></a>Mandatory/Optional</strong></p>
</th>
<th class="cellrowborder" valign="top" width="16%" id="mcps1.1.5.1.3"><p id="a17f3f4f0cc324bedad098ec2bf1075f9"><a name="a17f3f4f0cc324bedad098ec2bf1075f9"></a><a name="a17f3f4f0cc324bedad098ec2bf1075f9"></a><strong id="a97a7cccb74cd411da2349fec66b59cd0"><a name="a97a7cccb74cd411da2349fec66b59cd0"></a><a name="a97a7cccb74cd411da2349fec66b59cd0"></a>Type</strong></p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.1.5.1.4"><p id="ad9b424f5e16e4851a8e9baeaee10ba87"><a name="ad9b424f5e16e4851a8e9baeaee10ba87"></a><a name="ad9b424f5e16e4851a8e9baeaee10ba87"></a><strong id="b57824432116"><a name="b57824432116"></a><a name="b57824432116"></a>Description</strong></p>
</th>
</tr>
</thead>
<tbody><tr id="r0962c957f0334bce983be8cc83329a1b"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.1.5.1.1 "><p id="a89289105c16045e5a4b292a1cd526545"><a name="a89289105c16045e5a4b292a1cd526545"></a><a name="a89289105c16045e5a4b292a1cd526545"></a>units</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="af3fa9dc14c564aa19067425177f4875d"><a name="af3fa9dc14c564aa19067425177f4875d"></a><a name="af3fa9dc14c564aa19067425177f4875d"></a>Optional</p>
</td>
<td class="cellrowborder" valign="top" width="16%" headers="mcps1.1.5.1.3 "><p id="a7652c4c955e74e19b94ffc0076630907"><a name="a7652c4c955e74e19b94ffc0076630907"></a><a name="a7652c4c955e74e19b94ffc0076630907"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="afe14deaff7be4bcf911c2a3acc9fb025"><a name="afe14deaff7be4bcf911c2a3acc9fb025"></a><a name="afe14deaff7be4bcf911c2a3acc9fb025"></a>Scale unit. Four options are available: <strong id="b1222619369215"><a name="b1222619369215"></a><a name="b1222619369215"></a>imperial</strong>, <strong id="b109683917218"><a name="b109683917218"></a><a name="b109683917218"></a>nautical</strong>, and <strong id="b79161441626"><a name="b79161441626"></a><a name="b79161441626"></a>metric</strong>. The default value is <strong id="b1497145315214"><a name="b1497145315214"></a><a name="b1497145315214"></a>metric</strong>.</p>
</td>
</tr>
</tbody>
</table>

## LanguageCode<a name="sbeecdc5106da48ea8df14cd730975c40"></a>

<a name="table18568536173213"></a>
<table><thead align="left"><tr id="row2056813613210"><th class="cellrowborder" valign="top" width="33.33333333333333%" id="mcps1.1.4.1.1"><p id="p756863613216"><a name="p756863613216"></a><a name="p756863613216"></a><strong id="b10891912113310"><a name="b10891912113310"></a><a name="b10891912113310"></a>ISO-639-2</strong></p>
</th>
<th class="cellrowborder" valign="top" width="33.33333333333333%" id="mcps1.1.4.1.2"><p id="p1568636153216"><a name="p1568636153216"></a><a name="p1568636153216"></a><strong id="b6563192338"><a name="b6563192338"></a><a name="b6563192338"></a>BCP 47</strong></p>
</th>
<th class="cellrowborder" valign="top" width="33.33333333333333%" id="mcps1.1.4.1.3"><p id="p195681336163219"><a name="p195681336163219"></a><a name="p195681336163219"></a><strong id="a66d333f0be9649b1b3ae2f0b30d0aee0"><a name="a66d333f0be9649b1b3ae2f0b30d0aee0"></a><a name="a66d333f0be9649b1b3ae2f0b30d0aee0"></a>Language</strong></p>
</th>
</tr>
</thead>
<tbody><tr id="row1956893673213"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p1166462720349"><a name="p1166462720349"></a><a name="p1166462720349"></a>AFR</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p4981161003510"><a name="p4981161003510"></a><a name="p4981161003510"></a>af</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p2071425293617"><a name="p2071425293617"></a><a name="p2071425293617"></a>Afrikaans</p>
</td>
</tr>
<tr id="row556813368329"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p11664102783418"><a name="p11664102783418"></a><a name="p11664102783418"></a>SQI</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p1298112101359"><a name="p1298112101359"></a><a name="p1298112101359"></a>sq</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p15714135215366"><a name="p15714135215366"></a><a name="p15714135215366"></a>Albanian</p>
</td>
</tr>
<tr id="row9568113633212"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p136641272343"><a name="p136641272343"></a><a name="p136641272343"></a>AMH</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p19811210193520"><a name="p19811210193520"></a><a name="p19811210193520"></a>am</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p1871415525364"><a name="p1871415525364"></a><a name="p1871415525364"></a>Amharic</p>
</td>
</tr>
<tr id="row8569183613212"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p1266402763415"><a name="p1266402763415"></a><a name="p1266402763415"></a>AMH</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p15981310183517"><a name="p15981310183517"></a><a name="p15981310183517"></a>am-Latn</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p871445273615"><a name="p871445273615"></a><a name="p871445273615"></a>Amharic</p>
</td>
</tr>
<tr id="row35691136193214"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p1666442743411"><a name="p1666442743411"></a><a name="p1666442743411"></a>ARA</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p17981210163516"><a name="p17981210163516"></a><a name="p17981210163516"></a>ar</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p127141152103613"><a name="p127141152103613"></a><a name="p127141152103613"></a>Arabic</p>
</td>
</tr>
<tr id="row15694364329"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p96641273347"><a name="p96641273347"></a><a name="p96641273347"></a>HYE</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p17981191033516"><a name="p17981191033516"></a><a name="p17981191033516"></a>hy</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p1671455215365"><a name="p1671455215365"></a><a name="p1671455215365"></a>Armenian</p>
</td>
</tr>
<tr id="row14569836103212"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p1066432723414"><a name="p1066432723414"></a><a name="p1066432723414"></a>HYE</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p1398191013517"><a name="p1398191013517"></a><a name="p1398191013517"></a>hy-Latn</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p1671445218368"><a name="p1671445218368"></a><a name="p1671445218368"></a>Armenian</p>
</td>
</tr>
<tr id="row175691336103215"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p2664112718346"><a name="p2664112718346"></a><a name="p2664112718346"></a>ASM</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p598101033514"><a name="p598101033514"></a><a name="p598101033514"></a>as-Latn</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p1171495219368"><a name="p1171495219368"></a><a name="p1171495219368"></a>Assamese</p>
</td>
</tr>
<tr id="row556993633215"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p166641427133417"><a name="p166641427133417"></a><a name="p166641427133417"></a>ASM</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p10981110103516"><a name="p10981110103516"></a><a name="p10981110103516"></a>as</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p971485283617"><a name="p971485283617"></a><a name="p971485283617"></a>Assamese</p>
</td>
</tr>
<tr id="row3569036193212"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p7664122712345"><a name="p7664122712345"></a><a name="p7664122712345"></a>AYM</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p598131013352"><a name="p598131013352"></a><a name="p598131013352"></a>ay</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p17714452113617"><a name="p17714452113617"></a><a name="p17714452113617"></a>Aymara</p>
</td>
</tr>
<tr id="row105691936173210"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p1664527193418"><a name="p1664527193418"></a><a name="p1664527193418"></a>AZE</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p5981111093512"><a name="p5981111093512"></a><a name="p5981111093512"></a>az</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p17142525362"><a name="p17142525362"></a><a name="p17142525362"></a>Azerbaijani</p>
</td>
</tr>
<tr id="row16569536133211"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p136646279348"><a name="p136646279348"></a><a name="p136646279348"></a>BAQ</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p169816108356"><a name="p169816108356"></a><a name="p169816108356"></a>eu</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p12714452193617"><a name="p12714452193617"></a><a name="p12714452193617"></a>Basque</p>
</td>
</tr>
<tr id="row35701436143212"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p16664162763417"><a name="p16664162763417"></a><a name="p16664162763417"></a>BEL</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p19982191053519"><a name="p19982191053519"></a><a name="p19982191053519"></a>be-Latn</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p171425211365"><a name="p171425211365"></a><a name="p171425211365"></a>Belarusian</p>
</td>
</tr>
<tr id="row10570336153213"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p4664192713348"><a name="p4664192713348"></a><a name="p4664192713348"></a>BEL</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p698211003519"><a name="p698211003519"></a><a name="p698211003519"></a>be</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p67151529360"><a name="p67151529360"></a><a name="p67151529360"></a>Belarusian</p>
</td>
</tr>
<tr id="row19570123619328"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p106641827173411"><a name="p106641827173411"></a><a name="p106641827173411"></a>BEN</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p11982101010356"><a name="p11982101010356"></a><a name="p11982101010356"></a>bn-Latn</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p207151527366"><a name="p207151527366"></a><a name="p207151527366"></a>Bengali</p>
</td>
</tr>
<tr id="row12570193619324"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p16641327123416"><a name="p16641327123416"></a><a name="p16641327123416"></a>BEN</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p1498271019358"><a name="p1498271019358"></a><a name="p1498271019358"></a>bn</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p207151852143616"><a name="p207151852143616"></a><a name="p207151852143616"></a>Bengali</p>
</td>
</tr>
<tr id="row65701836153216"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p26651827123418"><a name="p26651827123418"></a><a name="p26651827123418"></a>BIS</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p198221012356"><a name="p198221012356"></a><a name="p198221012356"></a>bi</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p147151652133614"><a name="p147151652133614"></a><a name="p147151652133614"></a>Bislama</p>
</td>
</tr>
<tr id="row18570113619320"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p466517272348"><a name="p466517272348"></a><a name="p466517272348"></a>BOS</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p198221019356"><a name="p198221019356"></a><a name="p198221019356"></a>bs</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p20715135214369"><a name="p20715135214369"></a><a name="p20715135214369"></a>Bosnian</p>
</td>
</tr>
<tr id="row9570636153210"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p156651627123412"><a name="p156651627123412"></a><a name="p156651627123412"></a>BRE</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p2098241083516"><a name="p2098241083516"></a><a name="p2098241083516"></a>br</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p2071555210366"><a name="p2071555210366"></a><a name="p2071555210366"></a>Breton</p>
</td>
</tr>
<tr id="row14570143612329"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p2665627143412"><a name="p2665627143412"></a><a name="p2665627143412"></a>BUL</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p15982310143512"><a name="p15982310143512"></a><a name="p15982310143512"></a>bg-Latn</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p871516525363"><a name="p871516525363"></a><a name="p871516525363"></a>Bulgarian</p>
</td>
</tr>
<tr id="row1157013369326"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p76651927133417"><a name="p76651927133417"></a><a name="p76651927133417"></a>BUL</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p159826100351"><a name="p159826100351"></a><a name="p159826100351"></a>bg</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p127151052163617"><a name="p127151052163617"></a><a name="p127151052163617"></a>Bulgarian</p>
</td>
</tr>
<tr id="row4571193623214"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p2066582712344"><a name="p2066582712344"></a><a name="p2066582712344"></a>BUR</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p14982310193516"><a name="p14982310193516"></a><a name="p14982310193516"></a>my</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p571585273618"><a name="p571585273618"></a><a name="p571585273618"></a>Burmese</p>
</td>
</tr>
<tr id="row12571163618327"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p18665227103419"><a name="p18665227103419"></a><a name="p18665227103419"></a>CAT</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p189825107355"><a name="p189825107355"></a><a name="p189825107355"></a>ca</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p371505283618"><a name="p371505283618"></a><a name="p371505283618"></a>Catalan; Valencian</p>
</td>
</tr>
<tr id="row457133623212"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p866532713415"><a name="p866532713415"></a><a name="p866532713415"></a>CHI</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p798261073519"><a name="p798261073519"></a><a name="p798261073519"></a>zh</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p1771517529364"><a name="p1771517529364"></a><a name="p1771517529364"></a>Chinese</p>
</td>
</tr>
<tr id="row10571193683218"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p1665172723413"><a name="p1665172723413"></a><a name="p1665172723413"></a>ZHO</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p1598231013514"><a name="p1598231013514"></a><a name="p1598231013514"></a>zh-Hant</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p9715155217366"><a name="p9715155217366"></a><a name="p9715155217366"></a>Traditional Chinese</p>
</td>
</tr>
<tr id="row20571113618326"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p186651327133419"><a name="p186651327133419"></a><a name="p186651327133419"></a>CES</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p59829106352"><a name="p59829106352"></a><a name="p59829106352"></a>cs</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p6715452163613"><a name="p6715452163613"></a><a name="p6715452163613"></a>Czech</p>
</td>
</tr>
<tr id="row19571193633216"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p766522716346"><a name="p766522716346"></a><a name="p766522716346"></a>DAN</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p19982121033510"><a name="p19982121033510"></a><a name="p19982121033510"></a>da</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p3715115243618"><a name="p3715115243618"></a><a name="p3715115243618"></a>Danish</p>
</td>
</tr>
<tr id="row457183616329"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p13665927103420"><a name="p13665927103420"></a><a name="p13665927103420"></a>DIV</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p209821310143513"><a name="p209821310143513"></a><a name="p209821310143513"></a>dv</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p177159522367"><a name="p177159522367"></a><a name="p177159522367"></a>Divehi; Dhivehi; Maldivian</p>
</td>
</tr>
<tr id="row14571123614327"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p36657275344"><a name="p36657275344"></a><a name="p36657275344"></a>NLD</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p189821710153520"><a name="p189821710153520"></a><a name="p189821710153520"></a>nl</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p197151052113617"><a name="p197151052113617"></a><a name="p197151052113617"></a>Dutch; Flemish</p>
</td>
</tr>
<tr id="row657243613322"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p266516275344"><a name="p266516275344"></a><a name="p266516275344"></a>DZO</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p169821110183518"><a name="p169821110183518"></a><a name="p169821110183518"></a>dz</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p8715125213367"><a name="p8715125213367"></a><a name="p8715125213367"></a>Dzongkha</p>
</td>
</tr>
<tr id="row11572173643217"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p146651427163416"><a name="p146651427163416"></a><a name="p146651427163416"></a>ENG</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p11982121020358"><a name="p11982121020358"></a><a name="p11982121020358"></a>en</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p27151952183610"><a name="p27151952183610"></a><a name="p27151952183610"></a>English</p>
</td>
</tr>
<tr id="row3572173615329"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p15665132773419"><a name="p15665132773419"></a><a name="p15665132773419"></a>EST</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p498211012357"><a name="p498211012357"></a><a name="p498211012357"></a>et</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p13715195213612"><a name="p13715195213612"></a><a name="p13715195213612"></a>Estonian</p>
</td>
</tr>
<tr id="row14572133611327"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p206651327163416"><a name="p206651327163416"></a><a name="p206651327163416"></a>FAO</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p99831210143519"><a name="p99831210143519"></a><a name="p99831210143519"></a>fo</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p871575216361"><a name="p871575216361"></a><a name="p871575216361"></a>Faroese</p>
</td>
</tr>
<tr id="row65721936193216"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p1966512783416"><a name="p1966512783416"></a><a name="p1966512783416"></a>FIJ</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p159831107359"><a name="p159831107359"></a><a name="p159831107359"></a>fj</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p8716185233617"><a name="p8716185233617"></a><a name="p8716185233617"></a>Fijian</p>
</td>
</tr>
<tr id="row4572203618324"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p12665142753417"><a name="p12665142753417"></a><a name="p12665142753417"></a>FIL</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p298314108356"><a name="p298314108356"></a><a name="p298314108356"></a>tl</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p13716155233620"><a name="p13716155233620"></a><a name="p13716155233620"></a>Tagalog</p>
</td>
</tr>
<tr id="row1857213617327"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p666522753414"><a name="p666522753414"></a><a name="p666522753414"></a>FIN</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p1498331019354"><a name="p1498331019354"></a><a name="p1498331019354"></a>fi</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p2716752203616"><a name="p2716752203616"></a><a name="p2716752203616"></a>Finnish</p>
</td>
</tr>
<tr id="row457216368324"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p26661277346"><a name="p26661277346"></a><a name="p26661277346"></a>FRA</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p498318102353"><a name="p498318102353"></a><a name="p498318102353"></a>fr</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p17716175243612"><a name="p17716175243612"></a><a name="p17716175243612"></a>French</p>
</td>
</tr>
<tr id="row115721036173214"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p466611270345"><a name="p466611270345"></a><a name="p466611270345"></a>FRY</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p11983110163518"><a name="p11983110163518"></a><a name="p11983110163518"></a>fy</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p13716185218361"><a name="p13716185218361"></a><a name="p13716185218361"></a>Western Frisian</p>
</td>
</tr>
<tr id="row1657323673211"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p1766642763414"><a name="p1766642763414"></a><a name="p1766642763414"></a>KAT</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p698391020354"><a name="p698391020354"></a><a name="p698391020354"></a>ka</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p13716552103617"><a name="p13716552103617"></a><a name="p13716552103617"></a>Georgian</p>
</td>
</tr>
<tr id="row16573183663212"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p9666202716348"><a name="p9666202716348"></a><a name="p9666202716348"></a>KAT</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p7983191018359"><a name="p7983191018359"></a><a name="p7983191018359"></a>ka-Latn</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p12716125223616"><a name="p12716125223616"></a><a name="p12716125223616"></a>Georgian</p>
</td>
</tr>
<tr id="row1957373673217"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p16666202710347"><a name="p16666202710347"></a><a name="p16666202710347"></a>DEU</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p1998371011354"><a name="p1998371011354"></a><a name="p1998371011354"></a>de</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p871625214369"><a name="p871625214369"></a><a name="p871625214369"></a>German</p>
</td>
</tr>
<tr id="row1857323613214"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p1566612710345"><a name="p1566612710345"></a><a name="p1566612710345"></a>GLA</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p1983171043513"><a name="p1983171043513"></a><a name="p1983171043513"></a>gd</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p18716175218362"><a name="p18716175218362"></a><a name="p18716175218362"></a>Gaelic; Scottish Gaelic</p>
</td>
</tr>
<tr id="row357319363322"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p176677272341"><a name="p176677272341"></a><a name="p176677272341"></a>GLE</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p8983410193517"><a name="p8983410193517"></a><a name="p8983410193517"></a>ga</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p4716175263610"><a name="p4716175263610"></a><a name="p4716175263610"></a>Irish</p>
</td>
</tr>
<tr id="row16573153633218"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p1266772711342"><a name="p1266772711342"></a><a name="p1266772711342"></a>GLG</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p498331053514"><a name="p498331053514"></a><a name="p498331053514"></a>gl</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p071614526363"><a name="p071614526363"></a><a name="p071614526363"></a>Galician</p>
</td>
</tr>
<tr id="row11573203611323"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p116671227103417"><a name="p116671227103417"></a><a name="p116671227103417"></a>ELL</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p1098331013356"><a name="p1098331013356"></a><a name="p1098331013356"></a>el</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p9716195217362"><a name="p9716195217362"></a><a name="p9716195217362"></a>Greek, Modern (1453-)</p>
</td>
</tr>
<tr id="row657333611327"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p3667132715344"><a name="p3667132715344"></a><a name="p3667132715344"></a>ELL</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p149836104356"><a name="p149836104356"></a><a name="p149836104356"></a>el-Latn</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p671612527362"><a name="p671612527362"></a><a name="p671612527362"></a>Greek, Modern (1453-)</p>
</td>
</tr>
<tr id="row17574103673210"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p566717273343"><a name="p566717273343"></a><a name="p566717273343"></a>GRN</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p698311093519"><a name="p698311093519"></a><a name="p698311093519"></a>gn</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p4716115213619"><a name="p4716115213619"></a><a name="p4716115213619"></a>Guarani</p>
</td>
</tr>
<tr id="row2574136203216"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p106674275343"><a name="p106674275343"></a><a name="p106674275343"></a>GUJ</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p1198321019354"><a name="p1198321019354"></a><a name="p1198321019354"></a>gu-Latn</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p97164527367"><a name="p97164527367"></a><a name="p97164527367"></a>Gujarati</p>
</td>
</tr>
<tr id="row17574123616326"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p9667182723415"><a name="p9667182723415"></a><a name="p9667182723415"></a>GUJ</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p14983191063512"><a name="p14983191063512"></a><a name="p14983191063512"></a>gu</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p1571610528363"><a name="p1571610528363"></a><a name="p1571610528363"></a>Gujarati</p>
</td>
</tr>
<tr id="row15574836143214"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p15667112719344"><a name="p15667112719344"></a><a name="p15667112719344"></a>HAT</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p5983510143518"><a name="p5983510143518"></a><a name="p5983510143518"></a>ht</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p15716135216368"><a name="p15716135216368"></a><a name="p15716135216368"></a>Haitian; Haitian Creole</p>
</td>
</tr>
<tr id="row1057483617320"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p366782715340"><a name="p366782715340"></a><a name="p366782715340"></a>HAU</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p7983101063510"><a name="p7983101063510"></a><a name="p7983101063510"></a>ha</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p071619523369"><a name="p071619523369"></a><a name="p071619523369"></a>Hausa</p>
</td>
</tr>
<tr id="row75745364324"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p16667152712347"><a name="p16667152712347"></a><a name="p16667152712347"></a>HEB</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p6983110133519"><a name="p6983110133519"></a><a name="p6983110133519"></a>he-Latn</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p8716165210363"><a name="p8716165210363"></a><a name="p8716165210363"></a>Hebrew</p>
</td>
</tr>
<tr id="row155741036153213"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p1766712733415"><a name="p1766712733415"></a><a name="p1766712733415"></a>HEB</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p139841310203520"><a name="p139841310203520"></a><a name="p139841310203520"></a>he</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p27161523367"><a name="p27161523367"></a><a name="p27161523367"></a>Hebrew</p>
</td>
</tr>
<tr id="row857493663215"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p1766716271342"><a name="p1766716271342"></a><a name="p1766716271342"></a>HIN</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p19984191083510"><a name="p19984191083510"></a><a name="p19984191083510"></a>hi-Latn</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p1971614525367"><a name="p1971614525367"></a><a name="p1971614525367"></a>Hindi</p>
</td>
</tr>
<tr id="row125751636143217"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p566722763410"><a name="p566722763410"></a><a name="p566722763410"></a>HIN</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p1998461018352"><a name="p1998461018352"></a><a name="p1998461018352"></a>hi</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p16717152183617"><a name="p16717152183617"></a><a name="p16717152183617"></a>Hindi</p>
</td>
</tr>
<tr id="row16575133610323"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p666702710342"><a name="p666702710342"></a><a name="p666702710342"></a>HMO</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p1198410100358"><a name="p1198410100358"></a><a name="p1198410100358"></a>ho</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p18717145263619"><a name="p18717145263619"></a><a name="p18717145263619"></a>Hiri Motu</p>
</td>
</tr>
<tr id="row557511364321"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p1966852723417"><a name="p1966852723417"></a><a name="p1966852723417"></a>HUN</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p129842108352"><a name="p129842108352"></a><a name="p129842108352"></a>hu</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p107173526365"><a name="p107173526365"></a><a name="p107173526365"></a>Hungarian</p>
</td>
</tr>
<tr id="row18575113693210"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p10668132773420"><a name="p10668132773420"></a><a name="p10668132773420"></a>IBO</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p49851810123520"><a name="p49851810123520"></a><a name="p49851810123520"></a>ig</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p1171795223611"><a name="p1171795223611"></a><a name="p1171795223611"></a>Igbo</p>
</td>
</tr>
<tr id="row11575113616324"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p12668162723412"><a name="p12668162723412"></a><a name="p12668162723412"></a>ISL</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p109853105357"><a name="p109853105357"></a><a name="p109853105357"></a>is</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p15717125218368"><a name="p15717125218368"></a><a name="p15717125218368"></a>Icelandic</p>
</td>
</tr>
<tr id="row145751361320"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p11668152773418"><a name="p11668152773418"></a><a name="p11668152773418"></a>IKU</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p1498541053520"><a name="p1498541053520"></a><a name="p1498541053520"></a>iu</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p1471712523369"><a name="p1471712523369"></a><a name="p1471712523369"></a>Inuktitut</p>
</td>
</tr>
<tr id="row19575133616321"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p1766862715341"><a name="p1766862715341"></a><a name="p1766862715341"></a>IND</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p698581013357"><a name="p698581013357"></a><a name="p698581013357"></a>id</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p1571714526364"><a name="p1571714526364"></a><a name="p1571714526364"></a>Indonesian</p>
</td>
</tr>
<tr id="row175758362326"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p15668102763412"><a name="p15668102763412"></a><a name="p15668102763412"></a>ITA</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p9985110103515"><a name="p9985110103515"></a><a name="p9985110103515"></a>it</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p17172521369"><a name="p17172521369"></a><a name="p17172521369"></a>Italian</p>
</td>
</tr>
<tr id="row145761636113219"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p12668127103417"><a name="p12668127103417"></a><a name="p12668127103417"></a>JPN</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p15985510203518"><a name="p15985510203518"></a><a name="p15985510203518"></a>ja-Latn</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p19717135213366"><a name="p19717135213366"></a><a name="p19717135213366"></a>Japanese</p>
</td>
</tr>
<tr id="row357617361321"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p1466818276346"><a name="p1466818276346"></a><a name="p1466818276346"></a>JPN</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p198571012353"><a name="p198571012353"></a><a name="p198571012353"></a>ja</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p171715243612"><a name="p171715243612"></a><a name="p171715243612"></a>Japanese</p>
</td>
</tr>
<tr id="row185761136183210"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p9668162716348"><a name="p9668162716348"></a><a name="p9668162716348"></a>KAL</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p398531003514"><a name="p398531003514"></a><a name="p398531003514"></a>kl</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p1971735211361"><a name="p1971735211361"></a><a name="p1971735211361"></a>Kalaallisut; Greenlandic</p>
</td>
</tr>
<tr id="row957623603211"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p14668192710345"><a name="p14668192710345"></a><a name="p14668192710345"></a>KAN</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p1498510101358"><a name="p1498510101358"></a><a name="p1498510101358"></a>kn-Latn</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p1771735211369"><a name="p1771735211369"></a><a name="p1771735211369"></a>Kannada</p>
</td>
</tr>
<tr id="row85761236113210"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p36681627183415"><a name="p36681627183415"></a><a name="p36681627183415"></a>KAN</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p12985710173515"><a name="p12985710173515"></a><a name="p12985710173515"></a>kn</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p571719526361"><a name="p571719526361"></a><a name="p571719526361"></a>Kannada</p>
</td>
</tr>
<tr id="row10576173633219"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p3668122715345"><a name="p3668122715345"></a><a name="p3668122715345"></a>KAS</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p4985121014356"><a name="p4985121014356"></a><a name="p4985121014356"></a>ks</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p27171452143611"><a name="p27171452143611"></a><a name="p27171452143611"></a>Kashmiri</p>
</td>
</tr>
<tr id="row45761361324"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p566862718348"><a name="p566862718348"></a><a name="p566862718348"></a>KAZ</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p1698513103358"><a name="p1698513103358"></a><a name="p1698513103358"></a>kk-Latn</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p971785253619"><a name="p971785253619"></a><a name="p971785253619"></a>Kazakh</p>
</td>
</tr>
<tr id="row7576836163210"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p19668152753419"><a name="p19668152753419"></a><a name="p19668152753419"></a>KAZ</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p1298521019356"><a name="p1298521019356"></a><a name="p1298521019356"></a>kk</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p117171852153612"><a name="p117171852153612"></a><a name="p117171852153612"></a>Kazakh</p>
</td>
</tr>
<tr id="row45761736173212"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p6668102713344"><a name="p6668102713344"></a><a name="p6668102713344"></a>KHM</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p5985510173514"><a name="p5985510173514"></a><a name="p5985510173514"></a>km-Latn</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p371718529369"><a name="p371718529369"></a><a name="p371718529369"></a>Central Khmer</p>
</td>
</tr>
<tr id="row15577143616325"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p10668027193410"><a name="p10668027193410"></a><a name="p10668027193410"></a>KHM</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p1798571013356"><a name="p1798571013356"></a><a name="p1798571013356"></a>km</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p4717952173615"><a name="p4717952173615"></a><a name="p4717952173615"></a>Central Khmer</p>
</td>
</tr>
<tr id="row18577173633214"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p116681527133415"><a name="p116681527133415"></a><a name="p116681527133415"></a>KIN</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p498514100358"><a name="p498514100358"></a><a name="p498514100358"></a>rw</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p67171052123612"><a name="p67171052123612"></a><a name="p67171052123612"></a>Kinyarwanda</p>
</td>
</tr>
<tr id="row1357720362327"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p366852718347"><a name="p366852718347"></a><a name="p366852718347"></a>KIR</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p4986710163512"><a name="p4986710163512"></a><a name="p4986710163512"></a>ky-Latn</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p571735293612"><a name="p571735293612"></a><a name="p571735293612"></a>Kirghiz; Kyrgyz</p>
</td>
</tr>
<tr id="row1557717366322"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p116687275344"><a name="p116687275344"></a><a name="p116687275344"></a>KIR</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p1798616102356"><a name="p1798616102356"></a><a name="p1798616102356"></a>ky</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p1571813522365"><a name="p1571813522365"></a><a name="p1571813522365"></a>Kirghiz; Kyrgyz</p>
</td>
</tr>
<tr id="row65771536113212"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p166817275344"><a name="p166817275344"></a><a name="p166817275344"></a>KOR</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p5986171063514"><a name="p5986171063514"></a><a name="p5986171063514"></a>ko-Latn</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p17181052173614"><a name="p17181052173614"></a><a name="p17181052173614"></a>Korean</p>
</td>
</tr>
<tr id="row1957714365323"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p8668327153410"><a name="p8668327153410"></a><a name="p8668327153410"></a>KOR</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p14986161063513"><a name="p14986161063513"></a><a name="p14986161063513"></a>ko</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p1271815526365"><a name="p1271815526365"></a><a name="p1271815526365"></a>Korean</p>
</td>
</tr>
<tr id="row757715364327"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p116691327113415"><a name="p116691327113415"></a><a name="p116691327113415"></a>KUR</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p9986510103517"><a name="p9986510103517"></a><a name="p9986510103517"></a>ku-Latn</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p471815523365"><a name="p471815523365"></a><a name="p471815523365"></a>Kurdish</p>
</td>
</tr>
<tr id="row195770365328"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p176691527193411"><a name="p176691527193411"></a><a name="p176691527193411"></a>KUR</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p7986111063514"><a name="p7986111063514"></a><a name="p7986111063514"></a>ku</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p13718205253619"><a name="p13718205253619"></a><a name="p13718205253619"></a>Kurdish</p>
</td>
</tr>
<tr id="row4578103613214"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p66694274348"><a name="p66694274348"></a><a name="p66694274348"></a>LAO</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p398616102355"><a name="p398616102355"></a><a name="p398616102355"></a>lo</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p107181852163616"><a name="p107181852163616"></a><a name="p107181852163616"></a>Lao</p>
</td>
</tr>
<tr id="row3578036123211"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p13669927103412"><a name="p13669927103412"></a><a name="p13669927103412"></a>LAT</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p798614106355"><a name="p798614106355"></a><a name="p798614106355"></a>la</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p9718195263613"><a name="p9718195263613"></a><a name="p9718195263613"></a>Latin</p>
</td>
</tr>
<tr id="row45788365324"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p1366919278341"><a name="p1366919278341"></a><a name="p1366919278341"></a>LAV</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p209869104355"><a name="p209869104355"></a><a name="p209869104355"></a>lv</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p57189528363"><a name="p57189528363"></a><a name="p57189528363"></a>Latvian</p>
</td>
</tr>
<tr id="row957823663214"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p18669162719349"><a name="p18669162719349"></a><a name="p18669162719349"></a>LIT</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p14986210123520"><a name="p14986210123520"></a><a name="p14986210123520"></a>lt</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p16718135243615"><a name="p16718135243615"></a><a name="p16718135243615"></a>Lithuanian</p>
</td>
</tr>
<tr id="row11578113615320"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p566918271346"><a name="p566918271346"></a><a name="p566918271346"></a>LTZ</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p1098621018353"><a name="p1098621018353"></a><a name="p1098621018353"></a>lb</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p57181523368"><a name="p57181523368"></a><a name="p57181523368"></a>Luxembourgish; Letzeburgesch</p>
</td>
</tr>
<tr id="row12578103611322"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p116692027103419"><a name="p116692027103419"></a><a name="p116692027103419"></a>MKD</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p79861610173516"><a name="p79861610173516"></a><a name="p79861610173516"></a>mk-Latn</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p871815214367"><a name="p871815214367"></a><a name="p871815214367"></a>Macedonian</p>
</td>
</tr>
<tr id="row165781636113214"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p5669202711349"><a name="p5669202711349"></a><a name="p5669202711349"></a>MKD</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p16986171013511"><a name="p16986171013511"></a><a name="p16986171013511"></a>mk</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p1171815203615"><a name="p1171815203615"></a><a name="p1171815203615"></a>Macedonian</p>
</td>
</tr>
<tr id="row175781436113219"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p266912713416"><a name="p266912713416"></a><a name="p266912713416"></a>MAH</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p4986141014358"><a name="p4986141014358"></a><a name="p4986141014358"></a>mh</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p1471855293615"><a name="p1471855293615"></a><a name="p1471855293615"></a>Marshallese</p>
</td>
</tr>
<tr id="row8578163612328"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p366920273341"><a name="p366920273341"></a><a name="p366920273341"></a>MAL</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p1986191013512"><a name="p1986191013512"></a><a name="p1986191013512"></a>ml</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p1671805223616"><a name="p1671805223616"></a><a name="p1671805223616"></a>Malayalam</p>
</td>
</tr>
<tr id="row75797360322"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p196691327103410"><a name="p196691327103410"></a><a name="p196691327103410"></a>MAL</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p6986121013512"><a name="p6986121013512"></a><a name="p6986121013512"></a>ml-Latn</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p1771865203617"><a name="p1771865203617"></a><a name="p1771865203617"></a>Malayalam</p>
</td>
</tr>
<tr id="row057911367325"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p1566982733417"><a name="p1566982733417"></a><a name="p1566982733417"></a>MRI</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p1898621019355"><a name="p1898621019355"></a><a name="p1898621019355"></a>mi</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p17189523362"><a name="p17189523362"></a><a name="p17189523362"></a>Maori</p>
</td>
</tr>
<tr id="row17579163613215"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p1766972720341"><a name="p1766972720341"></a><a name="p1766972720341"></a>MAR</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p298610102352"><a name="p298610102352"></a><a name="p298610102352"></a>mr-Latn</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p167186529363"><a name="p167186529363"></a><a name="p167186529363"></a>Marathi</p>
</td>
</tr>
<tr id="row357913673211"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p19669192712347"><a name="p19669192712347"></a><a name="p19669192712347"></a>MAR</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p1598621014352"><a name="p1598621014352"></a><a name="p1598621014352"></a>mr</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p147181052113610"><a name="p147181052113610"></a><a name="p147181052113610"></a>Marathi</p>
</td>
</tr>
<tr id="row1357983653219"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p1766919274348"><a name="p1766919274348"></a><a name="p1766919274348"></a>MSA</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p998661063510"><a name="p998661063510"></a><a name="p998661063510"></a>ms</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p1771815218364"><a name="p1771815218364"></a><a name="p1771815218364"></a>Malay</p>
</td>
</tr>
<tr id="row175795367329"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p8669132713345"><a name="p8669132713345"></a><a name="p8669132713345"></a>MLG</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p1398651023517"><a name="p1398651023517"></a><a name="p1398651023517"></a>mg</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p4718115219368"><a name="p4718115219368"></a><a name="p4718115219368"></a>Malagasy</p>
</td>
</tr>
<tr id="row185797367322"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p56691927113410"><a name="p56691927113410"></a><a name="p56691927113410"></a>MLT</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p39878107356"><a name="p39878107356"></a><a name="p39878107356"></a>mt</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p27181552143615"><a name="p27181552143615"></a><a name="p27181552143615"></a>Maltese</p>
</td>
</tr>
<tr id="row7579436163210"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p866972711341"><a name="p866972711341"></a><a name="p866972711341"></a>MON</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p109871310173517"><a name="p109871310173517"></a><a name="p109871310173517"></a>mn-Latn</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p871914529364"><a name="p871914529364"></a><a name="p871914529364"></a>Mongolian</p>
</td>
</tr>
<tr id="row1579133663214"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p767042713417"><a name="p767042713417"></a><a name="p767042713417"></a>MON</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p1298711107354"><a name="p1298711107354"></a><a name="p1298711107354"></a>mn</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p117195528366"><a name="p117195528366"></a><a name="p117195528366"></a>Mongolian</p>
</td>
</tr>
<tr id="row95807362327"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p1367017275344"><a name="p1367017275344"></a><a name="p1367017275344"></a>NAU</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p13987201015359"><a name="p13987201015359"></a><a name="p13987201015359"></a>na</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p871915526365"><a name="p871915526365"></a><a name="p871915526365"></a>Nauru</p>
</td>
</tr>
<tr id="row1758093618326"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p12670182743416"><a name="p12670182743416"></a><a name="p12670182743416"></a>NDE</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p11987210203517"><a name="p11987210203517"></a><a name="p11987210203517"></a>nd</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p4719125233616"><a name="p4719125233616"></a><a name="p4719125233616"></a>Ndebele, North; North Ndebele</p>
</td>
</tr>
<tr id="row1458053617328"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p867062733418"><a name="p867062733418"></a><a name="p867062733418"></a>NEP</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p7987141043511"><a name="p7987141043511"></a><a name="p7987141043511"></a>ne-Latn</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p67195521367"><a name="p67195521367"></a><a name="p67195521367"></a>Nepali</p>
</td>
</tr>
<tr id="row195807361323"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p2670182717340"><a name="p2670182717340"></a><a name="p2670182717340"></a>NEP</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p1898771093518"><a name="p1898771093518"></a><a name="p1898771093518"></a>ne</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p5719205263619"><a name="p5719205263619"></a><a name="p5719205263619"></a>Nepali</p>
</td>
</tr>
<tr id="row65807368326"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p12670192713412"><a name="p12670192713412"></a><a name="p12670192713412"></a>NOR</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p998719102352"><a name="p998719102352"></a><a name="p998719102352"></a>no</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p12719652163619"><a name="p12719652163619"></a><a name="p12719652163619"></a>Norwegian</p>
</td>
</tr>
<tr id="row0580123611325"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p13670102714347"><a name="p13670102714347"></a><a name="p13670102714347"></a>NYA</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p159872106354"><a name="p159872106354"></a><a name="p159872106354"></a>ny</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p371913524367"><a name="p371913524367"></a><a name="p371913524367"></a>Chichewa; Chewa; Nyanja</p>
</td>
</tr>
<tr id="row20580236163213"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p1167042712347"><a name="p1167042712347"></a><a name="p1167042712347"></a>OCI</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p1698751013359"><a name="p1698751013359"></a><a name="p1698751013359"></a>oc</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p117191152193610"><a name="p117191152193610"></a><a name="p117191152193610"></a>Occitan (post 1500)</p>
</td>
</tr>
<tr id="row1858043613210"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p1867082711342"><a name="p1867082711342"></a><a name="p1867082711342"></a>ORI</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p1198721073518"><a name="p1198721073518"></a><a name="p1198721073518"></a>or-Latn</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p2071913526368"><a name="p2071913526368"></a><a name="p2071913526368"></a>Oriya</p>
</td>
</tr>
<tr id="row1658012361323"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p13670627103410"><a name="p13670627103410"></a><a name="p13670627103410"></a>ORI</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p3987171023518"><a name="p3987171023518"></a><a name="p3987171023518"></a>or</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p13719115216364"><a name="p13719115216364"></a><a name="p13719115216364"></a>Oriya</p>
</td>
</tr>
<tr id="row1058113673215"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p8670127163416"><a name="p8670127163416"></a><a name="p8670127163416"></a>ORM</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p698719102355"><a name="p698719102355"></a><a name="p698719102355"></a>om</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p12719952173614"><a name="p12719952173614"></a><a name="p12719952173614"></a>Oromo</p>
</td>
</tr>
<tr id="row135813366327"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p17670132783413"><a name="p17670132783413"></a><a name="p17670132783413"></a>PAN</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p18987151043513"><a name="p18987151043513"></a><a name="p18987151043513"></a>pa</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p3719135217365"><a name="p3719135217365"></a><a name="p3719135217365"></a>Punjabi, Panjabi</p>
</td>
</tr>
<tr id="row75819369322"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p36701527183413"><a name="p36701527183413"></a><a name="p36701527183413"></a>PAN</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p12987101023519"><a name="p12987101023519"></a><a name="p12987101023519"></a>pa-Latn</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p15719125223617"><a name="p15719125223617"></a><a name="p15719125223617"></a>Punjabi, Panjabi</p>
</td>
</tr>
<tr id="row558113633212"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p467012793412"><a name="p467012793412"></a><a name="p467012793412"></a>PAN</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p209876102355"><a name="p209876102355"></a><a name="p209876102355"></a>pa-Arab</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p771985283612"><a name="p771985283612"></a><a name="p771985283612"></a>Punjabi, Panjabi</p>
</td>
</tr>
<tr id="row45811736193211"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p16709273343"><a name="p16709273343"></a><a name="p16709273343"></a>PAN</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p3987201073519"><a name="p3987201073519"></a><a name="p3987201073519"></a>pa-Guru</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p9719175212368"><a name="p9719175212368"></a><a name="p9719175212368"></a>Punjabi, Panjabi</p>
</td>
</tr>
<tr id="row20581136123219"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p4670152717340"><a name="p4670152717340"></a><a name="p4670152717340"></a>FAS</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p1298731043510"><a name="p1298731043510"></a><a name="p1298731043510"></a>fa-Latn</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p17719205215369"><a name="p17719205215369"></a><a name="p17719205215369"></a>Persian</p>
</td>
</tr>
<tr id="row115811836163212"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p116704271348"><a name="p116704271348"></a><a name="p116704271348"></a>FAS</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p1198761023519"><a name="p1198761023519"></a><a name="p1198761023519"></a>fa</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p8719135213611"><a name="p8719135213611"></a><a name="p8719135213611"></a>Persian</p>
</td>
</tr>
<tr id="row55814362324"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p13670102753411"><a name="p13670102753411"></a><a name="p13670102753411"></a>POL</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p18988181043517"><a name="p18988181043517"></a><a name="p18988181043517"></a>pl</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p10719125263612"><a name="p10719125263612"></a><a name="p10719125263612"></a>Polish</p>
</td>
</tr>
<tr id="row25821136123215"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p66706273348"><a name="p66706273348"></a><a name="p66706273348"></a>POR</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p0988131063517"><a name="p0988131063517"></a><a name="p0988131063517"></a>pt</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p27191525368"><a name="p27191525368"></a><a name="p27191525368"></a>Portuguese</p>
</td>
</tr>
<tr id="row17582183623213"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p12670192743417"><a name="p12670192743417"></a><a name="p12670192743417"></a>PUS</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p8988510163515"><a name="p8988510163515"></a><a name="p8988510163515"></a>ps</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p13720952183613"><a name="p13720952183613"></a><a name="p13720952183613"></a>Pushto; Pashto</p>
</td>
</tr>
<tr id="row105821036173217"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p36711127133413"><a name="p36711127133413"></a><a name="p36711127133413"></a>QUE</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p179881610113512"><a name="p179881610113512"></a><a name="p179881610113512"></a>qu</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p15720652133610"><a name="p15720652133610"></a><a name="p15720652133610"></a>Quechua</p>
</td>
</tr>
<tr id="row158211367321"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p176711727113414"><a name="p176711727113414"></a><a name="p176711727113414"></a>ROH</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p129881410103514"><a name="p129881410103514"></a><a name="p129881410103514"></a>rm</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p107201052123619"><a name="p107201052123619"></a><a name="p107201052123619"></a>Romansh</p>
</td>
</tr>
<tr id="row758293616324"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p166711027113417"><a name="p166711027113417"></a><a name="p166711027113417"></a>RON</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p1198871093518"><a name="p1198871093518"></a><a name="p1198871093518"></a>ro</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p9720165283620"><a name="p9720165283620"></a><a name="p9720165283620"></a>Romanian; Moldavian; Moldovan</p>
</td>
</tr>
<tr id="row85821536173217"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p1067111273347"><a name="p1067111273347"></a><a name="p1067111273347"></a>RUN</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p11988191043519"><a name="p11988191043519"></a><a name="p11988191043519"></a>rn</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p20720852133614"><a name="p20720852133614"></a><a name="p20720852133614"></a>Rundi</p>
</td>
</tr>
<tr id="row1158243673214"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p2067117273340"><a name="p2067117273340"></a><a name="p2067117273340"></a>RUS</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p198881093518"><a name="p198881093518"></a><a name="p198881093518"></a>ru-Latn</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p07201352203618"><a name="p07201352203618"></a><a name="p07201352203618"></a>Russian</p>
</td>
</tr>
<tr id="row105823368325"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p13671827123418"><a name="p13671827123418"></a><a name="p13671827123418"></a>RUS</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p998851053513"><a name="p998851053513"></a><a name="p998851053513"></a>ru</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p187201052113617"><a name="p187201052113617"></a><a name="p187201052113617"></a>Russian</p>
</td>
</tr>
<tr id="row8582736163219"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p167132783418"><a name="p167132783418"></a><a name="p167132783418"></a>SAG</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p1998861017359"><a name="p1998861017359"></a><a name="p1998861017359"></a>sg</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p12720105215369"><a name="p12720105215369"></a><a name="p12720105215369"></a>Sango</p>
</td>
</tr>
<tr id="row10583193619323"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p46711227173419"><a name="p46711227173419"></a><a name="p46711227173419"></a>SAN</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p59881510153512"><a name="p59881510153512"></a><a name="p59881510153512"></a>sa</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p8720135211364"><a name="p8720135211364"></a><a name="p8720135211364"></a>Sanskrit</p>
</td>
</tr>
<tr id="row20583103612327"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p10671527163412"><a name="p10671527163412"></a><a name="p10671527163412"></a>HRV</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p39881103359"><a name="p39881103359"></a><a name="p39881103359"></a>hr</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p1372015216368"><a name="p1372015216368"></a><a name="p1372015216368"></a>Croatian</p>
</td>
</tr>
<tr id="row658313366326"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p186711827173415"><a name="p186711827173415"></a><a name="p186711827173415"></a>SRP</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p99882102356"><a name="p99882102356"></a><a name="p99882102356"></a>sr-Latn</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p87209528369"><a name="p87209528369"></a><a name="p87209528369"></a>Serbian</p>
</td>
</tr>
<tr id="row1258333653213"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p14671132793414"><a name="p14671132793414"></a><a name="p14671132793414"></a>SRP</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p6988910103517"><a name="p6988910103517"></a><a name="p6988910103517"></a>sr</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p472005211368"><a name="p472005211368"></a><a name="p472005211368"></a>Serbian</p>
</td>
</tr>
<tr id="row25833363321"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p17671132716343"><a name="p17671132716343"></a><a name="p17671132716343"></a>SIN</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p59881010113513"><a name="p59881010113513"></a><a name="p59881010113513"></a>si-Latn</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p0720135223610"><a name="p0720135223610"></a><a name="p0720135223610"></a>Sinhala; Sinhalese</p>
</td>
</tr>
<tr id="row115831436163215"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p18671527163417"><a name="p18671527163417"></a><a name="p18671527163417"></a>SIN</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p3988141043514"><a name="p3988141043514"></a><a name="p3988141043514"></a>si</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p207209526362"><a name="p207209526362"></a><a name="p207209526362"></a>Sinhala; Sinhalese</p>
</td>
</tr>
<tr id="row55831936173214"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p1267112277348"><a name="p1267112277348"></a><a name="p1267112277348"></a>SLK</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p14988710123515"><a name="p14988710123515"></a><a name="p14988710123515"></a>sk</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p3720195273618"><a name="p3720195273618"></a><a name="p3720195273618"></a>Slovak</p>
</td>
</tr>
<tr id="row10583153623215"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p10671192715347"><a name="p10671192715347"></a><a name="p10671192715347"></a>SLV</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p10988111063513"><a name="p10988111063513"></a><a name="p10988111063513"></a>sl</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p47201452173615"><a name="p47201452173615"></a><a name="p47201452173615"></a>Slovenian</p>
</td>
</tr>
<tr id="row958319369327"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p6671192716345"><a name="p6671192716345"></a><a name="p6671192716345"></a>SMO</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p898820103359"><a name="p898820103359"></a><a name="p898820103359"></a>sm</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p8720352183614"><a name="p8720352183614"></a><a name="p8720352183614"></a>Samoan</p>
</td>
</tr>
<tr id="row6584136173213"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p467114279344"><a name="p467114279344"></a><a name="p467114279344"></a>SNA</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p149881110113517"><a name="p149881110113517"></a><a name="p149881110113517"></a>sn</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p147201052193612"><a name="p147201052193612"></a><a name="p147201052193612"></a>Shona</p>
</td>
</tr>
<tr id="row858420362327"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p16711927153413"><a name="p16711927153413"></a><a name="p16711927153413"></a>SND</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p6989201011352"><a name="p6989201011352"></a><a name="p6989201011352"></a>sd-Latn</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p1072095273612"><a name="p1072095273612"></a><a name="p1072095273612"></a>Sindhi</p>
</td>
</tr>
<tr id="row155849361328"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p1067119274349"><a name="p1067119274349"></a><a name="p1067119274349"></a>SND</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p698911103359"><a name="p698911103359"></a><a name="p698911103359"></a>sd</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p16720105283618"><a name="p16720105283618"></a><a name="p16720105283618"></a>Sindhi</p>
</td>
</tr>
<tr id="row12584536153216"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p1367116275345"><a name="p1367116275345"></a><a name="p1367116275345"></a>SOM</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p99891810133517"><a name="p99891810133517"></a><a name="p99891810133517"></a>so</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p37201552103619"><a name="p37201552103619"></a><a name="p37201552103619"></a>Somali</p>
</td>
</tr>
<tr id="row45841036173219"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p267210275346"><a name="p267210275346"></a><a name="p267210275346"></a>SOT</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p998911012357"><a name="p998911012357"></a><a name="p998911012357"></a>st</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p19721145211364"><a name="p19721145211364"></a><a name="p19721145211364"></a>Sotho, Southern</p>
</td>
</tr>
<tr id="row3584193683216"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p6672327193411"><a name="p6672327193411"></a><a name="p6672327193411"></a>SPA</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p598914107359"><a name="p598914107359"></a><a name="p598914107359"></a>es</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p17721105220365"><a name="p17721105220365"></a><a name="p17721105220365"></a>Spanish; Castilian</p>
</td>
</tr>
<tr id="row18584193643218"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p11672112743410"><a name="p11672112743410"></a><a name="p11672112743410"></a>SRD</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p498915107354"><a name="p498915107354"></a><a name="p498915107354"></a>sc</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p15721952113617"><a name="p15721952113617"></a><a name="p15721952113617"></a>Sardinian</p>
</td>
</tr>
<tr id="row2584133693215"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p136721827113416"><a name="p136721827113416"></a><a name="p136721827113416"></a>SSW</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p498916100354"><a name="p498916100354"></a><a name="p498916100354"></a>ss</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p27216526364"><a name="p27216526364"></a><a name="p27216526364"></a>Swati</p>
</td>
</tr>
<tr id="row17584136123213"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p46728277343"><a name="p46728277343"></a><a name="p46728277343"></a>SWA</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p59892010193514"><a name="p59892010193514"></a><a name="p59892010193514"></a>sw</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p137211052133612"><a name="p137211052133612"></a><a name="p137211052133612"></a>Swahili</p>
</td>
</tr>
<tr id="row358515363323"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p116728276343"><a name="p116728276343"></a><a name="p116728276343"></a>SWE</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p1298941093516"><a name="p1298941093516"></a><a name="p1298941093516"></a>sv</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p177211525365"><a name="p177211525365"></a><a name="p177211525365"></a>Swedish</p>
</td>
</tr>
<tr id="row358553643215"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p5672152723410"><a name="p5672152723410"></a><a name="p5672152723410"></a>TAH</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p15989131053515"><a name="p15989131053515"></a><a name="p15989131053515"></a>ty</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p6721952183618"><a name="p6721952183618"></a><a name="p6721952183618"></a>Tahitian</p>
</td>
</tr>
<tr id="row1058513610322"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p76721427193418"><a name="p76721427193418"></a><a name="p76721427193418"></a>TAM</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p16989181083516"><a name="p16989181083516"></a><a name="p16989181083516"></a>ta-Latn</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p372135213614"><a name="p372135213614"></a><a name="p372135213614"></a>Tamil</p>
</td>
</tr>
<tr id="row1585153614322"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p19672202715349"><a name="p19672202715349"></a><a name="p19672202715349"></a>TAM</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p1498991014353"><a name="p1498991014353"></a><a name="p1498991014353"></a>ta</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p272105253612"><a name="p272105253612"></a><a name="p272105253612"></a>Tamil</p>
</td>
</tr>
<tr id="row16585636103216"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p1567218271340"><a name="p1567218271340"></a><a name="p1567218271340"></a>TAT</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p798910105355"><a name="p798910105355"></a><a name="p798910105355"></a>tt-Latn</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p17218525368"><a name="p17218525368"></a><a name="p17218525368"></a>Tatar</p>
</td>
</tr>
<tr id="row458593643212"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p1867211275347"><a name="p1867211275347"></a><a name="p1867211275347"></a>TAT</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p69891110203513"><a name="p69891110203513"></a><a name="p69891110203513"></a>tt</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p67211652113614"><a name="p67211652113614"></a><a name="p67211652113614"></a>Tatar</p>
</td>
</tr>
<tr id="row958563610321"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p267242718349"><a name="p267242718349"></a><a name="p267242718349"></a>TEL</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p598981014354"><a name="p598981014354"></a><a name="p598981014354"></a>te-Latn</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p1721125273618"><a name="p1721125273618"></a><a name="p1721125273618"></a>Telugu</p>
</td>
</tr>
<tr id="row1658513613214"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p1967216273344"><a name="p1967216273344"></a><a name="p1967216273344"></a>TEL</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p119895103355"><a name="p119895103355"></a><a name="p119895103355"></a>te</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p872125263614"><a name="p872125263614"></a><a name="p872125263614"></a>Telugu</p>
</td>
</tr>
<tr id="row115854369325"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p14672427193410"><a name="p14672427193410"></a><a name="p14672427193410"></a>TGK</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p198915101353"><a name="p198915101353"></a><a name="p198915101353"></a>tg-Latn</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p372114528364"><a name="p372114528364"></a><a name="p372114528364"></a>Tajik</p>
</td>
</tr>
<tr id="row5586336133218"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p186721427103417"><a name="p186721427103417"></a><a name="p186721427103417"></a>TGK</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p7989010193514"><a name="p7989010193514"></a><a name="p7989010193514"></a>tg</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p11721115213613"><a name="p11721115213613"></a><a name="p11721115213613"></a>Tajik</p>
</td>
</tr>
<tr id="row25861436113217"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p17672112763415"><a name="p17672112763415"></a><a name="p17672112763415"></a>THA</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p59891610163513"><a name="p59891610163513"></a><a name="p59891610163513"></a>th-Latn</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p472110525369"><a name="p472110525369"></a><a name="p472110525369"></a>Thai</p>
</td>
</tr>
<tr id="row145861136183217"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p16672102711345"><a name="p16672102711345"></a><a name="p16672102711345"></a>THA</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p99892106354"><a name="p99892106354"></a><a name="p99892106354"></a>th</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p5721152113617"><a name="p5721152113617"></a><a name="p5721152113617"></a>Thai</p>
</td>
</tr>
<tr id="row1858615369325"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p1672027103416"><a name="p1672027103416"></a><a name="p1672027103416"></a>TIR</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p1998991083514"><a name="p1998991083514"></a><a name="p1998991083514"></a>ti-Latn</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p187211952133612"><a name="p187211952133612"></a><a name="p187211952133612"></a>Tigrinya</p>
</td>
</tr>
<tr id="row1658603683217"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p867218277345"><a name="p867218277345"></a><a name="p867218277345"></a>TIR</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p499031018357"><a name="p499031018357"></a><a name="p499031018357"></a>ti</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p1472185216363"><a name="p1472185216363"></a><a name="p1472185216363"></a>Tigrinya</p>
</td>
</tr>
<tr id="row95871367329"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p167213270347"><a name="p167213270347"></a><a name="p167213270347"></a>TON</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p1899001012359"><a name="p1899001012359"></a><a name="p1899001012359"></a>to</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p8721195212363"><a name="p8721195212363"></a><a name="p8721195212363"></a>Tonga (Tonga Islands)</p>
</td>
</tr>
<tr id="row4587203693211"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p26731327113413"><a name="p26731327113413"></a><a name="p26731327113413"></a>TSN</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p7990121063515"><a name="p7990121063515"></a><a name="p7990121063515"></a>tn</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p7722205223612"><a name="p7722205223612"></a><a name="p7722205223612"></a>Tswana</p>
</td>
</tr>
<tr id="row458720361325"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p1673327173416"><a name="p1673327173416"></a><a name="p1673327173416"></a>TUK</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p3990910133518"><a name="p3990910133518"></a><a name="p3990910133518"></a>tk</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p12722752203610"><a name="p12722752203610"></a><a name="p12722752203610"></a>Turkmen</p>
</td>
</tr>
<tr id="row175871736143214"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p1367312719341"><a name="p1367312719341"></a><a name="p1367312719341"></a>TUR</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p1699081020359"><a name="p1699081020359"></a><a name="p1699081020359"></a>tr</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p16722145253620"><a name="p16722145253620"></a><a name="p16722145253620"></a>Turkish</p>
</td>
</tr>
<tr id="row12587236123212"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p7673192713420"><a name="p7673192713420"></a><a name="p7673192713420"></a>UIG</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p49907102354"><a name="p49907102354"></a><a name="p49907102354"></a>ug-Latn</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p13722165203615"><a name="p13722165203615"></a><a name="p13722165203615"></a>Uighur; Uyghur</p>
</td>
</tr>
<tr id="row758713365329"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p3673122716341"><a name="p3673122716341"></a><a name="p3673122716341"></a>UIG</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p1499061017354"><a name="p1499061017354"></a><a name="p1499061017354"></a>ug</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p11722752183614"><a name="p11722752183614"></a><a name="p11722752183614"></a>Uighur; Uyghur</p>
</td>
</tr>
<tr id="row18588193616328"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p126731427183410"><a name="p126731427183410"></a><a name="p126731427183410"></a>UKR</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p14990171063519"><a name="p14990171063519"></a><a name="p14990171063519"></a>uk-Latn</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p14722135217363"><a name="p14722135217363"></a><a name="p14722135217363"></a>Ukrainian</p>
</td>
</tr>
<tr id="row55881936103214"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p167332723417"><a name="p167332723417"></a><a name="p167332723417"></a>UKR</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p2099061013351"><a name="p2099061013351"></a><a name="p2099061013351"></a>uk</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p147221852193610"><a name="p147221852193610"></a><a name="p147221852193610"></a>Ukrainian</p>
</td>
</tr>
<tr id="row11588536163218"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p11673182723413"><a name="p11673182723413"></a><a name="p11673182723413"></a>URD</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p139909105358"><a name="p139909105358"></a><a name="p139909105358"></a>ur-Latn</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p14722752183611"><a name="p14722752183611"></a><a name="p14722752183611"></a>Urdu</p>
</td>
</tr>
<tr id="row17588036103215"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p13673152720349"><a name="p13673152720349"></a><a name="p13673152720349"></a>URD</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p2990710103519"><a name="p2990710103519"></a><a name="p2990710103519"></a>ur</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p137221352193613"><a name="p137221352193613"></a><a name="p137221352193613"></a>Urdu</p>
</td>
</tr>
<tr id="row558863610321"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p136731827113413"><a name="p136731827113413"></a><a name="p136731827113413"></a>UZB</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p89907101359"><a name="p89907101359"></a><a name="p89907101359"></a>uz-Latn</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p10722105283612"><a name="p10722105283612"></a><a name="p10722105283612"></a>Uzbek</p>
</td>
</tr>
<tr id="row205881236193217"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p1673202711348"><a name="p1673202711348"></a><a name="p1673202711348"></a>UZB</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p129908102353"><a name="p129908102353"></a><a name="p129908102353"></a>uz</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p1972205233614"><a name="p1972205233614"></a><a name="p1972205233614"></a>Uzbek</p>
</td>
</tr>
<tr id="row2058963617322"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p17673227203417"><a name="p17673227203417"></a><a name="p17673227203417"></a>VIE</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p11990181011355"><a name="p11990181011355"></a><a name="p11990181011355"></a>vi</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p6722175213613"><a name="p6722175213613"></a><a name="p6722175213613"></a>Vietnamese</p>
</td>
</tr>
<tr id="row1589836103216"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p1467352710340"><a name="p1467352710340"></a><a name="p1467352710340"></a>CYM</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p1799031053511"><a name="p1799031053511"></a><a name="p1799031053511"></a>cy</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p872225243618"><a name="p872225243618"></a><a name="p872225243618"></a>Welsh</p>
</td>
</tr>
<tr id="row155891736143212"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p86738270343"><a name="p86738270343"></a><a name="p86738270343"></a>WOL</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p159900105358"><a name="p159900105358"></a><a name="p159900105358"></a>wo</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p872225215365"><a name="p872225215365"></a><a name="p872225215365"></a>Wolof</p>
</td>
</tr>
<tr id="row2589133673210"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p4673427103415"><a name="p4673427103415"></a><a name="p4673427103415"></a>XHO</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p169901410103519"><a name="p169901410103519"></a><a name="p169901410103519"></a>xh</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p87228522368"><a name="p87228522368"></a><a name="p87228522368"></a>Xhosa</p>
</td>
</tr>
<tr id="row10589136203219"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p067314276346"><a name="p067314276346"></a><a name="p067314276346"></a>YOR</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p49905108358"><a name="p49905108358"></a><a name="p49905108358"></a>yo</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p167221952173616"><a name="p167221952173616"></a><a name="p167221952173616"></a>Yoruba</p>
</td>
</tr>
<tr id="row1058993616322"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.1 "><p id="p12673122717346"><a name="p12673122717346"></a><a name="p12673122717346"></a>ZUL</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.2 "><p id="p8990810173519"><a name="p8990810173519"></a><a name="p8990810173519"></a>zu</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.4.1.3 "><p id="p77221652113610"><a name="p77221652113610"></a><a name="p77221652113610"></a>Zulu</p>
</td>
</tr>
</tbody>
</table>

