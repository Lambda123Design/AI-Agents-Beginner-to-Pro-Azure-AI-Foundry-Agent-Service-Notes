# AI-Agents-Beginner-to-Pro-Azure-AI-Foundry-Agent-Service-Notes

**Table of Contents:**

**I) Intro to AI Agents:**

**A) Introduction to AI Agents**

**B) What is Agentic AI ?**

**C) Demo: AI Agents**

**D) What are AI Agents?**

**E) How an AI Agent Works ?**

**F) Use Cases of AI Agents in the Real World**

**II) Azure AI Foundry Basics (For Absolute Beginners)**

**A) Introduction to Azure AI Foundry**

**B) What is Azure AI Foundry?**

**C) Architecture of Azure AI Foundry**

**D) Projects vs Hubs**

**E) How It Differs from Azure OpenAI Service**

**F) Navigating the Azure AI Foundry Portal**

**G) Demo: Create a Hub & Project**

**H) Model Benchmarks**

**I) Acesss Playgrounds via Foundry**

**J) Management Centre**

**III) Assistants API - A Refresher**

**A) Title Intro - Assistants API**

**B) Introduction to Assistants API**

**C) What is Assistants API ?**

**D) Assistants API Component / Key Terms**

**E) Assistants API Architecture**

**F) What is Function Calling ?**

**G) Demo: FC: Python Code : Function Calling Intro**

**H) Demo: FC: Python Code: Get an API Key from openweathermap.org**

**I) Pre-Req Setup azureopenai.env**

**J) Demo: FC : Python Code : Initialise and Set the Environment**

**K) Demo: FC : Python Code : Instantiate the Client Object of Azure OpenAI**

**L) Demo:FC : Python Code: Define the get_weather Function**

**M) Demo: FC: Python Code: Define the tools list required for the Assistants API**

**N) Demo: FC_ Python Code : Create an Assistant & Thread**

**O) Demo: FC:Python Code: Create a function for running the conversation**

**P) Demo: FC: Python Code: Take the User input and show result**

**IV) Azure AI Agent Service**

**A) Intro to Azure AI Agent Service**

**B) What is Azure AI Agent Service?**

**C) Architecture of Azure AI Agent Service**

**D) Assistants API Vs Azure AI Agent Service**

**E) Model & Region Support**

**F) Quotas & Limits**

**G) Azure AI Agent Service Pricing**

**H) Demo: Create a Hub & Project**

**I) Demo: Create an Agent via Azure Foundry**

**J) Demo: Understand the various Knowledge & Action Tools**

**K) Demo : Get a Response to your prompt via the Agents Playground**

**V) Understanding Azure SDK for Python**

**A) Introduction to Azure SDK for Python**

**B) What is Azure AI Projects client library for Python**

**C) Demo: Create VSCode Environment & setup Azure-CLI**

**D) Execute the Sample Code**

**E) Understand the Workflow for Agent Creation**

**F) Demo: Create Azure AI Project via Azure AI Foundry**

**G) Demo: Create Entra ID Application & Grant Contributor access**

**VI) Azure AI Agent Service Action Tools- Function Calling**

**A) Intro to Function Calling**

**B) Demo: Create a new Deployment inside Project**

**C) Demo: Understand the Workflow for Weather Agent**

**D) Demo : Understand the Environment Variables**

**E) Demo : Install Libraries and Setup Enviornment**

**F) Demo: Understand the Get_Weather Function**

**G) Demo: Calling your Azure AI Agent**

**VII) Azure AI Agent Service Action Tools - Code Interpreter**

**A) Intro to Code Interpreter**

**B) What is Code Interpreter ?**

**C) Understand the Input Data - sales_data.csv**

**D) Demo: How to use CI in Agents Playground**

**E) Demo: Understand the Workflow for Graph Generator Agent**

**F) Demo: Upload the sales_data.csv & Environment variables file**

**G) Demo:Understand the Creation of Agent**

**H) Demo: Create Thread and Message Convesation**

**I) Demo: Run the Agent & Create Graphs**

**VIII) Azure AI Agent Service Action Tools - OpenAPI 3.0**

**A) What is OpenAPI 3.0 ?**

**B) Understanding the Workflow for Yahoo Finance**

**C) Demo: Create RapidAPI Key**

**D) Demo: Create a Connection to RapidAPI in Azure**

**E) Demo: Create a Stocks Agent and Attach OpenAPI 3.0**

**F) Demo: Test the Stocks Agent in Playground**

**G) Demo: Install the Libraries and Setup Environment**

**H) Authenticate/Initialize/ Load OpenAPI Spec**

**I) Get Connection / Create Auth Object / Create OpenAPI Tool**

**J) Create Agent / Thread / Conversation Loop**

**K) Execute the Program and run Queries**

**IX) Azure AI Agent Service Knowledge Tools - Bing Search**

**A) Intro to Grounding with Bing Search**

**B) What is Grounding with Bing Search ?**

**C) Demo : Create a Bing Search with Agent Service**

**D) Demo: Create a Bing Resource & Create Connection**

**E) Demo: Setup environment & install libraries**

**F) Demo: Understand the Code**

**G) Demo: Execute the Code**

**X) Azure AI Agent Knowledge Tools - File Search**

**A) Intro to File Search**

**B) What is File Search ?**

**C) Demo: Utilize File Search with AI Foundry**

**D) Demo: Understand the workflow**

**E) Demo: Install Libraries & Setup Environment**

**F) Demo: Initialise the Project Client & Upload the File**

**G) Demo: Create Vector Store / Agent**

**H) Demo: Create Thread and Process Messages**

**I) Demo: Run the Code and ask Questions**

**XI) Azure AI Agent Knowledge Tools - Azure AI Search**

**A) Intro Azure AI Search**

**B) What is Azure AI Search ?**

**C) Understand the Workflow**

**D) Demo: Create a Storage Account & Upload Document**

**E) Demo: Ensure / Create you have Azure OpenAI Service**

**F) Demo: Create Embeddings Deployment**

**G) Demo: Create Azure AI Search Resource**

**H) Demo: Create an Index**

**I) Demo: Create an Agent & Attach the Knowledge Tool**

**J) Demo: Run Queries in Agents Playground**

**K) Demo: How to use AI Search in Python Code**

**L) Demo: Install Libraries and Setup Environment**

**M) Demo: Initialise the Project Client**

**N) Demo: Create Agent**

**O) Demo: Execute the Code**

**XII) Real World Scenario - Freshdesk Agent**

**A) Understand the Workflow and what we shall Build**

**B) Create a login on freshdesk & Setup API Key**

**C) Install Binaries & Setup Environment**

**D) Understand the Custom Function create_freshdesk_ticket**

**E) Initialize Azure AI / Create toolset**

**F) Create the Freshdesk Agent**

**G) Execute the Program and Check the Tickets**

**XIII) Real World Scenario - Streamlit Application**

**A) What is Streamlit ?**

**B) Demo: Testing some Simple Sample Apps**

**C) Setup a Virtual Environment in VSCode & Install Requirements**

**D) Setup the Environment File**

**E) Understand the Streamlit Configuration**

**F) Understand the Freshdesk Ticket Creator**

**G) Demo: Executing the Code & Running Prompts**






# **I) Intro to AI Agents:**

# **A) Introduction to AI Agents**

This module introduces AI agents, focusing on their fundamentals, capabilities, and real-world applications. It covers Agentic AI, clarifying common misconceptions, and provides a simple demo to illustrate how an AI agent works. The session will define AI agents, highlight their key characteristics, and use a practical example—like Netflix or Amazon Prime’s recommendation system—to explain how AI agents function under the hood. Finally, the module will explore various real-world use cases across industries.

# **B) What is Agentic AI ?**

This lesson explains the difference between non-agentic AI (zero-shot AI) and Agentic AI.

Non-agentic AI works in a single step: it generates output immediately without planning, reviewing, or refining. A real-life analogy is a student writing an exam essay without outlining or checking for errors—fast but potentially shallow or error-prone.

Agentic AI follows a step-by-step, iterative workflow, improving output as it goes. For example, when writing an essay, it first creates an outline, gathers data, drafts, reviews for mistakes, and then finalizes a polished version. The analogy is a student drafting, revising, and refining an essay.

Key takeaway: Non-agentic AI is quick but less precise, while Agentic AI is structured, iterative, and produces more refined results.

# **C) Demo: AI Agents**

This section provides a real-world demo of an AI agent using a robotic vacuum cleaner as an example. The human gives a command (via app or button), and the vacuum autonomously makes decisions:

It avoids obstacles and cleans accessible areas.

It detects unsuitable surfaces (like carpet when mopping) and adjusts its actions accordingly.

Key takeaway: An AI agent can perceive its environment, make decisions, and act autonomously to achieve a goal.

# **D) What are AI Agents?**

This lesson explains AI agents, their definition, key characteristics, and examples:

Definition: An AI agent is a system that observes its environment, makes decisions, and takes actions autonomously to achieve specific goals, without requiring constant human intervention. It can range from simple rule-based bots to advanced machine learning systems.

Key Characteristics:

Autonomous: Operates independently, e.g., robotic vacuum cleaners.

Reactive & Proactive: Responds to changes and takes initiative, e.g., smart thermostats.

Goal-Oriented: Designed to achieve specific objectives, e.g., chess-playing AI.

Adaptive: Learns from experience to improve performance, e.g., Netflix recommendation system.

Interactive: Communicates with humans or other systems, e.g., Alexa or Siri.

Examples of AI Agents: Chatbots (like ChatGPT), recommendation systems (Netflix), autonomous vehicles, and AI assistants (Alexa, Siri).

Key takeaway: An AI agent is a smart, interactive, and adaptive system that acts autonomously to achieve goals by perceiving, deciding, and acting in its environment.

# **E) How an AI Agent Works ?**

This lesson explains how AI agents power recommendation systems, using Netflix/Amazon Prime as an example:

User Profiles & Preferences: Each user has a profile storing their viewing history and genre preferences.

Metadata Store: Contains details about movies (title, genre, year, description).

AI Agent Role: Acts as the coordinator, pulling user preferences, matching them with metadata, and deciding which movies to recommend.

Large Language Model (LLM) Role: Once movies are selected, the LLM generates a personalized, engaging email or message for the user (e.g., subject lines, friendly tone).

End-to-End Workflow: The AI agent integrates the selections and email content, then delivers the recommendations autonomously.

Key takeaway: AI agents combine user data, metadata, and LLMs to generate personalized, automated recommendations without human intervention.

# **F) Use Cases of AI Agents in the Real World**

This lesson explores real-world applications of AI agents across industries:

Customer Service & Personalization:

Hyper-personalization: Recommend products/services based on user preferences (e.g., Netflix).

Intelligent call routing: Direct calls to the right department.

Customer feedback analysis: Identify positive/negative trends to improve services.

AI-driven CRM: Automate data entry and suggest optimal follow-up times.

Smart agent profiling: Categorize customers for targeted offers.

Chatbots with human touch: Handle routine queries, escalate complex issues.

Finance & Banking (FSI):

Fraud detection: Spot suspicious transactions.

Anti-money laundering: Track unusual transactions.

Risk management: Predict financial risks and flag risky loans.

Credit scoring: Evaluate creditworthiness for loans.

Trading: Predict stock market trends and recommend trades.

Healthcare:

Training: Assist in medical education.

Research & data analysis: Identify disease links and trends.

Treatment recommendation: Suggest therapies for patients.

Wellness & early detection: Monitor health and detect diseases early.

Decision support: Assist doctors in making informed decisions.

Retail & E-commerce:

Enhance shopping experience with AI-powered chatbots.

Product recommendations based on past purchases (e.g., Amazon).

Key takeaway: AI agents are versatile and can improve efficiency, personalization, decision-making, and predictive capabilities across multiple industries.

# A Reference from Mayank Video - Understanding Automation, AI Automation, and AI Agents:

Topic: Understanding Automation, AI Automation, and AI Agents

1. Automation (Rule Follower)

Definition: Executes predefined steps exactly as programmed.

Characteristics: Rigid, consistent, deterministic, not adaptive.

Examples:

Coffee machine brewing at 7 AM every day.

Garden watering system operating regardless of rain.

CRM sending the same “Thank You” email for every signup.

Key Point: Good for routine, repetitive tasks but cannot adapt to changing conditions.

2. AI Automation (Smart Executor)

Definition: Automation enhanced with AI for smarter, personalized outputs.

Characteristics: Predefined workflow but outputs are dynamic, personalized, context-aware.

Examples:

AI-powered coffee machine adjusting strength based on user preference.

AI sending customized thank-you emails or recommendations.

Watering system that generates AI reports based on soil data.

Key Point: Still follows steps but improves efficiency and output using AI insights. Not fully autonomous.

Example: Coffee Machine Asks, "Do you want stronger coffee today" and alters receipe; 

Professional: Lead Capture Workflow that uses GPT to write thank-you emails

3. AI Agents (Autonomous Decision Makers)

Definition: Autonomous systems that make decisions, adapt, and use tools to achieve goals.

Characteristics: Dynamic, human-like reasoning, adaptive, can use multiple tools and memory, highly flexible.

Examples:

Garden AI agent adjusting watering based on weather, soil, plant type, and growth stage.

Coffee assistant checking calendar, adapting brewing schedule and strength.

Professional AI agents deciding whether to send an email, schedule a meeting, or draft messages.

Personal: Assistant checks your calendar, if you have a busy day it makes stronger coffee, if Saturday it asks even if we want a coffee

Professional: Instead of always sending the same email, agent decides, Should I send an email, schedule a meeting or draft a LinkedIn Message

Key Point: Acts like a digital human, makes independent decisions, highly adaptive, goes beyond AI automation.

Comparison Table
Feature	Automation	AI Automation	AI Agent
Flexibility	None	Medium	High
Decision-making	Fixed rules	Fixed rules + AI output	Autonomous & adaptive
Output	Static	Smarter, personalized	Dynamic, context-aware
Example	Scheduled email	AI-generated customized email	Agent decides how and when to respond based on context

Evolutionary Path:

Automation: Step-by-step rule-based execution. Predictable, repetitive, minimal variance.

AI Automation: Adds intelligence for smarter outputs while keeping process fixed.

AI Agents: Fully adaptive, autonomous, context-aware, and capable of using multiple tools to achieve goals.

Key Takeaways:

Automation: “Do exactly as instructed.”

AI Automation: “Do as instructed but smarter.”

AI Agents: “Understand the goal and figure out the best way to achieve it independently.”

# **II) Azure AI Foundry Basics (For Absolute Beginners)**

# **A) Introduction to Azure AI Foundry**

Welcome to the module on Azure AI Foundry.

Now, if you are a beginner in the field of generative AI and are looking to learn about agents, I would definitely recommend that you check out my course in the Udemy catalog: Generative AI Beginner to Pro with OpenAI and Azure OpenAI. This course will take you from being a beginner to a pro in the field of Azure OpenAI.

The thing with Azure AI Foundry is that it has its history with the Azure OpenAI service. Initially, Microsoft offered the Azure OpenAI Studio, then they introduced AI Studio, and eventually rebranded it as Azure AI Foundry.

If you are new to this, I suggest going through this series of lectures. If you already have experience, you may feel free to skip certain sections. In these lectures, I will talk about the architecture of Azure AI Foundry, explain what a project is, what a hub is, and how it differs from the Azure OpenAI service.

We will explore how things have changed if you’ve been using the Azure OpenAI service and are now transitioning to Azure AI Foundry. Additionally, we will see how you can navigate the Azure AI Foundry portal and understand key differences. Did you know that you can use the Azure OpenAI service with or without a project?

We will also do some hands-on demos. We’ll create a hub, set up projects, and explore model benchmarks where you can compare different models available in the Foundry.

Furthermore, we’ll take a look at the various playgrounds that Microsoft provides, such as the chat playground and the agents playground, all accessible via the Foundry.

Finally, we will discuss the management center, which is crucial for governance and management of hubs and projects. I look forward to seeing you in the lectures!

# **B) What is Azure AI Foundry?**

Now, the thing with Azure AI Foundry is that it has its own history. Microsoft has transitioned a lot over time. It all goes back to the days when Microsoft made a deal with OpenAI, agreeing to make the Azure OpenAI models available inside Azure.

Initially, we had the concept of Azure OpenAI Studio. Later, Microsoft introduced AI Studio, putting significant development effort into it so developers could work on AI projects using specific services. Even that didn’t fully meet their needs, so they eventually came up with Azure AI Foundry.

The word “foundry” is important. In English, a foundry is a factory where metal is melted and poured into molds to produce machine parts. Similarly, Azure AI Foundry is a platform where you can use AI models to build your projects.

Another important aspect is that Foundry isn’t limited to Azure OpenAI models. Microsoft has integrated a variety of models, including Meta’s LLaMA and DeepSeek, making these accessible within the platform.

Azure AI Foundry is a trusted platform that empowers developers to drive innovation safely, securely, and responsibly. Safety and security are core priorities, making it a reliable choice for organizations developing AI solutions. While it is still part of Azure, it operates on a dedicated domain accessible via ai.azure.com, separate from the main Azure portal.

The platform provides a model catalog, offering foundational, open-source, task-specific, and industry-specific AI models. For example, you can access OpenAI models, DeepSeek, or Meta LLaMA, depending on your project requirements.

Azure AI Foundry also integrates seamlessly with developer tools like Copilot Studio, Visual Studio, GitHub, and the Azure AI Foundry SDK. The SDK allows you to easily port different models between your projects—for example, switching from an OpenAI model to LLaMA or DeepSeek.

The platform includes core AI services such as Azure OpenAI Service, AI Search, and the new Azure AI Agent Service. Microsoft considers 2025–2026 as the era for AI agents, and the Foundry is built to support this focus. Additionally, it provides AI content safety, customization, and governance features. You can fine-tune models, perform evaluations, and ensure compliance and responsible AI usage.

In summary, Azure AI Foundry is a comprehensive platform that combines model access, developer tools, AI services, and enterprise-grade governance in one place.

In the next lecture, we will explore the architecture of Azure AI Foundry in detail.

# **C) Architecture of Azure AI Foundry**

Back in December 2024, at Microsoft Ignite, Azure AI Foundry was officially introduced by Satya Nadella. The architecture highlights several important components, including the developer tools (IDEs), the model catalog, and observability. Let’s explore each of these components in detail.

Azure AI Foundry is a platform that provides access to a variety of AI models—not just OpenAI models but models from other vendors as well. It offers AI models, services, and integrations to help developers build, customize, and deploy AI-powered applications.

Starting with the left side of the architecture, we have the Azure AI Foundry development tools. These integrate seamlessly with popular development environments and tools. First, there is Copilot Studio, which is used to build AI-powered copilots. Then, we have Visual Studio, Microsoft’s popular integrated development environment (IDE). GitHub is also included, offering version control and collaboration for AI projects. Most importantly, there is the Azure AI Foundry SDK, a software development kit that allows developers to interact with AI models and services. The SDK is versatile and can be used across many different AI models, opening up a wide range of possibilities for AI developers.

Next, we move to the model catalog, which is a core component of Azure AI Foundry. The model catalog includes several types of models:

Foundation models: General-purpose AI models that can be applied to a variety of tasks.

Open-source models: Pre-trained models from the open-source community, such as Meta LLaMA and DeepSeek.

Task-specific models: AI models designed for specific use cases. Many of these are available in the model catalog to address particular tasks.

Industry models: AI solutions tailored for specific industries, allowing developers to leverage domain-specific capabilities.

The core AI services form the backbone of Azure AI Foundry. Previously, the Azure OpenAI service was a standalone offering, but now it has been integrated into the Foundry. Through the Azure OpenAI service, developers have access to OpenAI’s large language models, such as GPT-4 and upcoming models.

Other key services include Azure AI Search, which provides intelligent search and indexing capabilities, and the Azure AI Agent Service, which helps create AI agents that can automate tasks and workflows—an increasingly important focus for 2025–2026. Additionally, Azure AI Content Safety provides tools to ensure responsible AI usage by filtering harmful or inappropriate content.

Finally, we have the observability layer, which includes evaluations, customization, governance, and monitoring.

Evaluations involve assessing the performance of different AI models.

Customization allows fine-tuning models to meet specific project needs.

Governance ensures compliance, security, and responsible AI usage.

Monitoring tracks AI performance and identifies potential issues.

This observability layer provides transparency, continuous monitoring, and ongoing improvement of AI applications.

Overall, this comprehensive architecture highlights the beauty and power of Azure AI Foundry, combining models, services, developer tools, and governance into one cohesive platform.

# **D) Projects vs Hubs**

Another key aspect you need to be aware of when studying Azure AI Foundry is the concept of projects and hubs. When working on AI projects, these are two components you will always use. A hub acts as a container, and inside it, you have projects. Think of it like this: the hub is the outer container, and the projects are the items inside it.

Hubs serve as a central AI governance and management layer across multiple projects. They facilitate the sharing and reuse of AI assets, which could include models, datasets, or even prompts. This makes hubs particularly valuable for organizations managing multiple AI projects. Before you create a project, you must first create a hub, highlighting their interdependency. Hubs provide a collaborative environment for teams to share project work, model endpoints, compute resources, data connections, security settings, and governance policies.

Once a hub is created, you can create a project within it. Projects are designed for developing and managing AI models and workflows. For example, if you want to use a model such as LLaMA, DeepSeek, or an Azure OpenAI resource, you must access it through a project. A project serves as a workspace for experimenting, fine-tuning, and deploying AI models. It is essentially your entry point for interacting with Azure AI Foundry.

Projects also support integration with various AI services, data sources, and pipelines. For instance, if you want to use Azure AI Search, you can do so through your project. Projects are ideal for managing the full AI development lifecycle, from experimentation to production. You can start small, test and fine-tune models, and then transition seamlessly to production.

Finally, AI projects group components for model customization, orchestrate workflows, and isolate data and access, ensuring secure and organized development. Hubs and projects together provide a robust framework for managing AI resources efficiently.

Don’t worry if this feels a bit confusing at first—I will demonstrate all of this in a proper demo in the upcoming lectures.

# **E) How It Differs from Azure OpenAI Service**

Another key area where many folks get confused is how to use the Azure OpenAI service with AI Foundry.

Microsoft has clarified that using a project and a hub is not mandatory if you are only interested in the Azure OpenAI service. If you remember the architecture of Azure AI Foundry, the Azure OpenAI service was shown as a separate component. This means you don’t need a project if your goal is solely to access Azure OpenAI models.

Using Azure OpenAI service without a project allows you to directly go to Azure OpenAI through Azure AI Foundry. The primary focus here is to provide access to Azure OpenAI models, allowing users to deploy, fine-tune, and manage these models directly.

However, if you use Azure OpenAI service with a project, it becomes part of a broader platform. This setup focuses on end-to-end tooling to build generative AI applications and integrates with multiple AI services. For example, if you also want to use Azure AI Search or work with models like Meta Llama from various providers including Azure, OpenAI, Microsoft, Cohere, or Nvidia, then a project setup is recommended.

When using a project, the platform provides features like a model catalog, fine-tuning and deployment options, and access to all Azure OpenAI models as well as models from other providers. This setup offers a comprehensive suite of tools for building, testing, and deploying AI applications.

In terms of usage, if your focus is exclusively Azure OpenAI, you can skip the project and start developing individually. But if you are exploring multiple models and AI services, using a project provides enterprise-grade features like access management, private networks, and a unified interface for managing different AI resources and projects. It also allows you to leverage the SDK to work on multiple models efficiently.

In summary, if your goal is solely to use Azure OpenAI service, you can do so without a project. But for broader AI development with multiple services and models, creating a project in Azure AI Foundry is the better approach.

# **F) Navigating the Azure AI Foundry Portal**

This video is designed to demystify how to access the Azure AI Foundry.

This topic often confuses many folks because when you go to Portal.azure.com, you can see the Azure AI Foundry resource. Clicking on it takes you to the Foundry, but it may show that it cannot find any resources. From here, you could create a hub or a project, but we’re not going to do that for this lesson.

In the theory lesson, I explained that Microsoft has created a subdomain specifically for Azure AI Foundry, called ai.azure.com. Opening this domain takes you directly to the Azure AI Foundry interface.

Here is where it gets interesting. The page highlights options like “Jump start your AI journey”, finding the ideal model for your business needs, and tinker, tweak, customize to achieve your goals.

The first option is Jump start your AI journey. Clicking this opens a model catalog with a wide variety of models, such as Deep Seek, O3, Mini, GPT, and more—all under one umbrella.

If you are only interested in Azure OpenAI, there is an option to focus specifically on the Azure OpenAI service. Clicking this filters the model catalog to show only OpenAI models, excluding others like Llama or Deep Seek. This organization makes it easier to navigate and access what you need.

You will also notice a connected resource. This shows your Azure OpenAI resource that is already created and linked to your Foundry. You can see all Azure OpenAI models, with no other models included.

There are also concepts like playgrounds and tools, which are shared resources that help with deployments, quotas, and testing. Some older videos may show previous versions of Azure OpenAI Studio, but the concepts remain the same, even if the interface looks slightly different.

In the chat playground, you can type requests and test the models. You first need to create a deployment to use the chat playground effectively.

Other features include assistants API, which is the backbone for creating Azure AI agents (covered in upcoming lectures), real-time audio, image generation like DALL-E, completions, and other shared resources.

In summary, this video demonstrates how to access your Azure OpenAI service from Azure AI Foundry, navigate the model catalog, and understand the available tools and playgrounds.

# **G) Demo: Create a Hub & Project**

This lecture explains how to create your project and hub in Azure AI Foundry, which is actually quite straightforward.

As mentioned before, if you go to Portal.azure.com, you can access the resources inside the Foundry. However, if nothing is installed yet, it may show “no Azure AI Foundry to display.” The recommended approach is to access the Foundry via ai.azure.com.

Once you’re on ai.azure.com, you can create a project. This is important because it allows you to customize many aspects. You can either accept the default settings and simply click Create, or provide your own names. For example, you might name your project “Azure Foundry Project”.

Next, you’ll specify the hub name, e.g., Azure AI Hub, select the subscription, and choose a resource group. You can either use an existing resource group or create a new one. You can also choose the location, which defaults to a region like Sweden Central.

You then have the option to connect an Azure OpenAI service. You can either create a new Azure OpenAI service or connect an existing one. The same applies for Azure AI Search—you can create a new resource or connect an existing one. After clicking Next, you’ll review your choices, including project name, subscription, resource group, and location.

Clicking Create will start the creation of your resources. Within a few minutes, the following resources will be created:

Azure Foundry Project – your project.

Azure AI Hub – a hub can contain multiple projects.

Storage Account – used for data uploads and storing artifacts created by Azure AI.

Key Vault – stores connection strings for external resources managed within Azure AI.

After creation, you can view your hub and project in Portal.azure.com. Clicking the hub allows you to launch Azure AI Foundry, view users, models, endpoints, connected resources, and compute resources. This is essentially the global settings for your hub.

Similarly, clicking the project allows you to launch the studio, which provides an interface very similar to ai.azure.com. From here, you can access your model catalog, playgrounds, services, and agents, and manage them as needed.

It’s important to note that if your work is limited to Azure OpenAI resources or models, creating a project and hub is not necessary. However, if you plan to use other models like Meta Llama or Deep Seek, it is mandatory to go through the Azure AI hub and project in the Foundry.

