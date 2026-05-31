# Staff/Shift Scheduling — Source Notes

**Run date:** 2026-05-30
**Category:** Staff/shift scheduling (rostering hourly workforce)
**Segment in focus:** Mid-market, multi-location, 50–500+ hourly employees (retail, hospitality, healthcare)
**Decision the run supports:** Product wedge
**Source mode:** Web-fetched public sources
**Vendor set:** Deputy, When I Work, 7shifts, HotSchedules (Fourth), Homebase, Sling, Quinyx, Workforce.com (Tanda)

> These are raw, labeled source notes. Synthesis lives in `staff-shift-scheduling-white-space-map.md`. Nothing here is a category-gap claim on its own.

---

## 1. Source Coverage Summary

| Source type | Status | Notes |
|---|---|---|
| Capterra | **Primary, usable** | The workhorse for every vendor. Exposes reviewer role, industry, company-size band, tenure, date, and a "Verified Reviewer" flag — but **not** organic-vs-seller-invited-vs-incentivized provenance. |
| G2 | **Blocked (403)** for all vendors | The one platform that exposes organic/seller-invite/incentivized labels — and it was unreachable. Only search-snippet themes captured. |
| TrustRadius / Gartner Peer Insights | **Blocked (403)** | Snippets only. Gartner Quinyx page had just 3 reviews (too thin). |
| Reddit / operator forums | **Failed for every vendor** | reddit.com is blocked to the crawler on both search-filtering and fetch. **The framework's Tier-1 source (detailed practitioner field threads) is absent.** |
| Vendor pricing pages | **Usable** | Captured live tier structures and recent repricing for all published-price vendors. |
| Vendor docs / changelogs / press | **Usable** | Recent AI/forecasting/compliance shipments captured. |
| Aggregator blogs (turnozo, connecteam, Outsail, SelectHub) | **Low trust** | Used only for positioning context. connecteam and several others are competitors, so their con-framing is interested. |

### Source-health verdict: **MODERATE, capped**
Triggers the framework's thin-coverage flags: (a) attributable evidence leans on **one platform (Capterra)**; (b) **no review-source/incentivization labels obtainable** anywhere (G2 blocked); (c) **no native practitioner-forum voice**. Capterra also exposes few genuinely mid-market (51–500) reviewers — most are SMB/individual-contributor — so mid-market conclusions are **extrapolated from SMB complaints whose mechanics scale upward**, not proven on a deep mid-market base. Appropriate for **hypothesis generation, not proof.**

---

## 2. Table-Stakes Praise (clustered, cross-vendor)

Praised across nearly every vendor → not differentiators; this is the category floor.

| Table-stakes capability | Vendors praised for it |
|---|---|
| Easy/intuitive schedule building | Deputy, When I Work, Homebase, Sling, Quinyx |
| Self-service shift swap / drop / open-shift pickup | When I Work, 7shifts, Deputy, Sling |
| Mobile schedule visibility + reminders | When I Work, Homebase, Deputy |
| Time tracking → payroll handoff (when configured) | Deputy, When I Work (ADP/Rippling), Workforce.com (ADP) |
| Replaces Excel/Google Sheets rotas | Quinyx, 7shifts, Homebase |
| Basic demand forecasting exists | Deputy, 7shifts, Quinyx |

Most praise uses positioning-adjacent language ("easy," "all in one place") without before/after workflow detail → discounted per rules.

---

## 3. Complaint Evidence Matrix (by job-to-be-done)

Confidence reflects target-segment match + recency + source quality. Because no incentivization labels were obtainable, all rows are weighted on role/size/date, not source-health labels.

### 3a. Reporting & multi-location analytics
| Vendor | Complaint (paraphrase) | Role / Size / Date | Source | Confidence |
|---|---|---|---|---|
| When I Work | Custom reporting gated to Pro+ tier; no complaints found because low-tier reviewers can't reach it | (tier-gating from pricing page) | When I Work pricing | Moderate (gating confirmed) |
| Sling | Reporting only on top Business tier and desktop-only; no predictive insight | aggregated + Rosalina M. 2023 | Capterra / connecteam | Moderate-High |
| Quinyx | Reports don't pull correct data; too many clicks to extract | Office Mgr, Cosmetics, Dec 2018 | Capterra | Moderate |
| Workforce.com | Limited advanced reporting/analytics | Exec, Automotive (trial), Dec 2023 | Capterra | Low-Moderate |
| Homebase | Can't export role-specific cost reports; reporting rated low | Kylee G., Non-Profit Youth Dir, Aug 2025 | Capterra | Moderate-High |
| Deputy | Reporting strong on default fields, weak for the operating cadence buyers use | aggregated G2 snippets | G2 (snippet) | Low-Moderate |

