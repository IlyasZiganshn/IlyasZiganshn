# Ilyas Ziganshin

Python backend and LLM tooling. I build small services with tests, Docker and a number for every claim.

**Now:** building [`lead-router`](https://github.com/Pinger1456/lead-router) and the harness that keeps my agents honest, [`agent-evals`](https://github.com/Pinger1456/agent-evals).

Open to remote Python backend and LLM engineer roles.
[Email](mailto:ilyas.ziganshn@gmail.com) · [Telegram](https://t.me/z1ganshin_i) · Tashkent, UTC+5

## Selected work

| Project | What it is | Evidence |
| --- | --- | --- |
| [agent-evals](https://github.com/Pinger1456/agent-evals) | Planner-level eval harness for tool-using agents. YAML tasks, recorded observations, any OpenAI-compatible model. | 12 tasks, 5 tools, oracle 12/12, constant baseline 0/12, JSON reports in CI |
| [lead-router](https://github.com/Pinger1456/lead-router) | FastAPI service for lead intake. Idempotent upsert, CSV import, YAML routing rules, SQLite. | 28 tests, 0 duplicates across 5 repeated imports, p95 0.20 ms on 10k rows |

Every number above is produced by a script in the repo. A project without a number is not finished.

## How I work

- I start from the failure mode, not the framework. For agents the first question is what breaks, and how I see it.
- I keep the loop small and observable. One LLM call per step, one action per step, one trace per run.
- I write the eval before the feature. A demo that works once is not evidence.
- I write Python as small modules and functions. A class appears only when something has state to hold, like a browser session.

## Backend

FastAPI, SQLite and Postgres, Docker, pytest, GitHub Actions. Idempotent writes, dry-run first, rules in YAML, retries with backoff.

## Background

MSc in Software Engineering, BSc in Finance and Credit. Before LLM work I built CRM integrations, webhook queues and browser automations for a marketing company and a franchise network.

## Stack

Python, TypeScript, FastAPI, Playwright, PostgreSQL, Redis, Docker, GitHub Actions.
Providers: OpenAI, Anthropic and GLM through OpenAI-compatible endpoints.

## More work

[mcp-rag-mini](https://github.com/Pinger1456/mcp-rag-mini), [ai-browser-agent](https://github.com/Pinger1456/ai-browser-agent), [crm-lead-digest](https://github.com/Pinger1456/crm-lead-digest), [telegram-multitool-bot](https://github.com/Pinger1456/telegram-multitool-bot)
