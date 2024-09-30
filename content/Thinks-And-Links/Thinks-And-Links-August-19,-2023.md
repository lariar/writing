---
title: Thinks And Links August 19, 2023
draft: false
tags:
- Big Data
- Data Analytics
- Cybersecurity
- AI
- Large Language Models
- Databricks
- Machine Learning
- Model Governance
- AI Cybersecurity
- DEF CON
- AI Deployment
---

# Big Data & Analytics - Thinks and Links | August 19, 2023

![](../images\1679742887729)

#### BD&A - Thinks and Links

Big Data & Analytics - Thinks and Links | News and insights at the intersection of cybersecurity, data, and AI

![](../https://media.licdn.com/mediaD4E12AQEPGvw_94DnIg)

Happy Weekend!

I recently completed a training course from Databricks on Large Language Models: Application through Production. I would recommend it to anyone who is interested in a technical overview of the ways that the best data teams are implementing LLM solutions. The course provides fantastic education on leading practices for model selection, prompt engineering, vector databases, reasoning agents, LLM fine-tuning, use of Databricks’ own Dolly model, measuring bias, limiting hallucination, and integrating LLMs in to traditional MLOps.

If you are technically inclined, you might enjoy the materials and code notebooks available here.

Here are a few takeaways you may find interesting:

1.There are a lot of models! I’ve shared this site from Stanford before which tracks the major models, but I found in this course that even selecting models for labs there were many, many options.

2. Prompting is an important part of the development lifecycle. Production applications use prompt templates to standardize and mitigate the risks of hallucinations and injections. The approach to finding the right prompt is not unlike the need to perform hyperparameter tuning on other forms of AI. And there are automation methods available to search through potential prompts to find the best one.

3. Vectorization is the magic behind LLMs and is still vastly underestimated. As a refresher – vectors are created by these models so that text, images, and audio can be represented as a set of numbers. These numbers relate to each other in ways that make it possible to find similar things just by calculating the distance in between them. This slide had a nice visualization of how vehicles and animals might be represented differently as vectors, but then could be grouped together in a plot:

![No alt text provided for this image](../images\1692497915799)

4. Agents are also very exciting, and this course provided lots of great insights into how they function. Here’s a slide that nicely recapped the process where the code runs through a thought / action / observation loop – where the LLM is the “brain” to determine if a task was completed or what should be done next if not:

![No alt text provided for this image](../images\1692497974159)

5. Hello Dolly – it wouldn’t be a complete LLM course from Databricks without their own LLM option, complete with tutorials for loading and fine-tuning Dolly in a commercial use-approved manner.

6. Measurement is important, and there were a lot of examples of ways to test that LLMs are performing as expected. This includes metrics around task performance such as evaluating responses to questions or effectiveness of summarizations. It also included alignment metrics to make sure models are helpful (follow instructions), honest (minimize hallucination), and harmless (avoid toxicity or bias). And maybe you were wondering, but part of the fun of testing for toxicity is that you must swear at AI models.

7. Related to measurement – the criticality of governance and process to audit and monitor the model and the applications that use the model. Something that made this crystal clear to me was the implementation of a simple test for bias in one of the original foundational LLMs called BERT. Here’s a small snippet of code that demonstrates how massively biased this model can be and why racing into production with it would certainly lead to reputation harm or worse:

![No alt text provided for this image](../images\1692498039629)

The course was very wide-reaching into topics of governance and security of LLM models. It re-affirmed that the research and delivery work we’ve been doing with our clients it aligned. These are still early days, but as more and more clients look to bring LLMs into production, considerations such as the ones from this course will be key to doing so safely. people looking into these problems now, but resources from the course have helped me to further refine the Optiv answer for how to govern and secure AI.

---

$20 Million up for grabs in AI Cybersecurity Contest

News Story: https://www.cnbc.com/2023/08/09/biden-admin-launches-hacking-challenge-to-use-ai-for-cybersecurity.html

Sign Up for Updates / Eventual Registration: https://aicyberchallenge.com/

An announcement at Black Hat two weeks ago from the Biden administration included the launch of a competition for teams to compete for cash prizes for the best technology able to use AI for securing critical US systems. The contest will formally start in the Spring, semifinals at DEF CON 2024, and the grand prize will be awarded at DEF CON 2025. Collaboration with Google, OpenAI, Microsoft, and others will be a part of the contest. If you have any interest in forming a team to join this contest, please reach out!

How to Break LLMS: 5 Ways from DEF CON 2023

https://www.techopedia.com/how-to-break-llms-5-ways-from-def-con-2023

DEF CON 2023 recently included a 3,500 person AI Red Team event where researchers had 50 minutes to discover a vulnerability or error in an unidentified AI model. What’d they do?

The best way to defend against these risks is to continue to probe them and understand mitigations to reduce their likelihood and impact.

Boring AppSec – A framework to securely use LLMs in companies

https://boringappsec.substack.com/p/edition-21-a-framework-to-securely

https://boringappsec.substack.com/p/edition-22-a-framework-to-securely

![No alt text provided for this image](../images\1692498078537)

These two blog posts are excellent overviews of the risks associated with the deployment and usage of Large Language Models in enterprises. Understanding these risks is essential for implementing effective security measures and ensuring the safe adoption of AI technologies in organizational processes. The articles also offer frameworks for prioritizing and addressing these risks based on their organization's specific use cases and deployment types. These go in to a great deal of detail, but do a great job of synthesizing the relevant points for security-minded readers.

Build your own AI Sim City

https://github.com/a16z-infra/AI-town

Back in April I shared this paper where Stamford researchers had created a fun little “Sim City” to research how AI agents interact and respond to social activities. Four months later, venture firm Andreessen Horowitz has open sourced a code repository for developers to build their own version of the experiment. “AI Town” is a “deployable starter kit for easily building and customizing your own version” of this experiment. This code base can be further modified to make a playable game or also conduct further research into the state of the art for multi-agent AI models.

Yikes!

https://www.darkreading.com/attacks-breaches/ai-model-can-replicate-password-listening-to-keystrokes

A new AI model, trained on keystrokes recorded over a smartphone, can decipher typing and steal passwords with 95% accuracy. Researchers from Cornell University highlighted the increasing threat of acoustic side channel attacks on keyboards due to advancements in deep learning.

---

Have a Great Weekend!

![No alt text provided for this image](../images\1692498112121)