# Microsoft-Foundry-AI-Agents-Foundry-IQ-MCP-A2A-Notes
This Repository contains my "Microsoft Foundry: AI Agents, Foundry IQ, MCP &amp; A2A" Course Notes from Udemy

**I) Foundry Primer and Fundamentals**

**A) Introduction to Generative AI and AI Agents**

**B) Introduction to Microsoft Foundry**

**C) Introduction to the Microsoft Foundry SDK**

**D) Difference Between Hub-Based and Standalone Foundry Projects**

**E) Lab: Deploying Microsoft Foundry in Azure Portal (Hands-On Lab)**

**F) Important: Github Repo for Demos!!**

**G) Lab: Deploying OpenAI Model and Foundry SDK Demo (Hands-On Lab)**

**H) Lab: Deploying Claude and Foundry SDK Demo (Hands-On Lab)**

**I) Lab: Microsoft Foundry Extension in VSCode (Hands-On Lab)**





# **I) Foundry Primer and Fundamentals**

# **A) Introduction to Generative AI and AI Agents**

The video begins with a quick look at generative AI and agents, setting the context for the entire course. It provides an introduction to how artificial intelligence has evolved over the years. Artificial intelligence itself is not new—humans have long been fascinated with building systems capable of replicating or even exceeding human intelligence. This journey began around 1956, when early researchers became ambitious about creating intelligent systems. In 1997, the term “machine learning” emerged, aiming to democratize the creation of models that data scientists could build for domain-specific use cases.

By 2012, the era of deep learning arrived. Deep learning enhanced machine learning by becoming more human-like, using neural networks structured similarly to neurons in the human brain. Training models using these neural networks allowed systems to learn in ways that closely resembled human learning. Then in 2021, the era we live in today began: the era of generative AI. Technologies like Copilot, ChatGPT, and Google Gemini gained the ability to create written, visual, and auditory content simply from user instructions.

Zooming out, two major shifts have taken place. First is the democratization of AI technologies. Anyone—not just data scientists—can interact with advanced AI systems using natural-language prompts such as “write an email,” “create an image,” or “edit this text.” Earlier, interacting with AI models required specialized skills, but today anyone can use them through intuitive interfaces. Second is the shift in model behavior. Before 2021, AI models were predominantly predictive. They were probabilistic models designed for tasks like forecasting house prices or predicting numeric outcomes using algorithms like linear regression. They were not built for natural language conversations.

Generative AI changed that. Today’s models are not the best at predicting future stock prices, but they excel at understanding user intent expressed in natural language and responding in the same language. Every generative AI application relies on a foundation: the Large Language Model (LLM). An LLM is a neural-network-based model that processes natural language input, analyzes intent, and generates output. These models consist of an input layer, many hidden layers that analyze different aspects of language, and an output layer. Models like GPT-4 are massive—for example, GPT-4 was trained on roughly 1.4 trillion parameters, highlighting the incredible computational scale required to build such systems. Because this is extremely resource-intensive, most companies cannot build such models from scratch. Instead, they rely on pre-built foundation models from providers like OpenAI and customize them for domain-specific use cases.

The term foundation model refers to a specific version or instance of an LLM—such as GPT-4, GPT-4.1, or Meta’s Llama models. Developers typically do not build these from scratch due to limited resources, expertise, and infrastructure. Instead, they fine-tune them for business requirements and integrate them into production environments. This tuning and integration is where most developers, including us, spend our time.

This brings us to AI agents. To understand agents, the video introduces the concept of compound AI systems—systems that accomplish tasks by combining multiple interacting components. When foundation models are adapted for specific business use cases, they become part of these compound systems. Agents are essentially applications within this ecosystem that not only use LLMs but also interact with tools, APIs, databases, or enterprise knowledge sources as part of their workflow.

Think of an AI agent as a system where the LLM makes planning decisions, unlike earlier systems that relied on rigid, hard-coded logic. An agent can use an LLM to dynamically determine sequences such as: Step 1, call an API; Step 2, fetch information from a knowledge base; Step 3, generate a response. The LLM becomes the “brain,” orchestrating tools, external systems, and workflows in real time. The more freedom the model has to decide the behavior of the system, the more “agent-like” the application becomes. However, there's ongoing debate about fully autonomous agents versus approaches that include human-in-the-loop mechanisms for safety and control. The course will explore how to build such agents and incorporate controlled oversight.

The industry’s journey over the last few years has been fast-paced. Initially, developers built simple chatbots powered by LLMs to mimic ChatGPT—tools that could compose emails or answer questions. But these chatbot-only systems offered limited business value since they performed no operational actions. That realization led to the rise of agentic systems. Organizations began integrating LLMs with individual tools or plugins, often with hard-coded execution flows. But soon they recognized that users interact in diverse ways, and rigid workflows couldn’t support dynamic needs. They needed systems capable of dynamic execution planning—systems that adjust steps based on the user's query instead of being locked into fixed logic. This shift led to today’s agentic AI development practices, where LLMs plan and orchestrate actions at runtime.

In summary, an AI agent consists of three essential components:

A foundation model (an LLM),

Instructions describing how the agent should behave, and

Tools such as APIs, databases, or plugins that extend the model’s abilities.

Together, they form a powerful system capable of understanding user intent, performing reasoning, leveraging enterprise knowledge, calling tools, and executing business logic dynamically. This forms the core of generative AI and agentic AI fundamentals, which sets the stage for the rest of the course.

# **B) Introduction to Microsoft Foundry**



# **C) Introduction to the Microsoft Foundry SDK**

# **D) Difference Between Hub-Based and Standalone Foundry Projects**

# **E) Lab: Deploying Microsoft Foundry in Azure Portal (Hands-On Lab)**

# **F) Important: Github Repo for Demos!!**

# **G) Lab: Deploying OpenAI Model and Foundry SDK Demo (Hands-On Lab)**

# **H) Lab: Deploying Claude and Foundry SDK Demo (Hands-On Lab)**

# **I) Lab: Microsoft Foundry Extension in VSCode (Hands-On Lab)**
