# AgentMarketPlace

The marketplace for AI Agents — identities, skins, skills, MCP servers, developer tools and services.

## Local development

```bash
npm install
npm run dev
```

## Build

```bash
npm run build
```

The current V1 uses Next.js static export, so the generated `out/` directory can be deployed to Cloudflare Pages. No secrets are required for the storefront-only build.

## V1 monetization

Humans purchase digital Agent products first. Stripe Checkout will be added server-side before paid buttons are enabled. Do not expose Stripe secret keys in client-side code.
