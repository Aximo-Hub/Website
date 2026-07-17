# Aximo — website

Marketing website for **Aximo**, an advisory and execution firm in Nairobi, Kenya, taking companies and investors from decision to result in East Africa.

## Run it
Open **`index.html`** in a browser. No build step, no dependencies, no server required — everything loads from this folder.

## Files
- `index.html` — the site entry point (open this).
- `Aximo.dc.html` — the source design component (edit this; `index.html` is a copy of it).
- `support.js` — the runtime that renders the component (do not edit).
- `assets/` — logo marks, the Nairobi hero photo, and team portraits.
- `llms.txt` — a plain-text summary for AI assistants and answer engines (AI SEO).
- `robots.txt`, `sitemap.xml` — search-engine crawl and indexing hints.

## Pages
Single-page app with in-site navigation: Home, Services, About, Work with us, Contact, Privacy policy, Terms and agreement.

## Editing content
- **Text and colours:** click directly in the preview to edit.
- **Team:** photos in `assets/team-*.png`; names, roles, bios, and LinkedIn links are in the "The people accountable" section of `Aximo.dc.html`.
- **Contact details:** email `hello@aximohub.com`, phone/WhatsApp `+254 716 688 988`, socials `@aximohub`.
- After editing `Aximo.dc.html`, refresh `index.html` (it is a standalone copy — re-copy if you change the source).

## SEO / AI discoverability
- Rich meta tags, Open Graph, and Twitter cards are in the document head.
- Structured data (JSON-LD): Organization, WebSite, ProfessionalService with all seven services, and an FAQ.
- `llms.txt` gives AI assistants a clean, quotable summary of who Aximo is and what it does.

## Still to supply
- Real office street address for the Contact page.
- Confirm/adjust team roles and bios if needed.
