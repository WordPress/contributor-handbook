# Review Themes for Accessibility-Ready Tag

<div class="pathway-card">
  <div class="pathway-header">
    <span class="dashicons dashicons-welcome-view-site"></span> Test</div>
  <div class="pathway-details">
    <div>Intermediate task</div></div>
</div>

<div class="pathway-card">
  <div class="pathway-header">
    <span class="dashicons dashicons-lightbulb"></span> New here?</div>
  <div class="pathway-details">Get your <a href="https://make.wordpress.org/handbook/pathways/before-you-begin/">WordPress.org account, Slack access, and community introductions</a> sorted first. You'll also learn best practices, how to find help, and how to earn contributor badges.</div>
</div>

Review a WordPress theme against the accessibility-ready requirements and report what you find. Your review helps a theme earn the accessibility-ready tag, which tells users it works with keyboards, screen readers, and other assistive technology.

- **Prerequisite:** [Test for Accessibility](https://make.wordpress.org/handbook/pathways/test/test-for-accessibility/), which covers the keyboard and screen reader testing you'll use here
- **Reference:** The [accessibility-ready testing process](https://wpaccessibility.org/docs/testing/testing-themes/)
- **Connect:** Join [#accessibility](https://wordpress.slack.com/archives/accessibility) on Slack and introduce yourself

## Steps

1. **Find a theme to review.** New themes that requested the tag are in the [Themes Trac accessibility-ready queue](https://themes.trac.wordpress.org/query?status=!closed&status=!approved&keywords=~accessibility-ready&report=9&order=priority). Already-published themes are listed in the [review request spreadsheet](https://docs.google.com/spreadsheets/d/1AGJ4R13Y3VfnhT_qkvRyGd6DwpzZaGC0KZwqwD472fc/edit). See [Identifying themes](https://wpaccessibility.org/docs/testing/testing-themes/identifying-themes/).

2. **Claim it.** For a new theme, comment on its Trac ticket that you're reviewing it for accessibility. For a published theme, set its status to "Reviewing" in the spreadsheet and add your WordPress.org username. This stops two people testing the same theme.

3. **Set up a test site.** Launch the [accessibility-ready InstaWP template site](https://app.instawp.io/launch?s=wp-accessibility-ready-test-sites&d=v2), then install, activate, and configure the theme with the demo content. Playground does not work for these reviews. Full instructions are in [Getting set up to test](https://wpaccessibility.org/docs/testing/testing-themes/setup/).

4. **Copy the report template.** Make your own copy of the Google Sheet report from the [Theme Testing Reports folder](https://drive.google.com/drive/folders/1z3v3U02W1WFt38Kvzb4aaVVkqzUq9pnP?usp=sharing) and fill in the Summary tab before you start.

5. **Test against the requirements.** Work through the [accessibility-ready guidelines](https://wpaccessibility.org/docs/topics/theme-guidelines/), which include a testing note for each one. Check the theme with your keyboard, a screen reader, and an automated scanner, recording each result in your report. The [keyboard](https://wpaccessibility.org/docs/testing/keyboard/) and [screen reader](https://wpaccessibility.org/docs/testing/screen-readers/) guides show how.

6. **Share your report.** Post your completed report on the theme's Trac ticket and tag the developer so they can address what you found. If you get stuck at any point, ask in [#accessibility](https://wordpress.slack.com/archives/accessibility).

## Contribution checklist

- Claimed the theme on its Trac ticket or in the review spreadsheet before starting
- Tested with keyboard, screen reader, and an automated scanner against the accessibility-ready guidelines
- Recorded every result in your own copy of the report template
- Posted the completed report on the theme's Trac ticket and tagged the developer

## What happens next

Your report goes to the theme developer and the Themes Team on the Trac ticket. The developer addresses the issues you flag, and the theme can be approved for the accessibility-ready tag once it meets every requirement. You may be asked to re-test after changes. If the ticket goes quiet, post in [#accessibility](https://wordpress.slack.com/archives/accessibility).

Once you've finished a review, pick up another theme from the queue, or join an accessibility bug scrub in [#accessibility](https://wordpress.slack.com/archives/accessibility) to test alongside the team.

## Further reading

- [WP accessibility-ready guidelines](https://wpaccessibility.org/docs/topics/theme-guidelines/) — the full requirements, with testing notes for each
- [Testing workflow tips](https://wpaccessibility.org/docs/testing/testing-themes/theme-testing-workflow/) — practical advice for working through a review
- [Reporting sheet overview](https://wpaccessibility.org/docs/testing/testing-themes/reporting-sheet/) — how the report template is organized
- [Theme developer handbook: Accessibility](https://make.wordpress.org/themes/handbook/review/accessibility/) — the same requirements from the theme review side
