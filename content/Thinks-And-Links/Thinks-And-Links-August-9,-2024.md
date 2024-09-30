---
title: Thinks And Links August 9, 2024
draft: false
tags:
- AI
- Cybersecurity
- Large Language Models
- Data Privacy
- AI Security
- Generative AI
- AI Ethics
---

# Thinks and Links | August 9, 2024

![](../images\1679742887729)

#### BD&A - Thinks and Links

Big Data & Analytics - Thinks and Links | News and insights at the intersection of cybersecurity, data, and AI

![](../https://media.licdn.com/mediaD4E12AQFx5mJVmue16Q)

### Happy Friday!

#### Llama 3.1 - GPT-4 level intelligence available in open source

https://ai.meta.com/blog/meta-llama-3-1/

Meta recently released updates to their Llama family of Large Language Models to much fanfare. The open-source models provide longer context (e.g. how much information can go into the prompt) and measure the same against benchmarks compared to closed frontier models such as GPT-4o and Claude 3.5.

In a letter following the announcement, Meta CEO Mark Zuckerberg shared his rationale for why Meta is leaning in to Open Source:

Open-source AI is similar Linux and how it evolved into an industry standard

Open-source AI benefits include customization, cost efficiency, and security

Open-source AI is safer due to transparency and broader scrutiny, which helps prevent both unintentional and intentional harm.

Some are concerned about bad actors, hackers, and nation states having this capability too, but Zuckerberg's response is telling:

> Some people argue that we must close our models to prevent China from gaining access to them, but my view is that this will not work and will only disadvantage the US and its allies. Our adversaries are great at espionage, stealing models that fit on a thumb drive is relatively easy, and most tech companies are far from operating in a way that would make this more difficult. It seems most likely that a world of only closed models results in a small number of big companies plus our geopolitical adversaries having access to leading models, while startups, universities, and small businesses miss out on opportunities.

*Some people argue that we must close our models to prevent China from gaining access to them, but my view is that this will not work and will only disadvantage the US and its allies. Our adversaries are great at espionage, stealing models that fit on a thumb drive is relatively easy, and most tech companies are far from operating in a way that would make this more difficult. It seems most likely that a world of only closed models results in a small number of big companies plus our geopolitical adversaries having access to leading models, while startups, universities, and small businesses miss out on opportunities.*

![](../images\1723217001204)

So how good is Llama? I asked it to summarize some of the technical details for a Security audience. I then compared this to GPT-4o for good measure:

#### Llama 3.1

As a cybersecurity practitioner, here's a summary of the content relevant to your field:

Model Architecture and Training: The Llama 3.1 405B model was trained on over 15 trillion tokens using 16,000 H100 GPUs. The model architecture is a standard decoder-only transformer with minor adaptations, and the training process involved iterative post-training procedures, including supervised fine-tuning and direct preference optimization.

Security Considerations: The model was designed with safety in mind, and the training process included techniques to ensure the model provides maximally helpful answers while maintaining safety mitigations. The Llama system also includes components such as Llama Guard 3, a multilingual safety model, and Prompt Guard, a prompt injection filter.

Quantization and Inference: To support large-scale production inference, the models were quantized from 16-bit (BF16) to 8-bit (FP8) numerics, effectively lowering the compute requirements needed and allowing the model to run within a single server node. This could potentially reduce the attack surface by minimizing the amount of data being processed.

System Integration and Interoperability: The Llama system is designed to work as part of an overall system that can orchestrate several components, including calling external tools. The implementation of components in this Llama System vision is still fragmented, and the developers are working with industry, startups, and the broader community to help better define the interfaces of these components.

Potential security implications and areas for further exploration:

The use of quantization to reduce compute requirements could potentially introduce vulnerabilities if not properly implemented.

The integration of external tools and components could introduce new attack vectors if not properly secured.

The use of synthetic data generation and fine-tuning could potentially be used to create adversarial examples that could compromise the model's security.

The Llama System's reliance on standardized interfaces could potentially create a single point of failure if not properly secured.

Overall, the development of the Llama 3.1 405B model and the Llama System highlights the need for cybersecurity practitioners to be aware of the potential security implications of large language models and to work closely with developers to ensure the secure design and deployment of these systems.

#### GPT-4o

Summary for a Cybersecurity Practitioner:

Model Architecture:

Scale and Infrastructure: Llama 3.1 405B is the largest model yet, trained on over 15 trillion tokens using 16,000 H100 GPUs. This required optimizing the training stack for scalability and efficiency.

Design Choices: A standard decoder-only transformer architecture was chosen for stability, avoiding mixture-of-experts models. An iterative post-training process involving supervised fine-tuning and direct preference optimization was used to enhance data quality and model capabilities.

Data Quality: The new model benefits from improved data preprocessing and curation, enhancing both pre- and post-training data quality. This aligns with scaling laws, resulting in better performance than smaller models.

Quantization: To enable efficient large-scale inference, the model was quantized from 16-bit to 8-bit numerics, reducing computational demands and allowing for deployment on a single server node.

Instruction and Chat Fine-Tuning:

Enhanced Capabilities: The focus was on improving the model's helpfulness, instruction-following, and safety. Challenges included supporting a 128K context window and managing larger model sizes.

Alignment Process: The final chat models are refined through rounds of alignment, involving Supervised Fine-Tuning, Rejection Sampling, and Direct Preference Optimization. Synthetic data generation and filtering ensure high-quality fine-tuning data.

Balanced Performance: The model maintains high quality across all capabilities, including short-context benchmarks, while integrating safety mitigations.

The Llama System:

System Vision: Llama models are part of a broader system that orchestrates multiple components, including external tool integrations. The vision is to allow developers to create custom solutions beyond core LLM capabilities.

Responsible AI Development: A full reference system is being released, featuring components like Llama Guard 3 (a multilingual safety model) and Prompt Guard (a prompt injection filter). These open-source sample applications can be expanded by the community.

Standardization Efforts: The implementation of these components is still developing. A request for comment on GitHub introduces "Llama Stack," a set of standardized interfaces for building toolchain components and applications. The goal is to foster ecosystem growth and interoperability.

Community Engagement: Feedback is encouraged to refine the proposal, aiming to lower barriers for developers and enhance the platform's offerings.

#### The Bottom Line

I prefer the Llama 3.1 answer better than GPT-4o. I think the points it raised and the order presented are closer to natural writing. It tells you a bit more about where to focus and what's important. Of course, if you disagree with this approach you might prefer a more mechanistic summary like GPT-4o did. Either can be significantly improved with prompt engineering.

The availability of Llama 3.1, especially 405b, is an exciting development for researchers and product developers. It increases the number of people who can do innovative things with a frontier model. That will, in turn, increase the number of use cases and products built with AI that impact our daily lives and our businesses. AI's footprint will continue to expand. While there is talk in the media and in the financial markets of an "AI Winter" as some of the hype cools, the models, code, and cost structures keep pointing to more excitement ahead.

---

#### AI Shared Security Model

https://www.returnonsecurity.com/p/ai-security-shared-responsibility-model-navigating-risks-ai-deployment

Great post which introduces an AI Security Shared Responsibility Model similar to ones we've been sharing with clients. In this view, the model is used to clarify security responsibilities between AI service providers and businesses using AI systems. Having a way of clarifying which AI use case you are securing and the contour of its classification is important for security and for adaption. Different approaches have different features, benefits and risks. Here's how they classify it:

![](../images\1723217249223)

The framework is a good starting point for organizations to understand their security obligations when deploying AI systems and can help in decision-making processes based on an organization's capacity, budget, and risk appetite.

#### The Architects Guide to the GenAI Tech Stack

https://blog.min.io/the-architects-guide-to-the-genai-tech-stack-ten-tools/

I found this article to be helpful when thinking about the components of an in-house GenAI technology stack. If a company is looking to fully use the capabilities of GenAI alongside other AI/ML workloads, they'll need something from each category in this model. If organizations are using APIs to access external AI, some of these pieces will be what the model host is using. It's helpful to know and ensure all are considered in a security review of AI.

Components in this model and some example tools are:

Data Lake (AWS, GCP, Azure, MinIO)

OTF-Based Data Warehouse (Snowflake, Dremio, Starburst, Open Data Lakehouse, Microsoft Fabric)

Machine Learning Framework (PyTorch, TensorFlow)

Machine Learning Operations (MLRun, MLflow, Kubeflow)

Distributed Training (DeepSpeed, Horovod, Ray, Spark PyTorch Distributor, Spark TensorFlow Distributor)

Model Hub (Hugging Face)

Application Framework (LangChain, AgentGPT, Auto-GPT, BabyAGI, Flowise, GradientJ, LlamaIndex, Langdock, TensorFlow Keras API)

Document Processing (Unstructured, Open-Parse)

Vector Databases (Milvus, Pgvector, Pinecone, Weaviate)

Data Exploration and Visualization (Pandas, Matplotlib, Seaborn, Streamlit, PowerBI)

#### How a Prominent AI/ML/Security Researcher Uses AI

https://nicholas.carlini.com/writing/2024/how-i-use-ai.html

Nicholas Carlini has been an important figure in research into how to attack and thus defend AI. His work includes noteworthy topics such as:

Adversarial Machine Learning: Co-developed the Carlini & Wagner attack, a method for generating adversarial examples that can fool machine learning models which proved effective against various defenses.

Privacy Vulnerabilities: He has demonstrated that large language models, such as GPT-2 and GPT-3, can memorize and reproduce personally identifiable information from their training data. His work has shown similar vulnerabilities in generative image models like Stable Diffusion.

Model Stealing and Poisoning: He has also worked on attacks that allow for the extraction of training data from machine learning models and poisoning attacks that introduce malicious data into training datasets.

This is a guy that knows security and knows AI. So, his thoughtful and lengthy blog post on some of his AI workflows is a fun and very valuable read. Some of the use cases covers are:

Coding applications and making his code better, faster, simpler

Reading reference information about APIs

Automate boring tasks

Fixing errors

To learn new things

His post includes sample prompts and examples that are really helpful if you're looking for some fresh inspiration on getting the most out of these tools.

#### Replacing my Right Hand with AI

https://erikschluntz.com/software/2024/07/30/code-with-ai.html

Another blog on using AI, this time from the perspective of a developer with a broken hand. It is great walk through of all the ways life was improved while his hand was immobilized in a cast. The findings from his experience are also a reflection on where software development might be headed as models and tooling for software development improves. I liked this graphic:

![](../images\1723217298683)

The "AI Engineer" of the near future will be able to command an army of agents to perform specialized tasks and orchestrate the activity with pair programming with an AI that uses image and voice capabilities to act like a peer or a coach. They will work together to quickly solve for low-level code problems, think through complex architecture, and design considerations that require human focus. This setup doesn't replace humans in the software development process, but it leads to fewer people needed and higher personal productivity. The first engineers who master this toolset will create a lot of value for themselves and the companies they work for. The engineers who ignore this, do so at their own peril.

---

### Have a Great Weekend!

![](../images\1723217322966)

@dharmesh on Twitter

---

📫 Subscribe to Thinks & Links direct to your inbox

*You can also chat with the newsletter archive at **https://chat.openai.com/g/g-IjiJNup7g-thinks-and-links-digest*