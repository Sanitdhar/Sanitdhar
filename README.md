<!-- Profile README for github.com/Sanitdhar — lives in the repo Sanitdhar/Sanitdhar -->

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0B1F3A,100:2346D4&height=190&section=header&text=Sanit%20Dhar&fontSize=52&fontColor=ffffff&fontAlignY=36&desc=Distributed%20Systems%20%C2%B7%20Workflow%20Orchestration%20%C2%B7%20Agentic%20Platforms&descAlignY=58&descSize=16" alt="Sanit Dhar" />
</p>

<p align="center">
  <a href="https://github.com/Sanitdhar">
    <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&pause=1200&color=2346D4&center=true&vCenter=true&width=760&lines=Engineering+%40+Target;Durable+Temporal+workflows+%E2%86%92+10M+items%2Fday;35+systems%2C+one+item+orchestrator;Google+ADK+%C2%B7+A2A+%C2%B7+PostgreSQL+%2B+Citus+%C2%B7+Cassandra;Shipping+0+%E2%86%92+1+platforms+since+2017" alt="Typing intro" />
  </a>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/sanit-dhar-04a341139"><img src="https://img.shields.io/badge/LinkedIn-Sanit%20Dhar-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:sanitdhar25@gmail.com"><img src="https://img.shields.io/badge/Email-sanitdhar25%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://sanitdhar.github.io/Sanitdhar/"><img src="https://img.shields.io/badge/Portfolio-sanitdhar.github.io%2FSanitdhar-111827?style=for-the-badge&logo=githubpages&logoColor=white" alt="Portfolio" /></a>
  <img src="https://img.shields.io/badge/Bangalore-India-2346D4?style=for-the-badge&logo=googlemaps&logoColor=white" alt="Bangalore, India" />
</p>

---

## `$ whoami`

```yaml
name:        Sanit Dhar
role:        Software Engineer @ Target
experience:  9+ years — Target · Falabella · Lowe's · Mphasis
focus:
  - durable workflow orchestration (Temporal)
  - high-throughput ingestion & event-driven microservices
  - distributed data (PostgreSQL + Citus, Cassandra)
  - multi-agent systems (Google ADK, A2A) and LLMs with human-in-the-loop
patterns:    [Saga, CQRS, Event Sourcing, Pub/Sub, BFF]
currently:   scaling Temporal from 5M → 10M workflows/day
ask_me_about: [Temporal internals, sharding Postgres, agent orchestration, spec-driven dev]
```

## 📈 By the numbers

| | | | |
|:---:|:---:|:---:|:---:|
| **10M** items/day<br/><sub>UIO design target</sub> | **35** systems<br/><sub>orchestrated per item</sub> | **200+** stores<br/><sub>on my data plane & BFFs</sub> | **~30%** latency cut<br/><sub>Go promotion engine</sub> |
| **100%** traffic<br/><sub>migrated off a decade-old monolith</sub> | **0%** data loss<br/><sub>store data pipeline</sub> | **~50%** faster<br/><sub>event-driven order creation</sub> | **2M+** req/day<br/><sub>no extra infra cost</sub> |

---

## 🏗️ What I'm building

### 1 · Unified Item Orchestrator (UIO)

The single ingestion route for Target vendors and partners to bring catalog items to sale. Every item runs as a durable, long-running **Temporal** workflow that drives **35 systems** from submission to sellable.

<p align="center"><img src="diagrams/temporal-item-workflow.svg" alt="Temporal item workflow architecture" /></p>

- Saga-style compensation for partial failures; idempotent activities; workflow state survives worker restarts and downstream outages.
- **Core Data Service** on horizontally sharded **PostgreSQL + Citus** as the platform's system of record.

### 2 · Scaling Temporal: 5M → 10M workflows/day

Moving Temporal's persistence off a single PostgreSQL store onto horizontally sharded **Cassandra**.

<p align="center"><img src="diagrams/temporal-scaling.svg" alt="Temporal persistence scaling: single PostgreSQL to sharded Cassandra" /></p>

### 3 · Item Agent Orchestrator

A multi-agent platform on **Google ADK**. Agents talk over **A2A**, a **decision-model classifier** routes each request, and the UIO Temporal platform runs the long-running agent tasks.

<p align="center"><img src="diagrams/item-agent-orchestrator.svg" alt="Item Agent Orchestrator architecture" /></p>

### 4 · LLM attribute enrichment with human-in-the-loop

