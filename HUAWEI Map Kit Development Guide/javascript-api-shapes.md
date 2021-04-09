# Shapes<a name="EN-US_TOPIC_0000001098843578"></a>

-   [Polyline](#section482392182016)
-   [Polygon](#section740220982014)
-   [Circle](#section01461815192010)

The HMS Core Map SDK allows you to add different shapes on a map, including polylines, polygons, and circles.

## Polyline<a name="section482392182016"></a>

A polyline consists of multiple points with longitudes and latitudes.

1.  Add a polyline.

    The following sample code is to add a polyline on a map:

    ```
    var map;
    var polyline;
    function initMap() { 
        var mapOptions = {}; 
        mapOptions.center = {lat: 48.856613, lng: 2.352222}; 
        mapOptions.zoom = 8; 
        map = new HWMapJsSDK.HWMap(document.getElementById('map'), mapOptions); 
        polyline = new HWMapJsSDK.HWPolyline({ 
            map: map, 
            path: [ 
                {lat: 49, lng: 2}, 
                {lat: 48.5, lng: 2.5}, 
                {lat: 48, lng: 1.5} 
            ], 
            strokeColor: '#112233', 
            strokeWeight: 5, 
        }); 
    }
    ```

    [Figure 1](#fig1050735414718)  shows the added polyline.

    **Figure  1**  Polyline<a name="fig1050735414718"></a>  
    ![](figures/polyline-230.png "polyline-230")

2.  Remove a polyline.

    To remove a polyline from a map, call the  **setMap\(\)**  method and pass  **null**  as a parameter of the method.

    ```
    polyline.setMap(null);
    ```

    Note: The previous method cannot be used to delete a polyline. It simply removes the polyline from the map. To delete a polyline, you need to remove it from the map and set the polyline itself to  **null**.

    ```
    polyline.setMap(null); 
    polyline = null;
    ```

3.  Modify a polyline.

    You can use the methods of the  [HWPolyline](en-us_topic_0000001099163514.md)  object to modify polyline attributes. The following sample code is to modify the stroke width of a polyline:

    ```
    <tr> 
        <td>Polyline StrokeWeight:</td> 
        <td><input id="strokeWeightInput" type="text" value="2"/></td> 
    </tr>
    ```

    ```
    var strokeWeight = Number(document.getElementById("strokeWeightInput").value); 
    polyline.setStrokeWeight(strokeWeight);
    ```

    The following table describes the polyline attributes that can be customized.

    <a name="table185387853512"></a>
    <table><thead align="left"><tr id="row05381087353"><th class="cellrowborder" valign="top" width="40%" id="mcps1.1.3.1.1"><p id="p81811522113514"><a name="p81811522113514"></a><a name="p81811522113514"></a>Attribute</p>
    </th>
    <th class="cellrowborder" valign="top" width="60%" id="mcps1.1.3.1.2"><p id="p13181422103517"><a name="p13181422103517"></a><a name="p13181422103517"></a>Description</p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="row1053817812350"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p618102273517"><a name="p618102273517"></a><a name="p618102273517"></a>setPath(path)</p>
    </td>
    <td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p8181122133515"><a name="p8181122133515"></a><a name="p8181122133515"></a>Sets the path of a polyline.</p>
    </td>
    </tr>
    <tr id="row105391585352"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p2181122113514"><a name="p2181122113514"></a><a name="p2181122113514"></a>setStrokeColor(strokeColor)</p>
    </td>
    <td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p01811622193510"><a name="p01811622193510"></a><a name="p01811622193510"></a>Sets the stroke color of a polyline.</p>
    </td>
    </tr>
    <tr id="row1153916873519"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p1518112217358"><a name="p1518112217358"></a><a name="p1518112217358"></a>setStrokeWeight(strokeWeight)</p>
    </td>
    <td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p81814227352"><a name="p81814227352"></a><a name="p81814227352"></a>Sets the stroke width of a polyline.</p>
    </td>
    </tr>
    <tr id="row135391823516"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p91811922193518"><a name="p91811922193518"></a><a name="p91811922193518"></a>setVisible(visible)</p>
    </td>
    <td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p618132273517"><a name="p618132273517"></a><a name="p618132273517"></a>Sets the visibility of a polyline.</p>
    </td>
    </tr>
    </tbody>
    </table>

4.  Listen for polyline events.

    [HWPolyline](en-us_topic_0000001099163514.md)  supports multiple events. The following table describes these events.

    <a name="table282152763611"></a>
    <table><thead align="left"><tr id="row6821132703613"><th class="cellrowborder" valign="top" width="40%" id="mcps1.1.3.1.1"><p id="p964364319367"><a name="p964364319367"></a><a name="p964364319367"></a>Event</p>
    </th>
    <th class="cellrowborder" valign="top" width="60%" id="mcps1.1.3.1.2"><p id="p1164314434364"><a name="p1164314434364"></a><a name="p1164314434364"></a>Description</p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="row6822112718364"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p3643194353618"><a name="p3643194353618"></a><a name="p3643194353618"></a>click</p>
    </td>
    <td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p20643643123620"><a name="p20643643123620"></a><a name="p20643643123620"></a>Click on a polyline.</p>
    </td>
    </tr>
    <tr id="row198221727113615"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p364394333617"><a name="p364394333617"></a><a name="p364394333617"></a>dbclick</p>
    </td>
    <td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p364310438368"><a name="p364310438368"></a><a name="p364310438368"></a>Double-click on a polyline. </p>
    </td>
    </tr>
    <tr id="row168221627163615"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p1864316432367"><a name="p1864316432367"></a><a name="p1864316432367"></a>mousedown</p>
    </td>
    <td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p19643134313364"><a name="p19643134313364"></a><a name="p19643134313364"></a>Mouse button press.</p>
    </td>
    </tr>
    <tr id="row138221271368"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p146431043123615"><a name="p146431043123615"></a><a name="p146431043123615"></a>mouseup</p>
    </td>
    <td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p664374313364"><a name="p664374313364"></a><a name="p664374313364"></a>Mouse button release.</p>
    </td>
    </tr>
    </tbody>
    </table>

    The following sample code is to listen for polyline click events. To set this listener on the map, call the  **addListener\('click', callback\)**  method of the  [HWPolyline](en-us_topic_0000001099163514.md)  object.

    ```
    polyline.addListener('click', () => { 
        alert("On Polyline click."); 
    });
    ```


## Polygon<a name="section740220982014"></a>

A polygon consists of multiple points with longitudes and latitudes. Different from a polyline, a polygon is a closed area used to define what is inside it.

1.  Add a polygon.

    The following sample code is to add a polygon on a map:

    ```
    var map;
    var polygon;
    function initMap() { 
        var mapOptions = {}; 
        mapOptions.center = {lat: 48.856613, lng: 2.352222}; 
        mapOptions.zoom = 8; 
        map = new HWMapJsSDK.HWMap(document.getElementById('map'), mapOptions); 
        polygon = new HWMapJsSDK.HWPolygon({ 
            map : map, 
            paths: [ 
                [ 
                    {lat: 49, lng: 2}, 
                    {lat: 48.5, lng: 2.5}, 
                    {lat: 48, lng: 1.5} 
                ], 
            ], 
            fillColor: '#00ff41', 
            strokeColor: '#ff0000', 
            strokeWeight: 5, 
        }); 
    }
    ```

    [Figure 2](#fig28404248109)  shows the added polygon.

    **Figure  2**  Polygon<a name="fig28404248109"></a>  
    ![](figures/polygon-231.png "polygon-231")

2.  Remove a polygon.

    To remove a polygon from a map, call the  **setMap\(\)**  method and pass  **null**  as a parameter of the method.

    ```
    polygon.setMap(null);
    ```

    Note: The previous method cannot be used to delete a polygon. It simply removes the polygon from the map. To delete a polygon, you need to remove it from the map and set the polygon itself to  **null**.

    ```
    polygon.setMap(null); 
    polygon = null;
    ```

3.  Modify a polygon.

    You can use the methods of the  [HWPolygon](en-us_topic_0000001145723447.md)  object to modify polygon attributes. The following sample code is to modify the fill color of a polygon:

    ```
    <tr> 
        <td>Polygon FillColor:</td> 
        <td><input id="fillColorInput" type="text" value="#999999"/></td> 
    </tr>
    ```

    ```
    var fillColor = document.getElementById("fillColorInput").value; 
    polygon.setFillColor(fillColor);
    ```

    The following table describes the polygon attributes that can be customized.

    <a name="table1237930195"></a>
    <table><thead align="left"><tr id="row1737910890"><th class="cellrowborder" valign="top" width="40%" id="mcps1.1.3.1.1"><p id="p58511712891"><a name="p58511712891"></a><a name="p58511712891"></a>Attribute</p>
    </th>
    <th class="cellrowborder" valign="top" width="60%" id="mcps1.1.3.1.2"><p id="p138518129915"><a name="p138518129915"></a><a name="p138518129915"></a>Description</p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="row16379101695"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p1085131219913"><a name="p1085131219913"></a><a name="p1085131219913"></a>setFillColor(fillColor)</p>
    </td>
    <td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p4851212597"><a name="p4851212597"></a><a name="p4851212597"></a>Sets the fill color of a polygon.</p>
    </td>
    </tr>
    <tr id="row7379170594"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p28517126916"><a name="p28517126916"></a><a name="p28517126916"></a>setStrokeColor(strokeColor)</p>
    </td>
    <td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p78511212398"><a name="p78511212398"></a><a name="p78511212398"></a>Sets the stroke color of a polygon.</p>
    </td>
    </tr>
    <tr id="row53796010913"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p1785131218910"><a name="p1785131218910"></a><a name="p1785131218910"></a>setStrokeWeight(strokeWeight)</p>
    </td>
    <td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p48514121099"><a name="p48514121099"></a><a name="p48514121099"></a>Sets the stroke width of a polygon.</p>
    </td>
    </tr>
    <tr id="row193801707913"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p1085271214911"><a name="p1085271214911"></a><a name="p1085271214911"></a>setVisible(visible)</p>
    </td>
    <td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p6852111210914"><a name="p6852111210914"></a><a name="p6852111210914"></a>Sets the visibility of a polygon.</p>
    </td>
    </tr>
    </tbody>
    </table>

4.  Listen for polygon events.

    [HWPolygon](en-us_topic_0000001145723447.md)  supports multiple events. The following table describes these events.

    <a name="table182761755497"></a>
    <table><thead align="left"><tr id="row2276195515915"><th class="cellrowborder" valign="top" width="40%" id="mcps1.1.3.1.1"><p id="p530737111010"><a name="p530737111010"></a><a name="p530737111010"></a>Event</p>
    </th>
    <th class="cellrowborder" valign="top" width="60%" id="mcps1.1.3.1.2"><p id="p1330715714108"><a name="p1330715714108"></a><a name="p1330715714108"></a>Description</p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="row20277195515914"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p330787131012"><a name="p330787131012"></a><a name="p330787131012"></a>click</p>
    </td>
    <td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p1030797181016"><a name="p1030797181016"></a><a name="p1030797181016"></a>Click on a polygon.</p>
    </td>
    </tr>
    <tr id="row1227719551096"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p53071579107"><a name="p53071579107"></a><a name="p53071579107"></a>dbclick</p>
    </td>
    <td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p143074711011"><a name="p143074711011"></a><a name="p143074711011"></a>Double-click on a polygon. </p>
    </td>
    </tr>
    <tr id="row1327717551995"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p4307207181010"><a name="p4307207181010"></a><a name="p4307207181010"></a>mousedown</p>
    </td>
    <td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p6307578100"><a name="p6307578100"></a><a name="p6307578100"></a>Mouse button press.</p>
    </td>
    </tr>
    <tr id="row13277655897"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p730716731014"><a name="p730716731014"></a><a name="p730716731014"></a>mouseup</p>
    </td>
    <td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p230787191019"><a name="p230787191019"></a><a name="p230787191019"></a>Mouse button release.</p>
    </td>
    </tr>
    </tbody>
    </table>

    The following sample code is to listen for polygon click events. To set this listener on the map, call the  **addListener\('click', callback\)**  method of the  [HWPolygon](en-us_topic_0000001145723447.md)  object.

    ```
    polygon.addListener('click', () => { 
          alert("On Polygon click."); 
    });
    ```


## Circle<a name="section01461815192010"></a>

There are two types of circles: solid circle and hollow circle. By default, a circle is hollow, which can be controlled by circle attributes.

1.  Add a circle.

    The following sample code is to add a circle on a map:

    ```
    var map;
    var circle;
    function initMap() { 
        var mapOptions = {}; 
        mapOptions.center = {lat: 48.856613, lng: 2.352222}; 
        mapOptions.zoom = 8; 
        map = new HWMapJsSDK.HWMap(document.getElementById('map'), mapOptions); 
        circle = new HWMapJsSDK.HWCircle({ 
            map: map, 
            center: {lat: 48.5, lng: 2.3}, 
            radius: 20000, 
            fillColor: 'yellow', 
            strokeColor:'red', 
            strokeWeight: 10, 
        }); 
    }
    ```

    [Figure 3](#fig1820137131218)  shows the added circle.

    **Figure  3**  Circle<a name="fig1820137131218"></a>  
    ![](figures/circle-232.png "circle-232")

2.  Remove a circle.

    To remove a circle from a map, call the  **setMap\(\)**  method and pass  **null**  as a parameter of the method.

    ```
    circle.setMap(null);
    ```

    Note: The previous method cannot be used to delete a circle. It simply removes the circle from the map. To delete a circle, you need to remove it from the map and set the circle itself to  **null**.

    ```
    circle.setMap(null); 
    circle = null;
    ```

3.  Modify a circle.

    You can use the methods of the  [HWCircle](en-us_topic_0000001145723431.md)  object to modify circle attributes. The following sample code is to modify the center position of a circle:

    ```
    <tr> 
        <td>Center Lat:</td> 
        <td><input id="centerLatInput" type="text" value="48.6"/></td> 
    </tr> 
    <tr> 
        <td>Center Lng:</td> 
        <td><input id="centerLngInput" type="text" value="2.4"/></td> 
    </tr>
    ```

    ```
    var lat = Number(document.getElementById("centerLatInput").value); 
    var lng = Number(document.getElementById("centerLngInput").value); 
    circle.setCenter({lat: lat, lng: lng});
    ```

    The following table describes the circle attributes that can be customized.

    <a name="table113901411161814"></a>
    <table><thead align="left"><tr id="row173909111184"><th class="cellrowborder" valign="top" width="40%" id="mcps1.1.3.1.1"><p id="p523024161818"><a name="p523024161818"></a><a name="p523024161818"></a>Attribute</p>
    </th>
    <th class="cellrowborder" valign="top" width="60%" id="mcps1.1.3.1.2"><p id="p182332431820"><a name="p182332431820"></a><a name="p182332431820"></a>Description</p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="row1339031111185"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p123162410186"><a name="p123162410186"></a><a name="p123162410186"></a>setCenter(center)</p>
    </td>
    <td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p1323122441810"><a name="p1323122441810"></a><a name="p1323122441810"></a>Sets the center of a circle.</p>
    </td>
    </tr>
    <tr id="row339021101812"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p32312249182"><a name="p32312249182"></a><a name="p32312249182"></a>setRadius(radius)</p>
    </td>
    <td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p32311243188"><a name="p32311243188"></a><a name="p32311243188"></a>Sets the radius of a circle.</p>
    </td>
    </tr>
    <tr id="row183905111181"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p152411247185"><a name="p152411247185"></a><a name="p152411247185"></a>setFillColor(fillColor)</p>
    </td>
    <td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p162412412183"><a name="p162412412183"></a><a name="p162412412183"></a>Sets the fill color of a circle.</p>
    </td>
    </tr>
    <tr id="row18390121117180"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p12245242182"><a name="p12245242182"></a><a name="p12245242182"></a>setStrokeColor(strokeColor)</p>
    </td>
    <td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p172413249184"><a name="p172413249184"></a><a name="p172413249184"></a>Sets the stroke color of a circle's outline.</p>
    </td>
    </tr>
    <tr id="row11390911121817"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p824524181819"><a name="p824524181819"></a><a name="p824524181819"></a>setStrokeWeight(strokeWeight)</p>
    </td>
    <td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p1824112418182"><a name="p1824112418182"></a><a name="p1824112418182"></a>Sets the stroke width of a circle's outline.</p>
    </td>
    </tr>
    <tr id="row163901811191820"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p1924142420187"><a name="p1924142420187"></a><a name="p1924142420187"></a>setVisible(visible)</p>
    </td>
    <td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p624424171819"><a name="p624424171819"></a><a name="p624424171819"></a>Sets whether a circle is visible.</p>
    </td>
    </tr>
    </tbody>
    </table>

4.  Listen for circle events.

    [HWCircle](en-us_topic_0000001145723431.md)  supports multiple events. The following table describes these events.

    <a name="table1146963141916"></a>
    <table><thead align="left"><tr id="row1546913341910"><th class="cellrowborder" valign="top" width="40%" id="mcps1.1.3.1.1"><p id="p126444561912"><a name="p126444561912"></a><a name="p126444561912"></a>Event</p>
    </th>
    <th class="cellrowborder" valign="top" width="60%" id="mcps1.1.3.1.2"><p id="p16447518193"><a name="p16447518193"></a><a name="p16447518193"></a>Description</p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="row1846913121912"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p76441751190"><a name="p76441751190"></a><a name="p76441751190"></a>click</p>
    </td>
    <td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p06441853199"><a name="p06441853199"></a><a name="p06441853199"></a>Click on a circle.</p>
    </td>
    </tr>
    <tr id="row1946917321912"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p126451455191"><a name="p126451455191"></a><a name="p126451455191"></a>dbclick</p>
    </td>
    <td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p1564519511919"><a name="p1564519511919"></a><a name="p1564519511919"></a>Double-click on a circle. </p>
    </td>
    </tr>
    <tr id="row3469163131918"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p364515520191"><a name="p364515520191"></a><a name="p364515520191"></a>mousedown</p>
    </td>
    <td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p464512510199"><a name="p464512510199"></a><a name="p464512510199"></a>Mouse button press.</p>
    </td>
    </tr>
    <tr id="row647015351917"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p1645052196"><a name="p1645052196"></a><a name="p1645052196"></a>mouseup</p>
    </td>
    <td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p264585141919"><a name="p264585141919"></a><a name="p264585141919"></a>Mouse button release.</p>
    </td>
    </tr>
    </tbody>
    </table>

    The following sample code is to listen for circle click events. To set this listener on the map, call the  **addListener\('click', callback\)**  method of the  [HWCircle](en-us_topic_0000001145723431.md)  object.

    ```
    circle.addListener('click', () => { 
        alert("On Circle click."); 
    });
    ```


