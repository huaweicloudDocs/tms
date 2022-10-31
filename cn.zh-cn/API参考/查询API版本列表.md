# 查询API版本列表<a name="ListApiVersions"></a>

## 功能介绍<a name="section1720212411493"></a>

查询标签管理服务的API版本列表。

## 调试<a name="section17204154114919"></a>

您可以在[API Explorer](https://apiexplorer.developer.huaweicloud.com/apiexplorer/doc?product=TMS&api=ListApiVersions)中调试该接口，支持自动认证鉴权。API Explorer可以自动生成SDK代码示例，并提供SDK代码示例调试功能。

## URI<a name="section22056413490"></a>

GET /

## 请求参数<a name="section420613414493"></a>

无

## 响应参数<a name="section1920716414920"></a>

**状态码： 200**

**表 1**  响应Body参数

|参数|参数类型|描述|
|--|--|--|
|versions|Array of VersionDetail objects|版本列表|


**表 2**  VersionDetail

|参数|参数类型|描述|
|--|--|--|
|id|String|版本ID（版本号），如v1.0。|
|links|Array of Link objects|API的URL地址。|
|version|String|若该版本API支持微版本，则返回支持的最新微版本号，如果不支持微版本，则返回空。|
|status|String|版本状态，为如下3种： CURRENT：表示该版本为主推版本。 SUPPORTED：表示为老版本，但是现在还继续支持。 DEPRECATED：表示为废弃版本，存在后续删除的可能。|
|updated|String|版本发布时间，采用UTC时间表示。如v1.0发布的时间2016-12-09T00:00:00Z。|
|min_version|String|若该版本API 支持微版本，则返回支持的最早微版本号， 如果不支持微版本，则返回空。|


**表 3**  Link

|参数|参数类型|描述|
|--|--|--|
|href|String|API的URL地址。|
|rel|String|self|


**状态码： 400**

**表 4**  响应Body参数

|参数|参数类型|描述|
|--|--|--|
|error|RespErrorMessage object|响应错误信息|


**表 5**  RespErrorMessage

|参数|参数类型|描述|
|--|--|--|
|error_code|String|请求错误码|
|error_msg|String|错误信息|


**状态码： 404**

**表 6**  响应Body参数

|参数|参数类型|描述|
|--|--|--|
|error|RespErrorMessage object|响应错误信息|


**表 7**  RespErrorMessage

|参数|参数类型|描述|
|--|--|--|
|error_code|String|请求错误码|
|error_msg|String|错误信息|


**状态码： 405**

**表 8**  响应Body参数

|参数|参数类型|描述|
|--|--|--|
|error|RespErrorMessage object|响应错误信息|


**表 9**  RespErrorMessage

|参数|参数类型|描述|
|--|--|--|
|error_code|String|请求错误码|
|error_msg|String|错误信息|


**状态码： 406**

**表 10**  响应Body参数

|参数|参数类型|描述|
|--|--|--|
|error|RespErrorMessage object|响应错误信息|


**表 11**  RespErrorMessage

|参数|参数类型|描述|
|--|--|--|
|error_code|String|请求错误码|
|error_msg|String|错误信息|


**状态码： 409**

**表 12**  响应Body参数

|参数|参数类型|描述|
|--|--|--|
|error|RespErrorMessage object|响应错误信息|


**表 13**  RespErrorMessage

|参数|参数类型|描述|
|--|--|--|
|error_code|String|请求错误码|
|error_msg|String|错误信息|


**状态码： 410**

**表 14**  响应Body参数

|参数|参数类型|描述|
|--|--|--|
|error|RespErrorMessage object|响应错误信息|


**表 15**  RespErrorMessage

|参数|参数类型|描述|
|--|--|--|
|error_code|String|请求错误码|
|error_msg|String|错误信息|


**状态码： 412**

**表 16**  响应Body参数

|参数|参数类型|描述|
|--|--|--|
|error|RespErrorMessage object|响应错误信息|


**表 17**  RespErrorMessage

|参数|参数类型|描述|
|--|--|--|
|error_code|String|请求错误码|
|error_msg|String|错误信息|


**状态码： 429**

**表 18**  响应Body参数

|参数|参数类型|描述|
|--|--|--|
|error|RespErrorMessage object|响应错误信息|


**表 19**  RespErrorMessage

|参数|参数类型|描述|
|--|--|--|
|error_code|String|请求错误码|
|error_msg|String|错误信息|


**状态码： 500**

**表 20**  响应Body参数

|参数|参数类型|描述|
|--|--|--|
|error|RespErrorMessage object|响应错误信息|


**表 21**  RespErrorMessage

|参数|参数类型|描述|
|--|--|--|
|error_code|String|请求错误码|
|error_msg|String|错误信息|


**状态码： 501**

**表 22**  响应Body参数

|参数|参数类型|描述|
|--|--|--|
|error|RespErrorMessage object|响应错误信息|


**表 23**  RespErrorMessage

|参数|参数类型|描述|
|--|--|--|
|error_code|String|请求错误码|
|error_msg|String|错误信息|


**状态码： 503**

**表 24**  响应Body参数

|参数|参数类型|描述|
|--|--|--|
|error|RespErrorMessage object|响应错误信息|


**表 25**  RespErrorMessage

|参数|参数类型|描述|
|--|--|--|
|error_code|String|请求错误码|
|error_msg|String|错误信息|


## 请求示例<a name="section948404114913"></a>

查询标签管理接口版本号列表

```
GET https://{Endpoint}/
```

## 响应示例<a name="section10484174164917"></a>

**状态码： 200**

OK

```
{
  "versions" : [ {
    "id" : "v1.0",
    "links" : [ {
      "rel" : "self",
      "href" : "https://{Endpoint}/v1.0"
    } ],
    "version" : "",
    "status" : "CURRENT",
    "updated" : "2016-12-09T00:00:00Z",
    "min_version" : ""
  } ]
}
```

## 状态码<a name="section20485144184919"></a>

|状态码|描述|
|--|--|
|200|OK|
|400|Bad Request|
|404|Not Found|
|405|Method Not Allowed|
|406|Not Acceptable|
|409|Conflict|
|410|Gone|
|412|Precondition Failed|
|429|Too Many Requests|
|500|Internal Server Error|
|501|Not Implemented|
|503|Service Unavailable|


## 错误码<a name="section174860454916"></a>

请参见[错误码](错误码.md)。

