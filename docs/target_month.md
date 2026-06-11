---
search:
  boost: 5.0
---

# Slot: target_month 


_Target month (since program start) for this milestone._



<div data-search-exclude markdown="1">



URI: [core:target_month](https://w3id.org/collabri/core/target_month)
<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Milestone](Milestone.md) | A milestone groups subtasks (linked via Subtask |  no  |






## Properties

### Type and Range

| Property | Value |
| --- | --- |
| Range | [Integer](Integer.md) |
| Domain Of | [Milestone](Milestone.md) |

### Cardinality and Requirements

| Property | Value |
| --- | --- |
### Slot Characteristics

| Property | Value |
| --- | --- |
| Owner | [Milestone](Milestone.md) |


### Value Constraints

| Property | Value |
| --- | --- |
| Minimum Value | 1 |








## In Subsets


* [SowSpec](SowSpec.md)
* [ExecutionTracking](ExecutionTracking.md)






## Identifier and Mapping Information





### Schema Source


* from schema: https://w3id.org/collabri/core




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | core:target_month |
| native | core:target_month |




## LinkML Source

<details>
```yaml
name: target_month
description: Target month (since program start) for this milestone.
in_subset:
- sow_spec
- execution_tracking
from_schema: https://w3id.org/collabri/core
rank: 1000
owner: Milestone
domain_of:
- Milestone
range: integer
minimum_value: 1

```
</details></div>