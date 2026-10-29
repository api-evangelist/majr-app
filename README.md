# majr-app

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

MAJR provides agent services that expose shared, product‑neutral capabilities such as Dispatch (release‑note generation), AI SEO (search‑engine and AI answer‑engine optimization), and Media Encoding (video, audio, and image processing). These services are offered via a simple MCP‑based HTTP interface with a single bearer‑auth key, enabling developers to integrate powerful media and marketing functions without building them from scratch. The platform is hosted at majr.app and documented across sub‑domains for each service.

**Areas:** Company · AI · Media · SEO · Encoding · Agent Services

## majr-app on APIs.io

Everything profiled for majr-app is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/majr-app/](https://apis.io/providers/majr-app/)** — or go straight to one of the APIs or properties below.

### APIs (10)

- [majr-app Audit API](https://apis.io/apis/majr-app/majr-app-audit-api/) — Fetch one URL (SSRF-guarded) and score its technical SEO + AI-readiness signals.
- [majr-app Discovery API](https://apis.io/apis/majr-app/majr-app-discovery-api/) — Who this service is and where its contracts live.
- [majr-app Drafting API](https://apis.io/apis/majr-app/majr-app-drafting-api/) — The capability: dev log in, release-notes Markdown out.
- [majr-app Encode API](https://apis.io/apis/majr-app/majr-app-encode-api/) — The Encode API from majr-app — 1 operation(s) for encode.
- [majr-app Generation API](https://apis.io/apis/majr-app/majr-app-generation-api/) — Pure artifact generation — JSON in, artifact out, no fetches, no state.
- [majr-app Healthz API](https://apis.io/apis/majr-app/majr-app-healthz-api/) — The Healthz API from majr-app — 1 operation(s) for healthz.
- [majr-app Jobs API](https://apis.io/apis/majr-app/majr-app-jobs-api/) — The Jobs API from majr-app — 1 operation(s) for jobs.
- [majr-app Uploads API](https://apis.io/apis/majr-app/majr-app-uploads-api/) — The Uploads API from majr-app — 1 operation(s) for uploads.
- [majr-app Usage API](https://apis.io/apis/majr-app/majr-app-usage-api/) — Your metered usage (drafts + token counts).
- [majr-app Voice API](https://apis.io/apis/majr-app/majr-app-voice-api/) — Your account's brand-voice floor (composed beneath every draft).

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Majr App Webhooks](https://apis.io/asyncapis/majr-app/majr-app-webhooks/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Majr App Agentic Access](https://apis.io/agentic-access/majr-app/majr-app-agentic-access/)

#### JSON Schema (15)

The data models the API reads and writes.

- [AuditRequest](https://apis.io/schemas/majr-app/majr-app-audit-request/)
- [AuditResponse](https://apis.io/schemas/majr-app/majr-app-audit-response/)
- [DraftRequest](https://apis.io/schemas/majr-app/majr-app-draft-request/)
- [DraftResponse](https://apis.io/schemas/majr-app/majr-app-draft-response/)
- [EncodeRequest](https://apis.io/schemas/majr-app/majr-app-encode-request/)
- [EncodeStatus](https://apis.io/schemas/majr-app/majr-app-encode-status/)
- [HeadRequest](https://apis.io/schemas/majr-app/majr-app-head-request/)
- [JobState](https://apis.io/schemas/majr-app/majr-app-job-state/)
- [LlmsTxtRequest](https://apis.io/schemas/majr-app/majr-app-llms-txt-request/)
- [RobotsRequest](https://apis.io/schemas/majr-app/majr-app-robots-request/)
- [SitemapRequest](https://apis.io/schemas/majr-app/majr-app-sitemap-request/)
- [UploadContract](https://apis.io/schemas/majr-app/majr-app-upload-contract/)
- [UploadRequest](https://apis.io/schemas/majr-app/majr-app-upload-request/)
- [UsageResponse](https://apis.io/schemas/majr-app/majr-app-usage-response/)
- [VoiceResponse](https://apis.io/schemas/majr-app/majr-app-voice-response/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Majr App Context](https://apis.io/jsonld/majr-app/majr-app-context/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [majr-app API Rules](https://apis.io/rules/majr-app/majr-app-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Majr App Authentication](https://apis.io/security/majr-app/majr-app-authentication/)
- [Majr App Domain Security](https://apis.io/security/majr-app/majr-app-domain-security/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://majr.app/)
- [Documentation](https://dispatch.majr.app/docs)
- [Getting started](https://majr.app/quickstart/seo)
- [Sign up](https://majr.app/keys/)
- [Changelog](https://majr.app/whats-new)
- [Terms of service](https://majr.app/terms)
- [Privacy policy](https://majr.app/privacy)

## API Evangelist rating

**Kin Score 54.9** — strong · rubric 0.25.0 · scored 2026-10-29

| Facet | Score |
|---|---|
| Discoverability | 71.4 |
| Contract quality | 63.9 |
| Contract governance | 79.1 |
| Operational transparency | 23.7 |
| Developer ergonomics | 56.4 |
| Access clarity | 34.2 |

**Agent readiness 44.2** — agent-ready (gated down from agent-native)

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | unknown |
| Reversibility Documented | — |
| MCP Server | documented (partial credit) |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | verified |
| OpenAPI Examples | — |
| Rate Limit Signal | verified |
| Event Surface Described | unknown |
| Agent Skills | unknown |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | distinct |

**Regulatory alignment 22.7** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/majr-app/](https://apis.io/providers/majr-app/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for majr-app: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/majr-app/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
