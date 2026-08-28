# King's Cross Labs Marketplace

<p align="center">
  <a href="https://kingscrosslabs.com"><img alt="Kings Cross Labs" src="https://img.shields.io/badge/Website-kingscrosslabs.com-009900?style=for-the-badge"/></a>
</p>

This repository hosts Claude marketplace catalogs published by King's Cross Labs.

## Install Instasights

Run these commands in a Claude Code session, including Claude Code inside the Claude Desktop app:

```text
/plugin marketplace add https://github.com/kingscrosslabs/marketplace.git
/plugin install instasights@kingscrosslabs-marketplace
```

Then ask Claude:

> Connect my Instagram account and analyze the last 30 days.

Instasights opens Instagram authorization in your browser and queries professional-account analytics live through `https://instasights.kingscrosslabs.com`. It does not use an MCP server, analytics database, or synchronization job.

Source: [`nickcruz/instasights`](https://github.com/nickcruz/instasights)
