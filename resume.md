# Grigorii Eleskin

Senior Backend Engineer

Go / Golang \| Distributed Systems \| Performance & Reliability

Georgia · [LinkedIn](https://www.linkedin.com/in/nyarum/) · [nyarumilian@gmail.com](mailto:nyarumilian@gmail.com) · [GitHub](https://github.com/Nyarum) · [Telegram](https://t.me/golovatskiii)

## Summary

Senior Backend Engineer with 10\+ years of experience building and operating production software, primarily in Go.

My experience spans blockchain infrastructure, real-time multiplayer gaming, and user behavior analytics. I build distributed backend systems, messaging and state-distribution infrastructure, WebSocket services, and data pipelines using technologies such as NATS, Redis, PostgreSQL, and ClickHouse.

I take ownership from business requirements through architecture, implementation, deployment, and production verification. This includes operating services with Kubernetes and Helm, investigating latency and resource bottlenecks, and using tracing and profiling to guide performance improvements.

At 1inch, my work covered distributed state management, blockchain RPC integrations, Solidity contracts, and production performance. At Faraway, I built backend systems for multiplayer features and worked on horizontally scalable real-time communication and data-intensive architectures.

I prefer the simplest architecture that meets the requirements, with explicit trade-offs around reliability, performance, and operational complexity. I also work with Rust and TypeScript.

## Work Experience

### 1inch — Senior Backend Engineer

January 2023 – September 2026

- Designed state distribution between services using NATS and Redis, addressing consistency, fault tolerance, and the risk of state loss across distributed components.
- Built integrations with multiple blockchain RPC providers, accounting for latency, failures, and provider-specific limitations.
- Developed, modified, and deployed Solidity smart contracts, including batching multiple operations to reduce individual on-chain requests.
- Identified and addressed latency, CPU, and memory bottlenecks using distributed tracing and profiling with Grafana, Tempo, and Pyroscope.
- Owned service delivery and production operation with Kubernetes and Helm, including deployment, configuration, scaling, observability, and performance analysis.

### Faraway — Senior Golang Developer

January 2022 – December 2022 · Remote · Full-time

- Designed and developed backend systems for real-time multiplayer game features, including rooms and lobbies, with a focus on reliability and horizontal scalability.
- Built scalable microservices capable of supporting growing player concurrency and distributing workload across multiple service instances.
- Designed ETL and data distribution pipelines to move workloads away from a single PostgreSQL database and route data into storage systems optimized for specific access patterns, including PostgreSQL, ClickHouse, and Redis.
- Designed data-intensive architectures for high write throughput, using table partitioning, sharding, and workload separation to keep databases performant as data volume and traffic increased.
- Built and scaled WebSocket infrastructure for large numbers of concurrent connections, using message brokers to distribute events and communication across multiple backend instances.
- Worked on the full lifecycle of backend features, from product requirements and architecture to implementation, scaling, deployment, and production reliability.

### UserReplay — Senior Golang Developer

June 2020 – November 2021 · Remote · Full-time

- Developed Go backend functionality for a user behavior analytics platform.
- Integrated new analytics features into the existing backend, extending the platform's functionality.
- Refactored the event-driven backend to improve processing performance.
- Implemented Terraform pipelines for infrastructure changes alongside application development.
- Maintained AWS clusters supporting the analytics platform and its backend services.

### youwork.today — Technical Team Lead

December 2018 – May 2020 · Remote · Full-time

- Led a backend team developing new features for third-party client projects.
- Organized development work using agile practices, coordinating feature delivery and support for existing functionality.
- Combined technical leadership with hands-on work on backend functionality for client applications. Improved the architecture of existing backend systems across multiple client projects.
- Refactored existing application functionality as part of ongoing backend development and maintenance.

### Mobalytics — Backend Developer

October 2017 – October 2018 · Remote

- Developed microservices for a game analytics platform, implementing backend functionality for its analytical features.
- Worked on the communication protocol used to interact with CS:GO as part of game-specific backend development.
- Introduced a beta solution for CS:GO analytics, extending the platform's game-specific functionality. Investigated technical issues in the analytics backend to help the team resolve problems.
- Supported backend service stability alongside microservice and CS:GO analytics development.

### Ronin Club — Software Engineer

March 2017 – October 2017 · Remote · Contract

- Developed software features for external clients, translating business requirements into working application functionality.
- Worked through client requirements at implementation level, connecting business needs with concrete application behavior.
- Implemented application logic around client-specific workflows and business rules.
- Integrated feature-level changes into client applications as part of outsourced development work.
- Refined feature implementations against business requirements to keep application behavior aligned with client needs.

### SeeSaw Labs — Middle Golang Developer

July 2015 – January 2017 · Remote · Full-time

- Developed backend functionality in Go, contributing to the application's server-side implementation. Implemented business logic that translated application requirements into concrete backend behavior.
- Worked on backend components responsible for applying business rules within application workflows.
- Connected business-logic implementation with the surrounding backend functionality as part of feature development.
- Refined backend code to keep application behavior aligned with business-logic requirements.

### Iron.io — Middle Golang Developer

September 2016 – December 2016 · Remote · Freelance

- Developed a Go command-line utility for the Iron service, providing a terminal-based interface to its functionality.
- Implemented command behavior for interacting with Iron, connecting CLI actions to the service's capabilities.
- Worked on the utility's user-facing command flow, focusing on straightforward interaction from the terminal.
- Improved CLI usability by refining how users accessed the utility's functionality.
- Refined command-line workflows to make routine interactions with the Iron service more efficient.

## Skills

### Languages

Go / Golang, Rust, Elixir, TypeScript, JavaScript, Dart, Zig

### Backend & Systems

Backend Development, Distributed Systems, Event-Driven Architecture, Microservices, CLI Development

### Cloud & Infrastructure

AWS, GCP, Kubernetes, Multi-cluster Kubernetes, Docker, Terraform

### Delivery & Automation

CI/CD, GitHub Actions, Infrastructure as Code

### Databases & Search

PostgreSQL, CockroachDB, MySQL, MongoDB, Elasticsearch

### Messaging

NATS, NATS JetStream, Kafka, RabbitMQ

### Observability

Prometheus, Grafana, Jaeger, Grafana Tempo, Grafana Loki

### Reverse Engineering

IDA Pro, OllyDbg, Wireshark, Protocol Reverse Engineering

### AI & Agent Engineering

Claude Code, Codex, OpenCode, Onepiece, Local Qwen Models, LLM Deployment, vLLM, SGLang, Model Quantization, Custom Harnesses

### Engineering Practices

Backend Team Leadership, Agile Development, Scrum

### API & Networking

REST, gRPC, WebSockets, HTTP, TCP/IP, Protobuf, Asynchronous RPC

### Go Engineering

Concurrency, Profiling, pprof, Continuous Profiling, Benchmarking, Memory Optimization

### Reliability

Incident Response, Root-Cause Analysis, SLO/SLI, On-call

### Testing

Unit, Integration, End-to-End, Load Testing, Fuzzing

### Security

OAuth 2.0, JWT, RBAC, Secrets Management

### Blockchain Backend

EVM, JSON-RPC, ABI, Smart-Contract Integration, Transaction Lifecycle

### Platform

Linux, Bash, Helm, Argo CD, GitOps

### Caching

Redis, Cache Invalidation, Distributed Caching

## LLM Serving & Custom Harnesses

- Knowledge of LLM deployment and serving with vLLM and SGLang.
- Knowledge of model quantization in the context of LLM deployment.
- Develop and use my own modular Onepiece harness for AI-assisted engineering workflows.
- Enable optional capabilities and extensions independently in Onepiece as needed.
- Hands-on experience with Claude Code, Codex and OpenCode.
- Prefer local Qwen models for privacy.
- Follow spec-driven workflows with a research-first approach.
- Verify work through live testing and evidence-based checks. Re-check previously validated work in a fresh context, independently of earlier conclusions.

## Certifications

- Scrum Developer Certificate

## Open Source & Interests

I’ve open-sourced three game versions through more than a decade of reverse-engineering MMORPG protocols.

Interests include Zig and Gleam, low-level systems, functional programming and fault-tolerant backends.
