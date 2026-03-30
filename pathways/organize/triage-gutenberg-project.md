# Organize: Triage Gutenberg issues

**Function:** Organize\
**Type:** Project\
**Level:** Beginner

Triaging keeps the Gutenberg repository healthy. You review issues, check whether bugs still happen, add labels, and organize reports so the right people can act on them. You do not need to be a developer or designer.

## Before you start

Complete the [common setup](/handbook/contribution-pathways/before-you-begin/) first, then:

- **Setup:** Open [WordPress Playground](https://wordpress.org/playground/) in your browser (or a [local instance](https://learn.wordpress.org/lesson-plan/local-install/)). You will use it to test and reproduce issues.
- **Read:** [Triage handbook](https://developer.wordpress.org/block-editor/contributors/triage/)
- **Connect:** Join [#core-editor](https://wordpress.slack.com/archives/C02QB2JS7), introduce yourself, share your GitHub username, and ask to be added to the triage team.

## Steps

1. **Pick a starter queue.** Open one of these filtered lists and work through issues one by one:
   - [Issues without a label](https://github.com/WordPress/gutenberg/issues?q=is%3Aopen+is%3Aissue+no%3Alabel+sort%3Aupdated-asc) (easiest place to start - you just need to categorize them)
   - [Least recently updated issues](https://github.com/WordPress/gutenberg/issues?q=is%3Aopen+is%3Aissue+sort%3Aupdated-asc) (prevents important work from being overlooked)
   - [Issues with no comments](https://github.com/wordpress/gutenberg/issues?q=is%3Aissue+is%3Aopen+comments%3A0+) (makes sure every report gets acknowledged)
   - [Least commented issues](https://github.com/wordpress/gutenberg/issues?q=is%3Aissue+is%3Aopen+sort%3Acomments-asc) (additional starter queue)
   - [Most commented issues](https://github.com/wordpress/gutenberg/issues?q=is%3Aissue+is%3Aopen+sort%3Acomments-desc) (good for summarizing stalled discussions)
   - [Issues by specific block or feature label](https://github.com/WordPress/gutenberg/labels) (for focused triage once you are comfortable)

2. **Read the issue.** Identify what is broken or missing, what the reporter expected, and what actually happened. Determine whether it is a bug report, an enhancement request, a help request, or unclear.

3. **Search for duplicates.** Search open and closed issues for similar reports. If the issue is a duplicate, close the newer one with a comment like "Duplicate of #12345" and add any useful new details to the original.

4. **Add labels.** Start with a `[Type]` label (`[Type] Bug`, `[Type] Enhancement`, or `[Type] Help Request`), then add more specific labels like `[Block]` or `[Feature]` if applicable. See the [full label list](https://github.com/WordPress/gutenberg/labels) for options.

5. **Confirm bugs or request more information.** If you can reproduce the bug, comment with the steps you used, the environment you tested in, and what you observed. If you cannot reproduce it or the report lacks detail, add the `[Status] Needs More Info` label and ask the reporter for steps to reproduce.

6. **Improve the title** (optional). If the title is vague, edit it to put the main feature first and keep it short but descriptive. Example: "Navigation block: Page List should auto-convert when inserting new blocks."

## Contribution checklist

- You triaged at least one issue from a starter queue
- You added a label, confirmed a bug, or requested missing information
- You left a clear comment explaining what you found or what is needed
- If you closed an issue, you included a short, kind explanation and linked to any related issue

## What happens next

Your triage work takes effect immediately. There is no review step - once you add labels or comments, other contributors can see and act on them.

If no one responds to a question you asked on an issue, wait two weeks, then follow up or close the issue with a note explaining why.

When you are comfortable with the basics, try focusing on a specific block or feature label to build deeper familiarity with one area. You can also join the organized triage sessions listed on the [WordPress meetings page](https://make.wordpress.org/meetings/).

## Help

Stuck? Check the [getting help guide](/handbook/contribution-pathways/before-you-begin/#getting-help), then ask in [#core-editor](https://wordpress.slack.com/archives/C02QB2JS7). Include a link to the issue you are working on.

**Further reading:**
- [How to do triage on GitHub](https://learn.wordpress.org/lesson/how-to-do-triage-on-github/) (video tutorial)
- [Triage handbook](https://developer.wordpress.org/block-editor/contributors/triage/) (full reference for labels, closing policies, and escalation)
