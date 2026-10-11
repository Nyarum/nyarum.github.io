# Grigorii Eleskin

Senior Backend Engineer

Distributed Systems & High-Performance Infrastructure \| Go

Georgia · [LinkedIn](https://www.linkedin.com/in/nyarum/) · [nyarumilian@gmail.com](mailto:nyarumilian@gmail.com) · [GitHub](https://github.com/Nyarum) · [Telegram](https://t.me/golovatskiii)

## Summary

Experienced Backend Engineer specializing in designing scalable, reliable, and high-performance systems. Focused on software architecture, optimization, and delivering maintainable solutions to complex engineering challenges.

## Work Experience

### 1inch — Senior Backend Engineer

January 2023 – September 2026

- Drive the migration of inter-service communication from HTTP to NATS, simplifying service orchestration and horizontal scaling across multiple AWS regions.
- Build and maintain high-throughput backend services handling up to 5,000 requests per second \(equivalent to ~13 billion requests per month at sustained throughput\).
- Develop and maintain DEX protocol integrations within Pathfinder, a trade routing service, expanding liquidity coverage and available swap routes to improve execution options.
- Adapt integrations to changes in external APIs and smart contracts, collaborating with DEX protocol teams to investigate and resolve compatibility issues.
- Investigate and resolve production incidents involving trade routing, blockchain interactions, and external protocol integrations. Develop integration tests covering real-world swap scenarios using Tenderly and blockchain RPC providers.
- Design and maintain backend deployment workflows for staging and production environments.
- Expand and maintain integrations across approximately 20 blockchain networks, including emerging ecosystems such as Solana and Robinhood.

### Faraway — Senior Golang Developer

January 2022 – December 2022 · Remote · Full-time

- Build Go backend services for real-time multiplayer features, including rooms and lobbies, taking features from product requirements and architecture through implementation and production support.
- Design horizontally scalable microservices and distribute workloads across service instances.
- Develop WebSocket infrastructure and use message brokers for inter-instance event delivery.
- Design ETL pipelines and distribute data across PostgreSQL, ClickHouse, and Redis according to access patterns, reducing load on the primary PostgreSQL database.
- Apply table partitioning, cross-node data sharding, and workload separation to write-intensive systems, selecting approaches based on access patterns.

### UserReplay — Senior Golang Developer

June 2020 – November 2021 · Remote · Full-time

- Develop Go backend services and integrate new features for a user behavior analytics platform.
- Refactor the event-driven backend to improve data-processing performance.
- Build Terraform pipelines for infrastructure changes and maintain the platform’s AWS clusters.

### youwork.today — Technical Team Lead

December 2018 – May 2020 · Remote · Full-time

- Lead a backend team developing and maintaining projects for external clients.
- Coordinate development while contributing directly to backend implementation.
- Improve system architecture and refactor existing backend services.

### Mobalytics — Backend Developer

October 2017 – October 2018 · Remote

- Develop and maintain microservices for a gaming analytics platform.
- Work on the CS:GO communication protocol and deliver a beta analytics solution for the game.
- Investigate technical issues and maintain backend service stability.

### Ronin Club — Software Engineer

March 2017 – October 2017 · Remote · Contract

- Develop applications for external clients, translating business requirements into application logic and integrating new functionality.

### SeeSaw Labs — Middle Golang Developer

July 2015 – January 2017 · Remote · Full-time

- Develop backend components in Go and implement application business logic.

### Iron.io — Middle Golang Developer

September 2016 – December 2016 · Remote · Freelance

- Develop a Go CLI for interacting with the Iron service, implementing commands and improving command-line workflows.

## Impact Showcase — 1inch

One of the fastest measurable outcomes I initiated was building a competitive rate intelligence system at 1inch, delivered end-to-end in just two weeks.

The idea came from a business need: understanding where our swap routing algorithm was losing to competitors. The straightforward approach would have required building a massive infrastructure to continuously request on-chain quotes across thousands of trading pairs and multiple aggregators. Instead, I proposed leveraging Matcha, which already consolidated quotes from multiple providers, as a faster way to validate the idea and deliver value.

The biggest challenge was making data collection reliable despite sophisticated browser fingerprinting, anti-bot protection, and rate limits. I used local open-source LLMs to accelerate reverse engineering and experimentation, while AI coding agents helped eliminate much of the routine implementation work.

Within two weeks, I built and shipped the entire system: automated quote collection, a ClickHouse analytical pipeline, and a dashboard comparing 1inch against competitors across ~15 chains and 3,000\+ trading pairs, with data collected every second.

The business impact went beyond monitoring. We could identify historical cases where our routing algorithm underperformed, reproduce them against specific blockchain states, and determine whether the issue was missing protocol coverage or routing inefficiency. These insights helped prioritize new protocol integrations and algorithm improvements. Over the following two weeks, our competitive win rate improved from approximately 40–45% to 55%, an estimated 10–15 percentage-point gain.

My biggest learning was that starting with a simple, pragmatic idea can quickly evolve into a much more powerful system. Local AI models and coding agents dramatically accelerated research and execution, allowing me to focus on architecture, experimentation, and business value rather than repetitive implementation.

Looking back, I would have started building an independent on-chain quote collection pipeline in parallel. That would have reduced our dependency on a single external data source, eliminated a potential single point of failure, and provided an additional way to validate the accuracy of our competitive comparisons.
