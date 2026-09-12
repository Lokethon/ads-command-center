# Ads Command Center

Interactive ads performance dashboard for Aravind Laboratories — spend, ad revenue,
ROAS/ACOS, and campaign explorer across Amazon, Flipkart, Meesho, Blinkit, Purplle,
Snapdeal and Swiggy Instamart.

This repo is set up to serve `index.html` directly via **GitHub Pages**.

## Publish it (one-time setup)

1. Create a new repository on GitHub (public, no README/license needed — this folder
   already has one).
2. From this folder, run:

   ```bash
   git init
   git add .
   git commit -m "Add Ads Command Center dashboard"
   git branch -M main
   git remote add origin https://github.com/<your-username>/<your-repo>.git
   git push -u origin main
   ```

3. On GitHub: **Settings → Pages → Build and deployment → Source: Deploy from a
   branch → Branch: main / (root) → Save**.
4. Your live site appears in a minute or two at:
   `https://<your-username>.github.io/<your-repo>/`

## Updating it later

Replace `index.html` with the new version, then:

```bash
git add index.html
git commit -m "Update dashboard"
git push
```

GitHub Pages redeploys automatically on every push to `main`.
