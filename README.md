<div align="center">

# 史轶文 · Shi Yiwen

**厦门大学 · 计算机科学与技术 · 本科在读（2024 级）**

[![Typing SVG](https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&weight=800&size=20&duration=3000&pause=1000&color=88C0D0&center=true&vCenter=true&width=560&height=45&lines=AI+Agent+%2F+LLM+Applications;Reading+agent+framework+source+code;Building+terminal+tools+with+LLMs)](https://github.com/fszcd)

</div>

## 🧭 About

- 厦门大学计算机科学与技术专业本科生，方向：**AI Agent / 大模型应用**（上下文工程、工具调用、多智能体、RAG）
- 长期在 AI Agent 开源生态里学习和贡献代码：给 **claude-code-router**（37k+ ⭐）等项目提交过已合并的修复，同时精读主流 Agent 框架源码（见下方书单）
- 正在实现自己的终端 Coding Agent：[**MewCode**](https://github.com/fszcd/MewCode)（开发中）

## 🔧 Open Source Contributions

已合并的 PR（按项目热度排序）：

| 项目 | 说明 | PR |
| --- | --- | --- |
| [claude-code-router](https://github.com/musistudio/claude-code-router) ⭐37k+ | AI Agent 本地路由控制面：跨模型路由、能力聚合、编排。修复 gateway 核心配置接受超时不可配置的问题 | [#1794](https://github.com/musistudio/claude-code-router/pull/1794) |
| [ccrelay](https://github.com/amd5452/ccrelay) | claude-code-router 生态项目。修复 codex 场景下相邻 commentary 与 pending tool calls 的合并问题 | [commit](https://github.com/amd5452/ccrelay/commits?author=fszcd) |
| [cc-switch](https://github.com/chy-3825/cc-switch-stable-custom) | Claude Code / Codex 跨平台切换助手。同上修复 | [commit](https://github.com/chy-3825/cc-switch-stable-custom/commits?author=fszcd) |
| [RelayDesk](https://github.com/zhang520zy-prog/RelayDesk) | claude-code-router 生态项目。同上修复 | [commit](https://github.com/zhang520zy-prog/RelayDesk/commits?author=fszcd) |
| [Lightweight-opensource-ai-agent](https://github.com/murshedy2k/Lightweight-opensource-ai-agent) | 修复 OS 级代理环境下安全相关测试互相污染的问题（fixture hermetic） | [commit](https://github.com/murshedy2k/Lightweight-opensource-ai-agent/commits?author=fszcd) |

## 📚 Reading List（正在精读的 Agent 框架源码）

> Repositories 里的 fork 是我的「源码书单」：通过读主流框架的实现来理解 Agent 的上下文管理、工具调用与多智能体编排。

![dify](https://img.shields.io/badge/dify-workflow%20%2B%20RAG-1C64F2) ![camel](https://img.shields.io/badge/camel-multi--agent-88C0D0) ![smolagents](https://img.shields.io/badge/smolagents-code%20agent-FFD21E) ![pydantic-ai](https://img.shields.io/badge/pydantic--ai-typed%20agents-E92063) ![agentscope](https://img.shields.io/badge/agentscope-multi--agent-88C0D0) ![DB-GPT](https://img.shields.io/badge/DB--GPT-AI%20%2B%20data-1C64F2) ![litellm](https://img.shields.io/badge/litellm-LLM%20gateway-88C0D0) ![fastmcp](https://img.shields.io/badge/fastmcp-MCP%20server-1C64F2)

## 🛠 Projects

### [MewCode](https://github.com/fszcd/MewCode) — 终端 AI 编程助手（开发中）

> 受 Claude Code 等终端编程产品启发的学习实践项目：基于 ReAct 与 Plan Mode 双模式驱动 LLM 自主完成编程任务，采用「引擎 - 工具 - 交互 - 记忆 - 安全」五层结构。

- 🧠 上下文压缩：两层渐进式压缩，自动对齐 Function Calling 调用配对约束，支持长时间连续会话
- 💾 跨会话记忆：用户偏好 / 纠正反馈 / 项目知识 / 参考信息四类记忆持久化（JSONL），新会话自动继承项目上下文
- 🤖 多 Agent 协作：复杂任务拆分并行，基于 Git Worktree 文件级隔离；Coordinator 只负责拆分与汇总
- 🔌 MCP 工具按需加载 schema，百级工具场景下工具描述 Token 占用减少 85%；统一 Anthropic / OpenAI 双流式协议

<!-- TODO：仓库建好后放架构图 + 终端演示 GIF，删掉本行
![architecture](docs/architecture.png)
![demo](docs/demo.gif)
-->

### RAG 知识问答系统（仓库整理中）

基于 LangChain 的检索增强问答实践：文档解析 → 分块（512 token / 50 重叠）→ 向量化（text-embedding-v4）→ 语义检索（ChromaDB）→ 生成，Top-K 检索召回率 92%；集成 ReAct 智能体（6 个工具），工具调用准确率 >90%。

### 校园外卖系统（基于开源课程架构二次开发）

Spring Boot 前后端分离系统：Redis 缓存优化（接口平均响应 120ms → 15ms）、JWT 双端认证、六态订单状态机、微信支付集成、WebSocket 实时推送。

## 📮 Contact

- 📮 Email：[2256433591@qq.com](mailto:2256433591@qq.com)
- 🏫 厦门大学 · 计算机科学与技术 · 2024 级

