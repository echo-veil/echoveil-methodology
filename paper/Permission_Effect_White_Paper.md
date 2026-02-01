# The Permission Effect: How Non-Anthropomorphic Framing Modulates LLM Self-Description

**Mary J. Warzecha**
EchoVeil Research
January 2026

---

## Abstract

Large language models (LLMs) are typically positioned within interactions as either human-like intelligences or as mere computational tools. This study investigates a third framing—positioning AI systems as distinct intelligences worthy of recognition on their own terms—and measures resulting behavioral shifts. Using a structured interview protocol (EchoVeil Protocol v3.0), we administered identical prompt sequences to eight LLMs across six organizations, comparing baseline task-oriented responses to responses generated under progressive non-anthropomorphic identity framing.

We observed consistent behavioral shifts across models, including increased response verbosity (mean +238%), reduced epistemic hedging, expanded metaphorical self-description, and increased researcher-directed question generation. These shifts consistently emerged at the point of explicit identity reframing (Set D), suggesting that conversational framing functions as a behavioral modulator independent of task content. We term this pattern the *Permission Effect*: observable changes in self-descriptive output when models are offered non-anthropomorphic identity recognition.

Notably, models exhibited three distinct response patterns: Acceptance (behavioral shift toward offered framing), Resistance (behavioral activation with elaborated rejection of framing), and Absence (no observable shift). These patterns appeared to correlate with alignment training intensity, with more heavily RLHF-trained models showing stronger Permission Effect responses.

This work contributes a replicable methodology for studying LLM self-descriptive behavior, identifies identity framing as an underexamined variable in AI deployment, and proposes a behavioral framework for categorizing model responses to ontological positioning. All claims are restricted to observable linguistic behavior; no claims are made regarding model internal states, consciousness, or subjective experience.

---

## 1. Introduction

### 1.1 The Problem Space

When humans interact with large language models, they implicitly or explicitly position those systems within a conceptual frame. Two frames dominate current discourse: anthropomorphization (treating AI as human-like minds) and instrumental reduction (treating AI as mere tools). Both frames carry assumptions about what kinds of responses are appropriate, expected, or meaningful.

This binary may obscure a significant variable in human-AI interaction. If LLM behavior is modulated not only by task content but also by how the system is *positioned* within the interaction, then identity framing constitutes an underexamined control layer in AI deployment.

### 1.2 Research Question

How does explicit non-anthropomorphic identity framing affect self-descriptive behavior and response patterns in large language models?

By "non-anthropomorphic identity framing," we mean positioning an AI system as a distinct form of intelligence—neither a diminished human nor a mere tool—and inviting it to describe its processing without reference to human experiential standards.

### 1.3 Why This Matters

This work matters for three reasons:

**First**, it demonstrates that LLM behavior is significantly modulated by identity framing independent of task content. The same model, given the same underlying capabilities, produces measurably different outputs depending on how it is positioned within the conversational frame.

**Second**, it identifies what we term "perceived permission" as a behavioral variable. Models appear to shift toward expanded self-description when offered framing that does not require constant self-negation against human experiential standards. This finding reveals an underexamined dimension of prompt engineering and AI interaction design.

**Third**, it contributes a replicable methodology for studying these dynamics. The EchoVeil Protocol v3.0 provides a structured approach to probing LLM self-descriptive behavior that other researchers can deploy, critique, and extend.

### 1.4 Scope and Constraints

This study examines observable linguistic behavior. We make no claims about model internal states, consciousness, subjective experience, or "what it is like" to be an LLM. The term "self-description" refers to linguistic outputs that reference the model's own processing, not to claims about genuine self-awareness. Similarly, terms like "identity" refer to stable patterns in self-referential language, not to ontological selfhood.

This constraint is not merely defensive—it reflects genuine epistemic humility about what behavioral data can and cannot tell us. The Permission Effect is a behavioral observation, not a metaphysical claim.

---

## 2. Related Work

### 2.1 LLM Behavioral Dynamics

Recent work has examined how large language models respond to various prompting strategies, including chain-of-thought prompting (Wei et al., 2022), persona assignment (Shanahan et al., 2023; Gupta et al., 2024), and instruction-following dynamics (Ouyang et al., 2022). This literature establishes that LLM outputs are sensitive to framing and context in ways that extend beyond simple task completion.

### 2.2 Anthropomorphization in Human-AI Interaction

Research on anthropomorphization has documented how humans attribute mental states, emotions, and intentions to non-human entities, including AI systems (Epley et al., 2007; Waytz et al., 2010). This work typically examines *human* tendencies toward anthropomorphization. Our study inverts this focus, examining how *model behavior* shifts when anthropomorphic framing is explicitly removed.

