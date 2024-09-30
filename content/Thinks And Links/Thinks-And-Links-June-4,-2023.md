---
title: Thinks And Links June 4, 2023
draft: false
tags:
  - Big Data
  - Data Analytics
  - AI
  - Cybersecurity
  - Generative AI
  - AI Safety
  - AI Transparency
---

# Big Data & Analytics - Thinks and Links | June 4, 2023

![](../images\1679742887729)

#### BD&A - Thinks and Links

Big Data & Analytics - Thinks and Links | News and insights at the intersection of cybersecurity, data, and AI

![](../https://media.licdn.com/mediaD4E12AQFDpC_k69ho2A)

Happy Sunday!

It appears that chains are the future. When ChatGPT started to take the world by storm earlier this year, there was a moment where “Prompt Engineer” sounded like the next hot new job. However recent research and practical applications of AI (including Optiv projects) are showing the value of thinking in chains rather than in mega-prompts.

A lot of recent research and development has been focused on the impact of chaining AI prompts together, which has shown great promise in enhancing both the quality and the safety of AI outputs. (An Example) Instead of relying on a single prompt, we create a series of prompts and use the output of one as the input for the next. This process can take various forms such as pre-processing raw text inputs, refining the outputs, or even generating text in a specific format and quality . It's a bit like handing off a baton in a relay race, with each leg of the race being a different prompt and task. This chaining approach provides several key benefits:

Safety and control are significantly enhanced by chaining AI prompts together. By breaking down complex tasks into smaller, more manageable sub-tasks, we can increase the likelihood of successful task completion. This is because each sub-task in the chain can be handled more effectively than if we tried to tackle the entire task in one go. For instance, instead of asking an AI model to write a constructive review in one step, we could break it down into smaller sub-tasks: extracting presentation problems, brainstorming suggestions, and then synthesizing these into a friendly paragraph. The result? A noticeably improved output .

This concept is one of the reasons that tools like Microsoft Power Virtual Agents (nocode) and LangChain (code) are very popular for AI development.

Chaining AI prompts together isn't just about making AI more powerful, but also about making it more transparent, controllable, and collaborative. Think in chains to unlock greater capability and safety.

---

How AI Works + Uses in Cyber Security

If you’re looking to learn more about some of the technical details behind AI and Large Language Models, you should check out the slides and GitHub repository from Roberto Rodriguez @Cyb3rWard0g, Principal Security Researcher at the Microsoft Security Research Organization:

Slides https://bit.ly/X33fconSlides

Repo https://github.com/Cyb3rWard0g/GPT-Security-Adventures

He does a very thorough job explaining the concepts power modern day AI and then dives in deep into some ways that GPT-type models can enhance the cyber security workflows. The code provides notebooks that further demonstrate several of the use cases and explainers from the deck.

CrowdStrike Introduces Charlotte AI – their LLM / Co-Pilot offering

https://www.crowdstrike.com/blog/crowdstrike-introduces-charlotte-ai-to-deliver-generative-ai-powered-cybersecurity/

CrowdStrike has joined a growing list of cyber vendors to add Large Language Model capabilities to their product suite. The announcement includes several powerful examples of this AI at work including reporting on overall risk posture, providing cyber metrics and insights behind them, accelerating threat hunting, and automating repetitive and tedious tasks. Interestingly, CrowdStrike concedes that “while LLMs will be commoditized over time, the data the models use will not” – this is in line with what I’ve been reading and writing about. The very fact that LLMs are rapidly becoming commonplace is why it is so important to understand and secure them. CrowdStrike claims their data advantage comes from:

The resulting AI capabilities will be uniquely tuned to Cybersecurity outcomes, and I’m looking forward to hearing more about any hands-on experience with Charlotte our CrowdStrike clients are seeing.

Don’t Trust ChatGPT to Write a Court Filing

https://lawandcrime.com/lawsuit/lawyer-was-unaware-chatgpt-could-generate-fake-legal-research-now-faces-sanctions/

Don’t do this. ChatGPT and similar models make things up and do it in a way that is so believable that you might be tempted to copy/paste legalese from the system into a late night court brief. There are certainly ways to use these tools to accelerate your work, but please have a human review it!

In response to these events, District Judge Brantley Starr in Dallas has issued the following “Mandatory Certification Regarding Generative Artificial Intelligence:”

All attorneys and pro se litigants appearing before the Court must, together with their notice of appearance, file on the docket a certificate attesting either that no portion of any filing will be drafted by generative artificial intelligence (such as ChatGPT, Harvey.AI, or Google Bard) or that any language drafted by generative artificial intelligence will be checked for accuracy, using print reporters or traditional legal databases, by a human being.

I asked ChatGPT to explain that legalese like I’m five in a short sentence:

Lawyers must tell the court if they used a computer to help them write and have a person check it before submitting.

ChatGPT Plugin Vulnerabilities

https://www.tomshardware.com/news/chatgpt-plugins-prompt-injection

ChatGPT has made plugins available for paid subscribers which effectively give the AI model the ability to interact with websites, documents, and databases to solve some interesting problems. For example the Expedia plugin helps to search for flights, hotels, and activities to do on upcoming travel in a more intuitive and interactive way. One downside is that these plugins provide a pathway for bad actors to inject malicious prompts. This is a great example of one such exploit and a pattern we will need to detect against when the LLM models are home-grown and have the potential to expose company secrets or disrupt our businesses. (Same researcher does it again using YouTube transcripts, another popular data source for ChatGPT)

Nvidia: We’re all programmers now

https://www.reuters.com/technology/ai-means-everyone-can-now-be-programmer-nvidia-chief-says-2023-05-29/

Nvidia has caught a lot of attention in the financial press thanks to its impressive earnings beat driven by outsized demand for GPU chips in datacenters worldwide. This brief commentary explains some of the drive behind that demand (it’s not just hype). Anyone can be a programmer via natural language. A significant chunk of the economy understands this and has placed orders with Nvidia for more GPUs to do more AI.

Designing our National AI Strategy

https://www.whitehouse.gov/wp-content/uploads/2023/05/OSTP-Request-for-Information-National-Priorities-for-Artificial-Intelligence.pdf

The US is developing a National AI Strategy to harness the benefits and mitigate the risks of AI. The Office of Science and Technology Policy (OSTP) is seeking public comments to help inform this strategy. Public comments are open now until July 7, 2023. Topics of comments can include ideas around ways to protect rights, safety, and national security; impact of AI on civil rights and democratic elections; improvements possible to public services, economic output, and improving government. A robust national discussion is taking place about AI, and it will be very interesting to watch this unfold.

Optiv’s AI Executive Briefing

https://www.optiv.com/insights/discover/downloads/ai-executive-briefing (attached)

If you and/or your clients enjoy these newsletters and would like to participate in the live version of them, please reach out to schedule a session described in this newest Optiv Service Brief. I (and other Optiv leaders) are fielding questions daily about the state of AI and cyber security, and we’d be happy to share the latest details with your clients.

---

Have a Great Weekend!

![No alt text provided for this image](../images\1685795425380)

The power of Photoshop’s new Generative Fill capability
