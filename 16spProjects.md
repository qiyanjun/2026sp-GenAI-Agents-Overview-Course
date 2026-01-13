---
layout: page
title: ProjectGuide
desc: "Course Project Information for 2026 Spring UVa CS -GenAI-Overview"
---

### Each student team is expected to finish two different course projects. 
+ Each team need to deliver two different course projects
+ Each team's two projects need to cover two different components of LLM-agents 

- **1 (Foundations & LLMs):** Grasp the fundamental concepts and architecture of LLM agents
- **2 (Brain & Reasoning):** Understand the core LLM capabilities that enable agentic behavior
- **3 (Perception):** Learn how agents process multimodal and domain-specific inputs
- **4 (Memory):** Master memory architectures and knowledge management systems
- **5 (Action & Tools):** Develop skills in tool integration and agent-computer interfaces
- **6 (World Models):** Explore how agents build internal representations of their environment
- **7 (Planning):** Study planning algorithms and task orchestration strategies
- **8 (Multi-Agent):** Understand collaborative agent systems and communication protocols
- **9 (Safety):** Address ethical, safety, and alignment challenges in agent deployment
- **10 (Training):** Learn optimization and customization techniques
- **11 (Deployment):** Understand production infrastructure and serving systems
- **12 (Applications):** Translate agent capabilities into real-world domains and products;



### Details on Each Course Project and required artifacts: 

+ Each team includes up to three students 
+ Each team is required to submit four artifacts: one report, one codebase,  one slide deck presentation and one video code demo is required on their project
+ Each team needs to submit all first three artifact files to their own assignment submission entries in Canvas; and host the fourth on youtube. 

+ The final project should be technical, employing methods including, but not limited to, those covered in class (e.g., identify a real-world problem and apply relevant algorithms learned). Please keep your code and visualized results in Jupyter notebooks or well-organized code structure. Teams with multiple students may divide experiments across several notebooks. Each team is also required to present their project detailing the project's background (motivation), methodology, and results.