# **H) Model Benchmarks**

Another key feature of the Foundry is the model benchmarks.

Earlier, we looked at the model catalog, which contains a wide variety of models—not just Azure OpenAI or ChatGPT models (like GPT-0103), but also models from Meta, Microsoft, Deep Seek, and others. The model benchmark feature allows you to compare the performance of these models.

Inside the Foundry, in the model catalog, you’ll see an option to “Compare with benchmarks”. If new model benchmarks are available, you can select them here. The Foundry will automatically pick some popular models for comparison, and you can also add more models manually.

On the comparison screen, you’ll see various metrics like quality index and cost (USD per 1 million tokens, where lower is better). For example, the Llama model may appear with a certain quality score and cost score. The benchmark even provides rankings based on quality and cost—for instance, a model might rank fourth in quality and tenth in cost.

You can also switch to a list view, which shows all relevant metrics like accuracy, coherence, fluency, and more. This is useful if you prefer a table format over graphs.

Clicking on a specific model, like GPT-4, shows a detailed comparison against other models such as Mistral 5.3, GPT-3.5, and Llama 3.2. Various benchmarks are displayed, including AI quality index, estimated cost, latency, throughput, and generated tokens.

AI Quality: Higher is better. GPT-4 typically ranks at the top.

Cost: Lower is better. Llama models are strong performers here.

Throughput and Generated Tokens: Higher is better. Both GPT and Llama models perform well.

Overall, this feature allows you to compare different third-party models before deciding which one to use. Reviewing benchmarks can help you make an informed choice based on quality, cost, and other performance metrics.

# **I) Acesss Playgrounds via Foundry**

In this video, we will take a look at how to deploy a model inside your Azure AI Foundry and then use it within the playground.

Once you have created or deployed a project, click on your project—for example, Azure Foundry Project. Then navigate to the model catalog. As mentioned earlier, there are many models available.

Let’s say we are interested in a more recent OpenAI model like O3 Mini. To deploy it, simply click on Deploy. Note that some newer models, like O3 Mini, require registration and access.

If registration is required, you can choose a slightly older model, like O1 Mini. Here, you can create a new deployment, for example naming it O1 Mini New. Set the deployment type (e.g., Global Standard and REST), check the model version (e.g., 12th September 2024), and verify your project and capacity (e.g., 1 million tokens per minute). Select the region (e.g., East US 2) and click Deploy.

Once deployed, the system will display the endpoint and the API key needed for authentication. You can now access this deployment in the playground.

To do this, either select the deployment directly from the catalog or go to Assets → Models and Endpoints. You will see your deployed model, for example, O1 Mini New. Clicking Open in Playground allows you to interact with the model.

For instance, you can ask questions like “Who is the PM of India?” The model responds based on its knowledge. In this example, it returned: “As of 2023, Narendra Modi is the Prime Minister of India.”

This demonstrates how to deploy a model and use it through the Azure AI Foundry playground.

# **J) Management Centre**

It's now time to talk about another key artifact of Azure AI Foundry, which is the Management Center.

The Management Center is part of the Azure AI Foundry portal and is designed to streamline governance and management activities. From here, you can manage hubs, projects, resources, and settings within the Foundry.

To visit the Management Center, open your Azure AI Foundry project and select Management Center from the left menu. First, click on Launch Studio to enter your project interface. Once inside, the Management Center option will be available.

Within the Management Center, you can manage hubs and projects. You can create additional hubs, create new projects within those hubs, and view all hubs and projects you have access to. The left menu allows you to navigate hub and project sections to manage individual items.

For example, selecting All Hubs and Projects displays the names of your hubs and projects. You can also view quotas and request additional quota if needed. Each hub or project has a subsection where you can click Details or Overview to see information about users, models, endpoints, and connected resources. These connected resources will be particularly useful during coding and development tasks.

The Management Center also allows you to manage resource utilization, including quotas and usage metrics across multiple hubs and Azure subscriptions. The Quota link in the left menu lets you view and manage quotas efficiently.

Additionally, you can govern access through the Management Center. By selecting Users, you can manage access for both hubs and projects. You can assign roles, manage users, and ensure that all settings comply with organizational standards.

Overall, the Management Center is a critical feature for governance, resource management, and access control within Azure AI Foundry.

# **III) Assistants API - A Refresher**

# **A) Title Intro - Assistants API**

Just an Intro music of "Intro - Assisstants API"

# **B) Introduction to Assistants API**

Hello and welcome to the series of Lectures on Assistance API.

Now why have I included Assistance API as part of my Agents course? That would be the question that would be coming to your mind.

The reason for that is because the Agent service is actually based on top of the Assistance API. You can think of it in this way — the Assistance API forms the foundation or the foundational layer for the Agent service.

Now, the thing is, with the Assistance API, this is something that was actually given by OpenAI. OpenAI came up with the Assistance API where they introduced the concept of tools, where they said you could use function calling, you could use file search, and so on.

To give you a perfect example — with function calling, they understood the importance that our models are trained up to a certain level. But what if we give the capability for the model to talk to third-party APIs? For example, if I say, “What’s the weather like in London today?”, the model can actually interact with the OpenWeatherMap API.

These are the kinds of capabilities provided by the Assistance API. That’s why it’s very important to understand what an Assistance API is, its key components, and the terms that we use — things like threads and messages. You’ll notice that the same terms are used for the Agent service as well. That’s where it becomes very important to understand the architecture.

In this series of lectures, you will see complete Python code where we will explore how to use function calling with the Assistance API. We will actually create an API key in OpenWeatherMap and see how function calling can perform the same action — for example, fetching the current weather in London.

The LLM itself is not trained to provide this information, but now it can interact with a third-party API, such as OpenWeatherMap, to retrieve it.

Another reason for including this topic is that Microsoft mentions that when you use the Agent service, you can think of it as a wrapper built on top of the Assistance API. This means you have to write much fewer lines of code.

So I believe this would be a perfect opportunity for you to compare the code — what we will build with the Assistance API, and how it looks when implemented using the Agent service.

I’m sure this will be an interesting and valuable series of lectures.

# **C) What is Assistants API ?**

So let's dive straight into the topic of Azure OpenAI Assistants API.

Right. So the Assistants API is designed to help developers build powerful AI assistants. As the name suggests, with the Assistants API you are creating your own assistants.

Now, the best thing to understand is — if you think about a human, right? People like managers often have human assistants or personal assistants who help them with their work. In the same way, applications can create AI assistants.

So, in the coming future or in the coming months or years, you will see applications start deploying many small AI assistants. This is where the Assistants API becomes really important.

It enhances the developer experience. First of all, remember that it simplifies the creation of sophisticated, copilot-like experiences in applications.

Now you might ask, what is a copilot? So, a copilot typically refers to an AI-powered assistant which is designed to aid humans in various tasks across various domains like software development, content creation, and data analysis.

Now, when we actually start looking programmatically at how the Assistants API works, you'd be amazed — it's so simple. They have really enhanced the developer experience.

If I go to an example, a developer can integrate an AI assistant into an app to help users navigate and utilize the app. Let's say you have a navigation app — right inside that navigation app, you can create an AI assistant which can probably use something like natural language processing.

So, you can have those capabilities. Right now, you might be using just a postcode to search, but with NLP you could do more — for example, you could simply say, “Hey, I need to go to the nearest petrol pump.” You just say that or type that. This is just an example.

When I say “enhance developer experience,” it means that it automates tasks — a lot of tasks are automated, especially when you have to sift through data, process the data, suggest solutions, or automate workflows. Everything can be taken care of by the Assistants API.

A good example can be an AI assistant which can analyze customer feedback. So, there is an app that looks at the feedback, and based on that feedback, it generates a report suggesting improvements. It’s a perfect example — you’re constantly getting feedback, and based on that feedback, the assistant generates a report suggesting the kinds of improvements to be made. Otherwise, you would need humans to go through all that feedback and come up with those improvements manually.

Now again, another good thing is customizable personality. It allows the tuning of AI model personalities and capabilities through specific instructions. As we always say, there is always a brand voice — certain brands speak or reply in a certain manner. You can train your model that way. You can train your Assistants API in the same manner.

Another good example can be if you want to configure an AI assistant to respond in a friendly and casual tone — especially if you take the example of a social media platform. In such a platform, you will always see that the response you get will be in a very casual and friendly manner. That’s the benefit.

The Assistants API also allows parallel tool access. It supports accessing multiple tools simultaneously, including Azure-hosted tools and custom-built tools.

A perfect example can be that you can use both a database search tool and a code interpreter to help a user troubleshoot a technical issue. There are several tools — for example, file search and code interpreter. What this means is that the Assistants API allows you to call multiple tools at the same time. So, you could be using function calling, file search, or code interpreter — all at once. That level of parallel tool access is allowed.

The next good thing about the Assistants API is that you don’t have to worry about historical messages. It enables persistent conversation threads and stores message history.

So, all your previous conversations are stored — it maintains your context. Whatever interaction you’ve been having with your AI system, it stores that information and allows persistent conversation threads to be maintained. It also helps manage context length automatically.

A very good example can be that a user picks up a conversation with an AI assistant right where they left off after one week. Even after one week, when you go back to your conversation, the AI assistant is intelligent enough to know your context. It won’t ask, “Hey, what were you asking about?” That is the beauty of persistent threads.

The next one is file handling. The Assistants API has the capability not only to access data but also to create files in various formats. It can go through data and generate its own files as well.

A good example here can be that it can generate an Excel spreadsheet from sales data and include references to the original data files. That’s the beauty of the Assistants API.

Now, a very important thing — although it says no extra cost, please remember that there are certain tools, and I’ll talk to you about that later when we do deeper dives into these tools.

There is no additional pricing or quota for Assistants — basically, if you are just using the Assistants API, there are no additional charges. You’re paying for the input and output tokens anyway, which is standard.

But, just in case you are looking to use the two tools available at the moment — code interpreter and file search — then you have to be aware of the additional costs.

The costs are as follows (and we will discuss this in more detail in the deep-dive lectures):
If you use Code Interpreter, you will be charged $0.03 per session or per hour, and $0.01 per gigabyte of vector storage per day.
If you are using File Search, similar additional charges apply.

But all I want to say is this — if you are just purely using the Assistants API, you don’t have to pay anything extra. However, if within the Assistants API you are making use of these two tools (Code Interpreter or File Search), then you will need to pay additional charges.

A business use case for this can be where you have the Assistants API managing customer inquiries without incurring additional costs — or when you don’t need advanced tools.

The Assistants API has versatile use cases — it can be used in product recommenders, sales analyst apps, coding assistants, or even QA chatbots. All of these are great examples.

Another couple of examples could be an AI assistant helping employees find HR-related information by searching through the company’s internal knowledge base, or a marketing team using the Assistants Playground to experiment with different AI assistants.

If you want to utilize the Assistants API, you’ll see that it’s available in Azure OpenAI Studio as part of the Assistants Playground.

It offers a no-code environment — that’s the beauty of the Assistants API. You simply choose your assistant, select the tools you want to use, upload your data, and you can immediately start interacting with the LLM.

And that’s the beauty of the Assistants API.

So, I hope you got a good understanding — or at least an initial basic understanding — of what the Assistants API is.

# **D) Assistants API Component / Key Terms**

After taking a good look into what an Assistants API is, it’s time to explore several components—or rather, the important terms and technologies—that you should be aware of inside the Assistants API. These components are very important, especially if you are actually working on the coding side of things.

If you are using the Azure OpenAI Studio or Azure Studio, you may not need to go into too much detail about these components since those are more of no-code environments. However, when you are working on the coding side, these components become crucial to understand. That’s why it’s important to get a basic understanding of what each of these components represents. To make this easier, I’ve given a simple example for each of them.

The very first component we talk about is the Assistant. By now, you probably already understand what an assistant is. As I mentioned earlier, just like a manager has a personal assistant, an application can have an AI assistant. For instance, if you have a navigation app, inside that app you can have an AI assistant that helps users interact in a more natural, conversational way. In simple terms, an assistant is a custom AI that uses Azure OpenAI tools to help users. So, anything that is helping you perform a task is your assistant. A few examples could be an AI customer support agent that helps users fix their devices or a navigation assistant that helps you find routes.

Next comes the Thread, which is a very important concept and object. A thread is essentially a chat session between a user and the assistant. Here, you have the user on one side and the AI assistant on the other, and between them flows a series of messages. This entire session of communication is called a thread. The thread stores all the exchanged messages and can automatically trim older ones when needed. For example, if a user starts a chat to ask about an order status—say, you go to the Apple website and chat with the AI assistant asking for the status of your order—the entire conversation, including your query and the assistant’s response, is stored inside a thread.

Then we have the Message component. As discussed, between the user and the AI assistant, what actually flows back and forth are messages. A message can be a text, an image, or even a file sent either by the user or the assistant. These messages form the essence of interaction within the thread. For example, when a user says, “What is the status of my order?” and provides the order number, the assistant replies, “Your order has been shipped and will arrive by Friday.” Both of these are messages being exchanged within the thread.

Next is the Run. You can think of a run as an execution of a specific task. When the assistant begins to process something based on the contents of the chat, it uses the appropriate tools and models to complete the task, and this process is called a run. Because we are dealing with natural language processing, the moment the assistant starts to actually work on a request, that execution phase is termed a run. For example, if a user asks the assistant to summarize a document, when the assistant starts reading and summarizing the document, that marks the beginning of a run.

Finally, we have the Run Step. Within a run, there can be multiple smaller actions or steps. For instance, if the run involves summarizing a document, step one might be reading the document, step two could be generating the summary, and step three might involve displaying the summarized text to the user. Each of these individual actions within a run is called a run step. Run steps show the detailed actions taken by the assistant, including which tools or messages were used to complete the task. So, continuing with our example, step one could be the assistant reading the user’s question, step two could involve the summarization process, and step three could be creating and returning the summary.

As mentioned at the beginning, these are very important components or terms that you should be familiar with when working with the Assistants API: Assistant, Thread, Message, Run, and Run Step.

In the next lecture, we’ll take a look at the actual architecture of the Assistants API—how it looks, and how messages flow between each of these components.

# **E) Assistants API Architecture**

In the previous video, we had a good look at the different components and important terms that you need to be aware of when working with the Azure OpenAI Assistants API. In this video, we will go through the entire architecture—how these different components interact with each other and how data actually flows between them. Let’s take a look one by one.

The very first and most important component we talk about is the User. As you understand, the user is the end user who interacts with the system by uploading data files and sending or receiving messages within threads. It’s quite straightforward—the user is the person actually interacting with the AI system or AI assistant.

Next, we have Files. In many demos that you’ll see later, you’ll notice that you often interact with a lot of files—sometimes uploading them, and other times seeing that files are being created or generated by the AI assistant itself. So, it works both ways: either the user uploads files, or the AI assistant generates files as part of its operations. Typically, files represent the data uploaded by the user. For example, when we work with the code interpreter, we might upload a CSV file containing data about failed banks, and based on that, we’ll generate some graphs or analyses. Thus, files form a crucial component in the workflow.

Then we move to Threads. As discussed earlier, whenever there is a conversation happening between the user and the AI assistant, it happens inside a thread. All the message exchanges take place within that thread. A thread contains both user messages and AI messages. The messages you send to the AI assistant and the responses that come back are stored inside these threads. Messages are continuously added to and retrieved from threads. So, in essence, the user interacts with the thread, sends a message, and receives the response through the same thread.

Next, we talk about the Runtime Environment for the system. As we discussed before, a “run” refers to the execution of steps—so the runtime environment is the central environment where the assistant operates. It’s the core execution layer that interacts with the models, tools, and files. The runtime environment connects with all these components and manages how they communicate. All messages—especially the AI-generated ones—are added to and read from threads through this environment. Essentially, the runtime environment for the assistant is the one interacting with tools, assistants, models, and files, facilitating the overall data and message flow.

The Assistant, as you already know by now, comprises the instructional messages that guide the AI’s behavior. For instance, we’ve discussed several examples—like building a navigation app that includes an AI assistant to provide natural language responses to user queries.

Then we have Models. These are your language models—such as GPT-4-Turbo or other large language models (LLMs)—that generate AI responses based on the instructional messages and input data. The runtime environment depends on these models to generate meaningful responses. In the context of Azure OpenAI, a model would correspond to a deployment within your resource, which the assistant uses for text generation and reasoning.

We also have Tools, which play a very important role. Currently, there are three primary tools: Code Interpreter, Function Calling, and File Search. These tools provide additional functionalities that help the assistant generate accurate and context-aware responses. They enable operations like executing Python code, retrieving specific files, or calling custom functions. Don’t worry about them for now—we will go into a deep dive into each of these tools later in the course.

Now, let’s understand how the data flow takes place among these components. The process begins with the User, who uploads data files. These files could be PDFs, text documents, or CSVs. For example, in an upcoming session, we’ll upload data related to failed banks and ask the assistant to generate a graph based on it.

Then comes the Message Exchange. As we discussed, a thread consists of messages—both from the user and from the assistant. The user adds messages to the thread and retrieves messages (AI responses) from the same thread. So, there’s a continuous two-way flow of communication—the user sends input messages, and the assistant replies with responses.

The Runtime Environment plays a key role here. It processes user messages and interacts with the assistant to generate AI responses. When the runtime environment receives a message from the user, it processes that message and determines what needs to be done—whether it needs to access a file, invoke a model, or use one of the tools. Based on this logic, it coordinates the actions. The runtime environment accesses the model (or a specific model deployment) to generate responses based on the user’s input and the assistant’s instructions. Since we’re dealing with generative AI, this model interaction is essential for generating new responses dynamically.

Additionally, the runtime environment utilizes tools as needed. As we discussed, these tools could include the code interpreter, file search, or function calling. Depending on the task, the runtime environment can call one or more of these tools to help complete the operation.

Finally, we have Thread Management. The assistant’s messages (AI messages) are added to and read from the threads, maintaining a continuous interaction loop with the user. This means that as the conversation progresses, new messages are generated and stored, while older ones may be trimmed automatically when required.

Now, you might wonder why we are discussing all of this in such detail. The reason is that understanding these components and their interactions is crucial when we start writing Python code for the Assistants API. You’ll see all these terminologies—Run, Thread, Runtime Environment, Model (or Deployment), Assistant, and Files—come into play in your code.

By now, you should have a clear understanding that the user adds messages to the thread, interacts with AI responses, and that the runtime environment serves as the core orchestrator connecting everything together—tools, assistant, models, files, and the threads themselves. This gives you a complete picture of how the Azure OpenAI Assistants API architecture works.

So, I believe you now have a solid understanding of how data flows and how each component interacts within the Assistants API.

# **F) What is Function Calling ?**

Function calling in Azure OpenAI is an advanced capability available through the Assistants API, alongside tools like the code interpreter and file search. It plays an important role because Azure OpenAI or OpenAI models are always trained only up to a specific point in time, which means they cannot provide real-time information such as stock prices, weather, or flight details. To overcome this limitation, function calling allows the model to intelligently realize when it does not know information and instead call an external function to fetch the real-time data. For example, if a user asks for flights from London to Athens on 31st March for one adult, a normal ChatGPT response would say it cannot provide real-time flight data. However, with function calling, the model understands the user’s request, extracts key parameters like departure city, arrival city, date, and number of adults, and sends them to a third-party API that provides flight data. 

This extends the model’s capabilities beyond its built-in knowledge. You can build similar custom functions, such as one that retrieves real-time stock prices by accepting a stock symbol and returning the current trading price. The model dynamically decides when to call a function based on the conversation, such as calling a weather API function when a user asks for weather in a specific city. In the code, each function must be defined clearly with its name, parameters, and expected output. Functions also receive arguments either directly from the user or from the output of previous functions, such as a function that books appointments based on date, time, and service type. When the model decides to call a function, it produces a JSON response containing the function name and the arguments. For example, a function to send an email would receive JSON containing the recipient, subject, and body. Function calling can also happen multiple times in a conversation, enabling complex workflows. For instance, in customer support, the assistant may first call a function to verify account details and then call another function to fetch recent transaction history. Overall, function calling empowers Azure OpenAI to access real-time data and perform tasks that go beyond its training by intelligently invoking external APIs.

# **G) Demo: FC: Python Code : Function Calling Intro**

Hello and welcome. This is your instructor, Joy from Cloud Alchemy Limited. Many of you reached out saying you wanted to see a real use case of function calling, as well as the Python code behind it. You mentioned that while the earlier theoretical explanation was helpful, you would now like to understand how function calling actually works in practice. So, as I always say, your wish is my command—here it is. In the upcoming series of lectures, we will walk step by step through function calling, where I will explain the Python code clearly at every stage and demonstrate how the entire process is implemented. As a quick recap, we use function calling whenever we need to extend the capabilities of OpenAI or Azure OpenAI. In the earlier theory session, I showed how, for example, if you ask Azure OpenAI to book tickets from London to Milan, it cannot do this directly because it requires real-time data. Instead, function calling allows the model to call a third-party API—such as an airline booking system—and send a structured output in exactly the format the API expects. 

Azure OpenAI intelligently extracts the required details and prepares input parameters matching the API’s structure. In this demo, we will follow a similar approach but focus on retrieving the latest weather data. For example, if you are sitting in London or New Delhi and ask for the latest weather, Azure OpenAI cannot answer on its own because it is trained only up to December 2023 and does not have real-time weather updates. To solve this, we will call a third-party weather API, specifically openweathermap.org, to fetch live weather information. In the next lecture—what I call Step Zero—I will show you how to register for the OpenWeatherMap API, which is essential before using it inside your Python code. Keep watching.

# **H) Demo: FC: Python Code: Get an API Key from openweathermap.org**

Let’s begin by discussing Step Zero, because this is the very first action you must take before moving ahead with anything else in the process.

To start, you need to register on openweathermap.org. When you visit the website, you’ll notice sections for APIs, dashboards, pricing plans, and documentation. For our use case, you only need to sign up for their One Call API. On the pricing page, make sure you select the free tier, which offers 60 API calls per minute. This tier provides features like the current weather, three-hour forecasts for five days, and other essential data. It’s more than sufficient for development and testing purposes.

After you register and navigate to the API Keys section, you’ll be able to generate your personal API key. This key is extremely important because it’s what authenticates your requests to the OpenWeatherMap service. Once you receive it, you must add this API key to your Azure OpenAI .env file. So far, that file contained just two values — the Azure OpenAI endpoint and the Azure OpenAI API key. But since we’re now integrating with a third-party service (OpenWeatherMap), this weather API key must also be included there.

Once the API key is added, you can begin making actual weather API calls. The endpoint we’ll be using is the One Call API, which follows this format:
api.openweathermap.org/data/3.0/onecall. This endpoint expects specific parameters such as latitude, longitude, and your API key. The API key, of course, comes from your registration, while the latitude and longitude values will be dynamically passed at runtime.

What’s really interesting is how intelligent Azure OpenAI becomes when function calling is enabled. It can automatically determine when to call this weather API and how to pass the required parameters. You’ll see this behavior clearly when we move into the coding part.

So, to summarise: register on the website, generate your API key, add it to your .env file, and once that’s ready, we can proceed to the next phase of the setup.

# **I) Pre-Req Setup azureopenai.env**

Pre-Requisistes given to create these files:

AZURE_OPENAI_ENDPOINT="https://......openai.azure.com/"

AZURE_OPENAI_API_KEY="8xxxxxx88ba9fe0"

OPENWEATHERMAP_API_KEY="1xxxxxda94b02a"

# **J) Demo: FC : Python Code : Initialise and Set the Environment**

Alright, so moving forward, let’s discuss the next important step in our setup process.

At this stage, we need to install the OpenAI Python package using the latest version available. I’ve mentioned this before, and I’ll repeat it because it’s crucial — always run pip install --upgrade openai and pip install --upgrade python-dotenv. The reason behind this is simple: when you’re working on new features, integrations, or testing scenarios, you should always rely on the most recent versions of the packages. This ensures compatibility, avoids older bugs, and gives you access to the newest functionalities.

In this video or step, we’ll also be setting up the environment variables for your Azure OpenAI configuration. This includes your Azure OpenAI endpoint and, most importantly, the API keys. Remember, these keys are stored in your azure-openai.env file. Along with the Azure OpenAI key, this file also contains your API key from openweathermap.org, which we added earlier. Keeping all keys in a single environment file makes your setup cleaner and more secure.

Once the installations are complete, we move on to importing the necessary Python libraries. This usually includes the Azure OpenAI client and load_dotenv to help us read from our environment file. After loading the .env file, I personally like to run a quick check to ensure I’m operating in the correct environment. Since I have multiple environments configured on my system, this step helps me avoid any confusion or mix-ups. You can do the same—it’s a good practice to verify that the right endpoint and keys have been loaded.

When you execute these steps, the system should confirm that your environment is correctly set up. It will load details like the Azure OpenAI endpoint, the associated API key, and also the API key for OpenWeatherMap. All these values become available to your code, allowing you to smoothly proceed with upcoming operations.

In the next lecture, we’ll focus on initializing the Azure OpenAI client, which is a crucial part of enabling function calling and seamless communication with external APIs.

# **K) Demo: FC : Python Code : Instantiate the Client Object of Azure OpenAI**

This part honestly doesn’t require a lot of explanation because by now, we’ve repeated this procedure several times throughout the course. At this point, I’m quite confident that most of you can probably write this piece of code even in your sleep! It’s straightforward and forms one of the core setups whenever we work with Azure OpenAI through Python.

All we’re doing here is importing the AzureOpenAI library from the OpenAI package and then initializing the Azure OpenAI client. Nothing fancy, nothing new — just the standard boilerplate code that you’ll use again and again whenever you interact with the Azure OpenAI service.

While initializing the client, we pass three essential values. First is the Azure OpenAI endpoint, which is automatically fetched from your .env file. Next, we provide the Azure OpenAI API key, again loaded from the same environment file. And finally, we specify the API version. Now remember this: when you are developing or experimenting, it’s always best to use the latest API version. However, when you're working in a production environment, you should stick to the latest GA (Generally Available) version to ensure stability and long-term support.

Once we run this block of code, we successfully instantiate our client object. This object will act as the primary interface for sending requests to Azure OpenAI for everything we do next.

And now, with the setup complete, we can move on to the part that will actually be new and interesting for you — we’ll start defining a custom function, specifically the get_weather function that will interact with the third-party API through function calling.

# **L) Demo:FC : Python Code: Define the get_weather Function**

In this step, we will define the get_weather function. This is the function that Azure OpenAI will intelligently call whenever the user asks something like “What’s the weather in London?” or “Give me the latest weather in New Delhi.” The beauty here is that the user doesn’t need to manually provide the latitude and longitude. Azure OpenAI extracts that information on its own and passes the structured values to our function.

Now, our get_weather function accepts exactly two inputs: latitude and longitude. These are the same values the third-party API needs, and Azure OpenAI will supply them for us through the function calling logic. That’s exactly how we extend the capability of the model beyond its training cut-off date by plugging in real-time APIs.

Before we proceed further, one important habit I want you to develop: always check the documentation of any third-party API you plan to call. When working with OpenWeatherMap, the documentation clearly explains what parameters are required, in what ranges, and what shape the response will return. So let’s walk through that step-by-step.

