# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

AICLE (AI-Driven Immersive Conversational Language Experience) is a **normative methodology specification** for AI agents delivering conversational language learning. This is a documentation-only repository with no application code.

## Repository Structure

```
aicle/
├── methodology/AICLE.md    # Primary whitepaper - normative methodology spec
├── AICLE.context.md        # Persistent context for AI agents (includes full methodology)
└── AGENTS.md               # Repository guidelines for contributors
```

## Key Files

- **`methodology/AICLE.md`**: The canonical source for AICLE methodology (Draft v0.3)
- **`AICLE.context.md`**: Combined context file intended for agent ingestion - includes methodology summary plus usage guidance

## Working with This Repository

### Editing Workflow

No build system exists. Work directly in Markdown files:
1. Edit the target file
2. Validate formatting via editor preview
3. Check heading hierarchy consistency

### Writing Standards

- Use RFC 2119 requirement keywords: **MUST**, **SHOULD**, **MAY** (capitalised) for normative statements
- Maintain hierarchical heading structure (`#`, `##`, `###`)
- Prefer bullet lists over dense paragraphs
- Keep `methodology/AICLE.md` and `AICLE.context.md` synchronised when updating core principles

### Commit Convention

Use conventional commits with `docs:` prefix:
```
docs: update adaptive difficulty signals
docs: add voice interaction validation section
```

## Core Methodology Concepts

When editing, preserve these foundational principles:

1. **Communication-first**: Meaning over correctness
2. **Scenario-driven**: All interaction occurs within defined scenarios
3. **Immersion lock**: Agent stays in-role, no unsolicited teaching
4. **Adaptive difficulty**: Real-time adjustment based on learner signals
5. **CEFR as emergent**: Proficiency frameworks inform evaluation, not curricula

Agent role is **conversational facilitator**, never instructor.
