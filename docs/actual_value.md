---
search:
  boost: 5.0
---

# Slot: actual_value 


_The observed / current value, when known._



<div data-search-exclude markdown="1">



URI: [core:actual_value](https://w3id.org/collabri/core/actual_value)
<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Metric](Metric.md) | A measurable indicator used to evaluate a deliverable, together with the rati... |  no  |






## Properties

### Type and Range

| Property | Value |
| --- | --- |
| Range | [String](String.md) |
| Domain Of | [Metric](Metric.md) |

### Cardinality and Requirements

| Property | Value |
| --- | --- |
### Slot Characteristics

| Property | Value |
| --- | --- |
| Owner | [Metric](Metric.md) |








## In Subsets


* [ExecutionTracking](ExecutionTracking.md)






## Identifier and Mapping Information





### Schema Source


* from schema: https://w3id.org/collabri/core




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | core:actual_value |
| native | core:actual_value |
| close | qudt:value, schema:value |




## LinkML Source

<details>
```yaml
name: actual_value
description: The observed / current value, when known.
in_subset:
- execution_tracking
from_schema: https://w3id.org/collabri/core
close_mappings:
- qudt:value
- schema:value
rank: 1000
owner: Metric
domain_of:
- Metric
range: string

```
</details></div>