# ACORD (acord)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

ACORD is a global standards-setting body for the insurance industry, providing data standards, reference architecture, and digital tools that enable insurers, brokers, and software providers to exchange information.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/acord/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/acord/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Claims
- Insurance
- Policy
- Standards
- Underwriting

## Timestamps

- **Modified:** 2026-04-19

## APIs

### ACORD XML Standards API

ACORD XML Standards define data exchange formats for property & casualty, life, annuity, and reinsurance using SOAP/XML protocols. APIs enable claims inquiry, policy administration, and regulatory reporting across insurers, reinsurers, and intermediaries.

- **Human URL:** [https://www.acord.org/standards-architecture/acord-data-standards](https://www.acord.org/standards-architecture/acord-data-standards)
- **Base URL:** `https://claims.insurer-internal.example.com/acord`

#### Tags

- ACORD
- Claims
- Insurance
- Policy
- Property Casualty
- SOAP
- XML

#### Properties

- [Documentation](https://www.acord.org/standards-architecture/acord-data-standards)
- [Reference](https://www.acord.org/standards-architecture/acord-data-standards)
- [Postman Collection](collections/acord-ngds.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/acord-ngds.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### ACORD Next-Generation Digital Standards (NGDS) API

The ACORD Next-Generation Digital Standards (NGDS) Object Model provides granular, transaction-centric standards for APIs, microservices, IoT, and RESTful architectures. Based on JSON and YAML data-interchange formats, NGDS enables modern insurance data exchange for underwriting, policy management, and claims administration.

- **Human URL:** [https://www.acord.org/standards-architecture/acord-data-standards/next-generation-digital-standards](https://www.acord.org/standards-architecture/acord-data-standards/next-generation-digital-standards)
- **Base URL:** `https://api.insurer-internal.example.com/ngds`

#### Tags

- ACORD
- Digital Standards
- Insurance
- IoT
- JSON
- Microservices
- REST

#### Properties

- [Documentation](https://www.acord.org/standards-architecture/acord-data-standards/next-generation-digital-standards)
- [Reference](https://www.acord.org/standards-architecture/acord-data-standards/next-generation-digital-standards)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/acord/refs/heads/main/openapi/acord-ngds-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/acord/refs/heads/main/json-schema/ngds-policy-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/acord/refs/heads/main/json-schema/ngds-claim-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/acord/refs/heads/main/json-schema/ngds-party-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/acord/refs/heads/main/json-schema/ngds-coverage-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/acord/refs/heads/main/json-schema/ngds-underwriting-submission-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Postman Collection](collections/acord-ngds.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/acord-ngds.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### ACORD Reinsurance & Large Commercial Data Standards API

ACORD Global Reinsurance & Large Commercial Data Standards define XML data exchange formats for reinsurance and large commercial lines. APIs support facultative and treaty reinsurance transactions, placement, and settlement between cedants, reinsurers, and brokers.

- **Human URL:** [https://www.acord.org/standards-architecture/acord-data-standards/Global_Reinsurance_Data_Standards](https://www.acord.org/standards-architecture/acord-data-standards/Global_Reinsurance_Data_Standards)
- **Base URL:** `https://reinsurance.insurer-internal.example.com/acord`

#### Tags

- Data Standards
- Insurance
- Large Commercial
- Reinsurance
- XML

#### Properties

- [Documentation](https://www.acord.org/standards-architecture/acord-data-standards/Global_Reinsurance_Data_Standards)
- [Postman Collection](collections/acord-ngds.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/acord-ngds.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/acord)
- [Website](https://www.acord.org)
- [Portal](https://www.acord.org/standards-architecture/acord-data-standards)
- [Documentation](https://www.acord.org/standards-architecture/acord-data-standards)
- [Getting Started](https://www.acord.org/standards-architecture/acord-data-standards/next-generation-digital-standards)
- [Documentation](https://www.acord.org/standards-architecture/reference-architecture)
- [Support](https://www.acord.org/standards-architecture/get-involved/standards-project-advisory-groups)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/acord/refs/heads/main/openapi/acord-ngds-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/acord/refs/heads/main/json-schema/acord-policy-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/acord/refs/heads/main/json-schema/acord-claim-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [J S O N L D Context](https://raw.githubusercontent.com/api-evangelist/acord/refs/heads/main/json-ld/acord-context.jsonld)
- [GitHub Organization](https://github.com/api-evangelist/acord)
- [Spectral Rules](https://raw.githubusercontent.com/api-evangelist/acord/refs/heads/main/rules/acord-spectral-rules.yml)
- [Vocabulary](https://raw.githubusercontent.com/api-evangelist/acord/refs/heads/main/vocabulary/acord-vocabulary.yaml)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)

## Maintainers

**Email:** kin@apievangelist.com
