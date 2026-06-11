---
search:
  boost: 5.0
---

# Slot: record_count 


_Number of records in the dataset._



<div data-search-exclude markdown="1">



URI: [core:record_count](https://w3id.org/collabri/core/record_count)
<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Data](Data.md) | A dataset, spreadsheet, or other structured-data artifact |  no  |






## Properties

### Type and Range

| Property | Value |
| --- | --- |
| Range | [Integer](Integer.md) |
| Domain Of | [Data](Data.md) |

### Cardinality and Requirements

| Property | Value |
| --- | --- |
### Slot Characteristics

| Property | Value |
| --- | --- |
| Owner | [Data](Data.md) |


### Value Constraints

| Property | Value |
| --- | --- |
| Minimum Value | 0 |








## In Subsets


* [ExecutionTracking](ExecutionTracking.md)






## Identifier and Mapping Information





### Schema Source


* from schema: https://w3id.org/collabri/core




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | core:record_count |
| native | core:record_count |




## LinkML Source

<details>
```yaml
name: record_count
description: Number of records in the dataset.
in_subset:
- execution_tracking
from_schema: https://w3id.org/collabri/core
rank: 1000
owner: Data
domain_of:
- Data
range: integer
minimum_value: 0

```
</details></div>