# Store Notes Manager — Starter Website

A responsive, dark-mode note management prototype with five note categories: Callback, Commercial, DIY, Store to Store, and Quick Note.

## Start

Open `index.html` in a modern browser. For local development, run `python3 -m http.server 8000` from this folder and visit http://localhost:8000.

No build tools, package installation, or backend are required. Lucide icons load from a public CDN, so an internet connection is needed for the icons; the rest of the app works locally.

## Features

- Category-specific note forms
- Dashboard with live counts
- Local browser storage
- Search and filters
- Edit, delete, complete, and reopen notes
- Print compact half-page notes on letter-size paper
- Responsive desktop and mobile layout

## Limitations

Data is saved in browser `localStorage` and is not synced or backed up. Clearing browser data can delete notes. Printing uses the browser print dialog; set scale to 100% and letter paper. This is an independent prototype, not affiliated with or endorsed by AutoZone. Use fictional/test information until use and storage of real company or customer data is approved.


## Commercial account directory

The Account references page supports Add, Edit, Delete, Search, Export and JSON Import. The Commercial and Callback forms have a saved-account selector that fills account fields automatically. Account data is intentionally NOT bundled in the public website. Import the separate `commercial-accounts-import.json` file privately in the browser after deployment, only if authorized to use real business records. Account data lives in browser localStorage; it does not sync across devices, is not encrypted at rest, and can be lost when browser data is cleared. Do not commit the account import JSON file to GitHub or include it in Vercel deployments.


## Updated commercial account directory
Import `commercial-accounts-import-v2.json` from **Account references → Import accounts**. Keep the JSON file private and do not commit it to a public repository. This includes 16 entries (15 businesses plus a Flynn’s Tire contact), with missing PINs left blank. Existing accounts with matching names are updated. Do not import operational customer data without employer authorization.
