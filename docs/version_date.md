---
search:
  boost: 5.0
---

# Slot: version_date 


_The date this entry was recorded / reported out. Required on every entry. Every entry is a dated point, so the negotiation, award, and execution history is captured by accumulating entries rather than overwriting values; multiple entries of the same entry_type with different version_dates represent the chronological history of that view._

_For actuals and encumbrance, version_date is when the snapshot was actually reported — which lags the period close, because reconciliation takes time. Example: books close 2026-12-31 (accounting_date) but the figure isn't reported until 2027-01-20 (version_date) because the close cycle takes three weeks. Same two-date structure also accommodates restatements: a corrected Q4 figure reported 2027-03-15 has accounting_date 2026-12-31 and version_date 2027-03-15._



<div data-search-exclude markdown="1">



URI: [core:version_date](https://w3id.org/collabri/core/version_date)
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
| Required | Yes |
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
| self | core:version_date |
| native | core:version_date |




## LinkML Source

<details>
```yaml
name: version_date
description: 'The date this entry was recorded / reported out. Required on every entry.
  Every entry is a dated point, so the negotiation, award, and execution history is
  captured by accumulating entries rather than overwriting values; multiple entries
  of the same entry_type with different version_dates represent the chronological
  history of that view.

  For actuals and encumbrance, version_date is when the snapshot was actually reported
  — which lags the period close, because reconciliation takes time. Example: books
  close 2026-12-31 (accounting_date) but the figure isn''t reported until 2027-01-20
  (version_date) because the close cycle takes three weeks. Same two-date structure
  also accommodates restatements: a corrected Q4 figure reported 2027-03-15 has accounting_date
  2026-12-31 and version_date 2027-03-15.'
in_subset:
- sow_spec
- execution_tracking
from_schema: https://w3id.org/collabri/core
rank: 1000
owner: BudgetEntry
domain_of:
- BudgetEntry
range: date
required: true

```
</details></div>