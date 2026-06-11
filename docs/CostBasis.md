---
search:
  boost: 2.0
---


# Enum: CostBasis 




_Contractual cost-determination mechanism for a budget entry. The legal mechanism by which the amount OWED is established and validated. Lives per-BudgetEntry so a single subtask can mix bases across orgs (e.g. cost-reimbursable prime with fixed-price subs)._

_Important: cost_basis governs how the payment is determined, NOT whether actual costs must be tracked or reported. Many fixed-price awards still require the performer to track and report actual costs — for audit, transparency, or future negotiations — even though those actuals don't affect what gets paid. Actuals and encumbrance BudgetEntries are independent of cost_basis. Mark each contractually-required entry with `reporting_required: true` (and capture the full reporting duty — cadence, template, recipient — as a ReportingObligation on TaskTeam.obligations)._



<div data-search-exclude markdown="1">

URI: [core:CostBasisScheme](https://w3id.org/collabri/core/CostBasisScheme)

**Enum URI:** [core:CostBasisScheme](https://w3id.org/collabri/core/CostBasisScheme)


## Permissible Values
| Value | Meaning | Description |
| --- | --- | --- |
| fixed_price | None | Firm-fixed-price (FFP) |
| cost_reimbursable | None | Cost-reimbursable |
| cost_plus_fixed_fee | None | Cost-reimbursable plus a pre-negotiated fixed fee (CPFF) |
| cost_plus_incentive_fee | None | Cost-reimbursable plus an incentive fee tied to performance (CPIF) |
| time_and_materials | None | Time-and-materials (T&M) — labor at agreed rates, plus materials at cost |
| hybrid | None | Mixed-basis contracts (e |
| other | None |  |




## Slots

| Name | Description |
| ---  | --- |
| [cost_basis](cost_basis.md) | Headline cost basis for this Payment (fixed_price, cost_reimbursable, etc |










## Identifier and Mapping Information





### Schema Source


* from schema: https://w3id.org/collabri/core






## LinkML Source

<details>
```yaml
name: CostBasis
description: 'Contractual cost-determination mechanism for a budget entry. The legal
  mechanism by which the amount OWED is established and validated. Lives per-BudgetEntry
  so a single subtask can mix bases across orgs (e.g. cost-reimbursable prime with
  fixed-price subs).

  Important: cost_basis governs how the payment is determined, NOT whether actual
  costs must be tracked or reported. Many fixed-price awards still require the performer
  to track and report actual costs — for audit, transparency, or future negotiations
  — even though those actuals don''t affect what gets paid. Actuals and encumbrance
  BudgetEntries are independent of cost_basis. Mark each contractually-required entry
  with `reporting_required: true` (and capture the full reporting duty — cadence,
  template, recipient — as a ReportingObligation on TaskTeam.obligations).'
from_schema: https://w3id.org/collabri/core
rank: 1000
enum_uri: core:CostBasisScheme
permissible_values:
  fixed_price:
    text: fixed_price
    description: Firm-fixed-price (FFP). The amount is established at award and does
      not depend on incurred costs. Performer bears cost risk.
  cost_reimbursable:
    text: cost_reimbursable
    description: Cost-reimbursable. The amount owed reflects actual allowable costs
      incurred (typically plus a fee). Sponsor bears cost risk.
  cost_plus_fixed_fee:
    text: cost_plus_fixed_fee
    description: Cost-reimbursable plus a pre-negotiated fixed fee (CPFF).
  cost_plus_incentive_fee:
    text: cost_plus_incentive_fee
    description: Cost-reimbursable plus an incentive fee tied to performance (CPIF).
  time_and_materials:
    text: time_and_materials
    description: Time-and-materials (T&M) — labor at agreed rates, plus materials
      at cost.
  hybrid:
    text: hybrid
    description: Mixed-basis contracts (e.g. cost-reimbursable for research tasks
      but fixed-price for deliverable production).
  other:
    text: other

```
</details>

</div>