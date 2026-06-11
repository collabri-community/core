---
search:
  boost: 5.0
---

# Slot: spans_full_award 


_True if the task spans the entire period of performance._



<div data-search-exclude markdown="1">



URI: [core:spans_full_award](https://w3id.org/collabri/core/spans_full_award)
<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Task](Task.md) | Thematic bucket of work, possibly spanning the full award |  no  |






## Properties

### Type and Range

| Property | Value |
| --- | --- |
| Range | [Boolean](Boolean.md) |
| Domain Of | [Task](Task.md) |

### Cardinality and Requirements

| Property | Value |
| --- | --- |
### Slot Characteristics

| Property | Value |
| --- | --- |
| Owner | [Task](Task.md) |








## In Subsets


* [SowSpec](SowSpec.md)
* [ExecutionTracking](ExecutionTracking.md)






## Identifier and Mapping Information





### Schema Source


* from schema: https://w3id.org/collabri/core




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | core:spans_full_award |
| native | core:spans_full_award |




## LinkML Source

<details>
```yaml
name: spans_full_award
description: True if the task spans the entire period of performance.
in_subset:
- sow_spec
- execution_tracking
from_schema: https://w3id.org/collabri/core
rank: 1000
owner: Task
domain_of:
- Task
range: boolean

```
</details></div>