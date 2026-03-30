# Write: Document a WordPress Release

**Function:** Write  
**Type:** Team  
**Level:** Intermediate  

This pathway describes how the Documentation team prepares, publishes, and maintains documentation for a major WordPress release. Following a consistent process ensures users and developers have accurate, up-to-date information when a new version ships. This process is actively evolving and may change from release to release.

This work is tracked in the [Documentation Issue Tracker](https://github.com/WordPress/Documentation-Issue-Tracker), discussed in [#docs](https://wordpress.slack.com/archives/C02RP4WU5), and coordinated with the release squad in their dedicated Slack channel.

## Before you start

Complete the [common setup](/handbook/pathways/before-you-begin/) first, then:

- **Setup:** Set up [WordPress Playground](https://playground.wordpress.net/) to explore features, take screenshots, and verify changes. If writing directly to HelpHub, request access in #docs — otherwise, draft in a Google Doc and share the link.
- **Read:** Read through the [documentation process during a major version release](https://make.wordpress.org/docs/handbook/workflows/documentation-process-during-a-major-version-release/) — this is the team's primary reference for how release documentation works.
- **Connect:** Join [#docs](https://wordpress.slack.com/archives/C02RP4WU5) on Slack. Volunteer during a weekly Docs team meeting when the call goes out. Less experienced contributors are encouraged — you may be paired with a mentor.

## Steps

### During the release cycle

1. **Set up the project.** Create a GitHub project in the [Documentation Issue Tracker](https://github.com/WordPress/Documentation-Issue-Tracker) to track all work for the release (e.g. the [WordPress 6.9 Documentation project](https://github.com/orgs/WordPress/projects/262)). List both DevNotes and user docs.
2. **Identify what needs updating.** Review the release roadmap shared at the start of the cycle. At each stage (Roadmap → Beta 1 → RC1), the list narrows. For each item, decide whether it needs a new document or an update — if unsure, ask in #docs. Open an issue with the release-specific label and add it to the release project.
3. **Write documentation.** DevNotes are written by core committers; user docs are written by docs team members. When writing user docs, match the style of existing documentation for similar features. Always update screenshots and include a changelog at the bottom of every document. Use Playground to verify — features can change drastically during the cycle, so always test the actual release rather than relying on PRs.
4. **Review documentation.** When writing is done, change the issue status to "Needs 1st Review" under Projects. Share in #docs that work is ready. Coordinate with the release squad as needed — for progress updates, confirming what needs documenting, and flagging if help is needed.

### DevNotes and the Field Guide

- Each DevNote requires two reviews: one technical (accuracy) and one copy (grammar/spelling).
- Space DevNotes out — no more than three published on the same day.
- All DevNotes should be published before RC1.
- At RC1, compile all DevNotes into the [Field Guide](https://make.wordpress.org/core/handbook/tutorials/publishing-the-field-guide/), which is linked from the WordPress admin About page, the release announcement, and the HelpHub version page.

### Preparing for release day

5. **Create the HelpHub version page.** Duplicate the previous version's page (e.g. [Version 6.8](https://wordpress.org/documentation/wordpress-version/version-6-8/)) and update: jazz musician name (provided on release day), announcement link, db_version and Trac revision (from the release team Slack channel), ticket list link, release squad, and changelog (from the Triage Lead or Tech Lead — can be added later if needed).
6. **Schedule publication.** Schedule all completed articles for release day. Publish only after the official announcement — ideally within 30 minutes. Publish everything at once rather than staggered.

### Release day

7. **Update key pages in order.** Follow the publishing order defined in the [documentation process handbook](https://make.wordpress.org/docs/handbook/workflows/documentation-process-during-a-major-version-release/):
   1. [HelpHub Version page](https://wordpress.org/documentation/article/wordpress-versions/) (under WP Versions)
   2. [WordPress Versions page](https://wordpress.org/documentation/article/wordpress-versions/) — version link, release date, musician name, changelog, announcement, db_version, and update "Planned Versions"
   3. [Roadmap page](https://wordpress.org/about/roadmap/)
   4. [History page](https://wordpress.org/about/history/)
   5. [Origins and version history page](https://wordpress.org/documentation/article/learn-about-wordpress-and-version-history/)

### After the release

8. **Continue documentation work.** The team continues updating and writing user docs post-release. Reviews happen post-publication and issues are corrected as needed. For minor releases, only create the HelpHub version page and update the WordPress Versions page.

## Contribution checklist

- Release project created in the Documentation Issue Tracker with all items listed
- DevNotes reviewed (technical + copy) and published before RC1, Field Guide compiled at RC1
- User docs and screenshots match the current version
- HelpHub version page complete and all key pages updated on release day in the correct order

## What happens next

After the release, continue updating any remaining user docs and review published documentation for post-publication issues. Monitor the release project board and #docs for feedback.

When the next release cycle begins, the process starts again. Volunteer early to get involved.

## Help

Stuck? Check the [getting help guide](/handbook/pathways/before-you-begin/#getting-help), then ask in [#docs](https://wordpress.slack.com/archives/C02RP4WU5).

**Further reading:**
- [Releasing major versions (core handbook)](https://make.wordpress.org/core/handbook/about/release-cycle/releasing-major-versions/)
- [Publishing the Field Guide](https://make.wordpress.org/core/handbook/tutorials/publishing-the-field-guide/)
- [Documentation Grammar Guide](https://make.wordpress.org/docs/handbook/documentation-team-handbook/handbooks-grammar-guide/)
- [Style and Formatting Guide](https://make.wordpress.org/docs/handbook/documentation-team-handbook/handbooks-style-and-formatting-guide/)
- [Tone and Voice Guide](https://make.wordpress.org/docs/handbook/documentation-team-handbook/tone-and-voice-guide/)
- [External Linking Policy](https://make.wordpress.org/docs/handbook/documentation-team-handbook/external-linking-policy/)
- [Screenshot best practices](https://make.wordpress.org/docs/handbook/get-involved/onboarding-sessions/updating-and-creating-new-screenshots/)
- [Meeting notes on the Make WordPress Documentation blog](https://make.wordpress.org/docs/)