Inside our function, we first validate both latitude and longitude. These checks exist because the API defines strict permissible ranges. Latitude must be between –90 and +90, while longitude must be between –180 and +180. If the provided values fall outside these ranges or are missing, the function should immediately raise an error. So the initial part of our function simply enforces these basic rules.

Next comes the actual API call setup. We start by loading the API key from our .env file — the same key you obtained from OpenWeatherMap during step zero. Once again, this is why I stressed earlier that the API key must be stored inside your Azure OpenAI environment file, so the Python script can securely access it.

Then we create the base URL for the API. This comes directly from the OpenWeatherMap documentation. Their endpoint for the One Call API looks like:

api.openweathermap.org/data/3.0/onecall

So we replicate that structure inside our code. The complete URL is then constructed by adding the latitude, longitude, any exclusions we want, the unit system (in our case, “metric”), and finally the API key. Once that’s done, we simply call requests.get() on the fully constructed URL.

The data returned from OpenWeatherMap comes in JSON format. To understand the structure, again, the documentation is your best friend. You will see that weather information sits inside current, and inside that you have details such as weather, main, description, and temperature-related fields. Based on that, we extract two important values: the weather condition and the temperature.

Finally, because this is a function, we return a JSON object containing the four key pieces of information we care about: the latitude, longitude, the weather condition, and the temperature. The function definition ends there — we are not executing it yet, just defining it so Azure OpenAI can call it when needed.

So that completes the logic for our get_weather function. In the next steps, you’ll see how Azure OpenAI automatically selects and triggers this function when a user asks about the weather.

# **M) Demo: FC: Python Code: Define the tools list required for the Assistants API**

We now need to define the tools list that the assistant can use because we are learning how to work with the Azure OpenAI Assistants API. As I mentioned before, the Assistants API provides access to different types of tools. In a previous lecture, we explored the interpreter tool, and now we are focusing on the function-calling tool.

This is the step where we give the assistant more information about the functions it can use. To define the tools list, we create a list of functions, specifying the type and the function details. In our case, the type is function, and the function name is exactly what we defined earlier — get_weather. By doing this, we are informing the Azure OpenAI assistant that it has access to this function for function calling.

Along with the name, we provide a description of the function. For our example, the description is: “Get the weather condition using the latitude and longitude.” This is important because, when calling the third-party API, the assistant needs to know the latitude and longitude values. Without this information, it wouldn’t be able to fetch the weather data accurately.

Next, we define the parameters of the function, specifying their types and descriptions. For example, latitude is a number, and its description is “latitude of the location.” Similarly, longitude is a number, with the description “longitude of the location.” We also mark these parameters as required, which tells the Azure OpenAI assistant that it cannot call the function unless these values are provided. This ensures that the function is always executed with valid inputs.

The beauty of this setup is that, as an end user, you don’t even need to manually provide the latitude or longitude. Based on your natural language query, the assistant can intelligently infer these values and make the API call to the third-party service automatically. This is what makes function calling in Azure OpenAI so powerful and seamless.

With this, we have successfully defined our tools list with the functions that the assistant can use. In the next step, we will look at how to create assistant thread messages and continue from there.

# **N) Demo: FC_ Python Code : Create an Assistant & Thread**

And now we finally come to the step where we need to create the assistant and the thread. This step is actually quite simple. By now, we have done it several times, so you should be familiar with the hierarchy. Essentially, you have an assistant, and one of the major components of an assistant is a thread. Within a thread, you have messages, which can be of two types: user messages and responses from Azure OpenAI.

To start, we call the assistants.create method to create the assistant. As we discussed previously, this method requires some inputs. The first input is the name of the assistant. In our case, we are naming it weather_assistant. Next, we provide instructions in plain English, explaining what the assistant is supposed to do. Here, the instruction is that it is a weather assistant that provides weather information using real-time data.

A very important part of this setup is providing the tools. We pass in the tools list, which contains all the functions the assistant can use. This is the same tools list we defined earlier with the get_weather function. The assistant now knows that there is a function available called get_weather which requires two values: latitude and longitude. By giving this information upfront, we ensure that the assistant has all the context it needs to perform its tasks intelligently.

Next, we specify the model to use. Since this is Azure OpenAI, instead of a standard OpenAI model name, we provide the deployment name from our Azure OpenAI setup. This ensures that the assistant uses the correct model configured in your Azure environment.

Once the assistant is created, the thread also needs to be created. This is done by calling the threads.create method, which sets up the messaging thread for the assistant. With this, both the assistant and the thread are fully ready to interact and handle requests.

After completing this step, we will move on to the next lecture, where we will define a function for running the conversation. This function will bring everything together in a single place to manage user interactions efficiently. Don’t confuse this with the function calling feature we discussed earlier — I will explain the distinction in the next lecture.

# **O) Demo: FC:Python Code: Create a function for running the conversation**

Now we will talk about the run_conversation function. Don’t confuse this with function calling; this is a separate function we created specifically to handle running the conversation with the assistant using the user input. The input to this function is user_message, which represents the message or prompt that the user is providing. Essentially, this is the question the user is asking the assistant at that moment.

The process is straightforward. First, we create a user message in the thread. In the previous lectures, we already instantiated the assistant and created the thread. Now, we call threads.messages.create to create the message, passing in the user message and any relevant prompt information. Once the message is created, we proceed to run the thread using threads.run.create. This method requires two key pieces of information: the thread ID and the assistant ID, which we obtained when we created the thread and assistant. This generates the run for the conversation.

To ensure smooth processing, we add a small sleep period, usually around five seconds, while continuously checking the status of the run. We retrieve the run status using threads.runs.retrieve, passing in the thread ID and run ID. If the run status is completed, all messages are captured by calling threads.messages.list with the thread ID. From here, we print the last response, which contains the output returned by the assistant.

If the run status indicates that action is required, it means the assistant needs additional information or needs to execute a function. This is where function calling comes into play. We handle required actions by accessing run_status.required_action.submit_tool_outputs.model_dump, and we iterate over each tool output. For every action, we check the function name and its arguments. For example, if the function name is get_weather, we call the get_weather function with its required arguments, such as latitude and longitude. All outputs from the function calls are appended into tool_outputs, which represents the assistant’s resulting messages.

Once all the tool outputs are collected, we submit them back to the assistant using threads.run.submit_tool_output, providing the thread ID, run ID, and the collected tool outputs. This completes the cycle of retrieving data from the third-party API and passing it back to the assistant. If the system is still processing, we simply wait for a few seconds and check again.

In summary, the run_conversation function acts as the central hub for all interactions with the assistant. It handles user input, manages the conversation flow, executes function calls if needed, and submits the results back to the assistant. Essentially, everything that happens in the conversation with the assistant is orchestrated through this single function.

# **P) Demo: FC: Python Code: Take the User input and show result**

We have finally come to see the real magic—the part we’ve been waiting for and why we did so much coding up to this point. The process is simple yet powerful. We set up a loop to keep the conversation going, allowing continuous interaction with the Azure OpenAI Assistants API until the user types "end." Every interaction in this loop is passed as a user message to the assistant, and we utilize the run_conversation function that we defined earlier to handle this seamlessly.

When you provide a prompt, such as “Please give me the current weather in London,” this request is sent directly to the Azure OpenAI Assistants API. The assistant intelligently identifies that it needs to call a function to retrieve real-time data. In this case, it recognizes that it must access the OpenWeatherMap API, a third-party service, to get the current weather. The assistant then constructs the API call, passing the required parameters such as latitude and longitude, which it can determine automatically based on the location you requested.

The third-party API responds with the weather data, which is then formatted into a tool output and sent back to the Azure OpenAI assistant. The assistant consolidates the response and provides a natural-language answer. For example, the response might read: “The current weather in London is clear sky with a temperature of 20.95 degrees.” You can quickly verify this information against the actual weather, and it matches, showing that the function calling is working perfectly.

You can continue interacting with the assistant by asking for weather updates in other locations, such as New Delhi. The process is the same: the assistant determines the required latitude and longitude, calls the third-party API, retrieves the current weather, and then formats the response for you. This demonstrates the intelligence and automation that function calling adds—OpenAI itself does not have access to real-time weather, but it can seamlessly integrate with external APIs to provide accurate, up-to-date information.

This series of lectures highlights the power and flexibility of Azure OpenAI with function calling, enabling dynamic, real-time interactions that extend far beyond the model’s training data. I hope you found this walkthrough valuable. If you haven’t yet provided feedback on the course, please do so—it really helps us continue producing high-quality content and new learning material. Thank you for watching, and I hope you enjoyed this demonstration.

# **IV) Azure AI Agent Service**

# **A) Intro to Azure AI Agent Service**

Hello and welcome to the module on Azure AI Agent Service and the reason why you've enrolled in this course.

Obviously, you must be thinking that we've enrolled to learn about the Azure AI Agent Service, and it is coming now. The reason we are covering this now is that we first needed to talk about the Azure AI Foundry and the Assistance API, as these are foundational layers. Understanding these will help you grasp the Azure AI Agent Service better.

In this series of lectures, we will focus on the Azure AI Agent Service itself. We’ll do a deep dive into its architecture, which is truly amazing. I love it because Microsoft has introduced a concept of tools within the service. These include knowledge tools and action tools, and we will explore all of these in detail.

I will also provide a comparison between the Assistance API and the Azure AI Agent Service. This is why understanding the Assistance API beforehand is important. Additionally, as with Azure OpenAI Service, not every model is available in every region. We will discuss model and region support in the context of Azure AI Agent Service.

Another important aspect to cover is quotas and limits. There are specific quotas to follow, including the number of files you can upload, the total size of the files, and the number of tokens you can have. All of this falls under the quota and limit guidelines, which you need to be aware of.

We will also discuss the pricing aspect. Many people read in blogs that Azure AI Agent Service is free. While the service itself is free, the underlying resources are paid. By underlying resources, I mean you would be paying for Azure OpenAI Service, file search capabilities, grounding with Bing search, SharePoint usage, and other individual services. So, be careful and keep this in mind.

In the upcoming sessions, we will have a lot of practical demos. We will create a hub and a project, which is a good opportunity to practice if you haven’t done it yet. You will also see how to create an agent via the Azure Foundry. The theoretical concepts of tools we discussed earlier will now be demonstrated practically. I will show you where the knowledge and action tools are located inside the agents playground.

Finally, we will explore the agents playground by creating a sample agent, giving it a prompt, and observing the response from the agent. This will provide hands-on exposure to how agents work and interact in real scenarios.

Keep watching, guys, because this module is going to be very informative and practical.

# **B) What is Azure AI Agent Service?**

Hi folks, it's now time to take a look at Azure AI Agent Service and the reason why you enrolled in this course.

So, let’s dive in. Azure AI Agent Service is a fully managed service. By now, you probably understand that when we say it’s a managed service, it means you don’t have to worry about infrastructure, scalability, or security. The cloud vendor, or the provider of the service, takes care of all these aspects. This service is designed to empower developers to build securely. Essentially, you are building, deploying, and scaling high-quality, extensible AI agents within the Azure ecosystem in a very secure manner.

The service is purely focused on Azure AI agents. When we talk about its key characteristics, it provides a managed intelligent agent platform, which simplifies the building and deployment of AI-powered agents. There has been a lot of discussion around AI agents and how complex it can be, especially because AI interactions often require stateful context awareness. This service simplifies that process, allowing you to build intelligent, context-aware agents efficiently.

As mentioned earlier, Azure AI Agent Service is fully integrated with the Azure ecosystem. This is one of its biggest advantages. You can seamlessly integrate with Azure Cognitive Services (also known as Azure AI Search), Azure OpenAI Service, and Azure Machine Learning to enrich your agent’s capabilities. Furthermore, integration with Azure Logic Apps allows access to over 1,400 connectors, which include Microsoft Teams, Excel, Dynamics 365, and many more. This integration enables your agents to be versatile and enterprise-ready.

Additionally, the service provides scalability and security. Built on Azure’s robust cloud infrastructure, it ensures enterprise-grade scalability, security, and compliance. Among its features, bring your own storage allows enterprises to securely retrieve data for agents, and bring your own virtual network enables secure deployment with data privacy and compliance in mind. The service also supports limitless scale, providing maximum performance and scaling capabilities when running Azure AI Agent Service on your provisioned deployments.

Another remarkable feature of Azure AI Agent Service is that it is multi-modal. Multi-modal means you can interact not just with text, but also with other forms like voice, video, and images, allowing the creation of versatile conversational AI experiences. Traditionally, natural language processing relied only on text input and output, but now you can work with multiple modalities, expanding the scope of interaction significantly.

Finally, the service offers multi-vendor support, which is an exciting development. Microsoft, in close collaboration with OpenAI, initially provided only OpenAI models. Now, customers can create agents using not only Azure OpenAI models but also models from other partners, such as Meta (LLaMA 3), Mistral, and Cohere. Over time, more vendor support will be added, allowing even greater flexibility in choosing models for AI agents.

With this lecture, I wanted to give you a quick but comprehensive glimpse of Azure AI Agent Service. It combines robust cloud infrastructure, multi-modal capabilities, multi-vendor support, and seamless Azure integration to simplify building intelligent, scalable, and secure AI agents.

# **C) Architecture of Azure AI Agent Service**

Now it’s time to take a look at the architecture of Azure AI Agent Service. The first thing you’ll notice is the presence of the Azure AI Foundry. Remember, the agent service is actually part of the Foundry. When you look at the Agent Service, it comes under the umbrella of Azure AI Foundry. In the portal, when you go to a project inside the Foundry, you will be able to access your agents directly.

Let’s start from left to right and explore the key features. The first is built-in enterprise readiness. Microsoft has designed this with enterprises in mind, understanding the requirements of modern organizations. This includes BYO – Bring Your Own options. For example, Bring Your Own File Storage allows organizations to use their existing data storage solutions. Similarly, Bring Your Own Search Index lets enterprises integrate their own search index for customized search experiences.

Next is OBOE – On Behalf Of authorization support. This feature enables secure delegated access, meaning you can delegate access on behalf of someone else. Another key feature is enhanced observability, which provides monitoring and analytics capabilities for better insights into system performance and usage.

Moving to the middle part, we have the extensive ecosystem of tools. Earlier, we discussed Assistance API tools like the code interpreter and function calling. Microsoft has now expanded this, providing a plethora of tools that empower agents. These are categorized into knowledge tools and action tools.

Knowledge tools provide agents with access to various data and services:

Microsoft Fabric: A unified data platform for analytics and AI.

SharePoint: Integration for accessing enterprise content stored in SharePoint or Confluence.

Bing Search: For web searching, allowing agents to ground responses using Bing.

Azure AI Search: A cloud search service for indexing and retrieving data seamlessly.

Licensed Data: Organizations can integrate proprietary data sources like TripAdvisor or other licensed datasets.

Files & File Search: Agents can search and retrieve data from Azure blobs or local/cloud-based file storage.

Code Interpreter: Allows executing code for data analysis and automation, generating graphs, or performing computations.

Action tools define what actions the agent can perform. Key integrations include:

Azure Logic Apps: Enables workflow automation and process integration with over 1,400 connectors, including Microsoft Teams, Excel, Dynamics 365, and Azure App Service.

OpenAPI 3.0 Specified Tools: Supports in-house APIs following the OpenAPI 3.0 specification for interoperability.

Azure Functions: Provides serverless computing to run event-driven applications.

On the right side, we have the Model Catalog. This is not limited to Azure OpenAI or GPT models. Microsoft now supports additional partners, including Meta (LLaMA), Mistral, and Cohere. Azure OpenAI provides access to the latest GPT models, while the Model-as-a-Service approach allows using third-party AI models like LLaMA, Mistral, and Cohere for natural language tasks.

To summarize, Azure AI Foundry and the Agent Service enable enterprises to integrate AI-powered agents with secure storage, search, and processing capabilities. It offers a broad ecosystem of tools, enterprise-ready features, and access to top AI models, making it a powerful solution for AI-driven automation and decision-making.

# **D) Assistants API Vs Azure AI Agent Service**

As we study Azure AI Agents, you’ll notice many similarities with the Assistance API, which we covered extensively in the Assistance API module. If you haven’t gone through those lectures, I strongly recommend revisiting them first. In the Assistance API module, we studied several important concepts:

Assistant: A custom AI that uses models.

Thread: A conversation session between the assistant and a user.

Message: Created by either the assistant or the user, messages can include text, images, or other files.

Run: The activation of the Assistance API to begin processing based on the contents of the thread.

Run Step: The detailed list of steps the Assistance API took as part of a run.

When I looked at the Azure AI Agent documentation, I noticed that the structure is essentially the same. So, all the work you did learning the Assistance API has not gone to waste.

In Azure AI Agents, the concepts are very similar, with slight enhancements:

Agent: Equivalent to the assistant, a custom AI that uses models.

Thread: A conversation session between the agent and a user.

Message: Created between the agent or a user, just like messages in the Assistance API.

Essentially, Microsoft has enhanced the Assistance API and replaced the term “assistant” with “agent.” The architecture remains the same, and all the core concepts — agent, thread, message, run, and run step — still hold true.

The takeaway from this lecture is that Azure AI Agents is not a completely new paradigm. Everything you learned from the Assistance API module applies here as well. The architecture, the SDK usage, and the flow remain consistent, so your previous knowledge is directly transferable.

# **E) Model & Region Support**

This is a very important lecture on model and region support in Azure AI Agent Service. As we’ve seen with Azure OpenAI, not every model is available in every Azure region. The same applies to Azure AI Agent Service. I strongly recommend that you always visit the “Models Supported by Azure AI Agent Service” page to check availability. Keep in mind that what is available may change over time, so it’s important to verify this whenever you start working with Azure OpenAI or Azure AI Agent Service.

The main thing to check on that page is the table that clearly states which deployment or model is available in which region. For example, if you are interested in GPT-4 (2024-1120), it is not available in East US but is available in Japan East. Similarly, GPT-3.5 Turbo is available in Australia East. Always refer to this table before creating any deployments.

Apart from GPT models, another important point is that Azure AI Agent Service currently supports three partner models. These are Meta (LLaMA 3), Cohere (Command R / Command Plus), and Mistral. This means that non-Microsoft models are also supported, and you can create agents using these models as well. The process is similar to Azure OpenAI: you simply create a deployment, specify the model name (whether GPT-4, LLaMA 3, etc.), provide the agent name, and give the instructions for the agent.

One important consideration is that certain tools may only be compatible with specific models. For instance, grounding with Bing Search is one of the knowledge tools for agents. Not every model supports this tool, so it’s crucial to check the documentation before using it. Currently, grounding with Bing Search works only with GPT-3.5 Turbo, GPT-4, and GPT-4 Turbo. If you try to create this knowledge tool with an unsupported model, you will receive a compatibility error.

In summary, always consult the documentation for model and region support as well as tool compatibility. This ensures you select the correct model and region, and that the tools you plan to use will function as expected.

# **F) Quotas & Limits**

Okay folks, this is a quick lecture on Azure AI Agent Service quotas and limits.

Since Azure AI Agent Service is a relatively new service, it’s very important to be aware of quotas and limits before starting production workloads. Microsoft has published these limits clearly, making it easier to plan your usage.

The maximum number of files per agent or thread is around 10,000, whether you are using the API or the Foundry portal. Previously, in Azure OpenAI Studio, the limit was only 20 files. With the Foundry, Microsoft has increased this limit to 10,000 files per agent per thread, which is especially relevant when working with RAG (Retrieval-Augmented Generation) scenarios.

Regarding file sizes, the maximum size for a single file is 512 MB. This applies both when providing knowledge sources to your agents or when using fine-tuning datasets for training or testing. While 512 MB is relatively small, it is expected that this limit may be relaxed in the future.

For all uploaded files combined, the total size that you can upload to an agent should not exceed 100 GB. This includes all chunks or files uploaded together, so it’s important to keep this cumulative limit in mind.

Finally, let’s discuss the agent token limit. Tokens represent chunks of text, such as words, subwords, or characters, that the AI processes. Roughly, one token corresponds to about four English characters, or approximately 750 words per 1,000 tokens. For Azure AI Agent Service, the maximum token limit for an agent is around 2 million tokens.

Being aware of these quotas and limits is essential to avoid issues when creating agents or uploading knowledge sources. Always plan your workloads accordingly to stay within these boundaries.

# **G) Azure AI Agent Service Pricing**

So, obviously, if we are studying such an amazing service, it will come at a cost. You may have read several documents or blogs claiming that Azure AI Agent Service is free to use. Technically, yes, the service itself is free, but the resources and services utilized within the platform will incur costs according to their respective pricing models.

A key component contributing to overall expenses is the Azure OpenAI Service. Azure OpenAI works at three levels:

Standard / On-Demand: Pay-as-you-go pricing based on the number of input and output tokens processed. The cost depends on the large language model (LLM) you choose.

Provisioned Throughput Units (PTUs): Reserved capacity offering predictable costs, suitable for consistent workloads.

Batch API: Provides discounted rates for batch processing, but with a longer turnaround time.

While the Azure AI Agent Service itself does not have a direct price, you will incur costs when using Azure OpenAI models, such as GPT-4, GPT-4 Mini, or GPT-103, as part of your agent deployment.

In addition, certain tools and capabilities may generate additional charges:

File Search and Code Interpreter: These features, part of the Assistance API, will incur separate billing. Even though using these tools may seem simple, such as performing a search query or running a code interpreter, additional costs apply.

Azure AI Search: This is a managed service providing enterprise-scale search integration with AI agents for tasks like RAG. Pricing depends on the number of documents indexed and the query volume.

Knowledge Connections: Integrations with services like Microsoft Fabric, SharePoint, Bing Search, or bringing your own licensed data may incur additional charges and require separate licenses.

Automation Services: Using Azure Functions is currently available, and future integration with Azure Logic Apps may also involve additional billing.

The key takeaway is to not be misled by the term “free”. While the Azure AI Agent Service itself does not have a cost, the underlying services, model usage, knowledge tools, and automation integrations all have separate charges. Always check the pricing pages and plan your usage carefully to avoid unexpected costs.

# **H) Demo: Create a Hub & Project**

First, go to the Azure AI Foundry. From the Foundry, ensure that all your resources are available. Usually, it opens with a prompt; click “Use with AI Foundry” and navigate to AI Hubs.

In AI Hub, we start by creating a new hub, as projects are created inside a hub. You can choose your resource group, for example, Azure AI Resource Group, and select a region, such as East US. Give your hub a friendly name, like Azure AI Hub Agents. Make sure to use a simple name without hyphens, as friendly names are preferred. The default project resource group can be the same resource group you selected.

When you create a hub, it automatically provisions a new Azure OpenAI Service for you. This service is managed behind the scenes by Microsoft and provides access to base models in your Azure subscription. You don’t need to configure anything manually. Once you’ve set the hub name and resource group, click Review and Create. After validation passes, create the hub.

Once the hub is created, we can create a project. The project acts as an endpoint where you will create and deploy your agents. Depending on backend provisioning, this may take a few seconds or minutes. Behind the scenes, Azure also creates associated resources, including a Microsoft Cognitive Service, a storage account, and a key vault. Once deployment is complete, your hub will be fully ready.

After the hub is ready, go to Resources and create a project inside the hub. Remember, the project is contained within the hub. Choose your subscription, assign a resource group, and give the project a name, for example, Azure AI Project for Agents. The project will inherit the hub as its container. Click Review and Create, and your project will be deployed.

At this stage, both the hub and the project will be up and running. Once the project is created, you can start creating and deploying agents inside it. This setup forms the foundation for managing your AI agents within Azure AI Foundry.

# **I) Demo: Create an Agent via Azure Foundry**

Once your Azure AI Hub, project, and AI service are up and running, it’s time to see how to utilize the Azure AI Agent Service within the portal.

Start by clicking on your project and then select “Launch Studio”. This opens the studio or Foundry interface. On the left-hand side, you will see an Agents section, which is what we are primarily interested in. Click on Agents, and you will be prompted to select an Azure OpenAI Service resource. Here, you can choose from the existing connected Azure OpenAI Service resources. This is also where all your agents will be stored.

From this, it’s clear that the foundation of Azure AI Agent Service is still Azure OpenAI. The AI service that gets automatically created as part of your project utilizes Azure OpenAI under the hood. By selecting this auto-created service, you are essentially linking your agents to the Azure OpenAI deployment managed within your subscription.

After selecting the service, you will enter the Azure AI Agent Service interface. Initially, after creating the hub and project, nothing is deployed yet. This screen allows you to deploy a model, as agents run against a specific deployment. The deployment can be a GPT model, such as GPT-4 Mini, or third-party models like Llama.

To deploy, choose a model, for example, GPT-4 Mini, confirm your selection, and assign a deployment name if needed. The deployment type can be set to Global Standard, and then click Deploy. Once deployment completes, a new agent is created. Previously there were no agents, but now your workspace has a functioning agent.

In the next video, we will explore the Agents Playground, where you can interact with your agent and see it in action.

# **J) Demo: Understand the various Knowledge & Action Tools**


In the previous video, we saw that your agent gets created automatically. If you look closely, it has been assigned a name, like Agent 672, and it also has an ID, which is based on the assistant. This clearly indicates that the agent is built on top of the Assistants API.

The interface also shows which model or deployment your agent will use, such as GPT-4 Mini. This is why having a deployment in place is important. The deployment could be a Llama model, any of the third-party partners’ models, or the GPT models provided by Azure.

Once you select the agent, you will notice on the right-hand side the agent ID, which is primarily used when interacting programmatically at the coding level. Additionally, it displays the name, the connected Azure OpenAI Service resource, and the deployment associated with this agent. If needed, you can create a new deployment—for example, Mistral or Llama—and connect it to the agent. You can also define a system prompt for the agent.

An important feature to understand here is the distinction between knowledge tools and action tools. Microsoft has categorized these tools to enhance the agent’s capabilities. Under Knowledge Tools, you will see options such as file search, Azure AI search, and grounding with Bing Search. In some cases, a tool might not be compatible with the model you are using; for instance, grounding with Bing Search may not work with GPT-4 Mini in some deployments. Knowledge tools essentially form the knowledge base for the agent, providing the information that your LLM will use to respond intelligently.

Action Tools, on the other hand, enable the agent to perform operations at runtime. Examples include the code interpreter, OpenAPI 3.0-specified tools (which allow integration with your own APIs), custom functions for real-time calculations, and Azure Functions for scalable, event-driven backend operations. By leveraging action tools, the agent can interact with external systems and perform complex tasks beyond simple question-answering.

Overall, this setup gives a comprehensive view of your agent, including its ID, deployment, connected resources, and the tools it can use. In the next lecture, we will explore the Agents Playground, where you can interact with the agent and see these tools in action.

# **K) Demo : Get a Response to your prompt via the Agents Playground**

In this video, we’ll look at how to submit a prompt to your agent and get a response.

To keep things simple, you can start by defining a system prompt or instructions for your agent. For example, you can simply say:
“You are a helpful agent.”

Next, click Try in Playground. This will automatically open the Agents Playground, and a new thread will be created for you.

Remember, a thread is essentially a collection of messages. Each thread contains the conversation history between the agent and the user.

For this example, after setting the system prompt as “You are a helpful agent”, you can submit a simple query. For instance:
“Who is the Prime Minister of India? Give bullet points for his achievements.”

The agent responds with information like:
“As of October 2023, the Prime Minister is Narendra Modi,” along with a list of his achievements.

