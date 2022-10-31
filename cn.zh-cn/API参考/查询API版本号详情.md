# 查询API版本号详情<a name="ShowApiVersion"></a>

## 功能介绍<a name="section1978811415490"></a>

查询指定的标签管理服务API版本号详情。

## 调试<a name="section127889411493"></a>

您可以在[API Explorer](https://apiexplorer.developer.huaweicloud.com/apiexplorer/doc?product=TMS&api=ShowApiVersion)中调试该接口，支持自动认证鉴权。API Explorer可以自动生成SDK代码示例，并提供SDK代码示例调试功能。

## URI<a name="section978910419495"></a>

GET /\{api\_version\}

**表 1**  路径参数

|参数|是否必选|参数类型|描述|
|--|--|--|--|
|api_version|是|String|API版本号。|


## 请求参数<a name="section979415416494"></a>

无

## 响应参数<a name="section87941043495"></a>

**状态码： 200**

**表 2**  响应Body参数

|参数|参数类型|描述|
|--|--|--|
|version|VersionDetail object|版本详情|


**表 3**  VersionDetail

|参数|参数类型|描述|
|--|--|--|
|id|String|版本ID（版本号），如v1.0。|
|links|Array of Link objects|API的URL地址。|
|version|String|若该版本API支持微版本，则返回支持的最新微版本号，如果不支持微版本，则返回空。|
|status|String|版本状态，为如下3种： CURRENT：表示该版本为主推版本。 SUPPORTED：表示为老版本，但是现在还继续支持。 DEPRECATED：表示为废弃版本，存在后续删除的可能。|
|updated|String|版本发布时间，采用UTC时间表示。如v1.0发布的时间2016-12-09T00:00:00Z。|
|min_version|String|若该版本API 支持微版本，则返回支持的最早微版本号， 如果不支持微版本，则返回空。|


**表 4**  Link

|参数|参数类型|描述|
|--|--|--|
|href|String|API的URL地址。|
|rel|String|self|


**状态码： 400**

**表 5**  响应Body参数

|参数|参数类型|描述|
|--|--|--|
|error|RespErrorMessage object|响应错误信息|


**表 6**  RespErrorMessage

|参数|参数类型|描述|
|--|--|--|
|error_code|String|请求错误码|
|error_msg|String|错误信息|


**状态码： 404**

**表 7**  响应Body参数

|参数|参数类型|描述|
|--|--|--|
|error|RespErrorMessage object|响应错误信息|


**表 8**  RespErrorMessage

|参数|参数类型|描述|
|--|--|--|
|error_code|String|请求错误码|
|error_msg|String|错误信息|


**状态码： 405**

**表 9**  响应Body参数

|参数|参数类型|描述|
|--|--|--|
|error|RespErrorMessage object|响应错误信息|


**表 10**  RespErrorMessage

|参数|参数类型|描述|
|--|--|--|
|error_code|String|请求错误码|
|error_msg|String|错误信息|


**状态码： 406**

**表 11**  响应Body参数

|参数|参数类型|描述|
|--|--|--|
|error|RespErrorMessage object|响应错误信息|


**表 12**  RespErrorMessage

|参数|参数类型|描述|
|--|--|--|
|error_code|String|请求错误码|
|error_msg|String|错误信息|


**状态码： 408**

**表 13**  响应Body参数

|参数|参数类型|描述|
|--|--|--|
|error|RespErrorMessage object|响应错误信息|


**表 14**  RespErrorMessage

|参数|参数类型|描述|
|--|--|--|
|error_code|String|请求错误码|
|error_msg|String|错误信息|


**状态码： 409**

**表 15**  响应Body参数

|参数|参数类型|描述|
|--|--|--|
|error|RespErrorMessage object|响应错误信息|


**表 16**  RespErrorMessage

|参数|参数类型|描述|
|--|--|--|
|error_code|String|请求错误码|
|error_msg|String|错误信息|


**状态码： 410**

**表 17**  响应Body参数

|参数|参数类型|描述|
|--|--|--|
|error|RespErrorMessage object|响应错误信息|


**表 18**  RespErrorMessage

|参数|参数类型|描述|
|--|--|--|
|error_code|String|请求错误码|
|error_msg|String|错误信息|


**状态码： 412**

**表 19**  响应Body参数

|参数|参数类型|描述|
|--|--|--|
|error|RespErrorMessage object|响应错误信息|


**表 20**  RespErrorMessage

|参数|参数类型|描述|
|--|--|--|
|error_code|String|请求错误码|
|error_msg|String|错误信息|


**状态码： 429**

**表 21**  响应Body参数

|参数|参数类型|描述|
|--|--|--|
|error|RespErrorMessage object|响应错误信息|


**表 22**  RespErrorMessage

|参数|参数类型|描述|
|--|--|--|
|error_code|String|请求错误码|
|error_msg|String|错误信息|


**状态码： 500**

**表 23**  响应Body参数

|参数|参数类型|描述|
|--|--|--|
|error|RespErrorMessage object|响应错误信息|


**表 24**  RespErrorMessage

|参数|参数类型|描述|
|--|--|--|
|error_code|String|请求错误码|
|error_msg|String|错误信息|


**状态码： 501**

**表 25**  响应Body参数

|参数|参数类型|描述|
|--|--|--|
|error|RespErrorMessage object|响应错误信息|


**表 26**  RespErrorMessage

|参数|参数类型|描述|
|--|--|--|
|error_code|String|请求错误码|
|error_msg|String|错误信息|


**状态码： 503**

**表 27**  响应Body参数

|参数|参数类型|描述|
|--|--|--|
|error|RespErrorMessage object|响应错误信息|


**表 28**  RespErrorMessage

|参数|参数类型|描述|
|--|--|--|
|error_code|String|请求错误码|
|error_msg|String|错误信息|


## 请求示例<a name="section14051452492"></a>

查询标签管理接口版本号详情

```
GET https://{Endpoint}/v1.0
```

## 响应示例<a name="section140519512499"></a>

**状态码： 200**

OK

```
{
  "version" : {
    "id" : "v1.0",
    "links" : [ {
      "rel" : "self",
      "href" : "https://{Endpoint}/v1.0"
    } ],
    "version" : "",
    "status" : "CURRENT",
    "updated" : "2016-12-09T00:00:00Z",
    "min_version" : ""
  }
}
```

## 状态码<a name="section134061857491"></a>

|状态码|描述|
|--|--|
|200|OK|
|400|Bad Request|
|404|Not Found|
|405|Method Not Allowed|
|406|Not Acceptable|
|408|Request Timeout|
|409|Conflict|
|410|Gone|
|412|Precondition Failed|
|429|Too Many Requests|
|500|Internal Server Error|
|501|Not Implemented|
|503|Service Unavailable|


## 错误码<a name="section10408125164913"></a>

请参见[错误码](错误码.md)。

