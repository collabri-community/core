---
search:
  boost: 5.0
---

# Slot: target_date 


_Target calendar date for this milestone._



<div data-search-exclude markdown="1">



URI: [core:target_date](https://w3id.org/collabri/core/target_date)
<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Milestone](Milestone.md) | A milestone groups subtasks (linked via Subtask |  no  |






## Properties

### Type and Range

| Property | Value |
| --- | --- |
| Range | [Date](Date.md) |
| Domain Of | [Milestone](Milestone.md) |

### Cardinality and Requirements

| Property | Value |
| --- | --- |
### Slot Characteristics

| Property | Value |
| --- | --- |
| Owner | [Milestone](Milestone.md) |








## In Subsets


* [SowSpec](SowSpec.md)
* [ExecutionTracking](ExecutionTracking.md)






## Identifier and Mapping Information





### Schema Source


* from schema: https://w3id.org/collabri/core




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | core:target_date |
| native | core:target_date |




## LinkML Source

<details>
```yaml
name: target_date
description: Target calendar date for this milestone.
in_subset:
- sow_spec
- execution_tracking
from_schema: https://w3id.org/collabri/core
rank: 1000
owner: Milestone
domain_of:
- Milestone
range: date

```
</details></div>