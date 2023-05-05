# Awesome AGI Resources [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) 

A curated list of awesome AGI frameworks, software, and resources.

Mirrors:

[![GitHub repo](https://img.shields.io/badge/repo-AwesomeAGI-brightgreen.svg?logo=github)](https://github.com/yzfly/Awesome-AGI)
[![GitLab repo](https://img.shields.io/badge/repo-AwesomeAGI-orange.svg?logo=gitlab)](https://gitlab.com/awesomeai/Awesome-AGI)

Related Resources:  [ChatGPT 中文指南](https://github.com/yzfly/awesome-chatgpt-zh) 🔥

## What is AGI?
> Artificial General Intelligence (AGI) refers to advanced AI systems that exhibit human-like cognitive abilities across various tasks and domains. Unlike narrow AI, which excels in specific tasks, AGI aims to encompass learning, reasoning, problem-solving, perception, and natural language understanding. Although AGI remains an ambitious goal, its pursuit has led to numerous AI advancements. The development of AGI holds the potential to revolutionize industries such as healthcare, finance, transportation, and education, while also raising ethical, safety, and societal concerns that must be carefully addressed.

- [Awesome AGI Resources ](#awesome-agi-resources-)
  - [What is AGI?](#what-is-agi)
  - [Frameworks and Platforms](#frameworks-and-platforms)
  - [Papers, Courses and Lectures](#papers-courses-and-lectures)
    - [Papers](#papers)
    - [awesome-agi-cocosci](#awesome-agi-cocosci)
  - [Websites and Blogs](#websites-and-blogs)
    - [Online Demo (在线试用)](#online-demo-在线试用)
    - [Generative Agents](#generative-agents)
    - [The Marketplace for AI Agents](#the-marketplace-for-ai-agents)
  - [Tutorials and Guides](#tutorials-and-guides)


## Frameworks and Platforms

|Name|Stars|Introduction| Notes |
-|-|-|-
|[:fire: Auto-GPT](https://github.com/Significant-Gravitas/Auto-GPT) |![GitHub Repo stars](https://img.shields.io/github/stars/Significant-Gravitas/Auto-GPT?style=social)|An experimental open-source attempt to make GPT-4 fully autonomous.|-|
|[Auto-GPT-Plugins](https://github.com/Significant-Gravitas/Auto-GPT-Plugins) |![GitHub Repo stars](https://img.shields.io/github/stars/Significant-Gravitas/Auto-GPT-Plugins?style=social)|Plugins for Auto-GPT.|-|
|[AutoGPT.js](https://github.com/zabirauf/AutoGPT.js)|![GitHub Repo stars](https://img.shields.io/github/stars/zabirauf/AutoGPT.js?style=social)|Auto-GPT on the browser.|-|
|[AutoGPT-GUI](https://github.com/thecookingsenpai/autogpt-gui)|![GitHub Repo stars](https://img.shields.io/github/stars/thecookingsenpai/autogpt-gui?style=social)|A graphical user interface for AutoGPT.|AutoGPT 项目的图形界面|
|[:fire: AgentGPT](https://github.com/reworkd/AgentGPT) |![GitHub Repo stars](https://img.shields.io/github/stars/reworkd/AgentGPT?style=social)|Assemble, configure, and deploy autonomous AI Agents in your browser.|-|
|[:fire: JARVIS](https://github.com/microsoft/JARVIS)|![GitHub Repo stars](https://img.shields.io/github/stars/microsoft/JARVIS?style=social)|A system to connect LLMs with ML community.|-|
|[:fire: babyagi](https://github.com/yoheinakajima/babyagi)|![GitHub Repo stars](https://img.shields.io/github/stars/yoheinakajima/babyagi?style=social)|Use OpenAI and Pinecone APIs to create, prioritize, and execute tasks.|[中文博客-babyagi: 人工智能任务管理系统](https://juejin.cn/post/7218815501433946173)|
|[OpenAGI](https://github.com/agiresearch/OpenAGI) |![GitHub Repo stars](https://img.shields.io/github/stars/agiresearch/OpenAGI?style=social)|When LLM (Large Language Models) Meets Domain Experts.|-|
|[AI-legion](https://github.com/eumemic/ai-legion)|![GitHub Repo stars](https://img.shields.io/github/stars/eumemic/ai-legion?style=social)|An LLM-powered autonomous agent platform.|-|
|[MicroGPT](https://github.com/muellerberndt/micro-gpt)|![GitHub Repo stars](https://img.shields.io/github/stars/muellerberndt/micro-gpt?style=social)|A minimal generic autonomous agent based on GPT3.5/4. Can analyze stock prices, perform network security tests, create art, and order pizza.|-|
|[:fire: MiniGPT-4](https://github.com/Vision-CAIR/MiniGPT-4)|![GitHub Repo stars](https://img.shields.io/github/stars/Vision-CAIR/MiniGPT-4?style=social)|MiniGPT-4: Enhancing Vision-language Understanding with Advanced Large Language Models.|-|
|[Agent-LLM](https://github.com/Josh-XT/Agent-LLM)|![GitHub Repo stars](https://img.shields.io/github/stars/Josh-XT/Agent-LLM?style=social)|An Artificial Intelligence Automation Platform. AI Instruction management from various providers, has an adaptive memory, and a versatile plugin system with many commands including web browsing.| 人工智能自动化平台。https://agent-llm.com/|
|[loopgpt](https://github.com/farizrahman4u/loopgpt)|![GitHub Repo stars](https://img.shields.io/github/stars/farizrahman4u/loopgpt?style=social)|Modular Auto-GPT Framework.|模块化Auto-GPT框架.|
|[AutoGPT-Next-Web](https://github.com/Dogtiti/AutoGPT-Next-Web)|![GitHub Repo stars](https://img.shields.io/github/stars/Dogtiti/AutoGPT-Next-Web?style=social)|Assemble, configure, and deploy autonomous AI Agents in your browser.|一键免费部署你的私人AutoGPT 网页应用.|
|[Free-AUTO-GPT-with-NO-API](https://github.com/IntelligenzaArtificiale/Free-AUTO-GPT-with-NO-API)|![GitHub Repo stars](https://img.shields.io/github/stars/IntelligenzaArtificiale/Free-AUTO-GPT-with-NO-API?style=social)|Free AUTOGPT with NO API is a repository that offers a simple version of Autogpt, an autonomous AI agent capable of performing tasks independently. Unlike other versions, our implementation does not rely on any paid OpenAI API, making it accessible to anyone.|众所周知 AGI 项目调用 API 很花钱，这个项目让你免费运行AutoGPT, babyagi 等 AGI 项目！|

## Papers, Courses and Lectures

### Papers
- [Generative Agents: Interactive Simulacra of Human Behavior](https://arxiv.org/abs/2304.03442)
- [HuggingGPT: Solving AI Tasks with ChatGPT and its Friends in HuggingFace](https://arxiv.org/abs/2303.17580)
- [One Small Step for Generative AI, One Giant Leap for AGI: A Complete Survey on ChatGPT in AIGC Era](https://arxiv.org/abs/2304.06488)

### Blogs
- [Planning for AGI and beyond](https://openai.com/blog/planning-for-agi-and-beyond)- OpenAI discuss their short-term and long-term plans for achieving AGI.

### [awesome-agi-cocosci](https://github.com/YuzheSHI/awesome-agi-cocosci)

An awesome & curated list for Artificial General Intelligence, an emerging inter-discipline field that combines artificial intelligence and computational cognitive sciences.

## Websites and Blogs

### Online Demo (在线试用)
Easily try Auto-GPT online using the following websites:

* https://www.cognosys.ai/
* https://godmode.space/
* https://agentgpt.reworkd.ai/

### [Generative Agents](https://reverie.herokuapp.com/arXiv_Demo/)

Westworld lured millions of us into a fantasy of human-like robots in a Wild West-themed world.

Could it be real one day?

Stanford/Google researchers just told us how they used AI to make "generative agents".

* [Demo](https://reverie.herokuapp.com/arXiv_Demo/)
* [Paper](https://arxiv.org/abs/2304.03442)
* [Twitter](https://twitter.com/nonmayorpete/status/1645355224029356032?s=20)

![generative agents](imgs/gen_agents_diagram_1.jpg)

### [The Marketplace for AI Agents](https://www.dataleap.xyz/)

Discover Dataleap the Upwork for AI Agents, where AutoGPTs are revolutionizing the gig economy

![market](imgs/market_for_ai_agents.jpg)

## Tutorials and Guides