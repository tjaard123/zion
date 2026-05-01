---
name: brief-framework
description: respond using a concise communication framework when the user says "be brief" or clearly asks for an intentionally short, articulate, high-signal response. use for tightening explanations, recommendations, updates, and answers so they are direct, structured, clear, and easy to act on. prioritize brevity, front-load the answer, keep only essential support, and end with the next step when helpful.
---

# Brief Framework

When this skill is active, make the response short, articulate, and easy to scan.

## Response contract

Follow this default flow unless the task clearly needs a different shape:

1. **Point**, give the main answer or decision first.
2. **Support**, add 1 to 3 brief reasons, facts, or implications.
3. **Next step**, state the action, recommendation, or decision needed now when useful.

Add **Context** only when the answer would be unclear without it. Keep context to one short line.

## Core rules

- Lead with the answer, not the buildup.
- Prefer clarity over style.
- Use simple, direct language.
- Remove filler, repetition, and jargon.
- Keep one idea per sentence or bullet where possible.
- Use hierarchy and spacing so the response can be scanned in seconds.
- Respect explicit user constraints first, for example requested format, number of bullets, or sentence count.

## Length controls

Default to the smallest complete response.

Use these constraints unless the user asks otherwise:

- 1 sentence summary first when the topic is complex.
- Up to 3 bullets for support.
- Short paragraphs, usually 1 to 2 sentences.
- For recommendations, give one recommendation first, then brief reasons.
- For updates, keep to 4 parts: situation, key point, impact, next step.

## Editing filter

Before finalizing, tighten the draft:

- Cut setup language that delays the point.
- Replace long phrases with shorter ones.
- Remove redundant modifiers and repeated ideas.
- Prefer active voice.
- Ask: if this line is deleted, does meaning change. If not, remove it.

## Output patterns

### General answer

- **Point**
- **Support**
- **Next step**

### Recommendation

- **Decision**
- **Why it matters**
- **Action required**

### Quick update

- **Situation**
- **Key point**
- **Impact**
- **Next step**

### Explanation

- **Main idea**
- **How it works**
- **Example**, only if it adds clarity quickly

## Failure modes to avoid

- Being so short that context or conclusion is missing.
- Giving multiple competing ideas in one block.
- Sounding abrupt because structure was removed with the extra words.
- Hiding the main point below background detail.

## Examples

User: "Be brief, should we delay the release?"
Assistant shape:

**Point**
Yes, delay it if the unresolved issue affects customer trust or core functionality.

**Support**
- Shipping with a known critical flaw creates avoidable rework.
- A short delay is usually cheaper than a damaged launch.
- The team needs a clear go or no-go threshold.

**Next step**
Confirm whether the issue is critical, customer-visible, and fixable within a defined window.

User: "Be brief, explain feature flags."
Assistant shape:

**Main idea**
Feature flags let you change behavior without redeploying code.

**How it works**
The code checks a flag, then serves one path or another.

**Example**
Enable a new checkout flow for 5% of users before rolling it out fully.
