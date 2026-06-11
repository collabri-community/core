---
search:
  boost: 5.0
---

# Slot: id 


_Stable identifier; together with version forms the element IRI._



<div data-search-exclude markdown="1">



URI: [dcterms:identifier](http://purl.org/dc/terms/identifier)
<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Core](Core.md) | Foundational base class for every addressable Collabri element |  no  |
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
| [Obligation](Obligation.md) | Abstract base for any contractual duty (ODRL pattern) |  no  |
| [Payment](Payment.md) | Payment obligation tied to milestone acceptance |  no  |
| [ReportingObligation](ReportingObligation.md) | Recurring reporting duty (quarterly progress report, annual technical report,... |  no  |
| [ChangeProposal](ChangeProposal.md) | A bundled set of element-level Changes against a base SOW version, analogous ... |  no  |
| [Change](Change.md) | A single element-level edit within a ChangeProposal |  no  |
| [Approval](Approval.md) | Signoff on a specific version of a SOW element |  no  |
| [Organization](Organization.md) | An organization participating in the SOW |  no  |
| [Person](Person.md) | A person who can be assigned as a lead or contributor |  no  |
| [Party](Party.md) | A role-bearing entity in the contract (Organization or Person wrapped with a ... |  no  |






## Properties

### Type and Range

| Property | Value |
| --- | --- |
| Range | [String](String.md) |
| Domain Of | [Core](Core.md), [Change](Change.md), [Organization](Organization.md), [Person](Person.md) |
| Slot URI | [dcterms:identifier](http://purl.org/dc/terms/identifier) |

### Cardinality and Requirements

| Property | Value |
| --- | --- |
| Required | Yes |
### Slot Characteristics

| Property | Value |
| --- | --- |
| Identifier | Yes |








## In Subsets


* [SowSpec](SowSpec.md)
* [ExecutionTracking](ExecutionTracking.md)






## Identifier and Mapping Information





### Schema Source


* from schema: https://w3id.org/collabri/core




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | dcterms:identifier |
| native | core:id |
| exact | schema:identifier |




## LinkML Source

<details>
```yaml
name: id
description: Stable identifier; together with version forms the element IRI.
in_subset:
- sow_spec
- execution_tracking
from_schema: https://w3id.org/collabri/core
exact_mappings:
- schema:identifier
rank: 1000
slot_uri: dcterms:identifier
identifier: true
domain_of:
- Core
- Change
- Organization
- Person
range: string
required: true

```
</details></div>