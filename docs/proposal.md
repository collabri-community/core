---
search:
  boost: 5.0
---

# Slot: proposal 


_Foreign key to the upstream Proposal Intent record this contract derives from (pi:Proposal.id in the institution- agnostic Proposal Intent Core schema, https://w3id.org/tislab/ proposal-intent/core). Proposal Intent captures the pre-award information — sponsor, funding opportunity, PI roster, deadlines, subaward intentions — that becomes the working contract scope when awarded. Loose coupling by uriorcurie rather than inlining: the proposal and the TaskTeam live in different schemas and evolve independently, but link referentially so a contract instance can be traced back to its proposal of record._

_Cardinality is Proposal 1 : N TaskTeam. A single proposal commonly spans multiple task areas (a DARPA TA1/TA2/TA3 BAA, an NIH multi-aim grant, a multi-PI award with separable subscopes) and each awarded slice becomes its own TaskTeam. Use proposal_segment to label which slice this TaskTeam realizes._



<div data-search-exclude markdown="1">



URI: [core:proposal](https://w3id.org/collabri/core/proposal)
<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [TaskTeam](TaskTeam.md) | Root of a Statement of Work, scoped to a single contract |  no  |






## Properties

### Type and Range

| Property | Value |
| --- | --- |
| Range | [Uriorcurie](Uriorcurie.md) |
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
| self | core:proposal |
| native | core:proposal |
| close | dcterms:source, prov:wasDerivedFrom |




## LinkML Source

<details>
```yaml
name: proposal
description: 'Foreign key to the upstream Proposal Intent record this contract derives
  from (pi:Proposal.id in the institution- agnostic Proposal Intent Core schema, https://w3id.org/tislab/
  proposal-intent/core). Proposal Intent captures the pre-award information — sponsor,
  funding opportunity, PI roster, deadlines, subaward intentions — that becomes the
  working contract scope when awarded. Loose coupling by uriorcurie rather than inlining:
  the proposal and the TaskTeam live in different schemas and evolve independently,
  but link referentially so a contract instance can be traced back to its proposal
  of record.

  Cardinality is Proposal 1 : N TaskTeam. A single proposal commonly spans multiple
  task areas (a DARPA TA1/TA2/TA3 BAA, an NIH multi-aim grant, a multi-PI award with
  separable subscopes) and each awarded slice becomes its own TaskTeam. Use proposal_segment
  to label which slice this TaskTeam realizes.'
in_subset:
- sow_spec
- execution_tracking
from_schema: https://w3id.org/collabri/core
close_mappings:
- dcterms:source
- prov:wasDerivedFrom
rank: 1000
owner: TaskTeam
domain_of:
- TaskTeam
range: uriorcurie

```
</details></div>