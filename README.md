# Md Imran Khan

Software engineer in Dhaka, Bangladesh. I build distributed backends in .NET and frontends in Angular — most of the work lives in private repos, but the snapshot below is what I do day to day.

## What I build

- **Multi-service .NET backends** — ASP.NET Core 8/10, EF Core, PostgreSQL & SQL Server, YARP API gateway, MediatR-based CQRS, Hangfire background jobs.
- **Real-time features** — SignalR chat & notifications backed by Redis, FCM push, live agent geolocation tracking with offline batch sync.
- **Multi-tenant SaaS shape** — branch-scoped RBAC with custom JWT claim transformation, soft-delete + audit trail across every entity, jsonb columns for flexible per-record metadata.
- **Angular frontends** — Angular 18+ standalone components, ng-zorro Ant Design, white-label theming.
- **Cross-cutting** — Swashbuckle / OpenAPI, FluentValidation, AutoMapper, Docker, integration & unit tests, EF migrations.

## Currently

Lead backend on a multi-tenant real-estate platform. Scope:

- 6 microservices behind a YARP gateway (auth, property, search, interaction, file, marketing) with role-aware routing and per-cluster health checks.
- Full agent CRM — leads pipeline (7 stages, BR-1 prerequisites), manual-client approval workflow, GPS-verified visit logs, commission tracking.
- Real-time chat with SignalR + Redis backplane, FCM push with per-device token registry and deep-link routing.
- Companion Flutter agent mobile app sharing the same backend through the gateway.

## Selected public work

These are smaller / older projects, but they show how I think about backend fundamentals:

- **[CQRSOrderManagement](https://github.com/iMu21/CQRSOrderManagement)** — hand-rolled CQRS dispatcher in .NET, no MediatR. Useful for understanding what the framework actually does for you.
- **[AuthShield](https://github.com/iMu21/AuthShield)** — clean-architecture starter for JWT auth + identity, MediatR-based.
- **[ApiChangeTracker](https://github.com/iMu21/ApiChangeTracker)** — small console tool that hashes a Swagger doc on a schedule and only snapshots when the surface actually changes.
- **[Competitive-Programming](https://github.com/iMu21/Competitive-Programming)** — 1,651 problems solved across LeetCode and Codeforces.

## Stack

| Backend | Frontend | Patterns / Infra |
|---|---|---|
| ASP.NET Core, C# | Angular, TypeScript | CQRS, microservices, YARP |
| EF Core, MediatR | Ng-Zorro Ant Design | RabbitMQ, Redis, SignalR |
| PostgreSQL, SQL Server | RxJS | Hangfire, Docker |

Also Python (data work in Jupyter) and C++ for competitive programming.

## Connect

Open to interesting backend / full-stack work. Reach me at [`@iMu21`](https://github.com/iMu21).
