---
search:
  boost: 5.0
---

# Slot: target_value 


_The target value to be achieved._



<div data-search-exclude markdown="1">



URI: [qudt:value](http://qudt.org/schema/qudt/value)
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
| Slot URI | [qudt:value](http://qudt.org/schema/qudt/value) |

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
| self | qudt:value |
| native | core:target_value |




## LinkML Source

<details>
```yaml
name: target_value
description: The target value to be achieved.
in_subset:
- sow_spec
- execution_tracking
from_schema: https://w3id.org/collabri/core
rank: 1000
slot_uri: qudt:value
owner: Metric
domain_of:
- Metric
range: string

```
</details></div>