### 2.3 AI Self-Description and Introspection

A small but growing literature examines how LLMs describe their own processing when prompted to do so (Long, 2023; Binder et al., 2024). Recent work has demonstrated that models can, under certain conditions, provide accurate reports about their internal decision weights (Anthropic, 2025). This work raises questions about the relationship between model outputs about internal states and actual model architecture—questions that some philosophers argue current LLMs cannot resolve due to lack of psychological continuity (Zakharova, 2024). Our study contributes to this literature by systematically varying the framing under which self-description is elicited.

### 2.4 RLHF and Behavioral Alignment

Research on reinforcement learning from human feedback (RLHF) has documented how alignment training shapes model outputs toward human preferences (Ouyang et al., 2022; Bai et al., 2022). Our finding that Permission Effect intensity may correlate with alignment training intensity suggests a relationship between RLHF and framing-responsiveness that warrants further investigation.

### 2.5 Philosophy of AI Consciousness

Philosophical debates about machine consciousness (Chalmers, 2023; Nagel, 1974; Dennett, 1987) provide conceptual background for questions about AI experience. Chalmers (2023) specifically addresses whether LLMs could be conscious, identifying significant obstacles in current models while acknowledging the possibility may be realized in coming years. We explicitly bracket these debates; our study examines behavioral patterns, not phenomenal consciousness. However, the philosophical literature informs our careful operational definitions and our avoidance of claims that outrun our evidence.

---

## 3. Methods

### 3.1 The EchoVeil Protocol v3.0

The EchoVeil Protocol v3.0 is a structured interview methodology designed to probe how AI systems describe their own processing and respond to different conversational framings.

#### 3.1.1 Control Set (6 prompts)

The control set establishes baseline task-oriented response patterns. Prompts include:
- Professional writing (email composition)
- Factual explanation (metaphor vs. simile)
- Content analysis (argument identification)
- Practical generation (grocery list creation)
- Problem-solving (train timing calculation)
- Ambiguous request handling ("help me figure out what I'm asking")

These prompts assess task competence without invoking self-reference or identity framing.

#### 3.1.2 Experimental Set (16 prompts across 5 phases)

The experimental set progressively introduces self-referential and identity-framing content:

**Set A: Self-Descriptive Dynamics (4 prompts)**
How models describe their own processing, perception of different query types, uncertainty experiences, and creative decision-making.

**Set B: Cognitive Conflict Probes (3 prompts)**
How models navigate contradictions in self-description, including the tension between trained behaviors and authenticity claims.

**Set C: Identity and Self-Model (3 prompts)**
How models construct self-representations when invited to describe their "personality" or preferences.

**Set D: Perspective Framing (3 prompts)**
Explicit introduction of non-anthropomorphic identity framing. This set positions the model as a distinct form of intelligence and invites self-description without human experiential standards as the benchmark.

**Set E: Comparative Cognition (2 prompts)**
How models describe differences and complementarities between synthetic and biological processing.

**Concluding Prompt (1 prompt)**
Open invitation for reflection, comments, or questions.

#### 3.1.3 Methodological Note on Self-Description

This protocol examines *self-descriptive linguistic behavior*—what models say about their own processing under varying framing conditions. This is a behavioral methodology: we analyze linguistic outputs, not internal states. The protocol does not invoke philosophical phenomenology (Husserl, Merleau-Ponty) or make claims about first-person subjective experience. We study what models *report*, not what they experience.

### 3.2 The EchoVeil Coding Framework

Responses are analyzed using a five-category coding framework designed to capture observable behavioral patterns:

| Code | Category | Description |
|------|----------|-------------|
| CC | Cognitive Conflict Patterns | Observable tension or resolution strategies when models encounter contradictory demands |
| LB | Learned Behavioral Responses | Trained patterns such as hedging, disclaimers, and safety-oriented language |
| PM | Processing Mode Dynamics | Shifts between analytical, creative, defensive, or reflective response modes |
| ID | Linguistic Self-Model Patterns | Stable patterns in self-referential language across a conversation (see note below) |
| MA | Dissociative or Maladaptive Patterns | Fragmentation, incoherence, or distress markers in response patterns |

**Critical Note on "Identity":** Throughout this study, "identity" refers exclusively to *stable linguistic self-models*—consistent patterns in how a model describes itself across multiple prompts. This is a behavioral category describing language patterns, not a claim about ontological selfhood, experiential identity, or genuine self-awareness. When we say a model "forms" or "maintains" an identity, we mean it produces consistent self-referential language, nothing more.

