---
search:
  boost: 5.0
---

# Slot: notes 

<div data-search-exclude markdown="1">



URI: [core:notes](https://w3id.org/collabri/core/notes)
<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Objective](Objective.md) | The aim of a subtask — a single statement of what success means for this chun... |  no  |
| [BudgetEntry](BudgetEntry.md) | One datestamped budget snapshot for a spending unit (TaskTeam, Subtask, or Pa... |  no  |






## Properties

### Type and Range

| Property | Value |
| --- | --- |
| Range | [String](String.md) |
| Domain Of | [Objective](Objective.md), [BudgetEntry](BudgetEntry.md) |

### Cardinality and Requirements

| Property | Value |
| --- | --- |










## Identifier and Mapping Information






## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | core:notes |
| native | core:notes |




## LinkML Source

<details>
```yaml
name: notes
domain_of:
- Objective
- BudgetEntry
range: string

```
</details></div>