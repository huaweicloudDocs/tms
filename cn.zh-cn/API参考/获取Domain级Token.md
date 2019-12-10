# 获取Domain级Token<a name="ZH-CN_TOPIC_0186103096"></a>

```
POST https://iam.cn-north-1.myhuaweicloud.com/v3/auth/tokens
Content-Type: application/json

{
    "auth": {
        "identity": {
            "methods": [
                "password"
            ],
            "password": {
                "user": {
                    "name": "username",
                    "password": "********",
                    "domain": {
                        "name": "domainname"
                    }
                }
            }
        },
        "scope": {
            "domain": {
                "id": "xxxxxxxxxxxxxxxxxx"
            }
        }
    }
}
```

