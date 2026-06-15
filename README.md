# Zesty (zesty)

Zesty.io is a composable, data-driven, headless CMS platform that provides REST APIs for authentication, account management, instance content management, and media file management. All resources are identified by ZUIDs (Zesty Universal Identifiers). The platform supports WebEngine for traditional CMS, headless API architecture, GraphQL, and JamStack implementations. Built on Google Cloud Platform with Fastly edge caching.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/zesty/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/zesty/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- CMS
- Composable
- Content Management
- GraphQL
- Headless CMS
- Media

## Timestamps

- **Created:** 2025-02-17
- **Modified:** 2026-05-19

## APIs

### Zesty Auth API

The Zesty.io Auth API is used to authenticate users with the platform. It returns a session token that grants access to the Instances API, Accounts API, and Media API. User authentication is done by providing an email and password combination, which issues a short-lived 30-minute session token. Also supports Microsoft SSO, Okta SSO, and Azure SSO.

- **Human URL:** [https://docs.zesty.io/docs/auth-api](https://docs.zesty.io/docs/auth-api)

#### Tags

- Authentication
- Sessions
- Tokens

#### Properties

- [Documentation](https://docs.zesty.io/docs/auth-api)
- [OpenAPI](openapi/zesty-auth-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/zesty-auth-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/zesty-auth-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Zesty Accounts API

The Zesty.io Accounts API is used to manage users, roles, instances, teams, tokens, ecosystems, webhooks, and apps. It provides administrative control over the organizational structure of a Zesty.io account.

- **Human URL:** [https://docs.zesty.io/docs/accounts](https://docs.zesty.io/docs/accounts)

#### Tags

- Accounts
- Instances
- Roles
- Teams
- Users

#### Properties

- [Documentation](https://docs.zesty.io/docs/accounts)
- [OpenAPI](openapi/zesty-accounts-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/zesty-accounts-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/zesty-accounts-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/instance.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/user.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/role.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/team.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/token.json) — [JSON Schema](https://json-schema.org/specification)

### Zesty Instances API

The Zesty.io Instances API is a REST API that allows CRUD operations on Zesty.io instances. It provides access to content models, content items, fields, views, stylesheets, scripts, settings, head tags, navigation, audits, and publishing operations. Each instance is identified by a unique ZUID.

- **Human URL:** [https://docs.zesty.io/docs/instances-api](https://docs.zesty.io/docs/instances-api)

#### Tags

- CMS
- Content Items
- Content Models
- Publishing
- Views

#### Properties

- [Documentation](https://docs.zesty.io/docs/instances-api)
- [OpenAPI](openapi/zesty-instances-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/zesty-instances-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/zesty-instances-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/content-model.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/content-item.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/field.json) — [JSON Schema](https://json-schema.org/specification)

### Zesty Media API

The Zesty.io Media API is a collection of services for managing media files. It consists of four services: Media Manager, Media Storage, Media Modify, and Media Resolver. It handles bins, groups (folders), file uploads, and CDN URL resolution.

- **Human URL:** [https://docs.zesty.io/docs/media](https://docs.zesty.io/docs/media)

#### Tags

- CDN
- Files
- Images
- Media
- Storage

#### Properties

- [Documentation](https://docs.zesty.io/docs/media)
- [OpenAPI](openapi/zesty-media-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/zesty-media-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/zesty-media-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/media-bin.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/media-group.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/media-file.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/zesty-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/zesty-io)
- [Documentation](https://www.zesty.io/docs/)
- [Documentation](https://docs.zesty.io/)
- [Blog](https://www.zesty.io/mindshare/)
- [Support](https://www.zesty.io/contact/)
- [Git Hub](https://github.com/zesty-io)
- [S D Ks](https://github.com/zesty-io/node-sdk)
- [S D Ks](https://github.com/zesty-io/fetch-wrapper)
- [Integrations](https://www.zesty.io/integrations/)
- [L L Ms Txt](https://docs.zesty.io/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
