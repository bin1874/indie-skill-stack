# Roadmap

This repository grows in small, reviewed steps.

## Phase 1: Candidate Pool

Goal: collect 40 to 60 candidate skills without adding them to the main list yet.

Rules:

- Candidates live in [data/candidates.yml](data/candidates.yml).
- Every candidate starts as `Hold`.
- A candidate is not endorsed just because it appears in the pool.
- Each candidate needs a source URL, likely category, rough use case, and initial risk guess.
- Already included skills should not stay in the candidate pool.

Exit criteria:

- 40 to 60 candidates across all six categories.
- At least 6 candidates per category.
- Obvious prompt dumps, unclear repos, and high-risk financial automation removed.
- First review pass recorded in [REVIEW_LOG.md](REVIEW_LOG.md).

## Phase 2: First Review Pass

Goal: reduce the candidate pool to a short list of likely inclusions.

Rules:

- Do not use star count as the deciding factor.
- Apply the hard gates from [CONTRIBUTING.md](CONTRIBUTING.md).
- Record `Include`, `Hold`, or `Reject` decisions in [REVIEW_LOG.md](REVIEW_LOG.md).
- Do not add a skill to [data/skills.yml](data/skills.yml) until its risk note is clear.

Exit criteria:

- Up to 20 to 30 `Include` candidates. The first release may be smaller if fewer candidates pass review.
- Every included candidate has a category, setup path, use case, inclusion reason, and risk note.
- Rejected candidates have a short reason.

## Phase 3: First Public Stack

Goal: publish the first real version of the curated stack.

Tasks:

- Move reviewed `Include` entries to [data/skills.yml](data/skills.yml).
- Update the category pages.
- Keep the public list under 30 entries.
- Add a `v0.1.0` tag or GitHub release.

Exit criteria:

- Main README explains the stack clearly.
- Category pages contain only reviewed entries.
- `data/skills.yml` and category pages are consistent.

## Phase 4: Distribution

Goal: get feedback from the right users, not vanity traffic.

Channels:

- GitHub repository announcement.
- Indie Hackers.
- Hacker News.
- X / Twitter.
- Relevant agent skill directories.

Rules:

- Lead with strict curation, not size.
- Explain how this differs from a generic awesome list.
- Record links, responses, and follow-up tasks in [DISTRIBUTION_LOG.md](DISTRIBUTION_LOG.md).

## Phase 5: Maintenance

Goal: avoid becoming an abandoned link list.

Rules:

- No quota. Add only reviewed entries.
- Avoid adding more than 5 entries per week unless maintenance capacity is clear.
- Re-check included entries at least every 3 months.
- Keep a visible `Hold` state for uncertain candidates.
- Remove or downgrade entries when setup, security, or relevance becomes unclear.
