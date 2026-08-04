# IBM MQ (ibm-mq)

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

APIs for IBM MQ messaging middleware for enterprise integration.

**APIs.json:** [https://www.ibm.com/products/mq](https://www.ibm.com/products/mq)

## Tags

- Async
- Enterprise
- Integration
- Messaging
- Middleware
- Queue

## Timestamps

- **Created:** 2024-01-20
- **Modified:** 2026-05-19

## APIs

### IBM MQ REST API

REST API for managing and monitoring IBM MQ queue managers, queues, topics, and channels.

- **Human URL:** [https://www.ibm.com/docs/en/ibm-mq/latest?topic=api-rest-overview](https://www.ibm.com/docs/en/ibm-mq/latest?topic=api-rest-overview)
- **Base URL:** `https://{host}:{port}/ibmmq/rest/v2`

#### Tags

- Admin
- Messaging
- Rest

#### Properties

- [Documentation](https://www.ibm.com/docs/en/ibm-mq/latest?topic=api-rest)
- [openapi](https://www.ibm.com/docs/en/SSFKSJ_9.3.0/com.ibm.mq.dev.doc/rest_api_swagger.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/ibm-mq-admin-rest-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/ibm-mq-admin-rest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ibm-mq-admin-rest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### IBM MQ Messaging REST API

REST API for sending and receiving messages via HTTP.

- **Human URL:** [https://www.ibm.com/docs/en/ibm-mq/latest?topic=api-messaging-rest](https://www.ibm.com/docs/en/ibm-mq/latest?topic=api-messaging-rest)
- **Base URL:** `https://{host}:{port}/ibmmq/rest/v2/messaging`

#### Tags

- Consumer
- Messaging
- Producer
- Rest

#### Properties

- [Documentation](https://www.ibm.com/docs/en/ibm-mq/latest?topic=api-messaging-rest)
- [openapi](https://www.ibm.com/docs/en/SSFKSJ_9.3.0/com.ibm.mq.dev.doc/messaging_rest_api_swagger.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/ibm-mq-messaging-rest-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/ibm-mq-messaging-rest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ibm-mq-messaging-rest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### IBM MQ JMS API

Java Message Service API for IBM MQ.

- **Human URL:** [https://www.ibm.com/docs/en/ibm-mq/latest?topic=api-jms](https://www.ibm.com/docs/en/ibm-mq/latest?topic=api-jms)

#### Tags

- Java
- Jms
- Messaging

#### Properties

- [Documentation](https://www.ibm.com/docs/en/ibm-mq/latest?topic=mq-developing-jms-applications)
- [sdk](https://mvnrepository.com/artifact/com.ibm.mq/com.ibm.mq.allclient)
- [AsyncAPI](asyncapi/ibm-mq-messaging-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Postman Collection](collections/ibm-mq-admin-rest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ibm-mq-admin-rest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/ibm-mq-messaging-rest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ibm-mq-messaging-rest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### IBM MQ Native API

Native procedural API for IBM MQ (MQI).

- **Human URL:** [https://www.ibm.com/docs/en/ibm-mq/latest?topic=reference-mqi](https://www.ibm.com/docs/en/ibm-mq/latest?topic=reference-mqi)

#### Tags

- Mqi
- Native
- Procedural

#### Properties

- [Documentation](https://www.ibm.com/docs/en/ibm-mq/latest?topic=programming-mqi)
- [Postman Collection](collections/ibm-mq-admin-rest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ibm-mq-admin-rest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/ibm-mq-messaging-rest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ibm-mq-messaging-rest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/ibm-messaging)
- [getting-started](https://www.ibm.com/docs/en/ibm-mq/latest?topic=mq-getting-started)
- [tutorials](https://developer.ibm.com/tutorials/?s=mq)
- [downloads](https://www.ibm.com/support/pages/downloading-ibm-mq)
- [pricing](https://www.ibm.com/products/mq/pricing)
- [support](https://www.ibm.com/mysupport)
- [blog](https://community.ibm.com/community/user/integration/communities/community-home?CommunityKey=183ec850-4947-49c8-9a2e-8e7c7fc46c64)
- [JSON-LD](json-ld/ibm-mq-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON Schema](json-schema/ibm-mq-queue-manager-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/ibm-mq-queue-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Rules](rules/ibm-mq-rules.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
