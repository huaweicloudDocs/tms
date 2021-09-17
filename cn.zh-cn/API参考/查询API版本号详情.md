# 查询API版本号详情<a name="zh-cn_topic_0133313257"></a>

## 功能介绍<a name="section112333415306"></a>

查询指定的标签管理服务API版本号详情。

## URI<a name="section9128153473016"></a>

GET /\{api\_version\}

## 请求消息<a name="section32381034103013"></a>

-   要素说明

    **表 1**  请求样例的要素说明

    <a name="table12569102910"></a>
    <table><thead align="left"><tr id="row863915010914"><th class="cellrowborder" valign="top" width="22.97%" id="mcps1.2.5.1.1"><p id="p86399015915"><a name="p86399015915"></a><a name="p86399015915"></a><strong id="b196391601693"><a name="b196391601693"></a><a name="b196391601693"></a>名称</strong></p>
    </th>
    <th class="cellrowborder" valign="top" width="18.15%" id="mcps1.2.5.1.2"><p id="p15639401794"><a name="p15639401794"></a><a name="p15639401794"></a><strong id="b3639100594"><a name="b3639100594"></a><a name="b3639100594"></a>是否必选</strong></p>
    </th>
    <th class="cellrowborder" valign="top" width="25.91%" id="mcps1.2.5.1.3"><p id="p363930296"><a name="p363930296"></a><a name="p363930296"></a><strong id="b206391010910"><a name="b206391010910"></a><a name="b206391010910"></a>参数类型</strong></p>
    </th>
    <th class="cellrowborder" valign="top" width="32.97%" id="mcps1.2.5.1.4"><p id="p2640101992"><a name="p2640101992"></a><a name="p2640101992"></a><strong id="b11640901591"><a name="b11640901591"></a><a name="b11640901591"></a>说明</strong></p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="row1864013012915"><td class="cellrowborder" valign="top" width="22.97%" headers="mcps1.2.5.1.1 "><p id="p1364000890"><a name="p1364000890"></a><a name="p1364000890"></a>api_version</p>
    </td>
    <td class="cellrowborder" valign="top" width="18.15%" headers="mcps1.2.5.1.2 "><p id="p146400018913"><a name="p146400018913"></a><a name="p146400018913"></a>是</p>
    </td>
    <td class="cellrowborder" valign="top" width="25.91%" headers="mcps1.2.5.1.3 "><p id="p9640601896"><a name="p9640601896"></a><a name="p9640601896"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="32.97%" headers="mcps1.2.5.1.4 "><p id="p1464011017920"><a name="p1464011017920"></a><a name="p1464011017920"></a>API版本号。</p>
    </td>
    </tr>
    </tbody>
    </table>

-   请求样例

    ```
    GET https://{TMS的Endpoint}/v1.0
    ```


## 响应消息<a name="section17252434193018"></a>

-   要素说明

    **表 2**  响应样例的要素说明

    <a name="table638373419305"></a>
    <table><thead align="left"><tr id="row163831536143019"><th class="cellrowborder" valign="top" width="24.83%" id="mcps1.2.4.1.1"><p id="p1738363612307"><a name="p1738363612307"></a><a name="p1738363612307"></a><strong id="b10108718203616"><a name="b10108718203616"></a><a name="b10108718203616"></a>名称</strong></p>
    </th>
    <th class="cellrowborder" valign="top" width="29.65%" id="mcps1.2.4.1.2"><p id="p4383136193010"><a name="p4383136193010"></a><a name="p4383136193010"></a><strong id="b7111418153616"><a name="b7111418153616"></a><a name="b7111418153616"></a>参数类型</strong></p>
    </th>
    <th class="cellrowborder" valign="top" width="45.519999999999996%" id="mcps1.2.4.1.3"><p id="p153838362301"><a name="p153838362301"></a><a name="p153838362301"></a><strong id="b1711421823612"><a name="b1711421823612"></a><a name="b1711421823612"></a>说明</strong></p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="row163832366304"><td class="cellrowborder" valign="top" width="24.83%" headers="mcps1.2.4.1.1 "><p id="p3383133610301"><a name="p3383133610301"></a><a name="p3383133610301"></a>version</p>
    </td>
    <td class="cellrowborder" valign="top" width="29.65%" headers="mcps1.2.4.1.2 "><p id="p2383133616305"><a name="p2383133616305"></a><a name="p2383133616305"></a>object</p>
    </td>
    <td class="cellrowborder" valign="top" width="45.519999999999996%" headers="mcps1.2.4.1.3 "><p id="p1238343618301"><a name="p1238343618301"></a><a name="p1238343618301"></a>描述version相关对象。</p>
    <p id="p041917181204"><a name="p041917181204"></a><a name="p041917181204"></a>详细参数请参见<a href="#table7480934143011">表3</a>。</p>
    </td>
    </tr>
    </tbody>
    </table>

