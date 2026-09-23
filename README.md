# Tremenburger

A static Astro landing page for Tremenburger, adapted from the supplied café reference. The page includes a responsive layout, menu filters, product detail dialogs, and a swipeable food gallery.

## Local development

Use Node.js 22.12 or newer.

```sh
npm ci
npm run dev
```

Build and preview the production site:

```sh
npm run build
npm run preview
```

## Deploy on Vercel

Push this folder as the root of a GitHub repository, then import that repository in Vercel. Vercel detects Astro and uses `npm run build` with `dist` as the output directory. This static site needs no adapter, environment variables, or `vercel.json`.

Menu names, prices, and contact copy are illustrative placeholders to replace with real business information before publishing. Food images were generated for this project.
