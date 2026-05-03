# ZenML (zenml)

ZenML is an open-source MLOps and LLMOps framework that unifies machine learning and generative AI workflows through a single orchestration, versioning, and governance layer. It provides a Python SDK, CLI, REST API, and server for managing pipelines, stacks, artifacts, models, and deployments across any infrastructure backend, with 60+ integrations spanning orchestrators, ML frameworks, GenAI tools, cloud storage, and experiment tracking platforms.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/zenml/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- AI, Machine Learning, MLOps, LLMOps, Pipelines, Open Source, Python

## Timestamps

- **Created:** 2025-02-08
- **Modified:** 2026-05-03

## APIs

### ZenML OSS REST API

The ZenML open-source REST API exposes endpoints for managing ML pipelines, stacks, components, artifacts, models, deployments, runs, schedules, secrets, users, and projects in a self-hosted ZenML server. It is consumed by the Python SDK and CLI and can be called directly for automation and integration with CI/CD systems and MLOps workflows.

**Human URL:** [https://docs.zenml.io/api-reference/oss-api](https://docs.zenml.io/api-reference/oss-api)

#### Tags

- MLOps, Pipelines, Open Source

#### Properties

- [Documentation](https://docs.zenml.io/api-reference/oss-api)
- [APIReference](https://docs.zenml.io/api-reference/oss-api)
- [OpenAPI](openapi/zenml-openapi.yml)
- [GettingStarted](https://docs.zenml.io/getting-started/installation)
- [Authentication](https://docs.zenml.io/getting-started/deploying-zenml)
- [SDK](https://docs.zenml.io/sdk-reference)
- [GitHubRepository](https://github.com/zenml-io/zenml)
- [JSONSchema (Pipeline)](json-schema/zenml-pipeline-schema.json)
- [JSONSchema (PipelineRun)](json-schema/zenml-pipeline-run-schema.json)
- [JSONSchema (Stack)](json-schema/zenml-stack-schema.json)
- [JSONSchema (Model)](json-schema/zenml-model-schema.json)
- [JSONSchema (Artifact)](json-schema/zenml-artifact-schema.json)
- [Example: List Pipelines](examples/zenml-list-pipelines-example.json)
- [Example: Get Pipeline Run](examples/zenml-get-pipeline-run-example.json)
- [Example: Create Stack](examples/zenml-create-stack-example.json)

### ZenML Pro REST API

The ZenML Pro REST API extends the OSS API with managed control-plane features for teams, including organization and tenant management, role-based access control, audit logs, and enterprise governance.

**Human URL:** [https://docs.zenml.io/api-reference/pro-api](https://docs.zenml.io/api-reference/pro-api)

#### Tags

- MLOps, Enterprise, Governance

#### Properties

- [Documentation](https://docs.zenml.io/api-reference/pro-api)
- [APIReference](https://docs.zenml.io/api-reference/pro-api)
- [Authentication](https://docs.zenml.io/pro/core-concepts/access-control)

## Common Properties

- [Portal](https://www.zenml.io/)
- [Documentation](https://docs.zenml.io/)
- [GettingStarted](https://docs.zenml.io/getting-started/installation)
- [ChangeLog](https://docs.zenml.io/changelog/server-sdk)
- [GitHubRepository](https://github.com/zenml-io/zenml)
- [GitHubOrganization](https://github.com/zenml-io)
- [Pricing](https://www.zenml.io/pro)
- [Integrations](https://www.zenml.io/integrations)
- [Blog](https://www.zenml.io/blog)
- [StatusPage](https://status.zenml.io/)
- [Resources (Careers)](https://www.zenml.io/careers)
- [TermsOfService](https://www.zenml.io/terms-of-service)
- [PrivacyPolicy](https://www.zenml.io/privacy-policy)
- [SDK (PyPI)](https://pypi.org/project/zenml/)
- [SDK (Python Reference)](https://docs.zenml.io/sdk-reference)
- [ReleaseNotes](https://github.com/zenml-io/zenml/releases)
- [JSON-LD Context](json-ld/zenml-context.jsonld)
- [Vocabulary](vocabulary/zenml-vocabulary.yml)
- [Spectral Rules](rules/zenml-rules.yml)
- [Capability: Pipeline Lifecycle](capabilities/pipeline-lifecycle.yaml)
- [Capability: Model Promotion](capabilities/model-promotion.yaml)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
