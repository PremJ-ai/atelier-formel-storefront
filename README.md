# Atelier Formel — Menswear Storefront

A responsive editorial-style clothing storefront concept for menswear, built around four distinct collections:

- Formal shirts
- Casual and checked shirts
- Formal trousers
- Chinos

## Live demo

Once the GitHub Pages deployment finishes, the storefront is available at:

https://premj-ai.github.io/atelier-formel-storefront/

## What's included

The site includes collection-specific pages, sorting/filter controls, search, a browser-local demo cart and wishlist, outfit pairing, responsive product grids, and paced motion with reduced-motion support.

The static HTML/CSS/JavaScript storefront is at the repository root and is what GitHub Pages deploys. The component-based Next.js implementation is retained in `next-app/`.

## Run the Next.js version locally

Requires Node.js 22 or a compatible current Node.js release.

```bash
cd next-app
npm install
npm run dev
```

Open http://localhost:3000.

The `/api/products` route belongs to the Next.js app and requires a Node.js host. GitHub Pages only serves the static storefront demo; the demo cart does not process payments or place real orders.

## Project structure

```
.
├── index.html
├── formal-shirts.html
├── casual-shirts.html
├── formal-trousers.html
├── chinos.html
├── styles.css
├── script.js
├── next-app/              # Next.js app and products API
└── .github/workflows/     # Pages deployment and Next.js build check
```
