# Manik Singh Dhanjal

**Senior Software Engineer | Technical Manager**

📧 manikdhanjal217@gmail.com | 📱 +91 7060137665 | 🔗 [LinkedIn](https://linkedin.com/in/manik-s-d/) | 🌐 [manikdhanjal.com](https://manikdhanjal.com)

---

## Professional Summary

Senior Software Engineer with **5+ years** of experience designing and operating mission-critical distributed systems at scale. Deep expertise in building observability platforms, reliability tooling, and high-throughput data pipelines — reducing incident resolution from weeks to hours. Production experience shipping AI-powered automation and LLM-based agents that drive operational efficiency. Proven track record of delivering **99.99% uptime** on revenue-critical services through circuit breakers, fault isolation, and proactive SLA management. Passionate about embedding reliability culture across engineering teams and leveraging AI/ML to build self-healing, observable systems.

---

## Technical Skills

**Languages:** Java, Kotlin, JavaScript/TypeScript, Python, Go, C/C++

**Backend & Frameworks:** NestJS, Node.js, Express.js, Spring Boot, FastAPI, Kafka, gRPC

**Observability & Reliability:** New Relic, OpenTelemetry, Datadog, Prometheus, Grafana, Distributed Tracing, Structured Logging, Incident Management, SLA/SLO Management, Circuit Breakers, Chaos Engineering Principles

**AI / ML:** LLM Fine-tuning, RAG Systems, AI Agents, MCP Protocol, LangChain, Vector Databases, PyTorch, Scikit-learn

**Databases:** MongoDB Atlas (Tiered Storage, Vector Search), MySQL, PostgreSQL, Redis, Neo4j

**Cloud & Infrastructure:** AWS, Azure (API Gateway, VMs, Load Balancer), Docker, Kubernetes, Terraform, Portainer, Docker Swarm, Nginx, Traefik

**Developer Tools:** Git, Bitbucket Pipelines, Jest, Postman, Flywheel (DB migrations), Slack

---

## Work Experience

### Technical Manager — Telematics Platform
**Escorts Kubota Limited** | Faridabad, India (Remote) | Oct 2025 – Present

- Led observability uplift of Kubota's IoT telematics platform by integrating New Relic APM across gRPC and REST services, enabling real-time visibility into service health, latency distributions, and error rates across EU and US regions
- Designed and shipped gRPC streaming endpoints for real-time vehicle telemetry data, improving communication efficiency between microservices. Added structured JSON logging with correlation IDs to enable end-to-end trace correlation across distributed services
- Drove reliability improvements to the myKubota and Autosteer subscription platform by implementing Stripe webhook retry handling, idempotency guards, and circuit breaker patterns — ensuring zero duplicate billing events under network failure conditions
- Implemented infrastructure-as-code using Terraform for Docker Swarm deployments on Azure VMs, reducing manual deployment errors and enabling reproducible environment provisioning across teams

### Full Stack Engineer — EV Charging Platform
**Ford Motor Company** | Bengaluru, India | Mar 2023 – Oct 2025

**Charging Console — Real-Time Observability & CDC Platform**
- Built Charging Console, a real-time Change Data Capture and event replay platform that reduced L3 support incident resolution time from **weeks to hours** by replacing manual log tracing with a visual timeline dashboard. Eliminated dependence on Datadog for internal observability, cutting observability infrastructure costs significantly
- Designed and operationalised a Kafka-based observability pipeline ingesting **100M+ monthly events** from multiple sources with horizontally scalable consumer microservices. Implemented fine-tuned batch consumption and bulk insert strategies, improving write performance by **5×** and reducing database contention
- Engineered a hot–warm–cold tiered storage architecture in MongoDB Atlas — active events in standard collections, indexed time-series for warm data, and automatic archival to AWS S3 via Atlas Online Archive for cold data — boosting read query performance by **35%**, CUD performance by **80%**, and reducing storage and infrastructure costs by **15%**
- Built Datadog dashboards for live tracking of Kafka consumer lag, event processing error rates, and end-to-end pipeline throughput, enabling proactive alerting and rapid RCA during incidents
- Leveraged Kafka + WebSocket pipeline to stream live system state updates to users with sub-30s latency, supporting incident response workflows with real-time operational visibility

**Platform Reliability & Infrastructure**
- Designed and implemented an advanced circuit breaker strategy across mission-critical EV charging microservices, improving system fault tolerance and ensuring **99.99% uptime** for revenue-critical services under peak load and downstream failures
- Architected migration from HTTPS ingestion pipelines to Apache Kafka, achieving **6× higher throughput**, race-condition-free parallel processing, and improved horizontal scalability — enabling the platform to handle order-of-magnitude traffic growth without re-architecture
- Designed a highly available OAuth 2.0 authentication framework with Redis caching and exponential back-off, reducing authentication response times by **30%** and cutting downtime by **50%** during upstream identity provider degradation
- Optimised database query performance for energy dispensed reports, reducing DB cluster CPU utilisation by **25%** and server costs by **20%** while improving real-time analytics responsiveness for business decision-making
- Led re-architecture of the Charger Microservice from Go to NestJS, reducing feature development time by **35%** and enabling faster iteration on reliability improvements and new charging protocol support

**AI-Powered Operational Tooling**
- Developed a production RAG-based AI chatbot integrating LLMs with a vector database and company documentation as a knowledge base, delivering accurate context-aware support for EV fleet charging platform users. Reduced Tier-1 support query volume by enabling self-service answers to operational questions
- Drove Ford Pro Charging integration with Geotab by implementing a custom Kong plugin for SSO in Go, improving customer retention and reducing authentication-related support incidents by introducing centralised identity management

### Software Developer
**2626 Creative Studio Pvt. Ltd.** | New Delhi, India | Dec 2020 – Jul 2022

- Led development of mission-critical web applications and games for the Indian government, serving **10,000+ monthly active users** with high availability requirements
- Designed and built a React Native inventory and sales management system, increasing client revenue by **18%** through real-time data insights and automated reporting
- Automated data entry workflows using Puppeteer and Node.js, saving **40+ hours** of monthly maintenance time and eliminating error-prone manual processes
- Mentored junior developers, establishing best practices in scalable system design, testing, and performance optimisation

### Web Developer Intern
**Netart** | Coimbatore, India | Jun 2020 – Nov 2020

- Built static blogging sites using GatsbyJS and GraphQL, reducing page load time by **43%** versus the previous server-rendered CMS setup
- Implemented asynchronous add-to-cart feature for Chaayos Bazaar, increasing click-through rate by **22%** through improved UX responsiveness

---

## Key Projects

### Charging Console: Real-Time Observability & CDC System
**NestJS, Kafka, MongoDB Atlas, Redis, React, Socket.IO, Docker, Kubernetes**

Designed a CDC platform replaying and visualising historical database states in real time via scrollable timeline widgets, pie charts, node graphs, and bar charts — replacing manual log tracing for L3 engineering teams.

- Implemented checkpointing every 10K events to maintain consistent state recreation within 200ms across 500M+ event histories
- Hot-warm-cold MongoDB tiered storage with AWS S3 archival achieved 80% CUD performance gain and 35% read performance improvement

### Poshan Gyan: Government Nutrition Repository
**Node.js, AWS EC2, S3, Nginx, PM2**

Built India's first nutritional multimedia repository for pregnant women and children, achieving **2,400+ active users** and **5,000+ content downloads** within the first month of launch.

- Deployed with high availability on AWS EC2 behind Nginx for SSL termination and routing, with AWS S3 for scalable media storage

### Skynet Neural Engine
**Python, PyTorch, NumPy, Pandas**

Built a modular neural network engine from scratch with backpropagation via Reverse Mode Automatic Differentiation, benchmarked on MNIST handwritten digit recognition.

---

## Achievements

- **Ranked 4th** on GeeksForGeeks for problem solving at institute level
- **5 stars** on HackerRank for problem solving in Java
- **Solved 300+** coding problems on GFG and LeetCode combined
- **Secured 2nd position** in science fair for building a line-following robot

---

## Education

**B.Tech in Computer Science & Engineering**  
United College of Engineering & Research, Greater Noida, U.P.  
**CGPA: 8.2 / 10**

---

## Recent Profile Update

This resume complements the comprehensive GitHub profile at [github.com/manik-dhanjal](https://github.com/manik-dhanjal), which showcases:

- **Tech Stack Badges** — 45+ modern technologies organized by category
- **Featured Projects** — Detailed achievements from Charging Console, Poshan Gyan, and Skynet
- **GitHub Stats** — Real-time contribution metrics and language breakdown
- **Live Profile Views Counter** — Modern analytics tracking

For the most up-to-date information about my current work and open-source contributions, visit the main GitHub profile.

---

**Last Updated:** May 2026
