# Medusa Plugin for Cursor

Connect [Cursor](https://cursor.com) to your Medusa Cloud stores and the Medusa documentation through the [Medusa MCP server](https://docs.medusajs.com/cloud/medusa-mcp).

## Install

Open **Cursor Settings → Plugins**, search for **Medusa**, and click **Install**. Or run this in the Cursor chat:

```
/add-plugin medusa
```

Then sign in with your Medusa Cloud account when Cursor prompts you, or from **Cursor Settings → Tools & MCP**.

## What you can do

- Read data from your Medusa Cloud stores, such as products, orders and customers, through the Admin and Store APIs.
- Find and inspect your store's API routes, including custom routes.
- Ask questions about Medusa, answered from the official documentation.

Store tools are read-only.

## Example prompts

- "List my connected Medusa stores."
- "Show the 10 most recent orders in my staging store."
- "How do I create a custom module in Medusa?"

## What's included

| Component | Path | Purpose |
| --- | --- | --- |
| MCP server | `mcp.json` | Connects to `https://cloud.medusajs.com/mcp` with OAuth |
| Rule | `rules/medusa.mdc` | Guides the agent on picking environments, reading APIs and searching the docs |

## Requirements

- A Medusa Cloud account with access to the Medusa MCP.

## License

MIT
