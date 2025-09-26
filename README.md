# Electricity Supplier Data Validation

This repository contains JSON Schemas used in the **Strompreise Schweiz** project. Schemas define the expected structure of JSON files that energy suppliers (and other partners) publish in their repositories.

By validating your JSON data against these schemas, we ensure consistent and reliable data quality across all suppliers.

## Available Schemas

### Supplier

- **Current version:** `v1`
- **Schema file:** [`supplier/v1/supplier.schema.json`](./supplier/v1/supplier.schema.json)
- **Schema URL (for use in JSON files):** https://raw.githubusercontent.com/Strompreise-Schweiz/supplier-data-validation/main/supplier/v1/supplier.schema.json

## Versioning Strategy

- Each schema type has its own version folder (`v1`, `v2`, …).  
- Changes inside the same version (`v1`) are **non-breaking** (e.g. description updates, optional fields).  
- Breaking changes always result in a **new major version** (e.g. `v2`).  

