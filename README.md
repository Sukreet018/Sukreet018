<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,100:1f6feb&height=300&section=header&text=Sukreet%20Biswas&fontSize=76&fontColor=ffffff&fontAlignY=40&desc=Backend%20Engineer%20%C2%B7%20Distributed%20Systems%20%C2%B7%20Applied%20AI&descSize=26&descAlignY=65" width="100%" alt="Sukreet Biswas" />

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=28&pause=1500&color=1F6FEB&center=true&vCenter=true&width=900&height=60&lines=Building+scalable+microservices+in+Python+%26+Go;Serving+Transformer+models+in+production+with+FastAPI;B.Tech+CSE+(AI)+%C2%B7+Kolkata%2C+India" alt="Typing SVG" />

<br/><br/>

<a href="https://www.linkedin.com/in/sukreet-biswas-6031b3361/"><img height="42" src="https://img.shields.io/badge/LinkedIn-0d1117?style=for-the-badge&logo=linkedin&logoColor=58a6ff" alt="LinkedIn" /></a>
<a href="mailto:sukreet018@gmail.com"><img height="42" src="https://img.shields.io/badge/Email-0d1117?style=for-the-badge&logo=gmail&logoColor=58a6ff" alt="Email" /></a>
<a href="https://github.com/Sukreet018?tab=repositories"><img height="42" src="https://img.shields.io/badge/Repositories-0d1117?style=for-the-badge&logo=github&logoColor=58a6ff" alt="Repositories" /></a>
<a href="https://leetcode.com/u/ckZeMutkDL/"><img height="42" src="https://img.shields.io/badge/LeetCode-0d1117?style=for-the-badge&logo=leetcode&logoColor=58a6ff" alt="LeetCode" /></a>
<a href="https://x.com/sukreet7"><img height="42" src="https://img.shields.io/badge/X-0d1117?style=for-the-badge&logo=x&logoColor=58a6ff" alt="X" /></a>

<br/><br/>

<img height="30" src="https://komarev.com/ghpvc/?username=sukreet018&label=Profile%20Views&color=1f6feb&labelColor=0d1117&style=for-the-badge" alt="Profile views" />
<img height="30" src="https://img.shields.io/github/followers/Sukreet018?style=for-the-badge&logo=github&logoColor=58a6ff&labelColor=0d1117&color=1f6feb" alt="Followers" />
<img height="30" src="https://img.shields.io/github/last-commit/Sukreet018/Velora?style=for-the-badge&logo=github&logoColor=58a6ff&label=Last%20Commit&labelColor=0d1117&color=1f6feb" alt="Last commit" />

</div>

<br/>

## About

I am a final-year B.Tech student in Computer Science & Engineering (Artificial Intelligence) at Techno India University, Kolkata. I design and build backend systems, from event-driven microservices to production-ready ML inference services, with a focus on clean architecture, reliability and concurrency.

<div align="center">

<img src="https://skillicons.dev/icons?i=py,go,fastapi,nodejs,docker,postgres,redis,rabbitmq,pytorch,react&theme=dark&perline=10" height="64" alt="Core technologies" />

</div>

<br/>

<div align="center">

<table>
  <tr>
    <td align="center" width="25%"><h1>11</h1><b>Services</b><br/>in the Velora microservices backend</td>
    <td align="center" width="25%"><h1>20</h1><b>Goroutines</b><br/>in a concurrent Go crawler</td>
    <td align="center" width="25%"><h1>94.8%</h1><b>Accuracy</b><br/>Transformer fusion research</td>
    <td align="center" width="25%"><h1>140K+</h1><b>Samples</b><br/>used for model evaluation</td>
  </tr>
</table>

</div>

<br/>

## Focus Areas

- **Backend Engineering:** REST APIs, JWT authentication, role-based access control, API gateways, rate limiting and idempotent payment flows
- **Distributed Systems:** event-driven architecture with RabbitMQ, Redis, WebSockets and Docker-based deployment
- **Concurrency:** worker pools, channels and race-condition debugging in Go
- **Applied AI:** Transformer models for NLP, served in real time through FastAPI

<br/>

## Projects

### [Velora: Food-Delivery Microservices Backend](https://github.com/Sukreet018/Velora)

A production-style backend made of 11 deployable services (9 FastAPI, 2 Go) on PostgreSQL, Redis, RabbitMQ and SeaweedFS, running with Docker Compose behind a load-balanced Nginx gateway.

