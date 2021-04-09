# 使用入门<a name="ZH-CN_TOPIC_0000001145781035"></a>

-   [快速上手](#section8992121481312)
-   [开发环境](#s845eec131f9e42549dac39748969abc4)
-   [开发流程](#section18946774278)

## 快速上手<a name="section8992121481312"></a>

本节点是向Android应用添加地图的[快速入门指南](https://developer.huawei.com/consumer/cn/codelab/HMSMapKit/index.html#0)，在快速入门指南中，您可以学到以下内容：

-   在开发者联盟中配置地图相关App。
-   从开发者联盟的Map服务开发者文档获取地图Demo代码。
-   使用Android Studio集成Map SDK进行地图功能开发。
-   构建地图并展示。

## 开发环境<a name="s845eec131f9e42549dac39748969abc4"></a>

-   安装Android Studio 3.3及以上

-   JDK 1.8及以上
-   您的应用应满足以下条件：

    -   minSdkVersion 19
    -   targetSdkVersion 29
    -   compileSdkVersion 29
    -   Gradle 3.5.3及以上

-   测试应用的设备：EMUI 5.0及以上的华为手机或Android 7.0及以上的非华为手机。


## 开发流程<a name="section18946774278"></a>

您需要按照如下流程完成应用的开发工作。

<a name="table4122153120269"></a>
<table><thead align="left"><tr id="row15305163112618"><th class="cellrowborder" align="center" valign="top" width="7.620762076207621%" id="mcps1.1.4.1.1"><p id="p19280142664212"><a name="p19280142664212"></a><a name="p19280142664212"></a>序号</p>
</th>
<th class="cellrowborder" valign="top" width="28.9028902890289%" id="mcps1.1.4.1.2"><p id="p830511312266"><a name="p830511312266"></a><a name="p830511312266"></a>步骤</p>
</th>
<th class="cellrowborder" valign="top" width="63.47634763476348%" id="mcps1.1.4.1.3"><p id="p103051631192618"><a name="p103051631192618"></a><a name="p103051631192618"></a>说明</p>
</th>
</tr>
</thead>
<tbody><tr id="row103051431182612"><td class="cellrowborder" align="center" valign="top" width="7.620762076207621%" headers="mcps1.1.4.1.1 "><p id="p1483673810243"><a name="p1483673810243"></a><a name="p1483673810243"></a>1</p>
</td>
<td class="cellrowborder" valign="top" width="28.9028902890289%" headers="mcps1.1.4.1.2 "><p id="p27011313104416"><a name="p27011313104416"></a><a name="p27011313104416"></a><a href="android-sdk-config-agc.md">配置AppGallery Connect</a></p>
</td>
<td class="cellrowborder" valign="top" width="63.47634763476348%" headers="mcps1.1.4.1.3 "><p id="p1483220153314"><a name="p1483220153314"></a><a name="p1483220153314"></a>在开发应用前，需要在<a href="https://developer.huawei.com/consumer/cn/service/josp/agc/index.html" target="_blank" rel="noopener noreferrer">AppGallery Connect</a>中配置相关信息。包括：<a href="android-sdk-config-agc.md#section47264296">注册成为开发者</a>、<a href="android-sdk-config-agc.md#section83893131911">创建项目</a>、<a href="android-sdk-config-agc.md#section0592162815915">创建应用</a>、<a href="android-sdk-config-agc.md#section147011294331">生成签名证书指纹</a>、<a href="android-sdk-config-agc.md#section4972271336">配置签名证书指纹</a>、<a href="android-sdk-config-agc.md#section58097464">打开相关服务</a>。</p>
</td>
</tr>
<tr id="row1730663162618"><td class="cellrowborder" align="center" valign="top" width="7.620762076207621%" headers="mcps1.1.4.1.1 "><p id="p683543822413"><a name="p683543822413"></a><a name="p683543822413"></a>2</p>
</td>
<td class="cellrowborder" valign="top" width="28.9028902890289%" headers="mcps1.1.4.1.2 "><p id="p530693118266"><a name="p530693118266"></a><a name="p530693118266"></a><a href="android-sdk-integrating-sdk.md">集成HMS Core SDK</a></p>
</td>
<td class="cellrowborder" valign="top" width="63.47634763476348%" headers="mcps1.1.4.1.3 "><p id="p17184513165"><a name="p17184513165"></a><a name="p17184513165"></a>在开发应用前，您需要将HMS Core SDK集成到您的开发环境中。</p>
</td>
</tr>
<tr id="row215818418196"><td class="cellrowborder" align="center" valign="top" width="7.620762076207621%" headers="mcps1.1.4.1.1 "><p id="p13834938192418"><a name="p13834938192418"></a><a name="p13834938192418"></a>3</p>
</td>
<td class="cellrowborder" valign="top" width="28.9028902890289%" headers="mcps1.1.4.1.2 "><p id="p161581145192"><a name="p161581145192"></a><a name="p161581145192"></a><a href="android-sdk-config-obfuscation-scripts.md">配置混淆脚本</a></p>
</td>
<td class="cellrowborder" valign="top" width="63.47634763476348%" headers="mcps1.1.4.1.3 "><p id="p415816401912"><a name="p415816401912"></a><a name="p415816401912"></a>编译APK前需要配置混淆配置文件，避免混淆HMS Core SDK导致功能异常。</p>
</td>
</tr>
<tr id="row14808202071911"><td class="cellrowborder" rowspan="4" align="center" valign="top" width="7.620762076207621%" headers="mcps1.1.4.1.1 "><p id="p1315711211110"><a name="p1315711211110"></a><a name="p1315711211110"></a>4</p>
</td>
<td class="cellrowborder" valign="top" width="28.9028902890289%" headers="mcps1.1.4.1.2 "><p id="p149471455191912"><a name="p149471455191912"></a><a name="p149471455191912"></a><a href="android-sdk-map-creation-overview.md">创建地图</a></p>
</td>
<td class="cellrowborder" valign="top" width="63.47634763476348%" headers="mcps1.1.4.1.3 "><p id="p133911750181919"><a name="p133911750181919"></a><a name="p133911750181919"></a>使用地图容器快速地获得地图对象，并改变地图类型、在地图上显示<span class="parmvalue" id="parmvalue77565293319"><a name="parmvalue77565293319"></a><a name="parmvalue77565293319"></a>“我的位置”</span>，以及开启地图的精简模式等。</p>
</td>
</tr>
<tr id="row734019881617"><td class="cellrowborder" valign="top" headers="mcps1.1.4.1.1 "><p id="p1534116891612"><a name="p1534116891612"></a><a name="p1534116891612"></a><a href="android-sdk-map-interaction-overview.md">地图交互</a></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.4.1.2 "><p id="p19341280165"><a name="p19341280165"></a><a name="p19341280165"></a><span>通过控制内置UI控件的显示以及允许哪些手势来自定义用户与地图交互的方式。</span></p>
</td>
</tr>
<tr id="row13302593166"><td class="cellrowborder" valign="top" headers="mcps1.1.4.1.1 "><p id="p16302794162"><a name="p16302794162"></a><a name="p16302794162"></a><a href="android-sdk-drawing-map-overview.md">在地图上绘制</a></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.4.1.2 "><p id="p230209131615"><a name="p230209131615"></a><a name="p230209131615"></a><span>在地图上绘制标记、覆盖物以及形状等。</span></p>
</td>
</tr>
<tr id="row17240217151612"><td class="cellrowborder" valign="top" headers="mcps1.1.4.1.1 "><p id="p15241717191617"><a name="p15241717191617"></a><a name="p15241717191617"></a><a href="android-sdk-map-style-customization-overview.md">自定义地图样式</a></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.4.1.2 "><p id="p42411117141614"><a name="p42411117141614"></a><a name="p42411117141614"></a>在应用中添加自定义风格的地图。</p>
</td>
</tr>
<tr id="row067021715166"><td class="cellrowborder" align="center" valign="top" width="7.620762076207621%" headers="mcps1.1.4.1.1 "><p id="p1670717111616"><a name="p1670717111616"></a><a name="p1670717111616"></a>5</p>
</td>
<td class="cellrowborder" valign="top" width="28.9028902890289%" headers="mcps1.1.4.1.2 "><p id="p146701617101612"><a name="p146701617101612"></a><a name="p146701617101612"></a><a href="google-maps-to-map-kit.md">从Google Maps迁移到HUAWEI Map Kit</a></p>
</td>
<td class="cellrowborder" valign="top" width="63.47634763476348%" headers="mcps1.1.4.1.3 "><p id="p1167015173169"><a name="p1167015173169"></a><a name="p1167015173169"></a>从最基本的环境配置开始，介绍如何将Android应用程序从Google Maps SDK for Android切换到Map Kit提供的SDK for Android。</p>
</td>
</tr>
<tr id="row14390150111916"><td class="cellrowborder" align="center" valign="top" width="7.620762076207621%" headers="mcps1.1.4.1.1 "><p id="p1983273816248"><a name="p1983273816248"></a><a name="p1983273816248"></a>6</p>
</td>
<td class="cellrowborder" valign="top" width="28.9028902890289%" headers="mcps1.1.4.1.2 "><p id="p2306133132615"><a name="p2306133132615"></a><a name="p2306133132615"></a><a href="pre-release-check.md">开发后自检</a></p>
</td>
<td class="cellrowborder" valign="top" width="63.47634763476348%" headers="mcps1.1.4.1.3 "><p id="p1130619315263"><a name="p1130619315263"></a><a name="p1130619315263"></a>华为提供对应用自动检查的能力。</p>
</td>
</tr>
<tr id="row930610316269"><td class="cellrowborder" align="center" valign="top" width="7.620762076207621%" headers="mcps1.1.4.1.1 "><p id="p1831133882417"><a name="p1831133882417"></a><a name="p1831133882417"></a>7</p>
</td>
<td class="cellrowborder" valign="top" width="28.9028902890289%" headers="mcps1.1.4.1.2 "><p id="p5306123192610"><a name="p5306123192610"></a><a name="p5306123192610"></a><a href="app-release.md">上架申请</a></p>
</td>
<td class="cellrowborder" valign="top" width="63.47634763476348%" headers="mcps1.1.4.1.3 "><p id="p0306123115265"><a name="p0306123115265"></a><a name="p0306123115265"></a>开发完成后需要在<a href="https://developer.huawei.com/consumer/cn/service/josp/agc/index.html" target="_blank" rel="noopener noreferrer">AppGallery Connect</a>中将应用信息补充完整并提交上架申请。</p>
</td>
</tr>
</tbody>
</table>

如果您已有集成第三方移动服务的应用程序，可以使用[HMS Toolkit](https://developer.huawei.com/consumer/cn/huawei-toolkit/)提供的Convertor工具将第三方移动服务相关的API接口自动转换为HMS Core相对应的API接口，实现快速转换和集成HMS Core的能力。

