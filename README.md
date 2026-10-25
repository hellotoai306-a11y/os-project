# ext4 Explorer

Static, dependency-free web app (one HTML file in `public/`). No build step.

## Deploy on Vercel

**Option A: CLI**
```
npm i -g vercel
cd ext4-explorer
vercel --prod
```
Accept the defaults (Framework: Other). Vercel serves the `public/` folder (set in vercel.json).

**Option B: GitHub**
1. Push this folder to a GitHub repo.
2. In Vercel: Add New > Project > import the repo.
3. Framework Preset: Other. Leave build command empty. Deploy.

## Run locally
```
npx serve public
```
