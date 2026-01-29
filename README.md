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

## Featured Project

<table>
<tr>
<td>

### <a href="https://github.com/mohosy/irl-official">IRL</a> — Real-Time Social Video Platform

<img src="https://img.shields.io/badge/470+-beta_testers-58A6FF?style=flat-square" /> <img src="https://img.shields.io/badge/1,000+-weekly_clips-A78BFA?style=flat-square" /> <img src="https://img.shields.io/badge/35%25-week--1_retention-22C55E?style=flat-square" />

Full-stack mobile app where friends hang out through video messages, live presence, and real-time games — built from the ground up as a solo engineer.

**Presence Avatars** — Bitmoji-style animated characters that mirror each user's real-time position, emoji, and activity state across screens via WebRTC data channels (~50ms sync). Supports 9 choreographed dances, speech bubbles, push-to-talk mic indicators, and an 8-state presence machine (recording, watching, typing, etc.).

**Lobby Mode** — Synchronized virtual hangout where both users' avatars exist in a shared 3D animated scene. Features ready-up invite flow with countdown, staggered entrance animations, voice activity indicators, and an emote action bar.

**Battle Royale** — Real-time 1v1 multiplayer game with projectile physics, distance-based damage, knockback mechanics, progressive storm zones, health bar systems, and screen shake + haptic feedback on impact — all state-synced over Agora data stream and Socket.io.

**Video Pipeline** — Ephemeral Snapchat-style video/photo DMs with Vision Camera capture, FFmpeg transcoding, S3 multipart uploads, CloudFront CDN delivery, view-once consumption tracking, screenshot detection, replay limits, and auto-expiry via MongoDB TTL indexes.

**Real-Time Architecture** — Hybrid WebSocket layer combining Agora WebRTC (voice, data streaming) with Socket.io (15+ event types, per-message compression, connection state recovery). In-memory caching with 30-60s TTL, rate limiting, and 44 MongoDB collections with compound indexes.

<sub>React Native · TypeScript · Node.js · Express · MongoDB · Socket.io · Agora WebRTC · FFmpeg · AWS S3 · CloudFront · Firebase · Redux Toolkit · Reanimated</sub>

</td>
</tr>
</table>

---

## Production

<table>
<tr>
<td width="50%">

**PCC AI Chatbot** · *Founding Engineer*

**30,000+ users** · 640 daily queries · 99.9% uptime

RAG pipeline indexing 900+ documents with sub-100ms retrieval. Improved response accuracy from 38% to 66% and reduced hallucinations by 40%.

<sub>Node.js · Express · MongoDB · GPT-4 · RAG · Sentry</sub>

</td>
<td width="50%">

**AI Patrol Drone** · *1st Place, HTCC 2024*

Computer vision system for predatory wildlife detection to protect outdoor pets. Won against 50+ competing projects.

<sub>Python · OpenCV · TensorFlow · Raspberry Pi</sub>

</td>
</tr>
<tr>
<td width="50%">

**Code Can Bridge** · *Founder, 501(c)(3)*

Nonprofit teaching coding to students with learning disabilities at Arcadia High School. Making CS education accessible.

<sub>Python · Scratch · Curriculum Design</sub>

</td>
<td width="50%">

</td>
</tr>
</table>

---

## From Scratch

*No frameworks. No libraries. Just the fundamentals — built from first principles.*

<table>
<tr>
<td width="50%" valign="top">

**<a href="https://github.com/mohosy/transformer-lm-from-scratch">Transformer Language Model</a>**
<br/>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" /> <img src="https://img.shields.io/badge/NumPy_Only-013243?style=flat-square&logo=numpy&logoColor=white" /> <img src="https://img.shields.io/badge/55_tests-brightgreen?style=flat-square" />

GPT-style decoder with **manual backpropagation** through every layer — multi-head attention, rotary embeddings, SwiGLU, KV-cache. LLaMA/Mistral architecture. Every gradient derived analytically.

</td>
<td width="50%" valign="top">

**<a href="https://github.com/mohosy/garbage-collector-from-scratch">Garbage Collector</a>**
<br/>
<img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white" /> <img src="https://img.shields.io/badge/Zero_Dependencies-black?style=flat-square" /> <img src="https://img.shields.io/badge/43_tests-brightgreen?style=flat-square" />

**Mark-and-sweep** with generational collection, object graph tracing, circular reference handling, automatic trigger thresholds. Handles 100K allocations in 7ms.

