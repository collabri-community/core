---
search:
  boost: 5.0
---

# Slot: orcid 


_ORCID identifier._



<div data-search-exclude markdown="1">



URI: [schema:identifier](http://schema.org/identifier)
<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Person](Person.md) | A person who can be assigned as a lead or contributor |  no  |






## Properties

### Type and Range

| Property | Value |
| --- | --- |
| Range | [String](String.md) |
| Domain Of | [Person](Person.md) |
| Slot URI | [schema:identifier](http://schema.org/identifier) |

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
| self | schema:identifier |
| native | core:orcid |




## LinkML Source

<details>
```yaml
name: orcid
description: ORCID identifier.
in_subset:
- sow_spec
- execution_tracking
from_schema: https://w3id.org/collabri/core
rank: 1000
slot_uri: schema:identifier
owner: Person
domain_of:
- Person
range: string

```
</details></div>