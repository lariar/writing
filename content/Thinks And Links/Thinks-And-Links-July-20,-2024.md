---
title: Thinks And Links July 20, 2024
draft: false
tags:
  - Big Data
  - Data Analytics
  - Cybersecurity
  - AI
  - Generative AI
  - AI Adoption
  - Tech News
  - AI and Cybersecurity
---

# Thinks and Links | July 20, 2024

![](../images\1679742887729)

#### BD&A - Thinks and Links

Big Data & Analytics - Thinks and Links | News and insights at the intersection of cybersecurity, data, and AI

![](../https://media.licdn.com/mediaD4E12AQE2GDv0f6C9tg)

### Happy Weekend!

#### Bookmark and Share

Very excited to share AI at Optiv now has a consolidated landing page at:

https://www.optiv.com/solutions/artificial-intelligence

We now have a single page to reference our thought leadership, partnerships, and services for securing AI. Please help us get the word out!

#### Smaller, Better, Faster, Cheaper

OpenAI announced GPT-4o mini Thursday, which is cheaper, faster, and performs better than many other similar-priced models. The initial release shared a high performance of 82% on the MMLU benchmark which has become a standard in marketing how good a given Generative AI model is at academic tasks. As a measure for comparing models, it places GPT-4o mini in the same category as Mistral and Llama smaller open source models. The cost to run it is significantly lower than its competitors.

![](../images\1721482796570)

OpenAI did not confirm the actual size of the model, but based on its performance speed and cost, it is most likely significantly smaller than GPT-4o and other models. The trend towards smaller and more cost-effective models is important for security as well. When ChatGPT first came out and organizations were considering if and how to use it, models were too big to realistically manage and secure centrally without specialized teams. Azure, AWS, and GCP have made this significantly easier with their cloud platforms and the availability of dedicated models. But the other driver of size and cost decrease has been open source model providers like Meta and Mistral. As smaller, open source models became more wide-spread, this has opened the flood gates for organizations to download and run models full on-prem. This mitigates many of the data leakage concerns that CISOs have.

CTOs and Analytics teams will also find GPT-4o mini and models like it to be useful. Tasks that run well with the largest, most powerful models like GPT-4 Turbo and Gemini 2 often fail with smaller models. But engineers have the option to run a model multiple times and then use a model to select the best answer - and this often boosts performance of the outputs. This technique ends up costing less with GPT-4o mini versus using the more powerful single-shot alternative. So teams building with AI now have options to orchestrate complex workflows of multiple model runs and validations that perform well and cost less. The model's increased context window (how much stuff can be fed in for instructions and data) also provides further "democratization" of low cost, powerful AI capabilities. The barriers to further AI adoption keep falling.

The implication for cybersecurity defenders is to expect more and more models in your environment. Lower bariers to entry mean that good and bad models will be found across the enterprise and within various products in your technology stack. These in turn may provide expanded attack surfaces for exploitation. For example, in less than 24 hours from the GPT-4o mini announcement, threat researchers had already jailbroken it:

![](../images\1721482840100)

AI teams have been downloading and testing some of the thousands of open source models available, and we can only expect that trend to continue. Having a plan for governing and managing all of the model mayhem will come in handy. What OpenAI has shown with GPT-4o mini is also a willingness on the closed model providers to fight back with API-based approaches to get that small model performance. It remains the most cost-effective way to access AI capabilities when you factor in all of the additional costs associated with hosting, maintaining, and securing open source models. But this competition is sure to continue to drive prices down and adoption up.

---

#### Avoiding Prompt Lock In

https://www.datanami.com/2024/07/17/coming-to-grips-with-prompt-lock-in/

Working with Generative AI is different than traditional software development because the stochastic nature of the models and because they can be easily swapped out as newer, better, and less expensive models become available. System prompts which work for one model may be less effective for others, requiring developers to maintain an ever-growing list of prompts that have to be monitored and managed. While not directly mentioned in this article, the same is true if you're trying to mitigate some of the more obvious prompt injection techniques. Protections built into the model prompts or surrounding components may need to evolve say when a developer switches from GPT-4 to Mixtral moe 8x7b. AI applications are never "done" by this standard and need to be actively monitored and governed.

#### Large Language Models in Cybersecurity: Threats, Exposure and Mitigation

https://link.springer.com/content/pdf/10.1007/978-3-031-54827-7.pdf

A tremendous, free book from the Swiss Federal Office for Defense Procurement's Cyber-Defense Campus. In it, multiple experts discuss many dimensions of AI and Cybersecurity. This link could take you a long time to read, and might be worth it. But here's how I recommend you consume it:

Upload it to Claude, ChatGPT, or your model of choice

Chat with it to think through various topics on your mind.

For example, I asked Claude for a summary:

Here’s a ChatGPT GPT: LLMs in Cybersecurity Book that you can feel free to use to explore this topic yourself!

#### California SB-1047 AI Safety Law

https://leginfo.legislature.ca.gov/faces/billTextClient.xhtml?bill_id=202320240SB1047

California is currently debating a law that would regulate the development of powerful AI models and put additional liability on model developers for the outcomes of their models if used to cause harm. It has already passed the Senate and will move through the assembly later this year. This legislation has been polling extremely well, and it may be the next major law that impacts AI use in the United States. Since most AI companies are based in or have major presences in California, this can impact the overall AI market and how organizations respond.

The bill mandates a "Positive Safety" determination, full shutdown capability, compliance with NIST AI RMF guidelines, third-party model testing, annual safety reviews, and whistleblower protections. It is also aimed at models using over 10^26 flops, which might also tie in to the smaller models discussion above. Regulatory limits might play an increasing role in the drive to smaller models in addition to cost. Another impact to be mindful of: if your company fine-tunes a model at this size, you will then assume the liability and security considerations. This may further chill the efforts of companies outside of tech or small startups to avoid the regulatory burden.

#### AI and the Future of SecOps

https://www.tanium.com/blog/ai-vs-humans-why-secops-may-not-be-the-next-battleground/

I was interviewed for this article discussing the intersection of SOC Technology and AI - in short, how is it being used by Security teams and what might the future look like. The discussion for this article was one of my favorites - wide ranging on the nature of innovation and the likelihood of disruption in various fields. In security operations, there's so much work to do and so few people to do it that we are not too concerned that AI will replace humans. The people who chose to go into cybersecurity roles will be equipped with tools that make them more effective and able to focus on the more creative and value-additive parts of the job.

---

### Have a Great Weekend!

![](../images\1721483308759)

---

📫 Subscribe to Thinks & Links direct to your inbox

_You can also chat with the newsletter archive at \*\*https://chat.openai.com/g/g-IjiJNup7g-thinks-and-links-digest_
