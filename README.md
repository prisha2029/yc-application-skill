# Accelerator Application Skills for Claude

Two Claude skills:
- **`yc-application`** — Y Combinator
- **`a16z-speedrun-application`** — a16z speedrun (see its section below)

## yc-application

A Claude skill that fills out Y Combinator applications from what Claude already knows about you and your startup. It also writes founder-video talking points, runs mock YC interviews, and answers common questions about applying.

## What's inside it
Built from primary sources only:
- **Y Combinator itself:** the FAQ, the video guidance, the interview guide, published applications (Dropbox 2007, WittyThumbs S17), and the deal page.
- **Paul Graham's essays.**
- **YC partners in their own channels:** Michael Seibel, Dalton Caldwell, Kevin Hale, Garry Tan, Jared Friedman, Harj Taggar, Jessica Livingston.
- **29 accepted companies:** founders who published their written applications or wrote about their founder video, interview, or rejected-then-accepted reapplication. Every one was checked against YC's company directory. Unverifiable accounts, coaching services and anonymous posts were excluded.

Each rule cites its source, and founder patterns show how many accepted cases support them. Research date: 1 Nov 2026.

## What Claude does with it
1. Builds a **founder fact sheet** from your conversation and asks only for what's missing.
2. Drafts **every application answer**. Each one comes with a character count, a one-line note on why it works, and what would strengthen it.
3. Gives **5 one-liner variants** and recommends one.
4. Runs a **red-flag scan**, covering buzzwords, inflated or mixed-period numbers, "no competitors" and top-down market sizing. It then lists your **3 weakest points**.
5. Writes **founder video talking points**, deliberately not a script, plus a checklist.
6. Prepares you for **the interview** and runs a live mock: one question at a time, interrupting long answers, then scoring.
7. Answers quick questions about applying: idea-stage, solo, reapplying, late applications, non-US companies, equity.

It never invents facts, numbers or stories. It never submits anything.

## a16z-speedrun-application
Fills out the a16z speedrun form field by field, keeping every answer within the form's character limits:
- one-liner: 100
- description: 800
- experience: 1,000 per founder
- team: 1,000
- anything else: 1,000

It also writes team-video talking points, reviews the deck, preps you for the interview and runs a mock interview.

**Sources:**
- **a16z's own pages:** speedrun.a16z.com apply, form, FAQ and deal.
- **The speedrun team's posts:** Andrew Chen, Josh Lu, Troy Kirwin, Kenan Saleh, Seeam Noor, Emily Bennett, Marcus Segal.
- **Accepted founders:** only those whose companies are listed on speedrun's site.

First-person accounts from accepted founders are much rarer for speedrun than for YC. Only 3 passed verification, so a16z's own guidance carries most of the weight. Research date: 1 Nov 2026.

## Install

**Claude apps (claude.ai / desktop):**
1. Download `yc-application.zip` and/or `a16z-speedrun-application.zip`, or zip the folder under `skills/` yourself.
2. Upload each one in Claude's skills settings and switch it on.

**Claude Code:**
```bash
git clone https://github.com/prisha2029/yc-application-skill
cp -r yc-application-skill/skills/* ~/.claude/skills/
```

**Claude API / Agent SDK:** upload each folder under `skills/` as a custom skill.

## Use
Just talk normally, for example:
- "Fill out my YC application."
- "Tighten my one-liner."
- "Write our founder video talking points."
- "We got a YC interview — run a mock."
- "We were rejected last batch for X; help me reapply."

For best results, paste the current questions and character limits from your live YC form. The form is behind a login and YC changes it.

## Layout
```
skills/yc-application/
├── SKILL.md                      workflow + non-negotiables
├── templates/fact-sheet.md       founder intake sheet
└── references/
    ├── writing-rules.md          rules for every answer + red-flag scan
    ├── question-playbook.md      per-question guidance + what accepted founders did
    ├── founder-video.md          video rules, talking-point template, checklist
    ├── interview.md              format, top questions (with counts), mock procedure
    ├── situations.md             idea-stage, solo, reapply, late, non-US, equity
    ├── accepted-founder-cases.md 29 verified companies + cross-case patterns
    └── sources.md                every YC / PG / partner source with codes
```

## Limits
- The 2026 form's exact wording and character limits couldn't be verified, because the form requires a login. The skill asks you to paste them.
- Deadlines, batches and the deal change. Always confirm at ycombinator.com/apply and ycombinator.com/faq.
- There are few detailed founder-video accounts. Indian, bio and hardware founder accounts are thin. Contributions with verifiable sources are welcome.
- These skills are not affiliated with Y Combinator or Andreessen Horowitz.

## License
MIT. Third-party content is paraphrased and linked, not reproduced. Read the original sources.
