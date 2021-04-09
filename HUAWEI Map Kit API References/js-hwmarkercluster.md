# HWMarkerCluster<a name="EN-US_TOPIC_0000001145860959"></a>

-   [Overview](#saffbc72739344d038610562032168656)
-   [Build Method](#s46a2f8013c4f4894a3885fc58c999d00)
-   [Public Methods](#scd2287c7674e42f0b510bd4652cc6dbc)
-   [MarkerClusterOptions](#sa9b7e975e868409fbafe25dec6e603ae)

## Overview<a name="saffbc72739344d038610562032168656"></a>

Clusters the specified marker sets on a map and sets the clustering distance and images to be displayed after clustering. 

## Build Method<a name="s46a2f8013c4f4894a3885fc58c999d00"></a>

<a name="tb1accdb43bc74edfb819353fad0bb5da"></a>
<table><thead align="left"><tr id="r996880471aef43e48d4db12106fb761c"><th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.1"><p id="aeb5271b5aad24f5bb23c7f5bd0b85d4b"><a name="aeb5271b5aad24f5bb23c7f5bd0b85d4b"></a><a name="aeb5271b5aad24f5bb23c7f5bd0b85d4b"></a><strong id="a0f5766932d424278a8f9acea61706d13"><a name="a0f5766932d424278a8f9acea61706d13"></a><a name="a0f5766932d424278a8f9acea61706d13"></a>Build Method</strong></p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.2"><p id="a1e35b71f53de4fad9dbd896b16b57625"><a name="a1e35b71f53de4fad9dbd896b16b57625"></a><a name="a1e35b71f53de4fad9dbd896b16b57625"></a><strong id="b676151343014"><a name="b676151343014"></a><a name="b676151343014"></a>Description</strong></p>
</th>
</tr>
</thead>
<tbody><tr id="r50637fb644c34b27ae23f8f5ca1f085f"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="abc8614897a904fa6a99bac96588c9fd9"><a name="abc8614897a904fa6a99bac96588c9fd9"></a><a name="abc8614897a904fa6a99bac96588c9fd9"></a>HWMapJsSDK.HWMarkerCluster(map, markers, options)</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><a name="u18e3d387b3434f2b8d44e566e6beeee2"></a><a name="u18e3d387b3434f2b8d44e566e6beeee2"></a><ul id="u18e3d387b3434f2b8d44e566e6beeee2"><li><strong id="b15149231153011"><a name="b15149231153011"></a><a name="b15149231153011"></a>map</strong>: map layer to be added. This parameter is mandatory.</li><li><strong id="b728017883117"><a name="b728017883117"></a><a name="b728017883117"></a>markers</strong>: a set of <a href="js-hwmarker.md">HWMarker</a> objects to be clustered. This parameter is mandatory. </li><li><strong id="b141695439312"><a name="b141695439312"></a><a name="b141695439312"></a>options</strong>: attributes of <a href="js-hwmarkercluster.md">HWMarkerCluster</a>. This parameter is optional. For details, please refer to <a href="#sa9b7e975e868409fbafe25dec6e603ae">MarkerClusterOptions</a>.</li></ul>
</td>
</tr>
</tbody>
</table>

## Public Methods<a name="scd2287c7674e42f0b510bd4652cc6dbc"></a>

<a name="tc92456bc91174d20b431199980ebb872"></a>
<table><thead align="left"><tr id="r468d66c42b0343f58fd97cef9a551a47"><th class="cellrowborder" valign="top" width="33%" id="mcps1.1.5.1.1"><p id="a074585f3ed6b4d25a7651db84e034bc9"><a name="a074585f3ed6b4d25a7651db84e034bc9"></a><a name="a074585f3ed6b4d25a7651db84e034bc9"></a><strong id="b169371835133218"><a name="b169371835133218"></a><a name="b169371835133218"></a>Method</strong></p>
</th>
<th class="cellrowborder" valign="top" width="26%" id="mcps1.1.5.1.2"><p id="ab666ba8497184a8b974eeb2c82ddac6c"><a name="ab666ba8497184a8b974eeb2c82ddac6c"></a><a name="ab666ba8497184a8b974eeb2c82ddac6c"></a><strong id="b496813753213"><a name="b496813753213"></a><a name="b496813753213"></a>Description</strong></p>
</th>
<th class="cellrowborder" valign="top" width="26.08%" id="mcps1.1.5.1.3"><p id="aa415d5bdbd4f48d18b015a0d9058ab03"><a name="aa415d5bdbd4f48d18b015a0d9058ab03"></a><a name="aa415d5bdbd4f48d18b015a0d9058ab03"></a><strong id="ab58958a5299b453ba980fbf19fa38508"><a name="ab58958a5299b453ba980fbf19fa38508"></a><a name="ab58958a5299b453ba980fbf19fa38508"></a>Type</strong></p>
</th>
<th class="cellrowborder" valign="top" width="14.92%" id="mcps1.1.5.1.4"><p id="a4d25ea9e43704aceb1b5729938f7ae49"><a name="a4d25ea9e43704aceb1b5729938f7ae49"></a><a name="a4d25ea9e43704aceb1b5729938f7ae49"></a><strong id="a5ffaf4d97ec64510b79979ef6004bffa"><a name="a5ffaf4d97ec64510b79979ef6004bffa"></a><a name="a5ffaf4d97ec64510b79979ef6004bffa"></a>Return Value</strong></p>
</th>
</tr>
</thead>
<tbody><tr id="r99bdb64f367a470087be9948cc7f9ab3"><td class="cellrowborder" valign="top" width="33%" headers="mcps1.1.5.1.1 "><p id="a56e61da523bb45f3af0efa76e90134e5"><a name="a56e61da523bb45f3af0efa76e90134e5"></a><a name="a56e61da523bb45f3af0efa76e90134e5"></a>addMarker(marker)</p>
</td>
<td class="cellrowborder" valign="top" width="26%" headers="mcps1.1.5.1.2 "><p id="a54fbca867d45402c9cff9f9597db9375"><a name="a54fbca867d45402c9cff9f9597db9375"></a><a name="a54fbca867d45402c9cff9f9597db9375"></a>Adds a <a href="js-hwmarker.md">HWMarker</a> object.</p>
</td>
<td class="cellrowborder" valign="top" width="26.08%" headers="mcps1.1.5.1.3 "><p id="a332d71a046d44084be1d17d19aff393e"><a name="a332d71a046d44084be1d17d19aff393e"></a><a name="a332d71a046d44084be1d17d19aff393e"></a><a href="js-hwmarker.md">HWMarker</a></p>
</td>
<td class="cellrowborder" valign="top" width="14.92%" headers="mcps1.1.5.1.4 "><p id="a91518013664b4dda99b78d87ff215f3d"><a name="a91518013664b4dda99b78d87ff215f3d"></a><a name="a91518013664b4dda99b78d87ff215f3d"></a>-</p>
</td>
</tr>
<tr id="rabe5e67e72974b1cb7d83380ddab6ec1"><td class="cellrowborder" valign="top" width="33%" headers="mcps1.1.5.1.1 "><p id="ae5503120fc4c49eaa08072fb77206795"><a name="ae5503120fc4c49eaa08072fb77206795"></a><a name="ae5503120fc4c49eaa08072fb77206795"></a>addMarkers(markers)</p>
</td>
<td class="cellrowborder" valign="top" width="26%" headers="mcps1.1.5.1.2 "><p id="a2211e56decf2421291bdc08858c28f3b"><a name="a2211e56decf2421291bdc08858c28f3b"></a><a name="a2211e56decf2421291bdc08858c28f3b"></a>Adds a set of <a href="js-hwmarker.md">HWMarker</a> objects.</p>
</td>
<td class="cellrowborder" valign="top" width="26.08%" headers="mcps1.1.5.1.3 "><p id="a6430998d1c814cbaaaacc311fb4b3f38"><a name="a6430998d1c814cbaaaacc311fb4b3f38"></a><a name="a6430998d1c814cbaaaacc311fb4b3f38"></a>Array&lt;<a href="js-hwmarker.md">HWMarker</a>&gt;</p>
</td>
<td class="cellrowborder" valign="top" width="14.92%" headers="mcps1.1.5.1.4 "><p id="a4255bd523b6449128ef0d8ef26e4052e"><a name="a4255bd523b6449128ef0d8ef26e4052e"></a><a name="a4255bd523b6449128ef0d8ef26e4052e"></a>-</p>
</td>
</tr>
<tr id="ra53ffa985092435984c2534c800f96ba"><td class="cellrowborder" valign="top" width="33%" headers="mcps1.1.5.1.1 "><p id="ae7fb0f1305dd42fabd64b5c83f38a610"><a name="ae7fb0f1305dd42fabd64b5c83f38a610"></a><a name="ae7fb0f1305dd42fabd64b5c83f38a610"></a>removeMarker(marker)</p>
</td>
<td class="cellrowborder" valign="top" width="26%" headers="mcps1.1.5.1.2 "><p id="a267d27b53f1d413e85ae23ff2301508a"><a name="a267d27b53f1d413e85ae23ff2301508a"></a><a name="a267d27b53f1d413e85ae23ff2301508a"></a>Deletes a <a href="js-hwmarker.md">HWMarker</a> object.</p>
</td>
<td class="cellrowborder" valign="top" width="26.08%" headers="mcps1.1.5.1.3 "><p id="ad075887c18394c4f87e0acd507343f3d"><a name="ad075887c18394c4f87e0acd507343f3d"></a><a name="ad075887c18394c4f87e0acd507343f3d"></a><a href="js-hwmarker.md">HWMarker</a></p>
</td>
<td class="cellrowborder" valign="top" width="14.92%" headers="mcps1.1.5.1.4 "><p id="a0d1ea23976cc4bab988c61ee38686947"><a name="a0d1ea23976cc4bab988c61ee38686947"></a><a name="a0d1ea23976cc4bab988c61ee38686947"></a>-</p>
</td>
</tr>
<tr id="r44fc9cea33db47f88a8ead3d223050a4"><td class="cellrowborder" valign="top" width="33%" headers="mcps1.1.5.1.1 "><p id="a0241d45716cf470a89e54123dde596b2"><a name="a0241d45716cf470a89e54123dde596b2"></a><a name="a0241d45716cf470a89e54123dde596b2"></a>removeMarkers(markers)</p>
</td>
<td class="cellrowborder" valign="top" width="26%" headers="mcps1.1.5.1.2 "><p id="ae9cf29b6eb3e4f8c8f80b0a6d207fd71"><a name="ae9cf29b6eb3e4f8c8f80b0a6d207fd71"></a><a name="ae9cf29b6eb3e4f8c8f80b0a6d207fd71"></a>Deletes a set of <a href="js-hwmarker.md">HWMarker</a> objects.</p>
</td>
<td class="cellrowborder" valign="top" width="26.08%" headers="mcps1.1.5.1.3 "><p id="a683ae8900e4240c5a66f02002ff97296"><a name="a683ae8900e4240c5a66f02002ff97296"></a><a name="a683ae8900e4240c5a66f02002ff97296"></a>Array&lt;<a href="js-hwmarker.md">HWMarker</a>&gt;</p>
</td>
<td class="cellrowborder" valign="top" width="14.92%" headers="mcps1.1.5.1.4 "><p id="ab0fd3d6af329471d974cce17fd052659"><a name="ab0fd3d6af329471d974cce17fd052659"></a><a name="ab0fd3d6af329471d974cce17fd052659"></a>-</p>
</td>
</tr>
<tr id="r9cbddbc4b2c9412e8890fd3e618c1e1f"><td class="cellrowborder" valign="top" width="33%" headers="mcps1.1.5.1.1 "><p id="abc1d1fd37c3845bcb4b77c8670ed4721"><a name="abc1d1fd37c3845bcb4b77c8670ed4721"></a><a name="abc1d1fd37c3845bcb4b77c8670ed4721"></a>clearMarkers()</p>
</td>
<td class="cellrowborder" valign="top" width="26%" headers="mcps1.1.5.1.2 "><p id="a30a15d3a4f234a24be2396c9de73f058"><a name="a30a15d3a4f234a24be2396c9de73f058"></a><a name="a30a15d3a4f234a24be2396c9de73f058"></a>Clears all <a href="js-hwmarker.md">HWMarker</a> objects.</p>
</td>
<td class="cellrowborder" valign="top" width="26.08%" headers="mcps1.1.5.1.3 "><p id="acb47e97553c346cd819afc18802202d2"><a name="acb47e97553c346cd819afc18802202d2"></a><a name="acb47e97553c346cd819afc18802202d2"></a>-</p>
</td>
<td class="cellrowborder" valign="top" width="14.92%" headers="mcps1.1.5.1.4 "><p id="a8e60f789ab944c6192d63844087442cf"><a name="a8e60f789ab944c6192d63844087442cf"></a><a name="a8e60f789ab944c6192d63844087442cf"></a>-</p>
</td>
</tr>
<tr id="r26a730b8c5454d768236538bf34be52f"><td class="cellrowborder" valign="top" width="33%" headers="mcps1.1.5.1.1 "><p id="a18ed377c42c14786b1a2216dd5b35c21"><a name="a18ed377c42c14786b1a2216dd5b35c21"></a><a name="a18ed377c42c14786b1a2216dd5b35c21"></a>getMarkers()</p>
</td>
<td class="cellrowborder" valign="top" width="26%" headers="mcps1.1.5.1.2 "><p id="a81014f306f634e4d9d7aec12af528983"><a name="a81014f306f634e4d9d7aec12af528983"></a><a name="a81014f306f634e4d9d7aec12af528983"></a>Obtains all <a href="js-hwmarker.md">HWMarker</a> objects.</p>
</td>
<td class="cellrowborder" valign="top" width="26.08%" headers="mcps1.1.5.1.3 "><p id="aa8fdc7c676df4762a95a33dfd79d0323"><a name="aa8fdc7c676df4762a95a33dfd79d0323"></a><a name="aa8fdc7c676df4762a95a33dfd79d0323"></a>-</p>
</td>
<td class="cellrowborder" valign="top" width="14.92%" headers="mcps1.1.5.1.4 "><p id="abb0709045c594f8d828e0142d3757282"><a name="abb0709045c594f8d828e0142d3757282"></a><a name="abb0709045c594f8d828e0142d3757282"></a>Array&lt;<a href="js-hwmarker.md">HWMarker</a>&gt;</p>
</td>
</tr>
</tbody>
</table>

## MarkerClusterOptions<a name="sa9b7e975e868409fbafe25dec6e603ae"></a>

<a name="t170c7f0e5ae742ecb5f67fba878f3b5a"></a>
<table><thead align="left"><tr id="rd6345bee6871444b9e709f444f80ece6"><th class="cellrowborder" valign="top" width="18.86%" id="mcps1.1.5.1.1"><p id="ace1cb5cdeecc4423a5c9a7ed10d4d8ed"><a name="ace1cb5cdeecc4423a5c9a7ed10d4d8ed"></a><a name="ace1cb5cdeecc4423a5c9a7ed10d4d8ed"></a><strong id="afadf05fa61d94637a189f62cafa0d8a8"><a name="afadf05fa61d94637a189f62cafa0d8a8"></a><a name="afadf05fa61d94637a189f62cafa0d8a8"></a>Parameter</strong></p>
</th>
<th class="cellrowborder" valign="top" width="14.000000000000002%" id="mcps1.1.5.1.2"><p id="a1897c571b91f47f69099db3228a0fe7f"><a name="a1897c571b91f47f69099db3228a0fe7f"></a><a name="a1897c571b91f47f69099db3228a0fe7f"></a><strong id="a8bd793c7906b4bc7b346c9a733d70c00"><a name="a8bd793c7906b4bc7b346c9a733d70c00"></a><a name="a8bd793c7906b4bc7b346c9a733d70c00"></a>Mandatory/Optional</strong></p>
</th>
<th class="cellrowborder" valign="top" width="21.54%" id="mcps1.1.5.1.3"><p id="a76cddce80061491f89c640298508e73c"><a name="a76cddce80061491f89c640298508e73c"></a><a name="a76cddce80061491f89c640298508e73c"></a><strong id="a9987e00a0a93419f9fd37d81da22342c"><a name="a9987e00a0a93419f9fd37d81da22342c"></a><a name="a9987e00a0a93419f9fd37d81da22342c"></a>Type</strong></p>
</th>
<th class="cellrowborder" valign="top" width="45.6%" id="mcps1.1.5.1.4"><p id="a94fe65a0a4654ab4b5042324d88408ae"><a name="a94fe65a0a4654ab4b5042324d88408ae"></a><a name="a94fe65a0a4654ab4b5042324d88408ae"></a><strong id="b1417004320338"><a name="b1417004320338"></a><a name="b1417004320338"></a>Description</strong></p>
</th>
</tr>
</thead>
<tbody><tr id="r64d37cd9b8134cba886cbeb6cdb42ceb"><td class="cellrowborder" valign="top" width="18.86%" headers="mcps1.1.5.1.1 "><p id="a95c22b26f96c48ffa4350b9b260cb81b"><a name="a95c22b26f96c48ffa4350b9b260cb81b"></a><a name="a95c22b26f96c48ffa4350b9b260cb81b"></a>options.icon</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="a77773a12ae414ddfb122ed4d194697f3"><a name="a77773a12ae414ddfb122ed4d194697f3"></a><a name="a77773a12ae414ddfb122ed4d194697f3"></a>Optional</p>
</td>
<td class="cellrowborder" valign="top" width="21.54%" headers="mcps1.1.5.1.3 "><p id="ab6477798c34f4b9d95364931866f95d9"><a name="ab6477798c34f4b9d95364931866f95d9"></a><a name="ab6477798c34f4b9d95364931866f95d9"></a>String | <a href="js-hwmarker.md#sfbc5428e87a44deb9010cc2f3a589894">MarkerIconOption</a></p>
</td>
<td class="cellrowborder" valign="top" width="45.6%" headers="mcps1.1.5.1.4 "><p id="a5d7e95042d2744ce8b7ceb73a540022e"><a name="a5d7e95042d2744ce8b7ceb73a540022e"></a><a name="a5d7e95042d2744ce8b7ceb73a540022e"></a>Icon displayed after <a href="js-hwmarker.md">HWMarker</a> clustering. Set this parameter in the same way as adding a <a href="js-hwmarker.md">HWMarker</a> object.</p>
</td>
</tr>
<tr id="r31a34b512e4f48acb8db2b43cf914752"><td class="cellrowborder" valign="top" width="18.86%" headers="mcps1.1.5.1.1 "><p id="a1cdf5415f23440feb76392e2435228cc"><a name="a1cdf5415f23440feb76392e2435228cc"></a><a name="a1cdf5415f23440feb76392e2435228cc"></a>options.label</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="abe8360901f88468b80e954e8f3c8f3a6"><a name="abe8360901f88468b80e954e8f3c8f3a6"></a><a name="abe8360901f88468b80e954e8f3c8f3a6"></a>Optional</p>
</td>
<td class="cellrowborder" valign="top" width="21.54%" headers="mcps1.1.5.1.3 "><p id="a250fb239f81443fe90e128d1b887c488"><a name="a250fb239f81443fe90e128d1b887c488"></a><a name="a250fb239f81443fe90e128d1b887c488"></a>String | <a href="js-hwmarker.md#sddf63bee876d44188dec2b7ccdfcaeb8">MarkerLabelOption</a></p>
</td>
<td class="cellrowborder" valign="top" width="45.6%" headers="mcps1.1.5.1.4 "><p id="a5426c447d9034e269f04a87276b0913f"><a name="a5426c447d9034e269f04a87276b0913f"></a><a name="a5426c447d9034e269f04a87276b0913f"></a>Label displayed after <a href="js-hwmarker.md">HWMarker</a> clustering. The default value is the total number of labels after clustering. Set this parameter in the same way as adding a <a href="js-hwmarker.md">HWMarker</a> object.</p>
</td>
</tr>
</tbody>
</table>