Within the thread, you can also explore additional features, such as:

Thread files – where you can attach or link files.

Knowledge tools – like file search or code interpreter.

Token usage – the agent provides information about input tokens (66 in this case) and output tokens (341), which is useful for monitoring usage and costs.

You can also view the thread from the Agents tab. Clicking on the thread shows all messages in that session—the messages sent by the user as well as the agent’s responses. This helps you keep track of the conversation history.

This example gives you a practical understanding of how to interact with your agent using the Agents Playground.

In future videos, we will explore:

Using different knowledge tools.

Leveraging the no-code interface via the graphical portal.

Submitting queries and commands using Python code for programmatic control.

By the end of this series, you’ll be comfortable using Azure AI agents both in the portal and programmatically.

# **V) Understanding Azure SDK for Python**

# **A) Introduction to Azure SDK for Python**

I know that if I had shown you just the Agents Playground without explaining how to do this programmatically with Python, it wouldn’t have been enough. So in this lecture, my goal is to give you a complete understanding of how to create and manage Azure AI agents using Python.

We will focus on the Azure AI Projects client library. Currently, there is no separate library specifically for agents—everything is handled through the AI Projects client library. This may change in the future, but this is the current approach.

Here’s what we’ll cover:

Authentication Scenarios

Using development/test environments.

Using production environments (this is what we will focus on for the rest of the course).

We will also demonstrate using the default Azure client methodology, which allows you to authenticate via Azure CLI.

Setting Up Your Environment

Create a Visual Studio Code environment.

Set up Azure CLI in VS Code.

Install the required Python libraries:

azure-ai-projects

azure-identity

Sample Code Execution

Run a simple example to ensure your environment is properly set up.

Creating an Azure AD Application

Register an intra-ID application in Azure AD.

Grant the application the Contributor role within your Azure AI Foundry environment.

By the end of this lecture, you will have a strong foundation for using the Azure SDK for Python to create, manage, and interact with Azure AI agents programmatically.

This is a crucial step for automating your AI workflows and moving from the portal-based playground to a Python-driven development environment.

# **B) What is Azure AI Projects client library for Python**

I’m sure a question might be coming to your mind:
"So far, we’ve seen how to work with Azure AI Foundry, the Agents Playground, creating agents, and attaching tools… but how do we do this programmatically in Python?"

Well, for that, Azure provides the Azure AI Projects client library. This library is available for Python, and I strongly recommend that you read its documentation. As of the time of recording, it is still in preview mode, so things may change, but currently, this library is the way to work with agents programmatically.

All the upcoming examples in this lecture series will use the Azure AI Projects client library.

Key Highlights of the Library:

Enables developing agents using the Azure AI Agent Service.

Leverages an extensive ecosystem of models and tools:

Models like OpenAI GPT, GPT-4 mini, and others.

Tools such as File Search, Code Interpreter, and other knowledge/action tools.

Support from multiple LLM providers like Microsoft, OpenAI, Meta, Cohere, etc.

Supports a wide range of generative AI use cases.

Prerequisites:

Before using the SDK, ensure you have the following:

Python 3.8 or later.

An Azure subscription.

A project in Azure AI Foundry.

Access to the Project Connect string, which is needed to connect your SDK to the Azure AI project.

Azure Active Directory (Azure AD) authentication via an app registration (Intra ID), which allows secure access.

Authentication Overview:

Token credentials: Interface for dynamically retrieving authentication tokens, so you don’t need to hardcode anything.

DefaultAzureCredential: Simplifies authentication by automatically selecting the best method available:

Environment variables

Managed identity

Azure CLI method

The SDK handles OAuth 2.0 tokens, automatically retrieving, using, and refreshing them, without requiring manual intervention.

Using the SDK:

The main package used is azure-ai-projects.

Authentication typically involves using the DefaultAzureCredential along with the Project Connect string.

Once authenticated, you can create agents programmatically:

Specify the model name (which corresponds to the deployment in Azure OpenAI).

Give a name for the agent.

Provide instructions/system prompts for the agent.

Later, you can attach tools such as:

Enterprise file search

Code interpreter

Bing grounding

Custom functions and Azure Functions

This library essentially gives you the same capabilities as the portal, but programmatically via Python, allowing you to fully automate agent creation, tool attachment, and deployment.

In the upcoming lectures, we will go step by step into creating agents, attaching all types of tools, and using the Python SDK for advanced workflows.

So rest assured—you are in safe hands and will be able to do everything via code just like you did in the portal.

# **C) Demo: Create VSCode Environment & setup Azure-CLI**

In this quick video, we’ll showcase how to use the Azure SDK with Visual Studio Code, specifically leveraging the Azure CLI method.

As I mentioned earlier, there are two ways to authenticate:

Azure CLI method – useful for development or test environments.

Production method – involves creating an app registration and assigning it the contributor role. This will be covered later in the course.

For now, let’s focus on the Azure CLI method and how it works with DefaultAzureCredential in Python.

Step 1: Setting up Visual Studio Code

Open Visual Studio Code.

Create a new folder, for example, agents_practice.

Open the folder in VS Code to start your environment.

Step 2: Creating a Python Virtual Environment

Open a new terminal in VS Code.

Run the following command to create a virtual environment:

python3 -m venv agents


Here, agents is the name of your virtual environment.

Activate the virtual environment:

source agents/bin/activate


Your terminal should now show that the virtual environment is active.

Step 3: Installing Azure CLI

On Mac, you can install Azure CLI using Homebrew:

brew update
brew install azure-cli


brew update ensures your Homebrew is up to date.

brew install azure-cli installs the Azure CLI.

On Windows, follow the official Microsoft documentation for installation.

Once installed, verify the version using:

az --version

Step 4: Logging into Azure

Run the following command to log in:

az login


This will open a browser window for login.

Complete the authentication, including MFA if prompted.

Once logged in, you can close the browser window and return to VS Code.

Select the Azure subscription to use (for example, subscription 1).

The beauty of using DefaultAzureCredential is that your code will automatically pick up your CLI login credentials without hardcoding anything.

Step 5: Ready to Use SDK

Now that your virtual environment is active, Azure CLI is installed, and you are logged in, you are ready to start writing Python code to create and manage your agents.

In the next lecture, we’ll dive into actually creating an agent programmatically using the SDK.

# **D) Execute the Sample Code**

In this video, we’ll go through a Python example (example.py) that demonstrates how to use the Azure SDK for Python to create and interact with an AI agent.

Step 1: Understanding the Imports

At the top of the code, we import some libraries:

import os
from azure.ai.projects import AIProjectClient
from azure.identity import DefaultAzureCredential


os: Standard Python module for interacting with the operating system.

AIProjectClient: From the Azure AI Projects SDK, it allows you to manage AI agents and their operations.

DefaultAzureCredential: From Azure Identity SDK, it automatically handles authentication using environment variables, managed identities, or Azure CLI login. Since we’re using Azure CLI, it will use that authentication path.

Step 2: Project Connection String

The project connection string is required to connect to your Azure AI project.

You can find it in your Azure AI Foundry project.

Simply copy it into your project_connection_string variable.

The connection string contains:

Region (e.g., East US)

Project UUID

Resource group (e.g., Azure OpenAI Resource Group)

Service type

This string provides credentials and metadata to connect to your project.

Step 3: Initializing the AI Project Client
project_client = AIProjectClient.from_connection_string(project_connection_string)


This initializes the AI project client using your connection string and default credentials.

Using a with statement ensures resources are properly managed and closed when done:

with project_client:
    # Your code here

Step 4: Creating an AI Agent

Inside the client session, you can create an AI agent:

agent = project_client.create_agent(model="GPT-4-mini")


model="GPT-4-mini": This deployment should already exist in your project.

The agent will act as your conversational AI model.

Step 5: Creating a Thread
thread = agent.create_thread()


A thread acts as a session or context for conversations.

It keeps the conversation stateful.

Step 6: Sending a User Message
user_message = "Who is the PM of India?"
thread.add_message(user_message)
response = thread.run()


Sends the message to the agent.

The agent processes it and generates a response.

Step 7: Handling the Response

To extract the agent’s response from the thread, you can access the messages:

messages = thread.messages
for msg in messages:
    print(msg.content)


Important: If you don’t use messages[0].content or similar, you may get a raw JSON response.

Step 8: Cleaning Up
agent.delete()


Deletes the agent to keep things simple after execution.

Step 9: Required Libraries

Make sure to install these libraries in your environment:

pip install azure-ai-projects
pip install azure-identity


After installing, you can run the script.

Expected output: the agent responds, for example:

"As of my last knowledge, the Prime Minister of India is Narendra Modi..."

# **E) Understand the Workflow for Agent Creation**

Before we start creating agents, it’s important to understand the complete workflow and the steps involved in the process. Since we’ll be working inside the Azure AI Foundry with a project and a hub, it’s crucial to know how to authenticate properly and what additional artifacts come into play when creating agents.

The first step is straightforward: we need to create a project and a hub. We’ve already seen in earlier lectures how to do this using the AI.Azure.com portal. In this series of lectures, I’ll also show you how to do it directly inside the portal itself and explain what happens if there’s no existing Azure OpenAI service running.

Once the project and hub are created, the next step is to create a deployment for the model you intend to use. For instance, if you want to use GPT-4 or GPT-4-mini, you must create a deployment for that specific model. This deployment ensures that the model is available for your agent to interact with.

After creating the deployment, you need to create an Azure Active Directory (Azure AD) application, also known as an app registration. This app registration is required for authentication purposes so that your code can securely access the Azure AI project and its resources. Once the app registration is created, you must also create a secret for the application. This secret will be used in your Python code or SDK calls to authenticate the client.

A very important step is assigning the Contributor role to the application for the project you created. Without this, the app will not have sufficient permissions to interact with the project, and authentication will fail. This is often a tricky part where many users get stuck, so ensuring that the app has contributor access is essential for smooth agent creation.

To summarize, the steps for agent creation are as follows: first, create a hub and a project in Azure AI Foundry; second, create a deployment of the model you wish to use, such as GPT-4-mini; third, create an Azure AD application (app registration); fourth, generate a secret for the app; and finally, grant contributor access to the app for the project. Following these steps ensures that authentication works seamlessly and that you can proceed with creating and interacting with your agents without any issues.

# **F) Demo: Create Azure AI Project via Azure AI Foundry**

Now we are ready to start with the first step: creating your project and hub. To do this, go to Portal.azure.com and navigate to Azure AI Foundry. Since no resources exist yet, you will see a plus icon. Inside the Foundry, you have the option to create both a project and a hub. We start by creating a hub. When creating a hub, it will ask for your subscription and resource group. You can either pick an existing resource group or create a new one. You also need to select the region, such as East US, and give your hub a friendly name. For example, we can call it Azure AI Hub Agents. The default project resource group will also be selected, and the system automatically provisions an Azure AI service as part of the hub creation. This service, behind the scenes, points to an Azure OpenAI service, which is automatically created for you. Once all the details are filled, click Review and Create. After validation passes, the hub will be created. It’s important to note that a hub must be created first because projects are created inside a hub.

Once the hub is created, you can go back home and see that the hub now appears in your Foundry. Along with the hub, the pre-created Azure AI service will also appear, which is internally linked to an Azure OpenAI resource. Now that the hub is ready, you can proceed to create a project. Again, select the resource group, give the project a name, such as Azure AI Project for Agents, and make sure to select the hub you just created. This step is crucial because the project must be associated with a hub. After validation, the project creation will begin. The deployment usually takes less than a minute, and once it completes, your project will be up and running.

At this point, you should have all three resources available in your Foundry: the hub, the project, and the Azure AI service created in the background. These resources form the foundation for creating and deploying agents. In the next lecture, we will dive into deployment configuration and see how to set up the model for the agents.

# **G) Demo: Create Entra ID Application & Grant Contributor access**

The step we are going to work on is crucial for authentication. This may be new to some, but it’s important to understand. We need to create an app registration, which will be used for authenticating our Azure AI project. As mentioned in the workflow, this app must also be granted contributor access to the Azure AI project we created. To do this, go to Microsoft Entra ID, then navigate to App Registration. Click on Add to create a new app registration. For the user-facing display name, enter something like Application for Agents, and click Register. Once the application is registered, the next step is to create a client secret, which will be used in our code for authentication. Go to the newly created application, navigate to Certificates & Secrets, and create a new client secret. Give it a name, such as MySecret, set an expiration (six months is common), and click Add. This secret will now appear in the list and will be used in your Python or SDK code for authenticating the app.

After creating the app registration and the client secret, the final step is to grant contributor access to the project. Go back to your Azure portal, navigate to Azure AI Foundry, and open your Azure AI Project for Agents. Under Access Control (IAM), go to Role Assignments and click Add Role Assignment. In the role selection, choose Contributor, which grants full access to manage all resources without allowing role assignments. Next, for assign access to, select Service Principal, as our app registration is a service principal. Click Select Members, choose Application for Agents, and confirm. Finally, click Review and Assign to complete the process. Once done, you will see the application listed as a Contributor under role assignments with the type Service Principal. This step is extremely important; without it, authentication for Azure AI agents will fail, and you will face issues when interacting with your agents.

# **VI) Azure AI Agent Service Action Tools- Function Calling**

# **A) Intro to Function Calling**

As I mentioned in the previous lecture, the Azure AI Agent Service includes knowledge tools and action tools. In this series of lectures, we will focus on the first action tool, which is function calling. I have chosen function calling as the first topic because we already covered a lecture on function calling with the Assistants API, and this allows us to draw comparisons between the number of lines of code required with the Assistants API versus what is actually needed for the Agents API. In this lecture, we will first understand the workflow for the agent that we will be creating. We will then review the various environment variables that are required, install the important libraries, and set up the environment. Following that, we will go through the “get weather” function and demonstrate how to call your Azure AI agent, specifically the weather agent, using function calling. Remember, function calling is one of the action tools provided by the Azure AI Agent Service. Looking forward to seeing you in the lectures.

# **B) Demo: Create a new Deployment inside Project**

This will be a very quick video where we will create a new deployment inside the Azure AI project. As we discussed previously with Azure OpenAI services, whenever you want to use an LLM or any model, you first need to create a deployment for it. This step is essential before you can start using the model in your agents or code.

To start, select your project, which in this case is Azure AI Project for Agents, and go to Launch Studio. Once the studio launches, you will be inside the Azure AI Foundry, within the project. From here, navigate to Models + Endpoints, where you have the option to create a new model deployment.

When creating a deployment, begin with a base model. For our example, you can select GPT-4 or Mini as the model. Confirm your selection, and it will provide you with details such as the deployment name and type. Choose the Global Standard deployment type. The capacity settings, such as 250K tokens per minute, are generally sufficient for most use cases.

Once you finalize the options, click Deploy, and your deployment will be created with the name GPT-4 or Mini. This deployment name is crucial because, when you start coding, you will reference this exact deployment to access the LLM and utilize its generative capabilities in your agent workflows.

# **C) Demo: Understand the Workflow for Weather Agent**

This is a very quick video to understand the workflow of the weather agent that we’ll be creating. The workflow here is very similar to what we did previously with the Assistance API. The main difference is that, in this case, the user is making a call to an AI agent, not the Assistance API.

With an agent, there are usually tools associated with it. For this example, the tool we are using is function calling. The function we will call is a third-party API, specifically the OpenWeatherMap API.

The beauty of this approach is that the user can request information in natural language. For example, the user can simply say, “Get me the weather in London.” Normally, the OpenWeatherMap API requires latitude and longitude as input. In our code, we don’t provide the latitude and longitude directly.

Behind the scenes, the LLM powering the agent understands that the API needs latitude and longitude. It converts “London” into its corresponding latitude and longitude, sends this to the third-party API, retrieves the weather information, and then generates a friendly, human-readable weather report.

This is the core workflow of the weather agent, demonstrating how agents can seamlessly translate natural language input into API calls and return meaningful outputs.

# **D) Demo : Understand the Environment Variables**

Welcome back. In this lecture, we’ll understand the various environment variables that we’ll be using, which is a very important step when setting up your environment. You should follow along while building your environment to ensure everything works smoothly.

The key environment variables we’ll be using include client ID, client secret, and tenant ID, which are all related to the app registration we created earlier. In addition, we need the project connection string, which is required to connect to our Azure AI Foundry project. Finally, since our agent will call a third-party API for weather data, we also need the OpenWeatherMap API key.

To get the client ID, go to your app registration in Azure, copy the client ID, and add it to your environment variable file. The client secret is created under Certificates & Secrets in the app registration; copy the secret ending with the specified suffix and add it to your environment file. The tenant ID, also called the directory ID, can be retrieved from the same app registration and should be added to your environment file as well.

Next, the project connection string can be found in your Azure AI project. Go to the portal, open your project, and click Launch Studio. The project details will display the connection string, which you can copy and add to your environment file.

Finally, for the OpenWeatherMap API key, go to openweathermap.org, create a free account if needed, navigate to API keys, and create a key. Copy this key and add it to your environment file.

With these environment variables set up, you now have a clear understanding of what is required. In the next steps, we will start implementing the code step by step to get your AI agents up and running.

# **E) Demo : Install Libraries and Setup Enviornment**

In this lecture, we’ll start going through our code step by step to understand how it works. One of the advantages of using Azure AI agents, as Microsoft documents, is that it requires significantly less code—hundreds of lines less compared to the Assistants API.

The first step in the code is to install the necessary Python libraries. We install Azure AI Projects SDK and Azure Identity Library for authentication, along with python-dotenv to handle environment variables. You can install these using:

pip install azure-ai-projects azure-identity python-dotenv


The Azure AI Projects SDK is used to interact with Azure AI services, such as creating AI agents, managing tools, and handling conversations. The Azure Identity Library simplifies authentication with Azure services, handling OAuth 2.0 tokens securely without manual intervention. This is where our earlier setup with the app registration and secrets comes into play. Finally, python-dotenv is used to load environment variables from an .env file.

The environment file, which in this case is API_settings.env, contains all the necessary variables like client ID, client secret, tenant ID, project connection string, and OpenWeatherMap API key. The code uses load_dotenv to load this file, and then the variables are fetched using os.getenv(). This ensures that all sensitive credentials and API keys are securely loaded from the environment and can be used in the program.

After setting up the environment variables, the code initializes these variables with the fetched values. Once this is done, the setup is complete, and we are ready to move on to calling the function inside the program.

# **F) Demo: Understand the Get_Weather Function**

Now we move on to the second part of the program, and this part of the program is where we are setting up or showing our function definition for the get_weather function. This get_weather function is directly mapped to the OpenWeatherMap third-party API that we are going to use. The best way to understand this is to visit openweathermap.org and look at how its API call is made. If you notice, we are calling api.openweathermap.org and the API takes the input as latitude, longitude, and the API key. So nowhere are you mentioning any city here, and that’s the beauty I keep mentioning about OpenAI or the LLM here—you only give latitude and longitude, and the model handles the rest. So now let’s go back into the code and see how we do this. 

First, we import the required libraries. We import os for accessing environment variables, then json to handle the weather data in JSON format. We also import requests, which is required to make HTTP requests to the OpenWeatherMap API, because the URL we create is essentially an HTTP request that is sent to their API. Then we import typing, which is used for giving type hints in Python. After that, we start defining our function. This function is meant to get weather information, and as I already showed you, the API takes latitude and longitude as inputs. So we define the function get_weather with parameters latitude and longitude, both as floats, and very importantly, this function returns the weather details in JSON string format. Then, we perform validation—we check whether the latitude and longitude are valid values; otherwise, errors could occur. After validating, we set up our API key because the API key needs to be passed as part of the request. We fetch this API key from the environment variables. Then we start building our actual API request. To call this API, we must construct the request URL. We first define the base URL, and then we construct the full URL by combining the base URL with the latitude, longitude, and API key parameters. After that, we handle API response errors. If the response status code is not equal to 200, we raise an error because something went wrong with the API request. Then we extract the weather details from the response JSON—specifically, we extract the weather condition (the current weather description) and the temperature (the current temperature). Finally, we return the weather details in JSON format. 

As I said earlier, we give latitude and longitude as inputs, but the response we get back is a JSON structure containing the latitude, longitude, weather condition, and temperature. And now comes a very important part—this is something new with Azure AI Agents. Here, we add the get_weather function to a set of functions that can be used by the AI Agent. In the next part of the code, the agent will actually call this function. That is why it’s important to register this function so the agent knows which functions it is allowed to use. Right now, we have only one function, but if we want more in the future, we can simply add them using commas. So this part of the code executes fine, which is good. Now we can move on to the last part where we will see how to create the agent, call the agent, and where the real magic happens. Thanks for watching.

# **G) Demo: Calling your Azure AI Agent**

So finally, we are in the heart of the program where we actually create and call the Azure AI agent, so let’s take a look. The first thing we do is import the important libraries, starting with os, which allows us to interact with the operating system and is required because we need to access environment variables. Then we import json because we will be working with JSON data—remember, we are sending latitude and longitude information and receiving data back in JSON format. Next, we import requests, a very important library since we need to make HTTP or HTTPS requests to interact with APIs. Then we have three important imports from azure.ai.projects: we import the AIProjectClient, which is the main class for interacting with Azure AI Projects, and this is used to create agents, send messages, and manage conversations. After that, from azure.identity we import ClientSecretCredential, which is critical for authentication with Azure services; this is where all the earlier hard work around app registration and secret creation comes into play because this class uses the client ID, client secret, and tenant ID and simplifies acquiring the access token for secure API calls. Next, from azure.ai.projects.models we import FunctionTool and ToolSet. FunctionTool wraps a Python function so that the AI agent can use it as a tool—remember, the agent must have tools available to perform actions, and in this case we are using a function-calling tool. ToolSet represents a collection of tools available to the agent, and together these allow the agent to call custom functions such as our get_weather function.

Then we move to the main execution block where we configure Azure credentials using environment variables. Here, we authenticate with Azure using a service principal, and the key parameters required are the tenant ID, client ID, and client secret. We use os.getenv to read these values from the environment, and then we create a ClientSecretCredential object, which handles obtaining OAuth tokens for our API calls—this entire section is purely on the authentication side. After that, we initialize the Azure AI Project Client, whose purpose is to create an authenticated client for interacting with Azure AI Projects. The key inputs here are the credential we created above and the connection (connectivity) string. The client establishes a connection using these inputs, enabling us to create agents, send messages, and manage conversations with Azure AI Services. Once the project client is ready, we then create the Azure AI Agent.

Before creating the agent, we prepare the toolset with our custom function. This is done by wrapping our function using FunctionTool, referencing the function defined earlier, and then instantiating a ToolSet. We add our function tool to this toolset using toolset.add(). With the toolset ready, we move on to creating the Azure AI Agent. Here the purpose is to define and deploy the agent. The key parameters include the model (GPT-4 or GPT-4-mini), the agent name (WeatherAgent), and the instructions telling the agent that it is a helpful weather agent. While creating the agent, we also attach the toolset so the agent knows it can call the get_weather function when needed.

Next, we create a conversation thread using project_client.agents.create_thread(), which sets up a new session with the AI agent. Then we enter an interactive conversation loop, where the system continuously waits for user input until the user types “end.” Inside this loop, the code sends messages to the agent using agents.create_message, where the user’s query is processed by the model and the tools if needed. We also have error handling in place. Then the run is created, and we check whether the run state has failed or not. We fetch the agent’s response using list_messages, which retrieves all messages in the thread and prints the agent’s reply. At the end, we optionally perform cleanup because if the code is run repeatedly, many agents may get created, and cleaning them up avoids unnecessary clutter. Finally, when we execute everything and test it by saying “Give me a friendly weather report for London,” we do not provide latitude or longitude anywhere. The agent internally resolves London to its coordinates, calls the OpenWeatherMap API, and returns the weather report. The output comes back like: “Wow, it’s a pleasant day with few clouds…” and so on, which matches the live weather because it just fetched the real-time information. The whole point is that we created an agent that could get a weather report for us exactly like we did with the Assistants API earlier, but now with Azure AI Agents the code is much shorter, cleaner, and more efficient. Thanks for watching.

# **VII) Azure AI Agent Service Action Tools - Code Interpreter**

# **A) Intro to Code Interpreter**

Welcome to this series of lectures on the second action tool, which is the Code Interpreter.

So, what is a code interpreter?

The Azure OpenAI Code Interpreter is a tool that allows users to run Python code inside a secure sandbox environment. This enables safe data analysis, complex calculations, and automation directly within chat-based interactions. The beauty of the Code Interpreter is that it is designed specifically to help with data analysis, and that’s exactly what we are going to focus on throughout this set of lectures.

Our plan is simple: we will first try everything inside the Agents Playground. I will show you how to use the Code Interpreter as an action tool within the agent environment. We will work with a sample sales dataset, upload the data, and then ask the Code Interpreter—through our agent, which will be a Graph Generator Agent—to explain what the dataset contains. After that, we’ll ask it to create some interesting visualizations, and you’ll be amazed by the quality of the graphs it generates.

Once we explore this in the playground, we will replicate the entire workflow inside a Python script. I will provide you with the Python code that shows how to use the Code Interpreter action tool within your own agent programmatically. This will allow you to achieve the same results directly through your code.

# **B) What is Code Interpreter ?**

Now it’s time to take a look at one of the first tools in the Assistants API. In the previous videos, I mentioned that there are mainly three tools available today within the Assistants API:

Code Interpreter

File Search

Function Calling

In this video, we’ll focus on understanding what the Code Interpreter is.

To begin with, I’ve taken one of the OpenAI tweets that announced this feature. I’ll read it out and then explain it in more detail so that the concept becomes clearer.

The tweet describes the Code Interpreter as an experimental ChatGPT model that uses Python. This means that behind the scenes, everything it does is powered by Python. It can handle file uploads and downloads, which means you can upload files to it and you can also download output files that it generates.

OpenAI explains that they provide the model with a fully functional Python interpreter running in a sandbox environment. This is a key point: the environment is sandboxed and completely firewalled, ensuring that any code running inside it remains fully isolated. It is also backed by a small, ephemeral disk space, which persists only for the duration of the chat session. So as long as the conversation continues, the session remains active, and subsequent actions can build on previous results.

In simple terms, the Code Interpreter allows the assistant to write and execute Python code within an isolated execution environment. But what does this sandbox environment really mean? Whenever a service needs to execute code — such as Python scripts — it does so inside a sandbox to ensure isolation. This isolation prevents any harmful or unintended code from affecting the underlying system or accessing unauthorized data. So the Python execution happens in a safe, isolated space, which is extremely important when dealing with unknown or potentially risky code.

The tool can process files with diverse data and formats. You’ll see that it can accept inputs in the form of CSV files, PDF files, and many other formats. It can even generate files with data — including visualizations and graphs. We’ll explore all of this in the upcoming demos.

One of its core capabilities is code analysis. It can analyze a code snippet submitted through the API, understand the purpose of the code, and describe what it does. For example, if you provide a piece of Python code and ask what the code does, the Code Interpreter can not only explain it but also execute it safely inside the sandbox to verify the output. This becomes particularly useful when you're dealing with unfamiliar code or code from an untrusted source.

A practical example might be using the assistant to execute Python code to analyze a dataset while ensuring that the integrity and security of your production environment are not impacted. Since the sandbox isolates all activity, there is zero risk of malicious code affecting your system.

