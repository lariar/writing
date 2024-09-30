---
title: Thinks And Links January 6, 2024
draft: false
tags:
- Big Data
- Data Analytics
- Cybersecurity
- AI
- Generative AI
- Data Science
- Legal Issues in AI
- AI and Data Management
- Large Language Models
---

# Thinks & Links | January 6, 2024

![](../images\1679742887729)

#### BD&A - Thinks and Links

Big Data & Analytics - Thinks and Links | News and insights at the intersection of cybersecurity, data, and AI

![](../https://media.licdn.com/mediaD4E12AQG-hfUw7tbSuQ)

*New for 2024: 📫 **Subscribe to Thinks & Links** direct to your inbox*

### Happy New Year!

Welcome to 2024! Last year felt like a decade in AI advancement. This year will probably make it feel sleepy by comparison. All of the factors driving last year’s intensity are still here: ever-improving generative AI use cases, investors eager to realize automation value and cost-saving, research continuing to push the frontier, and a huge open source community adopting and modifying every new development. Criminals and hackers are still here too, and the business of attacking AI / attacking with AI is booming.

In the spirit of kicking off the new year, a few predictions for themes we’ll see (and write about here) in 2024:

#### AI Moves to Production

After demos from excited engineers, chatty consultants, and valuation-driven vendors - it is time for Generative AI to start truly showing value. Teams at companies will be fully grappelling with how to get AI into production while ensuring it works correctly, doesn’t open up massive security holes, and stays within the law. As with all data and analytics projects, the demo on sanitized data can wow, but the devil is in the details.

2024 will be the year that the best Data and AI teams will begin to demonstrate traction with real-world use cases. Security practitioners will need to partner with their business to enable safe AI use cases and strengthen underlying data and IT protections. (Spoiler alert - teams that didn’t have safe data and IT before AI will continue to be at risk, if not more so, with the addition of AI to the tech stack)

We will also see tools from Microsoft, Google, and Amazon to give even more architects and engineers access to some of the more sophisticated capabilities needed to produce high-quality AI applications.

#### AI for X Intensifies

Startups, business units, and products will continue to launch and grow focused on taking high-performing general AI and customizing it for specific industries or use cases. They will benefit from proprietary datasets and/or carefully tuned prompts to help automate tasks that once seemed to require a human. Larger companies will release their own models which will mostly be fine-tuned variations of the larger foundational models. These will work surprisingly well, although a few high-profile information security mistakes will garner a lot of attention.

Companies will continue to adopt these tools at breath-taking pace, and their security teams will struggle to keep up with the expanding threat surface. Fortunately, AI for Security is also intensifying…

#### The Security Job Gap Shrinks

The methodology used to generate the oft-cited 3.5 million open roles in cybersecurity pre-dates the rise of Generative AI. A new study will be performed somewhere that shows how efficiency gains for each person in cyber will result in fewer overall people being needed. This will compete with increasing threat landscape, more prevalent attacks, and changing insurance requirements - but the net result when Generative AI is included will be a shrink to at least 2.5 million, possibly more in 2024. I’m predicting less what the number will be and more that someone will do the math to confirm this assumption.

#### Lawyers will Lawyer

AI shows great promise in automating and enabling the legal industry. You might assume that this could threaten lawyers from future work. However, 2024 will show that the number of legal and regulatory issues that human lawyers will be needed for will jump by an order of magnitude. Signs like the NYTimes lawsuit against OpenAI and the impending EU AI Law mean that for every billable hour AI eliminates, ten more will be created. That being said, don’t let *AI do all your legal work for you* - it never works as you think it would.

#### Smaller is Better

AI adoption will depend on making outputs 1) equivalent or better than human alternatives and 2) less expensive than humans. As organizations become more and more sophisticated with their use of AI, they’ll discover that it still costs a lot of money! While cloud providers will have another record year in revenues from data calculation and storage, businesses will need to consider cost as they bring more AI use cases online.

We don’t know exactly how large GPT-4 and Gemini are, just that the parameters are in the hundreds of billions and the data used for training is a significant percentage of all available written text. GPT-5 and Gemini 3 (or whatever comes next) won’t just add more compute power and data. The current frontier for research is in better-performing, more efficient models and better curation/creation of training data. We know that human brains can learn quite a bit without consuming every piece of writing in history. Research in both neuroscience and AI will continue to probe how this happens and what we can apply to training smaller models.

