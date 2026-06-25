# Build a WordPress Playground Blueprint

Playground Blueprints let anyone launch a WordPress demo in a single click, with a theme, plugins, and even content. This guide explains how to create a Blueprint and ship it to a gallery where people share their blueprints for others to use and learn from.

- **Reference:** [Build your first blueprint](https://wordpress.github.io/wordpress-playground/blueprints/tutorial/build-your-first-blueprint/) — the official tutorial
- **Connect:** Join [#playground](https://wordpress.slack.com/archives/playground) and introduce yourself

## Steps

1. **Explore existing blueprints.** Open a few at [wordpress.github.io/blueprints](https://wordpress.github.io/blueprints/) to see how they work — tap any one to load a temporary WordPress instance.

2. **Work through the tutorial.** Follow [Build your first blueprint](https://wordpress.github.io/wordpress-playground/blueprints/tutorial/build-your-first-blueprint/). By the end, you'll have a working `blueprint.json` that installs a theme, plugins, and content.

3. **Decide what to build.** Look at the [Blueprint Gallery source files](https://github.com/WordPress/blueprints/blob/trunk/GALLERY.md) to see how others have structured their submissions. Check to see what's already there, and find inspiration for what you'd like to share.

4. **Build your own blueprint.** Pick something you find interesting — a plugin you want to showcase, a theme setup worth sharing, a testing environment you'd find useful — and create a `blueprint.json` for it using the official tutorial: [Build your first blueprint](https://wordpress.github.io/wordpress-playground/blueprints/tutorial/build-your-first-blueprint/).

5. **Test your blueprint.** Paste the JSON into the [Playground Builder](https://playground.wordpress.net/builder/builder.html). Make sure the site loads and works as expected.

6. **Prepare your submission folder.** Follow the [contributing guidelines](https://github.com/WordPress/blueprints/blob/trunk/CONTRIBUTING.md). Your folder needs a `blueprint.json` with the required metadata (`title` and `author`), plus any static files your blueprint references (WXR, ZIP, images, etc.).

7. **Submit a pull request.** Add your folder under `blueprints/your-blueprint-name/` in the [WordPress/blueprints](https://github.com/WordPress/blueprints) repository.

## Contribution checklist

- Blueprint runs in WordPress Playground without errors
- `blueprint.json` includes the required metadata (`title` and `author`)
- Submission folder contains the blueprint and all referenced files
- Pull request submitted to the WordPress/blueprints repository

## What happens next

A Playground team member will review your PR. They may ask for changes or flag missing files. You'll also get a test link generated from your PR to verify your blueprint works. If you don't hear back within a week, ask in #meta-playground.

After your first blueprint is merged, consider [creating a Blueprint for a community theme or plugin](https://make.wordpress.org/handbook/pathways/build/create-a-playground-blueprint-for-a-community-plugin-or-theme/) — or explore other ways to contribute to [WordPress Playground](https://github.com/WordPress/wordpress-playground).

## Help

Stuck? Check the [getting help guide](https://make.wordpress.org/handbook/pathways/before-you-begin/#getting-help), then ask in [#playground](https://wordpress.slack.com/archives/playground).

**Further reading:**
- [Gallery contributing guidelines](https://github.com/WordPress/blueprints/blob/trunk/CONTRIBUTING.md)
- [Create a demo with Playground](https://wordpress.tv/2025/04/30/create-a-demo-with-playground/) — 27-minute video walkthrough
- [Blueprint Steps API Reference](https://wordpress.github.io/wordpress-playground/blueprints/steps)
- [Blueprint Resources API Reference](https://wordpress.github.io/wordpress-playground/blueprints/steps/resources/)
- [The Blueprint Gallery announcement](https://make.wordpress.org/meta/2024/05/15/the-blueprint-gallery-share-your-wordpress-creations-with-playground/) — background on the gallery initiative

<div class="wp-block-wporg-sidebar-container is-floating-sidebar" data-breakpoint="1300px">
  <div class="pathway-info">
    <div class="pathway-header">
      <span class="dashicons dashicons-editor-code"></span> Build
    </div>
    <div class="pathway-dtails">
      <p>Beginner-friendly project</p>
      <p class="newbies">New here? <a href="https://make.wordpress.org/handbook/pathways/before-you-begin/">Get set up</a> with accounts, community basics, and info on badges. →</p>
    </div>
  </div>
</div>
