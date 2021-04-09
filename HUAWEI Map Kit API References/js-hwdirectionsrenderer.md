# HWDirectionsRenderer<a name="EN-US_TOPIC_0000001145941069"></a>

-   [Overview](#sa8e6f18a96b94ab99cc06b2c60610581)
-   [Build Method](#s3bbda110ffd94c86b1234ed1027c5572)
-   [Public Methods](#s4b91cce9824e42d1a489643325bc3893)
-   [RendererOptions](#s2fd0eef94f7d406dba7e693745e954f0)

## Overview<a name="sa8e6f18a96b94ab99cc06b2c60610581"></a>

Displays the planned routes on the map using polylines based on the result returned by the route planning API. 

## Build Method<a name="s3bbda110ffd94c86b1234ed1027c5572"></a>

<a name="tab0e9ec50c0e434c9181180f3abb8053"></a>
<table><thead align="left"><tr id="rd574be4b1b9d4103b051b5c2a9b8fdb6"><th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.1"><p id="a384191f9dd614e028f1a084e35a91f82"><a name="a384191f9dd614e028f1a084e35a91f82"></a><a name="a384191f9dd614e028f1a084e35a91f82"></a><strong id="a176adfd5270d4882bb941164bb09118b"><a name="a176adfd5270d4882bb941164bb09118b"></a><a name="a176adfd5270d4882bb941164bb09118b"></a>Build Method</strong></p>
</th>
<th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.2"><p id="a754295a0134b4fe084a21cfc68ca89f1"><a name="a754295a0134b4fe084a21cfc68ca89f1"></a><a name="a754295a0134b4fe084a21cfc68ca89f1"></a><strong id="b3882343175613"><a name="b3882343175613"></a><a name="b3882343175613"></a>Description</strong></p>
</th>
</tr>
</thead>
<tbody><tr id="r4dcd5d86b3354af8b82d620ab1d90457"><td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.1 "><p id="a772e573665cb4d0781bf69a3a8be2b93"><a name="a772e573665cb4d0781bf69a3a8be2b93"></a><a name="a772e573665cb4d0781bf69a3a8be2b93"></a>HWMapJsSDK.HWDirectionsRenderer()</p>
</td>
<td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.2 "><p id="a8c209857ff0b472c815da14ac26b7770"><a name="a8c209857ff0b472c815da14ac26b7770"></a><a name="a8c209857ff0b472c815da14ac26b7770"></a>-</p>
</td>
</tr>
</tbody>
</table>

## Public Methods<a name="s4b91cce9824e42d1a489643325bc3893"></a>

<a name="td769085cfe7a439c9852880f3782d9e3"></a>
<table><thead align="left"><tr id="re161b98a303d443a8b6a9e7d90869b40"><th class="cellrowborder" valign="top" width="24%" id="mcps1.1.5.1.1"><p id="ada01bd2bf8d14b5b969c5dd4b826924a"><a name="ada01bd2bf8d14b5b969c5dd4b826924a"></a><a name="ada01bd2bf8d14b5b969c5dd4b826924a"></a><strong id="b24241156175912"><a name="b24241156175912"></a><a name="b24241156175912"></a>Method</strong></p>
</th>
<th class="cellrowborder" valign="top" width="24%" id="mcps1.1.5.1.2"><p id="aeaa685ad5c0c4e4397e8c5b5dfef2e24"><a name="aeaa685ad5c0c4e4397e8c5b5dfef2e24"></a><a name="aeaa685ad5c0c4e4397e8c5b5dfef2e24"></a><strong id="b156981451115613"><a name="b156981451115613"></a><a name="b156981451115613"></a>Description</strong></p>
</th>
<th class="cellrowborder" valign="top" width="32.67%" id="mcps1.1.5.1.3"><p id="ac1c0df988fcc4282afa5ff6a0784691c"><a name="ac1c0df988fcc4282afa5ff6a0784691c"></a><a name="ac1c0df988fcc4282afa5ff6a0784691c"></a><strong id="a9d18aaee46114ecab693079b30603533"><a name="a9d18aaee46114ecab693079b30603533"></a><a name="a9d18aaee46114ecab693079b30603533"></a>Type</strong></p>
</th>
<th class="cellrowborder" valign="top" width="19.33%" id="mcps1.1.5.1.4"><p id="a02e1b78043d4413f869b25af519f3923"><a name="a02e1b78043d4413f869b25af519f3923"></a><a name="a02e1b78043d4413f869b25af519f3923"></a><strong id="aac70655e4aa74b1da1b5ba4fcbaf00d1"><a name="aac70655e4aa74b1da1b5ba4fcbaf00d1"></a><a name="aac70655e4aa74b1da1b5ba4fcbaf00d1"></a>Return Value</strong></p>
</th>
</tr>
</thead>
<tbody><tr id="rc22087a853c24effafaea354d439774a"><td class="cellrowborder" valign="top" width="24%" headers="mcps1.1.5.1.1 "><p id="a8ec92f7ec2ae4368a5fdda2c2c9e9a5a"><a name="a8ec92f7ec2ae4368a5fdda2c2c9e9a5a"></a><a name="a8ec92f7ec2ae4368a5fdda2c2c9e9a5a"></a>setMap(map)</p>
</td>
<td class="cellrowborder" valign="top" width="24%" headers="mcps1.1.5.1.2 "><p id="aba41661d6d944b2398a8276efbb33088"><a name="aba41661d6d944b2398a8276efbb33088"></a><a name="aba41661d6d944b2398a8276efbb33088"></a>Sets a map instance to which the planned routes are bound.</p>
</td>
<td class="cellrowborder" valign="top" width="32.67%" headers="mcps1.1.5.1.3 "><p id="a275b76de64cc482784c6d7fa855a8652"><a name="a275b76de64cc482784c6d7fa855a8652"></a><a name="a275b76de64cc482784c6d7fa855a8652"></a><a href="js-hwmap.md">HWMap</a></p>
</td>
<td class="cellrowborder" valign="top" width="19.33%" headers="mcps1.1.5.1.4 "><p id="ae0b85742bb63450bb9e30dc7b7e528df"><a name="ae0b85742bb63450bb9e30dc7b7e528df"></a><a name="ae0b85742bb63450bb9e30dc7b7e528df"></a>-</p>
</td>
</tr>
<tr id="rba135a2225224a8fa314600ca6bff1cb"><td class="cellrowborder" valign="top" width="24%" headers="mcps1.1.5.1.1 "><p id="a2399cdecd18f486390770fce78f8ff79"><a name="a2399cdecd18f486390770fce78f8ff79"></a><a name="a2399cdecd18f486390770fce78f8ff79"></a>getMap()</p>
</td>
<td class="cellrowborder" valign="top" width="24%" headers="mcps1.1.5.1.2 "><p id="ac04fb1f2afd94e1ab513f87ce9d1b1f7"><a name="ac04fb1f2afd94e1ab513f87ce9d1b1f7"></a><a name="ac04fb1f2afd94e1ab513f87ce9d1b1f7"></a>Obtains the map instance to which the planned routes are bound.</p>
</td>
<td class="cellrowborder" valign="top" width="32.67%" headers="mcps1.1.5.1.3 "><p id="afa06a9bcd09b4460bacf305946932b75"><a name="afa06a9bcd09b4460bacf305946932b75"></a><a name="afa06a9bcd09b4460bacf305946932b75"></a>-</p>
</td>
<td class="cellrowborder" valign="top" width="19.33%" headers="mcps1.1.5.1.4 "><p id="a5d0a7405f0ab4078a1703c9f0f59eeb6"><a name="a5d0a7405f0ab4078a1703c9f0f59eeb6"></a><a name="a5d0a7405f0ab4078a1703c9f0f59eeb6"></a><a href="js-hwmap.md">HWMap</a></p>
</td>
</tr>
<tr id="rfadc474f6c184dd391308b1c75cf9f87"><td class="cellrowborder" valign="top" width="24%" headers="mcps1.1.5.1.1 "><p id="a8da6a73e3c114924ad68cf989f74d530"><a name="a8da6a73e3c114924ad68cf989f74d530"></a><a name="a8da6a73e3c114924ad68cf989f74d530"></a>setOptions(options)</p>
</td>
<td class="cellrowborder" valign="top" width="24%" headers="mcps1.1.5.1.2 "><p id="a5adee56a11854544a0c1ffe651285d5c"><a name="a5adee56a11854544a0c1ffe651285d5c"></a><a name="a5adee56a11854544a0c1ffe651285d5c"></a>Sets the route style.</p>
</td>
<td class="cellrowborder" valign="top" width="32.67%" headers="mcps1.1.5.1.3 "><p id="aa66fbf61314247e193219e32ebd8ae96"><a name="aa66fbf61314247e193219e32ebd8ae96"></a><a name="aa66fbf61314247e193219e32ebd8ae96"></a><a href="#s2fd0eef94f7d406dba7e693745e954f0">RendererOptions</a></p>
</td>
<td class="cellrowborder" valign="top" width="19.33%" headers="mcps1.1.5.1.4 "><p id="a2b98619a40d74896a31185c78949e0a4"><a name="a2b98619a40d74896a31185c78949e0a4"></a><a name="a2b98619a40d74896a31185c78949e0a4"></a>-</p>
</td>
</tr>
<tr id="r6914328efb9e414aaf5cb96578609900"><td class="cellrowborder" valign="top" width="24%" headers="mcps1.1.5.1.1 "><p id="a08c1211a475141718b4597cdd524dbc7"><a name="a08c1211a475141718b4597cdd524dbc7"></a><a name="a08c1211a475141718b4597cdd524dbc7"></a>getOptions()</p>
</td>
<td class="cellrowborder" valign="top" width="24%" headers="mcps1.1.5.1.2 "><p id="a1b5724f0812d4d74ac03e1f974369f0b"><a name="a1b5724f0812d4d74ac03e1f974369f0b"></a><a name="a1b5724f0812d4d74ac03e1f974369f0b"></a>Obtains the route style.</p>
</td>
<td class="cellrowborder" valign="top" width="32.67%" headers="mcps1.1.5.1.3 "><p id="a515d45b1c2ba457c82c9bd4d95f898f1"><a name="a515d45b1c2ba457c82c9bd4d95f898f1"></a><a name="a515d45b1c2ba457c82c9bd4d95f898f1"></a>-</p>
</td>
<td class="cellrowborder" valign="top" width="19.33%" headers="mcps1.1.5.1.4 "><p id="a97497c2ecaf54e6d9cd2d0340c51270e"><a name="a97497c2ecaf54e6d9cd2d0340c51270e"></a><a name="a97497c2ecaf54e6d9cd2d0340c51270e"></a><a href="#s2fd0eef94f7d406dba7e693745e954f0">RendererOptions</a></p>
</td>
</tr>
<tr id="r2fc12b01c8e34dcaa9d2bb475db94116"><td class="cellrowborder" valign="top" width="24%" headers="mcps1.1.5.1.1 "><p id="abeee08b2d63f4cb38118692cbd45b326"><a name="abeee08b2d63f4cb38118692cbd45b326"></a><a name="abeee08b2d63f4cb38118692cbd45b326"></a>setDirections(directionsResult,options)</p>
</td>
<td class="cellrowborder" valign="top" width="24%" headers="mcps1.1.5.1.2 "><p id="abc980e939c894491a43b4e82b5879899"><a name="abc980e939c894491a43b4e82b5879899"></a><a name="abc980e939c894491a43b4e82b5879899"></a>Displays the routes based on data returned by the route planning API. The <strong id="b49871025115817"><a name="b49871025115817"></a><a name="b49871025115817"></a>options</strong> parameter is optional. </p>
</td>
<td class="cellrowborder" valign="top" width="32.67%" headers="mcps1.1.5.1.3 "><a name="u77ecb5740e4342298e69a0eb33aa840f"></a><a name="u77ecb5740e4342298e69a0eb33aa840f"></a><ul id="u77ecb5740e4342298e69a0eb33aa840f"><li><strong id="b20248411601"><a name="b20248411601"></a><a name="b20248411601"></a>directionsResult</strong>: <a href="js-hwdirectionsservice.md#s5136fc4b19984160b25e2cf8d90bf122">DirectionsResult</a>, which is the route planning result.</li><li><strong id="b37861521707"><a name="b37861521707"></a><a name="b37861521707"></a>options</strong>: <a href="#s2fd0eef94f7d406dba7e693745e954f0">RendererOptions</a>, which indicates the route rendering style.</li></ul>
</td>
<td class="cellrowborder" valign="top" width="19.33%" headers="mcps1.1.5.1.4 "><p id="a3fb57769291745ab9414a6a3a4adfbd1"><a name="a3fb57769291745ab9414a6a3a4adfbd1"></a><a name="a3fb57769291745ab9414a6a3a4adfbd1"></a>Array&lt;<a href="js-hwpolyline.md">HWPolyline</a>&gt;</p>
</td>
</tr>
</tbody>
</table>

## RendererOptions<a name="s2fd0eef94f7d406dba7e693745e954f0"></a>

<a name="t3a329061b1df494cbfaea2d20b75637a"></a>
<table><thead align="left"><tr id="raa2bc585fc2d435eb85340ac7ce04ba7"><th class="cellrowborder" valign="top" width="16%" id="mcps1.1.5.1.1"><p id="a18bcf818bdc84bee9938f6a480da52c0"><a name="a18bcf818bdc84bee9938f6a480da52c0"></a><a name="a18bcf818bdc84bee9938f6a480da52c0"></a><strong id="aede26268cd2e45a2853bb09955caa7f3"><a name="aede26268cd2e45a2853bb09955caa7f3"></a><a name="aede26268cd2e45a2853bb09955caa7f3"></a>Parameter</strong></p>
</th>
<th class="cellrowborder" valign="top" width="14.000000000000002%" id="mcps1.1.5.1.2"><p id="a7a310ddf421a4b2499e6bda5522d7414"><a name="a7a310ddf421a4b2499e6bda5522d7414"></a><a name="a7a310ddf421a4b2499e6bda5522d7414"></a><strong id="a2b0df885dbbd4a12ba70493875ca5efa"><a name="a2b0df885dbbd4a12ba70493875ca5efa"></a><a name="a2b0df885dbbd4a12ba70493875ca5efa"></a>Mandatory/Optional</strong></p>
</th>
<th class="cellrowborder" valign="top" width="16%" id="mcps1.1.5.1.3"><p id="a3c0a56ff6f824bf1a2a190fcd25967b2"><a name="a3c0a56ff6f824bf1a2a190fcd25967b2"></a><a name="a3c0a56ff6f824bf1a2a190fcd25967b2"></a><strong id="b15416114919589"><a name="b15416114919589"></a><a name="b15416114919589"></a>Type</strong></p>
</th>
<th class="cellrowborder" valign="top" width="54%" id="mcps1.1.5.1.4"><p id="a6a3d5fd547dd4e21bb72d955816b83af"><a name="a6a3d5fd547dd4e21bb72d955816b83af"></a><a name="a6a3d5fd547dd4e21bb72d955816b83af"></a><strong id="b1258011511586"><a name="b1258011511586"></a><a name="b1258011511586"></a>Description</strong></p>
</th>
</tr>
</thead>
<tbody><tr id="r029d8ee190054211a84df57dc68497b8"><td class="cellrowborder" valign="top" width="16%" headers="mcps1.1.5.1.1 "><p id="acbac403c5a4b439c92e161a7b21bb516"><a name="acbac403c5a4b439c92e161a7b21bb516"></a><a name="acbac403c5a4b439c92e161a7b21bb516"></a>strokeColor</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="a7c6d9bb4cc3046068429de35f8a0ae86"><a name="a7c6d9bb4cc3046068429de35f8a0ae86"></a><a name="a7c6d9bb4cc3046068429de35f8a0ae86"></a>Optional</p>
</td>
<td class="cellrowborder" valign="top" width="16%" headers="mcps1.1.5.1.3 "><p id="a504e896d1f4d493db756c87ab9d29807"><a name="a504e896d1f4d493db756c87ab9d29807"></a><a name="a504e896d1f4d493db756c87ab9d29807"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="54%" headers="mcps1.1.5.1.4 "><p id="a9fab62c35894432b831b9818db2b0b69"><a name="a9fab62c35894432b831b9818db2b0b69"></a><a name="a9fab62c35894432b831b9818db2b0b69"></a>Stroke color and transparency of a route. The default color is black. </p>
<p id="adef6ba77d39547589ca79d1a35c8d6a4"><a name="adef6ba77d39547589ca79d1a35c8d6a4"></a><a name="adef6ba77d39547589ca79d1a35c8d6a4"></a>The color can be set in the following ways:</p>
<a name="ub2b5c5b1a41b4dd1874bc1037781edde"></a><a name="ub2b5c5b1a41b4dd1874bc1037781edde"></a><ul id="ub2b5c5b1a41b4dd1874bc1037781edde"><li>Color name: green</li><li>Hexadecimal value: #ff0000</li><li>RGB: rgb(0,0,0)</li><li>RGBA: rgba(0,0,0,0.5)</li><li>HSL: hsl(120,65%,75%)</li></ul>
</td>
</tr>
<tr id="r2952c8f1107d4aa7b28536f6ecaec71d"><td class="cellrowborder" valign="top" width="16%" headers="mcps1.1.5.1.1 "><p id="ad9c3f17b82734a16b034291d80f8d538"><a name="ad9c3f17b82734a16b034291d80f8d538"></a><a name="ad9c3f17b82734a16b034291d80f8d538"></a>strokeWeight</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="a5303862c066647bab3a1ff5f21030361"><a name="a5303862c066647bab3a1ff5f21030361"></a><a name="a5303862c066647bab3a1ff5f21030361"></a>Optional</p>
</td>
<td class="cellrowborder" valign="top" width="16%" headers="mcps1.1.5.1.3 "><p id="ad5de249adacd4d39ae749e033354dad1"><a name="ad5de249adacd4d39ae749e033354dad1"></a><a name="ad5de249adacd4d39ae749e033354dad1"></a>Number</p>
</td>
<td class="cellrowborder" valign="top" width="54%" headers="mcps1.1.5.1.4 "><p id="a5c3aef08cb4341f5b9b97aff7304c74f"><a name="a5c3aef08cb4341f5b9b97aff7304c74f"></a><a name="a5c3aef08cb4341f5b9b97aff7304c74f"></a>Route stroke width, in pixels. The default value is <strong id="b84158216116"><a name="b84158216116"></a><a name="b84158216116"></a>1</strong>.</p>
</td>
</tr>
<tr id="r652378d39d624b279efa87a89956f069"><td class="cellrowborder" valign="top" width="16%" headers="mcps1.1.5.1.1 "><p id="ad54c1967db2446309b004e5ccab2d911"><a name="ad54c1967db2446309b004e5ccab2d911"></a><a name="ad54c1967db2446309b004e5ccab2d911"></a>visible</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="ad003a5b033fc433a9813a678c9687515"><a name="ad003a5b033fc433a9813a678c9687515"></a><a name="ad003a5b033fc433a9813a678c9687515"></a>Optional</p>
</td>
<td class="cellrowborder" valign="top" width="16%" headers="mcps1.1.5.1.3 "><p id="a12627c485e9a4c6aadae0cfb46b78de4"><a name="a12627c485e9a4c6aadae0cfb46b78de4"></a><a name="a12627c485e9a4c6aadae0cfb46b78de4"></a>Boolean</p>
</td>
<td class="cellrowborder" valign="top" width="54%" headers="mcps1.1.5.1.4 "><p id="acd85cc34680a4df39c239d8ba507f9c0"><a name="acd85cc34680a4df39c239d8ba507f9c0"></a><a name="acd85cc34680a4df39c239d8ba507f9c0"></a>Indicates whether the route is visible. The options include <strong id="b11740202914592"><a name="b11740202914592"></a><a name="b11740202914592"></a>true</strong> (yes) and <strong id="b17741429105919"><a name="b17741429105919"></a><a name="b17741429105919"></a>false</strong> (no). The default value is <strong id="b19743229115912"><a name="b19743229115912"></a><a name="b19743229115912"></a>true</strong>.</p>
</td>
</tr>
<tr id="rdb24cad51d7d44e6a04483ac8d26289b"><td class="cellrowborder" valign="top" width="16%" headers="mcps1.1.5.1.1 "><p id="a1aa10f1bdfd848dd8d01ef88c036942a"><a name="a1aa10f1bdfd848dd8d01ef88c036942a"></a><a name="a1aa10f1bdfd848dd8d01ef88c036942a"></a>zIndex</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="a4fe02d49b613408aadb67a664a6388bb"><a name="a4fe02d49b613408aadb67a664a6388bb"></a><a name="a4fe02d49b613408aadb67a664a6388bb"></a>Optional</p>
</td>
<td class="cellrowborder" valign="top" width="16%" headers="mcps1.1.5.1.3 "><p id="a54a95db6d30145e699e4932d24ad5ca0"><a name="a54a95db6d30145e699e4932d24ad5ca0"></a><a name="a54a95db6d30145e699e4932d24ad5ca0"></a>Number</p>
</td>
<td class="cellrowborder" valign="top" width="54%" headers="mcps1.1.5.1.4 "><p id="a08aa0b1b22f94c4f861f0f519e2026ec"><a name="a08aa0b1b22f94c4f861f0f519e2026ec"></a><a name="a08aa0b1b22f94c4f861f0f519e2026ec"></a>Z-index of a <a href="js-hwpolyline.md">HWPolyline</a> object.</p>
</td>
</tr>
</tbody>
</table>

