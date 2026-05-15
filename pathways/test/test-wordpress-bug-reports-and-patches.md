# Test WordPress Bug Reports and Patches

**Function:** Test  
**Type:** Task  
**Level:** Beginner  

Follow established testing workflows to reproduce reported bugs or test code patches against WordPress Trac tickets. Every test report helps ensure WordPress releases are stable by confirming issues and validating fixes. You can do this on your own, or join a [Patch Testing Scrub](https://make.wordpress.org/meetings/#test) for facilitated support where experienced contributors assign tickets and guide you through the process.

## Before you start

Complete the [common setup](/handbook/pathways/before-you-begin/) first, then:

- **Setup:** Set up [WordPress Playground](https://playground.wordpress.net/) for quick testing, or a [local WordPress environment](https://make.wordpress.org/core/handbook/tutorials/installing-wordpress-locally/) for more thorough testing. You'll also need a [WordPress Trac](https://core.trac.wordpress.org/) account to submit test reports
- **Read:** Read through the [Test Team Handbook](https://make.wordpress.org/test/handbook/) to understand how the team works and where testing fits into the WordPress development process
- **Connect:** Join [#core-test](https://wordpress.slack.com/archives/core-test) on Slack and introduce yourself

## Steps

1. **Choose a testing workflow.** There are two main ways to contribute:
   - **Issue reproduction:** Confirm whether reported bugs are reproducible. Follow the [Issue Reproduction workflow](https://make.wordpress.org/test/handbook/test-reports/issue-reproduction/).
   - **Patch testing:** Test code patches against Trac tickets to validate fixes. Follow the [Patch Testing workflow](https://make.wordpress.org/test/handbook/test-reports/patch-testing/).
2. **Find a ticket to test.** You have two options here:
   - **On your own:** Browse [WordPress Trac](https://core.trac.wordpress.org/) for tickets that need testing. Look for tickets tagged with `needs-testing` or `has-patch`.
   - **With guidance:** Join a Patch Testing Scrub, where experienced contributors assign tickets and guide you through testing. Check the [Test team meeting calendar](https://make.wordpress.org/meetings/#test) for upcoming scrub times.
3. **Run through the testing workflow.** Follow the steps in the relevant handbook page. Set up your environment, reproduce the issue or apply the patch, and document what you find. Be thorough and note your environment, browser, OS, and the steps you took. If you're testing a patch with a GitHub PR link, look for the "Test this pull request with WordPress Playground" comment for a one-click way to load the patch.
4. **Submit your test report.** Post your findings directly on the Trac ticket as a comment. Use one of the [Test Report templates](https://make.wordpress.org/test/handbook/test-reports/) for consistency. Include what you tested, how you tested it, your environment details (OS, PHP, WordPress version, browser), and whether you could reproduce the issue or confirm the fix works. If you notice any gaps or errors in the testing documentation itself, open an issue or PR on the [Test Handbook GitHub repository](https://github.com/WordPress/test-handbook).

## Contribution checklist

- Testing environment set up (Playground or local install)
- Ticket selected from WordPress Trac
- Testing workflow followed (issue reproduction or patch testing)
- Environment details documented (OS, PHP, WordPress version, browser)
- Test report submitted directly on the Trac ticket

## What happens next

A developer or committer will review your test report alongside others on the ticket. Your report helps them decide whether a bug is confirmed or whether a patch is ready to commit. If you've reported a regression, they may ask follow-up questions in the Trac comment thread, so check back on the ticket to see if anyone responds.

As you get comfortable, keep contributing on your own or join the regular Patch Testing Scrubs for guided support and to connect with other testers. Consistent testing contributions can earn you a [Test Team profile badge](https://make.wordpress.org/test/handbook/test-team-profile-badges/).

## Help

Stuck? Check the [getting help guide](/handbook/pathways/before-you-begin/#getting-help), then ask in [#core-test](https://wordpress.slack.com/archives/core-test).

**Further reading:**
- [Test Team Handbook](https://make.wordpress.org/test/handbook/)
- [Issue Reproduction workflow](https://make.wordpress.org/test/handbook/test-reports/issue-reproduction/)
- [Patch Testing workflow](https://make.wordpress.org/test/handbook/test-reports/patch-testing/)
- [Test Reports and templates](https://make.wordpress.org/test/handbook/test-reports/)
- [Test Core Tickets with Playground](https://make.wordpress.org/test/handbook/get-setup-for-testing/test-core-tickets-with-playground/)
- [Documenting Testing Flow](https://make.wordpress.org/test/handbook/documenting-flow/)
- [Test Handbook GitHub repository](https://github.com/WordPress/test-handbook)
- [WordPress Trac](https://core.trac.wordpress.org/)
