# TIDAL (tidal)

TIDAL is a high-fidelity music streaming service owned by Block (Square's parent, acquired 2021) offering HiRes Lossless FLAC audio up to 192 kHz / 24-bit and Dolby Atmos Music across a 100M+ track catalog. TIDAL's developer platform exposes a unified JSON:API web API at openapi.tidal.com/v2 covering catalog metadata, personalized recommendations, playlists, user collections, playback manifests, search, social features, creator commerce, and artist claims. Playback bytes are restricted to the official TIDAL Player SDK for Web, iOS, and Android. All APIs use OAuth 2.0 — Authorization Code with PKCE for user-context flows and Client Credentials for server-to-server use. TIDAL also operates the TIDAL Embed Player and the open-source tidal-music GitHub organization.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/tidal/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/tidal/refs/heads/main/apis.yml)

## Scope

- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- Music
- Streaming
- Hi-Fi
- HiRes Lossless
- Audio
- Block
- Square

## Timestamps

- **Created:** 2026-05-25
- **Modified:** 2026-05-25

## APIs

### TIDAL Catalog API

Browse TIDAL's high-fidelity music catalog. Resource-oriented JSON:API surface for albums, artists, tracks, videos, genres, lyrics, credits, artworks, providers, and biographies, with cursor pagination, sparse fieldsets, sort, filter, and JSON:API `include` relationship traversal.

