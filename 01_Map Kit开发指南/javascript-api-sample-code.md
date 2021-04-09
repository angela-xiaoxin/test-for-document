# 示例代码<a name="ZH-CN_TOPIC_0000001099341094"></a>

```
    var map; 
    var directionsService; 
    var directionsRenderer; 
    var makerOrigin, makerDestination; 
    // 创建路径规划请求体
    var DirectionsRequest = {}; 
    DirectionsRequest.origin = { 
        lat: 48.86, 
        lng: 2.36 
    }; 
    DirectionsRequest.destination = { 
        lat: 49.18, 
        lng: 0.39 
    }; 
 
    function initMap() { 
        directionsService = new HWMapJsSDK.HWDirectionsService(); 
        directionsRenderer = new HWMapJsSDK.HWDirectionsRenderer(); 
 
        var mapOptions = {}; 
        mapOptions.center = {lat: 48.856613, lng: 2.352222}; 
        mapOptions.zoom = 8; 
        mapOptions.language = 'ENG'; 
 
        map = new HWMapJsSDK.HWMap(document.getElementById('map'), mapOptions); 
 
        makerOrigin = new HWMapJsSDK.HWMarker({ 
            position: DirectionsRequest.origin, 
            label: 'Origin' 
        }); 
 
        makerDestination = new HWMapJsSDK.HWMarker({ 
            position: DirectionsRequest.destination, 
            label: 'Destination' 
        }); 
 
        makerOrigin.setMap(map); 
        makerDestination.setMap(map); 
        // 调用路径规划接口 
        directionsService.routeDriving(DirectionsRequest, callback); 
        directionsRenderer.setMap(map); 
        // 通过回调函数获取路径规划结果 
        function callback(DirectionsResult, DirectionsStatus) { 
            if (DirectionsStatus == '0') { 
                // 通过HWDirectionsRenderer对象渲染路径 
                directionsRenderer.setDirections(DirectionsResult); 
            } 
        } 
    }
```

效果如[图1](#fig19773162144319)所示：

**图 1**  路径规划结果<a name="fig19773162144319"></a>  


![](figures/7路径.png)

