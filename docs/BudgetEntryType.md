---
search:
  boost: 2.0
---


# Enum: BudgetEntryType 




_Categories of financial snapshot recorded on a BudgetEntry. Proposed / awarded / working are planning views (each carries its own version history because negotiations and amendments generate multiple snapshots before any single view is final); actual and encumbrance are execution views._



<div data-search-exclude markdown="1">

URI: [core:BudgetEntryTypeScheme](https://w3id.org/collabri/core/BudgetEntryTypeScheme)

**Enum URI:** [core:BudgetEntryTypeScheme](https://w3id.org/collabri/core/BudgetEntryTypeScheme)


## Permissible Values
| Value | Meaning | Description |
| --- | --- | --- |
| proposed | None | Amount the performer proposed at solicitation time |
| awarded | None | Amount the sponsor formally awarded under the contract |
| working | None | Current authorized amount after modifications and change orders |
| actual | None | Cumulative amount actually paid / spent as of as_of_date |
| encumbrance | None | Committed-but-not-yet-paid amount as of as_of_date — signed POs, executed sub... |




## Slots

| Name | Description |
| ---  | --- |
| [entry_type](entry_type.md) | Which budget view this entry represents |










## Identifier and Mapping Information





### Schema Source


* from schema: https://w3id.org/collabri/core






## LinkML Source

<details>
```yaml
name: BudgetEntryType
description: Categories of financial snapshot recorded on a BudgetEntry. Proposed
  / awarded / working are planning views (each carries its own version history because
  negotiations and amendments generate multiple snapshots before any single view is
  final); actual and encumbrance are execution views.
from_schema: https://w3id.org/collabri/core
rank: 1000
enum_uri: core:BudgetEntryTypeScheme
permissible_values:
  proposed:
    text: proposed
    description: Amount the performer proposed at solicitation time. May have multiple
      snapshots over a negotiation cycle.
  awarded:
    text: awarded
    description: Amount the sponsor formally awarded under the contract. May have
      multiple snapshots if there are pre-execution modifications.
  working:
    text: working
    description: Current authorized amount after modifications and change orders.
      For un-modified contracts, equals awarded. Each contract modification adds a
      new working snapshot.
  actual:
    text: actual
    description: Cumulative amount actually paid / spent as of as_of_date. Typically
      populated from the accounting system at each monthly close. Required to be tracked
      even on fixed-price awards whenever the sponsor's reporting obligations call
      for it, independent of whether the actuals affect what gets paid.
  encumbrance:
    text: encumbrance
    description: Committed-but-not-yet-paid amount as of as_of_date — signed POs,
      executed subcontracts, payroll commitments, etc.

```
</details>

</div>