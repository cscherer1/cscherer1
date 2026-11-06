# Christian Scherer

**Full-Stack & AI Systems Engineer / Solutions Architect** — I build software, automation, and AI tooling that runs enterprises, and I make legacy and modern systems talk to each other.

[christianscherer.dev](https://christianscherer.dev) · Kansas City → Brighton, UK

---

## What I do

I have spent 8+ years building and integrating systems: IBM i / RPGLE business logic and Azure/.NET integration at Murphy-Hoffman, and before that Microsoft 365, ServiceNow, and IT systems at Burns & McDonnell. The through-line is integration and automation — replacing manual, fragile processes with explicit pipelines that can be verified and operated.

Outside work I run a self-hosted homelab (Intel NUC, Ubuntu, Docker Compose) with **52 containers** across home, career, and local-AI stacks: a full media pipeline, DNS and ad-blocking, remote access, monitoring, file and terminal tools, and local speech and LLM services. Everything is running, monitored (Uptime Kuma, **38 monitors**), and exposed through Cloudflare Zero Trust with no open inbound ports.

## What I'm building now

- **OP-E Console / Secure-Term** — an end-to-end encrypted browser terminal and AI operations console. It fronts OpenCode/DeepSeek sessions with cost analytics, a **Mind** observer feed, a read-only **Sentinel** observer (anomaly triage and advisory alerts), local **FTS5 recall** across notes/Mind/council/Sentinel history, a **four-lab model council** with triage, verification and a judge, a supervised **remote-desktop** gateway, and a live **architecture/data-flow** view.
- **JobDashboard / Career OS** — a self-hosted job-search stack: n8n orchestration, NocoDB on PostgreSQL as the system of record, JobSpy ingestion, an evidence-based skill inventory grounded in real GitHub/portfolio/LinkedIn data, LLM fit scoring, and ATS-safe resumes and cover letters from a JSON-Resume model.
- **Contract Radar** — a private contract pipeline covering discovery, review, submissions, invoices, chase-ups, and encrypted backups.
- **Command Deck** — a config-driven container control plane and **43-tool** console over the live Docker inventory, with health probes, host and container stats, and guarded actions behind Cloudflare Access.
- **Agent-Test**, **CrAM**, **Lulu**, **OP-E Voice**, and **Command Center** (a sanitized disaster-recovery rebuild repo) round out the operated stack.

## What you'll find here

| Repo | What it is | Why it's interesting |
|---|---|---|
| [scherer-api](https://github.com/cscherer1/scherer-api) | ASP.NET Core 9 REST API | Production API with JWT auth, BCrypt, FluentValidation, and rate-limited login |
| [scherer-site](https://github.com/cscherer1/scherer-site) | React 19 + TypeScript SPA | The portfolio frontend; JWT held in memory only, with an admin portal |
| [trackfolio](https://github.com/cscherer1/trackfolio) | Java 21 + Spring Boot app tracker | The foundation of the job-search stack — search, filters, sorting, real tests |

Most of the operations work (Secure-Term, OP-E Console, JobDashboard, Contract Radar, Command Deck, Agent-Test, Command Center) is in private repos; the live results are linked above.

## How I operate

- **Self-healing by default.** Kuma-to-ntfy alerts, health and CPU watchdogs, queue janitors, dead-man freshness checks, port guards, and nightly appdata backups mirrored across drives.
- **Verification over vibes.** Agent-Test runs static analysis, unit/API/UI checks, and hardcode scans in disposable containers; merges wait on a green gate. I develop with OpenCode + DeepSeek under the same gates as any human change.
- **Encrypted by default.** An E2E-encrypted terminal and console (AES-GCM, SSH, tmux), Cloudflare Access in front of every UI, encrypted backups, and a sanitized DR repo with a host-detecting bootstrap and rebuild runbooks.
- **Reproducible laptop.** A private sync repo manages the OpenCode config, wrappers, tmux shim, and launchers with a five-minute pull/apply.

## Outside the code

- 8+ years Burns & McDonnell (software developer → ServiceNow lead → IT systems) → now Full-Stack Developer & Solutions Architect at Murphy-Hoffman Company (IBM i middleware + Azure/.NET integration)
- BS Computer Science, Southern New Hampshire University — Summa Cum Laude, 4.0 GPA, Distinguished Scholar Award, earned while working full time
- I build tools for my hobbies too — game mod load-order management and Steam workshop tooling — because the automation habit does not turn off

## Tech I live in

IBM i / RPGLE · CL · Profound UI · Python · SQL · JavaScript · TypeScript · React · .NET / C# · Azure · ServiceNow · FastAPI · Docker · n8n · PostgreSQL · LLM / Ollama · Whisper STT · Kokoro / Piper / eSpeak TTS · OpenCode · DeepSeek · Cloudflare Zero Trust · Cloudflare Access · Kasm · Uptime Kuma · ntfy · Cron/systemd automation · Linux

## Get in touch

Reach me through [christianscherer.dev](https://christianscherer.dev) — I am open to Full-Stack Engineer / AI Systems Engineer / Enterprise Solutions Architect / Systems Integration roles, and always happy to talk automation.
