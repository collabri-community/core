---
search:
  boost: 5.0
---

# Slot: milestone 


_Milestone whose acceptance gates contractual events (e.g. payment) for this subtask. Referenced by id; the Milestone itself is defined on TaskTeam.milestones._



<div data-search-exclude markdown="1">



URI: [core:milestone](https://w3id.org/collabri/core/milestone)
<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Subtask](Subtask.md) | A step toward completion of a Task |  no  |






## Properties

### Type and Range

| Property | Value |
| --- | --- |
| Range | [Milestone](Milestone.md) |
| Domain Of | [Subtask](Subtask.md) |

### Cardinality and Requirements

| Property | Value |
| --- | --- |
### Slot Characteristics

| Property | Value |
| --- | --- |
| Owner | [Subtask](Subtask.md) |








## In Subsets


* [SowSpec](SowSpec.md)
* [ExecutionTracking](ExecutionTracking.md)






## Identifier and Mapping Information





### Schema Source


* from schema: https://w3id.org/collabri/core




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | core:milestone |
| native | core:milestone |




## LinkML Source

<details>
```yaml
name: milestone
description: Milestone whose acceptance gates contractual events (e.g. payment) for
  this subtask. Referenced by id; the Milestone itself is defined on TaskTeam.milestones.
in_subset:
- sow_spec
- execution_tracking
from_schema: https://w3id.org/collabri/core
rank: 1000
owner: Subtask
domain_of:
- Subtask
range: Milestone

```
</details></div>