---
search:
  boost: 5.0
---

# Slot: authored_by 


_Author(s) of this version snapshot._



<div data-search-exclude markdown="1">



URI: [pav:authoredBy](http://purl.org/pav/authoredBy)
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
| Range | [Uriorcurie](Uriorcurie.md) |
| Domain Of | [Versioned](Versioned.md) |
| Slot URI | [pav:authoredBy](http://purl.org/pav/authoredBy) |

### Cardinality and Requirements

| Property | Value |
| --- | --- |
| Multivalued | Yes |
### Slot Characteristics

| Property | Value |
| --- | --- |
| Owner | [Versioned](Versioned.md) |








## In Subsets


* [SowSpec](SowSpec.md)
* [ExecutionTracking](ExecutionTracking.md)






## Identifier and Mapping Information





### Schema Source


* from schema: https://w3id.org/collabri/core




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | pav:authoredBy |
| native | core:authored_by |




## LinkML Source

<details>
```yaml
name: authored_by
description: Author(s) of this version snapshot.
in_subset:
- sow_spec
- execution_tracking
from_schema: https://w3id.org/collabri/core
rank: 1000
slot_uri: pav:authoredBy
owner: Versioned
domain_of:
- Versioned
range: uriorcurie
multivalued: true

```
</details></div>