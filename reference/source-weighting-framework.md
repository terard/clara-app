# Source Weighting Framework

## Purpose

Use this framework to decide which public signals deserve trust during ops-tooling competitive research.

## Source Tiers

| Tier | Source Type | Use For | Default Weight |
|------|-------------|---------|----------------|
| 1 | Detailed practitioner threads, founder posts, CS leader comments, implementation-manager field reports | Workflow truth, workarounds, language buyers use | High |
| 2 | Recent verified reviews with role, segment, date, and review-source label | Product experience and repeated pain | High |
| 3 | Review-site AI summaries, category pages, comparison pages | Vendor set, common vocabulary, directional themes | Medium |
| 4 | Analyst reports, marketplace listings, expert roundups | Category boundaries and buyer criteria | Medium |
| 5 | Vendor docs, case studies, product pages, pricing pages | Positioning, claimed capabilities, recent product direction | Low for pain claims |
| 6 | Anonymous short blurbs, unlabeled pasted reviews, promotional comments | Weak support only | Low |

## Review Labels To Capture

G2 and Capterra expose labels that matter for weighting. Capture them when visible.

- Verified current user.
- Organic source.
- Seller invite or vendor-managed campaign.
- Incentivized review.
- Business partner, guest user, or non-scoring review.
- Reviewer role and company size.
- Date and usage duration.

Official reference points:

- G2 review validity: https://sell.g2.com/review-validity
- G2 review activity docs: https://documentation.g2.com/docs/fr/review-activity
- Capterra review verification: https://www.capterra.com/resources/how-we-verify-reviews/
- Capterra community guidelines: https://www.capterra.com/legal/community-guidelines/

## Scoring Heuristic

Score each evidence item from 0 to 5.

| Signal | Add |
|--------|-----|
| Reviewer is in target segment | +1 |
| Reviewer role touches the workflow directly | +1 |
| Review is recent for the category | +1 |
| Source label is organic or non-incentivized | +1 |
| Review gives a concrete before-and-after workflow | +1 |

Subtract 1 when:

- Review is seller-invited or incentivized.
- Review is generic praise with no workflow detail.
- Source is vendor-owned.
- Reviewer segment does not match the angle.
- The same language appears across many reviews.

Do not use the score mechanically. Use it to force explicit judgment.

## Pattern Calls

| Pattern | Meaning |
|---------|---------|
| Same complaint across 3 vendors | Category gap candidate |
| Same complaint across 2 vendors and Reddit | Probable category gap |
| One vendor only | Vendor miss or reviewer mismatch |
| Praise across every vendor | Table stakes |
| Strong praise plus same workflow workaround | Adoption gap |
| Review-site complaint plus vendor docs claiming solution | Messaging or execution gap |

## Bias Checks

- Does the review page show many recent seller-invited reviews?
- Are most reviews from one company size that does not match the target segment?
- Are negative reviews older than a major product release?
- Are positive reviews newer than an incentive campaign?
- Are Reddit comments from vendors, affiliates, or accounts created to promote a tool?
- Are vendor comparisons naming competitors fairly or only constructing straw men?

## Confidence Labels

| Label | Use When |
|-------|----------|
| Strong | Multiple competitors, multiple source types, target-segment reviewers, recent evidence |
| Moderate | Multiple competitors, but one source type dominates |
| Low | Sparse data, blocked pages, mostly vendor-owned sources, or unlabeled pasted reviews |
| Do not call | Evidence cannot distinguish category gap from vendor-specific miss |