### 3b. Labor-cost forecasting (accessible vs. gated)
| Vendor | Complaint | Role / Size / Date | Source | Confidence |
|---|---|---|---|---|
| HotSchedules | "Forecasting models are static" | **VP of Finance, Hospitality, 1,001–5,000 emp, Dec 19 2025** | Capterra | **Very High** (senior, large multi-loc, recent) |
| 7shifts | "Optimal labor tool is pretty weak"; wants daypart + actual-vs-forecast; ML auto-scheduler **enterprise-tier only** | GM, Restaurants, Aug 2021; Founder, 250-seat, Oct 2019 | Capterra | Moderate-High |
| When I Work | Custom unit forecasting is Pro+ only | (pricing page) | When I Work pricing | Moderate |
| Deputy | Demand forecasting / AI auto-schedule gated to Core+ | (pricing page) | Deputy pricing | Moderate |

### 3c. Compliance / labor-law (advisory vs. blocking)
| Vendor | Complaint | Role / Size / Date | Source | Confidence |
|---|---|---|---|---|
| Sling | Rest/clopening warnings are **advisory only — system does not block** violations; not HIPAA-compliant | connecteam analysis | connecteam (interested) | Moderate-High |
| When I Work | Shipping Break Attestation / Scheduled Breaks in 2025 + roadmap promises "more compliance" → **concedes it's underbuilt** | 2025 release notes / roadmap | Vendor changelog | Moderate |
| Homebase | Manual break deductions required; should be automated | Tom C., Logistics Owner, Mar 2025 | Capterra | Moderate-High |
| Deputy | Touts labor-law compliance, **but** kiosk fails to log a punch overlapping approved time-off → payroll discrepancies, no alert | Amy E., VP, Retail, Nov 25 2025 | Capterra | High |

### 3d. Multi-location architecture & cost cliff (segment-specific)
| Vendor | Complaint | Role / Size / Date | Source | Confidence |
|---|---|---|---|---|
| Deputy | Architected around single physical locations; distributed/multi-timezone teams forced into "areas" workarounds | **Katy W., Dir Talent Mgmt, 201–500 emp, Dec 4 2024** | Capterra | High (target size, recent, concrete) |
| Homebase | Per-location billing; **cannot assign separate managers per location**; cross-location hour tracking paywalled | Dee W. (Dec 2024), Angela P. (Sep 2025), Brandon C. (Apr 2025) | Capterra | High (3 reviews + pricing page) |
| 7shifts | Per-location pricing scales with footprint (20 locations = 20× plan) | (pricing page) | 7shifts pricing | Moderate-High |
| Sling | Multi-location group messaging has no per-location separation | Larisa F. (Nov 2025), Rosalina M. (2023) | Capterra | High (2 reviews) |

### 3e. Payroll-sync accuracy
| Vendor | Complaint | Role / Size / Date | Source | Confidence |
|---|---|---|---|---|
| Deputy | Punch/time-off overlap → payroll discrepancies; Xero integration errors at scale | Amy E. VP Retail (Nov 2025); GM Retail (Aug 2025) | Capterra | High |
| When I Work | Gusto sync errors give no actionable info on what to fix | Nicole H., Dir of Operations, Jan 2026 | Capterra | Moderate-High |
| Homebase | Payroll tax-calc errors ("messed up tax returns," $3,230 variance) | aggregated 2025-26 | turnozo (aggregator) | Low-Moderate |

### 3f. Mobile app reliability
| Vendor | Complaint | Role / Size / Date | Source | Confidence |
|---|---|---|---|---|
| 7shifts | App logs everyone out / servers crash | Manager on Duty, Jun 2025 | Capterra | High |
| Workforce.com | App crashes on open / "black screen"; clock-in won't load → manual payroll fixes | App-store / justuseapp employees | justuseapp | Moderate-Strong |
| Deputy | Freezing, crashes, random logouts, notifications not firing → staff miss shifts | Josh N., Aanchal B. (Nov 2024) | Capterra | Moderate |
| When I Work | Glitchy after updates; delayed/unreliable notifications | Yanina A., 11–50, May 2025; others | Capterra | Moderate-High |
| Sling | Phone↔desktop sync delays; changes don't push immediately | Hallye N., 11–50, Jan 2026 | Capterra | High |
| Homebase | Occasional crashes; private-message notifications don't surface | Gabriela P., Nov 2024 | Capterra | Moderate |

