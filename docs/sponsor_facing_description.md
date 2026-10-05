---
search:
  boost: 5.0
---

# Slot: sponsor_facing_description 


_Narrative of this subtask written for the sponsor. This is the description a sponsor report prints. When omitted, use description. Do not store this text on objective.notes._



<div data-search-exclude markdown="1">



URI: [core:sponsor_facing_description](https://w3id.org/collabri/core/sponsor_facing_description)
<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Subtask](Subtask.md) | A step toward completion of a Task |  no  |






## Properties

### Type and Range

| Property | Value |
| --- | --- |
| Range | [String](String.md) |
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
| self | core:sponsor_facing_description |
| native | core:sponsor_facing_description |




## LinkML Source

<details>
```yaml
name: sponsor_facing_description
description: Narrative of this subtask written for the sponsor. This is the description
  a sponsor report prints. When omitted, use description. Do not store this text on
  objective.notes.
in_subset:
- sow_spec
- execution_tracking
from_schema: https://w3id.org/collabri/core
rank: 1000
owner: Subtask
domain_of:
- Subtask
range: string

```
</details></div>