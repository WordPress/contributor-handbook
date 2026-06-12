# Create a Community Blueprint

Help theme and plugin contributors get started faster by creating a Playground Blueprint for their project. A Blueprint is a JSON file that spins up a ready-to-go WordPress instance with the right extensions and content pre-loaded — useful for demos, testing, and reviewing PRs.

- **Prerequisite:** [Build a Blueprint for the Gallery](https://make.wordpress.org/handbook/pathways/build/create-a-playground-blueprint/) — learn Blueprint basics first
- **Reference:** [Blueprint Steps API Reference](https://wordpress.github.io/wordpress-playground/blueprints/steps/) — keep this handy while building
- **Connect:** Join [#playground](https://wordpress.slack.com/archives/playground) and introduce yourself

## Steps

1. **Pick a project.** Find a WordPress.org community-maintained [theme](https://profiles.wordpress.org/wordpressdotorg/#content-themes) or [plugin](https://profiles.wordpress.org/wordpressdotorg/#content-plugins) that doesn't have a Blueprint yet.

2. **Coordinate with the team.** Check the project's repository for an existing issue requesting a Blueprint, or open one. Reach out in the team's Slack channel to let them know you'd like to contribute one.

3. **Draft your Blueprint.** Create a `blueprint.json` that installs the extension, adds useful demo content, and configures the site so someone can see it working immediately.

4. **Test your Blueprint.** Run it in Playground. Try different PHP versions. Does everything install? Does the demo content make sense?

5. **Open a pull request.** Submit your Blueprint to the plugin or theme's repository with a brief explanation of what it does and why it's useful.

## Contribution checklist

- `blueprint.json` is clean, readable, and uses [shorthand syntax](https://wordpress.github.io/wordpress-playground/blueprints/tutorial/build-your-first-blueprint/#shorthands) where appropriate
- PR explains what the Blueprint does and why
- Demo content is useful and makes the Blueprint's value obvious
- Blueprint installs cleanly in Playground, tested in at least two PHP versions

## What happens next

The plugin or theme maintainer will review your PR. If they're unfamiliar with Blueprints, your PR description may need to explain what Playground is and how it helps. If you haven't heard back in a week or so, try reaching out in the team's Slack channel again.

Once merged, anyone can spin up a working demo with one click. Then pick another project, or help improve the Blueprint tooling in the [Playground repository](https://github.com/WordPress/wordpress-playground).

## Help

Stuck? Check the [getting help guide](https://make.wordpress.org/handbook/pathways/before-you-begin/#getting-help), then ask in [#playground](https://wordpress.slack.com/archives/playground).

**Further reading:**
- [Build your first blueprint](https://wordpress.github.io/wordpress-playground/blueprints/tutorial/build-your-first-blueprint/) — refresher on the basics
- [Blueprint Resources API Reference](https://wordpress.github.io/wordpress-playground/blueprints/steps/resources/)
- [Create a demo with Playground](https://wordpress.tv/2025/04/30/create-a-demo-with-playground/) — 27-minute video walkthrough

<div class="wp-block-wporg-sidebar-container is-floating-sidebar" data-breakpoint="1300px">
  <div class="pathway-info">
    <div class="pathway-header">
      <span class="dashicons dashicons-editor-code"></span> Build
    </div>
    <div class="pathway-dtails">
      <p>Intermediate project</p>
      <p class="newbies">New here? <a href="https://make.wordpress.org/handbook/pathways/before-you-begin/">Get set up</a> with accounts, community basics, and info on badges. →</p>
    </div>
  </div>
</div>
