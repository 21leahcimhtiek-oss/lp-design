# design

AI-powered application from Aurora Rayes ecosystem.

## Domain
https://auroramarket.org

## Features
- Premium-only AI tools
- No free tier
- Subscription required

## Deployment (Vercel)
This repository is configured as a static site deployment.

1. Import the repository into Vercel.
2. Leave **Build Command** empty.
3. Set **Output Directory** to `.`.
4. Deploy from the `main` branch.

You can also deploy with the CLI:

```bash
vercel --prod
```

## Environment Variables
Copy `.env.example` to `.env` for local development. In production, configure the same keys in Vercel project settings:

- `NEXT_PUBLIC_APP_URL`
- `NODE_ENV`
- `STRIPE_SECRET_KEY`
- `STRIPE_WEBHOOK_SECRET`
- `NEXT_PUBLIC_STRIPE_PUBLISHABLE_KEY`
- `DATABASE_URL`
- `OPENAI_API_KEY`

## License
See LICENSE file for details.
