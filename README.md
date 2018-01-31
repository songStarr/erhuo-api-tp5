# 二货api接口文档
## 1.获得验证码
>get api.erhuo.com/code

|参数|类型|必需/可选|默认|描述|
|-|-|-|-|-|
|time|int|必需|无|时间戳（用于判断请求是否超时）|
|token|string|必需|无|确定来着身份|
|username|string|必需|无|手机号或邮箱|
|is_exist|int|必需|无|用户名是否应该存在（1：是 0：否）|

```json
{
    "code": 200,
    "msg": "手机验证码已经发送成功, 每天可以发送5次, 请在一分钟内验证!",
    "data": []
}
```
