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
- **buylist** / **buy order** — lowercase. A buyer adds projects to their buylist, creating a buy order for each.
- **Max Price (MCap)** — the buyer's setting for the highest price, expressed as a market cap, they're willing to buy at (their order's ceiling). "Max MCap" is acceptable shorthand.
- **effective market cap** — the market cap a buyer effectively pays once sniper tax and LP fees are accounted for. AutoBoy compares a buyer's Max Price (MCap) against this.
- **AutoBoy wallet** — the kernel smart wallet (managed by Privy) where buyers deposit USDC and receive purchased tokens.
- **Open Market Buy**, **Dev Buy**, **OTC Buy** — the three auto-buy types. Capitalize as named types, "Buy" included.
- **Verified Launch** — the stamp a project earns once AutoBoy supports its launchpad and knows its deployment address ahead of time.
- **sniper tax** — a launchpad fee on early swaps that reduces how many tokens a buyer receives.
- **block zero** — the deployment block; Dev Buys execute here, before snipers.

## Style preferences

{/* Add any project-specific style rules below */}

- Use active voice and second person ("you")
- Keep sentences concise — one idea per sentence
- Use sentence case for headings
- Bold for UI elements: Click **Settings**
- Code formatting for file names, commands, paths, and code references

## Content boundaries

{/* Define what should and shouldn't be documented */}
{/* Example: Don't document internal admin features */}
