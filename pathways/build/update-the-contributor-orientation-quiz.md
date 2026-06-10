# Update the Contributor Orientation Quiz

The Contributor Orientation Tool is the interactive quiz on [make.wordpress.org/contribute](https://make.wordpress.org/contribute/) that helps newcomers find the right WordPress team based on their skills and interests. It needs updating to reflect current teams, remove retired ones, and ensure all links point to the right places. This tool is used during feature releases and WordCamp contributor days, so keeping it accurate matters.

- **Prerequisite:** Comfortable with JavaScript, React, and WordPress block development
- **Reference:** [wporg-contributor-orientation repository](https://github.com/WordPress/wporg-contributor-orientation)
- **Connect:** Join [#meta](https://wordpress.slack.com/archives/meta) on Slack and introduce yourself

## Steps

1. **Set up your local environment.** Clone the [wporg-contributor-orientation](https://github.com/WordPress/wporg-contributor-orientation) repository and follow the README to set up a local development environment using `wp-env`.

2. **Audit the current quiz.** Go through the [Contributor Orientation page](https://make.wordpress.org/contribute/) and take the quiz. Note which teams are listed, where the results link to, and what's outdated. Compare against the [current Make WordPress teams](https://make.wordpress.org/) and the [contribution teams list](https://make.wordpress.org/community/handbook/contributor-day/contributor-days/contribution-teams/).

3. **Identify what needs changing.** Document which teams need removing (e.g. Marketing, Sustainability), which need adding (e.g. Core AI), and which links are broken or pointing to outdated onboarding pages.

4. **Update the source code.** Work through the block plugin source in the `src` folder. Update the team data, quiz logic, and result links to reflect the current state of WordPress teams.

5. **Test your changes locally.** Run the updated quiz in your local `wp-env` environment and verify that all paths through the quiz produce accurate results with working links.

6. **Submit a pull request.** Open a PR against the repository. Describe what you changed and why, and include screenshots of the updated quiz in action.

## Contribution checklist

- Current quiz audited and outdated content documented
- Retired teams removed and new teams added in the source code
- All result links verified as pointing to current onboarding pages
- PR submitted with clear description and screenshots

## What happens next

A maintainer will review your PR and may request changes. If there's no response after two weeks, follow up in #meta. Once merged, the updated quiz will go live on make.wordpress.org/contribute and help newcomers find their team more accurately.

## Help

Stuck? Check the [getting help guide](https://make.wordpress.org/handbook/pathways/before-you-begin/#getting-help), then ask in [#meta](https://wordpress.slack.com/archives/meta).

**Further reading:**
- [Make WordPress teams page](https://make.wordpress.org/)
- [Contribution teams list](https://make.wordpress.org/community/handbook/contributor-day/contributor-days/contribution-teams/)
- [Contributor Orientation page](https://make.wordpress.org/contribute/)

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
