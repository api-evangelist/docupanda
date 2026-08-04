# DocuPanda (docupanda)

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

DocuPanda — now also branded **DocuPipe** and operated by Hoss Inc. — is an AI-powered document
intelligence API that turns unstructured documents (invoices, leases, medical records, insurance
claims, contracts, bills of lading, receipts, and more) into reliable, schema-conformant JSON.
The platform combines an OCR + parsing pipeline with custom extraction schemas, an agentic
standardization engine, classification, workflows, visual source-highlight review, and webhooks.
Over one billion pages processed, SOC 2 Type 2 and ISO 27001 certified, HIPAA BAA available, and
deployable in cloud, VPC, or on-premises.

**URL:** [apis.yml](https://raw.githubusercontent.com/api-evangelist/docupanda/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags

AI, Artificial Intelligence, Document Extraction, Document Intelligence, IDP, OCR, Document AI

## Timestamps

- **Created:** 2026-05-25
- **Modified:** 2026-05-25

## APIs

DocuPanda exposes a single REST surface at `https://app.docupipe.ai`. For profiling purposes the
operations are grouped into ten logical APIs:

### DocuPanda Documents API
Submit, retrieve, list, search, split, merge, bulk-download, and delete documents. Parses files
into searchable PDFs and structured page-level text, tables, and bounding boxes. Handles
handwriting, checkboxes, tables, and 60+ languages.

- [Documentation](https://docs.docupipe.ai/reference/getting-started-with-docupipe)
- [Getting Started](https://docs.docupipe.ai/docs/getting-started)
- [API Reference (llms.txt index)](https://docs.docupipe.ai/llms.txt)

### DocuPanda Schemas API
Create, edit, copy, delete, and list extraction schemas. Includes AI auto-generation of a schema
from sample documents and per-document schema proposals.

- [Documentation](https://docs.docupipe.ai/reference/getting-started-with-docupipe)

### DocuPanda Standardizations API
Run the agentic V3 standardization engine (or legacy V2) against documents to produce
schema-compliant JSON. Retrieve as JSON, plaintext, or XML; bulk-download as Excel or merged Excel;
query in natural language; and match standardizations against candidate lists.

- [Documentation](https://docs.docupipe.ai/reference/getting-started-with-docupipe)

### DocuPanda Classifications API
Classify batches of documents into a workspace-defined taxonomy. Add, edit, delete, list, and copy
classes across workspaces; route documents to the right downstream schema or workflow.

- [Documentation](https://docs.docupipe.ai/reference/getting-started-with-docupipe)

### DocuPanda Analysis API
Run free-form LLM analysis prompts against a single document or a batch and retrieve the result by
id. Suited to one-off Q&A, summaries, or red-flag checks that do not need a fixed schema.

- [Documentation](https://docs.docupipe.ai/reference/getting-started-with-docupipe)

### DocuPanda Reviews API
Generate visual extraction reviews that highlight where each standardized field was sourced in the
original document. Shareable via presigned URL. Underpins human-in-the-loop QA on production
extractions.

- [Documentation](https://docs.docupipe.ai/reference/getting-started-with-docupipe)

### DocuPanda Workflows API
Define on-submit-document workflows that chain classification, schema selection, standardization,
and review automatically when a new document is uploaded.

- [Documentation](https://docs.docupipe.ai/reference/getting-started-with-docupipe)

### DocuPanda Jobs API
Inspect every job DocuPanda runs on your behalf with the credit cost it consumed. Pulls a summary
count with credit breakdown for FinOps reporting.

- [Documentation](https://docs.docupipe.ai/reference/getting-started-with-docupipe)

### DocuPanda Webhooks API
Register and deregister webhook endpoints to receive event-driven callbacks when documents finish
processing, classifications complete, or standardizations are ready. A portal-link endpoint hands
users a managed subscription portal.

- [Documentation](https://docs.docupipe.ai/reference/getting-started-with-docupipe)

### DocuPanda Account API
Fetch the current account profile including remaining credits, plan tier, and workspace context.

- [Documentation](https://docs.docupipe.ai/reference/getting-started-with-docupipe)

## Common Properties

- [Portal — DocuPipe](https://www.docupipe.ai/)
- [Portal — DocuPanda (legacy)](https://www.docupanda.io)
- [Documentation](https://docs.docupipe.ai/)
- [API Reference](https://docs.docupipe.ai/reference/getting-started-with-docupipe)
- [llms.txt API index](https://docs.docupipe.ai/llms.txt)
- [Getting Started](https://docs.docupipe.ai/docs/getting-started)
- [Authentication](https://docs.docupipe.ai/reference/authentication)
- [Console / SignUp / Login](https://app.docupipe.ai/)
- [Status Page](https://www.docupipe.ai/status)
- [Blog](https://www.docupipe.ai/blog)
- [Security](https://www.docupipe.ai/security)
- [Trust Center](https://docupipe.com/security)
- [Pricing](https://www.docupipe.ai/pricing)
- [GitHub — DocuPanda](https://github.com/DocuPanda)
- [SDK — Python](https://github.com/DocuPanda/docupanda-python-api)
- [Tool — DocuPanda Desktop](https://github.com/DocuPanda/docupanda-desktop)

## Pricing

| Tier | Price (mo) | Credits | Overage | Notes |
|---|---|---|---|---|
| Starter | Free | 100 + 300 sign-up bonus | — | Full API access, no card |
| Business | $99 | 2,500 | $0.08/credit | HIPAA BAA available |
| Premium | $499 | 20,000 | $0.05/credit | Unlimited seats, prod + dev envs |
| Enterprise | Call | Custom | Negotiated | On-prem, dedicated SE, SLAs |

Most common workflow (parse + extract) costs 3 credits per page. All paid plans get 20% off when
billed annually.

## Integrations

- **Make** — native DocuPanda app with actions and triggers
- **Workato** — DocuPanda Document Understanding connector
- **n8n** — DocuPipe for n8n
- **Microsoft Power Automate** — official connector
- **Boost.space** — DocuPanda integration

## Use Cases

- **Finance** — invoices, bank statements, loan applications, purchase orders
- **Healthcare** — medical records and insurance claims (HIPAA BAA)
- **Logistics** — bills of lading, shipping documents, customs paperwork
- **Real Estate** — lease and rental agreement terms
- **Legal** — contract clause extraction
- **Global Operations** — 60+ language support

## Security & Compliance

- SOC 2 Type 2 certified
- ISO 27001 certified
- HIPAA compliant (BAA available on Business+ plans)
- GDPR compliant
- TLS in transit, encryption at rest
- Segregated workspaces, audit logs, disaster recovery
- Cloud, VPC, and on-premises deployment options

## Maintainers

**FN:** Kin Lane

**Email:** info@apievangelist.com
