# Lichess (lichess)
Lichess is a free, ad-free, open-source online chess server operated by a French nonprofit and powered entirely by volunteers and donations. It serves millions of games per day with live play, tournaments, puzzles, studies, broadcasts, analysis, and a public API. The server (`lila`), engine library (`scalachess`), mobile app, board UI (`chessground`), and distributed Stockfish analysis network (`fishnet`) are all open source under AGPL-3.0, MIT, and GPL-3.0 licenses. The Lichess API provides 185 documented operations across 23 functional areas with comprehensive ND-JSON streaming support.

**URL:** [Visit APIs.json](https://raw.githubusercontent.com/api-evangelist/lichess/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=opensource-api-evangelist&utm_content=repo)

## Tags

- Chess, Games, Open Source, Nonprofit, Tournaments, Puzzles, Bots, Streaming, ND-JSON, OAuth

## Timestamps

- **Created:** 2026-05-25
- **Modified:** 2026-05-25

## At a Glance

| Item | Value |
|---|---|
| OpenAPI version | 3.1.0 |
| Spec version | 2.0.144 |
| Operations | 185 |
| Tag groups | 23 |
| Base URL | `https://lichess.org` |
| Streaming format | ND-JSON (newline-delimited JSON) |
| Auth | OAuth 2.0 PKCE, Personal Access Tokens (bearer) |
| Server license | AGPL-3.0-or-later (`lila`) |
| Engine library | MIT (`scalachess`) |
| Mobile app | GPL-3.0 (`mobile`) |
| Governance | Lichess (French nonprofit), volunteer-driven |
| Funding | Patron donations (lichess.org/patron) |

## APIs

### Lichess API
Comprehensive REST and streaming API covering account, users, games, puzzles, teams, challenges, board and bot play, Arena and Swiss tournaments, simuls, studies, broadcasts, messaging, OAuth, FIDE, opening explorer, tablebase, external engine, and cloud evaluation.

**Human URL:** [https://lichess.org/api](https://lichess.org/api)

- [API Reference](https://lichess.org/api)
- [OpenAPI 3.1 (bundled, local)](openapi/lichess-openapi.yml)
- [OpenAPI source repo](https://github.com/lichess-org/api)
- [JSON Schema — Game](json-schema/lichess-game-schema.json)
- [JSON Schema — User](json-schema/lichess-user-schema.json)
- [JSON-LD context](json-ld/lichess-context.jsonld)

## Capability Coverage (Naftiko)

One self-contained capability per Lichess API tag.

| Tag | Operations | Capability |
|---|---|---|
| Account | 6 | [account](capabilities/account.yaml) |
| Analysis (Cloud eval) | 1 | [analysis](capabilities/analysis.yaml) |
| Board | 13 | [board](capabilities/board.yaml) |
| Bot | 12 | [bot](capabilities/bot.yaml) |
| Broadcasts | 19 | [broadcasts](capabilities/broadcasts.yaml) |
| Bulk pairings | 6 | [bulk-pairings](capabilities/bulk-pairings.yaml) |
| Challenges | 11 | [challenges](capabilities/challenges.yaml) |
| External engine | 8 | [external-engine](capabilities/external-engine.yaml) |
| FIDE | 3 | [fide](capabilities/fide.yaml) |
| Games | 13 | [games](capabilities/games.yaml) |
| Messaging | 1 | [messaging](capabilities/messaging.yaml) |
| OAuth | 4 | [oauth](capabilities/oauth.yaml) |
| Opening Explorer | 4 | [opening-explorer](capabilities/opening-explorer.yaml) |
| Puzzles | 11 | [puzzles](capabilities/puzzles.yaml) |
| Relations | 5 | [relations](capabilities/relations.yaml) |
| Simuls | 1 | [simuls](capabilities/simuls.yaml) |
| Studies | 9 | [studies](capabilities/studies.yaml) |
| Tablebase | 3 | [tablebase](capabilities/tablebase.yaml) |
| Teams | 14 | [teams](capabilities/teams.yaml) |
| Tournaments (Arena) | 13 | [arena-tournaments](capabilities/arena-tournaments.yaml) |
| Tournaments (Swiss) | 10 | [swiss-tournaments](capabilities/swiss-tournaments.yaml) |
| TV | 4 | [tv](capabilities/tv.yaml) |
| Users | 13 | [users](capabilities/users.yaml) |

## Source Code

Lichess is open source from the ground up. The repos below are the canonical ones for the platform.

- [`lila`](https://github.com/lichess-org/lila) — main Lichess server, Scala, AGPL-3.0
- [`api`](https://github.com/lichess-org/api) — OpenAPI specs, docs, and examples for the public API
- [`scalachess`](https://github.com/lichess-org/scalachess) — chess engine library, MIT
- [`chessground`](https://github.com/lichess-org/chessground) — web/mobile chess board UI, GPL-3.0
- [`pgn-viewer`](https://github.com/lichess-org/pgn-viewer) — embeddable PGN viewer widget
- [`mobile`](https://github.com/lichess-org/mobile) — official Flutter mobile app, GPL-3.0
- [`fishnet`](https://github.com/lichess-org/fishnet) — distributed Stockfish analysis network, GPL-3.0
- [`lila-ws`](https://github.com/lichess-org/lila-ws) — websocket server
- [`lila-openingexplorer`](https://github.com/lichess-org/lila-openingexplorer) — opening explorer backend
- [`lila-tablebase`](https://github.com/lichess-org/lila-tablebase) — 7-piece Syzygy tablebase server
- [`lila-engine`](https://github.com/lichess-org/lila-engine) — external engine broker
- [`lila-gif`](https://github.com/lichess-org/lila-gif) — GIF rendering microservice
- [`broadcaster`](https://github.com/lichess-org/broadcaster) — live event broadcast tool
- [`external-engine`](https://github.com/lichess-org/external-engine) — Python client for hosting your own analysis engine
- [`database`](https://github.com/lichess-org/database) — public dataset exports (games, puzzles, evals)

## SDKs and Clients

| Language | Library | Source |
|---|---|---|
| Python | berserk | [lichess-org/berserk](https://github.com/lichess-org/berserk) |
| Python (async) | async-lichess-sdk | [pypi.org/project/async-lichess-sdk](https://pypi.org/project/async-lichess-sdk) |
| MicroPython | uberserk | [mkomon/uberserk](https://github.com/mkomon/uberserk) |
| Python (bot framework) | lichess-bot | [lichess-bot-devs/lichess-bot](https://github.com/lichess-bot-devs/lichess-bot) |
| Java | chariot | [tors42/chariot](https://github.com/tors42/chariot) |
| JavaScript / TypeScript | equine | [devjiwonchoi/equine](https://github.com/devjiwonchoi/equine) |
| .NET | LichessSharp | [Dblike/LichessSharp](https://github.com/Dblike/LichessSharp) |
| C# | LichessNET | [Rabergsel/LichessNET](https://github.com/Rabergsel/LichessNET) |

## Artifacts

### OpenAPI

- [Lichess API (bundled OpenAPI 3.1)](openapi/lichess-openapi.yml)

### JSON Schema

- [Lichess Game Schema](json-schema/lichess-game-schema.json)
- [Lichess User Schema](json-schema/lichess-user-schema.json)

### JSON-LD

- [Lichess Context](json-ld/lichess-context.jsonld)

### Capabilities (Naftiko)

See the [Capability Coverage](#capability-coverage-naftiko) table above. All 23 capabilities live under [`capabilities/`](capabilities/) and each is a self-contained Naftiko `consumes`/`exposes` definition with REST and MCP adapters.

### Commercial artifacts

- [Plans / Pricing](plans/lichess-plans-pricing.yml) — Lichess is free; an optional Lichess Patron donation tier is documented but provides no functional gating
- [Rate Limits](rate-limits/lichess-rate-limits.yml) — per-endpoint guidance plus the global "one request at a time, back off 60s on 429" policy

## Datasets

Lichess publishes complete public dataset exports under the Creative Commons CC0 license.

- [database.lichess.org](https://database.lichess.org/) — all rated games in PGN, all puzzles with themes and ratings, all evaluated positions

## Authentication

- Personal API access tokens: [lichess.org/account/oauth/token](https://lichess.org/account/oauth/token)
- OAuth 2.0 Authorization Code Flow with PKCE; long-lived access tokens (typical one-year lifetime); no refresh tokens
- See the OAuth examples in [lichess-org/api/example](https://github.com/lichess-org/api/tree/master/example)

## Maintainers

**FN:** Kin Lane

**Email:** info@apievangelist.com

**X:** apievangelist

**URL:** [https://apievangelist.com](https://apievangelist.com)
