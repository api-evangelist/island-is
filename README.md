# island.is (island-is)

island.is (Stafrænt Ísland / Digital Iceland) is Iceland's national digital-services and government **API platform** — a GraphQL gateway plus OpenAPI 3.0 services registered in the X-Road "Straumurinn" API Catalogue. The developer handbook is at docs.devland.is.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/island-is/refs/heads/main/apis.yml)

## Type
- **kind:** government  ·  **software:** GraphQL gateway + OpenAPI 3.0 / X-Road

## API
- **island.is GraphQL Gateway** — `https://api.island.is` (auth-gated; returns 404 to anonymous probes). [Docs](https://docs.devland.is/)
- **X-Road (Straumurinn) API Catalogue** — government-to-government REST services described with OpenAPI 3.0, auto-imported into the X-Road catalogue. [X-Road docs](https://docs.devland.is/products/x-road.md)
- **Note:** Iceland's former CKAN open-data portal **opingogn.is is decommissioned** and 301-redirects into island.is; its CKAN Action API returns 404. The live, governed national API surface is island.is / Digital Iceland. Do not confuse with the community aggregator apis.is.

## Timestamps
- **Created:** 2026-06-23
- **Modified:** 2026-06-23

## Maintainers
**FN:** Kin Lane

**Email:** kin@apievangelist.com
