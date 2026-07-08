# Reasoning Models

**o1, o3, DeepSeek R1, Gemini Thinking — the new class of AI that thinks before it answers.**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

---

## What Are Reasoning Models?

Standard LLMs: Input → Immediate Output

Reasoning LLMs: Input → Hidden Thinking (chain of thought) → Better Output

Reasoning models explicitly think through problems before answering —
dramatically improving accuracy on complex tasks.

## Model Landscape 2025

| Model | Company | Best For | Cost vs GPT-4o |
|---|---|---|---|
| o3 | OpenAI | Hardest problems | ~20x higher |
| o4-mini | OpenAI | Cost-efficient reasoning | ~2x higher |
| Claude (thinking) | Anthropic | Reasoning + long context | ~3x higher |
| DeepSeek R1 | DeepSeek | Open source reasoning | Free (local) |
| Gemini 2.5 Pro | Google | Multimodal reasoning | ~3x higher |

## When to Use Reasoning Models

### USE for:
- Complex math (multi-step calculations, optimization)
- Code debugging (finding subtle bugs, logic errors)
- Strategic planning (multi-factor decisions)
- Research synthesis (connecting insights across sources)
- Contract analysis (finding edge cases)

### DO NOT use for:
- Simple text generation (email, summaries) — too slow and expensive
- Real-time applications — latency too high
- High-volume simple tasks — too expensive
- Creative writing — standard models are better

## Prompting Reasoning Models

**Key insight:** Less prompting is more.

Standard LLM: Need detailed step-by-step instructions.
Reasoning model: Just state the problem clearly, it figures out how to solve it.

Give the full complexity — don't simplify the problem for the model.

## DeepSeek R1 — The Open Source Alternative

DeepSeek R1 matches o1 performance at a fraction of the cost.
Can be run locally for free on powerful hardware.
The thinking process is visible in the API response.

---

Part of the [Real-World AI Skills Ecosystem](https://github.com/saitejabandaru-in)
