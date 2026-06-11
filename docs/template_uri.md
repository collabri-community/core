---
search:
  boost: 5.0
---

# Slot: template_uri 


_Pointer to the required reporting template, if any._



<div data-search-exclude markdown="1">



URI: [core:template_uri](https://w3id.org/collabri/core/template_uri)
<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [ReportingObligation](ReportingObligation.md) | Recurring reporting duty (quarterly progress report, annual technical report,... |  no  |






## Properties

### Type and Range

| Property | Value |
| --- | --- |
| Range | [String](String.md) |
| Domain Of | [ReportingObligation](ReportingObligation.md) |

### Cardinality and Requirements

| Property | Value |
| --- | --- |
### Slot Characteristics

| Property | Value |
| --- | --- |
| Owner | [ReportingObligation](ReportingObligation.md) |








## In Subsets


* [SowSpec](SowSpec.md)
* [ExecutionTracking](ExecutionTracking.md)






## Identifier and Mapping Information





### Schema Source


* from schema: https://w3id.org/collabri/core




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | core:template_uri |
| native | core:template_uri |




## LinkML Source

<details>
```yaml
name: template_uri
description: Pointer to the required reporting template, if any.
in_subset:
- sow_spec
- execution_tracking
from_schema: https://w3id.org/collabri/core
rank: 1000
owner: ReportingObligation
domain_of:
- ReportingObligation
range: string

```
</details></div>