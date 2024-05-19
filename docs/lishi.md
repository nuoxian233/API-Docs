# 接口地址

请求方式：`GET`

返回格式：`JSON` / `TEXT` / `JS`

```API
https://api.nxvav.cn/api/lishi/
```

# 请求示例

[https://api.nxvav.cn/api/lishi/](https://api.nxvav.cn/api/lishi/)

[https://api.nxvav.cn/api/lishi/?format=json](https://api.nxvav.cn/api/lishi/?format=json)

[https://api.nxvav.cn/api/lishi/?format=js](https://api.nxvav.cn/api/lishi/?format=js)

# 使用场景

<!-- tabs:start -->

#### **html**

```html
等待编辑...
```

<!-- tabs:end -->

# 请求参数

| 参数名 | 类型 | 示例 | 说明 |
| ------ | ---- | ---- | ---- |
| format | 可空 | json / js | 获取历史上的今天 js json格式 |

# 返回参数

| 返回参数 | 说明 |
| -------- | ---- |
| code | 状态码 |
| day | 今天时间 |
| content | 发生的事件 |

# 状态代码

| 返回状态 | 说明 |
| -------- | ---- |
| 200 | 正常 |

# 返回示例

```json
{
    "code": 200,
    "day": "2021年11月24日",
    "content": [
        "清朝军队攻陷广州展开广州大屠杀",
        "瑞典国王卡尔十一世出生",
        "美国第12任总统扎卡里泰勒出生",
        "俄罗斯共产主义革命家尤里马尔托夫出生",
        "德国军事家曼施坦因出生",
        "中国革命家政治家刘少奇出生",
        "抗日名将吉鸿昌逝世",
        "前日本首相西园寺公望逝世",
        "保加利亚一架客机在布拉迪斯拉发坠毁",
        "中国南方航空3943班机在广西阳朔县坠毁",
        "美军撤离苏比克海军基地",
        "中国物理学家周培源逝世",
        "十字航空3597号班机发生空难",
        "香港填词人作家黄沾逝世",
        "泰国前总理沙马顺达卫逝世"
    ]
}
```
