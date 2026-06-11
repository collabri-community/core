---
search:
  boost: 5.0
---

# Slot: after 


_Snapshot of the element after the change (null for removes)._



<div data-search-exclude markdown="1">



URI: [core:after](https://w3id.org/collabri/core/after)
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
| self | core:after |
| native | core:after |




## LinkML Source

<details>
```yaml
name: after
description: Snapshot of the element after the change (null for removes).
from_schema: https://w3id.org/collabri/core
rank: 1000
owner: Change
domain_of:
- Change
range: string

```
</details></div>