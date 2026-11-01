# The YC interview

## Format
- About **10 minutes**, usually on Zoom, with 2–5 YC partners. They have your application open, and all founders should attend [DC-2023; JL-2016]. Accepted founders consistently report 10 minutes with 3–5 partners and no small talk (Hera S21, PostHog W20, Nebullam W19 and others).
- YC's own guide says you don't need much preparation [YC-INT]. Read https://www.ycombinator.com/interviews before the interview, since the format can change.
- **Follow-up calls are common.** A second interview, a technical deep-dive or a call with different partners happened in 5 of the 19 verified accepted-founder accounts (Onu W23, SimCare S24, Lingo.dev F24, Vitable S20, InsForge Spring 2026).
- Feedback is only given to teams that interview. Rejection emails after an interview often contain specific reasons (Gumloop W24, Metorial F25).

## How to answer (partners and accepted founders agree)
- **Answer first, then add detail.** Use the inverted pyramid [GT-INT].
- **Keep each answer to 1–3 sentences, about 10–15 seconds.** Reported by Shogun W18, Hera S21 and InsForge Spring 2026.
- **Have a conversation, not a pitch.** Never recite memorized speeches; robotic answers are a red flag [JL-2015; DC-2023].
- **Use plain words.** Jargon sounds fake [JL-2015; Stilt W16].
- **Give specifics:** numbers, names, real user stories [JL-2015].
- **Say "I don't know"** rather than deflect [Shogun W18]. Overconfidence is a red flag, and self-awareness about the risks is a plus [DC-2018].
- **Show mastery of your own business:** know your numbers, risks and next steps [DC-2023; GT-INT].
- **Explain the product without a demo.** Needing one to explain what you do is a warning sign [JL-2015]. Still keep a 1–2 minute demo ready in case they ask (Basedash S20, PostHog W20). Make sure your laptop is online, because PostHog's demo died on wifi.
- **Partners probe your weakest point** (Gumloop W24, PostHog W20). Find it before they do.
- **Volunteer your strongest facts early** (Nebullam W19 led with three).
- **Co-founders split the topics in advance** and don't talk over each other (Hera S21, Nebullam W19, Nuvocargo W18, webapp.io S20).

## Most frequently asked questions
Below are the questions accepted founders most often report, with the number of verified cases in brackets, followed by the topics partners say they probe. Prepare a one-sentence answer to each, then one follow-up layer.

1. What are you building / working on? This is almost always first (5).
2. How do you know people want this? Who's using it, who's paying, why would anyone pay? (5)
3. Team: who does what, how you know each other, are you full-time, why no co-founder? (5)
4. Competition: how are you different? Couldn't an incumbent build this? What's your moat? (5)
5. How big can this get? How do you make money? (4)
6. Show me a demo (2).
7. What changed since you applied? Metrics growth (1).

Situational questions from partners [DC-2023]:
- Pre-launch: when do you launch?
- Regulated space: how will you handle regulation?
- Crowded market: how are you different?
- Idea pivot: would you work on a different idea? (Onu W23 was asked this, brainstormed with partners, and got in.)

Other questions worth preparing, drawn from the same partner topics: Who needs this most, and how do you know? What's the hardest part? Where will your first users come from? What's your growth rate? What did you learn from users? Why now? What would you do if YC said no?

## Preparation that accepted founders report
- **Mock interviews,** mostly with YC alumni, asking them to interrupt and push back. 9 verified cases did this, with counts ranging from 5 to about 50 [PostHog W20, Nebullam W19, webapp.io S20, Lingo.dev F24, Vitable S20 and others; GT-INT].
- **A written sheet of questions and answers.** Some add a "decision tree" of follow-ups (webapp.io S20).
- **Timed 10-minute runs** (Nuvocargo W18).
- **Script only the one-liner.** Everything else is talking points (Basedash S20).
- **Keep a metrics doc open** during the call (Basedash S20).
- **Research the interviewing partners** on the day if YC names them (Nuvocargo W18, Basedash S20, webapp.io S20).
- **Don't over-prepare broadly.** Focus on the 7 questions above and your weakest point (Hera S21's regret).
- **Avoid paid intermediaries** promising admission. Dalton Caldwell calls them scammers [DC-2023].

## How Claude should run a mock interview
1. Read the founder fact sheet (`templates/fact-sheet.md`) and the drafted application.
2. Ask one question at a time, starting with "What are you working on?"
3. Interrupt long answers. After each answer, flag:
   - answers longer than 3 sentences
   - jargon
   - missing numbers
   - a dodge, where "I don't know" would have been better
4. Push on the weakest area identified in the application: traction, competition, team commitment, or market size.
5. Finish with a scored list of the 3 answers to tighten and a rewritten one-sentence version of each.
6. Never invent facts for the founder's answers. If a fact is missing, say what to go find out.
