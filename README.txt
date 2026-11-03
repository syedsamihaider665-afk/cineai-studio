# CineAI Studio

A responsive static website starter for the CineAI Studio project.

## Files
- `index.html` — responsive prompt builder and imported-video preview
- `manifest.webmanifest` — installable web app metadata
- `sw.js` — basic offline shell caching
- `icons/` — app icons

## Deploy on Cloudflare Pages
1. Upload the contents of this folder to the root of your GitHub repository.
2. In Cloudflare Pages, connect the GitHub repository.
3. Framework preset: None
4. Build command: leave blank
5. Build output directory: `/` or `.` (depending on the dashboard field)
6. Deploy.

## Important limitation
This is a front-end starter. It builds prompts and previews video files that users import. It does **not** generate AI video on its own. Real text-to-video/image-to-video generation requires a video model provider/API and a secure backend. Never put secret API keys in browser-side HTML or JavaScript.
