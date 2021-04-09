# 地图事件<a name="ZH-CN_TOPIC_0000001145860965"></a>

-   地图点击事件：

    ```
    map.on('click', () => {
          map.zoomIn();
    });
    ```

-   地图中心点改变事件：

    ```
    map.onCenterChanged(centerChangePost);
    
    function centerChangePost() {
        var center = map.getCenter();
        alert( 'Lng:'+map.getCenter().lng+'\n'+'Lat:'+map.getCenter().lat);
    }
    ```

-   地图方向改变事件：

    ```
    map.onHeadingChanged(headingChangePost);
    
    function headingChangePost() {
        alert('Heading Changed!')
    }
    ```

-   地图缩放级别改变事件：

    ```
    map.onZoomChanged(zoomChangePost);
    
    function zoomChangePost() {
        alert('Zoom Changed!')
    }
    ```


关于地图事件，如下表格所示，具体请参见[HWMap](zh-cn_topic_0000001145860979.md)。

<a name="table41236172"></a>
<table><thead align="left"><tr id="row19206131"><th class="cellrowborder" valign="top" width="24.490000000000002%" id="mcps1.1.4.1.1"><p id="p12192756"><a name="p12192756"></a><a name="p12192756"></a><strong id="b1952117729"><a name="b1952117729"></a><a name="b1952117729"></a>事件</strong></p>
</th>
<th class="cellrowborder" valign="top" width="26.529999999999998%" id="mcps1.1.4.1.2"><p id="p48089211"><a name="p48089211"></a><a name="p48089211"></a><strong id="b155551076212"><a name="b155551076212"></a><a name="b155551076212"></a>含义</strong></p>
</th>
<th class="cellrowborder" valign="top" width="48.980000000000004%" id="mcps1.1.4.1.3"><p id="p2911981"><a name="p2911981"></a><a name="p2911981"></a><strong id="b859117716214"><a name="b859117716214"></a><a name="b859117716214"></a>使用方式</strong></p>
</th>
</tr>
</thead>
<tbody><tr id="row26207835"><td class="cellrowborder" valign="top" width="24.490000000000002%" headers="mcps1.1.4.1.1 "><p id="p42459867"><a name="p42459867"></a><a name="p42459867"></a>click</p>
</td>
<td class="cellrowborder" valign="top" width="26.529999999999998%" headers="mcps1.1.4.1.2 "><p id="p16697212"><a name="p16697212"></a><a name="p16697212"></a>鼠标左键点击。</p>
</td>
<td class="cellrowborder" valign="top" width="48.980000000000004%" headers="mcps1.1.4.1.3 "><p id="p10296933"><a name="p10296933"></a><a name="p10296933"></a>map.on('click',  callback), 参数callback为回调函数。</p>
</td>
</tr>
<tr id="row25563541"><td class="cellrowborder" valign="top" width="24.490000000000002%" headers="mcps1.1.4.1.1 "><p id="p57380926"><a name="p57380926"></a><a name="p57380926"></a>singleclick</p>
</td>
<td class="cellrowborder" valign="top" width="26.529999999999998%" headers="mcps1.1.4.1.2 "><p id="p17343428"><a name="p17343428"></a><a name="p17343428"></a>鼠标左键点击。</p>
</td>
<td class="cellrowborder" valign="top" width="48.980000000000004%" headers="mcps1.1.4.1.3 "><p id="p62640398"><a name="p62640398"></a><a name="p62640398"></a>map.on('singleclick', callback), 参数callback为回调函数。</p>
</td>
</tr>
<tr id="row26892672"><td class="cellrowborder" valign="top" width="24.490000000000002%" headers="mcps1.1.4.1.1 "><p id="p30822828"><a name="p30822828"></a><a name="p30822828"></a>dblclick</p>
</td>
<td class="cellrowborder" valign="top" width="26.529999999999998%" headers="mcps1.1.4.1.2 "><p id="p13621136"><a name="p13621136"></a><a name="p13621136"></a>鼠标左键双击。</p>
</td>
<td class="cellrowborder" valign="top" width="48.980000000000004%" headers="mcps1.1.4.1.3 "><p id="p29570261"><a name="p29570261"></a><a name="p29570261"></a>map.on('dblclick', callback), 参数callback为回调函数。</p>
</td>
</tr>
<tr id="row64805763"><td class="cellrowborder" valign="top" width="24.490000000000002%" headers="mcps1.1.4.1.1 "><p id="p14775484"><a name="p14775484"></a><a name="p14775484"></a>contextmenu</p>
</td>
<td class="cellrowborder" valign="top" width="26.529999999999998%" headers="mcps1.1.4.1.2 "><p id="p55963561"><a name="p55963561"></a><a name="p55963561"></a>鼠标右键点击。</p>
</td>
<td class="cellrowborder" valign="top" width="48.980000000000004%" headers="mcps1.1.4.1.3 "><p id="p36754611"><a name="p36754611"></a><a name="p36754611"></a>map.on('contextmenu', callback), 参数callback为回调函数。</p>
</td>
</tr>
<tr id="row62356046"><td class="cellrowborder" valign="top" width="24.490000000000002%" headers="mcps1.1.4.1.1 "><p id="p17674957"><a name="p17674957"></a><a name="p17674957"></a>pointermove</p>
</td>
<td class="cellrowborder" valign="top" width="26.529999999999998%" headers="mcps1.1.4.1.2 "><p id="p22385437"><a name="p22385437"></a><a name="p22385437"></a>鼠标移动。</p>
</td>
<td class="cellrowborder" valign="top" width="48.980000000000004%" headers="mcps1.1.4.1.3 "><p id="p1281126"><a name="p1281126"></a><a name="p1281126"></a>map.on('pointermove', callback), 参数callback为回调函数。</p>
</td>
</tr>
<tr id="row11530135"><td class="cellrowborder" valign="top" width="24.490000000000002%" headers="mcps1.1.4.1.1 "><p id="p61525703"><a name="p61525703"></a><a name="p61525703"></a>pointerdown</p>
</td>
<td class="cellrowborder" valign="top" width="26.529999999999998%" headers="mcps1.1.4.1.2 "><p id="p17526019"><a name="p17526019"></a><a name="p17526019"></a>鼠标键按下。</p>
</td>
<td class="cellrowborder" valign="top" width="48.980000000000004%" headers="mcps1.1.4.1.3 "><p id="p10321460"><a name="p10321460"></a><a name="p10321460"></a>map.on('pointerdown', callback), 参数callback为回调函数。</p>
</td>
</tr>
<tr id="row25784284"><td class="cellrowborder" valign="top" width="24.490000000000002%" headers="mcps1.1.4.1.1 "><p id="p8152279"><a name="p8152279"></a><a name="p8152279"></a>pointerup</p>
</td>
<td class="cellrowborder" valign="top" width="26.529999999999998%" headers="mcps1.1.4.1.2 "><p id="p56354875"><a name="p56354875"></a><a name="p56354875"></a>鼠标键松开。</p>
</td>
<td class="cellrowborder" valign="top" width="48.980000000000004%" headers="mcps1.1.4.1.3 "><p id="p1342126"><a name="p1342126"></a><a name="p1342126"></a>map.on('pointerup', callback), 参数callback为回调函数。</p>
</td>
</tr>
<tr id="row461141118215"><td class="cellrowborder" valign="top" width="24.490000000000002%" headers="mcps1.1.4.1.1 "><p id="p49322849"><a name="p49322849"></a><a name="p49322849"></a>pointerdrag</p>
</td>
<td class="cellrowborder" valign="top" width="26.529999999999998%" headers="mcps1.1.4.1.2 "><p id="p35727861"><a name="p35727861"></a><a name="p35727861"></a>地图拖动。</p>
</td>
<td class="cellrowborder" valign="top" width="48.980000000000004%" headers="mcps1.1.4.1.3 "><p id="p8275629"><a name="p8275629"></a><a name="p8275629"></a>map.on('pointerdrag', callback), 参数callback为回调函数。</p>
</td>
</tr>
<tr id="row12079142"><td class="cellrowborder" valign="top" width="24.490000000000002%" headers="mcps1.1.4.1.1 "><p id="p38886454"><a name="p38886454"></a><a name="p38886454"></a>movestart</p>
</td>
<td class="cellrowborder" valign="top" width="26.529999999999998%" headers="mcps1.1.4.1.2 "><p id="p62795050"><a name="p62795050"></a><a name="p62795050"></a>地图开始移动。</p>
</td>
<td class="cellrowborder" valign="top" width="48.980000000000004%" headers="mcps1.1.4.1.3 "><p id="p53234283"><a name="p53234283"></a><a name="p53234283"></a>map.on('movestart', callback), 参数callback为回调函数。</p>
</td>
</tr>
<tr id="row9346499"><td class="cellrowborder" valign="top" width="24.490000000000002%" headers="mcps1.1.4.1.1 "><p id="p18868961"><a name="p18868961"></a><a name="p18868961"></a>moveend</p>
</td>
<td class="cellrowborder" valign="top" width="26.529999999999998%" headers="mcps1.1.4.1.2 "><p id="p51990912"><a name="p51990912"></a><a name="p51990912"></a>地图结束移动。</p>
</td>
<td class="cellrowborder" valign="top" width="48.980000000000004%" headers="mcps1.1.4.1.3 "><p id="p50514376"><a name="p50514376"></a><a name="p50514376"></a>map.on('moveend', callback), 参数callback为回调函数。</p>
</td>
</tr>
<tr id="row7371802"><td class="cellrowborder" valign="top" width="24.490000000000002%" headers="mcps1.1.4.1.1 "><p id="p60245124"><a name="p60245124"></a><a name="p60245124"></a>onCenterChanged</p>
</td>
<td class="cellrowborder" valign="top" width="26.529999999999998%" headers="mcps1.1.4.1.2 "><p id="p48016903"><a name="p48016903"></a><a name="p48016903"></a>地图中心点改变。</p>
</td>
<td class="cellrowborder" valign="top" width="48.980000000000004%" headers="mcps1.1.4.1.3 "><p id="p64163914"><a name="p64163914"></a><a name="p64163914"></a>map.onCenterChanged(callback), 参数callback为回调函数。</p>
</td>
</tr>
<tr id="row40604315"><td class="cellrowborder" valign="top" width="24.490000000000002%" headers="mcps1.1.4.1.1 "><p id="p615201"><a name="p615201"></a><a name="p615201"></a>onHeadingChanged</p>
</td>
<td class="cellrowborder" valign="top" width="26.529999999999998%" headers="mcps1.1.4.1.2 "><p id="p49831357"><a name="p49831357"></a><a name="p49831357"></a>方向改变。</p>
</td>
<td class="cellrowborder" valign="top" width="48.980000000000004%" headers="mcps1.1.4.1.3 "><p id="p9808084"><a name="p9808084"></a><a name="p9808084"></a>map.onHeadingChanged(callback), 参数callback为回调函数。</p>
</td>
</tr>
<tr id="row21163898"><td class="cellrowborder" valign="top" width="24.490000000000002%" headers="mcps1.1.4.1.1 "><p id="p36554200"><a name="p36554200"></a><a name="p36554200"></a>onZoomChanged</p>
</td>
<td class="cellrowborder" valign="top" width="26.529999999999998%" headers="mcps1.1.4.1.2 "><p id="p8100198"><a name="p8100198"></a><a name="p8100198"></a>缩放级别改变。</p>
</td>
<td class="cellrowborder" valign="top" width="48.980000000000004%" headers="mcps1.1.4.1.3 "><p id="p52136268"><a name="p52136268"></a><a name="p52136268"></a>map.onZoomChanged(callback), 参数callback为回调函数。</p>
</td>
</tr>
</tbody>
</table>

