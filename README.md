# DocuPanda (docupanda)

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
