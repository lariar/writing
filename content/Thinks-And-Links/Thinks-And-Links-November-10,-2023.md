---
title: Thinks And Links November 10, 2023
draft: false
tags:
  - Big Data
  - Data Analytics
  - Cybersecurity
  - AI
  - OpenAI
  - Generative AI
  - ChatGPT
  - AI Development
  - AI Safety
  - AI Security
---

# Thinks and Links | November 10, 2023

![](../images\1679742887729)

#### BD&A - Thinks and Links

Big Data & Analytics - Thinks and Links | News and insights at the intersection of cybersecurity, data, and AI

![](../https://media.licdn.com/mediaD4E12AQHKwGnCxIeNJw)

### Happy Veterans Day!

Thank you to all who served and continue to serve.

#### Big AI Developments in DC and SF

Last week in DC the Biden Administrated put forth its 19,700+ word Executive Order on AI. It is a very large executive order, and it covers a wide range of topics and executive branch directives to shape Americas agenda on AI. There is lots of coverage available (including a few quotes from yours truly), so I took some time to read it and think about how to provide a unique angle on it here.

This week in San Francisco, OpenAI held their DevDay event. We are approaching the one year anniversary of ChatGPT, a small experiment they shared without any expectation of virality back then. This week, the features they introduced have made the original ChatGPT look quaint, and we will see how they push the boundary of what we can do with Generative AI into the next year. These will also further democratize access to these capabilities: For developers, OpenAI has created an “Assistants API” which allows applications to call on customized AI Agents who can search the web, write, and execute code, make third party API calls, and access stored knowledge. But agents are no longer just for those who code.

I think the biggest announcement for most people this week will be the launch of Custom GPTs. They are a ChatGPT-like interface that provides the functionality of the Assistants API. The GPTs can be created entirely through conversation. A chatbot to build a chatbot. No code needed. But they can do everything the Assistants API can offer, which means they can search knowledge stores, run functions, and provide incredible variety in their utility.

How better to share in the excitement of the last two week’s announcements than to AI to explore the AI Executive Order; in three versions that represent the journey AI tools have been on…

Version 1 – Open Source Agent Tooling

Example: https://ai-executive-order.streamlit.app/

Steps to Build

Convert the text of the Executive Order into chunks of text

Run each chunk through an embedding model that compresses the information into a format ideal for working with LLMs

Store the data in a vector database

Create an agent with multiple prompts that can use the vector database to answer questions about the EO

Tinker and modify several different prompts to be sure it works well

Time spent ~ 3 hours\*

![](../images\1699673694800)

Version 2 – OpenAI Assistant API

Example: https://ai-executive-order.streamlit.app/

Steps to Build

Create an assistant with a single API call or through the website GUI, and upload the same text file of the Executive Order on AI

Write some code to interact with the assistant and show an interface

Assistant automatically comes with code execution and web search without any further coding needed

Time Spent ~1 hour

![](../images\1699673729752)

Version 3 – AI Executive Order Advisor GPT

Example: https://chat.openai.com/g/g-4WswVd1pX-ai-executive-order-advisor (Requires ChatGPT Plus Account)

Create a custom GPT on ChatGPT. Chat with it to design functionality, create a logo, and upload my document.

Time spent ~5 minutes

![](../images\1699673807136)

The future is wild and it’s here now. Anyone can be an AI developer. It is easier than ever to share data and information with AI and get useful results. The function calling capability will also quickly link these agents to a lot of other services. Which means that there will be security concerns that look something like this:

![](../images\1699673941388)

If the file you used to create the agent can’t be public – don’t put it in a public GPT!

GPTs can be configured for limited individual or organization access, but security is often an afterthought when new tools like this come out. Be responsible with what agents you create and share data with. You really should try this out. You might find that it is very easy to create something like…

OptivGPT

https://chat.openai.com/g/g-sYx3iu1N2-optivgpt

This is an experimental GPT that uses only public information from www.optiv.com – try it out and share your feedback!

![](../images\1699673991110)

---

Three Ways AI Chatbots are a Security Disaster

https://www.technologyreview.com/2023/04/03/1070893/three-ways-ai-chatbots-are-a-security-disaster/

This article from earlier in the year is a helpful reminder now that AI chatbots have gotten even easier to deploy. Think about ways adversaries of all shapes could take advantage of your new GPT or Assistant-API tool. Certainly anything involving non-public data or critical business actions needs careful and ongoing scrutiny due to the three items from the article: Jailbreaking, Assisting scamming and phishing, & Data poisoning.

There was also an AI Safety Summit in the UK

https://www.gov.uk/government/publications/ai-safety-summit-2023-the-bletchley-declaration/the-bletchley-declaration-by-countries-attending-the-ai-safety-summit-1-2-november-2023

The Bletchley Declaration was issued from the AI Safety Summit hosted in Bletchley Park in England (where Alan Turing famously had his workshop for early computers). The declaration affirmed a common desire to capture the benefits of AI while working to mitigate the risks. I did not take the time to build a chatbot for this one, so the link above will have to suffice.

Microsoft 365 Copilot is now Generally Available

https://techcommunity.microsoft.com/t5/microsoft-365-copilot/microsoft-365-copilot-is-generally-available/ba-p/3969331

AI assistants are embedded in Microsoft 365 for any who want them as long as they pay for the feature and have at least 300 seats. This limitation excludes many small and medium-sized businesses who would benefit from AI, but is likely only temporary.

GitHub is Going All-In on AI

https://github.blog/2023-11-08-universe-2023-copilot-transforms-github-into-the-ai-powered-developer-platform/?utm_source=bensbites&utm_medium=newsletter&utm_campaign=daily-digest-most-successful-ai-product

“Just as GitHub was founded on Git, today we are re-founded on Copilot.” It will soon be uncommon for developers to write code without some form of generative AI assistance.

More Coverage of the OpenAI DevDay Announcements

https://www.linkedin.com/events/generativeaiunleashed-exploring7127397616048365568/theater/

You can hear the excitement as John Petty, James Hilbert, and myself unpack what was announced after Sam Altman's Keynote on Monday.

OpenAI Had a DDOS

https://www.securityweek.com/major-chatgpt-outage-caused-by-ddos-attack/

There were a few hours on Tuesday and Wednesday where the OpenAI APIs and ChatGPT were not working well. It turns out that this was a targeted attack by the hacker group “Anonymous Sudan.”  While an inconvenience, the attack does not seem to have impacted anything important and everything is back to normal as of today.

---

### Have a Great Weekend!

OpenAI’s Security Team Had Some Fun with Hackers:

True story from the engineering challenges of scaling at OpenAI: When hackers were starting to reverse-engineer the APIs and take actions with higher privileges than they should, the team gave them a customized version of the model which would answer queries in the voice of a cat. The security team had also been monitoring the hackers for some time and were able to watch in their discord and telegram channels as confusion set in.

![](../images\1699674042473)