Next, we talk about supported languages. Even though the internal execution happens in Python, the Code Interpreter can understand and interpret code written in various programming languages. It can analyze code written in Java, C++, and many others. As the name suggests, it interprets the code — even if it cannot execute it natively. For example, you could provide Java code that sorts an array, and the tool will interpret or simulate the logic to show you the expected output, confirming the functionality across languages.

It also supports various file formats. You can upload files containing code — such as .py, .cpp, or .java files — as well as plain text files. For instance, a user can upload a C++ script for debugging or review, and the tool will read and process it accordingly.

Now comes one of the most impressive aspects: the capabilities that go beyond interpretation. Although the name suggests that it only interprets code, the Code Interpreter goes far beyond that. It can suggest code fixes, generate fresh code snippets, improve your existing code, and iterate on code that fails to run. If the assistant writes code that doesn’t execute correctly, it can automatically attempt different versions until it succeeds. This iterative intelligence makes it far more powerful than a simple code interpreter.

When we move to parallel processing, the assistant can use the Code Interpreter alongside other tools such as File Search. This allows for more comprehensive workflows. For example, while processing a Python script, the assistant might simultaneously use File Search to look for related documentation or additional context, making problem-solving faster and more accurate. In programming scenarios, you define the tools the assistant can access, and the assistant intelligently selects them when required.

Another important aspect is the model choice. Assistants API leverages the latest OpenAI or Azure OpenAI models, which come with larger context windows and more up-to-date training data. Using advanced models allows the Code Interpreter to understand more complex projects with multiple files, enabling it to provide highly accurate and helpful feedback.

One crucial point that many people overlook is that the Code Interpreter is a billable service. While the Assistants API itself is free, the Code Interpreter and File Search tools are not. They incur additional charges on top of standard Azure OpenAI usage costs, which are based on input and output tokens. So you must account for additional charges while using the Code Interpreter.

For example, if a company uses the Code Interpreter to review or enhance their software, they will incur charges based on the interpreter’s usage time and the resources consumed.

So now, we have a complete theoretical understanding of what the Code Interpreter is. It doesn’t just interpret code — it analyzes, executes, debugs, fixes, generates files, generates graphs, and even iterates intelligently through code until it works. And all of this happens in a secure, isolated sandbox environment.

In the next demos, we will explore these capabilities hands-on and see how powerful this tool truly is.

# **C) Understand the Input Data - sales_data.csv**

This will be a series of lectures focused on Azure AI Agents using the Code Interpreter. One of the strongest advantages of the Code Interpreter is its ability to perform data analysis and data visualization, and that is exactly one of the key use cases we will be putting to the test throughout this series.

To demonstrate this, we need some input data. So I’ve prepared a sample sales dataset, which we will be working with. We’ll be uploading a file named sales_data.csv as the input to our agent. The Code Interpreter needs this dataset so it can analyze and visualize the information we provide.

The structure of the dataset is very simple. It contains three or four columns: Date, Product, Revenue, Profit

In essence, we are giving the model a list of dates, a list of products, and the corresponding revenue and profit numbers. Think of it as a company wanting to understand which product generated the maximum sales and which product contributed the highest profit. These are exactly the types of insights we will be looking for.

Once the file is uploaded, we will test the Code Interpreter by asking our AI assistant—or AI agent—to analyze the data and generate some interesting visualizations for us. The exciting part is seeing what kinds of graphs and insights it produces automatically.

# **D) Demo: How to use CI in Agents Playground**

This lecture is going to be an interesting one because here we will explore how to use AI Agents together with the Code Interpreter, and we’ll also walk through the Agents Playground. To begin, you simply need to go to your Azure AI Foundry. From there, select the appropriate project — in our case, it is the Azure AI Project for Agents. Once selected, click Launch Studio.

When the studio loads, you’ll notice that an agent has already been created automatically. It displays an agent ID and assigns a default name, which you can change to something like agent_code_interpreter. It also shows the associated Azure OpenAI resource. As discussed earlier, every Azure AI Agent is always linked to an Azure OpenAI resource. We will make use of an existing deployment, such as GPT-4 or GPT-4 Mini. In later lectures, we can experiment with additional deployments, but for now we’ll keep things simple.

Next, you’ll see a section where you define your agent’s instructions. For this scenario, we’ll specify that the agent is responsible for data analysis and data visualization. These are the two primary capabilities we want from our agent.

We won’t be using the Knowledge feature here, but we will make use of Actions. When you click Add, you’ll see that one of the available tools is the Code Interpreter. Select it. Then choose your input file—the same file we discussed earlier, sales_data.csv. Upload it and save the configuration.

With that, your agent is fully set up. You can even check the Threads section, where you’ll notice that a thread has been created automatically. Now, return to Agents and click Try in Playground.

In the playground, you’ll get a chat interface. For example, you can begin by asking: “What is the uploaded data all about?” The agent will process the request using the Code Interpreter and respond with a summary—explaining that the dataset contains columns such as date, product, revenue, and profit.

Next, you can ask: “Can you create some interesting graphs for me?” The agent will analyze the data and suggest different types of visualizations. For instance, it may propose a pie chart showing the distribution of total revenue across products. If you like that one, you simply say: “This one.” It will generate the graph for you.

You can then request another visualization — for example, a scatter plot — and the agent will create that as well. It’s incredibly intuitive and powerful.

So that’s how you use the Code Interpreter inside AI Agents and interact with it through the Agents Playground.

# **E) Demo: Understand the Workflow for Graph Generator Agent**

This will be a quick video demonstrating the overall workflow for creating and running an agent using Azure AI Projects, specifically with the Code Interpreter tool. The idea is straightforward: the user submits a request to an Azure AI agent, and the agent—equipped with specific tools—in this case, the Code Interpreter—executes Python code, retrieves the results, and returns the response back to the user. This entire workflow is what we will be walking through in this session.

The first step involves setting up the environment and credentials. For this, we will upload the sales_data.csv file into our Google Colab environment. We will also upload our credential file, the API settings environment file, just as we did in previous lectures. These two files are essential to ensure proper configuration and authentication.

Next, we will create an AI agent using the Code Interpreter tool. As mentioned earlier, every agent uses a defined toolset, and the tool we are focusing on in this video is the Code Interpreter. After the agent is created, we work with concepts such as threads, runs, run steps, and messages. A thread represents a conversation session between the user and the agent. All exchanges—questions, responses, and any data—flow through messages within that thread.

The agent will process the user’s input, execute the code through the Code Interpreter, handle its responses, manage file outputs, and also deal with any error handling. Since our goal is data visualization, we will provide the sales data, ask the agent to explain what the data is about, and then request it to generate various graphs—similar to what we did earlier in the Agents Playground. Whenever the agent creates a graph, it generates an image file such as a PNG, and that file will also be saved so you can access it later if needed.

Finally, although optional, we will look at deleting the agent once we are done. This is good practice because if you repeatedly run code that creates agents, your Azure AI Foundry environment will accumulate a large number of unused agents. Clearing them helps keep your workspace tidy and efficient.

With that overview covered, we are ready to move on and start working through the program.

# **F) Demo: Upload the sales_data.csv & Environment variables file**

This is going to be an important lecture.

In this session, we’ll actually be uploading two essential files to our environment:
the sales_data.csv and the environment variables file.

Both of these are crucial—especially the environment file—because all authentication for our Azure AI agents will rely on those values.

Let’s go step by step.

First, inside Google Colab, click on the left panel and upload the required files.
You’ll need to upload:

The API settings file – this contains all the environment variables we’ll use.

The sales data CSV – the dataset we already reviewed.

Once uploaded, you’ll see both files listed in your workspace.

The environment file contains values such as the client ID, client secret, tenant ID, and project connection string.
We’ve already discussed each of these in earlier lectures—how to generate them and where they come from.
These values are fetched from your Azure AD app registration and your Azure AI Project configuration.

If you haven’t watched those lectures, I strongly recommend revisiting them, because everything we’re doing here builds on that foundation.

Next, we’ll install the three essential Python libraries:

azure-ai-projects → used to interact with Azure AI Projects via the API

azure-identity → handles authentication using the credentials in your environment file

python-dotenv → loads variables from the .env file into the notebook session

Once these libraries are installed, we’ll load the environment file and set each parameter—client ID, client secret, tenant ID, and project connection string—so they’re available for the rest of our code.

You’ll also see a quick confirmation printed out, showing that our environment variables are successfully loaded.

With this setup in place, our Azure resources—like the AI Hub, Project, and associated components—are ready to be accessed by our agent.

In the next lecture, we’ll move ahead with uploading the sales file to the agent, creating the agent instance, and initializing the thread.

# **G) Demo:Understand the Creation of Agent**

Let’s now break down the second part of the program, where we focus on authentication, uploading the file, creating the agent, and creating a thread. This is where the real magic happens. If you look at the code, it’s impressive how many steps we are able to handle with just a few lines. So let’s walk through each part carefully.

We start by importing the required Azure AI libraries. The first key component is the AIProjectClient. This is essentially the core client used to manage everything related to AI Projects—agents, threads, and file uploads. It provides the methods we need, such as create_agent(), upload_file(), and create_thread(). Along with this, we import the CodeInterpreterTool and FilePurpose. The Code Interpreter Tool is the mechanism that allows our agent to interpret code, analyze data files like CSVs, and generate insights. The FilePurpose enum simply clarifies the intent of the uploaded file—for example, specifying that the file is meant for agent use, such as analysis or querying.

Next, we have the ClientSecretCredential, which manages authentication. This uses the service principal credentials we configured earlier in Azure AD (or Entra ID). All the work we did during app registration now comes into play, enabling our program to securely access Azure AI resources. We also import Path from the pathlib module to handle file paths in a way that works consistently across operating systems.

Once the imports are ready, we authenticate and initialize the AI Project Client. Using the ClientSecretCredential, Azure authenticates the service principal without any user interaction. Then, with AIProjectClient.from_connection_string(), we establish a direct connection to our Azure AI Project using the connection string we loaded from the environment file. This step just combines the tenant ID, client ID, and client secret, and hands them over to Azure for secure access.

With authentication complete, we move on to uploading the sales CSV file. For this, we use upload_file_and_poll(). This method uploads the file and waits until the upload is fully complete before returning. Once done, it provides a file object containing metadata such as the file ID—which is what we’ll need for the next step.

Finally, we reach the core section: creating the agent and creating the thread. With a single, clean create_agent() call, we instantiate a new AI Agent. We specify the model (our deployment), provide a name, and define the agent’s instruction—something like “You are a helpful agent that performs data analysis and visualization.” We also specify the list of tools, where we include the Code Interpreter Tool and pass the uploaded file’s ID so the agent knows which file to work with. The tool resources indicate that the code interpreter tool is the active tool for this agent.

Once the agent is created, the program also creates a thread. The thread ID is returned, and this becomes extremely important because the thread maintains context across multiple interactions. This means our agent can remember the previous messages and continue the conversation seamlessly.

# **H) Demo: Create Thread and Message Convesation**

Now let’s move to the final part of the program, which focuses on starting an infinite loop to interact with the agent. This loop is what enables continuous conversation with the agent, processing messages until the user decides to end the session.

The structure is simple: we start a while True loop. Inside it, we check if the user message is "end". If it is, the loop breaks, terminating the interaction. Otherwise, the loop keeps running, continuously reading messages from the user and processing them in the thread.

For each user message, we call project_client.agents.create_message(), passing the thread ID, the role as user, and the content as the message itself. This is crucial because it ensures that the agent receives the user input correctly within the context of the ongoing thread.

Next, we process the interaction by calling project_client.create_and_process_run(). Here, the concept of a run and run steps comes into play. Each run represents a single execution of the agent in response to the message. This method requires both the thread ID and the assistant (agent) ID. Once the run finishes, the status is checked. If the run fails, an error is raised indicating that the execution was unsuccessful.

After processing the run, we fetch the agent’s responses. This is done by iterating over the messages in the thread to get the latest message, which is then saved. This ensures that all responses from the agent are captured for future reference or further processing.

In cases where the agent generates visualizations or graphs, this section of the code also handles saving the generated images to a specific location. This is important because the images are not just displayed—they are stored for later use, allowing you to review or include them in reports.

Finally, as a best practice, we include a cleanup step. Many agents can accumulate during testing, especially if you are repeatedly creating new agents. To avoid clutter in the Azure AI Foundry, it’s recommended to delete the agent once your testing is complete. This helps maintain a clean environment and avoids unnecessary resource usage.

# **I) Demo: Run the Agent & Create Graphs**

Now it’s time to actually execute our program. Before we run it, I recommend taking a quick look at the Azure AI Foundry under Agents. At this point, you will see only one agent currently active. Once we execute our program, new artifacts will start appearing—your agent will be created, a thread will be initialized, and other related items will be generated.

Let’s run the program. When executed, three main actions happen simultaneously: the file gets uploaded, the agent is created, and the thread is initialized. After execution, you will receive the file ID, the agent ID, and the thread ID. These IDs are essential as they reference the uploaded data, the agent instance, and the conversation thread. Once you refresh your Foundry, you will see that the new agent and thread have appeared.

Next, we can interact with the agent. For example, you can ask, “What is the uploaded data all about?” The agent will examine the uploaded CSV file and respond with a structured summary of the data. It identifies columns like date, product, revenue, and profit, and even provides a preview of the dataset. The formatting is neat and clear, making it easy to understand the contents at a glance.

Let’s now look into the thread in Foundry. As we studied earlier, a thread contains all messages exchanged between the user and the agent. This maintains context across multiple interactions. For instance, the user’s message asking about the data is stored in the thread, and the agent’s response appears right alongside it. If you ask another question, it will continue under the same thread, keeping all communication organized.

We can also request the agent to create a graph. For example, asking it to generate a graph for total revenue and profit by product will trigger the agent to process the data and create a visual representation. Once the run status shows as complete, the graph is generated and saved as a file. The file is stored in the content directory, usually with a unique identifier, and you can easily download it to view the visualization. In our case, it shows total revenue and profit for different products such as cameras, headphones, and tablets.

Finally, since this is primarily a learning exercise, it’s a good practice to end the conversation and delete the agent afterward. This prevents unnecessary accumulation of agents in your Foundry environment and keeps it tidy. With this workflow, you now have a solid understanding of how Azure AI agents interact with the Code Interpreter, handle files, maintain context through threads, and generate outputs like graphs.

# **VIII) Azure AI Agent Service Action Tools - OpenAPI 3.0**

# **A) What is OpenAPI 3.0 ?**

Now, as I promised, whenever Microsoft releases any new tools or features inside the Azure AI Agent Service, I will update you all. Today, I’m here to talk about the OpenAPI 3.0 specified tool. Recently, Microsoft introduced this tool, and just like we worked with the Code Interpreter previously, we will now explore how agents can work with the OpenAPI 3.0 tool.

So, what is OpenAPI 3.0? For those new to this, it’s important to understand its purpose. OpenAPI is a standard, language-agnostic format for describing REST APIs, also known as RESTful APIs. The beauty of this standard is that it allows both humans and machines to understand the capabilities of web services without needing to look into the source code or documentation. Essentially, it lets developers define all aspects of an API in a structured way, including available endpoints, parameters, response types, and authentication methods. Originally, this format was known as Swagger, but the modern standard is now OpenAPI 3.0.

There are a few key highlights of OpenAPI 3.0. It can be written in YAML or JSON format, and the current example we are using is in JSON. OpenAPI 3.0 was introduced in 2017 as the successor to Swagger. Understanding the structure of an OpenAPI 3.0 specification is important, so let’s break it down using a real example, which we will also use in our course.

First, we have the info section, which provides API metadata such as the title, description, and version. For example, in our case, the API is the Yahoo Finance stock API. The title specifies the API name, the description gives a brief explanation of what the API does, and the version tells us the specific version of the API being used, such as v1.

Next, we have the servers section, which specifies the base URL where the API is hosted. In our example, the API is hosted on Yahoo Finance via RapidAPI. We are using RapidAPI to access Yahoo Finance instead of calling the Yahoo API directly, as it provides a more convenient and reliable interface.

The paths section defines the available endpoints of the API. Each endpoint specifies the operations you can perform, like GET for fetching information. For instance, the markets/code endpoint allows us to retrieve market information for a given stock. The GET operation contains several important pieces of information, such as the operation ID (a unique identifier for the operation), a summary (short description), and parameters. Parameters are particularly important because they define the inputs you need to send with your API request. For example, the ticker parameter specifies which stock you want to query, like Apple, Microsoft, or Tesla.

With Azure AI Agent Service, OpenAPI 3.0 integrates seamlessly as a tool for agents. You can upload your YAML or JSON schema to Azure AI Agent Service, configure authentication using API keys (for example, from RapidAPI), and let the agent dynamically invoke API calls at runtime. The agent can then interact with these APIs and retrieve data as part of its workflow.

To make an API call, here’s how it works in practice. The base URL might look like https://yahoo-finance15.p.rapidapi.com/api/v1/markets/code. You then specify the endpoint, such as markets/code, and pass the required parameter, for instance, ticker=Apple. This allows the agent to dynamically fetch stock information using the OpenAPI 3.0 specification.

At this point, this explanation is theoretical, providing the foundation you need to understand OpenAPI 3.0. In the upcoming lectures, we will demonstrate how to practically work with OpenAPI 3.0 inside Azure AI Agent Service, upload the schema, configure authentication, and make API calls dynamically.

# **B) Understanding the Workflow for Yahoo Finance**

Let’s try to understand what we are aiming to achieve with this set of programs and videos. The goal is to work with the OpenAPI tool, which is connected to our Azure AI agent. But how does this actually work internally, or under the hood? Let’s break it down step by step to make it simpler.

From a user perspective, all you need to do is provide a ticker symbol or ask for the current stock price for a company, say Tesla. You simply express your interest, and the Azure AI agent does all the heavy lifting to give you the final response. For the user, this is the only part that is visible.

However, behind the scenes, the Azure AI agent is interacting with a tool that is based on OpenAPI. This tool connects to the Yahoo Finance API, which provides the stock data. But rather than calling the Yahoo Finance API directly, we use a service called RapidAPI, which acts as a portal or intermediary. The agent calls the RapidAPI, which in turn fetches data from Yahoo Finance. This layer simplifies access and provides additional features like authentication management and rate limiting.

A key component in this process is the connector. The Azure AI agent needs a connector to communicate with the OpenAPI tool. This connector is configured using RapidAPI keys and the OpenAPI JSON schema. The JSON schema defines the API endpoints, parameters, and responses, while the RapidAPI key handles authentication. Once this connection is established, the agent can dynamically fetch data from RapidAPI, process it, and return the response to the user seamlessly.

If this still sounds a bit confusing, don’t worry. In the upcoming videos, we will go step by step, showing how to create the connector, upload the OpenAPI schema, configure authentication, and make the API calls through the Azure AI agent. By the end, the workflow will become very clear and practical.

# **C) Demo: Create RapidAPI Key**

In this lecture, we’ll look at how to use RapidAPI in conjunction with your Azure AI agent. It is essential for your agent to have a connector, and to configure this connector, you need an API key. But where does this API key come from? The API key is generated through RapidAPI.

To get started, go to rapidapi.com and create an account. You can either sign up directly or use a Google login, which is what I did. Once logged in, navigate to the console on the right-hand side. Here, you will see a section called Applications. Initially, no applications exist, so you need to create one. Give it a name, for example, “Yahoo Finance,” and add a description if needed. Once you click Create, the application is generated, and within a few seconds, your API key will appear.

Previously, the authorization keys section would have been empty, but now you’ll see your RapidAPI key listed. This key is essential for connecting your Azure AI agent to RapidAPI, though it should always be kept private. The key typically starts with a string like d45…. We will use this API key in the next lecture when configuring our agent.

The next step is to navigate to Collections on RapidAPI. Here, we will use a collection called Yahoo Finance. By searching for “Yahoo Finance,” you will find the relevant API collection. Clicking on it reveals the RapidAPI host and RapidAPI key, along with the full URL endpoint. This URL is the same as the one we discussed in the OpenAPI theory lecture: https://yahoofinance15.p.rapidapi.com/api/v1/markets/code.

You can even test the endpoint directly in RapidAPI. For example, by specifying a ticker symbol like Apple, the API will return detailed stock information, including the exchange (NASDAQ), latest sale price, net change, and other key metrics. This is exactly the data we will be pulling into our Azure AI agent, allowing it to fetch real-time stock information dynamically.

# **D) Demo: Create a Connection to RapidAPI in Azure**

Now it’s time to create your connector. You might remember that we discussed the concept of a connector earlier. Essentially, a connector links two points—in this case, it connects RapidAPI to our Azure AI agent.

To create the connector, go to your Azure AI Foundry and click on New Connection. You’ll need to select Custom Keys because this is where we will add our RapidAPI credentials. Once selected, click Add Key-Value Pair.

Here, you need to provide a name and a value. The value comes directly from your RapidAPI account. Specifically, you will use the key called X-RapidAPI-Key. Copy this key from RapidAPI and paste it as the value in Azure. You can also give a descriptive connection name, for example, Yahoo-Finance.

There’s an option to define access—by default, it’s shared with all projects in your workspace, but you can restrict it to the current project if needed. Once everything is filled in, click Add Connection.

This step is very important because your connector will be required when creating a tool inside the Azure AI Agent Service. In the next lecture, we will use this connection to configure an OpenAPI 3.0 tool, enabling the agent to make API calls securely using your RapidAPI key.

# **E) Demo: Create a Stocks Agent and Attach OpenAPI 3.0**

The time has finally come to create your own stocks agent. To start, click on New Agent and give it a meaningful name. For example, you can call it Stocks Agent. This agent will be used to retrieve stock prices and other related information.

Next, you need to choose a deployment. In this example, we are using GPT-4 or mini. You can also provide a brief description for your agent, such as: “A helpful agent based on OpenAPI 3.0.”

Now, it’s time to configure the action tools. Microsoft has introduced the capability to use OpenAPI 3.0 as a tool. Click on Action Tool and select OpenAPI 3.0. Then, give your tool a name, for example, Yahoo Finance Tool, and add a description like “Based on RapidAPI for fetching stock prices.”

The next step is to define the schema for this tool. This is where your OpenAPI JSON schema comes into play. If you’ve followed the previous lectures, you can copy the schema from the resources section and paste it here. For the authentication method, choose Connection and select the connector we previously created, which is Yahoo Finance.

Paste your OpenAPI JSON schema in the designated area. This schema specifies important details such as version information, server URL, available paths like markets/code, and parameters such as ticker. Once everything looks good, click Next to review and then Create Tool.

After this step, a tool will be created and associated with your Stocks Agent. This OpenAPI 3.0-based tool connects to RapidAPI, which in turn fetches data from Yahoo Finance. In the next lecture, we will put this agent to the test by running prompts and queries against it.

# **F) Demo: Test the Stocks Agent in Playground**

Now it’s time to put our Stocks Agent to the test and see if it can fetch the latest stock prices accurately. To do this, click on Try in the Playground. This will open a chat interface where you can interact with your agent and run queries.

To start, you can try something simple. For example, just type “Tesla”. That’s it—you don’t need to specify anything else. The agent is intelligent enough to understand that you are interested in details about Tesla.

As a result, the agent returns relevant information such as the company name, stock price, exchange (Nasdaq), and other details, all fetched from the RapidAPI data source.

You can also ask the agent to create a table of the latest stock prices, including information like the 52-week low and 52-week high for Tesla. Notice that even without providing the ticker symbol, the agent is able to infer the correct stock based on the company name.

In this test, the agent successfully generated a table summarizing the latest stock price and 52-week range for Tesla. For example, the latest stock price was $285, the 52-week low was $138, and the 52-week high was $488—a great time to buy!

Overall, our Stocks Agent performed exceptionally well, delivering accurate, up-to-date information based on the latest stock prices.

# **G) Demo: Install the Libraries and Setup Environment**

Let’s go step by step and see how we can create the same Stocks Agent using Python code. The architecture remains the same: Yahoo Finance communicates with RapidAPI, and through the OpenAPI tool connected via the connector to the Azure AI Agent, we can execute our queries seamlessly.

The first step is to install the required libraries and set up the environment. Some of these libraries we have discussed before, but let’s quickly review them. The Azure AI Projects library enables the creation and interaction with AI agents. Azure Identity provides different credential types for authenticating with Azure resources.

A new library for you here is JSON Ref, which helps parse JSON files and supports $ref references commonly used in OpenAPI specifications. This is especially useful for working with OpenAPI JSON schemas. Once you execute the installation commands, all the required SDKs, agents library, and dependencies will be installed.

Next, there are two files you need to upload as part of the setup. The first is your OpenAPI JSON file, the same one used when creating the tool or agent in the GUI. You can download this from the resources section and upload it for your code-based setup. The second is the API settings file, where you specify your client ID, tenant ID, project connect string, and other API-related details.

For the setup in code, you will import os and load_dotenv to load the environment file. The client ID, client secret, tenant ID, and project connect string are then automatically picked from this file. Once this is executed, your environment is ready, and the Azure credentials can be configured.

In the next video, we will focus on configuring the Azure credentials and initializing the Azure AI Project client so that the Stocks Agent can start executing queries programmatically.

# **H) Authenticate/Initialize/ Load OpenAPI Spec**

In this video, we will focus on authentication with Azure, initializing the Azure AI Project client, and loading the OpenAPI specification.

First, we need to import the necessary libraries. These libraries are required to handle authentication, work with the Azure AI Project client, and parse OpenAPI specifications.

Next, we configure the Azure credentials using the Client Secret Credential. This type of credential is used for confidential client applications, such as scripts or backend apps, rather than user-interactive applications. We provide three parameters to the credential: tenant ID, client ID, and client secret. These values are stored in the API settings.env file. The Client Secret Credential authenticates your app using Azure Active Directory (AAD), ensuring secure access to Azure resources.

After authentication, we move on to initializing the Azure AI Project client. We use the AIProjectClient, which connects to your Azure AI project workspace using the project connect string. This string is also available in your API settings.env file. Once initialized, this client allows you to manage agents, tools, connections, and threads, making it a central piece of the workflow.

Next, we focus on loading the OpenAPI specification. The OpenAPI spec serves as a blueprint for the Yahoo Finance API, describing endpoints, inputs, outputs, and other details. We use jsonref.load to load the specification, which also resolves any $ref pointers within the JSON. In this example, the file openAPI.json is read and loaded into the program.

With the OpenAPI spec loaded, we are now ready to extract connection lists, create authentication objects, and initialize OpenAPI tools, which will be covered in the next lecture.

# **I) Get Connection / Create Auth Object / Create OpenAPI Tool**

In this lecture, we will cover three key tasks: extracting the connection ID, creating the authentication object for the OpenAPI tool, and initializing the OpenAPI tool with the Yahoo Finance API. Let’s go through these steps one by one.

The first task is extracting the connection list. Here, we retrieve the list of connections already configured in your Azure AI project. We filter the connections by the name “Yahoo Finance” and store the result as a unique connection ID. This is necessary because there isn’t a direct way to fetch the connection ID. Essentially, this ID links your Azure AI project to the Yahoo Finance connection you created earlier.

