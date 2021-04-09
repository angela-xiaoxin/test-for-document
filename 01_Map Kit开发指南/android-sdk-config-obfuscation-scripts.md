# 配置混淆脚本<a name="ZH-CN_TOPIC_0000001099661078"></a>

您编译APK前需要配置混淆配置文件，避免混淆HMS Core SDK导致功能异常。

1.  打开应用级根目录下的混淆配置文件“proguard-rules.pro“，需要加入排除HMS Core SDK的混淆配置。

    ```
    -ignorewarnings 
    -keepattributes *Annotation* 
    -keepattributes Exceptions 
    -keepattributes InnerClasses 
    -keepattributes Signature 
    -keepattributes SourceFile,LineNumberTable 
    -keep class com.huawei.hianalytics.**{*;} 
    -keep class com.huawei.updatesdk.**{*;} 
    -keep class com.huawei.hms.**{*;}
    ```

2.  如果您使用了AndResGuard，需要在混淆配置文件中加入AndResGuard允许清单。

    ```
    "R.string.agc*",
    "R.string.hms*", 
    "R.string.connect_server_fail_prompt_toast", 
    "R.string.getting_message_fail_prompt_toast", 
    "R.string.no_available_network_prompt_toast", 
    "R.string.third_app_*", 
    "R.string.upsdk_*", 
    "R.layout.hms*", 
    "R.layout.upsdk_*", 
    "R.drawable.upsdk*", 
    "R.color.upsdk*", 
    "R.dimen.upsdk*", 
    "R.style.upsdk*"
    ```


