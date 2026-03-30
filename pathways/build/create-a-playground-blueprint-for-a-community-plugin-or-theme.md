# Create a Playground Blueprint for a Community Plugin or Theme

**Function:** Build
**Type:** Project
**Level:** Intermediate

Help theme and plugin contributors get started faster by creating a Playground Blueprint for their project. A Blueprint is a JSON file that spins up a ready-to-go WordPress instance with the right extensions and content pre-loaded — useful for demos, testing, and reviewing PRs.

## Before you start

Complete the [common setup](/handbook/contribution-pathways/before-you-begin/) first, then:

- **Complete:** [Build a Blueprint for the Gallery](/handbook/pathways/build/create-a-playground-blueprint/)
- **Setup:** You need a text editor and a web browser
- **Read:** [Blueprint Steps API Reference](https://wordpress.github.io/wordpress-playground/blueprints/steps/) — keep this handy while building
- **Connect:** Join [#playground](https://wordpress.slack.com/archives/C04EWKGDJ0K) and introduce yourself

## Steps

1. Pick a WordPress.org community-maintained [theme](https://profiles.wordpress.org/wordpressdotorg/#content-themes) or [plugin](https://profiles.wordpress.org/wordpressdotorg/#content-plugins) that doesn't have a Blueprint yet.
2. Check the project's repository for an existing issue requesting a Blueprint, or open one. Reach out in the team's Slack channel to let them know you'd like to contribute one.
3. Draft a `blueprint.json` that installs the extension, adds useful demo content, and configures the site so someone can see it working immediately.
4. Test your Blueprint in Playground. Try different PHP versions. Does everything install? Does the demo content make sense?
5. Open a PR in the plugin or theme's repository with your Blueprint and a brief explanation of what it does and why it's useful.

## Contribution checklist

- Your `blueprint.json` is clean, readable, and uses [shorthand syntax](https://wordpress.github.io/wordpress-playground/blueprints/tutorial/build-your-first-blueprint/#shorthands) where appropriate
- Your PR explains what the Blueprint does and why
- Demo content is useful and makes the Blueprint's value obvious
- The Blueprint installs cleanly in Playground without errors, tested in at least two PHP versions

## What happens next

The plugin or theme maintainer will review your PR. If they're unfamiliar with Blueprints, your PR description may need to explain what Playground is and how it helps. If you haven't heard back in a week or so, try reaching out in the team's Slack channel again.

Once merged, anyone can spin up a working demo with one click. Then pick another project, or help improve the Blueprint tooling in the [Playground repository](https://github.com/WordPress/wordpress-playground).

## Help

Stuck? Check the [getting help guide](/handbook/contribution-pathways/before-you-begin/#getting-help), then ask in [#playground](https://wordpress.slack.com/archives/C04EWKGDJ0K).

**Further reading:**
- [Build your first blueprint](https://wordpress.github.io/wordpress-playground/blueprints/tutorial/build-your-first-blueprint/) (refresher on the basics)
- [Blueprint Resources API Reference](https://wordpress.github.io/wordpress-playground/blueprints/steps/resources/)
- [Create a demo with Playground](https://wordpress.tv/2025/04/30/create-a-demo-with-playground/) (27-minute video walkthrough)
