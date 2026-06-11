---
search:
  boost: 2.0
---


# Enum: PayerType 




_A party that owes payment on milestone acceptance._



<div data-search-exclude markdown="1">

URI: [core:PayerTypeScheme](https://w3id.org/collabri/core/PayerTypeScheme)

**Enum URI:** [core:PayerTypeScheme](https://w3id.org/collabri/core/PayerTypeScheme)


## Permissible Values
| Value | Meaning | Description |
| --- | --- | --- |
| sponsor | None | The government sponsor pays on acceptance (sponsor-payable) |
| prime | None | The prime contractor pays on acceptance (prime-payable) |




## Slots

| Name | Description |
| ---  | --- |
| [payable_by](payable_by.md) | Which parties owe payment on acceptance of the milestone gating this subtask |










## Identifier and Mapping Information





### Schema Source


* from schema: https://w3id.org/collabri/core






## LinkML Source

<details>
```yaml
name: PayerType
description: A party that owes payment on milestone acceptance.
from_schema: https://w3id.org/collabri/core
related_mappings:
- fibo_ctr:ContractParty
rank: 1000
enum_uri: core:PayerTypeScheme
permissible_values:
  sponsor:
    text: sponsor
    description: The government sponsor pays on acceptance (sponsor-payable).
  prime:
    text: prime
    description: The prime contractor pays on acceptance (prime-payable).

```
</details>

</div>