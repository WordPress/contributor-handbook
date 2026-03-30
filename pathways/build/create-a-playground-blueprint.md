# Build a WordPress Playground Blueprint

**Function:** Build  
**Type:** Project  
**Level:** Beginner

Build a WordPress Blueprint and submit it to the Blueprint Gallery. Blueprints are JSON files that configure a WordPress Playground instance — they can install themes, plugins, and content in a few clicks. The gallery is a public collection of community-submitted blueprints that others can learn from and reuse.

## Before you start

Complete the [common setup](/handbook/contribution-pathways/before-you-begin/) first, then:

- **Setup:** Open a few blueprints at [wordpress.github.io/blueprints](https://wordpress.github.io/blueprints/) to see how they work — tap any one to load a temporary WordPress instance. You'll also need a text editor and a web browser. Optionally, use an editor with JSON support (like VS Code) for autocomplete with the [Blueprint JSON Schema](https://playground.wordpress.net/blueprint-schema.json).
- **Read:** [Build your first blueprint](https://wordpress.github.io/wordpress-playground/blueprints/tutorial/build-your-first-blueprint/) and the [gallery contributing guidelines](https://github.com/WordPress/blueprints/blob/trunk/CONTRIBUTING.md)
- **Connect:** Join [#meta-playground](https://wordpress.slack.com/archives/C04EWKGDJ0K) and introduce yourself

## Steps

1. Work through the [Build your first blueprint](https://wordpress.github.io/wordpress-playground/blueprints/tutorial/build-your-first-blueprint/) tutorial. By the end, you'll have a working `blueprint.json` that installs a theme, plugins, and content.
2. Decide what to build. Look at the [Blueprint Gallery](https://github.com/WordPress/blueprints/blob/trunk/GALLERY.md) source files to see how others have structured their submissions. People use blueprints to:
   - Demo the capabilities of a WordPress plugin, theme, or design
   - Provide a hands-on environment for tutorials
   - Set up a test site for debugging or review
3. Build your own blueprint. Pick something you find interesting — a plugin you want to showcase, a theme setup worth sharing, a testing environment you'd find useful — and create a `blueprint.json` for it. Be as creative as you like.
4. Test your blueprint by pasting the JSON into the [Playground Builder](https://playground.wordpress.net/builder/builder.html). Make sure the site loads and works as expected.
5. Prepare your submission folder following the [contributing guidelines](https://github.com/WordPress/blueprints/blob/trunk/CONTRIBUTING.md). Your folder needs:
   - A `blueprint.json` file with the required metadata (`title` and `author`)
   - Any static files your blueprint references (WXR, ZIP, images, etc.)
   - A `screenshot.jpg` of the result (optional — one will be generated if you skip this)
6. Submit a pull request to the [WordPress/blueprints](https://github.com/WordPress/blueprints) repository with your folder under `blueprints/your-blueprint-name/`.

## Contribution checklist

- Your blueprint runs in WordPress Playground without errors
- Your `blueprint.json` includes the required metadata (`title` and `author`)
- Your submission folder contains the blueprint and all referenced files
- Your pull request is submitted to the WordPress/blueprints repository

## What happens next

A Playground team member will review your PR. They may ask for changes or flag missing files. You'll also get a test link generated from your PR to verify your blueprint works. If you don't hear back within a week, ask in [#meta-playground](https://wordpress.slack.com/archives/C04EWKGDJ0K).

After your first blueprint is merged, consider [creating a Blueprint for a community theme or plugin](/handbook/pathways/build/create-a-playground-blueprint-for-a-community-plugin-or-theme/) — or explore other ways to contribute to [WordPress Playground](https://github.com/WordPress/wordpress-playground).

## Help

Stuck? Check the [getting help guide](/handbook/contribution-pathways/before-you-begin/#getting-help), then ask in [#meta-playground](https://wordpress.slack.com/archives/C04EWKGDJ0K).

**Further reading:**
- [Create a demo with Playground](https://wordpress.tv/2025/04/30/create-a-demo-with-playground/) (27-minute video walkthrough)
- [Blueprint Steps API Reference](https://wordpress.github.io/wordpress-playground/blueprints/steps)
- [Blueprint Resources API Reference](https://wordpress.github.io/wordpress-playground/blueprints/steps/resources/)
- [The Blueprint Gallery: Share your WordPress creations with Playground](https://make.wordpress.org/meta/2024/05/15/the-blueprint-gallery-share-your-wordpress-creations-with-playground/) (background on the gallery initiative)
