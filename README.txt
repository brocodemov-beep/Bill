SHOPMITRA HTML / CSS / JAVASCRIPT STARTER

Files:
- index.html       Main app structure
- style.css        Responsive visual styling
- app.js           App interactions and local browser storage
- manifest.webmanifest
- sw.js            Basic app-shell cache for PWA
- README.txt       This guide

Run:
1. Extract the ZIP.
2. Open the folder in Visual Studio Code.
3. For best results, install the "Live Server" extension.
4. Right-click index.html and choose "Open with Live Server".

Or use a local static server. The service worker/PWA requires localhost or HTTPS, not file://.

Features in this starter:
- Dashboard, product search/category filter, quick-sale cart
- Add/edit/delete products and stock
- Cash, UPI, card, credit and partial sale payments
- Credit collection against the existing sale (not counted as a second sale)
- Expense recording
- Analytics, low stock and product performance
- English/Tamil toggle for navigation and selected labels
- Shop profile and JSON export backup
- Responsive desktop and mobile layout

IMPORTANT LIMITATIONS:
- This is a local demo, not production-ready accounting software.
- Data is stored in this browser's localStorage only.
- Demo records are seeded on first run.
- Supabase login/database/RLS and multi-device sync are not configured.
- Google Drive OAuth backup/restore is not implemented; export downloads JSON.
- PIN/passkeys, voice entry, customer directory, refunds, full audit logs and reliable offline sync are not implemented.
- Do not use this demo as the only copy of real shop transactions.
