# 自定义覆盖物<a name="ZH-CN_TOPIC_0000001099341064"></a>

-   [添加自定义图片和输入框覆盖物](#section137581141202511)
-   [添加自定义弹出框覆盖物](#section187711733193317)
-   [删除自定义覆盖物](#section56318683810)
-   [设置自定义覆盖物](#section10440105104014)

在地图上添加自定义覆盖物。

## 添加自定义图片和输入框覆盖物<a name="section137581141202511"></a>

用户可以使用HWMapJsSDK.[HWOverlay](zh-cn_topic_0000001145941065.md)\(overlayOptions\)构造方法创建一个自定义图片和输入框覆盖物添加到地图上，示例代码如下：

```
html,
body {
    margin: 0;
    padding: 0;
    height: 100%;
    width: 100%;
}
#map {
    height: 100%;
    width: 100%;
    margin: 0 auto;
}
#marker {
    background: url('./marker-with-dot.png');
    user-select: none;
    width: 48px;
    height: 48px;
}
#label {
    padding: 2px;
    text-indent: 2px;
}
#popup {
    position: absolute;
    opacity: 0;
    max-width: 276px;
    padding: 1;
    font: 400 14px Arial, Helvetica, sans-serif;
    line-height: 1.3;
    background-color: #fff;
    border: 1px solid rgba(0, 0, 0, .2);
    border-radius: 6px;
    box-shadow: 0 5px 10px rgba(0, 0, 0, .2);
}
#popup::after {
    width: 0;
    height: 0;
    content: '';
    display: block;
    border: 10px solid transparent;
    border-top-color: #fff;
    position: absolute;
    left: calc(50% - 10px);
}
.popover_title {
    border-bottom: 1px solid rgba(0, 0, 0, .2);
    padding: 10px;
    margin: 0;
}
.close {
    float: right;
    user-select: none;
    cursor: pointer;
}
.popup_content {
    padding: 10px;
    word-wrap: break-word;
    max-width: 200px;
    text-align: center;
}
<div id="map">
        <div id="popup">
            <h3 class="popover_title">overlayPopup
                <span class="close">x</span>
            </h3>
            <div class="popup_content"></div>
        </div>
</div>
```

```
var map, overlayPopup; 
var popup = document.querySelector('#popup')
var popup_content = popup.querySelector('.popup_content')
var popup_close = popup.querySelector('.close')

function initMap() {
    var mapOptions = {};
    mapOptions.center = {lat: 48.856613, lng: 2.352222};
    mapOptions.zoom = 8;
    map = new HWMapJsSDK.HWMap(document.getElementById('map'), mapOptions);

    // 初始化HWOverlay marker图片
    overlayMarker = new HWMapJsSDK.HWOverlay({
        map: map,
        content: '<div id="marker"></div>',
        stopEvent: true,
        position: map.getCenter()
    });

    // 初始化HWOverlay 
    overlayLabel = new HWMapJsSDK.HWOverlay({
        map: map,
        offset: [40, -10],
        stopEvent: true,
        position: map.getCenter()
    });

    // 设置覆盖物(textarea输入框)
    overlayLabel.setContent('<textarea id="label" placeholder="label" cols="10" rows="2"></textarea>')
}
```

以上代码在经纬度为（48.85, 2.35）的位置上添加了一个自定义图片覆盖物和自定义输入框覆盖物，效果如[图1](#fig8206165243113)所示：

**图 1**  图片和输入框覆盖物<a name="fig8206165243113"></a>  
![](figures/图片和输入框覆盖物.png "图片和输入框覆盖物")

## 添加自定义弹出框覆盖物<a name="section187711733193317"></a>

创建一个自定义弹出框覆盖物添加到地图上，示例代码如下：

```
// 初始化HWOverlay popup弹出框
overlayPopup = new HWMapJsSDK.HWOverlay({
    map: map,
    content: popup,
    stopEvent: false
});
 
// 设置不允许穿透
overlayPopup. setStopEvent(true)
 
// 监听地图点击，绑定地图实例
map.on('click', function (e) {
    overlayPopup.setMap(map)
    const coordinate = HWMapJsSDK.HWMapUtils.epsgToLatLng(e.coordinate);
    Popup.setText(JSON.stringify(coordinate))
    // 设置overlayPopup的位置
    overlayPopup.setPosition(coordinate)
})
 
// 解绑地图实例
popup_close.onclick = function () {
    overlayPopup.setMap(null)
}
 
// 构造弹出框方法
class Popup {
    static async setText(text) {
        popup.style.opacity = 1
        popup_content.innerText = await text
        Popup.setStyle()
    }
    static async setStyle() {
        popup.style.left = (-popup.offsetWidth / 2) + 'px'
        popup.style.top = (-popup.offsetHeight - 10) + 'px'
    }
 }
```

以上代码在地图上点击添加了一个自定义弹出框覆盖物，效果如[图2](#fig2787370360)所示：

**图 2**  弹出框覆盖物<a name="fig2787370360"></a>  
![](figures/弹出框覆盖物.png "弹出框覆盖物")

## 删除自定义覆盖物<a name="section56318683810"></a>

要从地图中移除自定义覆盖物，请调用setMap\(\)方法并将null作为传递参数。

```
// 解绑地图实例
popup_close.onclick = function () {
    overlayPopup.setMap(null)
}
```

## 设置自定义覆盖物<a name="section10440105104014"></a>

用户可以通过[HWOverlay](zh-cn_topic_0000001145941065.md)对象的方法设置覆盖物属性，以下代码示例使用setContent方法设置覆盖物的内容：

```
// 设置覆盖物内容
overlayLabel.setContent('<textarea id="label" placeholder="label" cols="10" rows="2"></textarea>')
```

覆盖物的以下属性支持自定义，具体请参见[HWOverlay](zh-cn_topic_0000001145941065.md)。

<a name="table83562271411"></a>
<table><thead align="left"><tr id="row3356142734112"><th class="cellrowborder" valign="top" width="40%" id="mcps1.1.3.1.1"><p id="p1356127194113"><a name="p1356127194113"></a><a name="p1356127194113"></a>属性</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.1.3.1.2"><p id="p13561427104115"><a name="p13561427104115"></a><a name="p13561427104115"></a>含义</p>
</th>
</tr>
</thead>
<tbody><tr id="row23563277413"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p17329751144119"><a name="p17329751144119"></a><a name="p17329751144119"></a>setContent(content)</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p1032985110413"><a name="p1032985110413"></a><a name="p1032985110413"></a>设置<a href="zh-cn_topic_0000001145941065.md">HWOverlay</a>的内容。</p>
</td>
</tr>
<tr id="row183564279415"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p143291651144120"><a name="p143291651144120"></a><a name="p143291651144120"></a>setMap(map)</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p93299510417"><a name="p93299510417"></a><a name="p93299510417"></a>绑定到地图。</p>
</td>
</tr>
<tr id="row235612724119"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p83291351114111"><a name="p83291351114111"></a><a name="p83291351114111"></a>setPosition(latLng)</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p3329145114417"><a name="p3329145114417"></a><a name="p3329145114417"></a>设置<a href="zh-cn_topic_0000001145941065.md">HWOverlay</a>的位置。</p>
</td>
</tr>
<tr id="row10356527174117"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p103291551164117"><a name="p103291551164117"></a><a name="p103291551164117"></a>setStopEvent(boolean)</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p193294518410"><a name="p193294518410"></a><a name="p193294518410"></a>设置是否支持穿透。</p>
</td>
</tr>
</tbody>
</table>

