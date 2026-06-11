---
search:
  boost: 5.0
---

# Slot: affiliation 


_The organization this person belongs to._



<div data-search-exclude markdown="1">



URI: [schema:affiliation](http://schema.org/affiliation)
<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Person](Person.md) | A person who can be assigned as a lead or contributor |  no  |






## Properties

### Type and Range

| Property | Value |
| --- | --- |
| Range | [Organization](Organization.md) |
| Domain Of | [Person](Person.md) |
| Slot URI | [schema:affiliation](http://schema.org/affiliation) |

### Cardinality and Requirements

| Property | Value |
| --- | --- |
### Slot Characteristics

| Property | Value |
| --- | --- |
| Owner | [Person](Person.md) |








## In Subsets


* [SowSpec](SowSpec.md)
* [ExecutionTracking](ExecutionTracking.md)






## Identifier and Mapping Information





### Schema Source


* from schema: https://w3id.org/collabri/core




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | schema:affiliation |
| native | core:affiliation |




## LinkML Source

<details>
```yaml
name: affiliation
description: The organization this person belongs to.
in_subset:
- sow_spec
- execution_tracking
from_schema: https://w3id.org/collabri/core
rank: 1000
slot_uri: schema:affiliation
owner: Person
domain_of:
- Person
range: Organization

```
</details></div>