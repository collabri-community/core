---
search:
  boost: 2.0
---


# Enum: StandardSubtype 




_Kinds of standards, ADMS-aligned where applicable._



<div data-search-exclude markdown="1">

URI: [core:StandardSubtypeScheme](https://w3id.org/collabri/core/StandardSubtypeScheme)

**Enum URI:** [core:StandardSubtypeScheme](https://w3id.org/collabri/core/StandardSubtypeScheme)


## Permissible Values
| Value | Meaning | Description |
| --- | --- | --- |
| data_standard | None |  |
| controlled_vocabulary | None |  |
| schema | None |  |
| methodology | None |  |
| reporting_standard | None |  |
| other | None |  |




## Slots

| Name | Description |
| ---  | --- |
| [standard_subtype](standard_subtype.md) | Kind of standard (ADMS-aligned) |










## Identifier and Mapping Information





### Schema Source


* from schema: https://w3id.org/collabri/core






## LinkML Source

<details>
```yaml
name: StandardSubtype
description: Kinds of standards, ADMS-aligned where applicable.
from_schema: https://w3id.org/collabri/core
close_mappings:
- adms:Asset
rank: 1000
enum_uri: core:StandardSubtypeScheme
permissible_values:
  data_standard:
    text: data_standard
  controlled_vocabulary:
    text: controlled_vocabulary
  schema:
    text: schema
  methodology:
    text: methodology
  reporting_standard:
    text: reporting_standard
  other:
    text: other

```
</details>

</div>