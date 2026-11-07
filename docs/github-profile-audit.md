# GitHub profile audit

Audit date: 2026-11-07

## Executive assessment

The account contains one clearly substantial public system, several smaller original product sites and utilities, and multiple forks. The strongest hiring signal is `tuqo-market`: its repository documents a full-stack marketplace, hosted payment boundary, AI provider integration, authorization model, database migrations, CI, browser tests, and explicit verification caveats.

The main presentation problem was discoverability. The account bio only said `Builder`, the strongest project was not pinned, the profile had no engineering README, and the portfolio described the owner as a `Graphic Designer & Developer` with a `relatively short journey in coding`. This profile repository addresses those issues without changing repository history or overstating outcomes.

## Account-level findings

| Area | Verified state | Hiring impact | Action |
| --- | --- | --- | --- |
| Identity | Nick Mathenge; location shown as Dubai; website set to `mathengeinc.com` | The identity was real but positioning was too broad | Use an engineering-specific bio and link the public portfolio |
| Public repositories | 26 public repositories at audit time | Quantity obscured the strongest work | Classify work by depth; do not delete or archive history |
| Pinned work | Only `FormSG`, a fork, was pinned | The first project a reviewer saw did not demonstrate original ownership | Pin original, technically substantial work first |
| Documentation | TUQO was well documented; many smaller repositories had minimal or no README | Reviewers could not quickly understand scope or status | Improve flagship/supporting descriptions and preserve historical projects |
| Public activity | Recent work exists, but public PR/issue/review signals are limited | Collaboration is less visible than product-building | Make future open-source contributions authentic and reviewable |
| Portfolio | Existing site used outdated design/developer positioning and stale metadata | Inconsistent story weakens recruiter confidence | Update copy and project ordering |

## Repository inventory

### Flagship

| Repository | Origin | Purpose and evidence | Presentation action |
| --- | --- | --- | --- |
| [`tuqo-market`](https://github.com/nickmax/tuqo-market) | Original | AI-assisted marketplace. Verified evidence includes TanStack Start/React, PostgreSQL migrations, Supabase Auth, Whop hosted checkout and signed webhooks, Cloudflare R2, AI adapters, durable approvals, rate limits, spend controls, CI, unit tests, mobile contracts, and Playwright suites. | Keep as the primary case study; link architecture and verification documents from the profile |

### Supporting original projects

| Repository | Purpose | Hiring signal | Presentation action |
| --- | --- | --- | --- |
| [`magari360`](https://github.com/nickmax/magari360) | Car rental/dealership application | Full-stack product work with Next.js, TypeScript, Supabase, auth, and responsive UI | Keep visible with a concise README and accurate description |
| [`nickmax.github.io`](https://github.com/nickmax/nickmax.github.io) | Public portfolio site | Product presentation and deployed static web work | Use as the portfolio link; keep copy aligned with GitHub |
| [`sweeven`](https://github.com/nickmax/sweeven) | Static cafe marketing site and menu | Lightweight web delivery and content structure | Label as a client/product site, not a systems project |
| [`pvc`](https://github.com/nickmax/pvc) | Prime Variable Covers site | Client-facing web delivery | Keep as supporting historical work |
| [`cuesmithske`](https://github.com/nickmax/cuesmithske) | Pool-products storefront site | E-commerce presentation and responsive UI | Keep as supporting historical work |
| [`mathengeinc`](https://github.com/nickmax/mathengeinc) | ElimuX/Mathenge Inc site | Company/product web presence | Keep with historical-status context |
| [`mayad`](https://github.com/nickmax/mayad) | ElimuX/Mayad site | Small product/site implementation | Keep as an experiment/supporting project |
| [`animix`](https://github.com/nickmax/animix) | Animal-health business site | Client-facing frontend work | Add a concise README before featuring it |
| [`iste140`](https://github.com/nickmax/iste140) | HTML project | Historical/educational work | Leave unfeatured and document only if revisited |
| [`kiambugolf`](https://github.com/nickmax/kiambugolf) | Golf site | Historical web work | Leave unfeatured and document only if revisited |
| [`schoolportfolio`](https://github.com/nickmax/schoolportfolio) | Portfolio site | Historical frontend work | Leave unfeatured |
| [`whitewave-landing`](https://github.com/nickmax/whitewave-landing) | Landing page | Small frontend experiment | Leave unfeatured |

### Small utilities and experiments

`Password-Generator`, `Password-Validator`, `Poweroff-Scheduler`, `TicTacToe`, `TypeWriter`, and `pdf` are valid historical or learning work. They should remain preserved, but should not compete with TUQO for recruiter attention.

### Forks and contributions

`FormSG`, `apple-design-skill`, `awesome-selfhosted`, `free-programming-books`, `public-apis`, and `Flutter-Instagram-UI-Clone` are forks. They must not be presented as original systems. Their value is determined by the visible upstream contributions, which should be referenced only when commit or pull-request evidence supports it.

## Recommended pinned order

1. `tuqo-market`
2. `magari360`
3. `nickmax.github.io`
4. `sweeven`

Only four are recommended because the remaining public repositories do not currently provide comparable engineering evidence. Do not fill all six slots for appearance.

## Evidence-based gaps

- No public repository currently provides verified performance benchmarks or user-scale metrics.
- The public account shows limited visible pull-request, issue, and code-review activity compared with product commits.
- No public LinkedIn or résumé URL was available during this audit.
- TUQO documents sandbox and production caveats; those caveats should remain visible rather than being replaced with stronger unsupported claims.

## Next authentic signals

The highest-value future improvements are a small number of substantive open-source pull requests, a public technical note derived from TUQO's architecture, and measured (not estimated) reliability or performance results. These should be earned through actual work rather than generated as profile activity.
