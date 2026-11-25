<p align="center">
  <img src="assets/banner.png" alt="Jose AM Talavera — Software that runs companies, with a human in charge" />
</p>

<h3 align="center">Founder @ BeWorking &amp; Globaltechno OÜ · Building <a href="https://globaltechno.io">maarja.ai</a>, an AI agent that runs a company's operations</h3>

<p align="center">
  <a href="https://globaltechno.io"><img src="https://img.shields.io/badge/globaltechno.io-0b0d10?style=for-the-badge&logo=googlechrome&logoColor=white" alt="globaltechno.io" /></a>
  <a href="https://be-working.com"><img src="https://img.shields.io/badge/BeWorking-0e0e0c?style=for-the-badge&logo=rocket&logoColor=4fd66a" alt="BeWorking" /></a>
  <a href="https://www.linkedin.com/in/jose-am-talavera-5346391/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <img src="https://img.shields.io/badge/Tallinn%2C%20Estonia-1e3a8a?style=for-the-badge&logo=googlemaps&logoColor=white" alt="Tallinn, Estonia" />
</p>

---

### 👋 About me

I build software and run the businesses it serves.

I spent the first part of my career on the operating side: **8 years running operations for a 15-hotel group (€17M turnover)**, then founding **WebRentals**, a B2B distribution platform for short rentals, and **manaager.com**, a channel manager for holiday rentals that I sold in 2023.

Today I design, build and operate **[BeWorking](https://be-working.com)**, a multi-tenant SaaS for coworking spaces running in production on AWS, and I'm building **maarja.ai** at **[Globaltechno OÜ](https://globaltechno.io)**. Currently studying Computer Science at IU International University.

---

### 🚀 What I'm building

| | |
|---|---|
| ◎ **maarja.ai** · *early access* | An AI agent that runs a company's daily operations in the tools it already uses, with a human in charge of what matters. Every action is logged; payments wait for a human yes. |
| ⛨ **gtID** · *in development* | The delegation layer under Maarja: each process has an authority level (D0–D4), starting at suggest-only and climbing only on evidence. |
| ▣ **BeWorking** · *live* | Coworking and virtual office in Málaga, on a platform I designed and build. Maarja's first company. |

#### BeWorking platform

```mermaid
flowchart LR
    U([Customers & operators]) --> W[Web apps<br/>React · Next.js]
    W --> API[Core API<br/>Java 17 · Spring Boot]
    API --> DB[(PostgreSQL<br/>RDS · Flyway)]
    API --> PAY[Payments service<br/>Python]
    PAY --> S[Stripe<br/>subscriptions · SEPA · webhooks]
    API --> M[Email<br/>Amazon SES]
    subgraph AWS [AWS · ECS Fargate]
      W
      API
      PAY
    end
    GH[GitHub Actions<br/>tests → OIDC deploy] -.-> AWS
```

- **Billing:** Stripe subscriptions, SEPA debits, invoices and credit notes, daily payment reconciliation
- **Compliance:** EU VAT rules per customer type, accounting sync
- **Access:** building door keys tied to active subscriptions
- **Delivery:** six services on ECS Fargate, test-gated CI/CD, least-privilege deploys

---

### 🧭 Career

| Years | Role |
|---|---|
| 2020 – today | **Founder**, BeWorking (Málaga) · **Founder**, Globaltechno OÜ (Tallinn) |
| 2018 – 2023 | **Founder**, manaager.com: channel manager for holiday rentals in Spain, *sold in 2023* |
| 2012 – 2018 | **Founder**, WebRentals: B2B distribution for short rentals |
| 2004 – 2012 | **Operations Manager**, MF Turiscontrol (Grupo Summa Hoteles): 15 hotels, €17M turnover |

---

### 🧰 Tech stack

<p>
<img src="https://img.shields.io/badge/Java%2017-ED8B00?style=flat-square&logo=openjdk&logoColor=white" />
<img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white" />
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" />
<img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" />
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" />
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
<img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white" />
<img src="https://img.shields.io/badge/ECS%20Fargate-FF9900?style=flat-square&logo=amazonecs&logoColor=white" />
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
<img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" />
<img src="https://img.shields.io/badge/Stripe-635BFF?style=flat-square&logo=stripe&logoColor=white" />
<img src="https://img.shields.io/badge/Claude%20API-D97757?style=flat-square&logo=anthropic&logoColor=white" />
</p>

---

### 📫 Let's talk

Reach me on **[LinkedIn](https://www.linkedin.com/in/jose-am-talavera-5346391/)** or through **[globaltechno.io](https://globaltechno.io)**.
