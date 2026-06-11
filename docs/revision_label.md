---
search:
  boost: 5.0
---

# Slot: revision_label 


_Optional human label for this snapshot (e.g. "Initial proposal", "Post-Q&A revision", "Mod 0001 awarded", "FY26 Q2 close"). Useful when there are many same-typed entries._



<div data-search-exclude markdown="1">



URI: [core:revision_label](https://w3id.org/collabri/core/revision_label)
<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [BudgetEntry](BudgetEntry.md) | One datestamped budget snapshot for a spending unit (TaskTeam, Subtask, or Pa... |  no  |






## Properties

### Type and Range

| Property | Value |
| --- | --- |
| Range | [String](String.md) |
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
| self | core:revision_label |
| native | core:revision_label |




## LinkML Source

<details>
```yaml
name: revision_label
description: Optional human label for this snapshot (e.g. "Initial proposal", "Post-Q&A
  revision", "Mod 0001 awarded", "FY26 Q2 close"). Useful when there are many same-typed
  entries.
in_subset:
- sow_spec
- execution_tracking
from_schema: https://w3id.org/collabri/core
rank: 1000
owner: BudgetEntry
domain_of:
- BudgetEntry
range: string

```
</details></div>