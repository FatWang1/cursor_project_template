# AI Project Design Template

## 1. 核心数据结构
- 以伪代码/多语言风格描述主要结构体、类、接口。
- 支持字段注释、类型说明、可选/必选标记。

```go
type {{Entity}} struct {
    ID      int    // 主键
    Name    string // 名称
    // ... 其他字段
}
```

## 2. 主要接口/方法
- 以伪代码/多语言风格描述主要 API、服务方法、路由等。
- 支持 REST/gRPC/GraphQL/CLI 等多种风格。

```go
// 创建新实体
func Create{{Entity}}(input Create{{Entity}}Input) ({{Entity}}, error)
```

## 3. 配置与扩展
- 说明如何通过配置文件/参数扩展功能。
- 支持插件、钩子、事件等机制。

## 4. AI协作建议
- 可在本文件中补充“特殊业务规则”、“接口约束”，AI 会自动融合。