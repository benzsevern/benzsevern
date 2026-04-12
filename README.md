### Hi, I'm Ben

[![Website](https://img.shields.io/badge/bensevern.dev-000?style=flat&logo=vercel&logoColor=white)](https://bensevern.dev/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/bensevern/)
[![PyPI](https://img.shields.io/badge/PyPI-3775A9?style=flat&logo=pypi&logoColor=white)](https://pypi.org/user/benzsevern/)

I build open-source data quality and entity resolution tools in Python. Everything I ship lands on [PyPI](https://pypi.org/user/benzsevern/) and the [MCP Registry](https://smithery.ai/) so it works out of the box with LLM agents.

---

#### Golden Suite

A modular toolkit where each piece works standalone or chains together via GoldenPipe.

```
  CSV / DB / API
       │
       ▼
┌─────────────┐    ┌─────────────┐    ┌─────────────┐
│ GoldenCheck │───▶│ GoldenFlow  │───▶│ GoldenMatch │
│  Validate   │    │  Transform  │    │   Resolve   │
└─────────────┘    └─────────────┘    └─────────────┘
       └──────────────────┬──────────────────┘
                          ▼
                    GoldenPipe
                   (orchestrator)
```

| | Project | Highlights | Downloads |
|---|---------|-----------|-----------|
| **Resolve** | [GoldenMatch](https://github.com/benzsevern/goldenmatch) | 97.2% F1 on DBLP-ACM · 30 MCP tools · 10 A2A skills | [![Downloads](https://img.shields.io/pypi/dm/goldenmatch)](https://pypi.org/project/goldenmatch/) |
| **Validate** | [GoldenCheck](https://github.com/benzsevern/goldencheck) | Zero-config profiling & drift detection · 19 MCP tools | [![Downloads](https://img.shields.io/pypi/dm/goldencheck)](https://pypi.org/project/goldencheck/) |
| **Transform** | [GoldenFlow](https://github.com/benzsevern/goldenflow) | 76 transforms · DQBench Transform: 100/100 · 10 MCP tools | [![Downloads](https://img.shields.io/pypi/dm/goldenflow)](https://pypi.org/project/goldenflow/) |
| **Orchestrate** | [GoldenPipe](https://github.com/benzsevern/goldenpipe) | Chains Check → Flow → Match · 4 MCP tools | [![Downloads](https://img.shields.io/pypi/dm/goldenpipe)](https://pypi.org/project/goldenpipe/) |

<details>
<summary><b>Extensions & integrations</b></summary>

- [goldencheck-action](https://github.com/benzsevern/goldencheck-action) — GitHub Action for data validation in CI with PR comments
- [goldencheck-types](https://github.com/benzsevern/goldencheck-types) — Community semantic type definitions (healthcare, finance, e-commerce)
- [goldenmatch-extensions](https://github.com/benzsevern/goldenmatch-extensions) — SQL extensions for Postgres (pgrx) and DuckDB
- [goldenmatch-wallet-attribution](https://github.com/benzsevern/goldenmatch-wallet-attribution) — Entity resolution on 13M blockchain records across 10 sources
- [goldenmatch-vuln-attribution](https://github.com/benzsevern/goldenmatch-vuln-attribution) — Entity resolution on 869K OSS vulnerability records across 15 sources

</details>

---

#### Other Projects

[**DQBench**](https://github.com/benzsevern/dqbench) — The standard benchmark for data quality tools. 4 categories, 12 tiers, 161 tests. Used to score Golden Suite and compare against Great Expectations, Pandera, Soda Core, and others.

[**InferMap**](https://github.com/benzsevern/infermap) — Inference-driven schema mapping for Python & TypeScript. 7 scorers, domain dictionaries, cross-language parity (F1 0.84).

[**DevPilot**](https://github.com/benzsevern/devpilot) — Dev server supervisor for AI coders. CLI + MCP server with 10 tools. Lifecycle management, health checks, crash recovery.

---

#### Tech

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000?style=flat&logo=rust&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Polars](https://img.shields.io/badge/Polars-CD792C?style=flat&logo=polars&logoColor=white)
