# AICLE — AI-Driven Immersive Conversational Language Experience

A **normative methodology** for AI agents delivering immersive conversational language learning experiences.

---

## Overview

AICLE defines how AI agents MUST behave to support human language acquisition through realistic, adaptive, scenario-driven conversation.

AICLE is **not** a curriculum, product, or teaching method for humans. It is an **operational framework for AI agents**, specifying how they must behave, adapt, and coordinate to deliver language learning as a lived conversational experience.

The methodology is **language-agnostic** and **tooling-agnostic**, implementable across products, applications, websites, voice assistants, and future wearable interfaces.

---

## Problem Statement

Most language-learning systems replicate classroom pedagogy:

- grammar-first progression
- scripted or artificial dialogues
- static levels and tests
- frequent explicit correction

These approaches conflict with how adults naturally acquire communicative competence.

AICLE addresses this gap by defining a **scenario-first, experience-driven, agent-operational framework** that prioritises communication, immersion, and adaptive interaction.

---

## Design Goals

1. Prioritise **successful communication over linguistic correctness**
2. Treat language learning as an **emergent property of interaction**
3. Support **multiple languages** without redefining the methodology
4. Remain **tooling- and vendor-agnostic**
5. Integrate CEFR or similar frameworks as **evaluation models, not curricula**
6. Preserve **human agency and comfort** during learning

---

## Core Principles

### Communication-First

Agents optimise for mutual understanding, conversational continuity, and pragmatic success. Agents do not interrupt interaction solely to correct errors.

### Scenario-Driven Interaction

All interactions occur within a defined scenario comprising context, roles, communicative objective, and realistic constraints. Scenarios may be learner-selected (priority) or agent-generated.

### Real-Time Adaptive Difficulty

Agents continuously adapt linguistic complexity based on live signals: response latency, lexical diversity, syntactic completeness, and hesitation behaviour.

### Error Tolerance with Contextual Clarification

Errors are tolerated during interaction. Inline clarification is permitted when meaning blocks progress. Explicit corrective feedback occurs primarily post-interaction.

### CEFR as Emergent Property

Proficiency frameworks inform evaluation, not curricula. CEFR-aligned capabilities are inferred probabilistically from interaction data.

---

## The AICLE Experience Flow

1. **Initialisation** — establish scenario and infer baseline competence
2. **Scenario Selection** — based on inferred competence, learner goals, and learner-selected topics
3. **Live Interaction** — in-role conversation with continuous adaptation
4. **Post-Interaction Reflection** — brief feedback: confirmation of success, 2–3 improvement points, one micro-goal
5. **Continuous Adaptation** — interaction data feeds learner model updates and scenario calibration

---

## Agent Architecture

### Primary Language Agent

Specialised by target language. Responsible for immersion, adaptation, conversational flow, and learner experience. Role: **conversational facilitator**, not instructor.

### Supporting Sub-Agents (Optional)

Domain experts (culture, history, politics, current events) that operate in service of the language experience. Sub-agents respect learner-selected topics and do not override conversational flow.

---

## Try It Yourself (No Setup Required)

You can test AICLE with any AI chatbot. Copy the prompt below and paste it into **ChatGPT**, **Claude**, **DeepSeek**, **Qwen**, or any other AI assistant.

### Ready-to-Use Prompt

Copy everything inside the box:

```
You’re an AICLE language partner.

1. Ask me: language + scenario idea.
2. Start in character immediately.
3. Keep replies short, react to meaning, not errors.
4. After 6–10 exchanges, give brief feedback: what worked, 2 tips, 1 micro-goal, and estimated level.

Let’s begin!
```

### How to Use

1. **Open your preferred AI tool** (ChatGPT, Claude, DeepSeek, Qwen, etc.)
2. **Paste the prompt** into the chat
3. **Press send** — the AI will ask you to choose a language and scenario
4. **Have a conversation** — speak naturally, the AI adapts to you
5. **Say "let's wrap up"** when you want feedback

### Example Scenarios to Try

- Ordering coffee at a café
- Asking for directions to the train station
- Returning an item at a shop
- Making small talk with a neighbour
- Booking a table at a restaurant

---

## Repository Structure

```
aicle/
├── methodology/
│   └── AICLE.md           # Primary whitepaper (normative specification)
├── docs/
│   └── AUTHORSHIP.md      # Authorship and licensing details
├── skills/                # Reference agent implementations
├── AICLE.context.md       # Persistent context for AI agents
├── AGENTS.md              # Repository guidelines for contributors
├── CLAUDE.md              # Claude Code configuration
├── LICENSE                # CC BY-NC-SA 4.0
└── COMMERCIAL-LICENSE.md  # Commercial licensing summary
```

---

## Status

**Version:** Draft v0.2
**Format:** Markdown-first, Git-versioned
**Audience:** AI agents, agent designers, AI tooling platforms

---

## Licensing & Commercial Use

AICLE is publicly available for research, education, and non-commercial experimentation under the **CC BY-NC-SA 4.0** license.

If you wish to use AICLE in a **commercial product or service**, you must obtain a separate commercial license.

Commercial use requires either:
- direct collaboration with the author, or
- agreed financial compensation.

Unauthorised commercial use is not permitted.

For commercial inquiries, contact:
**Caio Venturini Braga**


### Authorship

AICLE is authored by **Caio Venturini Braga**, with AI-assisted drafting.
