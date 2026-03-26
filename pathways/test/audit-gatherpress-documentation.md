# Write: Audit GatherPress Documentation

**Function:** Test  
**Type:** Task

GatherPress is a community-powered event management plugin for WordPress that is under active development. You'll audit sections of its documentation against the actual plugin, identify gaps or inaccuracies, and file issues on GitHub. Every gap you find helps make the plugin easier for new users and developers to adopt.

No coding experience is required. If you can read documentation, test a plugin, and write a clear issue report, you can do this.

## Before you start

Complete the [common setup](/handbook/contribution-pathways/before-you-begin/) first, then:

- **Setup:** Open the [GatherPress Playground Environment](https://playground.wordpress.net/?blueprint-url=https://raw.githubusercontent.com/GatherPress/gatherpress/main/.wordpress-org/blueprints/blueprint.json) to explore the plugin with demo data — no local setup required.
- **Read:** [What is GatherPress?](https://gatherpress.org/what-is-gatherpress/), [user documentation](https://gatherpress.org/documentation/documentation-for-users/), [developer documentation](https://gatherpress.org/documentation/documentation-for-developers/), [GitHub /docs folder](https://github.com/GatherPress/gatherpress/tree/main/docs), and the [Contributor Guide](https://github.com/GatherPress/gatherpress/blob/main/docs/contributing.md).
- **Connect:** Join [#gatherpress](https://wordpress.slack.com/archives/C07NB4N0ESJ) on Slack and introduce yourself. You can also connect via [GatherPress.org Get Involved](https://gatherpress.org/get-involved/).

## Steps

1. **Get familiar with the plugin.** Read [What is GatherPress?](https://gatherpress.org/what-is-gatherpress/), skim the [user documentation table of contents](https://gatherpress.org/documentation/documentation-for-users/), then open the [Playground Environment](https://playground.wordpress.net/?blueprint-url=https://raw.githubusercontent.com/GatherPress/gatherpress/main/.wordpress-org/blueprints/blueprint.json) and click around — create an event, set up a venue, try the RSVP system.
2. **Pick a section to audit.** Good starting points: Getting started, Creating and managing events, Blocks, RSVP system, or the GitHub [installation](https://github.com/GatherPress/gatherpress/blob/main/docs/installation.md) / [configuration](https://github.com/GatherPress/gatherpress/blob/main/docs/configuration.md) guides. Not sure where to start? Ask in #gatherpress.
3. **Audit against the live plugin.** Work through your chosen section, comparing what the documentation says to what the plugin actually does. Check accuracy, completeness, clarity, screenshots, links, and consistency between [GatherPress.org](https://gatherpress.org/documentation/) and the [GitHub /docs folder](https://github.com/GatherPress/gatherpress/tree/main/docs).
4. **File one issue per problem** on the [GatherPress GitHub repository](https://github.com/GatherPress/gatherpress/issues/new). Use a clear title (e.g. `Docs: Getting started page missing timezone setting step`), include the documentation URL, describe the problem, and note the GatherPress version you tested against. If you're unsure whether something is a real gap, file it anyway and note your uncertainty.

## Contribution checklist

- [ ] Explored GatherPress in Playground to build familiarity
- [ ] Checked both GatherPress.org and the GitHub /docs folder for your section
- [ ] Verified screenshots, links, and steps against the current plugin version
- [ ] Filed one issue per problem with a clear title, URL, and version tested
- [ ] Shared what you filed in #gatherpress for team visibility

## What happens next

Watch your GitHub issues for responses or questions from the team. Follow up promptly if a maintainer asks for clarification. Once an issue is resolved, verify the fix and close it if it looks good.

After your first audit, there are always more sections to review. Check [open issues](https://github.com/GatherPress/gatherpress/issues) for existing documentation issues you could help with, or follow [GatherPress releases](https://github.com/GatherPress/gatherpress/releases) to see what's changed and whether the docs have kept up.

## Help

Stuck? Check the [getting help guide](/handbook/contribution-pathways/before-you-begin/#getting-help), then ask in [#gatherpress](https://wordpress.slack.com/archives/C07NB4N0ESJ).
