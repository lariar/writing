---
title: Thinks And Links January 20, 2024
draft: false
tags:
- Big Data
- Data Analytics
- Cybersecurity
- AI
- Data Privacy
- Data Security
- Machine Learning
- Generative AI
- Large Language Models
- AI Governance
- AI Research
- AI Development Tools
---

# Thinks & Links | January 20, 2024

![](../images\1679742887729)

#### BD&A - Thinks and Links

Big Data & Analytics - Thinks and Links | News and insights at the intersection of cybersecurity, data, and AI

![](../https://media.licdn.com/mediaD4E12AQFRCT7Lx77FEQ)

*New for 2024: 📫 **Subscribe to Thinks & Links** direct to your inbox*

### Happy Weekend!

#### Copilot for All

*Big announcement* from Microsoft expanding access to Copilot in the Microsoft 365 suite of tools. For the same cost as a ChatGPT license, you can now access the same model GPT-4 as well as have it:

Generate drafts, summarize, and rewrite your content on Word

Create whole presentations from other documents in PowerPoint

Summarize long email threads and draft responses in Outlook

Create status updates based on a team's meetings, emails, and chat threads

Soon you will be able to create Copilot GPTs (like on ChatGPT) likely with similar functionality and wide-ranging applicability

As someone who lives in PowerPoint, this excites me most of all: *Copilot in PowerPoint – Copilot Snack Show Me How Video*

#### Key Details of the Announcement

Copilot for Microsoft 365 is now generally available for small businesses with Microsoft 365 Business Premium and Business Standard Customers can purchase between one and 299 seats for $30 per person per month.

We’re removing the 300-seat purchase minimum for commercial plans and making Copilot available for Office 365 E3 and E5 customers (A Microsoft 365 license was previously required).

Commercial customers can now purchase Copilot for Microsoft 365 through our amazing network of *Microsoft Cloud Solution Provider partners*.

Last month, we also *announced* eligibility of Copilot for Microsoft 365 for education faculty and staff.

#### Getting Ready

The benefits of Copilot are immense, but so are the privacy and data risks. Now is a great time to *Prepare for Copilot* by doing the following:

Assess AI Readiness: Evaluate your organization's readiness for AI integration. This involves understanding your organization’s relationship to change and innovation, its current stance on AI, willingness to adopt AI technologies, investment and funding capabilities, and endpoint management and security capabilities.

Leverage Microsoft 365 Features: If you already use Microsoft 365, you're a step ahead, as it is required to implement Copilot. If not, first deploy and configure Microsoft 365 to work well in your environment. You will also need to be using Azure Active Directory and to align your network with the *Microsoft 365 network connectivity principles*.

Develop a Strong Foundation in Security and Endpoint Management: Ensure that your organization has a robust security foundation. Zero Trust security is crucial for protecting data and enabling AI-powered work from any endpoint.

Permissions and Content Management: Copilot will rely on your existing permissions and policies, to determine what content can be shared across endpoints. A robust content management practice is key to manage oversharing and ensure data governance. Done right, this is one of the most magical features of Copilot. Without it, you're no better off than with ChatGPT.

Security, Privacy, and Data Residency: Copilot adheres to Microsoft's security and privacy standards. If you trust Microsoft with your data already, Copilot doesn't add new risk. Data stays within borders, does not go to OpenAI's public services, and is not used for training. Copilot can accelerate bad practices that are already possible in your environment.

Invest in Change Management and Training: Prepare your workforce for the transition to AI-powered processes and systems. This includes investing in training programs that familiarize employees with AI tools and new technologies.

Secure Funding for AI Deployment: Ensure that there is adequate funding and support from leadership for implementing AI technologies. This includes budgeting for both the deployment of the technology and the necessary training and change management initiatives.

Get Help: For personalized guidance, consider speaking with experts. *I* *happen* to *know* a *few*, but regardless of where you find them, Advisors can help smooth the transition and avoid known security and product pitfalls.

Bottom Line: If you see something in AI that’s only available for big companies / sophisticated data science teams, there’s a simple solution:

Wait a few months.

Copilot for all is here.

---

#### Sleeper Agents a new LLM Threat?

*https://arxiv.org/abs/2401.05566*

*Anthropic* released a troubling research finding last week demonstrating how a large language model can hide adversarial or undesirable behavior until triggered. Imagine certifying through rigorous testing and evaluation that a model is "safe" and production ready. Then the right sequence of words unlocks a different mode of operation, ready to code malware or betray secrets.

This is very concerning if true. As with all research, it's going to take time and independent verification before we truly understand the problem and then what to do about it. Until then, please please please treat LLMs with care. There are thousands of low-risk, high-value use cases that won't be impacted by a mis-behaving language model. Focus there, build systems and processes to secure them, and monitor this space for further research developments.

#### Protect AI's January 2024 Vulnerability Report

*https://protectai.com/threat-research/january-vulnerability-report*

Nice summary of some Critical and High CVE's found and fixed by the AI/ML community. Particularly noteworthy to see popular Machine Learning platform *MLflow* on this list a few times. Also a very interesting Deserialization of Untrusted Data attack that I think is worth highlighting.

*CVE-2023-7018* is an exploit that demonstrates how downloading an open source model from Hugging Face can lead to remote code execution. With one line of python code, an unsuspecting developer who believes their downloading the latest-and-greatest new AI model can instead have the code create and run malware on their machine.

![](../images\1705749701315)

Open Source models are tremendously useful and a great alternative for use cases where price or data sensitivity makes using a service like OpenAI less attractive. But vulnerabilities like this are a reminder that they are also a pathway for unknown dangers into our environment. User training, models certification, vulnerability scanning, and extending a "zero trust" mindset to cover AI/ML activities are key

Details: *https://huntr.com/bounties/e1a3e548-e53a-48df-b708-9ee62140963c/*

#### Llama 3?

*https://decrypt.co/205436/llama-3-release-date-rumored-meta-ai-challenger*

Rumors and recent statements from Meta CEO Mark Zuckerberg lead us to believe that sometime in 2024 we will see the release of Llama 3. *Llama 2* is one of the leading Open Source alternatives to large closed source models like OpenAI GPT-4 or Google Gemini. It is the starting point for a great deal of research and user customization, fine tuning, and production use cases. With a large and growing inventory of specialized GPU AI-trianing hardware and a commitment to open-sourcing anything that is developed - Llama's next release is sure to make waves.

Bottom line: Many problems that the current generation of AI applications have will likely be mitigated by better Open Source options. If your proof of concept model is unreliable today, sit tight. Engineering will help, but a better LLM engine is coming.

#### What Do Boards Need to Know About AI

*https://www.travilliannext.com/2024/01/18/board-insights-series-part-v-a-panel-discussion-on-strategic-board-talent-and-expertise/*

I had an exciting opportunity to join in a wide-ranging conversation about Board Governance and Risk, which touched on topics of Financial Services Risk, Regulatory Compliance, and Board Governance. (Fun fact - my first experience with Natural Language Models and AI/ML was in Financial Services Risk Use Cases. There are MANY) We also dove into the rapidly-changing world of Generative AI and the growing challenges of cyber risks. These technology-driven risks and opportunities are present in every industry, and Financial Services has a special exposure to and awareness of them.

Here's what stood out: Board members don't need to be experts in AI, cybersecurity, or finance, but they are essential in managing these new challenges. They need to ask tough questions and think deeply about risks. Having board members with diverse experiences and a questioning attitude is invaluable. They face a unique challenge – to understand how a business traditionally works and its common risks, while also pushing it to adapt and stay ahead in the market. The role of AI in this scenario is increasingly becoming a regular topic in board meetings.

#### AI-Driven Threat Modelling with STRIDE GPT

Demo: *https://www.youtube.com/watch?v=_eOcezCeM1M*

Try It Yourself: *https://stridegpt.streamlit.app/* (bring your own API key)

Nice video demo of a tool called Stride GPT that can be used to automatically generate threat models. Stride GPT helps non-security experts quickly and easily generate a threat model for their application, which can then be reviewed by a security expert. This can help to save time and resources, and can also help to improve the overall security of applications.

#### Good

*https://hbr.org/2024/01/survey-genai-is-making-companies-more-data-oriented*

21% to 43% of organizations claimed to have a "data and analytics culture" last year and this year according to a new Harvard Business Review survey. AI has had a profound impact on businesses that recognize the opportunities can only be realized with secure and reliable data.

#### OWASP AI Exchange

*owaspai.org*

I was excited to find this over the past week. Looking forward to learning and contributing. If you're also interested in this topic, the purpose statement says it all:

The OWASP AI Exchange is as an open source collaborative document to advance the development of global AI security standards and regulations. It provides a comprehensive overview of AI threats, vulnerabilities, and controls to foster alignment among different standardization initiatives. This includes the EU AI Act, ISO/IEC 27090 (AI security), the *OWASP ML top 10*, the *OWASP LLM top 10*, and *OpenCRE* - which we want to use to provide the AI Exchange content through the security chatbot *OpenCRE-Chat*.

Our mission is to be the authoritative source for consensus, foster alignment, and drive collaboration among initiatives - NOT to set a standard, but to drive standards. By doing so, it provides a safe, open, and independent place to find and share insights for everyone. See *AI Exchange LinkedIn page*.

![](../images\1705749688343)

#### Tools for Builders: Choosing Model and Provider

*https://artificialanalysis.ai/*

If you are building with AI, odds are good that you've spent a lot of money with OpenAI. GPT-4 has been the best option for AI development since it's release - prompts are more likely to work quickly and consistently and so the time from idea to reality is much faster. And then you're hit with a big bill at the end of the month. Applications requiring multiple model calls can also be slower with GPT-4 as it is (we believe) on of the largest models available and certainly in high demand. This site does a nice job of comparing the alternative options from a cost and speed perspective.

#### Tools for Researchers: Tracking Papers

*https://www.emergentmind.com/*

A great use case for AI is helping to keep up with research on AI. Here's an aggregator of research that looks at X (twitter), Youtube, GitHub, and HackerNews for references to research and then provides some LLM-assisted summarization and references. A great source for seeing how the open source and research community are solving problems related to AI. Another useful resource is my *Research Buddy* who helps think through problems and query research papers for relevant insights.

---

### Have a Great Weekend!

![](../images\1705749711918)

![](../images\1705749719839)

*WTH is this email? (Recap)*

*Each week I get to talk with lots of clients, colleagues, and team members about fascinating topics at the intersection of cybersecurity, data, and AI. I’ve decided to share some of the fun. There’s so much going on in this space that impacts all of us. It’s exciting for me – and I hope you’ll be entertained too.*

*🤖 Chat with the newsletter archive at **https://chat.openai.com/g/g-IjiJNup7g-thinks-and-links-digest*

* 📫 **Subscribe to Thinks & Links** direct to your inbox*