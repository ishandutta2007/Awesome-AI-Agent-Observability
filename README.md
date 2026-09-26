# Awesome-AI-Agent-Observability

# Top AI Agent Observability Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Agent Tracing, Span-Level Telemetry, Session Replay, Cost & Latency Analytics, Tool-Call Visibility & Production Agent Debugging*  
**Last updated: September 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **AI Agent Observability**. These systems instrument multi-step agents—capturing LLM calls, tool use, memory, and handoffs—so teams can debug failures, measure reliability, and optimize cost and latency in production.

**Examples** include Langfuse, Arize Phoenix, Braintrust, LangSmith, Helicone, Traceloop, OpenLIT, Lunary, WhyLabs AI Observatory, and Weights & Biases Weave (the category leaders).

**Open-source emphasis**: Agent observability has a strong open stack. **Langfuse**, **Arize Phoenix**, **OpenLLMetry (Traceloop)**, **Helicone**, **OpenLIT**, and related projects provide self-hosted tracing and analytics. This section is heavily expanded.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Langfuse (Cloud)](https://langfuse.com/)**  
  LLM and agent engineering platform—traces, sessions, prompt management, and evals with excellent multi-step agent support (open-source core available).

- **[LangSmith](https://www.langchain.com/langsmith)**  
  Observability and debugging hub for LangChain/LangGraph agents—full trajectory inspection, datasets, and evaluation.

- **[Arize Phoenix / Arize AX](https://arize.com/)**  
  Open Phoenix plus enterprise Arize for tracing, evaluation, and monitoring of agents and LLM applications.

- **[Braintrust, Helicone, Lunary](https://www.braintrust.dev/)**  
  Platforms focused on logging, scoring, cost analytics, and production insights for LLM and agent workloads.

- **[Traceloop, OpenLIT, WhyLabs AI Observatory](https://www.traceloop.com/)**  
  OpenTelemetry-oriented and AI-native observability offerings for GenAI and agent telemetry.

- **[Weights & Biases Weave](https://wandb.ai/weave)**  
  W&B’s observability and evaluation layer for LLM and agent applications, integrated with experiment tracking.

- **[Other commercial agent observability platforms](https://langfuse.com/)**  
  Additional solutions for agent session replay, multi-agent analytics, and production reliability.

## Open-Source GitHub Projects

- **[Langfuse](https://github.com/langfuse/langfuse)**  
  Leading open-source (MIT) platform for LLM and agent observability—traces, nested spans, sessions, dashboards, and evals; fully self-hostable.

- **[Arize Phoenix](https://github.com/Arize-ai/phoenix)**  
  Open-source tracing and evaluation toolkit for LLM and agent runs—OpenTelemetry-friendly, notebook and production use.

- **[OpenLLMetry (Traceloop)](https://github.com/traceloop/openllmetry)**  
  OpenTelemetry instrumentation for GenAI and agents—standard spans for LLM providers, tools, and vector DBs exportable to any OTel backend.

- **[Helicone](https://github.com/Helicone/helicone)**  
  Open-source proxy logging for LLM/agent traffic—request/response capture, cost, and latency analytics with simple gateway integration.

- **[OpenLIT](https://github.com/openlit/openlit)**  
  Open instrumentation and observability layer for LLM and agent stacks, emitting traces and metrics for existing backends.

- **[Opik (Comet)](https://github.com/comet-ml/opik)**  
  Open evaluation and observability library for tracing agent runs and comparing experiments.

- **[Lunary open / agent logging projects](https://github.com/search?q=lunary+OR+agent+observability+open+source)**  
  Community and vendor open components for agent session logging and analytics.

- **[OpenTelemetry GenAI semantic conventions](https://opentelemetry.io/)**  
  Emerging standard for LLM and agent spans—foundation for vendor-neutral observability pipelines.

### Additional Strong Open-Source Options

- **Full observability product**: Langfuse for end-to-end agent traces, sessions, and evals.
- **OTel-native**: OpenLLMetry + Grafana/Jaeger/Datadog for custom agent telemetry.
- **Proxy path**: Helicone/OpenLIT for quick visibility without deep SDK work.
- **Eval + observe**: Phoenix and Opik for experiment tracking tied to production traces.
- **Composable stacks**: LangGraph/CrewAI agents + Langfuse or OpenLLMetry + dashboards.
- Commercial platforms still lead in polished multi-team UX and managed insight reports.

**Frameworks for building custom systems**:  
**Langfuse** and **Phoenix** are the strongest open agent observability products.  
**OpenLLMetry** and **Helicone** provide instrumentation and proxy options.  
Commercial platforms (LangSmith, Braintrust, W&B Weave, WhyLabs, Lunary, etc.) add enterprise workflows and analytics.  
Most teams instrument with open SDKs and optionally send data to commercial backends. Fully open stacks are production-ready with self-hosted Langfuse or OTel collectors.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Agent traces often contain prompts, tool outputs, and sensitive data. Apply redaction, encryption, retention limits, and strict access control. Observability does not by itself prevent harmful agent actions—pair with guardrails and least-privilege tools.
- Open-source tools offer data residency and control but require operational ownership. Commercial platforms shift that burden to the vendor. Align observability with your security and compliance requirements.

---

**Made for agent builders, AI platform teams, and anyone debugging multi-step agents in production.**  
Let's expand open AI agent observability while recognizing the specialized analytics and scale that leading commercial platforms deliver.
