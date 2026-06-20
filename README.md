<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=30&duration=3000&pause=1000&color=58A6FF&center=true&vCenter=true&multiline=true&repeat=true&width=700&height=100&lines=Sayed+Herzallah;Backend+Engineer+%7C+System+Architect" alt="Typing SVG" />

<p>
  <a href="https://herzallah.me"><img src="https://img.shields.io/badge/herzallah.me-000000?style=for-the-badge&logo=About.me&logoColor=white" /></a>
  <a href="https://linkedin.com/in/sayed-herzallah"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:herzallahdeveloper@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" /></a>
</p>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:161b22,100:58a6ff&height=120&section=header" width="100%" />

</div>

## `$ whoami`

> **Backend-focused Software Engineer** specializing in **high-throughput API architectures**, **database transaction safety**, and **real-time telemetry systems**. I design systems that handle concurrency at scale — from InnoDB row-level locking in financial engines to full-duplex WebSocket pipelines for medical sensor data. My work sits at the intersection of **system reliability** and **performance engineering**.

---

## ⚙️ Engineering Principles

```
┌─────────────────────────────────────────────────────────────────────┐
│                                                                     │
│   → Design for failure, not just for success                        │
│   → Optimize at the query level before scaling the infrastructure   │
│   → Decouple transport from business logic — always                 │
│   → If it's not tested, it's not shipped                            │
│   → Latency is a feature, not a metric                              │
│                                                                     │
└─────────────────────────────────────────────────────────────────────┘
```

---

## 🧬 Core Architecture Stack

<table>
<tr>
<td align="center" width="140">
<img src="https://skillicons.dev/icons?i=nodejs" width="48" height="48" alt="Node.js" /><br><strong>Node.js</strong><br><sub>Runtime</sub>
</td>
<td align="center" width="140">
<img src="https://skillicons.dev/icons?i=ts" width="48" height="48" alt="TypeScript" /><br><strong>TypeScript</strong><br><sub>Type System</sub>
</td>
<td align="center" width="140">
<img src="https://skillicons.dev/icons?i=express" width="48" height="48" alt="Express" /><br><strong>Express</strong><br><sub>HTTP Layer</sub>
</td>
<td align="center" width="140">
<img src="https://skillicons.dev/icons?i=mongodb" width="48" height="48" alt="MongoDB" /><br><strong>MongoDB</strong><br><sub>Document Store</sub>
</td>
<td align="center" width="140">
<img src="https://skillicons.dev/icons?i=mysql" width="48" height="48" alt="MySQL" /><br><strong>MySQL</strong><br><sub>Relational DB</sub>
</td>
</tr>
<tr>
<td align="center" width="140">
<img src="https://skillicons.dev/icons?i=react" width="48" height="48" alt="React" /><br><strong>React</strong><br><sub>UI Framework</sub>
</td>
<td align="center" width="140">
<img src="https://skillicons.dev/icons?i=nextjs" width="48" height="48" alt="Next.js" /><br><strong>Next.js</strong><br><sub>SSR Framework</sub>
</td>
<td align="center" width="140">
<img src="https://skillicons.dev/icons?i=docker" width="48" height="48" alt="Docker" /><br><strong>Docker</strong><br><sub>Containerization</sub>
</td>
<td align="center" width="140">
<img src="https://skillicons.dev/icons?i=git" width="48" height="48" alt="Git" /><br><strong>Git</strong><br><sub>Version Control</sub>
</td>
<td align="center" width="140">
<img src="https://skillicons.dev/icons?i=postman" width="48" height="48" alt="Postman" /><br><strong>Postman</strong><br><sub>API Testing</sub>
</td>
</tr>
</table>

<details>
<summary><strong>📦 Extended Toolchain</strong></summary>
<br>

| Layer | Technologies |
|:---|:---|
| **ORM / ODM** | Sequelize (MySQL), Mongoose (MongoDB) |
| **Auth & Security** | JWT, Bcrypt, Role-Based Access Control (RBAC) |
| **Real-time** | Socket.io (WebSockets), Event-Driven Architecture |
| **API Design** | RESTful, Cursor-based Pagination, Rate Limiting |
| **Frontend** | React, Next.js, TypeScript, Tailwind CSS |
| **DevOps** | Docker, GitHub Actions, Vercel |

