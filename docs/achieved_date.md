---
search:
  boost: 5.0
---

# Slot: achieved_date 


_Date the milestone was achieved._



<div data-search-exclude markdown="1">



URI: [core:achieved_date](https://w3id.org/collabri/core/achieved_date)
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


* [ExecutionTracking](ExecutionTracking.md)






## Identifier and Mapping Information





### Schema Source


* from schema: https://w3id.org/collabri/core




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | core:achieved_date |
| native | core:achieved_date |




## LinkML Source

<details>
```yaml
name: achieved_date
description: Date the milestone was achieved.
in_subset:
- execution_tracking
from_schema: https://w3id.org/collabri/core
rank: 1000
owner: Milestone
domain_of:
- Milestone
range: date

```
</details></div>