- **Human URL:** [https://developer.tidal.com/documentation/api-sdk/api-sdk-overview](https://developer.tidal.com/documentation/api-sdk/api-sdk-overview)

#### Tags

- Music
- Catalog
- Albums
- Artists
- Tracks
- Videos

#### Properties

- [Documentation](https://developer.tidal.com/documentation/api-sdk/api-sdk-overview)
- [Documentation](https://tidal-music.github.io/tidal-api-reference/)
- [OpenAPI](openapi/tidal-catalog-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/tidal-catalog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tidal-catalog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/tidal-album-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/tidal-artist-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/tidal-track-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/tidal-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### TIDAL Search API

Search the TIDAL catalog with personalized search results, type-ahead suggestions, and per-user search history. Supports filtering by entity type and respects user locale and country.

- **Human URL:** [https://developer.tidal.com/documentation/api-sdk/api-sdk-overview](https://developer.tidal.com/documentation/api-sdk/api-sdk-overview)

#### Tags

- Music
- Search
- Suggestions

#### Properties

- [Documentation](https://developer.tidal.com/documentation/api-sdk/api-sdk-overview)
- [OpenAPI](openapi/tidal-search-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/tidal-search-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tidal-search-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### TIDAL Playlists API

Create, read, update, delete, and reorder TIDAL playlists. Manage playlist items, cover art, owners, and editorial vs. user-created classifications. Requires playlists.read and playlists.write scopes.

- **Human URL:** [https://developer.tidal.com/documentation/api-sdk/api-sdk-overview](https://developer.tidal.com/documentation/api-sdk/api-sdk-overview)

#### Tags

- Music
- Playlists

#### Properties

- [Documentation](https://developer.tidal.com/documentation/api-sdk/api-sdk-overview)
- [OpenAPI](openapi/tidal-playlists-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/tidal-playlists-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tidal-playlists-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/tidal-playlist-schema.json) — [JSON Schema](https://json-schema.org/specification)

### TIDAL Users API

User account management surface. Read user profile and country, manage accepted terms, list registered installations and clients, submit user reports, and request data exports for GDPR/CCPA compliance.

- **Human URL:** [https://developer.tidal.com/documentation/api-sdk/api-sdk-overview](https://developer.tidal.com/documentation/api-sdk/api-sdk-overview)

#### Tags

- Users
- Accounts
- Terms

#### Properties

- [Documentation](https://developer.tidal.com/documentation/api-sdk/api-sdk-overview)
- [OpenAPI](openapi/tidal-users-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/tidal-users-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tidal-users-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/tidal-user-schema.json) — [JSON Schema](https://json-schema.org/specification)

### TIDAL User Collections API

TIDAL's My Collection — the user's saved albums, artists, tracks, videos, playlists, folders, and save-for-later items. Add, remove, organize into folders, and traverse the collection via JSON:API relationships. Requires collection.read/write scopes.

- **Human URL:** [https://developer.tidal.com/documentation/api-sdk/api-sdk-overview](https://developer.tidal.com/documentation/api-sdk/api-sdk-overview)

#### Tags

- Users
- Collections
- Library
- My Collection

#### Properties

- [Documentation](https://developer.tidal.com/documentation/api-sdk/api-sdk-overview)
- [OpenAPI](openapi/tidal-user-collections-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/tidal-user-collections-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tidal-user-collections-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### TIDAL Recommendations API

Personalized recommendations powered by TIDAL's algorithmic mixes. Daily Mix, Discovery Mix, New Release Mix, and Offline Mix, plus dynamic editorial pages and modules curated for the user. Requires recommendations.read scope.

- **Human URL:** [https://developer.tidal.com/blog/discover-explore-play-tidals-recommendation-apis-unraveled](https://developer.tidal.com/blog/discover-explore-play-tidals-recommendation-apis-unraveled)

#### Tags

- Music
- Recommendations
- Mixes
- Personalization
- Discovery

#### Properties

- [Documentation](https://developer.tidal.com/blog/discover-explore-play-tidals-recommendation-apis-unraveled)
- [OpenAPI](openapi/tidal-recommendations-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/tidal-recommendations-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tidal-recommendations-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### TIDAL Playback API

Playback prerequisites — play queues, encrypted track manifests (HLS/DASH with HI_RES_LOSSLESS, LOSSLESS, HIGH, LOW quality tiers), video manifests, offline tasks, downloads, and usage rules. Per TIDAL policy, audio bytes flow exclusively through the official TIDAL Player SDK; the Playback API only issues signed manifests. Requires playback scope.

- **Human URL:** [https://developer.tidal.com/documentation/api-sdk/api-sdk-overview](https://developer.tidal.com/documentation/api-sdk/api-sdk-overview)

#### Tags

- Music
- Playback
- Streaming
- Hi-Fi
- HiRes
- Manifests
- Downloads

#### Properties

- [Documentation](https://developer.tidal.com/documentation/api-sdk/api-sdk-overview)
- [Documentation](https://github.com/tidal-music/tidal-sdk)
- [OpenAPI](openapi/tidal-playback-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/tidal-playback-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tidal-playback-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### TIDAL Social API

TIDAL's social surface — shares, saved shares, DSP sharing links (deep links to TIDAL content from other DSPs), comments, reactions, and artist appreciations across albums, artists, tracks, videos, and playlists.

- **Human URL:** [https://developer.tidal.com/documentation/api-sdk/api-sdk-overview](https://developer.tidal.com/documentation/api-sdk/api-sdk-overview)

#### Tags

- Music
- Social
- Sharing
- Comments
- Reactions

#### Properties

- [Documentation](https://developer.tidal.com/documentation/api-sdk/api-sdk-overview)
- [OpenAPI](openapi/tidal-social-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/tidal-social-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tidal-social-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### TIDAL Commerce API

TIDAL's marketplace and creator-commerce surface — direct fan purchases of music, artist price configurations, Stripe and Square connections (reflecting TIDAL's Block / Square parentage), and Stripe dashboard links for connected artists.

- **Human URL:** [https://developer.tidal.com/documentation/api-sdk/api-sdk-overview](https://developer.tidal.com/documentation/api-sdk/api-sdk-overview)

#### Tags

- Music
- Commerce
- Purchases
- Pricing
- Stripe
- Square

#### Properties

- [Documentation](https://developer.tidal.com/documentation/api-sdk/api-sdk-overview)
- [OpenAPI](openapi/tidal-commerce-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/tidal-commerce-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tidal-commerce-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### TIDAL Claims API

Artist verification and content rights claims for the TIDAL Artist platform. Artists claim profiles, content owners assert ownership of catalog items, and TIDAL operations review manual claim workflows.

- **Human URL:** [https://developer.tidal.com/documentation/api-sdk/api-sdk-overview](https://developer.tidal.com/documentation/api-sdk/api-sdk-overview)

#### Tags

- Music
- Claims
- Artists
- Verification
- Rights

#### Properties

- [Documentation](https://developer.tidal.com/documentation/api-sdk/api-sdk-overview)
- [OpenAPI](openapi/tidal-claims-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/tidal-claims-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tidal-claims-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Arazzo Workflows](arazzo/) — [Arazzo Specification](https://spec.openapis.org/arazzo/latest.html)
- [Portal](https://tidal.com)
- [Documentation](https://developer.tidal.com)
- [Documentation](https://developer.tidal.com/documentation)
- [Documentation](https://tidal-music.github.io/tidal-api-reference/)
- [Getting Started](https://developer.tidal.com/documentation/api-sdk/api-sdk-quick-start)
- [Authentication](https://developer.tidal.com/documentation/api-sdk/api-sdk-authorization)
- [Sign Up](https://developer.tidal.com/dashboard)
- [Terms of Service](https://developer.tidal.com/documentation/guidelines/guidelines-developer-terms)
- [Documentation](https://developer.tidal.com/documentation/guidelines-developer-guidelines-2_0)
- [Documentation](https://developer.tidal.com/documentation/guidelines/guidelines-design-guidelines)
- [Documentation](https://developer.tidal.com/documentation/api-sdk/api-sdk-manage-apps)
- [Blog](https://developer.tidal.com/blog)
- [Blog](https://tidal.com/magazine)
- [Privacy Policy](https://tidal.com/privacy)
- [Terms of Service](https://tidal.com/terms)
- [Status Page](https://status.tidal.com)
- [GitHub Organization](https://github.com/tidal-music)
- [SDK](https://github.com/tidal-music/tidal-sdk-web)
- [SDK](https://github.com/tidal-music/tidal-sdk-ios)
- [SDK](https://github.com/tidal-music/tidal-sdk-android)
- [SDK](https://github.com/tidal-music/tidal-sdk)
- [Tool](https://github.com/tidal-music/embed-player)
- [Tool](https://github.com/tidal-music/tidal-algorithmic-mixes)
- [Tool](https://github.com/tidal-music/networktime)
- [Tool](https://github.com/tidal-music/openapi-generator)
- [Tool](https://github.com/tidal-music/eslint-config-tidal)
- [Forum](https://github.com/tidal-music/discussions)
- [Documentation](https://developer.tidal.com/documentation/open-source)
- [Plans](https://tidal.com/pricing)
- [Plans](plans/tidal-plans-pricing.yml)
- [Rate Limits](rate-limits/tidal-rate-limits.yml)
- [Fin Ops](finops/tidal-finops.yml)
- [Features](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** info@apievangelist.com
**URL:** https://apievangelist.com
