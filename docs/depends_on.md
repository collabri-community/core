---
search:
  boost: 5.0
---

# Slot: depends_on 


_Other subtasks that must complete before this one can proceed._



<div data-search-exclude markdown="1">



URI: [dcterms:requires](http://purl.org/dc/terms/requires)
<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Subtask](Subtask.md) | A step toward completion of a Task |  no  |






## Properties

### Type and Range

| Property | Value |
| --- | --- |
| Range | [Subtask](Subtask.md) |
| Domain Of | [Subtask](Subtask.md) |
| Slot URI | [dcterms:requires](http://purl.org/dc/terms/requires) |

### Cardinality and Requirements

| Property | Value |
| --- | --- |
| Multivalued | Yes |
### Slot Characteristics

| Property | Value |
| --- | --- |
| Owner | [Subtask](Subtask.md) |








## In Subsets


* [SowSpec](SowSpec.md)
* [ExecutionTracking](ExecutionTracking.md)






## Identifier and Mapping Information





### Schema Source


* from schema: https://w3id.org/collabri/core




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | dcterms:requires |
| native | core:depends_on |
| close | prov:wasInformedBy |




## LinkML Source

<details>
```yaml
name: depends_on
description: Other subtasks that must complete before this one can proceed.
in_subset:
- sow_spec
- execution_tracking
from_schema: https://w3id.org/collabri/core
close_mappings:
- prov:wasInformedBy
rank: 1000
slot_uri: dcterms:requires
owner: Subtask
domain_of:
- Subtask
range: Subtask
multivalued: true

```
</details></div>