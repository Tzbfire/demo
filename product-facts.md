# product-facts · Codex / Coding Agent

更新时间：2026-06-07（Asia/Shanghai）

## 已核验事实

1. OpenAI Developers 文档将 Codex 定义为 “OpenAI’s coding agent for software development”。文档列出的典型能力包括：write code、understand unfamiliar codebases、review code。
2. OpenAI 在 2025-05 发布/预览 Codex in ChatGPT。公开报道与 OpenAI 页面均描述其可处理软件工程任务；TechCrunch 报道称其可同时处理多个软件工程任务，并由面向软件工程优化的模型驱动。
3. Codex 相关文档包含 GitHub/code review、CLI、本地权限、AGENTS.md、自定义指令、subagents 等开发工作流主题。
4. OpenAI Developers 的 “Agent approvals & security” 文档强调：Codex 使用 sandboxing、approvals、network controls；默认情况下 agent 网络访问关闭；本地 Codex 使用 OS-enforced sandbox 限制可访问范围，并由 approval policy 控制越权操作。

## 讲解时的安全表述

- 对非技术听众说：Codex 是 OpenAI 的“会做软件任务的 AI 助手/编码代理”，不是只给建议的聊天机器人。
- 不承诺它“自动正确”或“可以直接上线”；所有结果仍需人类审核、测试和权限治理。
- 企业功能可用性取决于账号计划、管理员权限、仓库连接方式和 OpenAI 最新产品状态。

## 来源

- https://developers.openai.com/codex
- https://developers.openai.com/codex/agent-approvals-security
- https://developers.openai.com/codex/guides/agents-md
- https://openai.com/index/introducing-codex
- https://techcrunch.com/2025/05/16/openai-launches-codex-an-ai-coding-agent-in-chatgpt/
