---
search:
  boost: 5.0
---

# Slot: before 


_Snapshot of the element before the change (null for adds)._



<div data-search-exclude markdown="1">



URI: [core:before](https://w3id.org/collabri/core/before)
<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Change](Change.md) | A single element-level edit within a ChangeProposal |  no  |






## Properties

### Type and Range

| Property | Value |
| --- | --- |
| Range | [String](String.md) |
| Domain Of | [Change](Change.md) |

### Cardinality and Requirements

| Property | Value |
| --- | --- |
### Slot Characteristics

| Property | Value |
| --- | --- |
| Owner | [Change](Change.md) |












## Identifier and Mapping Information





### Schema Source


* from schema: https://w3id.org/collabri/core




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | core:before |
| native | core:before |




## LinkML Source

<details>
```yaml
name: before
description: Snapshot of the element before the change (null for adds).
from_schema: https://w3id.org/collabri/core
rank: 1000
owner: Change
domain_of:
- Change
range: string

```
</details></div>