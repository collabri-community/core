---
search:
  boost: 5.0
---

# Slot: objective 


_The aim of this subtask — what success looks like, expressed once, independent of any specific deliverable. Optional but strongly encouraged: setting it explicitly is what prevents the 90%-overlap-with-deliverable failure mode._



<div data-search-exclude markdown="1">



URI: [core:objective](https://w3id.org/collabri/core/objective)
<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Subtask](Subtask.md) | A step toward completion of a Task |  no  |






## Properties

### Type and Range

| Property | Value |
| --- | --- |
| Range | [Objective](Objective.md) |
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
| self | core:objective |
| native | core:objective |
| close | schema:purpose |




## LinkML Source

<details>
```yaml
name: objective
description: 'The aim of this subtask — what success looks like, expressed once, independent
  of any specific deliverable. Optional but strongly encouraged: setting it explicitly
  is what prevents the 90%-overlap-with-deliverable failure mode.'
in_subset:
- sow_spec
- execution_tracking
from_schema: https://w3id.org/collabri/core
close_mappings:
- schema:purpose
rank: 1000
owner: Subtask
domain_of:
- Subtask
range: Objective
inlined: true

```
</details></div>