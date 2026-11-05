# Pantoprazole Evidence Dashboard

A static, single-file website (`index.html`). No build step, no dependencies.

## Run locally
Double-click `index.html`, or run `python3 -m http.server 8000` in this folder and open http://localhost:8000.

## Publish on Netlify
**Drag and drop (fastest):** log in at https://app.netlify.com/drop and drag this whole `pantoprazole-site` folder onto the page. You get a live link in seconds.

**Via GitHub:** push this folder to a repo, then in Netlify choose Add new site > Import from Git. Leave Build command empty and set Publish directory to `.` (or the folder holding index.html).

## Publish on Vercel
1. Go to https://vercel.com/new and import a GitHub repo containing this folder, or install the CLI with `npm i -g vercel`.
2. From inside this folder run `vercel` and accept the defaults (Framework: Other, no build command, output directory `.`).
3. Run `vercel --prod` for the production URL.

## Publish on GitHub Pages (alternative)
Push to a repo, then Settings > Pages > Deploy from branch > `main` / root.

## Updating data
All chart and table data sits in the `D` object near the bottom of `index.html`. Edit values there and re-deploy. References are in the "Methods, limitations and references" section.

## Note
Figures are transcribed from the cited sources. Items marked "unavailable" were not collected. Verify against full texts before academic or clinical use.