The second task is creating the authentication object for the OpenAPI tool. This step prepares the authentication schema, telling the assistant how to authenticate with the Yahoo Finance API during usage. We use the OpenAPI connection security scheme and pass the connection ID. Although it’s called Yahoo Finance here, it’s essentially the Rapid API key that we set up earlier. By doing this, we create an authentication object that will be used by the OpenAPI tool.

The third and final task is initializing the OpenAPI tool with Yahoo Finance. Here, we call the OpenAPI tool and pass the following parameters: a name (“Get Yahoo Finance data”), the OpenAPI specification, a description (“Fetch real-time stock market and financial data from Yahoo Finance”), and the authentication object we just created. This step wraps the OpenAPI specification into a tool that the assistant can use, making it ready for the agent to consume.

At the end of this setup, the tool becomes a reusable component for the assistant. When we later create our agent, it will make use of this OpenAPI tool, just like we did previously in the GUI. The tool acts as a wrapper around the OpenAPI spec, enabling the agent to fetch real-time stock data via Rapid API.

In the next lecture, we will see how to create the agent and start the conversation thread, continuing the workflow we have been building in the previous sessions.

# **J) Create Agent / Thread / Conversation Loop**

In this final part of the program, we focus on creating the assistant, which in this case is our Azure AI agent, setting up the conversation thread, and implementing the interactive loop.

First, we create the agent using project_client.agents.create_agent(). We pass the model name, which in our example is GPT-4 or mini. We also give the agent a name — “Yahoo Finance Assistant” — and a description: “You are an intelligent assistant that provides real-time financial and stock market data.” Since this is a stocks agent, it is specifically designed to fetch and provide financial data.

Next, we specify the tools for the agent. Unlike previous examples where we used the code interpreter tool, here we use the OpenAPI tool definitions. This comes from the OpenAPI tool we initialized earlier with Yahoo Finance via Rapid API. This ensures that the agent can fetch real-time stock and financial data dynamically using the tool. The agent is now fully set up with its model, purpose, and tool assignment.

After creating the agent, we create a conversation thread. The thread tracks all chat messages, which allows the agent to maintain context throughout a conversation. This is essential for intelligent, context-aware interactions.

We then start the interactive loop. The loop continuously takes user input via input(). Each message is sent to the agent through the thread, triggering the assistant to think and respond using its tools. This is achieved using project_client.agents.create_and_process_run(). The agent processes the input, generates a response, and we retrieve and print the latest message back to the user.

The loop continues until the user types “end”, at which point the interaction stops. Finally, the agent is deleted to release resources and prevent clutter in the Azure AI project. This ensures that agents with the same name do not accumulate unnecessarily.

In the next lecture, we will demonstrate running the agent in action and testing its ability to fetch real-time stock and financial data.

# **K) Execute the Program and run Queries**

Now we have reached the stage where we can actually run or execute the program. Let’s see what happens when we do that.

Upon execution, the program will create the agent and the conversation thread. If we check the Foundry workspace, we can confirm that a new agent has been created — the Yahoo Finance Assistant. One important thing to note is that the tool “Get Yahoo Finance Data” has been neatly attached to this agent. This ensures that the agent can fetch stock and financial data dynamically.

Looking back at the source code, we see that the agent name is Yahoo Finance Assistant, and the tool name is Get Yahoo Finance Data. Everything is correctly configured.

We can now test the agent. For example, we can input a simple query like Tesla, and the agent will fetch the relevant data from Rapid API via the Yahoo Finance API. Similarly, if we input Apple, the agent recognizes it as Apple Inc. (AAPL) listed on Nasdaq, and returns the latest stock price, 52-week range, and other financial details. The agent intelligently interprets company names even without explicit ticker symbols.

Once we are done testing, we simply type “end”. The program will then end the conversation and automatically delete the agent, releasing resources and keeping the workspace clean.

This demonstrates the complete workflow of integrating Azure AI agents with OpenAPI tools, using Yahoo Finance data via Rapid API, and creating a real-time, interactive stocks assistant.

Thanks for watching, and I hope this gives you a clear understanding of how Azure AI agents, OpenAPI specifications, and the Rapid API work together to provide intelligent, real-time responses.

# **IX) Azure AI Agent Service Knowledge Tools - Bing Search**

# **A) Intro to Grounding with Bing Search**

After exploring the various action tools in Azure AI agents, it’s now time to dive into the knowledge tools provided by Microsoft.

The first knowledge tool we will focus on is grounding with Bing Search. Most of you are likely familiar with Bing as Microsoft’s search engine. What Microsoft has enabled is the ability for your agent to leverage Bing’s search capabilities to fetch real-time information and provide accurate responses.

In this lecture series, we will cover:

What grounding with Bing Search means and how it works.

Supported models for Bing Search within Azure AI agents.

Creating a Bing Search agent in the agents playground (no-code/low-code approach).

Implementing the same functionality using Python code:

Creating a Bing resource.

Setting up a connection for the agent.

Installing required libraries.

Understanding and executing the Python code.

As always, we will explore both the no-code/low-code approach and the full Python implementation, giving you flexibility depending on your workflow.

Get ready to see how your agent can interact with real-time Bing Search to provide up-to-date knowledge in response to user queries.

# **B) What is Grounding with Bing Search ?**

Now it’s time to explore the knowledge tools available in the Azure AI Agent Service. The first tool we’ll discuss is grounding with Bing Search.

To give some context, one limitation of large language models (LLMs) is that they are trained only up to a specific point in time. This means that if you ask a model questions like “What’s the weather today?” or “What’s the top news for today?”, it won’t be able to provide up-to-date answers.

Microsoft and OpenAI identified this gap and proposed a solution: combining the generative capabilities of LLMs with live search capabilities. In other words, if the LLM cannot answer a question on its own, it can dynamically search the web to find the most current information. Microsoft leveraged Bing, its search engine, to enable this functionality. This integration is what we call grounding with Bing Search.

There are a few important points to note about using this tool. First, costs: grounding with Bing Search incurs additional charges. Microsoft recommends checking the pricing details before using it. Currently, it allows up to 150 transactions per second or 1 million transactions per day, and the cost is $35 per 1,000 transactions. Essentially, this feature allows your AI agent to utilize the power of Bing Search APIs as a knowledge source to ground responses.

Second, deployment restrictions: grounding with Bing Search is not available with every model deployment. It is supported only on specific GPT models, including: GPT-3.5-turbo, GPT-4-0-125, GPT-4-turbo, Certain versions of GPT-4

Attempting to use unsupported models will result in failures, so it is important to select the correct deployment when configuring your agent.

Finally, there are multiple ways to use grounding with Bing Search. You can create a Bing resource and connect it programmatically when using API calls, or you can leverage it directly in the Agents Playground, which is very straightforward and user-friendly.

In the next video, we will demonstrate step by step how to configure and use grounding with Bing Search, both programmatically and in the playground. By now, you should have a solid understanding of what grounding with Bing Search is, why it’s useful, and the key considerations for using it effectively.

# **C) Demo : Create a Bing Search with Agent Service**

Now it’s time to put grounding with Bing Search to the test and see how it works in practice.

Before we start, it’s important to remember that deploying the correct model is crucial. In this case, I am using GPT-4-0-513. If you check the models I have deployed, you’ll see that GPT-4-0-2 with version 0513 is the one supported by agents, and that is the model I will be using for this demonstration.

Next, I navigate to Agents and choose the deployment. Since agents are based on deployed models, selecting the right one is critical. I select GPT-4-0-2 (0513) and then create a new agent. I give the agent a name—Agent Grounding with Bing—and provide system instructions: essentially, this agent’s role is to assist with Bing searches.

Now, we move to the knowledge tools section. Here, you can see the “Knowledge” option; if it’s grayed out, it usually means the wrong model deployment was selected. With the correct model, I create a new connection for grounding with Bing Search. This involves creating a Bing Search resource in the Azure portal.

During the resource creation, I select the appropriate resource group and give it a name, such as Web Searching. It’s important to choose the correct pricing tier, review the settings, and then create the resource. Once created, this Bing Search resource is visible when creating the connection. It comes with its own authentication key and clearly notes that any user in the same hub with access to the project can utilize this resource.

After creating the connection, it shows as connected, and the Bing resource is now available as a knowledge tool for the agent. At this point, we can test it in the playground. Once loaded, you can verify the agent details, including the agent ID, name, deployment, and the linked knowledge resource, which in this case is Web Searching.

To test the agent, I asked: “Please give me the latest news for today.” Normally, a large language model cannot provide real-time information. However, since this agent is grounded with Bing Search, it fetched the latest news by querying the Bing resource. The response included highlights such as the Ukraine conflict, gold smuggling cases, Supreme Court decisions in India, and political developments, along with references to credible sources like The Hindu and other news outlets.

This demonstrates that the agent is now capable of performing real-time web searches, supplementing the limitations of the base language model. The integration of Bing as a knowledge base allows it to provide up-to-date information effectively.

Thanks for watching, and now your agent is ready to perform live web searches using Bing Search.

# **D) Demo: Create a Bing Resource & Create Connection**

The aim of this lecture series is to demonstrate how to implement grounding with Bing Search using Python code. As shown in the diagram, the flow works as follows: the user submits a query or request to the Azure AI agent. The agent is intelligent enough to recognize that it needs to use the knowledge tool, which in this case is grounding with Bing Search. For example, if you ask, “What is the top news for today?”, the request is routed to the agent, which then interacts with the Bing Search knowledge tool. The tool retrieves the relevant information and sends the response back to the user.

Before we start coding, there are a couple of prerequisites. First, you need to create a Bing Search resource in Azure. Since this is a separate entity from Azure AI services, you also need to create a connection to this Bing resource inside your Azure AI project. These two steps lay the foundation for using Bing Search with your agent programmatically.

To create the resource, go to your Bing resources in the Azure portal and select Grounding with Bing Search. Choose a resource group (I usually pick a standard one), give your resource a name such as Web Search Coding, select the region as Global, and choose the pricing tier—typically the default, $35 per 1000 transactions. After confirming the details, click Review and Create, and then create the resource. Once deployed, you can verify the deployment progress and check the resource details. The resource should also appear in your Bing Resources list, confirming that Web Search Coding is now available.

After the resource is created, the next step is to create a connection to it. Inside your Azure AI Foundry, navigate to Connected Resources in your hub. Click New Connection, and when prompted to add a connection to external assets, select Bing. It will display the Grounding with Bing Search option, and you can pick your newly created resource, Web Search Coding. Click Add Connection, and your connection will be established shortly.

With the resource and connection set up, the groundwork is complete, and the foundation for using Bing Search in your Python code has been laid. In the next step, we will start writing code to interact with the agent and see how to query Bing Search programmatically.

# **E) Demo: Setup environment & install libraries**

Now it’s time to set up your environment and install the required libraries. We’ve already discussed most of the SDKs and libraries you need, but let’s quickly recap. The main library is Azure AI Projects, which provides the SDK for managing AI projects and interacting with AI agents on Azure. Next, we have Azure Identity, which handles authentication for Azure services using different credential types. Finally, load_dotenv is used to load environment variables from your .env file, making it easier to manage sensitive information like keys and IDs. You can execute the installation, and it will check your requirements and install any missing libraries.

The next step is to configure your API settings by setting all the necessary environment variables. These include your Client ID, Client Secret, Tenant ID, Project Connection String, and a new piece for this setup—the Bing connection name. One important note that often confuses people (myself included) is the distinction between the resource name and the connection name.

For example, your Bing resource might be named web-search-coding, but the connection name you created in your connected resources could be Web Search Coding. It’s crucial that the connection name is correctly specified in your environment variables, otherwise your code will fail to execute properly. I even recommend printing the value after loading it to verify that it matches your connection name exactly.

In this part of the setup, we are simply specifying the Client ID, Client Secret, Tenant ID, and the Bing connection name. Once this is done, we will move on to the next stage: creating the agent and integrating it with the knowledge tool.

# **F) Demo: Understand the Code**

Welcome back, folks. Now it’s time to dive into the main part of the program and understand the logic step by step. The first part involves importing the Azure SDK and authentication classes. The AIProjectClient is the main class for managing AI projects and interacting with agents, while the ClientSecretCredential handles authentication using the Client ID, Client Secret, and Tenant ID that we set up during app registration. A new addition here is the Bing Grounding Tool, which allows integration with Bing search services to enhance the AI agent’s capabilities.

The next step is configuring Azure credentials. Here, we create a ClientSecretCredential object for secure authentication. This uses a service principal approach to authenticate with Azure Active Directory, and the credential is later passed to the AI Project Client for making API calls securely.

Once credentials are set, we initialize the Azure AI Project Client using AIProjectClient.from_connection_string. This sets up secure access to the project using the connection string stored in environment variables. The client is responsible for managing agents, messages, and tools within the Azure AI project.

Next, we focus on retrieving the Bing Search Resource Connection ID. The purpose of this step is to access the Bing search resource using its connection name, in this case, Web Search Coding. The unique connection ID is necessary for linking the Bing search tool to the AI agent. A simple print statement confirms that we’ve successfully retrieved the connection ID.

With the connection ID in hand, we initialize the Bing Grounding Tool. This creates an instance of the tool that allows the AI agent to use Bing search results as part of its responses.

The core of the program is creating the AI agent. The model used is GPT-4-2, which supports the Bing grounding tool. We give the agent a name and simple instructions, such as “You are a helpful assistant that provides coding assistance using Bing searches.” We pass the Bing search tool to the agent for external information retrieval. Additionally, headers are used to enable preview features for enhanced capabilities.

Every agent is associated with a conversation thread, which maintains context across multiple interactions. This is critical for ensuring that the agent remembers the ongoing conversation. Once the thread is created, we move into the interactive loop, which continuously interacts with the user.

Inside the loop, the user’s input is sent to the agent as a message within the current conversation thread, distinguishing between user messages and agent responses. The agent processes the message, and the run’s status is checked to ensure processing was successful. If it fails, the error message is printed, and the loop exits. Finally, the agent’s response is retrieved and displayed to the user.

The purpose of this program is to provide an interactive experience where the agent can fetch the latest information using Bing as a knowledge tool, maintaining context throughout the conversation. In the next video, we will execute the program and observe its functionality in action.

# **G) Demo: Execute the Code**

The time has finally come to execute our code. First, if you go to your agents and refresh the page, you will notice that there is only one agent created so far, named agent_CL.

Now, let’s return to our code and reconnect. Executing the code will print the connection ID, which we can verify, and it will create a new agent along with a conversation thread. After refreshing the agents page, you will see that a new agent has been created, named “my agent for Bing coding”.

At this point, the code is waiting for user input. For example, if you type “Give me the top news for today”, the agent activates the Bing search capabilities. It searches for the latest news and provides a summary. The response might include headlines such as political developments, legal news, or global events, clearly demonstrating how the Bing tool integrates with the agent to fetch real-time information.

Once you are done testing, typing “end” will terminate the conversation. This not only ends the interactive session but also deletes the agent, helping maintain a clean workspace. Without this step, running the code repeatedly would create multiple agents, cluttering your Azure AI project. One limitation to note is that the agent portal does not allow bulk deletion—you need to delete agents individually if done manually.

This approach ensures that your code and project environment stay clean, while still allowing you to create and test agents as needed. By automating agent deletion at the end of the session, you avoid unnecessary accumulation of agents and keep your workspace organized.

# **X) Azure AI Agent Knowledge Tools - File Search**

# **A) Intro to File Search**

It's now time to talk about the next knowledge tool, which is File Search.

Historically, file search has always been present as part of the Assistance API from OpenAI. What Microsoft has done is bring file search into the Azure AI Agent Service, integrating it as part of their knowledge tools ecosystem.

So, what exactly does file search provide? File search is one of the best solutions if you want to search against your own documents, particularly if your documents are stored on Azure Blob Storage. It is designed to help implement RAG (Retrieval Augmented Generation), enabling more intelligent querying and retrieval from your data.

As part of this lecture series, we will go through the workflow for file search and how you can utilize it with the Azure AI Agent Service. Similar to other tools, we will cover both no-code and code-based approaches. In the no-code scenario, you can leverage the Foundry interface, while in the code-based approach, you will need to create your vector store, build your agent, and manage your threads to process messages.

To make this practical, we will take an example using a GPT-4 system card. This document will be uploaded into file search, and we will demonstrate how to query against it to retrieve relevant results. This set of demos will help you understand how file search works end-to-end and how it can enhance your document querying and knowledge retrieval capabilities.

# **B) What is File Search ?**

This is your instructor, Joy. First, I’d like to really appreciate the love and support you have shown for the course. A big thanks for all the comments and compliments you have shared.

Now, we are studying the Assistance API. So far, we have looked at function calling and the code interpreter. Today, it’s time to explore another type of Assistance API tool called File Search.

So, what exactly is file search? File search augments the assistant with knowledge from outside its model, which is very important. The word augment might ring a bell because it connects with RAG (Retrieval Augmented Generation). Essentially, file search provides the same capabilities as RAG. It allows the assistant to use generative capabilities while relying on your private data for retrieval.

OpenAI automatically parses and chunks your documents, identifies important keywords, creates embeddings, and stores them. As we know, any document, sentence, or word needs to be converted into embeddings to be stored in a vector database. This functionality is what makes file search powerful.

Let’s talk about chunking. Chunking is the process of breaking a large document into smaller pieces, or chunks, which makes processing and searching much easier. File search uses both vector search and keyword search to retrieve relevant information. Vector search enables semantic search, understanding the context of a query, whereas keyword search simply looks for exact words or phrases. For example, searching for “real estate” will match the phrase in keyword search, but vector search understands the context and relevance of queries.

It’s important to note that file search incurs additional charges beyond the token-based fees for Azure OpenAI usage. Currently, it costs $0.10 per GB of vector storage per day, indicating that a vector storage or database is used behind the scenes, although Microsoft hasn’t publicly disclosed the exact database.

The vector store stores embeddings created from your documents. When you perform a search, your query is converted into an embedding, and the vector store identifies the chunks most similar in meaning. When a file is added to a vector store, it is automatically parsed, chunked, embedded, and stored. This store supports both keyword search and semantic search.

Another key feature is automatic updates. When new files are uploaded to Azure OpenAI file search, they are automatically processed for future searches without additional setup. You don’t need to manually handle chunking or embedding — everything happens under the hood, making it easy to search newly added files.

To better understand, let’s consider the workflow diagram:

User Interaction: The user submits a query, for example, “What is the refund policy?”

Query Handling: The query is sent to the OpenAI or Azure OpenAI model. The assistant understands the user’s intent and retrieves the required information.

Vector Store Lookup: Uploaded files are chunked, converted into embeddings, and stored in the vector store. The assistant queries this vector store, performing a vector similarity search to find the closest matches.

Response Generation: The retrieved information is then used to generate a coherent, context-aware response. The assistant leverages its generative capabilities to craft a final response. For example, it might reply, “Refunds are allowed within 30 days of purchase,” based on the uploaded document.

# **C) Demo: Utilize File Search with AI Foundry**

With Azure AI Agents, it’s now time to explore another knowledge tool: File Search.

The easiest way to use file search through the GUI is to create a new agent. You can give it a name, for example, Agent-FileSearch. The system automatically assigns an Agent ID, which is fine. Next, you need to select a deployment; here, we can use GPT-402. You can also provide instructions or a system prompt, such as: “Help me with RAG and file search, and display results only from the contents of the document.” This ensures the agent uses retrieval augmented generation (RAG) and limits results to the document content.

Next, under Knowledge, you click Plus. Unlike the grounding we saw with Bing Search, this is File Search. Here, you upload your documents. This introduces an important concept: the Vector Store. A vector store enables semantic search, not just text-based keyword search. It works by converting text into vector embeddings and storing them for efficient retrieval.

To demonstrate, let’s upload a file, for example, a GPT-4 system card, which will also be available in the resources section. When uploading, Azure OpenAI processes the text, chunks it, converts it into vector embeddings, and stores it in a vector database. Behind the scenes, the vector store is powered by this database. When you later query the system, your query is also converted into an embedding, which is then compared with the stored embeddings to find the most relevant chunks of data.

During retrieval and response generation, the retrieved text chunks act as context for the model, allowing it to generate an accurate answer. The best way to test this is via the Playground. Here, your knowledge tool — the agent and vector store — is directly embedded, and the file is uploaded.

For example, you can input a query like: “Summarize the document in five lines.” Even if the document is large (10–20 pages), the agent processes it and returns a concise summary. Another query could be: “I am concerned about cybersecurity. Give me some tips based on this document.” The agent then provides relevant advice, such as phishing prevention, vulnerability monitoring, secure algorithms, and using HTTPS for communication — all based on the content of the uploaded document.

You can even explore further. For instance, if you want more details about secure algorithms, the agent provides references, such as Bcrypt or Argon2, along with the sources it used.

Overall, this demonstrates how File Search with Azure OpenAI and the Azure AI Agent Service can be effectively used to query documents and retrieve contextually relevant information using RAG and vector-based semantic search.

# **D) Demo: Understand the workflow**

It’s now time to explore how the File Search tool can be integrated with Azure AI Agent using Python code.

As part of this lecture, the goal is to keep things simple and focus on understanding the workflow and the steps required to implement it programmatically.

From the workflow perspective, it’s straightforward: the user sends a request to the Azure AI agent. The agent intelligently determines that it needs to interact with a tool, and in this case, the tool is the File Search tool. Behind the scenes, a vector store or vector database is created, but the user only receives a vector store ID — the details of the underlying database are abstracted away.

The File Search tool allows the agent to perform semantic searches against the uploaded files, not just simple text-based searches. Once the relevant information is retrieved, the Azure AI agent sends the response back to the user. This response can be formatted as bullet points, tables, or any other structure based on the user’s request.

The key features of this approach include:

Uploading files to create a vector store for search and retrieval.

Performing semantic search on the uploaded documents.

Generating context-aware responses based on the retrieved content.

In this example, we will upload the GPT system demo file (the system card file) and create an AI agent powered by GPT-4 Mini integrated with the file system. As emphasized before, you will use a deployment, in this case probably GPT-4 or GPT-4 Mini.

Next, you set up a conversation thread. Threads are crucial because they maintain context for the conversation. Messages are attached to these threads, and the uploaded files are linked to messages to enable content-based responses. The agent processes user queries and retrieves relevant responses using the uploaded files.

This example demonstrates a very simple workflow: you upload a file, query against it, and observe the results generated by the agent using the File Search tool. It provides a clear, hands-on understanding of integrating file search with Azure AI Agent using Python.

# **E) Demo: Install Libraries & Setup Environment**

This will be a very quick video focused on installing the Azure AI Projects SDK and the Azure Identity library for authentication. The lecture covers how to install the necessary libraries and set up your environment.

As we’ve discussed in previous lectures, we won’t go into too much repetition. The process is straightforward: simply run pip install for azure-ai-projects, azure-identity, and python-dotenv. You already know the importance of these libraries from earlier discussions.

One important thing to remember is that you need to upload two files. The first file is the API settings .env file, which contains all your environment settings, such as client ID, client secret, tenant ID, and project connection string. The second file is the document against which you want to run your queries or perform semantic search.

The uploaded document will eventually be processed into the vector store, where it will be chunked and embedded. However, as a physical file, it first needs to be uploaded manually. The rest of the processing and embedding will happen automatically within the program, which you’ll see in the demonstration.

Once the files are uploaded, you can configure your environment. After configuring the environment variables, the next steps involve creating the vector store, setting up your AI agent, and proceeding with query processing and response retrieval.

# **F) Demo: Initialise the Project Client & Upload the File**

In this lecture, we’ll explore how to import the required modules, configure Azure credentials, initialize the Azure AI Project client, and upload a file that will be used for vector store creation. Let’s go through each step one by one.

The first step is importing the required modules. This includes:

AIProjectClient, which is the main client used to interact with Azure AI Projects.

FileSearchTool, which allows searching within uploaded files.

MessageAttachment, which is used to attach files to messages, enabling interaction with the agent.

FilePurpose, an enum that defines the reason for uploading a file, such as for the agent to use.

ClientSecretCredential, which handles authentication using Azure credentials.

Next, we move to configuring the Azure credentials. This involves providing:

Tenant ID, which identifies your organization in Azure.

Client ID, which refers to the application you created.

Client Secret, which authenticates the application.

These parameters ensure secure access to Azure resources.

Once the credentials are configured, we initialize the Azure AI Project client. Here, we create an instance of AIProjectClient using the project connection string obtained from Azure AI Foundry, which identifies the specific Azure AI project to connect to. This step links your Python script with your Azure AI project.

The final step is uploading a file for the vector store. While the file can be uploaded in your local or Colab environment, it must also be uploaded to Azure via Python. In this example, we upload the GPT-4 system card file, which will be used for AI agent interaction. When uploading, you specify the file purpose as FilePurpose.AGENTS, indicating that the file will be used by the AI agent.

After uploading, the file ID is printed. This is important because the AI agent needs this as a knowledge source for retrieval. Essentially, this step uploads a document that will later be used for semantic search via the File Search tool.

In the next lecture, we will see how to create a vector store, set up your File Search tool, and integrate it with your AI agent.

# **G) Demo: Create Vector Store / Agent**

In this lecture, we will focus on three key steps: creating a vector store, building a File Search tool, and creating an AI agent. Let’s go through each step one by one.

The first step is creating a vector store. The vector store is used for storing and searching embeddings. As explained earlier, when a file is uploaded, it is parsed, broken into chunks, converted into embeddings, and stored in a vector store (or vector database). In this step, we create a vector store and link the uploaded file to it. Using code like vector_store = project.agents.create_vector_store(...) and providing the file ID, we ensure the file is connected to the vector store. Printing the vector store ID confirms that the vector store has been successfully created. The vector store allows the AI agent to perform semantic search within the documents.

Next, we move on to creating the File Search tool. This tool enables the agent to search inside the uploaded files. In the code, we instantiate the File Search tool and provide the vector store ID. This setup allows the agent to deliver context-aware responses based on the uploaded document. Creating the File Search tool is straightforward and is essential for the AI agent to utilize the vector store for semantic search.

Finally, we create the AI agent. This is the heart of the program. Using agents.create_agent(...), we define the model/deployment, give a name to the agent, and provide a system prompt. For example, the system prompt might be: “You are a helpful agent for file searches or RAG. Keep responses only to the uploaded file.” This ensures that the agent responds only using the uploaded document and not from any other data the model was trained on.

Next, we provide the tools to the agent. Here, we link the File Search tool definitions and resources to the agent, which allows the agent to perform document lookup efficiently. Once the agent is created, we receive an agent ID, confirming successful creation.

In the next lecture, we will cover creating a conversation thread, interacting with the conversation loop, attaching files as message attachments, processing messages, and retrieving responses from the agent.

# **H) Demo: Create Thread and Process Messages**

Now we have reached the final part of the program, where we will focus on creating a conversation thread and implementing an interactive conversation loop. This allows users to interact with the AI agent in real time. If the user types end, the agent will be deleted and the conversation will terminate.

First, we create a conversation thread. Threads are important because they track the conversation and maintain context across multiple messages.

Next, we implement a continuous loop for user interaction. If the user types end, the loop breaks, and the agent is deleted. Otherwise, the loop continues to process messages.

A key step here is uploading the file as a message attachment. The uploaded file, such as the GPT-4 system card, is attached to the user’s message. Using upload_file_and_poll, the file path and file purpose (for agent use) are specified. The attachment is created with the file ID and linked tools, such as FileSearchTool.definitions. This ensures the AI agent can reference the uploaded document when responding.

