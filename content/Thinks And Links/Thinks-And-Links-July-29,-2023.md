---
title: Thinks And Links July 29, 2023
draft: false
tags:
  - Big Data
  - Data Analytics
  - Cybersecurity
  - AI
  - NIST AI Risk Management Framework
  - AI Governance
  - AI Ethics
  - Machine Learning
---

# Big Data & Analytics - Thinks & Links | July 29, 2023

![](../images\1679742887729)

#### BD&A - Thinks and Links

Big Data & Analytics - Thinks and Links | News and insights at the intersection of cybersecurity, data, and AI

![](../https://media.licdn.com/mediaD4E12AQEXnjMInIF0Tg)

### Happy Weekend!

A widely covered research paper came out a few weeks ago from Stanford University and UC Berkeley1 about the degrading performance of GPT-4 over the last few months. Researchers showed that the model no longer performed as well on multiple tasks as originally advertised. This is likely due to trade-offs made by the company regarding performance and security. AI models can be instructed to finish processing sooner at the expense of having as useful of an output. They may also have additional instructions they’re following related to safety and bias which can degrade the primary sentence completion capabilities. Some of these changes are rather dramatic:

![No alt text provided for this image](../images\1690595288560)

There are several interesting implications of this study worth noting from a cyber and security perspective:

#### Models Change

No matter how carefully you train and govern your AI, the performance that you saw yesterday is not guaranteed today. In the case of ChatGPT, the model itself is regularly tweaked and altered. Often these changes are not widely publicized. If you are relying on the APIs from OpenAI or other platforms, you do not control how and when the model changes happen. Ultimately you sacrifice some control and complexity in exchange for generally excellent models that are good at most things.

#### Data Changes

Even if you build your own LLM, it is likely that you will need to retrain and/or re-tune it as your context evolves. The data that you used to develop the model may not match the data you’re working with today. This might especially be true when you’re working with a fine tuned version of one of the large public models or a custom-developed model that is specific to your use case. Data drift and model drift are common phenomena in the AI/ML lifecycle. Large Language Models should be added to the tooling used to detect and mitigate the impact of degrading model performance.

#### Degrading Models are Vulnerabilities

If you are building functionality that depends on a model to perform a certain way, the degrading capability can be considered the equivalent of a software vulnerability. The largest and well known models can make changes that may – for a time – create an opening for an attacker to take advantage of these weaknesses. The OpenAI API can be configured to call out to a specific version of each of their main models. It may be wise to direct queries to these endpoints rather than the general ones which update whenever OpenAI decides to. Of course, there is nothing to stop them from making changes to the timestamped versions, but at the very least it is worth tracking. Likewise with Open Source models – these can be tracked based on when they were downloaded and implemented. Should a degradation be detected in the wild, it would be advisable to change the model or pause any automation relying on it.

#### Measurement Matters

This research made a deliberate effort to capture model performance against benchmarks at different points in time. The implication is that if you are to use a model like this in production, you may want to model the base LLMs performance independent of any additional monitoring within your product or service. These benchmark test consist of a set of questions to send into the model along with expected results. Maintaining that set of questions for future model validation (or gradually adding to the test suite as new model uses are built out) is likely an important role for a centralized model governance or data science team. Perhaps everyone in your business will get to have their own LLM-powered copilot. I can imagine a business function (or future managed service) that would keep tabs on the underlying LLM for degradation and vulnerabilities.

We’re still early in the story of LLM adaption. Depending on your use case and risk tolerance, issues like model degradation may not be a big deal. It matters a whole lot when the LLM is driving core business functionality or can have an outsized impact on customers or society. Regulation is coming in Europe and elsewhere to encode that level or rigor into law. Research like this shows why regulation may be crucial in preventing businesses from hastily deploying LLMs and missing the warnings if they start to get dumber.

---

#### New Large Language Model Vulnerability Discovered

https://www.cylab.cmu.edu/news/2023/07/24-research-find-vulnerability-in-llms.html

http://llm-attacks.org/

Researchers have developed a new variation of prompt injection that sufficiently confuses large language models so that they can be jailbroken to circumvent safety controls on the model that would normally prevent it from providing harmful answers. This injection was found to work on many different LLMs, both open and closed source (e.g. Llama2 and OpenAI GPT-4).

It is likely this will be “patched” by updated versions of these models and potentially by fine-tuning techniques, but it highlights the degree to which these components will be potentially exploitable in the future. Vulnerability monitoring and patching of AI will be just as important soon as it is for software.

#### OpenAI Closes Down its AI Classifier Tool

https://futurism.com/the-byte/openai-shuttered-ai-detection-tool

OpenAI arguably has the most advance text generation capabilities in the world right now via the GPT-4 model and the ecosystem of other LLMs and related tools. Their decision last week to shut down their AI detector showcase just how hard – potentially hopeless – a purely automated AI detector will be. There were many instances of false positives, including some students and the US Constitution. There will need to be more complex approaches to verifying accuracy – think two factor authentication but for writing. In the meantime, since no one can tell what’s real and what’s AI – now’s a great time to bring back oral exams.

#### Third Party Liability and Product Liability for AI Systems

https://iapp.org/news/a/third-party-liability-and-product-liability-for-ai-systems/

Who is responsible for the outcomes of AI? Software makers and service providers may find that AI capabilities are treated much less favorably than traditional services. This article summarizes recent legal rulings and regulatory guidance on liability of vendors in the context of AI and software development.

Relatedly, Accenture faced liability while acting as a cybersecurity service provider to Marriott following a large data breach. AI, data privacy, and cybersecurity all share a similar risk characteristic and are likely to become riskier over time. As courts and regulators are reaching further into the relationships that power outcomes, it will become the responsibility of all stakeholders to be knowledgeable about cybersecurity, data privacy, and AI. The article helpfully references the NIST AI Risk Management Framework, which is an excellent resource for any firms that foresee an entanglement with AI regulations and liability. (Hint – that’s probably your business now or sometime soon)

#### Less Talk, More Executive Orders

https://www.wired.com/story/the-white-house-already-knows-how-to-make-ai-safer/

This editorial by a former Biden Administration official calls for the use of Executive Orders to instantly put into place a national regulatory framework for AI. He argues that the Blueprint for an AI Bill of Rights and the NIST AI Risk Management Framework are both standards that the administration could require be enforced in the executive branch immediately. The executive order could require government agencies, federal procurement, recipients of federal funds, and regulatory agencies to comply with these practices. This would rapidly bring to bear a large amount of testing, monitoring, and disclosure requirements for AI systems. Should the federal government make this change it would have a huge impact on the AI products and services market.

---

### Have a Great Weekend!

![No alt text provided for this image](../images\1690595350870)

---

_[1] – Fun fact, in addition to publishing the paper on ChatGPT’s apparent decreasing capabilities, **Matei Zaharia** is CTO and Cofounder of Databricks and the creator of Apache Spark. This research paper is via his role as a Computer Science professor at Berkeley, although Databricks does have an excellent GPT-3 alternative in **Dolly**. _
