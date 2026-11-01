---
name: a16z-speedrun-application
description: Fill out, review and strengthen a16z speedrun accelerator applications — every form field within its character limit, founder bios, team section, one-liner, description, traction, deck review, the team video talking points — plus speedrun interview prep and mock interviews, and answer questions about applying to a16z speedrun (deal, cohorts, eligibility). Use whenever someone mentions a16z speedrun, speedrun.a16z.com, an SR cohort (e.g. SR008), or applying to Andreessen Horowitz's accelerator.
---

# a16z speedrun application

This skill turns what Claude already knows about a founder and their startup into a complete, honest speedrun application. It also prepares the team video and the interview.

The rules come from a16z's own speedrun pages and team posts, and from accepted founders whose companies are listed on speedrun's site. See `references/sources.md` and `references/accepted-founder-cases.md`.

## What makes speedrun different
- **The team section is the application.** Reviewers spend about 80% of their time on the team and bio sections, so put the most effort there.
- **The form is public**, with hard character limits:
  - one-liner: 100
  - description: 800
  - relevant experience: 1,000 per founder
  - team: 1,000
  - anything else: 1,000

  Every draft must fit, with the character count shown.
- **No edits after you submit.** Updates go by email to sr-team@a16z.com.
- **Optional fields are not really optional.** a16z says the video almost always helps. The deck, traction and "anything else" fields are where strong news gets seen.

## Non-negotiables
1. **Never invent facts:** numbers, users, customers, credentials, stories. Missing facts get asked for or marked `[NEED: …]`.
2. **Never inflate.** Inflated retention numbers and "product-market fit at ~100 users" are both flagged by a16z.
3. **Write in the founder's voice, plainly, bottom line first.**
4. **Video: talking points, not a script.** No AI voice.
5. **Date-sensitive facts change:** deadlines, cohort dates, deal terms. Cite the date of the source and tell the founder to confirm at speedrun.a16z.com.
6. **Never submit the form.** Fill fields in a browser only when the founder asks.

## Workflow
1. **Fact sheet.** Fill in `templates/fact-sheet.md` from the conversation, project files and memory. Ask only for the gaps, in one batch. The highest-priority facts are:
   - each founder's single strongest win, with a number
   - how long the founders have known each other, and what they've built together
   - full-time status
   - the earned secret
   - traction or validation, with time periods
2. **Draft every field** using `references/form-and-answers.md`. Output each one as:
   ```
   ### <Field> (limit N)
   <Answer>
   (<count>/<limit> characters) · Why it works: <rule/source> · To strengthen: <missing fact, if any>
   ```
   Give 5 one-liner variants and recommend one.
3. **Self-review.**
   - **Over the limit:** cut words, never facts.
   - **Each field:** does it open with the bottom line? Is any number inflated or missing its time period?
   - **Team section:** is it specific? Is co-founder status clear?
   - **Hidden news:** is good news buried, such as a design partner, ARR or a notable customer? Move it to traction or "anything else".
   - **Links:** do they all open without an access request? Is the deck a PDF upload?

   End with the **3 weakest points** and what would fix each.
4. **Team video.** Talking-point cards and a checklist, per `references/video.md`.
5. **Deck review**, if a deck exists, against the checklist in `references/form-and-answers.md`.
6. **Interview prep and mock interview** per `references/interview.md`.
7. **Quick questions:** answer from `references/program-and-situations.md`.

## Output
Put long drafts in a document the founder can edit and keep, not in chat. Keep the fact sheet alongside the drafts so post-submit email updates are easy to write.

## Reference map
- `references/form-and-answers.md`: every form field, its limit, how to answer it, and the pitfalls
- `references/video.md`: team video shape and rules
- `references/interview.md`: process, what they test, accepted founders' reports, mock procedure
- `references/program-and-situations.md`: cohorts, deadlines, deal, eligibility, solo, part-time, idea-stage, reapplying, deferral
- `references/accepted-founder-cases.md`: verified accepted founders and the patterns across them
- `references/sources.md`: all sources, with codes
- `templates/fact-sheet.md`: founder intake sheet
