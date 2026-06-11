---
search:
  boost: 5.0
---

# Slot: software_license 


_License under which the software is distributed._



<div data-search-exclude markdown="1">



URI: [doap:license](http://usefulinc.com/ns/doap#license)
<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Software](Software.md) | A software deliverable (source code, library, release) |  no  |






## Properties

### Type and Range

| Property | Value |
| --- | --- |
| Range | [String](String.md) |
| Domain Of | [Software](Software.md) |
| Slot URI | [doap:license](http://usefulinc.com/ns/doap#license) |

### Cardinality and Requirements

| Property | Value |
| --- | --- |
### Slot Characteristics

| Property | Value |
| --- | --- |
| Owner | [Software](Software.md) |








## In Subsets


* [SowSpec](SowSpec.md)
* [ExecutionTracking](ExecutionTracking.md)






## Identifier and Mapping Information





### Schema Source


* from schema: https://w3id.org/collabri/core




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | doap:license |
| native | core:software_license |




## LinkML Source

<details>
```yaml
name: software_license
description: License under which the software is distributed.
in_subset:
- sow_spec
- execution_tracking
from_schema: https://w3id.org/collabri/core
rank: 1000
slot_uri: doap:license
owner: Software
domain_of:
- Software
range: string

```
</details></div>