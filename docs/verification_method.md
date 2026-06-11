---
search:
  boost: 5.0
---

# Slot: verification_method 


_How the criterion will be checked (e.g. "test suite green", "editorial review", "demo accepted by sponsor")._



<div data-search-exclude markdown="1">



URI: [core:verification_method](https://w3id.org/collabri/core/verification_method)
<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [AcceptanceCriterion](AcceptanceCriterion.md) | A single, testable condition for accepting a deliverable |  no  |






## Properties

### Type and Range

| Property | Value |
| --- | --- |
| Range | [String](String.md) |
| Domain Of | [AcceptanceCriterion](AcceptanceCriterion.md) |

### Cardinality and Requirements

| Property | Value |
| --- | --- |
### Slot Characteristics

| Property | Value |
| --- | --- |
| Owner | [AcceptanceCriterion](AcceptanceCriterion.md) |








## In Subsets


* [SowSpec](SowSpec.md)
* [ExecutionTracking](ExecutionTracking.md)






## Identifier and Mapping Information





### Schema Source


* from schema: https://w3id.org/collabri/core




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | core:verification_method |
| native | core:verification_method |




## LinkML Source

<details>
```yaml
name: verification_method
description: How the criterion will be checked (e.g. "test suite green", "editorial
  review", "demo accepted by sponsor").
in_subset:
- sow_spec
- execution_tracking
from_schema: https://w3id.org/collabri/core
rank: 1000
owner: AcceptanceCriterion
domain_of:
- AcceptanceCriterion
range: string

```
</details></div>