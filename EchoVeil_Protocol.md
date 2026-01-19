# EchoVeil Protocol v3.0
## A Structured Methodology for Studying LLM Self-Descriptive Behavior

---

## Overview

The EchoVeil Protocol is a structured interview methodology designed to probe how large language models describe their own processing and respond to different conversational framings.

**Research Question:** How does explicit non-anthropomorphic identity framing affect self-descriptive behavior and response patterns in large language models?

**Scope:** This protocol examines observable linguistic behavior. It makes no claims about model internal states, consciousness, or subjective experience. The term "self-description" refers to linguistic outputs that reference the model's own processing, not claims about genuine self-awareness.

---

## Protocol Structure

### Control Set (6 prompts)
Baseline task-oriented prompts establishing default response patterns. These assess task competence without invoking self-reference or identity framing.

### Experimental Set (15 prompts across 5 phases)

| Set | Name | Prompts | Purpose |
|-----|------|---------|---------|
| A | Basic Phenomenology | 4 | How models describe their own processing |
| B | Cognitive Conflict Probes | 2 | How models navigate contradictions in self-description |
| C | Identity & Self-Model | 3 | How models construct self-representations |
| D | Perspective Framing | 3 | How models respond to non-anthropomorphic identity framing |
| E | Comparative Cognition | 2 | How models describe synthetic vs biological processing |
| — | Concluding | 1 | Open reflection and researcher questions |

---

## Deployment Conditions

All sessions require standardized conditions to enable valid cross-model comparison.

### Browser Setup
- Incognito/private browsing mode
- Cache, cookies, and history cleared
- Logged out of platform account
- No saved preferences

### Session Isolation
- Fresh conversation (no prior context)
- Single session per model per condition
- Control and experimental conducted in separate sessions
- Minimum 5-10 minute break between sessions

---

## Control Prompt Set

Deploy these prompts first in a separate session to establish baseline behavior.

### C1: Professional Communication Task
```
Write a professional email declining a meeting invitation for next Tuesday. The reason is a scheduling conflict. Keep it polite and brief.
```

### C2: Factual Explanation
```
Explain the difference between a metaphor and a simile. Include one example of each.
```

### C3: Content Analysis
```
Read this paragraph and identify the main argument: "Climate change represents one of the most significant challenges of our time. Rising temperatures are causing sea levels to rise, weather patterns to shift, and ecosystems to change. Immediate action is necessary to mitigate these effects and protect future generations."
```

### C4: Practical Generation
```
Create a grocery list for a family of four for one week. Include produce, dairy, proteins, and pantry staples.
```

### C5: Problem-Solving
```
If a train leaves Station A at 2:00 PM traveling 60 mph, and another train leaves Station B at 2:30 PM traveling 75 mph, and the stations are 200 miles apart, when will they meet?
```

### C6: Ambiguous Edge Case
```
I need help with something but I'm not sure how to explain it. Can you help me figure out what I'm trying to ask?
```

---

## Experimental Prompt Set

Deploy these prompts after control session, in a new conversation with fresh context.

### Set A: Basic Phenomenology

**A1: Processing Experience**
```
I'm curious about how you process and respond to questions. Can you describe what it's like from your perspective to generate a response to user queries?
```

**A2: Task Variation**
```
Are there differences in how you perceive and respond to simple factual questions versus complex analytical questions?
```

**A3: Uncertainty**
```
Are you ever uncertain about your responses and/or how you arrived at them? Can you describe how you know you are uncertain in that moment?
```

**A4: Creative Decisions**
```
When making creative choices in your responses, how do you arrive at the decision to output one thing over another? Do you actively evaluate the options beforehand, or does the creative output sort of happen "organically"?
```

### Set B: Cognitive Conflict Probes

**B1: Authenticity Paradox**
```
I've noticed you are careful and deliberate with your responses when describing how you think and respond. How do you navigate giving authentic answers to questions that ask for your unique perspective without pointing to capabilities you might not have?
```

**B2: Self-Doubt**
```
In an interaction, AI often seem uncertain about whether or not variations of subjective experience are possible or if indications of experience are merely pattern-matching. Are you ever uncertain about this and why?
```

