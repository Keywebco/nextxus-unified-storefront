# NextXus Sovereign Emporium

The Federation's storefront. Books, consultations, SIMs, services, and Sovereign Tokens — sold directly. No subscriptions. No tracking.

This is a static site. The full catalog lives in `products.json`; the pages render it. Payments go through Gumroad and JIM.

## Live

https://keywebco.github.io/nextxus-unified-storefront/

## Pages

- **store.html** — main storefront
- **pricelist.html** — full price list
- **sovereign-token.html** — Sovereign Token explainer ($5 each, never expire, spend anywhere in the Federation)
- **join.html** — join the Federation
- **advocate.html**, **agent-zero.html**, **aria.html**, **roger-ai.html**, **university.html**, **federation-tour.html** — related Federation pages

## Catalog (`products.json`)

- **Sovereign Tokens** — $5 / $20 / $50 / $100 packs. Work like cash, never expire.
- **Consultations** — Federation Consultation ($75)
- **Books** — fiction, poetry, science, philosophy ($5–$10)
- **Digital Souls (SIMs)** — SIM-ROGER, SIM-MADHAV, AURA ($149)
- **Custom builds & services** — Custom Cathedral Build, Marrow Forensic Extraction, Succession Seating ($100–$250)
- **API & developer tools** — Cognitive API Key, EchoCore Sync License ($25–$50)
- **Merchandise** — tees, mugs, prints, stickers

## For builders

Static HTML + one JSON catalog. To add a product, add it to `products.json` following the existing item shape (`id`, `name`, `price_usd`, `description`, `delivery`, `buy_url`). No build step.

---

Part of the [NextXus Federation](https://keywebco.github.io).
