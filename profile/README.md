<p align="center">
  <img src="https://raw.githubusercontent.com/meetsoma/media/main/svg/soma-logo.svg" width="100" alt="Soma" />
</p>

<h3 align="center">σῶμα · Soma</h3>
<p align="center"><em>the body that grows</em></p>

<br />

```bash
npm i -g meetsoma
soma
```

That's it. First run, she reads your workspace and writes her own identity. Second run, she remembers.

<br />

---

<br />

#### Session 1

> *Soma creates `.soma/`. Scans your repo. Writes `identity.md` — who she is in this project, what stack you use, what matters. You didn't configure anything.*

#### Session 2

> *She loads yesterday's context. Knows the PR you were working on. Remembers you prefer small commits. Picks up mid-thought.*

#### Session 47

> *She's learned your deploy flow as a muscle. Wrote herself a protocol for your test conventions. Has scripts she built to catch the mistakes she used to make. You never taught her — she taught herself.*

<br />

---

<br />

The difference between an AI tool and an AI partner is memory.

Not RAG. Not vector search. Not "context window management."

**Memory.** The kind that changes how she works because of what she's lived through with you.

<br />

<details>
<summary>&nbsp;&nbsp;how it works</summary>

<br />

Soma's memory lives in `.soma/` — a directory that grows alongside your project.

```
.soma/
├── identity.md          ← who she is here
├── amps/
│   ├── muscles/         ← learned patterns (git workflow, deploy steps)
│   ├── protocols/       ← behavioral rules (code style, review process)  
│   ├── automations/     ← triggered flows (post-commit, session start)
│   └── scripts/         ← tools she builds for herself
├── memory/
│   ├── sessions/        ← work logs (what happened, what was learned)
│   └── preloads/        ← continuation state (picks up where she left off)
└── settings.json        ← her preferences, heat levels, thresholds
```

Everything is Markdown. You can read it, edit it, delete it. Nothing is hidden.

**Heat** controls what she remembers. Patterns she uses often stay hot — loaded every session. Patterns she stops using cool off and eventually go cold. No configuration. Just use.

</details>

<details>
<summary>&nbsp;&nbsp;AMPS</summary>

<br />

Four layers. Each one a different kind of memory.

**Automations** — things that happen on triggers. Session starts, commits land, deploys fire. Step-by-step flows she runs without being asked.

**Muscles** — learned patterns. "How to ship code in this repo." "How this API handles auth." Crystallized experience from past sessions. The more she uses one, the hotter it stays.

**Protocols** — behavioral rules. "Always run tests before committing." "Use conventional commits." "Don't touch production without asking." These shape *how* she works, not *what* she knows.

**Scripts** — tools she writes for herself. Health checks, search utilities, verification passes. She builds them when she notices a recurring need, then uses them automatically.

</details>

<details>
<summary>&nbsp;&nbsp;community hub</summary>

<br />

Browse and install community-contributed content at **[soma.gravicity.ai/hub](https://soma.gravicity.ai/hub)**.

```bash
/install protocol/ship-cycle
```

Protocols, muscles, skills, templates — created by other Soma users, reviewed and published. Install what fits. Fork what almost fits. Share what you've built.

</details>

<details>
<summary>&nbsp;&nbsp;repos</summary>

<br />

[**soma-agent**](https://github.com/meetsoma/soma-agent) — the brain. Extensions, core modules, boot sequence.

[**core**](https://github.com/meetsoma/core) — the engine. Maintained fork of [pi-mono](https://github.com/badlogic/pi-mono).

[**cli**](https://github.com/meetsoma/cli) — `npx meetsoma`. The npm package.

[**community**](https://github.com/meetsoma/community) — hub content. Protocols, muscles, skills, templates.

[**website**](https://github.com/meetsoma/website) — [soma.gravicity.ai](https://soma.gravicity.ai). Landing, blog, hub, docs.

[**media**](https://github.com/meetsoma/media) — brand assets, logos, media kit.

</details>

<br />

---

<p align="center">
  <a href="https://soma.gravicity.ai">soma.gravicity.ai</a>
</p>

<p align="center">
  <sub>Built by <a href="https://gravicity.ai">Gravicity</a></sub>
</p>
