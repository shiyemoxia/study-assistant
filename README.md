# 课程知识库与代码学习助手 Demo

这是一个用于展示 **AI 课程学习助手** 思路的前端 Demo。项目定位是：面向计算机专业课程资料整理、知识库问答、代码解释和复习计划生成的学习辅助系统。

> 说明：本仓库当前内容为 Demo 原型，页面中的文件、问答、统计数据均为演示数据，不代表真实生产系统。

## 功能模块

- **首页概览**：展示上传资料数量、知识点问答次数、代码解析次数和复习任务。
- **知识库管理**：模拟课程资料上传、解析状态、标签分类和资料统计。
- **智能问答**：基于课程资料进行问答，并展示引用资料卡片。
- **代码解析**：对 Scala / Spark 示例代码进行逐行解释、考点总结和常见错误提醒。
- **复习计划**：根据课程章节生成复习任务和学习进度。

## 如何运行

本项目是纯静态页面，不需要后端环境。

```bash
git clone https://github.com/shiyemoxia/study-assistant.git
cd study-assistant
# 直接用浏览器打开 index.html
```

或者使用 VS Code 的 Live Server 插件打开 `index.html`。

## 文件结构

```text
.
├── index.html        # 单文件前端 Demo
├── demo-data.json    # 演示数据
└── README.md         # 项目说明
```

## 适合展示的截图

建议截取以下页面：

1. 首页概览 Dashboard
2. 知识库管理页面
3. 智能问答页面
4. 代码解析页面
5. 复习计划页面

## 后续可扩展方向

- 接入真实文档解析能力：PDF / DOCX / PPTX 内容抽取。
- 接入向量数据库：FAISS、Milvus、Chroma 或 pgvector。
- 增加 RAG 检索增强问答流程。
- 增加用户学习记录、错题追踪和个性化复习计划。
- 使用 FastAPI / Flask / Spring Boot 搭建后端接口。

## 技术栈设想

- 前端：HTML / CSS / JavaScript 或 Vue / React
- 后端：FastAPI / Flask / Spring Boot
- AI 能力：LLM API + Embedding + RAG
- 数据存储：SQLite / MySQL / PostgreSQL
- 向量检索：FAISS / Chroma / Milvus