The research community has been in a race to “beat” GPT-4, the current leader in general AI capabilities. An important breakthrough last year was *QLoRA* which enables a far more efficient Fine Tuning of the major foundational

models. This plus better small foundational models are improving all the time. I’m particularly excited about *Mistral* and *Microsoft* work in this space.

#### Its All About The Data

![](../images\1704540057454)

The better LLMs get, the more people are discovering that retrieval of high quality, well managed, and securely governed data is the key. Retrieval Augmented Generation ([[RAG]]) will be an ever increasing focus this year. The research is clear that contextual “grounding” data helps LLMs produce honest, helpful, and harmless results. Making sure your AI gets the right data at prompt time is an engineering challenge into itself. How much data to retrieve, how to break it up, which data should it be, and focus on quantity or quality - are all questions being resolved. I’ve been following as *Neo4j* has been doing some really interesting work using Knowledge Graphs for RAG with impressive results.

#### LLMs will Participate in a Major Data Breach

A prediction for this year is that at some point Generative AI, and most likely Large Language Models will play a role in a high-profile data breach. It may be successful social engineering using gramatically perfect spear-phishing. It could be the acceleration of malware delivery using “co-pilots” for attacks. It could be security vulnerabilities from hastily implemented AI solutions or Shadow AI. Regardless of how it happens, it will happen in enough places that at least one of them will be high-profile and reported on widely in the news (and in this newsletter!)

---

#### NYTimes Sues Microsoft + OpenAI

*https://www.cnbc.com/2023/12/27/new-york-times-sues-microsoft-chatgpt-maker-openai-over-copyright-infringement.html*

In a *69 page filing*, NYTimes alleges that the AI providers are facilitating copyright theft by using news articles for large language model training. The times complains that by prompting these LLMs in the right way, end users can retrieve full articles with little to no change in a verbatim copy of what the times would have written. Cases like this are to be expected, and we will see how the legal system treats text for AI model training of this nature. When an AI company can generate $1B+ in revenue from a model that includes copyright material, is a portion of that revenue owed as royalties? Because it involves a media company, other media companies are sure to cover it in detail as a new domain of case law is developed over the course of 2024.

#### 

#### How to Hack LLMs

https://www.youtube.com/watch?v=1epBOJqg10w

Highly entertaining and informative talk from Mark C. (*@LargeCardinal*) covering the details of how language models work from the foundational transformer architecture up through the fun ways he’s found to hack them. Note-worthy ideas include some thoughts around securing the system message which causes the chatbot to behave as you’d like (or can be hijacked with clever prompt injection techniques) - in a concept he calls prompt sandboxing:

![](../images\1704540047765)

Prompt Sandboxing introduces some random text into the system prompt and instructs the AI to include this random text any time it shares details of it’s own system prompt. When an attacker attempts to access the sensitive information that might be in that prompt or tries to convince the AI that it has a different (more malicious) function - the random text is included in the answer. The orchestration of the inputs and outputs to the LLM then detect this text and prevent it from reaching the end user.

### DocLLM - Processing Documents for JP Morgan Chase

*https://arxiv.org/abs/2401.00908*

This research paper published by Data Scientists at JP Morgan Chase has been fine-tuned to address a very common and wide-spread problem in Financial Services - form sprawl. Back in the “before times” without GPT-4 this was a high-focus use case for developing AI models. Optical Character Recognition (OCR) could extract text from documents, but any time there were graphics, tables, and forms context would be lost. Many sleepless nights over bounding boxes and sliding windows… Now here comes JPMC with a model posted to Hugging Face that shows great promise. One day soon analysts will download the model, plug it into their application, and massively automate the review and treatment of documents. This revolution will move so much faster than efforts to digitalize and go paperless.

---

### Have a Great Weekend!

![](../images\1704540035018)

2024 marks the entry of *Mickey Mouse into the Public Domain* which means that the earliest cartoons have been rapidly added to *Generative Image models*. Here’s a “drawing of mickey working with AI”

---

📫 Subscribe to Thinks & Links in your inbox

💬 Chat with the Newsletter Archive