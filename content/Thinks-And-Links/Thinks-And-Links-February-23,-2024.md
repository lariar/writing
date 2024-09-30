---
title: Thinks And Links February 23, 2024
draft: false
tags:
  - AI Policy
  - Cybersecurity
  - Deepfakes
  - Generative AI
  - AI Procurement
  - Shadow AI
  - Risk Management
  - AI Ethics
  - Data Privacy
  - Big Data
  - Data Analytics
---

# Thinks & Links | February 23, 2024

![](../images\1679742887729)

#### BD&A - Thinks and Links

Big Data & Analytics - Thinks and Links | News and insights at the intersection of cybersecurity, data, and AI

![](../https://media.licdn.com/mediaD5612AQGrdJCHO1uvzw)

_📫 **Subscribe to Thinks & Links** direct to your inbox_

### Happy Friday!

#### AI Invented Policies Must Be Honored

(https://arstechnica.com/tech-policy/2024/02/air-canada-must-honor-refund-policy-invented-by-airlines-chatbot/

Air Canada deployed a LLM based chatbot to help with customer service. When the bot hallucinated a bereavement policy, the airline tried to get out of honoring it by claiming the user should have known not to trust the chatbot. Canadian courts politely disagreed, and the customer got his _partial_ refund. Many thoughts about this story, but probably the most incredible was the lengths Air Canada went to try and keep the money of a man who was just trying to make it home for his grandmother's funeral. If they had consulted ChatGPT, they might have realized the $1,200 this ticket would cost them is far far less than the badwill (and the chatbot development costs) that they had to deal with instead. Don't fly Air Canada - that's the main takeaway. Also be prepared to live with the consequences of whatever your AI dreams up. Guardrails and controls would be helpful here.

#### $25 Million Stolen with Deepfakes (and What to Do About It)

https://woodruffsawyer.com/cyber-liability/deepfakes-ai-cyberattacks/

A recent wire transfer fraud case involved the use of a phishing email that lead to a convincing deepfake simulation over video chat of the CFO requesting a secret transaction be carried out. A successful social engineering attack isn't new, unfortunately. But the availability of AI tools to aid with all aspects of this and other attacks is getting more common every day. This article shares advice which hasn't really changed, regardless of the sophistication of AI: Build a layered Cyber Defense, have a Payment Fraud Detection Strategy, Develop a Response Plan, and have sufficient Cyber Liability Coverage. Some coverage may not include the expanding threat of AI-generated deepfakes. This fraud incident is a great wake up call for organizations to strengthen their defenses for the next AI-assisted attack.

#### A Recent History of Shadow AI + Cyborgs

https://hackernoon.com/shadow-ai-reshaping-the-future-but-at-what-cost

As most firms have either developed AI Acceptible Use Policies or blocked employee access to Generative AI, a number of recent studies have shown the steady increase in "Shadow AI." This brief article summarizes the recent history as well as discussed a few options that CISOs and leadership have. These include developing and enforcing an AI acceptible use policy, training the workforce, and classifying data that can and can not go into an LLM. It might also include creation of approved AI use cases and tools that can re-direct demand from unsanctioned Shadow AI. Another thought-provoking reference was to this blog from last year, "Detecting the Secret Cyborgs." The translation - organizations should encourage Shadow AI and seek out high-performing employees who are using advanced techniques to capture that enthusiasm for their AI transformation. If you can't beat them, promote them and let them help you re-define how efficient work gets done.

#### XSS Marks the Spot: Digging Up Vulnerabilities in ChatGPT

https://www.imperva.com/blog/xss-marks-the-spot-digging-up-vulnerabilities-in-chatgpt/

This blog documents the approach for identifying security flaws in ChatGPT. The cross-site scripting (XSS) vulnerability was discovered when files are cited by the chatbot. The author found a way to inject demonstration malicious code using a specially crafted file that could get around ChatGPT's Content Security Policy. The author also found a Mass Assignment vulnerability, enabling manipulation of conversation metadata to make the exploit shareable. Another vulnerability relates to rendering citations from websites, which could be exploited using an embedded iframe and tricking the user into executing JavaScript. The demonstrated exploits could have lead to an account takeover, however OpenAI was very responsive to address and mitigate these issues prior to publication. Many organizations that are developing their own variations of the ChatGPT service using an internal model may have similar XSS vulnerabilities.

#### Are LLMs Good Enough Yet?

https://blog.mozilla.ai/exploring-llm-evaluation-at-scale-with-the-neurips-large-language-model-efficiency-challenge/

Summary of the approach and findings behind the NeurIPS Large Language Model Efficiency Challenge last Fall. The challenge aimed to address the complexity of evaluating large language models (LLMs) due to their diverse architectures, rapid integration into products, and the growing ecosystem around them. Everything that was done was open sourced to showcase the methodology, technical challenges, and metrics necessary to rigorously validate if models are "good enough." In a blog about AI, considerable focus is on containerization with Docker image reproducibility and Kubernetes infrastructure for machine learning being topics of difficulty and learnings. Model selection, evaluation, and infrastructure remain serious challenges that data teams need to tackle to provide LLM capabilities.

#### Risk Management Framework for AI Procurement

https://www.inclusivechange.org/ai-governance-solutions/rmf-for-ai-procurement

The "Risk Management Framework for AI Procurement" provides a structured approach to evaluate and mitigate risks associated with AI system procurement. It emphasizes understanding organizational risk appetite and integrating risk considerations into procurement processes. With a focus on buyer literacy, readiness, and legitimate need, it outlines steps from risk assessment to monitoring, ensuring AI implementations align with business goals and risk tolerance. This framework is crucial for organizations aiming to harness AI's power responsibly and effectively.

#### Microsoft Automation Framework for Red Teamng Gen AI

https://www.microsoft.com/en-us/security/blog/2024/02/22/announcing-microsofts-open-automation-framework-to-red-team-generative-ai-systems/

Microsoft's own AI Red Team has been hard at work over the last two years testing and strengthening the suite of products that have been released incorporating Generative AI. The scripts and approaches they use have been automated and now open sourced for Security Teams to use. The PyRIT (Python Risk Identification Toolkit) that this log announces can be used by Security Practitioners everywhere to throw malicious prompts at Generative AI systems and secure them from threats.

---

###

### Have a Great Weekend!

![](../images\1708718897202)

####

---

####

_You can now chat with the newsletter archive at \*\*https://chat.openai.com/g/g-IjiJNup7g-thinks-and-links-digest_
