---
name: delinea-workflow-step-create-and-retrieve
description: Create a new workflow step in a template and then retrieve it.
api: openapi/delinea-workflowsteptemplates-api-openapi.yml
operations:
- WorkflowStepTemplatesService_CreateStep
- WorkflowStepTemplatesService_GetTemplateStep
generated: '2026-10-03'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/delinea-workflowsteptemplates-api-openapi.yml ; every operationId checked against the contract
---

# delinea-workflow-step-create-and-retrieve

Create a new workflow step in a template and then retrieve it.

## Steps

1. 1. Call `WorkflowStepTemplatesService_CreateStep` with the required path parameter `id` and the request body defining the new step.
2. 2. Call `WorkflowStepTemplatesService_GetTemplateStep` with the path parameters `id` (the template ID) and `stepNum` (the step number returned or assigned after creation) to retrieve the created step.

## Rules

- Auth: Include a Bearer token in the `Authorization` header (scheme: BearerToken).
- Idempotency: Not applicable; the Create operation is not idempotent.
