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

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

- **[LangSmith](https://www.langchain.com/langsmith)**  

  End-to-end LLMOps platform tightly integrated with LangChain/LangGraph — tracing, evaluation, prompt hub, datasets, and production monitoring.



- **[Weights & Biases (Weave)](https://wandb.ai/site/weave)**  

  Experiment tracking, tracing, and evaluation for LLM applications inside the broader W&B MLOps platform.



- **[Humanloop](https://www.humanloop.com/)**  

  Prompt engineering and evaluation platform focused on collaborative development, versioning, and production feedback.



- **[Literal AI](https://literalai.com/)**  

  LLM observability and collaboration platform for tracing, evaluation, and improving AI applications.



- **[Galileo](https://www.galileo.ai/)**  

  LLM evaluation, observability, and quality monitoring platform aimed at production reliability.



- **[PromptLayer](https://www.promptlayer.com/)**  

  Prompt management, logging, versioning, and basic observability for teams iterating on prompts.



- **[HoneyHive](https://www.honeyhive.ai/)**  

  LLM observability and evaluation platform with production monitoring and feedback loops.



- **[Other commercial LLMOps / AI engineering platforms](https://github.com/)**  

  Additional hosted tools covering prompt ops, agent monitoring, or integrated evaluation workflows.



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
