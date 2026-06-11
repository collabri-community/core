---
search:
  boost: 10.0
---

# Class: Obligation 


_Abstract base for any contractual duty (ODRL pattern). Concrete subclasses model payment, reporting cadence, etc._



<div data-search-exclude markdown="1">


* __NOTE__: this is an abstract class and should not be instantiated directly


URI: [core:Obligation](https://w3id.org/collabri/core/Obligation)





```mermaid
 classDiagram
    class Obligation
    click Obligation href "../Obligation/"
      Core <|-- Obligation
        click Core href "../Core/"
      

      Obligation <|-- Payment
        click Payment href "../Payment/"
      Obligation <|-- ReportingObligation
        click ReportingObligation href "../ReportingObligation/"
      

      Obligation : action
        
      Obligation : assignee
        
          
    
        
        
        Obligation --> "0..1" Party : assignee
        click Party href "../Party/"
    

        
      Obligation : assigner
        
          
    
        
        
        Obligation --> "0..1" Party : assigner
        click Party href "../Party/"
    

        
      Obligation : description
        
      Obligation : id
        
      Obligation : name
        
      Obligation : obligation_class
        
      Obligation : terms_ref
        
      
```





## Inheritance
* [Core](Core.md)
    * **Obligation**
        * [Payment](Payment.md)
        * [ReportingObligation](ReportingObligation.md)


## Slots

| Name | Cardinality and Range | Description | Inheritance |
| ---  | --- | --- | --- |
| [obligation_class](obligation_class.md) | 0..1 <br/> [String](String.md) | Discriminator for the concrete Obligation subclass | direct |
| [assigner](assigner.md) | 0..1 <br/> [Party](Party.md) | Party imposing the obligation | direct |
| [assignee](assignee.md) | 0..1 <br/> [Party](Party.md) | Party bound by the obligation | direct |
| [action](action.md) | 0..1 <br/> [String](String.md) | ODRL action term or local action label (e | direct |
| [terms_ref](terms_ref.md) | 0..1 <br/> [String](String.md) | Pointer to the governing contract clause | direct |
| [id](id.md) | 1 <br/> [String](String.md) | Stable identifier; together with version forms the element IRI | [Core](Core.md) |
| [name](name.md) | 1 <br/> [String](String.md) | Human-readable name | [Core](Core.md) |
| [description](description.md) | 0..1 <br/> [String](String.md) | Narrative description | [Core](Core.md) |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [TaskTeam](TaskTeam.md) | [obligations](obligations.md) | range | [Obligation](Obligation.md) |












## Identifier and Mapping Information





### Schema Source


* from schema: https://w3id.org/collabri/core




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | core:Obligation |
| native | core:Obligation |
| close | odrl:Duty, fibo_ctr:ContractualCommitment |






## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>
```yaml
name: Obligation
description: Abstract base for any contractual duty (ODRL pattern). Concrete subclasses
  model payment, reporting cadence, etc.
from_schema: https://w3id.org/collabri/core
close_mappings:
- odrl:Duty
- fibo_ctr:ContractualCommitment
is_a: Core
abstract: true
attributes:
  obligation_class:
    name: obligation_class
    description: Discriminator for the concrete Obligation subclass.
    in_subset:
    - sow_spec
    - execution_tracking
    from_schema: https://w3id.org/collabri/core
    rank: 1000
    domain_of:
    - Obligation
  assigner:
    name: assigner
    description: Party imposing the obligation.
    in_subset:
    - sow_spec
    - execution_tracking
    from_schema: https://w3id.org/collabri/core
    rank: 1000
    slot_uri: odrl:assigner
    domain_of:
    - Obligation
    range: Party
  assignee:
    name: assignee
    description: Party bound by the obligation.
    in_subset:
    - sow_spec
    - execution_tracking
    from_schema: https://w3id.org/collabri/core
    rank: 1000
    slot_uri: odrl:assignee
    domain_of:
    - Obligation
    range: Party
  action:
    name: action
    description: ODRL action term or local action label (e.g. "report", "deliver",
      "pay").
    in_subset:
    - sow_spec
    - execution_tracking
    from_schema: https://w3id.org/collabri/core
    rank: 1000
    slot_uri: odrl:action
    domain_of:
    - Obligation
  terms_ref:
    name: terms_ref
    description: Pointer to the governing contract clause.
    in_subset:
    - sow_spec
    - execution_tracking
    from_schema: https://w3id.org/collabri/core
    rank: 1000
    domain_of:
    - Obligation

```
</details>

### Induced

<details>
```yaml
name: Obligation
description: Abstract base for any contractual duty (ODRL pattern). Concrete subclasses
  model payment, reporting cadence, etc.
from_schema: https://w3id.org/collabri/core
close_mappings:
- odrl:Duty
- fibo_ctr:ContractualCommitment
is_a: Core
abstract: true
attributes:
  obligation_class:
    name: obligation_class
    description: Discriminator for the concrete Obligation subclass.
    in_subset:
    - sow_spec
    - execution_tracking
    from_schema: https://w3id.org/collabri/core
    rank: 1000
    owner: Obligation
    domain_of:
    - Obligation
    range: string
  assigner:
    name: assigner
    description: Party imposing the obligation.
    in_subset:
    - sow_spec
    - execution_tracking
    from_schema: https://w3id.org/collabri/core
    rank: 1000
    slot_uri: odrl:assigner
    owner: Obligation
    domain_of:
    - Obligation
    range: Party
  assignee:
    name: assignee
    description: Party bound by the obligation.
    in_subset:
    - sow_spec
    - execution_tracking
    from_schema: https://w3id.org/collabri/core
    rank: 1000
    slot_uri: odrl:assignee
    owner: Obligation
    domain_of:
    - Obligation
    range: Party
  action:
    name: action
    description: ODRL action term or local action label (e.g. "report", "deliver",
      "pay").
    in_subset:
    - sow_spec
    - execution_tracking
    from_schema: https://w3id.org/collabri/core
    rank: 1000
    slot_uri: odrl:action
    owner: Obligation
    domain_of:
    - Obligation
    range: string
  terms_ref:
    name: terms_ref
    description: Pointer to the governing contract clause.
    in_subset:
    - sow_spec
    - execution_tracking
    from_schema: https://w3id.org/collabri/core
    rank: 1000
    owner: Obligation
    domain_of:
    - Obligation
    range: string
  id:
    name: id
    description: Stable identifier; together with version forms the element IRI.
    in_subset:
    - sow_spec
    - execution_tracking
    from_schema: https://w3id.org/collabri/core
    exact_mappings:
    - schema:identifier
    rank: 1000
    slot_uri: dcterms:identifier
    identifier: true
    owner: Obligation
    domain_of:
    - Core
    - Change
    - Organization
    - Person
    range: string
    required: true
  name:
    name: name
    description: Human-readable name.
    in_subset:
    - sow_spec
    - execution_tracking
    from_schema: https://w3id.org/collabri/core
    exact_mappings:
    - dcterms:title
    - foaf:name
    rank: 1000
    slot_uri: schema:name
    owner: Obligation
    domain_of:
    - Core
    - Metric
    - Organization
    - Person
    range: string
    required: true
  description:
    name: description
    description: Narrative description.
    in_subset:
    - sow_spec
    - execution_tracking
    from_schema: https://w3id.org/collabri/core
    exact_mappings:
    - schema:description
    rank: 1000
    slot_uri: dcterms:description
    owner: Obligation
    domain_of:
    - Core
    range: string

```
</details></div>