---
search:
  boost: 5.0
---

# Slot: attendee_count 


_Number of attendees (recorded post-event)._



<div data-search-exclude markdown="1">



URI: [core:attendee_count](https://w3id.org/collabri/core/attendee_count)
<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Activity](Activity.md) | An event-type deliverable (training, workshop, presentation) |  no  |






## Properties

### Type and Range

| Property | Value |
| --- | --- |
| Range | [Integer](Integer.md) |
| Domain Of | [Activity](Activity.md) |

### Cardinality and Requirements

| Property | Value |
| --- | --- |
### Slot Characteristics

| Property | Value |
| --- | --- |
| Owner | [Activity](Activity.md) |


### Value Constraints

| Property | Value |
| --- | --- |
| Minimum Value | 0 |








## In Subsets


* [ExecutionTracking](ExecutionTracking.md)






## Identifier and Mapping Information





### Schema Source


* from schema: https://w3id.org/collabri/core




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | core:attendee_count |
| native | core:attendee_count |




## LinkML Source

<details>
```yaml
name: attendee_count
description: Number of attendees (recorded post-event).
in_subset:
- execution_tracking
from_schema: https://w3id.org/collabri/core
rank: 1000
owner: Activity
domain_of:
- Activity
range: integer
minimum_value: 0

```
</details></div>