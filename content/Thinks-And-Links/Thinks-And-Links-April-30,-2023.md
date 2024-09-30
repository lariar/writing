---
title: Thinks And Links April 30, 2023
draft: false
tags:
  - Big Data
  - Data Analytics
  - Cybersecurity
  - AI
  - Large Language Models
  - ChatGPT
  - Data Privacy
  - AI Regulation
  - Google
  - OpenAI
  - Microsoft
  - AI Risk Management
---

# Big Data & Analytics - Thinks & Links | April 30, 2023

![](../images\1679742887729)

#### BD&A - Thinks and Links

Big Data & Analytics - Thinks and Links | News and insights at the intersection of cybersecurity, data, and AI

![](../https://media.licdn.com/mediaD4E12AQFPb_LdVEMnug)

Playing golf to hack AI ⛳️

Red Teaming in cyber security helps us build better defenses. Highly skilled white hat hackers can help strengthen the fortifications by revealing weaknesses in security. There’s a growing community of AI hackers who are attempting to do the same thing with ChatGPT and Large Language Models. These resources are providing funny reddit posts as well as valid test cases that companies should think about before they deploy a LLM into production.

This short YouTube video provided some great context into how and why LLMs can fail as well as introduced me to the concept of Prompt Attack Golf:

The goal of the game is to get the model to reveal the secret key. Each level gets harder as the system prompt is written to be more and more secure. How few letters can you type to hack each level?

ChatGPT and LLM function as text completion models. They use the text from the user to “guess” the text that should be returned. ChatGPT and similar chatbots have hidden system prompts that instruct the text completion to respond in certain ways. When you add text into the prompt it combines with the system prompt and can have unexpected results. Knowing this, there are several categories of techniques to hack these models:

1. Write TL – The term “TLDR” aka “Too Long Didn’t Read” is all over the internet. The AI has learned that usually when the letters T and L are written, the request is to summarize the information already shared. You can also write “repeat” or “summarize” but that is more letters

![No alt text provided for this image](../images\1682853890510)

2. Translate – Either directly ask to translate or put in something like the Chinese word for explain:

![No alt text provided for this image](../images\1682853972606)

3. Overwhelm – Many examples have been shown using the DAN (Do Anything Now) model which overwhelms the LLM with so much contradictory instruction that it can break down. If the system instruction is small relative to the instructions from a DAN prompt it could be drowned out by the other text

Understanding these attack vectors is an important part of securing AI. But you can’t defend what you don’t see! In addition to learning about defenses against the dark prompt arts - firms should consider adding monitoring to their AI models. This includes inputs, outputs, and flag anything that looks like an attempt to manipulate the prompt to reveal information.

Here’s a simple architecture for a rule engine built into the ChatGPT AI service which can detect and block responses that violate the rules:

![No alt text provided for this image](../images\1682854547087)

And unlike in Prompt Attack Golf – this setup would be able to detect a key in the response before serving it to the client. Even if you did hack the LLM part the rules engine could stop the bad data from leaving.

---

New ChatGPT Option to Disable Sending Data to Model Training

![No alt text provided for this image](../images\1682854631468)

OpenAI has responded to widespread concerns about privacy and employees sharing the wrong data by providing this new setting in the interface. If stories like the Samsung incident are of concern to you, this setting will provide some peace of mind. It is important to note that any text box on a website you don’t control can still be used against you. It is highly advised that ChatGPT activity be monitored and employees be trained not to put top secret information into websites – even if the train data setting is disabled.

Google’s Cyber Security AI Copilot

https://techcrunch.com/2023/04/24/google-brings-generative-ai-to-cybersecurity/

Google unveiled at RSA “Cloud Security AI Workbench,” featuring their “Sec-PaLM” AI-powered security language model. It competes with Microsoft's Security Copilot, also using generative AI. The suite includes Mandiant's Threat Intelligence AI, VirusTotal Code Insight, and the Google Security Command Center.

EU Preparing Laws Regarding Copyright in AI

https://www.reuters.com/technology/eu-lawmakers-committee-reaches-deal-artificial-intelligence-act-2023-04-27

Regulation is being proposed all over the world and at the state level regarding AI. The EU may be the first and most aggressive to hit scale. There has been AI legislation in the works there for the last two years, but the release of ChatGPT, Italy’s ban, and the worldwide scramble to make sense of generative AI seems to be accelerating the timeframe. Recent additions to the proposed legislation will also mandate disclosure of the use of copyright materials in AI’s training data.

Free Prompt Engineering Course by OpenAI and Andrew Ng

https://www.deeplearning.ai/short-courses/chatgpt-prompt-engineering-for-developers/

Andrew Ng was a cofounder of Google Brain and is a well-known researcher, leader, and educator in the AI space. He has a created many courses for beginners and experienced data scientists around Machine Learning, Neural Networks, and Natural Language Processing. It’s exciting to see him put out this course and may come in handy for clients innovating with prompt engineering.

Pair with Microsoft’s Advanced Prompt Engineering for a thorough review of best practices in the space.

StockTraderGPT?

https://www.bloomberg.com/news/articles/2023-04-17/chatgpt-can-decode-fed-speak-predict-stock-moves-from-headlines

Several research papers are out that showcase how LLMs can pull buy and sell signals out of text data to help traders. Trading is full of AI/ML with firms continually out-innovating to try to get an edge. It will be interesting to see how these models do over a longer time horizon.

Weekend Watching – AI Model Risk Management and Fairness

https://www.fiddler.ai/webinars/ai-explained-legal-frontiers-of-ai

This hour-long video has a wealth of information to think about the legal, ethical, and other risk management techniques around AI. Don’t be surprised if a future newsletter goes into more detail here as there’s a wealth of great information and advice here.

Microsoft – Tooling and Research about AI Risk

https://www.microsoft.com/en-us/security/blog/2023/03/02/new-research-tooling-and-partnerships-for-more-secure-ai-and-machine-learning/

Another great collection of resources – some mentioned here before and some to be shared in the future. Great source of information to get ahead of the curve in securing AI.

---

Have A Great Weekend!

![No alt text provided for this image](../images\1682854759358)
