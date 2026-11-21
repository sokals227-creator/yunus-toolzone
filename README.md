# ToolZone starter website

A lightweight, SEO-friendly static website starter for an all-in-one online tools platform.

## Included working tools
- Word Counter
- Case Converter
- JSON Formatter & Validator
- Base64 Encoder / Decoder
- URL Encoder / Decoder
- Percentage Calculator
- Age Calculator

## Run locally
Open `index.html` in a browser, or run a local static server from this folder:
`python -m http.server 8000`
Then visit `http://localhost:8000`.

## Deploy free with Netlify
1. Create a GitHub repository and upload the contents of this folder.
2. In Netlify, choose Add new site > Import an existing project.
3. Connect your GitHub repository.
4. Build command: leave blank. Publish directory: `.`.
5. Deploy.

## Before publishing
- Replace `https://YOUR-DOMAIN.com` in `index.html`, tool pages, `robots.txt`, and `sitemap.xml` with your real domain.
- Add your real contact email and complete/review the Privacy Policy.
- Add your Adsterra ad code only after Adsterra approves your site and provides the code. Replace the visible Advertisement placeholders with the supplied code.
- Test every tool on desktop and mobile.
- Connect Google Search Console and submit `/sitemap.xml`.

## Important
This is the first working foundation, not a finished large-scale platform. More tools and a secure admin/content management system can be added in later phases. Do not put private API keys or passwords in frontend JavaScript.