</td>
</tr>
<tr>
<td width="50%" valign="top">

**<a href="https://github.com/mohosy/http-server-from-scratch">HTTP Server</a>**
<br/>
<img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white" /> <img src="https://img.shields.io/badge/Zero_Dependencies-black?style=flat-square" /> <img src="https://img.shields.io/badge/46_tests-brightgreen?style=flat-square" />

HTTP/1.1 from **raw TCP sockets**. Thread pool, Express-style router, middleware chain, static file serving, keep-alive connections.

</td>
<td width="50%" valign="top">

**<a href="https://github.com/mohosy/pedestrian-detection-cnn">CNN + Object Detection</a>**
<br/>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" /> <img src="https://img.shields.io/badge/Zero_Dependencies-black?style=flat-square" /> <img src="https://img.shields.io/badge/125_tests-brightgreen?style=flat-square" />

3 CNN architectures from scratch — **Baseline**, **ResNet**, **MobileNet**. im2col convolution, BatchNorm, focal loss, sliding window detection + NMS.

</td>
</tr>
<tr>
<td width="50%" valign="top">

**<a href="https://github.com/mohosy/lisp-interpreter-from-scratch">Lisp Interpreter</a>**
<br/>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" /> <img src="https://img.shields.io/badge/Zero_Dependencies-black?style=flat-square" /> <img src="https://img.shields.io/badge/97_tests-brightgreen?style=flat-square" />

Lexer, parser, tree-walking evaluator. **Tail-call optimization** via trampoline (100K+ recursion depth), closures, macros, lexical scoping.

</td>
<td width="50%" valign="top">

**<a href="https://github.com/mohosy/bytecode-vm-compiler">Bytecode Compiler + VM</a>**
<br/>
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" /> <img src="https://img.shields.io/badge/Zero_Dependencies-black?style=flat-square" /> <img src="https://img.shields.io/badge/53_tests-brightgreen?style=flat-square" />

Full compiler pipeline: **lexer → parser → bytecode → stack VM**. Call frames, forward patching, constant pool. Custom "Bolt" language.

</td>
</tr>
<tr>
<td width="50%" valign="top">

**<a href="https://github.com/mohosy/sql-database-engine">SQL Database Engine</a>**
<br/>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" /> <img src="https://img.shields.io/badge/Zero_Dependencies-black?style=flat-square" /> <img src="https://img.shields.io/badge/80_tests-brightgreen?style=flat-square" />

**Recursive descent SQL parser**, query executor, B-tree column indexing, persistence, interactive REPL. Full DDL/DML + aggregates.

</td>
<td width="50%" valign="top">

**<a href="https://github.com/mohosy/raytracer-from-scratch">3D Ray Tracer</a>**
<br/>
<img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white" /> <img src="https://img.shields.io/badge/Zero_Dependencies-black?style=flat-square" /> <img src="https://img.shields.io/badge/34_tests-brightgreen?style=flat-square" />

Phong shading, recursive reflections, shadow rays, supersampled anti-aliasing, **multi-threaded rendering**. 800×600 in 163ms.

</td>
</tr>
</table>

<details>
<summary><b>All 24+ from-scratch implementations →</b></summary>
<br/>

