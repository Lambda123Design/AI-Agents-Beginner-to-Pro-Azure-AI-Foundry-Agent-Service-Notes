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



# **G) Demo: FC: Python Code : Function Calling Intro**

# **H) Demo: FC: Python Code: Get an API Key from openweathermap.org**

# **I) Pre-Req Setup azureopenai.env**

# **J) Demo: FC : Python Code : Initialise and Set the Environment**

# **K) Demo: FC : Python Code : Instantiate the Client Object of Azure OpenAI**

# **L) Demo:FC : Python Code: Define the get_weather Function**

# **M) Demo: FC: Python Code: Define the tools list required for the Assistants API**

# **N) Demo: FC_ Python Code : Create an Assistant & Thread**

# **O) Demo: FC:Python Code: Create a function for running the conversation**

# **P) Demo: FC: Python Code: Take the User input and show result**
