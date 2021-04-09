# 样式参考<a name="ZH-CN_TOPIC_0000001145541099"></a>

自定义地图样式JSON文件通过下列4个元素来定义地图样式：

-   mapFeature：地图要素
-   options：元素选项
    -   geometry.fill：几何填充
    -   geometry.stroke：几何边框
    -   geometry.icon：几何图标
    -   labels.text.fill：文本填充
    -   labels.text.stroke：文本

-   paint：绘制属性
    -   color：颜色，16进制颜色，例如“\#FFFF00”
    -   icon-type：图标类型，目前支持night/simple

-   visibility：可见属性，默认为可见
    -   true：可见
    -   false：不可见


下表将向您展示支持修改的地图元素。

<a name="table7173038124620"></a>
<table><thead align="left"><tr id="row191291551217"><th class="cellrowborder" colspan="2" valign="top" id="mcps1.1.9.1.1"><p id="p1191561611210"><a name="p1191561611210"></a><a name="p1191561611210"></a>元素代码 / Feature type</p>
</th>
<th class="cellrowborder" valign="top" id="mcps1.1.9.1.2"><p id="p81291252218"><a name="p81291252218"></a><a name="p81291252218"></a>地图元素 / Element  type</p>
</th>
<th class="cellrowborder" valign="top" id="mcps1.1.9.1.3"><p id="p5129115126"><a name="p5129115126"></a><a name="p5129115126"></a>几何填充颜色 / Geometry.fill.color</p>
</th>
<th class="cellrowborder" valign="top" id="mcps1.1.9.1.4"><p id="p812935922"><a name="p812935922"></a><a name="p812935922"></a>几何边框颜色 / Geometry.stroke.color</p>
</th>
<th class="cellrowborder" valign="top" id="mcps1.1.9.1.5"><p id="p668810291598"><a name="p668810291598"></a><a name="p668810291598"></a>文本填充颜色 / Labels.text.fill.color</p>
</th>
<th class="cellrowborder" valign="top" id="mcps1.1.9.1.6"><p id="p161301553212"><a name="p161301553212"></a><a name="p161301553212"></a>文本颜色 / 	Labels.text.stroke.color</p>
</th>
<th class="cellrowborder" valign="top" id="mcps1.1.9.1.7"><p id="p1013045226"><a name="p1013045226"></a><a name="p1013045226"></a>图标类型 /	Geometry.icon.icon-type</p>
</th>
</tr>
</thead>
<tbody><tr id="row37131328142417"><td class="cellrowborder" valign="top" width="12.68126812681268%" headers="mcps1.1.9.1.1 "><p id="p13168630122412"><a name="p13168630122412"></a><a name="p13168630122412"></a>all</p>
</td>
<td class="cellrowborder" valign="top" width="14.07140714071407%" headers="mcps1.1.9.1.1 "><p id="p20168103011245"><a name="p20168103011245"></a><a name="p20168103011245"></a>-</p>
</td>
<td class="cellrowborder" valign="top" width="18.371837183718373%" headers="mcps1.1.9.1.2 "><p id="p2865112244"><a name="p2865112244"></a><a name="p2865112244"></a>全部</p>
</td>
<td class="cellrowborder" valign="top" width="14.671467146714672%" headers="mcps1.1.9.1.3 "><p id="p163543556254"><a name="p163543556254"></a><a name="p163543556254"></a>-</p>
</td>
<td class="cellrowborder" valign="top" width="8.440844084408441%" headers="mcps1.1.9.1.4 "><p id="p1786735816255"><a name="p1786735816255"></a><a name="p1786735816255"></a>-</p>
</td>
<td class="cellrowborder" valign="top" width="9.750975097509752%" headers="mcps1.1.9.1.5 "><p id="p1876145810257"><a name="p1876145810257"></a><a name="p1876145810257"></a>-</p>
</td>
<td class="cellrowborder" valign="top" width="9.72097209720972%" headers="mcps1.1.9.1.6 "><p id="p1488495862512"><a name="p1488495862512"></a><a name="p1488495862512"></a>-</p>
</td>
<td class="cellrowborder" valign="top" width="12.291229122912291%" headers="mcps1.1.9.1.7 "><p id="p4169133013246"><a name="p4169133013246"></a><a name="p4169133013246"></a><a name="image0148144818209"></a><a name="image0148144818209"></a><span><img id="image0148144818209" src="figures/right.png" width="18.945584" height="15.949626000000002"></span></p>
</td>
</tr>
<tr id="row1956943834613"><td class="cellrowborder" rowspan="6" valign="top" width="12.68126812681268%" headers="mcps1.1.9.1.1 "><p id="p125691038104619"><a name="p125691038104619"></a><a name="p125691038104619"></a>administrative</p>
</td>
<td class="cellrowborder" valign="top" width="14.07140714071407%" headers="mcps1.1.9.1.1 "><p id="p14569103864612"><a name="p14569103864612"></a><a name="p14569103864612"></a>country</p>
</td>
<td class="cellrowborder" valign="top" width="18.371837183718373%" headers="mcps1.1.9.1.2 "><p id="p13569938144615"><a name="p13569938144615"></a><a name="p13569938144615"></a>国家</p>
</td>
<td class="cellrowborder" valign="top" width="14.671467146714672%" headers="mcps1.1.9.1.3 "><p id="p1637316553253"><a name="p1637316553253"></a><a name="p1637316553253"></a>-</p>
</td>
<td class="cellrowborder" valign="top" width="8.440844084408441%" headers="mcps1.1.9.1.4 "><p id="p10386185818203"><a name="p10386185818203"></a><a name="p10386185818203"></a><a name="image4386125816205"></a><a name="image4386125816205"></a><span><img id="image4386125816205" src="figures/right-228.png" width="18.945584" height="15.949626000000002"></span></p>
</td>
<td class="cellrowborder" valign="top" width="9.750975097509752%" headers="mcps1.1.9.1.5 "><p id="p9548659152010"><a name="p9548659152010"></a><a name="p9548659152010"></a><a name="image205481359122014"></a><a name="image205481359122014"></a><span><img id="image205481359122014" src="figures/right-229.png" width="18.945584" height="15.949626000000002"></span></p>
</td>
<td class="cellrowborder" valign="top" width="9.72097209720972%" headers="mcps1.1.9.1.6 "><p id="p392930192111"><a name="p392930192111"></a><a name="p392930192111"></a><a name="image16929180112110"></a><a name="image16929180112110"></a><span><img id="image16929180112110" src="figures/right-230.png" width="18.945584" height="15.949626000000002"></span></p>
</td>
<td class="cellrowborder" valign="top" width="12.291229122912291%" headers="mcps1.1.9.1.7 "><p id="p168623822611"><a name="p168623822611"></a><a name="p168623822611"></a>-</p>
</td>
</tr>
<tr id="row165705380461"><td class="cellrowborder" valign="top" headers="mcps1.1.9.1.1 "><p id="p11570838134619"><a name="p11570838134619"></a><a name="p11570838134619"></a>province</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.1 "><p id="p1457017387468"><a name="p1457017387468"></a><a name="p1457017387468"></a>省</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.2 "><p id="p11396175562519"><a name="p11396175562519"></a><a name="p11396175562519"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.3 "><p id="p155812122110"><a name="p155812122110"></a><a name="p155812122110"></a><a name="image12558182152111"></a><a name="image12558182152111"></a><span><img id="image12558182152111" src="figures/right-231.png" width="18.945584" height="15.949626000000002"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.4 "><p id="p167465362112"><a name="p167465362112"></a><a name="p167465362112"></a><a name="image17460352115"></a><a name="image17460352115"></a><span><img id="image17460352115" src="figures/right-232.png" width="18.945584" height="15.949626000000002"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.5 "><p id="p1313810516213"><a name="p1313810516213"></a><a name="p1313810516213"></a><a name="image131386514216"></a><a name="image131386514216"></a><span><img id="image131386514216" src="figures/right-233.png" width="18.945584" height="15.949626000000002"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.6 "><p id="p168715811261"><a name="p168715811261"></a><a name="p168715811261"></a>-</p>
</td>
</tr>
<tr id="row157023819468"><td class="cellrowborder" valign="top" headers="mcps1.1.9.1.1 "><p id="p057043874611"><a name="p057043874611"></a><a name="p057043874611"></a>capital</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.1 "><p id="p1357033874615"><a name="p1357033874615"></a><a name="p1357033874615"></a>首都</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.2 "><p id="p12406105552517"><a name="p12406105552517"></a><a name="p12406105552517"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.3 "><p id="p1428112122614"><a name="p1428112122614"></a><a name="p1428112122614"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.4 "><p id="p13383564218"><a name="p13383564218"></a><a name="p13383564218"></a><a name="image123831061214"></a><a name="image123831061214"></a><span><img id="image123831061214" src="figures/right-234.png" width="18.945584" height="15.949626000000002"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.5 "><p id="p472197142111"><a name="p472197142111"></a><a name="p472197142111"></a><a name="image16721117182115"></a><a name="image16721117182115"></a><span><img id="image16721117182115" src="figures/right-235.png" width="18.945584" height="15.949626000000002"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.6 "><p id="p688088172619"><a name="p688088172619"></a><a name="p688088172619"></a>-</p>
</td>
</tr>
<tr id="row1957193820463"><td class="cellrowborder" valign="top" headers="mcps1.1.9.1.1 "><p id="p1357119383467"><a name="p1357119383467"></a><a name="p1357119383467"></a>major-city</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.1 "><p id="p1957116383465"><a name="p1957116383465"></a><a name="p1957116383465"></a>1~4级城市</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.2 "><p id="p84171655112513"><a name="p84171655112513"></a><a name="p84171655112513"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.3 "><p id="p15437122172615"><a name="p15437122172615"></a><a name="p15437122172615"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.4 "><p id="p392798142116"><a name="p392798142116"></a><a name="p392798142116"></a><a name="image292788122110"></a><a name="image292788122110"></a><span><img id="image292788122110" src="figures/right-236.png" width="18.945584" height="15.949626000000002"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.5 "><p id="p040561115219"><a name="p040561115219"></a><a name="p040561115219"></a><a name="image840519112218"></a><a name="image840519112218"></a><span><img id="image840519112218" src="figures/right-237.png" width="18.945584" height="15.949626000000002"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.6 "><p id="p1888816882619"><a name="p1888816882619"></a><a name="p1888816882619"></a>-</p>
</td>
</tr>
<tr id="row857115383465"><td class="cellrowborder" valign="top" headers="mcps1.1.9.1.1 "><p id="p857111387468"><a name="p857111387468"></a><a name="p857111387468"></a>district</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.1 "><p id="p957123813465"><a name="p957123813465"></a><a name="p957123813465"></a>区\县</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.2 "><p id="p1430255162519"><a name="p1430255162519"></a><a name="p1430255162519"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.3 "><p id="p194462212265"><a name="p194462212265"></a><a name="p194462212265"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.4 "><p id="p1034151311219"><a name="p1034151311219"></a><a name="p1034151311219"></a><a name="image534112138215"></a><a name="image534112138215"></a><span><img id="image534112138215" src="figures/right-238.png" width="18.945584" height="15.949626000000002"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.5 "><p id="p166981815202111"><a name="p166981815202111"></a><a name="p166981815202111"></a><a name="image136983158218"></a><a name="image136983158218"></a><span><img id="image136983158218" src="figures/right-239.png" width="18.945584" height="15.949626000000002"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.6 "><p id="p38971785267"><a name="p38971785267"></a><a name="p38971785267"></a>-</p>
</td>
</tr>
<tr id="row105721938184617"><td class="cellrowborder" valign="top" headers="mcps1.1.9.1.1 "><p id="p957219381463"><a name="p957219381463"></a><a name="p957219381463"></a>locality</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.1 "><p id="p557223816460"><a name="p557223816460"></a><a name="p557223816460"></a>乡村、城镇</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.2 "><p id="p16441115512519"><a name="p16441115512519"></a><a name="p16441115512519"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.3 "><p id="p7455825264"><a name="p7455825264"></a><a name="p7455825264"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.4 "><p id="p16248417152113"><a name="p16248417152113"></a><a name="p16248417152113"></a><a name="image13248617102111"></a><a name="image13248617102111"></a><span><img id="image13248617102111" src="figures/right-240.png" width="18.945584" height="15.949626000000002"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.5 "><p id="p7554111822116"><a name="p7554111822116"></a><a name="p7554111822116"></a><a name="image20554918102119"></a><a name="image20554918102119"></a><span><img id="image20554918102119" src="figures/right-241.png" width="18.945584" height="15.949626000000002"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.6 "><p id="p1190578172617"><a name="p1190578172617"></a><a name="p1190578172617"></a>-</p>
</td>
</tr>
<tr id="row185721138194610"><td class="cellrowborder" rowspan="8" valign="top" width="12.68126812681268%" headers="mcps1.1.9.1.1 "><p id="p157283816465"><a name="p157283816465"></a><a name="p157283816465"></a>landcover</p>
</td>
<td class="cellrowborder" valign="top" width="14.07140714071407%" headers="mcps1.1.9.1.1 "><p id="p557233815463"><a name="p557233815463"></a><a name="p557233815463"></a>natural</p>
</td>
<td class="cellrowborder" valign="top" width="18.371837183718373%" headers="mcps1.1.9.1.2 "><p id="p5572103884620"><a name="p5572103884620"></a><a name="p5572103884620"></a>陆地、岛屿、海滩、冰川等</p>
</td>
<td class="cellrowborder" valign="top" width="14.671467146714672%" headers="mcps1.1.9.1.3 "><p id="p73091723122119"><a name="p73091723122119"></a><a name="p73091723122119"></a><a name="image330942392120"></a><a name="image330942392120"></a><span><img id="image330942392120" src="figures/right-242.png" width="18.945584" height="15.949626000000002"></span></p>
</td>
<td class="cellrowborder" valign="top" width="8.440844084408441%" headers="mcps1.1.9.1.4 "><p id="p144631325266"><a name="p144631325266"></a><a name="p144631325266"></a>-</p>
</td>
<td class="cellrowborder" valign="top" width="9.750975097509752%" headers="mcps1.1.9.1.5 "><p id="p188411019112120"><a name="p188411019112120"></a><a name="p188411019112120"></a><a name="image11841191902119"></a><a name="image11841191902119"></a><span><img id="image11841191902119" src="figures/right-243.png" width="18.945584" height="15.949626000000002"></span></p>
</td>
<td class="cellrowborder" valign="top" width="9.72097209720972%" headers="mcps1.1.9.1.6 "><p id="p3751215214"><a name="p3751215214"></a><a name="p3751215214"></a><a name="image177582192116"></a><a name="image177582192116"></a><span><img id="image177582192116" src="figures/right-244.png" width="18.945584" height="15.949626000000002"></span></p>
</td>
<td class="cellrowborder" valign="top" width="12.291229122912291%" headers="mcps1.1.9.1.7 "><p id="p4913285265"><a name="p4913285265"></a><a name="p4913285265"></a>-</p>
</td>
</tr>
<tr id="row957383814467"><td class="cellrowborder" rowspan="2" valign="top" headers="mcps1.1.9.1.1 "><p id="p13573113834617"><a name="p13573113834617"></a><a name="p13573113834617"></a>human-made</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.1 "><p id="p257315389461"><a name="p257315389461"></a><a name="p257315389461"></a>聚集区、小区、工业区、监狱地面等</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.2 "><p id="p1852632482113"><a name="p1852632482113"></a><a name="p1852632482113"></a><a name="image18527324202111"></a><a name="image18527324202111"></a><span><img id="image18527324202111" src="figures/right-245.png" width="18.945584" height="15.949626000000002"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.3 "><p id="p11491866263"><a name="p11491866263"></a><a name="p11491866263"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.4 "><p id="p25001960264"><a name="p25001960264"></a><a name="p25001960264"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.5 "><p id="p2050913616265"><a name="p2050913616265"></a><a name="p2050913616265"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.6 "><p id="p135178662617"><a name="p135178662617"></a><a name="p135178662617"></a>-</p>
</td>
</tr>
<tr id="row1573163814467"><td class="cellrowborder" valign="top" headers="mcps1.1.9.1.1 "><p id="p185731638174619"><a name="p185731638174619"></a><a name="p185731638174619"></a>building   建筑物</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.1 "><p id="p105861725132120"><a name="p105861725132120"></a><a name="p105861725132120"></a><a name="image45861525162120"></a><a name="image45861525162120"></a><span><img id="image45861525162120" src="figures/right-246.png" width="18.945584" height="15.949626000000002"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.2 "><p id="p12431313264"><a name="p12431313264"></a><a name="p12431313264"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.3 "><p id="p104313130264"><a name="p104313130264"></a><a name="p104313130264"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.4 "><p id="p1647132261"><a name="p1647132261"></a><a name="p1647132261"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.5 "><p id="p1776161302620"><a name="p1776161302620"></a><a name="p1776161302620"></a>-</p>
</td>
</tr>
<tr id="row1357417387465"><td class="cellrowborder" valign="top" headers="mcps1.1.9.1.1 "><p id="p1257410381466"><a name="p1257410381466"></a><a name="p1257410381466"></a>parkland</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.1 "><p id="p7574038194617"><a name="p7574038194617"></a><a name="p7574038194617"></a>森林、公园、荒地、高尔夫球场等</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.2 "><p id="p7470132813218"><a name="p7470132813218"></a><a name="p7470132813218"></a><a name="image1470162813214"></a><a name="image1470162813214"></a><span><img id="image1470162813214" src="figures/right-247.png" width="18.945584" height="15.949626000000002"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.3 "><p id="p142194164265"><a name="p142194164265"></a><a name="p142194164265"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.4 "><p id="p15150193016214"><a name="p15150193016214"></a><a name="p15150193016214"></a><a name="image1415063052115"></a><a name="image1415063052115"></a><span><img id="image1415063052115" src="figures/right-248.png" width="18.945584" height="15.949626000000002"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.5 "><p id="p191657312219"><a name="p191657312219"></a><a name="p191657312219"></a><a name="image16165031182113"></a><a name="image16165031182113"></a><span><img id="image16165031182113" src="figures/right-249.png" width="18.945584" height="15.949626000000002"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.6 "><p id="p1265710185268"><a name="p1265710185268"></a><a name="p1265710185268"></a>-</p>
</td>
</tr>
<tr id="row125741138174613"><td class="cellrowborder" valign="top" headers="mcps1.1.9.1.1 "><p id="p14574138114617"><a name="p14574138114617"></a><a name="p14574138114617"></a>attraction</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.1 "><p id="p165741238144614"><a name="p165741238144614"></a><a name="p165741238144614"></a>游乐场、动植物园等</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.2 "><p id="p325313311213"><a name="p325313311213"></a><a name="p325313311213"></a><a name="image6253143342111"></a><a name="image6253143342111"></a><span><img id="image6253143342111" src="figures/right-250.png" width="18.945584" height="15.949626000000002"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.3 "><p id="p1722811167263"><a name="p1722811167263"></a><a name="p1722811167263"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.4 "><p id="p5786103492114"><a name="p5786103492114"></a><a name="p5786103492114"></a><a name="image1778673414214"></a><a name="image1778673414214"></a><span><img id="image1778673414214" src="figures/right-251.png" width="18.945584" height="15.949626000000002"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.5 "><p id="p15115103692118"><a name="p15115103692118"></a><a name="p15115103692118"></a><a name="image311513617214"></a><a name="image311513617214"></a><span><img id="image311513617214" src="figures/right-252.png" width="18.945584" height="15.949626000000002"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.6 "><p id="p466611882612"><a name="p466611882612"></a><a name="p466611882612"></a>-</p>
</td>
</tr>
<tr id="row145751238104615"><td class="cellrowborder" valign="top" headers="mcps1.1.9.1.1 "><p id="p0575038124617"><a name="p0575038124617"></a><a name="p0575038124617"></a>hospital</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.1 "><p id="p135757388462"><a name="p135757388462"></a><a name="p135757388462"></a>医院</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.2 "><p id="p2080983712215"><a name="p2080983712215"></a><a name="p2080983712215"></a><a name="image138091837152111"></a><a name="image138091837152111"></a><span><img id="image138091837152111" src="figures/right-253.png" width="18.945584" height="15.949626000000002"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.3 "><p id="p1923601602616"><a name="p1923601602616"></a><a name="p1923601602616"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.4 "><p id="p13556639192118"><a name="p13556639192118"></a><a name="p13556639192118"></a><a name="image1955623962116"></a><a name="image1955623962116"></a><span><img id="image1955623962116" src="figures/right-254.png" width="18.945584" height="15.949626000000002"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.5 "><p id="p186718409218"><a name="p186718409218"></a><a name="p186718409218"></a><a name="image367111407219"></a><a name="image367111407219"></a><span><img id="image367111407219" src="figures/right-255.png" width="18.945584" height="15.949626000000002"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.6 "><p id="p16741418162612"><a name="p16741418162612"></a><a name="p16741418162612"></a>-</p>
</td>
</tr>
<tr id="row45756383463"><td class="cellrowborder" valign="top" headers="mcps1.1.9.1.1 "><p id="p14575438184615"><a name="p14575438184615"></a><a name="p14575438184615"></a>college</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.1 "><p id="p4575103814469"><a name="p4575103814469"></a><a name="p4575103814469"></a>学校</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.2 "><p id="p104185427219"><a name="p104185427219"></a><a name="p104185427219"></a><a name="image74187429217"></a><a name="image74187429217"></a><span><img id="image74187429217" src="figures/right-256.png" width="18.945584" height="15.949626000000002"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.3 "><p id="p1324510166260"><a name="p1324510166260"></a><a name="p1324510166260"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.4 "><p id="p178531943122112"><a name="p178531943122112"></a><a name="p178531943122112"></a><a name="image685324311212"></a><a name="image685324311212"></a><span><img id="image685324311212" src="figures/right-257.png" width="18.945584" height="15.949626000000002"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.5 "><p id="p1603124513218"><a name="p1603124513218"></a><a name="p1603124513218"></a><a name="image3603154512114"></a><a name="image3603154512114"></a><span><img id="image3603154512114" src="figures/right-258.png" width="18.945584" height="15.949626000000002"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.6 "><p id="p1668251810267"><a name="p1668251810267"></a><a name="p1668251810267"></a>-</p>
</td>
</tr>
<tr id="row75759382463"><td class="cellrowborder" valign="top" headers="mcps1.1.9.1.1 "><p id="p195754388468"><a name="p195754388468"></a><a name="p195754388468"></a>business</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.1 "><p id="p957633894619"><a name="p957633894619"></a><a name="p957633894619"></a>购物中心、商业区等</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.2 "><p id="p11953164713215"><a name="p11953164713215"></a><a name="p11953164713215"></a><a name="image59531547102116"></a><a name="image59531547102116"></a><span><img id="image59531547102116" src="figures/right-259.png" width="18.945584" height="15.949626000000002"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.3 "><p id="p2254116132616"><a name="p2254116132616"></a><a name="p2254116132616"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.4 "><p id="p470417493213"><a name="p470417493213"></a><a name="p470417493213"></a><a name="image2704144910217"></a><a name="image2704144910217"></a><span><img id="image2704144910217" src="figures/right-260.png" width="18.945584" height="15.949626000000002"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.5 "><p id="p496551192119"><a name="p496551192119"></a><a name="p496551192119"></a><a name="image199675172110"></a><a name="image199675172110"></a><span><img id="image199675172110" src="figures/right-261.png" width="18.945584" height="15.949626000000002"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.6 "><p id="p76905183264"><a name="p76905183264"></a><a name="p76905183264"></a>-</p>
</td>
</tr>
<tr id="row195761838184618"><td class="cellrowborder" rowspan="13" valign="top" width="12.68126812681268%" headers="mcps1.1.9.1.1 "><p id="p135769387462"><a name="p135769387462"></a><a name="p135769387462"></a>poi</p>
</td>
<td class="cellrowborder" valign="top" width="14.07140714071407%" headers="mcps1.1.9.1.1 "><p id="p1257683844620"><a name="p1257683844620"></a><a name="p1257683844620"></a>shopping</p>
</td>
<td class="cellrowborder" valign="top" width="18.371837183718373%" headers="mcps1.1.9.1.2 "><p id="p165768384468"><a name="p165768384468"></a><a name="p165768384468"></a>购物中心、市场等</p>
</td>
<td class="cellrowborder" valign="top" width="14.671467146714672%" headers="mcps1.1.9.1.3 "><p id="p14609172420260"><a name="p14609172420260"></a><a name="p14609172420260"></a>-</p>
</td>
<td class="cellrowborder" valign="top" width="8.440844084408441%" headers="mcps1.1.9.1.4 "><p id="p1462162418267"><a name="p1462162418267"></a><a name="p1462162418267"></a>-</p>
</td>
<td class="cellrowborder" valign="top" width="9.750975097509752%" headers="mcps1.1.9.1.5 "><p id="p10459175213215"><a name="p10459175213215"></a><a name="p10459175213215"></a><a name="image1845945232114"></a><a name="image1845945232114"></a><span><img id="image1845945232114" src="figures/right-262.png" width="18.945584" height="15.949626000000002"></span></p>
</td>
<td class="cellrowborder" valign="top" width="9.72097209720972%" headers="mcps1.1.9.1.6 "><p id="p267919537216"><a name="p267919537216"></a><a name="p267919537216"></a><a name="image1567916530218"></a><a name="image1567916530218"></a><span><img id="image1567916530218" src="figures/right-263.png" width="18.945584" height="15.949626000000002"></span></p>
</td>
<td class="cellrowborder" valign="top" width="12.291229122912291%" headers="mcps1.1.9.1.7 "><p id="p7698191892612"><a name="p7698191892612"></a><a name="p7698191892612"></a>-</p>
</td>
</tr>
<tr id="row4576838134617"><td class="cellrowborder" valign="top" headers="mcps1.1.9.1.1 "><p id="p1257613854615"><a name="p1257613854615"></a><a name="p1257613854615"></a>tourism</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.1 "><p id="p3577138194611"><a name="p3577138194611"></a><a name="p3577138194611"></a>旅游景点、历史遗迹、教堂等</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.2 "><p id="p136329248269"><a name="p136329248269"></a><a name="p136329248269"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.3 "><p id="p8644162412260"><a name="p8644162412260"></a><a name="p8644162412260"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.4 "><p id="p57691355142113"><a name="p57691355142113"></a><a name="p57691355142113"></a><a name="image2076910557212"></a><a name="image2076910557212"></a><span><img id="image2076910557212" src="figures/right-264.png" width="18.945584" height="15.949626000000002"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.5 "><p id="p4375135717214"><a name="p4375135717214"></a><a name="p4375135717214"></a><a name="image143751057172115"></a><a name="image143751057172115"></a><span><img id="image143751057172115" src="figures/right-265.png" width="18.945584" height="15.949626000000002"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.6 "><p id="p17707161818265"><a name="p17707161818265"></a><a name="p17707161818265"></a>-</p>
</td>
</tr>
<tr id="row6577338194610"><td class="cellrowborder" valign="top" headers="mcps1.1.9.1.1 "><p id="p5577153884613"><a name="p5577153884613"></a><a name="p5577153884613"></a>leisure</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.1 "><p id="p8577113816468"><a name="p8577113816468"></a><a name="p8577113816468"></a>休闲娱乐</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.2 "><p id="p19656224152619"><a name="p19656224152619"></a><a name="p19656224152619"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.3 "><p id="p1466813240265"><a name="p1466813240265"></a><a name="p1466813240265"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.4 "><p id="p15762597216"><a name="p15762597216"></a><a name="p15762597216"></a><a name="image1676159172120"></a><a name="image1676159172120"></a><span><img id="image1676159172120" src="figures/right-266.png" width="18.945584" height="15.949626000000002"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.5 "><p id="p218318032214"><a name="p218318032214"></a><a name="p218318032214"></a><a name="image41831502223"></a><a name="image41831502223"></a><span><img id="image41831502223" src="figures/right-267.png" width="18.945584" height="15.949626000000002"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.6 "><p id="p1882145219265"><a name="p1882145219265"></a><a name="p1882145219265"></a>-</p>
</td>
</tr>
<tr id="row115787385468"><td class="cellrowborder" valign="top" headers="mcps1.1.9.1.1 "><p id="p195782038134614"><a name="p195782038134614"></a><a name="p195782038134614"></a>eating&amp;drinking</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.1 "><p id="p55781538114611"><a name="p55781538114611"></a><a name="p55781538114611"></a>饮食快餐</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.2 "><p id="p6679224152619"><a name="p6679224152619"></a><a name="p6679224152619"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.3 "><p id="p3691824172615"><a name="p3691824172615"></a><a name="p3691824172615"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.4 "><p id="p029881172219"><a name="p029881172219"></a><a name="p029881172219"></a><a name="image12981813229"></a><a name="image12981813229"></a><span><img id="image12981813229" src="figures/right-268.png" width="18.945584" height="15.949626000000002"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.5 "><p id="p18487192152210"><a name="p18487192152210"></a><a name="p18487192152210"></a><a name="image1648722132210"></a><a name="image1648722132210"></a><span><img id="image1648722132210" src="figures/right-269.png" width="18.945584" height="15.949626000000002"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.6 "><p id="p198911525269"><a name="p198911525269"></a><a name="p198911525269"></a>-</p>
</td>
</tr>
<tr id="row125792385468"><td class="cellrowborder" valign="top" headers="mcps1.1.9.1.1 "><p id="p3579113814620"><a name="p3579113814620"></a><a name="p3579113814620"></a>beauty</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.1 "><p id="p9579123894617"><a name="p9579123894617"></a><a name="p9579123894617"></a>美容中心</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.2 "><p id="p9703152432615"><a name="p9703152432615"></a><a name="p9703152432615"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.3 "><p id="p271572418261"><a name="p271572418261"></a><a name="p271572418261"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.4 "><p id="p12655143132219"><a name="p12655143132219"></a><a name="p12655143132219"></a><a name="image186552362214"></a><a name="image186552362214"></a><span><img id="image186552362214" src="figures/right-270.png" width="18.945584" height="15.949626000000002"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.5 "><p id="p17817104132219"><a name="p17817104132219"></a><a name="p17817104132219"></a><a name="image118173414225"></a><a name="image118173414225"></a><span><img id="image118173414225" src="figures/right-271.png" width="18.945584" height="15.949626000000002"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.6 "><p id="p10900135218269"><a name="p10900135218269"></a><a name="p10900135218269"></a>-</p>
</td>
</tr>
<tr id="row18580163854620"><td class="cellrowborder" valign="top" headers="mcps1.1.9.1.1 "><p id="p458063824619"><a name="p458063824619"></a><a name="p458063824619"></a>lodging</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.1 "><p id="p13580153894610"><a name="p13580153894610"></a><a name="p13580153894610"></a>酒店、住宿点</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.2 "><p id="p5726172417263"><a name="p5726172417263"></a><a name="p5726172417263"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.3 "><p id="p1873610241268"><a name="p1873610241268"></a><a name="p1873610241268"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.4 "><p id="p31931364222"><a name="p31931364222"></a><a name="p31931364222"></a><a name="image111932610226"></a><a name="image111932610226"></a><span><img id="image111932610226" src="figures/right-272.png" width="18.945584" height="15.949626000000002"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.5 "><p id="p17217147112219"><a name="p17217147112219"></a><a name="p17217147112219"></a><a name="image112171773222"></a><a name="image112171773222"></a><span><img id="image112171773222" src="figures/right-273.png" width="18.945584" height="15.949626000000002"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.6 "><p id="p14908352142616"><a name="p14908352142616"></a><a name="p14908352142616"></a>-</p>
</td>
</tr>
<tr id="row1558116383463"><td class="cellrowborder" valign="top" headers="mcps1.1.9.1.1 "><p id="p18581203864610"><a name="p18581203864610"></a><a name="p18581203864610"></a>health-care</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.1 "><p id="p75811380468"><a name="p75811380468"></a><a name="p75811380468"></a>医院、诊所、药店等</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.2 "><p id="p1174820244266"><a name="p1174820244266"></a><a name="p1174820244266"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.3 "><p id="p13761132412266"><a name="p13761132412266"></a><a name="p13761132412266"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.4 "><p id="p9488118202220"><a name="p9488118202220"></a><a name="p9488118202220"></a><a name="image74891789224"></a><a name="image74891789224"></a><span><img id="image74891789224" src="figures/right-274.png" width="18.945584" height="15.949626000000002"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.5 "><p id="p2059212972211"><a name="p2059212972211"></a><a name="p2059212972211"></a><a name="image185921296229"></a><a name="image185921296229"></a><span><img id="image185921296229" src="figures/right-275.png" width="18.945584" height="15.949626000000002"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.6 "><p id="p49188524264"><a name="p49188524264"></a><a name="p49188524264"></a>-</p>
</td>
</tr>
<tr id="row958115380462"><td class="cellrowborder" valign="top" headers="mcps1.1.9.1.1 "><p id="p1758123820461"><a name="p1758123820461"></a><a name="p1758123820461"></a>public-service</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.1 "><p id="p1058117383467"><a name="p1058117383467"></a><a name="p1058117383467"></a>学校、政府、警察局等</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.2 "><p id="p47725241261"><a name="p47725241261"></a><a name="p47725241261"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.3 "><p id="p1678514247267"><a name="p1678514247267"></a><a name="p1678514247267"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.4 "><p id="p1181811022215"><a name="p1181811022215"></a><a name="p1181811022215"></a><a name="image281817108221"></a><a name="image281817108221"></a><span><img id="image281817108221" src="figures/right-276.png" width="18.945584" height="15.949626000000002"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.5 "><p id="p147851911102218"><a name="p147851911102218"></a><a name="p147851911102218"></a><a name="image678501142217"></a><a name="image678501142217"></a><span><img id="image678501142217" src="figures/right-277.png" width="18.945584" height="15.949626000000002"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.6 "><p id="p192745214267"><a name="p192745214267"></a><a name="p192745214267"></a>-</p>
</td>
</tr>
<tr id="row1758183820462"><td class="cellrowborder" valign="top" headers="mcps1.1.9.1.1 "><p id="p95811438154614"><a name="p95811438154614"></a><a name="p95811438154614"></a>business</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.1 "><p id="p17582538164611"><a name="p17582538164611"></a><a name="p17582538164611"></a>公司、商业楼等</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.2 "><p id="p67972024142615"><a name="p67972024142615"></a><a name="p67972024142615"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.3 "><p id="p12810152422615"><a name="p12810152422615"></a><a name="p12810152422615"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.4 "><p id="p5468101312210"><a name="p5468101312210"></a><a name="p5468101312210"></a><a name="image1646891312224"></a><a name="image1646891312224"></a><span><img id="image1646891312224" src="figures/right-278.png" width="18.945584" height="15.949626000000002"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.5 "><p id="p17446121462214"><a name="p17446121462214"></a><a name="p17446121462214"></a><a name="image44463145223"></a><a name="image44463145223"></a><span><img id="image44463145223" src="figures/right-279.png" width="18.945584" height="15.949626000000002"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.6 "><p id="p0937185242610"><a name="p0937185242610"></a><a name="p0937185242610"></a>-</p>
</td>
</tr>
<tr id="row105828387467"><td class="cellrowborder" valign="top" headers="mcps1.1.9.1.1 "><p id="p15582838184611"><a name="p15582838184611"></a><a name="p15582838184611"></a>automotive</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.1 "><p id="p658243810463"><a name="p658243810463"></a><a name="p658243810463"></a>汽修、充电桩、洗车等</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.2 "><p id="p1982272482617"><a name="p1982272482617"></a><a name="p1982272482617"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.3 "><p id="p98321424112617"><a name="p98321424112617"></a><a name="p98321424112617"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.4 "><p id="p1756571510224"><a name="p1756571510224"></a><a name="p1756571510224"></a><a name="image1856591512215"></a><a name="image1856591512215"></a><span><img id="image1856591512215" src="figures/right-280.png" width="18.945584" height="15.949626000000002"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.5 "><p id="p6583216192211"><a name="p6583216192211"></a><a name="p6583216192211"></a><a name="image158361632218"></a><a name="image158361632218"></a><span><img id="image158361632218" src="figures/right-281.png" width="18.945584" height="15.949626000000002"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.6 "><p id="p9946195272620"><a name="p9946195272620"></a><a name="p9946195272620"></a>-</p>
</td>
</tr>
<tr id="row105821938104613"><td class="cellrowborder" rowspan="2" valign="top" headers="mcps1.1.9.1.1 "><p id="p12582113824610"><a name="p12582113824610"></a><a name="p12582113824610"></a>sports</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.1 "><p id="p145821538124613"><a name="p145821538124613"></a><a name="p145821538124613"></a>outdoor 户外运动、爬山、骑车等</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.2 "><p id="p1884320249260"><a name="p1884320249260"></a><a name="p1884320249260"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.3 "><p id="p9855132432613"><a name="p9855132432613"></a><a name="p9855132432613"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.4 "><p id="p16954111792211"><a name="p16954111792211"></a><a name="p16954111792211"></a><a name="image3954111715224"></a><a name="image3954111715224"></a><span><img id="image3954111715224" src="figures/right-282.png" width="18.945584" height="15.949626000000002"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.5 "><p id="p17978181812224"><a name="p17978181812224"></a><a name="p17978181812224"></a><a name="image1897811892215"></a><a name="image1897811892215"></a><span><img id="image1897811892215" src="figures/right-283.png" width="18.945584" height="15.949626000000002"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.6 "><p id="p6955145242619"><a name="p6955145242619"></a><a name="p6955145242619"></a>-</p>
</td>
</tr>
<tr id="row2583038164615"><td class="cellrowborder" valign="top" headers="mcps1.1.9.1.1 "><p id="p1958314387462"><a name="p1958314387462"></a><a name="p1958314387462"></a>other 保龄球、游泳等</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.1 "><p id="p13864192414267"><a name="p13864192414267"></a><a name="p13864192414267"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.2 "><p id="p58761424142618"><a name="p58761424142618"></a><a name="p58761424142618"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.3 "><p id="p11124224102217"><a name="p11124224102217"></a><a name="p11124224102217"></a><a name="image1612432416224"></a><a name="image1612432416224"></a><span><img id="image1612432416224" src="figures/right-284.png" width="18.945584" height="15.949626000000002"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.4 "><p id="p106991625172216"><a name="p106991625172216"></a><a name="p106991625172216"></a><a name="image17699162582217"></a><a name="image17699162582217"></a><span><img id="image17699162582217" src="figures/right-285.png" width="18.945584" height="15.949626000000002"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.5 "><p id="p1096365282615"><a name="p1096365282615"></a><a name="p1096365282615"></a>-</p>
</td>
</tr>
<tr id="row175831038104614"><td class="cellrowborder" valign="top" headers="mcps1.1.9.1.1 "><p id="p558310388464"><a name="p558310388464"></a><a name="p558310388464"></a>natural</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.1 "><p id="p15831138124619"><a name="p15831138124619"></a><a name="p15831138124619"></a>山峰、森林等</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.2 "><p id="p188711244262"><a name="p188711244262"></a><a name="p188711244262"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.3 "><p id="p4898182422612"><a name="p4898182422612"></a><a name="p4898182422612"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.4 "><p id="p8815142619228"><a name="p8815142619228"></a><a name="p8815142619228"></a><a name="image1981572642215"></a><a name="image1981572642215"></a><span><img id="image1981572642215" src="figures/right-286.png" width="18.945584" height="15.949626000000002"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.5 "><p id="p083512713223"><a name="p083512713223"></a><a name="p083512713223"></a><a name="image1783562715223"></a><a name="image1783562715223"></a><span><img id="image1783562715223" src="figures/right-287.png" width="18.945584" height="15.949626000000002"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.6 "><p id="p59711252182611"><a name="p59711252182611"></a><a name="p59711252182611"></a>-</p>
</td>
</tr>
<tr id="row1058463844617"><td class="cellrowborder" rowspan="7" valign="top" width="12.68126812681268%" headers="mcps1.1.9.1.1 "><p id="p2058403815464"><a name="p2058403815464"></a><a name="p2058403815464"></a>road</p>
</td>
<td class="cellrowborder" rowspan="2" valign="top" width="14.07140714071407%" headers="mcps1.1.9.1.1 "><p id="p458417385467"><a name="p458417385467"></a><a name="p458417385467"></a>highway</p>
</td>
<td class="cellrowborder" valign="top" width="18.371837183718373%" headers="mcps1.1.9.1.2 "><p id="p75841438194612"><a name="p75841438194612"></a><a name="p75841438194612"></a>country 国家高速</p>
</td>
<td class="cellrowborder" valign="top" width="14.671467146714672%" headers="mcps1.1.9.1.3 "><p id="p1994368224"><a name="p1994368224"></a><a name="p1994368224"></a><a name="image0983611226"></a><a name="image0983611226"></a><span><img id="image0983611226" src="figures/right-288.png" width="18.945584" height="15.949626000000002"></span></p>
</td>
<td class="cellrowborder" valign="top" width="8.440844084408441%" headers="mcps1.1.9.1.4 "><p id="p662483710224"><a name="p662483710224"></a><a name="p662483710224"></a><a name="image462473792214"></a><a name="image462473792214"></a><span><img id="image462473792214" src="figures/right-289.png" width="18.945584" height="15.949626000000002"></span></p>
</td>
<td class="cellrowborder" valign="top" width="9.750975097509752%" headers="mcps1.1.9.1.5 "><p id="p213973982217"><a name="p213973982217"></a><a name="p213973982217"></a><a name="image1813943911223"></a><a name="image1813943911223"></a><span><img id="image1813943911223" src="figures/right-290.png" width="18.945584" height="15.949626000000002"></span></p>
</td>
<td class="cellrowborder" valign="top" width="9.72097209720972%" headers="mcps1.1.9.1.6 "><p id="p1547334032219"><a name="p1547334032219"></a><a name="p1547334032219"></a><a name="image14473204062219"></a><a name="image14473204062219"></a><span><img id="image14473204062219" src="figures/right-291.png" width="18.945584" height="15.949626000000002"></span></p>
</td>
<td class="cellrowborder" valign="top" width="12.291229122912291%" headers="mcps1.1.9.1.7 "><p id="p15981155222617"><a name="p15981155222617"></a><a name="p15981155222617"></a>-</p>
</td>
</tr>
<tr id="row10584143814467"><td class="cellrowborder" valign="top" headers="mcps1.1.9.1.1 "><p id="p55841438114613"><a name="p55841438114613"></a><a name="p55841438114613"></a>city 城市高速</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.1 "><p id="p112601156122217"><a name="p112601156122217"></a><a name="p112601156122217"></a><a name="image16260135612229"></a><a name="image16260135612229"></a><span><img id="image16260135612229" src="figures/right-292.png" width="18.945584" height="15.949626000000002"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.2 "><p id="p2260175615222"><a name="p2260175615222"></a><a name="p2260175615222"></a><a name="image226095692212"></a><a name="image226095692212"></a><span><img id="image226095692212" src="figures/right-293.png" width="18.945584" height="15.949626000000002"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.3 "><p id="p142607563229"><a name="p142607563229"></a><a name="p142607563229"></a><a name="image1226015612214"></a><a name="image1226015612214"></a><span><img id="image1226015612214" src="figures/right-294.png" width="18.945584" height="15.949626000000002"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.4 "><p id="p52604564221"><a name="p52604564221"></a><a name="p52604564221"></a><a name="image526013563229"></a><a name="image526013563229"></a><span><img id="image526013563229" src="figures/right-295.png" width="18.945584" height="15.949626000000002"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.5 "><p id="p79891852102612"><a name="p79891852102612"></a><a name="p79891852102612"></a>-</p>
</td>
</tr>
<tr id="row1658543814465"><td class="cellrowborder" valign="top" headers="mcps1.1.9.1.1 "><p id="p15585738164611"><a name="p15585738164611"></a><a name="p15585738164611"></a>national</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.1 "><p id="p75851938184610"><a name="p75851938184610"></a><a name="p75851938184610"></a>国道</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.2 "><p id="p471145714222"><a name="p471145714222"></a><a name="p471145714222"></a><a name="image1371657172213"></a><a name="image1371657172213"></a><span><img id="image1371657172213" src="figures/right-296.png" width="18.945584" height="15.949626000000002"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.3 "><p id="p171115752211"><a name="p171115752211"></a><a name="p171115752211"></a><a name="image4712570229"></a><a name="image4712570229"></a><span><img id="image4712570229" src="figures/right-297.png" width="18.945584" height="15.949626000000002"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.4 "><p id="p12713573227"><a name="p12713573227"></a><a name="p12713573227"></a><a name="image372145718221"></a><a name="image372145718221"></a><span><img id="image372145718221" src="figures/right-298.png" width="18.945584" height="15.949626000000002"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.5 "><p id="p15725573225"><a name="p15725573225"></a><a name="p15725573225"></a><a name="image1772145713225"></a><a name="image1772145713225"></a><span><img id="image1772145713225" src="figures/right-299.png" width="18.945584" height="15.949626000000002"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.6 "><p id="p79986523263"><a name="p79986523263"></a><a name="p79986523263"></a>-</p>
</td>
</tr>
<tr id="row25851938124614"><td class="cellrowborder" valign="top" headers="mcps1.1.9.1.1 "><p id="p2585338184611"><a name="p2585338184611"></a><a name="p2585338184611"></a>province</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.1 "><p id="p185851338194616"><a name="p185851338194616"></a><a name="p185851338194616"></a>省道</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.2 "><p id="p628158192210"><a name="p628158192210"></a><a name="p628158192210"></a><a name="image32805852215"></a><a name="image32805852215"></a><span><img id="image32805852215" src="figures/right-300.png" width="18.945584" height="15.949626000000002"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.3 "><p id="p7281358102219"><a name="p7281358102219"></a><a name="p7281358102219"></a><a name="image72895862211"></a><a name="image72895862211"></a><span><img id="image72895862211" src="figures/right-301.png" width="18.945584" height="15.949626000000002"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.4 "><p id="p1828135814227"><a name="p1828135814227"></a><a name="p1828135814227"></a><a name="image328105815223"></a><a name="image328105815223"></a><span><img id="image328105815223" src="figures/right-302.png" width="18.945584" height="15.949626000000002"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.5 "><p id="p72855820228"><a name="p72855820228"></a><a name="p72855820228"></a><a name="image3283583229"></a><a name="image3283583229"></a><span><img id="image3283583229" src="figures/right-303.png" width="18.945584" height="15.949626000000002"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.6 "><p id="p11618538268"><a name="p11618538268"></a><a name="p11618538268"></a>-</p>
</td>
</tr>
<tr id="row205861038134620"><td class="cellrowborder" valign="top" headers="mcps1.1.9.1.1 "><p id="p158616381466"><a name="p158616381466"></a><a name="p158616381466"></a>city-arterial</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.1 "><p id="p458623874616"><a name="p458623874616"></a><a name="p458623874616"></a>市区内交通要道</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.2 "><p id="p493395802220"><a name="p493395802220"></a><a name="p493395802220"></a><a name="image1393314582221"></a><a name="image1393314582221"></a><span><img id="image1393314582221" src="figures/right-304.png" width="18.945584" height="15.949626000000002"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.3 "><p id="p1933175832219"><a name="p1933175832219"></a><a name="p1933175832219"></a><a name="image39331458102216"></a><a name="image39331458102216"></a><span><img id="image39331458102216" src="figures/right-305.png" width="18.945584" height="15.949626000000002"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.4 "><p id="p169331458172214"><a name="p169331458172214"></a><a name="p169331458172214"></a><a name="image13933458152213"></a><a name="image13933458152213"></a><span><img id="image13933458152213" src="figures/right-306.png" width="18.945584" height="15.949626000000002"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.5 "><p id="p993395862216"><a name="p993395862216"></a><a name="p993395862216"></a><a name="image793312589225"></a><a name="image793312589225"></a><span><img id="image793312589225" src="figures/right-307.png" width="18.945584" height="15.949626000000002"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.6 "><p id="p6141253172618"><a name="p6141253172618"></a><a name="p6141253172618"></a>-</p>
</td>
</tr>
<tr id="row185861938194613"><td class="cellrowborder" valign="top" headers="mcps1.1.9.1.1 "><p id="p16586238164616"><a name="p16586238164616"></a><a name="p16586238164616"></a>minor-road</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.1 "><p id="p1758611385467"><a name="p1758611385467"></a><a name="p1758611385467"></a>市区内支线等</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.2 "><p id="p13998175918225"><a name="p13998175918225"></a><a name="p13998175918225"></a><a name="image29981159112215"></a><a name="image29981159112215"></a><span><img id="image29981159112215" src="figures/right-308.png" width="18.945584" height="15.949626000000002"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.3 "><p id="p89981594229"><a name="p89981594229"></a><a name="p89981594229"></a><a name="image19998959182216"></a><a name="image19998959182216"></a><span><img id="image19998959182216" src="figures/right-309.png" width="18.945584" height="15.949626000000002"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.4 "><p id="p189988592222"><a name="p189988592222"></a><a name="p189988592222"></a><a name="image7998135918229"></a><a name="image7998135918229"></a><span><img id="image7998135918229" src="figures/right-310.png" width="18.945584" height="15.949626000000002"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.5 "><p id="p499835982220"><a name="p499835982220"></a><a name="p499835982220"></a><a name="image17998175902210"></a><a name="image17998175902210"></a><span><img id="image17998175902210" src="figures/right-311.png" width="18.945584" height="15.949626000000002"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.6 "><p id="p3231953132615"><a name="p3231953132615"></a><a name="p3231953132615"></a>-</p>
</td>
</tr>
<tr id="row458703819462"><td class="cellrowborder" valign="top" headers="mcps1.1.9.1.1 "><p id="p19587143817466"><a name="p19587143817466"></a><a name="p19587143817466"></a>sidewalk</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.1 "><p id="p55871738164615"><a name="p55871738164615"></a><a name="p55871738164615"></a>人行道</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.2 "><p id="p18946507233"><a name="p18946507233"></a><a name="p18946507233"></a><a name="image17946150102317"></a><a name="image17946150102317"></a><span><img id="image17946150102317" src="figures/right-312.png" width="18.945584" height="15.949626000000002"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.3 "><p id="p994620011231"><a name="p994620011231"></a><a name="p994620011231"></a><a name="image594690152318"></a><a name="image594690152318"></a><span><img id="image594690152318" src="figures/right-313.png" width="18.945584" height="15.949626000000002"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.4 "><p id="p12946309232"><a name="p12946309232"></a><a name="p12946309232"></a><a name="image59461103236"></a><a name="image59461103236"></a><span><img id="image59461103236" src="figures/right-314.png" width="18.945584" height="15.949626000000002"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.5 "><p id="p189466082310"><a name="p189466082310"></a><a name="p189466082310"></a><a name="image6946705236"></a><a name="image6946705236"></a><span><img id="image6946705236" src="figures/right-315.png" width="18.945584" height="15.949626000000002"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.6 "><p id="p193211531262"><a name="p193211531262"></a><a name="p193211531262"></a>-</p>
</td>
</tr>
<tr id="row958763884615"><td class="cellrowborder" rowspan="7" valign="top" width="12.68126812681268%" headers="mcps1.1.9.1.1 "><p id="p12587538174614"><a name="p12587538174614"></a><a name="p12587538174614"></a>transit</p>
</td>
<td class="cellrowborder" valign="top" width="14.07140714071407%" headers="mcps1.1.9.1.1 "><p id="p558713381465"><a name="p558713381465"></a><a name="p558713381465"></a>railway</p>
</td>
<td class="cellrowborder" valign="top" width="18.371837183718373%" headers="mcps1.1.9.1.2 "><p id="p25871038194618"><a name="p25871038194618"></a><a name="p25871038194618"></a>铁路线、高铁线</p>
</td>
<td class="cellrowborder" valign="top" width="14.671467146714672%" headers="mcps1.1.9.1.3 "><p id="p1534812413191"><a name="p1534812413191"></a><a name="p1534812413191"></a>-</p>
</td>
<td class="cellrowborder" valign="top" width="8.440844084408441%" headers="mcps1.1.9.1.4 "><p id="p976331716231"><a name="p976331716231"></a><a name="p976331716231"></a><a name="image197636176231"></a><a name="image197636176231"></a><span><img id="image197636176231" src="figures/right-316.png" width="18.945584" height="15.949626000000002"></span></p>
</td>
<td class="cellrowborder" valign="top" width="9.750975097509752%" headers="mcps1.1.9.1.5 "><p id="p178553329268"><a name="p178553329268"></a><a name="p178553329268"></a>-</p>
</td>
<td class="cellrowborder" valign="top" width="9.72097209720972%" headers="mcps1.1.9.1.6 "><p id="p14873233172619"><a name="p14873233172619"></a><a name="p14873233172619"></a>-</p>
</td>
<td class="cellrowborder" valign="top" width="12.291229122912291%" headers="mcps1.1.9.1.7 "><p id="p204155372612"><a name="p204155372612"></a><a name="p204155372612"></a>-</p>
</td>
</tr>
<tr id="row1058883874614"><td class="cellrowborder" valign="top" headers="mcps1.1.9.1.1 "><p id="p15881738194612"><a name="p15881738194612"></a><a name="p15881738194612"></a>rail-station</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.1 "><p id="p85881638194610"><a name="p85881638194610"></a><a name="p85881638194610"></a>火车站、高铁站</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.2 "><p id="p17321162016233"><a name="p17321162016233"></a><a name="p17321162016233"></a><a name="image18321142014237"></a><a name="image18321142014237"></a><span><img id="image18321142014237" src="figures/right-317.png" width="18.945584" height="15.949626000000002"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.3 "><p id="p1527231182615"><a name="p1527231182615"></a><a name="p1527231182615"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.4 "><p id="p194312216235"><a name="p194312216235"></a><a name="p194312216235"></a><a name="image16943102119232"></a><a name="image16943102119232"></a><span><img id="image16943102119232" src="figures/right-318.png" width="18.945584" height="15.949626000000002"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.5 "><p id="p415982392315"><a name="p415982392315"></a><a name="p415982392315"></a><a name="image141591123202314"></a><a name="image141591123202314"></a><span><img id="image141591123202314" src="figures/right-319.png" width="18.945584" height="15.949626000000002"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.6 "><p id="p1150125315267"><a name="p1150125315267"></a><a name="p1150125315267"></a>-</p>
</td>
</tr>
<tr id="row1358873817464"><td class="cellrowborder" valign="top" headers="mcps1.1.9.1.1 "><p id="p14588103812461"><a name="p14588103812461"></a><a name="p14588103812461"></a>ferry-line</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.1 "><p id="p14588123817462"><a name="p14588123817462"></a><a name="p14588123817462"></a>航线</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.2 "><p id="p1370452913268"><a name="p1370452913268"></a><a name="p1370452913268"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.3 "><p id="p1660072413235"><a name="p1660072413235"></a><a name="p1660072413235"></a><a name="image3600192472313"></a><a name="image3600192472313"></a><span><img id="image3600192472313" src="figures/right-320.png" width="18.945584" height="15.949626000000002"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.4 "><p id="p20107153614264"><a name="p20107153614264"></a><a name="p20107153614264"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.5 "><p id="p183791037162615"><a name="p183791037162615"></a><a name="p183791037162615"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.6 "><p id="p18591053122611"><a name="p18591053122611"></a><a name="p18591053122611"></a>-</p>
</td>
</tr>
<tr id="row1458883874615"><td class="cellrowborder" valign="top" headers="mcps1.1.9.1.1 "><p id="p058911389463"><a name="p058911389463"></a><a name="p058911389463"></a>ferry-terminal</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.1 "><p id="p15589103817463"><a name="p15589103817463"></a><a name="p15589103817463"></a>港口</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.2 "><p id="p19991626102312"><a name="p19991626102312"></a><a name="p19991626102312"></a><a name="image139992682317"></a><a name="image139992682317"></a><span><img id="image139992682317" src="figures/right-321.png" width="18.945584" height="15.949626000000002"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.3 "><p id="p162262039132614"><a name="p162262039132614"></a><a name="p162262039132614"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.4 "><p id="p17464527122314"><a name="p17464527122314"></a><a name="p17464527122314"></a><a name="image18464122782313"></a><a name="image18464122782313"></a><span><img id="image18464122782313" src="figures/right-322.png" width="18.945584" height="15.949626000000002"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.5 "><p id="p1771812287234"><a name="p1771812287234"></a><a name="p1771812287234"></a><a name="image3718528202316"></a><a name="image3718528202316"></a><span><img id="image3718528202316" src="figures/right-323.png" width="18.945584" height="15.949626000000002"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.6 "><p id="p36765313266"><a name="p36765313266"></a><a name="p36765313266"></a>-</p>
</td>
</tr>
<tr id="row195891538104611"><td class="cellrowborder" valign="top" headers="mcps1.1.9.1.1 "><p id="p17589163884610"><a name="p17589163884610"></a><a name="p17589163884610"></a>airport</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.1 "><p id="p11589123824614"><a name="p11589123824614"></a><a name="p11589123824614"></a>机场</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.2 "><p id="p429811301237"><a name="p429811301237"></a><a name="p429811301237"></a><a name="image11298430132317"></a><a name="image11298430132317"></a><span><img id="image11298430132317" src="figures/right-324.png" width="18.945584" height="15.949626000000002"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.3 "><p id="p16235183912617"><a name="p16235183912617"></a><a name="p16235183912617"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.4 "><p id="p6689123116231"><a name="p6689123116231"></a><a name="p6689123116231"></a><a name="image1468913182313"></a><a name="image1468913182313"></a><span><img id="image1468913182313" src="figures/right-325.png" width="18.945584" height="15.949626000000002"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.5 "><p id="p78415321239"><a name="p78415321239"></a><a name="p78415321239"></a><a name="image198413324236"></a><a name="image198413324236"></a><span><img id="image198413324236" src="figures/right-326.png" width="18.945584" height="15.949626000000002"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.6 "><p id="p67555332617"><a name="p67555332617"></a><a name="p67555332617"></a>-</p>
</td>
</tr>
<tr id="row18589838144612"><td class="cellrowborder" valign="top" headers="mcps1.1.9.1.1 "><p id="p6589153854612"><a name="p6589153854612"></a><a name="p6589153854612"></a>bus-station</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.1 "><p id="p75894381467"><a name="p75894381467"></a><a name="p75894381467"></a>公交车站</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.2 "><p id="p156761643122615"><a name="p156761643122615"></a><a name="p156761643122615"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.3 "><p id="p16700194312617"><a name="p16700194312617"></a><a name="p16700194312617"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.4 "><p id="p137246434268"><a name="p137246434268"></a><a name="p137246434268"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.5 "><p id="p1373604311265"><a name="p1373604311265"></a><a name="p1373604311265"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.6 "><p id="p77507434268"><a name="p77507434268"></a><a name="p77507434268"></a>-</p>
</td>
</tr>
<tr id="row125905384467"><td class="cellrowborder" valign="top" headers="mcps1.1.9.1.1 "><p id="p14590173854614"><a name="p14590173854614"></a><a name="p14590173854614"></a>other</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.1 "><p id="p1459013834617"><a name="p1459013834617"></a><a name="p1459013834617"></a>出租车、出入口等</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.2 "><p id="p1476264317266"><a name="p1476264317266"></a><a name="p1476264317266"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.3 "><p id="p977014315263"><a name="p977014315263"></a><a name="p977014315263"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.4 "><p id="p147796432265"><a name="p147796432265"></a><a name="p147796432265"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.5 "><p id="p878784332619"><a name="p878784332619"></a><a name="p878784332619"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.9.1.6 "><p id="p07961743152616"><a name="p07961743152616"></a><a name="p07961743152616"></a>-</p>
</td>
</tr>
<tr id="row1859063810465"><td class="cellrowborder" valign="top" width="12.68126812681268%" headers="mcps1.1.9.1.1 "><p id="p459013389468"><a name="p459013389468"></a><a name="p459013389468"></a>water</p>
</td>
<td class="cellrowborder" valign="top" width="14.07140714071407%" headers="mcps1.1.9.1.1 "><p id="p95901038124611"><a name="p95901038124611"></a><a name="p95901038124611"></a>-</p>
</td>
<td class="cellrowborder" valign="top" width="18.371837183718373%" headers="mcps1.1.9.1.2 "><p id="p10590183819464"><a name="p10590183819464"></a><a name="p10590183819464"></a>水系、海洋、湖泊、河流</p>
</td>
<td class="cellrowborder" valign="top" width="14.671467146714672%" headers="mcps1.1.9.1.3 "><p id="p123222343233"><a name="p123222343233"></a><a name="p123222343233"></a><a name="image1932383422315"></a><a name="image1932383422315"></a><span><img id="image1932383422315" src="figures/right-327.png" width="18.945584" height="15.949626000000002"></span></p>
</td>
<td class="cellrowborder" valign="top" width="8.440844084408441%" headers="mcps1.1.9.1.4 "><p id="p1953713451269"><a name="p1953713451269"></a><a name="p1953713451269"></a>-</p>
</td>
<td class="cellrowborder" valign="top" width="9.750975097509752%" headers="mcps1.1.9.1.5 "><p id="p66615367233"><a name="p66615367233"></a><a name="p66615367233"></a><a name="image10661436122310"></a><a name="image10661436122310"></a><span><img id="image10661436122310" src="figures/right-328.png" width="18.945584" height="15.949626000000002"></span></p>
</td>
<td class="cellrowborder" valign="top" width="9.72097209720972%" headers="mcps1.1.9.1.6 "><p id="p2184114772619"><a name="p2184114772619"></a><a name="p2184114772619"></a>-</p>
</td>
<td class="cellrowborder" valign="top" width="12.291229122912291%" headers="mcps1.1.9.1.7 "><p id="p15197154712611"><a name="p15197154712611"></a><a name="p15197154712611"></a>-</p>
</td>
</tr>
</tbody>
</table>

>![](public_sys-resources/icon-note.gif) **说明：** 
>图标类型icon-type支持范围为：standard/night/simple。

