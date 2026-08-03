# Azure Networking Services (azure-networking-services)

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

A comprehensive collection of Azure networking APIs for managing virtual networks, load balancers, application gateways, VPN gateways, DNS, and other networking resources.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/azure-networking-services/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Azure, Cloud, Infrastructure, Microsoft, Networking

## Timestamps

- **Created:** 2024-01-15
- **Modified:** 2026-04-19

## APIs

### Azure Networking Services
A comprehensive collection of Azure networking APIs for managing virtual networks, load balancers, application gateways, VPN gateways, DNS, and other networking resources.

**Human URL:** [https://learn.microsoft.com/en-us/azure/networking/](https://learn.microsoft.com/en-us/azure/networking/)

#### Tags:

 - Load Balancer, Networking, Virtual Network

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/azure/networking/)
- [OpenAPI](openapi/azure-networking-services-virtual-network-openapi.yaml)
- [OpenAPI](openapi/azure-networking-services-load-balancer-openapi.yaml)

## Common Properties


## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Virtual Network](openapi/azure-networking-services-virtual-network-openapi.yaml)
- [Load Balancer](openapi/azure-networking-services-load-balancer-openapi.yaml)

### JSON Schema

- [Resource Navigation Link Format](json-schema/azure-networking-services-resource-navigation-link-format-schema.json)
- [Probe Properties Format](json-schema/azure-networking-services-probe-properties-format-schema.json)
- [Load Balancer](json-schema/azure-networking-services-load-balancer-schema.json)
- [Inbound Nat Rule](json-schema/azure-networking-services-inbound-nat-rule-schema.json)
- [Outbound Rule Properties Format](json-schema/azure-networking-services-outbound-rule-properties-format-schema.json)
- [Backend Address Pool Properties Format](json-schema/azure-networking-services-backend-address-pool-properties-format-schema.json)
- [Virtual Network](json-schema/azure-networking-services-virtual-network-schema.json)
- [Inbound Nat Pool](json-schema/azure-networking-services-inbound-nat-pool-schema.json)
- [Load Balancer Frontend Ip Configuration List Result](json-schema/azure-networking-services-load-balancer-frontend-ip-configuration-list-result-schema.json)
- [Virtual Network Bgp Communities](json-schema/azure-networking-services-virtual-network-bgp-communities-schema.json)

### JSON-LD

- [Azure Networking Services Context](json-ld/azure-networking-services-context.jsonld)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Azure Networking Services](capabilities/shared/azure-networking-services.yaml)

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|----------|
| [Azure Networking Services Management](capabilities/azure-networking-services-management.yaml) | Azure Networking Services | 5 | Cloud Engineer |

## Vocabulary

- [Azure Networking Services Vocabulary](vocabulary/azure-networking-services-vocabulary.yaml)

## Rules

- [Azure Networking Services Spectral Rules](rules/azure-networking-services-spectral-rules.yml) — 15 rules enforcing Azure Networking Services API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
