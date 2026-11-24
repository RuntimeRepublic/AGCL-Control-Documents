# AMD-002 — Point 02: household prebate and business-input rebate for state and local consumption taxes

Status: PROPOSED (pull request, for the founder's review). Not adopted.
Proposed: 2026-11-24, by Claude (Opus 5.5) at James Hodges's direction ("yes, change the control documents").
Version (Rule J1): Point 02 goes from unversioned (current text) to 0.2 if adopted.

## Why (the conflict)
Point 02, "State and Local Sales Tax Authority," requires state and local sales taxes to follow H.R. 25's structure, then says "No credits, offsets, or behavioral conditions." H.R. 25 itself has two credits:
- the family consumption allowance (monthly prebate: rate × the poverty guideline for household size), and
- no tax on business-purpose purchases (tax paid on them is refunded or credited).
So a state or local tax "fully aligned with H.R. 25" cannot exist under the current wording. James directed that the state plan be modeled just like H.R. 25, with a rebate and a prebate.
Related: Constitutional-Engineering Bill A (LOU-004, Draft 1.12) mirrors H.R. 25 at the state level and lists the Kansas prebate as an OPEN HUMAN DECISION (WD-BILL-A-009, XW-HR25-009). This amendment records the AGCL side; the Bill A decision is recorded there separately.

## Scope (Rule J4)
- Affected document: `plan/02_revenue_sharing.md` only, section "State and Local Sales Tax Authority."
- Change: replace the bullet "No credits, offsets, or behavioral conditions" with:
  - "No credits, offsets, or behavioral conditions, except two that mirror H.R. 25:"
  - "(a) Household prebate: each household receives, monthly, the state or local rate × the federal poverty guideline for its size. Same formula for every household; no income test; no behavior required."
  - "(b) Business-input rebate: tax paid on purchases for business purpose is refunded or credited, so the tax falls once, on the final consumer."
- Intended effect: state and local consumption taxes can match H.R. 25 completely, as Point 02 already intends.
- Unintended risks: a prebate becomes a growing transfer program; the rebate becomes a loophole for personal purchases. Guards: the prebate formula is fixed (rate × poverty guideline, nothing else) and shown on the public ledger (00G); business-purpose rules follow H.R. 25's definitions, nothing added (RP3).

## Regulative Principles check (000 Rule S8)
- RP2: the exception is written down; silence still restricts. Pass.
- RP3: no official may add conditions beyond the formula. Pass.
- RP4: rain on the just and the unjust: every household gets the same formula by size, rich or poor. Pass.
- RP5: protects property: no tax on the necessities a poverty-level budget buys; no recurring claim on owned property. Pass.

## Cascade impact (Rule J8)
- Authority: slightly widens state/local tax design, only to match H.R. 25.
- Property rights: strengthens them (replacement for property tax becomes feasible).
- Exit (00D): unchanged; consumption choices still control exposure.
- Debt (00E): none.
- Downstream: Lean Office Pro demo "Property tax" tab, section 7 (Kansas use tax modeled on H.R. 25) can drop its conflict flag once adopted. Constitutional-Engineering Bill A XW-HR25-009 decision to be recorded by its own process.

## Notice interval (Rule J6)
7 days after adoption before it takes effect. Prior text preserved in Git history (Rule J2).

## Red team / blue team
- Red: credits are how tax codes grow; this opens the door Point 02 tried to shut.
- Blue: the door opens exactly as wide as H.R. 25 and no wider; the formula is fixed, public and identical for everyone, and without it the plan taxes groceries for the poorest households, which is the strongest argument against replacing property tax with a consumption tax.
