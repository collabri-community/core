---
search:
  boost: 5.0
---

# Slot: org_type 


_The organization's role in the program._



<div data-search-exclude markdown="1">



URI: [core:org_type](https://w3id.org/collabri/core/org_type)
<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Organization](Organization.md) | An organization participating in the SOW |  no  |






## Properties

### Type and Range

| Property | Value |
| --- | --- |
| Range | [OrgType](OrgType.md) |
| Domain Of | [Organization](Organization.md) |

### Cardinality and Requirements

| Property | Value |
| --- | --- |
### Slot Characteristics

| Property | Value |
| --- | --- |
| Owner | [Organization](Organization.md) |








## In Subsets


* [SowSpec](SowSpec.md)
* [ExecutionTracking](ExecutionTracking.md)






## Identifier and Mapping Information





### Schema Source


* from schema: https://w3id.org/collabri/core




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | core:org_type |
| native | core:org_type |




## LinkML Source

<details>
```yaml
name: org_type
description: The organization's role in the program.
in_subset:
- sow_spec
- execution_tracking
from_schema: https://w3id.org/collabri/core
rank: 1000
owner: Organization
domain_of:
- Organization
range: OrgType

```
</details></div>