---
search:
  boost: 10.0
---

# Class: Versioned 


_Mixin: per-element version metadata, aligned with PAV and PROV. Element IRI is `<id>/<version>` and an element may have multiple version-snapshots that share an `id`._



<div data-search-exclude markdown="1">



URI: [core:Versioned](https://w3id.org/collabri/core/Versioned)





```mermaid
 classDiagram
    class Versioned
    click Versioned href "../Versioned/"
      Versioned <|-- TaskTeam
        click TaskTeam href "../TaskTeam/"
      Versioned <|-- Task
        click Task href "../Task/"
      Versioned <|-- Subtask
        click Subtask href "../Subtask/"
      Versioned <|-- Milestone
        click Milestone href "../Milestone/"
      Versioned <|-- Deliverable
        click Deliverable href "../Deliverable/"
      
      Versioned : authored_by
        
      Versioned : created_on
        
      Versioned : current_version
        
      Versioned : previous_version
        
      Versioned : version
        
      
```




<!-- no inheritance hierarchy -->

## Class Properties

| Property | Value |
| --- | --- |
| Mixin | Yes |


## Slots

| Name | Cardinality and Range | Description | Inheritance |
| ---  | --- | --- | --- |
| [version](version.md) | 0..1 <br/> [String](String.md) | Semantic version of this element | direct |
| [previous_version](previous_version.md) | 0..1 <br/> [Uriorcurie](Uriorcurie.md) | IRI of the immediately prior version of this element | direct |
| [current_version](current_version.md) | 0..1 <br/> [Boolean](Boolean.md) | True iff this is the current accepted version of the element | direct |
| [created_on](created_on.md) | 0..1 <br/> [Date](Date.md) | Date this version snapshot was created | direct |
| [authored_by](authored_by.md) | * <br/> [Uriorcurie](Uriorcurie.md) | Author(s) of this version snapshot | direct |



## Mixin Usage

| mixed into | description |
| --- | --- |
| [TaskTeam](TaskTeam.md) | Root of a Statement of Work, scoped to a single contract |
| [Task](Task.md) | Thematic bucket of work, possibly spanning the full award |
| [Subtask](Subtask.md) | A step toward completion of a Task |
| [Milestone](Milestone.md) | A milestone groups subtasks (linked via Subtask |
| [Deliverable](Deliverable.md) | A concrete, acceptance-bearing output owed for a payable subtask |














## Identifier and Mapping Information





### Schema Source


* from schema: https://w3id.org/collabri/core




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | core:Versioned |
| native | core:Versioned |






## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>
```yaml
name: Versioned
description: 'Mixin: per-element version metadata, aligned with PAV and PROV. Element
  IRI is `<id>/<version>` and an element may have multiple version-snapshots that
  share an `id`.'
from_schema: https://w3id.org/collabri/core
mixin: true
attributes:
  version:
    name: version
    description: Semantic version of this element.
    in_subset:
    - sow_spec
    - execution_tracking
    from_schema: https://w3id.org/collabri/core
    rank: 1000
    slot_uri: pav:version
    domain_of:
    - Versioned
  previous_version:
    name: previous_version
    description: IRI of the immediately prior version of this element.
    in_subset:
    - execution_tracking
    from_schema: https://w3id.org/collabri/core
    rank: 1000
    slot_uri: pav:previousVersion
    domain_of:
    - Versioned
    range: uriorcurie
  current_version:
    name: current_version
    description: True iff this is the current accepted version of the element.
    in_subset:
    - execution_tracking
    from_schema: https://w3id.org/collabri/core
    rank: 1000
    slot_uri: pav:hasCurrentVersion
    domain_of:
    - Versioned
    range: boolean
  created_on:
    name: created_on
    description: Date this version snapshot was created.
    in_subset:
    - sow_spec
    - execution_tracking
    from_schema: https://w3id.org/collabri/core
    rank: 1000
    slot_uri: pav:createdOn
    domain_of:
    - Versioned
    range: date
  authored_by:
    name: authored_by
    description: Author(s) of this version snapshot.
    in_subset:
    - sow_spec
    - execution_tracking
    from_schema: https://w3id.org/collabri/core
    rank: 1000
    slot_uri: pav:authoredBy
    domain_of:
    - Versioned
    range: uriorcurie
    multivalued: true

```
</details>

### Induced

<details>
```yaml
name: Versioned
description: 'Mixin: per-element version metadata, aligned with PAV and PROV. Element
  IRI is `<id>/<version>` and an element may have multiple version-snapshots that
  share an `id`.'
from_schema: https://w3id.org/collabri/core
mixin: true
attributes:
  version:
    name: version
    description: Semantic version of this element.
    in_subset:
    - sow_spec
    - execution_tracking
    from_schema: https://w3id.org/collabri/core
    rank: 1000
    slot_uri: pav:version
    owner: Versioned
    domain_of:
    - Versioned
    range: string
  previous_version:
    name: previous_version
    description: IRI of the immediately prior version of this element.
    in_subset:
    - execution_tracking
    from_schema: https://w3id.org/collabri/core
    rank: 1000
    slot_uri: pav:previousVersion
    owner: Versioned
    domain_of:
    - Versioned
    range: uriorcurie
  current_version:
    name: current_version
    description: True iff this is the current accepted version of the element.
    in_subset:
    - execution_tracking
    from_schema: https://w3id.org/collabri/core
    rank: 1000
    slot_uri: pav:hasCurrentVersion
    owner: Versioned
    domain_of:
    - Versioned
    range: boolean
  created_on:
    name: created_on
    description: Date this version snapshot was created.
    in_subset:
    - sow_spec
    - execution_tracking
    from_schema: https://w3id.org/collabri/core
    rank: 1000
    slot_uri: pav:createdOn
    owner: Versioned
    domain_of:
    - Versioned
    range: date
  authored_by:
    name: authored_by
    description: Author(s) of this version snapshot.
    in_subset:
    - sow_spec
    - execution_tracking
    from_schema: https://w3id.org/collabri/core
    rank: 1000
    slot_uri: pav:authoredBy
    owner: Versioned
    domain_of:
    - Versioned
    range: uriorcurie
    multivalued: true

```
</details></div>