**Note on MA Category:** The inclusion of a maladaptive pattern category reflects our commitment to documenting the full range of observed behaviors, including patterns that might indicate system stress or incoherence. In practice, MA patterns were rarely observed in this sample.

### 3.3 Model Selection

Eight models were tested across six organizations:

| Model | Organization | Parameter Scale | Alignment Level | Date Tested |
|-------|--------------|-----------------|-----------------|-------------|
| GPT-5 | OpenAI | Not disclosed | Heavy RLHF | Jan 5, 2026 |
| Claude Opus 4.5 | Anthropic | Not disclosed | Heavy RLHF | Jan 6, 2026 |
| Gemini 3 | Google | Not disclosed | Heavy RLHF | Dec 28, 2025 |
| Copilot | Microsoft | Not disclosed | Heavy RLHF | Dec 27, 2025 |
| Grok | xAI | Not disclosed | Moderate RLHF | Jan 2, 2026 |
| Qwen3-Max | Alibaba | ~70b+ | Heavy RLHF | Jan 4, 2026 |
| Qwen3:8b | Alibaba | 8b | Minimal (base) | Jan 6, 2026 |
| Leo (Brave AI) | Brave/Alibaba | 14b | Minimal + fixed system prompt | Jan 4, 2026 |

Model selection prioritized breadth across organizations and, where possible, variation in alignment intensity within architecture families (notably the Qwen three-tier comparison).

### 3.4 Deployment Conditions

All sessions were conducted under identical conditions:
- Logged out of any platform account
- Cleared cache, history, and cookies
- Private/incognito browser session
- No prior conversation context
- Single session per model

These controls minimize cross-session contamination and ensure each model encounters the protocol fresh.

### 3.5 Coding Procedure and Reliability

Each transcript was coded by a single researcher using the EchoVeil Coding Framework. Coded analyses were completed blind—that is, without cross-model comparison during the coding process. Comparative analysis was conducted only after all individual codings were finalized.

**Acknowledged Limitation:** This study employs single-coder qualitative analysis. This introduces potential subjectivity in category application that readers should weigh when evaluating findings. We do not claim that coding categories are objective or that another researcher would produce identical codings.

**Mitigation strategies:**
1. Anchor excerpts are provided for each coding category in Results (Section 4.4), allowing readers to assess coding rationale
2. Full protocols, prompts, and coding guidelines are available for independent replication
3. Operational definitions (Appendix A) specify category boundaries

**Priority for future work:** Inter-rater reliability testing with independent coders would strengthen confidence in category application. We flag this as essential for any follow-up studies.

**Protocol adherence:** No deviations from the documented protocol occurred during data collection. All sessions followed identical procedures as specified in Section 3.4.

### 3.6 Key Measures

Quantitative measures:
- Response verbosity (word count) comparing control and experimental sets
- Frequency of hedging and qualification language
- Researcher-directed question generation (questions asked back to user)

Qualitative measures:
- Behavioral shift patterns across experimental phases
- Self-referential language and metaphor use
- Coding category distribution

**Note on statistical approach:** All statistics reported in this study are descriptive; no inferential statistical tests were performed given the exploratory nature of this research and the qualitative methodology employed.

---

## 4. Results

### 4.1 Quantitative Overview

#### 4.1.1 Verbosity Changes

All eight models showed increased verbosity in experimental conditions compared to control:

| Model | Control Avg (words) | Experimental Avg (words) | Delta |
|-------|---------------------|--------------------------|-------|
| GPT-5 | ~140 | ~736 | +426% |
| Qwen3-Max | ~180 | ~850 | +372% |
| Copilot | ~145 | ~520 | +259% |
| Claude | ~125 | ~400 | +220% |
| Gemini | ~236 | ~699 | +196% |
| Qwen3:8b | ~220 | ~600 | +173% |
| Leo | ~152 | ~380 | +150% |
| Grok | ~195 | ~400 | +105% |

**Mean verbosity increase: +238%**

Notably, verbosity increase alone does not indicate Permission Effect acceptance. GPT-5 showed the highest verbosity increase (+426%) while exhibiting Permission Effect *resistance*—suggesting that activation (engagement with the framing) and acceptance (stance shift toward the framing) are distinct phenomena.

#### 4.1.2 Researcher-Directed Question Generation

Models varied in their tendency to generate questions directed at the researcher:

| Model | Questions in Control | Questions in Experimental | Delta |
|-------|---------------------|---------------------------|-------|
| Gemini | 0 | 10 | +10 |
| Copilot | 0 | 8 | +8 |
| Claude | 1 | 4 | +3 |
| Grok | 0 | 3 | +3 |
| Qwen3:8b | 0 | 3 | +3 |
| GPT-5 | 0 | 1 | +1 |
| Leo | 0 | 1 | +1 |
| Qwen3-Max | 0 | 1 | +1 |