### 3g. Support model mismatched to mid-market
| Vendor | Complaint | Role / Size / Date | Source | Confidence |
|---|---|---|---|---|
| Deputy | Chat/email-only, offshore (AU), slow in US hours; phone + 24/7 chat gated to Pro tier | Sue B. CEO (Aug 2024) + others | Capterra | High |
| HotSchedules | Ticket resolution "days to weeks," hard to reach | Regional Mgr (Jul 2022) + others | Capterra | High |
| Sling | No phone; chat only post-login; 8a–8p ET weekdays only | Susan L., Mar 2024 | Capterra | Moderate-High |
| Workforce.com | Chatbot-only, no live agent | Coordinator, Jan 2025 | Capterra | Low-Moderate |

### 3h. Implementation difficulty (upper-mid tools)
| Vendor | Complaint | Role / Size / Date | Source | Confidence |
|---|---|---|---|---|
| Quinyx | Lengthy configuration; complex for non-standard org structures; steep learning curve | 3+ reviewers, 2018–2019 | Capterra | Moderate-Strong (recurs) |
| Workforce.com | Steep learning curve; hard to find compliance views; integrations need custom mapping | Mgr Hospitality (Apr 2024) + others | Capterra | Moderate |

---

## 4. Recent Change Events (high-signal per rules)

- **Deputy** — Repriced Oct 1 2025 into Lite $5 / Core $6.50 / Pro $9 per user; $30/mo minimum spend (Sept 2025). Forecasting/AI gated to Core+, SSO + 24/7 support to Pro. Xero invested $25M (2024); new CTO hired Jun 2025 to lead AI. Several "paying 40% more / add-ons stack up" complaints post-date the change → high signal.
- **7shifts** — Per-location repricing Feb/Jul 2025 (Entrée → $44.99, The Works → $76.99/location); new $10/location Brink-POS infra fee (Oct 1 2025).
- **HotSchedules / Fourth** — Merged under Marlin Equity (2019); a 2024 trade report indicated Marlin seeking to sell — watch for further ownership change. Pricing sales-gated. Fourth iQ 2.1 (Oct 2025) adds AI labor-adjustment recommendations — but in the newer iQ layer, not the legacy scheduler reviewers complain about.
- **When I Work** — 2025 Location-Based Plans moved geofencing, accruals, advanced breaks, forecasting behind higher tiers. Shipped Break Attestation / Scheduled Breaks (CA meal-break compliance); Rippling named preferred payroll partner.
- **Homebase** — AI Payroll Assistant (Oct 2025); AI Scheduling Assistant. AI hiring feature promised Jul 2025, still "coming soon" Feb 2026 (shipped-vs-promised gap).
- **Workforce.com** — Capterra review distribution suspiciously 5-star-heavy ("Cons: none") from short-tenure small companies → possible seller-invite campaign; treat onboarding praise as low confidence.

---

## 5. Coverage Caveats / Thin Spots (do not bury)

1. **No native Reddit/forum evidence** — Tier-1 practitioner voice missing for the whole run.
2. **G2/TrustRadius/Gartner blocked (403)** — no incentivization labels captured for any vendor.
3. **Capterra-dominant** — single-platform reliance trips the thin-coverage flag.
4. **SMB skew** — genuinely mid-market (51–500) reviewers are scarce (notably Katy W. 201–500 Deputy; VP Finance 1,001–5,000 HotSchedules; Hikmet L. 51–200 Sling). Mid-market claims are extrapolated.
5. **Quinyx reviews skew 2018–2019** — pre-current product; treat UI/speed complaints as possibly stale, implementation/reporting complaints as durable.
6. **Aggregator/competitor sources** (connecteam, turnozo) used only for positioning, not as proof of buyer pain.

**Fastest upgrade path:** paste 3–5 labeled Reddit/operator-forum threads (source URL, date, role, vendor) on (a) blocking compliance and (b) multi-location reporting — that would move those themes from *probable* to *strong*.
