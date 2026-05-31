# White-Space Map: A Wedge Against Onboarding-Portal Incumbents

Segment: Mid-market B2B SaaS implementation / onboarding teams.
Incumbents tested: Rocketlane, GUIDEcx, Dock; adjacents Arrows, OnRamp.
Decision supported: product wedge.

## Angle Tested

Where can a new entrant beat onboarding-portal incumbents — given that the obvious wedge (the "dead portal," clients won't log in) is already being commoditized?

## Source Health

Confidence: **Low-to-Moderate.** Weaker than the cached client-onboarding demo.

G2 and TrustRadius review pages 403-blocked, so parts rely on review-site summaries (Tier 3) rather than primary reviews (Tier 2). GUIDEcx review detail skews to 2023. No Tier-1 practitioner thread surfaced this run. Vendor-owned comparison content (Arrows, GUIDEcx, Rocketlane) was over-represented and discounted. Good enough to shape a wedge and an interview guide; not good enough to commit build dollars. Direct buyer interviews required.

## What the Research Did to the Prior

The starting belief was **dead-portal / adoption.** Research **partly disconfirmed it**:

- The literal "clients won't log in" problem is being competed away. **Dock** ships passwordless email-only entry; **Arrows** removes the separate portal by living inside the CRM. A wedge built on portal stickiness fights incumbents on ground they already hold.
- The surviving, still-open form of the prior is one level up: **onboarding risk is invisible inside the tool, and it doesn't reach the CRM.** That is where adoption pain actually costs the implementation manager.

## Table Stakes (no longer a wedge)

- Centralized, customer-facing onboarding workspace.
- Shared timeline, task lists, templates/playbooks.
- Reduced email and spreadsheet scatter.
- **Low-friction client entry** — newly table stakes. Passwordless/CRM-embedded access is now expected, not differentiating.

## Repeated Complaints Across Vendors

| Complaint | Rocketlane | GUIDEcx | Dock | OnRamp | Call |
|-----------|-----------|---------|------|--------|------|
| Can't see onboarding risk *in* the tool | Yes (no health score, leave platform) | Yes (filters reset) | Yes (analytics depth) | Yes (logging unreliable) | Category gap |
| Truth doesn't sync cleanly to CRM | Yes (Salesforce record rigidity) | Partial | Partial | n/a | Probable category gap |
| Reporting won't match team cadence | Yes | Yes (can't save dashboards) | Yes | Yes | Category gap |
| Setup heavy / process-dependent | Yes | Yes | Yes | Yes (stiff) | Friction, not a wedge |

## Ranked Gaps

### 1. The Invisible-Risk Gap (strongest)

Buyer pain: The portal tracks tasks but can't tell the implementation manager that a project is sliding. Rocketlane reviewers go *outside* the platform to monitor onboarding health; GUIDEcx report filters don't persist.

Wedge: A risk layer that detects stalled customer action, infers the likely blocker, and surfaces go-live confidence — without the manager building a side spreadsheet.

Promise: *"Your onboarding tool should know a project is off-track before your QBR does."*

Confidence: Moderate.

### 2. The CRM-Truth Gap (most durable)

Buyer pain: Implementation detail lives in the onboarding tool; CRM/CS systems need manual updates. Rocketlane's Salesforce sync can't write to a record other than the project's creator record. Arrows' entire pitch — "60 data points synced to CRM" — only sells because incumbents leave this open.

Wedge: Two-way implementation truth — write milestone risk, blockers, customer effort, and go-live confidence back to Salesforce/HubSpot records.

Promise: *"Salesforce should know onboarding risk before the deck does."*

Confidence: Moderate to strong (the most consistent cross-vendor signal, including competitor framing).

### 3. The Cadence-Reporting Gap

Buyer pain: Default reports don't match how a services team runs. GUIDEcx admins can't save report filters/dashboards; Rocketlane filtering is thin; Dock/OnRamp analytics shallow.

Wedge: Reporting that starts from the team's operating rhythm (blocker aging, customer effort, IM workload) rather than vendor-default objects.

Promise: *"Report on the rhythm you actually run."*

Confidence: Moderate.

### 4. Time-to-Value Watch (category context, weaker)

Buyer pain: OnRamp's 2025 survey claims 48% of customers abandon onboarding without fast value. Vendor-owned, so directional only — but it corroborates that adoption risk is a money problem, which is what makes Gaps 1-2 fundable.

Confidence: Low-Moderate, directional.

## Vendor-Specific Misses (do not overclaim)

| Vendor | Likely miss | Still strong at |
|--------|-------------|-----------------|
| Rocketlane | Health scoring, Salesforce record rigidity, reporting flexibility, setup effort | Structured multi-phase implementation, PSA depth |
| GUIDEcx | Persisting report filters, dated UX, customer firewall/access friction | Onboarding structure, health/forecasting positioning, support reputation |
| Dock | Analytics/permission depth, not a system of record | Frictionless passwordless entry, fast workspace creation |
| OnRamp | Customization rigidity, reliable task logging, one-project-per-customer | Speed via prebuilt templates |

## Thin / Biased Areas

- Adoption "win" claims for Dock/Arrows come partly from their own marketing — discount accordingly.
- Best Salesforce-sync evidence is one vendor (Rocketlane) plus a competitor's framing; needs a second independent vendor before calling it strong.
- GUIDEcx evidence is dated; recheck post-AI-feature reviews.

## Recommended Wedge

Build the **risk-and-truth layer above onboarding portals**, not another portal:

- Detect customer-side stagnation from portal activity, email, and meeting signal.
- Infer the blocker and escalate with context, not a generic reminder.
- Write milestone risk, blocker aging, customer effort, and go-live confidence back to CRM/CS.
- Report on the team's cadence, not the vendor's default objects.

Do **not** wedge on "stickier portal / get clients to log in" — Dock and Arrows are commoditizing that.

Short positioning: *"Portals show the plan. We show what's blocking go-live — and tell your CRM first."*

## Next Validation

Interview five mid-market B2B SaaS implementation leaders.

1. Where does onboarding risk actually live today — in the tool, a spreadsheet, or someone's head?
2. What customer action still requires manual chasing despite the portal?
3. What report do execs ask for that your onboarding tool can't answer cleanly?
4. How does implementation truth reach Salesforce/HubSpot today, and who does it?
5. Would you trust an automatic "this project is at risk" signal — and what would it take to?

Success condition: if 3+ leaders describe the same outside-the-tool risk tracking or manual CRM-update workaround, prototype the risk-and-truth layer before building portal features.