<p align="center">
<a href="https://github.com/mohosy/traffic-sign-neural-network"><img src="https://github-readme-stats.vercel.app/api/pin/?username=mohosy&repo=traffic-sign-neural-network&theme=tokyonight&hide_border=true" width="49%" /></a>
<a href="https://github.com/mohosy/search-engine-from-scratch"><img src="https://github-readme-stats.vercel.app/api/pin/?username=mohosy&repo=search-engine-from-scratch&theme=tokyonight&hide_border=true" width="49%" /></a>
</p>
<p align="center">
<a href="https://github.com/mohosy/realtime-exchange-engine"><img src="https://github-readme-stats.vercel.app/api/pin/?username=mohosy&repo=realtime-exchange-engine&theme=tokyonight&hide_border=true" width="49%" /></a>
<a href="https://github.com/mohosy/swift-posix-shell"><img src="https://github-readme-stats.vercel.app/api/pin/?username=mohosy&repo=swift-posix-shell&theme=tokyonight&hide_border=true" width="49%" /></a>
</p>
<p align="center">
<a href="https://github.com/mohosy/kv-store-engine"><img src="https://github-readme-stats.vercel.app/api/pin/?username=mohosy&repo=kv-store-engine&theme=tokyonight&hide_border=true" width="49%" /></a>
<a href="https://github.com/mohosy/drone-swarm-mapf-planner"><img src="https://github-readme-stats.vercel.app/api/pin/?username=mohosy&repo=drone-swarm-mapf-planner&theme=tokyonight&hide_border=true" width="49%" /></a>
</p>
<p align="center">
<a href="https://github.com/mohosy/dns-resolver-from-scratch"><img src="https://github-readme-stats.vercel.app/api/pin/?username=mohosy&repo=dns-resolver-from-scratch&theme=tokyonight&hide_border=true" width="49%" /></a>
<a href="https://github.com/mohosy/regexium"><img src="https://github-readme-stats.vercel.app/api/pin/?username=mohosy&repo=regexium&theme=tokyonight&hide_border=true" width="49%" /></a>
</p>
<p align="center">
<a href="https://github.com/mohosy/memory-allocator-simulator"><img src="https://github-readme-stats.vercel.app/api/pin/?username=mohosy&repo=memory-allocator-simulator&theme=tokyonight&hide_border=true" width="49%" /></a>
<a href="https://github.com/mohosy/postgres-backed-pubsub-queue"><img src="https://github-readme-stats.vercel.app/api/pin/?username=mohosy&repo=postgres-backed-pubsub-queue&theme=tokyonight&hide_border=true" width="49%" /></a>
</p>
<p align="center">
<a href="https://github.com/mohosy/myers-diff-from-scratch"><img src="https://github-readme-stats.vercel.app/api/pin/?username=mohosy&repo=myers-diff-from-scratch&theme=tokyonight&hide_border=true" width="49%" /></a>
<a href="https://github.com/mohosy/b-tree-index-from-scratch"><img src="https://github-readme-stats.vercel.app/api/pin/?username=mohosy&repo=b-tree-index-from-scratch&theme=tokyonight&hide_border=true" width="49%" /></a>
</p>
<p align="center">
<a href="https://github.com/mohosy/django-trie-autocomplete-api"><img src="https://github-readme-stats.vercel.app/api/pin/?username=mohosy&repo=django-trie-autocomplete-api&theme=tokyonight&hide_border=true" width="49%" /></a>
<a href="https://github.com/mohosy/json-recursive-descent-parser"><img src="https://github-readme-stats.vercel.app/api/pin/?username=mohosy&repo=json-recursive-descent-parser&theme=tokyonight&hide_border=true" width="49%" /></a>
</p>
<p align="center">
<a href="https://github.com/mohosy/swift-lru-cache-from-scratch"><img src="https://github-readme-stats.vercel.app/api/pin/?username=mohosy&repo=swift-lru-cache-from-scratch&theme=tokyonight&hide_border=true" width="49%" /></a>
<a href="https://github.com/mohosy/flowguard"><img src="https://github-readme-stats.vercel.app/api/pin/?username=mohosy&repo=flowguard&theme=tokyonight&hide_border=true" width="49%" /></a>
</p>
<p align="center">
<a href="https://github.com/mohosy/cpu-scheduling-visualizer"><img src="https://github-readme-stats.vercel.app/api/pin/?username=mohosy&repo=cpu-scheduling-visualizer&theme=tokyonight&hide_border=true" width="49%" /></a>
<a href="https://github.com/mohosy/algoscape"><img src="https://github-readme-stats.vercel.app/api/pin/?username=mohosy&repo=algoscape&theme=tokyonight&hide_border=true" width="49%" /></a>
</p>

</details>

---

## Tech Stack

**Languages** · Python · TypeScript · Java · C++ · Swift · JavaScript · SQL
**Backend** · Node.js · Express · Django · Spring Boot
**Frontend** · React · React Native
**Data** · PostgreSQL · MongoDB · Redis · Firebase
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

---

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=mohosy&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="GitHub Stats" height="180" />
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=mohosy&theme=tokyonight&hide_border=true" alt="GitHub Streak" height="180" />
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=mohosy&theme=tokyo-night&hide_border=true&area=true" width="100%" />
</p>

---

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=mohosy&style=for-the-badge&color=8B5CF6" alt="Profile Views" />
</p>

<p align="center">
  <b>Open to SWE internship opportunities at top tech companies</b>
  <br/>
  <i>Let's build something that matters.</i>
</p>

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,12,19&height=100&section=footer" width="100%" />
