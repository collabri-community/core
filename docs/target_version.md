---
search:
  boost: 5.0
---

# Slot: target_version 

<div data-search-exclude markdown="1">



URI: [core:target_version](https://w3id.org/collabri/core/target_version)
<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Change](Change.md) | A single element-level edit within a ChangeProposal |  no  |
| [Approval](Approval.md) | Signoff on a specific version of a SOW element |  no  |






## Properties

### Type and Range

| Property | Value |
| --- | --- |
| Range | [String](String.md) |
| Domain Of | [Change](Change.md), [Approval](Approval.md) |

### Cardinality and Requirements

| Property | Value |
| --- | --- |










## Identifier and Mapping Information






## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | core:target_version |
| native | core:target_version |




## LinkML Source

<details>
```yaml
name: target_version
domain_of:
- Change
- Approval
range: string

```
</details></div>