---
search:
  boost: 2.0
---


# Enum: PerformanceStatus 




_Execution state, orthogonal to ContractualStatus._



<div data-search-exclude markdown="1">

URI: [core:PerformanceStatusScheme](https://w3id.org/collabri/core/PerformanceStatusScheme)

**Enum URI:** [core:PerformanceStatusScheme](https://w3id.org/collabri/core/PerformanceStatusScheme)


## Permissible Values
| Value | Meaning | Description |
| --- | --- | --- |
| not_started | None | Work has not yet begun |
| in_progress | None | Work is underway |
| at_risk | None | In progress but at risk of slipping due_month or acceptance |
| blocked | None | Cannot proceed pending resolution of a dependency or external decision |
| completed | None | Work is finished |




## Slots

| Name | Description |
| ---  | --- |
| [performance_status](performance_status.md) | Execution state, orthogonal to contractual_status |










## Identifier and Mapping Information





### Schema Source


* from schema: https://w3id.org/collabri/core






## LinkML Source

<details>
```yaml
name: PerformanceStatus
description: Execution state, orthogonal to ContractualStatus.
from_schema: https://w3id.org/collabri/core
close_mappings:
- schema:ActionStatusType
rank: 1000
enum_uri: core:PerformanceStatusScheme
permissible_values:
  not_started:
    text: not_started
    description: Work has not yet begun.
  in_progress:
    text: in_progress
    description: Work is underway.
  at_risk:
    text: at_risk
    description: In progress but at risk of slipping due_month or acceptance.
  blocked:
    text: blocked
    description: Cannot proceed pending resolution of a dependency or external decision.
  completed:
    text: completed
    description: Work is finished.

```
</details>

</div>