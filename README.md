# Forethought (forethought)

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
