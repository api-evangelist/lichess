# Lichess

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

Lichess is a free, ad-free, open-source online chess server operated by a French nonprofit and powered entirely by volunteers and donations. It serves millions of games per day with live play, tournaments, puzzles, studies, broadcasts, analysis, and a public API. The server (lila), engine library (scalachess), mobile app, board UI (chessground), and distributed Stockfish analysis network (fishnet) are all open source under AGPL-3.0, MIT, and GPL-3.0 licenses. The Lichess API provides 185 documented operations across 23 functional areas including Account, Users, Games, Puzzles, Teams, Board, Bot, Challenges, Arena and Swiss Tournaments, Simuls, Studies, Broadcasts, Messaging, OAuth, FIDE, Opening Explorer, Tablebase, External Engine, and Cloud Analysis, with comprehensive ND-JSON streaming support.

**Areas:** Chess · Games · Open Source · Non-Profit · Tournaments · Puzzles · Bots · Streaming · ND-JSON · Authentication

## Lichess on APIs.io

Everything profiled for Lichess is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/lichess/](https://apis.io/providers/lichess/)** — or go straight to one of the APIs or properties below.

### APIs (23)

- [Lichess Account API](https://apis.io/apis/lichess/lichess-account-api/) — Read and write account information and preferences. <https://lichess.org/account/preferences/game-display>
- [Lichess Analysis API](https://apis.io/apis/lichess/lichess-analysis-api/) — Access Lichess cloud evaluations database. <https://lichess.org/analysis>
- [Lichess Board API](https://apis.io/apis/lichess/lichess-board-api/) — Play on Lichess with physical boards and third-party clients. Works with normal Lichess accounts. Engine play or assistance is…
- [Lichess Bot API](https://apis.io/apis/lichess/lichess-bot-api/) — Play on Lichess as a bot. Allows engine play. Read the [blog post announcement of lichess…
- [Lichess Broadcasts API](https://apis.io/apis/lichess/lichess-broadcasts-api/) — Relay chess events on Lichess. [Official broadcasts](https://lichess.org/broadcast) are maintained by Lichess, but you can [create your own…
- [Lichess Bulk pairings API](https://apis.io/apis/lichess/lichess-bulk-pairings-api/) — Create many games for other players. These endpoints are intended for tournament organisers.
- [Lichess Challenges API](https://apis.io/apis/lichess/lichess-challenges-api/) — Send and receive challenges to play. To create a lot of challenges, consider [bulk pairing](#tag/bulk-pairings/POST/api/bulk-pairing) instead.
- [Lichess External engine API](https://apis.io/apis/lichess/lichess-external-engine-api/) — **This API is in alpha and subject to change.** Use or provide external engine analysis. External engines can provide analysis on pages like the [analysis…
- [Lichess FIDE API](https://apis.io/apis/lichess/lichess-fide-api/) — FIDE players and federations from [their public download](https://ratings.fide.com/download_lists.phtml). <https://lichess.org/fide>
- [Lichess Games API](https://apis.io/apis/lichess/lichess-games-api/) — Access games played on Lichess. <https://lichess.org/games>
- [Lichess Messaging API](https://apis.io/apis/lichess/lichess-messaging-api/) — Private messages with other players. <https://lichess.org/inbox>
- [Lichess Opening Explorer API](https://apis.io/apis/lichess/lichess-opening-explorer-api/) — Lookup positions from the [Lichess opening explorer](https://lichess.org/analysis#explorer). Runs <https://github.com/lichess-org/lila-openingexplorer>. >…
- [Lichess Puzzles API](https://apis.io/apis/lichess/lichess-puzzles-api/) — Fetch and solve [puzzles](https://lichess.org/training), view your puzzle history and dashboard. Our collection of puzzles is in the public domain, you can…
- [Lichess Relations API](https://apis.io/apis/lichess/lichess-relations-api/) — Access relations between users.
- [Lichess Simuls API](https://apis.io/apis/lichess/lichess-simuls-api/) — Access simuls played on Lichess. <https://lichess.org/simul>
- [Lichess Studies API](https://apis.io/apis/lichess/lichess-studies-api/) — Access Lichess studies. <https://lichess.org/study>
- [Lichess Tablebase API](https://apis.io/apis/lichess/lichess-tablebase-api/) — Lookup positions from the [Lichess tablebase server](https://lichess.org/blog/W3WeMyQAACQAdfAL/7-piece-syzygy-tablebases-are-complete). > [!important] > The…
- [Lichess Teams API](https://apis.io/apis/lichess/lichess-teams-api/) — Access and manage Lichess teams and their members. <https://lichess.org/team>
- [Lichess Tournaments (Arena) API](https://apis.io/apis/lichess/lichess-tournaments-arena-api/) — Access Arena tournaments played on Lichess. [Official Arena tournaments](https://lichess.org/tournament) are maintained by Lichess, but you can [create your…
- [Lichess Tournaments (Swiss) API](https://apis.io/apis/lichess/lichess-tournaments-swiss-api/) — Access Swiss tournaments played on Lichess. [Read more about Swiss tournaments.](https://lichess.org/swiss).
- [Lichess TV API](https://apis.io/apis/lichess/lichess-tv-api/) — Access Lichess TV channels and games. <https://lichess.org/tv> & <https://lichess.org/games>
- [Lichess Users API](https://apis.io/apis/lichess/lichess-users-api/) — Access registered users on Lichess. <https://lichess.org/player> - Each user blog exposes an atom (RSS) feed, like…
- [Lichess O Auth API](https://apis.io/apis/lichess/lichess-oauth-api/) — Obtaining and revoking OAuth tokens. [Read about the Lichess API authentication methods and code…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Lichess Streaming API](https://apis.io/asyncapis/lichess/lichess-asyncapi/)

#### Event channels (11)

Individual events and webhooks the provider emits.

- [/api/board/game/stream/{gameId}](https://apis.io/channels/lichess/api-board-game-stream-gameid/)
- [/api/bot/game/stream/{gameId}](https://apis.io/channels/lichess/api-bot-game-stream-gameid/)
- [/api/broadcast/my-rounds](https://apis.io/channels/lichess/api-broadcast-my-rounds/)
- [/api/games/user/{username}](https://apis.io/channels/lichess/api-games-user-username/)
- [/api/stream/broadcast/round/{broadcastRoundId}.pgn](https://apis.io/channels/lichess/api-stream-broadcast-round-broadcastroundid-pgn/)
- [/api/stream/event](https://apis.io/channels/lichess/api-stream-event/)
- [/api/stream/game/{id}](https://apis.io/channels/lichess/api-stream-game-id/)
- [/api/stream/games-by-users](https://apis.io/channels/lichess/api-stream-games-by-users/)
- [/api/stream/games/{streamId}](https://apis.io/channels/lichess/api-stream-games-streamid/)
- [/api/tv/{channel}/feed](https://apis.io/channels/lichess/api-tv-channel-feed/)
- [/api/tv/feed](https://apis.io/channels/lichess/api-tv-feed/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Lichess Agentic Access](https://apis.io/agentic-access/lichess/lichess-agentic-access/)

#### JSON Schema (2)

The data models the API reads and writes.

- [Lichess Game](https://apis.io/schemas/lichess/lichess-game/)
- [Lichess User](https://apis.io/schemas/lichess/lichess-user/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Lichess Context](https://apis.io/jsonld/lichess/lichess-context/)

#### Collections (47)

Postman and Open Collection request collections.

- [Lichess.org API reference](https://apis.io/collections/lichess/open-lichess/)
- [Lichess.org API reference Account API](https://apis.io/collections/lichess/open-lichess-account-api/)
- [Lichess.org API reference Account Analysis API](https://apis.io/collections/lichess/open-lichess-analysis-api/)
- [Lichess.org API reference Account Board API](https://apis.io/collections/lichess/open-lichess-board-api/)
- [Lichess.org API reference Account Bot API](https://apis.io/collections/lichess/open-lichess-bot-api/)
- [Lichess.org API reference Account Broadcasts API](https://apis.io/collections/lichess/open-lichess-broadcasts-api/)
- [Lichess.org API reference Account Bulk pairings API](https://apis.io/collections/lichess/open-lichess-bulk-pairings-api/)
- [Lichess.org API reference Account Challenges API](https://apis.io/collections/lichess/open-lichess-challenges-api/)
- [Lichess.org API reference Account External engine API](https://apis.io/collections/lichess/open-lichess-external-engine-api/)
- [Lichess.org API reference Account FIDE API](https://apis.io/collections/lichess/open-lichess-fide-api/)
- [Lichess.org API reference Account Games API](https://apis.io/collections/lichess/open-lichess-games-api/)
- [Lichess.org API reference Account Messaging API](https://apis.io/collections/lichess/open-lichess-messaging-api/)
- [Lichess.org API reference Account OAuth API](https://apis.io/collections/lichess/open-lichess-oauth-api/)
- [Lichess.org API reference Account Opening Explorer API](https://apis.io/collections/lichess/open-lichess-opening-explorer-api/)
- [Lichess.org API reference Account Puzzles API](https://apis.io/collections/lichess/open-lichess-puzzles-api/)
- [Lichess.org API reference Account Relations API](https://apis.io/collections/lichess/open-lichess-relations-api/)
- [Lichess.org API reference Account Simuls API](https://apis.io/collections/lichess/open-lichess-simuls-api/)
- [Lichess.org API reference Account Studies API](https://apis.io/collections/lichess/open-lichess-studies-api/)
- [Lichess.org API reference Account Tablebase API](https://apis.io/collections/lichess/open-lichess-tablebase-api/)
- [Lichess.org API reference Account Teams API](https://apis.io/collections/lichess/open-lichess-teams-api/)
- [Lichess.org API reference Account Tournaments (Arena) API](https://apis.io/collections/lichess/open-lichess-tournaments-arena-api/)
- [Lichess.org API reference Account Tournaments (Swiss) API](https://apis.io/collections/lichess/open-lichess-tournaments-swiss-api/)
- [Lichess.org API reference Account TV API](https://apis.io/collections/lichess/open-lichess-tv-api/)
- [Lichess.org API reference Account Users API](https://apis.io/collections/lichess/open-lichess-users-api/)
- [Lichess.org API reference Account API](https://apis.io/collections/lichess/postman-lichess-account-api/)
- …and 22 more published on APIs.io

#### Governance rules (3)

Spectral rulesets for the provider's contracts.

- [Lichess — asyncapi rules](https://apis.io/rules/lichess/lichess-asyncapi-spectral-rules/)
- [Lichess — jsonschema rules](https://apis.io/rules/lichess/lichess-jsonschema-spectral-rules/)
- [Lichess API Rules](https://apis.io/rules/lichess/lichess-rules/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Lichess Authentication](https://apis.io/security/lichess/lichess-authentication/)
- [Lichess Domain Security](https://apis.io/security/lichess/lichess-domain-security/)
- [Lichess Vulnerability Disclosure](https://apis.io/security/lichess/lichess-vulnerability-disclosure/)

#### OAuth scopes (1)

The permissions the API asks for.

- [Lichess Scopes](https://apis.io/scopes/lichess/lichess-scopes/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Lichess Plans Pricing](https://apis.io/plans/lichess/lichess-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Lichess Rate Limits](https://apis.io/rate-limits/lichess/lichess-rate-limits/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.lichess.org/)
- [Documentation](https://lichess.org/api)
- [Blog](https://lichess.org/blog)
- [Terms of service](https://lichess.org/page/fair-play)
- [Privacy policy](https://lichess.org/privacy)
- [GitHub](https://github.com/lichess-org)
- [Status](https://status.lichess.org/)

## API Evangelist rating

**Kin Score 53.0** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 66.1 |
| Contract quality | 74.7 |
| Contract governance | 13.6 |
| Operational transparency | 39.5 |
| Developer ergonomics | 63.1 |
| Access clarity | 26.3 |

**Agent readiness 38.4** — agent-ready

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | documented (partial credit) |
| MCP Server | — |
| Auth Clarity | negotiable (partial credit) |
| Idempotency | — |
| Error Semantics | verified |
| OpenAPI Examples | verified |
| Rate Limit Signal | documented (partial credit) |
| Event Surface Described | derived (partial credit) |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | documented (partial credit) |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | — |
| Operation Distinctiveness | distinct |

**Regulatory alignment 40.2** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/lichess/](https://apis.io/providers/lichess/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Lichess: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/lichess/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
