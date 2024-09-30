---
title: Thinks And Links June 17, 2023
draft: false
tags:
- Cybersecurity
- AI
- Big Data
- Data Analytics
- Ransomware
- Cyber Attack
- EU AI Regulation
- AI Security
---

# Big Data & Analytics - Thinks and Links | June 17, 2023

![](../images\1679742887729)

#### BD&A - Thinks and Links

Big Data & Analytics - Thinks and Links | News and insights at the intersection of cybersecurity, data, and AI

![](../https://media.licdn.com/mediaD4E12AQGQwU_AIWTdbQ)

Happy Father's Day Weekend!

Unfortunately, there’s a large breach currently impacting multiple US Federal Agencies. It is associated with several zero day vulnerabilities in the MOVEit file transfer tool. This is a widespread incident where many security teams are scrambling to patch and assess the impact of this breach with their own environment and their supply chains.

This blog is frequently about AI and always about data. While I don’t know much about the MOVEit file transfer tool, I know how to find out more. I used a little bit of AI to make myself more useful as a trusted cybersecurity advisor.

Bing Chat:

The MOVEit Federal data breach is a recent cyberattack that exploited a zero-day vulnerability in the MOVEit Transfer software, a widely used file sharing tool developed by Progress Software. The attackers are believed to be Clop, a Russian ransomware group that has been active since 2019 and has targeted various organizations, including universities, corporations, and local governments¹.

According to CISA, several U.S. federal agencies have experienced intrusions related to the MOVEit vulnerability, including the Department of Energy, which confirmed that two of its entities had their records compromised². Other agencies that have active MOVEit contracts include the Department of the Army, the Department of the Air Force, and the Food and Drug Administration⁵. CISA is providing support to the affected agencies and working urgently to understand the impacts and ensure timely remediation³.

The attackers used the MOVEit vulnerability to access and steal files from the targeted systems, some of which contained personally identifiable information of millions of individuals². The attackers then threatened to extort or release the stolen data on their dark web leak site, where they have listed several victims⁵. However, CISA director Jen Easterly said that the intrusions were not being leveraged to steal specific high-value information or to gain persistence into the targeted systems. She also said that she was not aware of Clop actors threatening to release any data stolen from U.S. government agencies⁴.

The MOVEit vulnerability is the latest in a series of cyberattacks that have hit multiple federal agencies in recent years, following the SolarWinds and Pulse Secure breaches that were attributed to Russian and Chinese state-sponsored hackers respectively⁶. The MOVEit breach highlights the need for continuous monitoring and patching of critical software and systems, as well as improved coordination and information sharing among federal agencies and private sector partners.

Source: Conversation with Bing, 6/16/2023

(1) Russian Ransomware Group Breached Federal Agencies in Cyberattack. https://www.nytimes.com/2023/06/15/us/politics/russian-ransomware-cyberattack-clop-moveit.html.

(2) MOVEit Cyber Attack: Personal Data Of Millions Stolen From Oregon, Louisiana, U.S. Agency. https://www.forbes.com/sites/maryroeloffs/2023/06/16/moveit-cyber-attack-personal-data-of-millions-stolen-from-oregon-louisiana-us-agency/.

(3) US confirms federal agencies hit by MOVEit breach, as ... - TechCrunch. https://techcrunch.com/2023/06/16/us-confirms-federal-agencies-hit-by-moveit-breach-as-hackers-list-more-victims/.

(4) US confirms federal agencies hit by MOVEit breach, as hackers list more victims. https://www.msn.com/en-us/news/politics/us-confirms-federal-agencies-hit-by-moveit-breach-as-hackers-list-more-victims/ar-AA1cDNZo.

(5) US energy department and other agencies hit by hackers in MoveIt breach. https://www.theguardian.com/technology/2023/jun/16/moveit-transfer-hack-department-of-energy.

(6) U.S. government says several agencies hacked as part of broader cyberattack. https://www.nbcnews.com/tech/security/us-govenment-agencies-hacked-cyberattack-moveit-rcna89525.

...

I tried several prompts on ChatGPT and Bing Chat that could help with threat hunting. The results… were not great. General Purpose AI models don’t always get the nuance of what we’re asking. We can work on refining a better prompt, or we can just give the AI the information we’re looking for. As an example:

Prompt:

Bing Chat:

Sure, I can suggest some threat hunting searches based on the information at 1. According to the article, the threat group behind the Clop ransomware exploited a zero-day SQL injection vulnerability in MOVEit Transfer software to deploy a web shell called LEMURLOOT and steal data from various organizations. The article also provides some indicators of compromise (IOCs) such as file names, hashes, and IP addresses that can be used to search for evidence of this activity.

Some possible threat hunting searches are:

...

Doing my own search for a useful article with technical details of how the vulnerability might be exploited and what researchers were seeing in the wild was much more powerful. I could then run one more prompt to get right to work on my imaginary SIEM:

Bing Chat:

Sure, I can provide you some Splunk SPL searches based on the threat hunting suggestions I gave you. Here are some examples:

To search for any files named human2.aspx or _human2.aspx on your web servers, you can use the following search:

To search for any network connections to or from the IP addresses listed in the article, you can use the following search:

To search for any SQL injection attacks against the guestaccess.aspx file on your web servers, you can use the following search:

To search for any user accounts created or modified with the name "guest" on your web servers, you can use the following search:

To search for any unusual or large data transfers from your web servers to external destinations, you can use the following search:

...

Welcome to mid-2023 where you can have actionable searches and actions to take moments after trusted information comes in about a new vulnerability. The time to understand and begin taking action can dramatically decrease. Even with publicly available LLM models, some thoughtful prompting gets you everything you need to protect your environment, communicate with stakeholders, and respond faster. AI built for cybersecurity will be well tuned to cyber use cases, informed by reliable threat intelligence feeds, and embedded in SOC workflows. Powerful stuff.

---

European Parliament Agrees on Position on the AI Act

https://www.huntonprivacyblog.com/2023/06/15/european-parliament-agrees-on-position-on-the-ai-act/

Europe’s AI regulation is moving closer to law with many implications worth paying attention to:

Google Shares Its Secure AI Framework, but something is missing

https://blog.google/technology/safety-security/introducing-googles-secure-ai-framework/

This is a great list of intersections between Cybersecurity and AI. See if you can guess what immediately popped up as missing from this list:

Data. Perhaps you can squeeze that into #6, but in my opinion trusted training and evaluation data for model development and deployment is critical. Bad data = bad models or at least biased models. Data is foundational to the AI Governance model that we’ve been discussing with our clients. But all of the other stuff is also important. Optiv’s many offerings can align with a lot of what’s here. And Google promises more tools and accelerators around this framework in the weeks and months to come.

A Survey of the Large Language Model Stack from the VC / Startup Perspective

https://www.sequoiacap.com/article/llm-stack-perspective/

VC firm Sequoia Capital surveyed their portfolio companies to see how LLMs were being incorporated into the technology stack. The key findings include a list of the tools and vendors who are making significant progress in this space. It also includes some takeaways for businesses of all sizes contemplating adopting / scaling AI. Noteworthy findings include:

Introducing the Elastic AI Assistant

https://www.elastic.co/blog/introducing-elastic-ai-assistant

I’m very excited to start using this in demonstrations. This security copilot uses the powerful natural language processing capabilities of the Elastic Search Relevance Engine along with the OpenAI LLM API. It promises to revolutionize workflows – although users will need to be cautioned still to not put anything into the prompt that would be against your corporate AI policies.

Some examples of the capabilities of this tool (and more are coming):

The Databricks Lakehouse Platform for Cybersecurity Applications

https://www.databricks.com/blog/databricks-lakehouse-platform-cybersecurity-applications

Very excited to see Databricks launch this architecture and approach for cybersecurity. I’ll be in San Francisco at their Data and AI Summit the last week of June to speak with clients, partners, and represent Optiv and our capabilities to help clients realize the cybersecurity capabilities they have in their Databricks environments. If you or someone you know will be there – let’s meet up!

---

Have a Great Weekend!

![No alt text provided for this image](../images\1686972561405)

*                    **Metrics reporting** doesn't have to be "Charlie Work"*