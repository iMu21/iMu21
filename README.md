<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:512BD4,100:DD0031&height=220&section=header&text=Md%20Imran%20Khan&fontSize=58&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Senior%20Software%20Engineer%20%E2%80%A2%20Brain%20Station%2023&descSize=18&descAlignY=60" alt="banner" />

<a href="https://github.com/iMu21">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=2800&pause=900&color=512BD4&center=true&vCenter=true&width=720&lines=Enterprise+%2ENET+by+day%2C+distributed+systems+by+night.;Building+for+MetLife%2C+Guardian+Life%2C+Stella+International.;6-service+real-estate+platform+with+Flutter+%2B+Angular.;1%2C500%2B+competitive-programming+problems+solved." alt="typing intro" />
</a>

<p>
  <img src="https://komarev.com/ghpvc/?username=iMu21&style=for-the-badge&color=512BD4&label=Profile+Views" />
  <img src="https://img.shields.io/github/followers/iMu21?style=for-the-badge&color=DD0031&label=Followers" />
  <img src="https://img.shields.io/badge/Dhaka%2C%20BD-512BD4?style=for-the-badge&logo=googlemaps&logoColor=white" />
  <img src="https://img.shields.io/badge/Open%20to%20Work-2EA44F?style=for-the-badge&logo=github&logoColor=white" />
</p>

</div>

---

### About

I build enterprise **.NET / Angular** systems for international clients by day, and a multi-service distributed real-estate platform on my own time. Three years at **Brain Station 23**, four delivered products across **insurance, law enforcement, and logistics**.

---

### Professional Work · Brain Station 23 · since July 2022

| Project | Client | Domain | Stack | Timeframe |
|---|---|---|---|---|
| **Law Enforcement Case Management** | Stella International (USA) | Case & evidence tracking | ASP.NET Core · MVC · EF Core · SQL Server · Angular · XUnit · GH Actions | Oct 2025 – present |
| **Invoice Management System** | Stella International (USA) | Billing & invoicing for logistics | ASP.NET Core · EF Core · SQL Server · Angular · GH Actions | Jun 2025 – present |
| **Guardian Life App** | Guardian Life Insurance (BD) | Policy & claims management | ASP.NET Core · Angular · SQL Server | Sep 2024 – May 2025 |
| **Claims Integrated Care System** | MetLife (BD) | Insurance claims lifecycle | ASP.NET Core · EF Core · SQL Server · Angular | Nov 2022 – Aug 2024 |

---

### After-hours Architecture · Multi-tenant Real-Estate Platform

A self-directed playground where I take the architecture as far as I want it.

```
                   ┌──────────────────── Angular Admin / Public Web ───────────────────┐
                   │                                                                    │
                   │              Flutter Agent Mobile App ←──────────┐                 │
                   │                                                  │                 │
                   ▼                                                  ▼                 │
        ┌──────────────────────────  YARP API Gateway  ──────────────────────────┐     │
        │                                                                          │     │
        ▼          ▼          ▼               ▼              ▼              ▼     │     │
   AuthService  Property   Search          Interaction      File         Marketing │
   (JWT, RBAC) Service  (Elasticsearch) (SignalR + FCM)   Service       Service   │
                                                                                   │
                            PostgreSQL · Redis · Hangfire · Docker
```

- **6-service .NET backend** behind a YARP gateway with role-aware routing and per-cluster health checks.
- **Multi-tenant + branch-scoped RBAC** with custom JWT claim transformation, soft-delete + audit trail across every entity.
- **Real-time** — SignalR chat over a Redis backplane, FCM push with a per-device token registry and deep-link routing.
- **Live agent ops** — geolocation tracking with offline batch sync, GPS-verified visit logs, 7-stage CRM lead pipeline.
- **Three frontends** — Angular web (admin + public), Flutter agent mobile app sharing the same gateway.

---

### Tech Stack

<div align="center">

