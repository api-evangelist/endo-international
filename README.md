# Endo International

Endo International was a specialty pharmaceutical company best known for **Xiaflex** (collagenase clostridium histolyticum), branded **urology** and **orthopedics** products, and a large **sterile-injectables and generics** business operated through Par Pharmaceutical. This repository is part of the [API Evangelist Network](https://github.com/api-evangelist) catalog of corporate event histories where the entity has no public software API surface.

## Status: No Public Software API

Endo never operated a public developer program, OpenAPI specification, SDK, CLI, or technology API of any kind. References to "API" on Endo's successor websites refer to pharmaceutical **Active Pharmaceutical Ingredients** (chemical compounds manufactured for inclusion in finished drug products), not software application programming interfaces.

This repo therefore documents the **corporate event history** — Chapter 11, emergence, merger, separation — rather than an API portfolio.

## Corporate Event Timeline

### 2022-08-16 — Chapter 11 Filing
Endo International plc and certain subsidiaries filed voluntary petitions for Chapter 11 protection in the US Bankruptcy Court for the Southern District of New York, citing mass opioid-related litigation tied to its legacy **Opana ER** franchise (a reformulated extended-release oxymorphone product withdrawn in 2017) and the resulting balance-sheet pressure.

### 2024-04-23 — Emergence as Endo, Inc.
Endo emerged from Chapter 11 as **Endo, Inc.**, a privately held company owned by its former creditors. The reorganization reduced funded debt, funded opioid settlement obligations under the broader pharmaceutical national opioid framework, and left the operating portfolio (Xiaflex, urology, orthopedics, sterile injectables, generics) intact.

### 2025-07-31 — Mallinckrodt + Endo Combination
Endo combined with **Mallinckrodt** to form a single specialty pharmaceuticals and generics group. Per the successor site: *"On July 31, 2025, Mallinckrodt and Endo joined together to better serve patients and customers with a bold plan for the future."*

### 2025-11 — Separation into Two Companies
The combined company separated into two independent operating companies:

- **[Keenova Therapeutics](https://www.keenova.com)** — specialty branded therapeutics, covering immunology, urology, hepatology, ophthalmology, orthopedics, and critical care (the home of the former Endo Xiaflex / urology / orthopedics franchises plus Mallinckrodt specialty brands).
- **[Par Health](https://www.parhealth.com)** — generics, sterile injectables (TruDelivery), and pharmaceutical Active Pharmaceutical Ingredients manufacturing; ~4,000 staff, ~200 marketed products, 10 manufacturing sites, distribution to 70+ countries, operator of *"the largest API manufacturing facility in the US."*

Endo no longer operates as a standalone public-facing pharmaceutical company.

## Why This Repo Exists

The API Evangelist Network indexes pharmaceutical issuers because they represent a category where:

- Litigation, reorganization, and consolidation events are the meaningful "API" of the business (regulatory disclosures, court filings, settlement trust reporting).
- The post-Chapter 11 ownership and entity structure is frequently misunderstood in citations to "Endo" (now actually Keenova or Par Health).
- Any future digital, supply-chain, or REST API surface (e.g., DSCSA traceability endpoints, GS1 product master APIs, patient support program portals) would be tracked here for successor entities.

## Files

- [`apis.yml`](apis.yml) — APIs.json index documenting the entity, successors, and the corporate event timeline. The `apis:` list is intentionally empty.

## Related Repositories

- [api-evangelist/mallinckrodt](https://github.com/api-evangelist/mallinckrodt) — merger partner
- [api-evangelist/pharmaceuticals](https://github.com/api-evangelist/pharmaceuticals) — sector topic index
