# Maintaining Contribution Pathways

This guide covers the ongoing maintenance tasks for WordPress Contribution Pathways—keeping content current, triaging feedback, and helping new pathways get published.  If you'd like to help maintain this repository and handbook, come say hi in [#core-program](https://wordpress.slack.com/archives/core-program).

## Quick Links

- [Pathways Project Board](https://github.com/orgs/WordPress/projects/282/views/1)
- [Feedback & Update Requests](https://github.com/WordPress/contributor-handbook/issues?q=is%3Aissue%20state%3Aopen%20label%3A%22Pathways%3A%20Update%22)
- [Good First Issues Board](https://github.com/orgs/WordPress/projects/289/views/1?pane=info)

## What You'll Need

- GitHub account with write access to the [WordPress/contributor-handbook](https://github.com/WordPress/contributor-handbook/) repository
- Familiarity with JSON formatting
- Access to the project boards above
- Rarely: wp-admin access (if you don't have it, ping in our slack for help).

## Creating and Reviewing Pathways

Before a pathway reaches the publishing stage, it needs to be written and reviewed. We have guides for that!

- **[Create a Pathway Guide](https://make.wordpress.org/handbook/pathways/write/create-a-pathway-guide/)** – How to write a new pathway from scratch
- **[Review a Pathway Guide](https://make.wordpress.org/handbook/pathways/test/review-a-pathway-guide/)** – How to test and provide feedback on draft pathways

Once a pathway passes review, it's moved to the **Add to Manifest** column on the project board so it can be published.

## Publishing New Pathways

New pathways move through columns on the [project board](https://github.com/orgs/WordPress/projects/282/views/1), from ideation to published pathway. When a pathway is done, it should be in the **Add to Manifest** column. To proceed, edit [bin/handbook-manifest.json](https://github.com/WordPress/contributor-handbook/blob/main/bin/handbook-manifest.json) and add the new pathway guide there. Be sure to:

- Follow the existing format exactly
- Validate your JSON before committing (a trailing comma, extra slash, or missing quote will break things)
- Set the order to an appropriate number based on what's already listed
- Commit to a new branch (manifest-[date] is a good name)
- Merge, then wait 15-20 minutes for content to appear
- Confirm the pathway has loaded correctly, then move the card to **Done** (or close the issue)

## Triaging Feedback

Community members can request updates or flag problems via [GitHub issues labeled `Pathways: Update`](https://github.com/WordPress/contributor-handbook/issues?q=is%3Aissue%20state%3Aopen%20label%3A%22Pathways%3A%20Update%22).

When triaging:

- **Acknowledge** – A quick comment lets the reporter know it's been seen
- **Label** – Add relevant labels (e.g., specific team, complexity, or even good first issue)
- **Assess feasibility** – Some requests may require input from the relevant Make team
- **Link related issues** – If it duplicates or relates to existing work, connect them

<!-- [TODO: Expected response time? Who can close issues?] -->

## Curating Good First Issues

The [Good First Issues board](https://github.com/orgs/WordPress/projects/289/views/1?pane=info) helps new contributors find approachable tasks.

<!-- [TODO: How often should this be reviewed? What criteria make something a "good first issue"?] -->

When adding issues to this board, look for:

- Clear, well-scoped tasks
- Minimal prior context required
- Something that can be completed independently

Remove issues that have gone stale or are no longer relevant.

## Retiring or Archiving Pathways

Sometimes a pathway becomes outdated or blocked—for example, if a team is no longer active or the work described no longer exists. Here's what to do:
1. Remove the pathway from the manifest.
2. Remove the file from GitHub.
3. Remove any mentions in a manually-curated index. Commit and merge
4. Log into wp-admin and delete the handbook page.

Signs a pathway may need retirement:

- No active work in the linked area for an extended period
- Feedback indicating the pathway leads nowhere
- Team or project has been sunset

## Troubleshooting

| Problem | What to check |
|---------|---------------|
| Page didn't appear after 20 min | Ensure the JSON syntax is correct |
| Duplicate Pages | Fix any validation problems in JSON, delete excess pages through wp-admin, then wait 20 minutes to confirm manifest works correctly the next time |
| Guide steps no longer work | Please update the guide if possible, or surface the issue in the relevant team's slack |
| Still stuck | Check in with @velda on slack |

## Questions?

This project lives in a quiet channel. If you have any questions, head on over to [#core-program](https://wordpress.slack.com/archives/core-program) and we'll be happy to help.
