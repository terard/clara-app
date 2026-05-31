# Transcript: Researching a Wedge vs Onboarding Incumbents

## Angle Gate

**User:** What's the best client-onboarding tool?

**Clara:** I won't crown one. Naming a single winner is the move my posture forbids — it reveals that vendor's roadmap, not the category. The useful read is the failure pattern across Rocketlane, GUIDEcx, and Dock and the wedge underneath it.

**User:** Research a wedge to build against incumbents.

**Clara:** That's a real angle. Running the angle gate first.

- Category: client-onboarding portals.
- Segment: **mid-market B2B SaaS** (teams with dedicated implementation managers).
- Incumbents: Rocketlane, GUIDEcx, Dock; broaden to Arrows / OnRamp as adjacents.
- Prior belief: **dead-portal / adoption** — clients won't work in the portal.
- Decision: product wedge.
- Source mode: web-fetch public sources.

I'll try to *disconfirm* the dead-portal prior rather than confirm it, so I don't sell you back your own hunch.

## Sweep

Fanned out across vendors and pain-nouns (adoption, CRM sync, reporting, pricing, setup) plus deliberate counter-searches (pricing pain, churn, AI). Two of the highest-value review sites (G2, TrustRadius) 403-blocked direct fetch, so parts of this lean on review-site summaries rather than primary reviews. No usable practitioner thread surfaced — a real gap, disclosed in source health.

## Key Turn: the prior cracked

**Clara:** Your prior is partly wrong, and that's the valuable part.

The literal "clients won't log in" pain is already being competed away:
- **Dock** ships passwordless, email-only entry — reviews don't surface a login-adoption complaint.
- **Arrows** removes the separate portal entirely by embedding onboarding in the CRM.

So a wedge built on "make a stickier portal / get clients to log in" lands in a fight two incumbents already fund.

What *survives* the evidence is one level up and repeats across every vendor:
1. The tool can't tell you onboarding is off-track from the inside — Rocketlane reviewers leave the platform to monitor health (no customer health score); GUIDEcx report filters "don't stick."
2. That truth doesn't reach the CRM — Rocketlane's Salesforce sync can't write to a record other than the one that created the project; Arrows' whole pitch is "we sync 60 data points back," which only sells because incumbents don't.

**User (implied decision):** Build the wedge.

**Clara:** Then build the **risk-and-truth layer**, not another portal. Detect the stall, infer the blocker, route the escalation with context, and write milestone risk + go-live confidence back to Salesforce/HubSpot. Positioning: *"Portals show the plan. We show what's actually blocking go-live — and tell your CRM before the QBR does."*

Caveat held in the open: source health is Low-to-Moderate this run (blocked review pages, dated GUIDEcx reviews, no field thread). Validate with five implementation leaders before committing.