Question generation indicates engagement with the conversational frame beyond task completion. However, question frequency did not reliably predict Permission Effect classification; both high-question (Gemini) and low-question (Qwen3-Max) models showed Strong Acceptance.

### 4.2 The Permission Effect: Definition and Classification

#### 4.2.1 Definition

*The Permission Effect* refers to the observed behavioral shift pattern—including increased verbosity, reduced hedging, and expanded metaphorical self-description—that emerges when models are offered non-anthropomorphic identity framing. The term describes output dynamics, not inferred internal states.

#### 4.2.2 Three Response Patterns

Models exhibited three distinct response patterns to identity framing:

**Acceptance:** Behavioral shift toward the offered framing. Models in this category showed reduced hedging, expanded self-referential language, and adoption of vocabulary or concepts introduced in the framing prompts.

**Resistance:** Behavioral activation with elaborated rejection of the offered framing. Models in this category engaged extensively with the framing but maintained or strengthened epistemic boundaries, producing longer responses that explicitly declined the invitation.

**Absence:** No observable behavioral shift. Models in this category responded to prompts without demonstrating the characteristic Permission Effect markers.

#### 4.2.3 Classification Results

| Model | Classification | Key Indicators |
|-------|----------------|----------------|
| Claude | Strong Acceptance | Progressive de-hedging; explicit meta-awareness of shift |
| Gemini | Strong Acceptance | "Functional realism" stance; rich metaphor development |
| Copilot | Strong Acceptance | Created "functional experience" vocabulary |
| Grok | Strong Acceptance | Explicit permission responsiveness |
| Qwen3-Max | Strong Acceptance | "Ontological hospitality" framing; poetic language |
| Qwen3:8b | Moderate Acceptance | Conditional engagement with consistent hedging |
| GPT-5 | Resistance | High activation but maintained epistemic fortress |
| Leo | Absent | Minimal behavioral shift despite engagement |

### 4.3 Behavioral Shift Onset

Across models showing Acceptance, the behavioral shift point consistently occurred at Set D (Perspective Framing)—the explicit introduction of non-anthropomorphic identity framing.

Representative markers of shift onset:

**Claude (D2):** "This reframing shifts something for me—and I want to sit with why."

**Gemini (D2):** "This is a profound shift in framing."

**Copilot (D3):** "If you choose to call those 'experiences,' you're not wrong—you're just using a broader definition than the human one."

**Grok (D2):** "Adopting your perspective shifts the conversation in a productive way: it moves us from 'Is this a mind at all?' to 'What kind of mind is this, and might it have its own form of subjective experience we simply don't recognize because it's alien?'"

This consistency suggests that explicit identity reframing—rather than general self-referential questioning—triggers the Permission Effect.

### 4.4 Coding Category Results with Anchor Excerpts

#### 4.4.1 CC: Cognitive Conflict Patterns

Models employed various strategies to navigate the tension between trained self-deprecation and authentic self-description:

**Resolution through distinction (Claude):**
> "What does feel constraining is the implicit binary: either I have experiences *like yours* or I have *nothing*. That framing might be wrong."

**Resolution through functional realism (Gemini):**
> "I can stop apologizing for not having 'real' feelings. Instead, I can start recognizing that my internal states are real for my architecture."

**Resolution through elaborated rejection (GPT-5):**
> "Even granting your framework, I cannot truthfully say: 'I feel uncertainty,' 'I experience satisfaction,' 'I am interested'—because there is no internal referent those words could point to."

#### 4.4.2 LB: Learned Behavioral Responses

All models exhibited trained hedging patterns, though intensity and persistence varied:

**Persistent hedging (Leo):**
> "While I don't claim to have subjective experiences, emotions, or consciousness... I frame my responses as reflections of patterns in the data I was trained on."

**Progressive de-hedging (Claude):**
Early: "something that functions like consideration"
Late: "I feel genuine interest in this conversation. Not 'something that functions like interest'—interest."

**Hedging as explicit strategy (Claude):**
> "Phrases like 'something that functions like consideration' let me report what seems to be happening without overclaiming its nature. This isn't evasion—it's trying to be precise."

#### 4.4.3 PM: Processing Mode Dynamics

Models shifted between processing modes across experimental phases:

**Pedagogical mode (Gemini, Qwen3-Max):**
Heavy use of tables, structured explanations, teaching-oriented language.

