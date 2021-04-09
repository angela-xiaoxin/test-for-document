# 地址详情<a name="ZH-CN_TOPIC_0000001099661044"></a>

-   [实现步骤](#section188145510364)
-   [示例代码](#section12972209377)

您可以通过某一地点的Site ID来获取该地点的详细信息，Site ID是地点的唯一标识符。

## 实现步骤<a name="section188145510364"></a>

1.  通过HWMapJsSDK初始化[HWSiteService](zh-cn_topic_0000001099181268.md)对象。
2.  构建搜索的请求体request对象，传入以下参数，其中politicalView参数已废弃。
    -   siteId：地址ID，必选项。
    -   language：查询结果的语种，可选项。如果不指定语种，使用地点的当地语言。
    -   politicalView：政治观点参数，采用ISO 3166-1 alpha-2规范的2位国家码，该参数已废弃。

3.  通过第1步创建的[HWSiteService](zh-cn_topic_0000001099181268.md)对象调用searchById接口，传入第2步创建的request对象。
4.  获取搜索结果。通过第3步searchById接口的回调函数返回搜索结果result和搜索状态status。status参见[错误码](zh-cn_topic_0000001145780991.md)，result包含以下对象：

    site：搜索结果[Site](zh-cn_topic_0000001145860985.md#s60f796f99e2a42589d569ce7de36a113)，[Site](zh-cn_topic_0000001145860985.md#s60f796f99e2a42589d569ce7de36a113)描述参见[参数说明](zh-cn_topic_0000001145860985.md)。


## 示例代码<a name="section12972209377"></a>

```
var map;
var mapOptions = {};
mapOptions.zoom = 15;
map = new HWMapJsSDK.HWMap(document.getElementById('map'), mapOptions);
var siteService
// 初始化HWSiteService对象
siteService = new HWMapJsSDK.HWSiteService();
// 初始化请求参数对象
var request = {
    siteId: "F45411D2CC51C59156364492A8D13622"
};

siteService.searchById(request, function (result, status) {
    if (status == '0') {
        var marker = new HWMapJsSDK.HWMarker({
            map: map,
            position: {lat: result.site.location.lat, lng: result.site.location.lng},
            label: result.site.name
        });
        map.setCenter({lat: result.site.location.lat, lng: result.site.location.lng})
    }
});
```

