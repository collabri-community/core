---
search:
  boost: 5.0
---

# Slot: cost_basis 

<div data-search-exclude markdown="1">



URI: [core:cost_basis](https://w3id.org/collabri/core/cost_basis)
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
| self | core:cost_basis |
| native | core:cost_basis |




## LinkML Source

<details>
```yaml
name: cost_basis
domain_of:
- Payment
- BudgetEntry
range: string

```
</details></div>