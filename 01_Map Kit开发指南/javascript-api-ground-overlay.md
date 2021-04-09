# 覆盖物<a name="ZH-CN_TOPIC_0000001099501054"></a>

-   [添加覆盖物](#section8130729132917)
-   [删除覆盖物](#section8879241103017)
-   [修改覆盖物](#section173661808318)

地图覆盖物是固定在地图上的图片。

## 添加覆盖物<a name="section8130729132917"></a>

用户可以使用HWMapJsSDK.[HWGroundOverlay](zh-cn_topic_0000001099661058.md)\(imageUrl, bounds, groundOverlayOptions\)构造方法创建一个标记添加到地图上，示例代码如下：

```
var map;
var mGroundOverlay;

function initMap() {
    var mapOptions = {};
    mapOptions.center = {lat: 48.856613, lng: 2.352222};
    mapOptions.zoom = 6;

    map = new HWMapJsSDK.HWMap(document.getElementById('map'), mapOptions);

    var imageBounds = {
        north: 48.8,
        south: 48.3,
        east: 2.8,
        west: 2,
    };

    mGroundOverlay = new HWMapJsSDK.HWGroundOverlay(
        // 本地资源图片路径或者是图片的URL
        'covering.png',
        imageBounds,
        {
            map: map,
            opacity: 1,
            zIndex: 1
        }
    );
}
```

以上代码添加覆盖物的效果如[图1](#fig175861416172715)所示：

**图 1**  覆盖物<a name="fig175861416172715"></a>  


![](figures/5-3覆盖物.png)

## 删除覆盖物<a name="section8879241103017"></a>

要从地图中移除覆盖物，请调用setMap\(\)方法并将null作为传递参数。

```
mGroundOverlay.setMap(null);
```

请注意，上述方法不会删除覆盖物，它只是把覆盖物从地图上移除。如果用户希望删除覆盖物，则应将其从地图上移除，然后将覆盖物本身置为null即可。

```
mGroundOverlay.setMap(null);
mGroundOverlay = null;
```

## 修改覆盖物<a name="section173661808318"></a>

用户可以通过[HWGroundOverlay](zh-cn_topic_0000001099661058.md)对象的方法对属性进行修改，以下代码示例修改GroundOverlay的url：

```
<tr>
    <td>URL:</td>
    <td><input id="urlInput" type="text"
               <!-- value可以是本地资源图片路径或者是图片的URL -->
               value="huawei_logo.png"/>
    </td>
</tr>
```

```
var url = document.getElementById("urlInput").value;
mGroundOverlay.setUrl(url);
```

覆盖物的以下属性支持自定义，具体请参见[HWGroundOverlay](zh-cn_topic_0000001099661058.md)。

<a name="table28525097"></a>
<table><thead align="left"><tr id="row20859864"><th class="cellrowborder" valign="top" width="40%" id="mcps1.1.3.1.1"><p id="p11927387"><a name="p11927387"></a><a name="p11927387"></a><strong id="b136606719159"><a name="b136606719159"></a><a name="b136606719159"></a>属性</strong></p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.1.3.1.2"><p id="p26594328"><a name="p26594328"></a><a name="p26594328"></a><strong id="b176811071156"><a name="b176811071156"></a><a name="b176811071156"></a>含义</strong></p>
</th>
</tr>
</thead>
<tbody><tr id="row38022363"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p59912543"><a name="p59912543"></a><a name="p59912543"></a>setBounds(bounds)</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p21077808"><a name="p21077808"></a><a name="p21077808"></a>设置限制范围。</p>
</td>
</tr>
<tr id="row55482544"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p64901086"><a name="p64901086"></a><a name="p64901086"></a>setOpacity(opacity)</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p22496653"><a name="p22496653"></a><a name="p22496653"></a>设置透明度。</p>
</td>
</tr>
<tr id="row1143293"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p25497871"><a name="p25497871"></a><a name="p25497871"></a>setUrl(url)</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p52061686"><a name="p52061686"></a><a name="p52061686"></a>设置图片URL。</p>
</td>
</tr>
<tr id="row65901997"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p36461550"><a name="p36461550"></a><a name="p36461550"></a>setMap(map)</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p595575"><a name="p595575"></a><a name="p595575"></a>设置地图实例。</p>
</td>
</tr>
</tbody>
</table>

