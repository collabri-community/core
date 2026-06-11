---
search:
  boost: 5.0
---

# Slot: obligation_class 


_Discriminator for the concrete Obligation subclass._



<div data-search-exclude markdown="1">



URI: [core:obligation_class](https://w3id.org/collabri/core/obligation_class)
<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Obligation](Obligation.md) | Abstract base for any contractual duty (ODRL pattern) |  no  |
| [Payment](Payment.md) | Payment obligation tied to milestone acceptance |  no  |
| [ReportingObligation](ReportingObligation.md) | Recurring reporting duty (quarterly progress report, annual technical report,... |  no  |






## Properties

### Type and Range

| Property | Value |
| --- | --- |
| Range | [String](String.md) |
| Domain Of | [Obligation](Obligation.md) |

### Cardinality and Requirements

| Property | Value |
| --- | --- |
### Slot Characteristics

| Property | Value |
| --- | --- |
| Owner | [Obligation](Obligation.md) |








## In Subsets


* [SowSpec](SowSpec.md)
* [ExecutionTracking](ExecutionTracking.md)






## Identifier and Mapping Information





### Schema Source


* from schema: https://w3id.org/collabri/core




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | core:obligation_class |
| native | core:obligation_class |




## LinkML Source

<details>
```yaml
name: obligation_class
description: Discriminator for the concrete Obligation subclass.
in_subset:
- sow_spec
- execution_tracking
from_schema: https://w3id.org/collabri/core
rank: 1000
owner: Obligation
domain_of:
- Obligation
range: string

```
</details></div>