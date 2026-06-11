---
search:
  boost: 5.0
---

# Slot: period_of_performance_start 


_Calendar date on which program month 1 begins. Anchor for converting due_month values to absolute calendar dates._



<div data-search-exclude markdown="1">



URI: [schema:startDate](http://schema.org/startDate)
<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [TaskTeam](TaskTeam.md) | Root of a Statement of Work, scoped to a single contract |  no  |






## Properties

### Type and Range

| Property | Value |
| --- | --- |
| Range | [Date](Date.md) |
| Domain Of | [TaskTeam](TaskTeam.md) |
| Slot URI | [schema:startDate](http://schema.org/startDate) |

### Cardinality and Requirements

| Property | Value |
| --- | --- |
### Slot Characteristics

| Property | Value |
| --- | --- |
| Owner | [TaskTeam](TaskTeam.md) |








## In Subsets


* [SowSpec](SowSpec.md)
* [ExecutionTracking](ExecutionTracking.md)






## Identifier and Mapping Information





### Schema Source


* from schema: https://w3id.org/collabri/core




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | schema:startDate |
| native | core:period_of_performance_start |
| close | time:hasBeginning |




## LinkML Source

<details>
```yaml
name: period_of_performance_start
description: Calendar date on which program month 1 begins. Anchor for converting
  due_month values to absolute calendar dates.
in_subset:
- sow_spec
- execution_tracking
from_schema: https://w3id.org/collabri/core
close_mappings:
- time:hasBeginning
rank: 1000
slot_uri: schema:startDate
owner: TaskTeam
domain_of:
- TaskTeam
range: date

```
</details></div>