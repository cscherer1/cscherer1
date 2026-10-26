# Christian Scherer

**Solutions Architect & Integration Engineer** — I turn messy, manual workflows into self-hosted, self-healing automation, and I make legacy and modern systems talk to each other.

🔗 [christianscherer.dev](https://christianscherer.dev) · 📍 Kansas City → Brighton, UK

---

## What I do

8+ years building and integrating systems — from IBM i / RPGLE business logic to Azure, Python, and .NET — plus my own operated homelab that runs **34 containers** across 28 services: a full self-hosted media pipeline, DNS, ad-blocking, remote access, monitoring, a FileBrowser, a WebTTY, a mesh VPN, even a Folding@home node. Nothing here is a tutorial project; everything is **running, self-hosted, and monitored** (Uptime Kuma), exposed through Cloudflare Zero Trust tunnels with **no open inbound ports** — split-horizon DNS via AdGuard Home, orchestration via Portainer, ClamAV quarantine-review and Cloudflare Zero Trust IP-sync scripts I wrote for my own stack.

**Career focus:** Enterprise Solutions Architecture · Systems Integration · Automation Engineering · ServiceNow · Azure integration · Cloudflare Zero Trust networking.

## What you'll find here

| Repo | What it is | Why it's interesting |
|---|---|---|
| [scherer-api](https://github.com/cscherer1/scherer-api) | ASP.NET Core 9 REST API | Production-deployed API with JWT auth, BCrypt, FluentValidation, rate-limited login — powers my portfolio site |
| [scherer-site](https://github.com/cscherer1/scherer-site) | React 19 + TypeScript SPA | Performance-conscious frontend with a hidden admin panel; holds the JWT in memory only |
| [trackfolio](https://github.com/cscherer1/trackfolio) | Java 21 + Spring Boot app tracker | The foundation of my job-search stack — search, filters, sorting, real tests |

**Currently building:** a fully automated, self-hosted career stack — **JobDashboard** — that replaces manual job hunting with an orchestrated pipeline: n8n orchestrates, NocoDB (on PostgreSQL 17) is the system of record, JobSpy ingests listings, an evidence-based skill inventory grounds resumes in *real* GitHub/portfolio/LinkedIn skills (not self-reported claims), and a resume renderer produces ATS-safe PDFs. It's architected around the Cloudflare 524 edge-timeout lesson: heavy work runs as background jobs that report progress instead of one long-lived request.

## The operating evidence (things I actually run and operate)

- **Home server (Intel NUC, Ubuntu 24.04 LTS + Docker Compose):** 34 containers / 28 services across three stacks — a full self-hosted media pipeline (automated acquisition, metadata, and streaming, ~10 services deep), a **local AI stack** (Ollama, my **ouroborn** agent-orchestration project: a council of local LLMs with jury/witness evaluation and blind labels so models can't anchor on each other's names — the opposite of an API-call wrapper), remote access (Cloudflare Zero Trust, meshcentral, WebTTY), platform (Portainer, Glances, Uptime Kuma, Stirling-PDF, PairDrop, FileBrowser, Homepage), and the career stack above.
- Everything is **self-hosted, terminal-first, and monitored** — I automate the things I use, and I operate the automation.

## Outside the code

- **8+ years** Burns & McDonnell (software developer → ServiceNow lead → IT systems) → **now** Full-Stack Developer & Solutions Architect at Murphy-Hoffman Company (IBM i middleware + Azure/.NET integration)
- **BS Computer Science**, Southern New Hampshire University — Summa Cum Laude, **4.0 GPA**, Distinguished Scholar Award, earned while working full time
- Designs tools for my hobbies (game mod load-order management, Steam workshop tooling) — I automate even the things I enjoy

## Tech I live in

IBM i / RPGLE · CL · Profound UI · Python · SQL · JavaScript · TypeScript · Java · .NET / C# · Azure · ServiceNow · Docker · n8n · PostgreSQL · Cloudflare Zero Trust · Linux (self-hosted everything)

## Get in touch

Reach me through [christianscherer.dev](https://christianscherer.dev) — I'm open to Enterprise Solutions Architect / Systems Integration / Automation Engineer roles, and always happy to talk automation.
