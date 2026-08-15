# Ganesh Chaturthi 2026 — Invite Website

A single-page site for the Ganesh Chaturthi celebration at Gorai Shivai CHS Ltd (14–15 Sep 2026).

## Deploy on Vercel (2 minutes, no account setup beyond signup)

**Option A — Drag & drop (fastest, no CLI):**
1. Go to https://vercel.com/new and log in.
2. Click **"Deploy"** → choose **"Upload"** / drag the `index.html` file (and this folder) into the browser window.
3. Vercel auto-detects it as a static site — click **Deploy**. You'll get a live `.vercel.app` link in ~20 seconds.

**Option B — Vercel CLI:**
```bash
npm i -g vercel      # one-time install
cd ganesh-site
vercel               # follow prompts, accept defaults (static site)
vercel --prod        # promote to production URL
```

**Option C — GitHub:**
1. Push this folder to a new GitHub repo.
2. On vercel.com → **New Project** → import that repo → Deploy (no build settings needed, it's plain HTML).

No framework, build step, or environment variables required — it's a single static `index.html`.
