---
search:
  boost: 5.0
---

# Slot: location 


_Location (physical or virtual) of the activity._



<div data-search-exclude markdown="1">



URI: [core:location](https://w3id.org/collabri/core/location)
<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Activity](Activity.md) | An event-type deliverable (training, workshop, presentation) |  no  |






## Properties

### Type and Range

| Property | Value |
| --- | --- |
| Range | [String](String.md) |
| Domain Of | [Activity](Activity.md) |

### Cardinality and Requirements

| Property | Value |
| --- | --- |
### Slot Characteristics

| Property | Value |
| --- | --- |
| Owner | [Activity](Activity.md) |








## In Subsets


* [SowSpec](SowSpec.md)
* [ExecutionTracking](ExecutionTracking.md)






## Identifier and Mapping Information





### Schema Source


* from schema: https://w3id.org/collabri/core




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | core:location |
| native | core:location |




## LinkML Source

<details>
```yaml
name: location
description: Location (physical or virtual) of the activity.
in_subset:
- sow_spec
- execution_tracking
from_schema: https://w3id.org/collabri/core
rank: 1000
owner: Activity
domain_of:
- Activity
range: string

```
</details></div>