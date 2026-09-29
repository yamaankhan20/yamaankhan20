<div align="center">

# Hey, I'm Yamaan Khan 👋

### Software Engineer • Distributed Systems • Backend Infrastructure

**Go & TypeScript Open Source Contributor**

Building backend systems that are fast, concurrent, observable, and reliable under real production traffic.

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Yamaan_Khan-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/yamaan-khan)
[![GitHub](https://img.shields.io/badge/GitHub-yamaankhan20-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/yamaankhan20)
[![Email](https://img.shields.io/badge/Email-Contact_Me-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:khanyamaan1@gmail.com)

</div>

---

## ⚡ About Me

I'm a **Software Engineer with 4+ years of experience** building backend infrastructure and distributed systems using **Go, Python, and TypeScript**.

My work is focused on systems where **performance, concurrency, reliability, and architecture matter** — API gateways, event-driven workers, distributed processing pipelines, caching layers, real-time data ingestion, and cloud infrastructure.

I enjoy working below the framework layer and understanding what is actually happening underneath the system.

```go
type Engineer struct {
    Focus     []string
    Languages []string
    Interests []string
}

me := Engineer{
    Focus: []string{
        "Distributed Systems",
        "Backend Infrastructure",
        "Performance Engineering",
        "Event-Driven Architecture",
    },

    Languages: []string{
        "Go",
        "TypeScript",
        "Python",
    },

    Interests: []string{
        "Open Source",
        "Concurrency",
        "Linux Internals",
        "Cloud Infrastructure",
    },
}
```

---

## 🧠 What I Work On

```text
Backend Engineering
├── High-throughput APIs
├── REST & gRPC services
├── API Gateways
├── Authentication & RBAC
├── Rate Limiting
└── Circuit Breakers

Distributed Systems
├── Kafka
├── Amazon SQS
├── Background Workers
├── Async Processing
├── Retry / DLQ Strategies
└── Graceful Shutdown

Performance
├── Go Concurrency
├── Goroutines & Channels
├── ErrGroups
├── Redis
├── Ristretto
├── Singleflight
└── pprof Profiling

Infrastructure
├── AWS
├── Docker
├── CI/CD
├── Prometheus
├── Grafana
└── Linux Internals
```

---

## 🚀 Engineering Highlights

### ⚡ High-Performance API Infrastructure

Built an internal **Go API Gateway** using:

`net/http` • `chi` • `JWT` • `HTTP/2` • `Rate Limiting` • `Circuit Breakers`

**Impact:**
- **35% lower average end-to-end latency**
- **Sub-40ms p99 gateway response times**
- Performance profiling and optimization using **pprof**

---

### 📈 Backend Performance Optimization

Migrated legacy backend workloads to concurrent Go services.

**Impact:**
- **150% increase in API throughput**
- **60% reduction in multi-file upload latency**
- **30% reduction in average API response time**
- Structured export pipelines processing **50,000+ records**

---

### 🎙 Real-Time Audio Processing

Designed and improved real-time audio ingestion for concurrent call workloads.

Instead of publishing every audio chunk independently, the system aggregates chunks in memory and emits one structured payload per completed call.

```text
Audio Stream
     ↓
In-Memory Aggregation
     ↓
Structured Payload
     ↓
Processing Pipeline
```

This reduced unnecessary messaging overhead while supporting multiple concurrent calls.

---

### ⚙️ Event-Driven Architecture

Built asynchronous processing systems using **Kafka** and **Amazon SQS**.

```text
API / Gateway
      │
      ▼
 Kafka / SQS
      │
 ┌────┼────┐
 ▼    ▼    ▼
Worker Worker Worker
      │
      ▼
PostgreSQL / Redis / MongoDB
```

Implemented:
- Retry strategies
- Dead-letter queues
- Graceful worker shutdown
- `context.Context` propagation
- Background processing
- Grafana monitoring
- Rolling deployment workflows

---

### 🧩 Multi-Service Processing Platform

Worked on a multi-service Go processing platform handling voice, transcript, and embedding workflows.

Key areas included:
- Coordinated shutdown hooks
- Context propagation
- Explicit service contracts
- OpenAPI specifications
- Release and acceptance criteria
- Reliable background processing

---

### 🐳 Systems Programming

I also enjoy going below the application layer.

I've built Go-based systems using:
- Linux namespaces
- cgroups
- raw syscalls
- process isolation
- container runtime concepts
- container orchestration concepts

Understanding infrastructure is much easier when you've built parts of it yourself.

---

## 🛠 Tech Stack

<div align="center">

### Languages

<img src="https://skillicons.dev/icons?i=go,ts,python,rust" />

### Backend & Databases

<img src="https://skillicons.dev/icons?i=postgres,redis,mongodb,nodejs" />

### Cloud & Infrastructure

<img src="https://skillicons.dev/icons?i=aws,docker,githubactions,linux" />

### Tooling

<img src="https://skillicons.dev/icons?i=git,github,vscode" />

</div>

---

## 🔧 Technologies I Use

![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![gRPC](https://img.shields.io/badge/gRPC-244C5A?style=flat-square)
![Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=flat-square&logo=apachekafka)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)

---

## 🌍 Open Source

I contribute across the **Go and TypeScript ecosystems** and enjoy working on software around:

- Backend infrastructure
- Developer tooling
- Distributed systems
- APIs
- Performance
- Cloud-native software

> Good software should not only work — it should be understandable, observable, and resilient.

---

## 📊 GitHub Analytics

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=yamaankhan20&show_icons=true&hide_border=true&count_private=true" />

<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=yamaankhan20&layout=compact&hide_border=true" />

</div>

<br/>

<div align="center">

<img src="https://streak-stats.demolab.com?user=yamaankhan20&hide_border=true" />

</div>

---

## 🎯 Currently Focused On

- Distributed systems engineering
- High-performance Go services
- Open-source contributions
- gRPC and streaming architectures
- Cloud-native backend infrastructure
- Performance profiling and optimization
- Reliable event-driven systems

---

## 🤝 Let's Connect

I'm interested in engineering problems involving **Go, backend infrastructure, distributed systems, developer platforms, and performance-sensitive systems**.

If you're building something technically challenging, I'd be happy to connect.

<div align="center">

### [LinkedIn](https://www.linkedin.com/in/yamaan-khan) • [GitHub](https://github.com/yamaankhan20) • [Email](mailto:khanyamaan1@gmail.com)

<br/>

**Build systems that don't just work — build systems that keep working.**

</div>
