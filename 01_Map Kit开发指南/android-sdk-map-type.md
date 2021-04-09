# 地图类型<a name="ZH-CN_TOPIC_0000001099181262"></a>

[HuaweiMap](zh-cn_topic_0000001145941019.md)目前支持两种地图类型：

-   MAP\_TYPE\_NORMAL：标准地图。展示道路，建筑物以及河流等重要的自然特征。
-   MAP\_TYPE\_NONE：没有加载任何数据的空地图。

要设置地图的类型，请调用[HuaweiMap](zh-cn_topic_0000001145941019.md)对象的[setMapType](zh-cn_topic_0000001145941019.md#section3746134811217)方法，并传递[HuaweiMap](zh-cn_topic_0000001145941019.md)中定义的静态常量。设置地图方法及地图显示效果如下：

-   设置空地图类型：调用[HuaweiMap](zh-cn_topic_0000001145941019.md)对象的[setMapType](zh-cn_topic_0000001145941019.md#section3746134811217)\(HuaweiMap.MAP\_TYPE\_NONE\)，显示效果如[图1](#fig13171704408)。
-   设置标准地图类型：调用[HuaweiMap](zh-cn_topic_0000001145941019.md)对象的[setMapType](zh-cn_topic_0000001145941019.md#section3746134811217)\(HuaweiMap.MAP\_TYPE\_NORMAL\)，显示效果如[图2](#fig15549151810415)。

<a name="table1149534385719"></a>
<table><tbody><tr id="row9495184319574"><td class="row-nocellborder" style="border:none" valign="top" width="50%"><div class="fignone" id="fig13171704408"><a name="fig13171704408"></a><a name="fig13171704408"></a><span class="figcap"><b>图1 </b>空地图类型</span><br><a name="image61700144019"></a><a name="image61700144019"></a><span><img id="image61700144019" src="figures/空地图类型.jpg" height="394.566711" width="332.5"></span></div>
</td>
<td class="cellrowborder" style="border:none" valign="top" width="50%"><div class="fignone" id="fig15549151810415"><a name="fig15549151810415"></a><a name="fig15549151810415"></a><span class="figcap"><b>图2 </b>标准地图类型</span><br><a name="image1855012187412"></a><a name="image1855012187412"></a><span><img id="image1855012187412" src="figures/标准地图类型.jpg" height="392.1950550000001" width="331.66875000000005"></span></div>
</td>
</tr>
</tbody>
</table>

