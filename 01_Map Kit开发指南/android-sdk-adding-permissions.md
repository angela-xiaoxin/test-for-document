# 添加权限<a name="ZH-CN_TOPIC_0000001145860977"></a>

您调用地图服务能力，必须在AndroidManifest中为您的应用添加下列权限：

```
<!--允许程序访问网络连接-->
<uses-permission android:name="android.permission.INTERNET"/>
<!--允许程序获取网络信息状态-->
<uses-permission android:name="android.permission.ACCESS_NETWORK_STATE"/>
<!--自定义权限，允许程序读取公共数据-->
<uses-permission android:name="com.huawei.appmarket.service.commondata.permission.GET_COMMON_DATA"/>
```

获取设备当前位置需要在AndroidManifest中增加以下权限，且Android 6.0以后需动态申请：

```
<!--允许程序通过Wi-Fi或移动基站的方式获取用户粗略的经纬度信息-->
<uses-permission android:name="android.permission.ACCESS_COARSE_LOCATION"/>
<!--允许程序通过GPS芯片接收卫星的定位信息-->
<uses-permission android:name="android.permission.ACCESS_FINE_LOCATION"/>
```

