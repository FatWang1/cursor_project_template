# AI Project Guide Template

## 1. 项目结构建议
- 推荐目录结构（可按需调整）：

```sh
/{{PROJECT_ROOT}}
├── main.go / app.py / index.js # 入口文件
├── go.mod / package.json / pyproject.toml
├── internal/ 或 src/
│ └── {{MODULE_NAME}}/ # 核心模块
│ ├── server.go / handler.py
│ ├── model.go / model.py
│ ├── config.go / config.py
│ └── ...
├── config/
│ └── config.yaml / config.json
└── tests/
└── ...
```
- 支持多语言/多框架，AI 可根据 `TECH_STACK` 自动调整。

## 2. 功能模块建议
- 支持灵活扩展，AI 可根据需求自动拆分/组合模块。
- 典型模块：请求路由、业务逻辑、数据访问、配置加载、测试、文档等。

## 3. 配置与集成
- 支持多种配置格式（JSON/YAML/TOML），AI 可自动识别并生成解析代码。
- 支持插件式扩展、热加载等高级特性。

## 4. AI协作建议
- 明确每个模块的职责，便于 AI 自动生成和后续维护。
- 可在本文件中补充“特殊约定”或“业务场景”，AI 会自动融合。
