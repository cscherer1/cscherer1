# Christian Scherer

**Full-Stack & AI Systems Engineer / Solutions Architect** — I build software, automation, and AI tooling that runs enterprises, and I make legacy and modern systems talk to each other.

🔗 [christianscherer.dev](https://christianscherer.dev) · 📍 Kansas City → Brighton, UK

---

## What I do

8+ years building and integrating systems — from IBM i / RPGLE business logic to Azure, Python, and .NET — plus my own operated homelab that runs **43 containers** across the home, career, and local-AI stacks: a full self-hosted media pipeline, DNS, ad-blocking, remote access, monitoring, a FileBrowser, a WebTTY, a mesh VPN, even a Folding@home node. Nothing here is a tutorial project; everything is **running, self-hosted, and monitored** (Uptime Kuma), exposed through Cloudflare Zero Trust tunnels with **no open inbound ports** — split-horizon DNS via AdGuard Home, orchestration via Portainer, ClamAV quarantine-review and Cloudflare Zero Trust IP-sync scripts I wrote for my own stack.

Recent builds include an **end-to-end encrypted browser terminal** (AES-GCM via WebCrypto, paramiko SSH into persistent tmux sessions, no inbound ports), a **disposable-container verification pipeline** that gates merges on reproducible static, unit, API, and UI checks, a **config-driven container control plane** (FastAPI + Docker SDK behind a scoped socket proxy, Cloudflare Access JWT verification), a **self-hosted speech service** (faster-whisper STT plus Kokoro/Piper/eSpeak TTS with per-emotion prosody), and a **sanitized disaster-recovery repo** with a host-detecting bootstrap, backup/restore tooling, and rebuild runbooks, and a **self-healing operations layer** (Kuma-to-ntfy alerts, health/CPU watchdogs, queue janitor, nightly appdata backups).

**Career focus:** Full-Stack Engineering · AI Systems Engineering · Enterprise Solutions Architecture · Systems Integration · Automation Engineering · ServiceNow · Azure integration · Cloudflare Zero Trust networking.

## What you'll find here

| Repo | What it is | Why it's interesting |
|---|---|---|
| [scherer-api](https://github.com/cscherer1/scherer-api) | ASP.NET Core 9 REST API | Production-deployed API with JWT auth, BCrypt, FluentValidation, rate-limited login — powers my portfolio site |
| [scherer-site](https://github.com/cscherer1/scherer-site) | React 19 + TypeScript SPA | Performance-conscious frontend with a hidden admin panel; holds the JWT in memory only |
| [trackfolio](https://github.com/cscherer1/trackfolio) | Java 21 + Spring Boot app tracker | The foundation of my job-search stack — search, filters, sorting, real tests |

**Currently building:** a fully automated, self-hosted career stack — **JobDashboard** — that replaces manual job hunting with an orchestrated pipeline: n8n orchestrates, NocoDB (on PostgreSQL 17) is the system of record, JobSpy ingests listings, an evidence-based skill inventory grounds resumes in *real* GitHub/portfolio/LinkedIn skills (not self-reported claims), and a resume renderer produces ATS-safe PDFs. It's architected around the Cloudflare 524 edge-timeout lesson: heavy work runs as background jobs that report progress instead of one long-lived request. It now also generates per-job company research, study guides, and interview prep grounded in verified evidence, and I develop it through an agentic **OpenCode + DeepSeek** workflow constrained by the same verification gates as any human change.

## The operating evidence (things I actually run and operate)

- **Home server (Intel NUC, Ubuntu 24.04 LTS + Docker Compose):** 40 containers across three stacks — a full self-hosted media pipeline (automated acquisition, metadata, and streaming, ~10 services deep), a **local AI stack** (Ollama, my **ouroborn** agent-orchestration project: a council of local LLMs with jury/witness evaluation and blind labels so models can't anchor on each other's names — the opposite of an API-call wrapper), remote access (Cloudflare Zero Trust, meshcentral, WebTTY), platform (Portainer, Glances, Uptime Kuma, ntfy, Stirling-PDF, PairDrop, FileBrowser, Homepage), the career stack above, and a **Command Deck** control plane and 42-tool operations console that discovers the live Docker inventory, groups tools by function, runs health probes, and exposes guarded start/stop/restart with host and per-container stats.
- **Secure-Term:** an end-to-end encrypted long-poll browser terminal that keeps terminal content opaque to edge and TLS-inspection proxies — Python standard library HTTP server, AES-GCM, SSH, and persistent tmux sessions, reachable only through an authenticated tunnel.
- **OP-E Voice:** a local speech service for my agent interface — faster-whisper transcription and Kokoro/Piper/eSpeak synthesis with per-emotion prosody. No cloud speech APIs; all inference runs on owned hardware.
- **Command Center:** the sanitized disaster-recovery repo for the whole server — services pinned as submodules, a host-detecting bootstrap, backup/restore tooling, and written rebuild runbooks.
- **Self-healing operations:** 35 Kuma monitors bridged to ntfy; cron watchdogs restart high-CPU/unhealthy containers, clear stuck Sonarr imports, block executable downloads, and run nightly consistent appdata backups mirrored across both drives.
- Everything is **self-hosted, terminal-first, and monitored** — I automate the things I use, and I operate the automation.

## Outside the code

- **8+ years** Burns & McDonnell (software developer → ServiceNow lead → IT systems) → **now** Full-Stack Developer & Solutions Architect at Murphy-Hoffman Company (IBM i middleware + Azure/.NET integration)
- **BS Computer Science**, Southern New Hampshire University — Summa Cum Laude, **4.0 GPA**, Distinguished Scholar Award, earned while working full time
- Designs tools for my hobbies (game mod load-order management, Steam workshop tooling) — I automate even the things I enjoy

## Tech I live in

IBM i / RPGLE · CL · Profound UI · Python · SQL · JavaScript · TypeScript · React · .NET / C# · Azure · ServiceNow · FastAPI · Docker · n8n · PostgreSQL · LLM / Ollama · Whisper STT · Kokoro / Piper / eSpeak TTS · OpenCode · DeepSeek · Cloudflare Zero Trust · Cloudflare Access · Kasm · Uptime Kuma · ntfy · Cron/systemd automation · Linux (self-hosted everything)

## Get in touch

Reach me through [christianscherer.dev](https://christianscherer.dev) — I'm open to Full-Stack Engineer / AI Systems Engineer / Enterprise Solutions Architect / Systems Integration roles, and always happy to talk automation.