+ On what to create / submit for each one of your project: 
  - 1. A mini demo "Shark Tank" presentation to the instructors on your project idea is expected. The mini presentation is expected to explain  (WHY/ WHAT/ HOW on your project!) -- intended to be a more conceptual, idea-based pitch; please use [a given template]({{ site.baseurl }}/Lectures/ProjPresentationTemplate-1.pptx) to help you pitch the idea! 
  - 2. A slide deck (Due in Canvas) summarizing your project  and describing the results you reproduce; Filling in the template slide pages will be enough enough (more is better!). Here is the [given template]({{ site.baseurl }}/Lectures/ProjPresentationTemplate-1.pptx)
  - 3. A python Jupyter notebook ((or codebase form that you prefer! due to project Github codebase Pull Request, together with the slide deck to Canvas) to present the code, data visualization, and obtain the results and analysis through step by step code cell run. 
  - 4. A detailed project report including intro, background, related work, experimental design, results and comparison to baselines. 
  - 5. On the project demo day, you are expected to present a formal / complete demo using your slide deck and your code demo during the project presentation session. 
  - You are expected to go through and show the codebase  and your final project presentation to the instructors via a final project presentation session (25mins). 
  
+ What to submit as the final artifacts of your project: 
    0. your project slide deck as your final report into Canvas (the slide deck is required to have your video links and your codebase to the course project Github-PR information)
    1. your project iPython Notebook (or codebase form that you prefer!) and you cell run it in the demo video (Here is the course project Github [https://github.com/Qdata4Capstone/uva-machine-learning-25f-projects](https://github.com/Qdata4Capstone/uva-machine-learning-25f-projects), you are expected to PullRequest to add yours into this Github)
    2. To minimize the overhead time cost (switching, wrong setup, ….), we will expect you to record a demo video to present your project / We recommend you to submit your video demo to youtube and share the link in the Canvas project submission. (Please practice the whole process for a few times before you make video demos.) 

+ On how we grade the projects: 
  - Here is the grading rubrics we will use to grade your final report 
  - Good slide deck (aka also via final presentation ) (60%)
    1. Clear definition of problem and importance (10%)
    2. Clear explanation of approach and code runs (15%)
    3. clear summary of results (and/or difficulties) (15%)
    4. Well-organized, polished as a whole (10%) 
    5. Great delivery of content at the final demo session and the "shark tank" sessions (10%)
  - Good coding artifacts (aka also presented via final presentation) (40%)
  - Good video demo (Extra credits: 20%)

+ On the project report: 
  - Here is the grading rubrics we will use to grade your final report 
  - Clear definition of problem and importance (25%)
  - Clear explanation of approach (25%)
  - clear summary of results (and/or difficulties) (25%)
  - Well-organized, polished as a whole (25%) 


+ Please following the following instruction for organizing your PR to the project codebase: [tocome](tocome)

  - Plese Follow the following folder structure to organize your team project artifacts:
  - Place all code scripts in the `src/` folder
  - Place all documentation in the `doc/` folder
  - A README.md will be helpful if you have one. 

```
team-x/
├── src/
└── doc/
```

+ How to PR to the project codebase: 
#### Step 1: Set up your local branch

* Go to the course repository and click Fork: https://github.com/Qdata4Capstone/uva-machine-learning-25f-projects
* Go to your new forked repository and clone it to your local environment:
   * `git clone https://github.com/<your-username>/uva-machine-learning-25f-projects.git`
* Navigate into the cloned folder and add the original repository as an upstream remote:
   * `git remote add upstream https://github.com/Qdata4Capstone/uva-machine-learning-25f-projects.git`

#### Step 2: Prepare your code

* For each team, please create a folder named `team-XX` corresponding to your team ID (e.g., team-1, team-11, team-111).
* Inside this folder, include the following:
   * `src/`: A subfolder containing all source code.
   * `data/`: A subfolder with the data required to reproduce results.
      * Note: If the data cannot be uploaded, include a markdown file describing how to collect it.
   * `requirements.txt`: A file listing required packages. (Format reference)
   * `README.md`: A markdown file describing the folder content. You can view an example here. Your README should include:
      * Project Title
      * Team ID and Members
      * Overview: A brief introduction to the project.
      * Usage: How to run the code to get core results.
      * (Optional) Setup: Instructions for environment setup (if non-trivial).
      * (Optional) Video: A link to your demo video with a brief description.
* You are also welcome to include additional files or documentation in the folder or README.md if they help people better understand your project and code.

#### Step 3: Upload your code

* Commit your changes (no requirements on the commit message)
   * `git add .`
   * `git commit -m "upload project code by Team-XX"`
* Push the changes to your fork
   * `git push origin main`
* On GitHub, navigate to your fork and open a pull request via: Pull requests → New pull request


<hr> 

- Plese select your session in the signup sheet! 


## Potential Generative AI (GenAI) Project Ideas

### 0. Potential project types: for example, 
- Build a novel dataset to evaluate a certain capability of LLMs / VLMs / agents
  + e.g., personality of LLMs 
  + e.g., characters of LLMs 
  + e.g., safety of LLMs
  + e.g., code security 
  + e.g., for a specific domain, like Health commonsense? 
  + e.g., for a specific domain, like robotic spatial awareness?
  + e.g., CS theory exams?
  + e.g., following certain sofeware specifications?  
- Build a GenAI application, like Prompt to Blogpost Creation  
- Build a GenAI application, GenAI-Powered audio editing
- Build a GenAI guardrail, like GenAI generative content detetion 
- Build a GenAI guardrail, like misinforamtion / hallucination detection 
- Reproduce a GenAI paper 


### 1 GenAI for Creative Media (Text, Image, Music, Video)

- **Problem:** Generate creative or branded content automatically.
- **Applications:**
  - **Text:** Story or blog generation with **GPT-4o or Claude 3.5** fine-tuned via OpenAI's fine-tuning API.
  - **Image:** **Stable Diffusion XL**, **DALL·E 3**, or **Ideogram** for text-to-image.
  - **Music:** Use **MusicLM**, **Suno**, or **Mubert API** for audio generation.
  - **Video:** Explore **OpenAI Sora (text-to-video)** or **Runway Gen-3 Alpha** for cinematic short clips.
- **Data:** Creative commons datasets (e.g., COCO Captions, LAION-Aesthetics, MusicCaps).

### 2 GenAI for Data Augmentation and Simulation

- **Problem:** Improve ML robustness with synthetic data in low-data regimes.
- **Application:** Use **Diffusion models** or **tabular GANs (CTGAN, TVAE)** to generate synthetic examples.
- **Data:** Any small real dataset (medical, fraud, sensor).
- **Extension:** Evaluate using **TSTR/TSTS metrics** and **privacy leakage testing**.

### 3 GenAI for Explainable AI (LLMs as Explainers)

- **Problem:** Explain model predictions and surface reasoning traces.
- **Application:** Build an **LLM-based explainer agent** that interprets model outputs using Chain-of-Thought prompting.
- **Tools:** OpenAI function calling, LangChain, or LlamaIndex integration.

## 4. AI Agent and Systems Project Ideas

### 4.1 AI Agents for Information Retrieval or Research Assistants

- **Problem:** Automate retrieval, summarization, and reasoning over long documents.
- **Application:** Build a **Retrieval-Augmented Generation (RAG)** agent using **LangChain**, **LlamaIndex**, and **Qdrant/FAISS** vector stores.
- **Extension:** Add **multi-agent debate** (via **AutoGen**, **CrewAI**, or **OpenDevin**) to improve factual accuracy.

### 4.2 Simulation Agents for Cybersecurity or Finance

- **Problem:** Model adversarial or autonomous agent behavior (e.g., attacker vs defender).
- **Application:** Create **red-team vs blue-team agents** to simulate phishing or intrusion responses using **AutoGen** or **SuperAGI**.
- **Extension:** Integrate **policy engine (Cedar / Guardrails)** for enforcing compliance and ethical constraints.

### 4.3 Personal Productivity or Education Agent

- **Problem:** Build an AI tutor, assistant, or planner that interacts naturally with users.
- **Application:** Combine **speech recognition (Whisper)**, **LLMs (GPT-4o / Claude)**, and **tool-use frameworks (LangGraph)**.
- **Extension:** Add **memory and scheduling** via vector databases and gcal integration.


### Many many more! 

#### Looking forward to your demos and artifacts! 


