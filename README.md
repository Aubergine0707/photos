# Photo Gallery

A minimalist photography portfolio, free on GitHub Pages.

## Quick Deploy

```bash
cd photo-portfolio
git init
git add .
git commit -m "🎞️ Photo gallery"
git remote add origin https://github.com/YOUR_USERNAME/photos.git
git push -u origin main
```

Then go to GitHub repo → **Settings → Pages** → Source: `Deploy from a branch`, branch `main` → `/ (root)`.

Your site will be at: `https://YOUR_USERNAME.github.io/photos`

## Edit Photos

Open `index.html` and find the `const photos = [...]` array. Each entry:

```js
{ file: "filename.jpg", category: "landscape" }
```

Categories: `landscape` | `portrait` | `street` | `bw`

## Add / Remove Photos

Just drop images in `photos/` and update the array in `index.html`. That's it.

## Custom Domain (Optional)

Create a `CNAME` file in the repo root with `photo.yourdomain.com`, and add a CNAME DNS record.

---

📸
