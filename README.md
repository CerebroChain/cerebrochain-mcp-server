<p align="center">
  <img src="assets/logo.svg" width="120" alt="CerebroChain Logo">
</p>

# CerebroChain MCP server

CerebroChain is a warehouse-management and logistics platform. Its MCP server is hosted, so there
is nothing to install: point Claude, or any MCP client that speaks Streamable HTTP, at

```
https://cerebrochain.com/mcp
```

## Connect

**Claude (web, desktop and mobile).** Open Settings → Connectors → Add custom connector, paste the
URL above, and sign in with your CerebroChain account.

**Other MCP clients.** Use the same URL. Sign in with OAuth 2.1, or send a workspace API key in the
`X-API-Key` header. Create a key in the console under Settings → API keys.

Create an account at [app.cerebrochain.com](https://app.cerebrochain.com). The full setup guide is
at [cerebrochain.com/connect](https://cerebrochain.com/connect).

## What you can do

- **Run your workspace.** Search inventory, list warehouses, orders and shipments, pull the pick
  and pack lists, and read order statistics, KPIs and financial metrics.
- **Make changes, with your go-ahead.** Import items from a spreadsheet, create a warehouse, create
  an order, move an order through its statuses, and adjust stock.
- **Ship.** Compare live UPS, USPS and FedEx rates for a package and prepare the label. You buy it
  in the console with one click.
- **Plan.** Demand forecasts with stockout dates, bottleneck detection, and reorder
  recommendations, computed from your own orders, stock and receiving records.
- **Read the market.** Freight rates, port congestion, shipping lanes, route optimization, and
  forex, commodity and economic series.

## Claude plugin

The [CerebroChain plugin for Claude](https://github.com/CerebroChain/cerebrochain-plugin) pairs the
connector with five skills for everyday warehouse work: set up a workspace from a spreadsheet, ship
an order, the daily floor report, a reorder review, and rate shopping a package.

## Pricing

Each tool call is paid from prepaid credits at the price the tool states. Workspace tools run on a
CerebroChain plan or trial, and rate quotes and market tools work on credits alone. A label costs
the carrier's price plus a $1.00 label fee. Current prices are at
[cerebrochain.com/connect#pricing](https://cerebrochain.com/connect#pricing).

## The npm package

The npm package `@cerebrochain/mcp-server`, whose source is in `src/`, has moved to the hosted
server above. Use the URL in place of the package.

## Support

- Setup guide: [cerebrochain.com/connect](https://cerebrochain.com/connect)
- Privacy: [cerebrochain.com/privacy](https://cerebrochain.com/privacy)
- Help: support@cerebrochain.com

## License

MIT
