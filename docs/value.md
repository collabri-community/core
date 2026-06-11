---
search:
  boost: 5.0
---

# Slot: value 


_The numeric amount._



<div data-search-exclude markdown="1">



URI: [schema:value](http://schema.org/value)
<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Money](Money.md) | A monetary amount with currency |  no  |






## Properties

### Type and Range

| Property | Value |
| --- | --- |
| Range | [Decimal](Decimal.md) |
| Domain Of | [Money](Money.md) |
| Slot URI | [schema:value](http://schema.org/value) |

### Cardinality and Requirements

| Property | Value |
| --- | --- |
| Required | Yes |
### Slot Characteristics

| Property | Value |
| --- | --- |
| Owner | [Money](Money.md) |


### Value Constraints

| Property | Value |
| --- | --- |
| Minimum Value | 0 |












## Identifier and Mapping Information





### Schema Source


* from schema: https://w3id.org/collabri/core




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | schema:value |
| native | core:value |




## LinkML Source

<details>
```yaml
name: value
description: The numeric amount.
from_schema: https://w3id.org/collabri/core
rank: 1000
slot_uri: schema:value
owner: Money
domain_of:
- Money
range: decimal
required: true
minimum_value: 0

```
</details></div>