---
search:
  boost: 5.0
---

# Slot: currency 


_ISO 4217 currency code._



<div data-search-exclude markdown="1">



URI: [schema:currency](http://schema.org/currency)
<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Money](Money.md) | A monetary amount with currency |  no  |






## Properties

### Type and Range

| Property | Value |
| --- | --- |
| Range | [String](String.md) |
| Domain Of | [Money](Money.md) |
| Slot URI | [schema:currency](http://schema.org/currency) |

### Cardinality and Requirements

| Property | Value |
| --- | --- |
### Slot Characteristics

| Property | Value |
| --- | --- |
| If Absent | `string(USD)` |
| Owner | [Money](Money.md) |


### Value Constraints

| Property | Value |
| --- | --- |
| Regex Pattern | `^[A-Z]{3}$` |












## Identifier and Mapping Information





### Schema Source


* from schema: https://w3id.org/collabri/core




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | schema:currency |
| native | core:currency |




## LinkML Source

<details>
```yaml
name: currency
description: ISO 4217 currency code.
from_schema: https://w3id.org/collabri/core
rank: 1000
slot_uri: schema:currency
ifabsent: string(USD)
owner: Money
domain_of:
- Money
range: string
pattern: ^[A-Z]{3}$

```
</details></div>