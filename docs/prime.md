---
search:
  boost: 5.0
---

# Slot: prime 


_Prime contractor under this contract._



<div data-search-exclude markdown="1">



URI: [core:prime](https://w3id.org/collabri/core/prime)
<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [TaskTeam](TaskTeam.md) | Root of a Statement of Work, scoped to a single contract |  no  |






## Properties

### Type and Range

| Property | Value |
| --- | --- |
| Range | [Organization](Organization.md) |
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
| self | core:prime |
| native | core:prime |




## LinkML Source

<details>
```yaml
name: prime
description: Prime contractor under this contract.
in_subset:
- sow_spec
- execution_tracking
from_schema: https://w3id.org/collabri/core
rank: 1000
owner: TaskTeam
domain_of:
- TaskTeam
range: Organization

```
</details></div>