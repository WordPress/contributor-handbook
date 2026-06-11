# Update Theme Check Plugin Documentation

Review the Theme Check plugin handbook page, identify what's outdated or missing, and draft improvements for the Themes team. The handbook page is the go-to reference for theme reviewers, and keeping it accurate helps the entire theme review process run smoothly.

- **Reference:** [Theme Check plugin handbook page](https://make.wordpress.org/themes/handbook/review/required/theme-check-plugin/)
- **Connect:** Join [#themes](https://wordpress.slack.com/archives/themes) on Slack and introduce yourself

## Steps

1. **Set up your testing environment.** Open [WordPress Playground](https://wordpress.wordpress.net/) and install the [Theme Check](https://wordpress.org/plugins/theme-check/) plugin.

2. **Familiarize yourself with the plugin.** Install a theme in Playground and run Theme Check against it. Explore what the plugin checks, what it flags, and how the results are presented.

3. **Compare the plugin to the handbook.** Read through the [Theme Check plugin handbook page](https://make.wordpress.org/themes/handbook/review/required/theme-check-plugin/) and note anything that's outdated, inaccurate, missing, or unclear. Compare what the plugin actually does against what the handbook says.

4. **Research the plugin's current state.** Review the [Theme Check GitHub repository](https://github.com/WordPress/theme-check) for recent changes, open issues, or new checks that may not be reflected in the handbook.

5. **Draft your improvements.** Write your updated version of the handbook page in a Google Doc or WordPress post. Below are some known issues to get you started, but don't limit yourself to these:
   - The page displays an "Information on this page may be out of date" warning and was last updated in November 2020
   - Broken links to the old GitHub repository (`Otto42/theme-check`) need updating to the current [WordPress/theme-check](https://github.com/WordPress/theme-check) repo
   - The page lists checks with little context about what each one does, why it matters, or what a theme author should do if they fail
   - There are no installation or usage instructions for the plugin
   - There are no screenshots or examples showing what Theme Check output looks like
   - Some sections are raw GitHub links rather than actual documentation
   - There is no mention of how checks apply to block themes vs classic themes

6. **Share your draft for review.** Post a link to your draft in #themes on Slack and ask the Themes team to review it. A team member with handbook access will apply the changes once approved.

## Contribution checklist

- Theme Check tested in Playground and compared against the handbook page
- Outdated, missing, or inaccurate content identified
- Draft improvements written up in a Google Doc or WordPress post
- Draft shared in #themes for review

## What happens next

A Themes team member will review your draft and may suggest changes or ask questions. Once approved, someone with handbook access will update the page. If there's no response after two weeks, follow up in #themes.

This page benefits from periodic review, particularly after major plugin updates or WordPress releases. If you'd like to check back in a few months, your familiarity with the page will make future reviews quicker.

## Help

Stuck? Check the [getting help guide](https://make.wordpress.org/handbook/pathways/before-you-begin/#getting-help), then ask in [#themes](https://wordpress.slack.com/archives/themes).

**Further reading:**
- [Theme Review handbook](https://make.wordpress.org/themes/handbook/review/) — how Theme Check fits into the review process
- [Theme Check plugin page](https://wordpress.org/plugins/theme-check/)
- [Theme Check GitHub repository](https://github.com/WordPress/theme-check)
- [Required theme checks](https://make.wordpress.org/themes/handbook/review/required/)

<div class="wp-block-wporg-sidebar-container is-floating-sidebar" data-breakpoint="1300px">
  <div class="pathway-info">
    <div class="pathway-header">
      <span class="dashicons dashicons-edit-page"></span> Write
    </div>
    <div class="pathway-dtails">
      <p>Beginner-friendly project</p>
      <p class="newbies">New here? <a href="https://make.wordpress.org/handbook/pathways/before-you-begin/">Get set up</a> with accounts, community basics, and info on badges. →</p>
    </div>
  </div>
</div>
