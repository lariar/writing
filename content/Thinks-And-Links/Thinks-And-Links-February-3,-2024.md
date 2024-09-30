---
title: Thinks And Links February 3, 2024
draft: false
tags:
  - Big Data
  - Data Analytics
  - Cybersecurity
  - AI Integration
  - Generative AI
  - Data Governance
  - AI Adoption
---

# Thinks and Links | February 3, 2024

![](../images\1679742887729)

#### BD&A - Thinks and Links

Big Data & Analytics - Thinks and Links | News and insights at the intersection of cybersecurity, data, and AI

![](../https://media.licdn.com/mediaD4E12AQGRFH4df-VdRQ)

_New for 2024: 📫 **Subscribe to Thinks & Links** direct to your inbox_

### Happy Weekend

### Microsoft New Future of Work Report 2023

Microsoft Research has published a comprehensive study into the integration of Large Language Models (LLMs) in the workplace. They use data from their unique perspective into how work happens on tools like Copilot, Teams, Azure, and Microsoft 365. There's also a survey of recent and foundational research into how automation, artificial intelligence, and human nature come together to provide meaning and drive outcomes at work. The _full report_ is dense with insights, and here are a few take aways to think about for enabling and securing AI.

#### Enhancing Productivity and Skills with AI

The study highlights that LLMs like Copilot for Microsoft 365 can significantly improve productivity in common information work tasks. These tools not only save time but also reduce effort, with a predominantly neutral impact on task quality; some things are better and some things are worse when AI is involved. Less experienced workers benefit the most from these AI advancements, suggesting a leveling of the playing field in workplace skills. Beyond automating tasks, AI can play a role in critical thinking, with LLMs acting as provocateurs that challenge and deepen users' thought processes. Frameworks to structure critical thinking such as "Bloom's Taxonomy" (Remember -> Understand -> Apply -> Analyze -> Evaluate -> Create) might become a key part of AI integrations.

#### Working Dynamically with AI

The study reviews research into AI's ability to break down complex tasks into smaller subtasks ("microproductivity") that can enhance efficiency and quality. This point emphasizes a movement away from traditional task execution towards more dynamic analysis and integration. As an example, a user might enter "Exercise more frequently" into his task list and an action plan will be created to "find a workout buddy to keep you accountable; get a gym membership; create a weekly exercise schedule; Start working out this Monday and stick to the schedule." Prompt engineering is an important gateway to gaining productivity, and it is becoming easier and more effective thanks to tooling and finer-trained models.

#### Over-Reliance

The study stresses the importance of a human-centered approach in AI collaboration, where humans and AI complement each other's capabilities. However, managing the degree of reliance on AI is crucial to avoid over-dependence. The fear is that humans will tend to trust AI outputs without reviewing them thoroughly. Techniques are shared such as "uncertainty visualization" which can counteract over-reliance. Another concept introduced is Co-audit which can form a feedback loop with prompt construction focused on principles such as citing reliable sources, providing multiple options, and direct attention to areas most likely to contain errors. As applications and businesses adopt AI, over-reliance will become an additional concern that requires heightened self-awareness from users and vigilance from organizations.

#### Solving Organizations' Greatest Problem: Knowledge Fragmentation

AI is revolutionizing how knowledge is managed and accessed. Where organizations traditionally relied on documents for knowledge, AI makes it possible to incorporate dynamic dialogues (think chat and email histories) into knowledge management. Microsoft Teams and Copilot demonstrate this with features like meeting transcription, summary, and discussion. The further embrace of LLMs within knowledge management make it possible to unify information about what is happening in an organization and speed information retrieval. When information is easily accessible, many use cases open up, including enhanced engineering processes to revolutionizing educational methods and social science research.

#### AI Integration Challenges and Future Perspectives

The study underscores the sociotechnical nature of AI integration, where technology and human factors are deeply intertwined. Effective AI adoption is influenced by workers' perceptions and its alignment with existing workflows. Challenges in human-AI working, such as monitoring and takeover, are highlighted, emphasizing the need to mitigate risks like "moral crumple zones" where workers could unfairly bear the blame during technological failures. Furthermore, the study notes that AI adoption disparities follow traditional digital divides, impacting various jobs and emphasizing the need for innovation in job creation.

#### Lead Like a Scientist

The research review concludes with the advice to follow a scientific process towards leading through change. This includes continually adapting and learning in this rapidly evolving AI landscape. It also means developing hypotheses and metrics about how AI can impact an organization and doing experiments to test the hypotheses. Given the many ways the world of working has changed and will changed, it's imperative for Security to stay just as experimental as any other business function. Enabling safe testing of new capabilities and being mindful to the risks are key. Protecting the organization's assets and outcomes is critical to supporting the New Future of Work that is unfolding every day.

---

#### More than Half of Generative AI Adopters Use Unapproved Tools at Work

*https://www.salesforce.com/news/stories/ai-at-work-research/*

Salesforce interviewed 14,000 people across 14 countries about how they use AI at work. 28% of workers admit to using generative AI at work and 55% do so with unapproved tools. 32% of workers expect to use it soon. 79% of workers report ambiguous or unknown/non-existent AI Policies, with industries such as Healthcare lagging behind others.

![](../images\1706995649042)

#### How Google Uses AI for Automated Vulnerability Fixes

*https://research.google/pubs/ai-powered-patching-the-future-of-automated-vulnerability-fixes/*

Sanitizer bugs are found using specialized tools that check for out-of-bounds accesses to heap, stack, and global objects, as well as use-after-free bugs. These tricky to find, but lower priority vulnerabilities can pile up at large organizations such as Google. This Google Security Engineering Technical Report showcases how Google uses their Gemini LLM to automate bug fixing as part of a patching pipeline:

![](../images\1706995632267)

Steps 1-4 are automated, with specialized tooling to detect and test the fix as well as different machine learning models to find the right information to feed into the LLM for successful code generation. Google also found that the LLM selection to develop the fix is important, and requires fine-tuning and multiple prompt examples ("few shot prompting") in order to have useful results. In the end, a 15% success rate was all that was achieved. Against multiple thousands of bugs found every year, this is not insignificant, however there's plenty of room for growth.

#### Generative AI for Scaling Code Analysis and Threat Modeling

*https://betterappsec.com/how-automated-ai-code-analysis-can-scale-application-security-667002ad63c4*

Excellent write-up by _better appsec_ for how to use tools like ChatGPT, Github Copilot, or scripts hitting Generative AI endpoints to enable and accelerate application security programs. As the author eloquently explains, AppSec teams need to be experts on many technologies, their business-specific applications, and security concepts at a deep level. Generative AI helps them keep up with their business and scale their ability to help the organization publish secure code. There's a lot of valuable insights here, including example prompts and "Pro Tips" to really accelerate your AppSec workflows.

#### How AI Has Been Happening

*https://www.airstreet.com/blog/state-of-ai-report-5-years*If you want to understand all aspects of AI from Research to Industry to Government to where we might head next - the Annual _State of AI Report_ from Air Street Capital is a must-read. This blog entry tracks how the report has evolved over the past five years and has some great insights on where trends were spotted early as well as prediction that missed the mark.

#### EU AI Act Moves Closer to Law

*https://techcrunch.com/2024/02/02/eu-ai-act-coreper-vote/*The European Union's landmark regulation on Artificial Intelligence passed a key milestone this week as all 27 Member States approved the final text of the proposed law. It seems likely that the law will start to go into effect later this year with a phased roll out of provisions over the next two years. If you're interested in learning more about the proposed law check out _this GPT_ or _this overview_ from the IAPP.

#### CFOs: If You Want AI, do Data Governance and Cybersecurity first

*https://www.forbes.com/sites/shivaramrajgopal/2024/01/30/a-view-of-artificial-intelligence-ai-from-the-trenches/?sh=3489010d2693*An opinion article by a professor at Columbia Business School who speaks with many CFOs about their concerns with AI. Finance leaders are rightly concerned about the hype outpacing the value provided in these investments. They're also concerned that under-investment in data and security will hamper any innovative AI use cases. I disagree with his assessment that AI is mostly PR for most companies. The future of work information from Microsoft above applies universally to organizations large and small. The survey results from Salesforce shows that with or without leadership buy-in, Generative AI is a large and growing footprint in the business. And I think that small organizations are just as well positioned to take advantage of some of these things as large ones. In fact, companies which have less data to manage and secure will be the fastest to adopt AI holistically. What do you think?

#### Protect AI: Guardian

*https://protectai.com/press/protect-ai-announces-guardian*

Protect AI, a leader in AI and ML security, has launched Guardian, a groundbreaking tool that enforces security policies on ML models, particularly those from open-source repositories like Hugging Face. Guardian, building upon Protect AI's open-source tool ModelScan, identifies and blocks potentially malicious code in ML models. This innovation addresses the increasing security risks in the AI/ML sector, especially the threats posed by widely used open-source models. Guardian's capabilities extend beyond existing tools by offering advanced features like specialized scanners and integration with existing security frameworks.

---

### Have a Great Weekend!

![](../images\1706995609789)

---

_WTH is this email? (Recap)_

_Each week I get to talk with lots of clients, colleagues, and team members about fascinating topics at the intersection of cybersecurity, data, and AI. I’ve decided to share some of the fun. There’s so much going on in this space that impacts all of us. It’s exciting for me – and I hope you’ll be entertained too._

_You can now chat with the newsletter archive at \*\*https://chat.openai.com/g/g-IjiJNup7g-thinks-and-links-digest_
