# Indie Skill Stack

Curated, hand-reviewed AI agent skills for indie builders.

No bulk lists. No prompt dumps. This project reviews skills for practical signal before they reach the public stack.

## What This Is

`Indie Skill Stack` is a strict collection of AI agent skills for indie hackers, solo founders, micro-SaaS builders, and small product teams.

It is not trying to be the biggest list. It is trying to be useful.

Each included skill should answer:

- When should an indie builder use this?
- What real workflow does it support?
- How do you install or copy it?
- What risk should users understand before using it?

## What This Is Not

- Not a generic awesome list.
- Not ranked by GitHub stars.
- Not a dump of generated prompts.
- Not tied to one agent platform.
- Not a place for skills with unclear permissions, credentials, or data access.

## Categories

| Category | Use when |
|---|---|
| [Idea & Validation](categories/idea-validation.md) | You need to check if a product, feature, or market bet is worth building. |
| [Product Building](categories/product-building.md) | You need to turn a validated idea into scope, requirements, interfaces, or architecture. |
| [Coding & QA](categories/coding-qa.md) | You need to review code, generate tests, fix CI, or reduce implementation risk. |
| [Launch & Growth](categories/launch-growth.md) | You need to prepare launch copy, SEO, community posts, or early distribution. |
| [Operations](categories/operations.md) | You need to handle feedback, changelogs, support, analytics, or retention loops. |
| [Founder Workflow](categories/founder-workflow.md) | You need to make decisions, review progress, maintain notes, or manage the founder loop. |

## Starter Stack For Indie Builders

This repository will stay small. The first public version should include only 20 to 30 reviewed skills.

The starter stack should cover:

1. Idea risk review.
2. Requirements and scope.
3. UX or landing page review.
4. Code review and tests.
5. Launch and distribution copy.
6. Feedback, changelog, and analytics review.

## Inclusion Standard

Default answer is no.

A skill must be useful in a real indie-builder workflow, not just interesting as a demo. See [CONTRIBUTING.md](CONTRIBUTING.md) and [templates/review-checklist.md](templates/review-checklist.md).

## Review Workflow

New suggestions start in [data/candidates.yml](data/candidates.yml), not in the public category pages.

Decisions are recorded in [REVIEW_LOG.md](REVIEW_LOG.md):

- `Include`: reviewed and ready for the public stack.
- `Hold`: promising, but not clear enough yet.
- `Reject`: not a fit for this repository.

See [ROADMAP.md](ROADMAP.md) for the current implementation plan.

## Data

The structured index lives in [data/skills.yml](data/skills.yml).

Candidates live in [data/candidates.yml](data/candidates.yml). A candidate is not endorsed until it moves into `data/skills.yml` and the matching category page.

Research sources and maintainer-tool candidates live in [data/sources.yml](data/sources.yml). Source directories are not public-stack entries.

Category pages are written for humans. The YAML file is a simple index with the same fields described in [templates/skill-entry.md](templates/skill-entry.md).

## License

MIT. See [LICENSE](LICENSE).
