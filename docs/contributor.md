---
search:
  boost: 5.0
---

# Slot: contributor 


_Person who made the contribution._



<div data-search-exclude markdown="1">



URI: [core:contributor](https://w3id.org/collabri/core/contributor)
<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Contribution](Contribution.md) | Contributor role on a deliverable, CRediT-aligned where applicable |  no  |






## Properties

### Type and Range

| Property | Value |
| --- | --- |
| Range | [Person](Person.md) |
| Domain Of | [Contribution](Contribution.md) |

### Cardinality and Requirements

| Property | Value |
| --- | --- |
| Required | Yes |
### Slot Characteristics

| Property | Value |
| --- | --- |
| Owner | [Contribution](Contribution.md) |








## In Subsets


* [ExecutionTracking](ExecutionTracking.md)






## Identifier and Mapping Information





### Schema Source


* from schema: https://w3id.org/collabri/core




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | core:contributor |
| native | core:contributor |




## LinkML Source

<details>
```yaml
name: contributor
description: Person who made the contribution.
in_subset:
- execution_tracking
from_schema: https://w3id.org/collabri/core
rank: 1000
owner: Contribution
domain_of:
- Contribution
range: Person
required: true

```
</details></div>