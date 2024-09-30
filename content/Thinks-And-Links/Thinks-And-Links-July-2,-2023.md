---
title: Thinks And Links July 2, 2023
draft: false
tags:
  - Big Data
  - Data Analytics
  - AI
  - Cybersecurity
  - Generative AI
  - Data Governance
  - AI Risk Management
  - MITRE ATT&CK
  - AI in Business
---

# Big Data & Analytics - Thinks & Links | July 2, 2023

![](../images\1679742887729)

#### BD&A - Thinks and Links

Big Data & Analytics - Thinks and Links | News and insights at the intersection of cybersecurity, data, and AI

![This Lakehouse is made of data bricks](../https://media.licdn.com/mediaD4E12AQEORyFVVT3SHw)

### Happy (early) Independence Day!

#### Living in the future

The first thing you’ll notice on the drive from San Francisco’s airport is that unlike anywhere else in the country, the billboards here all seem to be about AI. The Bay Area is buzzing with excitement over Large Language Models and Generative AI. I was in town this week to participate in Databricks’ Data and AI Summit – so perhaps I should not have been surprised.

Attending a conference surrounded by several thousand of the most enthusiastic early-adopters of these capabilities is a great way to see what is coming. While many companies are still working hard to understand AI’s potential and risks – most are not yet ready with production models. But a growing number of them are, and I was very interested to learn about what they’re doing around risk and security. Here are a few of my takeaways from a week in Data and AI Nirvana:

#### Security and Governance are Central

The most impressive use cases for AI rely on secure, governed data, infrastructure, and tools to deliver. Model accuracy and the near elimination of “hallucination” are mainly driven by having sufficient quality data and tooling to wrap around the large language model. This takes the form of custom tuning of a general LLM, using prompting to guide models to higher accuracy, and having guardrails on the final output. You cannot get Large Language Models or other AI to production safely without it.

#### Use AI to Secure AI

Models that have made it to production have had a number of reviews before going live. These are often in alignment with concepts like NIST’s AI Risk Management Framework or similar frameworks. Practitioners are using AI to create synthetic data which can validate models are not responding to inputs inappropriately or showing signs of bias. Other AI can be used to bolster anomaly detection and shifts in model performance that indicate a deterioration of its functionality. There are a number of organizations looking to standardize these approaches and provide resources for the model building community. Selecting the right test cases and monitoring frameworks will be key to let AI Secure AI.

#### AI is Embedding in Every Product

I was not surprised when Databricks announced Lakehouse IQ which is a knowledge engine that enables things like natural language queries, coding assistance, and administrative automations. It uses a variety of techniques to understand the business context of the data on the platform and then uses large language models to allow you to talk to your data. This capability will very quickly mean that non-technical users of the platform can so many powerful tasks.

Databricks has the resources to build and secure their internal language models. Those resources were bolstered by another big announcement of the week involving the acquisition of a major OpenAI competitor. So the security implications aren’t as broad. But in a client conversation another example that reinforces this theme is when a tool which had access to thousands of internal meeting recordings and transcriptions suddenly announced it’s own ChatGPT-like capabilities. This client was upset to learn that a tool which had been vetted and handled as a subcontractor had suddenly enabled OpenAI to potentially receive sensitive information that hadn’t been explicitly approved.

#### Themes of Generative AI Use Cases + One Extra

Many of the presentations and discussions at the event were focused around Large Language Models and other forms of Generative AI solving one of the following business problems:

These are powerful use cases with many opportunities across industries. In the hallways and some advanced sessions, there was another exciting opportunity that deserves recognition:

Most autonomous AI agents right now make for awesome demonstrations, but they don’t quite work. However, there are teams who are solving some of the foundational problems. Better agents are coming very soon and may be very powerful for additional use cases as well as additional risks. Trusting an agent in your environment will be an even higher bar to secure than a stand-alone large language model. But CISOs and risk professionals will need to be familiar with this use case as well to be ready to provide security best practices.

---

Most Enterprise SIEMs Blind to MITRE ATT&CK Tactics

https://www.darkreading.com/analytics/enterprise-siem-blind-mitre-attack-coverage

A recent report by CardinalOps revealed that most SIEM implementations have significant gaps in coverage, only detecting 24% of all MITRE ATT&CK techniques used by threat actors. Organizations aren’t doing enough to focus on scaling detection-engineering. Automation can help to accelerate this as well as to be ready for SIEM detections against AI-enabled threats

How Generative AI Can Dupe SaaS Authentication

https://thehackernews.com/2023/06/how-generative-ai-can-dupe-saas.html

Companies of all shapes and sizes rely on SaaS components to carry on business. This article discusses several of the ways that AI can be used either directly against them or as a “trojan horse” to enable traditional attacks. Implementing multi-factor authentication, physical security keys, and continuous monitoring are all good ideas for your SaaS platform. Security tooling, proactive communication with employees, and a robust security solution are all important to mitigate these risks.

Cloud Security Alliance ChatGPT Guidance Paper

https://cloudsecurityalliance.org/press-releases/2023/04/24/cloud-security-alliance-releases-first-chatgpt-guidance-paper-and-issues-call-for-artificial-intelligence-roadmap-collaboration

Sharing another helpful resource – this time from the Cloud Security Alliance (CSA) – called "Security Implications of ChatGPT." The report discusses how ChatGPT can aid cybersecurity, its potential misuse, direct attacks on it, and responsible usage guidelines. Additionally, it suggests various use cases for enhancing cybersecurity in organizations.

Denver-based Cybersecurity Firm Discusses Generative AI and Security

https://digital.cobizmag.com/2021/SUM23/index.html (Page 78 & 79)

Navigate through this e-magazine to see an interview about AI, cybersecurity, and risk management. Available in print for those of you in Denver!

Executives (Wisely) not Reducing Headcount Due to AI… Yet

https://www.forbes.com/sites/joemckendrick/2023/06/28/executives-not-inclined-to-remove-humans-from-ai-decision-making/?sh=7fd58177778b

A survey of 1,000 executives worldwide reveals that 93% believe it is important for humans to have oversight of AI and machine learning when making significant decisions. Executives feel pressure to implement AI but are hesitant to give up decision-making power. Despite concerns, executives report business benefits from AI, such as better decision-making, automation of processes, and increased productivity.

---

Have a Great Weekend!

![No alt text provided for this image](../images\1688332870447)
