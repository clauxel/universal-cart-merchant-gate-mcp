# Universal Cart Merchant Gate MCP

Universal Cart merchant readiness MCP with structured receipts.

Paid remote MCP for Universal Cart merchant readiness MCP, structured receipts, audit logs, and reviewer-ready evidence.

## Public Endpoints

- Website: https://universalcartmerchantgate.clauxel.com/?utm_source=github&utm_medium=directory&utm_campaign=sbl202605
- MCP endpoint: https://universalcartmerchantgate.clauxel.com/mcp
- Server card: https://universalcartmerchantgate.clauxel.com/server-card.json
- Registry name: `com.clauxel.universalcartmerchantgate/universalcartmerchantgate-mcp`

## Access

This is a paid hosted remote MCP. Production calls require a bearer token issued from the product website.

```http
Authorization: Bearer <token>
```

Unauthenticated browser visits to `/mcp` return a clear JSON error instead of internal details.

## Tools

- `check_universal_cart_readiness`
- `classify_checkout_blocker`
- `explain_offer_gap`
- `issue_agentic_commerce_receipt`
- `export_readiness_log`

## Quick Start

1. Open the website and choose a plan.
2. Create or request an API token.
3. Add the endpoint to an MCP client that supports Streamable HTTP remote servers.
4. Send JSON-RPC requests with the bearer token.

## Useful Links

- Product page: https://universalcartmerchantgate.clauxel.com/?utm_source=github&utm_medium=directory&utm_campaign=sbl202605
- Pricing: https://universalcartmerchantgate.clauxel.com/?utm_source=github&utm_medium=directory&utm_campaign=sbl202605#pricing
- Server card: https://universalcartmerchantgate.clauxel.com/server-card.json
- MCP endpoint: https://universalcartmerchantgate.clauxel.com/mcp

## Status

This repository is a public documentation and directory-submission reference for the hosted service. It does not contain the private production source code.
