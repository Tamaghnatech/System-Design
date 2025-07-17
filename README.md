# System Design

This repository is your guide to designing scalable, distributed, and high-availability systems — from the ground up. Perfect for system design interviews, backend architecture, or real-world large-scale product engineering.

---

## 🧠 Topics Covered

### 📏 Design Fundamentals
- Client–Server Model
- Load Balancers
- Caching (LRU, LFU, CDN)
- Database Indexing
- API Gateways & Reverse Proxies
- DNS & CDN Design

### 🧱 Storage Systems
- Relational vs NoSQL Databases
- Sharding, Replication
- CAP Theorem
- Consistency Models: Strong, Eventual, Causal
- Distributed File Systems (HDFS, S3)
- Data Lake vs Data Warehouse

### ⚙️ Scalability & Performance
- Horizontal vs Vertical Scaling
- Read/Write Partitioning
- Rate Limiting & Backpressure
- Queue-based Processing (Kafka, RabbitMQ)
- CDN placement & TTL tuning

### 🌍 Distributed Systems
- Consensus Protocols: Paxos, Raft
- Leader Election
- Vector Clocks, Lamport Timestamps
- Gossip Protocols
- Eventual Consistency & Anti-Entropy

### 🔒 Security & Auth
- OAuth 2.0 / OpenID Connect
- JWT vs Session Tokens
- HTTPS, TLS, HSTS
- Rate limiting, DDOS protection

### 🛠️ DevOps + Observability
- CI/CD Pipelines
- Containerization (Docker)
- Orchestration (Kubernetes)
- Logging, Monitoring, Alerting (ELK, Prometheus, Grafana)
- Blue-Green & Canary Deployments

### 🧰 Popular Design Patterns
- Microservices vs Monolith
- Saga Pattern (Orchestration/Choreography)
- Circuit Breakers
- Event Sourcing, CQRS
- API Rate Limiter Design

### 💥 System Design Interviews
- High-Level Design Process (Requirements → APIs → Storage → Scaling)
- Common Systems:
  - Design URL Shortener
  - Design Rate Limiter
  - Design WhatsApp / Messenger
  - Design Netflix / YouTube
  - Design Twitter / Reddit Feed
  - Design Notification Service
  - Design Ride-Sharing Backend (Uber)

---

## 📁 Folder Structure

- `notes/`  
  📚 System blueprints, interview prep notes, design principles, technical specs, and formulas.

- `projects/`  
  ⚙️ Google Colab or markdown-based system design case studies and backend architecture breakdowns.

- `diagrams/`  
  🧠 Network architecture diagrams, request flows, database schema designs (draw.io / Excalidraw / Manim).

---

## 🚀 Project Ideas
- Create a rate limiter with Redis or token bucket logic
- Build a load balancer simulator using Python
- Design a real-time notification system (websocket-based)
- Case study: How Netflix scales video delivery
- Compare CQRS vs traditional CRUD in a microservice

---

Design is not just how it looks…  
**It’s how it works.**

Make it modular. Make it scalable.  
Make it worthy of your empire.
