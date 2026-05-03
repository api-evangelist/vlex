# vLex

vLex (part of Clio) is a global legal intelligence platform that applies AI to ingest, enrich, classify, and deliver insights from over 100 million legal documents across 2,000+ multilingual sources. The vLex Iceberg platform provides APIs for legal document search, anonymization, classification, key phrase extraction, and citation detection.

**Human URL:** https://vlex.com  
**Developer Portal:** https://developer.vlex.com  
**APIs.json:** https://raw.githubusercontent.com/api-evangelist/vlex/refs/heads/main/apis.yml

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

AI, Classification, Legal Research, Legal Tech, Natural Language Processing, Privacy

## APIs

### vLex Iceberg Anonymization API

Identifies and anonymizes personally identifiable information in legal text. Pre-trained on legal data for high accuracy on court documents and contracts.

**Human URL:** https://developer.vlex.com/apis

#### Properties

- [Documentation](https://developer.vlex.com/apis)
- [OpenAPI](openapi/vlex-iceberg-anonymization-openapi.yml)

---

### vLex Iceberg Legal Research API

AI-powered legal document search, classification, key phrase extraction, and vCite citation detection across 100M+ documents.

**Human URL:** https://developer.vlex.com/apis

#### Properties

- [Documentation](https://developer.vlex.com/apis)
- [OpenAPI](openapi/vlex-iceberg-legal-research-openapi.yml)

---

## OpenAPI Specifications

| File | Description |
|---|---|
| [vlex-iceberg-anonymization-openapi.yml](openapi/vlex-iceberg-anonymization-openapi.yml) | Anonymize text and extract named entities |
| [vlex-iceberg-legal-research-openapi.yml](openapi/vlex-iceberg-legal-research-openapi.yml) | Search, retrieve, classify, key phrases, and citation detection |

## Spectral Rules

| File | Description |
|---|---|
| [vlex-rules.yml](rules/vlex-rules.yml) | Spectral ruleset for vLex Iceberg API conventions |

## Naftiko Capabilities

### Shared Definitions

| File | APIs |
|---|---|
| [shared/iceberg-anonymization.yaml](capabilities/shared/iceberg-anonymization.yaml) | vLex Anonymization API |
| [shared/iceberg-legal-research.yaml](capabilities/shared/iceberg-legal-research.yaml) | vLex Legal Research API |

### Workflow Capabilities

| File | Description |
|---|---|
| [legal-ai-workflow.yaml](capabilities/legal-ai-workflow.yaml) | Unified REST + MCP for legal research, review, and privacy workflows |

## JSON Schema

| File | Description |
|---|---|
| [vlex-legal-document-schema.json](json-schema/vlex-legal-document-schema.json) | Legal document schema with full text, metadata, and citations |

## JSON Structure

| File | Description |
|---|---|
| [vlex-legal-document-structure.json](json-structure/vlex-legal-document-structure.json) | Field-level structure for vLex Legal Document |

## JSON-LD Context

| File | Description |
|---|---|
| [vlex-context.jsonld](json-ld/vlex-context.jsonld) | Linked data context aligned with schema.org/LegalCase and dct |

## Examples

| File | Description |
|---|---|
| [vlex-iceberg-anonymization-anonymize-text-example.json](examples/vlex-iceberg-anonymization-anonymize-text-example.json) | Anonymize PII in case law text |

## Vocabulary

| File | Description |
|---|---|
| [vlex-vocabulary.yml](vocabulary/vlex-vocabulary.yml) | vLex terminology: Iceberg, IceNet, vCite, Anonymization, Jurisdiction, Practice Area |

## Common Properties

- [Website](https://vlex.com/)
- [Developer Portal](https://developer.vlex.com/)
- [Reference](https://developer.vlex.com/apis)
- [Iceberg AI](https://vlex.com/iceberg-ai)
- [Use Cases](https://developer.vlex.com/use-cases)
- [Integrations](https://vlex.com/integrations)
- [GitHub Organization](https://github.com/vlex)
- [Support](https://support.vlex.com/)

## Maintainers

**FN:** Kin Lane  
**Email:** kin@apievangelist.com
