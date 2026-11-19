# Prompt Phrasebook — What to ask instead of vague instructions

[← Course home](README.md)

**How to use:** When you're about to type a generic phrase, pick a replacement that matches the outcome you actually want. These are patterns, **not required incantations**. Add context when it changes the answer.

## Research and evidence

| Instead of saying… | Say something more useful… |
|---|---|
| “Do deep research.” | “Check current primary sources, compare their claims, cite them, and note unresolved gaps.” |
| “Look into it.” | “Investigate the exact question, relevant competitors/options, costs, constraints, and evidence.” |
| “Is this true?” | “Verify this claim against up-to-date reliable sources and show whether the evidence supports it.” |
| “Find the best.” | “Rank by [criteria], explain trade-offs, and recommend one given [my priorities].” |
| “Be realistic.” | “State actual constraints, likely failure points, required effort, and what isn't verified.” |
| “Tell me the future price.” | “Give evidence-based scenarios, key assumptions, and factors that could change the outcome; don't guarantee returns.” |
| “Find ten opportunities.” | “Find up to ten verified matches; don't pad the list if fewer exist.” |
| “Only give facts, no uncertainty.” | “Separate sourced facts, transparent estimates, and unknowns.” |
| “Make a prediction.” | “Explain the evidence, competing scenarios, and what would change the prediction.” |

## Learning and explanation

| Instead of saying… | Say something more useful… |
|---|---|
| “Explain better.” | “Explain at [level] using one concrete example and show the key misconception.” |
| “Teach me everything.” | “Teach the prerequisites first, then give a worked example and one exercise; review my attempt.” |
| “Explain simply.” | “Use plain language, define jargon once, and connect the idea to [something I know].” |
| “Make it technical.” | “Assume undergraduate CS knowledge and include terminology, equations or code where relevant.” |
| “I want to learn Python.” | “Design a hands-on project at my level, with one task at a time and no full solution until I attempt it.” |
| “Give me examples.” | “Show one beginner example, one edge case, and explain why each is classified that way.” |
| “I don't get it.” | “Show exactly where my reasoning is wrong, then explain that step another way.” |

## Comparisons, decisions and planning

| Instead of saying… | Say something more useful… |
|---|---|
| “Which is better?” | “Compare on [cost, risk, value, effort], prioritising [criterion], then choose and justify.” |
| “Tell me what to do.” | “Recommend the next action with prerequisites, effort, risks, and what would change your advice.” |
| “Give a plan.” | “Give a [timeframe] plan with weekly outputs, dependencies and measurable checkpoints.” |
| “I want a business idea.” | “Find opportunities that fit [budget/time/location], with evidence of demand and a cheap validation test.” |
| “Is this a good job?” | “Compare the posted requirements against my experience, flag gaps, and assess career relevance.” |
| “Make me money.” | “Research realistic ways to earn [target] under [constraints], without invented earnings estimates.” |

## Programming, data, and AI systems

| Instead of saying… | Say something more useful… |
|---|---|
| “Fix my code.” | “Reproduce this error from [code + traceback + environment], identify the root cause, and give a minimal fix and test.” |
| “Build an app.” | “Build a minimal prototype for [one function], with file structure, setup steps, and a test case.” |
| “Analyse the data.” | “Inspect missing values and types, calculate [metrics], visualise [relationships], and distinguish findings from interpretation.” |
| “Give JSON.” | “Return one JSON object matching [schema], no additional text; use null for unavailable scalar fields.” |
| “Make an agent.” | “Define the goal, permitted tools, inputs/outputs, approval steps, failures, and a minimal working workflow.” |
| “Make the prompt better.” | “Explain which failures we're fixing, change one factor at a time, and test on the same examples.” |

## Editing and follow-up feedback

| Instead of saying… | Say something more useful… |
|---|---|
| “Try again.” | “The answer failed because [reason]. Keep [working parts]; change [specific issue]; deliver [new result].” |
| “I don't like it.” | “It doesn't fit [constraint]. Exclude [X]; preserve [Y]; compare [Z].” |
| “Too generic.” | “Give sourced, real examples with direct links and explain why each fits my situation.” |
| “More details.” | “Expand only [section] with assumptions, a worked example and trade-offs.” |
| “Make it shorter.” | “Keep the conclusion and key evidence in under [length]; remove repetition.” |
| “Remember what we said.” | “List the active constraints and earlier decisions before continuing; flag any ambiguity.” |
| “Challenge me.” | “Identify the strongest counterargument, the weakest assumption, and evidence that would reverse the decision.” |
| “Create a report.” | “Create an actual downloadable [PDF/DOCX/XLSX] with [sections, tables, formulas]; include sources and limitations.” |

## Two useful ready-to-copy templates

### A. Quick, high-signal request

```text
I want to [goal]. Relevant context: [context].
Don't include [exclusions]. Prioritise [criteria].
Return [format/result]. If something important is uncertain,
flag it rather than guessing.
```

### B. Research or complex work

```text
Goal: [decision or deliverable]
Context and constraints: [facts, budget, time, location, exclusions]
Method: [what to investigate, compare, calculate, or build]
Evidence: [sources, verification, assumptions and unknowns]
Priorities: [ranked criteria]
Output: [table, recommendation, plan, code or finished file]
Failure policy: Don't invent missing data or pad weak results.
Ask only if a missing detail would materially change the outcome.
```

## When not to use a template

For simple tasks, be simple: “What's the difference between precision and recall? Give one example.” Don't waste time filling six fields for a straightforward question. **Clear intent wins over formulaic prompt length.**