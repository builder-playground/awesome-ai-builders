# Awesome AI Builders

A curated list of open-source projects, tools, and tutorials for people building real products with AI — coders and non-coders alike.

面向「用 AI 把想法做成真实产品的人」的开源项目、工具与教程清单，不区分科班或非科班。

Every link below was checked on **2026-11-17** through the GitHub REST API: the repository resolves, is public, and is not archived.
以下链接均于 **2026-11-17** 通过 GitHub REST API 实测：仓库可访问、公开、未归档。

## Contents / 目录

- [Coding agents & editors / AI 编程 agent 与编辑器](#coding-agents--editors--ai-编程-agent-与编辑器)
- [Agent frameworks & building blocks / Agent 框架与积木](#agent-frameworks--building-blocks--agent-框架与积木)
- [Infrastructure / 基础设施](#infrastructure--基础设施)
- [Learn & collections / 教程与合集](#learn--collections--教程与合集)
- [Adding an entry / 如何添加条目](#adding-an-entry--如何添加条目)

## Coding agents & editors / AI 编程 agent 与编辑器

- [openai/codex](https://github.com/openai/codex) — Lightweight coding agent that runs in your terminal. 在终端里跑的轻量编程 agent。
- [anthropics/claude-code](https://github.com/anthropics/claude-code) — Agentic coding tool in the terminal: reads the codebase, runs tasks, handles git. 终端里的 agentic 编程工具，能读代码库、跑任务、处理 git 流程。
- [google-gemini/gemini-cli](https://github.com/google-gemini/gemini-cli) — Open-source terminal agent that brings Gemini into your shell. 把 Gemini 接到终端的开源 agent。
- [Aider-AI/aider](https://github.com/Aider-AI/aider) — AI pair programming in your terminal, with automatic git commits. 终端里的 AI 结对编程，自动生成 git commit。
- [cline/cline](https://github.com/cline/cline) — Autonomous coding agent usable as an IDE extension, CLI, or SDK. 可作为 IDE 扩展、CLI 或 SDK 使用的自主编程 agent。
- [continuedev/continue](https://github.com/continuedev/continue) — Open-source coding agent you can plug into your editor and your own models. 可接编辑器与自有模型的开源编程 agent。
- [SWE-agent/SWE-agent](https://github.com/SWE-agent/SWE-agent) — Takes a GitHub issue and tries to fix it automatically with your chosen model. 给一个 GitHub issue，用你选的模型自动尝试修复。

## Agent frameworks & building blocks / Agent 框架与积木

- [OpenHands/OpenHands](https://github.com/OpenHands/OpenHands) — Open platform for AI-driven development, from sandbox to running agent. AI 驱动开发的开放平台，含沙箱与可运行的 agent。
- [microsoft/autogen](https://github.com/microsoft/autogen) — Framework for building multi-agent conversations and workflows. 构建多 agent 对话与工作流的框架。
- [FoundationAgents/MetaGPT](https://github.com/FoundationAgents/MetaGPT) — Multi-agent framework that assigns roles (PM, architect, engineer) to build software. 用角色分工（产品、架构、工程）来写软件的多 agent 框架。
- [crewAIInc/crewAI](https://github.com/crewAIInc/crewAI) — Framework for orchestrating role-playing autonomous agents. 编排角色化自主 agent 的框架。
- [langchain-ai/langchain](https://github.com/langchain-ai/langchain) — The widely used platform for composing LLM apps and agents. 组合 LLM 应用与 agent 的通用框架。
- [huggingface/smolagents](https://github.com/huggingface/smolagents) — Barebones library for agents that write actions as code. 轻量 agent 库，让 agent 把动作写成代码。
- [browser-use/browser-use](https://github.com/browser-use/browser-use) — Python library for AI browser agents, so agents can click through real pages. 让 agent 真的去点网页的 Python 库。
- [e2b-dev/E2B](https://github.com/e2b-dev/E2B) — Secure sandbox environments with real tools for running agent-generated code. 给 agent 生成代码用的安全沙箱环境。
- [modelcontextprotocol/servers](https://github.com/modelcontextprotocol/servers) — Reference MCP servers showing how to expose tools and data to agents. MCP 参考实现，示范如何把工具和数据暴露给 agent。

## Infrastructure / 基础设施

- [ollama/ollama](https://github.com/ollama/ollama) — Run open models locally with one command. 一条命令在本地跑开源模型。
- [vllm-project/vllm](https://github.com/vllm-project/vllm) — High-throughput inference and serving engine for LLMs. 高吞吐的 LLM 推理与服务引擎。
- [sgl-project/sglang](https://github.com/sgl-project/sglang) — Fast serving framework for language and multimodal models. 语言与多模态模型的快速服务框架。

## Learn & collections / 教程与合集

- [microsoft/generative-ai-for-beginners](https://github.com/microsoft/generative-ai-for-beginners) — 21 lessons that start from zero and end with a working generative AI app. 从零开始的 21 课，走完能做出一个生成式 AI 应用。
- [openai/openai-cookbook](https://github.com/openai/openai-cookbook) — Examples and guides for using the OpenAI API in practice. OpenAI API 的实战示例与指南。
- [anthropics/claude-cookbooks](https://github.com/anthropics/claude-cookbooks) — Notebooks and recipes for building with Claude. 用 Claude 做东西的 notebook 与配方。
- [punkpeye/awesome-mcp-servers](https://github.com/punkpeye/awesome-mcp-servers) — Collection of MCP servers you can plug into your own agents. 可直接接入自己 agent 的 MCP server 合集。
- [PatrickJS/awesome-cursorrules](https://github.com/PatrickJS/awesome-cursorrules) — Collection of rule files that shape how AI editors behave on a codebase. 影响 AI 编辑器在代码库里行为的规则文件合集。

## Adding an entry / 如何添加条目

- The project must be open source and publicly accessible. 项目必须开源且可公开访问。
- One line per entry, in English and Chinese, saying what it does — not what it promises. 每条一句中英文说明，讲它做什么，不讲它承诺什么。
- Open a pull request; the template asks where you checked the link. 直接提 PR，模板会问你在哪校验过链接。
- Entries that are unverified, paywalled, or dead will be removed. 无法校验、需要付费墙或已失效的条目会被移除。

---

<sub>Brand: `Builder Playground` · Maintained by the community.</sub>
