# Delinea (delinea)

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

Delinea is a privileged access management (PAM) platform providing REST APIs for Secret Server, DevOps Secrets Vault, Privilege Manager, and Cloud Suite. It enables organizations to manage, rotate, and audit privileged credentials, sessions, and access policies across on-premises and cloud infrastructure.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/delinea/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/delinea/refs/heads/main/apis.yml)

## Tags

- Privileged Access Management
- PAM
- Secrets Management
- Identity Security
- DevOps
- Cybersecurity

## Timestamps

- **Created:** 2026-06-13
- **Modified:** 2026-06-13

## APIs

### Secret Server REST API

REST API for Delinea Secret Server enabling programmatic management of privileged credentials, secrets, folders, permissions, and session recording. Supports Bearer token, OAuth 2.0, and Windows Integrated Authentication.

- **Human URL:** [https://docs.delinea.com/online-help/secret-server/api-scripting/rest-api/index.htm](https://docs.delinea.com/online-help/secret-server/api-scripting/rest-api/index.htm)
- **Base URL:** `https://your-secret-server-instance/api/v1`

#### Tags

- Secrets
- Credentials
- Privileged Access
- REST

#### Properties

- [Documentation](https://docs.delinea.com/online-help/secret-server/api-scripting/rest-api/index.htm)
- [API Reference](https://docs.delinea.com/online-help/secret-server/api-scripting/rest-api/rest-api-reference-download/index.htm)
- [Authentication](https://docs.delinea.com/online-help/platform-api/secret-server.htm)
- [Examples](https://docs.delinea.com/online-help/secret-server/api-scripting/rest-api/examples/index.htm)
- [Developer Resources](https://docs.delinea.com/online-help/secret-server/api-scripting/developer-resources/index.htm)

### DevOps Secrets Vault API

REST API for Delinea DevOps Secrets Vault (DSV), a cloud-native secrets management service for DevOps pipelines. Provides endpoints for secrets CRUD, token management, role-based access control, encryption as a service, PKI, and SIEM integration.

- **Human URL:** [https://docs.delinea.com/online-help/devops-secrets-vault/start.htm](https://docs.delinea.com/online-help/devops-secrets-vault/start.htm)
- **Base URL:** `https://secretsvaultcloud.com/v1`

#### Tags

- DevOps
- Secrets Management
- Cloud
- CI/CD

#### Properties

- [Documentation](https://docs.delinea.com/online-help/devops-secrets-vault/start.htm)
- [API Reference](https://dsv.secretsvaultcloud.com/api)
- [S D Ks](https://docs.delinea.com/online-help/devops-secrets-vault/developer-resources/sdk.htm)
- [Python S D K](https://github.com/DelineaXPM/python-dsv-sdk)
- [Go S D K](https://github.com/DelineaXPM/dsv-sdk-go)
- [Java S D K](https://github.com/DelineaXPM/dsv-sdk-java)

### Delinea Platform API

Platform-level REST API for Delinea's unified cloud platform enabling OAuth 2.0 authentication, role and group management, service account operations, and integration with Secret Server through the platform layer.

- **Human URL:** [https://docs.delinea.com/online-help/delinea-platform/api/index.htm](https://docs.delinea.com/online-help/delinea-platform/api/index.htm)
- **Base URL:** `https://your-tenant.delinea.app/api`

#### Tags

- Platform
- Identity
- OAuth
- Access Control

#### Properties

- [Documentation](https://docs.delinea.com/online-help/delinea-platform/api/index.htm)
- [API Reference](https://docs.delinea.com/online-help/platform-api/secret-server.htm)

## Common Properties

- [Website](https://delinea.com/)
- [Documentation](https://docs.delinea.com/online-help/library/start.htm)
- [Git Hub Org](https://github.com/DelineaXPM)
- [LinkedIn](https://www.linkedin.com/company/delinea/)
- [Blog](https://delinea.com/blog)
- [Pricing](https://delinea.com/products/delinea-platform-bundles)
- [Status Page](https://status.delinea.com/)
- [X (Twitter)](https://x.com/DelineaInc)
- [Plans](plans/delinea-plans-pricing.yml)
- [Rate Limits](rate-limits/delinea-rate-limits.yml)
- [Fin Ops](finops/delinea-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
