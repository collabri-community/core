---
search:
  boost: 5.0
---

# Slot: contract_value 


_Headline contract value for convenience. The detailed, datestamped breakdown lives in budget_entries; contract_value should match the latest working-budget entry's headline total._



<div data-search-exclude markdown="1">



URI: [core:contract_value](https://w3id.org/collabri/core/contract_value)
<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [TaskTeam](TaskTeam.md) | Root of a Statement of Work, scoped to a single contract |  no  |






## Properties

### Type and Range

| Property | Value |
| --- | --- |
| Range | [Money](Money.md) |
| Domain Of | [TaskTeam](TaskTeam.md) |

### Cardinality and Requirements

| Property | Value |
| --- | --- |
### Slot Characteristics

| Property | Value |
| --- | --- |
| Owner | [TaskTeam](TaskTeam.md) |








## In Subsets


* [SowSpec](SowSpec.md)
* [ExecutionTracking](ExecutionTracking.md)






## Identifier and Mapping Information





### Schema Source


* from schema: https://w3id.org/collabri/core




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | core:contract_value |
| native | core:contract_value |




## LinkML Source

<details>
```yaml
name: contract_value
description: Headline contract value for convenience. The detailed, datestamped breakdown
  lives in budget_entries; contract_value should match the latest working-budget entry's
  headline total.
in_subset:
- sow_spec
- execution_tracking
from_schema: https://w3id.org/collabri/core
rank: 1000
owner: TaskTeam
domain_of:
- TaskTeam
range: Money
inlined: true

```
</details></div>