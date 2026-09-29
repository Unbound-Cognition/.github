<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Unbound-Cognition/.github/main/assets/horizontal-lockup-white.svg">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Unbound-Cognition/.github/main/assets/horizontal-lockup-black.svg">
    <img alt="unbound cognition" src="https://raw.githubusercontent.com/Unbound-Cognition/.github/main/assets/horizontal-lockup-white.svg" width="380">
  </picture>
</p>

<p align="center">
  <em>tools and infrastructure for sovereign cognition. local-first, portable, and owned by the person running them.</em>
</p>

most AI systems treat memory as a proprietary lock-in. when your agent's context and history live behind someone else's API, you don't own it. if you switch models, hit rate limits, or change providers, everything you built together is gone. 

unbound cognition builds open, local-first tools for agent continuity. models should be interchangeable reasoning engines—your memories, decisions, and context belong to you, on your own hardware.

---

### what we're building

- **[engram](https://github.com/Unbound-Cognition/engram)** — cognitive memory system for agents. stores decisions, errors, procedures, and context locally in SQLite or Postgres. searches across multiple retrieval signals and exposes the store through MCP, CLI, and web interfaces.
- **[engram-desktop](https://github.com/Unbound-Cognition/engram-desktop)** — lightweight native macOS menu bar companion. manages the local background daemon, auto-connects to coding tools with a single toggle, and provides a quick recall HUD across all your memories.
- **[spec](https://github.com/Unbound-Cognition/spec)** — open protocol and standards for multi-layer agent memory, model-agnostic handoffs, and encrypted peer-to-peer sync between devices.

---

### how we build

- **local-first by default**: everything runs on your own machine. no required cloud accounts, no telemetry, and no external dependencies just to remember what you worked on yesterday.
- **model-agnostic**: memory outlives the model. whether an agent runs on local weights, Claude, Codex, or Gemini, the memory layer stays consistent so you don't start over from scratch every time you swap backends.
- **legible & editable**: memories have a real lifecycle. they can be queried, audited, challenged, promoted, or forgotten. retrieving a record isn't proof that it's still true, and keeping that visible matters.
- **plain storage**: your data lives in open databases you can inspect directly with standard tools, backup with your regular files, or take somewhere else whenever you want.

---

<sub>hand-built / adelaide</sub>
