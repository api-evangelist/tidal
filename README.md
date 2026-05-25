# TIDAL (tidal)
TIDAL is a high-fidelity music streaming service owned by Block (Square's parent, acquired 2021) offering HiRes Lossless FLAC audio up to 192 kHz / 24-bit and Dolby Atmos Music across a 100M+ track catalog. TIDAL's developer platform exposes a unified JSON:API web API at `openapi.tidal.com/v2` covering catalog metadata, personalized recommendations, playlists, user collections, playback manifests, search, social features, creator commerce, and artist claims. Playback bytes are restricted to the official TIDAL Player SDK for Web, iOS, and Android. All APIs use OAuth 2.0 — Authorization Code with PKCE for user-context flows and Client Credentials for server-to-server use.

**URL:** [Visit APIs.yml](https://raw.githubusercontent.com/api-evangelist/tidal/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags

- Music, Streaming, Hi-Fi, HiRes Lossless, Audio, Block, Square

## Timestamps

- **Created:** 2026-05-25
- **Modified:** 2026-05-25

## Catalog Footprint

| Surface | Count |
|---|---|
| APIs profiled | 10 |
| OpenAPI paths | 241 |
| OpenAPI operations | 325 |
| Naftiko capabilities | 36 |
| Resource types | 64 |

## Authentication

| Flow | Use case | Token URL |
|---|---|---|
| Authorization Code with PKCE | End-user flows (collections, playlists, recommendations, playback) | `https://auth.tidal.com/v1/oauth2/token` |
| Client Credentials | Server-to-server catalog and metadata access | `https://auth.tidal.com/v1/oauth2/token` |

**Scopes:** `collection.read`, `collection.write`, `playlists.read`, `playlists.write`, `playback`, `recommendations.read`, `search.read`, `search.write`, `user.read`, `entitlements.read`.

## APIs

### TIDAL Catalog API
Browse TIDAL's high-fidelity music catalog. Resource-oriented JSON:API surface for albums, artists, tracks, videos, genres, lyrics, credits, artworks, providers, and biographies, with cursor pagination, sparse fieldsets, sort, filter, and JSON:API `include` relationship traversal.

**Human URL:** [https://developer.tidal.com/documentation/api-sdk/api-sdk-overview](https://developer.tidal.com/documentation/api-sdk/api-sdk-overview)

- [OpenAPI](openapi/tidal-catalog-api-openapi.yml)
- [JSON Schema — Album](json-schema/tidal-album-schema.json)
- [JSON Schema — Artist](json-schema/tidal-artist-schema.json)
- [JSON Schema — Track](json-schema/tidal-track-schema.json)
- [JSON-LD Context](json-ld/tidal-context.jsonld)
- [Naftiko Capability — Albums](capabilities/catalog-albums.yaml)
- [Naftiko Capability — Artists](capabilities/catalog-artists.yaml)
- [Naftiko Capability — Tracks](capabilities/catalog-tracks.yaml)
- [Naftiko Capability — Videos](capabilities/catalog-videos.yaml)

### TIDAL Search API
Search the TIDAL catalog with personalized search results, type-ahead suggestions, and per-user search history. Supports filtering by entity type and respects user locale and country.

- [OpenAPI](openapi/tidal-search-api-openapi.yml)
- [Naftiko Capability — Search Results](capabilities/search-search-results.yaml)
- [Naftiko Capability — Suggestions](capabilities/search-suggestions.yaml)
- [Naftiko Capability — Search History](capabilities/search-history.yaml)

### TIDAL Playlists API
Create, read, update, delete, and reorder TIDAL playlists. Manage playlist items, cover art, owners, and editorial vs. user-created classifications. Requires `playlists.read` and `playlists.write` scopes.

- [OpenAPI](openapi/tidal-playlists-api-openapi.yml)
- [JSON Schema — Playlist](json-schema/tidal-playlist-schema.json)
- [Naftiko Capability — Playlists](capabilities/playlists-playlists.yaml)

### TIDAL Users API
User account management surface. Read user profile and country, manage accepted terms, list registered installations and clients, submit user reports, and request data exports for GDPR/CCPA compliance.

- [OpenAPI](openapi/tidal-users-api-openapi.yml)
- [JSON Schema — User](json-schema/tidal-user-schema.json)
- [Naftiko Capability — Users](capabilities/users-users.yaml)
- [Naftiko Capability — Terms](capabilities/users-terms.yaml)
- [Naftiko Capability — Clients](capabilities/users-clients.yaml)

### TIDAL User Collections API
TIDAL's My Collection — the user's saved albums, artists, tracks, videos, playlists, folders, and save-for-later items. Requires `collection.read` and `collection.write` scopes.

- [OpenAPI](openapi/tidal-user-collections-api-openapi.yml)
- [Naftiko Capability — Albums](capabilities/user-collections-albums.yaml)
- [Naftiko Capability — Artists](capabilities/user-collections-artists.yaml)
- [Naftiko Capability — Tracks](capabilities/user-collections-tracks.yaml)
- [Naftiko Capability — Playlists](capabilities/user-collections-playlists.yaml)
- [Naftiko Capability — Videos](capabilities/user-collections-videos.yaml)
- [Naftiko Capability — Folders and Save for Later](capabilities/user-collections-folders.yaml)

### TIDAL Recommendations API
Personalized recommendations powered by TIDAL's algorithmic mixes. Daily Mix, Discovery Mix, New Release Mix, and Offline Mix, plus dynamic editorial pages and modules curated for the user. Requires `recommendations.read` scope.

**Human URL:** [Discover, Explore, Play: TIDAL's Recommendation APIs Unraveled](https://developer.tidal.com/blog/discover-explore-play-tidals-recommendation-apis-unraveled)

- [OpenAPI](openapi/tidal-recommendations-api-openapi.yml)
- [Naftiko Capability — User Recommendations](capabilities/recommendations-user-recommendations.yaml)
- [Naftiko Capability — Daily Mixes](capabilities/recommendations-daily-mixes.yaml)
- [Naftiko Capability — Discovery and Offline Mixes](capabilities/recommendations-discovery-mixes.yaml)
- [Naftiko Capability — New Release Mixes](capabilities/recommendations-new-release-mixes.yaml)
- [Naftiko Capability — Dynamic Pages](capabilities/recommendations-dynamic-pages.yaml)

### TIDAL Playback API
Playback prerequisites — play queues, encrypted track manifests (HLS/DASH with HI_RES_LOSSLESS, LOSSLESS, HIGH, LOW quality tiers), video manifests, offline tasks, downloads, and usage rules. Per TIDAL policy, audio bytes flow exclusively through the official TIDAL Player SDK; the Playback API only issues signed manifests. Requires `playback` scope.

- [OpenAPI](openapi/tidal-playback-api-openapi.yml)
- [Naftiko Capability — Play Queues](capabilities/playback-play-queues.yaml)
- [Naftiko Capability — Track Manifests](capabilities/playback-track-manifests.yaml)
- [Naftiko Capability — Video Manifests](capabilities/playback-video-manifests.yaml)
- [Naftiko Capability — Downloads](capabilities/playback-downloads.yaml)

### TIDAL Social API
TIDAL's social surface — shares, saved shares, DSP sharing links (deep links to TIDAL content from other DSPs), comments, reactions, and artist appreciations across albums, artists, tracks, videos, and playlists.

- [OpenAPI](openapi/tidal-social-api-openapi.yml)
- [Naftiko Capability — Shares](capabilities/social-shares.yaml)
- [Naftiko Capability — Comments](capabilities/social-comments.yaml)
- [Naftiko Capability — Reactions](capabilities/social-reactions.yaml)
- [Naftiko Capability — Appreciations](capabilities/social-appreciations.yaml)

### TIDAL Commerce API
TIDAL's marketplace and creator-commerce surface — direct fan purchases of music, artist price configurations, Stripe and Square connections (reflecting TIDAL's Block / Square parentage), and Stripe dashboard links for connected artists.

- [OpenAPI](openapi/tidal-commerce-api-openapi.yml)
- [Naftiko Capability — Purchases](capabilities/commerce-purchases.yaml)
- [Naftiko Capability — Price Configurations](capabilities/commerce-price-configurations.yaml)
- [Naftiko Capability — Stripe and Square Connections](capabilities/commerce-stripe-connections.yaml)

### TIDAL Claims API
Artist verification and content rights claims for the TIDAL Artist platform. Artists claim profiles, content owners assert ownership of catalog items, and TIDAL operations review manual claim workflows.

- [OpenAPI](openapi/tidal-claims-api-openapi.yml)
- [Naftiko Capability — Artist Claims](capabilities/claims-artist-claims.yaml)
- [Naftiko Capability — Content Claims](capabilities/claims-content-claims.yaml)
- [Naftiko Capability — Manual Artist Claims](capabilities/claims-manual-artist-claims.yaml)

## SDKs and Tools

| Repo | Language | Purpose |
|---|---|---|
| [tidal-sdk](https://github.com/tidal-music/tidal-sdk) | meta | TIDAL SDK overview and Auth / Player / EventProducer module docs |
| [tidal-sdk-web](https://github.com/tidal-music/tidal-sdk-web) | TypeScript | Web SDK including Auth, Player, Catalog API client |
| [tidal-sdk-ios](https://github.com/tidal-music/tidal-sdk-ios) | Swift | iOS SDK |
| [tidal-sdk-android](https://github.com/tidal-music/tidal-sdk-android) | Kotlin | Android SDK |
| [embed-player](https://github.com/tidal-music/embed-player) | JavaScript | TIDAL Embed Player for third-party sites |
| [tidal-algorithmic-mixes](https://github.com/tidal-music/tidal-algorithmic-mixes) | Python | Open-source algorithmic mix generation reference |
| [networktime](https://github.com/tidal-music/networktime) | Kotlin Multiplatform | SNTP client for accurate playback timing |
| [openapi-generator](https://github.com/tidal-music/openapi-generator) | Java | TIDAL fork of OpenAPI Generator |
| [eslint-config-tidal](https://github.com/tidal-music/eslint-config-tidal) | JavaScript | Shared ESLint config |

## Plans, Rate Limits, and FinOps

- [Plans and Pricing](plans/tidal-plans-pricing.yml)
- [Rate Limits](rate-limits/tidal-rate-limits.yml)
- [FinOps Definition](finops/tidal-finops.yml)

## Standards and Schemas

- [JSON-LD Context](json-ld/tidal-context.jsonld) — maps TIDAL entities to schema.org Music* hierarchy
- [Vocabulary](vocabulary/tidal-vocabulary.yml) — domain terms, concepts, and relationships
- [Spectral Rules](rules/tidal-rules.yml) — TIDAL JSON:API conventions

## Examples

- [Get Album](examples/tidal-get-album-example.json)
- [Search](examples/tidal-search-example.json)
- [Create Playlist](examples/tidal-create-playlist-example.json)
- [Track Manifest](examples/tidal-track-manifest-example.json)

## Notes

- TIDAL is a **Block, Inc.** company (Square's parent acquired TIDAL in 2021). The Commerce API surfaces both `stripeConnections` and `squareConnections` for artist payouts.
- The Playback API only returns **signed, opaque manifests**; the official TIDAL Player SDK (Web / iOS / Android) is the only sanctioned consumer. Decoding manifests or extracting media bytes violates TIDAL's Developer Terms.
- The entire TIDAL v2 surface is **JSON:API** compliant — clients should send `Accept: application/vnd.api+json` and expect cursor pagination via `page[cursor]`, sparse fieldsets via `fields[type]`, and compound documents via `include`.
- The canonical OpenAPI spec is published at [https://tidal-music.github.io/tidal-api-reference/tidal-api-oas.json](https://tidal-music.github.io/tidal-api-reference/tidal-api-oas.json).
