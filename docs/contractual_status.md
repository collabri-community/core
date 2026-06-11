---
search:
  boost: 5.0
---

# Slot: contractual_status 


_Where this element sits in the contract lifecycle._



<div data-search-exclude markdown="1">



URI: [core:contractual_status](https://w3id.org/collabri/core/contractual_status)
<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Trackable](Trackable.md) | Mixin: dual-axis status |  no  |
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
| Range | [ContractualStatus](ContractualStatus.md) |
| Domain Of | [Trackable](Trackable.md) |

### Cardinality and Requirements

| Property | Value |
| --- | --- |
| Required | Yes |
### Slot Characteristics

| Property | Value |
| --- | --- |
| Owner | [Trackable](Trackable.md) |








## In Subsets


* [SowSpec](SowSpec.md)
* [ExecutionTracking](ExecutionTracking.md)






## Identifier and Mapping Information





### Schema Source


* from schema: https://w3id.org/collabri/core




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | core:contractual_status |
| native | core:contractual_status |




## LinkML Source

<details>
```yaml
name: contractual_status
description: Where this element sits in the contract lifecycle.
in_subset:
- sow_spec
- execution_tracking
from_schema: https://w3id.org/collabri/core
rank: 1000
owner: Trackable
domain_of:
- Trackable
range: ContractualStatus
required: true

```
</details></div>