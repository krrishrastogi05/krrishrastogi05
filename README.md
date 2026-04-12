
<!-- ══════════════════════════════════════════════════════════════════════════ -->
<!--                         KRRISH RASTOGI · PROFILE README                   -->
<!-- ══════════════════════════════════════════════════════════════════════════ -->

<div align="center">

<!-- Dynamic Typing SVG -->
<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=28&duration=3000&pause=1000&color=58A6FF&center=true&vCenter=true&multiline=true&repeat=true&width=800&height=100&lines=%E2%9A%A1+Krrish+Rastogi;Backend+Systems+%C2%B7+GenAI+%C2%B7+Distributed+Architecture" alt="Typing SVG" /></a>

<br/>

<!-- Badges Row -->
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/krrish-rastogi-a41712283)
[![Gmail](https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:krrishrastogi00@gmail.com)
[![LeetCode](https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black)](https://leetcode.com/u/godsownsoldier)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/krrishrastogi05)


<br/>

<img src="https://komarev.com/ghpvc/?username=krrishrastogi05&style=for-the-badge&color=58A6FF&label=PROFILE+VIEWS" alt="Profile Views"/>

</div>

---

<div align="center">
<table>
<tr>
<td>

### 🏆 National Champion · SIH 2025

</td>
<td>

### 🎯 Amazon HackOn Top 75 / 50K+

</td>
<td>

### ♞ LeetCode Knight · 1900+

</td>
</tr>
</table>
</div>

---

## `$ whoami`

```yaml
name:        Krrish Rastogi
location:    BIT Mesra, Ranchi — Jharkhand, India
degree:      B.Tech in AI & Machine Learning (CGPA: 8.7/10)
focus_areas: [ "Distributed Backend Systems", "Generative AI Pipelines",
               "Real-Time Architectures", "Agentic AI Workflows" ]
philosophy:  "Engineer systems that think, scale, and never sleep."
```

I build **production-grade backend systems** and **AI-powered platforms** that operate at scale — from asynchronous job queues processing 15K+ tasks/sec to multimodal GenAI pipelines with sub-500ms latency. My work sits at the intersection of **distributed systems engineering** and **generative AI**, and I've shipped code that won national hackathons and earned recognition across 8.26 Lakh+ participants.

---

## ⚔️ Achievements & Recognition

<div align="center">

| 🏅 Achievement | 📊 Scale |
|:---|:---|
| **🥇 Smart India Hackathon 2025 — National Winner** | Top **0.2%** of 8,26,000+ participants |
| **🏆 Amazon HackOn 2025 — Top 75** | Top **0.15%** of 50,000+ participants |
| **🎯 UIDAI Aadhaar Data Hackathon — National Finalist** | Selected among top teams nationally |
| **🌍 Open Source Contributor — UN-OICT** | United Nations Office of ICT |
| **♞ LeetCode Knight — Rating 1900+** | Global Top **5%** |
| **🎓 GP Birla Merit Scholarship** | ₹~1.4 Lakh for academic excellence |

</div>

---

## 🚀 Flagship Projects

<details open>
<summary><b>🏛️ Beneficiary Management Platform — SIH 2025 National Winner</b></summary>
<br/>

> **The system that won Smart India Hackathon 2025.** A scalable government beneficiary management backend handling automated eligibility processing, role-based access, and high-throughput async job queues.

[![Repo](https://img.shields.io/badge/⚙️_Source_Code-SIH--Backend-181717?style=for-the-badge&logo=github)](https://github.com/krrishrastogi05/SIH-Backend)

**Architecture Highlights:**

```
┌──────────────┐     ┌───────────────┐     ┌──────────────────┐
│  Express API │────▶│  BullMQ Queue │────▶│  Redis Workers   │
│  + JWT/RBAC  │     │  (15K+ ops/s) │     │  (Eligibility    │
│  + Zod Valid.│     └───────────────┘     │   Engine)        │
└──────┬───────┘                           └────────┬─────────┘
       │                                            │
       ▼                                            ▼
┌──────────────┐                           ┌──────────────────┐
│  PostgreSQL  │◀──────────────────────────│  Prisma ORM      │
│  (10+ Tables)│   Normalized Schema       │  (Type-Safe)     │
└──────────────┘                           └──────────────────┘
```

`Node.js` `TypeScript` `PostgreSQL` `Redis` `BullMQ` `Prisma` `JWT` `RBAC` `Zod`

- Designed a scalable **RBAC backend** with JWT authentication supporting 3+ distinct roles and strict middleware security
- Engineered an **async eligibility engine** automating beneficiary qualification across 10+ rule conditions
- Implemented **BullMQ background workers** configured to handle **15,000+ async tasks/sec** with a normalized Prisma schema across 10+ relational tables

</details>

---

<details open>
<summary><b>⚔️ CodeFortress — Competitive Programming IDE Extension</b></summary>
<br/>

> **The developer tool that eliminates context-switching.** A VS Code + Chrome Extension pair that brings competitive programming problems directly into your editor with a multi-language local judge.

[![Repo](https://img.shields.io/badge/⚙️_Source_Code-CodeFortress-181717?style=for-the-badge&logo=github)](https://github.com/krrishrastogi05/CodeFortress-Extension)
[![Stars](https://img.shields.io/github/stars/krrishrastogi05/CodeFortress-Extension?style=for-the-badge&color=FFA116)](https://github.com/krrishrastogi05/CodeFortress-Extension/stargazers)

**System Design:**

```
┌───────────────────┐    HTTP Bridge     ┌────────────────────────┐
│  Chrome Extension │◀──────────────────▶│  VS Code Extension     │
│  (Problem Scraper)│    localhost:PORT   │  (Problem Viewer +     │
└───────────────────┘                    │   Local Judge)         │
                                         └───────────┬────────────┘
                                                     │
                                         ┌───────────▼────────────┐
                                         │  Execution Engine      │
                                         │  C++ · Python · Java   │
                                         │  + 2 more languages    │
                                         │  ─────────────────     │
                                         │  Sub-2s Verdicts       │
                                         │  TLE Enforcement       │
                                         │  Output Validation     │
                                         └────────────────────────┘
```

`VS Code API` `Chrome Extension` `Node.js` `React` `WebSockets` `Webpack`

- Built a **browser-to-editor communication bridge** via localhost HTTP, reducing context-switching by **80%**
- Designed a **language-agnostic execution engine** supporting 5+ languages with automated judging and time-limit enforcement
- Orchestrated **isolated execution workflows** within VS Code Extension Host with **sub-2s verdict turnaround**

</details>

---

<details open>
<summary><b>👁️ Argus.AI — Real-Time Disaster Management with GenAI</b></summary>
<br/>

> **AI-powered crisis intelligence.** A multimodal generative AI platform that processes text, image, and audio data streams to provide real-time disaster analysis with geospatial visualization.

[![Repo](https://img.shields.io/badge/⚙️_Source_Code-Argus.AI-181717?style=for-the-badge&logo=github)](https://github.com/krrishrastogi05/Argus.AI)
[![Live](https://img.shields.io/badge/🌐_Live_Demo-argus--ai-58A6FF?style=for-the-badge)](https://argus-ai-psi.vercel.app)

**Real-Time Pipeline:**

```
     ┌─────────┐  ┌─────────┐  ┌─────────┐
     │  Text   │  │  Image  │  │  Audio  │   ← 3 Data Modalities
     └────┬────┘  └────┬────┘  └────┬────┘
          │            │            │
          └────────────┼────────────┘
                       ▼
              ┌────────────────┐
              │  Google Gemini │   ← Multimodal Analysis
              │  (< 500ms)    │      Severity Scoring
              └───────┬────────┘     Auto-Geolocation
                      │
         ┌────────────▼─────────────┐
         │  Socket.io WebSocket     │   ← Bi-directional
         │  Pipeline (50+ clients)  │      Real-time Broadcast
         └────────────┬─────────────┘
                      ▼
         ┌──────────────────────┐
         │  Leaflet Live Map    │   ← Geospatial Visualization
         │  + Smart Dispatch    │      Asset Tracking
         └──────────────────────┘
```

`Node.js` `Express` `MongoDB` `Socket.io` `Google Gemini AI` `React` `Leaflet`

- Architected a **multimodal AI backend** processing 3+ data modalities with **< 500ms average latency**
- Implemented **bi-directional WebSocket pipeline** broadcasting live geospatial updates to **50+ concurrent clients**
- Built real-time command dashboard with AI-drafted public advisories and smart unit dispatch

</details>

---

<details>
<summary><b>🏦 NatWest Hackathon Project</b></summary>
<br/>

[![Repo](https://img.shields.io/badge/⚙️_Source_Code-Natwest--Hackathon-181717?style=for-the-badge&logo=github)](https://github.com/krrishrastogi05/Natwest-Hackathon)

A hackathon project built for the NatWest challenge, showcasing full-stack engineering and problem-solving under competitive constraints.

</details>

---

## 🛠️ Tech Arsenal

<div align="center">

### Languages
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)

### Backend & Runtime
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)
![Socket.io](https://img.shields.io/badge/Socket.io-010101?style=for-the-badge&logo=socketdotio&logoColor=white)
![BullMQ](https://img.shields.io/badge/BullMQ-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![REST API](https://img.shields.io/badge/REST_APIs-FF6F00?style=for-the-badge&logo=fastapi&logoColor=white)
![WebSockets](https://img.shields.io/badge/WebSockets-4353FF?style=for-the-badge&logo=websocket&logoColor=white)

### Databases & ORM
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white)
![Mongoose](https://img.shields.io/badge/Mongoose-880000?style=for-the-badge&logo=mongoose&logoColor=white)

### Frontend & AI
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Google Gemini](https://img.shields.io/badge/Google_Gemini-8E75B2?style=for-the-badge&logo=google&logoColor=white)

### Auth & Security
![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white)
![OAuth 2.0](https://img.shields.io/badge/OAuth_2.0-EB5424?style=for-the-badge&logo=auth0&logoColor=white)
![RBAC](https://img.shields.io/badge/RBAC-4A154B?style=for-the-badge&logoColor=white)

### Tools & Platforms
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white)

### CS Fundamentals
`Data Structures & Algorithms` · `Object-Oriented Programming` · `Operating Systems` · `DBMS` · `Computer Networks`

</div>

---

## 📊 GitHub Analytics

<div align="center">

<img height="180" src="https://github-readme-stats.vercel.app/api?username=krrishrastogi05&show_icons=true&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=58A6FF&icon_color=58A6FF&text_color=c9d1d9&ring_color=58A6FF" alt="GitHub Stats"/>
<img height="180" src="https://github-readme-stats.vercel.app/api/top-langs/?username=krrishrastogi05&layout=compact&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=58A6FF&text_color=c9d1d9&langs_count=8" alt="Top Languages"/>

<br/><br/>

<img width="600" src="https://github-readme-streak-stats.herokuapp.com?user=krrishrastogi05&theme=github-dark-blue&hide_border=true&background=0D1117&ring=58A6FF&fire=58A6FF&currStreakLabel=58A6FF" alt="GitHub Streak"/>

<br/><br/>

<!-- Activity Graph -->
<img width="800" src="https://github-readme-activity-graph.vercel.app/graph?username=krrishrastogi05&theme=github-compact&hide_border=true&bg_color=0d1117&color=58A6FF&line=58A6FF&point=c9d1d9&area=true&area_color=58A6FF" alt="Contribution Graph"/>

</div>

---

## 📈 LeetCode Stats

<div align="center">

<img height="200" src="https://leetcard.jacoblin.cool/godsownsoldier?theme=dark&font=Fira%20Code&ext=heatmap&border=0&radius=20" alt="LeetCode Stats"/>

<br/><br/>

| 🏷️ Metric | 📊 Value |
|:---|:---|
| **Rating** | `1900+` Knight |
| **Global Rank** | Top **5%** |
| **Profile** | [leetcode.com/godsownsoldier](https://leetcode.com/u/godsownsoldier) |

</div>

---

## 🎓 Education

```
┌─────────────────────────────────────────────────────────────┐
│  🏫  Birla Institute of Technology, Mesra                   │
│  📘  B.Tech in AI & Machine Learning                        │
│  📊  CGPA: 8.7 / 10.0  ·  2023 — Present                  │
│  📍  Ranchi, Jharkhand                                      │
├─────────────────────────────────────────────────────────────┤
│  🏫  CBSE Board, Sitapur, Uttar Pradesh                     │
│  📘  Class XII — 93.0%  ·  Class X — 94.2%                 │
└─────────────────────────────────────────────────────────────┘
```

---

## 💼 Experience

**Software Engineering Intern** · P2P Connect *(Remote)*
`Jun 2024 — Jul 2024`

- Improved AI-driven matchmaking algorithm accuracy by **28%** through structured requirement analysis and iterative model evaluation
- Identified and documented **50+ functional bugs**, strengthening platform reliability
- Authored technical documentation for **10+ core platform features**

---

## 🤝 Leadership

**Student Alumni Relations Coordinator** · BIT Mesra *(2023 — Present)*

Organized networking events with **75+ industry professionals**, facilitating **40+ mentorship connections** and onboarding **50+ alumni** to the official BIT Mesra portal.

---

<div align="center">

### 🌍 Open Source Contributor at [United Nations — OICT](https://unite.un.org/technologies)

<br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0d1117&height=100&section=footer" width="100%"/>

<br/>

**If you build systems that scale, ship AI that thinks, or hack under pressure — let's connect.**

[![LinkedIn](https://img.shields.io/badge/Let's_Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/krrish-rastogi-a41712283)
[![Email](https://img.shields.io/badge/Say_Hello-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:krrishrastogi00@gmail.com)

</div>
