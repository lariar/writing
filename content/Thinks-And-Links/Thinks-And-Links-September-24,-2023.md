---
title: Thinks And Links September 24, 2023
draft: false
tags:
- Big Data
- Data Analytics
- AI Policy
- Cybersecurity
- Generative AI
- Data Governance
---

# Big Data & Analytics - Thinks and Links | September 24, 2023

![](../images\1679742887729)

#### BD&A - Thinks and Links

Big Data & Analytics - Thinks and Links | News and insights at the intersection of cybersecurity, data, and AI

![](../https://media.licdn.com/mediaD4E12AQHEfY6U-LlG3g)

### Happy Weekend!

#### Here comes Copilot!

This Tuesday new features are rolling out for general availability in Windows 11, Microsoft 365, and Bing Chat… The wide-release of Microsoft Copilot is here. This seems a good time to remind readers about the importance of having a stance on AI. Love it or hate it, block it or buy everyone a ChatGPT Pro subscription – your business needs to have a stance on AI. New features rolling out in Windows and Microsoft products mean that your teams will be able to:

Quickly draft content

Access their files and content displayed on screen

Respond to emails

Summarize reports

And much, much more…

Businesses should have an AI policy that informs what employees can and cannot do. Anything you wouldn’t like them doing on ChatGPT should probably be prohibited on Microsoft Copilot. There may be administrative controls to enforce this, but the first step is having a rule. The second step is telling your teams about the rule and giving them safe options to use.

Here are some additional considerations for your AI Policy:

![](../images\1695600313208)

Microsoft Copilot will – by default – be the biggest release of “Product AI” this year. There are sure to be misuses and issues that arise from out of policy (bad) behavior. Microsoft announced that come Tuesday businesses are out of time to figure out their plan for this. It’s here.

---

#### 38 Terabytes of Accidental Data Exposure

https://www.wiz.io/blog/38-terabytes-of-private-data-accidentally-exposed-by-microsoft-ai-researchers

Oops. A 38 Terabyte reminder that access control and data governance are very important, especially around data used with AI. There are many potential use cases for AI, and some involve highly sensitive data. Whether you are Microsoft or Dunder Mifflin – be careful with your data!

> The simple step of sharing an AI dataset led to a major data leak, containing over 38TB of private data. The root cause was the usage of Account SAS tokens as the sharing mechanism. Due to a lack of monitoring and governance, SAS tokens pose a security risk, and their usage should be as limited as possible. These tokens are very hard to track, as Microsoft does not provide a centralized way to manage them within the Azure portal. In addition, these tokens can be configured to last effectively forever, with no upper limit on their expiry time. Therefore, using Account SAS tokens for external sharing is unsafe and should be avoided.

*The simple step of sharing an AI dataset led to a major data leak, containing over 38TB of private data. The root cause was the usage of Account SAS tokens as the sharing mechanism. Due to a lack of monitoring and governance, SAS tokens pose a security risk, and their usage should be as limited as possible. These tokens are very hard to track, as Microsoft does not provide a centralized way to manage them within the Azure portal. In addition, these tokens can be configured to last effectively forever, with no upper limit on their expiry time. Therefore, using Account SAS tokens for external sharing is unsafe and should be avoided.*

> In the wider scope, similar incidents can be prevented by granting security teams more visibility into the processes of AI research and development teams. As we see wider adoption of AI models within companies, it’s important to raise awareness of relevant security risks at every step of the AI development process, and make sure the security team works closely with the data science and research teams to ensure proper guardrails are defined.

*In the wider scope, similar incidents can be prevented by **granting security teams more visibility into the processes of AI research and development teams. As we see wider adoption of AI models within companies, it’s important to raise awareness of relevant security risks at every step of the AI development process, and make sure the security team works closely with the data science and research teams to ensure proper guardrails are defined.*

#### AI in Software Development: The Good, the Bad, and the Dangerous

https://darkreading.com/application-security/ai-in-software-development-the-good-the-bad-and-the-dangerous

AI accelerates many things in software development and application security. However, don’t use AI-generated code without human supervision! AI can create vulnerabilities and false responses. It can propagate license restrictions and inherited vulnerabilities from open source code. Organizations should be diligent in testing AI components and understanding how they handle sensitive data and comply with regulations. While AI brings value in minimizing repetitive tasks, it should be used with caution and human vetting.

#### Calling All Security Experts Interested in AI

https://openai.com/blog/red-teaming-network

OpenAI is inviting domain experts to join their OpenAI Red Teaming Network to help improve the safety of their AI models. The network will consist of trusted experts who will collaborate with OpenAI in evaluating and testing their models for potential risks. The network aims to provide continuous input and make the red teaming process more iterative. OpenAI is seeking experts from diverse domains and backgrounds, and compensation will be provided for their contributions. The network members may be contacted to test new models or areas of interest, and the time commitment can be adjusted based on availability. Joining the network does not guarantee involvement in every project. OpenAI also offers other collaborative AI safety opportunities, such as conducting safety evaluations and participating in the Researcher Access Program.

#### GitHub Copilot and Amazon CodeWhisper can be coaxed to emit hardcoded credentials that these AI models captured during training, though not all that often

https://www.theregister.com/AMP/2023/09/19/github_copilot_amazon_api/

Researchers have discovered that AI code completion tools, such as GitHub Copilot and Amazon CodeWhisperer, can reveal hardcoded credentials that were captured during their training. These tools, used to generate software, have been found to expose secrets that were mistakenly made public in code repositories. The researchers developed a tool called the Hardcoded Credential Revealer (HCR) to identify API keys, access tokens, and other sensitive information. They found that both GitHub Copilot and Amazon CodeWhisperer can emit original secrets from their training code, as well as suggest new secrets not present in the training code.

Important to note: these exposed credentials were already public, but it does raise concerns about the potential for other sensitive information to be recalled by AI models.

#### DALL-E 3 – New Generative Image Generator Coming This Fall

https://openai.com/dall-e-3

Nothing actionable in this update – OpenAI announced a new version of their DALL-E text-to-image model. Judging from the examples shared so far it will be very powerful and also capable of adding words / text into images. Currently the state of the art for text-to-images fails on this test case. When the model is released in October we’ll see how good the text generation within image generation actually is.

![](../images\1695600401699)

---

### Have a Great Weekend!

![](../images\1695600431119)