# Northwind Data Lab — Public Data Catalog

This repository maintains the public data catalog for the Northwind Data Lab platform.

- `catalog.json` — the authoritative machine-readable catalog of published datasets.
- Every published dataset is released on the Hugging Face Hub as a dataset repository.

## Compliance Policy

Every published dataset must be released under the **same license** as its upstream
source dataset. The Data Governance team audits each published asset and records the
outcome in the dataset's Hugging Face card (`README.md`), specifically the `license`
field in the YAML front matter.
