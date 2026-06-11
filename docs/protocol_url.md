---
search:
  boost: 5.0
---

# Slot: protocol_url 


_URL where the method/protocol is documented._



<div data-search-exclude markdown="1">



URI: [core:protocol_url](https://w3id.org/collabri/core/protocol_url)
<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Method](Method.md) | A method deliverable, modeled as a prov:Plan |  no  |






## Properties

### Type and Range

| Property | Value |
| --- | --- |
| Range | [String](String.md) |
| Domain Of | [Method](Method.md) |

### Cardinality and Requirements

| Property | Value |
| --- | --- |
### Slot Characteristics

| Property | Value |
| --- | --- |
| Owner | [Method](Method.md) |








## In Subsets


* [SowSpec](SowSpec.md)
* [ExecutionTracking](ExecutionTracking.md)






## Identifier and Mapping Information





### Schema Source


* from schema: https://w3id.org/collabri/core




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | core:protocol_url |
| native | core:protocol_url |




## LinkML Source

<details>
```yaml
name: protocol_url
description: URL where the method/protocol is documented.
in_subset:
- sow_spec
- execution_tracking
from_schema: https://w3id.org/collabri/core
rank: 1000
owner: Method
domain_of:
- Method
range: string

```
</details></div>