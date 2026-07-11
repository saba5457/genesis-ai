# Architecture Decision Records (ADR)

## Purpose

This directory contains the official **Architecture Decision Records (ADRs)** for Genesis AI.

An ADR documents an important architectural decision, the reasoning behind it, the available alternatives, and the long-term consequences of the chosen approach.

ADRs ensure that architectural knowledge remains traceable, reviewable, and maintainable throughout the project's lifecycle.

---

# Principles

Every ADR must:

- Record a single architectural decision.
- Explain why the decision was made.
- Consider relevant alternatives.
- Describe the consequences of the decision.
- Be reviewed before approval.
- Never contradict approved architecture.

---

# Naming Convention

Each ADR uses the following naming format:

```text
ADR-0001-short-title.md
ADR-0002-short-title.md
ADR-0003-short-title.md
```

ADR numbers are permanent.

Numbers must never be reused.

If an ADR becomes obsolete, it is marked as **Superseded** rather than deleted.

---

# ADR Lifecycle

1. Proposal
2. Architectural Review
3. Founder Approval
4. Documentation Update
5. Repository Commit
6. Git Push

An ADR becomes official only after Founder approval.

---

# Status Values

Every ADR must include one of the following statuses:

- Proposed
- Accepted
- Superseded
- Deprecated

---

# Relationship to Other Documentation

ADRs complement the existing documentation.

They do **not** replace:

- PROJECT_CONTEXT.md
- SYSTEM_ARCHITECTURE.md
- PROJECT_WORKFLOW.md
- PROJECT_HISTORY.md

Instead, ADRs capture **why** an architectural decision was made, while the other documents describe **what** the architecture is.

---

# Maintenance

New ADRs should only be created for significant architectural decisions.

Minor documentation updates or implementation details should not generate new ADRs.

All ADRs must remain immutable after acceptance.

If a decision changes, create a new ADR that supersedes the previous one instead of modifying history.