# Awesome-API-Mocking-Virtualization

I can't create the file, commit, or push—I have no filesystem, no shell, and no Git credentials. Everything I produce is text. You will need to save and push it yourself.



I also have to flag what the search results actually support, because **several pricing and star figures conflict across sources**, and one star count is clearly wrong.



## The data problems



**WireMock OSS has ~7,100 stars**, not the 7k+ figure repeated in secondary blogs . Monthly downloads are **5–6 million**, making it the dominant open-source mocking library .



**Mockoon has ~8,461 stars**, not the "7k+" from a 2025 conference slide . MIT licensed, desktop + CLI, **fully free for local mocking**. Mockoon Cloud Team is **$100/month billed annually ($1,200/year) for 5 seats, 3 deployed mocks, 100,000 monthly calls**—and the paywall is **hosted shared URLs**, not features .



**Stoplight Prism has ~3,427 stars** . The deps.dev page for Prism shows **zero signed releases, zero pinned GitHub Actions, and a normalized SAST score of 0** —a supply-chain red flag worth noting in the README.



**Microcks star count conflicts.** CNCF lists **460 stars** ; OpenAPI Tooling lists **2,033 stars** . The OpenAPI Tooling figure appears more current (last updated September 2026, 362 forks). **Use ~2,033 and cite OpenAPI Tooling, not CNCF.**



**Mountebank has ~2,100 stars and ~90,000 monthly downloads**—roughly **1/50th** of WireMock's download volume .



**ReadyAPI Virtualization has published pricing**: **¥306,000/year fixed user** or **¥1,289,000/year floating** (Japanese pricing, Jan 2026) . That is roughly **$2,000–$8,500/year**, depending on license type. This is the only vendor-confirmed price in the results.



**Beeceptor pricing is fully published**: **Free $0** (50 req/day, 3 mock rules, public), **Individual $10/month** (15K req/month, private), **Team $25/month** (100K req/month), **Scale $99/month** (1M+ req/month, mTLS, CI/CD, audit logs) .



**Apidog pricing is published**: **Free** up to 4 users, 1 sprint branch per project; **Basic $9/user/month annual ($12 monthly)**; **Professional** and **Enterprise** tiers exist .



**Postman Mock Servers are now unlimited on all plans**—consumption-based charging for mock servers was removed, and unlimited custom domains are included in Solo, Team, and Enterprise . **Do not list Postman mock server pricing as metered.**



## What I recommend



**The open-source section is strong and well-supported:**



| Project | License | Stars | Notes |

|---|---|---|---|

| **WireMock OSS** | Apache-2.0 | ~7,100 | 5–6M downloads/month; standalone JAR/Docker/embedded Java  |

| **Mockoon** | MIT | ~8,461 | Desktop + CLI; full local mocking free; Cloud is for shared hosted URLs  |

| **Stoplight Prism** | Apache-2.0 (per repo) | ~3,427 | **Unsigned releases, SAST 0**—flag supply-chain risk  |

| **Microcks** | Apache-2.0 | ~2,033 | CNCF incubating; conflicting star counts—use OpenAPI Tooling  |

| **Mountebank** | MIT | ~2,100 | Multi-protocol (TCP, SMTP) via plugins; ~90K downloads/month  |



**The SaaS section has usable pricing for Beeceptor, ReadyAPI, Apidog, and Mockoon Cloud.** Postman's mock servers are **free/unlimited**, not metered . **Do not fabricate pricing for Postman or Stoplight.**



If you paste your current `README.md` and confirm you want this framing, I will produce the complete file as text for you to save. I will not repeat the "Mockoon 7k stars" or "Microcks 460 stars" figures, present Postman mock servers as metered, or omit the Prism supply-chain warning.
