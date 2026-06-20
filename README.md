# Nuclia (nuclia)

Nuclia is a RAG-as-a-Service / AI search platform (now part of Progress as Progress Agentic RAG). It ingests unstructured data - documents, files, audio, video, web pages and conversations - into Knowledge Boxes, automatically extracting, embedding and indexing it so applications can run hybrid (semantic, keyword, graph) search and get grounded generative answers through a regional REST API.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/nuclia/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/nuclia/refs/heads/main/apis.yml)

## Tags

- AI
- RAG
- Search
- Knowledge Base
- Unstructured Data

## Timestamps

- **Created:** 2026-06-20
- **Modified:** 2026-06-20

## APIs

### Nuclia Knowledge Boxes API

Create, configure and inspect Knowledge Boxes - the indexed collections of unstructured data - including counters, label sets, synonyms, entities and model configuration.

- **Human URL:** [https://docs.nuclia.dev/docs/api](https://docs.nuclia.dev/docs/api)
- **Base URL:** `https://{zone}.nuclia.cloud/api/v1`

#### Tags

- Knowledge Boxes
- Configuration
- Labels

#### Properties

- [Documentation](https://docs.nuclia.dev/docs/management/knowledgebox/)
- [API Reference](https://docs.nuclia.dev/docs/api)
- [OpenAPI](openapi/nuclia-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/nuclia.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/nuclia.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Nuclia Resources & Ingestion API

Create, list, read, modify and delete resources, and upload binaries (including TUS resumable uploads and direct Knowledge Box upload) into Nuclia's extraction, embedding and indexing pipeline.

- **Human URL:** [https://docs.nuclia.dev/docs/api](https://docs.nuclia.dev/docs/api)
- **Base URL:** `https://{zone}.nuclia.cloud/api/v1`

#### Tags

- Resources
- Ingestion
- Upload

#### Properties

- [Documentation](https://docs.nuclia.dev/docs/ingestion/)
- [API Reference](https://docs.nuclia.dev/docs/api)
- [OpenAPI](openapi/nuclia-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/nuclia.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/nuclia.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Nuclia Search & Find API

Hybrid search combining semantic, keyword, fulltext and graph search, the find endpoint optimized for RAG context retrieval, plus suggest autocomplete over a Knowledge Box.

- **Human URL:** [https://docs.nuclia.dev/docs/rag/search-strategy/](https://docs.nuclia.dev/docs/rag/search-strategy/)
- **Base URL:** `https://{zone}.nuclia.cloud/api/v1`

#### Tags

- Search
- Find
- Semantic Search

#### Properties

- [Documentation](https://docs.nuclia.dev/docs/rag/search-strategy/)
- [API Reference](https://docs.nuclia.dev/docs/api)
- [OpenAPI](openapi/nuclia-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/nuclia.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/nuclia.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Nuclia Ask & Chat (RAG) API

Generative RAG answers grounded in a Knowledge Box - the ask/chat endpoint retrieves context, builds a prompt and returns a cited answer, streamed as newline-delimited JSON / SSE, plus document summarization.

- **Human URL:** [https://docs.nuclia.dev/docs/rag/](https://docs.nuclia.dev/docs/rag/)
- **Base URL:** `https://{zone}.nuclia.cloud/api/v1`

#### Tags

- Ask
- Chat
- RAG
- Generative

#### Properties

- [Documentation](https://docs.nuclia.dev/docs/rag/)
- [API Reference](https://docs.nuclia.dev/docs/api)
- [OpenAPI](openapi/nuclia-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [AsyncAPI](asyncapi/nuclia-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Postman Collection](collections/nuclia.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/nuclia.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Nuclia Predict (NUA) API

The Nuclia Understanding API - generative chat/completions, summarize, rephrase, rerank, sentence embeddings and token/NER extraction - authenticated with a NUA key.

- **Human URL:** [https://docs.nuclia.dev/docs/nua-api/](https://docs.nuclia.dev/docs/nua-api/)
- **Base URL:** `https://{zone}.nuclia.cloud/api/v1`

#### Tags

- Predict
- NUA
- Embeddings
- Tokens

#### Properties

- [Documentation](https://docs.nuclia.dev/docs/understanding/intro)
- [API Reference](https://docs.nuclia.dev/docs/nua-api/)
- [OpenAPI](openapi/nuclia-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/nuclia.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/nuclia.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/nuclia)
- [LinkedIn](https://www.linkedin.com/company/nuclia)
- [Website](https://nuclia.com/)
- [Documentation](https://docs.nuclia.dev/docs)
- [Plans](plans/nuclia-plans-pricing.yml)
- [Rate Limits](rate-limits/nuclia-rate-limits.yml)
- [Fin Ops](finops/nuclia-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
