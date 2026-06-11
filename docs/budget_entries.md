---
search:
  boost: 5.0
---

# Slot: budget_entries 

<div data-search-exclude markdown="1">



URI: [core:budget_entries](https://w3id.org/collabri/core/budget_entries)
<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [TaskTeam](TaskTeam.md) | Root of a Statement of Work, scoped to a single contract |  no  |
| [Subtask](Subtask.md) | A step toward completion of a Task |  no  |
| [Payment](Payment.md) | Payment obligation tied to milestone acceptance |  no  |






## Properties

### Type and Range

| Property | Value |
| --- | --- |
| Range | [String](String.md) |
| Domain Of | [TaskTeam](TaskTeam.md), [Subtask](Subtask.md), [Payment](Payment.md) |

### Cardinality and Requirements

| Property | Value |
| --- | --- |










## Identifier and Mapping Information






## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | core:budget_entries |
| native | core:budget_entries |




## LinkML Source

<details>
```yaml
name: budget_entries
domain_of:
- TaskTeam
- Subtask
- Payment
range: string

```
</details></div>