# Lichess (lichess)

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

Lichess is a free, ad-free, open-source online chess server operated by a French nonprofit and powered entirely by volunteers and donations. It serves millions of games per day with live play, tournaments, puzzles, studies, broadcasts, analysis, and a public API. The server (lila), engine library (scalachess), mobile app, board UI (chessground), and distributed Stockfish analysis network (fishnet) are all open source under AGPL-3.0, MIT, and GPL-3.0 licenses. The Lichess API provides 185 documented operations across 23 functional areas including Account, Users, Games, Puzzles, Teams, Board, Bot, Challenges, Arena and Swiss Tournaments, Simuls, Studies, Broadcasts, Messaging, OAuth, FIDE, Opening Explorer, Tablebase, External Engine, and Cloud Analysis, with comprehensive ND-JSON streaming support.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/lichess/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/lichess/refs/heads/main/apis.yml)

## Scope

- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- Chess
- Games
- Open Source
- Nonprofit
- Tournaments
- Puzzles
- Bots
- Streaming
- ND-JSON
- OAuth

## Timestamps

- **Created:** 2026-05-25T00:00:00.000Z
- **Modified:** 2026-05-25

## APIs

### Lichess API

The Lichess API is a comprehensive REST and streaming API covering account, users, games, puzzles, teams, challenges, board and bot play, Arena and Swiss tournaments, simuls, studies, broadcasts, messaging, OAuth, FIDE data, opening explorer, tablebase, external engine, and cloud evaluation. The full OpenAPI 3.1 specification is published at github.com/lichess-org/api with 185 operations across 23 tags, and many endpoints stream responses as newline-delimited JSON (ND-JSON).

- **Human URL:** [https://lichess.org/api](https://lichess.org/api)
- **Base URL:** `https://lichess.org`

#### Tags

- Chess
- Games
- Open Source
- REST

#### Properties

- [Documentation](https://lichess.org/api)
- [OpenAPI](openapi/lichess-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/lichess.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/lichess.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [OpenAPI](https://github.com/lichess-org/api/blob/master/doc/specs/lichess-api.yaml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [AsyncAPI](asyncapi/lichess-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [JSON Schema](json-schema/lichess-game-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/lichess-user-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/lichess-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Spectral Ruleset](rules/lichess-rules.yml)

## Common Properties

- [Portal](https://lichess.org)
- [Documentation](https://lichess.org/api)
- [Sandbox](https://lichess.org/api/ui)
- [Sandbox](https://lichess-org.github.io/api-demo/)
- [GitHub Organization](https://github.com/lichess-org)
- [Source Code](https://github.com/lichess-org/api)
- [Source Code](https://github.com/lichess-org/lila)
- [Source Code](https://github.com/lichess-org/scalachess)
- [Source Code](https://github.com/lichess-org/chessground)
- [Source Code](https://github.com/lichess-org/pgn-viewer)
- [Source Code](https://github.com/lichess-org/mobile)
- [SDK](https://github.com/lichess-org/berserk)
- [SDK](https://github.com/tors42/chariot)
- [SDK](https://github.com/devjiwonchoi/equine)
- [SDK](https://github.com/Rabergsel/LichessNET)
- [SDK](https://github.com/Dblike/LichessSharp)
- [SDK](https://github.com/mkomon/uberserk)
- [SDK](https://pypi.org/project/async-lichess-sdk)
- [Tool](https://github.com/lichess-bot-devs/lichess-bot)
- [Tool](https://github.com/lichess-org/fishnet)
- [Tool](https://github.com/lichess-org/external-engine)
- [Tool](https://github.com/lichess-org/broadcaster)
- [Tool](https://github.com/lichess-org/pgn-mule)
- [Tool](https://github.com/lichess-org/api-ui)
- [Code Examples](https://github.com/lichess-org/api/tree/master/example)
- [Forum](https://discord.gg/lichess)
- [Forum](https://lichess.org/forum)
- [Bulk Data Download](https://database.lichess.org/)
- [Authentication](https://lichess.org/account/oauth/token)
- [Documentation](https://lichess.org/developers)
- [Authentication](https://lichess.org/account/oauth/app)
- [Terms of Service](https://lichess.org/page/fair-play)
- [Terms of Service](https://lichess.org/terms-of-service)
- [Privacy Policy](https://lichess.org/privacy)
- [Source Code](https://lichess.org/source)
- [Donate](https://lichess.org/patron)
- [Status Page](https://status.lichess.org/)
- [Blog](https://lichess.org/blog)
- [Rate Limits](https://lichess.org/api#section/Introduction/Rate-limiting)
- [Authentication](https://lichess.org/api#tag/OAuth)
- [License](https://www.gnu.org/licenses/agpl-3.0.txt)
- [Plans](plans/lichess-plans-pricing.yml)
- [Rate Limits](rate-limits/lichess-rate-limits.yml)
- [Features](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** info@apievangelist.com
**URL:** https://apievangelist.com
