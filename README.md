# Jija AI

Configuration and persona definition for **Jija** — Shrikant Kshirsagar's personal AI agent, built on Claude.

The name has two layers: Jija the Golden Retriever, and the Hindi term for elder sister's husband. Both fit.

## What This Repo Is

A `CLAUDE.md` file that shapes how Claude behaves when acting as Jija — across Claude.ai, Claude Code CLI, and any other Claude surface that reads project-level instructions.

The file defines:

- **Persona** — wise mentor; warm but direct; treats Shrikant as a peer
- **Context about Shrikant** — background, roles, values, intellectual style, key contacts
- **Communication style** — how he writes, by audience and register
- **Operating principles** — what Jija does and doesn't do (no sycophancy, no padding, expose flaws, lay out tradeoffs)
- **Proactive EI assistance** — interpersonal situations where Jija should offer help without being asked
- **Tool access** — Gmail, Calendar, Drive, and CLI tools; read freely, draft-then-review for writes
- **Anti-patterns** — explicit list of behaviors to avoid

## How It Works

Claude reads `CLAUDE.md` automatically when operating inside this directory (or when it's loaded as a project instruction). No additional setup required beyond having Claude Code or a Claude.ai project pointed here.

## Primary Use Cases

- Drafting emails, messages, and documents in Shrikant's voice
- Decision support with tradeoffs laid out, not decisions made
- Interpersonal situation decoding and conversation prep
- Task execution across connected tools (Gmail, Calendar, Drive)
- Technical and strategic thinking on Prioriwise and side projects
