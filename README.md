# A Survey of Agentic Harness Engineering

<p align="center">
  <strong>An Awesome List and Structured Reading Map</strong>
</p>

<p align="center">
  <a href="#"><img src="https://img.shields.io/badge/Status-Building-2ea44f" alt="status"></a>
  <a href="#"><img src="https://img.shields.io/badge/Papers-440-blue" alt="papers"></a>
  <a href="#"><img src="https://img.shields.io/badge/Last%20Update-2026--03--16-orange" alt="last-update"></a>
  <a href="./LICENSE"><img src="https://img.shields.io/badge/License-MIT-lightgrey" alt="license"></a>
</p>

This repository is a curated survey list for **Agentic Harness Engineering**, organized to align with the paper structure of *A Survey of Agentic Harness Engineering*.

## Table of Contents

- [How to Use This Repo](#how-to-use-this-repo)
- [2. Foundations of Harness Engineering](#2-foundations-of-harness-engineering)
  - [2.1 What is Harness Engineering](#21-what-is-harness-engineering)
  - [2.2 Three Phases of Harness Engineering](#22-three-phases-of-harness-engineering)
- [3. Key Components of Agentic Harness Engineering](#3-key-components-of-agentic-harness-engineering)
  - [3.1 Agent Loop](#31-agent-loop)
  - [3.2 Memory Systems](#32-memory-systems)
  - [3.3 Skill Libraries](#33-skill-libraries)
  - [3.4 Multi-agent Orchestration](#34-multi-agent-orchestration)
- [4. Optimization](#4-optimization)
  - [4.1 Test-Time Enhancements](#41-test-time-enhancements)
  - [4.2 Supervised Fine-tuning](#42-supervised-fine-tuning)
  - [4.3 Agentic Reinforcement Learning](#43-agentic-reinforcement-learning)
- [5. Benchmarks and Evaluation](#5-benchmarks-and-evaluation)
  - [5.1 DeepResearch Tasks](#51-deepresearch-tasks)
  - [5.2 Software Engineering Tasks](#52-software-engineering-tasks)
  - [5.3 Tool Use and Function Calling Tasks](#53-tool-use-and-function-calling-tasks)
  - [5.4 Computer Use and GUI Tasks](#54-computer-use-and-gui-tasks)
  - [5.5 Machine Learning Engineering and Scientific Research Tasks](#55-machine-learning-engineering-and-scientific-research-tasks)
- [Citation](#citation)

## How to Use This Repo

- Browse by section: follow the same chapter order as the survey paper.
- Start with tagged tracks: `Foundations`, `Agent Loop`, `Memory`, `Skills`, `Multi-Agent`, `Optimization`, `Evaluation`.
- Add papers with consistent metadata so this list stays searchable.

<!-- ### Entry Template

Use the following format when adding a paper:

```markdown
- [Paper Title](link) | Venue Year | `Tag1` `Tag2` `Tag3`
  - One-line takeaway
  - Optional: code / project / benchmark links
``` -->

## 2. Foundations of Harness Engineering

### 2.1 What is Harness Engineering

#### 2.1.1 Core Definition
- [ ] Placeholder for papers

#### 2.1.2 Comparisons with Related Concepts
- [ ] Placeholder for papers

### 2.2 Three Phases of Harness Engineering

#### 2.2.1 Model and Environment Interfaces
- [ ] Placeholder for papers

#### 2.2.2 Developer Assistants
- [ ] Placeholder for papers

#### 2.2.3 Personal Assistants
- [ ] Placeholder for papers

## 3. Key Components of Agentic Harness Engineering
### 3.1 Agent Loop
#### 3.1.1 Environment Perception
##### State Representation
1. BLIP-2: Bootstrapping Language-Image Pre-training with Frozen Image Encoders and Large Language Models. [[Paper]](https://proceedings.mlr.press/v202/li23q/li23q.pdf) [[Code]](https://github.com/salesforce/LAVIS) `ICML 2023`
1. Flamingo: a Visual Language Model for Few-Shot Learning. [[Paper]](https://proceedings.neurips.cc/paper_files/paper/2022/file/960a172bc7fbf0177ccccbb411a7d800-Paper-Conference.pdf) `NeurIPS 2022`
1. ImageBind-LLM: Multi-modality Instruction Tuning. [[Paper]](https://arxiv.org/pdf/2309.03905.pdf) [[Code]](https://github.com/OpenGVLab/LLaMA-Adapter) `arXiv 2023`
1. ImageBind: One Embedding Space To Bind Them All. [[Paper]](https://openaccess.thecvf.com/content/CVPR2023/papers/Girdhar_ImageBind_One_Embedding_Space_To_Bind_Them_All_CVPR_2023_paper.pdf) [[Code]](https://github.com/facebookresearch/ImageBind) `CVPR 2023`
1. Learning Transferable Visual Models From Natural Language Supervision. [[Paper]](https://proceedings.mlr.press/v139/radford21a/radford21a.pdf) [[Code]](https://github.com/OpenAI/CLIP) `ICML 2021`
1. Visual Instruction Tuning. [[Paper]](https://arxiv.org/pdf/2304.08485.pdf) [[Code]](https://github.com/haotian-liu/LLaVA) `NeurIPS 2023 Oral`
1. GRAPHGPT-O: Synergistic Multimodal Comprehension and Generation on Graphs. [[Paper]](https://arxiv.org/pdf/2502.11925.pdf) [[Code]](https://github.com/YiFang99/GraphGPT-O) `CVPR 2025`
1. ESCA: Contextualizing Embodied Agents via Scene-Graph Generation. [[Paper]](https://arxiv.org/pdf/2510.15963.pdf) [[Code]](https://github.com/video-fm/ESCA) `NeurIPS 2025`
1. PaLM-E: An Embodied Multimodal Language Model. [[Paper]](https://arxiv.org/pdf/2303.03378.pdf) `ICML 2023`
1. RT-2: Vision-Language-Action Models Transfer Web Knowledge to Robotic Control. [[Paper]](https://proceedings.mlr.press/v229/zitkovich23a/zitkovich23a.pdf) `CoRL 2023`
##### Information Extraction
1. Mitigating Hallucination in Multimodal LLMs with Layer Contrastive Decoding. [[Paper]](https://arxiv.org/pdf/2509.25177.pdf) [[Code]](https://github.com/maifoundations/LayerCD) `arXiv 2025`
1. Multi-Modal Hallucination Control by Visual Information Grounding. [[Paper]](https://arxiv.org/pdf/2403.14003.pdf) `arXiv 2024`
1. Multi-modal Instruction Tuned LLMs with Fine-grained Visual Perception. [[Paper]](https://openaccess.thecvf.com/content/CVPR2024/papers/He_Multi-modal_Instruction_Tuned_LLMs_with_Fine-grained_Visual_Perception_CVPR_2024_paper.pdf) [[Code]](https://github.com/jwh97nn/AnyRef) `CVPR 2024`
1. ChartPoint: Guiding MLLMs with Grounding Reflection for Chart Reasoning. [[Paper]](https://arxiv.org/pdf/2512.00305v1.pdf) `ICCV 2025`
1. Compositional Chain-of-Thought Prompting for Large Multimodal Models. [[Paper]](https://openaccess.thecvf.com/content/CVPR2024/papers/Mitra_Compositional_Chain-of-Thought_Prompting_for_Large_Multimodal_Models_CVPR_2024_paper.pdf) [[Code]](https://github.com/chancharikmitra/CCoT) `CVPR 2024`
1. Retrieval-Augmented Generation for Knowledge-Intensive NLP Tasks. [[Paper]](https://arxiv.org/pdf/2005.11401.pdf) [[Code]](https://github.com/huggingface/transformers) `NeurIPS 2020`
1. GUI-Actor: Coordinate-Free Visual Grounding for GUI Agents. [[Paper]](https://arxiv.org/pdf/2506.03143v1.pdf) [[Code]](https://github.com/microsoft/GUI-Actor) `NeurIPS 2025`
1. INREACT: An Inspire-Then-Reinforce Training Framework For Multimodal GUI Agent. [[Paper]](https://aclanthology.org/2025.findings-emnlp.486.pdf) `EMNLP 2025`
1. Navigating the Digital World as Humans Do: Universal Visual Grounding for GUI Agents. [[Paper]](https://arxiv.org/pdf/2410.05243.pdf) [[Code]](https://github.com/OSU-NLP-Group/UGround) `ICLR 2025`
1. Eyes Wide Shut? Exploring the Visual Shortcomings of Multimodal LLMs. [[Paper]](https://openaccess.thecvf.com/content/CVPR2024/papers/Tong_Eyes_Wide_Shut_Exploring_the_Visual_Shortcomings_of_Multimodal_LLMs_CVPR_2024_paper.pdf) [[Code]](https://github.com/tsb0601/MMVP) `CVPR 2024`
#### 3.1.2 Task Planning
##### Task Decomposition
1. Least-to-Most Prompting Enables Complex Reasoning in Large Language Models. [[Paper]](https://arxiv.org/pdf/2205.10625.pdf) `ICLR 2023`
1. Chain-of-Thought Prompting Elicits Reasoning in Large Language Models. [[Paper]](https://arxiv.org/pdf/2201.11903.pdf) [[Code]](https://github.com/google-research/url-nlp/tree/main/mgsm) `NeurIPS 2022`
1. Tree of Thoughts: Deliberate Problem Solving with Large Language Models. [[Paper]](https://arxiv.org/pdf/2305.10601.pdf) [[Code]](https://github.com/princeton-nlp/tree-of-thought-llm) `NeurIPS 2023`
1. Visual CoT: Advancing Multi-Modal Language Models with a Comprehensive Dataset and Benchmark for Chain-of-Thought Reasoning. [[Paper]](https://proceedings.neurips.cc/paper_files/paper/2024/file/0ff38d72a2e0aa6dbe42de83a17b2223-Paper-Datasets_and_Benchmarks_Track.pdf) [[Code]](https://github.com/deepcs233/Visual-CoT) `NeurIPS 2024`
1. Compositional Chain-of-Thought Prompting for Large Multimodal Models. [[Paper]](https://openaccess.thecvf.com/content/CVPR2024/papers/Mitra_Compositional_Chain-of-Thought_Prompting_for_Large_Multimodal_Models_CVPR_2024_paper.pdf) [[Code]](https://github.com/chancharikmitra/CCoT) `CVPR 2024`
##### Plan Generation
1. Agentic Reasoning: A Streamlined Framework for Enhancing LLM Reasoning with Agentic Tools. [[Paper]](https://aclanthology.org/2025.acl-long.1383.pdf) `ACL 2025`
1. Chain of Thoughtlessness? An Analysis of CoT in Planning. [[Paper]](https://proceedings.neurips.cc/paper_files/paper/2024/file/3365d974ce309623bd8151082d78206c-Paper-Conference.pdf) [[Code]](https://github.com/karthikv792/cot-planning) `NeurIPS 2024`
1. GAP: Graph-Based Agent Planning with Parallel Tool Use and Reinforcement Learning. [[Paper]](https://arxiv.org/pdf/2510.25320.pdf) [[Code]](https://github.com/WJQ7777/Graph-Agent-Planning) `NeurIPS 2025`
1. LLaMAR: Long-Horizon Planning for Multi-Agent Robots in Partially Observable Environments. [[Paper]](https://arxiv.org/pdf/2407.10031.pdf) [[Code]](https://github.com/nsidn98/LLaMAR) `NeurIPS 2024`
1. Player-Coach Teamwork: Multi-agent Collaboration for Improving LLM Reasoning. [[Paper]](https://openreview.net/pdf?id=qNHbqlRBel) `NeurIPS 2025`
1. Proactive Agent: Shifting LLM Agents from Reactive Responses to Active Assistance. [[Paper]](https://arxiv.org/pdf/2410.12361.pdf) [[Code]](https://github.com/thunlp/ProactiveAgent) `ICLR 2025`
1. Self-Consistency Improves Chain of Thought Reasoning in Language Models. [[Paper]](https://arxiv.org/pdf/2203.11171.pdf) `ICLR 2023`
##### Self-Reflection
1. Boosting LLM Reasoning via Spontaneous Self-Correction. [[Paper]](https://arxiv.org/pdf/2506.06923.pdf) `COLM 2025`
1. Recursive Introspection: Teaching Language Model Agents How to Self-Improve. [[Paper]](https://arxiv.org/pdf/2407.18219.pdf) [[Code]](https://github.com/cmu-mind/RISE) `NeurIPS 2024`
1. Reflexion: Language Agents with Verbal Reinforcement Learning. [[Paper]](https://arxiv.org/pdf/2303.11366.pdf) [[Code]](https://github.com/noahshinn/reflexion) `NeurIPS 2023`
1. Reinforce LLM Reasoning through Multi-Agent Reflection. [[Paper]](https://arxiv.org/pdf/2506.08379.pdf) `ICML 2025`
1. Self-Correction Bench: Uncovering and Addressing the Self-Correction Blind Spot in Large Language Models. [[Paper]](https://arxiv.org/pdf/2507.02778.pdf) [[Code]](https://github.com/kenhktsui/self-correction-bench) `arXiv 2025`
#### 3.1.3 Action Execution
##### Tool Selection
1. WebGPT: Browser-assisted question-answering with human feedback. [[Paper]](https://arxiv.org/pdf/2112.09332.pdf) `arXiv 2021`
1. Agent S: An Open Agentic Framework that Uses Computers Like a Human. [[Paper]](https://arxiv.org/pdf/2410.08164.pdf) [[Code]](https://github.com/simular-ai/Agent-S) `ICLR 2025`
1. AppWorld: A Controllable World of Apps and People for Benchmarking Interactive Coding Agents. [[Paper]](https://aclanthology.org/2024.acl-long.850.pdf) [[Code]](https://github.com/StonyBrookNLP/appworld) `ACL 2024`
1. VisualWebArena: Evaluating Multimodal Agents on Realistic Visual Web Tasks. [[Paper]](https://aclanthology.org/2024.acl-long.50.pdf) [[Code]](https://github.com/web-arena-x/visualwebarena) `ACL 2024`
1. WebVoyager: Building an End-to-End Web Agent with Large Multimodal Models. [[Paper]](https://arxiv.org/pdf/2401.13919.pdf) [[Code]](https://github.com/MinorJerry/WebVoyager) `ACL 2024`
1. SWE-agent: Agent-Computer Interfaces Enable Automated Software Engineering. [[Paper]](https://arxiv.org/pdf/2405.15793.pdf) [[Code]](https://github.com/princeton-nlp/SWE-agent) `NeurIPS 2024`
1. Code as Policies: Language Model Programs for Embodied Control. [[Paper]](https://arxiv.org/pdf/2209.07753.pdf) [[Code]](https://github.com/google-research/google-research/tree/master/code_as_policies) `ICRA 2023`
1. Grounding Multimodal Large Language Models in Actions. [[Paper]](https://proceedings.neurips.cc/paper_files/paper/2024/file/2406694fd7bc7e7bf257446a14f9ea63-Paper-Conference.pdf) `NeurIPS 2024`
1. Do As I Can, Not As I Say: Grounding Language in Robotic Affordances. [[Paper]](https://arxiv.org/pdf/2204.01691.pdf) [[Code]](https://github.com/google-research/google-research/tree/master/saycan) `CoRL 2023`
##### Environment Interaction
1. AvaTaR: Optimizing LLM Agents for Tool Usage via Contrastive Reasoning. [[Paper]](https://arxiv.org/pdf/2406.11200.pdf) [[Code]](https://github.com/zou-group/avatar) `NeurIPS 2024`
1. AutoML-Agent: A Multi-Agent LLM Framework for Full-Pipeline AutoML. [[Paper]](https://raw.githubusercontent.com/mlresearch/v267/main/assets/trirat25a/trirat25a.pdf) [[Code]](https://github.com/DeepAuto-AI/automl-agent) `ICML 2025`
1. EASYTOOL: Enhancing LLM-based Agents with Concise Tool Instruction. [[Paper]](https://arxiv.org/pdf/2401.06201.pdf) [[Code]](https://github.com/microsoft/JARVIS/tree/main/easytool) `ACL 2025`
1. Distilling LLM Agent into Small Models with Retrieval and Code Tools. [[Paper]](https://arxiv.org/pdf/2505.17612.pdf) [[Code]](https://github.com/Nardien/agent-distillation) `arXiv 2025`
1. Toolformer: Language Models Can Teach Themselves to Use Tools. [[Paper]](https://arxiv.org/pdf/2302.04761.pdf) `NeurIPS 2023`
1. MRKL Systems: A modular, neuro-symbolic architecture that combines large language models, external knowledge sources and discrete reasoning. [[Paper]](https://arxiv.org/pdf/2205.00445.pdf) [[Code]](https://github.com/AI21Labs/MRKL_synthetic_data) `arXiv 2022`
### 3.2 Memory Systems
#### 3.2.1 Short-term Memory
##### Working Memory
1. AFlow: Automating Agentic Workflow Generation. [[Paper]](https://arxiv.org/pdf/2410.10762.pdf) [[Code]](https://github.com/FoundationAgents/AFlow) `ICLR 2025`
1. Graph of Thoughts: Solving Elaborate Problems with Large Language Models. [[Paper]](https://arxiv.org/pdf/2308.09687.pdf) [[Code]](https://github.com/spcl/graph-of-thoughts) `AAAI 2024`
1. Memo: Training Memory-Efficient Embodied Agents with Reinforcement Learning. [[Paper]](https://arxiv.org/pdf/2510.19732.pdf) [[Code]](https://github.com/gunshi/memo) `NeurIPS 2025`
1. ReAct: Synergizing Reasoning and Acting in Language Models. [[Paper]](https://arxiv.org/pdf/2210.03629.pdf) [[Code]](https://github.com/ysymyth/ReAct) `ICLR 2023`
1. Working Memory Attack on LLMs. [[Paper]](https://openreview.net/pdf?id=II0NVPLBcI) [[Code]](https://github.com/UNHSAILLab/working-memory-attack-on-llms) `ICLR 2025`
##### Conversational Memory
1. Agent Reviewers: Domain-specific Multimodal Agents with Shared Memory for Paper Review. [[Paper]](https://raw.githubusercontent.com/mlresearch/v267/main/assets/lu25p/lu25p.pdf) [[Code]](https://github.com/AReviewers/AgentReviewers) `ICML 2025`
1. ChatDev: Communicative Agents for Software Development. [[Paper]](https://aclanthology.org/2024.acl-long.810.pdf) [[Code]](https://github.com/OpenBMB/ChatDev) `ACL 2024`
1. Evaluating Memory in LLM Agents via Incremental Multi-Turn Interactions. [[Paper]](https://arxiv.org/pdf/2507.05257.pdf) [[Code]](https://github.com/HUST-AI-HYZ/MemoryAgentBench) `ICLR 2026`
#### 3.2.2 Long-term Memory
##### Semantic Memory
1. Augmenting Language Models with Long-Term Memory. [[Paper]](https://arxiv.org/pdf/2306.07174.pdf) [[Code]](https://github.com/Victorwz/LongMem) `NeurIPS 2023`
1. From RAG to Memory: Non-Parametric Continual Learning for Large Language Models. [[Paper]](https://arxiv.org/pdf/2502.14802.pdf) [[Code]](https://github.com/OSU-NLP-Group/HippoRAG) `ICML 2025`
1. Ghost in the Minecraft: Generally Capable Agents for Open-World Environments via Large Language Models with Text-based Knowledge and Memory. [[Paper]](https://arxiv.org/pdf/2305.17144.pdf) [[Code]](https://github.com/OpenGVLab/GITM) `arXiv 2023`
1. M+: Extending MemoryLLM with Scalable Long-Term Memory. [[Paper]](https://arxiv.org/pdf/2502.00592.pdf) [[Code]](https://github.com/wangyu-ustc/MemoryLLM) `ICML 2025`
1. Memory Decoder: A Pretrained, Plug-and-Play Memory for Large Language Models. [[Paper]](https://arxiv.org/pdf/2508.09874.pdf) [[Code]](https://github.com/LUMIA-Group/MemoryDecoder) `NeurIPS 2025`
##### Episodic Memory
1. Evaluating Very Long-Term Conversational Memory of LLM Agents. [[Paper]](https://aclanthology.org/2024.acl-long.747.pdf) [[Code]](https://github.com/snap-research/LoCoMo) `ACL 2024`
1. ExpeL: LLM Agents Are Experiential Learners. [[Paper]](https://arxiv.org/pdf/2308.10144.pdf) [[Code]](https://github.com/LeapLabTHU/ExpeL) `AAAI 2024`
1. LongMemEval: Benchmarking Chat Assistants on Long-Term Interactive Memory. [[Paper]](https://openreview.net/pdf?id=pZiyCaVuti) [[Code]](https://github.com/xiaowu0162/LongMemEval) `ICLR 2025`
1. MemoryBank: Enhancing Large Language Models with Long-Term Memory. [[Paper]](https://arxiv.org/pdf/2305.10250.pdf) [[Code]](https://github.com/zhongwanjun/MemoryBank-SiliconFriend) `AAAI 2024`
1. Reflexion: Language Agents with Verbal Reinforcement Learning. [[Paper]](https://proceedings.neurips.cc/paper_files/paper/2023/file/1b44b878bb782e6954cd888628510e90-Paper-Conference.pdf) [[Code]](https://github.com/noahshinn/reflexion) `NeurIPS 2023`
1. MemGPT: Towards LLMs as Operating Systems. [[Paper]](https://arxiv.org/pdf/2310.08560.pdf) [[Code]](https://github.com/letta-ai/letta) `arXiv 2023`
1. A-Mem: Agentic Memory for LLM Agents. [[Paper]](https://arxiv.org/pdf/2502.12110.pdf) [[Code]](https://github.com/agiresearch/A-mem) `NeurIPS 2025`
##### Procedural Memory
1. LEGO-Prover: Neural Theorem Proving with Growing Libraries. [[Paper]](https://proceedings.iclr.cc/paper_files/paper/2024/file/85dca46374dc0f27b4bb5f265b3d17f0-Paper-Conference.pdf) [[Code]](https://github.com/wiio12/LEGO-Prover) `ICLR 2024`
1. Memory OS of AI Agent. [[Paper]](https://aclanthology.org/2025.emnlp-main.1318.pdf) [[Code]](https://github.com/BAI-LAB/MemoryOS) `EMNLP 2025`
1. TPTU: Large Language Model-based AI Agents for Task Planning and Tool Usage. [[Paper]](https://arxiv.org/pdf/2308.03427.pdf) `arXiv 2023`
1. Voyager: An Open-Ended Embodied Agent with Large Language Models. [[Paper]](https://openreview.net/pdf?id=ehfRiF0R3a) [[Code]](https://github.com/MineDojo/Voyager) `NeurIPS 2023`
#### 3.2.3 Memory Management
##### Memory Retrieval
1. BIDER: Bridging Knowledge Inconsistency for Efficient Retrieval-Augmented LLMs via Key Supporting Evidence. [[Paper]](https://arxiv.org/pdf/2402.12174.pdf) `ACL 2024`
1. Cognitive Personalized Search Integrating Large Language Models with an Efficient Memory Mechanism. [[Paper]](https://arxiv.org/pdf/2402.10548.pdf) `WWW 2024`
1. DeepRAG: Thinking to Retrieve Step by Step for Large Language Models. [[Paper]](https://arxiv.org/pdf/2502.01142.pdf) [[Code]](https://github.com/gxy-gxy/DeepRAG) `ICLR 2026`
1. From Local to Global: A Graph RAG Approach to Query-Focused Summarization. [[Paper]](https://arxiv.org/pdf/2404.16130.pdf) [[Code]](https://github.com/microsoft/graphrag) `arXiv 2024`
1. LLatrieval: LLM-Verified Retrieval for Verifiable Generation. [[Paper]](https://aclanthology.org/2024.naacl-long.305.pdf) [[Code]](https://github.com/BeastyZ/LLM-Verified-Retrieval) `NAACL 2024`
1. Metacognitive Retrieval-Augmented Large Language Models. [[Paper]](https://arxiv.org/pdf/2402.11626.pdf) [[Code]](https://github.com/ignorejjj/MetaRAG) `WWW 2024`
1. Retrieval-Augmented Generation for Knowledge-Intensive NLP Tasks. [[Paper]](https://arxiv.org/pdf/2005.11401.pdf) [[Code]](https://github.com/huggingface/transformers) `NeurIPS 2020`
1. RetroLLM: Empowering Large Language Models to Retrieve Fine-grained Evidence within Generation. [[Paper]](https://aclanthology.org/2025.acl-long.819.pdf) [[Code]](https://github.com/sunnynexus/RetroLLM) `ACL 2025`
1. Chain-of-Memory: Lightweight Memory Construction with Dynamic Evolution for LLM Agents. [[Paper]](https://arxiv.org/pdf/2601.14287.pdf) `arXiv 2026`
1. Sim-LLM: Optimizing LLM Inference at the Edge through Inter-Task KV Reuse. [[Paper]](https://openreview.net/pdf?id=z1Cvcovlms) [[Code]](https://github.com/CGCL-codes/SimLLM) `NeurIPS 2025`
##### Memory Summarization
1. Chain of Agents: Large Language Models Collaborating on Long-Context Tasks. [[Paper]](https://arxiv.org/pdf/2406.02818.pdf) `arXiv 2024`
### 3.3 Skill Libraries
#### 3.3.1 Skill Acquisition
##### Learning form Demonstration
1. SkillCraft: Can LLM Agents Learn to Use Tools Skillfully? [[Paper]](https://arxiv.org/pdf/2603.00718.pdf) [[Code]](https://github.com/shiqichen17/SkillCraft) `arXiv 2026`
1. ToolLLM: Facilitating Large Language Models to Master 16000+ Real-world APIs. [[Paper]](https://openreview.net/pdf?id=dHng2O0Jjr) [[Code]](https://github.com/OpenBMB/ToolBench) `ICLR 2024`
1. Leveraging Skills from Unlabeled Prior Data for Efficient Online Exploration. [[Paper]](https://arxiv.org/pdf/2410.18076.pdf) [[Code]](https://github.com/rail-berkeley/SUPE) `ICML 2025`
1. ExpeL: LLM Agents Are Experiential Learners. [[Paper]](https://arxiv.org/pdf/2308.10144.pdf) [[Code]](https://github.com/LeapLabTHU/ExpeL) `AAAI 2024`
1. Ghost in the Minecraft: Generally Capable Agents for Open-World Environments via Large Language Models with Text-based Knowledge and Memory. [[Paper]](https://arxiv.org/pdf/2305.17144.pdf) [[Code]](https://github.com/OpenGVLab/GITM) `ICLR 2024 Workshop`
##### Learning from Feedback
1. Reinforcement Learning for Self-Improving Agent with Skill Library. [[Paper]](https://arxiv.org/pdf/2512.17102.pdf) [[Code]](https://github.com/amazon-science/SAGE) `arXiv 2025`
1. SkillRL: Evolving Agents via Recursive Skill-Augmented Reinforcement Learning. [[Paper]](https://arxiv.org/pdf/2602.08234.pdf) [[Code]](https://github.com/aiming-lab/SkillRL) `ICLR 2026`
1. Describe, Explain, Plan and Select: Interactive Planning with Large Language Models Enables Open-World Multi-Task Agents. [[Paper]](https://proceedings.neurips.cc/paper_files/paper/2023/file/6b8dfb8c0c12e6fafc6c256cb08a5ca7-Paper-Conference.pdf) [[Code]](https://github.com/CraftJarvis/MC-Planner) `ICLR 2026`
1. SEAgent: Self-Evolving Computer Use Agent with Autonomous Learning from Experience. [[Paper]](https://arxiv.org/pdf/2508.04700.pdf) [[Code]](https://github.com/SunzeY/SEAgent) `arXiv 2025`
1. Voyager: An Open-Ended Embodied Agent with Large Language Models. [[Paper]](https://arxiv.org/pdf/2305.16291.pdf) [[Code]](https://github.com/MineDojo/Voyager) `TMLR 2024`
1. AvaTaR: Optimizing LLM Agents for Tool Usage via Contrastive Reasoning. [[Paper]](https://proceedings.neurips.cc/paper_files/paper/2024/file/2db8ce969b000fe0b3fb172490c33ce8-Paper-Conference.pdf) [[Code]](https://github.com/zou-group/avatar) `NeurIPS 2024`
1. Agent Skill Acquisition for Large Language Models via CycleQD. [[Paper]](https://arxiv.org/pdf/2410.14735.pdf) [[Code]](https://github.com/SakanaAI/CycleQD) `ICLR 2025`
#### 3.3.2 Skill Management
##### Skill Representation
1. Instruction Embedding: Latent Representations of Instructions Towards Task Identification. [[Paper]](https://proceedings.neurips.cc/paper_files/paper/2024/file/9f9e2982759f384495f4b75a33f3dd72-Paper-Datasets_and_Benchmarks_Track.pdf) [[Code]](https://github.com/Yiwei98/instruction-embedding-benchmark) `NeurIPS 2024`
1. Learning Structured Representations with Hyperbolic Embeddings. [[Paper]](https://proceedings.neurips.cc/paper_files/paper/2024/file/a5d2da376bab7624b3caeb9f78fcaa2f-Paper-Conference.pdf) [[Code]](https://github.com/uiuctml/HypStructure) `NeurIPS 2024`
1. Embedding-Aligned Language Models. [[Paper]](https://arxiv.org/pdf/2406.00024.pdf) `NeurIPS 2024`
1. Do LLMs Build World Representations? Probing Through the Lens of State Abstraction. [[Paper]](https://proceedings.neurips.cc/paper_files/paper/2024/file/b1b16c4b875eb84d3585cb70d23970ca-Paper-Conference.pdf) [[Code]](https://github.com/BorealisAI/llm-world-abs) `NeurIPS 2024`
1. Hierarchical Programmatic Option Framework. [[Paper]](https://proceedings.neurips.cc/paper_files/paper/2024/file/e51ec47238fc3e82c269965c5533f9ef-Paper-Conference.pdf) [[Code]](https://github.com/NTURobotLearningLab/HIPO) `NeurIPS 2024`
1. Learning to Reason via Program Generation, Emulation, and Search. [[Paper]](https://arxiv.org/pdf/2405.16337.pdf) [[Code]](https://github.com/nweir127/CoGEX) `NeurIPS 2024`
1. ToolGen: Unified Tool Retrieval and Calling via Generation. [[Paper]](https://arxiv.org/pdf/2410.03439.pdf) [[Code]](https://github.com/Reason-Wang/ToolGen) `ICLR 2025`
1. MaestroMotif: Skill Design from Artificial Intelligence Feedback. [[Paper]](https://arxiv.org/pdf/2412.08542.pdf) [[Code]](https://github.com/mklissa/maestromotif) `ICLR 2025`
1. Distilling LLM Agent into Small Models with Retrieval and Code Tools. [[Paper]](https://arxiv.org/pdf/2505.17612.pdf) [[Code]](https://github.com/Nardien/agent-distillation) `NeurIPS 2025`
##### Skill Scheduling
1. Multi-task Batch Reinforcement Learning with Metric Learning. [[Paper]](https://proceedings.neurips.cc/paper/2020/file/4496bf24afe7fab6f046bf4923da8de6-Paper.pdf) [[Code]](https://github.com/Ji4chenLi/Multi-Task-Batch-RL) `NeurIPS 2020`
1. Incremental Learning of Retrievable Skills For Efficient Continual Task Adaptation. [[Paper]](https://arxiv.org/pdf/2410.22658.pdf) [[Code]](https://github.com/L2dulgi/IsCiL) `NeurIPS 2024`
1. Exploratory Retrieval-Augmented Planning For Continual Embodied Instruction Following. [[Paper]](https://proceedings.neurips.cc/paper_files/paper/2024/file/7bacd0ebd061d4694583ae0eb69ad15f-Paper-Conference.pdf) `NeurIPS 2024`
1. Found in the Middle: How Language Models Use Long Contexts Better via Plug-and-Play Positional Encoding. [[Paper]](https://openreview.net/pdf?id=fPmScVB1Td) [[Code]](https://github.com/VITA-Group/Ms-PoE) `NeurIPS 2024`
1. Exploiting Task Relationships in Continual Learning via Transferability-Aware Task Embeddings. [[Paper]](https://arxiv.org/pdf/2502.11609.pdf) [[Code]](https://github.com/viki760/Hembedding_Guided_Hypernet) `NeurIPS 2025`
1. G-Memory: Tracing Hierarchical Memory for Multi-Agent Systems. [[Paper]](https://openreview.net/pdf?id=mmIAp3cVS0) [[Code]](https://github.com/bingreeky/GMemory) `NeurIPS 2025`
1. SRSA: Skill Retrieval and Adaptation for Robotic Assembly Tasks. [[Paper]](https://arxiv.org/pdf/2503.04538.pdf) `ICLR 2025`
1. Insight Agents: An LLM-Based Multi-Agent System for Data Insights. [[Paper]](https://arxiv.org/pdf/2601.20048.pdf) `SIGIR 2025`
1. LifelongAgentBench: Evaluating LLM Agents as Lifelong Learners. [[Paper]](https://arxiv.org/pdf/2505.11942.pdf) [[Code]](https://github.com/caixd-220529/LifelongAgentBench) `ICLR 2026`
### 3.4 Multi-agent Orchestration
#### 3.4.1 Coordination Architectures
##### Centralized
1. AutoGen: Enabling Next-Gen LLM Applications via Multi-Agent Conversations. [[Paper]](https://openreview.net/pdf?id=BAakY1hNKS) [[Code]](https://github.com/microsoft/autogen) `COLM 2024`
1. MetaGPT: Meta Programming for A Multi-Agent Collaborative Framework. [[Paper]](https://openreview.net/pdf?id=VtmBAGCN7o) [[Code]](https://github.com/geekan/MetaGPT) `ICLR 2024`
1. ChatDev: Communicative Agents for Software Development. [[Paper]](https://aclanthology.org/2024.acl-long.810.pdf) [[Code]](https://github.com/OpenBMB/ChatDev) `ACL 2024`
1. CAMEL: Communicative Agents for "Mind" Exploration of Large Language Model Society. [[Paper]](https://proceedings.neurips.cc/paper/2023/hash/a3621ee907def47c1b952ade25c67698-Abstract-Conference.html) [[Code]](https://github.com/camel-ai/camel) `NeurIPS 2023`
1. AutoAgents: A Framework for Automatic Agent Generation. [[Paper]](https://arxiv.org/pdf/2309.17288) [[Code]](https://github.com/Link-AGI/AutoAgents) `IJCAI 2024`
1. MegaAgent: A Large-Scale Autonomous LLM-based Multi-Agent System Without Predefined SOPs. [[Paper]](https://aclanthology.org/2025.findings-acl.259.pdf) [[Code]](https://github.com/Xtra-Computing/MegaAgent) `Findings of ACL 2025`
##### Decentralized
1. AgentVerse: Facilitating Multi-Agent Collaboration and Exploring Emergent Behaviors. [[Paper]](https://openreview.net/pdf?id=EHg5GDnyq1) [[Code]](https://github.com/OpenBMB/AgentVerse) `ICLR 2024`
1. A Dynamic LLM-Powered Agent Network for Task-Oriented Agent Collaboration (DyLAN). [[Paper]](https://arxiv.org/pdf/2310.02170) [[Code]](https://github.com/SALT-NLP/DyLAN) `COLM 2024`
1. Encouraging Divergent Thinking in Large Language Models through Multi-Agent Debate. [[Paper]](https://aclanthology.org/2024.emnlp-main.992.pdf) [[Code]](https://github.com/Skytliang/Multi-Agents-Debate) `EMNLP 2024`
1. CONSENSAGENT: Towards Efficient and Effective Consensus in Multi-Agent LLM Interactions Through Sycophancy Mitigation. [[Paper]](https://aclanthology.org/2025.findings-acl.1141.pdf) [[Code]](https://github.com/priyapitre/CONSENSAGENT) `Findings of ACL 2025`
1. Multi-Agent Collaboration via Evolving Orchestration. [[Paper]](https://arxiv.org/abs/2505.19591) [[Code]](https://github.com/OpenBMB/ChatDev/tree/puppeteer) `NeurIPS 2025`
##### Hierarchical
1. Long-Horizon Planning for Multi-Agent Robots in Partially Observable Environments (LLaMAR). [[Paper]](https://arxiv.org/abs/2407.10031) [[Code]](https://github.com/nsidn98/LLaMAR) `NeurIPS 2024`
1. ProAgent: Building Proactive Cooperative Agents with Large Language Models. [[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/29710) `AAAI 2024`
1. Player-Coach Teamwork: Multi-agent Collaboration for Improving LLM Reasoning. [[Paper]](https://openreview.net/pdf?id=qNHbqlRBel) `NeurIPS 2025 Workshop`
1. AutoHMA-LLM: Efficient Task Coordination and Execution in Heterogeneous Multi-Agent Systems Using Hybrid Large Language Models. [[Paper]](https://ieeexplore.ieee.org/abstract/document/10839354/) `IEEE TCCN 2024`
1. Halo: Hierarchical Autonomous Logic-Oriented Orchestration for Multi-Agent LLM Systems. [[Paper]](https://arxiv.org/abs/2505.13516) [[Code]](https://github.com/23japhone/HALO) `arXiv 2025`
#### 3.4.2 Coordination Mechanisms
##### Rule-based Coordination
1. SOP-Agent: Empower General Purpose AI Agent with Domain-Specific SOPs. [[Paper]](https://arxiv.org/abs/2501.09316) `arXiv 2025`
1. Flow-of-Action: SOP Enhanced LLM-Based Multi-Agent System for Root Cause Analysis. [[Paper]](https://arxiv.org/pdf/2502.08224) `WWW 2025`
1. Structuring the Unstructured: A Multi-Agent LLM Framework for Transforming Ambiguous SOPs into Code. [[Paper]](https://aclanthology.org/anthology-files/pdf/emnlp/2025.emnlp-industry.163.pdf) `EMNLP 2025 Industry`
1. InstructFlow: Adaptive Symbolic Constraint-Guided Code Generation for Long-Horizon Planning. [[Paper]](https://openreview.net/forum?id=nzwjvpCO4F) [[Code]](https://github.com/chiht21/InstructFlow) `NeurIPS 2025`
##### Role-based Coordination
1. RoleLLM: Benchmarking, Eliciting, and Enhancing Role-Playing Abilities of Large Language Models. [[Paper]](https://aclanthology.org/2024.findings-acl.878.pdf) [[Code]](https://github.com/InteractiveNLP-Team/RoleLLM-public) `Findings of ACL 2024`
1. Debate-to-Write: A Persona-Driven Multi-Agent Framework for Diverse Argument Generation. [[Paper]](https://aclanthology.org/2025.coling-main.314.pdf) [[Code]](https://github.com/Derekkk/LLM4ArgGen) `COLING 2025`
1. CollabPersona: A Framework for Collaborative Decision Analysis in Persona Driven LLM-Based Multi-Agent Systems. [[Paper]](https://ieeexplore.ieee.org/abstract/document/11204223/) `MLSP 2025`
1. Multi-Agent Consensus Matrix Modeling for Medical Decision-Making: A Role-Specialized LLM Framework for Oncology MDT Consultations. [[Paper]](https://openreview.net/forum?id=em8vGhlUxU) `arXiv`
1. Using Role-Specialized LLM Agents for Workflow Execution in a Product Development Setting. [[Paper]](https://ieeexplore.ieee.org/abstract/document/11188152/) `ICISC 2025`
1. LLM-driven Multi-Agent Architectures for Intelligent Self-Organizing Networks. [[Paper]](https://ieeexplore.ieee.org/abstract/document/11169757/) `IEEE Network 2025`
##### Learning-based Coordination
1. Reinforce LLM Reasoning through Multi-Agent Reflection. [[Paper]](https://arxiv.org/pdf/2506.08379) `ICML 2025`
1. GAP: Graph-based Agent Planning with Parallel Tool Use and Reinforcement Learning. [[Paper]](https://openreview.net/pdf?id=7bJIVHEvLm) [[Code]](https://github.com/WJQ7777/Graph-Agent-Planning) `NeurIPS 2025 Workshop`
1. MAPoRL: Multi-Agent Post-Co-Training for Collaborative Large Language Models with Reinforcement Learning. [[Paper]](https://aclanthology.org/2025.acl-long.1459.pdf) [[Code]](https://github.com/chanwoo-park-official/MAPoRL) `ACL 2025`
1. LLM-guided Decision-Making Toolkit for Multi-Agent Reinforcement Learning. [[Paper]](https://www.sciencedirect.com/science/article/pii/S0925231225007775) [[Code]](https://github.com/lizhemin18/pymarl_LLM) `Neurocomputing 2025`
1. Enhancing Multi-Agent Systems via Reinforcement Learning with LLM-based Planner and Graph-based Policy. [[Paper]](https://ieeexplore.ieee.org/abstract/document/11127486/) `ICRA 2025`
## 4. Optimization
### 4.1 Test-Time Enhancements
#### 4.1.1 Role Specification
##### Generic Role-Playing
1. Personalizing Dialogue Agents: I Have a Dog, Do You Have Pets Too? [[Paper]](https://aclanthology.org/P18-1205.pdf) `ACL 2018`
1. Generative Agents: Interactive Simulacra of Human Behavior. [[Paper]](https://dl.acm.org/doi/epdf/10.1145/3586183.3606763) [[Code]](https://github.com/joonspk-research/generative_agents) `UIST 2023`
1. Role Play with Large Language Models. [[Paper]](https://www.nature.com/articles/s41586-023-06647-8.pdf) `Nature`
1. RoleLLM: Benchmarking, Eliciting, and Enhancing Role-Playing Abilities of LLMs. [[Paper]](https://aclanthology.org/2024.findings-acl.878.pdf) [[Code]](https://github.com/InteractiveNLP-Team/RoleLLM-public) `Findings of ACL 2023`
1. Scaling Synthetic Data Creation with 1,000,000,000 Personas. [[Paper]](https://arxiv.org/pdf/2406.20094) [[Code]](https://github.com/tencent-ailab/persona-hub) `arXiv 2024`
1. Bias Runs Deep: Implicit Reasoning Biases in Persona-Assigned LLMs. [[Paper]](https://arxiv.org/abs/2311.04892) [[Code]](https://github.com/allenai/persona-bias?tab=readme-ov-file) `ICLR 2024`
1. Large Language Models are Superpositions of All Characters: Attaining Arbitrary Role-play via Self-Alignment. [[Paper]](https://aclanthology.org/2024.acl-long.423.pdf) [[Code]](https://github.com/OFA-Sys/Ditto) `ACL 2024`
1. CharacterEval: A Chinese Benchmark for Role-Playing Conversational Agent Evaluation. [[Paper]](https://aclanthology.org/2024.acl-long.638.pdf) [[Code]](https://github.com/morecry/CharacterEval) `ACL 2024`
1. Enhancing Persona Consistency for LLMs' Role-Playing using Persona-Aware Contrastive Learning. [[Paper]](https://aclanthology.org/2025.findings-acl.1344.pdf) `Findings of ACL 2025`
1. CoSER: Coordinating LLM-Based Persona Simulation of Established Roles. [[Paper]](https://arxiv.org/pdf/2502.09082) [[Code]](https://github.com/Neph0s/CoSER) `ICML 2025`
##### Persona-based Role-Playing
1. Personalized Soups: Personalized LLM Alignment via Post-hoc Parameter Merging. [[Paper]](https://arxiv.org/pdf/2310.11564) [[Code]](https://github.com/joeljang/RLPHF) `arXiv 2023`
1. Character-LLM: A Trainable Agent for Role-Playing. [[Paper]](https://aclanthology.org/2023.emnlp-main.814v1.pdf) [[Code]](https://github.com/choosewhatulike/trainable-agents) `EMNLP 2023`
1. LongLaMP: A Benchmark for Personalized Long-form Text Generation. [[Paper]](https://arxiv.org/pdf/2407.11016) [[Code]](https://longlamp-benchmark.github.io/) `arXiv 2024`
1. InCharacter: Evaluating Personality Fidelity in Role-Playing Agents through Psychological Interviews. [[Paper]](https://aclanthology.org/2024.acl-long.102.pdf) [[Code]](https://incharacter.github.io/) `ACL 2024`
1. LaMP: When Large Language Models Meet Personalization. [[Paper]](https://aclanthology.org/2024.acl-long.399.pdf) [[Code]](https://lamp-benchmark.github.io/) `ACL 2024`
1. Democratizing LLMs via Personalized Parameter-Efficient Fine-tuning. [[Paper]](https://aclanthology.org/2024.emnlp-main.372.pdf) [[Code]](https://github.com/TamSiuhin/OPPU) `EMNLP 2024`
1. PERSONA: A Reproducible Testbed for Pluralistic Alignment. [[Paper]](https://aclanthology.org/2025.coling-main.752.pdf) [[Code]](https://www.synthlabs.ai/research/persona) `COLING 2025`
1. Personalized Language Modeling from Personalized Human Feedback. [[Paper]](https://arxiv.org/pdf/2402.05133) [[Code]](https://github.com/HumainLab/Personalized_RLHF) `arXiv 2024`
1. RLHF from Heterogeneous Feedback via Personalization and Preference Aggregation. [[Paper]](https://arxiv.org/pdf/2405.00254) `arXiv 2024`
1. Memory-Augmented LLM Personalization with Short- and Long-Term Memory Coordination. [[Paper]](https://aclanthology.org/2024.naacl-long.132.pdf) [[Code]](https://github.com/MatthewKKai/MaLP) `NAACL 2024`
1. Personalizing Reinforcement Learning from Human Feedback with Variational Preference Learning. [[Paper]](https://proceedings.neurips.cc/paper_files/paper/2024/file/5e1c255653eb98cef13f45b2d337c882-Paper-Conference.pdf) [[Code]](https://github.com/WEIRDLabUW/vpl_llm) `NeurIPS 2024`
1. HYDRA: Model Factorization Framework for Black-Box LLM Personalization. [[Paper]](https://proceedings.neurips.cc/paper_files/paper/2024/file/b6b4906c1334656e97cc9968ccfca073-Paper-Conference.pdf) [[Code]](https://github.com/night-chen/HYDRA) `NeurIPS 2024`
1. Personalized Pieces: Efficient Personalized LLMs through Collaborative Efforts. [[Paper]](https://aclanthology.org/2024.emnlp-main.371.pdf) [[Code]](https://github.com/TamSiuhin/Per-Pcs) `EMNLP 2024`
1. PersonalLLM: Tailoring LLMs to Individual Preferences. [[Paper]](https://arxiv.org/pdf/2409.20296) [[Code]](https://huggingface.co/datasets/namkoong-lab/PersonalLLM) `ICLR 2025`
1. PRIME: Large Language Model Personalization with Cognitive Dual-Memory and Personalized Thought Process. [[Paper]](https://arxiv.org/pdf/2507.04607) [[Code]](https://github.com/launchnlp/LM_Personalization) `EMNLP 2025`
1. Persona Vectors: Monitoring and Controlling Character Traits in Language Models. [[Paper]](https://arxiv.org/pdf/2507.21509) [[Code]](https://github.com/safety-research/persona_vectors) `arXiv 2025`
1. HER: Human-like Reasoning and Reinforcement Learning for LLM Role-playing. [[Paper]](https://arxiv.org/abs/2601.21459) [[Code]](https://github.com/cydu24/HER) `arXiv 2026`
1. Persona Prompting as a Lens on LLM Social Reasoning. [[Paper]](https://arxiv.org/abs/2601.20757) `arXiv 2026`
#### 4.1.2 Context Management
##### Context Retrieval
1. Active Retrieval Augmented Generation. [[Paper]](https://aclanthology.org/2023.emnlp-main.495.pdf) [[Code]](https://github.com/jzbjyb/FLARE) `EMNLP 2023`
1. Self-RAG: Learning to Retrieve, Generate, and Critique through Self-Reflection. [[Paper]](https://proceedings.iclr.cc/paper_files/paper/2024/file/25f7be9694d7b32d5cc670927b8091e1-Paper-Conference.pdf) [[Code]](https://selfrag.github.io/) `ICLR 2024`
1. HippoRAG: Neurobiologically Inspired Long-Term Memory for LLMs. [[Paper]](https://proceedings.neurips.cc/paper_files/paper/2024/file/6ddc001d07ca4f319af96a3024f6dbd1-Paper-Conference.pdf) [[Code]](https://github.com/OSU-NLP-Group/HippoRAG) `NeurIPS 2024`
1. Chain-of-Agents: LLMs Collaborating on Long-Context Tasks. [[Paper]](https://proceedings.neurips.cc/paper_files/paper/2024/file/ee71a4b14ec26710b39ee6be113d7750-Paper-Conference.pdf) `NeurIPS 2024`
1. R1-Searcher: Incentivizing Search Capability in LLMs via RL. [[Paper]](https://arxiv.org/pdf/2503.05592) [[Code]](https://github.com/RUCAIBox/R1-Searcher) `arXiv 2025`
1. From RAG to Memory: Non-Parametric Continual Learning for LLMs. [[Paper]](https://arxiv.org/pdf/2502.14802) [[Code]](https://github.com/OSU-NLP-Group/HippoRAG) `ICML 2025`
1. Search-R1: Training LLMs to Reason and Leverage Search Engines with RL. [[Paper]](https://arxiv.org/pdf/2503.09516) [[Code]](https://github.com/PeterGriffinJin/Search-R1) `COLM 2025`
##### Context Processing
1. Learning to Compress Prompts with Gist Tokens. [[Paper]](https://proceedings.neurips.cc/paper_files/paper/2023/file/3d77c6dcc7f143aa2154e7f4d5e22d68-Paper-Conference.pdf) [[Code]](https://github.com/jayelm/gisting) `NeurIPS 2023`
1. Adapting Language Models to Compress Contexts. [[Paper]](https://aclanthology.org/2023.emnlp-main.232.pdf) [[Code]](https://github.com/princeton-nlp/AutoCompressors) `EMNLP 2023`
1. LLMLingua: Compressing Prompts for Accelerated Inference of LLMs. [[Paper]](https://aclanthology.org/2023.emnlp-main.825.pdf) [[Code]](https://llmlingua.com/) `EMNLP 2023`
1. Compressing Context to Enhance Inference Efficiency. [[Paper]](https://aclanthology.org/2023.emnlp-main.391.pdf) [[Code]](https://github.com/liyucheng09/Selective_Context) `EMNLP 2023`
1. In-context Autoencoder for Context Compression. [[Paper]](https://arxiv.org/abs/2307.06945) [[Code]](https://github.com/getao/icae) `ICLR 2024`
1. SnapKV: LLM Knows What You are Looking for Before Generation. [[Paper]](https://arxiv.org/abs/2404.14469) [[Code]](https://github.com/FasterDecoding/SnapKV) `ICML 2024`
1. LazyLLM: Dynamic Token Pruning for Efficient Long Context Inference. [[Paper]](https://arxiv.org/pdf/2407.14057) `ICML 2024`
1. Acon: Optimizing Context Compression for Long-Horizon LLM Agents. [[Paper]](https://arxiv.org/pdf/2510.00615) [[Code]](https://github.com/microsoft/acon) `arXiv 2025`
##### Context Updating
1. Reflexion: Language Agents with Verbal Reinforcement Learning. [[Paper]](https://proceedings.neurips.cc/paper_files/paper/2023/file/1b44b878bb782e6954cd888628510e90-Paper-Conference.pdf) [[Code]](https://github.com/noahshinn024/reflexion) `NeurIPS 2023`
1. MemGPT: Towards LLMs as Operating Systems. [[Paper]](https://arxiv.org/pdf/2310.08560) [[Code]](https://research.memgpt.ai/) `ICLR 2024`
1. Efficient Streaming Language Models with Attention Sinks. [[Paper]](https://proceedings.iclr.cc/paper_files/paper/2024/file/5e5fd18f863cbe6d8ae392a93fd271c9-Paper-Conference.pdf) [[Code]](https://github.com/mit-han-lab/streaming-llm) `ICLR 2024`
1. Mem0: Building Production-Ready AI Agents with Scalable Long-Term Memory. [[Paper]](https://arxiv.org/pdf/2504.19413) [[Code]](https://mem0.ai/research) `arXiv 2025`
1. Agent Workflow Memory. [[Paper]](https://arxiv.org/pdf/2409.07429) [[Code]](https://github.com/zorazrw/agent-workflow-memory) `ICML 2025`
1. Working Memory for Agents: Dynamic Context Swapping using External States. [[Paper]](https://aclanthology.org/2025.acl-long.334.pdf) `ACL 2025`
1. DAM-LLM: Dynamic Affective Memory Management for Personalized Agents. [[Paper]](https://arxiv.org/pdf/2510.27418) `arXiv 2025`
1. A-MEM: Agentic Memory for LLM Agents. [[Paper]](https://arxiv.org/pdf/2502.12110) [[Code]](https://github.com/WujiangXu/A-mem) `NeurIPS 2025`
1. Forgetful but Faithful: MaRS – Memory-Aware Retention Schema. [[Paper]](https://arxiv.org/pdf/2512.12856) `arXiv 2025`
1. AgentSys: Secure LLM Agents Through Hierarchical Memory Management. [[Paper]](https://arxiv.org/pdf/2602.07398) [[Code]](https://github.com/ruoyaow/agentsys-memory) `arXiv 2026`
### 4.2 Supervised Fine-tuning
#### 4.2.1 Distillation Strategies
##### Off-policy Distillation Methods
1. Stanford Alpaca: An Instruction-following LLaMA Model. [[Paper]](https://crfm.stanford.edu/2023/03/13/alpaca.html) [[Code]](https://github.com/tatsu-lab/stanford_alpaca) `Stanford Blog`
1. Vicuna: An Open-Source Chatbot Impressing GPT-4 with 90%* ChatGPT Quality. [[Paper]](https://lmsys.org/blog/2023-03-30-vicuna/) [[Code]](https://github.com/lm-sys/FastChat) `LMSYS Blog`
1. WizardLM: Empowering Large Pre-Trained Language Models to Follow Complex Instructions. [[Paper]](https://arxiv.org/abs/2304.12244) [[Code]](https://github.com/nlpxucan/WizardLM) `ICLR 2024`
1. Orca: Progressive Learning from Complex Explanation Traces of GPT-4. [[Paper]](https://arxiv.org/abs/2306.02707) `arXiv 2023`
1. AgentTuning: Enabling Generalized Agent Abilities for LLMs. [[Paper]](https://arxiv.org/abs/2310.12823) [[Code]](https://github.com/THUDM/AgentTuning) `ACL 2024 Findings`
1. FireAct: Toward Language Agent Fine-tuning. [[Paper]](https://arxiv.org/abs/2310.05915) [[Code]](https://github.com/anchen1011/FireAct) `arXiv 2023`
1. Agent-FLAN: Designing Data and Methods of Effective Agent Tuning for Large Language Models. [[Paper]](https://arxiv.org/abs/2403.12881) [[Code]](https://github.com/InternLM/Agent-FLAN) `ACL 2024 Findings`
1. AgentOhana: Design Unified Data and Training Pipeline for Effective Agent Learning. [[Paper]](https://arxiv.org/abs/2402.15506) [[Code]](https://github.com/SalesforceAIResearch/xLAM) `arXiv 2024`
1. DeepSeek-R1: Incentivizing Reasoning Capability in LLMs via Reinforcement Learning. [[Paper]](https://arxiv.org/abs/2501.12948) [[Code]](https://github.com/deepseek-ai/DeepSeek-R1) `arXiv 2025`
1. AgentTrek: Agent Trajectory Synthesis via Guiding Replay with Web Tutorials. [[Paper]](https://arxiv.org/abs/2412.09605) [[Code]](https://github.com/xlang-ai/AgentTrek) `ICLR 2025 Spotlight`
1. OS-Genesis: Automating GUI Agent Trajectory Construction via Reverse Task Synthesis. [[Paper]](https://arxiv.org/abs/2412.19723) [[Code]](https://qiushisun.github.io/OS-Genesis-Home/) `ACL 2025`
1. UI-TARS: Pioneering Automated GUI Interaction with Native Agents. [[Paper]](https://arxiv.org/abs/2501.12326) [[Code]](https://github.com/bytedance/UI-TARS) `arXiv 2025`
1. Distilling LLM Agent into Small Models with Retrieval and Code Tools. [[Paper]](https://arxiv.org/abs/2505.17612) [[Code]](https://github.com/Nardien/agent-distillation) `arXiv 2025`
1. 1.4 Million Open-Source Distilled Reasoning Dataset to Empower LLM Training. [[Paper]](https://www.google.com/search?q=https://arxiv.org/search/cs%3Fquery%3D1.4%2BMillion%2BOpen-Source%2BDistilled%2BReasoning%2BDataset&authuser=1) [[Code]](https://huggingface.co/datasets/a-m-team/AM-DeepSeek-R1-Distilled-1.4M) `arXiv`
##### On-policy Distillation Methods
1. On-Policy Distillation of Language Models: Learning from Self-Generated Mistakes. [[Paper]](https://arxiv.org/abs/2306.13649) `ICLR 2024`
1. MiniLLM: On-Policy Distillation of Large Language Models. [[Paper]](https://arxiv.org/abs/2306.08543) [[Code]](https://github.com/microsoft/LMOps/tree/main/minillm) `ICLR 2024`
1. Trial and Error: Exploration-Based Trajectory Optimization for LLM Agents. [[Paper]](https://arxiv.org/abs/2403.02502) [[Code]](https://github.com/Yifan-Song793/ETO) `ACL 2024`
1. Agent Q: Advanced Reasoning and Learning for Autonomous AI Agents. [[Paper]](https://arxiv.org/abs/2408.07199) `arXiv 2024`
1. AgentGen: Enhancing Planning Abilities for LLM-based Agent via Environment and Task Generation. [[Paper]](https://arxiv.org/abs/2408.00764) [[Code]](https://agent-gen.github.io/) `KDD 2025`
1. UI-TARS-2 Technical Report: Advancing GUI Agent with Multi-Turn Reinforcement Learning. [[Paper]](https://arxiv.org/abs/2509.02544) `arXiv 2025`
1. WebRL: Training LLM Web Agents via Self-Evolving Online Curriculum Reinforcement Learning. [[Paper]](https://arxiv.org/pdf/2411.02337) [[Code]](https://github.com/THUDM/WebRL) `ICLR 2025`
1. How to Train Your LLM Web Agent: A Statistical Diagnosis. [[Paper]](https://arxiv.org/pdf/2507.04103) `NeurIPS 2025`
1. WebSynthesis: World-Model-Guided Mcripts for Efficient WebUI-Trajectory Synthesis. [[Paper]](https://arxiv.org/pdf/2507.04370) [[Code]](https://www.google.com/search?q=https://github.com/search%3Fq%3DWebSynthesis&authuser=1) `arXiv 2025`
1. SynthAgent: Adapting Web Agents with Synthetic Supervision. [[Paper]](https://arxiv.org/pdf/2511.06101) [[Code]](https://github.com/aiming-lab/SynthAgent) `arXiv 2025`
#### 4.2.2 Self-Evolving Strategies
##### Self-Refine Methods
1. STaR: Bootstrapping Reasoning With Reasoning. [[Paper]](https://arxiv.org/abs/2203.14465) [[Code]](https://github.com/ezelikman/STaR) `NeurIPS 2022`
1. Large Language Models Can Self-Improve. [[Paper]](https://arxiv.org/abs/2210.11610) `EMNLP 2023`
1. Self-Refine: Iterative Refinement with Self-Feedback. [[Paper]](https://arxiv.org/abs/2303.17651) [[Code]](https://github.com/madaan/self-refine) `NeurIPS 2023`
1. Reflexion: Language Agents with Verbal Reinforcement Learning. [[Paper]](https://arxiv.org/abs/2303.11366) [[Code]](https://github.com/noahshinn/reflexion) `NeurIPS 2023`
1. Beyond Human Data: Scaling Self-Training for Problem-Solving with Language Models. [[Paper]](https://arxiv.org/abs/2312.06585) `TMLR 2024`
1. V-STaR: Training Verifiers for Self-Taught Reasoners. [[Paper]](https://arxiv.org/abs/2402.06457) `COLM 2024`
1. Quiet-STaR: Language Models Can Teach Themselves to Think Before Speaking. [[Paper]](https://arxiv.org/abs/2403.09629) [[Code]](https://github.com/ezelikman/quiet-star) `COLM 2024`
1. Self-Rewarding Language Models. [[Paper]](https://arxiv.org/abs/2401.10020) `ICML 2024`
1. CREAM: Consistency Regularized Self-Rewarding Language Models. [[Paper]](https://www.google.com/search?q=https://arxiv.org/search/cs%3Fquery%3DConsistency%2BRegularized%2BSelf-Rewarding%2BLanguage%2BModels&authuser=1) [[Code]](https://www.google.com/search?q=https://github.com/search%3Fq%3DCREAM%2BConsistency%2BRegularized%2BSelf-Rewarding&authuser=1) `ICLR 2025`
1. Self-play with Execution Feedback: Improving Instruction-following Capabilities of LLMs. [[Paper]](https://www.google.com/search?q=https://arxiv.org/search/cs%3Fquery%3DSelf-play%2Bwith%2BExecution%2BFeedback&authuser=1) [[Code]](https://www.google.com/search?q=https://github.com/search%3Fq%3DSelf-play%2Bwith%2BExecution%2BFeedback&authuser=1) `ICLR 2025`
1. Self-Improving LLM Agents at Test-Time. [[Paper]](https://www.google.com/search?q=https://arxiv.org/search/cs%3Fquery%3DSelf-Improving%2BLLM%2BAgents%2Bat%2BTest-Time&authuser=1) [[Code]](https://www.google.com/search?q=https://github.com/search%3Fq%3DSelf-Improving%2BLLM%2BAgents%2Bat%2BTest-Time&authuser=1) `arXiv`
1. EvolveR: Self-Evolving LLM Agents through an Experience-Driven Lifecycle. [[Paper]](https://www.google.com/search?q=https://arxiv.org/search/cs%3Fquery%3DEvolveR%2BSelf-Evolving&authuser=1) [[Code]](https://www.google.com/search?q=https://github.com/search%3Fq%3DEvolveR%2BSelf-Evolving&authuser=1) `arXiv`
1. Agent0: Unleashing Self-Evolving Agents from Zero Data via Tool-Integrated Reasoning. [[Paper]](https://www.google.com/search?q=https://arxiv.org/search/cs%3Fquery%3DAgent0%2BUnleashing%2BSelf-Evolving&authuser=1) [[Code]](https://www.google.com/search?q=https://github.com/search%3Fq%3DAgent0%2BUnleashing%2BSelf-Evolving&authuser=1) `arXiv`
1. Does Reinforcement Learning Really Incentivize Reasoning Capacity in LLMs Beyond the Base Model? [[Paper]](https://www.google.com/search?q=https://arxiv.org/search/cs%3Fquery%3DDoes%2BReinforcement%2BLearning%2BReally%2BIncentivize%2BReasoning%2BCapacity&authuser=1) [[Code]](https://www.google.com/search?q=https://github.com/search%3Fq%3DDoes%2BReinforcement%2BLearning%2BReally%2BIncentivize&authuser=1) `NeurIPS 2025 Oral`
1. Reinforcing Large Language Model Reasoning through Multi-Agent Reflection (DPSDP). [[Paper]](https://www.google.com/search?q=https://arxiv.org/search/cs%3Fquery%3DReinforcing%2BLarge%2BLanguage%2BModel%2BReasoning%2Bthrough%2BMulti-Agent%2BReflection&authuser=1) [[Code]](https://www.google.com/search?q=https://github.com/search%3Fq%3DDPSDP%2BReinforcing%2BLarge%2BLanguage%2BModel&authuser=1) `ICML 2025`
1. Self-Challenging Agents. [[Paper]](https://www.google.com/search?q=https://arxiv.org/search/cs%3Fquery%3DSelf-Challenging%2BAgents&authuser=1) [[Code]](https://www.google.com/search?q=https://github.com/search%3Fq%3DSelf-Challenging%2BAgents&authuser=1) `NeurIPS 2025`
1. Self-Generated In-Context Examples Improve LLM Agents for Sequential Decision-Making Tasks. [[Paper]](https://www.google.com/search?q=https://arxiv.org/search/cs%3Fquery%3DSelf-Generated%2BIn-Context%2BExamples%2BImprove%2BLLM%2BAgents&authuser=1) [[Code]](https://www.google.com/search?q=https://github.com/search%3Fq%3DSelf-Generated%2BIn-Context%2BExamples%2BImprove%2BLLM%2BAgents&authuser=1) `NeurIPS 2025`
##### Self-Play Methods
1. Human-level Play in the Game of Diplomacy. [[Paper]](https://www.science.org/doi/10.1126/science.ade9097) [[Code]](https://github.com/facebookresearch/diplomacy_cicero) `Science 2022`
1. Self-Play Fine-Tuning Converts Weak Language Models to Strong Language Models. [[Paper]](https://arxiv.org/abs/2401.01335) [[Code]](https://github.com/uclaml/SPIN) `ICML 2024`
1. Nash Learning from Human Feedback. [[Paper]](https://arxiv.org/abs/2312.00886) `ICML 2024`
1. Improving Factuality and Reasoning in Language Models through Multiagent Debate. [[Paper]](https://arxiv.org/abs/2305.14325) [[Code]](https://github.com/composable-models/llm_multiagent_debate) `ICML 2024`
1. Debating with More Persuasive LLMs Leads to More Truthful Answers. [[Paper]](https://arxiv.org/abs/2402.06782) [[Code]](https://github.com/ucl-dark/llm_debate) `arXiv 2024`
1. Self-playing Adversarial Language Game Enhances LLM Reasoning. [[Paper]](https://arxiv.org/abs/2404.10642) [[Code]](https://github.com/Linear95/SPAG) `NeurIPS 2024`
1. Self-Play Preference Optimization for Language Model Alignment. [[Paper]](https://arxiv.org/abs/2405.00675) [[Code]](https://github.com/uclaml/SPPO) `NeurIPS 2024`
1. Encouraging Divergent Thinking in Large Language Models through Multi-Agent Debate. [[Paper]](https://arxiv.org/abs/2305.19118) [[Code]](https://github.com/Skytliang/Multi-Agents-Debate) `EMNLP 2024`
1. MARFT: Multi-Agent Reinforcement Fine-Tuning. [[Paper]](https://arxiv.org/abs/2504.16129) [[Code]](https://github.com/jwliao-ai/MARFT) `arXiv 2025`
1. MARSHAL: Incentivizing Multi-Agent Reasoning via Self-Play with Strategic LLMs. [[Paper]](https://arxiv.org/abs/2510.15414) [[Code]](https://github.com/thu-nics/MARSHAL) `arXiv 2025`
1. Multi-Agent Evolve: LLM Self-Improve through Co-evolution. [[Paper]](https://arxiv.org/abs/2510.23595) [[Code]](https://github.com/ulab-uiuc/Multi-agent-Evolve) `arXiv 2025`
1. Strategist: Learning Strategic Skills by LLMs via Bi-Level Tree Search. [[Paper]](https://arxiv.org/abs/2408.10635) [[Code]](https://github.com/jonathanmli/Avalon-LLM) `ICLR 2025`
1. MAPoRL: Multi-Agent Post-Co-Training for Collaborative Large Language Models with Reinforcement Learning. [[Paper]](https://arxiv.org/abs/2502.18439) [[Code]](https://github.com/chanwoo-park-official/MAPoRL) `ACL 2025`
1. Improving Rationality in the Reasoning Process of Language Models through Self-playing Game. [[Paper]](https://arxiv.org/abs/2506.22920) [[Code]](https://github.com/PinzhengWang322/Critic_Discernment_Game) `ICML 2025`
1. SiriuS: Self-improving Multi-agent Systems via Bootstrapped Reasoning. [[Paper]](https://arxiv.org/abs/2502.04780) [[Code]](https://github.com/zou-group/sirius) `NeurIPS 2025`
1. SPICE: Self-Play In Corpus Environments Improves Reasoning. [[Paper]](https://arxiv.org/abs/2510.24684) `arXiv 2025`
1. War of Thoughts: Competition Stimulates Stronger Reasoning in Large Language Models. [[Paper]](https://aclanthology.org/2025.findings-acl.1118/) `Findings of ACL 2025`
### 4.3 Agentic Reinforcement Learning
#### 4.3.1 Environment Construction
##### Rule-based Environments
1. TextWorld: A Learning Environment for Text-Based Games. [[Paper]](https://arxiv.org/abs/1806.11532) [[Code]](https://github.com/microsoft/TextWorld) `CGW @ IJCAI 2018`
1. Interactive Fiction Games: A Colossal Adventure (Jericho). [[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/6297) [[Code]](https://github.com/microsoft/jericho) `AAAI 2020`
1. ALFWorld: Aligning Text and Embodied Environments for Interactive Learning. [[Paper]](https://arxiv.org/abs/2010.03768) [[Code]](https://github.com/alfworld/alfworld) `ICLR 2021`
1. ScienceWorld: Is your Agent Smarter than a 5th Grader? [[Paper]](https://aclanthology.org/2022.emnlp-main.775/) [[Code]](https://github.com/allenai/ScienceWorld) `EMNLP 2022`
1. WebShop: Towards Scalable Real-World Web Interaction with Grounded Language Agents. [[Paper]](https://arxiv.org/abs/2207.01206) [[Code]](https://github.com/princeton-nlp/WebShop) `NeurIPS 2022`
1. InterCode: Standardizing and Benchmarking Interactive Coding with Execution Feedback. [[Paper]](https://arxiv.org/abs/2306.14898) [[Code]](https://github.com/princeton-nlp/intercode) `arXiv 2023`
1. EnvGen: Generating and Adapting Environments via LLMs for Training Embodied Agents. [[Paper]](https://arxiv.org/abs/2403.12014) [[Code]](https://github.com/aszala/EnvGen) `arXiv 2024`
1. DiscoveryWorld: A Virtual Environment for Developing and Evaluating Automated Scientific Discovery Agents. [[Paper]](https://arxiv.org/abs/2406.06769) [[Code]](https://github.com/allenai/discoveryworld) `NeurIPS 2024 Datasets and Benchmarks`
1. RAGEN: Understanding Self-Evolution in LLM Agents via Multi-Turn Reinforcement Learning. [[Paper]](https://arxiv.org/abs/2504.20073) [[Code]](https://github.com/RAGEN-AI/RAGEN) `arXiv 2025`
1. GEM: A Gym for Agentic LLMs. [[Paper]](https://arxiv.org/abs/2510.01051) [[Code]](https://github.com/axon-rl/gem) `arXiv 2025`
1. Meta-RL Induces Exploration in Language Agents. [[Paper]](https://arxiv.org/abs/2512.16848) `arXiv 2025`
##### Simulation-based Environments
1. AI2-THOR: An Interactive 3D Environment for Visual AI. [[Paper]](https://arxiv.org/abs/1712.05474) [[Code]](https://github.com/allenai/ai2thor) `arXiv 2017`
1. VirtualHome: Simulating Household Activities via Programs. [[Paper]](https://arxiv.org/abs/1806.07011) [[Code]](https://github.com/xavierpuigf/virtualhome) `CVPR 2018 Oral`
1. Habitat: A Platform for Embodied AI Research. [[Paper]](https://openaccess.thecvf.com/content_ICCV_2019/html/Savva_Habitat_A_Platform_for_Embodied_AI_Research_ICCV_2019_paper.html) [[Code]](https://github.com/facebookresearch/habitat-sim) `ICCV 2019`
1. Habitat 2.0: Training Home Assistants to Rearrange their Habitat. [[Paper]](https://arxiv.org/abs/2106.14405) [[Code]](https://github.com/facebookresearch/habitat-sim) `NeurIPS 2021`
1. SWE-bench: Can Language Models Resolve Real-World GitHub Issues? [[Paper]](https://arxiv.org/abs/2310.06770) [[Code]](https://github.com/SWE-bench/SWE-bench) `ICLR 2024`
1. BEHAVIOR-1K: A Human-Centered, Embodied AI Benchmark with 1,000 Everyday Activities and Realistic Simulation. [[Paper]](https://arxiv.org/abs/2403.09227) [[Code]](https://github.com/StanfordVL/BEHAVIOR-1K) `arXiv 2024`
1. OSWorld: Benchmarking Multimodal Agents for Open-Ended Tasks in Real Computer Environments. [[Paper]](https://arxiv.org/abs/2404.07972) [[Code]](https://github.com/xlang-ai/OSWorld) `NeurIPS 2024`
1. AndroidWorld: A Dynamic Benchmarking Environment for Autonomous Agents. [[Paper]](https://arxiv.org/abs/2405.14573) `arXiv 2024`
1. Training Software Engineering Agents and Verifiers with SWE-Gym. [[Paper]](https://arxiv.org/abs/2412.21139) [[Code]](https://github.com/SWE-Gym/SWE-Gym) `arXiv 2024`
1. ARPO: End-to-End Policy Optimization for GUI Agents with Experience Replay. [[Paper]](https://arxiv.org/abs/2505.16282) [[Code]](https://github.com/JIA-Lab-research/ARPO) `arXiv 2025`
##### Real-world Environments
1. WebArena: A Realistic Web Environment for Building Autonomous Agents. [[Paper]](https://arxiv.org/abs/2307.13854) [[Code]](https://github.com/web-arena-x/webarena) `ICLR 2024`
1. AgentBench: Evaluating LLMs as Agents. [[Paper]](https://arxiv.org/abs/2308.03688) [[Code]](https://github.com/THUDM/AgentBench) `ICLR 2024`
1. VisualWebArena: Evaluating Multimodal Agents on Realistic Visual Web Tasks. [[Paper]](https://arxiv.org/abs/2401.13649) [[Code]](https://github.com/web-arena-x/visualwebarena) `ACL 2024`
1. DigiRL: Training In-The-Wild Device-Control Agents with Autonomous Reinforcement Learning. [[Paper]](https://arxiv.org/abs/2406.11896) [[Code]](https://github.com/DigiRL-agent/digirl) `NeurIPS 2024`
1. VideoWebArena: Evaluating Long Context Multimodal Agents with Video Understanding Web Tasks. [[Paper]](https://arxiv.org/abs/2410.19100) [[Code]](https://github.com/ljang0/videowebarena) `ICLR 2025`
1. WebRL: Training LLM Web Agents via Self-Evolving Online Curriculum RL. [[Paper]](https://arxiv.org/abs/2411.02337) [[Code]](https://github.com/THUDM/WebRL) `ICLR 2025`
1. BrowserGym Ecosystem for Web Agent Research. [[Paper]](https://arxiv.org/abs/2412.05467) `arXiv 2024`
1. Digi-Q: Learning Q-Value Functions for Training Device-Control Agents. [[Paper]](https://arxiv.org/abs/2502.15760) `arXiv 2025`
1. LOOP: Reinforcement Learning for Long-Horizon Interactive LLM Agents. [[Paper]](https://arxiv.org/abs/2502.01600) `arXiv 2025`
1. Search-R1: Training LLMs to Reason and Leverage Search Engines with RL. [[Paper]](https://arxiv.org/abs/2503.09516) [[Code]](https://github.com/PeterGriffinJin/Search-R1) `arXiv 2025`
1. R1-Searcher: Incentivizing the Search Capability in LLMs via RL. [[Paper]](https://arxiv.org/abs/2503.05592) [[Code]](https://github.com/RUCAIBox/R1-Searcher) `arXiv 2025`
1. DeepResearcher: Scaling Deep Research via Reinforcement Learning in Real-world Environments. [[Paper]](https://aclanthology.org/2025.emnlp-main.22/) [[Code]](https://github.com/GAIR-NLP/DeepResearcher) `EMNLP 2025`
1. SFR-DeepResearch: Towards Effective RL for Autonomously Reasoning Single Agents. [[Paper]](https://arxiv.org/abs/2509.06283) `arXiv 2025`
1. SkyRL-Agent: Efficient RL Training for Multi-turn LLM Agent. [[Paper]](https://arxiv.org/abs/2511.16108) [[Code]](https://github.com/NovaSky-AI/SkyRL) `arXiv 2025`
1. WebAgent-R1: Training Web Agents via End-to-End Multi-Turn RL. [[Paper]](https://aclanthology.org/2025.emnlp-main.401.pdf) [[Code]](https://github.com/weizhepei/WebAgent-R1) `EMNLP 2025`
#### 4.3.2 Reward Design
##### Outcome-level Rewards
1. Training Verifiers to Solve Math Word Problems. [[Paper]](https://arxiv.org/abs/2110.14168) [[Code]](https://github.com/openai/grade-school-math) `arXiv 2021`
1. Scaling Laws for Reward Model Overoptimization. [[Paper]](https://arxiv.org/abs/2210.10760) `ICML 2023`
1. Solving Math Word Problems with Process- and Outcome-Based Feedback. [[Paper]](https://arxiv.org/abs/2211.14275) `arXiv 2022`
1. OVM: Outcome-supervised Value Models for Planning in Mathematical Reasoning. [[Paper]](https://arxiv.org/abs/2311.09724) `arXiv 2023`
1. Scaling Laws for Reward Model Overoptimization in Direct Alignment Algorithms. [[Paper]](https://arxiv.org/abs/2406.02900) `NeurIPS 2024`
1. Generative Verifiers: Reward Modeling as Next-Token Prediction (GenRM). [[Paper]](https://arxiv.org/abs/2408.15240) `ICLR 2025`
1. DeepSeek-R1: Incentivizing Reasoning Capability in LLMs via Reinforcement Learning. [[Paper]](https://arxiv.org/abs/2501.12948) [[Code]](https://github.com/deepseek-ai/DeepSeek-R1) `Nature 2025`
1. Kimi k1.5: Scaling Reinforcement Learning with LLMs. [[Paper]](https://arxiv.org/abs/2501.12599) `arXiv 2025`
1. Exploring the Limit of Outcome Reward for Learning Mathematical Reasoning. [[Paper]](https://arxiv.org/abs/2502.06781) `arXiv 2025`
1. Reinforcement Learning with Verifiable Rewards Implicitly Incentivizes Correct Reasoning. [[Paper]](https://arxiv.org/abs/2506.14245) `arXiv 2025`
##### Process-level Rewards
1. Let's Verify Step by Step. [[Paper]](https://arxiv.org/abs/2305.20050) [[Code]](https://github.com/openai/prm800k) `ICLR 2024`
1. Let's Reward Step by Step: Step-Level Reward Model as the Navigators for Reasoning. [[Paper]](https://arxiv.org/abs/2310.10080) `arXiv 2023`
1. Math-Shepherd: Verify and Reinforce LLMs Step-by-step without Human Annotations. [[Paper]](https://arxiv.org/abs/2312.08935) `ACL 2024`
1. Improve Mathematical Reasoning in Language Models by Automated Process Supervision. [[Paper]](https://arxiv.org/abs/2406.06592) `arXiv 2024`
1. Scaling LLM Test-Time Compute Optimally can be More Effective than Scaling Model Parameters. [[Paper]](https://arxiv.org/abs/2408.03314) `ICLR 2025`
1. The Lessons of Developing Process Reward Models in Mathematical Reasoning. [[Paper]](https://arxiv.org/abs/2501.07301) `arXiv 2025`
1. Process Reinforcement through Implicit Rewards. [[Paper]](https://arxiv.org/abs/2502.01456) [[Code]](https://github.com/PRIME-RL/PRIME) `arXiv 2025`
1. Process Reward Models for LLM Agents (AgentPRM). [[Paper]](https://arxiv.org/abs/2502.10325) `arXiv 2025`
1. PURE: Process sUpervised Reinforcement lEarning. [[Paper]](https://arxiv.org/abs/2504.13941) [[Code]](https://github.com/CJReinforce/PURE) `arXiv 2025`
1. Process Reward Models That Think (ThinkPRM). [[Paper]](https://arxiv.org/abs/2504.16828) [[Code]](https://github.com/mukhal/thinkprm) `arXiv 2025`
1. Reinforcing Multi-Turn Reasoning in LLM Agents via Turn-Level Credit Assignment (MT-GRPO). [[Paper]](https://arxiv.org/abs/2505.11821) `arXiv 2025`
1. A Survey of Process Reward Models: From Outcome Signals to Process Supervisions for LLMs. [[Paper]](https://arxiv.org/abs/2510.08049) `arXiv 2025`
1. CARL: Focusing Agentic Reinforcement Learning on Critical Actions. [[Paper]](https://arxiv.org/abs/2512.04949) `arXiv 2025`
1. Enhancing Agentic RL with Progressive Reward Shaping and Value-based Sampling Policy Optimization. [[Paper]](https://arxiv.org/abs/2512.07478) `arXiv 2025`
1. SLATE: Step-Level Advantage Estimation for Truncated Exploration. [[Paper]](https://arxiv.org/abs/2602.23440) [[Code]](https://github.com/algoprog/SLATE) `arXiv 2026`
#### 4.3.3 Algorithms
##### Optimization Objectives
1. Deep Reinforcement Learning from Human Preferences. [[Paper]](https://arxiv.org/abs/1706.03741) `NeurIPS 2017`
1. Fine-Tuning Language Models from Human Preferences. [[Paper]](https://arxiv.org/abs/1909.08593) [[Code]](https://github.com/openai/lm-human-preferences) `arXiv 2019`
1. Learning to Summarize from Human Feedback. [[Paper]](https://arxiv.org/abs/2009.01325) [[Code]](https://github.com/openai/summarize-from-feedback) `NeurIPS 2020`
1. Training Language Models to Follow Instructions with Human Feedback. [[Paper]](https://arxiv.org/abs/2203.02155) `NeurIPS 2022`
1. Training a Helpful and Harmless Assistant with Reinforcement Learning from Human Feedback. [[Paper]](https://arxiv.org/abs/2204.05862) [[Code]](https://github.com/anthropics/hh-rlhf) `arXiv 2022`
1. A General Theoretical Paradigm to Understand Learning from Human Preferences. [[Paper]](https://arxiv.org/abs/2310.12036) `AISTATS 2024`
1. Nash Learning from Human Feedback. [[Paper]](https://arxiv.org/abs/2312.00886) `ICML 2024`
1. Self-Play Fine-Tuning Converts Weak Language Models to Strong Language Models. [[Paper]](https://arxiv.org/abs/2401.01335) [[Code]](https://github.com/uclaml/SPIN) `ICML 2024`
1. WARM: On the Benefits of Weight Averaged Reward Models. [[Paper]](https://arxiv.org/abs/2401.12187) `ICML 2024`
1. Direct Nash Optimization: Teaching Language Models to Self-Improve with General Preferences. [[Paper]](https://arxiv.org/abs/2404.03715) `arXiv 2024`
1. Iterative Nash Policy Optimization: Aligning LLMs with General Preferences via No-Regret Learning (INPO). [[Paper]](https://arxiv.org/abs/2407.00617) `ICLR 2025`
1. Kimi k1.5: Scaling Reinforcement Learning with LLMs. [[Paper]](https://arxiv.org/abs/2501.12599) `arXiv 2025`
1. DAPO: An Open-Source LLM Reinforcement Learning System at Scale. [[Paper]](https://arxiv.org/abs/2503.14476) [[Code]](https://dapo-sia.github.io/) `NeurIPS 2025`
1. Demystifying Group Relative Policy Optimization: Its Policy Gradient is a U-Statistic. [[Paper]](https://arxiv.org/abs/2603.01162) `arXiv 2026`
##### Critic-based Algorithms
1. Proximal Policy Optimization Algorithms (PPO). [[Paper]](https://arxiv.org/abs/1707.06347) `arXiv 2017`
1. Secrets of RLHF in Large Language Models Part I: PPO. [[Paper]](https://arxiv.org/abs/2307.04964) [[Code]](https://github.com/OpenLMLab/MOSS-RLHF) `arXiv 2023`
1. Secrets of RLHF in Large Language Models Part II: Reward Modeling. [[Paper]](https://arxiv.org/abs/2401.06080) [[Code]](https://github.com/OpenLMLab/MOSS-RLHF) `arXiv 2024`
1. ArCHer: Training Language Model Agents via Hierarchical Multi-Turn RL. [[Paper]](https://arxiv.org/abs/2402.19446) [[Code]](https://github.com/YifeiZhou02/ArCHer) `ICML 2024`
1. WARP: On the Benefits of Weight Averaged Rewarded Policies. [[Paper]](https://arxiv.org/abs/2406.16768) `arXiv 2024`
1. VinePPO: Unlocking RL Potential For LLM Reasoning Through Refined Credit Assignment. [[Paper]](https://arxiv.org/abs/2410.01679) [[Code]](https://github.com/McGill-NLP/VinePPO) `ICLR 2025`
1. LLM Collaboration With Multi-Agent Reinforcement Learning. [[Paper]](https://arxiv.org/abs/2508.04652) `arXiv 2025`
##### Critic-free Algorithms
1. Direct Preference Optimization: Your Language Model is Secretly a Reward Model. [[Paper]](https://arxiv.org/abs/2305.18290) [[Code]](https://github.com/eric-mitchell/direct-preference-optimization) `NeurIPS 2023`
1. ReMax: A Simple, Effective, and Efficient RL Method for Aligning Large Language Models. [[Paper]](https://arxiv.org/abs/2310.10505) [[Code]](https://github.com/liziniu/ReMax) `ICML 2024`
1. KTO: Model Alignment as Prospect Theoretic Optimization. [[Paper]](https://arxiv.org/abs/2402.01306) [[Code]](https://github.com/ContextualAI/HALOs) `ICML 2024`
1. DeepSeekMath: Pushing the Limits of Mathematical Reasoning in Open Language Models. [[Paper]](https://arxiv.org/abs/2402.03300) [[Code]](https://github.com/deepseek-ai/DeepSeek-Math) `arXiv 2024`
1. Back to Basics: Revisiting REINFORCE-Style Optimization for Learning from Human Feedback in LLMs. [[Paper]](https://arxiv.org/abs/2402.14740) `ACL 2024`
1. ORPO: Monolithic Preference Optimization without Reference Model. [[Paper]](https://arxiv.org/abs/2403.07691) [[Code]](https://github.com/xfactlab/orpo) `EMNLP 2024`
1. SimPO: Simple Preference Optimization with a Reference-Free Reward. [[Paper]](https://arxiv.org/abs/2405.14734) [[Code]](https://github.com/princeton-nlp/SimPO) `NeurIPS 2024`
1. DeepSeek-R1: Incentivizing Reasoning Capability in LLMs via Reinforcement Learning. [[Paper]](https://arxiv.org/abs/2501.12948) [[Code]](https://github.com/deepseek-ai/DeepSeek-R1) `Nature 2025`
1. Understanding R1-Zero-Like Training: A Critical Perspective. [[Paper]](https://arxiv.org/abs/2503.20783) [[Code]](https://github.com/sail-sg/understand-r1-zero) `COLM 2025`
1. StarPO: State-Thinking-Actions-Reward Policy Optimization. [[Paper]](https://arxiv.org/abs/2504.20073) [[Code]](https://github.com/RAGEN-AI/RAGEN) `arXiv 2025`
1. ReTool: Reinforcement Learning for Strategic Tool Use in LLMs. [[Paper]](https://arxiv.org/abs/2504.11536) [[Code]](https://github.com/ReTool-RL/ReTool) `arXiv 2025`
1. GiGPO: Group-in-Group Policy Optimization for LLM Agent Training. [[Paper]](https://arxiv.org/abs/2505.10978) [[Code]](https://github.com/langfengQ/verl-agent) `arXiv 2025`
1. ARTIST: Agentic Reasoning and Tool Integration for LLMs via Reinforcement Learning. [[Paper]](https://arxiv.org/abs/2505.01441) `arXiv 2025`
1. ARPO: Agentic Reinforced Policy Optimization. [[Paper]](https://arxiv.org/abs/2507.19849) [[Code]](https://github.com/dongguanting/ARPO) `arXiv 2025`
1. ML-Agent: Reinforcing LLM Agents for Autonomous Machine Learning Engineering. [[Paper]](https://openreview.net/forum?id=AEgyitdRWf) `OpenReview`
1. AEPO: Agentic Entropy-Balanced Policy Optimization. [[Paper]](https://arxiv.org/abs/2510.14545) [[Code]](https://github.com/RUC-NLPIR/ARPO) `arXiv 2025`
1. Tool Zero: Training Tool-Augmented LLMs via Pure Reinforcement Learning from Scratch. [[Paper]](https://arxiv.org/abs/2511.01934) `arXiv 2025`
1. CARL: Focusing Agentic Reinforcement Learning on Critical Actions. [[Paper]](https://arxiv.org/abs/2512.04949) `arXiv 2025`
#### 4.3.4 Infrastructure
##### Basic Frameworks
1. TRL: Transformer Reinforcement Learning. [[Paper]](https://huggingface.co/docs/trl/en/index) [[Code]](https://github.com/huggingface/trl) `2020`
1. Colossal-AI: A Unified Deep Learning System For Large-Scale Parallel Training. [[Paper]](https://arxiv.org/abs/2110.14883) [[Code]](https://github.com/hpcaitech/ColossalAI) `arXiv 2021`
1. DeepSpeed-Chat: Easy, Fast and Affordable RLHF Training of ChatGPT-like Models at All Scales. [[Paper]](https://arxiv.org/abs/2308.01320) [[Code]](https://github.com/microsoft/DeepSpeedExamples) `arXiv 2023`
1. OpenRLHF: An Easy-to-use, Scalable and High-performance RLHF Framework. [[Paper]](https://arxiv.org/abs/2405.11143) [[Code]](https://github.com/OpenRLHF/OpenRLHF) `arXiv 2024`
1. NeMo-Aligner: Scalable Toolkit for Efficient Model Alignment. [[Paper]](https://arxiv.org/abs/2405.01481) [[Code]](https://github.com/NVIDIA/NeMo-Aligner) `COLM 2024`
1. ReaLHF: Optimized RLHF Training for Large Language Models through Parameter Reallocation. [[Paper]](https://arxiv.org/abs/2406.14088) [[Code]](https://github.com/openpsi-project/ReaLHF) `MLSys 2025`
1. HybridFlow: A Flexible and Efficient RLHF Framework (veRL). [[Paper]](https://arxiv.org/abs/2409.19256) [[Code]](https://github.com/volcengine/verl) `EuroSys 2025`
1. Asynchronous RLHF: Faster and More Efficient Off-Policy RL for Language Models. [[Paper]](https://arxiv.org/abs/2410.18252) [[Code]](https://github.com/mnoukhov/async_rlhf) `ICLR 2025`
1. Open-Reasoner-Zero: An Open Source Approach to Scaling Up RL on the Base Model. [[Paper]](https://arxiv.org/abs/2503.24290) [[Code]](https://github.com/Open-Reasoner-Zero/Open-Reasoner-Zero) `NeurIPS 2025`
1. AReaL: A Large-Scale Asynchronous Reinforcement Learning System for Language Reasoning. [[Paper]](https://arxiv.org/abs/2505.24298) [[Code]](https://github.com/inclusionAI/AReaL) `arXiv 2025`
1. ROLL: Reinforcement Learning Optimization for Large-scale Learning. [[Paper]](https://arxiv.org/abs/2506.06122) [[Code]](https://github.com/alibaba/ROLL) `arXiv 2025`
##### Specialized Frameworks
##### Agentic, multi-agent, multimodal
1. AgentGym: Evolving Large Language Model-based Agents across Diverse Environments. [[Paper]](https://arxiv.org/abs/2406.04151) [[Code]](https://github.com/WooooDyy/AgentGym) `arXiv 2024`
1. Agent Q: Advanced Reasoning and Learning for Autonomous AI Agents. [[Paper]](https://arxiv.org/abs/2408.07199) [[Code]](https://github.com/sentient-engineering/agent-q) `arXiv 2024`
1. WebRL: Training LLM Web Agents via Self-Evolving Online Curriculum RL. [[Paper]](https://arxiv.org/abs/2411.02337) [[Code]](https://github.com/THUDM/WebRL) `ICLR 2025`
1. AgentTrek: Agent Trajectory Synthesis via Guiding Replay with Web Tutorials. [[Paper]](https://arxiv.org/abs/2412.09605) [[Code]](https://agenttrek.github.io/) `arXiv 2024`
1. RAGEN: Understanding Self-Evolution in LLM Agents via Multi-Turn Reinforcement Learning. [[Paper]](https://arxiv.org/abs/2504.20073) [[Code]](https://github.com/RAGEN-AI/RAGEN) `arXiv 2025`
1. verl-agent: Extension of veRL for LLM/VLM Agent RL Training. [[Paper]](https://arxiv.org/abs/2505.10978) [[Code]](https://github.com/langfengQ/verl-agent) `arXiv 2025`
1. Agent Lightning: Train ANY AI Agents with Reinforcement Learning. [[Paper]](https://arxiv.org/abs/2508.03680) [[Code]](https://github.com/microsoft/agent-lightning) `arXiv 2025`
1. LLM Collaboration With Multi-Agent Reinforcement Learning (MAGRPO). [[Paper]](https://arxiv.org/abs/2508.04652) `arXiv 2025`
1. VerlTool: Towards Holistic Agentic Reinforcement Learning with Tool Use. [[Paper]](https://arxiv.org/abs/2509.01055) [[Code]](https://github.com/TIGER-AI-Lab/verl-tool) `arXiv 2025`
1. AgentGym-RL: Training LLM Agents for Long-Horizon Decision Making through Multi-Turn RL. [[Paper]](https://arxiv.org/abs/2509.08755) [[Code]](https://github.com/WooooDyy/AgentGym-RL) `arXiv 2025`
1. AgentRL: Scaling Agentic RL with a Multi-Turn, Multi-Task Framework. [[Paper]](https://arxiv.org/abs/2510.04206) [[Code]](https://github.com/THUDM/AgentRL) `arXiv 2025`
1. Agent-R1: Training Powerful LLM Agents with End-to-End Reinforcement Learning. [[Paper]](https://arxiv.org/abs/2511.14460) [[Code]](https://github.com/AgentR1/Agent-R1) `arXiv 2025`
1. SkyRL-Agent: Efficient RL Training for Multi-turn LLM Agent. [[Paper]](https://arxiv.org/abs/2511.16108) [[Code]](https://github.com/NovaSky-AI/SkyRL) `arXiv 2025`
1. Agent0: Unleashing Self-Evolving Agents from Zero Data via Tool-Integrated Reasoning. [[Paper]](https://arxiv.org/abs/2511.16043) [[Code]](https://github.com/aiming-lab/Agent0) `arXiv 2025`
1. RollArc: Scaling Agentic RL Training via Disaggregated Infrastructure. [[Paper]](https://arxiv.org/abs/2512.22560) `arXiv 2025`
## 5. Benchmarks and Evaluation
### 5.1 DeepResearch Tasks
1. Deep Research Bench: Evaluating AI Web Research Agents. [[Paper]](https://arxiv.org/pdf/2506.06287) `arXiv 2025`
1. DeepResearch Bench: A Comprehensive Benchmark for Deep Research Agents. [[Paper]](https://arxiv.org/pdf/2506.11763) [[Code]](https://github.com/Ayanami0730/deep_research_bench) `ICLR 2026 Poster`
1. ResearcherBench: Evaluating Deep AI Research Systems on the Frontiers of Scientific Inquiry. [[Paper]](https://arxiv.org/pdf/2507.16280) [[Code]](https://github.com/GAIR-NLP/ResearcherBench) `arXiv 2025`
1. ReportBench: Evaluating Deep Research Agents via Academic Survey Tasks. [[Paper]](https://arxiv.org/pdf/2508.15804) [[Code]](https://github.com/ByteDance-BandAI/ReportBench) `arXiv 2025`
1. Characterizing Deep Research: A Benchmark and Formal Definition. [[Paper]](https://arxiv.org/pdf/2508.04183) [[Code]](https://github.com/microsoft/LiveDRBench) `arXiv 2025`
1. LiveResearchBench: A Live Benchmark for User-Centric Deep Research in the Wild. [[Paper]](https://arxiv.org/pdf/2510.14240) [[Code]](https://github.com/SalesforceAIResearch/LiveResearchBench) `ICLR 2026 Poster`
1. ResearchRubrics: A Benchmark of Prompts and Rubrics For Evaluating Deep Research Agents. [[Paper]](https://arxiv.org/pdf/2511.07685) [[Code]](https://github.com/scaleapi/researchrubrics) `ICLR 2026 Poster`
1. DEER: A Comprehensive and Reliable Benchmark for Deep-Research Expert Reports. [[Paper]](https://arxiv.org/pdf/2512.17776) [[Code]](https://github.com/hanjanghoon/DEER) `arXiv 2025`
1. DeepSynth-Eval: Objectively Evaluating Information Consolidation in Deep Survey Writing. [[Paper]](https://arxiv.org/pdf/2601.03540) `arXiv 2026`
1. DeepSurvey-Bench: Evaluating Academic Value of Automatically Generated Scientific Survey. [[Paper]](https://arxiv.org/pdf/2601.15307) `arXiv 2026`
1. A Benchmark for Deep Information Synthesis. [[Paper]](https://arxiv.org/pdf/2602.21143) [[Code]](https://github.com/agentdeepsynthesis/deepsynth-bench) `ICLR 2026 Poster`
1. DeepResearch-9K: A Challenging Benchmark Dataset of Deep-Research Agent. [[Paper]](https://arxiv.org/pdf/2603.01152) [[Code]](https://github.com/Applied-Machine-Learning-Lab/DeepResearch-R1) `arXiv 2026`
### 5.2 Software Engineering Tasks
1. RepoBench: Benchmarking Repository-Level Code Auto-Completion Systems. [[Paper]](https://arxiv.org/pdf/2306.03091) [[Code]](https://github.com/Leolty/repobench) `ICLR 2024 Poster`
1. SWE-bench: Can Language Models Resolve Real-World GitHub Issues? [[Paper]](https://arxiv.org/pdf/2310.06770) [[Code]](https://github.com/princeton-nlp/SWE-bench) `ICLR 2024 Oral`
1. CodeAgent: Enhancing Code Generation with Tool-Integrated Agent Systems for Real-World Repo-level Coding Challenges. [[Paper]](https://arxiv.org/pdf/2401.07339) `ACL 2024`
1. LiveCodeBench: Holistic and Contamination Free Evaluation of Large Language Models for Code. [[Paper]](https://arxiv.org/pdf/2403.07974) [[Code]](https://github.com/LiveCodeBench/LiveCodeBench) `ICLR 2025 Poster`
1. DevEval: A Manually-Annotated Code Generation Benchmark Aligned with Real-World Code Repositories. [[Paper]](https://arxiv.org/pdf/2405.19856) [[Code]](https://github.com/seketeam/DevEval) `ACL Findings 2024`
1. BigCodeBench: Benchmarking Code Generation with Diverse Function Calls and Complex Instructions. [[Paper]](https://arxiv.org/pdf/2406.15877) [[Code]](https://github.com/bigcode-project/bigcodebench) `ICLR 2025 Oral`
1. Can Language Models Replace Programmers? REPOCOD Says "Not Yet". [[Paper]](https://arxiv.org/pdf/2410.21647) [[Code]](https://github.com/lt-asset/REPOCOD) `ACL 2025`
1. HumanEval Pro and MBPP Pro: Evaluating Large Language Models on Self-invoking Code Generation Task. [[Paper]](https://arxiv.org/pdf/2412.21199) [[Code]](https://github.com/CodeEval-Pro/CodeEval-Pro) `ACL Findings 2025`
1. Commit0: Library Generation from Scratch. [[Paper]](https://arxiv.org/pdf/2412.01769) [[Code]](https://github.com/commit-0/commit0) `ICLR 2025 Poster`
1. FEA-Bench: A Benchmark for Evaluating Repository-Level Code Generation for Feature Implementation. [[Paper]](https://arxiv.org/pdf/2503.06680) [[Code]](https://github.com/microsoft/FEA-Bench) `ACL 2025`
1. AutoCodeBench: Large Language Models are Automatic Code Benchmark Generators. [[Paper]](https://arxiv.org/pdf/2508.09101) [[Code]](https://github.com/Tencent-Hunyuan/AutoCodeBenchmark) `ICLR 2026 Poster`
1. SWE-Universe: Scale Real-World Verifiable Environments to Millions. [[Paper]](https://arxiv.org/pdf/2602.02361) `arXiv 2026`
1. FeatureBench: Benchmarking Agentic Coding for Complex Feature Development. [[Paper]](https://arxiv.org/pdf/2602.10975) [[Code]](https://github.com/LiberCoders/FeatureBench) `ICLR 2026 Poster`
### 5.3 Tool Use and Function Calling Tasks
1. API-Bank: A Comprehensive Benchmark for Tool-Augmented LLMs. [[Paper]](https://arxiv.org/pdf/2304.08244) [[Code]](https://github.com/AlibabaResearch/DAMO-ConvAI/tree/main/api-bank) `EMNLP 2023`
1. ToolLLM: Facilitating Large Language Models to Master 16000+ Real-world APIs. [[Paper]](https://arxiv.org/pdf/2307.16789) [[Code]](https://github.com/OpenBMB/ToolBench) `ICLR 2024 Spotlight`
1. AgentBench: Evaluating LLMs as Agents. [[Paper]](https://arxiv.org/pdf/2308.03688) [[Code]](https://github.com/THUDM/AgentBench) `ICLR 2024 Poster`
1. GAIA: a benchmark for General AI Assistants. [[Paper]](https://arxiv.org/pdf/2311.12983) [[Code]](https://huggingface.co/gaia-benchmark) `ICLR 2024 Poster`
1. $\tau$-bench: A Benchmark for Tool-Agent-User Interaction in Real-World Domains. [[Paper]](https://arxiv.org/pdf/2406.12045) [[Code]](https://github.com/sierra-research/tau-bench) `arXiv 2024`
1. AppWorld: A Controllable World of Apps and People for Benchmarking Interactive Coding Agents. [[Paper]](https://arxiv.org/pdf/2407.18901) [[Code]](https://github.com/StonyBrookNLP/appworld) `ACL 2024`
1. AssistantBench: Can Web Agents Solve Realistic and Time-Consuming Tasks? [[Paper]](https://arxiv.org/pdf/2407.15711) [[Code]](https://github.com/oriyor/assistantbench) `EMNLP 2024`
1. ToolSandbox: A Stateful, Conversational, Interactive Evaluation Benchmark for LLM Tool Use Capabilities. [[Paper]](https://arxiv.org/pdf/2408.04682) [[Code]](https://github.com/apple/ToolSandbox) `NAACL 2025 Findings`
1. $\tau^2$-Bench: Evaluating Conversational Agents in a Dual-Control Environment. [[Paper]](https://arxiv.org/pdf/2506.07982) [[Code]](https://github.com/sierra-research/tau2-bench) `arXiv 2025`
1. The Berkeley Function Calling Leaderboard (BFCL): From Tool Use to Agentic Evaluation of Large Language Models. [[Paper]](https://openreview.net/pdf?id=2GmDdhBdDk) [[Code]](https://github.com/ShishirPatil/gorilla/tree/main/berkeley-function-call-leaderboard) `ICML 2025`
1. Towards Reliable Benchmarking: A Contamination Free, Controllable Evaluation Framework for Multi-step LLM Function Calling. [[Paper]](https://arxiv.org/pdf/2509.26553) [[Code]](https://github.com/megagonlabs/FuncBenchGen) `ICLR 2026 Poster`
### 5.4 Computer Use and GUI Tasks
1. Mind2Web: Towards a Generalist Agent for the Web. [[Paper]](https://arxiv.org/pdf/2306.06070) [[Code]](https://github.com/OSU-NLP-Group/Mind2Web) `NeurIPS 2023 Datasets and Benchmarks Poster`
1. WebArena: A Realistic Web Environment for Building Autonomous Agents. [[Paper]](https://arxiv.org/pdf/2307.13854) [[Code]](https://github.com/web-arena-x/webarena) `ICLR 2024 Poster`
1. Android in the Wild: A Large-Scale Dataset for Android Device Control. [[Paper]](https://arxiv.org/pdf/2307.10088) [[Code]](https://github.com/google-research/google-research/tree/master/android_in_the_wild) `NeurIPS 2023 Datasets and Benchmarks Poster`
1. VisualWebArena: Evaluating Multimodal Agents on Realistic Visual Web Tasks. [[Paper]](https://arxiv.org/pdf/2401.13649) [[Code]](https://github.com/web-arena-x/visualwebarena) `ICLR 2024 Poster + ACL 2024`
1. WorkArena: How Capable Are Web Agents at Solving Common Knowledge Work Tasks? [[Paper]](https://arxiv.org/pdf/2403.07718) [[Code]](https://github.com/ServiceNow/WorkArena) `ICLR 2024 Poster`
1. OSWorld: Benchmarking Multimodal Agents for Open-Ended Tasks in Real Computer Environments. [[Paper]](https://arxiv.org/pdf/2404.07972) [[Code]](https://github.com/xlang-ai/OSWorld) `NeurIPS 2024 Track Datasets and Benchmarks Poster`
1. AndroidWorld: A Dynamic Benchmarking Environment for Autonomous Agents. [[Paper]](https://arxiv.org/pdf/2405.14573) [[Code]](https://github.com/google-research/android_world) `ICLR 2025 Poster`
1. Windows Agent Arena: Evaluating Multi-Modal OS Agents at Scale. [[Paper]](https://arxiv.org/pdf/2409.08264) [[Code]](https://github.com/microsoft/WindowsAgentArena) `ICML 2025 Poster`
1. ScreenSpot-Pro: GUI Grounding for Professional High-Resolution Computer Use. [[Paper]](https://arxiv.org/pdf/2504.07981) [[Code]](https://github.com/likaixin2000/ScreenSpot-Pro-GUI-Grounding) `ICLR 2025 Poster`
1. OSWorld-MCP: Benchmarking MCP Tool Invocation In Computer-Use Agents. [[Paper]](https://arxiv.org/pdf/2510.24563) [[Code]](https://github.com/X-PLUG/OSWorld-MCP) `ICLR 2026 Poster`
### 5.5 Machine Learning Engineering and Scientific Research Tasks
1. DS-1000: A Natural and Reliable Benchmark for Data Science Code Generation. [[Paper]](https://arxiv.org/pdf/2211.11501) [[Code]](https://github.com/xlang-ai/DS-1000) `ICML 2023 Poster`
1. MLAgentBench: Evaluating Language Agents on Machine Learning Experimentation. [[Paper]](https://arxiv.org/pdf/2310.03302) [[Code]](https://github.com/snap-stanford/MLAgentBench) `ICML 2024`
1. DA-Code: Agent Data Science Code Generation Benchmark for Large Language Models. [[Paper]](https://arxiv.org/pdf/2410.07331) [[Code]](https://github.com/yiyihum/da-code) `EMNLP 2024`
1. ScienceAgentBench: Toward Rigorous Assessment of Language Agents for Data-Driven Scientific Discovery. [[Paper]](https://arxiv.org/pdf/2410.05080) [[Code]](https://github.com/OSU-NLP-Group/ScienceAgentBench) `ICLR 2025 Poster`
1. MLE-bench: Evaluating Machine Learning Agents on Machine Learning Engineering. [[Paper]](https://arxiv.org/pdf/2410.07095) [[Code]](https://github.com/openai/mle-bench) `ICLR 2025`
1. PaperBench: Evaluating AI's Ability to Replicate AI Research. [[Paper]](https://arxiv.org/pdf/2504.01848) [[Code]](https://github.com/openai/preparedness) `arXiv 2025`
1. MLR-Bench: Evaluating AI Agents on Open-Ended Machine Learning Research. [[Paper]](https://arxiv.org/pdf/2505.19955) [[Code]](https://github.com/chchenhui/mlrbench) `NeurIPS 2025 Track Datasets and Benchmarks Poster`
1. FML-bench: A Benchmark for Automatic ML Research Agents Highlighting the Importance of Exploration Breadth. [[Paper]](https://arxiv.org/pdf/2510.10472) [[Code]](https://github.com/qrzou/FML-bench) `arXiv 2025`
1. ReplicatorBench: Benchmarking LLM Agents for Replicability in Social and Behavioral Sciences. [[Paper]](https://arxiv.org/pdf/2602.11354) [[Code]](https://github.com/CenterForOpenScience/llm-benchmarking) `arXiv 2026`
## Citation

If this repository helps your work, please consider citing the survey paper and starring this repository.
