# AIP05 企业 AI 工作台

AIP05 是一个自包含的企业 AI 工作台前端原型，覆盖对话、智能体、知识库、数据概览、调用记录、评测、Skills、MCP 和空间设置等管理场景。

## 运行

无需安装依赖，直接打开 `index.html`：

- 对话：`index.html#chat`
- 智能体：`index.html#agents`
- 知识库：`index.html#knowledge`
- 数据概览：`index.html#overview`

也可使用任意静态文件服务器：

```bash
python3 -m http.server 8080
```

然后访问 `http://localhost:8080/#chat`。

## 特性

- 单文件静态应用，无构建步骤和后端依赖。
- 企业 AI Workspace 对话体验。
- 正文引用、来源列表和原文预览联动。
- 智能体与知识资产管理。
- 响应式桌面端和移动端布局。
- 演示数据保存在浏览器本地存储中。

## 说明

该仓库用于产品原型演示。页面中的模型调用、文件解析和任务执行为前端模拟流程。
