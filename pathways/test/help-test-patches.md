# Test WordPress Patches

**Function:** Test  
**Type:** Task  
**Level:** Beginner

Test patches on WordPress core tickets to validate fixes before release. Test independently at your own pace, or join weekly team sessions for guided support.

## Before you start

Complete the [common setup](https://make.wordpress.org/handbook/contribution-pathways/before-you-begin/) first, then:

- **Setup:** Set up [WordPress Playground](https://playground.wordpress.net/) for testing patches
- **Read:** [Patch Testing](https://make.wordpress.org/test/handbook/test-reports/patch-testing/) and [Test Core Tickets with Playground](https://make.wordpress.org/test/handbook/get-setup-for-testing/test-core-tickets-with-playground/)
- **Connect:** Join [#core-test](https://wordpress.slack.com/archives/core-test) and introduce yourself

## Steps
1. **Find a ticket to test.** You have two options here:
- **On your own:** Browse [WordPress Trac](https://core.trac.wordpress.org/) for tickets that need testing. Look for tickets tagged with `needs-testing` or `has-patch`.
- **With guidance:** Join a Patch Testing Scrub, where experienced contributors assign tickets and guide you through testing. Check the [Test team meeting calendar](https://make.wordpress.org/meetings/#test) for upcoming scrub times.

2. **Check for a testable patch.** Look for a GitHub PR link in the ticket. If there's only a `.patch` file, ask in #core-test for help or skip to another ticket.

3. **Open the patch in Playground.** Click "View PR" to open the GitHub pull request. Find the comment that says "Test this pull request with WordPress Playground" and click the link.

4. **Test the patch.** Check:
- Whether the patch fixes the reported issue
- Any unintended side effects or regressions
- How it behaves in different scenarios

5. **Submit your test report to Trac.** Add a comment to the Trac ticket with your results using one of these methods:
- **Test Reports plugin:** Use [Generating Reports with the Test Reports Plugin](https://make.wordpress.org/test/handbook/test-reports/patch-testing/#generating-reports-with-the-test-reports-plugin) on your test site to auto-generate a report with your environment details pre-filled.
- **Manual template:** Copy the [Patch Testing Report Template](https://make.wordpress.org/test/handbook/test-reports/patch-testing/#patch-testing-report-template) into a text editor, fill in your details and findings, then post it as a comment on the ticket.

## Contribution checklist

- Test report posted on the Trac ticket
- Environment documented (OS, PHP, WordPress version, browser)
- Confirmed whether patch fixes the issue and noted any regressions


## What happens next
The patch maintainer will review your test report to determine if the patch is ready. They may ask follow-up questions in the ticket comments.

Continue testing patches on your own or join the regular Patch Testing Scrubs for guided support and community.

## Help

Stuck? Check the [getting help guide](https://make.wordpress.org/handbook/contribution-pathways/before-you-begin/#getting-help), then ask in [#core-test](https://wordpress.slack.com/archives/core-test).

**Further reading:**
- [Patch Testing templates and examples](https://make.wordpress.org/test/handbook/test-reports/patch-testing/)
- [WordPress Playground documentation](https://wordpress.github.io/wordpress-playground/)
- [Test reports overview](https://make.wordpress.org/test/handbook/test-reports/)
- [Test Reports Plugin](https://wordpress.org/plugins/test-reports/)
