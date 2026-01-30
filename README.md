<img src="https://komarev.com/ghpvc/?username=mohosy&style=flat-square&color=8B5CF6" alt="Profile Views" />

<img align="right" src="presentationpic.png" width="280" />

<img src="https://readme-typing-svg.demolab.com?font=Inter&weight=700&size=32&duration=1000&pause=10000&color=58A6FF&vCenter=true&repeat=false&width=300&height=45&lines=Hey%2C+I'm+Mo+%F0%9F%91%8B" alt="Hey, I'm Mo" />

**CS @ USC Viterbi** · B.S./M.S. · 3.92 GPA

I build systems that scale. At 19, I shipped an AI chatbot serving **30,000+ students** and got **featured in Forbes**. Currently building a social app with **470+ beta testers**.

<a href="https://readme-typing-svg.demolab.com/demo/">
  <img src="https://readme-typing-svg.demolab.com?font=Inter&weight=600&size=15&duration=3000&pause=1500&color=A78BFA&vCenter=true&width=350&lines=Forbes-Featured+Engineer;1st+Place+%40+HTCC+Honors+Conference;Founding+Engineer+%40+PCC+AI;Building+in+public+%E2%9C%A8" alt="Typing SVG" />
</a>

<br/>

[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:mshirmoh@usc.edu)&nbsp;
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/mohossy)

<br clear="right"/>

---

## Production

<table>
<tr>
<td width="50%">

**PCC AI Chatbot** · *Founding Engineer*

