# 地点搜索建议<a name="ZH-CN_TOPIC_0000001099341060"></a>

-   [实现步骤](#section05671521114112)
-   [示例代码](#section1715816329413)

该功能可用于在用户键入查询内容的时候，实时地返回建议的查询结果，从而实现查询预测效果。

## 实现步骤<a name="section05671521114112"></a>

1.  通过HWMapJsSDK初始化[HWSiteService](zh-cn_topic_0000001099181268.md)对象。
2.  构建搜索的请求体request对象，其中query是必选参数，其余可选，politicalView参数已废弃。
    -   query：搜索关键字。
    -   location：搜索结果偏向的经纬度。
    -   radius：搜索半径，单位：米。取值范围：\[1, 50000\]，默认50000米。
    -   bounds：搜索结果偏向的范围。
    -   poiType：返回指定POI类型的地点。
    -   countryCode：在指定的国家内搜索，采用ISO 3166-1 alpha-2。
    -   language：搜索结果的语种。如果不指定语种，使用地点的当地语言。
    -   countries：多个国家码，采用ISO 3166-1 alpha-2规范的2位国家码。
    -   politicalView：政治观点参数，采用ISO 3166-1 alpha-2规范的2位国家码，该参数已废弃。

3.  通过第1步创建的[HWSiteService](zh-cn_topic_0000001099181268.md)对象调用querySuggestion接口，传入第2步创建的request对象。
4.  获取搜索结果。通过第3步querySuggestion接口的回调函数返回搜索结果result和搜索状态status。status参见[错误码](zh-cn_topic_0000001145780991.md)，result包含以下对象：

    sites：返回5条搜索结果[Site](zh-cn_topic_0000001145860985.md#s60f796f99e2a42589d569ce7de36a113)\[\]，[Site](zh-cn_topic_0000001145860985.md#s60f796f99e2a42589d569ce7de36a113)描述参见[参数说明](zh-cn_topic_0000001145860985.md)。


## 示例代码<a name="section1715816329413"></a>

```
var map;
var mapOptions = {};
mapOptions.center = {lat: 48.856613, lng: 2.352222};
mapOptions.zoom = 15;
map = new HWMapJsSDK.HWMap(document.getElementById('map'), mapOptions);
var siteService
// 初始化HWSiteService对象
siteService = new HWMapJsSDK.HWSiteService();
// 初始化请求参数对象
var request = {
    query: "coffee"
};

siteService.querySuggestion(request, function (result, status) {
    if (status == '0') {
        for (var i = 0; i < result.sites.length; i++) {
            // 在地图上添加标记
            var marker = new HWMapJsSDK.HWMarker({
                map: map,
                position: {lat: result.sites[i].location.lat, lng: result.sites[i].location.lng},
                label: result.sites[i].name
            });
            // 设置地图的中心点
            map.setCenter({lat: result.sites[0].location.lat, lng: result.sites[0].location.lng})
        }
    }
});
```

