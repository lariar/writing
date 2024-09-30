---
title: Thinks And Links May 17, 2024
draft: false
tags:
- AI
- Cybersecurity
- Data Analytics
- Big Data
- OpenAI
- Machine Learning
- AI Security
- AI Adoption
---

# Thinks and Links | May 17, 2024

![](../images\1679742887729)

#### BD&A - Thinks and Links

Big Data & Analytics - Thinks and Links | News and insights at the intersection of cybersecurity, data, and AI

![](../https://media.licdn.com/mediaD4E12AQE8Idn1p10euA)

📫 Subscribe to Thinks & Links direct to your inbox

### Happy Friday!

It's been a very busy week for news in AI and Security. OpenAI and Google both announced a host of new AI capabilities. Not to be outdone, Exabeam + LogRythm and Palo Alto + IBM upended the SIEM market. There's a lot to unpack:

#### OpenAI: GPT-4o, Screen Capture, and Her

OpenAI launched its newest model on Monday, optimized for speed. The video demonstrations show what is possible with a model that can process inputs significantly faster while also maintaining the high quality we’ve come to expect of the GPT-4 class models. Combining speed with quality yields an experience that many are comparing the fictional AI from the movie “Her.” In one example, ChatGPT’s mobile app coaches the presenter through the process of solving a math equation by using the video interface. At each step the AI provides hints that helps the human learn the material like a personalized tutor. In another demonstration, the new ChatGPT desktop app is granted permission to view the users desktop to provide an explanation of code and analysis of the charts produced by it.

High speed interaction with AI is a new model of interaction that we’ve barely scratched the surface on. Voice assistants like Siri and Alexa have provided some hints of what could be possible, but mostly these have been relegated to providing a hands-free way to send a text message or set a kitchen timer. Engaging with an AI tool has been "turn based” up until now. Send a question, wait, get a response. With GPT-4o it shifts to a dialogue. You can interrupt it. It can process more context about your task and ways for it to be helpful. It’s going to ultimately make AI tools better and more “human.”

This is the starting gun of the next phase of the AI races. Within the next 2-3 years we’ll see an explosion in this kind of capability just as we’ve seen with the Chatbot model that started to accelerate two years ago. Multimodal, real-time AI agents are coming very soon to a software solution near you. The security implications are astounding; Tools that can read desktops or have a running dialogue with your employees are certain to leak IP and company secrets. As open source solutions rush to compete with GPT-4o any number of compromised solutions will social engineer users into running insecure code. With OpenAI also making GPT-4o available for free, consumers will get to experience this capability and expect a more real-time AI experience.

#### Google I/O: AI, AI, AI

This year's Google I/O provided introduction to the upcoming tools and features of the company's suite of tools, and many many AI updates. The big announcement of Gemini's context window shifting to 2 million tokens is under-hyped. 2 million tokens is 40 50,000 page books. Or that's 16+ hours of video. (Easily double that with some light pre-processing). The possibilities to build solutions that work with that context are astounding. So too are the security considerations. If you can easily build a powerful model that knows your business by uploading all your documents, should you? And if you sent in a directory of "stuff" do you know what's in that stuff and should it go to google? We know in security the answer is "heck no!" but controls and mitigations are lagging. Good luck to the security team that tries to block google.com

Google also demonstrated AI features that are coming soon such as real-time video interactions and intelligent agents. The real time videos were similar to OpenAI, worth watching for more insights into what people are going to be doing with these tools. The intelligent agents are exciting, but not yet available. They appear to function similarly to Microsoft Co-pilot with a bit more autonomy. They'll have their own identity and access to whichever things you grant them, much like a human would. When the feature launches, it'll be very interested to test and see how secure it is.

#### SIEM City

Much has been written about this elsewhere and much is still unknown but as of today, Friday morning: Exabeam and LogRhythm are merging and Palo Alto is Buying IBM's QRadar assets. We're watching closely to see how this shakes out: what happens to the various tools we've supported for a long time, and how it might impact recommendations to our clients. There's never been a better time to invite your clients to a SIEM Summit to discuss this market and strategic steps to take (regardless of SIEM) to mature your SOC.

#### 

---

#### AI Aided Red Team Steals Sensitive IP in 8 Hours

https://www.theregister.com/2024/05/13/ai_xforce_red_penetration/

IBM's "X-Force" penetration testers were able to achieve the objective of stealing sensitive computer hardware information from one of the world's leading manufacturers by using custom AI tools to quickly breach and infiltrate their customers' network. While the name of the manufacturer hasn't been disclosed, the results of the exercise - scoped to take three weeks - demonstrates the impressive capabilities Generative AI tools can bring to attackers. While many pen testing tools bring automation, the killer-app - according to X-Force - was the data analytics capability of generative models. Previous iterations of this exercise involved significant data analysis over large amounts of information to identify the best path in. With AI the "dots are closer together" for the human team to find and exploit their way in. Worth noting - all experts agree that "within two years, the models will be ten-times more powerful than they are today." And much more widely available for real attackers.

See also: https://www.bloomberg.com/news/articles/2024-05-07/microsoft-creates-top-secret-generative-ai-service-for-us-spies

#### AI Security 101 from MITRE ATLAS

https://atlas.mitre.org/resources/ai-security-101

ATLAS has been tracking AI/ML security since before it was hyped. They're the real deal for understanding how these tools might be attacked in your environment and what you can do about it. I really liked the framing and the visual from this article:

AI Access Time: Attackers may focus on training an AI model or the inference (aka running it)

AI Access Points: Techniques include Digital (e.g. at an API) or Physical (e.g. sending in specific inputs)

System Knowledge: How much could the adversary know about the components of the system. White box involves open source models with full information about the training data, architecture, and weights or black box where none of that is known, but can still be manipulated through various techniques.

![](../images\1715954663619)

This framing helps defenders understand the many tactics and techniques of MITRE ATLAS and ways to mitigate them. The article continues to share good background on the CRISP-ML(Q) methodology for Machine Learning Operations. ATLAS has aligned mitigations against the various attacks at stages of the CRISP-ML(Q) to help align AI teams with Security to work together for safer AI implementations.

![](../images\1715954709909)

As an example: ATLAS Mitigation M0004 is Restrict Number of ML Model Queries. This can mitigate several techniques at Inference time such as Discovering Model Ontology and Cost Harvesting. It can be mitigated during Business & Data Understanding (setting realistic metrics for expected volume), Model Development (configuring the inference tooling to block or throttle excessive queries), and as a part of ongoing Monitoring and Maintenance.

Many additional examples and great links to MITRE content here for tactical steps to secure AI (and ML!)

#### 2024 is the Year AI Gets to Work

https://www.microsoft.com/en-us/worklab/work-trend-index/ai-at-work-is-here-now-comes-the-hard-part

*Written by Claude 3 Opus provided examples of my past writing + the report PDF*

Microsoft and LinkedIn just released their 2024 Work Trend Index Annual Report and the findings are sure to get your clients thinking. The major theme? AI at work has arrived, and while employees are excited to use it, organizations are struggling to keep up.

Here are the key takeaways:

AI adoption is surging: 75% of knowledge workers already use AI at work, with nearly half starting in the last six months alone. Users say AI helps them save time (90%), be more creative (84%), and enjoy work more (83%).

Employees are taking things into their own hands: 78% are bringing their own AI to work, and over half are reluctant to admit using it for important tasks for fear of looking replaceable. This exposes organizations to new risks.

Hiring may shift to prioritize AI aptitude: 66% of leaders say they wouldn't hire someone without AI skills and 71% prefer less experienced candidates with AI skills over experienced ones without.

AI power users are reshaping work: By experimenting with AI and developing new habits, power users are seeing outsized benefits and providing a window into the future of work.

The opportunity for leaders is clear: Channel employee enthusiasm into a thoughtful strategy to apply AI for business transformation. This will look different for every organization, but key priorities include:

Identifying high-value processes to automate with AI

Enlisting leaders at all levels to champion AI

Prioritizing ongoing training, both universal and role-specific

The data signals we've reached a pivotal moment for AI at work. Those who move quickly and strategically to embrace it could surge ahead. But it will take bold leadership to navigate this disruption and turn early experiments into tangible results.

#### Introducing Google Threat Intelligence

https://cloud.google.com/blog/products/identity-security/introducing-google-threat-intelligence-actionable-threat-intelligence-at-google-scale-at-rsa/

*Written by Google Gemini Advanced provided examples of my past writing + the link + a few back-and-forth instructions to tweak it*

Google's latest offering, Google Threat Intelligence, is making waves in the security world. Promising a "Google-scale" approach to threat intelligence, it's aggregating data from Mandiant, VirusTotal, and a vast array of open-source intel. This could be a game-changer, providing a comprehensive, real-time view of the threat landscape that was previously unattainable.

One standout feature is Gemini, an AI-powered agent designed to analyze code and root out vulnerabilities. Google claims Gemini can identify threats with unprecedented speed and accuracy. Could this finally be the AI-powered security solution we've been dreaming of?

The potential benefits are tantalizing: improved threat detection, faster incident response, and a significant reduction in breach risk. Imagine being able to proactively identify and mitigate threats before they wreak havoc on your systems.

#### OpenAI's Model Spec

https://openai.com/index/introducing-the-model-spec/

Some very important decisions are being made about AI models at all levels of society, from government, to businesses, to individuals. OpenAI's new Model Spec is a frame of reference to describe what models do so that we can have more aligned conversations about what they should do. Worth keeping track of.

#### Lakera PINT Benchmark

https://www.lakera.ai/blog/lakera-pint-benchmark

Lakera's Prompt Injection Test (PINT) Benchmark is a new evaluation tool for testing prompt injection protection solutions. It uses a comprehensive dataset of 3,007 English inputs, including public and proprietary attack techniques, to measure the effectiveness of detecting true positives and minimizing false negatives. The benchmark includes categories like public and internal prompt injections, jailbreak directives, hard negatives, chat inputs, and documents. The evaluation tools are publicly available for researchers and developers to contribute and improve prompt injection defenses.

---

### Have a Great Weekend!

![](../images\1715954726513)

---

*You can chat with the newsletter archive at **https://chat.openai.com/g/g-IjiJNup7g-thinks-and-links-digest*