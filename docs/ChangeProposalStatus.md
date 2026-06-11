---
search:
  boost: 2.0
---


# Enum: ChangeProposalStatus 




_Lifecycle of a change proposal (≈ GitHub PR)._



<div data-search-exclude markdown="1">

URI: [core:ChangeProposalStatusScheme](https://w3id.org/collabri/core/ChangeProposalStatusScheme)

**Enum URI:** [core:ChangeProposalStatusScheme](https://w3id.org/collabri/core/ChangeProposalStatusScheme)


## Permissible Values
| Value | Meaning | Description |
| --- | --- | --- |
| open | None | Proposed and under review |
| approved | None | Approved but not yet merged |
| merged | None | Merged into the current SOW version |
| closed | None | Closed without merge |
| withdrawn | None | Withdrawn by the proposer |




## Slots

| Name | Description |
| ---  | --- |
| [status](status.md) | Lifecycle of this proposal (open, merged, closed, etc |










## Identifier and Mapping Information





### Schema Source


* from schema: https://w3id.org/collabri/core






## LinkML Source

<details>
```yaml
name: ChangeProposalStatus
description: Lifecycle of a change proposal (≈ GitHub PR).
from_schema: https://w3id.org/collabri/core
rank: 1000
enum_uri: core:ChangeProposalStatusScheme
permissible_values:
  open:
    text: open
    description: Proposed and under review.
  approved:
    text: approved
    description: Approved but not yet merged.
  merged:
    text: merged
    description: Merged into the current SOW version.
  closed:
    text: closed
    description: Closed without merge.
  withdrawn:
    text: withdrawn
    description: Withdrawn by the proposer.

```
</details>

</div>