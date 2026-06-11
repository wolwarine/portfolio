# Karan Tewari — Personal Portfolio

Personal portfolio website hosted on GitHub Pages.

## 🚀 Deploying to GitHub Pages

### Option A — User/Org site (recommended)
1. Create a repo named exactly `wolwarine.github.io`
2. Push all files to the `main` branch root
3. GitHub Pages will automatically serve `index.html` at `https://wolwarine.github.io`

### Option B — Project site
1. Create any repo (e.g. `portfolio`)
2. Push files to `main`
3. Go to **Settings → Pages → Source** → select `main` branch, `/ (root)`
4. Site will be live at `https://wolwarine.github.io/portfolio`

## 🌐 Custom Domain Setup

1. In your domain registrar's DNS, add:
   ```
   Type  Name   Value
   A     @      185.199.108.153
   A     @      185.199.109.153
   A     @      185.199.110.153
   A     @      185.199.111.153
   karantewari.com www    portfolio.github.io
   ```
2. Edit the `CNAME` file in this repo — replace the placeholder with your actual domain:
   ```
   yourdomain.com
   ```
3. In **Settings → Pages → Custom domain**, enter your domain and hit Save
4. Check **Enforce HTTPS** once the certificate is provisioned (can take ~10 min)

## 📁 Files

| File | Purpose |
|------|---------|
| `index.html` | The entire site — single self-contained file |
| `CNAME` | Custom domain for GitHub Pages |
| `README.md` | This file |

## 📸 Adding Your Photo

In `index.html`, find the `about-photo-placeholder` div and replace it with:
```html
<img src="photo.jpg" alt="Karan Tewari" />
```
Then drop your `photo.jpg` in the repo root.

## ✏️ Updating Content

All content is in `index.html`. Search for the section you want to update:
- Hero tagline → search `hero-tagline`
- Projects → search `projects-grid`
- Certifications → search `certs-grid`
- Skills → search `skills-grid`
