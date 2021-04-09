# CameraPosition.Builder<a name="ZH-CN_TOPIC_0000001099181280"></a>

-   [Public Constructor Summary](#section1399259101117)
-   [Public Method Summary](#section12318155421116)
-   [Public Constructors](#section186512179184)
-   [CameraPosition.Builder](#section168973357123)
-   [Public Methods](#section184955312226)
-   [build](#section141231075266)
-   [bearing](#section676214092616)
-   [target](#section1962717532250)
-   [tilt](#section1341654415259)
-   [zoom](#section178881735182515)


<a name="table9327mcpsimp"></a>
<table><thead align="left"><tr id="row9331mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p9333mcpsimp"><a name="p9333mcpsimp"></a><a name="p9333mcpsimp"></a>Class Info</p>
</th>
</tr>
</thead>
<tbody><tr id="row9334mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p846716341366"><a name="p846716341366"></a><a name="p846716341366"></a>public static class CameraPosition.Builder</p>
<p id="p9336mcpsimp"><a name="p9336mcpsimp"></a><a name="p9336mcpsimp"></a>是<a href="cameraposition.md">CameraPosition</a>的内部接口，包含了<a href="#section141231075266">build</a>()、<a href="#section676214092616">bearing</a>(float bearing)、<a href="#section1962717532250">target</a>(<a href="latlng.md">LatLng</a> location)、<a href="#section1341654415259">tilt</a>(float tilt)和<a href="#section178881735182515">zoom</a>(float zoom)五个方法，下面对这五个方法分别介绍。</p>
</td>
</tr>
</tbody>
</table>

## Public Constructor Summary<a name="section1399259101117"></a>

<a name="table9340mcpsimp"></a>
<table><thead align="left"><tr id="row9344mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p145mcpsimp"><a name="p145mcpsimp"></a><a name="p145mcpsimp"></a>Constructor Name</p>
</th>
</tr>
</thead>
<tbody><tr id="row9347mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p9349mcpsimp"><a name="p9349mcpsimp"></a><a name="p9349mcpsimp"></a><a href="#section168973357123">CameraPosition.Builder</a>()</p>
<p id="p54251842103414"><a name="p54251842103414"></a><a name="p54251842103414"></a>CameraPosition.Builder的默认构造方法。</p>
</td>
</tr>
<tr id="row9350mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p9352mcpsimp"><a name="p9352mcpsimp"></a><a name="p9352mcpsimp"></a><a href="#section168973357123">CameraPosition.Builder</a>(<a href="cameraposition.md">CameraPosition</a> cameraPosition)</p>
<p id="p73231038712"><a name="p73231038712"></a><a name="p73231038712"></a>根据给定的参数构造一个新的<a href="cameraposition.md">CameraPosition</a>对象。</p>
</td>
</tr>
</tbody>
</table>

## Public Method Summary<a name="section12318155421116"></a>

<a name="table9354mcpsimp"></a>
<table><thead align="left"><tr id="row9359mcpsimp"><th class="cellrowborder" valign="top" width="40%" id="mcps1.1.3.1.1"><p id="p9361mcpsimp"><a name="p9361mcpsimp"></a><a name="p9361mcpsimp"></a>Qualifier and Type</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.1.3.1.2"><p id="p9363mcpsimp"><a name="p9363mcpsimp"></a><a name="p9363mcpsimp"></a>Method Name and Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row9364mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p9366mcpsimp"><a name="p9366mcpsimp"></a><a name="p9366mcpsimp"></a><a href="cameraposition.md">CameraPosition</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p9368mcpsimp"><a name="p9368mcpsimp"></a><a name="p9368mcpsimp"></a><a href="#section141231075266">build</a>()</p>
<p id="p12638133313218"><a name="p12638133313218"></a><a name="p12638133313218"></a>获取一个<a href="cameraposition.md">CameraPosition</a>对象。</p>
</td>
</tr>
<tr id="row9369mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p9371mcpsimp"><a name="p9371mcpsimp"></a><a name="p9371mcpsimp"></a><a href="cameraposition-builder.md">CameraPosition.Builder</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p9373mcpsimp"><a name="p9373mcpsimp"></a><a name="p9373mcpsimp"></a><a href="#section676214092616">bearing</a>(float bearing)</p>
<p id="p15913103473218"><a name="p15913103473218"></a><a name="p15913103473218"></a>设置相机指向的角度，正北方向为0度，顺时针增加。</p>
</td>
</tr>
<tr id="row9374mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p9376mcpsimp"><a name="p9376mcpsimp"></a><a name="p9376mcpsimp"></a><a href="cameraposition-builder.md">CameraPosition.Builder</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p9378mcpsimp"><a name="p9378mcpsimp"></a><a name="p9378mcpsimp"></a><a href="#section1962717532250">target</a>(<a href="latlng.md">LatLng</a> location)</p>
<p id="p68211364329"><a name="p68211364329"></a><a name="p68211364329"></a>给相机设置一个指向的位置，即经纬度。</p>
</td>
</tr>
<tr id="row9379mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p9381mcpsimp"><a name="p9381mcpsimp"></a><a name="p9381mcpsimp"></a><a href="cameraposition-builder.md">CameraPosition.Builder</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p9383mcpsimp"><a name="p9383mcpsimp"></a><a name="p9383mcpsimp"></a><a href="#section1341654415259">tilt</a>(float tilt)</p>
<p id="p184282375322"><a name="p184282375322"></a><a name="p184282375322"></a>设置相机的倾斜角度，即相机角度与垂直于地球表面直线的夹角。</p>
</td>
</tr>
<tr id="row9384mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p14956121761810"><a name="p14956121761810"></a><a name="p14956121761810"></a><a href="cameraposition-builder.md">CameraPosition.Builder</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p9388mcpsimp"><a name="p9388mcpsimp"></a><a name="p9388mcpsimp"></a><a href="#section178881735182515">zoom</a>(float zoom)</p>
<p id="p19399438113219"><a name="p19399438113219"></a><a name="p19399438113219"></a>修改相机的缩放级别。</p>
</td>
</tr>
</tbody>
</table>

## Public Constructors<a name="section186512179184"></a>

## CameraPosition.Builder<a name="section168973357123"></a>

<a name="table227mcpsimp"></a>
<table><thead align="left"><tr id="row231mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p233mcpsimp"><a name="p233mcpsimp"></a><a name="p233mcpsimp"></a>Constructor</p>
</th>
</tr>
</thead>
<tbody><tr id="row235mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p62391843141812"><a name="p62391843141812"></a><a name="p62391843141812"></a>public <a href="#section168973357123">CameraPosition.Builder</a>()</p>
<p id="p7239164381810"><a name="p7239164381810"></a><a name="p7239164381810"></a>默认的构造方法。</p>
</td>
</tr>
<tr id="row18166166189"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p1423904311816"><a name="p1423904311816"></a><a name="p1423904311816"></a>public <a href="#section168973357123">CameraPosition.Builder</a>(<a href="cameraposition.md">CameraPosition</a> cameraPosition)</p>
<p id="p6240124312188"><a name="p6240124312188"></a><a name="p6240124312188"></a>使用<a href="cameraposition.md">CameraPosition</a>创建<a href="cameraposition-builder.md">CameraPosition.Builder</a>对象。</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table243mcpsimp"></a>
<table><thead align="left"><tr id="row248mcpsimp"><th class="cellrowborder" valign="top" width="43%" id="mcps1.1.3.1.1"><p id="p250mcpsimp"><a name="p250mcpsimp"></a><a name="p250mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="56.99999999999999%" id="mcps1.1.3.1.2"><p id="p253mcpsimp"><a name="p253mcpsimp"></a><a name="p253mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row255mcpsimp"><td class="cellrowborder" valign="top" width="43%" headers="mcps1.1.3.1.1 "><p id="p18260165916195"><a name="p18260165916195"></a><a name="p18260165916195"></a>cameraPosition</p>
</td>
<td class="cellrowborder" valign="top" width="56.99999999999999%" headers="mcps1.1.3.1.2 "><p id="p12259205919197"><a name="p12259205919197"></a><a name="p12259205919197"></a><a href="cameraposition.md">CameraPosition</a>实例。</p>
</td>
</tr>
</tbody>
</table>

## Public Methods<a name="section184955312226"></a>

## build<a name="section141231075266"></a>

<a name="table9391mcpsimp"></a>
<table><thead align="left"><tr id="row9395mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p9397mcpsimp"><a name="p9397mcpsimp"></a><a name="p9397mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row9398mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p9400mcpsimp"><a name="p9400mcpsimp"></a><a name="p9400mcpsimp"></a>public <a href="cameraposition.md">CameraPosition</a> build()</p>
<p id="p1545424418290"><a name="p1545424418290"></a><a name="p1545424418290"></a>您调用此API可以获取一个<a href="cameraposition.md">CameraPosition</a>对象。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table9409mcpsimp"></a>
<table><thead align="left"><tr id="row9414mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p9416mcpsimp"><a name="p9416mcpsimp"></a><a name="p9416mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p9418mcpsimp"><a name="p9418mcpsimp"></a><a name="p9418mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row9419mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p9421mcpsimp"><a name="p9421mcpsimp"></a><a name="p9421mcpsimp"></a>CameraPosition</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p9423mcpsimp"><a name="p9423mcpsimp"></a><a name="p9423mcpsimp"></a><a href="cameraposition.md">CameraPosition</a>对象。</p>
</td>
</tr>
</tbody>
</table>

## bearing<a name="section676214092616"></a>

<a name="table9425mcpsimp"></a>
<table><thead align="left"><tr id="row9429mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p9431mcpsimp"><a name="p9431mcpsimp"></a><a name="p9431mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row9432mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p9434mcpsimp"><a name="p9434mcpsimp"></a><a name="p9434mcpsimp"></a>public <a href="cameraposition-builder.md">CameraPosition.Builder</a> bearing(float bearing)</p>
<p id="p19421174133010"><a name="p19421174133010"></a><a name="p19421174133010"></a>设置相机指向的角度，正北方向为0度，顺时针增加。</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table9440mcpsimp"></a>
<table><thead align="left"><tr id="row9445mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p9447mcpsimp"><a name="p9447mcpsimp"></a><a name="p9447mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p9449mcpsimp"><a name="p9449mcpsimp"></a><a name="p9449mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row9450mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p9452mcpsimp"><a name="p9452mcpsimp"></a><a name="p9452mcpsimp"></a>bearing</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p9454mcpsimp"><a name="p9454mcpsimp"></a><a name="p9454mcpsimp"></a>相机指定的角度，取值范围：[0, 360]。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table9457mcpsimp"></a>
<table><thead align="left"><tr id="row9462mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p9464mcpsimp"><a name="p9464mcpsimp"></a><a name="p9464mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p9466mcpsimp"><a name="p9466mcpsimp"></a><a name="p9466mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row9467mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p33501322151911"><a name="p33501322151911"></a><a name="p33501322151911"></a>CameraPosition.Builder</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p9471mcpsimp"><a name="p9471mcpsimp"></a><a name="p9471mcpsimp"></a><a href="cameraposition-builder.md">CameraPosition.Builder</a>对象。</p>
</td>
</tr>
</tbody>
</table>

## target<a name="section1962717532250"></a>

<a name="table9473mcpsimp"></a>
<table><thead align="left"><tr id="row9477mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p9479mcpsimp"><a name="p9479mcpsimp"></a><a name="p9479mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row9480mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p9482mcpsimp"><a name="p9482mcpsimp"></a><a name="p9482mcpsimp"></a>public <a href="cameraposition-builder.md">CameraPosition.Builder</a> target(<a href="latlng.md">LatLng</a> location)</p>
<p id="p1721820145015"><a name="p1721820145015"></a><a name="p1721820145015"></a>您调用此API给相机设置一个指向的位置，即经纬度。</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table9488mcpsimp"></a>
<table><thead align="left"><tr id="row9493mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p9495mcpsimp"><a name="p9495mcpsimp"></a><a name="p9495mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p9497mcpsimp"><a name="p9497mcpsimp"></a><a name="p9497mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row9498mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p9500mcpsimp"><a name="p9500mcpsimp"></a><a name="p9500mcpsimp"></a>location</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p9502mcpsimp"><a name="p9502mcpsimp"></a><a name="p9502mcpsimp"></a>经纬度。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table9505mcpsimp"></a>
<table><thead align="left"><tr id="row9510mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p9512mcpsimp"><a name="p9512mcpsimp"></a><a name="p9512mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p9514mcpsimp"><a name="p9514mcpsimp"></a><a name="p9514mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row9515mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p9517mcpsimp"><a name="p9517mcpsimp"></a><a name="p9517mcpsimp"></a>CameraPosition.Builder</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p9519mcpsimp"><a name="p9519mcpsimp"></a><a name="p9519mcpsimp"></a><a href="cameraposition-builder.md">CameraPosition.Builder</a>对象。</p>
</td>
</tr>
</tbody>
</table>

## tilt<a name="section1341654415259"></a>

<a name="table9521mcpsimp"></a>
<table><thead align="left"><tr id="row9525mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p9527mcpsimp"><a name="p9527mcpsimp"></a><a name="p9527mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row9528mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p9530mcpsimp"><a name="p9530mcpsimp"></a><a name="p9530mcpsimp"></a>public <a href="cameraposition-builder.md">CameraPosition.Builder</a> tilt(float tilt)</p>
<p id="p9533mcpsimp"><a name="p9533mcpsimp"></a><a name="p9533mcpsimp"></a>用于设置相机的倾斜角度，即相机角度与垂直于地球表面直线的夹角。</p>
<p id="p9534mcpsimp"><a name="p9534mcpsimp"></a><a name="p9534mcpsimp"></a>倾斜角度受到缩放系数的限制：</p>
<a name="ul9535mcpsimp"></a><a name="ul9535mcpsimp"></a><ul id="ul9535mcpsimp"><li>缩放系数小于10时，地图不可倾斜。</li><li>缩放系数大于等于10时，地图倾斜范围是[0, 60]。</li></ul>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table9540mcpsimp"></a>
<table><thead align="left"><tr id="row9545mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p9547mcpsimp"><a name="p9547mcpsimp"></a><a name="p9547mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p9549mcpsimp"><a name="p9549mcpsimp"></a><a name="p9549mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row9550mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p9552mcpsimp"><a name="p9552mcpsimp"></a><a name="p9552mcpsimp"></a>tilt</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p9554mcpsimp"><a name="p9554mcpsimp"></a><a name="p9554mcpsimp"></a>倾斜角度，单位：度。取值范围：[0, 90]。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table9557mcpsimp"></a>
<table><thead align="left"><tr id="row9562mcpsimp"><th class="cellrowborder" valign="top" width="47.02%" id="mcps1.1.3.1.1"><p id="p9564mcpsimp"><a name="p9564mcpsimp"></a><a name="p9564mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="52.980000000000004%" id="mcps1.1.3.1.2"><p id="p9566mcpsimp"><a name="p9566mcpsimp"></a><a name="p9566mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row9567mcpsimp"><td class="cellrowborder" valign="top" width="47.02%" headers="mcps1.1.3.1.1 "><p id="p9569mcpsimp"><a name="p9569mcpsimp"></a><a name="p9569mcpsimp"></a>CameraPosition.Builder</p>
</td>
<td class="cellrowborder" valign="top" width="52.980000000000004%" headers="mcps1.1.3.1.2 "><p id="p9571mcpsimp"><a name="p9571mcpsimp"></a><a name="p9571mcpsimp"></a><a href="cameraposition-builder.md">CameraPosition.Builder</a>对象。</p>
</td>
</tr>
</tbody>
</table>

## zoom<a name="section178881735182515"></a>

<a name="table9573mcpsimp"></a>
<table><thead align="left"><tr id="row9577mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p9579mcpsimp"><a name="p9579mcpsimp"></a><a name="p9579mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row9580mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p9582mcpsimp"><a name="p9582mcpsimp"></a><a name="p9582mcpsimp"></a>public <a href="cameraposition-builder.md">CameraPosition.Builder</a> zoom(float zoom)</p>
<p id="p6711125615301"><a name="p6711125615301"></a><a name="p6711125615301"></a>您调用此API可以修改相机的缩放级别。</p>
<p id="p699218520201"><a name="p699218520201"></a><a name="p699218520201"></a>更改地图的相机位置时，相机的缩放级别将根据位置、地图类型和地图大小等各种因素限制在一定范围内。使用<a href="huaweimap.md">HuaweiMap</a>.<a href="huaweimap.md#section15491181135412">getMinZoomLevel</a>()和<a href="huaweimap.md">HuaweiMap</a>. <a href="huaweimap.md#section10176115075312">getMaxZoomLevel</a>()查找限制。请注意，相机缩放级别不是整数类型。</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table9588mcpsimp"></a>
<table><thead align="left"><tr id="row9593mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p9595mcpsimp"><a name="p9595mcpsimp"></a><a name="p9595mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p9597mcpsimp"><a name="p9597mcpsimp"></a><a name="p9597mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row9598mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p9600mcpsimp"><a name="p9600mcpsimp"></a><a name="p9600mcpsimp"></a>zoom</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p9602mcpsimp"><a name="p9602mcpsimp"></a><a name="p9602mcpsimp"></a>缩放级别，取值范围：[3, 20]。</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table9605mcpsimp"></a>
<table><thead align="left"><tr id="row9610mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p9612mcpsimp"><a name="p9612mcpsimp"></a><a name="p9612mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p9614mcpsimp"><a name="p9614mcpsimp"></a><a name="p9614mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row9615mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p9617mcpsimp"><a name="p9617mcpsimp"></a><a name="p9617mcpsimp"></a>CameraPosition.Builder</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p9619mcpsimp"><a name="p9619mcpsimp"></a><a name="p9619mcpsimp"></a><a href="cameraposition-builder.md">CameraPosition.Builder</a>对象。</p>
</td>
</tr>
</tbody>
</table>

