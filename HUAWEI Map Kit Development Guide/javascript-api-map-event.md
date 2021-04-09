# Map Event<a name="EN-US_TOPIC_0000001145523595"></a>

-   Map click event:

    ```
    map.on('click', () => {
          map.zoomIn();
    });
    ```

-   Map center change event:

    ```
    map.onCenterChanged(centerChangePost);
    
    function centerChangePost() {
        var center = map.getCenter();
        alert( 'Lng:'+map.getCenter().lng+'\n'+'Lat:'+map.getCenter().lat);
    }
    ```

-   Map heading change event:

    ```
    map.onHeadingChanged(headingChangePost);
    
    function headingChangePost() {
        alert('Heading Changed!')
    }
    ```

-   Map zoom level change event:

    ```
    map.onZoomChanged(zoomChangePost);
    
    function zoomChangePost() {
        alert('Zoom Changed!')
    }
    ```


The following table describes map events. For details, please refer to  [HWMap](en-us_topic_0000001145523545.md).

<a name="table41236172"></a>
<table><thead align="left"><tr id="row19206131"><th class="cellrowborder" valign="top" width="24.490000000000002%" id="mcps1.1.4.1.1"><p id="p12192756"><a name="p12192756"></a><a name="p12192756"></a><strong id="b1952117729"><a name="b1952117729"></a><a name="b1952117729"></a>Event</strong></p>
</th>
<th class="cellrowborder" valign="top" width="26.529999999999998%" id="mcps1.1.4.1.2"><p id="p48089211"><a name="p48089211"></a><a name="p48089211"></a><strong id="b155551076212"><a name="b155551076212"></a><a name="b155551076212"></a>Description</strong></p>
</th>
<th class="cellrowborder" valign="top" width="48.980000000000004%" id="mcps1.1.4.1.3"><p id="p2911981"><a name="p2911981"></a><a name="p2911981"></a><strong id="b859117716214"><a name="b859117716214"></a><a name="b859117716214"></a>Usage</strong></p>
</th>
</tr>
</thead>
<tbody><tr id="row26207835"><td class="cellrowborder" valign="top" width="24.490000000000002%" headers="mcps1.1.4.1.1 "><p id="p42459867"><a name="p42459867"></a><a name="p42459867"></a>click</p>
</td>
<td class="cellrowborder" valign="top" width="26.529999999999998%" headers="mcps1.1.4.1.2 "><p id="p16697212"><a name="p16697212"></a><a name="p16697212"></a>Click on the left button of the mouse once or more.</p>
</td>
<td class="cellrowborder" valign="top" width="48.980000000000004%" headers="mcps1.1.4.1.3 "><p id="p10296933"><a name="p10296933"></a><a name="p10296933"></a><strong id="b7119102992513"><a name="b7119102992513"></a><a name="b7119102992513"></a>map.on('click', callback)</strong>, where <strong id="b511932911252"><a name="b511932911252"></a><a name="b511932911252"></a>callback</strong> is a callback function.</p>
</td>
</tr>
<tr id="row25563541"><td class="cellrowborder" valign="top" width="24.490000000000002%" headers="mcps1.1.4.1.1 "><p id="p57380926"><a name="p57380926"></a><a name="p57380926"></a>singleclick</p>
</td>
<td class="cellrowborder" valign="top" width="26.529999999999998%" headers="mcps1.1.4.1.2 "><p id="p17343428"><a name="p17343428"></a><a name="p17343428"></a>Click on the left button of the mouse once.</p>
</td>
<td class="cellrowborder" valign="top" width="48.980000000000004%" headers="mcps1.1.4.1.3 "><p id="p62640398"><a name="p62640398"></a><a name="p62640398"></a><strong id="b158613513259"><a name="b158613513259"></a><a name="b158613513259"></a>map.on('singleclick', callback)</strong>, where <strong id="b125911851142516"><a name="b125911851142516"></a><a name="b125911851142516"></a>callback</strong> is a callback function.</p>
</td>
</tr>
<tr id="row26892672"><td class="cellrowborder" valign="top" width="24.490000000000002%" headers="mcps1.1.4.1.1 "><p id="p30822828"><a name="p30822828"></a><a name="p30822828"></a>dblclick</p>
</td>
<td class="cellrowborder" valign="top" width="26.529999999999998%" headers="mcps1.1.4.1.2 "><p id="p13621136"><a name="p13621136"></a><a name="p13621136"></a>Double-click on the left button of the mouse.</p>
</td>
<td class="cellrowborder" valign="top" width="48.980000000000004%" headers="mcps1.1.4.1.3 "><p id="p29570261"><a name="p29570261"></a><a name="p29570261"></a><strong id="b974611592255"><a name="b974611592255"></a><a name="b974611592255"></a>map.on('dblclick', callback)</strong>, where <strong id="b197511659112513"><a name="b197511659112513"></a><a name="b197511659112513"></a>callback</strong> is a callback function.</p>
</td>
</tr>
<tr id="row64805763"><td class="cellrowborder" valign="top" width="24.490000000000002%" headers="mcps1.1.4.1.1 "><p id="p14775484"><a name="p14775484"></a><a name="p14775484"></a>contextmenu</p>
</td>
<td class="cellrowborder" valign="top" width="26.529999999999998%" headers="mcps1.1.4.1.2 "><p id="p55963561"><a name="p55963561"></a><a name="p55963561"></a>Click on the right button of the mouse.</p>
</td>
<td class="cellrowborder" valign="top" width="48.980000000000004%" headers="mcps1.1.4.1.3 "><p id="p36754611"><a name="p36754611"></a><a name="p36754611"></a><strong id="b42911010102617"><a name="b42911010102617"></a><a name="b42911010102617"></a>map.on('contextmenu', callback)</strong>, where <strong id="b16297510152614"><a name="b16297510152614"></a><a name="b16297510152614"></a>callback</strong> is a callback function.</p>
</td>
</tr>
<tr id="row62356046"><td class="cellrowborder" valign="top" width="24.490000000000002%" headers="mcps1.1.4.1.1 "><p id="p17674957"><a name="p17674957"></a><a name="p17674957"></a>pointermove</p>
</td>
<td class="cellrowborder" valign="top" width="26.529999999999998%" headers="mcps1.1.4.1.2 "><p id="p22385437"><a name="p22385437"></a><a name="p22385437"></a>Moving of the mouse pointer.</p>
</td>
<td class="cellrowborder" valign="top" width="48.980000000000004%" headers="mcps1.1.4.1.3 "><p id="p1281126"><a name="p1281126"></a><a name="p1281126"></a><strong id="b165382020152611"><a name="b165382020152611"></a><a name="b165382020152611"></a>map.on('pointermove', callback)</strong>, where <strong id="b2543162012610"><a name="b2543162012610"></a><a name="b2543162012610"></a>callback</strong> is a callback function.</p>
</td>
</tr>
<tr id="row11530135"><td class="cellrowborder" valign="top" width="24.490000000000002%" headers="mcps1.1.4.1.1 "><p id="p61525703"><a name="p61525703"></a><a name="p61525703"></a>pointerdown</p>
</td>
<td class="cellrowborder" valign="top" width="26.529999999999998%" headers="mcps1.1.4.1.2 "><p id="p17526019"><a name="p17526019"></a><a name="p17526019"></a>Mouse button press.</p>
</td>
<td class="cellrowborder" valign="top" width="48.980000000000004%" headers="mcps1.1.4.1.3 "><p id="p10321460"><a name="p10321460"></a><a name="p10321460"></a><strong id="b365310597267"><a name="b365310597267"></a><a name="b365310597267"></a>map.on('pointerdown', callback)</strong>, where <strong id="b19658159132618"><a name="b19658159132618"></a><a name="b19658159132618"></a>callback</strong> is a callback function.</p>
</td>
</tr>
<tr id="row25784284"><td class="cellrowborder" valign="top" width="24.490000000000002%" headers="mcps1.1.4.1.1 "><p id="p8152279"><a name="p8152279"></a><a name="p8152279"></a>pointerup</p>
</td>
<td class="cellrowborder" valign="top" width="26.529999999999998%" headers="mcps1.1.4.1.2 "><p id="p56354875"><a name="p56354875"></a><a name="p56354875"></a>Mouse button release.</p>
</td>
<td class="cellrowborder" valign="top" width="48.980000000000004%" headers="mcps1.1.4.1.3 "><p id="p1342126"><a name="p1342126"></a><a name="p1342126"></a><strong id="b149874619276"><a name="b149874619276"></a><a name="b149874619276"></a>map.on('pointerup', callback)</strong>, where <strong id="b69927611278"><a name="b69927611278"></a><a name="b69927611278"></a>callback</strong> is a callback function.</p>
</td>
</tr>
<tr id="row461141118215"><td class="cellrowborder" valign="top" width="24.490000000000002%" headers="mcps1.1.4.1.1 "><p id="p49322849"><a name="p49322849"></a><a name="p49322849"></a>pointerdrag</p>
</td>
<td class="cellrowborder" valign="top" width="26.529999999999998%" headers="mcps1.1.4.1.2 "><p id="p35727861"><a name="p35727861"></a><a name="p35727861"></a>Map dragging.</p>
</td>
<td class="cellrowborder" valign="top" width="48.980000000000004%" headers="mcps1.1.4.1.3 "><p id="p8275629"><a name="p8275629"></a><a name="p8275629"></a><strong id="b168943304273"><a name="b168943304273"></a><a name="b168943304273"></a>map.on('pointerdrag', callback)</strong>, where <strong id="b289919301279"><a name="b289919301279"></a><a name="b289919301279"></a>callback</strong> is a callback function.</p>
</td>
</tr>
<tr id="row12079142"><td class="cellrowborder" valign="top" width="24.490000000000002%" headers="mcps1.1.4.1.1 "><p id="p38886454"><a name="p38886454"></a><a name="p38886454"></a>movestart</p>
</td>
<td class="cellrowborder" valign="top" width="26.529999999999998%" headers="mcps1.1.4.1.2 "><p id="p62795050"><a name="p62795050"></a><a name="p62795050"></a>Map moving start.</p>
</td>
<td class="cellrowborder" valign="top" width="48.980000000000004%" headers="mcps1.1.4.1.3 "><p id="p53234283"><a name="p53234283"></a><a name="p53234283"></a><strong id="b1859111552711"><a name="b1859111552711"></a><a name="b1859111552711"></a>map.on('movestart', callback)</strong>, where <strong id="b6596151510277"><a name="b6596151510277"></a><a name="b6596151510277"></a>callback</strong> is a callback function.</p>
</td>
</tr>
<tr id="row9346499"><td class="cellrowborder" valign="top" width="24.490000000000002%" headers="mcps1.1.4.1.1 "><p id="p18868961"><a name="p18868961"></a><a name="p18868961"></a>moveend</p>
</td>
<td class="cellrowborder" valign="top" width="26.529999999999998%" headers="mcps1.1.4.1.2 "><p id="p51990912"><a name="p51990912"></a><a name="p51990912"></a>Map moving stop.</p>
</td>
<td class="cellrowborder" valign="top" width="48.980000000000004%" headers="mcps1.1.4.1.3 "><p id="p50514376"><a name="p50514376"></a><a name="p50514376"></a><strong id="b42476251270"><a name="b42476251270"></a><a name="b42476251270"></a>map.on('moveend', callback)</strong>, where <strong id="b1025272519276"><a name="b1025272519276"></a><a name="b1025272519276"></a>callback</strong> is a callback function.</p>
</td>
</tr>
<tr id="row7371802"><td class="cellrowborder" valign="top" width="24.490000000000002%" headers="mcps1.1.4.1.1 "><p id="p60245124"><a name="p60245124"></a><a name="p60245124"></a>onCenterChanged</p>
</td>
<td class="cellrowborder" valign="top" width="26.529999999999998%" headers="mcps1.1.4.1.2 "><p id="p48016903"><a name="p48016903"></a><a name="p48016903"></a>Map center change.</p>
</td>
<td class="cellrowborder" valign="top" width="48.980000000000004%" headers="mcps1.1.4.1.3 "><p id="p64163914"><a name="p64163914"></a><a name="p64163914"></a><strong id="b16242123711272"><a name="b16242123711272"></a><a name="b16242123711272"></a>map.onCenterChanged(callback)</strong>, where <strong id="b16247037142716"><a name="b16247037142716"></a><a name="b16247037142716"></a>callback</strong> is a callback function.</p>
</td>
</tr>
<tr id="row40604315"><td class="cellrowborder" valign="top" width="24.490000000000002%" headers="mcps1.1.4.1.1 "><p id="p615201"><a name="p615201"></a><a name="p615201"></a>onHeadingChanged</p>
</td>
<td class="cellrowborder" valign="top" width="26.529999999999998%" headers="mcps1.1.4.1.2 "><p id="p49831357"><a name="p49831357"></a><a name="p49831357"></a>Map heading change.</p>
</td>
<td class="cellrowborder" valign="top" width="48.980000000000004%" headers="mcps1.1.4.1.3 "><p id="p9808084"><a name="p9808084"></a><a name="p9808084"></a><strong id="b1063564415276"><a name="b1063564415276"></a><a name="b1063564415276"></a>map.onHeadingChanged(callback)</strong>, where <strong id="b964094410278"><a name="b964094410278"></a><a name="b964094410278"></a>callback</strong> is a callback function.</p>
</td>
</tr>
<tr id="row21163898"><td class="cellrowborder" valign="top" width="24.490000000000002%" headers="mcps1.1.4.1.1 "><p id="p36554200"><a name="p36554200"></a><a name="p36554200"></a>onZoomChanged</p>
</td>
<td class="cellrowborder" valign="top" width="26.529999999999998%" headers="mcps1.1.4.1.2 "><p id="p8100198"><a name="p8100198"></a><a name="p8100198"></a>Map zoom level change.</p>
</td>
<td class="cellrowborder" valign="top" width="48.980000000000004%" headers="mcps1.1.4.1.3 "><p id="p52136268"><a name="p52136268"></a><a name="p52136268"></a><strong id="b783819505276"><a name="b783819505276"></a><a name="b783819505276"></a>map.onZoomChanged(callback)</strong>, where <strong id="b98431550182715"><a name="b98431550182715"></a><a name="b98431550182715"></a>callback</strong> is a callback function.</p>
</td>
</tr>
</tbody>
</table>

