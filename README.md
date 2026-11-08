# Awesome API Mocking & Service Virtualization [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of awesome API mocking, service virtualization, and stubbing tools, frameworks, and SaaS platforms.

---

## Sector Overview & Market Dynamics

The dedicated API mocking software market is valued at approximately **$100M+**, while the broader service virtualization market stands at **~$1.1B** (projected to reach **$2.27B by 2030** at ~17.4% CAGR). The market exhibits **moderate fragmentation with tiered concentration**: enterprise service virtualization and full API lifecycle management are dominated by established incumbents (Postman, SmartBear), while developer-first mocking tools remain competitive and fragmented across specialized SaaS offerings and popular open-source engines.

---

## SaaS & Commercial Platforms

| Product | Company Size / Valuation | Starting Paid Tier Pricing | Free Tier / Trial Limit | Key Features |
|---|---|---|---|---|
| **[Postman](https://www.postman.com/)** | **$5.6B Valuation** (~$313M+ ARR) | **$9/month** (Solo, billed annually) or **$19/user/month** (Team, billed annually) | **Forever Free**: Unlimited mock server calls; limited to 1 user seat | Full API lifecycle suite, integrated workspace mock servers, Postbot AI, collection runners. |
| **[SmartBear ReadyAPI](https://smartbear.com/product/ready-api/api-virtualization/)** | **$1.8B–$2B Valuation** (~$150M+ ARR) | **$1,270/year** (Fixed / Named user license for Virtualization module) | **14-day Free Trial**: Full access to Pro features; no credit card required | Enterprise-grade multi-protocol service virtualization, automated assertions, CI/CD pipelines. |
| **[Apidog](https://apidog.com/)** | **Bootstrapped / Private** (Mid-tier SaaS, undisclosed valuation) | **$9/user/month** (Basic, billed annually at $108/user/year) | **Forever Free**: Up to 4 users, unlimited mock calls & test runs; limited project sprint branches | All-in-one API design, dynamic smart mocking based on JSON Schema/faker rules, automated testing. |
| **[Beeceptor](https://beeceptor.com/)** | **Bootstrapped / Private** (<$50M revenue, lean indie team) | **$10/month** (Individual tier) | **Forever Free**: 50 requests/day, 3 mock rules/endpoint, 50 JSON storage objects; public endpoints (unclaimed deleted after 30 days, claimed retained 90 days) | Zero-setup instant mock endpoints, request routing, HTTP inspection, webhook debugging, proxying. |
| **[Mockoon Pro](https://mockoon.com/)** | **Bootstrapped / Indie** (OSS-backed, minor accelerator grants) | **€10/license/month** (Team plan, billed annually at €120/license/yr; min. 5 licenses = €50/mo) | **14-day Free Trial** for Pro; *(Core Mockoon desktop/CLI application is 100% free & open source under MIT)* | Real-time team collaboration, remote self-hosted mock deployment via Docker, role-based access control. |

---

## Open-Source Mocking & Virtualization Engines

| Project | License | Stars | Description |
|---|---|---|---|
| **[WireMock](https://wiremock.org/)** | Apache-2.0 | ~7,100 | Industry standard HTTP mock server with 5–6M downloads/month; runs as standalone JAR, Docker container, or embedded in Java. |
| **[Mockoon](https://mockoon.com/)** | MIT | ~8,500 | Fast, zero-configuration desktop GUI and CLI tool for local mock REST APIs; completely free for local usage. |
| **[Stoplight Prism](https://stoplight.io/open-source/prism)** | Apache-2.0 | ~3,400 | CLI-based HTTP mock server driven by OpenAPI v2/v3 documents; generates dynamic mocks and validates contract schemas. *(Note: Watch supply-chain signals as recent builds lack signed releases).* |
| **[Microcks](https://microcks.io/)** | Apache-2.0 | ~2,000 | CNCF incubating cloud-native service mocking and contract testing platform supporting REST, GraphQL, gRPC, and asynchronous event APIs (Kafka, WebSocket). |
| **[Mountebank](http://www.mbtest.org/)** | MIT | ~2,100 | Multi-protocol open-source service virtualization tool with native support for HTTP, HTTPS, TCP, and SMTP. |

---

## License

Distributed under the MIT License.