LLMs derive and enrich item attributes. The taxonomy platform controls which attributes AI may derive, and taxonomists review AI recommendations to close the loop.

<p align="center"><img src="diagrams/llm-enrichment-hitl.svg" alt="LLM attribute enrichment with human-in-the-loop" /></p>

### 5 · AI-driven development harness

A harness for my team that sets **team-wide context** for coding agents (Claude Code, OpenCode) through reusable **skills** and skill config, run as **spec-driven development**: spec first, agents implement against it.

---

## 🧰 Tech stack

<p align="center">
  <img height="64" src="https://skillicons.dev/icons?i=java,go,kotlin,py,js,spring,nodejs&perline=7" alt="Languages and frameworks" /><br/>
  <img height="64" src="https://skillicons.dev/icons?i=postgres,cassandra,mongodb,redis,elasticsearch,kafka,graphql&perline=7" alt="Data and messaging" /><br/>
  <img height="64" src="https://skillicons.dev/icons?i=gcp,kubernetes,docker,terraform,gitlab,githubactions,jenkins,grafana,prometheus&perline=9" alt="Cloud, infra and observability" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Temporal-000000?style=flat-square&logo=temporal&logoColor=white" />
  <img src="https://img.shields.io/badge/Citus-2346D4?style=flat-square&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Google%20ADK-4285F4?style=flat-square&logo=google&logoColor=white" />
  <img src="https://img.shields.io/badge/A2A%20Protocol-0B1F3A?style=flat-square" />
  <img src="https://img.shields.io/badge/gRPC-244c5a?style=flat-square&logo=grpc&logoColor=white" />
  <img src="https://img.shields.io/badge/Pub%2FSub-4285F4?style=flat-square&logo=googlecloud&logoColor=white" />
  <img src="https://img.shields.io/badge/Couchbase-EA2328?style=flat-square&logo=couchbase&logoColor=white" />
  <img src="https://img.shields.io/badge/BigQuery-669DF6?style=flat-square&logo=googlebigquery&logoColor=white" />
  <img src="https://img.shields.io/badge/ArgoCD-EF7B4D?style=flat-square&logo=argo&logoColor=white" />
  <img src="https://img.shields.io/badge/Spinnaker-139BB4?style=flat-square&logo=spinnaker&logoColor=white" />
  <img src="https://img.shields.io/badge/Datadog-632CA6?style=flat-square&logo=datadog&logoColor=white" />
  <img src="https://img.shields.io/badge/Loki-F46800?style=flat-square&logo=grafana&logoColor=white" />
  <img src="https://img.shields.io/badge/OpenTelemetry-425CC7?style=flat-square&logo=opentelemetry&logoColor=white" />
  <img src="https://img.shields.io/badge/Claude%20Code-D97757?style=flat-square&logo=anthropic&logoColor=white" />
</p>

---

## 🛤️ Career path

| When | Where | What I built |
|---|---|---|
| 2024 → now | **Target** · Software Engineer | Unified Item Orchestrator (Temporal, 35 systems, 10M/day), Item Agent Orchestrator (ADK + A2A), Citus core data service, LLM attribute enrichment, item taxonomy rewrite |
| 2021 → 2024 | **Falabella** · Senior SWE | Go promotion engine (−30% latency, −10% memory), store data plane to 200+ stores with zero data loss, event-driven order confirmation & store BFFs |
| 2019 → 2021 | **Lowe's** · SWE | Enterprise Cart & Checkout; migrated 100% of traffic off a decade-old system (Spring WebFlux, Couchbase, Kafka) |
| 2017 → 2019 | **Mphasis** · SWE | NEXTSTEP: platform hosting 40 microservices, plus a liveness-monitoring service |

---

## 📊 GitHub activity

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=Sanitdhar&show_icons=true&hide_border=true&include_all_commits=true&theme=tokyonight" alt="GitHub stats" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Sanitdhar&layout=compact&hide_border=true&theme=tokyonight" alt="Top languages" />
</p>
<p align="center">
  <img src="https://streak-stats.demolab.com?user=Sanitdhar&hide_border=true&theme=tokyonight" alt="Contribution streak" />
</p>

---

<p align="center">
  <sub>Built with durable workflows, sharded tables and a lot of retries. Say hi on <a href="https://www.linkedin.com/in/sanit-dhar-04a341139">LinkedIn</a>.</sub>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:2346D4,100:0B1F3A&height=100&section=footer" alt="" />
</p>
