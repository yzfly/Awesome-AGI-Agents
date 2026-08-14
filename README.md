# Awesome-AGI-Agents

Agents (智能体) 精选资源合集，持续更新中

## 目录

- [文章和视频](#文章和视频)
- [论文](#论文)
- [2024-2026 重要项目](#2024-2026-重要项目)
- [前沿项目](#前沿项目)
- [Agents 开发平台](#agents-开发平台)
- [Curated List](#curated-list)
- [Star History](#star-history)

## 文章和视频

|名称|简介|备注|
|---|---|---|
|[AI Agents大爆发：软件2.0雏形初现，OpenAI的下一步](https://mp.weixin.qq.com/s/Jb8HBbaKYXXxTSQOBsP5Wg)|Lilian Weng 的个人博客文章，Lilian 现在是 OpenAI 的 Head of Safety Systems，之前还领导过 OpenAI 的 Applied AI 团队。AI Agent 被认为是 OpenAI 发力的下一个方向。OpenAI 的联合创始人 Andrej Karpathy 在近期的一次公开活动上提到“相比模型训练方法，OpenAI 内部目前更关注 Agent 领域的变化，每当有新的 AI Agents 论文出来的时候，内部都会很兴奋并且认真地讨论”，而在更早之前，Andrej  还评价 AutoGPT 是 Prompt Engineering 下一阶段的探索方向。|[英文原文](https://lilianweng.github.io/posts/2023-06-23-agent/)|
|[《综述：全新大语言模型驱动的Agent》——4.5万字详细解读复旦NLP和米哈游最新Agent Survey](https://zhuanlan.zhihu.com/p/656676717)|复旦NLP团队和米哈游一起出的《TITLE：The Rise and Potential of Large Language Model Based Agents: A Survey》论文一个翻译版本，作者同时对部分内容进行了删繁就简，总结概括。|[论文原文](https://arxiv.org/pdf/2309.07864v1.pdf)|
|[AI Agent的千亿美金问题：如何重构10亿知识工作职业，掀起软件生产革命？](https://mp.weixin.qq.com/s/JYu_oXWbWbasT1fcBRo-cA)|作者认为 agent 产品需要具备的特性是，要给产品设计者和用户提供干预空间。目前实践中最具代表性的有两类：中间层的 Agent Framework 和垂直领域的 Vertical Agent。|-|
|[LangChain Agents - Joining Tools and Chains with Decisions](https://www.youtube.com/watch?v=ziu87EXZVUE&ab_channel=SamWitteveen)|LangChain Agents--将工具和任务链与决策结合起来|英文 Youtube 视频，LangChain 项目官方对预置的 agents 介绍。|-|


## 论文
|名称|简介|备注|
|---|---|---|
|[LLM-Agent-Survey](https://github.com/Paitesanshi/LLM-Agent-Survey)| LLM-based Autonomous Agents 综述| ![GitHub Repo stars](https://badgen.net/github/stars/Paitesanshi/LLM-Agent-Survey)|
|[LLM-Agent-Paper-List](https://github.com/WooooDyy/LLM-Agent-Paper-List)| "The Rise and Potential of Large Language Model Based Agents: A Survey"综述论文的论文列表| ![GitHub Repo stars](https://badgen.net/github/stars/WooooDyy/LLM-Agent-Paper-List)|
|[LLMAgentPapers](https://github.com/zjunlp/LLMAgentPapers)| LLM-based Autonomous Agents 综述| ![GitHub Repo stars](https://badgen.net/github/stars/zjunlp/LLMAgentPapers)|
|[Toolformer: Language Models Can Teach Themselves to Use Tools](https://arxiv.org/abs/2302.04761)|大语言模型可以学会使用工具|-|
|[HuggingGPT: Solving AI Tasks with ChatGPT and its Friends in Hugging Face](https://arxiv.org/abs/2303.17580)|用ChatGPT作为控制器，连接HuggingFace社区中的各种AI模型，完成多模态复杂任务。整个过程，只需要做的是：用自然语言将你的需求输出。|[知乎中文讨论](https://www.zhihu.com/question/594533230/answer/2975525808)|
|[ToolLLM: Facilitating Large Language Models to Master 16000+ Real-world APIs](https://arxiv.org/abs/2307.16789)|研究人员设计了一个评测 LLM 使用工具能力的 Benchmark（基准）—— LLMBench，以及一个针对该场景的数据构建、模型训练、评测的框架—— ToolLLM。|[[知乎文章](https://zhuanlan.zhihu.com/p/649277843)], [[GitHub 开源地址](https://github.com/OpenBMB/ToolBench)]|
|[AgentBench: Evaluating LLMs as Agents](https://arxiv.org/abs/2308.03688)| AgentBench 是首个旨在评估 LLM 在各种不同环境中作为智能体的基准。它包含 8 种不同的环境，可以更全面地评估 LLM 在各种场景中作为自主智能体运行的能力。|[GitHub 开源地址](https://github.com/THUDM/AgentBench)|


## 2024-2026 重要项目

本仓库早期内容主要覆盖 2023 年的 Agent 生态。以下为 2024-2026 年间崛起并经验证仍活跃的重要项目与协议。

|名称|Stars|简介|
|---|---|---|
|[LangGraph](https://github.com/langchain-ai/langgraph)|![GitHub Repo stars](https://badgen.net/github/stars/langchain-ai/langgraph)|LangChain 团队推出的有状态、多角色 Agent 编排框架，以图 (Graph) 的方式构建可控、可循环的 Agent 工作流。|
|[CrewAI](https://github.com/crewAIInc/crewAI)|![GitHub Repo stars](https://badgen.net/github/stars/crewAIInc/crewAI)|面向角色协作的多 Agent 框架，让多个扮演不同角色的智能体像团队一样协同完成复杂任务。|
|[OpenAI Agents SDK](https://github.com/openai/openai-agents-python)|![GitHub Repo stars](https://badgen.net/github/stars/openai/openai-agents-python)|OpenAI 官方推出的轻量级多 Agent 编排 SDK，内置 handoffs, guardrails 与 tracing，是 Swarm 的生产级继任者。|
|[OpenHands](https://github.com/OpenHands/OpenHands)|![GitHub Repo stars](https://badgen.net/github/stars/OpenHands/OpenHands)|原 OpenDevin，能够编写代码, 运行命令, 浏览网页的自主软件工程 Agent 平台。|
|[SWE-agent](https://github.com/SWE-agent/SWE-agent)|![GitHub Repo stars](https://badgen.net/github/stars/SWE-agent/SWE-agent)|普林斯顿大学出品，让语言模型自主修复 GitHub Issue 的 Agent，在 SWE-bench 上表现出色。|
|[Model Context Protocol (MCP)](https://github.com/modelcontextprotocol)|![GitHub Repo stars](https://badgen.net/github/stars/modelcontextprotocol/modelcontextprotocol)|Anthropic 提出的开放协议，为 LLM 与外部工具, 数据源的连接提供统一标准，已成为 Agent 生态事实标准。|
|[Browser Use](https://github.com/browser-use/browser-use)|![GitHub Repo stars](https://badgen.net/github/stars/browser-use/browser-use)|让 AI Agent 像人一样操作浏览器，是当下最流行的网页自动化 Agent 工具之一。|
|[smolagents](https://github.com/huggingface/smolagents)|![GitHub Repo stars](https://badgen.net/github/stars/huggingface/smolagents)|Hugging Face 推出的极简 Agent 库，核心仅约一千行代码，主打以代码形式编写 Agent 动作。|
|[Pydantic AI](https://github.com/pydantic/pydantic-ai)|![GitHub Repo stars](https://badgen.net/github/stars/pydantic/pydantic-ai)|由 Pydantic 团队打造的 Agent 框架，强调类型安全与结构化输出，将 Pydantic 的工程体验带入 GenAI 开发。|
|[A2A (Agent2Agent)](https://github.com/a2aproject/A2A)|![GitHub Repo stars](https://badgen.net/github/stars/a2aproject/A2A)|Google 发起的开放协议 (现由 Linux 基金会托管)，用于不同框架, 不同厂商的 Agent 之间互联互通。|
|[Claude Code](https://github.com/anthropics/claude-code)|![GitHub Repo stars](https://badgen.net/github/stars/anthropics/claude-code)|Anthropic 官方推出的终端编程 Agent，可在命令行中理解代码库、编辑文件、运行命令并完成复杂工程任务，是 2025 年最具影响力的 coding agent 之一。|
|[Gemini CLI](https://github.com/google-gemini/gemini-cli)|![GitHub Repo stars](https://badgen.net/github/stars/google-gemini/gemini-cli)|Google 官方开源的终端 AI Agent，将 Gemini 模型带入命令行，支持代码理解、工具调用与 MCP，采用 Apache-2.0 协议。|
|[Cline](https://github.com/cline/cline)|![GitHub Repo stars](https://badgen.net/github/stars/cline/cline)|VS Code 中的自主编程 Agent，可创建/编辑文件、执行命令、使用浏览器，并原生支持 MCP，是最流行的开源 IDE 编程助手之一。|
|[Google ADK](https://github.com/google/adk-python)|![GitHub Repo stars](https://badgen.net/github/stars/google/adk-python)|Google 开源的 Agent Development Kit，模型与部署无关的代码优先 Agent 开发框架，为 Google 自家 Agent 产品提供支撑，并原生支持 A2A/MCP。|
|[Microsoft Agent Framework](https://github.com/microsoft/agent-framework)|![GitHub Repo stars](https://badgen.net/github/stars/microsoft/agent-framework)|微软推出的新一代开源 Agent 框架，统一并继承 AutoGen 与 Semantic Kernel，面向生产级多 Agent 编排与工作流。|
|[AG-UI](https://github.com/ag-ui-protocol/ag-ui)|![GitHub Repo stars](https://badgen.net/github/stars/ag-ui-protocol/ag-ui)|Agent-User Interaction Protocol，用于连接后端 Agent 与前端应用的开放协议，与 MCP(接工具)、A2A(接 Agent)互补，专注 Agent 与用户界面的实时交互。|


## 前沿项目
|名称|Stars|简介|备注|
|---|---|---|---|
|[:fire: AutoGPT](https://github.com/Significant-Gravitas/AutoGPT) |![GitHub Repo stars](https://badgen.net/github/stars/Significant-Gravitas/AutoGPT)|An experimental open-source attempt to make GPT-4 fully autonomous.|大名鼎鼎的 AutoGPT 项目, AI Agents 的早期尝试之一 (2023, 活跃度下降)|
|[:fire: gpt-engineer](https://github.com/AntonOsika/gpt-engineer)|![GitHub Repo stars](https://badgen.net/github/stars/AntonOsika/gpt-engineer)|Specify what you want it to build, the AI asks for clarification, and then builds it.|全栈开发 Agent，用 GPT 编写整个项目代码！|
|[:fire: AgentGPT](https://github.com/reworkd/AgentGPT) |![GitHub Repo stars](https://badgen.net/github/stars/reworkd/AgentGPT)|Assemble, configure, and deploy autonomous AI Agents in your browser.|在浏览器中部署运行 AI Agents.|
|[:fire: MetaGPT](https://github.com/FoundationAgents/MetaGPT) |![GitHub Repo stars](https://badgen.net/github/stars/FoundationAgents/MetaGPT)|🌟 The Multi-Agent Framework: Given one line Requirement, return PRD, Design, Tasks, Repo. |MetaGPT, 多智能体框架，输入一句话的老板需求，输出用户故事 / 竞品分析 / 需求 / 数据结构 / APIs / 文件等|
|[llama-hub,shopify agent](https://github.com/run-llama/llama-hub/blob/main/llama_hub/tools/notebooks/shopify.ipynb)|![GitHub Repo stars](https://badgen.net/github/stars/run-llama/llama-hub)|A customer support agent 🤖 that can interface with @Shopify’s ENTIRE GraphQL API Spec (>50k lines!).| llama-hub 构建的客户支持 agent，能够与 @Shopify 的整个 GraphQL API规范(>5万行!)交互|
|[AGiXT (原 Agent-LLM)](https://github.com/Josh-XT/AGiXT)|![GitHub Repo stars](https://badgen.net/github/stars/Josh-XT/AGiXT)|An Artificial Intelligence Automation Platform. AI Instruction management from various providers, has an adaptive memory, and a versatile plugin system with many commands including web browsing.| 人工智能自动化平台 (项目已更名为 AGiXT)。https://agixt.com/|
|[skyagi](https://github.com/litanlitudan/skyagi)|![GitHub Repo stars](https://badgen.net/github/stars/litanlitudan/skyagi)|SkyAGI implements the idea of Generative Agents and delivers a role-playing game that creates a very interesting user experience.| SkyAGI 实现了 "生成式智能体 "的理念，设计了一个角色扮演游戏，创造了非常有趣的用户体验。|
|[generative_agents](https://github.com/joonspk-research/generative_agents)|![GitHub Repo stars](https://badgen.net/github/stars/joonspk-research/generative_agents)|Generative Agents: Interactive Simulacra of Human Behavior.| 斯坦福和谷歌的研究人员以《模拟人生》游戏为灵感，创建的 AI 智能体小镇；研究人员在模拟城镇中添加了 25 个生成式智能体 (Generative Agents)，这 25 个角色由 ChatGPT 和自定义代码控制，以高度逼真的行为独立地生活。在 ChatGPT 的支持下，每个人都有自己独特的身份、记忆和行为，并且可以独立交互，但他们都不会意识到自己是生活在模拟中。[中文介绍](https://www.oschina.net/news/253170/generative-agents-open-source)|
|[developer](https://github.com/smol-ai/developer)|![GitHub Repo stars](https://badgen.net/github/stars/smol-ai/developer)|the first library to let you embed a developer agent in your own app!| 工程师智能体，给它一个产品规格，为你搭建一个完整的代码库，提供基本的模块，让您在自己的应用程序内拥有一个智能开发人员。|
|[opencode](https://github.com/sst/opencode)|![GitHub Repo stars](https://badgen.net/github/stars/sst/opencode)|An AI coding agent built for the terminal.|SST 团队打造的终端编程 Agent，模型无关，支持多种 LLM 提供商，2025 年增长极快。|
|[Aider](https://github.com/Aider-AI/aider)|![GitHub Repo stars](https://badgen.net/github/stars/Aider-AI/aider)|AI pair programming in your terminal.|终端 AI 结对编程工具，直接在本地 Git 仓库中编辑代码并自动提交，是 CLI 编程 Agent 的代表作。|
|[goose](https://github.com/block/goose)|![GitHub Repo stars](https://badgen.net/github/stars/block/goose)|An open source, extensible AI agent that goes beyond code suggestions.|Block(Square 母公司)开源的本地可扩展 AI Agent，支持 MCP，可自动构建、执行和调试任务。|
|[DeerFlow](https://github.com/bytedance/deer-flow)|![GitHub Repo stars](https://badgen.net/github/stars/bytedance/deer-flow)|A community-driven Deep Research framework.|字节跳动开源的深度研究 Agent 框架，基于 LangGraph，结合搜索、爬取与代码执行完成自动化研究报告。|
|[Suna](https://github.com/kortix-ai/suna)|![GitHub Repo stars](https://badgen.net/github/stars/kortix-ai/suna)|Open source generalist AI agent.|开源通用型 AI Agent（对标 Manus），可自主浏览网页、执行命令、操作文件完成真实世界任务。|


## Agents 开发平台
|名称|Stars|简介|备注|
|---|---|---|---|
|[langchain](https://github.com/langchain-ai/langchain)|![GitHub Repo stars](https://badgen.net/github/stars/langchain-ai/langchain)|Building applications with LLMs through composability|开发的 ChatGPT 应用,构建基于 LLM 的 agents. 参见 [LangChain Agents 官方文档](https://docs.langchain.com/oss/python/langchain/agents) |
|[AutoChain](https://github.com/Forethought-Technologies/AutoChain)|![GitHub Repo stars](https://badgen.net/github/stars/Forethought-Technologies/AutoChain)|AutoChain: Build lightweight, extensible, and testable LLM Agents.| AutoChain:构建轻量级、可扩展和可测试的LLM agents。|
|[SuperAGI](https://github.com/TransformerOptimus/SuperAGI)|![GitHub Repo stars](https://badgen.net/github/stars/TransformerOptimus/SuperAGI)|<⚡️> SuperAGI - A dev-first open source autonomous AI agent framework. Enabling developers to build, manage & run useful autonomous agents quickly and reliably.|[官网](superagi.com/) 构建、管理和运行 AI Agents.|
|[superagent](https://github.com/superagent-ai/superagent)|![GitHub Repo stars](https://badgen.net/github/stars/superagent-ai/superagent)|Superagent - Build, deploy, and manage LLM-powered agents.|[官网](https://docs.superagent.sh/) 开发人员能更轻松地构建、管理和部署智能体到生产中，包括内置内存、通过向量数据库检索文档、强大的工具、网络钩子、cron 任务等功能.|
|[ai-town](https://github.com/a16z-infra/ai-town)|![GitHub Repo stars](https://badgen.net/github/stars/a16z-infra/ai-town)|A MIT-licensed, deployable starter kit for building and customizing your own version of AI town - a virtual town where AI characters live, chat and socialize.| 用于构建和定制你自己版本的人工智能小镇--一个人工智能角色生活、聊天和社交的虚拟小镇。|
|[agent-protocol](https://github.com/agi-inc/agent-protocol)|![GitHub Repo stars](https://badgen.net/github/stars/agi-inc/agent-protocol)|Common interface for interacting with AI agents. The protocol is tech stack agnostic - you can use it with any framework for building agents.|[官网](www.agentprotocol.ai) AutoGPT, smol developer 等知名项目都在使用的"智能体通讯协议"--用于与智能体进行通信的通用接口。|
|[autogen](https://github.com/microsoft/autogen)|![GitHub Repo stars](https://badgen.net/github/stars/microsoft/autogen)|AutoGen is a framework that enables development of LLM applications using multiple agents that can converse with each other to solve task.| AutoGen是一个框架，它允许使用多个 agents 来开发LLM应用程序，这些智能体可以相互交谈以解决任务。|
|[agents](https://github.com/aiwaves-cn/agents)|![GitHub Repo stars](https://badgen.net/github/stars/aiwaves-cn/agents)|An Open-source Framework for Autonomous Language Agents.| Agents 是一个用于构建自主语言智能体的开源库/框架。|
|[bisheng 毕昇](https://github.com/dataelement/bisheng)|![GitHub Repo stars](https://badgen.net/github/stars/dataelement/bisheng)|Bisheng is an open LLM devops platform for next generation AI applications. | 一款领先的开源大模型应用开发平台，赋能和加速大模型应用开发落地，帮助用户以最佳体验进入下一代应用开发模式。|
|[Agently](https://github.com/Maplemx/Agently)|![GitHub Repo stars](https://badgen.net/github/stars/Maplemx/Agently)|🚀 A fast way to build LLM Agent based Application. | 面向应用开发者：Agently提供方便快速生成能力强大的Agent实例的能力，让开发者可以便捷地将这些实例与自己的业务代码相结合。|
|[Dify](https://github.com/langgenius/dify)|![GitHub Repo stars](https://badgen.net/github/stars/langgenius/dify)|Production-ready platform for agentic workflow development.|生产级 LLM 应用与 Agent 工作流开发平台，提供可视化编排、RAG、工具调用与可观测性，社区规模巨大。|
|[Agno](https://github.com/agno-agi/agno)|![GitHub Repo stars](https://badgen.net/github/stars/agno-agi/agno)|Full-stack framework for building Multi-Agent Systems with memory, knowledge and reasoning.|原 Phidata，高性能全栈多 Agent 框架，内置记忆、知识、推理与工具，主打轻量与运行速度。|
|[Letta](https://github.com/letta-ai/letta)|![GitHub Repo stars](https://badgen.net/github/stars/letta-ai/letta)|Letta (formerly MemGPT) is a framework for creating stateful LLM agents.|原 MemGPT，专注于具备长期记忆的有状态 Agent，让智能体在跨会话中持续学习与保留上下文。|

## Curated List
|名称|Stars|简介|备注|
|---|---|---|---|
|[awesome-ai-agents](https://github.com/e2b-dev/awesome-ai-agents)|![GitHub Repo stars](https://badgen.net/github/stars/e2b-dev/awesome-ai-agents)|A list of AI autonomous agents. |基于 LLM 的 agents 精选资源.|
|[awesome-llm-apps](https://github.com/Shubhamsaboo/awesome-llm-apps)|![GitHub Repo stars](https://badgen.net/github/stars/Shubhamsaboo/awesome-llm-apps)|Collection of awesome LLM apps with AI Agents and RAG.|大量带 AI Agent 与 RAG 的实战应用示例合集，覆盖多种模型与框架，实操性强。|
|[awesome-mcp-servers](https://github.com/punkpeye/awesome-mcp-servers)|![GitHub Repo stars](https://badgen.net/github/stars/punkpeye/awesome-mcp-servers)|A collection of MCP servers.|MCP(Model Context Protocol)服务器精选合集，是为 Agent 接入外部工具/数据源的重要资源导航。|

## Star History

[![Star History Chart](https://star-history.dera.page/svg?repos=yzfly/Awesome-AGI-Agents&type=Date)](https://star-history.dera.page/#yzfly/Awesome-AGI-Agents&Date)

## License

本项目采用 [CC BY-NC 4.0](LICENSE) 协议授权 (署名-非商业性使用)。

---

作者：云中江树，微信公众号: 云中江树