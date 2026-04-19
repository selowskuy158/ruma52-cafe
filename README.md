# Ruma 52 — Cafe Website

A premium, single-page website for Ruma 52 Home Cafe, Lippo Karawaci.

## Deploy to Vercel

This is a static HTML site — no build step needed.

### Option 1: Vercel CLI
```bash
npm i -g vercel
vercel --prod
```

### Option 2: Vercel Dashboard
1. Go to [vercel.com](https://vercel.com)
2. Click "Add New Project"
3. Drag and drop this folder, or connect your GitHub repo
4. Vercel will auto-detect it as a static site and deploy instantly

## ⚠️ Image Note

Images are currently loaded from temporary signed URLs. For a permanent production deployment, you should:

1. Upload all cafe photos to a CDN (e.g. Cloudflare Images, AWS S3, or Vercel Blob)
2. Replace the long signed URLs in `index.html` with your permanent CDN URLs

Search for `claudeusercontent.com` in `index.html` to find all image references — there are about 15 of them.

## Stack
- Pure HTML/CSS/JS — no framework, no build tools
- Google Fonts: Cormorant Garamond, DM Sans, Josefin Sans
- Fully responsive (mobile + desktop)
- Smooth scroll animations, parallax hero, tabbed menu

## Sections
1. Hero (full-height, centered CTA)
2. About
3. Menu (tabbed: Signature, Coffee, Matcha, Tea, Pastry)
4. Gallery
5. Experience pillars
6. Visit / Location
7. Testimonials (auto-scroll carousel)
8. Instagram
9. Footer
