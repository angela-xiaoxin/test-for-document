# HuaweiMap.OnPoiClickListener<a name="ZH-CN_TOPIC_0000001145541059"></a>

-   [Public Method Summary](#section6395728173310)
-   [Public Methods](#section14615648155312)
-   [onPoiClick](#section12145175895317)


<a name="table4516mcpsimp"></a>
<table><thead align="left"><tr id="row4520mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p4522mcpsimp"><a name="p4522mcpsimp"></a><a name="p4522mcpsimp"></a>Interface Info</p>
</th>
</tr>
</thead>
<tbody><tr id="row4523mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p14288173414246"><a name="p14288173414246"></a><a name="p14288173414246"></a>public interface HuaweiMap.OnPoiClickListener</p>
<p id="p4525mcpsimp"><a name="p4525mcpsimp"></a><a name="p4525mcpsimp"></a>是<a href="huaweimap.md">HuaweiMap</a>类的一个内部接口，表示POI点击事件的侦听器，包含一个抽象函数<a href="#section12145175895317">onPoiClick</a>(<a href="pointofinterest.md">PointOfInterest</a>)。</p>
</td>
</tr>
</tbody>
</table>

## Public Method Summary<a name="section6395728173310"></a>

<a name="table4531mcpsimp"></a>
<table><thead align="left"><tr id="row4536mcpsimp"><th class="cellrowborder" valign="top" width="40%" id="mcps1.1.3.1.1"><p id="p4538mcpsimp"><a name="p4538mcpsimp"></a><a name="p4538mcpsimp"></a>Qualifier and Type</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.1.3.1.2"><p id="p4540mcpsimp"><a name="p4540mcpsimp"></a><a name="p4540mcpsimp"></a>Method Name and Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row4541mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p4543mcpsimp"><a name="p4543mcpsimp"></a><a name="p4543mcpsimp"></a>abstract void</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p4545mcpsimp"><a name="p4545mcpsimp"></a><a name="p4545mcpsimp"></a><a href="#section12145175895317">onPoiClick</a>(<a href="pointofinterest.md">PointOfInterest</a> poi)</p>
<p id="p9876111563610"><a name="p9876111563610"></a><a name="p9876111563610"></a>点击POI时的回调方法。</p>
</td>
</tr>
</tbody>
</table>

## Public Methods<a name="section14615648155312"></a>

## onPoiClick<a name="section12145175895317"></a>

<a name="table4548mcpsimp"></a>
<table><thead align="left"><tr id="row4552mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p4554mcpsimp"><a name="p4554mcpsimp"></a><a name="p4554mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row4555mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p4557mcpsimp"><a name="p4557mcpsimp"></a><a name="p4557mcpsimp"></a>public abstract void onPoiClick(<a href="pointofinterest.md">PointOfInterest</a> poi)</p>
<p id="p1175541116542"><a name="p1175541116542"></a><a name="p1175541116542"></a>点击POI时的回调方法。必须在主线程中执行。</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table4563mcpsimp"></a>
<table><thead align="left"><tr id="row4568mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p4570mcpsimp"><a name="p4570mcpsimp"></a><a name="p4570mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p4572mcpsimp"><a name="p4572mcpsimp"></a><a name="p4572mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row4573mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p4575mcpsimp"><a name="p4575mcpsimp"></a><a name="p4575mcpsimp"></a>poi</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p4577mcpsimp"><a name="p4577mcpsimp"></a><a name="p4577mcpsimp"></a>被点击的POI对象。</p>
</td>
</tr>
</tbody>
</table>

