---
search:
  boost: 5.0
---

# Slot: cadence 


_Reporting cadence (e.g. "quarterly", "annually")._



<div data-search-exclude markdown="1">



URI: [core:cadence](https://w3id.org/collabri/core/cadence)
<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [ReportingObligation](ReportingObligation.md) | Recurring reporting duty (quarterly progress report, annual technical report,... |  no  |






## Properties

### Type and Range

| Property | Value |
| --- | --- |
| Range | [String](String.md) |
| Domain Of | [ReportingObligation](ReportingObligation.md) |

### Cardinality and Requirements

| Property | Value |
| --- | --- |
### Slot Characteristics

| Property | Value |
| --- | --- |
| Owner | [ReportingObligation](ReportingObligation.md) |








## In Subsets


* [SowSpec](SowSpec.md)
* [ExecutionTracking](ExecutionTracking.md)






## Identifier and Mapping Information





### Schema Source


* from schema: https://w3id.org/collabri/core




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | core:cadence |
| native | core:cadence |




## LinkML Source

<details>
```yaml
name: cadence
description: Reporting cadence (e.g. "quarterly", "annually").
in_subset:
- sow_spec
- execution_tracking
from_schema: https://w3id.org/collabri/core
rank: 1000
owner: ReportingObligation
domain_of:
- ReportingObligation
range: string

```
</details></div>