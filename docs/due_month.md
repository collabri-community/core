---
search:
  boost: 5.0
---

# Slot: due_month 


_Due date expressed as a whole number of months since program start (month 1 = the first month of the period of performance). Primary due-date convention in Collabri; calendar dates are derived by anchoring against TaskTeam.period_of_performance_start._



<div data-search-exclude markdown="1">



URI: [core:due_month](https://w3id.org/collabri/core/due_month)
<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Subtask](Subtask.md) | A step toward completion of a Task |  no  |
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
| Range | [Integer](Integer.md) |
| Domain Of | [Subtask](Subtask.md), [Deliverable](Deliverable.md) |

### Cardinality and Requirements

| Property | Value |
| --- | --- |
### Value Constraints

| Property | Value |
| --- | --- |
| Minimum Value | 1 |








## In Subsets


* [SowSpec](SowSpec.md)
* [ExecutionTracking](ExecutionTracking.md)






## Identifier and Mapping Information





### Schema Source


* from schema: https://w3id.org/collabri/core




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | core:due_month |
| native | core:due_month |
| close | time:hasBeginning, schema:scheduledTime |




## LinkML Source

<details>
```yaml
name: due_month
description: Due date expressed as a whole number of months since program start (month
  1 = the first month of the period of performance). Primary due-date convention in
  Collabri; calendar dates are derived by anchoring against TaskTeam.period_of_performance_start.
in_subset:
- sow_spec
- execution_tracking
from_schema: https://w3id.org/collabri/core
close_mappings:
- time:hasBeginning
- schema:scheduledTime
rank: 1000
domain_of:
- Subtask
- Deliverable
range: integer
minimum_value: 1

```
</details></div>