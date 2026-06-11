---
search:
  boost: 5.0
---

# Slot: proposed_by 


_Author of the proposal._



<div data-search-exclude markdown="1">



URI: [core:proposed_by](https://w3id.org/collabri/core/proposed_by)
<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [ChangeProposal](ChangeProposal.md) | A bundled set of element-level Changes against a base SOW version, analogous ... |  no  |






## Properties

### Type and Range

| Property | Value |
| --- | --- |
| Range | [Uriorcurie](Uriorcurie.md) |
| Domain Of | [ChangeProposal](ChangeProposal.md) |

### Cardinality and Requirements

| Property | Value |
| --- | --- |
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
| self | core:proposed_by |
| native | core:proposed_by |




## LinkML Source

<details>
```yaml
name: proposed_by
description: Author of the proposal.
in_subset:
- execution_tracking
from_schema: https://w3id.org/collabri/core
rank: 1000
owner: ChangeProposal
domain_of:
- ChangeProposal
range: uriorcurie

```
</details></div>