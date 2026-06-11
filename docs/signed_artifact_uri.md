---
search:
  boost: 5.0
---

# Slot: signed_artifact_uri 

<div data-search-exclude markdown="1">



URI: [core:signed_artifact_uri](https://w3id.org/collabri/core/signed_artifact_uri)
<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [ChangeProposal](ChangeProposal.md) | A bundled set of element-level Changes against a base SOW version, analogous ... |  no  |
| [Approval](Approval.md) | Signoff on a specific version of a SOW element |  no  |






## Properties

### Type and Range

| Property | Value |
| --- | --- |
| Range | [String](String.md) |
| Domain Of | [ChangeProposal](ChangeProposal.md), [Approval](Approval.md) |

### Cardinality and Requirements

| Property | Value |
| --- | --- |










## Identifier and Mapping Information






## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | core:signed_artifact_uri |
| native | core:signed_artifact_uri |




## LinkML Source

<details>
```yaml
name: signed_artifact_uri
domain_of:
- ChangeProposal
- Approval
range: string

```
</details></div>