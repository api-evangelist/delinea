---
name: delinea-create-and-get-sdk-client-account
description: Create a new SDK client account and retrieve its details.
api: openapi/delinea-sdkclientaccounts-api-openapi.yml
operations:
- SdkClientAccountsService_CreateClientAccount
- SdkClientAccountsService_Get
generated: '2026-10-03'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/delinea-sdkclientaccounts-api-openapi.yml ; every operationId checked against the contract
---

# delinea-create-and-get-sdk-client-account

Create a new SDK client account and retrieve its details.

## Steps

1. 1. Call `SdkClientAccountsService_CreateClientAccount` with the required request body fields and include the `Authorization: Bearer <token>` header.
2. 2. Call `SdkClientAccountsService_Get` with the path parameter `id` returned from the create call and include the `Authorization: Bearer <token>` header.

## Rules

- Authentication: Provide a Bearer token in the `Authorization` header for all requests.
- Idempotency: Not applicable for these operations.
- Pagination: Not applicable for these operations.