</details>

---

## 🏗️ Featured System Architectures

> These are production-grade systems I designed and built end-to-end — from database schema design to API deployment.

<table>
<tr>
<td width="50%" valign="top">

### 🏥 [R3aya — Medical Telemetry Engine](https://github.com/Sayed-Herzallah/R3aya-Care-System-Api)

**Problem:** Real-time EMG sensor data needed sub-second delivery to therapist dashboards with zero data loss.

**Solution Architecture:**
- Full-duplex WebSocket pipeline with automatic reconnection & heartbeat monitoring
- Decoupled transport layer from business logic for isolated unit testing
- Role-based access: Therapists, Patients, Admins with granular endpoint permissions
- Optimized MongoDB aggregation pipelines for patient analytics

`Node.js` `Socket.io` `MongoDB` `JWT` `Layered Architecture`

</td>
<td width="50%" valign="top">

### 🗺️ [Siwa — High-Concurrency Booking Engine](https://github.com/Sayed-Herzallah/Siwa-Oasis-APi)

**Problem:** Double-booking race conditions during peak tourism traffic causing financial inconsistencies.

**Solution Architecture:**
- InnoDB row-level locking with `SELECT ... FOR UPDATE` inside serializable transactions
- Eliminated 100% of double-booking incidents under concurrent load
- Multi-entity relational schema: Hotels, Transports, Tours with cross-entity availability checks
- Cursor-based pagination reducing query latency on large datasets

`Node.js` `MySQL` `Sequelize` `InnoDB Locks` `Transaction Isolation`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🌟 [Ataa — Distributed Charity Platform](https://github.com/Sayed-Herzallah/Ataa-Charity-Platform-React-TypeScript)

**Problem:** Building a production-grade donation system with full audit trails and analytical reporting.

**Solution Architecture:**
- Decoupled React/TypeScript frontend with Node.js API backend
- Immutable donation audit trail with complete transaction history
- Role-based dashboards with real-time analytics and optimized schema design
- Responsive UI with complex state management and form validation

`React` `TypeScript` `Node.js` `MongoDB` `Full-Stack Architecture`

</td>
<td width="50%" valign="top">

### 💬 [Social Graph — Real-time Feed System](https://github.com/Sayed-Herzallah/Social-Media-APi)

**Problem:** Timeline retrieval at scale with real-time messaging across concurrent connections.

**Solution Architecture:**
- Cursor-based pagination achieving sub-10ms query latency on timeline retrieval
- WebSocket-driven messaging server handling concurrent bidirectional streams
- Friendship graph with mutual-follow detection and feed personalization
- Infinite scroll with zero-offset pagination eliminating duplicate content issues

`Node.js` `Socket.io` `MongoDB` `Mongoose` `Event-Driven Architecture`

</td>
</tr>
</table>

---

## 📈 System Metrics

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=Sayed-Herzallah&show_icons=true&theme=github_dark&count_private=true&hide_border=true&bg_color=0d1117&title_color=58a6ff&icon_color=58a6ff&text_color=c9d1d9&ring_color=58a6ff" height="180px" />
&nbsp;&nbsp;&nbsp;
<img src="https://github-readme-streak-stats.herokuapp.com/?user=Sayed-Herzallah&theme=github-dark-blue&hide_border=true&background=0d1117&ring=58a6ff&fire=58a6ff&currStreakLabel=58a6ff" height="180px" />

<br><br>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=Sayed-Herzallah&theme=github-compact&hide_border=true&bg_color=0d1117&color=58a6ff&line=58a6ff&point=ffffff&area=true&area_color=58a6ff" width="95%" />

</div>

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:161b22,100:58a6ff&height=100&section=footer" width="100%" />

<sub><strong>Architected with intention. Built for production.</strong></sub>

</div>
