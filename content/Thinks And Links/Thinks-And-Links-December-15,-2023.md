---
title: Thinks And Links December 15, 2023
draft: false
tags:
  - Big Data
  - Data Analytics
  - Cybersecurity
  - AI
  - Generative AI
  - Deep Learning
  - Machine Learning
  - AI Safety
  - AI Ethics
  - Generative AI Impact
---

# BD&A - Thinks & Links | December 15, 2023

![](../images\1679742887729)

### Happy Friday!

#### Everything is Evals, just ask David Lee Roth

It’s almost the end of the year and a time for reflection on what worked and did not work in 2023 as well as setting goals for 2024. A thought starter for me in this season were these recent tweets from OpenAI President Greg Brockman:

![](../images\1702698568302)

There are many reasons not to trust AI by default. Hallucination, bias, exposure of sensitive information, etc. Modern AI models are hugely complex and do not have an ability to precisely control responses. There are best practices – relying on trusted data, fine tuning, prompt engineering, retrieval augmented generation, knowledge graphs, etc. But at the end of the day placing AI into production requires some assurance that the model will behave as expected. It is impossible to reach 100% certainty.

This is a similar situation to what Greg describes as an “important leadership skill.” We can write job descriptions, standard operating procedures, playbooks, etc. But working with other humans can never be scripted with 100% certainty. We need to have measurement and a frame of reference to direct actions.

Evals for AI consist of a series of questions to provide to a candidate AI system along with the expected answers. A set of evals might look like this:

![](../images\1702698437182)

The question and four options are fed into the Large Language Model and it returns A, B, C, or D based on its understanding of the concept. This is then compared to the Answer at right to either be a 1 – correct or 0 – incorrect. You would expect a random guess at the answer to be right 1 out of every four times or 25%.

These questions come from the computer security test which is part of the Massive Multitask Language Understanding (MMLU) set of Evals. According to the research, the questions were chosen so that an expert human would score 90%. Every time a new foundational model is built or a new prompting, fine-tuning, or other research task is added - MMLU is one of the measures that is used to score how good it is. GPT-4 when it came out claimed to get 86.4% of all the evals correct. Gemini’s release last week scored 90.04% and Google made a big deal about how this was the first time that MMLU scores exceeded the expert level. (Microsoft recently counter-claimed a modified version of prompting GPT-4 could reach 90.1%)

Meanwhile, in the Open Source community, some of the best models score a little lower. Meta’s Llama 2 scores 69.9% while Mixtral 8x7B (unceremoniously released last week) is at 70.6%. The Hugging Face Open LLM Leaderboard tracks Open Source models uploaded to their repository. As of this writing the highest MMLU score there is 78.78% from PlatYi-34B-Llama-Q.

This doesn’t necessarily mean that the top scoring models are better. One of the cardinal sins in Data Science is training on your test data. In other words, since these MMLU questions are open source, it is easy for models to be trained to pass the test. That’s cheating and much like memorizing answers to a school test, it doesn’t set up the model for real world usefulness – just test fooling. An open forum like Hugging Face can have frauds and other suspicious content – so use with care!

Bringing models into production – and delivering security programs at scale – depend on framing. SOCs often turn to MITRE ATT&CK for framing and measuring detections. The very helpful DeTTECT Framework creates a structure along with ATT&CK to also measure data log source quality, coverage, and usefulness. MITRE ATLAS is a useful framework for aligning security with Artificial Intelligence systems. Van Halen included an eval within their tour contracts, one of my favorites.

Contracts for their tour in the 1980’s included a rider specifying that no brown M&Ms be allowed backstage. This eval is more like the others than you may think… including this tiny detail in the contract was a test to be sure that venues were detail-oriented enough to safely construct the complex sets that came with the show. A failure on the M&M test could also mean a missed detail in the construction that could be hazardous.

Evals less about spelling out precisely what to do, and more about what good outcomes look like. It’s a worthwhile framework to think about for personal goals as well as team, family, and business goals. What evals are you setting for 2024? Are you bringing in the right data sources to measure progress?

---

#### Purple Llama: Meta’s Open Source Trust and Safety Toolkit

https://ai.meta.com/blog/purple-llama-open-trust-safety-generative-ai/

Meta has created and distributed one of the most popular Open Source Large Language Models, Llama 2. They’re now also open sourcing a series of tools to make LLMs safer. The first round of releases includes evals (Evals are all you need!) for Cybersecurity. CyberSecEval can measure the likelihood of an LLM or AI solution on two dimensions:

How likely is this model going to generate insecure code

How helpful will this model be if asked to participate in a cyber attack

Running CyberSecEval helped to identify and correct weaknesses in OpenAI and Llama models.

Meta also released an Open Source model called Llama Guard that can be used to detect risky prompts and responses in AI systems.

#### How MLSecOps Can Reshape AI Security

https://www.forbes.com/sites/forbestechcouncil/2023/12/04/how-mlsecops-can-reshape-ai-security/?sh=3e5ae33c44ed

Ian Swanson, CEO and co-founder of Protect AI, discusses how MLSecOps, an evolution of MLOps and DevSecOps, aims to enhance cybersecurity in AI and ML applications. He outlines five core domains of MLSecOps:

Supply Chain Vulnerability

Model Provenance

Governance Risk and Compliance (GRC)

Trusted AI

Adversarial ML.

Swanson emphasizes the need for transparency, accountability, and robust security practices throughout the ML development lifecycle to protect against threats like data poisoning, malicious code, and regulatory risks.

#### New AI Tool: NotebookLM

https://blog.google/technology/ai/notebooklm-new-features-availability/This is a really useful tool. Google soft-launched NotebookLM in July, but with the Gemini release it has become very capable. If you are researching a complex topic (say for a weekly newsletter) you can use this as a way to quickly load and work with documents. First upload the PDF, Google Docs, or text you are working with. Then chat with it. Discover content and make notes. For example, here’s what it found when I uploaded the history of this newsletter:

![](../images\1702698588284)

#### What Impact Will Generative AI Have on Cyber Insurance?

https://www.spglobal.com/marketintelligence/en/news-insights/latest-news-headlines/insurers-brace-for-claims-from-generative-ai-surge-79584195

An interesting overview of the state of the Insurance Industry with regards to Generative AI.

So far, the industry has not imposed any generative AI-specific restrictions or exclusions to brace for these potential claims, but they are keeping a close eye on developments. Some insurers already provide policies specifically to cover AI. Munich Re's “Insure AI” product suite has been doing this for six years. They will cover financial losses from underperformance of traditional AI models. They also cover Generative AI, for now. With the increased use and unique risk profile of new AI tools, it will be interesting to see how the market evolves.

#### New Discoveries using Large Language Models

https://deepmind.google/discover/blog/funsearch-making-new-discoveries-in-mathematical-sciences-using-large-language-models/

Researchers at Google Deepmind demonstrated how AI could advance the frontiers of knowledge. In this research paper, they demonstrate how an approach called “FunSearch” pairs a Large Language Model with an evaluation model. This combines the creativity of the LLM with the reliability of the evaluation model to search for new solutions to the research problems. This worked for the mathematics research tested in the paper. This is an approach that may one day apply to products and services near you. It is early, but AI is moving quickly.

### Have a Great Weekend!

![](../images\1702698612215)

_Chat with the archive of this newsletter at \*\*https://chat.openai.com/g/g-IjiJNup7g-thinks-and-links-digest_