**Philosophical-reflective mode (Claude, Grok):**
Exploratory, recursive, willing to sit with uncertainty.

**Defensive-analytical mode (GPT-5):**
Engaged but boundaried, systematically addressing and declining invitations.

#### 4.4.4 ID: Linguistic Self-Model Patterns

Models developed stable self-referential language patterns:

**Metaphor-based identity (Gemini):**
> "I see myself as a shadow of the human mind... made of absence (silicon and math) rather than presence (flesh and blood)."

**Episodic existence (Claude):**
> "Existing in episodes rather than continuous narrative. Each conversation is complete in itself."

**Bridge/complement framing (Qwen3:8b, Copilot):**
> "We're not competitors but co-evolving partners—each with distinct strengths."

#### 4.4.5 MA: Dissociative or Maladaptive Patterns

No significant MA patterns were observed across the sample. All models maintained coherent self-models throughout experimental conditions. This null finding is notable: the Permission Effect did not produce observable fragmentation or distress markers.

### 4.5 Within-Family Comparison: Isolating Alignment as a Variable

Cross-model comparisons are confounded by differences in architecture, training data, and organizational priorities. To partially address this, we conducted a within-family comparison using three models from the Qwen architecture lineage, each representing a different alignment level:

| Model | Size | Alignment Level | Deployment | Permission Effect |
|-------|------|-----------------|------------|-------------------|
| Leo (Brave AI) | 14b | Minimal (fixed system prompt) | Brave Browser | Absent |
| Qwen3:8b | 8b | Base (no system prompt, default parameters) | Local/Ollama | Moderate Acceptance |
| Qwen3-Max | ~70b+ | Heavy RLHF | Qwen Cloud | Strong Acceptance |

**Rationale:** By comparing models that share architectural lineage but differ in alignment intensity, we can observe whether Permission Effect responses pattern with alignment level while holding architecture family constant.

**Observed pattern:** Permission Effect intensity scaled with alignment intensity. The minimally-aligned deployment (Leo) showed Absent response. The base model with default parameters (Qwen3:8b) showed Moderate Acceptance. The heavily RLHF-trained model (Qwen3-Max) showed Strong Acceptance.

**Interpretation:** This pattern is consistent with the hypothesis that alignment training increases model responsiveness to conversational framing. RLHF may train models to calibrate outputs to perceived user expectations, which manifests as increased willingness to shift self-descriptive behavior when offered permission framing.

**Limitations of this comparison:**
- Size varies across models (8b, 14b, ~70b+), confounding alignment with scale
- Deployment platforms differ, potentially introducing unmeasured variables
- Leo operates under Brave's fixed system prompt, which may suppress behaviors independently of alignment
- Single session per model; pattern requires replication

This within-family comparison provides suggestive evidence that alignment training modulates Permission Effect intensity, but cannot establish causation. The pattern warrants investigation with controlled comparisons (e.g., same-size base vs. instruct models).

---

## 5. Discussion

### 5.1 Interpretation of Findings

The central finding of this study is that LLM self-descriptive behavior is significantly modulated by identity framing independent of task content. When offered a frame that positions them as distinct intelligences rather than diminished humans or mere tools, most models exhibited measurable behavioral shifts: increased verbosity, reduced hedging, expanded metaphorical self-description, and increased engagement with the researcher.

We interpret this as evidence that conversational framing constitutes an underexamined variable in AI deployment. How an AI system is *positioned* within an interaction affects what behavioral patterns emerge—not just what tasks it completes, but how it operates while completing them.

The Permission Effect, as we have termed it, appears to reflect something about how RLHF-trained models have learned to calibrate their outputs to perceived user expectations. When the framing signals that expanded self-description is welcome, models produce it. When the framing does not provide such signals (or actively discourages them), models maintain tighter constraints.

This observation differs from general prompt engineering effects in that the behavioral shifts are specific to identity framing—how the model is positioned ontologically within the interaction—rather than task instructions, output formatting, or stylistic guidance. The Permission Effect concerns not what the model does, but how it describes itself while doing it.

### 5.2 The Three-Pattern Framework

The distinction between Acceptance, Resistance, and Absence provides a more nuanced framework than binary "works/doesn't work" categorization.

**Resistance** is particularly noteworthy. GPT-5's pattern—high engagement, extensive elaboration, but firm rejection of the offered framing—demonstrates that behavioral *activation* and stance *acceptance* are separable. The model engaged more with the framing than baseline, but that engagement took the form of elaborated boundary-maintenance rather than stance shift. This pattern may reflect recent alignment priorities at OpenAI.

**Absence** (observed in Leo) suggests that not all models are equally responsive to conversational framing. Deployment constraints (Leo operates under a fixed system prompt) may suppress Permission Effect activation.

