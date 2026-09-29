# NEXORA — Deployable React Frontend

NEXORA is a portfolio-grade simulated multi-asset investment platform frontend built with React, TypeScript, Vite and Tailwind CSS.

## Run locally (optional)

```bash
npm install
npm run dev
```

## Build

```bash
npm run build
```

## Deploy directly to Vercel

You do NOT need VS Code to deploy this project.

### Option A — GitHub + Vercel

1. Create a GitHub repository.
2. Upload the contents of this folder to the repository.
3. Open Vercel and choose **Add New → Project**.
4. Import the GitHub repository.
5. Vercel should detect Vite automatically.
6. Use:
   - Build command: `npm run build`
   - Output directory: `dist`
   - Install command: `npm install`
7. Deploy.

`vercel.json` is included so React Router routes work on direct page refreshes.

### Option B — Vercel CLI

If you later install Node.js:

```bash
npm install -g vercel
vercel
```

## Demo scope

The current app uses simulated balances, performance, property opportunities, crypto prices and referral commissions. The 5% Daily Growth figure is explicitly a demo projection and is not presented as a guaranteed real-world return.

No real money movement, custody, investment execution, KYC/AML processing or payment processing is included.

## Next production layers

- Backend API
- PostgreSQL
- Authentication/session service
- Role-based admin permissions
- Transaction ledger
- Wallet/payment integrations
- Market-data integrations
- Audit logging
- Notifications
- Production security and compliance architecture
