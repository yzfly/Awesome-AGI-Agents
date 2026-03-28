# Awesome-AGI-Agents

Agents (智能体) 精选资源合集，持续更新中

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


## 前沿项目
|名称|Stars|简介|备注|
|---|---|---|---|
|[:fire: Auto-GPT](https://github.com/Significant-Gravitas/Auto-GPT) |![GitHub Repo stars](https://badgen.net/github/stars/Significant-Gravitas/Auto-GPT)|An experimental open-source attempt to make GPT-4 fully autonomous.|大名鼎鼎的 AutoGPT 项目, AI Agents 的早期尝试之一|
|[:fire: gpt-engineer](https://github.com/AntonOsika/gpt-engineer)|![GitHub Repo stars](https://badgen.net/github/stars/AntonOsika/gpt-engineer)|Specify what you want it to build, the AI asks for clarification, and then builds it.|全栈开发 Agent，用 GPT 编写整个项目代码！|
|[:fire: AgentGPT](https://github.com/reworkd/AgentGPT) |![GitHub Repo stars](https://badgen.net/github/stars/reworkd/AgentGPT)|Assemble, configure, and deploy autonomous AI Agents in your browser.|在浏览器中部署运行 AI Agents.|
|[:fire: MetaGPT](https://github.com/geekan/MetaGPT) |![GitHub Repo stars](https://badgen.net/github/stars/geekan/MetaGPT)|🌟 The Multi-Agent Framework: Given one line Requirement, return PRD, Design, Tasks, Repo. |MetaGPT, 多智能体框架，输入一句话的老板需求，输出用户故事 / 竞品分析 / 需求 / 数据结构 / APIs / 文件等|
|[llama-hub,shopify agent](https://github.com/emptycrown/llama-hub/blob/main/llama_hub/tools/notebooks/shopify.ipynb)|![GitHub Repo stars](https://badgen.net/github/stars/emptycrown/llama-hub)|A customer support agent 🤖 that can interface with @Shopify’s ENTIRE GraphQL API Spec (>50k lines!).| llama-hub 构建的客户支持 agent，能够与 @Shopify 的整个 GraphQL API规范(>5万行!)交互|
|[Agent-LLM](https://github.com/Josh-XT/Agent-LLM)|![GitHub Repo stars](https://badgen.net/github/stars/Josh-XT/Agent-LLM)|An Artificial Intelligence Automation Platform. AI Instruction management from various providers, has an adaptive memory, and a versatile plugin system with many commands including web browsing.| 人工智能自动化平台。https://agent-llm.com/|
|[skyagi](https://github.com/litanlitudan/skyagi)|![GitHub Repo stars](https://badgen.net/github/stars/litanlitudan/skyagi)|SkyAGI implements the idea of Generative Agents and delivers a role-playing game that creates a very interesting user experience.| SkyAGI 实现了 "生成式智能体 "的理念，设计了一个角色扮演游戏，创造了非常有趣的用户体验。|
|[generative_agents](https://github.com/joonspk-research/generative_agents)|![GitHub Repo stars](https://badgen.net/github/stars/joonspk-research/generative_agents)|Generative Agents: Interactive Simulacra of Human Behavior.| 斯坦福和谷歌的研究人员以《模拟人生》游戏为灵感，创建的 AI 智能体小镇；研究人员在模拟城镇中添加了 25 个生成式智能体 (Generative Agents)，这 25 个角色由 ChatGPT 和自定义代码控制，以高度逼真的行为独立地生活。在 ChatGPT 的支持下，每个人都有自己独特的身份、记忆和行为，并且可以独立交互，但他们都不会意识到自己是生活在模拟中。[中文介绍](https://www.oschina.net/news/253170/generative-agents-open-source)|
|[developer](https://github.com/smol-ai/developer)|![GitHub Repo stars](https://badgen.net/github/stars/smol-ai/developer)|the first library to let you embed a developer agent in your own app!| 工程师智能体，给它一个产品规格，为你搭建一个完整的代码库，提供基本的模块，让您在自己的应用程序内拥有一个智能开发人员。|
|[Bernstein](https://github.com/chernistry/bernstein)|![GitHub Repo stars](https://badgen.net/github/stars/chernistry/bernstein)|Deterministic multi-agent orchestrator — spawns parallel AI coding agents (Claude Code, Codex CLI, Gemini CLI), verifies with tests, auto-commits.|确定性多智能体编排器，并行启动多个 AI 编码智能体（Claude Code、Codex CLI、Gemini CLI），通过测试验证，自动提交代码。|


## Agents 开发平台
|名称|Stars|简介|备注|
|---|---|---|---|
|[langchain](https://github.com/hwchase17/langchain)|![GitHub Repo stars](https://badgen.net/github/stars/hwchase17/langchain)|Building applications with LLMs through composability|开发的 ChatGPT 应用,构建基于 LLM 的 agents. [CSV Agent](https://python.langchain.com/en/latest/modules/agents/toolkits/examples/csv.html) [JSON Agent](https://python.langchain.com/en/latest/modules/agents/toolkits/examples/json.html), [OpenAPI Agent](https://python.langchain.com/en/latest/modules/agents/toolkits/examples/openapi.html), [Pandas Dataframe Agent](https://python.langchain.com/en/latest/modules/agents/toolkits/examples/pandas.html), [Python Agent](https://python.langchain.com/en/latest/modules/agents/toolkits/examples/python.html), [SQL Database Agent](https://python.langchain.com/en/latest/modules/agents/toolkits/examples/sql_database.html), [Vectorstore Agent](https://python.langchain.com/en/latest/modules/agents/toolkits/examples/vectorstore.html) |
|[AutoChain](https://github.com/Forethought-Technologies/AutoChain)|![GitHub Repo stars](https://badgen.net/github/stars/Forethought-Technologies/AutoChain)|AutoChain: Build lightweight, extensible, and testable LLM Agents.| AutoChain:构建轻量级、可扩展和可测试的LLM agents。|
|[SuperAGI](https://github.com/TransformerOptimus/SuperAGI)|![GitHub Repo stars](https://badgen.net/github/stars/TransformerOptimus/SuperAGI)|<⚡️> SuperAGI - A dev-first open source autonomous AI agent framework. Enabling developers to build, manage & run useful autonomous agents quickly and reliably.|[官网](superagi.com/) 构建、管理和运行 AI Agents.|
|[superagent](https://github.com/homanp/superagent)|![GitHub Repo stars](https://badgen.net/github/stars/homanp/superagent)|Superagent - Build, deploy, and manage LLM-powered agents.|[官网](https://docs.superagent.sh/) 开发人员能更轻松地构建、管理和部署智能体到生产中，包括内置内存、通过向量数据库检索文档、强大的工具、网络钩子、cron 任务等功能.|
|[ai-town](https://github.com/a16z-infra/ai-town)|![GitHub Repo stars](https://badgen.net/github/stars/a16z-infra/ai-town)|A MIT-licensed, deployable starter kit for building and customizing your own version of AI town - a virtual town where AI characters live, chat and socialize.| 用于构建和定制你自己版本的人工智能小镇--一个人工智能角色生活、聊天和社交的虚拟小镇。|
|[agent-protocol](https://github.com/e2b-dev/agent-protocol)|![GitHub Repo stars](https://badgen.net/github/stars/e2b-dev/agent-protocol)|Common interface for interacting with AI agents. The protocol is tech stack agnostic - you can use it with any framework for building agents.|[官网](www.agentprotocol.ai) AutoGPT, smol developer 等知名项目都在使用的"智能体通讯协议"--用于与智能体进行通信的通用接口。|
|[autogen](https://github.com/microsoft/autogen)|![GitHub Repo stars](https://badgen.net/github/stars/microsoft/autogen)|AutoGen is a framework that enables development of LLM applications using multiple agents that can converse with each other to solve task.| AutoGen是一个框架，它允许使用多个 agents 来开发LLM应用程序，这些智能体可以相互交谈以解决任务。|
|[agents](https://github.com/aiwaves-cn/agents)|![GitHub Repo stars](https://badgen.net/github/stars/aiwaves-cn/agents)|An Open-source Framework for Autonomous Language Agents.| Agents 是一个用于构建自主语言智能体的开源库/框架。|
|[bisheng 毕昇](https://github.com/dataelement/bisheng)|![GitHub Repo stars](https://badgen.net/github/stars/dataelement/bisheng)|Bisheng is an open LLM devops platform for next generation AI applications. | 一款领先的开源大模型应用开发平台，赋能和加速大模型应用开发落地，帮助用户以最佳体验进入下一代应用开发模式。|
|[Agently](https://github.com/Maplemx/Agently)|![GitHub Repo stars](https://badgen.net/github/stars/Maplemx/Agently)|🚀 A fast way to build LLM Agent based Application. | 面向应用开发者：Agently提供方便快速生成能力强大的Agent实例的能力，让开发者可以便捷地将这些实例与自己的业务代码相结合。|

## Curated List
|名称|Stars|简介|备注|
|---|---|---|---|
|[awesome-ai-agents](https://github.com/e2b-dev/awesome-ai-agents)|![GitHub Repo stars](https://badgen.net/github/stars/e2b-dev/awesome-ai-agents)|A list of AI autonomous agents. |基于 LLM 的 agents 精选资源.|

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=yzfly/Awesome-AGI-Agents&type=Date)](https://star-history.com/#yzfly/Awesome-AGI-Agents&Date)