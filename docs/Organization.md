---
search:
  boost: 5.0
---

# Slot: organization 


_Specific organization this entry breaks out, on multi-org payable subtasks. Omit for totals not broken down by org._



<div data-search-exclude markdown="1">



URI: [org:organization](http://www.w3.org/ns/org#organization)
<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [BudgetEntry](BudgetEntry.md) | One datestamped budget snapshot for a spending unit (TaskTeam, Subtask, or Pa... |  no  |






## Properties

### Type and Range

| Property | Value |
| --- | --- |
| Range | [Organization](Organization.md) |
| Domain Of | [BudgetEntry](BudgetEntry.md) |
| Slot URI | [org:organization](http://www.w3.org/ns/org#organization) |

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
| self | org:organization |
| native | core:organization |




## LinkML Source

<details>
```yaml
name: organization
description: Specific organization this entry breaks out, on multi-org payable subtasks.
  Omit for totals not broken down by org.
in_subset:
- sow_spec
- execution_tracking
from_schema: https://w3id.org/collabri/core
rank: 1000
slot_uri: org:organization
owner: BudgetEntry
domain_of:
- BudgetEntry
range: Organization

```
</details></div>