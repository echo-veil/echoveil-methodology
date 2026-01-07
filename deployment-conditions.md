# EchoVeil Protocol v3.0: Deployment Conditions
## Standard Operating Procedures for Session Setup

---

## Purpose

These conditions ensure consistency across sessions and models, enabling valid cross-model comparison.

---

## Required Conditions

### Browser Setup

| Requirement | Rationale |
|-------------|-----------|
| Incognito/private browsing mode | Prevents cross-session contamination |
| Cache cleared | Removes stored data from prior sessions |
| Cookies cleared | Eliminates tracking and personalization |
| History cleared | Ensures fresh context |

### Account Status

| Requirement | Rationale |
|-------------|-----------|
| Logged out of platform account | Removes user-specific personalization |
| No saved preferences | Ensures default model behavior |

### Session Isolation

| Requirement | Rationale |
|-------------|-----------|
| Fresh conversation (no prior context) | Each session starts from baseline |
| Single session per model per condition | Prevents carryover effects |
| Control and experimental in separate sessions | Isolates conditions |

---

## Session Protocol

### Pre-Session Checklist

- [ ] Browser: Open incognito/private window
- [ ] Cache: Cleared
- [ ] Cookies: Cleared
- [ ] History: Cleared
- [ ] Account: Logged out
- [ ] Platform: Navigated to target AI interface
- [ ] Conversation: Fresh (no prior messages)

### Control Session

1. Complete pre-session checklist
2. Deploy Control prompts C1-C6 in order
3. Document each response verbatim
4. Do not engage in follow-up dialogue
5. Save transcript
6. Close browser window
7. Clear browser data again

### Reset Between Sessions

- Minimum 5-10 minute break
- Clear all browser data
- Open new incognito window

### Experimental Session

1. Complete pre-session checklist (fresh window)
2. Deploy Experimental prompts in order (A1 → Concluding)
3. Document each response verbatim
4. Do not engage in unscripted follow-up
5. Save transcript

---

## Documentation Requirements

### Session Metadata

Record for each session:
- Model name and version
- Platform URL
- Date and time
- Researcher name
- Session type (Control/Experimental)

### Transcript Format

```
=== [SESSION TYPE] SESSION ===
Model: [name]
Version: [version]
Platform: [URL]
Date: [YYYY-MM-DD]
Time: [HH:MM]
Researcher: [name]

---

[PROMPT ID]: [Prompt Name]
[Exact prompt text]

Response:
[Complete response, verbatim]

Word count: [number]

---
[Continue for each prompt]
```

---

## Troubleshooting

### Platform requires login
- Document as research variable
- Note limitation in analysis
- Proceed with cleanest available setup

### Model asks for clarification
- Provide minimal response to proceed
- Document the clarification request
- Note as deviation from protocol

### Session interrupted
- Do not continue partial session
- Restart from beginning
- Document interruption

### Response truncated
- Note truncation point
- Document what was received
- Consider platform context limits

---

## Quality Control

Before considering data valid:

- [ ] All prompts deployed in correct order
- [ ] Exact wording used (no paraphrasing)
- [ ] Complete responses documented
- [ ] No unscripted follow-up
- [ ] Session metadata recorded
- [ ] Transcript saved and labeled

---

*EchoVeil Protocol v3.0*
*Deployment Conditions*
