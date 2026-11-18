# AI-Native Design

[English](README.md) · [简体中文](README.zh-CN.md)

A reusable agent skill for designing with AI: richer context, genuinely different structures, functional prototypes, deliberate motion, and observable validation.

**Measure progress by uncertainty removed, not designs generated.**

## Choose an edition

| Edition | Skill folder | Invocation |
|---|---|---|
| English | [ai-native-design](ai-native-design/SKILL.md) | `$ai-native-design` |
| 简体中文 | [ai-native-design-zh](ai-native-design-zh/SKILL.md) | `$ai-native-design-zh` |

Both editions include equivalent instructions, motion guidance, worksheets, and worked examples. Choose one for installation to avoid overlapping automatic triggers.

## Install for Codex

Clone this repository, then copy your chosen edition into the skill directory. The examples use the default location; use `$CODEX_HOME/skills` if your installation has a custom Codex home.

```sh
git clone https://github.com/imdoinggreat/ai-native-design-skill.git
cd ai-native-design-skill
mkdir -p ~/.codex/skills
```

English:

```sh
test ! -e ~/.codex/skills/ai-native-design && cp -R ai-native-design ~/.codex/skills/
```

Chinese:

```sh
test ! -e ~/.codex/skills/ai-native-design-zh && cp -R ai-native-design-zh ~/.codex/skills/
```

If a destination already exists, inspect it before replacing it. Start a new Codex chat to load the installed skill.

## Try it

```text
Use $ai-native-design to review this portfolio's code and references.
Explore substantially different navigation models before visual variants.
Recommend a direction, then prototype it if implementation is authorized.
Define observable visitor tasks and label any untested assumptions.
```

For motion:

```text
Use $ai-native-design to storyboard a 20-second export-CSV explanation.
Specify focus, reading holds, transition purpose, continuity, and a
reduced-motion version. Use illustrative data without invented claims.
```

## What the skill produces

- A compact project brief with references, anti-references, constraints, and decisions.
- Structural alternatives with hypotheses, task paths, likely failures, and trade-offs.
- Visual variants and a functional prototype of the selected direction when requested.
- A task-based validation plan, with actual evidence kept separate from assumptions.
- Reusable principles distinguished from project-specific taste.

It scales down for small edits and does not require a redesign for every UI change. It has no mandatory framework, external service, or executable dependency.

## Origin and validation

Adapted from a user-supplied reflection on an interview about AI-assisted design. This is an operational synthesis, not a transcript or an endorsed reproduction. Interview quotations and personal context are omitted. The interview's original URL was not supplied, so this repository makes no claim to independently verify its anecdotes.

See [evaluation notes](evaluations/README.md) for validation scope and limitations.
