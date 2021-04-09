# 版本更新说明<a name="ZH-CN_TOPIC_0000001099181272"></a>

-   [5.2.1.300（2021-04-08）](#section1975882984511)
-   [历史版本](#section185731027105216)
    -   [5.2.0.300（2021-03-09）](#section14977161811329)
    -   [5.1.1.300（2021-01-29）](#section197526615243)
    -   [5.1.0.300（2020-12-31）](#section41141212193417)
    -   [5.0.5.300（2020-11-27）](#section137948182311)
    -   [5.0.2.300（2020-09-18）](#section1293013818228)
    -   [5.0.1.300（2020-07-13）](#section1230951612514)
    -   [4.0.4.300（2020-05-25）](#section177811737194015)
    -   [4.0.3.300（2020-03-27）](#section3117143172416)
    -   [4.0.2.300（2020-03-12）](#section4293173412246)
    -   [4.0.1.300（2020-01-21）](#section10201151052417)
    -   [4.0.0.300（2019-12-30）](#section27214573129)


## 5.2.1.300（2021-04-08）<a name="section1975882984511"></a>

<a name="simpletable975892984513"></a>
<table id="simpletable975892984513"><tr id="strow1775982915454"><td valign="top" id="stentry107591529194518"><p id="p17759162914514"><a name="p17759162914514"></a><a name="p17759162914514"></a>本次JavaScript API特性变更如下：</p>
<p id="p10759152904514"><a name="p10759152904514"></a><a name="p10759152904514"></a><strong id="b275919296452"><a name="b275919296452"></a><a name="b275919296452"></a>新增特性</strong></p>
<a name="ul1365011262358"></a><a name="ul1365011262358"></a><ul id="ul1365011262358"><li><a href="zh-cn_topic_0000001099181268.md#sd7916193426041b1b9579296b161bba6">QuerySuggestionRequest</a>、<a href="zh-cn_topic_0000001099181268.md#s0636d688325540bab4ba4311b4092d9d">SearchByTextRequest</a>、<a href="zh-cn_topic_0000001099181234.md#sea3723661c23416abe76f745765cce56">AutocompleteOptions</a>新增countries属性，支持传入多个国家码。</li><li><a href="zh-cn_topic_0000001145860985.md#scff6465e40704ddf9d95d3572e9e61bc">Route</a>对象新增overviewPolyline属性，表示该路线的编码后的折线。</li><li>新增<a href="zh-cn_topic_0000001099661080.md">HWPolyUtils</a>经纬度编解码工具类。</li></ul>
</td>
</tr>
</table>

## 历史版本<a name="section185731027105216"></a>

### 5.2.0.300（2021-03-09）<a name="section14977161811329"></a>

<a name="simpletable1977111853213"></a>
<table id="simpletable1977111853213"><tr id="strow59771718153211"><td valign="top" id="stentry59771188328"><p id="p6977118123216"><a name="p6977118123216"></a><a name="p6977118123216"></a>本次JavaScript API特性变更如下：</p>
<p id="p597718182324"><a name="p597718182324"></a><a name="p597718182324"></a><strong id="b997701813320"><a name="b997701813320"></a><a name="b997701813320"></a>新增特性</strong></p>
<a name="ul3977151873219"></a><a name="ul3977151873219"></a>
<p id="p39778188325"><a name="p39778188325"></a><a name="p39778188325"></a><a href="zh-cn_topic_0000001145860985.md#scff6465e40704ddf9d95d3572e9e61bc">Route</a>对象新增hasRestrictedRoad、dstInRestrictedArea、crossCountry、crossMultiCountries、hasRoughRoad、dstInDiffTimeZone、hasFerry、hasTrafficLight、hasTolls、trafficLightNum属性。</p>
</td>
</tr>
</table>

### 5.1.1.300（2021-01-29）<a name="section197526615243"></a>

<a name="simpletable87520622417"></a>
<table id="simpletable87520622417"><tr id="strow157521863241"><td valign="top" id="stentry975218682417"><p id="p1998473919119"><a name="p1998473919119"></a><a name="p1998473919119"></a>本次JavaScript API特性变更如下：</p>
<p id="p1575213622414"><a name="p1575213622414"></a><a name="p1575213622414"></a><strong id="b157525602417"><a name="b157525602417"></a><a name="b157525602417"></a>新增特性</strong></p>
<p id="p16190193172414"><a name="p16190193172414"></a><a name="p16190193172414"></a><a href="zh-cn_topic_0000001145860979.md#s08ea7a96339f4dcf82f72b0e4bad2db5">MapOptions</a>新增参数sourceType，设置地图加载时使用的瓦片类型，支持vector（矢量）或raster（栅格）。</p>
</td>
</tr>
</table>

### 5.1.0.300（2020-12-31）<a name="section41141212193417"></a>

<a name="simpletable254010319355"></a>
<table id="simpletable254010319355"><tr id="strow7541103153518"><td valign="top" id="stentry135414383517"><p id="p2234162415110"><a name="p2234162415110"></a><a name="p2234162415110"></a>本次JavaScript API特性变更如下：</p>
<p id="p0664105543510"><a name="p0664105543510"></a><a name="p0664105543510"></a><strong id="b42441317646"><a name="b42441317646"></a><a name="b42441317646"></a>修改特性</strong></p>
<p id="p20421443292"><a name="p20421443292"></a><a name="p20421443292"></a><a href="zh-cn_topic_0000001099181268.md#s0636d688325540bab4ba4311b4092d9d">关键字搜索</a>、<a href="zh-cn_topic_0000001099181268.md#se147bc59b0194eda80de17c0bdaee77c">周边搜索</a>、<a href="zh-cn_topic_0000001099181268.md#s07869d36847f4dcd8b38d5428c2cafd4">地点详情</a>、<a href="zh-cn_topic_0000001099181268.md#sd7916193426041b1b9579296b161bba6">地点搜索建议</a>、<a href="zh-cn_topic_0000001099181234.md#sea3723661c23416abe76f745765cce56">自动补全</a>、<a href="zh-cn_topic_0000001099181268.md#sd5e3ac239f6a48689261e9d5f38b8641">正地理编码</a>、<a href="zh-cn_topic_0000001099181268.md#s871ce65677cc4e1dbfd1636c3b325d6f">逆地理编码</a>废弃politicalView参数。</p>
</td>
</tr>
</table>

### 5.0.5.300（2020-11-27）<a name="section137948182311"></a>

<a name="simpletable20376489231"></a>
<table id="simpletable20376489231"><tr id="strow938134852319"><td valign="top" id="stentry13815486239"><p id="p3490161618"><a name="p3490161618"></a><a name="p3490161618"></a>本次JavaScript API特性变更如下：</p>
<p id="p2381848132319"><a name="p2381848132319"></a><a name="p2381848132319"></a><strong id="b2384483230"><a name="b2384483230"></a><a name="b2384483230"></a>新增特性</strong></p>
<a name="ul138174810231"></a><a name="ul138174810231"></a><ul id="ul138174810231"><li>样例图片左下角新增Legal版权申明的Logo。</li><li>JavaScript API接口自2021年1月1日起变为收费接口，详情请参见<a href="about-charging.md">服务定价</a>。</li></ul>
</td>
</tr>
</table>

### 5.0.2.300（2020-09-18）<a name="section1293013818228"></a>

<a name="simpletable8930103842216"></a>
<table id="simpletable8930103842216"><tr id="strow17930138112215"><td valign="top" id="stentry6930183816222"><p id="p1766825320014"><a name="p1766825320014"></a><a name="p1766825320014"></a>本次JavaScript API特性变更如下：</p>
<p id="p49301338172218"><a name="p49301338172218"></a><a name="p49301338172218"></a><strong id="b1893093819229"><a name="b1893093819229"></a><a name="b1893093819229"></a>新增特性</strong></p>
<a name="ul993073811226"></a><a name="ul993073811226"></a><ul id="ul993073811226"><li>增加距离计算接口<a href="zh-cn_topic_0000001099341122.md">HWDistanceCalculator</a>。</li><li>自动补全控件的可选参数对象<a href="zh-cn_topic_0000001099181234.md#sea3723661c23416abe76f745765cce56">AutocompleteOptions</a>新增maxHeight、data、customHandler参数，支持自定义样式。</li></ul>
</td>
</tr>
</table>

### 5.0.1.300（2020-07-13）<a name="section1230951612514"></a>

<a name="simpletable33091516152518"></a>
<table id="simpletable33091516152518"><tr id="strow53091016112512"><td valign="top" id="stentry8309416152514"><p id="p205114423010"><a name="p205114423010"></a><a name="p205114423010"></a>本次JavaScript API特性变更如下：</p>
<p id="p103091616192517"><a name="p103091616192517"></a><a name="p103091616192517"></a><strong id="b73098167256"><a name="b73098167256"></a><a name="b73098167256"></a>新增特性</strong></p>
<p id="p16309181617256"><a name="p16309181617256"></a><a name="p16309181617256"></a>Web JavaScript移动端手势支持无缝调节比例尺。</p>
</td>
</tr>
</table>

### 4.0.4.300（2020-05-25）<a name="section177811737194015"></a>

<a name="simpletable152451705119"></a>
<table id="simpletable152451705119"><tr id="strow132459014110"><td valign="top" id="stentry6245301112"><p id="p93097321806"><a name="p93097321806"></a><a name="p93097321806"></a>本次JavaScript API特性变更如下：</p>
<p id="p520613684119"><a name="p520613684119"></a><a name="p520613684119"></a><strong id="b1626018110436"><a name="b1626018110436"></a><a name="b1626018110436"></a>新增特性</strong></p>
<a name="ul20146255113"></a><a name="ul20146255113"></a><ul id="ul20146255113"><li><a href="zh-cn_topic_0000001099341054.md">HWCircle</a>，<a href="zh-cn_topic_0000001145781037.md">HWPolyline</a>和<a href="zh-cn_topic_0000001099341096.md">HWPolygon</a>增加strokeLineDash属性。</li><li>地图控件增加位置按钮。</li><li>支持自定义地图样式能力。</li></ul>
</td>
</tr>
</table>

### 4.0.3.300（2020-03-27）<a name="section3117143172416"></a>

<a name="simpletable181171743132413"></a>
<table id="simpletable181171743132413"><tr id="strow181172431243"><td valign="top" id="stentry16117943192411"><p id="p2051110171209"><a name="p2051110171209"></a><a name="p2051110171209"></a>本次JavaScript API特性变更如下：</p>
<p id="p179061430182418"><a name="p179061430182418"></a><a name="p179061430182418"></a><strong id="b5906330102410"><a name="b5906330102410"></a><a name="b5906330102410"></a>新增特性</strong></p>
<a name="ul090617300240"></a><a name="ul090617300240"></a><ul id="ul090617300240"><li>新增Distance Matrix，支持<span>给定的出行方式来计算多个起点和目的地之间的出行距离和旅行持续时间。</span></li><li>新增当前位置控件和当前位置显示呈现。</li><li><a href="zh-cn_topic_0000001145860985.md#sfb73d14e02cb4b2ebab582421fa618a7">Path</a>、<a href="zh-cn_topic_0000001145860985.md#s6220d04bd11944c184eeb757cc11c0d9">Step</a>对象新增属性distanceText、durationText，补齐距离和时长的文字指引相关信息。</li><li><a href="zh-cn_topic_0000001145860985.md#sfb73d14e02cb4b2ebab582421fa618a7">Path</a>对象新增属性durationInTrafficText，提供基于实时路况计算出来的行驶时长的文字指引。</li><li><a href="zh-cn_topic_0000001145860985.md#s6220d04bd11944c184eeb757cc11c0d9">Step</a>对象新增属性instruction，提供步骤的文字指引。</li></ul>
</td>
</tr>
</table>

### 4.0.2.300（2020-03-12）<a name="section4293173412246"></a>

<a name="simpletable829483410245"></a>
<table id="simpletable829483410245"><tr id="strow4294183482411"><td valign="top" id="stentry132941934152410"><p id="p1599233818598"><a name="p1599233818598"></a><a name="p1599233818598"></a>本次JavaScript API特性变更如下：</p>
<p id="p4665144213539"><a name="p4665144213539"></a><a name="p4665144213539"></a><strong id="b366520425530"><a name="b366520425530"></a><a name="b366520425530"></a>新增特性</strong></p>
<a name="ul1166534215533"></a><a name="ul1166534215533"></a><ul id="ul1166534215533"><li><a href="zh-cn_topic_0000001099181268.md">HWSiteService</a>类新增searchByText方法，提供关键字搜索功能。</li><li><a href="zh-cn_topic_0000001099181268.md">HWSiteService</a>类新增nearbySearch方法，提供周边搜索功能。</li><li><a href="zh-cn_topic_0000001099181268.md">HWSiteService</a>类新增searchById方法，根据ID查询地址接口。</li><li><a href="zh-cn_topic_0000001099181268.md">HWSiteService</a>类新增querySuggestion方法，提供输入提示功能。</li><li>支持预置标准地图样式。</li></ul>
</td>
</tr>
</table>

### 4.0.1.300（2020-01-21）<a name="section10201151052417"></a>

<a name="simpletable5201171072417"></a>
<table id="simpletable5201171072417"><tr id="strow12201131018249"><td valign="top" id="stentry192011910112414"><p id="p14506410171314"><a name="p14506410171314"></a><a name="p14506410171314"></a>本次JavaScript API特性变更如下：</p>
<p id="p196631337173914"><a name="p196631337173914"></a><a name="p196631337173914"></a><strong id="b4663637123917"><a name="b4663637123917"></a><a name="b4663637123917"></a>新增特性</strong></p>
<a name="ul3663133713912"></a><a name="ul3663133713912"></a><ul id="ul3663133713912"><li>提供鉴权管理，新增支持API_key和Service Account鉴权方式，原WEB API接口中的AT，调整为API_key。</li><li>提供鼠标和手势动作支持。</li><li>新增<a href="zh-cn_topic_0000001145860955.md">Marker</a>类，支持在地图上添加标记点。</li><li>新增<a href="zh-cn_topic_0000001145780995.md">GroundOverlay</a>类，支持根据Bbox展示图片，自动填充。</li><li>支持路径规划能力（步行、骑行和驾车），您申请使用JavaScript API接口路径规划能力前需在同一个项目中开通Directions API能力。</li></ul>
</td>
</tr>
</table>

### 4.0.0.300（2019-12-30）<a name="section27214573129"></a>

<a name="simpletable472114571122"></a>
<table id="simpletable472114571122"><tr id="strow117217576128"><td valign="top" id="stentry17211573122"><p id="p1624581311315"><a name="p1624581311315"></a><a name="p1624581311315"></a>本次JavaScript API特性变更如下：</p>
<p id="p2394357193"><a name="p2394357193"></a><a name="p2394357193"></a><strong id="b27215579121"><a name="b27215579121"></a><a name="b27215579121"></a>新增特性</strong></p>
<p id="p106535772118"><a name="p106535772118"></a><a name="p106535772118"></a>地图服务提供JavaScript语言开发的应用编程接口，帮助您轻松完成适用于浏览器的地图应用开发。支持基础地图展示，绘制地图，地图交互等功能。</p>
</td>
</tr>
</table>

