---
layout: page
title: Syllabus
desc: "Information for 2026 Spring UVa CS -GenAI-Overview"
---


### [The official Academic Calendar at UVA Registrar](http://www.virginia.edu/registrar/calendar.html)


### Prerequisite:

+ Required courses as prerequisites: Machine Learning; Deep learning. The seminar is for research-focused graduate students with interests in generative deep learning models, foundations, applications, and related LLM Agents topics. 


### General Description and Disclaimer: 

+ The course will take the form of a combination of seminar, lectures by the instructor and project deliverables from students. 

+ TuTh 3:30pm - 4:45pm  
+ Rice Hall

+ It is quite hard to make important topics of Generative AI fit on a one-semester schedule.  We aim to make the course reasonably digestible in an seminar team-learning manner. Our goals here are to highlight the most timing research topics relating to GenAI. We think this teaching style provides students with research centered learning on both knowledge and workflows, helping them build a quick understanding of State-of-the-Art in GenAI.

+ 2025 spring's same course website was [here](https://qiyanjun.github.io/2025sp-GenAI-overview/)
  - [25 Spring course's students project github HERE](https://github.com/Qdata4Capstone/uva-25-spring-genai-students-projects/tree/main/students-projects-code)

+ 2024 spring's same course website was [here](https://qiyanjun.github.io/2024sp-GenAI-Risk-Benefits/)

+ ATT: This year we expand and put much more emphasis on the course projects than the previous two. 


### Course Expectations

Student teams (size 3) in the seminar are expected to:

+ Present One SOTA Topics. For each topic, a slide deck and an in-class presentation is expected from a team: 
  - Example of Slide deck: [here](https://qiyanjun.github.io/2024sp-GenAI-Risk-Benefits//Lectures/W3-LLMEvaluation-Team5.pdf)
  - We recommend students to use 365 powerpoint [here](https://virginia.service-now.com/its?id=itsweb_kb_article&sys_id=713ff34fdb3ac744f032f1f51d961937#login) to support their co-editing of presentation slide decks. 

+ Finish Two course projects  
  - More details on final project, please check out the Project Page via sidebar! 

+ Participate actively in class meets. This means being prepared to contribute by presenting assigned papers, and working activerly on your course projects.


### Course Websites

+ Course schedule and materials  @ [https://qiyanjun.github.io/2025sp-GenAI-overview/](https://qiyanjun.github.io/2025sp-GenAI-overview/)

+  Assignment submissions via [Cavas site:](https://canvas.its.virginia.edu) 

+ Course annoucement via: [?]

+ Course Discussion via Course Slack Space (please ask TA to get you in!) 


+ ##### Instructors: 
  - Prof. [Yanjun Qi](https://qiyanjun.github.io/Homepage/) / [yanjun@virginia.edu](mailto:?);
  - TA: [?] 
  - Instructor office hour: TBD
  - TA office hours: TBD


### Course Grading Policy

+ No exams in this course.
+ Sit-in: No. This course is for registered students only.

+ Final grades will be based on.
  - 15% for the quality of your seminar presentations; 
  - 15% for the course attendance 
  - 35% for the quality of your first course projects; 
  - 35% for the quality of your second course projects; 




## Course Framework Overview

We use a course content organization that emphasizes the modular, compositional nature of modern agent architectures. 
It follows the **Perception → World Modeling → Planning → Action → Learning** cycle that defines modern LLM agent architectures:

**Course Organization:** 

This syllabus is organized around the core components of LLM agent architectures: Brain (Reasoning Engine), Perception (Input Processing), 
Memory Systems, Action & Tools, Planning & Orchestration, Multi-Agent Collaboration, and Safety & Evaluation.

**Note:** This schedule is tentative and continually subject to change. We will move at whatever pace we find comfortable.


```
┌─────────────────────────────────────────────────────────────┐
│                     AGENT ARCHITECTURE                       │
├─────────────────────────────────────────────────────────────┤
│                                                              │
│  BRAIN (Reasoning Engine) ────────────────────┐            │
│   ↓                                            │            │
│  PERCEPTION (Input Processing) ←───────────────┤            │
│   ↓                                            │            │
│  MEMORY (Context & Knowledge) ←────────────────┤            │
│   ↓                    ↓                       │            │
│  WORLD MODEL (Environment Understanding) ←─────┤            │
│   ↓                                            │            │
│  PLANNING (Task Decomposition) ←───────────────┤            │
│   ↓                                            │            │
│  ACTION (Tool Use & Execution) ←───────────────┤            │
│   ↓                                            │            │
│  MULTI-AGENT (Collaboration) ←─────────────────┤            │
│   ↓                                            │            │
│  SAFETY & EVALUATION ──────────────────────────┘            │
│   ↓                                                          │
│  DEPLOYMENT & SERVING                                        │
│                                                              │
└─────────────────────────────────────────────────────────────┘
```

## Learning Objectives by Phase (Roughly per week one phase to cover this Semester)

**Phase 1 (Foundations & Overview):** Grasp the fundamental concepts and architecture of LLM agents
**Phase 2 (Brain & Reasoning): ** Understand the core LLM capabilities that enable agentic behavior
**Phase 3 (Perception):** Learn how agents process multimodal and domain-specific inputs
**Phase 4 (Memory):** Master memory architectures and knowledge management systems
**Phase 5 (Action & Tools):** Develop skills in tool integration and agent-computer interfaces
**Phase 6 (World Models):** Explore how agents build internal representations of their environment
**Phase 7 (Planning):** Study planning algorithms and task orchestration strategies
**Phase 8 (Multi-Agent):** Understand collaborative agent systems and communication protocols
**Phase 9 (Safety):** Address ethical, safety, and alignment challenges in agent deployment
**Phase 10 (Training):** Learn optimization and customization techniques
**Phase 11 (Deployment):** Understand production infrastructure and serving systems


---

## PHASE 1: FOUNDATIONS - The Agent "Basics" 

**Core Component:** LLM as the Central Reasoning Engine

Understanding the foundation model that serves as the "brain" of agentic systems - the core reasoning, language understanding, and decision-making capabilities.

**Key Concepts:** Deep neural networks, transformer architecture, emergent abilities, multimodal capabilities, recent architectural advances




### Here are the related slide deck from the previous two course offerings:

| Topic | Slide Deck | Previous Semester  |
|-------|------------|-------------------|
| Introduction to Deep NLP Basics | W1.1-deepNNtext | [25course](https://qiyanjun.github.io/2025sp-GenAI-overview/) |
| LLM Basics - Emergent Ability and GenAI Platform | W1.2-IntroLLMv3 | [25course](https://qiyanjun.github.io/2025sp-GenAI-overview/) |
| More LLM Basics - A Survey | W2.1-moreLLM |  [25course](https://qiyanjun.github.io/2025sp-GenAI-overview/) |
| LLM Basics Foundation | S0-Intro | [24course](https://qiyanjun.github.io/2024sp-GenAI-Risk-Benefits/) |
| Survey: LLMs and Multimodal FMs | S1-LLM | [24course](https://qiyanjun.github.io/2024sp-GenAI-Risk-Benefits/) |
| Recent LLM Basics | W13-RecentLLMbasics | [24course](https://qiyanjun.github.io/2024sp-GenAI-Risk-Benefits/) |
| Advanced Transformer Architectures | W14_LLM_advanced_arch |  [24course](https://qiyanjun.github.io/2024sp-GenAI-Risk-Benefits/) |


### 2025 HIGH-IMPACT PAPERS on this topic 

#### a. **Large Language Model Agent: A Survey on Methodology, Applications and Challenges** (March 2025)
- **Link:** https://arxiv.org/abs/2503.21460
- **GitHub:** https://github.com/luo-junyu/Awesome-Agent-Papers
- **Framework Coverage:** Brain-Perception-Action model, memory systems, planning mechanisms, multi-agent coordination, evolutionary pathways, evaluation methodologies


#### b. **A Survey on Large Language Model based Autonomous Agents** (Updated March 2025)
- **Links:**
  - arXiv: https://arxiv.org/abs/2308.11432  
- Unified framework: Brain (profiling, memory, planning, action)
- Extensive application coverage: single-agent, multi-agent, human-agent cooperation
- Agent societies analysis: behavior, personality, social phenomena


---

## PHASE 2: REASONING & COGNITION 
**Core Component:** Advanced Reasoning Capabilities of the Agent Brain

Exploring how agents reason through complex problems, including code generation, mathematical reasoning, and domain-specific reasoning.

**Key Concepts:** Chain-of-thought reasoning, code generation, mathematical reasoning, self-examination, test-time compute scaling

| Topic | Slide Deck | Previous Semester  |
|-------|------------|-------------------|
| Advanced LLM - Code Reasoning | W4.1-Gen AI-code |  [25course](https://qiyanjun.github.io/2025sp-GenAI-overview/)  |
| Advanced LLM - Math Reasoning | W4.2-LLM-Math-Reasoning |  [25course](https://qiyanjun.github.io/2025sp-GenAI-overview/)  |
| Inference Test Time Scaling Law | Week14.1-T5-Test-Time-Scaling | [25course](https://qiyanjun.github.io/2025sp-GenAI-overview/) |
| Self-exam LLM and Reasoning | W12-team-2-self-exam-LLM | [24course](https://qiyanjun.github.io/2024sp-GenAI-Risk-Benefits/)  |

### 2025 HIGH-IMPACT PAPERS on this topic 
#### a. ⭐ **DeepSeek-R1: Incentivizing Reasoning Capability in LLMs via Reinforcement Learning** (January 2025)
- **Authors:** DeepSeek-AI (198 authors)
- **Venue:** Nature (September 2025) + arXiv
- **Links:**
  - arXiv: https://arxiv.org/abs/2501.12948
  - Nature: https://www.nature.com/articles/s41586-025-09422-z  
  - HuggingFace: https://huggingface.co/papers/2501.12948
  - GitHub: https://github.com/deepseek-ai/DeepSeek-R1
- **Pure RL approach** - Shows reasoning emerges without supervised demonstrations
- **Remarkable results**: AIME 2024 accuracy jumped from 15.6% → 71.0% (pass@1) → 86.7% (majority voting), matching OpenAI o1
- **Emergent behaviors**: Self-reflection, verification, strategy adaptation, "aha moments"
- **Open source**: Released models from 1.5B to 671B parameters
- **Industry impact**: Triggered the "reasoning model" race across all major labs
- **Key Innovation:** Demonstrates that advanced reasoning patterns emerge naturally through GRPO (Group Relative Policy Optimization) without human-labeled trajectories. The paper shows thinking time scales with performance - agents learn to "think longer" for harder problems.


#### b. Reasoning Language Models: A Blueprint** (January 2025)
- **Link:** https://arxiv.org/abs/2501.11223

**Survey Focus:** Reinforcement learning approaches for reasoning
- Connects to DeepSeek-R1, Kimi k1.5, and other reasoning models
- Comprehensive taxonomy of RLVR (Reinforcement Learning with Verifiable Rewards)
- Discusses emergent reasoning patterns and distillation to smaller models


---

## PHASE 3: PERCEPTION & INPUT PROCESSING 

Understanding how agents perceive and process different types of information from their environment.

**Core Component:** How Agents Process and Understand Environmental Inputs
**Key Concepts:** Domain-specific perception, multimodal input processing, specialized domain understanding (bio, healthcare, robotics)


| Topic | Slide Deck | Previous Semester  |
|-------|------------|-------------------|
| Survey - BioScience LLMs | W2.2-bioLM | [25course](https://qiyanjun.github.io/2025sp-GenAI-overview/) |
| Survey - FMs in Healthcare | W3.1-GenAI-healthcare | [25course](https://qiyanjun.github.io/2025sp-GenAI-overview/) |
| Survey - FMs in Robotics | W3.2-GenAI-Robotics | [25course](https://qiyanjun.github.io/2025sp-GenAI-overview/) |
| Multimodal FMs - Video/Audio | W12.1.25-multimodalGenAI | [25course](https://qiyanjun.github.io/2025sp-GenAI-overview/) |
| Domain Centered FMs | W9-T2-domain-LLM | [24course](https://qiyanjun.github.io/2024sp-GenAI-Risk-Benefits/) |


### 2025 HIGH-IMPACT PAPERS on this topic 
#### a. **From Single-Agent to Multi-Agent: Legal Agents Review** (November 2025)
- **Venue:** AI Agent Journal 2025
- **Link:** https://www.oaepublish.com/articles/aiagent.2025.06
- **Core tasks**: Legal information retrieval, QA, judgment prediction, text generation
- **Evaluation benchmarks**: LAiW (Chinese practical), UCL-Bench (user-centric), JuDGE (judgment documents)
- **Single-agent challenges**: Trustworthiness, explainability, factuality
- **Multi-agent systems**: Collaborative reasoning, specialized roles (researcher, analyst, writer)
- **Future directions**: Cross-jurisdictional interoperability via legal knowledge graphs, ethical governance


#### b. **LitMOF: LLM-Driven Multi-Agent Curation of Materials Database** (December 2025)
- **Link:** https://arxiv.org/abs/2512.01693
- **Problem**: Nearly half of Metal-Organic Framework (MOF) database entries contain structural errors
- **Solution**: Multi-agent framework validating crystallographic information from literature
- **Results**:
  - Curated LitMOF-DB: 118,464 computation-ready structures
  - Corrected 69% (6,161 MOFs) of invalid entries in CoRE MOF database
  - Discovered 12,646 experimentally reported MOFs absent from existing resources
- **Paradigm:** Self-correcting scientific databases through LLM-driven curation


#### c. **LongVideoAgent: Multi-Agent Reasoning with Long Videos** (December 2025)
- **Link:** https://arxiv.org/abs/2512.20618
**Architecture:**
- **Master agent**: Coordinates with step limit, trained via RL
- **Grounding agent**: Localizes question-relevant segments
- **Vision agent**: Extracts targeted textual observations from video
- **Training:** Reinforcement learning to encourage concise, correct, efficient cooperation
- **Benchmark:** LongTVQA and LongTVQA+ (episode-level datasets from TVQA/TVQA+)
- **Results:** Significantly outperforms non-agent baselines on hour-long video reasoning


---

## PHASE 4: MEMORY SYSTEMS 

Exploring how agents maintain, retrieve, and use information across interactions.

**Core Component:** Agent Memory Architecture - Context, Knowledge, and Persistence
**Key Concepts:** RAG systems, long-term vs short-term memory, context window management, knowledge augmentation, hallucination mitigation, model editing


| Topic | Slide Deck | Previous Semester  |
|-------|------------|-------------------|
| Platform - Context Construction via RAG and Agent | W5.2.Team6-RAGagent | [25course](https://qiyanjun.github.io/2025sp-GenAI-overview/) |
| Platform - Long Context vs RAG + Hallucination | W9.2-Team2-longContext | [25course](https://qiyanjun.github.io/2025sp-GenAI-overview/) |
| Knowledge Augmented FMs | W8-T1-KnowledgeAugmentedFMs.pdf | [24course](https://qiyanjun.github.io/2024sp-GenAI-Risk-Benefits/) |
| LLM Hallucination | W9-Team3-P4-hallucination | [24course](https://qiyanjun.github.io/2024sp-GenAI-Risk-Benefits/) |


### 2025 HIGH-IMPACT PAPERS on this topic 
#### a. **Memory in the Age of AI Agents: A Survey** (2025)
- **GitHub Repository:** https://github.com/Shichun-Liu/Agent-Memory-Paper-List

**Comprehensive Coverage of Memory Systems:**
- **MIRIX**: Multi-Agent Memory System (July 2025)
- **Hierarchical Memory**: Efficient long-term reasoning (July 2025)
- **G-Memory**: Tracing memory for multi-agent systems (June 2025)
- **MemGuide**: Intent-driven memory selection (May 2025)
- **EverMemOS**: Self-organizing memory operating system (January 2026)
- **Key Distinction:** Agent memory vs LLM memory vs RAG vs context engineering

**Major Papers:**
- A-MEM: Agentic Memory for LLM Agents (Feb 2025)
- WorldMM: Dynamic Multimodal Memory Agent for Long Video Reasoning (Dec 2025)
- CAM: Constructivist View of Agentic Memory (Oct 2025)



---

## PHASE 5: ACTION & TOOL USE 
Understanding how agents execute actions through external tools, APIs, and interfaces.

**Core Component:** Agent-Computer Interface (ACI) - How Agents Interact with Tools and Systems
**Key Concepts:** Prompt engineering, tool calling, function APIs, agent tooling frameworks, efficient tool use



| Topic | Slide Deck | Previous Semester  |
|-------|------------|-------------------|
| Platform - Prompting Engineering Tools / Compression | W5.1.Team5-Prompt | [25course](https://qiyanjun.github.io/2025sp-GenAI-overview/) |
| Platform - Agent Tooling | W6.1-team2-master-ai-agent-book-review | [25course](https://qiyanjun.github.io/2025sp-GenAI-overview/) |
| Platform - More Agent Related | W6.2-team2-agent24-full | [25course](https://qiyanjun.github.io/2025sp-GenAI-overview/) |
| Prompt Engineering | W11-team-2-prompt-engineering-2 | [24course](https://qiyanjun.github.io/2024sp-GenAI-Risk-Benefits/) |
| Bonus Session: KV Cache, Tooling and WMDP | W15-KVcahe-WMDP-Tools | [24course](https://qiyanjun.github.io/2024sp-GenAI-Risk-Benefits/) |




### 2025 HIGH-IMPACT PAPERS on this topic 
#### a. **AgentGym-RL: Training Agents for Long-Horizon Decision Making** (September 2025)
- **GitHub:** https://github.com/WooooDyy/LLM-Agent-Paper-List
- **Innovation:** RL version of AgentGym for learning from interactive environments
- **Features:** Interactive frontend for trajectory visualization, multi-turn RL


---

## PHASE 6: WORLD MODELS & ENVIRONMENT UNDERSTANDING 
**Core Component:** Internal Representations - How Agents Model Their Environment

World models enable agents to build internal representations of their environment, predict outcomes, and simulate consequences before taking action. This bridges perception and planning.

**Key Concepts:** Environment modeling, state representation, predictive models, simulation-based planning, model-based reasoning

**World Model Role in Agent Architecture:**
- **Input:** Receives data from Perception (Phase 3) and Memory (Phase 4)
- **Function:** Builds internal representation of environment dynamics and causal relationships
- **Output:** Informs Planning (Phase 7) by enabling agents to predict action consequences
- **Use Cases:** Robotics, game playing, strategic decision-making, healthcare interventions


| Topic | Slide Deck | Previous Semester  |
|-------|------------|-------------------|
| Agent - Planning / World Model | W10.1-Team 3-Planning | [25course](https://qiyanjun.github.io/2025sp-GenAI-overview/) |



### 2025 HIGH-IMPACT PAPERS on this topic 
#### a. **Deep Research: A Survey of Autonomous Research Agents** (August 2025)
- **Link:** https://arxiv.org/html/2508.12752v1

**Research Agent Architecture:**
- **Planning strategies**: World model simulation, modular design search, human-like reasoning synthesis, self-refinement
- **World models**: LLMs as implicit world models, graph-based structured knowledge
- **Meta-learning**: MPO (Meta-Plan Optimization) - adaptive tuning across environments
- **Architecture search**: AgentSquare for automatic pipeline assembly

**DeepResearchBench:** Evaluates report fidelity, citation accuracy, comprehensive coverage

**Key Challenge:** Plan brittleness, lack of robustness to ambiguous queries, evaluation coarseness

#### b. **Towards Scientific Intelligence: LLM-based Scientific Agents** (2025)
- Roadmap for scientific discovery with LLM agents
- Differentiation from general agents

#### c. **A Survey of Data Science Agents** (Published October 2025)
- **Venue:** Journal of the American Statistical Association
- **Link:** https://www.tandfonline.com/doi/full/10.1080/00031305.2025.2561140
- Comprehensive review of LLM agents for data analysis, visualization, ML workflows

#### d. **CitySim: Modeling Urban Behaviors with LLM-Driven Agents** (2025)
- Urban simulation using recursive value-driven approach
- Scalable agent-based modeling for city dynamics


---

## PHASE 7: PLANNING & ORCHESTRATION
**Core Component:** Agent Planning Module - Goal Decomposition and Strategy Formation

How agents break down complex tasks, form plans, and orchestrate multi-step workflows, leveraging world models when available.
**Key Concepts:** Task decomposition, planning algorithms (with/without world models), agent workflows, domain-specific planning strategies, plan-then-act vs. continuous replanning


| Topic | Slide Deck | Previous Semester  |
|-------|------------|-------------------|
| Agent - In Healthcare | W9.1-HealthAI-agenticHealth | [25course](https://qiyanjun.github.io/2025sp-GenAI-overview/) |
| More on LLM Based Agents | W13.1-T3-smallLLM-agents | [25course](https://qiyanjun.github.io/2025sp-GenAI-overview/) |
| LLM Agents | W12-Team2-LLMAgents |  [24course](https://qiyanjun.github.io/2024sp-GenAI-Risk-Benefits/)  |




### 2025 HIGH-IMPACT PAPERS on this topic 
#### a. **Model-First Reasoning LLM Agents: Reducing Hallucinations through Explicit Problem Modeling** (December 2025)
- **Authors:** Annu Rana, Gaurav Kumar
- **Link:** https://arxiv.org/abs/2512.14474

**Two-Phase Paradigm:**
1. **Modeling Phase**: LLM constructs explicit model (entities, state variables, actions, constraints)
2. **Solution Phase**: Generate plan based on explicit model
- Reduces constraint violations across medical scheduling, route planning, resource allocation, logic puzzles
- Outperforms Chain-of-Thought and ReAct
- **Critical finding**: Many planning failures stem from representational deficiencies, not reasoning limitations

**Domains Tested:** Medical scheduling, route planning, resource allocation, logic puzzles, procedural synthesis


#### b. **EnCompass: Separating Search from Agent Workflows** (December 2025)
- **Links:**
  - arXiv: https://arxiv.org/abs/2512.03571
  - Press: https://techxplore.com/news/2025-12-ai-agents-results-large-language.html

**Key Innovation:** Separates search strategy from workflow code
- **Performance**: 15-40% accuracy boost on code repository translation
- **Search strategies**: Backtracking, parallel exploration, beam search (best: two-level beam search)

**Use Cases:** Code translation, digital grid transformation rules


---

## PHASE 8: MULTI-AGENT SYSTEMS 
**Core Component:** Multi-Agent Collaboration - Coordination, Communication, and Collective Intelligence

Understanding how multiple agents work together to solve complex problems.
**Key Concepts:** Agent communication protocols, collaborative problem-solving, role-based coordination, multi-agent architectures


| Topic | Slide Deck | Previous Semester  |
|-------|------------|-------------------|
| Agent - Multiagent Collaboration | W11.1.Team5-agent | [25course](https://qiyanjun.github.io/2025sp-GenAI-overview/) |
| MultiAgent LLMs | W13-MultiAgentLLMs | [24course](https://qiyanjun.github.io/2024sp-GenAI-Risk-Benefits/) |


### 2025 HIGH-IMPACT PAPERS on this topic 

#### a. **MAR: Multi-Agent Reflexion Improves Reasoning** (December 2025)
- **Link:** https://arxiv.org/abs/2512.20845
- **Key Idea:** Multi-persona debators prevent degeneration of thought
- **Results:** 47% EM on HotPot QA, 82.7% on HumanEval



#### b. **Towards a Science of Scaling Agent Systems** (December 2025)
- **Link:** https://arxiv.org/abs/2512.08296

**Quantitative Scaling Laws:**
- **180 configurations tested**: 5 architectures (single, independent, centralized, decentralized, hybrid) × 3 LLM families × 4 benchmarks
- **Key findings**:
  - **Capability saturation**: Coordination has diminishing returns above ~45% single-agent baseline
  - **Error amplification**: Independent agents amplify errors 17.2×, centralized reduces to 4.4×
  - **Task dependency**: Centralized excels on parallelizable tasks (+80.8%), decentralized on web navigation (+9.2%)
  - **Sequential tasks**: All multi-agent variants degrade performance by 39-70%
- **Predictive framework**: 87% accuracy on held-out configurations
- **Validated on GPT-5.2** (MAE=0.071)

**Impact:** First rigorous quantitative framework for agent coordination

#### c. **Multi-Agent Collaboration Mechanisms: A Survey of LLMs** (January 2025)
- **Link:** https://arxiv.org/abs/2501.06322

**Framework Dimensions:**
- **Actors**: Agents involved in collaboration
- **Types**: Cooperation, competition, coopetition
- **Structures**: Peer-to-peer, centralized, distributed
- **Strategies**: Role-based, model-based
- **Coordination protocols**: Communication patterns
- **Applications**: 5G/6G networks, Industry 5.0, question answering, social/cultural settings



---

## PHASE 9: RISK, SAFETY, ALIGNMENT & GUARDRAILS 
**Core Component:** Agent Safety Systems - Ensuring Reliable, Ethical, and Secure Operation

Addressing safety, alignment, and ethical considerations in agent deployment.

| Topic | Slide Deck | Previous Semester  |
|-------|------------|-------------------|
| Platform - Model Jailbreaking / Safeguarding | W7.1-team3-jailbreak | [25course](https://qiyanjun.github.io/2025sp-GenAI-overview/) |
| Platform - VLM Jailbreaking / Probing | W7.2-team4-MMJailbreak-garak | [25course](https://qiyanjun.github.io/2025sp-GenAI-overview/) |
| Agent Safety | W10.2-team4-agent-safety | [25course](https://qiyanjun.github.io/2025sp-GenAI-overview/) |
| LLM Evaluating Framework | W3-LLMEvaluation-Team5 | [24course](https://qiyanjun.github.io/2024sp-GenAI-Risk-Benefits/) |
| GenAI Guardrails | W3-Guardrail-Team3 | [24course](https://qiyanjun.github.io/2024sp-GenAI-Risk-Benefits/) |
| Survey: Human Alignment | W4-LLM-Human-Alignment | [24course](https://qiyanjun.github.io/2024sp-GenAI-Risk-Benefits/) |
| Survey: AI Risk Framework | W5-AI-RiskFramework | [24course](https://qiyanjun.github.io/2024sp-GenAI-Risk-Benefits/) |
| FM Copyright Infringement | W5-FM-copyright-infrigement | [24course](https://qiyanjun.github.io/2024sp-GenAI-Risk-Benefits/) |
| FM Privacy Leakage Issues | W6-FM-privacy-leakage | [24course](https://qiyanjun.github.io/2024sp-GenAI-Risk-Benefits/) |
| FM Fairness / Bias Issues | W6-LLM-Bias-Fairness-Team5 | [24course](https://qiyanjun.github.io/2024sp-GenAI-Risk-Benefits/) |
| FM Toxicity / Harmful Outputs | W7-LLM-harm | [24course](https://qiyanjun.github.io/2024sp-GenAI-Risk-Benefits/) |
| LLM Multimodal Harm Responses | W7-multimodal-LLMharm | [24course](https://qiyanjun.github.io/2024sp-GenAI-Risk-Benefits/) |
| More FM Risk / Extra - Agent Guardrailing | W8-Team3-P3-moreRisk.pdf | [25course](https://qiyanjun.github.io/2025sp-GenAI-overview/) |




---

## PHASE 10: MODEL TRAINING & OPTIMIZATION 
**Core Component:** Improving the Agent Brain - Training, Fine-tuning, and Optimization

Techniques for improving model capabilities and efficiency.

**Key Concepts:** Evaluation frameworks, guardrails, alignment (RLHF, PPO, DPO), risk assessment, jailbreaking defense, fairness, bias mitigation, toxicity prevention, agent safety protocols
**Key Concepts:** Data preparation, instruction tuning, LoRA/DoRA, parameter-efficient fine-tuning, scaling laws, efficiency optimization


| Topic | Slide Deck | Previous Semester  |
|-------|------------|-------------------|
| Platform - Model Customization (Instruction Tuning/LoRA) | W8.1-LoRA-Team5 | [25course](https://qiyanjun.github.io/2025sp-GenAI-overview/) |
| LLM Alignment - PPO | W11.2-team6-PPO | [25course](https://qiyanjun.github.io/2025sp-GenAI-overview/) |
| LLM Post-training | W14.3.DPO | [25course](https://qiyanjun.github.io/2025sp-GenAI-overview/) |
| Open Source LLM - Mistral Data Preparation | W4-OpenSourceLLM | [24course](https://qiyanjun.github.io/2024sp-GenAI-Risk-Benefits/) |
| Scaling Law and Efficiency | W11-ScalinglawEfficientLLM | [24course](https://qiyanjun.github.io/2024sp-GenAI-Risk-Benefits/) |
| LLM Fine Tuning | W14-LLM-FineTuning | [24course](https://qiyanjun.github.io/2024sp-GenAI-Risk-Benefits/) |
| Model Editing and Disgorgement | W10-T5-ModelEditing | [24course](https://qiyanjun.github.io/2024sp-GenAI-Risk-Benefits/) |


### 2025 HIGH-IMPACT PAPERS on this topic 
#### a. **Kimi k1.5: Scaling Reinforcement Learning with LLMs** (January 2025)
- **Link:** https://arxiv.org/abs/2501.12599

**Contribution:** Alternative approach to scaling reasoning via RL
- Complements DeepSeek-R1 with different architectural choices
- Emphasizes scaling strategies for RL training
- Addresses computational efficiency in large-scale RL


#### b. **The Landscape of Agentic Reinforcement Learning for LLMs** (September 2025)
  - Referenced in: https://github.com/zjunlp/LLMAgentPapers

**Comprehensive RL Survey:**
- **Taxonomy** of agentic RL approaches
- **Training methods**: GRPO, PPO variations, RLVR
- **Policy optimization**: Group-in-Group, Stepwise Progress Attribution (SPA-RL)
- **Challenges**: Reward hacking, sample efficiency, exploration-exploitation
- **Applications**: Reasoning, planning, multi-agent coordination

**Key Papers Covered:**
- GRPO (Group Relative Policy Optimization)
- History Resampling Policy Optimization (SRPO)
- PVPO (Pre-Estimated Value-Based Policy Optimization)

---

## PHASE 11: DEPLOYMENT & SERVING 
**Core Component:** Production Infrastructure - Deploying and Serving Agents at Scale

Understanding the infrastructure and systems for deploying agents in production.
**Key Concepts:** Model serving systems, vLLM, KV cache optimization, inference efficiency, chunked prefill, monitoring and interpretability

| Topic | Slide Deck | Previous Semester  |
|-------|------------|-------------------|
| Platform - Model Serving | W8.2-Model Serving-team6-t5 | [25course](https://qiyanjun.github.io/2025sp-GenAI-overview/) |
| More Model Serving - SGlang + Chunked Prefill | W12.2-Model-Serving | [25course](https://qiyanjun.github.io/2025sp-GenAI-overview/) |
| Model Serving - Efficiency Inference | W14.2.ModelServing | [25course](https://qiyanjun.github.io/2025sp-GenAI-overview/) |
| Model Interpretability for FM | W13.2-GenAI-Interpretability | [25course](https://qiyanjun.github.io/2025sp-GenAI-overview/) |
| LLM Interpretability, Trust and Knowledge Conflicts | W10-T6-LLMInterpretibility | [24course](https://qiyanjun.github.io/2024sp-GenAI-Risk-Benefits/) |


### 2025 HIGH-IMPACT PAPERS on a related topic: benchmaarking after deployed 
#### a. **Evaluation and Benchmarking of LLM Agents: A Survey** (July 2025)
- **Link:** https://arxiv.org/html/2507.21504v1
- **Comprehensive taxonomy**: Evaluation objectives (behavior, capabilities, reliability, safety) × evaluation process (interaction modes, datasets, metrics, tooling, environments)
- **Enterprise focus**: Role-based access control, reliability guarantees, long-term interaction, compliance
- **Novel metrics**: Consistency (pass@k vs all-k), robustness under input variations


#### b. **OSWorld: Benchmarking Multimodal Agents for Open-Ended Tasks in Real Computer Environments** (April 2024, Major Updates 2025)
- **Links:**
  - arXiv: https://arxiv.org/abs/2404.07972
  - Project: https://os-world.github.io/
  - HuggingFace: https://huggingface.co/spaces/xlanglab/OSWorld

**why to read:**
- **First real computer environment** benchmark (Ubuntu, Windows, macOS)
- **369 tasks** across real web/desktop apps, file I/O, cross-app workflows
- **Execution-based evaluation** with custom scripts per task
- **State-of-the-art results (2025)**: OpenAI Operator 38%, best open-source ~24%
- Reveals massive gap between current capabilities and human performance
- **Industry Impact:** Became the standard for evaluating computer-use agents (Claude Computer Use, OpenAI Operator, etc.)


#### c. **WebArena: A Realistic Web Environment for Building Autonomous Agents** (July 2023, Extensive 2025 Extensions)
- **Links:**
  - arXiv: https://arxiv.org/abs/2307.13854
  - Project: https://webarena.dev/
  - Extensions: WebChoreArena, ST-WebAgentBench
- **Record performance**: IBM CUGA achieved 61.7% (vs 14% in 2023)
- **812 templated tasks** across e-commerce, forums, code repositories, CMS
- **Extensions**:
  - WebChoreArena: 532 tedium-focused tasks (top models: 37.8%)
  - ST-WebAgentBench: Safety/trust templates, policy compliance metrics
- **Key insights**: Success driven by Planner-Executor-Memory architecture + specialized training data


#### d. **AgentBench: Evaluating LLMs as Agents** (August 2023, Updated 2025)
- **Venue:** ICLR 2024
- **Links:**
  - arXiv: https://arxiv.org/abs/2308.03688
  - GitHub: https://github.com/THUDM/AgentBench

**Comprehensive Coverage:**
- **8 environments**: Code, game playing, web shopping, digital card games, lateral thinking, household tasks, web browsing, OS interaction
- **Multi-dimensional evaluation**: Breadth across domains reveals agent weak spots
- **Function-calling version** (2025): Integrated with AgentRL framework
- **VisualAgentBench**: Extension for multimodal agents (5 environments, 17 LMMs tested)


---

## CROSS-CUTTING THEMES IN 2025

### **1. Reasoning Revolution**
- Pure RL without supervised demonstrations (DeepSeek-R1, Kimi k1.5)
- Emergent reasoning patterns: self-reflection, verification, strategy adaptation
- Test-time compute scaling
- Published in Nature - mainstream scientific recognition

### **2. Quantitative Scaling Laws**
- First rigorous study of multi-agent coordination (Towards a Science of Scaling)
- Capability saturation thresholds identified
- Task-dependent optimal architectures

### **3. Real-World Evaluation**
- OSWorld: First real computer environment (369 tasks)
- WebArena: 61.7% performance reached (from 14% in 2023)
- Enterprise-specific metrics: reliability, consistency, compliance

### **4. Memory Architecture Innovation**
- Hierarchical memory systems
- Self-organizing memory (EverMemOS)
- Multi-agent memory coordination (G-Memory, MIRIX)
- Distinction from RAG and context engineering

### **5. Domain Specialization**
- Legal: Trustworthiness, explainability, cross-jurisdictional
- Materials science: Self-correcting databases
- Video understanding: Multi-agent coordination for long-form content
- Data science: End-to-end automation

### **6. Safety & Reliability**
- Game theory for understanding strategic behavior
- Cross-linguistic behavioral divergence
- Policy compliance metrics (ST-WebAgentBench)
- Failure mode analysis (WABER benchmark)



---

## RESOURCES FOR FURTHER STUDY

### **Curated Paper Repositories:**
1. **Awesome-Agent-Papers**: https://github.com/luo-junyu/Awesome-Agent-Papers
2. **LLM-Agent-Papers**: https://github.com/AGI-Edgerunners/LLM-Agents-Papers
3. **zjunlp Collection**: https://github.com/zjunlp/LLMAgentPapers
4. **Agent-Memory-Paper-List**: https://github.com/Shichun-Liu/Agent-Memory-Paper-List

### **Sebastian Raschka's 2025 Lists:**
- Part 1 (Jan-June): https://magazine.sebastianraschka.com/p/llm-research-papers-2025-list-one
- Part 2 (July-Dec): https://magazine.sebastianraschka.com/p/llm-research-papers-2025-part2

### **Benchmarking Resources:**
- OSWorld Leaderboard: https://os-world.github.io/ (Industry standard for computer-use evaluation)
- WebArena Project: https://webarena.dev/ (Foundational for web agent development)
- AgentBench GitHub: https://github.com/THUDM/AgentBench

#### **Industry Adoption:**
- **OpenAI Operator**: Uses OSWorld (58% WebArena, 38% OSWorld)
- **Claude Computer Use**: Evaluated on OSWorld benchmarks
- **Gemini 2.5 Pro**: 54.8% WebArena, 37.8% WebChoreArena
- **IBM CUGA**: 61.7% WebArena (current record)



### Academic Integrity
The School of Engineering and Applied Science relies upon and cherishes its community of trust. We firmly endorse, uphold, and embrace the University’s Honor principle that students will not lie, cheat, or steal, nor shall they tolerate those who do. We recognize that even one honor infraction can destroy an exemplary reputation that has taken years to build. Acting in a manner consistent with the principles of honor will benefit every member of the community both while enrolled in the Engineering School and in the future. 


Students are expected to be familiar with the university honor code, including the section on academic fraud. Each assignment will describe allowed collaborations, and deviations from these will be considered Honor violations. If you are in doubt regarding the requirements, please consult with me before you complete any requirement of this course. Unless otherwise noted, exams and individual assignments will be considered pledged that you have neither given nor received help. (Among other things, this means that you are not allowed to describe problems on an exam to a student who has not taken it yet. You are not allowed to show exam papers to another student or view another student’s exam papers while working on an exam.) Send, receiving or otherwise copying electronic files that are part of course assignments are not allowed collaborations (except for those explicitly allowed in assignment instructions). 

Assignments or exams where honor infractions or prohibited collaborations occur will receive a zero grade for that entire assignment or exam, as well as a full letter-grade penalty on the course grade. Such infractions will also be submitted to the Honor Committee if that is appropriate. Students who have had prohibited collaborations may not be allowed to work with partners on remaining homeworks. 


### SDAC and Other Special Circumstances
The University of Virginia strives to provide accessibility to all students. If you require an accommodation to fully access this course, please contact the Student Disability Access Center (SDAC) at 434-243-5180 or sdac@virginia.edu. If you are unsure if you require an accommodation, or to learn more about their services, you may contact the SDAC at the number above or by visiting their website at [URL](http://studenthealth.virginia.edu/student-disability-access-center/faculty-staff). 

If you have been identified as an SDAC student, please let the Center know you are taking this class. If you suspect you should be an SDAC student, please schedule an appointment with them for an evaluation. Students who need academic accommodations should see me and contact the SDAC. All academic accommodations must be arranged through the SDAC. 

If you have other special circumstances (athletics, other university-related activities, etc.) please contact instructor and/or TA as soon as you know these may affect you in class. 


### Religious Accommodations
It is the University's long-standing policy and practice to reasonably accommodate students so that they do not experience an adverse academic consequence when sincerely held religious beliefs or observances conflict with academic requirements. Students who wish to request academic accommodation for a religious observance should submit their request in writing directly to me by email as far in advance as possible. Students and instructors who have questions or concerns about academic accommodations for religious observance or religious beliefs may contact the University's Office for Equal Opportunity and Civil Rights (EOCR) at UVAEOCR@virginia.edu or 434-924-3200. 

Accommodations do not relieve you of the responsibility for completion of any part of the coursework missed as the result of a religious observance. 


### Statement on Violence
The University of Virginia is dedicated to providing a safe and equitable learning environment for all students. To that end, it is vital that you know two values that I and the University hold as critically important:

Power-based personal violence will not be tolerated.
Everyone has a responsibility to do their part to maintain a safe community on Grounds.
If you or someone you know has been affected by power-based personal violence, more information can be found on the UVA Sexual Violence website that describes reporting options and resources available - www.virginia.edu/sexualviolence. 

As your professor and as a person, know that I care about you and your well-being and stand ready to provide support and resources as I can. As a faculty member, I am a responsible employee, which means that I am required by University policy and federal law to report what you tell me to the University's Title IX Coordinator. The Title IX Coordinator's job is to ensure that the reporting student receives the resources and support that they need, while also reviewing the information presented to determine whether further action is necessary to ensure survivor safety and the safety of the University community. If you would rather keep this information confidential, there are Confidential Employees you can talk to on Grounds (See http://www.virginia.edu/justreportit/confidential_resources.pdf). The worst possible situation would be for you or your friend to remain silent when there are so many here willing and able to help. 

### This syllabus
This syllabus is to be considered a reference document that can and will be adjusted through the course of the semester to address changing needs. This syllabus can be changed at any time without notification. It is up to the student to monitor this page for any changes. Final authority on any decision in this course rests with the professor, not with this document.
