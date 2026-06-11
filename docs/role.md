---
search:
  boost: 5.0
---

# Slot: role 

<div data-search-exclude markdown="1">



URI: [core:role](https://w3id.org/collabri/core/role)
<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Party](Party.md) | A role-bearing entity in the contract (Organization or Person wrapped with a ... |  no  |
| [Contribution](Contribution.md) | Contributor role on a deliverable, CRediT-aligned where applicable |  no  |






## Properties

### Type and Range

| Property | Value |
| --- | --- |
| Range | [String](String.md) |
| Domain Of | [Party](Party.md), [Contribution](Contribution.md) |

### Cardinality and Requirements

| Property | Value |
| --- | --- |










## Identifier and Mapping Information






## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | core:role |
| native | core:role |




## LinkML Source

<details>
```yaml
name: role
domain_of:
- Party
- Contribution
range: string

```
</details></div>