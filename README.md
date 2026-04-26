<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:512BD4,100:DD0031&height=180&section=header&text=Md%20Imran%20Khan&fontSize=52&fontColor=ffffff&animation=fadeIn&fontAlignY=40&desc=Senior%20Software%20Engineer%20%E2%80%A2%20Brain%20Station%2023%20%E2%80%A2%20Dhaka%2C%20BD&descSize=16&descAlignY=62" alt="banner" />

<br/>

**i build** distributed systems &nbsp;·&nbsp; **and overthink** monoliths &nbsp;·&nbsp; **and feed** three loud birds

</div>

<br/>

## Work

Three years at **Brain Station 23**, four shipped products for clients in BD and the USA.

| Project | Client | Year |
|---|---|---|
| Law Enforcement Case Management | Stella International (USA) | 2025 – present |
| Invoice Management System | Stella International (USA) | 2025 – present |
| Guardian Life App | Guardian Life Insurance (BD) | 2024 – 2025 |
| Claims Integrated Care System | MetLife (BD) | 2022 – 2024 |

`ASP.NET Core` · `EF Core` · `Angular` · `SQL Server` · `XUnit` · `GitHub Actions`

<br/>

## After-hours

A self-directed multi-tenant real-estate platform — six .NET microservices behind a YARP gateway, an Angular admin/web app, and a Flutter agent mobile app. Could it have been a monolith? Yes. Is it? No.

```mermaid
flowchart LR
    Clients["Angular Web · Flutter App"] --> Gateway["YARP Gateway"]
    Gateway --> Auth["Auth"]
    Gateway --> Property["Property"]
    Gateway --> Search["Search"]
    Gateway --> Interaction["Chat · Notify"]
    Gateway --> File["File"]
    Gateway --> Marketing["Marketing"]
    Auth & Property & Marketing --> PG[(PostgreSQL)]
    Interaction --> Redis[(Redis)]
    Search --> ES[(Elasticsearch)]

    classDef gw fill:#512BD4,stroke:#fff,color:#fff
    classDef svc fill:#1B6EC2,stroke:#fff,color:#fff
    classDef data fill:#336791,stroke:#fff,color:#fff
    class Gateway gw
    class Auth,Property,Search,Interaction,File,Marketing svc
    class PG,Redis,ES data
```

`SignalR over Redis` · `FCM with deep links` · `Hangfire` · `Elasticsearch` · `Docker`

<br/>

<div align="center">

<a href="https://github.com/iMu21"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" /></a>
&nbsp;
<a href="https://www.linkedin.com/in/md-imran-khan-b9450b194/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
&nbsp;
<a href="mailto:mdimrankhan.imu21@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>

<br/><br/>

<sub><i>~ written in Markdown · debugged in production · last patched whenever ~</i></sub>

</div>
