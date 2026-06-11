---
search:
  boost: 5.0
---

# Slot: first_due 


_First due-month for the recurring report._



<div data-search-exclude markdown="1">



URI: [core:first_due](https://w3id.org/collabri/core/first_due)
<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [ReportingObligation](ReportingObligation.md) | Recurring reporting duty (quarterly progress report, annual technical report,... |  no  |






## Properties

### Type and Range

| Property | Value |
| --- | --- |
| Range | [Integer](Integer.md) |
| Domain Of | [ReportingObligation](ReportingObligation.md) |

### Cardinality and Requirements

| Property | Value |
| --- | --- |
### Slot Characteristics

| Property | Value |
| --- | --- |
| Owner | [ReportingObligation](ReportingObligation.md) |


### Value Constraints

| Property | Value |
| --- | --- |
| Minimum Value | 1 |








## In Subsets


* [SowSpec](SowSpec.md)
* [ExecutionTracking](ExecutionTracking.md)






## Identifier and Mapping Information





### Schema Source


* from schema: https://w3id.org/collabri/core




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | core:first_due |
| native | core:first_due |




## LinkML Source

<details>
```yaml
name: first_due
description: First due-month for the recurring report.
in_subset:
- sow_spec
- execution_tracking
from_schema: https://w3id.org/collabri/core
rank: 1000
owner: ReportingObligation
domain_of:
- ReportingObligation
range: integer
minimum_value: 1

```
</details></div>