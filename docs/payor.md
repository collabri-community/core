---
search:
  boost: 5.0
---

# Slot: payor 

<div data-search-exclude markdown="1">



URI: [core:payor](https://w3id.org/collabri/core/payor)
<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Payment](Payment.md) | Payment obligation tied to milestone acceptance |  no  |
| [BudgetEntry](BudgetEntry.md) | One datestamped budget snapshot for a spending unit (TaskTeam, Subtask, or Pa... |  no  |






## Properties

### Type and Range

| Property | Value |
| --- | --- |
| Range | [String](String.md) |
| Domain Of | [Payment](Payment.md), [BudgetEntry](BudgetEntry.md) |

### Cardinality and Requirements

| Property | Value |
| --- | --- |










## Identifier and Mapping Information






## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | core:payor |
| native | core:payor |




## LinkML Source

<details>
```yaml
name: payor
domain_of:
- Payment
- BudgetEntry
range: string

```
</details></div>