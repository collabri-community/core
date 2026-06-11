---
search:
  boost: 5.0
---

# Slot: changes 


_Element-level changes bundled in this proposal._



<div data-search-exclude markdown="1">



URI: [core:changes](https://w3id.org/collabri/core/changes)
<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [ChangeProposal](ChangeProposal.md) | A bundled set of element-level Changes against a base SOW version, analogous ... |  no  |






## Properties

### Type and Range

| Property | Value |
| --- | --- |
| Range | [Change](Change.md) |
| Domain Of | [ChangeProposal](ChangeProposal.md) |

### Cardinality and Requirements

| Property | Value |
| --- | --- |
| Multivalued | Yes |
### Slot Characteristics

| Property | Value |
| --- | --- |
| Owner | [ChangeProposal](ChangeProposal.md) |








## In Subsets


* [ExecutionTracking](ExecutionTracking.md)






## Identifier and Mapping Information





### Schema Source


* from schema: https://w3id.org/collabri/core




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | core:changes |
| native | core:changes |




## LinkML Source

<details>
```yaml
name: changes
description: Element-level changes bundled in this proposal.
in_subset:
- execution_tracking
from_schema: https://w3id.org/collabri/core
rank: 1000
owner: ChangeProposal
domain_of:
- ChangeProposal
range: Change
multivalued: true
inlined: true
inlined_as_list: true

```
</details></div>