-   version字段数据结构说明

    **表 3**  version字段数据结构说明

    <a name="table7480934143011"></a>
    <table><thead align="left"><tr id="row5383153610309"><th class="cellrowborder" valign="top" width="18.688131186881314%" id="mcps1.2.4.1.1"><p id="p2384153663010"><a name="p2384153663010"></a><a name="p2384153663010"></a><strong id="b98711320193612"><a name="b98711320193612"></a><a name="b98711320193612"></a>名称</strong></p>
    </th>
    <th class="cellrowborder" valign="top" width="22.077792220777923%" id="mcps1.2.4.1.2"><p id="p8384203618302"><a name="p8384203618302"></a><a name="p8384203618302"></a><strong id="b1872142043619"><a name="b1872142043619"></a><a name="b1872142043619"></a>参数类型</strong></p>
    </th>
    <th class="cellrowborder" valign="top" width="59.23407659234077%" id="mcps1.2.4.1.3"><p id="p17384123612304"><a name="p17384123612304"></a><a name="p17384123612304"></a><strong id="b12877142019360"><a name="b12877142019360"></a><a name="b12877142019360"></a>说明</strong></p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="row838413616301"><td class="cellrowborder" valign="top" width="18.688131186881314%" headers="mcps1.2.4.1.1 "><p id="p638463613305"><a name="p638463613305"></a><a name="p638463613305"></a>id</p>
    </td>
    <td class="cellrowborder" valign="top" width="22.077792220777923%" headers="mcps1.2.4.1.2 "><p id="p43841036173017"><a name="p43841036173017"></a><a name="p43841036173017"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="59.23407659234077%" headers="mcps1.2.4.1.3 "><p id="p153844368307"><a name="p153844368307"></a><a name="p153844368307"></a>版本ID（版本号），如v1.0。</p>
    </td>
    </tr>
    <tr id="row143841136183018"><td class="cellrowborder" valign="top" width="18.688131186881314%" headers="mcps1.2.4.1.1 "><p id="p2038423643018"><a name="p2038423643018"></a><a name="p2038423643018"></a>links</p>
    </td>
    <td class="cellrowborder" valign="top" width="22.077792220777923%" headers="mcps1.2.4.1.2 "><p id="p2384736163019"><a name="p2384736163019"></a><a name="p2384736163019"></a>List&lt;Link&gt;</p>
    </td>
    <td class="cellrowborder" valign="top" width="59.23407659234077%" headers="mcps1.2.4.1.3 "><p id="p8384123653010"><a name="p8384123653010"></a><a name="p8384123653010"></a>API的URL地址。</p>
    <p id="p149851402025"><a name="p149851402025"></a><a name="p149851402025"></a>详细参数请参见<a href="#table86914347304">表4</a>。</p>
    </td>
    </tr>
    <tr id="row14384173643012"><td class="cellrowborder" valign="top" width="18.688131186881314%" headers="mcps1.2.4.1.1 "><p id="p8384153619301"><a name="p8384153619301"></a><a name="p8384153619301"></a>version</p>
    </td>
    <td class="cellrowborder" valign="top" width="22.077792220777923%" headers="mcps1.2.4.1.2 "><p id="p8384133683015"><a name="p8384133683015"></a><a name="p8384133683015"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="59.23407659234077%" headers="mcps1.2.4.1.3 "><p id="p113841236183014"><a name="p113841236183014"></a><a name="p113841236183014"></a>若该版本API支持微版本，则返回支持的最新微版本号，如果不支持微版本，则返回空。</p>
    </td>
    </tr>
    <tr id="row1138415367307"><td class="cellrowborder" valign="top" width="18.688131186881314%" headers="mcps1.2.4.1.1 "><p id="p20385143614301"><a name="p20385143614301"></a><a name="p20385143614301"></a>status</p>
    </td>
    <td class="cellrowborder" valign="top" width="22.077792220777923%" headers="mcps1.2.4.1.2 "><p id="p123851236133011"><a name="p123851236133011"></a><a name="p123851236133011"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="59.23407659234077%" headers="mcps1.2.4.1.3 "><p id="p113881736183016"><a name="p113881736183016"></a><a name="p113881736183016"></a>版本状态，为如下3种：</p>
    <a name="ul012713412324"></a><a name="ul012713412324"></a><ul id="ul012713412324"><li>CURRENT：表示该版本为主推版本。</li><li>SUPPORTED：表示为老版本，但是现在还继续支持。</li><li>DEPRECATED：表示为废弃版本，存在后续删除的可能。</li></ul>
    </td>
    </tr>
    <tr id="row038814361309"><td class="cellrowborder" valign="top" width="18.688131186881314%" headers="mcps1.2.4.1.1 "><p id="p8388133673018"><a name="p8388133673018"></a><a name="p8388133673018"></a>updated</p>
    </td>
    <td class="cellrowborder" valign="top" width="22.077792220777923%" headers="mcps1.2.4.1.2 "><p id="p123891236183012"><a name="p123891236183012"></a><a name="p123891236183012"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="59.23407659234077%" headers="mcps1.2.4.1.3 "><p id="p1938918364303"><a name="p1938918364303"></a><a name="p1938918364303"></a>版本发布时间，采用UTC时间表示。如v1.0发布的时间2016-12-09T00:00:00Z。</p>
    </td>
    </tr>
    <tr id="row1638943618309"><td class="cellrowborder" valign="top" width="18.688131186881314%" headers="mcps1.2.4.1.1 "><p id="p63894367302"><a name="p63894367302"></a><a name="p63894367302"></a>min_version</p>
    </td>
    <td class="cellrowborder" valign="top" width="22.077792220777923%" headers="mcps1.2.4.1.2 "><p id="p1738912361308"><a name="p1738912361308"></a><a name="p1738912361308"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="59.23407659234077%" headers="mcps1.2.4.1.3 "><p id="p638963653019"><a name="p638963653019"></a><a name="p638963653019"></a>若该版本API支持微版本，则返回支持的最早微版本号，如果不支持微版本，则返回空。</p>
    </td>
    </tr>
    </tbody>
    </table>

