# Azure Networking Services (azure-networking-services)
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
