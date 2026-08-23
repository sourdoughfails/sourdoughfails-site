# SourdoughFails – Prototype Site

Simple multi-page static website for **sourdoughfails.com**.

## Pages
- `index.html` – Home with intro + featured fails
- `gallery.html` – Fail gallery (placeholder cards)
- `about.html` – About the project + future “share your fail” section

## Design notes
- Warm bakery palette (cream, wheat, soft browns)
- Clean Inter font
- Mobile-friendly with sticky nav and simple hamburger menu
- Photo placeholders ready to replace with real images
- Easy to expand later (more pages, individual fail detail pages, form, etc.)

## How to put it on GitHub Pages

1. Create a new **public** repository (e.g. `sourdoughfails`).
2. Upload all the files in this folder (keep the same structure: `index.html`, `gallery.html`, `about.html`, `css/`, etc.).
3. Go to the repo **Settings → Pages**.
4. Under “Source”, choose **Deploy from a branch**.
5. Select branch `main` (or `master`) and folder `/ (root)`, then Save.
6. Wait a minute or two. Your site will be live at `https://YOUR-USERNAME.github.io/sourdoughfails/` (or similar).

### Custom domain (sourdoughfails.com)

1. In the same Pages settings, under “Custom domain”, enter `sourdoughfails.com` (and optionally `www.sourdoughfails.com`) and Save.
2. GitHub will show the DNS records you need.
3. At your domain registrar, add:
   - For the apex (`sourdoughfails.com`): A records pointing to GitHub’s IPs  
     (currently 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153)
   - For `www`: a CNAME record pointing to `YOUR-USERNAME.github.io`
4. Wait for DNS to propagate (can take a few minutes to a few hours). GitHub will then issue a free HTTPS certificate.

## Editing the site
- Replace the gray “Photo placeholder” boxes with real `<img>` tags.
- Update the short descriptions in the cards.
- Tweak colors in `css/styles.css` (look for the `:root` variables at the top).
- Add more pages by copying an existing HTML file and updating the nav links.

This is intentionally small and easy to change. We can refine the visuals, switch to a single long page, add a form, or build individual fail detail pages whenever you’re ready.
