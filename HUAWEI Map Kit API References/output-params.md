# Response Parameters<a name="EN-US_TOPIC_0000001099661046"></a>

-   [CoordinateBounds](#section11213141013305)
-   [Path](#section1617173616304)
-   [Route](#section05097566301)
-   [Step](#section8706417143120)
-   [ViaWayPoints](#section87541839183119)
-   [Row](#section98851198326)
-   [Cell](#section1110111245321)

## CoordinateBounds<a name="section11213141013305"></a>

<a name="table8163917"></a>
<table><thead align="left"><tr id="row65280430"><th class="cellrowborder" valign="top" width="18%" id="mcps1.1.5.1.1"><p id="p44133910"><a name="p44133910"></a><a name="p44133910"></a><strong id="b27823264618"><a name="b27823264618"></a><a name="b27823264618"></a>Parameter</strong></p>
</th>
<th class="cellrowborder" valign="top" width="14.000000000000002%" id="mcps1.1.5.1.2"><p id="p324010694520"><a name="p324010694520"></a><a name="p324010694520"></a><strong id="b99769185454"><a name="b99769185454"></a><a name="b99769185454"></a>Mandatory/Optional</strong></p>
</th>
<th class="cellrowborder" valign="top" width="18%" id="mcps1.1.5.1.3"><p id="p28475059"><a name="p28475059"></a><a name="p28475059"></a><strong id="b1777342414478"><a name="b1777342414478"></a><a name="b1777342414478"></a>Type</strong></p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.1.5.1.4"><p id="p21679321"><a name="p21679321"></a><a name="p21679321"></a><strong id="b16915122504718"><a name="b16915122504718"></a><a name="b16915122504718"></a>Description</strong></p>
</th>
</tr>
</thead>
<tbody><tr id="row48839530"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="p63687823"><a name="p63687823"></a><a name="p63687823"></a>northeast</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="p58221122125517"><a name="p58221122125517"></a><a name="p58221122125517"></a>Mandatory</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.3 "><p id="p58440016"><a name="p58440016"></a><a name="p58440016"></a><a href="input-params.md#section1256775182913">Coordinate</a></p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="p36020887"><a name="p36020887"></a><a name="p36020887"></a>Coordinates of the northeast corner. </p>
</td>
</tr>
<tr id="row55752527"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="p19660823"><a name="p19660823"></a><a name="p19660823"></a>southwest</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="p38221222185512"><a name="p38221222185512"></a><a name="p38221222185512"></a>Mandatory</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.3 "><p id="p49022807"><a name="p49022807"></a><a name="p49022807"></a><a href="input-params.md#section1256775182913">Coordinate</a></p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="p11424440"><a name="p11424440"></a><a name="p11424440"></a>Coordinates of the southwest corner.</p>
</td>
</tr>
</tbody>
</table>

## Path<a name="section1617173616304"></a>

<a name="table17522377"></a>
<table><thead align="left"><tr id="row36351665"><th class="cellrowborder" valign="top" width="18%" id="mcps1.1.5.1.1"><p id="p583184312309"><a name="p583184312309"></a><a name="p583184312309"></a><strong id="b18314433301"><a name="b18314433301"></a><a name="b18314433301"></a>Parameter</strong></p>
</th>
<th class="cellrowborder" valign="top" width="14.000000000000002%" id="mcps1.1.5.1.2"><p id="p168315435304"><a name="p168315435304"></a><a name="p168315435304"></a><strong id="b19831194315309"><a name="b19831194315309"></a><a name="b19831194315309"></a>Mandatory/Optional</strong></p>
</th>
<th class="cellrowborder" valign="top" width="18%" id="mcps1.1.5.1.3"><p id="p58312434307"><a name="p58312434307"></a><a name="p58312434307"></a><strong id="b530034234717"><a name="b530034234717"></a><a name="b530034234717"></a>Type</strong></p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.1.5.1.4"><p id="p78318431303"><a name="p78318431303"></a><a name="p78318431303"></a><strong id="b12768134316474"><a name="b12768134316474"></a><a name="b12768134316474"></a>Description</strong></p>
</th>
</tr>
</thead>
<tbody><tr id="row62220677"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="p6710104"><a name="p6710104"></a><a name="p6710104"></a>steps</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="p6797659105510"><a name="p6797659105510"></a><a name="p6797659105510"></a>Mandatory</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.3 "><p id="p6647531"><a name="p6647531"></a><a name="p6647531"></a><a href="#section8706417143120">Step</a>[]</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="p1579110"><a name="p1579110"></a><a name="p1579110"></a>Route section information.</p>
</td>
</tr>
<tr id="row14211994"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="p10320902"><a name="p10320902"></a><a name="p10320902"></a>distance</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="p13797115910558"><a name="p13797115910558"></a><a name="p13797115910558"></a>Optional</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.3 "><p id="p30686701"><a name="p30686701"></a><a name="p30686701"></a>double</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="p2594873"><a name="p2594873"></a><a name="p2594873"></a>Route distance, in meters.</p>
</td>
</tr>
<tr id="row17748173111477"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="p111219528013"><a name="p111219528013"></a><a name="p111219528013"></a>distanceText</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="p485174611568"><a name="p485174611568"></a><a name="p485174611568"></a>Optional</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.3 "><p id="p1612135214013"><a name="p1612135214013"></a><a name="p1612135214013"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="p121211452104"><a name="p121211452104"></a><a name="p121211452104"></a>Distance description.</p>
</td>
</tr>
<tr id="row23353865"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="p12614887"><a name="p12614887"></a><a name="p12614887"></a>duration</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="p2040134695615"><a name="p2040134695615"></a><a name="p2040134695615"></a>Optional</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.3 "><p id="p15172893"><a name="p15172893"></a><a name="p15172893"></a>double</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="p21044820"><a name="p21044820"></a><a name="p21044820"></a>Journey time, in seconds.</p>
</td>
</tr>
<tr id="row2010013386016"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="p9901175910019"><a name="p9901175910019"></a><a name="p9901175910019"></a>durationText</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="p1813314665615"><a name="p1813314665615"></a><a name="p1813314665615"></a>Optional</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.3 "><p id="p14901059008"><a name="p14901059008"></a><a name="p14901059008"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="p79011559704"><a name="p79011559704"></a><a name="p79011559704"></a>Journey time description.</p>
</td>
</tr>
<tr id="row55185655"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="p40853074"><a name="p40853074"></a><a name="p40853074"></a>durationInTraffic</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="p91261646105619"><a name="p91261646105619"></a><a name="p91261646105619"></a>Optional</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.3 "><p id="p20764673"><a name="p20764673"></a><a name="p20764673"></a>double</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="p4216941"><a name="p4216941"></a><a name="p4216941"></a>Journey time calculated based on the real-time traffic condition, in seconds.</p>
</td>
</tr>
<tr id="row2077115617018"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="p647192487"><a name="p647192487"></a><a name="p647192487"></a>durationInTrafficText</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="p34913237486"><a name="p34913237486"></a><a name="p34913237486"></a>Optional</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.3 "><p id="p1641919114814"><a name="p1641919114814"></a><a name="p1641919114814"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="p194181974816"><a name="p194181974816"></a><a name="p194181974816"></a>Journey time description.</p>
</td>
</tr>
<tr id="row37952469"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="p54251110"><a name="p54251110"></a><a name="p54251110"></a>startLocation</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="p714015466562"><a name="p714015466562"></a><a name="p714015466562"></a>Mandatory</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.3 "><p id="p32263784"><a name="p32263784"></a><a name="p32263784"></a><a href="input-params.md#section1256775182913">Coordinate</a></p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="p63229698"><a name="p63229698"></a><a name="p63229698"></a>Longitude and latitude of the departure place.</p>
</td>
</tr>
<tr id="row16845881712"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="p37691319119"><a name="p37691319119"></a><a name="p37691319119"></a>startAddress</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="p1614764645611"><a name="p1614764645611"></a><a name="p1614764645611"></a>Optional</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.3 "><p id="p1476141318114"><a name="p1476141318114"></a><a name="p1476141318114"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="p87612139118"><a name="p87612139118"></a><a name="p87612139118"></a>Departure place details.</p>
</td>
</tr>
<tr id="row32196376"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="p57769674"><a name="p57769674"></a><a name="p57769674"></a>endLocation</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="p015216469568"><a name="p015216469568"></a><a name="p015216469568"></a>Mandatory</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.3 "><p id="p48832041"><a name="p48832041"></a><a name="p48832041"></a><a href="input-params.md#section1256775182913">Coordinate</a></p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="p63081244"><a name="p63081244"></a><a name="p63081244"></a>Longitude and latitude of the destination.</p>
</td>
</tr>
<tr id="row23353151013"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="p1259621914118"><a name="p1259621914118"></a><a name="p1259621914118"></a>endAddress</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="p116084613566"><a name="p116084613566"></a><a name="p116084613566"></a>Optional</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.3 "><p id="p1359614191515"><a name="p1359614191515"></a><a name="p1359614191515"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="p1359611194113"><a name="p1359611194113"></a><a name="p1359611194113"></a>Destination details.</p>
</td>
</tr>
<tr id="row1838116367116"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.1 "><p id="p126078391917"><a name="p126078391917"></a><a name="p126078391917"></a>viaWaypoints</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="p716754645617"><a name="p716754645617"></a><a name="p716754645617"></a>Optional</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.5.1.3 "><p id="p13607939515"><a name="p13607939515"></a><a name="p13607939515"></a><a href="#section87541839183119">ViaWaypoint</a>[]</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.5.1.4 "><p id="p66071391712"><a name="p66071391712"></a><a name="p66071391712"></a>Waypoint information. </p>
</td>
</tr>
</tbody>
</table>

## Route<a name="section05097566301"></a>

<a name="table4864091"></a>
<table><thead align="left"><tr id="row4080300"><th class="cellrowborder" valign="top" width="18%" id="mcps1.1.6.1.1"><p id="p11684847313"><a name="p11684847313"></a><a name="p11684847313"></a><strong id="b136841413318"><a name="b136841413318"></a><a name="b136841413318"></a>Parameter</strong></p>
</th>
<th class="cellrowborder" valign="top" width="14.000000000000002%" id="mcps1.1.6.1.2"><p id="p176841049313"><a name="p176841049313"></a><a name="p176841049313"></a><strong id="b136841844317"><a name="b136841844317"></a><a name="b136841844317"></a>Mandatory/Optional</strong></p>
</th>
<th class="cellrowborder" valign="top" width="18.96%" id="mcps1.1.6.1.3"><p id="p768424203111"><a name="p768424203111"></a><a name="p768424203111"></a><strong id="b92881327194813"><a name="b92881327194813"></a><a name="b92881327194813"></a>Type</strong></p>
</th>
<th class="cellrowborder" valign="top" width="34.68%" id="mcps1.1.6.1.4"><p id="p368515415313"><a name="p368515415313"></a><a name="p368515415313"></a><strong id="b52261290483"><a name="b52261290483"></a><a name="b52261290483"></a>Description</strong></p>
</th>
<th class="cellrowborder" valign="top" width="14.360000000000001%" id="mcps1.1.6.1.5"><p id="p161228128389"><a name="p161228128389"></a><a name="p161228128389"></a><strong id="b13764636124413"><a name="b13764636124413"></a><a name="b13764636124413"></a>Value</strong></p>
</th>
</tr>
</thead>
<tbody><tr id="row31474554"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.6.1.1 "><p id="p66410939"><a name="p66410939"></a><a name="p66410939"></a>paths</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.6.1.2 "><p id="p798823314570"><a name="p798823314570"></a><a name="p798823314570"></a>Mandatory</p>
</td>
<td class="cellrowborder" valign="top" width="18.96%" headers="mcps1.1.6.1.3 "><p id="p10576944"><a name="p10576944"></a><a name="p10576944"></a><a href="#section1617173616304">Path</a>[]</p>
</td>
<td class="cellrowborder" valign="top" width="34.68%" headers="mcps1.1.6.1.4 "><p id="p51426113"><a name="p51426113"></a><a name="p51426113"></a>Route planning information.</p>
</td>
<td class="cellrowborder" valign="top" width="14.360000000000001%" headers="mcps1.1.6.1.5 "><p id="p11221124389"><a name="p11221124389"></a><a name="p11221124389"></a>-</p>
</td>
</tr>
<tr id="row60181840"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.6.1.1 "><p id="p42890904"><a name="p42890904"></a><a name="p42890904"></a>optimizedWaypoints</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.6.1.2 "><p id="p20988133195714"><a name="p20988133195714"></a><a name="p20988133195714"></a>Optional</p>
</td>
<td class="cellrowborder" valign="top" width="18.96%" headers="mcps1.1.6.1.3 "><p id="p51611184"><a name="p51611184"></a><a name="p51611184"></a>int[]</p>
</td>
<td class="cellrowborder" valign="top" width="34.68%" headers="mcps1.1.6.1.4 "><p id="p19756352"><a name="p19756352"></a><a name="p19756352"></a>Optimized waypoint index. This parameter is available only when <strong id="b12861932174812"><a name="b12861932174812"></a><a name="b12861932174812"></a>viaType</strong> is set to <strong id="b98612325487"><a name="b98612325487"></a><a name="b98612325487"></a>false</strong> and <strong id="b16861432114814"><a name="b16861432114814"></a><a name="b16861432114814"></a>optimize</strong> is set to <strong id="b887332124811"><a name="b887332124811"></a><a name="b887332124811"></a>true</strong>.</p>
</td>
<td class="cellrowborder" valign="top" width="14.360000000000001%" headers="mcps1.1.6.1.5 "><p id="p0122412143816"><a name="p0122412143816"></a><a name="p0122412143816"></a>-</p>
</td>
</tr>
<tr id="row43589445"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.6.1.1 "><p id="p41084157"><a name="p41084157"></a><a name="p41084157"></a>bounds</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.6.1.2 "><p id="p798843314571"><a name="p798843314571"></a><a name="p798843314571"></a>Optional</p>
</td>
<td class="cellrowborder" valign="top" width="18.96%" headers="mcps1.1.6.1.3 "><p id="p39482434"><a name="p39482434"></a><a name="p39482434"></a><a href="#section11213141013305">CoordinateBounds</a></p>
</td>
<td class="cellrowborder" valign="top" width="34.68%" headers="mcps1.1.6.1.4 "><p id="p43960571"><a name="p43960571"></a><a name="p43960571"></a>Route bounds.</p>
</td>
<td class="cellrowborder" valign="top" width="14.360000000000001%" headers="mcps1.1.6.1.5 "><p id="p8122141214383"><a name="p8122141214383"></a><a name="p8122141214383"></a>-</p>
</td>
</tr>
<tr id="row4253447203613"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.6.1.1 "><p id="p325424773620"><a name="p325424773620"></a><a name="p325424773620"></a>hasRestrictedRoad</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.6.1.2 "><p id="p112541447103614"><a name="p112541447103614"></a><a name="p112541447103614"></a>Optional</p>
</td>
<td class="cellrowborder" valign="top" width="18.96%" headers="mcps1.1.6.1.3 "><p id="p143916375331"><a name="p143916375331"></a><a name="p143916375331"></a>int</p>
</td>
<td class="cellrowborder" valign="top" width="34.68%" headers="mcps1.1.6.1.4 "><p id="p182541147113619"><a name="p182541147113619"></a><a name="p182541147113619"></a>Indicates whether the route includes private or restricted roads. </p>
</td>
<td class="cellrowborder" rowspan="9" valign="top" width="14.360000000000001%" headers="mcps1.1.6.1.5 "><a name="ul16197141823415"></a><a name="ul16197141823415"></a><ul id="ul16197141823415"><li><strong id="b179213526447"><a name="b179213526447"></a><a name="b179213526447"></a>0</strong>: no</li><li><strong id="b0943153104415"><a name="b0943153104415"></a><a name="b0943153104415"></a>1</strong>: yes</li></ul>
</td>
</tr>
<tr id="row15554165843612"><td class="cellrowborder" valign="top" headers="mcps1.1.6.1.1 "><p id="p15541558203611"><a name="p15541558203611"></a><a name="p15541558203611"></a>dstInRestrictedArea</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.6.1.2 "><p id="p1554175823615"><a name="p1554175823615"></a><a name="p1554175823615"></a>Optional</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.6.1.3 "><p id="p341416386333"><a name="p341416386333"></a><a name="p341416386333"></a>int</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.6.1.4 "><p id="p19554658103611"><a name="p19554658103611"></a><a name="p19554658103611"></a>Indicates whether the destination is in a restricted area.</p>
</td>
</tr>
<tr id="row106664611371"><td class="cellrowborder" valign="top" headers="mcps1.1.6.1.1 "><p id="p146676612372"><a name="p146676612372"></a><a name="p146676612372"></a>crossCountry</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.6.1.2 "><p id="p466712663711"><a name="p466712663711"></a><a name="p466712663711"></a>Optional</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.6.1.3 "><p id="p73281639193315"><a name="p73281639193315"></a><a name="p73281639193315"></a>int</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.6.1.4 "><p id="p432310481281"><a name="p432310481281"></a><a name="p432310481281"></a>Indicates whether the route crosses a country boundary. </p>
</td>
</tr>
<tr id="row15239161213379"><td class="cellrowborder" valign="top" headers="mcps1.1.6.1.1 "><p id="p623961273710"><a name="p623961273710"></a><a name="p623961273710"></a>crossMultiCountries</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.6.1.2 "><p id="p65158516280"><a name="p65158516280"></a><a name="p65158516280"></a>Optional</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.6.1.3 "><p id="p681104015337"><a name="p681104015337"></a><a name="p681104015337"></a>int</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.6.1.4 "><p id="p15239141223715"><a name="p15239141223715"></a><a name="p15239141223715"></a>Indicates whether the route crosses multiple country boundaries.</p>
</td>
</tr>
<tr id="row1510411814376"><td class="cellrowborder" valign="top" headers="mcps1.1.6.1.1 "><p id="p5104818113718"><a name="p5104818113718"></a><a name="p5104818113718"></a>hasRoughRoad</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.6.1.2 "><p id="p31041218163710"><a name="p31041218163710"></a><a name="p31041218163710"></a>Optional</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.6.1.3 "><p id="p48651240163312"><a name="p48651240163312"></a><a name="p48651240163312"></a>int</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.6.1.4 "><p id="p1110416188379"><a name="p1110416188379"></a><a name="p1110416188379"></a>Indicates whether the route includes rough roads.</p>
</td>
</tr>
<tr id="row914542403717"><td class="cellrowborder" valign="top" headers="mcps1.1.6.1.1 "><p id="p1014502414372"><a name="p1014502414372"></a><a name="p1014502414372"></a>dstInDiffTimeZone</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.6.1.2 "><p id="p2145202418373"><a name="p2145202418373"></a><a name="p2145202418373"></a>Optional</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.6.1.3 "><p id="p159127414331"><a name="p159127414331"></a><a name="p159127414331"></a>int</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.6.1.4 "><p id="p8145324133711"><a name="p8145324133711"></a><a name="p8145324133711"></a>Indicates whether the time zone of the destination is different from that of the departure place.</p>
</td>
</tr>
<tr id="row49570296378"><td class="cellrowborder" valign="top" headers="mcps1.1.6.1.1 "><p id="p15958132911372"><a name="p15958132911372"></a><a name="p15958132911372"></a>hasFerry</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.6.1.2 "><p id="p8958102923714"><a name="p8958102923714"></a><a name="p8958102923714"></a>Optional</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.6.1.3 "><p id="p179853426336"><a name="p179853426336"></a><a name="p179853426336"></a>int</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.6.1.4 "><p id="p196645236295"><a name="p196645236295"></a><a name="p196645236295"></a>Indicates whether the route includes ferry.</p>
</td>
</tr>
<tr id="row124081935103712"><td class="cellrowborder" valign="top" headers="mcps1.1.6.1.1 "><p id="p9408173512374"><a name="p9408173512374"></a><a name="p9408173512374"></a>hasTrafficLight</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.6.1.2 "><p id="p9408143513712"><a name="p9408143513712"></a><a name="p9408143513712"></a>Optional</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.6.1.3 "><p id="p17122544173310"><a name="p17122544173310"></a><a name="p17122544173310"></a>int</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.6.1.4 "><p id="p1140883517372"><a name="p1140883517372"></a><a name="p1140883517372"></a>Indicates whether the route has traffic lights.</p>
</td>
</tr>
<tr id="row11985441103718"><td class="cellrowborder" valign="top" headers="mcps1.1.6.1.1 "><p id="p2098618413375"><a name="p2098618413375"></a><a name="p2098618413375"></a>hasTolls</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.6.1.2 "><p id="p89861241133712"><a name="p89861241133712"></a><a name="p89861241133712"></a>Optional</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.6.1.3 "><p id="p3201194518331"><a name="p3201194518331"></a><a name="p3201194518331"></a>int</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.6.1.4 "><p id="p398644113712"><a name="p398644113712"></a><a name="p398644113712"></a>Indicates whether the route includes toll gates.</p>
</td>
</tr>
<tr id="row77061636103610"><td class="cellrowborder" valign="top" width="18%" headers="mcps1.1.6.1.1 "><p id="p53574557295"><a name="p53574557295"></a><a name="p53574557295"></a>trafficLightNum</p>
</td>
<td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.6.1.2 "><p id="p20992123710367"><a name="p20992123710367"></a><a name="p20992123710367"></a>Optional</p>
</td>
<td class="cellrowborder" valign="top" width="18.96%" headers="mcps1.1.6.1.3 "><p id="p85545424286"><a name="p85545424286"></a><a name="p85545424286"></a>int</p>
</td>
<td class="cellrowborder" valign="top" width="34.68%" headers="mcps1.1.6.1.4 "><p id="p17834102372816"><a name="p17834102372816"></a><a name="p17834102372816"></a>Number of traffic lights.</p>
</td>
<td class="cellrowborder" valign="top" width="14.360000000000001%" headers="mcps1.1.6.1.5 "><p id="p61231121388"><a name="p61231121388"></a><a name="p61231121388"></a>-</p>
</td>
</tr>
</tbody>
</table>

## Step<a name="section8706417143120"></a>

<a name="table37057034"></a>
<table><thead align="left"><tr id="row13886058"><th class="cellrowborder" valign="top" width="18.18%" id="mcps1.1.5.1.1"><p id="p329920277311"><a name="p329920277311"></a><a name="p329920277311"></a><strong id="b529942718312"><a name="b529942718312"></a><a name="b529942718312"></a>Parameter</strong></p>
</th>
<th class="cellrowborder" valign="top" width="12.73%" id="mcps1.1.5.1.2"><p id="p12299102713314"><a name="p12299102713314"></a><a name="p12299102713314"></a><strong id="b16299192793115"><a name="b16299192793115"></a><a name="b16299192793115"></a>Mandatory/Optional</strong></p>
</th>
<th class="cellrowborder" valign="top" width="16.36%" id="mcps1.1.5.1.3"><p id="p929942713315"><a name="p929942713315"></a><a name="p929942713315"></a><strong id="b15136546114811"><a name="b15136546114811"></a><a name="b15136546114811"></a>Type</strong></p>
</th>
<th class="cellrowborder" valign="top" width="52.73%" id="mcps1.1.5.1.4"><p id="p829922793116"><a name="p829922793116"></a><a name="p829922793116"></a><strong id="b473394744812"><a name="b473394744812"></a><a name="b473394744812"></a>Description</strong></p>
</th>
</tr>
</thead>
<tbody><tr id="row59133445"><td class="cellrowborder" valign="top" width="18.18%" headers="mcps1.1.5.1.1 "><p id="p25079723"><a name="p25079723"></a><a name="p25079723"></a>distance</p>
</td>
<td class="cellrowborder" valign="top" width="12.73%" headers="mcps1.1.5.1.2 "><p id="p952182015817"><a name="p952182015817"></a><a name="p952182015817"></a>Optional</p>
</td>
<td class="cellrowborder" valign="top" width="16.36%" headers="mcps1.1.5.1.3 "><p id="p18191719"><a name="p18191719"></a><a name="p18191719"></a>double</p>
</td>
<td class="cellrowborder" valign="top" width="52.73%" headers="mcps1.1.5.1.4 "><p id="p64243102"><a name="p64243102"></a><a name="p64243102"></a>Route distance, in meters.</p>
</td>
</tr>
<tr id="row177481456611"><td class="cellrowborder" valign="top" width="18.18%" headers="mcps1.1.5.1.1 "><p id="p12300122703110"><a name="p12300122703110"></a><a name="p12300122703110"></a>distanceText</p>
</td>
<td class="cellrowborder" valign="top" width="12.73%" headers="mcps1.1.5.1.2 "><p id="p092815216594"><a name="p092815216594"></a><a name="p092815216594"></a>Optional</p>
</td>
<td class="cellrowborder" valign="top" width="16.36%" headers="mcps1.1.5.1.3 "><p id="p1830092733117"><a name="p1830092733117"></a><a name="p1830092733117"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="52.73%" headers="mcps1.1.5.1.4 "><p id="p93001127163113"><a name="p93001127163113"></a><a name="p93001127163113"></a>Distance description.</p>
</td>
</tr>
<tr id="row20155171210496"><td class="cellrowborder" valign="top" width="18.18%" headers="mcps1.1.5.1.1 "><p id="p169771420124919"><a name="p169771420124919"></a><a name="p169771420124919"></a>duration</p>
</td>
<td class="cellrowborder" valign="top" width="12.73%" headers="mcps1.1.5.1.2 "><p id="p1614642312499"><a name="p1614642312499"></a><a name="p1614642312499"></a>Optional</p>
</td>
<td class="cellrowborder" valign="top" width="16.36%" headers="mcps1.1.5.1.3 "><p id="p11977820104912"><a name="p11977820104912"></a><a name="p11977820104912"></a>double</p>
</td>
<td class="cellrowborder" valign="top" width="52.73%" headers="mcps1.1.5.1.4 "><p id="p797742018498"><a name="p797742018498"></a><a name="p797742018498"></a>Journey time, in seconds.</p>
</td>
</tr>
<tr id="row176626592120"><td class="cellrowborder" valign="top" width="18.18%" headers="mcps1.1.5.1.1 "><p id="p1300172716317"><a name="p1300172716317"></a><a name="p1300172716317"></a>durationText</p>
</td>
<td class="cellrowborder" valign="top" width="12.73%" headers="mcps1.1.5.1.2 "><p id="p6199316599"><a name="p6199316599"></a><a name="p6199316599"></a>Optional</p>
</td>
<td class="cellrowborder" valign="top" width="16.36%" headers="mcps1.1.5.1.3 "><p id="p15300327163112"><a name="p15300327163112"></a><a name="p15300327163112"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="52.73%" headers="mcps1.1.5.1.4 "><p id="p10300132763114"><a name="p10300132763114"></a><a name="p10300132763114"></a>Journey time description.</p>
</td>
</tr>
<tr id="row36391162"><td class="cellrowborder" valign="top" width="18.18%" headers="mcps1.1.5.1.1 "><p id="p62003000"><a name="p62003000"></a><a name="p62003000"></a>startLocation</p>
</td>
<td class="cellrowborder" valign="top" width="12.73%" headers="mcps1.1.5.1.2 "><p id="p02811335918"><a name="p02811335918"></a><a name="p02811335918"></a>Optional</p>
</td>
<td class="cellrowborder" valign="top" width="16.36%" headers="mcps1.1.5.1.3 "><p id="p56187107"><a name="p56187107"></a><a name="p56187107"></a><a href="input-params.md#section1256775182913">Coordinate</a></p>
</td>
<td class="cellrowborder" valign="top" width="52.73%" headers="mcps1.1.5.1.4 "><p id="p54861794"><a name="p54861794"></a><a name="p54861794"></a>Longitude and latitude of the departure place.</p>
</td>
</tr>
<tr id="row23994101"><td class="cellrowborder" valign="top" width="18.18%" headers="mcps1.1.5.1.1 "><p id="p0301132719315"><a name="p0301132719315"></a><a name="p0301132719315"></a>endLocation</p>
</td>
<td class="cellrowborder" valign="top" width="12.73%" headers="mcps1.1.5.1.2 "><p id="p047137595"><a name="p047137595"></a><a name="p047137595"></a>Optional</p>
</td>
<td class="cellrowborder" valign="top" width="16.36%" headers="mcps1.1.5.1.3 "><p id="p130172715315"><a name="p130172715315"></a><a name="p130172715315"></a><a href="input-params.md#section1256775182913">Coordinate</a></p>
</td>
<td class="cellrowborder" valign="top" width="52.73%" headers="mcps1.1.5.1.4 "><p id="p33011127183112"><a name="p33011127183112"></a><a name="p33011127183112"></a>Longitude and latitude of the destination.</p>
</td>
</tr>
<tr id="row39254219"><td class="cellrowborder" valign="top" width="18.18%" headers="mcps1.1.5.1.1 "><p id="p25475209"><a name="p25475209"></a><a name="p25475209"></a>action</p>
</td>
<td class="cellrowborder" valign="top" width="12.73%" headers="mcps1.1.5.1.2 "><p id="p6670335915"><a name="p6670335915"></a><a name="p6670335915"></a>Optional</p>
</td>
<td class="cellrowborder" valign="top" width="16.36%" headers="mcps1.1.5.1.3 "><p id="p50226059"><a name="p50226059"></a><a name="p50226059"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="52.73%" headers="mcps1.1.5.1.4 "><p id="p41779002"><a name="p41779002"></a><a name="p41779002"></a>Operation to be performed in the current step. The options are as follows:</p>
<a name="ul8691751191610"></a><a name="ul8691751191610"></a><ul id="ul8691751191610"><li>TURN_SLIGHT_LEFT</li><li>TURN_SHARP_LEFT</li><li>UTURN_LEFT</li><li>TURN_LEFT</li><li>TURN_SLIGHT_RIGHT</li><li>TURN_SHARP_RIGHT</li><li>UTURN_RIGHT</li><li>TURN_RIGHT</li><li>STRAIGHT</li><li>RAMP_LEFT</li><li>RAMP_RIGHT</li><li>MERGE</li><li>FORK_LEFT</li><li>FORK_RIGHT</li><li>FERRY (not supported currently)</li><li>FERRY_TRAIN (not supported currently)</li><li>ROUNDABOUT_LEFT</li><li>ROUNDABOUT_RIGHT</li></ul>
</td>
</tr>
<tr id="row43154428"><td class="cellrowborder" valign="top" width="18.18%" headers="mcps1.1.5.1.1 "><p id="p5847780"><a name="p5847780"></a><a name="p5847780"></a>polyline</p>
</td>
<td class="cellrowborder" valign="top" width="12.73%" headers="mcps1.1.5.1.2 "><p id="p977193145919"><a name="p977193145919"></a><a name="p977193145919"></a>Optional</p>
</td>
<td class="cellrowborder" valign="top" width="16.36%" headers="mcps1.1.5.1.3 "><p id="p3908185"><a name="p3908185"></a><a name="p3908185"></a><a href="input-params.md#section1256775182913">Coordinate</a>[]</p>
</td>
<td class="cellrowborder" valign="top" width="52.73%" headers="mcps1.1.5.1.4 "><p id="p48127554"><a name="p48127554"></a><a name="p48127554"></a>A series of coordinates of a road section (including coordinates of the departure place and destination).</p>
</td>
</tr>
<tr id="row30494806"><td class="cellrowborder" valign="top" width="18.18%" headers="mcps1.1.5.1.1 "><p id="p54160201"><a name="p54160201"></a><a name="p54160201"></a>roadName</p>
</td>
<td class="cellrowborder" valign="top" width="12.73%" headers="mcps1.1.5.1.2 "><p id="p4879375915"><a name="p4879375915"></a><a name="p4879375915"></a>Optional</p>
</td>
<td class="cellrowborder" valign="top" width="16.36%" headers="mcps1.1.5.1.3 "><p id="p24900132"><a name="p24900132"></a><a name="p24900132"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="52.73%" headers="mcps1.1.5.1.4 "><p id="p3644816"><a name="p3644816"></a><a name="p3644816"></a>Road name.</p>
</td>
</tr>
<tr id="row32803348"><td class="cellrowborder" valign="top" width="18.18%" headers="mcps1.1.5.1.1 "><p id="p39825499"><a name="p39825499"></a><a name="p39825499"></a>orientation</p>
</td>
<td class="cellrowborder" valign="top" width="12.73%" headers="mcps1.1.5.1.2 "><p id="p198635594"><a name="p198635594"></a><a name="p198635594"></a>Optional</p>
</td>
<td class="cellrowborder" valign="top" width="16.36%" headers="mcps1.1.5.1.3 "><p id="p4640007"><a name="p4640007"></a><a name="p4640007"></a>int</p>
</td>
<td class="cellrowborder" valign="top" width="52.73%" headers="mcps1.1.5.1.4 "><p id="p40296320"><a name="p40296320"></a><a name="p40296320"></a>Road direction. The options are as follows:</p>
<a name="ul124261012477"></a><a name="ul124261012477"></a><ul id="ul124261012477"><li><strong id="b1854182944912"><a name="b1854182944912"></a><a name="b1854182944912"></a>0</strong>: bidirectional</li><li><strong id="b20502183074917"><a name="b20502183074917"></a><a name="b20502183074917"></a>1</strong>: forward direction</li><li><strong id="b34126313493"><a name="b34126313493"></a><a name="b34126313493"></a>2</strong>: reverse direction</li></ul>
</td>
</tr>
<tr id="row485132914212"><td class="cellrowborder" valign="top" width="18.18%" headers="mcps1.1.5.1.1 "><p id="p25481333627"><a name="p25481333627"></a><a name="p25481333627"></a>instruction</p>
</td>
<td class="cellrowborder" valign="top" width="12.73%" headers="mcps1.1.5.1.2 "><p id="p18109336593"><a name="p18109336593"></a><a name="p18109336593"></a>Optional</p>
</td>
<td class="cellrowborder" valign="top" width="16.36%" headers="mcps1.1.5.1.3 "><p id="p135481334218"><a name="p135481334218"></a><a name="p135481334218"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="52.73%" headers="mcps1.1.5.1.4 "><p id="p125481733728"><a name="p125481733728"></a><a name="p125481733728"></a>Instruction description.</p>
</td>
</tr>
</tbody>
</table>

## ViaWayPoints<a name="section87541839183119"></a>

<a name="table9658556153112"></a>
<table><thead align="left"><tr id="row665845617319"><th class="cellrowborder" valign="top" width="16.6%" id="mcps1.1.5.1.1"><p id="p146581756103112"><a name="p146581756103112"></a><a name="p146581756103112"></a><strong id="b1365805620310"><a name="b1365805620310"></a><a name="b1365805620310"></a>Parameter</strong></p>
</th>
<th class="cellrowborder" valign="top" width="22.18%" id="mcps1.1.5.1.2"><p id="p1065818563315"><a name="p1065818563315"></a><a name="p1065818563315"></a><strong id="b065811566314"><a name="b065811566314"></a><a name="b065811566314"></a>Mandatory/Optional</strong></p>
</th>
<th class="cellrowborder" valign="top" width="18.23%" id="mcps1.1.5.1.3"><p id="p26581656193117"><a name="p26581656193117"></a><a name="p26581656193117"></a><strong id="b072713340506"><a name="b072713340506"></a><a name="b072713340506"></a>Type</strong></p>
</th>
<th class="cellrowborder" valign="top" width="42.99%" id="mcps1.1.5.1.4"><p id="p9658195603110"><a name="p9658195603110"></a><a name="p9658195603110"></a><strong id="b849523685013"><a name="b849523685013"></a><a name="b849523685013"></a>Description</strong></p>
</th>
</tr>
</thead>
<tbody><tr id="row15658175611318"><td class="cellrowborder" valign="top" width="16.6%" headers="mcps1.1.5.1.1 "><p id="p840075113318"><a name="p840075113318"></a><a name="p840075113318"></a>location</p>
</td>
<td class="cellrowborder" valign="top" width="22.18%" headers="mcps1.1.5.1.2 "><p id="p113691522135917"><a name="p113691522135917"></a><a name="p113691522135917"></a>Mandatory</p>
</td>
<td class="cellrowborder" valign="top" width="18.23%" headers="mcps1.1.5.1.3 "><p id="p74001051131"><a name="p74001051131"></a><a name="p74001051131"></a><a href="input-params.md#section1256775182913">Coordinate</a></p>
</td>
<td class="cellrowborder" valign="top" width="42.99%" headers="mcps1.1.5.1.4 "><p id="p16400175114316"><a name="p16400175114316"></a><a name="p16400175114316"></a>Longitude and latitude of the waypoint.</p>
</td>
</tr>
<tr id="row9659195693116"><td class="cellrowborder" valign="top" width="16.6%" headers="mcps1.1.5.1.1 "><p id="p94005512313"><a name="p94005512313"></a><a name="p94005512313"></a>stepIndex</p>
</td>
<td class="cellrowborder" valign="top" width="22.18%" headers="mcps1.1.5.1.2 "><p id="p19369422145916"><a name="p19369422145916"></a><a name="p19369422145916"></a>Mandatory</p>
</td>
<td class="cellrowborder" valign="top" width="18.23%" headers="mcps1.1.5.1.3 "><p id="p240019514317"><a name="p240019514317"></a><a name="p240019514317"></a>int</p>
</td>
<td class="cellrowborder" valign="top" width="42.99%" headers="mcps1.1.5.1.4 "><p id="p24007515319"><a name="p24007515319"></a><a name="p24007515319"></a>Waypoint index in the <strong id="b28640407508"><a name="b28640407508"></a><a name="b28640407508"></a>Step</strong> array. </p>
</td>
</tr>
</tbody>
</table>

## Row<a name="section98851198326"></a>

<a name="table9594192033211"></a>
<table><thead align="left"><tr id="row1859422010328"><th class="cellrowborder" valign="top" width="16.46%" id="mcps1.1.5.1.1"><p id="p15594220193212"><a name="p15594220193212"></a><a name="p15594220193212"></a><strong id="b659452073220"><a name="b659452073220"></a><a name="b659452073220"></a>Parameter</strong></p>
</th>
<th class="cellrowborder" valign="top" width="22.59%" id="mcps1.1.5.1.2"><p id="p6594142003212"><a name="p6594142003212"></a><a name="p6594142003212"></a><strong id="b1559411206322"><a name="b1559411206322"></a><a name="b1559411206322"></a>Mandatory/Optional</strong></p>
</th>
<th class="cellrowborder" valign="top" width="18.64%" id="mcps1.1.5.1.3"><p id="p159552011324"><a name="p159552011324"></a><a name="p159552011324"></a><strong id="b974494511504"><a name="b974494511504"></a><a name="b974494511504"></a>Type</strong></p>
</th>
<th class="cellrowborder" valign="top" width="42.309999999999995%" id="mcps1.1.5.1.4"><p id="p5595172019323"><a name="p5595172019323"></a><a name="p5595172019323"></a><strong id="b25841447205015"><a name="b25841447205015"></a><a name="b25841447205015"></a>Description</strong></p>
</th>
</tr>
</thead>
<tbody><tr id="row1595202014324"><td class="cellrowborder" valign="top" width="16.46%" headers="mcps1.1.5.1.1 "><p id="p1260131124415"><a name="p1260131124415"></a><a name="p1260131124415"></a>cells</p>
</td>
<td class="cellrowborder" valign="top" width="22.59%" headers="mcps1.1.5.1.2 "><p id="p178331818104"><a name="p178331818104"></a><a name="p178331818104"></a>Mandatory</p>
</td>
<td class="cellrowborder" valign="top" width="18.64%" headers="mcps1.1.5.1.3 "><p id="p9100194174418"><a name="p9100194174418"></a><a name="p9100194174418"></a><a href="#section1110111245321">Cell</a>[]</p>
</td>
<td class="cellrowborder" valign="top" width="42.309999999999995%" headers="mcps1.1.5.1.4 "><p id="p110034112445"><a name="p110034112445"></a><a name="p110034112445"></a>Information about each cell in the distance matrix. </p>
</td>
</tr>
</tbody>
</table>

## Cell<a name="section1110111245321"></a>

<a name="table893518377324"></a>
<table><thead align="left"><tr id="row10935153717320"><th class="cellrowborder" valign="top" width="16.46%" id="mcps1.1.5.1.1"><p id="p1193514373328"><a name="p1193514373328"></a><a name="p1193514373328"></a><strong id="b17935103719327"><a name="b17935103719327"></a><a name="b17935103719327"></a>Parameter</strong></p>
</th>
<th class="cellrowborder" valign="top" width="22.31%" id="mcps1.1.5.1.2"><p id="p993510378328"><a name="p993510378328"></a><a name="p993510378328"></a><strong id="b293603720327"><a name="b293603720327"></a><a name="b293603720327"></a>Mandatory/Optional</strong></p>
</th>
<th class="cellrowborder" valign="top" width="19.32%" id="mcps1.1.5.1.3"><p id="p29361337143220"><a name="p29361337143220"></a><a name="p29361337143220"></a><strong id="b14868195618501"><a name="b14868195618501"></a><a name="b14868195618501"></a>Type</strong></p>
</th>
<th class="cellrowborder" valign="top" width="41.91%" id="mcps1.1.5.1.4"><p id="p193623712326"><a name="p193623712326"></a><a name="p193623712326"></a><strong id="b148218584501"><a name="b148218584501"></a><a name="b148218584501"></a>Description</strong></p>
</th>
</tr>
</thead>
<tbody><tr id="row4936183763216"><td class="cellrowborder" valign="top" width="16.46%" headers="mcps1.1.5.1.1 "><p id="p1938695094513"><a name="p1938695094513"></a><a name="p1938695094513"></a>status</p>
</td>
<td class="cellrowborder" valign="top" width="22.31%" headers="mcps1.1.5.1.2 "><p id="p172341715602"><a name="p172341715602"></a><a name="p172341715602"></a>Mandatory</p>
</td>
<td class="cellrowborder" valign="top" width="19.32%" headers="mcps1.1.5.1.3 "><p id="p038616505454"><a name="p038616505454"></a><a name="p038616505454"></a>int</p>
</td>
<td class="cellrowborder" valign="top" width="41.91%" headers="mcps1.1.5.1.4 "><p id="p738645014454"><a name="p738645014454"></a><a name="p738645014454"></a>Result code for route calculation between the departure place and destination. For details, please refer to <a href="error-code.md">Result Codes</a>.</p>
</td>
</tr>
<tr id="row33921844144518"><td class="cellrowborder" valign="top" width="16.46%" headers="mcps1.1.5.1.1 "><p id="p73860500451"><a name="p73860500451"></a><a name="p73860500451"></a>distance</p>
</td>
<td class="cellrowborder" valign="top" width="22.31%" headers="mcps1.1.5.1.2 "><p id="p142342151602"><a name="p142342151602"></a><a name="p142342151602"></a>Optional</p>
</td>
<td class="cellrowborder" valign="top" width="19.32%" headers="mcps1.1.5.1.3 "><p id="p63861950144518"><a name="p63861950144518"></a><a name="p63861950144518"></a>double</p>
</td>
<td class="cellrowborder" valign="top" width="41.91%" headers="mcps1.1.5.1.4 "><p id="p15386145016457"><a name="p15386145016457"></a><a name="p15386145016457"></a>Route distance, in meters.</p>
</td>
</tr>
<tr id="row13349163619457"><td class="cellrowborder" valign="top" width="16.46%" headers="mcps1.1.5.1.1 "><p id="p153863506459"><a name="p153863506459"></a><a name="p153863506459"></a>distanceText</p>
</td>
<td class="cellrowborder" valign="top" width="22.31%" headers="mcps1.1.5.1.2 "><p id="p223511156012"><a name="p223511156012"></a><a name="p223511156012"></a>Optional</p>
</td>
<td class="cellrowborder" valign="top" width="19.32%" headers="mcps1.1.5.1.3 "><p id="p17386125094510"><a name="p17386125094510"></a><a name="p17386125094510"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="41.91%" headers="mcps1.1.5.1.4 "><p id="p16386150134514"><a name="p16386150134514"></a><a name="p16386150134514"></a>Distance description.</p>
</td>
</tr>
<tr id="row1792673310458"><td class="cellrowborder" valign="top" width="16.46%" headers="mcps1.1.5.1.1 "><p id="p438625074512"><a name="p438625074512"></a><a name="p438625074512"></a>duration</p>
</td>
<td class="cellrowborder" valign="top" width="22.31%" headers="mcps1.1.5.1.2 "><p id="p142354151301"><a name="p142354151301"></a><a name="p142354151301"></a>Optional</p>
</td>
<td class="cellrowborder" valign="top" width="19.32%" headers="mcps1.1.5.1.3 "><p id="p10386155012451"><a name="p10386155012451"></a><a name="p10386155012451"></a>double</p>
</td>
<td class="cellrowborder" valign="top" width="41.91%" headers="mcps1.1.5.1.4 "><p id="p6386850124511"><a name="p6386850124511"></a><a name="p6386850124511"></a>Journey time, in seconds.</p>
</td>
</tr>
<tr id="row1428343194515"><td class="cellrowborder" valign="top" width="16.46%" headers="mcps1.1.5.1.1 "><p id="p203862050134516"><a name="p203862050134516"></a><a name="p203862050134516"></a>durationText</p>
</td>
<td class="cellrowborder" valign="top" width="22.31%" headers="mcps1.1.5.1.2 "><p id="p323517151905"><a name="p323517151905"></a><a name="p323517151905"></a>Optional</p>
</td>
<td class="cellrowborder" valign="top" width="19.32%" headers="mcps1.1.5.1.3 "><p id="p1338645015458"><a name="p1338645015458"></a><a name="p1338645015458"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="41.91%" headers="mcps1.1.5.1.4 "><p id="p73861050174513"><a name="p73861050174513"></a><a name="p73861050174513"></a>Journey time description.</p>
</td>
</tr>
</tbody>
</table>

