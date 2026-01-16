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


#### Please check out more details of each phase in [our main schedule page](https://qiyanjun.github.io/2026sp-GenAI-Agents-Overview-Course/)



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
│   ↓                                                          │
│  APPLICATIONS                                               │
│                                                              │
└─────────────────────────────────────────────────────────────┘
```


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

