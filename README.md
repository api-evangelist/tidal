# TIDAL

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

TIDAL is a high-fidelity music streaming service owned by Block (Square's parent, acquired 2021) offering HiRes Lossless FLAC audio up to 192 kHz / 24-bit and Dolby Atmos Music across a 100M+ track catalog. TIDAL's developer platform exposes a unified JSON:API web API at openapi.tidal.com/v2 covering catalog metadata, personalized recommendations, playlists, user collections, playback manifests, search, social features, creator commerce, and artist claims. Playback bytes are restricted to the official TIDAL Player SDK for Web, iOS, and Android. All APIs use OAuth 2.0 — Authorization Code with PKCE for user-context flows and Client Credentials for server-to-server use. TIDAL also operates the TIDAL Embed Player and the open-source tidal-music GitHub organization.

**Areas:** Music · Streaming · Hi-Fi · HiRes Lossless · Audio · Block · Square

## TIDAL on APIs.io

Everything profiled for TIDAL is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/tidal/](https://apis.io/providers/tidal/)** — or go straight to one of the APIs or properties below.

### APIs (65)

- [TIDAL Playlists API](https://apis.io/apis/tidal/tidal-playlists-api/) — Create, read, update, delete, and reorder TIDAL playlists. Manage playlist items, cover art, owners, and editorial vs. user-created classifications.…
- [TIDAL Users API](https://apis.io/apis/tidal/tidal-users-api/) — User account management surface. Read user profile and country, manage accepted terms, list registered installations and clients, submit user reports, and…
- [TIDAL Accepted Terms API](https://apis.io/apis/tidal/tidal-acceptedterms-api/) — The acceptedTerms API from TIDAL — 3 operation(s) for acceptedterms.
- [TIDAL Albums API](https://apis.io/apis/tidal/tidal-albums-api/) — The albums API from TIDAL — 15 operation(s) for albums.
- [TIDAL Album Statistics API](https://apis.io/apis/tidal/tidal-albumstatistics-api/) — The albumStatistics API from TIDAL — 3 operation(s) for albumstatistics.
- [TIDAL Appreciations API](https://apis.io/apis/tidal/tidal-appreciations-api/) — The appreciations API from TIDAL — 1 operation(s) for appreciations.
- [TIDAL Artist Biographies API](https://apis.io/apis/tidal/tidal-artistbiographies-api/) — The artistBiographies API from TIDAL — 3 operation(s) for artistbiographies.
- [TIDAL Artist Claims API](https://apis.io/apis/tidal/tidal-artistclaims-api/) — The artistClaims API from TIDAL — 5 operation(s) for artistclaims.
- [TIDAL Artist Roles API](https://apis.io/apis/tidal/tidal-artistroles-api/) — The artistRoles API from TIDAL — 2 operation(s) for artistroles.
- [TIDAL Artists API](https://apis.io/apis/tidal/tidal-artists-api/) — The artists API from TIDAL — 14 operation(s) for artists.
- [TIDAL Artworks API](https://apis.io/apis/tidal/tidal-artworks-api/) — The artworks API from TIDAL — 3 operation(s) for artworks.
- [TIDAL Clients API](https://apis.io/apis/tidal/tidal-clients-api/) — The clients API from TIDAL — 3 operation(s) for clients.
- [TIDAL Comments API](https://apis.io/apis/tidal/tidal-comments-api/) — The comments API from TIDAL — 5 operation(s) for comments.
- [TIDAL Content Claims API](https://apis.io/apis/tidal/tidal-contentclaims-api/) — The contentClaims API from TIDAL — 5 operation(s) for contentclaims.
- [TIDAL Credits API](https://apis.io/apis/tidal/tidal-credits-api/) — The credits API from TIDAL — 4 operation(s) for credits.
- [TIDAL Downloads API](https://apis.io/apis/tidal/tidal-downloads-api/) — The downloads API from TIDAL — 3 operation(s) for downloads.
- [TIDAL Dsp Sharing Links API](https://apis.io/apis/tidal/tidal-dspsharinglinks-api/) — The dspSharingLinks API from TIDAL — 2 operation(s) for dspsharinglinks.
- [TIDAL Dynamic Pages API](https://apis.io/apis/tidal/tidal-dynamicpages-api/) — The dynamicPages API from TIDAL — 3 operation(s) for dynamicpages.
- [TIDAL Genres API](https://apis.io/apis/tidal/tidal-genres-api/) — The genres API from TIDAL — 2 operation(s) for genres.
- [TIDAL Installations API](https://apis.io/apis/tidal/tidal-installations-api/) — The installations API from TIDAL — 4 operation(s) for installations.
- [TIDAL Lyrics API](https://apis.io/apis/tidal/tidal-lyrics-api/) — The lyrics API from TIDAL — 4 operation(s) for lyrics.
- [TIDAL Manual Artist Claims API](https://apis.io/apis/tidal/tidal-manualartistclaims-api/) — The manualArtistClaims API from TIDAL — 1 operation(s) for manualartistclaims.
- [TIDAL Offline Tasks API](https://apis.io/apis/tidal/tidal-offlinetasks-api/) — The offlineTasks API from TIDAL — 5 operation(s) for offlinetasks.
- [TIDAL Play Queues API](https://apis.io/apis/tidal/tidal-playqueues-api/) — The playQueues API from TIDAL — 6 operation(s) for playqueues.
- [TIDAL Price Configurations API](https://apis.io/apis/tidal/tidal-priceconfigurations-api/) — The priceConfigurations API from TIDAL — 2 operation(s) for priceconfigurations.
- [TIDAL Provider Owners API](https://apis.io/apis/tidal/tidal-providerowners-api/) — The providerOwners API from TIDAL — 3 operation(s) for providerowners.
- [TIDAL Provider Product Infos API](https://apis.io/apis/tidal/tidal-providerproductinfos-api/) — The providerProductInfos API from TIDAL — 3 operation(s) for providerproductinfos.
- [TIDAL Providers API](https://apis.io/apis/tidal/tidal-providers-api/) — The providers API from TIDAL — 2 operation(s) for providers.
- [TIDAL Purchases API](https://apis.io/apis/tidal/tidal-purchases-api/) — The purchases API from TIDAL — 3 operation(s) for purchases.
- [TIDAL Reactions API](https://apis.io/apis/tidal/tidal-reactions-api/) — The reactions API from TIDAL — 4 operation(s) for reactions.
- [TIDAL Saved Shares API](https://apis.io/apis/tidal/tidal-savedshares-api/) — The savedShares API from TIDAL — 1 operation(s) for savedshares.
- [TIDAL Search History Entries API](https://apis.io/apis/tidal/tidal-searchhistoryentries-api/) — The searchHistoryEntries API from TIDAL — 2 operation(s) for searchhistoryentries.
- [TIDAL Shares API](https://apis.io/apis/tidal/tidal-shares-api/) — The shares API from TIDAL — 4 operation(s) for shares.
- [TIDAL Square Connections API](https://apis.io/apis/tidal/tidal-squareconnections-api/) — The squareConnections API from TIDAL — 2 operation(s) for squareconnections.
- [TIDAL Stripe Connections API](https://apis.io/apis/tidal/tidal-stripeconnections-api/) — The stripeConnections API from TIDAL — 2 operation(s) for stripeconnections.
- [TIDAL Stripe Dashboard Links API](https://apis.io/apis/tidal/tidal-stripedashboardlinks-api/) — The stripeDashboardLinks API from TIDAL — 2 operation(s) for stripedashboardlinks.
- [TIDAL Temporary User Tokens API](https://apis.io/apis/tidal/tidal-temporaryusertokens-api/) — The temporaryUserTokens API from TIDAL — 3 operation(s) for temporaryusertokens.
- [TIDAL Terms API](https://apis.io/apis/tidal/tidal-terms-api/) — The terms API from TIDAL — 2 operation(s) for terms.
- [TIDAL Track Files API](https://apis.io/apis/tidal/tidal-trackfiles-api/) — The trackFiles API from TIDAL — 1 operation(s) for trackfiles.
- [TIDAL Track Manifests API](https://apis.io/apis/tidal/tidal-trackmanifests-api/) — The trackManifests API from TIDAL — 1 operation(s) for trackmanifests.
- [TIDAL Tracks API](https://apis.io/apis/tidal/tidal-tracks-api/) — The tracks API from TIDAL — 20 operation(s) for tracks.
- [TIDAL Tracks Metadata Status API](https://apis.io/apis/tidal/tidal-tracksmetadatastatus-api/) — The tracksMetadataStatus API from TIDAL — 2 operation(s) for tracksmetadatastatus.
- [TIDAL Track Source Files API](https://apis.io/apis/tidal/tidal-tracksourcefiles-api/) — The trackSourceFiles API from TIDAL — 3 operation(s) for tracksourcefiles.
- [TIDAL Track Statistics API](https://apis.io/apis/tidal/tidal-trackstatistics-api/) — The trackStatistics API from TIDAL — 3 operation(s) for trackstatistics.
- [TIDAL Usage Rules API](https://apis.io/apis/tidal/tidal-usagerules-api/) — The usageRules API from TIDAL — 2 operation(s) for usagerules.
- [TIDAL User Collection Albums API](https://apis.io/apis/tidal/tidal-usercollectionalbums-api/) — The userCollectionAlbums API from TIDAL — 3 operation(s) for usercollectionalbums.
- [TIDAL User Collection Artists API](https://apis.io/apis/tidal/tidal-usercollectionartists-api/) — The userCollectionArtists API from TIDAL — 3 operation(s) for usercollectionartists.
- [TIDAL User Collection Folders API](https://apis.io/apis/tidal/tidal-usercollectionfolders-api/) — The userCollectionFolders API from TIDAL — 4 operation(s) for usercollectionfolders.
- [TIDAL User Collection Playlists API](https://apis.io/apis/tidal/tidal-usercollectionplaylists-api/) — The userCollectionPlaylists API from TIDAL — 3 operation(s) for usercollectionplaylists.
- [TIDAL User Collections API](https://apis.io/apis/tidal/tidal-usercollections-api/) — The userCollections API from TIDAL — 7 operation(s) for usercollections.
- [TIDAL User Collection Save For Laters API](https://apis.io/apis/tidal/tidal-usercollectionsaveforlaters-api/) — The userCollectionSaveForLaters API from TIDAL — 3 operation(s) for usercollectionsaveforlaters.
- [TIDAL User Collection Tracks API](https://apis.io/apis/tidal/tidal-usercollectiontracks-api/) — The userCollectionTracks API from TIDAL — 4 operation(s) for usercollectiontracks.
- [TIDAL User Collection Videos API](https://apis.io/apis/tidal/tidal-usercollectionvideos-api/) — The userCollectionVideos API from TIDAL — 3 operation(s) for usercollectionvideos.
- [TIDAL User Daily Mixes API](https://apis.io/apis/tidal/tidal-userdailymixes-api/) — The userDailyMixes API from TIDAL — 2 operation(s) for userdailymixes.
- [TIDAL User Data Export Requests API](https://apis.io/apis/tidal/tidal-userdataexportrequests-api/) — The userDataExportRequests API from TIDAL — 1 operation(s) for userdataexportrequests.
- [TIDAL User Discovery Mixes API](https://apis.io/apis/tidal/tidal-userdiscoverymixes-api/) — The userDiscoveryMixes API from TIDAL — 2 operation(s) for userdiscoverymixes.
- [TIDAL User New Release Mixes API](https://apis.io/apis/tidal/tidal-usernewreleasemixes-api/) — The userNewReleaseMixes API from TIDAL — 2 operation(s) for usernewreleasemixes.
- [TIDAL User Offline Mixes API](https://apis.io/apis/tidal/tidal-userofflinemixes-api/) — The userOfflineMixes API from TIDAL — 2 operation(s) for userofflinemixes.
- [TIDAL Video Manifests API](https://apis.io/apis/tidal/tidal-videomanifests-api/) — The videoManifests API from TIDAL — 1 operation(s) for videomanifests.
- [TIDAL Videos API](https://apis.io/apis/tidal/tidal-videos-api/) — The videos API from TIDAL — 11 operation(s) for videos.
- [TIDAL User Reports API](https://apis.io/apis/tidal/tidal-user-reports-api/) — The User Reports API from TIDAL — 1 operation(s) for user reports.
- [TIDAL Dynamic Modules API](https://apis.io/apis/tidal/tidal-dynamic-modules-api/) — The Dynamic Modules API from TIDAL — 2 operation(s) for dynamic modules.
- [TIDAL Search Results API](https://apis.io/apis/tidal/tidal-search-results-api/) — The Search Results API from TIDAL — 7 operation(s) for search results.
- [TIDAL Search Suggestions API](https://apis.io/apis/tidal/tidal-search-suggestions-api/) — The Search Suggestions API from TIDAL — 3 operation(s) for search suggestions.
- [TIDAL User Recommendations API](https://apis.io/apis/tidal/tidal-user-recommendations-api/) — The User Recommendations API from TIDAL — 5 operation(s) for user recommendations.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Arazzo workflows (9)

Multi-step workflows that chain operations into a business task.

- [TIDAL Album Tracklist Explorer](https://apis.io/arazzos/tidal/tidal-album-tracklist-workflow/)
- [TIDAL Artist Discography Explorer](https://apis.io/arazzos/tidal/tidal-artist-discography-workflow/)
- [TIDAL Browse Collection Tracks](https://apis.io/arazzos/tidal/tidal-browse-collection-tracks-workflow/)
- [TIDAL Create Playlist and Add Tracks](https://apis.io/arazzos/tidal/tidal-create-playlist-and-add-tracks-workflow/)
- [TIDAL Discovery Mix Tracks](https://apis.io/arazzos/tidal/tidal-discovery-mix-tracks-workflow/)
- [TIDAL Search and Save Track to Collection](https://apis.io/arazzos/tidal/tidal-search-and-save-track-to-collection-workflow/)
- [TIDAL Search to Track and Album](https://apis.io/arazzos/tidal/tidal-search-to-track-album-workflow/)
- [TIDAL Track Playback Manifest](https://apis.io/arazzos/tidal/tidal-track-playback-manifest-workflow/)
- [TIDAL Video Explorer](https://apis.io/arazzos/tidal/tidal-video-explorer-workflow/)

#### GraphQL (1)

GraphQL schemas.

- [Moved to /providers/tidal/](https://apis.io/graphqls/tidal/tidal-graphql/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Tidal Agentic Access](https://apis.io/agentic-access/tidal/tidal-agentic-access/)

#### JSON Schema (5)

The data models the API reads and writes.

- [TIDAL Album](https://apis.io/schemas/tidal/tidal-album/)
- [TIDAL Artist](https://apis.io/schemas/tidal/tidal-artist/)
- [TIDAL Playlist](https://apis.io/schemas/tidal/tidal-playlist/)
- [TIDAL Track](https://apis.io/schemas/tidal/tidal-track/)
- [TIDAL User](https://apis.io/schemas/tidal/tidal-user/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Tidal Context](https://apis.io/jsonld/tidal/tidal-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [Tidal Vocabulary](https://apis.io/vocabularies/tidal/tidal-vocabulary/)

#### Examples (4)

Example requests and responses.

- [Tidal Create Playlist Example](https://apis.io/examples/tidal/tidal-create-playlist-example/)
- [Tidal Get Album Example](https://apis.io/examples/tidal/tidal-get-album-example/)
- [Tidal Search Example](https://apis.io/examples/tidal/tidal-search-example/)
- [Tidal Track Manifest Example](https://apis.io/examples/tidal/tidal-track-manifest-example/)

#### Collections (83)

Postman and Open Collection request collections.

- [TIDAL Catalog acceptedTerms API](https://apis.io/collections/tidal/open-tidal-acceptedterms-api/)
- [TIDAL Catalog acceptedTerms albums API](https://apis.io/collections/tidal/open-tidal-albums-api/)
- [TIDAL Catalog acceptedTerms albumStatistics API](https://apis.io/collections/tidal/open-tidal-albumstatistics-api/)
- [TIDAL Catalog acceptedTerms appreciations API](https://apis.io/collections/tidal/open-tidal-appreciations-api/)
- [TIDAL Catalog acceptedTerms artistBiographies API](https://apis.io/collections/tidal/open-tidal-artistbiographies-api/)
- [TIDAL Catalog acceptedTerms artistClaims API](https://apis.io/collections/tidal/open-tidal-artistclaims-api/)
- [TIDAL Catalog acceptedTerms artistRoles API](https://apis.io/collections/tidal/open-tidal-artistroles-api/)
- [TIDAL Catalog acceptedTerms artists API](https://apis.io/collections/tidal/open-tidal-artists-api/)
- [TIDAL Catalog acceptedTerms artworks API](https://apis.io/collections/tidal/open-tidal-artworks-api/)
- [TIDAL Catalog API](https://apis.io/collections/tidal/open-tidal-catalog-api/)
- [TIDAL Claims API](https://apis.io/collections/tidal/open-tidal-claims-api/)
- [TIDAL Catalog acceptedTerms clients API](https://apis.io/collections/tidal/open-tidal-clients-api/)
- [TIDAL Catalog acceptedTerms comments API](https://apis.io/collections/tidal/open-tidal-comments-api/)
- [TIDAL Commerce API](https://apis.io/collections/tidal/open-tidal-commerce-api/)
- [TIDAL Catalog acceptedTerms contentClaims API](https://apis.io/collections/tidal/open-tidal-contentclaims-api/)
- [TIDAL Catalog acceptedTerms credits API](https://apis.io/collections/tidal/open-tidal-credits-api/)
- [TIDAL Catalog acceptedTerms downloads API](https://apis.io/collections/tidal/open-tidal-downloads-api/)
- [TIDAL Catalog acceptedTerms dspSharingLinks API](https://apis.io/collections/tidal/open-tidal-dspsharinglinks-api/)
- [TIDAL Catalog acceptedTerms dynamicModules API](https://apis.io/collections/tidal/open-tidal-dynamicmodules-api/)
- [TIDAL Catalog acceptedTerms dynamicPages API](https://apis.io/collections/tidal/open-tidal-dynamicpages-api/)
- [TIDAL Catalog acceptedTerms genres API](https://apis.io/collections/tidal/open-tidal-genres-api/)
- [TIDAL Catalog acceptedTerms installations API](https://apis.io/collections/tidal/open-tidal-installations-api/)
- [TIDAL Catalog acceptedTerms lyrics API](https://apis.io/collections/tidal/open-tidal-lyrics-api/)
- [TIDAL Catalog acceptedTerms manualArtistClaims API](https://apis.io/collections/tidal/open-tidal-manualartistclaims-api/)
- [TIDAL Catalog acceptedTerms offlineTasks API](https://apis.io/collections/tidal/open-tidal-offlinetasks-api/)
- …and 58 more published on APIs.io

#### Governance rules (2)

Spectral rulesets for the provider's contracts.

- [TIDAL — jsonschema rules](https://apis.io/rules/tidal/tidal-jsonschema-spectral-rules/)
- [TIDAL API Rules](https://apis.io/rules/tidal/tidal-rules/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Tidal Authentication](https://apis.io/security/tidal/tidal-authentication/)
- [Tidal Domain Security](https://apis.io/security/tidal/tidal-domain-security/)
- [Tidal Vulnerability Disclosure](https://apis.io/security/tidal/tidal-vulnerability-disclosure/)

#### OAuth scopes (1)

The permissions the API asks for.

- [Tidal Scopes](https://apis.io/scopes/tidal/tidal-scopes/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Tidal Plans Pricing](https://apis.io/plans/tidal/tidal-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Tidal Rate Limits](https://apis.io/rate-limits/tidal/tidal-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Tidal Finops](https://apis.io/finops/tidal/tidal-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://tidal.com)
- [Documentation](https://developer.tidal.com)
- [Getting started](https://developer.tidal.com/documentation/api-sdk/api-sdk-quick-start)
- [Blog](https://developer.tidal.com/blog)
- [Terms of service](https://developer.tidal.com/documentation/guidelines/guidelines-developer-terms)
- [Privacy policy](https://tidal.com/privacy)
- [GitHub](https://github.com/tidal-music)
- [Status](https://status.tidal.com)

## API Evangelist rating

**Kin Score 48.8** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 62.5 |
| Contract quality | 63.1 |
| Contract governance | 9.8 |
| Operational transparency | 28.9 |
| Developer ergonomics | 44.0 |
| Access clarity | 50.0 |

**Agent readiness 31.9** — agent-ready

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | negotiable (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | verified |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | documented (partial credit) |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | paginated |
| Operation Distinctiveness | distinct |

**Regulatory alignment 40.2** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/tidal/](https://apis.io/providers/tidal/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for TIDAL: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/tidal/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
