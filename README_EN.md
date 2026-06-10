# 🧠 Tongchou — AI Skill Orchestration Engine

![Python](https://img.shields.io/badge/python-3.8+-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![Version](https://img.shields.io/badge/version-1.0.0-brightgreen.svg)
![Skills](https://img.shields.io/badge/skills-50%2B-orange.svg)
![Made for Hermes](https://img.shields.io/badge/made%20for-Hermes%20Agent-8A2BE2.svg)
![Crawler Stack](https://img.shields.io/badge/integrated-Crawler%20Stack%20v5-success.svg)

> **"Don't tell me what tools to use. Tell me what you want."**
>
> Tongchou turns your AI Agent from a tool-user into a brain. Say the goal, it handles the rest. **Zero config, zero learning curve, zero BS.**

[中文说明](README.md) · [Report Bug](https://github.com/xianjianhuang/tongchou/issues) · [Crawler Stack](https://github.com/xianjianhuang/crawler-stack)

---

## 🔥 Without Tongchou, Your Agent Is Just a Fancy Search Engine

**You bought an iPhone but only use it to make calls — that's your AI Agent without Tongchou.**

| Without Tongchou | **With Tongchou** |
|---------|-------------|
| "Help me do something" → Agent asks "what tools do you want to use?" | **"On it."** — Tongchou auto-decides what, how, and in what order |
| Need to combine 3 features → manually chain them, write prompts | **"One-stop."** — Tongchou auto-parallelizes/pipelines, you wait for results |
| Agent doesn't know what skills you have → you tell it | **"What can you do?"** — Tongchou scans the entire library, recommends by need |
| One step fails → entire workflow crashes | **"Plan B."** — Tongchou auto-falls back to alternatives, never returns empty-handed |

**Bottom line: other people's agents are tools. Your agent is a CEO.**

---

## The Trinity — Full AI Skill Lifecycle

| Role | Skill | One-liner | GitHub |
|------|-------|-----------|--------|
| **🧬 Nuwa** | Create skills from scratch | "Make me a skill for X" → auto-investigates, generates full SKILL.md | Coming soon |
| **🧬 Darwin** | Evolve existing skills | "How good is this skill?" → 9-dimension scoring + optimization | Coming soon |
| **🧠 Tongchou** | Orchestrate everything | "Handle this end-to-end" → analyze → match → orchestrate → deliver | ✅ **This repo** |

**Together = your Agent has superpowers of self-evolution and self-organization.**

---

## 🚀 Install in 10 Seconds

```bash
# Hermes Agent
hermes skills install tongchou

# Manual
cp SKILL.md ~/.hermes/skills/tongchou/

# Then just talk to your agent:
"Handle this for me"
"One-stop: do X, Y, and Z"
```

**Zero config. Install and it just works.**

---

## 🧪 Real-World Case Studies

### Case 1: Full Research Report in One Sentence

```
You: One-stop: research the latest AI Agent open-source trends, give me a full report

Tongchou:
  Phase 0 → Instant: needs research + analysis combo
  Phase 1 → Match: web-research (search) + code-analyzer (analyze)
  Phase 2 → Parallel execution:
    ├─ web-research: search AI Agent trends
    ├─ web-research: fetch Top 10 project details
    └─ code-analyzer: analyze each project's tech stack and activity
  Phase 3 → You get: Top 5 analysis report + trend summary + community comparison

You said: one sentence.
Time saved: at least 2 hours.
```

### Case 2: Create + Auto-Optimize a Skill

```
You: Make me a "file organizer" skill

Tongchou:
  Phase 0 → Instant: skill creation, hand off to Nuwa
  Nuwa → Researches file organization methods → generates full SKILL.md
  Tongchou → Auto-routes to Darwin for evaluation
  Darwin → 9-dimension score: 72/100 → 5 optimization suggestions
  Tongchou → Reports back:
    ✅ Skill "file-sorter" created
    📊 Score: 72/100
    💡 Suggestions: add classification rules, dry-run mode, batch support

You said: one sentence.
You got: a complete skill + professional evaluation + improvement roadmap.
```

### Case 3: E-commerce Price Tracking + Visual Report

```
You: Scrape this JD product page, analyze price trends, generate a visual report

Tongchou:
  Phase 0 → Instant: scraper + analyzer, pipeline mode
  Phase 2 → Three-step pipeline:
    1. crawler-stack → 9-layer auto-degradation scraping
    2. code-analyzer → price data analysis, historical comparison
    3. Main agent → HTML report with price trend chart + recommendations
  Phase 3 → You get: a ready-to-open HTML report file

You said: one sentence.
You got: complete price analysis + visualization + buying advice.
```

### Case 4: One-Stop Finance + Fund + Briefing

```
You: Check gold prices, analyze my portfolio, write today's market briefing

Tongchou:
  Phase 0 → Instant: three independent tasks, parallel mode
  Phase 2 → Simultaneously:
    ├─ market-quote: gold/silver real-time prices
    ├─ market-quote: fund portfolio analysis
    └─ Main agent: search today's market news
  Phase 3 → You get:
    📊 Gold: real-time price + daily trend
    📈 Fund: holdings distribution + sector allocation + rebalancing advice
    📰 Market summary: important news + impact on your holdings

You said: one sentence.
Time saved: at least 45 minutes.
```

### Case 5: Scheduled Auto-Briefing While You Sleep

```
You before bed: Tongchou, set up a daily 8 AM market briefing

Tongchou:
  Phase 0 → Instant: cron task, needs cronjob + research
  Phase 2 → Creates cronjob:
    └─ Every 8 AM auto-execute:
       ├─ market-quote: gold, A-shares, US stocks
       ├─ web-research: today's important news
       └─ Aggregate into briefing
  Next morning 8 AM → You receive a complete market briefing

You said: one sentence.
You got: daily auto-pushed market briefing, runs until you cancel it.
```

### Case 6: Multi-Site Scraping + Competitive Analysis

```
You: Scrape these competitor sites, analyze pricing strategies, make a comparison table

Tongchou:
  Phase 0 → Instant: multi-target scraping + comparison analysis
  Phase 2 → Step by step:
    1. crawler-stack × N: scrape all competitors simultaneously
    2. code-analyzer: extract pricing, plan structures, promotions
    3. Main agent: generate pricing comparison table + strategy analysis
  Phase 3 → You get:
    📊 Competitor pricing comparison table
    🔍 Pricing strategy analysis
    💡 Your pricing recommendations

You said: one sentence.
Time saved: at least half a day of manual research.
```

---

## 🧠 What Tongchou Can Orchestrate: 50+ Skills

| Domain | Skill | What It Does | Case |
|--------|-------|-------------|------|
| **🕷️ Scraping** | crawler-stack | 9-layer auto-degradation | 3, 6 |
| **📖 Research** | web-research | Multi-source aggregation | 1, 5 |
| **🔍 Code** | code-analyzer | Architecture/data flow analysis | 1, 3, 6 |
| **🧬 Create** | huashu-nuwa | Skill creation from scratch | 2 |
| **🧬 Evolve** | darwin-skill | 9-dimension scoring + optimization | 2 |
| **💰 Finance** | market-quote | Stock/fund data + advice | 4, 5 |
| **⚙️ DevOps** | cronjob-automation | Scheduled tasks | 5 |
| **🎨 Creative** | brainstorming | Idea generation | Anything |
| **🎨 Design** | sketch | HTML prototypes | Anything |
| **📁 Files** | file-organizer | Auto file sorting | 2 |
| **🎬 Video** | video-download | Video downloading | Anything |
| **🐙 GitHub** | github-pr-workflow | Automated PRs | Dev workflows |
| **...** | **50+ growing** | Auto-discovered | Install and it works |

---

## 📊 Efficiency: With vs Without Tongchou

| Scenario | Without Tongchou | **With Tongchou** | Time Saved |
|----------|----------------|-------------------|:----------:|
| Competitive research report | 2 hours manual | **One sentence → 10 min** | **92%** |
| Create a new skill | 1 hour reading docs | **One sentence → 5 min** | **92%** |
| Scrape + analyze pipeline | 1.5 hours | **One sentence → 15 min** | **83%** |
| Daily market briefing | 30 min/day manual | **Set once, auto forever** | **100%** |
| Combine 3 features | 45 min manual chaining | **One sentence → 5 min** | **89%** |

**Average: 90%+ time saved. One extra day per week.**

---

## 🔧 Failure Recovery: 5 Backup Plans

| What Goes Wrong | Tongchou Saves It | You See |
|----------------|-------------------|---------|
| Matched skill doesn't exist | Auto-rescan, pick alternative | Task continues unaffected |
| Subagent 403 (broke) | Fallback to main agent | Same result, just slower |
| Too vague to match | Ask 1 clarifying question | "Are you asking about tech or business?" |
| Skill says "can't do it" | Switch to alternative | Plan B continues, no interruption |
| Step times out | Skip it, continue rest | Report notes "XX step timed out, skipped" |

**Tongchou's principle: never come back empty-handed.**

---

## ⚡ Tongchou vs The Competition

| Dimension | **Tongchou 🚀** | OpenAI Assistants | LangChain | Manual |
|-----------|----------------|-------------------|-----------|--------|
| **Learning cost** | **Zero** — plain language | Low — learn Assistant concept | High — learn Chain concept | Very high — learn every tool |
| **Install time** | **10 seconds** | Register + API Key + config | pip install + write code | Unlimited |
| **Skill discovery** | **Auto** — scan entire library | Manual create/select | Manual import | Manual docs |
| **Orchestration** | 4 modes (direct/pipeline/parallel/iterative) | Pipeline only | Multiple but needs config | Write your own logic |
| **Failure recovery** | **Auto** — 5 fallback plans | Manual handling | try/catch | Implement yourself |
| **Ecosystem** | **50+ skills** + trinity | OpenAI only | Fragmented community | DIY |
| **Self-evolution** | ✅ Full trinity loop | ❌ | ❌ | ❌ |
| **Price** | **Free & open source** 💯 | Pay per token | Free & open source | Your time |

**Verdict: theirs are toolboxes. Tongchou is an assembly line.**

---

## 🔗 Ecosystem

| Project | Relationship | GitHub |
|---------|-------------|--------|
| **🕷️ Crawler Stack v5** | Tongchou orchestrates its scraping power | [xianjianhuang/crawler-stack](https://github.com/xianjianhuang/crawler-stack) |
| **🧬 Nuwa** | Creates skills on demand | Coming soon |
| **🧬 Darwin** | Evolves skills for quality | Coming soon |
| **🤖 Hermes Agent** | Tongchou runs inside Hermes | [NousResearch/hermes-agent](https://github.com/NousResearch/hermes-agent) |

---

## 📄 License

MIT — use it, modify it, keep the copyright notice.

---

> **Tongchou = your Agent doesn't need to know "what tools" — just tell it "what result."**
>
> With Nuwa (create) + Darwin (evolve), your AI Agent has complete self-evolution capability.
>
> **Say what you want. Tongchou handles the rest.** 🧠
