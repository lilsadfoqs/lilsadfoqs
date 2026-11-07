```text
░▒▓█▓▒░      ░▒▓█▓▒░▒▓█▓▒░       ░▒▓███████▓▒░░▒▓██████▓▒░░▒▓███████▓▒░░▒▓████████▓▒░▒▓██████▓▒░ ░▒▓██████▓▒░ ░▒▓███████▓▒░ 
░▒▓█▓▒░      ░▒▓█▓▒░▒▓█▓▒░      ░▒▓█▓▒░      ░▒▓█▓▒░░▒▓█▓▒░▒▓█▓▒░░▒▓█▓▒░▒▓█▓▒░     ░▒▓█▓▒░░▒▓█▓▒░▒▓█▓▒░░▒▓█▓▒░▒▓█▓▒░        
░▒▓█▓▒░      ░▒▓█▓▒░▒▓█▓▒░      ░▒▓█▓▒░      ░▒▓█▓▒░░▒▓█▓▒░▒▓█▓▒░░▒▓█▓▒░▒▓█▓▒░     ░▒▓█▓▒░░▒▓█▓▒░▒▓█▓▒░░▒▓█▓▒░▒▓█▓▒░        
░▒▓█▓▒░      ░▒▓█▓▒░▒▓█▓▒░       ░▒▓██████▓▒░░▒▓████████▓▒░▒▓█▓▒░░▒▓█▓▒░▒▓██████▓▒░░▒▓█▓▒░░▒▓█▓▒░▒▓█▓▒░░▒▓█▓▒░░▒▓██████▓▒░  
░▒▓█▓▒░      ░▒▓█▓▒░▒▓█▓▒░             ░▒▓█▓▒░▒▓█▓▒░░▒▓█▓▒░▒▓█▓▒░░▒▓█▓▒░▒▓█▓▒░     ░▒▓█▓▒░░▒▓█▓▒░▒▓█▓▒░░▒▓█▓▒░      ░▒▓█▓▒░ 
░▒▓█▓▒░      ░▒▓█▓▒░▒▓█▓▒░             ░▒▓█▓▒░▒▓█▓▒░░▒▓█▓▒░▒▓█▓▒░░▒▓█▓▒░▒▓█▓▒░     ░▒▓█▓▒░░▒▓█▓▒░▒▓█▓▒░░▒▓█▓▒░      ░▒▓█▓▒░ 
░▒▓████████▓▒░▒▓█▓▒░▒▓████████▓▒░▒▓███████▓▒░░▒▓█▓▒░░▒▓█▓▒░▒▓███████▓▒░░▒▓█▓▒░      ░▒▓██████▓▒░ ░▒▓██████▓▒░░▒▓███████▓▒░  
                                                                                                   ░▒▓█▓▒░                  
                                                                                                    ░▒▓██▓▒░                
```

hi, i'm lilsadfoqs :Đ

I'm the Tortoise in the SWE race.

---

# Software Engineer @ OPSWAT, MetaDefender Cloud

Computer Science Graduate @ HCMUS

[portfolio](https://lilsadfoqs.dev) | [linkedin](https://linkedin.com/in/lilsadfoqs) | [ctftime](https://ctftime.org/team/406024)

---

## featured projects

### [elfoqsy](https://github.com/lilsadfoqs/elfoqsy)
Local-first orchestrator: one Claude Code agent per Jira ticket, with an approval gate and full replay.

- a Node daemon polls the sprint board and spawns one agent per ticket in its own git clone, with sub-agents and a read-only reviewer
- agents hold no credentials. git, gh, kubectl, aws and jira calls go through capability proxies
- 4-tier approval gate: log, undoable, ask first, deny. merge, prod, force-push and `kubectl apply` are always denied
- append-only SQLite event log, and every screen is a fold over it, so undo and replay come for free
- TypeScript, Claude Agent SDK, React, Zod, pnpm monorepo. ~2k unit tests on the gate

### [azhaq](https://github.com/lilsadfoqs/azhaq)
Recon in one Go binary. Stands in for subfinder, dnsx, httpx, katana, ffuf, gau, arjun, naabu, gowitness, asnmap and notify.

- route mapping from app JS, cross-account access control diffing (`azhaq roles`), takeover candidates, `azhaq watch` for route changes between runs
- every request is held to a scope and a request budget, and logged to a hash-chained ledger (`azhaq ledger -verify`)
- one SQLite workspace, headless Chrome crawling, cosign-signed releases via GoReleaser
- `azhaq mcp` runs it as an MCP server. scope, budget and rate are fixed at server start, so the agent can't widen them
- juice-shop v20.3.0 route map: 70/77 in 2.0 s and 113 MB, katana gets 1/77 in 14 s and 1420 MB

### [Seedance-2.0-APIze](https://github.com/lilsadfoqs/Seedance-2.0-APIze)
Unofficial REST API for Seedance 2.0, since Dreamina has no public one.

- Go + Playwright drive the Dreamina web UI behind an async job queue
- omni and start/end frame modes, up to 9 reference images, session persistence, optional API key
- 44 stars, 11 forks

---

## more projects

| project | what it is | stack |
| --- | --- | --- |
| [ChapBaiSlayer-CTF-Writeups](https://github.com/lilsadfoqs/ChapBaiSlayer-CTF-Writeups) | writeups of my CTF team [ChapBaiSlayer](https://ctftime.org/team/406024), where I play web. 110+ total, 55 mine (19 of the 30 web). 50+ CTFtime-rated events since 2025, best 11th at RITSEC CTF 2026 and 14th at RSTCON 2025 | web, crypto, rev, forensics |
| [aurelinth-ctf-agentic-ai](https://github.com/lilsadfoqs/aurelinth-ctf-agentic-ai) | supervisor LLM routing 23 specialist agents (10 blackbox, 13 whitebox), SSE live monitor. 8 flags across 4 live CTFs in March 2026 | Python, Gemini, Redis Streams, React |
| [relayops](https://github.com/lilsadfoqs/relayops) | event-driven job platform: retry with backoff, DLQ, replay, append-only delivery attempts. [demo](https://relayops.lilsadfoqs.dev) | Go, chi, NATS, Postgres, Docker Compose, Nginx, EC2 |
| [support-dashboard](https://github.com/lilsadfoqs/support-dashboard) | ticketing with JWT, RBAC in the service layer, Gemini reply suggestions | Go, Gin, Next.js, Postgres |
| [aurelinth.me](https://aurelinth.me) | bootstrapped micro-SaaS for AI video workflows | TypeScript |

---

## what i work with

| | |
| --- | --- |
| **lang** | Go, TypeScript, Python, Bash |
| **ai** | Claude Code, Claude Agent SDK, MCP |
| **backend** | Kafka, RabbitMQ, NATS, Redis, PostgreSQL, MongoDB, SQLite |
| **infra** | AWS (EKS, S3, EC2), Kubernetes, Docker, Nginx, Linux |
| **web** | Next.js, React, Gin, chi |

---

## what i'm into

- agentic AI, and the guardrails that let agents run against real infra without blowing anything up
- distributed systems: async processing, retries, failure handling
- open-source offensive security tooling
- if I do something by hand twice, it becomes a script or a tool
- several Claude Code sessions in parallel, one git worktree each. I write the spec and review every diff

---

```python
while alive:
    learn()
    build()
    improve()
```
---

<sub>Built by <a href="https://github.com/lilsadfoqs">@lilsadfoqs</a></sub>