**Backend**

<img src="https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white" />
<img src="https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=csharp&logoColor=white" />
<img src="https://img.shields.io/badge/ASP.NET_Core-512BD4?style=for-the-badge&logo=dotnet&logoColor=white" />
<img src="https://img.shields.io/badge/Entity_Framework-512BD4?style=for-the-badge&logo=nuget&logoColor=white" />
<img src="https://img.shields.io/badge/MediatR-CC2927?style=for-the-badge&logo=nuget&logoColor=white" />
<img src="https://img.shields.io/badge/Hangfire-D63C28?style=for-the-badge&logo=apachespark&logoColor=white" />
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />

**Frontend & Mobile**

<img src="https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white" />
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />
<img src="https://img.shields.io/badge/RxJS-B7178C?style=for-the-badge&logo=reactivex&logoColor=white" />
<img src="https://img.shields.io/badge/Ng--Zorro-1890FF?style=for-the-badge&logo=antdesign&logoColor=white" />
<img src="https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white" />
<img src="https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white" />

**Data**

<img src="https://img.shields.io/badge/SQL_Server-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white" />
<img src="https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white" />
<img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" />
<img src="https://img.shields.io/badge/Elasticsearch-005571?style=for-the-badge&logo=elasticsearch&logoColor=white" />

**Infra & Tooling**

<img src="https://img.shields.io/badge/YARP-512BD4?style=for-the-badge&logo=microsoft&logoColor=white" />
<img src="https://img.shields.io/badge/SignalR-6F2DA8?style=for-the-badge&logo=microsoft&logoColor=white" />
<img src="https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white" />
<img src="https://img.shields.io/badge/Firebase_Cloud_Messaging-FFCA28?style=for-the-badge&logo=firebase&logoColor=black" />
<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
<img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" />
<img src="https://img.shields.io/badge/XUnit-512BD4?style=for-the-badge&logo=xunit&logoColor=white" />

</div>

---

### Public Repos · Fundamentals

- **[CQRSOrderManagement](https://github.com/iMu21/CQRSOrderManagement)** — order pipeline with a hand-rolled CQRS dispatcher, no MediatR.
- **[AuthShield](https://github.com/iMu21/AuthShield)** — clean-architecture .NET 8 starter for JWT auth & identity, MediatR-based.
- **[ApiChangeTracker](https://github.com/iMu21/ApiChangeTracker)** — hashes a Swagger doc on a schedule, snapshots only when the API surface changes.
- **[Competitive-Programming](https://github.com/iMu21/Competitive-Programming)** — 1,500+ problems across LeetCode and Codeforces.
- **[CLiCSForecast](https://github.com/iMu21/CLiCSForecast)** — applying data analysis & ML over CLiCS data (Jupyter).
- **[ExpenseTracker](https://github.com/iMu21/ExpenseTracker)** — personal-finance app on ASP.NET Core MVC + EF Core + Identity.

---

### Highlights

> **Champion** — PSTU Intra University Programming Contest, Season 2.
>
> **1,500+** algorithmic problems solved across LeetCode and Codeforces.
>
> **Three-domain experience inside a single role** — insurance · law enforcement · logistics, on the same .NET stack.

---

### Off the Keyboard

When the IDE is closed: I'm probably **playing video games**, **looking after my birds**, or grinding another Codeforces round. I think hobbies are part of the engineer — pattern-spotting in a competitive programming problem and pattern-spotting in your aviary are not as different as they look.

---

### Education

**B.Sc. in Computer Science & Engineering** — Patuakhali Science & Technology University · 2017 – 2022.

---

<div align="center">

### Connect

<a href="https://github.com/iMu21"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" /></a>
<a href="https://www.linkedin.com/in/md-imran-khan-b9450b194/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
<a href="mailto:mdimrankhan.imu21@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>

<br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:DD0031,100:512BD4&height=100&section=footer" alt="footer" />

</div>
