# Clara: Ops Gap Researcher

Star ratings are marketing. The signal is in the complaints that repeat across vendors.

Clara is a portable ICM-style competitive-intelligence researcher for ops tooling. It refuses to summarize a single competitor in isolation. Before researching, it asks what wedge, buyer segment, belief, competitor set, and decision the user is testing. Then it weighs public review data, field discussions, and vendor material to separate vendor-specific misses from category-wide white space.

Public repo: https://github.com/terard/clara-ops-gap-researcher

## Who It Is For

Clara is for founders, product leaders, and operators evaluating an ops-tooling category where the obvious review-site summary is too shallow to be useful. It is especially tuned for categories like client onboarding, service scheduling, SOP automation, customer-success operations, and implementation management.

## Who Would Pay

- Seed-stage founders looking for a credible wedge before building.
- Product marketers mining competitor complaints for sharper positioning.
- Product managers deciding whether a repeated complaint is a roadmap miss or a category opening.
- Operators choosing between tools and wanting source-aware analysis instead of listicle summaries.

## What It Does

- Interrogates the angle before searching or summarizing.
- Weighs sources by recency, reviewer role, segment fit, review-source label, and independence.
- Discounts vendor-sponsored, incentive-heavy, and suspiciously generic signals.
- Looks for complaints that repeat across competitors.
- Flags thin, blocked, or astroturfed source coverage instead of pretending certainty.
- Produces a white-space map with evidence strength, buyer pain, and wedge hypotheses.

## Use It

1. Drop `ops-gap-researcher/` into a Claude Code project.
2. Open Claude in that project and say: `Use ops-gap-researcher to research [ops-tooling category]`.
3. Answer the angle gate. Clara will ask for category, segment, competitor set, wedge, beliefs, source inputs, and decision.
4. Let Claude web-fetch public sources, or paste reviews into the conversation if a review site blocks fetch.
5. Review the source-health section before using the recommendation.

## Worked Example

The included demo researches client onboarding portals for B2B implementation teams.

- Source notes: `ops-gap-researcher/demo/client-onboarding-source-notes.md`
- Full transcript: `ops-gap-researcher/demo/client-onboarding-transcript.md`
- White-space map: `ops-gap-researcher/demo/client-onboarding-white-space-map.md`
- Walkthrough video: `walkthrough/clara-walkthrough.mp4`

## Runtime Folder

```text
ops-gap-researcher/
+-- CLAUDE.md
+-- CONTEXT.md
+-- identity.md
+-- rules.md
+-- examples.md
+-- reference/
|   +-- source-weighting-framework.md
|   +-- ops-tooling-source-map.md
+-- demo/
    +-- client-onboarding-source-notes.md
    +-- client-onboarding-transcript.md
    +-- client-onboarding-white-space-map.md
```

## What It Is Not

Clara is not a scraper, API pipeline, scheduled ingestion system, hosted chatbot, or review database. It is a judgment layer: portable instructions and source-weighing rules that tell an AI agent how to investigate public material at runtime.

## Submission Blurb

See `submission-blurb.md`.
