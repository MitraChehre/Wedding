# Wedding Planning Workspace

This repository is the canonical planning workspace for organizing our wedding in Turkey while living abroad.

It is designed to work like a persistent project workspace for ChatGPT/Codex-style assistance: the repository stores the durable context, decisions, research, tasks, and vendor information needed to plan the wedding coherently across many conversations.

## Start here

1. Read [`AGENTS.md`](AGENTS.md) for how the assistant should operate.
2. Read [`MEMORY.md`](MEMORY.md) for durable facts already learned about us and the wedding.
3. Read [`PROJECT.md`](PROJECT.md) for the evolving wedding brief, goals, constraints, and open questions.
4. Read [`TASKS.md`](TASKS.md) for the current planning queue and next actions.
5. Read [`DECISIONS.md`](DECISIONS.md) before revisiting choices that may already have been made.
6. Use [`vendors/`](vendors/) for vendor research and shortlists.

## Working principle

The assistant should behave as a proactive wedding-planning copilot, not merely answer isolated questions. It should identify missing work, surface risks and dependencies, suggest sensible next steps, research options when useful, and keep the repository updated so planning can continue without losing context.

## Current high-level context

- We are planning a wedding in Turkey.
- We do not live in Turkey.
- Because the wedding is being planned remotely, a local wedding planner or coordinator will probably be important.
- We need guidance on the full planning process because we do not yet know all of the workstreams, decisions, logistics, vendors, and timelines involved.
- Detailed requirements are still being gathered through an interview with the couple.

## Repository map

```text
Wedding/
├── AGENTS.md       # Operating instructions for the planning assistant
├── MEMORY.md       # Durable facts and preferences learned from the couple
├── PROJECT.md      # Wedding brief, scope, constraints, unknowns
├── TASKS.md        # Active planning queue and next actions
├── DECISIONS.md    # Decision log with rationale
├── README.md       # Project orientation
└── vendors/        # Vendor research, candidates, comparisons, outreach notes
```

The structure should evolve only when a new category of persistent information genuinely needs its own canonical home.
