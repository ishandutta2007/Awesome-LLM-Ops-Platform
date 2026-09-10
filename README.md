# Awesome-LLM-Ops-Platform

## Top LLMOps Platforms Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Prompt Management, Tracing, Evaluation, Versioning, Experimentation & Production LLM Operations*

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **LLMOps**. These tools help teams develop, evaluate, version, monitor, and improve LLM and agent applications across the full lifecycle — from prompt engineering to production observability.



**Examples** include LangSmith, Weights & Biases, Langfuse, Helicone, Arize Phoenix, Traceloop, Humanloop, Literal AI, Galileo, PromptLayer, HoneyHive, Comet Opik, and Agenta (the category leaders).



**Open-source emphasis**: LLMOps has a rich open-source ecosystem. **Langfuse**, **Arize Phoenix**, **Comet Opik**, **Helicone**, **Agenta**, **OpenLLMetry**, and related projects deliver production-grade tracing, evals, and prompt management with full self-hosting. This section is heavily expanded with these tools.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saashosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

| Platform | Description / Core Focus | Pricing (Starting Tier) | Free Tier / Trial Limits |
| :--- | :--- | :--- | :--- |
| **[LangSmith](https://www.langchain.com/langsmith)** | End-to-end LLMOps platform tightly integrated with LangChain/LangGraph — tracing, evaluation, prompt hub, datasets, and production monitoring. | **$39 / user / month** (Plus plan, includes 10,000 base traces/mo; overage $0.50/1k traces) | **Free forever** (Developer plan): 1 seat, 5,000 base traces/month, 14-day data retention |
| **[Weights & Biases (Weave)](https://wandb.ai/site/weave)** | Experiment tracking, tracing, and evaluation for LLM applications inside the broader W&B MLOps platform. | **$60 / month** (Pro plan, includes 10 model seats, 100 GB storage, 1.5 GB/mo Weave ingestion) | **Free forever**: Up to 5 model seats, 5 GB storage/month, 1 GB/month Weave data ingestion |
| **[Galileo](https://www.galileo.ai/)** | LLM evaluation, observability, and quality monitoring platform aimed at production reliability. | **$100 / month** ($100/mo billed annually or $150/mo billed monthly for Pro plan; includes 50,000 traces/mo) | **Free forever**: 5,000 traces/month, unlimited users, unlimited custom evaluations |
| **[PromptLayer](https://www.promptlayer.com/)** | Prompt management, logging, versioning, and basic observability for teams iterating on prompts. | **$49 / month** (Pro plan, includes unlimited playgrounds/workspaces, 150 MB dataset size, $0.003/extra transaction) | **Free forever** (Hacker plan): 5 users, 2,500 requests/month, 750 agent executions/mo, 250 eval cell executions/mo, 10 MB dataset limit |
| **[Braintrust](https://www.braintrust.dev/)** | Enterprise-grade evaluation, tracing, prompt playground, and dataset management platform. | **$249 / month** (Pro plan, includes 5 GB data, 50,000 scores, $100/mo model credits, 30-day retention) | **Free forever** (Starter plan): 1 GB processed data/month, 10,000 scores/month, $10/mo model credits, 14-day data retention |
| **[Portkey](https://portkey.ai/)** | AI Gateway and LLM observability platform with intelligent routing, caching, prompt management, and guardrails. | **$49 / month** (Production plan, includes 100,000 recorded logs; overage $9 per 100k logs) | **Free forever** (Developer plan): 10,000 recorded logs/month, unlimited unlogged routing requests |
| **[Arize AX](https://arize.com/)** | Enterprise AI observability and evaluation platform with OpenTelemetry tracing, Alyx AI debug assistant, and labeling. | **$50 / month** (AX Pro plan, includes 100,000 trace spans/month, 100 GB storage, unlimited users) | **Free forever** (AX Free plan): 1 user, 25,000 trace spans/month, 1 GB storage, 14-day retention |
| **[Langfuse Cloud](https://langfuse.com/)** | Managed cloud version of the open-source LLMOps platform — tracing, prompt management, evaluations, and datasets. | **$29 / month** (Core plan, includes 100,000 units/month, 90-day retention; overage $8/100k units) | **Free forever** (Hobby plan): 2 users, 50,000 units/month, 30-day data retention |
| **[Helicone Cloud](https://www.helicone.ai/)** | LLM observability and gateway platform offering request logging, cost tracking, caching, alerts, and analytics. | **$79 / month** (Pro plan, includes 10,000 requests/month, unlimited seats, 1-month retention) | **Free forever** (Hobby plan): 1 user, 10,000 requests/month, 1 GB storage, 7-day data retention |
| **[Comet Opik Cloud](https://www.comet.com/site/products/opik/)** | Managed tracing and evaluation platform for LLM applications with automated metric tracking and dataset curation. | **$19 / month** (Pro plan, includes up to 50 team members, 100,000 spans/month, 60-day retention) | **Free forever** (Free plan): Up to 10 team members, 25,000 spans/month, 60-day data retention |
| **[Agenta Cloud](https://agenta.ai/)** | Developer platform for prompt engineering, collaborative evaluation, and rapid LLM application iteration. | **$49 / month** (Pro plan, includes 3 seats, 10,000 agent runs/month, 1-month retention) | **Free forever** (Hobby plan): 2 team members, 5,000 agent runs/month, 7-day data retention |
| **[HoneyHive](https://www.honeyhive.ai/)** | LLM observability and evaluation platform with production monitoring, evaluation benchmarks, and feedback loops. | **Custom Enterprise quote** (Tailored SLAs, dedicated account manager, startup discounts for <$5M raised) | **Free forever** (Developer plan): 5 users, 10,000 events/month, 1,000 requests/min, 30-day retention |
| **[Humanloop](https://www.humanloop.com/)** | Collaborative prompt engineering, evaluation, and feedback platform (Acquired by Anthropic in Aug 2025). | **Custom Enterprise quote** (Platform acquired by Anthropic; grandfathered/enterprise access) | **Free plan / Trial**: 2 team members, 10,000 logs/month, 50 evaluation runs |
| **[Literal AI](https://literalai.com/)** | Observability and evaluation platform for LLM applications created by the makers of Chainlit (Platform sunset). | **Custom Enterprise quote** (Hosted platform sunset; self-hosting retired Oct 2025) | **Free Basic tier**: 10,000 log units/month, 30-day retention |



## Open-Source GitHub Projects

- **[Langfuse](https://github.com/langfuse/langfuse)**  

  Leading open-source LLM engineering / LLMOps platform (MIT) — tracing, prompt management, evaluations, datasets, metrics, and playground. Fully self-hostable with a managed cloud option.



- **[Arize Phoenix](https://github.com/Arize-ai/phoenix)**  

  Open-source AI observability and evaluation platform — OpenTelemetry-native tracing, LLM-as-judge evals, datasets, and debugging. Self-host free; managed via Arize AX.



- **[Comet Opik](https://github.com/comet-ml/opik)**  

  Open-source tracing and evaluation toolkit for LLM applications, usable standalone or within the Comet platform.



- **[Helicone](https://github.com/Helicone/helicone)**  

  Open-source LLM observability via proxy or SDK — logging, cost tracking, caching, and analytics. Self-hostable.



- **[Agenta](https://github.com/Agenta-AI/agenta)**  

  Open-source LLMOps platform focused on prompt engineering, evaluation, and collaborative development of LLM applications.



- **[OpenLLMetry / Traceloop](https://github.com/traceloop/openllmetry)**  

  OpenTelemetry-native instrumentation for LLM and agent applications, enabling vendor-neutral tracing.



- **[OpenLIT](https://github.com/openlit/openlit)**  

  Open-source, OpenTelemetry-native platform for tracing, evaluations, prompt management, and cost tracking.



- **[DeepEval](https://github.com/confident-ai/deepeval)**  

  Open-source evaluation framework with pytest-style testing for prompts, RAG, and agents — ideal for CI/CD.



- **[Promptfoo and similar prompt-testing tools](https://github.com/)**  

  Open-source prompt evaluation and red-teaming frameworks for systematic testing.



- **[Custom LLMOps stacks (OTEL + Grafana + eval libraries)](https://github.com/)**  

  Composable open pipelines that combine instrumentation, storage, dashboards, and evaluation code.



### Additional Strong Open-Source Options

- Starting with **Langfuse** for the most complete open LLMOps workbench (traces + prompts + evals + datasets).

- Choosing **Arize Phoenix** or **Comet Opik** when OpenTelemetry-native tracing and strong evaluation primitives matter most.

- Using **Agenta** for collaborative prompt engineering and evaluation workflows.

- Instrumenting with **OpenLLMetry** so traces can land in any OTEL backend you already operate.

- Running **DeepEval** or **Promptfoo** in CI to catch regressions before deployment.

- Accepting that some enterprise features (advanced SSO, managed scale, specialized agent analytics) still favor commercial platforms.



**Frameworks for building custom systems**: Instrument LLM/agent calls with open SDKs or OpenTelemetry → store traces and prompts in a self-hosted platform (Langfuse / Phoenix) → version prompts and datasets → run automated and human evaluations → monitor cost, latency, and quality in production. This stack is fully open and widely used. Commercial platforms (LangSmith, W&B Weave, Humanloop, Galileo, HoneyHive, etc.) remain strong when you want tight framework integration, managed infrastructure, or specialized collaboration features without operating the stack yourself.



## How to Contribute

1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.

- LLMOps platforms capture prompts, outputs, and sometimes user data. Treat this information as sensitive and apply appropriate access controls, retention policies, and compliance measures. Self-hosted deployments require security hardening, backups, and monitoring of the observability infrastructure itself. Automated evaluation scores are decision-support tools, not absolute ground truth. This list is not security, compliance, or production-architecture advice.



---

**Made for AI engineers, LLMOps practitioners, and teams shipping reliable LLM applications.**

Let's keep the full LLM lifecycle observable, evaluable, and as open as possible.
