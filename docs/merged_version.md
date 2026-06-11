---
search:
  boost: 5.0
---

# Slot: merged_version 


_Resulting SOW semver after merge._



<div data-search-exclude markdown="1">



URI: [core:merged_version](https://w3id.org/collabri/core/merged_version)
<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [ChangeProposal](ChangeProposal.md) | A bundled set of element-level Changes against a base SOW version, analogous ... |  no  |






## Properties

### Type and Range

| Property | Value |
| --- | --- |
| Range | [String](String.md) |
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
| self | core:merged_version |
| native | core:merged_version |




## LinkML Source

<details>
```yaml
name: merged_version
description: Resulting SOW semver after merge.
in_subset:
- execution_tracking
from_schema: https://w3id.org/collabri/core
rank: 1000
owner: ChangeProposal
domain_of:
- ChangeProposal
range: string

```
</details></div>