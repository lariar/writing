---
title: Thinks And Links July 22, 2023
draft: false
tags:
- Big Data
- Data Analytics
- Cybersecurity
- AI
- Large Language Models
- AI Policy
- AI Strategy
- AI Regulation
- AI Security
- AI Development
---

# Big Data & Analytics - Thinks & Links | July 22, 2023

![](../images\1679742887729)

#### BD&A - Thinks and Links

Big Data & Analytics - Thinks and Links | News and insights at the intersection of cybersecurity, data, and AI

![](../https://media.licdn.com/mediaD4E12AQG56_TfwZCpmQ)

Happy Weekend!

If you’ve been following along in this newsletter since the beginning of 2023, you may be familiar with two predictions I’ve been writing about once the capabilities of this new generation of LLMs became clear:

We saw major examples of both predictions this week. Let me start with the bad guys:

![No alt text provided for this image](../images\1690000864379)

WormGPT made some headlines this week as a newly announced AI Chatbot without the restrictions of ChatGPT when it comes to doing harm. It is most likely a fine-tuned version of an open source LLM called GPT-J. Researchers did some clever prompt injections to the WormGPT to learn about how it may have been built and what data might have been used to train it. Allegedly this tool will help write phishing emails easier and simplify the development of malicious code.

If anyone reading this newsletter has a lab for malware research and gets ahold of this tool, please let me know! I’d be very interested to hear from you! WormGPT or something like it may be very-soon repurposed for Red Teams not unlike other malware and hacker tools. I can go on all day about language models, but I’m nowhere near qualified enough to fiddle with tools like this on environment. I’ll leave the real threat research to the experts, and share some witty commentary when they post their findings.

I wish I could tell you that building WormGPT was a tremendously expensive and difficult thing to do. However, this is likely just the first version of LLM based hacking tools that has reached mainstream awareness. Someone will make a lot of money selling this, and copycats will soon emerge.

This leads me to the next big story of this week, Llama 2.

Back in February, the original Llama model was released (leaked?) by Meta, and soon found it’s way into several animal variations including Alpaca (Stanford NLP), Vicuna (UC Berkley), and Dolly (Databricks). These all had impressive, GPT-3 like performance without the limitations of a hosted AI service from OpenAI.

This week, Meta introduced an updated version of the Llama model and open sourced it to be free for commercial and research use. Early tests show it has performance near equivalent to GPT-3.5 on reasoning tasks and better than any other Open Source models. It is also, critically, built in a way to encourage enterprise adoption. Meta is licensed for commercial use with the only restrictions being the normal ones about don’t use it for malicious purposes (don’t train WormLlama, for instance). In a further demonstration of the seriousness of what Meta is hoping this model becomes, the announcement of a new, powerful Open Source model was paired with a launch partner to help with distribution:

![No alt text provided for this image](../images\1690000887829)

Microsoft is making it very easy to build with LLMs, either from OpenAI or with Meta. Whether an organization wants to us the leading closed-source models or the leading open-source ones, Microsoft will have the tools to make it easier. (Although in fairness, it is easy to access these tools from any platform – that’s part of what makes them so powerful and so risky)

It’s also worth reviewing the model whitepaper for details on what Meta did to prepare for eventual enterprise adoption of Llama 2 with an eye on Safety. A good chunk of the details in the methodology covers how the model was trained with an eye towards avoiding anything that would make this inappropriate in a corporate environment. Sample safety procedures include:

These are all good ideas to put into practice in whatever size model you may be working with!

---

Infosec Doesn't Know What AI Tools Orgs Are Using

https://www.darkreading.com/tech-trends/infosec-doesnt-know-what-ai-tools-orgs-are-using

AI tools are everywhere, and many organizations are in the dark about what's being used, who's using them, and what data is shared. ChatGPT is the most well known, but other tools like Jasper.ai have been around longer and are in your environment. Security teams must ensure they know and govern the AI tools in use. Optiv can help.

Firms should really be thinking about all three flavors of AI as they build their own AI Policy and Strategy:

![No alt text provided for this image](../images\1690000957062)

The FTC Has Some Questions about OpenAI

https://www.washingtonpost.com/documents/67a7081c-c770-4f05-a39e-9d02117e50e8.pdf?itid=lk_inline_manual_4

Here are 49 Questions OpenAI is being asked about how their models are developed and secured. These are very thoughtful, and important questions to consider as firms build their own AI strategies. It is possible a regulator may one day ask you similar questions, such as:

How many of these 49 could your business answer if a regulator came knocking?

Checkmarx Plugin for ChatGPT – Shifting Left into Chat

https://www.darkreading.com/attacks-breaches/checkmarx-announces-checkai-plugin-for-chatgpt-to-detect-and-prevent-attacks-against-chatgpt-generated-code

Optiv Partner Checkmarx recently announced a plugin that will scan code generated by ChatGPT for vulnerabilities. This is a great idea. It allows developers and security teams to protect against attacks caused by malicious open source packages and dependencies within the ChatGPT interface. The plugin allows development teams to use AI tools while remaining aligned and compliant with application security standards. The CheckAI Plugin is currently available to ChatGPT Plus users and additional use cases will be added in future releases.

AI must have better security, says top cyber official

https://www.bbc.com/news/technology-66166824

Lindy Cameron, CEO of the UK’s National Cyber Security Centre (NCSC), emphasizes integrating cybersecurity into AI systems and establishing early security measures. Rushed development of AI products can lead to overlooked security, risking devastating attacks. Severe consequences are possible as AI integrates into daily life, including autonomous vehicles. Malicious actors can exploit AI, hacking devices or spreading fake messages. Adversarial machine learning studies how AI can be tricked into incorrect results, posing risks like fooling self-driving cars with stickers on road signs. Poisoning AI data creates biased results, difficult to detect due to complexity. Lack of transparency hinders trust. Attacks on AI systems are emerging, necessitating increased security attention. Learning from internet security's early days, developers must take responsibility for cybersecurity.

Auto Documentation for Compliance with EU AI Act

https://blog.vectice.com/press-release-auto-documentation-solution-for-ml-projects-their-governance

Machine Learning documentation tool Vectice has several helpful features for organizations building AI/ML at scale – from individual automations up to risk and compliance reporting. But this was one of the first companies I saw putting out a release specifically about tools to prepare for the EU AI Act. It’ll be a space to watch as more and more companies realize that they may be impacted by this, just as they were surprised to learn they had an impact from GDPR.

Technical Rant About The Hard Part of AI

https://vickiboykis.com/2023/07/18/what-we-dont-talk-about-when-we-talk-about-building-ai-apps/

There’s a lot of work behind the scenes to make the AI magic really happen at scale. Vicki writes a great newsletter for Data Engineering topics, and this post about the difficulties of working with containers and GPUs and details of model building resonated for me. It also supports my believe that AI building and protecting is a significant cross-practice challenge. Bringing subject matter expertise on Cloud, Orchestration, and Network configuration are real differentiators beyond competitors who can just build an AI model.

Researchers Made South Park with AI

https://fablestudio.github.io/showrunner-agents/

Quality is amazing and it’s actually pretty funny. The AI model wrote the plot, generated the images, and created the audio. GPT-4 drove the plot, “Since transcriptions of most of the south park episodes are part of GPT-4's training dataset, it already has a good understanding of the character's personalities, talking style as well as overall humor of the show, eliminating the need for a custom fine-tuned model.” The images were trained using a dataset of ~1,200 characters and 600 background images from the show. The plot centers around a greedy corporation that is using AI to create TV shows. They also create a children’s toy that quickly turns racist. Then the boys even comment on the unrealistic nature of the AI-generated TV shows in the AI-generated TV show. Wild stuff!

---

Have a Great Weekend!

![No alt text provided for this image](../images\1690001011550)

Late nights coding with https://github.com/ThioJoe/Full-Stack-AI-Meme-Generator