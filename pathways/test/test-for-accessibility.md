# Test: Test for Accessibility

**Function:** Test  
**Type:** Task

You'll find accessibility tickets, test them using your keyboard, browser tools, and optionally a screen reader, then report your findings. Every test result helps the Accessibility team identify and fix barriers that prevent people with disabilities from using WordPress.

## Before you start

Complete the [common setup](/handbook/contribution-pathways/before-you-begin/) first, then:

- **Setup:** Install the [axe DevTools browser extension](https://www.deque.com/axe/browser-extensions/). Optionally install [WAVE](https://wave.webaim.org/extension/) for visual checks, and [NVDA](https://www.nvaccess.org/download/) (Windows) or VoiceOver (built into Mac) for screen reader testing. A [local environment](https://make.wordpress.org/core/handbook/tutorials/installing-wordpress-locally/) or [WordPress Playground](https://playground.wordpress.net/) can be used for testing patches. Your keyboard and axe DevTools are enough to start.
- **Read:** Browse the [WebAIM WCAG Checklist](https://webaim.org/standards/wcag/checklist) to familiarize yourself with AA criteria — WordPress targets [WCAG 2 AA](https://www.w3.org/WAI/standards-guidelines/wcag/). Also review the [Accessibility Quick Start Guide](https://wpaccessibility.org/docs/start/quick-wins/) and [Test for Web Accessibility](https://make.wordpress.org/accessibility/handbook/test-for-web-accessibility/) handbook page. The goal is familiarity, not mastery.
- **Connect:** Join [#accessibility](https://wordpress.slack.com/archives/C02RP4X03) on Slack and introduce yourself.

## Steps

1. Find a ticket to test from the [Tickets, Tasks, and Reports](https://make.wordpress.org/accessibility/handbook/get-involved/tickets-tasks-reports/) page — start with good first bugs or tickets with patches on [Core Trac](https://core.trac.wordpress.org/query?status=!closed&focuses=~accessibility&keywords=~good-first-bug), or [Needs Accessibility Feedback](https://github.com/WordPress/gutenberg/labels/Needs%20Accessibility%20Feedback) issues on Gutenberg. If the lists feel overwhelming, ask in #accessibility.
2. **Keyboard test.** Put your mouse aside. Use Tab/Shift+Tab to navigate, Enter/Space to activate, arrow keys inside menus. Check that you can reach every interactive element, see where focus is, operate everything without a mouse, and escape modals. See the [WebAIM Keyboard Accessibility Guide](https://webaim.org/techniques/keyboard/).
3. **Automated scan.** Open DevTools (F12), go to the axe DevTools tab, and click "Scan All of My Page." Note issues relevant to your ticket. Automated tools catch ~30% of issues — they're a starting point, not a complete test.
4. **Screen reader test** (optional, but where the team most needs help). Navigate the page with NVDA or VoiceOver and check roles, reading order, alt text, and form labels. See [WebAIM's screen reader testing guide](https://webaim.org/articles/screenreader_testing/).
5. **Report your findings.** Add a comment on the ticket with what you tested, how you tested (tools, browser, OS), and what you found. Include steps to reproduce and screenshots where possible. See the [Reporting Issues](https://make.wordpress.org/accessibility/handbook/reporting-issues/) handbook page. For new issues, file on [Core Trac](https://core.trac.wordpress.org/) (Focus: "accessibility", Type: "defect (bug)"), [Gutenberg GitHub](https://github.com/WordPress/gutenberg/issues), or [Meta Trac](https://meta.trac.wordpress.org/) depending on where the issue lives.

## Contribution checklist

- [ ] Tested against a specific ticket or issue
- [ ] Used at least one testing method (keyboard, automated scan, or screen reader)
- [ ] Report includes what you tested, how you tested, browser/OS, and what you found
- [ ] Included steps to reproduce and screenshots for any issues found
- [ ] New tickets filed with correct Focus and Type
- [ ] Report posted in the right place (Core Trac, Gutenberg GitHub, or Meta Trac)

## What happens next

Watch the ticket for responses from the team. Address any questions and verify the fix once it's applied. If you don't hear back within 2–3 weeks, post in #accessibility.

As you gain confidence, expand your testing methods and check the [Current Release Progress](https://make.wordpress.org/accessibility/current-release-progress/) page for active work. Joining accessibility bug scrubs in #accessibility is a good way to learn and find tickets. Contributing can earn you a [profile badge](https://make.wordpress.org/accessibility/handbook/get-involved/profile-badges/).

## Help

Stuck? Check the [getting help guide](/handbook/contribution-pathways/before-you-begin/#getting-help), then ask in [#accessibility](https://wordpress.slack.com/archives/C02RP4X03).
