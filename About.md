---
layout: page
title: Syllabus
desc: "Information for 2026 Spring UVa CS -GenAI-Overview"
---


### [The official Academic Calendar at UVA Registrar](http://www.virginia.edu/registrar/calendar.html)


### Prerequisite:

+ Required courses as prerequisites: Machine Learning; Deep learning; Optional on RL. The seminar is for research-focused graduate students with interests in generative deep learning models, foundations, applications, and related LLM Agents topics. 


### General Description and Disclaimer: 

+ The course will take the form of a combination of seminar, lectures by the instructor and project deliverables from students. 

+ TuTh 3:30pm - 4:45pm  
+ Rice Hall

+ It is quite hard to make important topics of Generative AI fit on a one-semester schedule.  We aim to make the course reasonably digestible in an seminar plus projects using team-learning manner. Our goals here are to highlight the most timing research topics relating to GenAI. We think this teaching style provides students with research centered learning on both knowledge and workflows, helping them build a quick understanding of State-of-the-Art in GenAI.

+ 2025 spring's same course website was [here](https://qiyanjun.github.io/2025sp-GenAI-overview/)
  - [25 Spring course's students project github HERE](https://github.com/Qdata4Capstone/uva-25-spring-genai-students-projects/tree/main/students-projects-code)

+ 2024 spring's same course website was [here](https://qiyanjun.github.io/2024sp-GenAI-Risk-Benefits/)

+ ATT: This year we expand and put much more emphasis on the course projects than the previous two. 


### Course Expectations

Student teams are expected to:

+ Present One SOTA Topics. For each topic, a slide deck and an in-class presentation is expected from a team: 
  - Example of Slide deck: [here](https://qiyanjun.github.io/2024sp-GenAI-Risk-Benefits//Lectures/W3-LLMEvaluation-Team5.pdf)
  - We recommend students to use 365 powerpoint [here](https://virginia.service-now.com/its?id=itsweb_kb_article&sys_id=713ff34fdb3ac744f032f1f51d961937#login) to support their co-editing of presentation slide decks. 

+ Finish two course projects  
  - Course Project A: Build agents to benefit domains like healthcare, finance or .....
  - Course Project B: A deep dive project on a component of LLM agents or property of LLM agents ... 
  - Please check out more details on project viathe Project Guide Page via sidebar! 

+ Participate actively in class meets. This means being prepared to contribute by presenting assigned papers, and working activerly on your course projects.


### Course Websites

+ Course schedule and materials  @ [https://qiyanjun.github.io/2025sp-GenAI-overview/](https://qiyanjun.github.io/2025sp-GenAI-overview/)
+  Assignment submissions via [Cavas site:](https://canvas.its.virginia.edu) 
+ Course annoucement via Canvas Annoucement
+ Course Discussion via Course Slack Space (please ask TA to get you in!) 


+ ##### Instructors: 
  - Prof. [Yanjun Qi](https://qiyanjun.github.io/Homepage/) / [yanjun@virginia.edu](mailto:?);
  - TA: [Alex Su](mailto:acf7ea@virginia.edu)  
  - Instructor office hour: TBD
  - TA office hours: TBD


### Course Grading Policy

+ No exams in this course.
+ Sit-in: No. This course is for registered students only.

+ Final grades will be based on.
  - 10% for the course attendance (starting from W4)
  - 10% for the your weekly reading log (starting from W4)
  - 20% for the quality of your seminar presentations; 
  - 30% for the quality of your first course projects; 
  - 30% for the quality of your second course projects; 




## Course Framework Overview

We use a course content organization that emphasizes the modular, compositional nature of modern agent architectures.
It follows the **Perception → World Modeling → Planning → Action → Learning** cycle that defines modern LLM agent architectures:


**Course Organization:** 

This syllabus is organized around 

## Learning Objectives by Phase (Roughly per week one phase to cover this Semester)


- **Phase 0 (Foundations & Overview):** Grasp the fundamental concepts and architecture of LLM agents
- **Phase 1 (Applications):** Translate agent capabilities into real-world domains and products; study case studies, human-in-the-loop workflows, and impact measurement
- **Phase 2 (Brain & Reasoning):** Understand the core LLM capabilities that enable agentic behavior
- **Phase 3 (Perception):** Learn how agents process multimodal and domain-specific inputs
- **Phase 4 (Memory):** Master memory architectures and knowledge management systems
- **Phase 5 (Action & Tools):** Develop skills in tool integration and agent-computer interfaces
- **Phase 6 (World Models):** Explore how agents build internal representations of their environment
- **Phase 7 (Planning):** Study planning algorithms and task orchestration strategies
- **Phase 8 (Multi-Agent):** Understand collaborative agent systems and communication protocols
- **Phase 9 (Safety):** Address ethical, safety, and alignment challenges in agent deployment
- **Phase 10 (Training):** Learn optimization and customization techniques
- **Phase 11 (Deployment):** Understand production infrastructure and serving systems





---


## PHASE 5: 



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

+ a. AgentGym-RL: Training Agents for Long-Horizon Decision Making (September 2025)
  - https://github.com/WooooDyy/LLM-Agent-Paper-List
  - RL version of AgentGym for learning from interactive environments
  - Interactive frontend for trajectory visualization, multi-turn RL

+ b. DreamerV3: Mastering Diverse Control Tasks through World Models
  - Nature (April 2025) / [arXiv](https://arxiv.org/abs/2301.04104) | [GitHub](https://github.com/danijar/dreamerv3)
  - A general reinforcement-learning algorithm that outperforms specialized expert algorithms across diverse tasks by learning a model of the environment and improving its behaviour by imagining future scenarios.
  - Dreamer succeeds across domains ranging from robot locomotion and manipulation tasks over Atari games, procedurally generated ProcGen levels, and DMLab tasks to the complex and infinite world of Minecraft.
  - First algorithm to collect diamonds in Minecraft from scratch without human data or curricula
  - Uses Recurrent State-Space Model (RSSM) for latent imagination and planning

+ c. V-JEPA 2: Self-Supervised Video Models Enable Understanding, Prediction and Planning
  - [arXiv](https://arxiv.org/abs/2506.09985) | [GitHub](https://github.com/facebookresearch/vjepa2) | [Meta AI](https://ai.meta.com/vjepa/)
  - The first world model trained on video that achieves state-of-the-art visual understanding and prediction, enabling zero-shot robot control in new environments.
  - Post-training a latent action-conditioned world model, V-JEPA 2-AC, using less than 62 hours of unlabeled robot videos from the Droid dataset enables zero-shot deployment on Franka arms without collecting any data from those environments.
  - V-JEPA 2-AC achieves reach = 100%, manipulation = 60–80% compared to Cosmos's reach = 80%, manipulation = 0–20%, while being 15× faster (16 seconds/action vs 4 minutes).
  - Predicts in representation space rather than pixel space—key innovation for efficient planning

+ c. NVIDIA Cosmos: World Foundation Model Platform for Physical AI
  - [NVIDIA Cosmos](https://www.nvidia.com/en-us/ai/cosmos/) | [Technical Report](https://arxiv.org/abs/2501.03575)
  - Open world foundation models (WFMs), guardrails, and data processing libraries to accelerate the development of physical AI for autonomous vehicles (AVs), robots, and video analytics AI agents.
  - WFMs are purpose-built for physical AI research and development, and can generate physics-based videos from a combination of inputs, like text, image and video, as well as robot sensor or motion data.
  - Cosmos Reason—a new open, customizable, 7-billion-parameter reasoning VLM for physical AI and robotics—lets robots and vision AI agents reason like humans using prior knowledge, physics understanding and common sense.
  - Early adopters include 1X, Agility Robotics, Figure AI, Skild AI, Boston Dynamics

+ d. RT-2: Vision-Language-Action Models Transfer Web Knowledge to Robotic Control
  - [DeepMind Blog](https://deepmind.google/blog/rt-2-new-model-translates-vision-and-language-into-action/)
  - RT-2 shows that vision-language models (VLMs) can be transformed into powerful vision-language-action (VLA) models, which can directly control a robot by combining VLM pre-training with robotic data.
  - Thanks to its VLM backbone, RT-2 can plan from both image and text commands, enabling visually grounded planning, whereas current plan-and-act approaches like SayCan cannot see the real world and rely entirely on language.
  - Uses PaLM-E and PaLI-X backbones; demonstrates chain-of-thought reasoning for multi-stage semantic reasoning


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

+ a. EnCompass: Separating Search from Agent Workflows (December 2025)
  - arXiv: https://arxiv.org/abs/2512.03571
  - Press: https://techxplore.com/news/2025-12-ai-agents-results-large-language.html
  Key Innovation: Separates search strategy from workflow code
  - Performance: 15-40% accuracy boost on code repository translation
  - Search strategies: Backtracking, parallel exploration, beam search (best: two-level beam search)

  Use Cases: Code translation, digital grid transformation rules

+ b. Model-First Reasoning LLM Agents: Reducing Hallucinations through Explicit Problem Modeling (December 2025)
  - Link: https://arxiv.org/abs/2512.14474

  Two-Phase Paradigm:
  1. Modeling Phase: LLM constructs explicit model (entities, state variables, actions, constraints)
  2. Solution Phase: Generate plan based on explicit model
  - Reduces constraint violations across medical scheduling, route planning, resource allocation, logic puzzles
  - Outperforms Chain-of-Thought and ReAct
  - Critical finding: Many planning failures stem from representational deficiencies, not reasoning limitations

  Domains Tested: Medical scheduling, route planning, resource allocation, logic puzzles, procedural synthesis




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

+ a. MAR: Multi-Agent Reflexion Improves Reasoning (December 2025)
  - Link: https://arxiv.org/abs/2512.20845
  - Key Idea: Multi-persona debators prevent degeneration of thought
  - Results: 47% EM on HotPot QA, 82.7% on HumanEval


+ b. Towards a Science of Scaling Agent Systems (December 2025)
  - Link: https://arxiv.org/abs/2512.08296

  Quantitative Scaling Laws:
  - 180 configurations tested: 5 architectures (single, independent, centralized, decentralized, hybrid) × 3 LLM families × 4 benchmarks
  - Key findings:
    - Capability saturation: Coordination has diminishing returns above ~45% single-agent baseline
    - Error amplification: Independent agents amplify errors 17.2×, centralized reduces to 4.4×
    - Task dependency: Centralized excels on parallelizable tasks (+80.8%), decentralized on web navigation (+9.2%)
    - Sequential tasks: All multi-agent variants degrade performance by 39-70%
  - Predictive framework: 87% accuracy on held-out configurations
  - Validated on GPT-5.2 (MAE=0.071)


+ c. Multi-Agent Collaboration Mechanisms: A Survey of LLMs (January 2025)
  - Link: https://arxiv.org/abs/2501.06322

  Framework Dimensions:
  - Actors: Agents involved in collaboration
  - Types: Cooperation, competition, coopetition
  - Structures: Peer-to-peer, centralized, distributed
  - Strategies: Role-based, model-based
  - Coordination protocols: Communication patterns
  - Applications: 5G/6G networks, Industry 5.0, question answering, social/cultural settings


---

## PHASE 9: 

- OSWorld Leaderboard: https://os-world.github.io/ (Industry standard for computer-use evaluation)
- WebArena Project: https://webarena.dev/ (Foundational for web agent development)
- AgentBench GitHub: https://github.com/THUDM/AgentBench

+ a. Evaluation and Benchmarking of LLM Agents: A Survey (July 2025)
  - Link: https://arxiv.org/html/2507.21504v1
  - Comprehensive taxonomy: Evaluation objectives (behavior, capabilities, reliability, safety) × evaluation process (interaction modes, datasets, metrics, tooling, environments)
  - Enterprise focus: Role-based access control, reliability guarantees, long-term interaction, compliance
  - Novel metrics: Consistency (pass@k vs all-k), robustness under input variations


+ b. OSWorld: Benchmarking Multimodal Agents for Open-Ended Tasks in Real Computer Environments (April 2024, Major Updates 2025)
  - arXiv: https://arxiv.org/abs/2404.07972
  - Project: https://os-world.github.io/
  - HuggingFace: https://huggingface.co/spaces/xlanglab/OSWorld
  - First real computer environment benchmark (Ubuntu, Windows, macOS)
  - 369 tasks across real web/desktop apps, file I/O, cross-app workflows
  - Execution-based evaluation with custom scripts per task
  - State-of-the-art results (2025): OpenAI Operator 38%, best open-source ~24%
  - Reveals massive gap between current capabilities and human performance
  - Industry Impact: Became the standard for evaluating computer-use agents (Claude Computer Use, OpenAI Operator, etc.)


+ c. WebArena: A Realistic Web Environment for Building Autonomous Agents (July 2023, Extensive 2025 Extensions)
  - arXiv: https://arxiv.org/abs/2307.13854
  - Project: https://webarena.dev/
  - Extensions: WebChoreArena, ST-WebAgentBench
  - Record performance: IBM CUGA achieved 61.7% (vs 14% in 2023)
  - 812 templated tasks across e-commerce, forums, code repositories, CMS
  - Extensions:
    - WebChoreArena: 532 tedium-focused tasks (top models: 37.8%)
    - ST-WebAgentBench: Safety/trust templates, policy compliance metrics
  - Key insights: Success driven by Planner-Executor-Memory architecture + specialized training data


+ d. AgentBench: Evaluating LLMs as Agents (August 2023, Updated 2025)
  - Venue: ICLR 2024
  - arXiv: https://arxiv.org/abs/2308.03688
  - GitHub: https://github.com/THUDM/AgentBench

  Comprehensive Coverage:
  - 8 environments: Code, game playing, web shopping, digital card games, lateral thinking, household tasks, web browsing, OS interaction
  - Multi-dimensional evaluation: Breadth across domains reveals agent weak spots
  - Function-calling version (2025): Integrated with AgentRL framework
  - VisualAgentBench: Extension for multimodal agents (5 environments, 17 LMMs tested)



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


+ b. The Landscape of Agentic Reinforcement Learning for LLMs (September 2025)
  - Referenced in: https://github.com/zjunlp/LLMAgentPapers
  - Taxonomy of agentic RL approaches
  - Training methods: GRPO, PPO variations, RLVR
  - Policy optimization: Group-in-Group, Stepwise Progress Attribution (SPA-RL)
  - Challenges: Reward hacking, sample efficiency, exploration-exploitation
  - Applications: Reasoning, planning, multi-agent coordination
  - Key Papers Covered:
    - GRPO (Group Relative Policy Optimization)
    - History Resampling Policy Optimization (SRPO)
    - PVPO (Pre-Estimated Value-Based Policy Optimization)

 + Two papers on RL for discreate diffusion models: 
  - A Reparameterized Discrete Diffusion Model for Text Generation / - In recent years, masked diffusion models (MDMs) have emerged as a promising alternative approach for generative modeling over discrete domains. Compared to autoregressive models (ARMs), MDMs trade off complexity at training time with flexibility at inference time. At training time, they must learn to solve an exponentially large number of infilling problems, but at inference time, they can decode tokens in essentially arbitrary order. In this work, we closely examine these two competing effects. On the training front, we theoretically and empirically demonstrate that MDMs indeed train on computationally intractable subproblems compared to their autoregressive counterparts. On the inference front, we show that a suitable strategy for adaptively choosing the token decoding order significantly enhances the capabilities of MDMs, allowing them to sidestep hard subproblems. On logic puzzles like Sudoku, we show that adaptive inference can boost solving accuracy in pretrained MDMs from <7% to ≈90%, even outperforming ARMs with 7× as many parameters and that were explicitly trained via teacher forcing to learn the right order of decoding.
  - Train for the Worst, Plan for the Best: Understanding Token Ordering in Masked Diffusions /  - This work studies discrete diffusion probabilistic models with applications to natural language generation. We derive an alternative yet equivalent formulation of the sampling from discrete diffusion processes and leverage this insight to develop a family of reparameterized discrete diffusion models. The derived generic framework is highly flexible, offers a fresh perspective of the generation process in discrete diffusion models, and features more effective training and decoding techniques. We conduct extensive experiments to evaluate the text generation capability of our model, demonstrating significant improvements over existing diffusion models.
Comments:	COLM 2024; Code available at this https URL

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


#### Academic Resource: 
- 1. UC Berkeley CS294/194-196 Large Language Model Agents- Fall24： [CS294/194-196 Large Language Model Agents -24](https://rdi.berkeley.edu/llm-agents/f24)
- 2. UC Berkeley CS294/194-280 Advanced Large Language Model Agents- Spring 25: [CS294/194-196 Large Language Model Agents -25](https://rdi.berkeley.edu/adv-llm-agents/sp25)
- 3. Many recent LLM agents workshop, e.g., ICLR LLM agent summary figure like follows: 




---

## CROSS-CUTTING THEMES of LLM Agents IN 2025

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

### **7. Application Domains & Real-World Deployment** e.g., 
- SWE-bench family: Verified (79.2%), Pro (45.8%), Multilingual, Multimodal
- Med-PaLM 2: 85% on medical exams (human expert level)
- Data science Full lifecycle automation: EDA → feature engineering → modeling → deployment



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
