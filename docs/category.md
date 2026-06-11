---
search:
  boost: 5.0
---

# Slot: category 


_Discriminator naming the concrete Deliverable subclass for this instance. Required because Deliverable is abstract; every instance must declare which typed subclass it is (Activity, Data, Method, NarrativeDocument, Software, Standard)._



<div data-search-exclude markdown="1">



URI: [core:category](https://w3id.org/collabri/core/category)
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
| Range | [String](String.md) |
| Domain Of | [Deliverable](Deliverable.md) |

### Cardinality and Requirements

| Property | Value |
| --- | --- |
| Required | Yes |
### Slot Characteristics

| Property | Value |
| --- | --- |
| Designates Type | Yes |
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
| self | core:category |
| native | core:category |




## LinkML Source

<details>
```yaml
name: category
description: Discriminator naming the concrete Deliverable subclass for this instance.
  Required because Deliverable is abstract; every instance must declare which typed
  subclass it is (Activity, Data, Method, NarrativeDocument, Software, Standard).
in_subset:
- sow_spec
- execution_tracking
from_schema: https://w3id.org/collabri/core
rank: 1000
designates_type: true
owner: Deliverable
domain_of:
- Deliverable
range: string
required: true

```
</details></div>