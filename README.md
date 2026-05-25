# Forethought (forethought)

Forethought is a San Francisco-based generative AI customer-support platform. Its multi-agent suite — Solve (omnichannel resolution), Triage (ticket classification), Discover (knowledge-gap detection), Assist (agent copilot), and Agent QA (automated quality scoring) — is powered by SupportGPT, Forethought's fine-tuned generative AI engine. Forethought is now part of Zendesk.

**URL:** [Visit APIs.json](https://raw.githubusercontent.com/api-evangelist/forethought/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags

AI, Artificial Intelligence, Customer Support, Customer Service, Generative AI, SupportGPT, Conversational AI, Ticket Triage, Agentic AI, Voice AI, Helpdesk, Multi-Agent

## Timestamps

- **Created:** 2026-05-24
- **Modified:** 2026-05-24

## APIs

### Forethought Solve API

Headless REST API for the Solve omnichannel AI agent. Start a conversation with a free-form customer query, continue the conversation with additional turns or context-variable updates, and inspect the workspace's defined context variables. Bearer-token authenticated against `app.forethought.ai/solve/api/v1`.

**Human URL:** [Solve API Developer Reference](https://support.forethought.ai/hc/en-us/articles/31636750750227-Solve-API-Developer-Reference)

- [OpenAPI](openapi/forethought-solve-api-openapi.yml)
- [JSON Schema — Conversation](json-schema/forethought-conversation-schema.json)
- [JSON Schema — Context Variable](json-schema/forethought-context-variable-schema.json)
- [JSON Structure — Conversation](json-structure/forethought-conversation-structure.json)
- [JSON-LD context](json-ld/forethought-context.jsonld)
- [Naftiko Capability — Conversations](capabilities/solve-conversations.yaml)
- [Naftiko Capability — Metadata](capabilities/solve-metadata.yaml)
- [Example — Start conversation](examples/solve-start-conversation-example.json)
- [Example — Continue conversation](examples/solve-continue-conversation-example.json)
- [Example — Metadata](examples/solve-metadata-example.json)

### Forethought Triage API

REST API for the Triage agent. POST a ticket subject and body plus a `model_name` issued by Forethought, and receive ranked predictions with confidence scores.

**Human URL:** [Triage API Guide for Users](https://support.forethought.ai/hc/en-us/articles/26701042038419-Triage-API-Guide-for-Users)

- [OpenAPI](openapi/forethought-triage-api-openapi.yml)
- [JSON Schema — Triage Prediction](json-schema/forethought-triage-prediction-schema.json)
- [JSON Structure — Triage Prediction](json-structure/forethought-triage-prediction-structure.json)
- [Naftiko Capability — Predictions](capabilities/triage-predictions.yaml)
- [Example — Predict](examples/triage-predict-example.json)

## Plans, Rate Limits, FinOps

- [Plans](plans/forethought-plans-pricing.yml) — Basic, Professional, Enterprise (Forethought API is Enterprise-only) plus Assist, Agent QA, and Forethought for Slack add-ons. Sales-quoted.
- [Rate Limits](rate-limits/forethought-rate-limits.yml) — Server-side throttling, 429 on overflow. Per-tenant limits coordinated with Forethought Customer Success.
- [FinOps](finops/forethought-finops.yml) — Annual subscription billing, FOCUS-aligned definition.

## Vocabulary and Rules

- [Vocabulary](vocabulary/forethought-vocabulary.yml)
- [Spectral rules](rules/forethought-rules.yml)

## SDKs and Open Source

- [Solve iOS SDK](https://github.com/Forethought-Technologies/solve-ios) (Apache-2.0)
- [Solve Android SDK](https://github.com/Forethought-Technologies/solve-android) (Apache-2.0)
- [AutoChain](https://github.com/Forethought-Technologies/AutoChain) — open-source LLM agent framework (MIT)

## Maintainers

- Kin Lane — kin@apievangelist.com
