# 🎯 AI 全栈工程化 · 互动打卡清单

> 用法：把 `- [ ]` 改成 `- [x]` 即完成打卡。建议在 GitHub 仓库或 Obsidian 中使用。

## 📊 总进度
- [ ] 阶段一：零代码 & 全栈基础
- [ ] 阶段二：RAG & Agent 工程化
- [ ] 阶段三：微服务 & 行业落地
- [ ] 阶段四：模型微调 & 部署

---

## 阶段一：零代码 & 全栈基础

📦 **核心仓库**：[Karovia/fullstack-ai-agent-roadmap](https://github.com/Karovia/fullstack-ai-agent-roadmap)（58 万字，110 个教程，30+ 章节验收项目）

### 大章节 1：Python & 后端地基
- [ ] 完成 Python 基础语法与数据结构教程（对应仓库 `01 Python` 章节）
- [ ] 做完该章节的 **验收项目**（仓库要求“没做完不算学完”）
- [ ] 用 FastAPI 独立跑通一个最小的 CRUD 接口

### 大章节 2：数据库与全栈贯通
- [ ] 完成 SQL 与关系型数据库设计教程（对应 `06 数据库`）
- [ ] 把 CRUD 接口连接到真实数据库，完成一次完整读写

---

## 阶段二：RAG & Agent 工程化

📦 **核心仓库**：
- [dsplab75/awesome-llm-apps](https://github.com/dsplab75/awesome-llm-apps)（100+ 可直接运行的 Agent/RAG 模板）
- [Karovia/fullstack-ai-agent-roadmap](https://github.com/Karovia/fullstack-ai-agent-roadmap)（`08 AI Agent` 章节）

### 大章节 3：RAG 检索增强生成
- [ ] 从 `awesome-llm-apps` 中 **clone 并跑通** 一个 RAG 模板（3 条命令即可启动）
- [ ] 理解模板的检索链路：文档切分 → 向量化 → 召回 → 重排
- [ ] 把模板改成你自己的私有数据，验证问答效果

### 大章节 4：AI Agent 开发
- [ ] 跑通 `awesome-llm-apps` 中一个 **Agent 模板**（如 Tool Use / Multi-Agent）
- [ ] 阅读 `fullstack-ai-agent-roadmap` 的 Agent 章节，完成对应练习题

---

## 阶段三：微服务 & 行业落地

📦 **核心仓库**：[findpsyche/GoodFDE](https://github.com/findpsyche/GoodFDE)（基于真实 JD 的就业路线，覆盖生产级 RAG + Multi-Agent + 模型部署）

### 大章节 5：企业级服务与部署
- [ ] 打开 `GoodFDE` 中的 **`AI_100天学习计划_JD分析版_2025.md`**，通读一遍路线图
- [ ] 完成 **“模型服务化”** 相关模块：用 FastAPI 封装一个 LLM 接口
- [ ] 用 Docker 把封装好的服务打包运行

### 大章节 6：Multi-Agent 与生产级 RAG
- [ ] 跑通 `GoodFDE` 推荐的 **LangGraph Multi-Agent** 示例
- [ ] 对比 `awesome-llm-apps` 中的 RAG 模板，总结生产级 RAG 多了哪些工程环节（监控、鉴权、缓存等）

---

## 阶段四：模型微调 & 部署

📦 **核心仓库**：继续使用 [findpsyche/GoodFDE](https://github.com/findpsyche/GoodFDE)

### 大章节 7：LoRA / SFT 微调
- [ ] 完成 `GoodFDE` 知识库中 **LoRA/SFT 微调** 的理论部分
- [ ] 找一个开源小模型（如 Qwen 小尺寸版本），跑通一次 **LoRA 微调脚本**
- [ ] 对比微调前后的输出差异，写一段简短实验记录

### 大章节 8：高性能推理部署
- [ ] 用 **vLLM 或 Ollama** 在本机部署一个模型，跑通推理接口
- [ ] 记录吞吐/延迟数据，和直接调用 API 做一次对比
