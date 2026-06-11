---
search:
  boost: 5.0
---

# Slot: tasks 


_Tasks (thematic buckets) that make up this SOW._



<div data-search-exclude markdown="1">



URI: [dcterms:hasPart](http://purl.org/dc/terms/hasPart)
<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [TaskTeam](TaskTeam.md) | Root of a Statement of Work, scoped to a single contract |  no  |






## Properties

### Type and Range

| Property | Value |
| --- | --- |
| Range | [Task](Task.md) |
| Domain Of | [TaskTeam](TaskTeam.md) |
| Slot URI | [dcterms:hasPart](http://purl.org/dc/terms/hasPart) |

### Cardinality and Requirements

| Property | Value |
| --- | --- |
| Required | Yes |
| Multivalued | Yes |
### Slot Characteristics

| Property | Value |
| --- | --- |
| Owner | [TaskTeam](TaskTeam.md) |








## In Subsets


* [SowSpec](SowSpec.md)
* [ExecutionTracking](ExecutionTracking.md)






## Identifier and Mapping Information





### Schema Source


* from schema: https://w3id.org/collabri/core




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | dcterms:hasPart |
| native | core:tasks |




## LinkML Source

<details>
```yaml
name: tasks
description: Tasks (thematic buckets) that make up this SOW.
in_subset:
- sow_spec
- execution_tracking
from_schema: https://w3id.org/collabri/core
rank: 1000
slot_uri: dcterms:hasPart
owner: TaskTeam
domain_of:
- TaskTeam
range: Task
required: true
multivalued: true
inlined: true
inlined_as_list: true

```
</details></div>