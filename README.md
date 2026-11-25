# Awesome-Enterprise-AI-Orchestration-Workflow-Engines

<p align="center">
  <img src="./assets/banner.svg" alt="Top Enterprise AI Orchestration & Workflow Engines" width="100%" />
</p>

<p align="center">
  <a href="https://github.com"><img src="https://shields.io" alt="Awesome"/></a>
  <a href="https://discord.gg"><img src="https://shields.io" alt="Discord" /></a>
  <a href="https://github.com"><img src="https://shields.io" alt="GitHub stars" /></a>
  <a href="https://github.com"><img src="https://shields.io" alt="GitHub forks" /></a>
  <a href="https://github.com"><img alt="GitHub followers" src="https://shields.io" /></a>
</p>

# ⚙️ Top Enterprise AI Orchestration & Workflow Engines

**Curated List of SaaS/Commercial Platforms & Open-Source GitHub Projects**  
*Focused on Enterprise MLOps & LLMOps Pipelines, Multi-Agent AI Orchestration, GPU Cluster Scheduling, DAG Workflow Engines & Model Registry Infrastructure*  
**Last updated: November 2026**

This repository tracks notable **SaaS/Commercial platforms** and **open-source projects** for **Enterprise AI Orchestration & Workflow Engines**. These tools power end-to-end MLOps/LLMOps pipelines, durable multi-agent workflows, Kubernetes GPU scheduling, distributed Ray/Spark execution, experiment tracking, and hybrid-cloud AI governance for enterprise AI teams, ML platform engineers, and data architects.

**Examples** include Databricks Mosaic AI, Google Vertex AI, AWS Step Functions, Azure Machine Learning, Dataiku, Weights & Biases (CoreWeave), DataRobot, Domino Data Lab, Run:ai (NVIDIA), and MLflow Cloud (Databricks Managed MLflow) (the category leaders).

**🚀 Open-source emphasis**: This section is heavily expanded with every major active project for AI/ML workflow orchestration (`Orkas`, `Apache Airflow`, `Prefect`, `Dagster`, `Temporal`, `Flyte`, `Kubeflow`, `Metaflow`, `ZenML`), LLM/Agent orchestration (`LangGraph`, `Dify`, `n8n`, `CrewAI`), MLOps tracking (`MLflow`, `ClearML`), and GPU cluster scheduling (`SkyPilot`, `Volcano`, `Kueue`, `Ray`) — ideal for enterprise platform teams building portable, self-hosted AI infrastructure without vendor lock-in.

