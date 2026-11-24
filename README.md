# Christian Scherer

**Software & Platform Engineer — Enterprise Integration, Automation & Applied AI**

I build the integration and automation layer between systems that were never meant to talk to each other — and the private, self-hosted systems that keep my own operation running.

[christianscherer.dev](https://www.christianscherer.dev) · Las Vegas, NV · Remote-first · US/UK dual citizen

---

## What I do

A decade in enterprise IT, including eight years at Burns & McDonnell, where I automated enterprise and M365 processes through ServiceNow, Azure and PowerShell: access and licensing changes, IP-address management, backup and restore, and the supporting data workflows around them. Examples include EfficientIP pool reservations, Revit server and ImaginIT Clarity automation, employee name changes, manager access to departed employees' files, and ArcGIS backup and restore in Azure. Those changes removed hundreds of administrative hours a year and replaced hand-run processes with documented, supported services.

Now at MHC Kenworth, I bridge IBM i (RPGLE/CL) business systems to Azure-hosted Python and .NET services: defining interfaces with stakeholders, replacing manual workflows, and keeping production integrations observable and recoverable.

The through-line is engineering, not just code: understand the process, design the interfaces and controls, then build the smallest system that stays supportable.

## Selected private case studies

Most of my recent work is private for real reasons — live credentials, personal data, a commercial game, a security boundary — not because there is nothing to show. Each system below has a public case study covering the problem, architecture, evidence, limits, and exactly why the code is private.

| System | What it is | Why the code is private | Public case study |
|---|---|---|---|
| **OP-E Console, Secure-Term & Voice** | Encrypted AI operations console, encrypted browser terminal, local Whisper/Kokoro speech, model council, cost analytics | Live session keys, agent memory, security model and operator context | [Read](https://www.christianscherer.dev/work/op-e-console) |
| **Career Automation Stack** | JobDashboard, Career OS and Contract Radar: scraping, evidence-based skills, fit scoring, tailored applications | Personal job/contract data, recruiter data, API tokens and search strategy | [Read](https://www.christianscherer.dev/work/career-automation) |
| **Agent-Test** | Disposable-container CI gate: static, unit, API, browser and hardcode checks | Host topology, internal ports, deploy path and credential references | [Read](https://www.christianscherer.dev/work/agent-test) |
| **Coin Cascade** | Physics-based coin-pusher game: TypeScript, Rapier/Three.js, fixed timestep, 10k+ test lines | Commercial game in development: simulation, economy, art and anti-cheat | [Read](https://www.christianscherer.dev/work/coin-cascade) |
| **Ouroborn** | Local LLM deliberation council: independent jury, blind rounds, foreman verdict | Original research: prompts, round design, model roster and failure catalogue | [Read](https://www.christianscherer.dev/work/ouroborn) |
| **Zero Trust Home Infrastructure** | Self-hosted platform: no open inbound ports, Access tunnels, encrypted backups, DR bootstrap, watchdog, BLE mesh experiment | Network topology, tunnel IDs, credentials, backup keys and physical layout | [Read](https://www.christianscherer.dev/work/home-infrastructure) |
| **Private Health** | Records-grounded health assistant: citation verification, model panel, per-person guardrails, read-only learning loop | Medical records, PII and consent; the privacy boundary is the design | [Read](https://www.christianscherer.dev/work/private-health) |
| **Flip Scout** | Photo-to-profit reseller tool: vision ID, verified comps, fee math, max buy, listing draft | A family member's reseller account, comps, costs and marketplace access | [Read](https://www.christianscherer.dev/work/flip-scout) |

The code is withheld; the evidence is not. Every case study states what is public, what is not, and where the system stops.

## Public repositories

| Repo | What it is | Why it is interesting |
|---|---|---|
| [scherer-api](https://github.com/cscherer1/scherer-api) | ASP.NET Core 9 REST API | JWT auth, BCrypt, FluentValidation, rate-limited login; powers this portfolio |
| [scherer-site](https://github.com/cscherer1/scherer-site) | React 19 + TypeScript SPA | The portfolio frontend; JWT held in memory only; admin portal |
| [trackfolio](https://github.com/cscherer1/trackfolio) | Java 21 + Spring Boot app tracker | The foundation of the job-search stack: search, filters, sorting, real tests |

## How I operate

- **Verification over vibes.** Agent-Test runs static analysis, unit/API/UI checks and hardcode scans in disposable containers; merges wait on a green gate. I develop with OpenCode and DeepSeek under the same gates as any human change.
- **Encrypted by default where it matters.** An end-to-end encrypted terminal and console (AES-GCM, SSH, tmux), Cloudflare Access in front of every UI, encrypted backups, and a sanitized disaster-recovery repo with a host-detecting bootstrap and rebuild runbooks.
- **Self-healing by default.** Health and CPU watchdogs, queue janitors, dead-man freshness checks, port guards, and nightly appdata backups mirrored across machines.
- **Config over hardcoding.** Hosts, ports, searches, title filters, tech aliases, model routing and schedules live in settings or environment configuration. A solution someone else cannot adopt by changing config is not finished.

## Background

- **MHC Kenworth** — Programmer/Analyst: IBM i (RPGLE/CL) middleware and Azure/Python/.NET integration
- **Burns & McDonnell** — IT support → ServiceNow automation → software development (eight years)
- **BS Computer Science, Southern New Hampshire University** — Summa Cum Laude, 4.0 GPA, Distinguished Scholar Award, earned while working full time
- I build tools for my hobbies too — a browser coin-pusher game and game mod load-order tooling — because the automation habit does not turn off

## Tech I live in

IBM i / RPGLE · CL · Profound UI · Python · SQL · JavaScript · TypeScript · React · .NET / C# · Azure · ServiceNow · Microsoft 365 · EfficientIP · ArcGIS · FastAPI · Docker · n8n · PostgreSQL · LLM / Ollama · faster-whisper · Kokoro / Piper TTS · OpenCode · DeepSeek · Cloudflare Zero Trust · Cloudflare Access · Kasm · Uptime Kuma · ntfy · Cron/systemd automation · Linux

## Get in touch

Reach me through [christianscherer.dev](https://www.christianscherer.dev). I am open to **remote** software, platform and integration engineering roles; hybrid in Las Vegas considered for an exceptional fit. Full-time or contract. Always glad to compare notes in writing about integration, automation, security or applied AI.
