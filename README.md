# Tyler Iverson

**Full-stack engineer · Platform, integrations, and production systems**  
La Crosse, Wisconsin

I build and operate software end to end: architecture, APIs, front ends, cloud infrastructure, and testing. I lead engineers while staying hands-on, with a focus on reliable systems, clear ownership, and practical improvements for the people using them.

## What I’m building

I’m the founding engineer and engineering lead at **ABC Amplified**, a multi-tenant real estate SaaS platform. I led its development from the first commit through production, beginning at Castle Realty before the platform became its own company.

- [ABC Amplified](https://abcamplified.com) — the platform
- [Online Castles](https://onlinecastles.com) — a production tenant

My work includes:

- **Full-stack delivery:** a Laravel API, a Vue 3 front end with server-side rendering, and containerized AWS infrastructure.
- **Data integrations:** ingesting roughly 50,000 listings from two MLS providers on an integration built for three, reconciling inconsistent schemas, and deduplicating overlapping records.
- **Access control:** tenant isolation, authentication, and authorization boundaries for shared listings and private records.
- **Platform administration:** leading the team behind an admin portal for connecting MLS providers, configuring display-compliance rules, and choosing which brokerages receive each feed.
- **Legacy modernization:** maintaining an existing PHP application while building and deploying its replacement.

## How I work

I use Claude Code daily for planning, implementation, refactoring, review, and test generation. I scope agents to specific tasks, coordinate changes across the front end and back end, and review the resulting code myself. **Agents draft; I own what merges.**

I pay particular attention to code that looks correct in isolation but fails at system boundaries. My testing work includes Pest tests against real databases and Redis, Vitest component and store tests, and Playwright browser tests. For regression tests, I check that they expose the original failure as well as pass with the fix.

I also mentor engineers, establish review standards, and use production logs and query analysis to investigate failures and performance issues.

## Technologies

- **Application development:** PHP, Laravel, JavaScript, Vue 3
- **Data and background processing:** MySQL, MongoDB, Redis, Laravel Horizon
- **Infrastructure:** AWS ECS/Fargate, RDS, S3, CloudFront, Docker, Nginx
- **Testing:** Pest, Vitest, Playwright
- **Additional experience:** C#, ASP.NET Core, Python, VB.NET, SQL Server

## About the code here

Most of my recent professional work lives in private company repositories. The product links above provide public context for that work; I’m happy to discuss architecture decisions, testing approaches, and implementation tradeoffs without sharing proprietary code.

## Connect

[LinkedIn](https://www.linkedin.com/in/tyler-iverson) · [Email](mailto:tivy1996@gmail.com)
