---
search:
  boost: 5.0
---

# Slot: payment 


_Optional payment obligation triggered by milestone acceptance._



<div data-search-exclude markdown="1">



URI: [core:payment](https://w3id.org/collabri/core/payment)
<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Milestone](Milestone.md) | A milestone groups subtasks (linked via Subtask |  no  |






## Properties

### Type and Range

| Property | Value |
| --- | --- |
| Range | [Payment](Payment.md) |
| Domain Of | [Milestone](Milestone.md) |

### Cardinality and Requirements

| Property | Value |
| --- | --- |
### Slot Characteristics

| Property | Value |
| --- | --- |
| Owner | [Milestone](Milestone.md) |








## In Subsets


* [SowSpec](SowSpec.md)
* [ExecutionTracking](ExecutionTracking.md)






## Identifier and Mapping Information





### Schema Source


* from schema: https://w3id.org/collabri/core




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | core:payment |
| native | core:payment |




## LinkML Source

<details>
```yaml
name: payment
description: Optional payment obligation triggered by milestone acceptance.
in_subset:
- sow_spec
- execution_tracking
from_schema: https://w3id.org/collabri/core
rank: 1000
owner: Milestone
domain_of:
- Milestone
range: Payment
inlined: true

```
</details></div>