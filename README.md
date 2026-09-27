<h1 align="center">Özlem Kılıç</h1>

<p align="center">
  <b>Computer Engineer · Data & AI Engineering · Fintech</b><br>
  I build data products that decision-makers actually trust.
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/kilic-ozlem/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn">
  </a>
  <a href="mailto:ozlem.kilicdev@gmail.com">
    <img src="https://img.shields.io/badge/Email-EA4335?style=flat&logo=gmail&logoColor=white" alt="Email">
  </a>
</p>

---

## About Me

I'm a **Computer Engineering graduate** with professional experience across **Data Analytics, Data Science and AI Engineering** in fintech.

My work has focused on turning data into systems that support real business decisions — from predictive models and production data pipelines to CRM-integrated decision tools and AI-native workflows used by operational teams.

In my professional work, I have:

- Built **churn and deposit-propensity models** for 15,000+ customers
- Developed customer decision logic using **RFM, CLTV and behavioral signals**
- Integrated ML outputs into **Salesforce** and operational workflows
- Built and orchestrated production data pipelines with **Apache Airflow**
- Worked across **AWS, PostgreSQL, BI and CRM** ecosystems
- Established **Data Dictionary, Data Catalog and data quality** practices
- Collaborated with Product, CRM, Sales, Finance, Risk, Compliance and Engineering teams

More recently, I have been deepening my focus on **AI Engineering and AI-native product development**, especially around LLM-based applications, agentic workflows, tool use, RAG, structured outputs, validation and reliable AI-assisted software development.

I'm especially interested in the intersection of:

**Data Products × Production ML × AI Engineering × Product Thinking**

---

## AI Engineering Perspective

I don't think about AI as simply adding an LLM to an application.

I'm interested in how increasingly capable models can be turned into **reliable, measurable and controllable systems that operate inside real products and workflows**.

My professional work sits at the intersection of **production ML, agentic systems, data products and AI-native engineering**. I work with predictive models, LLM-based workflows, RAG, tool/function calling, structured outputs, validation and guardrails — with a strong focus on how AI outputs become real operational decisions.

A principle that shapes how I build is:

> **Capability alone is not enough. An AI system should also be testable, observable and trustworthy within the environment in which it operates.**

I try to separate **deterministic logic from probabilistic reasoning**.

Data validation, numerical scoring, business rules and access control remain explicit in code. LLMs are introduced where semantic understanding, reasoning or natural-language interaction genuinely adds value.

I'm particularly interested in:

- Agentic systems with controlled autonomy
- Evaluation and reliability of LLM applications
- RAG, grounding and tool use
- Human-in-the-loop system design
- Guardrails and failure-mode analysis
- AI-assisted software engineering

I also use coding agents such as **Claude Code** as an engineering partner for implementation, refactoring, debugging and exploring alternative solutions.

I treat AI-generated code the same way I would treat any external contribution: it should be understood, tested and validated before becoming part of a production system.

The broader problem I want to work on is:

**How do we give AI systems more reasoning and agency without losing our ability to understand, evaluate and control what they do?**

---

## Current AI Engineering Focus

- LLM-based application development
- Agentic workflows and automation
- RAG and semantic retrieval
- Tool / function calling
- Structured outputs and workflow design
- Validation, guardrails and reliable AI system design

---

## Selected Work

### Brokerage Operations AI Copilot

I'm working on an **AI-native operations copilot** for fintech and brokerage teams to interact with operational data and internal knowledge using natural language.

Instead of treating the system as a traditional chatbot, I approach it as a modular agentic architecture combining **structured data tools, RAG, tool calling and controlled orchestration**.

The goal is to prevent the LLM from accessing data or making decisions without boundaries. Data access is handled through defined tools, while outputs are validated and grounded before being returned to the user.

My focus in this project is on separating deterministic business logic from LLM reasoning and designing an AI system that can operate with **controlled autonomy, validation and guardrails** in a low-error-tolerance environment.

Because the project involves internal operational processes and proprietary data models, the repository is not public.

---

### Churn & Deposit Prediction — Fintech

Built Python-based churn and deposit-propensity models for **15,000+ customers**, designed around behavioral signals rather than simple active/inactive definitions.

The work covered data preparation, feature engineering, model evaluation, threshold design, scoring, validation and production orchestration.

Apache Airflow was used to automate data preparation and scoring pipelines, while model outputs were integrated into Salesforce so Sales and CRM teams could act on prioritized customer lists directly inside their existing workflow.

The goal was not simply to build a predictive model, but to turn model outputs into a **usable operational decision-support system**.

