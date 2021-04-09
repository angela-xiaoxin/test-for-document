# FAQ<a name="ZH-CN_TOPIC_0000001145781005"></a>

-   [Android SDK](#section193511931172712)
    -   [鉴权成功，但onMapReady没有回调？](#section1991391419284)
    -   [目前Map Kit各个服务是否支持中国大陆？](#section575392093016)
    -   [Map Kit提供的Android SDK是否支持地图的横竖屏切换？](#section18979181011321)
    -   [如果出现下面的错误，要怎么处理？](#section240091511320)
    -   [返回错误码010001或010002或010003可能的原因？](#section1817194262911)
    -   [调用BitmapDescriptorFactory.fromResource\(int\)发生空指针异常？](#section6660927203220)
    -   [返回错误码010010的可能原因？](#section432949201910)
    -   [Android SDK设置我的位置按钮隐藏不生效？](#section15538229121711)
    -   [如何保护API Key？](#section8487183365413)
    -   [地图加载出来前会闪现缩放图标，如何规避？](#section112363496406)

-   [JavaScript API](#section7377623173215)
    -   [目前Map Kit各个服务是否支持中国大陆？](#section15294819193711)
    -   [返回错误码010024的原因？](#section2066381513498)
    -   [返回错误码010027的原因？](#section224819328403)

-   [REST API](#section35174614325)
    -   [目前Map Kit各个服务是否支持中国大陆？](#section161933384521)
    -   [调用Web API返回错误码6的原因？](#section9358141913329)
    -   [返回错误码010024的原因？](#section1983141718433)
    -   [返回错误码010027的原因？](#section3299143320474)


如果您在下面没有找到需要的问题，请加入[Stack Overflow](https://stackoverflow.com/questions/tagged/huawei-mobile-services?tab=Newest)社区参与讨论。

## Android SDK<a name="section193511931172712"></a>

### 鉴权成功，但onMapReady没有回调？<a name="section1991391419284"></a>

如果使用MapView，请查看生命周期方法是否完整调用。

### 目前Map Kit各个服务是否支持中国大陆？<a name="section575392093016"></a>

Map Kit的地图数据覆盖不支持中国大陆，所以Android SDK、JavaScript API、Static Map API以及Directions API功能模块不支持中国大陆，支持的范围请参见[支持的国家/地区](supported-countries-and-regions.md)。

### Map Kit提供的Android SDK是否支持地图的横竖屏切换？<a name="section18979181011321"></a>

不支持。

### 如果出现下面的错误，要怎么处理？<a name="section240091511320"></a>

```
Duplicate class com.huawei.secure.android.common.ssl.R found in modules r-classes.jar (com.huawei.agconnect:agconnect-credential:1.3.0.300) and r-classes.jar (com.huawei.hms:maps-base:4.0.0.301)
```

解决方式：需要升级Map Kit Android SDK版本到4.0.1.302及以上。

### 返回错误码010001或010002或010003可能的原因？<a name="section1817194262911"></a>

-   项目中App ID与[AppGallery Connect](https://developer.huawei.com/consumer/cn/service/josp/agc/index.html)上不一致。
-   未配置指纹。需在本地生成签名证书指纹，然后在[AppGallery Connect](https://developer.huawei.com/consumer/cn/service/josp/agc/index.html)中配置。
-   未配置应用的[AppGallery Connect](https://developer.huawei.com/consumer/cn/service/josp/agc/index.html)配置文件，参见[添加当前应用的AppGallery Connect配置文件](android-sdk-integrating-sdk.md#section4256162815361)。
-   API Key没有使用encode转码。

### 调用BitmapDescriptorFactory.fromResource\(int\)发生空指针异常？<a name="section6660927203220"></a>

异常堆栈：

```
E/HmsMapKit_CrashHandler_79: uncaughtException stacktrace is java.lang.NullPointerException: Attempt to invoke virtual method 'android.content.res.Resources android.content.Context.getResources()' on a null object reference
```

解决方式：

在使用BitmapDescriptorFactory之前调用MapsInitializer.initialize\(this.getApplicationContext\(\)\)或者MapsInitializer.initialize\(this\)。

### 返回错误码010010的可能原因？<a name="section432949201910"></a>

日志中搜到“responseBody is returnCode: 010010; resultInfo : unkown error.”并且日志中有“MapClientDataImpl.getAppId\(\) is:  ，”。

该问题是App ID没有取到，可以在AndroidManifest.xml的application标签下添加：

```
<meta-data
	android:name="com.huawei.hms.client.appid"
	android:value="appid=*****9011" />
```

### Android SDK设置我的位置按钮隐藏不生效？<a name="section15538229121711"></a>

需要在onMapReady中设置：

```
hmap.setMyLocationEnabled(false);
hmap.getUiSettings().setMyLocationButtonEnabled(false);
```

### 如何保护API Key？<a name="section8487183365413"></a>

1.  监控收费API的额度消费情况，以及设置消费提醒。

    详情查看[服务定价与订购](https://developer.huawei.com/consumer/cn/doc/development/AppGallery-connect-Guides/agc-service-billing)中的“查看您的账户详情“、“查看项目服务SKU月详情费用“、“查看项目服务SKU日详情费用“和“设置消费提醒“指导文档。

2.  不再使用的API Key及时删除。

### 地图加载出来前会闪现缩放图标，如何规避？<a name="section112363496406"></a>

Android 8以下设备在地图加载出来前会闪现缩放图标（Android 8为低概率偶现，Android 8以上正常显示）。

目前，您可以通过如下两种方式规避上述闪现问题：

-   XML方式设置：将uiZoomControls属性设置为false。
-   代码方式设置：将[HuaweiMapOptions](zh-cn_topic_0000001099661076.md).[zoomControlsEnabled](zh-cn_topic_0000001099661076.md#section937192082118)\(boolean isZoomControlsEnabled\)方法参数设置为false。

## JavaScript API<a name="section7377623173215"></a>

### 目前Map Kit各个服务是否支持中国大陆？<a name="section15294819193711"></a>

Map Kit的地图数据覆盖不支持中国大陆，所以Android SDK、JavaScript API、Static Map API以及Directions API功能模块不支持中国大陆，支持的范围请参见[支持的国家/地区](supported-countries-and-regions.md)。

### 返回错误码010024的原因？<a name="section2066381513498"></a>

010024表示接口已经欠费，需要在“我的项目 \> 我的套餐”中对欠费的服务进行充值。

### 返回错误码010027的原因？<a name="section224819328403"></a>

010027表示未订购付费套餐，有两种可能情况：

1.  您未通过[AppGallery Connect](https://developer.huawei.com/consumer/cn/service/josp/agc/index.html)创建项目。检查使用的API Key是否在[AppGallery Connect](https://developer.huawei.com/consumer/cn/service/josp/agc/index.html)存在，如果不存在重新到[AppGallery Connect](https://developer.huawei.com/consumer/cn/service/josp/agc/index.html)上创建项目和应用，使用应用的API Key作为认证凭证。
2.  您未升级到付费档。请到“[我的项目](https://developer.huawei.com/consumer/cn/service/josp/agc/index.html#/myProject)  \> 我的套餐”，进行套餐升级。

## REST API<a name="section35174614325"></a>

### 目前Map Kit各个服务是否支持中国大陆？<a name="section161933384521"></a>

Map Kit的地图数据覆盖不支持中国大陆，所以Android SDK、JavaScript API、Static Map API以及Directions API功能模块不支持中国大陆，支持的范围请参见[支持的国家/地区](supported-countries-and-regions.md)。

### 调用Web API返回错误码6的原因？<a name="section9358141913329"></a>

可能原因是API Key中包含特殊字符，此时需要对特殊字符编码进行encodeURI编码。例如：原始API Key：ABC/DFG+ ，转换结果：ABC%2FDFG%2B。

### 返回错误码010024的原因？<a name="section1983141718433"></a>

010024表示接口已经欠费，需要在“我的项目 \> 我的套餐”中对欠费的服务进行充值。

### 返回错误码010027的原因？<a name="section3299143320474"></a>

010027表示未订购付费套餐，有两种可能情况：

1.  您未通过[AppGallery Connect](https://developer.huawei.com/consumer/cn/service/josp/agc/index.html)创建项目。检查使用的API Key是否在[AppGallery Connect](https://developer.huawei.com/consumer/cn/service/josp/agc/index.html)存在，如果不存在重新到[AppGallery Connect](https://developer.huawei.com/consumer/cn/service/josp/agc/index.html)上创建项目和应用，使用应用的API Key作为认证凭证。
2.  您未升级到付费档。请到“[我的项目](https://developer.huawei.com/consumer/cn/service/josp/agc/index.html#/myProject)  \> 我的套餐”，进行套餐升级。

