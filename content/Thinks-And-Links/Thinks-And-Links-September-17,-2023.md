---
title: Thinks And Links September 17, 2023
draft: false
tags:
- Big Data
- Data Analytics
- AI
- Generative AI
- Cybersecurity
- AI Security
- AI and Privacy
- AI Models
---

# Big Data & Analytics - Thinks and Links | September 17, 2023

![](../images\1679742887729)

#### BD&A - Thinks and Links

Big Data & Analytics - Thinks and Links | News and insights at the intersection of cybersecurity, data, and AI

![](../https://media.licdn.com/mediaD4E12AQFYMCxF4onMOA)

### Happy Weekend!

I recently had the opportunity to try out the self-driving features of a Tesla. Without removing my hands from the wheel or foot from the pedal I experienced what letting AI take charge might be like. It could navigate highways and side roads. Full speed and bumper to bumper traffic. Twists, turns, sudden cut-offs, and changing signals. It was pretty impressive, but also lacking. For one thing, I didn’t trust it. Sometimes it would speed up or slow down in ways that are different from my instincts. I wanted to ask it “you see that merging tractor trailor up ahead, right?” Or wouldn’t it be great to discuss if we take the fastest route or the one with more options to stop for coffee?

Large Language Models (of course) are coming to this domain. I found this research blog by Wayve to be an eye opener: LINGO-1: Exploring Natural Language for Autonomous Driving. The researchers shared how including reasoning from an LLM to the AI stack had the following impacts:

Interpret road and traffic conditions

Explain AI model decisions

Create more robust training data for other AI models

The blog introduces LINGO-1, which was trained on the video and sensor inputs of Wayve cars along with spoken commentary by human drivers. The model is built to respond to questions that can explain reasoning and decisions behind actions the autonomous vehicle would make. It can then provide a continuous commentary throughout the drive:

![](../images\1694977773845)

The integration of language into existing AI models is an exciting development and one which will apply to more than just self-driving cars. Regulation, lawsuits, and general social concern about AI is largely centered around the lack of transparency involved with “black box” deep learning models. AI that can both explain itself and incorporate feedback is likely to be a requirement for any “high risk” use cases. Language can also increase the rate of training AI models by providing specific instructions. Instead of feeding a self-driving car model thousands of videos of slowing down at a crosswalk with a person in it, researchers can teach it the logic of what to do with a sentence.

This example is one more reason to be unreasonably excited about AI this year. ChatGPT was cool and Microsoft Copilots will likely help automate many tasks, but the real transformation is just getting started. Human-level language models that are either trained (like Wayve) or built into products are going to transform what we thought was possible with AI. As a life-long Star Trek fan, I’m looking forward to being able to truly ask my computer to lay in a course and engage.

Four Steps to Prepare Enterprises for Generative AI

https://www.securitymagazine.com/articles/99884-generative-ai-in-the-enterprise-4-steps-to-prepare-organizations

If you accept that Generative AI in the workplace is a matter of when and not if, then there’s several things you may want to work on in parallel. Organizations will move at different paces to adopt this technology in different ways, but regardless of pace and approach the following are useful investments in effort:

Data liquidity – This is the first time I’ve seen this term used, but it’s a measure of how easy can data flow through the organization. I’d caveat that to be *Useful* Data Liquidity which would be data that is appropriately access controlled, governed, and of high quality. Data being essential for everything in the business – bad data = bad outcomes. Bad data in AI = fast and bad outcomes.

Multi-Cloud – The argument being that different business units and model needs may be best served by different cloud providers. The author recommends building the capability to scale up and down, have options for failover, and select the best cost solution.

Citizen Development – Support employees who want to experiment with these capabilities and enable low-code / no-code solutions for certain use cases. While demand for AI technical talent currently outpaces supply this can be a path to build up capacity and solve for some low risk use cases. I would add to beware of “Shadow AI” at your organization which can be as hazardous as “Shadow IT” – so give tools that provide a pathway to monitoring and enterprise controls.

Improve Processes – If you automate a dumb process, you’ll just do dumb things faster. Natural Language Processing models such as LLMs provide a lot of great options to automate parts of operational and support processes. Organizations can focus on how to automate the right processes to find value.

Do CFO’s Not Care About AI?

If you only read the headline of this article, you might think that’s the case. The nuance in the actual CFO survey from Deloitte is actually quite different. CFO’s are rightly concerned that many of their organizations do not have sufficient talent to safely and cost-effectively take advantage of new AI capabilities. However the survey also reports that 42% of organizations surveyed are experimenting with generative AI. 15% are incorporating it into their business strategy. Many CFOs are looking for use cases and comprehensive accountings of costs, benefits, and returns before going all-in on generative AI.

Most striking: 57% of CFOs said their top concern with Generative AI is the impact to risk and internal controls. This justifiable concern is a key barrier to adoption and a reason why Secure AI is a focus at Optiv.

AI RMF Does Not Address Common Needs

https://aivillage.org/ai%20security/airmf-response/

This article is about a year old, but I found it to be very insightful in the discussion of “small” AI/ML models. While the NIST AI Risk Management Framework provides excellent guidance to organizations about how to design, deploy, and manage AI, this critique adds a few more suggestions that would be helpful to add. In particular, most machine learning models are being regularly retrained and updated based on changing data. The AI RMF does not address model, concept, or data drift in a significant fashion – and these are the biggest foes of most organizational AI/ML. The article also points out that recommendations about training security in a model directly can impact its accuracy.

Critiques like this are useful to build a holistic picture of AI Security. It is very likely that future versions of the NIST AI RMF will include these concepts:

*GOVERN should include suggest org establish minium response times for model issues.*

*MAP should explicitly call out the drift issue and suggest that the org have minimum performance requirements.*

*MEASURE should explicitly require continuous monitoring of performance. Orgs will do one off performance evaluations as continuous monitoring can be expensive.*

*MANAGE should include a suggestion for a scheduled model lifecycle, or performance based triggered redeployments.*

Protect Your Business from AI Cyberthreats

https://www.forbes.com/sites/forbestechcouncil/2023/09/13/ai-models-under-attack-protecting-your-business-from-ai-cyberthreats/?sh=16e7882e1cb5

This article has a nice walk-through of the MITRE ATLAS security framework which documents potential attack vectors and mitigations for AI and ML models. This includes top attack methods such as:

Data Poisoning – injecting malicious data to be used by AI models for incorrect or disruptive outputs

Evasion Attacks – Circumvent security that uses AI by exploiting known attack techniques

Model Theft – Capture the source code or weights of the AI model to assist in an attack or use “model inversion” to retrieve the sensitive or private data which was used to train the model

Supply Chain Compromise – Infiltrating the source code, datasets, or accessing the accounts of people involved in model development and maintenance

Backdoor AI Model – Replace a model with one that is nearly identical except for allowing certain inputs to cause undesired outputs – e.g. making a weapon detection system not alert on a specific type of weapon

The article (and ATLAS) also provide mitigations for these kinds of attacks:

Adversarial Training – Include examples in the training data of what bad guys might try, to teach the model how to handle these edge cases

Secure Virtual Repositories – Models and their data are “crown jewel” type information, and access should be severely restricted, encrypted, and models can be cryptographically watermarked.

Train Employees – About AI, attackers using AI, and how to follow corporate AI policies

Mask Your AI Model – Use techniques such as “model obfuscation” to hide information that would enable an attacker to know precisely how to attack

Use Multilayered Threat Detection – There are multiple cybersecurity tools which can apply to secure models including Intrusion Prevention and Detection Systems (IDS) and anomaly detection tools. (I’d also add that the way you build your model can be multi-layered and security-aware)

Embed Security and Privacy – Keep security and privacy baked in to AI models by default. Secure coding practices, encrypted data, frequent audits, and continuous monitoring are all important for keeping AI models secure

Nerdy Nostalgia – The Unreasonable Effectiveness of RNNs

http://karpathy.github.io/2015/05/21/rnn-effectiveness/

This article from 2015 is an excellent primer to Recurrent Nueral Networks, the architecture behind much of today’s Generative AI hype. Even then, they were showing incredible promise. As you work through the examples and referenced code you can get an understanding of how they work and why they’re “unreasonably effective”

Have a Great Weekend!

![](../images\1694987442167)

*This is important for when we’re all talking to our computers like in Star Trek*