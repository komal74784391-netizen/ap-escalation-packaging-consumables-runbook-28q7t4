# AP Escalation Runbook - Packaging & Consumables

**Status: DRAFT - not approved, not released.**

This repository is a placeholder scaffold for the Packaging & Consumables escalation procedure. The procedure has not been approved for use and must not be cited or applied to supplier notices until the Procurement Controls Board signs off (planned review: 2027-Q1). The material below is working content only.

## Purpose

Define the controlled process for resolving open supplier balances in the Packaging & Consumables
spend category, from discrepancy classification through supplier notice and closure.

## Scope

Applies to all purchase documents in the Packaging & Consumables category that remain partially or
wholly unsettled at quarter end.

## Roles and responsibilities

| Role | Responsibility |
| --- | --- |
| Purchasing lead | Owns the supplier relationship and signs the supplier notice |
| AP analyst | Confirms the open balance from the settlement ledger |
| Category board | Approves settlements above the delegated limit |
| Procurement compliance | Audits evidence and case records |

## Trigger conditions

- The document is not fully settled at the reporting cut-off.
- The open balance exceeds the category tolerance.
- No credit note or remittance advice explains the difference.

## Procedure

1. Confirm the open balance by recomputing invoice value less settled amount.
2. Classify the discrepancy and collect the evidence listed in `configs/escalation_rules.yaml`.
3. Open a case record and assign the purchasing lead named on the statement.
4. Raise the supplier notice using `templates/escalation-notice.md`.
5. Track the response for ten business days and escalate if unresolved.

## Evidence requirements

Statements, purchase orders, goods receipts and remittance advice must all be attached
to the case record before the notice is raised.

## Templates

See `templates/escalation-notice.md` for the controlled notice wording.

## Escalation matrix

See `contact-matrix.md` for the first, second and final escalation points.

## Maintenance

The runbook is maintained by the procurement controls team. Proposed changes go through
the quarterly review recorded in `docs/review-record.md` when the board is in session.
