# Christian Scherer

**Enterprise Integration & Automation Architect** — I connect legacy systems, cloud services, and AI, then automate the work around them.

[christianscherer.dev](https://christianscherer.dev) · Kansas City → Brighton / Greater London, UK · US/UK dual citizen

---

## What I do

I design the integration and automation layer between systems that were never meant to talk to each other. A decade in enterprise IT, including eight years at Burns & McDonnell, where I automated enterprise and M365 processes through ServiceNow, Azure and PowerShell: access and licensing changes, IP-address management, backup and restore, and the supporting data workflows around them. Examples include EfficientIP pool reservations, Revit server and ImaginIT Clarity automation, employee name changes, manager access to departed employees' files after termination, and ArcGIS backup and restore in Azure. Those changes removed hundreds of administrative hours a year and replaced hand-run processes with documented, supported services.

Now at Murphy-Hoffman, I bridge IBM i (RPGLE/CL) business systems to Azure-hosted Python and .NET services: defining interfaces with stakeholders, replacing manual workflows, and keeping production integrations observable and recoverable.

The through-line is architecture, not just code: understand the process, design the interfaces and controls, then build the smallest system that stays supportable.

## Selected work

- **Enterprise Integration & Automation** — enterprise and M365 process automation through ServiceNow, Azure and PowerShell, including EfficientIP pool reservations, access and licensing workflows, backup and restore, and OAuth/REST integrations.
- **IBM i ↔ Azure Integration Bridge** — production integration between RPGLE/CL business logic and Azure-hosted Python/.NET services.
- **OP-E Console / Secure-Term** — an end-to-end encrypted AI operations console and browser terminal: TypeScript/React, Python, AES-GCM/WebCrypto, SSH/tmux, cost analytics, monitoring, recall, model routing, and a supervised remote-desktop gateway, behind Cloudflare Access with backups and recovery runbooks.
- **Career Automation Stack** — self-hosted job and contract pipeline on n8n, NocoDB/PostgreSQL, and FastAPI; evidence-based fit scoring, ATS-safe résumé generation, and a human in control of every application.
- **Agent-Test & Command Deck** — disposable-container verification for static, unit/API/UI, and hardcoded-value checks; plus a config-driven Docker control plane with health probes, guarded actions, and Cloudflare Access.
- **Zero Trust Self-Hosted Platform** — Linux/Docker platform published only through Cloudflare Zero Trust tunnels, with identity-aware access, monitoring, alerting, backups, and disaster-recovery runbooks.
- **Local AI Deliberation Council** — local models answer independently, cross-examine in blind-labelled rounds, and a separate judge reads the verdict. Runs entirely on owned hardware via Ollama.

## What you'll find here

| Repo | What it is | Why it's interesting |
|---|---|---|
| [scherer-api](https://github.com/cscherer1/scherer-api) | ASP.NET Core 9 REST API | Production API with JWT auth, BCrypt, FluentValidation, and rate-limited login |
| [scherer-site](https://github.com/cscherer1/scherer-site) | React 19 + TypeScript SPA | The portfolio frontend; JWT held in memory only, with an admin portal |
| [trackfolio](https://github.com/cscherer1/trackfolio) | Java 21 + Spring Boot app tracker | The foundation of the job-search stack — search, filters, sorting, real tests |

Most of the operations work (Secure-Term, OP-E Console, JobDashboard, Contract Radar, Command Deck, Agent-Test, Command Center) is in private repos; the live results are linked above.

## How I operate

- **Self-healing by default.** Health and CPU watchdogs, queue janitors, dead-man freshness checks, port guards, and nightly appdata backups mirrored across drives.
- **Verification over vibes.** Agent-Test runs static analysis, unit/API/UI checks, and hardcode scans in disposable containers; merges wait on a green gate. I develop with OpenCode and DeepSeek under the same gates as any human change.
- **Encrypted by default.** An end-to-end encrypted terminal and console (AES-GCM, SSH, tmux), Cloudflare Access in front of every UI, encrypted backups, and a sanitized DR repo with a host-detecting bootstrap and rebuild runbooks.
- **Reproducible laptop.** A private sync repo manages the OpenCode config, wrappers, tmux shim, and launchers with a five-minute pull/apply.

## Outside the code

- Burns & McDonnell: IT support → ServiceNow automation → software development
- Murphy-Hoffman: Programmer/Analyst, IBM i middleware + Azure/.NET integration
- BS Computer Science, Southern New Hampshire University — Summa Cum Laude, 4.0 GPA, Distinguished Scholar Award, earned while working full time
- I build tools for my hobbies too — game mod load-order management and Steam workshop tooling — because the automation habit does not turn off

## Tech I live in

IBM i / RPGLE · CL · Profound UI · Python · SQL · JavaScript · TypeScript · React · .NET / C# · Azure · ServiceNow · Microsoft 365 · EfficientIP · ArcGIS · FastAPI · Docker · n8n · PostgreSQL · LLM / Ollama · Whisper STT · Kokoro / Piper / eSpeak TTS · OpenCode · DeepSeek · Cloudflare Zero Trust · Cloudflare Access · Kasm · Uptime Kuma · ntfy · Cron/systemd automation · Linux

## Get in touch

Reach me through [christianscherer.dev](https://christianscherer.dev) — I am open to Enterprise Integration Architect, Solutions Architect, Automation Architect, and Forward Deployed Engineer roles. Always glad to compare notes in writing about integration, automation, or applied AI.
