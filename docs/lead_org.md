---
search:
  boost: 5.0
---

# Slot: lead_org 


_The organization accountable for delivering this subtask._



<div data-search-exclude markdown="1">



URI: [prov:wasAssociatedWith](http://www.w3.org/ns/prov#wasAssociatedWith)
<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Subtask](Subtask.md) | A step toward completion of a Task |  no  |






## Properties

### Type and Range

| Property | Value |
| --- | --- |
| Range | [Organization](Organization.md) |
| Domain Of | [Subtask](Subtask.md) |
| Slot URI | [prov:wasAssociatedWith](http://www.w3.org/ns/prov#wasAssociatedWith) |

### Cardinality and Requirements

| Property | Value |
| --- | --- |
### Slot Characteristics

| Property | Value |
| --- | --- |
| Owner | [Subtask](Subtask.md) |








## In Subsets


* [ExecutionTracking](ExecutionTracking.md)






## Identifier and Mapping Information





### Schema Source


* from schema: https://w3id.org/collabri/core




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | prov:wasAssociatedWith |
| native | core:lead_org |




## LinkML Source

<details>
```yaml
name: lead_org
description: The organization accountable for delivering this subtask.
in_subset:
- execution_tracking
from_schema: https://w3id.org/collabri/core
rank: 1000
slot_uri: prov:wasAssociatedWith
owner: Subtask
domain_of:
- Subtask
range: Organization

```
</details></div>