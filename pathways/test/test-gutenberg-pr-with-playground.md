# Test a Gutenberg Pull Request with Playground

**Function:** Test  
**Type:** Task  
**Level:** Beginner

Test a Gutenberg pull request and post a report. Your feedback helps developers confirm whether a change works as expected before it ships to millions of WordPress sites. No coding required — just a browser and a WordPress site to test on.

## Before you start

Complete the [common setup](/handbook/contribution-pathways/before-you-begin/) first, then:

- **Setup:** Have a WordPress site available for testing — [WordPress Playground](https://playground.wordpress.net/) works and requires no installation
- **Read:** [Test Reports](https://make.wordpress.org/test/handbook/test-reports/) — how to write and format your findings
- **Connect:** Join [#core-editor](https://wordpress.slack.com/messages/core-editor) on Slack and introduce yourself

## Steps

1. Find a PR to test. Browse [Gutenberg PRs that need testing](https://github.com/WordPress/gutenberg/issues?q=state%3Aopen%20label%3A%22Needs+Testing%22%20is%3Apr) and pick one that interests you. If there are no PRs available with that label, check the [Test pathways index](https://make.wordpress.org/handbook/pathways/test/) for other ways to contribute through testing while you wait.
2. Read the PR description carefully. Scroll through the full description, testing instructions are often included further down under a "Testing Instructions" section. If testing instructions are provided, follow them. If not, look for the user-facing behavior described in the PR — what should a user see or experience differently? Test that.
3. Get the PR running on a WordPress site. Find the PR number after the `#` in the PR title or in the page URL (e.g. `github.com/WordPress/gutenberg/pull/12345`). Go to [gutenberg.run](https://gutenberg.run/), enter the number, and wait for it to load — it opens a WordPress site with the PR's changes already applied. If it says the PR isn't ready, the build is still running — try again in a few minutes or pick a different PR from the list.
4. Test the change. Follow the PR's testing instructions if provided. If not, focus on the specific area the PR changes — try to confirm that the fix or feature works as described, and check that nothing nearby appears broken.
5. Write your test report as a comment on the PR. Include:
   - Your environment (OS, browser, WordPress version, Gutenberg version)
   - The steps you followed
   - What you observed — use ✅ for expected behavior and ❌ for unexpected behavior
   - Screenshots or a short screen recording if helpful
6. Post your comment on the PR. A confirmed pass is just as valuable as catching a bug.

## Contribution checklist

- PR tested on a working WordPress site
- Testing instructions followed (or noted as absent)
- Test report posted as a comment on the PR
- Environment details included in the report
- Results marked clearly with ✅ or ❌

## What happens next

The PR author or a reviewer will see your comment. If your report confirms the fix works, it moves the PR closer to being merged into WordPress. If you found an issue, the developer will follow up in the PR comments.

If you don't hear back within a week and the PR is still open, follow up with a comment or ask in [#core-editor](https://wordpress.slack.com/messages/core-editor).

Once you've tested one PR, pick up another from the [Needs Testing queue](https://github.com/WordPress/gutenberg/issues?q=state%3Aopen%20label%3A%22Needs+Testing%22%20is%3Apr) or explore other [Test pathways](https://make.wordpress.org/handbook/pathways/test/).

## Help

Stuck? Check the [getting help guide](/handbook/contribution-pathways/before-you-begin/#getting-help), then ask in [#core-editor](https://wordpress.slack.com/messages/core-editor) on Slack. Include a link to the PR you're working on.

**Further reading:**
- [Test Reports](https://make.wordpress.org/test/handbook/test-reports/) — full guide to writing test reports
- [Get Set Up for Testing](https://make.wordpress.org/test/handbook/get-setup-for-testing/) — options for setting up a local test environment
- [Testing a Gutenberg PR](https://make.wordpress.org/design/2021/03/03/testing-a-gutenberg-pull-request-pr/) — walkthrough of the plugin zip download method
