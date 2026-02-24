# Lab 5: AI Observability

## 5.1 Intro

### The Challenge of AI in Production

As organizations rapidly adopt generative AI and large language models (LLMs) into their applications, a new set of observability challenges emerges. Traditional monitoring approaches fall short when dealing with AI systems because:

- **Non-deterministic behavior** — Unlike conventional applications, AI models can produce different outputs for the same input
- **Complex dependencies** — Modern AI applications involve multiple models, RAG pipelines, vector databases, and agentic frameworks working together
- **Hidden costs** — Token consumption, API fees, and GPU resources can spiral without proper visibility
- **Quality risks** — Model hallucinations, prompt injection attacks, and data drift can degrade user experience and introduce security vulnerabilities

**AI Observability** is the practice of monitoring, analyzing, and visualizing the internal states, inputs, and outputs of AI models embedded in modern applications—ensuring correctness, reliability, and effectiveness while supporting compliance requirements.

### Dynatrace AI Observability

Dynatrace extends its unified observability platform to provide comprehensive insights into AI applications, helping teams drive reliability, performance, security, and compliance while understanding their AI return on investment (ROI).

| Capability | Description |
|------------|-------------|
| **LLM Monitoring** | Track performance metrics including token consumption, latency, availability, and errors across AI providers |
| **Multi-model Tracing** | Map dependencies between multiple LLMs working with RAG pipelines or agentic frameworks |
| **Input/Output Guardrails** | Detect model hallucinations, prompt injection attempts, PII leakage, and toxic language |
| **Vector Database Monitoring** | Monitor solutions like Milvus, Weaviate, and Qdrant for performance bottlenecks |
| **Cost Tracking** | Visibility into token usage, service fees, and resource consumption |
| **Responsible AI** | Audit trail of every input and output for governance and compliance |

![image](img/lab5-ai-observability-overview.png)

### Key Metrics for AI Applications

Dynatrace monitors critical metrics that determine AI application health:

- **Stability** — Frequency of successful model responses vs. failures
- **Latency** — Time taken by models or services to return results
- **Load** — Volume of requests handled and detection of abnormal spikes/drops
- **Model drift** — Changes in model accuracy due to shifting input data
- **Data drift** — Monitoring input data stationarity over time
- **Cost** — Token usage, service fees, and resource consumption

### Integration with Azure AI Services

Dynatrace integrates with major AI providers including:

- **Azure OpenAI Service** — Monitor GPT models deployed in Azure
- **NVIDIA NIM** — Observe inference microservices
- **OpenAI** — Direct integration with OpenAI APIs
- **Ollama** — Monitor locally deployed models

??? info
    ℹ️ For more details on AI Observability capabilities, see the <a href="https://docs.dynatrace.com/docs/observe/dynatrace-for-ai-observability" target="_blank">Dynatrace AI Observability Documentation</a>.

### Objectives of this Lab

🔷 Explore the AI Observability app and locate AI-powered services

🔷 Monitor LLM service and model health metrics

🔷 Analyze token consumption and cost implications

🔷 Troubleshoot latency issues in LLM responses

🔷 Explore distributed traces to view prompts and responses

### Lab Sections

| Section | Description |
|---------|-------------|
| 5.2 AI Observability App | Explore the AI Observability interface |
| 5.3 Service Health | Monitor LLM service and model health |
| 5.4 Cost & Tokens | Analyze token consumption and costs |
| 5.5 Latency | Troubleshoot latency issues |
| 5.6 Traces | Explore traces with prompts and responses |
| 5.7 Summary | Review what you accomplished |