After attaching the file, we create the message. Each message is linked to the thread ID to maintain context. The role is set to user, and the content includes the user input. The attachment travels along with the message, allowing the AI agent to process both the query and the associated file simultaneously.

The next step is processing the agent’s response. Using create_and_process_run, we pass the thread ID and agent ID. The system handles everything under the hood — it retrieves the relevant information, generates a response, and checks the run status. If the run fails, the process breaks; otherwise, it continues.

We then retrieve and display the messages. Using list_messages with the thread ID, we access the AI-generated responses and display the latest reply. This ensures that the most recent response is always shown, whether it’s a summary, a table, or any other requested format.

Finally, as an optional cleanup step, it is important to delete the vector store and the agent. Since vector stores incur additional cost, deleting them prevents unnecessary Azure charges. Cleaning up also ensures that no unused resources are left running.

With this, we reach the end of the program. In the next lecture, we will run the code and observe the complete workflow in action.

# **I) Demo: Run the Code and ask Questions**

The time has finally come to run the code and see the workflow in action. Once you press run, you will notice that the vector store, thread, and agent are all created automatically. Each of these components generates a specific ID for tracking and integration: a file ID for the uploaded document, a vector store ID, an agent ID, and a thread ID. These IDs are essential for the smooth interaction between the components.

Once everything is set up, we can ask a simple question. For example, we might say: “Can you summarize the document into five lines?” Since the document is quite large, the AI agent saves us time by quickly providing a concise summary. In the background, the agent parses the uploaded file and retrieves the relevant information to generate the summary. For instance, it might summarize the document as discussing safety challenges associated with GPT-4, including hallucinations, generation of harmful content, and other key concerns.

Next, we can test the context awareness of the thread by asking the agent to provide bullet points. Because the conversation thread keeps track of previous messages, the agent can maintain context and respond accurately. The output demonstrates that the AI agent can extract and present the key bullet points from the uploaded document efficiently.

To test the retrieval-augmented generation (RAG) functionality, we can perform a negative test. For example, if we ask, “Who is the PM of India?”, the agent should not provide unrelated answers. Ideally, it will indicate that this information is not available in the uploaded document. In this test, the agent confirms that the document does not contain information about the current Prime Minister, showing that it strictly follows the uploaded content for retrieval and response.

This demonstrates the power of Azure AI agents with File Search: they can perform semantic search, maintain conversation context, generate structured outputs, and follow the instructions to rely solely on the uploaded documents.

With this, we have come to the end of the series of lectures on Azure AI agents using File Search. Thank you for watching!

# **XI) Azure AI Agent Knowledge Tools - Azure AI Search**

# **A) Intro Azure AI Search**

It’s now time to discuss the next knowledge tool, which is Azure AI Search. Many people have asked why one would use AI Search if File Search already allows you to implement RAG. The reason is that Azure AI Search is a full-fledged search and indexing service, whereas Azure OpenAI File Search is more lightweight and primarily focused on retrieving content for OpenAI models.

With File Search, you can work with Azure Blobs, but Azure AI Search significantly extends your capabilities. For instance, you can search against your SQL databases, Cosmos DB, and other structured or unstructured data sources. Another advantage is that Azure AI Search is a managed service, so you don’t need to worry about infrastructure, scalability, or security. This makes it the preferred solution for enterprises.

However, using Azure AI Search can sometimes be more complicated than File Search. There are multiple steps required before you can create an agent that utilizes AI Search. To make it easier, a complete workflow has been provided.

Before creating your agent, you need to:

Create a storage account.

Upload your document.

Ensure you have an Azure OpenAI service running.

Set up an embeddings deployment, which is essential for converting your documents into vector representations.

In this lecture, we will use a CrowdStrike threat report as our document and demonstrate how to search against it. After uploading the document, you need to create an index, which is the backbone of Azure AI Search.

Once the setup is complete, we will follow the same approach as before: first, using the no-code approach within Azure AI Foundry, and then performing a deep dive into the Python code to understand how it can be implemented programmatically.

# **B) What is Azure AI Search ?**

Today, we are going to deep dive into the concept of RAG (Retrieval-Augmented Generation) and explore some practical demos to understand how it works. For this, we will be using a service within Azure called Azure AI Search.

So, what exactly is Azure AI Search? Azure AI Search was originally based on Azure Cognitive Search, and Microsoft has rebranded it. It provides secure information retrieval at scale and is a fully managed service, meaning you don’t have to worry about the underlying infrastructure. When performing searches, it can automatically scale the infrastructure, while working on user-owned content.

This connects directly to the concept of RAG. In RAG, you are not searching generic databases or content that OpenAI has trained on; instead, you are searching your private documents. This ensures that your AI responses are based specifically on your own data.

To understand Azure AI Search better, imagine three components: your content, the Azure AI Search service, and your application. Your application sends queries to Azure AI Search, which retrieves and processes relevant information from your content.

When we say “content,” we are referring to your private data that you want to make searchable. This data can be in various formats, such as files in the cloud, content in Azure Blob Storage, or entries in a Cosmos DB database.

The next step is data ingestion. Azure AI Search uses indexers to automatically retrieve data from your chosen sources. It also supports AI enrichment, which performs tasks such as image processing, language processing, and extracting key phrases. Concepts like OCR (Optical Character Recognition) and named entity recognition fall under AI enrichment.

Azure AI Search also supports full indexing and refresh indexing. Refresh indexing becomes necessary if the underlying data changes, ensuring that your indexes are always up to date.

Under the hood, Azure AI Search has two main engines: the indexing engine and the query engine.

The indexing engine creates an inverted index, which is a highly efficient way to store and organize data. Instead of storing every word in every document, it stores unique words and tracks which documents contain them and how often. This improves both storage efficiency and ranking of search results.

The query engine retrieves the documents most relevant to a search query and ranks them using relevance scoring techniques. This ensures that the most contextually appropriate content is returned to the user.

When a user sends a query, the request goes from your application to Azure AI Search. The response returned becomes part of the RAG prompt: it combines the user query, the knowledge retrieved from your private data, and then feeds this to the language model (LM) to generate a response.

Azure AI Search works on data chunking, breaking large documents or files into smaller segments such as paragraphs, sections, or sentences. This allows the system to process and retrieve data more efficiently.

It also supports AI-powered indexing, automatically extracting text, key phrases, and entities from documents, such as PDFs stored in Azure Blob Storage.

Another key feature is semantic search, which goes beyond exact keyword matching to understand the intent and meaning behind queries. For example, a query containing the word “bank” is interpreted based on context, such as financial “bank” versus “river bank,” ensuring more relevant results.

Azure AI Search also incorporates cognitive skills, such as OCR, language detection, entity recognition, and the creation of custom skills. For instance, you can extract text from scanned images and identify technical terms using entity recognition.

One of the major advantages is that you don’t have to worry about infrastructure management. Microsoft automatically handles scaling to accommodate varying data volumes and query traffic, ensuring efficient and consistent search performance, even during peak loads.

Finally, Azure AI Search integrates seamlessly with the Azure ecosystem. For example, you can use Azure Functions to trigger data processing whenever new content is added to Azure Blob Storage, which is then automatically indexed by Azure AI Search.

In summary, Azure AI Search acts as the bridge between your private content and your application. It indexes, enriches, and semantically searches your data, enabling context-aware, accurate RAG applications. This makes it a powerful tool for integrating private data into AI workflows.

# **C) Understand the Workflow**

Today, our aim is to learn Azure AI Search and understand how to create an AI agent using this knowledge tool. Since Azure AI Search is a bit more complex than the simpler file search, I thought it would be useful to show a complete workflow—a step-by-step guide highlighting the essential artifacts and objects required to make it work.

Unlike file search, which is relatively straightforward, Azure AI Search involves multiple components that need to be properly configured before you can create an AI agent and attach the knowledge tool. It’s crucial to follow these steps in order, to avoid issues later in the process.

So let’s go step by step. The first step is to create a storage account in Azure. This storage account will host the documents that your AI agent will search over. Once you have the storage account, you need to upload your document. In our demo, we’ll be using a CrowdStrike cybersecurity analysis report for 2025, which covers breaches and cybersecurity insights. This will be the knowledge source for our agent.

The next important step is to ensure that you have an Azure OpenAI service. If you don’t already have one, you will need to create it first. Within this service, it is critical to set up an embeddings deployment. This is necessary because Azure AI Search will use embeddings to convert your document into vectors, which are essential for semantic search and retrieval. For our demo, we will use the text-embedding-ada model for this deployment.

After setting up the embeddings deployment, the next step is to create the Azure AI Search resource. This will allow us to manage indexing, search queries, and retrieval over the documents stored in the storage account. Once the search resource is ready, we will create an index and an indexer. These are critical for enabling Azure AI Search to efficiently organize, retrieve, and rank the content from your documents.

Only after completing all these steps can you move to the final step, which is creating an AI agent and attaching the knowledge tool. Following this sequence ensures that the agent can successfully interact with the Azure AI Search resource and provide context-aware, relevant responses.

Throughout this workflow, we’ll take it in small, manageable steps, with short videos of one to two minutes each. It’s important to follow along carefully to ensure everything is set up correctly before creating the agent.

# **D) Demo: Create a Storage Account & Upload Document**

Right, so the aim here is to implement RAG (Retrieval-Augmented Generation) using our own knowledge base. In this example, the knowledge base is a document shared by CrowdStrike for the 2025 Global Threat Report. We will query against this document, and it will act as the knowledge source for our AI agent.

This document is quite large—around 50 pages—and that’s the beauty of Azure AI Search. It can handle documents at scale, so even if you upload hundreds of pages, the service can efficiently search and process the content for relevant responses.

The first step is to create a storage account in Azure. Once the storage account is ready, we can upload the document we want to query. To create the storage account, you need to provide a resource group—in this case, I’ll use my existing Azure OpenAI resource group. Next, give a name for the storage account, such as Azure AI Agent Store, and select the region (e.g., East US).

For the primary service, I’ll use Azure Blob Storage, which is suitable for large files and Azure Data Lake integration. You can also select other options like Azure Files, but Blob Storage works well for this scenario. Next, you can choose the performance tier; I’ll select standard instead of premium to avoid unnecessary costs. For redundancy, I’ll go with locally redundant storage to keep it cost-effective. After reviewing the settings, you can create the storage account. Within a few minutes, it should be ready.

Once the storage account is created, the next step is to upload the document. You can upload the document as a blob inside the storage account. You can either select an existing container or create a new one—for example, Azure CrowdStrike Report. Set the container as private and leave other settings, like block size and blob type, as default. Upload the document to this container.

At this point, the first two steps are complete: you have created a storage account and uploaded the document that the AI agent will query against. This prepares the foundation for creating the AI agent and configuring Azure AI Search in the next steps.

# **E) Demo: Ensure / Create you have Azure OpenAI Service**

According to our workflow, the first two steps—creating a storage account and uploading the document—are already completed. The next step is to create an Azure OpenAI resource.

If you haven’t created an Azure OpenAI service yet, you can do this easily from the Azure portal. Simply search for “Azure OpenAI” in the search bar, and it should bring up the Azure OpenAI service. If no service exists, you’ll need to create a new one.

Creating the service is straightforward. You’ll need to specify some basic details: choose your resource group (for example, your existing Azure OpenAI resource group), give a name for the service, and select a pricing tier—typically, the standard tier is sufficient. After filling in these details, just proceed to the next steps, and your Azure OpenAI service will be created.

In our case, I will be using an existing service called Azure OpenAI – Udemy, so I won’t be creating a new one.

It’s very important to note that Azure AI Search requires an Azure OpenAI resource to function. Within that resource, you will also need an embeddings deployment, which is essential for generating embeddings from your documents. In the next lecture, I will show you how to create the embeddings deployment step by step.

If you are following along, go ahead and create a new Azure OpenAI service now, and then we can move forward with the workflow

# **F) Demo: Create Embeddings Deployment**

I think you’ve been following along well so far. Now it’s time to move ahead and focus on creating a deployment, specifically an embeddings deployment.

With Azure AI Search, when you upload a document or create an AI search resource, it needs to know which embeddings deployment to use. The reason is simple: when the document is provided as a source, it must be chunked, and embeddings must be created for the content. These embeddings are eventually stored in a vector database to enable retrieval and search functionality. That’s why specifying the embeddings deployment is crucial.

To create an embeddings deployment, first go to your Azure OpenAI resource. Click on the resource and navigate to the Deployments section. The easiest way to do this is via the Azure AI Foundry Portal. If this is a new service, you won’t see any existing deployments yet.

Click Deploy Model, then select Deploy Base Model. Here, we will choose a base model for our deployment. I recommend picking something like the text-embedding-ada model from OpenAI. This model is designed specifically for embeddings and outperforms earlier embedding models for text and code search. Embeddings are essentially numerical representations of concepts, converting text into number sequences that the AI can work with.

After selecting the model, confirm the deployment. For the deployment type, you can stick with Global Standard, and you can use the default name or pick your own. Click Deploy, and within seconds to a few minutes, your deployment will be ready.

Once the deployment is created, we can move on to the next step: creating the Azure AI Search resource. All the steps we’ve done so far—creating a storage account, uploading the document, creating the OpenAI resource, and deploying embeddings—are essential prerequisites for this. In the next video, I’ll show you exactly how this comes together.

# **G) Demo: Create Azure AI Search Resource**

In this video, we will focus on creating the Azure AI Search resource. Our ultimate goal is to attach an AI agent with a knowledge tool that uses Azure AI Search. To do this, we first need to set up the search resource itself.

The easiest way to start is by searching for AI Search in the Azure portal. You’ll see an option under Azure AI Services, and AI Search is a part of that. From there, simply click Create.

One important point to remember is that Azure AI Search can get expensive, so you should be careful when creating the resource. First, choose your resource group—for example, the “Azure OpenAI Resource Group” that you might already be using. Next, give your search service a name; it can be anything meaningful, such as AgentSearchRAG. Choose your location, like East US.

A critical step is to change the pricing tier. By default, Azure picks the Standard tier, which can become costly if left running for a long time. While there is a free option, it often comes with latency issues and limitations. The Basic tier is generally a safer and more cost-effective choice. Remember, once you are done using the resource, it’s best to delete it to avoid unnecessary charges.

After specifying all details, click Review + Create. Azure will validate your configuration, and once validated, you can create the search service.

Once your Azure AI Search service is ready, the next step is to create an index and an indexer inside the service. These are essential components for enabling document search functionality and supporting your AI agent. In the next lecture, we’ll go step by step on how to create the Azure AI Search index.

# **H) Demo: Create an Index**

In this lecture, we will focus on creating the Azure AI Search index. The search index forms the backbone of searching and the Retrieval-Augmented Generation (RAG) process that we utilize with Azure AI Search and the knowledge tool.

To start, go to the Azure AI Search resource that you previously created. There are multiple ways to create an index, but for our approach, we will use “Import and Vectorize Data”. Click on this option to begin.

You will be guided through a workflow where you first connect to your data and then vectorize it. Vectorizing essentially means creating embeddings for your data, which is why we previously set up the Azure OpenAI embedding models. This step ensures that the textual information can be transformed into numerical vectors for semantic search. You also have the option to vectorize and enrich images, but in our case, we are focusing on hybrid text-based and semantic search.

Next, you need to set up your data connection. Azure AI Search allows you to connect to multiple data sources, including Azure Blob Storage, Azure Data Lake, Cosmos DB, or even Azure SQL Database. This flexibility distinguishes Azure AI Search from the simpler file search, as it allows integration with databases and enterprise-grade storage solutions.

For our example, we will select Azure Blob Storage. Choose your subscription, storage account, and the container where the document resides (for example, the “Azure CrowdStrike Report” container). There are optional settings such as document layout detection and deletion tracking, but for simplicity, we can leave them at default.

Once the data connection is set, you will proceed to vectorize the text. Here, you connect to the Azure OpenAI service and select the embedding model. This is why we created the embeddings deployment in earlier steps. You choose your subscription, the Azure OpenAI resource, and the deployment name. The authentication type is usually set as API key, which establishes a secure connection between Azure OpenAI and Azure AI Search. Acknowledge that this will incur additional costs for both AI Search and Azure OpenAI services.

If you do not have images in your data, you can skip image-related settings. You can enable the semantic ranker and optionally configure a schedule for automatic indexing if you plan to add more documents later. Once everything is set, click Create.

Azure AI Search will then create several resources: the index, the indexer, and a skill set. Once complete, you will see that the index has been created, with a default name such as “vector”. This index will later be referenced programmatically when implementing RAG with Azure AI Search.

In summary, by following these steps, we have successfully created an Azure AI Search index, which is a critical component for enabling semantic search and RAG workflows on our knowledge base.

# **I) Demo: Create an Agent & Attach the Knowledge Tool**

Now, we can proceed to create an Azure AI agent that will be based on our knowledge tool, which in this case is Azure AI Search. All the preparation work we’ve done so far—creating the storage account, uploading the document, setting up Azure OpenAI embeddings, and creating the search index—will now come into play.

To start, go to your Azure AI Foundry project for agents and open Launch Studio. Here, we will create a new agent. Click on “New Agent” and give it a name, for example, Agent Rag I Search. You can then select the deployment model, such as GPT-4 or GPT-4 Mini, depending on what you have available. You can also provide a brief description, like “A RAG-based agent helping me using Azure AI Search tools.”

Next, navigate to the Knowledge section and click Add, then select Azure AI Search. This step is crucial because it connects your agent to the search index you created earlier. Azure AI Search uses this index to allow the agent to quickly retrieve relevant information from your documents. The connection ensures that the agent can leverage the full power of the index you prepared.

You will now need to connect to an index. Here, you have two options: indexes already part of the project, or indexes that are not yet part of this project. In our case, we will create a new connection. Click Select Azure AI Search Resource Connection, then Add Connection. Choose your Azure AI Search resource (for example, Agent AI Search Rag).

Once connected, you can select your Azure AI Search index. In our example, the index we created earlier was called vector, but you can give it a more descriptive name, like Vector Index – CrowdStrike, since it’s based on our CrowdStrike document.

Finally, choose the search type. You have the option for text-based search, semantic search, or a hybrid approach. For our scenario, select Hybrid (Vector + Keyword) to leverage both semantic embeddings and traditional keyword matching. Once selected, click Connect, and your agent will now be fully linked to the Azure AI Search index.

This completes the setup of your Azure AI agent with the knowledge tool, allowing it to perform RAG-based queries on your uploaded documents efficiently.

# **J) Demo: Run Queries in Agents Playground**

Once your vector index is connected to the agent, you will see it appear as part of the knowledge section. All the connections you created and the vector index you prepared should now be visible here. This confirms that your agent is properly linked to the Azure AI Search index.

Now, to test it, click “Try in Playground.” This will open the agent’s playground, allowing you to interact with it just like a normal chat interface. You can start by asking a simple query, such as “What is the uploaded document all about?” The agent will retrieve information using Azure AI Search and provide a summary based on the document you uploaded.

Once you see the agent correctly summarizing the document, you can try more specific queries. For example, ask “Which countries are majorly being attacked?” The agent will again use the Azure AI Search index to retrieve relevant information. It will respond with the findings from your knowledge base, noting regions such as North America, Western Europe, and East Asia, and even highlight particular advisories or activity trends, like increased intrusions by Chinese actors.

This demonstrates the power of RAG (Retrieval-Augmented Generation). Your agent is now able to leverage the Azure AI Search index to query your private document effectively, providing accurate and contextually relevant answers.

# **K) Demo: How to use AI Search in Python Code**

In this section, we will explore how to work with Azure AI Agents and Azure AI Search using Python code. Essentially, we will replicate the same exercise we did in the agents playground, but this time programmatically. The idea is to go step by step so that you can follow the workflow in a structured manner.

All the resources you created in the portal—such as the Azure Storage account, uploaded document, and Azure AI resources—will be used here. The Python code will connect to these resources and perform the same operations we did manually, allowing the agent to query your knowledge base.

The key feature here is that we are creating a conversational AI agent powered by GPT-4 or GPT-4 Mini. The agent uses the Azure AI Search index as its knowledge base, leveraging the knowledge tools we configured earlier. When a user sends a request, it goes to the AI agent, which understands that its knowledge tool is Azure AI Search. Behind the scenes, it interacts with the search index and indexers to retrieve relevant data and provide the response.

By doing this programmatically, you can integrate the Azure AI agent workflow into your applications, automate queries, and scale your RAG-based solution beyond the portal interface. This makes it straightforward to leverage your private knowledge base for retrieval-augmented generation with Python.

# **L) Demo: Install Libraries and Setup Environment**

The first part of the program is quite similar to what we have done previously. Here, we start by installing the essential libraries, including the Azure AI Projects SDK, Azure Identity, and python-dotenv. These libraries are necessary to interact with Azure services and manage environment variables securely.

In this setup, we use an .env file to store API settings such as client_id, client_secret, tenant_id, and the project connection string. This file also allows you to specify names for your vector indexes or other resources if needed. For now, the configuration is straightforward and focused on connecting to the Azure AI Project and Azure AI Search.

Once the libraries are installed, we configure the environment so that the program picks up the correct credentials and connection settings. This ensures that all subsequent calls to Azure services, including the AI project and search index, are authenticated and authorized properly.

In the next part of the lecture, we will see how to initialize the Azure AI Project client and set up the Azure credentials programmatically, which is the next crucial step to enable interaction with your search index and knowledge base.

# **M) Demo: Initialise the Project Client**

In the first part of the program, we begin by importing the necessary Azure SDK modules, which are essential for interacting with Azure services. We set up authentication using the ClientSecretCredential, which uses your tenant_id, client_id, and client_secret to authenticate against Azure. This credential is then used for all subsequent API requests to ensure they are authorized.

Next, we initialize the Azure AI Project client. This initialization requires two things: the authenticated Azure credentials and the Project Connection string. The credentials allow secure access to Azure, while the connection string, which you obtain from the Azure AI project in the Foundry, links your program to the specific AI project. These values are typically stored in environment variables for security and convenience.

One very important aspect here is retrieving your connection ID. This is often a point of confusion because the connection ID links your AI project (Foundry) to the Azure AI Search resource. Azure AI Search is a separate service, so establishing this connection is crucial. The connection ID is not directly visible in the Foundry or Azure portal, so you need to retrieve it programmatically.

In the code, we retrieve the connection ID by scanning through the metadata fields of each connection in the AI project, filtering for connections of type Azure AI Search, and then storing the relevant connection ID in a variable (con_ID). If you have multiple AI Search connections, it’s best to explicitly assign the correct one in your environment file. The retrieved connection ID comes in a format like search/subscriptions/..., which is essential to pass when initializing your search tool.

In the next part of the program, we will use this connection ID to initialize the AI Search tool with the index we created earlier. This step is necessary to enable your AI project to query the Azure AI Search index effectively.

# **N) Demo: Create Agent**

Now we come to the final part of the program, where we initialize the AI Search tool with the index name. Essentially, we are creating the AI Search tool and specifying two things: the index connection ID and the index name. The connection ID is what we retrieved in the earlier part of the program, as discussed at length. The index name refers to the index we created when setting up the Azure AI Search resource. You can cross-check this by going to your AI Search resource and looking under the indexes section. In this example, the index name ends with 7439, which we have already copied for use in the code.

Next, we move to the creation of the AI agent, which is a critical part of the program. We utilize the GPT-4 or mini model, and the agent is given a name—in this case, my_agent_search. We also provide instructions, acting like a system prompt, telling the agent that it is a helpful assistant designed to perform RAG queries using Azure AI Search. At this stage, it is important to specify the tools the agent will use. Here, tools is set to I_search.definitions, which defines the search tool, and tool_resources is set to I_search.resources, linking the agent to the actual AI Search tool. After this, the agent ID is printed for reference.

Once the agent is created, the program moves on to conversation threads, where messages between the user and the agent are exchanged. Each conversation takes place within a unique thread, and a thread ID is assigned. The program includes an interactive loop that waits for user input. The loop continues until the user types end, at which point the agent session is cleaned up. This ensures proper resource management and avoids leaving unnecessary active threads.

The last part of the program involves sending user messages to the agent. Each user input is sent to the AI agent within the conversation thread, with the role parameter set to user to indicate the source. The agent then processes this message using create_and_process_run, which triggers the AI to generate a response. After processing, the program checks whether the run was successful. Finally, the agent’s response is retrieved and displayed using a function that fetches the latest messages from the thread, extracts the agent’s reply, and presents it to the user.

This completes the explanation of the program, covering how the AI Search tool is initialized, how the agent is created and linked to the tool, and how user interactions are handled through conversation threads. In the next video, the code will be executed to demonstrate the workflow in action.

# **O) Demo: Execute the Code**

Finally, the time has come to run the code. Let’s execute our program and see it in action. When we run the code, the first thing it does is print the connection ID, which, as discussed earlier, is crucial for establishing the connection between the Azure AI agent and the Azure AI Search service. This connection ID appears as a long string, which will be used throughout the program.

Next, the program proceeds to create the agent, printing the agent ID and the conversation thread ID. Once the agent is ready, we can start sending inputs. For example, I ask, “What is the uploaded document all about?” The agent responds immediately, showing the power of the integrated system. It correctly identifies the document as the CrowdStrike 2025 Global Threat Report and summarizes its focus on various aspects of cybersecurity.

We can then test the agent’s summarization capabilities. I ask it to “Summarize the document in five lines”, and the agent generates a concise summary covering key aspects of the threat report and threat detection measures. The summarization is clear and captures the essence of the 50-page document.

Next, we can ask a more specific question, such as “Which countries are the major threats?” The agent quickly responds, listing countries like China, North Korea, Russia, Iran, along with other notable mentions such as Vietnam, Pakistan, and Syria. It even highlights significant statistics, like China’s cyber activity surge by 150%. This demonstrates how effectively the agent can query and synthesize information from large, unstructured documents in seconds.

Finally, once we are done with our queries, we simply type end, and the conversation ends, automatically deleting the agent and cleaning up resources.

Overall, this demonstrates a complete workflow of using the Azure AI Search knowledge tool with Azure AI agents. A large, unstructured document is transformed into a queryable knowledge base, and the agent efficiently retrieves and summarizes relevant information, showcasing the power and flexibility of RAG (Retrieval-Augmented Generation) with Azure AI.

# **XII) Real World Scenario - Freshdesk Agent**

# **A) Understand the Workflow and what we shall Build**

In this series of lectures, we will build a practical use case that applies the knowledge we’ve gained about OpenAI function calling. Specifically, we will see how function calling can be used in a real-world scenario with an Azure AI agent.

Here’s the idea: Imagine a user interacting in natural language, saying something like:

"Hey, can you create a support ticket for me? The file system usage is above 90%. Also, send me an email confirmation."

The goal is for the AI agent to understand this request, perform the necessary backend operations, and respond appropriately. In our case, the backend service we’ll be using is Freshdesk, a ticketing tool. The Freshdesk API will be triggered via Azure AI agent through function calling, automating ticket creation and notifications.

To understand the workflow:

User Interaction – The user sends a request in natural language, for example, asking to raise a ticket.

Azure AI Agent – This is the central AI layer that processes the request. It is powered by OpenAI models via Azure OpenAI. The agent understands the intent of the user.

