---
search:
  boost: 5.0
---

# Slot: contributors 


_Per-deliverable contributor roles (CRediT-aligned)._



<div data-search-exclude markdown="1">



URI: [core:contributors](https://w3id.org/collabri/core/contributors)
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
| Range | [Contribution](Contribution.md) |
| Domain Of | [Deliverable](Deliverable.md) |

### Cardinality and Requirements

| Property | Value |
| --- | --- |
| Multivalued | Yes |
### Slot Characteristics

| Property | Value |
| --- | --- |
| Owner | [Deliverable](Deliverable.md) |








## In Subsets


* [ExecutionTracking](ExecutionTracking.md)






## Identifier and Mapping Information





### Schema Source


* from schema: https://w3id.org/collabri/core




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | core:contributors |
| native | core:contributors |




## LinkML Source

<details>
```yaml
name: contributors
description: Per-deliverable contributor roles (CRediT-aligned).
in_subset:
- execution_tracking
from_schema: https://w3id.org/collabri/core
rank: 1000
owner: Deliverable
domain_of:
- Deliverable
range: Contribution
multivalued: true
inlined: true
inlined_as_list: true

```
</details></div>