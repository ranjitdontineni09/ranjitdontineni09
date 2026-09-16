<div align="center">

# Ranjit Dontineni

Full-stack AI engineer. Cloud services, streaming data, and agents that cite their sources.

Atlanta | MS CS @ Georgia State | SDE Intern @ AWS Connect | previously SDE I @ Aditya Birla Capital

**[Open the interactive command center](https://ranjitdontineni09.github.io/#/overview)**

[Overview](https://ranjitdontineni09.github.io/#/overview)
| [Stack](https://ranjitdontineni09.github.io/#/stack)
| [Systems](https://ranjitdontineni09.github.io/#/systems)
| [Timeline](https://ranjitdontineni09.github.io/#/timeline)
| [LinkedIn](https://www.linkedin.com/in/ranjit-dontineni-767399216/)
| [Email](mailto:ranjitdontineni9@gmail.com)

</div>

GitHub profile pages cannot run JavaScript, so the dashboards live on GitHub Pages. Every control below expands here and also jumps into the live command center on the matching view.

<details open>
<summary><strong>Live production signal</strong> - click a metric to inspect it</summary>

| Signal | Proof | Open live |
| --- | --- | --- |
| **10M+** messages / day | WhatsApp / SMS / email journeys on API Gateway + Lambda | [comms platform](https://ranjitdontineni09.github.io/#/systems/biztalk/lambda) |
| **27M** daily KYC / loan APIs | Submit-poll-webhook contracts, 99.9% availability | [loan / KYC APIs](https://ranjitdontineni09.github.io/#/systems/biztalk/lambda) |
| **350ms** holdings latency | DynamoDB read-through cache, was 2.8s | [cache refresh](https://ranjitdontineni09.github.io/#/systems/biztalk/sfn) |
| **24h to minutes** Connect freshness | Lambda, SQS, Kinesis, Spark, Iceberg | [Connect stream](https://ranjitdontineni09.github.io/#/systems/connect/iceberg) |

</details>

<details>
<summary><strong>Stack topology</strong> - interface down to cloud</summary>

| Layer | What shipped | Inspect |
| --- | --- | --- |
| INTERFACE | React, REST, command UIs, tracking dashboards | [React](https://ranjitdontineni09.github.io/#/stack/react) | [REST](https://ranjitdontineni09.github.io/#/stack/apis) |
| AGENTS | RAG, LoRA, Llama, Qdrant, DeepSeek Harness | [RAG](https://ranjitdontineni09.github.io/#/stack/rag) | [LoRA](https://ranjitdontineni09.github.io/#/stack/lora) |
| SERVICES | Node.js, Java, Spring Boot, FastAPI, Lambda | [Node](https://ranjitdontineni09.github.io/#/stack/node) | [Java](https://ranjitdontineni09.github.io/#/stack/java) |
| STREAMS | Kinesis, Kafka, Spark, Iceberg, SQS | [Spark](https://ranjitdontineni09.github.io/#/stack/spark) | [Kafka](https://ranjitdontineni09.github.io/#/stack/kafka) |
| CLOUD | AWS, DynamoDB, EMR Serverless, Docker, CI/CD | [AWS](https://ranjitdontineni09.github.io/#/stack/aws) | [CI/CD](https://ranjitdontineni09.github.io/#/stack/docker) |

</details>

<details>
<summary><strong>Systems</strong> - click a stage on the live pipeline</summary>

**Connect stream** (Amazon Connect telemetry)

`SQS + Lambda` -> `Kinesis` -> `Spark / EMR` -> `Iceberg`

[Events](https://ranjitdontineni09.github.io/#/systems/connect/events)
| [Kinesis](https://ranjitdontineni09.github.io/#/systems/connect/kinesis)
| [Spark](https://ranjitdontineni09.github.io/#/systems/connect/spark)
| [Iceberg](https://ranjitdontineni09.github.io/#/systems/connect/iceberg)

**BizTalk to AWS** (8+ services, 12 Lambdas)

`API Gateway` -> `12 Lambdas` -> `DynamoDB` -> `Step Functions`

[Gateway](https://ranjitdontineni09.github.io/#/systems/biztalk/gw)
| [Lambdas](https://ranjitdontineni09.github.io/#/systems/biztalk/lambda)
| [DynamoDB](https://ranjitdontineni09.github.io/#/systems/biztalk/ddb)
| [Step Functions](https://ranjitdontineni09.github.io/#/systems/biztalk/sfn)

**Grounded Q&A agent** (refuse when retrieval is empty)

`React UI` -> `FastAPI` -> `Qdrant RAG` -> `Llama + LoRA`

[UI](https://ranjitdontineni09.github.io/#/systems/agent/ui)
| [API](https://ranjitdontineni09.github.io/#/systems/agent/api)
| [RAG](https://ranjitdontineni09.github.io/#/systems/agent/ret)
| [Model](https://ranjitdontineni09.github.io/#/systems/agent/model)

</details>

<details>
<summary><strong>Path</strong> - ABC / GSU / AWS</summary>

| When | Where | Open |
| --- | --- | --- |
| 2019–2023 | VIT, B.Tech Computer Science, 8.88/10 | [timeline](https://ranjitdontineni09.github.io/#/timeline) |
| 2023–2025 | Aditya Birla Capital, SDE I, 10M+ msgs/day | [timeline](https://ranjitdontineni09.github.io/#/timeline) |
| 2025–2027 | Georgia State, MS CS + GRA | [timeline](https://ranjitdontineni09.github.io/#/timeline) |
| Summer 2026 | AWS Connect intern, streaming telemetry | [Connect](https://ranjitdontineni09.github.io/#/systems/connect) |

</details>

---

### Runtime

```text
languages   Java | TypeScript | Python | SQL | C#
backend     Node.js | Spring Boot | FastAPI | REST | event-driven
cloud       AWS Lambda | API Gateway | SQS | Kinesis | EMR | DynamoDB | S3
data        Spark | Iceberg | Kafka | PostgreSQL | Redis | Qdrant
ai          Llama | LoRA | RAG | PyTorch | Hugging Face | DeepSeek Harness
frontend    React | command UIs | tracking dashboards
```

MS Computer Science at Georgia State (2025-2027). Open to **full-time SDE / full-stack AI** roles.

[Schedule a conversation](https://calendly.com/ranjitdontineni9/30min) | [ranjitdontineni9@gmail.com](mailto:ranjitdontineni9@gmail.com) | [ranjitd.com](https://ranjitd.com)
