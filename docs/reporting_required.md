---
search:
  boost: 5.0
---

# Slot: reporting_required 


_True iff this entry exists to satisfy a contractually-required reporting obligation (typically: actuals on cost-reimbursable awards, actuals on fixed-price awards where the sponsor still mandates cost reporting, encumbrance reporting on a defined cadence, etc.). Distinguishes contractually-mandated entries from optional internal tracking. The full obligation detail — cadence, template, recipient — lives in a corresponding ReportingObligation on TaskTeam.obligations._



<div data-search-exclude markdown="1">



URI: [core:reporting_required](https://w3id.org/collabri/core/reporting_required)
<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [BudgetEntry](BudgetEntry.md) | One datestamped budget snapshot for a spending unit (TaskTeam, Subtask, or Pa... |  no  |






## Properties

### Type and Range

| Property | Value |
| --- | --- |
| Range | [Boolean](Boolean.md) |
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
| self | core:reporting_required |
| native | core:reporting_required |




## LinkML Source

<details>
```yaml
name: reporting_required
description: 'True iff this entry exists to satisfy a contractually-required reporting
  obligation (typically: actuals on cost-reimbursable awards, actuals on fixed-price
  awards where the sponsor still mandates cost reporting, encumbrance reporting on
  a defined cadence, etc.). Distinguishes contractually-mandated entries from optional
  internal tracking. The full obligation detail — cadence, template, recipient — lives
  in a corresponding ReportingObligation on TaskTeam.obligations.'
in_subset:
- sow_spec
- execution_tracking
from_schema: https://w3id.org/collabri/core
rank: 1000
owner: BudgetEntry
domain_of:
- BudgetEntry
range: boolean

```
</details></div>