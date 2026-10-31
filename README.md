# AI Governance Operating Model
A practical operating model for governing AI at enterprise scale: how models and agents get proposed, evaluated, approved, monitored, and retired, and who owns each step.

This repository holds the framework and templates. It is drawn from leading an enterprise AI governance program that includes an AI Control Tower, rewritten in generic enterprise language so any organization can adopt it. No employer-specific systems, data, or internal documents are included.

## Why an operating model, not a policy PDF
Policies state intent. They do not route work. AI governance fails in the gaps between teams: a model built before anyone assessed its risk, an agent in production that nobody inventoried, a vendor tool adopted by one department with no oversight at all. An operating model closes those gaps with named owners, defined gates, and a single inventory of record.

## The five components

### 1. Intake
Every proposed model, agent, or AI-enabled vendor tool enters through one door. The intake record captures the business purpose, the owner, the data it touches, the population it affects, and whether a human reviews its outputs. Intake is lightweight by design: if the front door is painful, people build side doors.

### 2. Inventory
The intake record becomes the inventory of record, the Control Tower view: every AI system in the enterprise with its owner, risk tier, lifecycle state, and review dates. If it is not in the inventory, it is not approved to run. The inventory is a living system, fed by intake and discovery, not a spreadsheet refreshed for audits.

### 3. Risk tiering
Systems are tiered by the harm they could do, not by how impressive the technology is. Tiering weighs decision impact, data sensitivity, autonomy (does it act, or does it advise?), and external exposure. The tier sets the depth of review, the required controls, and the approval level. Mapped to the NIST AI Risk Management Framework functions: Govern, Map, Measure, Manage.

### 4. Lifecycle gates
Defined checkpoints from proposal to retirement: design review, data and privacy review, security review, evaluation evidence, production approval, periodic re-review, and a retirement path so systems do not linger unowned. Gates scale with the tier. A low-risk internal tool should move in days; an autonomous system touching customers should expect scrutiny.

### 5. Oversight and reporting
Leadership gets a current, honest picture: what is running, what is in review, where the risk concentrates, and which systems are overdue for re-review. Oversight reporting is generated from the inventory, so it cannot drift from reality without someone noticing.

## Templates in this repository
- Model and agent intake form
- Risk tiering worksheet, mapped to NIST AI RMF
- Governance council charter outline: membership, decision rights, escalation path
- Periodic review checklist for systems in production

## Principles
- Governance is a design input, not a review at the end.
- One inventory, one intake, no side doors.
- Controls scale with risk, so low-risk work moves fast.
- Every system has a named owner, or it does not run.
- Human accountability stays explicit, especially where agents act.
