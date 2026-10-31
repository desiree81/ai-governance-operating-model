# Periodic Review Checklist: AI Systems in Production
Run at the cadence set by the system's tier, and whenever a re-tier trigger fires. The system owner completes it; governance verifies.

## Ownership and record
- [ ] Named business owner and technical owner are still correct.
- [ ] Inventory record matches reality: purpose, data, population, integrations.
- [ ] Vendor, model, or foundation model changes since last review are recorded.

## Performance and behavior
- [ ] Evaluation set re-run since last review; results meet the acceptance criteria set at approval.
- [ ] Drift or quality monitoring reviewed; thresholds not breached, or breach actions documented.
- [ ] Override and challenge rate reviewed. A rate of zero usually means the review point is decorative, not that the system is perfect.

## Data and privacy
- [ ] Data categories in use match the approved intake. No new category crept in.
- [ ] Retention and training-use behavior verified against the vendor's current terms, not the terms at signing.
- [ ] Access list reviewed; departed team members removed.

## Risk and incidents
- [ ] Incidents since last review listed, with root cause and remediation.
- [ ] Complaints or harm reports from affected people reviewed.
- [ ] Tier re-scored against the current worksheet. Tier change recorded if any dimension moved.

## Decision
- [ ] Continue as-is.
- [ ] Continue with conditions (list them, with dates).
- [ ] Pause pending remediation.
- [ ] Retire, with data and access cleanup confirmed.
- Reviewer name and date recorded in the inventory.
