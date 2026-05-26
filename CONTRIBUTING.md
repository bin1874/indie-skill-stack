# Contributing

Thanks for suggesting a skill.

This repository is intentionally selective. It is better for a good skill to wait in `Hold` than for the main list to become a link dump.

## Before You Submit

Ask:

- Does this help an indie builder validate, ship, launch, operate, or improve a real product?
- Can a user understand when to use it in 5 minutes?
- Is there a clear install, copy, or setup path?
- Are data, credential, shell, network, and file-access risks explained?
- Is it meaningfully different from skills already listed?

## Include Criteria

A skill should satisfy at least 6 of these 8 criteria:

- Clear `SKILL.md` or equivalent instruction file.
- Direct install, copy, or setup path.
- Clear use case, not just a generic prompt.
- Supports a real product workflow.
- Does not require sensitive data by default.
- Explains any high permissions, shell access, network calls, API keys, or credentials.
- Maintained recently, or stable enough that frequent maintenance is not required.
- Documentation lets a user start within 5 minutes.

The first four criteria are hard gates. The safety gate below is also mandatory.

## Safety Gate

A skill must not require sensitive data by default, and it must explain any high permissions, shell access, network calls, API keys, credentials, file writes, production access, or third-party account control.

High-risk access is acceptable only when all of these are true:

- the permission is the minimum needed for the workflow;
- the sensitive step is optional or clearly separated;
- the data flow is explained in plain language;
- the user can review the setup before any action runs;
- the risk note is marked `High`.

If this cannot be explained clearly, use `Reject`.

## Reject Criteria

We reject:

- Bulk-generated skill packs.
- Prompt dumps with no usage boundary.
- Skills with no README or unclear setup path.
- Crypto, wallet, trading automation, or high-risk financial decision skills.
- Skills that request customer data, credentials, private financials, or production access without minimum-permission setup, clear data flow, and an explicit high-risk warning.
- API wrappers that do not support a real workflow.
- Skills included only because they have many stars.
- Duplicate skills without distinct value.

## Entry Format

Use [templates/skill-entry.md](templates/skill-entry.md).

Every entry needs:

- Name.
- Repo or official page.
- Supported tools.
- Category.
- Use when.
- Best for.
- Install or setup.
- Why included.
- Risk note.
- Review status.
- Last reviewed date.

## Pull Request Checklist

Use [templates/review-checklist.md](templates/review-checklist.md) before opening a PR.

If you are unsure, open an issue first and mark the suggestion as `Hold`.

## Candidate Workflow

Do not add a new skill directly to `data/skills.yml` or a category page unless it has passed review.

Use this path:

1. Add the skill to `data/candidates.yml` with `status: Hold`.
2. Review it with `templates/review-checklist.md`.
3. Record the decision in `REVIEW_LOG.md`.
4. Move it to `data/skills.yml` and the matching category page only if the verdict is `Include`.
