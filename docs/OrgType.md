---
search:
  boost: 2.0
---


# Enum: OrgType 




_The role an organization plays in the program._



<div data-search-exclude markdown="1">

URI: [core:OrgTypeScheme](https://w3id.org/collabri/core/OrgTypeScheme)

**Enum URI:** [core:OrgTypeScheme](https://w3id.org/collabri/core/OrgTypeScheme)


## Permissible Values
| Value | Meaning | Description |
| --- | --- | --- |
| prime | None | The prime contractor |
| subcontractor | None | A subcontractor or performer under the prime |
| sponsor | None | The government sponsor / paying agency |
| government | None | A government participant that is not the paying sponsor |
| performer | None | A research performer (commonly under the prime) |
| other | None | Any other participating organization |




## Slots

| Name | Description |
| ---  | --- |
| [org_type](org_type.md) | The organization's role in the program |
| [role](role.md) | Contract role (sponsor, prime, subcontractor, performer, etc |










## Identifier and Mapping Information





### Schema Source


* from schema: https://w3id.org/collabri/core






## LinkML Source

<details>
```yaml
name: OrgType
description: The role an organization plays in the program.
from_schema: https://w3id.org/collabri/core
close_mappings:
- org:Role
- schema:Role
rank: 1000
enum_uri: core:OrgTypeScheme
permissible_values:
  prime:
    text: prime
    description: The prime contractor.
  subcontractor:
    text: subcontractor
    description: A subcontractor or performer under the prime.
  sponsor:
    text: sponsor
    description: The government sponsor / paying agency.
  government:
    text: government
    description: A government participant that is not the paying sponsor.
  performer:
    text: performer
    description: A research performer (commonly under the prime).
  other:
    text: other
    description: Any other participating organization.

```
</details>

</div>