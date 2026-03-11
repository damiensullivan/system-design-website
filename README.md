We will be building a website which captures the following as a means to demonstrate our knowledge of the following topics.  
For each topic we will provide:  

- **A definition** and explanation of the concept, what it is and how it works  
- **An real world analogy** that makes the concept easier to understand  
- **The benefits, drawbacks and trade-offs** to be aware of when using this technology  
- **Why it is important or useful in practice**

# 1. Core System Design Principles
- Scalability
- Availability
- Reliability
- Latency vs Throughput vs Bandwidth
- Horizontal vs Vertical Scaling
- Autoscaling
- Tail Latency
- Backpressure
- Graceful Degradation
- Load Shedding
- Single Point of Failure
- High Availability vs Fault Tolerance
- Network Partitions
- Split-Brain Problem
- CAP Theorem
- PACELC Theorem

---

# 2. Architecture Patterns
- Client-Server Architecture
- Monolithic Architecture
- Microservices Architecture
- Serverless Architecture
- Event-Driven Architecture
- Layered Architecture
- Hexagonal Architecture (Ports and Adapters)
- Clean Architecture
- Domain Driven Design (DDD)
- Backend for Frontend
- Sidecar Pattern
- Service Mesh
- Circuit Breaker Pattern
- Bulkhead Pattern
- Strangler Fig Pattern
- Anti-Corruption Layer

---

# 3. API & Communication
- API Design
- REST APIs
- GraphQL
- gRPC
- API Versioning
- Pagination (Offset vs Cursor)
- Idempotency
- Idempotency Keys
- HATEOAS
- OpenAPI / Swagger
- Synchronous vs Asynchronous Communication
- WebSockets
- Long Polling
- Server-Sent Events
- Webhooks
- WebRTC
- API Gateways

---

# 4. Networking Fundamentals
- OSI Model
- TCP vs UDP
- HTTP vs HTTPS
- TLS/SSL
- DNS
- DNS Load Balancing
- Anycast Routing
- Proxy vs Reverse Proxy
- NAT (Network Address Translation)
- CIDR
- Subnetting
- MTU / Packet Fragmentation
- BGP (Border Gateway Protocol)

---

# 5. Load Distribution & Traffic Management
- Load Balancing
- Load Balancing Algorithms
- Rate Limiting
- CDN
- Traffic Shaping
- Blue/Green Deployment
- Canary Deployment
- Feature Flags

---

# 6. Caching Systems
- Caching
- Distributed Cache
- Cache Invalidation
- Cache Eviction Policies
- Cache Stampede
- Cache Warming
- Write-through Cache
- Write-back Cache
- Write-around Cache
- Read-through Cache
- Hot Key Problem

---

# 7. Databases & Storage
- Databases
- SQL vs NoSQL
- ACID vs BASE
- OLTP vs OLAP
- Data Warehouse
- Data Lake
- Columnar Databases
- NewSQL Databases
- Object Storage
- Distributed File Systems
- Block vs File vs Object Storage
- Time Series Database
- Vector Database
- Full-Text Search Engine

---

# 8. Database Scaling & Data Distribution
- Data Replication
- Read Replicas
- Sharding
- Data Partitioning
- Consistent Hashing
- Rebalancing Shards
- Denormalization
- Materialized Views
- Indexing
- Secondary Indexes
- Composite Indexes
- Covering Indexes
- Query Optimization
- Connection Pooling
- Hot Partition Problem

---

# 9. Data Structures Used in Systems
- B-trees and B+ trees
- LSM Tree
- Bloom Filter
- Merkle Tree
- HyperLogLog

---

# 10. Distributed Systems Coordination
- Heartbeats
- Leader Election
- Consensus Algorithms
- Quorum
- Paxos Algorithm
- Raft Algorithm
- Gossip Protocol
- ZooKeeper
- etcd
- Distributed Locks
- Lease Mechanisms

---

# 11. Time & Ordering in Distributed Systems
- Clock Synchronization Problem
- Logical Clocks
- Lamport Timestamps
- Vector Clocks

---

# 12. Distributed Data Consistency
- Consistency Models
- Strong Consistency
- Eventual Consistency
- Read Your Writes Consistency
- Monotonic Reads
- Write Skew
- Distributed Transactions
- Two-Phase Commit
- Three-Phase Commit
- SAGA Pattern
- SAGA Orchestration vs Choreography
- Outbox Pattern
- Delivery Semantics
- Change Data Capture
- CQRS
- Event Sourcing

---

# 13. Messaging & Event Streaming
- Message Queues
- Pub/Sub
- Dead Letter Queues
- Message Replay
- Event Log
- Exactly Once Processing
- Kafka

---

# 14. Data Processing Systems
- Batch vs Stream Processing
- ETL Pipelines
- MapReduce
- Stream Processing Frameworks
- Windowing (Tumbling / Sliding)
- Data Backfills

---

# 15. Observability & Monitoring
- Observability
- Logging
- Metrics
- Distributed Tracing
- Correlation IDs
- SLIs (Service Level Indicators)
- SLO (Service Level Objectives)
- SLA (Service Level Agreements)
- Alerting Systems
- Sampling in Tracing

---

# 16. Security & Identity
- Authentication vs Authorization
- Session-based vs Token-based Authentication
- OAuth / OAuth2 / OpenID Connect
- JWT
- Security Secrets Management
- Role-Based Access Control
- Single Sign-On
- API Keys
- HMAC Signatures
- mTLS
- Zero Trust Architecture
- Certificate Rotation

---

# 17. Data Integrity & Efficiency
- Checksums
- Data Compression
- Deduplication
- Data Versioning
- Snapshots
- Write Amplification
- Erasure Coding