---

### Customer Retention Decision System

Worked on a Salesforce-based decision layer combining **CRM, trading and financial data** with RFM, CLTV and churn-risk signals.

The system was designed to help Sales and CRM teams understand customer behavior and prioritize actions without moving between disconnected analytics tools.

My focus was on making analytics outputs operational — not just visible.

---

### Winning Product Finder

Winning Product Finder is a personal **AI-native product research system** designed to automate repetitive product research and evaluation workflows.

The project combines:

- Python
- REST APIs
- Apify
- n8n
- LLM APIs
- Data validation
- Weighted scoring
- Multi-step workflow orchestration

The workflow follows this structure:

```text
Collect
   ↓
Validate
   ↓
Transform
   ↓
Score
   ↓
AI Analysis
   ↓
Validate
   ↓
Output
```

One of the core design decisions was to avoid sending every problem to an LLM.

Numerical scoring, validation, normalization and deterministic logic remain in code, while LLMs are used for semantic interpretation and reasoning.

The project also reflects how I use AI coding tools: as an engineering partner for implementation, refactoring, debugging and exploring alternative solutions — while still reviewing and understanding the generated code myself.

**GitHub:** [github.com/OzlemKlc/winning-product-finder](https://github.com/OzlemKlc/winning-product-finder)

---

### Enterprise Data Dictionary & Data Catalog

Built and standardized a shared data language across business teams by defining and documenting:

- KPI and metric definitions
- Business glossary
- Source systems
- Data owners
- Refresh logic
- Data lineage
- Data quality expectations

This work focused on making analytics and reporting outputs more consistent, explainable and trustworthy across teams.

---

## Tech Stack

### Data & Machine Learning

`Python` `SQL` `pandas` `NumPy` `scikit-learn`  
`Machine Learning` `Predictive Analytics` `RFM` `CLTV`

### AI Engineering

`LLM APIs` `Claude Code` `Agentic Workflows` `n8n`  
`RAG` `Tool Calling` `Structured Outputs` `Prompt Engineering`

### Data & Platform

`Apache Airflow` `AWS` `PostgreSQL` `REST APIs`  
`Git` `CI/CD` `Salesforce` `Tableau`

### Product & Data

`Product Analytics` `Data Products` `Data Quality`  
`Data Governance` `Agile / Scrum`

---

## Engineering Approach

I care about building systems that are not only technically correct, but also usable and reliable in production.

A few principles I try to follow:

- Separate deterministic logic from LLM reasoning
- Validate data before it reaches downstream systems
- Keep workflows modular and observable
- Ground AI outputs in real data or trusted sources
- Prefer explainable outputs over opaque automation
- Treat AI-generated code as code that still needs review
- Design around real user actions, not only model metrics
- Define clear boundaries for what an AI system can and cannot do
- Optimize for reliability before adding unnecessary complexity

---

## AI-Assisted Development

I actively use coding agents such as **Claude Code** during development.

I use them for:

- Initial implementation
- Refactoring
- Debugging
- Generating test scenarios
- Exploring alternative technical approaches
- Understanding documentation
- Reviewing potential edge cases

I don't treat generated code as automatically correct.

My workflow is closer to:

**Generate → Understand → Review → Test → Adapt**

AI is not the owner of the engineering decision. It is a tool that helps me shorten the feedback loop between an idea, an implementation and a tested solution.

---

## Earlier Public Work

My public repositories also include university and early software engineering projects covering:

- API gateway patterns
- Message-driven architecture with RabbitMQ
- Redis and MySQL
- Flask and Web APIs
- PyTorch
- Time-series analysis
- Association-rule analysis
- Image processing
- Frontend and full-stack coursework

I keep these repositories public as a record of my engineering foundations and learning path.

---

## Currently Exploring

- AI-native product engineering
- Agentic systems
- Evaluation and reliability for LLM applications
- RAG architectures
- Tool-using agents
- Human-in-the-loop systems
- AI-assisted development workflows
- Production AI system design
- Observability and failure modes in AI systems

---

## Open To

I'm currently interested in opportunities across:

**AI Engineer · Applied AI Engineer · AI Product Engineer · LLM Engineer · Data Scientist · Data Product**

I'm particularly interested in teams building **real AI products, production ML systems, agentic workflows and data-intensive products**.

---

## Get in Touch

- **LinkedIn:** [linkedin.com/in/kilic-ozlem](https://www.linkedin.com/in/kilic-ozlem/)
- **Email:** [ozlem.kilicdev@gmail.com](mailto:ozlem.kilicdev@gmail.com)
