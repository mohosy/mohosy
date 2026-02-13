<p align="right">
  <img src="presentationpic.png" width="260" alt="Mo presentation photo" />
</p>

<h1 align="center">Mo Shirmohammadi</h1>
<p align="center"><strong>Software Engineer | Data Infrastructure | Distributed Systems | Applied ML</strong></p>
<p align="center">
  USC Viterbi (B.S./M.S. Computer Science, Spring 2029) · Building production-minded systems in Python/Java/TypeScript on AWS and cloud-native tooling.
</p>

<p align="center">
  <a href="mailto:mshirmoh@usc.edu"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://linkedin.com/in/mohossy"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
</p>

---

## Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### [SurgGraph Pipeline](https://github.com/mohosy/SurgGraph-Pipeline)
Graph-enhanced robotic surgery analytics pipeline prototype.

- Streaming telemetry pipeline (`Kafka -> Flink-style -> dbt/DuckDB -> API/Dashboard`)
- Procedure-graph intelligence with shortest-path optimization and bottleneck analysis
- Recovery-risk ML modeling with fairness disparity checks

`Python` `Kafka` `Airflow` `dbt` `DuckDB` `Docker` `Kubernetes` `AWS`

</td>
<td width="50%" valign="top">

### [Distributed Task Queue](https://github.com/mohosy/distributed-task-queue)
Production-grade distributed queue in pure Python.

- Priority scheduling, WAL persistence, checkpointing, and crash recovery
- Retry/backoff, dead-letter queue, deduplication, and circuit breaker
- DAG execution, cron scheduling, and P50/P95/P99 metrics

`Python` `Distributed Systems` `Reliability` `WAL` `Concurrency`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [Database Replication Engine](https://github.com/mohosy/database-replication-engine)
PostgreSQL-inspired replication system built from scratch.

- Leader-follower replication over a write-ahead log
- Automatic failover, leader election, and split-brain handling
- Sync/async/semi-sync replication tradeoff modes

`TypeScript` `Replication` `Consensus` `Fault Tolerance`

</td>
<td width="50%" valign="top">

### [KV Store Engine](https://github.com/mohosy/kv-store-engine)
Java key-value engine with a custom storage core.

- Open-addressing hash table (no built-in map)
- TTL-based eviction (lazy + active strategies)
- Snapshot persistence with atomic save/restore

`Java` `Spring Boot` `Data Structures` `Storage Engine`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [Load Balancer from Scratch](https://github.com/mohosy/load-balancer-from-scratch)
Java load balancer implementing production routing strategies.

- 6 algorithms (round-robin, weighted, least-connections, hashing, and more)
- Health checks and chaos-style failure simulation
- Concurrent traffic handling with throughput/latency metrics

`Java` `Networking` `Distributed Systems` `Concurrency`

</td>
<td width="50%" valign="top">

### [Container Runtime from Scratch](https://github.com/mohosy/container-runtime-from-scratch)
Docker/OCI-style runtime simulator in pure Python.

- PID/mount/network/UTS namespace isolation
- cgroup-style memory/CPU/PID resource controls
- Union filesystem with copy-on-write layers + Dockerfile parsing

`Python` `Linux` `Containers` `Systems Programming`

</td>
</tr>
</table>

---

## Additional Systems Projects

- [Raft Consensus Simulator](https://github.com/mohosy/raft-consensus-simulator): deterministic leader election and log replication with fault injection.
- [LSM-Tree Storage Engine](https://github.com/mohosy/lsm-tree-storage-engine): WAL, memtables, SSTables, compaction, and Bloom filters.
- [Postgres-backed Pub/Sub Queue](https://github.com/mohosy/postgres-backed-pubsub-queue): durable messaging with consumer-group offsets and ACID semantics.
- [SQL Database Engine](https://github.com/mohosy/sql-database-engine): parser, executor, indexing, persistence, and REPL from first principles.
- [Transformer LM from Scratch](https://github.com/mohosy/transformer-lm-from-scratch): GPT-style decoder with manual backprop and full test coverage.
- [HTTP Server from Scratch](https://github.com/mohosy/http-server-from-scratch): multithreaded HTTP/1.1 server over raw TCP sockets.

---

## Engineering Snapshot

- Founding engineer on an AI student-support chatbot used by 30,000+ students.
- Built and shipped systems across backend, data, ML, and infra layers.
- 1st Place at HTCC 2024 (AI Patrol Drone project).
- Featured in Forbes.

---

## Core Stack

**Languages:** Python, Java, TypeScript, C++, SQL  
**Backend:** Flask, Express, Spring Boot, Django  
**Data:** PostgreSQL, MongoDB, DuckDB, Redis  
**Infra:** AWS, Docker, Kubernetes, Linux, GitHub Actions

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,java,typescript,cpp,postgres,mongodb,redis,aws,docker,kubernetes,linux,git&theme=light&perline=12" alt="Tech stack" />
</p>
