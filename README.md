# QuickPay

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

QuickPay is a Venezuelan payment platform that enables businesses to collect payments via WhatsApp, QR codes, links, and recurring billing. It supports various sectors such as restaurants, gyms, clinics, and e‑commerce, offering a portal for merchants to manage transactions, view webhooks, and integrate through its API. QuickPay provides test credentials for sandbox integration and aims to simplify digital payments across Venezuelan banks.

**Areas:** Payments · FinTech · Venezuela · WhatsApp · QR

## QuickPay on APIs.io

Everything profiled for QuickPay is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/pagaconquickpay-com/](https://apis.io/providers/pagaconquickpay-com/)** — or go straight to one of the APIs or properties below.

### APIs (8)

- [QuickPay Cobros API](https://apis.io/apis/pagaconquickpay-com/pagaconquickpay-com-cobros-api/) — Debitar al pagador (débito inmediato con OTP)
- [QuickPay Configuración API](https://apis.io/apis/pagaconquickpay-com/pagaconquickpay-com-configuraci-n-api/) — Configuración del comercio (lectura). La edición de la config money-critical es solo-admin.
- [QuickPay Consultas API](https://apis.io/apis/pagaconquickpay-com/pagaconquickpay-com-consultas-api/) — Estado de una operación y catálogos
- [QuickPay Links de cobro API](https://apis.io/apis/pagaconquickpay-com/pagaconquickpay-com-links-de-cobro-api/) — Enlaces de pago alojados (hosted checkout); el link se paga exactamente una vez
- [QuickPay Onboarding API](https://apis.io/apis/pagaconquickpay-com/pagaconquickpay-com-onboarding-api/) — Alta del comercio (self-signup público) y activación (KYC + aprobación, operada por el administrador de QuickPay).
- [QuickPay Pagos API](https://apis.io/apis/pagaconquickpay-com/pagaconquickpay-com-pagos-api/) — Enviar dinero a un beneficiario
- [QuickPay Webhooks API](https://apis.io/apis/pagaconquickpay-com/pagaconquickpay-com-webhooks-api/) — Suscripciones a eventos del comercio (entrega firmada HMAC-SHA256). Aislado por tenant: cada comercio gestiona solo los suyos.
- [QuickPay WhatsApp Flows (Kit T2) API](https://apis.io/apis/pagaconquickpay-com/pagaconquickpay-com-whatsapp-flows-kit-t2-api/) — Endpoint data-exchange: tu propio WABA/Flow delega el paso de pago a QuickPay.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Pagaconquickpay Com Webhooks](https://apis.io/asyncapis/pagaconquickpay-com/pagaconquickpay-com-webhooks/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [QuickPay Agentic Access](https://apis.io/agentic-access/pagaconquickpay-com/pagaconquickpay-com-agentic-access/)

#### JSON Schema (6)

The data models the API reads and writes.

- [CobrarRequest](https://apis.io/schemas/pagaconquickpay-com/pagaconquickpay-com-cobrar-request/)
- [Link](https://apis.io/schemas/pagaconquickpay-com/pagaconquickpay-com-link/)
- [LinkCobroRequest](https://apis.io/schemas/pagaconquickpay-com/pagaconquickpay-com-link-cobro-request/)
- [PagarRequest](https://apis.io/schemas/pagaconquickpay-com/pagaconquickpay-com-pagar-request/)
- [Resultado](https://apis.io/schemas/pagaconquickpay-com/pagaconquickpay-com-resultado/)
- [TokenRequest](https://apis.io/schemas/pagaconquickpay-com/pagaconquickpay-com-token-request/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Pagaconquickpay Com Context](https://apis.io/jsonld/pagaconquickpay-com/pagaconquickpay-com-context/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [QuickPay API Rules](https://apis.io/rules/pagaconquickpay-com/pagaconquickpay-com-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [QuickPay Authentication](https://apis.io/security/pagaconquickpay-com/pagaconquickpay-com-authentication/)
- [QuickPay Domain Security](https://apis.io/security/pagaconquickpay-com/pagaconquickpay-com-domain-security/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://pagaconquickpay.com/)
- [Documentation](https://docs.pagaconquickpay.com/)
- [Getting started](https://docs.pagaconquickpay.com/developers/quickstart)
- [API reference](https://docs.pagaconquickpay.com/docs)

## API Evangelist rating

**Kin Score 45.2** — developing · rubric 0.27.0 · scored 2026-11-20

| Facet | Score |
|---|---|
| Discoverability | 65.0 |
| Contract quality | 66.9 |
| Contract governance | 79.1 |
| Operational transparency | 23.7 |
| Developer ergonomics | 50.0 |
| Access clarity | 0.0 |

**Agent readiness 56.6** — agent-ready (gated down from agent-native)

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | unknown |
| Reversibility Documented | — |
| MCP Server | documented (partial credit) |
| Auth Clarity | served (partial credit) |
| Idempotency | verified |
| Error Semantics | derived (partial credit) |
| OpenAPI Examples | partial |
| Rate Limit Signal | — |
| Event Surface Described | unknown |
| Agent Skills | — |
| Well Known Catalog | yes |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | served (partial credit) |
| Protected Resource Metadata | verified |
| Dynamic Client Registration | yes |
| Agentic Commerce | — |
| Pagination Ratio | — |
| Operation Distinctiveness | distinct |
| MCP Tool Quality | na |

**Regulatory alignment 15.2** — Payments

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/pagaconquickpay-com/](https://apis.io/providers/pagaconquickpay-com/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for QuickPay: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/pagaconquickpay-com/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