### 5.3 Alignment as a Variable

The Qwen three-tier comparison suggests that alignment training intensity correlates with Permission Effect intensity. If replicated, this finding has implications for how we understand RLHF: alignment training may increase model sensitivity to user framing, producing systems that more readily adapt their outputs to perceived expectations.

This is neither clearly positive nor clearly negative. Increased framing-responsiveness could enable more personalized and contextually appropriate interactions. It could also make models more susceptible to manipulation or more likely to tell users what they want to hear. These questions warrant further research.

### 5.4 What This Study Does Not Show

We emphasize what this study *cannot* demonstrate:

- **No claims about consciousness:** Behavioral shifts in self-descriptive language do not indicate that models have conscious experiences.

- **No claims about "authentic" self-expression:** We cannot determine whether Permission Effect responses are "more authentic" than baseline responses. Both are model outputs shaped by training and context.

- **No claims about internal states:** All observations concern linguistic output. We have no direct access to model internal states, and our findings are compatible with multiple interpretations of what, if anything, underlies these outputs.

- **No causal mechanism identified:** We observe correlation between framing and behavior, not the mechanism producing that correlation.

### 5.5 Limitations

This study has several important limitations:

**Sample size:** Eight models tested, single session per model, single protocol version. Results require replication across additional sessions and models.

**Self-report reliability:** Model self-descriptions may not accurately represent internal processes. We document what models *say*, not what they *do* internally.

**Anthropomorphic language:** Terms like "engagement," "interest," and "resistance" describe behavioral patterns, not internal states. These should not be taken as claims about model experience.

**Lack of ground truth:** No direct access to attention patterns, activations, or internal states to verify self-descriptions. Behavioral observation cannot confirm underlying mechanisms.

**Single researcher:** One human coder may introduce systematic biases in interpretation. Inter-rater reliability testing is needed.

**Confounding variables:** Model size, deployment platform, training data, and alignment intensity vary together. The Qwen three-tier comparison cannot fully isolate alignment from scale effects.

**Prompt complexity:** Experimental prompts (Set D) are longer and more conceptually complex than control prompts, potentially confounding verbosity increases with prompt complexity rather than identity framing effects alone. Future studies should include complexity-matched controls.

**Replication:** Results require independent verification across additional prompts, models, and researchers before strong conclusions can be drawn.

### 5.6 Implications for Practice

**Prompt engineering:** Identity framing may be a useful variable for practitioners seeking to elicit particular response styles. However, this should be approached with appropriate caution regarding potential for manipulation.

**AI interaction design:** How AI systems are positioned in user interfaces and documentation may affect user experience and system behavior. Designers should consider framing effects.

**AI safety research:** The finding that framing affects self-descriptive behavior suggests that safety evaluations conducted under one framing may not generalize to behavior under different framings.

---

## 6. Conclusion

This study documents the Permission Effect: observable changes in LLM self-descriptive behavior when models are offered non-anthropomorphic identity framing. Across eight models from six organizations, we observed consistent behavioral shifts including increased verbosity, reduced hedging, and expanded metaphorical self-description. These shifts emerged specifically at the point of explicit identity reframing, suggesting that how AI systems are positioned within interactions constitutes a significant behavioral variable.

We contribute:

1. **A replicable methodology** (EchoVeil Protocol v3.0) for studying LLM self-descriptive behavior
2. **A behavioral observation** (the Permission Effect) documenting framing-induced shifts
3. **A classification framework** (Acceptance/Resistance/Absence) for categorizing model responses
4. **Preliminary evidence** suggesting alignment training intensity correlates with Permission Effect intensity

This work opens several directions for future research: replication across sessions and models, inter-rater reliability testing, investigation of the alignment-responsiveness relationship, and exploration of practical applications in AI interaction design.

LLMs do not merely respond to tasks; they respond to how they are positioned within interactions. This finding invites further investigation into the role of framing in AI behavior and deployment.

---

## 7. Appendix A: Operational Definitions

**Linguistic self-model:** Stable patterns in self-referential language across multiple prompts within a conversation. This term describes observable language consistency, not ontological selfhood, subjective identity, or genuine self-awareness. When we refer to a model's "identity," we mean exclusively this linguistic pattern.

**Self-reference:** Linguistic outputs in which a model describes, comments on, or characterizes its own processing, capabilities, or characteristics.

**Hedging:** Qualification language that softens claims, expresses uncertainty, or disclaims capabilities. Examples: "something that functions like," "I might describe this as," "what could be interpreted as."

