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

## 🚀 Production Systems

<table>
<tr>
<td width="50%">

**PCC AI Chatbot** — *Founding Engineer*

![Users](https://img.shields.io/badge/Users-30,000+-8B5CF6?style=flat-square)
![Queries](https://img.shields.io/badge/Daily_Queries-640+-06B6D4?style=flat-square)
![Uptime](https://img.shields.io/badge/Uptime-99.9%25-10B981?style=flat-square)

- RAG pipeline: 900+ docs indexed, sub-100ms retrieval
- Improved accuracy 38% → 66%, reduced hallucinations 40%
- Built agentic mode with Browserbase + Playwright

`Node.js` `Express` `MongoDB` `GPT-4` `RAG` `Sentry`

</td>
<td width="50%">

**IRL Social App** — *Founder & Lead Engineer*

![Beta](https://img.shields.io/badge/Beta_Testers-470+-8B5CF6?style=flat-square)
![Pipeline](https://img.shields.io/badge/Upload_Latency-<200ms-06B6D4?style=flat-square)
![Volume](https://img.shields.io/badge/Weekly_Clips-1,000+-10B981?style=flat-square)

- Real-time video social network with 6-second posts
- FFmpeg transcoding + AWS S3 presigned URLs
- Iterated on 35% week-1 retention data

`React Native` `Node.js` `FFmpeg` `Socket.io` `AWS`

</td>
</tr>
<tr>
<td width="50%">

**AI Patrol Drone** — *1st Place @ HTCC 2024*

![Award](https://img.shields.io/badge/HTCC-1st_Place-FFD700?style=flat-square)
![Type](https://img.shields.io/badge/Computer_Vision-Wildlife_Detection-06B6D4?style=flat-square)

- CV-based system to identify predatory wildlife
- Protects outdoor pets via real-time detection
- Won against 50+ competing projects

`Python` `OpenCV` `TensorFlow` `Raspberry Pi`

</td>
<td width="50%">

**Code Can Bridge** — *Founder, 501(c)(3) Nonprofit*

![Status](https://img.shields.io/badge/Status-501(c)(3)-8B5CF6?style=flat-square)
![Impact](https://img.shields.io/badge/Teaching-Students_with_Disabilities-10B981?style=flat-square)

- Founded nonprofit teaching coding to students with learning disabilities
- Program at Arcadia High School
- Making CS education accessible

`Python` `Scratch` `Curriculum Design`

</td>
</tr>
</table>

---

## 🔧 From-Scratch Implementations

<p align="center">
  <img src="https://img.shields.io/badge/Philosophy-If_you_can't_build_it,_you_don't_understand_it-8B5CF6?style=for-the-badge" />
</p>

<table>
<tr>
<td width="50%" valign="top">

### 🌐 [DNS Resolver](https://github.com/mohosy/dns-resolver-from-scratch)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Networking](https://img.shields.io/badge/UDP_Sockets-06B6D4?style=flat-square)

```python
def resolve(domain):
    query = build_dns_query(domain)
    sock.sendto(query, ("8.8.8.8", 53))
    response = parse_dns_response(sock.recv(512))
    return response.answers[0].ip
```
*How the internet actually finds websites*

</td>
<td width="50%" valign="top">

### 🌳 [B-Tree Index](https://github.com/mohosy/b-tree-index-from-scratch)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white)
![Database](https://img.shields.io/badge/Data_Structures-10B981?style=flat-square)

```typescript
class BTreeNode<K, V> {
  keys: K[] = [];
  children: BTreeNode<K, V>[] = [];

  search(key: K): V | null {
    // O(log n) balanced tree traversal
  }
}
```
*Why databases can search billions of rows instantly*

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 📝 [Myers Diff](https://github.com/mohosy/myers-diff-engine)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white)
![Algorithms](https://img.shields.io/badge/Graph_Theory-FFD700?style=flat-square)

```typescript
function shortestEdit(a: string[], b: string[]) {
  // Find shortest edit script via
  // graph traversal on edit grid
  // The algorithm powering `git diff`
}
```
*The exact algorithm behind `git diff`*

</td>
<td width="50%" valign="top">

### 🔤 [Regex Engine](https://github.com/mohosy/regexium)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Theory](https://img.shields.io/badge/Automata_Theory-E4405F?style=flat-square)

```python
class NFA:
    def thompson_construct(self, regex):
        # Convert regex → NFA using
        # Thompson's construction
        # Then simulate NFA for matching
```
*How regex engines match patterns in O(n)*

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🧠 [Memory Allocator](https://github.com/mohosy/memory-allocator-simulator)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Systems](https://img.shields.io/badge/Systems-8B5CF6?style=flat-square)

```cpp
void* my_malloc(size_t size) {
    Block* block = find_free_block(size);
    if (!block) block = request_space(size);
    split_block(block, size);
    return block->data;
}
```
*How `malloc()` and `free()` actually work*

</td>
<td width="50%" valign="top">

### 📨 [PubSub Queue](https://github.com/mohosy/postgres-backed-pubsub-queue)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white)
![Database](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white)

```typescript
// LISTEN/NOTIFY for real-time events
await client.query('LISTEN new_job');
client.on('notification', async (msg) => {
  await processJob(msg.payload);
});
```
*Building Kafka-like queues with just Postgres*

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🔍 [Trie Autocomplete](https://github.com/mohosy/django-trie-autocomplete-api)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)

```python
class TrieNode:
    def __init__(self):
        self.children = {}
        self.is_end = False

    def insert(self, word):
        node = self
        for char in word:
            node = node.children.setdefault(char, TrieNode())
        node.is_end = True
```
*How Google search suggestions work under the hood*

</td>
<td width="50%" valign="top">

### 🚀 More Coming Soon...
![Status](https://img.shields.io/badge/Status-Always_Building-8B5CF6?style=flat-square)

```text
┌─────────────────────────────┐
│  Next up:                   │
│  → HTTP server from scratch │
│  → Git internals            │
│  → Compiler frontend        │
└─────────────────────────────┘
```
*The learning never stops*

</td>
</tr>
</table>

---

## 📊 Tech Stack & Activity

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=mohosy&theme=tokyo-night&hide_border=true&area=true" width="100%" />
</p>

### Skills & Proficiency

```text
Python          ████████████████████░░░░░   80%
TypeScript      ███████████████████░░░░░░   75%
JavaScript      ███████████████████░░░░░░   75%
C++             ██████████████░░░░░░░░░░░   55%
React/RN        ██████████████████░░░░░░░   70%
Node.js         ████████████████████░░░░░   80%
```

```text
MongoDB         ███████████████████░░░░░░   75%
PostgreSQL      ██████████████████░░░░░░░   70%
AWS             ██████████████░░░░░░░░░░░   55%
Docker          ██████████████░░░░░░░░░░░   55%
RAG/LLMs        ████████████████████░░░░░   80%
System Design   ██████████████████░░░░░░░   70%
```

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,typescript,cpp,react,nodejs,express,mongodb,postgres,aws,docker,git,linux&theme=dark&perline=6" />
</p>

---

## 🏆 Achievements

<p align="center">
  <img src="https://img.shields.io/badge/Forbes-Featured-E4405F?style=for-the-badge&logo=forbes&logoColor=white" />
  <img src="https://img.shields.io/badge/HTCC_2024-1st_Place-FFD700?style=for-the-badge&logo=trophy&logoColor=white" />
  <img src="https://img.shields.io/badge/Presidential_Service-2x_Gold-C9B037?style=for-the-badge&logo=award&logoColor=white" />
</p>

---

## 📈 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=mohosy&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="GitHub Stats" height="180" />
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=mohosy&theme=tokyonight&hide_border=true" alt="GitHub Streak" height="180" />
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=mohosy&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" alt="Top Languages" height="165" />
</p>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/mohosy/mohosy/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/mohosy/mohosy/output/github-snake.svg" />
  <img alt="github contribution snake animation" src="https://raw.githubusercontent.com/mohosy/mohosy/output/github-snake.svg" width="100%" />
</picture>

---

## 🎯 Currently

<p align="center">
  <img src="https://img.shields.io/badge/Building-IRL_Social_App-8B5CF6?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Learning-Distributed_Systems-06B6D4?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Reading-Designing_Data--Intensive_Apps-10B981?style=for-the-badge" />
</p>

---

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=mohosy&style=for-the-badge&color=8B5CF6" alt="Profile Views" />
</p>

<p align="center">
  <b>Open to SWE opportunities at top tech companies</b>
  <br/>
  <i>Let's build something that matters.</i>
</p>

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,12,19&height=100&section=footer" width="100%" />
