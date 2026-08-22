# Endo International

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
