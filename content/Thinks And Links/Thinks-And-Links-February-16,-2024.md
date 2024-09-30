---
title: Thinks And Links February 16, 2024
draft: false
tags:
  - Big Data
  - Data Analytics
  - Cybersecurity
  - AI
  - Generative Video
  - OpenAI
  - AI Safety
  - Deepfake
  - Ethics in AI
  - Data Security
  - AI Innovation
---

# Thinks and Links | February 16, 2024

![](../images\1679742887729)

#### BD&A - Thinks and Links

Big Data & Analytics - Thinks and Links | News and insights at the intersection of cybersecurity, data, and AI

![](../https://media.licdn.com/mediaD4E12AQGVprUOvL_rBg)

_📫 **Subscribe to Thinks & Links** direct to your inbox_

### Happy Friday!

#### Seeing is not believing

Text to generative video is here. It has been here a while, to be honest. But it had it's ChatGPT moment yesterday when OpenAI announced Sora and began releasing demonstrations online. While existing generative video tools can take existing photos and animate them, Sora takes a text prompt and produces up to a minute of realistic video. Sora can create videos with highly accurate details, multiple characters, complex motion, and realistic backgrounds. It not only understands the context of the prompt, it delivers realistic physics for those things in the real world.

A few videos are worth far more than a thousand words on this topic:

![](../images\1708113759130)

![](../images\1708113811206)

![](../images\1708113859138)

This model is not yet public. OpenAI has begun permitting Red Team researchers to test the model for misinformation, hateful content, and bias. The eventual release of the AI product may come with limitations on the ability to create public figures or certain kinds of content. But we know from language models that these restrictions can only do so much. There are always ways to prompt generative models that can be used to generate a benign response that is useful for evil - e.g. ask ChatGPT to make a marketing email and then use for phishing. This also sets a new benchmark for Open Source models to aspire to, and likely similar capabilities will be available - unfiltered - by the end of the year.  Social engineering and causing false reputational damage continue to get easier and thus more wide-spread.

#### In Other Major AI Release News

Google

Released Gemini 1.5 and 1.5 Pro, offering significant improvements in efficiency and computational power. The new models enhance long-context understanding, handling up to 1 million tokens. That is nearly 10x what competitors OpenAI and Anthropic can provide. While it remains to be tested and proven if the 1 million token context window is truly effective, the potentials for even larger context means even greater power and use cases for the models. The models are currently only available in a limited preview for developers and enterprise customers through AI Studio and Vertex AI.

Gemini 1.5 Pro has been demonstrating advanced abilities in analyzing and summarizing extensive data, reasoning over multimodal inputs, and solving complex problems in large codebases. Its performance rivals the previous version, 1.0 Ultra, across many benchmarks, despite the reduced computational load.

Google is working on performing the rigorous ethics and safety testing to meet its AI Principles. They will likely continue to roll out Gemini 1.5 Pro to select users, with pricing tiers for different levels of service in the future.

####

ChatGPT

ChatGPT is testing a new memory feature, initially available to a small group of users. This feature allows ChatGPT to remember information you provide, improving its usefulness in future interactions. You have full control over this feature, with options to turn it off, delete specific memories, or clear all memories. The memory function is designed to enhance user experience by retaining details like preferences and personal information, which can be used to tailor responses in future conversations. However, it incorporates privacy and safety measures to prevent sensitive information from being remembered without explicit consent.

Team and Enterprise users will find memory beneficial for work-related tasks, as it can learn and adapt to specific needs and preferences, making interactions more efficient. Separate memory capabilities will be introduced for different GPT applications, requiring users to share relevant details across different platforms as needed.

---

#### NIST U.S. AI Safety Institute (USAISI) Launches

https://www.nist.gov/artificial-intelligence/artificial-intelligence-safety-institute

The U.S. AI Safety Institute (USAISI), established at the National Institute of Standards and Technology (NIST), spearheads efforts to ensure artificial intelligence (AI) safety and trustworthiness. Announced by U.S. Secretary of Commerce Gina Raimondo in February 2024, the USAISI, through its consortium of over 200 organizations, aims to develop science-based guidelines and standards. Its focus includes facilitating knowledge and data sharing, engaging in collaborative research, and advancing the measurement science of AI. This initiative is a critical move towards managing risks associated with the next generation of AI technologies, enhancing the United States' readiness in AI safety, and promoting secure, responsible AI deployment globally.

#### Disrupting Threat Actors Using AI

OpenAI Blog: https://openai.com/blog/disrupting-malicious-uses-of-ai-by-state-affiliated-threat-actors

Microsoft Technical Blog: https://www.microsoft.com/en-us/security/blog/2024/02/14/staying-ahead-of-threat-actors-in-the-age-of-ai/

OpenAI and Microsoft Threat Intelligence thwarted the malicious efforts of five state-affiliated cyber groups attempting to exploit AI for harmful cyber activities. Their partnership has led to significant disruptions in these groups' operations, specifically:

“

Charcoal Typhoon (China) used our services to research various companies and cybersecurity tools, debug code and generate scripts, and create content likely for use in phishing campaigns.

Salmon Typhoon (China) used our services to translate technical papers, retrieve publicly available information on multiple intelligence agencies and regional threat actors, assist with coding, and research common ways processes could be hidden on a system.

Crimson Sandstorm (Iran) used our services for scripting support related to app and web development, generating content likely for spear-phishing campaigns, and researching common ways malware could evade detection.

Emerald Sleet (North Korea) used our services to identify experts and organizations focused on defense issues in the Asia-Pacific region, understand publicly available vulnerabilities, help with basic scripting tasks, and draft content that could be used in phishing campaigns.

Forest Blizzard (Russia) used our services primarily for open-source research into satellite communication protocols and radar imaging technology, as well as for support with scripting tasks.

”

The approach includes monitoring, strategic partnerships within the AI ecosystem, iterative safety enhancements, and ongoing threat hunting. The Techniques, Tactics, and Procedures (TTPs) from MITRE ATT&CK and ATLAS include:

LLM-informed reconnaissance: Employing LLMs to gather actionable intelligence on technologies and potential vulnerabilities.

LLM-enhanced scripting techniques: Utilizing LLMs to generate or refine scripts that could be used in cyberattacks, or for basic scripting tasks such as programmatically identifying certain user events on a system and assistance with troubleshooting and understanding various web technologies.

LLM-aided development: Utilizing LLMs in the development lifecycle of tools and programs, including those with malicious intent, such as malware.

LLM-supported social engineering: Leveraging LLMs for assistance with translations and communication, likely to establish connections or manipulate targets.

LLM-assisted vulnerability research: Using LLMs to understand and identify potential vulnerabilities in software and systems, which could be targeted for exploitation.

LLM-optimized payload crafting: Using LLMs to assist in creating and refining payloads for deployment in cyberattacks.

LLM-enhanced anomaly detection evasion: Leveraging LLMs to develop methods that help malicious activities blend in with normal behavior or traffic to evade detection systems.

LLM-directed security feature bypass: Using LLMs to find ways to circumvent security features, such as two-factor authentication, CAPTCHA, or other access controls.

LLM-advised resource development: Using LLMs in tool development, tool modifications, and strategic operational planning.

#### Model Safety Wont Keep You Safe...

https://arxiv.org/abs/2310.20624

The study examines the effectiveness of safety training in AI, specifically by testing the robustness of Meta's Llama 2-Chat models against misuse. By applying a common fine-tuning method, researchers were able to significantly undermine the safety measures of the Llama-2 model with less than $200 and a single GPU. Despite this, the general performance of the models remained intact. The study underscores the potential risks associated with releasing model weights, as even well-guarded AI systems can be manipulated to bypass safety protocols. The findings suggest that risk assessments for AI models should include evaluations of vulnerabilities to fine-tuning methods.

#### ...But Models Should be Free

https://press.airstreet.com/p/the-case-for-open-source-ai

Open source innovation has massively accelerated software development and is a major factor in AI's rapid evolution. Yet, a looming cloud of regulation threatens to skew the playing field towards the old guard. This article makes the case for keeping AI Open because it is essential for nurturing research, fostering competitive landscapes, and ensuring our collective digital safety. True safety, continued innovation, and equitable technological advancement may mean accepting some of the risks that come with open source AI.

####

#### AI Security Pentest

https://wiki.hego.tech/ai-security/ai-security-pentest

This website has a great walk through of how a LLM pentest might be conducted. LLMs are increasingly integrated into various applications, posing new risks such as prompt injection. To mitigate these risks, organizations should identify and secure LLM data and API access points, enforce strict access controls, avoid exposing sensitive data, and conduct regular security assessments. This site shares recommendations on how to conduct these tests:

Identify the LLM's inputs, including both direct (such as a prompt) and indirect (such as training data) inputs.

Work out what data and APIs the LLM has access to.

Probe this new attack surface for vulnerabilities.

A few examples to probe include:

Chaining vulnerabilities in LLM APIs: Harmless APIs may expose LLMs to secondary vulnerabilities; map LLM API access for potential exploits.

Insecure output handling: Lack of validation or sanitization in LLM outputs can lead to vulnerabilities like XSS and CSRF.

Indirect prompt injection: Attacks can be direct (e.g., chatbot messages) or indirect (via training data or API outputs), often leading to unauthorized actions.

Training data poisoning: Compromised training data can mislead LLM responses, resulting from untrusted sources or overly broad datasets.

Leaking sensitive training data: Attackers might extract sensitive training data through crafted prompts, risking exposure of private information.

Relying solely on model-based restrictions is inadequate; a comprehensive approach encompassing system and data lifecycle security is crucial for robust defense against emerging LLM vulnerabilities.

####

#### Deepfaked video conference call costs company $25M

https://cybernews.com/news/deepfake-video-conference-call-hong-kong/

In a sophisticated fraud case in Hong Kong, scammers used deepfake technology to impersonate officials from a multinational company during a video conference, tricking an employee into transferring $25 million to fraudulent accounts. Initially skeptical, the employee was convinced after recognizing the digital replicas of his colleagues. The fraud was discovered only after he confirmed the transactions with the company's head office. This incident is part of a rising trend where deepfake technology is used for financial scams and non-consensual explicit content, prompting legislative responses such as the DEFIANCE Act in the US to combat this issue.

####

#### Embracing the Future of AI with Varonis (and Optiv)

https://www.optiv.com/insights/discover/blog/embracing-future-ai-varonis

The blog post by Optiv’s Partner Architect for Varonis Jeremy Bieber highlights the partnership between Varonis and Microsoft to ensure secure deployment of Microsoft Copilot for Microsoft 365, leveraging Varonis enhanced security measures and compliance frameworks. It introduces Athena AI, a significant innovation within the Varonis Data Security Platform, designed to streamline cybersecurity processes through advanced features like AI SOC Analyst and Natural Language Search. Together, these developments offer a comprehensive approach to enhancing organizational productivity and security in the AI landscape, with Optiv serving as a guiding partner for navigating these technological advancements.

#### AI Training Resources

Here are a few free AI certifications. Want to level-up your AI Skills in 2024? Check out:

AI for everyone - Deep Learning https://www.coursera.org/learn/ai-for-everyone

Introduction to generative AI - Google https://www.coursera.org/learn/introduction-to-generative-ai

Machine Learning Specialization - Stanford https://www.coursera.org/specializations/machine-learning-introduction

AI for business specialization - Penn University https://www.coursera.org/specializations/ai-for-business-wharton

AI, Business & the Future of Work - Lund University https://www.coursera.org/learn/ai-business-future-of-work

Introduction to prompt engineering - LinkedIn https://www.linkedin.com/learning/introduction-to-prompt-engineering-for-generative-ai/joining-the-nlp-revolution

---

### Have a Great Weekend!

![](../images\1708114046750)

####
