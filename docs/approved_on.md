---
search:
  boost: 5.0
---

# Slot: approved_on 


_Date the approval was recorded._



<div data-search-exclude markdown="1">



URI: [core:approved_on](https://w3id.org/collabri/core/approved_on)
<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Approval](Approval.md) | Signoff on a specific version of a SOW element |  no  |






## Properties

### Type and Range

| Property | Value |
| --- | --- |
| Range | [Date](Date.md) |
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
| self | core:approved_on |
| native | core:approved_on |




## LinkML Source

<details>
```yaml
name: approved_on
description: Date the approval was recorded.
in_subset:
- execution_tracking
from_schema: https://w3id.org/collabri/core
rank: 1000
owner: Approval
domain_of:
- Approval
range: date

```
</details></div>