![Users](https://img.shields.io/badge/Users-30,000+-8B5CF6?style=flat-square)
![Queries](https://img.shields.io/badge/Daily_Queries-640+-06B6D4?style=flat-square)
![Uptime](https://img.shields.io/badge/Uptime-99.9%25-10B981?style=flat-square)

- RAG pipeline: 900+ docs indexed, sub-100ms retrieval
- Improved accuracy 38% → 66%, reduced hallucinations 40%
- Built agentic mode with Browserbase + Playwright

`Node.js` `Express` `MongoDB` `GPT-4` `RAG` `Sentry`

</td>
<td width="50%">

**IRL Social App** · *Founder & Solo Engineer*

![Beta](https://img.shields.io/badge/Beta_Testers-470+-8B5CF6?style=flat-square)
![Volume](https://img.shields.io/badge/Weekly_Clips-1,000+-06B6D4?style=flat-square)
![Retention](https://img.shields.io/badge/Week--1_Retention-35%25-10B981?style=flat-square)

- Real-time video social network with live presence and multiplayer games
- Hybrid WebSocket layer: Agora WebRTC + Socket.io (15+ event types)
- FFmpeg transcoding, S3 multipart uploads, CloudFront CDN delivery

`React Native` `TypeScript` `Node.js` `Socket.io` `Agora` `AWS`

</td>
</tr>
<tr>
<td width="50%">

**AI Patrol Drone** · *1st Place @ HTCC 2024*

![Award](https://img.shields.io/badge/HTCC-1st_Place-FFD700?style=flat-square)
![Type](https://img.shields.io/badge/Computer_Vision-Wildlife_Detection-06B6D4?style=flat-square)

- CV-based system to identify predatory wildlife and protect outdoor pets
- Real-time detection on embedded hardware
- Won against 50+ competing projects

`Python` `OpenCV` `TensorFlow` `Raspberry Pi`

</td>
<td width="50%">

**[Container Runtime](https://github.com/mohosy/container-runtime-from-scratch)** · *Docker from First Principles*

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Zero Deps](https://img.shields.io/badge/Zero_Dependencies-black?style=flat-square)

- PID, mount, network, and UTS namespace isolation
- cgroups: memory limits with OOM kill, CPU shares, process caps
- Union filesystem with copy-on-write layers and Dockerfile parser

`Python` `Namespaces` `cgroups` `Union FS` `OCI`

</td>
</tr>
</table>

---

## Systems Engineering

*No frameworks. No libraries. Built from first principles.*

<table>
<tr>
<td width="50%" valign="top">

**[Transformer Language Model](https://github.com/mohosy/transformer-lm-from-scratch)**
<br/>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" /> <img src="https://img.shields.io/badge/NumPy_Only-013243?style=flat-square&logo=numpy&logoColor=white" /> <img src="https://img.shields.io/badge/55_tests-brightgreen?style=flat-square" />

GPT-style decoder with manual backpropagation through every layer — multi-head attention, rotary embeddings, SwiGLU, KV-cache. LLaMA/Mistral architecture. Every gradient derived analytically.

</td>
<td width="50%" valign="top">

**[HTTP Server](https://github.com/mohosy/http-server-from-scratch)**
<br/>
<img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white" /> <img src="https://img.shields.io/badge/Zero_Dependencies-black?style=flat-square" /> <img src="https://img.shields.io/badge/46_tests-brightgreen?style=flat-square" />

HTTP/1.1 from raw TCP sockets. Thread pool, Express-style router, middleware chain, static file serving, keep-alive connections.

</td>
</tr>
<tr>
<td width="50%" valign="top">

**[SQL Database Engine](https://github.com/mohosy/sql-database-engine)**
<br/>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" /> <img src="https://img.shields.io/badge/Zero_Dependencies-black?style=flat-square" /> <img src="https://img.shields.io/badge/80_tests-brightgreen?style=flat-square" />

Recursive descent SQL parser, query executor, B-tree column indexing, persistence, interactive REPL. Full DDL/DML with aggregates.

</td>
<td width="50%" valign="top">

**[Garbage Collector](https://github.com/mohosy/garbage-collector-from-scratch)**
<br/>
<img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white" /> <img src="https://img.shields.io/badge/Zero_Dependencies-black?style=flat-square" /> <img src="https://img.shields.io/badge/43_tests-brightgreen?style=flat-square" />

Mark-and-sweep with generational collection, object graph tracing, circular reference handling. Handles 100K allocations in 7ms.

</td>
</tr>
</table>

<details>
<summary><b>All 30+ from-scratch implementations →</b></summary>
<br/>

| Project | Lang | What It Demonstrates |
|---------|------|---------------------|
| [Database Replication Engine](https://github.com/mohosy/database-replication-engine) | TypeScript | WAL, leader-follower replication, automatic failover, split-brain healing |
| [Raft Consensus](https://github.com/mohosy/raft-consensus-simulator) | TypeScript | Leader election, log replication, fault injection, network partitions |
| [LSM-Tree Storage Engine](https://github.com/mohosy/lsm-tree-storage-engine) | TypeScript | WAL, memtables, SSTables, Bloom filters, compaction |
| [CNN + Object Detection](https://github.com/mohosy/pedestrian-detection-cnn) | Python | ResNet, MobileNet from scratch, im2col convolution, focal loss, NMS |
| [Lisp Interpreter](https://github.com/mohosy/lisp-interpreter-from-scratch) | Python | Lexer, parser, tree-walking eval, tail-call optimization, macros |
| [Bytecode Compiler + VM](https://github.com/mohosy/bytecode-vm-compiler) | TypeScript | Full pipeline: lexer → parser → bytecode → stack VM. Custom "Bolt" language |
| [3D Ray Tracer](https://github.com/mohosy/raytracer-from-scratch) | C++ | Phong shading, reflections, shadow rays, multi-threaded rendering |
| [Search Engine](https://github.com/mohosy/search-engine-from-scratch) | Python | Inverted index, BM25 ranking, full-text search |
| [Exchange Engine](https://github.com/mohosy/realtime-exchange-engine) | Python | Limit order book, NYSE-style price-time priority matching |
| [Load Balancer](https://github.com/mohosy/load-balancer-from-scratch) | Java | Request distribution, health checks, connection management |
| [WebSocket Server](https://github.com/mohosy/websocket-server-from-scratch) | C++ | WebSocket protocol from raw TCP |
| [GraphQL Engine](https://github.com/mohosy/graphql-engine-from-scratch) | Python | Query parsing, schema resolution, execution |
| [Build System](https://github.com/mohosy/build-system-from-scratch) | TypeScript | Dependency graph, incremental builds |
| [Network Protocol Stack](https://github.com/mohosy/network-protocol-stack-from-scratch) | Python | TCP/IP stack implementation |
| [Virtual Filesystem](https://github.com/mohosy/virtual-filesystem-from-scratch) | Python | VFS with inodes, directory tree, permissions |
| [Video Codec](https://github.com/mohosy/video-codec-from-scratch) | Python | Video encoding/decoding from scratch |
| [Huffman Compression](https://github.com/mohosy/huffman-compression-engine) | C++ | Entropy coding, file compression |
| [POSIX Shell](https://github.com/mohosy/swift-posix-shell) | Swift | Shell interpreter with pipes, redirects, builtins |
| [DNS Resolver](https://github.com/mohosy/dns-resolver-from-scratch) | Python | Iterative resolution from root servers via raw UDP |
| [Regex Engine](https://github.com/mohosy/regexium) | Python | Thompson's NFA construction, O(n) matching |
| [Memory Allocator](https://github.com/mohosy/memory-allocator-simulator) | C++ | First-fit, best-fit, worst-fit placement strategies |
| [Distributed Task Queue](https://github.com/mohosy/distributed-task-queue) | Python | Priority scheduling, dependency DAGs, circuit breakers |
| [Drone Swarm Planner](https://github.com/mohosy/drone-swarm-mapf-planner) | Python | Multi-agent pathfinding for drone coordination |
| [Myers Diff](https://github.com/mohosy/myers-diff-from-scratch) | TypeScript | The algorithm behind `git diff` |
| [B-Tree Index](https://github.com/mohosy/b-tree-index-from-scratch) | TypeScript | The data structure behind database indexes |
| [KV Store](https://github.com/mohosy/kv-store-engine) | Java | Hash table, TTL expiration, snapshot persistence |
| [PubSub Queue](https://github.com/mohosy/postgres-backed-pubsub-queue) | TypeScript | Durable messaging on PostgreSQL LISTEN/NOTIFY |
| [JSON Parser](https://github.com/mohosy/json-recursive-descent-parser) | TypeScript | Recursive descent parsing, zero dependencies |
| [Rate Limiter](https://github.com/mohosy/flowguard) | Python | Token bucket and sliding window implementations |
| [LRU Cache](https://github.com/mohosy/swift-lru-cache-from-scratch) | Swift | O(1) cache with doubly-linked list + hash map |
| [Trie Autocomplete API](https://github.com/mohosy/django-trie-autocomplete-api) | Python | Weighted prefix search in O(k) time |
| [Traffic Sign CNN](https://github.com/mohosy/traffic-sign-neural-network) | Python | Neural network for traffic sign classification |

</details>

---

## Tech Stack

**Languages** · Python · TypeScript · Java · C++ · Swift · JavaScript · SQL
<br/>
**Backend** · Node.js · Express · Django · Spring Boot
<br/>
**Frontend** · React · React Native
<br/>
**Data** · PostgreSQL · MongoDB · Redis · Firebase
<br/>
**Infrastructure** · AWS · Docker · Git · Linux

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,typescript,java,cpp,swift,react,nodejs,express,spring,django,mongodb,postgres,aws,docker,git,linux&theme=dark&perline=8" />
</p>

---

<p align="center">
  <img src="https://img.shields.io/badge/Forbes-Featured-E4405F?style=for-the-badge&logo=forbes&logoColor=white" />
  <img src="https://img.shields.io/badge/HTCC_2024-1st_Place-FFD700?style=for-the-badge&logo=trophy&logoColor=white" />
  <img src="https://img.shields.io/badge/Presidential_Service-2x_Gold-C9B037?style=for-the-badge&logo=award&logoColor=white" />
</p>
