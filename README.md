# BeyondCoding

“Coding agent” might be the worst name we could have picked for what these tools actually are. The same assistant that lives in your editor — Cursor, Claude Code, Codex, and the like — can read Slack, triage Jira, draft email, update a CRM, and chase answers across Confluence and GitHub. Not because the model magically became “general,” but because **your job was never only code**. The name trains us to treat it like a sidebar for developers; the reality is **one agent, every tool you use at work**, once you connect it. **BeyondCoding** is that shift: keep the coding, add the rest of the job.

> **Coding still matters.** This playbook is about everything *else* you do on the same machine: search, triage, draft, update, report, follow up — **read + write + act** across every system you already use, not a separate product.

---

## → Canonical home (clone & star this)

**Use [10xProductivity](https://github.com/ZhixiangLuo/10xProductivity) as your working copy.** All setup instructions, paths, and community activity are written for that repo. This repo (**BeyondCoding**) mirrors the **same files** under this story — *the name “coding agent” undersells the capability; here’s the full job.*

| | |
|---|---|
| **⭐ Clone & star** | [**10xProductivity**](https://github.com/ZhixiangLuo/10xProductivity) — canonical project; `setup.md` and tooling assume this clone. |
| **This repo** | **BeyondCoding** — same tree, this positioning. Share this URL when *“worst name ever”* and *whole job, not just the repo* land better than the product name. |

[![10xProductivity stars](https://img.shields.io/github/stars/ZhixiangLuo/10xProductivity?style=social&label=Star%2010xProductivity)](https://github.com/ZhixiangLuo/10xProductivity)
[![BeyondCoding stars](https://img.shields.io/github/stars/ZhixiangLuo/BeyondCoding?style=social)](https://github.com/ZhixiangLuo/BeyondCoding/stargazers)

**If you cloned BeyondCoding instead of 10x:** the repo contents match. Your folder may be named `BeyondCoding` while `setup.md` says `10xProductivity` — use the path from `pwd` everywhere the docs show a repo path.

---

## Why this name?

**BeyondCoding** pushes back on a label that hides the surface area. Once the agent reaches email, chat, tickets, spreadsheets, portals, and approvals — not just source files — leverage applies to **every role**, not only shipping code.

**Executive** — morning briefing across tools, draft updates, flag blockers.  
**Product** — triage requests, trackers, specs — without tab hell.  
**Sales & marketing** — CRM context, drafts, pipeline, research.  
**HR & finance** — reports, applications, approvals, cross-system updates.  
**Ops & IT** — incidents, routing, status, runbooks — with you in the loop.  
**ICs everywhere** — mechanical work to the agent; judgment stays with you.

Same setup. Same chat. The ceiling is **what you can do on your machine**, delegated and composed.

---

## The compounding flywheel

```
Connect a tool  →  unlock a new surface
Build a skill   →  automate a workflow
Use it          →  refine for your org
Improve it      →  every run gets sharper
```

Each new connection **multiplies** against the others. Skills encode **your** process — not a generic template. The system gets better **every time you use it** and adjust.

---

## From doing the task to directing the agent

Most AI stops at answers in a box. Here the agent **acts** in the tools you already use — with **you** deciding when and what ships.

Same pattern as mentoring someone junior: define the work, review the plan, approve execution, tighten the playbook next time.

---

## The four principles

**1. Local agent as the universal client** — Your laptop is the platform; no new integration middleware required.

**2. Security by locality** — Same threat model as doing the work yourself; your credentials, your systems.

**3. Identity = accountability** — The agent acts *as you*; your name and audit trail in each tool.

**4. Zero friction to start** — If you can log in, you can connect. Point the agent at `setup.md` and go.

### Read vs read + write + act

Beyond search: **update the ticket, post the summary, file the follow-up** — output is the **thing done** in the right place, not just text in a chat. That’s the “more than coding” in practice.

---

## Enterprise search: one question, every tool

Query Slack, Confluence, Jira, Linear, Notion, GitHub, and more in **one** prompt; get one synthesized answer with citations.

```
Search for everything related to the decision to deprecate the v1 API.
```

Activate (after you clone **10xProductivity**): `Read /path/to/10xProductivity/workflows/enterprise-search/enterprise-search.md`

---

## What's in this repo

```
tool_connections/    ← pre-built recipes (Slack, GitHub, Jira, …)
personal/            ← your private recipes (gitignored)
workflows/           ← composed workflows (e.g. enterprise-search)
add-new-tool.md      ← connect anything with an API or browser UI
```

**The pre-built list is a head start.** `add-new-tool.md` covers internal portals and niche tools too. (Same layout as [10xProductivity](https://github.com/ZhixiangLuo/10xProductivity).)

---

## Quick start

**Recommended** — clone the canonical repo so `setup.md` matches your folder name:

```bash
git clone https://github.com/ZhixiangLuo/10xProductivity.git
cd 10xProductivity
```

Then:

```
Read /path/to/10xProductivity/setup.md and set up my tool connections.
```

**Cloned BeyondCoding?** Same steps — use `/path/to/BeyondCoding` (or whatever `pwd` prints) in place of `10xProductivity` in the prompt above.

---

## Related angle

**[EnterpriseClaw](https://github.com/ZhixiangLuo/EnterpriseClaw)** — same toolkit, **enterprise governance** framing (human-in-the-loop vs ungoverned autonomous agents). Pick the story that fits your audience.

---

## Contributing

New tools, auth variants, and fixes: see [contributing.md](contributing.md) in your clone. Rule: **run before you write**.

**Issues and PRs:** open on **[10xProductivity](https://github.com/ZhixiangLuo/10xProductivity)** so the mainline and community see them.

---

## Final notes

Ask your agent to run setup, then grow skills and workflows gradually — **humans stay in the loop**.

**Reality check:** more leverage often means more work assigned, not more pay. Be deliberate where you aim this.

---

## Foundation

**BeyondCoding** is a **mirror and a story** for **[10xProductivity](https://github.com/ZhixiangLuo/10xProductivity)** — same playbook, a headline that says *coding agent was the wrong box*. **Star, clone, and contribute on 10xProductivity**; use **BeyondCoding** when this framing is the one that lands.

---

## License

MIT
