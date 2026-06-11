---
search:
  boost: 2.0
---


# Enum: ContractualStatus 




_Where this element sits in the contract lifecycle._



<div data-search-exclude markdown="1">

URI: [core:ContractualStatusScheme](https://w3id.org/collabri/core/ContractualStatusScheme)

**Enum URI:** [core:ContractualStatusScheme](https://w3id.org/collabri/core/ContractualStatusScheme)


## Permissible Values
| Value | Meaning | Description |
| --- | --- | --- |
| draft | None | Drafted but not yet submitted for approval |
| proposed | None | Submitted for approval (in a ChangeProposal) |
| approved | None | Approved, not yet executed (e |
| executed | None | Executed (signed) |
| accepted | None | Deliverable / milestone accepted by the paying party |
| paid | None | Payment for the accepted item has been made |
| superseded | None | Replaced by a newer version |
| cancelled | None | Descoped or terminated |




## Slots

| Name | Description |
| ---  | --- |
| [contractual_status](contractual_status.md) | Where this element sits in the contract lifecycle |










## Identifier and Mapping Information





### Schema Source


* from schema: https://w3id.org/collabri/core






## LinkML Source

<details>
```yaml
name: ContractualStatus
description: Where this element sits in the contract lifecycle.
from_schema: https://w3id.org/collabri/core
rank: 1000
enum_uri: core:ContractualStatusScheme
permissible_values:
  draft:
    text: draft
    description: Drafted but not yet submitted for approval.
  proposed:
    text: proposed
    description: Submitted for approval (in a ChangeProposal).
  approved:
    text: approved
    description: Approved, not yet executed (e.g. signed).
  executed:
    text: executed
    description: Executed (signed).
  accepted:
    text: accepted
    description: Deliverable / milestone accepted by the paying party. Payable subtasks
      only.
  paid:
    text: paid
    description: Payment for the accepted item has been made. Payable subtasks only.
  superseded:
    text: superseded
    description: Replaced by a newer version.
  cancelled:
    text: cancelled
    description: Descoped or terminated.

```
</details>

</div>