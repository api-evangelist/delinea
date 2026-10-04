---
name: delinea-event-subscriptions-create
description: Create a new event subscription using the Delinea Event Subscriptions API.
api: openapi/delinea-event-subscriptions-api-openapi.yml
operations:
- EventSubscriptionsService_GetSubscriptionStub
- EventSubscriptionsService_GetSubscriptionEntityTypes
- EventSubscriptionsService_CreateEventSubscription
generated: '2026-10-03'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/delinea-event-subscriptions-api-openapi.yml ; every operationId checked against the contract
---

# delinea-event-subscriptions-create

Create a new event subscription using the Delinea Event Subscriptions API.

## Steps

1. 1. `EventSubscriptionsService_GetSubscriptionStub` – send a GET request to `/v1/event-subscriptions/stub` with the `Authorization: Bearer <token>` header.
2. 2. `EventSubscriptionsService_GetSubscriptionEntityTypes` – send a GET request to `/v1/event-subscriptions/event-types` with the `Authorization: Bearer <token>` header to retrieve available subscription types and actions.
3. 3. `EventSubscriptionsService_CreateEventSubscription` – send a POST request to `/v1/event-subscriptions` with the `Authorization: Bearer <token>` header and a JSON body describing the subscription to create.

## Rules

- Include a Bearer token in the `Authorization` header for all requests.
