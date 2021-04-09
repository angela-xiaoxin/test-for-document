# BitmapDescriptor<a name="ZH-CN_TOPIC_0000001099501086"></a>


<a name="table8460mcpsimp"></a>
<table><thead align="left"><tr id="row8464mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p8466mcpsimp"><a name="p8466mcpsimp"></a><a name="p8466mcpsimp"></a>Class Info</p>
</th>
</tr>
</thead>
<tbody><tr id="row8467mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p48004492218"><a name="p48004492218"></a><a name="p48004492218"></a>public final class BitmapDescriptor</p>
<p id="p8469mcpsimp"><a name="p8469mcpsimp"></a><a name="p8469mcpsimp"></a>用于定义Bitmap图像，可以通过<a href="bitmapdescriptorfactory.md">BitmapDescriptorFactory</a>类获得。Bitmap图像可用于标记的图标或覆盖物的图像。</p>
<p id="p519619498610"><a name="p519619498610"></a><a name="p519619498610"></a>例如，使用BitmapDescriptor设置<a href="marker.md">Marker</a>图标的示例代码如下：</p>
<pre class="screen" id="screen340403519711"><a name="screen340403519711"></a><a name="screen340403519711"></a>MarkerOptions options = new MarkerOptions()
        .position(new LatLng(48.893478, 2.334595))
        .title("Hello Huawei Map")
        .snippet("This is a snippet!")
        .icon(BitmapDescriptorFactory.defaultMarker());
Marker mMarker = hMap.addMarker(options);</pre>
</td>
</tr>
</tbody>
</table>

