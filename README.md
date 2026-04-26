# Md Imran Khan

**Senior Software Engineer I** at **Brain Station 23** — Dhaka, Bangladesh

I build enterprise .NET / Angular systems for international clients by day, and multi-service distributed platforms on my own time. Three years at Brain Station 23, four delivered products across insurance, law enforcement, and logistics.

## At work — Brain Station 23 · since July 2022

Each line is a real product I've shipped or am actively shipping for clients:

| Project | Client | Domain | Stack | Timeframe |
|---|---|---|---|---|
| **Law Enforcement Case Management System** | Stella International (USA) | Case & evidence tracking for LE | ASP.NET Core, ASP.NET MVC, EF Core, SQL Server, Angular, XUnit, GitHub Actions CI/CD | Oct 2025 – present |
| **Invoice Management System** | Stella International (USA) | Billing & invoicing for logistics | ASP.NET Core, EF Core, SQL Server, Angular, GitHub Actions CI/CD | Jun 2025 – present |
| **Guardian Life App** | Guardian Life Insurance (BD) | Policy & claims management | ASP.NET Core, Angular, SQL Server | Sep 2024 – May 2025 |
| **Claims Integrated Care System** | MetLife (BD) | Insurance claims lifecycle | ASP.NET Core, EF Core, SQL Server, Angular | Nov 2022 – Aug 2024 |

## On the side — multi-tenant real-estate platform

A self-directed engineering project where I take the architecture as far as I want it to go:

- **Six-service .NET backend** behind a YARP API gateway — auth, property, search, file, marketing, and an interaction service for chat & notifications.
- **Multi-tenant + branch-scoped RBAC** with custom JWT claim transformation, soft-delete + audit trail across every entity, jsonb columns for flexible per-record metadata.
- **Real-time** — SignalR chat over a Redis backplane, FCM push notifications with a per-device token registry and deep-link routing into the app.
- **Live agent operations** — geolocation tracking with offline batch sync, GPS-verified visit logs, and a 7-stage CRM lead pipeline with manual-client approval workflow.
- **Three frontends** — Angular web app (admin + public listings), Flutter mobile app for agents.
- **Search** powered by Elasticsearch; background jobs on Hangfire; everything containerized with Docker.

## Public repos — fundamentals & smaller demos

- **[CQRSOrderManagement](https://github.com/iMu21/CQRSOrderManagement)** — order pipeline with a hand-rolled CQRS dispatcher (no MediatR). Built to understand what the framework actually does for you.
- **[AuthShield](https://github.com/iMu21/AuthShield)** — clean-architecture .NET 8 starter for JWT auth & identity, MediatR-based.
- **[ApiChangeTracker](https://github.com/iMu21/ApiChangeTracker)** — small console tool that hashes a Swagger doc on a schedule and only snapshots when the surface changes.
- **[Competitive-Programming](https://github.com/iMu21/Competitive-Programming)** — 1,500+ problems across LeetCode and Codeforces.
- **[CLiCSForecast](https://github.com/iMu21/CLiCSForecast)** — applying data analysis & ML over CLiCS data (Jupyter).
- **[ExpenseTracker](https://github.com/iMu21/ExpenseTracker)** — personal-finance app on ASP.NET Core MVC + EF Core + Identity.

## Stack

| Backend | Frontend | Data | Patterns / Infra |
|---|---|---|---|
| ASP.NET Core, C# | Angular, TypeScript | SQL Server, PostgreSQL | CQRS, microservices, YARP gateway |
| EF Core, MediatR | Ng-Zorro Ant Design | Redis, Elasticsearch | RabbitMQ, SignalR, FCM |
| Hangfire, Swashbuckle | RxJS | jsonb metadata | Docker, GitHub Actions, XUnit |
| Flutter (Dart) for mobile | | | Agile / Scrum |

Also Python (Jupyter) and C++ (competitive programming).

## Highlights

- **Champion** — PSTU Intra University Programming Contest, Season 2.
- **1,500+** algorithmic problems solved across LeetCode and Codeforces.
- Three-domain experience inside a single role: **insurance** (MetLife, Guardian Life), **law enforcement** (Stella International), and **logistics** (Stella International).

## Education

**B.Sc. in Computer Science & Engineering** — Patuakhali Science & Technology University · 2017 – 2022.

## Connect

[`@iMu21`](https://github.com/iMu21) on GitHub. Open to interesting backend / full-stack work.
