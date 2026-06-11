---
search:
  boost: 5.0
---

# Slot: activity_date 


_Date the activity was held._



<div data-search-exclude markdown="1">



URI: [core:activity_date](https://w3id.org/collabri/core/activity_date)
<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Activity](Activity.md) | An event-type deliverable (training, workshop, presentation) |  no  |






## Properties

### Type and Range

| Property | Value |
| --- | --- |
| Range | [Date](Date.md) |
| Domain Of | [Activity](Activity.md) |

### Cardinality and Requirements

| Property | Value |
| --- | --- |
### Slot Characteristics

| Property | Value |
| --- | --- |
| Owner | [Activity](Activity.md) |








## In Subsets


* [ExecutionTracking](ExecutionTracking.md)






## Identifier and Mapping Information





### Schema Source


* from schema: https://w3id.org/collabri/core




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | core:activity_date |
| native | core:activity_date |




## LinkML Source

<details>
```yaml
name: activity_date
description: Date the activity was held.
in_subset:
- execution_tracking
from_schema: https://w3id.org/collabri/core
rank: 1000
owner: Activity
domain_of:
- Activity
range: date

```
</details></div>