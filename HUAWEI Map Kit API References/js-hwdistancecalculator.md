# HWDistanceCalculator<a name="EN-US_TOPIC_0000001099341122"></a>

-   [Overview](#section194833517270)
-   [Build Method](#section59204122287)
-   [Public Methods](#section12524111762818)

## Overview<a name="section194833517270"></a>

Calculates the linear distance between two points based on their longitudes and latitudes. 

## Build Method<a name="section59204122287"></a>

<a name="table392918596288"></a>
<table><thead align="left"><tr id="row1292995915281"><th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.1"><p id="p1392925918289"><a name="p1392925918289"></a><a name="p1392925918289"></a>Build Method</p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.2"><p id="p39295591284"><a name="p39295591284"></a><a name="p39295591284"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row13929659162819"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p1992945913282"><a name="p1992945913282"></a><a name="p1992945913282"></a>HWMapJsSDK.HWDistanceCalculator()</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p18929359102815"><a name="p18929359102815"></a><a name="p18929359102815"></a>-</p>
</td>
</tr>
</tbody>
</table>

## Public Methods<a name="section12524111762818"></a>

<a name="td769085cfe7a439c9852880f3782d9e3"></a>
<table><thead align="left"><tr id="re161b98a303d443a8b6a9e7d90869b40"><th class="cellrowborder" valign="top" width="26.43%" id="mcps1.1.5.1.1"><p id="ada01bd2bf8d14b5b969c5dd4b826924a"><a name="ada01bd2bf8d14b5b969c5dd4b826924a"></a><a name="ada01bd2bf8d14b5b969c5dd4b826924a"></a><strong id="b16642121016123"><a name="b16642121016123"></a><a name="b16642121016123"></a>Method</strong></p>
</th>
<th class="cellrowborder" valign="top" width="21.57%" id="mcps1.1.5.1.2"><p id="aeaa685ad5c0c4e4397e8c5b5dfef2e24"><a name="aeaa685ad5c0c4e4397e8c5b5dfef2e24"></a><a name="aeaa685ad5c0c4e4397e8c5b5dfef2e24"></a><strong id="b92913141125"><a name="b92913141125"></a><a name="b92913141125"></a>Description</strong></p>
</th>
<th class="cellrowborder" valign="top" width="32.67%" id="mcps1.1.5.1.3"><p id="ac1c0df988fcc4282afa5ff6a0784691c"><a name="ac1c0df988fcc4282afa5ff6a0784691c"></a><a name="ac1c0df988fcc4282afa5ff6a0784691c"></a><strong id="b1276391415128"><a name="b1276391415128"></a><a name="b1276391415128"></a>Type</strong></p>
</th>
<th class="cellrowborder" valign="top" width="19.33%" id="mcps1.1.5.1.4"><p id="a02e1b78043d4413f869b25af519f3923"><a name="a02e1b78043d4413f869b25af519f3923"></a><a name="a02e1b78043d4413f869b25af519f3923"></a><strong id="b055115169127"><a name="b055115169127"></a><a name="b055115169127"></a>Return Value</strong></p>
</th>
</tr>
</thead>
<tbody><tr id="rc22087a853c24effafaea354d439774a"><td class="cellrowborder" valign="top" width="26.43%" headers="mcps1.1.5.1.1 "><p id="p188301112123010"><a name="p188301112123010"></a><a name="p188301112123010"></a>computeDistanceBetween(fromPostion, toPosition, opt_radius)</p>
</td>
<td class="cellrowborder" valign="top" width="21.57%" headers="mcps1.1.5.1.2 "><p id="p382981263019"><a name="p382981263019"></a><a name="p382981263019"></a>Calculates the linear distance between two points.</p>
</td>
<td class="cellrowborder" valign="top" width="32.67%" headers="mcps1.1.5.1.3 "><a name="ul4554133683110"></a><a name="ul4554133683110"></a><ul id="ul4554133683110"><li><strong id="b92791176131"><a name="b92791176131"></a><a name="b92791176131"></a>fromPostion</strong>: <a href="js-params.md#s1f33822192a04bbe9bd9de86a17460b1">LatLng</a> object that contains the longitude and latitude of the start point.</li><li><strong id="b1143913720131"><a name="b1143913720131"></a><a name="b1143913720131"></a>toPosition</strong>: <a href="js-params.md#s1f33822192a04bbe9bd9de86a17460b1">LatLng</a> object that contains the longitude and latitude of the end point.</li><li><strong id="b21231638141"><a name="b21231638141"></a><a name="b21231638141"></a>opt_radius</strong>: sphere radius, in meters. The value is a number. This parameter is optional and the default value is <strong id="b13636162313156"><a name="b13636162313156"></a><a name="b13636162313156"></a>6378137.0</strong>.</li></ul>
</td>
<td class="cellrowborder" valign="top" width="19.33%" headers="mcps1.1.5.1.4 "><p id="p10826191218305"><a name="p10826191218305"></a><a name="p10826191218305"></a>Linear distance between two points, in meters.</p>
</td>
</tr>
</tbody>
</table>

