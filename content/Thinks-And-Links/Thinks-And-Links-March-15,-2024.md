---
title: Thinks And Links March 15, 2024
draft: false
tags:
  - Generative AI
  - Cybersecurity
  - AI Risks
  - AI Regulation
  - Machine Learning
  - AI Ethics
---

# Thinks & Links | March 15, 2024

![](../images\1679742887729)

#### BD&A - Thinks and Links

Big Data & Analytics - Thinks and Links | News and insights at the intersection of cybersecurity, data, and AI

![](../https://media.licdn.com/mediaD4E12AQHgKY2iJG8BSg)

_📫 **Subscribe to Thinks & Links** direct to your inbox_

### Happy Friday!

### The Journey Towards Secure AI

AI over the last fifteen months has been massively accelerated thanks to large technology companies incorporating Generative AI models into as many products as possible. I would argue that no one has done this more effectively than Microsoft. Their partnership with OpenAI and rapid incorporation of GPT-4 capabilities across their ecosystem has onboarded hundreds of thousands of people into Generative AI use.

It's disheartening to learn this week of a major breach by Russian state hackers. Microsoft disclosed that Russian state hackers (APT29 aka Cozy Bear) penetrated their defenses back in November, accessing source code, emails, and who knows what else. We don't know which source code was compromised, but the bad guys have open access to find holes and backdoors. Microsoft is one of the largest targets in the world, and successful compromise of their systems and source code makes every other company less secure.

It's a poignant reminder however that no matter how large the technology company, their security is not guaranteed. Generative AI can massively impact businesses by working with some of their most sensitive data - and that data's security is not a supplier's responsibility. It's yours.

Businesses that are working with AI are at the early stages of a long journey right now. They may have proofs of concept in place. Some are even in production. But the risk of data loss and system compromise is mitigated in part by being discerning about which use cases AI touches. Don't want to risk losing sensitive data? Don't work with sensitive data. Ships are safest in the harbor, but that's not what they're built for.

As organizations get comfortable with deploying and monitoring Generative AI, there will likely be shifts to tackle more complex use cases. The stages of the journey might be as follows:

Public AI - Using sites like ChatGPT and claud.ai to experiment with generative capabilities. Paying for the full versions of these products offers the chance to try agents, automations, and retrieval in a curated and high-performant environment. Nothing sensitive should be shared and tools can monitor and block risky interactions

Prompt Engineering - Developing highly tailored prompts for the AI tools which are likely to provide the kinds of outputs the business expects. The most capable AI models (GPT-4, Gemini Ultra, Claud Opus) are the best at taking prompts and returning reliable results via reliable APIs. At this point security can still monitor usage and a review process can ensure nothing is included in prompts that wouldn't be OK to be posted on the cover of the Wall Street Journal. (e.g. security and privacy are not assured)

Retrieval Augmented Generation ([[RAG]]) - As AI use cases get more complex, firms must rely on their own data to drive insight and the LLM to act as a reasoning engine. RAG methods stage the appropriate data into the input prompt so that the output is more likely to be accurate (e.g. not hallucinated)and to provide some lineage back to the source systems/data. At this point, many firms are switching over from a public model to a private hosted instance. Azure, AWS, and GCP all provide options to access secure copies of the most capable models within your own cloud infrastructure. Some firms are also opting to bring the models on premises. This is possible with Open Source models like Meta's Llama and the large cohort of models that are hosted on Hugging Face and elsewhere. These models introduce new risks into your environment - can contain malware and backdoors, and can be very use at your own risk. In exchange for bringing in the new tool you get complete control over what goes into and out of the model.

Fine Tuning - As AI usage grows and becomes more sophisticated, so too will cost. Many organizations are discovering the pain of repeated queries to a large model end up delivering a very high bill. Complex use cases can include several or even dozens of model calls. A promising solution is fine tuning open source and smaller models on specific use cases. Organizations that have been working with AI for a while likely already have the teams and tools necessary to perform this. As with everything AI, it's all about the data. Gathering and calibrating an appropriate fine tuning training data set can be a challenge. However once you fine tune the model, your organization has even greater control over the outputs. These fine tuned models represent risks in the kinds of proprietary information they'll contain. There's no reliable way to fine tune a model to make it "forget" what it's been trained. So once you share your company secrets in a customized model, that model could be accidentally or purposely used to spill them. The data, model artifacts, and software involved all become high priority company crown jewels.

AI Risks are similar no matter how far down the journey you go. In the early stages, the control firms have is limited, and so the trust that gets extended to AI must necessarily be so too. When new tools and platforms arrive using Generative AI, it's important to assess them against the maturity level they claim to be at. A fully fine-tuned solution for your business better be locked down so that your models don't comingle with other customers of a vendor. If a new tool relies on Bagel-Hermes-34B-Slerp or SauerkrautLM-7b-LaserChat you may want to thoroughly test it before welcoming it into your environment.

The journey of a thousand miles begins with one step. Generative AI will be a part of our technology discussions for the rest of our careers. Don't let the long and winding road to secure AI intimidate you. Whether you're just testing the waters with public AI or diving deep into the fine-tuning ocean, the key is to keep your head above water with the right mix of enthusiasm and caution.

---

#### Europe - The Final Countdown

The EU AI Act has been approved by the European Parliment, codifying the most sweeping regulation of AI capabilities to date. Europe's legislative process is long and involves a lot of collaboration, so today's approval is both a major milestone and not quite finished. It will enter into force twenty days after its publication into the official journal and will start to be enforced over the following two years.

The Act employs a risk-based approach to AI regulation with some practices to be banned outright as unacceptable risk (e.g. social scoring by public authorities, manipulative AI, and indiscriminate surveillance). Others in high risk categories (e.g. healthcare, law enforcement, critical infrastructure) will be required to submit to strict oversight. That includes:

Conformity Assessment: Providers prove system compliance before market introduction

Monitoring: Continuous performance assessment and compliance monitoring after deployment.

Market Surveillance: Member States will monitor and enforce AI system compliance

Data Governance and Transparency: Declaration of system accuracy, resilience against errors, and robust data handling practices.

Documentation: Required maintenance of detailed documentation on AI system development, functioning, and security measures.

The EU's lead in AI regulation will be monitored closely by businesses and governments around the world. Successes and failures in Europe are likely to inform in-development regulations everywhere else. It's almost time to see what happens next.

#### Introducing Devin, the First AI Software Engineer

https://www.youtube.com/watch?v=fjHtjT7GO1c

Meet Devin, an AI software engineer created by Cognition AI. This video showcases Devin's capabilities by having it benchmark the performance of an AI model across several API providers. Devin tackles the problem by first creating a step-by-step plan and then building the entire project using the same tools a human software engineer would use. This includes a command line, code editor, and even its own browser.

In the video, Devin uses the browser to pull up API documentation to learn how to plug into each API. When Devin runs into an unexpected error, it is able to debug the code by adding a debugging print statement and then using the error in the logs to fix the bug. Finally, Devin builds and deploys a website with full styling as the visualization.

As tools like Devin enter our client's environments, there will be an important role to play in guiding them towards secure SDLC practices and monitoring their actions to conform with our policies. This will not eliminate software engineering, but shift the focus into keeping the AI coders aligned with the mission. Expect more agents like this for other job functions in the coming months.

#### ChatGPT in a Robot

https://www.youtube.com/watch?v=Sq1QZB5baNw

In an impressive video demonstration, a Figure AI robot showcases its advanced reasoning capabilities powered by GPT-4. The robot successfully identifies an edible apple and gently gives it to a person upon request, explains its decision-making process, determines that dirty dishes belong on the drying rack and places them there, and self-evaluates its performance. This demonstration highlights the rapid convergence of AI for reasoning and robotics, and the potential for AI models to very soon assist with real-world tasks. When AI Security meets physical security the need for governance and controls becomes even more urgent.

#### Ensuring Safe and Effective Healthcare AI: Lessons from Mayo Clinic

https://www.healthcareitnews.com/news/john-halamka-risks-and-benefits-clincial-llms

In a keynote speech at HIMSS24, Dr. John Halamka, president of Mayo Clinic Platform, discussed the potential benefits and risks of using predictive and generative artificial intelligence (AI) in clinical settings. He emphasized the need for transparency and accountability in healthcare AI models to ensure their credibility and effectiveness.

Key points:

Data quality: AI needs high quality, representative data to avoid bias.

More data = better AI: Diverse, multimodal data from lots of patients makes for resilient models. Collaboration is critical.

Careful data selection: Including certain data elements, such as race and ethnicity, may introduce bias into AI models if not biologically relevant.

Test, test, test: Data sets should be evaluated for fairness, effectiveness, and safety. The Coalition for Health AI (CHAI) is working to define these metrics and provide resources for the community.

Bias mitigation: Inherent biases in AI algorithms can be identified and mitigated by retraining the models on different data or understanding their limitations.

Generative AI challenges: Evaluating generative AI is more complex than predictive models, as the accuracy of the output depends on the prompt given. Careful validation and deployment processes are necessary to ensure patient safety.

Mayo Clinic has developed strategies to derisk AI development, including data de-identification, model validation, and deployment. Dr. Halamka encourages healthcare organizations to learn from Mayo's experiences and utilize resources from CHAI to build a virtuous AI lifecycle that ensures safe and effective healthcare AI.

#### Why Adopting Gen AI is So Difficult

https://hbr.org/2024/03/why-adopting-genai-is-so-difficult

HBR reports many of the leaders they've interviewed report struggles with Generative AI. This is due to three primary concerns:

Most businesses haven't fully adopted predictive AI and traditional Machine Learning models. Lack of familiarity and capability to use data and models to drive value transfers over when they attempt to do similar things with the cutting edge Large Language Models.

The complexity and expense of LLMs is greater than what could be achieved with simpler models. Despite the magic of ChatGPT, AI doesn't solve all problems auomatically.

Massive uncertainty around the security, long-term costs, regulation, and impact on the job force.

Despite these challenges, organizations are pressing forward by bringing in the needed expertise, rationalizing their analytics processes, choosing high-impact use cases, and building resilient AI systems.

#### What is Trusted and Secure AI Anyway?

https://arxiv.org/abs/2403.05957

A fascinating new research paper explores what motivates people to trust AI systems. The study, based on a survey of over 450 participants from more than 30 countries, uncovers four key rationales that influence people's willingness to trust AI: the Human favoritism rationale (humans perform better than machines), the Black box rationale (we should only trust what we can question and explain), the OPSEC rationale (we should be cautious about any use of AI), and the 'Wicked world, tame computers' rationale (many real-world problems are too complex for algorithmic representation). These rationales provide valuable insights into how people perceive and evaluate the trustworthiness of AI systems, and could inform the design and development of more trustworthy AI. The findings also highlight some interesting discrepancies between scholarly discussions and public perceptions of AI, such as the near absence of terms like "fairness" and "ethics" in the survey responses. As AI continues to advance and permeate our lives, understanding these trust dynamics will be crucial for fostering responsible AI adoption and mitigating potential risks. (Summarized by Claude)

---

### Have a Great Weekend!
