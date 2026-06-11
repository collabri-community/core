---
search:
  boost: 5.0
---

# Slot: action 


_ODRL action term or local action label (e.g. "report", "deliver", "pay")._



<div data-search-exclude markdown="1">



URI: [odrl:action](http://www.w3.org/ns/odrl/2/action)
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
| Slot URI | [odrl:action](http://www.w3.org/ns/odrl/2/action) |

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
| self | odrl:action |
| native | core:action |




## LinkML Source

<details>
```yaml
name: action
description: ODRL action term or local action label (e.g. "report", "deliver", "pay").
in_subset:
- sow_spec
- execution_tracking
from_schema: https://w3id.org/collabri/core
rank: 1000
slot_uri: odrl:action
owner: Obligation
domain_of:
- Obligation
range: string

```
</details></div>