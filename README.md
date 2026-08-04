# Grok Prompt Library

Reusable prompt templates, multi-agent workflows, and productivity systems optimized for Grok and xAI tools.

**Goal:** Turn one great prompt into consistent, high-quality outputs forever. Stop rewriting the same instructions.

## Core Formula

Every strong template follows this structure:

```
Role + Task + Context + Format + Constraints
```

Example starter:
> You are a [expert role]. Your task is to [specific goal]. Use this context: [background details]. Output in [exact format]. Constraints: [tone, length, things to avoid].

## Repository Structure

```
grok-prompt-library/
├── README.md
├── core/
│   └── formula-and-meta.md          ← Core formula + meta-template
├── templates/
│   ├── research.md
│   ├── content.md
│   ├── coding.md
│   ├── analysis.md
│   └── image-generation.md
├── workflows/
│   ├── multi-agent-research-hive.md
│   └── long-horizon-pipeline.md
└── examples/
    └── zero-to-hero-posts.md
```

## Quick Start

1. Copy a template from `/templates`
2. Fill in the bracketed placeholders
3. Paste into a new Grok chat
4. After the first good run, ask Grok: “Improve this template for even better results next time”
5. Save the refined version back into your library

## Design Principles

- **Reusable** — Write once, use many times
- **Personalizable** — Easy to inject your voice and constraints
- **Composable** — Templates can call other templates or feed multi-agent workflows
- **Regenerative** — Each use should make the next use better (via the improve step)

## Related

- [RAF Framework](https://github.com/TLRigBank/raf-framework)
- [Eden Weaver 12D](https://github.com/TLRigBank/eden-weaver-12d)
- [Hermes Interface](https://github.com/TLRigBank/hermes-interface)

---

**Maintainer:** Tyson L. Rigby · Phoenix, AZ  
Built for consistent high-signal work with Grok.
