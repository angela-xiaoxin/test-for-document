# HWSiteService<a name="EN-US_TOPIC_0000001099181268"></a>

-   [Overview](#sbaa09de1257c4c5393ccaae60267fead)
-   [Build Method](#s800396f52cb24b929c903dcde3ce4adb)
-   [Public Methods](#sb70adea8b6f941f58b61960877fb4d7d)
-   [GeocodeRequest](#saf1bb1ddcd9041eeb84f89e5e671d7c4)
-   [GeocodeResult](#s7090a9c881f14c48b30da5db6f324a49)
-   [NearbySearchRequest](#s30220a53b51e40cd8478c9d9f12a045a)
-   [NearbySearchResult](#sf6c7d4cedcec4b4b940b7752dab31ffa)
-   [QuerySuggestionRequest](#s324f281f10ab45e680aadd15c41b5ed0)
-   [QuerySuggestionResult](#s5852156104864e6fa179b296ce50da80)
-   [ReverseGeocodeRequest](#s96dc7d2f75954b16bc3d18aadb84ab95)
-   [ReverseGeocodeResult](#se01b3c4effc145eea8d138b862d579bd)
-   [SearchByIdRequest](#se56aef8cc8f84672a38beaeb38483422)
-   [SearchByIdResult](#s17d0b19b28ce4030848dc8970b41f896)
-   [SearchByTextRequest](#s8239feda84464c79a65d17ea4e91409b)
-   [SearchByTextResult](#sed67def73702462b8ae318a0f755b245)

## Overview<a name="sbaa09de1257c4c5393ccaae60267fead"></a>

Provides place search and geocoding APIs. 

## Build Method<a name="s800396f52cb24b929c903dcde3ce4adb"></a>

<a name="t56a19c0ec56a49f299838b4861980eaf"></a>
<table><thead align="left"><tr id="rb7e290bf3d4b4a79add9f4f34eec52a6"><th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.1"><p id="a33254e3cf9284a7aa65ef59eec545230"><a name="a33254e3cf9284a7aa65ef59eec545230"></a><a name="a33254e3cf9284a7aa65ef59eec545230"></a><strong id="a9c3527bee68c4c329ea4f942b9306fe0"><a name="a9c3527bee68c4c329ea4f942b9306fe0"></a><a name="a9c3527bee68c4c329ea4f942b9306fe0"></a>Build Method</strong></p>
</th>
<th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.2"><p id="a02acb0a301584a4c8c69e6acf690104c"><a name="a02acb0a301584a4c8c69e6acf690104c"></a><a name="a02acb0a301584a4c8c69e6acf690104c"></a><strong id="b266512231119"><a name="b266512231119"></a><a name="b266512231119"></a>Description</strong></p>
</th>
</tr>
</thead>
<tbody><tr id="r9f1c4fcbce384cd09678fe3f52b57483"><td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.1 "><p id="a681685241dab48898843b7765324ba2d"><a name="a681685241dab48898843b7765324ba2d"></a><a name="a681685241dab48898843b7765324ba2d"></a>HWMapJsSDK.HWSiteService()</p>
</td>
<td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.2 "><p id="a0eb66c0ba624484eacf515858af84e7f"><a name="a0eb66c0ba624484eacf515858af84e7f"></a><a name="a0eb66c0ba624484eacf515858af84e7f"></a>-</p>
</td>
</tr>
</tbody>
</table>

## Public Methods<a name="sb70adea8b6f941f58b61960877fb4d7d"></a>

<a name="t7004b4a8eee54f168ed00b0366a088ac"></a>
<table><thead align="left"><tr id="r75a441d45573492f85af0bc8cca6d5f0"><th class="cellrowborder" valign="top" width="27%" id="mcps1.1.5.1.1"><p id="a031fc0ed096740879f50ff8d2e392f79"><a name="a031fc0ed096740879f50ff8d2e392f79"></a><a name="a031fc0ed096740879f50ff8d2e392f79"></a><strong id="b10916102619115"><a name="b10916102619115"></a><a name="b10916102619115"></a>Method</strong></p>
</th>
<th class="cellrowborder" valign="top" width="14.67%" id="mcps1.1.5.1.2"><p id="af3230483f3b9499b9f85b1d8fb9545d7"><a name="af3230483f3b9499b9f85b1d8fb9545d7"></a><a name="af3230483f3b9499b9f85b1d8fb9545d7"></a><strong id="b84635291913"><a name="b84635291913"></a><a name="b84635291913"></a>Description</strong></p>
</th>
<th class="cellrowborder" valign="top" width="41.23%" id="mcps1.1.5.1.3"><p id="af2aba3e52d9643beae49cc0ff0673b73"><a name="af2aba3e52d9643beae49cc0ff0673b73"></a><a name="af2aba3e52d9643beae49cc0ff0673b73"></a><strong id="a3b6b52f341f1412e9160a7581c4fd298"><a name="a3b6b52f341f1412e9160a7581c4fd298"></a><a name="a3b6b52f341f1412e9160a7581c4fd298"></a>Type</strong></p>
</th>
<th class="cellrowborder" valign="top" width="17.1%" id="mcps1.1.5.1.4"><p id="a479dd72a3c174d2ba7a0a14609e36345"><a name="a479dd72a3c174d2ba7a0a14609e36345"></a><a name="a479dd72a3c174d2ba7a0a14609e36345"></a><strong id="a0e6b089ce83b4a8390cd0855ccafb6dd"><a name="a0e6b089ce83b4a8390cd0855ccafb6dd"></a><a name="a0e6b089ce83b4a8390cd0855ccafb6dd"></a>Return Value</strong></p>
</th>
</tr>
</thead>
<tbody><tr id="r3fab5cd59fc140b39dd75a6796605edb"><td class="cellrowborder" valign="top" width="27%" headers="mcps1.1.5.1.1 "><p id="ad545e990971c462db6aec5dfd8cfc3cb"><a name="ad545e990971c462db6aec5dfd8cfc3cb"></a><a name="ad545e990971c462db6aec5dfd8cfc3cb"></a>geocode(request, callback)</p>
</td>
<td class="cellrowborder" valign="top" width="14.67%" headers="mcps1.1.5.1.2 "><p id="a7967564cfe3c426fa9935b655fd41bcc"><a name="a7967564cfe3c426fa9935b655fd41bcc"></a><a name="a7967564cfe3c426fa9935b655fd41bcc"></a>Performs forward geocoding.</p>
</td>
<td class="cellrowborder" valign="top" width="41.23%" headers="mcps1.1.5.1.3 "><a name="u855305fb8551413187b06c464e289f6c"></a><a name="u855305fb8551413187b06c464e289f6c"></a><ul id="u855305fb8551413187b06c464e289f6c"><li><strong id="b1458159619"><a name="b1458159619"></a><a name="b1458159619"></a>request</strong>: <a href="#saf1bb1ddcd9041eeb84f89e5e671d7c4">GeocodeRequest</a>, which is the body of the forward geocoding request.</li><li><strong id="b19984434727"><a name="b19984434727"></a><a name="b19984434727"></a>callback</strong>: <strong id="b87873564216"><a name="b87873564216"></a><a name="b87873564216"></a>Function(<a href="#s7090a9c881f14c48b30da5db6f324a49">GeocodeResult</a>, StatusCode)</strong>, which is the callback function for forward geocoding.</li></ul>
</td>
<td class="cellrowborder" valign="top" width="17.1%" headers="mcps1.1.5.1.4 "><p id="a4a168ad800af4019a7ade3798d074b85"><a name="a4a168ad800af4019a7ade3798d074b85"></a><a name="a4a168ad800af4019a7ade3798d074b85"></a>-</p>
</td>
</tr>
<tr id="r81ecf46d546246079b7e072ba9a084a7"><td class="cellrowborder" valign="top" width="27%" headers="mcps1.1.5.1.1 "><p id="a0c3fc36ebb034cfd82fc968f2e0c0c28"><a name="a0c3fc36ebb034cfd82fc968f2e0c0c28"></a><a name="a0c3fc36ebb034cfd82fc968f2e0c0c28"></a>nearbySearch(request, callback)</p>
</td>
<td class="cellrowborder" valign="top" width="14.67%" headers="mcps1.1.5.1.2 "><p id="a951988dbefd04901b58712482a7e0a72"><a name="a951988dbefd04901b58712482a7e0a72"></a><a name="a951988dbefd04901b58712482a7e0a72"></a>Searches for nearby places.</p>
</td>
<td class="cellrowborder" valign="top" width="41.23%" headers="mcps1.1.5.1.3 "><a name="u096e631b3abd4994a33c2f2ba42e28dc"></a><a name="u096e631b3abd4994a33c2f2ba42e28dc"></a><ul id="u096e631b3abd4994a33c2f2ba42e28dc"><li><strong id="b6949813343"><a name="b6949813343"></a><a name="b6949813343"></a>request</strong>: <a href="#s30220a53b51e40cd8478c9d9f12a045a">NearbySearchRequest</a>, which is the body of the nearby place search request.</li><li><strong id="b1393212372045"><a name="b1393212372045"></a><a name="b1393212372045"></a>callback</strong>: <strong id="b10277194915420"><a name="b10277194915420"></a><a name="b10277194915420"></a>Function(<a href="#sf6c7d4cedcec4b4b940b7752dab31ffa">NearbySearchResult</a>, StatusCode)</strong>, which is the callback function for nearby place search.</li></ul>
</td>
<td class="cellrowborder" valign="top" width="17.1%" headers="mcps1.1.5.1.4 "><p id="ac7a03ef2350f48f6904c4dcad6335f54"><a name="ac7a03ef2350f48f6904c4dcad6335f54"></a><a name="ac7a03ef2350f48f6904c4dcad6335f54"></a>-</p>
</td>
</tr>
<tr id="r60d26a1f782d4307897593b41836d063"><td class="cellrowborder" valign="top" width="27%" headers="mcps1.1.5.1.1 "><p id="a16184059a15c49b892c81cd94468bfed"><a name="a16184059a15c49b892c81cd94468bfed"></a><a name="a16184059a15c49b892c81cd94468bfed"></a>querySuggestion(request, callback)</p>
</td>
<td class="cellrowborder" valign="top" width="14.67%" headers="mcps1.1.5.1.2 "><p id="a9150496ce4184ffa8bee95662a90a0d0"><a name="a9150496ce4184ffa8bee95662a90a0d0"></a><a name="a9150496ce4184ffa8bee95662a90a0d0"></a>Suggests searched places. </p>
</td>
<td class="cellrowborder" valign="top" width="41.23%" headers="mcps1.1.5.1.3 "><a name="u64111f5d5c964a9382275e701d0fb90a"></a><a name="u64111f5d5c964a9382275e701d0fb90a"></a><ul id="u64111f5d5c964a9382275e701d0fb90a"><li><strong id="b175913221251"><a name="b175913221251"></a><a name="b175913221251"></a>request</strong>: <a href="#s324f281f10ab45e680aadd15c41b5ed0">QuerySuggestionRequest</a>, which is the body of the place search suggestion request.</li><li><strong id="b15241452758"><a name="b15241452758"></a><a name="b15241452758"></a>callback</strong>: <strong id="b202801632619"><a name="b202801632619"></a><a name="b202801632619"></a>Function(<a href="#s5852156104864e6fa179b296ce50da80">QuerySuggestionResult</a>, StatusCode)</strong>, which is the callback function for place search suggestion.</li></ul>
</td>
<td class="cellrowborder" valign="top" width="17.1%" headers="mcps1.1.5.1.4 "><p id="aba726d4d0036436993064d88d71db7de"><a name="aba726d4d0036436993064d88d71db7de"></a><a name="aba726d4d0036436993064d88d71db7de"></a>-</p>
</td>
</tr>
<tr id="rca84cef8a51448ed98217682291b7a31"><td class="cellrowborder" valign="top" width="27%" headers="mcps1.1.5.1.1 "><p id="a99959413fe614bc8b1fefc5876c40182"><a name="a99959413fe614bc8b1fefc5876c40182"></a><a name="a99959413fe614bc8b1fefc5876c40182"></a>reverseGeocode(request, callback)</p>
</td>
<td class="cellrowborder" valign="top" width="14.67%" headers="mcps1.1.5.1.2 "><p id="ac9bb7204a9244c70a66a871b7757eeee"><a name="ac9bb7204a9244c70a66a871b7757eeee"></a><a name="ac9bb7204a9244c70a66a871b7757eeee"></a>Performs reverse geocoding.</p>
</td>
<td class="cellrowborder" valign="top" width="41.23%" headers="mcps1.1.5.1.3 "><a name="u703c19e5019943c88faab762b379b446"></a><a name="u703c19e5019943c88faab762b379b446"></a><ul id="u703c19e5019943c88faab762b379b446"><li><strong id="b1989333111619"><a name="b1989333111619"></a><a name="b1989333111619"></a>request</strong>: <a href="#s96dc7d2f75954b16bc3d18aadb84ab95">ReverseGeocodeRequest</a>, which is the body of the reverse geocoding request.</li><li><strong id="b1883084414611"><a name="b1883084414611"></a><a name="b1883084414611"></a>callback</strong>: <strong id="b158361441068"><a name="b158361441068"></a><a name="b158361441068"></a>Function(<a href="#se01b3c4effc145eea8d138b862d579bd">ReverseGeocodeResult</a>, StatusCode)</strong>, which is the callback function for reverse geocoding.</li></ul>
</td>
<td class="cellrowborder" valign="top" width="17.1%" headers="mcps1.1.5.1.4 "><p id="ababcb783b1724f1d8e1e84448f77efdc"><a name="ababcb783b1724f1d8e1e84448f77efdc"></a><a name="ababcb783b1724f1d8e1e84448f77efdc"></a>-</p>
</td>
</tr>
<tr id="r025cb93bc85b4b10bdd6f9f8fcd70e44"><td class="cellrowborder" valign="top" width="27%" headers="mcps1.1.5.1.1 "><p id="a601050b4c3b9479b9870cea861c88ef3"><a name="a601050b4c3b9479b9870cea861c88ef3"></a><a name="a601050b4c3b9479b9870cea861c88ef3"></a>searchById(request, callback)</p>
</td>
<td class="cellrowborder" valign="top" width="14.67%" headers="mcps1.1.5.1.2 "><p id="a3dd066a1c3ba4efe84517197dea1828a"><a name="a3dd066a1c3ba4efe84517197dea1828a"></a><a name="a3dd066a1c3ba4efe84517197dea1828a"></a>Searches for place details.</p>
</td>
<td class="cellrowborder" valign="top" width="41.23%" headers="mcps1.1.5.1.3 "><a name="ua21241db6389429d99beb0ffc83e8ba8"></a><a name="ua21241db6389429d99beb0ffc83e8ba8"></a><ul id="ua21241db6389429d99beb0ffc83e8ba8"><li><strong id="b424814271291"><a name="b424814271291"></a><a name="b424814271291"></a>request</strong>: <a href="#se56aef8cc8f84672a38beaeb38483422">SearchByIdRequest</a>, which is the body of the place details search request.</li><li><strong id="b1374814581799"><a name="b1374814581799"></a><a name="b1374814581799"></a>callback</strong>: <strong id="b1235115961013"><a name="b1235115961013"></a><a name="b1235115961013"></a>Function(<a href="#s17d0b19b28ce4030848dc8970b41f896">SearchByIdResult</a>, StatusCode)</strong>, which is the callback function for place details search.</li></ul>
</td>
<td class="cellrowborder" valign="top" width="17.1%" headers="mcps1.1.5.1.4 "><p id="aeb78494e26db4b359a735812b5557f93"><a name="aeb78494e26db4b359a735812b5557f93"></a><a name="aeb78494e26db4b359a735812b5557f93"></a>-</p>
</td>
</tr>
<tr id="r55fc04b90d0e418b8d31736357214470"><td class="cellrowborder" valign="top" width="27%" headers="mcps1.1.5.1.1 "><p id="ad3832924c7d74d43a464dfdb6ca626d2"><a name="ad3832924c7d74d43a464dfdb6ca626d2"></a><a name="ad3832924c7d74d43a464dfdb6ca626d2"></a>searchByText(request, callback)</p>
</td>
<td class="cellrowborder" valign="top" width="14.67%" headers="mcps1.1.5.1.2 "><p id="a5f87fea1e65145bfb4b9c619321669ac"><a name="a5f87fea1e65145bfb4b9c619321669ac"></a><a name="a5f87fea1e65145bfb4b9c619321669ac"></a>Searches for places by keyword.</p>
</td>
<td class="cellrowborder" valign="top" width="41.23%" headers="mcps1.1.5.1.3 "><a name="ubc5f9968fc6147b8ba7d1c81e4c048f1"></a><a name="ubc5f9968fc6147b8ba7d1c81e4c048f1"></a><ul id="ubc5f9968fc6147b8ba7d1c81e4c048f1"><li><strong id="b177925456119"><a name="b177925456119"></a><a name="b177925456119"></a>request</strong>: <a href="#s8239feda84464c79a65d17ea4e91409b">SearchByTextRequest</a>, which is the body of the keyword search request.</li><li><strong id="b19384621121215"><a name="b19384621121215"></a><a name="b19384621121215"></a>callback</strong>: <strong id="b141249325123"><a name="b141249325123"></a><a name="b141249325123"></a>Function(<a href="#sed67def73702462b8ae318a0f755b245">SearchByTextResult</a>, StatusCode)</strong>, which is the callback function for keyword search.</li></ul>
</td>
<td class="cellrowborder" valign="top" width="17.1%" headers="mcps1.1.5.1.4 "><p id="a4a941465e7fc4023807d95dd0955b122"><a name="a4a941465e7fc4023807d95dd0955b122"></a><a name="a4a941465e7fc4023807d95dd0955b122"></a>-</p>
</td>
</tr>
</tbody>
</table>

>![](public_sys-resources/icon-note.gif) **NOTE:** 
>In the methods,  **StatusCode**  indicates the result code returned for API call. For details, please refer to  [Result Codes](error-code.md).

## GeocodeRequest<a name="saf1bb1ddcd9041eeb84f89e5e671d7c4"></a>

<a name="t29319ecbd62148a496dd2bd118b7a7f5"></a>
<table><thead align="left"><tr id="rbfd51684711542c19eadc22411f00ff5"><th class="cellrowborder" valign="top" width="16.97%" id="mcps1.1.5.1.1"><p id="af2c383548da2425aa60279a3554738ae"><a name="af2c383548da2425aa60279a3554738ae"></a><a name="af2c383548da2425aa60279a3554738ae"></a>Parameter</p>
</th>
<th class="cellrowborder" valign="top" width="14.000000000000002%" id="mcps1.1.5.1.2"><p id="a25591bcb02764dfab3cae49e232183dd"><a name="a25591bcb02764dfab3cae49e232183dd"></a><a name="a25591bcb02764dfab3cae49e232183dd"></a>Mandatory/Optional</p>
</th>
<th class="cellrowborder" valign="top" width="16%" id="mcps1.1.5.1.3"><p id="a80c80fc8e3e04885b0b9e752bb98866d"><a name="a80c80fc8e3e04885b0b9e752bb98866d"></a><a name="a80c80fc8e3e04885b0b9e752bb98866d"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53.03%" id="mcps1.1.5.1.4"><p id="a3fd18e794429462087d1b12337e3cf98"><a name="a3fd18e794429462087d1b12337e3cf98"></a><a name="a3fd18e794429462087d1b12337e3cf98"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="reb067db0d79745119876ee09c3c6e854"><td class="cellrowborder" valign="top" width="16.97%" headers="mcps1.1.5.1.1 "><p id="aad377cd3352f4c4397e31f35bc94cec8"><a name="aad377cd3352f4c4397e31f35bc94cec8"></a><a name="aad377cd3352f4c4397e31f35bc94cec8"></a>address</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="ab5c3103d15834426890a19c3017756e7"><a name="ab5c3103d15834426890a19c3017756e7"></a><a name="ab5c3103d15834426890a19c3017756e7"></a>Mandatory</p>
</td>
<td class="cellrowborder" valign="top" width="16%" headers="mcps1.1.5.1.3 "><p id="a701bd929e7f04449a29aefcad82978a2"><a name="a701bd929e7f04449a29aefcad82978a2"></a><a name="a701bd929e7f04449a29aefcad82978a2"></a>String(&lt;=512)</p>
</td>
<td class="cellrowborder" valign="top" width="53.03%" headers="mcps1.1.5.1.4 "><p id="a9c6dff2413c345998b80878830b6d370"><a name="a9c6dff2413c345998b80878830b6d370"></a><a name="a9c6dff2413c345998b80878830b6d370"></a>Place information.</p>
</td>
</tr>
<tr id="rb2977ab1760c407d80f188347f90f620"><td class="cellrowborder" valign="top" width="16.97%" headers="mcps1.1.5.1.1 "><p id="aaad1272cea3b49f19924ab9f5a533fc0"><a name="aaad1272cea3b49f19924ab9f5a533fc0"></a><a name="aaad1272cea3b49f19924ab9f5a533fc0"></a>bounds</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="ab4a04055a2f64158b226bbeda2babd86"><a name="ab4a04055a2f64158b226bbeda2babd86"></a><a name="ab4a04055a2f64158b226bbeda2babd86"></a>Optional</p>
</td>
<td class="cellrowborder" valign="top" width="16%" headers="mcps1.1.5.1.3 "><p id="a11e15ce3edc045f0aa3348e8f95657d1"><a name="a11e15ce3edc045f0aa3348e8f95657d1"></a><a name="a11e15ce3edc045f0aa3348e8f95657d1"></a><a href="js-params.md#sb6bca9c1a2f142d287414bceeabe54a9">LatLngBounds</a></p>
</td>
<td class="cellrowborder" valign="top" width="53.03%" headers="mcps1.1.5.1.4 "><p id="abbe2ae38cee1427aa9778df11d84891d"><a name="abbe2ae38cee1427aa9778df11d84891d"></a><a name="abbe2ae38cee1427aa9778df11d84891d"></a>Coordinate bounds to which search results need to be biased.</p>
</td>
</tr>
<tr id="rd3c64184d3854c559fe7706ac92ffcd2"><td class="cellrowborder" valign="top" width="16.97%" headers="mcps1.1.5.1.1 "><p id="a8e8634935d0843b880e4214d7cb44db2"><a name="a8e8634935d0843b880e4214d7cb44db2"></a><a name="a8e8634935d0843b880e4214d7cb44db2"></a>language</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="a08d2b7d46e1447239e798a6a36bf1fec"><a name="a08d2b7d46e1447239e798a6a36bf1fec"></a><a name="a08d2b7d46e1447239e798a6a36bf1fec"></a>Optional</p>
</td>
<td class="cellrowborder" valign="top" width="16%" headers="mcps1.1.5.1.3 "><p id="acbac5710b2e14956a7e4e6d710ccf5b8"><a name="acbac5710b2e14956a7e4e6d710ccf5b8"></a><a name="acbac5710b2e14956a7e4e6d710ccf5b8"></a>String(&lt;=6)</p>
</td>
<td class="cellrowborder" valign="top" width="53.03%" headers="mcps1.1.5.1.4 "><p id="p6702102920561"><a name="p6702102920561"></a><a name="p6702102920561"></a>Language in which search results are displayed. For details, please refer to <a href="en-us_topic_0000001050162856.md">Supported Languages</a>. If this parameter is not passed, the local language of the place will be used.</p>
</td>
</tr>
<tr id="r3b17f4419c5847b99d64532484c924d0"><td class="cellrowborder" valign="top" width="16.97%" headers="mcps1.1.5.1.1 "><p id="a25ddda811c1b489a8082a7895504d292"><a name="a25ddda811c1b489a8082a7895504d292"></a><a name="a25ddda811c1b489a8082a7895504d292"></a>politicalView</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="a58adcda5dfc34bc5bd6335bf86cde51f"><a name="a58adcda5dfc34bc5bd6335bf86cde51f"></a><a name="a58adcda5dfc34bc5bd6335bf86cde51f"></a>Optional</p>
</td>
<td class="cellrowborder" valign="top" width="16%" headers="mcps1.1.5.1.3 "><p id="acaf1caba724d44d384aa8a623835db71"><a name="acaf1caba724d44d384aa8a623835db71"></a><a name="acaf1caba724d44d384aa8a623835db71"></a>String(=2)</p>
</td>
<td class="cellrowborder" valign="top" width="53.03%" headers="mcps1.1.5.1.4 "><p id="a2a5f6b16d31b447cb96b8134b0a4be69"><a name="a2a5f6b16d31b447cb96b8134b0a4be69"></a><a name="a2a5f6b16d31b447cb96b8134b0a4be69"></a>Political view. The value is a two-letter country or region code complying with ISO 3166-1 alpha-2. </p>
<div class="caution" id="note1528292117492"><a name="note1528292117492"></a><a name="note1528292117492"></a><span class="cautiontitle"> CAUTION: </span><div class="cautionbody"><p id="p52829212494"><a name="p52829212494"></a><a name="p52829212494"></a>This parameter has been deprecated.</p>
</div></div>
</td>
</tr>
</tbody>
</table>

## GeocodeResult<a name="s7090a9c881f14c48b30da5db6f324a49"></a>

<a name="t765f06b6e90c4b389f6619fb881a7d2d"></a>
<table><thead align="left"><tr id="r20949078cded4d4986acd49f304d3fe1"><th class="cellrowborder" valign="top" width="20%" id="mcps1.1.4.1.1"><p id="a7edc60880c6e4a1baca7e91bed059376"><a name="a7edc60880c6e4a1baca7e91bed059376"></a><a name="a7edc60880c6e4a1baca7e91bed059376"></a>Parameter</p>
</th>
<th class="cellrowborder" valign="top" width="20%" id="mcps1.1.4.1.2"><p id="a55b9eb81f3a44edab89ceff94f94edd1"><a name="a55b9eb81f3a44edab89ceff94f94edd1"></a><a name="a55b9eb81f3a44edab89ceff94f94edd1"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.1.4.1.3"><p id="a17c268da30ae42498a39a0e05f8ebe84"><a name="a17c268da30ae42498a39a0e05f8ebe84"></a><a name="a17c268da30ae42498a39a0e05f8ebe84"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="r72607785b648418b9b30e2545ba40952"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.1.4.1.1 "><p id="a010b84a23dda4bce87992d341dfa97f4"><a name="a010b84a23dda4bce87992d341dfa97f4"></a><a name="a010b84a23dda4bce87992d341dfa97f4"></a>sites</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.1.4.1.2 "><p id="a40ba34b791a447aa843a2fe137c7e327"><a name="a40ba34b791a447aa843a2fe137c7e327"></a><a name="a40ba34b791a447aa843a2fe137c7e327"></a>Array&lt;<a href="js-params.md#s39aa5bdd04dc4c36a885114f35ed8b00">Site</a>&gt;</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.4.1.3 "><p id="a5b20e7c95cd54081ba8932b84e69565c"><a name="a5b20e7c95cd54081ba8932b84e69565c"></a><a name="a5b20e7c95cd54081ba8932b84e69565c"></a>Search result returned upon a successful search. If no results are available, an empty array will be returned.</p>
<div class="caution" id="note9272141116547"><a name="note9272141116547"></a><a name="note9272141116547"></a><span class="cautiontitle"> CAUTION: </span><div class="cautionbody"><p id="p152722011155413"><a name="p152722011155413"></a><a name="p152722011155413"></a>The <strong id="b121401112144417"><a name="b121401112144417"></a><a name="b121401112144417"></a>Site</strong> array does not contain the POI information. </p>
</div></div>
</td>
</tr>
</tbody>
</table>

## NearbySearchRequest<a name="s30220a53b51e40cd8478c9d9f12a045a"></a>

<a name="tc6e242e75fd84fce8a24fd0197db7522"></a>
<table><thead align="left"><tr id="r1d48a617ccc6464c86a90da82fc7bc1e"><th class="cellrowborder" valign="top" width="17.401740174017398%" id="mcps1.1.5.1.1"><p id="ab97cee60ad4941038a538f81b86f7c44"><a name="ab97cee60ad4941038a538f81b86f7c44"></a><a name="ab97cee60ad4941038a538f81b86f7c44"></a>Parameter</p>
</th>
<th class="cellrowborder" valign="top" width="14.001400140014002%" id="mcps1.1.5.1.2"><p id="ac6532ce3045a445089c96c2eda52d421"><a name="ac6532ce3045a445089c96c2eda52d421"></a><a name="ac6532ce3045a445089c96c2eda52d421"></a>Mandatory/Optional</p>
</th>
<th class="cellrowborder" valign="top" width="16.38163816381638%" id="mcps1.1.5.1.3"><p id="a43b2519422be4d309ed8cc2b8b713921"><a name="a43b2519422be4d309ed8cc2b8b713921"></a><a name="a43b2519422be4d309ed8cc2b8b713921"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="52.21522152215221%" id="mcps1.1.5.1.4"><p id="a20a0f5bef520465687c8b40b7fd5a132"><a name="a20a0f5bef520465687c8b40b7fd5a132"></a><a name="a20a0f5bef520465687c8b40b7fd5a132"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="r32f6b8e6171f40ee8b330fcb8bc6ea01"><td class="cellrowborder" valign="top" width="17.401740174017398%" headers="mcps1.1.5.1.1 "><p id="a2606b8ca717c46c1b01a0e296416b17d"><a name="a2606b8ca717c46c1b01a0e296416b17d"></a><a name="a2606b8ca717c46c1b01a0e296416b17d"></a>location</p>
</td>
<td class="cellrowborder" valign="top" width="14.001400140014002%" headers="mcps1.1.5.1.2 "><p id="ac7422671f8a74dec8b3d40c422e28fb5"><a name="ac7422671f8a74dec8b3d40c422e28fb5"></a><a name="ac7422671f8a74dec8b3d40c422e28fb5"></a>Mandatory</p>
</td>
<td class="cellrowborder" valign="top" width="16.38163816381638%" headers="mcps1.1.5.1.3 "><p id="a996e5aa594dd4feb989d460d105796c3"><a name="a996e5aa594dd4feb989d460d105796c3"></a><a name="a996e5aa594dd4feb989d460d105796c3"></a><a href="js-params.md#s1f33822192a04bbe9bd9de86a17460b1">LatLng</a></p>
</td>
<td class="cellrowborder" valign="top" width="52.21522152215221%" headers="mcps1.1.5.1.4 "><p id="a1f6af6ffbb1741b1a910129c213c2084"><a name="a1f6af6ffbb1741b1a910129c213c2084"></a><a name="a1f6af6ffbb1741b1a910129c213c2084"></a>Current location of a user.</p>
</td>
</tr>
<tr id="r8d719be351174be9b887729f55acd1c3"><td class="cellrowborder" valign="top" width="17.401740174017398%" headers="mcps1.1.5.1.1 "><p id="a7876efd8f5a640e1b4a2f48e64360620"><a name="a7876efd8f5a640e1b4a2f48e64360620"></a><a name="a7876efd8f5a640e1b4a2f48e64360620"></a>radius</p>
</td>
<td class="cellrowborder" valign="top" width="14.001400140014002%" headers="mcps1.1.5.1.2 "><p id="a8cebf9bbe9a94ed38834dbc6ff8181eb"><a name="a8cebf9bbe9a94ed38834dbc6ff8181eb"></a><a name="a8cebf9bbe9a94ed38834dbc6ff8181eb"></a>Optional</p>
</td>
<td class="cellrowborder" valign="top" width="16.38163816381638%" headers="mcps1.1.5.1.3 "><p id="afe1ddc345eb64ebba99330f360c38c3e"><a name="afe1ddc345eb64ebba99330f360c38c3e"></a><a name="afe1ddc345eb64ebba99330f360c38c3e"></a>Number</p>
</td>
<td class="cellrowborder" valign="top" width="52.21522152215221%" headers="mcps1.1.5.1.4 "><p id="a4ff01e5abb904ef3bde2055438be3211"><a name="a4ff01e5abb904ef3bde2055438be3211"></a><a name="a4ff01e5abb904ef3bde2055438be3211"></a>Search radius, in meters. The default value is <strong id="b15087430164"><a name="b15087430164"></a><a name="b15087430164"></a>1000</strong>.</p>
<p id="acf0b25ac8d034b5582502b487227dfca"><a name="acf0b25ac8d034b5582502b487227dfca"></a><a name="acf0b25ac8d034b5582502b487227dfca"></a>The value ranges from 1 to 50000.</p>
</td>
</tr>
<tr id="r84184a6fedbe4f6bb23eeca39d88837e"><td class="cellrowborder" valign="top" width="17.401740174017398%" headers="mcps1.1.5.1.1 "><p id="a65760b77c4d04a03a881506685ad5b1e"><a name="a65760b77c4d04a03a881506685ad5b1e"></a><a name="a65760b77c4d04a03a881506685ad5b1e"></a>query</p>
</td>
<td class="cellrowborder" valign="top" width="14.001400140014002%" headers="mcps1.1.5.1.2 "><p id="aef4c8f45863842f9922785d6bf14ddd6"><a name="aef4c8f45863842f9922785d6bf14ddd6"></a><a name="aef4c8f45863842f9922785d6bf14ddd6"></a>Optional</p>
</td>
<td class="cellrowborder" valign="top" width="16.38163816381638%" headers="mcps1.1.5.1.3 "><p id="afbaf8f03b5d84df996ab5a2d283a7b29"><a name="afbaf8f03b5d84df996ab5a2d283a7b29"></a><a name="afbaf8f03b5d84df996ab5a2d283a7b29"></a>String(&lt;=512)</p>
</td>
<td class="cellrowborder" valign="top" width="52.21522152215221%" headers="mcps1.1.5.1.4 "><p id="ae55f03eb17dc4eb79112ba7f7762cf31"><a name="ae55f03eb17dc4eb79112ba7f7762cf31"></a><a name="ae55f03eb17dc4eb79112ba7f7762cf31"></a>Search keyword.</p>
</td>
</tr>
<tr id="rf839da1ba2f1439e97064072351a63af"><td class="cellrowborder" valign="top" width="17.401740174017398%" headers="mcps1.1.5.1.1 "><p id="a61da986c69e94b15a27af4d937922c4a"><a name="a61da986c69e94b15a27af4d937922c4a"></a><a name="a61da986c69e94b15a27af4d937922c4a"></a>poiType</p>
</td>
<td class="cellrowborder" valign="top" width="14.001400140014002%" headers="mcps1.1.5.1.2 "><p id="ab2ff02075c7441f0913688f809f21303"><a name="ab2ff02075c7441f0913688f809f21303"></a><a name="ab2ff02075c7441f0913688f809f21303"></a>Optional</p>
</td>
<td class="cellrowborder" valign="top" width="16.38163816381638%" headers="mcps1.1.5.1.3 "><p id="ad030932d2f3142ffa4f8bfb8b966bcdf"><a name="ad030932d2f3142ffa4f8bfb8b966bcdf"></a><a name="ad030932d2f3142ffa4f8bfb8b966bcdf"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="52.21522152215221%" headers="mcps1.1.5.1.4 "><p id="ac5dedde8d2b64bf289ef6a843717dc38"><a name="ac5dedde8d2b64bf289ef6a843717dc38"></a><a name="ac5dedde8d2b64bf289ef6a843717dc38"></a>POI type of the returned place.</p>
</td>
</tr>
<tr id="r0a30c28a1fcd4d1f98c5acda42034a84"><td class="cellrowborder" valign="top" width="17.401740174017398%" headers="mcps1.1.5.1.1 "><p id="ac027481a2a7a495997209c9f93c813d0"><a name="ac027481a2a7a495997209c9f93c813d0"></a><a name="ac027481a2a7a495997209c9f93c813d0"></a>language</p>
</td>
<td class="cellrowborder" valign="top" width="14.001400140014002%" headers="mcps1.1.5.1.2 "><p id="a56506dcdb699427494f9576a9c3ce389"><a name="a56506dcdb699427494f9576a9c3ce389"></a><a name="a56506dcdb699427494f9576a9c3ce389"></a>Optional</p>
</td>
<td class="cellrowborder" valign="top" width="16.38163816381638%" headers="mcps1.1.5.1.3 "><p id="a7174e782a29f4c868b231b0a0ecb1135"><a name="a7174e782a29f4c868b231b0a0ecb1135"></a><a name="a7174e782a29f4c868b231b0a0ecb1135"></a>String(&lt;=6)</p>
</td>
<td class="cellrowborder" valign="top" width="52.21522152215221%" headers="mcps1.1.5.1.4 "><p id="a931cfc632efa43e5882c4cc340665394"><a name="a931cfc632efa43e5882c4cc340665394"></a><a name="a931cfc632efa43e5882c4cc340665394"></a>Language in which search results are displayed. For details, please refer to <a href="en-us_topic_0000001050162856.md">Supported Languages</a>. If this parameter is not passed, the local language of the place will be used.</p>
</td>
</tr>
<tr id="r5fa77ad10d33456d9799592ca85b9b2a"><td class="cellrowborder" valign="top" width="17.401740174017398%" headers="mcps1.1.5.1.1 "><p id="ae57669e3a3c141ebb7e5fbc9c6873391"><a name="ae57669e3a3c141ebb7e5fbc9c6873391"></a><a name="ae57669e3a3c141ebb7e5fbc9c6873391"></a>pageSize</p>
</td>
<td class="cellrowborder" valign="top" width="14.001400140014002%" headers="mcps1.1.5.1.2 "><p id="addff7f8dafa24259b29bef89e39d1478"><a name="addff7f8dafa24259b29bef89e39d1478"></a><a name="addff7f8dafa24259b29bef89e39d1478"></a>Optional</p>
</td>
<td class="cellrowborder" valign="top" width="16.38163816381638%" headers="mcps1.1.5.1.3 "><p id="ab9ee335ca15d4e769ed2af813cbeff06"><a name="ab9ee335ca15d4e769ed2af813cbeff06"></a><a name="ab9ee335ca15d4e769ed2af813cbeff06"></a>Number</p>
</td>
<td class="cellrowborder" valign="top" width="52.21522152215221%" headers="mcps1.1.5.1.4 "><p id="a669ddc09e8c54f02aa630062fb0ce9de"><a name="a669ddc09e8c54f02aa630062fb0ce9de"></a><a name="a669ddc09e8c54f02aa630062fb0ce9de"></a>Number of records on each page. The default value is <strong id="b166191635141813"><a name="b166191635141813"></a><a name="b166191635141813"></a>20</strong>.</p>
<p id="adc86c035f45f4d36a14154121a1e0be5"><a name="adc86c035f45f4d36a14154121a1e0be5"></a><a name="adc86c035f45f4d36a14154121a1e0be5"></a>The value ranges from 1 to 20.</p>
</td>
</tr>
<tr id="ra8ef386e9ab54afe9cfbbca03201dbea"><td class="cellrowborder" valign="top" width="17.401740174017398%" headers="mcps1.1.5.1.1 "><p id="a59ddf78f01724c74b939bbe632a2aadb"><a name="a59ddf78f01724c74b939bbe632a2aadb"></a><a name="a59ddf78f01724c74b939bbe632a2aadb"></a>pageIndex</p>
</td>
<td class="cellrowborder" valign="top" width="14.001400140014002%" headers="mcps1.1.5.1.2 "><p id="acccaed4abc344e4182257671abfbc7f0"><a name="acccaed4abc344e4182257671abfbc7f0"></a><a name="acccaed4abc344e4182257671abfbc7f0"></a>Optional</p>
</td>
<td class="cellrowborder" valign="top" width="16.38163816381638%" headers="mcps1.1.5.1.3 "><p id="af26965e3aa5744758aab559b0d895b6c"><a name="af26965e3aa5744758aab559b0d895b6c"></a><a name="af26965e3aa5744758aab559b0d895b6c"></a>Number</p>
</td>
<td class="cellrowborder" valign="top" width="52.21522152215221%" headers="mcps1.1.5.1.4 "><p id="abb5e5c748b694db1ae8861c8264e6b27"><a name="abb5e5c748b694db1ae8861c8264e6b27"></a><a name="abb5e5c748b694db1ae8861c8264e6b27"></a>Current page number. The default value is <strong id="b42691642171818"><a name="b42691642171818"></a><a name="b42691642171818"></a>1</strong>.</p>
<p id="a39ba59ce2e9244e7b02d49870aa1bba1"><a name="a39ba59ce2e9244e7b02d49870aa1bba1"></a><a name="a39ba59ce2e9244e7b02d49870aa1bba1"></a>The value ranges from 1 to 60.</p>
<p id="a2c80787cf3fb40d4bb600adf8941d0be"><a name="a2c80787cf3fb40d4bb600adf8941d0be"></a><a name="a2c80787cf3fb40d4bb600adf8941d0be"></a>The following formula must be met: <strong id="b79881953101813"><a name="b79881953101813"></a><a name="b79881953101813"></a>pageIndex</strong> x <strong id="b7993185318189"><a name="b7993185318189"></a><a name="b7993185318189"></a>pageSize</strong> ≤ 60. </p>
</td>
</tr>
<tr id="r0ff6c7224dcf49108c6831c952e06bde"><td class="cellrowborder" valign="top" width="17.401740174017398%" headers="mcps1.1.5.1.1 "><p id="a0d9d884b758a48db9d60de946664a88c"><a name="a0d9d884b758a48db9d60de946664a88c"></a><a name="a0d9d884b758a48db9d60de946664a88c"></a>politicalView</p>
</td>
<td class="cellrowborder" valign="top" width="14.001400140014002%" headers="mcps1.1.5.1.2 "><p id="a4dce4c83bf8a4a1ebb0bcf42b50aab86"><a name="a4dce4c83bf8a4a1ebb0bcf42b50aab86"></a><a name="a4dce4c83bf8a4a1ebb0bcf42b50aab86"></a>Optional</p>
</td>
<td class="cellrowborder" valign="top" width="16.38163816381638%" headers="mcps1.1.5.1.3 "><p id="ace8cae0ba1f241a699d8ccd46eca8c98"><a name="ace8cae0ba1f241a699d8ccd46eca8c98"></a><a name="ace8cae0ba1f241a699d8ccd46eca8c98"></a>String(=2)</p>
</td>
<td class="cellrowborder" valign="top" width="52.21522152215221%" headers="mcps1.1.5.1.4 "><p id="a44380f94703e4612a6b31729d45a270e"><a name="a44380f94703e4612a6b31729d45a270e"></a><a name="a44380f94703e4612a6b31729d45a270e"></a>Political view. The value is a two-letter country or region code complying with ISO 3166-1 alpha-2. </p>
<div class="caution" id="note105419228395"><a name="note105419228395"></a><a name="note105419228395"></a><span class="cautiontitle"> CAUTION: </span><div class="cautionbody"><p id="p3541422163916"><a name="p3541422163916"></a><a name="p3541422163916"></a>This parameter has been deprecated.</p>
</div></div>
</td>
</tr>
</tbody>
</table>

## NearbySearchResult<a name="sf6c7d4cedcec4b4b940b7752dab31ffa"></a>

<a name="t1cdef3b06a4942ec947b98e5ce58dd71"></a>
<table><thead align="left"><tr id="r99eeabf88da147d7a393401b09b691a2"><th class="cellrowborder" valign="top" width="18.18%" id="mcps1.1.4.1.1"><p id="a8108100889fc499085d8d54f3076a3d8"><a name="a8108100889fc499085d8d54f3076a3d8"></a><a name="a8108100889fc499085d8d54f3076a3d8"></a>Parameter</p>
</th>
<th class="cellrowborder" valign="top" width="18.18%" id="mcps1.1.4.1.2"><p id="afb064aaf5e824169a08ea33e0e8886ed"><a name="afb064aaf5e824169a08ea33e0e8886ed"></a><a name="afb064aaf5e824169a08ea33e0e8886ed"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="63.63999999999999%" id="mcps1.1.4.1.3"><p id="ae8d5965e24d943889a9358bca818bbd5"><a name="ae8d5965e24d943889a9358bca818bbd5"></a><a name="ae8d5965e24d943889a9358bca818bbd5"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="rc5a5e80db83a43508d1d47a41e601d83"><td class="cellrowborder" valign="top" width="18.18%" headers="mcps1.1.4.1.1 "><p id="ab3c06cbe05644e998503a34e61edb9f9"><a name="ab3c06cbe05644e998503a34e61edb9f9"></a><a name="ab3c06cbe05644e998503a34e61edb9f9"></a>totalCount</p>
</td>
<td class="cellrowborder" valign="top" width="18.18%" headers="mcps1.1.4.1.2 "><p id="aa16fc9953154455cb9caac60c229f05a"><a name="aa16fc9953154455cb9caac60c229f05a"></a><a name="aa16fc9953154455cb9caac60c229f05a"></a>Number</p>
</td>
<td class="cellrowborder" valign="top" width="63.63999999999999%" headers="mcps1.1.4.1.3 "><p id="a1793efc5bb344eb1b558d670f4451953"><a name="a1793efc5bb344eb1b558d670f4451953"></a><a name="a1793efc5bb344eb1b558d670f4451953"></a>Total number of records returned upon a successful search. If no records are found, <strong id="b41245320201"><a name="b41245320201"></a><a name="b41245320201"></a>0</strong> will be returned.</p>
</td>
</tr>
<tr id="r5fe7e94a3f2049b7b013d08afe31b5a7"><td class="cellrowborder" valign="top" width="18.18%" headers="mcps1.1.4.1.1 "><p id="af1819f6d71f34cc48dea98b02771d29e"><a name="af1819f6d71f34cc48dea98b02771d29e"></a><a name="af1819f6d71f34cc48dea98b02771d29e"></a>sites</p>
</td>
<td class="cellrowborder" valign="top" width="18.18%" headers="mcps1.1.4.1.2 "><p id="adfa34a5066334476a65aba989e6a0125"><a name="adfa34a5066334476a65aba989e6a0125"></a><a name="adfa34a5066334476a65aba989e6a0125"></a>Array&lt;<a href="js-params.md#s39aa5bdd04dc4c36a885114f35ed8b00">Site</a>&gt;</p>
</td>
<td class="cellrowborder" valign="top" width="63.63999999999999%" headers="mcps1.1.4.1.3 "><p id="aad7b94279cc344b09b920d50c081a502"><a name="aad7b94279cc344b09b920d50c081a502"></a><a name="aad7b94279cc344b09b920d50c081a502"></a>Search result returned upon a successful search. If no results are available, an empty array will be returned.</p>
</td>
</tr>
</tbody>
</table>

## QuerySuggestionRequest<a name="s324f281f10ab45e680aadd15c41b5ed0"></a>

<a name="t5ea26019aee8477680e520d4aef09223"></a>
<table><thead align="left"><tr id="r8cdc6146772a4a00a5d79235a50b79da"><th class="cellrowborder" valign="top" width="17.401740174017398%" id="mcps1.1.5.1.1"><p id="a438df0f2485b4c4f88e33e0c8a99739a"><a name="a438df0f2485b4c4f88e33e0c8a99739a"></a><a name="a438df0f2485b4c4f88e33e0c8a99739a"></a>Parameter</p>
</th>
<th class="cellrowborder" valign="top" width="14.001400140014002%" id="mcps1.1.5.1.2"><p id="a93e99bc8327849e283e1989b4ba5fe43"><a name="a93e99bc8327849e283e1989b4ba5fe43"></a><a name="a93e99bc8327849e283e1989b4ba5fe43"></a>Mandatory/Optional</p>
</th>
<th class="cellrowborder" valign="top" width="16.38163816381638%" id="mcps1.1.5.1.3"><p id="a0037d3d99dc84f2fbeed3fad1fe42316"><a name="a0037d3d99dc84f2fbeed3fad1fe42316"></a><a name="a0037d3d99dc84f2fbeed3fad1fe42316"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="52.21522152215221%" id="mcps1.1.5.1.4"><p id="a81907a21e20040e4b48b3fc8f30a69bf"><a name="a81907a21e20040e4b48b3fc8f30a69bf"></a><a name="a81907a21e20040e4b48b3fc8f30a69bf"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="r733fb65ae3ca40709293ab89396340c3"><td class="cellrowborder" valign="top" width="17.401740174017398%" headers="mcps1.1.5.1.1 "><p id="af347501db2f24af0983399f3a127e22e"><a name="af347501db2f24af0983399f3a127e22e"></a><a name="af347501db2f24af0983399f3a127e22e"></a>query</p>
</td>
<td class="cellrowborder" valign="top" width="14.001400140014002%" headers="mcps1.1.5.1.2 "><p id="aa5f059486ea346959438004cc6f56360"><a name="aa5f059486ea346959438004cc6f56360"></a><a name="aa5f059486ea346959438004cc6f56360"></a>Mandatory</p>
</td>
<td class="cellrowborder" valign="top" width="16.38163816381638%" headers="mcps1.1.5.1.3 "><p id="ad555bc7ced2f48f99264fac9297313b9"><a name="ad555bc7ced2f48f99264fac9297313b9"></a><a name="ad555bc7ced2f48f99264fac9297313b9"></a>String(&lt;=512)</p>
</td>
<td class="cellrowborder" valign="top" width="52.21522152215221%" headers="mcps1.1.5.1.4 "><p id="afe3034c978534ee68560714324002132"><a name="afe3034c978534ee68560714324002132"></a><a name="afe3034c978534ee68560714324002132"></a>Search keyword.</p>
</td>
</tr>
<tr id="r5ff8220674aa456b84908d899b21eecf"><td class="cellrowborder" valign="top" width="17.401740174017398%" headers="mcps1.1.5.1.1 "><p id="a6e9a35b27bee4a228b3091988e579c71"><a name="a6e9a35b27bee4a228b3091988e579c71"></a><a name="a6e9a35b27bee4a228b3091988e579c71"></a>location</p>
</td>
<td class="cellrowborder" valign="top" width="14.001400140014002%" headers="mcps1.1.5.1.2 "><p id="a97744f38321347329553511607147a04"><a name="a97744f38321347329553511607147a04"></a><a name="a97744f38321347329553511607147a04"></a>Optional</p>
</td>
<td class="cellrowborder" valign="top" width="16.38163816381638%" headers="mcps1.1.5.1.3 "><p id="ae0d9adc534b04268a9bbc12cba0c0d80"><a name="ae0d9adc534b04268a9bbc12cba0c0d80"></a><a name="ae0d9adc534b04268a9bbc12cba0c0d80"></a><a href="js-params.md#s1f33822192a04bbe9bd9de86a17460b1">LatLng</a></p>
</td>
<td class="cellrowborder" valign="top" width="52.21522152215221%" headers="mcps1.1.5.1.4 "><p id="ad1f6ea6d04e649fa9f4d337eee52a086"><a name="ad1f6ea6d04e649fa9f4d337eee52a086"></a><a name="ad1f6ea6d04e649fa9f4d337eee52a086"></a>Longitude and latitude to which search suggestions need to be biased.</p>
</td>
</tr>
<tr id="rf1778fd95dc3419b945a20a299520712"><td class="cellrowborder" valign="top" width="17.401740174017398%" headers="mcps1.1.5.1.1 "><p id="a77bb0992e8494e428ef9a2b5d666d610"><a name="a77bb0992e8494e428ef9a2b5d666d610"></a><a name="a77bb0992e8494e428ef9a2b5d666d610"></a>radius</p>
</td>
<td class="cellrowborder" valign="top" width="14.001400140014002%" headers="mcps1.1.5.1.2 "><p id="a02ea30cb50a24e1d95913826cda6d9b7"><a name="a02ea30cb50a24e1d95913826cda6d9b7"></a><a name="a02ea30cb50a24e1d95913826cda6d9b7"></a>Optional</p>
</td>
<td class="cellrowborder" valign="top" width="16.38163816381638%" headers="mcps1.1.5.1.3 "><p id="ac28778ad617f4c8fba9e091bf4fe5a7d"><a name="ac28778ad617f4c8fba9e091bf4fe5a7d"></a><a name="ac28778ad617f4c8fba9e091bf4fe5a7d"></a>Number</p>
</td>
<td class="cellrowborder" valign="top" width="52.21522152215221%" headers="mcps1.1.5.1.4 "><p id="a8dfaa6ccff584cfe8708750b49c4ede7"><a name="a8dfaa6ccff584cfe8708750b49c4ede7"></a><a name="a8dfaa6ccff584cfe8708750b49c4ede7"></a>Search radius, in meters. The default value is <strong id="b16056263217"><a name="b16056263217"></a><a name="b16056263217"></a>50000</strong>.</p>
<p id="a3889f8d560594b8c994542fbe0e4ea52"><a name="a3889f8d560594b8c994542fbe0e4ea52"></a><a name="a3889f8d560594b8c994542fbe0e4ea52"></a>The value ranges from 1 to 50000.</p>
</td>
</tr>
<tr id="ref1ce1f4acfa44c48d83e00bd18b1843"><td class="cellrowborder" valign="top" width="17.401740174017398%" headers="mcps1.1.5.1.1 "><p id="aef115f28f21c4c719acbf95875d79270"><a name="aef115f28f21c4c719acbf95875d79270"></a><a name="aef115f28f21c4c719acbf95875d79270"></a>bounds</p>
</td>
<td class="cellrowborder" valign="top" width="14.001400140014002%" headers="mcps1.1.5.1.2 "><p id="a2cace3320a214767be2b7bf6b3470598"><a name="a2cace3320a214767be2b7bf6b3470598"></a><a name="a2cace3320a214767be2b7bf6b3470598"></a>Optional</p>
</td>
<td class="cellrowborder" valign="top" width="16.38163816381638%" headers="mcps1.1.5.1.3 "><p id="aead00800060d4420a972a0f123fdccea"><a name="aead00800060d4420a972a0f123fdccea"></a><a name="aead00800060d4420a972a0f123fdccea"></a><a href="js-params.md#sb6bca9c1a2f142d287414bceeabe54a9">LatLngBounds</a></p>
</td>
<td class="cellrowborder" valign="top" width="52.21522152215221%" headers="mcps1.1.5.1.4 "><p id="a79f4eae1597c4a618ab3377a820b4c24"><a name="a79f4eae1597c4a618ab3377a820b4c24"></a><a name="a79f4eae1597c4a618ab3377a820b4c24"></a>Coordinate bounds to which search suggestions need to be biased.</p>
<div class="caution" id="note192134581559"><a name="note192134581559"></a><a name="note192134581559"></a><span class="cautiontitle"> CAUTION: </span><div class="cautionbody"><p id="p1621325818551"><a name="p1621325818551"></a><a name="p1621325818551"></a>If both <strong id="b65791339164413"><a name="b65791339164413"></a><a name="b65791339164413"></a>bounds</strong> and <strong id="b6580133984412"><a name="b6580133984412"></a><a name="b6580133984412"></a>location</strong> are passed, the value of <strong id="b858015397444"><a name="b858015397444"></a><a name="b858015397444"></a>bounds</strong> takes precedence.</p>
</div></div>
</td>
</tr>
<tr id="r62fa8bef2add4e178348b99afab3638c"><td class="cellrowborder" valign="top" width="17.401740174017398%" headers="mcps1.1.5.1.1 "><p id="ac34d730339fd416a99f832d8db604f2c"><a name="ac34d730339fd416a99f832d8db604f2c"></a><a name="ac34d730339fd416a99f832d8db604f2c"></a>poiType</p>
</td>
<td class="cellrowborder" valign="top" width="14.001400140014002%" headers="mcps1.1.5.1.2 "><p id="aebf30d64cefa41c28fb1822d54dcc54e"><a name="aebf30d64cefa41c28fb1822d54dcc54e"></a><a name="aebf30d64cefa41c28fb1822d54dcc54e"></a>Optional</p>
</td>
<td class="cellrowborder" valign="top" width="16.38163816381638%" headers="mcps1.1.5.1.3 "><p id="a6086d0adb54440b2a1e3ebbfd2d47321"><a name="a6086d0adb54440b2a1e3ebbfd2d47321"></a><a name="a6086d0adb54440b2a1e3ebbfd2d47321"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="52.21522152215221%" headers="mcps1.1.5.1.4 "><p id="a57fff6e539294278a9a07e1eebcc4270"><a name="a57fff6e539294278a9a07e1eebcc4270"></a><a name="a57fff6e539294278a9a07e1eebcc4270"></a>POI type of the returned place.</p>
<p id="a033733b72ddf40689feda1a1237ec6cd"><a name="a033733b72ddf40689feda1a1237ec6cd"></a><a name="a033733b72ddf40689feda1a1237ec6cd"></a>The options are as follows:</p>
<a name="udf923d80d1c848e8b63c30519ce99b23"></a><a name="udf923d80d1c848e8b63c30519ce99b23"></a><ul id="udf923d80d1c848e8b63c30519ce99b23"><li><strong id="b360611752315"><a name="b360611752315"></a><a name="b360611752315"></a>GEOCODE</strong>: Returns only geocoding results (such as countries, cities, and streets) but not business places (such as hotels, restaurants, and railway stations). This value can be used to eliminate ambiguity in user input. For example, when a user enters <strong id="b1430716278236"><a name="b1430716278236"></a><a name="b1430716278236"></a>China</strong>, <strong id="b83148274231"><a name="b83148274231"></a><a name="b83148274231"></a>China</strong> will be returned but data such as <strong id="b13141527122310"><a name="b13141527122310"></a><a name="b13141527122310"></a>Bank of China</strong> will not.</li><li><strong id="b1881213407231"><a name="b1881213407231"></a><a name="b1881213407231"></a>ADDRESS</strong> (a subset of <strong id="b128181140192319"><a name="b128181140192319"></a><a name="b128181140192319"></a>GEOCODE</strong>): Returns only geocoding results with accurate addresses, but not business places or coarse-grained geocoding results (such as countries and cities). This value is recommended when a user searches for a complete address.</li><li><strong id="b2403143172414"><a name="b2403143172414"></a><a name="b2403143172414"></a>ESTABLISHMENT</strong> (a complementary set of <strong id="b641133172412"><a name="b641133172412"></a><a name="b641133172412"></a>GEOCODE</strong>): Returns only business places (such as hotels, restaurants, and railway stations) but not geocoding results (such as countries, cities, and streets). For example, when a user enters <strong id="b183921401268"><a name="b183921401268"></a><a name="b183921401268"></a>China</strong>, data such as <strong id="b0398140162619"><a name="b0398140162619"></a><a name="b0398140162619"></a>Bank of China</strong> will be returned but <strong id="b1839913409263"><a name="b1839913409263"></a><a name="b1839913409263"></a>China</strong> will not.</li><li><strong id="b1488317453268"><a name="b1488317453268"></a><a name="b1488317453268"></a>REGIONS</strong> (a subset of <strong id="b588924511263"><a name="b588924511263"></a><a name="b588924511263"></a>GEOCODE</strong>): Returns only places of the following types:<p id="ac8e1d786d76c41cea1bf8547a2a3a0d5"><a name="ac8e1d786d76c41cea1bf8547a2a3a0d5"></a><a name="ac8e1d786d76c41cea1bf8547a2a3a0d5"></a>LOCALITY</p>
<p id="ac8dfa3d2257d47e1850784550160ffc3"><a name="ac8dfa3d2257d47e1850784550160ffc3"></a><a name="ac8dfa3d2257d47e1850784550160ffc3"></a>SUBLOCALITY</p>
<p id="adeb2c79100584dad8826eb8a6690e12b"><a name="adeb2c79100584dad8826eb8a6690e12b"></a><a name="adeb2c79100584dad8826eb8a6690e12b"></a>POSTAL_CODE</p>
<p id="accd97154279b4cd680b859c33f5fea00"><a name="accd97154279b4cd680b859c33f5fea00"></a><a name="accd97154279b4cd680b859c33f5fea00"></a>COUNTRY</p>
<p id="a79a6a059b1ab40bc974d4024424d9f47"><a name="a79a6a059b1ab40bc974d4024424d9f47"></a><a name="a79a6a059b1ab40bc974d4024424d9f47"></a>ADMINISTRATIVE_AREA_LEVEL_1</p>
<p id="a7e614c8f5e09422eaa92385c24cf4229"><a name="a7e614c8f5e09422eaa92385c24cf4229"></a><a name="a7e614c8f5e09422eaa92385c24cf4229"></a>ADMINISTRATIVE_AREA_LEVEL_2</p>
</li><li><strong id="b025135032617"><a name="b025135032617"></a><a name="b025135032617"></a>CITIES</strong>: Returns only places of the <strong id="b11258250152618"><a name="b11258250152618"></a><a name="b11258250152618"></a>LOCALITY</strong> or <strong id="b5259155022615"><a name="b5259155022615"></a><a name="b5259155022615"></a>ADMINISTRATIVE_AREA_LEVEL_3</strong> type.</li></ul>
</td>
</tr>
<tr id="r67c4d905797f44dcac5870e5d0e064ff"><td class="cellrowborder" valign="top" width="17.401740174017398%" headers="mcps1.1.5.1.1 "><p id="aa4a07c86a31e414c935d79e4c5e05eed"><a name="aa4a07c86a31e414c935d79e4c5e05eed"></a><a name="aa4a07c86a31e414c935d79e4c5e05eed"></a>countryCode</p>
</td>
<td class="cellrowborder" valign="top" width="14.001400140014002%" headers="mcps1.1.5.1.2 "><p id="a1f074322b2bf49bb880ecebe6bd2849c"><a name="a1f074322b2bf49bb880ecebe6bd2849c"></a><a name="a1f074322b2bf49bb880ecebe6bd2849c"></a>Optional</p>
</td>
<td class="cellrowborder" valign="top" width="16.38163816381638%" headers="mcps1.1.5.1.3 "><p id="ad1323eabac634fb0b3ab20c8a31d1759"><a name="ad1323eabac634fb0b3ab20c8a31d1759"></a><a name="ad1323eabac634fb0b3ab20c8a31d1759"></a>String(=2)</p>
</td>
<td class="cellrowborder" valign="top" width="52.21522152215221%" headers="mcps1.1.5.1.4 "><p id="ab894aa4ea985476b84759e2f49184e61"><a name="ab894aa4ea985476b84759e2f49184e61"></a><a name="ab894aa4ea985476b84759e2f49184e61"></a>Code of the country where places are searched. The value is a two-letter code complying with the ISO 3166-1 alpha-2 standard.</p>
</td>
</tr>
<tr id="ra869d23f0e0d4a5081f2e7dc2dbb358c"><td class="cellrowborder" valign="top" width="17.401740174017398%" headers="mcps1.1.5.1.1 "><p id="af2e203e06b574363bbb588e9c05965c5"><a name="af2e203e06b574363bbb588e9c05965c5"></a><a name="af2e203e06b574363bbb588e9c05965c5"></a>language</p>
</td>
<td class="cellrowborder" valign="top" width="14.001400140014002%" headers="mcps1.1.5.1.2 "><p id="a1d5971a15efb4c119f331c7a1b6547d2"><a name="a1d5971a15efb4c119f331c7a1b6547d2"></a><a name="a1d5971a15efb4c119f331c7a1b6547d2"></a>Optional</p>
</td>
<td class="cellrowborder" valign="top" width="16.38163816381638%" headers="mcps1.1.5.1.3 "><p id="a37014c13e3c9446a84eb493d910696c0"><a name="a37014c13e3c9446a84eb493d910696c0"></a><a name="a37014c13e3c9446a84eb493d910696c0"></a>String(&lt;=6)</p>
</td>
<td class="cellrowborder" valign="top" width="52.21522152215221%" headers="mcps1.1.5.1.4 "><p id="a849d0c3c810d4e9789a38423b29260f1"><a name="a849d0c3c810d4e9789a38423b29260f1"></a><a name="a849d0c3c810d4e9789a38423b29260f1"></a>Language in which search results are displayed. For details, please refer to <a href="en-us_topic_0000001050162856.md">Supported Languages</a>. If this parameter is not passed, the local language of the place will be used.</p>
</td>
</tr>
<tr id="r251c6db9b84244c89fda4f0f6b1ec4b1"><td class="cellrowborder" valign="top" width="17.401740174017398%" headers="mcps1.1.5.1.1 "><p id="a3086d1e00c1d4091ba6d6a1ff598f98d"><a name="a3086d1e00c1d4091ba6d6a1ff598f98d"></a><a name="a3086d1e00c1d4091ba6d6a1ff598f98d"></a>politicalView</p>
</td>
<td class="cellrowborder" valign="top" width="14.001400140014002%" headers="mcps1.1.5.1.2 "><p id="a3db0d62e5e764408a619dc86f30f5bee"><a name="a3db0d62e5e764408a619dc86f30f5bee"></a><a name="a3db0d62e5e764408a619dc86f30f5bee"></a>Optional</p>
</td>
<td class="cellrowborder" valign="top" width="16.38163816381638%" headers="mcps1.1.5.1.3 "><p id="a288091d957744afe9f059761b1b4ff10"><a name="a288091d957744afe9f059761b1b4ff10"></a><a name="a288091d957744afe9f059761b1b4ff10"></a>String(=2)</p>
</td>
<td class="cellrowborder" valign="top" width="52.21522152215221%" headers="mcps1.1.5.1.4 "><p id="afdd81ba1044d4c38b28e3383396af9f1"><a name="afdd81ba1044d4c38b28e3383396af9f1"></a><a name="afdd81ba1044d4c38b28e3383396af9f1"></a>Political view. The value is a two-letter country or region code complying with ISO 3166-1 alpha-2. </p>
<div class="caution" id="note13222123623911"><a name="note13222123623911"></a><a name="note13222123623911"></a><span class="cautiontitle"> CAUTION: </span><div class="cautionbody"><p id="p6222173623914"><a name="p6222173623914"></a><a name="p6222173623914"></a>This parameter has been deprecated.</p>
</div></div>
</td>
</tr>
</tbody>
</table>

## QuerySuggestionResult<a name="s5852156104864e6fa179b296ce50da80"></a>

<a name="t85bb7783e0c94f7d97180b25729233f4"></a>
<table><thead align="left"><tr id="r3389c6c95f3c4d6891cfcea536f9f688"><th class="cellrowborder" valign="top" width="20%" id="mcps1.1.4.1.1"><p id="a45bf17d7246c469bb1a34d7c92a5914e"><a name="a45bf17d7246c469bb1a34d7c92a5914e"></a><a name="a45bf17d7246c469bb1a34d7c92a5914e"></a><strong id="af66dcc69594d40d284c37455f4ffa1c0"><a name="af66dcc69594d40d284c37455f4ffa1c0"></a><a name="af66dcc69594d40d284c37455f4ffa1c0"></a>Parameter</strong></p>
</th>
<th class="cellrowborder" valign="top" width="22%" id="mcps1.1.4.1.2"><p id="a2eb6771bb44e4ee79f1a14752eb91b2e"><a name="a2eb6771bb44e4ee79f1a14752eb91b2e"></a><a name="a2eb6771bb44e4ee79f1a14752eb91b2e"></a><strong id="ad46585a7059d412ebfc64ffde6b6a5f5"><a name="ad46585a7059d412ebfc64ffde6b6a5f5"></a><a name="ad46585a7059d412ebfc64ffde6b6a5f5"></a>Type</strong></p>
</th>
<th class="cellrowborder" valign="top" width="57.99999999999999%" id="mcps1.1.4.1.3"><p id="a6819c63f39cb4d36871b1c03c93ccd03"><a name="a6819c63f39cb4d36871b1c03c93ccd03"></a><a name="a6819c63f39cb4d36871b1c03c93ccd03"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="r7730615871b14c01870a89ab7f5711c1"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.1.4.1.1 "><p id="a00e72990630c4636abff6f81609c6091"><a name="a00e72990630c4636abff6f81609c6091"></a><a name="a00e72990630c4636abff6f81609c6091"></a>sites</p>
</td>
<td class="cellrowborder" valign="top" width="22%" headers="mcps1.1.4.1.2 "><p id="a88f98745120d4c608f14f2ebe3a37427"><a name="a88f98745120d4c608f14f2ebe3a37427"></a><a name="a88f98745120d4c608f14f2ebe3a37427"></a>Array&lt;<a href="js-params.md#s39aa5bdd04dc4c36a885114f35ed8b00">Site</a>&gt;</p>
</td>
<td class="cellrowborder" valign="top" width="57.99999999999999%" headers="mcps1.1.4.1.3 "><p id="aa4e7e2ec43474b02855476505b469bf0"><a name="aa4e7e2ec43474b02855476505b469bf0"></a><a name="aa4e7e2ec43474b02855476505b469bf0"></a>Search result returned upon a successful search. If no results are available, an empty array will be returned.</p>
<div class="caution" id="note1158215346568"><a name="note1158215346568"></a><a name="note1158215346568"></a><span class="cautiontitle"> CAUTION: </span><div class="cautionbody"><p id="p65821734115612"><a name="p65821734115612"></a><a name="p65821734115612"></a>The <strong id="b1926415317443"><a name="b1926415317443"></a><a name="b1926415317443"></a>Site</strong> array does not contain the POI information. </p>
</div></div>
</td>
</tr>
</tbody>
</table>

## ReverseGeocodeRequest<a name="s96dc7d2f75954b16bc3d18aadb84ab95"></a>

<a name="table813562911913"></a>
<table><thead align="left"><tr id="row11135629096"><th class="cellrowborder" valign="top" width="18%" id="mcps1.1.5.1.1"><p id="p813514299918"><a name="p813514299918"></a><a name="p813514299918"></a>Parameter</p>
</th>
<th class="cellrowborder" valign="top" width="14.000000000000002%" id="mcps1.1.5.1.2"><p id="p813510291299"><a name="p813510291299"></a><a name="p813510291299"></a>Mandatory/Optional</p>
</th>
<th class="cellrowborder" valign="top" width="16%" id="mcps1.1.5.1.3"><p id="p213517291494"><a name="p213517291494"></a><a name="p213517291494"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="52%" id="mcps1.1.5.1.4"><p id="p111351292095"><a name="p111351292095"></a><a name="p111351292095"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row11355293910"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="p8136172910919"><a name="p8136172910919"></a><a name="p8136172910919"></a>location</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="p11365291293"><a name="p11365291293"></a><a name="p11365291293"></a>Mandatory</p>
</td>
<td class="cellrowborder" valign="top" width="16%" headers="mcps1.1.5.1.3 "><p id="p191363299913"><a name="p191363299913"></a><a name="p191363299913"></a><a href="js-params.md#s1f33822192a04bbe9bd9de86a17460b1">LatLng</a></p>
</td>
<td class="cellrowborder" valign="top" width="52%" headers="mcps1.1.5.1.4 "><p id="p191361429593"><a name="p191361429593"></a><a name="p191361429593"></a>Longitude and latitude.</p>
</td>
</tr>
<tr id="row141361429593"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="p013632911912"><a name="p013632911912"></a><a name="p013632911912"></a>language</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="p171368291095"><a name="p171368291095"></a><a name="p171368291095"></a>Optional</p>
</td>
<td class="cellrowborder" valign="top" width="16%" headers="mcps1.1.5.1.3 "><p id="p61366296916"><a name="p61366296916"></a><a name="p61366296916"></a>String(&lt;=6)</p>
</td>
<td class="cellrowborder" valign="top" width="52%" headers="mcps1.1.5.1.4 "><p id="p613613293915"><a name="p613613293915"></a><a name="p613613293915"></a>Language in which search results are displayed. For details, please refer to <a href="en-us_topic_0000001050162856.md">Supported Languages</a>. If this parameter is not passed, the local language of the place will be used.</p>
</td>
</tr>
<tr id="row613612916916"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="p7136172918916"><a name="p7136172918916"></a><a name="p7136172918916"></a>returnPoi</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="p9136129198"><a name="p9136129198"></a><a name="p9136129198"></a>Optional</p>
</td>
<td class="cellrowborder" valign="top" width="16%" headers="mcps1.1.5.1.3 "><p id="p1013615291392"><a name="p1013615291392"></a><a name="p1013615291392"></a>Boolean</p>
</td>
<td class="cellrowborder" valign="top" width="52%" headers="mcps1.1.5.1.4 "><p id="p21361329996"><a name="p21361329996"></a><a name="p21361329996"></a>Indicates whether to return the place name of a POI. The default value is <strong id="b2742202413511"><a name="b2742202413511"></a><a name="b2742202413511"></a>true</strong>.</p>
<div class="note" id="note14136729794"><a name="note14136729794"></a><a name="note14136729794"></a><span class="notetitle"> NOTE: </span><div class="notebody"><p id="p713662913918"><a name="p713662913918"></a><a name="p713662913918"></a>Currently, the reverse geocoding API can only return the name of an airport.</p>
</div></div>
</td>
</tr>
<tr id="row8137229699"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="p7137172912910"><a name="p7137172912910"></a><a name="p7137172912910"></a>politicalView</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="p101372291898"><a name="p101372291898"></a><a name="p101372291898"></a>Optional</p>
</td>
<td class="cellrowborder" valign="top" width="16%" headers="mcps1.1.5.1.3 "><p id="p1013718292913"><a name="p1013718292913"></a><a name="p1013718292913"></a>String(=2)</p>
</td>
<td class="cellrowborder" valign="top" width="52%" headers="mcps1.1.5.1.4 "><p id="p1313711296911"><a name="p1313711296911"></a><a name="p1313711296911"></a>Political view. The value is a two-letter country or region code complying with ISO 3166-1 alpha-2. </p>
<div class="caution" id="note13391446193912"><a name="note13391446193912"></a><a name="note13391446193912"></a><span class="cautiontitle"> CAUTION: </span><div class="cautionbody"><p id="p194014623919"><a name="p194014623919"></a><a name="p194014623919"></a>This parameter has been deprecated.</p>
</div></div>
</td>
</tr>
</tbody>
</table>

## ReverseGeocodeResult<a name="se01b3c4effc145eea8d138b862d579bd"></a>

<a name="table17467449096"></a>
<table><thead align="left"><tr id="row14467164913915"><th class="cellrowborder" valign="top" width="20%" id="mcps1.1.4.1.1"><p id="p104671549496"><a name="p104671549496"></a><a name="p104671549496"></a>Parameter</p>
</th>
<th class="cellrowborder" valign="top" width="20%" id="mcps1.1.4.1.2"><p id="p154672049599"><a name="p154672049599"></a><a name="p154672049599"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.1.4.1.3"><p id="p446713491196"><a name="p446713491196"></a><a name="p446713491196"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row1946714918920"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.1.4.1.1 "><p id="p946734910918"><a name="p946734910918"></a><a name="p946734910918"></a>sites</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.1.4.1.2 "><p id="p114671491591"><a name="p114671491591"></a><a name="p114671491591"></a>Array&lt;<a href="js-params.md#s39aa5bdd04dc4c36a885114f35ed8b00">Site</a>&gt;</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.4.1.3 "><p id="p17467174911918"><a name="p17467174911918"></a><a name="p17467174911918"></a>Search result returned upon a successful search. If no results are available, an empty array will be returned.</p>
<div class="caution" id="note546734917911"><a name="note546734917911"></a><a name="note546734917911"></a><span class="cautiontitle"> CAUTION: </span><div class="cautionbody"><p id="p134671949994"><a name="p134671949994"></a><a name="p134671949994"></a>The <strong id="b8970610184512"><a name="b8970610184512"></a><a name="b8970610184512"></a>Site</strong> array does not contain the POI information. </p>
</div></div>
</td>
</tr>
</tbody>
</table>

## SearchByIdRequest<a name="se56aef8cc8f84672a38beaeb38483422"></a>

<a name="tf867e395641c4951b207a2b9128310cf"></a>
<table><thead align="left"><tr id="rb441a3564f2f4a06a527a5f8365416cc"><th class="cellrowborder" valign="top" width="20%" id="mcps1.1.5.1.1"><p id="a22eddb6c56c148ec8f761aec3e340b9c"><a name="a22eddb6c56c148ec8f761aec3e340b9c"></a><a name="a22eddb6c56c148ec8f761aec3e340b9c"></a>Parameter</p>
</th>
<th class="cellrowborder" valign="top" width="14.000000000000002%" id="mcps1.1.5.1.2"><p id="a5c85deea7f4d4b53b7c7031e9654c94a"><a name="a5c85deea7f4d4b53b7c7031e9654c94a"></a><a name="a5c85deea7f4d4b53b7c7031e9654c94a"></a>Mandatory/Optional</p>
</th>
<th class="cellrowborder" valign="top" width="16%" id="mcps1.1.5.1.3"><p id="a9f3979242d4e4a96a4137a0f6df0a801"><a name="a9f3979242d4e4a96a4137a0f6df0a801"></a><a name="a9f3979242d4e4a96a4137a0f6df0a801"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.1.5.1.4"><p id="afa8ae40cb53d456289c10d9246b38087"><a name="afa8ae40cb53d456289c10d9246b38087"></a><a name="afa8ae40cb53d456289c10d9246b38087"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="r76baf25a9a934d89b986cb93064f7437"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.1.5.1.1 "><p id="ac5661819ff014fb39fc0588d9f4028c3"><a name="ac5661819ff014fb39fc0588d9f4028c3"></a><a name="ac5661819ff014fb39fc0588d9f4028c3"></a>siteId</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="adcfa234057624bfbba12fbc19975a692"><a name="adcfa234057624bfbba12fbc19975a692"></a><a name="adcfa234057624bfbba12fbc19975a692"></a>Mandatory</p>
</td>
<td class="cellrowborder" valign="top" width="16%" headers="mcps1.1.5.1.3 "><p id="a88fe597e29b34d71ab01aa94a5e0ccc2"><a name="a88fe597e29b34d71ab01aa94a5e0ccc2"></a><a name="a88fe597e29b34d71ab01aa94a5e0ccc2"></a>String(&lt;=256)</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="a44453692420e4576a82ea59fe24318cb"><a name="a44453692420e4576a82ea59fe24318cb"></a><a name="a44453692420e4576a82ea59fe24318cb"></a>ID of a place.</p>
</td>
</tr>
<tr id="r39373648ca1640d7bf32a2116c3dd72d"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.1.5.1.1 "><p id="a14661487091a41a69d64feedc4be07fa"><a name="a14661487091a41a69d64feedc4be07fa"></a><a name="a14661487091a41a69d64feedc4be07fa"></a>language</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="a8d9d4ab443ae46ecab4e84816a21e3c7"><a name="a8d9d4ab443ae46ecab4e84816a21e3c7"></a><a name="a8d9d4ab443ae46ecab4e84816a21e3c7"></a>Optional</p>
</td>
<td class="cellrowborder" valign="top" width="16%" headers="mcps1.1.5.1.3 "><p id="aad3ba6f653f54ba39a8ae35efa71219f"><a name="aad3ba6f653f54ba39a8ae35efa71219f"></a><a name="aad3ba6f653f54ba39a8ae35efa71219f"></a>String(&lt;=6)</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="a187534fbf0444d4488edc68f5f783837"><a name="a187534fbf0444d4488edc68f5f783837"></a><a name="a187534fbf0444d4488edc68f5f783837"></a>Language in which search results are displayed. For details, please refer to <a href="en-us_topic_0000001050162856.md">Supported Languages</a>. If this parameter is not passed, the local language of the place will be used.</p>
</td>
</tr>
<tr id="r09e8af6e92e544cdbe0cb304a4ba620d"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.1.5.1.1 "><p id="ac853303df4ac4da5bf2641e69f598a8b"><a name="ac853303df4ac4da5bf2641e69f598a8b"></a><a name="ac853303df4ac4da5bf2641e69f598a8b"></a>politicalView</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="a93dea5b909c34218b2e63df216fbb405"><a name="a93dea5b909c34218b2e63df216fbb405"></a><a name="a93dea5b909c34218b2e63df216fbb405"></a>Optional</p>
</td>
<td class="cellrowborder" valign="top" width="16%" headers="mcps1.1.5.1.3 "><p id="a87f0bf3257484695a9fde4d170bb3509"><a name="a87f0bf3257484695a9fde4d170bb3509"></a><a name="a87f0bf3257484695a9fde4d170bb3509"></a>String(=2)</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="a7a885bdd07dd473eba69411143865d57"><a name="a7a885bdd07dd473eba69411143865d57"></a><a name="a7a885bdd07dd473eba69411143865d57"></a>Political view. The value is a two-letter country or region code complying with ISO 3166-1 alpha-2. </p>
<div class="caution" id="note11401175411395"><a name="note11401175411395"></a><a name="note11401175411395"></a><span class="cautiontitle"> CAUTION: </span><div class="cautionbody"><p id="p44011554173911"><a name="p44011554173911"></a><a name="p44011554173911"></a>This parameter has been deprecated.</p>
</div></div>
</td>
</tr>
</tbody>
</table>

## SearchByIdResult<a name="s17d0b19b28ce4030848dc8970b41f896"></a>

<a name="t07c3d1703c6a4208940937ccc20d9d5e"></a>
<table><thead align="left"><tr id="r4d498ca9e86d4dcb8196baa98eb46efb"><th class="cellrowborder" valign="top" width="18%" id="mcps1.1.4.1.1"><p id="ad6bb51b2d4e4459385a92e3c63c7648e"><a name="ad6bb51b2d4e4459385a92e3c63c7648e"></a><a name="ad6bb51b2d4e4459385a92e3c63c7648e"></a><strong id="ae6d171f1f9884f9da1dc5b32e7dfca54"><a name="ae6d171f1f9884f9da1dc5b32e7dfca54"></a><a name="ae6d171f1f9884f9da1dc5b32e7dfca54"></a>Parameter</strong></p>
</th>
<th class="cellrowborder" valign="top" width="22%" id="mcps1.1.4.1.2"><p id="a70278159affb492abb317c26fefaeca2"><a name="a70278159affb492abb317c26fefaeca2"></a><a name="a70278159affb492abb317c26fefaeca2"></a><strong id="affbe5794dd6f47de84505a68b48ef15e"><a name="affbe5794dd6f47de84505a68b48ef15e"></a><a name="affbe5794dd6f47de84505a68b48ef15e"></a>Type</strong></p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.1.4.1.3"><p id="a19a16c48d902445f9eb7eadf6c847582"><a name="a19a16c48d902445f9eb7eadf6c847582"></a><a name="a19a16c48d902445f9eb7eadf6c847582"></a><strong id="a00a1adc9144e45d3b7572ae1e1521ef8"><a name="a00a1adc9144e45d3b7572ae1e1521ef8"></a><a name="a00a1adc9144e45d3b7572ae1e1521ef8"></a>Description</strong></p>
</th>
</tr>
</thead>
<tbody><tr id="rad15cd9e00154ac68f5cc91348adb013"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.4.1.1 "><p id="a18d59290faee48ea928f263a11e8d133"><a name="a18d59290faee48ea928f263a11e8d133"></a><a name="a18d59290faee48ea928f263a11e8d133"></a>site</p>
</td>
<td class="cellrowborder" valign="top" width="22%" headers="mcps1.1.4.1.2 "><p id="aa7f6436f46754803b9ec85083ca6509b"><a name="aa7f6436f46754803b9ec85083ca6509b"></a><a name="aa7f6436f46754803b9ec85083ca6509b"></a><a href="js-params.md#s39aa5bdd04dc4c36a885114f35ed8b00">Site</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.4.1.3 "><p id="a2c5f07764c3746d095c124e063f81b3b"><a name="a2c5f07764c3746d095c124e063f81b3b"></a><a name="a2c5f07764c3746d095c124e063f81b3b"></a>Place details upon a successful search or error description upon a search failure.</p>
</td>
</tr>
</tbody>
</table>

## SearchByTextRequest<a name="s8239feda84464c79a65d17ea4e91409b"></a>

<a name="t7f94119c94c4401bbeebfd779d954294"></a>
<table><thead align="left"><tr id="rbb4a6ffa5fcb460690da6c5e9e68202c"><th class="cellrowborder" valign="top" width="17.82821717828217%" id="mcps1.1.5.1.1"><p id="a6b4893ec27db45c4a5f5645b557560a9"><a name="a6b4893ec27db45c4a5f5645b557560a9"></a><a name="a6b4893ec27db45c4a5f5645b557560a9"></a>Parameter</p>
</th>
<th class="cellrowborder" valign="top" width="13.998600139986003%" id="mcps1.1.5.1.2"><p id="aa7b73af1298c40f18e32940a9173deb6"><a name="aa7b73af1298c40f18e32940a9173deb6"></a><a name="aa7b73af1298c40f18e32940a9173deb6"></a>Mandatory/Optional</p>
</th>
<th class="cellrowborder" valign="top" width="20.97790220977902%" id="mcps1.1.5.1.3"><p id="ace18c5c266554206a1e171d59ada8f9a"><a name="ace18c5c266554206a1e171d59ada8f9a"></a><a name="ace18c5c266554206a1e171d59ada8f9a"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="47.195280471952806%" id="mcps1.1.5.1.4"><p id="a26902fec438e4176b71d64b054f87dc9"><a name="a26902fec438e4176b71d64b054f87dc9"></a><a name="a26902fec438e4176b71d64b054f87dc9"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="re1428f90dc6549848ce2294585839095"><td class="cellrowborder" valign="top" width="17.82821717828217%" headers="mcps1.1.5.1.1 "><p id="af188033a64584fa1a6f2b68a6ffb2b1a"><a name="af188033a64584fa1a6f2b68a6ffb2b1a"></a><a name="af188033a64584fa1a6f2b68a6ffb2b1a"></a>query</p>
</td>
<td class="cellrowborder" valign="top" width="13.998600139986003%" headers="mcps1.1.5.1.2 "><p id="af79028769910497798cfb01c78f21f40"><a name="af79028769910497798cfb01c78f21f40"></a><a name="af79028769910497798cfb01c78f21f40"></a>Mandatory</p>
</td>
<td class="cellrowborder" valign="top" width="20.97790220977902%" headers="mcps1.1.5.1.3 "><p id="ab6a40bd335c34bf6966e9e1093adbd75"><a name="ab6a40bd335c34bf6966e9e1093adbd75"></a><a name="ab6a40bd335c34bf6966e9e1093adbd75"></a>String(&lt;=512)</p>
</td>
<td class="cellrowborder" valign="top" width="47.195280471952806%" headers="mcps1.1.5.1.4 "><p id="a15af4c617356431db6ca9fc3e2433d64"><a name="a15af4c617356431db6ca9fc3e2433d64"></a><a name="a15af4c617356431db6ca9fc3e2433d64"></a>Search keyword.</p>
</td>
</tr>
<tr id="r41571bad57f94fd8a5ad297f02ba4bc1"><td class="cellrowborder" valign="top" width="17.82821717828217%" headers="mcps1.1.5.1.1 "><p id="afdc789d585ec4d54bb039f97ba0e52d3"><a name="afdc789d585ec4d54bb039f97ba0e52d3"></a><a name="afdc789d585ec4d54bb039f97ba0e52d3"></a>location</p>
</td>
<td class="cellrowborder" valign="top" width="13.998600139986003%" headers="mcps1.1.5.1.2 "><p id="a8fa3566276f54870a5cd4c65195f6b86"><a name="a8fa3566276f54870a5cd4c65195f6b86"></a><a name="a8fa3566276f54870a5cd4c65195f6b86"></a>Optional</p>
</td>
<td class="cellrowborder" valign="top" width="20.97790220977902%" headers="mcps1.1.5.1.3 "><p id="a005be4f5a91247999426842dc615ae29"><a name="a005be4f5a91247999426842dc615ae29"></a><a name="a005be4f5a91247999426842dc615ae29"></a><a href="js-params.md#s1f33822192a04bbe9bd9de86a17460b1">LatLng</a></p>
</td>
<td class="cellrowborder" valign="top" width="47.195280471952806%" headers="mcps1.1.5.1.4 "><p id="aba4638481b7644e8a66dc33439f6afd1"><a name="aba4638481b7644e8a66dc33439f6afd1"></a><a name="aba4638481b7644e8a66dc33439f6afd1"></a>Longitude and latitude to which search results need to be biased.</p>
</td>
</tr>
<tr id="r53c1b01876a94db48d3150faa5bea577"><td class="cellrowborder" valign="top" width="17.82821717828217%" headers="mcps1.1.5.1.1 "><p id="aa21a503cbab54974bc07669748f2fe28"><a name="aa21a503cbab54974bc07669748f2fe28"></a><a name="aa21a503cbab54974bc07669748f2fe28"></a>radius</p>
</td>
<td class="cellrowborder" valign="top" width="13.998600139986003%" headers="mcps1.1.5.1.2 "><p id="a19231a234b024f0b84accadb3a532f95"><a name="a19231a234b024f0b84accadb3a532f95"></a><a name="a19231a234b024f0b84accadb3a532f95"></a>Optional</p>
</td>
<td class="cellrowborder" valign="top" width="20.97790220977902%" headers="mcps1.1.5.1.3 "><p id="a0e6dd09590f647fcbbe2291231f26702"><a name="a0e6dd09590f647fcbbe2291231f26702"></a><a name="a0e6dd09590f647fcbbe2291231f26702"></a>Number</p>
</td>
<td class="cellrowborder" valign="top" width="47.195280471952806%" headers="mcps1.1.5.1.4 "><p id="a31a623572f3248fb9909998f9d0beccd"><a name="a31a623572f3248fb9909998f9d0beccd"></a><a name="a31a623572f3248fb9909998f9d0beccd"></a>Search radius, in meters. The default value is <strong id="b6519833154117"><a name="b6519833154117"></a><a name="b6519833154117"></a>50000</strong>.</p>
<p id="a07f99e9c2dee4c6f9f0ac59a0d99fddc"><a name="a07f99e9c2dee4c6f9f0ac59a0d99fddc"></a><a name="a07f99e9c2dee4c6f9f0ac59a0d99fddc"></a>The value ranges from 1 to 50000.</p>
</td>
</tr>
<tr id="r43c326fa8deb494ebb5ad1e8c5194df1"><td class="cellrowborder" valign="top" width="17.82821717828217%" headers="mcps1.1.5.1.1 "><p id="a95c0d1b4593540c9b80ef7b335f6a64f"><a name="a95c0d1b4593540c9b80ef7b335f6a64f"></a><a name="a95c0d1b4593540c9b80ef7b335f6a64f"></a>poiType</p>
</td>
<td class="cellrowborder" valign="top" width="13.998600139986003%" headers="mcps1.1.5.1.2 "><p id="a1043ad490832406f91892c1ac408daff"><a name="a1043ad490832406f91892c1ac408daff"></a><a name="a1043ad490832406f91892c1ac408daff"></a>Optional</p>
</td>
<td class="cellrowborder" valign="top" width="20.97790220977902%" headers="mcps1.1.5.1.3 "><p id="a24eb6ff8c9c34f6086ecd8aea10bfabc"><a name="a24eb6ff8c9c34f6086ecd8aea10bfabc"></a><a name="a24eb6ff8c9c34f6086ecd8aea10bfabc"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="47.195280471952806%" headers="mcps1.1.5.1.4 "><p id="a8acf4c1514f94474a4831809d7ceff8e"><a name="a8acf4c1514f94474a4831809d7ceff8e"></a><a name="a8acf4c1514f94474a4831809d7ceff8e"></a>POI type of the returned place.</p>
</td>
</tr>
<tr id="r1f4a5044ea8a41aa9f2510a28d945771"><td class="cellrowborder" valign="top" width="17.82821717828217%" headers="mcps1.1.5.1.1 "><p id="acc1e24332415461893b25315749be4ca"><a name="acc1e24332415461893b25315749be4ca"></a><a name="acc1e24332415461893b25315749be4ca"></a>countryCode</p>
</td>
<td class="cellrowborder" valign="top" width="13.998600139986003%" headers="mcps1.1.5.1.2 "><p id="a4eafc10bc867408ab043fded99b9ba15"><a name="a4eafc10bc867408ab043fded99b9ba15"></a><a name="a4eafc10bc867408ab043fded99b9ba15"></a>Optional</p>
</td>
<td class="cellrowborder" valign="top" width="20.97790220977902%" headers="mcps1.1.5.1.3 "><p id="a90cc050b4e814d36adf20efb2b812a6f"><a name="a90cc050b4e814d36adf20efb2b812a6f"></a><a name="a90cc050b4e814d36adf20efb2b812a6f"></a>String(=2)</p>
</td>
<td class="cellrowborder" valign="top" width="47.195280471952806%" headers="mcps1.1.5.1.4 "><p id="ad27c3121b93d4f5f8d76d0d318c187dd"><a name="ad27c3121b93d4f5f8d76d0d318c187dd"></a><a name="ad27c3121b93d4f5f8d76d0d318c187dd"></a>Code of the country where places are searched. The value is a two-letter code complying with the ISO 3166-1 alpha-2 standard.</p>
</td>
</tr>
<tr id="r61587d60e7644a51ae1bfcbea2f5ab8a"><td class="cellrowborder" valign="top" width="17.82821717828217%" headers="mcps1.1.5.1.1 "><p id="adbc73ff8f32447179efcd17379ef994b"><a name="adbc73ff8f32447179efcd17379ef994b"></a><a name="adbc73ff8f32447179efcd17379ef994b"></a>language</p>
</td>
<td class="cellrowborder" valign="top" width="13.998600139986003%" headers="mcps1.1.5.1.2 "><p id="aefb07f739f8644be9587bb2eff302cb3"><a name="aefb07f739f8644be9587bb2eff302cb3"></a><a name="aefb07f739f8644be9587bb2eff302cb3"></a>Optional</p>
</td>
<td class="cellrowborder" valign="top" width="20.97790220977902%" headers="mcps1.1.5.1.3 "><p id="a07471e1c5a0a4e73a9f655632e77bd1b"><a name="a07471e1c5a0a4e73a9f655632e77bd1b"></a><a name="a07471e1c5a0a4e73a9f655632e77bd1b"></a>String(&lt;=6)</p>
</td>
<td class="cellrowborder" valign="top" width="47.195280471952806%" headers="mcps1.1.5.1.4 "><p id="a4e6d5468df164f8eb8cc01a6195a18d5"><a name="a4e6d5468df164f8eb8cc01a6195a18d5"></a><a name="a4e6d5468df164f8eb8cc01a6195a18d5"></a>Language in which search results are displayed. For details, please refer to <a href="en-us_topic_0000001050162856.md">Supported Languages</a>. If this parameter is not passed, the local language of the place will be used.</p>
</td>
</tr>
<tr id="rc4d8b85d261947afa6ab163510150ce1"><td class="cellrowborder" valign="top" width="17.82821717828217%" headers="mcps1.1.5.1.1 "><p id="a8d9089b86cc14614a6931ea38eb3d44c"><a name="a8d9089b86cc14614a6931ea38eb3d44c"></a><a name="a8d9089b86cc14614a6931ea38eb3d44c"></a>pageSize</p>
</td>
<td class="cellrowborder" valign="top" width="13.998600139986003%" headers="mcps1.1.5.1.2 "><p id="af72024b9239d41efb2c5676d24f9f45f"><a name="af72024b9239d41efb2c5676d24f9f45f"></a><a name="af72024b9239d41efb2c5676d24f9f45f"></a>Optional</p>
</td>
<td class="cellrowborder" valign="top" width="20.97790220977902%" headers="mcps1.1.5.1.3 "><p id="a1b92568c396846d19bfc9eb569771e0e"><a name="a1b92568c396846d19bfc9eb569771e0e"></a><a name="a1b92568c396846d19bfc9eb569771e0e"></a>Number</p>
</td>
<td class="cellrowborder" valign="top" width="47.195280471952806%" headers="mcps1.1.5.1.4 "><p id="ab690e927cfd24e328c272f357f00ec2e"><a name="ab690e927cfd24e328c272f357f00ec2e"></a><a name="ab690e927cfd24e328c272f357f00ec2e"></a>Number of records on each page. The default value is <strong id="b496987164211"><a name="b496987164211"></a><a name="b496987164211"></a>20</strong>.</p>
<p id="a606e84dd75bc4620ad6309182c8da93a"><a name="a606e84dd75bc4620ad6309182c8da93a"></a><a name="a606e84dd75bc4620ad6309182c8da93a"></a>The value ranges from 1 to 20.</p>
</td>
</tr>
<tr id="r4f91a969bf99443aa84c86e47a51ae16"><td class="cellrowborder" valign="top" width="17.82821717828217%" headers="mcps1.1.5.1.1 "><p id="adeaf942ac29d42c7be2a7ce15f1cc2ce"><a name="adeaf942ac29d42c7be2a7ce15f1cc2ce"></a><a name="adeaf942ac29d42c7be2a7ce15f1cc2ce"></a>pageIndex</p>
</td>
<td class="cellrowborder" valign="top" width="13.998600139986003%" headers="mcps1.1.5.1.2 "><p id="accbf7b02b0a54fe0b0040da60a4060f0"><a name="accbf7b02b0a54fe0b0040da60a4060f0"></a><a name="accbf7b02b0a54fe0b0040da60a4060f0"></a>Optional</p>
</td>
<td class="cellrowborder" valign="top" width="20.97790220977902%" headers="mcps1.1.5.1.3 "><p id="a33aea6f1705a46fe9e287de3cc8e7a0d"><a name="a33aea6f1705a46fe9e287de3cc8e7a0d"></a><a name="a33aea6f1705a46fe9e287de3cc8e7a0d"></a>Number</p>
</td>
<td class="cellrowborder" valign="top" width="47.195280471952806%" headers="mcps1.1.5.1.4 "><p id="aecbfb953da7a48cfa9cefad3aba9fe9c"><a name="aecbfb953da7a48cfa9cefad3aba9fe9c"></a><a name="aecbfb953da7a48cfa9cefad3aba9fe9c"></a>Current page number. The default value is <strong id="b2920181034212"><a name="b2920181034212"></a><a name="b2920181034212"></a>1</strong>.</p>
<p id="a89b6d643a1ce48c2bee83ada1bdb17f1"><a name="a89b6d643a1ce48c2bee83ada1bdb17f1"></a><a name="a89b6d643a1ce48c2bee83ada1bdb17f1"></a>The value ranges from 1 to 60.</p>
<p id="a6dc0d1b78adb446889862996cb95e0aa"><a name="a6dc0d1b78adb446889862996cb95e0aa"></a><a name="a6dc0d1b78adb446889862996cb95e0aa"></a>The following formula must be met: <strong id="b14891162114212"><a name="b14891162114212"></a><a name="b14891162114212"></a>pageIndex</strong> x <strong id="b58921521124212"><a name="b58921521124212"></a><a name="b58921521124212"></a>pageSize</strong> ≤ 60. </p>
</td>
</tr>
<tr id="rba413975650d4634af8ea07ef9b9d407"><td class="cellrowborder" valign="top" width="17.82821717828217%" headers="mcps1.1.5.1.1 "><p id="abf1c8c2a16d34dfc839812598f1a7a0d"><a name="abf1c8c2a16d34dfc839812598f1a7a0d"></a><a name="abf1c8c2a16d34dfc839812598f1a7a0d"></a>politicalView</p>
</td>
<td class="cellrowborder" valign="top" width="13.998600139986003%" headers="mcps1.1.5.1.2 "><p id="af2456727b056432da4018c10bdd6da0a"><a name="af2456727b056432da4018c10bdd6da0a"></a><a name="af2456727b056432da4018c10bdd6da0a"></a>Optional</p>
</td>
<td class="cellrowborder" valign="top" width="20.97790220977902%" headers="mcps1.1.5.1.3 "><p id="a649c629c5f4944cbaeb6b411da880edd"><a name="a649c629c5f4944cbaeb6b411da880edd"></a><a name="a649c629c5f4944cbaeb6b411da880edd"></a>String(=2)</p>
</td>
<td class="cellrowborder" valign="top" width="47.195280471952806%" headers="mcps1.1.5.1.4 "><p id="af6c4a0206bfe4913abd3f6a094710a5e"><a name="af6c4a0206bfe4913abd3f6a094710a5e"></a><a name="af6c4a0206bfe4913abd3f6a094710a5e"></a>Political view. The value is a two-letter country or region code complying with ISO 3166-1 alpha-2. </p>
<div class="caution" id="note191789616402"><a name="note191789616402"></a><a name="note191789616402"></a><span class="cautiontitle"> CAUTION: </span><div class="cautionbody"><p id="p11784654012"><a name="p11784654012"></a><a name="p11784654012"></a>This parameter has been deprecated.</p>
</div></div>
</td>
</tr>
</tbody>
</table>

## SearchByTextResult<a name="sed67def73702462b8ae318a0f755b245"></a>

<a name="tbee7f847bc6f4a2cb2e7974d1c6c6261"></a>
<table><thead align="left"><tr id="r0faedef41b034f6f846af4b4ef26dde5"><th class="cellrowborder" valign="top" width="18.18%" id="mcps1.1.4.1.1"><p id="abb177b9a7b274899a48ab4eb79d6a2c2"><a name="abb177b9a7b274899a48ab4eb79d6a2c2"></a><a name="abb177b9a7b274899a48ab4eb79d6a2c2"></a>Parameter</p>
</th>
<th class="cellrowborder" valign="top" width="22.220000000000002%" id="mcps1.1.4.1.2"><p id="ac36d048e99844fe68199cc548e442056"><a name="ac36d048e99844fe68199cc548e442056"></a><a name="ac36d048e99844fe68199cc548e442056"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="59.599999999999994%" id="mcps1.1.4.1.3"><p id="a91c24686cce3480b932a8310d2463ff1"><a name="a91c24686cce3480b932a8310d2463ff1"></a><a name="a91c24686cce3480b932a8310d2463ff1"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="rc7496322fb8e4cc8a97d18e0e591b3fa"><td class="cellrowborder" valign="top" width="18.18%" headers="mcps1.1.4.1.1 "><p id="a45f88a381b214aa4bde6f2ceac52cd52"><a name="a45f88a381b214aa4bde6f2ceac52cd52"></a><a name="a45f88a381b214aa4bde6f2ceac52cd52"></a>totalCount</p>
</td>
<td class="cellrowborder" valign="top" width="22.220000000000002%" headers="mcps1.1.4.1.2 "><p id="a920b0c423ea6482f86143a675314532c"><a name="a920b0c423ea6482f86143a675314532c"></a><a name="a920b0c423ea6482f86143a675314532c"></a>int</p>
</td>
<td class="cellrowborder" valign="top" width="59.599999999999994%" headers="mcps1.1.4.1.3 "><p id="afd3eb9508ed0462180178efe650fba97"><a name="afd3eb9508ed0462180178efe650fba97"></a><a name="afd3eb9508ed0462180178efe650fba97"></a>Total number of records returned upon a successful search. If no records are found, <strong id="b24200427428"><a name="b24200427428"></a><a name="b24200427428"></a>0</strong> will be returned.</p>
</td>
</tr>
<tr id="r21f1bd49a2924a1eb50888044cb917fc"><td class="cellrowborder" valign="top" width="18.18%" headers="mcps1.1.4.1.1 "><p id="a8fc9e8e0410d4fb6be246b8bafb7575c"><a name="a8fc9e8e0410d4fb6be246b8bafb7575c"></a><a name="a8fc9e8e0410d4fb6be246b8bafb7575c"></a>sites</p>
</td>
<td class="cellrowborder" valign="top" width="22.220000000000002%" headers="mcps1.1.4.1.2 "><p id="ac479e139e28641b4909a63854e6fb3cf"><a name="ac479e139e28641b4909a63854e6fb3cf"></a><a name="ac479e139e28641b4909a63854e6fb3cf"></a>Array&lt;<a href="js-params.md#s39aa5bdd04dc4c36a885114f35ed8b00">Site</a>&gt;</p>
</td>
<td class="cellrowborder" valign="top" width="59.599999999999994%" headers="mcps1.1.4.1.3 "><p id="a69b16f3793e047f08aed0ce9cc08882a"><a name="a69b16f3793e047f08aed0ce9cc08882a"></a><a name="a69b16f3793e047f08aed0ce9cc08882a"></a>Search result returned upon a successful search. If no results are available, an empty array will be returned.</p>
</td>
</tr>
</tbody>
</table>

