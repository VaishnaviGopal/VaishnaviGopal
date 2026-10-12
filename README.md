## Hi, I'm Vaishnavi Gunishetty 👋

**Senior AI & Cloud Infrastructure Engineer**  
Architecting autonomous AI agent platforms, distributed cloud backbones, and mission-critical data systems at enterprise scale.

📍 Bengaluru, India · 💼 IBM Cloud · ✉️ [ggunishetty9work@gmail.com](mailto:ggunishetty9work@gmail.com) · 🔗 [LinkedIn](https://linkedin.com/in/vaishnavi-gunishetty)

---

### AI Systems & Autonomous Agent Architecture

- **Bob Loop Engineering — Autonomous AI Agent Platform**
  - *Sole Architect & Builder:* Designed and built an end-to-end autonomous agent platform that ingests GitHub issues, navigates codebases via an AST symbol graph (N-hop BFS traversal), synthesizes fixes, executes test suites in ephemeral sandboxed containers, and automatically raises verified Pull Requests in **under 2 minutes**.
  - *Security & Determinism:* Engineered a deterministic Policy Gate enforcing non-root container isolation, workspace boundary checks, HMAC request validation, and structured OKF audit trails for agent decision tracing.

- **NexusAI — Multi-Agent Cognitive Load & Focus Platform**
  - *Lead Engineer:* Architected a multi-agent orchestration platform on IBM watsonx.ai and Granite LLMs that ingests real-time streams (Slack, Outlook, ServiceNow, PagerDuty), computes real-time cognitive load states, and activates *Guardian Mode* to intelligently defer low-priority interrupts — recovering **30–60 minutes of uninterrupted focus time per developer daily**.

- **Bob Box — Centralized Autonomous Digital Worker**
  - *Designer & Builder:* Built a cloud-hosted team agent utilizing the **Model Context Protocol (MCP)** and sandboxed execution, enabling multi-file autonomous refactoring and CI test execution with an agentic feedback loop that prevents repeated build failures across shared repos.

- **Agentic Documentation & Workflow Assistant**
  - *Lead Engineer (Team of 5):* Built a multi-agent pipeline using **LangGraph, CrewAI, and watsonx** that monitors product milestones and GitHub PRs to autonomously author release notes and submit docs PRs — reducing documentation time by **70%** (InnerSource tool presented at IBM AI Guild & Sangam Open House).

- **GenAI Observability & Log Anomaly Detection**
  - Fine-tuned domain models with **InstructLab / Llama-3** to pinpoint exact root-cause failure lines in complex CI/CD logs, packaged as a production Go/Python microservice across 7 service repositories.

---

### ☁️ Cloud Platforms, Distributed Systems & Scale

- **★ Cloudant → PostgreSQL Production Live Migration (10M+ Documents)**
  - *Development Owner (TRI):* Architected and executed live zero-data-loss migration of **10M+ documents** across 11 entity types & 212 field mappings.
  - *High-Throughput Engine:* Engineered a 3-phase view-based Python engine with 16-worker multiprocessing, connection pooling, and batch writes — delivering an **18–36× throughput speedup** (200–500 docs/s; Stage in **~24 min**; Dev in **<5 min**).
  - *Production Resilience:* Built checkpoint-resume fault tolerance, Secrets Manager integration, and regex JSONB sanitization (reducing failure rate from 0.34% to 0%); executed CA-MON (**100% first-run success**) and CA-TOR production cutovers at **<$40 cost per region**.

- **Large-Scale Orphan Resource Cleanup Initiative**
  - Designed MapReduce analytics views and automated purge pipelines; analyzed **721,893 job documents** (isolated ~670K orphaned records), audited **209,190 activity documents** (purged 100K+ records), and resolved **3,436 standalone workspaces** prior to relational migration.

- **Enterprise Agent Platform & Release Engineering**
  - Engineered CLI tooling, Terraform provider resources, and Red Hat OpenShift / Calico CNI networking for IBMCloud Schematics Agents;

- **Platform Reliability & KPI Infrastructure Optimization**
  - Eliminated memory out-of-bound errors causing persistent KPI service pod crashes, fixed multi-region Redis replication drift, and slashed customer support backlog

- **High-Throughput RabbitMQ Quorum Queue Migration**
  - Led the migration of core messaging infrastructure from classic mirrored queues to Quorum Queues across all production regions with **zero data loss**.

---

### 🔧 Open Source & Cross-Repo Engineering

- **[terraform-provider-ibm](https://github.com/IBM-Cloud/terraform-provider-ibm)** — Official IBM Cloud Terraform Provider
  - Top contributor · Owned VPC infrastructure module (`ibm_is_vpc`, `ibm_is_instance`, `ibm_is_subnet`, `ibm_is_security_group`, `ibm_schematics_*`).
  - Expanded acceptance testing suites and authored provider documentation.
- **Cross-Repository Coordination:** Raised and coordinated PRs across **14 service repositories** for EU-GB environment deployment readiness.
- **[Google Terraformer](https://github.com/GoogleCloudPlatform/terraformer):** Contributed IBM Cloud VPC reverse-engineering support to open source.

---

### 🏆 Leadership, Hackathon Judging & Patents

- **Bob Hackathon Judge:** Official judge evaluating 10 innovative generative AI and agent submissions.
- **Mentorship:** Mentored junior engineers on GenAI/RAG patterns, microservice architecture, and distributed systems best practices.
- **3 Publications (IP.com):**
  - *Method and Process to Expose Intelligent Port as a Service*
  - *System and Method for Universal Device Health Rating Platform*
  - *Confidential Usage Proof Verifier for Cloud Metering*

---

### 🛠 Technical Arsenal

- **AI / Agentic Systems:** ReAct Loops, Model Context Protocol (MCP), LangGraph, CrewAI, LangChain, IBM watsonx.ai, Granite LLMs, InstructLab, RAG, Ollama
- **Languages & Core:** Go (Golang), Python, TypeScript, SQL, Bash/Shell, HCL, Node.js
- **Cloud & Infrastructure:** IBM Cloud VPC, Azure, AWS, GCP services, Red Hat OpenShift, Kubernetes, Docker, Terraform, Helm, Calico CNI
- **Databases & Messaging:** PostgreSQL (JSONB, Connection Pooling), IBM Cloudant (CouchDB), Redis, RabbitMQ (Quorum Queues), MySQL, COS object storage
- **DevOps & Observability:** Tekton CI/CD, Jenkins, Grafana, GitOps, FluentBit, OpenAPI/Swagger, IBM Secrets Manager, Azure Monitor, OpenTelemetry, Cloudwatch.
