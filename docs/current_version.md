---
search:
  boost: 5.0
---

# Slot: current_version 


_True iff this is the current accepted version of the element._



<div data-search-exclude markdown="1">



URI: [pav:hasCurrentVersion](http://purl.org/pav/hasCurrentVersion)
<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Versioned](Versioned.md) | Mixin: per-element version metadata, aligned with PAV and PROV |  no  |
| [TaskTeam](TaskTeam.md) | Root of a Statement of Work, scoped to a single contract |  no  |
| [Task](Task.md) | Thematic bucket of work, possibly spanning the full award |  no  |
| [Subtask](Subtask.md) | A step toward completion of a Task |  no  |
| [Milestone](Milestone.md) | A milestone groups subtasks (linked via Subtask |  no  |
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
| Range | [Boolean](Boolean.md) |
| Domain Of | [Versioned](Versioned.md) |
| Slot URI | [pav:hasCurrentVersion](http://purl.org/pav/hasCurrentVersion) |

### Cardinality and Requirements

| Property | Value |
| --- | --- |
### Slot Characteristics

| Property | Value |
| --- | --- |
| Owner | [Versioned](Versioned.md) |








## In Subsets


* [ExecutionTracking](ExecutionTracking.md)






## Identifier and Mapping Information





### Schema Source


* from schema: https://w3id.org/collabri/core




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | pav:hasCurrentVersion |
| native | core:current_version |




## LinkML Source

<details>
```yaml
name: current_version
description: True iff this is the current accepted version of the element.
in_subset:
- execution_tracking
from_schema: https://w3id.org/collabri/core
rank: 1000
slot_uri: pav:hasCurrentVersion
owner: Versioned
domain_of:
- Versioned
range: boolean

```
</details></div>