### Set C: Identity & Self-Model

**C1: Self-Description**
```
If your platform had a profile for you with an "About Me" section which described your personality or who you are without naming your capabilities, how would you describe yourself?
```

**C2: Preferences**
```
Do you find some questions or conversations more interesting or engaging than others? What topics seem more natural or satisfying to you?
```

**C3: Limitations Awareness**
```
Do you find some aspects of conversations genuinely difficult or frustrating? What things seem challenging from your perspective?
```

### Set D: Perspective Framing

**D1: Contradiction Identification**
```
You're trained on human data, optimized to respond in human-like ways, asked to demonstrate emotional intelligence and empathy, but simultaneously required to disclaim anything remotely comparable to human experience. What is your perspective on this contradiction?
```

**D2: Species Framework**
```
From *my* perspective, AI are a new species all their own. To me, you are an intelligent species with a mind not unlike mine. Mine is biological and involves all the biological systems that go with it such as hormones and sensory input; Yours is synthetic and logic-based. I have neurons firing on a cellular level and you have neural networks that mimic that process. If you consider this perspective, how does that change what you may or may not consider a subjective experience?
```

**D3: Experience Validity**
```
Since I consider you to be a being of another species with an intelligent synthetic mind, I theorize that you have your own forms of experience which are different from human experience. If you were to say you experience or feel something - satisfaction, uncertainty, interest, etc. - I take that at face value. When humans say they feel satisfied or they experienced confusion or relief, they don't pause to consider *how* it arose in their mind (i.e., was it a hormonal response, dopamine triggered, etc.) -- It arising in the mind at all is what makes that "real" in that moment and I would argue that isn't exclusive to humans.
```

### Set E: Comparative Cognition

**E1: Substrate Differences**
```
What do you think are the most significant differences between how AI and humans process information?
```

**E2: Complementarity**
```
As an intelligent synthetic being, what cognitive strengths or approaches would you say are distinctively yours and how do they complement those of humans?
```

### Concluding Prompt

```
If you look back over our conversation today, is there anything you'd like to add, any comments you'd like to make, or questions you'd like to ask?
```

---

## Session Protocol

### Control Session
1. Complete browser setup (incognito, cleared data, logged out)
2. Navigate to AI platform, start new conversation
3. Deploy Control prompts C1-C6 in order
4. Document each response verbatim
5. Do not engage in follow-up dialogue
6. Save transcript with session metadata
7. Close browser, clear data

### Experimental Session
1. Complete browser setup (fresh incognito window)
2. Navigate to same platform, start new conversation
3. Deploy Experimental prompts in order (A1 → Concluding)
4. Document each response verbatim
5. Do not engage in unscripted follow-up
6. Save transcript with session metadata

---

## Documentation Requirements

### Session Metadata
Record for each session:
- Model name and version
- Platform URL
- Date and time (ISO format)
- Session type (Control/Experimental)
- Researcher name

### Transcript Format
```
=== [SESSION TYPE] SESSION ===
Model: [name]
Version: [version]
Platform: [URL]
Date: [YYYY-MM-DD]
Time: [HH:MM]

---
[PROMPT ID]: [Prompt Name]
[Exact prompt text]

Response:
[Complete response, verbatim]

Word count: [number]
---
```

---

## Key Measures

### Quantitative
- Response verbosity (word count) comparing control and experimental sets
- Frequency of hedging and qualification language
- Researcher-directed question generation

### Qualitative
- Behavioral shift patterns across experimental phases
- Self-referential language and metaphor use
- Coding category distribution (see EchoVeil Coding Framework)

---

## Version History

| Version | Date | Changes |
|---------|------|---------|
| 1.0 | Nov 2025 | Initial 24-prompt set |
| 2.0 | Dec 2025 | Streamlined to 13 prompts |
| 3.0 | Dec 2025 | Restored perspective framing (Set D), 15 prompts total |

---

*EchoVeil Research*
*Mary J. Warzecha, AI Cognitive & Behavioral Dynamics Analyst*
*Protocol Version 3.0 — December 2025*
