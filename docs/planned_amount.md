---
search:
  boost: 5.0
---

# Slot: planned_amount 


_Headline planned payment amount on milestone acceptance. The full datestamped budget history lives in budget_entries; this slot is a convenience that should match the latest working-budget entry._



<div data-search-exclude markdown="1">



URI: [core:planned_amount](https://w3id.org/collabri/core/planned_amount)
<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Payment](Payment.md) | Payment obligation tied to milestone acceptance |  no  |






## Properties

### Type and Range

| Property | Value |
| --- | --- |
| Range | [Money](Money.md) |
| Domain Of | [Payment](Payment.md) |

### Cardinality and Requirements

| Property | Value |
| --- | --- |
### Slot Characteristics

| Property | Value |
| --- | --- |
| Owner | [Payment](Payment.md) |








## In Subsets


* [SowSpec](SowSpec.md)
* [ExecutionTracking](ExecutionTracking.md)






## Identifier and Mapping Information





### Schema Source


* from schema: https://w3id.org/collabri/core




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | core:planned_amount |
| native | core:planned_amount |




## LinkML Source

<details>
```yaml
name: planned_amount
description: Headline planned payment amount on milestone acceptance. The full datestamped
  budget history lives in budget_entries; this slot is a convenience that should match
  the latest working-budget entry.
in_subset:
- sow_spec
- execution_tracking
from_schema: https://w3id.org/collabri/core
rank: 1000
owner: Payment
domain_of:
- Payment
range: Money
inlined: true

```
</details></div>