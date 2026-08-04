# Forethought (forethought)

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

Forethought is a San Francisco-based generative AI customer-support platform. Its multi-agent product suite — Solve (omnichannel resolution), Triage (ticket classification and routing), Discover (knowledge-gap detection and article generation), Assist (agentic copilot for human agents), and Agent QA (automated quality scoring) — is powered by SupportGPT, Forethought's fine-tuned generative AI engine. The platform supports chat, email, voice, Slack, mobile, and a Headless API channel, and integrates with Zendesk, Salesforce, Intercom, Front, Gorgias, Genesys, Five9, LiveChat, and knowledge sources including Notion, Document360, and Stonly. Forethought exposes two public REST APIs on the Enterprise plan: the Solve API (https://app.forethought.ai/solve/api/v1) for starting and continuing AI conversations and inspecting workspace context variables, and the Triage API (https://api.forethought.ai/api/predict) for classifying tickets against customer-trained models. Public iOS and Android SDKs (Forethought- Technologies/solve-ios, solve-android) embed Solve into mobile apps. The Forethought engineering team also maintains AutoChain, an open-source lightweight framework for building and testing LLM agents. Forethought is now part of Zendesk.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/forethought/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/forethought/refs/heads/main/apis.yml)

## Scope

- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- AI
- Artificial Intelligence
- Customer Support
- Customer Service
- Generative AI
- SupportGPT
- Conversational AI
- Ticket Triage
- Agentic AI
- Voice AI
- Helpdesk
- Multi-Agent

## Timestamps

- **Created:** 2026-05-24
- **Modified:** 2026-05-24

## APIs

### Forethought Solve API

Headless REST API for the Solve omnichannel AI agent. Start a conversation with a free-form customer query, continue the conversation with additional turns or context-variable updates, and inspect the workspace's defined context variables. Bearer-token authenticated against app.forethought.ai/solve/api/v1.

- **Human URL:** [https://support.forethought.ai/hc/en-us/articles/31636750750227-Solve-API-Developer-Reference](https://support.forethought.ai/hc/en-us/articles/31636750750227-Solve-API-Developer-Reference)

#### Tags

- AI
- Customer Support
- Solve
- Conversations
- Headless

#### Properties

- [Documentation](https://support.forethought.ai/hc/en-us/articles/31636750750227-Solve-API-Developer-Reference)
- [OpenAPI](openapi/forethought-solve-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/forethought-solve-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/forethought-solve-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/forethought-conversation-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/forethought-context-variable-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/forethought-conversation-structure.json)
- [JSON-LD](json-ld/forethought-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Example](examples/solve-start-conversation-example.json)
- [Example](examples/solve-continue-conversation-example.json)
- [Example](examples/solve-metadata-example.json)

### Forethought Triage API

REST API for the Triage agent. POST a ticket subject (text_a) and body (text_b) plus the model_name issued by Forethought, and receive ranked predictions with confidence scores. Use to drive ticket routing, auto-populated ticket fields, language detection, sentiment, or other customer-trained labels.

- **Human URL:** [https://support.forethought.ai/hc/en-us/articles/26701042038419-Triage-API-Guide-for-Users](https://support.forethought.ai/hc/en-us/articles/26701042038419-Triage-API-Guide-for-Users)

#### Tags

- AI
- Customer Support
- Triage
- Classification
- Predictions

#### Properties

- [Documentation](https://support.forethought.ai/hc/en-us/articles/26701042038419-Triage-API-Guide-for-Users)
- [OpenAPI](openapi/forethought-triage-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/forethought-triage-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/forethought-triage-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/forethought-triage-prediction-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/forethought-triage-prediction-structure.json)
- [JSON-LD](json-ld/forethought-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Example](examples/triage-predict-example.json)

## Common Properties

- [Website](https://forethought.ai)
- [Portal](https://forethought.ai/platform)
- [Documentation](https://support.forethought.ai/hc/en-us)
- [Documentation](https://support.forethought.ai/hc/en-us/articles/31636750750227-Solve-API-Developer-Reference)
- [Documentation](https://support.forethought.ai/hc/en-us/articles/26701042038419-Triage-API-Guide-for-Users)
- [Pricing](https://forethought.ai/pricing)
- [Plans](plans/forethought-plans-pricing.yml)
- [Rate Limits](rate-limits/forethought-rate-limits.yml)
- [Fin Ops](finops/forethought-finops.yml)
- [Blog](https://forethought.ai/resource-center)
- [Blog](https://engineering.forethought.ai/blog/)
- [Careers](https://forethought.ai/careers)
- [Contact](https://forethought.ai/contact-us)
- [LinkedIn](https://www.linkedin.com/company/forethought-ai)
- [Twitter](https://twitter.com/forethought_ai)
- [GitHub Organization](https://github.com/Forethought-Technologies)
- [SDK](https://github.com/Forethought-Technologies/solve-ios)
- [SDK](https://github.com/Forethought-Technologies/solve-android)
- [Tool](https://github.com/Forethought-Technologies/AutoChain)
- [Documentation](https://autochain.forethought.ai)
- [Integrations](https://forethought.ai/platform)
- [Channels](undefined)
- [Customers](undefined)
- [Features](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
