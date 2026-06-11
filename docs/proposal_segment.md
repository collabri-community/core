---
search:
  boost: 5.0
---

# Slot: proposal_segment 


_Identifier of the slice of the upstream proposal this TaskTeam realizes. Used when a single Proposal yields multiple TaskTeams (multi-TA BAAs, multi-aim grants, multi-PI awards). Free-text by convention — typical values are domain-specific strings the proposal itself used: "TA1", "TA2", "Aim 1", "Aim 2", "Work Package C", "Subproject A". Becomes a uriorcurie when the upstream Proposal Intent schema starts modelling task areas / aims as structured entries; for now it stays a string so it can carry whatever the proposal said._



<div data-search-exclude markdown="1">



URI: [core:proposal_segment](https://w3id.org/collabri/core/proposal_segment)
<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [TaskTeam](TaskTeam.md) | Root of a Statement of Work, scoped to a single contract |  no  |






## Properties

### Type and Range

| Property | Value |
| --- | --- |
| Range | [String](String.md) |
| Domain Of | [TaskTeam](TaskTeam.md) |

### Cardinality and Requirements

| Property | Value |
| --- | --- |
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
| self | core:proposal_segment |
| native | core:proposal_segment |
| close | dcterms:isPartOf |




## LinkML Source

<details>
```yaml
name: proposal_segment
description: 'Identifier of the slice of the upstream proposal this TaskTeam realizes.
  Used when a single Proposal yields multiple TaskTeams (multi-TA BAAs, multi-aim
  grants, multi-PI awards). Free-text by convention — typical values are domain-specific
  strings the proposal itself used: "TA1", "TA2", "Aim 1", "Aim 2", "Work Package
  C", "Subproject A". Becomes a uriorcurie when the upstream Proposal Intent schema
  starts modelling task areas / aims as structured entries; for now it stays a string
  so it can carry whatever the proposal said.'
in_subset:
- sow_spec
- execution_tracking
from_schema: https://w3id.org/collabri/core
close_mappings:
- dcterms:isPartOf
rank: 1000
owner: TaskTeam
domain_of:
- TaskTeam
range: string

```
</details></div>