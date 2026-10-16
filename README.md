# Awesome-Automl-Low-Code-ML

# Top AutoML & Low-Code ML Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on No-Code Model Building, Automated Feature Engineering & Citizen Data Science*  
**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **AutoML & Low-Code ML**. These tools enable analysts, domain experts, and developers to build and deploy machine learning models with minimal code—automating feature engineering, model selection, hyperparameter tuning, and deployment.

**Examples** include DataRobot, H2O Driverless AI, Google Cloud AutoML, AWS SageMaker Autopilot, Azure Automated ML, Dataiku, Pecan AI, BigML, dotData, and Akkio (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, low-code ML, and open AutoML—ideal for data scientists, analysts, and organizations seeking transparent, vendor-independent model building.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[DataRobot](https://www.datarobot.com/)**
  **Enterprise AutoML platform** with **model monitoring, challenger comparison, and compliance documentation** . Features **LLM fine-tuning workflows** (2025–2026 releases). **The enterprise governance play**—justifies cost for large institutions managing regulatory risk .

- **[H2O Driverless AI](https://h2o.ai/platform/ai-cloud/make/h2o-driverless-ai/)**
  **Automatic machine learning platform** with **feature engineering, model selection, and hyperparameter tuning** . Features **MOJO export** for deployment without cloud dependency. **The most mature enterprise AutoML** for tabular data.

- **[Google Cloud AutoML](https://cloud.google.com/automl)**
  **Google's managed AutoML suite** for vision, natural language, and tabular data. Features **custom model training** without ML expertise. **Vertex AI** consolidates AutoML with custom training and MLOps.

- **[AWS SageMaker Autopilot](https://aws.amazon.com/sagemaker/autopilot/)**
  **Fully managed AutoML** that automatically explores data, selects algorithms, and tunes hyperparameters. Features **transparent model explanations** and **deployment-ready artifacts** .

- **[Azure Automated ML](https://azure.microsoft.com/en-us/products/machine-learning/automatedml/)**
  **Microsoft's AutoML** integrated with Azure Machine Learning. Features **automated feature engineering**, **model selection**, and **responsible AI dashboards**.

- **[Dataiku](https://www.dataiku.com/)**
  **Enterprise AI platform** uniting people, orchestration, and governance. **No-code, low-code, and full-code interfaces** for analytics, ML, and AI agents. **$350M ARR, 750+ customers, 1,200+ employees** globally .

- **[Pecan AI](https://www.pecan.ai/)**
  **Predictive AI agent built for business outcomes** . **Automates data prep and modeling, delivering predictions directly to CRM**. **90% of predictions delivered without data science support** .

- **[BigML](https://bigml.com/)**
  **Cloud-based machine learning platform** founded 2011. **Provides scalable ML services for data-driven decision making**. **Accessible to non-experts**—upload data and start exploring .

- **[dotData](https://www.dotdata.com/)**
  **Leader in automated feature discovery and extraction platform** . **dotData Enterprise 4.0** features AI-powered automated feature engineering that analyzes complex relational data in hours. **Trusted by Fortune 500 companies** .

- **[Akkio](https://www.akkio.com/)**
  **Predictive analytics and modeling platform** empowered by generative AI . **Founded 2019, headquartered in Cambridge, MA**. **Serves businesses of all sizes with swift insights** .

## Open-Source GitHub Projects

- **[PyCaret](https://github.com/pycaret/pycaret)**  
  **The most widely used open-source, low-code machine learning library in Python** (MIT) . **9,836+ GitHub stars** . **PyCaret 4.0 (February 2026)**: **sklearn-native engine** (reuses sklearn estimators, splitters, metrics, and pipelines directly) + **React control plane** . **Unified interface** for regression, classification, clustering, anomaly detection, NLP, and time series . **Low-code workflow**: `setup()` → `compare_models()` → `tune_model()` → `finalize_model()` → `deploy_model()` . **Runs on Jupyter, VS Code, or the new web UI** . **The default choice for teams that want AutoML without deep infrastructure investment** .

- **[AutoGluon](https://github.com/autogluon/autogluon)**  
  **Fast and accurate ML in 3 lines of code** (Apache-2.0) . **10,594+ GitHub stars** . **Broadest open-source coverage**—tabular, time series, multimodal, and foundation-model support . **Multi-layer stacking and automatic feature engineering** . **Best for maximum benchmark performance and broad task coverage** .

- **[MLJAR AutoML](https://github.com/mljar/mljar-supervised)**  
  **Tabular AutoML with reports, explanations, feature engineering, tuning, stacking, and ensembling** (Apache-2.0) . **Powered by mljar-supervised**. **Built around reports and explainability from the beginning**—gives you models, reports, explanations, and artifacts that can be reviewed later . **Best for privacy-sensitive, explainable, local business modeling** .

- **[FLAML](https://github.com/microsoft/FLAML)**  
  **Resource-aware AutoML and tuning** (MIT). **Fast, budget-aware model search**—excellent when compute budget and training time matter . **Lightweight and efficient** with support for classification, regression, and time series.

- **[TPOT](https://github.com/EpistasisLab/tpot)**  
  **Genetic programming for pipeline search** (LGPL-3.0) . **10,049+ GitHub stars** . **Outputs scikit-learn code** that teams can read and modify . **Best for discovering pipeline structures** and interpretable ML pipelines .

- **[H2O AutoML](https://github.com/h2oai/h2o-3)**  
  **Distributed enterprise AutoML** with algorithm portfolios and stacked ensembles (Apache-2.0) . **Fastest open-source option**—trains models in 5–10 minutes typically . **Competitive accuracy on tabular data**. **Best for scalable tabular ML in enterprise environments** .

- **[Auto-sklearn](https://github.com/automl/auto-sklearn)**  
  **Automated machine learning with scikit-learn** (BSD-3-Clause) . **8,128+ GitHub stars** . **Bayesian optimization, meta-learning, ensemble selection**. **Often wins competitions**—5–15% better than H2O on hard problems . **No recent major release**—latest official release from 2023 .

- **[AutoKeras](https://github.com/keras-team/autokeras)**  
  **AutoML system based on Keras** (Apache-2.0) . **9,086+ GitHub stars** . **Automatic model architecture search** for deep learning tasks . **The Keras-native AutoML** for neural architecture search .

### Additional Strong Open-Source Options

- **[Ludwig (Uber)](https://github.com/ludwig-ai/ludwig)** — Low-code framework for building custom LLMs, neural networks, and tree-based models (Apache-2.0) . **11,259+ GitHub stars** . **Declarative YAML configuration**—no code required .
- **[NNI (Microsoft)](https://github.com/microsoft/nni)** — Neural Network Intelligence (MIT) . **14,365+ GitHub stars** . **Automates feature engineering, neural architecture search, model compression, and hyperparameter tuning** .
- **[Featuretools](https://github.com/alteryx/featuretools)** — Automated feature engineering for relational data (BSD-3-Clause) . **Deep feature synthesis** for complex datasets .
- **[MLflow](https://github.com/mlflow/mlflow)** — Open source AI engineering platform (Apache-2.0) . **27,484+ GitHub stars** . **Experiment tracking, model registry, and deployment** .
- Community **n8n** workflows for AutoML pipeline automation and model deployment alerts.

**Frameworks for building custom systems**: Combine **PyCaret** for low-code AutoML with **MLJAR AutoML** for explainable reports, **AutoGluon** for broad task coverage, **FLAML** for budget-aware search, and **MLflow** for experiment tracking and deployment—creating a fully self-hosted, enterprise-grade low-code ML platform.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- AutoML and low-code ML systems handling training data must comply with data protection regulations (GDPR, CCPA, etc.) and model governance requirements.
- **Open-source low-code ML is mature and production-ready.** PyCaret (9.8K+ stars) provides the most accessible AutoML workflow with sklearn-native engine . AutoGluon delivers broad task coverage . MLJAR AutoML prioritizes explainability . **These are genuine alternatives to commercial platforms.**
- **The right tool depends on your deployment environment, not the benchmark leaderboard.** "The best model is the one your team can monitor and retrain without external help" . **Choose based on operational fit, not accuracy alone.**
- **auto-sklearn has no recent major release.** Latest official release from 2023 . **Not recommended as default for new production projects in 2026.**
- **Low-code does not mean no-expertise.** AutoML automates search, not problem formulation. Feature engineering, target definition, and validation strategy still require domain understanding.
- Self-hosted open-source solutions require proper compute provisioning, experiment tracking infrastructure, and ongoing maintenance. **AutoML models require the same monitoring and retraining discipline as hand-built models.**

---

**Made for data scientists, analysts, and organizations building transparent low-code ML solutions.**  
Let's make AutoML & Low-Code ML more open, data-driven, and accessible.
