# Risk Tiering Worksheet
Tier by the harm a system could do, not by how impressive the technology is. Score each dimension, then assign the tier by the highest single score, not the average. A system that can act on its own with regulated data is top tier even if everything else is mild.

## Dimensions

### Decision impact
- 1 — Internal convenience only. Output is informational.
- 2 — Influences an internal decision a human makes and can reverse.
- 3 — Influences customer-facing outcomes, or decisions that are costly to reverse.
- 4 — Determines prices, payments, eligibility, employment, safety, or legal outcomes.

### Data sensitivity
- 1 — Public data only.
- 2 — Internal business data.
- 3 — Confidential data or personal data at small scale.
- 4 — Regulated data, personal data at scale, or data about protected groups.

### Autonomy
- 1 — Human writes every output; the system drafts only.
- 2 — System recommends; a human approves each action.
- 3 — System acts; a human reviews outcomes on a sample or a schedule.
- 4 — System acts with no routine human review.

### External exposure
- 1 — Internal users only.
- 2 — Partners or vendors under contract.
- 3 — Customers, in a bounded surface.
- 4 — The public, or unbounded interaction.

## Tiers and what they require

### Tier 1 — Low (all scores 1)
- Intake record and inventory entry. Owner attests annually.
- No council review. Standard security review only.

### Tier 2 — Moderate (any score 2, none higher)
- Intake, inventory, documented evaluation before launch.
- Governance team review. Re-review every 12 months or on material change.

### Tier 3 — High (any score 3, none at 4)
- Full review: data and privacy, security, and evaluation evidence with named acceptance criteria.
- Governance council approval. Human review point required in the decision path. Re-review every 6 months.

### Tier 4 — Critical (any score 4)
- All Tier 3 requirements, plus an executive sponsor and a documented rollback or shutdown path.
- Continuous monitoring with defined performance and drift thresholds. Re-review every 3 months.
- The accountable executive accepts the residual risk in writing.

## Mapping to the NIST AI Risk Management Framework
- **Govern** — ownership, council decision rights, tier policy (this worksheet and the charter).
- **Map** — intake and the decision impact and exposure dimensions.
- **Measure** — evaluation evidence required at Tier 2 and above, monitoring at Tier 4.
- **Manage** — lifecycle gates, re-review cadence, incident and retirement paths.

## Re-tier triggers
Retier immediately when the system gains autonomy, starts using a new data category, expands to a new population, or changes vendor or foundation model.
