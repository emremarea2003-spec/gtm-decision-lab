# Sample Output: Developer Analytics Tool GTM Decision Brief

## 1. Product Snapshot

**Product:** Hosted adoption analytics dashboard for open-source maintainers  
**Core use case:** Aggregate adoption signals into a report maintainers can share with sponsors, teams, or stakeholders  
**Current stage:** First free users  
**Desired outcome:** Choose first beachhead and GTM motion  
**Constraints:** Solo builder, strong developer access, no sales team  

## 2. Input Completeness Audit

**Completeness:** Medium  
**Strongest evidence:** 5 prototype users, 3 sponsor/stakeholder reporting needs, known manual alternatives  
**Missing critical evidence:** Willingness to pay and buyer distinction between maintainers, DevRel, and company teams  
**Confidence impact:** Strong enough to choose a validation beachhead, not strong enough to scale acquisition  

## 3. Recommended Beachhead Segment

**Recommendation:** Independent open-source maintainers seeking sponsorship or stakeholder proof  
**Confidence:** Medium  
**Why this segment:** They have the clearest repeated pain, are easiest to reach through GitHub/community channels, and can validate the PDF/reporting use case quickly. Their willingness to pay is still unproven, so the first experiment should test paid reporting, not dashboard usage alone.

| Segment | Pain | Urgency | Pay | Reach | Win | Proof | Reference | Total | Confidence |
|---|---:|---:|---:|---:|---:|---:|---:|---:|---|
| Independent OSS maintainers seeking sponsors | 4 | 3 | 2[A] | 5 | 4 | 5 | 4 | 27 | Medium |
| DevRel teams at devtool startups | 4[A] | 3[A] | 4[A] | 3 | 3[A] | 4 | 3 | 24 | Low-medium |
| Engineering managers with company-backed OSS | 3[A] | 3[A] | 4[A] | 2 | 3[A] | 3 | 3 | 21 | Low |

## 4. Rejected or Deferred Segments

| Segment | Decision | Reason | Revisit trigger |
|---|---|---|---|
| DevRel teams | Defer | Better budget, but current evidence comes from maintainers, not DevRel buyers | Revisit after 5 maintainers use reports in sponsor or stakeholder conversations |
| Engineering managers | Defer | Buyer is harder to reach and proof likely requires team workflow/integration | Revisit after export/reporting use case is validated |

## 5. Recommended GTM Motion

**Primary motion:** Developer-led  
**Supporting motion:** Content-led  
**Why this fits:** The users are developers/maintainers, proof can happen quickly through GitHub data, and the builder has developer-community access.  
**Why other motions are weaker now:** Outbound to companies is premature because company buyer and budget are unproven. PLG may work later, but first value needs a sharp report/export use case.  
**Contraindication to watch:** If maintainers like the dashboard but will not pay, the commercial buyer may be DevRel or company-backed OSS teams instead.  
**First action:** Ship a monthly sponsor-ready PDF report and ask current users whether they would pay for it.  

## 6. Positioning Hypothesis

**For:** Independent open-source maintainers seeking sponsors or stakeholder buy-in  
**In this trigger situation:** They need to show project adoption and community momentum  
**Current alternative:** GitHub Insights, package download charts, manual screenshots, ad hoc docs analytics  
**Main pain:** Adoption evidence is scattered and hard to package  
**Why now:** Sponsors and stakeholders increasingly ask maintainers to prove momentum  
**Why this product:** It turns scattered adoption signals into one shareable report  
**Proof needed:** Maintainers must pay for reporting or use reports in sponsor conversations  

**One-line hypothesis:** For open-source maintainers seeking sponsorship, the product is a sponsor-ready adoption report that turns scattered GitHub, package, docs, and community signals into proof of momentum.  

**Claims to avoid until proven:**

- "For DevRel teams" until DevRel buyers are interviewed
- "Revenue analytics" unless sponsor conversion is tracked
- "Complete open-source intelligence" if key channels are missing

## 7. Channel Bets

| Channel | Why reachable | First tactic | Evidence needed |
|---|---|---|---|
| GitHub/community outreach | Maintainers are visible and project data is public | Offer 20 maintainers a free adoption report | Reply rate, report usage, payment interest |
| Technical content | Maintainers search/share examples of open-source growth | Publish "How to create a sponsor-ready OSS adoption report" | Qualified maintainer signups |

## 8. 30-Day Validation Plan

| Experiment | Hypothesis | Segment | Action | Success signal | Failure threshold | Evidence to collect | Decision rule |
|---|---|---|---|---|---|---|---|
| Sponsor-ready report test | Maintainers will value exportable adoption proof more than a dashboard | Independent OSS maintainers | Generate 10 reports and offer paid monthly refresh | 5 reports delivered, 3 users share/use them, 2 payment discussions | Users praise report but will not use or pay | Use case, sponsor context, payment ceiling, missing metrics | Continue if reports create stakeholder use; pivot buyer if no payment signal |

## 9. Decision Gates

**Continue if:** Maintainers use reports externally and at least 2 discuss payment  
**Change segment if:** Reports are valued only by company-backed projects  
**Change motion if:** Community/content gets attention but no usage  
**Change positioning if:** "Sponsor-ready report" beats "analytics dashboard" in replies and usage  

## 10. Evidence, Assumption, Risk Ledger

| Decision | Evidence | Assumption | Risk if wrong | Validation action |
|---|---|---|---|---|
| Start with independent maintainers | 5 users, 3 reporting needs | Maintainers can or will pay | Product may need DevRel buyer | Test paid monthly report |
| Use developer-led motion | GitHub users are visible and builder has community access | Maintainers will try tools from direct outreach | Interest may not convert to payment | Track report usage and payment asks |
| Position around sponsor-ready reports | One user asked for PDF export; 3 need stakeholder proof | Report is more valuable than dashboard | Export may be a feature, not a product | Offer report as the paid unit |

## 11. Next Actions

1. Build one sponsor-ready PDF export from existing prototype data.
2. Send it to the 5 current users and ask what they would change before sharing it.
3. Contact 20 similar maintainers with a concrete sample report offer.
