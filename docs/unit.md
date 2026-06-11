---
search:
  boost: 5.0
---

# Slot: unit 


_Unit of measure for the target and actual values._



<div data-search-exclude markdown="1">



URI: [qudt:hasUnit](http://qudt.org/schema/qudt/hasUnit)
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
| Slot URI | [qudt:hasUnit](http://qudt.org/schema/qudt/hasUnit) |

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
| self | qudt:hasUnit |
| native | core:unit |




## LinkML Source

<details>
```yaml
name: unit
description: Unit of measure for the target and actual values.
in_subset:
- sow_spec
- execution_tracking
from_schema: https://w3id.org/collabri/core
rank: 1000
slot_uri: qudt:hasUnit
owner: Metric
domain_of:
- Metric
range: string

```
</details></div>