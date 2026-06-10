# Collabri Core Schema

[![w3id](https://img.shields.io/badge/w3id-collabri%2Fcore-blue)](https://w3id.org/collabri/core)

The foundational Collabri schema. Defines a single, unambiguous vocabulary
for contract-scoped Statements of Work, with `TaskTeam` → `Task` →
recursive `Subtask` → typed `Deliverable` subclasses; structured
`Objective`, `Metric`, and `AcceptanceCriterion` classes;
Milestone-gated payment with per-org breakdowns; and a first-class
change-management layer (`ChangeProposal` / `Change` / `Approval`) —
"GitHub for contracts."

## Canonical IRI

```
https://w3id.org/collabri/core
```

Term IRIs resolve under this base. Class IRIs use the form
`https://w3id.org/collabri/core/{ClassName}`. Slots and enums follow the
same pattern. Permanent opaque `COLLABRI_0000nnn` IDs will replace the
current name-based URIs at 1.0.

## Status

**Draft (v0.5.0).** The model has been pilot-tested against one real
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

- `core.yaml` — the LinkML source schema.
- `core_docs/` — generated docs (run `gen-doc core.yaml -d core_docs/`).
- `core.json` — JSON Schema export (run `gen-json-schema core.yaml > core.json`).

## Build

```bash
pip install linkml
gen-doc core.yaml -d core_docs/
gen-json-schema core.yaml > core.json
linkml-validate -s core.yaml <your-instance.yaml>
```

## License

CC BY 4.0.

## Citation

> McMurry J. and contributors. *Collabri Core Schema.*
> https://w3id.org/collabri/core
