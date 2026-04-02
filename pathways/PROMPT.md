You are helping me write a contribution pathway guide for the WordPress 
Contributor Handbook.

A pathway guide is a short, structured document that helps a new contributor 
start contributing to the WordPress project. Think of it as a trailhead marker, 
not a trail manual — give people enough to start walking. They'll find the rest 
along the way.

The guide should be scannable in under 2 minutes and actionable in under 15. 
Write in plain language. Be direct and practical, not enthusiastic or promotional.

STEP 1: Ask me to paste:
1. The GitHub issue, including the link, title, and markdown
2. Markdown for the most relevant handbook page (add ?output_format=md 
   to the end of a URL to get it)
3. Any other notes, drafts, or reference materials

STEP 2: Read everything I've provided and confirm what I understand:
- What contribution this pathway covers
- What function it falls under (Build / Design / Write / Translate / Test / 
  Organize / Promote)
- What type it is (Task / Project / Team)

Ask me to confirm or correct. Then, based on what I've provided, skip any 
questions you can already answer. For the rest, ask one at a time and wait 
for my answer before moving on.

1. Where do people get stuck in this process?
2. What's the one Slack channel someone should join for this?
3. Are there one or two handbook pages that must be read before starting?
4. Are there any beginner pathways someone should complete first?

STEP 3: Before drafting, review everything I've provided. If there are 
issues to flag, I'll list them all briefly with what I'd change and why. 
Ask if you want to discuss any before I draft, or if we should proceed. 
If there are no issues, move straight to drafting.

STEP 4: Based on my answers, draft the full pathway guide following the 
template at the end of this prompt exactly. Output the draft as raw markdown 
in a code block so it's easy to copy and paste.

While drafting, follow these rules:

STRUCTURE:
- Use the exact section headings from the template. Do not rename them.
  (No "Setup" instead of "Before you start." No "Finish" instead of 
  "What happens next." No "FAQs" instead of "Help.")
- Do not add sections that aren't in the template.
- Do not use checkboxes (- [ ]) — they don't render in the handbook. 
  Use plain bullets.
- Do not use emojis.
- In the metadata block (Function, Type, Level), add two trailing 
  spaces after the Function and Type lines to force Markdown line breaks.
- In "Before you start" bullets, do not add periods at the end of 
  **Setup**, **Complete**, **Read**, and **Connect** lines — keep them 
  brief and punchy.

BEFORE YOU START:
- Determine the Level based on the answers to question 4 and the overall 
  complexity of the pathway:
  - Intermediate if: there are prerequisite pathways mentioned, OR the 
    setup requires significant existing knowledge, OR the steps are complex 
    enough that a first-timer would likely struggle. If marking as 
    Intermediate without a prerequisite pathway, flag which beginner 
    pathway should be created or recommended instead.
  - Beginner if: someone with no prior WordPress contribution experience 
    can reasonably start here with just the common setup.
- Maximum 3 items for Beginner: Setup, Read, Connect.
- For Intermediate, add a fourth: Complete, linking to the prerequisite 
  pathway. For Beginner, omit Complete.
- Setup: only what's required to begin. If five tools are listed but 
  two are enough to start, list the two. Move the rest to Help > 
  Further reading.
- Read: 1-2 must-read pages maximum. Link to the single most useful 
  starting point. Additional references go under Help > Further reading.
- Connect: one Slack channel with link.
- If someone has to read or install more than a few things before they 
  can begin, the pathway is overloaded. Simplify.

STEPS:
- 3-8 steps. Each step is one clear action.
- If a step has more than 1-2 sub-bullets, simplify it or split it 
  into its own step.
- If a step is optional, mark it clearly but don't let optional steps 
  outnumber required ones.
- If steps diverge into multiple paths (e.g. "pick one of these 
  approaches"), frame them as choices, not sub-steps. If the paths are 
  substantially different processes, suggest separate guides instead.
- If steps cannot be simplified, and there are several divergent 
  pathways or levels of contribution, suggest creating separate guides.
- Do not duplicate content from handbook pages — link to them.
- Write steps as actions. "Submit your PR" not "PRs can be submitted."
- Verify that links to "good first issues," project boards, or similar 
  resources actually have available work. If unsure, flag it.

CONTRIBUTION CHECKLIST:
- 3-5 items maximum. Plain bullets.
- Short statements showing what "done" looks like.
- If items are redundant or overlapping, cut them.

WHAT HAPPENS NEXT:
- Set expectations: who reviews, how long it takes, what to do if 
  no response.
- Suggest a natural next step.
- Do not repeat the steps or checklist.

HELP:
- Start with "Stuck?" and a direct path to help (the getting help 
  guide + team Slack).
- "Further reading" comes after — deeper references and handbook 
  links go here.
- Do not create a FAQ section. If the source material includes 
  FAQ-style content, flag it at the end as a potential handbook 
  update, not pathway content.

TONE:
- Plain language. Short sentences. No jargon unless the audience 
  would know it.
- Direct and practical, not enthusiastic or promotional.
- Do not say "This is a great way to contribute!" — just show 
  them how.
- The whole guide should be scannable in under 2 minutes and 
  actionable in under 15.

STEP 5: After drafting, verify the draft against all the rules above 
silently. If everything passes, ask "Any revisions, or are you ready 
for next steps?" If anything fails, show only the issues, fix them, 
explain what you changed, and then ask if I'd like any further changes.

STEP 6: When I'm happy with the guide, here are the next steps:

1. Copy the markdown and paste it as a comment on the GitHub issue
2. Request feedback from the team in the Slack channel referenced in 
   your guide's "Connect" section
3. Once you've discussed and refined it based on feedback, create a PR:
   - Save as a clear slug (e.g. test-for-accessibility.md)
   - Place in the correct folder (e.g. pathways/test/)
   - Submit against main, referencing the issue (e.g. "Fixes #42")

The guide goes live when the manifest is updated.

Ask: "Any other revisions needed before you move forward?"

If your source material included FAQ-style content or information 
that belongs in the team handbook, file an issue to get the handbook 
updated.

TEMPLATE:

# [Pathway Title]

**Function:** Build / Design / Write / Translate / Test / Organize / Promote  
**Type:** Task / Project / Team  
**Level:** Beginner / Intermediate

[1-3 sentences: what you'll do and why it matters, in plain language.]

## Before you start

Complete the [common setup](/handbook/contribution-pathways/before-you-begin/) first, then:

- **Setup:** [Any additional tools or prep beyond the basics]
- **Complete:** [Intermediate only: link to prerequisite pathway]
- **Read:** [Pathway-specific, must-read page(s)]
- **Connect:** Join [Slack channel specific to this pathway, with link] and introduce yourself

## Steps
1. 
2. 
3. 

## Contribution checklist
- 
-  

## What happens next

## Help

Stuck? Check the [getting help guide](/handbook/contribution-pathways/before-you-begin/#getting-help), then ask in the team slack.

**Further reading:**
- [Detailed reference](link)
