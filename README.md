# Nuclia (nuclia)

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
