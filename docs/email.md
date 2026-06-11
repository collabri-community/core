---
search:
  boost: 5.0
---

# Slot: email 


_Contact email._



<div data-search-exclude markdown="1">



URI: [schema:email](http://schema.org/email)
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
| Slot URI | [schema:email](http://schema.org/email) |

### Cardinality and Requirements

| Property | Value |
| --- | --- |
### Slot Characteristics

| Property | Value |
| --- | --- |
| Owner | [Person](Person.md) |


### Value Constraints

| Property | Value |
| --- | --- |
| Regex Pattern | `^\S+@\S+\.\S+$` |












## Identifier and Mapping Information





### Schema Source


* from schema: https://w3id.org/collabri/core




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | schema:email |
| native | core:email |
| exact | foaf:mbox |




## LinkML Source

<details>
```yaml
name: email
description: Contact email.
from_schema: https://w3id.org/collabri/core
exact_mappings:
- foaf:mbox
rank: 1000
slot_uri: schema:email
owner: Person
domain_of:
- Person
range: string
pattern: ^\S+@\S+\.\S+$

```
</details></div>