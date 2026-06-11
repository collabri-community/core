---
search:
  boost: 5.0
---

# Slot: metrics 


_The metric(s) by which this deliverable is evaluated._



<div data-search-exclude markdown="1">



URI: [core:metrics](https://w3id.org/collabri/core/metrics)
<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Deliverable](Deliverable.md) | A concrete, acceptance-bearing output owed for a payable subtask |  no  |
| [Activity](Activity.md) | An event-type deliverable (training, workshop, presentation) |  no  |
| [Data](Data.md) | A dataset, spreadsheet, or other structured-data artifact |  no  |
| [Method](Method.md) | A method deliverable, modeled as a prov:Plan |  no  |
| [NarrativeDocument](NarrativeDocument.md) | Policy, SOP, report, recommendation, publication, progress-report blurb, etc |  no  |
| [Software](Software.md) | A software deliverable (source code, library, release) |  no  |
| [Standard](Standard.md) | A normative or internal standard, classified by subtype |  no  |






## Properties

### Type and Range

| Property | Value |
| --- | --- |
| Range | [Metric](Metric.md) |
| Domain Of | [Deliverable](Deliverable.md) |

### Cardinality and Requirements

| Property | Value |
| --- | --- |
| Required | Yes |
| Multivalued | Yes |
### Slot Characteristics

| Property | Value |
| --- | --- |
| Owner | [Deliverable](Deliverable.md) |








## In Subsets


* [SowSpec](SowSpec.md)
* [ExecutionTracking](ExecutionTracking.md)






## Identifier and Mapping Information





### Schema Source


* from schema: https://w3id.org/collabri/core




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | core:metrics |
| native | core:metrics |




## LinkML Source

<details>
```yaml
name: metrics
description: The metric(s) by which this deliverable is evaluated.
in_subset:
- sow_spec
- execution_tracking
from_schema: https://w3id.org/collabri/core
rank: 1000
owner: Deliverable
domain_of:
- Deliverable
range: Metric
required: true
multivalued: true
inlined: true
inlined_as_list: true

```
</details></div>