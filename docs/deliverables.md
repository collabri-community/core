---
search:
  boost: 5.0
---

# Slot: deliverables 


_Deliverables produced by this subtask. Required (one or more) when the subtask is sponsor- or prime-payable._



<div data-search-exclude markdown="1">



URI: [prov:generated](http://www.w3.org/ns/prov#generated)
<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Subtask](Subtask.md) | A step toward completion of a Task |  no  |






## Properties

### Type and Range

| Property | Value |
| --- | --- |
| Range | [Deliverable](Deliverable.md) |
| Domain Of | [Subtask](Subtask.md) |
| Slot URI | [prov:generated](http://www.w3.org/ns/prov#generated) |

### Cardinality and Requirements

| Property | Value |
| --- | --- |
| Multivalued | Yes |
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
| self | prov:generated |
| native | core:deliverables |




## LinkML Source

<details>
```yaml
name: deliverables
description: Deliverables produced by this subtask. Required (one or more) when the
  subtask is sponsor- or prime-payable.
in_subset:
- sow_spec
- execution_tracking
from_schema: https://w3id.org/collabri/core
rank: 1000
slot_uri: prov:generated
owner: Subtask
domain_of:
- Subtask
range: Deliverable
multivalued: true
inlined: true
inlined_as_list: true

```
</details></div>