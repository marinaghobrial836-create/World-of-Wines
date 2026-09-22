# World of Wine — Free Static Website

This is a free/static version of the supplied World of Wine site.

## Easiest free hosting: GitHub Pages

1. Create a free GitHub account at https://github.com/
2. Create a new **public** repository, for example `world-of-wine`.
3. Upload `index.html`, `styles.css`, and `script.js`.
4. Open the repository's **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Choose `main` and `/ (root)`, then Save.
7. GitHub will give you a free `github.io` website address.

## Products

The supplied JavaScript originally requested `/api/products`, which requires a server. This version removes that paid/server dependency and reads the Google Sheet directly using its public CSV endpoint.

Your sheet must be published to the web:
Google Sheets → File → Share → Publish to web → choose the correct sheet → CSV → Publish.

The first row should contain:
Category, Type, Brand, Product, Inventory, Price, Size

The spreadsheet ID and GID from the supplied code are already in `script.js`.

## Important

The checkout in this free version is a **demo checkout**. It does not process payment or place a real liquor order. A real alcohol-commerce site needs an appropriate compliant ordering/payment/age-verification setup.
