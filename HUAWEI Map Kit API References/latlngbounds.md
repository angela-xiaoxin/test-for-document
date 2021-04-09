# LatLngBounds<a name="EN-US_TOPIC_0000001145941079"></a>

-   [Nested Class Summary](#section13451115715114)
-   [Public Field Summary](#section8372124205120)
-   [Public Constructor Summary](#section693314525100)
-   [Public Method Summary](#section109381127121110)
-   [Public Constructors](#section042681119126)
-   [LatLngBounds](#section168973357123)
-   [Public Methods](#section978616471695)
-   [builder](#section1854132519124)
-   [contains](#section374220141215)
-   [createFromAttributes](#section17200912111215)
-   [getCenter](#section0135184111219)
-   [including](#section693552011189)


<a name="table13974mcpsimp"></a>
<table><thead align="left"><tr id="row13978mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p13980mcpsimp"><a name="p13980mcpsimp"></a><a name="p13980mcpsimp"></a>Class Info</p>
</th>
</tr>
</thead>
<tbody><tr id="row13981mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p19550134514402"><a name="p19550134514402"></a><a name="p19550134514402"></a>public class LatLngBounds</p>
<p id="p13983mcpsimp"><a name="p13983mcpsimp"></a><a name="p13983mcpsimp"></a>Defines a rectangular area using a pair of longitude and latitude.</p>
</td>
</tr>
</tbody>
</table>

## Nested Class Summary<a name="section13451115715114"></a>

<a name="table14091mcpsimp"></a>
<table><thead align="left"><tr id="row14096mcpsimp"><th class="cellrowborder" valign="top" width="56.99999999999999%" id="mcps1.1.3.1.1"><p id="p7543132495318"><a name="p7543132495318"></a><a name="p7543132495318"></a>Qualifier and Type</p>
</th>
<th class="cellrowborder" valign="top" width="43%" id="mcps1.1.3.1.2"><p id="p1554319242536"><a name="p1554319242536"></a><a name="p1554319242536"></a>Class Name and Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row14101mcpsimp"><td class="cellrowborder" valign="top" width="56.99999999999999%" headers="mcps1.1.3.1.1 "><p id="p14103mcpsimp"><a name="p14103mcpsimp"></a><a name="p14103mcpsimp"></a>public interface</p>
</td>
<td class="cellrowborder" valign="top" width="43%" headers="mcps1.1.3.1.2 "><p id="p19225163512365"><a name="p19225163512365"></a><a name="p19225163512365"></a><a href="latlngbounds-builder.md">LatLngBounds.Builder</a></p>
<p id="p14105mcpsimp"><a name="p14105mcpsimp"></a><a name="p14105mcpsimp"></a>Creates a <a href="latlngbounds.md">LatLngBounds</a> object.</p>
</td>
</tr>
</tbody>
</table>

## Public Field Summary<a name="section8372124205120"></a>

<a name="table51207528357"></a>
<table><thead align="left"><tr id="row6121185283516"><th class="cellrowborder" valign="top" width="32.21%" id="mcps1.1.3.1.1"><p id="p1528164471414"><a name="p1528164471414"></a><a name="p1528164471414"></a>Qualifier and Type</p>
</th>
<th class="cellrowborder" valign="top" width="67.78999999999999%" id="mcps1.1.3.1.2"><p id="p1554614158108"><a name="p1554614158108"></a><a name="p1554614158108"></a>Field and Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row1632818461140"><td class="cellrowborder" valign="top" width="32.21%" headers="mcps1.1.3.1.1 "><p id="p19321251454"><a name="p19321251454"></a><a name="p19321251454"></a><a href="latlng.md">LatLng</a></p>
</td>
<td class="cellrowborder" valign="top" width="67.78999999999999%" headers="mcps1.1.3.1.2 "><p id="p1274655217515"><a name="p1274655217515"></a><a name="p1274655217515"></a>northeast</p>
<p id="p897804213519"><a name="p897804213519"></a><a name="p897804213519"></a>Northeast corner of the bound.</p>
</td>
</tr>
<tr id="row2012119527357"><td class="cellrowborder" valign="top" width="32.21%" headers="mcps1.1.3.1.1 "><p id="p232118512510"><a name="p232118512510"></a><a name="p232118512510"></a><a href="latlng.md">LatLng</a></p>
</td>
<td class="cellrowborder" valign="top" width="67.78999999999999%" headers="mcps1.1.3.1.2 "><p id="p1391111481855"><a name="p1391111481855"></a><a name="p1391111481855"></a>southwest</p>
<p id="p897810421859"><a name="p897810421859"></a><a name="p897810421859"></a>Southwest corner of the bound.</p>
</td>
</tr>
</tbody>
</table>

## Public Constructor Summary<a name="section693314525100"></a>

<a name="table14013mcpsimp"></a>
<table><thead align="left"><tr id="row14017mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p145mcpsimp"><a name="p145mcpsimp"></a><a name="p145mcpsimp"></a>Constructor Name</p>
</th>
</tr>
</thead>
<tbody><tr id="row14020mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p14022mcpsimp"><a name="p14022mcpsimp"></a><a name="p14022mcpsimp"></a><a href="#section168973357123">LatLngBounds</a>(<a href="latlng.md">LatLng</a> southwest, <a href="latlng.md">LatLng</a> northeast)</p>
<p id="p17203160102"><a name="p17203160102"></a><a name="p17203160102"></a>Creates a <a href="latlngbounds.md">LatLngBounds</a> object based on the coordinates of the southwest and northeast corners.</p>
</td>
</tr>
</tbody>
</table>

## Public Method Summary<a name="section109381127121110"></a>

<a name="table14024mcpsimp"></a>
<table><thead align="left"><tr id="row14029mcpsimp"><th class="cellrowborder" valign="top" width="40%" id="mcps1.1.3.1.1"><p id="p081120285386"><a name="p081120285386"></a><a name="p081120285386"></a>Qualifier and Type</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.1.3.1.2"><p id="p681112883813"><a name="p681112883813"></a><a name="p681112883813"></a>Method Name and Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row14049mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p14051mcpsimp"><a name="p14051mcpsimp"></a><a name="p14051mcpsimp"></a>static <a href="latlngbounds-builder.md">LatLngBounds.Builder</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p14053mcpsimp"><a name="p14053mcpsimp"></a><a name="p14053mcpsimp"></a><a href="#section1854132519124">builder</a>()</p>
<p id="p2029464512411"><a name="p2029464512411"></a><a name="p2029464512411"></a>Creates a <a href="latlngbounds-builder.md">LatLngBounds.Builder</a> object, which can then be used to create a <a href="latlngbounds.md">LatLngBounds</a> object.</p>
</td>
</tr>
<tr id="row14054mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p14056mcpsimp"><a name="p14056mcpsimp"></a><a name="p14056mcpsimp"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p14058mcpsimp"><a name="p14058mcpsimp"></a><a name="p14058mcpsimp"></a><a href="#section374220141215">contains</a>(<a href="latlng.md">LatLng</a> point)</p>
<p id="p12391194662414"><a name="p12391194662414"></a><a name="p12391194662414"></a>Checks whether a <a href="latlngbounds.md">LatLngBounds</a> object contains a specified location.</p>
</td>
</tr>
<tr id="row14059mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p14061mcpsimp"><a name="p14061mcpsimp"></a><a name="p14061mcpsimp"></a>static <a href="latlngbounds.md">LatLngBounds</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p14063mcpsimp"><a name="p14063mcpsimp"></a><a name="p14063mcpsimp"></a><a href="#section17200912111215">createFromAttributes</a>(Context context, AttributeSet attrs)</p>
<p id="p14444124772415"><a name="p14444124772415"></a><a name="p14444124772415"></a>Creates a <a href="latlngbounds.md">LatLngBounds</a> object using specified attributes.</p>
</td>
</tr>
<tr id="row41111348151214"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p14036mcpsimp"><a name="p14036mcpsimp"></a><a name="p14036mcpsimp"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p14038mcpsimp"><a name="p14038mcpsimp"></a><a name="p14038mcpsimp"></a>equals(Object other)</p>
<p id="p0395415155810"><a name="p0395415155810"></a><a name="p0395415155810"></a>Checks whether a <a href="latlngbounds.md">LatLngBounds</a> object equals another.</p>
</td>
</tr>
<tr id="row14064mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p14066mcpsimp"><a name="p14066mcpsimp"></a><a name="p14066mcpsimp"></a><a href="latlng.md">LatLng</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p14068mcpsimp"><a name="p14068mcpsimp"></a><a name="p14068mcpsimp"></a><a href="#section0135184111219">getCenter</a>()</p>
<p id="p1532734920244"><a name="p1532734920244"></a><a name="p1532734920244"></a>Obtains the longitude and latitude of the center of a <a href="latlngbounds.md">LatLngBounds</a> object.</p>
</td>
</tr>
<tr id="row15558671136"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p14041mcpsimp"><a name="p14041mcpsimp"></a><a name="p14041mcpsimp"></a>int</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p14043mcpsimp"><a name="p14043mcpsimp"></a><a name="p14043mcpsimp"></a>hashCode()</p>
<p id="p198781251165811"><a name="p198781251165811"></a><a name="p198781251165811"></a>Returns the hash code of an object.</p>
</td>
</tr>
<tr id="row14069mcpsimp"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p14071mcpsimp"><a name="p14071mcpsimp"></a><a name="p14071mcpsimp"></a><a href="latlngbounds.md">LatLngBounds</a></p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p14073mcpsimp"><a name="p14073mcpsimp"></a><a name="p14073mcpsimp"></a><a href="#section693552011189">including</a>(<a href="latlng.md">LatLng</a> point)</p>
<p id="p1558995022419"><a name="p1558995022419"></a><a name="p1558995022419"></a>Obtains a <a href="latlngbounds.md">LatLngBounds</a> object that contains a specified location.</p>
</td>
</tr>
<tr id="row349482371317"><td class="cellrowborder" valign="top" width="40%" headers="mcps1.1.3.1.1 "><p id="p14046mcpsimp"><a name="p14046mcpsimp"></a><a name="p14046mcpsimp"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.1.3.1.2 "><p id="p14048mcpsimp"><a name="p14048mcpsimp"></a><a name="p14048mcpsimp"></a>toString()</p>
<p id="p8660175110575"><a name="p8660175110575"></a><a name="p8660175110575"></a>Returns the object as a string.</p>
</td>
</tr>
</tbody>
</table>

## Public Constructors<a name="section042681119126"></a>

## LatLngBounds<a name="section168973357123"></a>

<a name="table227mcpsimp"></a>
<table><thead align="left"><tr id="row231mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p233mcpsimp"><a name="p233mcpsimp"></a><a name="p233mcpsimp"></a>Constructor</p>
</th>
</tr>
</thead>
<tbody><tr id="row235mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p1884817142017"><a name="p1884817142017"></a><a name="p1884817142017"></a>public <a href="latlngbounds.md">LatLngBounds</a>(<a href="latlng.md">LatLng</a> southwest, <a href="latlng.md">LatLng</a> northeast)</p>
<p id="p1573217396116"><a name="p1573217396116"></a><a name="p1573217396116"></a>Creates a <a href="latlngbounds.md">LatLngBounds</a> object based on specified parameters.</p>
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
<tbody><tr id="row255mcpsimp"><td class="cellrowborder" valign="top" width="43%" headers="mcps1.1.3.1.1 "><p id="p2404192013619"><a name="p2404192013619"></a><a name="p2404192013619"></a>southwest</p>
</td>
<td class="cellrowborder" valign="top" width="56.99999999999999%" headers="mcps1.1.3.1.2 "><p id="p16403192012362"><a name="p16403192012362"></a><a name="p16403192012362"></a>Southwest corner of the bound.</p>
</td>
</tr>
<tr id="row05001713362"><td class="cellrowborder" valign="top" width="43%" headers="mcps1.1.3.1.1 "><p id="p451517103611"><a name="p451517103611"></a><a name="p451517103611"></a>northeast</p>
</td>
<td class="cellrowborder" valign="top" width="56.99999999999999%" headers="mcps1.1.3.1.2 "><p id="p351171743616"><a name="p351171743616"></a><a name="p351171743616"></a>Northeast corner of the bound.</p>
</td>
</tr>
</tbody>
</table>

**Throws**

<a name="table14075mcpsimp"></a>
<table><thead align="left"><tr id="row14080mcpsimp"><th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.1"><p id="p1240643813161"><a name="p1240643813161"></a><a name="p1240643813161"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.2"><p id="p14084mcpsimp"><a name="p14084mcpsimp"></a><a name="p14084mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row14085mcpsimp"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p14087mcpsimp"><a name="p14087mcpsimp"></a><a name="p14087mcpsimp"></a>IllegalArgumentException</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p14089mcpsimp"><a name="p14089mcpsimp"></a><a name="p14089mcpsimp"></a>If the latitude of the northeast corner is lower than that of the southwest corner.</p>
</td>
</tr>
</tbody>
</table>

## Public Methods<a name="section978616471695"></a>

## builder<a name="section1854132519124"></a>

<a name="table14108mcpsimp"></a>
<table><thead align="left"><tr id="row14112mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p14114mcpsimp"><a name="p14114mcpsimp"></a><a name="p14114mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row14115mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p14117mcpsimp"><a name="p14117mcpsimp"></a><a name="p14117mcpsimp"></a>public static <a href="latlngbounds-builder.md">LatLngBounds.Builder</a> builder()</p>
<p id="p197511623191111"><a name="p197511623191111"></a><a name="p197511623191111"></a>Creates a <a href="latlngbounds-builder.md">LatLngBounds.Builder</a> object, which can then be used to create a <a href="latlngbounds.md">LatLngBounds</a> object.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table14126mcpsimp"></a>
<table><thead align="left"><tr id="row14131mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p14133mcpsimp"><a name="p14133mcpsimp"></a><a name="p14133mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p14135mcpsimp"><a name="p14135mcpsimp"></a><a name="p14135mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row14136mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p193838422373"><a name="p193838422373"></a><a name="p193838422373"></a>LatLngBounds.Builder</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p14140mcpsimp"><a name="p14140mcpsimp"></a><a name="p14140mcpsimp"></a><a href="latlngbounds-builder.md">LatLngBounds.Builder</a> object.</p>
</td>
</tr>
</tbody>
</table>

## contains<a name="section374220141215"></a>

<a name="table14142mcpsimp"></a>
<table><thead align="left"><tr id="row14146mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p14148mcpsimp"><a name="p14148mcpsimp"></a><a name="p14148mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row14149mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p14151mcpsimp"><a name="p14151mcpsimp"></a><a name="p14151mcpsimp"></a>public boolean contains(<a href="latlng.md">LatLng</a> point)</p>
<p id="p1918243218112"><a name="p1918243218112"></a><a name="p1918243218112"></a>Checks whether a <a href="latlngbounds.md">LatLngBounds</a> object contains a specified location.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table14157mcpsimp"></a>
<table><thead align="left"><tr id="row14162mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p14164mcpsimp"><a name="p14164mcpsimp"></a><a name="p14164mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p14166mcpsimp"><a name="p14166mcpsimp"></a><a name="p14166mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row14167mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p14169mcpsimp"><a name="p14169mcpsimp"></a><a name="p14169mcpsimp"></a>point</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p14171mcpsimp"><a name="p14171mcpsimp"></a><a name="p14171mcpsimp"></a>Specified location.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table14174mcpsimp"></a>
<table><thead align="left"><tr id="row14179mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p14181mcpsimp"><a name="p14181mcpsimp"></a><a name="p14181mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p14183mcpsimp"><a name="p14183mcpsimp"></a><a name="p14183mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row14184mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p14186mcpsimp"><a name="p14186mcpsimp"></a><a name="p14186mcpsimp"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p14188mcpsimp"><a name="p14188mcpsimp"></a><a name="p14188mcpsimp"></a><strong id="b11722638145018"><a name="b11722638145018"></a><a name="b11722638145018"></a>true</strong> if the specified location is contained; <strong id="b869191195010"><a name="b869191195010"></a><a name="b869191195010"></a>false</strong> otherwise.</p>
</td>
</tr>
</tbody>
</table>

## createFromAttributes<a name="section17200912111215"></a>

<a name="table14190mcpsimp"></a>
<table><thead align="left"><tr id="row14194mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p14196mcpsimp"><a name="p14196mcpsimp"></a><a name="p14196mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row14197mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p14199mcpsimp"><a name="p14199mcpsimp"></a><a name="p14199mcpsimp"></a>public static <a href="latlngbounds.md">LatLngBounds</a> createFromAttributes(Context context, AttributeSet attrs)</p>
<p id="p16499104313115"><a name="p16499104313115"></a><a name="p16499104313115"></a>Creates a <a href="latlngbounds.md">LatLngBounds</a> object using specified attributes.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table14205mcpsimp"></a>
<table><thead align="left"><tr id="row14210mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p14212mcpsimp"><a name="p14212mcpsimp"></a><a name="p14212mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p14214mcpsimp"><a name="p14214mcpsimp"></a><a name="p14214mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row14215mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p14217mcpsimp"><a name="p14217mcpsimp"></a><a name="p14217mcpsimp"></a>context</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p14219mcpsimp"><a name="p14219mcpsimp"></a><a name="p14219mcpsimp"></a>Context.</p>
</td>
</tr>
<tr id="row14220mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p14222mcpsimp"><a name="p14222mcpsimp"></a><a name="p14222mcpsimp"></a>attrs</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p14224mcpsimp"><a name="p14224mcpsimp"></a><a name="p14224mcpsimp"></a>Specified attributes.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table14227mcpsimp"></a>
<table><thead align="left"><tr id="row14232mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p14234mcpsimp"><a name="p14234mcpsimp"></a><a name="p14234mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p14236mcpsimp"><a name="p14236mcpsimp"></a><a name="p14236mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row14237mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p14239mcpsimp"><a name="p14239mcpsimp"></a><a name="p14239mcpsimp"></a>LatLngBounds</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p14241mcpsimp"><a name="p14241mcpsimp"></a><a name="p14241mcpsimp"></a><a href="latlngbounds.md">LatLngBounds</a> object.</p>
</td>
</tr>
</tbody>
</table>

## getCenter<a name="section0135184111219"></a>

<a name="table14243mcpsimp"></a>
<table><thead align="left"><tr id="row14247mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p14249mcpsimp"><a name="p14249mcpsimp"></a><a name="p14249mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row14250mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p14252mcpsimp"><a name="p14252mcpsimp"></a><a name="p14252mcpsimp"></a>public <a href="latlng.md">LatLng</a> getCenter()</p>
<p id="p221212532112"><a name="p221212532112"></a><a name="p221212532112"></a>Obtains the longitude and latitude of the center of a <a href="latlngbounds.md">LatLngBounds</a> object.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table14261mcpsimp"></a>
<table><thead align="left"><tr id="row14266mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p14268mcpsimp"><a name="p14268mcpsimp"></a><a name="p14268mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p14270mcpsimp"><a name="p14270mcpsimp"></a><a name="p14270mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row14271mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p14273mcpsimp"><a name="p14273mcpsimp"></a><a name="p14273mcpsimp"></a>LatLng</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p14275mcpsimp"><a name="p14275mcpsimp"></a><a name="p14275mcpsimp"></a>Longitude and latitude of the center of a <a href="latlng.md">LatLng</a> or <a href="latlngbounds.md">LatLngBounds</a> object.</p>
</td>
</tr>
</tbody>
</table>

## including<a name="section693552011189"></a>

<a name="table14277mcpsimp"></a>
<table><thead align="left"><tr id="row14281mcpsimp"><th class="cellrowborder" valign="top" width="100%" id="mcps1.1.2.1.1"><p id="p14283mcpsimp"><a name="p14283mcpsimp"></a><a name="p14283mcpsimp"></a>Method</p>
</th>
</tr>
</thead>
<tbody><tr id="row14284mcpsimp"><td class="cellrowborder" valign="top" width="100%" headers="mcps1.1.2.1.1 "><p id="p14286mcpsimp"><a name="p14286mcpsimp"></a><a name="p14286mcpsimp"></a>public <a href="latlngbounds.md">LatLngBounds</a> including(<a href="latlng.md">LatLng</a> point)</p>
<p id="p1596418271211"><a name="p1596418271211"></a><a name="p1596418271211"></a>Obtains a <a href="latlngbounds.md">LatLngBounds</a> object that contains a specified location.</p>
</td>
</tr>
</tbody>
</table>

**Parameters**

<a name="table14292mcpsimp"></a>
<table><thead align="left"><tr id="row14297mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p14299mcpsimp"><a name="p14299mcpsimp"></a><a name="p14299mcpsimp"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p14301mcpsimp"><a name="p14301mcpsimp"></a><a name="p14301mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row14302mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p14304mcpsimp"><a name="p14304mcpsimp"></a><a name="p14304mcpsimp"></a>point</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p14306mcpsimp"><a name="p14306mcpsimp"></a><a name="p14306mcpsimp"></a>Location to be contained.</p>
</td>
</tr>
</tbody>
</table>

**Returns**

<a name="table14309mcpsimp"></a>
<table><thead align="left"><tr id="row14314mcpsimp"><th class="cellrowborder" valign="top" width="47%" id="mcps1.1.3.1.1"><p id="p14316mcpsimp"><a name="p14316mcpsimp"></a><a name="p14316mcpsimp"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.1.3.1.2"><p id="p14318mcpsimp"><a name="p14318mcpsimp"></a><a name="p14318mcpsimp"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row14319mcpsimp"><td class="cellrowborder" valign="top" width="47%" headers="mcps1.1.3.1.1 "><p id="p14321mcpsimp"><a name="p14321mcpsimp"></a><a name="p14321mcpsimp"></a>LatLngBounds</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.1.3.1.2 "><p id="p14323mcpsimp"><a name="p14323mcpsimp"></a><a name="p14323mcpsimp"></a><a href="latlngbounds.md">LatLngBounds</a> object that contains the specified location.</p>
</td>
</tr>
</tbody>
</table>

