# Monceau farewell page

A single static page for monceau.com.au, built 6 Oct 2026.

## What's here

- `index.html` – the page. Everything is plain HTML and CSS, no build step.
- `img/` – 15 Jana Langhorst photographs (Oct 2020 shoot), resized for the web, plus the wordmark SVGs.
- `fonts/` – the brand's Geometric 212 webfonts, recovered from the old Shopify theme via the Wayback Machine.
- `artifact.html` – a copy of the page body used for the Claude preview link. Not needed for hosting.

## Hosting it on monceau.com.au

Upload the whole folder (keep `index.html`, `img/` and `fonts/` together) to any static host:

- **Netlify Drop** – drag the folder onto https://app.netlify.com/drop, then add `monceau.com.au` as a custom domain and follow the DNS instructions.
- **Cloudflare Pages / GitHub Pages / Vercel** – all work the same way; point the site at this folder.

Then change the domain's DNS from Shopify to the new host. The old Shopify store can be closed once DNS has moved.

## Editing the words

All copy is in `index.html`. Things worth checking before it goes live:

- The dates "2020 – 2025" (top bar and meta tags).
- The line "Some of the drinks we created have found new homes" – name the brands and buyers if you want to.
- The flavour lists under "What we made" were taken from the old shop's product images.
