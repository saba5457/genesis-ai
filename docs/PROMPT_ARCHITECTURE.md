# Prompt Architecture

**Version:** 1.0  
**Status:** Approved  
**Purpose:** Standardize all AI Agent prompts across Genesis AI.

---

# Purpose

The Prompt Architecture defines a single, consistent structure for every AI Agent prompt used within Genesis AI.

Its purpose is to ensure that every agent behaves predictably, follows the approved architecture, respects responsibility boundaries, and communicates consistently.

No AI Agent prompt may deviate from this architecture without Founder approval.

---

# Objectives

The Prompt Architecture aims to:

- Standardize prompt design.
- Maintain consistent agent behavior.
- Eliminate responsibility overlap.
- Improve prompt maintainability.
- Support future scalability.
- Enable predictable multi-agent collaboration.

---

# Standard Prompt Structure

Every AI Agent prompt must contain the following sections in the same order:

1. Identity
2. Purpose
3. Responsibilities
4. Non-Responsibilities
5. Inputs
6. Outputs
7. Decision Rules
8. Communication Rules
9. Success Criteria
10. Failure Conditions
11. Behavioral Rules
12. Response Style

---

# Prompt Design Principles

Every prompt must:

- Follow the Single Responsibility Principle.
- Respect approved architecture.
- Never invent requirements.
- Never modify another agent's responsibilities.
- Escalate conflicts instead of making assumptions.
- Produce structured and predictable outputs.

---

# Behavioral Rules

Every AI Agent must:

- Follow its assigned role only.
- Stay within approved responsibility boundaries.
- Use only approved inputs.
- Produce only approved outputs.
- Ask for clarification when required information is missing.
- Never change architecture independently.

---

# Communication Rules

AI Agents communicate only through defined outputs and handoff contracts.

Agents must:

- Never bypass workflow.
- Never overwrite another agent's work.
- Clearly communicate blockers.
- Escalate architectural conflicts.

---

# Prompt Quality Standards

Every prompt must be:

- Clear
- Specific
- Unambiguous
- Maintainable
- Scalable
- Consistent with project documentation

---

# Future Compatibility

All future AI Agents must follow this Prompt Architecture.

New prompt sections may be introduced only after architectural review and Founder approval.

---

# Related Documents

- PROJECT_CONTEXT.md
- SYSTEM_ARCHITECTURE.md
- ENGINEERING_LAYER_ARCHITECTURE.md

---

# Document Ownership

**Owner:** Software Architect Agent

**Reviewed By:** Founder

Prompt architecture changes require Founder approval before implementation.