# TIDAL (tidal)

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
