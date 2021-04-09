# 样式参考<a name="ZH-CN_TOPIC_0000001145780993"></a>

自定义地图样式JSON文件通过下列4个元素来定义地图样式：

-   mapFeature：地图要素
-   options：元素选项
    -   geometry.fill：几何填充
    -   geometry.stroke：几何描边
    -   geometry.icon：几何图标
    -   labels.text.fill：文本填充
    -   labels.text.stroke：文本描边

-   paint：绘制属性
    -   color：颜色，16进制颜色，例如“\#FFFF00”
    -   weight：线条宽度。整型值，\[0, 8\]，默认为0，大于0表示加宽
    -   saturation：饱和度。整型值，\[-100, 100\]，默认为0
    -   lightness：亮度。整型值，\[-100, 100\]，默认为0
    -   icon-type：图标类型，目前支持night/simple/standard

-   visibility：可见属性，默认为可见
    -   true：可见
    -   false：不可见


下表将向您展示支持修改的地图元素。

<a name="table7173038124620"></a>
<table><thead align="left"><tr id="row191291551217"><th class="cellrowborder" colspan="2" valign="top" id="mcps1.1.13.1.1"><p id="p1191561611210"><a name="p1191561611210"></a><a name="p1191561611210"></a>元素代码 / Feature type</p>
</th>
<th class="cellrowborder" valign="top" id="mcps1.1.13.1.2"><p id="p1653182512367"><a name="p1653182512367"></a><a name="p1653182512367"></a>地图元素 / Element  type</p>
</th>
<th class="cellrowborder" valign="top" id="mcps1.1.13.1.3"><p id="p5129115126"><a name="p5129115126"></a><a name="p5129115126"></a>几何填充颜色 / Geometry.fill.color</p>
</th>
<th class="cellrowborder" valign="top" id="mcps1.1.13.1.4"><p id="p131292051426"><a name="p131292051426"></a><a name="p131292051426"></a>几何填充线条描边宽度 /Geometry.fill.weight</p>
</th>
<th class="cellrowborder" valign="top" id="mcps1.1.13.1.5"><p id="p812935922"><a name="p812935922"></a><a name="p812935922"></a>几何描边颜色 / Geometry.stroke.color</p>
</th>
<th class="cellrowborder" valign="top" id="mcps1.1.13.1.6"><p id="p11291651725"><a name="p11291651725"></a><a name="p11291651725"></a>几何描边宽度 / Geometry.stroke.weight</p>
</th>
<th class="cellrowborder" valign="top" id="mcps1.1.13.1.7"><p id="p668810291598"><a name="p668810291598"></a><a name="p668810291598"></a>文本填充颜色 / Labels.text.fill.color</p>
</th>
<th class="cellrowborder" valign="top" id="mcps1.1.13.1.8"><p id="p13129951721"><a name="p13129951721"></a><a name="p13129951721"></a>文本填充描边宽度 / Labels.text.fill.weight</p>
</th>
<th class="cellrowborder" valign="top" id="mcps1.1.13.1.9"><p id="p161301553212"><a name="p161301553212"></a><a name="p161301553212"></a>文本描边颜色 / 	Labels.text.stroke.color</p>
</th>
<th class="cellrowborder" valign="top" id="mcps1.1.13.1.10"><p id="p19130105424"><a name="p19130105424"></a><a name="p19130105424"></a>文本描边宽度 / Labels.text.stroke.weight</p>
</th>
<th class="cellrowborder" valign="top" id="mcps1.1.13.1.11"><p id="p1013045226"><a name="p1013045226"></a><a name="p1013045226"></a>图标类型 /	Geometry.icon-type</p>
</th>
</tr>
</thead>
<tbody><tr id="row45691638164619"><td class="cellrowborder" valign="top" headers="mcps1.1.13.1.1 "><p id="p5584524124215"><a name="p5584524124215"></a><a name="p5584524124215"></a>all</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.1 "><p id="p7569113816466"><a name="p7569113816466"></a><a name="p7569113816466"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.2 "><p id="p8569113815463"><a name="p8569113815463"></a><a name="p8569113815463"></a>全部</p>
</td>
<td class="cellrowborder" colspan="9" valign="top" headers="mcps1.1.13.1.3 mcps1.1.13.1.4 mcps1.1.13.1.5 mcps1.1.13.1.6 mcps1.1.13.1.7 mcps1.1.13.1.8 mcps1.1.13.1.9 mcps1.1.13.1.10 mcps1.1.13.1.11 "><p id="p45695389467"><a name="p45695389467"></a><a name="p45695389467"></a>All分类是所有类别的集合，支持能力范围同下方列表。</p>
</td>
</tr>
<tr id="row1956943834613"><td class="cellrowborder" rowspan="6" valign="top" width="10.452090418083618%" headers="mcps1.1.13.1.1 "><p id="p125691038104619"><a name="p125691038104619"></a><a name="p125691038104619"></a>administrative</p>
</td>
<td class="cellrowborder" valign="top" width="9.661932386477297%" headers="mcps1.1.13.1.1 "><p id="p14569103864612"><a name="p14569103864612"></a><a name="p14569103864612"></a>country</p>
</td>
<td class="cellrowborder" valign="top" width="12.20244048809762%" headers="mcps1.1.13.1.2 "><p id="p13569938144615"><a name="p13569938144615"></a><a name="p13569938144615"></a>国家</p>
</td>
<td class="cellrowborder" valign="top" width="10.552110422084418%" headers="mcps1.1.13.1.3 "><p id="p1534812413191"><a name="p1534812413191"></a><a name="p1534812413191"></a>-</p>
</td>
<td class="cellrowborder" valign="top" width="7.701540308061613%" headers="mcps1.1.13.1.4 "><p id="p149385332311"><a name="p149385332311"></a><a name="p149385332311"></a>-</p>
</td>
<td class="cellrowborder" valign="top" width="6.05121024204841%" headers="mcps1.1.13.1.5 "><p id="p10569938194616"><a name="p10569938194616"></a><a name="p10569938194616"></a><a name="image1040815316812"></a><a name="image1040815316812"></a><span><img id="image1040815316812" src="figures/right.png"></span></p>
</td>
<td class="cellrowborder" valign="top" width="7.061412282456492%" headers="mcps1.1.13.1.6 "><p id="p6676103710812"><a name="p6676103710812"></a><a name="p6676103710812"></a><a name="image1067743719810"></a><a name="image1067743719810"></a><span><img id="image1067743719810" src="figures/right-0.png"></span></p>
</td>
<td class="cellrowborder" valign="top" width="7.041408281656332%" headers="mcps1.1.13.1.7 "><p id="p67331639485"><a name="p67331639485"></a><a name="p67331639485"></a><a name="image16733173920816"></a><a name="image16733173920816"></a><span><img id="image16733173920816" src="figures/right-1.png"></span></p>
</td>
<td class="cellrowborder" valign="top" width="7.051410282056411%" headers="mcps1.1.13.1.8 "><p id="p58509411381"><a name="p58509411381"></a><a name="p58509411381"></a><a name="image8850141480"></a><a name="image8850141480"></a><span><img id="image8850141480" src="figures/right-2.png"></span></p>
</td>
<td class="cellrowborder" valign="top" width="6.931386277255452%" headers="mcps1.1.13.1.9 "><p id="p1423919436812"><a name="p1423919436812"></a><a name="p1423919436812"></a><a name="image1423914431984"></a><a name="image1423914431984"></a><span><img id="image1423914431984" src="figures/right-3.png"></span></p>
</td>
<td class="cellrowborder" valign="top" width="6.481296259251851%" headers="mcps1.1.13.1.10 "><p id="p127078441812"><a name="p127078441812"></a><a name="p127078441812"></a><a name="image15707244186"></a><a name="image15707244186"></a><span><img id="image15707244186" src="figures/right-4.png"></span></p>
</td>
<td class="cellrowborder" valign="top" width="8.811762352470495%" headers="mcps1.1.13.1.11 "><p id="p185618448243"><a name="p185618448243"></a><a name="p185618448243"></a>-</p>
</td>
</tr>
<tr id="row165705380461"><td class="cellrowborder" valign="top" headers="mcps1.1.13.1.1 "><p id="p11570838134619"><a name="p11570838134619"></a><a name="p11570838134619"></a>province</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.1 "><p id="p1457017387468"><a name="p1457017387468"></a><a name="p1457017387468"></a>省</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.2 "><p id="p6579759122213"><a name="p6579759122213"></a><a name="p6579759122213"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.3 "><p id="p1165119472314"><a name="p1165119472314"></a><a name="p1165119472314"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.4 "><p id="p939511017913"><a name="p939511017913"></a><a name="p939511017913"></a><a name="image33952101795"></a><a name="image33952101795"></a><span><img id="image33952101795" src="figures/right-5.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.5 "><p id="p182919137916"><a name="p182919137916"></a><a name="p182919137916"></a><a name="image192911137919"></a><a name="image192911137919"></a><span><img id="image192911137919" src="figures/right-6.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.6 "><p id="p16725151411914"><a name="p16725151411914"></a><a name="p16725151411914"></a><a name="image27264147914"></a><a name="image27264147914"></a><span><img id="image27264147914" src="figures/right-7.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.7 "><p id="p103211615919"><a name="p103211615919"></a><a name="p103211615919"></a><a name="image15321816293"></a><a name="image15321816293"></a><span><img id="image15321816293" src="figures/right-8.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.8 "><p id="p1245514171694"><a name="p1245514171694"></a><a name="p1245514171694"></a><a name="image8455517992"></a><a name="image8455517992"></a><span><img id="image8455517992" src="figures/right-9.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.9 "><p id="p11862181812916"><a name="p11862181812916"></a><a name="p11862181812916"></a><a name="image17862161815915"></a><a name="image17862161815915"></a><span><img id="image17862161815915" src="figures/right-10.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.10 "><p id="p13711944152417"><a name="p13711944152417"></a><a name="p13711944152417"></a>-</p>
</td>
</tr>
<tr id="row157023819468"><td class="cellrowborder" valign="top" headers="mcps1.1.13.1.1 "><p id="p057043874611"><a name="p057043874611"></a><a name="p057043874611"></a>capital</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.1 "><p id="p1357033874615"><a name="p1357033874615"></a><a name="p1357033874615"></a>首都</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.2 "><p id="p206481101239"><a name="p206481101239"></a><a name="p206481101239"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.3 "><p id="p337017552314"><a name="p337017552314"></a><a name="p337017552314"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.4 "><p id="p10810140162312"><a name="p10810140162312"></a><a name="p10810140162312"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.5 "><p id="p11836144072320"><a name="p11836144072320"></a><a name="p11836144072320"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.6 "><p id="p146001520991"><a name="p146001520991"></a><a name="p146001520991"></a><a name="image1560042013913"></a><a name="image1560042013913"></a><span><img id="image1560042013913" src="figures/right-11.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.7 "><p id="p34014221398"><a name="p34014221398"></a><a name="p34014221398"></a><a name="image24019222913"></a><a name="image24019222913"></a><span><img id="image24019222913" src="figures/right-12.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.8 "><p id="p770792312910"><a name="p770792312910"></a><a name="p770792312910"></a><a name="image11707122313911"></a><a name="image11707122313911"></a><span><img id="image11707122313911" src="figures/right-13.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.9 "><p id="p102693256910"><a name="p102693256910"></a><a name="p102693256910"></a><a name="image62697251497"></a><a name="image62697251497"></a><span><img id="image62697251497" src="figures/right-14.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.10 "><p id="p1572712615920"><a name="p1572712615920"></a><a name="p1572712615920"></a><a name="image1772752620914"></a><a name="image1772752620914"></a><span><img id="image1772752620914" src="figures/right-15.png"></span></p>
</td>
</tr>
<tr id="row1957193820463"><td class="cellrowborder" valign="top" headers="mcps1.1.13.1.1 "><p id="p1357119383467"><a name="p1357119383467"></a><a name="p1357119383467"></a>major-city</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.1 "><p id="p1957116383465"><a name="p1957116383465"></a><a name="p1957116383465"></a>1~4级城市</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.2 "><p id="p1049491192313"><a name="p1049491192313"></a><a name="p1049491192313"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.3 "><p id="p112526692317"><a name="p112526692317"></a><a name="p112526692317"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.4 "><p id="p16865104016234"><a name="p16865104016234"></a><a name="p16865104016234"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.5 "><p id="p10880440112313"><a name="p10880440112313"></a><a name="p10880440112313"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.6 "><p id="p5752153312911"><a name="p5752153312911"></a><a name="p5752153312911"></a><a name="image187521133197"></a><a name="image187521133197"></a><span><img id="image187521133197" src="figures/right-16.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.7 "><p id="p738819320913"><a name="p738819320913"></a><a name="p738819320913"></a><a name="image4388932099"></a><a name="image4388932099"></a><span><img id="image4388932099" src="figures/right-17.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.8 "><p id="p178213014917"><a name="p178213014917"></a><a name="p178213014917"></a><a name="image27821130596"></a><a name="image27821130596"></a><span><img id="image27821130596" src="figures/right-18.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.9 "><p id="p161995296915"><a name="p161995296915"></a><a name="p161995296915"></a><a name="image1519915291692"></a><a name="image1519915291692"></a><span><img id="image1519915291692" src="figures/right-19.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.10 "><p id="p6865182716917"><a name="p6865182716917"></a><a name="p6865182716917"></a><a name="image10865142719915"></a><a name="image10865142719915"></a><span><img id="image10865142719915" src="figures/right-20.png"></span></p>
</td>
</tr>
<tr id="row857115383465"><td class="cellrowborder" valign="top" headers="mcps1.1.13.1.1 "><p id="p857111387468"><a name="p857111387468"></a><a name="p857111387468"></a>district</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.1 "><p id="p957123813465"><a name="p957123813465"></a><a name="p957123813465"></a>区\县</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.2 "><p id="p221919212235"><a name="p221919212235"></a><a name="p221919212235"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.3 "><p id="p1617314752319"><a name="p1617314752319"></a><a name="p1617314752319"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.4 "><p id="p198951040192311"><a name="p198951040192311"></a><a name="p198951040192311"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.5 "><p id="p16910840122318"><a name="p16910840122318"></a><a name="p16910840122318"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.6 "><p id="p0250162110106"><a name="p0250162110106"></a><a name="p0250162110106"></a><a name="image4250122141013"></a><a name="image4250122141013"></a><span><img id="image4250122141013" src="figures/right-21.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.7 "><p id="p1743502319109"><a name="p1743502319109"></a><a name="p1743502319109"></a><a name="image16435122341011"></a><a name="image16435122341011"></a><span><img id="image16435122341011" src="figures/right-22.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.8 "><p id="p116971324111019"><a name="p116971324111019"></a><a name="p116971324111019"></a><a name="image1169718244107"></a><a name="image1169718244107"></a><span><img id="image1169718244107" src="figures/right-23.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.9 "><p id="p8382112691011"><a name="p8382112691011"></a><a name="p8382112691011"></a><a name="image123824267109"></a><a name="image123824267109"></a><span><img id="image123824267109" src="figures/right-24.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.10 "><p id="p023054816249"><a name="p023054816249"></a><a name="p023054816249"></a>-</p>
</td>
</tr>
<tr id="row105721938184617"><td class="cellrowborder" valign="top" headers="mcps1.1.13.1.1 "><p id="p957219381463"><a name="p957219381463"></a><a name="p957219381463"></a>locality</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.1 "><p id="p557223816460"><a name="p557223816460"></a><a name="p557223816460"></a>乡村、城镇</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.2 "><p id="p6932152122318"><a name="p6932152122318"></a><a name="p6932152122318"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.3 "><p id="p1990212718233"><a name="p1990212718233"></a><a name="p1990212718233"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.4 "><p id="p492694022313"><a name="p492694022313"></a><a name="p492694022313"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.5 "><p id="p1294113401234"><a name="p1294113401234"></a><a name="p1294113401234"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.6 "><p id="p13786133261018"><a name="p13786133261018"></a><a name="p13786133261018"></a><a name="image07868322109"></a><a name="image07868322109"></a><span><img id="image07868322109" src="figures/right-25.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.7 "><p id="p445973061017"><a name="p445973061017"></a><a name="p445973061017"></a><a name="image7459123011102"></a><a name="image7459123011102"></a><span><img id="image7459123011102" src="figures/right-26.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.8 "><p id="p1027912291103"><a name="p1027912291103"></a><a name="p1027912291103"></a><a name="image0279102941010"></a><a name="image0279102941010"></a><span><img id="image0279102941010" src="figures/right-27.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.9 "><p id="p1388122711106"><a name="p1388122711106"></a><a name="p1388122711106"></a><a name="image1988192713102"></a><a name="image1988192713102"></a><span><img id="image1988192713102" src="figures/right-28.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.10 "><p id="p72569484241"><a name="p72569484241"></a><a name="p72569484241"></a>-</p>
</td>
</tr>
<tr id="row185721138194610"><td class="cellrowborder" rowspan="8" valign="top" width="10.452090418083618%" headers="mcps1.1.13.1.1 "><p id="p157283816465"><a name="p157283816465"></a><a name="p157283816465"></a>landcover</p>
</td>
<td class="cellrowborder" valign="top" width="9.661932386477297%" headers="mcps1.1.13.1.1 "><p id="p557233815463"><a name="p557233815463"></a><a name="p557233815463"></a>natural</p>
</td>
<td class="cellrowborder" valign="top" width="12.20244048809762%" headers="mcps1.1.13.1.2 "><p id="p5572103884620"><a name="p5572103884620"></a><a name="p5572103884620"></a>陆地、岛屿、海滩、冰川等</p>
</td>
<td class="cellrowborder" valign="top" width="10.552110422084418%" headers="mcps1.1.13.1.3 "><p id="p1480733411019"><a name="p1480733411019"></a><a name="p1480733411019"></a><a name="image780716344106"></a><a name="image780716344106"></a><span><img id="image780716344106" src="figures/right-29.png"></span></p>
</td>
<td class="cellrowborder" valign="top" width="7.701540308061613%" headers="mcps1.1.13.1.4 "><p id="p96801527132316"><a name="p96801527132316"></a><a name="p96801527132316"></a>-</p>
</td>
<td class="cellrowborder" valign="top" width="6.05121024204841%" headers="mcps1.1.13.1.5 "><p id="p8957740192310"><a name="p8957740192310"></a><a name="p8957740192310"></a>-</p>
</td>
<td class="cellrowborder" valign="top" width="7.061412282456492%" headers="mcps1.1.13.1.6 "><p id="p5973240162316"><a name="p5973240162316"></a><a name="p5973240162316"></a>-</p>
</td>
<td class="cellrowborder" valign="top" width="7.041408281656332%" headers="mcps1.1.13.1.7 "><p id="p18583133610107"><a name="p18583133610107"></a><a name="p18583133610107"></a><a name="image558313366101"></a><a name="image558313366101"></a><span><img id="image558313366101" src="figures/right-30.png"></span></p>
</td>
<td class="cellrowborder" valign="top" width="7.051410282056411%" headers="mcps1.1.13.1.8 "><p id="p9180183831015"><a name="p9180183831015"></a><a name="p9180183831015"></a><a name="image10180538161020"></a><a name="image10180538161020"></a><span><img id="image10180538161020" src="figures/right-31.png"></span></p>
</td>
<td class="cellrowborder" valign="top" width="6.931386277255452%" headers="mcps1.1.13.1.9 "><p id="p1873511397105"><a name="p1873511397105"></a><a name="p1873511397105"></a><a name="image147351039131017"></a><a name="image147351039131017"></a><span><img id="image147351039131017" src="figures/right-32.png"></span></p>
</td>
<td class="cellrowborder" valign="top" width="6.481296259251851%" headers="mcps1.1.13.1.10 "><p id="p172711041111010"><a name="p172711041111010"></a><a name="p172711041111010"></a><a name="image17271154141010"></a><a name="image17271154141010"></a><span><img id="image17271154141010" src="figures/right-33.png"></span></p>
</td>
<td class="cellrowborder" valign="top" width="8.811762352470495%" headers="mcps1.1.13.1.11 "><p id="p13286144817241"><a name="p13286144817241"></a><a name="p13286144817241"></a>-</p>
</td>
</tr>
<tr id="row957383814467"><td class="cellrowborder" rowspan="2" valign="top" headers="mcps1.1.13.1.1 "><p id="p13573113834617"><a name="p13573113834617"></a><a name="p13573113834617"></a>human-made</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.1 "><p id="p257315389461"><a name="p257315389461"></a><a name="p257315389461"></a>聚集区、小区、工业区、监狱地面等</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.2 "><p id="p5731044151016"><a name="p5731044151016"></a><a name="p5731044151016"></a><a name="image873184418101"></a><a name="image873184418101"></a><span><img id="image873184418101" src="figures/right-34.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.3 "><p id="p2707112752310"><a name="p2707112752310"></a><a name="p2707112752310"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.4 "><p id="p10981945101018"><a name="p10981945101018"></a><a name="p10981945101018"></a><a name="image3981145151012"></a><a name="image3981145151012"></a><span><img id="image3981145151012" src="figures/right-35.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.5 "><p id="p16514413231"><a name="p16514413231"></a><a name="p16514413231"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.6 "><p id="p98389470107"><a name="p98389470107"></a><a name="p98389470107"></a><a name="image11838747171011"></a><a name="image11838747171011"></a><span><img id="image11838747171011" src="figures/right-36.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.7 "><p id="p135074914109"><a name="p135074914109"></a><a name="p135074914109"></a><a name="image9350849131017"></a><a name="image9350849131017"></a><span><img id="image9350849131017" src="figures/right-37.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.8 "><p id="p61165112104"><a name="p61165112104"></a><a name="p61165112104"></a><a name="image31115131014"></a><a name="image31115131014"></a><span><img id="image31115131014" src="figures/right-38.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.9 "><p id="p1493105241017"><a name="p1493105241017"></a><a name="p1493105241017"></a><a name="image1949325211101"></a><a name="image1949325211101"></a><span><img id="image1949325211101" src="figures/right-39.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.10 "><p id="p230284814246"><a name="p230284814246"></a><a name="p230284814246"></a>-</p>
</td>
</tr>
<tr id="row1573163814467"><td class="cellrowborder" valign="top" headers="mcps1.1.13.1.1 "><p id="p185731638174619"><a name="p185731638174619"></a><a name="p185731638174619"></a>building建筑物</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.1 "><p id="p849475415106"><a name="p849475415106"></a><a name="p849475415106"></a><a name="image749419546105"></a><a name="image749419546105"></a><span><img id="image749419546105" src="figures/right-40.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.2 "><p id="p1173662712312"><a name="p1173662712312"></a><a name="p1173662712312"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.3 "><p id="p141141556121015"><a name="p141141556121015"></a><a name="p141141556121015"></a><a name="image141149565105"></a><a name="image141149565105"></a><span><img id="image141149565105" src="figures/right-41.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.4 "><p id="p435114111234"><a name="p435114111234"></a><a name="p435114111234"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.5 "><p id="p3334173462411"><a name="p3334173462411"></a><a name="p3334173462411"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.6 "><p id="p183492343248"><a name="p183492343248"></a><a name="p183492343248"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.7 "><p id="p536412345244"><a name="p536412345244"></a><a name="p536412345244"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.8 "><p id="p1075574717195"><a name="p1075574717195"></a><a name="p1075574717195"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.9 "><p id="p123171348142410"><a name="p123171348142410"></a><a name="p123171348142410"></a>-</p>
</td>
</tr>
<tr id="row1357417387465"><td class="cellrowborder" valign="top" headers="mcps1.1.13.1.1 "><p id="p1257410381466"><a name="p1257410381466"></a><a name="p1257410381466"></a>parkland</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.1 "><p id="p7574038194617"><a name="p7574038194617"></a><a name="p7574038194617"></a>森林、公园、荒地、高尔夫球场等</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.2 "><p id="p1234210587108"><a name="p1234210587108"></a><a name="p1234210587108"></a><a name="image73424588106"></a><a name="image73424588106"></a><span><img id="image73424588106" src="figures/right-42.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.3 "><p id="p1275242742318"><a name="p1275242742318"></a><a name="p1275242742318"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.4 "><p id="p1550341152319"><a name="p1550341152319"></a><a name="p1550341152319"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.5 "><p id="p1965134111232"><a name="p1965134111232"></a><a name="p1965134111232"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.6 "><p id="p148641017112"><a name="p148641017112"></a><a name="p148641017112"></a><a name="image1186410010112"></a><a name="image1186410010112"></a><span><img id="image1186410010112" src="figures/right-43.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.7 "><p id="p946822181111"><a name="p946822181111"></a><a name="p946822181111"></a><a name="image74689231113"></a><a name="image74689231113"></a><span><img id="image74689231113" src="figures/right-44.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.8 "><p id="p67621034116"><a name="p67621034116"></a><a name="p67621034116"></a><a name="image57629314117"></a><a name="image57629314117"></a><span><img id="image57629314117" src="figures/right-45.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.9 "><p id="p82712052116"><a name="p82712052116"></a><a name="p82712052116"></a><a name="image827175121118"></a><a name="image827175121118"></a><span><img id="image827175121118" src="figures/right-46.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.10 "><p id="p7333848182417"><a name="p7333848182417"></a><a name="p7333848182417"></a>-</p>
</td>
</tr>
<tr id="row125741138174613"><td class="cellrowborder" valign="top" headers="mcps1.1.13.1.1 "><p id="p14574138114617"><a name="p14574138114617"></a><a name="p14574138114617"></a>attraction</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.1 "><p id="p165741238144614"><a name="p165741238144614"></a><a name="p165741238144614"></a>游乐场、动植物园等</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.2 "><p id="p1097115209113"><a name="p1097115209113"></a><a name="p1097115209113"></a><a name="image997110205110"></a><a name="image997110205110"></a><span><img id="image997110205110" src="figures/right-47.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.3 "><p id="p16766327112310"><a name="p16766327112310"></a><a name="p16766327112310"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.4 "><p id="p279124111235"><a name="p279124111235"></a><a name="p279124111235"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.5 "><p id="p1094134116237"><a name="p1094134116237"></a><a name="p1094134116237"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.6 "><p id="p2073432241112"><a name="p2073432241112"></a><a name="p2073432241112"></a><a name="image1734112218112"></a><a name="image1734112218112"></a><span><img id="image1734112218112" src="figures/right-48.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.7 "><p id="p743592417119"><a name="p743592417119"></a><a name="p743592417119"></a><a name="image44351243112"></a><a name="image44351243112"></a><span><img id="image44351243112" src="figures/right-49.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.8 "><p id="p568192621120"><a name="p568192621120"></a><a name="p568192621120"></a><a name="image3698264113"></a><a name="image3698264113"></a><span><img id="image3698264113" src="figures/right-50.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.9 "><p id="p196371027131113"><a name="p196371027131113"></a><a name="p196371027131113"></a><a name="image663732781114"></a><a name="image663732781114"></a><span><img id="image663732781114" src="figures/right-51.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.10 "><p id="p1347114862416"><a name="p1347114862416"></a><a name="p1347114862416"></a>-</p>
</td>
</tr>
<tr id="row145751238104615"><td class="cellrowborder" valign="top" headers="mcps1.1.13.1.1 "><p id="p0575038124617"><a name="p0575038124617"></a><a name="p0575038124617"></a>hospital</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.1 "><p id="p135757388462"><a name="p135757388462"></a><a name="p135757388462"></a>医院</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.2 "><p id="p433512917118"><a name="p433512917118"></a><a name="p433512917118"></a><a name="image1533515292117"></a><a name="image1533515292117"></a><span><img id="image1533515292117" src="figures/right-52.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.3 "><p id="p16782192714234"><a name="p16782192714234"></a><a name="p16782192714234"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.4 "><p id="p15110184115235"><a name="p15110184115235"></a><a name="p15110184115235"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.5 "><p id="p1512614117237"><a name="p1512614117237"></a><a name="p1512614117237"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.6 "><p id="p415310317111"><a name="p415310317111"></a><a name="p415310317111"></a><a name="image19153103101117"></a><a name="image19153103101117"></a><span><img id="image19153103101117" src="figures/right-53.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.7 "><p id="p1346943218115"><a name="p1346943218115"></a><a name="p1346943218115"></a><a name="image1146920328114"></a><a name="image1146920328114"></a><span><img id="image1146920328114" src="figures/right-54.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.8 "><p id="p19161833101117"><a name="p19161833101117"></a><a name="p19161833101117"></a><a name="image7916233131118"></a><a name="image7916233131118"></a><span><img id="image7916233131118" src="figures/right-55.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.9 "><p id="p12180173541116"><a name="p12180173541116"></a><a name="p12180173541116"></a><a name="image1718043581119"></a><a name="image1718043581119"></a><span><img id="image1718043581119" src="figures/right-56.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.10 "><p id="p1051512514247"><a name="p1051512514247"></a><a name="p1051512514247"></a>-</p>
</td>
</tr>
<tr id="row45756383463"><td class="cellrowborder" valign="top" headers="mcps1.1.13.1.1 "><p id="p14575438184615"><a name="p14575438184615"></a><a name="p14575438184615"></a>college</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.1 "><p id="p4575103814469"><a name="p4575103814469"></a><a name="p4575103814469"></a>学校</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.2 "><p id="p5116637171110"><a name="p5116637171110"></a><a name="p5116637171110"></a><a name="image1611613710115"></a><a name="image1611613710115"></a><span><img id="image1611613710115" src="figures/right-57.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.3 "><p id="p12797132742311"><a name="p12797132742311"></a><a name="p12797132742311"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.4 "><p id="p7141194110234"><a name="p7141194110234"></a><a name="p7141194110234"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.5 "><p id="p015634102310"><a name="p015634102310"></a><a name="p015634102310"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.6 "><p id="p1174773861116"><a name="p1174773861116"></a><a name="p1174773861116"></a><a name="image137477389111"></a><a name="image137477389111"></a><span><img id="image137477389111" src="figures/right-58.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.7 "><p id="p36631400111"><a name="p36631400111"></a><a name="p36631400111"></a><a name="image2663134061117"></a><a name="image2663134061117"></a><span><img id="image2663134061117" src="figures/right-59.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.8 "><p id="p628012424118"><a name="p628012424118"></a><a name="p628012424118"></a><a name="image528016427117"></a><a name="image528016427117"></a><span><img id="image528016427117" src="figures/right-60.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.9 "><p id="p19751243131114"><a name="p19751243131114"></a><a name="p19751243131114"></a><a name="image199762438115"></a><a name="image199762438115"></a><span><img id="image199762438115" src="figures/right-61.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.10 "><p id="p4530105114242"><a name="p4530105114242"></a><a name="p4530105114242"></a>-</p>
</td>
</tr>
<tr id="row75759382463"><td class="cellrowborder" valign="top" headers="mcps1.1.13.1.1 "><p id="p195754388468"><a name="p195754388468"></a><a name="p195754388468"></a>business</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.1 "><p id="p957633894619"><a name="p957633894619"></a><a name="p957633894619"></a>购物中心、商业区等</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.2 "><p id="p159389451118"><a name="p159389451118"></a><a name="p159389451118"></a><a name="image17938134591117"></a><a name="image17938134591117"></a><span><img id="image17938134591117" src="figures/right-62.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.3 "><p id="p14812627172312"><a name="p14812627172312"></a><a name="p14812627172312"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.4 "><p id="p19170541152312"><a name="p19170541152312"></a><a name="p19170541152312"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.5 "><p id="p018715418238"><a name="p018715418238"></a><a name="p018715418238"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.6 "><p id="p7723104721112"><a name="p7723104721112"></a><a name="p7723104721112"></a><a name="image672394710119"></a><a name="image672394710119"></a><span><img id="image672394710119" src="figures/right-63.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.7 "><p id="p11479104917117"><a name="p11479104917117"></a><a name="p11479104917117"></a><a name="image20479114914113"></a><a name="image20479114914113"></a><span><img id="image20479114914113" src="figures/right-64.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.8 "><p id="p19158517113"><a name="p19158517113"></a><a name="p19158517113"></a><a name="image1615951101118"></a><a name="image1615951101118"></a><span><img id="image1615951101118" src="figures/right-65.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.9 "><p id="p9394852191117"><a name="p9394852191117"></a><a name="p9394852191117"></a><a name="image43942524114"></a><a name="image43942524114"></a><span><img id="image43942524114" src="figures/right-66.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.10 "><p id="p1354945172411"><a name="p1354945172411"></a><a name="p1354945172411"></a>-</p>
</td>
</tr>
<tr id="row195761838184618"><td class="cellrowborder" rowspan="13" valign="top" width="10.452090418083618%" headers="mcps1.1.13.1.1 "><p id="p135769387462"><a name="p135769387462"></a><a name="p135769387462"></a>poi</p>
</td>
<td class="cellrowborder" valign="top" width="9.661932386477297%" headers="mcps1.1.13.1.1 "><p id="p1257683844620"><a name="p1257683844620"></a><a name="p1257683844620"></a>shopping</p>
</td>
<td class="cellrowborder" valign="top" width="12.20244048809762%" headers="mcps1.1.13.1.2 "><p id="p165768384468"><a name="p165768384468"></a><a name="p165768384468"></a>购物中心、市场等</p>
</td>
<td class="cellrowborder" valign="top" width="10.552110422084418%" headers="mcps1.1.13.1.3 "><p id="p1180271742317"><a name="p1180271742317"></a><a name="p1180271742317"></a>-</p>
</td>
<td class="cellrowborder" valign="top" width="7.701540308061613%" headers="mcps1.1.13.1.4 "><p id="p9829122713232"><a name="p9829122713232"></a><a name="p9829122713232"></a>-</p>
</td>
<td class="cellrowborder" valign="top" width="6.05121024204841%" headers="mcps1.1.13.1.5 "><p id="p10203104172313"><a name="p10203104172313"></a><a name="p10203104172313"></a>-</p>
</td>
<td class="cellrowborder" valign="top" width="7.061412282456492%" headers="mcps1.1.13.1.6 "><p id="p122201413236"><a name="p122201413236"></a><a name="p122201413236"></a>-</p>
</td>
<td class="cellrowborder" valign="top" width="7.041408281656332%" headers="mcps1.1.13.1.7 "><p id="p761705419115"><a name="p761705419115"></a><a name="p761705419115"></a><a name="image19617185410118"></a><a name="image19617185410118"></a><span><img id="image19617185410118" src="figures/right-67.png"></span></p>
</td>
<td class="cellrowborder" valign="top" width="7.051410282056411%" headers="mcps1.1.13.1.8 "><p id="p146275610112"><a name="p146275610112"></a><a name="p146275610112"></a><a name="image462195616119"></a><a name="image462195616119"></a><span><img id="image462195616119" src="figures/right-68.png"></span></p>
</td>
<td class="cellrowborder" valign="top" width="6.931386277255452%" headers="mcps1.1.13.1.9 "><p id="p193116574119"><a name="p193116574119"></a><a name="p193116574119"></a><a name="image4311195718113"></a><a name="image4311195718113"></a><span><img id="image4311195718113" src="figures/right-69.png"></span></p>
</td>
<td class="cellrowborder" valign="top" width="6.481296259251851%" headers="mcps1.1.13.1.10 "><p id="p13662155812114"><a name="p13662155812114"></a><a name="p13662155812114"></a><a name="image10662135810116"></a><a name="image10662135810116"></a><span><img id="image10662135810116" src="figures/right-70.png"></span></p>
</td>
<td class="cellrowborder" valign="top" width="8.811762352470495%" headers="mcps1.1.13.1.11 "><p id="p893535981112"><a name="p893535981112"></a><a name="p893535981112"></a><a name="image393615921118"></a><a name="image393615921118"></a><span><img id="image393615921118" src="figures/right-71.png"></span></p>
</td>
</tr>
<tr id="row4576838134617"><td class="cellrowborder" valign="top" headers="mcps1.1.13.1.1 "><p id="p1257613854615"><a name="p1257613854615"></a><a name="p1257613854615"></a>tourism</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.1 "><p id="p3577138194611"><a name="p3577138194611"></a><a name="p3577138194611"></a>旅游景点、历史遗迹、教堂等</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.2 "><p id="p3830131719230"><a name="p3830131719230"></a><a name="p3830131719230"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.3 "><p id="p0843152720230"><a name="p0843152720230"></a><a name="p0843152720230"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.4 "><p id="p10236204114232"><a name="p10236204114232"></a><a name="p10236204114232"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.5 "><p id="p2251134110232"><a name="p2251134110232"></a><a name="p2251134110232"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.6 "><p id="p134758514124"><a name="p134758514124"></a><a name="p134758514124"></a><a name="image1047595201217"></a><a name="image1047595201217"></a><span><img id="image1047595201217" src="figures/right-72.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.7 "><p id="p171331277120"><a name="p171331277120"></a><a name="p171331277120"></a><a name="image413316771216"></a><a name="image413316771216"></a><span><img id="image413316771216" src="figures/right-73.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.8 "><p id="p1169658171215"><a name="p1169658171215"></a><a name="p1169658171215"></a><a name="image16962871213"></a><a name="image16962871213"></a><span><img id="image16962871213" src="figures/right-74.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.9 "><p id="p123911110131216"><a name="p123911110131216"></a><a name="p123911110131216"></a><a name="image93911810101219"></a><a name="image93911810101219"></a><span><img id="image93911810101219" src="figures/right-75.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.10 "><p id="p1685216114128"><a name="p1685216114128"></a><a name="p1685216114128"></a><a name="image168521011141211"></a><a name="image168521011141211"></a><span><img id="image168521011141211" src="figures/right-76.png"></span></p>
</td>
</tr>
<tr id="row6577338194610"><td class="cellrowborder" valign="top" headers="mcps1.1.13.1.1 "><p id="p5577153884613"><a name="p5577153884613"></a><a name="p5577153884613"></a>leisure</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.1 "><p id="p8577113816468"><a name="p8577113816468"></a><a name="p8577113816468"></a>休闲娱乐</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.2 "><p id="p19857181742317"><a name="p19857181742317"></a><a name="p19857181742317"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.3 "><p id="p168582027162313"><a name="p168582027162313"></a><a name="p168582027162313"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.4 "><p id="p1026644111232"><a name="p1026644111232"></a><a name="p1026644111232"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.5 "><p id="p1028115418236"><a name="p1028115418236"></a><a name="p1028115418236"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.6 "><p id="p1050861371217"><a name="p1050861371217"></a><a name="p1050861371217"></a><a name="image05081513101212"></a><a name="image05081513101212"></a><span><img id="image05081513101212" src="figures/right-77.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.7 "><p id="p322020150123"><a name="p322020150123"></a><a name="p322020150123"></a><a name="image1622091517125"></a><a name="image1622091517125"></a><span><img id="image1622091517125" src="figures/right-78.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.8 "><p id="p2865141681212"><a name="p2865141681212"></a><a name="p2865141681212"></a><a name="image1986551621217"></a><a name="image1986551621217"></a><span><img id="image1986551621217" src="figures/right-79.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.9 "><p id="p1161187128"><a name="p1161187128"></a><a name="p1161187128"></a><a name="image1716318201213"></a><a name="image1716318201213"></a><span><img id="image1716318201213" src="figures/right-80.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.10 "><p id="p69516192123"><a name="p69516192123"></a><a name="p69516192123"></a><a name="image4955190123"></a><a name="image4955190123"></a><span><img id="image4955190123" src="figures/right-81.png"></span></p>
</td>
</tr>
<tr id="row115787385468"><td class="cellrowborder" valign="top" headers="mcps1.1.13.1.1 "><p id="p195782038134614"><a name="p195782038134614"></a><a name="p195782038134614"></a>eating&amp;drinking</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.1 "><p id="p55781538114611"><a name="p55781538114611"></a><a name="p55781538114611"></a>饮食快餐</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.2 "><p id="p68737173233"><a name="p68737173233"></a><a name="p68737173233"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.3 "><p id="p487352712316"><a name="p487352712316"></a><a name="p487352712316"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.4 "><p id="p7296174117239"><a name="p7296174117239"></a><a name="p7296174117239"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.5 "><p id="p143151941122317"><a name="p143151941122317"></a><a name="p143151941122317"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.6 "><p id="p3753112811211"><a name="p3753112811211"></a><a name="p3753112811211"></a><a name="image11753202820125"></a><a name="image11753202820125"></a><span><img id="image11753202820125" src="figures/right-82.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.7 "><p id="p441816302129"><a name="p441816302129"></a><a name="p441816302129"></a><a name="image5418193011124"></a><a name="image5418193011124"></a><span><img id="image5418193011124" src="figures/right-83.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.8 "><p id="p1985623111213"><a name="p1985623111213"></a><a name="p1985623111213"></a><a name="image38563312125"></a><a name="image38563312125"></a><span><img id="image38563312125" src="figures/right-84.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.9 "><p id="p736373391215"><a name="p736373391215"></a><a name="p736373391215"></a><a name="image236318331120"></a><a name="image236318331120"></a><span><img id="image236318331120" src="figures/right-85.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.10 "><p id="p153687341128"><a name="p153687341128"></a><a name="p153687341128"></a><a name="image16368434161215"></a><a name="image16368434161215"></a><span><img id="image16368434161215" src="figures/right-86.png"></span></p>
</td>
</tr>
<tr id="row125792385468"><td class="cellrowborder" valign="top" headers="mcps1.1.13.1.1 "><p id="p3579113814620"><a name="p3579113814620"></a><a name="p3579113814620"></a>beauty</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.1 "><p id="p9579123894617"><a name="p9579123894617"></a><a name="p9579123894617"></a>美容中心</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.2 "><p id="p98891017102317"><a name="p98891017102317"></a><a name="p98891017102317"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.3 "><p id="p888782714238"><a name="p888782714238"></a><a name="p888782714238"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.4 "><p id="p233215416232"><a name="p233215416232"></a><a name="p233215416232"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.5 "><p id="p1634894117235"><a name="p1634894117235"></a><a name="p1634894117235"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.6 "><p id="p14996835141210"><a name="p14996835141210"></a><a name="p14996835141210"></a><a name="image699613355126"></a><a name="image699613355126"></a><span><img id="image699613355126" src="figures/right-87.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.7 "><p id="p610220372126"><a name="p610220372126"></a><a name="p610220372126"></a><a name="image1110283721217"></a><a name="image1110283721217"></a><span><img id="image1110283721217" src="figures/right-88.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.8 "><p id="p921538161216"><a name="p921538161216"></a><a name="p921538161216"></a><a name="image32116380123"></a><a name="image32116380123"></a><span><img id="image32116380123" src="figures/right-89.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.9 "><p id="p16964153841218"><a name="p16964153841218"></a><a name="p16964153841218"></a><a name="image1996414382120"></a><a name="image1996414382120"></a><span><img id="image1996414382120" src="figures/right-90.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.10 "><p id="p213411402124"><a name="p213411402124"></a><a name="p213411402124"></a><a name="image12134144021210"></a><a name="image12134144021210"></a><span><img id="image12134144021210" src="figures/right-91.png"></span></p>
</td>
</tr>
<tr id="row18580163854620"><td class="cellrowborder" valign="top" headers="mcps1.1.13.1.1 "><p id="p458063824619"><a name="p458063824619"></a><a name="p458063824619"></a>lodging</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.1 "><p id="p13580153894610"><a name="p13580153894610"></a><a name="p13580153894610"></a>酒店、住宿点</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.2 "><p id="p14904917142314"><a name="p14904917142314"></a><a name="p14904917142314"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.3 "><p id="p14903427192311"><a name="p14903427192311"></a><a name="p14903427192311"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.4 "><p id="p1936344172316"><a name="p1936344172316"></a><a name="p1936344172316"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.5 "><p id="p103781041102316"><a name="p103781041102316"></a><a name="p103781041102316"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.6 "><p id="p15845541161213"><a name="p15845541161213"></a><a name="p15845541161213"></a><a name="image1684544131218"></a><a name="image1684544131218"></a><span><img id="image1684544131218" src="figures/right-92.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.7 "><p id="p098617422121"><a name="p098617422121"></a><a name="p098617422121"></a><a name="image398624213120"></a><a name="image398624213120"></a><span><img id="image398624213120" src="figures/right-93.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.8 "><p id="p153302442129"><a name="p153302442129"></a><a name="p153302442129"></a><a name="image733074481219"></a><a name="image733074481219"></a><span><img id="image733074481219" src="figures/right-94.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.9 "><p id="p815464618122"><a name="p815464618122"></a><a name="p815464618122"></a><a name="image7154184681217"></a><a name="image7154184681217"></a><span><img id="image7154184681217" src="figures/right-95.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.10 "><p id="p7552114717127"><a name="p7552114717127"></a><a name="p7552114717127"></a><a name="image655264720123"></a><a name="image655264720123"></a><span><img id="image655264720123" src="figures/right-96.png"></span></p>
</td>
</tr>
<tr id="row1558116383463"><td class="cellrowborder" valign="top" headers="mcps1.1.13.1.1 "><p id="p18581203864610"><a name="p18581203864610"></a><a name="p18581203864610"></a>health-care</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.1 "><p id="p75811380468"><a name="p75811380468"></a><a name="p75811380468"></a>医院、诊所、药店等</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.2 "><p id="p20918141742319"><a name="p20918141742319"></a><a name="p20918141742319"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.3 "><p id="p9918182718239"><a name="p9918182718239"></a><a name="p9918182718239"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.4 "><p id="p16394104111231"><a name="p16394104111231"></a><a name="p16394104111231"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.5 "><p id="p164092419230"><a name="p164092419230"></a><a name="p164092419230"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.6 "><p id="p1699631612135"><a name="p1699631612135"></a><a name="p1699631612135"></a><a name="image899616168132"></a><a name="image899616168132"></a><span><img id="image899616168132" src="figures/right-97.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.7 "><p id="p7996916141315"><a name="p7996916141315"></a><a name="p7996916141315"></a><a name="image14996151618130"></a><a name="image14996151618130"></a><span><img id="image14996151618130" src="figures/right-98.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.8 "><p id="p3996416171310"><a name="p3996416171310"></a><a name="p3996416171310"></a><a name="image18996161681311"></a><a name="image18996161681311"></a><span><img id="image18996161681311" src="figures/right-99.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.9 "><p id="p5996151610137"><a name="p5996151610137"></a><a name="p5996151610137"></a><a name="image399671651310"></a><a name="image399671651310"></a><span><img id="image399671651310" src="figures/right-100.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.10 "><p id="p899621661311"><a name="p899621661311"></a><a name="p899621661311"></a><a name="image19996171681316"></a><a name="image19996171681316"></a><span><img id="image19996171681316" src="figures/right-101.png"></span></p>
</td>
</tr>
<tr id="row958115380462"><td class="cellrowborder" valign="top" headers="mcps1.1.13.1.1 "><p id="p1758123820461"><a name="p1758123820461"></a><a name="p1758123820461"></a>public-service</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.1 "><p id="p1058117383467"><a name="p1058117383467"></a><a name="p1058117383467"></a>学校、政府、警察局等</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.2 "><p id="p99331817152316"><a name="p99331817152316"></a><a name="p99331817152316"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.3 "><p id="p4934192712317"><a name="p4934192712317"></a><a name="p4934192712317"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.4 "><p id="p13425164112239"><a name="p13425164112239"></a><a name="p13425164112239"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.5 "><p id="p44405419238"><a name="p44405419238"></a><a name="p44405419238"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.6 "><p id="p4996101614134"><a name="p4996101614134"></a><a name="p4996101614134"></a><a name="image1199620165139"></a><a name="image1199620165139"></a><span><img id="image1199620165139" src="figures/right-102.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.7 "><p id="p0996191611315"><a name="p0996191611315"></a><a name="p0996191611315"></a><a name="image129961116111315"></a><a name="image129961116111315"></a><span><img id="image129961116111315" src="figures/right-103.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.8 "><p id="p13997131661318"><a name="p13997131661318"></a><a name="p13997131661318"></a><a name="image109979162132"></a><a name="image109979162132"></a><span><img id="image109979162132" src="figures/right-104.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.9 "><p id="p499791616137"><a name="p499791616137"></a><a name="p499791616137"></a><a name="image8997181631319"></a><a name="image8997181631319"></a><span><img id="image8997181631319" src="figures/right-105.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.10 "><p id="p15997416131317"><a name="p15997416131317"></a><a name="p15997416131317"></a><a name="image999751681318"></a><a name="image999751681318"></a><span><img id="image999751681318" src="figures/right-106.png"></span></p>
</td>
</tr>
<tr id="row1758183820462"><td class="cellrowborder" valign="top" headers="mcps1.1.13.1.1 "><p id="p95811438154614"><a name="p95811438154614"></a><a name="p95811438154614"></a>business</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.1 "><p id="p17582538164611"><a name="p17582538164611"></a><a name="p17582538164611"></a>公司、商业楼等</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.2 "><p id="p6949121715235"><a name="p6949121715235"></a><a name="p6949121715235"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.3 "><p id="p595072712235"><a name="p595072712235"></a><a name="p595072712235"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.4 "><p id="p1245764113231"><a name="p1245764113231"></a><a name="p1245764113231"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.5 "><p id="p747324192315"><a name="p747324192315"></a><a name="p747324192315"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.6 "><p id="p1399781618135"><a name="p1399781618135"></a><a name="p1399781618135"></a><a name="image5997916181318"></a><a name="image5997916181318"></a><span><img id="image5997916181318" src="figures/right-107.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.7 "><p id="p129976165135"><a name="p129976165135"></a><a name="p129976165135"></a><a name="image16997181671316"></a><a name="image16997181671316"></a><span><img id="image16997181671316" src="figures/right-108.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.8 "><p id="p5997111601312"><a name="p5997111601312"></a><a name="p5997111601312"></a><a name="image6997161618139"></a><a name="image6997161618139"></a><span><img id="image6997161618139" src="figures/right-109.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.9 "><p id="p1699713165133"><a name="p1699713165133"></a><a name="p1699713165133"></a><a name="image19997151610138"></a><a name="image19997151610138"></a><span><img id="image19997151610138" src="figures/right-110.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.10 "><p id="p299761671316"><a name="p299761671316"></a><a name="p299761671316"></a><a name="image1799710166136"></a><a name="image1799710166136"></a><span><img id="image1799710166136" src="figures/right-111.png"></span></p>
</td>
</tr>
<tr id="row105828387467"><td class="cellrowborder" valign="top" headers="mcps1.1.13.1.1 "><p id="p15582838184611"><a name="p15582838184611"></a><a name="p15582838184611"></a>automotive</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.1 "><p id="p658243810463"><a name="p658243810463"></a><a name="p658243810463"></a>汽修、充电桩、洗车等</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.2 "><p id="p11964111713238"><a name="p11964111713238"></a><a name="p11964111713238"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.3 "><p id="p16966112710236"><a name="p16966112710236"></a><a name="p16966112710236"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.4 "><p id="p2048919415231"><a name="p2048919415231"></a><a name="p2048919415231"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.5 "><p id="p4505204119234"><a name="p4505204119234"></a><a name="p4505204119234"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.6 "><p id="p19997161615138"><a name="p19997161615138"></a><a name="p19997161615138"></a><a name="image899718166134"></a><a name="image899718166134"></a><span><img id="image899718166134" src="figures/right-112.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.7 "><p id="p18997131671315"><a name="p18997131671315"></a><a name="p18997131671315"></a><a name="image1399711161130"></a><a name="image1399711161130"></a><span><img id="image1399711161130" src="figures/right-113.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.8 "><p id="p19998141611316"><a name="p19998141611316"></a><a name="p19998141611316"></a><a name="image149983164137"></a><a name="image149983164137"></a><span><img id="image149983164137" src="figures/right-114.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.9 "><p id="p1899891618139"><a name="p1899891618139"></a><a name="p1899891618139"></a><a name="image14998151619133"></a><a name="image14998151619133"></a><span><img id="image14998151619133" src="figures/right-115.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.10 "><p id="p1998191613131"><a name="p1998191613131"></a><a name="p1998191613131"></a><a name="image1099821618132"></a><a name="image1099821618132"></a><span><img id="image1099821618132" src="figures/right-116.png"></span></p>
</td>
</tr>
<tr id="row105821938104613"><td class="cellrowborder" rowspan="2" valign="top" headers="mcps1.1.13.1.1 "><p id="p12582113824610"><a name="p12582113824610"></a><a name="p12582113824610"></a>sports</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.1 "><p id="p145821538124613"><a name="p145821538124613"></a><a name="p145821538124613"></a>outdoor 户外运动、爬山、骑车等</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.2 "><p id="p1497941719235"><a name="p1497941719235"></a><a name="p1497941719235"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.3 "><p id="p1198082772318"><a name="p1198082772318"></a><a name="p1198082772318"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.4 "><p id="p9520184110235"><a name="p9520184110235"></a><a name="p9520184110235"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.5 "><p id="p1353514414236"><a name="p1353514414236"></a><a name="p1353514414236"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.6 "><p id="p51157329136"><a name="p51157329136"></a><a name="p51157329136"></a><a name="image17115832171314"></a><a name="image17115832171314"></a><span><img id="image17115832171314" src="figures/right-117.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.7 "><p id="p121151632181315"><a name="p121151632181315"></a><a name="p121151632181315"></a><a name="image1115232121315"></a><a name="image1115232121315"></a><span><img id="image1115232121315" src="figures/right-118.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.8 "><p id="p31154324133"><a name="p31154324133"></a><a name="p31154324133"></a><a name="image51155323132"></a><a name="image51155323132"></a><span><img id="image51155323132" src="figures/right-119.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.9 "><p id="p1411543210136"><a name="p1411543210136"></a><a name="p1411543210136"></a><a name="image2115832141314"></a><a name="image2115832141314"></a><span><img id="image2115832141314" src="figures/right-120.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.10 "><p id="p3115133281314"><a name="p3115133281314"></a><a name="p3115133281314"></a><a name="image1011563218136"></a><a name="image1011563218136"></a><span><img id="image1011563218136" src="figures/right-121.png"></span></p>
</td>
</tr>
<tr id="row2583038164615"><td class="cellrowborder" valign="top" headers="mcps1.1.13.1.1 "><p id="p1958314387462"><a name="p1958314387462"></a><a name="p1958314387462"></a>other 保龄球、游泳等</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.1 "><p id="p39941317192315"><a name="p39941317192315"></a><a name="p39941317192315"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.2 "><p id="p18996227102319"><a name="p18996227102319"></a><a name="p18996227102319"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.3 "><p id="p12549114172316"><a name="p12549114172316"></a><a name="p12549114172316"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.4 "><p id="p156434122318"><a name="p156434122318"></a><a name="p156434122318"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.5 "><p id="p11151432171318"><a name="p11151432171318"></a><a name="p11151432171318"></a><a name="image811583218133"></a><a name="image811583218133"></a><span><img id="image811583218133" src="figures/right-122.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.6 "><p id="p13115153216132"><a name="p13115153216132"></a><a name="p13115153216132"></a><a name="image1211517322135"></a><a name="image1211517322135"></a><span><img id="image1211517322135" src="figures/right-123.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.7 "><p id="p2115232131314"><a name="p2115232131314"></a><a name="p2115232131314"></a><a name="image8115163211313"></a><a name="image8115163211313"></a><span><img id="image8115163211313" src="figures/right-124.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.8 "><p id="p511603211131"><a name="p511603211131"></a><a name="p511603211131"></a><a name="image11116103214132"></a><a name="image11116103214132"></a><span><img id="image11116103214132" src="figures/right-125.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.9 "><p id="p10116132121316"><a name="p10116132121316"></a><a name="p10116132121316"></a><a name="image21161632121311"></a><a name="image21161632121311"></a><span><img id="image21161632121311" src="figures/right-126.png"></span></p>
</td>
</tr>
<tr id="row175831038104614"><td class="cellrowborder" valign="top" headers="mcps1.1.13.1.1 "><p id="p558310388464"><a name="p558310388464"></a><a name="p558310388464"></a>natural</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.1 "><p id="p15831138124619"><a name="p15831138124619"></a><a name="p15831138124619"></a>山峰、森林等</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.2 "><p id="p1310161812232"><a name="p1310161812232"></a><a name="p1310161812232"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.3 "><p id="p11112815239"><a name="p11112815239"></a><a name="p11112815239"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.4 "><p id="p195791941142313"><a name="p195791941142313"></a><a name="p195791941142313"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.5 "><p id="p1594154112318"><a name="p1594154112318"></a><a name="p1594154112318"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.6 "><p id="p201167328137"><a name="p201167328137"></a><a name="p201167328137"></a><a name="image1311663215132"></a><a name="image1311663215132"></a><span><img id="image1311663215132" src="figures/right-127.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.7 "><p id="p101165321131"><a name="p101165321131"></a><a name="p101165321131"></a><a name="image11116143261318"></a><a name="image11116143261318"></a><span><img id="image11116143261318" src="figures/right-128.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.8 "><p id="p8116632201315"><a name="p8116632201315"></a><a name="p8116632201315"></a><a name="image6116173211138"></a><a name="image6116173211138"></a><span><img id="image6116173211138" src="figures/right-129.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.9 "><p id="p181161032171315"><a name="p181161032171315"></a><a name="p181161032171315"></a><a name="image111693271313"></a><a name="image111693271313"></a><span><img id="image111693271313" src="figures/right-130.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.10 "><p id="p14116173211315"><a name="p14116173211315"></a><a name="p14116173211315"></a><a name="image3116832101313"></a><a name="image3116832101313"></a><span><img id="image3116832101313" src="figures/right-131.png"></span></p>
</td>
</tr>
<tr id="row1058463844617"><td class="cellrowborder" rowspan="7" valign="top" width="10.452090418083618%" headers="mcps1.1.13.1.1 "><p id="p2058403815464"><a name="p2058403815464"></a><a name="p2058403815464"></a>road</p>
</td>
<td class="cellrowborder" rowspan="2" valign="top" width="9.661932386477297%" headers="mcps1.1.13.1.1 "><p id="p458417385467"><a name="p458417385467"></a><a name="p458417385467"></a>highway</p>
</td>
<td class="cellrowborder" valign="top" width="12.20244048809762%" headers="mcps1.1.13.1.2 "><p id="p75841438194612"><a name="p75841438194612"></a><a name="p75841438194612"></a>country 国家高速</p>
</td>
<td class="cellrowborder" valign="top" width="10.552110422084418%" headers="mcps1.1.13.1.3 "><p id="p17133587142"><a name="p17133587142"></a><a name="p17133587142"></a><a name="image16133582144"></a><a name="image16133582144"></a><span><img id="image16133582144" src="figures/right-132.png"></span></p>
</td>
<td class="cellrowborder" valign="top" width="7.701540308061613%" headers="mcps1.1.13.1.4 "><p id="p1013378101418"><a name="p1013378101418"></a><a name="p1013378101418"></a><a name="image15133148181418"></a><a name="image15133148181418"></a><span><img id="image15133148181418" src="figures/right-133.png"></span></p>
</td>
<td class="cellrowborder" valign="top" width="6.05121024204841%" headers="mcps1.1.13.1.5 "><p id="p51331483141"><a name="p51331483141"></a><a name="p51331483141"></a><a name="image613415812145"></a><a name="image613415812145"></a><span><img id="image613415812145" src="figures/right-134.png"></span></p>
</td>
<td class="cellrowborder" valign="top" width="7.061412282456492%" headers="mcps1.1.13.1.6 "><p id="p21341682142"><a name="p21341682142"></a><a name="p21341682142"></a><a name="image313418141413"></a><a name="image313418141413"></a><span><img id="image313418141413" src="figures/right-135.png"></span></p>
</td>
<td class="cellrowborder" valign="top" width="7.041408281656332%" headers="mcps1.1.13.1.7 "><p id="p121341583142"><a name="p121341583142"></a><a name="p121341583142"></a><a name="image1413418871415"></a><a name="image1413418871415"></a><span><img id="image1413418871415" src="figures/right-136.png"></span></p>
</td>
<td class="cellrowborder" valign="top" width="7.051410282056411%" headers="mcps1.1.13.1.8 "><p id="p0370161815148"><a name="p0370161815148"></a><a name="p0370161815148"></a><a name="image437011801417"></a><a name="image437011801417"></a><span><img id="image437011801417" src="figures/right-137.png"></span></p>
</td>
<td class="cellrowborder" valign="top" width="6.931386277255452%" headers="mcps1.1.13.1.9 "><p id="p1737015180142"><a name="p1737015180142"></a><a name="p1737015180142"></a><a name="image93707187149"></a><a name="image93707187149"></a><span><img id="image93707187149" src="figures/right-138.png"></span></p>
</td>
<td class="cellrowborder" valign="top" width="6.481296259251851%" headers="mcps1.1.13.1.10 "><p id="p17370151814147"><a name="p17370151814147"></a><a name="p17370151814147"></a><a name="image13701718171412"></a><a name="image13701718171412"></a><span><img id="image13701718171412" src="figures/right-139.png"></span></p>
</td>
<td class="cellrowborder" valign="top" width="8.811762352470495%" headers="mcps1.1.13.1.11 "><p id="p63701418201415"><a name="p63701418201415"></a><a name="p63701418201415"></a><a name="image15370418141418"></a><a name="image15370418141418"></a><span><img id="image15370418141418" src="figures/right-140.png"></span></p>
</td>
</tr>
<tr id="row10584143814467"><td class="cellrowborder" valign="top" headers="mcps1.1.13.1.1 "><p id="p55841438114613"><a name="p55841438114613"></a><a name="p55841438114613"></a>city 城市高速</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.1 "><p id="p1561789171417"><a name="p1561789171417"></a><a name="p1561789171417"></a><a name="image56177921418"></a><a name="image56177921418"></a><span><img id="image56177921418" src="figures/right-141.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.2 "><p id="p166178917145"><a name="p166178917145"></a><a name="p166178917145"></a><a name="image186174941413"></a><a name="image186174941413"></a><span><img id="image186174941413" src="figures/right-142.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.3 "><p id="p76173914144"><a name="p76173914144"></a><a name="p76173914144"></a><a name="image1561718915145"></a><a name="image1561718915145"></a><span><img id="image1561718915145" src="figures/right-143.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.4 "><p id="p661714921415"><a name="p661714921415"></a><a name="p661714921415"></a><a name="image46171891146"></a><a name="image46171891146"></a><span><img id="image46171891146" src="figures/right-144.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.5 "><p id="p46188911144"><a name="p46188911144"></a><a name="p46188911144"></a><a name="image136184920143"></a><a name="image136184920143"></a><span><img id="image136184920143" src="figures/right-145.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.6 "><p id="p16370318151411"><a name="p16370318151411"></a><a name="p16370318151411"></a><a name="image15370171861415"></a><a name="image15370171861415"></a><span><img id="image15370171861415" src="figures/right-146.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.7 "><p id="p1137014186145"><a name="p1137014186145"></a><a name="p1137014186145"></a><a name="image737011891416"></a><a name="image737011891416"></a><span><img id="image737011891416" src="figures/right-147.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.8 "><p id="p1237010187141"><a name="p1237010187141"></a><a name="p1237010187141"></a><a name="image13371161881419"></a><a name="image13371161881419"></a><span><img id="image13371161881419" src="figures/right-148.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.9 "><p id="p63711186144"><a name="p63711186144"></a><a name="p63711186144"></a><a name="image637161810143"></a><a name="image637161810143"></a><span><img id="image637161810143" src="figures/right-149.png"></span></p>
</td>
</tr>
<tr id="row1658543814465"><td class="cellrowborder" valign="top" headers="mcps1.1.13.1.1 "><p id="p15585738164611"><a name="p15585738164611"></a><a name="p15585738164611"></a>national</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.1 "><p id="p75851938184610"><a name="p75851938184610"></a><a name="p75851938184610"></a>国道</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.2 "><p id="p61931161514"><a name="p61931161514"></a><a name="p61931161514"></a><a name="image6197111517"></a><a name="image6197111517"></a><span><img id="image6197111517" src="figures/right-150.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.3 "><p id="p1619191141512"><a name="p1619191141512"></a><a name="p1619191141512"></a><a name="image1919210159"></a><a name="image1919210159"></a><span><img id="image1919210159" src="figures/right-151.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.4 "><p id="p201919110154"><a name="p201919110154"></a><a name="p201919110154"></a><a name="image16199111513"></a><a name="image16199111513"></a><span><img id="image16199111513" src="figures/right-152.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.5 "><p id="p141961171514"><a name="p141961171514"></a><a name="p141961171514"></a><a name="image11191713157"></a><a name="image11191713157"></a><span><img id="image11191713157" src="figures/right-153.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.6 "><p id="p131913131514"><a name="p131913131514"></a><a name="p131913131514"></a><a name="image92031171518"></a><a name="image92031171518"></a><span><img id="image92031171518" src="figures/right-154.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.7 "><p id="p620181191513"><a name="p620181191513"></a><a name="p620181191513"></a><a name="image102051181511"></a><a name="image102051181511"></a><span><img id="image102051181511" src="figures/right-155.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.8 "><p id="p12016181518"><a name="p12016181518"></a><a name="p12016181518"></a><a name="image11201111514"></a><a name="image11201111514"></a><span><img id="image11201111514" src="figures/right-156.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.9 "><p id="p4203113155"><a name="p4203113155"></a><a name="p4203113155"></a><a name="image15202119153"></a><a name="image15202119153"></a><span><img id="image15202119153" src="figures/right-157.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.10 "><p id="p172020111513"><a name="p172020111513"></a><a name="p172020111513"></a><a name="image192011114151"></a><a name="image192011114151"></a><span><img id="image192011114151" src="figures/right-158.png"></span></p>
</td>
</tr>
<tr id="row25851938124614"><td class="cellrowborder" valign="top" headers="mcps1.1.13.1.1 "><p id="p2585338184611"><a name="p2585338184611"></a><a name="p2585338184611"></a>province</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.1 "><p id="p185851338194616"><a name="p185851338194616"></a><a name="p185851338194616"></a>省道</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.2 "><p id="p9201115155"><a name="p9201115155"></a><a name="p9201115155"></a><a name="image02012117157"></a><a name="image02012117157"></a><span><img id="image02012117157" src="figures/right-159.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.3 "><p id="p12015191513"><a name="p12015191513"></a><a name="p12015191513"></a><a name="image12071161511"></a><a name="image12071161511"></a><span><img id="image12071161511" src="figures/right-160.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.4 "><p id="p2020111181510"><a name="p2020111181510"></a><a name="p2020111181510"></a><a name="image132091201517"></a><a name="image132091201517"></a><span><img id="image132091201517" src="figures/right-161.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.5 "><p id="p20204131510"><a name="p20204131510"></a><a name="p20204131510"></a><a name="image192041121520"></a><a name="image192041121520"></a><span><img id="image192041121520" src="figures/right-162.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.6 "><p id="p11201517151"><a name="p11201517151"></a><a name="p11201517151"></a><a name="image10201712155"></a><a name="image10201712155"></a><span><img id="image10201712155" src="figures/right-163.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.7 "><p id="p92110151515"><a name="p92110151515"></a><a name="p92110151515"></a><a name="image15217119151"></a><a name="image15217119151"></a><span><img id="image15217119151" src="figures/right-164.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.8 "><p id="p112114121514"><a name="p112114121514"></a><a name="p112114121514"></a><a name="image11211917157"></a><a name="image11211917157"></a><span><img id="image11211917157" src="figures/right-165.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.9 "><p id="p142141111510"><a name="p142141111510"></a><a name="p142141111510"></a><a name="image021111181512"></a><a name="image021111181512"></a><span><img id="image021111181512" src="figures/right-166.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.10 "><p id="p8211131517"><a name="p8211131517"></a><a name="p8211131517"></a><a name="image132116112154"></a><a name="image132116112154"></a><span><img id="image132116112154" src="figures/right-167.png"></span></p>
</td>
</tr>
<tr id="row205861038134620"><td class="cellrowborder" valign="top" headers="mcps1.1.13.1.1 "><p id="p158616381466"><a name="p158616381466"></a><a name="p158616381466"></a>city-arterial</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.1 "><p id="p458623874616"><a name="p458623874616"></a><a name="p458623874616"></a>市区内交通要道</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.2 "><p id="p1272692171517"><a name="p1272692171517"></a><a name="p1272692171517"></a><a name="image772642101510"></a><a name="image772642101510"></a><span><img id="image772642101510" src="figures/right-168.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.3 "><p id="p1372632118158"><a name="p1372632118158"></a><a name="p1372632118158"></a><a name="image97271721171512"></a><a name="image97271721171512"></a><span><img id="image97271721171512" src="figures/right-169.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.4 "><p id="p07274215150"><a name="p07274215150"></a><a name="p07274215150"></a><a name="image147271221111517"></a><a name="image147271221111517"></a><span><img id="image147271221111517" src="figures/right-170.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.5 "><p id="p9727162121513"><a name="p9727162121513"></a><a name="p9727162121513"></a><a name="image472712115158"></a><a name="image472712115158"></a><span><img id="image472712115158" src="figures/right-171.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.6 "><p id="p57271921111517"><a name="p57271921111517"></a><a name="p57271921111517"></a><a name="image16727142121510"></a><a name="image16727142121510"></a><span><img id="image16727142121510" src="figures/right-172.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.7 "><p id="p12727172110159"><a name="p12727172110159"></a><a name="p12727172110159"></a><a name="image1727192116154"></a><a name="image1727192116154"></a><span><img id="image1727192116154" src="figures/right-173.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.8 "><p id="p1672752119156"><a name="p1672752119156"></a><a name="p1672752119156"></a><a name="image1872719214156"></a><a name="image1872719214156"></a><span><img id="image1872719214156" src="figures/right-174.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.9 "><p id="p1172792116151"><a name="p1172792116151"></a><a name="p1172792116151"></a><a name="image127274218158"></a><a name="image127274218158"></a><span><img id="image127274218158" src="figures/right-175.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.10 "><p id="p1866214572246"><a name="p1866214572246"></a><a name="p1866214572246"></a>-</p>
</td>
</tr>
<tr id="row185861938194613"><td class="cellrowborder" valign="top" headers="mcps1.1.13.1.1 "><p id="p16586238164616"><a name="p16586238164616"></a><a name="p16586238164616"></a>minor-road</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.1 "><p id="p1758611385467"><a name="p1758611385467"></a><a name="p1758611385467"></a>市区内支线等</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.2 "><p id="p93291023181512"><a name="p93291023181512"></a><a name="p93291023181512"></a><a name="image2032913232153"></a><a name="image2032913232153"></a><span><img id="image2032913232153" src="figures/right-176.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.3 "><p id="p6329102312152"><a name="p6329102312152"></a><a name="p6329102312152"></a><a name="image332962381512"></a><a name="image332962381512"></a><span><img id="image332962381512" src="figures/right-177.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.4 "><p id="p133291523111513"><a name="p133291523111513"></a><a name="p133291523111513"></a><a name="image43291023181510"></a><a name="image43291023181510"></a><span><img id="image43291023181510" src="figures/right-178.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.5 "><p id="p1329102371512"><a name="p1329102371512"></a><a name="p1329102371512"></a><a name="image9329202371515"></a><a name="image9329202371515"></a><span><img id="image9329202371515" src="figures/right-179.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.6 "><p id="p632992351510"><a name="p632992351510"></a><a name="p632992351510"></a><a name="image532918237156"></a><a name="image532918237156"></a><span><img id="image532918237156" src="figures/right-180.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.7 "><p id="p13329102316152"><a name="p13329102316152"></a><a name="p13329102316152"></a><a name="image1132972317155"></a><a name="image1132972317155"></a><span><img id="image1132972317155" src="figures/right-181.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.8 "><p id="p532992371516"><a name="p532992371516"></a><a name="p532992371516"></a><a name="image532920235159"></a><a name="image532920235159"></a><span><img id="image532920235159" src="figures/right-182.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.9 "><p id="p133291823101515"><a name="p133291823101515"></a><a name="p133291823101515"></a><a name="image93291323191517"></a><a name="image93291323191517"></a><span><img id="image93291323191517" src="figures/right-183.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.10 "><p id="p76778572240"><a name="p76778572240"></a><a name="p76778572240"></a>-</p>
</td>
</tr>
<tr id="row458703819462"><td class="cellrowborder" valign="top" headers="mcps1.1.13.1.1 "><p id="p19587143817466"><a name="p19587143817466"></a><a name="p19587143817466"></a>sidewalk</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.1 "><p id="p55871738164615"><a name="p55871738164615"></a><a name="p55871738164615"></a>人行道</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.2 "><p id="p16636142411510"><a name="p16636142411510"></a><a name="p16636142411510"></a><a name="image16636172401511"></a><a name="image16636172401511"></a><span><img id="image16636172401511" src="figures/right-184.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.3 "><p id="p2636112417156"><a name="p2636112417156"></a><a name="p2636112417156"></a><a name="image26369249153"></a><a name="image26369249153"></a><span><img id="image26369249153" src="figures/right-185.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.4 "><p id="p76361224141512"><a name="p76361224141512"></a><a name="p76361224141512"></a><a name="image06361242155"></a><a name="image06361242155"></a><span><img id="image06361242155" src="figures/right-186.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.5 "><p id="p26361724151513"><a name="p26361724151513"></a><a name="p26361724151513"></a><a name="image12636192481514"></a><a name="image12636192481514"></a><span><img id="image12636192481514" src="figures/right-187.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.6 "><p id="p136372244150"><a name="p136372244150"></a><a name="p136372244150"></a><a name="image163782410154"></a><a name="image163782410154"></a><span><img id="image163782410154" src="figures/right-188.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.7 "><p id="p66376248152"><a name="p66376248152"></a><a name="p66376248152"></a><a name="image17637132491519"></a><a name="image17637132491519"></a><span><img id="image17637132491519" src="figures/right-189.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.8 "><p id="p1063719246151"><a name="p1063719246151"></a><a name="p1063719246151"></a><a name="image46371824121517"></a><a name="image46371824121517"></a><span><img id="image46371824121517" src="figures/right-190.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.9 "><p id="p963702471519"><a name="p963702471519"></a><a name="p963702471519"></a><a name="image1863722412159"></a><a name="image1863722412159"></a><span><img id="image1863722412159" src="figures/right-191.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.10 "><p id="p0692155716243"><a name="p0692155716243"></a><a name="p0692155716243"></a>-</p>
</td>
</tr>
<tr id="row958763884615"><td class="cellrowborder" rowspan="7" valign="top" width="10.452090418083618%" headers="mcps1.1.13.1.1 "><p id="p12587538174614"><a name="p12587538174614"></a><a name="p12587538174614"></a>transit</p>
</td>
<td class="cellrowborder" valign="top" width="9.661932386477297%" headers="mcps1.1.13.1.1 "><p id="p558713381465"><a name="p558713381465"></a><a name="p558713381465"></a>railway</p>
</td>
<td class="cellrowborder" valign="top" width="12.20244048809762%" headers="mcps1.1.13.1.2 "><p id="p25871038194618"><a name="p25871038194618"></a><a name="p25871038194618"></a>铁路线、高铁线</p>
</td>
<td class="cellrowborder" valign="top" width="10.552110422084418%" headers="mcps1.1.13.1.3 "><p id="p15702163814155"><a name="p15702163814155"></a><a name="p15702163814155"></a><a name="image270211382156"></a><a name="image270211382156"></a><span><img id="image270211382156" src="figures/right-192.png"></span></p>
</td>
<td class="cellrowborder" valign="top" width="7.701540308061613%" headers="mcps1.1.13.1.4 "><p id="p2383184081516"><a name="p2383184081516"></a><a name="p2383184081516"></a><a name="image15383194031519"></a><a name="image15383194031519"></a><span><img id="image15383194031519" src="figures/right-193.png"></span></p>
</td>
<td class="cellrowborder" valign="top" width="6.05121024204841%" headers="mcps1.1.13.1.5 "><p id="p12840941111519"><a name="p12840941111519"></a><a name="p12840941111519"></a><a name="image08404416151"></a><a name="image08404416151"></a><span><img id="image08404416151" src="figures/right-194.png"></span></p>
</td>
<td class="cellrowborder" valign="top" width="7.061412282456492%" headers="mcps1.1.13.1.6 "><p id="p01469435155"><a name="p01469435155"></a><a name="p01469435155"></a><a name="image4146174321517"></a><a name="image4146174321517"></a><span><img id="image4146174321517" src="figures/right-195.png"></span></p>
</td>
<td class="cellrowborder" valign="top" width="7.041408281656332%" headers="mcps1.1.13.1.7 "><p id="p18197184411535"><a name="p18197184411535"></a><a name="p18197184411535"></a>-</p>
</td>
<td class="cellrowborder" valign="top" width="7.051410282056411%" headers="mcps1.1.13.1.8 "><p id="p25990196245"><a name="p25990196245"></a><a name="p25990196245"></a>-</p>
</td>
<td class="cellrowborder" valign="top" width="6.931386277255452%" headers="mcps1.1.13.1.9 "><p id="p147203271547"><a name="p147203271547"></a><a name="p147203271547"></a>-</p>
</td>
<td class="cellrowborder" valign="top" width="6.481296259251851%" headers="mcps1.1.13.1.10 "><p id="p13121184811194"><a name="p13121184811194"></a><a name="p13121184811194"></a>-</p>
</td>
<td class="cellrowborder" valign="top" width="8.811762352470495%" headers="mcps1.1.13.1.11 "><p id="p7709057172416"><a name="p7709057172416"></a><a name="p7709057172416"></a>-</p>
</td>
</tr>
<tr id="row1058883874614"><td class="cellrowborder" valign="top" headers="mcps1.1.13.1.1 "><p id="p15881738194612"><a name="p15881738194612"></a><a name="p15881738194612"></a>rail-station</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.1 "><p id="p85881638194610"><a name="p85881638194610"></a><a name="p85881638194610"></a>火车站、高铁站</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.2 "><p id="p1990111449151"><a name="p1990111449151"></a><a name="p1990111449151"></a><a name="image179011344161514"></a><a name="image179011344161514"></a><span><img id="image179011344161514" src="figures/right-196.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.3 "><p id="p8797448182316"><a name="p8797448182316"></a><a name="p8797448182316"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.4 "><p id="p1874418514233"><a name="p1874418514233"></a><a name="p1874418514233"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.5 "><p id="p8761751132318"><a name="p8761751132318"></a><a name="p8761751132318"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.6 "><p id="p14727135361517"><a name="p14727135361517"></a><a name="p14727135361517"></a><a name="image67271853161519"></a><a name="image67271853161519"></a><span><img id="image67271853161519" src="figures/right-197.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.7 "><p id="p1799395419156"><a name="p1799395419156"></a><a name="p1799395419156"></a><a name="image299315545159"></a><a name="image299315545159"></a><span><img id="image299315545159" src="figures/right-198.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.8 "><p id="p129616414169"><a name="p129616414169"></a><a name="p129616414169"></a><a name="image1629614410161"></a><a name="image1629614410161"></a><span><img id="image1629614410161" src="figures/right-199.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.9 "><p id="p754665121618"><a name="p754665121618"></a><a name="p754665121618"></a><a name="image14546758167"></a><a name="image14546758167"></a><span><img id="image14546758167" src="figures/right-200.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.10 "><p id="p13656106121615"><a name="p13656106121615"></a><a name="p13656106121615"></a><a name="image965612610169"></a><a name="image965612610169"></a><span><img id="image965612610169" src="figures/right-201.png"></span></p>
</td>
</tr>
<tr id="row1358873817464"><td class="cellrowborder" valign="top" headers="mcps1.1.13.1.1 "><p id="p14588103812461"><a name="p14588103812461"></a><a name="p14588103812461"></a>ferry-line</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.1 "><p id="p14588123817462"><a name="p14588123817462"></a><a name="p14588123817462"></a>航线</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.2 "><p id="p1878124561513"><a name="p1878124561513"></a><a name="p1878124561513"></a><a name="image17781114551518"></a><a name="image17781114551518"></a><span><img id="image17781114551518" src="figures/right-202.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.3 "><p id="p48135487232"><a name="p48135487232"></a><a name="p48135487232"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.4 "><p id="p77761351142313"><a name="p77761351142313"></a><a name="p77761351142313"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.5 "><p id="p11791751142313"><a name="p11791751142313"></a><a name="p11791751142313"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.6 "><p id="p143357871616"><a name="p143357871616"></a><a name="p143357871616"></a><a name="image233528151617"></a><a name="image233528151617"></a><span><img id="image233528151617" src="figures/right-203.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.7 "><p id="p169551991165"><a name="p169551991165"></a><a name="p169551991165"></a><a name="image14955149161617"></a><a name="image14955149161617"></a><span><img id="image14955149161617" src="figures/right-204.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.8 "><p id="p18496151110160"><a name="p18496151110160"></a><a name="p18496151110160"></a><a name="image3497101121616"></a><a name="image3497101121616"></a><span><img id="image3497101121616" src="figures/right-205.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.9 "><p id="p11829612121616"><a name="p11829612121616"></a><a name="p11829612121616"></a><a name="image128291012131614"></a><a name="image128291012131614"></a><span><img id="image128291012131614" src="figures/right-206.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.10 "><p id="p1643215542410"><a name="p1643215542410"></a><a name="p1643215542410"></a>-</p>
</td>
</tr>
<tr id="row1458883874615"><td class="cellrowborder" valign="top" headers="mcps1.1.13.1.1 "><p id="p058911389463"><a name="p058911389463"></a><a name="p058911389463"></a>ferry-terminal</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.1 "><p id="p15589103817463"><a name="p15589103817463"></a><a name="p15589103817463"></a>港口</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.2 "><p id="p157075465159"><a name="p157075465159"></a><a name="p157075465159"></a><a name="image2707246111512"></a><a name="image2707246111512"></a><span><img id="image2707246111512" src="figures/right-207.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.3 "><p id="p08299484235"><a name="p08299484235"></a><a name="p08299484235"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.4 "><p id="p1480813517237"><a name="p1480813517237"></a><a name="p1480813517237"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.5 "><p id="p10823135116238"><a name="p10823135116238"></a><a name="p10823135116238"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.6 "><p id="p1586721401617"><a name="p1586721401617"></a><a name="p1586721401617"></a><a name="image9867614201618"></a><a name="image9867614201618"></a><span><img id="image9867614201618" src="figures/right-208.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.7 "><p id="p983611571611"><a name="p983611571611"></a><a name="p983611571611"></a><a name="image483641519169"></a><a name="image483641519169"></a><span><img id="image483641519169" src="figures/right-209.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.8 "><p id="p14895181611614"><a name="p14895181611614"></a><a name="p14895181611614"></a><a name="image489518161168"></a><a name="image489518161168"></a><span><img id="image489518161168" src="figures/right-210.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.9 "><p id="p119579173164"><a name="p119579173164"></a><a name="p119579173164"></a><a name="image10957121761616"></a><a name="image10957121761616"></a><span><img id="image10957121761616" src="figures/right-211.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.10 "><p id="p17439101910162"><a name="p17439101910162"></a><a name="p17439101910162"></a><a name="image5439191951613"></a><a name="image5439191951613"></a><span><img id="image5439191951613" src="figures/right-212.png"></span></p>
</td>
</tr>
<tr id="row195891538104611"><td class="cellrowborder" valign="top" headers="mcps1.1.13.1.1 "><p id="p17589163884610"><a name="p17589163884610"></a><a name="p17589163884610"></a>airport</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.1 "><p id="p11589123824614"><a name="p11589123824614"></a><a name="p11589123824614"></a>机场</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.2 "><p id="p3472134810151"><a name="p3472134810151"></a><a name="p3472134810151"></a><a name="image447274841514"></a><a name="image447274841514"></a><span><img id="image447274841514" src="figures/right-213.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.3 "><p id="p4851124817232"><a name="p4851124817232"></a><a name="p4851124817232"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.4 "><p id="p18392051112310"><a name="p18392051112310"></a><a name="p18392051112310"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.5 "><p id="p158555511236"><a name="p158555511236"></a><a name="p158555511236"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.6 "><p id="p0847321111615"><a name="p0847321111615"></a><a name="p0847321111615"></a><a name="image11847192171614"></a><a name="image11847192171614"></a><span><img id="image11847192171614" src="figures/right-214.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.7 "><p id="p840211237169"><a name="p840211237169"></a><a name="p840211237169"></a><a name="image14021423181617"></a><a name="image14021423181617"></a><span><img id="image14021423181617" src="figures/right-215.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.8 "><p id="p13435192413165"><a name="p13435192413165"></a><a name="p13435192413165"></a><a name="image15435172441618"></a><a name="image15435172441618"></a><span><img id="image15435172441618" src="figures/right-216.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.9 "><p id="p1032122591613"><a name="p1032122591613"></a><a name="p1032122591613"></a><a name="image10321625171618"></a><a name="image10321625171618"></a><span><img id="image10321625171618" src="figures/right-217.png"></span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.10 "><p id="p891919307162"><a name="p891919307162"></a><a name="p891919307162"></a><a name="image11919163011612"></a><a name="image11919163011612"></a><span><img id="image11919163011612" src="figures/right-218.png"></span></p>
</td>
</tr>
<tr id="row18589838144612"><td class="cellrowborder" valign="top" headers="mcps1.1.13.1.1 "><p id="p6589153854612"><a name="p6589153854612"></a><a name="p6589153854612"></a>bus-station</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.1 "><p id="p75894381467"><a name="p75894381467"></a><a name="p75894381467"></a>公交车站</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.2 "><p id="p8848645182317"><a name="p8848645182317"></a><a name="p8848645182317"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.3 "><p id="p1987414487238"><a name="p1987414487238"></a><a name="p1987414487238"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.4 "><p id="p387045112235"><a name="p387045112235"></a><a name="p387045112235"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.5 "><p id="p68870516231"><a name="p68870516231"></a><a name="p68870516231"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.6 "><p id="p17639193845313"><a name="p17639193845313"></a><a name="p17639193845313"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.7 "><p id="p1642918072412"><a name="p1642918072412"></a><a name="p1642918072412"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.8 "><p id="p1736783917194"><a name="p1736783917194"></a><a name="p1736783917194"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.9 "><p id="p9190204881910"><a name="p9190204881910"></a><a name="p9190204881910"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.10 "><p id="p1011833218167"><a name="p1011833218167"></a><a name="p1011833218167"></a><a name="image18118632111610"></a><a name="image18118632111610"></a><span><img id="image18118632111610" src="figures/right-219.png"></span></p>
</td>
</tr>
<tr id="row125905384467"><td class="cellrowborder" valign="top" headers="mcps1.1.13.1.1 "><p id="p14590173854614"><a name="p14590173854614"></a><a name="p14590173854614"></a>other</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.1 "><p id="p1459013834617"><a name="p1459013834617"></a><a name="p1459013834617"></a>出租车、出入口等</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.2 "><p id="p387434562313"><a name="p387434562313"></a><a name="p387434562313"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.3 "><p id="p18901148192311"><a name="p18901148192311"></a><a name="p18901148192311"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.4 "><p id="p59068511233"><a name="p59068511233"></a><a name="p59068511233"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.5 "><p id="p199231512238"><a name="p199231512238"></a><a name="p199231512238"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.6 "><p id="p36541738155313"><a name="p36541738155313"></a><a name="p36541738155313"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.7 "><p id="p12444908248"><a name="p12444908248"></a><a name="p12444908248"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.8 "><p id="p4388173981911"><a name="p4388173981911"></a><a name="p4388173981911"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.9 "><p id="p720474811913"><a name="p720474811913"></a><a name="p720474811913"></a>-</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.13.1.10 "><p id="p8265103312169"><a name="p8265103312169"></a><a name="p8265103312169"></a><a name="image1226663371616"></a><a name="image1226663371616"></a><span><img id="image1226663371616" src="figures/right-220.png"></span></p>
</td>
</tr>
<tr id="row1859063810465"><td class="cellrowborder" valign="top" width="10.452090418083618%" headers="mcps1.1.13.1.1 "><p id="p459013389468"><a name="p459013389468"></a><a name="p459013389468"></a>water</p>
</td>
<td class="cellrowborder" valign="top" width="9.661932386477297%" headers="mcps1.1.13.1.1 "><p id="p95901038124611"><a name="p95901038124611"></a><a name="p95901038124611"></a>-</p>
</td>
<td class="cellrowborder" valign="top" width="12.20244048809762%" headers="mcps1.1.13.1.2 "><p id="p10590183819464"><a name="p10590183819464"></a><a name="p10590183819464"></a>水系、海洋、湖泊、河流</p>
</td>
<td class="cellrowborder" valign="top" width="10.552110422084418%" headers="mcps1.1.13.1.3 "><p id="p1572045021516"><a name="p1572045021516"></a><a name="p1572045021516"></a><a name="image1272055061512"></a><a name="image1272055061512"></a><span><img id="image1272055061512" src="figures/right-221.png"></span></p>
</td>
<td class="cellrowborder" valign="top" width="7.701540308061613%" headers="mcps1.1.13.1.4 "><p id="p7904154812320"><a name="p7904154812320"></a><a name="p7904154812320"></a>-</p>
</td>
<td class="cellrowborder" valign="top" width="6.05121024204841%" headers="mcps1.1.13.1.5 "><p id="p993935132311"><a name="p993935132311"></a><a name="p993935132311"></a>-</p>
</td>
<td class="cellrowborder" valign="top" width="7.061412282456492%" headers="mcps1.1.13.1.6 "><p id="p169573519233"><a name="p169573519233"></a><a name="p169573519233"></a>-</p>
</td>
<td class="cellrowborder" valign="top" width="7.041408281656332%" headers="mcps1.1.13.1.7 "><p id="p4230153771613"><a name="p4230153771613"></a><a name="p4230153771613"></a><a name="image023012373168"></a><a name="image023012373168"></a><span><img id="image023012373168" src="figures/right-222.png"></span></p>
</td>
<td class="cellrowborder" valign="top" width="7.051410282056411%" headers="mcps1.1.13.1.8 "><p id="p19621434121616"><a name="p19621434121616"></a><a name="p19621434121616"></a><a name="image129628343167"></a><a name="image129628343167"></a><span><img id="image129628343167" src="figures/right-223.png"></span></p>
</td>
<td class="cellrowborder" valign="top" width="6.931386277255452%" headers="mcps1.1.13.1.9 "><p id="p159860406202"><a name="p159860406202"></a><a name="p159860406202"></a>-</p>
</td>
<td class="cellrowborder" valign="top" width="6.481296259251851%" headers="mcps1.1.13.1.10 "><p id="p10462443132012"><a name="p10462443132012"></a><a name="p10462443132012"></a>-</p>
</td>
<td class="cellrowborder" valign="top" width="8.811762352470495%" headers="mcps1.1.13.1.11 "><p id="p107827232412"><a name="p107827232412"></a><a name="p107827232412"></a>-</p>
</td>
</tr>
</tbody>
</table>

>![](public_sys-resources/icon-note.gif) **说明：** 
>-   图标类型icon-type支持范围为：standard/night/simple。
>-   饱和度Saturation和亮度Lightness可在元素颜色Color中进行配置。

