# 正地理编码<a name="ZH-CN_TOPIC_0000001145781009"></a>

-   [实现步骤](#section8420822175014)
-   [示例代码](#section48971631185010)

获取地址对应的经纬度，最多返回10条记录。

## 实现步骤<a name="section8420822175014"></a>

1.  通过HWMapJsSDK初始化[HWSiteService](zh-cn_topic_0000001099181268.md)对象。
2.  构建请求体request对象，其中address是必选参数，其余可选，politicalView参数已废弃：
    -   address：地点信息。
    -   bounds：查询结果偏向的搜索范围。
    -   language：搜索结果的语种。如果不指定语种，使用地点的当地语言。语种取值请参见[支持的语言](zh-cn_topic_0000001050162856.md)列表。
    -   politicalView：政治观点参数，采用ISO 3166-1 alpha-2规范的2位国家码，该参数已废弃。

3.  通过第1步创建的[HWSiteService](zh-cn_topic_0000001099181268.md)对象调用geocode接口，传入第2步创建的request对象。
4.  获取搜索结果。通过第3步geocode接口的回调函数返回搜索结果result和搜索状态status。status参见[错误码](zh-cn_topic_0000001145780991.md)，result包含以下对象：

    sites：返回10条搜索结果[Site](zh-cn_topic_0000001145860985.md#s60f796f99e2a42589d569ce7de36a113)\[\]，[Site](zh-cn_topic_0000001145860985.md#s60f796f99e2a42589d569ce7de36a113)描述请参见[参数说明](zh-cn_topic_0000001145860985.md)。


## 示例代码<a name="section48971631185010"></a>

```
<body>
    <div id="map"></div>
    <script>
        var markers = [];
        var map;
        var mapOptions = {};
        function initMap() {
            mapOptions.center = {lat: 48.856613, lng: 2.352222};
            mapOptions.zoom = 8;
            map = new HWMapJsSDK.HWMap(document.getElementById('map'), mapOptions);
            var siteService
            // 初始化HWSiteService对象
            siteService = new HWMapJsSDK.HWSiteService();
            // 初始化请求参数对象
            var request = {
                address: '57,RUE DU CAPITAINE PICAVET,LEERS,LEERS,NORD,HAUTS-DE-FRANCE,France'
            };
            // 调用正地理编码接口，result为返回结果，status为返回状态
            siteService.geocode(request, function (result, status) {
                if (status == '0') {
                    const res = result && result.sites && result.sites[0].location
                    if (res) {
                        // 添加标记
                        var marker = new HWMapJsSDK.HWMarker({
                            map: map,
                            position: {lat: res.lat, lng: res.lng},
                            label: result.sites[0].name
                        });
                        markers.push(marker);
                        // 设置地图中心位置
                        map.setCenter({lat: res.lat, lng: res.lng})
                    }
                }
            });
        }
    </script>
</body>
```

