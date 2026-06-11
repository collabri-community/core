---
search:
  boost: 5.0
---

# Slot: entry_type 


_Which budget view this entry represents._



<div data-search-exclude markdown="1">



URI: [core:entry_type](https://w3id.org/collabri/core/entry_type)
<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [BudgetEntry](BudgetEntry.md) | One datestamped budget snapshot for a spending unit (TaskTeam, Subtask, or Pa... |  no  |






## Properties

### Type and Range

| Property | Value |
| --- | --- |
| Range | [BudgetEntryType](BudgetEntryType.md) |
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
| self | core:entry_type |
| native | core:entry_type |




## LinkML Source

<details>
```yaml
name: entry_type
description: Which budget view this entry represents.
in_subset:
- sow_spec
- execution_tracking
from_schema: https://w3id.org/collabri/core
rank: 1000
owner: BudgetEntry
domain_of:
- BudgetEntry
range: BudgetEntryType
required: true

```
</details></div>