---
search:
  boost: 5.0
---

# Slot: repository_url 


_URL of the source repository._



<div data-search-exclude markdown="1">



URI: [doap:repository](http://usefulinc.com/ns/doap#repository)
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
| Slot URI | [doap:repository](http://usefulinc.com/ns/doap#repository) |

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
| self | doap:repository |
| native | core:repository_url |




## LinkML Source

<details>
```yaml
name: repository_url
description: URL of the source repository.
in_subset:
- sow_spec
- execution_tracking
from_schema: https://w3id.org/collabri/core
rank: 1000
slot_uri: doap:repository
owner: Software
domain_of:
- Software
range: string

```
</details></div>