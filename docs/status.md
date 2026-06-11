---
search:
  boost: 5.0
---

# Slot: status 


_Lifecycle of this proposal (open, merged, closed, etc.)._



<div data-search-exclude markdown="1">



URI: [core:status](https://w3id.org/collabri/core/status)
<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [ChangeProposal](ChangeProposal.md) | A bundled set of element-level Changes against a base SOW version, analogous ... |  no  |






## Properties

### Type and Range

| Property | Value |
| --- | --- |
| Range | [ChangeProposalStatus](ChangeProposalStatus.md) |
| Domain Of | [ChangeProposal](ChangeProposal.md) |

### Cardinality and Requirements

| Property | Value |
| --- | --- |
| Required | Yes |
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
| self | core:status |
| native | core:status |




## LinkML Source

<details>
```yaml
name: status
description: Lifecycle of this proposal (open, merged, closed, etc.).
in_subset:
- execution_tracking
from_schema: https://w3id.org/collabri/core
rank: 1000
owner: ChangeProposal
domain_of:
- ChangeProposal
range: ChangeProposalStatus
required: true

```
</details></div>