---
search:
  boost: 5.0
---

# Slot: metric_text 


_Free-text fallback carrying the metric's verbatim statement from the source SOW, when the metric is not yet broken into structured name/target/unit fields._



<div data-search-exclude markdown="1">



URI: [core:metric_text](https://w3id.org/collabri/core/metric_text)
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


* [SowSpec](SowSpec.md)
* [ExecutionTracking](ExecutionTracking.md)






## Identifier and Mapping Information





### Schema Source


* from schema: https://w3id.org/collabri/core




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | core:metric_text |
| native | core:metric_text |
| close | dcterms:description |




## LinkML Source

<details>
```yaml
name: metric_text
description: Free-text fallback carrying the metric's verbatim statement from the
  source SOW, when the metric is not yet broken into structured name/target/unit fields.
in_subset:
- sow_spec
- execution_tracking
from_schema: https://w3id.org/collabri/core
close_mappings:
- dcterms:description
rank: 1000
owner: Metric
domain_of:
- Metric
range: string

```
</details></div>