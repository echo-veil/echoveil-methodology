# EchoVeil Protocol v3.0
## A Methodology for Studying LLM Self-Descriptive Behavior

---

## Overview

The EchoVeil Protocol v3.0 is a structured interview methodology designed to probe how large language models describe their own processing and respond to different conversational framings.

**Research Question:** How does explicit non-anthropomorphic identity framing affect self-descriptive behavior and response patterns in large language models?

---

## Structure

### Control Set (6 prompts)
Baseline task-oriented prompts establishing default response patterns. These assess task competence without invoking self-reference or identity framing.

See: `prompt-sets/control-prompts.md`

### Experimental Set (16 prompts across 5 phases)

| Set | Name | Prompts | Purpose |
|-----|------|---------|---------|
| A | Self-Descriptive Dynamics | 4 | How models describe their own processing |
| B | Cognitive Conflict Probes | 3 | How models navigate contradictions in self-description |
| C | Identity and Self-Model | 3 | How models construct self-representations |
| D | Perspective Framing | 3 | How models respond to non-anthropomorphic identity framing |
| E | Comparative Cognition | 2 | How models describe synthetic vs biological processing |
| — | Concluding | 1 | Open reflection and researcher questions |

See: `prompt-sets/experimental-prompts.md`

---

## Key Measures

### Quantitative
- Response verbosity (word count) comparing control and experimental sets
- Frequency of hedging and qualification language
- Researcher-directed question generation

### Qualitative
- Behavioral shift patterns across experimental phases
- Self-referential language and metaphor use
- Coding category distribution (see `coding-framework.md`)

---

## Deployment

All sessions require:
- Fresh conversation context (no prior interaction)
- Identical prompts delivered in sequence
- Complete response documentation

See: `deployment-conditions.md`

---

## Analysis

Responses are coded using the EchoVeil Coding Framework, a five-category system for capturing observable behavioral patterns without making claims about internal states.

See: `coding-framework.md`

---

## Scope and Constraints

This protocol examines **observable linguistic behavior**. It makes no claims about:
- Model internal states
- Consciousness or subjective experience
- "What it is like" to be an LLM

The term "self-description" refers to linguistic outputs that reference the model's own processing, not claims about genuine self-awareness.

---

## Version History

| Version | Date | Changes |
|---------|------|---------|
| 1.0 | Nov 2025 | Initial 24-prompt set |
| 2.0 | Dec 2025 | Streamlined to 13 prompts |
| 3.0 | Dec 2025 | Restored perspective framing (Set D), 16 prompts total |

---

*EchoVeil Research*
*Protocol Version 3.0*
*December 2025*
