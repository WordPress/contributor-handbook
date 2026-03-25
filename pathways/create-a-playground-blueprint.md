# Build: Create a Playground Blueprint for a community theme or plugin

**Function:** Build  
**Type:** Project

Help theme and plugin maintainers get started faster by creating a Playground Blueprint for their project. A Blueprint is a JSON file that spins up a ready-to-go WordPress instance with the right extensions and content pre-loaded — great for demos, testing, and reviewing PRs.

## Before you start

Complete the [common setup](/handbook/contribution-pathways/before-you-begin/)) first, then:

- **Setup:** Familiarize yourself with [WordPress Playground](https://wordpress.github.io/wordpress-playground/) — try spinning up a site to see how it works
- **Read:** The [Blueprint tutorial](https://wordpress.github.io/wordpress-playground/blueprints/tutorial/build-your-first-blueprint/). Keep the [Blueprint API reference](https://wordpress.github.io/wordpress-playground/blueprints/steps/) handy for when you're building.
- **Connect:** Join [#playground](https://wordpress.slack.com/archives/C04EWKGDJ0K) and introduce yourself

## Steps

1. **Pick a plugin or theme:** Choose a WordPress.org community-maintained [theme](https://profiles.wordpress.org/wordpressdotorg/#content-themes) or [plugin](https://profiles.wordpress.org/wordpressdotorg/#content-plugins) that doesn't have a Blueprint yet.
2. **Learn the basics:** Follow the [Blueprint tutorial](https://wordpress.github.io/wordpress-playground/blueprints/tutorial/build-your-first-blueprint/) to understand how `blueprint.json` works.
3. **Draft the Blueprint:** Write a `blueprint.json` that installs the extension, adds any useful demo content, and configures the site so someone can see it working immediately.
4. **Test it:** Run your Blueprint in Playground. Try different PHP versions. Does everything install? Does the demo content make sense?
5. **Submit:** Open a PR in the plugin or theme's repository with your Blueprint and a brief explanation of what it does and why it's useful. It may also help to ping the team's channel.

## Contribution checklist

- [ ] The `blueprint.json` is clean, readable, and uses the [shorthand syntax](https://wordpress.github.io/wordpress-playground/blueprints/tutorial/build-your-first-blueprint/#shorthands) where appropriate
- [ ] Your PR explains what the Blueprint does and why
- [ ] Added demo content is useful and makes the blueprint's value obvious
- [ ] Your Blueprint installs cleanly in Playground without errors, and you've tested it in at least two PHP versions

## What happens next

The plugin or theme maintainer will review your PR. Once merged, anyone can spin up a working demo with one click. If the maintainers are unfamiliar with Blueprints, your PR description may need to explain what Playground is and how it helps. If you haven't heard back in a week or so, try reaching out in the team's Slack channel.

Then if you want to keep going, pick another project or help improve the Blueprint tooling in the [Playground repository](https://github.com/WordPress/wordpress-playground).

## Help

Stuck? Check the [getting help guide](/handbook/contribution-pathways/before-you-begin/#getting-help), then ask in [#playground](https://wordpress.slack.com/archives/C04EWKGDJ0K).
