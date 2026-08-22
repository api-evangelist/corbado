# Corbado (corbado)

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

Corbado is a passkey-first authentication platform that helps companies add WebAuthn passkeys to their products. The Corbado Backend API manages users, login identifiers, sessions, passkeys/credentials, and connect tokens, while passkey intelligence and analytics surface readiness, adoption, and per-user debugging for passwordless rollouts.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/corbado/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/corbado/refs/heads/main/apis.yml)

## Tags

- Authentication
- Passkeys
- WebAuthn
- Passwordless
- CIAM
- Identity

## Timestamps

- **Created:** 2026-06-20
- **Modified:** 2026-06-20

## APIs

### Corbado Users API

Create, list, retrieve, update, and delete end users, plus manage their social logins and credentials, in the Corbado Backend API.

- **Human URL:** [https://docs.corbado.com/api-reference/backend-api](https://docs.corbado.com/api-reference/backend-api)
- **Base URL:** `https://backendapi.corbado.io/v2`

#### Tags

- Users
- Identity
- CIAM

#### Properties

- [Documentation](https://docs.corbado.com/api-reference/backend-api)
- [API Reference](https://docs.corbado.com/api-reference/backend-api/users)
- [OpenAPI](openapi/corbado-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/corbado.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/corbado.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Corbado Identifiers API

Manage login identifiers (email, phone, username) attached to a user, including create, update, delete, and list operations across the project.

- **Human URL:** [https://docs.corbado.com/api-reference/backend-api](https://docs.corbado.com/api-reference/backend-api)
- **Base URL:** `https://backendapi.corbado.io/v2`

#### Tags

- Identifiers
- Email
- Phone
- Username

#### Properties

- [Documentation](https://docs.corbado.com/api-reference/backend-api/identifiers)
- [API Reference](https://docs.corbado.com/api-reference/backend-api/identifiers)
- [OpenAPI](openapi/corbado-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/corbado.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/corbado.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Corbado Sessions API

List active authentication sessions and revoke individual sessions to terminate a user's authenticated state server-side.

- **Human URL:** [https://docs.corbado.com/api-reference/backend-api](https://docs.corbado.com/api-reference/backend-api)
- **Base URL:** `https://backendapi.corbado.io/v2`

#### Tags

- Sessions
- JWT
- Authentication

#### Properties

- [Documentation](https://docs.corbado.com/api-reference/backend-api/sessions)
- [API Reference](https://docs.corbado.com/api-reference/backend-api/sessions)
- [OpenAPI](openapi/corbado-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/corbado.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/corbado.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Corbado Passkeys API

WebAuthn passkey ceremonies - append (registration) and login start/finish, conditional UI mediation, signed-data verification - plus listing and deleting a user's passkey credentials.

- **Human URL:** [https://docs.corbado.com/api-reference/backend-api](https://docs.corbado.com/api-reference/backend-api)
- **Base URL:** `https://backendapi.corbado.io/v2`

#### Tags

- Passkeys
- WebAuthn
- Credentials

#### Properties

- [Documentation](https://docs.corbado.com/api-reference/backend-api/passkeys)
- [API Reference](https://docs.corbado.com/api-reference/backend-api/passkeys)
- [OpenAPI](openapi/corbado-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/corbado.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/corbado.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Corbado Connect Tokens API

Create, list, update, and delete short-lived Connect tokens that authorize Corbado Connect frontend passkey management flows on behalf of a known user.

- **Human URL:** [https://docs.corbado.com/api-reference/backend-api](https://docs.corbado.com/api-reference/backend-api)
- **Base URL:** `https://backendapi.corbado.io/v2`

#### Tags

- Connect Tokens
- Auth Tokens
- Corbado Connect

#### Properties

- [Documentation](https://docs.corbado.com/api-reference/backend-api/connect-tokens)
- [API Reference](https://docs.corbado.com/api-reference/backend-api/connect-tokens)
- [OpenAPI](openapi/corbado-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/corbado.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/corbado.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Corbado Projects API

Project-level configuration and data exports, including CNAME configuration and downloadable project exports for users and passkey events.

- **Human URL:** [https://docs.corbado.com/api-reference/backend-api](https://docs.corbado.com/api-reference/backend-api)
- **Base URL:** `https://backendapi.corbado.io/v2`

#### Tags

- Projects
- Configuration
- Exports

#### Properties

- [Documentation](https://docs.corbado.com/api-reference/backend-api)
- [API Reference](https://docs.corbado.com/api-reference/backend-api)
- [OpenAPI](openapi/corbado-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/corbado.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/corbado.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/corbado)
- [LinkedIn](https://www.linkedin.com/company/corbado)
- [Website](https://www.corbado.com)
- [Documentation](https://docs.corbado.com)
- [Plans](plans/corbado-plans-pricing.yml)
- [Rate Limits](rate-limits/corbado-rate-limits.yml)
- [Fin Ops](finops/corbado-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
