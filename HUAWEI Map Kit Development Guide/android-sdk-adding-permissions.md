# Adding Permissions<a name="EN-US_TOPIC_0000001145523601"></a>

To call capabilities of Map Kit, you must apply for the following permissions for your app in the  **AndroidManifest.xml**  file:

```
<!-- Allow the app to access Internet.-->
<uses-permission android:name="android.permission.INTERNET"/>
<!--Allow the app to query the network status.-->
<uses-permission android:name="android.permission.ACCESS_NETWORK_STATE"/>
<!-- Allow the app to read common data. -->
<uses-permission android:name="com.huawei.appmarket.service.commondata.permission.GET_COMMON_DATA"/>
```

To obtain the current device location, you need to add the following permissions to the  **AndroidManifest.xml**  file. In Android 6.0 and later, you need to apply for these permissions dynamically.

```
<!-- Allow the app to obtain the coarse longitude and latitude of a user through the Wi-Fi network or base station. -->
<uses-permission android:name="android.permission.ACCESS_COARSE_LOCATION"/>
<!-- Allow the app to receive location information from satellites through the GPS chip. -->
<uses-permission android:name="android.permission.ACCESS_FINE_LOCATION"/>
```

