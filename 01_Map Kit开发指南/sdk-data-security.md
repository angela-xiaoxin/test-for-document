# SDK数据安全说明<a name="ZH-CN_TOPIC_0000001099661070"></a>

-   [SDK工作方式](#section124962819524)
-   [SDK权限说明](#section15489113619524)
-   [SDK数据收集](#section18210529528)
-   [SDK数据安全保护](#section59571517533)

## SDK工作方式<a name="section124962819524"></a>

Map SDK在应用打包时会被加载在您的应用当中，SDK会随着用户应用的启动而启动。当用户关闭应用时，SDK会随着客户应用的关闭而关闭，不会在后台做额外动作。

## SDK权限说明<a name="section15489113619524"></a>

SDK需要以下权限，但已在内部对其进行了预设，因此开发人员无需再申请权限。其余功能不需要：

-   获取网络状态权限：android.permission.**ACCESS\_NETWORK\_STATE**，用于检测当前的网络连接是否有效。
-   获取Wi-Fi状态权限：android.permission.**ACCESS\_WIFI\_STATE**，用于获取当前Wi-Fi接入的状态以及WLAN热点的信息。

## SDK数据收集<a name="section18210529528"></a>

SDK会使用您应用的appid、包名和接口调用情况，用于牵引Map服务能力的持续优化和改进。

SDK不会收集用户个人数据。

## SDK数据安全保护<a name="section59571517533"></a>

SDK不会收集用户个人数据。

