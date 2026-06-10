# 🧠 Tongchou — AI Skill Orchestration Engine

> **"Don't tell me what tools to use. Tell me what you want."**

Tongchou is the **brain** of your AI Agent's skill system. Say a goal, and it automatically figures out which skills to use, in what order, and how to combine the output. **Zero config, zero learning curve, zero BS.**

[中文说明](README.md) · [Report Bug](https://github.com/xianjianhuang/tongchou/issues) · [Request Feature](https://github.com/xianjianhuang/tongchou/issues)

---

## The Trinity — Full AI Skill Lifecycle

| Role | Skill | One-liner |
|------|-------|-----------|
| **🧬 Nuwa** | Create skills from scratch | "Make me a skill that researches X" → auto-investigates, distills, generates full SKILL.md |
| **🧬 Darwin** | Evolve existing skills | "How good is this skill?" → 9-dimension scoring, optimization plan, iterative improvement |
| **🧠 Tongchou** | Orchestrate skills to get things done | "Handle this end-to-end" → analyze → match skills → orchestrate → deliver |

**Together = your Agent has superpowers of self-evolution and self-organization.**

---

## Quick Start

```bash
# Install into Hermes
hermes skills install tongchou

# Just talk to your agent in plain language:
"Handle this end-to-end: scrape that site and generate a report"
→ Tongchou auto-orchestrates: crawler-stack → code-analyzer → report

"One-stop: check gold prices, analyze my portfolio, write a market brief"
→ Tongchou parallel-executes market-quote × 2, then aggregates
```

## Four Orchestration Modes

| Mode | When | Example |
|------|------|---------|
| **⚡ Direct** | One skill is enough | "Check gold price" → `market-quote` |
| **🔗 Pipeline** | Skill A → Skill B | "Scrape and analyze" → crawler-stack → code-analyzer |
| **⚡ Parallel** | Multiple independent tasks | "Research these 3 companies" → parallel web-research × 3 |
| **🔄 Iterative** | Needs user confirmation mid-way | "Fix this site structure" → analyze → propose → wait → execute → verify |

## vs Other Orchestration Approaches

| Dimension | **Tongchou 🚀** | OpenAI Assistants | LangChain | Manual |
|-----------|----------------|-------------------|-----------|--------|
| Learning cost | **Zero** — plain language | Low — need to learn Assistant concept | High — Chain/AI concepts | Very high — every tool |
| Skill discovery | **Auto** — scans full library | Manual create/select | Manual import | Manual docs reading |
| Failure recovery | **Auto** — fallback or skip | Manual handling | try/catch | Implement yourself |
| Ecosystem | **50+ skills**, trinity | OpenAI only | Community, fragmented | DIY |
| Self-evolution | ✅ Full trinity loop | ❌ | ❌ | ❌ |

## What Tongchou Won't Do

- ❌ **No force-fitting** — no matching skill? Tongchou uses its own ability
- ❌ **No tool listing** — doesn't show you "here are your options," just does it
- ❌ **No over-confirmation** — high confidence = execute directly, low confidence = ask once
- ❌ **No over-engineering** — one skill is enough? No orchestration needed
- ❌ **No skill modification** — that's Darwin's job

---

## License

MIT — use it, modify it, keep the copyright notice.
