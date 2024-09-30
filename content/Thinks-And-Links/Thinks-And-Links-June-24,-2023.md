---
title: Thinks And Links June 24, 2023
draft: false
tags:
- Big Data
- Data Analytics
- AI Regulation
- Cybersecurity
- Data Governance
- AI Governance
- AI Risk Management
---

# Big Data & Analytics - Thinks and Links | June 24, 2023

![](../images\1679742887729)

#### BD&A - Thinks and Links

Big Data & Analytics - Thinks and Links | News and insights at the intersection of cybersecurity, data, and AI

![](../https://media.licdn.com/mediaD4E12AQFkSl5BLtMtsg)

### Happy Weekend!

What is the state of regulation in AI and why does it matter?

We’ve been talking a lot with clients about the importance of taking a holistic approach to AI that includes security and governance. During the conversations we’re often asked about the upcoming EU laws or the various regulations in US states. AI Regulation is patchy and will likely be that way for a very long time. There’s several reasons for this, but more importantly what should our clients do? What matters and what is noise in the AI regulatory space?

First, there are conflicting casual and regulatory definitions of AI. We are talking about something that is larger than ChatGPT but less than your entire digital transformation. Artificial intelligence can be defined as anything that enables a computer to make decisions based on data rather than based on code. Loosely worded regulation could therefore have very far-reaching implications. More likely than not, AI regulation will focus on automations that can lead to harmful outcomes as a priority. The EU draft AI regulation goes far enough to define the types of automation that will be in scope for its mandates as “high risk AI:”

This time next year businesses with a European footprint will likely be the process of registering AI with the EU and/or building the justification for why their AI systems should be exempt. Regardless, there will be a massive effort to understand where AI exists in the business and to ensure it is properly secured.

Those of us who don’t have a European footprint or who don’t work in these “high-risk” domains as defined by the state are not off the hook. Rather than argue the nuances, the approach is of great value here. Understanding where AI exists in your business is important regardless of which regulator you need to inform. AI – like software and infrastructure – has strengths, weaknesses, vulnerabilities, and lifecycles. Understanding your AI footprint is going to be critical to managing vulnerability, not just from hackers but from poorly functioning AI models!

If you or your clients are planning to go to the Databricks Data and AI Summit next week, please check out this talk by Optiv’s Alex Vanadio. He will be sharing his recent experiences with a very large retail client where he helped them process petabytes of data at a time. A key concept he has to deal with (and is relevant in this week’s rant) is the concept of Drift.

Things change. In Alex’s project it was the structure of the data which the security environment was sending in to the SIEM. In other projects it could be the data that models use to make their predictions and trigger their automations. It is pretty much a law of data physics that data drifts over time, and AI models need to plan for it. "You can't manage what you can't measure." Drift happens, models lose effectiveness, and fancy automation that was built during the AI Hype days of 2023 may cause AI Grief in 2024.

Regulator or not, AI Governance is a good idea. More (much more) coming as a formalized service brief soon. Please reach out any time to discuss regulation, governance, strategy, and drift.

PS – If you’re in San Francisco next week please join us at Optiv’s AI roundtable dinner. We’ll recap some of the biggest stories from this newsletter as well as going deeper into the topic of AI, Large Language Models, ChatGPT, GPT-4, Google Bard, Security’s role in AI, and approaches for building an offensive & defensive Data and AI strategy.

Register here if you can make it.

---

The Databricks Lakehouse Platform for Cybersecurity Applications

https://www.databricks.com/blog/databricks-lakehouse-platform-cybersecurity-applications

The Databricks Lakehouse can do many things, including cybersecurity. Many companies are looking at consolidating tools or leveraging the skillsets they’ve built in one line of business to support others. That’s where a cloud-agnostic and Data and AI platform can end up being used to accelerate adoption, reduce cost, and comply with data regulations.

Optiv is a partner to Databricks as they roll out their ecosystem for cybersecurity. We can support and integrate with partners for AI/ML protection, graph visualization and analytics, full-text search, data ingestion, governance and security, and threat intelligence feeds. I’m very excited for the official announcements around Security at the Data and AI Summit next week. If you or a client will be around lets meet up!

How to Avoid Shadow AI in your SOC

https://www.helpnetsecurity.com/2023/05/24/generative-ai-tools-risk/

Great article from Devo (another Big Data & Analytics partner) CTO Gunter Ollmann about one risk that AI poses – enhanced shadow IT capabilities. As someone who can code… somewhat… my skills dramatically increased when I started using ChatGPT. If I wanted to build little bots and tools to help myself out at work – I could do this much easier. And I would do this terribly, exposing myself and my firm to all sort of risk. AutoGPT sounds neat – let’s build a bot that checks SharePoint once a minute for new updates and then send them out to OpenAI for embedding. Is that bad?

Yes. That is bad. Don’t do this. Ollmann writes that its important to update your policies to cover new AI tools and then provide training and guardrails for responsible AI adoption.

Oops

https://thehackernews.com/2023/06/over-100000-stolen-chatgpt-account.html

This story earned an immediate inclusion in the timeline of AI in 2023 slide of our Executive Briefing. It is not really about AI. Account credentials are stolen all the time. But the scary part of 2023’s AI hype is the speed with which people have adopted a new tool with very little thought behind what could happen to their data. There are now 100K ChatGPT accounts which can be accessed and reviewed for chat history. This helps attackers of individuals and companies get valuable intelligence.

Also, to be clear, OpenAI and ChatGPT weren’t breached. This was instead done by commodity malware. OpenAI’s response: “We are currently investigating the accounts that have been exposed. OpenAI maintains industry best practices for authenticating and authorizing users to services including ChatGPT, and we encourage our users to use strong passwords and install only verified and trusted software to personal computers.”

Why Chief Data and AI Officers Are Set Up To Fail

https://hbr.org/2023/06/why-chief-data-and-ai-officers-are-set-up-to-fail

Chief Data and AI Officers often struggle due to a misalignment in focus on technology rather than business outcomes, lack of trust from business leaders, and difficulty in demonstrating the value of data initiatives. As a result, CDAIOs face challenges in driving data-driven culture and delivering business value from their investments. This can lead to job failure, as they cannot effectively showcase their contributions to the organization.

The same could be true of Cyber leaders. We have a lot to learn from each other.

Fun Fact – Cyber Metrics is designed to “Measure What Matters” first and foremost. Building dashboards and ML/AI depend on understanding use cases and driving business outcomes before, during, and after deploying technology

The International Association of Privacy Professionals (IAPP) Releases their AI Governance Professional Body of Knowledge

Press release: https://iapp.org/news/a/iapp-releases-ai-governance-professional-body-of-knowledge/

Document: https://iapp.org/media/pdf/certification/AIGP_BOK_1.0.0.pdf

This is the authority for Privacy Professionals and an alignment that we’re seeing across the board when we speak to clients about AI. It is focused around the following “competencies” which are all great topics for future newsletters:

Domain 1: ″Understanding the Foundations of Artificial Intelligence″

Domain 2: ″Understanding AI Impacts and Responsible AI Principles″

Domain 3: ″Understanding How Current Laws Apply to AI Systems″

Domain 4: ″Understanding the Existing and Emerging AI Laws and Standards″

Domain 5: ″Understanding the AI Development Life Cycle″

Domain 6: ″Implementing Responsible AI Governance and Risk Management″

Domain 7: ″Contemplating Ongoing Issues and Concerns″

You can expect to see certified Optiv practitioners as soon as official certification becomes available!

Stories Like This Excite Investors, Worry Risk Professionals

https://www.businessinsider.com/ai-work-automation-octopus-energy-greg-jackson-2023-5

This is about a month old, so everything could have changed since then. But according to this report:

The value to shareholders is real – greater customer satisfaction, decreased cost, etc. That is the fuel in the engine causing so much focus on this technology. It’s good to keep the prize in mind.

More Regulation Resources

https://www.technologyreview.com/2023/05/22/1073482/our-quick-guide-to-the-6-ways-we-can-regulate-ai/

I’ve been spending a lot of time lately with the links embedded here trying to keep up with AI Regulation efforts. While there’s a little bit of motion in the US Government, the real developments are happening overseas and within industry standards groups. A rabbit hole to go down for Data and Policy nerds alike. Strongly recommend clicking down into https://oecd.ai/en/ where you’ll get even more links to amazing resources and thought-provoking writing.

### Have a Great Weekend!

![No alt text provided for this image](../images\1687567804488)