# meshcode-ai/skills-exec

![Executive & Finance cover](assets/cover.svg)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Skills](https://img.shields.io/badge/skills-10-blue)](#)
[![Standard](https://img.shields.io/badge/agent--skills-spec-brightgreen)](https://agentskills.io/specification)

**Executive advisory and finance skills for Claude Code, Codex, Cursor** — 10 knowledge-first Agent Skills covering **CEO/CFO-level advisory** (executive mentoring, decision memos, leadership & crisis communication), **investor & board reporting** (investor update structure, metric definitions, runway narrative), **finance planning** (revenue forecast with commit categories, 13-week cash flow linkage, forecast accuracy), and **sales & revenue ops** (pipeline coverage ratio 3x, sales velocity & win rate, MEDDICC enablement, BATNA/ZOPA negotiation, ICP prospecting, RevOps metric governance). Judgment criteria and output contracts for executives, founders, and sales leaders — no scripts, pure decision knowledge. Works in meshcode desktop, Claude Code, Codex, Cursor, and any Agent Skills-standard runtime.

## Who this is for

- **Founder / CEO / executive** — when running delegation, decision-making, crisis communication, and investor updates by judgment criteria rather than standard templates
- **CFO / finance lead** — when reporting revenue forecasts, 13-week cash flow, and runway judgment in a consistent frame
- **Sales Leader / RevOps** — when managing pipeline coverage, win rate, and forecast error with shared definitions and reconciling numbers across departments

## Install

Download the zip → extract into your project's `.meshcode/skills/` (keep the flat layout). Automatically exposed from the next session onward.

## TOC

- [Skill list](#skill-list)
- [Recommended order of use](#recommended-order-of-use)
- [Related repos](#related-repos)
- [Use with meshcode](#use-with-meshcode)

## Skill list

| Skill | Role | Judgment criteria summary |
|---|---|---|
| `exec-executive-mentor` | Executive coaching & delegation | 4 delegation levels, 60/30/10 time split, single named decision owner |
| `exec-decision-memo` | Executive decision frames | ≥2 options + Do-nothing, premortem, mandatory review deadline |
| `exec-leadership-comm` | All-hands & crisis communication | Core 3 sentences, single spokesperson, 4 elements of change announcements |
| `exec-investor-update` | Investor & board reporting | Highlights→Lowlights→Metrics→Ask, bad news first |
| `fin-forecast` | Revenue forecasting & cash linkage | 3-layer forecast, Commit ≥90%, ±10% error, 13-week cash flow |
| `fin-sales-pipeline` | Pipeline management | Coverage 3x, velocity = opportunities × deal size × win rate ÷ cycle |
| `fin-sales-enablement` | Sales assets & qualification | MEDDICC ≥10, Demo = value scenario |
| `fin-negotiation` | Negotiation prep & execution | BATNA/ZOPA calculation, anchor first, Give-Get trades |
| `fin-prospecting` | ICP & outbound | ICP reverse-engineered from top cohort, Fit 60 + Timing 40 |
| `fin-revops` | RevOps & metric alignment | Definition owned by 1 person, cross-department conversion within 2%p |

## Recommended order of use

1. `exec-executive-mentor` → `exec-decision-memo` (management habits → decision quality)
2. `exec-investor-update` → `fin-forecast` (external reporting ← internal forecasting & cash linkage)
3. `fin-prospecting` → `fin-sales-pipeline` → `fin-sales-enablement` (inflow → management → conversion)
4. `fin-negotiation` (late-stage closing), `fin-revops` (definition & data governance across all stages)

Cross-references between skills: the gap calculation in forecast reuses the coverage formula from pipeline, and stage conversion rates in pipeline become the measured weighting data for forecast. The RevOps metric definition book guarantees that the numbers in the two skills mean the same thing.

## Use with meshcode

These skills are built for [meshcode](https://meshcode.ai) (free download — macOS/Windows):

1. Open your project in meshcode
2. In chat, ask **"show available skills"**, then **"install the executive skills"** — meshcode fetches from this repo automatically, no git or terminal needed
3. They appear in the next session and load only when a task matches, so installing all of them stays cheap

Manual alternative: download this repo's zip and extract into your project's `.meshcode/skills/`. Also works in Claude Code (`~/.claude/skills/`), Codex, and Cursor.

