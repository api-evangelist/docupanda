# DocuPipe

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

DocuPipe (formerly DocuPanda, operated by Hoss Inc.) is an AI-powered document intelligence API that converts unstructured documents — invoices, leases, medical records, claims, contracts, bills of lading, receipts, and more — into structured JSON. The platform pairs an OCR + parsing pipeline with custom extraction schemas, an agentic standardization engine, classification, workflows, visual review, and webhooks. It publishes DocuBench, an open benchmark for schema-based extraction across 72 documents. DocuPipe lists SOC 2 Type 2 and ISO 27001, offers a HIPAA BAA, and deploys in cloud, VPC, or on-premises.

**Areas:** Artificial Intelligence · Document Extraction · Document Intelligence · Intelligent Document Processing · OCR · Document AI

## DocuPipe on APIs.io

Everything profiled for DocuPipe is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/docupanda/](https://apis.io/providers/docupanda/)** — or go straight to one of the APIs or properties below.

### APIs (21)

- [DocuPipe Documents API](https://apis.io/apis/docupanda/docupanda-documents-api/) — Submit, retrieve, list, search, split, merge, bulk-download, and delete documents. DocuPipe parses files into searchable PDFs and structured page-level…
- [DocuPipe Schemas API](https://apis.io/apis/docupanda/docupanda-schemas-api/) — Create, edit, copy, delete, and list extraction schemas, plus AI auto-generate a schema from sample documents and retrieve schema proposals per document.…
- [DocuPipe Standardizations API](https://apis.io/apis/docupanda/docupanda-standardizations-api/) — Run the agentic V3 standardization engine (or legacy V2) against documents to produce schema-compliant JSON. Retrieve results as JSON, plaintext, or XML;…
- [DocuPipe Classifications API](https://apis.io/apis/docupanda/docupanda-classifications-api/) — Classify batches of documents into a workspace-defined taxonomy. Manage the class taxonomy (add, edit, delete, list, copy classes across workspaces) and…
- [DocuPipe Analysis API](https://apis.io/apis/docupanda/docupanda-analysis-api/) — Run free-form LLM analysis prompts against a single document or a batch and retrieve the resulting analysis by id. Useful for one-off Q&A, summaries, or…
- [DocuPipe Reviews API](https://apis.io/apis/docupanda/docupanda-reviews-api/) — Generate visual extraction reviews that highlight where each standardized field was sourced in the original document. List, update, share via presigned URL,…
- [DocuPipe Workflows API](https://apis.io/apis/docupanda/docupanda-workflows-api/) — Define on-submit-document workflows that chain classification, schema selection, standardization, and review automatically when a new document is uploaded.…
- [DocuPipe Jobs API](https://apis.io/apis/docupanda/docupanda-jobs-api/) — Inspect every job DocuPipe runs on your behalf with the credit cost it consumed. Retrieve a job by id, list jobs, bulk-delete jobs, and pull a summary count…
- [DocuPipe Webhooks API](https://apis.io/apis/docupanda/docupanda-webhooks-api/) — Register and deregister webhook endpoints to receive event-driven callbacks when documents finish processing, classifications complete, or standardizations…
- [DocuPipe Account API](https://apis.io/apis/docupanda/docupanda-account-api/) — Fetch the current account profile including remaining credits, plan tier, and workspace context. Pair with the Jobs API to build internal usage dashboards.
- [DocuPipe Account API](https://apis.io/apis/docupanda/docupanda-account-api/) — The Account API from DocuPipe — 1 operation(s) for account.
- [DocuPipe Analysis API](https://apis.io/apis/docupanda/docupanda-analysis-api/) — The Analysis API from DocuPipe — 4 operation(s) for analysis.
- [DocuPipe Classification API](https://apis.io/apis/docupanda/docupanda-classification-api/) — The Classification API from DocuPipe — 6 operation(s) for classification.
- [DocuPipe Document API](https://apis.io/apis/docupanda/docupanda-document-api/) — The Document API from DocuPipe — 18 operation(s) for document.
- [DocuPipe Job API](https://apis.io/apis/docupanda/docupanda-job-api/) — The Job API from DocuPipe — 4 operation(s) for job.
- [DocuPipe Review API](https://apis.io/apis/docupanda/docupanda-review-api/) — The Review API from DocuPipe — 6 operation(s) for review.
- [DocuPipe Schema API](https://apis.io/apis/docupanda/docupanda-schema-api/) — The Schema API from DocuPipe — 8 operation(s) for schema.
- [DocuPipe Standardization API](https://apis.io/apis/docupanda/docupanda-standardization-api/) — The Standardization API from DocuPipe — 19 operation(s) for standardization.
- [DocuPipe Transformation API](https://apis.io/apis/docupanda/docupanda-transformation-api/) — The Transformation API from DocuPipe — 6 operation(s) for transformation.
- [DocuPipe Webhook API](https://apis.io/apis/docupanda/docupanda-webhook-api/) — The Webhook API from DocuPipe — 5 operation(s) for webhook.
- [DocuPipe Workflow API](https://apis.io/apis/docupanda/docupanda-workflow-api/) — The Workflow API from DocuPipe — 5 operation(s) for workflow.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [docupanda-mcp.yml](https://apis.io/servers/docupanda/docupanda-mcp-yml/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Docupanda Agentic Access](https://apis.io/agentic-access/docupanda/docupanda-agentic-access/)

#### JSON Schema (6)

The data models the API reads and writes.

- [Document](https://apis.io/schemas/docupanda/docupanda-document/)
- [GetAccountResponse](https://apis.io/schemas/docupanda/docupanda-get-account-response/)
- [JobStandardize](https://apis.io/schemas/docupanda/docupanda-job-standardize/)
- [JobTransformationAuthoring](https://apis.io/schemas/docupanda/docupanda-job-transformation-authoring/)
- [Review](https://apis.io/schemas/docupanda/docupanda-review/)
- [StandardizeV2BatchRequest](https://apis.io/schemas/docupanda/docupanda-standardize-v2-batch-request/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Docupanda Context](https://apis.io/jsonld/docupanda/docupanda-context/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [DocuPipe API Rules](https://apis.io/rules/docupanda/docupanda-rules/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Docupanda Authentication](https://apis.io/security/docupanda/docupanda-authentication/)
- [Docupanda Domain Security](https://apis.io/security/docupanda/docupanda-domain-security/)
- [Docupanda Trust Center](https://apis.io/security/docupanda/docupanda-trust-center/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.docupipe.ai/)
- [Documentation](https://docs.docupipe.ai/)
- [Getting started](https://docs.docupipe.ai/docs/getting-started)
- [API reference](https://docs.docupipe.ai/reference/getting-started-with-docupipe)
- [Pricing](https://www.docupipe.ai/pricing)
- [Support](https://help.docupipe.ai/en/)
- [Changelog](https://www.docupipe.ai/changelog)
- [Blog](https://www.docupipe.ai/blog)
- [Security](https://www.docupipe.ai/security)
- [Compliance](https://www.docupipe.ai/security)
- [GitHub](https://github.com/DocuPanda)
- [Status](https://www.docupipe.ai/status)

## API Evangelist rating

**Kin Score 47.9** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 73.2 |
| Contract quality | 64.4 |
| Contract governance | 22.0 |
| Operational transparency | 44.7 |
| Developer ergonomics | 51.2 |
| Access clarity | 28.9 |

**Agent readiness 28.2** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | verified |
| OpenAPI Examples | — |
| Rate Limit Signal | — |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | yes |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | partial |
| Operation Distinctiveness | distinct |

**Regulatory alignment 20.0** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/docupanda/](https://apis.io/providers/docupanda/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for DocuPipe: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/docupanda/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
