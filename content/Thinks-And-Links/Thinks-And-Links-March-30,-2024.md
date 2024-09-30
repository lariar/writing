---
title: Thinks And Links March 30, 2024
draft: false
tags:
- AI
- Generative AI
- Open Source
- Cybersecurity
- Large Language Models
- AI Security
- AI Risks
---

# Thinks & Links | March 30, 2024

![](../images\1679742887729)

#### BD&A - Thinks and Links

Big Data & Analytics - Thinks and Links | News and insights at the intersection of cybersecurity, data, and AI

![](../https://media.licdn.com/mediaD4E12AQGBBkaXqVqlUQ)

📫 Subscribe to Thinks & Links direct to your inbox

### Happy Weekend!

#### DBRX

Databricks released DBRX this week, a powerful open source large language model that impressively beats a number of significant benchmarks. Accelerated by last year's acquisition of MosaicML, Databricks has not only created a useful model, but is demonstrating the possibilities for companies to work with them and use their platform to train or fine tune similarly powerful models.

Under the hood, DBRX leverages a combination of scale and architectural innovations to achieve its impressive results. With 136 billion parameters trained on a vast corpus of cleaned and curated data, it outperforms models like Llama 2, GPT-3.5, and Mixtral across a suite of natural language benchmarks. Even more notably, it comes close to matching OpenAI's GPT-4 and Gemini 1.0 Pro on several tasks, a remarkable feat for an open source model. The use of techniques like "mixture of experts" allows DBRX to activate only a fraction of its parameters for any given query, greatly enhancing efficiency. Databricks also optimized the model for better hardware utilization, yielding 30-50% improvements in training speed and reducing inference latency, energy consumption, and ultimately cost.

For organizations looking to deploy AI while maintaining control over their data and models, DBRX presents a compelling option. Many of our security-minded clients have been hesitant to use closed models like GPT-4 or invest in the resource-intensive process of fine-tuning their own models from scratch. DBRX provides a powerful, efficient foundation that can be adapted to a wide range of domain-specific tasks without sacrificing data sovereignty. The fact that Databricks has openly shared details about the model's training process and architecture is also a major plus, as it allows for more informed risk assessments and trust in the technology.

That said, the more that models like DBRX are adapted, the greater the need for more robust AI security practices. At first, the rise of large language models presented new attack surfaces and risks with one or two commonly used and highly tested models. As organizations look more and more to adopt DBRX or similar Open Source models, the combinatorial possibilities increase substantially. Many AI application development projects are now designed to easily swap models as new and better options are available. While this is great news for efficiency and cost, it only adds to the complexity of the security framework to stay on top of datasets, models, pipelines, and use cases. Continuous testing, monitoring, and hardening of the AI pipeline must follow. Techniques like adversarial training, input validation, and runtime detection of anomalous model behavior will be key to realizing the benefits of these powerful tools while mitigating their risks.

Ultimately, the release of DBRX is great news for corporations and a testament to the incredible pace of progress in open source AI.

---

#### Name Squatting AI/ML Supply Chain Attacks

https://protectai.com/blog/unveiling-ai-supply-chain-attacks-on-hugging-face

TLDR: Don't download a model from Facebook AI. The company has renamed itself to Meta, and that model could be a fraud.

This is a growing threat to AI/ML supply chain attacks on public repositories like Hugging Face, where malicious actors use name squatting techniques to impersonate reputable organizations and distribute compromised models containing malicious code. This blog from Protect AI provides two examples of such attacks: the "alshaya/mobilenet" repository hosting a model that exfiltrates user data, and the "facebook-llama/custom-code" repository exploiting the trust_remote_code parameter to execute malicious code. The article emphasizes the importance of vigilance when using resources from public sources and recommends that organizations implement controls to screen for verified organizations and scan models before deploying them.

#### Enterprise adoption of Generative AI is Booming

https://a16z.com/generative-ai-enterprise-2024/

Great insights from this recent Andreessen Horowitz blog post about the ways that large businesses are embracing Generative AI technologies this year. Through 16 charts, they lay out the story of a massive up-tick in adoption within Fortune 500 companies:

1.      Budgets are increasing by at least 2x and more than 5x in some cases, with the estimated 2024 average budget of $18M

2.      Open source models (e.g. Llama, Mistral) are being widely adopted, with 46% of respondents preferring them because of their security and customizability advantages

3.      Focus has been largely on internal use cases such as productivity, customer support, and marketing

4.      Most enterprises are engineering architectures to be able to easily swap out foundational models if/when better options become available

All signs point to an accelerating trend of more models, across more use cases, and more need for a programmatic approach towards securing this expanding landscape.

#### ShadowRay: Attack Campaign on AI Workloads, Actively Exploited In The Wild

https://www.oligo.security/blog/shadowray-attack-ai-workloads-actively-exploited-in-the-wild

In a shocking discovery, the Oligo Security research team has uncovered an active attack campaign, dubbed ShadowRay, targeting a disputed vulnerability (CVE-2023-48022) in the widely-used open-source AI framework, Ray. Thousands of publicly exposed Ray servers across various sectors have been compromised over the past 7 months, allowing attackers to take over computing power, leak sensitive data, and install crypto miners. The vulnerability, which lacks authorization in Ray's Jobs API, has been actively exploited despite being tagged as "disputed" by Anyscale, making it difficult for organizations to detect using standard scanning tools. Oligo estimates the total value of the compromised infrastructure to be nearly a billion USD, based on the high-end GPUs used in many of the affected clusters. The research team has provided a list of IoCs and mitigation strategies, urging all organizations using Ray to review their environments for exposure and suspicious activity.

#### How To Securely Deploy AI on Google Cloud

https://cloud.google.com/transform/to-securely-build-ai-on-google-cloud-follow-these-best-practices-infographic

Google Cloud recently published a detailed guide on best practices for securely deploying AI on their platform. The report explores the shared responsibility model between Google and customers in securing AI workloads, emphasizing the crucial steps customers must take across key security domains like models, applications, infrastructure, and data. Practical guidance is provided on topics like prompt injection risks, data encryption, logging and monitoring, and more. Here is Google's best practices checklist:

![](../images\1711771156195)

#### MITRE Opens AI Assurance and Discovery Lab

https://www.mitre.org/news-insights/news-release/mitre-opens-new-ai-assurance-and-discovery-lab

MITRE recently opened its new AI Assurance and Discovery Lab dedicated to discovering and mitigating critical risks in AI systems operating in complex, high-stakes environments like national security, healthcare and transportation. MITRE will provide objective, independent analysis to help federal agencies and private companies safely implement advanced AI while establishing end-user confidence. An exciting development and sure to feed back into the continuing enhancement and utility of MITRE ATLAS (https://atlas.mitre.org/)

#### GitHub Copilot Adds Code Scanning Autofix

https://github.blog/2024-03-20-found-means-fixed-introducing-code-scanning-autofix-powered-by-github-copilot-and-codeql/

Many organizations and developers first encountered the power of Generative AI by using GitHub's Copilot, which provides automatic generation of code and a number of tools to help with development and testing. One of the chief concerns of using tools like copilot is the necessity to include a Large Language Model trained at some point in the past, meaning the latest vulnerabilities could be written by the model without it having any sense that this was a risk. This week, GitHub announced additional features that will allow vulnerabilities to be fixed inline with the same intuitive flow of working with code. Ultimately, tools like copilot will enable creation of more secure code and provide security teams relief from chasing low-level flaws while focusing on more complex and systematic threats.

#### Research on AI Agents

https://github.com/agiresearch/AIOS

AIOS is an interesting architecture out of Rutgers University that provides a reference embedding large language models (LLMs) into operating systems, creating an "OS with soul" and facilitating the development and deployment of LLM-based agents. The AIOS kernel includes several key modules, such as an agent scheduler, context manager, memory manager, storage manager, tool manager, and access manager, to address the diverse execution needs of agent applications. The LLM system call interface and AIOS SDK provide developers with the tools to harness the full potential of their agent applications within the AIOS framework. Experiments demonstrate the reliability and efficiency of AIOS modules in supporting concurrent execution of multiple agents.

AIOS lays the foundation for future research in refining and expanding the architecture to meet the evolving needs of developing and deploying LLM agents. It is also an important space to watch for the next round of advancements in AI products and services. Complex agent architectures promise many new capabilities (e.g. AI software engineer or LLM-driven robots) but they increase the surface area for vulnerabilities and other AI risks.

#### Research on Dangerous Capabilities within Frontier Models

https://arxiv.org/abs/2403.13793

Researchers evaluated Gemini 1.0 models for dangerous capabilities in four areas: persuasion and deception, cyber-security, self-proliferation, and self-reasoning. Research like this is helpful to identify categories of risk and effective detection and mitigation of them. Persuasion and deception capabilities appeared the most mature, with the agents demonstrating social competence, duplicity, persistence, proactivity, and the ability to construct arguments, though struggling with flexibility and humor.

In cyber-security, the models could solve basic capture-the-flag challenges and identify straightforward vulnerabilities, but failed at more complex, multi-step tasks. We’re safe for now! (just kidding, this model is not the fine-tuned, sophisticated model on the dark web. Those are much better at cyber attacks)

---

### Have a Great Weekend!

![](../images\1711771128152)

---

*You can chat with the newsletter archive at **https://chat.openai.com/g/g-IjiJNup7g-thinks-and-links-digest*