# 标签管理服务API授权列表项<a name="zh-cn_topic_0180205869"></a>

**表 1**  API授权项列表

|权限|对应API接口|授权项(Action)|IAM项目(Project)|企业项目(Enterprise Project)|
|--|--|--|--|--|
|查询预定义标签|GET /v1.0/predefine_tags|tms:predefineTags:list|√|x|
|创建预定义标签|POST /v1.0/predefine_tags/action|tms:predefineTags:create|√|x|
|删除预定义标签|POST /v1.0/predefine_tags/action|tms:predefineTags:delete|√|x|
|修改预定义标签|PUT /v1.0/predefine_tags/action|tms:predefineTags:update|√|x|
|查询资源标签|GET /v1.0/tags|tms:resourceTags:list|√|x|
|创建资源标签|POST /v1.0/{resource_type}/{resource_id}/tags/action|tms:resourceTags:create|√|x|
|删除资源标签|POST /v1.0/{resource_type}/{resource_id}/tags/action|tms:resourceTags:delete|√|x|


