# Merhi Homekey

Demo website for **Merhi Homekey | Beirut Real Estate** (Instagram [@merhi.homekey](https://www.instagram.com/merhi.homekey/)). Apartments in Beirut & Lebanon · Buy · Sell · Rent · WhatsApp 70 868 757.

> The three listings are **sample content** to show the concept. Replace them with Merhi Homekey's own properties and photos before going live.

## Pages
- **Home**: hero with search (buy/rent, location, budget), featured properties, spotlight, areas, services, "List your property" form (sell or rent out), contact
- **Properties** (`#/properties?deal=sale|rent&area=...&max=...`): filters and sorting
- **Property page** (`#/p/<id>`): gallery with full-screen viewer, key facts, description, highlights, Google Maps link, similar properties
- **Saved** (`#/saved`): properties the visitor hearted (kept in their browser)

## Editing
In `index.html`: `CONFIG` (site address, WhatsApp, Instagram) and `PROPS` (one object per listing, `deal: 'sale'` or `'rent'`). Photos go in `img/` as `name.webp` and `name-s.webp`.

## Run / deploy
No build step. Serve the folder or import the repo into Vercel / Cloudflare Pages.