-   Links字段数据结构说明

    **表 4**  Links字段数据结构说明

    <a name="table86914347304"></a>
    <table><thead align="left"><tr id="row53898368307"><th class="cellrowborder" valign="top" width="20.79%" id="mcps1.2.4.1.1"><p id="p13895362301"><a name="p13895362301"></a><a name="p13895362301"></a><strong id="b4498724113612"><a name="b4498724113612"></a><a name="b4498724113612"></a>名称</strong></p>
    </th>
    <th class="cellrowborder" valign="top" width="33%" id="mcps1.2.4.1.2"><p id="p438913365302"><a name="p438913365302"></a><a name="p438913365302"></a><strong id="b115011024193617"><a name="b115011024193617"></a><a name="b115011024193617"></a>参数类型</strong></p>
    </th>
    <th class="cellrowborder" valign="top" width="46.21%" id="mcps1.2.4.1.3"><p id="p6389143683018"><a name="p6389143683018"></a><a name="p6389143683018"></a><strong id="b1504224183610"><a name="b1504224183610"></a><a name="b1504224183610"></a>说明</strong></p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="row8389103623010"><td class="cellrowborder" valign="top" width="20.79%" headers="mcps1.2.4.1.1 "><p id="p7389436193014"><a name="p7389436193014"></a><a name="p7389436193014"></a>href</p>
    </td>
    <td class="cellrowborder" valign="top" width="33%" headers="mcps1.2.4.1.2 "><p id="p73891236123010"><a name="p73891236123010"></a><a name="p73891236123010"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="46.21%" headers="mcps1.2.4.1.3 "><p id="p5389536123014"><a name="p5389536123014"></a><a name="p5389536123014"></a>API的URL地址。</p>
    </td>
    </tr>
    <tr id="row6389163653017"><td class="cellrowborder" valign="top" width="20.79%" headers="mcps1.2.4.1.1 "><p id="p63891036163012"><a name="p63891036163012"></a><a name="p63891036163012"></a>rel</p>
    </td>
    <td class="cellrowborder" valign="top" width="33%" headers="mcps1.2.4.1.2 "><p id="p13389133693017"><a name="p13389133693017"></a><a name="p13389133693017"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="46.21%" headers="mcps1.2.4.1.3 "><p id="p03899362303"><a name="p03899362303"></a><a name="p03899362303"></a>self</p>
    </td>
    </tr>
    </tbody>
    </table>

-   响应样例

    ```
    {
        "version": {
            "id": "v1.0",
            "links": [
                {
                    "rel": "self",
                    "href": "https://API的URL地址/v1.0"
                }
            ],
            "version": "",
            "status": "CURRENT",
            "updated": "2016-12-09T00:00:00Z",
            "min_version": ""
        }
    }
    ```


## 状态码<a name="section17789101582315"></a>

请参考[状态码](状态码.md)。

## 错误码<a name="section18604165622519"></a>

请参考[错误码](错误码.md)。

