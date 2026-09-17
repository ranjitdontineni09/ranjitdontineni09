# Ranjit Dontineni

Full-stack engineer for **AWS, streaming data, and grounded agents**.
SDE Intern @ AWS Connect · SDE I @ Aditya Birla Capital · MS CS @ Georgia State · Atlanta.

**Open to full-time SDE roles in the US.**
[ranjitd.com](https://ranjitd.com) · [Command center](https://ranjitdontineni09.github.io/#/overview) · [LinkedIn](https://www.linkedin.com/in/ranjit-dontineni-767399216/) · [Email](mailto:ranjitdontineni9@gmail.com)

---

### Repos a recruiter can clone

| Project | What it proves | Open |
| --- | --- | --- |
| **Computer-use runtime** | Record-once / replay-many agents. Discovery uses an LLM; production replay does not. | [computer-use-runtime](https://github.com/ranjitdontineni09/computer-use-runtime) |
| **Kafka task mesh** | Java / Spring Boot workers, Kafka, PostgreSQL, tracking UI. `docker compose up`. | [distributed-task-processing](https://github.com/ranjitdontineni09/distributed-task-processing) |
| **Connect-style stream** | Event bus ? microbatches ? partitioned tables. Freshness from a daily batch to minutes. | [connect-stream](https://github.com/ranjitdontineni09/connect-stream) |
| **Grounded Q&A** | FastAPI + RAG. Answers cite sources or refuse when retrieval is empty. | [grounded-qa-agent](https://github.com/ranjitdontineni09/grounded-qa-agent) |
| **Logistics APIs** | Java / Spring Boot services, API keys, orders and organizations. | [ranjit_fenixcommerce](https://github.com/ranjitdontineni09/ranjit_fenixcommerce) |

Interactive walkthrough of the same systems: **[command center](https://ranjitdontineni09.github.io/#/overview)**.

---

### Production signal

Shipped at Aditya Birla Capital and Amazon Connect. Internals stay in those orgs; the repos above are the public, runnable versions of the same patterns.

| Signal | Context | See |
| --- | --- | --- |
| **10M+** messages / day | WhatsApp / SMS / email on API Gateway + Lambda | [command center](https://ranjitdontineni09.github.io/#/systems/biztalk/lambda) |
| **27M** daily KYC / loan APIs | Submit-poll-webhook, 99.9% availability | [command center](https://ranjitdontineni09.github.io/#/systems/biztalk/lambda) |
| **2.8s ? 350ms** | DynamoDB read-through cache, Step Functions refresh | [command center](https://ranjitdontineni09.github.io/#/systems/biztalk/sfn) |
| **24h ? minutes** | Connect telemetry on Kinesis, Spark, Iceberg | [connect-stream](https://github.com/ranjitdontineni09/connect-stream) |

---

### Stack

```text
languages   Java | TypeScript | Python | SQL | C#
backend     Node.js | Spring Boot | FastAPI | REST | event-driven
cloud       AWS Lambda | API Gateway | SQS | Kinesis | EMR | DynamoDB | S3
data        Spark | Iceberg | Kafka | PostgreSQL | Redis | Qdrant
ai          Llama | LoRA | RAG | Playwright computer-use | Hugging Face
```

MS Computer Science, Georgia State (2025-2027). [Schedule 30 minutes](https://calendly.com/ranjitdontineni9/30min).
