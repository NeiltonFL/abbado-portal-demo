# Abbado Client Portal — Founders Law (Demo)

Interactive demo of the client-facing portal for Founders Law.

## Run Locally

```bash
npm install
npm run dev
```

Opens at http://localhost:3001

## Deploy to Vercel

1. Push this repo to GitHub
2. Go to [vercel.com](https://vercel.com) → New Project → Import this repo
3. Framework: Vite (auto-detected)
4. Click Deploy

No environment variables needed for the demo.

## What You're Looking At

This is the client portal — what TechVenture Inc. (Jamie Park, CEO) sees when they log into Founders Law's client portal.

**Try these things:**
- **Login flow** — Enter any email, click "Send Login Link", then click "Continue (Demo)" to enter
- **Dashboard** — Outstanding balance, entity count, compliance tasks, recent documents
- **Invoices** — Click any invoice to see full line items (attorney name, hours, rate, amount), payment history, and the "Pay Now" button
- **Entities** — TechVenture Inc. (DE corp) and TechVenture IP Holdings LLC (DE LLC) with officers, jurisdictions, and upcoming filings
- **Documents** — All documents shared by the firm with download buttons
- **Conversations** — Matter-scoped threads grouped by matter. Click "Cap Table Discussion" to see a real conversation with Sarah Chen, Marcus Williams, and Priya Patel. File attachments visible. Click "New Conversation" to see the matter-picker modal.
- **Sign Out** — bottom of sidebar, returns to login

## Tech

- React 18 + Vite
- Zero dependencies beyond React
- Founders Law brand: Cream #FCF8F1, Dark Green #213B2B, Green #3F7653
