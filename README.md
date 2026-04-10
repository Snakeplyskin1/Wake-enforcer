# Wake Up Enforcer — PWA

A mobile alarm app that forces you to answer trivia questions (math, physics, space, jet engines, aerospace) before it silences.

## How to deploy on GitHub Pages (free, ~5 minutes)

### Step 1 — Create a GitHub account
Go to github.com and sign up if you don't have one.

### Step 2 — Create a new repository
1. Click the "+" icon → "New repository"
2. Name it: `wake-enforcer`
3. Set it to **Public**
4. Click "Create repository"

### Step 3 — Upload the files
1. On your new repo page, click "uploading an existing file"
2. Drag and drop ALL files from this zip:
   - index.html
   - manifest.json
   - sw.js
   - icons/icon-192.png
   - icons/icon-512.png
3. Click "Commit changes"

### Step 4 — Enable GitHub Pages
1. Go to your repo → Settings → Pages (left sidebar)
2. Under "Branch", select `main` and click Save
3. Wait ~60 seconds, then your app is live at:
   `https://YOUR-USERNAME.github.io/wake-enforcer/`

### Step 5 — Install on your Android phone
1. Open Chrome on your Android phone
2. Go to your GitHub Pages URL
3. Tap the 3-dot menu → "Add to Home screen"
4. Tap "Add" — it installs like a real app!

## Important notes

- **Keep the app open on screen** while the alarm is counting down.
  PWAs can't fire background alarms like native apps — the screen needs to be on.
- Workaround: before bed, open the app, set your alarm, plug in your phone,
  and set your screen timeout to "Never" in Android display settings just for overnight.
- Volume must be turned up before you set the alarm.

## Files
- `index.html` — the entire app
- `manifest.json` — makes it installable as a PWA
- `sw.js` — service worker (enables offline use)
- `icons/` — app icons for home screen
