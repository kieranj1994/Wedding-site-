# Wedding Website (GitHub Pages Starter)

A clean, elegant, mobile‑friendly wedding website you can host **for free** with GitHub Pages.

## Quick start (no coding needed)
1. Create a new repo on GitHub (public): e.g. `wedding-site`.
2. Upload these files to the repo (or drag the whole zip).
3. Go to **Settings → Pages**:
   - **Build and deployment**: *Deploy from a branch*
   - **Branch**: `main` and folder `/ (root)` → **Save**
4. Wait ~1 minute, then visit your Pages URL (e.g. `https://USERNAME.github.io/wedding-site/`).

## Use your own domain
1. Go to **Settings → Pages → Custom domain**, enter your domain (e.g. `www.ourwedding.co.uk`). This will create a `CNAME` file for you.
   - Alternatively, edit the included `CNAME` file with your domain and commit.
2. Update your DNS with your registrar:
   - **Subdomain (e.g. `www`)**: Add a **CNAME** record pointing to `USERNAME.github.io`.
   - **Root/apex**: Add **A** records for GitHub Pages IPs:
     - `185.199.108.153`
     - `185.199.109.153`
     - `185.199.110.153`
     - `185.199.111.153`
3. Back in GitHub, keep "Enforce HTTPS" checked. DNS can take time to propagate.

## Edit the content
- Open `index.html` and replace names, dates, locations, and section text.
- Replace the images in `images/` with your photos (keep filenames or update paths).
- Swap the RSVP button link to your Google Form.

## Optional
- Create a Google Form for RSVPs and paste its link in the RSVP button.
- Add a `/.well-known/security.txt` or `robots.txt` if you want.
- Add a `favicon.ico` in the root.

_This template was generated on 2025-08-10._