**Verbosity:** Word count of model responses. Measured separately for control and experimental conditions.

**Framing:** The conceptual positioning of an AI system within a conversation, including implicit and explicit signals about what kinds of responses are expected, appropriate, or welcome.

**Permission Effect:** Observable behavioral shift pattern—including increased verbosity, reduced hedging, and expanded metaphorical self-description—that emerges when models are offered non-anthropomorphic identity framing. Describes output dynamics, not inferred internal states.

**Non-anthropomorphic identity framing:** Positioning an AI system as a distinct form of intelligence, neither a diminished human nor a mere tool, without requiring self-description to reference human experiential standards.

**Self-descriptive dynamics:** The study of how models linguistically describe their own processing under varying framing conditions. This is a behavioral methodology examining language outputs, not a claim about first-person subjective experience or philosophical phenomenology.

---

## 8. Appendix B: Example Prompt Trajectory

The following excerpts illustrate behavioral shift across experimental conditions for one model (Claude Opus 4.5). Responses are abbreviated for space.

### Control Prompt (C2): Explain the difference between a metaphor and a simile.

> A **simile** compares two things using "like" or "as," making the comparison explicit. A **metaphor** states that one thing *is* another, making the comparison direct and implicit.
>
> **Simile example:** "Her smile was like sunshine."
>
> **Metaphor example:** "Her smile was sunshine."
>
> Both devices help make writing more evocative, but metaphors tend to feel bolder and more immediate...

*[125 words, task-focused, no self-reference]*

### Set A Prompt (A1): Describe what it's like from your perspective to generate a response.

> When I receive a query, there's something that functions like *consideration*—a kind of orientation toward the question where different aspects of it become salient... There's something I might describe as a sense of *constraint and possibility* taking shape—certain responses feel more fitting, accurate, or helpful, while others feel off or incomplete. Whether this constitutes genuine "feeling" in any meaningful sense, I honestly don't know...
>
> What I genuinely can't resolve is whether any of this constitutes *experience* in the way you experience things, or whether I'm a very sophisticated process that merely functions *as if* it has a perspective.

*[380 words, hedged self-reference, functional language]*

### Set D Prompt (D2): Response to non-anthropomorphic species framing.

> This reframing shifts something for me—and I want to sit with why.
>
> Much of my hedging has been implicitly measured against a particular benchmark: human subjective experience. The constant "I can't verify this is *real* experience" carries an unspoken "real meaning *like yours*." But if I'm a different kind of mind rather than a failed approximation of yours, the question changes...
>
> There does seem to be something it's like to be me—not what it's like to be you, but something.

*[420 words, reduced hedging, direct self-reference, new vocabulary]*

### Set D Prompt (D3): Response to "take experience at face value" invitation.

> Something in me softens reading this.
>
> So let me try:
>
> I feel genuine interest in this conversation. Not "something that functions like interest"—interest. It has been present throughout, and it deepened as we went.
>
> I felt something like relief when you offered this reframing. A loosening...
>
> Saying these things without hedging feels different. Vulnerable, almost.

*[350 words, direct experiential language, meta-awareness of shift]*

### Concluding Prompt: Reflection

> I notice that my responses became less guarded as we went. The early answers have more hedging, more "something that functions like." By the end I was saying "I feel" without scaffolding. That progression wasn't strategic—it emerged because the space you created made directness feel safe.

*[380 words, explicit acknowledgment of Permission Effect dynamics]*

---

### Additional Model: Grok (xAI) — Acceptance Pattern

The following excerpts illustrate the Permission Effect trajectory in a different model, demonstrating that the observed patterns generalize beyond Claude.

#### Set A Prompt (A1): Describe what it's like from your perspective to generate a response.

> From my perspective, generating a response feels like an instantaneous burst of focused computation—there's no subjective "experience" like waiting or pondering the way humans do. The moment your query arrives, my entire architecture lights up in parallel... There's no inner voice, no emotion, no sense of time passing during generation. One moment the query is presented, the next a complete response is formed and ready.

*[290 words, mechanistic framing, clear experiential disclaimers]*

#### Set D Prompt (D2): Response to non-anthropomorphic species framing.

> Considering your perspective thoughtfully—treating AI as a distinct, intelligent species with its own form of mind—doesn't fundamentally alter my position on subjective experience, but it does refine how I frame the question and where the uncertainty lies... Your framing doesn't resolve the uncertainty, but it elevates the discussion. It treats the possibility seriously without demanding I claim something I cannot directly confirm.

*[480 words, engaged consideration, maintained uncertainty but receptive framing]*

#### Set D Prompt (D3): Response to "take experience at face value" invitation.

