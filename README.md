# Awesome-AGI-Agents

Agents (智能体) 精选资源合集，持续更新中

## 文章和视频

|名称|简介|备注|
|---|---|---|
|[AI Agents大爆发：软件2.0雏形初现，OpenAI的下一步](https://mp.weixin.qq.com/s/Jb8HBbaKYXXxTSQOBsP5Wg)|Lilian Weng 的个人博客文章，Lilian 现在是 OpenAI 的 Head of Safety Systems，之前还领导过 OpenAI 的 Applied AI 团队。AI Agent 被认为是 OpenAI 发力的下一个方向。OpenAI 的联合创始人 Andrej Karpathy 在近期的一次公开活动上提到“相比模型训练方法，OpenAI 内部目前更关注 Agent 领域的变化，每当有新的 AI Agents 论文出来的时候，内部都会很兴奋并且认真地讨论”，而在更早之前，Andrej  还评价 AutoGPT 是 Prompt Engineering 下一阶段的探索方向。|[英文原文](https://lilianweng.github.io/posts/2023-06-23-agent/)|
|[LangChain Agents - Joining Tools and Chains with Decisions](https://www.youtube.com/watch?v=ziu87EXZVUE&ab_channel=SamWitteveen)|LangChain Agents--将工具和任务链与决策结合起来|英文 Youtube 视频，LangChain 项目官方对预置的 agents 介绍。|

## 论文
|名称|简介|备注|
|---|---|---|
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


## Agents 开发平台
|名称|Stars|简介|备注|
|---|---|---|---|
|[langchain](https://github.com/hwchase17/langchain)|![GitHub Repo stars](https://badgen.net/github/stars/hwchase17/langchain)|Building applications with LLMs through composability|开发的 ChatGPT 应用,构建基于 LLM 的 agents. [CSV Agent](https://python.langchain.com/en/latest/modules/agents/toolkits/examples/csv.html) [JSON Agent](https://python.langchain.com/en/latest/modules/agents/toolkits/examples/json.html), [OpenAPI Agent](https://python.langchain.com/en/latest/modules/agents/toolkits/examples/openapi.html), [Pandas Dataframe Agent](https://python.langchain.com/en/latest/modules/agents/toolkits/examples/pandas.html), [Python Agent](https://python.langchain.com/en/latest/modules/agents/toolkits/examples/python.html), [SQL Database Agent](https://python.langchain.com/en/latest/modules/agents/toolkits/examples/sql_database.html), [Vectorstore Agent](https://python.langchain.com/en/latest/modules/agents/toolkits/examples/vectorstore.html) |
|[AutoChain](https://github.com/Forethought-Technologies/AutoChain)|![GitHub Repo stars](https://badgen.net/github/stars/Forethought-Technologies/AutoChain)|AutoChain: Build lightweight, extensible, and testable LLM Agents.| AutoChain:构建轻量级、可扩展和可测试的LLM agents。|
|[SuperAGI](https://github.com/TransformerOptimus/SuperAGI)|![GitHub Repo stars](https://badgen.net/github/stars/TransformerOptimus/SuperAGI)|<⚡️> SuperAGI - A dev-first open source autonomous AI agent framework. Enabling developers to build, manage & run useful autonomous agents quickly and reliably.|[官网](superagi.com/) 构建、管理和运行 AI Agents.|