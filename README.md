<h1 align="center">Hi, I'm Andrew Bugembe 👋</h1>
<h3 align="center">Software Architect &amp; Technical Lead · Founder of <a href="https://2-29-199-108.sslip.io/">Kazi Platform</a></h3>

<p align="center">
  📍 Kampala, Uganda · 🌍 Open to remote and on-site leadership roles
</p>

<p align="center">
  <a href="mailto:andebugembe17@gmail.com"><img src="https://img.shields.io/badge/Email-andebugembe17%40gmail.com-0F2A4A?style=flat&logo=gmail&logoColor=white" alt="Email"></a>
  <a href="https://wa.me/256780549732"><img src="https://img.shields.io/badge/WhatsApp_(Business)-%2B256_780_549_732-25D366?style=flat&logo=whatsapp&logoColor=white" alt="WhatsApp Business"></a>
  <a href="https://2-29-199-108.sslip.io/"><img src="https://img.shields.io/badge/Kazi_Platform-Live-1D4ED8?style=flat&logo=googlechrome&logoColor=white" alt="Kazi Platform"></a>
</p>

---

## 🧭 About me

I'm a software architect and hands-on technical leader with **10+ years** of experience building distributed, event-driven and financial systems. My work runs from core banking and mobile-money rails to a multi-tenant SaaS platform that I founded and run in production.

I take products from a blank page to a live service, covering domain modelling, system architecture, security, delivery pipelines and go-to-market. I'm strongest where software meets **money and regulation**: double-entry accounting, statutory tax and payroll compliance, payments and ISO 8583 integrations.

