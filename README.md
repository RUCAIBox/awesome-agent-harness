# Agent Systems with Harness Engineering: A Systematic Survey

<p align="center">
  <strong>A Curated Reading List and Structured Roadmap</strong>
</p>

<p align="center">
  <a href="#"><img src="https://img.shields.io/badge/Status-Building-2ea44f" alt="status"></a>
  <a href="#"><img src="https://img.shields.io/badge/Papers-475-blue" alt="papers"></a>
  <a href="#"><img src="https://img.shields.io/badge/Last%20Update-2026--05--13-orange" alt="last-update"></a>
  <a href="./LICENSE"><img src="https://img.shields.io/badge/License-MIT-lightgrey" alt="license"></a>
</p>

A curated collection of papers and resources related to **Agent Systems with Harness Engineering: A Systematic Survey**.
The organization of this repository refers to our survey [<u>"Agent Systems with Harness Engineering: A Systematic Survey"</u>](#8-citation).

## Table of Contents

- [1. Introduction](#1-introduction)
- [2. Foundations of Harness Engineering](#2-foundations-of-harness-engineering)
- [3. The Design of the Harness](#3-the-design-of-the-harness)
- [4. Model Adaptation for Harness](#4-model-adaptation-for-harness)
- [5. Harness Capacity and Evaluation](#5-harness-capacity-and-evaluation)
- [6. Future Directions](#6-future-directions)
- [7. Representative Benchmarks by Task Domain](#7-representative-benchmarks-by-task-domain)
- [8. Citation](#8-citation)

## How to Use This Repo

- Browse by section: the list follows the current survey manuscript order.
- Entries are generated from active LaTeX citations and the active benchmark summary table, not from every BibTeX entry.
- Each entry includes a required `[[Paper]]` link when available from the manuscript BibTeX, the previous README, or a paper URL in the table.
- `[[Code]]` links are included only when they are inherited from the previous README or clearly correspond to the benchmark/project URL in the paper table.

## 1. Introduction
1. A Survey of Large Language Models. [[Paper]](https://doi.org/10.48550/arXiv.2303.18223) `arXiv 2023`
1. A Survey of Large Language Model Empowered Agents for Recommendation and Search: Towards Next-Generation Information Retrieval. [[Paper]](https://doi.org/10.48550/arXiv.2503.05659) `arXiv 2025`
1. A Survey on Code Generation with LLM-based Agents. [[Paper]](https://doi.org/10.48550/arXiv.2508.00083) `arXiv 2025`
1. From Automation to Autonomy: A Survey on Large Language Models in Scientific Discovery. [[Paper]](https://doi.org/10.18653/v1/2025.emnlp-main.895) `ACL 2025`
1. Language Models are Few-Shot Learners. `NeurIPS 2020`
1. Pre-Trained Language Models for Text Generation: A Survey. [[Paper]](https://doi.org/10.1145/3649449) `CSUR 2024`
1. Qwen3 Technical Report. [[Paper]](https://arxiv.org/abs/2505.09388) `arXiv 2025`
1. Chain-of-Thought Prompting Elicits Reasoning in Large Language Models. [[Paper]](https://arxiv.org/pdf/2201.11903.pdf) [[Code]](https://github.com/google-research/url-nlp/tree/main/mgsm) `NeurIPS 2022`
1. Toolformer: Language Models Can Teach Themselves to Use Tools. [[Paper]](https://arxiv.org/pdf/2302.04761.pdf) `NeurIPS 2023`
1. A Survey of Context Engineering for Large Language Models. [[Paper]](https://arxiv.org/abs/2507.13334) `arXiv 2025`
1. ReAct: Synergizing Reasoning and Acting in Language Models. [[Paper]](https://arxiv.org/pdf/2210.03629.pdf) [[Code]](https://github.com/ysymyth/ReAct) `ICLR 2023`
1. OpenHands: An Open Platform for AI Software Developers as Generalist Agents. [[Paper]](https://openreview.net/forum?id=OJd3ayDDoF) `ICLR 2025`
1. SWE-agent: Agent-Computer Interfaces Enable Automated Software Engineering. [[Paper]](https://arxiv.org/pdf/2405.15793.pdf) [[Code]](https://github.com/princeton-nlp/SWE-agent) `NeurIPS 2024`
1. Claude Code Overview. `2026`
1. Large Language Model Agent: A Survey on Methodology, Applications and Challenges. [[Paper]](https://doi.org/10.48550/arXiv.2503.21460) `arXiv 2025`
1. A Survey on the Feedback Mechanism of LLM-based AI Agents. [[Paper]](https://doi.org/10.24963/ijcai.2025/1175) `IJCAI 2025`
1. Agentic Large Language Models, a Survey. [[Paper]](https://doi.org/10.1613/jair.1.18675) `JAIR 2025`
1. The Orchestration of Multi-Agent Systems: Architectures, Protocols, and Enterprise Adoption. [[Paper]](https://doi.org/10.48550/arXiv.2601.13671) `arXiv 2026`
1. Agentic AI: a comprehensive survey of architectures, applications, and future directions. `AIR 2025`
1. Evaluation and Benchmarking of LLM Agents: A Survey. [[Paper]](https://doi.org/10.1145/3711896.3736570) `KDD 2025`
1. From Static Templates to Dynamic Runtime Graphs: A Survey of Workflow Optimization for LLM Agents. [[Paper]](https://arxiv.org/abs/2603.22386) `2026`
1. A Survey on Trustworthy LLM Agents: Threats and Countermeasures. [[Paper]](https://doi.org/10.1145/3711896.3736561) `KDD 2025`
1. AutoAgents: A Framework for Automatic Agent Generation. [[Paper]](https://arxiv.org/pdf/2309.17288) [[Code]](https://github.com/Link-AGI/AutoAgents) `IJCAI 2024`
1. GAP: Graph-Based Agent Planning with Parallel Tool Use and Reinforcement Learning. [[Paper]](https://openreview.net/pdf?id=7bJIVHEvLm) [[Code]](https://github.com/WJQ7777/Graph-Agent-Planning) `arXiv 2025`
1. Reflexion: language agents with verbal reinforcement learning. [[Paper]](https://arxiv.org/abs/2303.11366) [[Code]](https://github.com/noahshinn/reflexion) `NeurIPS 2023`
1. ToolHop: A Query-Driven Benchmark for Evaluating Large Language Models in Multi-Hop Tool Use. [[Paper]](https://aclanthology.org/2025.acl-long.150/) `ACL 2025`
1. ToolRL: Reward is All Tool Learning Needs. [[Paper]](https://arxiv.org/abs/2504.13958) `arXiv 2025`
1. Memo: Training Memory-Efficient Embodied Agents with Reinforcement Learning. [[Paper]](https://arxiv.org/pdf/2510.19732.pdf) [[Code]](https://github.com/gunshi/memo) `NeurIPS 2025`
1. Memory OS of AI Agent. [[Paper]](https://aclanthology.org/2025.emnlp-main.1318.pdf) [[Code]](https://github.com/BAI-LAB/MemoryOS) `ACL 2025`
1. Mem0: Building Production-Ready AI Agents with Scalable Long-Term Memory. [[Paper]](https://arxiv.org/pdf/2504.19413) [[Code]](https://mem0.ai/research) `ECAI 2025`
1. MemoryBank: Enhancing Large Language Models with Long-Term Memory. [[Paper]](https://arxiv.org/pdf/2305.10250.pdf) [[Code]](https://github.com/zhongwanjun/MemoryBank-SiliconFriend) `AAAI 2024`
1. A-Mem: Agentic Memory for LLM Agents. [[Paper]](https://arxiv.org/pdf/2502.12110) [[Code]](https://github.com/WujiangXu/A-mem) `NeurIPS 2025`
1. AgentSys: Secure and Dynamic LLM Agents Through Explicit Hierarchical Memory Management. [[Paper]](https://arxiv.org/abs/2602.07398) `arXiv 2026`
1. SkillRL: Evolving Agents via Recursive Skill-Augmented Reinforcement Learning. [[Paper]](https://arxiv.org/pdf/2602.08234.pdf) [[Code]](https://github.com/aiming-lab/SkillRL) `arXiv 2026`
1. Trace2Skill: Distill Trajectory-Local Lessons into Transferable Agent Skills. [[Paper]](https://arxiv.org/abs/2603.25158) `arXiv 2026`
1. SoK: Agentic Skills - Beyond Tool Use in LLM Agents. [[Paper]](https://doi.org/10.48550/arXiv.2602.20867) `arXiv 2026`
1. SEAgent: Self-Evolving Computer Use Agent with Autonomous Learning from Experience. [[Paper]](https://arxiv.org/pdf/2508.04700.pdf) [[Code]](https://github.com/SunzeY/SEAgent) `arXiv 2025`
1. ToolGen: Unified Tool Retrieval and Calling via Generation. [[Paper]](https://arxiv.org/pdf/2410.03439.pdf) [[Code]](https://github.com/Reason-Wang/ToolGen) `ICLR 2025`
1. AutoGen: Enabling Next-Gen LLM Applications via Multi-Agent Conversations. [[Paper]](https://openreview.net/pdf?id=BAakY1hNKS) [[Code]](https://github.com/microsoft/autogen) `COLM 2024`
1. MetaGPT: Meta Programming for A Multi-Agent Collaborative Framework. [[Paper]](https://openreview.net/pdf?id=VtmBAGCN7o) [[Code]](https://github.com/geekan/MetaGPT) `ICLR 2024`
1. ChatDev: Communicative Agents for Software Development. [[Paper]](https://aclanthology.org/2024.acl-long.810.pdf) [[Code]](https://github.com/OpenBMB/ChatDev) `ACL 2024`
1. AgentVerse: Facilitating Multi-Agent Collaboration and Exploring Emergent Behaviors in Agents. [[Paper]](https://openreview.net/pdf?id=EHg5GDnyq1) [[Code]](https://github.com/OpenBMB/AgentVerse) `arXiv 2023`
1. AgentOrchestra: Orchestrating Multi-Agent Intelligence with the Tool-Environment-Agent(TEA) Protocol. [[Paper]](https://doi.org/10.48550/arXiv.2506.12508) `arXiv 2025`
1. StructRAG: Boosting Knowledge Intensive Reasoning of LLMs via Inference-time Hybrid Information Structurization. `ICLR 2025`
1. Deeprag: Thinking to retrieve step by step for large language models. [[Paper]](https://arxiv.org/pdf/2502.01142.pdf) [[Code]](https://github.com/gxy-gxy/DeepRAG) `arXiv 2025`
1. CoSER: A Comprehensive Literary Dataset and Framework for Training and Evaluating LLM Role-Playing and Persona Simulation. [[Paper]](https://arxiv.org/pdf/2502.09082) [[Code]](https://github.com/Neph0s/CoSER) `ICML 2025`
1. Reducing Cost of LLM Agents with Trajectory Reduction. [[Paper]](https://arxiv.org/abs/2509.23586) `arXiv 2025`
1. DeepSeek-R1: Incentivizing Reasoning Capability in LLMs via Reinforcement Learning. [[Paper]](https://arxiv.org/abs/2501.12948) [[Code]](https://github.com/deepseek-ai/DeepSeek-R1) `arXiv 2025`
1. HybridFlow: A Flexible and Efficient RLHF Framework. [[Paper]](https://arxiv.org/abs/2409.19256) [[Code]](https://github.com/volcengine/verl) `EuroSys 2025`
1. DAPO: An Open-Source LLM Reinforcement Learning System at Scale. [[Paper]](https://arxiv.org/abs/2503.14476) [[Code]](https://github.com/BytedTsinghua-SIA/DAPO) `arXiv 2025`
1. Search-R1: Training LLMs to Reason and Leverage Search Engines with Reinforcement Learning. [[Paper]](https://arxiv.org/abs/2503.09516) `arXiv 2025`
1. RAGEN: Understanding Self-Evolution in LLM Agents via Multi-Turn Reinforcement Learning. [[Paper]](https://arxiv.org/abs/2504.20073) [[Code]](https://github.com/RAGEN-AI/RAGEN) `arXiv 2025`
1. BrowseComp: A Simple Yet Challenging Benchmark for Browsing Agents. [[Paper]](https://doi.org/10.48550/arXiv.2504.12516) `arXiv 2025`
1. Characterizing Deep Research: A Benchmark and Formal Definition. [[Paper]](https://arxiv.org/pdf/2508.04183) [[Code]](https://github.com/microsoft/LiveDRBench) `arXiv 2025`
1. WideSearch: Benchmarking Agentic Broad Info-Seeking. [[Paper]](https://doi.org/10.48550/arXiv.2508.07999) `arXiv 2025`
1. DeepResearch Bench: A Comprehensive Benchmark for Deep Research Agents. [[Paper]](https://arxiv.org/pdf/2506.11763) [[Code]](https://github.com/Ayanami0730/deep_research_bench) `arXiv 2025`
1. Can Language Models Replace Programmers for Coding? REPOCOD Says 'Not Yet'. [[Paper]](https://aclanthology.org/2025.acl-long.1204/) `ACL 2025`
1. SWE-Bench Pro: Can AI Agents Solve Long-Horizon Software Engineering Tasks?. [[Paper]](https://doi.org/10.48550/arXiv.2509.16941) `arXiv 2025`
1. SWE-Bench++: A Framework for the Scalable Generation of Software Engineering Benchmarks from Open-Source Repositories. [[Paper]](https://doi.org/10.48550/arXiv.2512.17419) `arXiv 2025`
1. OmniCode: A Benchmark for Evaluating Software Engineering Agents. [[Paper]](https://doi.org/10.48550/arXiv.2602.02262) `arXiv 2026`
1. LiveCodeBench: Holistic and Contamination Free Evaluation of Large Language Models for Code. [[Paper]](https://arxiv.org/pdf/2403.07974) [[Code]](https://github.com/LiveCodeBench/LiveCodeBench) `ICLR 2025`
1. The Berkeley Function Calling Leaderboard (BFCL): From Tool Use to Agentic Evaluation of Large Language Models. [[Paper]](https://openreview.net/pdf?id=2GmDdhBdDk) [[Code]](https://github.com/ShishirPatil/gorilla/tree/main/berkeley-function-call-leaderboard) `ICML 2025`
1. DICE-BENCH: Evaluating the Tool-Use Capabilities of Large Language Models in Multi-Round, Multi-Party Dialogues. [[Paper]](https://aclanthology.org/2025.findings-acl.1375/) `ACL Findings 2025`
1. Toolsandbox: A stateful, conversational, interactive evaluation benchmark for llm tool use capabilities. [[Paper]](https://arxiv.org/pdf/2408.04682) [[Code]](https://github.com/apple/ToolSandbox) `ACL Findings 2025`
1. tau^2-Bench: Evaluating Conversational Agents in a Dual-Control Environment. [[Paper]](https://arxiv.org/pdf/2506.07982) [[Code]](https://github.com/sierra-research/tau2-bench) `arXiv 2025`
1. Gaia-2: A controllable multi-view generative world model for autonomous driving. [[Paper]](https://arxiv.org/abs/2503.20523) `arXiv 2025`
1. WorldGUI: An Interactive Benchmark for Desktop GUI Automation from Any Starting Point. [[Paper]](https://doi.org/10.48550/arXiv.2502.08047) `arXiv 2025`
1. MMBench-GUI: Hierarchical Multi-Platform Evaluation Framework for GUI Agents. [[Paper]](https://doi.org/10.48550/arXiv.2507.19478) `arXiv 2025`
1. AndroidWorld: A Dynamic Benchmarking Environment for Autonomous Agents. [[Paper]](https://arxiv.org/pdf/2405.14573) [[Code]](https://github.com/google-research/android_world) `ICLR 2025`
1. Osworld-mcp: Benchmarking mcp tool invocation in computer-use agents. [[Paper]](https://arxiv.org/pdf/2510.24563) [[Code]](https://github.com/X-PLUG/OSWorld-MCP) `arXiv 2025`
1. ResearchBench: Benchmarking LLMs in Scientific Discovery via Inspiration-Based Task Decomposition. [[Paper]](https://doi.org/10.48550/arXiv.2503.21248) `arXiv 2025`
1. ScienceAgentBench: Toward Rigorous Assessment of Language Agents for Data-Driven Scientific Discovery. [[Paper]](https://arxiv.org/pdf/2410.05080) [[Code]](https://github.com/OSU-NLP-Group/ScienceAgentBench) `ICLR 2025`
1. MLE-bench: Evaluating Machine Learning Agents on Machine Learning Engineering. [[Paper]](https://arxiv.org/pdf/2410.07095) [[Code]](https://github.com/openai/mle-bench) `ICLR 2025`
1. PaperBench: Evaluating AI's Ability to Replicate AI Research. [[Paper]](https://arxiv.org/pdf/2504.01848) [[Code]](https://github.com/openai/preparedness) `ICML 2025`

## 2. Foundations of Harness Engineering
1. OpenHands: An Open Platform for AI Software Developers as Generalist Agents. [[Paper]](https://openreview.net/forum?id=OJd3ayDDoF) `ICLR 2025`
1. AI runtime infrastructure. [[Paper]](https://arxiv.org/abs/2603.00495) `arXiv 2026`
1. The OpenHands Software Agent SDK: A Composable and Extensible Foundation for Production Agents. [[Paper]](https://doi.org/10.48550/arXiv.2511.03690) `arXiv 2025`
1. Beyond Context Sharing: A Unified Agent Communication Protocol (ACP) for Secure, Federated, and Autonomous Agent-to-Agent (A2A) Orchestration. [[Paper]](https://arxiv.org/abs/2602.15055) `arXiv 2026`

### 2.1. The Concept of Harness Engineering
##### 2.1.1. Perspective I: Harness Engineering as Structural Decomposition
##### 2.1.2. Perspective II: Harness Engineering as Framework Construction
##### 2.1.3. Perspective III: Harness Engineering as Synergistic System Optimization
### 2.2. Developmental Phases of Harness Engineering
#### 2.2.1. Action Interface: Connecting Model to Environment
1. Quine: Realizing LLM Agents as Native POSIX Processes. [[Paper]](https://arxiv.org/abs/2603.18030) `arXiv 2026`
1. ceLLMate: Sandboxing Browser AI Agents. [[Paper]](https://doi.org/10.48550/arXiv.2512.12594) `arXiv 2025`
1. Executable Code Actions Elicit Better LLM Agents. [[Paper]](https://proceedings.mlr.press/v235/wang24h.html) `ICML 2024`
1. DeepAgent: A General Reasoning Agent with Scalable Toolsets. [[Paper]](https://doi.org/10.48550/arXiv.2510.21618) `arXiv 2025`
1. ReAct: Synergizing Reasoning and Acting in Language Models. [[Paper]](https://arxiv.org/pdf/2210.03629.pdf) [[Code]](https://github.com/ysymyth/ReAct) `ICLR 2023`
1. Toolformer: Language Models Can Teach Themselves to Use Tools. [[Paper]](https://arxiv.org/pdf/2302.04761.pdf) `NeurIPS 2023`
1. Tool learning with large language models: a survey. [[Paper]](https://doi.org/10.1007/s11704-024-40678-2) `FCS 2025`
1. AIOS: LLM Agent Operating System. `Second Conference on Language Mode 2025`
#### 2.2.2. Workflow Infrastructure: Orchestrating Persistent Workspaces
1. SWE-agent: Agent-Computer Interfaces Enable Automated Software Engineering. [[Paper]](https://arxiv.org/pdf/2405.15793.pdf) [[Code]](https://github.com/princeton-nlp/SWE-agent) `NeurIPS 2024`
1. Engineering Pitfalls in AI Coding Tools: An Empirical Study of Bugs in Claude Code, Codex, and Gemini CLI. [[Paper]](https://arxiv.org/abs/2603.20847) `2026`
1. Building Effective AI Coding Agents for the Terminal: Scaffolding, Harness, Context Engineering, and Lessons Learned. [[Paper]](https://doi.org/10.48550/arXiv.2603.05344) `arXiv 2026`
1. SWE-Master: Unleashing the Potential of Software Engineering Agents via Post-Training. [[Paper]](https://arxiv.org/abs/2602.03411) `arXiv 2026`
1. VeRO: An Evaluation Harness for Agents to Optimize Agents. [[Paper]](https://arxiv.org/abs/2602.22480) `arXiv 2026`
1. OpenHands: An Open Platform for AI Software Developers as Generalist Agents. [[Paper]](https://openreview.net/forum?id=OJd3ayDDoF) `ICLR 2025`
1. Claude Code Overview. `2026`
#### 2.2.3. Persistence Architecture: Sustaining User-Centric Continuity
1. Toward Personalized LLM-Powered Agents: Foundations, Evaluation, and Future Directions. [[Paper]](https://arxiv.org/abs/2602.22680) `arXiv 2026`
1. Enabling Personalized Long-term Interactions in LLM-based Agents through Persistent Memory and User Profiles. [[Paper]](https://doi.org/10.48550/arXiv.2510.07925) `arXiv 2025`
1. User Preference Modeling for Conversational LLM Agents: Weak Rewards from Retrieval-Augmented Interaction. [[Paper]](https://arxiv.org/abs/2603.20939) `arXiv 2026`
1. From Human Memory to AI Memory: A Survey on Memory Mechanisms in the Era of LLMs. [[Paper]](https://doi.org/10.48550/arXiv.2504.15965) `arXiv 2025`
1. Persistent Assistant: Seamless Everyday AI Interactions via Intent Grounding and Multimodal Feedback. [[Paper]](https://doi.org/10.1145/3706598.3714317) `CHI 2025`
1. Introducing OpenClaw. `2026`
### 2.3. Connections with Related Concepts
##### 2.3.1. Agent Framework
1. The OpenHands Software Agent SDK: A Composable and Extensible Foundation for Production Agents. [[Paper]](https://doi.org/10.48550/arXiv.2511.03690) `arXiv 2025`
1. AIOS: LLM Agent Operating System. `Second Conference on Language Mode 2025`
##### 2.3.2. Other Related Concepts
1. Chain-of-Thought Prompting Elicits Reasoning in Large Language Models. [[Paper]](https://arxiv.org/pdf/2201.11903.pdf) [[Code]](https://github.com/google-research/url-nlp/tree/main/mgsm) `NeurIPS 2022`
1. Plan-and-Solve Prompting: Improving Zero-Shot Chain-of-Thought Reasoning by Large Language Models. [[Paper]](https://doi.org/10.18653/v1/2023.acl-long.147) `ACL 2023`
1. Unleashing the potential of prompt engineering for large language models. [[Paper]](https://doi.org/10.1016/j.patter.2025.101260) `Patterns 2025`
1. Tool learning with language models: a comprehensive survey of methods, pipelines, and benchmarks. `Vicinagearth 2025`
1. The Evolution of Tool Use in LLM Agents: From Single-Tool Call to Multi-Tool Orchestration. [[Paper]](https://arxiv.org/abs/2603.22862) `2026`
1. OpenHands: An Open Platform for AI Software Developers as Generalist Agents. [[Paper]](https://openreview.net/forum?id=OJd3ayDDoF) `ICLR 2025`
1. Toward Personalized LLM-Powered Agents: Foundations, Evaluation, and Future Directions. [[Paper]](https://arxiv.org/abs/2602.22680) `arXiv 2026`

## 3. The Design of the Harness
### 3.1. Agent Workflow
1. Unrolling the Codex agent loop. [[Paper]](https://openai.com/zh-Hans-CN/index/unrolling-the-codex-agent-loop/) `2026`

#### 3.1.1. Environment Perception
##### 3.1.1.1. Observation Extraction
1. WebVoyager: Building an End-to-End Web Agent with Large Multimodal Models. [[Paper]](https://arxiv.org/pdf/2401.13919.pdf) [[Code]](https://github.com/MinorJerry/WebVoyager) `ACL 2024`
1. VisualWebArena: Evaluating Multimodal Agents on Realistic Visual Web Tasks. [[Paper]](https://arxiv.org/pdf/2401.13649) [[Code]](https://github.com/web-arena-x/visualwebarena) `ACL 2024`
1. OSWorld: Benchmarking Multimodal Agents for Open-Ended Tasks in Real Computer Environments. [[Paper]](https://arxiv.org/pdf/2404.07972) [[Code]](https://github.com/xlang-ai/OSWorld) `NeurIPS 2024`
1. Agent S: An Open Agentic Framework that Uses Computers Like a Human. [[Paper]](https://arxiv.org/pdf/2410.08164.pdf) [[Code]](https://github.com/simular-ai/Agent-S) `ICLR 2025`
1. AndroidWorld: A Dynamic Benchmarking Environment for Autonomous Agents. [[Paper]](https://arxiv.org/pdf/2405.14573) [[Code]](https://github.com/google-research/android_world) `ICLR 2025`
1. Mind2Web: Towards a Generalist Agent for the Web. [[Paper]](https://arxiv.org/pdf/2306.06070) [[Code]](https://github.com/OSU-NLP-Group/Mind2Web) `NeurIPS 2023`
1. WebArena: A Realistic Web Environment for Building Autonomous Agents. [[Paper]](https://arxiv.org/pdf/2307.13854) [[Code]](https://github.com/web-arena-x/webarena) `ICLR 2024`
1. AgentOccam: A Simple Yet Strong Baseline for LLM-Based Web Agents. [[Paper]](https://openreview.net/forum?id=oWdzUpOlkX) `ICLR 2025`
1. GPT-4V(ision) is a Generalist Web Agent, if Grounded. [[Paper]](https://proceedings.mlr.press/v235/zheng24e.html) `ICML 2024`
1. SeeClick: Harnessing GUI Grounding for Advanced Visual GUI Agents. [[Paper]](https://aclanthology.org/2024.acl-long.505/) `ACL 2024`
1. VAGEN: Reinforcing World Model Reasoning for Multi-Turn VLM Agents. `NeurIPS 2025`
1. DigiRL: Training In-The-Wild Device-Control Agents with Autonomous Reinforcement Learning. [[Paper]](https://arxiv.org/abs/2406.11896) [[Code]](https://github.com/DigiRL-agent/digirl) `NeurIPS 2024`
1. GUI-Actor: Coordinate-Free Visual Grounding for GUI Agents. [[Paper]](https://arxiv.org/pdf/2506.03143v1.pdf) [[Code]](https://github.com/microsoft/GUI-Actor) `NeurIPS 2025`
##### 3.1.1.2. State Representation
1. ToolLLM: Facilitating Large Language Models to Master 16000+ Real-world APIs. [[Paper]](https://arxiv.org/pdf/2307.16789) [[Code]](https://github.com/OpenBMB/ToolBench) `ICLR 2024`
1. SWE-agent: Agent-Computer Interfaces Enable Automated Software Engineering. [[Paper]](https://arxiv.org/pdf/2405.15793.pdf) [[Code]](https://github.com/princeton-nlp/SWE-agent) `NeurIPS 2024`
1. WebArena: A Realistic Web Environment for Building Autonomous Agents. [[Paper]](https://arxiv.org/pdf/2307.13854) [[Code]](https://github.com/web-arena-x/webarena) `ICLR 2024`
1. Do LLMs Build World Representations? Probing Through the Lens of State Abstraction. [[Paper]](https://proceedings.neurips.cc/paper_files/paper/2024/file/b1b16c4b875eb84d3585cb70d23970ca-Paper-Conference.pdf) [[Code]](https://github.com/BorealisAI/llm-world-abs) `NeurIPS 2024`
1. Evaluating LLM Planning in Partially Observable Environments via Observation Representations and Action Sequences. [[Paper]](https://openreview.net/forum?id=bCKBuMKxJi) `NeurIPS 2025`
1. AgentOccam: A Simple Yet Strong Baseline for LLM-Based Web Agents. [[Paper]](https://openreview.net/forum?id=oWdzUpOlkX) `ICLR 2025`
1. The Complexity Trap: Simple Observation Masking Is as Efficient as LLM Summarization for Agent Context Management. [[Paper]](https://doi.org/10.48550/arXiv.2508.21433) `arXiv 2025`
1. AgentTrek: Agent Trajectory Synthesis via Guiding Replay with Web Tutorials. [[Paper]](https://arxiv.org/abs/2412.09605) [[Code]](https://agenttrek.github.io/) `ICLR 2025`
1. DynaWeb: Model-Based Reinforcement Learning of Web Agents. [[Paper]](https://doi.org/10.48550/arXiv.2601.22149) `arXiv 2026`
1. GRAPHGPT-O: Synergistic Multimodal Comprehension and Generation on Graphs. [[Paper]](https://arxiv.org/pdf/2502.11925.pdf) [[Code]](https://github.com/YiFang99/GraphGPT-O) `CVPR 2025`
1. ESCA: Contextualizing Embodied Agents via Scene-Graph Generation. [[Paper]](https://arxiv.org/pdf/2510.15963.pdf) [[Code]](https://github.com/video-fm/ESCA) `NeurIPS 2025`
1. Building a C compiler with a team of parallel Claudes. [[Paper]](https://www.anthropic.com/engineering/building-c-compiler) `2026`
#### 3.1.2. Task Planning
##### 3.1.2.1. Task Decomposition
1. Chain-of-Thought Prompting Elicits Reasoning in Large Language Models. [[Paper]](https://arxiv.org/pdf/2201.11903.pdf) [[Code]](https://github.com/google-research/url-nlp/tree/main/mgsm) `NeurIPS 2022`
1. Least-to-Most Prompting Enables Complex Reasoning in Large Language Models. [[Paper]](https://arxiv.org/pdf/2205.10625.pdf) `ICLR 2023`
1. Tree of Thoughts: Deliberate Problem Solving with Large Language Models. [[Paper]](https://arxiv.org/pdf/2305.10601.pdf) [[Code]](https://github.com/princeton-nlp/tree-of-thought-llm) `NeurIPS 2023`
1. Graph of Thoughts: Solving Elaborate Problems with Large Language Models. [[Paper]](https://arxiv.org/pdf/2308.09687.pdf) [[Code]](https://github.com/spcl/graph-of-thoughts) `AAAI 2024`
1. Agentic Reasoning: A Streamlined Framework for Enhancing LLM Reasoning with Agentic Tools. [[Paper]](https://aclanthology.org/2025.acl-long.1383.pdf) `ACL 2025`
1. Agentic Reasoning for Large Language Models. [[Paper]](https://doi.org/10.48550/arXiv.2601.12538) `arXiv 2026`
1. Effective Harnesses for Long-Running Agents. [[Paper]](https://www.anthropic.com/engineering/effective-harnesses-for-long-running-agents) `2025`
1. Building a C compiler with a team of parallel Claudes. [[Paper]](https://www.anthropic.com/engineering/building-c-compiler) `2026`
##### 3.1.2.2. Plan Generation
1. AvaTaR: Optimizing LLM Agents for Tool Usage via Contrastive Reasoning. [[Paper]](https://proceedings.neurips.cc/paper_files/paper/2024/file/2db8ce969b000fe0b3fb172490c33ce8-Paper-Conference.pdf) [[Code]](https://github.com/zou-group/avatar) `NeurIPS 2024`
1. GAP: Graph-Based Agent Planning with Parallel Tool Use and Reinforcement Learning. [[Paper]](https://openreview.net/pdf?id=7bJIVHEvLm) [[Code]](https://github.com/WJQ7777/Graph-Agent-Planning) `arXiv 2025`
1. Effective Harnesses for Long-Running Agents. [[Paper]](https://www.anthropic.com/engineering/effective-harnesses-for-long-running-agents) `2025`
#### 3.1.3. Action Execution
##### 3.1.3.1. Tool Invocation
1. Toolformer: Language Models Can Teach Themselves to Use Tools. [[Paper]](https://arxiv.org/pdf/2302.04761.pdf) `NeurIPS 2023`
1. Code as Policies: Language Model Programs for Embodied Control. [[Paper]](https://arxiv.org/pdf/2209.07753.pdf) [[Code]](https://github.com/google-research/google-research/tree/master/code_as_policies) `ICRA 2023`
1. SWE-agent: Agent-Computer Interfaces Enable Automated Software Engineering. [[Paper]](https://arxiv.org/pdf/2405.15793.pdf) [[Code]](https://github.com/princeton-nlp/SWE-agent) `NeurIPS 2024`
1. AppWorld: A Controllable World of Apps and People for Benchmarking Interactive Coding Agents. [[Paper]](https://arxiv.org/pdf/2407.18901) [[Code]](https://github.com/StonyBrookNLP/appworld) `ACL 2024`
1. Robust Tool Use via Fission-GRPO: Learning to Recover from Execution Errors. [[Paper]](https://arxiv.org/abs/2601.15625) `2026`
1. Agent0-VL: Exploring Self-Evolving Agent for Tool-Integrated Vision-Language Reasoning. [[Paper]](https://arxiv.org/abs/2511.19900) `2025`
1. Scaling Agentic Reinforcement Learning for Tool-Integrated Reasoning in VLMs. [[Paper]](https://arxiv.org/abs/2511.19773) `2025`
1. Code execution with MCP: building more efficient AI agents. [[Paper]](https://www.anthropic.com/engineering/code-execution-with-mcp) `2025`
##### 3.1.3.2. Environment Interaction
1. ReAct: Synergizing Reasoning and Acting in Language Models. [[Paper]](https://arxiv.org/pdf/2210.03629.pdf) [[Code]](https://github.com/ysymyth/ReAct) `ICLR 2023`
1. SWE-agent: Agent-Computer Interfaces Enable Automated Software Engineering. [[Paper]](https://arxiv.org/pdf/2405.15793.pdf) [[Code]](https://github.com/princeton-nlp/SWE-agent) `NeurIPS 2024`
1. Grounding Multimodal Large Language Models in Actions. [[Paper]](https://proceedings.neurips.cc/paper_files/paper/2024/file/2406694fd7bc7e7bf257446a14f9ea63-Paper-Conference.pdf) `NeurIPS 2024`
1. ceLLMate: Sandboxing Browser AI Agents. [[Paper]](https://doi.org/10.48550/arXiv.2512.12594) `arXiv 2025`
1. Quine: Realizing LLM Agents as Native POSIX Processes. [[Paper]](https://arxiv.org/abs/2603.18030) `arXiv 2026`
1. Agent-Fence: Mapping Security Vulnerabilities Across Deep Research Agents. [[Paper]](https://arxiv.org/abs/2602.07652) `2026`
### 3.2. Memory Systems
1. Managing Context on the Claude Developer Platform. [[Paper]](https://www.anthropic.com/news/context-management) `2025`
1. Effective Harnesses for Long-Running Agents. [[Paper]](https://www.anthropic.com/engineering/effective-harnesses-for-long-running-agents) `2025`

#### 3.2.1. Short-term Memory
1. Managing Context on the Claude Developer Platform. [[Paper]](https://www.anthropic.com/news/context-management) `2025`

##### 3.2.1.1. Working Memory
1. ReAct: Synergizing Reasoning and Acting in Language Models. [[Paper]](https://arxiv.org/pdf/2210.03629.pdf) [[Code]](https://github.com/ysymyth/ReAct) `ICLR 2023`
1. Understanding Software Engineering Agents: A Study of Thought-Action-Result Trajectories. [[Paper]](https://doi.org/10.1109/ASE63991.2025.00234) `40th IEEE/ACM International Confer 2025`
1. Memo: Training Memory-Efficient Embodied Agents with Reinforcement Learning. [[Paper]](https://arxiv.org/pdf/2510.19732.pdf) [[Code]](https://github.com/gunshi/memo) `NeurIPS 2025`
1. Graph-based Agent Memory: Taxonomy, Techniques, and Applications. [[Paper]](https://doi.org/10.48550/arXiv.2602.05665) `arXiv 2026`
1. Agent Workflow Memory. [[Paper]](https://arxiv.org/pdf/2409.07429) [[Code]](https://github.com/zorazrw/agent-workflow-memory) `ICML 2025`
1. Managing Context on the Claude Developer Platform. [[Paper]](https://www.anthropic.com/news/context-management) `2025`
1. Effective Harnesses for Long-Running Agents. [[Paper]](https://www.anthropic.com/engineering/effective-harnesses-for-long-running-agents) `2025`
##### 3.2.1.2. Conversational Memory
1. From Isolated Conversations to Hierarchical Schemas: Dynamic Tree Memory Representation for LLMs. [[Paper]](https://openreview.net/forum?id=moXtEmCleY) `ICLR 2025`
1. MemGPT: Towards LLMs as Operating Systems. [[Paper]](https://arxiv.org/pdf/2310.08560) [[Code]](https://research.memgpt.ai/) `arXiv 2023`
1. SeCom: On Memory Construction and Retrieval for Personalized Conversational Agents. [[Paper]](https://openreview.net/forum?id=xKDZAW0He3) `ICLR 2025`
1. From Single to Multi-Granularity: Toward Long-Term Memory Association and Selection of Conversational Agents. [[Paper]](https://openreview.net/forum?id=i2yIvZARnG) `ICLR 2026`
1. Hello Again! LLM-powered Personalized Agent for Long-term Dialogue. [[Paper]](https://aclanthology.org/2025.naacl-long.272/) `ACL 2025`
1. SGMem: Sentence Graph Memory for Long-Term Conversational Agents. [[Paper]](https://doi.org/10.48550/arXiv.2509.21212) `arXiv 2025`
1. Zep: A Temporal Knowledge Graph Architecture for Agent Memory. [[Paper]](https://doi.org/10.48550/arXiv.2501.13956) `arXiv 2025`
1. Agentic Memory: Learning Unified Long-Term and Short-Term Memory Management for Large Language Model Agents. [[Paper]](https://doi.org/10.48550/arXiv.2601.01885) `arXiv 2026`
1. FluxMem: Adaptive Hierarchical Memory for Streaming Video Understanding. `CVPR 2026`
1. Managing Context on the Claude Developer Platform. [[Paper]](https://www.anthropic.com/news/context-management) `2025`
#### 3.2.2. Long-term Memory
1. Memory Overview. [[Paper]](https://docs.langchain.com/oss/python/concepts/memory) `2026`
1. LangMem. [[Paper]](https://langchain-ai.github.io/langmem/) `2026`

##### 3.2.2.1. Structured Memory
1. Graph-Native Cognitive Memory for AI Agents: Formal Belief Revision Semantics for Versioned Memory Architectures. [[Paper]](https://arxiv.org/abs/2603.17244) `arXiv 2026`
1. A-Mem: Agentic Memory for LLM Agents. [[Paper]](https://arxiv.org/pdf/2502.12110) [[Code]](https://github.com/WujiangXu/A-mem) `NeurIPS 2025`
1. Generative Agents: Interactive Simulacra of Human Behavior. [[Paper]](https://dl.acm.org/doi/epdf/10.1145/3586183.3606763) [[Code]](https://github.com/joonspk-research/generative_agents) `Proceedings of the 36th Annual ACM 2023`
1. Bridging Intuitive Associations and Deliberate Recall: Empowering LLM Personal Assistant with Graph-Structured Long-term Memory. [[Paper]](https://aclanthology.org/2025.findings-acl.901/) `ACL Findings 2025`
1. CarMem: Enhancing Long-Term Memory in LLM Voice Assistants through Category-Bounding. [[Paper]](https://aclanthology.org/2025.coling-industry.29/) `ACL 2025`
1. Mem0: Building Production-Ready AI Agents with Scalable Long-Term Memory. [[Paper]](https://arxiv.org/pdf/2504.19413) [[Code]](https://mem0.ai/research) `ECAI 2025`
##### 3.2.2.2. Unstructured Memory
1. MOOM: Maintenance, Organization and Optimization of Memory in Ultra-Long Role-Playing Dialogues. [[Paper]](https://doi.org/10.48550/arXiv.2509.11860) `arXiv 2025`
1. MemGPT: Towards LLMs as Operating Systems. [[Paper]](https://arxiv.org/pdf/2310.08560) [[Code]](https://research.memgpt.ai/) `arXiv 2023`
1. MemoryBank: Enhancing Large Language Models with Long-Term Memory. [[Paper]](https://arxiv.org/pdf/2305.10250.pdf) [[Code]](https://github.com/zhongwanjun/MemoryBank-SiliconFriend) `AAAI 2024`
1. Reflexion: language agents with verbal reinforcement learning. [[Paper]](https://arxiv.org/abs/2303.11366) [[Code]](https://github.com/noahshinn/reflexion) `NeurIPS 2023`
1. RetroAgent: From Solving to Evolving via Retrospective Dual Intrinsic Feedback. [[Paper]](https://arxiv.org/abs/2603.08561) `arXiv 2026`
1. Agentic Memory: Learning Unified Long-Term and Short-Term Memory Management for Large Language Model Agents. [[Paper]](https://doi.org/10.48550/arXiv.2601.01885) `arXiv 2026`
1. Memory-R1: Enhancing Large Language Model Agents to Manage and Utilize Memories via Reinforcement Learning. [[Paper]](https://doi.org/10.48550/arXiv.2508.19828) `arXiv 2025`
1. O-Mem: Omni Memory System for Personalized, Long Horizon, Self-Evolving Agents. [[Paper]](https://arxiv.org/abs/2511.13593) `2025`
1. General Agentic Memory Via Deep Research. [[Paper]](https://arxiv.org/abs/2511.18423) `2025`
1. Mem0: Universal Memory Layer for AI Agents. [[Paper]](https://github.com/mem0ai/mem0) `2026`
1. OpenMemory: AI Memory MCP Server for Coding Agents. [[Paper]](https://mem0.ai/openmemory) `2026`
1. Memory - Docs by LangChain. [[Paper]](https://docs.langchain.com/oss/python/deepagents/memory) `2026`
1. Context Engineering: Memory, Compaction, and Tool Clearing. [[Paper]](https://platform.claude.com/cookbook/tool-use-context-engineering-context-engineering-tools) `2026`
### 3.3. Skill Libraries
1. SoK: Agentic Skills - Beyond Tool Use in LLM Agents. [[Paper]](https://doi.org/10.48550/arXiv.2602.20867) `arXiv 2026`
1. Agent Skills for Large Language Models: Architecture, Acquisition, Security, and the Path Forward. [[Paper]](https://arxiv.org/abs/2602.12430) `2026`
1. SkillsBench: Benchmarking How Well Agent Skills Work Across Diverse Tasks. [[Paper]](https://arxiv.org/abs/2602.12670) `arXiv 2026`
1. Memory - Docs by LangChain. [[Paper]](https://docs.langchain.com/oss/python/deepagents/memory) `2026`
1. Equipping Agents for the Real World with Agent Skills. [[Paper]](https://www.anthropic.com/engineering/equipping-agents-for-the-real-world-with-agent-skills) `2025`
1. Skills in OpenAI API. [[Paper]](https://developers.openai.com/cookbook/examples/skills_in_api) `2026`
1. SkillRouter: Skill Routing for LLM Agents at Scale. [[Paper]](https://arxiv.org/abs/2603.22455) `arXiv 2026`
1. SkillX: Automatically Constructing Skill Knowledge Bases for Agents. [[Paper]](https://arxiv.org/abs/2604.04804) `2026`

#### 3.3.1. Skill Acquisition
##### 3.3.1.1. Learning from Demonstration
1. SoK: Agentic Skills - Beyond Tool Use in LLM Agents. [[Paper]](https://doi.org/10.48550/arXiv.2602.20867) `arXiv 2026`
1. Agent Skills for Large Language Models: Architecture, Acquisition, Security, and the Path Forward. [[Paper]](https://arxiv.org/abs/2602.12430) `2026`
1. Toolformer: Language Models Can Teach Themselves to Use Tools. [[Paper]](https://arxiv.org/pdf/2302.04761.pdf) `NeurIPS 2023`
1. Gorilla: Large Language Model Connected with Massive APIs. [[Paper]](http://papers.nips.cc/paper_files/paper/2024/hash/e4c61f578ff07830f5c37378dd3ecb0d-Abstract-Conference.html) `NeurIPS 2024`
1. Voyager: An Open-Ended Embodied Agent with Large Language Models. [[Paper]](https://arxiv.org/pdf/2305.16291.pdf) [[Code]](https://github.com/MineDojo/Voyager) `Trans. Mach. Learn. Res. 2024`
1. Synatra: Turning Indirect Knowledge into Direct Demonstrations for Digital Agents at Scale. [[Paper]](http://papers.nips.cc/paper_files/paper/2024/hash/a6a6891cf1dfc64d664f086cf5976e93-Abstract-Conference.html) `NeurIPS 2024`
1. SkillWeaver: Web Agents can Self-Improve by Discovering and Honing Skills. [[Paper]](https://doi.org/10.48550/arXiv.2504.07079) `arXiv 2025`
1. SkillCraft: Can LLM Agents Learn to Use Tools Skillfully?. [[Paper]](https://arxiv.org/pdf/2603.00718.pdf) [[Code]](https://github.com/shiqichen17/SkillCraft) `2026`
1. Trace2Skill: Distill Trajectory-Local Lessons into Transferable Agent Skills. [[Paper]](https://arxiv.org/abs/2603.25158) `arXiv 2026`
1. Agent Skill Acquisition for Large Language Models via CycleQD. [[Paper]](https://arxiv.org/pdf/2410.14735.pdf) [[Code]](https://github.com/SakanaAI/CycleQD) `2025`
1. Go-Browse: Training Web Agents with Structured Exploration. [[Paper]](https://openreview.net/forum?id=IpzRWE52yw) `ICLR 2026`
1. Inducing Programmatic Skills for Agentic Tasks. [[Paper]](https://openreview.net/forum?id=lsAY6fWsog) `COLM 2025`
1. ContractSkill: Repairable Contract-Based Skills for Multimodal Web Agents. [[Paper]](https://arxiv.org/abs/2603.20340) `arXiv 2026`
##### 3.3.1.2. Learning from Experience
1. Hierarchical Reinforcement Learning: A Survey and Open Research Challenges. [[Paper]](https://doi.org/10.3390/make4010009) `Mach. Learn. Knowl. Extr. 2022`
1. ExpeL: LLM Agents Are Experiential Learners. [[Paper]](https://arxiv.org/pdf/2308.10144.pdf) [[Code]](https://github.com/LeapLabTHU/ExpeL) `AAAI 2024`
1. Evolving Programmatic Skill Networks. [[Paper]](https://doi.org/10.48550/arXiv.2601.03509) `arXiv 2026`
1. SkillRL: Evolving Agents via Recursive Skill-Augmented Reinforcement Learning. [[Paper]](https://arxiv.org/pdf/2602.08234.pdf) [[Code]](https://github.com/aiming-lab/SkillRL) `arXiv 2026`
1. Memento-Skills: Let Agents Design Agents. [[Paper]](https://arxiv.org/abs/2603.18743) `arXiv 2026`
1. AutoSkill: Experience-Driven Lifelong Learning via Skill Self-Evolution. [[Paper]](https://arxiv.org/abs/2603.01145) `2026`
1. ELITE: Experiential Learning and Intent-Aware Transfer for Self-improving Embodied Agents. [[Paper]](https://arxiv.org/abs/2603.24018) `arXiv 2026`
1. SEAgent: Self-Evolving Computer Use Agent with Autonomous Learning from Experience. [[Paper]](https://arxiv.org/pdf/2508.04700.pdf) [[Code]](https://github.com/SunzeY/SEAgent) `arXiv 2025`
1. Leveraging Skills from Unlabeled Prior Data for Efficient Online Exploration. [[Paper]](https://arxiv.org/pdf/2410.18076.pdf) [[Code]](https://github.com/rail-berkeley/SUPE) `ICML 2025`
1. Tool-R0: Self-Evolving LLM Agents for Tool-Learning from Zero Data. [[Paper]](https://arxiv.org/abs/2602.21320) `2026`
##### 3.3.1.3. Learning from External Resources
1. SKILLFOUNDRY: Building Self-Evolving Agent Skill Libraries from Heterogeneous Scientific Resources. [[Paper]](https://arxiv.org/abs/2604.03964) `arXiv 2026`
1. Equipping Agents for the Real World with Agent Skills. [[Paper]](https://www.anthropic.com/engineering/equipping-agents-for-the-real-world-with-agent-skills) `2025`
1. Agent Skills. [[Paper]](https://platform.claude.com/docs/en/agents-and-tools/agent-skills/overview) `2025`
1. Skills in OpenAI API. [[Paper]](https://developers.openai.com/cookbook/examples/skills_in_api) `2026`
#### 3.3.2. Skill Management
1. Skill Retrieval Augmentation for Agentic AI. [[Paper]](https://arxiv.org/abs/2604.24594) `arXiv 2026`

##### 3.3.2.1. Skill Representation
1. Voyager: An Open-Ended Embodied Agent with Large Language Models. [[Paper]](https://arxiv.org/pdf/2305.16291.pdf) [[Code]](https://github.com/MineDojo/Voyager) `Trans. Mach. Learn. Res. 2024`
1. SoK: Agentic Skills - Beyond Tool Use in LLM Agents. [[Paper]](https://doi.org/10.48550/arXiv.2602.20867) `arXiv 2026`
1. Inducing Programmatic Skills for Agentic Tasks. [[Paper]](https://openreview.net/forum?id=lsAY6fWsog) `COLM 2025`
1. Trace2Skill: Distill Trajectory-Local Lessons into Transferable Agent Skills. [[Paper]](https://arxiv.org/abs/2603.25158) `arXiv 2026`
1. Memento-Skills: Let Agents Design Agents. [[Paper]](https://arxiv.org/abs/2603.18743) `arXiv 2026`
1. SkillFlow: Scalable and Efficient Agent Skill Retrieval System. [[Paper]](https://arxiv.org/abs/2504.06188) `2026`
1. ToolGen: Unified Tool Retrieval and Calling via Generation. [[Paper]](https://arxiv.org/pdf/2410.03439.pdf) [[Code]](https://github.com/Reason-Wang/ToolGen) `ICLR 2025`
1. Evolving Programmatic Skill Networks. [[Paper]](https://doi.org/10.48550/arXiv.2601.03509) `arXiv 2026`
1. Equipping Agents for the Real World with Agent Skills. [[Paper]](https://www.anthropic.com/engineering/equipping-agents-for-the-real-world-with-agent-skills) `2025`
1. Skills in OpenAI API. [[Paper]](https://developers.openai.com/cookbook/examples/skills_in_api) `2026`
1. Agent Skills. [[Paper]](https://developers.openai.com/codex/skills) `2026`
1. Graph of Skills: Dependency-Aware Structural Retrieval for Massive Agent Skills. [[Paper]](https://arxiv.org/abs/2604.05333) `arXiv 2026`
1. SkillRouter: Skill Routing for LLM Agents at Scale. [[Paper]](https://arxiv.org/abs/2603.22455) `arXiv 2026`
##### 3.3.2.2. Skill Retrieval
1. Memento-Skills: Let Agents Design Agents. [[Paper]](https://arxiv.org/abs/2603.18743) `arXiv 2026`
1. Voyager: An Open-Ended Embodied Agent with Large Language Models. [[Paper]](https://arxiv.org/pdf/2305.16291.pdf) [[Code]](https://github.com/MineDojo/Voyager) `Trans. Mach. Learn. Res. 2024`
1. GraphSkill: Documentation-Guided Hierarchical Retrieval-Augmented Coding for Complex Graph Reasoning. [[Paper]](https://arxiv.org/abs/2603.06620) `arXiv 2026`
1. G-Memory: Tracing Hierarchical Memory for Multi-Agent Systems. [[Paper]](https://openreview.net/pdf?id=mmIAp3cVS0) [[Code]](https://github.com/bingreeky/GMemory) `NeurIPS 2025`
1. SRSA: Skill Retrieval and Adaptation for Robotic Assembly Tasks. [[Paper]](https://arxiv.org/pdf/2503.04538.pdf) `ICLR 2025`
1. SkillFlow: Scalable and Efficient Agent Skill Retrieval System. [[Paper]](https://arxiv.org/abs/2504.06188) `2026`
1. Graph of Skills: Dependency-Aware Structural Retrieval for Massive Agent Skills. [[Paper]](https://arxiv.org/abs/2604.05333) `arXiv 2026`
1. IntentCUA: Learning Intent-level Representations for Skill Abstraction and Multi-Agent Planning in Computer-Use Agents. `Proceedings of the 25th Internatio 2026`
1. WebXSkill: Skill Learning for Autonomous Web Agents. [[Paper]](https://arxiv.org/abs/2604.13318) `arXiv 2026`
1. EvolveR: Self-Evolving LLM Agents through an Experience-Driven Lifecycle. [[Paper]](https://arxiv.org/abs/2510.16079) [[Code]](https://github.com/Edaizi/EvolveR) `arXiv 2025`
1. SkillRouter: Skill Routing for LLM Agents at Scale. [[Paper]](https://arxiv.org/abs/2603.22455) `arXiv 2026`
1. Skill Retrieval Augmentation for Agentic AI. [[Paper]](https://arxiv.org/abs/2604.24594) `arXiv 2026`
#### 3.3.3. Skill Maintenance
##### 3.3.3.1. Library Curation
1. Using Skills to Accelerate OSS Maintenance. [[Paper]](https://developers.openai.com/blog/skills-agents-sdk) `2026`
1. Shell + Skills + Compaction: Tips for Long-Running Agents that Do Real Work. [[Paper]](https://developers.openai.com/blog/skills-shell-tips) `2026`
1. SkillRouter: Skill Routing for LLM Agents at Scale. [[Paper]](https://arxiv.org/abs/2603.22455) `arXiv 2026`
1. Graph of Skills: Dependency-Aware Structural Retrieval for Massive Agent Skills. [[Paper]](https://arxiv.org/abs/2604.05333) `arXiv 2026`
##### 3.3.3.2. Skill Governance
1. Skills in OpenAI API. [[Paper]](https://developers.openai.com/cookbook/examples/skills_in_api) `2026`
1. Testing Agent Skills Systematically with Evals. [[Paper]](https://developers.openai.com/blog/eval-skills) `2026`
1. Towards Secure Agent Skills: Architecture, Threat Taxonomy, and Security Analysis. [[Paper]](https://arxiv.org/abs/2604.02837) `arXiv 2026`
1. Equipping Agents for the Real World with Agent Skills. [[Paper]](https://www.anthropic.com/engineering/equipping-agents-for-the-real-world-with-agent-skills) `2025`
### 3.4. Multi-agent Orchestration
1. How We Built Our Multi-Agent Research System. [[Paper]](https://www.anthropic.com/engineering/multi-agent-research-system) `2025`

#### 3.4.1. Coordination Architectures
##### 3.4.1.1. Centralized Architectures
1. MetaGPT: Meta Programming for A Multi-Agent Collaborative Framework. [[Paper]](https://openreview.net/pdf?id=VtmBAGCN7o) [[Code]](https://github.com/geekan/MetaGPT) `ICLR 2024`
1. ChatDev: Communicative Agents for Software Development. [[Paper]](https://aclanthology.org/2024.acl-long.810.pdf) [[Code]](https://github.com/OpenBMB/ChatDev) `ACL 2024`
1. AutoGen: Enabling Next-Gen LLM Applications via Multi-Agent Conversations. [[Paper]](https://openreview.net/pdf?id=BAakY1hNKS) [[Code]](https://github.com/microsoft/autogen) `COLM 2024`
1. MegaAgent: A Large-Scale Autonomous LLM-based Multi-Agent System Without Predefined SOPs. [[Paper]](https://aclanthology.org/2025.findings-acl.259.pdf) [[Code]](https://github.com/Xtra-Computing/MegaAgent) `ACL Findings 2025`
1. Multi-Agent Collaboration via Evolving Orchestration. [[Paper]](https://arxiv.org/abs/2505.19591) [[Code]](https://github.com/OpenBMB/ChatDev/tree/puppeteer) `NeurIPS 2025`
1. AutoAgents: A Framework for Automatic Agent Generation. [[Paper]](https://arxiv.org/pdf/2309.17288) [[Code]](https://github.com/Link-AGI/AutoAgents) `IJCAI 2024`
1. How We Built Our Multi-Agent Research System. [[Paper]](https://www.anthropic.com/engineering/multi-agent-research-system) `2025`
1. Scaling Teams or Scaling Time? Memory Enabled Lifelong Learning in LLM Multi-Agent Systems. [[Paper]](https://arxiv.org/abs/2604.03295) `2026`
##### 3.4.1.2. Decentralized Architectures
1. CAMEL: Communicative Agents for "Mind" Exploration of Large Language Model Society. [[Paper]](https://proceedings.neurips.cc/paper/2023/hash/a3621ee907def47c1b952ade25c67698-Abstract-Conference.html) [[Code]](https://github.com/camel-ai/camel) `NeurIPS 2023`
1. AgentVerse: Facilitating Multi-Agent Collaboration and Exploring Emergent Behaviors in Agents. [[Paper]](https://openreview.net/pdf?id=EHg5GDnyq1) [[Code]](https://github.com/OpenBMB/AgentVerse) `arXiv 2023`
1. A Dynamic LLM-Powered Agent Network for Task-Oriented Agent Collaboration. [[Paper]](https://arxiv.org/pdf/2310.02170) [[Code]](https://github.com/SALT-NLP/DyLAN) `COLM 2024`
1. AgentOrchestra: Orchestrating Multi-Agent Intelligence with the Tool-Environment-Agent(TEA) Protocol. [[Paper]](https://doi.org/10.48550/arXiv.2506.12508) `arXiv 2025`
1. LLM-Driven Multi-Agent Architectures for Intelligent Self-Organizing Networks. [[Paper]](https://ieeexplore.ieee.org/abstract/document/11169757/) `IEEE Network 2025`
1. ProAgent: Building Proactive Cooperative Agents with Large Language Models. [[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/29710) `AAAI 2024`
1. CONSENSAGENT: Towards Efficient and Effective Consensus in Multi-Agent LLM Interactions Through Sycophancy Mitigation. [[Paper]](https://aclanthology.org/2025.findings-acl.1141.pdf) [[Code]](https://github.com/priyapitre/CONSENSAGENT) `ACL Findings 2025`
1. Building a C Compiler with a Team of Parallel Claudes. [[Paper]](https://www.anthropic.com/engineering/building-c-compiler) `2026`
1. Multi-Agent Coordination Patterns: Five Approaches and When to Use Them. [[Paper]](https://claude.com/blog/multi-agent-coordination-patterns) `2026`
#### 3.4.2. Communication Mechanisms
1. Don't Build Multi-Agents. [[Paper]](https://cognition.ai/blog/dont-build-multi-agents) `2025`

##### 3.4.2.1. Debate-based Methods
1. MetaGPT: Meta Programming for A Multi-Agent Collaborative Framework. [[Paper]](https://openreview.net/pdf?id=VtmBAGCN7o) [[Code]](https://github.com/geekan/MetaGPT) `ICLR 2024`
1. RoleLLM: Benchmarking, Eliciting, and Enhancing Role-Playing Abilities of Large Language Models. [[Paper]](https://aclanthology.org/2024.findings-acl.878.pdf) [[Code]](https://github.com/InteractiveNLP-Team/RoleLLM-public) `ACL 2024`
1. Table-Critic: A Multi-Agent Framework for Collaborative Criticism and Refinement in Table Reasoning. `ACL 2025`
1. Encouraging Divergent Thinking in Large Language Models through Multi-Agent Debate. [[Paper]](https://arxiv.org/abs/2305.19118) [[Code]](https://github.com/Skytliang/Multi-Agents-Debate) `ACL 2024`
1. Debate-to-Write: A Persona-Driven Multi-Agent Framework for Diverse Argument Generation. [[Paper]](https://aclanthology.org/2025.coling-main.314.pdf) [[Code]](https://github.com/Derekkk/LLM4ArgGen) `ACL 2025`
1. Player-Coach Teamwork: Multi-agent Collaboration for Improving LLM Reasoning. [[Paper]](https://openreview.net/pdf?id=qNHbqlRBel) `NeurIPS 2025`
1. Should we be going MAD? A Look at Multi-Agent Debate Strategies for LLMs. [[Paper]](https://proceedings.mlr.press/v235/smit24a.html) `ICML 2024`
1. Reinforce LLM Reasoning through Multi-Agent Reflection. [[Paper]](https://arxiv.org/pdf/2506.08379) `ICML 2025`
1. CONSENSAGENT: Towards Efficient and Effective Consensus in Multi-Agent LLM Interactions Through Sycophancy Mitigation. [[Paper]](https://aclanthology.org/2025.findings-acl.1141.pdf) [[Code]](https://github.com/priyapitre/CONSENSAGENT) `ACL Findings 2025`
##### 3.4.2.2. Collaboration-based Methods
1. Long-Horizon Planning for Multi-Agent Robots in Partially Observable Environments. [[Paper]](https://arxiv.org/pdf/2407.10031.pdf) [[Code]](https://github.com/nsidn98/LLaMAR) `NeurIPS 2024`
1. InstructFlow: Adaptive Symbolic Constraint-Guided Code Generation for Long-Horizon Planning. [[Paper]](https://openreview.net/forum?id=nzwjvpCO4F) [[Code]](https://github.com/chiht21/InstructFlow) `NeurIPS 2025`
1. ChatDev: Communicative Agents for Software Development. [[Paper]](https://aclanthology.org/2024.acl-long.810.pdf) [[Code]](https://github.com/OpenBMB/ChatDev) `ACL 2024`
1. Flow-of-Action: SOP Enhanced LLM-Based Multi-Agent System for Root Cause Analysis. [[Paper]](https://arxiv.org/pdf/2502.08224) `WWW 2025`
1. MetaGPT: Meta Programming for A Multi-Agent Collaborative Framework. [[Paper]](https://openreview.net/pdf?id=VtmBAGCN7o) [[Code]](https://github.com/geekan/MetaGPT) `ICLR 2024`
1. Multi-Agent Collaboration via Evolving Orchestration. [[Paper]](https://arxiv.org/abs/2505.19591) [[Code]](https://github.com/OpenBMB/ChatDev/tree/puppeteer) `NeurIPS 2025`
1. GPTSwarm: Language Agents as Optimizable Graphs. [[Paper]](https://proceedings.mlr.press/v235/zhuge24a.html) `ICML 2024`
1. MAPoRL: Multi-Agent Post-Co-Training for Collaborative Large Language Models with Reinforcement Learning. [[Paper]](https://arxiv.org/abs/2502.18439) [[Code]](https://github.com/chanwoo-park-official/MAPoRL) `ACL 2025`
1. MARFT: Multi-Agent Reinforcement Fine-Tuning. [[Paper]](https://arxiv.org/abs/2504.16129) [[Code]](https://github.com/jwliao-ai/MARFT) `arXiv 2025`
1. AgentOrchestra: Orchestrating Multi-Agent Intelligence with the Tool-Environment-Agent(TEA) Protocol. [[Paper]](https://arxiv.org/abs/2506.12508) `2026`
1. Toward Autonomous Long-Horizon Engineering for ML Research. [[Paper]](https://arxiv.org/abs/2604.13018) `arXiv 2026`
1. How and When to Build Multi-Agent Systems. [[Paper]](https://www.langchain.com/blog/how-and-when-to-build-multi-agent-systems) `2025`
1. Don't Build Multi-Agents. [[Paper]](https://cognition.ai/blog/dont-build-multi-agents) `2025`
1. Multi-Agent Coordination Patterns: Five Approaches and When to Use Them. [[Paper]](https://claude.com/blog/multi-agent-coordination-patterns) `2026`
1. How We Built Our Multi-Agent Research System. [[Paper]](https://www.anthropic.com/engineering/multi-agent-research-system) `2025`
### 3.5. A Comparative View of Representative Agent Systems
1. Claude Code Overview. `2026`
1. OpenClaw: Personal AI Assistant. [[Paper]](https://openclaw.ai) `2026`
1. Hermes Agent: The Agent That Grows With You. [[Paper]](https://hermes-agent.nousresearch.com/) `2026`

##### 3.5.1. Agent Workflow
##### 3.5.2. Memory Systems
##### 3.5.3. Skill Libraries
##### 3.5.4. Multi-Agent Orchestration

## 4. Model Adaptation for Harness
### 4.1. Context Engineering
#### 4.1.1. Context Design
##### 4.1.1.1. Prompt Engineering
1. Chain-of-Thought Prompting Elicits Reasoning in Large Language Models. [[Paper]](https://arxiv.org/pdf/2201.11903.pdf) [[Code]](https://github.com/google-research/url-nlp/tree/main/mgsm) `NeurIPS 2022`
1. Large Language Models are Zero-Shot Reasoners. `NeurIPS 2022`
1. Tree of Thoughts: Deliberate Problem Solving with Large Language Models. [[Paper]](https://arxiv.org/pdf/2305.10601.pdf) [[Code]](https://github.com/princeton-nlp/tree-of-thought-llm) `NeurIPS 2023`
1. Graph of Thoughts: Solving Elaborate Problems with Large Language Models. [[Paper]](https://arxiv.org/pdf/2308.09687.pdf) [[Code]](https://github.com/spcl/graph-of-thoughts) `AAAI 2024`
1. Role play with large language models. [[Paper]](https://www.nature.com/articles/s41586-023-06647-8.pdf) `Nat. 2023`
1. CAMEL: Communicative Agents for "Mind" Exploration of Large Language Model Society. [[Paper]](https://proceedings.neurips.cc/paper/2023/hash/a3621ee907def47c1b952ade25c67698-Abstract-Conference.html) [[Code]](https://github.com/camel-ai/camel) `NeurIPS 2023`
1. Generative Agents: Interactive Simulacra of Human Behavior. [[Paper]](https://dl.acm.org/doi/epdf/10.1145/3586183.3606763) [[Code]](https://github.com/joonspk-research/generative_agents) `Proceedings of the 36th Annual ACM 2023`
1. CoSER: A Comprehensive Literary Dataset and Framework for Training and Evaluating LLM Role-Playing and Persona Simulation. [[Paper]](https://arxiv.org/pdf/2502.09082) [[Code]](https://github.com/Neph0s/CoSER) `ICML 2025`
1. Large Language Models are Human-Level Prompt Engineers. `ICLR 2023`
1. Making Pre-trained Language Models Better Few-shot Learners. `ACL 2021`
1. Self-Refine: Iterative Refinement with Self-Feedback. [[Paper]](https://arxiv.org/abs/2303.17651) [[Code]](https://github.com/madaan/self-refine) `NeurIPS 2023`
1. Promptbreeder: Self-Referential Self-Improvement via Prompt Evolution. `ICML 2024`
##### 4.1.1.2. Context Retrieval
1. Interleaving Retrieval with Chain-of-Thought Reasoning for Knowledge-Intensive Multi-Step Questions. `ACL 2023`
1. Active Retrieval Augmented Generation. [[Paper]](https://aclanthology.org/2023.emnlp-main.495.pdf) [[Code]](https://github.com/jzbjyb/FLARE) `ACL 2023`
1. Self-RAG: Learning to Retrieve, Generate, and Critique through Self-Reflection. [[Paper]](https://proceedings.iclr.cc/paper_files/paper/2024/file/25f7be9694d7b32d5cc670927b8091e1-Paper-Conference.pdf) [[Code]](https://selfrag.github.io/) `ICLR 2024`
1. Deeprag: Thinking to retrieve step by step for large language models. [[Paper]](https://arxiv.org/pdf/2502.01142.pdf) [[Code]](https://github.com/gxy-gxy/DeepRAG) `arXiv 2025`
1. HippoRAG: Neurobiologically Inspired Long-Term Memory for Large Language Models. `NeurIPS 2024`
1. Think-on-Graph: Deep and Responsible Reasoning of Large Language Model on Knowledge Graph. `ICLR 2024`
1. StructRAG: Boosting Knowledge Intensive Reasoning of LLMs via Inference-time Hybrid Information Structurization. `ICLR 2025`
1. ReAct: Synergizing Reasoning and Acting in Language Models. [[Paper]](https://arxiv.org/pdf/2210.03629.pdf) [[Code]](https://github.com/ysymyth/ReAct) `ICLR 2023`
1. DSPy: Compiling Declarative Language Model Calls into Self-Improving Pipelines. [[Paper]](https://arxiv.org/abs/2310.03714) `arXiv 2023`
1. A-RAG: Scaling Agentic Retrieval-Augmented Generation via Hierarchical Retrieval Interfaces. [[Paper]](https://arxiv.org/abs/2602.03442) `arXiv 2026`
1. MA-RAG: Multi-Agent Retrieval-Augmented Generation via Collaborative Chain-of-Thought Reasoning. [[Paper]](https://arxiv.org/abs/2505.20096) `arXiv 2025`
#### 4.1.2. Context Management
##### 4.1.2.1. Context Processing
1. LLMLingua: Compressing Prompts for Accelerated Inference of Large Language Models. `ACL 2023`
1. Compressing Context to Enhance Inference Efficiency of Large Language Models. [[Paper]](https://aclanthology.org/2023.emnlp-main.391.pdf) [[Code]](https://github.com/liyucheng09/Selective_Context) `ACL 2023`
1. ACON: Optimizing Context Compression for Long-horizon LLM Agents. [[Paper]](https://arxiv.org/pdf/2510.00615) [[Code]](https://github.com/microsoft/acon) `arXiv 2025`
1. Reducing Cost of LLM Agents with Trajectory Reduction. [[Paper]](https://arxiv.org/abs/2509.23586) `arXiv 2025`
1. AgentFold: Long-Horizon Web Agents with Proactive Context Management. [[Paper]](https://arxiv.org/abs/2510.24699) `arXiv 2025`
1. SWE-Pruner: Self-Adaptive Context Pruning for Coding Agents. [[Paper]](https://arxiv.org/abs/2601.16746) `arXiv 2026`
1. IterResearch: Rethinking Long-Horizon Agents with Interaction Scaling. [[Paper]](https://openreview.net/forum?id=qQ5MZ5Mx7p) `ICLR 2026`
##### 4.1.2.2. Context Updating
1. Reflexion: language agents with verbal reinforcement learning. [[Paper]](https://arxiv.org/abs/2303.11366) [[Code]](https://github.com/noahshinn/reflexion) `NeurIPS 2023`
1. Agent Workflow Memory. [[Paper]](https://arxiv.org/pdf/2409.07429) [[Code]](https://github.com/zorazrw/agent-workflow-memory) `ICML 2025`
1. MemGPT: Towards LLMs as Operating Systems. [[Paper]](https://arxiv.org/pdf/2310.08560) [[Code]](https://research.memgpt.ai/) `arXiv 2023`
1. Mem0: Building Production-Ready AI Agents with Scalable Long-Term Memory. [[Paper]](https://arxiv.org/pdf/2504.19413) [[Code]](https://mem0.ai/research) `ECAI 2025`
1. Efficient Streaming Language Models with Attention Sinks. [[Paper]](https://proceedings.iclr.cc/paper_files/paper/2024/file/5e5fd18f863cbe6d8ae392a93fd271c9-Paper-Conference.pdf) [[Code]](https://github.com/mit-han-lab/streaming-llm) `ICLR 2024`
1. MemoryBank: Enhancing Large Language Models with Long-Term Memory. [[Paper]](https://arxiv.org/pdf/2305.10250.pdf) [[Code]](https://github.com/zhongwanjun/MemoryBank-SiliconFriend) `AAAI 2024`
1. AgentSys: Secure and Dynamic LLM Agents Through Explicit Hierarchical Memory Management. [[Paper]](https://arxiv.org/abs/2602.07398) `arXiv 2026`
1. A-Mem: Agentic Memory for LLM Agents. [[Paper]](https://arxiv.org/pdf/2502.12110) [[Code]](https://github.com/WujiangXu/A-mem) `NeurIPS 2025`
1. HiAgent: Hierarchical Working Memory Management for Solving Long-Horizon Agent Tasks with Large Language Model. `ACL 2025`
1. Dynamic Affective Memory Management for Personalized LLM Agents. [[Paper]](https://arxiv.org/abs/2510.27418) `arXiv 2025`
### 4.2. Agentic Training
#### 4.2.1. Environment Construction
##### 4.2.1.1. Rule-Based Environments
1. ALFWorld: Aligning Text and Embodied Environments for Interactive Learning. [[Paper]](https://arxiv.org/abs/2010.03768) [[Code]](https://github.com/alfworld/alfworld) `ICLR 2021`
1. ScienceWorld: Is your Agent Smarter than a 5th Grader?. [[Paper]](https://aclanthology.org/2022.emnlp-main.775/) [[Code]](https://github.com/allenai/ScienceWorld) `ACL 2022`
1. WebShop: Towards Scalable Real-World Web Interaction with Grounded Language Agents. [[Paper]](https://arxiv.org/abs/2207.01206) [[Code]](https://github.com/princeton-nlp/WebShop) `NeurIPS 2022`
1. AlphaMath Almost Zero: Process Supervision without Process. [[Paper]](https://openreview.net/forum?id=VaXnxQ3UKo) `NeurIPS 2024`
1. Step-level Value Preference Optimization for Mathematical Reasoning. [[Paper]](https://aclanthology.org/2024.findings-emnlp.463/) `ACL Findings 2024`
1. R-Zero: Self-Evolving Reasoning LLM from Zero Data. [[Paper]](https://arxiv.org/abs/2508.05004) `arXiv 2025`
1. Reinforcement Learning for Reasoning in Large Language Models with One Training Example. [[Paper]](https://arxiv.org/abs/2504.20571) `arXiv 2025`
1. FormalMATH: Benchmarking Formal Mathematical Reasoning of Large Language Models. [[Paper]](https://arxiv.org/abs/2505.02735) `arXiv 2025`
1. MLGym: A New Framework and Benchmark for Advancing AI Research Agents. [[Paper]](https://arxiv.org/abs/2502.14499) `arXiv 2025`
1. ScienceAgentBench: Toward Rigorous Assessment of Language Agents for Data-Driven Scientific Discovery. [[Paper]](https://arxiv.org/pdf/2410.05080) [[Code]](https://github.com/OSU-NLP-Group/ScienceAgentBench) `ICLR 2025`
1. InterCode: Standardizing and Benchmarking Interactive Coding with Execution Feedback. [[Paper]](https://arxiv.org/abs/2306.14898) [[Code]](https://github.com/princeton-nlp/intercode) `NeurIPS 2023`
1. AppWorld: A Controllable World of Apps and People for Benchmarking Interactive Coding Agents. [[Paper]](https://arxiv.org/pdf/2407.18901) [[Code]](https://github.com/StonyBrookNLP/appworld) `ACL 2024`
1. REASONING GYM: Reasoning Environments for Reinforcement Learning with Verifiable Rewards. [[Paper]](https://arxiv.org/abs/2505.24760) `arXiv 2025`
1. EnterpriseOps-Gym: Environments and Evaluations for Stateful Agentic Planning and Tool Use in Enterprise Settings. [[Paper]](https://arxiv.org/abs/2603.13594) `arXiv 2026`
1. Immersion in the GitHub Universe: Scaling Coding Agents to Mastery. [[Paper]](https://doi.org/10.48550/arXiv.2602.09892) `arXiv 2026`
##### 4.2.1.2. Simulation-Based Environments
1. WebWorld: A Large-Scale World Model for Web Agent Training. [[Paper]](https://arxiv.org/abs/2602.14721) `arXiv 2026`
1. NeuralOS: Towards Simulating Operating Systems via Neural Generative Models. [[Paper]](https://arxiv.org/abs/2507.08800) `arXiv 2025`
1. BuilderBench: The Building Blocks of Intelligent Agents. [[Paper]](https://arxiv.org/abs/2510.06288) `arXiv 2025`
1. MEAL: A Benchmark for Continual Multi-Agent Reinforcement Learning. [[Paper]](https://arxiv.org/abs/2506.14990) `arXiv 2025`
1. Reasoning with Language Model is Planning with World Model. `ACL 2023`
1. Agent World Model: Infinity Synthetic Environments for Agentic Reinforcement Learning. [[Paper]](https://arxiv.org/abs/2602.10090) `arXiv 2026`
##### 4.2.1.3. Real-World Environments
1. WebArena: A Realistic Web Environment for Building Autonomous Agents. [[Paper]](https://arxiv.org/pdf/2307.13854) [[Code]](https://github.com/web-arena-x/webarena) `ICLR 2024`
1. The BrowserGym Ecosystem for Web Agent Research. [[Paper]](https://arxiv.org/abs/2412.05467) `Trans. Mach. Learn. Res. 2025`
1. AgentBench: Evaluating LLMs as Agents. [[Paper]](https://arxiv.org/pdf/2308.03688) [[Code]](https://github.com/THUDM/AgentBench) `ICLR 2024`
1. DigiRL: Training In-The-Wild Device-Control Agents with Autonomous Reinforcement Learning. [[Paper]](https://arxiv.org/abs/2406.11896) [[Code]](https://github.com/DigiRL-agent/digirl) `NeurIPS 2024`
1. Digi-Q: Learning VLM Q-Value Functions for Training Device-Control Agents. `ICLR 2025`
1. WebRL: Training LLM Web Agents via Self-Evolving Online Curriculum Reinforcement Learning. [[Paper]](https://arxiv.org/pdf/2411.02337) [[Code]](https://github.com/THUDM/WebRL) `ICLR 2025`
1. MolmoWeb: Open Visual Web Agent and Open Data for the Open Web. [[Paper]](https://arxiv.org/abs/2604.08516) `arXiv 2026`
1. EnterpriseBench Corecraft: Training Generalizable Agents on High-Fidelity RL Environments. [[Paper]](https://arxiv.org/abs/2602.16179) `arXiv 2026`
1. DeepResearcher: Scaling Deep Research via Reinforcement Learning in Real-world Environments. [[Paper]](https://aclanthology.org/2025.emnlp-main.22/) [[Code]](https://github.com/GAIR-NLP/DeepResearcher) `ACL 2025`
1. BrowseComp-V^3: A Visual, Vertical, and Verifiable Benchmark for Multimodal Browsing Agents. [[Paper]](https://arxiv.org/abs/2602.12876) `arXiv 2026`
1. PaLM-E: An Embodied Multimodal Language Model. [[Paper]](https://arxiv.org/pdf/2303.03378.pdf) `ICML 2023`
1. RT-2: Vision-Language-Action Models Transfer Web Knowledge to Robotic Control. [[Paper]](https://proceedings.mlr.press/v229/zitkovich23a.html) `CoRL 2023`
1. PhysiAgent: An Embodied Agent Framework in Physical World. [[Paper]](https://arxiv.org/abs/2509.24524) `arXiv 2025`
#### 4.2.2. Reward Design
##### 4.2.2.1. Outcome-Level Rewards
1. Outcome-based Reinforcement Learning to Predict the Future. `Trans. Mach. Learn. Res. 2025`
1. Agentic Reasoning and Tool Integration for LLMs via Reinforcement Learning. [[Paper]](https://arxiv.org/abs/2505.01441) `arXiv 2025`
1. Agent RL Scaling Law: Agent RL with Spontaneous Code Execution for Mathematical Problem Solving. [[Paper]](https://arxiv.org/abs/2505.07773) `arXiv 2025`
1. ACECODER: Acing Coder RL via Automated Test-Case Synthesis. `ACL 2025`
1. Deepcoder: A fully open-source 14b coder at o3-mini level. `Notion Blog 2025`
1. Deepswe: Training a state-of-the-art coding agent from scratch by scaling rl, 2025. `Notion Blog 2025`
1. Search-R1: Training LLMs to Reason and Leverage Search Engines with Reinforcement Learning. [[Paper]](https://arxiv.org/abs/2503.09516) `arXiv 2025`
1. DeepResearcher: Scaling Deep Research via Reinforcement Learning in Real-world Environments. [[Paper]](https://aclanthology.org/2025.emnlp-main.22/) [[Code]](https://github.com/GAIR-NLP/DeepResearcher) `ACL 2025`
1. Qwen3 Technical Report. [[Paper]](https://arxiv.org/abs/2505.09388) `arXiv 2025`
1. TTRL: Test-Time Reinforcement Learning. [[Paper]](https://arxiv.org/abs/2504.16084) `arXiv 2025`
1. DeepSeek-Prover-V1.5: Harnessing Proof Assistant Feedback for Reinforcement Learning and Monte-Carlo Tree Search. `ICLR 2025`
##### 4.2.2.2. Process-Level Rewards
1. Let's Verify Step by Step. [[Paper]](https://arxiv.org/abs/2305.20050) [[Code]](https://github.com/openai/prm800k) `ICLR 2024`
1. Math-Shepherd: Verify and Reinforce LLMs Step-by-step without Human Annotations. [[Paper]](https://arxiv.org/abs/2312.08935) `ACL 2024`
1. Improve Mathematical Reasoning in Language Models by Automated Process Supervision. [[Paper]](https://arxiv.org/abs/2406.06592) `arXiv 2024`
1. GUI-G^2: Gaussian Reward Modeling for GUI Grounding. `AAAI 2026`
1. ToolRL: Reward is All Tool Learning Needs. [[Paper]](https://arxiv.org/abs/2504.13958) `arXiv 2025`
1. Process Reward Models That Think. [[Paper]](https://arxiv.org/abs/2504.16828) [[Code]](https://github.com/mukhal/thinkprm) `Trans. Mach. Learn. Res. 2026`
#### 4.2.3. Training Optimization Algorithms
##### 4.2.3.1. Supervised Fine-Tuning
1. FireAct: Toward Language Agent Fine-tuning. [[Paper]](https://arxiv.org/abs/2310.05915) [[Code]](https://github.com/anchen1011/FireAct) `arXiv 2023`
1. AgentTuning: Enabling Generalized Agent Abilities for LLMs. [[Paper]](https://arxiv.org/abs/2310.12823) [[Code]](https://github.com/THUDM/AgentTuning) `ACL 2024`
1. Agent-FLAN: Designing Data and Methods of Effective Agent Tuning for Large Language Models. [[Paper]](https://arxiv.org/abs/2403.12881) [[Code]](https://github.com/InternLM/Agent-FLAN) `ACL 2024`
1. AgentOhana: Design Unified Data and Training Pipeline for Effective Agent Learning. [[Paper]](https://arxiv.org/abs/2402.15506) [[Code]](https://github.com/SalesforceAIResearch/xLAM) `arXiv 2024`
1. AgentTrek: Agent Trajectory Synthesis via Guiding Replay with Web Tutorials. [[Paper]](https://arxiv.org/abs/2412.09605) [[Code]](https://agenttrek.github.io/) `ICLR 2025`
1. Expanding the Capability Frontier of LLM Agents with ZPD-Guided Data Synthesis. [[Paper]](https://openreview.net/forum?id=c5bf47nDx1) `ICLR 2026`
1. On Data Engineering for Scaling LLM Terminal Capabilities. [[Paper]](https://arxiv.org/abs/2602.21193) `arXiv 2026`
1. Efficient Agent Training for Computer Use. [[Paper]](https://arxiv.org/abs/2505.13909) `arXiv 2025`
1. Immersion in the GitHub Universe: Scaling Coding Agents to Mastery. [[Paper]](https://doi.org/10.48550/arXiv.2602.09892) `arXiv 2026`
1. ClawGym: A Scalable Framework for Building Effective Claw Agents. [[Paper]](https://arxiv.org/abs/2604.26904) `2026`
1. Merge-of-Thought Distillation. [[Paper]](https://arxiv.org/abs/2509.08814) `arXiv 2025`
1. MAGDi: Structured Distillation of Multi-Agent Interaction Graphs Improves Reasoning in Smaller Language Models. `ICML 2024`
1. Structured Agent Distillation for Large Language Model. [[Paper]](https://arxiv.org/abs/2505.13820) `arXiv 2025`
1. On-Policy Distillation of Language Models: Learning from Self-Generated Mistakes. [[Paper]](https://arxiv.org/abs/2306.13649) `ICLR 2024`
1. MiniLLM: Knowledge Distillation of Large Language Models. `ICLR 2024`
1. Stable On-Policy Distillation through Adaptive Target Reformulation. [[Paper]](https://arxiv.org/abs/2601.07155) `arXiv 2026`
1. Scaling Reasoning Efficiently via Relaxed On-Policy Distillation. [[Paper]](https://arxiv.org/abs/2603.11137) `arXiv 2026`
1. Learning beyond Teacher: Generalized On-Policy Distillation with Reward Extrapolation. [[Paper]](https://arxiv.org/abs/2602.12125) `arXiv 2026`
1. Black-Box On-Policy Distillation of Large Language Models. [[Paper]](https://arxiv.org/abs/2511.10643) `arXiv 2025`
##### 4.2.3.2. Reinforcement Learning Approaches
1. Proximal Policy Optimization Algorithms. [[Paper]](https://arxiv.org/abs/1707.06347) `arXiv 2017`
1. Secrets of RLHF in Large Language Models Part I: PPO. [[Paper]](https://arxiv.org/abs/2307.04964) [[Code]](https://github.com/OpenLMLab/MOSS-RLHF) `arXiv 2023`
1. Secrets of RLHF in Large Language Models Part II: Reward Modeling. [[Paper]](https://arxiv.org/abs/2401.06080) [[Code]](https://github.com/OpenLMLab/MOSS-RLHF) `arXiv 2024`
1. WARP: On the Benefits of Weight Averaged Rewarded Policies. [[Paper]](https://arxiv.org/abs/2406.16768) `arXiv 2024`
1. ArCHer: Training Language Model Agents via Hierarchical Multi-Turn RL. [[Paper]](https://arxiv.org/abs/2402.19446) [[Code]](https://github.com/YifeiZhou02/ArCHer) `ICML 2024`
1. VinePPO: Refining Credit Assignment in RL Training of LLMs. `ICML 2025`
1. LLM Collaboration with Multi-Agent Reinforcement Learning. [[Paper]](https://arxiv.org/abs/2508.04652) `AAAI 2026`
1. Direct Preference Optimization: Your Language Model is Secretly a Reward Model. [[Paper]](https://arxiv.org/abs/2305.18290) [[Code]](https://github.com/eric-mitchell/direct-preference-optimization) `NeurIPS 2023`
1. KTO: Model Alignment as Prospect Theoretic Optimization. [[Paper]](https://arxiv.org/abs/2402.01306) [[Code]](https://github.com/ContextualAI/HALOs) `arXiv 2024`
1. SimPO: Simple Preference Optimization with a Reference-Free Reward. [[Paper]](https://arxiv.org/abs/2405.14734) [[Code]](https://github.com/princeton-nlp/SimPO) `NeurIPS 2024`
1. ORPO: Monolithic Preference Optimization without Reference Model. [[Paper]](https://arxiv.org/abs/2403.07691) [[Code]](https://github.com/xfactlab/orpo) `ACL 2024`
1. DeepSeekMath: Pushing the Limits of Mathematical Reasoning in Open Language Models. [[Paper]](https://arxiv.org/abs/2402.03300) [[Code]](https://github.com/deepseek-ai/DeepSeek-Math) `arXiv 2024`
1. ReMax: A Simple, Effective, and Efficient Reinforcement Learning Method for Aligning Large Language Models. `ICML 2024`
1. RAGEN: Understanding Self-Evolution in LLM Agents via Multi-Turn Reinforcement Learning. [[Paper]](https://arxiv.org/abs/2504.20073) [[Code]](https://github.com/RAGEN-AI/RAGEN) `arXiv 2025`
1. Group-in-Group Policy Optimization for LLM Agent Training. [[Paper]](https://arxiv.org/abs/2505.10978) [[Code]](https://github.com/langfengQ/verl-agent) `arXiv 2025`
1. Tree Search for LLM Agent Reinforcement Learning. [[Paper]](https://arxiv.org/abs/2509.21240) `arXiv 2025`
1. DAPO: An Open-Source LLM Reinforcement Learning System at Scale. [[Paper]](https://arxiv.org/abs/2503.14476) [[Code]](https://github.com/BytedTsinghua-SIA/DAPO) `arXiv 2025`
1. Kimi k1.5: Scaling Reinforcement Learning with LLMs. [[Paper]](https://arxiv.org/abs/2501.12599) `arXiv 2025`
1. Agentic Reinforced Policy Optimization. [[Paper]](https://arxiv.org/abs/2507.19849) [[Code]](https://github.com/dongguanting/ARPO) `arXiv 2025`
1. ML-Agent: Reinforcing LLM Agents for Autonomous Machine Learning Engineering. [[Paper]](https://openreview.net/forum?id=AEgyitdRWf) `arXiv 2025`
#### 4.2.4. Infrastructure
##### 4.2.4.1. General-Purpose Frameworks
1. OpenRLHF: An Easy-to-use, Scalable and High-performance RLHF Framework. [[Paper]](https://arxiv.org/abs/2405.11143) [[Code]](https://github.com/OpenRLHF/OpenRLHF) `arXiv 2024`
1. ReaL: Efficient RLHF Training of Large Language Models with Parameter Reallocation. [[Paper]](https://arxiv.org/abs/2406.14088) [[Code]](https://github.com/openpsi-project/ReaLHF) `arXiv 2024`
1. HybridFlow: A Flexible and Efficient RLHF Framework. [[Paper]](https://arxiv.org/abs/2409.19256) [[Code]](https://github.com/volcengine/verl) `EuroSys 2025`
1. NeMo-Aligner: Scalable Toolkit for Efficient Model Alignment. [[Paper]](https://arxiv.org/abs/2405.01481) [[Code]](https://github.com/NVIDIA/NeMo-Aligner) `arXiv 2024`
1. AReaL: A Large-Scale Asynchronous Reinforcement Learning System for Language Reasoning. [[Paper]](https://arxiv.org/abs/2505.24298) [[Code]](https://github.com/inclusionAI/AReaL) `arXiv 2025`
1. Open-Reasoner-Zero: An Open Source Approach to Scaling Up Reinforcement Learning on the Base Model. [[Paper]](https://arxiv.org/abs/2503.24290) `arXiv 2025`
1. AgentGym: Evolving Large Language Model-based Agents across Diverse Environments. [[Paper]](https://arxiv.org/abs/2406.04151) [[Code]](https://github.com/WooooDyy/AgentGym) `arXiv 2024`
1. GEM: A Gym for Agentic LLMs. [[Paper]](https://arxiv.org/abs/2510.01051) [[Code]](https://github.com/axon-rl/gem) `arXiv 2025`
1. RAGEN: Understanding Self-Evolution in LLM Agents via Multi-Turn Reinforcement Learning. [[Paper]](https://arxiv.org/abs/2504.20073) [[Code]](https://github.com/RAGEN-AI/RAGEN) `arXiv 2025`
1. Group-in-Group Policy Optimization for LLM Agent Training. [[Paper]](https://arxiv.org/abs/2505.10978) [[Code]](https://github.com/langfengQ/verl-agent) `arXiv 2025`
1. Agent Lightning: Train ANY AI Agents with Reinforcement Learning. [[Paper]](https://arxiv.org/abs/2508.03680) [[Code]](https://github.com/microsoft/agent-lightning) `arXiv 2025`
1. AgentGym-RL: Training LLM Agents for Long-Horizon Decision Making through Multi-Turn Reinforcement Learning. [[Paper]](https://arxiv.org/abs/2509.08755) `arXiv 2025`
1. AgentRL: Scaling Agentic Reinforcement Learning with a Multi-Turn, Multi-Task Framework. [[Paper]](https://arxiv.org/abs/2510.04206) `arXiv 2025`
1. Agent-R1: Training Powerful LLM Agents with End-to-End Reinforcement Learning. [[Paper]](https://arxiv.org/abs/2511.14460) [[Code]](https://github.com/AgentR1/Agent-R1) `arXiv 2025`
1. RollArt: Scaling Agentic RL Training via Disaggregated Infrastructure. [[Paper]](https://arxiv.org/abs/2512.22560) `arXiv 2025`
1. SkyRL-Agent: Efficient RL Training for Multi-turn LLM Agent. [[Paper]](https://arxiv.org/abs/2511.16108) [[Code]](https://github.com/NovaSky-AI/SkyRL) `arXiv 2025`
##### 4.2.4.2. Specialized Frameworks
1. Dr. MAS: Stable Reinforcement Learning for Multi-Agent LLM Systems. [[Paper]](https://arxiv.org/abs/2602.08847) `arXiv 2026`
1. marti zhang iclr 2026. `ICLR 2026`
1. LLM Collaboration with Multi-Agent Reinforcement Learning. [[Paper]](https://arxiv.org/abs/2508.04652) `AAAI 2026`
1. WideSeek-R1: Exploring Width Scaling for Broad Information Seeking via Multi-Agent Reinforcement Learning. [[Paper]](https://arxiv.org/abs/2602.04634) `arXiv 2026`
1. GrandCode: Achieving Grandmaster Level in Competitive Programming via Agentic Reinforcement Learning. [[Paper]](https://arxiv.org/abs/2604.02721) `arXiv 2026`
1. Multimodal Reinforcement Learning with Agentic Verifier for AI Agents. [[Paper]](https://arxiv.org/abs/2512.03438) `arXiv 2025`
1. MM-DeepResearch: A Simple and Effective Multimodal Agentic Search Baseline. [[Paper]](https://arxiv.org/abs/2603.01050) `arXiv 2026`

## 5. Harness Capacity and Evaluation
1. WebArena: A Realistic Web Environment for Building Autonomous Agents. [[Paper]](https://arxiv.org/pdf/2307.13854) [[Code]](https://github.com/web-arena-x/webarena) `ICLR 2024`
1. WorkArena: How Capable are Web Agents at Solving Common Knowledge Work Tasks?. [[Paper]](https://arxiv.org/pdf/2403.07718) [[Code]](https://github.com/ServiceNow/WorkArena) `ICML 2024`
1. OSWorld: Benchmarking Multimodal Agents for Open-Ended Tasks in Real Computer Environments. [[Paper]](https://arxiv.org/pdf/2404.07972) [[Code]](https://github.com/xlang-ai/OSWorld) `NeurIPS 2024`
1. tau-bench: A Benchmark for Tool-Agent-User Interaction in Real-World Domains. [[Paper]](https://arxiv.org/pdf/2406.12045) [[Code]](https://github.com/sierra-research/tau-bench) `arXiv 2024`
1. AppWorld: A Controllable World of Apps and People for Benchmarking Interactive Coding Agents. [[Paper]](https://arxiv.org/pdf/2407.18901) [[Code]](https://github.com/StonyBrookNLP/appworld) `ACL 2024`
1. Characterizing Deep Research: A Benchmark and Formal Definition. [[Paper]](https://arxiv.org/pdf/2508.04183) [[Code]](https://github.com/microsoft/LiveDRBench) `arXiv 2025`
1. The Berkeley Function Calling Leaderboard (BFCL): From Tool Use to Agentic Evaluation of Large Language Models. [[Paper]](https://openreview.net/pdf?id=2GmDdhBdDk) [[Code]](https://github.com/ShishirPatil/gorilla/tree/main/berkeley-function-call-leaderboard) `ICML 2025`
1. LiveCodeBench: Holistic and Contamination Free Evaluation of Large Language Models for Code. [[Paper]](https://arxiv.org/pdf/2403.07974) [[Code]](https://github.com/LiveCodeBench/LiveCodeBench) `ICLR 2025`
1. PaperBench: Evaluating AI's Ability to Replicate AI Research. [[Paper]](https://arxiv.org/pdf/2504.01848) [[Code]](https://github.com/openai/preparedness) `ICML 2025`
1. IDRBench: Interactive Deep Research Benchmark. [[Paper]](https://doi.org/10.48550/arXiv.2601.06676) `arXiv 2026`
1. DeepResearch Bench II: Diagnosing Deep Research Agents via Rubrics from Expert Report. [[Paper]](https://doi.org/10.48550/arXiv.2601.08536) `arXiv 2026`
1. OmniCode: A Benchmark for Evaluating Software Engineering Agents. [[Paper]](https://doi.org/10.48550/arXiv.2602.02262) `arXiv 2026`
1. Live API-Bench: 2500+ Live APIs for Testing Multi-Step Tool Calling. [[Paper]](https://aclanthology.org/2026.eacl-long.143/) `ACL 2026`
1. MMBench-GUI: Hierarchical Multi-Platform Evaluation Framework for GUI Agents. [[Paper]](https://doi.org/10.48550/arXiv.2507.19478) `arXiv 2025`
1. TimeSeriesGym: A Scalable Benchmark for (Time Series) Machine Learning Engineering Agents. [[Paper]](https://doi.org/10.48550/arXiv.2505.13291) `arXiv 2025`

### 5.1. Deep Research
##### 5.1.1. Broad and Complex Search
1. BrowseComp: A Simple Yet Challenging Benchmark for Browsing Agents. [[Paper]](https://doi.org/10.48550/arXiv.2504.12516) `arXiv 2025`
1. Characterizing Deep Research: A Benchmark and Formal Definition. [[Paper]](https://arxiv.org/pdf/2508.04183) [[Code]](https://github.com/microsoft/LiveDRBench) `arXiv 2025`
1. WideSearch: Benchmarking Agentic Broad Info-Seeking. [[Paper]](https://doi.org/10.48550/arXiv.2508.07999) `arXiv 2025`
1. IDRBench: Interactive Deep Research Benchmark. [[Paper]](https://doi.org/10.48550/arXiv.2601.06676) `arXiv 2026`
##### 5.1.2. Research Reports
1. DeepResearch Bench: A Comprehensive Benchmark for Deep Research Agents. [[Paper]](https://arxiv.org/pdf/2506.11763) [[Code]](https://github.com/Ayanami0730/deep_research_bench) `arXiv 2025`
1. ReportBench: Evaluating Deep Research Agents via Academic Survey Tasks. [[Paper]](https://arxiv.org/pdf/2508.15804) [[Code]](https://github.com/ByteDance-BandAI/ReportBench) `arXiv 2025`
1. LiveResearchBench: A Live Benchmark for User-Centric Deep Research in the Wild. [[Paper]](https://arxiv.org/pdf/2510.14240) [[Code]](https://github.com/SalesforceAIResearch/LiveResearchBench) `arXiv 2025`
1. DeepResearch Bench II: Diagnosing Deep Research Agents via Rubrics from Expert Report. [[Paper]](https://doi.org/10.48550/arXiv.2601.08536) `arXiv 2026`
1. Towards Personalized Deep Research: Benchmarks and Evaluations. [[Paper]](https://doi.org/10.48550/arXiv.2509.25106) `arXiv 2025`
1. Watching, Reasoning, and Searching: A Video Deep Research Benchmark on Open Web for Agentic Video Reasoning. [[Paper]](https://doi.org/10.48550/arXiv.2601.06943) `arXiv 2026`
1. MMDeepResearch-Bench: A Benchmark for Multimodal Deep Research Agents. [[Paper]](https://doi.org/10.48550/arXiv.2601.12346) `arXiv 2026`
##### 5.1.3. Survey Generation and Evaluation
1. ResearchRubrics: A Benchmark of Prompts and Rubrics For Evaluating Deep Research Agents. [[Paper]](https://arxiv.org/pdf/2511.07685) [[Code]](https://github.com/scaleapi/researchrubrics) `arXiv 2025`
1. DeepResearch Bench II: Diagnosing Deep Research Agents via Rubrics from Expert Report. [[Paper]](https://doi.org/10.48550/arXiv.2601.08536) `arXiv 2026`
1. Towards Personalized Deep Research: Benchmarks and Evaluations. [[Paper]](https://doi.org/10.48550/arXiv.2509.25106) `arXiv 2025`
### 5.2. Software Engineering
##### 5.2.1. Repository Tasks
1. RepoBench: Benchmarking Repository-Level Code Auto-Completion Systems. [[Paper]](https://arxiv.org/pdf/2306.03091) [[Code]](https://github.com/Leolty/repobench) `ICLR 2024`
1. CodeAgent: Enhancing Code Generation with Tool-Integrated Agent Systems for Real-World Repo-level Coding Challenges. [[Paper]](https://arxiv.org/pdf/2401.07339) `ACL 2024`
1. Can Language Models Replace Programmers for Coding? REPOCOD Says 'Not Yet'. [[Paper]](https://aclanthology.org/2025.acl-long.1204/) `ACL 2025`
1. LoCoBench-Agent: An Interactive Benchmark for LLM Agents in Long-Context Software Engineering. [[Paper]](https://doi.org/10.48550/arXiv.2511.13998) `arXiv 2025`
##### 5.2.2. Issue Resolution
1. SWE-bench: Can Language Models Resolve Real-world Github Issues?. [[Paper]](https://arxiv.org/abs/2310.06770) [[Code]](https://github.com/SWE-bench/SWE-bench) `ICLR 2024`
1. SWE-Bench Pro: Can AI Agents Solve Long-Horizon Software Engineering Tasks?. [[Paper]](https://doi.org/10.48550/arXiv.2509.16941) `arXiv 2025`
1. LiveCodeBench: Holistic and Contamination Free Evaluation of Large Language Models for Code. [[Paper]](https://arxiv.org/pdf/2403.07974) [[Code]](https://github.com/LiveCodeBench/LiveCodeBench) `ICLR 2025`
1. SWE-Bench++: A Framework for the Scalable Generation of Software Engineering Benchmarks from Open-Source Repositories. [[Paper]](https://doi.org/10.48550/arXiv.2512.17419) `arXiv 2025`
1. SWE-Sharp-Bench: A Reproducible Benchmark for C# Software Engineering Tasks. [[Paper]](https://doi.org/10.1109/AIware69974.2025.00039) `2nd IEEE/ACM International Confere 2025`
##### 5.2.3. Broader Engineering Workflows
1. NL2Repo-Bench: Towards Long-Horizon Repository Generation Evaluation of Coding Agents. [[Paper]](https://doi.org/10.48550/arXiv.2512.12730) `arXiv 2025`
1. FeatureBench: Benchmarking Agentic Coding for Complex Feature Development. [[Paper]](https://arxiv.org/pdf/2602.10975) [[Code]](https://github.com/LiberCoders/FeatureBench) `arXiv 2026`
1. BeyondSWE: Can Current Code Agent Survive Beyond Single-Repo Bug Fixing?. [[Paper]](https://arxiv.org/abs/2603.03194) `arXiv 2026`
1. OmniCode: A Benchmark for Evaluating Software Engineering Agents. [[Paper]](https://doi.org/10.48550/arXiv.2602.02262) `arXiv 2026`
### 5.3. Tool Use and Function Calling
##### 5.3.1. Function Calling
1. API-Bank: A Comprehensive Benchmark for Tool-Augmented LLMs. [[Paper]](https://arxiv.org/pdf/2304.08244) [[Code]](https://github.com/AlibabaResearch/DAMO-ConvAI/tree/main/api-bank) `ACL 2023`
1. The Berkeley Function Calling Leaderboard (BFCL): From Tool Use to Agentic Evaluation of Large Language Models. [[Paper]](https://openreview.net/pdf?id=2GmDdhBdDk) [[Code]](https://github.com/ShishirPatil/gorilla/tree/main/berkeley-function-call-leaderboard) `ICML 2025`
1. Live API-Bench: 2500+ Live APIs for Testing Multi-Step Tool Calling. [[Paper]](https://aclanthology.org/2026.eacl-long.143/) `ACL 2026`
##### 5.3.2. Tool Use
1. ToolLLM: Facilitating Large Language Models to Master 16000+ Real-world APIs. [[Paper]](https://arxiv.org/pdf/2307.16789) [[Code]](https://github.com/OpenBMB/ToolBench) `ICLR 2024`
1. AgentBench: Evaluating LLMs as Agents. [[Paper]](https://arxiv.org/pdf/2308.03688) [[Code]](https://github.com/THUDM/AgentBench) `ICLR 2024`
1. GAIA: a benchmark for General AI Assistants. [[Paper]](https://arxiv.org/pdf/2311.12983) [[Code]](https://huggingface.co/gaia-benchmark) `ICLR 2024`
1. ToolHop: A Query-Driven Benchmark for Evaluating Large Language Models in Multi-Hop Tool Use. [[Paper]](https://aclanthology.org/2025.acl-long.150/) `ACL 2025`
##### 5.3.3. Stateful Interaction
1. tau-bench: A Benchmark for Tool-Agent-User Interaction in Real-World Domains. [[Paper]](https://arxiv.org/pdf/2406.12045) [[Code]](https://github.com/sierra-research/tau-bench) `arXiv 2024`
1. AppWorld: A Controllable World of Apps and People for Benchmarking Interactive Coding Agents. [[Paper]](https://arxiv.org/pdf/2407.18901) [[Code]](https://github.com/StonyBrookNLP/appworld) `ACL 2024`
1. AssistantBench: Can Web Agents Solve Realistic and Time-Consuming Tasks?. [[Paper]](https://arxiv.org/pdf/2407.15711) [[Code]](https://github.com/oriyor/assistantbench) `ACL 2024`
1. Toolsandbox: A stateful, conversational, interactive evaluation benchmark for llm tool use capabilities. [[Paper]](https://arxiv.org/pdf/2408.04682) [[Code]](https://github.com/apple/ToolSandbox) `ACL Findings 2025`
1. tau^2-Bench: Evaluating Conversational Agents in a Dual-Control Environment. [[Paper]](https://arxiv.org/pdf/2506.07982) [[Code]](https://github.com/sierra-research/tau2-bench) `arXiv 2025`
1. DICE-BENCH: Evaluating the Tool-Use Capabilities of Large Language Models in Multi-Round, Multi-Party Dialogues. [[Paper]](https://aclanthology.org/2025.findings-acl.1375/) `ACL Findings 2025`
1. CCTU: A Benchmark for Tool Use under Complex Constraints. [[Paper]](https://doi.org/10.48550/arXiv.2603.15309) `arXiv 2026`
### 5.4. Computer Use and GUI Grounding
##### 5.4.1. Web Navigation
1. Mind2Web: Towards a Generalist Agent for the Web. [[Paper]](https://arxiv.org/pdf/2306.06070) [[Code]](https://github.com/OSU-NLP-Group/Mind2Web) `NeurIPS 2023`
1. WebArena: A Realistic Web Environment for Building Autonomous Agents. [[Paper]](https://arxiv.org/pdf/2307.13854) [[Code]](https://github.com/web-arena-x/webarena) `ICLR 2024`
##### 5.4.2. Computer Use
1. VisualWebArena: Evaluating Multimodal Agents on Realistic Visual Web Tasks. [[Paper]](https://arxiv.org/pdf/2401.13649) [[Code]](https://github.com/web-arena-x/visualwebarena) `ACL 2024`
1. WorkArena: How Capable are Web Agents at Solving Common Knowledge Work Tasks?. [[Paper]](https://arxiv.org/pdf/2403.07718) [[Code]](https://github.com/ServiceNow/WorkArena) `ICML 2024`
1. Android in the Wild: A Large-Scale Dataset for Android Device Control. [[Paper]](https://arxiv.org/pdf/2307.10088) [[Code]](https://github.com/google-research/google-research/tree/master/android_in_the_wild) `arXiv 2023`
1. OSWorld: Benchmarking Multimodal Agents for Open-Ended Tasks in Real Computer Environments. [[Paper]](https://arxiv.org/pdf/2404.07972) [[Code]](https://github.com/xlang-ai/OSWorld) `NeurIPS 2024`
1. AndroidWorld: A Dynamic Benchmarking Environment for Autonomous Agents. [[Paper]](https://arxiv.org/pdf/2405.14573) [[Code]](https://github.com/google-research/android_world) `ICLR 2025`
1. Windows Agent Arena: Evaluating Multi-Modal OS Agents at Scale. [[Paper]](https://arxiv.org/pdf/2409.08264) [[Code]](https://github.com/microsoft/WindowsAgentArena) `ICML 2025`
1. WorldGUI: An Interactive Benchmark for Desktop GUI Automation from Any Starting Point. [[Paper]](https://doi.org/10.48550/arXiv.2502.08047) `arXiv 2025`
##### 5.4.3. GUI Grounding
1. ScreenSpot-Pro: GUI Grounding for Professional High-Resolution Computer Use. [[Paper]](https://arxiv.org/pdf/2504.07981) [[Code]](https://github.com/likaixin2000/ScreenSpot-Pro-GUI-Grounding) `Proceedings of the 33rd ACM Intern 2025`
1. Osworld-mcp: Benchmarking mcp tool invocation in computer-use agents. [[Paper]](https://arxiv.org/pdf/2510.24563) [[Code]](https://github.com/X-PLUG/OSWorld-MCP) `arXiv 2025`
1. VenusBench-GD: A Comprehensive Multi-Platform GUI Benchmark for Diverse Grounding Tasks. [[Paper]](https://doi.org/10.48550/arXiv.2512.16501) `arXiv 2025`
1. MMBench-GUI: Hierarchical Multi-Platform Evaluation Framework for GUI Agents. [[Paper]](https://doi.org/10.48550/arXiv.2507.19478) `arXiv 2025`
### 5.5. ML Engineering and Scientific Research
##### 5.5.1. ML Experimentation
1. DS-1000: A Natural and Reliable Benchmark for Data Science Code Generation. [[Paper]](https://arxiv.org/pdf/2211.11501) [[Code]](https://github.com/xlang-ai/DS-1000) `ICML 2023`
1. MLAgentBench: Evaluating Language Agents on Machine Learning Experimentation. [[Paper]](https://arxiv.org/pdf/2310.03302) [[Code]](https://github.com/snap-stanford/MLAgentBench) `ICML 2024`
1. TimeSeriesGym: A Scalable Benchmark for (Time Series) Machine Learning Engineering Agents. [[Paper]](https://doi.org/10.48550/arXiv.2505.13291) `arXiv 2025`
##### 5.5.2. Scientific Workflows
1. DA-Code: Agent Data Science Code Generation Benchmark for Large Language Models. [[Paper]](https://arxiv.org/pdf/2410.07331) [[Code]](https://github.com/yiyihum/da-code) `ACL 2024`
1. ScienceAgentBench: Toward Rigorous Assessment of Language Agents for Data-Driven Scientific Discovery. [[Paper]](https://arxiv.org/pdf/2410.05080) [[Code]](https://github.com/OSU-NLP-Group/ScienceAgentBench) `ICLR 2025`
1. MLE-bench: Evaluating Machine Learning Agents on Machine Learning Engineering. [[Paper]](https://arxiv.org/pdf/2410.07095) [[Code]](https://github.com/openai/mle-bench) `ICLR 2025`
1. ResearchBench: Benchmarking LLMs in Scientific Discovery via Inspiration-Based Task Decomposition. [[Paper]](https://doi.org/10.48550/arXiv.2503.21248) `arXiv 2025`
##### 5.5.3. Research Replication
1. PaperBench: Evaluating AI's Ability to Replicate AI Research. [[Paper]](https://arxiv.org/pdf/2504.01848) [[Code]](https://github.com/openai/preparedness) `ICML 2025`
1. MLR-Bench: Evaluating AI Agents on Open-Ended Machine Learning Research. [[Paper]](https://arxiv.org/pdf/2505.19955) [[Code]](https://github.com/chchenhui/mlrbench) `arXiv 2025`
1. FML-bench: Benchmarking Machine Learning Agents for Scientific Research. [[Paper]](https://arxiv.org/pdf/2510.10472) [[Code]](https://github.com/qrzou/FML-bench) `arXiv 2025`
1. ReplicatorBench: Benchmarking LLM Agents for Replicability in Social and Behavioral Sciences. [[Paper]](https://arxiv.org/pdf/2602.11354) [[Code]](https://github.com/CenterForOpenScience/llm-benchmarking) `arXiv 2026`
1. SWE-bench: Can Language Models Resolve Real-world Github Issues?. [[Paper]](https://arxiv.org/abs/2310.06770) [[Code]](https://github.com/SWE-bench/SWE-bench) `ICLR 2024`
1. MLE-bench: Evaluating Machine Learning Agents on Machine Learning Engineering. [[Paper]](https://arxiv.org/pdf/2410.07095) [[Code]](https://github.com/openai/mle-bench) `ICLR 2025`
1. tau-bench: A Benchmark for Tool-Agent-User Interaction in Real-World Domains. [[Paper]](https://arxiv.org/pdf/2406.12045) [[Code]](https://github.com/sierra-research/tau-bench) `arXiv 2024`
1. ResearchRubrics: A Benchmark of Prompts and Rubrics For Evaluating Deep Research Agents. [[Paper]](https://arxiv.org/pdf/2511.07685) [[Code]](https://github.com/scaleapi/researchrubrics) `arXiv 2025`
1. TRAJECT-Bench: A Trajectory-Aware Benchmark for Evaluating Agentic Tool Use. [[Paper]](https://arxiv.org/abs/2510.04550) `arXiv 2025`
1. DeepResearch Bench II: Diagnosing Deep Research Agents via Rubrics from Expert Report. [[Paper]](https://doi.org/10.48550/arXiv.2601.08536) `arXiv 2026`
1. IDRBench: Interactive Deep Research Benchmark. [[Paper]](https://doi.org/10.48550/arXiv.2601.06676) `arXiv 2026`
1. OmniCode: A Benchmark for Evaluating Software Engineering Agents. [[Paper]](https://doi.org/10.48550/arXiv.2602.02262) `arXiv 2026`

## 6. Future Directions
### 6.1. Efficiency
1. RouteLLM: Learning to Route LLMs from Preference Data. [[Paper]](https://openreview.net/forum?id=8sSqNntaMr) `ICLR 2025`
1. Chain of Thoughtlessness? An Analysis of CoT in Planning. [[Paper]](https://proceedings.neurips.cc/paper_files/paper/2024/file/3365d974ce309623bd8151082d78206c-Paper-Conference.pdf) [[Code]](https://github.com/karthikv792/cot-planning) `NeurIPS 2024`
1. ACON: Optimizing Context Compression for Long-horizon LLM Agents. [[Paper]](https://arxiv.org/pdf/2510.00615) [[Code]](https://github.com/microsoft/acon) `arXiv 2025`
1. Reducing Cost of LLM Agents with Trajectory Reduction. [[Paper]](https://arxiv.org/abs/2509.23586) `arXiv 2025`
1. ARC: Active and Reflection-driven Context Management for Long-Horizon Information Seeking Agents. [[Paper]](https://doi.org/10.48550/arXiv.2601.12030) `arXiv 2026`
1. Context as a Tool: Context Management for Long-Horizon SWE-Agents. [[Paper]](https://doi.org/10.48550/arXiv.2512.22087) `arXiv 2025`
1. Robust and Efficient Tool Orchestration via Layered Execution Structures with Reflective Correction. [[Paper]](https://arxiv.org/abs/2602.18968) `arXiv 2026`
### 6.2. Safety
1. AgentDojo: A Dynamic Environment to Evaluate Prompt Injection Attacks and Defenses for LLM Agents. [[Paper]](https://proceedings.neurips.cc/paper_files/paper/2024/file/97091a5177d8dc64b1da8bf3e1f6fb54-Paper-Datasets_and_Benchmarks_Track.pdf) `NeurIPS 2024`
1. MCPTox: A Benchmark for Tool Poisoning Attack on Real-World MCP Servers. [[Paper]](https://arxiv.org/abs/2508.14925) `2025`
1. AgentSys: Secure and Dynamic LLM Agents Through Explicit Hierarchical Memory Management. [[Paper]](https://arxiv.org/abs/2602.07398) `arXiv 2026`
1. OpenPort Protocol: A Security Governance Specification for AI Agent Tool Access. [[Paper]](https://arxiv.org/abs/2602.20196) `arXiv 2026`
1. Runtime Governance for AI Agents: Policies on Paths. [[Paper]](https://arxiv.org/abs/2603.16586) `arXiv 2026`
1. AgentSpec: Customizable runtime enforcement for safe and reliable LLM agents.(2026). [[Paper]](https://arxiv.org/abs/2503.18666) `Proceedings of the IEEE/ACM Intern 2026`
1. Autonomous Action Runtime Management(AARM):A System Specification for Securing AI-Driven Actions at Runtime. [[Paper]](https://doi.org/10.48550/arXiv.2602.09433) `arXiv 2026`
1. SafeHarness: Lifecycle-Integrated Security Architecture for LLM-based Agent Deployment. [[Paper]](https://arxiv.org/abs/2604.13630) `2026`
### 6.3. Continual Learning
1. MemGPT: Towards LLMs as Operating Systems. [[Paper]](https://arxiv.org/pdf/2310.08560) [[Code]](https://research.memgpt.ai/) `arXiv 2023`
1. A-Mem: Agentic Memory for LLM Agents. [[Paper]](https://arxiv.org/pdf/2502.12110) [[Code]](https://github.com/WujiangXu/A-mem) `NeurIPS 2025`
1. Memory as Action: Autonomous Context Curation for Long-Horizon Agentic Tasks. [[Paper]](https://doi.org/10.48550/arXiv.2510.12635) `arXiv 2025`
1. Context Engineering: Memory, Compaction, and Tool Clearing. [[Paper]](https://platform.claude.com/cookbook/tool-use-context-engineering-context-engineering-tools) `2026`
1. Agent Workflow Memory. [[Paper]](https://arxiv.org/pdf/2409.07429) [[Code]](https://github.com/zorazrw/agent-workflow-memory) `ICML 2025`
### 6.4. State and Environment Modeling
1. WorldCoder, a Model-Based LLM Agent: Building World Models by Writing Code and Interacting with the Environment. [[Paper]](https://proceedings.neurips.cc/paper_files/paper/2024/hash/820c61a0cd419163ccbd2c33b268816e-Abstract-Conference.html) `NeurIPS 2024`
1. PABU: Progress-Aware Belief Update for Efficient LLM Agents. [[Paper]](https://arxiv.org/abs/2602.09138) `2026`
1. Agent-World: Scaling Real-World Environment Synthesis for Evolving General Agent Intelligence. [[Paper]](https://arxiv.org/abs/2604.18292) `2026`
### 6.5. Embodied Harnesses
1. PaLM-E: An Embodied Multimodal Language Model. [[Paper]](https://arxiv.org/pdf/2303.03378.pdf) `ICML 2023`
1. RT-2: Vision-Language-Action Models Transfer Web Knowledge to Robotic Control. [[Paper]](https://proceedings.mlr.press/v229/zitkovich23a.html) `CoRL 2023`
1. Green-VLA: Staged Vision-Language-Action Model for Generalist Robots. [[Paper]](https://arxiv.org/abs/2602.00919) `arXiv 2026`
1. ACoT-VLA: Action Chain-of-Thought for Vision-Language-Action Models. [[Paper]](https://arxiv.org/abs/2601.11404) `arXiv 2026`
1. ST4VLA: Spatially Guided Training for Vision-Language-Action Models. [[Paper]](https://arxiv.org/abs/2602.10109) `arXiv 2026`
1. RoboAgent: Chaining Basic Capabilities for Embodied Task Planning. [[Paper]](https://arxiv.org/abs/2604.07774) `2026`
1. EmbodiedBench: Comprehensive Benchmarking Multi-modal Large Language Models for Vision-Driven Embodied Agents. `ICML 2025`
1. AgentSpec: Customizable Runtime Enforcement for Safe and Reliable LLM Agents. [[Paper]](https://arxiv.org/abs/2503.18666) `arXiv 2025`
### 6.6. Evaluation
1. BrowseComp-V^3: A Visual, Vertical, and Verifiable Benchmark for Multimodal Browsing Agents. [[Paper]](https://arxiv.org/abs/2602.12876) `arXiv 2026`
1. OSWorld: Benchmarking Multimodal Agents for Open-Ended Tasks in Real Computer Environments. [[Paper]](https://arxiv.org/pdf/2404.07972) [[Code]](https://github.com/xlang-ai/OSWorld) `NeurIPS 2024`
1. PaperBench: Evaluating AI's Ability to Replicate AI Research. [[Paper]](https://arxiv.org/pdf/2504.01848) [[Code]](https://github.com/openai/preparedness) `ICML 2025`
1. ReplicatorBench: Benchmarking LLM Agents for Replicability in Social and Behavioral Sciences. [[Paper]](https://arxiv.org/pdf/2602.11354) [[Code]](https://github.com/CenterForOpenScience/llm-benchmarking) `arXiv 2026`
1. BeyondSWE: Can Current Code Agent Survive Beyond Single-Repo Bug Fixing?. [[Paper]](https://arxiv.org/abs/2603.03194) `arXiv 2026`
1. Gaia-2: A controllable multi-view generative world model for autonomous driving. [[Paper]](https://arxiv.org/abs/2503.20523) `arXiv 2025`
1. Claw-Eval-Live: A Live Agent Benchmark for Evolving Real-World Workflows. [[Paper]](https://arxiv.org/abs/2604.28139) `2026`
1. ResearchRubrics: A Benchmark of Prompts and Rubrics For Evaluating Deep Research Agents. [[Paper]](https://arxiv.org/pdf/2511.07685) [[Code]](https://github.com/scaleapi/researchrubrics) `arXiv 2025`
1. Osworld-mcp: Benchmarking mcp tool invocation in computer-use agents. [[Paper]](https://arxiv.org/pdf/2510.24563) [[Code]](https://github.com/X-PLUG/OSWorld-MCP) `arXiv 2025`
1. AgentLongBench: A Controllable Long Benchmark For Long-Contexts Agents via Environment Rollouts. [[Paper]](https://arxiv.org/abs/2601.20730) `2026`
1. ATBench: A Diverse and Realistic Agent Trajectory Benchmark for Safety Evaluation and Diagnosis. [[Paper]](https://arxiv.org/abs/2604.02022) `2026`
1. AgentLeak: A Full-Stack Benchmark for Privacy Leakage in Multi-Agent LLM Systems. [[Paper]](https://arxiv.org/abs/2602.11510) `2026`
1. Benchmark Test-Time Scaling of General LLM Agents. [[Paper]](https://arxiv.org/abs/2602.18998) `2026`

## 7. Representative Benchmarks by Task Domain

### 7.1. Deep Research
1. BrowseComp: A Simple Yet Challenging Benchmark for Browsing Agents. [[Paper]](https://doi.org/10.48550/arXiv.2504.12516) [[Code]](https://github.com/openai/simple-evals) `2025.04` - Browsing-based information seeking; Rule-based
1. IDRBench: Interactive Deep Research Benchmark. [[Paper]](https://doi.org/10.48550/arXiv.2601.06676) `2025.05` - Web research; Rule-based
1. IDRBench: Interactive Deep Research Benchmark. [[Paper]](https://doi.org/10.48550/arXiv.2601.06676) [[Code]](https://github.com/Ayanami0730/deep_research_bench) `2025.06` - Deep research report generation; Rule-based
1. ReportBench: Evaluating Deep Research Agents via Academic Survey Tasks. [[Paper]](https://arxiv.org/pdf/2508.15804) [[Code]](https://github.com/ByteDance-BandAI/ReportBench) `2025.08` - Academic survey / report generation; Rule-based
1. Characterizing Deep Research: A Benchmark and Formal Definition. [[Paper]](https://arxiv.org/pdf/2508.04183) [[Code]](https://github.com/microsoft/LiveDRBench) `2025.08` - Deep research benchmarking; Rule-based
1. WideSearch: Benchmarking Agentic Broad Info-Seeking. [[Paper]](https://doi.org/10.48550/arXiv.2508.07999) [[Code]](https://github.com/ByteDance-Seed/WideSearch) `2025.08` - Agentic broad information seeking; Rule-based
1. LiveResearchBench: A Live Benchmark for User-Centric Deep Research in the Wild. [[Paper]](https://arxiv.org/pdf/2510.14240) [[Code]](https://github.com/SalesforceAIResearch/LiveResearchBench) `2025.10` - User-centric deep research in the wild; LLM Judge
1. ResearchRubrics: A Benchmark of Prompts and Rubrics For Evaluating Deep Research Agents. [[Paper]](https://arxiv.org/pdf/2511.07685) [[Code]](https://github.com/scaleapi/researchrubrics) `2025.11` - Prompt-and-rubric-based deep research evaluation; LLM Judge / Human Judge
1. DeepSynth-Eval: Objectively Evaluating Information Consolidation in Deep Survey Writing. [[Paper]](https://arxiv.org/pdf/2601.03540) `2026.01` - Information consolidation in deep survey writing; Rule-based
1. DeepResearch Bench II: Diagnosing Deep Research Agents via Rubrics from Expert Report. [[Paper]](https://doi.org/10.48550/arXiv.2601.08536) [[Code]](https://github.com/imlrz/DeepResearch-Bench-II) `2026.01` - Rubric-based diagnosis of deep research reports; Rule-based
1. MMDeepResearch-Bench: A Benchmark for Multimodal Deep Research Agents. [[Paper]](https://doi.org/10.48550/arXiv.2601.12346) [[Code]](https://github.com/AIoT-MLSys-Lab/MMDeepResearch-Bench) `2026.01` - Multimodal deep research; Rule-based / LLM Judge
1. DeepSurvey-Bench: Evaluating Academic Value of Automatically Generated Scientific Survey. [[Paper]](https://arxiv.org/pdf/2601.15307) `2026.01` - Academic value of generated scientific surveys; Human Judge

### 7.2. Software Engineering
1. RepoBench: Benchmarking Repository-Level Code Auto-Completion Systems. [[Paper]](https://arxiv.org/pdf/2306.03091) [[Code]](https://github.com/Leolty/repobench) `2023.06` - Repository-level code auto-completion; Rule-based
1. SWE-bench: Can Language Models Resolve Real-world Github Issues?. [[Paper]](https://arxiv.org/abs/2310.06770) [[Code]](https://github.com/SWE-bench/SWE-bench) `2023.10` - Real-world GitHub issue resolution; Rule-based
1. DA-Code: Agent Data Science Code Generation Benchmark for Large Language Models. [[Paper]](https://arxiv.org/pdf/2410.07331) [[Code]](https://github.com/yiyihum/da-code) `2024.01` - Tool-integrated repo-level coding challenges; Rule-based
1. LiveCodeBench: Holistic and Contamination Free Evaluation of Large Language Models for Code. [[Paper]](https://arxiv.org/pdf/2403.07974) [[Code]](https://github.com/LiveCodeBench/LiveCodeBench) `2024.03` - Holistic contamination-free code evaluation; Rule-based
1. Can Language Models Replace Programmers for Coding? REPOCOD Says 'Not Yet'. [[Paper]](https://aclanthology.org/2025.acl-long.1204/) [[Code]](https://github.com/lt-asset/REPOCOD) `2024.10` - Realistic repository-level coding; Rule-based
1. SWE-Bench Pro: Can AI Agents Solve Long-Horizon Software Engineering Tasks?. [[Paper]](https://doi.org/10.48550/arXiv.2509.16941) [[Code]](https://github.com/scaleapi/SWE-bench_Pro-os) `2025.09` - Long-horizon software engineering tasks; Rule-based
1. SWE-Sharp-Bench: A Reproducible Benchmark for C# Software Engineering Tasks. [[Paper]](https://doi.org/10.1109/AIware69974.2025.00039) [[Code]](https://huggingface.co/datasets/microsoft/SWE-Sharp-Bench) `2025.11` - Reproducible C# software engineering tasks; Rule-based
1. LoCoBench-Agent: An Interactive Benchmark for LLM Agents in Long-Context Software Engineering. [[Paper]](https://doi.org/10.48550/arXiv.2511.13998) [[Code]](https://github.com/SalesforceAIResearch/LoCoBench-Agent) `2025.11` - Long-context software engineering; Rule-based
1. NL2Repo-Bench: Towards Long-Horizon Repository Generation Evaluation of Coding Agents. [[Paper]](https://doi.org/10.48550/arXiv.2512.12730) [[Code]](https://github.com/multimodal-art-projection/NL2RepoBench) `2025.12` - Long-horizon repository generation; Rule-based
1. OmniCode: A Benchmark for Evaluating Software Engineering Agents. [[Paper]](https://doi.org/10.48550/arXiv.2602.02262) [[Code]](https://github.com/seal-research/OmniCode) `2026.02` - Diverse software engineering agent tasks; Rule-based
1. SWE-Universe: Scale Real-World Verifiable Environments to Millions. [[Paper]](https://arxiv.org/pdf/2602.02361) `2026.02` - Scalable verifiable software environments; Rule-based
1. FeatureBench: Benchmarking Agentic Coding for Complex Feature Development. [[Paper]](https://arxiv.org/pdf/2602.10975) [[Code]](https://github.com/LiberCoders/FeatureBench) `2026.02` - Complex feature development; Rule-based

### 7.3. Tool Use and Function Calling
1. API-Bank: A Comprehensive Benchmark for Tool-Augmented LLMs. [[Paper]](https://arxiv.org/pdf/2304.08244) [[Code]](https://github.com/AlibabaResearch/DAMO-ConvAI/tree/main/api-bank) `2023.04` - API planning and tool invocation; Rule-based
1. AgentBench: Evaluating LLMs as Agents. [[Paper]](https://arxiv.org/pdf/2308.03688) [[Code]](https://github.com/THUDM/AgentBench) `2023.08` - Multi-domain interactive agents; Rule-based
1. GAIA: a benchmark for General AI Assistants. [[Paper]](https://arxiv.org/pdf/2311.12983) [[Code]](https://huggingface.co/gaia-benchmark) `2023.11` - General AI assistant tasks; Rule-based
1. tau-bench: A Benchmark for Tool-Agent-User Interaction in Real-World Domains. [[Paper]](https://arxiv.org/pdf/2406.12045) [[Code]](https://github.com/sierra-research/tau-bench) `2024.06` - Tool-agent-user interaction; Rule-based
1. AppWorld: A Controllable World of Apps and People for Benchmarking Interactive Coding Agents. [[Paper]](https://arxiv.org/pdf/2407.18901) [[Code]](https://github.com/StonyBrookNLP/appworld) `2024.07` - Controllable world of apps and people; Rule-based
1. AssistantBench: Can Web Agents Solve Realistic and Time-Consuming Tasks?. [[Paper]](https://arxiv.org/pdf/2407.15711) [[Code]](https://github.com/oriyor/assistantbench) `2024.07` - Realistic web assistant tasks; Rule-based
1. Toolsandbox: A stateful, conversational, interactive evaluation benchmark for llm tool use capabilities. [[Paper]](https://arxiv.org/pdf/2408.04682) [[Code]](https://github.com/apple/ToolSandbox) `2024.08` - Stateful conversational tool use; Rule-based
1. ToolHop: A Query-Driven Benchmark for Evaluating Large Language Models in Multi-Hop Tool Use. [[Paper]](https://aclanthology.org/2025.acl-long.150/) [[Code]](https://huggingface.co/datasets/bytedance-research/ToolHop) `2025.01` - Query-driven multi-hop tool use; Rule-based
1. DICE-BENCH: Evaluating the Tool-Use Capabilities of Large Language Models in Multi-Round, Multi-Party Dialogues. [[Paper]](https://aclanthology.org/2025.findings-acl.1375/) [[Code]](https://github.com/snuhcc/DICE-Bench) `2025.06` - Multi-round, multi-party dialogue tool use; Rule-based
1. tau^2-Bench: Evaluating Conversational Agents in a Dual-Control Environment. [[Paper]](https://arxiv.org/pdf/2506.07982) [[Code]](https://github.com/sierra-research/tau2-bench) `2025.06` - Conversational agents in dual-control settings; Rule-based
1. The Berkeley Function Calling Leaderboard (BFCL): From Tool Use to Agentic Evaluation of Large Language Models. [[Paper]](https://openreview.net/pdf?id=2GmDdhBdDk) [[Code]](https://github.com/ShishirPatil/gorilla/tree/main/berkeley-function-call-leaderboard) `2025.07` - Function calling and agentic evaluation; Rule-based
1. CCTU: A Benchmark for Tool Use under Complex Constraints. [[Paper]](https://doi.org/10.48550/arXiv.2603.15309) [[Code]](https://github.com/Junjie-Ye/CCTU) `2026.03` - Tool use under complex constraints; Rule-based

### 7.4. Computer Use and GUI Grounding
1. Mind2Web: Towards a Generalist Agent for the Web. [[Paper]](https://arxiv.org/pdf/2306.06070) [[Code]](https://github.com/OSU-NLP-Group/Mind2Web) `2023.06` - Generalist web agent interaction; Rule-based
1. WebArena: A Realistic Web Environment for Building Autonomous Agents. [[Paper]](https://arxiv.org/pdf/2307.13854) [[Code]](https://github.com/web-arena-x/webarena) `2023.07` - Realistic web navigation; Rule-based
1. Android in the Wild: A Large-Scale Dataset for Android Device Control. [[Paper]](https://arxiv.org/pdf/2307.10088) [[Code]](https://github.com/google-research/google-research/tree/master/android_in_the_wild) `2023.07` - Android device control; Rule-based
1. VisualWebArena: Evaluating Multimodal Agents on Realistic Visual Web Tasks. [[Paper]](https://arxiv.org/pdf/2401.13649) [[Code]](https://github.com/web-arena-x/visualwebarena) `2024.01` - Multimodal visual web tasks; Rule-based
1. WorkArena: How Capable are Web Agents at Solving Common Knowledge Work Tasks?. [[Paper]](https://arxiv.org/pdf/2403.07718) [[Code]](https://github.com/ServiceNow/WorkArena) `2024.03` - Common knowledge-work web tasks; Rule-based
1. Osworld-mcp: Benchmarking mcp tool invocation in computer-use agents. [[Paper]](https://arxiv.org/pdf/2510.24563) [[Code]](https://github.com/X-PLUG/OSWorld-MCP) `2024.04` - Open-ended real computer use; Rule-based
1. AndroidWorld: A Dynamic Benchmarking Environment for Autonomous Agents. [[Paper]](https://arxiv.org/pdf/2405.14573) [[Code]](https://github.com/google-research/android_world) `2024.05` - Dynamic Android interaction environment; Rule-based
1. Windows Agent Arena: Evaluating Multi-Modal OS Agents at Scale. [[Paper]](https://arxiv.org/pdf/2409.08264) [[Code]](https://github.com/microsoft/WindowsAgentArena) `2024.09` - Multi-modal desktop OS tasks; Rule-based
1. WorldGUI: An Interactive Benchmark for Desktop GUI Automation from Any Starting Point. [[Paper]](https://doi.org/10.48550/arXiv.2502.08047) [[Code]](https://github.com/showlab/WorldGUI) `2025.02` - Dynamic testing for desktop GUI automation; Rule-based
1. ScreenSpot-Pro: GUI Grounding for Professional High-Resolution Computer Use. [[Paper]](https://arxiv.org/pdf/2504.07981) [[Code]](https://github.com/likaixin2000/ScreenSpot-Pro-GUI-Grounding) `2025.04` - Professional high-resolution GUI grounding; Rule-based
1. MMBench-GUI: Hierarchical Multi-Platform Evaluation Framework for GUI Agents. [[Paper]](https://doi.org/10.48550/arXiv.2507.19478) [[Code]](https://github.com/open-compass/MMBench-GUI) `2025.07` - Hierarchical multi-platform GUI evaluation; Rule-based
1. Osworld-mcp: Benchmarking mcp tool invocation in computer-use agents. [[Paper]](https://arxiv.org/pdf/2510.24563) [[Code]](https://github.com/X-PLUG/OSWorld-MCP) `2025.10` - MCP tool invocation in computer-use agents; Rule-based
1. VenusBench-GD: A Comprehensive Multi-Platform GUI Benchmark for Diverse Grounding Tasks. [[Paper]](https://doi.org/10.48550/arXiv.2512.16501) [[Code]](https://github.com/inclusionAI/UI-Venus/tree/VenusBench-GD) `2025.12` - Multi-platform GUI grounding; Rule-based

### 7.5. ML Engineering and Scientific Research
1. DS-1000: A Natural and Reliable Benchmark for Data Science Code Generation. [[Paper]](https://arxiv.org/pdf/2211.11501) [[Code]](https://github.com/xlang-ai/DS-1000) `2022.11` - Data science code generation; Rule-based
1. MLAgentBench: Evaluating Language Agents on Machine Learning Experimentation. [[Paper]](https://arxiv.org/pdf/2310.03302) [[Code]](https://github.com/snap-stanford/MLAgentBench) `2023.10` - Machine learning experimentation; Rule-based
1. DA-Code: Agent Data Science Code Generation Benchmark for Large Language Models. [[Paper]](https://arxiv.org/pdf/2410.07331) [[Code]](https://github.com/yiyihum/da-code) `2024.10` - Agent data science code generation; Rule-based
1. ScienceAgentBench: Toward Rigorous Assessment of Language Agents for Data-Driven Scientific Discovery. [[Paper]](https://arxiv.org/pdf/2410.05080) [[Code]](https://github.com/OSU-NLP-Group/ScienceAgentBench) `2024.10` - Data-driven scientific discovery; Rule-based
1. MLE-bench: Evaluating Machine Learning Agents on Machine Learning Engineering. [[Paper]](https://arxiv.org/pdf/2410.07095) [[Code]](https://github.com/openai/mle-bench) `2024.10` - Machine learning engineering; Rule-based
1. PaperBench: Evaluating AI's Ability to Replicate AI Research. [[Paper]](https://arxiv.org/pdf/2504.01848) [[Code]](https://github.com/openai/preparedness) `2025.04` - AI research replication; LLM Judge
1. TimeSeriesGym: A Scalable Benchmark for (Time Series) Machine Learning Engineering Agents. [[Paper]](https://doi.org/10.48550/arXiv.2505.13291) [[Code]](https://github.com/moment-timeseries-foundation-model/TimeSeriesGym) `2025.05` - Time-series ML engineering; Rule-based
1. MLR-Bench: Evaluating AI Agents on Open-Ended Machine Learning Research. [[Paper]](https://arxiv.org/pdf/2505.19955) [[Code]](https://github.com/chchenhui/mlrbench) `2025.05` - Open-ended ML research; LLM Judge
1. FML-bench: Benchmarking Machine Learning Agents for Scientific Research. [[Paper]](https://arxiv.org/pdf/2510.10472) [[Code]](https://github.com/qrzou/FML-bench) `2025.10` - Automatic ML research; Rule-based
1. ReplicatorBench: Benchmarking LLM Agents for Replicability in Social and Behavioral Sciences. [[Paper]](https://arxiv.org/pdf/2602.11354) [[Code]](https://github.com/CenterForOpenScience/llm-benchmarking) `2026.02` - Replicability in social and behavioral sciences; LLM Judge / Human Judge

## 8. Citation

If you find our survey useful for your research, please consider citing the survey paper and starring this repository.
