---
title: Thinks And Links October 8, 2023
draft: false
tags:
- Big Data
- Data Analytics
- Cybersecurity
- AI
- Machine Learning
- Generative AI
- AI Security
- Technology News
---

# Thinks and Links | October 8, 2023

![](../images\1679742887729)

#### BD&A - Thinks and Links

Big Data & Analytics - Thinks and Links | News and insights at the intersection of cybersecurity, data, and AI

![](../https://media.licdn.com/mediaD4E12AQFO25A-RsWLLA)

### Happy Weekend!

13 months ago an article called Text Is the Universal Interface was posted online to be consumed by an audience of Machine Learning enthusiasts and tech startup types. I re-read it this weekend to remind myself of both the philosophical point it made and how far we’ve come in such a short time.

The article draws an interesting parallel between the Unix philosophy of the 1960’s an 1970’s and the state of the art in working with language models. Since the time after computers being programmed with literal switches and punch cards, software has been controlled with text. Unix tools have a standard interface, can be composed into sequences, and use language to control how text inputs become text outputs. We all know that somewhere a compiler turns it into electrical signals specifying bit-wise instructions, but that hasn’t mattered for a very long time.

Last September, this article called out the phenomenon that was itself already a few years old. The rise of Prompting as a new interface for computing. Rather than write code, computers can now be instructed with language to perform tasks. Tactics learned from earlier machine learning guides prompt engineers to discover more effective “incantations” with text that are both more likely to result in the correct output and use fewer tokens. As the underlying language model gets better, prompts become even more effective or potentially compress.

Then there’s the question of dealing with non-text information. As the original GPT-4 paper promised, and OpenAI is finally delivering – multi-model (e.g. image, audio, and text) language models are here. These tools as well as the earlier examples from of Dall-E and Midjourney further support the argument about language models and their prompts eventually becoming foundational to software.

There’s also code generation, which has been available since before the time of this paper and has hit serious new strides this year. With better and better foundational models, the output can become stronger and conversation versus code becomes the necessary skillset. Might this even extend down to the operating system level? Windows 11 is all about AI as Copilot. What will Windows 12 be? And if LLMs continue to become as integral to the software stack as Unix – that means a whole new world for security and risk management.

---

#### Microsoft is Getting into Generative Agents with AutoGen

https://www.microsoft.com/en-us/research/blog/autogen-enabling-next-generation-large-language-model-applications/

Microsoft has released an open source framework called AutoGen for creating systems of interacting, task-solving AI agents. The framework allows users to quickly build specialized AI agents which can do things like generate and execute code, browse the web, and solving complex tasks. These can quickly spin up experiments in having multiple agents collaborate on solving a task via a committee or simulating a community. It is telling to see the tech giant innovating in this space, where future versions of it’s own CoPilot application may borrow from these multi-agent models.

#### New Open Source Tools for AI/ML Protection

https://www.businesswire.com/news/home/20231005973991/en/Protect-AI-Open-Sources-Three-Tools-to-Help-Organizations-Secure-AIML-Environments-from-Threats

Protect AI, a leading AI and machine learning security company, has released open-source software tools to help organizations protect their AI and ML environments from security threats. The tools include NB Defense for Jupyter notebook security, ModelScan for ML model security scanning, and Rebuff for detecting malicious inputs in applications built on large language models. These tools are freely available and aim to raise awareness about the need for AI security. Protect AI also offers the Protect AI Platform, which provides visibility, auditability, and security for ML systems.

#### FS-ISAC - Framework of an Acceptable Use Policy for External Generative AI

#### https://www.fsisac.com/hubfs/Knowledge/FrameworkOfAnAcceptableUsePolicyForExternalGenerativeAI.pdf

The Financial Services Information Sharing and Analysis Center (FS-ISAC) has released guidance on an acceptable use policy for employees regarding the use of generative AI systems. It emphasizes the importance of preserving the confidentiality of company work products and adhering to company policies and standards. The template provides guidance on what employees should consider and not share when using generative AI systems, such as intellectual property, proprietary information, and personally identifiable information. It also discusses the responsibility of employees in safeguarding against malicious activity and provides guidance on access control, monitoring, and the accuracy of generative AI systems.

#### Evaluating LLMs is A Minefield

https://www.cs.princeton.edu/~arvindn/talks/evaluating_llms_minefield/

A presentation given earlier this month showcasing some of the things we thing we know about LLMs may not be true. The research community needs access to models that don’t change to make reproducible studies. Progress with AI can’t just be about building things. We must get better at knowing how to test and secure them.

#### Navigating the Jagged Technological Frontier

Blog Post: https://www.oneusefulthing.org/p/centaurs-and-cyborgs-on-the-jagged

Research Paper:  https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4573321

Consultants at BCG took part in a large study this year to understand the impact that Large Language Models (specifically ChatGPT using GPT-4) would have on their productivity. This image from the research paper is the most striking answer:

![](../images\1696797080391)

The blog post talks a bit more about the nuance of these results. The “jagged technological frontier” refers to the fact that ChatGPT is not good at all things and the most successful participants in the study adopted either a centaur or cyborg approach:

Centaurs – named for the half man, half mythical beast would formulate a task and do their work as a human, then pass it to the AI for completion. Or would work vice-versa with clear distinctions between each part

Cyborgs – would be continuously partnering with AI, feeding it instructions for how to change the output and logic along the way

Neither approach is determined as categorically better, however the findings from the study are hard to ignore for those of us in the consulting (and knowledge work) business…

#### Making “Black Box” AI Models More Transparent

https://transformer-circuits.pub/2023/monosemantic-features/index.html

This was a very interesting, highly technical research paper from AI company Anthropic which claims to have a method to detect which parts of a very simple AI model are driving which behaviors. One of the biggest risks with using Large Language Models and other forms of Deep Nueral Network models is that it is impossible to know with complete certainty what output they will produce. If this research approach is successful, it may be a step towards being able to identify the specific parts of a model that would produce a negative outcome and control it. This would be revolutionary for safety and alignment of AI models. This is very early, but an area to watch, especially from an AI Security and Safety perspective.

---

### Have a Great Weekend!

![](../images\1696797150019)