- 🏗️ Currently building **[Kazi Platform](https://2-29-199-108.sslip.io/)**, a business software suite for East African SMEs
- 🎯 Looking for **lead technical roles**: Tech Lead, Software Architect, Principal Engineer, Engineering Lead
- 🤝 Years of remote work across time zones, mentoring engineers and turning messy business rules into simple, testable designs

---

## 🚀 Kazi Platform: what I'm building

**Software Architect & Founder · May 2025 – Present**

Kazi Platform is a multi-tenant SaaS suite. One sign-in opens a Google-style app launcher, and each paid app is unlocked separately.

| App | What it does | Status |
|---|---|---|
| **Kazi Books** | Accounting, inventory, CRM & sales, payroll | ✅ Live |
| **Kazi Retail** | Offline-first point of sale (Windows desktop) | ✅ Live |
| **Kazi Hospitality** | Restaurants, bars and rooms, hub-and-station on the LAN | 🛠️ In development |

**Highlights**

- **Platform architecture:** .NET Aspire (AppHost, API service, web host); ASP.NET Core Minimal APIs behind Blazor Server + MudBlazor desks; PostgreSQL with EF Core and Unit of Work repositories; Redis for sign-in state and Data Protection keys.
- **Accounting engine:** double-entry posting built on a template-method base with 11 voucher strategies. Handles Uganda VAT 18% and withholding tax 6% line by line, plus ledger mapping and stock movements. An end-to-end acceptance test matrix keeps it correct.
- **Security & multi-tenancy:** authentication and role-based access without a managed identity provider. Roles are scoped to branches, each tenant sets its own posting rights (post vs draft), staff join by owner invitation only, and platform admin requires two-factor sign-in.
- **Subscription & billing engine:** trials (one per tax ID and email), anniversary billing, grace periods, read-only lockout and audited overrides. Pricing is driven by configuration.
- **Offline-first desktop apps:** a WPF + SQLite till that keeps selling offline and syncs to Books through an outbox. It has PIN sign-in, USB, network and Bluetooth receipt printers chosen in settings, and contract tests that fail when the API drifts.
- **Statutory payroll (in design):** PAYE with annualisation of irregular pay, NSSF and LST held as dated, editable rate tables; EFT/RTGS bank files and statutory exports.
- **Lean DevOps:** Docker Compose behind Caddy (automatic TLS) on Hetzner Ubuntu, secrets in environment variables, one-command scripted deploys and Inno Setup installers. Zero licence cost.

---

## 🛠️ Tech stack

**Languages & frameworks**

![C#](https://img.shields.io/badge/C%23-512BD4?style=flat&logo=dotnet&logoColor=white)
![.NET](https://img.shields.io/badge/.NET_8+-512BD4?style=flat&logo=dotnet&logoColor=white)
![ASP.NET Core](https://img.shields.io/badge/ASP.NET_Core-5C2D91?style=flat&logo=dotnet&logoColor=white)
![Blazor](https://img.shields.io/badge/Blazor-512BD4?style=flat&logo=blazor&logoColor=white)
![WPF](https://img.shields.io/badge/WPF-0078D4?style=flat&logo=windows&logoColor=white)
![Java](https://img.shields.io/badge/Java_(Spring_Boot)-6DB33F?style=flat&logo=springboot&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)
![Angular](https://img.shields.io/badge/Angular-DD0031?style=flat&logo=angular&logoColor=white)

**Data & messaging**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=flat&logo=microsoftsqlserver&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat&logo=sqlite&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=flat&logo=rabbitmq&logoColor=white)
![Azure Service Bus](https://img.shields.io/badge/Azure_Service_Bus-0078D4?style=flat&logo=microsoftazure&logoColor=white)
![AWS SQS](https://img.shields.io/badge/AWS_SQS-FF4F8B?style=flat&logo=amazonsqs&logoColor=white)

**Cloud, DevOps & observability**

![.NET Aspire](https://img.shields.io/badge/.NET_Aspire-512BD4?style=flat&logo=dotnet&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Caddy](https://img.shields.io/badge/Caddy-1F88C0?style=flat&logo=caddy&logoColor=white)
![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=flat&logo=ubuntu&logoColor=white)
![Hetzner](https://img.shields.io/badge/Hetzner-D50C2D?style=flat&logo=hetzner&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat&logo=microsoftazure&logoColor=white)
![AWS Lambda](https://img.shields.io/badge/AWS_Lambda-FF9900?style=flat&logo=awslambda&logoColor=white)
![TeamCity](https://img.shields.io/badge/TeamCity-000000?style=flat&logo=teamcity&logoColor=white)
![Datadog](https://img.shields.io/badge/Datadog-632CA6?style=flat&logo=datadog&logoColor=white)

**Fintech & compliance:** double-entry accounting · Uganda VAT/WHT · PAYE/NSSF/LST payroll · core banking (CBS) · ISO 8583 · Open Banking APIs · MTN & Airtel Mobile Money · KYC/onboarding

---

## 💼 Experience

| Role | Company | Period |
|---|---|---|
| **Software Architect & Founder** | [Kazi Platform](https://2-29-199-108.sslip.io/), Kampala | May 2025 – Present |
| **Senior Software Engineer** | TrainerRoad, LLC, Reno, NV (Remote) | Oct 2021 – Apr 2025 |
| **Senior Software Engineer** | Huguso (U) Limited (Remote) | Oct 2020 – Oct 2021 |
| **Senior Software Engineer** | Emata Uganda Limited, Kampala | Jul 2019 – Nov 2021 |
| **Software Engineer** | Neptune Financial Software, Kampala | Oct 2016 – Jun 2019 |

<details>
<summary><b>Show details for each role</b></summary>

#### TrainerRoad, LLC: Senior Software Engineer
- Optimized distributed systems serving a global user base, using microservices patterns and API-gateway architecture.
- Led the migration of legacy .NET Framework 4.8 web code to .NET 8.
- Ran CI/CD in TeamCity, reaching **95% test coverage** and cutting **deployment errors by 20%**.
- Used Azure (WebJobs, Storage, SQL Server) for high-volume data processing.
- Delivered performance-focused React/Angular apps on .NET APIs with a team spread across time zones.

#### Huguso (U) Limited: Senior Software Engineer
- Maintained event-driven Spring Boot microservices on AWS Lambda and SQS for a solar fintech platform.
- Optimized payment processing for device down-payments and instalments through to full ownership transfer.
- Kept payment state consistent across services, with structured logging across thousands of devices.

#### Emata Uganda Limited: Senior Software Engineer
- Led event-driven fintech development on Azure Service Bus and serverless Azure Functions.
- Integrated Twilio WhatsApp chatbots and MTN/Airtel Mobile Money, cutting **customer response times by 30%**.
- Designed ETL pipelines in Azure Data Factory and built full-stack .NET/React apps.

#### Neptune Financial Software: Software Engineer
- **Core banking:** CIF, automated KYC/onboarding, and Account, Card and General Ledger modules.
- **ISO 8583:** ATM gateways into the Orbit-R CBS for FINCA and Salaam Bank.
- **Payments:** Mobile Money into Orbit-R for Hofokam; Agent Banking into the Profits CBS for Centenary Bank; Open Banking APIs for third-party fintechs.

</details>

---

## 🎓 Education & certifications

- **BSc. Software Engineering**, Makerere University (2012–2016): Second Class Honours (Upper Division), CGPA 3.99
- **React Developer Nanodegree**, Udacity (2021): [verify](https://confirm.udacity.com/DRNXLPVA)
- **Object-Oriented Programming in Java**, Coursera / UC San Diego (2016): [verify](https://www.coursera.org/account/accomplishments/verify/8YF48MJJTZB7)

---

## 📊 GitHub stats

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=magherita&show_icons=true&hide_border=true&theme=default" alt="GitHub stats">
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=magherita&layout=compact&hide_border=true" alt="Top languages">
</p>

<p align="center"><i>Most of my recent work is in private repositories. Happy to walk through architecture and code in an interview.</i></p>
