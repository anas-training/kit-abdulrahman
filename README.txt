
WELLSPRING KIDS — Child Kit Starter (Abdulrahman)
===============================================

What this is
------------
A ready-to-deploy mini-site for one child with:
- Index (dashboard)
- Interactive story (flipbook with Turn.js CDN)
- Games launcher (links)
- Video embed page
- Downloads page (worksheets & certificate PDFs)
- config.js for per-child personalization
- assets/ with 5 demo story pages (PNG)
- files/ with demo worksheets/certificate PDFs

How to deploy (GitHub Pages)
----------------------------
1) Create a new public repo named: kit-abdulrahman
2) Upload all files/folders from this package to the repo root
3) In repo Settings → Pages → Select "Deploy from branch" / main / root → Save
4) Wait 1–2 minutes, Pages URL appears: https://<your-user>.github.io/kit-abdulrahman/
5) Open it — the dashboard should load. Story flips pages.

Customize
---------
- Open config.js and replace URLs (video, song, game links, Drive file links).
- Replace assets/page*.png with your exported Canva story pages (1600x1000 recommended).
- Replace files/worksheets.pdf and files/certificate.pdf with real exports.
- Update text labels in HTML if needed; most content is driven by config.js.

Notes
-----
- Turn.js and jQuery are loaded via CDN. Ensure internet connectivity.
- For iOS download behavior, provide ZIP as alternative if needed.
- When cloning for another child, duplicate the repo and change config.js and assets.
