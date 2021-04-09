# Map Type<a name="EN-US_TOPIC_0000001145723503"></a>

Currently,  [HuaweiMap](en-us_topic_0000001098683684.md)  supports two types of maps:

-   **MAP\_TYPE\_NORMAL**: standard map, which shows roads, artificial structures, and natural features such as rivers.
-   **MAP\_TYPE\_NONE**: empty map without any data.

To set the map type, call the  [setMapType](en-us_topic_0000001098683684.md#section3746134811217)  method of the  [HuaweiMap](en-us_topic_0000001098683684.md)  object and pass one of the static constants defined in  [HuaweiMap](en-us_topic_0000001098683684.md). In detail:

-   To set an empty map, call the  [setMapType](en-us_topic_0000001098683684.md#section3746134811217)**\(HuaweiMap.MAP\_TYPE\_NONE\)**  method of the  [HuaweiMap](en-us_topic_0000001098683684.md)  object.  [Figure 1](#fig13171704408)  shows the map display effect. 
-   To set a standard map, call the  [setMapType](en-us_topic_0000001098683684.md#section3746134811217)**\(HuaweiMap.MAP\_TYPE\_NORMAL\)**  method of the  [HuaweiMap](en-us_topic_0000001098683684.md)  object.  [Figure 2](#fig15549151810415)  shows the map display effect.

<a name="table1149534385719"></a>
<table><tbody><tr id="row9495184319574"><td class="row-nocellborder" style="border:none" valign="top" width="50%"><div class="fignone" id="fig13171704408"><a name="fig13171704408"></a><a name="fig13171704408"></a><span class="figcap"><b>Figure 1 </b>Empty map</span><br><a name="image61700144019"></a><a name="image61700144019"></a><span><img id="image61700144019" src="figures/empty-map.jpg" height="394.566711" width="332.5"></span></div>
</td>
<td class="cellrowborder" style="border:none" valign="top" width="50%"><div class="fignone" id="fig15549151810415"><a name="fig15549151810415"></a><a name="fig15549151810415"></a><span class="figcap"><b>Figure 2 </b>Standard map</span><br><a name="image1855012187412"></a><a name="image1855012187412"></a><span><img id="image1855012187412" src="figures/standard-map.jpg" height="392.1950550000001" width="331.66875000000005"></span></div>
</td>
</tr>
</tbody>
</table>

