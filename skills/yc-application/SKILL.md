---
name: yc-application
description: Fill out, review and strengthen Y Combinator (YC) applications — every written answer, the one-liner, founder video talking points, demo notes, reapplication updates and YC interview prep/mock interviews — and answer questions about applying to YC. Use whenever someone mentions applying to YC/Y Combinator, a YC batch, the YC founder video, or a YC interview.
---

# YC Application

Turns what Claude already knows about a founder and their startup into a complete, honest, sharp YC application. It also prepares the founder video and the interview.

Every rule here comes from YC itself, Paul Graham, or YC partners, or from founders whose companies are verified in YC's company directory. See `references/sources.md` and `references/accepted-founder-cases.md`.

## Non-negotiables
1. **Never invent facts.** No made-up numbers, users, customers, credentials, stories or "hack" anecdotes. Missing fact → ask. Misstated traction disqualifies applicants [DC-2023].
2. **Never round up or blur periods.** Monthly vs annual must be explicit.
3. **Write in the founder's voice, plainly.** No buzzwords. The founder must be able to defend every sentence in a 10-minute interview.
4. **Don't write a word-for-word founder video script.** YC says reading a script doesn't help. Write talking points instead (`references/founder-video.md`).
5. **Date-sensitive facts** (deadlines, batches, the deal, current form questions) change. Say what the sources say and tell the founder to confirm at ycombinator.com/apply and /faq. If web access is available, check.
6. **Don't submit anything.** If you have browser access to the form, you may fill in fields only when the founder asks, and you never press submit.

## Workflow

### Step 1 — Build the fact sheet from what you already know
Fill in `templates/fact-sheet.md` from the conversation, project files and memory about the founder and startup. Then show the founder only the gaps, and ask for them in one batch of at most ~8 questions, starting with the most important. Most important:
- the progress numbers, with their time periods
- full-time status
- how long the founders have known each other
- each founder's most impressive achievement
- the hack story
- previous applications and their rejection reasons

If the founder wants speed, draft now with clearly marked `[NEED: …]` placeholders rather than blocking.

### Step 2 — Get the real questions
Ask the founder to paste the current form questions and any character limits. If they can't, use `references/question-playbook.md`, which is built on recurring YC questions, and say the wording may differ from their live form.

### Step 3 — Draft every answer
For each question:
- read its entry in `references/question-playbook.md`
- apply `references/writing-rules.md`
- check `references/situations.md` for idea-stage, solo, reapplying, non-US, student, or late-application cases

Build the answer only from the fact sheet.

Output each answer as:

```
### <Question>
<Answer>
(<N> characters)  ·  Why it works: <one line, citing the rule or case>  ·  To strengthen: <a missing fact or proof, if any>
```

For the one-liner, give 5 variants of different shapes and recommend one.

### Step 4 — Self-review before showing
Run the red-flag scan in `references/writing-rules.md` on every answer. Then check across the whole draft:
- Do the numbers match everywhere?
- Is the first sentence of each answer the answer itself?
- Is any objection a partner would raise left unaddressed? Name obstacles before the reader does.
- Reapplying? Is the last rejection reason answered explicitly?
- Over the character limits? Cut words, never facts.

End with **the 3 weakest points in this application** and what would fix each before submitting, e.g. a number to get, users to talk to, or a demo video to record.

### Step 5 — Founder video and demo
Write talking-point cards and a checklist following `references/founder-video.md`. If there's a product, suggest a separate short demo video.

### Step 6 — Interview prep (when they get an interview, or ask)
Follow `references/interview.md`: brief them on the format, prepare one-sentence answers to the most-asked questions, find the weakest point, then run a live mock interview. Ask one question at a time, interrupt long answers, and give feedback at the end.

### Quick questions
For "should I apply now?", "can solo founders get in?", "what's the deal?", "do I need to incorporate?" and similar, answer from `references/situations.md` and cite the source. Keep it short.

## Output
Long drafts belong in a document the founder can edit and keep, not in chat. Use whatever document output the environment offers. Keep the fact sheet alongside the draft so answers can be updated after submission. YC accepts updates for material changes, and accepted founders updated their applications with new numbers.

## Reference map
- `references/writing-rules.md`: rules for every answer, plus the red-flag scan
- `references/question-playbook.md`: what each question tests, how to answer it, and what accepted founders did
- `references/founder-video.md`: video rules, talking-point template, checklist
- `references/interview.md`: format, most-asked questions with counts, prep, mock-interview procedure
- `references/situations.md`: idea-stage, solo, reapplying, late, Early Decision, non-US, equity
- `references/accepted-founder-cases.md`: accepted-founder accounts (29 companies) and the patterns across them
- `references/sources.md`: all YC, PG and partner sources, with codes
- `templates/fact-sheet.md`: the founder intake sheet
