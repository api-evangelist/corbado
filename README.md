# Corbado (corbado)

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
