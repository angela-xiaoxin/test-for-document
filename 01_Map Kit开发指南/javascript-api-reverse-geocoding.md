# 逆地理编码<a name="ZH-CN_TOPIC_0000001145860957"></a>

-   [实现步骤](#section524014583501)
-   [示例代码](#section686017745117)

获取经纬度对应的地点，最多返回11条记录。

## 实现步骤<a name="section524014583501"></a>

1.  通过HWMapJsSDK初始化[HWSiteService](zh-cn_topic_0000001099181268.md)对象。
2.  构建请求体request对象，其中location是必选参数，其余可选，politicalView参数已废弃：
    -   location：经纬度。
    -   language：搜索结果的语种。如果不指定语种，使用地点的当地语言。语种取值请参见[支持的语言](zh-cn_topic_0000001050162856.md)列表。
    -   politicalView：政治观点参数，采用ISO 3166-1 alpha-2规范的2位国家码，该参数已废弃。
    -   returnPoi：是否返回POI的地点名称，默认是true。

3.  通过第1步创建的[HWSiteService](zh-cn_topic_0000001099181268.md)对象调用reverseGeocode接口，传入第2步创建的request对象。
4.  获取搜索结果。通过第3步reverseGeocode接口的回调函数返回搜索结果result和搜索状态status。status请参见[错误码](zh-cn_topic_0000001145780991.md)，result包含以下对象：

    sites：最多返回11条搜索结果[Site](zh-cn_topic_0000001145860985.md#s60f796f99e2a42589d569ce7de36a113)\[\]，[Site](zh-cn_topic_0000001145860985.md#s60f796f99e2a42589d569ce7de36a113)描述请参见[参数说明](zh-cn_topic_0000001145860985.md)。注意Site对象不返回POI信息。


## 示例代码<a name="section686017745117"></a>

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
                location: {
                    lat: 18.0527,
                    lng: 77.2155
                }
            };
            // 调用逆地理编码接口，result为返回结果，status为返回状态
            siteService.reverseGeocode(request, function (result, status) {
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

