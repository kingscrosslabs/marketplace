# King's Cross Labs Marketplace

<p align="center">
  <a href="https://kingscrosslabs.com"><img alt="Kings Cross Labs" src="https://img.shields.io/badge/Website-kingscrosslabs.com-009900?style=for-the-badge"/></a>
</p>

This repository hosts Claude marketplace catalogs published by King's Cross Labs.

## Install Instasights

Run these commands in Claude Code, including Claude Code inside the Claude Desktop app:

```text
/plugin marketplace add https://github.com/kingscrosslabs/marketplace.git
/plugin install instasights@kingscrosslabs-marketplace
```

Then ask Claude:

> Connect my Instagram account and analyze the last 30 days.

Instasights 3.0 is an MCP-only plugin. Claude opens Instagram Login through standard MCP OAuth and discovers five typed, read-only analytics tools. The plugin contains no CLI, executable skill, local token file, analytics database, or synchronization job.

Remote MCP endpoint: `https://instasights.kingscrosslabs.com/mcp`

Source: [`nickcruz/instasights`](https://github.com/nickcruz/instasights)
