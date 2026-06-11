---
search:
  boost: 5.0
---

# Slot: contracting_parties 


_All parties to the contract with their roles._



<div data-search-exclude markdown="1">



URI: [core:contracting_parties](https://w3id.org/collabri/core/contracting_parties)
<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [TaskTeam](TaskTeam.md) | Root of a Statement of Work, scoped to a single contract |  no  |






## Properties

### Type and Range

| Property | Value |
| --- | --- |
| Range | [Party](Party.md) |
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


* [SowSpec](SowSpec.md)
* [ExecutionTracking](ExecutionTracking.md)






## Identifier and Mapping Information





### Schema Source


* from schema: https://w3id.org/collabri/core




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | core:contracting_parties |
| native | core:contracting_parties |




## LinkML Source

<details>
```yaml
name: contracting_parties
description: All parties to the contract with their roles.
in_subset:
- sow_spec
- execution_tracking
from_schema: https://w3id.org/collabri/core
rank: 1000
owner: TaskTeam
domain_of:
- TaskTeam
range: Party
multivalued: true
inlined: true
inlined_as_list: true

```
</details></div>