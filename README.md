# LinkedIn Recruiter Comment Automation

This repository packages a public-safe workflow for finding recruiter-adjacent LinkedIn posts and drafting short manual comments for them.

The focus is public-sector recruiting lanes such as state, city, county, gov tech, government contractors, and adjacent hiring conversations where automation, analytics, delivery, and AI implementation come up regularly.

## What It Does

- defines a safe manual comment workflow
- documents review constraints for account safety
- provides a reusable daily prompt contract
- includes lightweight templates for a daily comment queue
- includes a short comment bank for human-sounding replies

## Repo Layout

- `LINKEDIN_COMMENT_CONTRACT.md` - safety and quality rules for manual LinkedIn comments
- `DAILY_LINKEDIN_COMMENT_WORKFLOW.md` - daily process for finding, reviewing, and drafting comments
- `templates/linkedin_comment_queue_template.csv` - tracking template for candidate posts
- `templates/one_sentence_comment_bank.md` - short comment starters
- `PUBLIC_REPO_SCOPE.md` - what is intentionally included and excluded

## Usage

1. Collect a small set of candidate LinkedIn posts manually.
2. Score them for relevance, audience fit, and safety.
3. Draft short comments that sound human and specific to the post.
4. Review manually before posting.

## Non-Goals

- auto-posting to LinkedIn
- scraping LinkedIn at scale
- bulk commenting or mass engagement
- pretending a comment is human when it has not been reviewed by a human

## License

MIT
