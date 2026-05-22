# Patch Testing

**Function:** Test  
**Type:** Team  
**Level:** Beginner

Join the Core Test team to validate patches during weekly testing sessions. Test patches on WordPress core tickets, report your findings, and help catch bugs before release.

## Before you start

Complete the [common setup](/handbook/contribution-pathways/before-you-begin/) first, then:

- **Setup:** Plan to join the patch testing session on Tuesday at 15:00 UTC
- **Read:** [Patch Testing](https://make.wordpress.org/test/handbook/test-reports/patch-testing/) and [Test Core Tickets with Playground](https://make.wordpress.org/test/handbook/get-setup-for-testing/test-core-tickets-with-playground/)
- **Connect:** Join the [Core Test Slack channel](https://wordpress.slack.com/archives/core-test) and introduce yourself

## Steps

1. **Attend the patch testing session.** Join the Core Test Slack channel on Tuesday at 15:00 UTC. The team leads the session and assigns tickets to test.

2. **Find a ticket to test.** Ask in the Slack thread or during the live session which ticket you should test. The team will guide you to one that matches your skill level.

3. **Check for an available patch.** Open the [Core Trac](https://core.trac.wordpress.org/tickets/has-patch). Look for a GitHub PR link in the ticket description. If there's a PR, you can test it with Playground. If there's only a `.patch` file, skip to the team handbook or channel to ask about testing options.

4. **Open the patch in Playground.** Click "View PR" to open the GitHub pull request. Find the comment that says "Test this pull request with WordPress Playground" and click the link. A temporary WordPress site with the patch will load in your browser.

5. **Test the patch.** Follow any testing instructions in the ticket. Look for:
   - Whether the patch fixes the reported issue
   - Any unintended side effects (regressions)
   - How it behaves in different scenarios

6. **Submit your test report to Trac.** Add a comment to the Trac ticket with your results using one of these methods:
   - **Test Reports plugin:** Use [Generating Reports with the Test Reports Plugin](https://make.wordpress.org/test/handbook/test-reports/patch-testing/#generating-reports-with-the-test-reports-plugin) on your test site to auto-generate a report with your environment details pre-filled.
   - **Manual template:** Copy the [Patch Testing Report Template](https://make.wordpress.org/test/handbook/test-reports/patch-testing/#patch-testing-report-template) into a text editor, fill in your details and findings, then post it as a comment on the ticket.

## Contribution checklist

- Your test report is posted as a comment on the Trac ticket
- You've documented your environment (OS, PHP, WordPress version, browser)
- You've noted whether the patch fixes the issue and if you found any regressions

## What happens next

The patch maintainer will review your test report and use it to decide whether the patch is ready. If you've reported a regression or issue, they may ask follow-up questions in the Trac comment thread. Check back on the ticket to see if anyone responds.

Return to the Tuesday session the following week to test the next batch of patches.

## Help

Stuck? Check the [getting help guide](/handbook/contribution-pathways/before-you-begin/#getting-help), then ask in the [Core Test Slack channel](https://wordpress.slack.com/archives/core-test).

**Further reading:**
- [Patch Testing templates and examples](https://make.wordpress.org/test/handbook/test-reports/patch-testing/)
- [WordPress Playground documentation](https://wordpress.github.io/wordpress-playground/)
- [Test reports overview](https://make.wordpress.org/test/handbook/test-reports/)
- [Test Reports Plugin](https://wordpress.org/plugins/test-reports/)
