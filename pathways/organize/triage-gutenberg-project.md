# Triage Gutenberg Issues

Triaging keeps the Gutenberg repository healthy. You review issues, check whether bugs still happen, add labels, and organize reports so the right people can act on them. You do not need to be a developer or designer.

- **Reference:** [Triage handbook](https://developer.wordpress.org/block-editor/contributors/triage/) — full reference for labels, closing policies, and escalation
- **Connect:** Join [#core-editor](https://wordpress.slack.com/archives/core-editor), introduce yourself, share your GitHub username, and ask to be added to the triage team

## Steps

1. **Set up your testing environment.** Open [WordPress Playground](https://wordpress.org/playground/) in your browser. You'll use it to test and reproduce issues.

2. **Pick a starter queue.** Open one of these filtered lists and work through issues one by one:
   - [Issues without a label](https://github.com/WordPress/gutenberg/issues?q=is%3Aopen+is%3Aissue+no%3Alabel+sort%3Aupdated-asc) — easiest place to start, you just need to categorize them
   - [Least recently updated issues](https://github.com/WordPress/gutenberg/issues?q=is%3Aopen+is%3Aissue+sort%3Aupdated-asc) — prevents important work from being overlooked
   - Issues sorted by comments ([none](https://github.com/wordpress/gutenberg/issues?q=is%3Aissue+is%3Aopen+comments%3A0+), [fewest](https://github.com/wordpress/gutenberg/issues?q=is%3Aissue+is%3Aopen+sort%3Acomments-asc), [most](https://github.com/wordpress/gutenberg/issues?q=is%3Aissue+is%3Aopen+sort%3Acomments-desc)) — surfaces overlooked or stalled discussions
   - [Issues by specific block or feature label](https://github.com/WordPress/gutenberg/labels) — for focused triage once you're comfortable

3. **Read the issue.** Identify what is broken or missing, what the reporter expected, and what actually happened. Determine whether it's a bug report, an enhancement request, a help request, or unclear.

4. **Search for duplicates.** Search open and closed issues for similar reports. If the issue is a duplicate, close the newer one with a comment like "Duplicate of #12345" and add any useful new details to the original.

5. **Add labels.** Start with a `[Type]` label (`[Type] Bug`, `[Type] Enhancement`, or `[Type] Help Request`), then add more specific labels like `[Block]` or `[Feature]` if applicable. See the [full label list](https://github.com/WordPress/gutenberg/labels) for options.

6. **Confirm bugs or request more information.** If you can reproduce the bug, comment with the steps you used, the environment you tested in, and what you observed. If you cannot reproduce it or the report lacks detail, add the `[Status] Needs More Info` label and ask the reporter for steps to reproduce.

## Contribution checklist

- Triaged at least one issue from a starter queue
- Added a label, confirmed a bug, or requested missing information
- Left a clear comment explaining what you found or what is needed

## What happens next

Your triage work takes effect immediately. There is no review step — once you add labels or comments, other contributors can see and act on them.

If no one responds to a question you asked on an issue, wait two weeks, then follow up or close the issue with a note explaining why.

When you're comfortable with the basics, try focusing on a specific block or feature label to build deeper familiarity with one area. You can also join the organized triage sessions listed on the [WordPress meetings page](https://make.wordpress.org/meetings/).

## Help

Stuck? Check the [getting help guide](https://make.wordpress.org/handbook/pathways/before-you-begin/#getting-help), then ask in [#core-editor](https://wordpress.slack.com/archives/core-editor). Include a link to the issue you're working on.

**Further reading:**
- [How to do triage on GitHub](https://learn.wordpress.org/lesson/how-to-do-triage-on-github/) — video tutorial
- [Set up a local WordPress instance](https://learn.wordpress.org/lesson-plan/local-install/) — alternative to Playground for testing

<div class="wp-block-wporg-sidebar-container is-floating-sidebar" data-breakpoint="1300px">
  <div class="pathway-info">
    <div class="pathway-header">
      <span class="dashicons dashicons-networking"></span> Organize
    </div>
    <div class="pathway-dtails">
      <p>Beginner-friendly task</p>
      <p class="newbies">New here? <a href="https://make.wordpress.org/handbook/pathways/before-you-begin/">Get set up</a> with accounts, community basics, and info on badges. →</p>
    </div>
  </div>
</div>
