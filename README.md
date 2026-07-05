# Collabri Core Schema

[![w3id](https://img.shields.io/badge/w3id-collabri%2Fcore-blue)](https://w3id.org/collabri/core)

The foundational Collabri schema. Defines a single, unambiguous vocabulary
for contract-scoped Statements of Work and the budget structure that
accompanies them, covering:

- the **work hierarchy** — `TaskTeam` → `Task` → recursive `Subtask` →
  typed `Deliverable` subclasses (`Activity`, `Data`, `Method`,
  `NarrativeDocument`, `Software`, `Standard`);
- **structured evaluation** — `Objective` (the aim) as a sibling to
  `Deliverable` (the artifact), with `Metric` and `AcceptanceCriterion`
  as structured classes carrying per-metric rationale and per-criterion
  verification method;
- the full **budget view** — `contract_value` at the `TaskTeam` level,
  Milestone-gated payments with sponsor- vs prime-payable distinctions,
  per-organization breakdowns (`OrgPayableValue`) on the prime side, and
  `Payment` obligations with `fixed` / `percent_complete` /
  `cost_reimbursement` bases. A TDD instance also functions as a budget
  instance that rolls up cleanly from subtask milestones to the contract
  total;
- a first-class **change-management layer** — `ChangeProposal` / `Change`
  / `Approval` ("GitHub for contracts"), with PAV-aligned version
  metadata on every addressable element.

**Security vocabulary** (participation, authorization decisions, tamper-evident
audit exports) lives in the sibling module [`security.yaml`](security.yaml)
(`https://w3id.org/collabri/security`). It imports `Person` and `Organization`
from Core — no duplicate agent types.

## Canonical IRI

```
https://w3id.org/collabri/core
```

Term IRIs resolve under this base. Class IRIs use the form
`https://w3id.org/collabri/core/{ClassName}`. Slots and enums follow the
same pattern. Permanent opaque `COLLABRI_0000nnn` IDs will replace the
current name-based URIs at 1.0.

## Status

**Draft (v0.5.4).** The model has been pilot-tested against one real
SOW (RAPID) but has not been bound to permanent term IDs yet. See
`docs/governance.md` (TBD) for the versioning and deprecation policy.

## Layered alignments

The schema reuses external IRIs where mature classes already exist and
specializes existing classes where Collabri adds structure. It mints
under `collabri/core` only what isn't already there.

- **Reused directly** — `cco:ont00001180` (Organization),
  `cco:ont00001262` (Person), `schema:MonetaryAmount` (Money).
- **Specialized** — `Program` (`gist:Agreement`), `Subtask`
  (`cco:ont00000005` Act, also `frapo:Task`).
- **Aligned (close/related mappings)** — FIBO Contracts (primary),
  ODRL (obligations/duties), FRAPO (project resources and processes),
  PROV-O + PAV (provenance + versioning), W3C Org, FOAF, schema.org,
  Dublin Core, DCAT, DOAP, SPAR/FaBiO, IAO, ADMS, gist. CCO Act is
  the canonical parent for `Subtask`; CCO Information Content Entity
  is the close-mapping target for the information-artifact subclasses
  of `Deliverable`.

## Files

- `core.yaml` — contracting and budget LinkML schema.
- `security.yaml` — participation, authorization, and audit export vocabulary.
- `core_docs/` — generated docs (run `gen-doc core.yaml -d core_docs/`).
- `core.json` — JSON Schema export (run `gen-json-schema core.yaml > core.json`).

## Build

```bash
pip install linkml
gen-doc core.yaml -d core_docs/
gen-doc security.yaml -d security_docs/
gen-json-schema core.yaml > core.json
gen-json-schema security.yaml > security.json
linkml-validate -s core.yaml <your-instance.yaml>
linkml-validate -s security.yaml <your-audit-export.yaml>
```

## License

CC BY 4.0.

## Citation

> McMurry J. and contributors. *Collabri Core Schema.*
> https://w3id.org/collabri/core
