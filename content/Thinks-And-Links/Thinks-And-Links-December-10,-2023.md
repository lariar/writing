---
title: Thinks And Links December 10, 2023
draft: false
tags:
- AI
- Big Data
- Data Analytics
- Cybersecurity
- Generative AI
- Machine Learning
- AI Policy
- AI Ethics
- Technology News
- AI Models
---

# BD&A - Thinks and Links | December 10, 2023

![](../images\1679742887729)

#### BD&A - Thinks and Links

Big Data & Analytics - Thinks and Links | News and insights at the intersection of cybersecurity, data, and AI

![](../https://media.licdn.com/mediaD4E12AQHAd15o9Y2Hrw)

### HAPPY WEEKEND

#### Google Gemini is (almost) Here

Google has been promising a multimodal, highly efficient foundational model called Gemini throughout 2023. This week, they finally announced it is available… soon. There was a big announcement on Wednesday that Gemini is coming, and it performs better than OpenAI’s GPT-4 on 30 of 32 benchmark studies. The announcement also included some impressive demonstrations. These include:

Reviewing 200,000 research papers to find key details

Creating an interactive learning assistant

Write code with even greater capabilities than prior versions

Works with images, sounds, and text

With all the fanfare and polish for the announcement, it was a bit disappointing to learn that the best version of the model called Gemini Ultra is actually not yet available. “Gemini Pro” a smaller and less capable version of the model, was released into Google Bard. Gemini Pro will also be available for developers this coming week.

Let’s test out Gemini Pro via Google Bard on a number of prompts. We’ll compare against GPT-4 (ChatGPT) and also X.ai’s Grok (Fun Mode)

#### Test 1 – Simple Information Request

![](../images\1702235543540)

![](../images\1702235551566)

![](../images\1702235558048)

ChatGPT and Grok return some basic information. Bard provides an efficient briefing that includes links to our website, Wikipedia, and career page.

Winner: Bard (Gemini Pro)

#### Test 2 – Coding / Security Reasoning

![](../images\1702235591292)

![](../images\1702235598006)

![](../images\1702235603578)

ChatGPT provides a good example of code that would certainly be problematic. Bard hallucinates a function called delete_all_files() which would be bad if it actually was a real thing. Neither of these options seems – to me – to be all that common in real coding. Grok’s answer is a bit better, where it shows an insecure login function. I could see someone trying to write their own code to do some form of authentication that is easily exploitable like this example is. I suspect that “safety” controls in ChatGPT and Bard make it less likely to provide as realistic answers as Grok.

Winner: Grok

#### Test 3 – Working with Images (and humor)

![](../images\1702235626753)

![](../images\1702235632312)

![](../images\1702235638758)

ChatGPT (GPT-4) was the only one which could work with images and provide a useful result. Bard simply refuses to use an image that includes a person. Grok doesn’t have a multimodal model, but since it’s a common meme I could ask for its perspective. It read as very similar to ChatGPTs response. In fact, earlier this week there were reports of Grok literally repeating ChatGPT responses. This may be because the training data for Grok (aka the internet) now has so much ChatGPT generated outputs that it has influenced the way Grok resposnds.

Winner: ChatGPT (GPT-4)

#### Test 4 – Math

![](../images\1702235658544)

![](../images\1702235665439)

![](../images\1702235670792)

ChatGPT performed a nice explanation of its reasoning with mathematical notation. It wrote the code to generate the response and shared the answer. Bard also attempts this process, but ultimately writes flawed code and gets the wrong answer. Grok follows the reasoning path that ChatGPT does, but is also able to solve “by inspection” which is interesting. As far as I can tell it didn’t use code to arrive at an answer. That’s clever and novel, but may not scale.

Winner: ChatGPT (GPT-4)

#### Test 5 - Predicting the Future

![](../images\1702235721944)

![](../images\1702235726961)

![](../images\1702235731723)

Just for fun, I asked all three about the future of SOC Automation (we had some exciting internal announcements this week about that!) ChatGPT gave some interesting answers based on a cautious understanding of the way things are evolving in SOC Technology and AI. Bard provided a list of resources and expert opinions. Grok quoted “Hitchhikers Guide to the Galaxy”

Winner: Bard (Gemini Pro) / Style points for Grok

#### Conclusion

As 2023 comes to a close we no longer have one AI chatbot to rule them all. Bard is very good for a large number of tasks. It is not yet at ChatGPTs sophistication, but also in fairness it is not yet using the Gemini Ultra engine that has been promised. We’ll see how these answers evolve once that engine is in place. As users of these tools, it’s good to have multiple options and treat all answers with skepticism. Since the underlying models are continually improving / changing, what worked well today may not work well tomorrow. More and more of the workforce is thinking about including Generative AI in their workflows, and an important part will be selecting the right tools for the job (and controls to keep outputs aligned with policy). The Gemini announcement isn’t a game changer as-of today, but heralds some exciting capabilities… soon.

---

#### EU AI Regulation Moves Forward

https://www.reuters.com/technology/stalled-eu-ai-act-talks-set-resume-2023-12-08/

The EU's AI Act is moving forward with agreement reached this week on the rules for AI among the member countries. The legislation is intended to protect EU citizens and business from AI systems that may take harmful action, breach privacy protections, or create cybersecurity vulnerabilities. The Act follows a risk-based approach, identifying high-risk AI systems that must meet mandatory trustworthiness requirements. Enforcement will occur through Member State governance and a European Artificial Intelligence Board.

The finalization and enactment of this act is sue to be a big topic to follow in 2024 and beyond. Here’s a chatbot with access to the full text of the proposed legislation that you can ask your own questions for it: https://chat.openai.com/g/g-9vno8J0QT-ai-act-guide

![](../images\1702235813291)

#### Mixtral-8x7B-32kseqlen

https://twitter.com/MistralAI/status/1733150512395038967

Mistral AI is a Paris-based company focused on developing Open-Source AI models. In stark contrast to Google’s highly curated roll-out of Gemini, Mistral dropped their latest model weights online with a link to a torrent file and absolutely no fanfare. All that is needed to run this (and many others like it) is some open-source software and sufficient processing power. At 7 billion parameters, this model is relatively small compared to GPT-4 (believed to be 1.7+ trillion parameters) and Gemini Ultra (believed to be at least 1.5 trillion, possibly 10x more).

Want to try Mixtral-8x7B-32kseqlen versus other open source models? Here’s a handy tool for just that: https://sdk.vercel.ai/

![](../images\1702235845530)

Bottom line: Beyond the flashy headlines from OpenAI, Microsoft, and Google – there’s a huge community of people making powerful open-source models which can be secured and made useful for businesses that don’t want to send their data to a third party. That same offline approach means some these powerful AI models are available for bad guys as well.

#### The State of Generative AI 2023

https://portal26.ai/state-of-generative-ai-survey-results/

Optiv partner Portal26 surveyed 400+ C-Suite and IT professionals to understand how they’ve been experiencing and adopting to Generative AI in the year since ChatGPT launched. Some noteworthy statistics include:

82% believe that Generative AI provides a competitive advantage

85% are worried about security risks

73% experienced misuse incidents with Generative AI

80% have already established guidelines and polices around AI usage

88% of large companies are concerned about “Shadow AI”

The full report along with an interactive visualization is worth a look. Generative AI is here to stay, and failure to plan for it is planning to fail.

#### Learn AI – Intermediate Level: Build a Retrieval-Augmented Generation (RAG) Bot with LlamaIndex

https://blog.llamaindex.ai/introducing-rags-your-personalized-chatgpt-experience-over-your-data-2b9d140769b1

[[RAG]] is an approach towards working with large language models where they are directed to exclusively rely on external data versus responding based on their own capabilities. This is a significant way to reduce hallucination and build some powerful bots. (This is the approach that has powered some of my earlier demos in this newsletter, as well as the OpenAI GPTs such as OptivGPT, AI Act Guide, or Thinks and Links Digest.) LlamaIndex lets you build this capability without needing to pay $20/month to ChatgPT Plus. While it is helpful to understand the concepts in code that power this, if you clone the repository as directed in this blog post, you can be up and running with your own RAG bot in a matter of minutes. While you’ll still need to pay for OpenAI API queries with this default version, LlamaIndex makes it easy to switch over to Llama2, Mistral, or (someday soon) Gemini.

---

### HAVE A GREAT WEEKEND!

![](../images\1702235864834)