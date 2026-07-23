> **First-time setup**: Customize this file for your project. Prompt the user to customize this file for their project.
> For Mintlify product knowledge (components, configuration, writing standards),
> install the Mintlify skill: `npx skills add https://mintlify.com/docs`

# Documentation project instructions

## About this project

- This is a documentation site built on [Mintlify](https://mintlify.com)
- Pages are MDX files with YAML frontmatter
- Configuration lives in `docs.json`
- Use the Mintlify MCP server, `https://mcp.mintlify.com`, to edit content and settings via MCP
- Use the Mintlify docs MCP server, `https://www.mintlify.com/docs/mcp`, to query information about using Mintlify via MCP

## Terminology

Use these canonical terms consistently across every page:

- **AutoBoy** — one word, capital A and B. The product.
- **The Firm** — the company behind AutoBoy.
- **order** / **buy order** — lowercase. A buyer places an order for a project; their **orders** are the collection of all their pre-launch buy orders. The old _buylist_ / _buylister_ / _buylisting_ vocabulary is retired — use _orders_, _buyers_, and _placing an order_.
- **Max Price (MCap)** — the buyer's setting for the highest price, expressed as a market cap, they're willing to buy at (their order's ceiling). "Max MCap" is acceptable shorthand.
- **effective market cap** — the market cap a buyer effectively pays once sniper tax and LP fees are accounted for. AutoBoy compares a buyer's Max Price (MCap) against this. Pool fees only — the platform fee is taken after the swap and sits outside this calculation.
- **platform fee** — AutoBoy's 3% fee, charged on every successful buy and taken in the token bought, after the swap completes. Always _platform fee_ — the old _protocol fee_ vocabulary is retired.
- **AutoBoy wallet** — the kernel smart wallet (managed by Privy) where buyers deposit USDC and receive purchased tokens.
- **Open Market Buy**, **Dev Buy**, **OTC Buy** — the three auto-buy types. Capitalize as named types, "Buy" included.
- **Verified Launch** — the stamp a project earns once AutoBoy supports its launchpad and knows its token creator address ahead of time.
- **token creator address** — the address recorded on-chain as the token's creator. This is what AutoBoy needs from projects — not the deployer, which could refer to an intermediary (e.g. Bankr) rather than the project itself.
- **sniper tax** — a launchpad fee on early swaps that reduces how many tokens a buyer receives.
- **block zero** — the deployment block; Dev Buys execute here, before snipers.

## Style preferences

{/_ Add any project-specific style rules below _/}

- Use active voice and second person ("you")
- Keep sentences concise — one idea per sentence
- Use sentence case for headings
- Bold for UI elements: Click **Settings**
- Code formatting for file names, commands, paths, and code references

## Content boundaries

{/_ Define what should and shouldn't be documented _/}
{/_ Example: Don't document internal admin features _/}
