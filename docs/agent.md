---
search:
  boost: 5.0
---

# Slot: agent 


_The Organization or Person playing the party role._



<div data-search-exclude markdown="1">



URI: [core:agent](https://w3id.org/collabri/core/agent)
<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Party](Party.md) | A role-bearing entity in the contract (Organization or Person wrapped with a ... |  no  |






## Properties

### Type and Range

| Property | Value |
| --- | --- |
| Range | [Uriorcurie](Uriorcurie.md) |
| Domain Of | [Party](Party.md) |

### Cardinality and Requirements

| Property | Value |
| --- | --- |
| Required | Yes |
### Slot Characteristics

| Property | Value |
| --- | --- |
| Owner | [Party](Party.md) |








## In Subsets


* [SowSpec](SowSpec.md)
* [ExecutionTracking](ExecutionTracking.md)






## Identifier and Mapping Information





### Schema Source


* from schema: https://w3id.org/collabri/core




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | core:agent |
| native | core:agent |




## LinkML Source

<details>
```yaml
name: agent
description: The Organization or Person playing the party role.
in_subset:
- sow_spec
- execution_tracking
from_schema: https://w3id.org/collabri/core
rank: 1000
owner: Party
domain_of:
- Party
range: uriorcurie
required: true

```
</details></div>