# Finally You — Phone App Setup (10 minutes, one time)

This folder is a complete web app. Once hosted, it installs on your iPhone
like a regular app and works offline.

## Step 1 — Put it online (GitHub Pages, free)

1. Go to **github.com** and sign up (free) if you don't have an account.
2. Click **+** (top right) → **New repository**. Name it `finally-you`,
   leave it **Public**, check "Add a README file", click **Create repository**.
   (Public only means the files are technically reachable at your URL — the
   address is obscure, it isn't listed anywhere, and your answers are NOT
   stored here; they stay on your phone.)
3. On the repo page click **Add file → Upload files**. Drag ALL files from
   this folder in (index.html, manifest.json, sw.js, and the 3 icon files).
   Click **Commit changes**.
4. Go to **Settings → Pages** (left sidebar). Under "Branch" choose
   **main** and **/ (root)**, click **Save**.
5. Wait ~2 minutes, refresh the page — it shows your site URL, like:
   `https://YOURNAME.github.io/finally-you/`

## Step 2 — Install on your iPhone

1. Open that URL in **Safari** on your phone.
2. Tap the **Share** button (square with arrow) → **Add to Home Screen** → Add.
3. Open it from your home screen — full screen, works offline after first load.

## Using it

- **Typing is the default** everywhere. Tap the 🎤 button next to any answer
  box to dictate instead (tap ■ to stop). Safari will ask for microphone
  permission the first time. If the in-app mic ever misbehaves, the 🎤 on
  the iPhone keyboard does the same job.
- **Everything saves automatically on your phone** — answers, notes, progress.
  Nothing is uploaded anywhere.
- **Back up occasionally:** More tab → "Backup file (JSON)" — save it to
  Files/iCloud. If you ever clear Safari data or switch phones, restore it
  with "Restore backup". "Export everything (Markdown)" gives you a readable
  document of all your answers.

## Alternative hosting

Netlify: app.netlify.com → free account → "Deploy manually" → drag this
whole folder in → done, same Add to Home Screen afterwards.
