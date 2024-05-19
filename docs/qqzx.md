# 接口地址

请求方式：`GET`

返回格式：`JSON`

```API
https://api.nxvav.cn/api/qqzx/
```

# 请求示例

[https://api.nxvav.cn/api/qqzx/?qq=36092547](https://api.nxvav.cn/api/qqzx/?qq=36092547)

# 使用场景

<!-- tabs:start -->

#### **html**

```html
等待编辑...
```

<!-- tabs:end -->

# 请求参数

| 参数名 | 类型 | 示例 | 说明 |
| ----- | ---- | ---- | ---- |
| qq | 必填 | QQ号码 | QQ号码 |

# 返回参数

| 返回参数 | 说明 |
| ------- | ---- |
| code | 状态码 |
| msg | 信息 |

# 状态代码

| 返回状态 | 说明 |
| ------- | ---- |
| 20 | 电脑离线 |
| 21 | 电脑在线 |

# 返回示例

```json
{
	"code": "21",
	"msg": "电脑在线"
}
```
