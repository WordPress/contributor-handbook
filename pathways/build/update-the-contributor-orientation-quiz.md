# Update the Contributor Orientation Quiz

**Function:** Build  
**Type:** Project  
**Level:** Intermediate

The Contributor Orientation Tool is the interactive quiz on [make.wordpress.org/contribute](https://make.wordpress.org/contribute/) that helps newcomers find the right WordPress team based on their skills and interests. It needs updating to reflect current teams, remove retired ones, and ensure all links point to the right places. This tool is used during feature releases and WordCamp contributor days, so keeping it accurate matters.

## Before you start

Complete the [common setup](/handbook/pathways/before-you-begin/) first, then:

- **Complete:** You should be comfortable with JavaScript, React, and WordPress block development before taking this on
- **Setup:** Clone the [wporg-contributor-orientation](https://github.com/WordPress/wporg-contributor-orientation) repository and follow the README to set up a local development environment using `wp-env`
- **Read:** Review the [Make WordPress teams page](https://make.wordpress.org/) to understand which teams are currently active, and visit the [Contributor Orientation page](https://make.wordpress.org/contribute/) to see the quiz in its current state
- **Connect:** Join [#meta](https://wordpress.slack.com/archives/meta) on Slack and introduce yourself

## Steps

1. **Audit the current quiz.** Go through the [Contributor Orientation page](https://make.wordpress.org/contribute/) and take the quiz. Note which teams are listed, where the results link to, and what's outdated. Compare against the [current Make WordPress teams](https://make.wordpress.org/) and the [contribution teams list](https://make.wordpress.org/community/handbook/contributor-day/contributor-days/contribution-teams/).
2. **Identify what needs changing.** Document which teams need removing (e.g. Marketing, Sustainability), which need adding (e.g. Core AI), and which links are broken or pointing to outdated onboarding pages.
3. **Update the source code.** Work through the block plugin source in the `src` folder. Update the team data, quiz logic, and result links to reflect the current state of WordPress teams.
4. **Test your changes locally.** Run the updated quiz in your local `wp-env` environment and verify that all paths through the quiz produce accurate results with working links.
5. **Submit a pull request.** Open a PR against the [wporg-contributor-orientation](https://github.com/WordPress/wporg-contributor-orientation) repo. Describe what you changed and why, and include screenshots of the updated quiz in action.

## Contribution checklist

- Current quiz audited and outdated content documented
- Retired teams removed and new teams added in the source code
- All result links verified as pointing to current onboarding pages
- PR submitted with clear description and screenshots

## What happens next

A maintainer will review your PR and may request changes. If there's no response after two weeks, follow up in #meta. Once merged, the updated quiz will go live on make.wordpress.org/contribute and help newcomers find their team more accurately.

## Help

Stuck? Check the [getting help guide](/handbook/pathways/before-you-begin/#getting-help), then ask in [#meta](https://wordpress.slack.com/archives/meta).

**Further reading:**
- [Contributor Orientation Tool GitHub repository](https://github.com/WordPress/wporg-contributor-orientation)
- [Make WordPress teams page](https://make.wordpress.org/)
- [Contribution teams list](https://make.wordpress.org/community/handbook/contributor-day/contributor-days/contribution-teams/)
- [Contributor Orientation page](https://make.wordpress.org/contribute/)