- API gateway that validates JWTs and enforces role-based, route-level authorization for customers, owners, riders and admins
- RabbitMQ workers for orders, riders, notifications and invoices, with payment idempotency keys and a Razorpay webhook
- Redis-backed rate limiter and WebSocket live-tracking service written in Go
- React and TypeScript customer and admin portals (around 17K lines of code) with live delivery maps

<img src="https://skillicons.dev/icons?i=py,fastapi,go,postgres,redis,rabbitmq,docker,nginx,react,ts&theme=dark&perline=10" height="56" alt="Velora stack" />

<br/><br/>

### [Wikipedia Graph Crawler: Concurrent Go Crawler](https://github.com/Sukreet018/web-crawler)

A concurrent crawler built around a 20-goroutine worker pool with a dynamic frontier that feeds discovered links back into the queue. It crawls 100 unique pages in 20.49 seconds (4.92 pages/sec).

- Atomic URL de-duplication using `sync.Map` and `LoadOrStore`
- Ticker-based rate limiter at 5 requests per second
- Graceful shutdown through `context` and `os/signal`, with race conditions diagnosed and fixed

<img src="https://skillicons.dev/icons?i=go,linux,git&theme=dark" height="56" alt="Crawler stack" />

<br/><br/>

### [Emotiverse: Emotion Analysis Platform](https://github.com/Sukreet018/Emotiverse)

A full-stack platform with a Node.js backend and a FastAPI inference service that serves BERT models in real time for sentiment and emotion analysis. It uses JWT authentication and MongoDB, and is currently being re-architected into FastAPI microservices (gateway, auth, user, emotion, media, notification).

<img src="https://skillicons.dev/icons?i=react,nodejs,fastapi,mongodb,py,pytorch&theme=dark" height="56" alt="Emotiverse stack" />

<br/><br/>

### TetraSense: Quad-Transformer Fusion Research

A fusion layer that combines BERT, ALBERT, ELECTRA and ERNIE for emotion classification, with optimized tokenization and output fusion. It reaches 94.8% accuracy on more than 140K samples. The paper is under review at the 7th International Conference on Frontier Technologies of Information and Computer (ICFTIC).

<img src="https://skillicons.dev/icons?i=pytorch,py,sklearn&theme=dark" height="56" alt="TetraSense stack" />
&nbsp;

<br/>

## Technical Skills

**Languages**<br/>
<img src="https://skillicons.dev/icons?i=py,go,js,ts,cpp,postgres,mysql&theme=dark" height="56" alt="Languages" />

**Backend and Frontend**<br/>
<img src="https://skillicons.dev/icons?i=fastapi,nodejs,express,react,tailwind&theme=dark" height="56" alt="Backend and frontend" />


**Databases and Messaging**<br/>
<img src="https://skillicons.dev/icons?i=postgres,mongodb,redis,rabbitmq&theme=dark" height="56" alt="Databases and messaging" />

**DevOps and Tools**<br/>
<img src="https://skillicons.dev/icons?i=docker,nginx,githubactions,git,github,linux,postman&theme=dark" height="56" alt="DevOps and tools" />

**AI and Machine Learning**<br/>
<img src="https://skillicons.dev/icons?i=pytorch,sklearn,opencv&theme=dark" height="56" alt="AI and ML" />
<img src="https://devicons.io/devicons/icons/pandas-icon.svg" height="50" />
<img src="https://devicons.io/devicons/icons/hugging-face-icon.svg" height="50"/>

<br/>

## GitHub Activity

<div align="center">

<img width="85%" src="https://streak-stats.demolab.com?user=Sukreet018&background=0D1117&ring=1F6FEB&fire=1F6FEB&currStreakNum=FFFFFF&sideNums=FFFFFF&currStreakLabel=58A6FF&sideLabels=58A6FF&dates=8B949E&stroke=30363D&border=30363D" alt="GitHub streak" />

</div>

<br/>

<br/>

## Contact

I am open to Backend Engineer and AI/ML opportunities.

**Email:** [sukreet018@gmail.com](mailto:sukreet018@gmail.com)<br/>
**LinkedIn:** [sukreet-biswas](https://www.linkedin.com/in/sukreet-biswas-6031b3361/)

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1f6feb,100:0d1117&height=120&section=footer" width="100%" alt="footer" />
