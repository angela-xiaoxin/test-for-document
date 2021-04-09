# 周边搜索<a name="ZH-CN_TOPIC_0000001099501088"></a>

-   [实现步骤](#section1562015393314)
-   [示例代码](#section28803277330)

通过用户传入自己的位置，可以返回周边地点列表，继而通过获取到的SiteID，可以查询该地点的详细信息。

## 实现步骤<a name="section1562015393314"></a>

1.  通过HWMapJsSDK初始化[HWSiteService](zh-cn_topic_0000001099181268.md)对象。
2.  构建搜索的请求体request对象，其中location是必选参数，其余可选，politicalView参数已废弃。
    -   location：用户当前的位置。
    -   radius：可以指定搜索半径，单位：米。取值范围：\[1, 50000\]，默认1000米。
    -   query：输入搜索关键字。
    -   poiType：返回指定POI类型的地点。
    -   language：搜索结果的语种。如果不指定语种，使用地点的当地语言。
    -   pageSize：每页返回的记录数。取值范围：\[1, 20\]，默认20。
    -   pageIndex：当前页数。取值范围：\[1, 60\]，默认1。
    -   politicalView：政治观点参数，采用ISO 3166-1 alpha-2规范的2位国家码，该参数已废弃。

3.  通过第1步创建的[HWSiteService](zh-cn_topic_0000001099181268.md)对象调用nearbySearch接口，传入第2步创建的request对象。
4.  获取搜索结果。通过第3步nearbySearch接口的回调函数返回搜索结果result和搜索状态status。status参见[错误码](zh-cn_topic_0000001145780991.md)，result包含以下对象：
    -   sites：搜索结果[Site](zh-cn_topic_0000001145860985.md#s60f796f99e2a42589d569ce7de36a113)\[\]，[Site](zh-cn_topic_0000001145860985.md#s60f796f99e2a42589d569ce7de36a113)描述参见[参数说明](zh-cn_topic_0000001145860985.md)。
    -   totalCount：记录总数。


## 示例代码<a name="section28803277330"></a>

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
	location: {
		lat: 48.893478,
		lng: 2.334595
	}
};
// 调用搜索接口，result为返回结果，status为返回状态
siteService.nearbySearch(request, function (result, status) {
	if (status == '0') {
		for (var i = 0; i < result.sites.length; i++) {
			// 在地图上添加标记
			var marker = new HWMapJsSDK.HWMarker({
				map: map,
				position: {lat: result.sites[i].location.lat, lng: result.sites[i].location.lng},
				label: result.sites[i].name
			});
		}
		// 设置地图的中心点
		map.setCenter({lat: result.sites[0].location.lat, lng: result.sites[0].location.lng})
	}
});
```

