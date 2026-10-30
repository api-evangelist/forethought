# Forethought

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
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

**Areas:** Artificial Intelligence · Customer Service · Generative AI · SupportGPT · Conversational AI · Ticket Triage · AI Agents · Voice AI · Help Desk · Multi-Agent

## Forethought on APIs.io

Everything profiled for Forethought is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/forethought/](https://apis.io/providers/forethought/)** — or go straight to one of the APIs or properties below.

### APIs (3)

- [Forethought Conversations API](https://apis.io/apis/forethought/forethought-conversations-api/) — Start and continue Solve conversations.
- [Forethought Metadata API](https://apis.io/apis/forethought/forethought-metadata-api/) — Inspect workspace-level Solve configuration.
- [Forethought Predictions API](https://apis.io/apis/forethought/forethought-predictions-api/) — Predict labels for customer-support tickets.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Forethought Agentic Access](https://apis.io/agentic-access/forethought/forethought-agentic-access/)

#### JSON Schema (3)

The data models the API reads and writes.

- [Forethought Solve Context Variable](https://apis.io/schemas/forethought/forethought-context-variable/)
- [Forethought Solve Conversation](https://apis.io/schemas/forethought/forethought-conversation/)
- [Forethought Triage Prediction](https://apis.io/schemas/forethought/forethought-triage-prediction/)

#### JSON Structure (2)

Data models expressed in JSON Structure.

- [Forethought Conversation Structure](https://apis.io/json-structure/forethought/forethought-conversation-structure/)
- [Forethought Triage Prediction Structure](https://apis.io/json-structure/forethought/forethought-triage-prediction-structure/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Forethought Context](https://apis.io/jsonld/forethought/forethought-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [Forethought Vocabulary](https://apis.io/vocabularies/forethought/forethought-vocabulary/)

#### Examples (4)

Example requests and responses.

- [Solve Continue Conversation Example](https://apis.io/examples/forethought/solve-continue-conversation-example/)
- [Solve Metadata Example](https://apis.io/examples/forethought/solve-metadata-example/)
- [Solve Start Conversation Example](https://apis.io/examples/forethought/solve-start-conversation-example/)
- [Triage Predict Example](https://apis.io/examples/forethought/triage-predict-example/)

#### Collections (5)

Postman and Open Collection request collections.

- [Forethought Solve Conversations API](https://apis.io/collections/forethought/open-forethought-conversations-api/)
- [Forethought Solve Conversations Metadata API](https://apis.io/collections/forethought/open-forethought-metadata-api/)
- [Forethought Solve Conversations Predictions API](https://apis.io/collections/forethought/open-forethought-predictions-api/)
- [Forethought Solve API](https://apis.io/collections/forethought/open-forethought-solve-api/)
- [Forethought Triage API](https://apis.io/collections/forethought/open-forethought-triage-api/)

#### Governance rules (2)

Spectral rulesets for the provider's contracts.

- [Forethought — jsonschema rules](https://apis.io/rules/forethought/forethought-jsonschema-spectral-rules/)
- [Forethought API Rules](https://apis.io/rules/forethought/forethought-rules/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Forethought Authentication](https://apis.io/security/forethought/forethought-authentication/)
- [Forethought Domain Security](https://apis.io/security/forethought/forethought-domain-security/)
- [Forethought Trust Center](https://apis.io/security/forethought/forethought-trust-center/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Forethought Plans Pricing](https://apis.io/plans/forethought/forethought-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Forethought Rate Limits](https://apis.io/rate-limits/forethought/forethought-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Forethought Finops](https://apis.io/finops/forethought/forethought-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://forethought.ai)
- [Documentation](https://support.forethought.ai/hc/en-us)
- [Pricing](https://forethought.ai/pricing)
- [Blog](https://forethought.ai/resource-center)
- [GitHub](https://github.com/Forethought-Technologies)

## API Evangelist rating

**Kin Score 38.3** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 57.1 |
| Contract quality | 64.3 |
| Contract governance | 13.6 |
| Operational transparency | 2.6 |
| Developer ergonomics | 40.5 |
| Access clarity | 34.2 |

**Agent readiness 19.2** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | documented (partial credit) |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 20.0** — AI & Biometrics

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/forethought/](https://apis.io/providers/forethought/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Forethought: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/forethought/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
