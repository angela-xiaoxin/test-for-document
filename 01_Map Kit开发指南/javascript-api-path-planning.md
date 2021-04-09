# 实现步骤<a name="ZH-CN_TOPIC_0000001099181266"></a>

1.  通过HWMapJsSDK初始化[HWDirectionsService](zh-cn_topic_0000001145941053.md)对象。
2.  构建路径规划的请求体request对象，必须传入起点经纬度和终点经纬度。
    -   origin：起点的经纬度。
    -   destination：终点的经纬度。

3.  通过第1步创建的[HWDirectionsService](zh-cn_topic_0000001145941053.md)对象调用路径规划接口，如驾车规划接口routeDriving，传入第2步创建的请求体，以及回调函数。
4.  定义路径规划的回调函数function\([DirectionsResult](zh-cn_topic_0000001145941053.md#s70691a88ea7b4be2aec22deb6a3f18e8), DirectionsStatus\)，[DirectionsResult](zh-cn_topic_0000001145941053.md#s70691a88ea7b4be2aec22deb6a3f18e8)是路径规划的结果，DirectionsStatus是返回码，当返回码为0时，表示获取结果成功。
5.  此时有多种方法展示路径规划结果，如使用绘制折线的功能，除此之外可以使用[HWDirectionsRenderer](zh-cn_topic_0000001145941069.md)渲染路径规划的结果，使用方法为[HWDirectionsRenderer](zh-cn_topic_0000001145941069.md).setDirections\([DirectionsResult](zh-cn_topic_0000001145941053.md#s70691a88ea7b4be2aec22deb6a3f18e8)\)。

