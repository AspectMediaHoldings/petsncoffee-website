# Pets & Coffee — petsncoffee.com

Static landing page for the Pets & Coffee Etsy shop.
Aspect Media Holdings, LLC | Marianna, FL

## Stack

Vanilla HTML + CSS. No build step. Deploy to Netlify.

## Deploy blockers

Before going live, all four items below must be complete:

1. OG image — 1200x630px crop from hero mockup, saved as `/assets/og-image.jpg`
2. Logo SVG — from Meghan, saved as `/assets/logo.svg`
3. Favicon — 32x32px saved as `/assets/favicon-32.png`, 180x180px saved as `/assets/apple-touch-icon.png`
4. Image optimization — all four images in `/assets/images/` must be compressed (see runbook)

## Image optimization (required before deploy)

Source images were copied at full resolution. Run each through Squoosh (squoosh.app) before deploy.

| File | Current size | Target | Settings |
|------|-------------|--------|---------|
| hero-golden-sand-dune.jpg | ~280KB | under 200KB | MozJPEG 80%, resize to 800x800 max |
| breed-german-shepherd.jpg | ~391KB | under 80KB | MozJPEG 80%, resize to 800x800 max |
| breed-rottweiler.jpg | ~205KB | under 80KB | MozJPEG 80%, resize to 800x800 max |
| breed-dachshund-brown.jpg | ~214KB | under 80KB | MozJPEG 80%, resize to 800x800 max |

Total page weight target: under 500KB

## Local preview

Open index.html in a browser. No server required for basic review.
For accurate header testing, use `npx serve .` or `netlify dev` locally.

## Deploy runbook

See: `C:\claude-workspace\petncoffee\output\landing-page-deploy-runbook.md`

## Kit form

Replace the placeholder form in index.html with the Kit inline embed code.
See TODO comment block in index.html for exact instructions.

## Pinterest verification

Replace `PINTEREST-CLAIM-CODE-PLACEHOLDER` in the meta tag in index.html with
the actual code from Pinterest Business Hub after creating the business account.
