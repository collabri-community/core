---
search:
  boost: 5.0
---

# Slot: decision 


_For decision-type milestones (e.g. go/no-go gates), the recorded decision outcome._



<div data-search-exclude markdown="1">



URI: [core:decision](https://w3id.org/collabri/core/decision)
<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Milestone](Milestone.md) | A milestone groups subtasks (linked via Subtask |  no  |






## Properties

### Type and Range

| Property | Value |
| --- | --- |
| Range | [String](String.md) |
| Domain Of | [Milestone](Milestone.md) |

### Cardinality and Requirements

| Property | Value |
| --- | --- |
### Slot Characteristics

| Property | Value |
| --- | --- |
| Owner | [Milestone](Milestone.md) |








## In Subsets


* [ExecutionTracking](ExecutionTracking.md)






## Identifier and Mapping Information





### Schema Source


* from schema: https://w3id.org/collabri/core




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | core:decision |
| native | core:decision |




## LinkML Source

<details>
```yaml
name: decision
description: For decision-type milestones (e.g. go/no-go gates), the recorded decision
  outcome.
in_subset:
- execution_tracking
from_schema: https://w3id.org/collabri/core
rank: 1000
owner: Milestone
domain_of:
- Milestone
range: string

```
</details></div>