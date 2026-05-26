# Review Log

This file records why skills are included, held, or rejected.

## 2026-05-26

### Before You Build Skill

```text
Verdict: Include
Category: Idea & Validation
Source: https://github.com/bin1874/before-you-build-skill
Install checked: openclaw skills install before-you-build
Checked criteria: clear instructions, direct install, clear use case, real workflow fit, no sensitive data by default, documented optional API.
Risk checked: text-only by default; optional Case Memory API requires user permission.
Reason: Helps indie builders review product and feature risk before asking an agent to write code.
Risk note: Low. Text-only by default. No API key required for normal use.
Decision owner: maintainer
Last reviewed: 2026-05-26
Reviewer: maintainer
```

### Repository Process

```text
Verdict: Hold candidate pool open
Reason: The public stack should not grow until 40 to 60 candidates have been collected and reviewed.
Risk note: Process risk is list bloat. Keep candidates separate from included skills.
Decision owner: maintainer
Last reviewed: 2026-05-26
Reviewer: maintainer
```

### Product Hunt Launch

```text
Verdict: Reject
Category: Launch & Growth
Source: https://clawhub.ai/abakermi/product-hunt-launch
Reason: Useful launch monitoring use case, but not suitable for the first strict stack because the reviewed listing depends on Product Hunt API token setup and unclear external CLI behavior.
Risk note: High. Requires credentials/network behavior that needs clearer setup and source verification before reconsideration.
Decision owner: review agent + maintainer
Last reviewed: 2026-05-26
Reviewer: independent review agent
```

### Weekly Goal Review Skill

```text
Verdict: Reject
Category: Founder Workflow
Source: https://clawhub.ai/abdullah944/weekly-goal-review-skill
Reason: Source page could not be verified reliably during review. Unverifiable sources cannot stay in the active candidate pool.
Risk note: Unknown until source is accessible.
Decision owner: review agent + maintainer
Last reviewed: 2026-05-26
Reviewer: independent review agent
```

### Awesome Frontend Agent Skills

```text
Verdict: Move to source list
Source: https://github.com/finfin/awesome-frontend-skills
Reason: This is a directory of skills, not an individual skill. It may be useful for research but should not be treated as a candidate.
Risk note: Review individual skills from the source before adding them as candidates.
Decision owner: review agent + maintainer
Last reviewed: 2026-05-26
Reviewer: independent review agent
```

### ClawHub Skill Vetting

```text
Verdict: Move to source list
Source: https://github.com/hugomrtz/skill-vetting-clawhub
Reason: This is a possible maintainer tool for reviewing skills, not a direct indie-builder workflow skill.
Risk note: Medium. Review separately before using it as part of the maintainer workflow.
Decision owner: review agent + maintainer
Last reviewed: 2026-05-26
Reviewer: independent review agent
```