Function Calling – Based on the intent, the agent decides if any backend service calls are required. Here, it triggers function calling to call the Freshdesk API.

Backend Service Execution – The Freshdesk API receives the request and performs the action, such as creating or updating a support ticket using the details provided by the agent.

So essentially, the agent acts as the intelligent intermediary, connecting the user’s natural language request to real backend actions.

Don’t worry if it sounds a bit complex at first. In the upcoming lectures, we will go step by step, building this Azure AI agent and integrating it with Freshdesk using function calling. By the end, you’ll see a complete, working example of an AI agent that understands user requests and performs backend operations automatically.

# **B) Create a login on freshdesk & Setup API Key**

So, as part of this workflow, we need to utilize the Freshdesk API. The first thing you need to do is create a Freshdesk account.

Here’s how you can do it:

Visit Freshworks – Freshdesk is part of Freshworks, and they provide a 14-day free trial, which you can use to get started.

Sign Up – Click on “Try it free”. You’ll see a simple form asking for:

First name

Last name

Work email (Note: You cannot use Gmail or Hotmail for this; it must be a company email)

Company name

Phone number

Activate Your Account – After submitting the form, you’ll receive an email from Freshdesk. Click the activation link to complete your account setup. Once activated, you’ll have your username and password.

Once your account is set up and activated, you should see a dashboard indicating your trial period, e.g., “14 days left”.

Now, there are two pieces of information that are crucial for our API integration:

API Key –

Go to Profile Settings in Freshdesk.

You’ll see your email listed there; click to reveal the API key.

Copy this key as we will use it in our code to authenticate API requests.

Helpdesk Domain –

Go to Admin → Helpdesk Settings.

Here, you’ll find your helpdesk URL, for example: cloudalchemy.freshdesk.com.

This domain is needed when making API calls to Freshdesk, so make sure to note it down.

Once you have your Freshdesk login, generated API key, and helpdesk URL, you are ready to proceed and integrate Freshdesk with your Azure AI agent using function calling.

# **C) Install Binaries & Setup Environment**

The very first step is to install the required libraries and set up our environment. This is always an important step, so take it slow and go step by step.

Here’s what we’ll do:

Fix library versions –
I’m specifying exact versions for the libraries we’ll be using. The reason is simple: if you try to run this code a few months from now, the libraries might have changed, and it could break the code. By fixing the versions, we ensure that the code works as expected.

Libraries we’ll install –

azure-ai-projects

azure-identity

python-dotenv (for environment variables)

We’ve already discussed these libraries in detail in previous lectures, so I won’t go into each again.

Environment file setup –
We’ll use a .env file called API settings to store our credentials. This includes:

CLIENT_ID, CLIENT_SECRET, TENANT_ID → From your Azure app registration

PROJECT_CONNECT_STRING → Your Azure AI project connection string

New additions for this workflow:

FRESHDESK_DOMAIN → The helpdesk URL from Admin → Helpdesk Settings in Freshdesk

FRESHDESK_API_KEY → From Profile Settings → View API Key in Freshdesk

Once we have this setup, we can load the environment variables in Python using dotenv and verify that everything is picked up correctly.

After that, we’ll move on to the next step, which is to understand what function we’ll be calling and which Freshdesk API endpoints we’ll use.

# **D) Understand the Custom Function create_freshdesk_ticket**

Now we shall go ahead and start creating our own custom function for Freshdesk ticket creation. The first step in this process is to import some type hints from Python’s typing module. We do this using the line:

from typing import Any, Callable, Set

Here, Any represents any type of value, Callable represents a function or method, and Set represents a set containing elements of a specific type. These type hints are useful for static type checking and improving code clarity.

Next, we define our custom function create_freshdesk_ticket. This function is responsible for creating a support ticket in Freshdesk. It takes two inputs: email and subject, both of which are strings, and returns a string. Essentially, the function says: “Create a ticket in Freshdesk via its API using the provided email and subject, and return the ticket information as a JSON string.”

In order to authenticate with Freshdesk, the function requires the Freshdesk domain and API key, both of which are stored in our environment file. Using these credentials, we construct the API endpoint URL, which is required to create a ticket. According to the Freshworks developer documentation, the endpoint we use is api/v2/tickets. The complete URL is constructed as:

url = f"https://{FRESHDESK_DOMAIN}/api/v2/tickets"

Here, FRESHDESK_DOMAIN is the domain associated with your Freshdesk account.

Once the endpoint is defined, we need to prepare the ticket data. This includes the email, subject, a description indicating the ticket was created via the Azure AI agent service, status (open), priority, and optional tags such as "api" or "python". This structured data forms the payload that will be sent to Freshdesk via an API request.

Next, we set up the HTTP headers for the request. The headers specify that the content type is JSON and that the response should also be accepted as JSON. After this setup, we send a POST request to the Freshdesk API using the requests library. Authentication is done using the Freshdesk API key, which is passed along with the headers and the JSON-formatted ticket data.

# **E) Initialize Azure AI / Create toolset**

Now that we have created our custom function, the next step is to import the additional required modules, initialize the Azure AI Project client, and set up the toolset. These components are essential before we can create the Azure AI Agent that will ultimately use the Freshdesk ticket function automatically. All of this work prepares the foundation for the agent we will build in the next lecture.

We begin by importing a set of modules that our script relies on. The first import is the os module, which allows our Python script to interact with the operating system and access environment variables. Next, we import json, which is necessary because we are interacting with external APIs that return responses in JSON format. The requests library is also imported, as it enables us to make HTTP calls to third-party APIs such as Freshdesk. Following this, we import AIProjectClient from azure.ai.projects, which is the main client required to interact with the Azure AI Project service. For authentication, we rely on Azure Identity, which allows us to authenticate securely using client credentials. Finally, we import FunctionTool and ToolSet from azure.ai.projects.models; these are needed because our agent requires tools, and this is where we define and register our custom Freshdesk ticket-creation function.

Next, we move to the main execution block of the script. This block ensures that the code inside it only runs when the script is executed directly, not when it is imported elsewhere. Inside this block, the first major step is to configure the Azure credentials. We do this by creating a credential object using the client ID, tenant ID, and client secret—all fetched from our environment file. This provides a secure way to authenticate with Azure services without hardcoding sensitive information.

Once authentication is correctly set up, the next step is to initialize the Azure AI Project client. This client requires a secure connection string, also stored in our environment file, and the credential we configured earlier. By establishing this connection, the script is now linked to the Azure AI Project where the agent lives and where the tools will be registered.

After establishing the connection, we move on to creating the toolset. This toolset contains all the custom functions that our Azure AI agent can use. To do this, we wrap the user-defined function—our Freshdesk ticket creation function—inside a FunctionTool. This wrapper helps the Azure agent understand how to call the function. Once wrapped, the function is added to a ToolSet, which serves as a collection of tools available to the agent. This step is essential, as it ensures the agent can call create_freshdesk_ticket whenever the user asks it to perform an action that requires creating a Freshdesk ticket.

Finally, we enable a new and important feature:

project_client.agents.enable_auto_function_calling()

This setting activates automatic function calling, which means the agent does not need explicit instructions to trigger the Freshdesk API function—it will automatically detect when the user’s request requires the tool and will invoke it on its own. This makes the agent more intelligent and capable of responding naturally to user queries.

With all these components in place—imports, authentication, project client initialization, toolset creation, and auto function calling—we are fully prepared to move on to the next stage. In the upcoming lecture, we will finally start building our Azure AI Agent and connect all these elements together to create a working solution.

# **F) Create the Freshdesk Agent**

Let’s walk through what this part of the program is doing.

We start by calling project_client.agents.create_agent, where we define the core configuration for our agent.
Here, we specify the model deployment we want to use — in this case, GPT-4 Mini.
Make sure you already have this model deployed inside your Azure AI Foundry project; otherwise, the agent won’t work.

Next, we provide the agent name — Freshdesk-agent — and set a simple instruction:
“You are a helpful agent who can create support tickets.”
This instruction guides the agent’s behavior during conversations.

Remember that every agent comes with a tool or toolset.
Here, we attach a toolset that includes our function create_helpdesk_ticket, which we defined earlier.
This function acts as the agent’s capability to generate support tickets.

Once the agent is created, the next step is to initialize a conversation thread.
This creates a new thread that maintains context for all interactions with the agent.

After that, we move into our interactive chat loop.
The user can input messages, and the loop continues until they type "end".

Inside the loop, we do two key things:

Create a message
We call create_message, provide the thread ID, set the role as "user", and include the user’s input.
This adds the message to the thread.

Run the agent
We trigger the agent using create_and_process_run, passing the thread ID and agent ID.
This executes the agent with the latest message and allows it to generate a response using the tools and instructions provided.

We also include a simple failure check. If anything goes wrong, we display the error.

Finally, we retrieve the agent’s latest output from the thread messages and print it to the console.

As a best practice, once the interaction is complete, we optionally delete the agent using its agent ID.
This helps keep your Azure environment clean and avoids accumulating unused agents.

In the next step, we’ll run this end-to-end and see the agent in action.

# **G) Execute the Program and Check the Tickets**

Now it’s time to execute the code and see our Azure AI agent in action.

After running the program, you’ll immediately see the Agent ID and the newly created Thread ID displayed in the console.
With our agent initialized and the thread ready, we can now interact with it.

Let’s try a sample request:

“Create me a support ticket for /u01 file system usage exceeding 90% and send an email to cve.joy@cloudalchemy.uk
.”

Imagine this scenario:
You notice that the /u01 filesystem on your server has reached 90% utilization.
As part of your company’s workflow, you want to raise a support ticket and receive an email confirmation.
Our Azure AI agent should be able to handle this end-to-end.

Once we submit the request, the agent processes it using the defined toolset and responds:

“I have successfully created a support ticket regarding the /u01 file system usage exceeding 90%.
The ticket details have been sent to cve.joy@cloudalchemy.uk
.”

And that’s exactly what we expect.

Next, let’s check the email inbox.
Perfect — the email has arrived from Cloud Alchemy Limited confirming that the request has been logged, along with the ticket reference number (in this case, Ticket #5).
If we click the link, it takes us straight to our Freshdesk portal.

Inside the Freshdesk dashboard, the newly created ticket is clearly visible.
It shows:

The source: Reported via portal

A note indicating that the ticket was created via Azure AI Agent Service

The complete metadata we included earlier (e.g., Python, API-based request)

This demonstrates how smoothly the entire flow works — from natural language input, to ticket creation, to email delivery, and finally to logging inside the support portal.

When you're done interacting, simply enter “end” in the console.
This exits the chat loop, deletes the agent from the environment, and completes the process cleanly.

This example perfectly showcases a real-world use case.
With our Azure AI Agent Service, a user can describe a support need in plain language, and the system intelligently handles everything — creating tickets, sending notifications, and integrating with existing support tools.

# **XIII) Real World Scenario - Streamlit Application**

# **A) What is Streamlit ?**

Before we begin building our Azure AI Agent Service with Streamlit—and before I show you how the front end will actually look—it’s important, especially for beginners, to first understand what Streamlit is. When I was creating this course, Streamlit was new to me as well, so everything I’m explaining here is based on my own learning experience.

Streamlit is an open-source Python library designed to make it incredibly easy to build interactive web applications, particularly for data science and machine learning projects. The beauty of Streamlit lies in its simplicity: you can build fully functional web apps with just a few lines of Python code. Since it is specifically created for data scientists, the framework focuses on enabling fast, interactive, and visually appealing applications with minimal effort.

One of the biggest advantages of Streamlit is that it requires no front-end development experience. You don’t need to know HTML, CSS, JavaScript, or even modern frameworks like React or Angular. If you can write Python, you can build web apps. Streamlit seamlessly converts your Python scripts into usable web interfaces, which makes the development process extremely beginner-friendly.

Streamlit also offers a wide range of built-in interactive widgets. These include sliders, buttons, text inputs, date pickers, dropdowns, radio buttons, and more. These widgets allow you to update your app in real time, creating highly dynamic and responsive user interfaces. This makes Streamlit ideal for rapid prototyping, enabling you to build interactive applications within minutes rather than weeks. In the next lecture, you’ll see just how easy it is to create simple components with minimal code—something that would require large amounts of HTML or JavaScript in traditional web development.

Another key strength of Streamlit is that it is heavily focused on data. The framework is designed with the needs of data scientists in mind, making it perfect for tasks such as data visualization, machine learning demos, dashboards, and more. It integrates smoothly with popular Python libraries like Pandas, NumPy, TensorFlow, and PyTorch. This makes it a natural choice for anyone working in analytics or machine learning.

Streamlit also provides live reloading, which means the app automatically refreshes whenever you modify your code. This real-time feedback loop greatly speeds up development and makes experimentation effortless. Simply save your Python file, and the browser reflects your changes instantly.

Creating a Streamlit app is incredibly simple. With just a few lines of code—such as importing Streamlit, writing a title, printing text, or adding a text input—you can create a complete interactive page. Many of the common functionalities you would normally implement with HTML or JavaScript are readily available through Streamlit’s Python APIs.

Streamlit supports a variety of input controls including buttons, checkboxes, sliders, number inputs, text fields, date pickers, dropdown selectors, multiselect widgets, and radio buttons. More advanced features like file uploaders, drag-and-drop functionality, and multi-file support are also built in. These capabilities make it easy to build rich, interactive interfaces without specialized front-end knowledge.

Overall, Streamlit empowers you to create clean, interactive, and visually appealing web applications very quickly. In the next lecture, I’ll walk you through some simple Streamlit examples to help you understand how easily you can build basic front-end components using only Python.

# **B) Demo: Testing some Simple Sample Apps**

In this video, you’ll get to see Streamlit in action. To begin, simply visit the Streamlit website by going to streamlit.io. Once the site loads, you’ll notice the tagline: “The fastest way to build and share applications.” Streamlit immediately showcases how effortless it is to create interactive apps. For example, by writing just a few lines—import streamlit as st, followed by st.write("Hello World")—a complete web interface appears instantly. You can update code, add a slider, and watch the app refresh automatically. This simplicity is what makes Streamlit so powerful: the UI responds directly to your Python code.

Streamlit also makes deployment incredibly easy. Once your app is ready, you can deploy it to the cloud or even package it into a mobile application. Everything—from development to deployment—can be done without writing any HTML, CSS, or JavaScript. Another great feature is the Streamlit Playground, which lets you experiment with Streamlit components live in the browser. The playground shows simple examples: importing the library, adding a title, writing markdown, and instantly seeing the output side-by-side. It’s an excellent way to learn and understand how each widget behaves.

For example, you can add playful elements like st.balloons(), which triggers an animated balloon celebration when a button is clicked. Streamlit previews all of this visually in the playground. You can also explore built-in charts and visualizations. With barely 15 lines of code, Streamlit can generate clean and interactive charts directly from Pandas data. The left side displays the code, and the right side shows the rendered chart instantly, making it a perfect tool for data exploration and visualization.

To demonstrate how easy it is to run Streamlit locally, I copied a simple code example from the playground into a Python file. To set it up, you only need to run pip install streamlit, which installs the framework in seconds. After that, you can run your app using the command streamlit run charts.py, and Streamlit will automatically open the app in your browser. The same chart and interface you saw in the playground now appear on your local machine. You can interact with the chart—hide or show series, adjust inputs, and explore the data in different ways.

Streamlit offers many additional components such as dataframes, sliders, inputs, live charts, computer vision demos, and even geospatial visualizations. All these examples are available for you to explore in the playground. You can browse through them in your free time to get comfortable with the wide range of possibilities Streamlit provides.

Now that you’ve seen Streamlit in action and understand how simple and powerful it is, the next lecture will show you how to integrate Streamlit with the Azure AI Agent Service. We’ll build a full application using both technologies, and this time, we'll use Visual Studio Code to develop the project.

# **C) Setup a Virtual Environment in VSCode & Install Requirements**

In this lecture — and the upcoming ones — our goal is to build an application using Streamlit. The application we’ll be working on is the same Freshdesk-based support ticket generator that we previously created. We will reuse the same code logic, but this time we will enhance the application by adding an interactive Streamlit user interface on top of it.

This also gives us the opportunity to demonstrate how the same solution can be built and executed using Visual Studio Code, since many of you have asked to see the workflow outside Google Colab. So, as always, your wish is my command.

To get started, you first need to have Visual Studio Code installed on your machine — whether it’s Windows, macOS, or Linux. Once VS Code is installed, open the application and create a new folder where your project will live. You can name this folder something like StreamlitApp. Open that folder in VS Code, and when prompted, click “I trust the authors” so the workspace can initialize properly.

Next, open a new terminal inside VS Code. By default, any Python package you install would go into your system’s main Python environment. However, best practices recommend keeping your project dependencies isolated. That’s why we create a virtual environment. You can do this by running:

python3 -m venv streamlit_ai_agent

This command creates a new virtual environment named streamlit_ai_agent. Once created, you will see folders like bin, include, and lib generated inside it. Even after creation, your terminal still points to the base environment, so the next step is to activate your new environment:

source streamlit_ai_agent/bin/activate

Once activated, your terminal prompt will update, confirming that you are now working inside the virtual environment. Any packages installed now will be contained within this environment.

Inside the course resources, you will find a requirements.txt file. This file lists all the Python libraries your application will need. The libraries include requests, streamlit, azure-ai-projects, azure-identity, and python-dotenv. These are the same modules we have already discussed earlier, and now we simply need to install them.

To install all required dependencies in one go, run:

pip install -r requirements.txt

This command instructs Python to install every library listed in the file. The installation process may take a little time because some of the Azure-related libraries have multiple internal dependencies.

Once the installation is complete, your development environment is fully prepared. This setup — creating a virtual environment and installing the necessary libraries — is the first and most essential step before we begin building the Streamlit application.

# **D) Setup the Environment File**

Once your libraries are installed, you can always re-run the installation command to verify everything is in place. Simply execute:

pip install -r requirements.txt

If all dependencies were installed earlier, the terminal will confirm that each requirement is already satisfied. This ensures your environment is correctly prepared and no packages are missing.

The next step is to bring two important files from the course resources into your project folder. These files are:

API_settings.env

Streamlit_Freshdesk.py

The API_settings.env file contains environment variables that hold your Azure and Freshdesk configuration details — such as your client ID, client secret, tenant ID, project connection string, Freshdesk domain, and Freshdesk API key. For security reasons, you must use your own credentials. The file included in the course is only for reference so you know exactly what variables you need.

This .env file is identical to the one we used earlier when building the Freshdesk integration in Google Colab. Nothing changes here — the values and structure remain the same.

Next, open your Streamlit_Freshdesk.py file. As soon as you open it in Visual Studio Code, you’ll notice that VS Code automatically selects the correct Python interpreter — the one associated with the virtual environment you created earlier. For example, you might see something like Python 3.11 or 3.12 mapped to the streamlit_ai_agent environment under bin/python. This ensures your script will run using the exact environment where we installed all required packages.

One important thing to check is the path to your .env file. Inside your script, you must explicitly specify where the API_settings.env file is located so that your application can correctly load your credentials. Adjust this path if needed so your script can find the file.

Other than that, the code should look very familiar. You're simply importing the same libraries we previously discussed, loading the environment variables, and pulling in values such as client ID, client secret, and tenant ID. This part of the script remains unchanged from the earlier Colab-based version.

Once you’ve confirmed that your environment variables are correctly set and the interpreter is pointing to the right environment, you’re ready for the next stage — integrating Streamlit with your Python logic.

From the next lecture onward, we’ll move into the Streamlit-specific implementation and see how to wrap our Freshdesk logic inside a user-friendly Streamlit interface.

# **E) Understand the Streamlit Configuration**

Let’s now break down the Streamlit portion of the application and understand how the layout and interface are configured. The first key section is the Streamlit layout configuration. In the code, we call st.set_page_config and specify layout="wide". This simply means the application should utilize the full width of the browser window instead of a narrow, centered layout. We also set the initial sidebar state to "collapsed", which means that when the app loads, the sidebar will start in a minimized state.

You can see this behavior in the actual application UI. The page spans the full width of the browser for a clean and spacious interface, while the sidebar remains collapsed when the page first loads. Users can expand it later when needed.

Next, the code defines a custom banner header. Streamlit allows the use of HTML-like and CSS-like syntax inside st.markdown, and I’ve used this capability to create a more polished UI. This is optional — you can remove the HTML/CSS portion if you prefer a simpler, native Streamlit style. However, for presentation purposes and to create a visually appealing layout, the code includes custom HTML styling.

To render this styled header, we pass the HTML block into st.markdown with unsafe_allow_html=True. This instructs Streamlit to render raw HTML inside the markdown block. While powerful, this should not be used in production environments because it can introduce security vulnerabilities such as script injection. For local testing and demonstration purposes, it’s acceptable.

The banner also uses an image—loaded from a URL—to enhance the visual appeal. You can replace this with any image of your choice depending on your brand or preference. The banner title and description, such as “Freshdesk AI Agent” and “Instantly assist customers and create Freshdesk support tickets,” are also defined here. These mirror exactly what you see displayed in the UI. The sidebar header, labeled “Chat with Agent,” is similarly defined and mapped to what appears on the actual sidebar.

The next part of the code deals with styling the chat interface. Using custom CSS within a markdown block, we define the appearance of chat bubbles, message alignment, avatar positioning, and the fixed input bar. This CSS-based customization is what gives the chat UI its structured and modern look.

Streamlit also provides a powerful concept called containers. In the code, you’ll see chat_container = st.container() and input_container = st.container(). The chat container holds the conversation messages, while the input container holds the text box and the send button. This separation keeps the interface organized — what you see as the chat history section and the input area in the UI are built using these containers.

Finally, we initialize Streamlit’s session_state, which is crucial for maintaining chat history across reruns (Streamlit reruns your script on every interaction). The code checks whether a chat history already exists in the session; if not, it initializes an empty one. This ensures that previous messages remain visible even when the page refreshes or when new inputs are submitted.

In the next lecture, we’ll walk through the Freshdesk ticket creator portion of the application. Since you are already familiar with most of this logic from previous sessions, we will quickly recap the existing code and then focus on the parts that integrate directly with Streamlit.

# **F) Understand the Freshdesk Ticket Creator**

Okay, so next we talk about the Freshdesk ticket creator. I won’t go into every single line of the code because we already discussed it in detail earlier when we covered the Freshdesk Support Agent. If you missed those lectures, it’s best to go back and watch them first, because the concepts there will help you understand this section better. Here, we will quickly skim through the important parts of the code used in this module.

In this file, the first thing we do is create a Freshdesk ticket-creation function, which we call create_fresh_ticket. This function is responsible for authenticating with Freshdesk using the API key, sending a POST request to create a ticket, and then returning the Freshdesk response in JSON format. This is the function that bridges our Azure AI agent with the Freshdesk backend.

Next, we move on to the Azure AI agent setup. Here we specify the credentials, such as the ClientSecretCredential, which allows our application to authenticate with Azure using service-principal details. We also connect to the project client by reading the project connection string from environment variables. One of the most important steps in this setup is the tool registration. As discussed earlier, every agent can have its own tool or set of tools. In our case, the tool we want the agent to use is the user-defined function we just created, which is the Freshdesk ticket creator. So we wrap this Python function as a callable tool so that the LLM agent can autonomously invoke it whenever needed.

After registering the tool, we proceed to create the agent. While creating the agent, we specify the model deployment from Azure Foundry—here we use GPT-4o-mini. We also provide system-level instructions and pass the toolset with function calling enabled. Once the agent is created, we initialize a conversation thread. As you know, an agent operates using a thread, and the thread stores all messages exchanged in the conversation. So we create a new thread using create_thread, which will track the back-and-forth between the user and the agent.

Then, we discuss the chat display loop, which controls how messages appear in the UI. For this, we use Streamlit. Inside the loop, we have added some Markdown and CSS to make the chat interface look nicer, though these customizations are optional—you can remove them if you prefer a simpler UI. The purpose of this loop is to display both user and agent messages as chat bubbles with avatars, giving the interface a clean conversational look.

Below that, we define the user input field and the send button. We use two columns in Streamlit—column one holds the text input box and column two holds the send button. So in the UI, the text box is on the left and the send button on the right.

The most important part comes next: message processing. Remember, every message coming to or from the agent has to flow through Streamlit so it can be displayed. Therefore, when the user clicks the send button and provides input, we take that input and send it to the agent. The agent then runs using the run call, processes the request, triggers the Freshdesk function if needed, and returns a response. We then fetch this response message from the agent.

Once we have both the user message and the agent response, we append them to st.session_state.chat_history, because Streamlit needs a stored history of messages to display them properly in the UI. The agent handles all backend logic—intent detection, function calling, and API communication—while Streamlit simply manages what the user sees. Finally, we call st.rerun() to refresh the interface so the newly added messages appear immediately.

That’s pretty much the entire flow for this code. In the next lecture, I’ll show you how to actually run this app end-to-end. Keep watching!

# **G) Demo: Executing the Code & Running Prompts**

Okay, so the time has finally come to actually run our code and see the magic in action. All you need to do is open your terminal and simply run the command streamlit run Streamlit_Freshdesk.py—or whatever your Python file is named. Once you hit Enter, Streamlit will automatically start up and open a web browser window for you. You will see the app launch exactly like the interface I have been showing you throughout the walkthrough. I could have kept it as a surprise reveal at the end, but since we were mapping everything—like the banner, the image, the sidebar, and the styling—I wanted you to see how each piece fits together with the code.

Now let’s actually try chatting with the Streamlit app and see how it behaves. When I type a simple greeting like “Hello” and hit the Send button, you’ll notice that the interface shows “Running…” for a moment. It is slightly slow, which I observed earlier too. But once the agent responds, you can clearly see the interaction in the chat bubbles. The user message appears with the user avatar, and the agent’s response appears with the agent avatar. This is exactly what we discussed in the CSS styling part of the code, where we defined different visual layouts for user and agent messages.

Next, I try sending another message, like “Okay, so what can you assist me with?” because I want to understand what capabilities this agent is presenting as a Freshdesk AI assistant. The agent responds by saying that it can help with creating Freshdesk support tickets for any issues or requests the user might have. Perfect—now I want to actually test this functionality end to end.

So let’s give it a real-world support request. I type: “Okay. Create me a support ticket for my SQL Server instance that is running slow and send an email to kvjoy@cloudalchemy.uk
.” This simulates a situation where someone working with a SQL Server database notices performance issues and wants to raise a support ticket. After clicking Send, the app begins processing. It shows the running indicator once again, and after a moment, the agent replies: “A support ticket has been successfully created regarding SQL Server instance running slow, and an email has been sent.”

To verify this, I switch back to my Freshdesk Helpdesk portal and refresh the tickets page. Sure enough, I see a new ticket—Ticket #8—with the title “SQL Server instance running slow.” That confirms the ticket creation worked perfectly. Next, I check my email inbox to confirm whether the notification email was actually sent. And yes, there it is: an email acknowledging the request and confirming that a support ticket has been created.

So with this demonstration, I believe I’ve addressed a question that many people asked: “You’ve shown AI agents and chatbots running in Python and Google Colab, but can you show a real-world application?” This example is exactly that—a complete, practical, real-world use case, built with Streamlit, Azure AI Agents, Freshdesk API integration, and a proper UI workflow.
