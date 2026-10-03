# Dsrupt for Claude

Dsrupt turns a company's saved brands into on-brand creative work. With this plugin, Claude can plan and produce images, video, audio, motion graphics and new versions of an existing ad, all using the logos, colours, products and people already stored in your Dsrupt account.

## What's inside

- **Dsrupt connector** (`.mcp.json`): connects Claude to the Dsrupt MCP server at `https://backend.dsrupt.ai/mcp`. You sign in to your Dsrupt account through OAuth the first time Claude uses it.
- **`dsrupt` skill** (`skills/dsrupt/SKILL.md`): a short pointer that tells Claude to fetch its working instructions from the Dsrupt server before doing anything, so it always follows the current guides instead of improvising.

## What it sends and where

The plugin talks to one place only: `backend.dsrupt.ai`, Dsrupt's own server. Prompts, uploaded files and brand details you ask Claude to use are sent there so Dsrupt can generate the work. Generation uses credits from your Dsrupt account, and Claude quotes the price before it spends any. The plugin runs no local code, installs no packages and stores no credentials on your machine.

## Requirements

A Dsrupt account. Sign up at [dsrupt.ai](https://dsrupt.ai).

## Privacy

See the Dsrupt privacy policy at [backend.dsrupt.ai/privacy-policy](https://backend.dsrupt.ai/privacy-policy).

## Support

Email support@dsrupt.ai.
