# ai-websites

This folder contains all client website builds, managed as one repository.

## Folder structure

```
ai-websites/
├── README.md          ← you are here
├── pipeline.md        ← live deal tracker for all prospects
├── drummonds/
│   ├── facts.md       ← verified facts, single source of truth
│   └── index.html     ← the built site
└── redmount-trust/
    ├── facts.md       ← verified facts, single source of truth
    └── index.html     ← the built site
```

Each client gets its own subfolder. Everything for that client — HTML, CSS, JS, images, and facts.md — lives inside it. Nothing is shared between client folders.

## What goes in a client folder

- **index.html** — the complete site (currently single-file builds with CSS and JS embedded)
- **facts.md** — verified information about the business (see below)
- Any assets (images, fonts) if added later go in an `assets/` subfolder

## What facts.md is for

`facts.md` is the single source of truth for every confirmed detail about a client: contact information, services, people, affiliations, and project status.

**Why it matters:** when editing a site weeks or months later, it is easy to accidentally introduce wrong details — a phone number misremembered, a service slightly reworded, a statistic invented to fill a gap. `facts.md` prevents this. Before editing any site, read its `facts.md` first. If a detail is not in `facts.md`, do not put it in the site — use `[ADD DETAIL HERE]` as a placeholder and confirm it with the client.

When new confirmed facts arrive (a client confirms their email address, a price is agreed, a site goes live), update `facts.md` immediately so it stays current.

## How to use pipeline.md

`pipeline.md` tracks every prospect — contacted or not — so no lead gets lost. Update it after every client interaction:

- Change the Status column when a deal moves forward
- Fill in Price Quoted when a number is sent
- Update Last Contact and Next Action after every touchpoint
- Add a new row the moment a new prospect is identified
