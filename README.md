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

**30,000+ users** · 640 daily queries · 99.9% uptime

RAG pipeline indexing 900+ documents with sub-100ms retrieval. Improved response accuracy from 38% to 66% and reduced hallucinations by 40%.

<sub>Node.js · Express · MongoDB · GPT-4 · RAG · Sentry</sub>

</td>
<td width="50%">

**IRL Social App** · *Founder & Lead Engineer*

**470+ beta testers** · 1,000+ weekly clips

Real-time video social network with 6-second posts. FFmpeg transcoding pipeline with AWS S3 presigned URLs. Iterated on 35% week-1 retention.

<sub>React Native · Node.js · FFmpeg · Socket.io · AWS</sub>

</td>
</tr>
<tr>
<td width="50%">

**AI Patrol Drone** · *1st Place, HTCC 2024*

Computer vision system for predatory wildlife detection to protect outdoor pets. Won against 50+ competing projects.

<sub>Python · OpenCV · TensorFlow · Raspberry Pi</sub>

</td>
<td width="50%">

**Code Can Bridge** · *Founder, 501(c)(3)*

Nonprofit teaching coding to students with learning disabilities at Arcadia High School. Making CS education accessible.

<sub>Python · Scratch · Curriculum Design</sub>

</td>
</tr>
</table>

---

## From Scratch

<p align="center">
<img src="https://img.shields.io/badge/16_systems_built_from_scratch-zero_dependencies-58A6FF?style=for-the-badge" />
</p>

<table>
<tr>
<td width="50%" valign="top">

**[Bytecode VM Compiler](https://github.com/mohosy/bytecode-vm-compiler)** · TypeScript

Full language pipeline — lexer, recursive descent parser, single-pass bytecode compiler, and stack-based VM with functions and closures.

```typescript
compile(ast: Program): Chunk {
  for (const stmt of ast.body)
    this.compileStatement(stmt);
  this.emit(Op.HALT);
  return this.chunk;
}
```

</td>
<td width="50%" valign="top">

**[Search Engine](https://github.com/mohosy/search-engine-from-scratch)** · Python

Inverted index with posting lists, BM25 ranking, boolean queries (AND/OR/NOT), Porter stemmer, and built-in web search UI.

```python
idf = log((N - df + 0.5) / (df + 0.5) + 1)
tf_norm = (tf * (k1 + 1)) / (
    tf + k1 * (1 - b + b * dl / avgdl))
score = idf * tf_norm  # BM25
```

</td>
</tr>
<tr>
<td width="50%" valign="top">

**[Exchange Engine](https://github.com/mohosy/realtime-exchange-engine)** · Python

Stock exchange with limit order book, price-time priority matching (NYSE/NASDAQ algorithm), and live terminal dashboard.

```python
while order.remaining > 0:
    best = self.best_ask if buy else self.best_bid
    if not best or not price_crosses: break
    self.execute_trade(order, best)
```

</td>
<td width="50%" valign="top">

**[KV Store Engine](https://github.com/mohosy/kv-store-engine)** · Java / Spring Boot

Custom open-addressing hash table with FNV-1a hashing, TTL expiration, snapshot persistence, and REST API.

```java
int idx = hash(key) & (capacity - 1);
while (table[idx] != null) {
    if (table[idx].key.equals(key))
        return table[idx].value; // O(1)
    idx = (idx + 1) & (capacity - 1);
}
```

</td>
</tr>
<tr>
<td width="50%" valign="top">

**[Regex Engine](https://github.com/mohosy/regexium)** · Python

NFA-based pattern matching via Thompson's construction. Converts regex to NFA and simulates for guaranteed O(n) matching.

```python
def thompson_construct(self, regex):
    # Regex → NFA via Thompson's
    # construction algorithm
    # Guarantees O(n) matching time
```

</td>
<td width="50%" valign="top">

**[DNS Resolver](https://github.com/mohosy/dns-resolver-from-scratch)** · Python

Iterative DNS resolution from root servers using raw UDP sockets. Parses the binary DNS wire format.

```python
query = build_dns_query(domain)
sock.sendto(query, ("8.8.8.8", 53))
resp = parse_dns_response(sock.recv(512))
return resp.answers[0].ip
```

</td>
</tr>
</table>

<details>
<summary><b>All 16 implementations →</b></summary>
<br/>

| Project | Tech | What it demonstrates |
|:--------|:-----|:---------------------|
| [Bytecode VM Compiler](https://github.com/mohosy/bytecode-vm-compiler) | TypeScript | Lexer, parser, compiler, stack-based virtual machine |
| [Search Engine](https://github.com/mohosy/search-engine-from-scratch) | Python | Inverted index, BM25 ranking, boolean query evaluation |
| [Exchange Engine](https://github.com/mohosy/realtime-exchange-engine) | Python | Limit order book, price-time priority matching |
| [KV Store Engine](https://github.com/mohosy/kv-store-engine) | Java / Spring Boot | Custom hash table, TTL expiration, snapshot persistence |
| [CPU Scheduler](https://github.com/mohosy/cpu-scheduling-visualizer) | React / TypeScript | FCFS, SJF, Round Robin with interactive Gantt chart |
| [Regex Engine](https://github.com/mohosy/regexium) | Python | Thompson's NFA construction, O(n) matching |
| [DNS Resolver](https://github.com/mohosy/dns-resolver-from-scratch) | Python | Iterative resolution, UDP sockets, binary protocol |
| [B-Tree Index](https://github.com/mohosy/b-tree-index-from-scratch) | TypeScript | Disk-optimized search tree, O(log n) operations |
| [Myers Diff](https://github.com/mohosy/myers-diff-from-scratch) | TypeScript | Shortest edit script via edit graph traversal |
| [Memory Allocator](https://github.com/mohosy/memory-allocator-simulator) | C++ | First-fit / best-fit placement, coalescing |
| [PubSub Queue](https://github.com/mohosy/postgres-backed-pubsub-queue) | TS / PostgreSQL | Durable message queue with consumer groups |
| [Trie Autocomplete](https://github.com/mohosy/django-trie-autocomplete-api) | Python / Django | Weighted prefix search with REST API |
| [JSON Parser](https://github.com/mohosy/json-recursive-descent-parser) | TypeScript | Tokenizer + recursive descent parser |
| [LRU Cache](https://github.com/mohosy/swift-lru-cache-from-scratch) | Swift | O(1) doubly-linked list + hash map |
| [Rate Limiter](https://github.com/mohosy/flowguard) | Python | Token bucket + sliding window algorithms |
| [Algorithm Visualizer](https://github.com/mohosy/algoscape) | JavaScript | QuickSort, MergeSort, A*, Dijkstra, BFS/DFS |

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
