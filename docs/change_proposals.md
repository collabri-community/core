---
search:
  boost: 5.0
---

# Slot: change_proposals 


_Open and historical change proposals against this SOW._



<div data-search-exclude markdown="1">



URI: [core:change_proposals](https://w3id.org/collabri/core/change_proposals)
<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [TaskTeam](TaskTeam.md) | Root of a Statement of Work, scoped to a single contract |  no  |






## Properties

### Type and Range

| Property | Value |
| --- | --- |
| Range | [ChangeProposal](ChangeProposal.md) |
| Domain Of | [TaskTeam](TaskTeam.md) |

### Cardinality and Requirements

| Property | Value |
| --- | --- |
| Multivalued | Yes |
### Slot Characteristics

| Property | Value |
| --- | --- |
| Owner | [TaskTeam](TaskTeam.md) |








## In Subsets


* [ExecutionTracking](ExecutionTracking.md)






## Identifier and Mapping Information





### Schema Source


* from schema: https://w3id.org/collabri/core




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | core:change_proposals |
| native | core:change_proposals |




## LinkML Source

<details>
```yaml
name: change_proposals
description: Open and historical change proposals against this SOW.
in_subset:
- execution_tracking
from_schema: https://w3id.org/collabri/core
rank: 1000
owner: TaskTeam
domain_of:
- TaskTeam
range: ChangeProposal
multivalued: true
inlined: true
inlined_as_list: true

```
</details></div>