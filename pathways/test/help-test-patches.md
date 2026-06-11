# Test WordPress Patches

Test patches on WordPress core tickets to validate fixes before release. Test independently at your own pace, or join weekly team sessions for guided support.

- **Reference:** [Test Core Tickets with Playground](https://make.wordpress.org/test/handbook/get-setup-for-testing/test-core-tickets-with-playground/)
- **Connect:** Join [#core-test](https://wordpress.slack.com/archives/core-test) and introduce yourself

## Steps

1. **Find a ticket to test.** You have two options:
   - **On your own:** Browse [WordPress Trac](https://core.trac.wordpress.org/) for tickets tagged `needs-testing` or `has-patch`.
   - **With guidance:** Join a Patch Testing Scrub, where experienced contributors assign tickets and guide you through testing. Check the [Test team meeting calendar](https://make.wordpress.org/meetings/#test) for upcoming scrub times.

2. **Check for a testable patch.** Look for a GitHub PR link in the ticket. If there's only a `.patch` file, ask in #core-test for help or skip to another ticket.

3. **Open the patch in Playground.** Click "View PR" to open the GitHub pull request. Find the comment that says "Test this pull request with WordPress Playground" and click the link.

4. **Test the patch.** Check whether the patch fixes the reported issue, look for unintended side effects or regressions, and try different scenarios.

5. **Submit your test report.** Add a comment to the Trac ticket with your results. Use the [Test Reports plugin](https://wordpress.org/plugins/test-reports/) to auto-generate a report with your environment details pre-filled, or copy the [Patch Testing Report Template](https://make.wordpress.org/test/handbook/test-reports/patch-testing/#patch-testing-report-template) and fill it in manually.

## Contribution checklist

- Test report posted on the Trac ticket
- Environment documented (OS, PHP, WordPress version, browser)
- Confirmed whether patch fixes the issue and noted any regressions

## What happens next

The patch maintainer will review your test report to determine if the patch is ready. They may ask follow-up questions in the ticket comments.

Continue testing patches on your own or join the regular Patch Testing Scrubs for guided support and community.

## Help

Stuck? Check the [getting help guide](https://make.wordpress.org/handbook/pathways/before-you-begin/#getting-help), then ask in [#core-test](https://wordpress.slack.com/archives/core-test).

**Further reading:**
- [Patch Testing templates and examples](https://make.wordpress.org/test/handbook/test-reports/patch-testing/)
- [WordPress Playground documentation](https://wordpress.github.io/wordpress-playground/)
- [Test reports overview](https://make.wordpress.org/test/handbook/test-reports/)

<div class="wp-block-wporg-sidebar-container is-floating-sidebar" data-breakpoint="1300px">
  <div class="pathway-info">
    <div class="pathway-header">
      <span class="dashicons dashicons-welcome-view-site"></span> Test
    </div>
    <div class="pathway-dtails">
      <p>Beginner-friendly task</p>
      <p class="newbies">New here? <a href="https://make.wordpress.org/handbook/pathways/before-you-begin/">Get set up</a> with accounts, community basics, and info on badges. →</p>
    </div>
  </div>
</div>
