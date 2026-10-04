---
name: delinea-create-and-retrieve-workflow-template
description: Create a new workflow template and then retrieve its details.
api: openapi/delinea-workflow-templates-api-openapi.yml
operations:
- WorkflowTemplatesService_CreateWorkflowTemplate
- WorkflowTemplatesService_GetTemplate
generated: '2026-10-03'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/delinea-workflow-templates-api-openapi.yml ; every operationId checked against the contract
---

# delinea-create-and-retrieve-workflow-template

Create a new workflow template and then retrieve its details.

## Steps

1. 1. Call `WorkflowTemplatesService_CreateWorkflowTemplate` with the request body fields required for creating a template.
2. 2. Call `WorkflowTemplatesService_GetTemplate` with the path parameter `id` returned from the create call.

## Rules

- Auth: Include a Bearer token in the `Authorization` header (scheme: BearerToken).
- Idempotency: Not applicable for these operations.
