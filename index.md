# Universal Cart Merchant Gate

Universal Cart Merchant Gate is a hosted remote MCP for Universal Cart merchant readiness MCP.

This repository is a public documentation project for Universal Cart Merchant Gate. Its structure follows the public documentation pattern used by [MiroFish](https://github.com/clauxel/MiroFish): a short front door, a clear reading order, practical guides, reference pages, and a public-safe boundary.

## Start Here

- Website: https://universalcartmerchantgate.clauxel.com/?utm_source=github&utm_medium=documentation&utm_campaign=universalcartmerchantgate_public_docs&utm_content=readme_home
- Pricing: https://universalcartmerchantgate.clauxel.com/pricing/?utm_source=github&utm_medium=documentation&utm_campaign=universalcartmerchantgate_public_docs&utm_content=readme_pricing
- Checkout: https://universalcartmerchantgate.clauxel.com/checkout/?utm_source=github&utm_medium=documentation&utm_campaign=universalcartmerchantgate_public_docs&utm_content=readme_checkout
- Support: support@aigeamy.com

## Remote MCP

- Endpoint: https://universalcartmerchantgate.clauxel.com/mcp
- Server card: https://universalcartmerchantgate.clauxel.com/server-card.json
- Registry name: `com.clauxel.universalcartmerchantgate/universalcartmerchantgate-mcp`
- Tools: `check_universal_cart_readiness`, `classify_checkout_blocker`, `explain_offer_gap`, `issue_agentic_commerce_receipt`, `export_readiness_log`

## Reading Order

1. [Quickstart](guide/quickstart.md)
2. [Evaluation guide](guide/evaluation.md)
3. [Checkout and pricing](guide/checkout-and-pricing.md)
4. [Workflow notes](features/workflow.md)
5. [Security model](features/security-model.md)
6. [Public link reference](reference/links.md)

## Audience

commerce teams, merchant operations teams, marketplace owners, and agentic checkout reviewers.

## Capabilities

- Streamable HTTP MCP endpoint
- Bearer-token access for production calls
- Structured tool-call output
- Receipt-oriented evidence export
- Public server card and registry metadata
- MCP tool: check_universal_cart_readiness
- MCP tool: classify_checkout_blocker
- MCP tool: explain_offer_gap
- MCP tool: issue_agentic_commerce_receipt
- MCP tool: export_readiness_log

## Public-Safe Boundary

This repository contains documentation only. It does not contain production source code, credentials, payment configuration, Cloudflare configuration, customer records, private analytics, or local machine paths.
