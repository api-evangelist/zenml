# ZenML (zenml)

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

ZenML is an open-source MLOps and LLMOps framework that unifies machine learning and generative AI workflows through a single orchestration, versioning, and governance layer. It provides a Python SDK, CLI, REST API, and server for managing pipelines, stacks, artifacts, models, and deployments across any infrastructure backend, with 60+ integrations spanning orchestrators, ML frameworks, GenAI tools, cloud storage, and experiment tracking platforms.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/zenml/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/zenml/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- AI
- Machine Learning
- MLOps
- LLMOps
- Pipelines
- Open Source
- Python

## Timestamps

- **Created:** 2025-02-08
- **Modified:** 2026-05-19

## APIs

### ZenML OSS REST API

The ZenML open-source REST API exposes endpoints for managing ML pipelines, stacks, components, artifacts, models, deployments, runs, schedules, secrets, users, and projects in a self-hosted ZenML server. It is consumed by the Python SDK and CLI and can be called directly for automation and integration with CI/CD systems and MLOps workflows.

- **Human URL:** [https://docs.zenml.io/api-reference/oss-api](https://docs.zenml.io/api-reference/oss-api)

#### Tags

- MLOps
- Pipelines
- Open Source

#### Properties

- [Documentation](https://docs.zenml.io/api-reference/oss-api)
- [API Reference](https://docs.zenml.io/api-reference/oss-api)
- [OpenAPI](openapi/zenml-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/zenml.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/zenml.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Getting Started](https://docs.zenml.io/getting-started/installation)
- [Authentication](https://docs.zenml.io/getting-started/deploying-zenml)
- [SDK](https://docs.zenml.io/sdk-reference)
- [GitHub Repository](https://github.com/zenml-io/zenml)
- [JSON Schema](json-schema/zenml-pipeline-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/zenml-pipeline-run-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/zenml-stack-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/zenml-model-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/zenml-artifact-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Code Examples](examples/zenml-list-pipelines-example.json)
- [Code Examples](examples/zenml-get-pipeline-run-example.json)
- [Code Examples](examples/zenml-create-stack-example.json)

### ZenML Pro REST API

The ZenML Pro REST API extends the OSS API with managed control-plane features for teams, including organization and tenant management, role-based access control, audit logs, and enterprise governance.

- **Human URL:** [https://docs.zenml.io/api-reference/pro-api](https://docs.zenml.io/api-reference/pro-api)

#### Tags

- MLOps
- Enterprise
- Governance

#### Properties

- [Documentation](https://docs.zenml.io/api-reference/pro-api)
- [API Reference](https://docs.zenml.io/api-reference/pro-api)
- [Authentication](https://docs.zenml.io/pro/core-concepts/access-control)
- [Postman Collection](collections/zenml.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/zenml.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Arazzo Workflows](arazzo/) — [Arazzo Specification](https://spec.openapis.org/arazzo/latest.html)
- [LinkedIn](https://www.linkedin.com/company/zenml)
- [Portal](https://www.zenml.io/)
- [Documentation](https://docs.zenml.io/)
- [Getting Started](https://docs.zenml.io/getting-started/installation)
- [Changelog](https://docs.zenml.io/changelog/server-sdk)
- [GitHub Repository](https://github.com/zenml-io/zenml)
- [GitHub Organization](https://github.com/zenml-io)
- [Pricing](https://www.zenml.io/pro)
- [Integrations](https://www.zenml.io/integrations)
- [Blog](https://www.zenml.io/blog)
- [Status Page](https://status.zenml.io/)
- [Resources](https://www.zenml.io/careers)
- [Terms of Service](https://www.zenml.io/terms-of-service)
- [Privacy Policy](https://www.zenml.io/privacy-policy)
- [SDK](https://pypi.org/project/zenml/)
- [SDK](https://docs.zenml.io/sdk-reference)
- [Release Notes](https://github.com/zenml-io/zenml/releases)
- [JSON-LD](json-ld/zenml-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Resources](vocabulary/zenml-vocabulary.yml)
- [Resources](rules/zenml-rules.yml)
- [Resources](capabilities/pipeline-lifecycle.yaml)
- [Resources](capabilities/model-promotion.yaml)
- [M C P Server](https://github.com/zenml-io/mcp-zenml)
- [Agent Skill](https://www.zenml.io/blog/introducing-zenml-agent-skills-let-ai-upgrade-your-mlops-setup-in-minutes)
- [L L Ms Txt](https://docs.zenml.io/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
