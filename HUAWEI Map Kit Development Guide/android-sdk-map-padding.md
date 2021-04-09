# Map Padding<a name="EN-US_TOPIC_0000001099003580"></a>

Map Kit is implemented by simulating a camera. The map camera area centers on the target location and will be padded. Map controls \(such as the compass, zoom icons, and my-location icon\) are placed at the border of the map camera area. By default, the compass is placed in the upper right corner of the map camera area, and the zoom icons and my-location icon are placed in the lower right corner of the map camera area.

You can use the  [HuaweiMap.setPadding](en-us_topic_0000001098683684.md#section10782142412914)**\(int left, int top, int right, int bottom\)**  method to set the padding between the map camera area bounds and map controls. Input parameters of the method are as follows:

-   **left**: incremental distance from the map controls to the left edge of the map, in pixels.
-   **top**: incremental distance from the map controls to the top edge of the map, in pixels.
-   **right**: incremental distance from the map controls to the right edge of the map, in pixels.
-   **bottom**: incremental distance from the map controls to the bottom edge of the map, in pixels.

[Figure 1](#fig18561531114719)  and  [Figure 2](#fig8557135134813)  show the default and custom map padding effects, respectively.

<a name="table1549111816117"></a>
<table><tbody><tr id="row164911781018"><td class="row-nocellborder" style="border:none" valign="top" width="50%"><div class="fignone" id="fig18561531114719"><a name="fig18561531114719"></a><a name="fig18561531114719"></a><span class="figcap"><b>Figure 1 </b>Default padding effect</span><br><a name="image165633124710"></a><a name="image165633124710"></a><span><img id="image165633124710" src="figures/default-padding-effect.jpg" width="332.5" height="392.89849200000003"></span></div>
</td>
<td class="cellrowborder" style="border:none" valign="top" width="50%"><div class="fignone" id="fig8557135134813"><a name="fig8557135134813"></a><a name="fig8557135134813"></a><span class="figcap"><b>Figure 2 </b>Custom padding effect</span><br><a name="image18557435114812"></a><a name="image18557435114812"></a><span><img id="image18557435114812" src="figures/custom-padding-effect.jpg" width="332.5" height="392.89849200000003"></span></div>
</td>
</tr>
</tbody>
</table>

