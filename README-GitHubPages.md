# Tail Trailz — GitHub Pages Deployment

This is a **ready-to-publish** static site. No build step, no frameworks.

## Quick Deploy (Browser only)

1. Go to https://github.com/new and create a repository named **tailtrailz** (public).
2. Click **Add file → Upload files**, and upload all files from this folder (or just upload the ZIP and use **Extract** in the GitHub web UI alternative).
3. Commit the changes.
4. Open **Settings → Pages**.
   - **Source**: Deploy from a branch.
   - **Branch**: `main` (or `master`) and folder `/root`.
   - Click **Save**.
5. Your site will be live at: `https://<your-username>.github.io/tailtrailz/`

## Customising

- Replace `assets/logo.svg` with your own logo.
- Update contact details in `contact.html` and `site footer`.
- Edit prices in `pricing.html`.
- Edit store products in `data/products.json`. The **Order via WhatsApp** button pre-fills a message to +44 7801 598 085 — change this if needed.

## Netlify (optional)

You can also drag-and-drop this folder at https://app.netlify.com/drop for an instant live URL.

## Notes

- The store is a **catalog + WhatsApp order** flow (no payment gateway). You can later embed Ecwid/Shopify Buy Buttons or add PayPal once accounts are set up.
- All pages are pure HTML/CSS/JS for maximum GitHub Pages compatibility.