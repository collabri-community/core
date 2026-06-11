---
search:
  boost: 5.0
---

# Slot: amount 


_The amount, with currency._



<div data-search-exclude markdown="1">



URI: [schema:price](http://schema.org/price)
<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [BudgetEntry](BudgetEntry.md) | One datestamped budget snapshot for a spending unit (TaskTeam, Subtask, or Pa... |  no  |






## Properties

### Type and Range

| Property | Value |
| --- | --- |
| Range | [Money](Money.md) |
| Domain Of | [BudgetEntry](BudgetEntry.md) |
| Slot URI | [schema:price](http://schema.org/price) |

### Cardinality and Requirements

| Property | Value |
| --- | --- |
| Required | Yes |
### Slot Characteristics

| Property | Value |
| --- | --- |
| Owner | [BudgetEntry](BudgetEntry.md) |








## In Subsets


* [SowSpec](SowSpec.md)
* [ExecutionTracking](ExecutionTracking.md)






## Identifier and Mapping Information





### Schema Source


* from schema: https://w3id.org/collabri/core




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | schema:price |
| native | core:amount |




## LinkML Source

<details>
```yaml
name: amount
description: The amount, with currency.
in_subset:
- sow_spec
- execution_tracking
from_schema: https://w3id.org/collabri/core
rank: 1000
slot_uri: schema:price
owner: BudgetEntry
domain_of:
- BudgetEntry
range: Money
required: true
inlined: true

```
</details></div>