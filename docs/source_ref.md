---
search:
  boost: 5.0
---

# Slot: source_ref 


_Pointer to the document or accounting record this entry derives from — a ChangeProposal IRI, an award-mod number, an AP ledger entry, etc. Becomes the audit trail for the snapshot._



<div data-search-exclude markdown="1">



URI: [core:source_ref](https://w3id.org/collabri/core/source_ref)
<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [BudgetEntry](BudgetEntry.md) | One datestamped budget snapshot for a spending unit (TaskTeam, Subtask, or Pa... |  no  |






## Properties

### Type and Range

| Property | Value |
| --- | --- |
| Range | [String](String.md) |
| Domain Of | [BudgetEntry](BudgetEntry.md) |

### Cardinality and Requirements

| Property | Value |
| --- | --- |
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
| self | core:source_ref |
| native | core:source_ref |




## LinkML Source

<details>
```yaml
name: source_ref
description: Pointer to the document or accounting record this entry derives from
  — a ChangeProposal IRI, an award-mod number, an AP ledger entry, etc. Becomes the
  audit trail for the snapshot.
in_subset:
- sow_spec
- execution_tracking
from_schema: https://w3id.org/collabri/core
rank: 1000
owner: BudgetEntry
domain_of:
- BudgetEntry
range: string

```
</details></div>