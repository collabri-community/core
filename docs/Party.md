---
search:
  boost: 5.0
---

# Slot: party 


_Party the approver is signing on behalf of._



<div data-search-exclude markdown="1">



URI: [core:party](https://w3id.org/collabri/core/party)
<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Approval](Approval.md) | Signoff on a specific version of a SOW element |  no  |






## Properties

### Type and Range

| Property | Value |
| --- | --- |
| Range | [Party](Party.md) |
| Domain Of | [Approval](Approval.md) |

### Cardinality and Requirements

| Property | Value |
| --- | --- |
### Slot Characteristics

| Property | Value |
| --- | --- |
| Owner | [Approval](Approval.md) |








## In Subsets


* [ExecutionTracking](ExecutionTracking.md)






## Identifier and Mapping Information





### Schema Source


* from schema: https://w3id.org/collabri/core




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | core:party |
| native | core:party |




## LinkML Source

<details>
```yaml
name: party
description: Party the approver is signing on behalf of.
in_subset:
- execution_tracking
from_schema: https://w3id.org/collabri/core
rank: 1000
owner: Approval
domain_of:
- Approval
range: Party

```
</details></div>