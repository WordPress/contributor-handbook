# Test WordPress Bug Reports

Test bug reports to see if you can trigger the same problem. Many reports turn out to be plugin conflicts or user mistakes, not WordPress bugs. Your testing helps developers focus on real issues.

- **Reference:** [Issue Reproduction workflow](https://make.wordpress.org/test/handbook/test-reports/issue-reproduction/)
- **Connect:** Join [#core-test](https://wordpress.slack.com/archives/core-test) and introduce yourself

## Steps

1. **Set up your Trac account.** Create a [WordPress Trac](https://core.trac.wordpress.org/) account if you don't have one — you'll need it to post test reports.

2. **Find a bug to test.** Browse [WordPress Trac](https://core.trac.wordpress.org/) for tickets tagged `needs-testing` or recent bug reports without many comments.

3. **Read the bug report.** Note the WordPress version, the steps to reproduce, and what should happen versus what actually happens.

4. **Open WordPress Playground.** Go to [playground.wordpress.net](https://playground.wordpress.net/). Click the settings icon and set the WordPress version to match the bug report if needed.

5. **Follow the reproduction steps.** Try to trigger the bug exactly as described. Test with a default theme (like Twenty Twenty-Four) and no plugins first.

6. **Post your results.** Comment on the Trac ticket with whether you could reproduce the bug, the WordPress version you tested, your browser, and any variations you tried.

## Contribution checklist

- Bug report selected from Trac
- Tested in WordPress Playground with default theme and no plugins
- Results posted on the ticket with environment details

## What happens next

Developers review test reports to confirm whether bugs are valid. Multiple confirmations help prioritize fixes. If no one can reproduce an issue, the ticket may be closed or need more information.

Once comfortable with bug testing, try [testing patches](https://make.wordpress.org/handbook/pathways/test/help-test-patches/) to validate fixes.

## Help

Stuck? Check the [getting help guide](https://make.wordpress.org/handbook/pathways/before-you-begin/#getting-help), then ask in [#core-test](https://wordpress.slack.com/archives/core-test).

**Further reading:**
- [WordPress Playground documentation](https://wordpress.github.io/wordpress-playground/)

<div class="wp-block-wporg-sidebar-container is-floating-sidebar" data-breakpoint="1300px">
  <div class="pathway-info">
    <div class="pathway-header">
      <span class="dashicons dashicons-welcome-view-site"></span> Test
    </div>
    <div class="pathway-dtails">
      <p>Beginner-friendly task</p>
      <p class="newbies">New here? <a href="https://make.wordpress.org/handbook/pathways/before-you-begin/">Get set up</a> with accounts, community basics, and info on badges. →</p>
    </div>
  </div>
</div>
