# Contribute to a Core Good First Bug

Pick a small, beginner-friendly Core ticket, write a fix, and submit it for review. Fixing a good first bug is the quickest way to learn Core's code, standards, and review process.

- **Prerequisite:** [Work on a Core Component](https://make.wordpress.org/handbook/pathways/build/work-on-a-core-component/) — learn how Trac tickets and bug scrubs work before writing a fix
- **Reference:** [Contribute with Code](https://make.wordpress.org/core/handbook/contribute/) — environment setup, patches, and review
- **Connect:** Join [#core](https://wordpress.slack.com/archives/core) on Slack and introduce yourself

## Steps

1. **Set up a local environment.** Clone the [wordpress-develop repository](https://github.com/WordPress/wordpress-develop) and start the Docker environment with `npm run env:start`. [Contribute with Code](https://make.wordpress.org/core/handbook/contribute/) lists alternatives if you can't use Docker.

2. **Read the core best practices.** Start with [Writing Patches](https://make.wordpress.org/core/handbook/best-practices/writing-patches/), [Coding Standards](https://make.wordpress.org/core/handbook/best-practices/coding-standards/), and [Inline Documentation Standards](https://make.wordpress.org/core/handbook/best-practices/inline-documentation-standards/). Skim the rest of the [Best Practices](https://make.wordpress.org/core/handbook/best-practices/) and return to them as your ticket needs.

3. **Pick a good first bug.** Open the [Good First Bugs report](https://core.trac.wordpress.org/tickets/good-first-bugs) and look in the "Unclaimed" section. Choose a ticket where the approach is already decided, and read its comments to confirm no one else is working on it. If you find a security issue instead, don't file a public ticket; follow the [security reporting guide](https://make.wordpress.org/core/handbook/testing/reporting-security-vulnerabilities/).

4. **Claim the ticket.** Comment on the ticket to say you're working on it.

5. **Reproduce the bug.** Confirm the problem on the latest trunk in your local environment before changing anything.

6. **Write and test your fix.** Work from the latest trunk, keep the change small, and follow the coding standards. Check that the bug is gone and nothing else broke.

7. **Submit it for review.** Choose one:
   - Attach a patch to the Trac ticket.
   - Open a pull request on wordpress-develop that includes the full Trac ticket URL, and allow edits from maintainers.

## Contribution checklist

- Commented on the ticket to claim it
- Reproduced the bug before the fix and tested after
- Change follows Core coding standards
- Patch attached, or pull request opened with the Trac ticket URL

## What happens next

A component maintainer or any committer can review and commit your fix. Expect feedback on the ticket; reply there and update your patch as needed. If your patch no longer applies, add the `needs-refresh` keyword and upload a new one.

If your ticket stalls, ping a component maintainer or committer, or raise it during open floor at the end of the [weekly core developer chat](https://make.wordpress.org/core/tag/agenda/).

When you're ready, pick another ticket or follow a component more closely. Accepted work is credited through [contributor attribution ("props")](https://make.wordpress.org/core/handbook/best-practices/contributor-attribution-props/).

## Help

Stuck? Check the [getting help guide](https://make.wordpress.org/handbook/pathways/before-you-begin/#getting-help), then ask in [#core](https://wordpress.slack.com/archives/core).

**Further reading:**
- [FAQs for New Contributors](https://make.wordpress.org/core/handbook/tutorials/faq-for-new-contributors/)
- [Trac workflow keywords](https://make.wordpress.org/core/handbook/contribute/trac/keywords/)
- [GitHub pull requests for code review](https://make.wordpress.org/core/handbook/contribute/git/github-pull-requests-for-code-review/)
- [Code Refactoring](https://make.wordpress.org/core/handbook/contribute/code-refactoring/) — why refactor-only patches are rarely accepted

<div class="wp-block-wporg-sidebar-container is-floating-sidebar" data-breakpoint="1300px">
  <div class="pathway-info">
    <div class="pathway-header">
      <span class="dashicons dashicons-editor-code"></span> Build
    </div>
    <div class="pathway-details">
      <p>Intermediate task</p>
      <p class="newbies">New here? <a href="https://make.wordpress.org/handbook/pathways/before-you-begin/">Get set up</a> with accounts, community basics, and info on badges. →</p>
    </div>
  </div>
</div>
