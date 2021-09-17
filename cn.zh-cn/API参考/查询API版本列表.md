# 查询API版本列表<a name="zh-cn_topic_0133313256"></a>

## 功能介绍<a name="section18687215132319"></a>

查询标签管理服务的API版本列表。

## URI<a name="section6695141502313"></a>

GET /

## 请求消息<a name="section147311515172315"></a>

请求样例

```
GET https://{TMS的Endpoint}/
```

>![](public_sys-resources/icon-note.gif) **说明：** 
>您可以从[地区和终端节点](https://developer.huaweicloud.com/endpoint)中查询TMS服务的终端节点。
>调用TMS服务的API接口都需要调用Domain级Token，详情请参见[获取Domain级Token](获取Domain级Token.md)。

## 响应消息<a name="section11732141562320"></a>

-   要素说明

    **表 1**  响应样例的要素说明

    <a name="table17740171518233"></a>
    <table><thead align="left"><tr id="row8871619238"><th class="cellrowborder" valign="top" width="19.848015198480155%" id="mcps1.2.4.1.1"><p id="p28141692310"><a name="p28141692310"></a><a name="p28141692310"></a><strong id="b4325123993518"><a name="b4325123993518"></a><a name="b4325123993518"></a>名称</strong></p>
    </th>
    <th class="cellrowborder" valign="top" width="23.44765523447655%" id="mcps1.2.4.1.2"><p id="p18416152317"><a name="p18416152317"></a><a name="p18416152317"></a><strong id="b0328239143510"><a name="b0328239143510"></a><a name="b0328239143510"></a>参数类型</strong></p>
    </th>
    <th class="cellrowborder" valign="top" width="56.7043295670433%" id="mcps1.2.4.1.3"><p id="p28171614232"><a name="p28171614232"></a><a name="p28171614232"></a><strong id="b133311339203512"><a name="b133311339203512"></a><a name="b133311339203512"></a>说明</strong></p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="row108191642320"><td class="cellrowborder" valign="top" width="19.848015198480155%" headers="mcps1.2.4.1.1 "><p id="p88111614232"><a name="p88111614232"></a><a name="p88111614232"></a>versions</p>
    </td>
    <td class="cellrowborder" valign="top" width="23.44765523447655%" headers="mcps1.2.4.1.2 "><p id="p28141622314"><a name="p28141622314"></a><a name="p28141622314"></a>Array</p>
    </td>
    <td class="cellrowborder" valign="top" width="56.7043295670433%" headers="mcps1.2.4.1.3 "><p id="p4873152115617"><a name="p4873152115617"></a><a name="p4873152115617"></a>描述version相关对象的列表。</p>
    <p id="p68101682312"><a name="p68101682312"></a><a name="p68101682312"></a>详细参数请参见<a href="#table374991515234">表2</a>。</p>
    </td>
    </tr>
    </tbody>
    </table>

-   versions字段数据结构说明

    **表 2**  versions字段数据结构说明

    <a name="table374991515234"></a>
    <table><thead align="left"><tr id="row68201612320"><th class="cellrowborder" valign="top" width="18.87%" id="mcps1.2.4.1.1"><p id="p281616202313"><a name="p281616202313"></a><a name="p281616202313"></a><strong id="b25031441143516"><a name="b25031441143516"></a><a name="b25031441143516"></a>名称</strong></p>
    </th>
    <th class="cellrowborder" valign="top" width="21.33%" id="mcps1.2.4.1.2"><p id="p15819166237"><a name="p15819166237"></a><a name="p15819166237"></a><strong id="b250664163510"><a name="b250664163510"></a><a name="b250664163510"></a>参数类型</strong></p>
    </th>
    <th class="cellrowborder" valign="top" width="59.8%" id="mcps1.2.4.1.3"><p id="p15861642317"><a name="p15861642317"></a><a name="p15861642317"></a><strong id="b135102412351"><a name="b135102412351"></a><a name="b135102412351"></a>说明</strong></p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="row19861612232"><td class="cellrowborder" valign="top" width="18.87%" headers="mcps1.2.4.1.1 "><p id="p9819160233"><a name="p9819160233"></a><a name="p9819160233"></a>id</p>
    </td>
    <td class="cellrowborder" valign="top" width="21.33%" headers="mcps1.2.4.1.2 "><p id="p38121612234"><a name="p38121612234"></a><a name="p38121612234"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="59.8%" headers="mcps1.2.4.1.3 "><p id="p109181619236"><a name="p109181619236"></a><a name="p109181619236"></a>版本ID（版本号），如v1.0。</p>
    </td>
    </tr>
    <tr id="row1991916122316"><td class="cellrowborder" valign="top" width="18.87%" headers="mcps1.2.4.1.1 "><p id="p790163234"><a name="p790163234"></a><a name="p790163234"></a>links</p>
    </td>
    <td class="cellrowborder" valign="top" width="21.33%" headers="mcps1.2.4.1.2 "><p id="p6991642317"><a name="p6991642317"></a><a name="p6991642317"></a>List&lt;Link&gt;</p>
    </td>
    <td class="cellrowborder" valign="top" width="59.8%" headers="mcps1.2.4.1.3 "><p id="p15951611231"><a name="p15951611231"></a><a name="p15951611231"></a>API的URL地址。</p>
    <p id="p64911367576"><a name="p64911367576"></a><a name="p64911367576"></a>详细参数请参见<a href="#table87796151239">表3</a>。</p>
    </td>
    </tr>
    <tr id="row16911161237"><td class="cellrowborder" valign="top" width="18.87%" headers="mcps1.2.4.1.1 "><p id="p209216142319"><a name="p209216142319"></a><a name="p209216142319"></a>version</p>
    </td>
    <td class="cellrowborder" valign="top" width="21.33%" headers="mcps1.2.4.1.2 "><p id="p4931615232"><a name="p4931615232"></a><a name="p4931615232"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="59.8%" headers="mcps1.2.4.1.3 "><p id="p59616142317"><a name="p59616142317"></a><a name="p59616142317"></a>若该版本API支持微版本，则返回支持的最新微版本号，如果不支持微版本，则返回空。</p>
    </td>
    </tr>
    <tr id="row179131652313"><td class="cellrowborder" valign="top" width="18.87%" headers="mcps1.2.4.1.1 "><p id="p5981613232"><a name="p5981613232"></a><a name="p5981613232"></a>status</p>
    </td>
    <td class="cellrowborder" valign="top" width="21.33%" headers="mcps1.2.4.1.2 "><p id="p1195169236"><a name="p1195169236"></a><a name="p1195169236"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="59.8%" headers="mcps1.2.4.1.3 "><p id="p4971617239"><a name="p4971617239"></a><a name="p4971617239"></a>版本状态，包含以下3种：</p>
    <a name="ul101632012202419"></a><a name="ul101632012202419"></a><ul id="ul101632012202419"><li>CURRENT：表示该版本为主推版本。</li><li>SUPPORTED：表示为老版本，但是现在还继续支持。</li><li>DEPRECATED：表示为废弃版本，存在后续删除的可能。</li></ul>
    </td>
    </tr>
    <tr id="row2931611231"><td class="cellrowborder" valign="top" width="18.87%" headers="mcps1.2.4.1.1 "><p id="p129101614238"><a name="p129101614238"></a><a name="p129101614238"></a>updated</p>
    </td>
    <td class="cellrowborder" valign="top" width="21.33%" headers="mcps1.2.4.1.2 "><p id="p1391016142310"><a name="p1391016142310"></a><a name="p1391016142310"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="59.8%" headers="mcps1.2.4.1.3 "><p id="p174961138125815"><a name="p174961138125815"></a><a name="p174961138125815"></a>版本发布时间，采用UTC时间表示。如v1.0发布的时间2016-12-09T00:00:00Z。</p>
    </td>
    </tr>
    <tr id="row12971617238"><td class="cellrowborder" valign="top" width="18.87%" headers="mcps1.2.4.1.1 "><p id="p29121692313"><a name="p29121692313"></a><a name="p29121692313"></a>min_version</p>
    </td>
    <td class="cellrowborder" valign="top" width="21.33%" headers="mcps1.2.4.1.2 "><p id="p189111692310"><a name="p189111692310"></a><a name="p189111692310"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="59.8%" headers="mcps1.2.4.1.3 "><p id="p1595167238"><a name="p1595167238"></a><a name="p1595167238"></a>若该版本API支持微版本，则返回支持的最早微版本号，如果不支持微版本，则返回空。</p>
    </td>
    </tr>
    </tbody>
    </table>

-   Links字段数据结构说明

    **表 3**  Links字段数据结构说明

    <a name="table87796151239"></a>
    <table><thead align="left"><tr id="row10941619231"><th class="cellrowborder" valign="top" width="21.11%" id="mcps1.2.4.1.1"><p id="p591816112316"><a name="p591816112316"></a><a name="p591816112316"></a><strong id="b5605144533511"><a name="b5605144533511"></a><a name="b5605144533511"></a>名称</strong></p>
    </th>
    <th class="cellrowborder" valign="top" width="32.87%" id="mcps1.2.4.1.2"><p id="p7915161233"><a name="p7915161233"></a><a name="p7915161233"></a><strong id="b1609154543515"><a name="b1609154543515"></a><a name="b1609154543515"></a>参数类型</strong></p>
    </th>
    <th class="cellrowborder" valign="top" width="46.02%" id="mcps1.2.4.1.3"><p id="p8911652317"><a name="p8911652317"></a><a name="p8911652317"></a><strong id="b176131045143511"><a name="b176131045143511"></a><a name="b176131045143511"></a>说明</strong></p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="row1591116192310"><td class="cellrowborder" valign="top" width="21.11%" headers="mcps1.2.4.1.1 "><p id="p14101016192311"><a name="p14101016192311"></a><a name="p14101016192311"></a>href</p>
    </td>
    <td class="cellrowborder" valign="top" width="32.87%" headers="mcps1.2.4.1.2 "><p id="p1710116192319"><a name="p1710116192319"></a><a name="p1710116192319"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="46.02%" headers="mcps1.2.4.1.3 "><p id="p01031642310"><a name="p01031642310"></a><a name="p01031642310"></a>API的URL地址。</p>
    </td>
    </tr>
    <tr id="row7101161237"><td class="cellrowborder" valign="top" width="21.11%" headers="mcps1.2.4.1.1 "><p id="p19101216112319"><a name="p19101216112319"></a><a name="p19101216112319"></a>rel</p>
    </td>
    <td class="cellrowborder" valign="top" width="32.87%" headers="mcps1.2.4.1.2 "><p id="p1710121612238"><a name="p1710121612238"></a><a name="p1710121612238"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="46.02%" headers="mcps1.2.4.1.3 "><p id="p151061632310"><a name="p151061632310"></a><a name="p151061632310"></a>self</p>
    </td>
    </tr>
    </tbody>
    </table>


-   响应样例

    ```
    {
        "versions": [
            {
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
        ]
    }
    ```


## 状态码<a name="section17789101582315"></a>

请参考[状态码](状态码.md)。

## 错误码<a name="section9414853182510"></a>

请参考[错误码](错误码.md)。

