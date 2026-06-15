# Polymarket (polymarket)

Polymarket is a decentralized prediction-market platform built on Polygon where users buy and sell binary outcome shares in real-world events. Settlement is on-chain via the UMA optimistic oracle, while order matching runs through a hybrid central-limit order book (CLOB). Developer surface includes the CLOB API for order placement and market data, the Gamma API for market and event metadata, a Data API for historical and analytical reads, a WebSocket stream, and official CLOB client SDKs in TypeScript, Python, and Rust.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/polymarket/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/polymarket/refs/heads/main/apis.yml)

## Tags

- Prediction Markets
- DeFi
- Polygon
- Order Book
- Crypto
- Markets

## Timestamps

- **Created:** 2026-05-23
- **Modified:** 2026-05-29

## APIs

### Polymarket CLOB API

Central-limit order book REST API for Polymarket - place, cancel, and query orders, list markets and tokens, fetch order books and trades, and look up user positions. Used by traders and bots interacting with Polymarket's matched markets.

- **Human URL:** [https://docs.polymarket.com/](https://docs.polymarket.com/)
- **Base URL:** `https://clob.polymarket.com`

#### Tags

- REST
- Orders
- Order Book
- Markets

#### Properties

- [Documentation](https://docs.polymarket.com/)
- [Postman Collection](collections/polymarket.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/polymarket.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Polymarket Gamma API

Read-only metadata API for markets, events, tags, and categories - the surface that powers polymarket.com's listings and search. Useful for discovery and for stitching multiple binary markets into the broader events they belong to.

- **Human URL:** [https://docs.polymarket.com/](https://docs.polymarket.com/)
- **Base URL:** `https://gamma-api.polymarket.com`

#### Tags

- REST
- Markets
- Events
- Metadata

#### Properties

- [Documentation](https://docs.polymarket.com/)
- [Postman Collection](collections/polymarket.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/polymarket.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Polymarket Data API

Historical and analytical data API exposing trades, prices, volumes, holders, and time-series aggregates across Polymarket markets, intended for research, dashboards, and quantitative use.

- **Human URL:** [https://docs.polymarket.com/](https://docs.polymarket.com/)
- **Base URL:** `https://data-api.polymarket.com`

#### Tags

- Data
- Historical
- Analytics

#### Properties

- [Documentation](https://docs.polymarket.com/)
- [Postman Collection](collections/polymarket.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/polymarket.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Polymarket WebSocket

Real-time streaming feed for order book updates, trades, and market events on the Polymarket CLOB - used by trading clients to maintain a live view of the book without polling.

- **Human URL:** [https://docs.polymarket.com/](https://docs.polymarket.com/)
- **Base URL:** `wss://ws-subscriptions-clob.polymarket.com`

#### Tags

- WebSocket
- Streaming
- Order Book

#### Properties

- [Documentation](https://docs.polymarket.com/)
- [AsyncAPI](https://raw.githubusercontent.com/api-evangelist/polymarket/refs/heads/main/asyncapi/polymarket-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Postman Collection](collections/polymarket.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/polymarket.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### py-clob-client (Python SDK)

Official Python SDK for the Polymarket CLOB API - wallet signing, EIP-712 order construction, place / cancel / query, and market data helpers.

- **Human URL:** [https://github.com/Polymarket/py-clob-client](https://github.com/Polymarket/py-clob-client)
- **Base URL:** `https://github.com/Polymarket/py-clob-client`

#### Tags

- SDK
- Python
- CLOB

#### Properties

- [Repository](https://github.com/Polymarket/py-clob-client)
- [Postman Collection](collections/polymarket.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/polymarket.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### clob-client (TypeScript SDK)

Official TypeScript / JavaScript SDK for the Polymarket CLOB API - typed clients, wallet integration (viem), order construction, and market data helpers.

- **Human URL:** [https://github.com/Polymarket/clob-client](https://github.com/Polymarket/clob-client)
- **Base URL:** `https://github.com/Polymarket/clob-client`

#### Tags

- SDK
- TypeScript
- JavaScript
- CLOB

#### Properties

- [Repository](https://github.com/Polymarket/clob-client)
- [Postman Collection](collections/polymarket.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/polymarket.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### clob-client (Rust SDK)

Official Rust SDK for the Polymarket CLOB API.

- **Human URL:** [https://github.com/Polymarket/rust-clob-client](https://github.com/Polymarket/rust-clob-client)
- **Base URL:** `https://github.com/Polymarket/rust-clob-client`

#### Tags

- SDK
- Rust
- CLOB

#### Properties

- [Repository](https://github.com/Polymarket/rust-clob-client)
- [Postman Collection](collections/polymarket.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/polymarket.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://polymarket.com/)
- [Documentation](https://docs.polymarket.com/)
- [U S  Documentation](https://docs.polymarket.us/)
- [Git Hub](https://github.com/Polymarket)
- [Builders  Program](https://builders.polymarket.com/)
- [Help  Desk](https://help.polymarket.com/)
- [Status](https://status.polymarket.com/)
- [LinkedIn](https://www.linkedin.com/company/polymarket/)
- [L L Ms Txt](https://docs.polymarket.us/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
