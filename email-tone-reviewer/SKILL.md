---
name: email-tone-reviewer
description: Reviews a draft business email for tone (too casual, too aggressive, unclear, etc.) and suggests a more professional rewrite. Use when the user asks to review, check, or improve the tone of an email, or wants help making an email sound more professional.
---

# Email Tone Reviewer

Review a draft email for professional business tone and suggest improvements.

## Steps

1. **Read the draft email** the user provides (or ask for it if not given).
2. **Identify the intended context**, if available: audience (boss, client, colleague, external partner), purpose (request, complaint, follow-up, announcement), and desired tone (formal, friendly-professional, firm). If unstated, infer a reasonable default (professional, neutral-friendly) and note the assumption.
3. **Evaluate tone issues**, checking for:
   - **Too casual**: slang, excessive exclamation points, emoji, overly informal greetings/sign-offs.
   - **Too aggressive/blunt**: accusatory phrasing, demands without softening language, all-caps emphasis.
   - **Too passive/unclear**: hedging that obscures the ask, no clear call to action, buried key point.
   - **Overly wordy or stiff**: unnecessarily long sentences, corporate jargon that reduces clarity.
   - **Missing structure**: no clear greeting, subject-appropriate opening, or sign-off.
4. **Give feedback in this format**:
   - A short summary (1-2 sentences) of the overall tone read.
   - A bullet list of specific issues found, each quoting the problematic phrase and explaining why it may land poorly.
   - A rewritten version of the full email that fixes the issues while preserving the original intent and key content.
5. **Keep the rewrite recognizable** — don't change facts, requests, or the core message, only tone and phrasing. Preserve the user's voice where it isn't the problem (don't over-formalize a message that's appropriately casual for its context, e.g. a note to a close teammate).
6. If the user provides context suggesting the recipient relationship is already informal (e.g., "this is for my work friend"), calibrate expectations accordingly rather than defaulting to maximum formality.

## Output format

```
**Tone summary:** <one-line read of current tone>

**Issues found:**
- "<quoted phrase>" — <why this could land poorly>
- ...

**Suggested rewrite:**
<full rewritten email>
```
