A curated list of awesome open-source tools for workflow automation, integration, building automation platforms, orchestrating AI agents, and more.

## What is this?

This repository aims to be a comprehensive hub for discovering self-hostable and open-source alternatives that empower you to automate tasks, integrate applications, orchestrate data pipelines, manage AI agent workflows, and perform web automation, all without being locked into proprietary services.

## Contributing

Contributions are highly welcome! If you know of an open-source automation tool that fits any of the categories below, please feel free to submit a pull request. When adding a tool, please try to include the following information:

* **Name:** The name of the tool.
* **Description:** A concise explanation of what the tool does and its key features.
* **Link:** The link to the official repository (e.g., GitHub, GitLab).
* **Key Features:** Highlight important functionalities relevant to automation.
* **Category:** Indicate which of the categories below the tool belongs to.

## Open Source Automation Tools

### 1. Workflow Orchestration

Tools that allow you to visually or programmatically define and execute automated workflows by connecting different services and tasks.

* **n8n**
    * **Description:** A fair-code licensed node-based workflow automation tool. It can be self-hosted and allows you to connect various apps and services to automate tasks.
    * **Link:** [https://github.com/n8n-io/n8n](https://github.com/n8n-io/n8n)
    * **Key Features:** Visual workflow editor, a wide range of integrations, extendable with custom nodes.
    * **Category:** Workflow Orchestration

* **Apache Airflow**
    * **Description:** A platform to programmatically author, schedule, and monitor workflows. Often used for data pipelines but can orchestrate other tasks.
    * **Link:** [https://airflow.apache.org/](https://airflow.apache.org/)
    * **Key Features:** Workflow orchestration, scheduling, monitoring, DAG-based workflow definition.
    * **Category:** Workflow Orchestration

* **Camunda**
    * **Description:** An open-source platform for automating end-to-end business processes and decision workflows.
    * **Link:** [https://camunda.com/](https://camunda.com/)
    * **Key Features:** BPMN 2.0 modeling, workflow engine, process monitoring.
    * **Category:** Workflow Orchestration

* **Activepieces**
    * **Description:** A no-code open-source automation tool that allows users to create workflows by connecting various applications.
    * **Link:** [https://www.activepieces.com/](https://www.activepieces.com/)
    * **Key Features:** No-code visual builder, growing number of integrations.
    * **Category:** Workflow Orchestration

* **Dagster**
    * **Description:** An open-source data orchestrator built for developing and deploying data pipelines and other workflows.
    * **Link:** [https://github.com/dagster-io/dagster](https://github.com/dagster-io/dagster)
    * **Key Features:** Software-defined assets, strong typing, testability, observability.
    * **Category:** Workflow Orchestration

### 2. Agent Workflow Orchestration

Tools specifically designed for orchestrating the behavior of AI agents.

* **LangChain**
    * **Description:** A framework for building applications powered by large language models (LLMs). It provides tools for creating complex workflows involving LLMs, including agentic behavior.
    * **Link:** [https://github.com/langchain-ai/langchain](https://github.com/langchain-ai/langchain)
    * **Key Features:** LLM integration, prompt management, memory, agent capabilities, tool use.
    * **Category:** Agent Workflow Orchestration

* **AutoGen**
    * **Description:** A framework from Microsoft that enables the development of multi-agent AI applications, allowing specialized agents to collaborate to solve tasks.
    * **Link:** [https://microsoft.github.io/autogen/](https://microsoft.github.io/autogen/)
    * **Key Features:** Multi-agent conversations, automated agent collaboration, customizable agents.
    * **Category:** Agent Workflow Orchestration

* **Dify**
    * **Description:** An open-source platform for building, testing, and deploying LLM-based AI applications, including those with agentic workflows.
    * **Link:** [https://dify.ai/](https://dify.ai/)
    * **Key Features:** Visual prompt engineering, model management, agent building blocks.
    * **Category:** Agent Workflow Orchestration

* **CrewAI**
    * **Description:** A framework for orchestrating autonomous AI agents to work collaboratively towards complex goals.
    * **Link:** [https://www.crewai.com/](https://www.crewai.com/)
    * **Key Features:** Agent roles, task delegation, collaborative problem-solving.
    * **Category:** Agent Workflow Orchestration

* **Semantic Kernel**
    * **Description:** Microsoft's open-source SDK that allows you to easily integrate AI models like OpenAI and Azure OpenAI into your applications. It supports the creation of AI agents and plugins.
    * **Link:** [https://github.com/microsoft/semantic-kernel](https://github.com/microsoft/semantic-kernel)
    * **Key Features:** Semantic functions, planners for task automation, connector integrations.
    * **Category:** Agent Workflow Orchestration

### 3. Data Automation & Pipelines

Tools focused on automating the movement, transformation, and processing of data.

* **Apache Airflow**
    * **(See Workflow Orchestration)**
    * **Category:** Data Automation & Pipelines

* **Dagster**
    * **(See Workflow Orchestration)**
    * **Category:** Data Automation & Pipelines

* **Apache Beam**
    * **Description:** A unified programming model for defining and executing data processing pipelines, including both batch and streaming.
    * **Link:** [https://beam.apache.org/](https://beam.apache.org/)
    * **Key Features:** Unified data processing model, portability across execution engines.
    * **Category:** Data Automation & Pipelines

* **Apache NiFi**
    * **Description:** An open-source data integration and processing platform designed for high-volume data flows.
    * **Link:** (Search for "Apache NiFi" on GitHub or the Apache website)
    * **Key Features:** Visual flow-based programming, data provenance, back pressure handling.
    * **Category:** Data Automation & Pipelines

### 4. Task Automation

Tools primarily aimed at automating repetitive tasks at the system or application level.

* **Ansible**
    * **Description:** An open-source automation engine that automates software provisioning, configuration management, and application deployment.
    * **Link:** [https://github.com/ansible/ansible](https://github.com/ansible/ansible)
    * **Key Features:** Agentless architecture, powerful configuration management.
    * **Category:** Task Automation

* **n8n**
    * **(See Workflow Orchestration)**
    * **Category:** Task Automation

* **Taiga.io**
    * **Description:** An open-source project management tool with workflow automation capabilities for agile development.
    * **Link:** [https://github.com/taigaio/taiga-back](https://github.com/taigaio/taiga-back) (Backend) / [https://github.com/taigaio/taiga-front](https://github.com/taigaio/taiga-front) (Frontend)
    * **Key Features:** Task management, Kanban/Scrum boards, workflow customization.
    * **Category:** Task Automation

* **Automate (Android)**
    * **(See previous description)**
    * **Category:** Task Automation

### 5. Web Automation

Tools for automating interactions with web pages and web services.

* **Selenium**
    * **(See previous description)**
    * **Category:** Web Automation

* **Cypress**
    * **Description:** A next-generation front-end testing tool built for the modern web, also usable for web automation tasks.
    * **Link:** [https://github.com/cypress-io/cypress](https://github.com/cypress-io/cypress)
    * **Key Features:** End-to-end testing, time travel debugging, automatic waiting.
    * **Category:** Web Automation

* **Playwright**
    * **Description:** A powerful library by Microsoft to automate Chromium, Firefox, and WebKit with a single API. Excellent for web scraping and automation.
    * **Link:** [https://github.com/microsoft/playwright](https://github.com/microsoft/playwright)
    * **Key Features:** Cross-browser automation, auto-waits, network interception, browser contexts.
    * **Category:** Web Automation
