# Zesty (zesty)
Zesty.io is a composable, data-driven, headless CMS platform that provides REST APIs for authentication, account management, instance content management, and media file management. All resources are identified by ZUIDs (Zesty Universal Identifiers).

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/zesty/refs/heads/main/apis.yml)

## Scope

- **Type:** Index 
- **Position:** Consuming 
- **Access:** 3rd-Party 

## Tags:

 - CMS, Content Management, Headless CMS, Media, Composable

## Timestamps

- **Created:** 2025-02-17 
- **Modified:** 2026-03-16 

## APIs

### Zesty Auth API
The Zesty.io Auth API is used to authenticate users with the platform. It returns a session token that grants access to the Instances API, Accounts API, and Media API. User authentication is done by providing an email and password combination, which issues a short-lived 30-minute session token.

**Human URL:** [https://docs.zesty.io/docs/auth-api](https://docs.zesty.io/docs/auth-api)


#### Tags:

 - Authentication, Sessions, Tokens

#### Properties

- [Documentation](https://docs.zesty.io/docs/auth-api)
- [OpenAPI](openapi/zesty-auth-api-openapi.yml)

### Zesty Accounts API
The Zesty.io Accounts API is used to manage users, roles, instances, teams, tokens, ecosystems, webhooks, and apps. It provides administrative control over the organizational structure of a Zesty.io account.

**Human URL:** [https://docs.zesty.io/docs/accounts](https://docs.zesty.io/docs/accounts)


#### Tags:

 - Accounts, Users, Roles, Teams, Instances

#### Properties

- [Documentation](https://docs.zesty.io/docs/accounts)
- [OpenAPI](openapi/zesty-accounts-api-openapi.yml)
- [JSONSchema](json-schema/instance.json)
- [JSONSchema](json-schema/user.json)
- [JSONSchema](json-schema/role.json)
- [JSONSchema](json-schema/team.json)
- [JSONSchema](json-schema/token.json)

### Zesty Instances API
The Zesty.io Instances API is a REST API that allows CRUD operations on Zesty.io instances. It provides access to content models, content items, fields, views, stylesheets, scripts, settings, head tags, navigation, audits, and publishing operations. Each instance is identified by a unique ZUID.

**Human URL:** [https://docs.zesty.io/docs/instances-api](https://docs.zesty.io/docs/instances-api)


#### Tags:

 - CMS, Content Models, Content Items, Views, Publishing

#### Properties

- [Documentation](https://docs.zesty.io/docs/instances-api)
- [OpenAPI](openapi/zesty-instances-api-openapi.yml)
- [JSONSchema](json-schema/content-model.json)
- [JSONSchema](json-schema/content-item.json)
- [JSONSchema](json-schema/field.json)

### Zesty Media API
The Zesty.io Media API is a collection of services for managing media files. It consists of four services: Media Manager, Media Storage, Media Modify, and Media Resolver. It handles bins, groups (folders), file uploads, and CDN URL resolution.

**Human URL:** [https://docs.zesty.io/docs/media](https://docs.zesty.io/docs/media)


#### Tags:

 - Media, Files, Images, CDN, Storage

#### Properties

- [Documentation](https://docs.zesty.io/docs/media)
- [OpenAPI](openapi/zesty-media-api-openapi.yml)
- [JSONSchema](json-schema/media-bin.json)
- [JSONSchema](json-schema/media-group.json)
- [JSONSchema](json-schema/media-file.json)
- [JSONLD](json-ld/zesty-context.jsonld)

## Common Properties

- [Documentation](https://www.zesty.io/docs/)
- [Blog](https://www.zesty.io/mindshare/)
- [Support](https://www.zesty.io/contact/)
- [GitHub](https://github.com/zesty-io)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
