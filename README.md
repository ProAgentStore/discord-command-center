# Discord Command Center

Private Discord operations agent for managing, searching, summarizing, and administering the Discord servers available to the owner's bot.

## AI billing

This generated agent does not use the ProAgentStore Cloudflare Workers AI binding by default. AI calls require caller-provided Cloudflare Workers AI credentials:

- `X-CF-Account-ID`
- `X-CF-AI-Token`

That makes inference spend bill to the caller's Cloudflare account, not the ProAgentStore platform account.

## Development

```bash
pnpm install
pnpm dev
```

## Deploy

```bash
pnpm deploy
```
