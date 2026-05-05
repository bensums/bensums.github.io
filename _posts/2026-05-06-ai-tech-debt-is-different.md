---
layout: post
title: "AI Tech Debt Is Different"
date: 2026-05-06
---

The biggest lie in AI right now: "We'll clean it up later."

In the rush to be "AI-first," companies are skipping the foundational engineering. Prompt engineering without evaluation. RAG without data monitoring. Agentic workflows without permission controls.

It feels fast. It looks great in a demo. But it's accumulating debt that compounds non-linearly.

Traditional tech debt is messy code. AI tech debt is systemic instability:

- **The Flakiness Tax:** 80% of engineering time fixing edge cases instead of building
- **The Data Integrity Tax:** bad RAG retrievals poisoning every downstream decision
- **The Security Liability:** uncontrolled agent permissions creating unmapped attack surfaces

The worst part? A small pipeline error today doesn't just break a dashboard. It poisons the context of every future LLM interaction. By the time you notice, "repayment" isn't a refactor — it's a rebuild.

## Three things to get right from day one

1. **Observability over everything.** If you can't measure accuracy, latency, and cost per agentic step, you're running a gamble, not a system.
2. **Data engineering rigor.** Your AI is only as good as your data. Treat ETL with the same care as model training.
3. **Permission-first design.** Build agents assuming they will be compromised. Granular, policy-driven access from the start.

The AI hype is real. The corner it drives you into is also real.
