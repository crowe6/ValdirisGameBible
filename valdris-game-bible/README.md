# Valdris — Game Design Bible

A fully interactive game design document for **Valdris**, a medieval fantasy Roblox game.

## How to open locally

Just double-click `index.html` — it opens in any web browser. No server needed.

## What's inside

- `index.html` — The full interactive game bible (single file, self-contained)
- `README.md` — This file + GitHub setup instructions

---

## How to connect this to GitHub

Follow these steps exactly:

### Step 1 — Install Git
Download and install Git from https://git-scm.com/downloads
During install, leave all options as default.

### Step 2 — Create a GitHub account
Go to https://github.com and sign up (free).

### Step 3 — Create a new repository on GitHub
1. Click the **+** button (top right) → **New repository**
2. Name it: `valdris-game-bible`
3. Set it to **Public** (so GitHub Pages can host it for free)
4. Do NOT check "Add a README" — we already have one
5. Click **Create repository**
6. Copy the repository URL — it will look like:
   `https://github.com/YOUR-USERNAME/valdris-game-bible.git`

### Step 4 — Open a terminal / command prompt
- **Windows**: Press Win + R, type `cmd`, press Enter
- **Mac**: Press Cmd + Space, type `terminal`, press Enter

### Step 5 — Navigate to your project folder
Type this (replace the path with where you saved this folder):
```
cd path/to/valdris-game-bible
```

### Step 6 — Initialize and push to GitHub
Run these commands one at a time:
```
git init
git add .
git commit -m "Initial commit — Valdris game bible"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/valdris-game-bible.git
git push -u origin main
```
Replace `YOUR-USERNAME` with your actual GitHub username.

---

## How to host it live (free) with GitHub Pages

Once your code is on GitHub:

1. Go to your repository on GitHub
2. Click **Settings** → scroll down to **Pages**
3. Under **Source**, select **main** branch → **/ (root)** → click **Save**
4. Wait 1–2 minutes
5. Your site will be live at:
   `https://YOUR-USERNAME.github.io/valdris-game-bible`

Share that link with anyone — it's a fully hosted interactive webpage.

---

## How to update the page later

When you make changes to `index.html`, run:
```
git add .
git commit -m "Updated [what you changed]"
git push
```
GitHub Pages will automatically update within a minute.
