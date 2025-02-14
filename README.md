

<img src="docs/images/owlmind-banner.png" width=800>

### [Understand](./README.md) | [Install](./INSTALLING.md) | [Get Started](./README.md#getting-started) | [Contribute](./CONTRIBUTING.md)

# OwlMind 

OwlMind Framework is being created by The Generative Intelligence Lab at Florida Atlantic University with the purpose to support Education and Experimentation with Hybrid Intelligence System. These are solutions that apply a combination of Rule- and GenAI-based inference to facilitate the implementation of local-AI solutions, improve latency, optimize costs, and reduce energy utilization and carbon emissions. This framework is designed to support education an experimentation, empowering students to rapidly achieve tangible outcomes by implementing consumable HybridAI-based Agentic Systems. 


<img src="docs/images/owlmind-arch.png" width=800>

The core components include:

* **Bot Runner for Discord Bots**: acts as the interface to host and execute bots on platforms like Discord, providing users with a conversational agent to interact with.
* **Agentic Core**: provides deliberation at the heart of the platform, enabling users to define and configure rule-based systems.
* **Configurable GenAI Pipelines**: supports flexible and dynamic pipelines to integrate large-scale Generative AI models into workflows.
* **Workflow Templates**: offers pre-configured or customizable templates that simplify the Prompt Augmentation Process.
* **Artifacts**: represents modular components that connect agents to external functionalities, such as web-connection, databases, RAG systems,interacting with APIs,  and others
* **Model Orchestrator**: connects diverse Generative AI models into its pipelines, providing developers with flexibility and simplicity.


The architecture adheres to the principle of ``Hybrid Intelligence Framework``, combining (local) Rule-based inference with (remote) GenAI Model-assisted inference and support. In this composition, the interplay between Rule- and Model-based inference can take place in different configurations:

* **GenAI generates the Rules:** The system leverages GenAI to create or refine rule-based logic, ensuring adaptability and efficiency in handling various scenarios.
* **Rules applied to solve interactions and when not feasible, pass through GenAI:** if the predefined rule set is insufficient, the system escalates the decision-making process to the GenAI model for further reasoning or resolution.
* **Rules applied to solve interactions and when not feasible, request GenAI for new rules:** instead of merely relying on GenAI for direct inference, the system can request the model to generate additional rules to expand or enhance its local knowledge base.
* **Proactive request for new rules for new contexts being identified:** the architecture anticipates novel situations and dynamically queries GenAI to generate relevant rules before encountering an issue, ensuring continuous learning and adaptability.


The ``Agentic Core`` adheres to the [Belief-Desire-Intention (BDI) framework](https://en.wikipedia.org/wiki/Belief–desire–intention_software_model) for agent-based systems. This cognitive architecture ensures that agents are capable of goal-oriented behavior by structuring their decision-making process around:
* **Beliefs**: represent the agent’s knowledge or perception of the environment. These beliefs act as the foundational understanding upon which the agent evaluates its actions.
* **Desires**: define the agent's objectives or goals it wishes to achieve, such as completing a workflow, retrieving specific data, or responding to user queries.
* **Intentions**: represent the plans or strategies the agent actively commits to in order to achieve its desires, balancing feasibility and optimality.
* **Plan Base**: A repository of predefined and dynamically generated plans; these plans serve as executable roadmaps for the agent to transform its intentions into actionable steps; the planBase ensures that agents can adapt to varying contexts and efficiently execute workflows based on their beliefs, desires, and current environment.
* **Capability Base**: defines agent’s operational capabilities, defining what the agent can do in terms of actions and interactions; connected to existing **Artifacts**.



## Getting Started

* [Configure a simple Rule-Based Discord Bot](./docs/bot-1.md)
* Configure GenAI Pipelines with bot-1.py to extend conversation capabilities
* Configure Prompt Engineering Workflows to improve reasoning.
* Configure Artifacts in the GenAI Pipelines to extend reasoning capabilities

