---
search:
  boost: 5.0
---

# Slot: narrative_type 


_Subtype of narrative document._



<div data-search-exclude markdown="1">



URI: [core:narrative_type](https://w3id.org/collabri/core/narrative_type)
<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [NarrativeDocument](NarrativeDocument.md) | Policy, SOP, report, recommendation, publication, progress-report blurb, etc |  no  |






## Properties

### Type and Range

| Property | Value |
| --- | --- |
| Range | [NarrativeDocumentType](NarrativeDocumentType.md) |
| Domain Of | [NarrativeDocument](NarrativeDocument.md) |

### Cardinality and Requirements

| Property | Value |
| --- | --- |
### Slot Characteristics

| Property | Value |
| --- | --- |
| Owner | [NarrativeDocument](NarrativeDocument.md) |








## In Subsets


* [SowSpec](SowSpec.md)
* [ExecutionTracking](ExecutionTracking.md)






## Identifier and Mapping Information





### Schema Source


* from schema: https://w3id.org/collabri/core




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | core:narrative_type |
| native | core:narrative_type |




## LinkML Source

<details>
```yaml
name: narrative_type
description: Subtype of narrative document.
in_subset:
- sow_spec
- execution_tracking
from_schema: https://w3id.org/collabri/core
rank: 1000
owner: NarrativeDocument
domain_of:
- NarrativeDocument
range: NarrativeDocumentType

```
</details></div>