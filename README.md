# ACORD (acord)
ACORD is a global standards-setting body for the insurance industry, providing data standards, reference architecture, and digital tools that enable insurers, brokers, and software providers to exchange information. ACORD produces XML standards for property & casualty, life, annuity, and reinsurance, as well as Next-Generation Digital Standards (NGDS) based on JSON/YAML for modern RESTful APIs and microservices architectures.

**URL:** [Visit APIs.json](https://raw.githubusercontent.com/api-evangelist/acord/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Claims, Insurance, Policy, Standards, Underwriting

## Timestamps

- **Created:** (see apis.yml)
- **Modified:** 2026-04-19

## APIs

### ACORD XML Standards API
ACORD XML Standards define data exchange formats for property & casualty, life, annuity, and reinsurance using SOAP/XML protocols.

**Human URL:** [https://www.acord.org/standards-architecture/acord-data-standards](https://www.acord.org/standards-architecture/acord-data-standards)

#### Tags:

 - ACORD, Claims, Insurance, Policy, Property Casualty, SOAP, XML

#### Properties

- [Documentation](https://www.acord.org/standards-architecture/acord-data-standards)

---

### ACORD Next-Generation Digital Standards (NGDS) API
The ACORD NGDS Object Model provides granular, transaction-centric standards for APIs, microservices, IoT, and RESTful architectures based on JSON and YAML.

**Human URL:** [https://www.acord.org/standards-architecture/acord-data-standards/next-generation-digital-standards](https://www.acord.org/standards-architecture/acord-data-standards/next-generation-digital-standards)

#### Tags:

 - ACORD, Digital Standards, Insurance, IoT, JSON, Microservices, REST

#### Properties

- [Documentation](https://www.acord.org/standards-architecture/acord-data-standards/next-generation-digital-standards)
- [OpenAPI](openapi/acord-ngds-openapi.yml)
- [NaftikoCapability](capabilities/shared/acord-ngds.yaml)

---

### ACORD Reinsurance & Large Commercial Data Standards API
ACORD Global Reinsurance & Large Commercial Data Standards define XML data exchange formats for reinsurance and large commercial lines.

**Human URL:** [https://www.acord.org/standards-architecture/acord-data-standards/Global_Reinsurance_Data_Standards](https://www.acord.org/standards-architecture/acord-data-standards/Global_Reinsurance_Data_Standards)

#### Tags:

 - Data Standards, Insurance, Large Commercial, Reinsurance, XML

#### Properties

- [Documentation](https://www.acord.org/standards-architecture/acord-data-standards/Global_Reinsurance_Data_Standards)

## Common Properties

- [Website](https://www.acord.org)
- [Portal](https://www.acord.org/standards-architecture/acord-data-standards)
- [Documentation](https://www.acord.org/standards-architecture/acord-data-standards)
- [GettingStarted](https://www.acord.org/standards-architecture/acord-data-standards/next-generation-digital-standards)
- [Support](https://www.acord.org/standards-architecture/get-involved/standards-project-advisory-groups)
- [GitHubOrganization](https://github.com/api-evangelist/acord)

## Features

| Name | Description |
|------|-------------|
| XML Data Standards | ACORD XML standards for property & casualty, life, annuity, and reinsurance SOAP/XML data exchange. |
| Next-Generation Digital Standards | JSON/YAML-based NGDS for RESTful APIs, microservices, and IoT insurance data exchange. |
| Reinsurance Standards | Global reinsurance and large commercial data standards for facultative and treaty transactions. |
| Life and Annuity Standards | Electronic data standards for life insurance and annuity products covering underwriting and policy management. |
| Reference Architecture | ACORD reference architecture providing structural frameworks for insurance technology implementations. |

## Use Cases

| Name | Description |
|------|-------------|
| Claims Data Exchange | Standardized ACORD XML or NGDS JSON claims transaction exchange between carriers, adjusters, and reinsurers. |
| Policy Administration | Automated policy issuance, endorsement, and renewal using ACORD NGDS microservices architecture. |
| Underwriting Automation | Straight-through processing of insurance applications using ACORD standardized data elements. |
| Reinsurance Settlement | Facultative and treaty reinsurance data exchange using ACORD Global Reinsurance Data Standards. |
| Regulatory Reporting | Compliance reporting using ACORD-standardized data formats for regulatory submissions. |

## Integrations

| Name | Description |
|------|-------------|
| Insurance Core Systems | Integration with policy administration systems (PAS) and claims management systems (CMS). |
| Reinsurance Platforms | Integration with reinsurance management platforms supporting ACORD AL3 and RIBO formats. |
| Insurtech Solutions | Modern insurtech API platforms consuming ACORD NGDS JSON standards. |
| Regulatory Systems | Integration with state and national insurance regulatory reporting systems. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [ACORD NGDS API](openapi/acord-ngds-openapi.yml)

### JSON Schema

- [ACORD Policy Schema](json-schema/acord-policy-schema.json)
- [ACORD Claim Schema](json-schema/acord-claim-schema.json)
- [NGDS Policy Request Schema](json-schema/ngds-policy-request-schema.json)
- [NGDS Claim Request Schema](json-schema/ngds-claim-request-schema.json)
- [NGDS Party Schema](json-schema/ngds-party-schema.json)
- [NGDS Coverage Schema](json-schema/ngds-coverage-schema.json)
- [NGDS Address Schema](json-schema/ngds-address-schema.json)
- [NGDS Underwriting Submission Schema](json-schema/ngds-underwriting-submission-schema.json)

### JSON Structure

- [NGDS Policy Structure](json-structure/ngds-policy-structure.json)
- [NGDS Claim Structure](json-structure/ngds-claim-structure.json)
- [NGDS Party Structure](json-structure/ngds-party-structure.json)
- [NGDS Address Structure](json-structure/ngds-address-structure.json)

### JSON-LD

- [ACORD Context](json-ld/acord-context.jsonld)
- [ACORD NGDS Context](json-ld/acord-ngds-context.jsonld)

### Examples

- [NGDS Policy Example](examples/ngds-policy-example.json)
- [NGDS Claim Example](examples/ngds-claim-example.json)
- [NGDS Party Example](examples/ngds-party-example.json)
- [ACORD Policy Example](examples/acord-policy-example.json)
- [ACORD Claim Example](examples/acord-claim-example.json)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [ACORD NGDS API](capabilities/shared/acord-ngds.yaml) — 10 operations for insurance data exchange

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Insurance Data Exchange](capabilities/insurance-data-exchange.yaml) | ACORD NGDS | 10 | Insurance Carrier, Broker, Reinsurer |

## Vocabulary

- [ACORD Vocabulary](vocabulary/acord-vocabulary.yaml) — Unified taxonomy mapping 4 resources, 5 actions, 1 workflow, and 3 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [ACORD Spectral Rules](rules/acord-spectral-rules.yml) — 30+ rules across 13 categories enforcing ACORD API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
