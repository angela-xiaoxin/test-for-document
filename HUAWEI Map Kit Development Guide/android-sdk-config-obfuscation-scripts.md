# Configuring Obfuscation Scripts<a name="EN-US_TOPIC_0000001098683762"></a>

Before building the APK, configure the obfuscation configuration file to prevent the HMS Core SDK from being obfuscated.

1.  Open the obfuscation configuration file  **proguard-rules.pro**  in the  **app**  directory of your project, and add configurations to exclude the HMS Core SDK from obfuscation.

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

2.  If you are using AndResGuard, add its trustlist to the obfuscation configuration file.

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


