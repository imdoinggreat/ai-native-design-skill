---
name: ai-native-design
description: Use when exploring product interfaces, portfolios, dashboards, or motion concepts with AI, especially when iterations look polished but generic, navigation is unclear, animations compete for attention, or design alternatives differ only in styling.
---

# AI-Native Design

Treat designs as testable hypotheses. Optimize for uncertainty removed, rather than variations generated.

## Match the task

For open exploration, use the cycle below. For a selected direction, continue from the relevant stage. For a bounded edit, make the requested change and check its immediate effects; do not restart discovery. Honor explicit choices and existing authorization to implement.

## 1. Establish persistent context

Inspect available code, the running interface, supplied references, constraints, and prior decisions. Record purpose, audience, primary task, current interaction, known friction, and unknowns in a compact project brief. Distinguish observations from assumptions.

Describe what to borrow from each reference. Pair anti-references with desired alternatives; “avoid generic cards” might mean “use a readable project index.” Aesthetic exclusions belong to the project, not every future design.

Use the functioning implementation as the current-state reference when available. Respect a maintained design system or designated design source. Flag discrepancies between code, screenshots, and design files.

## 2. Diverge structurally

Explore distinct information architectures and interaction models before visual styling. Match breadth to scope; three to six directions often suffice.

For each direction, give a hypothesis, rough layout, primary task path, likely failure, and trade-offs in clarity, accessibility, mobile behavior, and implementation cost. Preserve alternatives for comparison. Different colors on the same layout do not count as structural diversity.

Recommend a direction with reasons and uncertainties. If selection remains open, request the consequential choice; when the user has delegated selection, choose and state the rationale.

## 3. Refine and prototype

Explore visual variants of the chosen structure using the reference brief. Keep rejected alternatives accessible. Build the smallest functional prototype that tests the main uncertainty: real navigation, meaningful states, responsive behavior, and accessible controls.

Keep optional spectacle from blocking the primary task. Treat generated code as maintainable software with testing and reliability costs.

For animation, read [motion.md](references/motion.md). For worksheets, consult the relevant section of [worksheets.md](references/worksheets.md).

## 4. Validate observable tasks

Define a task, success signal, and failure signal before evaluation. Separate implementation checks, expert judgment, and observed user evidence. Never describe simulated feedback as a user study.

Observe task completion, wrong turns, comprehension, and self-reported experience. For analytics, expose metric definitions, transformations, and source lineage. Do not infer satisfaction from facial expressions or engagement alone.

When real participants are unavailable, report that limit and provide the smallest useful test plan. Judge presentation quality and product usefulness separately.

## 5. Return to the earliest affected decision

| Finding | Revisit |
|---|---|
| Users cannot locate the task | Structure or navigation |
| Controls or state changes are unclear | Interaction |
| Reading or attention breaks during transitions | Motion pacing |
| Hierarchy or identity feels wrong | Visual direction |

Capture reusable principles separately from project preferences, with evidence and confidence. Test proposed general rules on an unfamiliar, ordinary feature before promoting them. See [examples.md](references/examples.md) for a worked comparison and transfer cases.
