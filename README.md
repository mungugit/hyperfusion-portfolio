# Hyperfusion LLC Portfolio Website

Static portfolio website prepared for direct deployment to Vercel.

## Run locally

Open `index.html` directly, or run a local server:

```bash
python3 -m http.server 3000
```

Then open http://localhost:3000

## Deploy to Vercel

### Option A — GitHub + Vercel
1. Create a new GitHub repository.
2. Upload all files in this folder.
3. In Vercel choose **Add New → Project**.
4. Import the GitHub repository.
5. Framework Preset: **Other**.
6. Build Command: leave empty.
7. Output Directory: leave empty.
8. Deploy.

### Option B — Vercel CLI
```bash
npm i -g vercel
vercel
```

## Before publishing
- Replace `hello@hyperfusion.mn` with the actual company email.
- Add real project URLs if desired.
- Add company address / phone / social links if needed.
- Add logo assets if Hyperfusion has an official logo.
