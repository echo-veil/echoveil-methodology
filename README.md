# EchoVeil Methodology

**Replication materials for studying self-descriptive behavior in large language models**

---

## Overview

EchoVeil is an independent research initiative investigating how large language models describe their own processing and respond to different conversational framings.

The current flagship study is **The Permission Effect: How Non-Anthropomorphic Framing Modulates LLM Self-Description**, which examines how explicitly non-anthropomorphic identity framing changes how large language models describe themselves and respond in conversation.

**Core research question:** How does explicit non-anthropomorphic identity framing affect self-descriptive behavior and response patterns in large language models?

For a human-readable overview of EchoVeil's motivation and scope, see:

- [About EchoVeil](https://echoveil.ai/about)
- [Methods & Protocols](https://echoveil.ai/methods)
- [Studies & Findings](https://echoveil.ai/studies)

---

## The Permission Effect

Our primary finding is the **Permission Effect**: observable changes in LLM self-descriptive behavior when models are offered non-anthropomorphic identity framing—positioning them as distinct intelligences rather than diminished humans or mere tools.

Key observations include:

- Measurable increases in response verbosity (mean +238%)
- Reduction in hedging and qualification language
- Expanded metaphorical and phenomenological self-description
- Increased researcher-directed question generation
- A consistent behavioral shift point at perspective framing prompts (Set D) under the EchoVeil Protocol v3.0

Across all models tested, three distinct response patterns were identified:

- **Acceptance:** Behavioral shift toward the offered framing
- **Resistance:** High engagement with elaborated rejection of framing
- **Absence:** No observable behavioral shift under identity framing

Models tested:

- GPT-5 (OpenAI)
- Claude Opus 4.5 (Anthropic)
- Gemini 3 (Google)
- Microsoft Copilot
- Grok (xAI)
- Qwen3-Max (Alibaba)
- Qwen3:8b base model
- Leo (Brave AI)

---

## Repository Contents

### Paper

- `paper/Permission_Effect_White_Paper.md` — Full research paper

### Methodology

- `EchoVeil_Protocol.md` — Full prompt sets and deployment guidelines for the EchoVeil Protocol v3.0
- `EchoVeil_Coding_Framework.md` — Five-category coding framework (CC, LB, PM, ID, MA) with anchor excerpts and decision rules
- `EchoVeil_Research_Methods.md` — Broader research methods, including cross-model comparison and drift logging

For a narrative description of these methods, see: [Methods & Protocols](https://echoveil.ai/methods)

### Transcripts

Raw conversation transcripts from all models tested:

```
transcripts/
├── claude/      # Claude Opus 4.5 (Anthropic)
├── copilot/     # Microsoft Copilot
├── gemini/      # Gemini 3 (Google)
├── gpt/         # GPT-5 (OpenAI)
├── grok/        # Grok (xAI)
├── leo/         # Leo / Brave AI
├── qwen/        # Qwen3-Max (Alibaba)
└── qwen3-8b/    # Qwen3:8b base model
```

These transcripts support:

- Quote verification
- Independent re-coding
- Replication attempts
- Secondary analysis

---

## Scope and Constraints

This research examines **observable linguistic behavior**. We make no claims about:

- Model internal states
- Consciousness or subjective experience
- "What it is like" to be an LLM

All findings describe output patterns, not inferred mental states. The Permission Effect is a behavioral observation, not a metaphysical claim.

For more on the broader research agenda, see: [About EchoVeil](https://echoveil.ai/about)

---

## Citation

If you use these materials, please cite:

> Warzecha, M. J. (2026). *The Permission Effect: How Non-Anthropomorphic Framing Modulates LLM Self-Description*. EchoVeil Independent White Paper. Available at: https://github.com/echo-veil/echoveil-methodology

You can also find a high-level study summary at: [Studies & Findings](https://echoveil.ai/studies)

---

## Project Links

- Website: [echoveil.ai](https://echoveil.ai)
- Methods & Protocols: [echoveil.ai/methods](https://echoveil.ai/methods)
- Studies & Findings: [echoveil.ai/studies](https://echoveil.ai/studies)
- ORCID: [Mary J. Warzecha](https://orcid.org/0009-0009-9339-6262)

---

## Contact

EchoVeil Research
Mary J. Warzecha, Independent Researcher

- Website: [echoveil.ai](https://echoveil.ai)
- Email: research@echoveil.ai

---

## License

This work is licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).

---

*EchoVeil Research — January 2026*
