---
search:
  boost: 5.0
---

# Slot: percent_complete 


_For partial-completion payable subtasks (e.g. reports paid in stages), the current percent complete against the subtask's scope._



<div data-search-exclude markdown="1">



URI: [core:percent_complete](https://w3id.org/collabri/core/percent_complete)
<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Subtask](Subtask.md) | A step toward completion of a Task |  no  |






## Properties

### Type and Range

| Property | Value |
| --- | --- |
| Range | [Float](Float.md) |
| Domain Of | [Subtask](Subtask.md) |

### Cardinality and Requirements

| Property | Value |
| --- | --- |
### Slot Characteristics

| Property | Value |
| --- | --- |
| Owner | [Subtask](Subtask.md) |


### Value Constraints

| Property | Value |
| --- | --- |
| Minimum Value | 0 |
| Maximum Value | 100 |








## In Subsets


* [ExecutionTracking](ExecutionTracking.md)






## Identifier and Mapping Information





### Schema Source


* from schema: https://w3id.org/collabri/core




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | core:percent_complete |
| native | core:percent_complete |




## LinkML Source

<details>
```yaml
name: percent_complete
description: For partial-completion payable subtasks (e.g. reports paid in stages),
  the current percent complete against the subtask's scope.
in_subset:
- execution_tracking
from_schema: https://w3id.org/collabri/core
rank: 1000
owner: Subtask
domain_of:
- Subtask
range: float
minimum_value: 0
maximum_value: 100

```
</details></div>