🤝 Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## 📑 Table of Contents
- [📊 Sector Overview & Market Dynamics](#-sector-overview--market-dynamics)
- [☁️ SaaS/Hosted & Commercial Platforms](#️-saashosted--commercial-platforms)
- [💻 Open-Source GitHub Projects](#-open-source-github-projects)
- [🛠️ How to Contribute](#️-how-to-contribute)
- [⚠️ Disclaimer](#️-disclaimer)
- [💖 Support & Thank You](#-support--thank-you)

## 📊 Sector Overview & Market Dynamics

The global MLOps, AI Orchestration & Enterprise Workflow Automation market is valued at approximately **$16B–$21B+ in 2026**, expanding at a ~28%–36% CAGR toward $65B+ by 2032 as enterprises shift from isolated LLM pilots to governed, multi-agent production pipelines. The cloud data and GPU infrastructure layer exhibits **strong winner-take-most consolidation** around hyperscalers (AWS, Google Cloud, Azure) and lakehouse/GPU giants (Databricks, NVIDIA/Run:ai, CoreWeave/W&B), while the workflow orchestration and agent-control plane remains **vibrantly competitive and open-source led** (`Airflow`, `Temporal`, `Prefect`, `Dagster`, `Kubeflow`, `MLflow`, `LangGraph`).

## ☁️ SaaS/Hosted & Commercial Platforms

*Sorted descending by company valuation / annual revenue scale.*

| Platform | Description | Company Scale (Valuation / Revenue) | Starting Paid Tier | Free Tier / Trial Limit |
| :--- | :--- | :--- | :--- | :--- |
| **[Google Vertex AI](https://google.com)** | Unified Google Cloud AI orchestration platform combining Vertex AI Pipelines (Kubeflow/TFX), Agent Builder, Model Garden, and managed GPU training. | **Part of Alphabet / Google Cloud** (~$45B+ Google Cloud ARR; ~$2T+ parent market cap) | **~$0.03 / pipeline run** + pay-as-you-go compute (e.g., `n1-standard-4` from ~$0.19/hr) | **$300 Free Cloud Credits** (90-day new-user trial + forever-free monthly quotas on select AI APIs and Cloud Workflows) |
| **[AWS Step Functions](https://amazon.com)** | Serverless visual workflow orchestrator coordinating distributed AI training jobs, Amazon Bedrock agents, Lambda functions, and SageMaker pipelines. | **Part of Amazon / AWS** (~$115B+ AWS annual revenue; ~$2T+ parent market cap) | **$0.025 per 1,000 state transitions** (Standard Workflows) or **$1.00 per 1M requests** (Express) | **Forever Free Tier** (**4,000 state transitions per month** free indefinitely across all AWS accounts) |
| **[Azure Machine Learning](https://microsoft.com)** | Enterprise cloud MLOps and AI orchestration suite featuring drag-and-drop/YAML pipelines, Prompt Flow, managed endpoints, and responsible AI governance. | **Part of Microsoft Azure** (~$85B+ Azure cloud revenue; ~$3T+ parent market cap) | **$0.00 workspace surcharge** (Pay-as-you-go underlying Azure VM/GPU compute starting at ~$0.05/hr) | **$200 Free Azure Credit** (30-day full trial + 12 months of free basic VM/storage services; Azure ML Studio free to create) |
| **[Databricks Mosaic AI](https://databricks.com)** | Unified data-and-AI orchestration platform integrating Mosaic AI Agent Framework, Unity Catalog governance, GPU model training, and Lakeflow jobs. | **$62.0B Valuation** ($3.0B+ ARR run-rate) | **$0.07 / DBU** (Databricks Unit) for Workflows/Jobs compute (plus underlying cloud VM cost) | **14-Day Full-Access Free Trial** (Includes Databricks Lakehouse & Mosaic AI trial workspace + Forever Free Community Edition) |
| **[MLflow Cloud (Databricks Managed MLflow)](https://databricks.com)** | Enterprise-hosted, zero-ops deployment of MLflow offering Unity Catalog model lineage, RBAC security, and managed experiment tracking at scale. | **Part of Databricks** ($62.0B parent valuation; $3.0B+ ARR) | **$0.07 – $0.15 / DBU** (Bundled into Databricks Data Intelligence Platform workspaces) | **Forever Free Community Edition** (Hosted Databricks Community Edition includes free managed MLflow tracking server with 15 GB micro-cluster) |
| **[Dataiku](https://dataiku.com)** | Collaborative enterprise AI and analytics workflow studio ("Everyday AI") uniting visual/code pipelines, LLM Mesh governance, and MLOps deployment. | **$3.7B+ Valuation** (~$250M+ ARR) | **~$4,000 – $5,000+ / month** indicative starting enterprise team license (custom quotes) | **Forever Free Edition** (Free downloadable/hosted personal edition for up to **3 users** with visual/Python/R pipelines; 14-day Cloud trial) |
| **[Weights & Biases (CoreWeave)](https://wandb.ai)** | Industry-standard AI developer platform for experiment tracking, W&B Weave LLM tracing, model registry, and automated hyperparameter sweeps. | **Acquired by CoreWeave for ~$1.7B** (~$200M+ ARR; part of $23B+ CoreWeave AI cloud) | **$50 / month** per user for Pro tier (Team/Enterprise custom volume pricing) | **Forever Free Personal & Academic Tier** (Unlimited public/private projects for individuals/academics with **100 GB artifact storage** free) |
| **[Run:ai (NVIDIA)](https://run.ai)** | Kubernetes-based AI compute orchestration and fractional GPU virtualization platform maximizing cluster utilization for enterprise training and inference. | **Acquired by NVIDIA for ~$700M** (~$130B+ NVIDIA parent revenue) | **Enterprise Per-GPU / Cluster Subscription** (Custom annual licensing per managed GPU node) | **Guided Enterprise Sandbox / Demo** (No perpetual self-serve SaaS free tier; NVIDIA/Run:ai provides open-source `KubeAI`/K8s scheduler integrations) |
| **[DataRobot](https://datarobot.com)** | End-to-end enterprise AI lifecycle and generative AI orchestration platform featuring AutoML, predictive/generative guardrails, and production monitoring. | **~$1.0B–$2.5B Est. Valuation** (~$300M+ est. ARR) | **~$10,000+ / year** indicative starting enterprise AI platform subscription (custom quotes) | **14-Day Guided Free Trial** (Limited trial access to DataRobot Workbench and generative AI playground via business email registration) |
| **[Domino Data Lab](https://dominodatalab.com)** | Enterprise AI platform orchestrating hybrid/multi-cloud model development, reproducible workspaces, governance, and NVIDIA GPU workloads. | **~$1.0B+ Est. Valuation** (~$100M+ est. ARR; backed by Sequoia/Coatue) | **Enterprise Seat + Compute Subscription** (Custom annual enterprise licensing starting ~$1,500+/user/yr) | **Guided Enterprise Trial / Sandbox** (No perpetual free SaaS tier; hands-on trial environment available upon enterprise demo request) |

## 💻 Open-Source GitHub Projects

| Project | License / Hosting Cost | Free Tier / Self-Hosted Limit | Description |
| :--- | :--- | :--- | :--- |
| **[Orkas (`Orkas-AI/Orkas`)](https://github.com)** | **Open-Source** ($0 self-hosted; bring-your-own LLM/compute endpoints) | **100% Free forever** (Unlimited AI workflow orchestration, multi-agent pipelines, and task execution on your own infrastructure) | Open-source AI orchestration and workflow engine engineered to coordinate intelligent agents, automated pipelines, and enterprise AI tasks. |
