# 标签管理服务API授权列表项<a name="ZH-CN_TOPIC_0180205869"></a>

**表 1**  API授权项列表

<a name="table041693194917"></a>
<table><thead align="left"><tr id="row1641683154919"><th class="cellrowborder" valign="top" width="16.18%" id="mcps1.2.4.1.1"><p id="p10416163114917"><a name="p10416163114917"></a><a name="p10416163114917"></a>权限</p>
</th>
<th class="cellrowborder" valign="top" width="30.240000000000002%" id="mcps1.2.4.1.2"><p id="p1141613316495"><a name="p1141613316495"></a><a name="p1141613316495"></a>授权项</p>
</th>
<th class="cellrowborder" valign="top" width="53.580000000000005%" id="mcps1.2.4.1.3"><p id="p1859552116271"><a name="p1859552116271"></a><a name="p1859552116271"></a>对应API接口</p>
</th>
</tr>
</thead>
<tbody><tr id="row141673174914"><td class="cellrowborder" valign="top" width="16.18%" headers="mcps1.2.4.1.1 "><p id="p142531438101613"><a name="p142531438101613"></a><a name="p142531438101613"></a>查询预定义标签</p>
</td>
<td class="cellrowborder" valign="top" width="30.240000000000002%" headers="mcps1.2.4.1.2 "><p id="p192541738151610"><a name="p192541738151610"></a><a name="p192541738151610"></a>tms:predefineTags:list</p>
</td>
<td class="cellrowborder" valign="top" width="53.580000000000005%" headers="mcps1.2.4.1.3 "><p id="p1825412384165"><a name="p1825412384165"></a><a name="p1825412384165"></a>GET /v1.0/predefine_tags</p>
</td>
</tr>
<tr id="row34161433499"><td class="cellrowborder" valign="top" width="16.18%" headers="mcps1.2.4.1.1 "><p id="p52541338161612"><a name="p52541338161612"></a><a name="p52541338161612"></a>创建预定义标签</p>
</td>
<td class="cellrowborder" valign="top" width="30.240000000000002%" headers="mcps1.2.4.1.2 "><p id="p5254103811164"><a name="p5254103811164"></a><a name="p5254103811164"></a>tms:predefineTags:create</p>
</td>
<td class="cellrowborder" valign="top" width="53.580000000000005%" headers="mcps1.2.4.1.3 "><p id="p1825412382169"><a name="p1825412382169"></a><a name="p1825412382169"></a>POST /v1.0/predefine_tags/action</p>
</td>
</tr>
<tr id="row6416163114920"><td class="cellrowborder" valign="top" width="16.18%" headers="mcps1.2.4.1.1 "><p id="p19254153819162"><a name="p19254153819162"></a><a name="p19254153819162"></a>删除预定义标签</p>
</td>
<td class="cellrowborder" valign="top" width="30.240000000000002%" headers="mcps1.2.4.1.2 "><p id="p12254133821617"><a name="p12254133821617"></a><a name="p12254133821617"></a>tms:predefineTags:delete</p>
</td>
<td class="cellrowborder" valign="top" width="53.580000000000005%" headers="mcps1.2.4.1.3 "><p id="p1025413816169"><a name="p1025413816169"></a><a name="p1025413816169"></a>POST /v1.0/predefine_tags/action</p>
</td>
</tr>
<tr id="row11717183041418"><td class="cellrowborder" valign="top" width="16.18%" headers="mcps1.2.4.1.1 "><p id="p1525473841610"><a name="p1525473841610"></a><a name="p1525473841610"></a>修改预定义标签</p>
</td>
<td class="cellrowborder" valign="top" width="30.240000000000002%" headers="mcps1.2.4.1.2 "><p id="p2254173821613"><a name="p2254173821613"></a><a name="p2254173821613"></a>tms:predefineTags:update</p>
</td>
<td class="cellrowborder" valign="top" width="53.580000000000005%" headers="mcps1.2.4.1.3 "><p id="p125413881617"><a name="p125413881617"></a><a name="p125413881617"></a>PUT /v1.0/predefine_tags/action</p>
</td>
</tr>
<tr id="row96357374141"><td class="cellrowborder" valign="top" width="16.18%" headers="mcps1.2.4.1.1 "><p id="p18254153871615"><a name="p18254153871615"></a><a name="p18254153871615"></a>查询资源标签</p>
</td>
<td class="cellrowborder" valign="top" width="30.240000000000002%" headers="mcps1.2.4.1.2 "><p id="p52541838201611"><a name="p52541838201611"></a><a name="p52541838201611"></a>tms:resourceTags:list</p>
</td>
<td class="cellrowborder" valign="top" width="53.580000000000005%" headers="mcps1.2.4.1.3 "><p id="p2025463871620"><a name="p2025463871620"></a><a name="p2025463871620"></a>GET /v1.0/tags</p>
</td>
</tr>
<tr id="row1581132920169"><td class="cellrowborder" valign="top" width="16.18%" headers="mcps1.2.4.1.1 "><p id="p525413851613"><a name="p525413851613"></a><a name="p525413851613"></a>创建资源标签</p>
</td>
<td class="cellrowborder" valign="top" width="30.240000000000002%" headers="mcps1.2.4.1.2 "><p id="p14254438131614"><a name="p14254438131614"></a><a name="p14254438131614"></a>tms:resourceTags:create</p>
</td>
<td class="cellrowborder" valign="top" width="53.580000000000005%" headers="mcps1.2.4.1.3 "><p id="p925413871610"><a name="p925413871610"></a><a name="p925413871610"></a>POST /v1.0/{resource_type}/{resource_id}/tags/action</p>
</td>
</tr>
<tr id="row198313291161"><td class="cellrowborder" valign="top" width="16.18%" headers="mcps1.2.4.1.1 "><p id="p15254173819161"><a name="p15254173819161"></a><a name="p15254173819161"></a>删除资源标签</p>
</td>
<td class="cellrowborder" valign="top" width="30.240000000000002%" headers="mcps1.2.4.1.2 "><p id="p1325413812169"><a name="p1325413812169"></a><a name="p1325413812169"></a>tms:resourceTags:delete</p>
</td>
<td class="cellrowborder" valign="top" width="53.580000000000005%" headers="mcps1.2.4.1.3 "><p id="p19254338131610"><a name="p19254338131610"></a><a name="p19254338131610"></a>POST /v1.0/{resource_type}/{resource_id}/tags/action</p>
</td>
</tr>
</tbody>
</table>

