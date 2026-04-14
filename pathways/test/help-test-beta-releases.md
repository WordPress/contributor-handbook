## Test Beta Releases
**Function:** Test  
**Type:** Task  
**Level:** Beginner

You will test a pre-release version of WordPress (beta or RC) to find bugs and usability issues before the final release. Your test reports help make each WordPress release stable and reliable.

## Before you start

Complete the [common setup](/handbook/contribution-pathways/before-you-begin/) first, then:

- **Connect:** Join the [Core Test Slack channel](https://wordpress.slack.com/archives/core-test) and introduce yourself
- **Setup:** Have a WordPress site available for testing — [WordPress Playground](https://playground.wordpress.net/) works and requires no installation
-**Read:** [Test Reports](https://make.wordpress.org/test/handbook/test-reports/) — how to write and format your findings
- **Connect:** Join [#core-editor](https://wordpress.slack.com/messages/core-editor) on Slack and introduce yourself

## Steps

1. Find the current beta or release candidate announcement. 
2. Go to the [Releases category](https://wordpress.org/news/category/releases/) and look for the most recent post tagged Beta or RC.
3. Set up a test environment

Pick one of these methods from the announcement post:

- **WordPress Playground:** Click the link. No setup required.
- **Beta Tester plugin:** Install and activate the plugin. Select “Bleeding edge” channel and “Beta/RC Only” stream.
- **Direct download:** Download the zip and install on a test WordPress site.
- **WP-CLI:** Run `wp core update --version=7.0-beta2` (replace with the current version number).

**Do not** test on a **production** or **mission-critical** website.

4. Read the “what to test” guide
Each release announcement links to a guide on what to test. Find it in the “How to test this release” section.

5. Test features and the upgrade process
Follow the “what to test” guide. Pay attention to new features (like the Connectors UI in 7.0 Beta 2) and core functionality.

6. Document what you find
Use the Test Reports guide to structure your findings. Include:

- Environment (OS, browser, WordPress version, active plugins)
- Steps to reproduce
- Expected behavior
- Actual behavior (✅ for expected, ❌ for unexpected)
- Screenshots or logs if helpful

7. Report bugs

Pick one reporting method:
- **Alpha/Beta support forums:** Use this if you are unsure about writing a Trac ticket.
- **WordPress Trac:** Use this if you can write a reproducible bug report. Include all documentation from step 5.

Before reporting, search for existing tickets to avoid duplicates.

## Contribution checklist

- A test environment is set up with the beta/RC version
- You have tested at least one feature or the upgrade process
- You have documented your results
- You have reported any bugs you found (or confirmed no new bugs)

## What happens next

Your bug report will be reviewed by a WordPress contributor. They may ask for more information. If you reported to Trac, watch the ticket for updates. If you used the forums, check for replies.

Once you have completed testing for one release PR, look for another PR and repeat the process. 

## Help

Stuck? Check the getting help guide, then ask in [#core-test](https://wordpress.slack.com/archives/core-test) on slack.

**Further reading:**
- [WordPress Trac](https://core.trac.wordpress.org/newticket) – new ticket
