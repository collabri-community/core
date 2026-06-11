---
search:
  boost: 5.0
---

# Slot: payable_by 


_Which parties owe payment on acceptance of the milestone gating this subtask. Absent or empty means non-payable. Include "sponsor" for sponsor-payable, "prime" for prime-payable, or both. The MUST rule that payable subtasks require a deliverable is machine-enforced through this enum slot._



<div data-search-exclude markdown="1">



URI: [core:payable_by](https://w3id.org/collabri/core/payable_by)
<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Subtask](Subtask.md) | A step toward completion of a Task |  no  |






## Properties

### Type and Range

| Property | Value |
| --- | --- |
| Range | [PayerType](PayerType.md) |
| Domain Of | [Subtask](Subtask.md) |

### Cardinality and Requirements

| Property | Value |
| --- | --- |
| Multivalued | Yes |
### Slot Characteristics

| Property | Value |
| --- | --- |
| Owner | [Subtask](Subtask.md) |








## In Subsets


* [SowSpec](SowSpec.md)
* [ExecutionTracking](ExecutionTracking.md)






## Identifier and Mapping Information





### Schema Source


* from schema: https://w3id.org/collabri/core




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | core:payable_by |
| native | core:payable_by |
| close | fibo_ctr:hasContractParty |




## LinkML Source

<details>
```yaml
name: payable_by
description: Which parties owe payment on acceptance of the milestone gating this
  subtask. Absent or empty means non-payable. Include "sponsor" for sponsor-payable,
  "prime" for prime-payable, or both. The MUST rule that payable subtasks require
  a deliverable is machine-enforced through this enum slot.
in_subset:
- sow_spec
- execution_tracking
from_schema: https://w3id.org/collabri/core
close_mappings:
- fibo_ctr:hasContractParty
rank: 1000
owner: Subtask
domain_of:
- Subtask
range: PayerType
multivalued: true

```
</details></div>