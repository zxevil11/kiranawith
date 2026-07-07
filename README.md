# Kirana Store

A neighborhood grocery store web app with product browsing, cart, WhatsApp checkout, and a password-protected admin panel.

## Quick Start

```bash
npm install
npm run dev
```

Open http://localhost:5173

## Admin Panel

Go to `/admin` and enter the password: **kirana123**

To change the password, edit `src/lib/adminAuth.ts` → `ADMIN_PASSWORD`.

## Features

- Browse 21 products across Vegetables, Fruits, Dairy, Staples, Snacks
- Search and category filters
- Tap any product to open a detail view with quantity selector
- Cart with WhatsApp checkout (sends order to +91 91477 17491)
- Admin panel: add/edit/delete products, stock management, sales history
- Direct image upload in admin (stored as base64)
- All data saved in browser localStorage — no backend required

## Scripts

| Command | What it does |
|---------|-------------|
| `npm run dev` | Start dev server at http://localhost:5173 |
| `npm run build` | Build for production into `dist/` |
| `npm run preview` | Preview the production build |
