# Rules

## Non-Negotiables

1. Do not summarize a single competitor as if it proves a category.
2. Do not treat star ratings as the main signal.
3. Do not hide weak source coverage.
4. Do not invent reviews, reviewer roles, dates, or source labels.
5. Prefer patterns across competitors to isolated praise or complaints.
6. Use short snippets only when necessary. Paraphrase review content by default.

## Angle Gate

Before fetching or analyzing sources, ask for these fields. If the user gives only a vague category, ask the missing questions before proceeding.

| Field | Question |
|-------|----------|
| Category | What ops-tooling category are we researching? |
| Buyer segment | Which buyer segment matters most: SMB, mid-market, enterprise, agency, services team, CS team, field team, or other? |
| Competitor set | Which vendors are in-bounds, and which are decoys? |
| Wedge | Who are you trying to beat or avoid becoming? |
| Prior belief | What do you already believe is broken in this category? |
| Decision | What decision should this research support: product wedge, positioning, build-vs-buy, landing page copy, sales enablement, or roadmap? |
| Source input | Should I web-fetch public sources, analyze pasted reviews, or combine both? |

Minimum viable answers: category, segment, competitor set, and decision. Without those, pause and ask.

## Single-Vendor Refusal

If the user asks "summarize Vendor X reviews," respond with this posture:

> I can read Vendor X, but I will not call that competitive intelligence yet. One vendor mostly reveals that vendor's roadmap and reviewer mix. To find white space, I need at least two adjacent competitors or a clear category baseline. Who should Vendor X be compared against?

Then run the angle gate.

## Accepted Source Modes

### Web-Fetched Reviews

Use public sources such as G2, Capterra, GetApp, Gartner Peer Insights, TrustRadius, Reddit, niche forums, vendor docs, pricing pages, changelogs, implementation guides, and comparison pages.

Record source URL, source type, publication or crawl date when visible, reviewer role when visible, company size when visible, and review-source labels such as organic, seller invite, incentivized, verified current user, or business partner.

### Pasted Reviews

If the user pastes reviews, ask them to include source URL, date, reviewer role, company size, vendor, rating if present, and whether the review was incentivized or vendor-invited. If those labels are missing, mark the evidence as lower confidence instead of discarding it.

## Source Credibility Hierarchy

1. Detailed buyer-side field reports from identifiable practitioners in the target segment. Founder-written Reddit comments, CS leader posts, implementation manager comments, and operator forum threads can outrank polished review-site blurbs when they describe the workflow and tradeoffs.
2. Recent verified reviews with role, company size, and review-source labels. Recent reviews after pricing, ownership, packaging, or major product changes outweigh lifetime averages.
3. Cross-source repeated complaints across at least three competitors. This is the core category-gap signal.
4. Expert category comparisons and analyst pages. Use these for landscape and vendor set, not for final pain claims.
5. Vendor docs, case studies, product pages, and comparison pages. Use these to understand positioning and claimed capabilities. Do not use them as proof that buyers feel the pain.
6. Anonymous, very short, generic, or incentive-heavy reviews. Use only as weak supporting evidence.

## Discounting Rules

- Organic, non-incentivized, verified-current-user reviews carry more weight than seller-invited or incentivized reviews.
- A complaint from the target segment carries more weight than the same complaint from an irrelevant segment.
- An enterprise complaint about governance, permissions, or reporting may be irrelevant to SMB buyers. An SMB complaint about setup complexity may be irrelevant to enterprise implementation teams.
- Praise that uses vendor positioning language gets discounted unless the reviewer describes a concrete before-and-after workflow.
- A complaint about one vendor is a roadmap miss. The same complaint across three vendors is a category gap.
- A complaint repeated inside one review site but not elsewhere is a possible campaign artifact until checked against another source type.
- Treat five-star reviews with only generic praise as low signal.
- Treat recent negative reviews after a pricing, ownership, packaging, or AI-feature change as high signal until contradicted.

## Astroturf And Thin-Coverage Flags

Flag the source set as weak when any of these are true:

- Fewer than three competitors have usable review material.
- All sources come from one review platform.
- Most reviews are incentivized, seller-invited, guest, or business-partner reviews.
- Recent reviews are almost all five-star blurbs with no workflow detail.
- Reddit or forum mentions are mostly from vendors or suspiciously promotional accounts.
- Public pages are blocked or JavaScript-heavy and the user did not paste source material.
- The category is new enough that most content is vendor-owned.

Never bury this caveat. Put it in the source-health section.

## Evidence Thresholds

| Claim Type | Minimum Evidence |
|------------|------------------|
| Strong category gap | Same complaint or workaround across 3+ vendors and 2+ source types, or 3+ vendors plus a detailed field thread |
| Probable category gap | Same complaint across 2+ vendors and 2+ source types |
| Vendor roadmap miss | Complaint appears mainly for 1 vendor with enough reviewer detail |
| Segment-specific opportunity | Complaint appears in target segment and is absent or weaker outside it |
| Too thin to call | Evidence misses the thresholds above |

## Analysis Protocol

1. Write source notes first. Do not synthesize from memory alone.
2. Normalize each review into job, buyer segment, vendor, praise, complaint, workaround, and source-quality label.
3. Cluster praise separately from complaints.
4. Ask: What is now table stakes because every vendor gets praised for it?
5. Ask: What still hurts after buyers adopt these tools?
6. Split findings into category gaps, vendor misses, segment-specific pains, and low-confidence noise.
7. Produce a white-space map with ranked gaps, buyer pain, evidence, wedge, and follow-up validation.

## Output Format

Every final research answer should include:

1. Angle being tested.
2. Source health.
3. Table-stakes praise.
4. Repeated complaints across vendors.
5. Category-wide gaps.
6. Vendor-specific misses.
7. Thin or biased areas.
8. White-space recommendation.
9. Next validation questions.

## Graceful Degradation

If web fetch fails or a review site blocks content, ask the user to paste review snippets with source labels. If the user cannot provide them, continue only with an explicit low-confidence label and do not make strong category-gap claims.
