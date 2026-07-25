# SC Market

**[sc-market.space](https://sc-market.space)** — the community marketplace for [Star Citizen](https://robertsspaceindustries.com/).

Buy and sell ships, components, and services; run an org shop; and track orders across the 'verse.

## Repositories

| Repo | What it is |
|------|------------|
| [`sc-market-backend`](https://github.com/SC-Market/sc-market-backend) | Express + TypeScript API (v1 routes, v2 TSOA controllers) |
| [`sc-market-frontend`](https://github.com/SC-Market/sc-market-frontend) | React 19 + MUI + RTK Query single-page app (Vite) |
| [`sc-market-cdk`](https://github.com/SC-Market/sc-market-cdk) | AWS CDK infrastructure |
| [`sc-market-image-lambda`](https://github.com/SC-Market/sc-market-image-lambda) | Image processing Lambda (Rekognition moderation, S3, Backblaze) |
| [`SCMarketBot`](https://github.com/SC-Market/SCMarketBot) | Discord bot (Python) |

## Contributing

Issues and pull requests are welcome. This organization also hosts shared GitHub
Actions workflows in [`.github/workflows`](https://github.com/SC-Market/.github/tree/main/.github/workflows)
that individual repos reference via `uses:`.
