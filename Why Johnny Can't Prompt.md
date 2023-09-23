---
Date: 2023-09-18
tags:
  - research
  - CISC877
  - fall23
Week: W2
---

## Why Johnny Can’t Prompt: How Non-AI Experts Try (and Fail) to Design LLM Prompts

**Summary:**

For researchers, the combination of pre-trained large language models (LLMs) and prompt engineering is an appealing prospect. This scope includes how non-experts can design prompts using LLM-based tools, as well as the effectiveness of those prompts. Using a design probing prototype (a LLM-based chatbot design tool), the authors of this paper explored the scope of non-AI experts on prompt engineering. The authors developed "BotDesigner," a no-code LLM-based chatbot design tool that enables users to construct LLM-based chatbots using only prompts and encourages iterative design and evaluation of effective prompt strategies. Their findings, however, are limited to only 10 participants.

Their main contributions in this paper are the tool itself (BotDesigner), rich and rare description of how non-experts intuitively approached prompt design and where, how and why they struggled, identifying opportunities for non-experts facing prompt design tools and open research questions in making LLM-powered design innovation accessible. They also mentioned the known challenges in prompt design as well as explained the limitations of two prompt design tools (OpenAI playground and AI Chains).

While designing the no-code prompt design tool as a probe, the authors described the design goals and two challenges that need experimentation to achieve the goals. They address the challenges in a good way. The authors tried to present the whole workflow to their tool, which includes its conversation view and error browser. Also, they explained the whole process with an example. User study design is one of the key parts of this research, for which they invited only 10 participants. The authors explained the user's findings in a structured way. They explained how they approached the prompt design challenges while conducting these from the participant's perspective as well as the impacts on prompt design.

The findings indicate that although end-users may opportunistically explore prompt designs, they face challenges in achieving robust, systematic progress. These challenges are reminiscent of those frequently encountered in end-user programming systems (EUPS) and by novice users of interactive machine learning (iML) systems. The difficulties in effective prompt design arise from a restricted understanding of large language models' (LLMs) capabilities in prompt comprehension and execution. Moreover, there's a prevailing tendency among users to frame prompts in a manner akin to human-human interactions. The study further reveals that human intuitions, largely shaped by social interactions, considerably influence the type of prompts end-users are inclined to try. Such influences include a bias towards providing instructions rather than offering examples, making assumptions about the system's capabilities based on a limited set of interactions, and a reluctance to display emotions.

**Three Strong Points:**

1. **Identifying and addressing weaknesses in non-expert prompt design tools:** In the paper, the authors mention the goals they set while designing the tool. Also, they pointed out two challenges: how BotDesigner allows users to observe a prompt’s impact on a single conversation and how BotDesigner enables users to inspect a prompt’s impact on a full set of conversions. They address those challenges in a structured way with proper referencing.
2. **Formulation and descriptive structure of BotDesigner:** Despite having some flaws in the tool, the overall formulation and description of BotDesigner is good. The descriptions are backed with proper figures and explanations are detailed enough. The example section provides a lot of clarifications about the tool’s workflow. They also provide the implementation details and pilot evaluations as an appendix. The overall workflow of BotDesigner should be included in the main paper.
3. **Detailed observational findings:** The authors conducted a user study and provided detailed observational findings. They described the non expert’s approach to prompt design including their typical flow which was detailed enough. Also, they mentioned the challenges and impacts.

**Three Weak Points:**

1. **No replication package of BotDesigner:** The authors provided a descriptive appendix of the implementation of the tool. But there’s no replication package of this. As BotDesigner is one of the key points of this paper, the authors should add the replication package of that. Also, they should move the transcripts and other explanations there.
2. **User study is only limited to 10 participants:** The whole user study is limited to just 10 participants. In this paper, the authors presented a lot of impacts and these are based on the user study. All these findings can be biased with this limited number of participants. Also, while selecting the participants the authors should consider some more varieties of professions and age groups.
3. **Lack of visualizations and statistics:** The whole presentation of the paper is of a more descriptive type. It lacks visualization and statistics of user findings. Some statistics and visualizations of different user finding results should give us a bit more clear understanding.
4. Limited technical explanation of BotDesigner.
