---
search:
  boost: 5.0
---

# Slot: accounting_date 


_The accounting period this entry pertains to — i.e. when the books closed for the period the figures belong to. For actuals, this is the period close date (e.g. "2026-12-31" for Q4 2026 actuals); for encumbrance, the as-of date of the encumbrance state. Distinct from version_date because reconciliation lag, restatements, and audit corrections all cause the report-out date to differ from the close date — and both facts need to be preserved. Required on actual entries (enforced by rule); optional otherwise._



<div data-search-exclude markdown="1">



URI: [core:accounting_date](https://w3id.org/collabri/core/accounting_date)
<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [BudgetEntry](BudgetEntry.md) | One datestamped budget snapshot for a spending unit (TaskTeam, Subtask, or Pa... |  no  |






## Properties

### Type and Range

| Property | Value |
| --- | --- |
| Range | [Date](Date.md) |
| Domain Of | [BudgetEntry](BudgetEntry.md) |

### Cardinality and Requirements

| Property | Value |
| --- | --- |
### Slot Characteristics

| Property | Value |
| --- | --- |
| Owner | [BudgetEntry](BudgetEntry.md) |








## In Subsets


* [SowSpec](SowSpec.md)
* [ExecutionTracking](ExecutionTracking.md)






## Identifier and Mapping Information





### Schema Source


* from schema: https://w3id.org/collabri/core




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | core:accounting_date |
| native | core:accounting_date |




## LinkML Source

<details>
```yaml
name: accounting_date
description: The accounting period this entry pertains to — i.e. when the books closed
  for the period the figures belong to. For actuals, this is the period close date
  (e.g. "2026-12-31" for Q4 2026 actuals); for encumbrance, the as-of date of the
  encumbrance state. Distinct from version_date because reconciliation lag, restatements,
  and audit corrections all cause the report-out date to differ from the close date
  — and both facts need to be preserved. Required on actual entries (enforced by rule);
  optional otherwise.
in_subset:
- sow_spec
- execution_tracking
from_schema: https://w3id.org/collabri/core
rank: 1000
owner: BudgetEntry
domain_of:
- BudgetEntry
range: date

```
</details></div>