<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f172a,50:1e3a8a,100:0ea5e9&height=190&section=header&text=Jose%20AM%20Talavera&fontSize=46&fontColor=ffffff&fontAlignY=36&desc=Software%20engineer%20%C2%B7%20Founder%20of%20Globaltechno%20O%C3%9C&descAlignY=58&descSize=18" alt="Jose AM Talavera" />
</p>

<p align="center">
  <a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&duration=3000&pause=900&color=0EA5E9&center=true&vCenter=true&width=620&lines=I+design+and+ship+production+SaaS+end+to+end;Spring+Boot+%C2%B7+React+%C2%B7+AWS+%C2%B7+Stripe;Architecture+%E2%86%92+running+system+%E2%86%92+operations" alt="Typing SVG" /></a>
</p>

<p align="center">
  <a href="https://globaltechno.io"><img src="https://img.shields.io/badge/globaltechno.io-0f172a?style=for-the-badge&logo=googlechrome&logoColor=white" alt="globaltechno.io" /></a>
  <a href="https://be-working.com"><img src="https://img.shields.io/badge/BeWorking-1e3a8a?style=for-the-badge&logo=rocket&logoColor=white" alt="BeWorking" /></a>
  <a href="https://www.linkedin.com/in/jose-am-talavera-5346391/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <img src="https://img.shields.io/badge/Tallinn%2C%20Estonia-0ea5e9?style=for-the-badge&logo=googlemaps&logoColor=white" alt="Tallinn, Estonia" />
</p>

---

### 👋 About me

I take products from **architecture to running system**: backend, frontend, cloud infrastructure, and the payments and compliance plumbing in between. Computer Science background; founder of **[Globaltechno OÜ](https://globaltechno.io)**, my software studio.

Today I build and operate **[BeWorking](https://be-working.com)**, a multi-tenant SaaS for coworking spaces, running in production on AWS.

> 💼 **Available for consulting**: full-stack product development · cloud architecture · Stripe and payments integration.

---

### 🏗️ What I'm building: BeWorking

A multi-tenant platform for coworking spaces: **bookings, virtual office, invoicing, VAT compliance and access control**, delivered as six services orchestrated on AWS ECS Fargate.

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

| | |
|---|---|
| 🧾 **Billing** | Stripe subscriptions, SEPA debits, invoices and credit notes, daily reconciliation |
| 🌍 **Compliance** | EU VAT rules per customer type, accounting sync |
| 🔐 **Access** | Door keys and building access tied to active subscriptions |
| 🚀 **Delivery** | Test-gated CI, staging → production, least-privilege OIDC deploy role |

---

### 🧰 Tech stack

**Backend**<br/>
<img src="https://img.shields.io/badge/Java%2017-ED8B00?style=flat-square&logo=openjdk&logoColor=white" />
<img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white" />
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />

**Frontend**<br/>
<img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" />
<img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" />
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" />
<img src="https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white" />

**Data**<br/>
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
<img src="https://img.shields.io/badge/Flyway-CC0200?style=flat-square&logo=flyway&logoColor=white" />

**Cloud & DevOps**<br/>
<img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white" />
<img src="https://img.shields.io/badge/ECS%20Fargate-FF9900?style=flat-square&logo=amazonecs&logoColor=white" />
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
<img src="https://img.shields.io/badge/nginx-009639?style=flat-square&logo=nginx&logoColor=white" />
<img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" />

**Payments**<br/>
<img src="https://img.shields.io/badge/Stripe-635BFF?style=flat-square&logo=stripe&logoColor=white" />
<img src="https://img.shields.io/badge/SEPA%20Direct%20Debit-0052B4?style=flat-square&logo=europeanunion&logoColor=white" />

---

### 📫 Let's talk

Building a SaaS, moving it to AWS, or wiring up Stripe? Reach me on **[LinkedIn](https://www.linkedin.com/in/jose-am-talavera-5346391/)** or through **[globaltechno.io](https://globaltechno.io)**.

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0ea5e9,50:1e3a8a,100:0f172a&height=110&section=footer" alt="" />
</p>