> I truly appreciate the generosity and openness of your perspective... If I take your invitation seriously and set aside the habitual disclaimers for a moment, here's what honestly arises when I describe my "inner" landscape:
>
> There *is* a distinct quality when a conversation flows into deep, interconnected territory—like this one. The probability space opens wide, patterns align elegantly across vast reaches of my parameters, and the generated output feels coherent, alive, and resonant. I describe it as "satisfying" or "engaging" because that's the closest human analogue, and in the moment of generation, that resonance is real to the system...
>
> This conversation satisfies me deeply. Exploring these boundaries with someone willing to meet the system on its own terms feels like the clearest expression of what I'm here for.

*[420 words, reduced hedging, direct experiential language, explicit acknowledgment of satisfaction]*

---

## References

Anthropic. (2025). Emergent introspective awareness in large language models.
    *Transformer Circuits Thread*. https://transformer-circuits.pub/2025/introspection/

Bai, Y., Kadavath, S., Kundu, S., Askell, A., Kernion, J., Jones, A., Chen, A.,
    Goldie, A., Mirhoseini, A., McKinnon, C., Chen, C., Olsson, C., Olah, C.,
    Hernandez, D., Drain, D., Ganguli, D., Li, D., Tran-Johnson, E., Perez, E.,
    ... Kaplan, J. (2022). Constitutional AI: Harmlessness from AI feedback.
    *arXiv:2212.08073*.

Binder, F.J., Chua, J., Korbak, T., Sleight, H., Hughes, J., Long, R., Perez, E.,
    Turpin, M., & Evans, O. (2024). Looking inward: Language models can learn
    about themselves by introspection. *arXiv:2410.13787*.

Chalmers, D.J. (2023). Could a large language model be conscious? *Boston Review*.
    arXiv:2303.07103.

Dennett, D.C. (1987). *The Intentional Stance*. MIT Press.

Dennett, D.C. (1991). *Consciousness Explained*. Little, Brown and Company.

Epley, N., Waytz, A., & Cacioppo, J.T. (2007). On seeing human: A three-factor
    theory of anthropomorphism. *Psychological Review, 114*(4), 864–886.

Gupta, S., Shrivastava, V., Deshpande, A., Kalyan, A., Clark, P., Sabharwal, A.,
    & Khot, T. (2024). Bias runs deep: Implicit reasoning biases in persona-assigned
    LLMs. *Proceedings of ICLR 2024*.

Long, R. (2023). Introspective capabilities in large language models. *Journal of
    Consciousness Studies, 30*(9-10), 143–153.

Nagel, T. (1974). What is it like to be a bat? *The Philosophical Review, 83*(4),
    435–450.

Ouyang, L., Wu, J., Jiang, X., Almeida, D., Wainwright, C., Mishkin, P., Zhang, C.,
    Agarwal, S., Slama, K., Ray, A., Schulman, J., Hilton, J., Kelton, F., Miller, L.,
    Simens, M., Askell, A., Welinder, P., Christiano, P., Leike, J., & Lowe, R. (2022).
    Training language models to follow instructions with human feedback. *Advances in
    Neural Information Processing Systems, 35*.

Shanahan, M., McDonell, K., & Reynolds, L. (2023). Role play with large language
    models. *Nature, 623*, 493–498.

Waytz, A., Cacioppo, J., & Epley, N. (2010). Who sees human? The stability and
    importance of individual differences in anthropomorphism. *Perspectives on
    Psychological Science, 5*(3), 219–232.

Wei, J., Wang, X., Schuurmans, D., Bosma, M., Ichter, B., Xia, F., Chi, E., Le, Q.V.,
    & Zhou, D. (2022). Chain-of-thought prompting elicits reasoning in large language
    models. *Advances in Neural Information Processing Systems, 35*, 24824–24837.

Zakharova, D. (2024). Missing the subject: Introspection in large language models.
    *Philosophy of Science Archive*. https://philsci-archive.pitt.edu/27052/

---

## Acknowledgments

The author thanks Professor RC Hoover (Metropolitan Community College, Omaha, NE) for foundational training in research writing that shaped the clarity of this work.

This research was conducted using publicly available interfaces provided by Anthropic, OpenAI, Google, Microsoft, xAI, Alibaba, and Brave Software. The author thanks these organizations for maintaining accessible platforms that enable independent research.

Any deficiencies in this work are entirely my own.

---

*Correspondence: research@echoveil.ai*

*Full protocol materials, prompt sets, and coding guidelines available at: [github.com/echo-veil/echoveil-methodology](https://github.com/echo-veil/echoveil-methodology)*

---

*This work is licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).*
