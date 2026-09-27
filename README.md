## Hi, I'm Caner

I'm a backend developer based in Istanbul, mostly working with C# and .NET. I've spent the last five years in fintech and payments, where the code has to be right the first time because someone's money is on the other end of it.

Most of my day-to-day has been building APIs, integrating with banks and government services, and keeping message queues and caches from turning into the reason things break. Lately I've also been spending more time on the frontend side with Next.js, and I'm slowly getting into Flutter for mobile.

## What I've worked on

Over the years I've gone from writing my first production endpoints to designing and owning full services. Some of the things I've built along the way:

- KYC/AML flows and identity verification, including integration with NVI (the Turkish national identity registry)
- Bank integrations for payment and account operations
- A Logo ERP integration for an e-money company, syncing financial data between their platform and the ERP side
- Async processing with RabbitMQ and caching with Redis on services that needed to stay fast under load
- Containerizing services with Docker and working across both SQL Server and PostgreSQL

## Projects

**VasWeb** — *.NET Core*
A Direct Carrier Billing platform that works with Turkish mobile operators, letting users pay for subscriptions through their phone bill. Most of the interesting problems here were on the operator side: MSISDN header enrichment that only works over HTTP, encrypted token exchange with a PHP service, and tracking down renewal failures caused by a single misconfigured error-code mapping.

**E-Commerce Platform** — *.NET Core Web API, Next.js, PostgreSQL* (in progress)
A B2C and B2B e-commerce system split into a separate API and frontend. Uses EF Core, Serilog with Seq for logging, and a payment adapter layer so providers like PayTR can be swapped without touching the core. Marketplace integrations (Trendyol, Hepsiburada, N11) are planned for later phases.

**Sosyolobi** — *Next.js, Tailwind, MapLibre*
A location-based social platform for discovering events around you. I've been reworking the UI: a map-first layout with color-coded pins, a filterable event sidebar, and a darker, cleaner visual style.

**Live News Aggregator** — *PHP 7.4, MySQL*
A Turkish tech and finance news site that pulls from multiple sources in near real time. I deliberately built it without a framework, Composer, or Docker, just to see how far plain PHP can go. Cron-based fetching, MySQL full-text search, and long polling for live updates.

**Prayer Times App** — *Flutter* (planning)
A cross-platform mobile app for prayer times, with a choice between Diyanet data and international calculation methods. The goal is to pack in useful features without making the app feel crowded.

## Tech

**Backend:** C#, .NET Core, ASP.NET Core, Entity Framework Core, PHP, Laravel
**Data & Messaging:** SQL Server, PostgreSQL, MySQL, Redis, RabbitMQ
**Frontend:** JavaScript, Next.js, React, HTML, CSS, Tailwind
**DevOps & Tools:** Docker, Nginx, Apache, Git
**Also used:** Java, Python (NumPy, Pandas), Flutter

![C#](https://img.shields.io/badge/C%23-239120?style=flat-square&logo=csharp&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-5C2D91?style=flat-square&logo=dotnet&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL%20Server-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)

## Education

BSc in Computer Engineering, Balıkesir University (2019)

## Outside of code

I listen to music for an embarrassing number of hours a day, usually around six. When I'm stuck on a problem, I pick up the guitar instead of staring at the screen. It works more often than you'd think.

## Get in touch

I'm open to new opportunities and always happy to talk about .NET, backend architecture, or payment systems.

[LinkedIn](https://linkedin.com/in/canerelibol) · [Medium](https://medium.com/@elibol97) · [Twitter](https://twitter.com/elblcnr)

---

<p align="left">
  <img src="https://github-readme-stats.vercel.app/api?username=caner-elibol&theme=bear&include_all_commits=true&count_private=true" height="160" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=caner-elibol&theme=bear&layout=compact" height="160" />
</p>
