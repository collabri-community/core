---
search:
  boost: 5.0
---

# Slot: milestones 


_Milestones defined at the SOW level (referenced by subtasks)._



<div data-search-exclude markdown="1">



URI: [core:milestones](https://w3id.org/collabri/core/milestones)
<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [TaskTeam](TaskTeam.md) | Root of a Statement of Work, scoped to a single contract |  no  |






## Properties

### Type and Range

| Property | Value |
| --- | --- |
| Range | [Milestone](Milestone.md) |
| Domain Of | [TaskTeam](TaskTeam.md) |

### Cardinality and Requirements

| Property | Value |
| --- | --- |
| Multivalued | Yes |
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
| self | core:milestones |
| native | core:milestones |




## LinkML Source

<details>
```yaml
name: milestones
description: Milestones defined at the SOW level (referenced by subtasks).
in_subset:
- sow_spec
- execution_tracking
from_schema: https://w3id.org/collabri/core
rank: 1000
owner: TaskTeam
domain_of:
- TaskTeam
range: Milestone
multivalued: true
inlined: true
inlined_as_list: true

```
</details></div>